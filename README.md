Objective : 
The primary goal of this task is to implement the backend and API layers for the following
features:
1. Authentication API's (Login / Signup / Logout)
2. Users (CRUD)
3. NEWS (CRUD)


setup instructions: 
 
*Prerequisites :
 - JDK (Java Development Kit ) with version 11
 - MySQL workbench 

*Setup Instructions:
- Extract Project from  zip file
- Open the Project in an IDE (example : Spring Tool Suite (STS) IDE (I used it ) ,  IntelliJ IDEA )
- Build the Project (clean install then update maven)
- Run the Application as springboot application
- Access the Application USeing URL : http://localhost:8080
    EX: http://localhost:8080/v1/apps-wave/news
-create  database with name : appswavedb; in Mysql usong : create Database appswavedb;

API Documntaion :
I have used Swagger for API documntaion Kindly follow :
 http://localhost:8080/swagger-ui/index.html

Additinal Info  :
* Automatic soft deletion of news items if they exceed the publish date while occured every mid night
* I have added new table with name tbl_news_approvel to achive approvel request for approved news from content writer to admin
* I have added UserController with APIs for futcher use 
* I have added pending_deletion_approve_Request get API in News Controller to retrive waiting deleteion News by admin .
* I have added Inspector for logging
* database connection properties in application.properties file
