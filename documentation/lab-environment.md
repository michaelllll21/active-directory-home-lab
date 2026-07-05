# Lab Environment

## Overview
This lab was built using Oracle VirtualBox to simulate a small business Windows domain environment. The main goal of this lab is to practice Active Directory, DNS, DHCP, Group Policy, domain joining, and basic IT support tasks.

## Virtual Machines

| Device | Role | Operating System | Network Mode |
|--------|------|------------------|--------------|
| Server2022 | Domain Controller, DNS, DHCP | Windows Server 2022 | Internal Network / NAT |
| Desktop1 | Domain Client | Windows 10 | Internal Network / NAT |
| Kali-Linux | Testing Machine | Kali Linux | Internal Network / NAT |

## Domain Information

| Item | Value |
|------|-------|
| Domain Name | SimoTech.com |
| Domain Controller | server2022.simotech.com |
| Server IP Address | 192.168.10.10 |
| DNS Server | 192.168.10.10 |
| Default Gateway | 192.168.10.1 |
| Network Address | 192.168.10.0/24 |

## Services Used
- Active Directory Domain Services
- DNS Server
- DHCP Server
- Group Policy Management
- File Sharing
- Remote Desktop
- RSAT Tools

## Purpose of the Lab
This lab is designed to demonstrate practical IT support and system administration skills such as creating users, managing groups, joining computers to a domain, applying Group Policy, configuring DHCP, and troubleshooting network/domain issues.
