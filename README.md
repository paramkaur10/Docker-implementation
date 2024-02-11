# Docker-implementation
I created a RESTful web service using node.js and json database that run in a docker container whose image ID is in this repository . The web service contained 4 GET routes: 
The database consists of four different car companies (http://localhost:8000/companies).
Each car company in the database is defined by its manufactured cars, the name of the company and the company id (http://localhost:8000/companies/(1 – 4)).
Each company has four of its manufactured cars in the database (http://localhost:8000/companies/(1 – 4)/cars).
Each car is further defined by its specifications like Engine, Transmission, Drivetrain and price (http://localhost:8000/companies/(1 – 4)/cars/(1 - 4)).
The data returned from the web service routes is in JSON form. 

Author: Parampuneet Kaur Thind (Param)
