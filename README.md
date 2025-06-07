# 🌤️ Weather Dashboard using React & OpenWeatherMap API

A sleek, responsive React web application that provides real-time weather updates based on city input. Built with **React.js**, **Vite**, and the **OpenWeatherMap API**, this project demonstrates how to integrate APIs, manage state, and create a user-friendly UI using modern frontend development techniques.

---

## Features

- **Search by City** – Enter any city to fetch current weather data
- **Real-time Weather Info** – Displays temperature, humidity, wind speed, and icon-based conditions
- **Default Weather on Load** – Shows weather for London initially
- **Responsive Design** – Mobile-first layout using Flexbox and custom CSS
- **Fast Performance** – Powered by Vite for rapid development and instant reloads
- **Secure API Key Management** – Using `.env` files for sensitive data

---

## Tech Stack

| Category       | Tool / Tech           |
|----------------|------------------------|
| Framework      | React.js               |
| Build Tool     | Vite                   |
| Styling        | HTML5, CSS3, Flexbox   |
| API            | [OpenWeatherMap](https://openweathermap.org/) |
| State Handling | React Hooks (`useState`, `useEffect`, `useRef`) |
| Deployment     | (Optional) Vercel / Netlify |
| Version Control| Git, GitHub            |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/weather-dashboard.git
cd weather-dashboard
```
# Install Dependencies
### npm install

# Setup Environment Variable
Create a .env file in the root directory:
### VITE_APP_ID=your_openweathermap_api_key

# Run the App
### npm run dev

## Project Structure

```bash
weather-dashboard/
├── public/                         # Public static files
├── src/                            # Source code
│   ├── App.jsx                     # Root component
│   ├── main.jsx                    # Entry point rendering the app
│   ├── index.css                   # Global styles
│   ├── componenta/                 # Components folder
│   │   └── Weather.jsx             # Weather component with API logic
│   ├── assets/
│   │   └── pictures/               # Weather icons (clear, cloud, rain, etc.)
│       ├── search.png
│       ├── clear.png
│       ├── rain.png
│       ├── drizzle.png
│       ├── snow.png
│       ├── humidity.png
│       └── wind.png
├── .env                            # Environment file for API keys (not committed)
├── index.html                      # HTML template used by Vite
├── vite.config.js                  # Vite configuration file
├── package.json                    # Project metadata and scripts
├── package-lock.json               # Dependency lock file
├── README.md                       # Project documentation (this file)



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# Contributors
| Name        | Role                                              |
| ----------- | ------------------------------------------------- |
| Hari Vishnu | Project Setup, API Integration, Core Logic        |
| Nikitha     | UI Components, Weather Display, Styling           |
| Keerthana   | Input Handling, Responsive Design, Error Handling |

