# Cisco WAN & Internet Simulation Topology

A network architecture designed and simulated in **Cisco Packet Tracer**. This project demonstrates the separation between a private Local Area Network (LAN) and the public Internet (WAN).

## 🌐 Network Overview
<img width="1920" height="1015" alt="2026-11-04_20-59-35" src="https://github.com/user-attachments/assets/495cb939-23b8-45c5-b0f5-69857679337a" />


### ⚙️ Implemented Features:
* **Internet Simulation:** Configured a dedicated public Server acting as a remote Web Server, accessible via HTTP/HTTPS.
* **SOHO Gateway:** A Wireless Router acts as the boundary gateway separating the private internal network from the external web.
* **Hybrid LAN:** Supports both wired (via central Layer 2 Switch) and wireless (Wi-Fi) endpoints within the home/office zone.
* **End-to-End Connectivity:** Verified web routing by successfully accessing the Server's website using the built-in Cisco Packet Tracer Web Browser from end devices.

## 🛠️ Tools Used
* **Cisco Packet Tracer** (Simulation environment)
* **File format:** `.pkt`

## 🚀 How to Run
1. Download the `soho.pkt` file.
2. Open it in **Cisco Packet Tracer**.
3. Select any PC or Laptop, open the **Desktop** tab, and launch the **Web Browser**.
4. Enter the Server's IP address to view the simulated website.
## ⌨️ Configuration Note
In this layout, the network is built using standard plug-and-play components. Unlike complex enterprise systems, this SOHO simulation utilizes a standard Layer 2 Switch and a Home Wireless Router that do not require any manual CLI configuration scripts. All basic functions work automatically out of the box.


