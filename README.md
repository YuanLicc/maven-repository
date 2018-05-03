# maven-repository
​	个人maven仓库

### 使用方式

​	在`pom.xml`中的`<project>`标签内新增远程仓库即可，如下：

```xml
  <repositories>
    <repository>
      <id>liuhuanting-maven-snapshot-repository</id>
      <name>liuhuanting-maven-snapshot-repository</name>
      <url>https://raw.github.com/liuhuanting/maven/master/</url>
    </repository>
  </repositories>
```

### 列表

|   项目    |          描述          |                      项目地址                      | artifactId  |  groupId  |   version    |
| :-------: | :--------------------: | :------------------------------------------------: | :---------: | :-------: | :----------: |
|   base    | 工具类（StringUtil等） |      [base](https://github.com/YuanLicc/base)      | com.yl.base |   base    | 1.0-SNAPSHOT |
| location  |      表示资源位置      |  [location](https://github.com/YuanLicc/location)  | com.yl.web  | location  | 1.0-SNAPSHOT |
| exception |       自定义异常       | [exception](https://github.com/YuanLicc/exception) |   com.yl    | exception | 1.0-SNAPSHOT |
| container |       xwork容器        | [container](https://github.com/YuanLicc/container) | com.yl.web  | container | 1.0-SNAPSHOT |

