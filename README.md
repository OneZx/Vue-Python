#### 简介

本文档是Vue-python前后端分离项目的学习记录, 方便自己以后查阅梳理知识. 同时也分享出来供大家一起讨论学习~

> 技术栈

- Vue 2.0
- Django REST Framework
- restful api
- xadmin 后台管理系统
- sentry 错误日志监控
- 第三方登录和支付宝支付的集成
- 本地远程调试

> 重点

- django Rest Framework的开发

**通用View实现rest api接口**
- ApiView方式实现api
- GenericView方式实现api接口
- Viewset和router方式实现api接口和url配置
- django_filter、 SearchFilter、 OrderFilter、 分页
- 通用mixins

**权限和认证**
- Authentication用户认证设置
- 动态设置permission、Authentication
- Validators实现字段验证

**序列化和表单验证**
- Serializer
- ModelSerializer
- 动态设置Serializer

**支付、登录和注册**
- json web token实现登录
- 手机注册
- 支付宝支付
- 第三方登录

