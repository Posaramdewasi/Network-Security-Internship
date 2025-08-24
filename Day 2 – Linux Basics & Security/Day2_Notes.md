Day 2 – Linux Basics & Security
🔹 1. Why Linux for Security?

Most security tools (Wireshark, Nmap, Tcpdump, Snort, Suricata) Linux me run hote hain.

Open-source, stable, aur customizable OS.

SOC analysts ko Linux command line kaafi use karna padta hai.

🔹 2. Basic Linux Commands (Must Know)
Command	Purpose
pwd	Current working directory
ls -l	List files with details
cd /path	Change directory
cat file.txt	View file content
nano file.txt	Edit file
touch file.txt	Create new file
rm file.txt	Delete file
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

chmod 644 file.txt   # Owner: read+write, Group: read, Others: read

🔹 4. Networking Commands
Command	Purpose
ifconfig or ip a	Show IP address
ping google.com	Test connectivity
traceroute google.com	Show route
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



File permissions (ls -l)

Open ports (ss -tulnp)

Save as:

Day2_LinuxBasics/permissions_demo.png  
Day2_LinuxBasics/open_ports.png

🔹 6. Key Takeaway

Linux ka file system aur permissions samajh gaye ✅

Basic commands (navigation, networking, permissions) practice ho gaya ✅

Security ke liye Linux ka importance clear hua ✅
