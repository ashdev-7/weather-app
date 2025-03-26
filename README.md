# Weather App 🌦️

## 📌 Project Overview
This is a simple Weather App built using **HTML, CSS, and JavaScript**, with weather data fetched from the **OpenWeatherMap API**. It allows users to check the current weather conditions for any city in the world.

## 🚀 Features
- 🌍 Search weather by city name
- 🌡️ Display temperature, humidity, and weather conditions
- ⚡ Fast and responsive UI using **Vite**

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ashdev-7/weather-app.git
cd weather-app
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Set Up OpenWeatherMap API Key
1. Create a free account at [OpenWeatherMap](https://openweathermap.org/).
2. Get your API key from the **API keys** section.
3. Create a `.env` file in the root directory and add:
   ```
   VITE_API_KEY=your_openweathermap_api_key
   ```

### 4️⃣ Run the Application
```bash
npm run dev
```
Now open the provided local URL in your browser to use the app! 🎉

## 🖥️ Project Structure
```
weather-app/
│── assets/             # Images, icons, and static assets
│── src/
│   ├── main.js         # Main JavaScript logic
│   ├── api.js          # API call functions
│   ├── ui.js           # UI updates and interactions
│── index.html          # Main HTML file
│── style.css           # Styling
│── .env                # API keys and environment variables
│── vite.config.js      # Vite configuration
│── package.json        # Dependencies and scripts
```

