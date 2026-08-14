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

## 18.5 Control Framework Diagrams

### Part 3 – Preventive, Detective, and Corrective Controls

Controls can be classified according to **when and how they respond to risk**.

One of the most fundamental control classifications in GRC and cybersecurity is:

```text
Preventive Controls
        ↓
Detective Controls
        ↓
Corrective Controls
```

These three categories represent different points in the risk event lifecycle.

A simplified model is:

```text
              RISK EVENT
                  ↓
        ┌─────────┼─────────┐
        ↓         ↓         ↓
    PREVENT     DETECT    CORRECT
        ↓         ↓         ↓
    Stop the   Identify   Restore /
     event      event     remediate
```

A mature control environment generally uses a **combination** of all three.

---

# 1. Preventive Controls

Preventive controls are designed to **prevent an undesirable event from occurring** or reduce the likelihood of occurrence.

The basic model is:

```text
Threat / Risk
     ↓
Preventive Control
     ↓
Event Prevented
```

Examples include:

```text
Access restrictions
Multi-factor authentication
Network segmentation
Security policies
Segregation of duties
Change approvals
Encryption
Secure configuration
Input validation
Firewalls
```

For example:

```text
Unauthorized Access Attempt
          ↓
        MFA
          ↓
   Authentication Failed
          ↓
    Access Prevented
```

The control operates **before or at the point of the risk event**.

---

# Preventive Control Model

```text
              THREAT
                ↓
          Potential Event
                ↓
        ┌───────────────┐
        │   PREVENTIVE  │
        │    CONTROL    │
        └───────────────┘
                ↓
          Event Blocked
```

The objective is to reduce the probability that the undesirable event will occur.

---

# Example – Access Management

Consider unauthorized access to a critical application.

```text
User
 ↓
Login Attempt
 ↓
Authentication
 ↓
MFA
 ↓
Authorization
 ↓
Access Granted / Denied
```

MFA and authorization mechanisms are preventive controls because they attempt to stop unauthorized access before it occurs.

---

# Example – Change Management

A change to a production system may introduce operational or security risk.

A preventive control could require approval before implementation.

```text
Change Request
      ↓
Risk Assessment
      ↓
Approval Required
      ↓
Approved?
   ↙       ↘
 No         Yes
 ↓           ↓
Reject     Implement
```

The approval process prevents unauthorized or insufficiently assessed changes from being implemented.

---

# Example – Segregation of Duties

Segregation of duties prevents one individual from having excessive control over a sensitive process.

```text
Request
   ↓
Employee A
   ↓
Approval
   ↓
Employee B
   ↓
Execution
```

The separation reduces the opportunity for unauthorized activity.

---

# Preventive Controls in Cybersecurity

Common preventive cybersecurity controls include:

```text
Firewall
        ↓
Blocks unauthorized network traffic

MFA
        ↓
Prevents unauthorized authentication

Encryption
        ↓
Protects information if accessed

Network Segmentation
        ↓
Limits unauthorized movement

Least Privilege
        ↓
Limits unnecessary access

Secure Configuration
        ↓
Reduces exploitable weaknesses
```

Preventive controls are therefore an important component of defense-in-depth.

---

# 2. Detective Controls

Detective controls are designed to **identify an event, violation, failure, or deviation after or while it occurs**.

The basic model is:

```text
Risk Event
    ↓
Detective Control
    ↓
Detection
    ↓
Investigation / Response
```

Examples include:

```text
Security monitoring
SIEM alerts
Audit logs
Access reviews
Vulnerability scans
Fraud monitoring
Reconciliation
Intrusion detection
Compliance monitoring
Security assessments
```

---

# Detective Control Model

```text
              RISK EVENT
                  ↓
              Occurrence
                  ↓
        ┌─────────────────┐
        │    DETECTIVE    │
        │     CONTROL     │
        └─────────────────┘
                  ↓
              Detection
                  ↓
             Investigation
```

Unlike preventive controls, detective controls generally do not stop the original event.

Their purpose is to **discover that something happened or that something is wrong**.

---

# Example – SIEM Monitoring

Consider a compromised user account.

```text
Compromised Account
       ↓
Suspicious Login
       ↓
SIEM
       ↓
Alert
       ↓
SOC Investigation
```

The SIEM may not prevent the initial compromise.

Instead, it detects suspicious activity so that the organization can respond.

---

# Example – Access Review

Periodic access review is another detective control.

```text
Existing User Access
        ↓
Periodic Review
        ↓
Excessive Access Identified
        ↓
Investigation
        ↓
Access Removed
```

The review detects inappropriate access that may already exist.

---

# Example – Vulnerability Scanning

```text
System
  ↓
Vulnerability Scan
  ↓
Vulnerability Detected
  ↓
Risk Assessment
  ↓
Remediation
```

The scanning process detects weaknesses.

The actual remediation may be performed through another control.

---

# Example – Financial Reconciliation

Detective controls are not limited to cybersecurity.

For example:

```text
Transaction Records
       ↓
Bank Records
       ↓
Reconciliation
       ↓
Difference Identified
       ↓
Investigation
```

The reconciliation detects discrepancies that may indicate error or fraud.

---

# 3. Corrective Controls

Corrective controls are designed to **correct an identified problem, reduce its impact, restore normal operations, or prevent recurrence**.

The basic model is:

```text
Incident / Failure
       ↓
Corrective Control
       ↓
Remediation
       ↓
Recovery
       ↓
Normal Operation
```

Examples include:

```text
Incident response
System restoration
Backup recovery
Patch deployment
Account removal
Configuration correction
Malware removal
Disaster recovery
Corrective action plans
```

---

# Corrective Control Model

```text
              INCIDENT
                 ↓
              Detection
                 ↓
        ┌─────────────────┐
        │   CORRECTIVE    │
        │     CONTROL     │
        └─────────────────┘
                 ↓
             Remediation
                 ↓
              Recovery
                 ↓
          Normal Operation
```

Corrective controls therefore operate **after a problem has been identified**.

---

# Example – Malware Infection

Consider a malware infection.

```text
Malware
   ↓
Endpoint Detection
   ↓
Alert
   ↓
Investigation
   ↓
Malware Confirmed
   ↓
Isolation
   ↓
Malware Removal
   ↓
System Restoration
```

In this example:

```text
EDR Detection
     ↓
Detective Control

Endpoint Isolation
     ↓
Containment / Corrective Response

Malware Removal
     ↓
Corrective Control

System Restoration
     ↓
Recovery Control
```

A single incident may therefore involve multiple control types.

---

# Preventive + Detective + Corrective Model

The three control types work together.

```text
                 THREAT
                   ↓
          ┌─────────────────┐
          │    PREVENTIVE   │
          │     CONTROL     │
          └─────────────────┘
                   ↓
             Event Occurs?
                ↙     ↘
              No       Yes
              ↓         ↓
           Prevented  DETECTIVE
                       CONTROL
                          ↓
                       Alert
                          ↓
                    CORRECTIVE
                      CONTROL
                          ↓
                      Recovery
                          ↓
                    Improvement
```

This demonstrates why relying on a single type of control can create weaknesses.

---

# Defense-in-Depth Perspective

A mature cybersecurity environment often layers controls.

```text
Threat
  ↓
Preventive Control
  ↓
Preventive Control
  ↓
Event
  ↓
Detective Control
  ↓
Alert
  ↓
Corrective Control
  ↓
Recovery
```

For example:

```text
                CYBER ATTACK
                     ↓
          Firewall / MFA / IAM
             PREVENTIVE
                     ↓
                If Bypassed
                     ↓
             SIEM / EDR / IDS
               DETECTIVE
                     ↓
                  Alert
                     ↓
          Incident Response
               CORRECTIVE
                     ↓
               Recovery
```

The objective is to ensure that if one control fails, another layer provides protection or detection.

---

# Control Classification by Timing

Another way to visualize the three categories is according to **when the control acts**.

```text
BEFORE EVENT
     ↓
PREVENTIVE
     ↓
────────────────────────
     ↓
DURING / AFTER EVENT
     ↓
DETECTIVE
     ↓
────────────────────────
     ↓
AFTER DETECTION
     ↓
CORRECTIVE
```

A simplified timeline is:

```text
        BEFORE              DURING              AFTER
          │                   │                   │
          ↓                   ↓                   ↓
     PREVENTIVE           DETECTIVE           CORRECTIVE
          │                   │                   │
          ↓                   ↓                   ↓
      Block Risk          Identify Event      Fix Problem
```

The exact timing can vary depending on the control.

Some controls can have characteristics of more than one category.

---

# Preventive vs Detective vs Corrective

| Control Type | Primary Purpose      | Typical Timing     | Example            |
| ------------ | -------------------- | ------------------ | ------------------ |
| Preventive   | Prevent an event     | Before event       | MFA                |
| Detective    | Identify an event    | During/after event | SIEM monitoring    |
| Corrective   | Remediate or recover | After detection    | System restoration |

The categories should not be treated as mutually exclusive in every situation.

A control can sometimes provide multiple functions.

---

# Example – Firewall

A firewall is primarily preventive:

```text
Malicious Traffic
       ↓
Firewall
       ↓
Blocked
```

However, firewall logs can also provide detective information:

```text
Malicious Traffic
       ↓
Firewall
       ↓
Blocked
       ↓
Log Generated
       ↓
SIEM
       ↓
Alert
```

Therefore:

```text
Firewall Blocking
       ↓
Preventive Function

Firewall Logging
       ↓
Detective Capability
```

This demonstrates why classification should consider the **specific control activity and objective**, rather than simply the technology name.

---

# Example – Antivirus / EDR

Endpoint security technology may perform multiple functions.

```text
Malware
  ↓
Detection
  ↓
Alert
  ↓
Automatic Isolation
  ↓
Removal
```

The components may include:

```text
Detection
    ↓
Detective

Automatic Blocking
    ↓
Preventive

Isolation / Removal
    ↓
Corrective
```

Therefore, one technology can support multiple control objectives.

---

# Example – Backup

Backup controls are often associated with recovery.

```text
Data Loss
    ↓
Backup
    ↓
Restore
    ↓
Recovery
```

The backup itself does not necessarily prevent data loss.

Instead, it reduces the **impact** of data loss by allowing recovery.

It therefore supports a corrective/recovery function.

A stronger control environment may combine:

```text
Preventive
   ↓
Access Control

Detective
   ↓
Data Loss Monitoring

Corrective
   ↓
Backup and Recovery
```

---

# Control Categories and Risk Treatment

Preventive, detective, and corrective controls can also be connected to risk treatment.

```text
Risk
 ↓
Control Strategy
 ↓
┌──────────────┬──────────────┬──────────────┐
↓              ↓              ↓
Prevent       Detect         Correct
↓              ↓              ↓
Reduce        Identify       Reduce
Likelihood    Event          Impact
```

This demonstrates that controls can reduce risk in different ways.

---

# Control Categories and Risk

Consider the risk:

> Ransomware compromises a critical server.

A layered control environment could be:

```text
Risk
 ↓
Ransomware Attack
 ↓
──────────────────────────────
PREVENTIVE
 ↓
Endpoint Protection
Network Segmentation
MFA
Secure Configuration
──────────────────────────────
DETECTIVE
 ↓
EDR
SIEM
Threat Monitoring
──────────────────────────────
CORRECTIVE
 ↓
Isolation
Malware Removal
Backup Restoration
──────────────────────────────
Residual Risk
```

The organization is not relying on a single security mechanism.

---

# Control Failure Scenario

A mature control framework should consider what happens if a preventive control fails.

```text
Preventive Control
       ↓
      FAILS
       ↓
Risk Event
       ↓
Detective Control
       ↓
Detection
       ↓
Corrective Control
       ↓
Recovery
```

For example:

```text
MFA
 ↓
Compromised Account
 ↓
SIEM Detects Unusual Login
 ↓
SOC Alert
 ↓
Account Disabled
 ↓
Credentials Reset
 ↓
Investigation
```

This is a practical example of layered control design.

---

# Compensating Controls

Sometimes the preferred control cannot be implemented.

A **compensating control** may then be used to reduce the risk through another mechanism.

For example:

```text
Required Control
      ↓
Cannot Be Implemented
      ↓
Risk Assessment
      ↓
Compensating Control
      ↓
Residual Risk
      ↓
Management Approval
```

For example:

```text
Primary Control:
MFA

Constraint:
Legacy system does not support MFA

Compensating Controls:
Restricted network access
+
Privileged access monitoring
+
Additional authentication mechanism
+
Enhanced logging
```

The compensating control should provide an appropriate level of risk reduction.

---

# Control Redundancy

Multiple controls may address the same risk.

```text
                 RISK
                  ↓
       ┌──────────┼──────────┐
       ↓          ↓          ↓
      MFA       Firewall     SIEM
       ↓          ↓          ↓
       └──────────┼──────────┘
                  ↓
            Risk Reduction
```

This redundancy can increase resilience.

However, organizations should also avoid unnecessary duplication.

---

# Control Rationalization

A mature GRC program periodically reviews controls to determine whether they are:

```text
Necessary
Effective
Duplicated
Obsolete
Overlapping
Cost-Effective
Risk-Aligned
```

For example:

```text
Control A ─┐
Control B ─┼──→ Same Risk
Control C ─┘
```

The organization may discover that several controls perform substantially the same function.

Control rationalization can reduce:

* Administrative effort
* Testing effort
* Evidence collection
* Duplicate controls
* Unnecessary cost

while maintaining appropriate risk coverage.

---

# Mapping Control Types to Evidence

Each control type produces different evidence.

### Preventive Control Evidence

```text
MFA Configuration
Firewall Rules
Access Approvals
Security Configuration
Change Approval
Encryption Configuration
```

### Detective Control Evidence

```text
SIEM Alerts
Monitoring Reports
Access Review Reports
Vulnerability Scan Results
Security Logs
Fraud Detection Reports
```

### Corrective Control Evidence

```text
Incident Tickets
Remediation Records
Patch Records
Recovery Reports
System Restoration Tests
Corrective Action Plans
```

This relationship can be represented as:

```text
Control Type
     ↓
Control Activity
     ↓
Evidence
     ↓
Testing
```

---

# Control Testing by Control Type

Testing procedures should reflect the nature of the control.

### Preventive Control

Test whether the control prevents the intended activity.

```text
MFA Control
   ↓
Attempt Authentication
   ↓
MFA Required?
   ↓
Pass / Fail
```

### Detective Control

Test whether the control detects the intended event.

```text
Monitoring Control
   ↓
Generate / Identify Test Event
   ↓
Alert Generated?
   ↓
Pass / Fail
```

### Corrective Control

Test whether the control successfully remediates or recovers.

```text
Recovery Control
   ↓
Perform Recovery Test
   ↓
System Restored?
   ↓
Pass / Fail
```

This ensures testing is aligned with the control's purpose.

---

# Control Type and Business Resilience

The three categories can also support organizational resilience.

```text
PREVENT
   ↓
Reduce likelihood

DETECT
   ↓
Reduce detection time

CORRECT
   ↓
Reduce impact / recovery time
```

Together:

```text
         RESILIENCE
             ↑
   ┌─────────┼─────────┐
   ↑         ↑         ↑
Prevent    Detect    Correct
   ↑         ↑         ↑
Reduce     Reduce    Reduce
Likelihood  Delay    Impact
```

This is especially important for critical business services.

---

# Practical GRC Example

Consider a payment processing system.

### Preventive

```text
MFA
+
Segregation of Duties
+
Transaction Limits
+
Secure Coding
```

### Detective

```text
Transaction Monitoring
+
SIEM
+
Fraud Detection
+
Audit Logging
```

### Corrective

```text
Account Blocking
+
Transaction Reversal
+
Incident Response
+
System Recovery
```

The overall model becomes:

```text
                    PAYMENT SYSTEM
                          ↓
          ┌───────────────┼───────────────┐
          ↓               ↓               ↓
      PREVENTIVE       DETECTIVE       CORRECTIVE
          ↓               ↓               ↓
       Prevent          Detect          Remediate
          ↓               ↓               ↓
          └───────────────┼───────────────┘
                          ↓
                    Risk Reduction
                          ↓
                    Business Resilience
```

---

# Management Perspective

Executives should not only ask:

> "Do we have controls?"

They should ask:

```text
Do we have preventive controls?
        ↓
Can we detect when prevention fails?
        ↓
Can we respond and correct the problem?
        ↓
Can we recover?
        ↓
Can we learn and improve?
```

This creates a more mature view of control effectiveness.

---

# Integrated Control Model

A mature control environment can therefore be visualized as:

```text
                         RISK
                          ↓
              ┌───────────┴───────────┐
              ↓                       ↓
         PREVENTIVE                DETECTIVE
           CONTROLS                 CONTROLS
              ↓                       ↓
        Reduce Likelihood          Detect Event
              ↓                       ↓
              └───────────┬───────────┘
                          ↓
                     RISK EVENT
                          ↓
                    CORRECTIVE
                      CONTROLS
                          ↓
                     Remediation
                          ↓
                       Recovery
                          ↓
                    Lessons Learned
                          ↓
                  Control Improvement
                          ↺
```

The key principle is that **preventive, detective, and corrective controls should work as an integrated system rather than as isolated control categories**.

A strong GRC control framework seeks to prevent important events where possible, detect failures quickly when prevention is unsuccessful, and correct or recover from those failures while reducing the likelihood of recurrence.

# 18.5 Control Framework Diagrams

### Part 4 – Control Effectiveness Model

A control is not effective simply because it exists, has an assigned owner, or is documented in a policy.

Control effectiveness requires the organization to determine whether the control is **appropriately designed, properly implemented, operating as intended, and producing the expected risk-reduction outcome**.

A simplified control effectiveness model is:

```text
Risk / Requirement
        ↓
Control Objective
        ↓
Control Design
        ↓
Control Implementation
        ↓
Control Operation
        ↓
Evidence
        ↓
Control Testing
        ↓
Effectiveness Assessment
        ↓
Risk / Compliance Outcome
```

The fundamental question is:

> **Does the control actually achieve its intended purpose and reduce the risk to an acceptable level?**

---

## What Is Control Effectiveness?

Control effectiveness is the degree to which a control successfully performs its intended function.

For example:

```text
Risk:
Unauthorized privileged access

        ↓

Control:
Monthly privileged-access review

        ↓

Question:
Does the review consistently identify
and address inappropriate access?

        ↓

Effectiveness Assessment
```

A control may be documented and implemented but still fail to provide adequate protection.

---

# Control Effectiveness Dimensions

A practical model evaluates several dimensions:

```text
                 CONTROL EFFECTIVENESS
                         ↓
       ┌─────────────────┼─────────────────┐
       ↓                 ↓                 ↓
    Design           Operation          Outcome
 Effectiveness     Effectiveness     Effectiveness
       ↓                 ↓                 ↓
 Is the control      Does it operate   Does it reduce
 appropriately       as intended?       the intended
 designed?                              risk?
```

These dimensions provide a more complete assessment than simply asking whether a control exists.

---

# 1. Design Effectiveness

Design effectiveness asks:

> **Is the control appropriately designed to address the identified risk or requirement?**

The basic model is:

```text
Risk
 ↓
Control Objective
 ↓
Control Design
 ↓
Does the control address the risk?
```

For example:

```text
Risk:
Unauthorized access

Control:
Quarterly access review
```

The organization should determine whether a quarterly review is actually capable of identifying and addressing the relevant access risk.

If privileged access changes frequently, a quarterly review might not provide sufficient protection.

The control may therefore be **poorly designed**, even if every quarterly review is performed perfectly.

---

# 2. Operating Effectiveness

Operating effectiveness asks:

> **Does the control operate consistently and as designed?**

The model is:

```text
Control
   ↓
Execution
   ↓
Evidence
   ↓
Testing
   ↓
Operating Effectiveness
```

For example:

```text
Control:
Monthly access review

Required:
12 reviews per year

Actual:
8 reviews completed

        ↓

Operating Effectiveness Issue
```

The control may be well designed but not consistently operated.

---

# Design vs Operating Effectiveness

These two concepts should be clearly separated.

```text
                  CONTROL
                     ↓
          ┌──────────┴──────────┐
          ↓                     ↓
       DESIGN                OPERATION
          ↓                     ↓
 Is it capable of         Does it operate
 addressing the risk?       as intended?
```

A control can therefore have four possible combinations:

| Design      | Operation   | General Assessment   |
| ----------- | ----------- | -------------------- |
| Effective   | Effective   | Strong               |
| Effective   | Ineffective | Operational weakness |
| Ineffective | Effective   | Design weakness      |
| Ineffective | Ineffective | Significant weakness |

This is an important distinction in audit and GRC assessments.

---

# Control Effectiveness Testing

Testing provides the evidence needed to assess effectiveness.

A simplified process is:

```text
Control
   ↓
Testing Objective
   ↓
Testing Procedure
   ↓
Evidence Collection
   ↓
Sample / Population Review
   ↓
Exceptions Identified
   ↓
Test Conclusion
```

For example:

```text
Control:
Privileged access reviewed monthly

Testing:
Select six months

Check:
Was the review performed?
Was it approved?
Were exceptions identified?
Were exceptions resolved?
```

The tester then documents the result.

---

# Testing Population and Sampling

Controls may operate over a large population.

For example:

```text
10,000 User Accounts
       ↓
Monthly Access Review
       ↓
10,000 Records
       ↓
Testing Sample
       ↓
Selected Records
```

Testing may use sampling methodologies appropriate to the organization's assurance requirements.

The objective is to obtain sufficient evidence to support a reasonable conclusion about control performance.

---

# Evidence Evaluation

Testing should consider whether evidence is sufficient and appropriate.

```text
Evidence
   ↓
Authentic?
   ↓
Complete?
   ↓
Accurate?
   ↓
Relevant?
   ↓
Timely?
   ↓
Traceable?
   ↓
Sufficient for Conclusion?
```

Weak evidence can make it difficult to establish control effectiveness.

For example:

```text
Control:
Monthly access review

Evidence:
One screenshot from December
```

This may not demonstrate that the control operated throughout the year.

---

# Control Effectiveness Criteria

Organizations should establish defined criteria for determining effectiveness.

For example:

```text
Effective
    ↓
Control meets defined requirements

Partially Effective
    ↓
Control generally operates but has weaknesses

Ineffective
    ↓
Control does not adequately address the risk

Not Tested
    ↓
Insufficient testing performed
```

The exact terminology and thresholds should be defined by the organization's GRC methodology.

---

# Control Effectiveness Scoring

Organizations may also use numerical scoring.

For example:

```text
5 = Highly Effective
4 = Effective
3 = Partially Effective
2 = Weak
1 = Ineffective
```

A score might consider:

```text
Design
+
Implementation
+
Operating Performance
+
Evidence
+
Exceptions
+
Risk Coverage
```

For example:

```text
Control Score
      ↓
Design             5
Implementation     5
Operation          4
Evidence           4
Risk Coverage      5
      ↓
Overall Assessment
      ↓
Effective
```

The scoring methodology should be consistently applied.

---

# Control Exceptions

An exception occurs when the control does not operate according to its defined requirements.

For example:

```text
Required:
Monthly review

Actual:
Review completed late
```

Or:

```text
Required:
All privileged accounts reviewed

Actual:
95% reviewed
5% not reviewed
```

The exception should be evaluated based on:

```text
Frequency
Severity
Duration
Impact
Root Cause
Risk Exposure
```

Not every exception necessarily means that the entire control is ineffective.

---

# Control Failure vs Control Exception

These concepts should be distinguished.

### Control Exception

A specific deviation from the control requirement.

```text
Control
 ↓
Single Exception
 ↓
Investigate
 ↓
Determine Impact
```

### Control Failure

A broader or significant inability of the control to perform its intended function.

```text
Control
 ↓
Repeated / Significant Exceptions
 ↓
Control Failure
 ↓
Remediation
```

For example:

```text
One missed monthly review
        ↓
Exception
```

while:

```text
No access reviews performed for an entire year
        ↓
Potential Control Failure
```

The final classification depends on the organization's methodology and risk assessment.

---

# Root Cause Analysis

When a control is ineffective, the organization should understand **why**.

A simplified model is:

```text
Control Failure
      ↓
Root Cause Analysis
      ↓
Why did the control fail?
      ↓
Identify Root Cause
      ↓
Corrective Action
```

Potential causes include:

```text
Poor Control Design
Insufficient Resources
Lack of Training
Incorrect Configuration
Process Failure
Technology Failure
Unclear Ownership
Inadequate Monitoring
Poor Documentation
Organizational Change
```

Addressing only the immediate symptom may not resolve the underlying problem.

---

# Control Effectiveness and Risk

Control effectiveness should ultimately be connected to risk.

```text
Inherent Risk
      ↓
Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
```

For example:

```text
High Inherent Risk
       ↓
Strong Controls
       ↓
Effective Control Operation
       ↓
Lower Residual Risk
```

But:

```text
High Inherent Risk
       ↓
Weak Controls
       ↓
Control Deficiencies
       ↓
High Residual Risk
```

This connection makes control assessment more meaningful to management.

---

# Control Effectiveness and Residual Risk

A simplified relationship is:

```text
                INHERENT RISK
                      ↓
                Control Design
                      ↓
              Control Operation
                      ↓
             Control Effectiveness
                      ↓
                RESIDUAL RISK
```

Control effectiveness therefore contributes to the organization's understanding of how much risk remains after controls are applied.

---

# Effective Control Does Not Mean Zero Risk

An important GRC principle is:

> **An effective control does not necessarily eliminate risk.**

For example:

```text
Risk:
Phishing Attack

Control:
Email Security Gateway

        ↓

Many malicious emails blocked

        ↓

Some sophisticated attacks may remain

        ↓

Residual Risk
```

The objective of controls is generally to reduce risk to an acceptable level, not necessarily to eliminate every possible threat.

---

# Control Effectiveness and Risk Appetite

Management should consider whether the remaining risk is acceptable.

```text
Control
   ↓
Risk Reduction
   ↓
Residual Risk
   ↓
Compare with Risk Appetite
      ↙          ↘
 Acceptable    Unacceptable
     ↓              ↓
 Monitor        Remediate /
                Additional Controls
```

This connects control effectiveness with executive risk decisions.

---

# Layered Control Effectiveness

Organizations should evaluate controls as part of the broader control environment.

```text
                    RISK
                     ↓
          ┌──────────┴──────────┐
          ↓                     ↓
      Preventive             Detective
        Controls               Controls
          ↓                     ↓
          └──────────┬──────────┘
                     ↓
                  Event
                     ↓
               Corrective
                 Controls
                     ↓
                  Recovery
```

A weakness in one control may sometimes be compensated for by another control.

However, organizations should not assume that multiple controls automatically provide adequate protection. Their combined effectiveness should be assessed.

---

# Compensating Control Effectiveness

When a primary control cannot operate, a compensating control may reduce the associated risk.

```text
Primary Control
      ↓
     Fails
      ↓
Risk Exposure
      ↓
Compensating Control
      ↓
Risk Reduction
      ↓
Residual Risk
```

The organization should evaluate whether the compensating control provides sufficient protection.

---

# Control Effectiveness and Automation

Automation can improve control consistency, but automation alone does not guarantee effectiveness.

For example:

```text
Automated Control
      ↓
Configuration
      ↓
Execution
      ↓
Monitoring
      ↓
Testing
```

An incorrectly configured automated control can consistently perform the wrong action.

For example:

```text
Automated Firewall Rule
        ↓
Incorrect Configuration
        ↓
Repeated Incorrect Enforcement
```

Therefore, automated controls still require appropriate governance and testing.

---

# Continuous Control Monitoring

Modern GRC programs increasingly use continuous monitoring.

Instead of testing a control only periodically:

```text
Periodic Testing
      ↓
Quarterly / Annual
```

organizations may monitor control conditions continuously:

```text
System
  ↓
Continuous Monitoring
  ↓
Control Condition
  ↓
Exception
  ↓
Alert
  ↓
Investigation
```

For example:

```text
Privileged Account
       ↓
Continuous Monitoring
       ↓
Unexpected Privilege Change
       ↓
Alert
       ↓
Investigation
```

This can improve the speed at which control deficiencies are identified.

---

# Key Control Effectiveness Indicators

Organizations can monitor indicators such as:

```text
Control Failure Rate
Control Exception Rate
Overdue Control Activities
Evidence Completion Rate
Testing Pass Rate
Remediation Aging
Repeat Findings
Control Coverage
Automated Control Coverage
```

For example:

```text
Control Testing Results

100 Controls Tested
        ↓
90 Effective
7 Partially Effective
3 Ineffective
        ↓
Overall Control Effectiveness
```

Metrics should be interpreted in context rather than treated as isolated numbers.

---

# Repeat Findings

A particularly important indicator is the presence of repeat findings.

```text
Finding
   ↓
Remediation
   ↓
Retesting
   ↓
Finding Reappears
   ↓
Repeat Finding
```

Repeated failures may indicate:

```text
Weak Root Cause Analysis
Ineffective Remediation
Poor Ownership
Insufficient Resources
Poor Control Design
```

A mature organization should pay particular attention to recurring deficiencies.

---

# Control Remediation

When a control is ineffective, remediation should follow a structured process.

```text
Deficiency
    ↓
Risk Assessment
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
    ↓
Retesting
    ↓
Closure
```

Closure should be supported by evidence.

Simply marking a remediation task as "completed" does not necessarily demonstrate that the underlying control is effective.

---

# Control Effectiveness Lifecycle

The complete lifecycle can be represented as:

```text
                 CONTROL
                    ↓
              DESIGN REVIEW
                    ↓
              IMPLEMENTATION
                    ↓
                OPERATION
                    ↓
                 EVIDENCE
                    ↓
                 TESTING
                    ↓
          EFFECTIVENESS ASSESSMENT
                    ↓
             ┌──────┴──────┐
             ↓             ↓
         EFFECTIVE      DEFICIENT
             ↓             ↓
          MONITOR      ROOT CAUSE
                           ↓
                       REMEDIATION
                           ↓
                         RETEST
                           ↓
                      EFFECTIVE?
                       ↙       ↘
                     YES        NO
                      ↓          ↓
                   CLOSE      REWORK
                      ↓          │
                      └──────────┘
```

This creates a continuous feedback loop between control performance and control improvement.

---

# Practical Example – Privileged Access

Consider a privileged-access control.

### Risk

```text
Unauthorized privileged access
```

### Control Objective

```text
Ensure privileged access is appropriately authorized,
reviewed, and removed when no longer required.
```

### Control

```text
Monthly privileged-access review
```

### Testing

```text
Select six months
        ↓
Review evidence
        ↓
Check approvals
        ↓
Check exceptions
        ↓
Check remediation
```

### Results

```text
6 Reviews Required
        ↓
6 Reviews Completed
        ↓
1 Exception Identified
        ↓
Exception Remediated
        ↓
Control Operating Effectively
```

The control can therefore be considered effective even though an exception occurred, provided the exception was appropriately identified, addressed, and did not demonstrate a fundamental failure of the control.

---

# Practical Example – Vulnerability Management

```text
Risk
 ↓
Exploitation of known vulnerabilities
 ↓
Control Objective
 ↓
Identify and remediate vulnerabilities
 ↓
Control
 ↓
Monthly vulnerability scanning
 ↓
Evidence
 ↓
Scan reports
 ↓
Testing
 ↓
Review scan coverage and remediation
 ↓
Finding
 ↓
Critical vulnerabilities remain unresolved
 ↓
Control Effectiveness Assessment
 ↓
Partially Effective / Ineffective
```

The assessment should consider why the vulnerabilities remained unresolved and whether compensating measures were in place.

---

# Practical Example – Backup and Recovery

```text
Risk
 ↓
Loss of critical data
 ↓
Control Objective
 ↓
Ensure critical data can be recovered
 ↓
Control
 ↓
Backup and restoration testing
 ↓
Evidence
 ↓
Backup logs
+
Restoration test reports
 ↓
Testing
 ↓
Review recovery results
 ↓
Result
 ↓
Effective / Deficient
```

Importantly, successful backup completion alone may not demonstrate recovery effectiveness.

The organization may also need to demonstrate that the backup can actually be restored within the required recovery parameters.

---

# Executive Control Effectiveness Model

At the executive level, the detailed control information can be summarized as:

```text
                BUSINESS RISK
                     ↓
              CONTROL COVERAGE
                     ↓
            CONTROL EFFECTIVENESS
                     ↓
                RESIDUAL RISK
                     ↓
             RISK APPETITE
                     ↓
              MANAGEMENT ACTION
```

This gives executives a more meaningful view than simply reporting:

```text
"95% of controls are compliant."
```

A stronger executive question is:

> **Are our critical controls effective enough to keep our most important risks within acceptable levels?**

---

# Integrated Control Effectiveness Model

The complete model can be represented as:

```text
                         RISK
                          ↓
                  CONTROL OBJECTIVE
                          ↓
                     CONTROL DESIGN
                          ↓
                  IMPLEMENTATION
                          ↓
                      OPERATION
                          ↓
                       EVIDENCE
                          ↓
                       TESTING
                          ↓
               EFFECTIVENESS ASSESSMENT
                          ↓
                ┌─────────┴─────────┐
                ↓                   ↓
             EFFECTIVE          DEFICIENT
                ↓                   ↓
             MONITOR            ROOT CAUSE
                                    ↓
                                REMEDIATION
                                    ↓
                                  RETEST
                                    ↓
                               VALIDATION
                                    ↓
                           CONTROL IMPROVEMENT
                                    ↺
```

The most important principle is:

> **Control effectiveness should be demonstrated through evidence and testing, connected to the risk the control is intended to address, and continuously reassessed as the organization's risks, technologies, processes, and regulatory obligations change.**

A mature GRC program therefore moves beyond asking **"Do we have a control?"** and instead asks **"Is the control appropriately designed, operating as intended, supported by reliable evidence, and actually reducing the relevant risk to an acceptable level?"**

