# Malicious IP List

This repository shares a list of malicious IP addresses confirmed by our company's internal security monitoring and analysis.  
The goal is to help other security teams, researchers, and system administrators block or monitor these IPs to improve overall cyber defense.

## Purpose

- Provide up-to-date and verified IP addresses associated with malicious activity.
- Enable quick integration into firewalls, intrusion prevention systems (IPS), and threat intelligence platforms.
- Promote collaborative cyber threat mitigation by sharing reliable intelligence.

## Data Sources

The IP addresses in this repository are:
- Collected from our company's production systems and security infrastructure.
- Verified through internal incident response and log analysis.
- Regularly reviewed and updated to ensure accuracy.

## Usage

1. Download the latest IP list from the repository.
2. Import the list into your firewall, IPS, or SIEM system.
3. Schedule regular updates to ensure your block list remains current.

**Example (Linux `curl`):**
```bash
curl -O https://raw.githubusercontent.com/DigitalChosun/cyber-threat-ips/refs/heads/main/malicious_ips.txt
