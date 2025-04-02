This dataset was developed as part of the research and demonstration project presented in the book:
"AI-Powered Cybersecurity for Industrial IoT and Wireless Sensor Networks."

🔐 Objective
To simulate and analyze cyber threats in Industrial Internet of Things (IIoT) and Wireless Sensor Networks (WSN) environments using machine learning. The dataset enables hands-on demonstration of the data science lifecycle, including:

Exploratory Data Analysis (EDA)

Feature Engineering

Machine Learning Model Development

Real-Time Deployment and Visualization

📁 Dataset Files
File Name	Description
IIoT-WSN_CyberThreats.csv	Raw dataset including both normal and malicious activity samples.
IIoT-WSN_CyberThreats_preprocessed.csv	Cleaned and feature-engineered version of the dataset, ready for ML modeling.
IIoT-WSN_Train.csv	Training set used for model training.
IIoT-WSN_Test.csv	Testing set used for model evaluation.
🧾 Dataset Features
Feature	Description
Device_Type	Type of IoT/IIoT device (e.g., Sensor, Gateway).
Protocol	Communication protocol used (e.g., MQTT, Modbus).
Packet_Size	Size of the network packet in bytes.
Request_Type	Type of request (e.g., Read, Write).
Payload_Entropy	Measure of randomness in payload (used to detect anomalies).
CPU_Usage (%)	CPU usage of the device at the time of data capture.
Memory_Usage (%)	Memory utilization of the device.
Temperature (°C)	Internal device temperature reading.
Battery_Level (%)	Battery power remaining.
Timestamp	Time of event capture. (Dropped during preprocessing and split into components)
Year, Month, Day, Hour, Minute, Second	Time components extracted from the original timestamp.
Malicious_Activity	Binary target label: 1 for malicious activity, 0 for normal operation.
📌 Use Cases
This dataset is ideal for:

Teaching and training on cybersecurity ML pipelines

Research on anomaly detection and intrusion detection

Deployment of real-time cybersecurity dashboards

Prototyping AI security tools for smart industries, smart cities, and critical infrastructure

📎 Citation
If you use this dataset, please cite the book:
"AI-Powered Cybersecurity for Industrial IoT and Wireless Sensor Networks" by [Author Name] (Year).
📘 To be released / under publication.
