---
title: 查看Linux版本信息
date: 2018-02-27 15:41:20
tag: Linux
category: Linux
---
## 1、显示电脑及操作系统的相关信息
```bash
$ uname -a
```
<!-- more -->
## 2、查看内核版本
```bash
$ cat /proc/version
```
## 3、查看发行版信息
```bash
$ cat /etc/issue
```
## 4、通用的查看系统信息命令
```bash
$ lsb_release -a
```