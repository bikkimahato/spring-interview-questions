# Spring Interview Questions

![Spring Logo](https://spring.io/img/spring-2.svg)

Welcome to the Spring Interview Questions repository! This repository is your go-to resource for preparing for Spring Framework interviews. It includes a comprehensive collection of questions and answers covering a wide range of topics and difficulty levels.

## Introduction

This repository aims to help you prepare for Spring Framework interviews by providing a curated list of commonly asked questions along with detailed answers. Whether you're a beginner or an experienced developer, this resource will help you enhance your Spring knowledge and be well-prepared for your next interview.

## Topics Covered

- [Spring Core](#spring-core)
- [Spring MVC](#spring-mvc)
- [Spring Data JPA](#spring-data-jpa)
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

## Spring MVC
### Table of Contents
### Level : Spring MVC Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is Spring MVC?](#1-what-is-spring-mvc) |
| 2   | [Explain the architecture of Spring MVC.](#2-explain-the-architecture-of-spring-mvc) |
| 3   | [What are the main components of Spring MVC?](#3-what-are-the-main-components-of-spring-mvc) |
| 4   | [How do you configure Spring MVC in a web application?](#4-how-do-you-configure-spring-mvc-in-a-web-application) |
| 5   | [What is the role of DispatcherServlet in Spring MVC?](#5-what-is-the-role-of-dispatcherservlet-in-spring-mvc) |
| 6   | [How do you define a controller in Spring MVC?](#6-how-do-you-define-a-controller-in-spring-mvc) |
| 7   | [What is the use of @RequestMapping annotation?](#7-what-is-the-use-of-requestmapping-annotation) |
| 8   | [How do you handle form submission in Spring MVC?](#8-how-do-you-handle-form-submission-in-spring-mvc) |
| 9   | [What is ModelAndView in Spring MVC?](#9-what-is-modelandview-in-spring-mvc) |
| 10  | [How do you return JSON data from a Spring MVC controller?](#10-how-do-you-return-json-data-from-a-spring-mvc-controller) |
| 11  | [Explain the difference between @Controller and @RestController.](#11-explain-the-difference-between-controller-and-restcontroller) |
| 12  | [What is the use of @PathVariable annotation?](#12-what-is-the-use-of-pathvariable-annotation) |
| 13  | [How do you inject a service into a Spring MVC controller?](#13-how-do-you-inject-a-service-into-a-spring-mvc-controller) |
| 14  | [What is the role of ViewResolver in Spring MVC?](#14-what-is-the-role-of-viewresolver-in-spring-mvc) |
| 15  | [How do you handle exceptions in Spring MVC?](#15-how-do-you-handle-exceptions-in-spring-mvc) |
| 16  | [What is the difference between @RequestParam and @PathVariable?](#16-what-is-the-difference-between-requestparam-and-pathvariable) |
| 17  | [How do you perform validation in Spring MVC?](#17-how-do-you-perform-validation-in-spring-mvc) |
| 18  | [What is the use of @ModelAttribute annotation?](#18-what-is-the-use-of-modelattribute-annotation) |
| 19  | [How do you configure a view resolver in Spring MVC?](#19-how-do-you-configure-a-view-resolver-in-spring-mvc) |
| 20  | [What is the default scope of a Spring MVC controller?](#20-what-is-the-default-scope-of-a-spring-mvc-controller) |
| 21  | [How do you handle file uploads in Spring MVC?](#21-how-do-you-handle-file-uploads-in-spring-mvc) |
| 22  | [What is the difference between @RequestBody and @ResponseBody?](#22-what-is-the-difference-between-requestbody-and-responsebody) |
| 23  | [How do you configure a multipart resolver in Spring MVC?](#23-how-do-you-configure-a-multipart-resolver-in-spring-mvc) |
| 24  | [How do you enable Spring MVC annotations?](#24-how-do-you-enable-spring-mvc-annotations) |
| 25  | [What is the use of @SessionAttributes annotation?](#25-what-is-the-use-of-sessionattributes-annotation) |

### Level : Spring MVC Medium
| No. | Questions |
| --- | --------- |
| 26  | [How do you manage static resources in Spring MVC?](#26-how-do-you-manage-static-resources-in-spring-mvc) |
| 27  | [Explain the role of HandlerMapping in Spring MVC.](#27-explain-the-role-of-handlermapping-in-spring-mvc) |
| 28  | [What is the use of @InitBinder annotation?](#28-what-is-the-use-of-initbinder-annotation) |
| 29  | [How do you handle cross-origin requests in Spring MVC?](#29-how-do-you-handle-cross-origin-requests-in-spring-mvc) |
| 30  | [How do you configure internationalization in Spring MVC?](#30-how-do-you-configure-internationalization-in-spring-mvc) |
| 31  | [What is the role of Interceptor in Spring MVC?](#31-what-is-the-role-of-interceptor-in-spring-mvc) |
| 32  | [How do you implement security in a Spring MVC application?](#32-how-do-you-implement-security-in-a-spring-mvc-application) |
| 33  | [What is the difference between Spring MVC and Spring Boot?](#33-what-is-the-difference-between-spring-mvc-and-spring-boot) |
| 34  | [How do you configure a custom HandlerExceptionResolver in Spring MVC?](#34-how-do-you-configure-a-custom-handlerexceptionresolver-in-spring-mvc) |
| 35  | [What is the use of @CookieValue annotation?](#35-what-is-the-use-of-cookievalue-annotation) |
| 36  | [How do you configure message converters in Spring MVC?](#36-how-do-you-configure-message-converters-in-spring-mvc) |
| 37  | [What is the role of LocaleResolver in Spring MVC?](#37-what-is-the-role-of-localeresolver-in-spring-mvc) |
| 38  | [How do you enable CORS in Spring MVC?](#38-how-do-you-enable-cors-in-spring-mvc) |
| 39  | [What is the use of @RequestHeader annotation?](#39-what-is-the-use-of-requestheader-annotation) |
| 40  | [How do you implement RESTful web services using Spring MVC?](#40-how-do-you-implement-restful-web-services-using-spring-mvc) |
| 41  | [How do you integrate Spring MVC with Thymeleaf?](#41-how-do-you-integrate-spring-mvc-with-thymeleaf) |
| 42  | [What is the use of @ResponseStatus annotation?](#42-what-is-the-use-of-responsestatus-annotation) |
| 43  | [How do you configure a custom view resolver in Spring MVC?](#43-how-do-you-configure-a-custom-view-resolver-in-spring-mvc) |
| 44  | [What is the role of MultipartResolver in Spring MVC?](#44-what-is-the-role-of-multipartresolver-in-spring-mvc) |
| 45  | [How do you handle AJAX requests in Spring MVC?](#45-how-do-you-handle-ajax-requests-in-spring-mvc) |
| 46  | [What is the difference between @RequestMapping and @GetMapping?](#46-what-is-the-difference-between-requestmapping-and-getmapping) |
| 47  | [How do you configure a custom interceptor in Spring MVC?](#47-how-do-you-configure-a-custom-interceptor-in-spring-mvc) |
| 48  | [What is the use of @MatrixVariable annotation?](#48-what-is-the-use-of-matrixvariable-annotation) |
| 49  | [How do you configure a custom validator in Spring MVC?](#49-how-do-you-configure-a-custom-validator-in-spring-mvc) |
| 50  | [What is the role of FlashMap in Spring MVC?](#50-what-is-the-role-of-flashmap-in-spring-mvc) |

### Level : Spring MVC Hard
| No. | Questions |
| --- | --------- |
| 51  | [How do you implement asynchronous request processing in Spring MVC?](#51-how-do-you-implement-asynchronous-request-processing-in-spring-mvc) |
| 52  | [Explain the process of configuring Spring MVC with Java-based configuration.](#52-explain-the-process-of-configuring-spring-mvc-with-java-based-configuration) |
| 53  | [How do you configure a custom message converter in Spring MVC?](#53-how-do-you-configure-a-custom-message-converter-in-spring-mvc) |
| 54  | [What is the use of @ControllerAdvice annotation?](#54-what-is-the-use-of-controlleradvice-annotation) |
| 55  | [How do you handle WebSocket communication in a Spring MVC application?](#55-how-do-you-handle-websocket-communication-in-a-spring-mvc-application) |
| 56  | [How do you configure a custom locale resolver in Spring MVC?](#56-how-do-you-configure-a-custom-locale-resolver-in-spring-mvc) |
| 57  | [Explain the role of WebApplicationInitializer in Spring MVC.](#57-explain-the-role-of-webapplicationinitializer-in-spring-mvc) |
| 58  | [How do you implement file download functionality in Spring MVC?](#58-how-do-you-implement-file-download-functionality-in-spring-mvc) |
| 59  | [How do you configure a custom exception handler in Spring MVC?](#59-how-do-you-configure-a-custom-exception-handler-in-spring-mvc) |
| 60  | [What is the use of @RestControllerAdvice annotation?](#60-what-is-the-use-of-restcontrolleradvice-annotation) |
| 61  | [How do you integrate Spring MVC with Hibernate?](#61-how-do-you-integrate-spring-mvc-with-hibernate) |
| 62  | [Explain the process of handling multipart requests in Spring MVC.](#62-explain-the-process-of-handling-multipart-requests-in-spring-mvc) |
| 63  | [How do you configure a custom argument resolver in Spring MVC?](#63-how-do-you-configure-a-custom-argument-resolver-in-spring-mvc) |
| 64  | [What is the role of ContentNegotiationManager in Spring MVC?](#64-what-is-the-role-of-contentnegotiationmanager-in-spring-mvc) |
| 65  | [How do you implement HATEOAS in a Spring MVC application?](#65-how-do-you-implement-hateoas-in-a-spring-mvc-application) |
| 66  | [How do you configure a custom handler method return value handler in Spring MVC?](#66-how-do-you-configure-a-custom-handler-method-return-value-handler-in-spring-mvc) |
| 67  | [Explain the process of configuring Spring MVC with XML-based configuration.](#67-explain-the-process-of-configuring-spring-mvc-with-xml-based-configuration) |
| 68  | [How do you handle JSONP requests in Spring MVC?](#68-how-do-you-handle-jsonp-requests-in-spring-mvc) |
| 69  | [How do you configure a custom view in Spring MVC?](#69-how-do-you-configure-a-custom-view-in-spring-mvc) |
| 70  | [What is the role of HandlerAdapter in Spring MVC?](#70-what-is-the-role-of-handleradapter-in-spring-mvc) |
| 71  | [How do you configure a custom model attribute in Spring MVC?](#71-how-do-you-configure-a-custom-model-attribute-in-spring-mvc) |
| 72  | [How do you implement server-sent events (SSE) in a Spring MVC application?](#72-how-do-you-implement-server-sent-events-sse-in-a-spring-mvc-application) |
| 73  | [How do you configure a custom form handler in Spring MVC?](#73-how-do-you-configure-a-custom-form-handler-in-spring-mvc) |
| 74  | [What is the use of @JsonView annotation in Spring MVC?](#74-what-is-the-use-of-jsonview-annotation-in-spring-mvc) |
| 75  | [How do you implement OAuth2 authentication in a Spring MVC application?](#75-how-do-you-implement-oauth2-authentication-in-a-spring-mvc-application) |

## Spring Data JPA
### Table of Contents
### Level : Spring Data JPA Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is Spring Data JPA?](#1-what-is-spring-data-jpa) |
| 2   | [What is the purpose of the `@Entity` annotation in JPA?](#2-what-is-the-purpose-of-the-entity-annotation-in-jpa) |
| 3   | [What is an EntityManager in JPA?](#3-what-is-an-entitymanager-in-jpa) |
| 4   | [What is the role of the `@Id` annotation in JPA?](#4-what-is-the-role-of-the-id-annotation-in-jpa) |
| 5   | [How do you define a primary key in a JPA entity?](#5-how-do-you-define-a-primary-key-in-a-jpa-entity) |
| 6   | [What is the difference between `findById` and `getOne` methods in JPA?](#6-what-is-the-difference-between-findbyid-and-getone-methods-in-jpa) |
| 7   | [What is the purpose of the `@Table` annotation in JPA?](#7-what-is-the-purpose-of-the-table-annotation-in-jpa) |
| 8   | [Explain the difference between `@Column` and `@JoinColumn`.](#8-explain-the-difference-between-column-and-joincolumn) |
| 9   | [What is the role of the `@GeneratedValue` annotation in JPA?](#9-what-is-the-role-of-the-generatedvalue-annotation-in-jpa) |
| 10  | [What is the default fetch type for `@OneToMany` and `@ManyToOne` relationships in JPA?](#10-what-is-the-default-fetch-type-for-onetomany-and-manytoone-relationships-in-jpa) |
| 11  | [How do you define a one-to-many relationship in JPA?](#11-how-do-you-define-a-one-to-many-relationship-in-jpa) |
| 12  | [What is a repository in Spring Data JPA?](#12-what-is-a-repository-in-spring-data-jpa) |
| 13  | [What is the purpose of the `@Repository` annotation in Spring Data JPA?](#13-what-is-the-purpose-of-the-repository-annotation-in-spring-data-jpa) |
| 14  | [How do you create a custom query in Spring Data JPA?](#14-how-do-you-create-a-custom-query-in-spring-data-jpa) |
| 15  | [What is the purpose of the `@Query` annotation in Spring Data JPA?](#15-what-is-the-purpose-of-the-query-annotation-in-spring-data-jpa) |
| 16  | [What is a JPQL?](#16-what-is-a-jpql) |
| 17  | [What is the difference between JPQL and SQL?](#17-what-is-the-difference-between-jpql-and-sql) |
| 18  | [What is the purpose of the `@Modifying` annotation in Spring Data JPA?](#18-what-is-the-purpose-of-the-modifying-annotation-in-spring-data-jpa) |
| 19  | [How do you handle transactions in Spring Data JPA?](#19-how-do-you-handle-transactions-in-spring-data-jpa) |
| 20  | [What is the `@Transactional` annotation used for in Spring Data JPA?](#20-what-is-the-transactional-annotation-used-for-in-spring-data-jpa) |
| 21  | [How do you paginate results in Spring Data JPA?](#21-how-do-you-paginate-results-in-spring-data-jpa) |
| 22  | [What is the `Pageable` interface in Spring Data JPA?](#22-what-is-the-pageable-interface-in-spring-data-jpa) |
| 23  | [What is the `Page` interface in Spring Data JPA?](#23-what-is-the-page-interface-in-spring-data-jpa) |
| 24  | [How do you sort results in Spring Data JPA?](#24-how-do-you-sort-results-in-spring-data-jpa) |
| 25  | [What is a derived query method in Spring Data JPA?](#25-what-is-a-derived-query-method-in-spring-data-jpa) |
| 26  | [What is the purpose of the `@NamedQuery` annotation in JPA?](#26-what-is-the-purpose-of-the-namedquery-annotation-in-jpa) |
| 27  | [What is an entity lifecycle in JPA?](#27-what-is-an-entity-lifecycle-in-jpa) |
| 28  | [What are the different states of an entity in JPA?](#28-what-are-the-different-states-of-an-entity-in-jpa) |
| 29  | [What is the purpose of the `@PrePersist` annotation in JPA?](#29-what-is-the-purpose-of-the-prepersist-annotation-in-jpa) |
| 30  | [What is the purpose of the `@PostPersist` annotation in JPA?](#30-what-is-the-purpose-of-the-postpersist-annotation-in-jpa) |
| 31  | [What is the purpose of the `@PreUpdate` annotation in JPA?](#31-what-is-the-purpose-of-the-preupdate-annotation-in-jpa) |
| 32  | [What is the purpose of the `@PostUpdate` annotation in JPA?](#32-what-is-the-purpose-of-the-postupdate-annotation-in-jpa) |
| 33  | [What is the purpose of the `@PreRemove` annotation in JPA?](#33-what-is-the-purpose-of-the-preremove-annotation-in-jpa) |
| 34  | [What is the purpose of the `@PostRemove` annotation in JPA?](#34-what-is-the-purpose-of-the-postremove-annotation-in-jpa) |
| 35  | [What is the purpose of the `@PostLoad` annotation in JPA?](#35-what-is-the-purpose-of-the-postload-annotation-in-jpa) |

### Level : Spring Data JPA Hard
| No. | Questions |
| --- | --------- |
| 66  | [Explain the concept of entity graph in JPA and how it can be used to optimize performance.](#66-explain-the-concept-of-entity-graph-in-jpa-and-how-it-can-be-used-to-optimize-performance) |
| 67  | [How do you handle dynamic queries in Spring Data JPA?](#67-how-do-you-handle-dynamic-queries-in-spring-data-jpa) |
| 68  | [What is the role of the `Criteria API` in JPA?](#68-what-is-the-role-of-the-criteria-api-in-jpa) |
| 69  | [How do you use the `Criteria API` to create dynamic queries in JPA?](#69-how-do-you-use-the-criteria-api-to-create-dynamic-queries-in-jpa) |
| 70  | [What is the purpose of the `Specification` interface in Spring Data JPA?](#70-what-is-the-purpose-of-the-specification-interface-in-spring-data-jpa) |
| 71  | [How do you use the `Specification` interface to create dynamic queries in JPA?](#71-how-do-you-use-the-specification-interface-to-create-dynamic-queries-in-jpa) |
| 72  | [What is the purpose of the `@Cacheable` annotation in JPA?](#72-what-is-the-purpose-of-the-cacheable-annotation-in-jpa) |
| 73  | [How do you configure second-level cache in JPA?](#73-how-do-you-configure-second-level-cache-in-jpa) |
| 74  | [What is the difference between first-level and second-level cache in JPA?](#74-what-is-the-difference-between-first-level-and-second-level-cache-in-jpa) |
| 75  | [Explain the concept of dirty checking in JPA and how it works.](#75-explain-the-concept-of-dirty-checking-in-jpa-and-how-it-works) |
| 76  | [Explain the concept of cascade types in JPA and how they affect entity relationships.](#76-explain-the-concept-of-cascade-types-in-jpa-and-how-they-affect-entity-relationships) |
| 77  | [What are the different cascade types available in JPA and when would you use each?](#77-what-are-the-different-cascade-types-available-in-jpa-and-when-would-you-use-each) |
| 78  | [How do you handle orphan removal in JPA and what is the purpose of the `@OneToMany(orphanRemoval = true)` annotation?](#78-how-do-you-handle-orphan-removal-in-jpa-and-what-is-the-purpose-of-the-onetomanyorphanremoval--true-annotation) |
| 79  | [What are the different types of entity graphs (attribute node, subgraph) in JPA and how are they used?](#79-what-are-the-different-types-of-entity-graphs-attribute-node-subgraph-in-jpa-and-how-are-they-used) |
| 80  | [How do you optimize performance using Fetch Joins in JPQL?](#80-how-do-you-optimize-performance-using-fetch-joins-in-jpql) |
| 81  | [What is the N+1 select problem in JPA and how can it be mitigated?](#81-what-is-the-n1-select-problem-in-jpa-and-how-can-it-be-mitigated) |
| 82  | [Explain the purpose of the `@EntityListeners` annotation and how it is used in auditing.](#82-explain-the-purpose-of-the-entitylisteners-annotation-and-how-it-is-used-in-auditing) |
| 83  | [How do you handle multi-tenancy in JPA and what are the different strategies available?](#83-how-do-you-handle-multi-tenancy-in-jpa-and-what-are-the-different-strategies-available) |
| 84  | [How do you configure and use the `@SequenceGenerator` and `@TableGenerator` annotations in JPA?](#84-how-do-you-configure-and-use-the-sequencegenerator-and-tablegenerator-annotations-in-jpa) |
| 85  | [What is the purpose of the `@Converter` annotation in JPA and how do you use it to create custom converters?](#85-what-is-the-purpose-of-the-converter-annotation-in-jpa-and-how-do-you-use-it-to-create-custom-converters) |
| 86  | [How do you handle database migrations in a Spring Data JPA application?](#86-how-do-you-handle-database-migrations-in-a-spring-data-jpa-application) |
| 87  | [What are the key considerations when implementing a custom repository in Spring Data JPA?](#87-what-are-the-key-considerations-when-implementing-a-custom-repository-in-spring-data-jpa) |
| 88  | [How do you manage database connection pooling in a Spring Data JPA application?](#88-how-do-you-manage-database-connection-pooling-in-a-spring-data-jpa-application) |
| 89  | [What is the role of the `@SecondaryTable` annotation in JPA and how do you use it to map an entity to multiple tables?](#89-what-is-the-role-of-the-secondarytable-annotation-in-jpa-and-how-do-you-use-it-to-map-an-entity-to-multiple-tables) |
| 90  | [Explain the concept of `Entity Detachment` in JPA and how it affects the persistence context.](#90-explain-the-concept-of-entity-detachment-in-jpa-and-how-it-affects-the-persistence-context) |
| 91  | [How do you implement soft deletes in a Spring Data JPA application?](#91-how-do-you-implement-soft-deletes-in-a-spring-data-jpa-application) |
| 92  | [What are the pros and cons of using `EntityManager` directly versus using Spring Data JPA repositories?](#92-what-are-the-pros-and-cons-of-using-entitymanager-directly-versus-using-spring-data-jpa-repositories) |
| 93  | [How do you handle hierarchical data structures (e.g., trees, graphs) in JPA?](#93-how-do-you-handle-hierarchical-data-structures-eg-trees-graphs-in-jpa) |
| 94  | [Explain the concept of database sharding and how it can be implemented in a Spring Data JPA application.](#94-explain-the-concept-of-database-sharding-and-how-it-can-be-implemented-in-a-spring-data-jpa-application) |
| 95  | [What are the best practices for managing entity relationships and avoiding circular dependencies in JPA?](#95-what-are-the-best-practices-for-managing-entity-relationships-and-avoiding-circular-dependencies-in-jpa) |
| 96  | [How do you handle large data sets and pagination efficiently in a Spring Data JPA application?](#96-how-do-you-handle-large-data-sets-and-pagination-efficiently-in-a-spring-data-jpa-application) |
| 97  | [Explain the different types of joins (inner, outer, cross) in JPQL and provide examples of when to use each.](#97-explain-the-different-types-of-joins-inner-outer-cross-in-jpql-and-provide-examples-of-when-to-use-each) |
| 98  | [How do you handle custom exception handling and error codes in a Spring Data JPA application?](#98-how-do-you-handle-custom-exception-handling-and-error-codes-in-a-spring-data-jpa-application) |
| 99  | [What are the key differences between Hibernate and other JPA implementations like EclipseLink?](#99-what-are-the-key-differences-between-hibernate-and-other-jpa-implementations-like-eclipselink) |
| 100 | [How do you integrate Spring Data JPA with other Spring projects like Spring Batch or Spring Integration?](#100-how-do-you-integrate-spring-data-jpa-with-other-spring-projects-like-spring-batch-or-spring-integration) |

### Level : Spring Data JPA Medium
| No. | Questions |
| --- | --------- |
| 36  | [Explain the different types of primary key generation strategies in JPA.](#36-explain-the-different-types-of-primary-key-generation-strategies-in-jpa) |
| 37  | [What is the difference between `@OneToMany` and `@ManyToMany` relationships in JPA?](#37-what-is-the-difference-between-onetomany-and-manytomany-relationships-in-jpa) |
| 38  | [How do you handle bi-directional relationships in JPA?](#38-how-do-you-handle-bi-directional-relationships-in-jpa) |
| 39  | [What is the `@MappedBy` attribute used for in JPA?](#39-what-is-the-mappedby-attribute-used-for-in-jpa) |
| 40  | [What is the purpose of the `@ElementCollection` annotation in JPA?](#40-what-is-the-purpose-of-the-elementcollection-annotation-in-jpa) |
| 41  | [How do you handle composite keys in JPA?](#41-how-do-you-handle-composite-keys-in-jpa) |
| 42  | [What is the `@Embeddable` annotation used for in JPA?](#42-what-is-the-embeddable-annotation-used-for-in-jpa) |
| 43  | [What is the purpose of the `@EmbeddedId` annotation in JPA?](#43-what-is-the-purpose-of-the-embeddedid-annotation-in-jpa) |
| 44  | [What is the role of the `@Inheritance` annotation in JPA?](#44-what-is-the-role-of-the-inheritance-annotation-in-jpa) |
| 45  | [Explain the different inheritance strategies in JPA.](#45-explain-the-different-inheritance-strategies-in-jpa) |
| 46  | [What is the purpose of the `@DiscriminatorColumn` annotation in JPA?](#46-what-is-the-purpose-of-the-discriminatorcolumn-annotation-in-jpa) |
| 47  | [What is the purpose of the `@DiscriminatorValue` annotation in JPA?](#47-what-is-the-purpose-of-the-discriminatorvalue-annotation-in-jpa) |
| 48  | [What is the purpose of the `@SecondaryTable` annotation in JPA?](#48-what-is-the-purpose-of-the-secondarytable-annotation-in-jpa) |
| 49  | [How do you define a native query in Spring Data JPA?](#49-how-do-you-define-a-native-query-in-spring-data-jpa) |
| 50  | [What is the purpose of the `@NamedNativeQuery` annotation in JPA?](#50-what-is-the-purpose-of-the-namednativequery-annotation-in-jpa) |
| 51  | [How do you handle optimistic locking in JPA?](#51-how-do-you-handle-optimistic-locking-in-jpa) |
| 52  | [What is the purpose of the `@Version` annotation in JPA?](#52-what-is-the-purpose-of-the-version-annotation-in-jpa) |
| 53  | [How do you handle pessimistic locking in JPA?](#53-how-do-you-handle-pessimistic-locking-in-jpa) |
| 54  | [What is the `EntityGraph` in JPA and how is it used?](#54-what-is-the-entitygraph-in-jpa-and-how-is-it-used) |
| 55  | [What are the different types of fetching strategies in JPA?](#55-what-are-the-different-types-of-fetching-strategies-in-jpa) |
| 56  | [What is the difference between eager and lazy loading in JPA?](#56-what-is-the-difference-between-eager-and-lazy-loading-in-jpa) |
| 57  | [How do you handle batch processing in Spring Data JPA?](#57-how-do-you-handle-batch-processing-in-spring-data-jpa) |
| 58  | [What is the purpose of the `@BatchSize` annotation in JPA?](#58-what-is-the-purpose-of-the-batchsize-annotation-in-jpa) |
| 59  | [How do you handle native SQL queries in Spring Data JPA?](#59-how-do-you-handle-native-sql-queries-in-spring-data-jpa) |
| 60  | [What is the purpose of the `@SqlResultSetMapping` annotation in JPA?](#60-what-is-the-purpose-of-the-sqlresultsetmapping-annotation-in-jpa) |
| 61  | [How do you handle auditing in Spring Data JPA?](#61-how-do-you-handle-auditing-in-spring-data-jpa) |
| 62  | [What is the purpose of the `@CreatedDate` annotation in JPA?](#62-what-is-the-purpose-of-the-createddate-annotation-in-jpa) |
| 63  | [What is the purpose of the `@LastModifiedDate` annotation in JPA?](#63-what-is-the-purpose-of-the-lastmodifieddate-annotation-in-jpa) |
| 64  | [What is the purpose of the `@CreatedBy` annotation in JPA?](#64-what-is-the-purpose-of-the-createdby-annotation-in-jpa) |
| 65  | [What is the purpose of the `@LastModifiedBy` annotation in JPA?](#65-what-is-the-purpose-of-the-lastmodifiedby-annotation-in-jpa) |

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

### 61. What is the use of the @Async annotation?

The `@Async` annotation is used to indicate that a method should be executed asynchronously. It can be applied to methods in classes annotated with `@Service`, `@Component`, or other stereotypes.

**Example:**

```java
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

### 62. How do you implement caching in Spring?

Caching in Spring can be implemented using the `@EnableCaching` annotation and cache annotations such as `@Cacheable`, `@CachePut`, and `@CacheEvict`.

**Example:**

```java
@Configuration
@EnableCaching
public class AppConfig {
    @Bean
    public CacheManager cacheManager() {
        return new ConcurrentMapCacheManager("myCache");
    }
}

@Service
public class MyService {
    @Cacheable("myCache")
    public String cacheableMethod() {
        return "cached result";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 63. What is the use of the @Cacheable annotation?

The `@Cacheable` annotation is used to indicate that the result of a method should be cached. The next time the method is called with the same parameters, the cached result is returned.

**Example:**

```java
@Service
public class MyService {
    @Cacheable("myCache")
    public String cacheableMethod() {
        return "cached result";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 64. How do you configure a cache manager in Spring?

A cache manager can be configured using XML configuration or Java configuration.

**Example (Java Configuration):**

```java
@Configuration
@EnableCaching
public class AppConfig {
    @Bean
    public CacheManager cacheManager() {
        return new ConcurrentMapCacheManager("myCache");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 65. What is the Spring Event model?

The Spring Event model is a mechanism for decoupling components using events and listeners. It allows beans to publish and listen to events within the application context.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 66. How do you publish and listen to events in Spring?

Events can be published using the `ApplicationEventPublisher` and listened to using `@EventListener` or by implementing `ApplicationListener`.

**Example:**

```java
// Event Class
public class MyEvent extends ApplicationEvent {
    public MyEvent(Object source) {
        super(source);
    }
}

// Publisher
@Component
public class MyEventPublisher {
    @Autowired
    private ApplicationEventPublisher applicationEventPublisher;

    public void publishEvent() {
        MyEvent event = new MyEvent(this);
        applicationEventPublisher.publishEvent(event);
    }
}

// Listener
@Component
public class MyEventListener {
    @EventListener
    public void handleMyEvent(MyEvent event) {
        System.out.println("Event received: " + event);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 67. What is the use of the @EventListener annotation?

The `@EventListener` annotation is used to mark a method as an event listener. It listens for specific events and executes the method when the event is published.

**Example:**

```java
@Component
public class MyEventListener {
    @EventListener
    public void handleMyEvent(MyEvent event) {
        System.out.println("Event received: " + event);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 68. What is Spring's Task Scheduler?

Spring's Task Scheduler is an abstraction for scheduling tasks. It provides a way to execute tasks at specified intervals or at specific times.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 69. How do you schedule tasks in Spring?

Tasks can be scheduled in Spring using the `@EnableScheduling` annotation and the `@Scheduled` annotation on methods.

**Example:**

```java
@Configuration
@EnableScheduling
public class AppConfig {
    // configuration
}

@Component
public class MyTask {
    @Scheduled(fixedRate = 5000)
    public void scheduledTask() {
        System.out.println("Task executed");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 70. What is the use of the @Scheduled annotation?

The `@Scheduled` annotation is used to schedule tasks. It can be configured with parameters such as `fixedRate`, `fixedDelay`, and `cron` to specify the execution interval or timing.

**Example:**

```java
@Component
public class MyTask {
    @Scheduled(fixedRate = 5000)
    public void scheduledTask() {
        System.out.println("Task executed");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 71. What is the Spring Web MVC framework?

The Spring Web MVC framework is a module of the Spring Framework for building web applications. It follows the Model-View-Controller (MVC) pattern and provides support for handling requests, binding data, and rendering views.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 72. How do you configure a DispatcherServlet in Spring?

The `DispatcherServlet` is configured in the `web.xml` file or using Java configuration.

**Example (web.xml):**

```xml
<servlet>
    <servlet-name>dispatcher</servlet-name>
    <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
    <load-on-startup>1</load-on-startup>
</servlet>
<servlet-mapping>
    <servlet-name>dispatcher</servlet-name>
    <url-pattern>/</url-pattern>
</servlet-mapping>
```

**Example (Java Configuration):**

```java
import org.springframework.web.servlet.support.AbstractAnnotationConfigDispatcherServletInitializer;

public class WebAppInitializer extends AbstractAnnotationConfigDispatcherServletInitializer {
    @Override
    protected Class<?>[] getRootConfigClasses() {
        return new Class<?>[] { AppConfig.class };
    }

    @Override
    protected Class<?>[] getServletConfigClasses() {
        return new Class<?>[] { WebConfig.class };
    }

    @Override
    protected String[] getServletMappings() {
        return new String[] { "/" };
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 73. What is the role of the @Controller annotation?

The `@Controller` annotation is used to mark a class as a Spring MVC controller. It indicates that the class handles web requests and returns views.

**Example:**

```java
@Controller
public class MyController {
    @RequestMapping("/hello")
    public String hello() {
        return "hello";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 74. How do you handle form submissions in Spring MVC?

Form submissions in Spring MVC are handled using `@RequestMapping` or `@PostMapping` annotations on controller methods. The form data is bound to a model object.

**Example:**

```java
@Controller
public class MyController {
    @GetMapping("/form")
    public String showForm(Model model) {
        model.addAttribute("user", new User());
        return "form";
    }

    @PostMapping("/form")
    public String submitForm(@ModelAttribute User user) {
        // process form data
        return "result";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 75. What is the use of the @RequestMapping annotation?

The `@RequestMapping` annotation is used to map web requests to specific handler methods in a controller. It can be applied at the class level and method level to specify the URL patterns and HTTP methods.

**Example:**

```java
@Controller
@RequestMapping("/users")
public class UserController {
    @RequestMapping(value = "/{id}", method = RequestMethod.GET)
    public String getUser(@PathVariable("id") Long id, Model model) {
        // get user by id
        return "user";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 76. How do you handle exceptions in Spring MVC?

In Spring MVC, exceptions can be handled in various ways:

1. **Using `@ExceptionHandler` Annotation:**
   Define a method in your controller class to handle exceptions.

   ```java
   @Controller
   public class MyController {

       @ExceptionHandler(Exception.class)
       public ModelAndView handleException(Exception ex) {
           ModelAndView model = new ModelAndView("error");
           model.addObject("exception", ex);
           return model;
       }
   }
   ```

2. **Using `@ControllerAdvice` Annotation:**
   This annotation is used to define global exception handling across multiple controllers.

   ```java
   @ControllerAdvice
   public class GlobalExceptionHandler {

       @ExceptionHandler(Exception.class)
       public ModelAndView handleGlobalException(Exception ex) {
           ModelAndView model = new ModelAndView("error");
           model.addObject("exception", ex);
           return model;
       }
   }
   ```

3. **Using `HandlerExceptionResolver` Interface:**
   Implement this interface to create a centralized exception handling mechanism.

   ```java
   public class MyExceptionHandler implements HandlerExceptionResolver {

       @Override
       public ModelAndView resolveException(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex) {
           ModelAndView model = new ModelAndView("error");
           model.addObject("exception", ex);
           return model;
       }
   }
   ```

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 77. What is the use of the `@ExceptionHandler` annotation?

The `@ExceptionHandler` annotation is used to handle specific exceptions thrown by controller methods. It allows you to define a method that will be invoked when a specific exception is thrown.

Example:

```java
@Controller
public class MyController {

    @ExceptionHandler(MyException.class)
    public ModelAndView handleMyException(MyException ex) {
        ModelAndView model = new ModelAndView("error");
        model.addObject("exception", ex);
        return model;
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 78. How do you configure view resolvers in Spring MVC?

View resolvers in Spring MVC are configured in the `dispatcher-servlet.xml` file or using Java configuration.

**XML Configuration:**

```xml
<bean class="org.springframework.web.servlet.view.InternalResourceViewResolver">
    <property name="prefix" value="/WEB-INF/views/"/>
    <property name="suffix" value=".jsp"/>
</bean>
```

**Java Configuration:**

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Override
    public void configureViewResolvers(ViewResolverRegistry registry) {
        registry.jsp("/WEB-INF/views/", ".jsp");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 79. What is the use of the `@ModelAttribute` annotation?

The `@ModelAttribute` annotation is used to bind a method parameter or method return value to a named model attribute, and then expose it to a web view.

**Example:**

```java
@Controller
public class MyController {

    @ModelAttribute("myModel")
    public MyModel createModel() {
        return new MyModel();
    }

    @RequestMapping("/example")
    public String example(@ModelAttribute("myModel") MyModel model) {
        // Use the model attribute
        return "viewName";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 80. How do you perform validation in Spring MVC?

Validation in Spring MVC is typically performed using the `@Valid` annotation and a `BindingResult` object.

**Example:**

```java
@Controller
public class MyController {

    @RequestMapping(value = "/submit", method = RequestMethod.POST)
    public String submitForm(@Valid @ModelAttribute("formModel") FormModel formModel, BindingResult result) {
        if (result.hasErrors()) {
            return "formView";
        }
        return "successView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 81. What is the use of the `@Valid` annotation?

The `@Valid` annotation is used to indicate that a bean should be validated before performing an action, such as processing a form submission.

**Example:**

```java
@Controller
public class MyController {

    @RequestMapping(value = "/submit", method = RequestMethod.POST)
    public String submitForm(@Valid @ModelAttribute("formModel") FormModel formModel, BindingResult result) {
        if (result.hasErrors()) {
            return "formView";
        }
        return "successView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 82. How do you handle file uploads in Spring MVC?

To handle file uploads, you need to configure a `MultipartResolver` bean and use the `MultipartFile` class in your controller.

**Configuration:**

```xml
<bean id="multipartResolver" class="org.springframework.web.multipart.commons.CommonsMultipartResolver"/>
```

**Controller:**

```java
@Controller
public class FileUploadController {

    @RequestMapping(value = "/upload", method = RequestMethod.POST)
    public String handleFileUpload(@RequestParam("file") MultipartFile file) {
        if (!file.isEmpty()) {
            // Handle file upload
        }
        return "uploadView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 83. What is the use of the `MultipartResolver` in Spring MVC?

The `MultipartResolver` is used to handle file uploads in Spring MVC applications. It parses multipart requests and makes the uploaded files accessible via the `MultipartFile` class.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 84. Explain the concept of `RestTemplate` in Spring.

`RestTemplate` is a synchronous client to perform HTTP requests, exposing a simple, template method API over underlying HTTP client libraries.

**Example:**

```java
RestTemplate restTemplate = new RestTemplate();
String result = restTemplate.getForObject("https://api.example.com/resource", String.class);
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 85. How do you configure `RestTemplate` in Spring?

You can configure `RestTemplate` as a bean in your Spring configuration.

**Java Configuration:**

```java
@Configuration
public class AppConfig {

    @Bean
    public RestTemplate restTemplate() {
        return new RestTemplate();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 86. How do you make HTTP requests using `RestTemplate`?

`RestTemplate` provides several methods to make HTTP requests.

**Example:**

```java
RestTemplate restTemplate = new RestTemplate();

// GET request
String response = restTemplate.getForObject("https://api.example.com/resource", String.class);

// POST request
HttpHeaders headers = new HttpHeaders();
headers.setContentType(MediaType.APPLICATION_JSON);
HttpEntity<String> request = new HttpEntity<>("{\"key\":\"value\"}", headers);
String response = restTemplate.postForObject("https://api.example.com/resource", request, String.class);
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 87. What is the Spring WebFlux framework?

Spring WebFlux is a reactive web framework designed for asynchronous, non-blocking applications. It uses the Project Reactor library for reactive programming.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 88. How do you configure a WebFlux application in Spring?

**Java Configuration:**

```java
@Configuration
@EnableWebFlux
public class WebFluxConfig implements WebFluxConfigurer {
    // Configuration goes here
}

@SpringBootApplication
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 89. What is the role of the `@RestController` annotation?

The `@RestController` annotation is a specialized version of `@Controller` that combines `@Controller` and `@ResponseBody`. It is used to create RESTful web services.

**Example:**

```java
@RestController
public class MyRestController {

    @GetMapping("/resource")
    public String getResource() {
        return "Hello, World!";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 90. How do you handle reactive streams in Spring WebFlux?

Reactive streams in Spring WebFlux are handled using `Mono` and `Flux` types from Project Reactor.

**Example:**

```java
@RestController
public class ReactiveController {

    @GetMapping("/mono")
    public Mono<String> getMono() {
        return Mono.just("Hello, Mono!");
    }

    @GetMapping("/flux")
    public Flux<String> getFlux() {
        return Flux.just("Hello", "Flux", "!");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 91. What is the Spring Boot framework?

Spring Boot is a framework that simplifies the development of Spring applications by providing pre-configured templates and reducing boilerplate code. It also includes embedded servers, making it easy to run standalone applications.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 92. How do you configure a Spring Boot application?

Spring Boot applications are typically configured using `application.properties` or `application.yml` files.

**Example:**

```properties
server.port=8080
spring.datasource.url=jdbc:mysql://localhost:3306/mydb
spring.datasource.username=root
spring.datasource.password=root
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 93. What are the benefits of using Spring Boot?

- **Simplified Configuration:** Reduces boilerplate code and configuration.
- **Embedded Servers:** Makes it easy to run standalone applications.
- **Production-ready Features:** Includes features like health checks and metrics.
- **Auto-Configuration:** Automatically configures Spring applications based on dependencies.
- **Microservices Support:** Ideal for building microservices architecture.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 94. How do you create a RESTful web service using Spring Boot?

**Example:**

```java
@SpringBootApplication
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}

@RestController
@RequestMapping("/api")
public class MyRestController {

    @GetMapping("/resource")
    public String getResource() {
        return "Hello, World!";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 95. What is the role of the `application.properties` file in Spring Boot?

The `application.properties` file is used to configure various properties of a Spring Boot application, such as server port, database connection details, and more.

#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 96. How do you configure logging in Spring Boot?

Logging in Spring Boot is configured using the `application.properties` file.

**Example:**

```properties
logging.level.org.springframework=DEBUG
logging.file.name=app.log
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 97. How do you handle exceptions in a Spring Boot application?

In Spring Boot, exceptions can be handled using `@ControllerAdvice`, `@ExceptionHandler`, and `ResponseEntityExceptionHandler`.

**Example:**

```java
@ControllerAdvice
public class GlobalExceptionHandler extends ResponseEntityExceptionHandler {

    @ExceptionHandler(Exception.class)
    public ResponseEntity<Object> handleException(Exception ex) {
        return new ResponseEntity<>(ex.getMessage(), HttpStatus.INTERNAL_SERVER_ERROR);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 98. What is the use of the `@SpringBootApplication` annotation?

The `@SpringBootApplication` annotation is a combination of `@Configuration`, `@EnableAutoConfiguration`, and `@ComponentScan`, providing a convenient way to configure a Spring Boot application.

**Example:**

```java
@SpringBootApplication
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 99. How do you run a Spring Boot application?

A Spring Boot application can be run using the `main` method in the main application class or using the command line with `mvn spring-boot:run` or `gradle bootRun`.

**Example:**

```java
@SpringBootApplication
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 100. How do you test a Spring Boot application?

Spring Boot applications can be tested using Spring Boot Test, which provides utilities like `@SpringBootTest`, `@MockBean`, and `TestRestTemplate`.

**Example:**

```java
@SpringBootTest
public class MyControllerTest {

    @Autowired
    private TestRestTemplate restTemplate;

    @Test
    public void testGetResource() {
        ResponseEntity<String> response = restTemplate.getForEntity("/api/resource", String.class);
        assertEquals(HttpStatus.OK, response.getStatusCode());
        assertEquals("Hello, World!", response.getBody());
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

# Spring Core Hard Interview Questions and Answers
### 101. Explain the concept of Reactive Programming in Spring.

Reactive Programming is a programming paradigm oriented around data flows and the propagation of change. In Spring, Reactive Programming is implemented using the Project Reactor library, which provides support for creating reactive applications. Reactive Programming is built on the concept of non-blocking, event-driven programming with backpressure support.

Key concepts:
- **Publisher**: Emits a sequence of items.
- **Subscriber**: Consumes the sequence of items emitted by the Publisher.
- **Subscription**: Represents a one-to-one lifecycle of a Subscriber subscribing to a Publisher.
- **Backpressure**: A mechanism to control the flow of data between Publisher and Subscriber.

Example:
```java
import reactor.core.publisher.Flux;
import reactor.core.publisher.Mono;

public class ReactiveExample {
    public static void main(String[] args) {
        Flux<String> flux = Flux.just("Hello", "World");
        flux.subscribe(System.out::println);

        Mono<String> mono = Mono.just("Spring Reactive");
        mono.subscribe(System.out::println);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 102. How does Spring WebFlux handle backpressure?

Spring WebFlux handles backpressure using Reactive Streams. Reactive Streams provide a standard for asynchronous stream processing with non-blocking backpressure. WebFlux leverages Project Reactor to implement Reactive Streams.

Example:
```java
import reactor.core.publisher.Flux;

public class BackpressureExample {
    public static void main(String[] args) {
        Flux.range(1, 100)
            .onBackpressureBuffer(10)
            .subscribe(
                item -> System.out.println("Received: " + item),
                error -> System.err.println("Error: " + error),
                () -> System.out.println("Done")
            );
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 103. What is the difference between Spring MVC and Spring WebFlux?

| Feature        | Spring MVC                      | Spring WebFlux                        |
|----------------|---------------------------------|---------------------------------------|
| Programming    | Synchronous and blocking        | Asynchronous and non-blocking         |
| Reactive       | No                              | Yes                                   |
| Performance    | Suitable for traditional apps   | Suitable for high-concurrency apps    |
| Underlying Lib | Servlet API                     | Project Reactor                       |
| Controllers    | @Controller, @RestController    | @Controller, @RestController          |
| Execution      | Single-threaded per request     | Event-loop model                      |

#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 104. How do you configure security in a Spring application?

You can configure security in a Spring application using `Spring Security`. This involves adding dependencies, defining security configuration classes, and customizing authentication/authorization.

Example:
```xml
<!-- pom.xml -->
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-security</artifactId>
</dependency>
```

```java
import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;
import org.springframework.security.config.annotation.web.builders.HttpSecurity;
import org.springframework.security.config.annotation.web.configuration.WebSecurityConfigurerAdapter;
import org.springframework.security.crypto.bcrypt.BCryptPasswordEncoder;
import org.springframework.security.crypto.password.PasswordEncoder;

@Configuration
public class SecurityConfig extends WebSecurityConfigurerAdapter {

    @Override
    protected void configure(HttpSecurity http) throws Exception {
        http
            .authorizeRequests()
            .antMatchers("/public/**").permitAll()
            .anyRequest().authenticated()
            .and()
            .formLogin().and()
            .httpBasic();
    }

    @Bean
    public PasswordEncoder passwordEncoder() {
        return new BCryptPasswordEncoder();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 105. What is the role of the @EnableWebSecurity annotation?

`@EnableWebSecurity` is used to enable Spring Security’s web security support and provide the Spring MVC integration.

Example:
```java
import org.springframework.security.config.annotation.web.configuration.EnableWebSecurity;

@EnableWebSecurity
public class WebSecurityConfig {
    // Security configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 106. How do you implement OAuth2 authentication in Spring Security?

You can implement OAuth2 authentication using Spring Security’s `spring-security-oauth2` module.

Example:
```xml
<!-- pom.xml -->
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-oauth2-client</artifactId>
</dependency>
```

```yaml
# application.yml
spring:
  security:
    oauth2:
      client:
        registration:
          google:
            client-id: your-client-id
            client-secret: your-client-secret
            scope: profile, email
        provider:
          google:
            authorization-uri: https://accounts.google.com/o/oauth2/auth
            token-uri: https://accounts.google.com/o/oauth2/token
            user-info-uri: https://www.googleapis.com/oauth2/v3/userinfo
            user-name-attribute: sub
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 107. What is the use of the @PreAuthorize annotation?

`@PreAuthorize` is used to apply method-level security. It allows you to define access control expressions.

Example:
```java
import org.springframework.security.access.prepost.PreAuthorize;
import org.springframework.stereotype.Service;

@Service
public class MyService {
    
    @PreAuthorize("hasRole('ROLE_ADMIN')")
    public void secureMethod() {
        // method logic
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 108. How do you implement method-level security in Spring?

To implement method-level security, use `@EnableGlobalMethodSecurity` with `@PreAuthorize`, `@PostAuthorize`, `@Secured`, and `@RolesAllowed` annotations.

Example:
```java
import org.springframework.context.annotation.Configuration;
import org.springframework.security.config.annotation.method.configuration.EnableGlobalMethodSecurity;

@Configuration
@EnableGlobalMethodSecurity(prePostEnabled = true)
public class MethodSecurityConfig {
    // Configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 109. How do you configure a custom authentication provider in Spring Security?

You can configure a custom authentication provider by implementing `AuthenticationProvider` and overriding the `authenticate` and `supports` methods.

Example:
```java
import org.springframework.security.authentication.AuthenticationProvider;
import org.springframework.security.core.Authentication;
import org.springframework.security.core.AuthenticationException;
import org.springframework.security.core.userdetails.User;
import org.springframework.security.core.userdetails.UserDetails;
import org.springframework.security.core.userdetails.UsernameNotFoundException;
import org.springframework.security.crypto.password.PasswordEncoder;

public class CustomAuthenticationProvider implements AuthenticationProvider {

    private final PasswordEncoder passwordEncoder;

    public CustomAuthenticationProvider(PasswordEncoder passwordEncoder) {
        this.passwordEncoder = passwordEncoder;
    }

    @Override
    public Authentication authenticate(Authentication authentication) throws AuthenticationException {
        String username = authentication.getName();
        String password = authentication.getCredentials().toString();

        // Custom authentication logic
        UserDetails user = loadUserByUsername(username);
        if (user != null && passwordEncoder.matches(password, user.getPassword())) {
            return new UsernamePasswordAuthenticationToken(username, password, user.getAuthorities());
        } else {
            throw new UsernameNotFoundException("Invalid username or password");
        }
    }

    @Override
    public boolean supports(Class<?> authentication) {
        return UsernamePasswordAuthenticationToken.class.isAssignableFrom(authentication);
    }

    private UserDetails loadUserByUsername(String username) {
        // Load user from database or any other source
        return User.withUsername(username).password(passwordEncoder.encode("password")).roles("USER").build();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 110. What is the purpose of the SecurityContextHolder in Spring Security?

`SecurityContextHolder` holds the security context, including the authentication details of the currently authenticated user. It provides access to the `SecurityContext`.

Example:
```java
import org.springframework.security.core.Authentication;
import org.springframework.security.core.context.SecurityContextHolder;

public class SecurityContextExample {
    public void printAuthenticatedUser() {
        Authentication authentication = SecurityContextHolder.getContext().getAuthentication();
        if (authentication != null) {
            System.out.println("User: " + authentication.getName());
        }
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-medium)**
---

### 111. Explain the concept of CSRF protection in Spring Security.

CSRF (Cross-Site Request Forgery) protection prevents unauthorized commands being transmitted from a user that the web application trusts. Spring Security enables CSRF protection by default for web applications.

Example:
```java
import org.springframework.security.config.annotation.web.builders.HttpSecurity;
import org.springframework.security.config.annotation.web.configuration.WebSecurityConfigurerAdapter;

public class CsrfSecurityConfig extends WebSecurityConfigurerAdapter {
    @Override
    protected void configure(HttpSecurity http) throws Exception {
        http
            .csrf().csrfTokenRepository(CookieCsrfTokenRepository.withHttpOnlyFalse());
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 112. How do you configure session management in Spring Security?

You can configure session management using `HttpSecurity`'s session management section.

Example:
```java
import org.springframework.security.config.annotation.web.builders.HttpSecurity;
import org.springframework.security.config.annotation.web.configuration.WebSecurityConfigurerAdapter;

public class SessionManagementConfig extends WebSecurityConfigurerAdapter {
    @Override
    protected void configure(HttpSecurity http) throws Exception {
        http
            .sessionManagement()
            .sessionCreationPolicy(SessionCreationPolicy.IF_REQUIRED)
            .maximumSessions(1)
            .maxSessionsPreventsLogin(true);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 113. What is the use of the @EnableAspectJAutoProxy annotation?

`@EnableAspectJAutoProxy` enables support for handling components marked with AspectJ's `@Aspect` annotation, similar to functionality found in Spring's XML configuration.

Example:
```java
import org.springframework.context.annotation.Configuration;
import org.springframework.context.annotation.EnableAspectJAutoProxy;

@Configuration
@EnableAspectJAutoProxy
public class AppConfig {
    // Configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 114. How do you implement global exception handling in Spring?

You can implement global exception handling using `@ControllerAdvice` and `@ExceptionHandler` annotations.

Example:
```java
import org.springframework.http.HttpStatus;
import org.springframework.web.bind.annotation.ControllerAdvice;
import org.springframework.web.bind.annotation.ExceptionHandler;
import org.springframework.web.bind.annotation.ResponseStatus;

@ControllerAdvice
public class GlobalExceptionHandler {

    @ExceptionHandler(Exception.class)
    @ResponseStatus(HttpStatus.INTERNAL_SERVER_ERROR)
    public String handleException(Exception e) {
        return "error"; // Error view name
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 115. What is the use of the @ControllerAdvice annotation?

`@ControllerAdvice` is used to define global exception handlers, data binders, and model attributes that apply to multiple controllers.

Example:
```java
import org.springframework.web.bind.annotation.ControllerAdvice;
import org.springframework.web.bind.annotation.ModelAttribute;

@ControllerAdvice
public class GlobalControllerAdvice {

    @ModelAttribute("message")
    public String globalMessage() {
        return "Welcome to the application!";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 116. How do you configure internationalization in a Spring application?

You configure internationalization (i18n) by defining `MessageSource`, locale resolver, and locale interceptor.

Example:
```java
import org.springframework.context.MessageSource;
import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;
import org.springframework.context.support.ResourceBundleMessageSource;
import org.springframework.web.servlet.LocaleResolver;
import org.springframework.web.servlet.i18n.LocaleChangeInterceptor;
import org.springframework.web.servlet.i18n.SessionLocaleResolver;
import org.springframework.web.servlet.config.annotation.InterceptorRegistry;
import org.springframework.web.servlet.config.annotation.WebMvcConfigurer;

import java.util.Locale;

@Configuration
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public LocaleResolver localeResolver() {
        SessionLocaleResolver slr = new SessionLocaleResolver();
        slr.setDefaultLocale(Locale.US);
        return slr;
    }

    @Bean
    public LocaleChangeInterceptor localeChangeInterceptor() {
        LocaleChangeInterceptor lci = new LocaleChangeInterceptor();
        lci.setParamName("lang");
        return lci;
    }

    @Override
    public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(localeChangeInterceptor());
    }

    @Bean
    public MessageSource messageSource() {
        ResourceBundleMessageSource messageSource = new ResourceBundleMessageSource();
        messageSource.setBasename("messages");
        messageSource.setDefaultEncoding("UTF-8");
        return messageSource;
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 117. What is the use of the MessageSource interface in Spring?

`MessageSource` is used for resolving messages, with support for internationalization (i18n). It allows you to retrieve messages from properties files based on locale.

Example:
```java
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.context.MessageSource;
import org.springframework.stereotype.Service;

import java.util.Locale;

@Service
public class MessageService {

    @Autowired
    private MessageSource messageSource;

    public String getMessage(String code) {
        return messageSource.getMessage(code, null, Locale.US);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 118. How do you create a custom validator in Spring?

You create a custom validator by implementing the `Validator` interface and overriding the `validate` method.

Example:
```java
import org.springframework.stereotype.Component;
import org.springframework.validation.Errors;
import org.springframework.validation.Validator;

@Component
public class CustomValidator implements Validator {

    @Override
    public boolean supports(Class<?> clazz) {
        return MyForm.class.equals(clazz);
    }

    @Override
    public void validate(Object target, Errors errors) {
        MyForm form = (MyForm) target;
        if (form.getField() == null || form.getField().isEmpty()) {
            errors.rejectValue("field", "field.empty", "Field cannot be empty");
        }
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 119. What is the use of the @InitBinder annotation?

`@InitBinder` is used to customize the data binding for a specific controller. It allows you to register custom editors or formatters.

Example:
```java
import org.springframework.web.bind.WebDataBinder;
import org.springframework.web.bind.annotation.InitBinder;
import org.springframework.web.bind.annotation.Controller;

@Controller
public class MyController {

    @InitBinder
    public void initBinder(WebDataBinder binder) {
        binder.registerCustomEditor(Date.class, new CustomDateEditor(new SimpleDateFormat("yyyy-MM-dd"), false));
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 120. How do you configure a custom property editor in Spring?

You configure a custom property editor by extending `PropertyEditorSupport` and registering it with `WebDataBinder`.

Example:
```java
import java.beans.PropertyEditorSupport;

public class CustomDateEditor extends PropertyEditorSupport {

    private final SimpleDateFormat dateFormat;

    public CustomDateEditor(SimpleDateFormat dateFormat, boolean allowEmpty) {
        this.dateFormat = dateFormat;
    }

    @Override
    public void setAsText(String text) throws IllegalArgumentException {
        try {
            setValue(dateFormat.parse(text));
        } catch (ParseException e) {
            setValue(null);
        }
    }

    @Override
    public String getAsText() {
        return (getValue() != null ? dateFormat.format(getValue()) : "");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 121. Explain the concept of Spring Cloud.

Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems, such as configuration management, service discovery, circuit breakers, routing, etc.

#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 122. How do you configure a microservice using Spring Cloud?

To configure a microservice, you typically use Spring Boot and Spring Cloud dependencies. You will configure the application to use service discovery, load balancing, and other Spring Cloud features.

#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 123. What is the use of the @EnableEurekaClient annotation?

`@EnableEurekaClient` is used to register a service with a Eureka server for service discovery.

Example:
```java
import org.springframework.cloud.netflix.eureka.EnableEurekaClient;
import org.springframework.context.annotation.Configuration;

@Configuration
@EnableEurekaClient
public class EurekaClientConfig {
    // Configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 124. How do you configure load balancing in Spring Cloud?

Load balancing can be configured using `Spring Cloud LoadBalancer` or `Ribbon` (deprecated) by annotating a `RestTemplate` bean with `@LoadBalanced`.

Example:
```java
import org.springframework.cloud.client.loadbalancer.LoadBalanced;
import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;
import org.springframework.web.client.RestTemplate;

@Configuration
public class LoadBalancerConfig {

    @Bean
    @LoadBalanced
    public RestTemplate restTemplate() {
        return new RestTemplate();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 125. What is the use of the @EnableFeignClients annotation?

`@EnableFeignClients` is used to enable Feign clients, which allows you to create declarative REST clients.

Example:
```java
import org.springframework.cloud.openfeign.EnableFeignClients;
import org.springframework.context.annotation.Configuration;

@Configuration
@EnableFeignClients
public class FeignClientsConfig {
    // Configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 126. How do you implement circuit breaker pattern in Spring Cloud?

You can implement the circuit breaker pattern using `Resilience4j` or `Hystrix` (deprecated).

Example with Resilience4j:
```java
import io.github.resilience4j.circuitbreaker.annotation.CircuitBreaker;
import org.springframework.stereotype.Service;

@Service
public class MyService {

    @CircuitBreaker(name = "myService", fallbackMethod = "fallbackMethod")
    public String doSomething() {
        // service logic
        return "Success";
    }

    public String fallbackMethod(Throwable t) {
        return "Fallback response";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 127. What is the use of the @EnableCircuitBreaker annotation?

`@EnableCircuitBreaker` is used to enable circuit breaker functionality in your application.

Example:
```java
import org.springframework.cloud.client.circuitbreaker.EnableCircuitBreaker;
import org.springframework.context.annotation.Configuration;

@Configuration
@EnableCircuitBreaker
public class CircuitBreakerConfig {
    // Configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 128. How do you configure a distributed tracing system in Spring Cloud?

To configure distributed tracing, you can use `Spring Cloud Sleuth` and `Zipkin`.

Example:
```xml
<!-- pom.xml -->
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-sleuth</artifactId>
</dependency>
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-zipkin</artifactId>
</dependency>
```

```yaml
# application.yml
spring:
  zipkin:
    base-url: http://localhost:9411
  sleuth:
    sampler:
      probability: 1.0
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 129. What is the use of the @EnableHystrixDashboard annotation?

`@EnableHystrixDashboard` is used to enable the Hystrix Dashboard for monitoring circuit breakers.

Example:
```java
import org.springframework.cloud.netflix.hystrix.dashboard.EnableHystrixDashboard;
import org.springframework.context.annotation.Configuration;

@Configuration
@EnableHystrixDashboard
public class HystrixDashboardConfig {
    // Configuration
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 130. How do you configure a service gateway in Spring Cloud?

To configure a service gateway, you can use `Spring Cloud Gateway`.

Example:
```xml
<!-- pom.xml -->
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-gateway</artifactId>
</dependency>
```

```yaml
# application.yml
spring:
  cloud:
    gateway:
      routes:
        - id: service1
          uri: http://localhost:8081
          predicates:
            - Path=/service1/**
        - id: service2
          uri: http://localhost:8082
          predicates:
            - Path=/service2/**
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 131. What is the use of the @EnableZuulProxy annotation?

The `@EnableZuulProxy` annotation is used in a Spring Boot application to enable Zuul, which is a gateway service that provides dynamic routing, monitoring, resiliency, security, and more. This annotation sets up a Zuul server that can forward requests to other services, effectively acting as an API gateway.

### Example:
```java
@SpringBootApplication
@EnableZuulProxy
public class ApiGatewayApplication {
    public static void main(String[] args) {
        SpringApplication.run(ApiGatewayApplication.class, args);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 132. How do you implement API versioning in a Spring application?

API versioning can be implemented in Spring using different strategies such as URI versioning, request parameter versioning, and header versioning.

### Example: URI Versioning
```java
@RestController
@RequestMapping("/api/v1")
public class ApiControllerV1 {
    @GetMapping("/resource")
    public ResponseEntity<String> getResourceV1() {
        return ResponseEntity.ok("Resource V1");
    }
}

@RestController
@RequestMapping("/api/v2")
public class ApiControllerV2 {
    @GetMapping("/resource")
    public ResponseEntity<String> getResourceV2() {
        return ResponseEntity.ok("Resource V2");
    }
}
```

### Example: Request Parameter Versioning
```java
@RestController
public class ApiController {
    @GetMapping(value = "/resource", params = "version=1")
    public ResponseEntity<String> getResourceV1() {
        return ResponseEntity.ok("Resource V1");
    }

    @GetMapping(value = "/resource", params = "version=2")
    public ResponseEntity<String> getResourceV2() {
        return ResponseEntity.ok("Resource V2");
    }
}
```

### Example: Header Versioning
```java
@RestController
public class ApiController {
    @GetMapping(value = "/resource", headers = "X-API-Version=1")
    public ResponseEntity<String> getResourceV1() {
        return ResponseEntity.ok("Resource V1");
    }

    @GetMapping(value = "/resource", headers = "X-API-Version=2")
    public ResponseEntity<String> getResourceV2() {
        return ResponseEntity.ok("Resource V2");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 133. What is the use of the @JsonView annotation in Spring?

The `@JsonView` annotation is used in Spring to control the serialization of JSON data. It allows you to define different views for different parts of your application, so you can expose different subsets of the data to different clients.

### Example:
```java
public class Views {
    public static class Public {}
    public static class Internal extends Public {}
}

public class User {
    @JsonView(Views.Public.class)
    public String name;

    @JsonView(Views.Internal.class)
    public String email;
}

@RestController
public class UserController {
    @GetMapping("/user")
    @JsonView(Views.Public.class)
    public User getUser() {
        return new User("John Doe", "john.doe@example.com");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 134. How do you configure a custom JSON serializer in Spring?

You can configure a custom JSON serializer in Spring using the `@JsonSerialize` annotation along with a custom serializer class.

### Example:
```java
public class CustomDateSerializer extends JsonSerializer<Date> {
    @Override
    public void serialize(Date date, JsonGenerator gen, SerializerProvider serializers) throws IOException {
        SimpleDateFormat formatter = new SimpleDateFormat("yyyy-MM-dd");
        gen.writeString(formatter.format(date));
    }
}

public class Event {
    @JsonSerialize(using = CustomDateSerializer.class)
    private Date eventDate;

    // Getters and Setters
}

@RestController
public class EventController {
    @GetMapping("/event")
    public Event getEvent() {
        Event event = new Event();
        event.setEventDate(new Date());
        return event;
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 135. What is the use of the @JsonIgnore annotation?

The `@JsonIgnore` annotation is used to mark a property or field of a class to be ignored during the JSON serialization and deserialization process.

### Example:
```java
public class User {
    private String name;

    @JsonIgnore
    private String password;

    // Getters and Setters
}

@RestController
public class UserController {
    @GetMapping("/user")
    public User getUser() {
        return new User("John Doe", "secret");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 136. How do you configure a custom exception handler in Spring?

You can configure a custom exception handler in Spring using the `@ControllerAdvice` and `@ExceptionHandler` annotations.

### Example:
```java
@ControllerAdvice
public class GlobalExceptionHandler {

    @ExceptionHandler(ResourceNotFoundException.class)
    public ResponseEntity<String> handleResourceNotFoundException(ResourceNotFoundException ex) {
        return new ResponseEntity<>(ex.getMessage(), HttpStatus.NOT_FOUND);
    }

    @ExceptionHandler(Exception.class)
    public ResponseEntity<String> handleGeneralException(Exception ex) {
        return new ResponseEntity<>(ex.getMessage(), HttpStatus.INTERNAL_SERVER_ERROR);
    }
}

@RestController
public class ExampleController {
    @GetMapping("/example")
    public String getExample() {
        throw new ResourceNotFoundException("Resource not found");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 137. What is the use of the @RestControllerAdvice annotation?

The `@RestControllerAdvice` annotation is a specialized version of `@ControllerAdvice` that is used for global exception handling and data binding for `@RestController` classes.

### Example:
```java
@RestControllerAdvice
public class GlobalRestControllerAdvice {

    @ExceptionHandler(ResourceNotFoundException.class)
    public ResponseEntity<String> handleResourceNotFoundException(ResourceNotFoundException ex) {
        return new ResponseEntity<>(ex.getMessage(), HttpStatus.NOT_FOUND);
    }

    @ExceptionHandler(Exception.class)
    public ResponseEntity<String> handleGeneralException(Exception ex) {
        return new ResponseEntity<>(ex.getMessage(), HttpStatus.INTERNAL_SERVER_ERROR);
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 138. How do you configure CORS in a Spring application?

You can configure CORS in a Spring application using the `@CrossOrigin` annotation or by defining a `CorsConfiguration` bean.

### Example: Using @CrossOrigin
```java
@RestController
@CrossOrigin(origins = "http://allowed-origin.com")
public class ExampleController {
    @GetMapping("/example")
    public String getExample() {
        return "Example response";
    }
}
```

### Example: Global CORS Configuration
```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addCorsMappings(CorsRegistry registry) {
        registry.addMapping("/**").allowedOrigins("http://allowed-origin.com");
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 139. What is the use of the @CrossOrigin annotation?

The `@CrossOrigin` annotation is used to enable Cross-Origin Resource Sharing (CORS) on specific controller methods or classes, allowing client applications from different origins to access resources.

### Example:
```java
@RestController
public class ExampleController {

    @CrossOrigin(origins = "http://allowed-origin.com")
    @GetMapping("/example")
    public String getExample() {
        return "Example response";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 140. How do you configure a custom HTTP message converter in Spring?

You can configure a custom HTTP message converter in Spring by implementing the `HttpMessageConverter` interface and then adding it to the `WebMvcConfigurer`.

### Example:
```java
public class CustomMessageConverter extends AbstractHttpMessageConverter<MyCustomObject> {

    public CustomMessageConverter() {
        super(new MediaType("application", "x-mycustomtype"));
    }

    @Override
    protected boolean supports(Class<?> clazz) {
        return MyCustomObject.class.equals(clazz);
    }

    @Override
    protected MyCustomObject readInternal(Class<? extends MyCustomObject> clazz, HttpInputMessage inputMessage) throws IOException, HttpMessageNotReadableException {
        // Custom deserialization logic
    }

    @Override
    protected void writeInternal(MyCustomObject myCustomObject, HttpOutputMessage outputMessage) throws IOException, HttpMessageNotWritableException {
        // Custom serialization logic
    }
}

@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void configureMessageConverters(List<HttpMessageConverter<?>> converters) {
        converters.add(new CustomMessageConverter());
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 141. What is the use of the HttpMessageConverter interface in Spring?

The `HttpMessageConverter` interface in Spring is used to convert HTTP requests and responses to and from Java objects. It provides methods to read and write data for specific media types.

### Example:
```java
public class MyCustomObject {
    private String data;
    // Getters and Setters
}

public class CustomMessageConverter extends AbstractHttpMessageConverter<MyCustomObject> {
    // Implementation details
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 142. How do you configure a custom view resolver in Spring?

You can configure a custom view resolver in Spring by implementing the `ViewResolver` interface and then registering it as a bean.

### Example:
```java
public class CustomViewResolver implements ViewResolver {
    @Override
    public View resolveViewName(String viewName, Locale locale) throws Exception {
        // Custom view resolution logic
        return new CustomView();
    }
}

@Configuration
public class WebConfig {
    @Bean
    public ViewResolver customViewResolver() {
        return new CustomViewResolver();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 143. What is the use of the ViewResolver interface in Spring?

The `ViewResolver` interface in Spring is used to resolve view names to actual `View` instances. It allows you to define custom logic to map logical view names to specific view implementations.

### Example:
```java
public class CustomViewResolver implements ViewResolver {
    @Override
    public View resolveViewName(String viewName, Locale locale) throws Exception {
        // Custom view resolution logic
        return new CustomView();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 144. How do you configure a custom locale resolver in Spring?

You can configure a custom locale resolver in Spring by implementing the `LocaleResolver` interface and then registering it as a bean.

### Example:
```java
public class CustomLocaleResolver implements LocaleResolver {
    @Override
    public Locale resolveLocale(HttpServletRequest request) {
        // Custom locale resolution logic
    }

    @Override
    public void setLocale(HttpServletRequest request, HttpServletResponse response, Locale locale) {
        // Custom locale setting logic
    }
}

@Configuration
public class WebConfig {
    @Bean
    public LocaleResolver localeResolver() {
        return new CustomLocaleResolver();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 145. What is the use of the LocaleResolver interface in Spring?

The `LocaleResolver` interface in Spring is used to resolve the locale of the current request. It allows you to define custom logic to determine the locale based on the request.

### Example:
```java
public class CustomLocaleResolver implements LocaleResolver {
    @Override
    public Locale resolveLocale(HttpServletRequest request) {
        // Custom locale resolution logic
    }

    @Override
    public void setLocale(HttpServletRequest request, HttpServletResponse response, Locale locale) {
        // Custom locale setting logic
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 146. How do you configure a custom theme resolver in Spring?

You can configure a custom theme resolver in Spring by implementing the `ThemeResolver` interface and then registering it as a bean.

### Example:
```java
public class CustomThemeResolver implements ThemeResolver {
    @Override
    public String resolveThemeName(HttpServletRequest request) {
        // Custom theme resolution logic
    }

    @Override
    public void setThemeName(HttpServletRequest request, HttpServletResponse response, String themeName) {
        // Custom theme setting logic
    }
}

@Configuration
public class WebConfig {
    @Bean
    public ThemeResolver themeResolver() {
        return new CustomThemeResolver();
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 147. What is the use of the ThemeResolver interface in Spring?

The `ThemeResolver` interface in Spring is used to resolve the theme name for the current request. It allows you to define custom logic to determine the theme based on the request.

### Example:
```java
public class CustomThemeResolver implements ThemeResolver {
    @Override
    public String resolveThemeName(HttpServletRequest request) {
        // Custom theme resolution logic
    }

    @Override
    public void setThemeName(HttpServletRequest request, HttpServletResponse response, String themeName) {
        // Custom theme setting logic
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 148. How do you configure a custom session attribute in Spring?

You can configure a custom session attribute in Spring by using the `@SessionAttributes` and `@ModelAttribute` annotations in your controller.

### Example:
```java
@Controller
@SessionAttributes("myAttribute")
public class ExampleController {

    @ModelAttribute("myAttribute")
    public String myAttribute() {
        return "Default Value";
    }

    @GetMapping("/example")
    public String example(@ModelAttribute("myAttribute") String myAttribute, Model model) {
        model.addAttribute("myAttribute", "New Value");
        return "exampleView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 149. What is the use of the SessionAttributeStore interface in Spring?

The `SessionAttributeStore` interface in Spring is used to manage session attributes. It allows you to define custom logic for storing and retrieving session attributes.

### Example:
```java
public class CustomSessionAttributeStore implements SessionAttributeStore {
    @Override
    public void storeAttribute(WebRequest request, String attributeName, Object attributeValue) {
        // Custom logic to store the attribute
    }

    @Override
    public Object retrieveAttribute(WebRequest request, String attributeName) {
        // Custom logic to retrieve the attribute
    }

    @Override
    public void cleanupAttribute(WebRequest request, String attributeName) {
        // Custom logic to clean up the attribute
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

### 150. How do you configure a custom handler interceptor in Spring?

You can configure a custom handler interceptor in Spring by implementing the `HandlerInterceptor` interface and then registering it with the `WebMvcConfigurer`.

### Example:
```java
public class CustomHandlerInterceptor implements HandlerInterceptor {
    @Override
    public boolean preHandle(HttpServletRequest request, HttpServletResponse response, Object handler) throws Exception {
        // Custom pre-handle logic
        return true;
    }

    @Override
    public void postHandle(HttpServletRequest request, HttpServletResponse response, Object handler, ModelAndView modelAndView) throws Exception {
        // Custom post-handle logic
    }

    @Override
    public void afterCompletion(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex) throws Exception {
        // Custom after-completion logic
    }
}

@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(new CustomHandlerInterceptor());
    }
}
```
#### **[⬆ Back to Top](#level--spring-core-hard)**
---

# Spring MVC Easy Interview Questions and Answers
### 1. What is Spring MVC?
Spring MVC (Model-View-Controller) is a web framework from the Spring framework for building web applications. It follows the MVC design pattern, which separates the application into three interconnected components: Model, View, and Controller. This separation facilitates the development, testing, and maintenance of web applications.

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 2. Explain the architecture of Spring MVC.
Spring MVC architecture is based on the DispatcherServlet that handles all incoming requests. Here's a detailed flow:

1. **DispatcherServlet**: Central dispatcher for HTTP requests.
2. **Handler Mapping**: Determines the appropriate controller based on the URL.
3. **Controller**: Business logic execution and returning ModelAndView.
4. **ModelAndView**: Combines model data and view information.
5. **ViewResolver**: Resolves the view name to a specific view implementation.
6. **View**: Renders the model data.

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 3. What are the main components of Spring MVC?
- **DispatcherServlet**
- **Handler Mapping**
- **Controller**
- **ModelAndView**
- **ViewResolver**
- **View**

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 4. How do you configure Spring MVC in a web application?

### XML Configuration
```xml
<web-app>
    <servlet>
        <servlet-name>dispatcher</servlet-name>
        <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
        <load-on-startup>1</load-on-startup>
    </servlet>
    <servlet-mapping>
        <servlet-name>dispatcher</servlet-name>
        <url-pattern>/</url-pattern>
    </servlet-mapping>
</web-app>
```

### Java Configuration
```java
import org.springframework.context.annotation.Configuration;
import org.springframework.web.servlet.config.annotation.EnableWebMvc;
import org.springframework.web.servlet.config.annotation.WebMvcConfigurer;

@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {
    // Configuration code
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 5. What is the role of DispatcherServlet in Spring MVC?
DispatcherServlet is the core component of Spring MVC. It acts as a front controller, handling all incoming HTTP requests and delegating them to the appropriate controller based on the URL.

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 6. How do you define a controller in Spring MVC?

### Example
```java
import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RequestMethod;

@Controller
public class MyController {
    @RequestMapping(value = "/hello", method = RequestMethod.GET)
    public String sayHello() {
        return "hello"; // View name
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 7. What is the use of @RequestMapping annotation?
@RequestMapping is used to map web requests to specific handler methods or classes. It can map URLs, request methods, request parameters, headers, and more.

### Example
```java
@Controller
public class MyController {
    @RequestMapping(value = "/greet", method = RequestMethod.GET)
    public String greet() {
        return "greeting"; // View name
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 8. How do you handle form submission in Spring MVC?

### Example
```java
@Controller
public class FormController {
    @RequestMapping(value = "/submitForm", method = RequestMethod.POST)
    public String submitForm(@ModelAttribute("formData") FormData formData, Model model) {
        model.addAttribute("data", formData);
        return "formResult";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 9. What is ModelAndView in Spring MVC?
ModelAndView is a holder for both model data and view name. It allows a controller to return both the data and the name of the view to be rendered.

### Example
```java
@Controller
public class MyController {
    @RequestMapping("/showView")
    public ModelAndView showView() {
        ModelAndView mav = new ModelAndView("viewName");
        mav.addObject("message", "Hello, World!");
        return mav;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 10. How do you return JSON data from a Spring MVC controller?

### Example
```java
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RequestMethod;
import org.springframework.web.bind.annotation.ResponseBody;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class JsonController {
    @RequestMapping(value = "/data", method = RequestMethod.GET)
    @ResponseBody
    public MyData getData() {
        return new MyData("Hello", 123);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 11. Explain the difference between @Controller and @RestController.
- **@Controller**: Used for regular controllers. It returns views.
- **@RestController**: A combination of @Controller and @ResponseBody. It returns data directly, typically in JSON or XML format.

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 12. What is the use of @PathVariable annotation?
@PathVariable is used to extract values from URI templates.

### Example
```java
@Controller
public class PathVariableController {
    @RequestMapping("/user/{id}")
    public String getUser(@PathVariable("id") int id, Model model) {
        model.addAttribute("userId", id);
        return "userView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 13. How do you inject a service into a Spring MVC controller?

### Example
```java
@Controller
public class MyController {
    @Autowired
    private MyService myService;

    @RequestMapping("/service")
    public String useService(Model model) {
        String result = myService.performAction();
        model.addAttribute("result", result);
        return "serviceView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 14. What is the role of ViewResolver in Spring MVC?
ViewResolver resolves view names to actual view implementations. It allows for a flexible view rendering strategy.

### Example
```java
@Bean
public InternalResourceViewResolver viewResolver() {
    InternalResourceViewResolver resolver = new InternalResourceViewResolver();
    resolver.setPrefix("/WEB-INF/views/");
    resolver.setSuffix(".jsp");
    return resolver;
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 15. How do you handle exceptions in Spring MVC?

### Example
```java
@ControllerAdvice
public class GlobalExceptionHandler {
    @ExceptionHandler(Exception.class)
    public ModelAndView handleException(Exception ex) {
        ModelAndView mav = new ModelAndView("error");
        mav.addObject("message", ex.getMessage());
        return mav;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 16. What is the difference between @RequestParam and @PathVariable?
- **@RequestParam**: Extracts values from query parameters.
- **@PathVariable**: Extracts values from URI path segments.

### Example
```java
// Using @RequestParam
@RequestMapping("/search")
public String search(@RequestParam("query") String query, Model model) {
    model.addAttribute("query", query);
    return "searchResult";
}

// Using @PathVariable
@RequestMapping("/user/{id}")
public String getUser(@PathVariable("id") int id, Model model) {
    model.addAttribute("userId", id);
    return "userView";
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 17. How do you perform validation in Spring MVC?

### Example
```java
@Controller
public class FormController {
    @RequestMapping(value = "/submitForm", method = RequestMethod.POST)
    public String submitForm(@Valid @ModelAttribute("formData") FormData formData, BindingResult result) {
        if (result.hasErrors()) {
            return "formView";
        }
        return "formResult";
    }
}

// FormData class with validation
public class FormData {
    @NotEmpty
    private String name;
    @Email
    private String email;

    // Getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 18. What is the use of @ModelAttribute annotation?
@ModelAttribute is used to bind a method parameter or method return value to a named model attribute.

### Example
```java
@Controller
public class MyController {
    @ModelAttribute("message")
    public String message() {
        return "Hello, World!";
    }

    @RequestMapping("/showMessage")
    public String showMessage() {
        return "messageView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 19. How do you configure a view resolver in Spring MVC?

### Example
```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {
    @Bean
    public InternalResourceViewResolver viewResolver() {
        InternalResourceViewResolver resolver = new InternalResourceViewResolver();
        resolver.setPrefix("/WEB-INF/views/");
        resolver.setSuffix(".jsp");
        return resolver;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 20. What is the default scope of a Spring MVC controller?
The default scope of a Spring MVC controller is singleton.

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 21. How do you handle file uploads in Spring MVC?

### Example
```java
@Controller
public class FileUploadController {
    @RequestMapping(value = "/upload", method = RequestMethod.POST)
    public String handleFileUpload(@RequestParam("file") MultipartFile file) {
        if (!file.isEmpty()) {
            // Save the file somewhere
        }
        return "uploadSuccess";
    }
}

// Configuration for multipart resolver
@Bean
public MultipartResolver multipartResolver() {
    CommonsMultipartResolver resolver = new CommonsMultipartResolver();
    resolver.setMaxUploadSize(1000000); // Max upload size in bytes
    return resolver;
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 22. What is the difference between @RequestBody and @ResponseBody?
- **@RequestBody**: Binds the HTTP request body to a method parameter.
- **@ResponseBody**: Indicates that the return value of a method should be used as the response body.

### Example
```java
@RestController
public class MyController {
    @RequestMapping(value = "/data", method = RequestMethod.POST)
    public MyData processData(@RequestBody MyData data) {
        return data;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 23. How do you configure a multipart resolver in Spring MVC?

### Example
```java
@Bean
public MultipartResolver multipartResolver() {
    CommonsMultipartResolver resolver = new CommonsMultipartResolver();
    resolver.setMaxUploadSize(1000000); // Max upload size in bytes
    return resolver;
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 24. How do you enable Spring MVC annotations?

### Example
```java
@Configuration
@EnableWebMvc
@ComponentScan(basePackages = "com.example")
public class WebConfig implements WebMvcConfigurer {
    // Configuration code
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

### 25. What is the use of @SessionAttributes annotation?
@SessionAttributes is used to store model attributes in the session.

### Example
```java
@Controller
@SessionAttributes("user")
public class SessionController {
    @ModelAttribute("user")
    public User createUser() {
        return new User();
    }

    @RequestMapping("/userForm")
    public String userForm() {
        return "userForm";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

# Spring MVC Medium Interview Questions and Answers
### 26. How do you manage static resources in Spring MVC?

Spring MVC provides the `ResourceHandlerRegistry` to manage static resources like images, CSS, and JavaScript files. This is typically done by overriding the `addResourceHandlers` method in a configuration class that implements the `WebMvcConfigurer` interface.

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addResourceHandlers(ResourceHandlerRegistry registry) {
        registry.addResourceHandler("/resources/**")
                .addResourceLocations("/public-resources/")
                .setCachePeriod(3600)
                .resourceChain(true)
                .addResolver(new PathResourceResolver());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

In this example, any requests for resources under `/resources/**` will be served from the `/public-resources/` directory.

### 27. Explain the role of HandlerMapping in Spring MVC.

`HandlerMapping` is an interface in Spring MVC that maps web requests to handler objects. These handlers are typically annotated with `@RequestMapping` or its variant annotations. The `HandlerMapping` interface defines a single method, `getHandler`, which returns a handler for a given request.

Example:

```java
@Controller
public class MyController {
    @RequestMapping("/home")
    public String home() {
        return "home";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

In this example, the `HandlerMapping` maps the `/home` URL to the `home` method of `MyController`.

### 28. What is the use of @InitBinder annotation?

The `@InitBinder` annotation is used to customize the data binding for a specific controller. It is often used for formatting and validating request parameters.

Example:

```java
@Controller
public class MyController {

    @InitBinder
    public void initBinder(WebDataBinder binder) {
        SimpleDateFormat dateFormat = new SimpleDateFormat("yyyy-MM-dd");
        dateFormat.setLenient(false);
        binder.registerCustomEditor(Date.class, new CustomDateEditor(dateFormat, false));
    }

    @RequestMapping("/submitDate")
    public String submitDate(@RequestParam("date") Date date) {
        // Handle the date
        return "success";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 29. How do you handle cross-origin requests in Spring MVC?

Cross-Origin Resource Sharing (CORS) can be managed using the `@CrossOrigin` annotation or by overriding the `addCorsMappings` method in a configuration class.

Using `@CrossOrigin`:

```java
@RestController
@CrossOrigin(origins = "http://example.com")
public class MyController {
    @GetMapping("/greeting")
    public String greeting() {
        return "Hello, World!";
    }
}
```

Using `addCorsMappings`:

```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addCorsMappings(CorsRegistry registry) {
        registry.addMapping("/**")
                .allowedOrigins("http://example.com")
                .allowedMethods("GET", "POST");
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 30. How do you configure internationalization in Spring MVC?

Internationalization (i18n) in Spring MVC involves configuring a `LocaleResolver` and resource bundles.

Configuration:

```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Bean
    public LocaleResolver localeResolver() {
        SessionLocaleResolver slr = new SessionLocaleResolver();
        slr.setDefaultLocale(Locale.US);
        return slr;
    }

    @Bean
    public LocaleChangeInterceptor localeChangeInterceptor() {
        LocaleChangeInterceptor lci = new LocaleChangeInterceptor();
        lci.setParamName("lang");
        return lci;
    }

    @Override
    public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(localeChangeInterceptor());
    }
}
```

Resource bundles:

```
messages_en.properties
messages_fr.properties
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 31. What is the role of Interceptor in Spring MVC?

Interceptors in Spring MVC are used to process requests before they reach the controller or after the controller has processed the request. They can be used for logging, authentication, and modifying response data.

Example:

```java
public class MyInterceptor implements HandlerInterceptor {
    @Override
    public boolean preHandle(HttpServletRequest request, HttpServletResponse response, Object handler) throws Exception {
        // Pre-processing
        return true;
    }

    @Override
    public void postHandle(HttpServletRequest request, HttpServletResponse response, Object handler, ModelAndView modelAndView) throws Exception {
        // Post-processing
    }

    @Override
    public void afterCompletion(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex) throws Exception {
        // After completion
    }
}
```

Configuration:

```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(new MyInterceptor());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 32. How do you implement security in a Spring MVC application?

Security in a Spring MVC application is typically implemented using Spring Security. This involves configuring security rules and authentication mechanisms.

Example configuration:

```java
@Configuration
@EnableWebSecurity
public class WebSecurityConfig extends WebSecurityConfigurerAdapter {
    @Override
    protected void configure(HttpSecurity http) throws Exception {
        http
            .authorizeRequests()
                .antMatchers("/", "/home").permitAll()
                .anyRequest().authenticated()
                .and()
            .formLogin()
                .loginPage("/login")
                .permitAll()
                .and()
            .logout()
                .permitAll();
    }

    @Autowired
    public void configureGlobal(AuthenticationManagerBuilder auth) throws Exception {
        auth
            .inMemoryAuthentication()
                .withUser("user").password("{noop}password").roles("USER");
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 33. What is the difference between Spring MVC and Spring Boot?

| Feature          | Spring MVC                                    | Spring Boot                                 |
|------------------|-----------------------------------------------|---------------------------------------------|
| Setup            | Manual configuration                          | Convention over configuration               |
| Dependencies     | Manually managed                              | Auto-managed via starters                   |
| Embedded Server  | Not included                                  | Includes embedded servers like Tomcat       |
| Configuration    | XML or Java-based                             | Application properties or YAML              |
| Focus            | Web application framework                     | Rapid application development               |

#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 34. How do you configure a custom HandlerExceptionResolver in Spring MVC?

Implement the `HandlerExceptionResolver` interface and override the `resolveException` method.

Example:

```java
public class MyExceptionResolver implements HandlerExceptionResolver {
    @Override
    public ModelAndView resolveException(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex) {
        ModelAndView mav = new ModelAndView();
        mav.addObject("exception", ex);
        mav.setViewName("error");
        return mav;
    }
}

@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void configureHandlerExceptionResolvers(List<HandlerExceptionResolver> resolvers) {
        resolvers.add(new MyExceptionResolver());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 35. What is the use of @CookieValue annotation?

The `@CookieValue` annotation is used to bind the value of an HTTP cookie to a method parameter in a controller.

Example:

```java
@Controller
public class MyController {
    @RequestMapping("/showCookie")
    public String showCookie(@CookieValue("myCookie") String cookieValue) {
        // Use the cookie value
        return "showCookie";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 36. How do you configure message converters in Spring MVC?

Message converters in Spring MVC are used to convert HTTP requests and responses. You can customize them by overriding the `configureMessageConverters` method.

Example:

```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void configureMessageConverters(List<HttpMessageConverter<?>> converters) {
        converters.add(new MappingJackson2HttpMessageConverter());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 37. What is the role of LocaleResolver in Spring MVC?

`LocaleResolver` determines the current locale based on the request. It is used for internationalization.

Example:

```java
@Bean
public LocaleResolver localeResolver() {
    SessionLocaleResolver slr = new SessionLocaleResolver();
    slr.setDefaultLocale(Locale.US);
    return slr;
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 38. How do you enable CORS in Spring MVC?

CORS can be enabled using the `@CrossOrigin` annotation or by overriding the `addCorsMappings` method in a configuration class.

Using `@CrossOrigin`:

```java
@RestController
@CrossOrigin(origins = "http://example.com")
public class MyController {
    @GetMapping("/greeting")
    public String greeting() {
        return "Hello, World!";
    }
}
```

Using `addCorsMappings`:

```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addCorsMappings(CorsRegistry registry) {
        registry.addMapping("/**")
                .allowedOrigins("http://example.com")
                .allowedMethods("GET", "POST");
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 39. What is the use of @RequestHeader annotation?

The `@RequestHeader` annotation is used to bind the value of an HTTP header to a method parameter in a controller.

Example:

```java
@Controller
public class MyController {
    @RequestMapping("/showHeader")
    public String showHeader(@RequestHeader("User-Agent") String userAgent) {
        // Use the header value
        return "showHeader";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 40. How do you implement RESTful web services using Spring MVC?

To implement RESTful web services, use `@RestController` and HTTP method-specific annotations like `@GetMapping`, `@PostMapping`, etc.

Example:

```java
@RestController
@RequestMapping("/api")
public class MyRestController {
    @GetMapping("/users/{id}")
    public User getUser(@PathVariable("id") Long id) {
        // Retrieve user by ID
        return new User(id, "John Doe");
    }

    @PostMapping("/users")
    public User createUser(@RequestBody User user) {
        // Create new user
        return user;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 41. How do you integrate Spring MVC with Thymeleaf?

To integrate Thymeleaf with Spring MVC, add the Thymeleaf dependency and configure a `ThymeleafViewResolver`.

Example configuration:

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>
```

Configuration class:

```java
@Configuration
public class ThymeleafConfig {
    @Bean
    public SpringTemplateEngine templateEngine() {
        SpringTemplateEngine templateEngine = new SpringTemplateEngine();
        templateEngine.setTemplateResolver(templateResolver());
        return templateEngine;
    }

    @Bean
    public SpringResourceTemplateResolver templateResolver() {
        SpringResourceTemplateResolver templateResolver = new SpringResourceTemplateResolver();
        templateResolver.setPrefix("classpath:/templates/");
        templateResolver.setSuffix(".html");
        return templateResolver;
    }

    @Bean
    public ThymeleafViewResolver viewResolver() {
        ThymeleafViewResolver viewResolver = new ThymeleafViewResolver();
        viewResolver.setTemplateEngine(templateEngine());
        return viewResolver;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 42. What is the use of @ResponseStatus annotation?

The `@ResponseStatus` annotation is used to mark a method or exception class with a status code and reason that should be returned.

Example:

```java
@ResponseStatus(HttpStatus.NOT_FOUND)
public class ResourceNotFoundException extends RuntimeException {
    public ResourceNotFoundException(String message) {
        super(message);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 43. How do you configure a custom view resolver in Spring MVC?

To configure a custom view resolver, create a bean of the `ViewResolver` type in your configuration class.

Example:

```java
@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Bean
    public ViewResolver viewResolver() {
        InternalResourceViewResolver resolver = new InternalResourceViewResolver();
        resolver.setPrefix("/WEB-INF/views/");
        resolver.setSuffix(".jsp");
        return resolver;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 44. What is the role of MultipartResolver in Spring MVC?

`MultipartResolver` is used to handle file uploads in Spring MVC. It parses multipart requests.

Example:

```java
@Bean
public CommonsMultipartResolver multipartResolver() {
    CommonsMultipartResolver resolver = new CommonsMultipartResolver();
    resolver.setMaxUploadSize(1000000);
    return resolver;
}
```

Controller:

```java
@Controller
public class FileUploadController {
    @PostMapping("/upload")
    public String handleFileUpload(@RequestParam("file") MultipartFile file) {
        // Handle file upload
        return "uploadSuccess";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 45. How do you handle AJAX requests in Spring MVC?

To handle AJAX requests, use `@RestController` or `@ResponseBody` in your controller methods.

Example:

```java
@RestController
public class MyController {
    @GetMapping("/getData")
    public String getData() {
        return "Data from server";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 46. What is the difference between @RequestMapping and @GetMapping?

`@RequestMapping` is a general-purpose annotation for mapping HTTP requests, while `@GetMapping` is a shortcut for `@RequestMapping` with the `GET` method.

Example:

```java
// Using @RequestMapping
@RequestMapping(value = "/home", method = RequestMethod.GET)
public String home() {
    return "home";
}

// Using @GetMapping
@GetMapping("/home")
public String home() {
    return "home";
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 47. How do you configure a custom interceptor in Spring MVC?

To configure a custom interceptor, implement the `HandlerInterceptor` interface and register it in your configuration class.

Example:

```java
public class MyInterceptor implements HandlerInterceptor {
    @Override
    public boolean preHandle(HttpServletRequest request, HttpServletResponse response, Object handler) throws Exception {
        // Pre-processing
        return true;
    }

    @Override
    public void postHandle(HttpServletRequest request, HttpServletResponse response, Object handler, ModelAndView modelAndView) throws Exception {
        // Post-processing
    }

    @Override
    public void afterCompletion(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex) throws Exception {
        // After completion
    }
}

@Configuration
public class WebConfig implements WebMvcConfigurer {
    @Override
    public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(new MyInterceptor());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 48. What is the use of @MatrixVariable annotation?

The `@MatrixVariable` annotation is used to extract matrix variables from the URL.

Example:

```java
@RestController
public class MyController {
    @GetMapping("/cars/{make}")
    public String getCars(@PathVariable String make, @MatrixVariable int year) {
        return "Make: " + make + ", Year: " + year;
    }
}
```

URL: `/cars/ford;year=2020`

#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 49. How do you configure a custom validator in Spring MVC?

To configure a custom validator, implement the `Validator` interface and register it.

Example:

```java
public class MyValidator implements Validator {
    @Override
    public boolean supports(Class<?> clazz) {
        return MyModel.class.equals(clazz);
    }

    @Override
    public void validate(Object target, Errors errors) {
        MyModel model = (MyModel) target;
        if (model.getField() == null) {
            errors.rejectValue("field", "field.required");
        }
    }
}

@Controller
public class MyController {
    @InitBinder
    protected void initBinder(WebDataBinder binder) {
        binder.addValidators(new MyValidator());
    }

    @PostMapping("/submit")
    public String submit(@Valid MyModel model, BindingResult result) {
        if (result.hasErrors()) {
            return "form";
        }
        return "success";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

### 50. What is the role of FlashMap in Spring MVC?

`FlashMap` is used to pass attributes from one request to another, typically after a redirect. It is useful for passing success or error messages.

Example:

```java
@Controller
public class MyController {
    @RequestMapping("/save")
    public String save(RedirectAttributes redirectAttributes) {
        redirectAttributes.addFlashAttribute("message", "Save successful");
        return "redirect:/result";
    }

    @RequestMapping("/result")
    public String result(@ModelAttribute("message") String message) {
        // Use the flash attribute
        return "result";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-medium)**
---

# Spring MVC Hard Interview Questions and Answers
### 51. How do you implement asynchronous request processing in Spring MVC?

To implement asynchronous request processing in Spring MVC, you can use the `DeferredResult` or `Callable` classes. This allows you to handle long-running requests without blocking the servlet container.

#### Example using `Callable`

```java
@Controller
public class AsyncController {

    @RequestMapping("/asyncCallable")
    public @ResponseBody Callable<String> processAsyncCallable() {
        return () -> {
            // Simulate a long-running task
            Thread.sleep(2000);
            return "Task completed";
        };
    }
}
```

#### Example using `DeferredResult`

```java
@Controller
public class AsyncController {

    @RequestMapping("/asyncDeferred")
    public @ResponseBody DeferredResult<String> processAsyncDeferred() {
        DeferredResult<String> deferredResult = new DeferredResult<>();
        new Thread(() -> {
            // Simulate a long-running task
            try {
                Thread.sleep(2000);
            } catch (InterruptedException e) {
                e.printStackTrace();
            }
            deferredResult.setResult("Task completed");
        }).start();
        return deferredResult;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 52. Explain the process of configuring Spring MVC with Java-based configuration.

Java-based configuration in Spring MVC involves creating a configuration class annotated with `@Configuration` and `@EnableWebMvc`. This class replaces the traditional `web.xml` and Spring XML configuration files.

#### Example

```java
@Configuration
@EnableWebMvc
@ComponentScan(basePackages = "com.example")
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public InternalResourceViewResolver viewResolver() {
        InternalResourceViewResolver resolver = new InternalResourceViewResolver();
        resolver.setPrefix("/WEB-INF/views/");
        resolver.setSuffix(".jsp");
        return resolver;
    }

    @Override
    public void addResourceHandlers(ResourceHandlerRegistry registry) {
        registry.addResourceHandler("/resources/**").addResourceLocations("/resources/");
    }
}
```

You also need to create an initializer class to replace `web.xml`:

```java
public class WebAppInitializer implements WebApplicationInitializer {

    @Override
    public void onStartup(ServletContext servletContext) throws ServletException {
        AnnotationConfigWebApplicationContext context = new AnnotationConfigWebApplicationContext();
        context.register(WebConfig.class);
        context.setServletContext(servletContext);

        ServletRegistration.Dynamic servlet = servletContext.addServlet("dispatcher", new DispatcherServlet(context));
        servlet.setLoadOnStartup(1);
        servlet.addMapping("/");
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 53. How do you configure a custom message converter in Spring MVC?

To configure a custom message converter, you can override the `configureMessageConverters` method in your configuration class.

#### Example

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Override
    public void configureMessageConverters(List<HttpMessageConverter<?>> converters) {
        converters.add(new MappingJackson2HttpMessageConverter());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 54. What is the use of `@ControllerAdvice` annotation?

The `@ControllerAdvice` annotation is used to define a global exception handler, data binder, and model attribute for all controllers. It helps to separate cross-cutting concerns from individual controllers.

#### Example

```java
@ControllerAdvice
public class GlobalExceptionHandler {

    @ExceptionHandler(Exception.class)
    public ResponseEntity<String> handleException(Exception ex) {
        return new ResponseEntity<>("Global Exception Handler: " + ex.getMessage(), HttpStatus.INTERNAL_SERVER_ERROR);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 55. How do you handle WebSocket communication in a Spring MVC application?

To handle WebSocket communication, you need to configure a `WebSocketConfig` class and use `@EnableWebSocket` annotation.

#### Example

```java
@Configuration
@EnableWebSocket
public class WebSocketConfig implements WebSocketConfigurer {

    @Override
    public void registerWebSocketHandlers(WebSocketHandlerRegistry registry) {
        registry.addHandler(new MyWebSocketHandler(), "/websocket");
    }
}

public class MyWebSocketHandler extends TextWebSocketHandler {

    @Override
    public void handleTextMessage(WebSocketSession session, TextMessage message) throws Exception {
        String payload = message.getPayload();
        session.sendMessage(new TextMessage("Received: " + payload));
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 56. How do you configure a custom locale resolver in Spring MVC?

You can configure a custom locale resolver by implementing the `LocaleResolver` interface and then defining it as a bean in your configuration.

#### Example

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public LocaleResolver localeResolver() {
        SessionLocaleResolver localeResolver = new SessionLocaleResolver();
        localeResolver.setDefaultLocale(Locale.US);
        return localeResolver;
    }

    @Override
    public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(new LocaleChangeInterceptor());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 57. Explain the role of `WebApplicationInitializer` in Spring MVC.

`WebApplicationInitializer` is an interface provided by Spring that allows you to configure the `ServletContext` programmatically. It replaces the traditional `web.xml` file.

#### Example

```java
public class WebAppInitializer implements WebApplicationInitializer {

    @Override
    public void onStartup(ServletContext servletContext) throws ServletException {
        AnnotationConfigWebApplicationContext context = new AnnotationConfigWebApplicationContext();
        context.register(WebConfig.class);
        context.setServletContext(servletContext);

        ServletRegistration.Dynamic servlet = servletContext.addServlet("dispatcher", new DispatcherServlet(context));
        servlet.setLoadOnStartup(1);
        servlet.addMapping("/");
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 58. How do you implement file download functionality in Spring MVC?

To implement file download functionality, you can use `ResponseEntity` to set the headers and content.

#### Example

```java
@Controller
public class FileDownloadController {

    @RequestMapping("/download")
    public ResponseEntity<Resource> downloadFile() {
        Path path = Paths.get("path/to/file.txt");
        Resource resource = new FileSystemResource(path.toFile());

        HttpHeaders headers = new HttpHeaders();
        headers.add(HttpHeaders.CONTENT_DISPOSITION, "attachment; filename=file.txt");

        return ResponseEntity.ok()
                .headers(headers)
                .contentLength(path.toFile().length())
                .contentType(MediaType.APPLICATION_OCTET_STREAM)
                .body(resource);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 59. How do you configure a custom exception handler in Spring MVC?

You can configure a custom exception handler using the `@ExceptionHandler` annotation within a `@ControllerAdvice` class.

#### Example

```java
@ControllerAdvice
public class CustomExceptionHandler {

    @ExceptionHandler(ResourceNotFoundException.class)
    public ResponseEntity<String> handleResourceNotFoundException(ResourceNotFoundException ex) {
        return new ResponseEntity<>("Resource not found: " + ex.getMessage(), HttpStatus.NOT_FOUND);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 60. What is the use of `@RestControllerAdvice` annotation?

`@RestControllerAdvice` is a specialized version of `@ControllerAdvice` that is used to handle exceptions and provide custom responses for RESTful web services. It combines `@ControllerAdvice` and `@ResponseBody`.

#### Example

```java
@RestControllerAdvice
public class RestExceptionHandler {

    @ExceptionHandler(ResourceNotFoundException.class)
    public ResponseEntity<String> handleResourceNotFoundException(ResourceNotFoundException ex) {
        return new ResponseEntity<>("Resource not found: " + ex.getMessage(), HttpStatus.NOT_FOUND);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 61. How do you integrate Spring MVC with Hibernate?

To integrate Spring MVC with Hibernate, you need to configure a `DataSource`, `SessionFactory`, and transaction management.

#### Example

```java
@Configuration
@EnableTransactionManagement
public class AppConfig {

    @Bean
    public DataSource dataSource() {
        DriverManagerDataSource dataSource = new DriverManagerDataSource();
        dataSource.setDriverClassName("com.mysql.cj.jdbc.Driver");
        dataSource.setUrl("jdbc:mysql://localhost:3306/mydb");
        dataSource.setUsername("root");
        dataSource.setPassword("password");
        return dataSource;
    }

    @Bean
    public LocalSessionFactoryBean sessionFactory() {
        LocalSessionFactoryBean sessionFactory = new LocalSessionFactoryBean();
        sessionFactory.setDataSource(dataSource());
        sessionFactory.setPackagesToScan("com.example.model");
        sessionFactory.setHibernateProperties(hibernateProperties());
        return sessionFactory;
    }

    private Properties hibernateProperties() {
        Properties properties = new Properties();
        properties.put("hibernate.dialect", "org.hibernate.dialect.MySQL5Dialect");
        properties.put("hibernate.show_sql", "true");
        return properties;
    }

    @Bean
    public HibernateTransactionManager transactionManager() {
        HibernateTransactionManager transactionManager = new HibernateTransactionManager();
        transactionManager.setSessionFactory(sessionFactory().getObject());
        return transactionManager;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 62. Explain the process of handling multipart requests in Spring MVC.

To handle multipart requests, you need to configure a `MultipartResolver` bean in your configuration class.

#### Example

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public MultipartResolver multipartResolver() {
        CommonsMultipartResolver multipartResolver = new CommonsMultipartResolver();
        multipartResolver.setMaxUploadSize(5000000);
        return multipartResolver;
    }
}

@Controller
public class FileUploadController {

    @PostMapping("/upload")
    public String handleFileUpload(@RequestParam("file") MultipartFile file) {
        if (!file.isEmpty()) {
            try {
                byte[] bytes = file.getBytes();
                Path path = Paths.get("/uploads/" + file.getOriginalFilename());
                Files.write(path, bytes);
                return "File uploaded successfully";
            } catch (IOException e) {
                e.printStackTrace();
                return "File upload failed";
            }
        } else {
            return "File is empty";
        }
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 63. How do you configure a custom argument resolver in Spring MVC?

To configure a custom argument resolver, implement the `HandlerMethodArgumentResolver` interface and register it in your configuration class.

#### Example

```java
public class CustomArgumentResolver implements HandlerMethodArgumentResolver {

    @Override
    public boolean supportsParameter(MethodParameter parameter) {
        return parameter.getParameterType().equals(MyCustomObject.class);
    }

    @Override
    public Object resolveArgument(MethodParameter parameter, ModelAndViewContainer mavContainer,
                                  NativeWebRequest webRequest, WebDataBinderFactory binderFactory) throws Exception {
        // Custom logic to resolve the argument
        return new MyCustomObject();
    }
}

@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Override
    public void addArgumentResolvers(List<HandlerMethodArgumentResolver> resolvers) {
        resolvers.add(new CustomArgumentResolver());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 64. What is the role of `ContentNegotiationManager` in Spring MVC?

`ContentNegotiationManager` is responsible for determining the content type of the response based on the request. It uses various strategies like path extension, query parameter, and `Accept` header.

#### Example

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Override
    public void configureContentNegotiation(ContentNegotiationConfigurer configurer) {
        configurer.favorPathExtension(true)
                  .favorParameter(false)
                  .ignoreAcceptHeader(false)
                  .useRegisteredExtensionsOnly(false)
                  .defaultContentType(MediaType.APPLICATION_JSON);
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 65. How do you implement HATEOAS in a Spring MVC application?

To implement HATEOAS, use Spring HATEOAS library to add hypermedia links to your resources.

#### Example

```java
@RestController
public class MyController {

    @GetMapping("/resource")
    public Resource<MyResource> getResource() {
        MyResource resource = new MyResource("data");
        Resource<MyResource> resourceWithLinks = new Resource<>(resource);
        resourceWithLinks.add(linkTo(methodOn(MyController.class).getResource()).withSelfRel());
        return resourceWithLinks;
    }
}

class MyResource {
    private String data;

    public MyResource(String data) {
        this.data = data;
    }

    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 66. How do you configure a custom handler method return value handler in Spring MVC?

To configure a custom handler method return value handler, implement the `HandlerMethodReturnValueHandler` interface and register it in your configuration class.

#### Example

```java
public class CustomReturnValueHandler implements HandlerMethodReturnValueHandler {

    @Override
    public boolean supportsReturnType(MethodParameter returnType) {
        return returnType.getParameterType().equals(MyCustomObject.class);
    }

    @Override
    public void handleReturnValue(Object returnValue, MethodParameter returnType, ModelAndViewContainer mavContainer,
                                  NativeWebRequest webRequest) throws Exception {
        // Custom logic to handle the return value
        mavContainer.setRequestHandled(true);
    }
}

@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Override
    public void addReturnValueHandlers(List<HandlerMethodReturnValueHandler> returnValueHandlers) {
        returnValueHandlers.add(new CustomReturnValueHandler());
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 67. Explain the process of configuring Spring MVC with XML-based configuration.

XML-based configuration involves defining beans and settings in an XML file. This approach is less common but still supported.

#### Example

`web.xml`

```xml
<web-app>
    <servlet>
        <servlet-name>dispatcher</servlet-name>
        <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
        <load-on-startup>1</load-on-startup>
    </servlet>
    <servlet-mapping>
        <servlet-name>dispatcher</servlet-name>
        <url-pattern>/</url-pattern>
    </servlet-mapping>
</web-app>
```

`dispatcher-servlet.xml`

```xml
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xmlns:context="http://www.springframework.org/schema/context"
       xmlns:mvc="http://www.springframework.org/schema/mvc"
       xsi:schemaLocation="http://www.springframework.org/schema/beans 
           http://www.springframework.org/schema/beans/spring-beans.xsd
           http://www.springframework.org/schema/context 
           http://www.springframework.org/schema/context/spring-context.xsd
           http://www.springframework.org/schema/mvc 
           http://www.springframework.org/schema/mvc/spring-mvc.xsd">

    <context:component-scan base-package="com.example"/>

    <mvc:annotation-driven/>

    <bean class="org.springframework.web.servlet.view.InternalResourceViewResolver">
        <property name="prefix" value="/WEB-INF/views/"/>
        <property name="suffix" value=".jsp"/>
    </bean>

</beans>
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 68. How do you handle JSONP requests in Spring MVC?

To handle JSONP requests, you can use the `MappingJackson2JsonView` with a `JsonpCallbackFilter`.

#### Example

```java
@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public FilterRegistrationBean<JsonpCallbackFilter> jsonpCallbackFilter() {
        FilterRegistrationBean<JsonpCallbackFilter> filterRegistrationBean = new FilterRegistrationBean<>(new JsonpCallbackFilter());
        filterRegistrationBean.addUrlPatterns("/jsonp/*");
        return filterRegistrationBean;
    }
}

@RestController
public class JsonpController {

    @GetMapping("/jsonp/resource")
    public MappingJacksonValue getJsonpResource(@RequestParam("callback") String callback) {
        MyResource resource = new MyResource("data");
        MappingJacksonValue value = new MappingJacksonValue(resource);
        value.setJsonpFunction(callback);
        return value;
    }
}

class MyResource {
    private String data;

    public MyResource(String data) {
        this.data = data;
    }

    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 69. How do you configure a custom view in Spring MVC?

To configure a custom view, you can extend the `AbstractView` class and define it as a bean in your configuration class.

#### Example

```java
public class MyCustomView extends AbstractView {

    @Override
    protected void renderMergedOutputModel(Map<String, Object> model, HttpServletRequest request,
                                           HttpServletResponse response) throws Exception {
        response.setContentType("text/plain");
        PrintWriter writer = response.getWriter();
        writer.write("Custom View Content");
    }
}

@Configuration
@EnableWebMvc
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public ViewResolver viewResolver() {
        return new BeanNameViewResolver();
    }

    @Bean
    public View myCustomView() {
        return new MyCustomView();
    }
}

@Controller
public class MyController {

    @GetMapping("/customView")
    public String getCustomView() {
        return "myCustomView";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 70. What is the role of `HandlerAdapter` in Spring MVC?

`HandlerAdapter` is an interface that helps to invoke the handler methods based on the type of the handler. It is responsible for executing the handler with the appropriate parameters and returning the `ModelAndView`.

#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 71. How do you configure a custom model attribute in Spring MVC?

To configure a custom model attribute, use the `@ModelAttribute` annotation in your controller methods.

#### Example

```java
@Controller
public class MyController {

    @ModelAttribute("myAttribute")
    public MyCustomObject populateModel() {
        return new MyCustomObject();
    }

    @GetMapping("/modelAttribute")
    public String handleRequest() {
        return "viewName";
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 72. How do you implement server-sent events (SSE) in a Spring MVC application?

To implement SSE, you can use the `SseEmitter` class.

#### Example

```java
@RestController
public class SseController {

    @GetMapping("/sse")
    public SseEmitter handleSse() {
        SseEmitter emitter = new SseEmitter();
        new Thread(() -> {
            try {
                for (int i = 0; i < 5; i++) {
                    emitter.send("SSE event " + i);
                    Thread.sleep(1000);
                }
                emitter.complete();
            } catch (Exception e) {
                emitter.completeWithError(e);
            }
        }).start();
        return emitter;
    }
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 73. How do you configure a custom form handler in Spring MVC?

To configure a custom form handler, use the `@ModelAttribute` annotation and a corresponding handler method.

#### Example

```java
@Controller
public class FormController {

    @GetMapping("/form")
    public String showForm(Model model) {
        model.addAttribute("formObject", new MyFormObject());
        return "formView";
    }

    @PostMapping("/form")
    public String handleForm(@ModelAttribute("formObject") MyFormObject formObject) {
        // handle form submission
        return "resultView";
    }
}

class MyFormObject {
    // form fields
}
```
#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 74. What is the use of @JsonView annotation in Spring MVC?

The `@JsonView` annotation is used in Spring MVC to control the serialization of JSON objects. When a REST API returns a JSON response, there may be scenarios where different clients require different views of the same data object. The `@JsonView` annotation allows you to define multiple views and control which properties of the object are serialized based on the view requested.

#### How it works:

1. **Define Views**: Create interfaces to represent different views.
2. **Annotate Fields**: Use the `@JsonView` annotation on fields to include them in specific views.
3. **Specify View in Controller**: Use the `@JsonView` annotation in the controller method to specify which view to use for serialization.

#### Example:

```java
// Step 1: Define Views
public class Views {
    public static class Public {}
    public static class Internal extends Public {}
}

// Step 2: Annotate Fields
public class User {
    @JsonView(Views.Public.class)
    public String username;

    @JsonView(Views.Internal.class)
    public String password;
}

// Step 3: Specify View in Controller
@RestController
public class UserController {

    @GetMapping("/user")
    @JsonView(Views.Public.class)
    public User getUserPublicView() {
        User user = new User();
        user.username = "john_doe";
        user.password = "secret";
        return user;
    }

    @GetMapping("/user/internal")
    @JsonView(Views.Internal.class)
    public User getUserInternalView() {
        User user = new User();
        user.username = "john_doe";
        user.password = "secret";
        return user;
    }
}
```

#### Explanation:

- **Views**: Define different views using interfaces.
- **Annotations on Fields**: Annotate fields in the User class to specify which fields belong to which views.
- **Controller Methods**: In the controller, specify the view to use for serialization using the `@JsonView` annotation.

In this example:
- A request to `/user` will return only the `username` field.
- A request to `/user/internal` will return both `username` and `password` fields.

#### **[⬆ Back to Top](#level--spring-mvc-hard)**
---

### 75. How do you implement OAuth2 authentication in a Spring MVC application?

OAuth2 is a widely-used protocol for authorization that allows third-party applications to access a user's resources without exposing their credentials. Implementing OAuth2 in a Spring MVC application involves configuring Spring Security to handle the OAuth2 flow.

#### Steps to Implement OAuth2 Authentication:

1. **Add Dependencies**: Include the necessary Spring Security OAuth2 dependencies.
2. **Configure Security**: Configure OAuth2 resources and security.
3. **Create Security Configuration**: Define security rules and specify the OAuth2 login configurations.

#### Example:

1. **Add Dependencies**:

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-security</artifactId>
</dependency>
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-oauth2-client</artifactId>
</dependency>
```

2. **Configure Security**:

Create a `application.yml` or `application.properties` file with OAuth2 client details:

```yaml
spring:
  security:
    oauth2:
      client:
        registration:
          google:
            client-id: YOUR_CLIENT_ID
            client-secret: YOUR_CLIENT_SECRET
            scope: profile, email
            redirect-uri: "{baseUrl}/login/oauth2/code/{registrationId}"
            authorization-grant-type: authorization_code
            client-authentication-method: post
        provider:
          google:
            authorization-uri: https://accounts.google.com/o/oauth2/v2/auth
            token-uri: https://oauth2.googleapis.com/token
            user-info-uri: https://www.googleapis.com/oauth2/v3/userinfo
            user-name-attribute: sub
```

3. **Create Security Configuration**:

```java
import org.springframework.context.annotation.Configuration;
import org.springframework.security.config.annotation.web.builders.HttpSecurity;
import org.springframework.security.config.annotation.web.configuration.EnableWebSecurity;
import org.springframework.security.config.annotation.web.configuration.WebSecurityConfigurerAdapter;

@Configuration
@EnableWebSecurity
public class SecurityConfig extends WebSecurityConfigurerAdapter {

    @Override
    protected void configure(HttpSecurity http) throws Exception {
        http
            .authorizeRequests(authorizeRequests ->
                authorizeRequests
                    .antMatchers("/", "/login**", "/error**").permitAll()
                    .anyRequest().authenticated()
            )
            .oauth2Login(oauth2Login ->
                oauth2Login
                    .loginPage("/login")
                    .defaultSuccessURL("/home", true)
            );
    }
}
```

4. **Create Controller**:

```java
import org.springframework.security.core.annotation.AuthenticationPrincipal;
import org.springframework.security.oauth2.core.oidc.user.OidcUser;
import org.springframework.stereotype.Controller;
import org.springframework.ui.Model;
import org.springframework.web.bind.annotation.GetMapping;

@Controller
public class HomeController {

    @GetMapping("/home")
    public String home(Model model, @AuthenticationPrincipal OidcUser principal) {
        model.addAttribute("name", principal.getName());
        return "home";
    }

    @GetMapping("/login")
    public String login() {
        return "login";
    }
}
```

#### Explanation:

- **Dependencies**: Add Spring Security and OAuth2 client dependencies.
- **Configuration**: Set up OAuth2 client details in application properties.
- **Security Configuration**: Configure HTTP security to allow OAuth2 login.
- **Controller**: Create a controller to handle login and home page requests.

In this example, the application supports Google OAuth2 login. Users can log in via Google, and after successful authentication, they are redirected to the home page. The logged-in user's details are accessible via the `@AuthenticationPrincipal` annotation.

These steps provide a basic setup for OAuth2 authentication in a Spring MVC application. Depending on your requirements, you may need to customize and extend these configurations.

#### **[⬆ Back to Top](#level--spring-mvc-easy)**
---

# Spring Data JPA Easy Interview Questions and Answers
### 1. What is Spring Data JPA?
Spring Data JPA is a part of the larger Spring Data family. Its primary purpose is to simplify the data access layer by providing a repository abstraction over JPA. It helps reduce boilerplate code needed for database operations and offers a set of high-level abstractions for working with relational databases.

Example:
```java
public interface UserRepository extends JpaRepository<User, Long> {
    List<User> findByLastName(String lastName);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 2. What is the purpose of the `@Entity` annotation in JPA?
The `@Entity` annotation specifies that the class is an entity and is mapped to a database table. This is a mandatory annotation for JPA entities.

Example:
```java
import javax.persistence.Entity;
import javax.persistence.Id;

@Entity
public class User {
    @Id
    private Long id;
    private String name;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 3. What is an EntityManager in JPA?
The EntityManager is the primary JPA interface for interacting with the persistence context. It is responsible for managing the lifecycle of entity instances, including CRUD operations.

Example:
```java
@PersistenceContext
private EntityManager entityManager;

public void saveUser(User user) {
    entityManager.persist(user);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 4. What is the role of the `@Id` annotation in JPA?
The `@Id` annotation specifies the primary key of an entity. It is a mandatory annotation for each entity class.

Example:
```java
@Entity
public class User {
    @Id
    private Long id;
    private String name;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 5. How do you define a primary key in a JPA entity?
A primary key in a JPA entity is defined using the `@Id` annotation. Optionally, you can use the `@GeneratedValue` annotation to specify how the primary key should be generated.

Example:
```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String name;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 6. What is the difference between `findById` and `getOne` methods in JPA?
- `findById`: Returns an `Optional` containing the entity, or `Optional.empty()` if not found. It is a safe, immediate fetch.
- `getOne`: Returns a reference to the entity without fetching it immediately. It uses lazy loading and can throw an `EntityNotFoundException` if the entity does not exist upon access.

Example:
```java
Optional<User> user = userRepository.findById(1L);
User user = userRepository.getOne(1L);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 7. What is the purpose of the `@Table` annotation in JPA?
The `@Table` annotation specifies the primary table for the entity. It allows customization of the table name and schema.

Example:
```java
@Entity
@Table(name = "users")
public class User {
    @Id
    private Long id;
    private String name;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 8. Explain the difference between `@Column` and `@JoinColumn`.
- `@Column`: Maps a field to a column in the database table.
- `@JoinColumn`: Specifies a column for joining an entity association.

Example:
```java
@Entity
public class User {
    @Column(name = "username")
    private String name;

    @ManyToOne
    @JoinColumn(name = "department_id")
    private Department department;
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 9. What is the role of the `@GeneratedValue` annotation in JPA?
The `@GeneratedValue` annotation specifies the generation strategy for primary key values. Common strategies include `AUTO`, `IDENTITY`, `SEQUENCE`, and `TABLE`.

Example:
```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String name;
    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 10. What is the default fetch type for `@OneToMany` and `@ManyToOne` relationships in JPA?
- `@OneToMany`: `LAZY` by default, meaning the associated entities are loaded on demand.
- `@ManyToOne`: `EAGER` by default, meaning the associated entity is loaded immediately.

Example:
```java
@Entity
public class Department {
    @OneToMany(mappedBy = "department", fetch = FetchType.LAZY)
    private List<User> users;
}

@Entity
public class User {
    @ManyToOne(fetch = FetchType.EAGER)
    @JoinColumn(name = "department_id")
    private Department department;
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 11. How do you define a one-to-many relationship in JPA?
A one-to-many relationship is defined using the `@OneToMany` and `@ManyToOne` annotations, with the `mappedBy` attribute specifying the relationship owner.

Example:
```java
@Entity
public class Department {
    @Id
    private Long id;
    private String name;

    @OneToMany(mappedBy = "department")
    private List<User> users;
}

@Entity
public class User {
    @Id
    private Long id;
    private String name;

    @ManyToOne
    @JoinColumn(name = "department_id")
    private Department department;
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 12. What is a repository in Spring Data JPA?
A repository in Spring Data JPA is an interface that provides CRUD operations for an entity. It extends the `JpaRepository` interface, which includes methods for saving, deleting, and finding entities.

Example:
```java
public interface UserRepository extends JpaRepository<User, Long> {
    List<User> findByLastName(String lastName);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 13. What is the purpose of the `@Repository` annotation in Spring Data JPA?
The `@Repository` annotation is a specialization of the `@Component` annotation, indicating that the class is a DAO (Data Access Object). It also enables exception translation, converting database exceptions into Spring's `DataAccessException`.

Example:
```java
@Repository
public interface UserRepository extends JpaRepository<User, Long> {
    List<User> findByLastName(String lastName);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 14. How do you create a custom query in Spring Data JPA?
Custom queries can be created using the `@Query` annotation with JPQL or native SQL. This allows you to define complex queries beyond the capabilities of derived query methods.

Example:
```java
public interface UserRepository extends JpaRepository<User, Long> {
    @Query("SELECT u FROM User u WHERE u.lastName = ?1")
    List<User> findUsersByLastName(String lastName);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 15. What is the purpose of the `@Query` annotation in Spring Data JPA?
The `@Query` annotation is used to define custom JPQL or SQL queries directly on repository methods. It allows for more complex queries than those created using method naming conventions.

Example:
```java
public interface UserRepository extends JpaRepository<User, Long> {
    @Query("SELECT u FROM User u WHERE u.lastName = ?1")
    List<User> findUsersByLastName(String lastName);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 16. What is a JPQL?
JPQL (Java Persistence Query Language) is a query language used to create queries against entities stored in a relational database. It is similar to SQL but operates on the entity model rather than directly on database tables.

Example:
```java
@Query("SELECT u FROM User u WHERE u.lastName = :lastName")
List<User> findUsersByLastName(@Param("lastName") String lastName);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 17. What is the difference between JPQL and SQL?
- **JPQL**: Operates on the entity model and uses entity names and relationships.
- **SQL**: Operates directly on database tables and columns.

Example:
- JPQL: `SELECT u FROM User u WHERE u.lastName = :lastName`
- SQL: `SELECT * FROM users WHERE last_name = ?`

#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 18. What is the purpose of the `@Modifying` annotation in Spring Data JPA?
The `@Modifying` annotation is used in conjunction with `@Query` to indicate that the query is an update, delete, or insert operation. It modifies the data rather than just selecting it.

Example:
```java
@Modifying
@Query("UPDATE User u SET u.lastName = :lastName WHERE u.id = :id")
int updateUserLastName(@Param("id") Long id, @Param("lastName") String lastName);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 19. How do you handle transactions in Spring Data JPA?
Transactions in Spring Data JPA are managed using the `@Transactional` annotation. This annotation can be applied at the class or method level to define transactional boundaries.

Example:
```java
@Service
public class UserService {
    @Autowired
    private UserRepository userRepository;

    @Transactional
    public void updateUser(User user) {
        userRepository.save(user);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 20. What is the `@Transactional` annotation used for in Spring Data JPA?
The `@Transactional` annotation is used to define the scope of a single database transaction. It ensures that all operations within the annotated method are executed within a transaction context.

Example:
```java
@Service
public class UserService {
    @Autowired
    private UserRepository userRepository;

    @Transactional
    public void updateUser(User user) {
        userRepository.save(user);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 21. How do you paginate results in Spring Data JPA?
Pagination in Spring Data JPA is achieved using the `Pageable` interface and the `Page` object. The repository methods should accept a `Pageable` parameter and return a `Page` object.

Example:
```java
public interface UserRepository extends JpaRepository<User, Long> {
    Page<User> findByLastName(String lastName, Pageable pageable);
}

// Usage
Pageable pageable = PageRequest.of(0, 10);
Page<User> users = userRepository.findByLastName("Smith", pageable);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 22. What is the `Pageable` interface in Spring Data JPA?
The `Pageable` interface is used to specify pagination information for a query, such as the page number, page size, and sorting options.

Example:
```java
Pageable pageable = PageRequest.of(0, 10, Sort.by("lastName").ascending());
Page<User> users = userRepository.findAll(pageable);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 23. What is the `Page` interface in Spring Data JPA?
The `Page` interface represents a single page of data, including the content and pagination information such as the total number of pages and elements.

Example:
```java
Page<User> users = userRepository.findAll(PageRequest.of(0, 10));
int totalPages = users.getTotalPages();
long totalElements = users.getTotalElements();
List<User> userList = users.getContent();
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 24. How do you sort results in Spring Data JPA?
Sorting in Spring Data JPA is achieved using the `Sort` class. You can pass a `Sort` object to repository methods or include it in a `Pageable` object.

Example:
```java
// Sorting by last name in ascending order
Sort sort = Sort.by("lastName").ascending();
List<User> users = userRepository.findAll(sort);

// Sorting with pagination
Pageable pageable = PageRequest.of(0, 10, Sort.by("lastName").ascending());
Page<User> usersPage = userRepository.findAll(pageable);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 25. What is a derived query method in Spring Data JPA?
Derived query methods are defined by following a naming convention. Spring Data JPA automatically generates the query based on the method name.

Example:
```java
public interface UserRepository extends JpaRepository<User, Long> {
    List<User> findByLastName(String lastName);
    List<User> findByAgeGreaterThan(int age);
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 26. What is the purpose of the `@NamedQuery` annotation in JPA?
The `@NamedQuery` annotation defines a static, reusable query that can be referenced by name. It is defined at the entity class level and executed using the `EntityManager`.

Example:
```java
@Entity
@NamedQuery(name = "User.findByLastName", query = "SELECT u FROM User u WHERE u.lastName = :lastName")
public class User {
    @Id
    private Long id;
    private String lastName;
    // getters and setters
}

// Usage
TypedQuery<User> query = entityManager.createNamedQuery("User.findByLastName", User.class);
query.setParameter("lastName", "Smith");
List<User> users = query.getResultList();
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 27. What is an entity lifecycle in JPA?

In Java Persistence API (JPA), the entity lifecycle refers to the different states an entity can go through during its existence in a persistence context. The main stages of an entity lifecycle are:

1. **New (Transient)**: The entity is created but not associated with a persistence context.
2. **Managed (Persistent)**: The entity is associated with a persistence context and synchronized with the database.
3. **Detached**: The entity is no longer associated with a persistence context but still exists in memory.
4. **Removed**: The entity is marked for removal from the database.

These stages allow JPA to manage the state transitions of entities and ensure data consistency.

#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 28. What are the different states of an entity in JPA?

The different states of an entity in JPA are:

1. **New (Transient)**: An entity is new and not yet persisted.
2. **Managed (Persistent)**: The entity is associated with an active EntityManager and synchronized with the database.
3. **Detached**: The entity is no longer associated with an EntityManager but still exists in memory.
4. **Removed**: The entity is marked for deletion and will be removed from the database upon transaction commit.

#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 29. What is the purpose of the `@PrePersist` annotation in JPA?

The `@PrePersist` annotation is used to specify a callback method that is invoked before an entity is persisted (inserted into the database). This is useful for setting default values or performing validation checks.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @PrePersist
    protected void onCreate() {
        if (this.name == null) {
            this.name = "Unknown";
        }
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 30. What is the purpose of the `@PostPersist` annotation in JPA?

The `@PostPersist` annotation specifies a callback method that is invoked after an entity has been persisted (inserted into the database). It is useful for performing actions that need to be executed after the entity is saved.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @PostPersist
    protected void onPostPersist() {
        System.out.println("User persisted with ID: " + id);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 31. What is the purpose of the `@PreUpdate` annotation in JPA?

The `@PreUpdate` annotation is used to specify a callback method that is invoked before an entity is updated in the database. This is useful for updating timestamps or performing validation checks.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @PreUpdate
    protected void onUpdate() {
        System.out.println("Updating user with ID: " + id);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 32. What is the purpose of the `@PostUpdate` annotation in JPA?

The `@PostUpdate` annotation specifies a callback method that is invoked after an entity has been updated in the database. It is useful for performing actions that need to be executed after the entity is updated.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @PostUpdate
    protected void onPostUpdate() {
        System.out.println("Updated user with ID: " + id);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 33. What is the purpose of the `@PreRemove` annotation in JPA?

The `@PreRemove` annotation is used to specify a callback method that is invoked before an entity is removed from the database. This is useful for performing cleanup operations or logging.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @PreRemove
    protected void onRemove() {
        System.out.println("Removing user with ID: " + id);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 34. What is the purpose of the `@PostRemove` annotation in JPA?

The `@PostRemove` annotation specifies a callback method that is invoked after an entity has been removed from the database. It is useful for performing actions that need to be executed after the entity is deleted.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @PostRemove
    protected void onPostRemove() {
        System.out.println("Removed user with ID: " + id);
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

### 35. What is the purpose of the `@PostLoad` annotation in JPA?

The `@PostLoad` annotation specifies a callback method that is invoked after an entity has been loaded from the database. It is useful for initializing transient fields or performing additional setup.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @Transient
    private String displayName;

    @PostLoad
    protected void onLoad() {
        this.displayName = "User: " + name;
    }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-easy)**
---

# Spring Data JPA Medium Interview Questions and Answers
### 36. Explain the different types of primary key generation strategies in JPA.

JPA provides several strategies for generating primary keys for entities. These strategies are specified using the `@GeneratedValue` annotation along with the `GenerationType` enumeration. The primary key generation strategies are:

1. **AUTO**: JPA automatically selects the appropriate strategy for the database. This is the default strategy.
   
   ```java
   @Entity
   public class User {
       @Id
       @GeneratedValue(strategy = GenerationType.AUTO)
       private Long id;
   }
   ```

2. **IDENTITY**: The primary key is generated by the database using an auto-increment column.
   
   ```java
   @Entity
   public class User {
       @Id
       @GeneratedValue(strategy = GenerationType.IDENTITY)
       private Long id;
   }
   ```

3. **SEQUENCE**: The primary key is generated using a database sequence.
   
   ```java
   @Entity
   public class User {
       @Id
       @GeneratedValue(strategy = GenerationType.SEQUENCE, generator = "user_seq")
       @SequenceGenerator(name = "user_seq", sequenceName = "user_sequence", allocationSize = 1)
       private Long id;
   }
   ```

4. **TABLE**: The primary key is generated using a table to maintain the sequence values.
   
   ```java
   @Entity
   public class User {
       @Id
       @GeneratedValue(strategy = GenerationType.TABLE, generator = "user_table")
       @TableGenerator(name = "user_table", table = "id_gen", pkColumnName = "gen_name", valueColumnName = "gen_value", allocationSize = 1)
       private Long id;
   }
   ```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 37. What is the difference between `@OneToMany` and `@ManyToMany` relationships in JPA?

1. **@OneToMany**: This annotation defines a one-to-many relationship between two entities, where one entity (the parent) can have multiple instances of the other entity (the child).

   ```java
   @Entity
   public class Department {
       @Id
       @GeneratedValue(strategy = GenerationType.IDENTITY)
       private Long id;

       @OneToMany(mappedBy = "department")
       private List<Employee> employees;
   }

   @Entity
   public class Employee {
       @Id
       @GeneratedValue(strategy = GenerationType.IDENTITY)
       private Long id;

       @ManyToOne
       @JoinColumn(name = "department_id")
       private Department department;
   }
   ```

2. **@ManyToMany**: This annotation defines a many-to-many relationship between two entities, where multiple instances of one entity can be associated with multiple instances of the other entity.

   ```java
   @Entity
   public class Student {
       @Id
       @GeneratedValue(strategy = GenerationType.IDENTITY)
       private Long id;

       @ManyToMany
       @JoinTable(
           name = "student_course",
           joinColumns = @JoinColumn(name = "student_id"),
           inverseJoinColumns = @JoinColumn(name = "course_id")
       )
       private List<Course> courses;
   }

   @Entity
   public class Course {
       @Id
       @GeneratedValue(strategy = GenerationType.IDENTITY)
       private Long id;

       @ManyToMany(mappedBy = "courses")
       private List<Student> students;
   }
   ```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 38. How do you handle bi-directional relationships in JPA?

Bi-directional relationships involve two entities that reference each other. To handle bi-directional relationships, you use the `@MappedBy` attribute to specify the owning side and the inverse side of the relationship.

```java
@Entity
public class Department {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @OneToMany(mappedBy = "department")
    private List<Employee> employees;
}

@Entity
public class Employee {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @ManyToOne
    @JoinColumn(name = "department_id")
    private Department department;
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 39. What is the `@MappedBy` attribute used for in JPA?

The `@MappedBy` attribute is used in bi-directional relationships to specify the field that owns the relationship. It is used on the inverse side of the relationship to indicate that the relationship is managed by the other side.

```java
@Entity
public class Department {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @OneToMany(mappedBy = "department")
    private List<Employee> employees;
}

@Entity
public class Employee {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @ManyToOne
    @JoinColumn(name = "department_id")
    private Department department;
}
```

In this example, the `Department` entity has a `@OneToMany` relationship with the `Employee` entity, and the `Employee` entity has a `@ManyToOne` relationship with the `Department` entity. The `mappedBy` attribute on the `Department` entity specifies that the `department` field in the `Employee` entity owns the relationship.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 40. What is the purpose of the `@ElementCollection` annotation in JPA?

The `@ElementCollection` annotation is used to define a collection of basic or embeddable types. This allows you to map collections of non-entity types such as `String`, `Integer`, or custom embeddable types.

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @ElementCollection
    @CollectionTable(name = "user_phone_numbers", joinColumns = @JoinColumn(name = "user_id"))
    @Column(name = "phone_number")
    private List<String> phoneNumbers;
}
```

In this example, the `User` entity has a collection of phone numbers, which are stored in a separate table `user_phone_numbers`.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 41. How do you handle composite keys in JPA?

JPA provides two ways to handle composite keys:

1. **Using `@EmbeddedId`**: This annotation is used to specify a composite primary key class that is embedded in the entity.

    ```java
    @Embeddable
    public class UserId implements Serializable {
        private Long userId;
        private Long departmentId;

        // getters, setters, equals, and hashCode
    }

    @Entity
    public class User {
        @EmbeddedId
        private UserId id;

        private String name;
    }
    ```

2. **Using `@IdClass`**: This annotation is used to specify a separate primary key class.

    ```java
    @IdClass(UserId.class)
    @Entity
    public class User {
        @Id
        private Long userId;

        @Id
        private Long departmentId;

        private String name;
    }

    public class UserId implements Serializable {
        private Long userId;
        private Long departmentId;

        // getters, setters, equals, and hashCode
    }
    ```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 42. What is the `@Embeddable` annotation used for in JPA?

The `@Embeddable` annotation is used to specify a class whose instances are stored as an intrinsic part of an owning entity and share the identity of the entity. The fields of the embeddable class are mapped to the table of the owning entity.

```java
@Embeddable
public class Address {
    private String street;
    private String city;
    private String state;
    private String zipCode;

    // getters and setters
}

@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @Embedded
    private Address address;
}
```

In this example, the `Address` class is marked as `@Embeddable`, and an instance of `Address` is embedded in the `User` entity.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 43. What is the purpose of the `@EmbeddedId` annotation in JPA?

The `@EmbeddedId` annotation is used to specify a composite primary key class that is embedded in the entity. The composite primary key class must be annotated with `@Embeddable`.

```java
@Embeddable
public class UserId implements Serializable {
    private Long userId;
    private Long departmentId;

    // getters, setters, equals, and hashCode
}

@Entity
public class User {
    @EmbeddedId
    private UserId id;

    private String name;
}
```

In this example, the `UserId` class is marked as `@Embeddable`, and an instance of `UserId` is used as the primary key for the `User` entity.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 44. What is the role of the `@Inheritance` annotation in JPA?

The `@Inheritance` annotation is used to define the inheritance strategy for entity inheritance hierarchies. This annotation is applied to the root entity class of the inheritance hierarchy. The available strategies are:

1. **SINGLE_TABLE**: All entities in the hierarchy are mapped to a single table.
2. **TABLE_PER_CLASS**: Each entity in the hierarchy is mapped to its own table.
3. **JOINED**: Each entity in the hierarchy is mapped to its own table, and the tables are joined using foreign keys.

```java
@Entity
@Inheritance(strategy = InheritanceType.SINGLE_TABLE)
@DiscriminatorColumn(name = "type")
public abstract class Vehicle {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
}

@Entity
@DiscriminatorValue("CAR")
public class Car extends Vehicle {
    private int numberOfDoors;
}

@Entity
@DiscriminatorValue("TRUCK")
public class Truck extends Vehicle {
    private int payloadCapacity;
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

In this example, the `Vehicle` class is the root entity, and the inheritance strategy is `SINGLE_TABLE`.

### 45. Explain the different inheritance strategies in JPA.

JPA provides three inheritance strategies to map an inheritance hierarchy to the database:

1. **SINGLE_TABLE**: All classes in the hierarchy are mapped to a single table with a discriminator column to distinguish between entity types.

    ```java
    @Entity
    @Inheritance(strategy = InheritanceType.SINGLE_TABLE)
    @DiscriminatorColumn(name = "type")
    public abstract class Vehicle {
        @Id
        @GeneratedValue(strategy = GenerationType.IDENTITY)
        private Long id;
        
        private String name;
    }

    @Entity
    @DiscriminatorValue("CAR")
    public class Car extends Vehicle {
        private int numberOfDoors;
    }

    @Entity
    @DiscriminatorValue("TRUCK")
    public class Truck extends Vehicle {
        private int payloadCapacity;
    }
    ```

2. **TABLE_PER_CLASS**: Each class in the hierarchy is mapped to its own table. Each table contains all the fields of the entity, including inherited fields.

    ```java
    @Entity
    @Inheritance(strategy = InheritanceType.TABLE_PER_CLASS)
    public abstract class Vehicle {
        @Id
        @GeneratedValue(strategy = GenerationType.IDENTITY)
        private Long id;
        
        private String name;
    }

    @Entity
    public class Car extends Vehicle {
        private int numberOfDoors;
    }

    @Entity
    public class Truck extends Vehicle {
        private int payloadCapacity;
    }
    ```

3. **JOINED**: Each class in the hierarchy is mapped to its own table, and the tables are joined using foreign keys.

    ```java
    @Entity
    @Inheritance(strategy = InheritanceType.JOINED)
    public abstract class Vehicle {
        @Id
        @GeneratedValue(strategy = GenerationType.IDENTITY)
        private Long id;
        
        private String name;
    }

    @Entity
    public class Car extends Vehicle {
        private int numberOfDoors;
    }

    @Entity
    public class Truck extends Vehicle {
        private int payloadCapacity;
    }
    ```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 46. What is the purpose of the `@DiscriminatorColumn` annotation in JPA?

The `@DiscriminatorColumn` annotation is used in conjunction with the `SINGLE_TABLE` and `JOINED` inheritance strategies to specify the discriminator column that will be used to distinguish between different entity types in the same table.

```java
@Entity
@Inheritance(strategy = InheritanceType.SINGLE_TABLE)
@DiscriminatorColumn(name = "type")
public abstract class Vehicle {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    
    private String name;
}

@Entity
@DiscriminatorValue("CAR")
public class Car extends Vehicle {
    private int numberOfDoors;
}

@Entity
@DiscriminatorValue("TRUCK")
public class Truck extends Vehicle {
    private int payloadCapacity;
}
```

In this example, the `@DiscriminatorColumn` annotation specifies that the `type` column will be used to distinguish between `Car` and `Truck` entities.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 47. What is the purpose of the `@DiscriminatorValue` annotation in JPA?

The `@DiscriminatorValue` annotation is used in conjunction with the `@DiscriminatorColumn` annotation to specify the value that will be stored in the discriminator column for a particular entity type.

```java
@Entity
@Inheritance(strategy = InheritanceType.SINGLE_TABLE)
@DiscriminatorColumn(name = "type")
public abstract class Vehicle {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    
    private String name;
}

@Entity
@DiscriminatorValue("CAR")
public class Car extends Vehicle {
    private int numberOfDoors;
}

@Entity
@DiscriminatorValue("TRUCK")
public class Truck extends Vehicle {
    private int payloadCapacity;
}
```

In this example, the `@DiscriminatorValue` annotation specifies that the value `CAR` will be stored in the `type` column for `Car` entities, and the value `TRUCK` will be stored for `Truck` entities.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 48. What is the purpose of the `@SecondaryTable` annotation in JPA?

The `@SecondaryTable` annotation is used to map an entity to multiple tables. This allows you to split the entity's attributes across multiple tables.

```java
@Entity
@SecondaryTable(name = "user_details", pkJoinColumns = @PrimaryKeyJoinColumn(name = "user_id"))
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @Column(table = "user_details")
    private String address;

    @Column(table = "user_details")
    private String phoneNumber;
}
```

In this example, the `User` entity's `id` and `name` are stored in the `User` table, while `address` and `phoneNumber` are stored in the `user_details` table.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 49. How do you define a native query in Spring Data JPA?

In Spring Data JPA, you can define a native query using the `@Query` annotation with the `nativeQuery` attribute set to `true`.

```java
public interface UserRepository extends JpaRepository<User, Long> {
    @Query(value = "SELECT * FROM user WHERE name = ?1", nativeQuery = true)
    List<User> findByName(String name);
}
```

In this example, the `findByName` method uses a native SQL query to find users by their name.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 50. What is the purpose of the `@NamedNativeQuery` annotation in JPA?

The `@NamedNativeQuery` annotation is used to define a named native SQL query at the entity level. This allows you to reuse the query across multiple methods.

```java
@Entity
@NamedNativeQuery(
    name = "User.findByName",
    query = "SELECT * FROM user WHERE name = ?",
    resultClass = User.class
)
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
}
```

```java
public interface UserRepository extends JpaRepository<User, Long> {
    @Query(name = "User.findByName")
    List<User> findByName(String name);
}
```

In this example, the `User.findByName` named native query is defined at the entity level and used in the repository.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 51. How do you handle optimistic locking in JPA?

Optimistic locking in JPA is a mechanism used to ensure that data integrity is maintained during concurrent data access. It relies on versioning to detect conflicts and prevent lost updates. This is useful when there are multiple transactions that might update the same record concurrently.

#### Example:

To implement optimistic locking, you need to use the `@Version` annotation in your JPA entity class:

```java
@Entity
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
    private Double price;

    @Version
    private Long version;

    // getters and setters
}
```

In the above example, the `version` field will be automatically incremented by the JPA provider each time the entity is updated. When a transaction attempts to update an entity, the JPA provider checks the current version against the version in the database. If they don't match, an `OptimisticLockException` is thrown, indicating that another transaction has modified the entity.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 52. What is the purpose of the `@Version` annotation in JPA?

The `@Version` annotation is used to implement optimistic locking in JPA. It specifies the field in the entity that will be used for version control. The version field is automatically managed by the JPA provider and is incremented each time the entity is updated. This helps to detect concurrent modifications and prevent lost updates.

#### Example:

```java
@Entity
public class Employee {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
    private String department;

    @Version
    private Integer version;

    // getters and setters
}
```

In this example, the `version` field will be used to manage the version of the `Employee` entity and will be incremented with each update.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 53. How do you handle pessimistic locking in JPA?

Pessimistic locking in JPA is used to prevent concurrent transactions from modifying the same data simultaneously. This is achieved by locking the database rows that are being read or updated. Pessimistic locking can be implemented using `LockModeType.PESSIMISTIC_READ` or `LockModeType.PESSIMISTIC_WRITE`.

#### Example:

```java
EntityManager entityManager = entityManagerFactory.createEntityManager();
entityManager.getTransaction().begin();

Product product = entityManager.find(Product.class, 1L, LockModeType.PESSIMISTIC_WRITE);
product.setPrice(product.getPrice() + 10);

entityManager.getTransaction().commit();
entityManager.close();
```

In this example, the `Product` entity with ID 1 is locked using `LockModeType.PESSIMISTIC_WRITE`, which means no other transaction can read or write to this row until the current transaction is committed.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 54. What is the `EntityGraph` in JPA and how is it used?

`EntityGraph` in JPA is a mechanism to define and customize the graph of entities that should be fetched from the database. It allows you to specify which related entities should be loaded eagerly. This can help optimize the performance by reducing the number of SQL queries.

#### Example:

```java
@Entity
@NamedEntityGraph(name = "Product.detail",
        attributeNodes = @NamedAttributeNode("category"))
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
    private Double price;

    @ManyToOne(fetch = FetchType.LAZY)
    private Category category;

    // getters and setters
}
```

To use the defined `EntityGraph`:

```java
EntityManager entityManager = entityManagerFactory.createEntityManager();
EntityGraph<?> graph = entityManager.getEntityGraph("Product.detail");

Map<String, Object> properties = new HashMap<>();
properties.put("javax.persistence.fetchgraph", graph);

Product product = entityManager.find(Product.class, 1L, properties);
```

In this example, the `Product` entity and its `category` relationship are fetched eagerly using the `Product.detail` entity graph.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 55. What are the different types of fetching strategies in JPA?

JPA defines two fetching strategies:

1. **Eager Loading**: Entities and their relationships are loaded immediately.
2. **Lazy Loading**: Entities and their relationships are loaded on-demand, i.e., when they are accessed for the first time.

#### Example:

```java
@Entity
public class Order {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @OneToMany(fetch = FetchType.LAZY, mappedBy = "order")
    private List<OrderItem> items;

    // getters and setters
}
```

In this example, the `items` collection in the `Order` entity will be loaded lazily, meaning it will be fetched from the database only when accessed.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 56. What is the difference between eager and lazy loading in JPA?

**Eager Loading**:
- Loads related entities immediately.
- Uses `FetchType.EAGER`.

**Lazy Loading**:
- Loads related entities on demand.
- Uses `FetchType.LAZY`.

#### Example:

```java
@Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @OneToMany(fetch = FetchType.EAGER, mappedBy = "user")
    private List<Post> posts;

    @OneToMany(fetch = FetchType.LAZY, mappedBy = "user")
    private List<Comment> comments;

    // getters and setters
}
```

In this example, the `posts` collection will be loaded eagerly while the `comments` collection will be loaded lazily.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 57. How do you handle batch processing in Spring Data JPA?

Batch processing in Spring Data JPA can be handled using the `JpaItemWriter` and `JpaItemReader` components provided by Spring Batch. Batch processing involves reading a large set of data, processing it, and writing the results in bulk to improve performance.

#### Example:

```java
@Bean
public JpaItemWriter<Product> writer(EntityManagerFactory entityManagerFactory) {
    JpaItemWriter<Product> writer = new JpaItemWriter<>();
    writer.setEntityManagerFactory(entityManagerFactory);
    return writer;
}

@Bean
public JpaItemReader<Product> reader(EntityManagerFactory entityManagerFactory) {
    JpaItemReader<Product> reader = new JpaItemReader<>();
    reader.setQueryString("SELECT p FROM Product p");
    reader.setEntityManagerFactory(entityManagerFactory);
    return reader;
}

@Bean
public Step step1(StepBuilderFactory stepBuilderFactory, JpaItemReader<Product> reader, JpaItemWriter<Product> writer) {
    return stepBuilderFactory.get("step1")
            .<Product, Product>chunk(10)
            .reader(reader)
            .writer(writer)
            .build();
}
```

In this example, the `JpaItemReader` reads data from the `Product` entity, and the `JpaItemWriter` writes the processed data back to the database in chunks of 10.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 58. What is the purpose of the `@BatchSize` annotation in JPA?

The `@BatchSize` annotation in JPA is used to specify the size of the batch when fetching collections or instances of entities. This helps optimize performance by reducing the number of SQL queries executed.

#### Example:

```java
@Entity
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
    private Double price;

    @OneToMany(mappedBy = "product")
    @BatchSize(size = 10)
    private List<Review> reviews;

    // getters and setters
}
```

In this example, the `reviews` collection will be fetched in batches of 10.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 59. How do you handle native SQL queries in Spring Data JPA?

Native SQL queries in Spring Data JPA can be handled using the `@Query` annotation with the `nativeQuery` attribute set to `true`.

#### Example:

```java
public interface ProductRepository extends JpaRepository<Product, Long> {
    @Query(value = "SELECT * FROM products WHERE price > ?1", nativeQuery = true)
    List<Product> findProductsByPriceGreaterThan(Double price);
}
```

In this example, a native SQL query is used to fetch products with a price greater than a specified value.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 60. What is the purpose of the `@SqlResultSetMapping` annotation in JPA?

The `@SqlResultSetMapping` annotation is used to map the result set of a native SQL query to a JPA entity or a DTO (Data Transfer Object).

#### Example:

```java
@SqlResultSetMapping(
    name = "ProductMapping",
    entities = @EntityResult(
        entityClass = Product.class,
        fields = {
            @FieldResult(name = "id", column = "id"),
            @FieldResult(name = "name", column = "name"),
            @FieldResult(name = "price", column = "price")
        }
    )
)
@Entity
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;
    private Double price;

    // getters and setters
}
```

To use the mapping:

```java
@Entity
@NamedNativeQuery(
    name = "findProducts",
    query = "SELECT id, name, price FROM products",
    resultSetMapping = "ProductMapping"
)
public class Product {
    // fields, getters, and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 61. How do you handle auditing in Spring Data JPA?

Auditing in Spring Data JPA involves automatically populating fields such as created date, last modified date, created by, and last modified by. This is achieved using annotations like `@CreatedDate`, `@LastModifiedDate`, `@CreatedBy`, and `@LastModifiedBy`.

#### Example:

```java
@Configuration
@EnableJpaAuditing
public class JpaConfig {
}

@EntityListeners(AuditingEntityListener.class)
@Entity
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @CreatedDate
    private LocalDateTime createdDate;

    @LastModifiedDate
    private LocalDateTime lastModifiedDate;

    @CreatedBy
    private String createdBy;

    @LastModifiedBy
    private String lastModifiedBy;

    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 62. What is the purpose of the `@CreatedDate` annotation in JPA?

The `@CreatedDate` annotation is used to automatically populate the creation date of an entity when it is persisted. It works in conjunction with Spring Data JPA's auditing feature.

#### Example:

```java
@Entity
@EntityListeners(AuditingEntityListener.class)
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @CreatedDate
    private LocalDateTime createdDate;

    // getters and setters
}
```

In this example, the `createdDate` field will be automatically populated with the current date and time when the `Product` entity is created.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 63. What is the purpose of the `@LastModifiedDate` annotation in JPA?

The `@LastModifiedDate` annotation is used to automatically populate the last modified date of an entity when it is updated. It is part of Spring Data JPA's auditing feature.

#### Example:

```java
@Entity
@EntityListeners(AuditingEntityListener.class)
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @LastModifiedDate
    private LocalDateTime lastModifiedDate;

    // getters and setters
}
```

In this example, the `lastModifiedDate` field will be automatically updated with the current date and time whenever the `Product` entity is updated.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 64. What is the purpose of the `@CreatedBy` annotation in JPA?

The `@CreatedBy` annotation is used to automatically populate the field that stores the user who created the entity. It works in conjunction with Spring Data JPA's auditing feature.

#### Example:

```java
@Entity
@EntityListeners(AuditingEntityListener.class)
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @CreatedBy
    private String createdBy;

    // getters and setters
}
```

In this example, the `createdBy` field will be automatically populated with the username of the user who created the `Product` entity.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

### 65. What is the purpose of the `@LastModifiedBy` annotation in JPA?

The `@LastModifiedBy` annotation is used to automatically populate the field that stores the user who last modified the entity. It is part of Spring Data JPA's auditing feature.

#### Example:

```java
@Entity
@EntityListeners(AuditingEntityListener.class)
public class Product {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @LastModifiedBy
    private String lastModifiedBy;

    // getters and setters
}
```

In this example, the `lastModifiedBy` field will be automatically updated with the username of the user who last modified the `Product` entity.

#### **[⬆ Back to Top](#level--spring-data-jpa-medium)**
---

# Spring Data JPA Medium Interview Questions and Answers
### 66. Explain the concept of entity graph in JPA and how it can be used to optimize performance.

Entity graphs in JPA are a way to define which related entities should be loaded along with a given entity. This can optimize performance by reducing the number of database queries required to fetch related data. Entity graphs can be defined statically using annotations or dynamically at runtime.

**Static Entity Graph:**

```java
@Entity
@NamedEntityGraph(
  name = "author-books-entity-graph",
  attributeNodes = {
    @NamedAttributeNode("books")
  }
)
public class Author {
  @Id
  private Long id;
  
  private String name;
  
  @OneToMany(mappedBy = "author")
  private List<Book> books;
  
  // Getters and setters
}
```

**Dynamic Entity Graph:**

```java
EntityManager em = ...;
EntityGraph<Author> graph = em.createEntityGraph(Author.class);
graph.addAttributeNodes("books");

Map<String, Object> properties = new HashMap<>();
properties.put("javax.persistence.fetchgraph", graph);

Author author = em.find(Author.class, authorId, properties);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 67. How do you handle dynamic queries in Spring Data JPA?

Dynamic queries in Spring Data JPA can be handled using several approaches including the `@Query` annotation, `Querydsl`, and the `Criteria API`.

**Using `@Query` annotation:**

```java
public interface UserRepository extends JpaRepository<User, Long> {
  
  @Query("SELECT u FROM User u WHERE u.name = ?1")
  List<User> findByName(String name);
}
```

**Using `Specification` interface:**

```java
public class UserSpecification implements Specification<User> {

  private String name;

  public UserSpecification(String name) {
    this.name = name;
  }

  @Override
  public Predicate toPredicate(Root<User> root, CriteriaQuery<?> query, CriteriaBuilder criteriaBuilder) {
    if (name == null) {
      return criteriaBuilder.isTrue(criteriaBuilder.literal(true)); // always true
    }
    return criteriaBuilder.equal(root.get("name"), this.name);
  }
}
```

**Using `Querydsl`:**

```java
public interface UserRepository extends JpaRepository<User, Long>, QuerydslPredicateExecutor<User> {
}

// Usage
QUser user = QUser.user;
Predicate predicate = user.name.eq("John");
repository.findAll(predicate);
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 68. What is the role of the `Criteria API` in JPA?

The `Criteria API` in JPA is used to create dynamic, type-safe queries. It allows developers to build queries programmatically rather than using JPQL strings. This approach ensures compile-time checking of the queries.

**Example:**

```java
CriteriaBuilder cb = entityManager.getCriteriaBuilder();
CriteriaQuery<User> cq = cb.createQuery(User.class);
Root<User> user = cq.from(User.class);
cq.select(user).where(cb.equal(user.get("name"), "John"));

TypedQuery<User> query = entityManager.createQuery(cq);
List<User> results = query.getResultList();
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 69. How do you use the `Criteria API` to create dynamic queries in JPA?

To create dynamic queries using the `Criteria API`, you build the query programmatically using various criteria and conditions based on your requirements.

**Example:**

```java
CriteriaBuilder cb = entityManager.getCriteriaBuilder();
CriteriaQuery<User> cq = cb.createQuery(User.class);
Root<User> user = cq.from(User.class);

List<Predicate> predicates = new ArrayList<>();
if (name != null) {
  predicates.add(cb.equal(user.get("name"), name));
}
if (age != null) {
  predicates.add(cb.equal(user.get("age"), age));
}

cq.where(predicates.toArray(new Predicate[0]));

TypedQuery<User> query = entityManager.createQuery(cq);
List<User> results = query.getResultList();
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 70. What is the purpose of the `Specification` interface in Spring Data JPA?

The `Specification` interface in Spring Data JPA is used to create dynamic queries. It provides a way to encapsulate the query logic and allows for combining multiple specifications using logical operators.

**Example:**

```java
public class UserSpecification implements Specification<User> {

  private String name;

  public UserSpecification(String name) {
    this.name = name;
  }

  @Override
  public Predicate toPredicate(Root<User> root, CriteriaQuery<?> query, CriteriaBuilder criteriaBuilder) {
    if (name == null) {
      return criteriaBuilder.isTrue(criteriaBuilder.literal(true)); // always true
    }
    return criteriaBuilder.equal(root.get("name"), this.name);
  }
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 71. How do you use the `Specification` interface to create dynamic queries in JPA?

To use the `Specification` interface for creating dynamic queries, you implement the interface and override the `toPredicate` method. You can then combine different specifications using logical operators.

**Example:**

```java
public interface UserRepository extends JpaRepository<User, Long>, JpaSpecificationExecutor<User> {
}

// Usage
Specification<User> nameSpec = new UserSpecification("John");
Specification<User> ageSpec = (root, query, cb) -> cb.equal(root.get("age"), 30);

List<User> users = userRepository.findAll(Specification.where(nameSpec).and(ageSpec));
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 72. What is the purpose of the `@Cacheable` annotation in JPA?

The `@Cacheable` annotation in JPA is used to mark an entity as cacheable. This means that the entity will be stored in the second-level cache, which can improve performance by reducing the number of database queries.

**Example:**

```java
@Entity
@Cacheable
public class User {
  @Id
  private Long id;
  
  private String name;
  
  // Getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 73. How do you configure second-level cache in JPA?

To configure the second-level cache in JPA, you need to set up a cache provider (e.g., Ehcache or Hazelcast) and then enable caching in your JPA configuration.

**Ehcache Configuration:**

1. Add dependencies:

```xml
<dependency>
  <groupId>org.hibernate</groupId>
  <artifactId>hibernate-ehcache</artifactId>
  <version>5.3.6.Final</version>
</dependency>
<dependency>
  <groupId>org.ehcache</groupId>
  <artifactId>ehcache</artifactId>
  <version>3.8.1</version>
</dependency>
```

2. Configure the cache provider in `persistence.xml`:

```xml
<property name="hibernate.cache.region.factory_class" value="org.hibernate.cache.jcache.JCacheRegionFactory"/>
<property name="hibernate.javax.cache.provider" value="org.ehcache.jsr107.EhcacheCachingProvider"/>
<property name="hibernate.javax.cache.uri" value="/ehcache.xml"/>
```

3. Define `ehcache.xml`:

```xml
<config xmlns:xsi='http://www.w3.org/2001/XMLSchema-instance'
        xmlns='http://www.ehcache.org/v3'>
    <cache alias="user">
        <key-type>java.lang.Long</key-type>
        <value-type>com.example.User</value-type>
        <expiry>
            <ttl unit="seconds">60</ttl>
        </expiry>
        <resources>
            <heap unit="entries">100</heap>
            <offheap unit="mb">10</offheap>
        </resources>
    </cache>
</config>
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 74. What is the difference between first-level and second-level cache in JPA?

| Feature              | First-Level Cache                                      | Second-Level Cache                                      |
|----------------------|-------------------------------------------------------|--------------------------------------------------------|
| Scope                | Entity Manager (transactional)                        | Session Factory (shared across sessions)               |
| Default              | Enabled by default                                     | Requires explicit configuration                         |
| Lifetime             | Lifetime of the EntityManager                         | Configurable lifetime (e.g., time-to-live)              |
| Usage                | Specific to a particular EntityManager session         | Shared across multiple EntityManager sessions           |
| Implementation       | Part of JPA specification                             | Part of the JPA provider (e.g., Hibernate)              |

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 75. Explain the concept of dirty checking in JPA and how it works.

Dirty checking in JPA is a mechanism that automatically detects changes made to persistent entities and synchronizes them with the database. When an entity is modified, JPA keeps track of the original state and the new state. During the transaction commit, it compares the two states and updates the database accordingly.

**Example:**

```java
@Entity
public class User {
  @Id
  private Long id;
  
  private String name;
  
  // Getters and setters
}

// Usage
EntityManager em = ...;
em.getTransaction().begin();

User user = em.find(User.class, 1L);
user.setName("New Name");

em.getTransaction().commit(); // Dirty checking triggers update query
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 76. Explain the concept of cascade types in JPA and how they affect entity relationships.

Cascade types in JPA define the actions that should be propagated from a parent entity to its associated child entities. This helps in managing the lifecycle of related entities.

**Cascade Types:**

- `PERSIST`: Propagate persist operation
- `MERGE`: Propagate merge operation
- `REMOVE`: Propagate remove operation
- `REFRESH`: Propagate refresh operation
- `DETACH`: Propagate detach operation
- `ALL`: Propagate all operations

**Example:**

```java
@Entity
public class Author {
  @Id
  private Long id;
  
  private String name;
  
  @OneToMany(mappedBy = "author", cascade = CascadeType.ALL)
  private List<Book> books;
  
  // Getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 77. What are the different cascade types available in JPA and when would you use each?

| Cascade Type      | Description                                                                                                  | Usage Scenario                                                                                 |
|-------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| `PERSIST`         | Propagates persist operation to child entities                                                               | When saving a new entity along with its related entities                                       |
| `MERGE`           | Propagates merge operation to child entities                                                                 | When updating an entity along with its related entities                                        |
| `REMOVE`          | Propagates remove operation to child entities                                                                | When deleting an entity along with its related entities                                        |
| `REFRESH`         | Propagates refresh operation to child entities                                                               | When reloading an entity along with its related entities from the database                     |
| `DETACH`          | Propagates detach operation to child entities                                                                | When detaching an entity along with its related entities from the persistence context          |
| `ALL`             | Propagates all operations (persist, merge, remove, refresh, detach)                                          | When you want all operations to be cascaded to the related entities                            |

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 78. How do you handle orphan removal in JPA and what is the purpose of the `@OneToMany(orphanRemoval = true)` annotation?

Orphan removal in JPA is used to automatically delete child entities when they are removed from the parent entity's collection. This ensures that there are no orphaned records in the database.

**Example:**

```java
@Entity
public class Author {
  @Id
  private Long id;
  
  private String name;
  
  @OneToMany(mappedBy = "author", orphanRemoval = true)
  private List<Book> books;
  
  // Getters and setters
}

// Usage
Author author = em.find(Author.class, authorId);
author.getBooks().remove(0); // The removed book will be deleted from the database
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 79. What are the different types of entity graphs (attribute node, subgraph) in JPA and how are they used?

Entity graphs in JPA can be composed of attribute nodes and subgraphs. Attribute nodes specify which attributes to fetch, while subgraphs define nested entity graphs for related entities.

**Attribute Node:**

```java
@NamedEntityGraph(
  name = "author-books-entity-graph",
  attributeNodes = {
    @NamedAttributeNode("books")
  }
)
@Entity
public class Author {
  @Id
  private Long id;
  
  private String name;
  
  @OneToMany(mappedBy = "author")
  private List<Book> books;
  
  // Getters and setters
}
```

**Subgraph:**

```java
@NamedEntityGraph(
  name = "author-books-publisher-entity-graph",
  attributeNodes = {
    @NamedAttributeNode(value = "books", subgraph = "books-subgraph")
  },
  subgraphs = {
    @NamedSubgraph(
      name = "books-subgraph",
      attributeNodes = {
        @NamedAttributeNode("publisher")
      }
    )
  }
)
@Entity
public class Author {
  @Id
  private Long id;
  
  private String name;
  
  @OneToMany(mappedBy = "author")
  private List<Book> books;
  
  // Getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 80. How do you optimize performance using Fetch Joins in JPQL?

Fetch joins in JPQL are used to fetch related entities along with the main entity in a single query, reducing the number of database queries and improving performance.

**Example:**

```java
// JPQL Query
String jpql = "SELECT a FROM Author a JOIN FETCH a.books WHERE a.id = :id";
TypedQuery<Author> query = em.createQuery(jpql, Author.class);
query.setParameter("id", authorId);

Author author = query.getSingleResult();
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 81. What is the N+1 select problem in JPA and how can it be mitigated?

#### The N+1 Select Problem

The N+1 select problem occurs when an application executes N+1 database queries to retrieve data that could have been fetched with a single query. This problem is common in JPA when dealing with lazy-loaded associations.

For instance, consider an entity `Author` with a `OneToMany` relationship to `Book`:

```java
@Entity
public class Author {
    @Id
    private Long id;
    
    @OneToMany(mappedBy = "author", fetch = FetchType.LAZY)
    private List<Book> books;
    
    // getters and setters
}

@Entity
public class Book {
    @Id
    private Long id;
    
    @ManyToOne
    private Author author;
    
    // getters and setters
}
```

Fetching a list of authors and their books might look like this:

```java
List<Author> authors = em.createQuery("SELECT a FROM Author a", Author.class).getResultList();
for (Author author : authors) {
    System.out.println(author.getBooks());
}
```

This code will execute one query to fetch all authors and N additional queries to fetch books for each author, leading to performance issues.

#### Mitigation Strategies

1. **Using `JOIN FETCH`**

   Modify the query to fetch authors and their books in a single query:

   ```java
   List<Author> authors = em.createQuery(
       "SELECT a FROM Author a JOIN FETCH a.books", Author.class).getResultList();
   ```

2. **Entity Graphs**

   Define an entity graph to specify the associations to be fetched eagerly:

   ```java
   @NamedEntityGraph(name = "author-books-graph",
       attributeNodes = @NamedAttributeNode("books"))
   @Entity
   public class Author {
       // ...
   }

   EntityGraph<?> entityGraph = em.getEntityGraph("author-books-graph");
   List<Author> authors = em.createQuery("SELECT a FROM Author a", Author.class)
       .setHint("javax.persistence.loadgraph", entityGraph)
       .getResultList();
   ```

3. **Batch Fetching**

   Configure batch fetching in the JPA provider (e.g., Hibernate):

   ```java
   @Entity
   @BatchSize(size = 10)
   public class Author {
       // ...
   }
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 82. Explain the purpose of the `@EntityListeners` annotation and how it is used in auditing.

#### Purpose of `@EntityListeners`

The `@EntityListeners` annotation is used to specify callback listeners for an entity. These listeners can intercept entity lifecycle events such as pre-persist, post-persist, pre-update, post-update, pre-remove, and post-remove. This is particularly useful for auditing purposes.

#### Usage in Auditing

To implement auditing, define a listener class that handles the lifecycle events:

```java
public class AuditListener {

    @PrePersist
    public void prePersist(Object object) {
        if (object instanceof Auditable) {
            Auditable auditable = (Auditable) object;
            Audit audit = auditable.getAudit();
            audit.setCreatedDate(new Date());
            // Set other audit fields as needed
        }
    }

    @PreUpdate
    public void preUpdate(Object object) {
        if (object instanceof Auditable) {
            Auditable auditable = (Auditable) object;
            Audit audit = auditable.getAudit();
            audit.setLastModifiedDate(new Date());
            // Set other audit fields as needed
        }
    }
}
```

Annotate the entity with `@EntityListeners` and implement an `Auditable` interface:

```java
@Entity
@EntityListeners(AuditListener.class)
public class SomeEntity implements Auditable {

    @Embedded
    private Audit audit = new Audit();

    // getters and setters for audit
}

@Embeddable
public class Audit {

    private Date createdDate;
    private Date lastModifiedDate;
    // other audit fields

    // getters and setters
}

public interface Auditable {
    Audit getAudit();
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 83. How do you handle multi-tenancy in JPA and what are the different strategies available?

#### Multi-Tenancy Strategies

1. **Database per Tenant**

   Each tenant has its own database. The application switches between databases based on the tenant context.

   ```java
   @Bean
   public DataSource dataSource(TenantContext tenantContext) {
       return DataSourceBuilder.create()
           .url("jdbc:mysql://localhost:3306/" + tenantContext.getTenantId())
           .username("user")
           .password("password")
           .build();
   }
   ```

2. **Schema per Tenant**

   Each tenant has its own schema within the same database. The application switches schemas based on the tenant context.

   ```java
   @Bean
   public LocalContainerEntityManagerFactoryBean entityManagerFactory(TenantContext tenantContext) {
       LocalContainerEntityManagerFactoryBean em = new LocalContainerEntityManagerFactoryBean();
       em.setDataSource(dataSource);
       em.setPackagesToScan("com.example");
       em.setJpaPropertyMap(Map.of(
           "hibernate.default_schema", tenantContext.getTenantId()
       ));
       return em;
   }
   ```

3. **Table per Tenant**

   All tenants share the same schema and tables, with a tenant identifier column used to segregate data.

   ```java
   @Entity
   public class Customer {
       @Id
       private Long id;
       
       @Column(name = "tenant_id")
       private String tenantId;

       // other fields
   }
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 84. How do you configure and use the `@SequenceGenerator` and `@TableGenerator` annotations in JPA?

#### `@SequenceGenerator`

Used to generate primary key values based on a database sequence.

```java
@Entity
public class Employee {

    @Id
    @GeneratedValue(strategy = GenerationType.SEQUENCE, generator = "employee_seq")
    @SequenceGenerator(name = "employee_seq", sequenceName = "employee_seq", allocationSize = 1)
    private Long id;

    private String name;

    // getters and setters
}
```

#### `@TableGenerator`

Used to generate primary key values based on a table that stores sequence values.

```java
@Entity
public class Department {

    @Id
    @GeneratedValue(strategy = GenerationType.TABLE, generator = "dept_gen")
    @TableGenerator(name = "dept_gen", table = "id_gen", pkColumnName = "gen_name", valueColumnName = "gen_val", pkColumnValue = "dept_id", allocationSize = 1)
    private Long id;

    private String name;

    // getters and setters
}
```
#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 85. What is the purpose of the `@Converter` annotation in JPA and how do you use it to create custom converters?

#### Purpose of `@Converter`

The `@Converter` annotation is used to define custom converters that transform an entity attribute to and from its database representation.

#### Creating Custom Converters

1. **Define the Converter**

   ```java
   @Converter(autoApply = true)
   public class BooleanToStringConverter implements AttributeConverter<Boolean, String> {

       @Override
       public String convertToDatabaseColumn(Boolean attribute) {
           return attribute ? "Y" : "N";
       }

       @Override
       public Boolean convertToEntityAttribute(String dbData) {
           return "Y".equals(dbData);
       }
   }
   ```

2. **Apply the Converter**

   ```java
   @Entity
   public class User {

       @Id
       private Long id;
       
       @Convert(converter = BooleanToStringConverter.class)
       private Boolean active;

       // getters and setters
   }
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 86. How do you handle database migrations in a Spring Data JPA application?

#### Database Migrations

1. **Using Flyway**

   Add Flyway dependency:

   ```xml
   <dependency>
       <groupId>org.flywaydb</groupId>
       <artifactId>flyway-core</artifactId>
   </dependency>
   ```

   Configure Flyway properties in `application.properties`:

   ```properties
   spring.flyway.url=jdbc:mysql://localhost:3306/mydb
   spring.flyway.user=root
   spring.flyway.password=password
   spring.flyway.locations=classpath:db/migration
   ```

   Create migration scripts in `src/main/resources/db/migration`:

   ```sql
   -- V1__create_user_table.sql
   CREATE TABLE user (
       id BIGINT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(255) NOT NULL
   );
   ```

2. **Using Liquibase**

   Add Liquibase dependency:

   ```xml
   <dependency>
       <groupId>org.liquibase</groupId>
       <artifactId>liquibase-core</artifactId>
   </dependency>
   ```

   Configure Liquibase properties in `application.properties`:

   ```properties
   spring.liquibase.change-log=classpath:db/changelog/db.changelog-master.xml
   ```

   Create changelog file `src/main/resources/db/changelog/db.changelog-master.xml`:

   ```xml
   <databaseChangeLog
       xmlns="http://www.liquibase.org/xml/ns/dbchangelog"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xsi:schemaLocation="http://www.liquibase.org/xml/ns/dbchangelog
                           http://www.liquibase.org/xml/ns/dbchangelog/dbchangelog-3.8.xsd">

       <changeSet id="1" author="author">
           <createTable tableName="user">
               <column name="id" type="BIGINT" autoIncrement="true">
                   <constraints primaryKey="true"/>
               </column>
               <column name="name" type="VARCHAR(255)"/>
           </createTable>
       </changeSet>
   </databaseChangeLog>
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 87. What are the key considerations when implementing a custom repository in Spring Data JPA?

#### Key Considerations

1. **Interface Definition**

   Define a custom repository interface:

   ```java
   public interface CustomRepository {
       List<CustomEntity> customQueryMethod();
   }
   ```

2. **Implementation**

   Implement the custom repository interface:

   ```java
   public class CustomRepositoryImpl implements CustomRepository {
       
       @PersistenceContext
       private EntityManager em;

       @Override
       public List<CustomEntity> customQueryMethod() {
           return em.createQuery("SELECT c FROM CustomEntity c WHERE c.someField = :value", CustomEntity.class)
                    .setParameter("value", "someValue")
                    .getResultList();
       }
   }
   ```

3. **Extend Custom Repository**

   Extend the custom repository in the main repository:

   ```java
   public interface MainRepository extends JpaRepository<CustomEntity, Long>, CustomRepository {
   }
   ```

4. **Configuration**

   Ensure Spring Data JPA is aware of the custom implementation:

   ```java
   @Configuration
   public class RepositoryConfig {
       @Bean
       public CustomRepository customRepository(EntityManager em) {
           return new CustomRepositoryImpl(em);
       }
   }
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 88. How do you manage database connection pooling in a Spring Data JPA application?

#### Database Connection Pooling

1. **Using HikariCP (Default in Spring Boot)**

   Configure HikariCP properties in `application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/mydb
   spring.datasource.username=root
   spring.datasource.password=password
   spring.datasource.hikari.maximum-pool-size=10
   spring.datasource.hikari.minimum-idle=2
   spring.datasource.hikari.idle-timeout=30000
   spring.datasource.hikari.max-lifetime=1800000
   ```

2. **Using DBCP2**

   Add DBCP2 dependency:

   ```xml
   <dependency>
       <groupId>org.apache.commons</groupId>
       <artifactId>commons-dbcp2</artifactId>
   </dependency>
   ```

   Configure DBCP2 properties in `application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/mydb
   spring.datasource.username=root
   spring.datasource.password=password
   spring.datasource.type=org.apache.commons.dbcp2.BasicDataSource
   spring.datasource.dbcp2.initial-size=5
   spring.datasource.dbcp2.max-total=10
   spring.datasource.dbcp2.max-idle=5
   spring.datasource.dbcp2.min-idle=2
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 89. What is the role of the `@SecondaryTable` annotation in JPA and how do you use it to map an entity to multiple tables?

#### Role of `@SecondaryTable`

The `@SecondaryTable` annotation is used to map an entity to multiple tables. It is useful when an entity's attributes are spread across multiple tables.

#### Usage

1. **Define the Entity**

   ```java
   @Entity
   @Table(name = "primary_table")
   @SecondaryTable(name = "secondary_table", pkJoinColumns = @PrimaryKeyJoinColumn(name = "id"))
   public class MyEntity {

       @Id
       private Long id;

       @Column(table = "primary_table")
       private String primaryField;

       @Column(table = "secondary_table")
       private String secondaryField;

       // getters and setters
   }
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 90. Explain the concept of `Entity Detachment` in JPA and how it affects the persistence context.

#### Entity Detachment

Entity detachment occurs when an entity instance is no longer associated with a persistence context. Detached entities are not managed by the persistence context, and changes made to them are not automatically synchronized with the database.

#### Effects on Persistence Context

1. **Detached Entity**

   ```java
   EntityManager em = ...;
   MyEntity entity = em.find(MyEntity.class, 1L);
   em.detach(entity);
   ```

   The `entity` is now detached. Changes to this entity will not be persisted unless it is merged back into the persistence context.

2. **Merging Detached Entities**

   ```java
   entity.setField("newValue");
   em.merge(entity);
   ```

   The `merge` method re-attaches the entity to the persistence context, and changes are persisted.

### 91. How do you implement soft deletes in a Spring Data JPA application?

#### Soft Deletes

1. **Add a Boolean Field**

   Add a `deleted` field to the entity:

   ```java
   @Entity
   public class MyEntity {

       @Id
       private Long id;

       private Boolean deleted = false;

       // other fields and methods
   }
   ```

2. **Override Repository Methods**

   Override repository methods to filter out deleted records:

   ```java
   public interface MyEntityRepository extends JpaRepository<MyEntity, Long> {

       @Query("SELECT e FROM MyEntity e WHERE e.deleted = false")
       List<MyEntity> findAllNotDeleted();
   }
   ```

3. **Modify Delete Methods**

   Modify delete methods to set the `deleted` flag:

   ```java
   @Transactional
   public void softDelete(Long id) {
       MyEntity entity = repository.findById(id).orElseThrow(() -> new EntityNotFoundException());
       entity.setDeleted(true);
       repository.save(entity);
   }
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 92. What are the pros and cons of using `EntityManager` directly versus using Spring Data JPA repositories?

#### Pros and Cons

| Aspect                                | `EntityManager`                                           | Spring Data JPA Repositories                              |
|---------------------------------------|----------------------------------------------------------|----------------------------------------------------------|
| **Pros**                              |                                                          |                                                          |
| Flexibility                           | Full control over queries and transactions               | Simplified CRUD operations, less boilerplate code        |
| Custom Queries                        | Easier to write complex, custom queries                  | Supports derived queries, query methods                  |
| Transaction Management                | Direct control over transaction boundaries               | Built-in transaction management                          |
| **Cons**                              |                                                          |                                                          |
| Boilerplate Code                      | More boilerplate code for CRUD operations                | Limited flexibility for complex queries                  |
| Learning Curve                        | Steeper learning curve for beginners                     | Easier for beginners                                     |
| Performance Optimization              | Requires manual optimization                             | Automatic optimizations, but less control                |

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---

### 93. How do you handle hierarchical data structures (e.g., trees, graphs) in JPA?

#### Handling Hierarchical Data

1. **Self-Referencing Entity**

   Define an entity with a self-referencing relationship:

   ```java
   @Entity
   public class Category {

       @Id
       private Long id;

       private String name;

       @ManyToOne
       @JoinColumn(name = "parent_id")
       private Category parent;

       @OneToMany(mappedBy = "parent")
       private List<Category> children = new ArrayList<>();

       // getters and setters
   }
   ```

2. **Queries for Hierarchical Data**

   ```java
   // Fetch root categories
   List<Category> rootCategories = em.createQuery("SELECT c FROM Category c WHERE c.parent IS NULL", Category.class).getResultList();

   // Fetch children of a category
   List<Category> children = em.createQuery("SELECT c FROM Category c WHERE c.parent = :parent", Category.class)
                               .setParameter("parent", parentCategory)
                               .getResultList();
   ```

3. **Persisting Hierarchical Data**

   ```java
   Category parent = new Category();
   parent.setName("Parent Category");

   Category child = new Category();
   child.setName("Child Category");
   child.setParent(parent);

   em.persist(parent);
   em.persist(child);
   ```

#### **[⬆ Back to Top](#level--spring-data-jpa-hard)**
---