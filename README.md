Week 1 – Cybersecurity Internship Lab Setup
Project Overview

This project documents my Week 1 Cybersecurity Internship lab setup using Oracle VirtualBox and Kali Linux.

 Tools Used
- Oracle VirtualBox 7.2
- Kali Linux
- Windows 11
- 7-Zip

 Lab Configuration

1. Installed Oracle VirtualBox.
2. Downloaded and imported Kali Linux Virtual Machine.
3. Configured VM memory, processor and display settings.
4. Created a NAT Network with the subnet `10.0.0.0/24`.
5. Configured Kali Linux static IP address `10.0.0.2/24`.
6. Verified internet connectivity using the ping command.
7. Configured a shared folder between Windows and Kali Linux.
8. Verified file sharing using a test file.
9. Created a VirtualBox snapshot named `Kali-Final-Setup`.

 Verification Commands

Check IP Address
ip -4 addr show eth0

Test Internet Connectivity
ping -c 4 google.com

Check Shared Folder
ls -l /downloads

 Screenshots
 1. Kali Linux Desktop
[Kali Desktop](01-Kali-Desktop.png)

2. IP Address Configuration
[IP Address](02-IP-Address.png)

3. Internet Connectivity
[Internet Ping](03-Internet-Ping.png)

4. Shared Folder Verification
[Shared Folder](04-Shared-Folder.png)

5. VirtualBox Network Settings
[Network Settings](05-VirtualBox-Network-Settings.png)

6. VirtualBox Shared Folder Settings
[Shared Folder Settings](06-VirtualBox-Shared-Folder-Settings.png)

7. VirtualBox Snapshots
[Snapshots](07-VirtualBox-Snapshots.png)

Conclusion
Successfully completed the Week 1 Cybersecurity Internship lab setup. Verified Kali Linux installation, network configuration, internet connectivity and shared folder functionality.
