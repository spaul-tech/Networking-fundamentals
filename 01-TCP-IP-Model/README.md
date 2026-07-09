# TCP
**TCP** stands for Transmission Control Protocol

Ensures data sent from one device reaches to destination intact,in correct order without errors.

## Flags of TCP are :-

| Flags | Description|
|-|-|
|`ACK`(Acknowledgement)| Acknowledges the receipt of a packet|
|`SYN`(Synchronize) | Initiates connection between hosts|
|`URG`(Urgent)| Data contained in packet should be processed immediately|
|`PSH`(Push)| Sends all buffered data immediately|
|`RST`(Reset)| Resets a connection|
|`FIN`(Finish)| There will be no further transmission|

👉*TCP uses 3 way handshake to establish a connection*

# IP address
**IP** stands for Internet Protocol 

It's a unique numerical label assigned to every device connected to a computer network.

Two versions :-

**IPv4** - The traditional format, composed of four numbers separated by periods. (e.g., 192.168.0.1).
Each period have 8 bits, so a total address has 32 bits.
* It has total 2³²≈4.7 billion addresses. 

**IPv6** - The newer,alphanumeric format with hexadecimal notation developed to prevent a shortage of addresses 
(e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334). Each period have 16 bits, so total address has 128 bits.
* It has total 2¹²⁸≈340 trillion addreses.

Types of IP addreses :-
- Public address -
  - When many systems needs network for data transmission , public IP is used.
  - WAN is used.
- Private address -
  - When very few systems communicate in a small area , private IP is used.
  - LAN is used.

*Private IP can't communicate with public IP or vice-versa.*

- Dynamic address -
  - Mobile internets use dynamic IP's.
  - This IP is temporary.
- Static address -
  - These are reserved for business internets.
  - Its permanently assigned to a organization.
