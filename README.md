# 🧠 Advanced Networking Concepts

## 📍 Overview
Advanced networking concepts are the foundation of how data moves securely and efficiently across the internet.  
This document covers three major areas:

1. **TCP/IP Protocol Suite**
2. **Binary System**
3. **Basics of Cryptography**

---

## 1️⃣ TCP/IP Protocol Suite

### 🔹 What is TCP/IP?
**TCP/IP (Transmission Control Protocol / Internet Protocol)** is the **core communication model** of the internet.  
It defines how data is transmitted, routed, and delivered reliably between devices.

---

### 🔹 TCP/IP Layers

| Layer | Description | Example Protocols |
|--------|--------------|-------------------|
| **Network Interface Layer** | Physically transmits data over the network (hardware and drivers). | Ethernet, ARP, PPP |
| **Internet Layer** | Handles addressing and routing of packets. | IP (IPv4/IPv6), ICMP |
| **Transport Layer** | Ensures reliable or fast delivery between devices. | TCP, UDP |
| **Application Layer** | Provides services to end-users and apps. | HTTP, DNS, FTP, SMTP, SSH |

---

### 🔹 Key Protocols Explained

#### ✅ **IP (Internet Protocol)**
- Responsible for **addressing** and **routing**.
- Each device has a unique **IP address**.
- Doesn’t guarantee delivery (best-effort protocol).

#### ✅ **TCP (Transmission Control Protocol)**
- Provides **reliable**, **ordered**, and **error-checked** delivery.
- Uses a **three-way handshake** (SYN → SYN-ACK → ACK).
- Used by: **HTTP**, **SMTP**, **FTP**.

#### ✅ **UDP (User Datagram Protocol)**
- **Faster** but **unreliable** (no handshake).
- Used in: **Streaming**, **Gaming**, **VoIP**.

#### ✅ **ICMP (Internet Control Message Protocol)**
- Used for diagnostics, e.g., the **ping** command.

---

### 🔹 Encapsulation Process

Data flow through TCP/IP involves **encapsulation** — each layer adds its header before transmission.
