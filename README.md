# Weather App

This mobile application provides users with real-time weather information, including the current weather, upcoming forecasts, and details for specific cities. Built with React Native, it offers a cross-platform solution for both iOS and Android devices.

## Features

1. **Current Weather Screen:**
   - Displays the current weather conditions, including temperature, feels-like temperature, high and low temperatures, and a dynamic background based on the current weather.
   - Utilizes the [Feather icon library](https://feathericons.com/) for weather icons.

2. **Upcoming Weather Screen:**
   - Shows a five-day forecast with weather conditions, date, and temperature range.
   - Uses a stylish image background for a visually appealing display.

3. **City Details Screen:**
   - Provides comprehensive information about a specific city, including its name, country, population, and sunrise/sunset times.
   - Utilizes the IconText component for clear presentation.

## Dependencies

- **React Native:** [Link to React Native Documentation](https://reactnative.dev/)
  - React Native is a framework for building mobile applications using React and JavaScript.

- **Navigation:** [React Navigation](https://reactnavigation.org/)
  - React Navigation is a popular navigation library for React Native that provides a customizable and extensible navigation system.

- **Icons:** [Feather Icons](https://feathericons.com/)
  - Feather Icons is a collection of beautifully designed, customizable SVG icons. In this app, it is used for displaying weather icons in the Current Weather Screen.

## Getting Started

To run the React Native Weather App locally on your machine, follow these steps:

1. Clone the repository: `git clone https://github.com/Kalutu/weather-app`
2. Change into the project directory: `cd weather-app`
3. Install dependencies: `npm install` or `yarn install`
4. Obtain an API key from a weather API provider (e.g., OpenWeatherMap).
5. Set up environment variables:
   - Create a `.env` file in the backend directory and add necessary configurations.
   - `WEATHER_API_KEY=your_api_key_here`
6. Start the development server: `npx react-native run-android` or `npx react-native run-ios`

## Contributing

We welcome contributions! If you find a bug or have a feature request, please open an issue or submit a pull request.
