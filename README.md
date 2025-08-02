# 📡 IoT Sensor Data Collection using MQTT in Python
This project demonstrates how to implement a simple IoT data collection system using the MQTT protocol and Python. It simulates sensor data (temperature and humidity), publishes it to an MQTT broker, and receives it using a subscriber.

# 🔧 Features
Simulated sensor data (temperature + humidity)
Real-time MQTT communication using paho-mqtt
Publishes to a public broker (broker.hivemq.com)
Separate scripts for publisher and subscriber
Optional socket test to verify broker connectivity

# 📁 Project Structure
.
├── sensor_publisher.py       # Publishes random sensor data
├── sensor_subscriber.py      # Receives and displays sensor data
├── mqtt_broker_check.py      # Checks if the broker is reachable
└── README.md                 # Project documentation

# ⚙️ Requirements
Python 3.x
paho-mqtt library

# Install dependencies:
pip install paho-mqtt

# 🚀 How to Run
1. Start the subscriber first:
python sensor_subscriber.py

2. Then run the publisher:
python sensor_publisher.py

You should see sensor data published by the publisher and received in real-time by the subscriber.

# 🌐 MQTT Details
Broker: broker.hivemq.com (public test broker)
Port: 1883
Topic: aiot/lab1/sensordata

# 📚 Learning Goals
Understand how MQTT works in IoT systems
Practice Python networking using paho-mqtt
Simulate and test publish-subscribe communication
