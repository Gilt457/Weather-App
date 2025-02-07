# Weather App

This is a simple weather application that allows users to check the weather conditions for any city. The application fetches weather data from the OpenWeatherMap API and displays it in a user-friendly interface.

## Project Structure

```
weather-app
├── images
│   ├── clear.png         # Represents clear weather conditions
│   ├── clouds.png        # Represents cloudy weather conditions
│   ├── drizzle.png       # Represents drizzle weather conditions
│   ├── humidity.png      # Represents humidity information
│   ├── mist.png          # Represents misty weather conditions
│   ├── rain.png          # Represents rainy weather conditions
│   ├── search.png        # Search icon used in the application
│   ├── snow.png          # Represents snowy weather conditions
│   └── wind.png          # Represents wind information
├── style.css             # Styles for the weather application
├── index.html            # Main HTML document for the weather application
└── README.md             # Documentation for the project
```

## Installation

1. Clone the repository to your local machine:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd weather-app
   ```

3. Open `index.html` in your web browser to view the application.

## Usage

- Enter the name of a city in the input field and click the search button.
- The application will display the current temperature, humidity, wind speed, and weather conditions for the specified city.
- If the city name is invalid, an error message will be displayed.

## API Key

To fetch weather data, you need an API key from OpenWeatherMap. Replace the `apiKey` variable in the `index.html` file with your own API key.

## License

This project is open-source and available under the MIT License.
