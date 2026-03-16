
# Lab Architecture

This lab environment simulates a hybrid enterprise infrastructure combining on-premises Active Directory with Microsoft Azure cloud services.

## Environment Components

### On-Premises Lab

- Windows Server 2022 Domain Controller
- Active Directory Domain Services
- DNS Server
- Group Policy Management

### Client Systems

- Windows Workstation joined to the domain

### Azure Cloud Environment

- Azure Virtual Machines
- Virtual Network
- Network Security Groups
- Public IP Addresses
- Managed Disks

### Identity Platform

Microsoft Entra ID (Azure Active Directory)

## Azure Resource Details

Resource Group: IT-Lab-01  
Region: France Central

Virtual Machines

- IT-WinLab-01 (Windows Server)
- IT-Lab-VM01 (Linux VM)

## Networking

Virtual Network: vnet-francecentral  
Subnet: snet-francecentral-1

Security controls include Network Security Groups to control inbound and outbound traffic.

## Cost Optimization Measures

To reduce cloud costs in the lab environment:

- Virtual machines are **deallocated when not in use**
- Premium disks replaced with **Standard SSD**
- Unused **public IP addresses removed**
- Azure Cost Management used for monitoring

This environment allows practical experience with identity management, cloud administration, and security monitoring.
