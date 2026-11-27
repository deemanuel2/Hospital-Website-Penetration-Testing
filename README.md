# Hospital Website Penetration Testing

<p align="left">
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux"/>
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge" alt="Nmap"/>
  <img src="https://img.shields.io/badge/WhatWeb-2C3E50?style=for-the-badge" alt="WhatWeb"/>
  <img src="https://img.shields.io/badge/WHOIS-34495E?style=for-the-badge" alt="WHOIS"/>
  <img src="https://img.shields.io/badge/DNSRecon-34495E?style=for-the-badge" alt="DNSRecon"/>
  <img src="https://img.shields.io/badge/cURL-073551?style=for-the-badge&logo=curl&logoColor=white" alt="cURL"/>
  <img src="https://img.shields.io/badge/Wafw00f-6A5ACD?style=for-the-badge" alt="Wafw00f"/>
  <img src="https://img.shields.io/badge/John%20the%20Ripper-444444?style=for-the-badge" alt="John the Ripper"/>
</p>

## Project Overview

This project documents a practical black-box penetration testing assessment of a hospital website, conducted as part of my cybersecurity internship training at Networkwalks.

The assessment focused on identifying potential security weaknesses through footprinting, reconnaissance, network scanning and web application testing.

## Objectives

- Gather information about the target domain and its infrastructure.
- Identify exposed network ports and services.
- Examine website directories and publicly accessible resources.
- Test the website's login mechanism for SQL injection vulnerabilities.
- Analyse password-protected PDF files.
- Assess potential security risks and provide recommendations.

## Tools Used

- Kali Linux
- WHOIS
- WhatWeb
- Nslookup
- cURL
- Wafw00f
- DNSRecon
- Nmap
- PDF Hash Extractor
- Networkworks Hash Calculator
- Networkworks Password Cracker

## Techniques and Resources Used

- **robots.txt:** Examined crawler instructions to identify website directory paths.
- **SQL Injection:** Tested the login form using comment-based SQL injection to identify an authentication bypass.

## Key Findings

- Identified the website's hosting and DNS information.
- Discovered 10 open TCP ports.
- Identified directory paths through `robots.txt`.
- Demonstrated an SQL injection authentication bypass.
- Gained access to three password-protected PDF lab reports.

## Recommendations

The assessment highlighted the need for stronger authentication, secure database queries, proper access controls, secure configuration of exposed services and better protection of confidential documents.

## Project Report

The complete penetration testing report, including methodology, findings, evidence, risk analysis and recommendations, is available in the PDF file in this repository.

**File:** `Penetration-Testing-Report.doc`

## Disclaimer

This project was conducted as part of an authorised cybersecurity training exercise for educational purposes. The findings are documented to demonstrate practical security testing techniques and the importance of identifying and addressing security vulnerabilities.
