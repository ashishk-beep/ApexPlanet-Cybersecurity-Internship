# SQL Injection (SQLi) – DVWA

## Objective
To identify and exploit SQL Injection vulnerability in DVWA and demonstrate mitigation.

---

## What is SQL Injection?
SQL Injection occurs when user input is directly included in SQL queries without validation, allowing attackers to manipulate database queries.

---

## Lab Setup
- Attacker: Kali Linux
- Target: DVWA
- Security Level: Low

---

## Exploitation Steps

1. Open DVWA → SQL Injection.
2. Enter payload: 1' OR '1'='1
3. Click Submit.
4. All users from database are displayed.

---

## Extracting Data

Payload Used: 1' UNION SELECT user, password FROM users 

Result:
- Extracted usernames and hashed passwords.

