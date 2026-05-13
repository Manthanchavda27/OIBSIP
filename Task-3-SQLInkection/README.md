# Task 3 - SQL Injection on DVWA (Low Security)

## Objective
The objective of this task is to demonstrate an SQL Injection vulnerability using DVWA (Damn Vulnerable Web Application) configured with low security settings.

---

## Tools Used
- DVWA
- Kali Linux
- Apache2
- MariaDB
- PHP

---

## Steps Performed

### 1. Installed DVWA and Required Services
Apache, MariaDB, and PHP were installed and configured.

---

### 2. Configured DVWA
DVWA was cloned into the Apache web directory and database configuration was completed.

---

### 3. Set Security Level to Low
The DVWA security level was changed to LOW to allow demonstration of SQL Injection vulnerabilities.

---

### 4. Performed SQL Injection
The following payload was used:

```sql
1' OR '1'='1
```

This payload manipulated the SQL query logic and returned all user records.

---

## Vulnerability Explanation

SQL Injection occurs when user input is not properly sanitized before being used in SQL queries. Attackers can manipulate database queries and gain unauthorized access to sensitive information.

---

## Screenshots
Screenshots of:
- DVWA setup
- Security configuration
- SQL Injection payload
- Exploitation result

are included in the screenshots folder.

---

## Conclusion

This task demonstrated how insecure input validation can lead to SQL Injection vulnerabilities. Proper sanitization, prepared statements, and parameterized queries are important defenses against SQL Injection attacks.
