# 🌱 GrowSync – Smart Agriculture IoT System  
### Internet of Things – Group Project

**GrowSync** is a fully designed **smart agriculture IoT ecosystem** built to optimize farming through automation, real-time monitoring, cloud analytics, and mobile-based control.  

This project addresses real agricultural challenges such as fluctuating weather, soil instability, pest activity, inconsistent crop growth, and operational inefficiency.

GrowSync integrates **sensors**, **microcontrollers**, **wireless communication**, **cloud platforms**, **mobile applications**, and **machine learning** to create an end-to-end intelligent farming system.

---

## 🌾 Project Overview

GrowSync solves four core agricultural problems:

### 🚜 **1. Improper Soil Quality Monitoring**  
Manual soil checking is inaccurate and time-consuming.

### 🌡 **2. Environmental Instability**  
Temperature, humidity, and air quality fluctuate unpredictably.

### 🐛 **3. Crop Disturbances**  
Pests, animals, or human activities can damage crops.

### 🧪 **4. Chemical Imbalance**  
Incorrect pH or nutrient levels lead to poor growth.

These problems lead to reduced yield, plant stress, and increased operational cost.  

GrowSync provides a **scalable, automated, and data-driven solution**.

---

# 🧰 GrowSync System Architecture

GrowSync follows a structured **IoT layered architecture**, ensuring reliability and scalability.

## 🔹 **1. Perception Layer – Sensors & Actuators**
Hardware installed at the farm:
- **DHT22** – Temperature & humidity  
- **MQ135** – Air quality  
- **LSPH01** – Soil pH & moisture  
- **PIR (HC-SR501)** – Motion detection (animals & intruders)  
- **GPS (NEO-6M)** – Location tracking  
- **Actuators:**  
  - Ventilation fans  
  - Water pumps  
  - pH balancing pumps  
  - Solenoid valves  
  - Buzzer & LCD display  

---

## 🔹 **2. Gateway Layer – Arduino + ESP32**
- **Arduino Mega 2560** handles sensor readings & actuator control  
- **ESP32** enables Wi-Fi connectivity and sends data to the cloud via **MQTT**  
- Local anomaly filtering ensures only meaningful data is transmitted

---

## 🔹 **3. Cloud Layer – AWS Architecture**
GrowSync integrates a cloud ecosystem using:
- **AWS IoT Core** – MQTT device communication  
- **AWS Timestream** – Time-series sensor data  
- **AWS RDS (MySQL)** – Farm configuration & user data  
- **AWS S3** – Storage for logs and reports  
- **AES-128 / AES-256 encryption** – End-to-end security  

---

## 🔹 **4. Application Layer – Mobile App (Flutter)**
A farmer-focused mobile app offering:
- OTP-secured login  
- Real-time monitoring dashboards  
- Crop zone analysis (soil, environment, pH trends)  
- Alerts for pests, anomalies, or extreme conditions  
- Weather forecasting  
- Irrigation scheduling  
- Growth charts & sensor history  

*(UI shown in presentation slides — Home, Alerts, Analysis, Settings)*

---

# 🤖 Automation Features

## 🌬 **1. Ventilation Control**  
Fans activate automatically when temperature or CO₂ levels exceed thresholds.

## 💧 **2. Smart Irrigation System**  
Watering is triggered by soil moisture and environmental conditions.

## 🧪 **3. pH Balancing System**  
Acid or alkaline solutions are dispensed to maintain optimal soil pH.

## 🛡 **4. Pest Detection & Response**  
PIR sensor + buzzer/fan discourage animals and intruders.

## 📉 **5. Anomaly Detection**  
ESP32 filters faulty sensor readings (impossible values, sudden spikes).

## 🔄 **6. Multi-Zone Synchronization**  
Farm divided into zones (A, B, C), each monitored individually.

---

# 📊 Data Analytics & Machine Learning

The system uses analytics to enhance decision-making:

### 🔹 **Time-Series Forecasting**  
Predicts future light intensity for optimal plant growth.

### 🔹 **Sensor Anomaly Detection**  
Identifies missing, corrupted, or unrealistic sensor values.

### 🔹 **Crop Growth & Yield Prediction**  
Analyzes environmental and soil parameters.

### 🔹 **Risk Assessment**  
Combines weather, temperature, air quality, and sensor anomalies to determine crop health risk.

These insights help farmers take proactive actions.

---

# 🧩 Key Diagrams (from reports & slides)
Included inside the PDFs:
- System Architecture Diagram (perception → cloud → app)  
- AWS Cloud Integration Diagram  
- Sensor Node Circuit Diagram  
- GrowSync Mobile App UI Screens  
- LoRaWAN & ZigBee Mesh Topology  
- Use Case & Data Flow Diagrams  
- Sequence Diagrams  
- Entity Relationship Diagram (ERD)  

These visuals demonstrate strong technical documentation.

---

# 🧠 Skills Demonstrated

### 🔧 **Technical IoT Skills**
- IoT ecosystem design (hardware + software)  
- Arduino & ESP32 integration  
- Sensor calibration & filtering  
- MQTT communication  
- Cloud deployment with AWS  
- Wireless technologies: ZigBee, LoRaWAN  
- Data encryption & secure communication  

### 💡 **Software Engineering & Mobile Development**
- Flutter UI development  
- OTP & authentication flows  
- Real-time data visualization  
- API & database structuring  

### 🧪 **Data Analytics & Machine Learning**
- Time-series forecasting  
- Anomaly detection  
- Crop yield prediction  
- Statistical analysis & visualization  

### 👥 **Project Management & Research**
- Multi-part group collaboration  
- Technical report writing  
- Engineering diagrams & presentations  
- Problem-solving & solution design  

---

# ✨ Summary

GrowSync is a **professional-level IoT agriculture system**, combining embedded systems, automation, cloud engineering, data analytics, and mobile development into one cohesive solution.  

It shows strong capabilities in **IoT engineering, cloud integration, smart farming, and system design** — making this one of the most impactful projects in my IoT portfolio.

---

✨ *Thank you for exploring the GrowSync IoT System!*
