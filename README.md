# 🌦️ Python Weather App (Tkinter + Free API)

A simple **Python Weather Application** built using **Tkinter GUI** and the **Open-Meteo Free Weather API**.  
This app displays real-time weather information:

- 🌡️ **Temperature (°C)**
- 🌬️ **Wind Speed (km/h)**
- ☁️ **Weather Code**
- ✅ **No API key required**

---

## 🚀 Features

✔ Free Weather API (Open-Meteo)  
✔ No API key needed  
✔ Tkinter GUI  
✔ Real-time Temperature  
✔ City Search  
✔ Error Handling  
✔ Lightweight & Easy to Understand  

---

## 🛠️ Technologies Used

- Python  
- Tkinter (GUI)  
- Requests (API calls)  
- Open-Meteo Weather API  

---

## 📂 Project Structure

```
weather-app/
│
├── weather_app.py        # Main application file
└── README.md             # Project documentation
```

---

## 📦 Installation

### 1️⃣ Clone this repository
```bash
git clone https://github.com/your-username/weather-app.git
```

### 2️⃣ Navigate to project
```bash
cd weather-app
```

### 3️⃣ Install dependencies
```bash
pip install requests
```

---

## ▶️ How to Run

```bash
python weather_app.py
```

---

## 📡 How It Works

### 🔹 Step 1: User enters a city  
Fetches latitude & longitude using Open-Meteo Geocoding API:

```
https://geocoding-api.open-meteo.com/v1/search?name={city}
```

### 🔹 Step 2: Fetch weather details  
Using Open-Meteo Forecast API:

```
https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&current_weather=true
```

### 🔹 Step 3: Display results in Tkinter GUI  

---

## 📌 Example Output

```
Weather in Delhi:
Temperature: 26 °C
Wind Speed: 12 km/h
Weather Code: 1
```

---

## ❗ Error Handling

The app handles:

- City not found  
- Empty input  
- Internet/network errors  

---

## ⭐ Future Improvements

- Add Humidity & Pressure  
- Add Weather Icons  
- Dark Mode UI  
- 5-Day Forecast  
- Improved UI Theme  

---

## 🤝 Contributing

Pull requests are welcome.  
Feel free to suggest new features or improvements.

---

## 📜 License

This project is **open-source** and free to use.
