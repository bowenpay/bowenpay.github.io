---
layout: post
title:  "波纹积分技能表"
date:   2015-09-08 22:01:00
author: "易先生个蛋"
categories: manage
---
受到[《知道创宇研发技能表》](http://blog.knownsec.com/Knownsec_RD_Checklist/)的启发，我觉得每个技术公司都应该维护一份自己的技能表，
一是可以时刻看到整体架构，不断去思考和改进；
二是可以方便员工扩展自己的技术线，自我成长。

下面进入正题。

===========================分割线==========================

波纹积分是一家致力于积分的支付、兑换、转账、提现，及商家营销的公司。

本技能表为波纹积分各个职位的技能集合

* 聪明的人，会根据每个tip自动扩展
* 不聪明的人，坐等别人手把手，不仅不适合波纹科技，也不适合任何有极客精神的公司

# 价值观

## 公司与个人
* 公司是盈利性组织
* 个人和公司必须双赢
* 在认同公司理念且能够给公司创造足够价值的基础上，为个人发展而工作

## 选择公司的时候考虑以下三点
* 成就感
* 钱
* 健康
如果任何一项出现问题，则需要重新思考，自己是否适合留在公司了。

## 做事的态度
* 不仅仅是完成任务，时刻用高标准要求自己
* 不想做CEO的程序员不是好产品经理。不要为了完成任务而工作，多思考任务背后的原因。

# 研发技能

## 通用

### 基础知识

####1. 操作系统
要求熟练使用Debian和CentOS

    《Unix高级环境编程》
    《Unix编程艺术》
    同步/异步/协程

####2. 网络

    《TCP/IP详解 卷1：协议》
    《用TCP\IP进行网际互联》
    《Unix网络编程卷1，套接字》和《Unix网络编程卷2，进程间通信》

####3. 数据结构和算法

    《算法:C语言实现(第1～4部分)基础知识、数据结构、排序及搜索(原书第3版)》
    《算法导论》

### 版本控制
- git
- git-flow
- gitlab/gitlab-ci/codereview/jenkins
- github/bitbucket

### 文档
* 技术文档

	Jekyll + Markdown

* 开发文档

	Sphinx + reStructuredText + Graphviz + Nginx

### 效率工具
* Evernote
* github
* vim/Webstorm/Pycharm
* dropbox & 百度云
* tmux
* Chrome
* xmind
* PhotoShop

## 运维
熟练以下各个服务的搭建和配置，并且阅读过对应sdk的代码，具备随时修改的能力

* 服务器

    阿里云ECS、CentOS 7、linux基础命令（tail、top、netstat、ps、lsof、awk）

* 数据库

    阿里云RDS、mysql、postgresql

* nosql

    阿里云KVStore、redis

* 消息队列

    阿里云MNS/ONS、消息队列（beanstalkd、kafka）、发布订阅

* 搜索

    阿里云OpenSearch、solr、elasticsearch

* web server

    nginx、apache

* 脚本和进程管理

    crontab、supervisor

* 异常收集

    sentry

* 自动化部署

    fabric

* 常用软件和服务

    vim、sentry

## web开发

### web基础

* 熟悉HTTP协议

    __《HTTP权威指南》__

* 了解web安全

    《白帽子讲WEB安全》

* 熟悉restful：

    -《RESTful Web Services Cookbook》

    -《REST in Pratice》

### 后端：
* python语言

    至少读过一遍官方文档
    《python 参考手册》
    《Python源码剖析》
    异步/协程

* web框架

    tornado/django/flask

* 数据库

    《高性能mysql》 xtrabackup

    《MySQL性能调优与架构设计》

    红黑树/B树/B+树/B*树

* 消息队列

* 搜索

* nosql(redis和mongodb)

* 理解阻塞与非阻塞，同步、异步、协程

* 了解一些nodejs

#### 前端
* html/javascript/css
* jquery/zepto/bootstrap
* angular
* yeoman/grunt/bower
* less/coffee
* 必备工具：Chrome DevTools、pagespeed、WireShark

## 产品

## 运营

## 商务推广/销售

## CEO
参与活动、寻找投资、接触媒体、、决策、团结人心、组织活动

## CTO
架构、找人、任务调度、对外PK

# 订阅
互联网的知识更新换代非常快，只有不断的学习才能跟上时代。依据2-8原则，我们获取的信息中，80%都是噪音，所以合理的选择接受信息非常重要。
下面是推荐订阅的内容：
* 投资类
* 技术类
* 新闻类