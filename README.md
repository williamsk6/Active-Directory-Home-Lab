# Active Directory Home Lab
*Check screenshots file for further visuals*
## Overview
This project demonstrates a virtualized Active Directory environment built using Windows Server and Windows 10. The lab simulates a small enterprise network with centralized authentication, Group Policy enforcement, and domain-joined client machines.

## Lab Architecture
- Hypervisor: VirtualBox
- Domain Controller: Windows Server 2022
- Client Machine: Windows 10 Pro
- Network: Internal Network

https://github.com/williamsk6/Active-Directory-Home-Lab/blob/main/screenshots/Lab%20architecture.png

## Active Directory Setup
- Created Organizational Units (IT, Sales, HR, Finance)
- Added domain users and security groups
- Configured password and account lockout policies

https://github.com/williamsk6/Active-Directory-Home-Lab/blob/main/screenshots/AD%20setup.png

## Group Policy
- Configured desktop screen lock policy
- Applied user-based GPOs to Sales OU
- Verified policy application using gpresult

https://github.com/williamsk6/Active-Directory-Home-Lab/blob/main/screenshots/Password%20policy.png

## Client Machine
- Joined Windows client to domain
- Logged in using domain credentials
- Verified GPO application

https://github.com/williamsk6/Active-Directory-Home-Lab/blob/main/screenshots/domain%20login.png

## What I Learned
- Active Directory user and OU management
- Group Policy creation and troubleshooting
- DNS role in Windows domains
- Client domain join process

## Future Improvements
- PowerShell bulk user creation
- File server with NTFS permissions
- Help desk ticketing integration
