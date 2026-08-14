# 18.5 Control Framework Diagrams

### Part 1 – Control Lifecycle

Controls are one of the central building blocks of GRC. They translate requirements, risks, and objectives into **specific actions or mechanisms designed to prevent, detect, or correct undesirable events**.

A control should not be viewed as a static item in a spreadsheet. It has a lifecycle that includes design, implementation, operation, testing, evaluation, remediation, and continuous improvement.

The basic lifecycle can be represented as:

```text
Requirement / Risk
       ↓
Control Objective
       ↓
Control Design
       ↓
Control Implementation
       ↓
Control Operation
       ↓
Control Testing
       ↓
Control Evaluation
       ↓
Finding / Improvement
       ↓
Remediation
       ↓
Retesting
       ↓
Continuous Improvement
       ↺
```

This lifecycle demonstrates an important principle:

> **A control is only valuable when it is appropriately designed, implemented, operating, and demonstrably effective.**

---

## What Is a GRC Control?

A control is a measure designed to **modify or manage risk** and help an organization achieve its objectives.

Controls may be:

* Policies
* Procedures
* Technical configurations
* Automated mechanisms
* Manual activities
* Management reviews
* Segregation of duties
* Monitoring activities
* Approvals
* Reconciliations
* Security mechanisms

For example:

```text
Risk
 ↓
Unauthorized Access
 ↓
Control
 ↓
Multi-Factor Authentication
 ↓
Evidence
 ↓
Authentication Logs
```

The control exists because there is a risk or requirement that needs to be addressed.

---

## Control Lifecycle Overview

A practical control lifecycle can be divided into nine major stages:

```text
1. Identify Requirement / Risk
             ↓
2. Define Control Objective
             ↓
3. Design Control
             ↓
4. Implement Control
             ↓
5. Operate Control
             ↓
6. Test Control
             ↓
7. Evaluate Effectiveness
             ↓
8. Remediate Deficiencies
             ↓
9. Monitor and Improve
             ↺
```

Each stage has a different purpose.

---

# 1. Identify the Requirement or Risk

A control normally originates from a requirement, risk, business objective, or combination of these.

The starting point may be:

```text
Regulation
     ↓
Requirement
```

or:

```text
Business Objective
     ↓
Risk
```

or:

```text
Security Threat
     ↓
Vulnerability
     ↓
Risk
```

The organization then determines whether a control is required.

For example:

```text
Risk:
Unauthorized access to customer information

        ↓

Control Required
```

---

# 2. Define the Control Objective

The control objective describes **what the organization wants to achieve**.

For example:

```text
Risk:
Unauthorized access

        ↓

Control Objective:
Ensure access to sensitive systems is restricted
to authorized users.
```

The distinction is important:

```text
Control Objective
        ↓
WHAT must be achieved?

Control
        ↓
HOW will it be achieved?
```

For example:

```text
Control Objective
        ↓
Ensure privileged access is authorized.

Control
        ↓
All privileged access requires documented approval.
```

---

# 3. Design the Control

Control design determines how the control will operate.

The design should consider:

```text
Risk
 ↓
Control Objective
 ↓
Control Activity
 ↓
Owner
 ↓
Frequency
 ↓
Population
 ↓
Evidence
 ↓
Exception Handling
```

For example:

```text
Control:
Privileged access must be reviewed monthly.

Owner:
IT Security Manager

Frequency:
Monthly

Evidence:
Approved access review report

Exception:
Unauthorized account escalated to Security Operations
```

A well-designed control should clearly define **what, who, when, how, and what evidence**.

---

# Control Design Model

A useful control design model is:

```text
                CONTROL DESIGN
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
     WHAT            WHO            WHEN
       ↓              ↓              ↓
   Activity         Owner         Frequency
       └──────────────┼──────────────┘
                      ↓
                    HOW
                      ↓
                  Evidence
                      ↓
                 Exception
                  Handling
```

This helps prevent vague controls.

For example:

```text
Weak Control:

"Access is reviewed regularly."
```

This leaves several unanswered questions:

```text
Who?
When?
Which access?
How?
What evidence?
What happens if an exception is found?
```

A stronger control is:

```text
"System owners shall review privileged user access
monthly and document approval or removal of
inappropriate access."
```

The second version is much more testable.

---

# 4. Implement the Control

Once designed, the control must be implemented.

Implementation can be:

```text
Manual
Automated
Technical
Administrative
Hybrid
```

For example:

### Manual

```text
Manager
 ↓
Reviews Access List
 ↓
Approves / Rejects
 ↓
Records Evidence
```

### Automated

```text
IAM System
 ↓
Access Review Workflow
 ↓
Manager Approval
 ↓
Automatic Removal
```

### Hybrid

```text
IAM
 ↓
Generate Access Report
 ↓
Manager Review
 ↓
Manual Decision
 ↓
Automated Access Removal
```

The control design should match the organization's risk and operational environment.

---

# 5. Operate the Control

A control that exists on paper but is never performed is not an effective operating control.

The lifecycle therefore moves from:

```text
Control Design
      ↓
Implementation
      ↓
Actual Operation
```

For example:

```text
Policy:
Access must be reviewed monthly.
```

does not demonstrate that the control is operating.

Evidence is required:

```text
January Review
February Review
March Review
April Review
```

The organization must demonstrate that the control actually operates as intended.

---

# Control Operation Model

```text
CONTROL
   ↓
Frequency
   ↓
Execution
   ↓
Evidence
   ↓
Exception
   ↓
Action
```

For example:

```text
Monthly Access Review
        ↓
Review User Accounts
        ↓
Identify Excessive Access
        ↓
Remove / Approve
        ↓
Save Evidence
```

---

# 6. Test the Control

Control testing determines whether the control is operating as expected.

A simplified testing process is:

```text
Control
  ↓
Testing Objective
  ↓
Testing Procedure
  ↓
Evidence
  ↓
Test Result
  ↓
Conclusion
```

For example:

```text
Control:
Privileged access reviewed monthly.

Test:
Select sample of monthly access reviews.

Check:
Was the review completed?
Was approval documented?
Were exceptions resolved?
```

The test should be based on defined criteria.

---

# Control Testing Model

```text
              CONTROL TESTING
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
      Design     Operation     Evidence
        ↓           ↓           ↓
        └───────────┼───────────┘
                    ↓
               Test Result
                    ↓
             Effective / Gap
```

This distinction is important because a control can have a good design but poor operation.

---

# 7. Evaluate Control Effectiveness

After testing, the organization evaluates the control.

A simplified model is:

```text
Control Design
      +
Control Operation
      +
Evidence
      ↓
Control Effectiveness
```

Possible outcomes may include:

```text
Effective
Partially Effective
Ineffective
Not Tested
Not Applicable
```

The exact classification should be defined by the organization's methodology.

---

# Design Effectiveness vs Operating Effectiveness

These are different concepts.

### Design Effectiveness

The question is:

> **If the control operates as designed, is it capable of addressing the risk?**

```text
Risk
 ↓
Control Design
 ↓
Can it address the risk?
```

### Operating Effectiveness

The question is:

> **Does the control actually operate consistently and effectively?**

```text
Control
 ↓
Actual Operation
 ↓
Evidence
 ↓
Does it work?
```

The distinction can be represented as:

```text
                 CONTROL
                    ↓
          ┌─────────┴─────────┐
          ↓                   ↓
      DESIGN               OPERATION
          ↓                   ↓
   Does it address       Does it operate
      the risk?             properly?
```

A control can therefore be:

```text
Well Designed
     +
Poorly Operated
```

or:

```text
Poorly Designed
     +
Consistently Operated
```

Neither situation necessarily provides adequate risk reduction.

---

# 8. Identify Deficiencies

Testing may identify a control deficiency.

For example:

```text
Control
  ↓
Testing
  ↓
Evidence Missing
  ↓
Control Deficiency
```

Deficiencies may involve:

```text
Design
Operation
Evidence
Frequency
Ownership
Scope
Execution
Technology
```

For example:

```text
Required:
Monthly Access Review

Actual:
Review performed every three months
```

This may represent an operating deficiency.

---

# 9. Remediation

When a control deficiency is identified, remediation should follow.

```text
Deficiency
    ↓
Root Cause
    ↓
Corrective Action
    ↓
Owner
    ↓
Due Date
    ↓
Implementation
    ↓
Validation
```

For example:

```text
Finding:
Access reviews are not consistently completed.

        ↓

Root Cause:
No automated notification mechanism.

        ↓

Remediation:
Implement automated review workflow.

        ↓

Validation:
Test monthly review process.

        ↓

Closure
```

---

# Control Retesting

A remediated control should normally be validated.

```text
Finding
   ↓
Remediation
   ↓
Control Updated
   ↓
Retesting
   ↓
Effective?
 ↙       ↘
Yes       No
 ↓         ↓
Close     Reopen
Finding   Finding
```

This prevents organizations from closing findings merely because an action was marked "completed."

---

# Continuous Control Improvement

Controls should evolve as risks and business environments change.

```text
Risk Environment
      ↓
Control Performance
      ↓
Testing Results
      ↓
Lessons Learned
      ↓
Control Improvement
      ↓
Updated Control
      ↺
```

Triggers for control improvement may include:

```text
New Regulation
New Technology
New Threat
Security Incident
Audit Finding
Control Failure
Business Change
Organizational Change
New Vendor
Cloud Migration
Process Change
```

---

# Control Lifecycle and Risk Lifecycle

The control lifecycle is closely connected to the risk lifecycle.

```text
Risk Identification
        ↓
Risk Assessment
        ↓
Control Selection
        ↓
Control Design
        ↓
Control Implementation
        ↓
Control Operation
        ↓
Control Testing
        ↓
Residual Risk
        ↓
Risk Monitoring
        ↓
Control Improvement
        ↺
```

This demonstrates that controls are not independent from risk management.

They are part of the organization's overall risk response.

---

# Control Lifecycle and Compliance

Controls also provide the mechanism for meeting compliance obligations.

```text
Regulation
    ↓
Requirement
    ↓
Control Objective
    ↓
Control
    ↓
Evidence
    ↓
Assessment
    ↓
Compliance Status
```

For example:

```text
Regulatory Requirement
        ↓
Access must be appropriately controlled
        ↓
Access Control
        ↓
MFA
        ↓
Access Logs
        ↓
Control Testing
        ↓
Compliance Evidence
```

This creates regulatory traceability.

---

# Control Lifecycle and Audit

Auditors often examine the lifecycle from multiple perspectives.

```text
Requirement
    ↓
Risk
    ↓
Control
    ↓
Operation
    ↓
Evidence
    ↓
Testing
    ↓
Finding
    ↓
Remediation
```

An auditor may ask:

```text
Why does this control exist?
Who owns it?
How frequently does it operate?
What evidence exists?
How is it tested?
What happens when it fails?
How are deficiencies remediated?
```

A mature organization should be able to answer each question.

---

# Control Ownership

Every important control should have an accountable owner.

```text
Control
   ↓
Control Owner
   ↓
Execution
   ↓
Evidence
   ↓
Testing
   ↓
Remediation
```

The control owner is generally responsible for ensuring the control is appropriately implemented and operating.

However:

```text
Control Owner
      ≠
Control Tester
```

Where appropriate, separation of responsibilities should be maintained.

---

# Control Lifecycle Governance

The complete governance structure can be represented as:

```text
                    GOVERNANCE
                         ↓
                   Control Policy
                         ↓
                  Control Framework
                         ↓
                  Control Objective
                         ↓
                       Control
                         ↓
              ┌──────────┴──────────┐
              ↓                     ↓
           Owner                 Evidence
              ↓                     ↓
           Operation              Testing
              └──────────┬──────────┘
                         ↓
                    Effectiveness
                         ↓
                    Deficiency?
                    ↙        ↘
                  No          Yes
                  ↓             ↓
              Continue      Remediation
                  ↓             ↓
                  └──────┬──────┘
                         ↓
                   Improvement
                         ↺
```

---

# Practical Example – Access Control

Consider an organization managing privileged access.

```text
Risk
 ↓
Unauthorized Privileged Access
 ↓
Control Objective
 ↓
Ensure privileged access is authorized and reviewed
 ↓
Control
 ↓
Monthly privileged-access review
 ↓
Owner
 ↓
System Owner
 ↓
Evidence
 ↓
Approved access review records
 ↓
Testing
 ↓
Sample monthly reviews
 ↓
Result
 ↓
Effective
 ↓
Continuous Monitoring
```

If testing identifies an issue:

```text
Testing
   ↓
Unauthorized Account Found
   ↓
Finding
   ↓
Remediation
   ↓
Access Removed
   ↓
Retest
   ↓
Effective
   ↓
Close
```

---

# Practical Example – Automated Security Control

Consider endpoint security.

```text
Risk
 ↓
Malware Infection
 ↓
Control Objective
 ↓
Detect and prevent malicious activity
 ↓
Control
 ↓
Endpoint Detection and Response
 ↓
Automated Monitoring
 ↓
Security Alert
 ↓
Investigation
 ↓
Evidence
 ↓
Control Testing
 ↓
Effectiveness Assessment
```

This demonstrates that technical controls can also participate in the GRC lifecycle.

---

# Control Lifecycle Summary

The complete lifecycle can be summarized as:

```text
              REQUIREMENT / RISK
                      ↓
                CONTROL OBJECTIVE
                      ↓
                 CONTROL DESIGN
                      ↓
               IMPLEMENTATION
                      ↓
                   OPERATION
                      ↓
                    TESTING
                      ↓
                EFFECTIVENESS
                      ↓
              ┌───────┴───────┐
              ↓               ↓
           Effective       Deficient
              ↓               ↓
          Monitor         Remediate
              ↓               ↓
              └───────┬───────┘
                      ↓
                   RETEST
                      ↓
              CONTINUOUS IMPROVEMENT
                      ↺
```

The fundamental principle is:

> **A control is not simply something that exists. A mature control is one that is appropriately designed, implemented, operating, evidenced, tested, evaluated, remediated when necessary, and continuously improved.**

This control lifecycle becomes the foundation for the next parts of **18.5 – Control Framework Diagrams**, including the **Control Objective-to-Evidence Model**, **Preventive, Detective, and Corrective Controls**, and the **Control Effectiveness Model**.

# 18.5 Control Framework Diagrams

### Part 2 – Control Objective-to-Evidence Model

A control framework becomes meaningful when an organization can demonstrate a clear relationship between **what it is required to achieve and the evidence demonstrating that it has achieved it**.

A useful GRC traceability model is:

```text
Requirement
     ↓
Control Objective
     ↓
Control
     ↓
Control Activity
     ↓
Evidence
     ↓
Testing
     ↓
Control Result
```

This relationship allows an organization to answer a fundamental assurance question:

> **How can we demonstrate that the control is actually addressing the intended requirement or risk?**

---

## Requirement-to-Evidence Relationship

A control should not exist in isolation.

It should be connected to the requirement or objective that created the need for the control.

```text
Regulation
    ↓
Requirement
    ↓
Risk
    ↓
Control Objective
    ↓
Control
    ↓
Evidence
```

For example:

```text
Requirement:
Protect sensitive information

        ↓

Risk:
Unauthorized access

        ↓

Control Objective:
Ensure only authorized users can access sensitive information

        ↓

Control:
Access authorization and periodic access review

        ↓

Evidence:
Approved access requests
+
Access review records
+
IAM logs
```

This creates traceability between the **reason for the control** and the **evidence supporting its operation**.

---

# The Control Objective

A control objective describes the intended outcome of a control.

It should generally answer:

> **What should the organization achieve or ensure?**

Examples include:

```text
Ensure access is appropriately authorized.

Ensure security vulnerabilities are identified and remediated.

Ensure sensitive data is protected.

Ensure changes are authorized and documented.

Ensure backup processes support recovery requirements.

Ensure third parties are appropriately assessed.
```

A control objective is different from the control itself.

```text
CONTROL OBJECTIVE
        ↓
What should be achieved?

CONTROL
        ↓
What activity or mechanism achieves it?
```

For example:

```text
Control Objective:
Ensure privileged access is authorized.

        ↓

Control:
Privileged access requires documented approval
before access is granted.
```

---

# Control Objective-to-Control Relationship

The relationship can be represented as:

```text
              CONTROL OBJECTIVE
                      ↓
          ┌───────────┴───────────┐
          ↓                       ↓
      Expected Outcome       Risk Addressed
          ↓                       ↓
          └───────────┬───────────┘
                      ↓
                   CONTROL
                      ↓
               Control Activity
```

The control should be capable of achieving the control objective.

If it cannot, the control may have a **design deficiency**.

---

# Control Objective-to-Evidence Chain

The complete chain is:

```text
Requirement
     ↓
Control Objective
     ↓
Control
     ↓
Control Activity
     ↓
Evidence
```

Each layer answers a different question:

```text
Requirement
    ↓
What must be achieved?

Control Objective
    ↓
What outcome should the control produce?

Control
    ↓
What mechanism addresses the objective?

Control Activity
    ↓
What is actually performed?

Evidence
    ↓
How do we prove it?
```

This structure is particularly useful for audits and compliance assessments.

---

# Evidence Is Not the Control

One of the most important concepts in GRC is that **evidence and controls are not the same thing**.

For example:

```text
Control:
Managers review privileged access monthly.
```

Evidence may be:

```text
January Access Review
February Access Review
March Access Review
Approved Review Records
Access Review Logs
```

The relationship is:

```text
CONTROL
   ↓
Activity Performed
   ↓
Evidence Generated
```

Evidence demonstrates that an activity occurred.

It does not replace the control itself.

---

# Evidence-to-Control Relationship

A useful model is:

```text
                 CONTROL
                    ↓
             Control Activity
                    ↓
                 Execution
                    ↓
                Evidence
                    ↓
              Control Testing
                    ↓
              Effectiveness
```

For example:

```text
Control:
Backup restoration must be tested periodically.

        ↓

Activity:
Perform restoration test.

        ↓

Evidence:
Restoration test report.

        ↓

Testing:
Review restoration test results.

        ↓

Conclusion:
Control operating effectively.
```

---

# Types of Control Evidence

Evidence can take many forms.

### Documentary Evidence

```text
Policies
Procedures
Approved Documents
Meeting Minutes
Risk Assessments
Audit Reports
```

### System Evidence

```text
System Logs
Configuration Records
Access Logs
Security Alerts
System Reports
```

### Transactional Evidence

```text
Approval Records
Change Tickets
Access Requests
Purchase Approvals
Exception Records
```

### Monitoring Evidence

```text
Monitoring Reports
Dashboards
Alerts
Security Events
Compliance Monitoring Results
```

### Testing Evidence

```text
Test Results
Sampling Records
Screenshots
Audit Workpapers
Control Test Documentation
```

The type of evidence should be appropriate for the control being assessed.

---

# Evidence Quality

Not all evidence provides the same level of assurance.

A mature GRC program should consider evidence quality.

A useful model is:

```text
Evidence Quality
      ↓
Authenticity
      +
Completeness
      +
Accuracy
      +
Timeliness
      +
Relevance
      +
Traceability
```

For example, evidence should ideally be:

**Authentic**

```text
Can we establish where it came from?
```

**Complete**

```text
Does it cover the required population or period?
```

**Accurate**

```text
Does it correctly represent what occurred?
```

**Timely**

```text
Was it generated during the relevant period?
```

**Relevant**

```text
Does it actually support the control being tested?
```

**Traceable**

```text
Can it be connected to the control and activity?
```

---

# Evidence Traceability

Evidence should be traceable back to the control.

```text
Evidence
   ↓
Control Activity
   ↓
Control
   ↓
Control Objective
   ↓
Requirement
```

For example:

```text
Access Review Report
        ↓
Monthly Access Review
        ↓
Access Governance Control
        ↓
Ensure Access Is Authorized
        ↓
Security Requirement
```

This creates a defensible audit trail.

---

# One Control Can Generate Multiple Evidence Items

A single control may generate multiple pieces of evidence.

```text
                   CONTROL
                      ↓
              Monthly Access Review
                      ↓
        ┌─────────────┼─────────────┐
        ↓             ↓             ↓
   Access Report   Approvals     Exceptions
        ↓             ↓             ↓
        └─────────────┼─────────────┘
                      ↓
                  Evidence Set
```

The evidence set collectively demonstrates control operation.

---

# Multiple Controls Can Support One Objective

The relationship can also work in the opposite direction.

```text
              CONTROL OBJECTIVE
                      ↑
          ┌───────────┼───────────┐
          ↑           ↑           ↑
      Control A   Control B   Control C
```

For example:

```text
Objective:
Protect sensitive information

       ↑
       │
 ┌─────┼───────────────┐
 ↑     ↑               ↑
DLP   Encryption    Access Control
```

Multiple controls may therefore contribute to a single security or compliance objective.

---

# One Control Can Address Multiple Risks

A well-designed control can sometimes address multiple risks.

```text
                 CONTROL
                    ↓
             Multi-Factor
             Authentication
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
 Credential     Account      Unauthorized
 Compromise     Takeover       Access
```

This is one reason control frameworks should consider **control rationalization and mapping**.

---

# Control-to-Evidence Mapping

A GRC platform may maintain a mapping such as:

```text
Control ID
    ↓
Control Objective
    ↓
Control Owner
    ↓
Control Activity
    ↓
Evidence Requirement
    ↓
Evidence Source
    ↓
Testing Method
    ↓
Test Result
```

For example:

```text
CTRL-AC-001

Objective:
Protect privileged access

Activity:
Monthly privileged-access review

Owner:
IAM Manager

Evidence:
Monthly access review report

Source:
IAM Platform

Testing:
Sample-based review

Result:
Effective
```

This structure provides strong operational traceability.

---

# Requirement-to-Control-to-Evidence Model

A more complete model is:

```text
                    REQUIREMENT
                         ↓
                  CONTROL OBJECTIVE
                         ↓
                       RISK
                         ↓
                      CONTROL
                         ↓
                 CONTROL ACTIVITY
                         ↓
                      EVIDENCE
                         ↓
                       TEST
                         ↓
                     RESULT
                         ↓
                COMPLIANCE STATUS
```

This is one of the most important relationships in GRC.

It connects:

```text
Compliance
    ↕
Risk
    ↕
Controls
    ↕
Evidence
    ↕
Assurance
```

---

# Example – ISO 27001 Access Control

Consider an access control requirement.

```text
Security Requirement
        ↓
Access must be appropriately controlled
        ↓
Risk
        ↓
Unauthorized access
        ↓
Control Objective
        ↓
Ensure access is authorized and reviewed
        ↓
Control
        ↓
Periodic access review
        ↓
Evidence
        ↓
Access review records
        ↓
Testing
        ↓
Review sample
        ↓
Result
        ↓
Effective / Deficient
```

This model demonstrates how an abstract requirement becomes a measurable control.

---

# Example – Vulnerability Management

The same model can be applied to vulnerability management.

```text
Requirement
      ↓
Systems should be protected from known vulnerabilities
      ↓
Risk
      ↓
Exploitation of vulnerable systems
      ↓
Control Objective
      ↓
Identify and remediate vulnerabilities
      ↓
Control
      ↓
Periodic vulnerability scanning
      ↓
Evidence
      ↓
Vulnerability scan reports
      ↓
Testing
      ↓
Review scan coverage and remediation
      ↓
Result
```

The evidence demonstrates whether the control activity occurred.

---

# Example – Backup Control

```text
Requirement
      ↓
Critical information must be recoverable
      ↓
Risk
      ↓
Data loss
      ↓
Control Objective
      ↓
Ensure backups are performed and recoverable
      ↓
Control
      ↓
Scheduled backup and restoration testing
      ↓
Evidence
      ↓
Backup logs
+
Restoration test reports
      ↓
Testing
      ↓
Review backup and recovery evidence
      ↓
Result
```

This shows why evidence should cover both **execution** and, where appropriate, **effectiveness**.

---

# Evidence Collection Model

Evidence can be collected manually or automatically.

### Manual Evidence Collection

```text
Control Owner
      ↓
Perform Control
      ↓
Collect Evidence
      ↓
Upload to GRC
      ↓
Reviewer
      ↓
Assessment
```

### Automated Evidence Collection

```text
System
   ↓
Automated Data Collection
   ↓
GRC Platform
   ↓
Control Evidence
   ↓
Automated / Assisted Assessment
```

### Hybrid Evidence Collection

```text
System
   ↓
Automated Evidence
   ↓
GRC Platform
   ↓
Human Review
   ↓
Assessment
```

The appropriate approach depends on the control and the organization's technology environment.

---

# Evidence Frequency

Evidence should generally correspond to the frequency of the control.

For example:

```text
Control Frequency       Evidence
---------------------------------------
Daily                   Daily logs
Weekly                  Weekly reports
Monthly                 Monthly review
Quarterly               Quarterly assessment
Annually                Annual certification
Event-Based             Transaction/event record
```

For a monthly control:

```text
January
   ↓
Evidence

February
   ↓
Evidence

March
   ↓
Evidence
```

A single document created at the end of the year may not adequately demonstrate that a monthly control operated throughout the year.

---

# Evidence Retention

Evidence should be retained according to applicable requirements and organizational policy.

A simplified lifecycle is:

```text
Evidence Generated
       ↓
Evidence Validated
       ↓
Evidence Stored
       ↓
Evidence Protected
       ↓
Evidence Retained
       ↓
Retention Period
       ↓
Secure Disposal
```

Evidence itself may contain sensitive information and therefore may require appropriate protection.

---

# Evidence Integrity

Evidence should also be protected from unauthorized modification.

```text
Evidence
   ↓
Integrity Protection
   ↓
Access Control
   ↓
Audit Trail
   ↓
Retention
```

For highly sensitive evidence, organizations may need stronger mechanisms such as:

```text
Immutable Storage
Digital Signatures
Access Logging
Version Control
Hashing
```

The exact mechanism depends on the evidence type and risk.

---

# Control Evidence and Audit Trail

The evidence chain should allow an auditor or reviewer to reconstruct what happened.

```text
Who?
 ↓
Performed the activity

What?
 ↓
Control activity performed

When?
 ↓
Date / time

How?
 ↓
Process or system used

Result?
 ↓
Outcome

Evidence?
 ↓
Supporting record
```

For example:

```text
Who:
System Owner

What:
Access review

When:
30 June

How:
IAM access review workflow

Result:
3 inappropriate accounts identified

Action:
Accounts removed

Evidence:
Approved review record + IAM logs
```

This is much stronger than simply stating:

```text
"Access review completed."
```

---

# Evidence and the Audit Trail

A mature GRC environment should establish:

```text
Requirement
    ↓
Control
    ↓
Activity
    ↓
Evidence
    ↓
Review
    ↓
Decision
    ↓
Action
```

This creates an auditable chain of accountability.

---

# Common Control-to-Evidence Weaknesses

Organizations frequently encounter problems such as:

```text
Control exists
      ↓
No evidence

Control exists
      ↓
Evidence incomplete

Control exists
      ↓
Evidence outdated

Control exists
      ↓
Evidence does not prove operation

Control exists
      ↓
Evidence cannot be traced to the control
```

These situations can create audit and compliance challenges.

---

# The Evidence Gap

An important GRC concept is the **evidence gap**.

```text
Required Control Activity
          ↓
      Evidence?
       ↙      ↘
     Yes       No
      ↓         ↓
   Support    Evidence
   Available    Gap
```

For example:

```text
Control:
Quarterly access review

Required:
4 reviews per year

Available:
2 reviews

        ↓

Evidence Gap
```

The control may exist, but the available evidence does not fully demonstrate its operation.

---

# Control Objective-to-Evidence Traceability Matrix

A practical matrix may look like:

| Requirement               | Control Objective                      | Control                          | Evidence                   | Test Result         |
| ------------------------- | -------------------------------------- | -------------------------------- | -------------------------- | ------------------- |
| Protect privileged access | Ensure privileged access is authorized | Monthly privileged-access review | Access review reports      | Effective           |
| Protect systems           | Identify vulnerabilities               | Vulnerability scanning           | Scan reports               | Effective           |
| Protect data              | Prevent unauthorized disclosure        | DLP monitoring                   | DLP reports                | Partially Effective |
| Ensure recoverability     | Maintain recoverable backups           | Backup and restoration testing   | Backup logs / test reports | Effective           |

This type of matrix converts the visual relationship into an operational GRC record.

---

# Bidirectional Traceability

A mature GRC environment should ideally support both directions.

### Requirement → Evidence

```text
Requirement
    ↓
Control
    ↓
Evidence
```

This answers:

> **How are we demonstrating compliance with this requirement?**

### Evidence → Requirement

```text
Evidence
    ↓
Control
    ↓
Requirement
```

This answers:

> **What requirement or risk does this evidence support?**

Bidirectional traceability strengthens audit readiness.

---

# The Complete Control Objective-to-Evidence Model

The complete model can be represented as:

```text
                         REQUIREMENT
                              ↓
                           RISK
                              ↓
                     CONTROL OBJECTIVE
                              ↓
                           CONTROL
                              ↓
                      CONTROL ACTIVITY
                              ↓
                           OWNER
                              ↓
                         EXECUTION
                              ↓
                          EVIDENCE
                              ↓
                           REVIEW
                              ↓
                           TESTING
                              ↓
                     EFFECTIVENESS RESULT
                              ↓
                    COMPLIANCE / RISK STATUS
                              ↓
                     MANAGEMENT DECISION
```

This model connects the **strategic reason for a control** with the **operational evidence proving its execution**.

The fundamental principle is:

> **A strong GRC environment should be able to explain why a control exists, what objective it supports, how it operates, who owns it, what evidence it produces, and how its effectiveness is demonstrated.**


