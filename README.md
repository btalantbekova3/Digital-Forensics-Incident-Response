# Digital-Forensics-Incident-Response
As part of Georgia Tech's CS 3235 Information Security course, we acted as digital forensic investigators analyzing the computer of a fictional suspect named George Burdell.

George was suspected of stealing confidential company information and attempting to hide evidence of his activities. Using a forensic disk image, we conducted a full investigation to recover evidence, analyze suspicious activity, and determine whether sufficient evidence existed to support a criminal case.

## Dead Analysis

A major part of this investigation involved **dead analysis**, a forensic technique where digital evidence is examined without booting or interacting with the original operating system. This approach preserves forensic integrity and prevents evidence from being altered during the investigation.

The suspect had configured the system to wipe itself after multiple failed password attempts. To safely recover evidence, we analyzed a forensic image of the disk rather than interacting with the live system.

Using the Autopsy forensic platform, we examined files, deleted artifacts, browser history, system logs, user activity, and application data. Through this process, we reconstructed timelines and identified artifacts relevant to the investigation.

## Tools Used

- Autopsy
- Wireshark
- Linux
- Docker
- John the Ripper
- Steghide
- Ghidra
- Audacity

## Investigation Activities

### Digital Forensics
- Examined disk images and file systems
- Recovered deleted and hidden files
- Investigated browser history and system logs
- Collected and documented digital evidence

### Password Cracking
- Cracked passwords protecting files and archives
- Used recovered credentials to access additional evidence

### SQL Injection Testing
- Identified and exploited SQL injection vulnerabilities in investigation-related web applications
- Retrieved information that assisted the investigation

### Steganography Analysis
- Extracted hidden information from image files using Steghide

### Network Analysis
- Investigated packet captures and network artifacts using Wireshark

### Reverse Engineering
- Analyzed suspicious executable files using Ghidra to recover hidden information and credentials

## Key Findings

During the investigation, we uncovered evidence showing that the suspect:

- Stole confidential company information
- Created fake identities
- Used offensive security and hacking tools
- Attempted to permanently delete evidence
- Accessed external systems and services
- Tried to conceal his activities

Based on the collected evidence, we concluded that George was responsible for the theft of company information and took deliberate actions to hide his involvement.

## Skills Demonstrated

- Digital Forensics
- Incident Response
- Evidence Collection
- File Recovery
- Log Analysis
- Network Traffic Analysis
- Password Cracking
- SQL Injection Testing
- Reverse Engineering
- Steganography
- Linux Investigation
- Technical Reporting
