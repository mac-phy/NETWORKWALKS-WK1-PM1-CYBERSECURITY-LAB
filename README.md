# NETWORKWALKS – WEEK 1, PROJECT MODULE 1
## Cybersecurity Lab Setup: Kali Linux & Oracle VirtualBox

### 1. Project Overview

This project documents the setup and configuration of a cybersecurity lab environment using Oracle VirtualBox and Kali Linux as part of the NetworkWalks cybersecurity training programme.

The objective was to establish a functional virtual lab environment for conducting practical cybersecurity exercises, network analysis, and security testing.

### 2. Lab Environment

| Component | Configuration |
|---|---|
| Host Operating System | Windows 11 |
| Virtualization Platform | Oracle VirtualBox |
| Attacking Machine | Kali Linux |
| Network Mode | NAT Network |
| Network Name | NatNetwork |
| Network Subnet | 10.0.0.0/24 |
| Default Gateway | 10.0.0.1 |
| Kali Linux IP | 10.0.0.3/24 |
| DHCP Server | 10.0.0.2 |

### 3. Network Configuration

A NAT Network named `NatNetwork` was configured in VirtualBox using the `10.0.0.0/24` subnet.

Kali Linux obtained the IP address `10.0.0.3/24` through DHCP.

The network configuration provided:
- Internet connectivity.
- DNS resolution.
- Communication with the NAT Network gateway.

### 4. Connectivity Verification

The following commands were used to verify network configuration and connectivity:

```bash
ip -br addr
ip route
ping -c 4 8.8.8.8
ping -c 4 google.com
```

**Results:** Internet connectivity and DNS resolution were successfully verified.

### 5. VirtualBox Integration

The following integration features were configured:

- Bidirectional shared clipboard.
- Bidirectional drag and drop.
- Shared folder between Windows and Kali Linux.
- VirtualBox Guest Additions modules.

### 6. Virtual Machine Snapshot

A snapshot named `WK1-PM1 - Kali Network Configured` was created to preserve the working virtual machine configuration and provide a recovery point.

### 7. Skills Practised

- Virtual machine deployment and configuration.
- Linux command-line operations.
- IP addressing and subnetting.
- DHCP and default gateway configuration.
- Network connectivity troubleshooting.
- DNS verification.
- VirtualBox networking and VM management.

### 8. Tools Used

- Oracle VirtualBox
- Kali Linux
- Windows 11
- Linux terminal
- Network diagnostic# NETWORKWALKS-WK1-PM1-CYBERSECURITY-LAB
Documentation of my hands-on cybersecurity lab setup using Kali Linux and Oracle VirtualBox as part of the NetworkWalks programme.
