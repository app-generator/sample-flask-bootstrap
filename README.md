# How to use Bootstrap with [Flask](https://appseed.us/admin-dashboards/flask/)

Open-source [Flask](https://appseed.us/admin-dashboards/flask/) project enhanced with session-based authentication via `Flask-Login` and a simple UI powered by `Bootstrap`. For newcomers, Flask is a popular web framework used to code from simple one-page websites to complex eCommerce solutions and Bootstrap is the most popular JS/CSS framework.  

<br /> 

## Features

> `Have questions?` Contact **[Support](https://appseed.us/support/)** (Email & Discord) provided by **AppSeed**

| Free Version                          | [PRO Version](https://appseed.us/product/pixel-bootstrap-pro/flask/)          | 🚀 Custom - $3,999         |  
| --------------------------------------| --------------------------------------| --------------------------------------|
| ✓ **Bootstrap 5**                         | **Everything in Free**, plus:                                        | **Everything in PRO**, plus:       |
| ✓ Flask-Login                             | ✅ **Premium Bootstrap 5 Design**                                    | ✅ **1mo Custom Development**     | 
| ✓ Session-based Authentication            | ✅ `Auth` Provided by **Flask-Security-Too**                         | ✅ **Dedicated Developer**        |
| -                                         | ✅ `Extended User Model`                                             | ✅ Weekly Sprints                 |
| -                                         | ✅ `Users Roles`                                                     | ✅ Technical SPECS               |
| -                                         | ✅ `Private REPO Access`                                             | ✅ Documentation                  |
| -                                         | ✅ **PRO Support** - [Email & Discord](https://appseed.us/support/)  | ✅ **30 days Delivery Warranty**  |
| -                                         | ✅ Deployment Assistance                                             |  -                                 |
| -                                         | -                                                                     |  -                                 
| ---------------------------------         | ---------------------------------                                     | ---------------------------------  |
| ✓ [LIVE Demo](https://flask-pixel-lite.appseed-srv1.com/)  | 🚀 [LIVE Demo](https://flask-pixel-enhanced.onrender.com/) `PRO` | 🛒 `Order`: **[$3,999](https://appseed.gumroad.com/l/rocket-package)** (GUMROAD) |   

![Flask User Authentication - Free sample provided by AppSeed.](https://user-images.githubusercontent.com/51070104/134959525-3ad0c71c-27e4-45f7-b7b9-53b76f3884bf.png)

<br />

## Build from sources

> 👉 **Step #1** - Clone sources (this repo)

```bash
$ git clone https://github.com/app-generator/sample-flask-bootstrap.git
$ cd sample-flask-bootstrap
```

<br />

> 👉 **Step #2** - Create a virtual environment

```bash
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
```

<br />

> 👉 **Step #3** - Install dependencies

```bash
$ # Install requirements
$ pip3 install -r requirements.txt
```

<br />

> 👉 **Step #4** - Set Up Environment

```bash
$ # Set the FLASK_APP environment variable
$ (Unix/Mac) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
```

<br />

> 👉 **Step #5** - Create Tables (SQLite persistance)

```bash
$ # Create tables
$ flask shell
$ >>> from app import db
$ >>> db.create_all()
```

<br />

> 👉 **Step #6** - (optional) Enable DEBUG Environment (local development)

```bash
$ # Set up the DEBUG environment
$ # (Unix/Mac) export FLASK_ENV=development
$ # (Windows) set FLASK_ENV=development
$ # (Powershell) $env:FLASK_ENV = "development"
```

<br />

> 👉 **Step #7** - Start the project

```bash
$ # Run the application
$ # --host=0.0.0.0 - expose the app on all network interfaces (default 127.0.0.1)
$ # --port=5000    - specify the app port (default 5000)  
$ flask run --host=0.0.0.0 --port=5000
$
$ # Access the app in browser: http://127.0.0.1:5000/
```

<br />

## Code-base structure

The project has a super simple structure, represented as bellow:

```bash
< PROJECT ROOT >
   |
   |-- app/
   |    |-- static/
   |    |    |-- <css, JS, images>    # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |    |    |
   |    |    |-- index.html           # Index File
   |    |    |-- login.html           # Login Page
   |    |    |-- register.html        # Registration Page
   |    |    
   |    |
   |   config.py                      # Provides APP Configuration 
   |   forms.py                       # Defines Forms (login, register) 
   |   models.py                      # Defines app models 
   |   views.py                       # Application Routes 
   |
   |-- requirements.txt
   |-- run.py
   |
   |-- ************************************************************************
```

<br />

## Resources

- Free [Admin Dashboards](https://appseed.us/admin-dashboards/open-source) - index provided by AppSeed
- [Flask User Authentication](https://blog.appseed.us/flask-user-authentication-free-sample/) - blog article
- [Flask Social Login](https://blog.appseed.us/flask-social-login-with-github/) - blog article (includes a free sample)

<br />

---
How to use Bootstrap with [Flask](https://appseed.us/admin-dashboards/flask/) - Free sample provided by **[AppSeed](https://appseed.us)**.
