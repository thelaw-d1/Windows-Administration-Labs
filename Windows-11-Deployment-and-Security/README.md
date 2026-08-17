# Windows 11 Deployment and Security Configuration

## Project Overview

This project demonstrates the installation and configuration of Windows 11 Pro in a VMware virtual environment. The system was prepared for secure, functional use through operating system deployment, account configuration, system updates, BitLocker encryption, and verification.

## Environment

- VMware Workstation
- Windows 11 Pro
- 64 GB virtual disk
- 4 GB RAM
- 2 virtual processors

## Tasks Completed

- Created and configured a Windows 11 virtual machine
- Mounted the Windows 11 ISO and completed a clean installation
- Renamed the computer for easier identification
- Configured the private network profile
- Checked for and initiated Windows security updates
- Created a standard local user account to support least privilege
- Enabled BitLocker drive encryption
- Used PowerShell and `systeminfo` to verify the system configuration

## Security Features

### Least Privilege

A standard local user account was created separately from the administrator account. This reduces the risk of unauthorized or accidental system changes.

### BitLocker Encryption

BitLocker was enabled on the operating system drive to protect stored data from unauthorized access.

### System Updates

Windows Update was used to identify and install current security, Defender, and operating system updates.

## Troubleshooting

During deployment, I resolved issues involving the Windows 11 ISO configuration and BitLocker detecting removable installation media. I reviewed the virtual machine settings, disconnected the installation media, and successfully completed the security configuration.

## Skills Demonstrated

- Windows 11 deployment
- VMware configuration
- Local user administration
- Windows security configuration
- BitLocker encryption
- PowerShell verification
- Technical troubleshooting
- System documentation

## Key Takeaway

This project strengthened my understanding of deploying, securing, and verifying a Windows workstation in a virtual enterprise environment.
