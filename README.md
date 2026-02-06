# Heart Throb ❤️  
### Proactive AI + IoT Smartwatch for Predicting and Preventing Heart Attacks

Heart Throb is a low-cost, AI-powered IoT wearable designed to **predict cardiac distress before a heart attack occurs** and trigger **real-time emergency response**. Unlike traditional wearables that only monitor vitals, Heart Throb functions as a **predict-and-protect system**, targeting elderly and rural populations with limited access to timely healthcare.

---

## 📌 Problem Statement

Heart disease is the leading cause of death globally and in India, where delayed symptom recognition and limited rural healthcare infrastructure lead to preventable fatalities.  
Existing wearables act as passive trackers and fail to:
- Interpret complex cardiac patterns  
- Predict pre-symptomatic distress  
- Initiate automated emergency response  

There is a critical need for a **proactive, affordable, and explainable cardiac monitoring system**.

---

## 💡 Solution Overview

Heart Throb continuously monitors vital physiological signals and uses **Temporal Fusion Transformer (TFT)** models to predict early cardiac anomalies.  
When a critical risk is detected, the system **automatically alerts caregivers, hospitals, and emergency responders** via multiple communication channels.

---

## 🚀 Key Features

- Continuous monitoring of HRV, ECG, SpO₂, Blood Pressure, EDA, and motion data  
- AI-based multivariate time-series prediction using Temporal Fusion Transformer  
- Explainable AI (XAI) to justify alerts for clinical trust  
- Personalized baseline learning to reduce false alarms  
- Multi-channel emergency alerts (SMS, call, mobile app, dashboards)  
- Geo-tagged live location sharing during critical events  
- Voice, vibration, and multilingual alerts for accessibility  
- Energy-adaptive sensor sampling for improved battery efficiency  

---

## 🧠 AI & Software Architecture

- **Model:** Temporal Fusion Transformer (TFT)  
- **Learning:** Personalized, user-specific anomaly detection  
- **Explainability:** XAI for medical interpretability  
- **Backend:** Flask API deployed on Azure Cloud  
- **Alerts:** Twilio-based SMS and call system  
- **Dashboards:** Real-time monitoring for caregivers and doctors  

Alert Levels:
- Normal  
- Warning  
- Critical  

---

## 🛠️ Hardware Architecture

| Component | Description |
|--------|------------|
| MCU | Nordic nRF52840 (BLE 5.0, ultra-low power) |
| PPG Sensor | MAX86141 (HR, SpO₂, HRV) |
| ECG Front-End | AD8232 |
| IMU | LSM6DSOX (motion & posture tracking) |
| Battery | Li-Po 3.7V (300–500 mAh) |
| Charging | TP4056 with overcharge protection |
| PCB | FR-4 (2–4 layer), noise-isolated |
| Casing | 3D-printed PLA/ABS + silicone strap |

**Approximate unit cost:** ₹2,500 (scalable & affordable)

---

## 🔄 System Workflow

1. Wearable collects continuous biosignal data  
2. Data is processed locally and sent via BLE  
3. Cloud-based AI model predicts cardiac anomalies  
4. Explainable AI validates alert reasoning  
5. Emergency alerts and live location are shared instantly  

---

## 📈 Implementation Roadmap

- **Stage 1:** Prototype development (Completed)  
- **Stage 2:** Cloud & dashboard integration  
- **Stage 3:** Clinical validation and pilot trials  
- **Stage 4:** Rural and urban pilot deployment  
- **Stage 5:** Public health integration and analytics  

---

## 🌍 Social Impact

- Enables early cardiac intervention and saves critical minutes  
- Improves healthcare access for rural and elderly populations  
- Reduces emergency hospitalization costs  
- Supports ASHA workers and community health monitoring  
- Bridges healthcare inequity through affordable design  

---

## 💼 Business & Sustainability Model

- Hybrid **B2B2C** approach  
- Direct device sales + institutional partnerships  
- Subscription-based AI analytics and alert services  
- Insurance and telemedicine integrations  
- Privacy-preserving anonymized health data insights  

---

## 🔮 Future Scope

- Federated learning for on-device privacy-preserving AI  
- Integration with emergency services and smart ambulances  
- Nationwide decentralized tele-cardiac network  
- Public health dashboards for policymakers  

---

## 👥 Team

Built collaboratively by a multidisciplinary team focusing on:
- AI & Machine Learning  
- IoT & Embedded Systems  
- Cloud Infrastructure  
- Healthcare & Social Impact  

---

## 📜 License

This project is intended for academic, research, and social innovation purposes.
