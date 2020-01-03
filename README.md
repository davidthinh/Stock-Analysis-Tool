# Stock Analysis 

## Final Project Screencast 


[![Final Project Screencast](https://i.imgur.com/1aLX0P8.png)](https://youtu.be/wwDwdlkuKfA)


## Description
Stock Analysis provides an analysis tool which helps users to analyze stocks data more quickly and easily. Users can analyze the daily stock prices,the risk and return and how daily prices between competitive stocks correlate with one another in their porfolios. Below is a summary of all features in the web app. 

- Correlation Analysis 
- Risk and Return Analysis 
- Current Market Information
- Daily Price
- Daily Price Variation
- Sector Performance
- Ticker lookup
- Company Information 

This web-app is built on a Flask server with Postgres SQL database with SQLAlchmey as the ORM. One year of daily price data for 30 stocks is saved in the database. In the backend, a large of amounts of dataset is analyzed using Python Pandas library. Four different graphs are rendered by using Charts JS. The front end templating uses Jinja2. The HTML is built using Bootstrap. Javascript uses AJAX and JSON to interact with the backend. Database and server routes are tested using the Python unittest module. 

## Tech Stack 

- Backend: Python, Flask, SQLAlchemy, PostgreSQL, Python unittest module 

- Frontend: Javascript, AJAX, JSON, Bootstrap, Charts.JS, HTML, CSS, JQuery, Jinja2, Flask 

- APIs: Alphadvantage, iexcloud 

## Future Features
 
 For next sprint on the project, I want to make a feature, which users can predict the stock price and they will get notifications when the prices go up or go down. 

## Installation 

- Clone repository 

$ git clone https://github.com/thuytpham/Stock-Analysis-Tool.git

- Create database

$ createdb stocks

- Create a Virtual Environment 

$ virtualenv env

- Activate virtual environment 

$ source env/bin/activate

- Install dependencies 

$ pip install -r requirements.txt

- Run the app

$ python3 server.py 