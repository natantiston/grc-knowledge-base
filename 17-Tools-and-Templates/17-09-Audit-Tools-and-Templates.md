**17.9 Audit Tools and Templates**

**Part 1 – Audit Planning Template**

An Audit Planning Template is a structured tool used to define how an audit will be conducted, what will be assessed, who will participate, what evidence will be required, and how the audit will be completed and reported.

Effective audit planning ensures that the audit is properly scoped, risk-based, objective, and aligned with the organization's governance, security, compliance, and business objectives.

The audit planning process can be represented as:

```text
Audit Objective
      ↓
Audit Scope
      ↓
Audit Criteria
      ↓
Risk Assessment
      ↓
Audit Approach
      ↓
Audit Program
      ↓
Resources and Responsibilities
      ↓
Evidence Requirements
      ↓
Audit Schedule
      ↓
Audit Execution
      ↓
Reporting
      ↓
Follow-Up
```

A practical Audit Planning Template can contain:

```text
AUDIT PLANNING TEMPLATE

Audit ID:

Audit Name:

Audit Type:

Audit Objective:

Audit Scope:

Business Unit:

Systems / Processes:

Locations:

Audit Period:

Audit Criteria:

Applicable Regulations:

Applicable Standards:

Applicable Policies:

Risk Areas:

Audit Methodology:

Audit Approach:

Audit Team:

Lead Auditor:

Subject Matter Experts:

Business Contacts:

Audit Schedule:

Opening Meeting:

Fieldwork Start:

Fieldwork End:

Closing Meeting:

Evidence Requirements:

Sampling Approach:

Testing Approach:

Previous Findings:

Known Issues:

Audit Deliverables:

Reporting Date:

Finding Classification:

Corrective Action Process:

Management Responsibilities:

Audit Approval:

Audit Notes:
```

The first step in audit planning is to define the **audit objective**.

The audit objective explains why the audit is being performed and what the audit is expected to determine.

For example:

```text
Audit Objective:

Evaluate whether the organization's
information security controls are appropriately
designed, implemented, and operating effectively
to support ISO/IEC 27001 requirements.
```

Another example:

```text
Audit Objective:

Assess whether third-party security management
controls are implemented and operating in
accordance with organizational requirements.
```

A well-defined objective prevents the audit from becoming unnecessarily broad.

The objective should answer:

```text
What are we trying to determine?
```

The next step is to define the **audit scope**.

The scope establishes the boundaries of the audit.

For example:

```text
Scope:

Enterprise Identity and Access Management

Included:

User provisioning
User deprovisioning
Privileged access
Access reviews
MFA
Service accounts

Excluded:

Physical access controls
Application development
Network security
```

The scope should be sufficiently specific to allow the audit team and stakeholders to understand what will and will not be assessed.

A poorly defined scope can create problems during fieldwork.

For example:

> Review access controls.

This is too broad.

A stronger scope would be:

> Assess user lifecycle management, privileged access management, authentication controls, and periodic access reviews for production systems supporting critical business services.

The scope should also identify the **audit period**.

For example:

```text
Audit Period:

1 January 2026 – 30 June 2026
```

The audit period is important because evidence must normally relate to the period being assessed.

The audit should then identify the **audit criteria**.

Audit criteria are the requirements against which the organization will be assessed.

They may include:

```text
ISO/IEC 27001
ISO/IEC 27002
NIST CSF
NIS2
DORA
GDPR
Internal Policies
Security Standards
Contracts
Customer Requirements
Regulatory Requirements
```

For example:

```text
Audit Criteria:

ISO/IEC 27001:2022
Information Security Policy
Access Control Standard
Privileged Access Procedure
Internal Risk Management Requirements
```

The audit criteria should be clearly documented before fieldwork begins.

The auditor should not change the criteria informally during the audit without appropriate approval.

The next step is to perform an **audit risk assessment**.

Audit planning should be risk-based.

Not every process or control requires the same level of audit attention.

For example:

```text
High Risk:
Privileged Access
Incident Management
Third-Party Security
Critical Infrastructure

Medium Risk:
Security Awareness
Asset Management

Low Risk:
Administrative Documentation
```

Higher-risk areas may receive:

```text
More Testing
Larger Samples
More Detailed Evidence Review
More Frequent Interviews
Technical Validation
```

Risk-based planning allows limited audit resources to be focused where they provide the greatest assurance value.

A practical audit risk assessment may consider:

```text
Business Criticality
Regulatory Exposure
Threat Level
Previous Findings
Control Failures
System Sensitivity
Data Sensitivity
Recent Changes
Third-Party Dependencies
Audit History
```

For example:

| Audit Area               | Risk   | Reason                         | Audit Priority |
| ------------------------ | ------ | ------------------------------ | -------------- |
| Privileged Access        | High   | High-impact accounts           | High           |
| Vulnerability Management | High   | Significant technical exposure | High           |
| Security Awareness       | Medium | Broad employee population      | Medium         |
| Policy Management        | Low    | Limited operational impact     | Low            |

The audit plan should also consider **previous audit findings**.

For example:

```text
Previous Finding:

Privileged access reviews were not consistently
completed.

Current Planning Decision:

Increase testing coverage for privileged
access reviews.
```

Previous findings are valuable because recurring findings may indicate unresolved root causes.

The audit team should determine whether previous corrective actions were:

```text
Implemented
Partially Implemented
Not Implemented
Ineffective
Closed
Overdue
```

This information should influence the current audit approach.

The audit planning template should also identify the **audit methodology**.

Common approaches include:

```text
Document Review
Interviews
Walkthroughs
Sampling
Control Testing
Observation
Technical Validation
Data Analysis
Configuration Review
Evidence Inspection
```

For example:

```text
Access Management Audit

Document Review
       +
Process Walkthrough
       +
System Configuration Review
       +
Sample Testing
       +
Evidence Validation
```

Different audit objectives may require different combinations of methods.

The audit plan should also define the **audit approach**.

For example:

```text
Risk-Based Approach

High-Risk Controls:
Detailed testing

Medium-Risk Controls:
Standard testing

Low-Risk Controls:
Limited testing
```

The approach should be agreed with the relevant audit stakeholders where required.

The audit team should also define **audit responsibilities**.

A typical structure may include:

```text
Audit Director
      ↓
Lead Auditor
      ↓
Auditors
      ↓
Subject Matter Experts
```

Business stakeholders may include:

```text
Control Owners
Process Owners
System Owners
Risk Owners
Compliance
Legal
IT
Cybersecurity
Internal Audit
```

Responsibilities should be clear.

For example:

```text
Lead Auditor:
Owns audit execution and final conclusions.

Auditor:
Performs testing and documents evidence.

Control Owner:
Provides evidence and explains control operation.

Subject Matter Expert:
Provides technical expertise.

Audit Manager:
Reviews audit quality and approves reporting.
```

The audit planning template should identify the **audit team competencies** required.

For example:

```text
Technical Security Audit:

ISO 27001 Knowledge
Identity Management
Cloud Security
Network Security
Vulnerability Management
Risk Management
Audit Methodology
```

An audit should not rely on personnel who lack the expertise required to evaluate the subject matter.

Where specialized expertise is required, a subject matter expert may support the audit team.

The plan should also identify **audit contacts**.

For example:

```text
Business Contact:
Head of IT Security

Control Owner:
IAM Manager

Evidence Coordinator:
GRC Analyst

Technical Contact:
IAM Engineer
```

This makes evidence collection and communication more efficient.

The audit should also establish a **schedule**.

A basic audit schedule may include:

```text
Planning
    ↓
Opening Meeting
    ↓
Evidence Collection
    ↓
Interviews
    ↓
Control Testing
    ↓
Analysis
    ↓
Draft Findings
    ↓
Management Review
    ↓
Closing Meeting
    ↓
Final Report
    ↓
Follow-Up
```

For example:

| Activity            | Planned Date   | Owner        |
| ------------------- | -------------- | ------------ |
| Audit Planning      | 1 September    | Lead Auditor |
| Opening Meeting     | 5 September    | Audit Team   |
| Evidence Collection | 5–12 September | Auditors     |
| Fieldwork           | 8–20 September | Audit Team   |
| Draft Findings      | 23 September   | Lead Auditor |
| Management Review   | 26 September   | Management   |
| Closing Meeting     | 30 September   | Audit Team   |
| Final Report        | 5 October      | Lead Auditor |

The schedule should include sufficient time for evidence review, follow-up questions, testing, and quality review.

The audit plan should also define **evidence requirements**.

For example:

```text
Evidence Required:

Security Policies
Procedures
Risk Assessments
Control Records
System Reports
Access Review Reports
Incident Records
Training Records
Audit Logs
Meeting Records
Exception Records
```

The evidence request should be specific.

Weak request:

> Provide access management evidence.

Better request:

> Provide the Q2 2026 privileged access review report, including reviewer approvals, identified exceptions, remediation records, and evidence of access removal where applicable.

Specific evidence requests reduce unnecessary back-and-forth.

The audit plan should also define the **sampling approach**.

For example:

```text
Population:
2,500 user accounts

Sample:
50 accounts

Sampling Method:
Risk-based sampling

Higher-Risk Population:
Privileged users
Administrators
External users
Service accounts
```

Sampling should be appropriate to the audit objective.

For example, if the objective is to evaluate privileged access, the sample should not consist primarily of ordinary user accounts.

The auditor should document the sampling rationale.

```text
Sampling Rationale:

The sample emphasizes privileged accounts because
they present higher security and business risk.
```

The audit plan should also define the **testing approach**.

For example:

```text
Control:
Quarterly Access Review

Testing:

1. Obtain population.
2. Select sample.
3. Verify manager approval.
4. Verify access appropriateness.
5. Verify review completion.
6. Verify exceptions.
7. Verify remediation.
8. Document results.
```

This creates consistency across auditors.

The audit plan should identify **known issues and risks** before fieldwork.

For example:

```text
Known Issues:

Previous audit identified incomplete
privileged access reviews.

Recent Change:

IAM platform migrated in June 2026.

Planning Consideration:

Increase testing of access review
configuration and post-migration data.
```

Recent technology, organizational, regulatory, or process changes may require additional audit attention.

Examples include:

```text
New Cloud Platform
New Application
Merger or Acquisition
Organizational Restructuring
New Regulation
Major Security Incident
New Vendor
Technology Migration
New Security Control
```

The audit plan should also consider **dependencies**.

For example:

```text
Audit Dependency:

Cloud provider assurance report required
to evaluate inherited security controls.
```

Another example:

```text
Dependency:

IAM audit evidence depends on availability
of historical access review records.
```

Dependencies should be identified early so they do not delay the audit.

The audit planning template should also define the **audit deliverables**.

Typical deliverables include:

```text
Audit Workpapers
Evidence Register
Testing Results
Audit Findings
Corrective Action Plan
Draft Audit Report
Final Audit Report
Management Summary
Follow-Up Report
```

The final deliverables should be agreed with the relevant stakeholders.

The plan should also define **finding classification**.

For example:

```text
Critical
High
Medium
Low
Observation
Opportunity for Improvement
```

The organization should have documented definitions for each classification.

For example:

```text
Critical:

A significant control failure that creates
an immediate or severe risk to the organization
or results in significant regulatory exposure.
```

The exact definitions should follow the organization's approved audit methodology.

The audit plan should also establish the **corrective action process**.

For example:

```text
Finding
   ↓
Management Response
   ↓
Root Cause
   ↓
Corrective Action
   ↓
Owner
   ↓
Target Date
   ↓
Evidence
   ↓
Validation
   ↓
Closure
```

The audit should not end simply when the report is issued.

Follow-up is an important part of the audit lifecycle.

For example:

```text
Audit Report
     ↓
Corrective Actions
     ↓
Periodic Monitoring
     ↓
Validation
     ↓
Finding Closure
```

The audit planning template should also identify **management responsibilities**.

Management may be responsible for:

```text
Providing Access
Providing Evidence
Assigning Control Owners
Responding to Findings
Approving Remediation
Providing Resources
Meeting Remediation Deadlines
```

The audit team should remain independent while management remains responsible for operating and improving the controls.

The audit plan should therefore clearly distinguish:

```text
Auditor Responsibility:
Assess and report.

Management Responsibility:
Operate and remediate.
```

Auditors should not assume management's responsibility for designing or implementing controls they are expected to independently assess.

The audit plan should also consider **auditor independence and objectivity**.

For example:

```text
Auditor:
Has no direct responsibility for the
controls being audited.

Control Owner:
Provides evidence and management response.

Audit Team:
Independently evaluates evidence.
```

This is especially important for internal audits.

An individual who designed or operated a control may have valuable subject matter knowledge but may not be appropriate as the sole independent assessor of that same control.

The audit planning process should also define how **audit evidence will be stored and protected**.

For example:

```text
Evidence Repository
       ↓
Access Control
       ↓
Audit Workpapers
       ↓
Evidence Retention
       ↓
Audit Record Management
```

Audit evidence may contain sensitive information, including:

```text
Security Configurations
System Information
Employee Information
Access Records
Incident Information
Vendor Information
Personal Data
```

Therefore, audit evidence should be handled according to applicable information security and data protection requirements.

The audit plan should also identify the **communication process**.

For example:

```text
Opening Communication
       ↓
Periodic Status Updates
       ↓
Evidence Queries
       ↓
Preliminary Findings
       ↓
Management Discussion
       ↓
Closing Meeting
       ↓
Final Report
```

Regular communication helps prevent surprises at the end of the audit.

Potential issues should be discussed with control owners during the audit rather than being raised for the first time in the final report.

However, preliminary discussions should not compromise auditor independence or the final audit conclusion.

The audit plan should also define how **audit changes** will be managed.

For example:

```text
Original Scope:
Identity and Access Management

New Risk Identified:
Major privileged access issue

Decision:
Expand testing to cloud administrator accounts.

Reason:
Risk identified during fieldwork.

Approval:
Audit Manager
```

Changes to scope, criteria, or methodology should be documented.

The audit planning template should also support **audit readiness**.

Before fieldwork begins, the audit team should confirm:

```text
Scope Approved
Criteria Defined
Audit Team Assigned
Schedule Confirmed
Evidence Request Prepared
Previous Findings Reviewed
Risk Assessment Completed
Testing Approach Defined
Stakeholders Identified
Access Arrangements Completed
```

A simple readiness checklist can be:

```text
[ ] Objective defined
[ ] Scope approved
[ ] Criteria identified
[ ] Risks assessed
[ ] Audit team assigned
[ ] Responsibilities defined
[ ] Evidence request issued
[ ] Sampling methodology defined
[ ] Audit schedule confirmed
[ ] Previous findings reviewed
[ ] Opening meeting scheduled
```

This helps prevent an audit from starting before the necessary preparation has been completed.

A mature audit planning process should also consider **continuous auditing**.

Instead of performing certain assessments only once per year, organizations may use automated or recurring monitoring.

For example:

```text
Traditional Audit:

Annual Access Review Audit
        ↓
Once Per Year

Continuous Approach:

Monthly Access Monitoring
        ↓
Quarterly Control Testing
        ↓
Annual Independent Audit
```

Continuous monitoring does not necessarily replace independent auditing, but it can provide earlier identification of control weaknesses.

Audit planning can also be integrated with the organization's broader GRC platform.

For example:

```text
Audit Plan
    ↓
Audit Scope
    ↓
Controls
    ↓
Evidence Requests
    ↓
Testing
    ↓
Findings
    ↓
Issues
    ↓
Remediation
    ↓
Risk
```

This creates a connected audit lifecycle.

GRC platforms can automate activities such as:

```text
Audit Scheduling
Evidence Requests
Task Assignment
Notifications
Workflow Approvals
Finding Tracking
Remediation Tracking
Dashboard Reporting
Evidence Retention
```

The technology should support the audit methodology rather than replace professional judgment.

The Audit Planning Template should ultimately answer:

```text
Why are we auditing?

What are we auditing?

What requirements will we assess?

What risks are relevant?

Who will perform the audit?

What evidence will we need?

How will we test the controls?

When will the audit occur?

How will findings be classified?

How will remediation be tracked?
```

A complete audit planning record may therefore look like:

```text
Audit ID:
AUD-2026-014

Audit:
Third-Party Risk Management Audit

Objective:
Evaluate the effectiveness of supplier security
risk management controls.

Scope:
High-risk suppliers supporting critical services.

Criteria:
Internal TPRM Policy
Supplier Security Standard
Contractual Requirements
Applicable Regulatory Requirements

Risk:
High

Audit Approach:
Risk-based control testing

Sample:
25 high-risk suppliers

Key Evidence:
Supplier assessments
Security questionnaires
Contracts
Risk records
Security certifications
Remediation records

Lead Auditor:
Internal Audit Manager

Control Owner:
Third-Party Risk Manager

Fieldwork:
September 2026

Reporting:
October 2026

Deliverables:
Audit Report
Findings
Corrective Action Plan
```

The key principle is:

> **An effective Audit Planning Template establishes the objective, scope, criteria, risks, resources, evidence requirements, methodology, schedule, and responsibilities needed to conduct a structured, risk-based, and objective audit.**

**Part 2 – Audit Checklist**

An Audit Checklist is a structured list of audit criteria, control requirements, verification activities, and evidence expectations used by auditors to ensure that the audit is performed consistently and comprehensively.

The checklist translates the approved audit scope and criteria into practical assessment activities.

A well-designed audit checklist should help the auditor answer:

```text
What should be checked?

What requirement is being assessed?

What control addresses the requirement?

What evidence should be reviewed?

What testing should be performed?

What result was obtained?

Is there a gap?

What follow-up is required?
```

The basic structure is:

```text
Audit Criteria
      ↓
Requirement
      ↓
Control
      ↓
Assessment Question
      ↓
Evidence
      ↓
Testing
      ↓
Result
      ↓
Finding / Observation
```

A practical Audit Checklist Template can contain:

```text
AUDIT CHECKLIST

Audit ID:

Audit Name:

Audit Area:

Requirement ID:

Requirement:

Control ID:

Control Description:

Assessment Question:

Expected Condition:

Evidence Required:

Evidence Reviewed:

Testing Performed:

Sample:

Result:

Compliant / Effective:

Partially Compliant / Partially Effective:

Non-Compliant / Ineffective:

Not Applicable:

Observation:

Finding:

Risk:

Auditor Notes:

Control Owner:

Follow-Up Required:

Evidence Reference:

Auditor:

Date:
```

The first step in creating an audit checklist is to identify the **audit criteria**.

For example:

```text
Audit Criteria:

ISO/IEC 27001:2022
Information Security Policy
Access Control Standard
Identity Management Procedure
```

The criteria should then be translated into specific audit checks.

For example:

```text
Requirement:
Access to information assets shall be
appropriately managed.

Audit Check:

Is there an approved access control policy?

Is user access formally authorized?

Are privileged accounts controlled?

Are access rights periodically reviewed?

Are terminated users removed promptly?
```

This makes the audit requirement actionable.

A checklist should not simply copy regulatory or standard requirements.

It should translate them into questions that can be tested.

For example:

Weak checklist item:

```text
Access control is implemented.
```

Better checklist item:

```text
Verify that user access is authorized,
documented, periodically reviewed, and
removed when no longer required.
```

The second version gives the auditor a clear assessment objective.

The checklist should also identify the **control being tested**.

For example:

```text
Requirement:
Periodic access review

Control:
IAM-04 Quarterly Access Review

Audit Question:
Are user access rights reviewed at least
quarterly by authorized personnel?
```

This creates traceability between the requirement and the control.

The checklist should also define the **expected condition**.

For example:

```text
Expected Condition:

All privileged accounts are reviewed quarterly,
with documented approval and remediation of
inappropriate access.
```

The auditor can then compare the actual condition against the expected condition.

The checklist should also define the **evidence expected**.

For example:

```text
Evidence:

Quarterly access review report
Manager approvals
Exception records
Access removal tickets
IAM system reports
```

Evidence requirements should be specific enough to allow the auditor to determine whether the control is actually operating.

The checklist should also include an **evidence reference**.

For example:

```text
Evidence Reference:

EVD-2026-018
Q2 Privileged Access Review Report

EVD-2026-019
Access Removal Tickets

EVD-2026-020
IAM System Export
```

This creates an audit trail from the checklist to the supporting evidence.

A checklist can therefore connect:

```text
Requirement
     ↓
Control
     ↓
Audit Question
     ↓
Evidence
     ↓
Test Result
```

The auditor should document the **testing performed**.

For example:

```text
Testing:

Obtained population of 1,250 privileged
accounts.

Selected 40 accounts using risk-based sampling.

Verified:
Authorization
Business justification
Manager approval
Review completion
Exception handling
Access removal
```

The checklist should capture the **sample size and methodology** where sampling is used.

For example:

```text
Population:
1,250 accounts

Sample:
40 accounts

Method:
Risk-based random sampling
```

This allows another auditor or reviewer to understand how the conclusion was reached.

The checklist should distinguish between **reviewing evidence** and **testing the control**.

For example:

```text
Evidence Review:

Reviewed the access review report.

Control Testing:

Selected a sample of accounts and independently
verified authorization and review completion.
```

Evidence existing does not necessarily mean the control is effective.

A document may exist while the actual process is not being performed correctly.

The checklist should therefore encourage auditors to validate the operation of controls.

A practical checklist result may use standardized statuses:

```text
Effective
Partially Effective
Ineffective
Compliant
Partially Compliant
Non-Compliant
Not Applicable
Not Tested
```

The organization should define which status model applies to each audit methodology.

For example:

```text
Control Audit:

Effective
Partially Effective
Ineffective

Compliance Audit:

Compliant
Partially Compliant
Non-Compliant
```

Standardized results improve consistency across audits.

The auditor should also document the **basis for the result**.

For example:

```text
Result:
Partially Effective

Basis:

The quarterly access review process is
implemented; however, 5 of 40 sampled
accounts did not have documented review
evidence.
```

The result should always be supported by evidence.

The checklist should also capture **observations**.

For example:

```text
Observation:

Access reviews are performed quarterly.
However, review evidence is stored in
multiple repositories, making centralized
tracking difficult.
```

An observation does not necessarily represent a formal audit finding.

The auditor should distinguish between:

```text
Compliant Condition
Observation
Finding
Non-Conformity
Control Deficiency
```

The organization's audit methodology should define these terms.

The checklist can also help identify **control design deficiencies**.

For example:

```text
Audit Question:

Does the access review process cover all
privileged accounts?

Finding:

The process excludes certain cloud
administrator accounts.
```

This may indicate a design gap because the control population itself is incomplete.

Another example may represent an operating effectiveness issue:

```text
Control Design:
Effective

Implementation:
Effective

Operation:
Partially Effective

Issue:
Reviews were not completed for several
accounts during the assessment period.
```

The checklist should make this distinction visible.

A mature checklist should also include **follow-up questions**.

For example:

```text
Initial Question:

Are quarterly access reviews performed?

Answer:
Yes.

Follow-Up:

Provide the Q2 review evidence.

Answer:
Evidence provided.

Follow-Up:

Were exceptions identified?

Answer:
Yes.

Follow-Up:

Provide evidence that exceptions were
remediated or formally accepted.
```

This prevents the audit from stopping at a simple "yes" response.

Audit checklists should therefore support **evidence-based questioning**.

The auditor should avoid accepting statements such as:

> We perform this every quarter.

The auditor should ask:

> Please provide evidence demonstrating the quarterly reviews for the assessment period.

The checklist should encourage auditors to validate management assertions.

The same principle applies to policies.

For example:

```text
Management Statement:

The organization has a vulnerability
management policy.

Audit Verification:

Review approved policy.
Verify scope.
Verify ownership.
Verify review date.
Verify implementation.
Verify evidence of operation.
```

A policy alone does not demonstrate effective implementation.

The checklist should therefore distinguish between:

```text
Policy Exists
      ↓
Policy Approved
      ↓
Policy Communicated
      ↓
Policy Implemented
      ↓
Policy Operating
      ↓
Evidence Available
```

This provides a more complete assessment.

The checklist should also include **control ownership**.

For example:

```text
Control:
Vulnerability Management

Control Owner:
Security Operations Manager
```

The control owner may be responsible for providing evidence and explaining the process, while the auditor remains responsible for independently evaluating it.

The checklist can also be organized by **control domains**.

For example:

```text
1. Governance
2. Risk Management
3. Asset Management
4. Identity and Access Management
5. Vulnerability Management
6. Security Operations
7. Incident Management
8. Business Continuity
9. Third-Party Risk
10. Data Protection
11. Security Awareness
12. Compliance
```

This makes large audits easier to manage.

For example:

```text
Access Control Domain

AC-01 User Provisioning
AC-02 User Deprovisioning
AC-03 Privileged Access
AC-04 MFA
AC-05 Access Reviews
AC-06 Service Accounts
```

Each control can have multiple checklist questions.

The checklist should also support **regulatory mapping**.

For example:

```text
Requirement:
Regulatory Requirement R-12

Mapped Control:
IAM-04

Checklist Item:
Verify that privileged access is reviewed
at defined intervals.

Evidence:
Quarterly access review report.

Result:
Effective.
```

This creates traceability from the regulation to the audit result.

A checklist can also map multiple frameworks to the same control.

For example:

```text
Control:
Privileged Access Management

Mapped Requirements:

ISO 27001
NIS2
NIST CSF
Internal Security Standard
Customer Requirement
```

The auditor may therefore perform one control assessment that provides assurance across several requirements.

This reduces duplicated audit effort.

However, the auditor should verify that the control actually satisfies the specific requirements of each framework.

The checklist should also identify **not applicable requirements**.

For example:

```text
Requirement:
Physical data center access controls

Result:
Not Applicable

Reason:

The organization does not operate physical
data centers. Infrastructure is hosted by
qualified third-party providers.
```

The reason for marking an item as not applicable should be documented.

Simply selecting "N/A" without explanation can create questions during audit review.

The checklist should also capture **limitations**.

For example:

```text
Audit Limitation:

Historical access review records for January
2026 were unavailable due to a system migration.
```

The auditor should then consider whether the limitation affects the audit conclusion.

The checklist should also record **exceptions**.

For example:

```text
Requirement:
MFA required for privileged accounts.

Exception:
Legacy application does not support MFA.

Evidence:
Approved security exception.

Compensating Controls:
Network segmentation
Enhanced monitoring

Expiration:
31 December 2026
```

The auditor should verify that the exception is formally approved and still valid.

The checklist should also support **technical validation** where appropriate.

For example:

```text
Audit Question:

Is MFA enabled for privileged accounts?

Evidence:
IAM configuration report.

Technical Validation:
Sampled administrator accounts
and verified MFA enforcement.
```

This is stronger than relying only on screenshots or management statements.

Technical validation may include:

```text
Configuration Review
Log Review
System Query
Vulnerability Scan
Access Test
Configuration Export
Security Monitoring Data
```

The audit checklist should be designed according to the level of assurance required.

A low-risk administrative control may only require document review.

A high-risk technical control may require detailed testing.

For example:

```text
Low Risk:
Policy Review

Medium Risk:
Document Review + Interview

High Risk:
Document Review
+
Technical Validation
+
Sampling
+
Evidence Testing
```

The checklist should also support **walkthroughs**.

A walkthrough allows the auditor to follow a process from beginning to end.

For example:

```text
Employee Joins
      ↓
HR Record Created
      ↓
Access Request
      ↓
Manager Approval
      ↓
IAM Provisioning
      ↓
Access Granted
      ↓
Periodic Review
      ↓
Employee Leaves
      ↓
Access Removed
```

The auditor can test each stage.

This may identify gaps that would not be visible from reviewing the policy alone.

For example:

```text
Policy:
Manager approval required.

Walkthrough:
System allows access provisioning
before approval is completed.
```

This represents a potentially significant control weakness.

The checklist should also support **interviews**.

Interview questions should be structured around the control.

For example:

```text
Question:

Who approves privileged access?

Follow-Up:

What happens when the approver is unavailable?

Follow-Up:

How is emergency access handled?

Follow-Up:

How are emergency activities reviewed?
```

The auditor should validate interview responses against evidence.

The checklist should not become a substitute for professional judgment.

It is a structured guide, not a script that prevents auditors from investigating unexpected conditions.

For example:

```text
Checklist Question:
Are backups tested?

Answer:
Yes.

Evidence:
Backup test report.

Auditor Observation:
The report covers only one critical
application although five critical
applications are in scope.
```

The auditor should investigate the additional issue even if it was not explicitly listed as a checklist question.

A good checklist should therefore provide space for:

```text
Additional Observation
Additional Evidence
Follow-Up Question
Unexpected Condition
Auditor Judgment
```

The checklist should also support **quality review**.

A reviewer should be able to determine:

```text
Was the requirement clearly identified?

Was sufficient evidence reviewed?

Was testing appropriate?

Was the result supported?

Was the finding properly classified?

Was the conclusion reasonable?
```

This improves audit consistency and defensibility.

A practical checklist review may use:

```text
[ ] Requirement identified
[ ] Control identified
[ ] Assessment question defined
[ ] Evidence documented
[ ] Testing documented
[ ] Sample documented
[ ] Result recorded
[ ] Findings documented
[ ] Risk assessed
[ ] Follow-up identified
[ ] Evidence references included
[ ] Reviewer completed
```

The checklist should also be version-controlled.

For example:

```text
Checklist:
Access Control Audit Checklist

Version:
2.1

Owner:
Internal Audit

Effective Date:
1 September 2026

Review Date:
1 September 2027
```

Changes to the checklist should be controlled.

For example:

```text
Version 1.0:
Initial checklist.

Version 2.0:
Updated for ISO 27001:2022.

Version 2.1:
Added cloud privileged access checks.
```

Version control ensures that auditors know which criteria were used during a specific audit.

The checklist should also be reviewed periodically.

Changes may be triggered by:

```text
New Regulations
New Standards
New Security Risks
Audit Findings
Technology Changes
Business Changes
New Control Requirements
Lessons Learned
```

The checklist should therefore evolve with the organization's risk and compliance environment.

A GRC platform can also digitize the audit checklist.

For example:

```text
Audit
 ↓
Checklist
 ↓
Control
 ↓
Question
 ↓
Evidence Request
 ↓
Testing
 ↓
Result
 ↓
Finding
 ↓
Remediation
```

Digital checklists can provide:

```text
Automated Assignments
Due-Date Notifications
Evidence Links
Workflow
Status Tracking
Approval
Audit Trail
Dashboard Reporting
```

However, automation should not remove the auditor's responsibility to evaluate evidence and apply professional judgment.

A practical audit checklist may ultimately look like:

```text
CHECK-001

Requirement:
Privileged access must be periodically reviewed.

Control:
IAM-04 Quarterly Privileged Access Review

Audit Question:
Are all privileged accounts reviewed quarterly?

Expected Condition:
All active privileged accounts are included
in the review population and have documented
review approval.

Evidence:
Q2 2026 access review report.

Sample:
40 privileged accounts.

Testing:
Verified account population, approval,
review completion, and exception handling.

Result:
Partially Effective.

Observation:
5 sampled accounts lacked documented
review evidence.

Risk:
Medium.

Follow-Up:
Determine whether accounts were actually
reviewed and implement centralized evidence
retention.

Auditor:
GRC Auditor

Date:
30 September 2026
```

A well-designed Audit Checklist creates consistency without restricting professional judgment. It provides a structured path from the audit requirement to the control, evidence, testing, conclusion, and follow-up action.

The key principle is:

> **An Audit Checklist converts audit criteria into structured verification activities, helping auditors consistently evaluate controls, document evidence, identify deficiencies, and maintain a clear audit trail from requirements to conclusions.**

**Part 3 – Audit Evidence Request List**

An Audit Evidence Request List is a structured tool used to identify, organize, communicate, and track the evidence required to perform an audit.

The purpose is to ensure that auditors receive sufficient, relevant, reliable, and appropriate evidence to evaluate the controls and requirements within the audit scope.

An effective evidence request process should answer:

```text
What evidence is required?

Why is the evidence required?

Who owns the evidence?

What period should the evidence cover?

When is the evidence required?

Where should the evidence be submitted?

Has the evidence been received?

Has the evidence been reviewed?

Is additional evidence required?
```

The basic evidence request lifecycle is:

```text
Audit Scope
      ↓
Audit Criteria
      ↓
Control Requirements
      ↓
Evidence Identification
      ↓
Evidence Request
      ↓
Evidence Submission
      ↓
Evidence Review
      ↓
Follow-Up
      ↓
Evidence Validation
      ↓
Audit Conclusion
```

A practical Audit Evidence Request List can contain:

```text
AUDIT EVIDENCE REQUEST LIST

Request ID:

Audit ID:

Audit Area:

Requirement:

Control ID:

Evidence Description:

Evidence Purpose:

Evidence Owner:

Evidence Period:

Evidence Format:

Requested Date:

Due Date:

Submission Date:

Evidence Location:

Evidence Status:

Evidence Reviewed:

Additional Information Required:

Follow-Up Date:

Evidence Reference:

Confidentiality Classification:

Retention Requirement:

Auditor:

Reviewer:

Notes:
```

The first step is to identify the **audit requirement** that the evidence is intended to support.

For example:

```text
Requirement:
Privileged access must be periodically reviewed.

Control:
IAM-04 Quarterly Privileged Access Review

Evidence Required:
Q2 2026 privileged access review report.
```

This creates a direct connection between the evidence request and the audit objective.

The auditor should avoid requesting evidence without knowing what audit requirement it supports.

A weak request may say:

> Please send all access management documents.

This can result in excessive information that is difficult to review.

A stronger request is:

> Provide the Q2 2026 privileged access review report, including the population reviewed, reviewer approvals, identified exceptions, and remediation records.

Specific requests make the audit process more efficient.

The evidence request should also define the **purpose of the evidence**.

For example:

```text
Evidence:
Quarterly Access Review Report

Purpose:
Verify that privileged access was reviewed
during the assessment period.
```

Another example:

```text
Evidence:
Vulnerability Management Report

Purpose:
Verify identification, prioritization, and
remediation of critical vulnerabilities.
```

This helps the evidence owner understand what is required.

The request should identify the **evidence owner**.

For example:

```text
Evidence:
Privileged Access Review Report

Evidence Owner:
IAM Manager
```

Other evidence owners may include:

```text
Security Operations
IT Operations
HR
Privacy
Legal
Procurement
Third-Party Risk Management
Business Continuity
Cloud Operations
Application Owners
```

Clearly identifying ownership prevents requests from being sent to inappropriate individuals.

The evidence request should also define the **evidence period**.

For example:

```text
Evidence Period:
1 January 2026 – 30 June 2026
```

For recurring controls, the auditor may require evidence covering multiple periods.

For example:

```text
Quarterly Access Reviews:

Q1 2026
Q2 2026
Q3 2026
Q4 2026
```

The evidence period should align with the audit objective and scope.

The auditor should avoid requesting unnecessary historical information unless it is relevant to the audit.

The evidence request should also specify the **required format** where necessary.

For example:

```text
Preferred Format:

PDF
Excel
CSV
System Export
Screenshot
System Report
Meeting Record
Policy Document
```

The required format should depend on the type of evidence.

For example, a system configuration may be better provided as a system export rather than a screenshot.

A transaction population may be better provided in Excel or CSV format to support sampling and analysis.

The evidence request should also specify the **due date**.

For example:

```text
Requested:
5 September 2026

Due:
10 September 2026
```

Evidence deadlines should provide sufficient time for the evidence owner to respond while allowing the audit team enough time to review the material.

The request should also have a clear **status**.

A practical status model is:

```text
Requested
In Progress
Submitted
Under Review
Additional Evidence Required
Accepted
Rejected
Not Applicable
Overdue
Closed
```

For example:

```text
REQ-014

Status:
Additional Evidence Required
```

This means the original evidence was received but was not sufficient to complete the audit test.

The auditor should explain what additional information is required.

For example:

```text
Additional Evidence Required:

The submitted access review report does not
identify the reviewer for each account.

Please provide the approval records or
system audit trail demonstrating reviewer
authorization.
```

This is more effective than simply stating:

> More evidence required.

The evidence request process should also distinguish between **evidence received** and **evidence accepted**.

For example:

```text
Submitted:
Yes

Reviewed:
Yes

Accepted:
No

Reason:
Evidence does not cover the full audit period.
```

Receipt does not mean sufficiency.

Evidence must be evaluated for relevance, completeness, reliability, and adequacy.

The auditor should consider whether the evidence:

```text
Is Relevant
Is Complete
Is Authentic
Is Current
Covers the Required Period
Covers the Required Population
Comes From a Reliable Source
Supports the Audit Conclusion
```

For example:

```text
Requirement:
Quarterly privileged access review.

Evidence:
One review report from January 2026.

Audit Period:
January–June 2026.

Conclusion:
Evidence is incomplete because it does not
demonstrate the required review activity
for the full assessment period.
```

The evidence request list should therefore support **evidence sufficiency assessment**.

A practical evidence assessment may include:

```text
Relevance:
Sufficient / Insufficient

Completeness:
Sufficient / Insufficient

Reliability:
Sufficient / Insufficient

Period Coverage:
Sufficient / Insufficient

Population Coverage:
Sufficient / Insufficient

Conclusion Support:
Sufficient / Insufficient
```

Evidence should also be traceable to the specific audit test.

For example:

```text
Evidence ID:
EVD-2026-045

Audit Test:
TEST-IAM-004

Requirement:
Privileged Access Review

Control:
IAM-04

Evidence:
Q2 2026 Access Review Report
```

This creates a relationship between:

```text
Requirement
     ↓
Control
     ↓
Audit Test
     ↓
Evidence
     ↓
Result
```

This traceability is particularly important for internal audits, external audits, certification audits, regulatory assessments, and investigations.

The evidence request list should also identify **evidence sensitivity**.

Audit evidence may contain:

```text
Personal Data
Employee Information
Customer Information
Security Configurations
System Credentials
Network Information
Incident Details
Vendor Information
Commercially Sensitive Information
```

The evidence request should therefore specify appropriate handling requirements.

For example:

```text
Classification:
Confidential

Storage:
Approved Audit Evidence Repository

Access:
Audit Team and Authorized Reviewers

Transmission:
Approved Secure File Transfer
```

Sensitive evidence should not be casually exchanged through unsecured channels.

The evidence request process should also consider **data minimization**.

The auditor should request only the information necessary to perform the audit.

For example:

```text
Weak Request:
Provide the complete employee database.

Better Request:
Provide a report containing employee ID,
department, access role, account status,
and termination date for the selected sample.
```

This reduces unnecessary exposure of personal information.

The evidence request list should also identify whether evidence is **system-generated** or **manually produced**.

For example:

```text
Evidence Source:
IAM Platform

Generation:
System-generated

Evidence:
Access review completion report
```

Another example:

```text
Evidence Source:
Control Owner

Generation:
Manual

Evidence:
Management review meeting minutes
```

System-generated evidence may provide stronger assurance in some circumstances, but the auditor should still evaluate how the report was generated and whether the underlying system data is reliable.

For example:

```text
System Report:
Access Review Completed

Validation:
Verify report configuration
Verify population
Verify reporting period
Verify system source
```

A screenshot alone may not provide sufficient assurance.

The auditor should consider whether the evidence can be independently validated.

For example:

```text
Screenshot:
MFA Enabled

Additional Validation:
IAM configuration
System policy
User sample
Authentication logs
```

The strength of evidence should be evaluated based on the audit objective.

The evidence request list should also support **sampling evidence**.

For example:

```text
Population:
2,500 users

Audit Sample:
40 users

Evidence Requested:

Authorization records
Access provisioning records
Manager approval
Access review evidence
Termination records
```

The auditor may first request the population and then identify the sample.

The evidence lifecycle may therefore be:

```text
Request Population
      ↓
Receive Population
      ↓
Validate Population
      ↓
Select Sample
      ↓
Request Sample Evidence
      ↓
Receive Evidence
      ↓
Perform Testing
```

This prevents the auditor from allowing the control owner to select only favorable examples.

The evidence request list can also support **walkthrough evidence**.

For example:

```text
Process:
Employee Onboarding

Evidence:

HR onboarding record
Access request
Manager approval
IAM provisioning record
System access confirmation
```

The auditor can then follow one transaction through the complete process.

This provides a practical understanding of how the control operates.

The evidence request list should also support **interview evidence**.

For example:

```text
Interview:
IAM Manager

Topics:

User provisioning
Privileged access
Emergency access
Access reviews
Exception management
```

Interview evidence should generally be supported by documentary or system evidence where the audit conclusion depends on the statement.

For example:

```text
Interview Statement:
"All privileged accounts are reviewed quarterly."

Validation:
Q1 and Q2 review reports
Account population
Approval records
```

This prevents reliance on unsupported assertions.

The evidence request list should also track **follow-up requests**.

For example:

```text
Original Request:
Q2 Access Review Report

Response:
Submitted

Review Result:
Incomplete

Follow-Up:
Provide evidence of remediation for
identified access exceptions.

Follow-Up Status:
Submitted
```

This creates a complete communication trail.

The auditor should avoid losing follow-up requests in email conversations or informal messages.

The GRC system or audit repository should retain the formal request and response history.

The evidence request list should also track **overdue requests**.

For example:

```text
Total Requests:
85

Received:
71

Under Review:
6

Additional Evidence Required:
4

Overdue:
4
```

Management may need visibility into overdue evidence, particularly when delays could affect the audit schedule.

A dashboard could show:

```text
Evidence Requests

Submitted:
84%

Under Review:
7%

Additional Evidence:
5%

Overdue:
4%
```

This allows the audit team to focus follow-up efforts.

The auditor should distinguish between a genuine evidence delay and a control owner failing to provide evidence because the control was not performed.

For example:

```text
Control Owner:
"The report is unavailable."

Auditor:
Determine whether the report was not retained
or whether the control was not performed.
```

This distinction can materially affect the audit conclusion.

An absence of evidence does not automatically prove that a control did not operate, but where evidence is required to demonstrate operation, the lack of evidence may itself represent a control or evidence-retention deficiency.

The evidence request list should also record **evidence exceptions**.

For example:

```text
Requirement:
Annual supplier security assessment.

Evidence:
Assessment report unavailable for
three suppliers.

Explanation:
Supplier assessments were not completed.

Result:
Potential control failure.
```

This is different from:

```text
Evidence:
Assessment completed but report was
temporarily inaccessible.

Result:
Evidence retrieval issue.
```

The auditor should investigate the reason for missing evidence.

The evidence request list can also support **third-party evidence**.

For example:

```text
Third Party:
Cloud Service Provider

Evidence:
Independent assurance report
Penetration testing summary
Security certification
Incident notification process
Business continuity testing
```

Third-party evidence should be evaluated for:

```text
Scope
Period
Independence
Coverage
Exceptions
Complementary User Entity Controls
```

For example, an assurance report may cover only certain services or locations.

The auditor should verify that the report actually covers the services relevant to the organization's audit.

The evidence request list should also support **regulatory evidence**.

For example:

```text
Requirement:
Regulatory Incident Reporting

Evidence:

Incident records
Notification records
Regulator communications
Internal escalation records
Incident timeline
Management approval
```

The evidence should demonstrate both the control and the outcome.

The same principle applies to compliance assessments.

For example:

```text
Requirement:
Data Subject Request Process

Evidence:

Privacy procedure
Request register
Sample requests
Response records
Escalation records
```

The evidence should demonstrate that the process exists and operates.

The evidence request list should also identify **evidence dependencies**.

For example:

```text
Evidence:
Cloud security configuration

Dependency:
Cloud provider access

Status:
Pending provider confirmation
```

Dependencies should be tracked so they do not become invisible causes of audit delays.

The evidence request process should also define **retention requirements**.

For example:

```text
Evidence:
Audit Workpaper

Retention:
7 Years
```

The actual retention period should follow the organization's legal, regulatory, contractual, and internal requirements.

The evidence repository should preserve the relationship between:

```text
Audit
 ↓
Request
 ↓
Evidence
 ↓
Test
 ↓
Finding
 ↓
Remediation
```

This creates an auditable record of how conclusions were reached.

The evidence request list should also support **evidence version control**.

For example:

```text
Evidence:
Security Policy

Version Submitted:
2.0

Effective Date:
1 January 2026

Superseded Version:
1.5
```

The auditor should ensure that the evidence being assessed was effective during the audit period.

For example:

```text
Audit Period:
January–June 2026

Policy Submitted:
Version 3.0

Effective Date:
August 2026

Conclusion:
Policy was not effective during the
audit period.
```

This prevents auditors from accidentally using future-state documentation as evidence of historical compliance.

The same principle applies to system configurations.

For example:

```text
Configuration Evidence:
Captured August 2026

Audit Period:
January–June 2026
```

The auditor should determine whether the current configuration can demonstrate the historical condition or whether historical evidence is required.

The evidence request list should also record **evidence limitations**.

For example:

```text
Limitation:

The system retains access review logs for
only six months.

Impact:

Evidence for January 2026 could not be
independently verified.
```

The auditor should evaluate whether the limitation affects the audit conclusion.

The evidence request process should also be integrated with the audit checklist.

For example:

```text
Audit Checklist Item:
Verify quarterly access review.

Evidence Request:
Q1 and Q2 access review reports.

Evidence Received:
EVD-001
EVD-002

Testing:
TEST-004

Result:
Effective
```

This provides end-to-end traceability.

The evidence request list should also connect to audit findings.

For example:

```text
Evidence Request
       ↓
Evidence Not Provided
       ↓
Control Testing
       ↓
Control Deficiency
       ↓
Audit Finding
       ↓
Corrective Action
```

This is particularly important when missing evidence indicates that the control may not have been operating or that evidence-retention requirements were not satisfied.

A mature evidence request process should also define **escalation**.

For example:

```text
Day 1:
Evidence Requested

Day 5:
Reminder

Day 7:
Follow-Up

Day 10:
Control Owner Escalation

Day 14:
Management Escalation
```

The actual timeline should depend on the organization's audit methodology and urgency.

High-risk evidence requests may require faster escalation.

The evidence request list should also identify the person responsible for each request.

For example:

```text
Request:
REQ-023

Evidence Owner:
IAM Manager

Auditor:
GRC Auditor

Reviewer:
Audit Manager
```

This creates accountability.

A practical evidence request record may look like:

```text
REQ-2026-023

Audit:
Enterprise Access Control Audit

Requirement:
Periodic access reviews

Control:
IAM-04

Evidence:
Q2 2026 privileged access review report

Purpose:
Verify quarterly review of privileged access.

Evidence Owner:
IAM Manager

Requested:
5 September 2026

Due:
10 September 2026

Submitted:
9 September 2026

Evidence Reference:
EVD-2026-045

Review Result:
Insufficient

Reason:
Cloud administrator accounts were not
included in the submitted population.

Follow-Up:
Provide complete privileged account population.

Status:
Additional Evidence Required
```

This provides a clear record from request to follow-up.

The evidence request list should also be used during the audit closeout.

Before the audit is finalized, the audit team should confirm:

```text
All Critical Evidence Received
All Evidence Reviewed
Outstanding Requests Identified
Evidence References Recorded
Evidence Limitations Documented
Findings Supported
Workpapers Complete
Retention Requirements Confirmed
```

A final evidence reconciliation may look like:

```text
Total Requests:
120

Received:
116

Accepted:
108

Additional Evidence:
6

Outstanding:
2
```

Any outstanding evidence should be evaluated before the final audit conclusion is issued.

The auditor should determine whether the missing evidence:

```text
Has No Material Impact
Requires Additional Testing
Creates an Evidence Gap
Creates a Control Finding
Limits the Audit Conclusion
```

The key principle is:

> **An Audit Evidence Request List provides a controlled method for identifying, requesting, receiving, evaluating, tracking, and retaining the evidence needed to support objective and defensible audit conclusions.**

**Part 4 – Audit Findings and Corrective Action Template**

An Audit Findings and Corrective Action Template is a structured tool used to document audit findings, communicate identified deficiencies, establish corrective actions, assign accountability, and track remediation through closure.

The purpose of the template is to ensure that every significant audit finding is supported by evidence, clearly explains the underlying issue, identifies the associated risk, and results in an actionable remediation plan.

The audit finding lifecycle can be represented as:

```text id="q4m6v2"
Audit Testing
      ↓
Evidence
      ↓
Condition Identified
      ↓
Finding Validation
      ↓
Root Cause Analysis
      ↓
Risk Assessment
      ↓
Finding Classification
      ↓
Management Response
      ↓
Corrective Action
      ↓
Owner and Target Date
      ↓
Remediation
      ↓
Validation
      ↓
Closure
```

A practical Audit Findings and Corrective Action Template can contain:

```text id="q5x9ka"
AUDIT FINDING AND CORRECTIVE ACTION TEMPLATE

Finding ID:

Audit ID:

Audit Name:

Finding Title:

Audit Area:

Requirement:

Control ID:

Control Description:

Audit Criteria:

Condition:

Expected Condition:

Finding Description:

Evidence:

Evidence Reference:

Root Cause:

Risk:

Business Impact:

Regulatory Impact:

Finding Classification:

Management Response:

Corrective Action:

Corrective Action Owner:

Supporting Teams:

Target Completion Date:

Priority:

Compensating Control:

Remediation Evidence:

Validation Method:

Validation Result:

Residual Risk:

Risk Acceptance:

Finding Status:

Closure Date:

Auditor:

Reviewer:

Management Approval:

Notes:
```

The first step is to define the **finding title**.

The title should communicate the issue clearly and concisely.

For example:

```text id="0e2k8d"
Weak:

Access Control Issue

Better:

Privileged Access Reviews Were Not Completed
for All In-Scope Accounts
```

A good title allows management to understand the issue without reading the entire finding.

The next step is to identify the **audit criteria**.

For example:

```text id="yrxkgi"
Audit Criteria:

ISO/IEC 27001:2022
Internal Access Control Policy
Privileged Access Standard
```

The criteria establish what the organization was expected to comply with.

The finding should then identify the **control** being assessed.

For example:

```text id="t2d0ms"
Control ID:
IAM-04

Control:
Quarterly Privileged Access Review
```

This provides traceability between the finding and the control environment.

The finding should clearly document the **condition**.

The condition describes what the auditor actually found.

For example:

```text id="7qf6in"
Condition:

Five of the 40 privileged accounts selected
for testing did not have documented evidence
of quarterly access review.
```

The condition should be factual and evidence-based.

The auditor should avoid subjective language such as:

> The access review process is poorly managed.

A stronger statement is:

> Five of the 40 sampled privileged accounts did not have documented evidence of quarterly review.

The second statement can be independently verified.

The finding should also document the **expected condition**.

For example:

```text id="x9jj48"
Expected Condition:

All privileged accounts should be reviewed
quarterly by authorized personnel, with
documented evidence of review and approval.
```

The finding can then clearly demonstrate the difference between:

```text id="n1otqu"
Expected Condition
        vs.
Actual Condition
```

This is the foundation of an audit finding.

The finding should then describe the **gap**.

For example:

```text id="2okg3v"
Gap:

The quarterly access review process does not
consistently provide documented evidence that
all privileged accounts have been reviewed.
```

The auditor should explain the issue without exaggerating its significance.

The finding should also reference the **supporting evidence**.

For example:

```text id="l0cqjb"
Evidence:

Q2 2026 Privileged Access Review Report
Sample Testing Results
IAM System Export
Access Review Approval Records

Evidence References:

EVD-2026-045
EVD-2026-046
EVD-2026-047
```

This makes the finding traceable to the audit workpapers.

A strong finding should be supported by sufficient evidence.

The auditor should be able to answer:

```text id="6v4x4b"
What was tested?

What evidence was reviewed?

What sample was selected?

What was found?

How does the evidence support the finding?
```

The finding should also identify the **root cause**.

For example:

```text id="t7j7s8"
Root Cause:

The IAM platform does not automatically
include newly created cloud administrator
accounts in the quarterly review population.
```

Root cause analysis is important because correcting only the immediate symptom may not prevent recurrence.

For example:

```text id="f1n4os"
Symptom:
Five accounts were not reviewed.

Weak Action:
Review the five accounts.

Root Cause:
Cloud administrator accounts are not
automatically included in the review process.

Better Action:
Integrate cloud administrator accounts into
the centralized privileged access review
workflow.
```

The second action addresses the underlying control weakness.

The finding should also assess the **risk**.

For example:

```text id="yd0q1b"
Risk:

Privileged accounts that are not periodically
reviewed may retain unnecessary or inappropriate
access, increasing the risk of unauthorized
system activity.
```

Risk should be based on the organization's approved risk methodology.

Factors may include:

```text id="e1k84u"
Likelihood
Impact
Data Sensitivity
System Criticality
Privilege Level
Regulatory Exposure
Business Impact
Customer Impact
```

The finding should also document the **business impact**.

For example:

```text id="2f5j6b"
Business Impact:

Inadequate review of privileged access may
increase the organization's exposure to
unauthorized changes to critical systems.
```

Where applicable, the finding should also document **regulatory impact**.

For example:

```text id="j1c4fy"
Regulatory Impact:

The control deficiency may affect the
organization's ability to demonstrate
compliance with applicable information
security and regulatory requirements.
```

The auditor should avoid making unsupported claims regarding fines, penalties, or enforcement outcomes.

Where legal interpretation is required, the matter should be referred to the appropriate legal or compliance function.

The finding should then receive a **classification**.

A typical classification model may include:

```text id="5h6gdz"
Critical
High
Medium
Low
Observation
Opportunity for Improvement
```

The organization should define clear criteria for each classification.

For example:

```text id="oyf11n"
Critical:

A severe control deficiency that could result
in significant security, operational, financial,
legal, or regulatory consequences.
```

Another example:

```text id="w4v4uj"
High:

A significant control weakness that could
materially increase organizational risk or
result in significant compliance exposure.
```

Classification should be based on evidence and risk rather than the auditor's personal judgment.

The finding should then be communicated to the relevant **control owner and management**.

The control owner should have the opportunity to validate the factual accuracy of the finding.

This does not mean that management determines the audit conclusion.

The auditor remains responsible for the audit assessment.

The management response should be documented.

For example:

```text id="y5m9u8"
Management Response:

Management agrees with the finding and will
implement centralized privileged access review
automation.
```

If management disagrees, the disagreement should also be documented.

For example:

```text id="zv0r5b"
Management Response:

Management partially agrees with the finding
and considers the existing compensating controls
sufficient to reduce the identified risk.
```

The auditor should evaluate the response and determine whether the audit conclusion needs to change.

The next step is to define the **corrective action**.

Corrective actions should be specific, measurable, and directly related to the root cause.

Weak corrective action:

> Improve privileged access management.

Better corrective action:

> Configure the IAM platform to automatically include all privileged cloud administrator accounts in quarterly access reviews and implement escalation for incomplete reviews.

The corrective action should explain what will actually change.

A strong corrective action should answer:

```text id="3c9m5f"
What will be changed?

Who will implement it?

When will it be completed?

What evidence will demonstrate completion?

How will effectiveness be validated?
```

The template should identify the **corrective action owner**.

For example:

```text id="qv6xgb"
Corrective Action Owner:
IAM Manager
```

Supporting teams may also be identified.

For example:

```text id="c3nyjy"
Supporting Teams:

Cloud Engineering
Security Operations
GRC
IT Operations
```

Accountability should remain clear even when multiple teams participate.

The corrective action should have a **target completion date**.

For example:

```text id="d5ifw7"
Target Completion Date:
31 December 2026
```

Target dates should consider:

```text id="q9n1rk"
Risk
Complexity
Resources
Dependencies
Regulatory Deadlines
Technology Changes
Business Priorities
```

High-risk findings may require shorter remediation periods.

The template should also identify the **priority**.

For example:

```text id="2g8hcb"
Priority:

Critical
High
Medium
Low
```

Priority and finding severity may be related but do not necessarily have to be identical.

The organization should define the relationship between the two.

The template should also identify **compensating controls** where applicable.

For example:

```text id="j7s8jp"
Finding:

Legacy application does not support MFA.

Compensating Controls:

Network segmentation
Privileged account restrictions
Enhanced monitoring
Additional approval requirements
```

Compensating controls should be formally evaluated rather than assumed to eliminate the risk.

The corrective action process should also require **remediation evidence**.

For example:

```text id="n1uxd3"
Remediation Evidence:

Updated IAM configuration
Updated access review workflow
System test results
Access review report
Implementation documentation
```

Evidence should demonstrate that the corrective action was actually implemented.

The audit team should then perform **validation testing**.

For example:

```text id="0qgxq1"
Corrective Action:
Automated privileged access review implemented.

Validation:

1. Review system configuration.
2. Generate privileged account population.
3. Verify inclusion of cloud administrator accounts.
4. Review workflow notifications.
5. Test approval process.
6. Review audit trail.
```

This provides assurance that the remediation addresses the original finding.

The auditor should distinguish between:

```text id="0q4b9h"
Remediation Implemented
        ≠
Control Effective
```

For example:

```text id="hks1q4"
Management:
"We implemented the new workflow."

Auditor:
Testing confirms that the workflow
successfully includes all privileged accounts
and generates the required approvals.

Conclusion:
Corrective action effective.
```

The finding should not be closed simply because management states that remediation is complete.

The auditor should verify the implementation.

The template should also document the **validation result**.

For example:

```text id="7h1v0r"
Validation Result:

Effective

The updated IAM workflow includes all
privileged accounts and successfully
completed testing for two consecutive
review cycles.
```

If remediation is incomplete:

```text id="m6cz9u"
Validation Result:

Partially Effective

The workflow has been implemented, but
two privileged account categories remain
outside the automated review population.
```

The finding should remain open until the defined closure criteria are satisfied.

The template should also capture **residual risk**.

For example:

```text id="r8n9j5"
Initial Risk:
High

Remediation:
Implemented

Residual Risk:
Low
```

Risk reduction should be demonstrated using the organization's risk methodology.

The organization should also consider whether any remaining risk requires formal acceptance.

For example:

```text id="6j4p5k"
Residual Risk:
Medium

Risk Owner:
CISO

Decision:
Risk Accepted until legacy system replacement.
```

Risk acceptance should follow the organization's formal approval process.

A risk acceptance does not automatically mean that an audit finding can be closed.

For example:

```text id="wq7m7b"
Audit Finding:
Legacy system does not support MFA.

Risk:
Accepted by authorized risk owner.

Finding Status:
Open

Reason:
Regulatory requirement remains applicable
and remediation is still required.
```

This distinction is important in regulated environments.

The finding template should also support **overdue corrective actions**.

For example:

```text id="t5k6m1"
Finding:
AUD-F-2026-008

Classification:
High

Target Date:
30 September 2026

Current Date:
15 October 2026

Status:
Overdue
```

The audit team should record the reason for the delay.

For example:

```text id="x4q2z7"
Delay Reason:

Application migration was delayed due to
technical dependency.

Revised Target:
31 December 2026

Management Approval:
Required
```

Repeated extensions should receive appropriate management scrutiny.

The audit team should also track **recurring findings**.

For example:

```text id="n4v7h9"
2024:
Incomplete access reviews

2025:
Incomplete access reviews

2026:
Incomplete access reviews
```

Recurring findings may indicate that previous corrective actions did not address the root cause.

The organization should therefore investigate why the issue continues to occur.

Possible causes include:

```text id="v6s4e0"
Incorrect Root Cause
Insufficient Remediation
Weak Ownership
Insufficient Resources
Poor Monitoring
Process Complexity
Technology Limitations
Management Decisions
```

A recurring finding may require escalation.

The template should also support **finding aging**.

For example:

```text id="a3k7w5"
Finding Age:

0–30 Days
31–60 Days
61–90 Days
91–180 Days
181+ Days
```

Management can use this information to identify remediation bottlenecks.

For example:

```text id="y4x2r8"
High-Risk Findings Older Than 90 Days:
4
```

This is often more meaningful than simply reporting the total number of findings.

The organization can also calculate the **average remediation time**.

For example:

```text id="v1z8k4"
Average High-Risk Finding Remediation:
68 Days

Average Medium-Risk Finding Remediation:
112 Days
```

These metrics can be included in GRC dashboards.

The finding template should also support **management reporting**.

For example:

```text id="f2g8s1"
Audit Findings

Critical:
1

High:
5

Medium:
14

Low:
9

Open:
17

Overdue:
4

Closed:
12
```

Management should also see trends.

For example:

```text id="q9p5m3"
Q1:
34 Open Findings

Q2:
27 Open Findings

Q3:
21 Open Findings

Q4:
17 Open Findings
```

Trend information helps determine whether the organization's control environment is improving.

However, a declining number of findings does not automatically mean that security or compliance has improved.

Management should consider:

```text id="y7v4p2"
Audit Coverage
Assessment Frequency
Risk Profile
Control Changes
Regulatory Changes
Business Changes
```

The template should also allow findings to be linked to **risk records**.

For example:

```text id="m8r3x6"
Audit Finding
      ↓
Risk Record
      ↓
Risk Assessment
      ↓
Treatment Plan
      ↓
Corrective Action
```

This creates integration between audit management and enterprise risk management.

The same finding may also be linked to multiple compliance requirements.

For example:

```text id="r4c8n2"
Finding:

Insufficient privileged access review

Mapped Requirements:

ISO 27001
NIS2
Internal Security Policy
Customer Security Requirement
```

One corrective action may therefore reduce exposure across several requirements.

The organization should verify that the corrective action addresses all applicable requirements.

The template can also be integrated with a GRC platform.

For example:

```text id="z5w1j7"
Audit
 ↓
Finding
 ↓
Risk
 ↓
Issue
 ↓
Corrective Action
 ↓
Task Assignment
 ↓
Evidence
 ↓
Validation
 ↓
Closure
```

Workflow automation can provide:

```text id="n2c6v4"
Automatic Notifications
Task Assignment
Due-Date Reminders
Escalation
Management Approval
Evidence Collection
Validation Workflow
Closure Approval
Dashboard Reporting
```

Automation can improve tracking, but professional judgment remains necessary when determining whether a finding has actually been remediated.

The finding should also have clear **closure criteria**.

For example:

```text id="k1s6v9"
Closure Criteria:

1. Root cause addressed.

2. Corrective action implemented.

3. Supporting evidence provided.

4. Control testing completed.

5. Control operates effectively.

6. Residual risk assessed.

7. Required management approval obtained.
```

The closure decision should be documented.

For example:

```text id="d7h4q2"
Finding:
AUD-F-2026-014

Status:
Closed

Closure Basis:

Corrective action implemented.
Validation testing completed.
Control operating effectively.
Residual risk reduced to acceptable level.
Closure approved by Lead Auditor.
```

A finding should not be closed simply because the target date has passed.

The status should reflect the actual remediation condition.

For example:

```text id="c5m9r1"
Target Date Passed:
Yes

Remediation Complete:
No

Finding Status:
Overdue
```

The audit team should maintain an accurate status.

A complete finding record may look like:

```text id="b6t2w8"
Finding ID:
AUD-F-2026-014

Title:
Privileged Access Reviews Were Not Completed
for All In-Scope Accounts.

Requirement:
Internal Privileged Access Standard

Control:
IAM-04 Quarterly Privileged Access Review

Condition:
5 of 40 sampled privileged accounts did not
have documented quarterly review evidence.

Expected Condition:
All privileged accounts must be reviewed
quarterly with documented approval.

Evidence:
Q2 2026 Access Review Report
IAM System Export
Sample Testing Results

Root Cause:
Cloud administrator accounts are not
automatically included in the review population.

Risk:
Unauthorized or unnecessary privileged
access may remain undetected.

Classification:
High

Management Response:
Management agrees.

Corrective Action:
Integrate cloud administrator accounts into
the centralized access review workflow.

Owner:
IAM Manager

Target Date:
31 December 2026

Validation:
Review configuration and test two complete
review cycles.

Status:
Open
```

After remediation:

```text id="w7p3q9"
Remediation Evidence:
Updated IAM workflow
Configuration Report
Q1 2027 Review Report
Q2 2027 Review Report

Validation:
Effective

Residual Risk:
Low

Finding Status:
Closed

Closure Date:
30 June 2027
```

A well-designed Audit Findings and Corrective Action Template ensures that audit findings are not treated simply as observations recorded in a report. It creates a controlled process that connects the identified condition to the requirement, risk, root cause, corrective action, accountable owner, remediation evidence, validation, and final closure.

The key principle is:

> **An Audit Findings and Corrective Action Template transforms audit findings into accountable remediation activities and ensures that identified deficiencies are supported by evidence, risk-assessed, assigned to responsible owners, validated after remediation, and formally closed.**



