
# Weather App 🌤️

This is a simple, responsive **Weather Web Application** that fetches real-time weather data using the [WeatherAPI](https://www.weatherapi.com/) based on the user's entered location.

## Features

- Fetch current weather conditions for any city using WeatherAPI.
- Displays temperature, weather condition, humidity, wind speed, and weather icon.
- Responsive and mobile-friendly design using HTML, CSS, and JavaScript.
- Error handling for invalid city names or failed API requests.

## How It Works

1. Enter a city name (e.g., *Delhi*) in the input field.
2. Click the **Search** button.
3. The app fetches live weather data from WeatherAPI and displays:
   - Temperature (°C)
   - Weather condition and icon
   - Humidity and wind speed

## Requirements

- A free API key from [WeatherAPI](https://www.weatherapi.com/).
- A modern browser (Chrome, Edge, Firefox, etc.).
- Internet connection to fetch live weather data.

## Setup Instructions

1. Clone or download the repository.
2. Open the `weather.html` file in a code editor.
3. Replace the placeholder `API_KEY` in the JavaScript section with your own WeatherAPI key:

```javascript
const API_KEY = "your_api_key_here";
```
4. Open `weather.html` in your browser and start using the app.

## File Structure

```
weather.html  # Main application file (HTML, CSS, and JS combined)
```

## Example

Search for a city like "London" or "New York" to see live weather details.

---

Enjoy using the Weather App! ☀️🌧️❄️
