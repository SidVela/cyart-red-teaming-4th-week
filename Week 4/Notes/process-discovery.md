# Process Discovery

## Technique

T1057 - Process Discovery

## Commands

tasklist

tasklist | findstr explorer

tasklist | findstr svchost

## Purpose

Attackers enumerate running processes to:

- Identify security products
- Find user applications
- Locate privileged processes
- Understand host activity

## Detection Opportunities

- Monitor cmd.exe spawning tasklist.exe
- Monitor unusual process enumeration
- Correlate with user activity

## Learning Outcome

Process enumeration provides valuable information to attackers during reconnaissance and post-compromise activities.
