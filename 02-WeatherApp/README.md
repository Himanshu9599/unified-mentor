Weather App
A simple and intuitive weather application that provides current weather information for your location and allows you to search for weather details in any city.

Features
Your Weather: Fetches and displays weather information based on your current location.
Search Weather: Allows searching for weather information in any city.
Real-time Updates: Provides real-time weather data including temperature, wind speed, humidity, and cloud coverage.
Responsive Design: Optimized for different screen sizes and devices.
Technologies Used
HTML: Structure and layout of the application.
CSS: Styling and responsive design.
JavaScript: Logic for fetching and displaying weather data.
OpenWeatherMap API: Source of weather data.
Getting Started
Prerequisites
A modern web browser.
Internet connection.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/weather-app.git
Navigate to the project directory:
bash
Copy code
cd weather-app
Usage
Open index.html in your web browser:
bash
Copy code
open index.html
To get weather information based on your location, click the "Grant Access" button to allow location access.
To search for weather information in a specific city, switch to the "Search Weather" tab, enter the city name in the search bar, and click the search button.
Project Structure
index.html: The main HTML file.
style.css: The main CSS file for styling the application.
script.js: The main JavaScript file containing the logic for fetching and displaying weather data.
Images/: Directory containing images used in the application.
API Integration
This project uses the OpenWeatherMap API to fetch weather data. You will need to sign up and get an API key from OpenWeatherMap.

Setting Up the API Key
Replace the placeholder API key in script.js with your own API key:
javascript
Copy code
const API_KEY = "your_api_key_here";
Contributing
Contributions are welcome! Please fork this repository and submit pull requests with any enhancements or bug fixes.

License
This project is licensed under the MIT License.

Acknowledgments
OpenWeatherMap for providing the weather data API.
Google Fonts for the Merriweather Sans font.
