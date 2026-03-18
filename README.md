# IT-Homelab
Windows 11 home lab for IT Support skills building 
# IT Home Lab — Windows 11 Pro

## Overview
A hands-on IT support home lab built using VirtualBox and Windows 11 Pro.
This lab simulates a real workplace desktop environment for practising
IT support tasks including user account management, network configuration,
and system administration.

## Lab Environment
| Component | Details |
|-----------|---------|
| Hypervisor | VirtualBox 7.2.6 |
| Guest OS | Windows 11 Pro (Evaluation) |
| RAM allocated | 8 GB |
| Disk | 80 GB (dynamically allocated VDI) |
| Hostname | HELPDESK-PC01 |
| Static IP | 10.0.2.50 / 24 |

## What I configured
- Enabled EFI for Windows 11 compatibility
- Installed VirtualBox Guest Additions
- Set static IP address (10.0.2.50) with Google DNS
- Created local user accounts with correct permission levels:
  - `j.smith` — Standard User (simulates employee account)
  - `s.jones` — Standard User (simulates employee account)
  - `it.helpdesk` — Local Administrator (IT support account)
- Documented all changes in a work log

## Skills demonstrated
`VirtualBox` `Windows 11` `Network configuration` `User account management`
`Static IP` `Command Prompt` `IT documentation`

## Screenshots

<img width="1022" height="480" alt="ipconfig-static-ip" src="https://github.com/user-attachments/assets/0320f13a-7a8e-4a84-8e71-271c5d3a600d" />

<img width="1023" height="765" alt="user-accounts-net-user" src="https://github.com/user-attachments/assets/de1a2e04-93ef-4fd1-b457-b786fd4474cd" />

## Work Log
See `Day1-WorkLog.txt` in this repository.
