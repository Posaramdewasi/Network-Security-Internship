# 📘 Day 2 – Linux Basics & Security  

---

## 🔹 Theory Notes

### Why Linux is Important for Security
- Most cybersecurity tools (Wireshark, Nmap, Tcpdump, Snort) run best on Linux.  
- Open-source, customizable, widely used in servers.  
- SOC Analysts must know Linux for log analysis & threat hunting.  

### Basic Linux Commands
- `pwd` → Print current directory.  
- `ls -l` → List files with permissions.  
- `cd /path` → Change directory.  
- `cat file.txt` → View file content.  
- `touch file.txt` → Create new file.  
- `rm file.txt` → Delete a file.  
- `cp a.txt b.txt` → Copy file.  
- `mv a.txt b.txt` → Rename/Move file.  

### File Permissions
- **r = read, w = write, x = execute**.  
- Example:  
  ```bash
  chmod 600 test.txt
  ls -l test.txt

