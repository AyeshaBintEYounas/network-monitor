# 🌐 Network Traffic Monitoring and Analysis Platform

A web-based network traffic monitoring platform built with **Python (Flask)** and **HTML/CSS/JavaScript**.  
Developed as a Computer Networks undergraduate project.

---

## 👩‍💻 Student Information

| Field | Details |
|-------|---------|
| **Name** | Ayesha Bint E Younas |
| **Roll No** | BCSF24M032 |
| **Course** | Computer Networks |
| **Project** | Network Traffic Monitoring and Analysis Platform |

---

## 📋 Project Description

This platform simulates network traffic monitoring by capturing, displaying, and analyzing network packet data in real time through a clean web interface. It demonstrates core networking concepts including IP addressing, protocol identification, port-to-service mapping, and traffic statistics.

---

## ✨ Features

- ▶️ Start / Stop monitoring session
- 📦 Real-time packet capture and display
- 🔍 Filter by Protocol (TCP / UDP / ICMP), Source IP, Destination IP
- 🗂️ Port-to-service mapping (Port 80 = HTTP, Port 53 = DNS, etc.)
- 📊 Live statistics — total packets, protocol breakdown, average size
- 📝 System event log with timestamps

---

## 🗃️ Project Structure

```
network_monitor/
├── app.py                  # Flask backend (main server)
├── requirements.txt        # Python dependencies
├── dataset.csv             # Sample network traffic dataset
└── templates/
    └── index.html          # Web interface
```

---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.10+ | Backend logic |
| Flask | Web server and REST APIs |
| HTML5 | Interface structure |
| CSS3 | Styling and layout |
| JavaScript (ES6) | Frontend interactivity |

---

## 🚀 How to Run

**Step 1 — Install Python** from [python.org](https://python.org)

**Step 2 — Install Flask**
```bash
pip install flask
```

**Step 3 — Run the server**
```bash
python app.py
```

**Step 4 — Open in browser**
```
http://127.0.0.1:5000
```

> ⚠️ Keep the terminal open while using the app.

---

## 🖥️ How to Use

1. Open the app in your browser
2. Click **Start** to begin monitoring
3. View live packets in the table
4. Use filters to search by Protocol or IP address
5. Click **Stop** to end the session

---

## 📁 Dataset Fields

| Field | Example |
|-------|---------|
| Time | 10:35:21 |
| Source IP | 192.168.1.10 |
| Destination IP | 8.8.8.8 |
| Protocol | TCP |
| Source Port | 52341 |
| Destination Port | 80 |
| Service | HTTP |
| Packet Size | 512 bytes |

---

## 📌 Port to Service Mapping

| Port | Service |
|------|---------|
| 22 | SSH |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 3306 | MySQL |
| 3389 | RDP |
| 8080 | HTTP-Alt |

---

*Computer Networks Project — Undergraduate Level*
