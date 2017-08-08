# Objective of the project
This web app aims to help farmers by predicting the suitability of weather for a particular crop and giving them prior information.
We are predicting the weather of 15 days with the help of API and Algorithms .We are using these predictions to tell suitability of weather for the crops and notify farmers about the same.
A farmer can register in our website ,choose a crop and start receiving the messages about the various weather conditions related to stages of crop. 
The messages will consist of topics like “When to sow seeds? ”,  “How to manage the vegetative phase?”,  “How much water do they need from outer sources in case of inadequate rainfall? ”.
A non-registered user can see everything on our website but will not get messages.

#   Technology Stack:
•	Nasa WebWorldWind
•	R
•	HTML,CSS and its frameworks
•	Javascript
•	JSP
•	Java


•	We have used dark sky API for current weather information.
•	For historical weather data, we have used weather underground API.
•	For tracking the location of farmer,Google Api is used.
•	For SMS, we have used Textlocal api.



# How to Deploy the project?
Create database farms and and create all the tables that are in database.sql 
As the algorithm is implemented in R and we need to connect it with Java web project ,we have included Rserve.jar, Rengine.jar and JRI.jar in tomcat lib directory. 
Then, In R shell,run the library(Rserve) ,then execute the Rserve() cmd.This starts R server which will let you you use R written code in Java.
Server is TomCat version 7.0.78
Import the project in eclipse and run the project through server.

No need to signup if u don't want to get messages.All the pages are accessible to non-registered user.


Full documenatation can be seen here.
https://github.com/prasanthaitha/nasaeuropachallenge2017/blob/master/Documentation.pdf


You can find video tutorial and other descriptions here:
https://farmsntech.github.io/

