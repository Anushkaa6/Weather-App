# Weather App

A sleek and responsive weather application built using **React.js**, **Vite**, and **Tailwind CSS**. This app fetches real-time weather data for any location, providing users with an intuitive interface and up-to-date information.

## Features

- **Real-time Weather Data**: Fetch current weather conditions for any city or region.
- **Search Functionality**: Search for weather details by entering the name of a location.
- **Dynamic Backgrounds**: The app changes its appearance based on the weather conditions.
- **Responsive Design**: Fully responsive UI, optimized for both desktop and mobile devices.
- **User-friendly Interface**: Minimalistic design with easy navigation.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository.

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and go to:
   ```
   http://localhost:5173
   ```

   ## API Integration

This app integrates with a weather API to fetch real-time data. To use this app, you need an API key:

1. Sign up on [Rapid API](https://rapidapi.com/) and use Visual Crossing weather API provider.
2. Get your API key.
3. Create a `.env` file in the root directory and add your API key:
   ```env
   VITE_API_KEY=your_api_key_here
   ```
4. Restart the development server to apply changes.