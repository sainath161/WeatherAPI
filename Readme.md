The Weather Application is a web-based tool that allows users to fetch real-time weather data based on their current location. The application consists of two main pages: index.html and weather.html. Users can click the "Fetch Data" button on the index page to navigate to the weather page, where detailed weather information is displayed.

Getting Started

To run the Weather Application, simply open the index.html file in a web browser. Click the "Fetch Data" button to navigate to the weather.html page, where you can view your current location, a map, and detailed weather information.
Usage

    Fetch Data Button: Clicking the "Fetch Data" button on the index page redirects you to the weather page.

    Weather Page: The weather page displays your current location, a map with latitude and longitude, and detailed weather information, including location, wind speed, humidity, time zone, pressure, wind direction, UV index, feels-like temperature, and more.

Folder Structure

    index.html: The main page with the "Fetch Data" button.
    weather.html: The page displaying detailed weather information.
    style.css: Styles for both the index and weather pages.
    script.js: JavaScript file containing functions for fetching location, weather data, and handling UI updates.

Styles

The application uses CSS styles to enhance the visual appeal and user experience. Styles are organized in the style.css file, providing a clean and responsive design for both the index and weather pages.
JavaScript Functions

    Fetching Location: The getLocation function checks if geolocation is supported and retrieves the user's latitude and longitude.

    Fetching Weather Data: The currentWeather function fetches weather data using the OpenWeatherMap API, and the DisplayData function updates the weather information on the weather page.

    Responsive Design: The application adapts to different screen sizes with responsive design techniques, ensuring a seamless experience on various devices.

API Integration

The Weather Application integrates with the OpenWeatherMap API to provide accurate and up-to-date weather information. Replace the API key in the apiKey variable with your own OpenWeatherMap API key for proper functionality.
Responsive Design

The application incorporates media queries in the style.css file to ensure a responsive layout on different devices. The design adjusts dynamically to various screen sizes, providing an optimal viewing experience.
Contributing

Contributions to the Weather Application are welcome! Feel free to open issues or pull requests to suggest improvements, report bugs, or add new features.

![image](https://github.com/sainath161/WeatherAPI/assets/71361447/882ff256-794a-42f7-a69d-d1ce0c0ed2b1)

![image](https://github.com/sainath161/WeatherAPI/assets/71361447/0f6dbde8-1fb2-4914-896b-06b690f1494c)

![image](https://github.com/sainath161/WeatherAPI/assets/71361447/96d920e3-6007-41f7-a043-7c8225c171cc)
