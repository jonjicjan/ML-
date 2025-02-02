# Weather App

## Overview
This is a simple weather application built using **React**. It allows users to search for the weather conditions of any city and displays details such as temperature, humidity, wind speed, and more.

## Features
- Search for weather by city name.
- Display current weather conditions including:
  - Temperature
  - Weather description
  - Feels-like temperature
  - Humidity
  - Wind speed
- User-friendly interface with a clean and modern design.
- Responsive layout for mobile and desktop views.

## Technologies Used
- **React.js** (Frontend framework)
- **OpenWeather API** (Weather data provider)
- **Tailwind CSS** (Styling)
- **Lucide React** (Icons)

## Installation

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14 or later)
- **npm** or **yarn**

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd weather-app
   ```
3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
4. Get an API key from [OpenWeather](https://openweathermap.org/api).
5. Create a `.env` file in the root directory and add your API key:
   ```
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```
6. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
7. Open the app in your browser at `http://localhost:3000`.

## Project Structure
```
/weather-app
│── src
│   │── components
│   │   │── Weather.js  # Weather display component
│   │   │── Footer.js   # Footer component
│   │── App.js         # Main application file
│   │── index.js       # Entry point
│   │── styles.css     # Global styles
│── public
│── .env              # Environment variables
│── package.json      # Project dependencies
│── README.md         # Documentation
```

## Usage
1. Enter a city name in the search bar.
2. Press **Enter** or click the search button.
3. View the current weather details.

## Screenshots
(Add screenshots of the app here if available)

## Deployment
You can deploy this app using **Vercel**, **Netlify**, or any hosting service that supports React applications.

Example deployment on Vercel:
```bash
vercel
```

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, feel free to reach out:
- **Email:** your-email@example.com
- **GitHub:** [your-username](https://github.com/your-username)

Happy Coding! 🚀

