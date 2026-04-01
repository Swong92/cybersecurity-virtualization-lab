# Cybersecurity Virtualization Lab

## Overview
This project documents the setup and management of a hands-on virtualization lab using Oracle VirtualBox. The lab includes a Windows 11 virtual machine and a Kali Linux virtual machine to simulate a basic cybersecurity testing environment.

## Skills Demonstrated
- Virtual machine deployment
- Windows 11 installation and updating
- Kali Linux setup and package management
- Snapshot creation and rollback
- Software deployment with Ninite
- VM networking troubleshooting
- System isolation for safe testing

## Key Tasks Completed
### Windows 11
- Created a new Windows 11 VM
- Ran Windows Update until fully patched
- Created a baseline snapshot
- Installed software using Ninite
- Reverted to snapshot to restore a clean state

### Kali Linux
- Configured and launched a Kali Linux VM
- Updated the system using:
  - `sudo apt update`
  - `sudo apt upgrade -y`
- Created a baseline snapshot
- Troubleshot a network connectivity issue by adjusting the adapter to NAT

## What I Learned
This lab helped me better understand how virtualization supports cybersecurity by allowing systems to be isolated, tested, and restored safely. I also gained more confidence working with both Windows and Linux environments and troubleshooting VM configuration issues.
