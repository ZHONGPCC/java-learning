# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.5.0/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.5.0/maven-plugin/build-image.html)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/3.5.0/specification/configuration-metadata/annotation-processor.html)
* [Spring Data Elasticsearch (Access+Driver)](https://docs.spring.io/spring-boot/3.5.0/reference/data/nosql.html#data.nosql.elasticsearch)
* [Spring Data JDBC](https://docs.spring.io/spring-boot/3.5.0/reference/data/sql.html#data.sql.jdbc)
* [Spring Data MongoDB](https://docs.spring.io/spring-boot/3.5.0/reference/data/nosql.html#data.nosql.mongodb)
* [Spring Data Redis (Access+Driver)](https://docs.spring.io/spring-boot/3.5.0/reference/data/nosql.html#data.nosql.redis)
* [Apache Freemarker](https://docs.spring.io/spring-boot/3.5.0/reference/web/servlet.html#web.servlet.spring-mvc.template-engines)
* [Groovy Templates](https://docs.spring.io/spring-boot/3.5.0/reference/web/servlet.html#web.servlet.spring-mvc.template-engines)
* [OAuth2 Authorization Server](https://docs.spring.io/spring-boot/3.5.0/reference/web/spring-security.html#web.security.oauth2.authorization-server)
* [OAuth2 Client](https://docs.spring.io/spring-boot/3.5.0/reference/web/spring-security.html#web.security.oauth2.client)
* [Spring Web](https://docs.spring.io/spring-boot/3.5.0/reference/web/servlet.html)

### Guides

The following guides illustrate how to use some features concretely:

* [Using Spring Data JDBC](https://github.com/spring-projects/spring-data-examples/tree/master/jdbc/basics)
* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)
* [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/)
* [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the
parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

