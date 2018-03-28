# assesement_test

## Getting Started

These instructions will get you a copy of the project up and testing on your local machine.

#### Setting up database in properties files
###### Open resources/application.properties and replace your mysql database, user and password according to your system

	spring.datasource.url=jdbc:mysql://localhost:3306/<database>
	spring.datasource.username=<username>
	spring.datasource.password=<password>	

##### Execute the following command to run application
	`java -jar chart-1.0.war`

######  Open Application in browser
	http://localhost:8080/
