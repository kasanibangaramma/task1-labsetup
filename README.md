# task1-labsetup
cybersecurity&amp;ethical hacking 
# Task 1 – Cybersecurity Internship (Lab Setup & Fundamentals)

**Internship:** AICTE Apexplanet – Cybersecurity & Ethical Hacking  
**Name:** kasani bangaramma

---

## 🔹 Objective
Set up a professional hacking lab and practice fundamentals in Cybersecurity, Linux, Networking, Cryptography, and Tools.

---
## Lab Environment Setup
- Installed VirtualBox
- Installed Kali Linux (Attacker VM)
- Installed Metasploitable2 (Target VM)
- Configured **Host-Only Adapter** for isolated network

---

## Linux Fundamentals (Commands used)

```bash
# Check current directory
pwd

# List files with details
ls -la ~

# Create folder and file
mkdir demo_dir && cd demo_dir
echo "test" > file.txt

# Change permissions
chmod 600 file.txt
ls -l file.txt
## network basics
# Show IP details
ip addr show

# Ping target
ping -c 4 <TARGET_IP>

# Trace route
traceroute -m 10 <TARGET_IP>

# List open sockets
ss -tuln | head
## tools
# nmap
nmap -sS -Pn -p 22,80,443,3306 <TARGET_IP>
#wireshark
ip.addr == <TARGET_IP>


