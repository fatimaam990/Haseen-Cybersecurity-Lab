# Haseen Cybersecurity Lab

## Overview
This project demonstrates a basic penetration testing workflow in a controlled lab environment. It includes reconnaissance, vulnerability analysis, and reporting automation.

## Tools Used
- Nmap
- Burp Suite
- DVWA (Damn Vulnerable Web Application)
- Python

## Methodology
- Network reconnaissance and service enumeration using Nmap
- Web application testing using Burp Suite
- SQL Injection testing in DVWA environment
- Security findings documentation and classification

## Findings Summary

| Finding | Severity |
|--------|----------|
| Open HTTP Service (Apache) | Low |
| Missing HttpOnly Cookie Flag | Medium |
| SQL Injection Vulnerability | High |

## Recommendations
- Use parameterized SQL queries
- Enable HttpOnly cookie protection
- Reduce exposed services and hide server version
- Perform periodic vulnerability assessments

## Automation
A Python script (`report.py`) was developed to automate basic penetration testing reporting.

## Author
Cybersecurity & Network Systems Trainee
