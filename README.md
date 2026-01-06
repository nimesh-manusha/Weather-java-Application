🌦️ Weather Java Application
A sleek and interactive Desktop Weather Application built using Java and Swing. This application allows users to search for any city worldwide and get real-time weather updates, including temperature, weather conditions, humidity, and wind speed.

🚀 Features
Real-time Data: Fetches live weather information using external APIs.

Search Functionality: Search for any city or location globally.

Dynamic UI: Displays custom weather icons based on the current weather (Clear, Cloudy, Rain, Snow).

Comprehensive Details: Shows temperature (Celsius), humidity levels, and wind speed.

User-Friendly Interface: Modern and intuitive GUI built with Java Swing.

🛠️ Technologies Used
Language: Java

GUI Framework: Swing & AWT

JSON Parsing: json-simple library

API: Open-Meteo (or Geocoding API for location data)

Tooling: Java HTTP client for network requests.

📂 Project Structure
AppLauncher.java: The entry point of the application.

WeatherAppGui.java: Handles the visual components and user interactions.

WeatherApp.java: Contains the backend logic for API calls and data processing.

🔧 Installation & Setup
Clone the Repository

Bash

git clone https://github.com/nimesh-manusha/Weather-java-Application.git
Add Dependencies Make sure you have the json-simple library added to your project classpath to handle API responses.

Compile and Run Navigate to the src folder and run the AppLauncher class:

Bash

javac AppLauncher.java
java AppLauncher
🖥️ Usage
Launch the application.

Type the name of a city (e.g., "Colombo" or "London") in the search bar.

Click the search icon.

View the updated weather details and icons on the screen.
