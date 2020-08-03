# 《Redis 5.* 开发与实战》


为什么要编写本书？
=========

Redis作为一个流行的key-value内存数据库 ，由于性能高，数据类型丰富，API功能强大，可用性高等特点，已经被越来越多的企业用于生产实践了。Redis可以讲所有数据都存放在内存中，所以它的读写性能非常惊人，Redis还可以讲内存中的数据利用快照和日志的形式保存到硬盘上，保证内存中的数据不会丢失。总之在合适的场景使用好Redis，它就会像一把瑞士军刀一样方便。

本书基于最新的Redis 5.*版本，为帮助大家的理解，书中使用了大量的实战案例，覆盖了Redis的几乎所有方面，从Redis基本数据类型，常用该命令，一直到Redis缓存持久化，集群环境部署和开发实战等高级主题，

学习任何技术都要理论联系实践，所以本书的作者将通过大量的案例向读者系统的讲解Redis的各个知识点，在读者的个人计算机上，只要遵循本书案例的操作步骤，都可以很容易的理解每个案例的知识点，缩短学习Redis的时间和降低学习编程的难度，书中使用的案例都是作者在企业开发和运维工作中经验的总结和感悟。
希望本书可能让读者更好的理解Redis，可以帮助读者在工作中正确使用Redis的新特性。

本书的结构
=========

使用的是最新版本的 Redis 5.*，详细讲解了Redis 5.* 的各个知识点，包含从入门到实战的所有例子。

第1章  初识Redis ，
本章详细介绍了Redis服务器的安装和基本操作，包括在Windows和Linux环境下启动和停止Redis，使用redis-cli连接到Redis服务器。在本章的最后还介绍了Redis集群实验的安装环境。

第2章  Redis常用数据类型及操作，
本章主要介绍了Redis的常用的数据类型和操作数据类型的常用命令，还介绍了Redis 5.* 的插件功能，在Redis服务器上加载布隆过滤器模块。

第3章  Redis常用命令，
本章主要介绍了Redis的常用命令，包括键值相关命令和服务器相关命令。

第4章  Redis高级主题，
本章主要介绍了Redis的高级主题，包括Redis服务器配置，事务，发布和订阅功能，Pipline批量发送请求，性能测试，客户端连接和Redis开机启动，介绍了Redis的高级功能。

第5章  Redis缓存持久化，
本章主要介绍了Redis中的两种持久化方式：RDB和AOF，讲解了在Redis中如何启动RDB和AOF来实现持久化，并揭示了持久化的工作原理。本章讨论了RDB和AOF之间的区别，以及如何将这两种方式结合起来使用。

第6章  Redis集群环境部署，
本章主要介绍了Redis的高可用相关结构。讲解了主从复制，哨兵模式，Redis 4.* Cluster 和Redis 5.* Cluster集群配置和命令。主要介绍了Redis 5.* 集群配置的详细实验步骤和工作原理进行了解释。

第7章  Redis开发实战，
本章主要讲解了如何使用Java开发Redis程序，本章讨论了Redis的数据类型和API的使用，讲解了使用Redis客户端jedis应用程序的实例，在本章中使用案例介绍了edis在生产环境的使用场景和技巧。

第8章  Spring Boot与Redis整合使用，
本章介绍了 Spring Boot2框架与Redis的集成，详细介绍了RedisTemplate API的使用，最后使用案例介绍了Spring Session中使用Redis场景和原理。

第9章  Redis监控，
本章介绍了Redis的性能监控和自定义开发应用程序来监控Redis的性能,使用的是最新的Websocket技术与后台进行消息推送和接收。

第10章  Redis的缓存设计与优化，
本章介绍了Redis作为缓存的收益和成本，以及在生产环境下出现缓存雪崩和缓存穿透的原因和解决方法。

第11章  扩展知识，
本书设计的技术知识内容比较多，所以把读者需要掌握的内容单独汇聚成一张，包括CentOS的配置，Maven基础知识，配置Intellij IDEA，配置SecureCRT,Chrome常用技巧和Python 3操作Redis 5集群。

本书涉及的链接
=========
本书中涉及的软件下载链接如下所示：

- 1.1.1	Redis简介

Redis的官方网站是： http://Redis.io/ , 最新版本的Redis安装包是Redis 5.0.5(截止到2019年11月)

我们也可以访问Redis的中文官方网站： http://www.redis.cn ，这个页面有个方便的工具，访问互动教程链接(http://try.redis.io/) ,会弹出一个新的页面


- 1.2.1	在Windows下安装Redis

Redis的Windows版本下载链接：
https://github.com/MicrosoftArchive/redis

本节中使用的是基于Windows 64位版本下的Redis安装包,Redis安装包的下载地址:
https://github.com/MSOpenTech/Redis/releases

- 1.3	Redis可视化工具 

RedisDesktopManager官网地址如下：
https://redisdesktop.com/download





写书进度
=========
2019年10月完成本书的编写

- 2019年10月18日本书稿件第一版完成。

- 2020年2月10日本书稿件第二版修改完成。

- 2020年4月7日本书稿件第三版修改完成。








