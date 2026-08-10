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


