# 📡 Network Traffic Capture and Analysis with Wireshark

## 🎯 Objective
Capture live network traffic using Wireshark to:
- Identify common protocols (HTTP, DNS, TCP).
- Analyze packet structure and protocol interactions across OSI layers.
- Apply filters to focus on specific traffic types.
- Build practical skills in packet capture and network troubleshooting.


---

## 🛠️ Tools 
- **Wireshark**


---

## 📝 Procedure
1. **Installed and launched Wireshark.**
2. **Started capture** on the active network interface (**Wi-Fi**).
3. **Generated traffic**:
   - Browsed websites.
   - Ran `ping google.com`.
4. **Captured packets** for approximately 1 minute.
5. **Applied display filters** to analyze specific protocols:
   - `http`
   - `dns`
   - `tcp`
6. **Identified key protocols** present in the capture.
7. **Exported capture** as:
   - `network_capture.pcap`

---

## 📊 Summary of Findings

| Protocol | Purpose                           | Example Packet                           |
|----------|-----------------------------------|------------------------------------------|
| **HTTP** | Website data transfer            | `GET /` request to `example.com`        |
| **DNS**  | Resolving domain names to IPs    | Query for `google.com`                  |
| **TCP**  | Transport layer communication    | TCP handshake (`SYN`, `SYN-ACK`, `ACK`) |

---

## ✅ Outcome
- Successfully captured and analyzed live network traffic.
- Developed understanding of:
  - **Protocol layers** (Application, Transport).
  - **Packet structure** and sequence (e.g., TCP handshake).
- Practiced using **Wireshark filters** to isolate and inspect specific traffic types.

---

## 📂 Files
- `network_capture.pcap`: Exported capture file containing the packet data.

---


