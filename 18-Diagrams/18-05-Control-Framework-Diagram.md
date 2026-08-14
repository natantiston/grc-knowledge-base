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


