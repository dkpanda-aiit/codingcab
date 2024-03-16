This is a sample Spring Boot REST API project to demonstrate adding/getting employee data :-

Requirement
---------------
We have to design a RESTful service using SpringBoot to facilitate adding Employee, getting employee data based on ID, updating employee data based on ID and deleting employee data based on ID

Steps
-------
1) Visit https://start.spring.io/ site to generate SpringBoot initializer application
2) Select Project type as "Maven", choose SpringBoot version "3.1.9" and language as "Java" 
3) Enter Project Metadata as below :-

Group/package name  	: com.isl
Artifact 	Id						: rest
Name 							: RestDemo
Description					: My RESTful Demo project for Spring Boot
Package name				: com.isl.rest

4) Select Packaging as  "Jar" or "War"

5) Add dependency as "Spring Web" to enable REST api related jars in maven dependency
4) Select any java version "17" or "21", later we can change the version in pom.xml after download

7) Click on Generate button and download the sample project as zip file
8) Go to your download location, copy the zip ,  paste in your Workspace location and unzip it
 
9) Open this project by importing in your InteliJ Idea application

10) After import, use Maven - clean and install

11) Run your project and test using SOAPUI or Postman


A) Adding employee data using Post : http://localhost:8080/EmpService

Employee1 data
------------------
{
   "id": "101348",
   "name": "Nagarajan",
   "desig": "Soft Engg"
}

Employee2 data
------------------
{
   "id": "43884",
   "name": "Deepak",
   "desig": "Deepak"
}
	
B) Getting employee using Path Param URL : http://localhost:8080/EmpService/43884

C) Getting employee using Query/Request Param URL : http://localhost:8080/EmpService?id=43884
