# lightstreamer 在线实验环境

## 软件简介

软件基本信息，License，所属的类别，作用，特点等。
Lightstreamer是为互联网优化的实时消息传递服务器。混合WebSockets，HTTP和推送通知，它将数据传输到移动，平板电脑，基于浏览器，桌面和IoT应用程序。  

所属类别是服务器软件

特点：

具有实时性

## 软件官网

http://www.lightstreamer.com/

## Dockerfile 使用方法

运行正常
使用默认配置启动容器：
```
$ docker run --name ls-server -d -p 80:8080 lightstreamer
```
这将将容器内的端口8080映射到本地主机上的端口80。然后将您的浏览器指向http://localhost并观看欢迎页面，显示从本地部署的演示应用程序流入的实时数据，这是Lightstreamer技术提供的独特功能的第一个概述

## 资源链接

- http://www.lightstreamer.com/
- https://hub.docker.com/_/lightstreamer/
