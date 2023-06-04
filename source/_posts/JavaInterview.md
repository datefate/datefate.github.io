---
title: mysql realiteFile
date: 2023-06-04 18:25:34
tags:
 - Mysql
 - Database
categories: 数据库
---
### 查看和修改 MySQL数据库的最大连接数

#### 1、查看最大连接数：

```
show variables like '%max_connections%';
```

#### 2、修改最大连接数

永久, 打开MySQL配置文件 my.ini 或 my.cnf，查找

```
max_connections=100
```

临时，命令行修改

```
MySQL> set global max_connections=100
```
myPictureTest
![](20190810142838.jpg)


[![并行](https://s1.ax1x.com/2023/06/04/pC9LcPf.png)](https://imgse.com/i/pC9LcPf)
[![并发](https://s1.ax1x.com/2023/06/04/pC9LyIP.png)](https://imgse.com/i/pC9LyIP)