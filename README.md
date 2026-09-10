# Windows Server 2025 Active Directory Homelab

## Project Overview

This project involved building a virtualized Windows Server environment to simulate a small enterprise network. The lab demonstrates core system administration tasks including deploying a domain controller, configuring DNS services, managing domain users, applying Group Policy, and joining a Windows 11 client workstation to the domain.

## Objectives

- Deploy a Windows Server 2025 virtual machine
- Install and configure Active Directory Domain Services (AD DS)
- Configure DNS for domain name resolution
- Create and manage domain users and Organizational Units (OUs)
- Implement Group Policy controls
- Join a Windows 11 workstation to the domain
- Verify domain authentication and network connectivity

## Lab Environment

### Host System
- Windows 10
- Intel Core Processor
- 16 GB RAM
- 500 GB SSD

### Virtualization
- VMware Workstation

### Domain Controller
- Windows Server 2025
- 1 vCPU
- 4 GB RAM
- 40 GB Storage

### Client Workstation
- Windows 11
- 2 vCPU
- 4 GB RAM
- 70 GB Storage

## Technologies Used

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS Server
- Group Policy Management
- VMware Workstation
- Windows 11
- Windows Networking Tools

## Implementation

### 1. Virtualization Environment

Configured VMware Workstation to host the Windows Server 2025 domain controller and Windows 11 client workstation.

### 2. Windows Server Virtual Machine

Created a Windows Server 2025 virtual machine and allocated the required CPU, memory, and storage resources.

### 3. Initial Server Configuration

Configured the Windows Server environment, including the computer name, Windows Update settings, and remote management.

### 4. Static IP Configuration

Assigned the server a static IPv4 address to provide consistent communication between the domain controller and client workstation.

### 5. Active Directory Domain Services

Installed the Active Directory Domain Services (AD DS) role through Server Manager to provide centralized authentication and directory management.

### 6. Domain Controller Configuration

Promoted the Windows Server to a Domain Controller and created a new Active Directory domain. DNS services were installed as part of the domain configuration.

### 7. DNS Configuration

Verified the domain's Forward Lookup Zone and DNS records using DNS Manager.

### 8. Users and Organizational Units

Created domain users and Organizational Units (OUs) using Active Directory Users and Computers to simulate a structured business environment.

### 9. Group Policy

Created and applied a Group Policy Object (GPO) restricting access to the Windows Control Panel, demonstrating centralized workstation management.

### 10. Windows 11 Client

Created a Windows 11 virtual machine to function as an end-user workstation within the lab environment.

### 11. Domain Join

Successfully joined the Windows 11 workstation to the Active Directory domain, allowing centralized authentication and management.

### 12. Testing and Verification

Logged into the Windows 11 workstation using a domain account and verified network connectivity and DNS resolution using Windows command-line tools.

## Results

Successfully deployed a functional Windows domain environment. The Domain Controller provided centralized authentication, DNS name resolution, and Group Policy management. The Windows 11 workstation successfully joined the domain and authenticated using domain credentials.

## Skills Demonstrated

- Windows Server Administration
- Active Directory Management
- DNS Configuration
- Group Policy Management
- User and OU Administration
- Virtual Machine Deployment
- Windows Networking
- Network Troubleshooting
- Domain Authentication
