# 📡 Dynamic Host Configuration Protocol (DHCP)

DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and other network settings to devices, eliminating the need for manual configuration.

## 🎯 What DHCP Provides

- 🌐 IP Address
- 🎭 Subnet Mask
- 🚪 Default Gateway
- 🌍 DNS Server
- ⏱️ Lease Time

## 🔄 DHCP Process (DORA)

| Step | Description |
|------|-------------|
| **Discover** | Client searches for a DHCP server. |
| **Offer** | Server offers an available IP address. |
| **Request** | Client requests the offered IP. |
| **Acknowledge** | Server confirms the lease. |

## 🌐 DHCP Ports

| Protocol | Port |
|----------|------|
| UDP | 67 (Server) |
| UDP | 68 (Client) |

## 🖥️ Useful Commands

### Windows

```powershell
ipconfig /all
ipconfig /renew
ipconfig /release
```

### Linux

```bash
ip addr
sudo dhclient
```

📌 *Part of my Networking & Cybersecurity learning journey.*
