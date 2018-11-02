# Login-Panel-Demo
Android login-register panel with mySql and PHP

## Description

This is a simple login-registration panel developed in Android with Volley library and PHP & MySql.
This project is created with MAMP and Android Studio. To run this project you need these dependencies below.

## Dependencies

* Apache server
* mySQL
* PHP
* MAMP/WAMP server
* Android studio
* Volley library

### Installation

**To run the project, you need to open Apache, mySql and MAMP servers.**

##### Android

On Android Studio, you need to implement; 
'com.android.support:design:28.0.0' for the design and
'com.android.volley:volley:1.1.0' for the Volley Library.

##### PHP

On phpMyAdmin, create a structure name 'users'. Under the users, create a table name 'users_table' which contains 4 columns.

First columns name is 'id' which is a type of int. You need to check AUTO_INCREMENT. Set the index to PRIMARY.
Second colums name is 'name' which is a type of varchar of value 30. (utf8_general_ci)
Third colums name is 'email' which is a type of varchar of value 50. (utf8_general_ci)
Fourth colums name is 'password' which is a type of text.  (utf8_general_ci)

##### MAMP

Under the your localhost folder (In my case it is /Applications/MAMP/htdocs) put the android_register_login folder on it.

Set the URL_REGIST on Android Studio, http://yourlocalipaddress/android_register_login/register.php and
http://yourlocalipadress/android_register_login/login.php.

Based on your MAMP server PORT, add or delete :8888 port at the end of your 'yourlocalipaddress'.
