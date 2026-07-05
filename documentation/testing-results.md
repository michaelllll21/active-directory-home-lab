# Testing Results

This document contains the verification tests performed in the Active Directory Home Lab.

## Server Role Verification

| Test | Expected Result | Actual Result |
|------|-----------------|---------------|
| AD DS role installed | AD DS visible in Server Manager | Success |
| DNS role installed | DNS visible in Server Manager | Success |
| DHCP role installed | DHCP visible in Server Manager | Success |

![Server Manager Roles](../screenshots/01-server-manager-roles.png)

---

## Server IP Configuration

The Windows Server 2022 domain controller was configured with a static IP address.

| Item | Result |
|------|--------|
| IPv4 Address | 192.168.10.10 |
| DNS Server | 192.168.10.10 |
| Domain Suffix | SimoTech.com |

![Server IP Configuration](../screenshots/02-server-ipconfig.png)

---

## Active Directory Verification

Active Directory Users and Computers shows the SimoTech.com domain, organizational units, and domain users.

![Active Directory Users and Computers](../screenshots/03-active-directory-users-computers.png)

---

## DNS Verification

DNS Manager shows the SimoTech.com forward lookup zone.

![DNS Forward Lookup Zone](../screenshots/04-dns-forward-lookup-zone.png)

---

## DHCP Verification

DHCP Manager shows the configured IPv4 scope for the lab network.

![DHCP Scope](../screenshots/05-dhcp-scope.png)

---

## Windows 10 Domain Join Verification

The Windows 10 client successfully joined the SimoTech.com domain.

![Windows 10 Domain Joined](../screenshots/07-windows10-domain-joined.png)

---

## Client DNS Test

The Windows 10 client successfully resolved the SimoTech.com domain using the domain controller DNS server.

![Client DNS Test](../screenshots/08-client-ipconfig-nslookup.png)

---

## Domain User Login Test

The Helpdesk domain user successfully logged in to the Windows 10 client.

![Domain User Login](../screenshots/09-domain-user-login.png)

---

## Final Result

The Active Directory lab successfully demonstrated domain services, DNS, DHCP, Windows 10 domain joining, and domain user login verification.
