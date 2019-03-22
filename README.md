# Spring-Cloud-Study-



spring cloud 学习路线：    
-------------------------------------------------------------------------------------------
```markdown
┌─spring cloud eureka server      注册中心   
│─spring cloud eureka client      客户端    
│─spring cloud feign              声明式调用  
│─​            --- HTTP client   
│─​            --- OK HTTP   
│─spring cloud rabbit             负载均衡   
│─spring cloud zuul               路由网关   
│─spring cloud hystrix            熔断器    
│─spring cloud hystrix dashboard  熔断器监控  
  │─spring cloud sentinel  阿里开源熔断器 [待完成] 
│─spring cloud config             配置中心
  │─spring cloud ApolloConfig       携程Apollo阿波罗配置中心[待完成]
│================================================================
│─spring cloud turbine            聚合监控   
│─spring cloud sleuth             服务链路追踪 
  │-​--- zipkin分布式跟踪
  │-​--- 依赖mysql
  │-​--- 依赖elasticsearch/kibana 
  │-​--- 依赖rabbitmq 
    │-​--- SkyWalking同类分布式跟踪[待完成] 
│===================================================
│─spring boot admin               微服务监控--集中管理    
  │---- turbine   
  │---- security/login    
│─spring boot security            安全组件   
│─spring cloud oath2              授权协议 结合security使用  
│─spring cloud jwt                开放标准 结合oath2使用
    
```
