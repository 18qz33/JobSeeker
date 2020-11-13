# JobSeeker
## Background
JobSeeker is a Java and AWS based job recommendation engine. The system can be used to browse job positions based on the user’s current city and history records. Tradional recommender engines cannot satisfy users' requirements; for example, an e-commerce recommender might recommend products that the user only need once but never need again or recommend video games to an old man because he uses his grandchild's account, etc. That is why this recommender engine will be needed by users. 
## Demo
https://drive.google.com/file/d/1xDddkgrBZEaLs8S0fixseQESK0KXsCWb/view?usp=sharing
## Install
The project uses Tomcat Server and Java EE. Go check them out if you don't have them locally installed.   
Step 1: Open Eclipse Download page: https://www.eclipse.org/downloads/ to download the JavaEE based on your OS.   
Step 2: Open the Tomcat official download page: http://tomcat.apache.org/download-90.cgi to install the Tomcat server.  
Step 3: Add the project to Tomcat server and start; use the following link to view.
```sh
http://localhost:8080/jupiter
```
## Description
The front-end UI design was performed using AJAX technology and three servlets were created to handle HTTP requests and responses so that real job data can be obtained from the GitHub server. The first servlet is a SearchItem API that provides the functionality to search around. The second servlet allows a user to set or unset their favorite records. The third servlet recommneds similar positions to the user. The three servlets were deployed on tomcat. A content-based recommendation algorithm was designed to improve the recommender system accuracy by extracting keyword from job descriptions through MonkeyLearn API and comparing with the user’s history records. A MySQL database was built on Amazon RDS and the project was deployed to Amazon EC2 to increase engine scalability.
