# Lab Setup Log

Date: 30-05-2026

## Activities Performed

1. Installed and configured Oracle VirtualBox.
2. Created Windows 10 virtual machine.
3. Allocated:
   - RAM: 4240 MB
   - CPU: 2 Cores
   - Disk: 100 GB

4. Created Host-Only Network:
   - Name: vboxnet0
   - Network: 192.168.56.0/24

5. Configured Windows VM network adapter:
   - Host-Only Adapter
   - vboxnet0

6. Verified Connectivity:

Windows → Kali

Command:
ping 192.168.56.1

Result:
Success

Kali → Windows

Command:
ping -c 4 192.168.56.101

Result:
Success

## Outcome

Lab environment prepared successfully for Week 4 Red Team exercises.
