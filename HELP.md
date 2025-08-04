# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.5.4/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.5.4/maven-plugin/build-image.html)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/3.5.4/reference/actuator/index.html)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/3.5.4/specification/configuration-metadata/annotation-processor.html)
* [Spring Data JDBC](https://docs.spring.io/spring-boot/3.5.4/reference/data/sql.html#data.sql.jdbc)
* [Spring Data JPA](https://docs.spring.io/spring-boot/3.5.4/reference/data/sql.html#data.sql.jpa-and-spring-data)
* [Rest Repositories](https://docs.spring.io/spring-boot/3.5.4/how-to/data-access.html#howto.data-access.exposing-spring-data-repositories-as-rest)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/3.5.4/reference/using/devtools.html)
* [JDBC API](https://docs.spring.io/spring-boot/3.5.4/reference/data/sql.html)
* [Java Mail Sender](https://docs.spring.io/spring-boot/3.5.4/reference/io/email.html)
* [Spring REST Docs](https://docs.spring.io/spring-restdocs/docs/current/reference/htmlsingle/)
* [Spring Session for JDBC](https://docs.spring.io/spring-session/reference/)
* [Spring Web](https://docs.spring.io/spring-boot/3.5.4/reference/web/servlet.html)
* [Spring Web Services](https://docs.spring.io/spring-boot/3.5.4/reference/io/webservices.html)
* [Spring Reactive Web](https://docs.spring.io/spring-boot/3.5.4/reference/web/reactive.html)

### Guides

The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)
* [Using Spring Data JDBC](https://github.com/spring-projects/spring-data-examples/tree/master/jdbc/basics)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/)
* [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/)
* [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/)
* [Accessing Relational Data using JDBC with Spring](https://spring.io/guides/gs/relational-data-access/)
* [Managing Transactions](https://spring.io/guides/gs/managing-transactions/)
* [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Producing a SOAP web service](https://spring.io/guides/gs/producing-web-service/)
* [Building a Reactive RESTful Web Service](https://spring.io/guides/gs/reactive-rest-service/)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the
parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

