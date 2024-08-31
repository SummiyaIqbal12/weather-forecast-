
# Weather Forecasting System 🌦️

Welcome to the **Weather Forecasting System**! This C++ project provides a comprehensive solution for fetching and displaying both current and historical weather data. Leveraging the power of `libcurl` for HTTP requests and `nlohmann/json` for JSON parsing, this system offers a robust way to access weather information.

## 🚀 Features

- **Current Weather Data**: Retrieve and display up-to-date weather information for any location.
- **Historical Weather Data**: Access weather records for specific dates and locations.
- **Data Export**: Export weather data to CSV and JSON files for further analysis or reporting.

## 🛠️ Prerequisites

To get started, ensure you have the following installed:

- C++11 or later
- [libcurl](https://curl.se/libcurl/) library
- [nlohmann/json](https://github.com/nlohmann/json) library (JSON for Modern C++)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/weather-forecasting-system.git
   cd weather-forecasting-system
   ```

2. **Install Dependencies**

   Install `libcurl` and include `nlohmann/json` in your project. On Ubuntu, you can install `libcurl` with:

   ```bash
   sudo apt-get install libcurl4-openssl-dev
   ```

   Add `nlohmann/json` by copying `json.hpp` from the [nlohmann/json GitHub repository](https://github.com/nlohmann/json).

3. **Compile the Code**

   Compile the code using `g++` or another C++ compiler. Link against the `libcurl` library:

   ```bash
   g++ -std=c++11 -o weather_forecasting_system main.cpp -lcurl
   ```

## 💻 Usage

1. **Configure API Keys**

   Open `main.cpp` and replace `YOUR_CURRENT_API_KEY` and `YOUR_HISTORICAL_API_KEY` with your actual API keys. 

2. **Run the Application**

   Execute the compiled binary:

   ```bash
   ./weather_forecasting_system
   ```

   The application will:
   - Fetch and display the current weather data for London.
   - Fetch and display historical weather data for London on August 1, 2023.
   - Export the current and historical weather data to `current_weather.csv`, `current_weather.json`, `historical_weather.csv`, and `historical_weather.json`.

## 📚 Classes

- **`WeatherForecastingSystem`**: Manages current weather data retrieval and display. Supports exporting data to CSV and JSON formats.
- **`HistoricalWeatherSystem`**: Manages historical weather data retrieval and display. Also supports exporting data to CSV and JSON formats.
- **`LocationManager`**: Manages a list of locations (optional utility class for future extensions).

## 🎨 Enhancements

- **Data Visualization**: Integrate with graphical libraries for better data presentation.
- **Extended Forecasts**: Add support for more detailed forecasts and different weather parameters.
- **User Interface**: Develop a GUI application for easier interaction with the system.

## 🤝 Contributing

We welcome contributions to improve the Weather Forecasting System. Feel free to open issues or submit pull requests. For any questions or feedback, reach out via GitHub issues.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For further inquiries or feedback, please contact [your email address] or open an issue on the [GitHub repository](https://github.com/yourusername/weather-forecasting-system).

