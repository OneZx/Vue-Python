#### 简介

本文档是Vue-python前后端分离项目的学习记录, 方便自己以后查阅梳理知识. 同时也分享出来供大家一起讨论学习~

> 技术栈

1. Vue 2.0
- Django REST Framework
- restful api
- xadmin 后台管理系统
- sentry 错误日志监控
- 第三方登录和支付宝支付的集成
- 本地远程调试

> 重点

- django Rest Framework的开发

**通用View实现rest api接口**

1. ApiView方式实现api
- GenericView方式实现api接口
- Viewset和router方式实现api接口和url配置
- django_filter、 SearchFilter、 OrderFilter、 分页
- 通用mixins

**权限和认证**

1. Authentication用户认证设置
- 动态设置permission、Authentication
- Validators实现字段验证

**序列化和表单验证**

1. Serializer
- ModelSerializer
- 动态设置Serializer

**支付、登录和注册**

1. json web token实现登录
- 手机注册
- 支付宝支付
- 第三方登录

**进阶开发**

1. django rest framework部分核心源码解读
- 文档自动化管理
- django rest framework的缓存
- Throttling对用户和ip进行限速

#### 开发中常见的问题
1. 本地系统不能重现bug
- api接口出错不能及时发现找到错误
- api文档管理问题
- 大量的url配置造成url配置越来越多难以维护
- 接口文档不及时更新,写文档又会花费大量时间取维护
- 为防止爬虫,我们需要对api的访问频率进行限制
- 某些页面的数据放入缓存,加速某些api的访问速度

> 常见问题的解决方案

1. pycharm的远程服务器调试可以调试支付,第三方登录,远程服务器代码(重现服务器上的bug)
- 通过docker搭建sentry体验错误日志监控系统,可以得到线上错误栈并在系统错误时收到邮件通知
- django rest framework的文档自动化管理以及url的注册管理功能让我们省去写文档的时间,能直接在文档里测试接口,自动生成js接口代码,shell测试代码和python测试代码
- django rest framework提供throttle对api进行访问限制
- 引入第三方框架来设置某些api的缓存

#### django 进阶知识点
1. django migrations原理
- django信号量
- django 从请求到响应的完整过程
- 独立使用django的model

#### Vue知识点
1. Vue技术选型分析
- api后端数据填充到Vue组件模板
- Vue代码结构分析

#### 章节安排
- 第一二章 开发环境搭建
- 第三章 设计数据库以及导入原始数据
- 第四章 restful api基础以及vue项目结构介绍
- 第五章 商品列表功能
- 第六章 商品类别功能
- 第七章 手机注册和用户登录
- 第八章 商品详情页和收藏功能
- 第九章 个人中心功能
