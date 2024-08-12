# Powershell-File-Integrity-Monitor'

## Project Overview
This project illustrates the creation of a File Integrity Monitor (FIM) using basic coding principles and hashing techniques. The primary purpose is to safeguard file integrity by identifying any unauthorized alterations. It highlights the practical application of cryptographic hashing for monitoring and preserving the integrity of important files.

## Features
- Cryptographic Hashing: Utilizes cryptographic hashing methods (like SHA-256) to produce unique hash values for files.
- Initial Baseline: Generates and stores hash values of files to establish an initial reference state.
- Regular Integrity Checks: Continuously compares current file hash values with the initial baseline to detect changes.
- Notification System: Alerts users through notifications or logs when inconsistencies are discovered, suggesting possible unauthorized modifications.
- User Interface: Offers a straightforward user interface for adding files to the monitoring list and initiating integrity checks.
- PowerShell-Based: Developed in PowerShell, making use of its scripting features and compatibility with Windows systems.

## Project Components
- Hash Generation Function: A function that takes a file path and outputs its hash value based on the chosen hashing algorithm.
- Baseline Management: Functions for creating, updating, and maintaining a record of hash values for all monitored files.
- Integrity Verification: A function that compares current file hash values with the baseline and flags any discrepancies.
- User Guidance: Simple prompts and feedback to assist users in setting up and operating the FIM.

## Use Cases
- Security Monitoring: Identifies unauthorized modifications to critical system files, configurations, or application binaries.
- Regulatory Compliance: Assists in meeting security requirements that mandate file integrity monitoring.
- Data Protection: Helps maintain the integrity of sensitive data by regularly verifying its consistency.
