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

By [camila314](https://github.com/camila314):

File name: `quine-camila314-gh.spwn`
```rust
let a='let a=\'7\';a=a.replace(@string(1+6),a.replace(a[100-4]+a[100-4],a[100-4]+a[100-4]).replace(a[6],"\\\\"+a[6]));$.print(a)';a=a.replace(@string(1+6),a.replace(a[100-4]+a[100-4],a[100-4]+a[100-4]).replace(a[6],"\\"+a[6]));$.print(a)
```