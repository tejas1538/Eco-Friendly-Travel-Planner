# 🧭 Eco-Friendly Travel Planner

An intelligent travel planning web application that helps users effortlessly create personalized eco-friendly low carbon itineraries using AI.

## ✨ Objective

To design a digital travel planner that promotes sustainable tourism by helping users plan environmentally responsible trips. The planner aims to reduce carbon footprints, support local communities, and encourage eco-conscious decisions in transport, accommodation, and activities.

## 🧠 Problem It Solves

1. High carbon emissions from tourism
2. Lack of awareness about sustainable accommodation
3. Difficulty finding responsible local experiences
4. Excessive waste and plastic usage
5. Poor access to green travel resources

## 🛠 Tech Stack

### 🔙 Backend (Node.js)
- *Node.js + Express*: Handles API requests and routes.
- *OpenAI or GROQ API*: Powers the itinerary generation with natural language understanding.
- *Modular Structure*: Controllers, services, and routes organized for scalability.

### 🌐 Frontend (React)
- *React*: For building a responsive user interface.
- *React Router*: For navigation between views.
- *Custom CSS*: For minimalist and clean styling.

### 📡 API Communication
- Frontend communicates with the backend via REST API to request and receive AI-generated itineraries.
- Get your GROQ-SDK AI KEY and store it in .env 
---

## 🚀 Features

- User inputs destination, travel duration, and interests.
- AI generates a day-by-day itinerary with recommendations.
- Easy-to-use and minimal UI.
- Fast and personalized results.

---

## 📂 Project Structure

/backend
├── src
│ ├── controllers
│ ├── routes
│ ├── services
│ ├── app.js
│ └── server.js


/frontend
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ └── App.js



---

## 🧪 Setup Instructions

1. *Clone the repository:*

```bash
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
