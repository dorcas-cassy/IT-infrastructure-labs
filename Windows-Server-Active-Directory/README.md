# Active Directory Setup Lab

## Overview
This project documents my hands-on Windows Server home lab where I installed and configured Active Directory Domain Services (AD DS) using Oracle VirtualBox.

The goal of this lab is to demonstrate practical IT infrastructure skills including:

- Windows Server installation
- Virtual machine configuration
- Server Manager setup
- Active Directory deployment

## Objective
Install Windows Server and promote it to a Domain Controller using Active Directory Domain Services.

## Lab Environment

Hypervisor: Oracle VirtualBox  
Operating System: Windows Server Evaluation ISO  
VM Name: WinServer01  
Role: Domain Controller

## Step-by-Step Process

### 1️ Virtual Machine Creation
- Created a new VM in Oracle VirtualBox
- Allocated RAM and CPU resources
- Attached Windows Server ISO image
- Configured storage controller

### 2️ Windows Server Installation
- Booted from ISO file
- Installed Windows Server
- Logged in using Administrator account

### 3️ Initial Server Configuration
- Opened Server Manager dashboard
- Verified Local Server settings
- Prepared system for role installation

### 4️ Installing Active Directory Domain Services
- Navigated to **Add Roles and Features**
- Selected Role-based installation
- Chose Active Directory Domain Services
- Installed required features

### 5️ Promotion to Domain Controller
- Promoted server to Domain Controller
- Configured new forest
- Completed AD DS setup wizard

## Screenshots
Screenshots included show:

- VirtualBox configuration
- Windows Server login
- Server Manager dashboard
- AD DS installation progress

## Skills Demonstrated
- Windows Server Administration
- Active Directory Setup
- Virtualization (VirtualBox)
- System Configuration
- IT Infrastructure Fundamentals

## Progress
✔ Windows Server Installed  
✔ Server Manager Configured  
✔ AD DS Role Installed  
