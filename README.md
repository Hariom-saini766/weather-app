Python Weather App (Tkinter + Free API)

A simple Python Weather Application built using Tkinter GUI and the Open-Meteo Free Weather API.
This app shows real-time weather information such as:

Temperature (°C)

Wind Speed (km/h)

Weather Code (Weather Condition)

No API key required — works completely free.

🚀 Features

✔ Free Weather API (Open-Meteo)

✔ No API key needed

✔ Tkinter GUI

✔ Real-time Temperature

✔ City Search

✔ Error Handling

✔ Lightweight & Easy to Understand

🛠️ Technologies Used

Python

Tkinter (GUI)

Requests (API calls)

Open-Meteo Weather API

📂 Project Structure
weather-app/
│
├── weather_app.py
└── README.md

📦 Installation
1️⃣ Clone this repository
git clone https://github.com/your-username/weather-app.git

2️⃣ Navigate to project
cd weather-app

3️⃣ Install dependencies
pip install requests

▶️ How to Run
python weather_app.py

📡 How It Works
🔹 Step 1: User enters a city
🔹 Step 2: City → Latitude & Longitude

Uses Open-Meteo Geocoding API:

https://geocoding-api.open-meteo.com/v1/search?name={city}

🔹 Step 3: Fetch weather

Uses Forecast API:

https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&current_weather=true

🔹 Step 4: Display results in Tkinter
📌 Example Output
Weather in Delhi:
Temperature: 26 °C
Wind Speed: 12 km/h
Weather Code: 1

❗ Error Handling

The app shows warnings for:

City not found

Empty input

Internet/network error

⭐ Future Improvements

Add humidity & pressure

Add weather icons

Dark mode UI

5-day forecast

Better theme/UI enhancements

🤝 Contributing

Pull requests are welcome!
Feel free to suggest new features.

📜 License

This project is open-source and free to use.
