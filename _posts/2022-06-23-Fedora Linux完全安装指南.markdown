---
layout: post
title: "Fedora Linux完全安装指南"
date: 2022-6-23
categories: Linux
tags: [Linux,计算机技巧]
---
>Fedora Linux是目前我最喜欢的Linux发行版。它的可定制性强，界面美观、清爽、友好，并且有着强大的软件源 (yum，dnf，rpm）。本文将手把手教你安装Fedora Linux。

### 安装Fedora Linux

这篇文章是2022年写的，Fedora Linux的最新版本是36，但是这里我安装Fedora Linux Workstation35。为什么不选择36？因为“尝鲜有风险〞，当你安装Beta版后会有许多不确定因素。
例如软件源仓库没有这个版本的镜像源，我在安装36的时候就遇到了这个问题。如果你只是想尝试一下Linux，那么推荐小众版本 (xfce, kde等)。反之，如果你有日常开发上的需要，
那么选择Workstation版吧。
* Step1.去[Fedora官网](https://getfedora.org/)下载Fedora Media writer。
* Step2.安装完后插入一个被格式化过的U盘，并选择Fedora版本，最后写入。如果U盘是满的或是Linux启动盘，那么请重置。
* Step3.烧录好启动盘后将其插入电脑，重启电脑，开机时根据提示进入启动选项页面（按什么键具体根据你的电脑）进入安装界面。
* Step4. 最重要的是分区了，建议不要尝试双系统。你可以将fedora安装在本地硬盘上，或者像我一样安装在外接硬盘 (SSD），注意不要选错了，后果会很严重。
* Step5．安装好后重启电脑，这样就成功了。

尽享Linux之趣吧！
