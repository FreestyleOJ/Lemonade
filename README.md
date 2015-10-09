这是由24OI小组修改并维护的Lemon版本，可能存在一定的不稳定性（我们只是在消除一部分不稳定性）。

[![Build](https://travis-ci.org/FreestyleOJ/Lemonade.svg?branch=editing)](https://travis-ci.org/FreestyleOJ/Lemonade/builds)

[![Coverity Scan Build Status](https://scan.coverity.com/projects/6617/badge.svg)](https://scan.coverity.com/projects/freestyleoj-lemonade)

[![Stories in Ready](https://badge.waffle.io/FreestyleOJ/Lemonade.svg?label=ready&title=Ready)](http://waffle.io/FreestyleOJ/Lemonade)

同时由Lemon激励开始的Lemonade项目正在设计中～欢迎加入～

下面是原Repo的README，原Repo可以到Project-Lemon那个分支里找到所有的文件，在此鸣谢@zhipeng-jia和@Sojiv。OIer会记住你们的伟大！

---

Project_lemon
=============

A clone of Project-Lemon on Google code (https://code.google.com/p/project-lemon/)

请用git clone源代码，或使用右方的Download ZIP功能。

```sh
sudo apt-get install qt4-dev-tools
```

进入源代码目录编译：
```sh
qmake lemon.pro
make
```
Fedora16下的安装注意事项（By litimetal）： 1、安装 qt-devel 2、不要输入qmake, 而是qmake-qt4

 - argv[1]: 标准输入文件 
 - argv[2]: 选手输出文件
 - argv[3]: 标准输出文件
 - argv[4]: 本测试点满分
 - argv[5]: 分数输出文件（必须创建），仅一行，包含一个非负整数，表示得分。
 - argv[6]: 额外信息文件（可以不创建）
