**17.5 ISO 27001 Tools and Templates**

### Part 1 – ISO 27001 Control Mapping Template

ISO/IEC 27001 implementation requires an organization to understand how its security controls relate to the requirements of the Information Security Management System (ISMS), the organization's identified risks, and the applicable controls in **ISO/IEC 27001:2022 Annex A**.

A control mapping template provides a structured way to establish these relationships.

In practical GRC work, control mapping is important because organizations rarely manage security controls using only one framework. A single security control may support:

* ISO/IEC 27001:2022.
* NIST Cybersecurity Framework.
* Internal security policies.
* Regulatory requirements.
* Contractual requirements.
* Customer security requirements.
* Risk treatment activities.

A control mapping template creates traceability between these different requirements.

The basic relationship can be represented as:

```text
Business Requirement
        ↓
Risk
        ↓
Control Objective
        ↓
Security Control
        ↓
ISO 27001 Requirement / Annex A
        ↓
Evidence
        ↓
Assessment
```

For example:

```text
Risk:
Unauthorized access to sensitive systems

Existing Control:
Multi-factor authentication

ISO 27001:
Annex A access control-related controls

Internal Policy:
Access Control Policy

Evidence:
IAM configuration
MFA report
Access review records
```

The purpose of the mapping is not simply to create a list of ISO controls. The organization needs to demonstrate how each relevant control is implemented and how it contributes to managing identified risks.

A practical **ISO 27001 Control Mapping Template** can contain:

```text
ISO 27001 CONTROL MAPPING

Control ID:

Control Name:

ISO 27001 Reference:

Control Objective:

Business Process:

Information Asset:

Risk ID:

Risk Description:

Internal Control ID:

Internal Control Name:

Control Owner:

Control Type:

Control Description:

Implementation Status:

Control Evidence:

Related Policy:

Related Procedure:

Related Framework:

Related Regulatory Requirement:

Control Assessment:

Control Effectiveness:

Gap Identified:

Remediation Action:

Action Owner:

Target Date:

Comments:
```

The first important field is the **ISO 27001 reference**.

For example:

```text
ISO 27001 Reference:
Annex A control

Control Name:
[Applicable Annex A control]

Internal Control ID:
AC-001

Internal Control Name:
Privileged Access Management
```

The internal control should then be mapped to the organization's actual implementation.

This distinction is important because the ISO/IEC 27001 control is not necessarily the same thing as the organization's internal control.

For example:

```text
ISO 27001 Control
        ↓
Organizational Requirement
        ↓
Internal Policy
        ↓
Procedure
        ↓
Technical / Administrative Control
        ↓
Evidence
```

An organization may therefore implement one ISO requirement through several internal controls.

For example:

```text
Access Control Requirement
        ↓
Access Control Policy
        ↓
User Provisioning Procedure
        ↓
IAM Platform
        ↓
MFA
        ↓
Privileged Access Management
        ↓
Quarterly Access Review
```

The mapping template should capture these relationships.

One of the most useful fields is the **Risk ID**.

This connects the control to the organization's risk management process.

For example:

| Control ID | ISO Reference | Risk ID | Internal Control             |
| ---------- | ------------- | ------- | ---------------------------- |
| AC-001     | Annex A       | R-001   | Privileged Access Management |
| AC-002     | Annex A       | R-002   | User Access Review           |
| BC-001     | Annex A       | R-005   | Backup and Recovery          |
| VM-001     | Annex A       | R-009   | Vulnerability Management     |

This provides traceability from risk to control.

The relationship can be represented as:

```text
Risk R-001
    ↓
Control AC-001
    ↓
ISO 27001 Mapping
    ↓
Evidence
    ↓
Control Assessment
```

This is particularly valuable during internal and external audits.

An auditor may ask:

> How does the organization determine that this control is necessary?

The GRC professional should be able to trace the answer back to the organization's risk assessment.

For example:

```text
Risk:
Unauthorized privileged access

Risk Rating:
High

Treatment Decision:
Mitigate

Control:
Privileged Access Management

ISO Mapping:
Applicable Annex A control

Evidence:
PAM configuration
Privileged account inventory
Access review records
```

This demonstrates a risk-based approach.

The mapping template should also include **control ownership**.

A control should have a clearly identified owner.

Examples include:

| Control                  | Possible Owner                  |
| ------------------------ | ------------------------------- |
| Access Management        | IAM Manager                     |
| Vulnerability Management | Security Operations Manager     |
| Backup                   | Infrastructure Manager          |
| Supplier Security        | Third-Party Risk Manager        |
| Security Awareness       | Security Awareness Manager      |
| Incident Management      | SOC / Incident Response Manager |

The control owner is responsible for ensuring that the control remains implemented and operational.

The GRC team may coordinate the assessment, but it does not necessarily own the underlying control.

The template should also record the **control type**.

A basic classification could be:

```text
Preventive
Detective
Corrective
Directive
Deterrent
Compensating
Recovery
```

For example:

| Control           | Type         |
| ----------------- | ------------ |
| MFA               | Preventive   |
| SIEM Monitoring   | Detective    |
| Incident Response | Corrective   |
| Security Policy   | Directive    |
| Warning Banner    | Deterrent    |
| Network Isolation | Compensating |
| Backup            | Recovery     |

Understanding the control type helps the GRC professional determine what the control is intended to achieve.

The **control description** should explain what the organization actually does.

A weak description would be:

> Access is controlled.

A stronger description would be:

> User access to production systems is authorized through the centralized IAM process. Privileged access requires MFA and is reviewed quarterly by designated system owners.

The second description is more useful because it identifies:

* The process.
* The technology.
* The authorization mechanism.
* The privileged access requirement.
* The review frequency.
* The responsible parties.

The mapping template should also record the **implementation status**.

A practical status model could be:

| Status                | Meaning                                             |
| --------------------- | --------------------------------------------------- |
| Not Implemented       | Control does not exist                              |
| Planned               | Implementation has been approved but not started    |
| In Progress           | Implementation is underway                          |
| Partially Implemented | Some scope is covered                               |
| Implemented           | Control is implemented                              |
| Effective             | Control is implemented and operating effectively    |
| Not Applicable        | Control is not applicable, subject to justification |

The distinction between **implemented** and **effective** is important.

A control can be implemented but still have operational weaknesses.

For example:

> MFA has been deployed, but 7% of privileged accounts are still excluded.

The control is implemented, but it may not yet be fully effective.

The mapping template should therefore include an **evidence reference**.

Examples include:

* Policy documents.
* Procedures.
* System configurations.
* Reports.
* Audit logs.
* Access review records.
* Training records.
* Security monitoring reports.
* Contracts.
* Risk assessments.
* Meeting minutes.
* Test results.

For example:

```text
Evidence:

EV-001 – Access Control Policy
EV-002 – IAM Configuration Report
EV-003 – Privileged Account Inventory
EV-004 – Q2 Access Review
EV-005 – MFA Compliance Report
```

Evidence should ideally be uniquely identifiable.

This allows an auditor or reviewer to trace the control back to the supporting evidence.

The mapping can also connect the ISO 27001 control to the organization's **policies and procedures**.

For example:

| ISO Control         | Internal Policy             | Procedure                     |
| ------------------- | --------------------------- | ----------------------------- |
| Access Control      | Access Control Policy       | User Provisioning Procedure   |
| Incident Management | Incident Response Policy    | Incident Handling Procedure   |
| Supplier Security   | Third-Party Security Policy | Vendor Assessment Procedure   |
| Backup              | Backup Policy               | Backup and Recovery Procedure |

This creates a clear relationship between framework requirements and operational documentation.

A practical mapping structure is:

```text
ISO Requirement
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
       ↓
Assessment
```

This structure is extremely useful when preparing an organization for an ISO/IEC 27001 certification audit.

The mapping should also identify **related frameworks**.

For example:

| Internal Control         | ISO 27001                  | NIST CSF           | Internal Policy          |
| ------------------------ | -------------------------- | ------------------ | ------------------------ |
| MFA                      | Applicable Annex A control | Protect            | Access Control           |
| Vulnerability Management | Applicable Annex A control | Identify / Protect | Vulnerability Policy     |
| Incident Response        | Applicable Annex A control | Respond            | Incident Response Policy |
| Backup                   | Applicable Annex A control | Recover            | Backup Policy            |

This is called **cross-framework mapping**.

Cross-framework mapping reduces duplication.

Instead of creating separate controls for ISO 27001 and NIST CSF, the organization can identify where one internal control satisfies multiple framework requirements.

For example:

```text
Internal Control:
Privileged Access Management

        ├── ISO 27001
        ├── NIST CSF
        ├── Internal Security Policy
        ├── Customer Requirement
        └── Regulatory Requirement
```

This approach is particularly useful for organizations that operate multiple compliance programs.

The mapping template can therefore contain a **cross-reference section**:

```text
Framework Mapping:

ISO/IEC 27001:
[Reference]

NIST CSF:
[Function / Category]

Internal Policy:
[Policy Reference]

Regulatory Requirement:
[Requirement Reference]

Contractual Requirement:
[Requirement Reference]
```

The GRC professional should avoid assuming that two controls are identical simply because they have similar names.

For example:

> "Access Control" in two frameworks may have different scopes and requirements.

The mapping should therefore be based on the actual control objectives and requirements.

A useful classification is:

```text
Full Mapping
Partial Mapping
Related Control
No Equivalent
```

For example:

| Mapping | Meaning                                                        |
| ------- | -------------------------------------------------------------- |
| Full    | Internal control completely addresses the requirement          |
| Partial | Internal control addresses only part of the requirement        |
| Related | Control supports the requirement but does not fully satisfy it |
| None    | No relevant internal control exists                            |

This prevents false claims of compliance.

The template should also identify **gaps**.

For example:

```text
ISO Requirement:
Applicable

Internal Control:
Partially Implemented

Gap:
Privileged access reviews are not performed
for legacy applications.

Risk:
High

Treatment:
Implement centralized privileged access review.

Owner:
IAM Manager

Target:
31 December 2026
```

The mapping therefore becomes more than a compliance spreadsheet.

It becomes a mechanism for identifying improvement opportunities.

A practical end-to-end mapping process is:

```text
1. Identify ISO Requirement
          ↓
2. Determine Applicability
          ↓
3. Identify Organizational Risk
          ↓
4. Identify Existing Internal Control
          ↓
5. Map Control to ISO Requirement
          ↓
6. Identify Supporting Policies
          ↓
7. Identify Evidence
          ↓
8. Assess Implementation
          ↓
9. Identify Gaps
          ↓
10. Assign Remediation
```

The **applicability** step is particularly important.

Not every Annex A control will necessarily be implemented in exactly the same way.

The organization should determine applicability through its ISMS risk assessment and control selection process.

This determination should eventually be documented in the **Statement of Applicability (SoA)**, which will be covered in Part 2.

The mapping template should therefore not be confused with the SoA.

The two serve related but different purposes.

```text
Control Mapping
        ↓
Shows relationships between requirements,
risks, controls, policies, and evidence

Statement of Applicability
        ↓
Documents which Annex A controls are
applicable, justified, and implemented
```

The mapping provides the detailed working relationship, while the SoA provides the formal applicability record.

A practical ISO 27001 control mapping table could look like:

| ISO Reference | Internal Control         | Risk ID | Owner            | Status    | Evidence           | Gap               |
| ------------- | ------------------------ | ------- | ---------------- | --------- | ------------------ | ----------------- |
| Annex A       | Access Management        | R-001   | IAM Manager      | Effective | IAM Report         | None              |
| Annex A       | Privileged Access        | R-002   | Security Manager | Partial   | PAM Report         | Legacy systems    |
| Annex A       | Vulnerability Management | R-003   | SOC Manager      | Effective | VM Report          | None              |
| Annex A       | Backup                   | R-004   | Infrastructure   | Partial   | Backup Report      | Recovery testing  |
| Annex A       | Supplier Security        | R-005   | Vendor Manager   | Partial   | Vendor Assessments | 3 vendors pending |

This type of table can become the foundation of an organization's ISO 27001 control inventory.

The mapping should be periodically reviewed.

Triggers for review include:

* New ISO requirements or organizational interpretations.
* Changes to the ISMS scope.
* New business processes.
* New technologies.
* New risks.
* Major security incidents.
* Changes to internal controls.
* New regulatory requirements.
* Changes in third-party relationships.
* Audit findings.

For example:

```text
New Cloud Service
      ↓
New Business Process
      ↓
New Risk
      ↓
New / Modified Control
      ↓
ISO Mapping Updated
      ↓
Evidence Requirements Updated
```

The GRC professional should also maintain **version control** for the mapping.

A practical control mapping record might include:

```text
Document:
ISO 27001 Control Mapping

Version:
2.1

Owner:
GRC Manager

Approved By:
CISO

Effective Date:
01 September 2026

Next Review:
01 September 2027
```

Changes should be documented so that the organization can determine what changed and why.

A control mapping template should ultimately answer the following questions:

```text
What ISO requirement are we addressing?

Why is the control relevant?

What organizational risk does it address?

What internal control addresses it?

Who owns the control?

How is the control implemented?

What evidence demonstrates implementation?

Which other frameworks or requirements does it support?

Is there a gap?

What remediation is required?
```

For a practical exercise, assume that an organization has the following internal controls:

```text
AC-001 – User Access Management
AC-002 – Privileged Access Management
VM-001 – Vulnerability Management
IR-001 – Incident Response
BC-001 – Backup and Recovery
TP-001 – Third-Party Security Assessment
```

Create an ISO 27001 control mapping table containing:

```text
ISO Reference
Internal Control ID
Control Name
Risk ID
Control Owner
Implementation Status
Evidence
Related Policy
Related Framework
Gap
Remediation
```

Then identify which controls should be mapped to multiple requirements.

For example:

```text
Privileged Access Management
        ↓
Access Control
        ↓
Risk Management
        ↓
Internal Security Policy
        ↓
NIST CSF
        ↓
Customer Security Requirement
```

This exercise demonstrates an important GRC principle:

> **A single well-designed organizational control can support multiple security, compliance, and risk requirements.**

The purpose of control mapping is therefore not to create more documentation.

Its purpose is to create **traceability**.

A mature ISO 27001 control mapping should allow an assessor to move in either direction:

```text
Risk
 ↓
Control
 ↓
ISO Requirement
 ↓
Evidence
```

or:

```text
ISO Requirement
 ↓
Internal Control
 ↓
Risk
 ↓
Evidence
 ↓
Assessment Result
```

This bidirectional traceability is one of the most useful capabilities of a mature GRC program.

The **Statement of Applicability (SoA)** is one of the key documented components of an ISO/IEC 27001 Information Security Management System (ISMS). It records the organization's decisions regarding the applicable controls and provides a clear connection between the organization's risk assessment, risk treatment decisions, and selected security controls.

The SoA should not be treated as a simple checklist of Annex A controls.

Its purpose is to demonstrate that the organization has systematically determined which controls are necessary for its information security risks and ISMS objectives.

The basic relationship is:

```text
ISMS Scope
     ↓
Risk Assessment
     ↓
Risk Treatment
     ↓
Control Selection
     ↓
Statement of Applicability
     ↓
Control Implementation
     ↓
Evidence
```

A practical SoA should therefore provide traceability between the selected controls and the organization's risk treatment process.

A basic **Statement of Applicability Template** can contain:

```text
STATEMENT OF APPLICABILITY

Control Reference:

Control Name:

Applicable:

Justification for Applicability:

Risk Reference:

Risk Treatment Reference:

Control Implementation Status:

Implementation Description:

Control Owner:

Evidence Reference:

Related Policy:

Related Procedure:

Exclusion Justification:

Implementation Date:

Assessment Status:

Comments:
```

The **Applicable** field records whether the control has been determined to be applicable to the organization's ISMS.

For example:

```text
Control:
[Applicable Annex A control]

Applicable:
Yes

Justification:
The control is required to address risks
identified during the ISMS risk assessment.
```

If a control is determined not to be applicable, the organization should provide a documented justification.

For example:

```text
Applicable:
No

Justification:
The organization does not operate physical
data center facilities within the defined ISMS
scope. The relevant physical infrastructure
is provided by a contracted hosting provider.
```

However, the organization should be careful when declaring controls not applicable.

The decision should be based on the organization's actual circumstances and risk environment rather than simply because the control is inconvenient or difficult to implement.

The SoA should also connect the control to the **risk assessment**.

For example:

```text
Risk ID:
R-014

Risk:
Unauthorized privileged access

Treatment:
Mitigate

Selected Control:
Privileged Access Management

SoA:
Applicable
```

This creates traceability:

```text
Risk
 ↓
Risk Treatment
 ↓
Control
 ↓
SoA
 ↓
Implementation
```

This is one of the most important relationships in an ISO 27001 ISMS.

A control should have a clear reason for being selected.

Possible justifications include:

* It addresses an identified information security risk.
* It is necessary to achieve an ISMS security objective.
* It supports a contractual requirement.
* It addresses a legal or regulatory requirement.
* It supports business continuity.
* It protects critical information assets.
* It addresses a known threat.
* It supports customer security requirements.
* It is necessary because of the organization's operating environment.

For example:

```text
Control:
Supplier Security Management

Applicable:
Yes

Justification:
The organization relies on external suppliers
for critical technology services. Supplier-related
risks were identified during the risk assessment.

Risk:
R-021 – Third-Party Security Risk
```

The SoA should also record the **implementation status**.

A practical status model could be:

| Status                | Meaning                                          |
| --------------------- | ------------------------------------------------ |
| Not Implemented       | Control has not yet been implemented             |
| Planned               | Implementation has been approved                 |
| In Progress           | Implementation is underway                       |
| Partially Implemented | Control covers only part of the required scope   |
| Implemented           | Control has been implemented                     |
| Effective             | Control is implemented and operating as intended |

This distinction is useful during ISO 27001 implementation projects.

For example:

```text
Control:
Security Awareness

Status:
Partially Implemented

Current State:
Annual training exists for employees.

Gap:
Contractors are not currently included.

Action:
Extend training requirements to relevant contractors.
```

The SoA can therefore provide visibility into implementation gaps.

The **implementation description** should explain how the organization has implemented the control.

A weak description would be:

> Access is controlled.

A stronger description would be:

> User access is managed through the centralized identity management platform. Access requests require business owner approval, privileged accounts require MFA, and access rights are reviewed quarterly.

The second description provides meaningful information about the organization's implementation.

The SoA should also reference supporting documentation.

For example:

```text
Policy:
Access Control Policy

Procedure:
User Access Management Procedure

Standard:
Privileged Access Standard

Evidence:
IAM Access Review – Q2 2026
MFA Compliance Report – Q2 2026
```

This provides a documentation chain:

```text
SoA
 ↓
Policy
 ↓
Procedure
 ↓
Control
 ↓
Evidence
```

The SoA should also identify the **control owner**.

For example:

| Control             | Control Owner              |
| ------------------- | -------------------------- |
| Access Management   | IAM Manager                |
| Security Awareness  | Security Awareness Manager |
| Incident Management | SOC Manager                |
| Supplier Security   | Third-Party Risk Manager   |
| Backup              | Infrastructure Manager     |

The GRC team may maintain the SoA, but the underlying controls remain the responsibility of their respective control owners.

One important distinction is between **control applicability** and **control effectiveness**.

A control can be:

```text
Applicable + Effective
Applicable + Partially Effective
Applicable + Ineffective
Applicable + Not Implemented
```

For example:

```text
Applicable:
Yes

Implementation:
Yes

Effectiveness:
Partially Effective
```

This means the organization considers the control necessary but has identified weaknesses in its operation.

The SoA should therefore not be used to hide control deficiencies.

Instead, the deficiencies should be connected to the organization's risk and corrective-action processes.

For example:

```text
Applicable:
Yes

Implementation:
Partial

Gap:
Quarterly access reviews are not performed
for two legacy applications.

Risk:
R-014

Corrective Action:
Implement access review capability.

Owner:
IAM Manager

Target Date:
31 December 2026
```

Another important field is the **exclusion justification**.

When an organization determines that a control is not applicable, the justification should be specific and related to the organization's circumstances.

A weak justification would be:

> Not applicable.

A stronger justification would explain:

* What the organization does.
* Why the control does not apply.
* What is outside the ISMS scope.
* Whether another party provides the relevant capability.
* Whether the risk was considered during risk assessment.

For example:

```text
Control:
Physical Data Center Security

Applicable:
No

Justification:
The ISMS scope does not include organization-owned
data center facilities. Production infrastructure is
hosted entirely by contracted cloud service providers.
Physical infrastructure security is addressed through
supplier security requirements and contractual controls.
```

The justification should be reviewed to ensure that the organization has not incorrectly excluded a control simply because responsibility has been outsourced.

Outsourcing does not automatically eliminate organizational risk.

For example:

```text
Organization
     ↓
Cloud Provider
     ↓
Physical Infrastructure
```

The organization may not operate the physical data center, but it may still need to address supplier-related risks and contractual requirements.

The SoA can therefore identify the relationship between organizational responsibility and third-party responsibility.

Another useful field is the **related requirement**.

For example:

```text
ISO 27001 Control
       ↓
Regulatory Requirement
       ↓
Contractual Requirement
       ↓
Internal Policy
```

This helps organizations avoid maintaining separate control inventories for every requirement.

A single control may support several obligations.

For example:

```text
Control:
Security Logging

Supports:
ISO 27001
NIST CSF
Internal Security Policy
Customer Contract
Regulatory Requirement
```

This is particularly valuable for organizations with multiple compliance obligations.

The SoA should also be version controlled.

A practical document header could contain:

```text
Document:
Statement of Applicability

Version:
2.0

Document Owner:
GRC Manager

Approved By:
CISO

Effective Date:
01 September 2026

Next Review:
01 September 2027
```

Changes should be documented.

For example:

```text
Version 1.0:
Initial SoA

Version 1.1:
Added supplier security control

Version 2.0:
Updated following ISMS scope expansion
```

The SoA should be reviewed when significant organizational changes occur.

Triggers may include:

* Changes to ISMS scope.
* New business processes.
* New technologies.
* New information assets.
* Significant risk changes.
* New regulatory requirements.
* Major security incidents.
* New suppliers.
* Business acquisitions.
* Major changes to the threat environment.
* Changes to the organization's risk treatment strategy.

For example:

```text
New Critical Cloud Service
        ↓
New Risk
        ↓
Risk Assessment
        ↓
Risk Treatment
        ↓
Control Selection
        ↓
SoA Review
```

This ensures that the SoA remains aligned with the actual ISMS.

The SoA can also be used as an **audit navigation tool**.

An auditor may select a control from the SoA and ask:

> Why is this control applicable?

The organization should be able to provide:

```text
Control
 ↓
Applicability Justification
 ↓
Risk
 ↓
Risk Treatment
 ↓
Implementation
 ↓
Evidence
```

If the auditor asks:

> How do you know the control is operating effectively?

the organization should be able to continue the chain:

```text
Evidence
 ↓
Control Assessment
 ↓
Test Results
 ↓
Corrective Actions
```

This demonstrates traceability throughout the ISMS.

A practical SoA table might look like:

| Control              | Applicable | Justification                    | Risk  | Implementation | Evidence           | Status    |
| -------------------- | ---------- | -------------------------------- | ----- | -------------- | ------------------ | --------- |
| Access Control       | Yes        | Addresses access risk            | R-001 | Implemented    | IAM Report         | Effective |
| Privileged Access    | Yes        | Addresses privileged access risk | R-002 | Partial        | PAM Report         | Partial   |
| Supplier Security    | Yes        | Critical suppliers exist         | R-005 | Implemented    | Vendor Assessments | Effective |
| Physical Data Center | No         | No owned data centers in scope   | —     | N/A            | Scope Statement    | N/A       |
| Security Awareness   | Yes        | Required to reduce human risk    | R-008 | Implemented    | Training Report    | Effective |

The SoA should be kept consistent with the organization's actual control environment.

For example, if the SoA says:

> Control implemented.

but the organization cannot provide evidence that the control exists, there is a traceability problem.

Similarly, if the SoA says:

> Control not applicable.

but the risk register contains a significant risk that clearly relates to the control, the organization should reassess the decision.

This is why the SoA should be maintained as a **living ISMS document** rather than created once for certification and then forgotten.

A useful relationship between the major ISO 27001 documents is:

```text
ISMS Scope
    ↓
Context and Requirements
    ↓
Risk Assessment
    ↓
Risk Treatment Plan
    ↓
Statement of Applicability
    ↓
Policies / Procedures
    ↓
Controls
    ↓
Evidence
    ↓
Internal Audit
    ↓
Management Review
    ↓
Continual Improvement
```

The SoA sits between risk treatment and operational control implementation.

This makes it a central document within the ISMS.

For a practical exercise, create a mini-SoA for the following risks:

```text
R-001 – Unauthorized Access
R-002 – Malware Infection
R-003 – Data Leakage
R-004 – Supplier Security Risk
R-005 – Loss of Critical Data
```

Select appropriate ISO/IEC 27001:2022 Annex A controls for each risk and create the following fields:

```text
Control Reference
Control Name
Applicable
Justification
Risk ID
Implementation Status
Control Owner
Evidence
Related Policy
Gap
```

Then create one example where a control is **not applicable**.

Document a specific justification explaining why the control is outside the organization's circumstances or ISMS scope.

Finally, create one example where a control is **applicable but only partially implemented**.

Document:

```text
Current Implementation
Control Gap
Associated Risk
Remediation Action
Control Owner
Target Date
```

This exercise demonstrates the difference between:

```text
Not Applicable
        ≠
Not Implemented
        ≠
Partially Implemented
        ≠
Ineffective
```

These distinctions are critical when preparing an organization for ISO/IEC 27001 certification or maintaining an existing ISMS.

The key principle is:

> **The Statement of Applicability should provide a defensible explanation of which controls are relevant to the ISMS, why they are applicable or not applicable, how they are implemented, and how they connect to the organization's risks and treatment decisions.**

Once the applicable controls have been identified and documented in the Statement of Applicability, the next step is to connect those controls to the organization's **ISMS risk assessment and risk treatment process**.

The purpose of the ISMS risk assessment is to identify information security risks, determine their significance, and provide a rational basis for selecting appropriate risk treatment options and controls.

A practical relationship is:

```text
Assets / Processes
       ↓
Threats and Vulnerabilities
       ↓
Risk Identification
       ↓
Risk Analysis
       ↓
Risk Evaluation
       ↓
Risk Treatment
       ↓
Control Selection
       ↓
Implementation
       ↓
Residual Risk
```

The risk assessment template should provide enough information for the organization to understand why a particular control was selected.

A practical **ISMS Risk Assessment Template** can contain:

```text
ISMS RISK ASSESSMENT

Risk ID:

Asset / Process:

Asset Owner:

Business Function:

Threat:

Vulnerability:

Risk Scenario:

Existing Controls:

Likelihood:

Impact:

Inherent Risk:

Risk Appetite / Criteria:

Risk Rating:

Risk Treatment Decision:

Additional Controls Required:

Risk Owner:

Target Date:

Residual Likelihood:

Residual Impact:

Residual Risk:

Risk Acceptance:

Evidence:

Assessment Date:

Next Review:

Comments:
```

The first step is identifying the **asset, process, or business activity** affected by the risk.

For example:

```text
Asset:
Customer Database

Business Process:
Customer Account Management

Information:
Personally Identifiable Information

Owner:
Customer Operations Manager
```

The assessment should then identify the relevant threat.

For example:

```text
Threat:
Unauthorized access

Vulnerability:
Excessive user privileges

Risk Scenario:
An employee with excessive privileges could access
customer information beyond their business requirements.
```

A well-written risk scenario should explain the relationship between the threat, vulnerability, and potential consequence.

For example:

> Excessive privileges could allow an unauthorized employee to access sensitive customer information, resulting in data disclosure, regulatory penalties, financial loss, and reputational damage.

This is more useful than simply recording:

> Data breach.

The GRC professional should be able to understand what could happen and why it matters.

Risk analysis normally considers at least two major dimensions:

```text
Likelihood
    +
Impact
    ↓
Risk Level
```

A simple scoring model may use a 1–5 scale.

| Score | Likelihood     |
| ----: | -------------- |
|     1 | Rare           |
|     2 | Unlikely       |
|     3 | Possible       |
|     4 | Likely         |
|     5 | Almost Certain |

Impact can similarly be assessed:

| Score | Impact        |
| ----: | ------------- |
|     1 | Insignificant |
|     2 | Minor         |
|     3 | Moderate      |
|     4 | Major         |
|     5 | Severe        |

A simple risk calculation can then be:

```text
Risk Score = Likelihood × Impact
```

For example:

```text
Likelihood = 4

Impact = 5

Risk Score = 4 × 5 = 20
```

The organization may classify 20 as High or Critical depending on its defined risk criteria.

The important point is that the organization should use a **documented and consistently applied methodology**.

The risk matrix might look like:

| Likelihood \ Impact |  1 |  2 |  3 |  4 |  5 |
| ------------------- | -: | -: | -: | -: | -: |
| 5                   |  5 | 10 | 15 | 20 | 25 |
| 4                   |  4 |  8 | 12 | 16 | 20 |
| 3                   |  3 |  6 |  9 | 12 | 15 |
| 2                   |  2 |  4 |  6 |  8 | 10 |
| 1                   |  1 |  2 |  3 |  4 |  5 |

The organization should then define what the scores mean.

For example:

| Score | Risk Level | Typical Treatment                |
| ----: | ---------- | -------------------------------- |
|   1–4 | Low        | Accept / Monitor                 |
|   5–9 | Medium     | Treat / Monitor                  |
| 10–16 | High       | Treatment Required               |
| 17–25 | Critical   | Immediate Treatment / Escalation |

The actual thresholds should be established by the organization and documented in its risk methodology.

The next step is identifying **existing controls**.

For example:

```text
Risk:
Unauthorized access to customer database

Existing Controls:
- Role-based access
- MFA
- Access approval
- Quarterly access review
- Privileged access monitoring
```

This allows the organization to determine whether existing controls are already reducing the risk.

The assessment should distinguish between **inherent risk** and **residual risk**.

Inherent risk represents the level of risk before considering the effectiveness of existing controls.

Residual risk represents the remaining risk after controls and treatment measures are considered.

For example:

```text
Inherent Risk:
Likelihood = 5
Impact = 5
Risk = 25
Critical

Existing Controls:
MFA
RBAC
PAM
Access Reviews

Residual Risk:
Likelihood = 2
Impact = 5
Risk = 10
High
```

The controls have reduced the likelihood, but the potential impact remains significant.

This distinction is extremely important in an ISMS.

A control does not necessarily eliminate a risk.

It may simply reduce the probability or impact of the risk occurring.

The risk treatment plan should then identify what the organization intends to do with the remaining risk.

The primary treatment options are:

```text
Avoid
Reduce / Modify
Share / Transfer
Retain
```

For example:

**Avoid**

> Discontinue a high-risk business activity.

**Reduce / Modify**

> Implement additional security controls.

**Share / Transfer**

> Transfer some financial or operational consequences through insurance or contractual arrangements.

**Retain**

> Accept the remaining risk when it is within the organization's defined risk acceptance criteria.

The selected treatment should be documented.

For example:

```text
Risk:
R-014 – Privileged Access Risk

Inherent Risk:
Critical

Treatment:
Reduce

Actions:
Implement PAM
Enforce MFA
Perform quarterly access reviews

Target Residual Risk:
Medium
```

The treatment plan should identify specific actions rather than vague statements.

A weak treatment action would be:

> Improve security.

A stronger action would be:

> Implement centralized privileged access management for all production infrastructure and require MFA for privileged sessions.

The second statement can be assigned, measured, and verified.

A practical **ISMS Risk Treatment Template** can contain:

```text
RISK TREATMENT PLAN

Risk ID:

Risk Description:

Current Risk Rating:

Treatment Option:

Treatment Objective:

Required Control:

Control Reference:

Treatment Action:

Action Owner:

Priority:

Resources Required:

Target Date:

Milestone:

Expected Risk Reduction:

Residual Risk Target:

Status:

Evidence:

Validation Method:

Approval:

Comments:
```

Each treatment action should have a clear owner.

For example:

| Risk              | Treatment                  | Owner                  | Target |
| ----------------- | -------------------------- | ---------------------- | ------ |
| Privileged Access | Implement PAM              | IAM Manager            | Q4     |
| Data Leakage      | Implement DLP              | Security Manager       | Q3     |
| Supplier Risk     | Vendor reassessment        | Vendor Manager         | Q3     |
| Backup Failure    | Implement recovery testing | Infrastructure Manager | Q4     |

This creates accountability.

Treatment actions should also have measurable outcomes.

For example:

```text
Current:
30% of privileged accounts covered by PAM

Target:
100% of privileged accounts covered by PAM
```

This is better than:

> Implement PAM.

The GRC professional should be able to determine whether the treatment action has actually achieved its intended objective.

The risk treatment process should also identify the **expected residual risk**.

For example:

```text
Current Risk:
High

Treatment:
Implement MFA + PAM

Expected Residual Risk:
Medium
```

After implementation, the organization should reassess the risk.

```text
Before Treatment
       ↓
High Risk
       ↓
Treatment Implemented
       ↓
Control Validated
       ↓
Risk Reassessment
       ↓
Residual Risk
```

The actual residual risk may be different from the expected residual risk.

For example:

```text
Expected:
Medium

Actual:
High
```

This indicates that the treatment did not reduce the risk as expected.

The organization may then need additional treatment.

Risk treatment should therefore be considered a continuous process rather than a one-time activity.

The risk register can connect all these activities.

For example:

| Risk ID | Inherent | Treatment       | Residual | Owner            | Status      |
| ------- | -------- | --------------- | -------- | ---------------- | ----------- |
| R-001   | Critical | PAM             | High     | IAM Manager      | In Progress |
| R-002   | High     | DLP             | Medium   | Security Manager | Implemented |
| R-003   | High     | Vendor Controls | Medium   | Vendor Manager   | In Progress |
| R-004   | Medium   | Backup Testing  | Low      | Infrastructure   | Complete    |

This provides management with a consolidated view.

The **ISMS risk assessment** should also consider different types of impact.

Depending on the organization's methodology, impact may include:

* Confidentiality.
* Integrity.
* Availability.
* Privacy.
* Financial impact.
* Legal impact.
* Regulatory impact.
* Operational impact.
* Reputational impact.
* Customer impact.

For example:

```text
Confidentiality: High
Integrity:       Medium
Availability:    Low
Privacy:         High
Regulatory:      High
Reputation:      High
```

The organization can then determine an overall impact rating based on its defined methodology.

This is particularly useful for organizations handling sensitive personal, financial, health, or customer information.

Risk assessment should also consider **business context**.

The same vulnerability can create different levels of risk for different organizations.

For example:

```text
Vulnerability:
Database unavailable for 4 hours
```

For a non-critical internal application, the impact might be Medium.

For a critical payment system, the impact could be Critical.

Risk assessment should therefore not rely entirely on technical severity.

The GRC professional must understand the business consequences.

This is one reason GRC professionals need to work closely with:

* Business owners.
* IT teams.
* Security teams.
* Legal.
* Compliance.
* Privacy.
* Procurement.
* Senior management.

The treatment plan should also identify **dependencies**.

For example:

```text
Treatment:
Implement MFA

Dependencies:
IAM platform
Identity provider
Application compatibility
User enrollment
Help desk support
```

If a treatment depends on another project, the risk treatment plan should identify that dependency.

This helps prevent unrealistic treatment deadlines.

The organization should also document **risk acceptance criteria**.

For example:

```text
Risk Level:
Low

Treatment:
Risk may be accepted by business owner.

Risk Level:
High

Treatment:
Requires documented management approval.

Risk Level:
Critical

Treatment:
Requires executive escalation and formal
treatment decision.
```

The exact authority levels should be defined in the organization's risk management methodology.

Risk acceptance should not be confused with ignoring the risk.

A formal risk acceptance should document:

```text
Risk
 ↓
Reason for Acceptance
 ↓
Residual Risk
 ↓
Business Owner
 ↓
Approval Authority
 ↓
Expiration / Review Date
```

For example:

```text
Risk:
Legacy Application Vulnerability

Residual Risk:
High

Reason:
Replacement project scheduled for Q1 2027.

Compensating Controls:
Network isolation
Restricted administrative access
Enhanced monitoring

Accepted By:
Business Owner

Approval:
CISO

Review Date:
31 December 2026
```

This makes the acceptance decision accountable and time-bound.

Risk treatment should also be connected to the **Statement of Applicability**.

For example:

```text
Risk R-014
     ↓
Treatment Decision
     ↓
Selected Control
     ↓
SoA
     ↓
Implementation
     ↓
Evidence
```

The SoA records the control decision, while the risk treatment documentation explains why the control was selected.

This creates a strong audit trail.

The GRC professional should be able to demonstrate:

> This risk was identified, evaluated, treated, and linked to a specific control.

This is much stronger than simply stating:

> We selected the control because ISO 27001 contains it.

The organization should also avoid selecting controls without understanding the risk they are intended to address.

For example:

```text
Weak Approach:

ISO Control
     ↓
Implement Control
     ↓
Find Risk Later
```

A stronger risk-based approach is:

```text
Risk
     ↓
Risk Treatment
     ↓
Control Selection
     ↓
Implementation
     ↓
Validation
```

The organization should also consider whether a treatment introduces **new risks**.

For example, implementing a new cloud security platform may reduce cybersecurity risk but introduce:

* Supplier dependency.
* Data residency concerns.
* Privacy considerations.
* Integration risks.
* Availability risks.
* New administrative privileges.

Therefore, significant treatments should be considered within the broader risk management process.

A practical **Risk Treatment Tracking Table** might look like:

| Risk  | Treatment Action          | Owner            | Due Date | Status      | Expected Residual Risk |
| ----- | ------------------------- | ---------------- | -------- | ----------- | ---------------------- |
| R-001 | Implement PAM             | IAM Manager      | Q4       | In Progress | Medium                 |
| R-002 | Deploy DLP                | Security Manager | Q3       | Complete    | Medium                 |
| R-003 | Reassess critical vendors | Vendor Manager   | Q3       | In Progress | Low                    |
| R-004 | Conduct recovery testing  | Infrastructure   | Q4       | Planned     | Low                    |

The treatment status should be periodically reviewed.

A simple status model could be:

```text
Not Started
     ↓
Planned
     ↓
In Progress
     ↓
Implemented
     ↓
Validated
     ↓
Closed
```

The **Validated** stage is particularly important.

A treatment should not automatically be considered complete simply because the technical implementation has finished.

For example:

> PAM was installed.

does not necessarily mean:

> Privileged access risk has been reduced.

The GRC team should verify that the control operates as intended.

For example:

```text
PAM Installed
      ↓
Accounts Onboarded
      ↓
Policies Configured
      ↓
MFA Enforced
      ↓
Privileged Sessions Monitored
      ↓
Control Tested
      ↓
Treatment Validated
```

This provides stronger evidence that risk treatment has achieved its objective.

For a practical exercise, create an ISMS risk assessment for:

> **Risk:** Unauthorized access to a customer database.

Use the following information:

```text
Asset:
Customer Database

Threat:
Unauthorized access

Vulnerability:
Excessive user privileges

Existing Controls:
MFA
RBAC
Access Reviews

Likelihood:
4

Impact:
5
```

Calculate the inherent risk and document:

```text
Risk ID
Risk Scenario
Existing Controls
Inherent Risk
Treatment Decision
Additional Controls
Risk Owner
Target Date
Expected Residual Risk
```

Then create a treatment plan for the risk.

For example:

```text
Treatment:
Reduce

Additional Controls:
Privileged Access Management
Enhanced Access Monitoring
Quarterly Access Review

Owner:
IAM Manager

Target:
31 December 2026
```

Finally, reassess the risk after the proposed controls have been implemented.

The exercise should demonstrate the complete relationship:

```text
Risk Identification
        ↓
Risk Assessment
        ↓
Risk Evaluation
        ↓
Risk Treatment
        ↓
Control Selection
        ↓
Control Implementation
        ↓
Residual Risk Assessment
        ↓
Risk Acceptance / Further Treatment
```

The key principle is:

> **ISO 27001 controls should be connected to the organization's actual information security risks and treatment decisions.**

A strong ISMS does not implement controls simply because they appear in a standard. It determines what the organization needs to protect, identifies the risks, evaluates those risks, selects appropriate treatments and controls, implements them, and then verifies whether the remaining risk is acceptable.
:::




