# SQL Injection Exploitation Lab

A deliberately vulnerable web application designed to demonstrate SQL Injection (SQLi) attacks in a safe and controlled environment. The project provides a practical platform for learning how SQL injection vulnerabilities occur, how attackers exploit insecure database queries, and how developers can implement effective mitigation techniques.

The lab is intended for students, cybersecurity enthusiasts, ethical hackers, penetration testers, and developers who want hands-on experience understanding one of the most common and impactful web application vulnerabilities.

---

# Overview

SQL Injection remains one of the most well-known web application vulnerabilities. It occurs when user-supplied input is improperly validated or directly incorporated into SQL queries, allowing attackers to manipulate database operations.

This lab recreates realistic vulnerable scenarios to help users understand the complete attack lifecycle—from identifying injectable parameters to exploiting authentication mechanisms and extracting sensitive information.

Each exercise is designed to simulate real-world environments while remaining isolated for educational purposes.

---

# Objectives

- Understand how SQL Injection vulnerabilities occur
- Learn different SQL Injection techniques
- Practice identifying vulnerable parameters
- Explore authentication bypass attacks
- Understand database enumeration concepts
- Learn secure query implementation
- Demonstrate input validation techniques
- Understand parameterized queries
- Improve secure coding practices

---

# Features

## Interactive Vulnerable Web Application

The lab includes intentionally insecure pages that simulate common web application functionality such as login forms, search pages, user lookups, and authentication systems.

These pages are specifically designed to demonstrate insecure SQL query construction.

---

## Multiple SQL Injection Scenarios

The project includes different SQL Injection examples representing various attack surfaces commonly found in web applications.

Example scenarios include:

- Login Authentication
- User Search
- Product Search
- ID-Based Queries
- Search Filters
- Dynamic SQL Queries

---

## Authentication Bypass Demonstration

Users can observe how improperly constructed authentication queries allow attackers to bypass login mechanisms using malicious SQL payloads.

The lab demonstrates why secure authentication should never rely on string concatenation.

---

## Database Query Visualization

The application helps illustrate how user input is combined with SQL queries, making it easier to understand why vulnerable code behaves unexpectedly.

This visualization assists beginners in understanding SQL query execution.

---

## Secure Coding Demonstrations

In addition to vulnerable implementations, the lab explains secure alternatives using defensive programming techniques, allowing learners to compare insecure and secure approaches.

Topics include:

- Prepared Statements
- Parameterized Queries
- Input Validation
- Least Privilege Principle
- Error Handling
- Secure Authentication Logic

---

# Learning Outcomes

By completing this lab, users will gain practical knowledge of:

- SQL query construction
- User input handling
- Authentication mechanisms
- Injection attack methodology
- Database security fundamentals
- Defensive programming
- Secure database communication
- Web application security best practices

---

# Concepts Covered

The lab introduces important SQL Injection concepts including:

- Authentication Bypass
- Boolean-Based Injection
- Error-Based Injection
- Union-Based Injection
- Blind SQL Injection
- Time-Based SQL Injection
- Database Enumeration
- Information Disclosure
- Input Sanitization
- Parameterized Statements

---

# Educational Workflow

The lab follows a structured learning process:

1. Understand the vulnerable application
2. Identify injectable input fields
3. Observe insecure SQL query construction
4. Test SQL Injection payloads
5. Analyze application behavior
6. Understand exploitation techniques
7. Study secure implementations
8. Compare vulnerable and secure code

---

# Secure Development Focus

A major objective of this project is to demonstrate how SQL Injection vulnerabilities can be prevented using industry-standard secure coding practices.

Recommended defensive techniques include:

- Prepared Statements
- Parameterized Queries
- ORM Frameworks
- Server-Side Validation
- Input Sanitization
- Principle of Least Privilege
- Proper Error Handling
- Secure Authentication Design

---

# Target Audience

This project is suitable for:

- Cybersecurity Students
- Ethical Hackers
- Penetration Testers
- Web Developers
- Security Researchers
- Capture The Flag (CTF) Participants
- Security Training Programs
- Educational Institutions

---

# Educational Purpose

This lab is designed to bridge the gap between theoretical knowledge and practical understanding of SQL Injection vulnerabilities. By experimenting within a controlled environment, learners can safely observe the impact of insecure database interactions while developing secure coding habits.

The project encourages responsible security education and emphasizes the importance of protecting web applications against injection attacks.

---

# Usage

Start a local HTTP server from the project directory:

```bash
cd BobbyTables
python -m http.server
```

Then open the following URL in your browser:

```
http://localhost:8000/bobbytables.html
```

---

# Disclaimer

This project is intentionally vulnerable and is provided strictly for educational purposes, security research, and authorized training environments. It should only be used in isolated lab environments. Unauthorized testing against systems you do not own or have explicit permission to assess may violate applicable laws and regulations.
