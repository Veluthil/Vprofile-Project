# Prerequisites

- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 

- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch

  
# Database

Here, we use MySQL DB 
SQL dump file is located at:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a MySQL dump file, so you have to import this dump to MySQL DB server in order to make the app work.
- > mysql -u <user_name> -p accounts < db_backup.sql

# App Structure

Java application is in the src/main/java directory, MySQL data is in the src/main/resources/db_backup.sql file.

# Disclaimer

Please note that this project is for educational purposes only. It's not intended for production use. 

# Acknowledgments

This project has been created by the author of the "Decoding DevOps" course, Imran Teli.


