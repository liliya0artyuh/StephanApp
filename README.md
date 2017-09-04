# StephanApp

This example is based on the following original sample: https://tests4geeks.com/spring-data-boot-mongodb-example/
the original was modified first by this example: https://github.com/liliya0artyuh/mongodb_heroku

to run on local comment out body in MongoLabConfiguration configuration class, and 

comment the following lines in the application.properties file:
spring.data.mongodb.database=car_dealer
spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017

uncomment the following line in the application.properties file:
<!-- spring.data.mongodb.uri= ${MONGOLAB_URI} -->
<! -- spring.data.mongodb.uri=mongodb://heroku_fmndmsf2:Centennial2016!@ds161913.mlab.com:61913/heroku_fmndmsf2 -->
