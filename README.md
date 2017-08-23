# spray-module
spray模块架构分离，对spray项目进行拆分，拆分后项目分为：

```
spray-api 项目APP接口API模块

spray-service 项目基础公共模块

spray-manage 项目后台管理模块，采用spring-security登陆拦截

spray-crawler 项目定时任务爬虫模块,采用Job任务模式，可后台配置

spray-cas 单独的单点登录cas项目

spray-manage-cas 项目后台管理模块,采用cas拦截登陆与spray-cas一起使用
```

spray-service为公共模块，其他模块都需要引用这个模块的jar

关于数据库的建表语句在spray-service项目的resources目录下

# 联系我

QQ:787019494

Email:shangjing105@163.com
