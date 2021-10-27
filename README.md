# SpringBootHandout

### How to start with Spring


```bash
sudo apt-get install openjdk-17-jre 
```

## Quickstart
[Quickstart](https://spring.io/quickstart)

## Create a project
[Project tool](https://start.spring.io/)

	Dependencies: Spring Web
	
## Spring boot basic annotations

| annotations   					| Beschreibung  | 
| ------------- 					|:-------------:|
| @RestController    					|  Der Controller verarbeitet RESTful services	| 
| @GetMapping/@RequestMapping(method=GET) 		|  HTTP-Anfragen z.B GET/POST/PUT/DELETE	|  
| @Bean 						|  https://docs.spring.io/spring-javaconfig/docs/1.0.0.M4/reference/html/ch02s02.html   						|   
| @Configuration					|  https://docs.spring.io/spring-javaconfig/docs/1.0.0.M4/reference/html/ch02.html   						|   
| @Autowired						|  https://www.baeldung.com/spring-autowire   						|
| @RequestParam(value = "name", defaultValue = "World")	|  set default parameter   			| 
| @NotNull						|  check is not null   				| 
| @Size(min=2, max=30)					|  range from x to y   				| 
| @Min(18)						|  min value    				| 

## Testing 

0. https://www.baeldung.com/spring-boot-testing
1. https://spring.io/guides/gs/testing-web/

## Java Basics

[Learn JAVA - rheinwerk-verlag.de](http://openbook.rheinwerk-verlag.de/javainsel/)

## From Rails to Spring boot

[Rails to Spring](https://github.com/lidimayra/from-rails-to-spring-boot)

## Helpful for exam
0. Beginner guide: https://www.youtube.com/watch?v=vtPkZShrvXQ
1. Docker: https://spring.io/guides/gs/spring-boot-docker/
2. kubernetes: https://spring.io/guides/topicals/spring-on-kubernetes/
3. Gateway: https://spring.io/guides/gs/gateway/
4. Google api e.g: https://spring.io/guides/gs/messaging-gcp-pubsub/
5. Redis: https://spring.io/guides/gs/messaging-redis/
