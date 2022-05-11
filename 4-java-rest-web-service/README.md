## Name
java-rest-web-service

## Description
Building a RESTful Web Service

## 环境设置
- JDK 11
- Maven 3.8.4

## 详细步骤
1. 初始化项目
   - 通过 https://start.spring.io/ 初始化，填写相应的信息，生成之后下载到本地
   - 使用 IDE 自带的 Spring Initializr 初始化，填写相应的信息
     - Dependencies 选择 `Spring Web`
2. 编写代码
3. Build 可执行的 `JAR` 文件
```shell
./mvnw clean package
```
4. 运行 `JAR` 文件
```shell
$ java -jar target/java-rest-web-service-0.0.1-SNAPSHOT.jar


  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.6.7)

2022-05-11 18:04:32.609  INFO 89426 --- [           main] c.m.j.JavaRestWebServiceApplication      : Starting JavaRestWebServiceApplication v0.0.1-SNAPSHOT using Java 11.0.11 on CTANG2ML with PID 89426 (/Users/mtang/DevOps/CodeHub/com.GitHub/learn-java/4-java-rest-web-service/target/java-rest-web-service-0.0.1-SNAPSHOT.jar started by mtang in /Users/mtang/DevOps/CodeHub/com.GitHub/learn-java/4-java-rest-web-service)
2022-05-11 18:04:32.612  INFO 89426 --- [           main] c.m.j.JavaRestWebServiceApplication      : No active profile set, falling back to 1 default profile: "default"
2022-05-11 18:04:33.458  INFO 89426 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2022-05-11 18:04:33.469  INFO 89426 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2022-05-11 18:04:33.470  INFO 89426 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.62]
2022-05-11 18:04:33.567  INFO 89426 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2022-05-11 18:04:33.567  INFO 89426 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 894 ms
2022-05-11 18:04:33.859  INFO 89426 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2022-05-11 18:04:33.866  INFO 89426 --- [           main] c.m.j.JavaRestWebServiceApplication      : Started JavaRestWebServiceApplication in 2.379 seconds (JVM running for 2.837)
```
5. 打开浏览器访问
- 默认参数
  - http://127.0.0.1:8080/greeting
  - {"id":1,"content":"Hello, World!"}
- 提供参数
  - http://127.0.0.1:8080/greeting?name=Merlin
  - {"id":2,"content":"Hello, Merlin!"}

## 参考
https://spring.io/guides/gs/rest-service/
