1. Why Linux for Security?
Most security tools (Wireshark, Nmap, Tcpdump, Snort, Suricata) run best on Linux.
Open-source, stable, and customizable operating system.
SOC analysts frequently use the Linux command line for monitoring, analysis, and investigation.

🔹 2. Basic Linux Commands (Must Know)
Command	Purpose
pwd	Show current working directory
ls -l	List files with details
cd /path	Change directory
cat file.txt	View file content
nano file.txt	Edit file in nano editor
touch file.txt	Create a new file
rm file.txt	Delete a file
cp a.txt b.txt	Copy file
mv a.txt b.txt	Move/Rename file
history	Show command history
🔹 3. User & Permissions
Command	Purpose
whoami	Show current user
id	Show user + group IDs
sudo command	Run command as root
chmod 755 file	Change permissions
chown user:group file	Change ownership
🔑 Linux Permissions

r → Read

w → Write

x → Execute

Example:

chmod 644 file.txt


Owner: read + write

Group: read

Others: read

🔹 4. Networking Commands
Command	Purpose
ifconfig or ip a	Show IP address
ping google.com	Test connectivity
traceroute google.com	Show route to target
netstat -tulnp	Show open ports
ss -tulnp	Modern replacement for netstat
curl http://example.com	Make HTTP request
dig google.com	DNS lookup
🔹 5. Practical Task (Try it in Kali)

Create a test file:

echo "Hello Security" > test.txt


Change permissions:

chmod 600 test.txt
ls -l test.txt


Show your IP:

ip a


Check open ports:

ss -tulnp


Ping a site:

ping -c 4 google.com




File permissions (ls -l) → Save as Day2_LinuxBasics/permissions_demo.png

Open ports (ss -tulnp) → Save as Day2_LinuxBasics/open_ports.png

🔹 6. Key Takeaways

Learned Linux file system and permissions ✅

Practiced basic commands (navigation, networking, permissions) ✅

Understood why Linux is essential for cybersecurity ✅
