# Election-System
Online Election System - Developed  and built this system using Python , Flask , HTML , CSS and MySQL. 



 

## Steps to setup database  

1.Create Database in MySQL

```bash
  CREATE DATABASE database_name;
  USE database_name;
```

2.Copy the biometric.sql file path from sql folder and execute this command:

```bash
  SOURCE path;
```
- Tip : Enter \ while entering the path in source command.

3.Change MySQL username and password as per your MySQL installation

- Open `app.py` file.
- change `app.config['MYSQL_DATABASE_USER']` and `app.config['MYSQL_DATABASE_PASSWORD']`  properties as per your mysql installation.

## Steps to run the project

1.Install this packages  
- Flask                  
- Pillow                 
- PyMySQL                
- opencv-python
- flask-mysql
- mysql-connector-python

## Run the app

- Open terminal and run this command 
```
 flask run --no-reload
```
The server will start on port `5000`



   
    

