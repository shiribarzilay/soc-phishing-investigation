## Investigation

### 1. Initial Access
The attack started with a phishing email sent to the employee.
The email contained a malicious link that mimicked a legitimate PayPal domain.

---

### 2. Execution
After clicking the link, a PowerShell command was executed.
The command used suspicious flags such as -nop and hidden window.
It downloaded a script from an external IP address.

---

### 3. Persistence
A registry key was added under:
HKCU\Software\Microsoft\Windows\CurrentVersion\Run
This indicates an attempt to maintain persistence.

---

### 4. Network Activity
The infected machine communicated with an external IP (45.77.12.90) over HTTP.
A suspicious domain was also queried.

---

### 5. Conclusion
The system was compromised.

Indicators:
- Phishing email
- Malicious PowerShell execution
- Persistence mechanism
- External network communication
