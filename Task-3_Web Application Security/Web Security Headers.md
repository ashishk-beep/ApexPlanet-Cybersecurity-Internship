# Web Security Headers

## Objective
To analyze and improve HTTP security headers.

---

## Testing

1. Visit https://securityheaders.com
2. Enter test site URL.
3. Observe missing headers.

(Screenshot Here)

---

## Important Security Headers

### 1. X-Frame-Options
Prevents clickjacking.

### 2. X-Content-Type-Options
Prevents MIME sniffing.

### 3. Content-Security-Policy
Prevents XSS.

### 4. Strict-Transport-Security (HSTS)

---

## Apache Configuration Example

Edit: /etc/apache2/conf-available/security.conf

Header always set X-Frame-Options "DENY"
Header always set X-Content-Type-Options "nosniff"
Header always set X-XSS-Protection "1; mode=block"

Restart Apache: sudo systemctl restart apache2
