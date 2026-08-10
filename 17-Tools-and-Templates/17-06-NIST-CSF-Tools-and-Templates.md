**17.6 NIST Cybersecurity Framework Tools and Templates**

### Part 1 – NIST CSF Current Profile Template

The **NIST Cybersecurity Framework (CSF) Current Profile** is a practical tool for documenting the organization's current cybersecurity posture. It provides a structured view of how the organization currently manages cybersecurity risks across the NIST CSF Functions, Categories, and Subcategories.

A Current Profile answers a fundamental GRC question:

> **Where are we today?**

Unlike a policy or procedure, the Current Profile is an assessment and management tool. It captures the organization's existing cybersecurity practices, controls, capabilities, and current level of implementation.

The basic relationship is:

```text
NIST CSF
    ↓
Functions
    ↓
Categories
    ↓
Subcategories
    ↓
Current Organizational Practices
    ↓
Evidence
    ↓
Current Profile
```

The five Functions in the original NIST CSF 1.1 were:

```text
Identify
Protect
Detect
Respond
Recover
```

With **NIST CSF 2.0**, the framework contains six Functions:

```text
Govern
Identify
Protect
Detect
Respond
Recover
```

For a current GRC program, the **NIST CSF 2.0 structure should be used** unless an organization has a documented reason to continue using an earlier CSF version.

The Current Profile should therefore provide visibility across the six CSF 2.0 Functions.

A practical Current Profile template can contain:

```text
NIST CSF CURRENT PROFILE

Organization:

Assessment Date:

Assessment Scope:

Business Unit:

Profile Owner:

Assessment Team:

NIST CSF Version:

Function:

Category:

Subcategory:

Current Practice:

Current Implementation Status:

Evidence:

Control / Process Owner:

Related Policy:

Related Control:

Risk Reference:

Current Maturity / Capability:

Identified Gap:

Comments:
```

The first step is defining the **scope** of the Current Profile.

For example:

```text
Assessment Scope:

Corporate IT environment
Cloud infrastructure
Corporate endpoints
Identity and access management
Security operations
Critical business applications
```

The scope should be clearly defined.

A Current Profile for an entire enterprise is different from a Current Profile covering only:

* A business unit.
* A cloud environment.
* A critical application.
* A data center.
* A regional operation.
* A specific business process.

The scope determines what the assessment results actually mean.

For example:

```text
Current Profile A:
Entire Enterprise

Current Profile B:
Cloud Environment Only
```

A weakness identified in Profile B should not automatically be interpreted as a weakness across the entire enterprise.

The assessment should also identify the **NIST CSF version**.

For example:

```text
Framework:
NIST Cybersecurity Framework

Version:
CSF 2.0

Assessment Date:
August 2026
```

This is important because the framework structure and terminology have evolved.

The Current Profile should then map the organization's existing practices to the relevant CSF outcomes.

For example:

```text
NIST CSF Function:
Protect

Category:
Identity Management, Authentication,
and Access Control

Current Practice:
MFA is required for privileged accounts.

Evidence:
IAM configuration report
MFA compliance report
```

The Current Profile should describe the **actual current state**, rather than the desired future state.

For example:

**Current State:**

> MFA is implemented for privileged accounts but is not yet enforced for all standard user accounts.

This is different from:

> MFA will be implemented for all users.

The second statement describes a target state rather than a current state.

This distinction becomes particularly important in **17.6 Part 2**, where the Target Profile will be developed.

A practical Current Profile may use implementation ratings.

For example:

| Rating                | Meaning                                        |
| --------------------- | ---------------------------------------------- |
| Not Implemented       | Practice does not currently exist              |
| Initial               | Practice exists inconsistently                 |
| Partially Implemented | Practice covers some of the required scope     |
| Implemented           | Practice is broadly implemented                |
| Managed               | Practice is monitored and consistently managed |
| Optimized             | Practice is continuously improved              |

The organization should define the exact meaning of its rating system before using it.

The rating should also be supported by evidence.

For example:

```text
Current Practice:
Quarterly privileged access reviews

Implementation:
Partially Implemented

Evidence:
Q2 2026 access review

Finding:
Legacy applications are not included.

Rating:
Partially Implemented
```

This is more defensible than assigning a rating without supporting evidence.

The Current Profile can also use a simpler status model:

```text
Not Implemented
Partially Implemented
Implemented
Not Applicable
Unknown
```

This may be preferable when the organization does not yet have a mature capability-maturity model.

The key is **consistency**.

The same criteria should be applied across the assessment.

A Current Profile should also identify the **control or process supporting the CSF outcome**.

For example:

| NIST CSF Area            | Organizational Control           |
| ------------------------ | -------------------------------- |
| Identity Management      | IAM Process                      |
| Asset Management         | Asset Inventory Process          |
| Vulnerability Management | Vulnerability Management Process |
| Incident Response        | Incident Response Plan           |
| Recovery                 | Disaster Recovery Process        |
| Security Awareness       | Security Awareness Program       |

This connects the framework to actual organizational processes.

The mapping can be represented as:

```text
NIST CSF Outcome
       ↓
Organizational Process
       ↓
Internal Control
       ↓
Evidence
       ↓
Current Assessment
```

This prevents the Current Profile from becoming an abstract framework exercise.

For example:

```text
NIST CSF:
Protect

Organizational Process:
Security Awareness

Internal Control:
Annual Security Awareness Training

Current State:
Annual training is provided to employees.
Contractors are not consistently included.

Evidence:
2026 Training Completion Report

Gap:
Contractor coverage
```

The Current Profile should also record **control ownership**.

For example:

| Capability               | Owner                      |
| ------------------------ | -------------------------- |
| Asset Management         | IT Asset Manager           |
| Identity Management      | IAM Manager                |
| Vulnerability Management | Security Operations        |
| Incident Response        | SOC Manager                |
| Business Continuity      | BCM Manager                |
| Security Awareness       | Security Awareness Manager |

Ownership is important because identified gaps eventually need to be assigned to responsible individuals or teams.

The Current Profile can also incorporate **risk references**.

For example:

```text
NIST CSF:
Protect – Access Control

Risk:
R-014 Unauthorized Privileged Access

Current State:
PAM implemented for 70% of privileged accounts.

Gap:
30% of privileged accounts remain outside PAM.

Risk Rating:
High
```

This connects NIST CSF assessment activities to the organization's broader GRC risk management process.

A strong Current Profile therefore does not merely say:

> Partially implemented.

It explains **why**.

For example:

```text
Current Status:
Partially Implemented

Reason:
Centralized vulnerability scanning covers
corporate endpoints and servers but does not
yet cover several cloud workloads.

Evidence:
Vulnerability Management Report – Q2 2026

Risk:
R-023 – Undetected Vulnerabilities

Owner:
Security Operations Manager
```

The Current Profile should also capture **evidence references**.

Examples include:

* Policies.
* Procedures.
* Security reports.
* System configurations.
* Audit reports.
* Risk assessments.
* Vulnerability reports.
* Incident records.
* Training records.
* Access reviews.
* Recovery tests.
* Monitoring reports.

For example:

```text
Evidence ID:
EV-2026-035

Evidence:
Q2 Vulnerability Management Report

Related CSF:
Protect / Vulnerability Management

Owner:
Security Operations
```

This creates auditability.

The Current Profile can also be maintained in a spreadsheet.

A practical table could look like:

| Function | Category               | Current Practice            | Status      | Evidence    | Owner | Gap                |
| -------- | ---------------------- | --------------------------- | ----------- | ----------- | ----- | ------------------ |
| Govern   | Organizational Context | Cybersecurity roles defined | Implemented | Org Chart   | CISO  | None               |
| Identify | Asset Management       | Asset inventory maintained  | Partial     | CMDB Report | IT    | Cloud assets       |
| Protect  | Access Control         | MFA for privileged users    | Partial     | IAM Report  | IAM   | Standard users     |
| Detect   | Continuous Monitoring  | SIEM monitoring             | Implemented | SIEM Report | SOC   | None               |
| Respond  | Incident Management    | IR process established      | Implemented | IR Plan     | SOC   | Exercise frequency |
| Recover  | Recovery Planning      | DR plans exist              | Partial     | DR Plan     | BCM   | Testing coverage   |

This table provides management with a quick view of the current cybersecurity posture.

The Current Profile can also be represented visually.

For example:

```text
Govern       ████████░░
Identify     ██████░░░░
Protect      ███████░░░
Detect       ████████░░
Respond      ██████░░░░
Recover      █████░░░░░
```

The exact scoring methodology should be documented rather than relying on arbitrary percentages.

A GRC team should also be careful when calculating an overall score.

Cybersecurity capability is multidimensional.

A single score can hide important weaknesses.

For example:

> Overall score: 82%

may look positive even though:

> Privileged access management has a critical gap.

Therefore, the Current Profile should retain the detailed findings behind any summary score.

The Current Profile should also distinguish between **documented capability** and **operational capability**.

For example:

```text
Policy:
Documented

Procedure:
Documented

Implementation:
Partial

Evidence:
Available

Operational Effectiveness:
Partial
```

This provides a more realistic view of cybersecurity maturity.

A Current Profile can also include **assessment comments**.

For example:

> The organization has a documented incident response process and designated incident response roles. However, the process has not been exercised across all critical business units during the assessment period.

This provides useful context for management.

The assessment should also identify **not applicable** outcomes where appropriate.

However, the organization should provide a justification.

For example:

```text
Status:
Not Applicable

Justification:
The assessed business unit does not operate
industrial control systems within the defined scope.
```

The organization should avoid using "Not Applicable" simply to remove difficult requirements from the assessment.

The decision should be documented and defensible.

The Current Profile should also be reviewed when there are significant changes.

Triggers may include:

* New technologies.
* New business services.
* Cloud migration.
* Major security incidents.
* New regulatory requirements.
* Organizational restructuring.
* New suppliers.
* New critical assets.
* Changes in cybersecurity strategy.
* Significant changes to the threat environment.

For example:

```text
Cloud Migration
      ↓
New Assets
      ↓
New Risks
      ↓
Current Profile Update
      ↓
Gap Identification
```

The Current Profile should therefore be treated as a **living assessment**.

It should not be created once and then left unchanged for several years.

The GRC team should establish a review frequency.

For example:

```text
Formal Assessment:
Annually

Focused Review:
Quarterly

Event-Based Review:
After Significant Changes
```

The exact frequency should depend on organizational risk, regulatory requirements, business complexity, and the organization's cybersecurity governance model.

A practical Current Profile workflow is:

```text
1. Define Scope
        ↓
2. Select NIST CSF Version
        ↓
3. Identify Relevant CSF Outcomes
        ↓
4. Identify Existing Practices
        ↓
5. Collect Evidence
        ↓
6. Assess Current Implementation
        ↓
7. Identify Gaps
        ↓
8. Link Gaps to Risks
        ↓
9. Assign Owners
        ↓
10. Document Current Profile
```

The Current Profile should eventually provide the foundation for developing the **Target Profile**.

The relationship is:

```text
Current Profile
      ↓
Where Are We Today?
      ↓
Gap Analysis
      ↓
Target Profile
      ↓
Where Do We Want To Be?
```

For example:

```text
Current:
MFA covers 70% of privileged accounts.

Target:
MFA covers 100% of privileged accounts.

Gap:
30% coverage gap.

Action:
Extend MFA to remaining privileged accounts.

Owner:
IAM Manager.

Target Date:
31 December 2026.
```

This transforms the framework from a descriptive assessment into a practical improvement program.

For a practical exercise, assume an organization has the following current capabilities:

```text
Asset Management:
Corporate assets are inventoried.
Cloud assets are only partially inventoried.

Identity Management:
MFA is implemented for privileged users.
Standard user MFA is not yet universal.

Vulnerability Management:
Monthly vulnerability scanning is performed.
Several cloud workloads are excluded.

Incident Response:
An incident response plan exists.
The plan has not been tested during the current year.

Recovery:
Critical systems have recovery procedures.
Full recovery exercises are performed annually.
```

Create a **NIST CSF Current Profile** containing:

```text
Function
Category
Current Practice
Implementation Status
Evidence
Control Owner
Risk Reference
Current Gap
Comments
```

Then identify the three most significant gaps.

For example:

```text
Gap 1:
Incomplete cloud asset visibility

Gap 2:
Incomplete MFA coverage

Gap 3:
Incomplete vulnerability scanning coverage
```

Rank the gaps using the organization's risk criteria rather than simply choosing the gaps that appear technically interesting.

The final objective is to produce a Current Profile that management can actually use.

A good Current Profile should allow a CISO, GRC manager, risk owner, or executive to answer:

```text
What cybersecurity capabilities currently exist?

Which capabilities are fully implemented?

Which capabilities are only partially implemented?

Where are the major weaknesses?

What evidence supports the assessment?

Which risks are associated with the weaknesses?

Who owns the gaps?

What should be improved?
```

The key principle is:

> **The NIST CSF Current Profile provides an evidence-based picture of the organization's present cybersecurity posture and establishes the baseline from which future cybersecurity improvements can be planned.**


