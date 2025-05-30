# IIoT-WSN Cyber Threat Dataset

This dataset was developed as part of the research and demonstration project presented in the upcoming book:  
📘 **"AI-Powered Cybersecurity for Industrial IoT and Wireless Sensor Networks"**

---

## 🔐 Objective

To simulate and analyze cyber threats in Industrial Internet of Things (IIoT) and Wireless Sensor Networks (WSN) environments using machine learning.

This dataset enables hands-on demonstration of the entire data science lifecycle, including:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Development
- Real-Time Deployment and Visualization

---

## 📁 Dataset Files

| File Name                          | Description                                                  |
|-----------------------------------|--------------------------------------------------------------|
| `IIoT-WSN_CyberThreats.csv`       | Raw dataset including both normal and malicious activity     |
| `IIoT-WSN_CyberThreats_preprocessed.csv` | Cleaned and feature-engineered dataset ready for ML tasks |
| `IIoT-WSN_Train.csv`              | Training set for model training                              |
| `IIoT-WSN_Test.csv`               | Testing set for model evaluation                             |

---

## 🧾 Dataset Features

| Feature              | Description |
|----------------------|-------------|
| `Device_Type`        | Type of IoT/IIoT device (e.g., Sensor, Gateway) |
| `Protocol`           | Communication protocol used (e.g., MQTT, Modbus) |
| `Packet_Size`        | Size of the network packet in bytes |
| `Request_Type`       | Type of request (e.g., Read, Write) |
| `Payload_Entropy`    | Measure of randomness in payload (used to detect anomalies) |
| `CPU_Usage (%)`      | CPU usage of the device at time of capture |
| `Memory_Usage (%)`   | Memory utilization of the device |
| `Temperature (°C)`   | Internal temperature reading |
| `Battery_Level (%)`  | Battery power remaining |
| `Timestamp`          | Original timestamp (later split into components) |
| `Year, Month, Day, Hour, Minute, Second` | Time components derived from `Timestamp` |
| `Malicious_Activity` | Binary target label: `1` = attack, `0` = normal |

---

## 📌 Use Cases

This dataset is ideal for:
- 📚 Teaching and training on cybersecurity ML pipelines
- 🧪 Research on anomaly and intrusion detection in IIoT/WSN
- 🖥️ Real-time threat detection dashboards
- 🏭 AI security tools for smart industries, cities, and infrastructure

---

## 📎 Citation

If you use this dataset, please cite the book:  
**"AI-Powered Cybersecurity for Industrial IoT and Wireless Sensor Networks"**  
by *Atdhe Buja* (To be released / under publication)

---

## 📬 Contact

For questions or collaboration opportunities, please contact [Atdhe Buja](https://github.com/atdhebuja) via GitHub.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
