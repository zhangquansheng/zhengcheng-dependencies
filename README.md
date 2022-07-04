# 新征程框架项目

`zhengcheng`是一个基于**SpringBoot**的框架支持项目，只需简单配置，即可快速接入各种通用组件，从而节省大量时间,让我们在开发业务时能够专注于业务的编写而不必过多的关注框架的配置，并且可以促进团队合作，降低维护成本，减少低级BUG，有助于代码审查。

## Maven 安装

```xml
 <dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.zhengcheng</groupId>
            <artifactId>zc-dependencies</artifactId>
            <version>6.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```


