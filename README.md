# Travel-App

## Description
Developed a web application designed to revolutionize travel planning by generating personalized itineraries based on user preferences. It provides comprehensive trip details including activities, accommodations, dining options, and weather forecasts, ensuring a seamless travel experience.

## Features
- Personalized travel itinerary generation using user preferences.
- Weather forecasting for trip duration.
- Hotel and restaurant recommendations based on location.
- User authentication and profile management for saving itineraries.
- Interactive maps for location data and recommendations.

## Technologies Used
### Frontend:
- **React.js** for building the user interface.
- **CSS** for styling and responsive design.

### Backend:
- **Node.js** with **Express.js** for server-side logic.
- **MongoDB** for database management.
- **JSON Web Tokens (JWT)** for user authentication.

### APIs:
- **Google Maps API** for location data and recommendations.
- **Visual Crossing Weather API** for weather forecasting.

## Installation

1. Clone the repository
2. Install the dependencies for both frontend and backend
3. Set up environment variables by creating a .env file in the backend directory and adding your API keys:
   
   - MONGODB_URI=your_mongo_db_uri
   - JWT_SECRET=your_jwt_secret
   - GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   - WEATHER_API_KEY=your_weather_api_key
   - GEMINI_API_KEY=your_gemini_api_key

4. Start both frontend and backend servers:
5. Open your browser and go to local host.

## Usage
Once running, users can sign up, log in, and enter their travel preferences to generate a personalized itinerary. The app will provide tailored recommendations for activities, accommodations, dining, and weather forecasts for the trip duration.
