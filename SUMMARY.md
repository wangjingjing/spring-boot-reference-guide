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
            * [13.2.4 使用Spring Boot的Maven插件](III.Using_Spring_Boot/13.2.4.Using_the_Spring_Boot_Maven_plugin.md)
        * [13.3. Gradle](III.Using_Spring_Boot/13.3.Gradle.md)
        * 13.4. Ant
        * 13.5. Starters
    * [14. 构建代码](III.Using_Spring_Boot/14.Structuring_your_code.md)
    * [15. 配置类](III.Using_Spring_Boot/15.Configuration_classes.md)
    * [16. 自动配置](III.Using_Spring_Boot/16.Auto-configuration.md)
    * [17. Spring的bean以及依赖注入](III.Using_Spring_Boot/17.Spring_Beans_and_dependency_injection.md)
    * [18. 使用@SpringBootApplication注解](III.Using_Spring_Boot/18.Using_the_@SpringBootApplication_annotation.md)
* [IV. Spring Boot的特性](IV.Spring_Boot_features/README.md)
    * [29. 使用SQL数据库](IV.Spring_Boot_features/29.Working_with_SQL_databases.md)
        * [29.1 配置DataSource](IV.Spring_Boot_features/29.1.Configure_a_DataSource.md)
            * [29.1.1 嵌入式数据库支持](IV.Spring_Boot_features/29.1.1.Embedded_Database_Support.md)
            * 29.1.2. Connection to a production database
            * 29.1.3. Connection to a JNDI DataSource
        * [29.2 使用JdbcTemplate](IV.Spring_Boot_features/29.2.Using_JdbcTemplate.md)
        * [29.3 JPA和“Spring Data”](IV.Spring_Boot_features/29.3.JPA_and_‘Spring Data’.md)
            * [29.3.1 实体类](IV.Spring_Boot_features/29.3.1.Entity_Classes.md)
            * [29.3.2 Spring Data JPA仓库](IV.Spring_Boot_features/29.3.2.Spring_Data_JPA_Repositories.md)
            * 29.3.3. Creating and dropping JPA databases
            * 29.3.4. Open EntityManager in View
        * 29.4. Using H2’s web console
            * 29.4.1. Changing the H2 console’s path
            * 29.4.2. Securing the H2 console
        * 29.5. Using jOOQ
            * 29.5.1. Code Generation
            * 29.5.2. Using DSLContext
            * 29.5.3. Customizing jOOQ
    * [41. 测试](IV.Spring_Boot_features/41.Testing.md)
        * [41.1 测试范围内的依赖](IV.Spring_Boot_features/41.1.Test_scope_dependencies.md)
        * [41.2 测试Spring程序](IV.Spring_Boot_features/41.2.Testing_Spring_applications.md)
        * [41.3 测试Spring Boot程序](IV.Spring_Boot_features/41.3.Testing_Spring_Boot_applications.md)
            * [41.3.1 检测测试配置](IV.Spring_Boot_features/41.3.Testing_Spring_Boot_applications.md)
            * 41.3.2. Excluding test configuration
            * 41.3.3. Working with random ports
            * 41.3.4. Mocking and spying beans
            * [41.3.5 自动配置的测试](IV.Spring_Boot_features/41.3.5.Auto-configured_tests.md)
            * [41.3.6 自动配置的JSON测试](IV.Spring_Boot_features/41.3.6.Auto-configured_JSON_tests.md)
            * [41.3.7 自动配置的Spring MVC测试](IV.Spring_Boot_features/41.3.7.Auto-configured_Spring_MVC_tests.md)
            * 41.3.8. Auto-configured Data JPA tests
            * 41.3.9. Auto-configured JDBC tests
            * 41.3.10. Auto-configured Data MongoDB tests
            * 41.3.11. Auto-configured REST clients
            * 41.3.12. Auto-configured Spring REST Docs tests
            * 41.3.13. Using Spock to test Spring Boot applications
