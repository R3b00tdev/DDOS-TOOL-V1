# DDOS-TOOL-V1<img width="1109" height="582" alt="Screenshot 2025-10-05 134653" src="https://github.com/user-attachments/assets/485e4728-c016-463c-a11f-56e92883a683" />
\# DDOS-TOOL — Simulated Network Load Testing Tool (Free Version)



DDOS-TOOL is a \*\*simulated network load testing tool (command-line)\*\* created by R3b00t for educational and research purposes. It is designed to \*\*model high volumes of HTTP-based traffic in isolated lab environments only\*\*. The project supports multiple simulation modes, optional proxy configuration for controlled lab topologies, and real-time logging to monitor simulated activity effectively. 🖥️



---



\### 🧩 Features

\- 🔗 Target any HTTP/HTTPS URL (authorized lab targets only)   

\- 🔁 Custom request counts (e.g. 10, 100, 1000)  

\- 🖥️ Command-line interface (no GUI) with clear progress reporting  

\- 📊 Real-time logging, statistics and progress tracking  



---



\### 🧰 Requirements

The minimal dependencies are listed in `requirements.txt`:

\- aiohttp>=3.8.0  

\- aiohttp-socks>=0.7.0  

\- aiodns>=3.0.0  

\- cchardet>=2.1.7



Install dependencies via pip:

```bash

pip install -r requirements.txt



