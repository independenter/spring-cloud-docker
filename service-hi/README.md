1.spring-cloud-starter-zipkin，在某些版本没有集成
https://github.com/independenter/spring-cloud-sleuth/blob/master/spring-cloud-starter-zipkin/pom.xml
相当于
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-sleuth</artifactId>
</dependency>
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-sleuth-zipkin</artifactId>
</dependency>
2.
Finchley 是基于 Spring Boot 2.0.x 构建的，不支持 Spring Boot 1.5.x
Dalston 和 Edgware 是基于 Spring Boot 1.5.x 构建的，不支持 Spring Boot 2.0.x
Camden 构建于 Spring Boot 1.4.x，但依然能支持 Spring Boot 1.5.x
