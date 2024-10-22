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

## Preview

![Screenshot 2024-10-21 235857](https://github.com/user-attachments/assets/1241d6d9-87ce-4ae5-98da-0e41a8c5cae5)

![Screenshot 2024-10-22 000043](https://github.com/user-attachments/assets/a688c193-4a33-4259-849c-d74956adabe8)

![Screenshot 2024-10-22 000017](https://github.com/user-attachments/assets/447e2f00-e9be-437d-8c94-6538cebe0716)

![Screenshot 2024-10-22 000000](https://github.com/user-attachments/assets/24ee587b-17f8-4931-9198-1db40d6e81cd)

![Screenshot 2024-10-21 235926](https://github.com/user-attachments/assets/556b42de-bb18-43b4-bcf9-57e99e3a5f37)

![Screenshot 2024-10-22 000059](https://github.com/user-attachments/assets/55db8ba9-292f-4284-9731-7f233c18dced)


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

This web application provides real-time weather data for major metros in India, including Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad. The app fetches data from the OpenWeatherMap API and displays it in an interactive dashboard, allowing users to search for specific cities to view their current weather conditions.

## Key Features
- Real-time weather updates for major Indian metros.
- Search functionality to find weather data for specific cities.
- Temperature trends visualization using interactive charts.
- Alert notifications for high temperatures or extreme conditions.
- Responsive design for both mobile and desktop platforms.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- MongoDB (or access to a MongoDB database)

### 1. Setting Up the Backend
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the backend directory and add the following environment variables:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   OPENWEATHERMAP_API_KEY=your_openweathermap_api_key
   EMAIL_USER=your_email@gmail.com
   EMAIL_PASS=your_email_password
   POLLING_INTERVAL=300000
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### 2. Setting Up the Frontend
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm start
   ```

### Accessing the Application
Open your browser and go to `http://localhost:3000` to view the application.

## Running the Application
You can run both the backend and frontend servers simultaneously. Ensure that:
- The backend server is running on the specified port (default: `5000`).
- The frontend server is running on port `3000`.

## Design Considerations
- **State Management**: The application utilizes React's built-in hooks (`useState` and `useEffect`) for effective state management.
- **API Interaction**: Axios is implemented for cleaner and more concise API calls to fetch weather data from OpenWeatherMap.
- **Responsive Styling**: The user interface is styled using Tailwind CSS for a visually appealing and responsive experience.
- **Data Visualization**: Temperature trends are displayed using Chart.js for easy interpretation.

## API Integration
Weather data is fetched from the OpenWeatherMap API using the following endpoint:
```
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```
Remember to replace `{API_KEY}` with your actual OpenWeatherMap API key.

## Dependencies

### Backend Libraries
- **express**: Fast, unopinionated, minimalist web framework for Node.js.
- **mongoose**: MongoDB object modeling tool.
- **nodemailer**: Module to send emails.
- **axios**: Promise-based HTTP client for both browser and Node.js.
- **dotenv**: Module to load environment variables from a `.env` file.

### Frontend Libraries
- **react**: A JavaScript library for building user interfaces.
- **react-dom**: React package for DOM manipulation.
- **axios**: Promise-based HTTP client used in the frontend for API requests.
- **chart.js**: Charting library for visualizing data.
- **tailwindcss**: Utility-first CSS framework for responsive designs.

