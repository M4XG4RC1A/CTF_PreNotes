# RSA
n = large number
e = short number
c = large number

## Factordb.com
insert n

obtain p
obtain q

```py
from Crypto.Util.number import inverse

phi = (p-1)\*(q-1)

d = inverse(e,phi)

m = pow(c,d,n)

print hex(m)[2:-1].decode('hex')
```

https://www.youtube.com/watch?v=_lg2AEqRTjg