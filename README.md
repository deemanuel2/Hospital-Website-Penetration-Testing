# Hospital Website Penetration Testing

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

**File:** `Penetration-Testing-Report.pdf`

## Disclaimer

This project was conducted as part of an authorised cybersecurity training exercise for educational purposes. The findings are documented to demonstrate practical security testing techniques and the importance of identifying and addressing security vulnerabilities.
