# performance_test
压测

command:
```shell
# 本机执行
jmeter -Jthread=20 -Jduration=20 -Jcount=-1 -Dprotocol=https -Durl=device.didi365.com -Dport=443 -n -t demo.jmx

# 若分布式执行时
jmeter -Gthread=20 -Gduration=20 -Gcount=-1 -Dprotocol=https -Durl=device.didi365.com -Dport=443 -n -t demo.jmx -r
```
