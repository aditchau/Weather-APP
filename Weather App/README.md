
# Weather-app

This is a simple weather application built with HTML, CSS, and JavaScript. It provides real-time weather updates, hourly forecasts, and a 5-day forecast for any city entered by the user. The app uses the OpenWeather API to fetch weather data.

# Features

Current Weather Information: Displays the city name, weather description, temperature, humidity, and wind speed.

Hourly Forecast: Shows a forecast for the next 8 hours with temperature and weather icons.

5-Day Forecast: Provides weather information for the next 5 days with daily temperature and weather conditions.

Dynamic Background: Changes the background of the app based on the current weather condition (e.g., clear, cloudy, rainy, snowy).

Search Functionality: Users can search for weather details of any city worldwide by typing the city name in the search bar.

# Technologies Used
HTML5: Structure and layout of the application.

CSS3: Styling and responsiveness, including dynamic background changes based on weather conditions.

JavaScript: Handles fetching weather data, processing API responses, and updating the user interface.

OpenWeather API: Fetches weather data for the current city, hourly forecast, and 5-day forecast.

API Integration: This app integrates with the OpenWeather API to fetch weather information.

# API Endpoints:

Current Weather: https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={API_KEY}

5-Day Forecast: https://api.openweathermap.org/data/2.5/forecast?units=metric&q={city}&appid={API_KEY}
Replace {API_KEY} with your personal OpenWeather API key to fetch weather data.

# How to Use

Clone or download the project to your local machine.
Open the index.html file in your preferred web browser.
Enter a city name in the search bar and click the Search button to get weather updates for that city.
The weather details will be displayed along with hourly and 5-day forecasts.
The background image and color scheme will change dynamically based on the weather condition.

# Setup Instructions

# Step 1: 
Get OpenWeather API Key
Go to OpenWeather API.
Sign up and create a new API key.
Replace 8fc8d5c679b2e2e12143ae547dd72365 in the script with your generated API key.

# Step 2: 
Run the App
No backend setup is required. Simply open the index.html file in your browser, and the app should work instantly.

# Customization
You can modify the city by typing a different name into the search bar.

Update the background images (images/clear-sky.jpg, image/cloudy-sky.jpg, etc.) with your own images to match different weather conditions.

# Contributing

Feel free to fork the repository and make any improvements. If you have any suggestions or find bugs, please open an issue or submit a pull request.

# License

This project is open-source and available under the MIT License.
