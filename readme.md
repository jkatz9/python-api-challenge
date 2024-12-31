# WeatherPy

## Overview

WeatherPy is a Python-based project that analyzes weather data from various cities around the world. The project uses the OpenWeatherMap API to fetch weather data and performs linear regression analysis to understand the relationship between latitude and various weather parameters.

## Features

- Fetches weather data for random cities around the world.
- Analyzes the relationship between latitude and weather parameters such as temperature, humidity, cloudiness, and wind speed.
- Generates scatter plots and linear regression plots for both Northern and Southern Hemispheres.
- Exports the analyzed data and plots to CSV and PNG files respectively.

## Installation

1. create a file in WeatherPy called api_keys.py, and add your OpenWeatherMap API key as follows

```python
# OpenWeatherMap API Key
weather_api_key = your api key
# Geoapify API Key
geoapify_key = your api key
```

2. run the programs in the following order

```bash
python WeatherPy.ipynb
python VacationPy.ipynb
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
