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
