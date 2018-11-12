# Servlet Web

![java](https://img.shields.io/badge/language-java-red.svg)
![许可](https://img.shields.io/dub/l/vibe-d.svg) 
:cat: :smiley_cat: :kissing_cat:

> 基于Jsp + Servlet + Jdbc + Mysql + jQuery技术栈, 实现了DispatcherServlet请求分发机制 + 图像文件的上传/存储/读取功能。代码规范基于《阿里巴巴Java开发手册》。

#### [线上DEMO地址](http://www.lifecat.club:8080/lifecatweb)

点击'立即登录' 用户名:admin 密码:admin

## 项目部署
### 本地部署
``` bash
# Clone下载项目到本地
git clone https://github.com/kevinten10/lifecatweb

# 配置相关文件
进入lifecatweb/src/main/java/com/ten/constant包
1. DataBase.java :修改相应字段为自己的数据库配置  
2. HOST.java     :修改相应字段为数据库IP地址  
    
# 配置数据库
已导出数据库SQL文件, (建议使用navicat)执行lifecatweb/lifecat.sql文件即可生成对应数据库以及DEMO数据

# 配置tomcat
(使用idea)配置tomcat的Artifact时, Application context(即项目名)需要设为"/lifecatweb"

# 启动运行
若报错, 阅读错误信息, 若发现为缺少JSTL错误, 将lifecatweb/jstl-1.2.jar复制到tomcar/lib中
```

### 云服务器部署
```bash
# 部署Javaweb开发环境
# 生成war文件
# 放到对应tomcat目录下
```
云部署相关教程: [centos云服务器部署Javaweb应用](https://blog.csdn.net/wsh596823919/article/details/79717993)

## 项目分析

[若您已部署成功, 想深入理解整体项目的架构以及流程讲解, 点击阅读项目分析教程](Tutorial.md)

## DEMO

 ![show](Image/show1-1.png)
 
 ![show](Image/show1-2.png)
 
 ![show](Image/show1-3.png)
 
 ![show](Image/show1-4.png)
 
### lifecat相关项目
  [v1 jsp+servlet+mysql实现Javaweb](https://github.com/kevinten10/lifecatweb)    
  [v2 ssm框架实现Javaweb后台管理系统](https://github.com/kevinten10/SSM-lifecat)  
  [v3 前后端分离之SpringBoot实现Java后端开发](https://github.com/kevinten10/springboot-lifecat)  
  [v3 前后端分离之vue实现后台管理系统](https://github.com/kevinten10/Vue-Admin-lifecat)  
  [v3 前后端分离之vue实现仿ins效果web开发](https://github.com/kevinten10/Web-lifecat)  
  
  [ex wechat 微信移动端小程序开发](https://github.com/kevinten10/WeChat-lifecat)  
  [ex hadoop 分布式平台进行数据处理](https://github.com/kevinten10/Hadoop-lifecat)  
  [ex android 相应Android相册应用](https://github.com/kevinten10/Android-lifecat)  
  [ex python 机器学习进行图像智能处理](https://github.com/kevinten10/Python-lifecat)  
 
### LifeCat系列总览
  [LifeCat系列项目](https://github.com/kevinten10/LifeCat)  
  
  如果觉得有用，可以帮忙点个star，谢谢啦！
