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

A **Control Relationship Diagram** shows how policies, control objectives, controls, control activities, evidence, testing, findings, and remediation relate to one another.

```text
Policy / Requirement
        ↓
Control Objective
        ↓
Control
        ↓
Control Activity
        ↓
Evidence
        ↓
Control Testing
        ↓
Control Result
        ↓
Finding / Exception
        ↓
Remediation
        ↓
Retesting
        ↓
Control Effectiveness
```

A control should exist for a specific reason. It should address a requirement, reduce a risk, or support a business objective.

```text
Business Objective
        ↓
Risk
        ↓
Control Objective
        ↓
Control
        ↓
Risk Reduction
```

For example:

```text
Business Objective:
Protect Customer Data

        ↓

Risk:
Unauthorized Access

        ↓

Control Objective:
Ensure only authorized users
can access customer data

        ↓

Control:
Quarterly Access Review

        ↓

Control Activity:
Manager reviews user access

        ↓

Evidence:
Approved Access Review Report
```

This relationship is important because a control should not exist simply because it has always existed.

A mature GRC professional should be able to explain:

```text
Why does this control exist?
        ↓
What risk does it address?
        ↓
What requirement does it support?
        ↓
Who owns it?
        ↓
How does it operate?
        ↓
What evidence does it produce?
        ↓
How is it tested?
```

A control can be viewed through several layers.

```text
                    CONTROL
                       │
       ┌───────────────┼───────────────┐
       ↓               ↓               ↓
    Purpose          Owner          Frequency
       ↓               ↓               ↓
 Risk / Requirement  Accountability  Operation
       │
       ↓
 Control Activity
       ↓
 Evidence
       ↓
 Testing
       ↓
 Effectiveness
```

Controls can also be classified according to their purpose.

```text
Controls
   │
   ├── Preventive
   │
   ├── Detective
   │
   ├── Corrective
   │
   ├── Deterrent
   │
   └── Compensating
```

A **preventive control** attempts to stop an unwanted event before it occurs.

```text
Unauthorized Login
       ↓
MFA
       ↓
Access Blocked
```

A **detective control** identifies an event after or while it occurs.

```text
Suspicious Activity
       ↓
Security Monitoring
       ↓
Alert
       ↓
Investigation
```

A **corrective control** helps restore the environment after an issue.

```text
Security Incident
       ↓
Recovery Procedure
       ↓
System Restored
```

A **deterrent control** is designed to discourage undesirable behavior.

```text
Unauthorized Activity
       ↓
Warning / Monitoring / Sanctions
       ↓
Reduced Likelihood of Misconduct
```

A **compensating control** provides an alternative when the primary control cannot be implemented or is insufficient.

```text
Primary Control
       ↓
Not Available / Not Feasible
       ↓
Compensating Control
       ↓
Risk Reduced
```

Controls can also be categorized according to their nature.

```text
Control Type
    │
    ├── Administrative
    ├── Technical
    └── Physical
```

For example:

```text
Administrative
    ↓
Security Policy

Technical
    ↓
MFA

Physical
    ↓
Data Center Access Control
```

A mature control framework may combine these classifications.

```text
Control:
Privileged Access Management

Purpose:
Preventive

Nature:
Technical

Frequency:
Continuous

Owner:
IAM Manager
```

The relationship between a control and its **control objective** is especially important.

```text
Control Objective
        ↓
What should the control achieve?
        ↓
Control
        ↓
How will the objective be achieved?
```

For example:

```text
Control Objective:
Ensure privileged access is authorized

        ↓

Controls:
PAM
MFA
Approval Workflow
Periodic Access Review
Session Monitoring
```

One control objective may therefore be supported by multiple controls.

```text
             Control Objective
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
       PAM         MFA       Access Review
```

Conversely, one control may support multiple control objectives.

```text
             MFA
              ↓
     ┌────────┼────────┐
     ↓        ↓        ↓
Access     Identity   Remote
Security   Assurance   Access
```

This many-to-many relationship is common in mature GRC environments.

Controls should also have clearly defined **owners**.

```text
Control
   ↓
Control Owner
   ↓
Accountability
```

The control owner is responsible for ensuring that the control is appropriately designed, implemented, maintained, and monitored.

The control operator may be a different person.

```text
Control Owner
      ↓
Accountable for Control
      ↓
Control Operator
      ↓
Performs Control Activity
```

For example:

```text
Control Owner:
IAM Manager

        ↓

Control Operator:
IAM Analyst

        ↓

Activity:
Perform Quarterly Access Review
```

The GRC team may then independently monitor or assess the control.

```text
Control Owner
      ↓
Operates Control

GRC
      ↓
Monitors / Challenges / Assesses

Internal Audit
      ↓
Provides Independent Assurance
```

This separation helps maintain accountability and independence.

Control frequency should also be defined.

```text
Control Frequency
       │
       ├── Continuous
       ├── Real-time
       ├── Daily
       ├── Weekly
       ├── Monthly
       ├── Quarterly
       ├── Annually
       └── Event-driven
```

For example:

```text
MFA
 ↓
Continuous

Vulnerability Scanning
 ↓
Weekly

Access Review
 ↓
Quarterly

Security Policy Review
 ↓
Annual
```

Frequency should be appropriate to the risk.

A high-risk control performed annually may be insufficient if the risk can change rapidly.

The relationship between **risk frequency and control frequency** can be represented as:

```text
Rapidly Changing Risk
        ↓
More Frequent Monitoring

Stable Risk
        ↓
Periodic Monitoring
```

Controls should also have defined evidence requirements.

```text
Control
   ↓
Control Activity
   ↓
Evidence
```

For example:

```text
Control:
Quarterly Access Review

Activity:
Review user access

Evidence:
Access Review Report
Approval Record
Exception List
Remediation Record
```

Good evidence should demonstrate that the control actually operated.

```text
Evidence
   ↓
Who performed it?
What was performed?
When was it performed?
What was reviewed?
What was the result?
Were exceptions identified?
Was remediation completed?
```

The control testing relationship can then be represented as:

```text
Control
   ↓
Test Procedure
   ↓
Evidence Review
   ↓
Testing Result
```

For example:

```text
Control:
Quarterly Access Review

        ↓

Test:
Sample three quarters

        ↓

Review:
Access review evidence

        ↓

Result:
Control operating effectively
```

Control testing should consider both **design effectiveness** and **operating effectiveness**.

```text
Control
   ↓
Design Effectiveness
   ↓
Is the control appropriately designed?
   ↓
Operating Effectiveness
   ↓
Does the control operate as intended?
```

A control can therefore fail in different ways.

```text
Poor Design
     ↓
Control cannot adequately address risk
```

or:

```text
Good Design
     ↓
Poor Execution
     ↓
Control Failure
```

or:

```text
Good Design
     ↓
Good Execution
     ↓
Effective Control
```

The control lifecycle can therefore be represented as:

```text
Control Requirement
        ↓
Control Design
        ↓
Control Approval
        ↓
Control Implementation
        ↓
Control Operation
        ↓
Evidence Collection
        ↓
Control Testing
        ↓
Effectiveness Assessment
        ↓
Improvement
        ↓
Control Review
```

Controls should also be reviewed when the organization's environment changes.

```text
Business Change
      ↓
Technology Change
      ↓
Regulatory Change
      ↓
Threat Change
      ↓
Control Review
```

For example:

```text
New Cloud Platform
      ↓
Existing Control Review
      ↓
Control Still Appropriate?
     ↙             ↘
   Yes              No
    ↓                ↓
Continue         Redesign
                    ↓
                 Implement
```

This prevents the organization from relying on obsolete controls.

Controls should also be linked to risks.

```text
Risk
 ↓
Control
 ↓
Control Effectiveness
 ↓
Residual Risk
```

For example:

```text
Risk:
Ransomware

Controls:
EDR
Backups
Network Segmentation
Email Security
Security Awareness

        ↓

Control Effectiveness

        ↓

Residual Ransomware Risk
```

If a control fails, the risk may increase.

```text
Control Failure
      ↓
Risk Exposure Increases
      ↓
Residual Risk Reassessment
      ↓
Additional Treatment
```

This creates an important GRC feedback loop.

```text
Risk
 ↓
Control
 ↓
Testing
 ↓
Failure
 ↓
Finding
 ↓
Remediation
 ↓
Retesting
 ↓
Risk Reassessment
```

Controls should also be mapped to compliance requirements.

```text
ISO 27001 ──┐
NIS2 ───────┤
DORA ───────┤
GDPR ───────┤
NIST ───────┘
       ↓
Common Control
       ↓
Evidence
       ↓
Testing
```

This is the foundation of a common control framework.

A control can also have **dependencies**.

For example:

```text
Access Review
      ↓
Requires Accurate User Inventory
      ↓
Requires Identity Management
      ↓
Requires HR Joiner/Mover/Leaver Data
```

Therefore:

```text
Control A
   ↓
Dependency
   ↓
Control B
   ↓
Dependency
   ↓
Control C
```

If a dependent control fails, the effectiveness of another control may be affected.

For example:

```text
HR Termination Process
        ↓
Identity Deprovisioning
        ↓
Access Removal
        ↓
Quarterly Access Review
```

This demonstrates why controls should not always be assessed in isolation.

A control environment can also contain **control layers**.

```text
Threat
  ↓
Preventive Control
  ↓
Detective Control
  ↓
Corrective Control
  ↓
Recovery
```

For ransomware:

```text
Email Security
      ↓
Endpoint Protection
      ↓
EDR Detection
      ↓
Incident Response
      ↓
Backup Recovery
```

This is known as **defense in depth**.

The overall control relationship can therefore be summarized as:

```text
                   BUSINESS OBJECTIVE
                          ↓
                         RISK
                          ↓
                   CONTROL OBJECTIVE
                          ↓
                        CONTROL
                          ↓
                  CONTROL OWNER
                          ↓
                  CONTROL ACTIVITY
                          ↓
                       EVIDENCE
                          ↓
                    CONTROL TEST
                          ↓
               ┌──────────┴──────────┐
               ↓                     ↓
            EFFECTIVE            INEFFECTIVE
               ↓                     ↓
        Continue Monitoring       FINDING
                                     ↓
                                REMEDIATION
                                     ↓
                                   RETEST
                                     ↓
                                VALIDATION
                                     ↓
                                EFFECTIVE
```

A mature GRC professional should be able to trace any important control through this complete chain:

```text
Requirement
    ↓
Risk
    ↓
Control Objective
    ↓
Control
    ↓
Owner
    ↓
Activity
    ↓
Evidence
    ↓
Testing
    ↓
Effectiveness
    ↓
Finding
    ↓
Remediation
    ↓
Residual Risk
```

The key principle is:

> **A control is not simply a policy, procedure, or technology. It is a defined mechanism designed and operated to achieve a specific control objective, address risk, satisfy requirements, and provide demonstrable assurance that the intended outcome is being achieved.**

# 18.4 Compliance and Control Diagrams

A **Compliance Assessment and Gap Analysis Diagram** shows how an organization evaluates its current control environment against applicable requirements, identifies gaps, assesses their significance, and drives remediation.

The overall process is:

```text
Applicable Requirement
        ↓
Current Control Environment
        ↓
Compliance Assessment
        ↓
Gap Identification
        ↓
Gap Analysis
        ↓
Risk Assessment
        ↓
Remediation Plan
        ↓
Implementation
        ↓
Validation
        ↓
Compliance Reassessment
```

The first step is determining which requirements apply to the organization.

```text
Laws
Regulations
Standards
Contracts
Customer Requirements
Internal Policies
        ↓
Applicability Assessment
        ↓
Applicable Requirements
```

Not every requirement applies to every organization, business unit, system, or process.

For example:

```text
Regulation
     ↓
Applicability Assessment
     ↓
Applicable?
   ↙       ↘
 Yes        No
  ↓          ↓
Assess     Document
           Rationale
```

The organization should maintain evidence supporting why a requirement is considered applicable or not applicable.

The next step is mapping the applicable requirements to controls.

```text
Applicable Requirement
        ↓
Control Objective
        ↓
Existing Control
        ↓
Control Assessment
```

The assessment should determine whether the control:

```text
Exists
Implemented
Designed Correctly
Operating Effectively
Produces Evidence
Meets Requirement
```

A simple assessment model is:

```text
Requirement
     ↓
Control Exists?
   ↙        ↘
 Yes         No
  ↓           ↓
Assess       Gap
Control
  ↓
Effective?
 ↙      ↘
Yes      No
 ↓        ↓
Compliant Gap
```

A compliance gap exists when the current environment does not adequately satisfy an applicable requirement.

For example:

```text
Requirement:
MFA for privileged access

        ↓

Current State:
Password-only access

        ↓

Gap Identified:
MFA not implemented

        ↓

Compliance Gap
```

The difference between **current state** and **target state** is central to gap analysis.

```text
TARGET STATE
What should exist?
        ↓
       GAP
        ↑
CURRENT STATE
What actually exists?
```

This can be represented as:

```text
Current State
      ↓
      GAP
      ↓
Target State
```

For example:

```text
Current:
Annual Access Review

Target:
Quarterly Access Review

        ↓

Gap:
Review Frequency Insufficient
```

A gap may be related to different aspects of the control environment.

```text
Gap
 │
 ├── Control Missing
 ├── Control Not Implemented
 ├── Control Poorly Designed
 ├── Control Ineffective
 ├── Evidence Missing
 ├── Process Inconsistent
 ├── Ownership Unclear
 └── Requirement Not Fully Addressed
```

This distinction is important because the remediation approach depends on the type of gap.

For example:

```text
Missing Control
      ↓
Design and Implement Control
```

Whereas:

```text
Existing Control
      ↓
Poor Evidence
      ↓
Improve Evidence Collection
```

And:

```text
Existing Control
      ↓
Ineffective Operation
      ↓
Correct Execution / Training / Monitoring
```

The assessment should also distinguish between **control deficiency** and **compliance gap**.

```text
Control Deficiency
      ↓
Control does not operate as intended
```

while:

```text
Compliance Gap
      ↓
Requirement is not adequately satisfied
```

They can overlap, but they are not always identical.

For example:

```text
Strong Control
      ↓
Requirement Not Fully Addressed
      ↓
Compliance Gap
```

Or:

```text
Control Weakness
      ↓
Requirement Still Satisfied
      ↓
Potential Control Improvement
```

A mature assessment therefore considers both compliance and risk.

```text
Compliance Gap
      ↓
Risk Assessment
      ↓
Risk Level
      ↓
Treatment Priority
```

For example:

```text
Critical Regulatory Gap
        ↓
High Compliance Risk
        ↓
Immediate Remediation
```

A low-impact documentation gap may receive a different priority:

```text
Minor Documentation Gap
        ↓
Low Risk
        ↓
Normal Improvement Cycle
```

Gap analysis should therefore not be based only on the number of gaps.

An organization with ten minor gaps may have less exposure than an organization with one critical gap.

```text
10 Minor Gaps
      ≠
1 Critical Gap
```

The organization should establish a **gap severity methodology**.

For example:

```text
Critical
   ↓
Immediate Management Attention

High
   ↓
Priority Remediation

Medium
   ↓
Planned Remediation

Low
   ↓
Continuous Improvement
```

The exact thresholds should be defined by the organization's governance framework.

A gap assessment can also incorporate business impact.

```text
Gap
 ↓
Potential Impact
 ↓
Likelihood
 ↓
Risk
 ↓
Priority
```

A useful prioritization model is:

```text
Risk Severity
      +
Regulatory Importance
      +
Business Impact
      +
Remediation Complexity
      ↓
Remediation Priority
```

This helps management determine which gaps should be addressed first.

A complete gap analysis can therefore be represented as:

```text
Requirement
      ↓
Current State
      ↓
Target State
      ↓
Gap
      ↓
Risk
      ↓
Priority
      ↓
Remediation
```

The assessment should also identify the **gap owner**.

```text
Gap
 ↓
Gap Owner
 ↓
Remediation Owner
 ↓
Due Date
 ↓
Status
```

The gap owner is accountable for ensuring the issue is addressed.

For example:

```text
Gap:
Privileged accounts not reviewed quarterly

Gap Owner:
IAM Manager

Remediation:
Implement quarterly certification

Due Date:
Q4

Status:
In Progress
```

The remediation process can then be visualized:

```text
Gap Identified
      ↓
Gap Validated
      ↓
Risk Rated
      ↓
Remediation Assigned
      ↓
Action Plan
      ↓
Implementation
      ↓
Evidence Submitted
      ↓
Validation
      ↓
Retest
      ↓
Gap Closed
```

A gap should not be considered closed simply because management says the remediation is complete.

There should be evidence demonstrating that the remediation actually addressed the deficiency.

```text
Remediation Completed
        ↓
Evidence
        ↓
Independent / GRC Validation
        ↓
Effective?
     ↙        ↘
   Yes         No
    ↓           ↓
  Close      Reopen
              Gap
```

This creates an important distinction between:

```text
Remediation Complete
```

and:

```text
Remediation Validated
```

The second provides stronger assurance.

Compliance assessments can also generate multiple findings from a single requirement.

```text
Requirement
      ↓
Assessment
      ↓
 ┌────┼────┐
 ↓    ↓    ↓
Gap  Gap  Gap
```

For example:

```text
Access Control Requirement
        ↓
 ┌──────┼──────────┐
 ↓      ↓          ↓
MFA    Access     Privileged
Gap    Review Gap Access Gap
```

Each gap can then have a separate remediation action.

The assessment should also identify **partial compliance**.

```text
Requirement
      ↓
Control
      ↓
Partially Implemented
      ↓
Partial Compliance
      ↓
Gap Analysis
```

For example:

```text
Requirement:
Security Awareness Training

Current State:
Annual training exists

Missing:
Role-based training
New-hire training
Effectiveness measurement

        ↓

Partial Compliance
```

This is more informative than simply marking the requirement as "compliant" or "non-compliant."

A compliance maturity model can also be incorporated.

```text
Level 1
Ad Hoc
   ↓
Level 2
Developing
   ↓
Level 3
Defined
   ↓
Level 4
Managed
   ↓
Level 5
Optimized
```

The organization can assess not only whether a control exists, but how mature its implementation is.

For example:

```text
Access Management

Level 1:
Manual / Ad Hoc

Level 2:
Basic Procedures

Level 3:
Standardized Process

Level 4:
Automated Monitoring

Level 5:
Continuous Optimization
```

This allows gap analysis to support long-term improvement rather than only regulatory compliance.

The same assessment can be performed across multiple frameworks.

```text
ISO 27001
     ↓
NIS2
     ↓
DORA
     ↓
GDPR
     ↓
NIST
     ↓
Common Control Framework
     ↓
Unified Gap Analysis
```

This prevents organizations from performing completely separate assessments for each framework.

For example:

```text
Requirement A ──┐
Requirement B ──┤
Requirement C ──┼──→ Common Control
Requirement D ──┤
Requirement E ──┘
                       ↓
                 One Assessment
                       ↓
                  Multiple Results
```

A GRC platform can then maintain relationships between:

```text
Requirement
     ↓
Control
     ↓
Assessment
     ↓
Finding
     ↓
Risk
     ↓
Remediation
     ↓
Evidence
```

This provides traceability across the entire compliance lifecycle.

A compliance dashboard can summarize the assessment.

```text
Total Requirements
        ↓
      250

Compliant
        ↓
      190

Partially Compliant
        ↓
       35

Non-Compliant
        ↓
       20

Not Applicable
        ↓
        5
```

The dashboard can also display gaps by severity.

```text
Critical:   2
High:       8
Medium:    15
Low:       10
```

Trend reporting can show whether compliance is improving.

```text
Q1 → 72% Compliant
Q2 → 78% Compliant
Q3 → 84% Compliant
Q4 → 91% Compliant
```

However, percentage compliance should be interpreted carefully.

A high compliance percentage does not automatically mean low risk.

For example:

```text
98% Compliance
      ↓
2% Critical Gap
      ↓
Potentially Significant Risk
```

Therefore, management reporting should combine:

```text
Compliance Status
      +
Risk Severity
      +
Critical Gaps
      +
Remediation Progress
      +
Risk Appetite
```

A useful executive diagram is:

```text
Compliance Assessment
        ↓
 ┌──────┼────────┐
 ↓      ↓        ↓
Compliant Gaps   Risks
        ↓        ↓
   Remediation   ↓
        ↓        ↓
     Progress  Exposure
        └───────┬┘
                ↓
        Management Decision
```

Compliance assessments should also be repeated periodically.

```text
Assessment
    ↓
Gap Analysis
    ↓
Remediation
    ↓
Validation
    ↓
Reassessment
    ↓
New Gaps?
   ↙      ↘
 No        Yes
 ↓          ↓
Continue   Remediate
Monitoring
```

This creates a continuous compliance improvement cycle.

```text
Assess
  ↓
Identify
  ↓
Prioritize
  ↓
Remediate
  ↓
Validate
  ↓
Report
  ↓
Reassess
  ↺
```

Changes in the organization can trigger an unscheduled assessment.

Examples include:

```text
New Regulation
New Technology
New Business Process
New Supplier
Security Incident
Major Acquisition
Cloud Migration
Organizational Change
Audit Finding
```

For example:

```text
New Regulation
      ↓
Applicability Assessment
      ↓
New Requirements
      ↓
Control Mapping
      ↓
Gap Assessment
      ↓
Remediation
```

The complete compliance gap analysis lifecycle can therefore be represented as:

```text
                 APPLICABLE REQUIREMENTS
                          ↓
                   CONTROL MAPPING
                          ↓
                    CURRENT STATE
                          ↓
                     ASSESSMENT
                          ↓
                    TARGET STATE
                          ↓
                   GAP IDENTIFICATION
                          ↓
                     GAP ANALYSIS
                          ↓
                    RISK ASSESSMENT
                          ↓
                   PRIORITIZATION
                          ↓
                  REMEDIATION PLAN
                          ↓
                     IMPLEMENTATION
                          ↓
                       EVIDENCE
                          ↓
                      VALIDATION
                          ↓
                       RETESTING
                          ↓
                    GAP RESOLUTION
                          ↓
                    REPORTING
                          ↓
                    REASSESSMENT
                          ↺
```

The relationship between compliance, risk, and controls can be summarized as:

```text
              REQUIREMENT
                   ↓
                CONTROL
                   ↓
                CONTROL
              EFFECTIVENESS
                   ↓
            COMPLIANCE STATUS
                   ↓
              COMPLIANCE GAP
                   ↓
                  RISK
                   ↓
              PRIORITIZATION
                   ↓
              REMEDIATION
                   ↓
            RESIDUAL RISK
                   ↓
             REASSESSMENT
```

The key principle is:

> **Compliance gap analysis should not simply identify what is missing. It should determine the difference between the required state and the current state, understand the associated risk, prioritize the gap, drive remediation, and verify that the remediation actually achieved the intended outcome.**



