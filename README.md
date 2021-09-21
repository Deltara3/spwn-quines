# spwn-quines
Quines in SPWN!

By [me](https://github.com/Deltara3):

File name: `deltara3/quine-deltara3-gh-1.spwn`
```rust
d='JC5wcmludCgiZD0nIitkKyInOyIrJC5iNjRkZWNvZGUoZCkp';$.print("d='"+d+"';"+$.b64decode(d))
```
File name: `deltara3/quine-deltara3-gh-2.spwn`
```rust
x=';$.print("x={}{}".fmt([$.display(x), x]))';$.print("x={}{}".fmt([$.display(x), x]))
```
File name: `deltara3/quine-deltara3-gh-3.spwn`
```rust
x='$.print("x=",$.display(x),";",x)';$.print("x=",$.display(x),";",x)
```

By [sertdfyguhi](https://github.com/sertdfyguhi):

File name: `sertdfyguhi/quine-sertdfyguhi-gh-1.spwn`
```rust
x='x={};$.print(x.fmt($.display(x)))';$.print(x.fmt($.display(x)))
```

File name: `sertdfyguhi/quine-sertdfyguhi-gh-2.spwn`
```rust
x='JC5wcmludCgieD0ne30nO3t9Ii5mbXQoW3gsJC5iNjRkZWNvZGUoeCldKSk';$.print("x='{}';{}".fmt([x,$.b64decode(x)]))
```

File name: `sertdfyguhi/quine-sertdfyguhi-gh-3.spwn`
```rust
x=[';$.print("x=",x,x[0])'];$.print("x=",x,x[0])
```

By [camila314](https://github.com/camila314):

File name: `quine-camila314-gh.spwn`
```rust
let a='let a=\'7\';a=a.replace(@string(1+6),a.replace(a[100-4]+a[100-4],a[100-4]+a[100-4]).replace(a[6],"\\\\"+a[6]));$.print(a)';a=a.replace(@string(1+6),a.replace(a[100-4]+a[100-4],a[100-4]+a[100-4]).replace(a[6],"\\"+a[6]));$.print(a)
```

By [Specky](https://github.com/SpeckyYT):

File name: `quine-speckyyt-gh.spwn`
```rust
s='$.print("s=",$.display(s),";",s)';$.print("s=",$.display(s),";",s)
p={p: 'p=',pp: ';$.print(p.p,$.display(p).fmt(p),p.pp)'};$.print(p.p,$.display(p).fmt(p),p.pp)
(e)}("e="+$.display(e)+e)';(e){$.print(e)}("e="+$.display(e)+e)
c=()=>'{};$.print("c=()=>"+c().fmt($.display(c())))';$.print("c=()=>"+c().fmt($.display(c())))
(k){$.print(k+"("+$.display(k)+")")}('(k){$.print(k+"("+$.display(k)+")")}')
y=[(y)=>$.print(y,$.display(y),")")];y[0]('y=[(y)=>$.print(y,$.display(y),")")];y[0](')
(isCool,isFriendly,isSmart){$.print("("+",".join(isCool)+"){"+isFriendly+isSmart+isCool as@string+"".join([isFriendly,isSmart].map(v=>","+$.display(v)))+")")}(['isCool','isFriendly','isSmart'],'$.print','("("+",".join(isCool)+"){"+isFriendly+isSmart+isCool as@string+"".join([isFriendly,isSmart].map(v=>","+$.display(v)))+")")}(')
o={k: ';$.print("o=",o,o.k)'};$.print("o=",o,o.k)
```

By [typicaldev1](https://github.com/typicaldev1):

File name: `quine-typicaldev1-gh.spwn`
```rust
(p,x,d){p(x.fmt(d(x)))}($.print,'(p,x,d){p(x.fmt(d(x)))}($.print,{},$.display)',$.display)
```
