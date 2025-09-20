# FUTURE_CS_02 – Security Alert Monitoring & Incident Response

**Intern:** Rav Tej  
**Internship:** Cyber Security Internship – Future Interns  

## Summary of Findings
- Detected multiple SSH brute force attempts (17 failed logins).
- Identified attacker IPs responsible for repeated login attempts.
- Confirmed successful root login from attacker IPs (system compromise).
- Severity: Critical — unauthorized administrative access obtained.

## Deliverables
- `incident_report_task2.pdf` — full incident report  
- `incident_report_task2.docx` — editable version  
- `auth.log` — analyzed Linux SSH authentication log  
- `screenshots/` — evidence from Splunk queries  

## Tools Used
- Splunk Enterprise (log ingestion, search, reporting)  
- Regex field extraction (`rex`) for attacker IPs  
- SOC-style incident response methodology  
