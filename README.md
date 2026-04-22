📊 IoT Sensor Excel Data Logging

A simple IoT project that collects sensor data and logs it into an Excel-compatible format (CSV) for easy analysis and visualization.

🚀 Overview

This project demonstrates how to build a basic IoT data logging pipeline:

Sensor → Data Collection → File Logging → Excel Analysis

Instead of using a database, sensor readings are stored in a CSV file, making it easy to open and analyze the data in tools like Microsoft Excel or Google Sheets.

Features
- 📡 Collects real-time sensor data
- 📝 Logs data into a structured CSV file
- 📊 Compatible with Excel for visualization and analysis

🛠️ Tech Stack
- Language: Python, C++
- Data Format: CSV (Excel-readable)
- Sensor: DHT11 sensor
- Environment: Arduino Uno / Raspberry Pi 

⚙️ How It Works
- The script reads data from a sensor (or simulated input)
- Data is formatted into rows (e.g., timestamp + sensor value)
- Each reading is appended to a CSV file
The CSV file can be opened in Excel for analysis

▶️ Getting Started

1. Clone the repository
git clone `https://github.com/georgeodev/IoT-Sensor-Excel-data-logging.git`
cd IoT-Sensor-Excel-data-logging
2. Install dependencies (if needed)
pip install -r requirements.txt
3. Run the script
`python main.py`

