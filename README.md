# nGrinder-ext 1.0
========
是基于nGrinder的二次开发，压测平台1.0
## 技术框架：

      1. 数据库重构框架Liquibase
      2. DAO层框架Spring-data-jpa
      3. 定时任务调度框架spring task
      4. 缓存框架ehcache
      5. 安全框架spring security
      6. mvc框架spring mvc
      7. 服务端模板引擎freemarker
      8. 单测框架junit
      9. 开发框架spring framework    
      
##　解决问题：

      1. FIX任务调度时僵死任务的BUG。
      2. ADD服务器监控参数：RT分布、CPU利用率、内存使用率、网络IO、磁盘IO、CPU Load等。
      3. ADD任务的异步压测方案，弥补测试高并发时当前进程、线程模型的不足。
      4. 前端模板修改。
      5. 将SVN改为用git进行测试脚本管理。
      6. 支持创建dubbo压测模板（或者其它微服务框架）。
      7. 支持MySQL压测模板。
      8. 将脚本语言改为Java。

## 后期规划：分布式压测平台2.0
      完全重新架构，实现高可用的分布式全链路压测平台
