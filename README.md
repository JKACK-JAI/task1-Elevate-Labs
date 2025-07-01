# 🔍 Cyber Security Internship - Task 1

## 📌 Task Title:
**Scan Your Local Network for Open Ports using Nmap**

---

## 🎯 Objective:
To understand basic network reconnaissance by identifying devices in the local network and scanning for open ports using Nmap. This helps analyze potential vulnerabilities and understand how attackers may target exposed services.

---

## 🧰 Tools Used:
- [Nmap](https://nmap.org/) – for port scanning
- (Optional) Wireshark – for traffic analysis

---

## 💻 Command Used:

**sudo nmap -sS 192.168.1.0/24**


# 📎 Explanation:
sudo – run with root access (required for SYN scan)

nmap – tool used

-sS – TCP SYN scan (stealthy and fast)

192.168.1.0/24 – scans 256 IPs in the local subnet

# 📘 Task Explanation:
The purpose of this task is to perform network reconnaissance by scanning the local network to discover active devices and identify any open ports that could expose services to potential attackers.

Steps I Followed:
Checked my local IP range (192.168.1.0/24)

Performed a TCP SYN scan with Nmap

Identified active hosts and open/closed ports

Analyzed what services might be running (e.g., HTTP, HTTPS)

Saved results and documented the findings

# 📊 Scan Result Summary:
# 📂 See file: nmap_output_task1.txt

Host: 192.168.1.1 (Router - dsldevice.lan)

Open Ports:

80/tcp → HTTP (Admin Interface)

443/tcp → HTTPS (Secure Access)

MAC Address: 60:BD:2C:F1:B9:10

Host: 192.168.1.6

All 1000 ports closed

MAC Address: FA:A6:6B:E6:4A:01

Host: 192.168.1.8

All 1000 ports closed

# 🔐 What I Learned:
How to identify hosts in a network using Nmap

How open ports indicate exposed services

Basic security risks from running services

First step toward ethical hacking and penetration testing

# 📁 Files Included:
nmap_output_task1.txt – Scan output

README.md – This explanation file

