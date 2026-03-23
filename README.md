# ⚡ EcoFlux — Smart Microgrid Energy Management System

EcoFlux is an IoT-based smart energy management system designed to monitor, analyze, and control microgrid energy usage in real time. It integrates sensor data such as fuel level, temperature, and system status with a web dashboard to improve efficiency, detect anomalies, and prevent diesel theft.

---

## 🚀 Features

* 🔌 Real-time energy and sensor monitoring
* ⛽ Fuel level tracking (diesel monitoring)
* 🚨 Theft detection alerts
* 🌡️ Temperature and system health tracking
* 📊 Interactive dashboard with analytics
* ☁️ Firebase real-time database integration
* ⚡ Fast and responsive UI using modern web technologies

---

## 🛠️ Tech Stack

* React (Vite + TypeScript)
* Tailwind CSS
* ShadCN UI
* Firebase Realtime Database
* Recharts

---

## 📂 Project Structure

```
EcoFlux/
│
├── src/
│   ├── firebase.ts
│   ├── services/
│   │     └── firebaseService.ts
│   ├── pages/
│   │     └── Index.tsx
│   ├── components/
│
├── public/
├── package.json
├── vite.config.ts
```

---

## 📡 Example Data Format

```json
{
  "sensorData": {
    "fuelLevel": 45,
    "temperature": 32,
    "theftAlert": false,
    "ultrasonicStatus": "OK"
  }
}
```

---

## 🎯 Use Cases

* Smart microgrid energy optimization
* Diesel theft detection systems
* Industrial energy monitoring
* Remote infrastructure management

---

## 🔮 Future Enhancements

* 📱 Mobile app integration
* 🔔 Alert notification system
* 🤖 AI-based anomaly detection
* 📈 Advanced analytics dashboard
