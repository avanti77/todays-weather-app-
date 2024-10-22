# Weather Monitoring System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Running the Application](#running-the-application)
- [Design Choices](#design-choices)
- [API Integration](#api-integration)
- [Dependencies](#dependencies)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [License](#license)

## Introduction
The **Weather Monitoring System** is a web application that provides real-time weather data for major cities in India, including Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad. The application fetches weather data from the OpenWeatherMap API and displays it in an interactive dashboard. Users can search for specific cities to view their current weather conditions and temperature trends.

## Features
- Real-time weather updates
- City search functionality
- Temperature trends visualization using charts
- Alert notifications for high temperatures
- Responsive design for both mobile and desktop

## Technologies Used
- **Frontend**: React, Axios, Chart.js, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB
- **API**: OpenWeatherMap API
- **Deployment**: Heroku (or any preferred hosting solution)

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (v14 or higher)
- MongoDB (local or cloud database)
- Git (optional, for cloning the repository)

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/sameer0288/weather-monitoring-system.git
   cd weather-monitoring-system
# Weather Monitoring System

A web application that provides real-time weather data for major metros in India, including Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad. The app fetches data from the OpenWeatherMap API and displays it in an interactive dashboard, allowing users to search for specific cities to view their current weather conditions.

## Installation

### 1. Backend Setup
Navigate to the backend directory:
```bash
cd backend
```

Install dependencies:
```bash
npm install
```

Create a `.env` file in the backend directory and add the following environment variables:
```env
PORT=5000
MONGODB_URI=your_mongodb_uri
OPENWEATHERMAP_API_KEY=your_openweathermap_api_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
POLLING_INTERVAL=300000
```

Start the backend server:
```bash
npm start
```

### 2. Frontend Setup
Navigate to the frontend directory:
```bash
cd ../frontend
```

Install dependencies:
```bash
npm install
```

Start the frontend development server:
```bash
npm start
```

### Access the Application
Open your browser and navigate to `http://localhost:3000` to view the application.

## Running the Application
After completing the installation steps, you can run both the backend and frontend servers simultaneously. Ensure that the backend server is running on the specified port (default: `5000`) and the frontend on port `3000`.

## Design Choices
- **State Management**: The application uses React's built-in hooks (`useState` and `useEffect`) for state management, making the code simple and maintainable.
- **API Calls**: Axios is used for API calls to fetch weather data from OpenWeatherMap, providing a cleaner and more concise way to handle HTTP requests.
- **Responsive Design**: The application is styled using Tailwind CSS to ensure a responsive and visually appealing user interface.
- **Charts**: The temperature trends are visualized using Chart.js, allowing for easy interpretation of data.

## API Integration
The application fetches weather data from the OpenWeatherMap API using the following endpoint:
```
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```
Make sure to replace `{API_KEY}` with your actual OpenWeatherMap API key.

## Dependencies

### Backend Dependencies
- **express**: Fast, unopinionated, minimalist web framework for Node.js.
- **mongoose**: MongoDB object modeling tool.
- **nodemailer**: Module to send emails.
- **axios**: Promise-based HTTP client for the browser and Node.js.
- **dotenv**: Module to load environment variables from a `.env` file.

### Frontend Dependencies
- **react**: A JavaScript library for building user interfaces.
- **react-dom**: React package for working with the DOM.
- **axios**: Promise-based HTTP client for the browser and Node.js (used in frontend).
- **chart.js**: Charting library for visualizing data.
- **tailwindcss**: Utility-first CSS framework for creating responsive designs.

