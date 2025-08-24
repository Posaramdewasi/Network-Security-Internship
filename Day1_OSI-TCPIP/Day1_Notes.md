Day 1 – OSI vs TCP/IP & Packet Capture

🔹 1. OSI Model (7 Layers)
Layer	Function	Example Protocols

7. Application	User interaction	HTTP, FTP, DNS
6. Presentation	Data translation, encryption	SSL/TLS, JPEG
5. Session	Session management	NetBIOS, RPC
4. Transport	Reliable delivery, segmentation	TCP, UDP
3. Network	Routing packets	IP, ICMP
2. Data Link	Frames, MAC addressing	Ethernet, ARP
1. Physical	Transmission media	Cables, Wi-Fi
   
🔹 2. TCP/IP Model (4 Layers)
Layer	Matches OSI Layer(s)	Protocols
Application	Application + Presentation + Session	HTTP, FTP, DNS, SMTP
Transport	Transport	TCP, UDP
Internet	Network	IP, ICMP, ARP
Network Access	Data Link + Physical	Ethernet, Wi-Fi

🔹 3. Common Ports
Protocol	Port	Transport
HTTP	80	TCP
HTTPS	443	TCP
FTP	21	TCP
SSH	22	TCP
DNS	53	TCP/UDP
ICMP (Ping)	N/A	Network Layer


🔹 4. Practical Task – TCP 3-Way Handshake
Steps in Kali Linux:

Install Wireshark:

sudo apt update && sudo apt install wireshark -y


Run Wireshark:

sudo wireshark


Start capture on active interface (eth0 or wlan0).

Open browser → Visit: http://example.com

Apply filter:

tcp.flags.syn==1 || tcp.flags.ack==1


Identify 3 packets:

SYN → Client → Server

SYN/ACK → Server → Client

ACK → Client → Server



🔹 5. Key Takeaway

OSI vs TCP/IP model difference clear hua ✅

TCP 3-way handshake samajh liya ✅

Wireshark ka basic capture aur filter use karna seekh liya ✅
