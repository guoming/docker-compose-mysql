# Mysql
## 1、创建网络
``` SHELL
docker network create mysql
```
## 2、启动
``` SHELL
docker-compose up -d
```
## 3、测试
``` SHELL
telnet localhost 3306
```