## Beans

### Beans 知识点

- Dependencies
  - Dependency injection
    - Constructor-based Dependency injection
    - Setter-based Dependency injection
    - Dependency Resolution Process
    - Examples of Dependency injection
  - Dependencies and Configuration in Detail
    - Straight Values(Primitives, Strings, and so on)
    - The idref element
    - Inner Beans
    - Collections
    - Collection Merging
    - Compound Property Names
  - Using depends-on
  - Lazy-initialized Beans
  - Autowiring Collaborators
    - Limitations and Disadvantages of Autowiring
    - Excluding a Bean from Autowiring
  - Method injection
    - Lookup Method Injection
    - Abitrary Method Replacements
- Bean Scopes(范围)
- customizing the nature of a bean
  - Lifecycle Callbacks
    - InitializingBean
    - DisposableBean
- Bean Definition Inheritance
- Container Extension Points
  - Customizing Beans by Using a `BeanPostProcessor`



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

