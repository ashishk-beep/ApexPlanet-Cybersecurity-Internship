# Cross-Site Scripting (XSS) – DVWA

## Objective
To exploit Stored and Reflected XSS vulnerabilities and demonstrate prevention methods.

---

## What is XSS?
Cross-Site Scripting allows attackers to inject malicious JavaScript into web applications.

---

# Stored XSS

## Steps
1. Go to DVWA → XSS (Stored)
2. Enter:

```html
<script>alert('Stored XSS')</script>

---

Reflected XSS
Steps
1.	Go to DVWA → XSS (Reflected)
2.	Enter: <script>alert('Reflected XSS')</script>
3.	Click Submit
4.	Alert executes immediately

