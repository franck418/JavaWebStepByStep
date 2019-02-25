# JavaWebStepByStep

最简单的web程序，只需要一个html页面和一个web服务器。JavaWeb程序一般使用tomcat。完成一个最简单的web程序只需要以下步骤：

1 编写一个html页面。

2 将页面部署到tomcat里面去

3 启动tomcat

这样就完成了一个最简单的web程序，这个程序只展示一个html页面的功能，没有任何的交互。




使用IDEA开发这个程序的步骤是:

1 新建一个JavaWeb项目。

![创建项目](/img/1.png)

2 在IDEA里面配置一个tomcat

3 将项目打包（在设置里面用项目添加一个artifacts）

4 配置tomcat部署对应的artifacts

5 启动tomcat 。

启动成功后，在浏览器内就可以通过地址访问项目了。

为了简化这个步骤，SpringBoot诞生了。 SpringBoot内置了Tomcat。只需要编写好代码，然后启动对应的启动类，就可以访问到项目了。

关于SpringBoot，后面再详细说明。



