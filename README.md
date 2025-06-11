# RoadBuddy - Driving Confidence App

An application to help new drivers gain confidence through personalized driving routes.

## Features
- Generate driving routes based on skill level
- Location-based route suggestions
- Progress tracking
- Difficulty levels: Easy, Medium, Hard

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Flask backend:
```bash
python app.py
```

3. The backend will run on http://localhost:5000

## API Endpoints

- POST /api/generate-route
- GET /api/user-progress

## Frontend

The frontend is built with React Native and will be available in the `mobile` directory.

## Tech Stack

- Backend: Flask
- Database: SQLite
- Location Services: Geopy
- Frontend: React Native
- Maps: Google Maps API
