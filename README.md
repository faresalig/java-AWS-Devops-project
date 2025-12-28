<img src=imgs/cover.png>

# Enterprise Java Web Application with Complete CI/CD Pipeline:
 Developed and deployed a full-stack Java application using Spring MVC, Spring Security, and MySQL, implementing automated testing, code quality analysis with SonarQube, and containerized deployment to AWS EKS using GitHub Actions, Docker, and Helm charts.

## End-to-End DevOps Implementation:
 Built a comprehensive DevOps pipeline featuring automated testing, static code analysis, Docker containerization with AWS ECR, and Kubernetes deployment on EKS, demonstrating proficiency in modern cloud-native development and deployment practices.

Cloud-Native Application Deployment: Orchestrated complete application lifecycle management from code commit to production deployment using GitHub Actions, AWS services (ECR, EKS), and infrastructure as code principles with Helm for scalable container orchestration.
# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql
