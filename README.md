# PySocks
**PySocks** is a SOCKS5 server written by **Python**

## Progress

* CONNECT commnad - OK
* UDP ASSOCIATE - NO
* BIND - NO
* No Authentication Required - YES
* USERNAME/PASSWORD Authentication - YES
* GSS-API - NO

## Environment
Python 2.7

## Install


```
    $ git clone https://github.com/fengyouchao/pysocks.git ~/pysocks
    $ python ~/pysocks/socks5.py start
```
See options

```
    $ python ~/pysocks/socks5.py -h
    $ python ~/pysocks/socks5.py start --port=1080 --auth=admin:123456

键入消息

```
