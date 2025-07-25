# YOUHON - Honeypot & Intrusion Alert System

YouHon is a lightweight and powerful Ruby-based honeypot tool designed for network defense and intrusion detection. It simulates vulnerable services to deceive attackers, detect scanning or unauthorized access attempts, and raise alerts instantly.

⚠ Designed to deceive attackers. Built to alert defenders.

# Features
 Fake Service Emulation---->    Emulates common services (FTP, SSH, SMTP, SMB, LDAP, SNMP, TELNET, RDP, MYSQL, HTTPS etc.) on selected ports to attract and trap scans or unauthorized connection attempts.

 Real-time Scan Detection---->  Monitors the system for suspicious activity and detects port scans or connection attempts instantly.
 
 Intrusion Sound Alert----->      Triggers a  audio alert (inspired by Mr. Robot) when any intrusion or scanning is detected.

 Logging System<br>
 
Scan.txt: Records all scan attempts with source IP, port number, and timestamp. <br>
Log.txt: Logs every connection attempt with full details for forensic review.

# Purpose
 Built for defenders, YouHon helps:

> Identify unauthorized scanning activity

> Gather early warning signs of potential attacks

> Improve your network visibility and threat awareness


# Installation
git clone https://github.com/1Y0U1/YOUHON.git <br>
cd YOUHON<br>
chmod +x setup.sh<br>
bash setup.sh<br>
chmod +x youhon<br>
./youhon -h
