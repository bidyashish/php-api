# php-api
Basic and simple  PHP API RESt to accept only POST Request and store in MySql Database

This is simple PHP REST  Server to handle only POST request .

END Point url will be  http://localhost/api/api1.php

or http://yoururl.com/api/api1.php
It uses MySql database to Handle and store all Incoming Json to Database.

Post JSON  Format will be like:

  {
  "user_id":90,
  "male":89,
  "female":8
  }
  
  and in  response we will get 
  
  {
    "success": 90
  }
  
  We can Test Rest Server using Postman Application or using  Curl 
  
  Use Git BASH to test curl in Windows as CMD can't Handle  single Quotes.
  
  curl Command is like:
  
   curl -H "Content-Type: application/json" -X POST -d '{"user_id":40255,"male":445,"female":86}' http://localhost/api/api1.php;
   
   

  
  


