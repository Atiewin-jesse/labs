# DVWA Labs

This directory contains hands-on laboratory exercises conducted using the Damn Vulnerable Web Application (DVWA). Each lab demonstrates the exploitation of a specific web application vulnerability, analyzes the underlying source code, and discusses mitigation techniques based on industry best practices.

## Available Labs

### 01 – Cross-Site Scripting (XSS) & Cross-Site Request Forgery (CSRF)

#### Reflected Cross-Site Scripting (XSS)
Occurs when an application immediately returns unsanitized user input in an HTTP response. An attacker can craft malicious links that execute JavaScript in a victim's browser.

#### Stored Cross-Site Scripting (XSS)
Occurs when malicious input is permanently stored by the application (e.g., in a database) and executed whenever users access the affected page.

#### DOM-Based Cross-Site Scripting (XSS)
A client-side vulnerability where JavaScript manipulates untrusted data in the browser's Document Object Model (DOM), allowing malicious scripts to execute without server-side processing.

#### Cross-Site Request Forgery (CSRF)
Exploits a trusted user's authenticated session by forcing the browser to send unauthorized requests to a web application without the user's knowledge.

---

## Upcoming Labs

### 02 – SQL Injection (SQLi)
Tests how insufficient input validation allows attackers to manipulate SQL queries, potentially leading to unauthorized access, data disclosure, or database modification.

### 03 – Command Injection
Demonstrates how unsanitized user input can be used to execute operating system commands on the server.

### 04 – File Inclusion (LFI/RFI)
Explores vulnerabilities that allow attackers to include unintended local or remote files, potentially exposing sensitive information or executing malicious code.

### 05 – File Upload
Examines insecure file upload mechanisms that may allow attackers to upload and execute malicious files on the server.

### 06 – Brute Force
Investigates password guessing attacks against authentication mechanisms and the importance of account lockout and rate limiting.

### 07 – Authentication & Session Management
Focuses on weaknesses in login systems, session handling, cookies, and authentication controls that could lead to account compromise.

---

Each lab includes:

- Objective
- Lab setup
- Testing methodology
- Source code analysis
- Exploitation steps
- Results and findings
- Mitigation techniques
- References
