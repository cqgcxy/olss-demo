```
├── doc # 文档库
│   └── 数据库设计
├── pom.xml # maven描述符
└── src # 源代码库
    ├── main # 主程序
    │   ├── java # java源代码
    │   │   └── com.cqgcxy.olss # 顶级包名，通常规则是域名+项目名
    │   │               ├── common
    │   │               ├── dao
    │   │               ├── domain
    │   │               ├── mapper
    │   │               ├── service
    │   │               │   ├── impl
    │   │               │   │   └── UserServiceImpl.java
    │   │               │   └── UserService.java
    │   │               ├── util
    │   │               └── web
    │   ├── resources # 框架配置文件
    │   │   ├── log4j.properties
    │   │   ├── mybatis
    │   │   └── spring
    │   └── webapp # web程序根目录
    │       ├── index.jsp
    │       ├── static # 静态web资源
    │       │   ├── css
    │       │   ├── images
    │       │   ├── js
    │       │   ├── plugins
    │       │   └── videos
    │       └── WEB-INF
    │           ├── views # 动态web视图
    │           │   └── admin.jsp
    │           └── web.xml # web程序描述符
    └── test # 单元测试程序
        └── java

```