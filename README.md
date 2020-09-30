Migration to Spring Boot 2.3.1:

Bug fixes:
	The Default log levels are inconsistent between log4J2 and logback so they have been modified.
	Spring Boot CLI adds classes from current directory to the classpath on Unix-like platforms so they have been modified.
	Actuator 'loggers' endpoint is not return all loggers for log4j and it has been modified in this version.
	SpringConfigurationPropertySource incorrectly returns ABSENT for sub properties  and it has been modified in this version.
	We are getting NoSuchBeanDefinitionException for org.springframework.context.annotation.ConfigurationClassPostProcessor.importRegistry when trying to publish AvailabilityChangeEvent during context close processing after refresh failure.
	PropertiesLauncher cannot load a resource in jar via URL and this has been fixed in this release.
	The scope of few dependencies which have been changed from compile time to run time has been changed.
	Password-based authentication with Cassandra is not working with the previous version of spring boot and in this release this has been modified.
	

Dependency	Upgraded to Version
Postgresql 	42.2.14
Undertow 	2.1.3.Final
Tomcat 	9.0.36
Spring Security	 5.3.3.RELEASE
Spring AMQP 	 2.2.7.RELEASE 
Spring Batch	4.2.4
Spring Kafka 	2.5.2
Hibernate 	5.4.17.Final 
Groovy 	2.5.12
MongoDB 	4.0.4 


