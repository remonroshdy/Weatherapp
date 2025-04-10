# Weatherapp

# Weather App

A Django-based web application that fetches historical and current weather data for a given city or ZIP code using the OpenWeatherMap API. Users can view, edit, and save weather records in a SQLite database. The app supports geolocation to detect the user's location, displays a 5-day forecast, and allows users to manage weather records (edit temperature and description, delete records).

## Features
- Fetch historical weather data (from 1979 onward) and current/future forecasts (up to 7 days).
- Geolocation support to detect the user's location.
- View, edit, and delete weather records stored in a database.
- Display a 5-day forecast for the specified city.
- Responsive design with a sky-blue gradient background and card-like layout for weather records.


# to make it work in your environment. 
1- Download the zip file , extract it and add the folder to VS or your code editor. 

2- navigate to Weatherproject  and create the virtual environment 
3- python -m venv venv 
4- pip install -r requirements.txt
5- python manage.py migrate 
6-python manage.py runserver



