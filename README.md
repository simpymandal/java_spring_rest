# java_spring_rest
java_spring_rest

What is SpringBoot ?
Spring Boot is an open-source extension of the Spring Framework that hosts third-party libraries that help developers jump-start applications for production. It allows developers to focus on the application’s business logic rather than configuration.
The tool was created by Pivotal Software and has been upgraded approximately every four years. 

What are the New features in Spring 3.0 ?
The first version, Spring Boot 1.0, was released in 2014, Spring Boot 2.0 in 2018, and now Spring Boot 3.0 in November 2022.
1. Java 17 Baseline with Java 19 Support
2. Jakarta EE 9
3. Log4j2 Enhancements
4. Observability with Micrometer and Micrometer Tracing
5. GraalVM Native Image Functionality
   
**Inversion of Control (IoC)**
## What is Dependency Injection and why to use it ?
**Beans**



**plain old Java object (POJO)** is a class definition that is not tied to any Java framework so any Java program can use it. A POJO has no particular naming convention for properties and methods, or any other special restrictions. Their primary advantage is their reusability and simplicity.


@Component --
automatically detects custom beans . singleton
by annotating a class with **@Component**, you’re telling the Spring Framework that an instance of this class should be kept in the ApplicationContext
@Autowire -- 
used for automatic dependency injection.

@Qualifier -- 


@Component is a class-level annotation, but @Bean is at the method level
Link: https://www.youtube.com/watch?v=35EQXmHKZYs
**Web Application**
@Controller
@RequestMapping
@RequestBody
To make SpringBoot Support JSP add a dependency called "Tomcat Jasper" before that check which version of "Embedded Tomcat" is running in your springBoot(Goto Maven Dependencies folder and search for Tomcat)

autoConfiguration

manual Configuration can be done "application.properties" file <-- available in resources folder

"ModelView" Class -- to pass view and data
view can be pass --  setViewName
multiple data can be pass -- addObject

jackson library converts the java object to JSON

@ReprositoryRestResource




