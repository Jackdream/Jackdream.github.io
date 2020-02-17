## Beans

### Beans 知识点



### Beans 模式

- BeanDefinitionReader
  - XmlBeanDefinitionReader
- DefaultListableBeanFactory
  - ConfigurableListableBeanFactory
  - BeanDefinitionRegistry



- `Container
  - ApplicationContext : instantiating, configuring, and assembling the beans
  - Configuration metadata - BeanDefinition
    - xml
    - Java annotation
    - Java code



- bean definition: correspond to the actual objects
  - service layer objects
  - data access objects
  - presentation objects
    - Struts Action
  - infrastructure objects
    - Hibernate
    - SessionFactories
    - JMS Queues



### 语言提炼/收集

- Context
- Reader
- Factory
- Registry: 注册表

