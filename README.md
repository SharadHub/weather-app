# 🌤️ Weather App

A full-stack weather application that lets users search for real-time weather data for any city in the world. Built with a React frontend and a Node.js backend powered by the OpenWeatherMap API.

---

## 🔗 Live Demo

> [Click here to view the live app](#) *(add your deployment URL here)*

---

## 📸 Screenshots

| Home Screen | Search Results |
|-------------|----------------|
| ![Home](https://via.placeholder.com/500x300?text=Home+Screen) | ![Results](https://via.placeholder.com/500x300?text=Search+Results) |

> 💡 *Replace the placeholders above with actual screenshots of your app.*

---

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Displays real-time temperature (°C)
- 🌥️ Shows weather conditions and descriptions
- ⚡ Fast and responsive React UI
- 🔌 Node.js backend with OpenWeatherMap integration

---

## 🗂️ Project Structure

```
weather-app/
├── frontend/               # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
└── backend/                # Node.js backend
    ├── weather.js
    └── package.json
```

---

## 🛠️ Tech Stack

| Layer    | Technology                     |
|----------|-------------------------------|
| Frontend | React, JavaScript (ES Modules) |
| Backend  | Node.js, ES Modules            |
| API      | OpenWeatherMap API             |
| HTTP     | Axios                          |

---

## ⚙️ Requirements

- Node.js v18+ (ES Modules support)
- npm
- OpenWeatherMap API key → [Get one free here](https://openweathermap.org/api)

---

## 🚀 Getting Started

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

The app will be available at `http://localhost:5173`.

---

## 🔑 Environment Variables

| Variable              | Location         | Description                      |
|-----------------------|-----------------|----------------------------------|
| `OPENWEATHER_API_KEY` | `backend/.env`  | Your OpenWeatherMap API key      |

> ⚠️ Never commit your `.env` file. Make sure it's listed in `.gitignore`.

---

## 📦 Dependencies

### Backend
- [`axios`](https://axios-http.com/) — HTTP client for API requests

### Frontend
- [`react`](https://react.dev/) — UI library
- [`axios`](https://axios-http.com/) — HTTP requests to the backend

---

## 🤝 Contributing

Contributions are welcome! Here's how to get involved:

1. **Fork** the repository
2. **Create** a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes with a clear message:
   ```bash
   git commit -m "feat: add your feature description"
   ```
4. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** — describe what you changed and why

### Contribution Guidelines
- Keep pull requests focused and small
- Follow the existing code style
- Test your changes before submitting
- Update documentation if your change requires it

---

## 🙏 Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for the free weather API
- [React](https://react.dev/) and [Node.js](https://nodejs.org/) communities

---

*Made with ☀️ by [Your Name](https://github.com/your-username)*
