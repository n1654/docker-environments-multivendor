Allow connections:
```sh
$ sudo iptables -I INPUT -p tcp --dport 5000 -j ACCEPT
```
