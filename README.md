# Anomaly-Based Machine Learning Intrusion Detection System (IDS)

An intelligent Network Intrusion Detection System (NIDS) designed to identify, categorize, and alert on malicious network anomalies using Python, Scikit-learn, and TensorFlow.

## 🚀 Key Features
* **Traffic Capture**: Live raw packet analysis using Wireshark and `pyshark` processing layers.
* **Feature Engineering**: Tabular flow transformation containing timing metrics and byte counts.
* **ML Triage Engine**: Dual-layered inspection using Random Forest and Deep Neural Networks.

## 📊 Project Visuals & Artifacts
The live implementation metrics, traffic signatures, and test captures are detailed below:

### 1. Network Traffic Blueprint
![Network Capture Status](./Screenshot%202026-06-08%20093527.png)

### 2. Model Performance Evaluation
![Model Training Accuracy](./Screenshot%202026-06-08%20093807.png)

### 3. Intrusion Alert Dashboard
![Live Alert Feed](./Screenshot%202026-06-10%20133518.png)

## 🛠️ Tech Stack & Environment
* **OS Platforms**: Ubuntu LTS & Kali Linux Penetration Testing Environment
* **Analysis Software**: Wireshark Packet Analyzer (`wirecyber.pcapng` target sample included)
* **Core Libraries**: Python, Pandas, NumPy, Scikit-learn, TensorFlow, PyShark
