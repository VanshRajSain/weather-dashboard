# weather-dashboard


Weather Dashboard
A simple and responsive weather application that provides current weather information for any city worldwide. The app uses the OpenWeather API to fetch real-time weather details and displays them in an easy-to-read format.

Features
City Search: Users can search for any city in the world and get real-time weather data.
Current Weather: Displays temperature, humidity, wind speed, and weather condition (e.g., clear, clouds, rain).
Dynamic Weather Icons: Shows weather-specific icons (clouds, clear, rain, drizzle, snow, etc.) based on the weather condition.
Error Handling: Displays an error message if the city is not found or if there is an issue with the API request.
Responsive Design: Fully responsive, ensuring a seamless experience on mobile, tablet, and desktop.
Technologies Used
HTML5: For structuring the webpage.
CSS3: For styling and making the page responsive.
JavaScript (ES6): For handling the logic, API requests, and dynamic content updates.
OpenWeather API: To fetch real-time weather data.
Setup and Installation
Prerequisites
You need an active internet connection to fetch data from the OpenWeather API.
Sign up for a free API key from OpenWeather.
Steps
Clone this repository:

bash
Copy code
git clone https://github.com/VanshRajSain/weather-dashboard.git
Navigate into the project directory:

bash
Copy code
cd weather-dashboard
Open the index.html file in a browser to run the project locally.

Replace the apiKey in app.js with your OpenWeather API key:

javascript
Copy code
const apiKey = "YOUR_API_KEY";
Usage
Enter the name of the city in the search input box.
Click the "Search" button or press "Enter" to fetch the weather data.
The app will display:
Temperature in Celsius
Humidity percentage
Wind speed in km/h
Weather icon matching the condition (e.g., clear, clouds, rain)
Example Screenshot

Future Improvements
5-Day Forecast: Add functionality to show the 5-day weather forecast for searched cities.
Geolocation: Implement the ability to fetch weather data based on the user's current location.
Unit Toggle: Add an option to toggle between Celsius and Fahrenheit.
Contributing
If you would like to contribute to this project, feel free to submit a pull request or open an issue.

License
This project is licensed under the MIT License. See the LICENSE file for details.
