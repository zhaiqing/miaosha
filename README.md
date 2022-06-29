# miaosha
# 一、项目简介：  
一个基于Springboot开发的秒杀系统，实现的功能主要是登录，商品列表、商品详情、秒杀商品、订单详情等功能。在系统业务处理中，使用到分布式session维持会话、Redis预减库存降低数据库访问压力，消息队列异步下单（削峰）、客户端轮询结果、接口限流防刷等。
# 二、开发技术：  
后端处理：Springboot、MyBatis、MySQL、JSR303(参数验证)、RabbitMQ、Redis、Druid  
前端处理：Html、jQuery、Thymeleaf
# 三、实现细节  
1、用户密码两次MD5加密  
2、分布式Session维持会话  
3、异常统一处理  
4、页面缓存 + 对象缓存  
5、页面静态化  
6、内存标记+Redis预减库存 + RabbitMQ异步处理  
7、解决超卖  
8、接口限流
