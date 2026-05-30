# CYART Red Teaming Week 4 Lab Environment Report

## Objective

Build a controlled Windows lab environment for adversary emulation and security monitoring.

---

## Lab Components

### Host Machine

- Kali Linux
- VirtualBox 7.x

### Guest Machine

- Windows 10 x64
- Memory: 4240 MB
- CPUs: 2
- Disk: 100 GB

---

## Network Configuration

### VirtualBox Host Only Network

Network:

192.168.56.0/24

### Host IP

192.168.56.1

### Windows VM

192.168.56.101

---

## Connectivity Verification

### Windows to Kali

Successful ICMP communication verified.

### Kali to Windows

Successful ICMP communication verified.

---

## Security Monitoring

### Event Viewer

Logs Reviewed:

- Security
- System

### Notable Events

Security:

- Event ID 5379

System:

- Event ID 7040
- Event ID 7001
- Event ID 10016

---

## Evidence Collected

### Screenshots

- Windows Desktop
- VM Configuration
- Host Only Network
- Security Log
- System Log
- Network Connectivity

---

## Snapshot

Snapshot Created:

Fresh Windows 10 baseline before Week 4 labs

Purpose:

Restore clean state before adversary simulation.

---

## Learning Outcomes

- Virtual lab deployment
- Windows event log analysis
- Host-only networking
- Virtual machine management
- Evidence collection and documentation

---

## Status

Lab environment successfully deployed and validated.
