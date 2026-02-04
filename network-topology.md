# ✅ Network Topology

Network Topology is the physical or logical layout of a network — basically how devices (servers, switches, routers, computers) are connected and communicate with each other.

---

## ➡️ Types of Network Topologies

## 1️⃣ Bus Topology

### 📌 How it works
- All devices connect to a single backbone cable.

### ✅ Pros
- Simple, easy to set up (small networks)
- Cheap

### ❌ Cons
- Backbone failure = whole network down
- Performance degrades as traffic increases

<img width="585" height="488" alt="image" src="https://github.com/user-attachments/assets/241d0090-7d40-4e7a-848c-7f05c1a4c493" />

---

## 2️⃣ Star Topology

### 📌 How it works
- All devices connect to a central switch/router.

### ✅ Pros
- Easy to manage (add/remove nodes)
- One node failure does not affect others
- Better performance due to dedicated links

### ❌ Cons
- Central device failure = network down

<img width="579" height="543" alt="image" src="https://github.com/user-attachments/assets/a41d2104-19f4-412f-a63e-09aeab866081" />

---

## 3️⃣ Ring Topology

### 📌 How it works
- Devices form a circle/closed loop
- Data flows in one direction (or both directions in dual-ring)

### ✅ Pros
- Simple, predictable data flow

### ❌ Cons
- One device failure = whole network down

<img width="555" height="516" alt="image" src="https://github.com/user-attachments/assets/195ed8e0-2560-4d16-9ded-f6d15b74127b" />

---

## 4️⃣ Mesh Topology

### 📌 How it works
- Every device connects to multiple other devices.

### ✅ Pros
- Extremely fault tolerant
- No single point of failure  
  (If one node goes down → traffic reroutes automatically)

### ❌ Cons
- Complex, hard to scale and manage
- Expensive

<img width="542" height="539" alt="image" src="https://github.com/user-attachments/assets/e684f8b1-672d-4369-88fa-eff2316d1567" />

---

## 5️⃣ Tree Topology

### 📌 How it works
- Combination of Bus + Star topology
- Parent-child hierarchy

### ✅ Pros
- Structured
- Scalable

### ❌ Cons
- Upper-level failure affects lower levels

<img width="549" height="506" alt="image" src="https://github.com/user-attachments/assets/17983a45-0815-48b4-b895-f539e0f7aba4" />

---

## 6️⃣ Hybrid Topology

### 📌 How it works
- Combination of multiple topologies

### ✅ Pros
- Flexible

### ❌ Cons
- Design complexity

<img width="528" height="506" alt="image" src="https://github.com/user-attachments/assets/855721ab-5097-4898-b6e3-256aaae04716" />

---

> 💡 **Good network topology leads to fewer outages, faster debugging, and better scalability.**
