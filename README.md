# Weather App

This SwiftUI-based weather app allows users to track weather forecasts for various cities. It leverages SwiftUI for the user interface, Combine for reactive programming, and integrates with a weather API for accurate forecasts.

## Features

- **City List**: View a list of cities with their current weather information.
- **Add New Cities**: Search and add new cities to the list.
- **Weather Details**: Check detailed weather information, including temperature, rainfall, and icons.
- **Dynamic Icons**: Icons change based on weather conditions for a more visual experience.

## Architecture

The app follows a structured architecture:

- **Model**: The `City` class represents a city with its weather information. It uses the `WeatherForecast` model to fetch weather data.
- **User Interface**: SwiftUI is used for the app's interface, including dynamic rendering of weather icons.
- **Data Management**: Combine is employed for handling asynchronous data flows and keeping UI in sync.
- **Networking**: The `WeatherManager` interacts with a weather API to fetch forecasts.
- **Location Services**: `GeocodingManager` validates and fetches location data for new cities.

## How to Use

1. Clone the repository: `git clone https://github.com/your-username/weather-app.git`
2. Open the project in Xcode.
3. Build and run the app on your preferred simulator or device.

## Requirements

- Xcode 14
- Swift 5

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.
