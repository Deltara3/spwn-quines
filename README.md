# spwn-quines
Quines in SPWN!

By [me](https://github.com/Deltara3):

File name: `quine-deltara3-gh.spwn`
```rust
d='JC5wcmludCgiZD0nIitkKyInOyIrJC5iNjRkZWNvZGUoZCkp';$.print("d='"+d+"';"+$.b64decode(d))
```

By [sertdfyguhi](https://github.com/sertdfyguhi):

File name: `quine-sertdfyguhi-gh.spwn`
```rust
x='x={};$.print(x.fmt($.display(x)))';$.print(x.fmt($.display(x)))
```
```rust
x='JC5wcmludCgieD0ne30nO3t9Ii5mbXQoW3gsJC5iNjRkZWNvZGUoeCldKSk';$.print("x='{}';{}".fmt([x,$.b64decode(x)]))
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
```
```rust
p={p: 'p=',pp: ';$.print(p.p,$.display(p).fmt(p),p.pp)'};$.print(p.p,$.display(p).fmt(p),p.pp)
```
```rust
e=';(e){$.print(e)}("e="+$.display(e)+e)';(e){$.print(e)}("e="+$.display(e)+e)
```
```rust
c=()=>'{};$.print("c=()=>"+c().fmt($.display(c())))';$.print("c=()=>"+c().fmt($.display(c())))
```
```rust
(k){$.print(k+"("+$.display(k)+")")}('(k){$.print(k+"("+$.display(k)+")")}')
```
```rust
y=[(y)=>$.print(y,$.display(y),")")];y[0]('y=[(y)=>$.print(y,$.display(y),")")];y[0](')
```
```rust
(isCool,isFriendly,isSmart){$.print("("+",".join(isCool)+"){"+isFriendly+isSmart+isCool as@string+"".join([isFriendly,isSmart].map(v=>","+$.display(v)))+")")}(['isCool','isFriendly','isSmart'],'$.print','("("+",".join(isCool)+"){"+isFriendly+isSmart+isCool as@string+"".join([isFriendly,isSmart].map(v=>","+$.display(v)))+")")}(')
```
```rust
o={k: ';$.print("o=",o,o.k)'};$.print("o=",o,o.k)
```

By [typicaldev1](https://github.com/typicaldev1):

File name: `quine-typicaldev1-gh.spwn`
```rust
(p,x,d){p(x.fmt(d(x)))}($.print,'(p,x,d){p(x.fmt(d(x)))}($.print,{},$.display)',$.display)
```
