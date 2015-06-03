---
layout: post
title:  "django入门"
date:   2015-06-03 11:48:00
categories: manage
---

#1. python环境配置

##1) python版本

常用的稳定版本是2.7.6

##2) 包管理工具：pip

常用命令 pip install，pip uninstall

批量安装：pip freeze > requirement.txt, pip install -r requirements.txt

##3) python环境

使用`virtualenv`和`virtualenvwrapper`管理python的运行环境，安装完这两个包之后，使用以下命令创建隔离的dj1.8环境：

3.1) 在`~/.bashrc`中添加如下配置

```
### add for virtualenv
export WORKON_HOME=$HOME/.virtualenvs
source `which virtualenvwrapper.sh`
```

3.2) 执行`source ~/.bashrc`

3.3) 创建dj1.8隔离环境

```
mkvirtualenv dj1.8
```

3.4) 可以随时使用`workon dj1.8`进入该环境，注意使用pip安装包的时候，确认是否已经进入该环境

#2. django

##1) django版本

使用最新稳定版1.8

##2) django教程

英文版：https://docs.djangoproject.com/en/1.8/

中文版：[The Django Book](http://djangobook.py3k.cn/2.0/chapter01/) 、[Django 中文文档](https://django-chinese-docs.readthedocs.org/en/latest/)

#3. 非常有用的第三方库/应用

##1) django best practice

##2) readthedocs部署文档

##3) sentry收集异常日志

##4) jekyll编写技术日志