
/**************************************************************
Project Name: Rating Widget CFC
Project Author: Gary Gilbert
Project Description: A cfc that wraps the creation of the Spry Rating Widget
Project Version: 1.0
**************************************************************/

Intallation Instructions:

1) Run the ratingTables.sql file against your MYSQL database
2) copy the rating.cfc and ratingtest.cfm to a directory under your webroot
3) make sure you have downloaded spry 1.6.1 and copied the resources  under your webroot
4) edit the ratingTest.cfm page to make sure the path to your spry recources is correct.
5) add a request.dsn attribute to your application.cfm page that points to your database or change the value in the cfc to be your own datasource 
6) browse to the location of the ratingsTest.cfm and be amazed!