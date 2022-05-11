## Name
java-junit-test

## Description
Write a Test

## Usage
#### Build Java Code
运行 unit tests
```shell
$ mvn test

-------------------------------------------------------
 T E S T S
-------------------------------------------------------
Running hello.GreeterTest
Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.042 sec

Results :

Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
```

或者执行 `mvn install` 命令，因为 `install` 生命周期已经包含了 `test` 生命周期。
```shell
$ mvn install
```

#### 运行 `JAR` 文件
```shell
$ java -jar target/java-junit-test-0.1.0.jar
The current local time is: 14:55:26.815
Hello World!
```
