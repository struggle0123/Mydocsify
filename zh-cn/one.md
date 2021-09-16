# Tomcat就是这么简单

## 什么是Tomcat ##
> Tomcat简单的说就是一个运行JAVA的网络服务器，底层是Socket的一个程序，它也是JSP和Serlvet的一个容器
## 为什么我们需要用到Tomcat ##
> 如果你学过html，css，你会知道你写的页面只能自己访问，别人不能远程访问你写的页面，Tomcat就是提供能够让别人访问自己写的页面的一个程序
![tomcat](https://segmentfault.com/img/remote/1460000013228164?w=694&h=483)
## 配置Tomcat ##
###  运行Tomcat需要JDK的支持【Tomcat会通过JAVA_HOME找到所需要的JDK】。
###  新建JAVA_HOME环境变量【路径是JDK的主目录】
>>  ![tomcat1.1](https://segmentfault.com/img/remote/1460000013228165?w=460&h=558)
### 进入Tomcat目录下的bin中启动startup.bat，以下是成功启动Tomcat的页面。
>>  ![tomcat](https://segmentfault.com/img/remote/1460000013228166?w=677&h=443)
### 在浏览器地址栏输入http://localhost:8080,     如果能够出现Tomcat页面，说明配置成功了！