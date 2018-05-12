==== JavaMelody UI Module for SpringBootAdmin v1 ====

This module adds a view that displays the javamelody overview for each
registered application in [SpringBootAdmin v1](http://codecentric.github.io/spring-boot-admin/1.5.7/)

. Add the ui module to your classpath:

pom.xml (spring boot admin)
```xml
<dependency>
    <groupId>de.codecentric</groupId>
    <artifactId>spring-boot-admin-server-ui-javamelody</artifactId>
    <version>1.5.7.0</version>
</dependency>
```

. Make sure each application that is registered with SBA has javamelody client support enabled and can be reached at the default endpoint */monitoring*

pom.xml (javamelody client)
```xml
<!-- https://github.com/javamelody/javamelody/wiki/SpringBootStarter -->
<dependency>
    <groupId>net.bull.javamelody</groupId>
    <artifactId>javamelody-spring-boot-starter</artifactId>
    <version>1.72.0</version>
</dependency>
```

Latest javamelody version: [![Maven Central](https://maven-badges.herokuapp.com/maven-central/net.bull.javamelody/javamelody-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/net.bull.javamelody/javamelody-core)

License [ASL](http://www.apache.org/licenses/LICENSE-2.0)

