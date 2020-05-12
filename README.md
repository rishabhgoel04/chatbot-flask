Rule Based Chatbot flask
===================

This repository contains the code for chatbot. I have developed this chatbot using template based approach.

## Dependencies

In oreder to run this you need the following libraries.

* flask
* flask_cors
* json
* os
* flask_pymongo
* pytz
* datetime
* uuid

## Installation

* OS, json, datetime and uuid are default python libraries


* Install Flask libraries using following commands:
```bash
 $ sudo pip install Flask==1.1.2
 $ sudo pip Flask-Cors==3.0.2
 $ sudo Flask-PyMongo==3.10.1
```
* Installlation of pytz library
```bash
 $ sudo pip install pytz==2020.1
```


* Install MongoDB NoSQL db 


```
 ## usage
1. First run `flaskengin.py` 

2. Go to the URL: 

3. `http://localhost:5002/` where you can see Hello from chatbot Flask! 

4. You can see the chatbot JSON response by using this URL: 
```http://localhost:5002/welcomemsg_chat```

5. After that you can hit the following urls
  ```
  http://localhost:5002/hi_chat?msg=Hi
  http://localhost:5002/asking_borowers_full_name?msg=<your name> 
  http://localhost:5002/asking_borowers_email_id?msg=<Your email address>
  ```
 
