**17.5 Security Assessment and Audit Templates**

### Part 1 – Security Assessment Template

A **security assessment** evaluates whether an organization's security controls, processes, systems, or requirements are appropriately designed and operating as intended.

A well-designed security assessment template provides a consistent structure for collecting information, evaluating controls, recording evidence, identifying gaps, and documenting results.

The assessment process can be represented as:

```text
Assessment Scope
       ↓
Requirements
       ↓
Controls
       ↓
Evidence
       ↓
Testing
       ↓
Assessment Result
       ↓
Findings
       ↓
Remediation
       ↓
Follow-up
```

The objective is not simply to complete a checklist. The objective is to determine whether the organization is achieving the intended security outcome.

---

## 1.1 Purpose of a Security Assessment

Security assessments can be used to determine:

* Whether security controls are implemented.
* Whether controls are appropriately designed.
* Whether controls operate effectively.
* Whether requirements are being met.
* Whether risks are adequately addressed.
* Whether evidence supports compliance.
* Whether remediation is required.

Assessments can support:

* ISO/IEC 27001.
* NIST CSF.
* COBIT.
* GDPR.
* NIS2.
* Internal security requirements.
* Customer security requirements.
* Third-party assessments.
* Internal audits.
* Regulatory examinations.

---

## 1.2 Security Assessment Template

A practical security assessment template can contain:

```text
SECURITY ASSESSMENT

Assessment ID:
Assessment Name:
Assessment Type:
Assessment Scope:
Assessment Period:

Assessment Owner:
Lead Assessor:
Business Owner:

Framework / Requirement:
Assessment Criteria:

Assessment Objectives:

Systems / Processes in Scope:

Control Requirements:

Evidence Required:

Testing Method:

Assessment Results:

Findings:

Risk Rating:

Recommendations:

Remediation Actions:

Action Owner:

Target Date:

Overall Assessment Result:

Approval:

Review Date:
```

The exact fields can be modified depending on the type of assessment.

---

## 1.3 Assessment Types

Different assessments may require different approaches.

### Control Assessment

Evaluates whether specific security controls are designed and operating effectively.

### Compliance Assessment

Determines whether the organization meets defined regulatory or framework requirements.

### Risk Assessment

Identifies and evaluates risks associated with systems, processes, assets, or activities.

### Security Architecture Assessment

Evaluates whether a system architecture incorporates appropriate security controls.

### Application Security Assessment

Evaluates application security requirements and controls.

### Third-Party Security Assessment

Evaluates the security posture of a supplier or service provider.

### Internal Security Assessment

Evaluates organizational security practices independently of the operational team responsible for implementation.

The template should therefore identify the **assessment type** at the beginning.

---

## 1.4 Assessment Scope

The scope should clearly define what is being assessed.

For example:

> This assessment evaluates the access control, authentication, privileged access, and access review controls implemented for the organization's customer relationship management platform.

The scope should identify:

* Systems.
* Applications.
* Business processes.
* Locations where relevant.
* Business units.
* Control areas.
* Assessment period.

A poorly defined scope can create confusion about what was actually assessed.

---

## 1.5 Assessment Objectives

The assessment should define what it intends to determine.

Example:

> The objective of this assessment is to determine whether privileged access controls are appropriately designed and operating effectively.

Additional objectives could include:

* Determine compliance with organizational requirements.
* Identify control gaps.
* Evaluate evidence.
* Identify residual risks.
* Determine remediation requirements.

Objectives provide direction to the assessor.

---

## 1.6 Assessment Criteria

The assessor needs defined criteria against which the environment will be evaluated.

For example:

```text
Assessment Criteria:

- ISO/IEC 27001 requirements
- Organizational Access Control Policy
- Privileged Access Standard
- IAM Procedure
- Applicable regulatory requirements
```

The assessment result is meaningful only when the organization knows what it is being assessed against.

---

## 1.7 Control Assessment Structure

A control assessment can use a consistent structure:

| Field         | Example                        |
| ------------- | ------------------------------ |
| Control ID    | AC-07                          |
| Control Name  | Privileged Access              |
| Requirement   | Privileged access must use MFA |
| Control Owner | IAM Manager                    |
| Evidence      | IAM configuration report       |
| Testing       | Configuration inspection       |
| Result        | Effective                      |
| Finding       | None                           |

This allows multiple controls to be assessed consistently.

---

## 1.8 Evidence Collection

Evidence is a fundamental component of security assessments.

Examples include:

* Policies.
* Procedures.
* System configurations.
* Access reports.
* Audit logs.
* Vulnerability reports.
* Tickets.
* Training records.
* Risk assessments.
* Meeting records.
* Screenshots.
* System-generated reports.

Evidence should demonstrate the actual operation of the control.

For example, a policy stating that MFA is required does not necessarily prove that MFA is actually enabled.

A stronger evidence set might contain:

```text
MFA Standard
      ↓
IAM Configuration
      ↓
Privileged Account Report
      ↓
Sample Testing
      ↓
Assessment Result
```

---

## 1.9 Evidence Quality

Not all evidence has the same value.

Strong evidence is generally:

* Relevant.
* Current.
* Complete.
* Authentic.
* Traceable.
* Directly related to the control.
* Covering the required assessment period.

For example:

> "The company uses MFA."

is an assertion.

A system-generated report showing MFA enrollment for all privileged accounts is stronger evidence.

---

## 1.10 Assessment Testing Methods

Different controls require different testing methods.

Common methods include:

### Inquiry

The assessor asks responsible personnel how a control operates.

### Inspection

The assessor reviews documents, configurations, records, or evidence.

### Observation

The assessor observes a process being performed.

### Reperformance

The assessor independently performs the control activity or repeats part of it.

### Sampling

The assessor selects a representative subset of records for testing.

A mature assessment may use multiple methods.

---

## 1.11 Example – Access Review Assessment

Suppose the requirement is:

> Privileged access must be reviewed quarterly.

The assessor could:

1. Obtain the privileged account population.
2. Obtain quarterly review records.
3. Select a sample.
4. Verify management approval.
5. Verify review dates.
6. Verify identified exceptions.
7. Verify remediation.
8. Confirm evidence integrity.
9. Record the result.

The assessment is therefore based on evidence rather than simply asking:

> "Do you perform quarterly reviews?"

---

## 1.12 Assessment Results

Organizations should define consistent assessment results.

For example:

| Result              | Meaning                                              |
| ------------------- | ---------------------------------------------------- |
| Effective           | Requirement is implemented and operating effectively |
| Partially Effective | Requirement is implemented but weaknesses exist      |
| Ineffective         | Requirement is not operating effectively             |
| Not Implemented     | Requirement has not been implemented                 |
| Not Applicable      | Requirement does not apply                           |
| Unable to Determine | Insufficient evidence                                |

The organization should define these ratings before performing assessments.

---

## 1.13 Findings

A finding identifies a condition that requires attention.

A strong finding should explain:

```text
Requirement
     ↓
Condition
     ↓
Evidence
     ↓
Risk / Impact
     ↓
Recommendation
```

For example:

**Requirement**

> Privileged accounts must be reviewed quarterly.

**Condition**

> Three of the twelve quarterly reviews examined were completed after the required deadline.

**Evidence**

> Access review records for Q1, Q2, and Q3.

**Risk**

> Delayed reviews may allow inappropriate privileged access to remain active.

**Recommendation**

> Establish automated reminders and escalation for overdue privileged access reviews.

This is much stronger than simply writing:

> "Access review needs improvement."

---

## 1.14 Risk Rating

Findings should be risk-rated using the organization's approved methodology.

For example:

| Rating        | Description                                 |
| ------------- | ------------------------------------------- |
| Critical      | Severe security or business impact          |
| High          | Significant risk requiring prompt action    |
| Medium        | Moderate risk requiring planned remediation |
| Low           | Limited risk that should be addressed       |
| Informational | Improvement opportunity                     |

The rating should be based on the organization's risk methodology rather than the assessor's personal preference.

---

## 1.15 Recommendations

Recommendations should address the identified weakness.

Weak recommendation:

> Improve access reviews.

Better recommendation:

> Implement automated quarterly access review notifications with escalation to application owners when reviews remain incomplete after the defined deadline.

A good recommendation should be:

* Specific.
* Practical.
* Risk-focused.
* Actionable.
* Assigned to an appropriate owner.

---

## 1.16 Remediation Tracking

Findings should normally lead to tracked corrective actions.

Example:

| Finding                | Risk   | Action             | Owner | Due Date | Status      |
| ---------------------- | ------ | ------------------ | ----- | -------- | ----------- |
| Delayed access reviews | Medium | Automate reminders | IAM   | 30 Sep   | Open        |
| Missing MFA            | High   | Enable MFA         | IT    | 15 Sep   | In Progress |

This turns the assessment from a static report into an improvement process.

---

## 1.17 Assessment Report

At the conclusion of the assessment, the assessor should produce a concise report.

A typical report contains:

```text
1. Executive Summary
2. Assessment Scope
3. Objectives
4. Methodology
5. Assessment Criteria
6. Overall Results
7. Findings
8. Risk Summary
9. Recommendations
10. Remediation Plan
11. Conclusion
12. Appendices
```

Senior management generally needs the overall risk picture rather than every individual testing detail.

---

## 1.18 Executive Summary

The executive summary should answer:

* What was assessed?
* Why was it assessed?
* What was the overall result?
* What are the most significant issues?
* What actions are required?

Example:

> The assessment evaluated privileged access controls across 25 critical applications. Overall control effectiveness was assessed as Partially Effective. Two high-risk and five medium-risk findings were identified, primarily relating to delayed access reviews and incomplete MFA coverage. Remediation plans have been assigned to the responsible control owners.

This provides management with a concise view of the assessment.

---

## 1.19 Assessment Metrics

Assessment results can be converted into metrics.

Examples include:

* Percentage of controls effective.
* Percentage partially effective.
* Number of findings.
* Number of high-risk findings.
* Number of overdue findings.
* Average remediation time.
* Percentage of assessments completed on schedule.

For example:

```text
Total Controls Assessed: 100

Effective:             82
Partially Effective:   12
Ineffective:            4
Not Implemented:        2
```

This allows GRC teams to identify trends over time.

---

## 1.20 Assessment Dashboard

The results can be presented through a management dashboard:

```text
Security Assessment Status

Controls Assessed:          100
Effective:                    82%
Partially Effective:          12%
Ineffective:                   4%
Not Implemented:               2%

High-Risk Findings:            2
Medium-Risk Findings:          5
Overdue Actions:               3
```

Dashboards help management understand the organization's control environment without reviewing the complete assessment report.

---

## 1.21 Assessment Follow-Up

An assessment should not end when the report is issued.

Follow-up activities may include:

1. Confirm remediation ownership.
2. Monitor deadlines.
3. Validate completed actions.
4. Collect remediation evidence.
5. Re-test affected controls.
6. Close findings.
7. Update risk records.
8. Report unresolved issues.

The lifecycle becomes:

```text
Assess
  ↓
Identify
  ↓
Risk Rate
  ↓
Remediate
  ↓
Validate
  ↓
Close
```

---

## 1.22 Practical Exercise – Perform a Control Assessment

Select the following requirement:

> All privileged accounts must use multi-factor authentication.

Create an assessment record containing:

* Control ID.
* Requirement.
* Control owner.
* Evidence required.
* Testing method.
* Assessment result.
* Finding.
* Risk rating.
* Recommendation.
* Remediation owner.
* Due date.

Then determine what evidence would be sufficient to support the conclusion.

---

## 1.23 Practical Exercise – Assess a Sample

Assume an organization has:

```text
100 Privileged Accounts

MFA Enabled:
94

MFA Not Enabled:
6
```

The security standard requires:

> 100% of privileged accounts must use MFA.

Determine:

* Compliance percentage.
* Non-compliance percentage.
* Assessment result.
* Potential risk.
* Recommended action.

Then determine whether the six accounts should be remediated or formally excepted.

---

## 1.24 GRC Professional Perspective

A GRC professional should understand that an assessment is not simply a questionnaire.

There is a major difference between:

> "The control owner says the control is implemented."

and:

> "The control owner provides evidence demonstrating that the control is implemented and operating effectively."

The GRC professional should therefore challenge unsupported assertions and seek objective evidence.

A strong assessment connects:

```text
Requirement
    ↓
Control
    ↓
Evidence
    ↓
Testing
    ↓
Result
    ↓
Risk
    ↓
Remediation
```

This provides defensible evidence for management, auditors, regulators, customers, and other stakeholders.

The ultimate purpose of a security assessment is not to produce a completed spreadsheet.

It is to provide **reasonable assurance about the effectiveness of security controls and identify areas where security risk should be reduced**.

## Key Takeaways

1. A security assessment determines whether security requirements and controls are appropriately implemented and operating effectively.
2. Assessment templates provide consistency and repeatability.
3. The assessment should have a clearly defined scope, objective, criteria, and methodology.
4. Evidence is essential for supporting assessment conclusions.
5. Different testing methods may be appropriate for different controls.
6. Findings should identify the requirement, condition, evidence, risk, and recommendation.
7. Risk ratings should follow an approved organizational methodology.
8. Findings should be assigned owners and tracked through remediation.
9. Assessment results should be converted into meaningful GRC metrics.
10. Follow-up testing should confirm that remediation actually resolved the identified weakness.
11. GRC professionals should distinguish between management assertions and objective evidence.
12. A mature security assessment provides **evidence-based assurance about the organization's security posture and identifies opportunities for risk reduction**.
    :::
A security audit template provides a structured method for examining whether an organization's governance, controls, processes, and evidence meet defined requirements.

While a security assessment may focus on evaluating control effectiveness or identifying security weaknesses, an audit generally places greater emphasis on **independent, objective, and evidence-based evaluation against defined criteria**.

A practical security audit process can be represented as:

```text id="q5h8xm"
Audit Planning
      ↓
Scope and Criteria
      ↓
Evidence Collection
      ↓
Testing
      ↓
Findings
      ↓
Audit Report
      ↓
Corrective Actions
      ↓
Follow-Up
```

The audit template should help the auditor consistently document each stage.

A practical **Security Audit Template** can contain:

```text id="j7r2kd"
SECURITY AUDIT

Audit ID:
Audit Name:
Audit Type:
Audit Scope:
Audit Period:

Audit Lead:
Audit Team:
Business Owner:

Audit Criteria:
Applicable Policies:
Applicable Standards:
Applicable Regulations:

Audit Objectives:

Systems / Processes in Scope:

Audit Methodology:

Evidence Requested:

Tests Performed:

Audit Results:

Findings:

Risk Ratings:

Recommendations:

Corrective Actions:

Management Response:

Action Owner:

Due Date:

Audit Conclusion:

Approval:

Follow-Up Date:
```

The template should be adapted to the organization's audit methodology.

Security audits may be performed for different purposes.

Examples include:

* Internal security audits.
* ISO/IEC 27001 internal audits.
* Regulatory audits.
* Customer audits.
* Supplier audits.
* Compliance audits.
* Control audits.
* Information security management system audits.
* Technology audits.

The audit type should be documented because it affects the scope, criteria, independence requirements, and reporting approach.

A critical element of an audit is the **audit criteria**.

The auditor needs to know what requirements are being evaluated.

For example:

```text id="w4z0bd"
Audit Criteria

ISO/IEC 27001 requirements
        +
Information Security Policy
        +
Access Control Standard
        +
IAM Procedure
        +
Applicable regulatory requirements
```

The audit conclusion is then based on the defined criteria.

An audit should also establish clear **objectives**.

For example:

> The objective of this audit is to determine whether the organization's access control processes are implemented and operating in accordance with approved security policies, standards, and applicable ISO/IEC 27001 requirements.

Other objectives may include:

* Evaluating control effectiveness.
* Determining compliance.
* Identifying control deficiencies.
* Evaluating evidence.
* Identifying opportunities for improvement.
* Confirming corrective actions from previous audits.

The audit scope should be equally clear.

For example:

> The audit covers identity and access management controls for critical business applications operated by the organization's European business units during the period January–June 2026.

The scope may include:

* Organizational units.
* Applications.
* Infrastructure.
* Business processes.
* Geographic locations.
* Assessment period.
* Specific controls.

A clearly defined scope prevents disagreements about what the audit did and did not examine.

The audit team should also establish an **audit plan**.

A practical audit plan could contain:

| Activity         | Responsible | Planned Date | Status      |
| ---------------- | ----------- | ------------ | ----------- |
| Kickoff meeting  | Audit Lead  | 01 Sep       | Complete    |
| Evidence request | Auditor     | 02 Sep       | Complete    |
| Document review  | Audit Team  | 03–05 Sep    | In Progress |
| Interviews       | Audit Team  | 08 Sep       | Planned     |
| Control testing  | Audit Team  | 09–12 Sep    | Planned     |
| Findings review  | Audit Lead  | 15 Sep       | Planned     |
| Draft report     | Audit Lead  | 18 Sep       | Planned     |
| Final report     | Audit Lead  | 22 Sep       | Planned     |

This helps keep the audit controlled and predictable.

Evidence requests should also be standardized.

For example:

```text id="y7m3ba"
Evidence Request

Control:
Privileged Access Management

Requirement:
Privileged access must be reviewed quarterly.

Evidence Requested:
- Privileged account inventory
- Q1 access review
- Q2 access review
- Approval records
- Remediation tickets
- Exception records

Evidence Period:
January–June 2026

Evidence Owner:
IAM Manager

Due Date:
05 September 2026
```

This is more effective than sending a vague request such as:

> "Please provide access control evidence."

Evidence should be linked to specific audit requirements.

The auditor should maintain an **audit evidence register**.

Example:

| Evidence ID | Requirement       | Evidence    | Owner     | Status   |
| ----------- | ----------------- | ----------- | --------- | -------- |
| EV-001      | MFA               | IAM report  | IAM       | Received |
| EV-002      | Access review     | Q2 review   | App Owner | Received |
| EV-003      | Logging           | SIEM report | SOC       | Pending  |
| EV-004      | Privileged access | PAM report  | IAM       | Received |

This creates traceability between the audit requirement and supporting evidence.

Evidence should also be assessed for quality.

The auditor should consider:

* Is the evidence relevant?
* Is it complete?
* Is it current?
* Does it cover the audit period?
* Is the source reliable?
* Can it be independently verified?
* Does it actually demonstrate the control?

For example, a screenshot of a security configuration may demonstrate configuration at a particular point in time, but it may not demonstrate that the control operated consistently throughout the entire audit period.

Sampling is another important part of audit testing.

Auditors rarely examine every transaction or account.

Instead, they may select representative samples.

For example:

```text id="l9v4st"
1,000 User Accounts
        ↓
Risk-Based Sample
        ↓
50 Accounts Tested
        ↓
Evidence Review
        ↓
Test Result
```

The sampling methodology should be appropriate to the audit objective.

For higher-risk areas, the auditor may require:

* Larger samples.
* Targeted samples.
* Judgmental samples.
* Statistical sampling.
* Complete population testing.

The auditor should document how the sample was selected.

For example:

> A sample of 50 privileged accounts was selected from the population of 500 privileged accounts, with additional targeted selection of high-risk administrative accounts.

This makes the audit process more defensible.

Audit interviews are another source of information.

The auditor may interview:

* Control owners.
* System administrators.
* Security personnel.
* Business managers.
* GRC personnel.
* Application owners.
* Senior management.

However, an interview response should not automatically be treated as sufficient evidence.

For example:

> "We review access every quarter."

The auditor should then request evidence demonstrating that quarterly reviews actually occurred.

This creates an important principle:

> **Interview responses provide information; objective evidence provides support for audit conclusions.**

The auditor should document testing procedures.

Example:

```text id="m2tr1p"
Control:
Quarterly Privileged Access Review

Test:
1. Obtain privileged account population.
2. Select sample.
3. Verify quarterly review evidence.
4. Confirm reviewer authorization.
5. Verify review date.
6. Check identified exceptions.
7. Verify remediation.
8. Record results.
```

The test result should then be recorded.

For example:

| Sample      | Review Completed | Approved | Timely | Result |
| ----------- | ---------------- | -------- | ------ | ------ |
| Account 001 | Yes              | Yes      | Yes    | Pass   |
| Account 002 | Yes              | Yes      | Yes    | Pass   |
| Account 003 | Yes              | No       | —      | Fail   |
| Account 004 | Yes              | Yes      | Yes    | Pass   |

This allows the auditor to demonstrate how the conclusion was reached.

Audit findings should be structured consistently.

A useful finding structure is:

```text id="t2h5wx"
Finding ID:
Finding Title:

Requirement:

Condition:

Evidence:

Risk / Impact:

Root Cause:

Recommendation:

Management Response:

Action Owner:

Due Date:
```

The **requirement** explains what should have happened.

The **condition** explains what actually happened.

The **evidence** supports the condition.

The **risk** explains why the issue matters.

The **root cause** explains why the problem occurred.

The **recommendation** explains what should be done.

For example:

**Requirement**

> Privileged access must be reviewed quarterly.

**Condition**

> Five of twenty sampled privileged accounts did not have evidence of the required quarterly review.

**Evidence**

> IAM access review records for Q1 and Q2 2026.

**Risk**

> Inadequate periodic review may allow inappropriate privileged access to remain active.

**Root Cause**

> The current review process relies on manual tracking and does not include automated escalation.

**Recommendation**

> Implement automated access review reminders and escalation for overdue reviews.

This provides management with a much clearer understanding of the issue.

Audit findings should also be risk-rated.

A typical methodology might use:

```text id="v7v8si"
Critical
High
Medium
Low
Observation
```

The organization should define the criteria for each rating.

For example:

| Rating      | General Meaning                                          |
| ----------- | -------------------------------------------------------- |
| Critical    | Severe exposure requiring immediate management attention |
| High        | Significant security risk requiring prompt remediation   |
| Medium      | Material weakness requiring planned remediation          |
| Low         | Limited weakness requiring corrective action             |
| Observation | Improvement opportunity                                  |

The exact definitions should be based on the organization's risk management methodology.

Auditors should avoid assigning ratings purely based on intuition.

The rating should consider factors such as:

* Likelihood.
* Impact.
* Control effectiveness.
* Asset criticality.
* Data sensitivity.
* Regulatory exposure.
* Threat environment.
* Existing compensating controls.

Audit observations are different from formal findings.

An observation might identify an opportunity to improve a process even when the organization technically meets the requirement.

For example:

> The organization meets the minimum access review requirement, but automated monitoring could improve the timeliness of remediation.

This may not represent a control failure but could still be valuable to management.

The audit report should summarize the overall results.

A practical structure is:

```text id="nq0j1x"
Security Audit Report

1. Executive Summary
2. Audit Objectives
3. Audit Scope
4. Audit Criteria
5. Audit Methodology
6. Overall Conclusion
7. Findings
8. Risk Summary
9. Recommendations
10. Management Responses
11. Corrective Action Plan
12. Follow-Up Requirements
13. Appendices
```

The **executive summary** should be understandable to senior management.

It should answer:

* What was audited?
* Why was it audited?
* What was the overall conclusion?
* What are the most significant findings?
* What actions are required?

For example:

> The audit evaluated access management controls across 15 critical applications. The overall control environment was assessed as Generally Effective, with two high-risk and four medium-risk findings. The primary weaknesses relate to privileged access reviews and delayed remediation of excessive permissions.

This provides management with the essential information without requiring them to read the complete audit workpapers.

Audit results can also be presented using dashboards.

For example:

```text id="kj8qk7"
Audit Results

Controls Tested:             75

Effective:                   61
Partially Effective:          9
Ineffective:                  3
Not Applicable:               2

Critical Findings:            0
High Findings:                2
Medium Findings:              4
Low Findings:                 6

Overdue Actions:               3
```

This allows the GRC function to identify trends across multiple audits.

Audit findings should be tracked through a **corrective action plan**.

Example:

| Finding | Risk   | Corrective Action         | Owner | Due Date | Status      |
| ------- | ------ | ------------------------- | ----- | -------- | ----------- |
| F-001   | High   | Implement PAM MFA         | IAM   | 30 Sep   | In Progress |
| F-002   | High   | Automate access review    | IT    | 15 Oct   | Open        |
| F-003   | Medium | Improve logging retention | SOC   | 30 Oct   | Open        |

The audit is not complete simply because the report has been issued.

The organization must determine whether corrective actions actually address the findings.

This requires follow-up testing.

For example:

```text id="m7n6kn"
Audit Finding
      ↓
Corrective Action
      ↓
Management Claims Completion
      ↓
Evidence Submitted
      ↓
Auditor Validation
      ↓
Effective?
   ↙       ↘
 YES       NO
 ↓          ↓
Close     Reopen
```

A finding should not be closed simply because the action owner says:

> "Completed."

The auditor or designated reviewer should validate the evidence.

This distinction is important in GRC:

> **Action completion is not necessarily the same as risk remediation.**

For example, an organization may implement a new access review procedure but fail to perform the reviews.

The documentation changed, but the underlying control weakness remains.

Audit independence is another important consideration.

Where appropriate, the person performing an audit should be sufficiently independent from the activity being audited.

For example, the person responsible for operating a control should generally not be the sole person determining whether that same control is effective.

This helps reduce conflicts of interest and improves objectivity.

A practical audit governance model might be:

```text id="7w7xxh"
Control Owner
      ↓
Operates Control
      ↓
GRC / Internal Audit
      ↓
Performs Independent Assessment
      ↓
Management
      ↓
Reviews Findings
```

The appropriate level of independence depends on the type and purpose of the audit.

For regulated or certified environments, audit records should be retained according to the organization's document retention requirements.

Audit records may include:

* Audit plan.
* Evidence requests.
* Evidence received.
* Testing workpapers.
* Interview records.
* Sampling methodology.
* Findings.
* Management responses.
* Final report.
* Corrective action records.
* Follow-up evidence.

These records create an audit trail.

A GRC platform can automate many of these activities.

For example:

```text id="c5b3xu"
Audit Created
     ↓
Controls Assigned
     ↓
Evidence Requests
     ↓
Evidence Collection
     ↓
Testing
     ↓
Findings
     ↓
Corrective Actions
     ↓
Management Review
     ↓
Closure
```

This is particularly useful when an organization manages multiple frameworks, business units, audits, and regulatory obligations.

A practical audit assessment should also distinguish between **design effectiveness** and **operating effectiveness**.

Design effectiveness asks:

> Is the control appropriately designed to address the identified risk?

Operating effectiveness asks:

> Is the control actually operating as designed?

For example:

**Design**

> Quarterly privileged access reviews are required and assigned to application owners.

**Operating effectiveness**

> Evidence demonstrates that application owners actually performed the reviews every quarter and remediated identified issues.

A control may therefore be:

```text
Well Designed + Operating Effectively
        = Effective

Well Designed + Not Operating Effectively
        = Operating Weakness

Poorly Designed + Operating Consistently
        = Design Weakness
```

This distinction is extremely important for GRC professionals.

A practical audit exercise is to create an audit plan for an **Access Control Audit**.

Define:

```text id="f6s3eq"
Audit Objective:
Determine whether access controls are appropriately designed
and operating effectively.

Scope:
Critical business applications.

Criteria:
Access Control Policy
Access Control Standard
IAM Procedures
Applicable ISO/IEC 27001 controls

Testing:
- User provisioning
- User termination
- Privileged access
- MFA
- Access reviews
- Segregation of duties

Evidence:
- IAM reports
- Access tickets
- Review records
- Configuration reports
- Exception records
```

Then create at least three hypothetical findings.

For each finding, identify:

* Requirement.
* Condition.
* Evidence.
* Risk.
* Root cause.
* Recommendation.
* Owner.
* Due date.

Another useful exercise is to perform a **follow-up audit**.

Assume an original audit identified:

> 15 privileged accounts did not have MFA enabled.

Management implemented a remediation project and reported:

> "MFA has now been enabled."

The GRC professional should not immediately close the finding.

Instead:

1. Obtain the current privileged account population.
2. Obtain MFA configuration evidence.
3. Compare the population against the MFA-enabled accounts.
4. Test a sample.
5. Determine whether all affected accounts were remediated.
6. Identify any remaining exceptions.
7. Validate that exceptions are formally approved.
8. Determine whether the original risk has been reduced sufficiently.
9. Document the follow-up result.
10. Close or reopen the finding.

This demonstrates the difference between **management representation** and **validated remediation**.

From a GRC perspective, a strong audit template should create traceability across the entire audit lifecycle:

```text id="s3j4i4"
Requirement
      ↓
Control
      ↓
Evidence
      ↓
Test
      ↓
Result
      ↓
Finding
      ↓
Risk
      ↓
Corrective Action
      ↓
Validation
      ↓
Closure
```

This traceability is valuable during internal audits, external audits, regulatory reviews, customer assessments, and certification activities.

The most important principle is that an audit should be **evidence-based, objective, risk-focused, and actionable**.

A completed audit checklist by itself provides limited value.

A strong audit provides management with reasonable assurance about the effectiveness of controls, identifies significant weaknesses, explains the associated risks, and tracks corrective actions until the identified issues have been appropriately addressed.

## Key Takeaways

1. A security audit evaluates controls against defined and approved criteria.
2. An audit template provides consistency across planning, testing, reporting, and follow-up.
3. Audit scope, objectives, criteria, and methodology should be defined before testing begins.
4. Evidence should be relevant, reliable, current, complete, and traceable.
5. Interviews provide information, but objective evidence should support audit conclusions.
6. Sampling should follow an appropriate and documented methodology.
7. Findings should clearly identify the requirement, condition, evidence, risk, root cause, and recommendation.
8. Audit findings should be risk-rated using an approved methodology.
9. Corrective actions should be tracked to completion and independently validated where appropriate.
10. Management's claim that an action is complete does not automatically demonstrate that the underlying risk has been addressed.
11. Auditors should consider both design effectiveness and operating effectiveness.
12. A mature audit process provides an evidence-based chain from **requirement through control testing, finding, remediation, validation, and closure**.




