
# PCTO Management Documentation
---

## Team 5

### March 08, 2020

#### Team Members

Bryan Imaralu

Giovanni Gottardi

Edoardo Gruia

Nicolò Salaorni

## Revision History

|Version|Date|Name|Description|
| ----- | -- | -- | - |
|1|25/01/20|Edoardo Gruia|Initial Document|
|2|01/02/20|Edoardo Gruia Bryan Imaralu Nicolò Salaorni Giovanni Gottardi|Starting the ETL process
|3|08/02/20|Edoardo Gruia Bryan Imaralu Nicolò Salaorni Giovanni Gottardi|Optimization of the code and start looking for some idea of the web site|
|4|15/02/20|Edoardo Gruia Bryan Imaralu Nicolò Salaorni Giovanni Gottardi|Starting the web site and some documentation|
|5|22/02/20|Edoardo Gruia Bryan Imaralu Nicolò Salaorni Giovanni Gottardi|Almost complete the web site|



## Introduction

In this project our team have to do a site, for the students and for the teachers, that they need to search a company to go to work for the PCTO activity. In the first part we make a login part that is connected to the web spaggiari and if you have an account there you are allowed to join to our site. In the second part you can choice your company and search it by multiple filters.

## Login

When you go for the first time to the site you have to put your email and password connected to web spaggiari and so you can log into the site. In the program we do a connection with our site and with this [link](https://web.spaggiari.eu/services/ws/wsExtAuth.php?wsdl) that check the username or the email to verify if they are correct. Is a database that contain all the information of login for web spaggiari Classeviva.  

## Default page

The default page is formed from all the companies that the previous students where went with the various information about it for examples the name, where is it, the mail, the number, the site, the subject that you study/work there and finally the type of company.

In the top of the page there are the filter that are: name, city, ditrict, subject and type of company. Here you can choose what you want and later press in the top-left side search, now you have your researches.

## How to open the site? (for now)

### Required Programs

To run the site, you have to install XAMPP, once time you have it open the panel control of it. Later you can open phpMyAdmin to install the database on it so now you can see the companies. And finally import the database.

Steps to do

Launch **XAMPP** control panel

1. Press start on **Apache** and on **MySql**
* 1.2 Go on Apache’s config and press on **php.ini**
* 1.3 Once time the file is open you have the remove the “;” where it is written “**extension=php_soap.dll**”
* 1.4 Now you can log on the site

2. Go to phpMyAdmin
* 2.1 Create a new database
* 2.2 Select import and choose the database     “anagrafica_pcto”

3. Put all the files in this following path: “C:\xampp\htdocs”

4. Digit on your browser “localhost” and select the folder “anagrafica_PCTO”

5. Finally you have the access to the site, log in!
