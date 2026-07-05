# IP Addressing Plan

## Network Information

| Item | Value |
|------|-------|
| Network Address | 192.168.10.0/24 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.10.1 |
| DNS Server | 192.168.10.10 |
| Domain Controller | 192.168.10.10 |

## Server Static IP

| Device | Role | IP Address | DNS |
|--------|------|------------|-----|
| Server2022 | Domain Controller / DNS / DHCP | 192.168.10.10 | 192.168.10.10 |

## DHCP Scope

| Scope Item | Value |
|------------|-------|
| Scope Name | SimoTech DHCP Scope |
| Start IP Address | 192.168.10.50 |
| End IP Address | 192.168.10.200 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.10.1 |
| DNS Server | 192.168.10.10 |
| Domain Name | SimoTech.com |

## Client IP Assignment

| Device | Role | IP Address Method |
|--------|------|-------------------|
| Desktop1 | Windows 10 Domain Client | DHCP |
| Kali-Linux | Testing Machine | DHCP / Static |
