# FindLunch
This client server based application allows restaurants to register offers (e.g. for lunch) and helps customer to find these via their smartphone (based on their location).

## Webapp
The web application is based on several technologies:
  * Spring Boot
  * Spring Data JPA with Hibernate
  * Spring MVC
  * Thymeleaf Template Engine
  * Bootstrap
  
### Import into eclipse

In order to import the project into Eclipse, please follow these steps:

1.) Open Eclipse
2.) Right click on your project explorer and select "Import" --> "Import"
3.) In the following menu select "Maven" --> "Existing Maven Projects"
4.) Select the extracted "webapp" folder and click "Finish"

### Configure application

Before you can start the application please set up the MariaDB database with the database schema.
Afterwards, please open the "application.properties" file within eclispe (found under src/main/resources) and edit the database and tomcat configuration to match your environment.

### Run application

To start the application, right click on the "App" class found within the base package and select "Run as" --> "Java Application"

## Android App
