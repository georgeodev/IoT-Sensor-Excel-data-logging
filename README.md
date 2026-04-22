📊 IoT Sensor Excel Data Logging

A simple IoT project that collects sensor data and logs it into an Excel-compatible format (CSV) for easy analysis and visualization.

🚀 Overview

This project demonstrates how to build a basic IoT data logging pipeline:

Sensor → Data Collection → File Logging → Excel Analysis

Instead of using a database, sensor readings are stored in a CSV file, making it easy to open and analyze the data in tools like Microsoft Excel or Google Sheets.

🧠 Features
📡 Collects real-time sensor data
📝 Logs data into a structured CSV file
📊 Compatible with Excel for visualization and analysis
⚡ Lightweight and beginner-friendly
🔁 Supports continuous or periodic data logging
🛠️ Tech Stack
Language: Python, C++
Data Format: CSV (Excel-readable)
Environment: Local machine / Raspberry Pi / IoT device
📂 Project Structure
IoT-Sensor-Excel-data-logging/
│
├── main.py              # Main script to collect and log sensor data
├── data.csv             # Output file (generated)
├── requirements.txt     # Dependencies (if applicable)
└── README.md            # Project documentation
⚙️ How It Works
The script reads data from a sensor (or simulated input)
Data is formatted into rows (e.g., timestamp + sensor value)
Each reading is appended to a CSV file
The CSV file can be opened in Excel for analysis
▶️ Getting Started
1. Clone the repository
git clone `https://github.com/georgeodev/IoT-Sensor-Excel-data-logging.git`
cd IoT-Sensor-Excel-data-logging
2. Install dependencies (if needed)
pip install -r requirements.txt
3. Run the script
python `main.py`
📈 Example Output
Timestamp	Sensor Value
2026-04-22 10:00	23.5
2026-04-22 10:05	24.1
💡 Use Cases
Learning IoT fundamentals
Logging environmental data (temperature, humidity, etc.)
Creating Excel dashboards and charts
Simple monitoring systems without a database
