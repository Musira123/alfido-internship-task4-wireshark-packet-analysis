# 🧪 Task 4 - Packet Analysis with Wireshark (Alfido Tech Cybersecurity Internship)

## 👩‍💻 Intern: Masira Taj  
**Internship Program**: Alfido Tech - Cybersecurity Internship  
**Task Number**: 4  
**Task Name**: Packet Analysis using Wireshark  
**Platform**: Linux (Kali)

---

## 📌 Task Objective

To analyze network packets in real time using **Wireshark** and detect protocols like **DNS** and **HTTP**. The objective was to capture live traffic, apply filters, and analyze packet structures — a key skill in network security and threat hunting.

---

## 🛠️ Tools Used

- 🐧 **Kali Linux**
- 📡 **Wireshark** (Network Protocol Analyzer)
- 🌐 Browser to generate HTTP/DNS traffic

---

## 🧭 Task Steps

### 1. Launching Wireshark
Opened Wireshark and viewed all available network interfaces.

📸 Screenshot:  
`01-wireshark-interface-selection.png`

---

### 2. Capturing Packets on eth0
Selected the **eth0** interface and began live packet capture.

📸 Screenshot:  
`02-started-capturing-on-eth0.png`

---

### 3. Filtering HTTP Packets
Used the filter `http` to isolate HTTP traffic and inspect requests/responses.

📸 Screenshot:  
`03-http-filter-applied.png`

---

### 4. Filtering DNS Packets
Used the filter `dns` to observe domain name resolution queries and replies.

📸 Screenshot:  
`04-dns-filter-applied.png`

---

### 5. Packet Capture File
The complete `.pcapng` file from the scan is included for reference:

📂 File: `task4_capture.pcapng`

You can open this file in Wireshark to review the actual captured data, filters, and packet structures.

---

## 🔍 Observations

- **HTTP Traffic**: GET and POST requests to visited websites were visible.
- **DNS Queries**: Revealed domain resolution requests to external DNS servers.
- **Security Insight**: These filters are critical for identifying abnormal traffic patterns, phishing attempts, or malware communication.

---

## ✅ Task Outcome

✔️ Successfully completed live packet capture  
✔️ Applied protocol filters (HTTP, DNS)  
✔️ Analyzed captured traffic  
✔️ Shared `.pcapng` file for evidence  
✔️ Gained hands-on experi
