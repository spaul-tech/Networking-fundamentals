# 🌐 Address Resolution Protocol (ARP)

> Learn how devices on a local network discover the **MAC address** associated with an **IPv4 address**.

---

## 📖 What is ARP?

**Address Resolution Protocol (ARP)** is a network protocol used to map an **IPv4 address** to its corresponding **MAC (Media Access Control) address** within a **Local Area Network (LAN)**.

When a device knows the destination IP address but not its MAC address, it uses ARP to discover the correct MAC address before sending the data.

---

## ❓ Why is ARP Needed?

Devices communicate differently at different layers of the OSI model:

- 🌍 **Layer 3 (Network Layer)** uses **IP addresses**.
- 🔌 **Layer 2 (Data Link Layer)** uses **MAC addresses**.

Since Ethernet frames require a destination MAC address, ARP acts as a bridge between the **Network Layer** and the **Data Link Layer**.

---

## ⚙️ How ARP Works

1. 📤 A device wants to send data to another device on the same network.
2. 🔍 It checks its **ARP Cache** for the destination MAC address.
3. 📢 If the MAC address is not found, it sends an **ARP Request** (broadcast).
4. 📥 The device with the matching IP address replies with an **ARP Reply** containing its MAC address.
5. 💾 The sender stores the mapping in its ARP Cache.
6. 📦 The data is then sent using the discovered MAC address.

---

## 🖼️ ARP Communication

![ARP Communication](images/arp-communication.png)

---

## 📋 ARP Cache

An **ARP Cache** is a temporary table maintained by the operating system that stores recently learned IP-to-MAC address mappings.

### Example

| IP Address | MAC Address |
|------------|-------------|
| 192.168.1.1 | 00:11:22:33:44:55 |
| 192.168.1.20 | AA:BB:CC:DD:EE:FF |

---

## 🛠️ Common ARP Commands

### 🐧 Linux

```bash
arp -a
```

or

```bash
ip neigh
```

### 🪟 Windows

```cmd
arp -a
```

---

## 📚 Key Terms

- 🌍 **IP Address** – Logical address of a device.
- 🔌 **MAC Address** – Physical address assigned to a network interface.
- 📢 **Broadcast** – Sent to all devices on the local network.
- 📩 **Unicast** – Sent to one specific device.
- 💾 **ARP Cache** – Stores IP-to-MAC mappings.

---

## ⚠️ Limitations of ARP

- Works only within a **Local Area Network (LAN)**.
- Supports **IPv4 only**.
- Vulnerable to **ARP Spoofing/ARP Poisoning** attacks.

---

## 🔐 Security Note

Attackers can perform **ARP Spoofing** by sending fake ARP replies, causing devices to associate an incorrect MAC address with an IP address.

This can lead to:

- 🎯 Man-in-the-Middle (MITM) attacks
- 📡 Packet interception
- 🚫 Network disruptions 
