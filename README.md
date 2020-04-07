# 配置中心远程仓库，文件名规范如下：

1、公共配置信息放在application.properties或application.yml中.

2、微服务独立配置文件名按{application}-{profile}.properties或{application}-{profile}.yml，

   {application}为spring.application.name值
   
   {profile}为spring.profiles.active值
   
   
3、微服务独立配置文件中有与application.properties文件中重合的key, 则读取到的value是微独立配置的值。

4、新添加内容-测试git命令
