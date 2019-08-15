SpringBoot-yml
.yml file configuration in SpringBoot application

What were done in the project:
- Assign method parameter default value from application.properties file.
- Profile-specific Properties 
	- C:\MyProj\eclipse-workspace\SpringBootRestApp> mvn clean compile
	- > mvn spring-boot:run -Dspring.profiles.active=qa
- Hierarchical Properties
	- Create a class for configuration
	- Add @Component and  @ConfigurationProperties annotations
- Using .yaml instead of properties

Source: Udemy - Spring Boot: Complete guide from development to deployment
