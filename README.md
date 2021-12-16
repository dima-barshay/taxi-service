# Taxi Service
This project describes the work of the taxi service</br>
###Using it you can do the following:
![image](http://joxi.ru/krDdxkETGEJe6r.jpg)
#### There are also authorization and registration stages, which you have to pass to access these options
### Implementation details:
Project based on famous 3-layered architecture:
1. Presentation layer (controllers)
2. Application layer (service)
3. Data access layer (DAO)
### Technologies:
* Maven
* Apache Tomcat
* Servlet
* JDBC
* MySQL
* HTML, CSS
* log4j
* JSTL
* JSP
### Setup
1. Install and configure Apache Tomcat
2. Install and configure MySQL & MySQL Workbench
3. Run script from the resources/init_db.sql file in the Workbench.
4. In src/main/java/taxi/util/ConnectionUtil replace URL, USERNAME and PASSWORD with your data
5. Replace "PATH TO" your with absolute path to your log file in log4j2.xml
6. Change the absolute path to checkstyle.xml in pom.xml
7. Run with Tomcat
