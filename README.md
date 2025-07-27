# Weather Dashboard

A beautiful, responsive weather dashboard built with HTML, CSS, and JavaScript that displays current weather conditions and 5-day forecasts for any location.

## Features

- 🌤️ **Current Weather Display**: Shows temperature, weather description, and detailed metrics
- 📅 **5-Day Forecast**: Displays weather predictions for the upcoming days
- 🎨 **Modern UI**: Clean, responsive design with gradient backgrounds and card layouts
- 📱 **Mobile Responsive**: Works perfectly on desktop, tablet, and mobile devices
- 🔍 **City Search**: Search for any city worldwide
- ⚡ **Real-time Data**: Uses OpenWeatherMap API for accurate, up-to-date information

## Weather Information Displayed

- Current temperature and "feels like" temperature
- Weather description and conditions
- Humidity percentage
- Wind speed
- Atmospheric pressure
- 5-day weather forecast with daily predictions

## Setup Instructions

### 1. Get an API Key
1. Visit [OpenWeatherMap](https://openweathermap.org/)
2. Sign up for a free account
3. Navigate to your API keys section
4. Copy your API key

### 2. Configure the Application
1. Open `index.html` in a text editor
2. Find the line: `const API_KEY = 'YOUR_API_KEY_HERE';`
3. Replace `'YOUR_API_KEY_HERE'` with your actual API key
4. Save the file

### 3. Run the Application
1. Open `index.html` in your web browser
2. Enter a city name in the search box
3. Click "Search" or press Enter
4. View the weather information!

## Usage

1. **Search for a City**: Type any city name in the search box
2. **View Current Weather**: See detailed current conditions including temperature, humidity, wind, and pressure
3. **Check Forecast**: Scroll down to see the 5-day weather forecast
4. **Responsive Design**: The dashboard adapts to different screen sizes

## Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks required)
- **API**: OpenWeatherMap API for weather data
- **Styling**: CSS Grid and Flexbox for responsive layouts
- **Icons**: Unicode weather emojis for visual representation
- **Units**: Metric system (Celsius, m/s, hPa)

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## API Rate Limits

The free OpenWeatherMap API has the following limits:
- 60 calls per minute
- 1,000 calls per day

This is sufficient for personal use and testing.

## Customization

You can easily customize the dashboard by:
- Changing colors in the CSS variables
- Adding more weather details
- Modifying the layout and styling
- Adding additional features like weather alerts or maps

## Troubleshooting

- **"City not found" error**: Check the spelling of the city name
- **No data displayed**: Verify your API key is correct and active
- **Slow loading**: Check your internet connection

## License

This project is open source and available under the MIT License.

---

**Note**: This is a frontend-only application. For production use, consider implementing proper API key security measures on the backend.
