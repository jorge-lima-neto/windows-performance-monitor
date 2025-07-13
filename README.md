# 🖥️ Performance Monitor

**Performance Monitor** is a lightweight Windows **console application** developed in **C#**, designed to run silently in the background and monitor key system performance metrics. It provides a continuous and comprehensive view of your device’s health and usage over time.

---

## ⚙️ Features

- **Real-Time Data Collection**  
  Continuously monitors and collects usage data for:
  - **CPU**
  - **Memory (RAM)**
  - **Disk Storage**
  - **GPU**
  - **Network** (Download / Upload Speed)

- **Daily Metric Storage**  
  Performance data is temporarily stored in **JSON** format and aggregated into **daily summaries**. These are persistently saved in a **SQLite** database for historical tracking and performance trend analysis.

- **Background Execution**  
  Runs unobtrusively as a console application in the background, with minimal impact on system resources.

---

## 🛠️ Technologies Used

- **C#** – Core application logic and system metric access  
- **JSON** – Temporary storage format for raw metric data  
- **SQLite** – Embedded database for persistent historical data

---

## 🚀 Planned Features

- **API Integration for Remote Metric Upload**  
  Support for sending daily performance summaries to a remote REST API for centralized monitoring and cross-device analysis.

- **Machine Learning-Based Insights**  
  Implementation of ML models to analyze historical performance data and provide:
  - Anomaly detection (e.g., unusual CPU/GPU spikes)
  - Predictive alerts (e.g., anticipating storage or memory saturation)
  - Usage pattern recognition

---

> Ideal for developers, IT professionals, and power users seeking lightweight yet powerful system monitoring and data-driven insights without the overhead of a full graphical interface.
