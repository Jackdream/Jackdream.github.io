## [Spring Family](https://spring.io/)

> 该文档描述了spring家族所有成员

### [Spring Guides](https://spring.io/guides)

### [Spring Initializr](https://start.spring.io/)

### [Spring Boot](https://docs.spring.io/spring-boot/docs/2.2.4.RELEASE/reference/html/)

- goals
  - 快速Spring开发
  - 开箱即用
  - 提供许多非功能特征
  - 没有代码生成
- [Spring boot Feature](https://docs.spring.io/spring-boot/docs/2.2.4.RELEASE/reference/html/spring-boot-features.html#boot-features)
  - SpringApplication
    - @SpringBootApplication
  - Logging
    - **Commons Logging** ：该logging包给一下日志提供统一日志接口
    - Java Util Logging
    - Log4j2
    - Logback
  - data-bind
  - Json
    - jackson
    - gson
  - Testing
    - Unit Testing
    - Integration Testing
      - goals
      - TestContext
- Spring boot Actuator
  - health endpoint
- Spring Test
  - @SpringBootTest
  - @ContextConfiguration
- Deploy
  - cloud
  - docker
- DevOps
- Spring-boot-maven-plugin
- Spring Modules
  - spring-boot
  - spring-boot-autoconfigure
  - spring-boot-starters：
  - spring-boot-cli
  - spring-boot-actuator
  - spring-boot-actuator-autoconfigure
  - spring-boot-test
  - spring-boot-test-autoconfigure
  - spring-boot-loader
  - spring-boot-devtools
- non-functional features
  - embeded servers
  - security
  - metrics
  - health checks
  - externalized configuration
- appendix
  - Application Properties
  - Configuration Metadata
  - Auto-configuration
- [spring-boot-start](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#using-boot-starter)



#### Testing

- Spring boot Testing
  - Spring Testing
- [JUnit5](https://junit.org/junit5/)

### [Spring Framework](https://docs.spring.io/spring/docs/5.2.3.RELEASE/spring-framework-reference/)

- IOC/DI
  - ApplicationContext
- 配置资源
  - @Configuration
    - proxyBeanMethods
- Data Access
  - @Repository
- Web Servlet
  - @RestController
  - RequestMapping
- Enviroment / PropertySource
- 思想
  - 完好的兼容性
  - 尽可能推迟开发人员开发

### Spring Security

### [Spring Cloud](https://spring.io/projects/spring-cloud)

- [Spring Cloud Config](https://cloud.spring.io/spring-cloud-static/spring-cloud-config/2.2.1.RELEASE/reference/html/)
- Spring Cloud Vault
- [Spring Cloud Netflix](https://cloud.spring.io/spring-cloud-static/spring-cloud-netflix/2.2.1.RELEASE/reference/html/)
  - Service Discovery
  - Circuit Breaker
  - Declarative REST Client
  - Client Side Load Balancer
  - External Configuration
  - Router and Filter
- sample
  - [configserver](https://github.com/spring-cloud-samples/configserver)

### 思考方式

- 原理出发
  - 技术从哪里来
  - 技术怎么衍生
  - 技术的使用方式
  - 技术之间的关联技术
- 项目出发
- 从文档出发：
  - 了解技术分布特征
  - 了解其他资料（技术圈）的机会
- api角度
- 设计角度
- 基于已有知识模型构建
- 不基于已有知识模型构建

### 技术特点

- 使用annotation
- 找不到实现模型

### WEB框架的产生由来

### WEB规范

### Leanring

- 步步为营：需要综合看资料，尽可能覆盖更多的资料，而不是就某一个点进行深入专研