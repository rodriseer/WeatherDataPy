# WeatherDataPy

## Overview
WeatherDataPy, is a Python based weather tool which allows users to get and see the existing weather in an area for the next five days. An OpenWeather API is used to fetch the actual time climate information while also providing options for comparing different locations and their climate.

## Features
- Fetches and displays current weather data, including temperature (in Celsius and Fahrenheit) and weather descriptions.
- Visualizes weather data using `matplotlib`, including bar charts for temperature comparison.
- Provides a 5-day weather forecast with temperatures and weather conditions.
- Allows users to compare the weather data of two cities side by side.

## Technologies Used
- **Python**: Core programming language.
- **Requests**: For making HTTP requests to the OpenWeather API.
- **Pandas**: For handling and processing forecast data.
- **Matplotlib**: For data visualization.
- **Pillow**: For image processing (used for displaying weather icons).
- **dotenv**: For managing environment variables securely (API key).

## Setup Instructions

### Requirements
- Python 3.x installed on your machine.
- An API key from [OpenWeather](https://home.openweathermap.org/api_keys).
- pip install requests pandas matplotlib pillow python-dotenv

### Usage Example
Get Current Weather:

Enter a city name when prompted, and the tool will display the current temperature in both Celsius and Fahrenheit, along with a description of the weather.
Compare Two Cities: Rockville and Tokyo, as an example.

After fetching weather data for the first city, you will be prompted to enter a second city name to compare the weather conditions side by side.

### Contributing
Contributions are welcome and appreciated! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.
I would gladly accept some suggestions, feel free to contact me.

### Future Updates
- More weather data analysis such as air quality.
- A better, improved UI.




