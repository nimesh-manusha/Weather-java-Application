# 🌦️ Weather Java Application

A sleek and interactive Desktop Weather Application built using **Java** and **Swing**. This application allows users to search for any city worldwide and get real-time weather updates, including temperature, weather conditions, humidity, and wind speed.

---

## ✨ Features

* **Real-time Data:** Fetches live weather information using external APIs.
* **Search Functionality:** Search for any city or location globally.
* **Dynamic UI:** Displays custom weather icons based on the current weather (Clear, Cloudy, Rain, Snow).
* **Comprehensive Details:** Shows temperature (Celsius), humidity levels, and wind speed.
* **User-Friendly Interface:** Modern and intuitive GUI built with Java Swing.

---

## 🛠️ Technologies Used

* **Language:** Java
* **GUI Framework:** Swing & AWT
* **JSON Parsing:** `json-simple` library
* **API:** [Open-Meteo](https://open-meteo.com/) (for Weather data and Geocoding)

---

## 📂 Project Structure

| File | Description |
| :--- | :--- |
| **AppLauncher.java** | The main entry point to launch the application. |
| **WeatherAppGui.java** | Handles the visual layout, components, and user interactions. |
| **WeatherApp.java** | Backend logic for fetching data, API calls, and JSON parsing. |
| **assets/** | Folder containing images and weather icons. |

---

## 🚀 Installation & Setup

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/nimesh-manusha/Weather-java-Application.git](https://github.com/nimesh-manusha/Weather-java-Application.git)
    ```

2.  **Add Dependencies**
    * Download the `json-simple` JAR file.
    * Add it to your project's Build Path in your IDE (IntelliJ, Eclipse, or NetBeans).

3.  **Run the Application**
    * Locate `AppLauncher.java` in the `src` folder.
    * Right-click and select **Run**.

---

## ⚙️ How It Works

1.  **Input:** User enters a city name in the search bar.
2.  **Geocoding:** The app sends the city name to the Geocoding API to get Latitude and Longitude.
3.  **Weather Fetch:** Using those coordinates, it requests weather data from the Open-Meteo API.
4.  **Display:** The app parses the JSON response and updates the UI with the current temperature, weather description, humidity, and wind speed.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new features or improvements, feel free to fork the repo and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👤 Author

**Nimesh Manusha**
* GitHub: [@nimesh-manusha](https://github.com/nimesh-manusha)

---
*Developed with ❤️ using Java*
