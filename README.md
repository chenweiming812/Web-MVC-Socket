Web-MVC-Socket
===============
简介
----
使用底层的Socket进行通信，能够收发和监听网络请求和响应，同时实现对HTTP协议的解析，构造一个完整的Web Server
采用MVC架构，实现数据M、页面V以及控制C的解耦
Model层利用拼接SQL语句封装函数，实现基于MySQL的自制ORM，能够完成不同类型数据的CRUD
Control层由自制的Web框架组成，能够解析HTTP请求和构建返回HTTP响应，利用表驱动法完成路由注册和路由分发，此外支持404响应和重定向功能
View层使用Jinja2模版语言，利用模版继承简化页面处理加速开发
基于框架实现了用户注册、登录，通过session进行身份验证，密码进行加盐保护，利用装饰器对用户进行权限验证，此外还有发布微博、评论微博功能
