# spring-cloud-demo

### 内容
* 注册中心eureka
* producer服务，consumer服务
* zuul网关
* zipkin链式监控
* hystrix熔断
* hystrix-turbine监控

### 说明
* 所有服务均注册到一个服务中心上（配置文件中有多个profile，也可以启动集群服务中心）
* consumer中使用feign调用producer的一个方法，测试熔断


