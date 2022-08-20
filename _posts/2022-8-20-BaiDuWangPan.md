---
title: 百度网盘满速下载
author: IT余识
categories: [经验]
tags: [经验]
---
## 声明

本文所涉及的方法，均为网络收集，如有侵权，可通过邮箱<It_YuShi@163.com>联系我进行处理

## 广告

{% for post in site.data.poster %}

<li>{{ post.ad }}</li>

{% endfor %}

## 1.安装aria2

下载链接点[这里](http://aria2.baisheng999.com/)

根据自己的需要下载版本即可

![下载页面](/assets/img/BaiduWangPan/1.png)

使用方法很简单，如果是windows版本，下载解压后，就可以直接点击AriaNg.exe启动即可

## 2.下载脚本

然后我们还需要下载油猴插件，Edge浏览器可直接进入插件商店进行搜索**Tampermonkey**

![下载页面](/assets/img/BaiduWangPan/2.png)

然后安装即可，如果是其它浏览器请自行查找安装油猴插件的方法

然后点击[这里](https://greasyfork.org/zh-CN/scripts),搜索**百度网盘简易下载助手**

![下载脚本](/assets/img/BaiduWangPan/3.png)

点击搜索结果进入，安装即可

## 3.使用方法

1. 确保已经打开了aria2软件，并且该资源已经保存到了自己的百度网盘中
2. 然后登录自己的网页版百度网盘，点击右上角回到旧版
3. 注意一次只能下载一个文件，选择后点击**简易下载助手**即可
4. 此时会弹出对话框，关注那个作者，获取码，然后解析链接，发送至aria2即可开始下载

![右上角回到旧版](/assets/img/BaiduWangPan/4.png)

![下载](/assets/img/BaiduWangPan/5.png)

![下载](/assets/img/BaiduWangPan/6.png)
