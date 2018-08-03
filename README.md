# maven-repository
个人maven仓库

### 使用方式

在`pom.xml`中的`<project>`标签内新增远程仓库即可，如下：

```xml
<repositories>
    <repository>
        <id>YuanLi-maven-repository</id>
        <name>YuanLi-maven-repository</name>
        <url>https://raw.github.com/YuanLicc/maven-repository/[branch]/</url>
    </repository>
</repositories>
```

### 列表

|  项目  |      描述       |                   项目地址                   |  artifactId   | groupId | version |
| :----: | :-------------: | :------------------------------------------: | :-----------: | :-----: | :-----: |
| common | 公用接口及 util | [common](https://github.com/YuanLicc/common) | com.yl.common |  base   |   1.0   |

