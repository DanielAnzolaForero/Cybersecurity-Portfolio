## Forensic Analysis and Post-DDoS Hardening Plan (NIST CSF)

DISCLAIMER: This project is a simulation exercise created solely for educational purposes, focused on incident analysis, cyber defense, and proper documentation practices. None of the events, companies, or infrastructures described are real.

Project Summary

This repository documents a comprehensive analysis of a simulated ICMP Flood Distributed Denial of Service (DDoS) incident. The project focuses on:

Determining the Root Cause and Impact of the incident.

Applying the NIST Cybersecurity Framework (CSF) to structure a security posture improvement plan.

Proposing Perimeter Hardening solutions (Firewall, IDS/IPS) and Continuous Monitoring.

## Key Findings

Attack Vector: ICMP Flood (T1498 - MITRE ATT&CK).

Critical Vulnerability: Perimeter firewall without rate-limiting policies.

Conclusion: The service outage was a direct result of a failure in the Protect phase of the security lifecycle.
