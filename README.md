# 🌦️ Weather App

A simple and interactive **Weather App** built using HTML, CSS, and JavaScript that allows users to check real-time weather information for any city using the OpenWeatherMap API.

## ✨ Features

- 🌍 **City-Based Search** – Search for weather information by entering a city name.
- 🌡️ **Temperature** – Displays the current temperature in Celsius.
- 💧 **Humidity** – Shows the current humidity percentage.
- 💨 **Wind Speed** – Displays wind speed in km/h.
- ☁️ **Weather Icons** – Displays icons based on weather conditions, such as clouds, clear skies, rain, drizzle, and mist.
- ❌ **Error Handling** – Displays an error message when an invalid city is entered.
- 📱 **Interactive UI** – Updates weather information dynamically without reloading the page.

## 🛠️ Technologies Used

- **HTML5** – Structures the application.
- **CSS3** – Styles the user interface.
- **JavaScript (ES6+)** – Handles application logic and asynchronous API requests.
- **OpenWeatherMap API** – Fetches real-time weather data.
- **Fetch API** – Makes HTTP requests to the weather service.
- **Async/Await** – Handles asynchronous operations.

## 📂 Project Structure

```text
Weather-App/
│
├── index.html
├── style.css
├── script.js
│
└── images/
    ├── clouds.png
    ├── clear.png
    ├── rain.png
    ├── drizzle.png
    └── mist.png
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Navaneetha-21/Weather_app_using_javascript.git
```
### 2. Open the project

Navigate to the project folder and open `index.html` in your browser. You can also use the Live Server extension in Visual Studio Code.

### 3. Configure the API key

1. Create an account at [OpenWeatherMap](https://openweathermap.org/api).
2. Generate an API key.
3. Add your API key in `script.js`.

```javascript
const api_key = "YOUR_API_KEY";
```

**Important:** Do not publish your real API key in a public GitHub repository. For a production application, use a backend server to protect the key.

## ⚙️ How It Works

1. The user enters a city name in the search box.
2. JavaScript sends a request to the OpenWeatherMap API using the Fetch API.
3. The API returns weather data in JSON format.
4. The application extracts the city's name, temperature, humidity, wind speed, and weather condition.
5. The UI updates dynamically with the fetched information and the corresponding weather icon.
6. If the city is not found, an error message is displayed.

## 📚 What I Learned

- Working with third-party REST APIs.
- Using JavaScript's `async/await` and `fetch()`.
- Handling JSON responses and HTTP status codes.
- Updating HTML elements using DOM manipulation.
- Adding event listeners to interactive elements.
- Displaying dynamic content based on API responses.

## 🔮 Future Improvements

- Add a loading indicator while fetching weather data.
- Support searching by pressing the Enter key.
- Handle network errors and invalid API responses.
- Add weather conditions such as snow, thunderstorm, and haze.
- Make the application fully responsive for mobile devices.
- Store recent searches and display a multi-day forecast.

## 👨‍💻 Author

**Navaneetha**

A developer interested in Python,Beckend Development, JavaScript, and AI projects.

---

⭐ If you find this project useful, consider giving the repository a star!
