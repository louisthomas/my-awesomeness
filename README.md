# my-awesomeness
A curated list of awesome frameworks, libraries, software and tutorials.

## Contents
- [Projects](#projects)
  - [Monitoring](#monitoring)
  - [Cache](#cache)
  - [Secret](#secret)
  - [Messaging](#messaging)
  - [Feature Flag](#feature)
  - [Chaos](#chaos)
  - [Devops](#devops)
  - [Security](#security)
  - [Spring Boot migration](#Spring-Boot-migration)
  - [Java](#java)
  - [Blog](#blog)
  
## Projects


### Monitoring

*Application monitoring*

- [Promregator](https://github.com/promregator/promregator) - Prometheus Aggregator for Cloud Foundry.
- [Promregator & micrometer](https://docs.google.com/document/d/1XGwjn1wUW843q8G8SEsZYuMRuBIKhsufH0yUEaLMbPc/edit?ts=5afc5875) - SCDF Metrics Collection with Micrometer, Prometheus and Grafana - CloudFoundry.
- [Sprint Boot & Prometheus](https://dzone.com/articles/monitoring-using-spring-boot-20-prometheus-and-gra) - Set Up and Integrate Prometheus With Grafana for Monitoring
- [Spring Boot Actuator 2.0 & Micrometer](https://www.slideshare.net/makingx/spring-boot-actuator-20-micrometer-jjugccc-ccca1?qid=7619223e-82c0-4edc-b42e-17c9b118df29&v=&b=&from_search=4) - Presentation about Spring Boot Actuator, Micrometer, Prometheus
- [Micrometer & Spring Boot](https://www.youtube.com/watch?v=Bo4lRLyIgU0) - New insights into your Spring Boot

### Cache
- [Sprint Boot, Grafana & Prometheus](https://github.com/codecentric/spring-boot-monitoring-sample) - Spring Boot Monitoring, include docker compose with Grafana and Prometheus
- [Observability with Spring Boot and PCF](https://content.pivotal.io/blog/out-of-the-box-application-observability-with-spring-boot-pivotal-cloud-foundry) - PCF metrics, Metric registrar, Log-cache PCF platform, Actuator, Micrometer
- [Spring MVC ETAG](https://medium.com/simars/http-304-conditional-caching-in-rest-api-using-spring-mvc-ae49f95367de) HTTP-304 Conditional Cache Control using Spring MVC

- [Redis and PCC](https://content.pivotal.io/blog/cache-rules-everything-around-me-when-to-use-redis-and-when-to-use-pivotal-cloud-cache) - When to Use Redis and When to Use Pivotal Cloud Cache

### Secret

*Manage secret*

- [CredHub Service Broker](https://content.pivotal.io/blog/enterprise-architects-its-time-to-learn-how-the-credhub-service-broker-applies-the-principle-of-least-privilege-to-your-secrets) - Learn How the CredHub Service Broker Applies the Principle of Least Privilege to Your Secrets.
- [CredHub & Concourse](https://blog.ik.am/entries/496) - Use CredHub for Concourse's Credential Management (ACL enabled)  
- [Vault service broker](https://github.com/hashicorp/vault-service-broker) - The official HashiCorp Vault broker integration to the Open Service Broker API. This service broker provides support for secure secret storage and encryption-as-a-service to HashiCorp Vault. 
- [Vault service broker guide](https://www.hashicorp.com/blog/cloud-foundry-vault-service-broker) - How to configure Vault service broker
- [Vault & PCF](https://www.slideshare.net/stenio123/secure-and-convenient-workflows-integrating-hashicorp-vault-with-pivotal-cloud-foundry-93989914?qid=f0782f53-4280-491e-a120-5e179e5b9a99&v=&b=&from_search=1) - Secure and convenient workflow: Vault with PCF

### Messaging

*Message queue technology*

- [Spring cloud stream](https://piotrminkowski.wordpress.com/2018/06/15/building-and-testing-message-driven-microservices-using-spring-cloud-stream/) - Building and testing message-driven microservices using Spring Cloud Stream
- [Microservices, events, ...](https://www.slideshare.net/Pivotal/microservices-events-and-breaking-the-data-monolith-with-kafka) - software architecture and Kafka

### Feature

*Feature flagging, A/B testing*

- [Flagr](https://github.com/checkr/flagr) - Flagr is a feature flagging, A/B testing and dynamic configuration microservice

### Chaos

*Chaos engineering*

- [Chaos Monkey Spring Boot](https://github.com/codecentric/chaos-monkey-spring-boot) - Chaos Monkey for Spring Boot applications and will try to attack your running Spring Boot App.
- [Chaos Toolkit & Chaos Monkey Spring Boot](https://medium.com/chaos-toolkit/chaos-toolkit-loves-chaos-monkey-for-spring-boot-548352985c8f) - Chaos Toolkit LOVES Chaos Monkey for Spring Boot
- [Gremlin: Chaos engineering tool](https://www.gremlin.com/) - Chaos commercial product

### Devops

- [Concourse samples](https://github.com/pivotalservices/concourse-pipeline-samples) - Pivotal Concourse samples and recipes

### Security

- [Go Cloud Foundry OAuth adapter example](https://github.com/grafana/grafana/pull/6414/commits/801a62c582c8bab101412b312e5e3db5233ed9bd) - Cloud Foundry Oauth adapter for Grafana

### Spring-Boot-migration

*Spring boot migration 1.5.x to 2.X

- [Spring-Boot-2.0-Migration-Guide](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-2.0-Migration-Guide)
- [migration to Spring Boot 2 when using Flyway](https://wimdeblauwe.wordpress.com/2018/08/30/tip-on-migration-to-spring-boot-2-when-using-flyway/) - Guide to migrate with Flyway
- [Spring security features matrix](https://github.com/spring-projects/spring-security/wiki/OAuth-2.0-Features-Matrix)
- [Spring resource server sample](https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples/spring-boot-sample-oauth2-resource-server) - Sample project with spring-boot-starter-oauth2-resource-server

### Java

- [Upgrading java 8 to 12](https://www.infoq.com/articles/upgrading-java-8-to-12) - Pro and cons & new features for upgrading to Java 12

### Blog

- [High scability](http://highscalability.com/) - Blog about architecture
- [Piotr's TechBlog](https://piotrminkowski.wordpress.com/) - Blog about new technologies.
- [reflectoring](https://reflectoring.io/) - Blog about Java, Spring and Architecture.
- [Tuhrig blog](https://tuhrig.de/) - Blog about Spring and AWS




