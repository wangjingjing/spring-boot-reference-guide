# Part V. Spring Boot致动器（Actuator）：生产环境功能

Spring Boot包含许多附加功能，可帮助您在应用程序投入生产环境时对其进行监视和管理。您可以选择使用HTTP端点、JMX甚至远程shell（SSH或Telnet）来管理和监视您的程序。审计、健康及指标收集可以自动应用到您的程序。

致动器的HTTP端点仅适用于基于Spring MVC的应用程序。尤其是不能与Jersey一起工作，[除非您同时启用Spring MVC](../IX.‘How-to’_guides/82.4.Actuator_and_Jersey.md)。
