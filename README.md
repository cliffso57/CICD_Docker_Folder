## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
######
## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


## Warning message from git bash when running git add . command

$ git add .
warning: in the working copy of 'Docker-files/app/Dockerfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Docker-files/db/Dockerfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Docker-files/web/Dockerfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'docker-compose.yml', LF will be replaced by CRLF the next time Git touches it
