# Spring Interview Questions

![Spring Logo](https://spring.io/img/spring-2.svg)

Welcome to the Spring Interview Questions repository! This repository is your go-to resource for preparing for Spring Framework interviews. It includes a comprehensive collection of questions and answers covering a wide range of topics and difficulty levels.

## Introduction

This repository aims to help you prepare for Spring Framework interviews by providing a curated list of commonly asked questions along with detailed answers. Whether you're a beginner or an experienced developer, this resource will help you enhance your Spring knowledge and be well-prepared for your next interview.

## Topics Covered

- Spring Core
- Spring Boot
- Spring MVC
- Spring Data JPA
- Spring Security
- Spring AOP
- Spring Cloud
- Spring Batch
- Spring Integration

## How to Use

To use this repository, browse through the topics and questions. You can also clone the repository to your local machine for offline access.

```sh
git clone https://github.com/bikkimahato/spring-interview-questions.git
```

## Contributing

Contributions are welcome! If you have additional questions, answers, or improvements, please fork the repository and create a pull request. For major changes, please open an issue first to discuss what you would like to change.

---

Happy Interview Preparation!

Happy coding! If you find this repository helpful, please give it a star ⭐ and share it with others.

---

## Spring Core
### Table of Contents
### Level : Spring Core Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is the Spring Framework?](#1-what-is-the-spring-framework) |
| 2   | [What are the advantages of using Spring Framework?](#2-what-are-the-advantages-of-using-spring-framework) |
| 3   | [Explain Dependency Injection.](#3-explain-dependency-injection) |
| 4   | [What are the different types of Dependency Injection?](#4-what-are-the-different-types-of-dependency-injection) |
| 5   | [What is the BeanFactory in Spring?](#5-what-is-the-beanfactory-in-spring) |
| 6   | [What is the ApplicationContext in Spring?](#6-what-is-the-applicationcontext-in-spring) |
| 7   | [What is the difference between BeanFactory and ApplicationContext?](#7-what-is-the-difference-between-beanfactory-and-applicationcontext) |
| 8   | [How do you configure a Spring application using XML?](#8-how-do-you-configure-a-spring-application-using-xml) |
| 9   | [What is a Spring Bean?](#9-what-is-a-spring-bean) |
| 10  | [What are the different scopes of Spring Beans?](#10-what-are-the-different-scopes-of-spring-beans) |
| 11  | [How do you define a Spring Bean in XML configuration?](#11-how-do-you-define-a-spring-bean-in-xml-configuration) |
| 12  | [What is the default scope of a Spring Bean?](#12-what-is-the-default-scope-of-a-spring-bean) |
| 13  | [How do you inject a bean using constructor injection?](#13-how-do-you-inject-a-bean-using-constructor-injection) |
| 14  | [How do you inject a bean using setter injection?](#14-how-do-you-inject-a-bean-using-setter-injection) |
| 15  | [What is the role of the @Autowired annotation?](#15-what-is-the-role-of-the-autowired-annotation) |
| 16  | [What is the purpose of the @Component annotation?](#16-what-is-the-purpose-of-the-component-annotation) |
| 17  | [What are Spring stereotypes?](#17-what-are-spring-stereotypes) |
| 18  | [How do you enable component scanning in Spring?](#18-how-do-you-enable-component-scanning-in-spring) |
| 19  | [What is the difference between @Component, @Service, @Repository, and @Controller?](#19-what-is-the-difference-between-component-service-repository-and-controller) |
| 20  | [How do you handle bean autowiring in Spring?](#20-how-do-you-handle-bean-autowiring-in-spring) |
| 21  | [What is the use of the @Qualifier annotation?](#21-what-is-the-use-of-the-qualifier-annotation) |
| 22  | [What is the Spring IoC container?](#22-what-is-the-spring-ioc-container) |
| 23  | [Explain the lifecycle of a Spring Bean.](#23-explain-the-lifecycle-of-a-spring-bean) |
| 24  | [What is Spring AOP framework?](#24-what-is-spring-aop-framework) |
| 25  | [What is a pointcut in Spring AOP?](#25-what-is-a-pointcut-in-spring-aop) |
| 26  | [What is an advice in Spring AOP?](#26-what-is-an-advice-in-spring-aop) |
| 27  | [What are the different types of advice in Spring AOP?](#27-what-are-the-different-types-of-advice-in-spring-aop) |
| 28  | [What is a join point in Spring AOP?](#28-what-is-a-join-point-in-spring-aop) |
| 29  | [What is a proxy in Spring AOP?](#29-what-is-a-proxy-in-spring-aop) |
| 30  | [How do you configure AOP in Spring using XML?](#30-how-do-you-configure-aop-in-spring-using-xml) |
| 31  | [Explain the concept of Aspect in Spring AOP.](#31-explain-the-concept-of-aspect-in-spring-aop) |
| 32  | [What is the @Aspect annotation used for?](#32-what-is-the-aspect-annotation-used-for) |
| 33  | [How do you configure transactions in Spring?](#33-how-do-you-configure-transactions-in-spring) |
| 34  | [What is the @Transactional annotation?](#34-what-is-the-transactional-annotation) |
| 35  | [What is the difference between programmatic and declarative transaction management?](#35-what-is-the-difference-between-programmatic-and-declarative-transaction-management) |
| 36  | [How do you manage properties in Spring?](#36-how-do-you-manage-properties-in-spring) |
| 37  | [What is the Environment abstraction in Spring?](#37-what-is-the-environment-abstraction-in-spring) |
| 38  | [How do you use @PropertySource to load properties in Spring?](#38-how-do-you-use-propertysource-to-load-properties-in-spring) |
| 39  | [What is Spring Expression Language (SpEL)?](#39-what-is-spring-expression-language-spel) |
| 40  | [How do you use SpEL in Spring applications?](#40-how-do-you-use-spel-in-spring-applications) |
| 41  | [What is the purpose of the @Value annotation?](#41-what-is-the-purpose-of-the-value-annotation) |
| 42  | [What is the Spring JDBC template?](#42-what-is-the-spring-jdbc-template) |
| 43  | [How do you configure a DataSource in Spring?](#43-how-do-you-configure-a-datasource-in-spring) |
| 44  | [How do you use the JdbcTemplate in Spring?](#44-how-do-you-use-the-jdbctemplate-in-spring) |
| 45  | [What is the purpose of the @Repository annotation?](#45-what-is-the-purpose-of-the-repository-annotation) |
| 46  | [What is the Spring Data JPA?](#46-what-is-the-spring-data-jpa) |
| 47  | [How do you define a repository in Spring Data JPA?](#47-how-do-you-define-a-repository-in-spring-data-jpa) |
| 48  | [What is the purpose of the @Entity annotation?](#48-what-is-the-purpose-of-the-entity-annotation) |
| 49  | [What is the use of the @Id annotation in Spring Data JPA?](#49-what-is-the-use-of-the-id-annotation-in-spring-data-jpa) |
| 50  | [How do you define a primary key generation strategy in Spring Data JPA?](#50-how-do-you-define-a-primary-key-generation-strategy-in-spring-data-jpa) |

### Level : Spring Core Medium
| No. | Questions |
| --- | --------- |
| 51  | [How does Spring manage transactions?](#51-how-does-spring-manage-transactions) |
| 52  | [Explain the concept of Bean Post Processors.](#52-explain-the-concept-of-bean-post-processors) |
| 53  | [How do you create a custom Bean Post Processor?](#53-how-do-you-create-a-custom-bean-post-processor) |
| 54  | [What is the BeanFactoryPostProcessor and how is it different from BeanPostProcessor?](#54-what-is-the-beanfactorypostprocessor-and-how-is-it-different-from-beanpostprocessor) |
| 55  | [How does Spring handle circular dependencies?](#55-how-does-spring-handle-circular-dependencies) |
| 56  | [What is the use of the @Scope annotation?](#56-what-is-the-use-of-the-scope-annotation) |
| 57  | [Explain the concept of Spring Profiles.](#57-explain-the-concept-of-spring-profiles) |
| 58  | [How do you manage environment-specific properties in Spring?](#58-how-do-you-manage-environment-specific-properties-in-spring) |
| 59  | [What is the role of the @Profile annotation?](#59-what-is-the-role-of-the-profile-annotation) |
| 60  | [How do you enable asynchronous method execution in Spring?](#60-how-do-you-enable-asynchronous-method-execution-in-spring) |
| 61  | [What is the use of the @Async annotation?](#61-what-is-the-use-of-the-async-annotation) |
| 62  | [How do you implement caching in Spring?](#62-how-do-you-implement-caching-in-spring) |
| 63  | [What is the use of the @Cacheable annotation?](#63-what-is-the-use-of-the-cacheable-annotation) |
| 64  | [How do you configure a cache manager in Spring?](#64-how-do-you-configure-a-cache-manager-in-spring) |
| 65  | [What is the Spring Event model?](#65-what-is-the-spring-event-model) |
| 66  | [How do you publish and listen to events in Spring?](#66-how-do-you-publish-and-listen-to-events-in-spring) |
| 67  | [What is the use of the @EventListener annotation?](#67-what-is-the-use-of-the-eventlistener-annotation) |
| 68  | [What is Spring's Task Scheduler?](#68-what-is-springs-task-scheduler) |
| 69  | [How do you schedule tasks in Spring?](#69-how-do-you-schedule-tasks-in-spring) |
| 70  | [What is the use of the @Scheduled annotation?](#70-what-is-the-use-of-the-scheduled-annotation) |
| 71  | [What is the Spring Web MVC framework?](#71-what-is-the-spring-web-mvc-framework) |
| 72  | [How do you configure a DispatcherServlet in Spring?](#72-how-do-you-configure-a-dispatcherservlet-in-spring) |
| 73  | [What is the role of the @Controller annotation?](#73-what-is-the-role-of-the-controller-annotation) |
| 74  | [How do you handle form submissions in Spring MVC?](#74-how-do-you-handle-form-submissions-in-spring-mvc) |
| 75  | [What is the use of the @RequestMapping annotation?](#75-what-is-the-use-of-the-requestmapping-annotation) |
| 76  | [How do you handle exceptions in Spring MVC?](#76-how-do-you-handle-exceptions-in-spring-mvc) |
| 77  | [What is the use of the @ExceptionHandler annotation?](#77-what-is-the-use-of-the-exceptionhandler-annotation) |
| 78  | [How do you configure view resolvers in Spring MVC?](#78-how-do-you-configure-view-resolvers-in-spring-mvc) |
| 79  | [What is the use of the @ModelAttribute annotation?](#79-what-is-the-use-of-the-modelattribute-annotation) |
| 80  | [How do you perform validation in Spring MVC?](#80-how-do-you-perform-validation-in-spring-mvc) |
| 81  | [What is the use of the @Valid annotation?](#81-what-is-the-use-of-the-valid-annotation) |
| 82  | [How do you handle file uploads in Spring MVC?](#82-how-do-you-handle-file-uploads-in-spring-mvc) |
| 83  | [What is the use of the MultipartResolver in Spring MVC?](#83-what-is-the-use-of-the-multipartresolver-in-spring-mvc) |
| 84  | [Explain the concept of RestTemplate in Spring.](#84-explain-the-concept-of-resttemplate-in-spring) |
| 85  | [How do you configure RestTemplate in Spring?](#85-how-do-you-configure-resttemplate-in-spring) |
| 86  | [How do you make HTTP requests using RestTemplate?](#86-how-do-you-make-http-requests-using-resttemplate) |
| 87  | [What is the Spring WebFlux framework?](#87-what-is-the-spring-webflux-framework) |
| 88  | [How do you configure a WebFlux application in Spring?](#88-how-do-you-configure-a-webflux-application-in-spring) |
| 89  | [What is the role of the @RestController annotation?](#89-what-is-the-role-of-the-restcontroller-annotation) |
| 90  | [How do you handle reactive streams in Spring WebFlux?](#90-how-do-you-handle-reactive-streams-in-spring-webflux) |
| 91  | [What is the Spring Boot framework?](#91-what-is-the-spring-boot-framework) |
| 92  | [How do you configure a Spring Boot application?](#92-how-do-you-configure-a-spring-boot-application) |
| 93  | [What are the benefits of using Spring Boot?](#93-what-are-the-benefits-of-using-spring-boot) |
| 94  | [How do you create a RESTful web service using Spring Boot?](#94-how-do-you-create-a-restful-web-service-using-spring-boot) |
| 95  | [What is the role of the application.properties file in Spring Boot?](#95-what-is-the-role-of-the-application-properties-file-in-spring-boot) |
| 96  | [How do you configure logging in Spring Boot?](#96-how-do-you-configure-logging-in-spring-boot) |
| 97  | [How do you handle exceptions in a Spring Boot application?](#97-how-do-you-handle-exceptions-in-a-spring-boot-application) |
| 98  | [What is the use of the @SpringBootApplication annotation?](#98-what-is-the-use-of-the-springbootapplication-annotation) |
| 99  | [How do you run a Spring Boot application?](#99-how-do-you-run-a-spring-boot-application) |
| 100 | [How do you test a Spring Boot application?](#100-how-do-you-test-a-spring-boot-application) |

### Level : Spring Core Hard
| No. | Questions |
| --- | --------- |
| 101 | [Explain the concept of Reactive Programming in Spring.](#101-explain-the-concept-of-reactive-programming-in-spring) |
| 102 | [How does Spring WebFlux handle backpressure?](#102-how-does-spring-webflux-handle-backpressure) |
| 103 | [What is the difference between Spring MVC and Spring WebFlux?](#103-what-is-the-difference-between-spring-mvc-and-spring-webflux) |
| 104 | [How do you configure security in a Spring application?](#104-how-do-you-configure-security-in-a-spring-application) |
| 105 | [What is the role of the @EnableWebSecurity annotation?](#105-what-is-the-role-of-the-enablewebsecurity-annotation) |
| 106 | [How do you implement OAuth2 authentication in Spring Security?](#106-how-do-you-implement-oauth2-authentication-in-spring-security) |
| 107 | [What is the use of the @PreAuthorize annotation?](#107-what-is-the-use-of-the-preauthorize-annotation) |
| 108 | [How do you implement method-level security in Spring?](#108-how-do-you-implement-method-level-security-in-spring) |
| 109 | [How do you configure a custom authentication provider in Spring Security?](#109-how-do-you-configure-a-custom-authentication-provider-in-spring-security) |
| 110 | [What is the purpose of the SecurityContextHolder in Spring Security?](#110-what-is-the-purpose-of-the-securitycontextholder-in-spring-security) |
| 111 | [Explain the concept of CSRF protection in Spring Security.](#111-explain-the-concept-of-csrf-protection-in-spring-security) |
| 112 | [How do you configure session management in Spring Security?](#112-how-do-you-configure-session-management-in-spring-security) |
| 113 | [What is the use of the @EnableAspectJAutoProxy annotation?](#113-what-is-the-use-of-the-enableaspectjautoproxy-annotation) |
| 114 | [How do you implement global exception handling in Spring?](#114-how-do-you-implement-global-exception-handling-in-spring) |
| 115 | [What is the use of the @ControllerAdvice annotation?](#115-what-is-the-use-of-the-controlleradvice-annotation) |
| 116 | [How do you configure internationalization in a Spring application?](#116-how-do-you-configure-internationalization-in-a-spring-application) |
| 117 | [What is the use of the MessageSource interface in Spring?](#117-what-is-the-use-of-the-messagesource-interface-in-spring) |
| 118 | [How do you create a custom validator in Spring?](#118-how-do-you-create-a-custom-validator-in-spring) |
| 119 | [What is the use of the @InitBinder annotation?](#119-what-is-the-use-of-the-initbinder-annotation) |
| 120 | [How do you configure a custom property editor in Spring?](#120-how-do-you-configure-a-custom-property-editor-in-spring) |
| 121 | [Explain the concept of Spring Cloud.](#121-explain-the-concept-of-spring-cloud) |
| 122 | [How do you configure a microservice using Spring Cloud?](#122-how-do-you-configure-a-microservice-using-spring-cloud) |
| 123 | [What is the use of the @EnableEurekaClient annotation?](#123-what-is-the-use-of-the-enableeurekaclient-annotation) |
| 124 | [How do you configure load balancing in Spring Cloud?](#124-how-do-you-configure-load-balancing-in-spring-cloud) |
| 125 | [What is the use of the @EnableFeignClients annotation?](#125-what-is-the-use-of-the-enablefeignclients-annotation) |
| 126 | [How do you implement circuit breaker pattern in Spring Cloud?](#126-how-do-you-implement-circuit-breaker-pattern-in-spring-cloud) |
| 127 | [What is the use of the @EnableCircuitBreaker annotation?](#127-what-is-the-use-of-the-enablecircuitbreaker-annotation) |
| 128 | [How do you configure a distributed tracing system in Spring Cloud?](#128-how-do-you-configure-a-distributed-tracing-system-in-spring-cloud) |
| 129 | [What is the use of the @EnableHystrixDashboard annotation?](#129-what-is-the-use-of-the-enablehystrixdashboard-annotation) |
| 130 | [How do you configure a service gateway in Spring Cloud?](#130-how-do-you-configure-a-service-gateway-in-spring-cloud) |
| 131 | [What is the use of the @EnableZuulProxy annotation?](#131-what-is-the-use-of-the-enablezuulproxy-annotation) |
| 132 | [How do you implement API versioning in a Spring application?](#132-how-do-you-implement-api-versioning-in-a-spring-application) |
| 133 | [What is the use of the @JsonView annotation in Spring?](#133-what-is-the-use-of-the-jsonview-annotation-in-spring) |
| 134 | [How do you configure a custom JSON serializer in Spring?](#134-how-do-you-configure-a-custom-json-serializer-in-spring) |
| 135 | [What is the use of the @JsonIgnore annotation?](#135-what-is-the-use-of-the-jsonignore-annotation) |
| 136 | [How do you configure a custom exception handler in Spring?](#136-how-do-you-configure-a-custom-exception-handler-in-spring) |
| 137 | [What is the use of the @RestControllerAdvice annotation?](#137-what-is-the-use-of-the-restcontrolleradvice-annotation) |
| 138 | [How do you configure CORS in a Spring application?](#138-how-do-you-configure-cors-in-a-spring-application) |
| 139 | [What is the use of the @CrossOrigin annotation?](#139-what-is-the-use-of-the-crossorigin-annotation) |
| 140 | [How do you configure a custom HTTP message converter in Spring?](#140-how-do-you-configure-a-custom-http-message-converter-in-spring) |
| 141 | [What is the use of the HttpMessageConverter interface in Spring?](#141-what-is-the-use-of-the-httpmessageconverter-interface-in-spring) |
| 142 | [How do you configure a custom view resolver in Spring?](#142-how-do-you-configure-a-custom-view-resolver-in-spring) |
| 143 | [What is the use of the ViewResolver interface in Spring?](#143-what-is-the-use-of-the-viewresolver-interface-in-spring) |
| 144 | [How do you configure a custom locale resolver in Spring?](#144-how-do-you-configure-a-custom-locale-resolver-in-spring) |
| 145 | [What is the use of the LocaleResolver interface in Spring?](#145-what-is-the-use-of-the-localeresolver-interface-in-spring) |
| 146 | [How do you configure a custom theme resolver in Spring?](#146-how-do-you-configure-a-custom-theme-resolver-in-spring) |
| 147 | [What is the use of the ThemeResolver interface in Spring?](#147-what-is-the-use-of-the-themeresolver-interface-in-spring) |
| 148 | [How do you configure a custom session attribute in Spring?](#148-how-do-you-configure-a-custom-session-attribute-in-spring) |
| 149 | [What is the use of the SessionAttributeStore interface in Spring?](#149-what-is-the-use-of-the-sessionattributestore-interface-in-spring) |
| 150 | [How do you configure a custom handler interceptor in Spring?](#150-how-do-you-configure-a-custom-handler-interceptor-in-spring) |

# Spring Core Easy Interview Questions and Answers
### 1. What is the Spring Framework?

The Spring Framework is an open-source application framework that provides comprehensive infrastructure support for developing Java applications. It was initially released in 2003 by Rod Johnson. Spring makes it easier to create enterprise-level applications by providing various modules and extensions to build robust and maintainable applications.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 2. What are the advantages of using Spring Framework?

- **Modularity**: Spring is divided into several modules, allowing developers to use only the parts they need.
- **Dependency Injection**: Promotes loose coupling by allowing objects to be injected into other objects.
- **Aspect-Oriented Programming (AOP)**: Helps separate cross-cutting concerns such as logging, security, and transaction management.
- **Transaction Management**: Simplifies the management of transactions.
- **Integration with Other Frameworks**: Easily integrates with other frameworks like Hibernate, JPA, and Struts.
- **Testability**: Provides support for unit testing and integration testing.
- **Community Support**: Large community and extensive documentation.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 3. Explain Dependency Injection.

Dependency Injection (DI) is a design pattern that allows an object to be created and injected with its dependencies by an external entity. This promotes loose coupling between objects and enhances testability and maintainability.

**Example:**

```java
// Service interface
public interface MessageService {
    void sendMessage(String message, String receiver);
}

// Service implementation
public class EmailService implements MessageService {
    @Override
    public void sendMessage(String message, String receiver) {
        System.out.println("Email sent to " + receiver + " with Message: " + message);
    }
}

// Consumer class
public class MyApplication {
    private MessageService service;

    // Constructor-based dependency injection
    public MyApplication(MessageService service) {
        this.service = service;
    }

    public void processMessage(String message, String receiver) {
        service.sendMessage(message, receiver);
    }
}

// Main class
public class MainApp {
    public static void main(String[] args) {
        // Injecting dependency
        MessageService service = new EmailService();
        MyApplication app = new MyApplication(service);
        app.processMessage("Hello", "john@example.com");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 4. What are the different types of Dependency Injection?

- **Constructor Injection**: Dependencies are provided through a class constructor.
- **Setter Injection**: Dependencies are provided through setter methods.
- **Interface Injection**: Dependencies are provided through an interface method (less common).

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 5. What is the BeanFactory in Spring?

BeanFactory is the root interface for accessing a Spring bean container. It provides the configuration framework and basic functionality for managing beans. BeanFactory is lightweight and is typically used in simple applications or scenarios where resources are limited.

**Example:**

```java
// XML Configuration (beans.xml)
<beans>
    <bean id="myBean" class="com.example.MyBean"/>
</beans>

// Java Code
public class MainApp {
    public static void main(String[] args) {
        Resource resource = new ClassPathResource("beans.xml");
        BeanFactory factory = new XmlBeanFactory(resource);
        MyBean myBean = (MyBean) factory.getBean("myBean");
        myBean.doSomething();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 6. What is the ApplicationContext in Spring?

ApplicationContext is an extension of BeanFactory that provides more advanced features. It includes functionalities such as internationalization, event propagation, declarative mechanisms to create a bean, and various ways to look up a bean. It is more feature-rich and is typically used in enterprise applications.

**Example:**

```java
// XML Configuration (beans.xml)
<beans>
    <bean id="myBean" class="com.example.MyBean"/>
</beans>

// Java Code
public class MainApp {
    public static void main(String[] args) {
        ApplicationContext context = new ClassPathXmlApplicationContext("beans.xml");
        MyBean myBean = (MyBean) context.getBean("myBean");
        myBean.doSomething();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 7. What is the difference between BeanFactory and ApplicationContext?

| Feature            | BeanFactory                              | ApplicationContext                          |
|--------------------|------------------------------------------|---------------------------------------------|
| Initialization     | Lazy initialization                      | Eager initialization                        |
| Advanced Features  | Limited                                  | Provides advanced features like event propagation, declarative mechanisms, etc. |
| Internationalization | Not supported                            | Supported                                   |
| Event Handling     | Not supported                            | Supported                                   |
| Dependency Injection | Basic                                   | Advanced (supports annotations, AOP, etc.) |

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 8. How do you configure a Spring application using XML?

**Example:**

```xml
<!-- beans.xml -->
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
                           http://www.springframework.org/schema/beans/spring-beans.xsd">

    <bean id="myBean" class="com.example.MyBean">
        <property name="property" value="value"/>
    </bean>

</beans>
```

```java
// Java Code
public class MainApp {
    public static void main(String[] args) {
        ApplicationContext context = new ClassPathXmlApplicationContext("beans.xml");
        MyBean myBean = (MyBean) context.getBean("myBean");
        myBean.doSomething();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 9. What is a Spring Bean?

A Spring Bean is an object that is instantiated, assembled, and otherwise managed by the Spring IoC (Inversion of Control) container. Beans are the fundamental building blocks of a Spring application.

**Example:**

```java
public class MyBean {
    private String property;

    public void setProperty(String property) {
        this.property = property;
    }

    public void doSomething() {
        System.out.println("Property value: " + property);
    }
}
```

```xml
<!-- beans.xml -->
<beans>
    <bean id="myBean" class="com.example.MyBean">
        <property name="property" value="value"/>
    </bean>
</beans>
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 10. What are the different scopes of Spring Beans?

- **Singleton**: Only one instance of the bean is created for the Spring container. This is the default scope.
- **Prototype**: A new instance is created each time the bean is requested.
- **Request**: A new instance is created for each HTTP request. Applicable only in the context of a web-aware Spring ApplicationContext.
- **Session**: A new instance is created for each HTTP session. Applicable only in the context of a web-aware Spring ApplicationContext.
- **Global-session**: A single instance is created for the global HTTP session. Applicable only in the context of a web-aware Spring ApplicationContext.

**Example:**

```xml
<!-- beans.xml -->
<beans>
    <bean id="singletonBean" class="com.example.SingletonBean" scope="singleton"/>
    <bean id="prototypeBean" class="com.example.PrototypeBean" scope="prototype"/>
</beans>
```

```java
public class MainApp {
    public static void main(String[] args) {
        ApplicationContext context = new ClassPathXmlApplicationContext("beans.xml");

        // Singleton Scope
        SingletonBean singletonBean1 = (SingletonBean) context.getBean("singletonBean");
        SingletonBean singletonBean2 = (SingletonBean) context.getBean("singletonBean");
        System.out.println(singletonBean1 == singletonBean2); // true

        // Prototype Scope
        PrototypeBean prototypeBean1 = (PrototypeBean) context.getBean("prototypeBean");
        PrototypeBean prototypeBean2 = (PrototypeBean) context.getBean("prototypeBean");
        System.out.println(prototypeBean1 == prototypeBean2); // false
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 11. How do you define a Spring Bean in XML configuration?

A Spring Bean can be defined in the XML configuration file using the `<bean>` element. The `id` attribute specifies the bean's identifier, and the `class` attribute specifies the fully qualified class name of the bean.

**Example:**

```xml
<!-- beans.xml -->
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
                           http://www.springframework.org/schema/beans/spring-beans.xsd">

    <bean id="myBean" class="com.example.MyBean">
        <property name="property" value="value"/>
    </bean>

</beans>
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 12. What is the default scope of a Spring Bean?

The default scope of a Spring Bean is `singleton`. This means that only one instance of the bean is created for the Spring container.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 13. How do you inject a bean using constructor injection?

Constructor injection is performed by defining a constructor in the bean class and specifying the dependencies in the XML configuration.

**Example:**

```java
public class MyBean {
    private final Dependency dependency;

    // Constructor
    public MyBean(Dependency dependency) {
        this.dependency = dependency;
    }

    public void doSomething() {
        dependency.perform();
    }
}
```

```xml
<!-- beans.xml -->
<beans>
    <bean id="dependency" class="com.example.Dependency"/>
    <bean id="myBean" class="com.example.MyBean">
        <constructor-arg ref="dependency"/>
    </bean>
</beans>
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 14. How do you inject a bean using setter injection?

Setter injection is performed by defining setter methods in the bean class and specifying the dependencies in the XML configuration.

**Example:**

```java
public class MyBean {
    private Dependency dependency;

    // Setter method
    public void setDependency(Dependency dependency) {
        this.dependency = dependency;
    }

    public void doSomething() {
        dependency.perform();
    }
}
```

```xml
<!-- beans.xml -->
<beans>
    <bean id="dependency" class="com.example.Dependency"/>
    <bean id="myBean" class="com.example.MyBean">
        <property name="dependency" ref="dependency"/>
    </bean>
</beans>
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 15. What is the role of the @Autowired annotation?

The `@Autowired` annotation is used for automatic dependency injection in Spring. It can be applied to constructors, setter methods, and fields. Spring will automatically wire the annotated dependency by type.

**Example:**

```java
@Component
public class MyBean {
    @Autowired
    private Dependency dependency;

    public void doSomething() {
        dependency.perform();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 16. What is the purpose of the @Component annotation?

The `@Component` annotation indicates that a class is a Spring component. It is a generic stereotype for any Spring-managed component and allows Spring to automatically detect and register the bean.

**Example:**

```java
@Component
public class MyBean {
    public void doSomething() {
        System.out.println("Doing something...");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 17. What are Spring stereotypes?

Spring stereotypes are annotations that indicate the role of a Spring-managed component. These annotations help in better organizing and managing the components within a Spring application. Common stereotypes include `@Component`, `@Service`, `@Repository`, and `@Controller`.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 18. How do you enable component scanning in Spring?

Component scanning is enabled using the `<context:component-scan>` element in XML configuration or the `@ComponentScan` annotation in Java configuration.

**Example (XML Configuration):**

```xml
<!-- beans.xml -->
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xmlns:context="http://www.springframework.org/schema/context"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
                           http://www.springframework.org/schema/beans/spring-beans.xsd
                           http://www.springframework.org/schema/context
                           http://www.springframework.org/schema/context/spring-context.xsd">

    <context:component-scan base-package="com.example"/>
</beans>
```

**Example (Java Configuration):**

```java
@Configuration
@ComponentScan(basePackages = "com.example")
public class AppConfig {
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 19. What is the difference between @Component, @Service, @Repository, and @Controller?

| Annotation    | Description                                                             |
|---------------|-------------------------------------------------------------------------|
| `@Component`  | Generic stereotype for any Spring-managed component.                    |
| `@Service`    | Specialization of `@Component` for service layer components.           |
| `@Repository` | Specialization of `@Component` for DAO (Data Access Object) components.|
| `@Controller` | Specialization of `@Component` for web controllers in Spring MVC.      |

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 20. How do you handle bean autowiring in Spring?

Bean autowiring in Spring can be handled using the `@Autowired` annotation, which can be applied to fields, constructors, and setter methods. Spring will automatically resolve and inject the dependencies.

**Example:**

```java
@Component
public class MyBean {
    @Autowired
    private Dependency dependency;

    public void doSomething() {
        dependency.perform();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 21. What is the use of the @Qualifier annotation?

The `@Qualifier` annotation is used to resolve the ambiguity when multiple beans of the same type are available in the Spring context. It specifies which bean should be injected.

**Example:**

```java
@Component
public class MyBean {
    @Autowired
    @Qualifier("specificDependency")
    private Dependency dependency;

    public void doSomething() {
        dependency.perform();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 22. What is the Spring IoC container?

The Spring IoC (Inversion of Control) container is responsible for managing the lifecycle and configuration of application objects (beans). It uses dependency injection to manage components and their dependencies.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 23. Explain the lifecycle of a Spring Bean.

1. **Instantiation**: The bean is instantiated.
2. **Populate Properties**: Spring IoC container populates the bean properties.
3. **BeanNameAware**: If the bean implements `BeanNameAware`, Spring calls `setBeanName()`.
4. **BeanFactoryAware**: If the bean implements `BeanFactoryAware`, Spring calls `setBeanFactory()`.
5. **ApplicationContextAware**: If the bean implements `ApplicationContextAware`, Spring calls `setApplicationContext()`.
6. **Pre-initialization (BeanPostProcessor)**: If there are any `BeanPostProcessor`s, their `postProcessBeforeInitialization()` methods are called.
7. **InitializingBean**: If the bean implements `InitializingBean`, Spring calls `afterPropertiesSet()`.
8. **Custom init-method**: If a custom init-method is specified, it is called.
9. **Post-initialization (BeanPostProcessor)**: If there are any `BeanPostProcessor`s, their `postProcessAfterInitialization()` methods are called.
10. **Bean is ready to use**: The bean is fully initialized and ready for use.
11. **DisposableBean**: When the container is shutting down, if the bean implements `DisposableBean`, Spring calls `destroy()`.
12. **Custom destroy-method**: If a custom destroy-method is specified, it is called.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 24. What is Spring AOP framework?

Spring AOP (Aspect-Oriented Programming) framework allows the separation of cross-cutting concerns (such as logging, security, transaction management) from the main business logic. It provides a way to dynamically add behavior to existing code without modifying the code.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 25. What is a pointcut in Spring AOP?

A pointcut is an expression that matches join points (points in program execution, such as method execution). It defines where the advice should be applied.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 26. What is an advice in Spring AOP?

An advice is an action taken by an aspect at a particular join point. It defines what should be done at a matched join point.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 27. What are the different types of advice in Spring AOP?

- **Before Advice**: Executes before a join point.
- **After (finally) Advice**: Executes after a join point, regardless of the outcome.
- **After Returning Advice**: Executes after a join point completes normally.
- **After Throwing Advice**: Executes if a method exits by throwing an exception.
- **Around Advice**: Surrounds a join point; it can control whether the join point is executed.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 28. What is a join point in Spring AOP?

A join point is a point in the execution of the program, such as the execution of a method or the handling of an exception, where an aspect can be applied.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 29. What is a proxy in Spring AOP?

A proxy is an object created by the AOP framework to implement the advised methods. It acts as an intermediary between the caller and the target object and is responsible for invoking the advice at the appropriate join points.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 30. How do you configure AOP in Spring using XML?

**Example:**

```xml
<!-- beans.xml -->
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xmlns:aop="http://www.springframework.org/schema/aop"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
                           http://www.springframework.org/schema/beans/spring-beans.xsd
                           http://www.springframework.org/schema/aop
                           http://www.springframework.org/schema/aop/spring-aop.xsd">

    <!-- Aspect -->
    <bean id="myAspect" class="com.example.MyAspect"/>

    <!-- AOP Configuration -->
    <aop:config>
        <aop:aspect ref="myAspect">
            <aop:pointcut id="myPointcut" expression="execution(* com.example..*(..))"/>
            <aop:before method="beforeAdvice" pointcut-ref="myPointcut"/>
        </aop:aspect>
    </aop:config>

</beans>
```

```java
// Aspect class
public class MyAspect {
    public void beforeAdvice() {
        System.out.println("Executing before advice");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 31. Explain the concept of Aspect in Spring AOP.

An Aspect in Spring AOP is a modularization of a cross-cutting concern, such as transaction management or logging. Aspects encapsulate behaviors that affect multiple classes into reusable modules. An Aspect can contain multiple advices (actions) to be executed at specific join points within the application.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 32. What is the @Aspect annotation used for?

The `@Aspect` annotation is used to mark a class as an aspect, which contains advice and pointcut definitions. It is part of the Spring AOP framework and indicates that the class contains cross-cutting concerns.

**Example:**

```java
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;

@Aspect
public class LoggingAspect {
    @Before("execution(* com.example.service.*.*(..))")
    public void logBefore() {
        System.out.println("Logging before method execution");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 33. How do you configure transactions in Spring?

Transactions in Spring can be configured using XML configuration or annotations. The most common approach is to use the `@Transactional` annotation on methods or classes that require transactional behavior.

**XML Configuration:**

```xml
<!-- beans.xml -->
<beans>
    <tx:annotation-driven transaction-manager="transactionManager"/>
    <bean id="transactionManager" class="org.springframework.jdbc.datasource.DataSourceTransactionManager">
        <property name="dataSource" ref="dataSource"/>
    </bean>
</beans>
```

**Java Configuration:**

```java
@Configuration
@EnableTransactionManagement
public class AppConfig {
    @Bean
    public DataSource dataSource() {
        return new DriverManagerDataSource("jdbc:mysql://localhost:3306/mydb", "user", "password");
    }

    @Bean
    public PlatformTransactionManager transactionManager(DataSource dataSource) {
        return new DataSourceTransactionManager(dataSource);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 34. What is the @Transactional annotation?

The `@Transactional` annotation is used to declare transaction boundaries on methods or classes. When applied, it manages the transaction lifecycle, including starting, committing, and rolling back transactions as needed.

**Example:**

```java
@Service
public class MyService {
    @Transactional
    public void performTransaction() {
        // transactional code here
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 35. What is the difference between programmatic and declarative transaction management?

- **Programmatic Transaction Management**: Transactions are managed explicitly in the code using the `TransactionTemplate` or `PlatformTransactionManager` API.
- **Declarative Transaction Management**: Transactions are managed using annotations (`@Transactional`) or XML configuration, allowing Spring to handle the transaction lifecycle automatically.

**Example (Programmatic):**

```java
public class MyService {
    @Autowired
    private PlatformTransactionManager transactionManager;

    public void performTransaction() {
        TransactionTemplate transactionTemplate = new TransactionTemplate(transactionManager);
        transactionTemplate.execute(status -> {
            // transactional code here
            return null;
        });
    }
}
```

**Example (Declarative):**

```java
@Service
public class MyService {
    @Transactional
    public void performTransaction() {
        // transactional code here
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 36. How do you manage properties in Spring?

Properties can be managed using property files and the `@Value` annotation or `Environment` abstraction. Properties can be loaded using the `@PropertySource` annotation or XML configuration.

**Example (Java Configuration):**

```java
@Configuration
@PropertySource("classpath:application.properties")
public class AppConfig {
    @Autowired
    private Environment env;

    @Bean
    public MyBean myBean() {
        return new MyBean(env.getProperty("my.property"));
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 37. What is the Environment abstraction in Spring?

The `Environment` abstraction in Spring represents the environment in which the application is running. It provides access to properties, profiles, and system/environment variables.

**Example:**

```java
@Autowired
private Environment env;

public void printProperty() {
    String property = env.getProperty("my.property");
    System.out.println(property);
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 38. How do you use @PropertySource to load properties in Spring?

The `@PropertySource` annotation is used to load properties from a specified resource file into the Spring Environment.

**Example:**

```java
@Configuration
@PropertySource("classpath:application.properties")
public class AppConfig {
    @Bean
    public MyBean myBean(@Value("${my.property}") String myProperty) {
        return new MyBean(myProperty);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 39. What is Spring Expression Language (SpEL)?

Spring Expression Language (SpEL) is a powerful expression language that supports querying and manipulating an object graph at runtime. It can be used in various Spring features, such as defining bean properties, conditional configuration, and more.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 40. How do you use SpEL in Spring applications?

SpEL can be used within annotations and XML configuration to dynamically evaluate expressions.

**Example:**

```java
@Component
public class MyBean {
    @Value("#{systemProperties['user.name']}")
    private String userName;

    public void printUserName() {
        System.out.println(userName);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 41. What is the purpose of the @Value annotation?

The `@Value` annotation is used to inject values into fields, method parameters, or constructor arguments. It supports property placeholders and SpEL expressions.

**Example:**

```java
@Component
public class MyBean {
    @Value("${my.property}")
    private String myProperty;

    public void printProperty() {
        System.out.println(myProperty);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 42. What is the Spring JDBC template?

The Spring JDBC template simplifies the use of JDBC and helps to avoid common errors. It handles the creation and release of resources, simplifies error handling, and reduces boilerplate code.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 43. How do you configure a DataSource in Spring?

A `DataSource` can be configured using XML configuration or Java configuration.

**XML Configuration:**

```xml
<!-- beans.xml -->
<beans>
    <bean id="dataSource" class="org.springframework.jdbc.datasource.DriverManagerDataSource">
        <property name="driverClassName" value="com.mysql.cj.jdbc.Driver"/>
        <property name="url" value="jdbc:mysql://localhost:3306/mydb"/>
        <property name="username" value="user"/>
        <property name="password" value="password"/>
    </bean>
</beans>
```

**Java Configuration:**

```java
@Configuration
public class AppConfig {
    @Bean
    public DataSource dataSource() {
        DriverManagerDataSource dataSource = new DriverManagerDataSource();
        dataSource.setDriverClassName("com.mysql.cj.jdbc.Driver");
        dataSource.setUrl("jdbc:mysql://localhost:3306/mydb");
        dataSource.setUsername("user");
        dataSource.setPassword("password");
        return dataSource;
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 44. How do you use the JdbcTemplate in Spring?

The `JdbcTemplate` is used to interact with the database by executing SQL queries, updates, and stored procedures.

**Example:**

```java
@Repository
public class UserRepository {
    @Autowired
    private JdbcTemplate jdbcTemplate;

    public List<User> findAll() {
        return jdbcTemplate.query("SELECT * FROM users", new BeanPropertyRowMapper<>(User.class));
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 45. What is the purpose of the @Repository annotation?

The `@Repository` annotation indicates that a class is a Data Access Object (DAO). It is a specialization of `@Component`, used for classes that directly access the database.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 46. What is the Spring Data JPA?

Spring Data JPA is a part of the Spring Data project that simplifies data access using the Java Persistence API (JPA). It provides repository abstractions for JPA and simplifies the implementation of data access layers.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 47. How do you define a repository in Spring Data JPA?

Repositories in Spring Data JPA are defined by extending `JpaRepository` or other repository interfaces.

**Example:**

```java
public interface UserRepository extends JpaRepository<User, Long> {
    List<User> findByLastName(String lastName);
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 48. What is the purpose of the @Entity annotation?

The `@Entity` annotation specifies that a class is an entity and is mapped to a database table. It is used in JPA to define the data model.

**Example:**

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String firstName;
    private String lastName;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 49. What is the use of the @Id annotation in Spring Data JPA?

The `@Id` annotation is used to specify the primary key of an entity. It is applied to a field or property of the entity class.

**Example:**

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String firstName;
    private String lastName;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-core-easy)**
---

### 50. How do you define a primary key generation strategy in Spring Data JPA?

The primary key generation strategy is defined using the `@GeneratedValue` annotation along with the `strategy` attribute.

**Example:**

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String firstName;
    private String lastName;
    // getters and setters
}
```

The `strategy` attribute can take the following values:
- `GenerationType.AUTO`: The persistence provider chooses the appropriate strategy.
- `GenerationType.IDENTITY`: The database generates the primary key.
- `GenerationType.SEQUENCE`: Uses a database sequence.
- `GenerationType.TABLE`: Uses a database table to generate primary keys.

#### **[⬆ Back to Top](#level--spring-core-easy)**
---

# Spring Core Medium Interview Questions and Answers
### 51. How does Spring manage transactions?

Spring manages transactions using the `PlatformTransactionManager` interface and its implementations. It can manage transactions declaratively using the `@Transactional` annotation or programmatically using `TransactionTemplate`. Spring handles the transaction lifecycle, including starting, committing, and rolling back transactions as needed.

**Example:**

```java
@Service
public class MyService {
    @Transactional
    public void performTransaction() {
        // transactional code here
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 52. Explain the concept of Bean Post Processors.

Bean Post Processors are special beans that allow you to modify or wrap beans before and after their initialization. They implement the `BeanPostProcessor` interface and can be used to add custom logic or behavior to bean creation.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 53. How do you create a custom Bean Post Processor?

To create a custom Bean Post Processor, implement the `BeanPostProcessor` interface and override its `postProcessBeforeInitialization` and `postProcessAfterInitialization` methods.

**Example:**

```java
import org.springframework.beans.factory.config.BeanPostProcessor;
import org.springframework.stereotype.Component;

@Component
public class CustomBeanPostProcessor implements BeanPostProcessor {
    @Override
    public Object postProcessBeforeInitialization(Object bean, String beanName) {
        // custom logic before initialization
        return bean;
    }

    @Override
    public Object postProcessAfterInitialization(Object bean, String beanName) {
        // custom logic after initialization
        return bean;
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 54. What is the BeanFactoryPostProcessor and how is it different from BeanPostProcessor?

`BeanFactoryPostProcessor` is used to modify the `BeanFactory` configuration metadata before any beans are instantiated. It is different from `BeanPostProcessor`, which modifies bean instances after they are created.

**Example:**

```java
import org.springframework.beans.factory.config.BeanFactoryPostProcessor;
import org.springframework.beans.factory.config.ConfigurableListableBeanFactory;
import org.springframework.stereotype.Component;

@Component
public class CustomBeanFactoryPostProcessor implements BeanFactoryPostProcessor {
    @Override
    public void postProcessBeanFactory(ConfigurableListableBeanFactory beanFactory) {
        // custom logic to modify BeanFactory configuration
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 55. How does Spring handle circular dependencies?

Spring handles circular dependencies by using a three-phase process:
1. Create bean instances and store them in a cache.
2. Populate properties of the beans.
3. Initialize beans.

If a circular dependency is detected, Spring uses proxies or `ObjectFactory` to break the cycle.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 56. What is the use of the @Scope annotation?

The `@Scope` annotation specifies the scope of a bean. Common scopes are `singleton`, `prototype`, `request`, `session`, and `application`.

**Example:**

```java
@Component
@Scope("prototype")
public class MyBean {
    // bean definition
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 57. Explain the concept of Spring Profiles.

Spring Profiles allow you to group beans and configurations and activate them based on the environment or runtime conditions. Profiles help manage environment-specific configurations.

**Example:**

```java
@Configuration
@Profile("dev")
public class DevConfig {
    @Bean
    public MyBean myBean() {
        return new MyBean();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 58. How do you manage environment-specific properties in Spring?

Environment-specific properties can be managed using property files and the `@PropertySource` annotation. Profiles can be used to load different properties based on the active profile.

**Example:**

```java
@Configuration
@PropertySource("classpath:application-${spring.profiles.active}.properties")
public class AppConfig {
    @Autowired
    private Environment env;

    @Bean
    public MyBean myBean() {
        return new MyBean(env.getProperty("my.property"));
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 59. What is the role of the @Profile annotation?

The `@Profile` annotation is used to define beans that should only be created when a specific profile is active. It helps manage environment-specific beans and configurations.

**Example:**

```java
@Configuration
@Profile("prod")
public class ProdConfig {
    @Bean
    public MyBean myBean() {
        return new MyBean();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 60. How do you enable asynchronous method execution in Spring?

Asynchronous method execution in Spring can be enabled using the `@EnableAsync` annotation and the `@Async` annotation on methods.

**Example:**

```java
@Configuration
@EnableAsync
public class AppConfig {
    // configuration
}

@Service
public class MyService {
    @Async
    public void asyncMethod() {
        // asynchronous code
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---