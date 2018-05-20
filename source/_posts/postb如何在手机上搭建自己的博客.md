---
title: 如何在手机上搭建自己的博客
date: 2018-05-18 07:09:32
tags:
---
实质上在手机搭建博客不仅**麻烦**，而且容易**失败**。但还是有很多人想要搭建。为什么呢？我想他们应该要装逼吧。

<!--more-->

**第一步** ：安装**Termux** 。

链接我就不放出了，在[酷安](www.coolapk.com)可以下载。

**第二步**：在里面输入这条命令。
```
node
```
他会提示你未安装。这时会有提示，安装**第二个**，**一定要安装第二个**(node-c....)。然后等它安装完成。

**第三步**：检测是否安装**node**以及**npm**。

在Terumx下输入
```
node -v
npm -v
```
如果输出的是版本号，就证明你安装成功了。

**第四步**：安装git

**git**是必须安装的。在termux下输入
```
pkg install git
```

等他安装完成就行了。

**第五步**：在github上做工作。

进入 [github官网](github.com) 。点注册

![注�](https://github.com/shzheng233/imge/blob/master/Screenshot_%E6%B5%8F%E8%A7%88%E5%99%A8_20180519-071253.png?raw=true)

按照它的步骤完成就行了。

**第六步**：创建**repository**。

![添加](https://github.com/shzheng233/imge/blob/master/Screenshot_Via_20180519-224039.png?raw=true)


点击**new repository**。名字一定要为**yourname.github.io**。

![new repository](https://github.com/shzheng233/imge/blob/master/Screenshot_Via_20180519-224548.png?raw=true)

我的已经创建了，所以会提示错误。但你们应该没有问题。**接下来我们在看一直没有提到的Termux。**

**第七步**：在Termux下运行npm命令。
首先创建一个文件夹，作为hexo博客的根目录
```
mkdir hexo #your dir name
```
在进入这个目录
```
cd hexo
```
运行这条命令
```
npm install hexo
```
等它安装完成就可以了。如果你在前面安装的事第一个(node)的话。那么这一步你将会失败。而如果这一步失败的话，那将是致命的。

**第八步**：运行这条命令
```
hexo s
```
应该就可以了


