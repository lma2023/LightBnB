# LightBnB

AirBnB clone uses a server-size Javascript to display the information from queries to web pages via SQL queries.

# Dependences
* Node.js
* pg
* bcrypt
* express
* nodemon
* cookie-session

# Installation

* Clone this repo
* In LightBnB folder install Node Postgres: npm install pg
* Create a new database lightbnb
* Setup new tables with \i migrations/01_schema.sql
* Setup the tables with with \i seeds/02_seeds.sql
* Install dependencies by running npm i in the folder LightBnB_WebApp
* Run npm run local to run the app.
* Go to 'http://localhost:8080' in your browser