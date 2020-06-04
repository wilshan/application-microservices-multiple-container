
# Service One

## Use case

A simple application which generates UUID every minute and updates the same in mongo database. It also stores the UUID value generated by other service in its database asynchronously by Rabbit MQ (in case of docker environment).

Below are the architecture of the application in different environments:

#### Default Environment

![alt tag](https://github.com/vmudigal/microservices-sample/service-one/blob/version-5/doc/architecture/service-one%20(default).png?raw=true)   

Execute mvn build spring-boot:run to bring up the application in default environment

#### Docker Environment

![alt tag](https://github.com/vmudigal/microservices-sample/service-one/blob/version-5/doc/architecture/service-one%20(docker).png?raw=true)   

Refer: https://github.com/vmudigal/microservices-sample/ to bring up the micro services sample complete application using docker profile.

### Technology

Microservices sample project uses a number of open source projects to work properly:

* [SpringBoot 2.3] - Application framework
* [Consul] - Registration and Discovery
* [Docker] - Containerization platform
* [Project Reactor] - Reactive Systems
* [MongoDB] - Document based Database
* [Swagger] - API Documentation
* [Rabbit MQ] - Message Broker
* [Logstash] - Log Collector

### Tools

* [Java] - Programming
* [Maven] - Build
* [Git] - Version control
* [Docker] - Deployment

### Extras

##### Swagger UI

http://localhost:8082/swagger-ui.html

![alt tag](https://github.com/vmudigal/microservices-sample/service-one/blob/version-5/doc/tools/swagger.png?raw=true)   

##### Embedded MongoDB

Access the database through a mongodb client.

![alt tag](https://github.com/vmudigal/microservices-sample/service-one/blob/version-5/doc/tools/mongodb-login.png?raw=true)   

![alt tag](https://github.com/vmudigal/microservices-sample/service-one/blob/version-5/doc/tools/mongodb.png?raw=true)   


### Help

Feel free to reach "vijayendrap@gmail.com" in-case of any concerns.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job.)

   [SpringBoot]: <https://projects.spring.io/spring-boot/>
   [Consul]: <https://www.consul.io>
   [Project Reactor]: <https://projectreactor.io/>
   [Docker]: <https://www.docker.com>
   [Maven]: <https://maven.apache.org>
   [Git]: <https://git-scm.com>
   [Java]: <https://go.java>
   [Rabbit MQ]: <https://www.rabbitmq.com/>
   [Swagger]: <https://swagger.io/>
   [Logstash]: <https://www.elastic.co/products/logstash>
   [MongoDB]: <https://www.mongodb.com/>