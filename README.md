# Weather App

A responsive weather application built with React that allows users to search for real-time weather information for any city.

## Features

* Search weather by city name
* Display current temperature
* Display humidity level
* Display wind speed
* Dynamic weather icons
* Real-time weather data from a Weather API
* Responsive user interface
* Error handling for invalid city searches

## Technologies Used

* React JS
* JavaScript
* CSS
* Weather API

## What I Practiced

This project was built as a practical React learning project. It helped me practice:

* React Components
* `useState` Hook
* API Integration
* Fetching External Data
* Handling User Input
* Conditional Rendering
* Event Handling
* Working with JSON Data
* CSS Styling

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed.

### Installation

Clone the repository:

```bash
git clone https://github.com/Nidal15-ds/weather-app.git
```

Navigate to the project directory:

```bash
cd weather-app
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm run dev 
```

The application will run on:

```text
http://localhost:3000
```

## Project Structure

```text
weather-app/
│
├── node_modules/              # Dependencies (ignored)
├── dist/                      # Build output (generated, ignored)
├── public/                    # Static assets served as-is
│   ├── favicon.svg            # Site favicon
│   └── icons.svg              # Shared SVG icons
│
├── src/                       # Source code
│   ├── assets/                # Static image assets
│   │   ├── clear.png          # Weather icons
│   │   ├── cloud.png
│   │   ├── drizzle.png
│   │   ├── humidity.png
│   │   ├── rain.png
│   │   ├── search.png
│   │   ├── snow.png
│   │   └── wind.png
│   │
│   ├── components/
│   │   ├── Weather.css        # Weather component styles
│   │   └── Weather.jsx        # Main weather widget component
│   │
│   ├── App.jsx                # Root app component
│   ├── main.jsx               # Entry point (ReactDOM render)
│   └── index.css              # Global styles
│
├── .env                       # Environment variables (API key - ignored)
├── .gitignore                 # Git ignore rules
├── eslint.config.js           # ESLint configuration
├── index.html                 # HTML entry point
├── package.json               # Dependencies & scripts
├── package-lock.json          # Locked dependency versions
├── vite.config.js             # Vite configuration
└── README.md

## Future Improvements

* Add weather forecast for multiple days
* Add loading state
* Improve error handling
* Detect user's current location
* Add dark/light mode
* Save recent searches

## Learning Project

This project was created as part of my React learning journey to practice working with APIs and managing application state.

## Author

**Nidal**

GitHub:https://github.com/Nidal15-ds
