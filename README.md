🚀 Real-Time DoS Attack Detection and Traffic Visualization System
📌 Overview

This project focuses on detecting Denial of Service (DoS) attacks such as SYN Flood and ICMP Flood by analyzing network traffic in real time. It monitors packet behavior, identifies abnormal traffic spikes, and visualizes attack patterns using graphical representations.

🎯 Objectives
- Detect abnormal network traffic patterns
- Identify SYN Flood and ICMP Flood attacks
- Analyze packet-level data in real time
- Visualize traffic spikes and attack trends
  
🛠️ Technologies Used
- Python
- Scapy (Packet Capture & Analysis)
- Matplotlib (Data Visualization)
- Pandas (Data Processing)
- Flask (Web Dashboard - Optional)
- Wireshark (Traffic Analysis Tool)
- 
⚙️ Features
- Real-time packet sniffing
- SYN Flood detection using TCP flags
- ICMP Flood detection
- Threshold-based anomaly detection
- Traffic visualization using graphs
- Logging of detected attacks
- 
🧠 How It Works
- Network packets are captured using Scapy
- Packets are analyzed for TCP and ICMP behavior
- Traffic is monitored against predefined thresholds
- Suspicious activity is flagged as a potential attack
- Results are stored and visualized using graphs
  
📊 Output
- Console alerts for detected attacks
- Logged attack data in CSV file
- Graphical representation of traffic spikes

⚠️ Disclaimer

This project is developed for educational purposes only. Do not use it on unauthorized networks.
