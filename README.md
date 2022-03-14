学习地址：http://www.mydlq.club/article/47/



1、maven 打包命令为

```
mvn clean install -Dmaven.test.skip=true --settings settings.xml
```

2、读取pom.xml

artifactId为整个微服务的名称

```
    <artifactId>springboot-helloworld</artifactId>     #为微服务的名称
    <version>0.0.1</version>                           #为项目版本，可以体现在docker进行中。
    <name>springboot-helloworld</name>
```



3、value.yaml是helm单独指定文件。

4、jenkinsfile为jenkins执行文件。

