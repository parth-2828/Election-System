# Election-System
Online Election System - Developed this system using Python , Flask , HTML , CSS and MySQL. 

![Candidate_reg](https://user-images.githubusercontent.com/73604763/186624023-8e904a24-354b-4801-96ee-66c9ccf45963.png)

![image (1)](https://user-images.githubusercontent.com/73604763/186626386-08f725dd-c575-478b-a56c-8750e7452d66.png)

![image (8)](https://user-images.githubusercontent.com/73604763/186628717-be1c86b9-fdac-4ac8-8f6b-4d008c2de098.png)

![image](https://user-images.githubusercontent.com/73604763/186626134-da86f37f-f356-466a-8d70-22f1f682c6c6.png)

![image (6)](https://user-images.githubusercontent.com/73604763/186627821-401de6c2-118d-4e1a-9b6c-aa73710ee9d0.png)

![image (5)](https://user-images.githubusercontent.com/73604763/186627830-590bb386-6e4e-4e80-9745-c859a5541595.png)

![image (4)](https://user-images.githubusercontent.com/73604763/186627838-8c59ef10-7c2c-4b7b-ab39-7117fd1a65f4.png)

![image (7)](https://user-images.githubusercontent.com/73604763/186628240-ee3aba8c-027f-4d69-9318-287bfb36b4b7.png)

![image (2)](https://user-images.githubusercontent.com/73604763/186627265-cab7cfb6-60d6-449a-b7b8-349713f22ca3.png)





 

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



   
    

