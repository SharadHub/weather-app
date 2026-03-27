# Weather App 🌤️
A full-stack weather application that lets users search for real-time weather data for any city in the world. Built with a React frontend and a Node.js backend powered by the OpenWeatherMap API.

---

## 🔗 Live Demo

> [Link is not ready yet](#)

---

## 📸 Screenshots

| Home Screen | Search Results |
|-------------|----------------|
| ![Home](coming soon) | ![Results](coming soon) |

>

---

## Features

- 🔍 Search weather by city name
- 🌡️ Displays real-time temperature (°C)
- 🌥️ Shows weather conditions and descriptions
- ⚡ Fast and responsive React UI
- 🔌 Node.js backend with OpenWeatherMap integration

---

## Project Structure

```
weather-app/
├── weather-app-frontend    # React.js frontend is yet to make
│
└── weather-app-backend/
├── .gitignore              # Git ignore file
├── README.md               # Documentation
├── node_modules/           # Dependencies
├── package.json            # Project configuration
├── package-lock.json       # Dependency lock file
└── weather.js              # Main application file
```

---

## Tech Stack

| Layer    | Technology                     |
|----------|-------------------------------|
| Frontend | React, JavaScript (ES Modules) |
| Backend  | Node.js, ES Modules            |
| API      | OpenWeatherMap API             |
| HTTP     | Axios                          |

---

## Requirements

- Node.js (ES Modules support)
- npm
- OpenWeatherMap API key → [Get one free here](https://openweathermap.org)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2. Set up the Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend/` directory:

```env
OPENWEATHER_API_KEY=your_api_key_here
```

Start the backend server:

```bash
node weather.js
```

### 3. Set up the Frontend

```bash
cd ../frontend
npm install
npm run dev
```

The app will be available at `http://localhost:YOUR_PORT_NO`.

---

## Environment Variables

| Variable              | Location         | Description                      |
|-----------------------|-----------------|----------------------------------|
| `OPENWEATHER_API_KEY` | `backend/.env`  | Your OpenWeatherMap API key      |

> Never commit your `.env` file. Make sure it's listed in `.gitignore`.

---

## Dependencies

### Backend
- [`axios`](https://axios-http.com/) — HTTP client for API requests

### Frontend
- [`react`](https://react.dev/) — UI library
- [`axios`](https://axios-http.com/) — HTTP requests to the backend

---

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for the free weather API
---

*Made by [Sharad Bista](https://github.com/SharadHub)*
