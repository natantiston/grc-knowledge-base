# 19.10 Cybersecurity Incident and Crisis Case Studies

## Part 1 – Responding to a Major Cybersecurity Incident

A major cybersecurity incident is one of the most demanding situations a GRC professional can face. During a significant incident, technical teams must contain the threat while management must simultaneously understand business impact, regulatory exposure, operational consequences, financial risk, and recovery requirements.

The GRC function plays an important role because cybersecurity incidents are not purely technical events.

A mature response connects:

**Cybersecurity Detection → Incident Classification → Business Impact → Risk Assessment → Crisis Governance → Regulatory Assessment → Executive Decision-Making → Recovery → Corrective Action**

This case study demonstrates how a large telecommunications organization can manage a major cybersecurity incident from initial detection through recovery.

---

# Case Study: GlobalConnect Telecom

GlobalConnect Telecom operates telecommunications, cloud, digital, and enterprise technology services across multiple countries.

The organization has:

* 18,000 employees
* 20 million customers
* Multiple data centers
* Hybrid cloud infrastructure
* 24/7 Security Operations Center
* Enterprise SOC and SIEM
* Network Operations Center
* Critical telecommunications infrastructure
* Customer-facing digital platforms
* Third-party technology providers

The organization has an established cybersecurity incident-response process.

However, the incident described below becomes significantly larger than a normal security event.

---

# 1. The Initial Detection

At **02:17 Monday morning**, the Security Operations Center detects unusual authentication activity.

The initial indicators include:

* Multiple privileged-account logins
* Authentication from unusual geographic locations
* Large-volume database queries
* Unexpected administrative activity
* Disabled security controls on several servers
* Unusual outbound network traffic

The SOC initially categorizes the event as:

**Severity 2 – High Cybersecurity Incident**

Within 45 minutes, additional systems show signs of compromise.

The incident is escalated to:

* CISO
* CIO
* Chief Risk Officer
* Incident Response Manager
* Infrastructure Leadership
* Privacy Officer
* Legal
* Business Continuity
* Communications

The incident is now classified as:

**Severity 1 – Major Cybersecurity Incident**

---

# 2. Determine Whether It Is a Crisis

Not every cybersecurity incident becomes a business crisis.

GlobalConnect defines a crisis using business-impact criteria.

A cybersecurity incident becomes a potential crisis when it causes or threatens:

* Critical-service disruption
* Large-scale customer impact
* Significant financial loss
* Major data compromise
* Regulatory exposure
* Safety implications
* Extended operational disruption
* Material reputational damage
* Executive or board-level intervention

The incident begins affecting customer-facing systems.

The organization therefore activates its **Cyber Crisis Management Plan**.

---

# 3. Establish Incident Command

A major incident requires clear leadership.

GlobalConnect activates an incident command structure.

### Incident Commander

Responsible for coordinating the overall response.

### Technical Response Team

Responsible for:

* Investigation
* Containment
* Eradication
* Forensics
* Recovery

### GRC/Risk Team

Responsible for:

* Business-risk assessment
* Risk tracking
* Executive reporting
* Regulatory coordination
* Decision records
* Risk acceptance

### Legal and Privacy

Responsible for:

* Legal assessment
* Regulatory obligations
* Privacy implications
* Notification requirements

### Business Continuity

Responsible for:

* Critical-service continuity
* Business impact
* Recovery priorities

### Communications

Responsible for:

* Internal communication
* Customer communication
* Media coordination

This prevents dozens of executives from giving conflicting instructions to technical teams.

---

# 4. Establish the Incident War Room

The organization creates a dedicated virtual and physical crisis room.

The war room becomes the central coordination point.

The team maintains:

* Incident timeline
* Situation report
* Decision log
* Action tracker
* Risk register
* System-impact list
* Regulatory tracker
* Communication log
* Recovery tracker

Every major decision is documented.

For example:

**02:17** – Initial detection

**02:42** – Privileged-account compromise confirmed

**03:05** – Additional servers identified

**03:30** – Incident escalated to Severity 1

**04:00** – Crisis management activated

**05:15** – Customer platform isolation approved

**07:00** – Regulatory assessment initiated

The timeline later becomes important for internal audit, regulators, management review, and lessons learned.

---

# 5. Establish Known Facts and Unknowns

During a major incident, information changes rapidly.

GlobalConnect creates two categories.

### Confirmed Facts

* Privileged accounts were compromised.
* Multiple servers were accessed.
* Malware was detected.
* Unauthorized administrative activity occurred.
* Certain customer systems are affected.

### Unknowns

* Full attack timeline
* Complete attacker access
* Whether data was exfiltrated
* Whether backups were compromised
* Whether persistence remains
* Exact number of affected customers

This distinction prevents management from treating assumptions as facts.

---

# 6. Conduct Initial Business Impact Assessment

The GRC team immediately evaluates business impact.

The assessment considers:

| Area                  | Impact  |
| --------------------- | ------- |
| Customer services     | High    |
| Network operations    | Medium  |
| Billing               | High    |
| Customer portal       | High    |
| Internal systems      | High    |
| Data confidentiality  | High    |
| Regulatory compliance | High    |
| Financial             | Unknown |
| Reputation            | High    |

The GRC team does not wait for the technical investigation to finish before beginning the business-impact assessment.

---

# 7. Identify Critical Business Services

The organization maps affected technology to business services.

For example:

**Customer Portal**

→ Authentication platform

→ Identity infrastructure

→ Database

→ Cloud platform

The organization identifies:

* Which services are affected?
* Which services can operate manually?
* Which services can be isolated?
* Which services must remain available?
* What is the maximum tolerable downtime?

This connects cybersecurity response to business continuity.

---

# 8. Prioritize Containment

Technical teams must balance two competing objectives:

**Contain the attacker**

versus

**Maintain critical services**

For example, completely shutting down a telecommunications authentication system may stop the attack but could also affect millions of customers.

The Incident Commander therefore requires decisions to consider:

**Security Risk + Business Impact + Recovery Impact**

The GRC function helps management understand the trade-offs.

---

# 9. Establish Emergency Risk Decisions

Suppose the technical team recommends disconnecting a critical database.

The GRC assessment shows:

**Cybersecurity Benefit:** Very High

**Customer Impact:** Very High

**Operational Impact:** High

**Recovery Complexity:** Medium

Management decides:

> Disconnect the database after activating the emergency customer-service fallback process.

The decision is documented.

This is a critical GRC function.

The GRC team does not make the technical decision.

It ensures that the **risk trade-off is understood and formally governed**.

---

# 10. Investigate the Attack

The technical team investigates:

* Initial access
* Compromised accounts
* Vulnerabilities
* Malware
* Persistence mechanisms
* Lateral movement
* Command-and-control
* Data access
* Data exfiltration
* Privilege escalation

Suppose investigators determine:

**Initial Access**

→ Compromised privileged credentials

**Privilege Escalation**

→ Excessive permissions

**Lateral Movement**

→ Weak network segmentation

**Persistence**

→ Malicious scheduled tasks

**Data Access**

→ Customer database

This begins forming the attack narrative.

---

# 11. Preserve Forensic Evidence

Evidence preservation is critical.

The organization preserves:

* Disk images
* Memory captures
* Authentication logs
* Network logs
* SIEM records
* Cloud logs
* Endpoint telemetry
* Firewall logs
* Database activity
* Malware samples
* Configuration records

Evidence is stored securely and access is controlled.

The organization avoids unnecessarily altering compromised systems before forensic requirements are considered.

---

# 12. Assess Data Compromise

The Privacy and GRC teams determine whether personal or sensitive information may have been accessed.

Potentially affected information includes:

* Customer names
* Contact information
* Account information
* Service information
* Billing information

The organization separates:

**Systems compromised**

from

**Data confirmed accessed**

from

**Data potentially accessed**

This distinction is important for regulatory and customer communications.

---

# 13. Regulatory Assessment

Legal and Compliance identify potentially applicable requirements.

The assessment considers:

* Cybersecurity regulations
* Privacy regulations
* Telecommunications requirements
* Contractual obligations
* Sector-specific reporting requirements
* National requirements
* Customer notification requirements

The regulatory team creates a notification matrix.

| Requirement                 | Trigger              | Deadline            | Owner      | Status    |
| --------------------------- | -------------------- | ------------------- | ---------- | --------- |
| Privacy notification        | Personal-data breach | Applicable deadline | Privacy    | Assessing |
| Cyber incident notification | Significant incident | Applicable deadline | Compliance | Assessing |
| Contractual notice          | Service impact       | Contract-defined    | Legal      | Open      |

This prevents regulatory obligations from being overlooked during the technical response.

---

# 14. Establish Executive Situation Reports

Executives do not need raw SIEM alerts.

They need a concise business picture.

GlobalConnect produces a situation report every two hours.

### Executive Situation Report

**Incident:** Major Cybersecurity Incident

**Current Severity:** Critical

**Affected Services:** Customer portal, billing, selected enterprise services

**Customers Potentially Affected:** 4.2 million

**Confirmed Data Access:** Under investigation

**Attack Status:** Contained in primary environment

**Recovery:** 35% complete

**Regulatory Assessment:** In progress

**Current Business Risk:** High

**Major Decisions Required:** Customer notification strategy and temporary service restrictions

This provides executives with actionable information.

---

# 15. Crisis Communication

Communication is controlled through the crisis-management structure.

Internal communications explain:

* What employees need to know
* What services are affected
* What employees must do
* What information they should not disclose

Customer communication is coordinated through:

* Communications
* Legal
* Privacy
* Cybersecurity
* Executive Management

The organization avoids conflicting messages.

---

# 16. Regulatory and Customer Notification

If notification thresholds are met, the organization prepares communications.

The notification process is governed by:

**Facts → Risk Assessment → Legal Requirement → Approval → Notification → Evidence**

The organization records:

* Who approved notification
* When the decision was made
* What information was available
* Why the decision was reached
* What was communicated

This provides defensibility.

---

# 17. Recovery Strategy

Once the threat is contained, recovery begins.

Recovery priorities are based on business criticality.

Example:

### Priority 1

Critical telecommunications services

### Priority 2

Customer authentication and billing

### Priority 3

Customer portals

### Priority 4

Enterprise applications

### Priority 5

Non-critical internal systems

Recovery is performed in a controlled sequence.

Systems are not simply switched back on.

Each system must be validated for:

* Malware
* Unauthorized accounts
* Persistence
* Configuration integrity
* Security controls
* Monitoring

---

# 18. Restore from Trusted Sources

A major concern is whether backups have also been compromised.

The organization therefore validates:

* Backup integrity
* Backup timestamps
* Malware status
* Access controls
* Backup immutability
* Recovery-point validity

Where possible, systems are restored from known-good recovery points.

This connects incident response directly with disaster recovery.

---

# 19. Validate Before Returning to Production

A system is not considered recovered simply because it is technically online.

Validation includes:

* Security testing
* Vulnerability scanning
* Configuration review
* Authentication testing
* Access review
* Monitoring validation
* Business-function testing
* Data-integrity validation

The system is then approved for production.

---

# 20. Monitor for Recurrence

After recovery, heightened monitoring is maintained.

The SOC looks for:

* Repeated authentication attempts
* Suspicious administrative activity
* Malware indicators
* New persistence mechanisms
* Unusual network traffic
* Data-access anomalies

Enhanced monitoring may continue for several weeks.

This reduces the risk of premature closure.

---

# 21. Establish the Incident Risk Register

The GRC team maintains a temporary incident risk register.

Example:

| Risk                   | Likelihood | Impact | Residual Risk | Owner            |
| ---------------------- | ---------: | -----: | ------------- | ---------------- |
| Reinfection            |          4 |      5 | High          | CISO             |
| Data misuse            |          3 |      5 | High          | Privacy          |
| Service disruption     |          3 |      5 | High          | CIO              |
| Regulatory enforcement |          3 |      4 | High          | Legal            |
| Customer churn         |          3 |      4 | Medium        | Business         |
| Supplier recurrence    |          3 |      4 | Medium        | Third-Party Risk |

The register is reviewed during every major incident-management meeting.

---

# 22. Financial Impact Assessment

The Finance and GRC teams estimate the business impact.

Potential costs include:

* Incident response
* Forensic investigation
* External consultants
* System recovery
* Customer communication
* Regulatory penalties
* Legal costs
* Lost revenue
* Customer compensation
* Security improvements
* Overtime
* Business interruption

The initial estimate may be:

**€4 million–€8 million**

The range is refined as more information becomes available.

This gives executives a financial perspective on the incident.

---

# 23. Third-Party Risk

Suppose investigation reveals that one compromised administrative account belonged to a managed-service provider.

The organization immediately assesses:

* Supplier access
* Contractual obligations
* Supplier security controls
* Credential management
* Monitoring
* Privileged access
* Subcontractors
* Incident notification

The event is also recorded as a **third-party risk event**.

This may trigger:

* Supplier remediation
* Contract review
* Enhanced monitoring
* Security assessment
* Executive escalation

---

# 24. Cyber Insurance

Where applicable, the organization activates its cyber-insurance process.

The insurer may require:

* Incident timeline
* Forensic report
* Legal assessment
* Financial estimates
* Evidence of controls
* Incident-response documentation

This reinforces the importance of maintaining accurate records throughout the incident.

---

# 25. Incident Closure Criteria

GlobalConnect defines objective closure criteria.

The incident cannot be closed until:

* Threat is contained.
* Root cause is identified or sufficiently understood.
* Compromised accounts are secured.
* Systems are recovered.
* Monitoring is operational.
* Regulatory obligations are addressed.
* Customer communication is completed where required.
* High-risk residual risks are transferred to the appropriate risk process.
* Corrective actions are assigned.
* Executive management approves closure.

This prevents the organization from declaring victory too early.

---

# 26. Transition from Incident to Problem Management

After immediate response, the organization transitions from:

**Incident Management**

to

**Problem Management and Risk Treatment**

The organization asks:

> Why was this incident possible?

and:

> Why did existing controls fail to prevent or detect it?

This creates the foundation for Part 3 of this section, which focuses specifically on root-cause analysis and corrective action.

---

# 27. Lessons Learned

The post-incident review identifies several weaknesses.

### Identity and Access

Privileged accounts were not sufficiently protected.

### Network Segmentation

Attackers could move between environments.

### Monitoring

Important alerts were not escalated quickly enough.

### Third-Party Access

Supplier privileges were broader than necessary.

### Governance

Business impact assessment began later than technical response.

### Communication

Executive reporting initially contained too much technical information and not enough business impact.

The organization converts each lesson into an actionable improvement.

---

# 28. Executive and Board Review

After stabilization, the CISO presents a final incident report.

The report contains:

### Incident Overview

What happened?

### Business Impact

What services and customers were affected?

### Root Cause

Why did it happen?

### Control Failures

Which controls failed?

### Regulatory Impact

What obligations were triggered?

### Financial Impact

What did the incident cost?

### Recovery

How was the organization restored?

### Residual Risk

What risks remain?

### Corrective Action

What is management doing?

The board focuses on accountability and systemic improvement.

---

# 29. GRC Technology Integration

The incident is integrated into the enterprise GRC platform.

The relationship becomes:

**Security Incident**

↓

**Business Impact**

↓

**Privacy/Regulatory Assessment**

↓

**Enterprise Risk**

↓

**Control Failure**

↓

**Corrective Action**

↓

**Evidence**

↓

**Validation**

↓

**Audit**

This provides end-to-end traceability.

---

# 30. Key Performance Indicators

GlobalConnect establishes incident-response metrics.

| Metric                         |     Example |
| ------------------------------ | ----------: |
| Mean Time to Detect            |  42 minutes |
| Mean Time to Contain           |   3.8 hours |
| Mean Time to Recover           |    19 hours |
| Critical systems affected      |          17 |
| Customers potentially affected | 4.2 million |
| High-risk findings             |          12 |
| Corrective actions             |          38 |
| Actions completed              |         91% |
| Repeat control failures        |           3 |
| Regulatory notifications       |           2 |

Management should avoid using these metrics in isolation.

For example, a low recovery time is not necessarily positive if systems were restored before security validation.

---

# 31. Common Failure Modes

Organizations frequently fail during major incidents because they:

### Lack clear command

Too many people issue conflicting instructions.

### Focus exclusively on technology

Business and regulatory consequences are ignored.

### Communicate too much technical detail

Executives cannot determine what decision they need to make.

### Delay risk assessment

Management does not understand the business consequences quickly enough.

### Ignore business continuity

Technical containment causes unnecessary service disruption.

### Restore systems too quickly

Compromised systems may be reintroduced.

### Fail to document decisions

The organization cannot later demonstrate why important actions were taken.

### Close without corrective action

The same vulnerability can cause another incident.

---

# 32. Final GRC Incident-Management Model

A mature cybersecurity incident-management capability follows:

**Detect**

→ Identify suspicious activity.

**Classify**

→ Determine severity and business significance.

**Contain**

→ Prevent further damage.

**Assess**

→ Determine technical, business, privacy, and regulatory impact.

**Decide**

→ Make risk-based management decisions.

**Communicate**

→ Provide accurate information to stakeholders.

**Recover**

→ Restore critical services securely.

**Validate**

→ Confirm systems are safe and functional.

**Remediate**

→ Address root causes and control weaknesses.

**Assure**

→ Verify that improvements are effective.

The complete governance chain is:

**Cybersecurity Event → Business Risk → Management Decision → Recovery → Corrective Action → Assurance**

---

# 33. Practical GRC Exercise

You are the **Cybersecurity GRC Manager** for a telecommunications organization.

At 02:00, the SOC detects a coordinated attack affecting:

* Identity infrastructure
* Customer portal
* Billing systems
* Internal applications
* Cloud workloads

The investigation indicates:

* Privileged credentials were compromised.
* Attackers moved laterally.
* Several servers were encrypted.
* Approximately 3 million customer records may have been accessed.
* Some critical customer services are unavailable.
* A third-party managed-service provider had privileged access.

Management asks you to coordinate the GRC response.

Develop a complete response covering:

1. Incident classification
2. Crisis activation
3. Incident command
4. Business impact assessment
5. Critical-service identification
6. Risk assessment
7. Containment decisions
8. Regulatory assessment
9. Privacy assessment
10. Third-party assessment
11. Executive reporting
12. Customer communication
13. Recovery priorities
14. Backup validation
15. System restoration
16. Financial impact
17. Enterprise risk updates
18. Incident closure criteria
19. Lessons learned
20. Corrective actions
21. Board reporting
22. Internal audit assurance
23. GRC system integration

Your final assessment should answer:

> **What happened?**

> **What is the business risk?**

> **What decisions must management make now?**

> **What services must be restored first?**

> **What regulatory and privacy obligations exist?**

> **What controls failed?**

> **How will management prevent recurrence?**

The key lesson for a GRC professional is that a major cybersecurity incident is not simply an SOC problem.

It is an **enterprise risk event** requiring coordinated governance across:

**Cybersecurity + Risk + Compliance + Privacy + Legal + Business Continuity + Third-Party Risk + Executive Management + Internal Audit**

A mature organization does not measure incident response only by how quickly the attacker is removed.

It also measures whether the organization:

**understood the business impact, made defensible decisions, met its obligations, restored critical services safely, corrected systemic weaknesses, and reduced the probability of recurrence.**


