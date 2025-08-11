**📡 Wireshark Packet Capture – Protocol Analysis**

**Objective**

Capture live network packets using Wireshark and identify basic network protocols involved in typical browsing activity.

**Tools Used**

- Wireshark (Kali Linux VM)

**Steps Performed**

- Installed Wireshark using sudo apt install wireshark.

- Started capture on the active network interface (eth0).

- Generated traffic by browsing a website and running ping.

- Stopped capture after ~1 minute.

- Filtered packets by protocol (DNS, HTTP, TCP).

- Exported capture as packet_capture.pcap.

**Protocols Identified**

- DNS – Domain name resolution.

- HTTP – Web page requests and responses.

- TCP – Reliable transport for web and DNS traffic.

