# Cybersecurity Internship - Task 1 Report

## Task: Local Network Port Scanning

### Objective:
Perform a scan on the local network to identify open ports using Nmap, and analyze the services exposed.

### Steps Taken:
- Identified IP range using `ipconfig` (Windows).
- Ran TCP SYN scan using `nmap -sS 192.168.1.0/24`.
- Found several devices with open ports.
- Noted the services and ports in `scan_results.txt`.

### Observations:
- Multiple hosts had port 80 (HTTP) and 22 (SSH) open.
- Indicates potential service exposure.
- Some ports linked to unknown services, requiring further analysis.

### Tools Used:
- Nmap (Port scanning)
- Wireshark (Optional packet inspection)

### Conclusion:
This exercise demonstrates the importance of securing open ports. Unused ports must be closed and firewalls configured properly to prevent potential exploits.

### Timestamp:
2025-06-23 16:03:21