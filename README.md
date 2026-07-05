# Windows Server Active Directory Home Lab

## Project Overview
This project documents a Windows Server 2022 Active Directory home lab built for practicing common IT support, system administration, and networking tasks. The lab includes a domain controller, DNS, DHCP, domain-joined Windows 10 client, user and group management, Group Policy, mapped drives, and basic troubleshooting.

## Objectives
- Install and configure Windows Server 2022 as a domain controller
- Create an Active Directory domain
- Configure DNS and DHCP services
- Create users, organizational units, and security groups
- Join a Windows 10 client to the domain
- Apply Group Policy settings
- Configure mapped network drives
- Practice basic helpdesk tasks such as password reset and account unlock
- Document configuration steps and troubleshooting results

## Lab Environment

| Device | Role | Operating System | IP Address |
|--------|------|------------------|------------|
| Server2022 | Domain Controller / DNS / DHCP | Windows Server 2022 | 192.168.10.10 |
| Desktop1 | Domain Client | Windows 10 | DHCP |
| Kali-Linux | Testing Machine | Kali Linux | DHCP / Static |

## Domain Information

| Item | Value |
|------|-------|
| Domain Name | SimoTech.com |
| Domain Controller | server2022.simotech.com |
| Network | 192.168.10.0/24 |
| Gateway | 192.168.10.1 |
| DNS Server | 192.168.10.10 |

## Tools Used
- Oracle VirtualBox
- Windows Server 2022
- Windows 10
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy Management
- Command Prompt / PowerShell
- Remote Desktop / RSAT

## Key Features Implemented
- Active Directory domain setup
- DNS and DHCP configuration
- User and group management
- Windows 10 domain join
- Group Policy configuration
- Mapped network drives
- Basic troubleshooting documentation

## Documentation
- [Lab Environment](documentation/lab-environment.md)
- [IP Addressing Plan](documentation/ip-addressing.md)
- [Configuration Steps](documentation/configuration-steps.md)
- [Testing Results](documentation/testing-results.md)
- [Troubleshooting Notes](documentation/troubleshooting-notes.md)

## Project Status
In progress.

## Resume Summary
Built and documented a Windows Server 2022 Active Directory home lab with DNS, DHCP, domain-joined Windows 10 client, user and group management, Group Policy, mapped drives, and basic helpdesk troubleshooting tasks.
