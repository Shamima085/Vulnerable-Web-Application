# Vulnerable Web Application Security Assessment

## Project Overview

This project presents a security assessment of a deliberately vulnerable web application.

The assessment combines manual penetration testing and static code analysis to identify common web application security weaknesses and provide remediation recommendations.

---

## Vulnerabilities Identified

The project covers several OWASP-related security issues, including:

- Broken Authentication
- Cross-Site Scripting (XSS)
- Broken Access Control
- Sensitive Data Exposure
- Security Misconfiguration
- Insecure Deserialization
- SQL Injection

---

## Security Testing

The application was tested for scenarios such as:

- Brute-force authentication attacks
- Stored and DOM-based XSS
- Unauthorized access to user data
- Manipulation of authentication data
- SQL injection and UNION-based SQL injection
- Exposure of sensitive information

Each finding includes the vulnerability, severity, evidence, and recommended remediation.

---

## Static Code Analysis

The source code was also reviewed for security issues such as:

- Insecure MD5 password hashing
- Unsafe `mark_safe()` usage
- String-based SQL query construction
- Hardcoded credentials
- Insecure random number generation
- Unsafe XML parsing
- Potential command execution risks

The detailed scan results are available in `CodeScanReport.txt`.

---

## Security Recommendations

Key recommendations include:

- Multi-Factor Authentication
- Strong password hashing
- Login rate limiting
- Input validation and sanitization
- Output encoding
- Parameterized SQL queries
- Strong access-control validation
- Encryption of sensitive data
- Removal of hardcoded credentials
- Improved logging and monitoring

---

## Security Report

For the complete vulnerability analysis, screenshots, exploitation steps, and remediation guidance, see:

[View Security Assessment Report](webappanalysis.pdf)

---

## Author

**Shamima Sultana**