# Network Traffic Analysis & Threat Visualization using Python and Wireshark

## 🔐 Project Overview
This project analyzes real network traffic captured using Wireshark and performs
security-focused analysis using Python. The goal is to identify external connections,
understand geographic distribution of traffic, and present insights through an
interactive security dashboard and world map.

---

## 🧠 Key Objectives
- Extract external/public IP addresses from captured network traffic
- Perform IP geolocation to identify countries, cities, and cloud providers
- Detect traffic concentration from cloud/CDN providers
- Visualize global network connections on an interactive map
- Generate security metrics useful for SOC and threat analysis

---

## 🛠️ Tools & Technologies
- Wireshark / TShark (packet capture & parsing)
- Python (PyShark, Pandas, Requests, Folium)
- Jupyter Notebook
- IP Geolocation API (ip-api.com)

---

## 🔍 Security Analysis Performed
- Public vs Private IP identification
- Country-wise traffic analysis
- Cloud/CDN traffic percentage estimation
- Identification of high-frequency external endpoints
- Interactive map-based threat visualization

---

## 📊 Output
- Interactive world map showing external network connections
- Security summary dashboard with:
  - Total external IPs
  - Countries reached
  - Top destination country
  - Cloud traffic percentage
## 🔒 Data Privacy
PCAP files are excluded from this repository due to privacy and security reasons.
This follows standard cybersecurity best practices.
