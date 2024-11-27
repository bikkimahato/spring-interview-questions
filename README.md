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