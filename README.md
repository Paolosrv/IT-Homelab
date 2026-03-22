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

## What I Configured
- Enabled EFI for Windows 11 compatibility
- Installed VirtualBox Guest Additions — clipboard and drag/drop working
- Set static IP address (10.0.2.50) with Google DNS (8.8.8.8)
- Created local user accounts with correct permission levels:
  - `j.smith` — Standard User (simulates employee account)
  - `s.jones` — Standard User (simulates employee account)
  - `it.helpdesk` — Local Administrator (IT support account)
- Renamed PC to HELPDESK-PC01 following IT naming conventions
- Documented all changes in a work log

## Skills Demonstrated
`VirtualBox` `Windows 11` `Network Configuration` `User Account Management`
`Static IP` `Command Prompt` `IT Documentation` `EFI/UEFI`

## Screenshots

<img width="1022" height="480" alt="ipconfig-static-ip" src="https://github.com/user-attachments/assets/9ffbfcd2-1ef6-4733-88be-6714e641ea17" />
Static IP configuration via ipconfig

<img width="1023" height="765" alt="user-accounts-net-user" src="https://github.com/user-attachments/assets/774355c6-63f7-43b5-9f0e-efb6d483fef6" />
User accounts created via net user

## Work Log
See [Day1-worklog.txt](Day1-worklog.txt) in this repository.

## Lab Roadmap

| Task | Status |
|------|--------|
| Windows 11 VM setup + network config |  Complete |
| Local user account management |  Complete |
| Ticketing system (Freshdesk) |  Complete |
| PowerShell automation scripts |  Compete |
| Active Directory home lab |  Complete |
| Remote support simulation |  Planned |
| CompTIA A+ certification |  Studying |
