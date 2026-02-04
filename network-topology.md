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

<img width="491" height="390" alt="image" src="https://github.com/user-attachments/assets/40b3888a-7b40-4ef8-8d02-e980fdbe1b3b" />


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

<img width="466" height="410" alt="image" src="https://github.com/user-attachments/assets/02e712aa-09db-4a12-8c76-64c8b14bfb45" />


---

## 3️⃣ Ring Topology

### 📌 How it works
- Devices form a circle/closed loop
- Data flows in one direction (or both directions in dual-ring)

### ✅ Pros
- Simple, predictable data flow

### ❌ Cons
- One device failure = whole network down

<img width="461" height="438" alt="image" src="https://github.com/user-attachments/assets/abb828a9-f261-4a1c-8bb5-f59e5208bf24" />


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

<img width="494" height="443" alt="image" src="https://github.com/user-attachments/assets/0b69cdc6-cda6-4b9d-99b6-751a3a3b8848" />


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

<img width="473" height="416" alt="image" src="https://github.com/user-attachments/assets/cafb4ac1-c822-4fe2-80b3-e656580c4d42" />


---

## 6️⃣ Hybrid Topology

### 📌 How it works
- Combination of multiple topologies

### ✅ Pros
- Flexible

### ❌ Cons
- Design complexity

<img width="476" height="421" alt="image" src="https://github.com/user-attachments/assets/8af7d7d0-e530-412a-babe-cd85b52201d1" />


---

> 💡 **Good network topology leads to fewer outages, faster debugging, and better scalability.**
