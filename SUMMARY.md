#目录

* [I. Spring Boot文档](I.Spring_Boot_Documentation/README.md)
    * 1. About the documentation
    * 2. Getting help
    * 3. First steps
    * 4. Working with Spring Boot
    * 5. Learning about Spring Boot features
    * 6. Moving to production
    * 7. Advanced topics
* [II. 入门](II.Getting_started/README.md)
    * [8. Spring Boot简介](II.Getting_started/8.Introducing_Spring_Boot.md)
    * [9. 系统要求](II.Getting_started/9.System_Requirements.md)
    * 10. Installing Spring Boot
    * [11. 开发第一个Spring Boot程序](II.Getting_started/11.Developing_your_first_Spring_Boot_application.md)
        * [11.1 创建POM](II.Getting_started/11.1.Creating_the_POM.md)
        * [11.2 添加类路径依赖](II.Getting_started/11.2.Adding_classpath_dependencies.md)
        * [11.3 编写代码](II.Getting_started/11.3.Writing_the_code.md)
            * [11.3.1 @RestController和@RequestMapping注解](II.Getting_started/11.3.1.The_@RestController_and_@RequestMapping_annotations.md)
            * [11.3.2 @EnableAutoConfiguration注解](II.Getting_started/11.3.2.The_@EnableAutoConfiguration_annotation.md)
            * [11.3.3 “main”方法](II.Getting_started/11.3.3.The_“main”_method.md)
        * [11.4 运行示例](II.Getting_started/11.4.Running_the_example.md)
        * 11.5 Creating an executable jar
    * [12. 接下来读什么](II.Getting_started/12.What_to_read_next.md)
* [III. 使用Spring Boot](III.Using_Spring_Boot/README.md)
    * [13. 构建系统](III.Using_Spring_Boot/13.Build_systems.md)
        * [13.1 依赖管理](III.Using_Spring_Boot/13.1.Dependency_management.md)
        * [13.2 Maven](III.Using_Spring_Boot/13.2.Maven.md)
            * [13.2.1 继承父启动器](III.Using_Spring_Boot/13.2.1.Inheriting_the_starter_parent.md)
            * [13.2.2 不配置父POM使用Spring  Boot](III.Using_Spring_Boot/13.2.2.Using_Spring_Boot_without_the_parent_POM.md)
            * [13.2.3 更改Java版本](III.Using_Spring_Boot/13.2.3.Changing_the_Java_version.md)
            * 13.2.4. Using the Spring Boot Maven plugin
        * 13.3. Gradle
        * 13.4. Ant
        * 13.5. Starters
    * [14. 构建代码](III.Using_Spring_Boot/14.Structuring_your_code.md)
    * [15. 配置类](III.Using_Spring_Boot/15.Configuration_classes.md)
    * [16. 自动配置](III.Using_Spring_Boot/16.Auto-configuration.md)
    * [17. Spring的bean以及依赖注入](III.Using_Spring_Boot/17.Spring_Beans_and_dependency_injection.md)
    * [18. 使用@SpringBootApplication注解](III.Using_Spring_Boot/18.Using_the_@SpringBootApplication_annotation.md)
* [IV. Spring Boot的特性](IV.Spring_Boot_features/README.md)
    * [41. 测试](IV.Spring_Boot_features/41.Testing.md)
        * [41.1 测试范围内的依赖](IV.Spring_Boot_features/41.1.Test_scope_dependencies.md)
        * [41.2 测试Spring程序](IV.Spring_Boot_features/41.2.Testing_Spring_applications.md)
        * 41.3 测试Spring Boot程序
            * 41.3.1. Detecting test configuration
            * 41.3.2. Excluding test configuration
            * 41.3.3. Working with random ports
            * 41.3.4. Mocking and spying beans
            * 41.3.5. Auto-configured tests
            * 41.3.6. Auto-configured JSON tests
            * 41.3.7. Auto-configured Spring MVC tests
            * 41.3.8. Auto-configured Data JPA tests
            * 41.3.9. Auto-configured JDBC tests
            * 41.3.10. Auto-configured Data MongoDB tests
            * 41.3.11. Auto-configured REST clients
            * 41.3.12. Auto-configured Spring REST Docs tests
            * 41.3.13. Using Spock to test Spring Boot applications
