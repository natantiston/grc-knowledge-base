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

A **Control Testing Template** is used to determine whether a security control is operating as intended and whether there is sufficient evidence to support the assessment conclusion.

The questionnaire from Part 1 primarily gathers information from the control owner. Control testing goes further by independently examining evidence and determining whether the control actually works as intended.

The distinction can be summarized as:

```text
Control Questionnaire
        ↓
"What does the control owner say?"
        ↓
Control Testing
        ↓
"What does the evidence demonstrate?"
        ↓
Control Effectiveness
```

A control may be documented and implemented but still fail during testing.

For example:

> The organization states that privileged access is reviewed quarterly.

Testing may reveal that the last review occurred eight months ago.

The control therefore exists, but it is not operating according to its defined frequency.

A practical **Control Testing Template** can contain:

```text
CONTROL TESTING TEMPLATE

Test ID:

Assessment ID:

Control ID:

Control Name:

Control Objective:

Control Owner:

Process Owner:

Assessment Scope:

Testing Period:

Tester:

Test Date:

Control Requirement:

Test Objective:

Test Procedure:

Population:

Sample Size:

Sampling Method:

Evidence Requested:

Evidence Received:

Test Performed:

Test Result:

Exceptions Identified:

Control Effectiveness:

Risk Reference:

Finding:

Remediation Required:

Remediation Owner:

Target Date:

Retest Required:

Retest Result:

Final Status:

Tester Comments:
```

The first step is to define the **test objective**.

The test objective explains what the assessor is trying to determine.

For example:

```text
Control:
Privileged Access Review

Test Objective:
Determine whether privileged access reviews
are performed quarterly for all in-scope
production systems.
```

The objective should be directly related to the control requirement.

A good test objective is specific and measurable.

Weak:

> Test access controls.

Stronger:

> Determine whether all privileged accounts in the defined population were reviewed and approved during each required quarterly review period.

The next step is to define the **control requirement**.

For example:

```text
Control Requirement:

All privileged accounts must be reviewed
quarterly by an authorized reviewer.
Evidence of review and approval must
be retained.
```

The test should then determine whether the requirement has actually been met.

The tester should define the **testing period**.

For example:

```text
Testing Period:

1 January 2026 – 30 June 2026
```

If the control operates quarterly, the tester may therefore expect to see:

```text
Q1 2026 Review
Q2 2026 Review
```

The testing period should be appropriate to the control frequency and assessment objective.

The tester should also identify the **population**.

The population is the complete set of items from which testing may be performed.

For example:

```text
Population:

1,250 privileged access records
across all production systems.
```

Other examples of populations include:

* All employees.
* All privileged accounts.
* All security incidents.
* All vendors.
* All vulnerabilities.
* All access requests.
* All backup jobs.
* All firewall changes.
* All security awareness training records.

The population must be defined before sampling.

For example:

```text
Population:
1,250 privileged accounts
```

is different from:

```text
Sample:
50 privileged accounts
```

The sample is selected from the population.

The tester should document the **sampling method**.

Common approaches include:

```text
Random Sampling
Systematic Sampling
Risk-Based Sampling
Judgmental Sampling
Stratified Sampling
Full Population Testing
```

The appropriate method depends on the control, population, risk, and assessment objective.

For example, a high-risk control may justify full-population testing.

```text
Population:
All privileged accounts

Test:
100% of privileged accounts
```

For a large population, sampling may be more practical.

For example:

```text
Population:
10,000 user accounts

Sample:
100 accounts

Method:
Risk-based sampling
```

The sample size should be determined using the organization's approved testing methodology.

The tester should not simply choose a convenient number without justification.

The **risk-based approach** is particularly useful in cybersecurity GRC.

For example, a sample may deliberately include:

```text
High-privilege accounts
Remote users
External users
Recently created accounts
Recently terminated users
Service accounts
Cloud administrator accounts
```

This can provide greater assurance than purely random selection.

The testing procedure should then be documented.

For example:

```text
Test Procedure:

1. Obtain the privileged account population.
2. Obtain quarterly access review records.
3. Select the approved sample.
4. Verify each sampled account appears
   in the appropriate review.
5. Verify reviewer authorization.
6. Verify review date.
7. Verify approval or removal decision.
8. Verify evidence retention.
9. Document exceptions.
```

A clear test procedure makes the assessment repeatable.

Another tester should be able to understand how the test was performed.

Testing should also distinguish between **design testing** and **operating effectiveness testing**.

Design testing asks:

> Is the control appropriately designed to address the risk?

Operating effectiveness testing asks:

> Did the control actually operate as designed during the assessment period?

For example:

```text
Design:
Quarterly privileged access reviews
would address the identified risk.

Operating Effectiveness:
Were the quarterly reviews actually
performed and documented?
```

Both dimensions can be important.

A control may be well designed but poorly implemented.

For example:

```text
Design:
Effective

Implementation:
Effective

Operating Effectiveness:
Ineffective
```

Another control may be consistently performed but poorly designed.

For example:

```text
Design:
Ineffective

Operation:
Consistent
```

In this case, the organization may be performing a control reliably, but the control itself may not adequately address the underlying risk.

The tester should therefore understand what the control is intended to accomplish.

The testing process should collect **objective evidence**.

Examples include:

* System reports.
* Configuration exports.
* Audit logs.
* Access review records.
* Tickets.
* Approval records.
* Change records.
* Incident records.
* Vulnerability reports.
* Training records.
* Meeting minutes.
* Backup reports.
* Recovery test results.

Evidence should ideally come from reliable sources.

For example:

```text
Strong Evidence:
System-generated access report

Supporting Evidence:
Approved access review

Weak Evidence:
Verbal confirmation from control owner
```

A verbal statement may help explain the process but normally should not be the only evidence supporting a control conclusion.

The tester should document each piece of evidence.

For example:

```text
Evidence ID:
EV-2026-245

Evidence:
Q2 Privileged Access Review Report

Source:
IAM Platform

Period:
April–June 2026

Provided By:
IAM Manager

Date Received:
15 July 2026
```

This creates evidence traceability.

The tester should then record the **test performed**.

For example:

```text
Test Performed:

Selected 50 privileged accounts from
the approved population and compared
them against the Q2 access review report.

Result:

48 accounts were reviewed and approved.
2 accounts were not included in the review.
```

This provides a clear connection between the test procedure and the result.

The tester should identify **exceptions**.

For example:

```text
Sample:
50 accounts

Exceptions:
2

Exception Rate:
4%
```

However, an exception rate alone does not automatically determine whether a control is effective.

The organization should define its testing criteria.

For example:

```text
Control Result:

Pass:
No material exceptions identified.

Partial:
Limited exceptions that do not materially
undermine the control.

Fail:
Material or widespread exceptions.
```

The exact thresholds should be documented before testing where practical.

The tester should also consider the **nature of the exception**.

For example:

```text
Exception 1:
Low-risk standard administrator account.

Exception 2:
Production database administrator account.
```

The second exception may be significantly more important because of the privilege level and business criticality.

This is why control testing should be risk-based rather than purely numerical.

A useful assessment model is:

```text
Exception Count
        +
Exception Severity
        +
Control Coverage
        +
Risk Impact
        ↓
Control Test Result
```

The tester should also determine whether the exception is isolated or systemic.

For example:

```text
One exception:
Potential isolated failure

Repeated exceptions:
Potential process weakness

Widespread exceptions:
Potential control failure
```

This distinction is important for determining remediation.

The test result should be clearly documented.

For example:

```text
Test Result:

Partially Effective

Reason:

The control operates as designed for most
sampled accounts; however, two high-privilege
accounts were excluded from the quarterly
review.
```

The assessment should then identify the related risk.

For example:

```text
Risk:
Unauthorized privileged access may remain
undetected.

Risk Rating:
High

Risk ID:
R-023
```

The test result should not exist independently from the risk management process.

The relationship is:

```text
Control
   ↓
Test
   ↓
Exception
   ↓
Risk
   ↓
Finding
   ↓
Remediation
```

The tester should also determine whether the finding requires immediate escalation.

For example:

```text
Critical Finding:
Privileged account with inappropriate
production access and no review evidence.

Action:
Immediate management escalation.
```

Not every control exception requires the same response.

The tester should also document the **root cause**, where appropriate.

For example:

```text
Finding:
Cloud administrator accounts were not included
in quarterly access reviews.

Root Cause:
Cloud accounts were managed separately from
the corporate IAM review process.
```

Identifying root cause helps prevent recurring failures.

Possible root causes may include:

* Process design weakness.
* Lack of ownership.
* Technology limitation.
* Incomplete system integration.
* Insufficient training.
* Inadequate monitoring.
* Resource constraints.
* Poor documentation.
* Organizational change.
* Legacy technology.

The remediation should address the root cause where practical.

For example:

Weak remediation:

> Remind IAM team to perform reviews.

Stronger remediation:

> Integrate cloud administrator accounts into the enterprise access review population and establish automated quarterly review reporting.

The stronger remediation addresses the underlying process problem.

The testing template should also include **remediation ownership**.

For example:

```text
Finding:
Cloud administrator accounts excluded
from access review.

Remediation Owner:
IAM Manager

Supporting Owner:
Cloud Security Manager

Target Date:
31 December 2026
```

The remediation should then be tracked to closure.

The tester should also determine whether **retesting** is required.

For example:

```text
Initial Result:
Partially Effective

Remediation:
Completed

Retest:
Required
```

The retest determines whether the remediation actually resolved the finding.

A retest may include:

```text
Updated Population
+
Updated Configuration
+
New Evidence
+
Repeat Testing
```

The final result may then be:

```text
Original Finding:
Partially Effective

Retest Result:
Effective

Finding:
Closed
```

Alternatively:

```text
Retest Result:
Partially Effective

Finding:
Remains Open
```

This prevents organizations from closing findings merely because a remediation task has been marked complete.

A mature control testing lifecycle is:

```text
Control Identified
        ↓
Test Objective Defined
        ↓
Population Defined
        ↓
Sample Selected
        ↓
Evidence Collected
        ↓
Testing Performed
        ↓
Exceptions Identified
        ↓
Result Determined
        ↓
Finding Created
        ↓
Remediation
        ↓
Retest
        ↓
Closure
```

The testing template should also distinguish between **evidence obtained** and **evidence evaluated**.

For example:

```text
Evidence Received:
Access Review Report

Evidence Evaluated:
Reviewed population, dates,
approvals, exceptions, and reviewer identity.

Conclusion:
Evidence supports control operation
for 48 of 50 sampled accounts.
```

This creates a defensible audit trail.

A practical control testing table can look like:

| Test ID | Control                  | Test Objective                  | Population | Sample | Result       | Exceptions | Effectiveness |
| ------- | ------------------------ | ------------------------------- | ---------: | -----: | ------------ | ---------: | ------------- |
| T-001   | Privileged Access Review | Verify quarterly review         |      1,250 |     50 | 48/50 passed |          2 | Partial       |
| T-002   | Vulnerability Scanning   | Verify critical systems scanned |        850 |     85 | 85/85        |          0 | Effective     |
| T-003   | Security Awareness       | Verify annual training          |      2,000 |    100 | 94/100       |          6 | Partial       |

The testing results can then be summarized for management.

For example:

```text
Controls Tested:
25

Effective:
18

Partially Effective:
5

Ineffective:
2

Critical Findings:
1

High Findings:
4
```

However, management reporting should also explain the significance of the findings.

A simple percentage of effective controls may not provide enough context.

For example:

> 90% of controls were effective.

This could still conceal one critical failure involving privileged access or sensitive customer information.

The GRC professional should therefore emphasize **risk significance**, not only control counts.

Control testing can also be performed using different methods.

Common methods include:

```text
Inquiry
Inspection
Observation
Reperformance
Technical Testing
Data Analysis
Configuration Review
Walkthrough
```

For example:

**Inquiry**

The assessor interviews the control owner to understand how the process operates.

**Inspection**

The assessor reviews documentation and evidence.

**Observation**

The assessor observes the control being performed.

**Reperformance**

The assessor independently repeats the control activity.

**Technical Testing**

The assessor examines system configuration, logs, or technical settings.

Using multiple methods can provide stronger assurance.

For example:

```text
Inquiry:
IAM team explains the review process.

Inspection:
Reviewer examines access review records.

Technical Testing:
IAM system confirms account population.

Reperformance:
Assessor independently verifies sampled accounts.
```

This provides stronger assurance than inquiry alone.

The testing approach should also consider **control type**.

For example:

```text
Preventive Control
      ↓
Test whether the control prevents
the unwanted event.

Detective Control
      ↓
Test whether the control identifies
the unwanted event.

Corrective Control
      ↓
Test whether the control restores
or corrects the condition.
```

For example:

```text
Preventive:
MFA

Detective:
Security Monitoring

Corrective:
Incident Response
```

The test procedure should reflect the purpose of the control.

A control testing program should also maintain **independence and objectivity**.

Where appropriate, the person performing the assessment should not be the same person who owns or operates the control.

For example:

```text
Control Owner:
IAM Manager

Tester:
GRC Analyst

Approver:
CISO / GRC Manager
```

This separation improves credibility.

The degree of independence should depend on the purpose of the assessment.

An operational self-check may be performed by the control owner.

An internal audit may require greater independence.

A regulatory or external audit may require formal auditor independence.

The organization should therefore define different testing levels.

For example:

```text
Level 1:
Control Owner Self-Assessment

Level 2:
GRC Independent Assessment

Level 3:
Internal Audit

Level 4:
External / Regulatory Assessment
```

The evidence requirements and testing rigor can increase at each level.

For a practical exercise, use the following control:

```text
Control ID:
VM-03

Control Name:
Vulnerability Scanning

Control Requirement:
All critical production systems must be
scanned monthly for vulnerabilities.

Population:
500 critical production systems

Sample:
50 systems

Testing Period:
April–June 2026
```

Evidence shows:

```text
April:
49 of 50 sampled systems scanned

May:
50 of 50 scanned

June:
47 of 50 scanned
```

The assessor should determine:

```text
Test Objective:
Verify monthly vulnerability scanning.

Test Result:
Exceptions identified.

Overall Assessment:
Partially Effective.
```

The assessor should then investigate why the exceptions occurred.

Possible causes may include:

```text
Cloud systems excluded
Scanning failures
Asset inventory inaccuracies
Maintenance windows
Unregistered systems
Technical limitations
```

The final finding should identify the actual root cause rather than simply stating:

> Three systems were not scanned.

A stronger finding might be:

> Vulnerability scanning coverage is incomplete because recently deployed cloud workloads are not consistently registered in the vulnerability management platform.

The remediation should therefore address the underlying asset registration process.

For example:

```text
Remediation:

Integrate cloud asset discovery with the
vulnerability management platform and establish
a process to automatically identify unregistered
critical workloads.
```

The success criteria could be:

```text
100% of critical production systems are
included in monthly vulnerability scanning.
```

Evidence could include:

```text
Asset inventory
Vulnerability scanning report
Scanning coverage dashboard
Exception register
```

The complete testing lifecycle would then be:

```text
Control Requirement
        ↓
Test Objective
        ↓
Population
        ↓
Sample
        ↓
Evidence
        ↓
Testing
        ↓
Exception
        ↓
Finding
        ↓
Risk
        ↓
Remediation
        ↓
Retest
        ↓
Closure
```

The key principle is:

> **Control testing provides objective evidence that a control is appropriately designed, implemented, and operating as intended, while identifying exceptions that may require risk treatment or remediation.**




