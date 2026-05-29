# Week 4 Lab Setup

## Objective
Create an isolated red team lab environment for Week 4 activities.

## Environment

### Host Machine
- Kali Linux

### Virtualization
- Oracle VirtualBox

### Guest Machine
- Windows 10

## Network Configuration

### Host
IP Address: 192.168.56.1

### Windows VM
IP Address: 192.168.56.101

### Network Type
Host-Only Adapter (vboxnet0)

## Verification

### Windows to Kali

Command:
ping 192.168.56.1

Result:
Success (4/4 packets received)

### Kali to Windows

Command:
ping -c 4 192.168.56.101

Result:
Success (4/4 packets received)

## Status

Lab environment successfully configured and validated.
