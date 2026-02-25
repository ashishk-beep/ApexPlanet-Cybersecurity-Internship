
# File Inclusion Attacks – DVWA

## Objective
To exploit Local and Remote File Inclusion vulnerabilities.

---

# Local File Inclusion (LFI)

## Payload Used
../../../../etc/passwd


## Steps
1. Go to DVWA → File Inclusion.
2. Modify URL parameter.
3. Sensitive system file is displayed.

(Screenshot Here)

---

# Remote File Inclusion (RFI)

## Example Payload
Allows execution of external code.

---

## Impact
- Remote Code Execution
- System compromise
- Data leakage

---

## Mitigation

1. Disable `allow_url_include`
2. Validate file paths
3. Use whitelist of allowed files

---

## Conclusion
File Inclusion vulnerabilities can lead to full server compromise.
