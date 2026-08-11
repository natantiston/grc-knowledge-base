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

Incident classification is the process of determining the nature, scope, and severity of a security event so that the organization can apply the appropriate response, escalation, resources, and management attention. A consistent classification approach prevents minor events from consuming disproportionate resources while ensuring that serious incidents receive immediate attention.

A security event should first be evaluated to determine whether it represents an actual security incident.

```text
Security Event
      ↓
Initial Assessment
      ↓
Security Incident?
   ↙        ↘
 No          Yes
 ↓            ↓
Monitor     Classify
              ↓
           Assess Severity
              ↓
           Respond
```

A security event may be any observable occurrence within an information system or business environment.

Examples include:

```text
Failed Login
Successful Login
Antivirus Alert
Firewall Alert
Suspicious Email
Unusual Network Traffic
Configuration Change
Vulnerability Detection
Password Reset
```

Not every security event represents a security incident.

For example:

```text
Event:
Five failed login attempts

Assessment:
Normal user behavior

Classification:
Security Event

Action:
Monitor
```

However:

```text
Event:
500 failed login attempts against
multiple privileged accounts

Assessment:
Potential brute-force attack

Classification:
Security Incident

Action:
Investigate and respond
```

The organization should establish clear criteria for determining when an event becomes an incident.

Examples include:

```text
Confirmed Unauthorized Access
Confirmed Malware Infection
Confirmed Data Exposure
Confirmed Security Control Bypass
Confirmed Account Compromise
Confirmed Service Disruption
Confirmed Policy Violation
Confirmed Exploitation
```

Once an event is determined to be an incident, it should be assigned an **incident category**.

A practical classification structure may include:

```text
INCIDENT CATEGORIES

1. Unauthorized Access
2. Malware
3. Phishing and Social Engineering
4. Data Breach
5. Denial of Service
6. Vulnerability Exploitation
7. Insider Threat
8. Lost or Stolen Asset
9. Security Misconfiguration
10. Third-Party Security Incident
11. Cloud Security Incident
12. Policy Violation
```

Unauthorized access incidents may include:

```text
Compromised Credentials
Account Takeover
Privilege Escalation
Unauthorized System Access
Unauthorized Database Access
Unauthorized Administrative Access
```

Malware incidents may include:

```text
Virus
Trojan
Worm
Spyware
Ransomware
Remote Access Trojan
Malicious Script
Cryptominer
```

Phishing and social engineering incidents may include:

```text
Credential Phishing
Business Email Compromise
Malicious Attachment
Malicious Link
Impersonation
Voice Phishing
SMS Phishing
```

Data breach incidents may include:

```text
Unauthorized Disclosure
Data Exfiltration
Accidental Data Exposure
Lost Personal Data
Misconfigured Storage
Unauthorized Data Access
```

Denial-of-service incidents may include:

```text
Distributed Denial of Service
Application-Level Attack
Network Flood
Resource Exhaustion
```

Vulnerability exploitation incidents may include:

```text
Exploited Software Vulnerability
Zero-Day Exploitation
Unpatched System Exploitation
Web Application Exploitation
Remote Code Execution
```

Insider threat incidents may include:

```text
Malicious Insider
Unauthorized Employee Activity
Excessive Data Access
Unauthorized Data Transfer
Intentional Policy Violation
```

Lost or stolen asset incidents may include:

```text
Lost Laptop
Stolen Mobile Device
Lost Removable Media
Stolen Corporate Equipment
```

Security misconfiguration incidents may include:

```text
Publicly Exposed Storage
Incorrect Firewall Rule
Excessive Permissions
Weak Authentication Configuration
Unsecured Cloud Resource
```

Third-party incidents may include:

```text
Supplier Breach
Cloud Provider Incident
Managed Service Provider Compromise
Software Supply Chain Incident
Third-Party Data Exposure
```

Cloud security incidents may include:

```text
Compromised Cloud Account
Unauthorized Cloud Resource
Exposed Storage
Cloud Privilege Escalation
Cloud Configuration Error
```

Policy violations may include:

```text
Unauthorized Software
Unauthorized Data Transfer
Security Procedure Violation
Acceptable Use Violation
Unauthorized Device Usage
```

After classification, the organization should determine the **severity** of the incident.

A practical severity matrix can use four levels:

```text
Critical
High
Medium
Low
```

Some organizations may use five levels:

```text
Severity 1 – Critical
Severity 2 – High
Severity 3 – Medium
Severity 4 – Low
Severity 5 – Informational
```

The organization should define objective criteria for each level.

A Critical incident may involve:

```text
Widespread Business Disruption
Major Customer Impact
Major Data Breach
Critical Infrastructure Impact
Compromise of Critical Systems
Significant Regulatory Exposure
Active Ransomware Across Critical Systems
Major Financial Impact
```

A High incident may involve:

```text
Compromise of Privileged Account
Significant Data Exposure
Multiple Systems Affected
Material Business Disruption
Confirmed Exploitation
Significant Customer Impact
High-Value Asset Compromise
```

A Medium incident may involve:

```text
Limited System Impact
Limited Data Exposure
Single User Compromise
Contained Malware
Security Policy Violation
Limited Business Disruption
```

A Low incident may involve:

```text
Single Endpoint Alert
Suspicious Activity With No Confirmed Impact
Minor Policy Violation
Blocked Phishing Attempt
Low-Risk Security Event
```

Severity should not be determined solely by the technical characteristics of the incident. The organization should consider business impact, regulatory requirements, data sensitivity, operational impact, and potential harm.

A practical severity assessment can consider:

```text
Confidentiality Impact
Integrity Impact
Availability Impact
Data Sensitivity
Number of Users Affected
Number of Systems Affected
Business Criticality
Financial Impact
Regulatory Impact
Customer Impact
Reputational Impact
Threat Actor Capability
Scope of Compromise
Duration
Recoverability
```

The relationship can be represented as:

```text
Incident
   ↓
Scope
   +
Business Impact
   +
Data Sensitivity
   +
Security Impact
   +
Regulatory Impact
   +
Threat Capability
   ↓
Severity Rating
```

For example, consider a compromised employee account.

```text
Incident:
Employee Account Compromise

Affected User:
1

System:
Corporate Email

Data:
Internal Information

Business Impact:
Low

Regulatory Impact:
None

Severity:
Medium
```

Now consider a compromised privileged administrator account.

```text
Incident:
Privileged Account Compromise

Affected User:
1 Administrator

Systems:
Multiple Critical Systems

Data:
Confidential and Restricted

Business Impact:
High

Regulatory Impact:
Potential

Severity:
High
```

The same type of event can therefore receive different severity ratings depending on its circumstances.

The organization should also distinguish between **incident category** and **incident severity**.

For example:

```text
Incident Category:
Phishing

Incident Severity:
Low
```

Another phishing incident may be:

```text
Incident Category:
Phishing

Incident Severity:
Critical
```

The first may involve an employee reporting a suspicious email before interacting with it.

The second may involve a successful business email compromise that results in unauthorized access to financial systems and sensitive information.

The classification process should therefore evaluate both **what happened** and **how serious the consequences are**.

A practical Incident Classification and Severity Matrix may look like:

| Severity | Typical Impact                          | Example                                | Response                       |
| -------- | --------------------------------------- | -------------------------------------- | ------------------------------ |
| Critical | Major organizational impact             | Ransomware affecting critical services | Immediate executive escalation |
| High     | Significant business or security impact | Privileged account compromise          | Urgent incident response       |
| Medium   | Limited but confirmed impact            | Single endpoint malware infection      | Standard incident response     |
| Low      | Minimal impact                          | Blocked phishing attempt               | Monitor and document           |

The organization should establish **escalation requirements** for each severity level.

For example:

```text
Critical:
SOC → Incident Manager → CISO → Executive Management
        → Legal → Privacy → Business Leadership

High:
SOC → Incident Manager → CISO
      → Relevant Business Owner

Medium:
SOC → Incident Response Team
      → System Owner

Low:
SOC → Security Operations
      → Routine Monitoring
```

The exact escalation path should be customized to the organization's governance structure.

Critical incidents should generally trigger immediate escalation.

For example:

```text
Critical Incident Detected
        ↓
Immediate Incident Manager Notification
        ↓
CISO Notification
        ↓
Executive Management Notification
        ↓
Legal / Privacy Assessment
        ↓
Business Continuity Activation if Required
```

The classification process should define **response time targets**.

For example:

```text
Critical:
Immediate response

High:
Response within 15 minutes

Medium:
Response within 1 hour

Low:
Response within 1 business day
```

These targets should align with the organization's incident response policy and operational capabilities.

The organization should also define **containment expectations**.

For example:

```text
Critical:
Immediate containment

High:
Urgent containment

Medium:
Containment according to incident response procedure

Low:
Containment when operationally appropriate
```

The severity matrix should also define when additional functions must be involved.

For example:

```text
Privacy:
Personal data potentially affected

Legal:
Potential legal or contractual exposure

Compliance:
Regulatory requirement potentially triggered

Communications:
Significant customer or public impact

Finance:
Financial loss or fraud

Business Continuity:
Critical service disruption
```

The classification process should also consider **data sensitivity**.

For example:

```text
Public Data:
Low additional impact

Internal Data:
Low to Medium

Confidential Data:
Medium to High

Restricted / Highly Sensitive Data:
High to Critical
```

However, data classification should not automatically determine incident severity. The organization should consider the actual circumstances and potential impact.

The number of affected individuals should also be considered.

For example:

```text
Affected Users:
1

Potential Severity:
Low / Medium
```

Compared with:

```text
Affected Users:
500,000

Potential Severity:
High / Critical
```

The business criticality of affected systems is another important factor.

For example:

```text
System:
Internal Training Portal

Criticality:
Low
```

Compared with:

```text
System:
Core Banking Platform

Criticality:
Critical
```

An identical technical failure could therefore produce very different business consequences.

The organization should also consider the **duration of disruption**.

For example:

```text
Service Disruption:
5 minutes

Potential Severity:
Low
```

Compared with:

```text
Service Disruption:
48 hours

Potential Severity:
High / Critical
```

The ability to recover should also be considered.

A system with a validated backup and tested recovery procedure may have a lower operational impact than a system with no viable recovery capability.

The severity matrix should also consider **regulatory and contractual obligations**.

For example:

```text
Incident:
Personal Data Exposure

Regulatory Requirement:
Potential notification obligation

Severity:
High
```

Another incident involving the same amount of data may have a different severity depending on the nature of the information, jurisdiction, affected individuals, and potential harm.

The organization should maintain documented criteria for **severity reassessment**.

An incident may initially be classified as Medium:

```text
Initial Severity:
Medium
```

During investigation, the organization may discover that sensitive data was accessed:

```text
New Finding:
Restricted customer information accessed

Updated Severity:
High
```

Later, the organization may determine that a large number of records were exfiltrated:

```text
New Finding:
Confirmed large-scale data exfiltration

Updated Severity:
Critical
```

Severity should therefore be treated as a dynamic assessment rather than a permanent classification assigned at the beginning of the incident.

The incident record should maintain a history of severity changes.

For example:

```text
Severity History

10 Aug 08:50:
Medium – Initial assessment

10 Aug 10:15:
High – Privileged access confirmed

10 Aug 14:30:
Critical – Data exfiltration confirmed
```

This provides an important audit trail.

The organization should also record **who approved or assigned the severity**.

For example:

```text
Initial Classification:
SOC Analyst

High Severity Confirmation:
Incident Manager

Critical Severity Confirmation:
CISO
```

This creates accountability for significant classification decisions.

The severity matrix should be periodically reviewed to determine whether it remains appropriate.

The organization should analyze historical incidents to identify whether classifications were consistently applied.

For example:

```text
Incident Review:

20 incidents classified as Medium
8 incidents classified as High
2 incidents classified as Critical

Observation:

Several Medium incidents had significant
business impact but were initially
under-classified.
```

The organization can then refine its severity criteria.

The GRC professional should ensure that incident classification is aligned with the organization's:

```text
Incident Response Policy
Risk Management Framework
Business Continuity Plan
Data Protection Requirements
Regulatory Obligations
Third-Party Risk Requirements
Crisis Management Procedures
```

The Incident Classification and Severity Matrix should also support management reporting.

For example:

```text
Monthly Security Incidents

Critical:
2

High:
7

Medium:
24

Low:
51
```

Management can then identify whether the organization's incident risk is increasing or decreasing.

Trend analysis may show:

```text
Critical Incidents:
↑ Increasing

High Incidents:
→ Stable

Phishing Incidents:
↑ Increasing

Malware Incidents:
↓ Decreasing
```

This information can be used to prioritize security investments and corrective actions.

The classification matrix should also be connected with the organization's risk register.

For example:

```text
Incident:
Repeated Phishing Compromise

Observation:
Weak User Authentication

Risk:
Credential Compromise

Risk Rating:
High

Treatment:
Implement phishing-resistant MFA
```

The incident classification process can therefore become a source of risk intelligence rather than simply an operational activity.

A mature Incident Classification and Severity Matrix should enable the organization to answer:

```text
What type of incident occurred?

Is this a security incident?

How severe is the incident?

What systems are affected?

What data is affected?

How many users are affected?

What is the business impact?

What is the security impact?

Is there regulatory exposure?

Who must be notified?

How quickly must the organization respond?

What resources are required?

When should management be escalated?

When should severity be reassessed?
```

The key principle is:

> **Incident classification and severity assessment provide a consistent, risk-based mechanism for determining how a security event should be handled, ensuring that response activities, escalation, resources, and management attention are proportional to the actual and potential impact of the incident.**

A Security Incident Response Checklist provides a structured sequence of activities that security, IT, GRC, privacy, legal, and business teams can use when responding to a confirmed or suspected security incident. The checklist helps ensure that critical response activities are not overlooked during a potentially stressful and time-sensitive situation.

The checklist should support the complete incident lifecycle:

```text id="w7t8s3"
Preparation
    ↓
Identification
    ↓
Analysis
    ↓
Containment
    ↓
Eradication
    ↓
Recovery
    ↓
Post-Incident Review
    ↓
Improvement
```

A practical Security Incident Response Checklist can contain:

```text id="q4r1zx"
SECURITY INCIDENT RESPONSE CHECKLIST

Incident ID:

Incident Title:

Incident Date:

Incident Owner:

Severity:

Incident Category:

Detection Time:

Response Start Time:

Affected Systems:

Affected Users:

Affected Data:

Incident Response Team:

PREPARATION
☐ Incident response procedure available
☐ Incident response team identified
☐ Contact information available
☐ Required tools available
☐ Logging enabled
☐ Backup availability confirmed
☐ Evidence preservation process available

IDENTIFICATION AND TRIAGE
☐ Security event reviewed
☐ Incident confirmed
☐ Incident ID assigned
☐ Initial classification completed
☐ Initial severity assigned
☐ Affected assets identified
☐ Affected users identified
☐ Potential data exposure assessed
☐ Initial risk assessed
☐ Incident owner assigned

ANALYSIS AND INVESTIGATION
☐ Initial indicators documented
☐ Logs collected
☐ Evidence preserved
☐ Attack vector assessed
☐ Scope determined
☐ Threat actor assessed
☐ Compromised accounts identified
☐ Affected systems identified
☐ Affected data identified
☐ Root cause investigated

CONTAINMENT
☐ Immediate containment performed
☐ Compromised accounts disabled
☐ Malicious connections blocked
☐ Affected endpoints isolated
☐ Unauthorized access removed
☐ Additional compromise prevented
☐ Business impact assessed

ERADICATION
☐ Malware removed
☐ Vulnerability remediated
☐ Persistence mechanisms removed
☐ Compromised credentials changed
☐ Unauthorized accounts removed
☐ Security configuration corrected

RECOVERY
☐ Systems restored
☐ System integrity validated
☐ Security controls validated
☐ Monitoring increased
☐ Business owner approval obtained
☐ Services returned to normal operation

COMMUNICATION AND ESCALATION
☐ Incident manager notified
☐ CISO notified if required
☐ Business owner notified
☐ Privacy team notified if required
☐ Legal team notified if required
☐ Compliance team notified if required
☐ Third-party provider notified if required
☐ Customer notification assessed
☐ Regulatory notification assessed
☐ Executive management notified if required

POST-INCIDENT
☐ Incident report completed
☐ Root cause documented
☐ Lessons learned documented
☐ Corrective actions identified
☐ Action owners assigned
☐ Target dates established
☐ Residual risk assessed
☐ Risk register updated if required
☐ Policies or procedures updated if required
☐ Controls improved if required
☐ Incident formally closed
```

The checklist should begin with **preparation activities**. Effective incident response depends on preparation before an incident occurs.

The organization should maintain an approved incident response procedure that defines responsibilities, escalation requirements, communication channels, evidence handling, decision-making authority, and recovery requirements.

The incident response team should be clearly identified.

For example:

```text id="6x2g5m"
Incident Response Manager
SOC
Security Engineering
IT Operations
Network Security
Cloud Security
GRC
Privacy
Legal
Communications
Business Owner
```

Not every incident requires every function. The response team should be activated according to the incident's severity and characteristics.

Contact information should be maintained and periodically validated.

For example:

```text id="a9z3kd"
Primary Incident Manager:
Available 24/7

Security Operations:
24/7

CISO:
Escalation Contact

Privacy:
Business Hours / Emergency Contact

Legal:
Emergency Contact
```

The organization should ensure that required technical tools are available before an incident occurs.

Examples include:

```text id="qz7y2k"
SIEM
EDR
Network Monitoring
Forensic Tools
Threat Intelligence
Ticketing Platform
Secure Communication Platform
Backup Systems
Identity Management Tools
```

Logging should be enabled on critical systems and configured so that relevant security events can be investigated when required.

The organization should also verify that backups are available and recoverable.

A backup that exists but cannot be restored should not be considered an effective recovery control.

The identification and triage stage begins when a suspicious event is detected.

The analyst should determine whether the event represents a security incident.

For example:

```text id="z7o9kq"
Security Alert
      ↓
Review Evidence
      ↓
False Positive?
   ↙        ↘
 Yes         No
 ↓            ↓
Close      Investigate
```

The analyst should assign an Incident ID once the event is determined to require formal incident management.

For example:

```text id="y7r1p3"
Incident ID:
INC-2026-154
```

The initial classification should identify the type of incident.

For example:

```text id="0l1z9a"
Incident Category:
Unauthorized Access

Incident Type:
Compromised Privileged Account
```

An initial severity rating should also be assigned.

For example:

```text id="0m9d5v"
Initial Severity:
High
```

The severity should be reassessed as the investigation develops.

The response team should identify the affected assets.

For example:

```text id="u6r9by"
Affected Assets:

VPN Gateway
Administrator Account
Cloud Management Console
Customer Database
```

The response team should identify affected users.

For example:

```text id="m0n9w3"
Affected Users:

3 Administrators
12 Customer Service Users
```

The response team should determine whether sensitive information may have been affected.

For example:

```text id="p7c4am"
Potential Data Exposure:

Customer Personal Data
Internal Credentials
Security Configuration Information
```

The initial risk assessment should consider the potential impact even when the full scope is not yet known.

For example:

```text id="y0n4zk"
Initial Risk:
High

Reason:
Privileged access compromised and
customer information may have been accessed.
```

An incident owner should then be assigned to coordinate the response.

The analysis and investigation stage should establish what happened and determine the scope of the incident.

The investigation should begin by documenting the initial indicators.

Examples include:

```text id="9y7z2q"
Unusual Login
Suspicious Process
Malicious File
Abnormal Network Traffic
Unauthorized Configuration Change
Large Data Transfer
```

Relevant logs should be collected.

Examples include:

```text id="8p5x7b"
Authentication Logs
Firewall Logs
DNS Logs
Proxy Logs
EDR Logs
Application Logs
Database Logs
Cloud Audit Logs
Email Logs
```

Evidence should be preserved before systems are modified or rebuilt whenever possible.

The organization should maintain evidence integrity and document who collected, transferred, analyzed, or stored significant evidence.

For example:

```text id="4b7m1s"
Evidence ID:
EV-2026-044

Collected By:
Security Analyst

Collection Time:
10 August 2026 – 09:15

Source:
Cloud Authentication Logs

Storage:
Approved Evidence Repository
```

The investigation should identify the likely attack vector.

Examples include:

```text id="r3k8f1"
Phishing
Credential Theft
Exploited Vulnerability
Weak Authentication
Misconfiguration
Malicious Insider
Third-Party Compromise
```

The response team should determine the scope of compromise.

For example:

```text id="2q7h1v"
Initial Scope:
1 Account

Confirmed Scope:
1 Account
4 Systems
2 Cloud Resources
```

The investigation should identify compromised accounts.

For example:

```text id="p5w9ke"
Compromised Account:
admin01

Privilege:
Cloud Administrator
```

The team should identify affected systems and determine whether the attacker or malicious activity moved laterally.

For example:

```text id="j4k7y0"
Initial Access:
Email Account

Lateral Movement:
Cloud Management Console

Potential Target:
Customer Database
```

The team should determine whether sensitive information was accessed, modified, deleted, or exfiltrated.

For example:

```text id="c8y2pl"
Data Assessment:

Access:
Confirmed

Modification:
Not Identified

Deletion:
Not Identified

Exfiltration:
Under Investigation
```

The investigation should attempt to determine the root cause.

For example:

```text id="1k4b8f"
Root Cause:

Compromised administrator credentials
combined with insufficient privileged
authentication controls.
```

If the root cause cannot yet be confirmed, it should be documented as under investigation rather than assumed.

Containment activities should focus on preventing the incident from expanding.

Depending on the incident, containment may include:

```text id="q8x3pn"
Disable Compromised Account
Terminate Active Sessions
Isolate Endpoint
Block Malicious IP
Block Malicious Domain
Disable Network Access
Restrict Cloud Permissions
Quarantine Malware
Suspend Third-Party Access
```

For example:

```text id="8z6q1r"
Containment Completed:

Administrator account disabled.
Active sessions terminated.
Endpoint isolated.
Malicious IP blocked.
Cloud access restricted.
```

Containment decisions should consider business continuity.

For example, immediately shutting down a critical production system may prevent further compromise but could create significant operational consequences.

The response team should therefore consider:

```text id="6f3r9w"
Security Impact
Business Impact
Customer Impact
Safety Impact
Recovery Capability
Legal Requirements
```

Eradication activities should remove the cause of the incident.

Examples include:

```text id="5u7m2x"
Remove Malware
Patch Vulnerability
Remove Persistence
Reset Credentials
Remove Unauthorized Accounts
Correct Misconfiguration
Rebuild Compromised Systems
Update Security Controls
```

Credential changes should include all credentials that may have been exposed.

For example:

```text id="d8q4y7"
Password Reset
MFA Reset
API Key Rotation
Service Account Credential Rotation
Certificate Replacement
Privileged Credential Rotation
```

Recovery activities should restore systems to normal and verify that they are secure before returning them to production.

The response team should validate system integrity.

For example:

```text id="w4r8p2"
System Validation:

Operating System Integrity
Application Integrity
Configuration Integrity
Security Tool Status
Access Controls
Logging
Monitoring
```

Security controls should also be validated.

For example:

```text id="s7k5q2"
MFA:
Validated

EDR:
Operational

Logging:
Operational

Privileged Access:
Validated

Network Controls:
Validated
```

Monitoring should normally be increased after recovery.

For example:

```text id="c2n6x9"
Post-Recovery Monitoring:

Enhanced authentication monitoring
for 14 days.

Enhanced endpoint monitoring
for 30 days.
```

The business owner should confirm that the affected service is ready to return to normal operation.

Communication and escalation activities should be documented throughout the incident.

The incident manager should determine which stakeholders need to be informed.

For example:

```text id="v5m8k2"
Incident Manager
CISO
Business Owner
Privacy
Legal
Compliance
Communications
Executive Management
Third-Party Provider
```

The organization should avoid unnecessary disclosure of sensitive incident information.

Communication should follow approved procedures and the principle of need-to-know.

Where personal data may be affected, the privacy function should perform the required assessment.

For example:

```text id="p8r3m1"
Security Incident
       ↓
Personal Data Potentially Affected
       ↓
Privacy Assessment
       ↓
Breach Determination
       ↓
Notification Decision
```

Regulatory notification should be assessed according to applicable laws and organizational procedures.

Customer notification should also be assessed where appropriate.

The response checklist should record the decision and responsible authority.

For example:

```text id="f7n2q5"
Regulatory Notification:
Required

Decision Owner:
Privacy / Legal

Notification Status:
Completed
```

The post-incident stage begins after the immediate response has been completed.

The incident report should be finalized with the key facts established during the investigation.

The root cause should be documented.

For example:

```text id="r6v9k1"
Root Cause:

Phishing attack resulted in credential
compromise. Existing authentication controls
did not provide sufficient phishing resistance.
```

Lessons learned should be documented.

Examples include:

```text id="m5x7c2"
Detection worked as expected.

Privileged authentication requires improvement.

Email security controls should be strengthened.

Incident escalation was effective.

Third-party notification requirements
need clearer procedures.
```

Corrective actions should be documented and assigned.

For example:

```text id="e4q8n6"
Corrective Action:
Implement phishing-resistant MFA

Owner:
Identity and Access Management

Target Date:
30 September 2026

Status:
Open
```

The organization should determine whether the incident exposed a new or changed risk.

For example:

```text id="n2v7k4"
Incident:
Compromised Privileged Account

Risk Register Update:
Required

New Risk:
Insufficient Protection of Privileged Accounts

Risk Rating:
High
```

Policies and procedures should be reviewed when the incident identifies governance weaknesses.

For example:

```text id="y6m3p8"
Incident Finding:
Incident escalation was delayed.

Improvement:
Update Incident Response Procedure
and escalation matrix.
```

Security controls should also be reviewed.

For example:

```text id="k7q4x1"
Control:
Privileged Authentication

Finding:
Existing MFA was vulnerable to phishing.

Improvement:
Implement phishing-resistant MFA.
```

The incident should only be formally closed when the organization's closure criteria have been satisfied.

A practical closure checklist may include:

```text id="w8r2m5"
☐ Threat contained
☐ Root cause identified
☐ Eradication completed
☐ Systems recovered
☐ Evidence preserved
☐ Required notifications completed
☐ Corrective actions assigned
☐ Residual risk assessed
☐ Management informed
☐ Incident report completed
☐ Lessons learned documented
☐ Closure approved
```

The incident response checklist should also support evidence collection for audit purposes.

Auditors may request evidence showing:

```text id="c5n8q3"
Incident Detection
Incident Classification
Severity Assessment
Escalation
Investigation
Evidence Collection
Containment
Eradication
Recovery
Notification
Corrective Actions
Closure
```

The checklist can therefore demonstrate that the organization followed its approved incident response process.

The GRC professional should periodically review completed checklists to identify recurring weaknesses.

For example:

```text id="j3v6p9"
Observation:

Several incidents lacked documented
root cause analysis.

Action:

Require root cause documentation before
incident closure unless formally exempted.
```

Another example:

```text id="q5m8r2"
Observation:

Incident severity was frequently reassessed
after significant delays.

Action:

Require formal severity reassessment
during defined investigation milestones.
```

Incident response checklist data can also contribute to security metrics.

Examples include:

```text id="x7k2m4"
Mean Time to Detect
Mean Time to Respond
Mean Time to Contain
Mean Time to Recover
Percentage of Incidents Closed on Time
Percentage of Incidents With Root Cause Identified
Number of Repeat Incidents
Number of Overdue Corrective Actions
```

The checklist should be reviewed and improved after significant incidents.

The organization should ask:

```text id="p9r4v7"
Were the correct people notified?

Was escalation fast enough?

Was the incident correctly classified?

Was sufficient evidence collected?

Was containment effective?

Was the root cause identified?

Were recovery procedures effective?

Were regulatory requirements addressed?

Were corrective actions completed?

What should change in the response process?
```

The Security Incident Response Checklist should ultimately provide a practical bridge between the organization's incident response policy and its actual operational response.

The key principle is:

> **A Security Incident Response Checklist provides a consistent and auditable sequence of actions that helps ensure incidents are identified, investigated, contained, eradicated, recovered, communicated, and formally closed while supporting risk management, compliance, and continuous improvement.**





