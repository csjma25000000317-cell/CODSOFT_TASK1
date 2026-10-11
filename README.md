# Network Packet Analyzer

## Cyber Security Internship – Task 1

### Project Description
The Network Packet Analyzer is a Python application that captures network packets and displays important information about them.

### Features
- Captures network packets using Scapy.
- Displays source IP and destination IP addresses.
- Identifies TCP, UDP, and ICMP protocols.
- Shows packet size in bytes.
- Saves captured packet details to a CSV file.
- Generates a summary report of captured packets.

### Technologies Used
- Python
- Scapy
- CSV
- Npcap
- Visual Studio Code

### Requirements
- Python 3
- Scapy library
- Npcap on Windows

### How to Run
1. Install Python.
2. Install Scapy using `python -m pip install scapy`.
3. Install Npcap on Windows.
4. Open the project folder in VS Code.
5. Run `python packet_analyzer.py`.
6. Press `Ctrl+C` to stop packet capture and generate the summary report.

### Output Files
- `captured_packets.csv` – Stores packet details.
- `summary_report.txt` – Stores the packet summary.

### Disclaimer
Use this tool only on your own computer or networks where you have permission to capture traffic.
