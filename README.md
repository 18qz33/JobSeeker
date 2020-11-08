# JobSeeker
## Background
JobSeeker is a Java and AWS based job recommendation engine. The system can be used to browse job positions based on the user’s current city and history records. The front-end UI design was performed using AJAX technology and several servlets were created to handle HTTP requests and responses so that real job data can be obtained from the GitHub server. A content-based recommendation algorithm was designed to improve the recommender system accuracy by extracting keyword from job descriptions through MonkeyLearn API and comparing with the user’s history records. A MySQL database on Amazon RDS was built and the project was deployed to Amazon EC2 to increase engine scalability.
