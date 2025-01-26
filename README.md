# Cloud-Infrastructure-as-Service-Basics
***DevOps - Techworld-with-nana***

***Demo Project***
Create server and deploy application on DigitalOcean

***Technologies used***
 DigitalOcean, Linux, Java, Gradle

## Project Description
###Setup and configure a server on DigitalOcean###
 - [x] set up Droplet on DigitalOcean
 - [x] ssh keys root user
 - [x] set up of firewall my-first-droplet-firewall
 - [x] successfully remote sshed to root user

 ### Security best practice
 ***Create and configure a new Linux user on the Droplet***
  - [x] created user java
  - [x] ssh keys java user
 
 ### Deploy and run a Java Gradle application on Droplet 
 - [x] deployed _java_
 - [x] deplyed _gradle_
 - [x] scp of jar file to java user home/java/java-react-example.jar
 - [x] changed ownership of jar file to user:group java:java
 - [x] ran application as java
 - [x] `ps aux | grep java` to identify process ID and tcp port to open
 - [x] setup of firewall rules
 - [x] Successfully connected to https://x.x.x.x:7071
