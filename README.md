# Cyber Security Internship - Task 3

# Perform a Basic Vulnerability Scan on Your PC

## Objective

The objective of this task was to perform a basic vulnerability assessment on my local computer using Nessus Essentials. The scan identified security issues, categorized them based on severity, and provided remediation recommendations.

---

## Tools Used

- Nessus Essentials
- Windows 11
- GitHub

---

## Procedure

### Step 1: Install Nessus Essentials

Downloaded and installed Nessus Essentials from the official Tenable website.

---

### Step 2: Activate Nessus

- Created a Tenable account.
- Activated Nessus Essentials using the activation code.
- Waited for plugin download and compilation.

---

### Step 3: Identify Local IP Address

Executed:

```
ipconfig
```

Local IPv4 Address:

```
192.168.x.x
```

(IP address masked for privacy.)

---

### Step 4: Create a Basic Network Scan

Created a new scan using the **Basic Network Scan** template.

Target:

```
192.168.x.x
```

---

### Step 5: Run the Scan

Started the vulnerability scan and waited until completion.

---

## Scan Summary

| Item | Result |
|------|--------|
| Scanner | Nessus Essentials |
| Scan Type | Basic Network Scan |
| Hosts Scanned | 1 |
| Scan Status | Completed |
| Vulnerability Plugins Reported | 26 |
| Scan Duration | Approximately 14 minutes |

---

## Vulnerability Summary

The scan detected informational findings along with configuration-related issues. No critical vulnerabilities were identified during the assessment.

The detected issues mainly consisted of:

- Informational service detection
- Network service enumeration
- Security configuration observations
- System fingerprinting information

---

## Risk Assessment

Potential risks include:

- Exposure of unnecessary network services
- Information disclosure
- Weak security configurations
- Increased attack surface

---

## Recommended Mitigations

- Keep Windows updated.
- Enable Windows Firewall.
- Disable unused services.
- Keep antivirus definitions updated.
- Remove unnecessary open ports.
- Install security updates regularly.
- Use strong authentication.
- Perform periodic vulnerability scans.

---

# Outcome

Successfully performed a vulnerability assessment using Nessus Essentials, identified security findings, reviewed the scan report, understood vulnerability severity, and learned basic remediation techniques.

---

**Note:** Local IP addresses have been masked to protect network privacy.
