# Spring-Cloud-Feign-Eureka-Replicas-Sample
- Spring-Cloud-Feign-Eureka-Replicas-Sample
- Spring-Cloud Ribon Client Side Load Balancing in Feign

## Modules
- AccountServiceWithEureka * 2
- EurekaServerReplica * 2
- CustomerServiceWithEureka

## Dependencies
```xml
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-openfeign</artifactId>
</dependency>
```
```xml
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
</dependency>

<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
</dependency>
```

## Bundles

Take note of the `pom.xml` file.

## Philosophy
It's the system or dependency manager that
provides the libraries. Anyone who has the proper development
environment set up -- one that works across many projects -- should be
able to clone the repository and do a build simply by running the
build program with no special arguments. There should be no need to
edit or install anything into the project space for the initial build.

