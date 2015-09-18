---
layout: post
title:  "mysql server管理基础"
date:   2015-06-03 17:18:00
author: "易先生个蛋"
categories: tech
---

#1. mysql修改默认编码

使用mysql 5.5+版本，以支持utf8mb4，存储emoji字符。
增加文件：`/etc/mysql/conf.d/utf8mb4.cnf`，内容如下：

```
[client]
default-character-set = utf8mb4

[mysql]
default-character-set = utf8mb4

[mysqld]
character-set-client-handshake = FALSE
character-set-server = utf8mb4
collation-server = utf8mb4_unicode_ci
```

#2 mysql 分配权限

```
mysql> GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' IDENTIFIED BY 'password' WITH GRANT OPTION;
Query OK, 0 rows affected (0.00 sec)

mysql> FLUSH PRIVILEGES;
Query OK, 0 rows affected (0.00 sec)
```

#3 远程登录
在分配完了‘%’的权限后，需要注释掉my.cnf中的一行

```
bind-address = 127.0.0.1
```

centos 参考 [Install MySQL on CentOS 7](https://devops.profitbricks.com/tutorials/install-mysql-on-centos-7/)

#4 为了省去dba和运维的工作，最终我们选择了阿里云rds