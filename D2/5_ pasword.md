have the Zip file

## zip2john or rar2john
Open file hash
```console
zip2john name.zip > docHash.txt
```

## john (zip or rar)
crack pasword
```console
john --formaat=zip docHash.txt
```

have a profile linux

## User add
create new user
```console
useradd -r xUser
```

## User delete
create new user
```console
userdel xUser
```

## passwd
put password to user
```console
passwd xUser
```

## Crack linux password
crack shadow file /etc/shadow
```console
john /etc/shadow
```

https://www.youtube.com/watch?v=XjVYl1Ts6XI