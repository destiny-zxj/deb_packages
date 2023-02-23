# Destiny Debs

[中文](./README.md)|[English](./README.en.md)

## 简介
* 对一些 deb 软件包进行重新打包
* 更方便的安装软件
* 扩展原软件。包括但不限于增加 `service 服务文件`、`etc 配置文件`

## 注意

* 请使用命令 `sudo apt-get install -f package.deb` 安装

## 包含软件

| 软件名 | 原软件 | 官网 | Github |
| ------ | ---- | ------ | ------ |
| **destiny_aria2** | aria2 | https://aria2.github.io | https://github.com/aria2/aria2 |
|        |      |      |        |
|        |      |      |        |

#### **destiny_aria2**

* 新增配置文件 `/etc/aria2/aria2.conf`
  * `dir=/root/Downloads`
  * `log=/etc/aira2/aria2.log`
  * session `/etc/aria2/aria2.session`
  * `rpc-secret=c8759ddaf820022ebb2e7a4ce2f7c0d6`
* 新增服务文件 `/etc/systemd/system/aria2.service`

## 引用

* [Aria2](https://aria2.github.io/) | [Aria2 Github](https://github.com/aria2/aria2)



## 声明

