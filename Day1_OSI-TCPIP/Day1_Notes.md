Day 1 – OSI Model, TCP/IP & Wireshark Basics
🔹 1. OSI Model (7 Layers)

Application Layer – User applications like HTTP, FTP, DNS.

Presentation Layer – Encryption, compression, data formatting.

Session Layer – Establishes, maintains, and terminates sessions.

Transport Layer – Ensures reliable delivery (TCP/UDP).

Network Layer – Logical addressing (IP) and routing.

Data Link Layer – MAC addressing and error detection.

Physical Layer – Physical transmission: cables, signals, hardware.

🔹 2. TCP/IP Model (4 Layers)

Application Layer – Protocols (HTTP, DNS, SMTP).

Transport Layer – Responsible for end-to-end delivery (TCP/UDP).

Internet Layer – IP addressing, routing.

Network Access Layer – Ethernet, ARP, physical transmission.

🔹 3. TCP 3-Way Handshake

Step 1: SYN → Client requests a connection.

Step 2: SYN/ACK → Server acknowledges request.

Step 3: ACK → Client confirms.
✅ Secure TCP session established.

🔹 4. Practical Task (Wireshark)

Install and open Wireshark.

Start packet capture on your active network interface.

Open browser → Visit http://example.com.

Stop capture.

Apply filter:

http


Look for TCP 3-way handshake (SYN → SYN/ACK → ACK) packets.

Save screenshot → Day1_Wireshark/wireshark_handshake.png.

🔹 5. Key Takeaways

Understood OSI vs TCP/IP models.

Learned how TCP handshake establishes reliable communication.

Performed first hands-on task with Wireshark.
