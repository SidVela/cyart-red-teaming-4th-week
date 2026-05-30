# Cloud Attack Lab

## Lab Information

Date: 30-05-2026

## Objective

Document cloud security concepts, common misconfigurations, and defensive analysis techniques.

## Cloud Asset Log

| Asset ID | Service | Misconfiguration | Notes |
|-----------|----------|-----------------|---------|
| AID001 | S3 Bucket | Public Read Access | Example documentation entry |

## IAM Review

| Account Type | Risk Identified | Notes |
|-------------|----------------|-------|
| IAM User | Excessive Permissions | Principle of Least Privilege recommended |

## MITRE ATT&CK Mapping

| Technique ID | Description |
|-------------|-------------|
| T1580 | Cloud Infrastructure Discovery |
| T1078.004 | Valid Accounts: Cloud Accounts |
| T1537 | Transfer Data to Cloud Account |

## Observations

- Cloud security depends heavily on IAM configuration.
- Storage permissions should be regularly audited.
- MFA should be enabled for privileged accounts.

## Learning Outcome

Understanding cloud attack paths and defensive security controls.
