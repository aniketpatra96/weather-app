# Weather App - ReactJS with OpenWeather API
This is a simple weather application built using ReactJS and the OpenWeather API. It allows users to check the current weather for any city by entering the city name and viewing real-time weather information such as temperature, humidity, wind speed, and weather conditions.

## Features
Search for weather by city name.
Displays current temperature, humidity, wind speed, and weather condition.
Responsive design for mobile and desktop.
Real-time weather data fetched from the OpenWeather API.
Tech Stack
Frontend: ReactJS
API: OpenWeather API
Styling: CSS
State Management: React useState and useEffect
Icons: Weather icons from OpenWeather

## Installation
Prerequisites:
Node.js (v14 or higher)
npm (v6 or higher) or yarn
Steps to run the app locally:
Clone the repository:

bash
Copy code
git clone <https://aniketpatra96.github.io/weather-app/>
cd react-weather-app
Install dependencies:

If you're using npm:

bash
Copy code
npm install
Or if you're using yarn:

bash
Copy code
yarn install
Get an OpenWeather API key:

Go to OpenWeather and sign up for an API key.

Once you have your API key, create a .env file in the root of your project, and add your API key as follows:

makefile
Copy code
REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
Start the app:

To run the app in development mode:

bash
Copy code
npm start
Or if you're using yarn:

bash
Copy code
yarn start
The app will be available at <http://localhost:3000> in your browser.

How it Works
Search for a city: The user enters the name of a city into the search bar.
Fetch weather data: The app makes an API call to the OpenWeather API to fetch the current weather data for that city.
Display results: The app updates the UI to show the weather data, including:
Temperature (in Celsius or Fahrenheit)
Weather condition (sunny, cloudy, rainy, etc.)
Humidity
Wind speed
Weather icon
Error handling: If the city is not found or there's an issue with the API request, the app displays an error message.
File Structure
bash
Copy code
/react-weather-app
  /public
    index.html
  /src
    /components
      WeatherCard.js
      SearchBar.js
    /utils
      weatherApi.js
    App.js
    index.js
  .env
  package.json
  README.md
## Components:
WeatherCard.js: Displays the weather data for the searched city.
SearchBar.js: Input field for the user to type the city name and submit.
App.js: Main component that manages the state and renders the UI.
utils:
weatherApi.js: Handles the API calls to OpenWeather.

## Example Usage
Open the app.
Type a city name (e.g., "New York") in the search bar.
Press enter or click the search button to get the current weather for that city.
Error Handling
If the city is not found or the API request fails, an error message will appear on the screen.
Invalid or empty city names are also handled.
License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
The weather data is powered by OpenWeather API.
Weather icons are sourced from OpenWeather Icons.

