# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊


All credit to Devopshak @ aditya Jaiswal for providing this boardgame code 

I have cloned it to my RHEL 

to set it up 

1. install Java -> dnf install java or to be specific for this project install java-11-openjdk

2. install maven -> dnf install maven -y

3. clone this repo -> git clone https://github.com/Dhvanya-Shah/Boardgame-local.git

4.compile ->  mvn compile 

5. test -> mvn test (run from target folder )

6. package -> mvn package

7. change directory to target folder -> cd target/

8. run .jar file -> java -jar database_service_project-0.0.7.jar

9. output
  <img width="1590" height="827" alt="image" src="https://github.com/user-attachments/assets/2886ada0-4773-4e11-b490-8041d104b759" />



10. make sure port 8080 is listening on server to check use nmap -sT -O localhost  -> it should provide you list of all open ports on server , look for port 8080/tcp

11. opent it on you browser -> "serverip":8080 

Thank you 





