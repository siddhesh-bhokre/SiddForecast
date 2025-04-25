# SiddForecast - Weather Forecast Web Application

## Project Overview

**SiddForecast** is a simple yet effective weather forecasting web application built using HTML, CSS, and JavaScript. It allows users to check the current weather conditions for multiple cities around the world. The app fetches real-time data from the OpenWeatherMap API and presents the results in an intuitive and user-friendly interface. Additionally, it provides a theme toggle feature, where users can switch between light and dark modes based on their preferences.

---

## Key Features

- **City Search**: Allows users to input city names, and provides suggestions based on partial matches from a predefined list of cities.
- **Weather Data**: Fetches current weather details including temperature, humidity, and wind speed for the selected city.
- **Weather Icons**: Displays weather icons corresponding to the current weather conditions.
- **Theme Toggle**: Offers a light and dark mode toggle, changing the overall theme based on the current temperature or user preference.
- **Responsive Design**: The app is fully responsive, ensuring a seamless experience on both desktop and mobile devices.

---

## Technologies Used

- **HTML5**: Used for creating the structure of the application.
- **CSS3**: Utilized for styling and creating a responsive layout.
- **JavaScript**: Handles the logic for fetching weather data and dynamically updating the UI.
- **OpenWeatherMap API**: Used to retrieve real-time weather information.

---

## How It Works

1. **City Search**: As the user types in the city name, the app suggests cities from a predefined list that match the entered text. This is implemented using JavaScript's `input` event listener.
2. **Fetching Weather Data**: When the user selects a city or presses enter, the app fetches weather data using the OpenWeatherMap API. The weather information is displayed, including temperature, weather conditions, humidity, and wind speed.
3. **Theme Change**: Based on the fetched temperature, the app adjusts the theme to reflect the weather. For example:
   - **Cold weather**: Switches to a "cold" theme with a blue color palette.
   - **Warm weather**: Switches to a "warm" theme with an orange color palette.
   - **Moderate weather**: Stays on the default light or dark theme.
4. **Mode Toggle**: The user can manually toggle between light and dark modes by clicking the mode toggle button. The user's preference is saved in `localStorage` to persist the setting across sessions.

---

## How to Use

1. Open the app in your browser.
2. Type a city name in the input field.
3. Select a city from the suggestions or press "Enter" to fetch the weather details.
4. View the weather information displayed below, including temperature, humidity, and wind speed.
5. Toggle the light/dark mode by clicking the moon icon on the bottom right of the screen.


---

## Additional Features

- **Error Handling**: If the entered city name is not found or the API request fails, the app displays an error message.
- **Responsive Layout**: The app layout adapts to different screen sizes to ensure a smooth user experience across devices.

---

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/siddhesh-bhokre/SiddForecast.git
