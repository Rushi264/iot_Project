
# 📡 CIS600 Assignment 3: Cloud-based IoT System with ThingSpeak

## 👨‍💻 Student Details
- **Course**: CIS600 - Internet of Things: Application Development
- **Assignment**: 3 (Spring 2025)
- **Submission Date**: March 26, 2025
- **Channel ID**: 2894456

---

## ✅ 1. Steps Used to Develop the IoT System

1. **Created a ThingSpeak account** and set up a channel with 3 fields:
   - Field1: Temperature
   - Field2: Humidity
   - Field3: CO₂

2. **Generated random sensor values** using Python for a virtual environmental station.

3. **Sent data to ThingSpeak** using the HTTP API with `requests` in Google Colab.

4. **Fetched latest sensor values** and visualized data received during the last 5 hours using Python.

5. **Respected API constraints**, such as the 15-second update limit per channel.

---

## 📸 2. Screenshots of Output

> 📍 *Paste screenshots here (from Colab output and ThingSpeak graphs)*

---

## 🔗 3. GitHub Repository

> GitHub URL: `https://github.com/yourusername/CIS600-Assignment3`  
(*Replace with actual link once uploaded*)

Contents:
- `CIS600_Assignment3_ThingSpeak.ipynb` – Main Jupyter Notebook
- `README.md` – Overview and instructions

---

## 💬 4. Reflection

> *While completing this assignment, I learned how to simulate sensor data and interact with a real cloud IoT platform using REST APIs. One challenge I faced was the "400 response error" when using the wrong API key. After debugging, I realized I was using a Read API key instead of a Write API key. Fixing that and seeing data stream live into ThingSpeak was very satisfying. This assignment helped me understand the importance of keys, rate limits, and cloud data flows in real-world IoT systems.*

---
