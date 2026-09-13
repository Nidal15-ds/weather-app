# 🌥️ Weather App

A clean, responsive **weather application** built with **React** that fetches live weather data using the **OpenWeatherMap API**. Just type any city name and get the current temperature, location, humidity, and wind speed instantly. ☀️🌧️❄️

## 🚀 Live Demo

👉 **[weather-infos.vercel.app](https://weather-infos.vercel.app/)**

## 🛠️ Tech Stack

- ⚛️ **React** — component-based UI with hooks (`useState`, `useEffect`, `useRef`)
- ⚡ **Vite** — fast development server & build tool
- 🎨 **CSS** — fully responsive design using `clamp()`, flexbox & media queries
- 🌐 **OpenWeatherMap API** — real-time weather data
- 📦 **Vercel** — deployment

## 🧠 What I Learned

Building this project taught me the fundamentals of **React Hooks**:

- 🔁 **`useState`** — managing dynamic state (weather data, loading states)
- ⏳ **`useEffect`** — running side effects on mount (fetching default city weather)
- 🎯 **`useRef`** — accessing the search input value directly without re-renders
- 🌍 **Fetch API + async/await** — consuming third-party REST APIs
- 🧑‍🎨 **Dynamic icon mapping** — switching weather icons based on API condition codes
- 📱 **Responsive CSS** — building mobile-first UIs that scale from small phones to large desktops

## 📝 Features

- 🔍 Search weather by any city name
- 🌡️ Temperature in Celsius
- 💧 Humidity percentage
- 💨 Wind speed in Km/H
- 🖼️ Dynamic weather icons (clear, clouds, rain, snow, drizzle)
- 📱 Fully responsive on all screen sizes
- ⚠️ Error handling for invalid city names

## 💻 Getting Started

### 1️⃣ Clone the Project

```bash
git clone https://github.com/Nidal15-ds/weather-app.git
cd weather-app
2️⃣ Install Dependencies
npm install
3️⃣ Add Your API Key
Create a .env file in the root folder and add:
VITE_APP_ID=your_openweathermap_api_key
💡 Get a free API key at openweathermap.org (https://openweathermap.org/api)
4️⃣ Run the Dev Server
npm run dev
Open http://localhost:5173 (http://localhost:5173) in your browser. 🎉
📦 Build for Production
npm run build
npm run preview
🤝 Let's Connect
Made with ❤️ by Nidal
