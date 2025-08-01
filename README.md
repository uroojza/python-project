🌦 Weather Dashboard – Real-Time Climate Tracker

A Python-based GUI application that displays real-time weather conditions for any city using the OpenWeatherMap API. Users can search by city name and view temperature, humidity, wind speed, and weather conditions in a user-friendly interface.

📌 Features
🔍 Search weather by city name
🌡 View current temperature, humidity, wind speed, and condition
📈 (Upcoming) 3–5 day forecast and temperature trends
📤 (Optional) Export weather data to PDF
⭐ Save favorite or recent cities (optional)
🛠 Tech Stack
Category	Tools/Libraries
Language	Python
GUI	Tkinter
API	OpenWeatherMap API
HTTP	Requests Library
Data	JSON
Graphs	Matplotlib (optional)
Export	ReportLab (optional)
Security	.env to hide API keys (via python-dotenv)
🚀 Getting Started

Clone the repository
bash git clone https://github.com/yourusername/weather-dashboard.git cd weather-dashboard

Install dependencies
bash pip install requests python-dotenv

Set up the .env file
Create a .env file in the root directory and add your API key:

env OPENWEATHER_API_KEY=your_api_key_here

Run the App
bash python main.py

💡 Learnings

Integrating 3rd-party weather APIs
Building user interfaces with Tkinter
Managing secrets and environment variables
Visualizing live data and formatting JSON
Debugging real-time app flows
👥 Authors

Saad Khan – UI/UX, GUI Developer
Urooj Zaheer – Lead Developer, API Integration
📃 License
This project is for educational use only.
