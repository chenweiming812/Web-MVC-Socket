Web-MVC-Socket
===============
简介
----
* 使用底层的`Socket`进行通信，能够收发和监听网络请求和响应，同时实现对`HTTP协议`的解析，构造一个完整的`Web Server`<br>
* 采用`MVC`架构，实现数据M、页面V以及控制C的解耦<br>
* Model层利用拼接`SQL`语句封装函数，实现基于MySQL的自制`ORM`，能够完成不同类型数据的CRUD<br>
* Control层由自制的Web框架组成，能够解析HTTP请求和构建返回HTTP响应，利用`表驱动法`完成路由注册和路由分发，此外支持`404响应`和`重定向功能`<br>
* View层使用`Jinja2`模版语言，利用模版继承简化页面处理加速开发<br>
* 基于框架实现了用户注册、登录，通过 `session`进行身份验证，密码进行`加盐`保护，利用`装饰器`对用户进行权限验证，此外还有发布微博、评论微博功能<br>

功能演示
--------
测试账号：181  密码：111<br>
* 注册<br>
![](https://github.com/chenweiming812/Web-MVC-Socket/raw/master/static/register.gif)
* 登录<br>
![](https://github.com/chenweiming812/Web-MVC-Socket/raw/master/static/login.gif)
* 发表微博和评论
* 编辑、删除微博和评论 

