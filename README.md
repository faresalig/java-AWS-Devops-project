<img src=imgs/cover.png>

Designed and implemented enterprise CI/CD pipeline using GitHub Actions for Java Spring Boot application, integrating Maven builds, JUnit testing, SonarQube code quality analysis, and automated Docker containerization with AWS ECR registry.

Orchestrated production-ready Kubernetes deployment on AWS EKS using Helm charts and Infrastructure as Code practices, enabling zero-downtime deployments with automated scaling and rollback mechanisms.

Established comprehensive DevSecOps workflow with quality gates, security scanning, and monitoring integration, achieving 95% deployment success rate and reducing release cycles from weeks to hours.
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
