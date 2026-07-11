# 🔐SSH 

## What is SSH?

**SSH (Secure Shell)** is a cryptographic network protocol used to securely connect to and manage remote computers over an unsecured network. It encrypts all communication between the client and the server, protecting data from unauthorized access.

SSH is widely used because it provides a secure way to:

- Remotely access servers and computers.
- Execute commands on remote systems.
- Transfer files securely using **SCP** and **SFTP**.
- Perform system administration tasks.
- Authenticate users using passwords or SSH keys.

---

## Key Features

- Encrypted communication
- Secure remote login
- Authentication using passwords or SSH keys
- Secure file transfer
- Port forwarding and tunneling
- Cross-platform support (Linux, Windows, macOS)

---

## SSH Architecture

SSH follows a **Client-Server** model.

- **SSH Client:** The device initiating the connection.
- **SSH Server:** The remote system that accepts SSH connections.

```
+----------------+        Encrypted Connection        +----------------+
|   SSH Client   |  ------------------------------->  |   SSH Server   |
| (Your Device)  |                                    | (Remote System)|
+----------------+                                    +----------------+
```

---

## Default Port

SSH uses **TCP Port 22** by default.

---

## Basic SSH Syntax

```bash
ssh username@hostname
```

Example:

```bash
ssh kali@192.168.1.10
```

---

## Common SSH Commands

Check SSH version:

```bash
ssh -V
```

Connect to a remote machine:

```bash
ssh username@hostname
```

Connect using a custom port:

```bash
ssh -p 2222 username@hostname
```

Exit an SSH session:

```bash
exit
```

---

## Advantages of SSH

- Encrypts all network traffic.
- Prevents password sniffing.
- Provides secure remote administration.
- Supports key-based authentication.
- Works across different operating systems.

---

## Real-World Uses

- Managing Linux servers
- Cloud server administration (AWS, Azure, GCP)
- Connecting to Raspberry Pi devices
- Accessing virtual machines
- Securely managing remote systems
- GitHub authentication using SSH keys

---

## Summary

SSH is one of the most important protocols in networking and cybersecurity. It enables secure remote access, encrypted communication, and safe file transfers, making it an essential tool for system administrators, developers, and cybersecurity professionals.


