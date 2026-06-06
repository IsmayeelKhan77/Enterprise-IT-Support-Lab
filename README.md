# Enterprise IT Support Lab — Simulated Helpdesk Environment

**Author:** Ismayeel Khan
**Date:** June 2026
**Environment:** VMware Workstation 17 Player | Windows Server 2022 | Windows 11 Pro
**Domain:** Project.local
**Ticketing System:** Spiceworks Cloud Help Desk

---

## Project Overview

This project simulates a real-world enterprise IT support environment built from scratch using virtualization technology. The objective was to replicate the responsibilities and workflows of a Helpdesk Technician by building a multi-VM lab infrastructure, deploying a ticketing system, and resolving ten realistic IT support scenarios using structured troubleshooting methodology.

---

## Lab Infrastructure

The lab consists of two virtual machines running on VMware Workstation 17 Player. The first machine runs Windows Server 2022 and serves as the domain controller for the Project.local Active Directory domain. It also hosts the Spiceworks Cloud Help Desk ticketing system. The second machine runs Windows 11 Pro and represents a standard employee workstation joined to the domain. Both machines are connected via a private LAN Segment network adapter simulating a local business network, with a secondary NAT adapter providing internet access.

---

## Technologies Used

- VMware Workstation 17 Player
- Windows Server 2022
- Windows 11 Pro
- Active Directory Domain Services
- Spiceworks Cloud Help Desk
- Remote Desktop Protocol (RDP)
- Windows Command Prompt
- Event Viewer
- Task Manager
- Group Policy Management

---

## Helpdesk Ticketing System

Spiceworks Cloud Help Desk was configured with four ticket rules for automatic categorisation covering Network, Software, Hardware, and Account issues. Three canned responses were created to ensure professional and consistent communication with users throughout the ticket lifecycle.

---

## Support Scenarios Resolved

| Ticket | Issue | Priority | Category |
|--------|-------|----------|----------|
| T1 | Account Lockout | High | Account |
| T2 | Password Reset Request | High | Account |
| T3 | Cannot Connect to Network | High | Network |
| T4 | Remote Desktop Connection Issue | High | Network |
| T5 | Software Installation Failure | Medium | Software |
| T6 | Windows Update Error | Medium | Software |
| T7 | Slow System Performance | Medium | Hardware |
| T8 | Shared Drive Access Denied | High | Network |
| T9 | Application Crash | Medium | Software |
| T10 | New User Account Setup | High | Account |

---

## Repository Structure

- Documents — Contains three professional portfolio documents including the Lab Environment Overview, Ticket Resolution Log, and IT Support Troubleshooting Template
- Screenshots — Contains all lab screenshots organised by checkpoint

---

## Key Skills Demonstrated

- Virtual machine deployment and network configuration
- Active Directory user and group management
- Helpdesk ticket creation, prioritisation, categorisation, and closure
- Remote Desktop Protocol setup and troubleshooting
- Windows Update service management via Command Prompt
- Network connectivity troubleshooting using ping and ipconfig
- Shared folder permissions management
- Event Viewer log analysis
- System File Checker (sfc /scannow) usage
- Professional IT support documentation

---

## Related Projects

- Project 1 — Active Directory User Management Lab: github.com/IsmayeelKhan77
