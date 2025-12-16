
-  Task 5 – Wireshark Network Traffic Capture (Windows)

## 📌 Overview
This project demonstrates how to capture and analyze live network traffic on a Windows system using **Wireshark**.  
The main goals are to capture packets, identify multiple network protocols (DNS, TCP, HTTP, etc.), and summarize the observations. [file:1]

---

## 🎯 Objective
- Capture live network packets on Windows using Wireshark.  
- Identify at least **three different protocols** from the captured traffic.  
- Save the capture as a `.pcap` file and write a short analysis report. [file:1]

---

## 🛠 Tools & Environment
- **Operating System:** Windows 10 / 11  
- **Tool:** Wireshark (with Npcap) – free, open‑source packet analyzer [file:1]

---

## 🚀 Setup & Installation
1. Download Wireshark for Windows from the official website.  
2. Run the installer and keep default options.  
3. When asked, **install Npcap** (required for live capture).  
4. Launch Wireshark from the Start Menu after installation completes. [file:1]

---

## 📡 Packet Capture Workflow

### 1. Start Capturing
1. Open Wireshark – the **Capture** interfaces list is shown.  
2. Select the active interface (Wi‑Fi/Ethernet) with visible traffic graph.  
3. Double‑click the interface or click the blue **Start Capturing** (shark‑fin) button. [file:1]

### 2. Generate Network Traffic
While Wireshark is capturing:
- Open a browser and visit multiple websites.  
- Optionally run `ping` commands (e.g., `ping google.com`) in Command Prompt.  
Let this run for about **60 seconds**. [file:1]

### 3. Stop & Save Capture
1. Click the **red Stop** button in the toolbar.  
2. Go to **File → Save As…**.  
3. Save the file as `task5.pcap` inside this project folder. [file:1]

---

## 🔍 Protocol Analysis

### Using Display Filters
In the filter bar, apply filters to focus on protocols:

For each protocol:
- Inspect **Source IP**, **Destination IP**, and **ports**.  
- For DNS: note queried domain names.  
- For HTTP: note HTTP method and host (if present).  
- For TCP: observe connection setup and packet sequence. [file:1]

### Identified Protocols (Example)
- **DNS** – name resolution requests from the host to DNS servers.  
- **TCP** – reliable transport for web and other application traffic.  
- **HTTP/HTTPS** – web browsing traffic generated while visiting sites. [file:1]

---

## 📄 Report Summary (What I Documented)
The report (`report.md`) includes:
- List of protocols identified in the capture.  
- 1–2 sample packets per protocol with IPs, ports, and key fields.  
- Short explanation of how packet capture helps in troubleshooting networks. [file:1]

---

---

## ✅ Learning Outcomes
- Installed and configured Wireshark on Windows.  
- Performed live packet capture and saved results as `.pcap`.  
- Used filters to analyze DNS, TCP, HTTP and understood their roles in network communication. [file:1]
