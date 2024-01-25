# APIAnomalyDetector

Not Freely Licensed For Commercial Use! Contact me to use commercially. 

This repository contains code for a tool that detects anomalies in API payload sizes.

 Key Features:

Monitors API payload sizes: Tracks the payload size of responses from specified API endpoints.
Detects significant differences: Alerts when payload sizes deviate significantly from historical averages.
Visualizes trends: Displays a graph of average payload sizes over time for each endpoint.
 Structure:

api_anomaly_detector.py: Main Python script containing the anomaly detection logic.
payload-sizes.csv: Stores historical payload size data.
requirements.txt: Lists required Python libraries.
 Instructions:

Install required libraries: pip install -r requirements.txt
Run the script: python api_anomaly_detector.py
Access the Dash app at http://127.0.0.1:8050/ to view the payload size graph.
 Customization:

Modify the API_ENDPOINTS list to specify the API endpoints to monitor.
Adjust the THRESHOLD_SIZE_DIFFERENCE to control the sensitivity of anomaly detection.
 Potential Uses:

Identifying API performance issues: Detect unexpected changes in payload sizes that could indicate performance problems.
Detecting data quality issues: Flag anomalies that might suggest data corruption or inconsistencies.
Monitoring API usage patterns: Track payload size trends to understand how APIs are being used.
 Contributing:

 We welcome contributions! Please feel free to submit issues or pull requests.
