# Weather Dashboard

## Description

The Weather Dashboard is a web application that allows users to check the current weather .It provides detailed information including temperature, humidity, wind speed, and UV index. The application also features a search history function and the ability to switch between Fahrenheit and Celsius temperature units.

## Features

- Current weather display
- Search functionality for different cities
- Search history storage
- Temperature unit conversion (Fahrenheit/Celsius)
- Responsive design for various screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript
- jQuery
- Bootstrap 4
- Day.js
- OpenWeather API

## Setup Instructions

1. Clone the repository to your local machine:
   git clone https://github.com/your-username/weather-dashboard.git
2. Navigate to the project directory:
   cd weather-dashboard
3. Open the `index.html` file in your web browser.

4. Alternatively, you can use a local server to run the application. If you have Python installed, you can use:

- For Python 3.x:
  ```
  python -m http.server
  ```
- For Python 2.x:
  ```
  python -m SimpleHTTPServer
  ```
  Then open your browser and go to `http://localhost:8000`

5. To use the OpenWeather API, you need to sign up for a free API key at [OpenWeather](https://openweathermap.org/api). Once you have your API key, replace the placeholder in the `app.js` file:

```javascript
var APIKey = "YOUR_API_KEY_HERE";
```

Usage

Enter a city name in the search bar and click the search button or press Enter.
Click on a city in the search history to view its weather again.
Use the temperature toggle button to switch between Fahrenheit and Celsius.

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License
MIT
This README provides a comprehensive overview of your Weather Dashboard application, including a description, features, technologies used, setup instructions, usage guidelines, and information for contributors. You can save this content in a file named `README.md` in the root directory of your project.
