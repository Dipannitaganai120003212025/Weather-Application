# 🌦️ Weather WebApp
 
A beautiful, responsive, and interactive weather web application built using HTML5, CSS3, and vanilla JavaScript. It retrieves real-time weather information using the OpenWeatherMap API, featuring auto-location detection and dynamic weather condition styling.
 
---
 
## ✨ Features
 
*   🔍 **Global Search:** Find current weather information for any city around the world.
*   📍 **Automatic Geolocation:** Automatically requests user location access on load to fetch and display the weather of the user's current city.
*   📊 **Key Weather Metrics:**
    *   **Temperature:** Current local temperature in Celsius (°C).
    *   **Feels Like:** Apparent temperature details taking humidity and wind into account.
    *   **Humidity:** Relative humidity percentage (%).
    *   **Wind Speed:** Current wind velocity in meters per second (m/s).
*   🎨 **Dynamic Weather Theming:** UI icons and illustrations adjust dynamically based on current weather conditions (e.g., Clear, Clouds, Rain, Thunderstorm, Snow, Mist, Haze/Fog, Tornado, etc.).
*   📱 **Responsive Mobile Layout:** Adaptable layout designed with CSS breakpoints to look sleek and readable on screens as small as 360px.
*   🖋️ **Elegant Typography:** Utilizes Google Fonts (*Rubik* and *Alumni Sans Pinstripe*) combined with radial gradient backdrops and modern glassmorphic container shadows.
 
---
 
## 🛠️ Tech Stack
 
*   **Frontend Structure:** HTML5
*   **Styling:** CSS3 (Radial Gradients, Flexbox, Custom Media Queries)
*   **App Logic & API Integration:** Vanilla JavaScript (ES6 Fetch API, Geolocation API)
*   **Weather API:** [OpenWeatherMap API](https://openweathermap.org/)
*   **Icons:** FontAwesome v6.4.0 & Custom Graphical Weather Assets
 
---
 
## 📁 Directory Structure
 
```text
Weather WebApp/
├── index.html          # Main HTML structure
├── style.css           # Styling, layout, and responsive styles
├── script.js           # Fetch logic, coordinate mapping, and DOM updates
├── config.js           # Configuration file for API keys
└── myImg/              # Weather illustration and metric icon assets
    ├── sun.png
    ├── rain.png
    ├── wind.png
    ├── humidity.png
    ├── thermometer.png
    └── ... (other weather assets)
```
 
---
 
## 🚀 Setup & Local Installation
 
To run this application locally on your computer, follow these simple steps:
 
### 1. Clone or Download the Project
```bash
git clone https://github.com/your-username/Weather-WebApp.git
cd Weather-WebApp
```
 
### 2. Configure Your API Key
The application relies on the OpenWeatherMap API.
1. Go to [OpenWeatherMap](https://openweathermap.org/) and sign up for a free account.
2. Generate a free API Key (AppID) from your account dashboard.
3. Open `script.js` (and optionally `config.js`) and update the API Key variable with your key:
   ```javascript
   const apiKey = "YOUR_OPENWEATHERMAP_API_KEY";
   ```
 
### 3. Run the App
Since the application uses the browser's **Geolocation API** (which requires a secure context or local server environment in many browsers), running it via a local server is recommended:
 
*   **Option A: VS Code Live Server (Recommended)**
    1. Install the **Live Server** extension in VS Code.
    2. Right-click on `index.html` and select **"Open with Live Server"**.
    3. The application will launch automatically at `http://127.0.0.1:5500`.
 
*   **Option B: Simple Python Server**
    If you have Python installed, you can start a simple server from the project directory:
    ```bash
    # Python 3
    python -m http.server 5500
    ```
    Now, visit `http://localhost:5500` in your web browser.
 
---
 
## 📝 License
 
This project is open-source. Feel free to use, modify, and distribute it as you see fit.
