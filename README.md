# Smart City Dashboard

A modern, interactive dashboard for visualizing smart city data, including weather, 7-day forecast, air quality index, and live mapping.  
This project is built using HTML, CSS, JavaScript, [LeafletJS](https://leafletjs.com/) for maps, and [Chart.js](https://www.chartjs.org/) for graphs.  
External APIs from [OpenWeatherMap](https://openweathermap.org/) and [Open-Meteo](https://open-meteo.com/) are used for live weather, forecast, and pollution data.

---

## Features

- **Live Weather Data:**  
  See current weather (with icon), temperature, humidity, wind, and date/time for any city.
- **Interactive Search:**  
  Search for any city to see localized stats, forecast, and map location.
- **7-Day Forecast Graph:**  
  View chart of min/max temperature trends for the week.
- **Air Quality Index:**  
  Pie chart breakdown of air pollutants for the location.
- **Interactive Map:**  
  Map centers to searched city, with marker and popup using LeafletJS.
- **Styled Dashboard UI:**  
  Responsive layout with side navigation, info cards, and modern gradients.
- **Sidebar Quick Links:**  
  Includes links to news and a help page.
- **Support Page:**  
  See [help.html](help.html) for user guidance.

---

## File Structure

```
.
├── index.html         # Main dashboard UI and all logic (the file shown above)
├── help.html          # Help & FAQ page
└── README.md          # This documentation
```

---

## Quick Start

1. **Clone or Download the Project.**
2. **Open `index.html` directly in any modern web browser.**
   - No build or server needed for basic usage.
   - Ensure an internet connection for API calls and CDN libraries.

---

## How It Works

- **Weather & Forecast:**  
  Uses [OpenWeatherMap API](https://openweathermap.org/api) for current weather (`weather` endpoint) and geocoding,  
  and [Open-Meteo API](https://open-meteo.com/en/docs) for 7-day forecasts.
- **Air Quality:**  
  Uses OpenWeatherMap's Air Pollution endpoint.
- **Search:**  
  Enter a city name in the dashboard's top search bar to update all data cards and the map.
- **Map:**  
  Centers and marks searched city using Leaflet and OpenStreetMap tiles.
- **Graphs:**  
  Chart.js displays 7-day temperature and AQI (Air Quality Index) as a pie chart.

---

## Setup & API Keys

This project uses demo/free public API keys embedded in the code (for demo only):

- For production or your own use:
  1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) to obtain an API key.
  2. Replace the API key values in the JavaScript (look for `appid=...`).
  3. Respect API usage limits.

---

## Usage

- Search any city using the dashboard's search input.
- See the city's live weather, map, 7-day forecast, and air quality.
- Navigate to the Help page or useful news via the sidebar.

---

## Dependencies

- [Leaflet.js](https://leafletjs.com/) for map rendering
- [Chart.js](https://www.chartjs.org/) for chart visualizations
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Open-Meteo API](https://open-meteo.com/en/docs)

All dependencies are loaded via CDN in `index.html`, so no installation is required.

---

## Screenshots

> 💡 _Provide your own screenshots here by adding image links or pasting image files_  
> Example:  
> ![Dashboard](images/dashboard.png)

---

## Help & Support

See [help.html](help.html) in this repository for FAQ and support.

---

## License

This project is open-source and free to use—see [LICENSE](LICENSE) if present.

---

## Credits

Dashboard UI, logic, and integration by [badal484](https://github.com/badal484).

APIs and open-source libraries credited as above.

---

*Star ⭐ this repo to support further development!*
