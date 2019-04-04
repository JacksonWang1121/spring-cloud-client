Eureka Client服务提供者的创建过程
    1、添加依赖
        spring-cloud-starter-eureka-server
    2、在@SpringbootApplication注解的启动类，打上注解@EnableEurekaClient
    3、配置application.yml