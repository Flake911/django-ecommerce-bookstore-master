<p id ="top" align="center">
  <img src="https://github.com/YashMarmat/Pages-App-django/blob/master/templates/django bookstore logo.png" width="90%">
</p>


# Django-Ecommece-Bookstore
<p>An online bookshop developed in django-3 which allow users to purchase books online :) </p>

<img src="https://github.com/YashMarmat/Pages-App-django/blob/master/templates/dj-ecom-bstore-pic2.png?raw=true">

### Live App
* checkout the site here: <a href="https://dj-bookstore.onrender.com/" target="_blank" >Deployed App</a> (little note below)

(Note: The website can take upto 30 seconds (hosted on Render free tier services), as the project has no clients, its just for learning, please refer the source
code to run locally).

### Short Note

This guide will Step-by-Step help you to create your own ecommerce bookstore application in django. With HTML, CSS, JAVASCRIPT and Django Framework. 

Note: this guide is not for absolute beginners so im assuming that you have the basic knowledge of MVT in django to get started. To know more on it i recommend you <a href="https://docs.djangoproject.com/en/3.0/">django documentation</a>.

# Table of contents
- [About_this_App](#About_this_App)
- [Get_Started](#Get_Started)
- [Books_App](#Books_App)
  * [models](#models)
  * [migrations](#migrations)
  * [admin](#admin)
  * [server](#server)
  * [views](#views)
  * [urls](#urls)
  * [templates](#templates)
  * [logins](#logins)
- [Accounts_App](#Accounts_App)
  * [signup](#signup)
  * [signup_view](#signup_view)
  * [static_files](#static_files)
- [Paypal_payment_process](#Paypal_Payment_Process) 
  
<hr>

## About_this_App
A Beautifully designed Online Bookstore which contains multiple Books, the site allows you to search your favourite book in the bookstore, i didnt added too many book in database for now, but you can customize the site the way you like with the help of the source code present in this repository. You can purchase any book you like by two payment methods the first option is of paypal and the other one is debit card, use the sandbox paypal account please :)

Also, before purchasing any book you will be redirected to the login or signup page. So that new users can signup on the site and then can buy their favourite book. The site also informs which book is available and which one is out of stock !.

## Get_Started

I'm assuming that you are already done with setting up virtual enviornment in your system. Ok, now lets move to a location where we can store this project by using terminal or command prompt in windows. In my case im at this location,

~/Documents/django_project/$ 

* Now Setup the virtual environment

$`pipenv shell`

$`pipenv install django==3.0`



if you ran into some issues at some point please let me know. Go to issues section of this repository put your problems there. I'll answer them as soon as possible or email me for any feedback --> Aymenmajid911@gmail.com

<p><a href="#top">Back to Top</a></p>



