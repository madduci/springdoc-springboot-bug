# springdoc-springboot-bug

The following repository shows the bug affecting SpringBoot 3 in combination with SpringDoc 2.4.0.

In particular, the endpoint /v3/api-docs works fine, but the endpoint /swagger-ui/index.html does not work.

The Demo application was generated using start.spring.io with the following dependencies:

- Spring Web (org.springframework.boot:spring-boot-starter-web)


The JDK used for test is the Eclipse Temurin 21.0.2

## Important

With SpringDoc 2.5.0 it works again
