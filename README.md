# docker-metasploit

> Docker image containing Kali + Metasploit

## Run

```
# Pull/Start Container 
$ docker run -t -i -p 443:443 -p 55553:55553 bencevans/metasploit /bin/bash

# Start PostgreSQL
root@d1880a84591c:/# service postgresql start
[ ok ] Starting PostgreSQL 9.6 database server: main.

# Start msfrpcd
root@d1880a84591c:/# msfrpcd -U admin -P admin
[*] MSGRPC starting on 0.0.0.0:55553 (SSL):Msg...
[*] MSGRPC backgrounding at 2017-05-21 00:53:52 +0000...
```
