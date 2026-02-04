# ✅ OSI (Open System Interconnection) Model

The OSI Model is a conceptual 7-layered framework that explains how data travels from one system to another over a network.

<img width="566" height="374" alt="image" src="https://github.com/user-attachments/assets/20c8ca41-c691-441c-ba78-22e9cf3f9c75" />


---

## 1️⃣ Application Layer (L7)

- User interacts with this layer (browser, email, WhatsApp, etc.)
- **Important Protocols:**
  - HTTP
  - HTTPS
  - FTP
  - SMTP
  - SSH

---

## 2️⃣ Presentation Layer (L6)

- Data formatting and compression happen here
- Encryption and decryption (SSL/TLS)

---

## 3️⃣ Session Layer (L5)

- Establishes, maintains, and terminates communication sessions

---

## 4️⃣ Transport Layer (L4)

- Breaks data into segments
- Ensures correct delivery using:
  - Ports
  - Flow control
  - Retransmission
- **Important Protocols:**
  - TCP (reliable but slower)
  - UDP (faster, no delivery guarantee)

---

## 5️⃣ Network Layer (L3)

- Responsible for routing and IP addressing
- Finds best path to destination using routers
- **Important Protocols:**
  - IP
  - ICMP

---

## 6️⃣ Data Link Layer (L2)

- Node-to-node data delivery
- Uses:
  - MAC addresses
  - Switches
  - Ethernet
  - ARP

---

## 7️⃣ Physical Layer (L1)

- Transfers raw bits (0s and 1s) physically
- Uses:
  - Cables
  - Fiber optics
  - Wireless signals

---

> 💡 **Data Flow:**  
> Sender → Layer 7 down to Layer 1  
> Receiver → Layer 1 up to Layer 7
