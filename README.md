
# 🌤️ Weather App (Tkinter + OpenWeatherMap)

A clean and responsive desktop weather application built using Python, Tkinter, and the OpenWeatherMap API. This app allows users to enter a city name and retrieve real-time weather data including temperature, description, and weather icons.


## 🚀 Features

- Search for real-time weather by city

- Displays:

    - Temperature (in °C)

    - Weather description (formatted in camel case)

    - Location (City, Country)

    - Weather icon from OpenWeatherMap

- Error handling for invalid city names

- Modern UI using ttkbootstrap


## 🛠️ Technologies Used

- **Python 3**

- **Tkinter** – GUI framework

- **ttkbootstrap** – Modern themed widgets

- **Pillow (PIL)** – For image handling

- **OpenWeatherMap API** – Weather data provider

- **Requests** – For HTTP requests

## 📦 Requirements

Make sure you have the following Python packages installed:

```bash
pip install requests pillow ttkbootstrap
```
    
## 🧠 How It Works


    1. User inputs a city name and clicks Search.

    2. App sends a request to the OpenWeatherMap API.

    3. If found, weather data and icons are fetched and displayed.

    4. If not found, an error dialog is shown.

## 🔧 Setup & Usage

Clone the project

```bash
  git clone https://github.com/MphoItumeleng/weather-app.git
```

Go to the project directory

```bash
  cd weather-app
```

Install dependencies

```bash
  pip install requests pillow ttkbootstrap
```

Run the app

```bash
  python weather_app.py
```


## 🔑 API Key

This app uses the [OpenWeatherMap](https://openweathermap.org/api) API.
You will need an API key. Replace the placeholder in the code:

```http
  API_key = "your_api_key_here"
```

## 📌 Future Enhancements

- Add support for forecasts (5-day or hourly)

- Improve UI with weather-themed backgrounds

- Allow selection of metric/imperial units

- Save search history
