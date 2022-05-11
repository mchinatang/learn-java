## Name
java-hello-world

## Description
Using Maven to build a simple Java project.

## Usage
#### Build Java Code
将 Java 代码文件编译，打包成一个 `JAR` 包
```shell
$ mvn package
```
或者使用以下命令将生成的 `.jar` 包安装到本地 Maven 仓库
```shell
$ mvn install
```

#### 运行 `JAR` 文件
```shell
$ java -jar target/java-hello-world-0.1.0.jar
Hello World!
```

