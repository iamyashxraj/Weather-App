# Simple Weather App

## Description

The Simple Weather App is a basic web application that allows users to retrieve the current weather for any city they enter. This project utilizes the OpenWeatherMap API to fetch real-time weather data, including temperature and a short weather description.

## Features

- Enter any city name to get the current weather.
- Displays the temperature in Celsius.
- Shows a brief description of the weather conditions (e.g., clear sky, rain).
- Responsive design with a clean, minimalistic user interface.

## How It Works

1. The user enters the name of a city in the input field.
2. Upon clicking the "Get Weather" button, the app sends a request to the OpenWeatherMap API using the provided city name.
3. The app fetches the temperature and weather data from the API and displays the results on the page.
4. If the city is not found, an error message is displayed.

## Technologies Used

- **HTML**: For the structure of the app.
- **CSS**: For styling the app, including responsive design elements.
- **JavaScript**: For handling the API requests, fetching weather data, and dynamically displaying results.
- **OpenWeatherMap API**: For retrieving real-time weather data based on the city entered by the user.

## Project Structure

- `index.html`: The main HTML file containing the structure of the app.
- `styles.css`: The CSS file for styling the app.
- `script.js`: The JavaScript file that handles API requests and dynamic updates to the DOM.

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/simple-weather-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd simple-weather-app
    ```
3. Open the `index.html` file in your browser to run the app.

### API Key

This project uses the [OpenWeatherMap API](https://openweathermap.org/api). You will need to sign up for a free API key:

1. Go to the [OpenWeatherMap website](https://openweathermap.org/).
2. Create an account and generate an API key.
3. Replace the placeholder API key in `script.js` with your actual key:

    ```javascript
    const apiKey = 'your-api-key-here'; // Replace with your OpenWeatherMap API key
    ```

## License

This project is open-source and available under the [MIT License](LICENSE).
