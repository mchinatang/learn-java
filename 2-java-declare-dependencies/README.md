## Name
java-declare-dependencies

## Description
Declare Dependencies

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
$ java -jar target/java-declare-dependencies-0.1.0.jar
The current local time is: 23:57:50.408
Hello World!
```

