## Incident Response

### 1. Detection
The incident could be detected by:
- Suspicious PowerShell execution alert
- Connection to external IP alert
- Phishing domain detection

---

### 2. Triage
The alert was classified as a True Positive due to:
- Malicious PowerShell behavior
- External communication
- Persistence mechanism

Severity: High

---

### 3. Containment
- Isolate the infected machine from the network
- Block the malicious IP (45.77.12.90)
- Block the phishing domain

---

### 4. Eradication
- Remove registry persistence key
- Delete malicious scripts
- Perform full system scan

---

### 5. Recovery
- Restore system to a clean state
- Monitor for suspicious activity

---

### 6. Lessons Learned
- Improve phishing detection rules
- Add PowerShell monitoring alerts
- Conduct user awareness training
