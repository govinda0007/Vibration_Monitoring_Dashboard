# 🛰️ Enterprise IoT Vibration Monitoring System  
### ESP32 + SW-420 + MQTT + AWS EC2 + Realtime Dashboard + MongoDB + Alerts 🚨

This project monitors real-time vibration data using **ESP32 & SW-420**, analyzes activity, sends alerts to the AWS cloud, and displays live data in a web dashboard.

---

## 🔥 Technologies Used
![Tech](https://img.shields.io/badge/IoT-ESP32-blue)
![NodeJS](https://img.shields.io/badge/Backend-Node.js-green)
![MQTT](https://img.shields.io/badge/Protocol-MQTT-yellow)
![DB](https://img.shields.io/badge/Database-MongoDB-brightgreen)
![SocketIO](https://img.shields.io/badge/Realtime-Socket.io-critical)
![Cloud](https://img.shields.io/badge/Cloud-AWS-orange)
![License](https://img.shields.io/badge/License-MIT-success)

---

## 📡 System Architecture
<img src="assets/architecture.png" width="650">

### Flow:
1️⃣ SW-420 detects vibration  
2️⃣ ESP32 publishes data via MQTT  
3️⃣ EC2 broker stores logs into **MongoDB**  
4️⃣ Dashboard visualizes live activity  
5️⃣ Email/Telegram alert if vibration exceeds threshold  

---

## 🖥️ Real-time Dashboard Preview
<img src="assets/dashboard-demo.gif" width="650">

---

## ✉️ Smart Alerts  
✔ Instant email alert  
✔ Telegram bot notification  

---

## 🗄 Database Logging (MongoDB)
Every alert + normal log is saved for analysis:
