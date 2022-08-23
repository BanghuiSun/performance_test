# performance_test
压测

command:
```shell
jmeter -Jthread=20 -Jduration=20 -Jcount=-1 -Dprotocol=https -Durl=device.didi365.com -Dport=443 -n -t demo.jmx 
```
