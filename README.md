# 🌐 Local Attacks on DNS Server

## ✨ Description

The **Domain Name System (DNS)** functions as the Internet’s **phone book**, translating hostnames into **IP addresses** and vice versa. This translation process, known as **DNS resolution**, happens behind the scenes.

**DNS attacks** exploit vulnerabilities in this resolution process to **redirect users** to unintended, often malicious, destinations.  

The goal of this lab is to explore how these attacks operate. Participants will:
1. Set up and configure a DNS server.
2. Execute various DNS manipulations within a controlled lab environment to understand their impact and mechanisms.

![DNS Attack Image](image-link) *(Replace "image-link" with the actual image URL)*

---

## 💻 Languages and Utilities Used

- **Python**
- **Ubuntu 20.04 VM**

---

## 🖥️ Environments Used

- **Windows 11 Home (21H2)**

---

## 🧑‍🏫 Lab Topics Covered

- **DNS server setup**
- **DNS cache poisoning attack**
- **Spoofing DNS responses**
- **Packet sniffing and spoofing**
- **The Scapy tool**
- **Shell script commands:**

```bash
./dc-build.sh  # Build the docker images; can take an additional parameter, e.g. ./dc-build.sh --no-cache
./dc-up.sh  # Start the docker containers in the foreground
./dc-up-d.sh  # Start the docker containers in the background
./dc-stop.sh  # Stop the docker containers; can take an additional parameter for the stop process
./dc-down.sh  # Stop and remove the docker containers; can take an additional parameter for the stop and remove process
./dc-unittest.sh  # Utility script to run a specific unit test class
