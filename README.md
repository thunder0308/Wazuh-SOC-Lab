# Wazuh-SOC-Lab
Welcome to my Wazuh SOC Lab repository! This project documents my journey of deploying, configuring, and implementing different security tools.
# 📝 Overview
This project demonstrates the end-to-end deployment and configuration of different security tools using the open-source Wazuh SIEM/XDR platform.
# 🏗️ Lab Architecture
The Lab includes the following components:
| Category | Technology |
| :--- | :--- | 
| **Hardware** | Dell Latitude E5440 | 
| **OS** | Debian 13 (Headless) | 
| **Security** | UFW, OpenSSH | 
| **Containerization** | Docker | 
| **DNS Defense** | Pi-hole | 
| **Wazuh Server** | Runs the central Wazuh Manager, Indexer, and Dashboard. Collects and correlates logs from agents, Suricata, and UFW. |
| **Endpoint (Macbook Air)** | Runs the Wazuh Agent for system monitoring and log forwarding. |
| **UFW Firewall** | Provides firewall logs. Integrated into Wazuh for anomaly detection. |
| **Suricata IDS/IPS** | Monitors network traffic, Sends IDS alerts to Wazuh. |
