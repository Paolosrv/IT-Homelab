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

<img width="1022" height="480" alt="Screenshot 2026-03-17 014020" src="https://github.com/user-attachments/assets/f1eb6d88-a2f8-4d3c-b7eb-0b0000897f69" />

<img width="1023" height="765" alt="Screenshot 2026-03-17 011016" src="https://github.com/user-attachments/assets/b66604b3-a101-481e-a865-448679a9b154" />

## Work Log
See `Day1-WorkLog.txt` in this repository.

[Day1-worklog.txt](https://github.com/user-attachments/files/26087188/Day1-worklog.txt)
IT HOME LAB - WORK LOG DATE: 17/03/2026 Technician "Paolo Revollo" Machine "HELPDESK-PC01=================================================
Task: Build Windows 11 Pro home lab in VirtualBox COMPLETED: - Virtual Box 7.X installed with extension Pack - VM created: 2 vCPUs, 8GB RAM, 60GB VID disk compatibility - Guest Additions installed - clipboard working - static IP configured: 10.0.2.50/24 GW: 10.0.2.2 DNS: 8.8.8.8 - Hostname set to HELPDESK-PC01 - User Accounts created: j.smith - Standard User s.jones - Standard User it.deskhelp - Local Administrator - Connectivity verified: ping 8.8.8.8 and google.com successful - snapshot taken:"Day1 complete" ISSUES encountered: "Change graphics controller to VMSVGA to run and install the system"
Learning: Basic VM settings, networking config and User accounts settings.
