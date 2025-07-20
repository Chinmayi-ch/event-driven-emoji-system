# 🚀 Event-Driven Emoji Broadcast System

![GitHub top language](https://img.shields.io/github/languages/top/Chinmayi-ch/event-driven-emoji-system?color=blue)
![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)

A **highly scalable real-time emoji reaction system** built using Apache Kafka, Spark Streaming, and Flask. Designed to process and broadcast emoji interactions with minimal latency using a clean **event-driven architecture**.

---

## ✨ Features

✅ Real-time emoji reaction broadcasting  
✅ Kafka-based event messaging and queuing  
✅ Spark Streaming for real-time sentiment analytics  
✅ Flask API for frontend-backend integration  
✅ Scalable to handle thousands of concurrent users  

---

## 🛠️ Tech Stack

| Layer        | Tech Used                       |
|-------------|----------------------------------|
| Messaging   | ⚡ Apache Kafka                  |
| Processing  | 🔥 Apache Spark Streaming        |
| Backend     | 🐍 Flask (Python)                |
| Frontend    | 🌐 HTML/CSS/JavaScript           |
| Others      | 🧰 REST APIs, JSON, Git           |

---

## 📁 Project Structure
event-driven-emoji-system/
│
├── kafka/ # Kafka producer & consumer scripts
├── spark/ # Spark streaming job for real-time processing
├── backend/ # Flask server and API endpoints
├── frontend/ # Simple UI to send emoji reactions
├── requirements.txt # Dependencies (Python)
└── README.md


---

## 🧪 How It Works

1. **Users** react with emojis on the frontend  
2. **Flask API** receives reactions and produces Kafka events  
3. **Kafka** streams the events to Spark  
4. **Spark Streaming** processes and aggregates reactions live  
5. **Results** are broadcasted back for live frontend updates  

📌 All in near real-time — ideal for live events, dashboards, and streaming platforms!

---

## ⚙️ Getting Started

### 1️⃣ Prerequisites
- Python 3.8+
- Apache Kafka & Zookeeper
- Apache Spark
- Flask:  
  ```bash
  pip install flask

2️⃣ Basic Setup
bash
Copy
Edit
# Start Kafka & Zookeeper
zookeeper-server-start.sh config/zookeeper.properties
kafka-server-start.sh config/server.properties

# Start Flask server
cd backend
python app.py

# Run Spark streaming job
spark-submit spark/emoji_stream_processor.py

# Open frontend in browser
Note: Setup steps will vary depending on your environment. Consider using Docker for a full-stack local deployment.

🧠 Use Cases
🎥 Live-stream audience interaction

🧪 Real-time feedback systems

📊 Emoji-based sentiment dashboards

🧠 Big data event-streaming demonstrations

## 🤝 Credits  
> 🛠️ *This project was originally developed as part of a team effort during an academic course on Cloud Computing & Big Data. This version is a personal restructured copy, maintained and enhanced by Chinmayi C H for portfolio purposes.*

## 👩‍💻 Author  
> [Chinmayi C H](https://github.com/Chinmayi-ch)  
> 📧 chinmayich271@gmail.com

