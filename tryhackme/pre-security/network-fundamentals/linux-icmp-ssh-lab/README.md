# Linux ICMP and SSH Home Lab

## Overview
This lab demonstrates basic network security testing using Kali Linux and Ubuntu Server.

## Lab Setup
- Kali Linux (attacker)
- Ubuntu Server (target)
- Network: 192.168.137.0/24

## Task 1: Ping Test
Tested connectivity:
ping 8.8.8.8
ping google.com

## Task 2: Block ICMP
sudo iptables -I INPUT -p icmp -s 192.168.137.131 -j DROP

## Task 3: Ping Failed
Ping shows 100% packet loss.

## Task 4: Restore ICMP
Ping works again after removing rule.

## Task 5: SSH Access
ssh study@192.168.137.128

## Task 6: Stop SSH
sudo systemctl stop ssh
sudo systemctl stop ssh.socket

## Task 7: SSH Blocked
Connection refused.
