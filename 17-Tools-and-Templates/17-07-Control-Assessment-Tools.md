**17.7 Control Assessment Tools**

**Part 1 – Control Assessment Questionnaire**

A **Control Assessment Questionnaire (CAQ)** is a structured tool used by GRC, cybersecurity, internal audit, compliance, and risk teams to assess whether security controls have been designed and implemented appropriately.

The questionnaire provides a consistent method for collecting information about controls from control owners, process owners, system owners, suppliers, or other responsible stakeholders.

The fundamental purpose is to answer:

> **Is the control designed appropriately, implemented, and operating as expected?**

A control questionnaire should not simply ask whether a control exists. A mature assessment should gather enough information to determine:

* What the control is intended to achieve.
* Who owns the control.
* How the control operates.
* Where the control applies.
* How frequently it operates.
* What evidence supports it.
* Whether exceptions exist.
* Whether the control is effective.
* What risks are associated with weaknesses.

A basic control assessment questionnaire can contain:

```text
CONTROL ASSESSMENT QUESTIONNAIRE

Assessment ID:

Assessment Date:

Assessment Scope:

Business Unit:

Control ID:

Control Name:

Control Objective:

Control Description:

Control Owner:

Process Owner:

System / Asset:

Assessment Question:

Response:

Implementation Status:

Evidence Reference:

Exception:

Risk Reference:

Assessor Comments:

Control Owner Comments:

Assessment Result:

Remediation Required:

Remediation Owner:

Target Date:
```

The first step is defining the **assessment scope**.

For example:

```text
Assessment Scope:

Identity and Access Management

Systems:
Corporate applications
Cloud platforms
Remote access infrastructure

Business Units:
All corporate departments

Assessment Period:
January–December 2026
```

A clearly defined scope prevents confusion about which systems, business units, controls, and processes are included.

The questionnaire should then identify the **control being assessed**.

For example:

```text
Control ID:
AC-05

Control Name:
Privileged Access Review

Control Objective:
Ensure privileged access is periodically reviewed
and unauthorized or unnecessary access is removed.
```

The control objective is important because the assessment should determine whether the control actually achieves its intended purpose.

The questionnaire should capture the **control description**.

For example:

> Privileged accounts are reviewed quarterly by the designated system owner and inappropriate access is removed within the defined remediation period.

This provides the basis for assessment.

The questionnaire should then ask targeted questions.

For example:

```text
1. Is the control formally documented?

2. Is a control owner assigned?

3. Is the control implemented?

4. Is the control performed at the required frequency?

5. Are responsibilities clearly defined?

6. Is evidence retained?

7. Are exceptions formally managed?

8. Is the control monitored?

9. Has the control been tested?

10. Have weaknesses been identified?
```

The questions should be specific enough to produce useful information.

A weak question would be:

> Do you have access controls?

A stronger question would be:

> Are privileged user accounts reviewed at least quarterly by an authorized reviewer, with evidence of the review retained?

The second question is much easier to assess and validate.

A control questionnaire can use different response types.

For example:

```text
Yes
No
Partially
Not Applicable
Unknown
```

However, the meaning of each response should be clearly defined.

For example:

| Response  | Meaning                                                     |
| --------- | ----------------------------------------------------------- |
| Yes       | Control is implemented as defined                           |
| No        | Control is not implemented                                  |
| Partially | Control is implemented but does not fully meet requirements |
| N/A       | Control does not apply to the defined scope                 |
| Unknown   | Sufficient information is not currently available           |

The **Unknown** response is particularly useful.

An assessor should not force a Yes or No answer when the control owner cannot provide sufficient information.

For example:

> The control owner believes quarterly access reviews are performed, but no evidence is currently available.

The appropriate response may be:

> Unknown.

This should then generate an evidence request or follow-up assessment activity.

The questionnaire should also distinguish between **control existence** and **control effectiveness**.

For example:

```text
Control Exists:
Yes

Control Implemented:
Yes

Evidence Available:
Yes

Control Operating:
Yes

Control Effective:
To be validated
```

A documented policy alone does not prove that a control is effective.

For example:

> The organization has an Access Control Policy.

This demonstrates that a policy exists.

It does not demonstrate that:

> Access reviews are actually performed every quarter.

The questionnaire should therefore collect evidence.

Examples include:

* Policies.
* Procedures.
* System configurations.
* Access review reports.
* Audit logs.
* Security reports.
* Meeting records.
* Training records.
* Tickets.
* Screenshots.
* System-generated reports.
* Risk assessments.
* Exception records.

The questionnaire should include an **evidence reference**.

For example:

```text
Evidence ID:
EV-2026-104

Evidence:
Q2 2026 Privileged Access Review Report

Related Control:
AC-05

Evidence Owner:
IAM Team
```

This provides traceability between the assessment response and supporting documentation.

A control questionnaire can be structured around different control domains.

For example:

```text
Access Control
Asset Management
Vulnerability Management
Security Monitoring
Incident Response
Data Protection
Third-Party Risk
Business Continuity
Security Awareness
Physical Security
```

For example, an access control questionnaire might contain:

| Question                               | Response  | Evidence              |
| -------------------------------------- | --------- | --------------------- |
| Is access formally authorized?         | Yes       | Access Request        |
| Is MFA implemented?                    | Partially | IAM Report            |
| Are privileged accounts reviewed?      | Yes       | Q2 Review             |
| Are terminated users removed promptly? | Yes       | HR/IAM Report         |
| Are exceptions documented?             | No        | No register available |

The questionnaire can therefore identify weaknesses even when the control is generally implemented.

A control assessment should also identify the **control owner**.

For example:

```text
Control:
Privileged Access Review

Control Owner:
IAM Manager

Supporting Team:
Security Operations

Process Owner:
IT Security Manager
```

Ownership matters because the control owner is normally accountable for ensuring that the control is properly designed, implemented, maintained, and evidenced.

The questionnaire should also identify the **assessor**.

For example:

```text
Assessor:
GRC Analyst

Assessment Date:
10 August 2026

Review Method:
Questionnaire + Evidence Review
```

This creates an assessment trail.

A mature assessment should not rely exclusively on self-assessment questionnaires.

The questionnaire is often the **starting point**.

The overall process may be:

```text
Questionnaire
      ↓
Control Owner Response
      ↓
Evidence Submission
      ↓
GRC Review
      ↓
Testing
      ↓
Control Assessment Result
```

This distinction is important.

A control owner may respond:

> Yes, quarterly access reviews are performed.

The GRC assessor may then request:

> Please provide the Q1 and Q2 2026 access review records.

The evidence may reveal that only one review was actually performed.

The assessment result may therefore change from:

```text
Yes
```

to:

```text
Partially Implemented
```

This demonstrates why evidence-based assessment is important.

The questionnaire can also include **control assessment criteria**.

For example:

```text
Design:
Does the control adequately address the intended risk?

Implementation:
Has the control been deployed?

Operation:
Is the control actually performed?

Evidence:
Can performance be demonstrated?

Effectiveness:
Does the control achieve its intended objective?
```

This creates a more mature assessment model.

The questionnaire can therefore assess the control across multiple dimensions.

For example:

| Dimension      | Result              |
| -------------- | ------------------- |
| Design         | Effective           |
| Implementation | Effective           |
| Operation      | Partial             |
| Evidence       | Effective           |
| Overall        | Partially Effective |

This is more informative than a single Yes/No response.

The questionnaire should also consider **control frequency**.

Examples include:

```text
Continuous
Daily
Weekly
Monthly
Quarterly
Semiannual
Annual
Event-Based
```

For example:

```text
Control:
Privileged Access Review

Required Frequency:
Quarterly

Actual Frequency:
Semiannual
```

The control may therefore be considered partially implemented or ineffective depending on the organization's requirements.

Frequency should always be assessed against the approved control requirement.

The questionnaire should also identify **control scope**.

For example:

```text
Required Scope:
All production systems

Actual Scope:
80% of production systems
```

The control may exist but have incomplete coverage.

This is a common GRC issue.

For example:

> Vulnerability scanning is implemented.

However:

> Only corporate servers are scanned; cloud workloads are excluded.

The appropriate assessment should therefore consider the coverage gap.

A useful questionnaire field is:

```text
Control Coverage:
100%
75–99%
50–74%
Below 50%
Unknown
```

Organizations can define their own thresholds.

The questionnaire should also capture **exceptions**.

For example:

```text
Control:
MFA

Exception:
Legacy application does not support MFA.

Exception ID:
EX-2026-014

Compensating Control:
Network restriction and enhanced monitoring.

Expiration:
31 December 2026
```

The existence of an exception does not automatically mean the control is ineffective.

The assessor should determine whether the exception is:

* Formally approved.
* Risk assessed.
* Time-bound.
* Properly documented.
* Supported by compensating controls.

The questionnaire should also identify the related **risk**.

For example:

```text
Control:
MFA

Risk:
Unauthorized account access

Risk ID:
R-023

Risk Rating:
High
```

This allows the assessment to connect control weaknesses with organizational risk.

The relationship is:

```text
Risk
 ↓
Control
 ↓
Assessment
 ↓
Evidence
 ↓
Effectiveness Result
 ↓
Risk Treatment
```

This is a core GRC principle.

The questionnaire should also support **Not Applicable** decisions.

However, the assessor should require justification.

For example:

```text
Response:
N/A

Justification:
The control applies only to industrial control
systems, and no such systems are included
within the approved assessment scope.
```

An unsupported N/A response should not automatically be accepted.

The GRC team should validate whether the control truly falls outside the assessment scope.

A questionnaire can also be designed around a specific framework.

For example:

```text
ISO/IEC 27001
NIST CSF
NIST SP 800-53
COBIT
CIS Controls
Internal Security Framework
Regulatory Requirements
```

The same underlying control may map to multiple frameworks.

For example:

```text
Internal Control:
Privileged Access Review

ISO 27001:
Access Control

NIST CSF:
Identity Management and Access Control

CIS Controls:
Account Management
```

This allows organizations to avoid creating completely separate assessments for every framework.

A **control library** can therefore serve as the foundation for the questionnaire.

```text
Control Library
      ↓
Framework Mapping
      ↓
Assessment Questionnaire
      ↓
Evidence Collection
      ↓
Testing
      ↓
Reporting
```

The questionnaire can also be automated using a GRC platform.

A typical workflow may be:

```text
GRC System
    ↓
Assessment Created
    ↓
Questionnaire Assigned
    ↓
Control Owner Notified
    ↓
Responses Submitted
    ↓
Evidence Uploaded
    ↓
GRC Review
    ↓
Exceptions Identified
    ↓
Assessment Completed
```

This reduces manual coordination.

However, automation does not eliminate the need for professional judgment.

For example, a system may automatically record:

> Control Owner Response = Yes.

The GRC assessor still needs to determine whether the supporting evidence actually demonstrates that the control is operating effectively.

A good questionnaire should therefore balance **standardization** with **professional judgment**.

The questions should be standardized, while the assessor should retain the ability to request additional evidence or perform additional testing.

A practical control assessment questionnaire can be divided into sections.

```text
Section 1:
Control Identification

Section 2:
Control Design

Section 3:
Implementation

Section 4:
Operation

Section 5:
Evidence

Section 6:
Exceptions

Section 7:
Risk

Section 8:
Assessment Result

Section 9:
Remediation
```

For example:

```text
CONTROL IDENTIFICATION

Control ID:
AC-05

Control Name:
Privileged Access Review

Control Owner:
IAM Manager
```

Then:

```text
CONTROL DESIGN

Q1. Is the control formally documented?
Q2. Does the control address the identified risk?
Q3. Are responsibilities clearly defined?
Q4. Is the required frequency defined?
```

Then:

```text
CONTROL IMPLEMENTATION

Q5. Has the control been implemented?
Q6. Does implementation cover the defined scope?
Q7. Are supporting systems configured appropriately?
```

Then:

```text
CONTROL OPERATION

Q8. Is the control performed at the required frequency?
Q9. Are identified exceptions handled?
Q10. Are control results reviewed by management?
```

Then:

```text
EVIDENCE

Q11. Is evidence retained?
Q12. Is evidence complete?
Q13. Can the evidence demonstrate control performance?
```

This structured approach produces better assessment results.

The questionnaire should also include **assessor comments**.

For example:

> The control is implemented for corporate applications; however, two critical cloud applications are excluded from the quarterly access review process.

This provides context behind the assessment result.

The final assessment result can use a standard classification.

For example:

```text
Effective
Partially Effective
Ineffective
Not Implemented
Not Applicable
Unable to Determine
```

The organization should establish definitions for each result.

For example:

| Result              | Definition                                                                                      |
| ------------------- | ----------------------------------------------------------------------------------------------- |
| Effective           | Control is appropriately designed, implemented, operating, and supported by sufficient evidence |
| Partially Effective | Control exists but has material weaknesses or incomplete coverage                               |
| Ineffective         | Control exists but does not adequately address the intended risk                                |
| Not Implemented     | Required control is absent                                                                      |
| N/A                 | Control does not apply to the defined scope                                                     |
| Unable to Determine | Insufficient information or evidence to reach a conclusion                                      |

The assessment should then determine whether **remediation is required**.

For example:

```text
Assessment Result:
Partially Effective

Remediation:
Required

Remediation:
Extend quarterly access reviews
to cloud applications.
```

The remediation should be tracked through the organization's issue or risk management process.

A practical end-to-end control assessment process is:

```text
1. Define Scope
        ↓
2. Identify Controls
        ↓
3. Assign Control Owners
        ↓
4. Issue Questionnaire
        ↓
5. Collect Responses
        ↓
6. Collect Evidence
        ↓
7. Review Responses
        ↓
8. Perform Testing
        ↓
9. Assess Effectiveness
        ↓
10. Identify Gaps
        ↓
11. Create Remediation
        ↓
12. Track Closure
```

For a practical exercise, assess the following control:

```text
Control ID:
AC-05

Control Name:
Privileged Access Review

Control Objective:
Ensure privileged access is authorized,
appropriate, and periodically reviewed.

Required Frequency:
Quarterly

Required Scope:
All production systems
```

Assume the control owner provides the following responses:

```text
Control documented:
Yes

Control implemented:
Yes

Quarterly review performed:
Yes

Evidence available:
Yes

Coverage:
80%

Exceptions documented:
Yes

Cloud applications included:
No
```

The assessor should determine:

```text
Control Design:
Effective

Implementation:
Partial

Coverage:
80%

Overall Assessment:
Partially Effective
```

The assessor should then identify the gap:

> The privileged access review process is established but does not cover all production systems. Cloud applications are currently excluded from the quarterly review.

The associated risk may be:

> Unauthorized or excessive privileged access may remain undetected within excluded cloud applications.

The remediation could be:

```text
Action:
Extend quarterly privileged access reviews
to all in-scope cloud applications.

Owner:
IAM Manager

Target Date:
Q1 2027

Success Criteria:
100% of production systems are included
in the quarterly privileged access review.
```

This demonstrates how a questionnaire response can move through the GRC lifecycle:

```text
Questionnaire
      ↓
Evidence
      ↓
Assessment
      ↓
Gap
      ↓
Risk
      ↓
Remediation
      ↓
Validation
      ↓
Closure
```

The key principle is:

> **A Control Assessment Questionnaire provides a standardized mechanism for gathering control information, validating implementation, collecting evidence, identifying weaknesses, and establishing a defensible basis for assessing control effectiveness.**



