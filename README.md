# 🛡️ VPN Setup, Encryption, and Privacy Analysis

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)]()

---

## 📝 Overview

This repository documents a practical cybersecurity lab exercise focused on understanding, configuring, and testing a **Virtual Private Network (VPN)**.  
The goal of this task was to analyze VPN functionality, verify encryption, and compare performance before and after VPN usage.

---

## 🌐 Environment Details

- **VPN Used:** ProtonVPN 
- **Browser:** Google Chrome   
- **Operating System:** Windows 10  
- **VPN Server Location:** Singapore  
- **Testing Tool:** [WhatIsMyIPAddress.com](https://whatismyipaddress.com)  

---

## 🧪 Lab Exercise: Methodology & Phases

### **Phase 1 – Selection and Account Setup**
- Chose **ProtonVPN** for its reliability, transparency, and no-log policy.  
- Signed up for the free plan using an official Proton account.  
- Verified email and logged into the ProtonVPN dashboard.

---

### **Phase 2 – Download and Installation**
- Downloaded ProtonVPN from the official website: [https://protonvpn.com/download](https://protonvpn.com/download).  
- Installed the client on Windows 10 and logged in with credentials.  
- Verified installation by checking the client dashboard for available servers.

---

### **Phase 3 – Connection Setup**
- Connected to a **Singapore-based server** for optimal performance.  
- The VPN tunnel established successfully, showing a secure and encrypted status.  
- Verified that the VPN client was actively encrypting traffic.

---

### **Phase 4 – IP Verification**
- Checked IP before connection – displayed **original ISP-based location (India)**.  
- Connected VPN and rechecked IP using *WhatIsMyIPAddress.com* – location changed to **Singapore**.  
- Confirmed that the VPN successfully masked the real IP address.

---

### **Phase 5 – Encrypted Browsing Test**
- Accessed websites such as GitHub, Wikipedia, and Google while connected.  
- Verified HTTPS connections and VPN encryption indicator.  
- Browsing remained stable, and no DNS leaks were detected.

---

### **Phase 6 – Disconnect and Performance Comparison**

After verifying the VPN connection and testing encrypted browsing, the VPN was disconnected to observe differences in speed and performance.

| Metric | Without VPN | With VPN (Singapore Server) | Observation |
|---------|--------------|-----------------------------|-------------|
| **IP Address** | India | Singapore | Masked successfully |
| **Download Speed** | 52 Mbps | 35 Mbps | Moderate drop |
| **Upload Speed** | 18 Mbps | 12 Mbps | Slight reduction |
| **Latency (Ping)** | 23 ms | 87 ms | Noticeable delay |
| **Browsing** | Smooth | Slight lag | Acceptable difference |

**Interpretation:**  
VPN encryption slightly reduced speed due to data routing and overhead, but stability remained consistent. The IP change and encryption confirmed privacy protection.

---

### **Phase 7 – Research on VPN Encryption and Privacy Features**

**1. Encryption Standards:**  
- AES-256-bit encryption ensures unbreakable data confidentiality.  
- Uses **RSA-4096** for key exchange and **HMAC SHA-512** for message integrity.

**2. VPN Protocols Supported:**  

| Protocol | Description | Security | Use Case |
|-----------|-------------|-----------|-----------|
| **OpenVPN** | Open-source, strong encryption | High | Desktop usage |
| **IKEv2/IPSec** | Fast and mobile-friendly | High | Mobile networks |
| **WireGuard** | Lightweight and efficient | High | Low-latency connections |

**3. Privacy & Security Features:**  
- No-Logs Policy  
- Kill Switch Protection  
- DNS Leak Prevention  
- Secure Core Multi-hop Routing  
- Perfect Forward Secrecy  

**Interpretation:**  
ProtonVPN offers transparent, open-source protocols and robust encryption. Privacy features prevent leaks and ensure high trustworthiness.

---

### **Phase 8 – Summary of Findings and Performance Evaluation**

**1. Observations:**  

| Metric | Without VPN | With VPN | Impact |
|---------|--------------|----------|--------|
| **IP Address** | India | Singapore | Hidden successfully |
| **Speed** | 52 Mbps | 35 Mbps | 32% decrease |
| **Latency** | 23 ms | 87 ms | Increased |
| **Encryption** | None | AES-256 Enabled | Fully secure |

**2. Security Findings:**  
- VPN successfully masked IP and encrypted all data traffic.  
- No DNS or IP leaks observed.  
- HTTPS + VPN combined ensured full confidentiality.

**3. Performance Findings:**  
- Minor performance drop due to server distance and encryption overhead.  
- Stable connection and reliable server uptime.  

**4. Conclusion:**  
The VPN successfully demonstrated its ability to secure internet communication and preserve privacy.  
Despite minor speed reduction, VPN encryption significantly enhances data protection, anonymity, and browsing safety.

---

## ✅ Key Takeaways

- VPNs encrypt all internet traffic, protecting data from interception.  
- Free VPNs may have server limitations but still provide basic privacy.  
- Always use VPNs from **trusted and verified providers**.  
- Choose nearby servers to reduce latency and speed loss.  
- Regularly check for DNS or IP leaks to maintain privacy integrity.

---

## ⚠️ Ethical & Legal Note

All VPN configurations and tests were performed for **educational and awareness purposes** only.  
No unauthorized access, network intrusion, or data tampering was carried out during this exercise.

---

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).
