---
title: python最好用IDE之pycharm的使用
tags:
  - python
abbrlink: b3d62374
categories:
  - 1-编程语言
  - python
date: 2019-03-11 22:14:00
---



工欲善其事必先利其器, 学习 python 自然选用了 jetbrains 家族的 Pycharm.

### 1. pycharm formatting on save

1. PyCharm -> Preferences -> Plugins -> Save Actions -> install and restart ide
2. PyCharm -> Preferences -> Save Actions -> Reformat file

![1](python最好用IDE之pycharm的使用/1.png)

<!-- more -->

3. 取消Power Save Mode

   IDE右下角有个机器人, 一定不要勾选 Power Save Mode

   具体表现：关闭后，Pycharm就跟文本编辑器差不多了，不会去关联上下文，像纠错、联想关键字等功能都没有了



### 2. Keymap

进入发现了, ctrl+w 和 ctrl+a 和 ctrl+e 失效, 很别扭, 研究发现了, 需要在 Keymap 选择  `Mac OS X 10.5+`

ctrl + w 关闭

ctrl + a 到行首

ctrl + e 到行尾



### 3. Alt + Enter 万能组合键

import 包经常要用到这个组合键, 但是发现在我的电脑上又失效

网上找了很多方法也没有解决. 一说是其他程序占用, 可以关闭所有程序试试

最后找到了解决方案, 就是把`Save Actions`  插件停掉, 重启之后再开启, 就好了(吐血)



### 4. module unresolved reference

- 在项目的文件夹(module 的上一级)右键 `Mark Directory as` -> `Source root`
- `File` -> `Invalidate Caches / Restart` and restart PyCharm.