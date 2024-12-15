# Python Current Weather Temperature API Scripts

A Python project that fetches the current weather and temperature data using an external weather API. This script allows you to get real-time weather information for any city.

## Features

- **Real-time Weather**: Fetches current weather data such as temperature, humidity, and weather conditions.
- **City Search**: Allows users to input a city name to get the corresponding weather information.
- **API Integration**: Uses a weather API (e.g., OpenWeatherMap) to fetch the weather data.

## Requirements

- **Python 3.x**
- **API Key**: You will need an API key from a weather service provider like [OpenWeatherMap](https://openweathermap.org/api).

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/shahramsamar/Python_Current_weather_Temp_Api_Scripts.git
    cd Python_Current_weather_Temp_Api_Scripts
    ```

2. **Install Dependencies:**

    If you're using `pip`, run:

    ```bash
    pip install -r requirements.txt
    ```

3. **Get API Key**: 

    Sign up for an API key at a weather service provider (e.g., OpenWeatherMap).

4. **Set up the API Key**:

    In the script, replace the placeholder for the API key with your actual key.

    ```python
    api_key = 'your_api_key'
    ```

5. **Run the Script:**

    ```bash
    python weather.py
    ```

### How to Use

- The script will prompt you to enter a city name.
- It will then fetch the weather data for that city from the API.
- The weather details such as temperature, weather condition, and humidity will be displayed in the terminal.

### Project Structure

- `weather.py`: Main script that handles fetching weather data from the API.
- `requirements.txt`: Lists necessary libraries such as `requests` for API calls.

## Contributing

Feel free to fork the project and submit pull requests for new features, improvements, or bug fixes.

## License

This project is open-source and available for educational purposes.
![Alt](https://repobeats.axiom.co/api/embed/eabe6508a91fa38b4ace0060919094363916f544.svg "Repobeats analytics image")
