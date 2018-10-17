### 父pom工程

这个工程的主要目的是为业务工程提供jar包依赖管理，通用maven插件管理

### 使用方法
业务工程的父pom文件中加入下面依赖
```
<parent>
    <groupId>com.chinacat.boot</groupId>
    <artifactId>chinacat-boot-starter-parent</artifactId>
    <version>1.0.0</version>
</parent>
```