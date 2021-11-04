# The Hood

>[rashidaysher](https://github.com/rashidaysher)  
  
# Description  
Tis is a neighborhood where one gets to know what goes on in his/her neighbourhood. You can be able to get all the businesses listed at the and all the contacts of polce depertments in your area



##  Live Link  
 Click [View Site](https://hood-3590.herokuapp.com/account/login/)

 
## User Story  
  
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
https://github.com/rashidaysher/My-hood
```
##### Navigate into the folder and install requirements  
 ```bash 
cd HoodWatch 
```
##### Install and activate Virtual  
 ```bash 
-pipenv shell
```  
##### Install Dependencies  
 ```bash 
 pipenv install 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations hood
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
 
## Technology used  
  
* Python3.6
* Django 2.2.6
* Heroku
  
  
## Known Bugs  
*  none currently
  
## Contact Information   
If you have any contributions, send a pull request at[rashidaisha.ara@gmail.com]  
  
## License 


* Copyright (c) 2021 **Aisha Rashid**