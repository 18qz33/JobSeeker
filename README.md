# JobSeeker
## Background
JobSeeker is a Java and AWS based job recommendation engine. The system can be used to browse job positions based on the user’s current city and history records. The front-end UI design was performed using AJAX technology and three servlets were created to handle HTTP requests and responses so that real job data can be obtained from the GitHub server. A content-based recommendation algorithm was designed to improve the recommender system accuracy by extracting keyword from job descriptions through MonkeyLearn API and comparing with the user’s history records. A MySQL database was built on Amazon RDS and the project was deployed to Amazon EC2 to increase engine scalability.
## Demo
https://drive.google.com/file/d/1xDddkgrBZEaLs8S0fixseQESK0KXsCWb/view?usp=sharing
## Install
This project uses Tomcat Server and Java EE. Go check them out if you don't have them locally installed.   
Step 1: Open Eclipse Download page: https://www.eclipse.org/downloads/ to download the JavaEE based on your OS.   
Step 2: Open the Tomcat official download page: http://tomcat.apache.org/download-90.cgi to install the Tomcat server.  
Step 3: Add the project to Tomcat server and start; use the following link to view.
```sh
http://localhost:8080/jupiter
```
## Description
