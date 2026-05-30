# Windows Security Observations

## System Log Analysis

Location:
Windows Logs -> System

Observations:

- Event ID 7040 observed.
- Background Intelligent Transfer Service (BITS) startup type changed.
- Service Control Manager events present.
- System logging functioning correctly.
- Warning and Information level events visible.

Relevant Event IDs:

- 7040 - Service configuration change
- 7001 - Service startup dependency
- 10016 - DCOM permission related warning

Learning:

System logs provide evidence of service execution, configuration changes and operating system activities useful during investigations.

## Environment

Host: Kali Linux
Target: Windows 10 VM

## Event Viewer Analysis

Location:
Windows Logs -> Security

Observations:

- Security auditing enabled.
- Event ID 5379 observed.
- Credential Manager credential access recorded.
- Windows Security log contains authentication and auditing events.

## Network Information

Windows IP:
192.168.56.101

Connectivity Test:

- Windows -> Kali successful
- Kali -> Windows successful

## Security Controls Reviewed

- Windows Defender Firewall
- ICMP Echo Rules
- Security Event Logging
- Host-only Network Configuration

## Learning Outcome

Learned how Windows logs security-relevant events and how network communication can be monitored in a lab environment.
