# Python API Challenge

This repository contains the code for the Python API Challenge, which is divided into two parts: WeatherPy and VacationPy.

## WeatherPy

In the WeatherPy part of the challenge, a Python script is created to visualize the weather of over 500 cities of varying distances from the equator. The citipy Python library and the OpenWeatherMap API are used for this purpose.

### Requirements:
1. **Create Plots to Showcase the Relationship Between Weather Variables and Latitude:**
   - Latitude vs. Temperature
   - Latitude vs. Humidity
   - Latitude vs. Cloudiness
   - Latitude vs. Wind Speed

2. **Compute Linear Regression for Each Relationship:**
   - Northern Hemisphere: Temperature vs. Latitude
   - Southern Hemisphere: Temperature vs. Latitude
   - Northern Hemisphere: Humidity vs. Latitude
   - Southern Hemisphere: Humidity vs. Latitude
   - Northern Hemisphere: Cloudiness vs. Latitude
   - Southern Hemisphere: Cloudiness vs. Latitude
   - Northern Hemisphere: Wind Speed vs. Latitude
   - Southern Hemisphere: Wind Speed vs. Latitude

### Instructions:
- Open `WeatherPy.ipynb` to view the Jupyter notebook with the code.
- Follow the instructions within the notebook to execute the code and generate the required plots.

## VacationPy

In the VacationPy part of the challenge, the weather data obtained in WeatherPy is used to plan future vacations. Jupyter notebooks, the geoViews Python library, and the Geoapify API are utilized for this task.

### Requirements:
1. **Create a map that displays a point for every city in the dataset.**
2. **Narrow down the dataset to find ideal weather conditions.**
3. **Use the Geoapify API to find nearby hotels for each city.**

### Instructions:
- Open `VacationPy.ipynb` to view the Jupyter notebook with the code.
- Follow the instructions within the notebook to execute the code and generate the required maps.

## Files:
- `api_keys.py`: File to store API keys (not included in the repository for security reasons).
- `WeatherPy.ipynb`: Jupyter notebook for WeatherPy.
- `VacationPy.ipynb`: Jupyter notebook for VacationPy.

## Usage:
1. Clone the repository to your local machine.
2. Follow the instructions provided in the respective Jupyter notebooks to execute the code.
3. Ensure that you have the required Python libraries installed.