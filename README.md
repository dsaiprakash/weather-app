# Atmosphere - Modern Weather Application [LiveRun](https://weather-app.prakash.codes)

## Description

Atmosphere is an elegant, feature-rich weather application that provides real-time weather information and forecasts with a visually stunning interface. This modern web application delivers a seamless user experience with intuitive controls, dynamic theming based on weather conditions, and comprehensive weather data visualization.

![Atmosphere Weather App Screenshot](screenshot.png)

## Features

### Core Functionality
- **Real-time Weather Data**: Fetch and display current weather information for any location worldwide
- **5-Day Forecast**: View upcoming weather predictions to plan your week effectively
- **Geolocation Support**: Get weather for your current location with a single click
- **Search Functionality**: Easy-to-use search with city name lookup
- **Search History**: Quick access to your recently searched locations

### Design Features
- **Weather-Based Theming**: Dynamic background gradients that change based on current weather conditions
- **Dark/Light Mode**: Toggle between themes for comfortable viewing in any environment
- **Responsive Design**: Optimized for all devices from mobile phones to desktop monitors
- **Elegant Weather Icons**: Clear visual representations of weather conditions
- **Loading States**: Smooth transitions with loading indicators and error handling
- **Animated Elements**: Subtle animations enhance the user experience

### Technical Features
- **Geolocation Reverse Lookup**: Converts coordinates to city names for better user experience
- **Persistent Settings**: Remembers your theme preference and recent searches
- **Error Handling**: Graceful error management with helpful messages
- **Optimized API Usage**: Efficient API calls to reduce data usage

## Technologies Used

- **JavaScript**: Modern ES6+ features with async/await for API handling
- **CSS3**: Advanced styling with CSS variables, Flexbox, Grid, and responsive design
- **HTML5**: Semantic markup for accessibility and SEO
- **OpenWeather API**: Real-time weather data and forecasts
- **Geolocation API**: Browser-based location detection
- **LocalStorage**: Client-side persistent storage
- **Font Awesome**: Vector icons for weather conditions and UI elements

## Design Philosophy

Atmosphere was designed with these core principles:

1. **Visual Clarity**: Making weather data instantly understandable through thoughtful design
2. **Contextual Experience**: Adapting the interface to match current weather conditions
3. **Effortless Interaction**: Minimizing user effort to access essential information
4. **Elegant Animation**: Adding subtle motion to enhance engagement without distraction
5. **Consistent Branding**: Maintaining a cohesive visual language throughout the application

## Setup

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dsaiprakash/weather-app.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd weather-app
   ```

3. **Get an API Key**:
   - Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/)
   - Navigate to the API Keys section and copy your key

4. **Add Your API Key**:
   - Open `script.js` in your code editor
   - Replace the existing API key with your own key

5. **Open `index.html` in Your Browser**:
   - You can use a local development server for optimal experience
   - Alternatively, simply open the index.html file in your browser