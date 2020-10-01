1. Introduction
	1.1 Problem Statement: In this project we aim to build a system which will help the farmer to take decision about growing a particular kind of crop according to the air quality index of that region and the season. In this work we will be using web-scrapping to scrape the different attributes required to measure the air quality over that region then we will apply machine learning to understand that which kind of crop should be grown according to AQI and the local season. The user just needs to open the application and we’ll get the user’s location from the IP address used to access the system. This system can be really helpful to make farmers understand that exactly which crop can give them maximum profit.

	1.2 Importance: The main importance of this work is to help the farmers to clearly understand about the type of crop grown in that particular region according to the local season and the local AQI (Air Quality Index). We can achieve our aim by using our knowledge of Machine Learning and Internet of Things.

2. Overview and Planning
	2.1 Proposed System Overview: 
In this project we propose a system which will help the farmer to understand that which type of crop should be grown according to the season or local air AQI. We will be using Machine Learning algorithms to give a decision. The local AQI will be analyzed with the help of WSN. It observes many attributes of the air which defines the AQI of that local region. 

	2.2 Challenges:
The major challenge which we see in this work the effect of birds and animals on WSN. Our major work and analysis are done because e is getting the data from WSN but if they don’t work well than our results and predictions may lead to false results which may result to heavy loses to farmers.
	2.3 Assumptions:
There are several assumptions we have made like which type of crop is best for which type of environment. Obviously, it is not 100% accurate system but we are trying to implement a system with more than 90% accuracy. 
	2.4 Architecture Specifications:
Different WSN are installed at different locations around the country and that will send the data to the cloud where the data analysis and machine learning algorithm is applied to give a result.
	2.5 Hardware Requirements:
WSN, Internet Connection, Cloud Infrastructure.
	2.6 Software Requirements:
Numpy, Pandas, Jupyter Notebook

3. IoT Design Methodologies 


Step 1: Purpose and Requirement Specification
Purpose: To implement smart irrigation system which will suggest the farmer which type of crops should be grown in a particular region
Behavior: Applying machine learning to tell the farmer the type of crop soiled or manually entertaining the request
Data Analysis: The data analysis should be done in the cloud
Application Deployment: The application should be deployed on cloud 
Security Requirement: Only the authentication for the admin is required. Rest anybody the use the system


Step 2: Process Specification
           

Step 10:
 











4. Implementation (30%- 50%) with source code and sample output


Datasets
 
Dataset having the suitable air quality range for crop production

 
Dataset having the parameters affecting the air quality


T	Average annual temperature
TM	Annual average maximum temperature
Tm	Average annual minimum temperature
PP	Rain or snow precipitation total annual
V	Annual average wind speed
RA	Number of days with rain
SN	Number of days with snow
TS	Number of days with storm
FG	Number of foggy days
TN	Number of days with tornado
GR	Number of days with hail

Description about the parameters
Predicting PM 2.5 value using Machine Learning Multiple Linear Regression Algorithm

 

 

 


Predicting best suitable crop on the basis of location and air quality for the farmer 

 

 

 

