# 🌐 Network Address Translation (NAT)

> NAT enables devices on a private network to communicate with external networks by translating private IP addresses into public IP addresses.

---

## 📖 What is NAT?

**Network Address Translation (NAT)** is a technique used by routers to translate **private IP addresses** into **public IP addresses**, allowing multiple devices to share a single public IP address when accessing the internet.

---

## 🎯 Why is NAT Used?

- 🌍 Conserves public IPv4 addresses.
- 🏠 Allows multiple devices to share one public IP.
- 🔒 Hides internal IP addresses from external networks.
- 💰 Reduces the need for multiple public IP addresses.

---

## ⚙️ How NAT Works

1. A device sends a request to the internet using its private IP.
2. The router replaces the private IP with its public IP.
3. The destination server replies to the router.
4. The router translates the public IP back to the correct private IP and forwards the response.

---

## 📚 Types of NAT

### 🔹 Static NAT
Maps one private IP to one public IP.

### 🔹 Dynamic NAT
Maps a private IP to an available public IP from a pool.

### 🔹 PAT (Port Address Translation)
Allows multiple devices to share a single public IP by using different port numbers. This is the most common type of NAT in home networks.

---

## ✅ Advantages

- Conserves IPv4 addresses
- Improves privacy
- Allows internet access for private networks
- Easy to deploy

---

## ⚠️ Limitations

- Can make end-to-end connectivity more complex
- May affect some applications that require direct connections

