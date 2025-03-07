# Weather App

This is a simple React-based Weather App that allows users to search for weather information by city name. It fetches real-time weather data from the OpenWeatherMap API and displays it in a clean and user-friendly interface.

## Features

-   Search for weather information by city name.
-   Displays current temperature, city, country, latitude, longitude, humidity, and wind speed.
-   Shows weather condition icons based on the API response.
-   Handles loading and error states.
-   Displays a "City not found" message when an invalid city is entered.
-   Responsive design for various screen sizes.

## Technologies Used

-   React
-   JavaScript (ES6+)
-   CSS
-   OpenWeatherMap API

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd [repository name]
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Start the development server:**

    ```bash
    npm start
    ```

4.  **Open your browser and navigate to `http://localhost:3000`**

## API Key

This application uses the OpenWeatherMap API to fetch weather data. You'll need to obtain an API key from [OpenWeatherMap](https://openweathermap.org/) and replace the placeholder API key in `App.jsx` with your own.

```javascript
let api_Key = "YOUR_API_KEY"; // Replace with your API key