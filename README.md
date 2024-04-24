####
### Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

### Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
### Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql
  >
docker run -p 8080:8080 -p 50000:50000 -v /your/home:/var/jenkins_home jenkins/jenkins
docker run -d -p 8081:8081 --name nexus sonatype/nexus3
docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube
  


