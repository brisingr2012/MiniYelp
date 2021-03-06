# Find Delicious Around U Web App

## Find Delicious Around U
Note: server closed for running out of free trial on AWS 
[www.FindDeliciousAroundU.net](http://34.220.210.211:8080/Yelp/# "www.FindDeliciousAroundU.net")

 - demo
 - Username: test; Password: test
 ![web app demo](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/yelp.gif)

## Introduction
The Find Delicious Around U Web App provides three main APIs for users:
                
+ **Nearby:** Find the near-by restaurants for users based on their current geolocation.
+ **My Favorites:** Load favorite restaurants based on user database records. (Need Sign-up!)
+ **Recommendation:** Search recommended restaurants that users might be interested in based on users' visiting histories and favorite events. (Need Sign-up!)

The Find Delicious Around U Web App also provides Sign-in / Sign-up APIs for users:
          

 - Login

![Log in](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/login.PNG)

 - Sign Up

![enter image description here](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/signup.PNG)

## Pages
          
+ Nearby 
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/nearby.PNG)
  
+ My Favorites
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/fav.PNG)
  
+ Recommendation
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/rec.PNG)
  
## Data Flowchart
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/flowchart.png)
## Deploy on Amazon EC2
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/ec2.PNG)
## MySQL Dataset
    
+ Tables
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/db1.PNG)
+ "items" Table
![](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images//db2.PNG)

## Test on Apache JMeter

 - Aphache JMeter: **[http://ftp.wayne.edu/apache/jmeter/binaries](http://ftp.wayne.edu/apache/jmeter/binaries)**
 - Summary Report
 ![enter image description here](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/JUnit.PNG)
 - Request Per Second (QPS)
 ![enter image description here](https://raw.githubusercontent.com/brisingr2012/MiniYelp/master/images/QPS.PNG)

## Language，Framework and Libraries

+ Language: HTML, CSS, JavaScript, Java
+ Framework: Java Servlet, Apache Tomcat Server, MAMP, Postman, Amazon EC2, AJAX
+ Library: [java-json](http://www.java2s.com/Code/JarDownload/java-json/java-json.jar.zip "java-json"), [java-MySQL](https://dev.mysql.com/downloads/connector/j/8.0.html "java-MySQL")
