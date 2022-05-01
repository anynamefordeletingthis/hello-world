# Hello Flask

## To run

### set variables

set FLASK_APP=hello
set FLASK_ENV=development 

> This will run hello.py file as app, by default it runs app.py, there are two environments, development and production.

### run 

`python -m flask run`

-p for port

## using HTML templates

Flask uses jinja template engine.

## How to create a virtual environment

### install virtualenv

`pip install virtualenv`

### create a virtual environment

`python3 -m venv venv`

### activate virtual environment

`venv\Scripts\activate`

then install required libraries(eg flask)