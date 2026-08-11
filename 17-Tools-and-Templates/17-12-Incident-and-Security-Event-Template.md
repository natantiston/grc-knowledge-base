**17.12 Incident and Security Event Templates**

**Part 1 – Security Incident Report Template**

A Security Incident Report Template is a structured GRC tool used to formally document cybersecurity incidents from initial detection through investigation, containment, recovery, and closure. It provides a consistent method for recording what happened, when it happened, what systems or information were affected, how the incident was handled, and what corrective actions are required.

The purpose of the Security Incident Report Template is to ensure that security incidents are documented consistently and that important information is not lost during the incident lifecycle. It also provides an auditable record that can be used by cybersecurity teams, GRC professionals, management, internal auditors, regulators, legal teams, and other authorized stakeholders.

A security incident report should not be limited to major cyberattacks. Organizations should also document incidents involving suspicious activity, unauthorized access, malware, phishing, data exposure, policy violations, lost devices, compromised credentials, system vulnerabilities, and other events that may affect confidentiality, integrity, or availability.

A practical security incident management process can be represented as:

```text
Security Event Detected
        ↓
Initial Triage
        ↓
Incident Determination
        ↓
Incident Classification
        ↓
Severity Assessment
        ↓
Investigation
        ↓
Containment
        ↓
Eradication
        ↓
Recovery
        ↓
Post-Incident Review
        ↓
Corrective Actions
        ↓
Incident Closure
```

A practical Security Incident Report Template can contain:

```text
SECURITY INCIDENT REPORT

Incident ID:

Incident Title:

Date and Time Detected:

Date and Time Occurred:

Date and Time Reported:

Incident Reporter:

Incident Owner:

Incident Response Team:

Business Owner:

Affected Department:

Affected System / Application:

Affected Asset:

Incident Category:

Incident Type:

Incident Source:

Initial Description:

Detailed Incident Description:

Detection Method:

Initial Indicators:

Affected Users:

Affected Systems:

Affected Data:

Data Classification:

Confidentiality Impact:

Integrity Impact:

Availability Impact:

Initial Severity:

Business Impact:

Security Impact:

Regulatory Impact:

Initial Risk:

Investigation Summary:

Root Cause:

Threat Actor:

Attack Vector:

Indicators of Compromise:

Containment Actions:

Eradication Actions:

Recovery Actions:

Evidence Collected:

Third Parties Involved:

Communication / Escalation:

Regulatory Notification:

Customer / User Notification:

Corrective Actions:

Action Owner:

Target Date:

Lessons Learned:

Residual Risk:

Management Decision:

Closure Approval:

Closure Date:

Incident Status:
```

The first step is to assign a unique **Incident ID**.

For example:

```text
INC-2026-001
INC-2026-002
INC-2026-003
```

The Incident ID should remain associated with the incident throughout its entire lifecycle.

It can also be used to connect the incident with other GRC records.

For example:

```text
Incident:
INC-2026-145

Risk:
RSK-2026-034

Breach Assessment:
BRT-2026-021

Corrective Action:
CAPA-2026-018

Audit Finding:
AF-2026-009
```

This creates traceability between incident management, risk management, privacy, corrective actions, and audit activities.

The report should include an **Incident Title** that provides a concise description.

For example:

```text
Incident Title:
Compromised Customer Service Account
```

Or:

```text
Incident Title:
Ransomware Detected on File Server
```

Or:

```text
Incident Title:
Unauthorized Access to Cloud Storage
```

The incident title should be descriptive enough to allow management and analysts to understand the general nature of the incident without reviewing the entire report.

The report should record the **date and time the incident occurred**, where this information is known.

For example:

```text
Date and Time Occurred:
10 August 2026 – 02:15
```

If the exact time is unknown, the report should record the estimated period.

For example:

```text
Estimated Occurrence:
Between 01:00 and 03:00
```

The report should separately record the **date and time the incident was detected**.

For example:

```text
Date and Time Detected:
10 August 2026 – 08:42
```

This distinction is important because the difference between occurrence and detection can help the organization measure its detection capability.

For example:

```text
Incident Occurred:
02:15

Incident Detected:
08:42

Estimated Detection Delay:
6 hours 27 minutes
```

The report should identify the **incident reporter**.

For example:

```text
Incident Reporter:
SOC Analyst
```

The reporter may be:

```text
Employee
Security Analyst
System Administrator
Customer
Vendor
Automated Security Tool
External Researcher
Law Enforcement
```

The report should identify the **incident owner**.

For example:

```text
Incident Owner:
Incident Response Manager
```

The incident owner is responsible for coordinating the investigation and ensuring that required actions are completed.

The report should identify the **incident response team**.

For example:

```text
SOC
Incident Response
Network Security
Cloud Security
IT Operations
GRC
Privacy
Legal
Communications
Business Owner
```

The exact participants depend on the nature and severity of the incident.

The report should identify the **business owner** responsible for the affected system or business service.

For example:

```text
Business Owner:
Customer Operations Director
```

This ensures that business impact is assessed alongside technical impact.

The report should identify the **affected department**.

For example:

```text
Affected Department:
Customer Operations
```

The report should identify the **affected system or application**.

For example:

```text
Affected System:
Customer Relationship Management Platform
```

Other examples include:

```text
Email Platform
Identity Management System
Cloud Storage
Database
Web Application
VPN
Endpoint
Production Server
```

The report should identify the **affected asset**.

For example:

```text
Asset:
CRM-SRV-002
```

Where applicable, the report should include the organization's asset inventory identifier.

The incident should be assigned an **incident category**.

Examples include:

```text
Malware
Phishing
Unauthorized Access
Data Breach
Denial of Service
Ransomware
Insider Threat
Lost or Stolen Device
Policy Violation
Vulnerability Exploitation
Cloud Security Incident
Third-Party Security Incident
```

The report should also identify the specific **incident type**.

For example:

```text
Category:
Unauthorized Access

Type:
Compromised User Credentials
```

The report should identify the **incident source**.

For example:

```text
Security Monitoring
Employee Report
Customer Report
Vendor Notification
Threat Intelligence
Automated Detection
External Notification
```

The report should provide an **initial description**.

For example:

```text
Initial Description:

The SOC detected multiple successful
authentication attempts from an unusual
geographic location against a privileged
user account.
```

The initial description should be concise because more detailed information may not be available during the first stages of the investigation.

The report should later be expanded with a **detailed incident description**.

For example:

```text
Detailed Description:

On 10 August 2026, the Security Operations
Center detected multiple successful login
attempts to a privileged cloud account from
an unfamiliar geographic location. Investigation
identified that the account credentials had
likely been compromised through phishing.

The account was used to access cloud resources.
No evidence of data modification was initially
identified. The account was disabled and active
sessions were terminated while the investigation
continued.
```

The report should identify the **detection method**.

Examples include:

```text
SIEM Alert
EDR Alert
Firewall Alert
IDS / IPS
Cloud Security Monitoring
User Report
Threat Intelligence
DLP Alert
Identity Monitoring
Vulnerability Scanner
```

The detection method can be used later to measure the effectiveness of security monitoring.

The report should document the **initial indicators**.

Examples include:

```text
Unusual Login
Impossible Travel
Malware Detection
Suspicious Process
Abnormal Network Traffic
Multiple Failed Logins
Unexpected Privilege Escalation
Large Data Transfer
Unauthorized Configuration Change
```

The report should identify **affected users**.

For example:

```text
Affected Users:
3 privileged administrators
```

Where appropriate, individual user information should be restricted because the incident record may contain personal information.

The report should identify **affected systems**.

For example:

```text
Identity Platform
Cloud Management Console
Customer Database
Endpoint Device
```

The report should identify whether **data was affected**.

For example:

```text
Affected Data:
Customer Account Information
```

The report should identify the **data classification**.

For example:

```text
Data Classification:
Confidential
```

If restricted or sensitive information is involved, the incident should be escalated according to the organization's procedures.

The report should separately assess the impact on **confidentiality, integrity, and availability**.

For example:

```text
Confidentiality:
High

Integrity:
Low

Availability:
None
```

Confidentiality impact concerns unauthorized access or disclosure of information.

Integrity impact concerns unauthorized modification or destruction of information.

Availability impact concerns disruption or loss of access to systems or information.

These three dimensions should be assessed separately because an incident may have a major impact on one dimension but little or no impact on another.

The incident should receive an **initial severity rating**.

A practical scale may be:

```text
Severity 1 – Critical
Severity 2 – High
Severity 3 – Medium
Severity 4 – Low
Severity 5 – Informational
```

For example:

```text
Initial Severity:
High
```

Severity should be based on defined organizational criteria rather than personal judgment.

The assessment may consider:

```text
Number of Systems Affected
Number of Users Affected
Data Sensitivity
Business Criticality
Operational Disruption
Financial Impact
Regulatory Impact
Reputational Impact
Threat Actor Capability
Extent of Compromise
```

The report should document the **business impact**.

For example:

```text
Business Impact:

Customer support operations were disrupted
for approximately two hours while affected
systems were isolated.
```

The report should document the **security impact**.

For example:

```text
Security Impact:

A privileged account was compromised and
unauthorized access to cloud resources
was confirmed.
```

The report should document the **regulatory impact**.

For example:

```text
Regulatory Impact:

Potential personal data exposure identified.
Privacy assessment initiated.
```

The report should document the **initial risk**.

For example:

```text
Initial Risk:
High
```

The risk rating may change as additional information becomes available.

The report should contain an **investigation summary**.

For example:

```text
Investigation Summary:

Authentication logs were reviewed and showed
multiple successful logins from an unusual
location. Endpoint telemetry identified a
phishing email received by the affected user.
Credential theft is considered the most likely
initial access method.

No evidence of malware persistence was identified.
Cloud access logs are being reviewed to determine
whether sensitive data was accessed.
```

The report should identify the **root cause** once the investigation has established it.

For example:

```text
Root Cause:

User credentials were compromised through
a phishing campaign and the account did not
have phishing-resistant MFA enabled.
```

If the root cause is not yet known, the report should state:

```text
Root Cause:
Under Investigation
```

The organization should avoid prematurely assigning a root cause before sufficient evidence exists.

The report should identify the **threat actor** where possible.

For example:

```text
Threat Actor:
Unknown External Actor
```

Or:

```text
Threat Actor:
Known Cybercrime Group
```

Attribution should only be recorded when supported by reliable evidence.

The report should identify the **attack vector**.

Examples include:

```text
Phishing
Credential Theft
Exploited Vulnerability
Malicious Insider
Supply Chain Compromise
Weak Authentication
Misconfiguration
Remote Access
```

The report should document relevant **Indicators of Compromise**.

Examples include:

```text
Malicious IP Address
Malicious Domain
File Hash
Suspicious User Account
Malware Filename
Registry Modification
Unusual Process
Command-and-Control Connection
```

Sensitive technical information should be appropriately protected because incident reports can contain information that could assist attackers.

The report should document **containment actions**.

Examples include:

```text
Disable Account
Reset Credentials
Terminate Sessions
Isolate Endpoint
Block IP Address
Block Domain
Remove Malicious Files
Disable Network Connection
Restrict Cloud Access
Suspend Vendor Access
```

For example:

```text
Containment Actions:

Compromised account disabled.
Active sessions terminated.
Source IP blocked.
Affected endpoint isolated.
Cloud access restricted.
```

The report should document **eradication actions**.

Examples include:

```text
Remove Malware
Patch Vulnerability
Delete Unauthorized Accounts
Remove Persistence Mechanisms
Rebuild Compromised Systems
Rotate Credentials
Remove Malicious Configuration
```

For example:

```text
Eradication:

Malicious software removed.
Affected endpoint rebuilt.
Credentials rotated.
Unauthorized scheduled task removed.
```

The report should document **recovery actions**.

Examples include:

```text
Restore Systems
Validate System Integrity
Restore Connectivity
Re-enable Accounts
Monitor Systems
Validate Security Controls
Return Systems to Production
```

For example:

```text
Recovery:

Systems restored from verified backups.
Security monitoring enabled.
Access controls validated.
Business owner confirmed normal operation.
```

The report should identify **evidence collected**.

Examples include:

```text
SIEM Logs
EDR Data
Firewall Logs
Authentication Logs
Email Headers
Forensic Images
Cloud Audit Logs
Network Traffic
Screenshots
System Configuration
Threat Intelligence
```

Each evidence item should be handled according to the organization's evidence preservation and chain-of-custody requirements.

The report should identify **third parties involved**.

For example:

```text
Cloud Provider
Managed Security Service Provider
Software Vendor
Internet Service Provider
Payment Processor
Cyber Insurance Provider
```

Third-party involvement may create additional contractual, regulatory, and notification requirements.

The report should document **communication and escalation**.

For example:

```text
SOC notified:
08:45

Incident Manager notified:
08:50

CISO notified:
09:05

Business Owner notified:
09:15

Privacy Team notified:
09:30
```

This provides an auditable record of the incident escalation process.

The report should document whether **regulatory notification** may be required.

For example:

```text
Regulatory Notification:
Under Assessment
```

The incident report should not independently make a legal determination where the organization's procedures require review by privacy, legal, or compliance functions.

The report should document whether **customer or user notification** may be required.

For example:

```text
Customer Notification:
Under Assessment
```

Where personal data is involved, the security incident report should connect to the organization's Data Breach Assessment process.

For example:

```text
Security Incident:
INC-2026-145

Data Breach Assessment:
BRT-2026-021
```

The report should document **corrective actions**.

For example:

```text
Corrective Actions:

Implement phishing-resistant MFA.
Strengthen email security controls.
Improve privileged access monitoring.
Conduct targeted security awareness training.
Review privileged account inventory.
```

Each corrective action should have an **action owner**.

For example:

```text
Action:
Implement phishing-resistant MFA

Owner:
Identity and Access Management Manager
```

Each action should have a **target date**.

For example:

```text
Target Date:
30 September 2026
```

Corrective actions should remain tracked until completion or formal acceptance of residual risk.

The report should document **lessons learned**.

For example:

```text
Lessons Learned:

The existing authentication controls
reduced the impact of the compromise but
did not prevent credential theft.

Privileged accounts should transition to
phishing-resistant authentication.

Additional monitoring should be implemented
for unusual privileged access.
```

The report should identify the **residual risk** after containment and remediation.

For example:

```text
Initial Risk:
High

Residual Risk:
Medium
```

Where residual risk remains above the organization's acceptable level, additional treatment or formal risk acceptance may be required.

The report should document the **management decision**.

For example:

```text
Management Decision:

Corrective actions approved.
Residual medium risk accepted temporarily
until implementation of the planned controls.
```

The report should identify who approved **incident closure**.

For example:

```text
Closure Approval:
Incident Response Manager
CISO
Business Owner
```

The closure criteria should be clearly defined.

For example:

```text
Incident Closure Criteria:

Threat contained.
Root cause identified.
Affected systems recovered.
Required notifications completed.
Evidence preserved.
Corrective actions assigned.
Residual risk assessed.
Management informed.
```

The report should record the **closure date**.

For example:

```text
Closure Date:
18 August 2026
```

The final **incident status** may be:

```text
Open
Under Investigation
Contained
Recovering
Monitoring
Closed
```

A practical completed Security Incident Report may look like:

```text
SECURITY INCIDENT REPORT

Incident ID:
INC-2026-145

Incident Title:
Compromised Privileged User Account

Date and Time Occurred:
10 August 2026 – 02:15

Date and Time Detected:
10 August 2026 – 08:42

Incident Reporter:
SOC Analyst

Incident Owner:
Incident Response Manager

Affected Department:
Customer Operations

Affected System:
Cloud Customer Management Platform

Incident Category:
Unauthorized Access

Incident Type:
Compromised Credentials

Detection Method:
SIEM and Identity Monitoring

Initial Description:

Multiple successful logins were detected
from an unusual geographic location against
a privileged user account.

Affected Users:
1 privileged administrator

Affected Systems:
Cloud Management Console

Affected Data:
Customer Account Information

Data Classification:
Confidential

Confidentiality Impact:
High

Integrity Impact:
Low

Availability Impact:
None

Initial Severity:
High

Business Impact:
Customer support operations were temporarily
restricted during investigation.

Security Impact:
Unauthorized privileged access was confirmed.

Regulatory Impact:
Potential personal data exposure identified.

Initial Risk:
High

Root Cause:
Credentials were compromised through phishing.

Attack Vector:
Phishing

Threat Actor:
Unknown External Actor

Containment Actions:

Account disabled.
Active sessions terminated.
Source IP blocked.
Endpoint isolated.

Eradication Actions:

Malicious email removed.
Endpoint rebuilt.
Credentials rotated.

Recovery Actions:

System access restored after validation.
Enhanced monitoring enabled.

Evidence:

Authentication Logs
SIEM Alerts
Email Headers
Endpoint Telemetry
Cloud Audit Logs

Corrective Actions:

Implement phishing-resistant MFA.
Strengthen email security.
Improve privileged access monitoring.
Conduct targeted awareness training.

Residual Risk:
Medium

Management Decision:
Corrective actions approved.
Temporary residual risk accepted.

Closure Status:
Closed

Closure Date:
18 August 2026
```

The Security Incident Report should be connected with the organization's broader GRC processes.

```text
Security Event
      ↓
Incident Report
      ↓
Risk Assessment
      ↓
Data Breach Assessment
      ↓
Corrective Action
      ↓
Risk Register
      ↓
Audit Evidence
      ↓
Management Reporting
```

This ensures that an incident does not simply disappear after the technical response is completed.

A security incident may identify a previously unknown risk.

For example:

```text
Incident:
Privileged Account Compromise

Existing Risk:
Unauthorized Access – Medium

Incident Evidence:
Control weakness identified

Updated Risk:
Unauthorized Privileged Access – High

Treatment:
Implement phishing-resistant MFA
```

The incident may also identify a control deficiency.

For example:

```text
Control:
Privileged Account Authentication

Expected:
Phishing-resistant MFA

Actual:
Password + Basic MFA

Assessment:
Control Gap Identified
```

The control gap can then be connected to a remediation plan.

The incident report can also provide evidence for internal audits.

An auditor may request:

```text
Incident Register
Incident Reports
Incident Classification
Response Records
Escalation Evidence
Corrective Actions
Closure Records
Lessons Learned
```

A complete and consistently maintained incident report provides evidence that the organization has an operational incident management capability rather than merely a documented policy.

The GRC professional should periodically analyze incident reports to identify trends.

For example:

```text
2026 Security Incidents

Phishing:
42

Unauthorized Access:
18

Malware:
12

Misconfiguration:
9

Data Exposure:
7

Lost Devices:
5

Other:
7
```

The organization can then identify recurring problems.

For example:

```text
Observation:

Phishing represents the largest source
of security incidents.

Action:

Strengthen email security controls,
phishing-resistant authentication,
and targeted awareness activities.
```

Incident information can also contribute to cybersecurity metrics and executive reporting.

Examples include:

```text
Total Security Incidents
Critical Incidents
High-Severity Incidents
Mean Time to Detect
Mean Time to Respond
Mean Time to Contain
Mean Time to Recover
Repeat Incidents
Open Corrective Actions
Overdue Corrective Actions
```

The incident report should therefore serve not only as an historical record but also as a source of organizational risk intelligence.

A mature Security Incident Report Template should enable the GRC professional to answer:

```text
What happened?

When did it happen?

When was it detected?

How was it detected?

What systems were affected?

What users were affected?

What data was affected?

What was the confidentiality impact?

What was the integrity impact?

What was the availability impact?

How severe was the incident?

What caused the incident?

How did the attacker or event gain access?

What evidence was collected?

How was the incident contained?

How was the threat eradicated?

How were systems recovered?

Was personal data involved?

Were regulatory or contractual obligations triggered?

What corrective actions are required?

Who owns the corrective actions?

What is the residual risk?

Who approved closure?
```

The key principle is:

> **A Security Incident Report provides a consistent, traceable, and auditable record of a security incident from detection through closure, enabling effective response, accountability, regulatory and compliance support, risk management, corrective action, and continuous improvement of the organization's cybersecurity controls.**



