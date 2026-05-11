# Windows Event Log Analysis

## Objective

The objective of this project was to practice reviewing Windows security events and documenting activity in a SOC-style format.

## Tools Used

- Windows Event Viewer
- Windows Security Logs
- Sysmon
- Windows endpoint

## What I Practiced

- Navigating Windows Event Viewer
- Reviewing security-related logs
- Identifying failed login activity
- Capturing event evidence
- Writing clear event review notes
- Explaining security activity in plain language

## Security Relevance

Windows log analysis is important for SOC Analyst work because many investigations begin with endpoint activity, authentication events, failed logins, account changes, or suspicious system behavior.

## Example Event Review Format

**Event Type:** Failed Login  
**System:** Windows endpoint  
**Tool Used:** Windows Event Viewer  
**Observation:** A failed login event was generated and reviewed.  
**Security Meaning:** Failed login activity can indicate user error, password issues, brute-force attempts, or unauthorized access attempts.  
**Action Taken:** Captured the event, reviewed the details, and documented the finding.

## What I Learned

This project helped me understand how Windows events can be used to investigate activity on an endpoint and how clear documentation supports security operations.
