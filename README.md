# Task 5: Capture and Analyze Network Traffic Using Wireshark

## 📌 Objective:
To capture and analyze live network traffic using Wireshark and identify common internet protocols.

## 🛠 Tools Used:
- Wireshark 4.4.7
- Windows 11

## 📶 Protocols Identified:
1. **TCP** – Reliable communication, seen between client and servers.
2. **UDP** – Used for fast, connectionless traffic like QUIC.
3. **DNS** – Domain Name System resolving domain names to IPs.
4. **HTTP** – Web communication protocol.
5. **TLS** – Secure layer for encrypted communication.
6. **QUIC** – Modern fast protocol using UDP, often for Google services.

## 🧾 Packet Samples:
- **TCP**: Between 192.168.x.x and external IPs over port 443 (HTTPS)
- **UDP/QUIC**: Port 443 to 103.233.140.204 (Google service)
- **DNS**: Queries for domains like `google.com`, `hotstar.com`
- **HTTP**: File downloads from `amd.com`, JSON files
- **TLS**: Handshakes with servers (TLSv1.3)

## 📷 Screenshots Included:
- Interface selection
- Filters applied: UDP, TCP, DNS, HTTP, TLS

## 📁 Files Included:
- `task5-capture.pcapng` – Packet capture file
- Screenshots for each protocol view
- This README file

## ✅ Completed Steps (from guide):
- Wireshark installed and capture completed ✔️
- Filters applied and screenshots taken ✔️
- `.pcapng` file exported ✔️
- Report created ✔️

---

🔗 **Ready for GitHub Upload**