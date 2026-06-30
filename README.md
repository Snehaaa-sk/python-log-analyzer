# Python Security Log Analyzer

## Overview

Python Security Log Analyzer is a cybersecurity project that analyzes server log files and detects suspicious activities such as brute-force attacks and directory scanning attempts. The tool generates a security report by identifying failed logins, successful logins, HTTP 404 errors, and potential attack patterns.

---

## Features

- Reads and analyzes log files
- Counts total log entries
- Detects successful login attempts
- Detects failed login attempts
- Counts HTTP 404 errors
- Detects possible brute-force attacks
- Detects possible directory scanning attacks
- Generates a security report
- Saves the report to a text file

---

## Technologies Used

- Python 3
- File Handling
- Dictionaries
- Loops
- Conditional Statements
- String Processing

---

## Project Structure

```
Python-Security-Log-Analyzer/
│
├── log_analyzer.py
├── sample.log
├── security_report.txt
├── README.md
└── requirements.txt
```

---

## How It Works

1. Reads the log file.
2. Processes each log entry.
3. Counts successful and failed login attempts.
4. Detects repeated failed logins from the same IP address.
5. Identifies excessive HTTP 404 errors.
6. Detects possible brute-force attacks.
7. Detects possible directory scanning.
8. Generates and saves a security report.

---

## Sample Output

```
=========== SECURITY REPORT ===========

Total Log Entries : 7

Successful Logins : 1

Failed Logins     : 3

404 Errors        : 3

Suspicious Activities

Brute Force Attack Detected

IP Address : 192.168.1.10

Attempts : 3

Directory Scanning Detected

IP Address : 192.168.1.30

404 Errors : 3

Security report generated successfully!
```

---

## Skills Demonstrated

- Python Programming
- Security Log Analysis
- Threat Detection
- File Handling
- Basic Incident Detection
- Security Reporting

---

## Future Improvements

- Export reports to CSV
- Generate HTML dashboard
- Email alert notifications
- Support Apache and Nginx logs
- Detect SQL Injection patterns
- Detect XSS attempts
- Detect suspicious User-Agents

---

## Learning Outcomes

Through this project, I learned:

- Security log analysis
- Attack pattern identification
- Brute-force detection logic
- Directory scanning detection
- Python file handling
- Security report generation

---

## Author

Sneha Santhosh

Aspiring Cybersecurity & GRC Professional

GitHub:
https://github.com/Snehaaa-sk
