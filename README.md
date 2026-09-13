# 🌥️ Weather App

A clean, responsive **weather application** built with **React** that fetches live weather data using the **OpenWeatherMap API**.

Search for any city and instantly view its current temperature, humidity, wind speed, and weather conditions.




## 🛠️ Tech Stack

* ⚛️ **React** — component-based UI with Hooks (`useState`, `useEffect`, `useRef`)
* ⚡ **Vite** — fast development server and build tool
* 🎨 **CSS** — responsive design using Flexbox, `clamp()`, and media queries
* 🌐 **OpenWeatherMap API** — live weather data
* 📦 **Vercel** — deployment

## ✨ Features

* 🔍 Search weather by city name
* 🌡️ Temperature displayed in Celsius
* 💧 Humidity percentage
* 💨 Wind speed in km/h
* 🖼️ Dynamic weather icons based on weather conditions
* 📱 Fully responsive design
* ⚠️ Error handling for invalid city names
* ⏳ Loading state while fetching weather data
* 🌍 Displays city and country information

## 🧠 What I Learned

Building this project helped me practice the fundamentals of **React Hooks** and working with external APIs.

* 🔁 **`useState`** — managing weather data, loading states, and errors
* ⏳ **`useEffect`** — fetching the default city's weather when the component mounts
* 🎯 **`useRef`** — accessing the search input without causing unnecessary re-renders
* 🌍 **Fetch API + async/await** — consuming a third-party REST API
* 🧑‍🎨 **Dynamic rendering** — displaying different weather icons based on API condition codes
* 🔐 **Environment variables** — storing the API key outside the source code
* 🚀 **Deployment** — building and deploying a Vite React application with Vercel

## 💻 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Nidal15-ds/weather-app.git
cd weather-app
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure the API Key

Create a `.env` file in the root directory:

```env
VITE_APP_ID=your_openweathermap_api_key
```

Get an API key from [OpenWeatherMap](https://openweathermap.org/api).

**Important:** Never commit your `.env` file to GitHub.

Make sure `.env` is included in `.gitignore`:

```gitignore
.env
```

### 4️⃣ Run the Development Server

```bash
npm run dev
```

Open the local URL shown in your terminal, usually:

```text
http://localhost:5173
```

### 📦 Build for Production

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 🌐 Deployment

This project is deployed using **Vercel**.

For production deployment, configure the following environment variable in Vercel:

```text
VITE_APP_ID=your_openweathermap_api_key
```

## 📁 Project Structure

```text
weather-app/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Weather.jsx
│   │   └── Weather.css
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .env
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## 🚀 Live Demo

👉 **[weather-infos.vercel.app](https://weather-infos.vercel.app/)**

## 👨‍💻 Author

**Nidal**

GitHub: [Nidal15-ds](https://github.com/Nidal15-ds)

