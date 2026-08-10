Below is the reconstructed **17.5 Part 1**, following the original Chapter 17 outline and keeping it practical.

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



