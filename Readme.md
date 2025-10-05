# 🌦️ Local Weather App

A **simple, real-time weather application** built with **HTML, CSS, and JavaScript**.
This app automatically detects your **current location** using the **Geolocation API**, fetches **live weather data** from the **Open-Meteo API**, and displays it in a clean, responsive interface.

---

## 🚀 Features

* 🌍 **Auto Location Detection** — Uses your device’s location to fetch local weather.
* ☀️ **Real-Time Weather Data** — Fetches up-to-date weather information (temperature, wind speed, and time).
* 💎 **Clean & Fancy UI** — Beautiful gradient background with modern, minimal styling.
* 📱 **Responsive Design** — Works perfectly on mobile and desktop browsers.
* ⚡ **Fast & Lightweight** — No external libraries, just pure HTML, CSS, and JS.

---

## 🧠 How It Works

1. The app requests your **geolocation** using `navigator.geolocation`.
2. Once permission is granted, it retrieves your **latitude and longitude**.
3. It then makes a request to the **Open-Meteo API** using your coordinates.
4. The API responds with current weather data, which is displayed dynamically on the page.

---

## 🛠️ Tech Stack

| Technology               | Purpose                    |
| ------------------------ | -------------------------- |
| **HTML5**                | Structure and markup       |
| **CSS3**                 | Styling and responsiveness |
| **JavaScript (Vanilla)** | Logic and API integration  |
| **Open-Meteo API**       | Provides live weather data |

---

## ⚙️ Setup Instructions

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/local-weather-app.git
   cd local-weather-app
   ```

2. **Open the project**
   Open `index.html` directly in your browser (no server needed).

3. **Allow Location Access**
   When prompted, allow the browser to access your location.

4. **View Your Local Weather**
   Instantly see your temperature, wind speed, and local time!

---

## 📸 Preview

*(Add a screenshot of your app UI here)*
Example:

```markdown
![Local Weather App Screenshot](screenshot.png)
```

---

## 🌐 API Reference

This project uses the free **[Open-Meteo Weather API](https://open-meteo.com/)**.
Example API call used in the app:

```
https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&current_weather=true
```

---

## 🚧 Error Handling

The app gracefully handles:

* ❌ Location permission denied
* 📶 No network connection
* 🕒 Request timeouts
* ⚙️ Unknown API or browser errors

Error messages are shown directly in the UI.

---

## 💡 Future Enhancements

* 🌤 Add weather icons and conditions (e.g., “Sunny”, “Cloudy”)
* 📅 Include 7-day forecast view
* 🌡 Toggle between °C and °F
* 🕹 Add animations for UI transitions

---

## 👨‍💻 Author

**Bishop Odedeyi**
Full-Stack & Systems Developer
🔗 [GitHub](https://github.com/BishopOdedeyi)
