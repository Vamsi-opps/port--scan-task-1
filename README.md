#Cyber Security Internship - Task 1: Port Scan
Discover **open ports** and **services** running on devices in my local network.
Tools Used
- **Nmap** – Network scanning tool
- **Wireshark**  – Network traffic analyzer
- **Linux Terminal** – For running commands
- Installed Nmap on Linux by using
-sudo apt update
-sudo apt install nmap -y
-I found my local IP address and subnet  using ip a.
-Performed a TCP SYN Scan for 10.0.2.15/24.
-saved scan results.
-Analyzed network packets using Wireshark.
Main Findings
Active Devices Found: 3 devices 

Common Open Ports:

22 (SSH)

80 (HTTP)

443 (HTTPS)


Potential Risks:

Open SSH (port 22) devices may risk a brute-force attack unless secured.

Open HTTP (port 80) can expose insecure services unless encrypted or updated.

Inadequate, missing, or improperly configured firewalls enable attackers to find and take advantage of available services.

