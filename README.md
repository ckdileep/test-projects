** Build Instructions**
* Run mvn clean install
* war file (demo-0.0.1-SNAPSHOT.war) will be generated in target folder
* Deploy war in tomcat
* Run following in browser
1. http://localhost:8080/demo/users -  
returns all users
2. http://localhost:8080/demo/users/1
    returns details of a single user
3. web.xml with BASIC authentication is provided in jersey-springboot-demo\src\main\webapp\WEB-INF\ folder. User will have to be defined in tomcat-users.xml
Customized from https://howtodoinjava.com/spring-boot/spring-boot-jersey-example/.
