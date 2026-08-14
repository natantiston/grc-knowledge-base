# 18.4 Compliance and Control Diagrams

## Part 1 – Compliance-to-Control Mapping Diagram

A **Compliance-to-Control Mapping Diagram** visually shows how external requirements are translated into internal policies, control objectives, controls, evidence, testing, findings, and remediation.

This is one of the most useful diagrams in GRC because organizations rarely manage only one regulatory or security framework.

A basic compliance-to-control relationship is:

```text
Regulation / Standard
        ↓
Requirement
        ↓
Control Objective
        ↓
Control
        ↓
Evidence
        ↓
Control Testing
        ↓
Compliance Assessment
        ↓
Finding
        ↓
Remediation
```

The fundamental principle is:

```text
Requirement
     ↓
What must the organization achieve?
     ↓
Control Objective
     ↓
How will the organization achieve it?
     ↓
Control
     ↓
How can the organization demonstrate it?
     ↓
Evidence
```

For example:

```text
Security Requirement
        ↓
Access must be appropriately restricted
        ↓
Control Objective
        ↓
Ensure only authorized users receive access
        ↓
Access Control
        ↓
User Access Review
        ↓
Access Review Evidence
```

The compliance-to-control mapping should begin with the applicable **authority or source**.

Possible sources include:

```text
Laws
Regulations
Standards
Contracts
Internal Policies
Customer Requirements
Industry Requirements
Risk Requirements
```

These can be represented as:

```text
External Requirements
        │
        ├── Laws
        ├── Regulations
        ├── Standards
        ├── Contracts
        └── Industry Requirements
                 ↓
          Internal Requirements
                 ↓
               Controls
```

An organization may need to map several frameworks to the same control environment.

For example:

```text
ISO 27001
NIS2
DORA
GDPR
NIST CSF
Customer Requirements
        ↓
Common Control Framework
        ↓
Enterprise Controls
```

This avoids creating separate controls for every framework.

A single control can satisfy multiple requirements.

For example:

```text
ISO 27001 Requirement ──┐
NIS2 Requirement ────────┤
DORA Requirement ────────┤
NIST Requirement ────────┤
Customer Requirement ────┘
             ↓
      Access Control
             ↓
      Access Review
```

This is known as **control cross-mapping** or **common control mapping**.

The objective is to reduce duplicated work.

Instead of:

```text
Framework A
    ↓
Separate Assessment

Framework B
    ↓
Separate Assessment

Framework C
    ↓
Separate Assessment
```

a mature GRC program can use:

```text
Multiple Requirements
        ↓
Common Control
        ↓
Common Evidence
        ↓
Common Testing
        ↓
Multiple Compliance Assessments
```

A detailed compliance-to-control mapping can be represented as:

```text
Requirement
     ↓
Requirement ID
     ↓
Control Objective
     ↓
Control ID
     ↓
Control Description
     ↓
Control Owner
     ↓
Evidence
     ↓
Test Procedure
     ↓
Test Result
     ↓
Finding
     ↓
Remediation
```

For example:

```text
Requirement:
Access must be reviewed periodically

        ↓

Control Objective:
Ensure user access remains appropriate

        ↓

Control:
Quarterly User Access Review

        ↓

Control Owner:
IAM Manager

        ↓

Evidence:
Quarterly Access Review Report

        ↓

Testing:
Sample 25 User Accounts

        ↓

Result:
Effective

        ↓

Compliance Status:
Compliant
```

If the control fails:

```text
Control Testing
      ↓
Failure
      ↓
Finding
      ↓
Risk Assessment
      ↓
Remediation
      ↓
Retesting
      ↓
Closure
```

The mapping therefore creates a complete traceability chain:

```text
Requirement
      ↓
Control
      ↓
Evidence
      ↓
Testing
      ↓
Finding
      ↓
Remediation
```

This traceability is particularly important during audits and regulatory examinations.

A GRC professional should be able to answer:

```text
What requirement are we addressing?

Which control addresses it?

Who owns the control?

What evidence proves it operates?

When was it tested?

What was the result?

Were exceptions identified?

Who is responsible for remediation?
```

A **compliance obligation** may also map to multiple controls.

For example:

```text
Requirement:
Protect Sensitive Information
             ↓
       ┌─────┼─────┐
       ↓     ↓     ↓
   Encryption IAM  DLP
       ↓     ↓     ↓
    Evidence Evidence Evidence
```

This is important because one control may not be sufficient to fully satisfy a requirement.

A requirement can therefore have a one-to-many relationship:

```text
One Requirement
      ↓
Multiple Controls
```

while a control can also have a many-to-many relationship:

```text
Multiple Requirements
      ↓
Common Control
```

This creates a mapping structure such as:

```text
Requirement A ──┐
Requirement B ──┼──→ Control 001
Requirement C ──┘

Requirement D ──┐
Requirement E ──┼──→ Control 002
Requirement F ──┘
```

A GRC platform can use this relationship to support centralized compliance management.

The control mapping should also distinguish between **control design** and **control operating effectiveness**.

```text
Requirement
     ↓
Control Design
     ↓
Is the control appropriately designed?
     ↓
Control Implementation
     ↓
Is the control actually implemented?
     ↓
Operating Effectiveness
     ↓
Does the control work consistently?
```

For example:

```text
Access Review Control
       ↓
Designed Correctly?
       ↓
Implemented?
       ↓
Performed Quarterly?
       ↓
Evidence Available?
       ↓
Exceptions Identified?
       ↓
Effective?
```

A control can therefore be:

```text
Well Designed + Not Implemented
```

or:

```text
Implemented + Ineffective
```

or:

```text
Well Designed + Implemented + Effective
```

These distinctions are important in compliance assessments.

A mature compliance diagram should therefore show:

```text
Requirement
      ↓
Control Design
      ↓
Implementation
      ↓
Operation
      ↓
Evidence
      ↓
Testing
      ↓
Effectiveness
```

Evidence is another critical part of the mapping.

A control should produce appropriate evidence demonstrating that it operated.

For example:

```text
Control:
Quarterly Access Review

        ↓

Evidence:
Access Review Report

        ↓

Supporting Evidence:
Approval Records
Exception Records
Review Logs

        ↓

Testing
```

Evidence should normally demonstrate:

```text
Who?
What?
When?
How?
Result?
Approval?
Exceptions?
```

For example:

```text
Who:
IAM Manager

What:
Reviewed privileged accounts

When:
Q3 2026

How:
Compared accounts against approved access

Result:
3 unauthorized accounts identified

Action:
Access removed
```

This creates stronger audit evidence than simply stating:

```text
"Access reviews are performed."
```

The diagram can therefore be expanded:

```text
Requirement
      ↓
Control
      ↓
Control Activity
      ↓
Evidence
      ↓
Testing
      ↓
Conclusion
```

Compliance status can then be determined.

```text
Control Assessment
        ↓
Effective?
    ↙        ↘
  Yes         No
   ↓           ↓
Compliant   Non-Compliant /
            Finding
```

However, organizations may use additional classifications such as:

```text
Compliant
Partially Compliant
Non-Compliant
Not Applicable
Not Tested
In Progress
```

The exact terminology should be defined by the organization's assessment methodology.

The compliance-to-control mapping also supports **gap analysis**.

```text
Requirement
      ↓
Mapped Control
      ↓
Control Exists?
   ↙          ↘
 Yes           No
  ↓             ↓
Assess       Gap Identified
Effectiveness    ↓
  ↓          Remediation
Effective?
 ↙       ↘
Yes       No
 ↓         ↓
Compliant  Control Gap
```

This allows organizations to identify where requirements are not adequately addressed.

A complete compliance gap model is:

```text
Regulatory Requirement
        ↓
Control Mapping
        ↓
Control Exists?
        ↓
Control Implemented?
        ↓
Control Effective?
        ↓
Evidence Available?
        ↓
Compliance Status
```

The mapping can also connect compliance gaps to organizational risk.

```text
Compliance Gap
      ↓
Control Weakness
      ↓
Risk Assessment
      ↓
Risk Rating
      ↓
Treatment
      ↓
Remediation
```

For example:

```text
Missing MFA
      ↓
Control Gap
      ↓
Unauthorized Access Risk
      ↓
High Risk
      ↓
MFA Implementation
      ↓
Risk Reduction
```

This creates a powerful GRC relationship:

```text
Compliance
     ↓
Control
     ↓
Risk
     ↓
Treatment
```

Compliance should therefore not operate separately from enterprise risk management.

Another important concept is **control inheritance**.

A control may be centrally implemented and inherited by multiple business units or systems.

For example:

```text
Enterprise Identity Platform
          ↓
     Central MFA
          ↓
 ┌────────┼────────┐
 ↓        ↓        ↓
Business A Business B Business C
```

Instead of each business unit independently implementing MFA, they may inherit the enterprise control.

The compliance mapping can then show:

```text
Requirement
      ↓
Enterprise Control
      ↓
Inherited Control
      ↓
Business Unit
      ↓
Evidence
```

This can improve consistency and reduce duplicated implementation effort.

The same principle applies to cloud environments.

```text
Cloud Provider
      ↓
Inherited Security Controls
      ↓
Customer Responsibilities
      ↓
Customer Controls
      ↓
Combined Control Environment
```

The organization must clearly identify which controls are inherited and which remain its responsibility.

The mapping can also support **control rationalization**.

Organizations often accumulate hundreds or thousands of controls.

A mature GRC program can identify duplicate controls:

```text
Control A
"Review user access quarterly"

Control B
"Perform quarterly access certification"

Control C
"Validate user access every quarter"
```

These may represent essentially the same control objective.

The organization can rationalize them into:

```text
Common Control
Quarterly User Access Review
```

Then map multiple requirements to the common control.

```text
ISO 27001 ──┐
NIS2 ───────┤
DORA ───────┼──→ Common Access Review Control
GDPR ───────┤
NIST ───────┘
```

This reduces:

* Duplicate controls
* Duplicate evidence requests
* Duplicate testing
* Administrative effort
* Conflicting requirements

The compliance-to-control diagram can therefore become a **Common Control Framework**:

```text
External Requirements
        ↓
Requirement Library
        ↓
Control Objectives
        ↓
Common Controls
        ↓
Control Owners
        ↓
Evidence
        ↓
Testing
        ↓
Compliance Results
```

The final end-to-end diagram can be represented as:

```text
                    LAWS / REGULATIONS /
                  STANDARDS / CONTRACTS
                            ↓
                     REQUIREMENTS
                            ↓
                    CONTROL OBJECTIVES
                            ↓
                    COMMON CONTROLS
                            ↓
                  CONTROL IMPLEMENTATION
                            ↓
                     CONTROL OWNER
                            ↓
                     CONTROL OPERATION
                            ↓
                         EVIDENCE
                            ↓
                      CONTROL TESTING
                            ↓
                ┌───────────┴───────────┐
                ↓                       ↓
             EFFECTIVE              INEFFECTIVE
                ↓                       ↓
           COMPLIANT                 FINDING
                                        ↓
                                  REMEDIATION
                                        ↓
                                     RETEST
                                        ↓
                                   VALIDATION
                                        ↓
                                     CLOSURE
```

The broader GRC relationship can be summarized as:

```text
Requirement
      ↓
Control
      ↓
Risk
      ↓
Evidence
      ↓
Assessment
      ↓
Finding
      ↓
Remediation
      ↓
Residual Risk
      ↓
Management Reporting
```

This makes the compliance-to-control mapping one of the most important foundations of an effective GRC program.

The key principle is:

> **Every significant compliance requirement should be traceable to an appropriate control, and every important control should be traceable to an owner, evidence, testing, and a defined compliance or risk outcome.**



