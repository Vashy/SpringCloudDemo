# Spring Cloud Demo

A base example of a dockerized Spring Cloud architecture.

## Modules

Applications are separated in [Git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) (every application is a dockerized Spring Boot instance):
- [Config Server](https://github.com/Vashy/SpringCloudDemoConfigServer/tree/master)
- [Config Repo](https://github.com/Vashy/SpringCloudConfigServerRepo/tree/master)
- [Eureka Server](https://github.com/Vashy/SpringCloudEurekaServer/tree/master)
- [First Client App](https://github.com/Vashy/SpringCloudDemoFirstClientApp/tree/master)
- [Second Client App](https://github.com/Vashy/SpringCloudDemoSecondClientApp/tree/master)

## Microservices patterns

- [Externalized configuration](https://microservices.io/patterns/externalized-configuration.html)
- [Service Registry](https://microservices.io/patterns/service-registry.html) and [Service Discovery](https://microservices.io/patterns/client-side-discovery.html) with [Netflix Eureka](https://github.com/Netflix/eureka)
