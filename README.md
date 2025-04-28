# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
![image](https://github.com/user-attachments/assets/e933b2ba-bc24-4804-ad6d-cee006b206f8)
Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic
![image](https://github.com/user-attachments/assets/d6e99a52-b399-4eb3-8971-0d1f674fcd96)
Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

![image](https://github.com/user-attachments/assets/4e8f11fd-5b61-40e4-b033-f0f12a9b84f5)
Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.


![image](https://github.com/user-attachments/assets/9d16c20d-fc1b-4907-8c3a-fd787de90caa)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
