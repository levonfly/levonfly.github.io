---
title: golang_ide_goland使用
tags: golang
abbrlink: 5a4d0049
categories:
  - 1-编程语言
  - golang
date: 2018-05-10 18:17:48
---



### 1. 保存文件自动 go fmt + go imports

go to preferences ->Tools ->File Watchers and enable go fmt . This way on each save it will format the file.


goland tools->filewatchers->go fmt| go imports

<!-- more -->



### 2. 快捷命令

删除 cmd + x

复制 cmd + d

CMD + E 呼出最近文件和常用功能

favorites 可以查看书签/断点/收藏

各种搜索 两次 shift

比较文件 选择两个 cmd+d

ctrl + shift + h 搜索

cmd + [] 进入返回

+ 开启标签移动
	-  cmd + [] + shift

+ 代码提交比较
	- VCS -> Local History | Commit 查看

+ 文件导航 
	- cmd + f12 
	- cmd + 7

+ 看定义所有的方法 
	- cmd + b

+ 通过 interface 查看实现的Struct   
	- shift + cmd + b 
	- ctrl + h 贤淑类型层次  感觉差不多实现功能了

+ super method  查看struct实现了哪些接口, 找爹
	- cmd + u
