#  Network Protocol Analysis Lab

##  Overview

This project demonstrates how core network protocols work in practice by capturing and analyzing real traffic using Wireshark.

The lab covers:

* DNS (Domain Name System)
* ICMP (Ping)
* TCP (3-way handshake)
* HTTP / HTTPS communication

---

##  Objective

To understand how a website loads step-by-step:

1. DNS resolves a domain name to an IP address
2. ICMP verifies connectivity
3. TCP establishes a reliable connection
4. HTTP/HTTPS transfers data

---

##  Tools Used

* Kali Linux
* Wireshark
* curl
* nslookup / dig
* ping

---

##  Screenshots Description

###  DNS Analysis

* **DNS lookup using nslookup (domain → IP)**
* **DNS query and response for google.com (A and AAAA records)**

###  ICMP (Ping)

* **ICMP connectivity test using ping**
* **ICMP echo request and echo reply traffic in Wireshark**

###  TCP Analysis

* **TCP 3-way handshake: SYN → SYN-ACK → ACK**
* Connection established between client and server

###  HTTP / HTTPS Analysis

* **HTTP/HTTPS requests using curl**
* **HTTP GET request and 301 redirect response**
* HTTPS traffic observed with TLS (encrypted communication)
