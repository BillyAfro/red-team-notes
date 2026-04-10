# TCP/IP Model + TCP Basics

## 🔷 TCP/IP Model (4 layers)

1. Application → HTTP, DNS, SSH (user-level protocols)
2. Transport → TCP / UDP (communication between hosts)
3. Internet → IP addressing + routing (Packet delivery)
4. Network Interface → Physical + Data Link (MAC, cables, signals)

---

## 🔁 Mapping OSI → TCP/IP

- OSI Layer 7-5 → Application
- OSI Layer 4 → Transport
- OSI Layer 3 → Internet
- OSI Layer 2-1 → Network Interface

---

## 📦 Encapsulation flow

Data → Segment → Packet → Frame → Bits

---

## 🔥 TCP (Transmission Control Protocol)

- Connection-based protocol
- Reliable communication between devices
- Ensures data delivery (retransmission if lost)

---

## 🤝 Three-way handshake (TCP connection setup)

1. Client → SYN
2. Server → SYN-ACK
3. Client → ACK

✔ Connection established after this process

---

## 📌 Key terms

- SYN = Synchronise (start connection)
- ACK = Acknowledgement (confirm receipt)
- SYN-ACK = response from server

---

## ⚔️ TCP vs UDP

| TCP | UDP |
|-----|-----|
| Connection-based | Connectionless |
| Reliable | Fast but no guarantee |
| Slower | Faster |
| Used in web, SSH | Used in streaming, gaming |

---

## 🧠 Summary

TCP/IP is the real-world networking model.
It defines how data moves from one device to another using protocols like TCP and IP.
