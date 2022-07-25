# Multiple Language Website in PHP & MySQL (English, Nepali, Chinese)
This is a simple blog website which supports multi-languages (english, nepali and chinese). This is just for educational purpose (not for commercial use).
This is an Open Source Project, So feel free to explore (use) in any ways you like.

## Technologies Used
1. HTML5
2. CSS3
3. PHP (OOP)
4. MySQLi 


## Features
1. Categories Manager
2. Posts Manager
3. Users Manager
4. Secure Login in Multiple Languages

# Supported Languages
1. English
2. Nepali
3. Chinese

## Instructions to Use

### Pre-Requisites:

1. Download and Install XAMPP

[Click Here to Download](https://www.apachefriends.org/index.html)

2. Install any Text Editor (Sublime Text or Visual Studio Code or Atom or Brackets)

### Installtion

1. Download as as Zip or Clone this project
2. Extract and Move this project to Root Directory
```
Local Disc C: -> xampp -> htdocs -> 'this project'
```
*Local Disk C is the location where xampp was installed*

3. Open XAMPP Control Panel and Start 'Apache' and 'MySQL'

4. Extract and Import Database

a. Open 'phpmyadmin' in your browser
b. Create a Database ('phpblog')
c. Import the SQL file provided with this project ('phpblog')

5. Make Changes to settings

Go to 'admin' folder then'config' folder and Open 'constants.php' file. Then make changes on following constants
```php
<?php 
//Start Session
session_start();

//Create Constants to save Database Credentials
define('LOCALHOST', 'localhost');
define('USERNAME', 'root'); //Your Database username instead of 'root'
define('PASSWORD', ''); //Your Database Password instead of null/empty
define('DBNAME', 'phpblog'); //Your Database Name if it's not 'mlb2018'

define('SITEURL', 'http://localhost/phpblog/'); //Update the home URL of the project if you have changed port number or it's live on server

?>
```

6. Now, Open the project in your browser. It should run perfectly.


## CMS - Admin Panel
This is a very simple Content Management System (No advanced stuffs). 

**Instructions to use**
1. Go to the link -> yourhomeurl/admin  
>e.g. *http://localhost:81/phpblog/admin*
2. Login with the Username and Password 
>*[Username: admin, Password: admin]*
3. Hola! You're logged in. Now you can manage categories, posts and users.

## For Sponsor or Projects Enquiry
1. Email - neurake7@gmail.com

## Follow Me on
1. LinkedIn - [vijaythapa](https://www.linkedin.com/in/neurake/ "Vishal Thombre on LinkedIn")
2. Instagram - [@vijaythapa.code](https://www.instagram/neurake7/ "Vishal Thombre on Instagram")
5. Twitter - [@thevijaythapa](https://www.twitter.com/neurake7 "Vishal Thombre on Twitter")


