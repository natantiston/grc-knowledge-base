# **17.8 Compliance Management Tools**

## **Part 1 – Compliance Obligations Register**

A **Compliance Obligations Register** is a structured GRC tool used to identify, document, track, and manage the legal, regulatory, contractual, and internal requirements that apply to an organization.

For a cybersecurity GRC professional, the register provides a central view of **what the organization is required to comply with, why the requirement applies, who owns it, what controls address it, and whether compliance has been demonstrated**.

The fundamental purpose of the register is to answer:

> **What compliance obligations apply to the organization, and how are those obligations being managed?**

An organization may be subject to requirements from multiple sources, including:

```text
Laws
   ↓
Regulations
   ↓
Regulatory Guidance
   ↓
Industry Requirements
   ↓
Contractual Requirements
   ↓
Customer Requirements
   ↓
Internal Policies and Standards
```

For example, a European organization may need to consider:

```text
GDPR
NIS2
DORA
National Cybersecurity Laws
Sector-Specific Regulations
Customer Security Requirements
Contractual Security Obligations
Internal Security Policies
```

The exact obligations depend on the organization's industry, location, services, customers, size, and regulatory scope.

A compliance obligations register should therefore begin by identifying the **source of the obligation**.

For example:

```text
Obligation ID:
CO-001

Source:
NIS2 Directive

Requirement Area:
Cybersecurity Risk Management

Applicability:
Organization operates within an
in-scope sector and jurisdiction.
```

Another example:

```text
Obligation ID:
CO-002

Source:
GDPR

Requirement Area:
Protection of Personal Data

Applicability:
Organization processes personal data
of individuals within the applicable scope.
```

The register should not simply contain a list of regulations.

A regulation may contain hundreds of individual requirements.

The GRC professional must determine which specific obligations are relevant to the organization.

A practical **Compliance Obligations Register** can contain:

```text
COMPLIANCE OBLIGATIONS REGISTER

Obligation ID:

Requirement Source:

Law / Regulation / Standard:

Requirement Title:

Requirement Reference:

Requirement Description:

Applicability:

Jurisdiction:

Business Unit:

Process / System:

Regulatory Authority:

Compliance Owner:

Control Owner:

Effective Date:

Review Date:

Requirement Frequency:

Applicable Controls:

Evidence Required:

Assessment Method:

Compliance Status:

Risk Level:

Known Gap:

Remediation Action:

Target Date:

Last Assessment:

Next Assessment:

Notes:
```

The first important field is the **Obligation ID**.

Each obligation should have a unique identifier.

For example:

```text
CO-001
CO-002
CO-003
CO-004
```

This allows the obligation to be referenced consistently across the GRC environment.

The next field is the **requirement source**.

For example:

```text
Source:
European Union

Instrument:
NIS2 Directive

Requirement:
Risk-management measures
```

Or:

```text
Source:
European Union

Instrument:
GDPR

Requirement:
Article 32 – Security of Processing
```

The register should capture the specific **requirement reference** where possible.

For example:

```text
Regulation:
GDPR

Reference:
Article 32

Requirement:
Appropriate technical and organizational
measures must be implemented to ensure
a level of security appropriate to risk.
```

This is much more useful than simply recording:

> GDPR compliance.

The GRC professional needs to know exactly which requirement is being managed.

The register should also capture the **requirement description**.

This should summarize the obligation in practical language.

For example:

```text
Requirement:
Organizations must implement appropriate
technical and organizational security measures
based on the risks associated with processing.
```

The description should be clear enough that business and control owners can understand what is expected.

The next critical field is **applicability**.

Not every regulation applies to every organization.

For example:

```text
Regulation:
DORA

Applicability:
Financial entity within DORA scope

Status:
Applicable
```

Another organization may record:

```text
Regulation:
DORA

Applicability:
Organization is not a regulated financial
entity within DORA scope.

Status:
Not Applicable
```

The decision should be documented and supported by a clear rationale.

A mature GRC program should avoid simply marking requirements as "Not Applicable" without explanation.

For example:

```text
Applicability:
Not Applicable

Reason:
Organization does not provide financial
services covered by the regulation.
```

The register should also capture the **jurisdiction**.

For example:

```text
Jurisdiction:
European Union

Country:
Spain

Regulatory Environment:
EU + Spanish national requirements
```

Organizations operating internationally may need multiple jurisdictional registers or a consolidated global register.

For example:

```text
Global Organization
       ↓
EU Requirements
       ↓
US Requirements
       ↓
UK Requirements
       ↓
Middle East Requirements
       ↓
Asia-Pacific Requirements
```

A global organization may therefore have hundreds or thousands of compliance obligations.

The register should identify the **business unit** affected by each obligation.

For example:

```text
Business Unit:
Enterprise Services

Affected Functions:
Cybersecurity
IT
Legal
Procurement
HR
```

This helps determine who needs to participate in compliance activities.

The register should also identify affected **processes and systems**.

For example:

```text
Requirement:
Access Control

Affected Processes:
Identity Management
Joiner/Mover/Leaver
Privileged Access Management

Affected Systems:
IAM Platform
Active Directory
Cloud Identity Platform
```

This creates a connection between the regulatory requirement and the operational environment.

The register should also identify the **regulatory authority** where applicable.

For example:

```text
Regulation:
GDPR

Supervisory Authority:
Applicable Data Protection Authority
```

This information becomes particularly important during regulatory assessments, investigations, or reporting activities.

The next important field is the **compliance owner**.

The compliance owner is responsible for coordinating the organization's response to the obligation.

For example:

```text
Compliance Owner:
Head of GRC

Supporting Owner:
Data Protection Officer
```

The compliance owner may coordinate the assessment while different control owners remain responsible for implementing individual controls.

This distinction is important.

```text
Compliance Owner
       ↓
Coordinates Requirement

Control Owner
       ↓
Operates Control
```

For example:

```text
Requirement:
Security of Processing

Compliance Owner:
DPO / GRC

Control Owners:
CISO
IT Security Manager
IAM Manager
Security Operations Manager
```

The register should also capture the **effective date** of the requirement.

For example:

```text
Effective Date:
17 October 2024
```

This allows the GRC team to determine whether an obligation was already applicable during a particular assessment period.

The register should also contain a **review date**.

For example:

```text
Last Reviewed:
1 August 2026

Next Review:
1 February 2027
```

Regulatory requirements can change.

Therefore, compliance obligations should not be treated as static information.

The GRC team should monitor:

* New laws.
* Regulatory amendments.
* New regulatory guidance.
* Enforcement decisions.
* Changes to applicability.
* Changes in organizational scope.
* Changes in business activities.

A change in the organization's business model may also create new obligations.

For example:

```text
Organization launches a payment service
             ↓
New regulatory analysis
             ↓
Additional compliance obligations
             ↓
New controls / control changes
             ↓
Updated compliance register
```

The register should also capture the **frequency** associated with the requirement.

For example:

```text
Requirement:
Quarterly regulatory reporting

Frequency:
Quarterly
```

Other obligations may be:

```text
Annual
Monthly
Continuous
Event-Driven
Periodic
One-Time
```

The frequency helps determine the compliance monitoring schedule.

One of the most important fields is **Applicable Controls**.

This connects the compliance obligation to the organization's security controls.

For example:

```text
Requirement:
Protect personal data

Applicable Controls:
AC-01 Access Control
DP-03 Data Classification
EN-02 Encryption
IR-04 Data Breach Management
```

This creates the following relationship:

```text
Compliance Requirement
        ↓
Control
        ↓
Evidence
        ↓
Assessment
        ↓
Compliance Result
```

A requirement may map to multiple controls.

Likewise, one control may support multiple compliance obligations.

For example:

```text
Encryption Control
      ↓
GDPR
NIS2
ISO 27001
Customer Requirements
Internal Security Standard
```

This is one of the most important capabilities of a mature GRC program because it prevents duplicated compliance work.

The register should also identify the **evidence required** to demonstrate compliance.

For example:

```text
Requirement:
Periodic access review

Evidence:
Access review reports
Approval records
Exception records
Remediation tickets
```

Another requirement might require:

```text
Incident Reporting

Evidence:
Incident records
Regulatory notifications
Incident timelines
Management approvals
Post-incident reports
```

The evidence requirement should be specific enough to support an assessment.

The register should also identify the **assessment method**.

Examples include:

```text
Document Review
Control Testing
Management Questionnaire
Internal Audit
External Audit
Technical Testing
Sampling
Automated Monitoring
Regulatory Assessment
```

For example:

```text
Requirement:
Privileged Access Review

Assessment Method:
Control testing + evidence review
```

Another requirement may use:

```text
Requirement:
Security Awareness Training

Assessment Method:
Document review + training completion
analysis + sampling
```

The next important field is **compliance status**.

A practical status model may include:

```text
Compliant
Partially Compliant
Non-Compliant
Not Assessed
Not Applicable
Under Remediation
```

For example:

```text
Requirement:
Annual Security Awareness Training

Status:
Compliant
```

Another:

```text
Requirement:
Third-Party Risk Assessment

Status:
Partially Compliant
```

Another:

```text
Requirement:
Regulatory Reporting

Status:
Under Remediation
```

The status should be supported by evidence.

A GRC professional should avoid assigning a compliance status simply because a control owner says:

> We comply.

The status should be based on the organization's assessment methodology.

The register should also contain a **risk level**.

For example:

```text
Risk:
High
```

A compliance gap associated with a critical regulatory obligation may represent significant organizational risk.

The GRC team should consider:

* Regulatory penalties.
* Legal exposure.
* Operational impact.
* Customer impact.
* Security impact.
* Reputational impact.
* Business interruption.

A compliance gap should therefore be connected to the broader risk management process.

For example:

```text
Compliance Gap
       ↓
Risk
       ↓
Risk Assessment
       ↓
Treatment Decision
       ↓
Remediation
```

The register should also identify **known gaps**.

For example:

```text
Requirement:
Third-party security assessment

Gap:
20% of high-risk suppliers have not yet
completed the required assessment.
```

This should lead to a documented remediation activity.

For example:

```text
Remediation:
Complete security assessments for all
remaining high-risk suppliers.

Owner:
Third-Party Risk Manager

Target:
31 December 2026
```

The remediation should have a clear owner and target date.

This allows the GRC team to track compliance improvement over time.

The register should also record the **last assessment**.

For example:

```text
Last Assessment:
15 July 2026

Result:
Partially Compliant
```

And:

```text
Next Assessment:
15 January 2027
```

This supports recurring compliance monitoring.

A practical register might look like this:

| ID     | Requirement            | Source                 | Owner       | Status              | Risk   | Next Review |
| ------ | ---------------------- | ---------------------- | ----------- | ------------------- | ------ | ----------- |
| CO-001 | Security of Processing | GDPR Art. 32           | DPO         | Compliant           | Medium | Jan 2027    |
| CO-002 | Cyber Risk Management  | NIS2                   | CISO        | Partially Compliant | High   | Oct 2026    |
| CO-003 | Access Management      | Internal Standard      | IAM Manager | Compliant           | Medium | Dec 2026    |
| CO-004 | Incident Reporting     | Regulatory Requirement | SOC Manager | Under Remediation   | High   | Sep 2026    |

The register can become considerably more detailed in a mature GRC environment.

For example:

```text
CO-002
      ↓
NIS2 Requirement
      ↓
Risk Management
      ↓
ISO 27001 Controls
      ↓
NIST CSF Functions
      ↓
Internal Controls
      ↓
Evidence
      ↓
Assessment
      ↓
Gap
      ↓
Remediation
```

This demonstrates how the compliance obligations register can serve as the foundation for compliance mapping.

The GRC professional should also maintain **regulatory change tracking**.

For example:

```text
Regulatory Change Identified
        ↓
Impact Analysis
        ↓
Applicability Assessment
        ↓
Register Updated
        ↓
Control Mapping Updated
        ↓
Gap Assessment
        ↓
Remediation
```

Suppose a regulator introduces a new requirement for cybersecurity incident reporting.

The GRC team should not simply add the new regulation to the register.

The team should determine:

```text
Does it apply?

Which business units are affected?

Which processes are affected?

Which systems are affected?

Which controls address it?

What evidence is required?

Are there gaps?

Who owns remediation?
```

This transforms regulatory monitoring into actionable GRC activity.

The register should also support **compliance obligation prioritization**.

For example:

```text
Critical:
Legal / regulatory requirement
with immediate business impact

High:
Major regulatory requirement
with significant risk

Medium:
Important contractual or internal
requirement

Low:
Lower-impact organizational requirement
```

The organization should define its own classification criteria.

Priority may be based on:

* Regulatory impact.
* Business criticality.
* Enforcement exposure.
* Customer impact.
* Security risk.
* Deadline.
* Scope.
* Existing control maturity.

The register should also distinguish between **mandatory obligations** and **voluntary frameworks**.

For example:

```text
Mandatory:
Law
Regulation
Binding regulatory requirement
Contractual requirement

Voluntary:
Industry framework
Best-practice framework
Optional certification
```

ISO/IEC 27001, for example, may be a contractual, certification, or organizational requirement depending on the organization's circumstances.

The GRC professional should therefore document the actual basis for applicability rather than assuming that every framework is legally mandatory.

The compliance obligations register can also support **audit preparation**.

Before an audit, the GRC team can filter the register for:

```text
Applicable Obligations
        ↓
Mapped Controls
        ↓
Required Evidence
        ↓
Assessment Status
        ↓
Open Gaps
        ↓
Audit Readiness
```

For example:

```text
Audit:
ISO 27001 Certification Audit

Filter:
ISO-related obligations

Result:
42 applicable requirements
38 compliant
3 partially compliant
1 under remediation
```

This gives management an immediate view of readiness.

The register can also be used during management reviews.

A dashboard may show:

```text
Total Obligations:
185

Compliant:
142

Partially Compliant:
25

Under Remediation:
12

Not Assessed:
4

Not Applicable:
2
```

Management can then focus attention on the most significant gaps.

A mature GRC environment may automate reminders.

For example:

```text
90 Days Before Review
        ↓
Automated Notification

30 Days Before Review
        ↓
Escalation

Review Date
        ↓
Compliance Task

Overdue
        ↓
Management Escalation
```

Automation can reduce the risk of regulatory reviews being missed.

However, automation does not replace regulatory interpretation.

The GRC team still needs qualified professionals to determine whether a new requirement applies and how it should be implemented.

The register should also maintain **historical records**.

For example:

```text
Requirement Status:

2024:
Compliant

2025:
Partially Compliant

2026:
Compliant
```

This allows the organization to demonstrate improvement and understand recurring weaknesses.

Version history may include:

```text
Date
Change
Changed By
Reason
Approval
```

For example:

```text
1 August 2026
Added new regulatory requirement

Owner:
GRC Manager

Reason:
Regulatory amendment

Approved:
CISO
```

This provides governance over the register itself.

The Compliance Obligations Register should ultimately become a **living GRC record**, not a static spreadsheet that is updated only before an audit.

Its lifecycle should be:

```text
Identify
   ↓
Assess Applicability
   ↓
Document
   ↓
Map
   ↓
Assign Ownership
   ↓
Assess
   ↓
Monitor
   ↓
Remediate
   ↓
Review
   ↓
Update
```

The key principle is:

> **A Compliance Obligations Register provides the authoritative inventory of legal, regulatory, contractual, and internal requirements applicable to an organization and establishes the foundation for mapping those obligations to controls, evidence, assessments, risks, and remediation activities.**

**17.8 Compliance Management Tools**

**Part 2 – Regulatory Requirement Mapping**

Regulatory Requirement Mapping is the process of connecting specific legal, regulatory, contractual, and compliance requirements to the security controls, policies, procedures, processes, and evidence that demonstrate how the organization addresses those requirements.

The purpose is not simply to create a list of regulations.

The objective is to establish a clear relationship between:

```text
Regulatory Requirement
        ↓
Compliance Obligation
        ↓
Control
        ↓
Control Activity
        ↓
Evidence
        ↓
Assessment
        ↓
Compliance Status
        ↓
Gap / Remediation
```

For example, an organization may have a regulatory requirement requiring appropriate access controls.

The GRC professional should be able to trace that requirement through the organization's control environment:

```text
Regulatory Requirement
        ↓
Access must be restricted to authorized users
        ↓
AC-01 Access Control Policy
        ↓
AC-05 Privileged Access Review
        ↓
IAM System
        ↓
Access Review Evidence
        ↓
Control Testing
        ↓
Compliance Assessment
```

This traceability is one of the most important capabilities of a mature GRC program.

Without regulatory mapping, organizations may perform the same assessment multiple times.

For example:

```text
GDPR
NIS2
ISO 27001
Customer Requirement
Internal Security Standard
```

may all contain requirements related to access control.

Instead of assessing the same access control process separately for every requirement, the organization can establish a common control and map the different requirements to it.

```text
GDPR Requirement ─────┐
NIS2 Requirement ─────┤
ISO 27001 Requirement ┤
Customer Requirement ─┤──→ Access Control
Internal Requirement ─┘
```

This is commonly referred to as a **common control approach**.

A practical Regulatory Requirement Mapping Template can contain:

```text
REGULATORY REQUIREMENT MAPPING

Mapping ID:

Obligation ID:

Regulation / Source:

Requirement Reference:

Requirement Description:

Applicability:

Jurisdiction:

Business Unit:

Requirement Owner:

Control ID:

Control Name:

Control Objective:

Policy / Procedure:

Control Activity:

Evidence:

Assessment Method:

Compliance Status:

Control Effectiveness:

Gap:

Risk:

Remediation:

Remediation Owner:

Target Date:

Last Reviewed:

Next Review:

Mapping Notes:
```

The first step is to identify the **specific regulatory requirement**.

For example:

```text
Source:
GDPR

Reference:
Article 32

Requirement Area:
Security of Processing
```

The GRC professional should then translate the requirement into an actionable compliance statement.

For example:

```text
Requirement:

The organization must implement
appropriate technical and organizational
measures to provide an appropriate level
of security for personal data processing.
```

The next step is to identify the organization's **control objectives** that address the requirement.

For example:

```text
Regulatory Requirement:
Protect personal data

Control Objectives:
Prevent unauthorized access
Protect data confidentiality
Protect data integrity
Support availability
Detect security events
```

The mapping should then identify the specific controls.

For example:

```text
Control ID    Control
------------------------------------------------
AC-01         Access Control
AC-02         Privileged Access Management
DP-01         Data Classification
EN-01         Encryption
IR-01         Incident Management
BC-01         Backup and Recovery
```

This creates a traceable relationship between the regulatory requirement and the organization's security control environment.

The mapping should distinguish between **direct** and **indirect** control relationships.

A direct relationship means the control specifically addresses the requirement.

For example:

```text
Requirement:
Privileged access must be appropriately controlled.

Control:
Privileged Access Management
```

An indirect relationship means the control supports the requirement but does not directly satisfy it.

For example:

```text
Requirement:
Protect personal data.

Control:
Security Awareness Training
```

Security awareness may contribute to compliance but may not independently satisfy the complete requirement.

The distinction is important when assessing compliance.

A common mistake is to map a large number of controls to a requirement without determining whether those controls actually address the requirement.

For example:

```text
GDPR Article 32
        ↓
50 Controls
```

This may look comprehensive but could actually make the control environment more difficult to manage.

A better approach is:

```text
Requirement
     ↓
Relevant Control Objective
     ↓
Minimum Necessary Controls
```

The GRC professional should focus on **coverage and relevance**, not the number of mappings.

Regulatory mapping should also identify **control ownership**.

For example:

```text
Requirement:
Access Control

Compliance Owner:
GRC Manager

Control Owner:
IAM Manager

Supporting Owner:
IT Operations
```

This prevents ambiguity when a regulatory requirement is mapped to multiple controls owned by different teams.

The mapping should also identify the **policy or procedure** supporting the control.

For example:

```text
Requirement:
Access must be restricted.

Policy:
Access Control Policy

Procedure:
User Access Management Procedure

Standard:
Privileged Access Standard

Control:
Quarterly Access Review
```

This creates a hierarchy:

```text
Requirement
     ↓
Policy
     ↓
Standard
     ↓
Procedure
     ↓
Control
     ↓
Evidence
```

Each layer serves a different purpose.

The regulation establishes the external obligation.

The policy establishes organizational direction.

The standard establishes specific mandatory requirements.

The procedure describes how activities are performed.

The control provides the mechanism for managing the risk.

Evidence demonstrates that the control operated.

This hierarchy is particularly useful during audits.

An auditor may ask:

> How does the organization address this regulatory requirement?

The GRC professional should be able to demonstrate:

```text
Regulatory Requirement
        ↓
Internal Policy
        ↓
Security Standard
        ↓
Procedure
        ↓
Control
        ↓
Evidence
```

This provides a defensible audit trail.

Regulatory mapping should also capture the **evidence required**.

For example:

```text
Requirement:
Periodic privileged access review

Control:
Quarterly Privileged Access Review

Evidence:
Access review report
Approval records
Exception register
Access removal tickets
```

The evidence should demonstrate actual operation of the control rather than simply proving that a policy exists.

For example:

```text
Policy Document
        ↓
Demonstrates Design

Access Review Report
        ↓
Demonstrates Operation

Testing Results
        ↓
Demonstrates Effectiveness
```

The mapping should therefore support evidence traceability.

A mature mapping may use unique identifiers for every object.

For example:

```text
Requirement:
REG-GDPR-32

Control:
CTRL-AC-05

Policy:
POL-AC-001

Procedure:
PROC-AC-003

Evidence:
EVD-2026-045

Assessment:
ASM-2026-018

Finding:
FND-2026-007
```

This allows the GRC professional to trace a requirement through the complete control lifecycle.

Regulatory mapping can also be represented as a matrix.

| Requirement              | Control | Policy                   | Evidence          | Status              |
| ------------------------ | ------- | ------------------------ | ----------------- | ------------------- |
| GDPR Art. 32             | AC-01   | Access Control Policy    | Access Review     | Compliant           |
| GDPR Art. 32             | EN-01   | Encryption Standard      | Encryption Report | Compliant           |
| NIS2 Risk Management     | RM-01   | Risk Management Policy   | Risk Register     | Partially Compliant |
| NIS2 Incident Management | IR-01   | Incident Response Policy | Incident Records  | Compliant           |

A more detailed matrix may include control effectiveness and gaps.

| Requirement   | Control  | Effectiveness       | Compliance          | Gap                 |
| ------------- | -------- | ------------------- | ------------------- | ------------------- |
| Requirement A | CTRL-001 | Effective           | Compliant           | None                |
| Requirement B | CTRL-002 | Partially Effective | Partially Compliant | Incomplete coverage |
| Requirement C | CTRL-003 | Ineffective         | Non-Compliant       | Control failure     |

This distinction is important because **control effectiveness and compliance status are related but not identical**.

For example:

```text
Control:
Effective

Compliance:
Non-Compliant
```

This can happen when the control works as designed but does not completely satisfy a regulatory requirement.

Likewise:

```text
Control:
Partially Effective

Compliance:
Compliant
```

may occur where the organization has multiple controls collectively satisfying a requirement despite weaknesses in one individual control.

The assessment methodology should define how these situations are handled.

Regulatory mapping should also consider **multiple controls supporting one requirement**.

For example:

```text
Requirement:
Protect sensitive information.

Controls:
Data Classification
Access Control
Encryption
DLP
Security Monitoring
Incident Response
```

The GRC professional should determine whether all controls are necessary and how they collectively address the requirement.

This is particularly useful for broad regulatory requirements that cannot be satisfied by one technical control.

The opposite situation is also important:

```text
One Control
     ↓
Multiple Requirements
```

For example:

```text
Security Incident Management Control
        ↓
GDPR
NIS2
ISO 27001
Customer Requirements
Internal Policy
```

This allows the organization to leverage one control assessment across multiple compliance obligations.

However, the GRC professional must verify that the control actually addresses the relevant parts of each requirement.

A single control should not automatically be considered sufficient merely because it is mapped to several frameworks.

Regulatory mapping should also identify **partial coverage**.

For example:

```text
Requirement:
All critical suppliers must undergo
security due diligence.

Control:
Third-Party Risk Assessment

Coverage:
85%

Gap:
15% of critical suppliers have not
completed the required assessment.
```

The mapping should record:

```text
Coverage:
Partial

Compliance:
Partially Compliant

Risk:
High

Remediation:
Complete outstanding supplier assessments.
```

This provides much more useful information than simply marking the requirement as "Compliant" or "Non-Compliant."

The GRC team should also consider **control inheritance**.

For example, a cloud service provider may provide certain security controls that the organization relies upon.

```text
Cloud Provider
      ↓
Physical Security
      ↓
Infrastructure Security
      ↓
Organization
      ↓
Application Security
      ↓
Identity Management
```

The organization should identify which controls are:

```text
Organization Responsibility
Cloud Provider Responsibility
Shared Responsibility
```

This is especially important for cloud services.

For example:

```text
Control:
Physical Data Center Security

Responsibility:
Cloud Provider

Evidence:
Independent Assurance Report
```

Whereas:

```text
Control:
Customer Identity Management

Responsibility:
Organization

Evidence:
IAM Configuration
Access Reviews
```

And:

```text
Control:
Cloud Configuration Security

Responsibility:
Shared
```

The mapping should document these responsibilities clearly.

Regulatory requirement mapping should also account for **contractual obligations**.

For example, a customer contract may require:

```text
Annual penetration testing
ISO 27001 certification
24-hour incident notification
Encryption of customer data
Third-party risk assessments
```

These requirements should be incorporated into the organization's compliance environment where applicable.

For example:

```text
Contract Requirement
        ↓
Compliance Obligation
        ↓
Control Mapping
        ↓
Evidence
        ↓
Contract Compliance Assessment
```

This creates a unified compliance management approach rather than managing regulatory and contractual requirements separately.

The mapping process can also identify **control gaps**.

For example:

```text
Requirement:
Critical vulnerabilities must be remediated
within 15 days.

Existing Control:
Vulnerability Management

Assessment:
Partially Effective

Gap:
Critical vulnerabilities are sometimes
remediated after the 15-day requirement.
```

The GRC team can then create a remediation plan.

```text
Gap
 ↓
Root Cause
 ↓
Risk Assessment
 ↓
Remediation Action
 ↓
Owner
 ↓
Target Date
 ↓
Retest
```

Regulatory mapping should therefore be closely connected to the organization's risk and issue management processes.

A practical mapping workflow is:

```text
Identify Requirement
        ↓
Interpret Requirement
        ↓
Determine Applicability
        ↓
Identify Control Objective
        ↓
Map Existing Controls
        ↓
Validate Mapping
        ↓
Identify Evidence
        ↓
Assess Control
        ↓
Determine Compliance Status
        ↓
Identify Gaps
        ↓
Create Remediation
        ↓
Monitor
```

The **interpretation stage** is particularly important.

A regulation may contain broad language that requires professional interpretation.

For example:

> Appropriate technical and organizational measures.

The GRC team must determine what this means within the organization's specific context.

This may involve consultation with:

```text
Legal
Privacy
Cybersecurity
Risk
Compliance
Business Owners
Technical Specialists
```

The GRC professional should avoid independently making legal interpretations where legal advice is required.

Instead, the GRC function should translate validated regulatory requirements into actionable control requirements.

Regulatory mapping should also be reviewed whenever there is a **regulatory change**.

For example:

```text
Regulatory Amendment
        ↓
Requirement Changed
        ↓
Mapping Review
        ↓
Control Impact Assessment
        ↓
Gap Analysis
        ↓
Control Changes
        ↓
Evidence Requirements Updated
```

This prevents the organization from continuing to rely on outdated mappings.

A practical example can demonstrate the process.

Consider a regulatory requirement concerning incident management.

```text
Requirement:
Organizations must maintain appropriate
processes for handling cybersecurity incidents.
```

The GRC team maps this requirement to:

```text
Control:
Security Incident Management

Policy:
Incident Response Policy

Procedure:
Security Incident Response Procedure

Supporting Controls:
Security Monitoring
Incident Classification
Incident Escalation
Regulatory Notification
Post-Incident Review
```

Evidence may include:

```text
Incident Response Plan
Incident Tickets
Incident Classification Records
Escalation Records
Regulatory Notifications
Post-Incident Reports
Exercise Results
```

The assessment may determine:

```text
Control Design:
Effective

Implementation:
Effective

Evidence:
Available

Operating Effectiveness:
Partially Effective
```

The compliance status may therefore be:

```text
Partially Compliant
```

The gap could be:

> Regulatory notification procedures have been documented, but evidence of periodic testing of the notification process is incomplete.

The remediation could be:

```text
Action:
Conduct and document an incident notification
exercise.

Owner:
Security Operations Manager

Target:
30 November 2026
```

The mapping is then updated after remediation.

This demonstrates how regulatory mapping connects requirements with operational security activities.

A mature organization can also create a **cross-framework control mapping**.

For example:

```text
Common Control:
Identity and Access Management

ISO 27001:
Access Control Requirements

NIST CSF:
Protect / Identity Management

NIS2:
Access Control and Security Measures

GDPR:
Security of Processing

Internal Standard:
IAM-STD-001
```

This enables the organization to manage common controls across multiple frameworks.

The result may look like:

```text
                 ┌── ISO 27001
                 │
                 ├── NIST CSF
Common Control ──┼── NIS2
                 │
                 ├── GDPR
                 │
                 └── Customer Requirements
```

This is often much more efficient than maintaining completely separate compliance programs.

However, the GRC professional should still maintain the specific requirement references for each framework.

The mapping should not reduce different regulatory requirements into a generic statement such as:

> Access control is compliant.

Instead, it should demonstrate:

```text
Requirement A
    ↓
Control A
    ↓
Evidence A

Requirement B
    ↓
Control A + Control B
    ↓
Evidence A + Evidence B
```

This provides stronger assurance.

Regulatory mapping should also support **audit traceability**.

An auditor may select a regulatory requirement and ask:

> Show me how this requirement is addressed.

The GRC professional should be able to navigate from:

```text
Requirement
   ↓
Control
   ↓
Policy
   ↓
Procedure
   ↓
Evidence
   ↓
Assessment
   ↓
Finding
   ↓
Remediation
```

The reverse should also be possible.

An auditor may select a control and ask:

> Which regulatory requirements does this control support?

The GRC professional should be able to show:

```text
Control
   ↓
GDPR Requirement
NIS2 Requirement
ISO 27001 Requirement
Customer Requirement
Internal Requirement
```

This **bidirectional traceability** is a key characteristic of a mature GRC program.

The mapping should also support reporting.

For example:

```text
Regulatory Requirements:
250

Mapped:
238

Unmapped:
12

Coverage:
95.2%
```

The GRC team can then investigate the 12 unmapped requirements.

Another dashboard may show:

```text
Compliant:
185

Partially Compliant:
32

Non-Compliant:
11

Under Assessment:
10

Not Applicable:
12
```

Management can then focus on the most significant compliance gaps.

A risk-based dashboard may further show:

```text
High-Risk Compliance Gaps:
6

Medium-Risk:
18

Low-Risk:
19
```

This helps management prioritize resources.

The key principle is:

> **Regulatory requirement mapping creates traceability between external obligations and the organization's internal control environment, allowing GRC professionals to demonstrate coverage, identify gaps, reduce duplicate compliance work, and maintain an auditable connection between requirements, controls, evidence, risk, and remediation.**

**17.8 Compliance Management Tools**

**Part 3 – Compliance Assessment Template**

A **Compliance Assessment Template** is a structured tool used to evaluate whether an organization has implemented and is operating the controls and processes necessary to satisfy its applicable legal, regulatory, contractual, and internal compliance requirements.

The Compliance Obligations Register identifies **what requirements apply**.

Regulatory Requirement Mapping identifies **which controls address those requirements**.

The Compliance Assessment determines **whether those controls actually provide sufficient compliance coverage**.

The relationship can therefore be represented as:

```text
Compliance Obligation
        ↓
Regulatory Requirement Mapping
        ↓
Applicable Controls
        ↓
Compliance Assessment
        ↓
Evidence Review
        ↓
Compliance Determination
        ↓
Gap / Risk / Remediation
```

A practical compliance assessment should not simply ask:

> Are we compliant?

That question is too broad.

Instead, the assessment should determine:

```text
Is the requirement applicable?

Is the requirement understood?

Are appropriate controls defined?

Are the controls implemented?

Are the controls operating?

Is sufficient evidence available?

Are there exceptions?

Are there gaps?

Is the remaining risk acceptable?

What is the final compliance status?
```

A practical **Compliance Assessment Template** can contain:

```text
COMPLIANCE ASSESSMENT

Assessment ID:

Assessment Name:

Compliance Obligation:

Regulation / Requirement:

Requirement Reference:

Assessment Scope:

Jurisdiction:

Business Unit:

Compliance Owner:

Control Owner:

Assessment Period:

Assessment Date:

Requirement Description:

Applicable Controls:

Control Objectives:

Assessment Criteria:

Evidence Required:

Evidence Reviewed:

Assessment Method:

Control Design:

Control Implementation:

Operating Effectiveness:

Compliance Status:

Gap:

Risk:

Finding:

Remediation:

Remediation Owner:

Target Date:

Assessor:

Management Response:

Approval:

Next Assessment Date:

Assessment Notes:
```

The first step is to define the **assessment scope**.

For example:

```text
Assessment:

NIS2 Cybersecurity Compliance Assessment

Scope:

Enterprise IT
Security Operations
Cloud Infrastructure
Identity Management
Third-Party Risk
Incident Management

Assessment Period:

January–December 2026
```

The scope should clearly identify what is included and what is excluded.

For example:

```text
In Scope:
Corporate IT
Critical Applications
Cloud Infrastructure

Out of Scope:
Subsidiary X

Reason:
Separate legal entity with independent
security governance.
```

Clearly documenting scope prevents disagreements later about what the assessment actually covered.

The next step is to identify the **specific requirement being assessed**.

For example:

```text
Requirement Source:
NIS2

Requirement Area:
Cybersecurity Risk Management

Requirement Reference:
Applicable regulatory provision

Requirement:
Organizations must implement appropriate
measures to manage cybersecurity risks.
```

The GRC professional should use the organization's approved regulatory interpretation rather than relying on an informal interpretation of the law.

The assessment should then identify the **applicable controls**.

For example:

```text
Requirement:
Cybersecurity Risk Management

Mapped Controls:

RM-01 Enterprise Risk Assessment
RM-02 Risk Treatment
VM-01 Vulnerability Management
IR-01 Incident Management
TPRM-01 Third-Party Risk Management
BC-01 Business Continuity
```

The assessment should evaluate each control individually before determining the overall compliance position.

For example:

```text
Control:
RM-01

Control Objective:
Identify and assess cybersecurity risks.

Design:
Effective

Implementation:
Effective

Operating Effectiveness:
Effective

Compliance Contribution:
Sufficient
```

The next important component is the **assessment criteria**.

Assessment criteria define what the assessor expects to see.

For example:

```text
Requirement:
Critical vulnerabilities must be managed
within defined timeframes.

Assessment Criteria:

1. Vulnerability management process exists.
2. Critical assets are identified.
3. Vulnerabilities are periodically assessed.
4. Critical vulnerabilities have defined
   remediation timelines.
5. Exceptions are documented.
6. Remediation is monitored.
7. Evidence demonstrates operation.
```

This makes the assessment more objective.

Without defined criteria, different assessors may reach different conclusions.

The assessment criteria should be based on:

```text
Regulatory Requirement
        +
Internal Policies
        +
Control Objectives
        +
Assessment Methodology
```

The next stage is **evidence collection**.

Evidence should demonstrate that the organization actually meets the requirement.

For example:

```text
Requirement:
Periodic access review

Evidence:

Access review reports
Approval records
Exception records
Access removal tickets
IAM system logs
```

The assessor should record exactly what evidence was reviewed.

For example:

```text
Evidence ID:
EVD-2026-045

Evidence:
Q2 Privileged Access Review Report

Date:
30 June 2026

Source:
IAM Platform

Reviewed By:
GRC Analyst

Result:
Satisfactory
```

This creates traceability.

The assessment should also document the **assessment method**.

Common methods include:

```text
Document Review
Interviews
Management Questionnaire
Evidence Review
Sampling
Control Testing
Technical Validation
Observation
Automated Monitoring
Internal Audit
External Assessment
```

A regulatory requirement may require more than one assessment method.

For example:

```text
Security Awareness Requirement

Document Review
       +
Training Records Review
       +
Employee Sampling
       +
Phishing Simulation Results
```

This provides stronger assurance than relying only on a policy document.

The assessment should distinguish between **control design**, **implementation**, and **operating effectiveness**.

For example:

```text
Control Design
      ↓
Is the control appropriately designed?

Implementation
      ↓
Has the control been implemented?

Operating Effectiveness
      ↓
Has the control operated as intended?
```

A control may be well designed but not implemented.

For example:

```text
Policy:
Quarterly access reviews are required.

Reality:
No access reviews have been performed.
```

The design may be appropriate, but implementation is deficient.

Another situation is:

```text
Designed:
Effective

Implemented:
Effective

Operating:
Partially Effective
```

This may occur when the control operates but fails periodically.

The assessment template should therefore capture these dimensions separately.

A practical assessment section may look like:

```text
Control Design:
[ ] Effective
[ ] Partially Effective
[ ] Ineffective

Implementation:
[ ] Implemented
[ ] Partially Implemented
[ ] Not Implemented

Operating Effectiveness:
[ ] Effective
[ ] Partially Effective
[ ] Ineffective
[ ] Not Tested
```

The assessor should also record **assessment observations**.

For example:

```text
Observation:

The organization has established a formal
quarterly privileged access review process.
Evidence confirmed that reviews were completed
for Q1 and Q2. However, several cloud
administrator accounts were excluded from
the Q2 review.
```

The observation should be factual and evidence-based.

The assessor should then determine whether the observation represents a **compliance gap**.

For example:

```text
Requirement:
All privileged accounts must be reviewed.

Observation:
Cloud administrator accounts excluded.

Conclusion:
Partial compliance.
```

The assessment should distinguish between:

```text
Observation
Finding
Compliance Gap
Risk
```

These terms are related but not identical.

An observation is something identified during the assessment.

A finding represents a condition requiring attention.

A compliance gap means the organization does not fully satisfy the applicable requirement.

Risk represents the potential consequence associated with the gap.

For example:

```text
Observation:
10 privileged accounts were not reviewed.

Compliance Gap:
Required review coverage was incomplete.

Risk:
Unauthorized privileged access may remain
undetected.

Finding:
Privileged access review coverage is incomplete.
```

The assessment should also identify **exceptions**.

For example:

```text
Exception:

Legacy application does not support MFA.

Reason:

Technical limitation.

Compensating Control:

Network segmentation and enhanced monitoring.

Approval:

CISO

Expiry:

31 December 2026
```

An exception should have a defined lifecycle.

```text
Identify
   ↓
Assess
   ↓
Approve
   ↓
Document
   ↓
Monitor
   ↓
Expire / Renew / Remediate
```

The assessment should determine whether an exception affects compliance.

For example:

```text
Requirement:
MFA required

Exception:
Approved for legacy system

Compliance:
Partially Compliant

Risk:
High

Remediation:
Application modernization
```

The existence of an approved exception does not automatically mean the regulatory requirement has been satisfied.

The organization should determine the appropriate compliance treatment based on the applicable requirement and its approved assessment methodology.

The template should also capture **management responses**.

For example:

```text
Management Response:

The organization acknowledges the identified
gap and has approved a remediation project to
integrate the remaining cloud administrator
accounts into the quarterly access review process.
```

Management responses provide accountability for remediation.

The assessment should then determine the overall **compliance status**.

A practical status model may include:

```text
Compliant
Partially Compliant
Non-Compliant
Not Assessed
Not Applicable
Under Remediation
```

For example:

```text
Requirement:
Annual security awareness training

Assessment:
Training completed for 98% of employees.

Status:
Partially Compliant
```

The assessor should document why the requirement was not considered fully compliant.

For example:

```text
Reason:

2% of employees had not completed the
mandatory training within the required period.
```

The compliance status should be supported by objective evidence.

A useful assessment structure is:

| Assessment Area           | Result              | Evidence              |
| ------------------------- | ------------------- | --------------------- |
| Requirement Applicability | Applicable          | Regulatory analysis   |
| Control Design            | Effective           | Policy and procedure  |
| Implementation            | Effective           | System configuration  |
| Operating Effectiveness   | Partially Effective | Sampling results      |
| Evidence Availability     | Satisfactory        | Assessment records    |
| Compliance Status         | Partially Compliant | Assessment conclusion |

The assessor should also record the **assessment rationale**.

For example:

```text
Assessment Conclusion:

The organization has implemented an effective
privileged access management process. However,
the assessment identified incomplete coverage
of cloud administrator accounts. The control
therefore provides partial coverage of the
regulatory requirement.
```

A good assessment conclusion should explain:

```text
What was assessed
What evidence was reviewed
What was identified
Why the conclusion was reached
What remains unresolved
```

The assessment should also determine whether a **risk assessment** is required.

For example:

```text
Compliance Gap
      ↓
Risk Evaluation
      ↓
Likelihood
Impact
Existing Controls
Residual Risk
      ↓
Risk Treatment
```

A regulatory gap may create significant risk even when the immediate technical issue appears small.

For example:

```text
Gap:
One regulatory reporting process is not
tested regularly.

Potential Impact:
Delayed regulatory notification.

Risk:
High
```

The GRC professional should therefore avoid treating compliance as a simple pass/fail exercise.

Compliance assessment should be connected to enterprise risk management.

The assessment should also document **remediation actions**.

For example:

```text
Gap:

Incomplete privileged access review coverage.

Remediation:

Integrate cloud administrator accounts
into the enterprise access review process.

Owner:

IAM Manager

Target Date:

31 December 2026

Priority:

High
```

The remediation should be tracked until closure.

A practical lifecycle is:

```text
Assessment
    ↓
Gap Identified
    ↓
Finding Created
    ↓
Risk Assessed
    ↓
Remediation Assigned
    ↓
Remediation Implemented
    ↓
Evidence Submitted
    ↓
Retesting
    ↓
Finding Closed
```

The assessor should not close a compliance gap merely because management states that remediation has been completed.

Objective evidence should be reviewed.

For example:

```text
Management Statement:
"All cloud accounts are now included."

Required Verification:
Updated access review report
System configuration
Review evidence
Sampling
```

This provides independent confirmation.

The assessment template should also support **sampling**.

For example:

```text
Population:
1,250 privileged accounts

Sample:
40 accounts

Testing:
Access authorization
Business justification
Manager approval
Review completion
Removal where required
```

Sampling methodology should be documented.

For example:

```text
Population:
1,250

Sample:
40

Sampling Method:
Risk-based random sample

Rationale:
Higher-risk privileged accounts were
weighted more heavily.
```

This allows the assessment to be reproduced and reviewed.

The assessment should also record **limitations**.

For example:

```text
Assessment Limitation:

The assessment was performed using evidence
available as of 31 July 2026. Newly deployed
systems after this date were not included.
```

This is important for audit defensibility.

A compliance assessment should also identify **dependencies**.

For example:

```text
Requirement:
Third-party security monitoring

Dependency:
Cloud Service Provider

Evidence:
Independent assurance report
```

The organization may depend on external providers to satisfy part of a requirement.

The assessor should determine whether sufficient assurance exists over those external dependencies.

The assessment can also include a **maturity dimension**.

For example:

```text
Level 1:
Ad Hoc

Level 2:
Developing

Level 3:
Defined

Level 4:
Managed

Level 5:
Optimized
```

For example:

```text
Compliance Requirement:
Third-Party Risk Management

Compliance:
Partially Compliant

Maturity:
Level 2 – Developing
```

Compliance status and maturity should remain separate.

An organization may be compliant with a requirement but still have a relatively immature process.

Conversely, an organization may have a mature process but still fail a specific regulatory requirement.

This distinction is important for GRC reporting.

The assessment template should also support **multiple requirements within one assessment**.

For example:

```text
Assessment:
NIS2 Cybersecurity Assessment

Requirements:
REQ-001 Risk Management
REQ-002 Incident Management
REQ-003 Business Continuity
REQ-004 Supply Chain Security
REQ-005 Access Control
```

Each requirement can have its own assessment result.

```text
REQ-001:
Compliant

REQ-002:
Partially Compliant

REQ-003:
Compliant

REQ-004:
Non-Compliant

REQ-005:
Compliant
```

The overall assessment can then provide a consolidated view.

For example:

```text
Total Requirements:
5

Compliant:
3

Partially Compliant:
1

Non-Compliant:
1
```

However, the overall result should not simply be calculated mathematically.

Risk and regulatory significance should be considered.

For example:

```text
4 Low-Risk Requirements:
Compliant

1 Critical Requirement:
Non-Compliant
```

The assessment should still be treated as requiring significant management attention.

This is why risk-based compliance assessment is important.

A mature compliance assessment process should therefore consider:

```text
Requirement Criticality
        +
Business Impact
        +
Regulatory Exposure
        +
Control Effectiveness
        +
Residual Risk
```

The assessment results can then be presented to management through dashboards.

For example:

```text
Compliance Assessment Dashboard

Requirements Assessed: 150

Compliant: 112
Partially Compliant: 24
Non-Compliant: 8
Under Remediation: 6

High-Risk Gaps: 7
Overdue Actions: 4
```

The GRC team can also provide trend reporting.

```text
Q1:
82% Compliant

Q2:
86% Compliant

Q3:
91% Compliant

Q4:
94% Compliant
```

The trend provides management with an indication of whether compliance performance is improving.

However, percentages should be interpreted carefully.

An increase from 82% to 94% does not necessarily mean that the organization's risk has reduced by the same percentage.

The underlying requirements and risk levels must also be considered.

The Compliance Assessment Template should therefore create a structured evidence trail:

```text
Requirement
    ↓
Assessment Criteria
    ↓
Evidence
    ↓
Testing
    ↓
Observation
    ↓
Conclusion
    ↓
Compliance Status
    ↓
Risk
    ↓
Remediation
```

A well-designed template also makes assessments repeatable.

Different GRC analysts should be able to use the same methodology and reach reasonably consistent conclusions when reviewing equivalent evidence.

The template should therefore include standardized fields, assessment criteria, status definitions, and documentation requirements.

The final assessment record may look like:

```text
Assessment ID:
CA-2026-021

Requirement:
Third-Party Security Assessment

Requirement Reference:
REG-TPRM-04

Scope:
High-risk suppliers

Controls:
TPRM-01
TPRM-02
TPRM-03

Evidence:
Supplier Assessments
Security Questionnaires
Contractual Requirements
Risk Register

Result:
Partially Compliant

Gap:
12 high-risk suppliers have not completed
the required annual security assessment.

Risk:
High

Remediation:
Complete assessments for remaining suppliers.

Owner:
Third-Party Risk Manager

Target Date:
31 December 2026

Status:
Under Remediation
```

The assessment should then be reviewed and approved according to the organization's governance model.

For example:

```text
GRC Analyst
     ↓
GRC Manager
     ↓
Compliance Owner
     ↓
Risk Owner
     ↓
Management
```

Not every assessment requires every level of approval.

Approval requirements should be based on the organization's governance framework and the significance of the assessment.

The completed assessment should be retained according to the organization's records-management requirements.

It should also be linked to:

```text
Compliance Obligation
Regulatory Requirement
Control
Evidence
Risk
Finding
Remediation
Audit
```

This creates a complete compliance traceability chain.

The overall process can therefore be summarized as:

```text
Identify Requirement
        ↓
Determine Applicability
        ↓
Map Requirement to Controls
        ↓
Define Assessment Criteria
        ↓
Collect Evidence
        ↓
Perform Assessment
        ↓
Evaluate Control Design
        ↓
Evaluate Implementation
        ↓
Evaluate Operating Effectiveness
        ↓
Determine Compliance Status
        ↓
Identify Gaps
        ↓
Assess Risk
        ↓
Create Remediation
        ↓
Monitor Closure
        ↓
Retest
        ↓
Update Compliance Status
```

The key principle is:

> **A Compliance Assessment Template provides a consistent and evidence-based method for determining whether applicable regulatory requirements are being satisfied, connecting assessment results to controls, evidence, risk, findings, and remediation rather than treating compliance as a simple checklist exercise.**

**17.8 Compliance Management Tools**

**Part 4 – Compliance Gap Analysis**

Compliance Gap Analysis is the process of identifying the difference between the organization's current compliance position and the requirements that the organization is expected to satisfy.

A compliance assessment determines whether a requirement is being met. Gap analysis goes one step further by identifying **what is missing, what is insufficient, why the gap exists, what risk it creates, and what needs to be done to close it**.

The basic relationship is:

```text
Compliance Requirement
        ↓
Expected State
        ↓
Current State
        ↓
Gap Identification
        ↓
Risk Assessment
        ↓
Remediation
        ↓
Target State
```

A compliance gap does not necessarily mean that the organization has completely failed to meet a requirement.

A gap may represent:

```text
Missing Control
Incomplete Control
Ineffective Control
Insufficient Evidence
Partial Coverage
Process Deficiency
Documentation Deficiency
Ownership Deficiency
Monitoring Deficiency
Regulatory Interpretation Issue
```

For example, a regulatory requirement may require annual security awareness training for all employees.

The organization may have a training program, but 8% of employees may not have completed the required training.

The organization therefore has a **partial compliance gap** rather than a complete absence of a control.

A practical Compliance Gap Analysis Template can contain:

```text
COMPLIANCE GAP ANALYSIS

Gap ID:

Assessment ID:

Requirement ID:

Regulation / Source:

Requirement Reference:

Requirement Description:

Expected State:

Current State:

Gap Description:

Gap Category:

Affected Control:

Control Owner:

Evidence:

Compliance Status:

Risk Level:

Risk Description:

Root Cause:

Business Impact:

Regulatory Impact:

Remediation Action:

Remediation Owner:

Target Date:

Priority:

Compensating Control:

Management Response:

Validation Method:

Closure Evidence:

Closure Date:

Gap Status:

Notes:
```

The first step is to establish the **expected state**.

The expected state describes what the organization should have in place to satisfy the applicable requirement.

For example:

```text
Requirement:
Critical vulnerabilities must be remediated
within the defined regulatory timeframe.

Expected State:
All critical vulnerabilities are identified,
tracked, assigned, and remediated within
15 calendar days unless an approved
exception exists.
```

The expected state should be specific and measurable whenever possible.

A vague expected state such as:

> Vulnerabilities should be managed appropriately.

is difficult to assess.

A stronger statement is:

> All critical vulnerabilities must be remediated within 15 days or covered by a formally approved exception.

This provides a measurable basis for comparison.

The next step is to document the **current state**.

For example:

```text
Current State:

The organization has implemented a vulnerability
management process. Critical vulnerabilities are
tracked through the vulnerability management
platform. However, 14% of critical vulnerabilities
during the assessment period exceeded the
15-day remediation requirement.
```

The assessor can then compare:

```text
Expected State
        vs.
Current State
```

The difference represents the gap.

```text
Expected:
100% within 15 days

Current:
86% within 15 days

Gap:
14% outside required timeframe
```

The gap should be described in factual and objective language.

For example:

> The organization has a vulnerability management process; however, 14% of critical vulnerabilities reviewed during the assessment period exceeded the required remediation timeframe.

This is stronger than writing:

> Vulnerability management is poor.

The first statement identifies an observable condition.

The second is subjective and does not provide sufficient evidence.

A gap should also identify the **affected requirement**.

For example:

```text
Gap ID:
GAP-2026-014

Requirement:
NIS2 Cybersecurity Risk Management

Control:
Vulnerability Management

Gap:
Critical vulnerabilities exceeded the
defined remediation timeframe.
```

This creates traceability between the gap and the compliance obligation.

The gap should also be categorized.

Common categories include:

```text
Governance Gap
Policy Gap
Process Gap
Control Gap
Technical Gap
Documentation Gap
Evidence Gap
Monitoring Gap
Training Gap
Third-Party Gap
Resource Gap
Ownership Gap
```

For example:

```text
Gap:
No formal annual review of supplier security
requirements.

Category:
Governance / Process Gap
```

Another example:

```text
Gap:
Encryption is implemented but evidence of
key rotation is not retained.

Category:
Evidence Gap
```

Another:

```text
Gap:
MFA is not technically implemented for a
specific legacy application.

Category:
Technical Gap
```

Correct classification is important because the remediation approach depends on the type of gap.

A documentation gap may require a document update.

A technical gap may require system implementation.

A governance gap may require changes to roles, responsibilities, or decision-making.

A process gap may require redesigning the operational workflow.

The analysis should also identify the **affected control**.

For example:

```text
Requirement:
Third-Party Risk Management

Control:
TPRM-03 Annual Supplier Security Assessment

Gap:
12 high-risk suppliers have not completed
the required assessment.
```

The next step is to determine the **root cause**.

A gap analysis should not stop at identifying the immediate problem.

For example:

```text
Problem:
Supplier assessments are overdue.

Immediate Cause:
Assessments were not completed.

Root Cause:
No automated workflow exists to trigger
assessment requests and escalation.
```

The root cause may be:

```text
Insufficient Resources
Unclear Ownership
Weak Process
Technology Limitation
Lack of Training
Inadequate Governance
Poor Documentation
Incomplete Integration
Third-Party Dependency
Management Decision
```

Root cause analysis helps prevent the organization from repeatedly treating symptoms instead of addressing the underlying problem.

For example:

```text
Gap:
Access reviews are frequently overdue.

Weak Remediation:
Remind managers to complete reviews.

Better Root Cause:
The IAM platform does not automatically
notify managers or escalate overdue reviews.

Better Remediation:
Implement automated access review workflows
with escalation.
```

The second approach addresses the underlying process weakness.

The gap analysis should also evaluate the **risk created by the gap**.

For example:

```text
Gap:
Critical vulnerabilities remain unresolved.

Likelihood:
High

Impact:
High

Risk:
High
```

The risk assessment should consider:

```text
Regulatory Impact
Security Impact
Financial Impact
Operational Impact
Customer Impact
Privacy Impact
Reputational Impact
Legal Impact
```

The GRC professional should avoid automatically assigning a high risk level to every compliance gap.

Risk should be determined using the organization's approved risk methodology.

For example:

```text
Low Compliance Gap
        ↓
Limited impact
        ↓
Low residual risk

Critical Compliance Gap
        ↓
Significant regulatory exposure
        ↓
High residual risk
```

A small administrative documentation issue should not necessarily receive the same risk rating as a failure to comply with a critical regulatory reporting requirement.

The analysis should also identify the **business impact**.

For example:

```text
Business Impact:

Failure to complete required supplier
assessments may increase the organization's
exposure to third-party cybersecurity risk
and could affect contractual and regulatory
compliance.
```

The **regulatory impact** should also be documented where applicable.

For example:

```text
Regulatory Impact:

Failure to meet the requirement may result
in non-compliance with the applicable
regulatory obligation and may expose the
organization to regulatory scrutiny.
```

The GRC professional should avoid making unsupported claims about specific penalties.

Where legal interpretation is required, the organization should involve legal or regulatory specialists.

The gap analysis should then define the **remediation action**.

For example:

```text
Gap:
Incomplete privileged access reviews.

Remediation:
Integrate all cloud administrator accounts
into the quarterly privileged access review
process and validate review coverage.
```

The remediation should be specific.

Weak remediation:

> Improve access management.

Better remediation:

> Configure the IAM platform to include all privileged cloud accounts in the quarterly access review population and implement automated escalation for incomplete reviews.

The second statement provides a clear action that can be tracked and validated.

Every remediation should have an **owner**.

For example:

```text
Remediation Owner:
IAM Manager
```

The GRC function may coordinate the remediation, but the person accountable for fixing the underlying issue should be identified.

The remediation should also have a **target date**.

For example:

```text
Target Date:
31 December 2026
```

A gap without an owner and target date can remain unresolved indefinitely.

The analysis should also establish a **priority**.

For example:

```text
Critical
High
Medium
Low
```

Priority may consider:

```text
Risk
Regulatory Deadline
Business Criticality
Customer Impact
Audit Findings
Management Commitments
Remediation Complexity
```

For example:

```text
Gap:
Failure to meet mandatory regulatory
incident reporting timeframe.

Risk:
Critical

Priority:
Critical
```

Another gap may be:

```text
Gap:
Minor formatting inconsistency in a
security procedure.

Risk:
Low

Priority:
Low
```

The two issues should not receive the same remediation priority.

The gap analysis may also identify **compensating controls**.

For example:

```text
Primary Control:
Multi-Factor Authentication

Gap:
MFA cannot currently be enabled on a
legacy application.

Compensating Controls:
Network segmentation
Enhanced monitoring
Restricted access
Privileged account monitoring
```

The compensating controls should be formally assessed and approved where required.

They should not simply be listed as a justification for leaving a gap unresolved.

The organization should determine whether the compensating controls sufficiently reduce the risk.

The gap analysis should also identify whether the issue represents:

```text
Design Gap
Implementation Gap
Operating Effectiveness Gap
Evidence Gap
```

For example:

```text
Design Gap:

No formal process exists for reviewing
third-party security requirements.
```

Implementation gap:

```text
The process exists but has not been
implemented for all business units.
```

Operating effectiveness gap:

```text
The process exists and is implemented,
but required reviews are not consistently
performed.
```

Evidence gap:

```text
The review may have occurred, but sufficient
evidence was not retained to demonstrate it.
```

This classification helps determine the appropriate remediation.

A gap analysis should also consider **partial compliance**.

For example:

```text
Requirement:
All employees must complete security
awareness training annually.

Expected:
100% completion.

Current:
96% completion.

Gap:
4% of employees have not completed training.
```

The organization may therefore conclude:

```text
Compliance:
Partially Compliant

Risk:
Medium

Remediation:
Complete outstanding training and implement
automated escalation.
```

The gap should remain open until the defined closure criteria are satisfied.

A mature GRC program should define **closure criteria** before remediation begins.

For example:

```text
Closure Criteria:

1. All critical vulnerabilities are remediated
   within the required timeframe.

2. Evidence is available for the assessment period.

3. Control testing confirms effectiveness.

4. GRC validates remediation.

5. Risk owner approves closure.
```

This prevents premature closure.

The remediation lifecycle can be represented as:

```text
Gap Identified
      ↓
Gap Validated
      ↓
Risk Assessed
      ↓
Remediation Defined
      ↓
Owner Assigned
      ↓
Target Date Set
      ↓
Remediation Implemented
      ↓
Evidence Collected
      ↓
Validation Testing
      ↓
Risk Reassessed
      ↓
Closure Approved
```

The GRC team should distinguish between **remediation completion** and **gap closure**.

For example:

```text
Technical Team:
Remediation completed.

GRC:
Evidence reviewed.

Control Testing:
Effective.

Risk Owner:
Residual risk accepted.

Result:
Gap Closed.
```

The technical team's statement that remediation is complete does not automatically close the compliance gap.

The GRC function should verify that the remediation actually addresses the identified requirement.

A gap analysis should also track **overdue remediation**.

For example:

```text
Open Gaps:
32

Overdue:
7

Due Within 30 Days:
9

Due Within 90 Days:
10

Long-Term:
6
```

Management should receive visibility into overdue high-risk gaps.

For example:

```text
High-Risk Gaps:
8

High-Risk Overdue:
3
```

This provides a more meaningful management indicator than simply reporting the total number of open findings.

The GRC team should also monitor **recurring gaps**.

For example:

```text
2024:
Supplier assessment gap

2025:
Supplier assessment gap

2026:
Supplier assessment gap
```

Repeated gaps may indicate that the remediation approach is not addressing the root cause.

The organization may therefore need to perform a deeper root cause analysis.

For example:

```text
Recurring Gap
      ↓
Root Cause Analysis
      ↓
Process Redesign
      ↓
Technology Improvement
      ↓
Ownership Clarification
      ↓
Monitoring
```

Gap analysis can also be used to compare different business units.

For example:

| Business Unit   | Requirements | Compliant | Partial | Non-Compliant | High-Risk Gaps |
| --------------- | -----------: | --------: | ------: | ------------: | -------------: |
| Business Unit A |           50 |        43 |       5 |             2 |              1 |
| Business Unit B |           50 |        38 |       8 |             4 |              3 |
| Business Unit C |           50 |        46 |       3 |             1 |              0 |

This allows management to identify areas requiring additional support.

However, comparisons should consider differences in business scope and risk.

The gap analysis should also support **regulatory readiness assessments**.

For example:

```text
New Regulation
        ↓
Applicability Assessment
        ↓
Requirement Mapping
        ↓
Current-State Assessment
        ↓
Gap Analysis
        ↓
Remediation Roadmap
```

This is particularly useful when organizations must prepare for new regulatory obligations.

The same approach can be used for:

```text
NIS2
DORA
GDPR
ISO 27001
NIST CSF
Customer Requirements
Industry Regulations
Internal Standards
```

The organization can create a consolidated gap register.

For example:

| Gap ID  | Requirement       | Gap                               | Risk   | Owner            | Target   | Status     |
| ------- | ----------------- | --------------------------------- | ------ | ---------------- | -------- | ---------- |
| GAP-001 | NIS2              | Supplier assessments incomplete   | High   | TPRM Manager     | Dec 2026 | Open       |
| GAP-002 | GDPR              | Data retention reviews incomplete | Medium | Privacy Manager  | Nov 2026 | Open       |
| GAP-003 | ISO 27001         | Evidence retention inconsistent   | Medium | GRC Manager      | Oct 2026 | Remediated |
| GAP-004 | Customer Contract | Annual penetration test overdue   | High   | Security Manager | Sep 2026 | Open       |

The gap register should be linked to the organization's issue and risk management processes.

For example:

```text
Compliance Gap
      ↓
Issue Record
      ↓
Risk Record
      ↓
Remediation Plan
      ↓
Management Reporting
```

The organization may also identify **cross-framework gaps**.

For example:

```text
Gap:
Incomplete privileged access review

Affects:
ISO 27001
NIS2
GDPR
Customer Security Requirements
Internal Security Standard
```

One remediation may therefore address multiple compliance requirements.

This creates an opportunity for efficient risk treatment.

```text
One Root Cause
      ↓
One Remediation
      ↓
Multiple Compliance Improvements
```

However, the GRC team should verify that the remediation completely addresses each mapped requirement.

A compliance gap analysis should also support **management decision-making**.

For example, management may need to decide whether to:

```text
Remediate Immediately
Accept Risk
Transfer Risk
Implement Compensating Controls
Defer Remediation
Change the Business Process
Retire the Affected System
```

These decisions should follow the organization's approved risk acceptance and governance processes.

The gap analysis should not be used to automatically justify risk acceptance.

For example:

```text
Gap:
Critical regulatory requirement not satisfied.

Management:
Accepts the risk.

GRC:
Documents the decision.

Legal / Compliance:
Reviews regulatory implications.

Risk Owner:
Approves according to authority.

Result:
Risk acceptance does not necessarily
eliminate the compliance gap.
```

This distinction is particularly important.

A risk can sometimes be accepted by an authorized risk owner, but the organization may still have a legal or regulatory obligation that cannot simply be waived internally.

The GRC professional must therefore distinguish between:

```text
Risk Acceptance
        ≠
Regulatory Exemption
```

A regulatory exemption or formal derogation, where available, may require approval from the relevant authority rather than internal management.

The gap analysis should also identify **dependencies** that may affect remediation.

For example:

```text
Gap:
Legacy system does not support MFA.

Remediation:
Upgrade application.

Dependency:
Application replacement project.

Target:
Q2 2027
```

The GRC team should monitor the dependency because delays may extend the compliance gap.

The analysis should also document **temporary measures**.

For example:

```text
Temporary Control:
Additional privileged access monitoring

Duration:
Until application upgrade

Review:
Monthly

Owner:
Security Operations
```

Temporary controls should have expiration or review dates.

The GRC team should avoid allowing temporary measures to become permanent without formal review.

The gap analysis can also be used to develop a **compliance improvement roadmap**.

For example:

```text
Q3 2026
Address Critical Gaps

Q4 2026
Address High-Risk Gaps

Q1 2027
Address Medium-Risk Gaps

Q2 2027
Optimize Control Environment
```

A more detailed roadmap may include:

```text
Gap
 ↓
Priority
 ↓
Remediation
 ↓
Dependency
 ↓
Owner
 ↓
Budget
 ↓
Target Date
 ↓
Expected Risk Reduction
```

This allows management to connect compliance improvements with investment decisions.

The GRC team should also measure the effectiveness of remediation.

Useful metrics include:

```text
Total Compliance Gaps
Open Compliance Gaps
Closed Compliance Gaps
High-Risk Gaps
Overdue Gaps
Average Remediation Time
Recurring Gaps
Remediation Success Rate
Compliance Coverage
```

For example:

```text
Total Gaps:
60

Closed:
38

Open:
22

High-Risk:
6

Overdue:
4

Average Remediation Time:
74 Days
```

Trend analysis may show:

```text
Q1:
72 Open Gaps

Q2:
61 Open Gaps

Q3:
48 Open Gaps

Q4:
35 Open Gaps
```

This provides management with an indication of improvement.

However, the number of gaps alone does not determine compliance maturity.

An organization may have fewer gaps because it has performed less assessment.

Therefore, metrics should be interpreted alongside:

```text
Assessment Coverage
Requirement Coverage
Risk Profile
Control Effectiveness
Audit Results
Regulatory Changes
```

A mature compliance gap analysis should ultimately provide a clear answer to five questions:

```text
1. What should we have?

2. What do we actually have?

3. What is missing or ineffective?

4. What risk does the gap create?

5. What must we do to close or manage the gap?
```

The complete process can therefore be represented as:

```text
Requirement
     ↓
Expected State
     ↓
Current State
     ↓
Gap
     ↓
Root Cause
     ↓
Risk
     ↓
Priority
     ↓
Remediation
     ↓
Owner
     ↓
Target Date
     ↓
Implementation
     ↓
Validation
     ↓
Closure
```

A well-managed Compliance Gap Analysis ensures that compliance assessments result in actionable improvements rather than simply producing a list of findings.

The key principle is:

> **Compliance Gap Analysis identifies the difference between required and actual compliance, determines the risk and root cause of the gap, and establishes a controlled path toward remediation, validation, and sustainable compliance.**



