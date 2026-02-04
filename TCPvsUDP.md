# 🌐 TCP vs UDP – Networking Basics for DevOps

This file contains beginner-friendly notes on **TCP (Transmission Control Protocol)** and **UDP (User Datagram Protocol)** — two core transport layer protocols used in networking.

Understanding these is essential for DevOps, Cloud, and System Engineering.

---

## ✅ TCP (Transmission Control Protocol)

TCP is a **reliable, connection-oriented protocol** that ensures data is delivered correctly and in order.

### 🔹 Key Features:
- Reliable data transmission
- Maintains packet order
- Slower than UDP due to:
  - Connection setup
  - Acknowledgements
  - Retransmissions

### 📌 TCP Connection Setup (3-Way Handshake)

<img width="681" height="310" alt="image" src="https://github.com/user-attachments/assets/db0e73d4-a38c-4f07-b540-0e58e1878f0b" />


*(Client and server confirm readiness before data transfer)*

### 📊 Common Use Cases:
- Websites (HTTP/HTTPS)
- SSH connections
- Databases

---

## ✅ UDP (User Datagram Protocol)

UDP is a **fast, connectionless protocol** that sends data without guaranteeing delivery or order.

### 🔹 Key Features:
- No connection setup
- Faster than TCP
- No retransmission
- No guaranteed order or delivery

### 📊 Common Use Cases:
- Video streaming
- Online gaming
- Live video/audio calls (Zoom, VoIP)

---

## ⚖️ TCP vs UDP – Comparison Table

| Feature | TCP | UDP |
|--------|-----|-----|
| Connection Setup | Required (3-Way Handshake) | Not required |
| Reliability | High | Low |
| Speed | Slower | Faster |
| Packet Order | Maintained | Not guaranteed |
| Retransmission | Yes | No |
| Use Case | Critical data (logins, payments, databases) | Real-time data (streaming, gaming, calls) |


