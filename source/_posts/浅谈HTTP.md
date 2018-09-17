---
title: 浅谈HTTP
date: 2018-09-15 18:07:49
tags:
---
###　浅谈HTTP

目录：
１．补充
２．HTTP 请求包括哪些部分，如何用Chrome开发者工具查看 HTTP 请求内容
３．HTTP 响应包括哪些部分，如何用Chrome开发者工具查看 HTTP 响应内容
４．如何使用 curl 命令

####１．补充
**关于客户端与服务器：**
web的内容都是存储在web服务器上，这些服务器存储了数据，如果HTTP客户端发出请求的话，服务器会提供数据。即：客户端向服务器发送HTTP请求，服务器会在HTTP响应中回送所请求的数据。
**URI URL URN：**
* URI：统一资源标识符，可以标示唯一的一个资源。比如，ISBN:9787542637949 ，可以标识出一本书。
* URL：统一资源定位符，可以提供找到该资源的路径。又因为它同样可以唯一的标识出一个资源，所以是URL的子集。
*URN：统一资源名。作为特定内容的唯一名称使用，与目前的资源所在地无关。也是URI的子集。

**方法：**
常见的HTTP方法：
GET：获取
POST：发送
PUT：更新
DELETE：删除

####２．请求
请求包含四部分：进行描述的起始行，包含属性的首部行，**回车**，以及可选的，包含数据的主体部分。
用chrome进入百度，查看：
![image.png](https://upload-images.jianshu.io/upload_images/7513933-d921d6d9fdd6ffc7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
可以看到第一、第二部分

使用curl -d来试试POST上去的数据（第四部分数据没有显示）：
![image.png](https://upload-images.jianshu.io/upload_images/7513933-2409454f380acd08.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
不过已经可以看到 content-length 以及 content-type
 ####3．响应
响应也包含四部分：进行描述的起始行，包含属性的首部行，**回车**，以及可选的，包含数据的主体部分。
用chrome进入百度，查看：
![image.png](https://upload-images.jianshu.io/upload_images/7513933-553446049624ed00.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**同样的**可以用curl -I来查看
    
    curl -I "https://www.baidu.com"
![image.png](https://upload-images.jianshu.io/upload_images/7513933-caf1708ccf15a3e8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####curl的使用：
现在用到的几种：
１．获取页面内容

    curl https://www.baidu.com 

２．显示HTTP头

     curl -I https://www.baidu.com （显示HTTP头）
     curl  -i https://www.baidu.com（显示HTTP头和内容） 
３．将链接保存到文件

     curl https://www.baidu.com  > index.html
![image.png](https://upload-images.jianshu.io/upload_images/7513933-444507e7124e3652.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4．使用-d 发送POST请求

    curl -d "1234" "https://www.baidu.com"
5．使用-v显示请求详细信息
6．使用-X指定请求方式
7．使用-H增加头部信息