# <center>**mChat**</center>

* <a href="#项目介绍">项目介绍</a>
* <a href="#功能截图">功能截图</a>
* <a href="#系统架构">系统架构</a>

## <a name="项目介绍">项目介绍</a>
这是一个在PC运行的即时通讯工具，它目前提供如下功能：注册、登录、添加/搜索好友，聊天（文本）。技术栈如下：  
前端：Vue + Socket + Electron  
后端：Express + Redis + RabbitMQ + Mysql + Socket + Apisix

对应的仓库：[前端](https://github.com/Thinker-Mars/mChat-front)、[后端](https://github.com/Thinker-Mars/mChat-backend)

## <a name="功能截图">功能截图</a>
* 登录

	![登录](image/4172acf05ac3e63e7a93fa8b7433772.png)

* 注册

	![填写信息](image/2ea6b3fda99793208e2a4873c58b831.png)

	![注册成功](image/925fad8135365416efc39e097471d6a.png)

* 消息列表

	![消息列表](image/62cf18144e128200ed295e0a317eaf1.png)

* 好友列表

	![好友列表](image/5c8a479a14689be117881c5235bd3d6.png)

* 搜索好友

	![搜索好友](image/cbb8be4747f465d132276a78aab8006.png)

	![添加好友](image/341f0a8f972a06b2f910f582b100019.png)

## <a name="系统架构">系统架构</a>
如下图所示：
![系统架构](image/frame.png)

这个项目是我对于Node微服务的一次实践，各个服务通过网关（Apisix）进行聚合。