# 目录

* [I. Spring Boot文档](I.Spring_Boot_Documentation/README.md)
    * [1. 关于文档](I.Spring_Boot_Documentation/1.About_the_documentation.md)
    * [2. 获取帮助](I.Spring_Boot_Documentation/2.Getting_help.md)
    * [3. 第一步](I.Spring_Boot_Documentation/3.First_steps.md)
    * [4. 使用Spring Boot](I.Spring_Boot_Documentation/4.Working_with_Spring_Boot.md)
    * [5. 了解Spring Boot的功能](I.Spring_Boot_Documentation/5.Learning_about_Spring_Boot_features.md)
    * [6. 转到产品](I.Spring_Boot_Documentation/6.Moving_to_production.md)
    * [7. 高级主题](I.Spring_Boot_Documentation/7.Advanced_topics.md)
* [II. 入门](II.Getting_started/README.md)
    * [8. Spring Boot简介](II.Getting_started/8.Introducing_Spring_Boot.md)
    * [9. 系统要求](II.Getting_started/9.System_Requirements.md)
        * [9.1 Servlet容器](II.Getting_started/9.System_Requirements.md#91-servlet容器)
    * [10. 安装Spring Boot](II.Getting_started/10.Installing_Spring_Boot.md)
        * [10.1 Java开发者的安装说明](II.Getting_started/10.1.Installation_instructions_for_the_Java_developer.md)
            * [10.1.1 Maven安装](II.Getting_started/10.1.1.Maven_installation.md)
            * [10.1.2 Gradle安装](II.Getting_started/10.1.2.Gradle_installation.md)
        * 10.2. Installing the Spring Boot CLI
        * 10.3. Upgrading from an earlier version of Spring Boot
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
        * [13.5 启动器](III.Using_Spring_Boot/13.5.Starters.md)
    * [14. 构建代码](III.Using_Spring_Boot/14.Structuring_your_code.md)
        * [14.1 使用“default”包](III.Using_Spring_Boot/14.Structuring_your_code.md#141-使用default包)
        * [14.2 放置主程序类](III.Using_Spring_Boot/14.Structuring_your_code.md#142-放置主程序类)
    * [15. 配置类](III.Using_Spring_Boot/15.Configuration_classes.md)
        * [15.1 导入额外的配置类](III.Using_Spring_Boot/15.Configuration_classes.md#151-导入额外的配置类)
        * [15.2 导入XML配置](III.Using_Spring_Boot/15.Configuration_classes.md#152-导入XML配置)
    * [16. 自动配置](III.Using_Spring_Boot/16.Auto-configuration.md)
        * [16.1 逐步替代自动配置](III.Using_Spring_Boot/16.Auto-configuration.md#161-逐步替代自动配置)
        * [16.2 禁用指定的自动配置](III.Using_Spring_Boot/16.Auto-configuration.md#162-禁用指定的自动配置)
    * [17. Spring的bean以及依赖注入](III.Using_Spring_Boot/17.Spring_Beans_and_dependency_injection.md)
    * [18. 使用@SpringBootApplication注解](III.Using_Spring_Boot/18.Using_the_@SpringBootApplication_annotation.md)
    * [19. 运行您的程序](III.Using_Spring_Boot/19.Running_your_application.md)
        * [19.1 从IDE运行](III.Using_Spring_Boot/19.1.Running_from_an_IDE.md)
        * [19.2 作为打包程序运行](III.Using_Spring_Boot/19.2.Running_as_a_packaged_application.md)
        * [19.3 使用Maven插件](III.Using_Spring_Boot/19.3.Using_the_Maven_plugin.md)
        * [19.4 使用Gradle插件](III.Using_Spring_Boot/19.4.Using_the_Gradle_plugin.md)
        * [19.5 热插拔](III.Using_Spring_Boot/19.5.Hot_swapping.md)
    * [20. 开发者工具](III.Using_Spring_Boot/20.Developer_tools.md)
        * [20.1 属性默认值](III.Using_Spring_Boot/20.1.Property_defaults.md)
        * [20.2 自动重启](III.Using_Spring_Boot/20.2.Automatic_restart.md)
            * [20.2.1 排除的资源](III.Using_Spring_Boot/20.2.1.Excluding_resources.md)
            * [20.2.2 监视其他路径](III.Using_Spring_Boot/20.2.2.Watching_additional_paths.md)
            * [20.2.3 禁用重启](III.Using_Spring_Boot/20.2.3.Disabling_restart.md)
            * [20.2.4 使用触发文件](III.Using_Spring_Boot/20.2.4.Using_a_trigger_file.md)
            * [20.2.5 定制重启类加载器](III.Using_Spring_Boot/20.2.5.Customizing_the_restart_classloader.md)
            * [20.2.6 已知的限制](III.Using_Spring_Boot/20.2.6.Known_limitations.md)
        * [20.3 LiveReload](III.Using_Spring_Boot/20.3.LiveReload.md)
    * [21. 打包您的生产环境程序](III.Using_Spring_Boot/21.Packaging_your_application_for_production.md)
    * [22. 接下来读什么](III.Using_Spring_Boot/22.What_to_read_next.md)
* [IV. Spring Boot的功能](IV.Spring_Boot_features/README.md)
    * 27. Developing web applications
        * 27.1. The ‘Spring Web MVC framework’
            * 27.1.1. Spring MVC auto-configuration
            * 27.1.2. HttpMessageConverters
            * 27.1.3. Custom JSON Serializers and Deserializers
            * 27.1.4. MessageCodesResolver
            * 27.1.5. Static Content
            * 27.1.6. Custom Favicon
            * 27.1.7. ConfigurableWebBindingInitializer
            * 27.1.8. Template engines
            * 27.1.9. Error Handling
            * 27.1.10. Spring HATEOAS
            * 27.1.11. CORS support
        * 27.2. JAX-RS and Jersey
        * 27.3. Embedded servlet container support
            * 27.3.1. Servlets, Filters, and listeners
Registering Servlets, Filters, and listeners as Spring beans
            * 27.3.2. Servlet Context Initialization
Scanning for Servlets, Filters, and listeners
            * 27.3.3. The EmbeddedWebApplicationContext
            * 27.3.4. Customizing embedded servlet containers
Programmatic customization
Customizing ConfigurableEmbeddedServletContainer directly
            * 27.3.5. JSP limitations
    * 28. Security
        * 28.1. OAuth2
            * 28.1.1. Authorization Server
            * 28.1.2. Resource Server
        * 28.2. Token Type in User Info
        * 28.3. Customizing the User Info RestTemplate
            * 28.3.1. Client
            * 28.3.2. Single Sign On
        * 28.4. Actuator Security 
    * [29. 使用SQL数据库](IV.Spring_Boot_features/29.Working_with_SQL_databases.md)
        * [29.1 配置DataSource](IV.Spring_Boot_features/29.1.Configure_a_DataSource.md)
            * [29.1.1 内置数据库支持](IV.Spring_Boot_features/29.1.1.Embedded_Database_Support.md)
            * 29.1.2. Connection to a production database
            * 29.1.3. Connection to a JNDI DataSource
        * [29.2 使用JdbcTemplate](IV.Spring_Boot_features/29.2.Using_JdbcTemplate.md)
        * [29.3 JPA和“Spring Data”](IV.Spring_Boot_features/29.3.JPA_and_‘Spring_Data’.md)
            * [29.3.1 实体类](IV.Spring_Boot_features/29.3.1.Entity_Classes.md)
            * [29.3.2 Spring Data JPA仓库](IV.Spring_Boot_features/29.3.2.Spring_Data_JPA_Repositories.md)
            * [29.3.3 创建和删除JPA数据库](IV.Spring_Boot_features/29.3.3.Creating_and_dropping_JPA_databases.md)
            * [29.3.4 Open EntityManager in View](IV.Spring_Boot_features/29.3.4.Open_EntityManager_in_View.md)
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
* [V. Spring Boot致动器：生产环境功能](V.Spring_Boot_Actuator_Production-ready_features/README.md)
    * [46. 启用生产环境功能](V.Spring_Boot_Actuator_Production-ready_features/46.Enabling_production-ready_features.md)
