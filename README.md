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

![Static IP configuration via ipconfig](ipconfig-output.png)

![User accounts created via net user](user-accounts.png)

## Work Log
See [Day1-worklog.txt](Day1-worklog.txt) in this repository.

## Lab Roadmap

| Task | Status |
|------|--------|
| Windows 11 VM setup + network config |  Complete |
| Local user account management |  Complete |
| Ticketing system (Freshdesk) |  In Progress |
| PowerShell automation scripts |  Planned |
| Active Directory home lab |  Planned |
| Remote support simulation |  Planned |
| CompTIA A+ certification |  Studying |
