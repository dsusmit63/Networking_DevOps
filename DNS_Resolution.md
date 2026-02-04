# 🚀 DNS (Domain Name System)

DNS translates human-readable domain names into IP addresses that computers use to communicate.

### 🔁 Basic Concept

- Domain Name → IP Address  
- Example: `google.com` → `142.250.190.78`

---

## 📌 DNS Resolution Process

When you type a website in your browser (for example: `www.example.com`), the following steps happen:

1. Browser asks for the IP address of the domain
2. DNS resolver (ISP/System DNS) checks:
   - Browser cache  
   - Operating system cache  
   - Router cache  

   👉 If found, the website loads quickly

3. If not found, the resolver queries the internet DNS system:
   - Root DNS Server
   - TLD Server (like `.com`)
   - Authoritative DNS Server

4. Authoritative server returns the real IP address of the domain
5. Browser connects to the web server using that IP
6. Website loads ✨

---

## ⚡ DNS Caching (Performance Boost)

The DNS resolver stores the IP address for a certain time called **TTL (Time To Live)**.

This allows future requests to be resolved faster without repeating the full lookup process.

---

### 📌 Quick Summary

> DNS works like the internet’s phonebook — converting domain names into IP addresses.

