# cybersecurity-virtualization-lab
Built a Windows 11 and Kali Linux virtualization lab using Oracle VirtualBox. Includes system setup, updates, snapshots, and security use cases.
Cybersecurity Virtualization Lab
 Overview

This project demonstrates the setup and management of a virtualization lab using Oracle VirtualBox. The lab includes a Windows 11 virtual machine and a Kali Linux virtual machine to simulate real-world cybersecurity environments.

Technologies Used
Oracle VirtualBox
Windows 11
Kali Linux
Ninite (software deployment)
Linux CLI (apt package manager)

 Lab Objectives
Create and configure virtual machines
Apply system updates and maintain secure environments
Use snapshots to capture and restore system states
Demonstrate VM isolation and compartmentalization

Windows 11 Setup
Installed Windows 11 using ISO
Fully updated system using Windows Update
Created baseline snapshot
Installed applications using Ninite
Reverted snapshot to restore clean system

 Kali Linux Setup
Installed Kali Linux VM
Updated system using:
sudo apt update
sudo apt upgrade -y
Created baseline snapshot

 Key Concepts Learned
Virtualization in cybersecurity
Snapshot and rollback functionality
System isolation for safe testing
Basic Linux package management
Troubleshooting network issues in VMs

Challenges Encountered
Required creating Windows 11 instead of using an existing Windows 10 VM
Resolved Kali Linux network issue by adjusting VirtualBox adapter settings to NAT
Managed system resource usage while running multiple VMs
