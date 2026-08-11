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



