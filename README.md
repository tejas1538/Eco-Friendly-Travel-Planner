🧭 AI-Driven Eco-Friendly Trip Planner
An intelligent travel planning web application that helps users effortlessly create sustainable and personalized itineraries using AI.

✨ Overview
Planning a trip can be overwhelming — from finding attractions to minimizing your environmental footprint. The Eco-Friendly AI Trip Planner makes this easy by generating custom, low-impact travel itineraries based on user input such as destination, duration, travel preferences, and sustainability goals.

With a clean user interface and AI-powered backend, the app simplifies the planning process while promoting green travel choices.

🧠 Problem It Solves
Traditional trip planning is not only time-consuming but often overlooks sustainability. Travelers struggle to:

Research destinations with eco-conscious options

Balance interests, travel time, and environmental impact

Discover green transportation, eco-lodging, and local ethical experiences

Avoid switching between multiple tools (maps, blogs, guides, sustainability apps)
This project offers an all-in-one smart solution that uses AI to create personalized, efficient, and eco-friendly travel plans. It helps users make informed choices that are better for them — and for the planet

🛠️ Tech Stack
🔙 Backend (Node.js)
Node.js + Express: Handles API requests and routes.
OpenAI or GROQ API: Powers the itinerary generation with natural language understanding.
Modular Structure: Controllers, services, and routes organized for scalability.
🌐 Frontend (React)
React: For building a responsive user interface.
React Router: For navigation between views.
Custom CSS: For minimalist and clean styling.
📡 API Communication
Frontend communicates with the backend via REST API to request and receive AI-generated itineraries.
Get your GROQ-SDK AI KEY and store it in .env
🚀 Features
User inputs destination, travel duration, and interests.
AI generates a day-by-day itinerary with recommendations.
Easy-to-use and minimal UI.
Fast and personalized results.
📂 Project Structure
/backend ├── src │ ├── controllers │ ├── routes │ ├── services │ ├── app.js │ └── server.js

/frontend ├── public/ ├── src/ │ ├── components/ │ ├── pages/ │ └── App.js

🧪 Setup Instructions
Clone the repository:
git clone https://github.com/Shivang-6/AI_Trip_planner
cd ai-trip-planner

Setup backend:
cd backend
npm install cors axios dotenv express groq-sdk
# Add your API key in src/services/groqService.js or equivalent
node src/server.js


Setup frontend:
cd frontend
npm install react react-dom react-router-dom 
npm start


Built with passion to make travel planning effortless.
