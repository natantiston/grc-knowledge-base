**17.6 NIST Cybersecurity Framework Tools and Templates**

### Part 1 – NIST CSF Current Profile Template

The **NIST Cybersecurity Framework (CSF) Current Profile** is a practical tool for documenting the organization's current cybersecurity posture. It provides a structured view of how the organization currently manages cybersecurity risks across the NIST CSF Functions, Categories, and Subcategories.

A Current Profile answers a fundamental GRC question:

> **Where are we today?**

Unlike a policy or procedure, the Current Profile is an assessment and management tool. It captures the organization's existing cybersecurity practices, controls, capabilities, and current level of implementation.

The basic relationship is:

```text
NIST CSF
    ↓
Functions
    ↓
Categories
    ↓
Subcategories
    ↓
Current Organizational Practices
    ↓
Evidence
    ↓
Current Profile
```

The five Functions in the original NIST CSF 1.1 were:

```text
Identify
Protect
Detect
Respond
Recover
```

With **NIST CSF 2.0**, the framework contains six Functions:

```text
Govern
Identify
Protect
Detect
Respond
Recover
```

For a current GRC program, the **NIST CSF 2.0 structure should be used** unless an organization has a documented reason to continue using an earlier CSF version.

The Current Profile should therefore provide visibility across the six CSF 2.0 Functions.

A practical Current Profile template can contain:

```text
NIST CSF CURRENT PROFILE

Organization:

Assessment Date:

Assessment Scope:

Business Unit:

Profile Owner:

Assessment Team:

NIST CSF Version:

Function:

Category:

Subcategory:

Current Practice:

Current Implementation Status:

Evidence:

Control / Process Owner:

Related Policy:

Related Control:

Risk Reference:

Current Maturity / Capability:

Identified Gap:

Comments:
```

The first step is defining the **scope** of the Current Profile.

For example:

```text
Assessment Scope:

Corporate IT environment
Cloud infrastructure
Corporate endpoints
Identity and access management
Security operations
Critical business applications
```

The scope should be clearly defined.

A Current Profile for an entire enterprise is different from a Current Profile covering only:

* A business unit.
* A cloud environment.
* A critical application.
* A data center.
* A regional operation.
* A specific business process.

The scope determines what the assessment results actually mean.

For example:

```text
Current Profile A:
Entire Enterprise

Current Profile B:
Cloud Environment Only
```

A weakness identified in Profile B should not automatically be interpreted as a weakness across the entire enterprise.

The assessment should also identify the **NIST CSF version**.

For example:

```text
Framework:
NIST Cybersecurity Framework

Version:
CSF 2.0

Assessment Date:
August 2026
```

This is important because the framework structure and terminology have evolved.

The Current Profile should then map the organization's existing practices to the relevant CSF outcomes.

For example:

```text
NIST CSF Function:
Protect

Category:
Identity Management, Authentication,
and Access Control

Current Practice:
MFA is required for privileged accounts.

Evidence:
IAM configuration report
MFA compliance report
```

The Current Profile should describe the **actual current state**, rather than the desired future state.

For example:

**Current State:**

> MFA is implemented for privileged accounts but is not yet enforced for all standard user accounts.

This is different from:

> MFA will be implemented for all users.

The second statement describes a target state rather than a current state.

This distinction becomes particularly important in **17.6 Part 2**, where the Target Profile will be developed.

A practical Current Profile may use implementation ratings.

For example:

| Rating                | Meaning                                        |
| --------------------- | ---------------------------------------------- |
| Not Implemented       | Practice does not currently exist              |
| Initial               | Practice exists inconsistently                 |
| Partially Implemented | Practice covers some of the required scope     |
| Implemented           | Practice is broadly implemented                |
| Managed               | Practice is monitored and consistently managed |
| Optimized             | Practice is continuously improved              |

The organization should define the exact meaning of its rating system before using it.

The rating should also be supported by evidence.

For example:

```text
Current Practice:
Quarterly privileged access reviews

Implementation:
Partially Implemented

Evidence:
Q2 2026 access review

Finding:
Legacy applications are not included.

Rating:
Partially Implemented
```

This is more defensible than assigning a rating without supporting evidence.

The Current Profile can also use a simpler status model:

```text
Not Implemented
Partially Implemented
Implemented
Not Applicable
Unknown
```

This may be preferable when the organization does not yet have a mature capability-maturity model.

The key is **consistency**.

The same criteria should be applied across the assessment.

A Current Profile should also identify the **control or process supporting the CSF outcome**.

For example:

| NIST CSF Area            | Organizational Control           |
| ------------------------ | -------------------------------- |
| Identity Management      | IAM Process                      |
| Asset Management         | Asset Inventory Process          |
| Vulnerability Management | Vulnerability Management Process |
| Incident Response        | Incident Response Plan           |
| Recovery                 | Disaster Recovery Process        |
| Security Awareness       | Security Awareness Program       |

This connects the framework to actual organizational processes.

The mapping can be represented as:

```text
NIST CSF Outcome
       ↓
Organizational Process
       ↓
Internal Control
       ↓
Evidence
       ↓
Current Assessment
```

This prevents the Current Profile from becoming an abstract framework exercise.

For example:

```text
NIST CSF:
Protect

Organizational Process:
Security Awareness

Internal Control:
Annual Security Awareness Training

Current State:
Annual training is provided to employees.
Contractors are not consistently included.

Evidence:
2026 Training Completion Report

Gap:
Contractor coverage
```

The Current Profile should also record **control ownership**.

For example:

| Capability               | Owner                      |
| ------------------------ | -------------------------- |
| Asset Management         | IT Asset Manager           |
| Identity Management      | IAM Manager                |
| Vulnerability Management | Security Operations        |
| Incident Response        | SOC Manager                |
| Business Continuity      | BCM Manager                |
| Security Awareness       | Security Awareness Manager |

Ownership is important because identified gaps eventually need to be assigned to responsible individuals or teams.

The Current Profile can also incorporate **risk references**.

For example:

```text
NIST CSF:
Protect – Access Control

Risk:
R-014 Unauthorized Privileged Access

Current State:
PAM implemented for 70% of privileged accounts.

Gap:
30% of privileged accounts remain outside PAM.

Risk Rating:
High
```

This connects NIST CSF assessment activities to the organization's broader GRC risk management process.

A strong Current Profile therefore does not merely say:

> Partially implemented.

It explains **why**.

For example:

```text
Current Status:
Partially Implemented

Reason:
Centralized vulnerability scanning covers
corporate endpoints and servers but does not
yet cover several cloud workloads.

Evidence:
Vulnerability Management Report – Q2 2026

Risk:
R-023 – Undetected Vulnerabilities

Owner:
Security Operations Manager
```

The Current Profile should also capture **evidence references**.

Examples include:

* Policies.
* Procedures.
* Security reports.
* System configurations.
* Audit reports.
* Risk assessments.
* Vulnerability reports.
* Incident records.
* Training records.
* Access reviews.
* Recovery tests.
* Monitoring reports.

For example:

```text
Evidence ID:
EV-2026-035

Evidence:
Q2 Vulnerability Management Report

Related CSF:
Protect / Vulnerability Management

Owner:
Security Operations
```

This creates auditability.

The Current Profile can also be maintained in a spreadsheet.

A practical table could look like:

| Function | Category               | Current Practice            | Status      | Evidence    | Owner | Gap                |
| -------- | ---------------------- | --------------------------- | ----------- | ----------- | ----- | ------------------ |
| Govern   | Organizational Context | Cybersecurity roles defined | Implemented | Org Chart   | CISO  | None               |
| Identify | Asset Management       | Asset inventory maintained  | Partial     | CMDB Report | IT    | Cloud assets       |
| Protect  | Access Control         | MFA for privileged users    | Partial     | IAM Report  | IAM   | Standard users     |
| Detect   | Continuous Monitoring  | SIEM monitoring             | Implemented | SIEM Report | SOC   | None               |
| Respond  | Incident Management    | IR process established      | Implemented | IR Plan     | SOC   | Exercise frequency |
| Recover  | Recovery Planning      | DR plans exist              | Partial     | DR Plan     | BCM   | Testing coverage   |

This table provides management with a quick view of the current cybersecurity posture.

The Current Profile can also be represented visually.

For example:

```text
Govern       ████████░░
Identify     ██████░░░░
Protect      ███████░░░
Detect       ████████░░
Respond      ██████░░░░
Recover      █████░░░░░
```

The exact scoring methodology should be documented rather than relying on arbitrary percentages.

A GRC team should also be careful when calculating an overall score.

Cybersecurity capability is multidimensional.

A single score can hide important weaknesses.

For example:

> Overall score: 82%

may look positive even though:

> Privileged access management has a critical gap.

Therefore, the Current Profile should retain the detailed findings behind any summary score.

The Current Profile should also distinguish between **documented capability** and **operational capability**.

For example:

```text
Policy:
Documented

Procedure:
Documented

Implementation:
Partial

Evidence:
Available

Operational Effectiveness:
Partial
```

This provides a more realistic view of cybersecurity maturity.

A Current Profile can also include **assessment comments**.

For example:

> The organization has a documented incident response process and designated incident response roles. However, the process has not been exercised across all critical business units during the assessment period.

This provides useful context for management.

The assessment should also identify **not applicable** outcomes where appropriate.

However, the organization should provide a justification.

For example:

```text
Status:
Not Applicable

Justification:
The assessed business unit does not operate
industrial control systems within the defined scope.
```

The organization should avoid using "Not Applicable" simply to remove difficult requirements from the assessment.

The decision should be documented and defensible.

The Current Profile should also be reviewed when there are significant changes.

Triggers may include:

* New technologies.
* New business services.
* Cloud migration.
* Major security incidents.
* New regulatory requirements.
* Organizational restructuring.
* New suppliers.
* New critical assets.
* Changes in cybersecurity strategy.
* Significant changes to the threat environment.

For example:

```text
Cloud Migration
      ↓
New Assets
      ↓
New Risks
      ↓
Current Profile Update
      ↓
Gap Identification
```

The Current Profile should therefore be treated as a **living assessment**.

It should not be created once and then left unchanged for several years.

The GRC team should establish a review frequency.

For example:

```text
Formal Assessment:
Annually

Focused Review:
Quarterly

Event-Based Review:
After Significant Changes
```

The exact frequency should depend on organizational risk, regulatory requirements, business complexity, and the organization's cybersecurity governance model.

A practical Current Profile workflow is:

```text
1. Define Scope
        ↓
2. Select NIST CSF Version
        ↓
3. Identify Relevant CSF Outcomes
        ↓
4. Identify Existing Practices
        ↓
5. Collect Evidence
        ↓
6. Assess Current Implementation
        ↓
7. Identify Gaps
        ↓
8. Link Gaps to Risks
        ↓
9. Assign Owners
        ↓
10. Document Current Profile
```

The Current Profile should eventually provide the foundation for developing the **Target Profile**.

The relationship is:

```text
Current Profile
      ↓
Where Are We Today?
      ↓
Gap Analysis
      ↓
Target Profile
      ↓
Where Do We Want To Be?
```

For example:

```text
Current:
MFA covers 70% of privileged accounts.

Target:
MFA covers 100% of privileged accounts.

Gap:
30% coverage gap.

Action:
Extend MFA to remaining privileged accounts.

Owner:
IAM Manager.

Target Date:
31 December 2026.
```

This transforms the framework from a descriptive assessment into a practical improvement program.

For a practical exercise, assume an organization has the following current capabilities:

```text
Asset Management:
Corporate assets are inventoried.
Cloud assets are only partially inventoried.

Identity Management:
MFA is implemented for privileged users.
Standard user MFA is not yet universal.

Vulnerability Management:
Monthly vulnerability scanning is performed.
Several cloud workloads are excluded.

Incident Response:
An incident response plan exists.
The plan has not been tested during the current year.

Recovery:
Critical systems have recovery procedures.
Full recovery exercises are performed annually.
```

Create a **NIST CSF Current Profile** containing:

```text
Function
Category
Current Practice
Implementation Status
Evidence
Control Owner
Risk Reference
Current Gap
Comments
```

Then identify the three most significant gaps.

For example:

```text
Gap 1:
Incomplete cloud asset visibility

Gap 2:
Incomplete MFA coverage

Gap 3:
Incomplete vulnerability scanning coverage
```

Rank the gaps using the organization's risk criteria rather than simply choosing the gaps that appear technically interesting.

The final objective is to produce a Current Profile that management can actually use.

A good Current Profile should allow a CISO, GRC manager, risk owner, or executive to answer:

```text
What cybersecurity capabilities currently exist?

Which capabilities are fully implemented?

Which capabilities are only partially implemented?

Where are the major weaknesses?

What evidence supports the assessment?

Which risks are associated with the weaknesses?

Who owns the gaps?

What should be improved?
```

The key principle is:

> **The NIST CSF Current Profile provides an evidence-based picture of the organization's present cybersecurity posture and establishes the baseline from which future cybersecurity improvements can be planned.**

Part 2 builds directly on the Current Profile. The **Target Profile** defines the cybersecurity outcomes and capabilities the organization intends to achieve.

A Target Profile answers a different question:

> **Where do we want to be?**

The Current Profile describes the existing state, while the Target Profile describes the desired future state.

The relationship is:

```text
Current Profile
      ↓
Current State
      ↓
Risk and Business Requirements
      ↓
Target Profile
      ↓
Desired Future State
```

The Target Profile should not simply represent the highest possible cybersecurity maturity. It should represent a **realistic and risk-based target state** that supports the organization's business objectives, risk appetite, regulatory obligations, and available resources.

A practical **NIST CSF Target Profile Template** can contain:

```text id="3r7vqm"
NIST CSF TARGET PROFILE

Organization:

Assessment Scope:

Profile Owner:

NIST CSF Version:

Target Date:

Business Objective:

Risk Considerations:

Function:

Category:

Subcategory:

Target Cybersecurity Outcome:

Target Practice:

Target Implementation Status:

Required Capability:

Required Control:

Required Evidence:

Control Owner:

Priority:

Target Risk Level:

Gap Reference:

Implementation Dependency:

Target Completion Date:

Comments:
```

The first step is defining the **business context** for the target state.

For example:

```text id="2z8mks"
Business Objective:

Protect customer information while
expanding cloud-based services.

Risk Considerations:

Data exposure
Unauthorized access
Cloud misconfiguration
Third-party risk
Service availability
```

This is important because the target cybersecurity state should support business objectives.

A financial institution may require stronger controls around financial transactions.

A healthcare organization may place greater emphasis on privacy and availability.

A software company may place greater emphasis on cloud security, application security, and intellectual property protection.

The Target Profile should therefore be organization-specific.

The Target Profile should use the relevant **NIST CSF 2.0 Functions**:

```text id="1v5c8z"
Govern
Identify
Protect
Detect
Respond
Recover
```

Each Function can then be used to define desired future capabilities.

For example:

```text id="n7w4pj"
Current:

Asset inventory covers 80% of corporate assets.

Target:

100% of in-scope corporate and cloud assets
are identified and maintained in the organization's
asset inventory.
```

The target statement should be measurable whenever possible.

Instead of:

> Improve asset management.

Use:

> Maintain an authoritative inventory covering 100% of in-scope assets, with ownership and classification recorded.

This gives the organization something that can be assessed later.

The Target Profile should also define the **desired control capability**.

For example:

```text id="7j8m2q"
Current:
MFA implemented for privileged users.

Target:
MFA required for all users accessing
in-scope corporate and cloud systems.
```

The target can then be connected to a control:

```text id="f6p9wr"
NIST CSF Outcome
      ↓
Target Capability
      ↓
Internal Control
      ↓
Implementation Requirement
      ↓
Evidence
```

This makes the Target Profile operational.

A useful Target Profile table could look like:

| Function | Category               | Current State     | Target State                             | Priority | Owner |
| -------- | ---------------------- | ----------------- | ---------------------------------------- | -------- | ----- |
| Govern   | Cybersecurity Strategy | Strategy exists   | Strategy integrated with enterprise risk | High     | CISO  |
| Identify | Asset Management       | Partial inventory | Complete asset inventory                 | High     | IT    |
| Protect  | Access Control         | MFA partial       | MFA universal                            | Critical | IAM   |
| Detect   | Monitoring             | SIEM implemented  | Full critical asset coverage             | High     | SOC   |
| Respond  | Incident Management    | Plan exists       | Annual enterprise exercise               | Medium   | SOC   |
| Recover  | Recovery Planning      | Annual testing    | Critical systems tested regularly        | High     | BCM   |

The Target Profile should distinguish between **desired capability** and **implementation deadline**.

For example:

```text id="u0g9x5"
Target Capability:
100% MFA coverage

Target Date:
31 December 2026
```

This allows the organization to measure progress.

The target date should be realistic.

A target such as:

> Implement enterprise-wide zero trust within 30 days.

may not be realistic for a large organization.

The GRC team should consider:

* Budget.
* Staffing.
* Technology dependencies.
* Business impact.
* Procurement timelines.
* Regulatory deadlines.
* Existing projects.
* Organizational change capacity.

The Target Profile should therefore be aligned with the organization's implementation roadmap.

The Target Profile should also consider **risk appetite**.

For example:

```text id="l6t8mw"
Risk Appetite:
Low tolerance for unauthorized access
to customer information.

Target:
100% MFA for privileged and remote access.

Target Risk:
Low.
```

For a less critical system, the organization may accept a different target.

The target state should therefore be driven by risk rather than by arbitrary maturity goals.

The GRC professional should also distinguish between **target outcomes** and **specific technologies**.

For example:

Weak target:

> Deploy Vendor X security platform.

Stronger target:

> Establish centralized security monitoring capable of detecting and alerting on significant security events across all critical systems.

The second statement describes the desired capability rather than prematurely selecting a vendor or technology.

Technology can be selected later based on requirements.

This is particularly important in GRC because the framework should remain technology-neutral.

The Target Profile can also define the required **evidence**.

For example:

```text id="6f3m9q"
Target Outcome:
Continuous monitoring of critical systems

Target Evidence:
SIEM coverage report
Monitoring coverage dashboard
Alerting configuration
Incident records
Monthly monitoring review
```

This allows the organization to determine how it will prove that the target capability has been achieved.

The Target Profile should also identify **control ownership**.

For example:

| Target Capability           | Owner                     |
| --------------------------- | ------------------------- |
| Enterprise Asset Inventory  | IT Asset Manager          |
| MFA Coverage                | IAM Manager               |
| Vulnerability Management    | Security Operations       |
| Security Monitoring         | SOC Manager               |
| Incident Response Exercises | Incident Response Manager |
| Recovery Testing            | BCM Manager               |

Clear ownership is necessary for implementation.

The Target Profile can also include **priority**.

A practical priority model could be:

```text
Critical
High
Medium
Low
```

However, priority should be based on factors such as:

* Risk reduction.
* Regulatory requirements.
* Business criticality.
* Threat exposure.
* Customer requirements.
* Dependency on other initiatives.
* Implementation complexity.

For example:

```text id="5z1q7p"
Target:
100% MFA coverage

Risk:
Unauthorized access

Priority:
Critical

Reason:
High-risk privileged access exposure.
```

Another target may be:

```text id="m8v3cy"
Target:
Improve security awareness reporting

Priority:
Medium

Reason:
Useful improvement but lower immediate
risk reduction than privileged access controls.
```

The Target Profile should also capture **dependencies**.

For example:

```text id="b5q7mx"
Target:
Centralized cloud asset inventory

Dependencies:
Cloud discovery capability
CMDB integration
Cloud account ownership
Tagging standards
Application owner data
```

This is important because some target outcomes cannot be achieved independently.

For example:

```text id="j6n9wr"
Complete Asset Inventory
        ↓
Requires CMDB Integration
        ↓
Requires Cloud Discovery
        ↓
Requires Cloud Account Governance
```

The GRC team should document these dependencies so that the target state is achievable.

The Target Profile can also be linked to strategic initiatives.

For example:

```text id="x4m8qz"
Target:
Improve cloud security visibility

Related Initiative:
Cloud Security Program

Project:
Cloud Security Posture Management

Owner:
Cloud Security Manager

Target:
Q2 2027
```

This creates a direct relationship between framework outcomes and GRC projects.

The Target Profile should also consider **regulatory and contractual requirements**.

For example:

```text id="k3p6vn"
Target:
Implement stronger supplier security controls

Drivers:
NIS2
Customer Contracts
Internal Risk Appetite
Enterprise Security Strategy
```

The organization may therefore have several reasons for establishing the same target.

This can be represented as:

```text id="v8x2mq"
Business Requirement
        +
Risk Requirement
        +
Regulatory Requirement
        +
Customer Requirement
        ↓
Target Cybersecurity Capability
```

This makes the Target Profile more strategically useful.

The Target Profile should not necessarily include every NIST CSF outcome.

The organization can prioritize the outcomes most relevant to its:

* Business model.
* Risk environment.
* ISMS scope.
* Regulatory obligations.
* Technology environment.
* Strategic objectives.

However, the organization should document its methodology for determining what is included or excluded.

The Target Profile can also be created at different organizational levels.

For example:

```text id="t5k7wp"
Enterprise Target Profile
        ↓
Business Unit Target Profile
        ↓
Technology Target Profile
        ↓
Project Target Profile
```

For example, a cloud migration project could have its own Target Profile focused on:

* Cloud identity.
* Cloud asset inventory.
* Logging.
* Encryption.
* Vulnerability management.
* Incident response.
* Recovery.

This allows the NIST CSF to be applied flexibly.

A Target Profile should also be **time-bound**.

For example:

```text id="r9q4mc"
Target Profile:

Baseline:
August 2026

Target State:
December 2027
```

The organization can then monitor progress between the two states.

This creates the foundation for the gap assessment covered in Part 3.

The relationship is:

```text id="x6p8vn"
Current Profile
      ↓
Target Profile
      ↓
Gap Assessment
      ↓
Prioritization
      ↓
Implementation Roadmap
```

For example:

```text id="n2m5qx"
Current:
MFA = 70%

Target:
MFA = 100%

Gap:
30%

Priority:
Critical

Action:
Extend MFA coverage

Owner:
IAM Manager

Target:
December 2026
```

The Target Profile should also describe the **expected risk outcome**.

For example:

```text id="p4v7mz"
Current Risk:
High

Target Capability:
Centralized privileged access management

Expected Residual Risk:
Medium
```

This allows management to understand why the target matters.

A cybersecurity improvement should ideally answer:

> What risk will this investment reduce?

For example:

> Implementing centralized privileged access management is expected to reduce the likelihood of unauthorized privileged access and improve monitoring of administrative activity.

This is much more meaningful than:

> Implement PAM because NIST recommends it.

The Target Profile can also include a **success criterion**.

For example:

```text id="q8m3rx"
Target:
100% MFA coverage

Success Criteria:
All in-scope user accounts require MFA,
with exceptions formally documented and approved.
```

Another example:

```text id="w5k9pv"
Target:
Complete asset visibility

Success Criteria:
100% of in-scope production assets have:
- Asset owner
- Business classification
- System classification
- Criticality
- Location
- Lifecycle status
```

Success criteria make the target measurable.

The Target Profile should also consider **exceptions**.

For example:

```text id="g7x2mq"
Target:
100% MFA

Exception:
Legacy application cannot support MFA.

Compensating Controls:
Network restriction
Privileged access limitation
Enhanced monitoring

Exception Owner:
Application Owner

Expiration:
31 December 2026
```

This allows the organization to maintain a high target while formally managing unavoidable exceptions.

The Target Profile can also be maintained in a spreadsheet.

A practical structure is:

| CSF Function | Category            | Target Outcome                             | Target Capability                | Priority | Owner | Target Date |
| ------------ | ------------------- | ------------------------------------------ | -------------------------------- | -------- | ----- | ----------- |
| Govern       | Strategy            | Cybersecurity aligned with enterprise risk | Formal cyber risk reporting      | High     | CISO  | Q4 2026     |
| Identify     | Asset Management    | Complete asset visibility                  | Centralized inventory            | Critical | IT    | Q1 2027     |
| Protect      | Access Control      | Strong authentication                      | Universal MFA                    | Critical | IAM   | Q4 2026     |
| Detect       | Monitoring          | Timely threat detection                    | Expanded SIEM coverage           | High     | SOC   | Q2 2027     |
| Respond      | Incident Management | Tested response capability                 | Enterprise IR exercise           | Medium   | SOC   | Q1 2027     |
| Recover      | Recovery Planning   | Reliable recovery                          | Critical-system recovery testing | High     | BCM   | Q2 2027     |

The Target Profile should be reviewed periodically.

Changes may be required because of:

* New business objectives.
* New threats.
* New regulations.
* Major incidents.
* Technology changes.
* Budget changes.
* Changes to risk appetite.
* Changes in organizational strategy.
* Completed improvement initiatives.

For example:

```text id="z6q4mx"
New Regulation
      ↓
New Requirement
      ↓
Risk Assessment
      ↓
Target Profile Updated
      ↓
Roadmap Updated
```

This makes the Target Profile a living strategic document.

For a practical exercise, use the following Current Profile:

```text id="p7m3qv"
Asset Management:
80% coverage

MFA:
70% coverage

Vulnerability Management:
80% of systems scanned

Security Monitoring:
Critical servers monitored

Incident Response:
Plan exists but exercise incomplete

Recovery:
Annual recovery test
```

Develop a Target Profile with the following objectives:

```text id="c5x8nm"
Asset Management:
100% coverage

MFA:
100% coverage for in-scope users

Vulnerability Management:
100% coverage of critical systems

Security Monitoring:
All critical systems monitored

Incident Response:
Annual enterprise-wide exercise

Recovery:
Critical systems tested against defined
recovery objectives
```

For each target, document:

```text id="m8q2vr"
NIST CSF Function
Category
Current State
Target State
Business Driver
Risk Driver
Required Capability
Priority
Owner
Target Date
Success Criteria
Evidence
Dependencies
```

Then determine which targets should receive the highest priority.

For example:

```text id="y4p7mc"
Target:
100% MFA

Risk:
Unauthorized access

Priority:
Critical
```

The important point is that priority should be justified through business and risk considerations.

The Target Profile should ultimately allow management to answer:

```text id="k9m3qx"
What cybersecurity capabilities do we want?

Why do we need them?

Which risks will they address?

What will the future state look like?

Who owns each capability?

When should it be achieved?

How will success be measured?

What evidence will demonstrate achievement?
```

The Target Profile then becomes the foundation for the next stage:

```text id="v6x8mq"
Current Profile
      +
Target Profile
      ↓
Current-State vs Target-State Gap Assessment
```

The key principle is:

> **The NIST CSF Target Profile defines a realistic, risk-based future cybersecurity state that the organization intends to achieve and provides measurable objectives for improving its cybersecurity capabilities.**
> :::

**17.6 NIST Cybersecurity Framework Tools and Templates**

When the Current Profile and Target Profile have been completed, the organization can compare them to determine what needs to change.

This is the purpose of the **Current-State vs Target-State Gap Assessment**.

The basic concept is:

```text
Current State
      ↓
Compare
      ↓
Target State
      ↓
Identify Gaps
      ↓
Assess Risk
      ↓
Prioritize
      ↓
Define Actions
```

A gap does not necessarily mean that the organization has completely failed to meet a cybersecurity requirement. A gap can represent:

* A missing capability.
* A partially implemented capability.
* An ineffective control.
* Insufficient coverage.
* Inconsistent implementation.
* Missing evidence.
* Lack of ownership.
* Outdated processes.
* A capability that exists but does not meet the organization's target.

A practical **NIST CSF Gap Assessment Template** can contain:

```text
NIST CSF GAP ASSESSMENT

Gap ID:

NIST CSF Version:

Function:

Category:

Subcategory:

Current State:

Target State:

Gap Description:

Gap Type:

Risk Reference:

Risk Rating:

Business Impact:

Regulatory Impact:

Priority:

Recommended Action:

Action Owner:

Dependencies:

Target Completion Date:

Required Resources:

Success Criteria:

Evidence Required:

Status:

Comments:
```

The first step is to compare the Current Profile with the Target Profile.

For example:

| Capability               | Current State    | Target State                       | Gap                |
| ------------------------ | ---------------- | ---------------------------------- | ------------------ |
| Asset Management         | 80% coverage     | 100% coverage                      | 20% coverage gap   |
| MFA                      | 70% coverage     | 100% coverage                      | 30% coverage gap   |
| Vulnerability Management | 80% scanned      | 100% critical systems              | 20% coverage gap   |
| Security Monitoring      | Critical servers | All critical systems               | Cloud coverage gap |
| Incident Response        | Plan exists      | Annual enterprise exercise         | Testing gap        |
| Recovery                 | Annual testing   | Defined recovery objectives tested | Validation gap     |

The assessment should describe the gap clearly.

A weak statement would be:

> MFA needs improvement.

A stronger statement would be:

> MFA is implemented for approximately 70% of in-scope users. The remaining user population, including several remote-access accounts, does not currently use MFA.

The second statement provides a clear basis for remediation.

The GRC professional should also identify the **type of gap**.

A useful classification is:

```text
Capability Gap
Control Gap
Process Gap
Technology Gap
People / Skills Gap
Evidence Gap
Governance Gap
Compliance Gap
```

For example:

```text
Gap:
No formal third-party cybersecurity assessment process.

Gap Type:
Process / Governance
```

Another example:

```text
Gap:
SIEM does not receive logs from several
critical cloud workloads.

Gap Type:
Technology / Coverage
```

Another:

```text
Gap:
Access review is performed but evidence
is not consistently retained.

Gap Type:
Evidence / Process
```

This classification helps determine the appropriate treatment.

The assessment should also determine whether the gap represents a **risk**.

For example:

```text
Gap:
30% of users do not have MFA.

Potential Risk:
Unauthorized account access.

Risk:
High.
```

The gap assessment should therefore connect to the organization's risk register.

The relationship is:

```text
NIST CSF Gap
      ↓
Risk Scenario
      ↓
Risk Assessment
      ↓
Risk Rating
      ↓
Treatment Priority
```

This prevents the GRC team from treating every gap as equally important.

For example:

```text
Gap A:
30% of privileged accounts lack MFA.

Risk:
Critical

Gap B:
Security awareness dashboard lacks
one additional reporting metric.

Risk:
Low
```

Both are gaps, but they should not receive the same priority.

The organization should define a **gap prioritization methodology**.

For example:

| Priority | Description                                                |
| -------- | ---------------------------------------------------------- |
| Critical | Significant risk or urgent regulatory/business requirement |
| High     | Material cybersecurity risk requiring planned action       |
| Medium   | Meaningful improvement needed                              |
| Low      | Minor improvement or optimization                          |

The organization can also use numerical scoring.

For example:

```text
Priority Score =
Risk Impact × Likelihood × Business Criticality
```

The exact calculation should follow the organization's approved methodology.

A gap assessment table might therefore look like:

| Gap                     | Risk                 | Impact | Likelihood | Priority |
| ----------------------- | -------------------- | -----: | ---------: | -------- |
| Privileged MFA coverage | Unauthorized access  |      5 |          4 | Critical |
| Cloud asset inventory   | Unknown assets       |      4 |          4 | High     |
| SIEM cloud coverage     | Delayed detection    |      5 |          3 | High     |
| IR exercise             | Response readiness   |      4 |          3 | Medium   |
| Dashboard enhancement   | Reporting limitation |      2 |          2 | Low      |

The GRC team should also consider **regulatory requirements**.

A gap may receive a higher priority if it affects a mandatory requirement.

For example:

```text
Gap:
Insufficient incident reporting process

Risk:
Operational / Regulatory

Regulatory Driver:
Applicable cybersecurity regulation

Priority:
High
```

This means gap prioritization should consider more than technical risk.

A useful model is:

```text
Cybersecurity Risk
       +
Regulatory Requirement
       +
Business Criticality
       +
Customer Requirement
       +
Implementation Complexity
       ↓
Gap Priority
```

The gap assessment should then identify the recommended action.

For example:

```text
Gap:
MFA coverage = 70%

Target:
MFA coverage = 100%

Recommended Action:
Extend MFA enrollment to all remaining
in-scope users and formally document
approved exceptions.
```

The action should be specific enough to become a project or remediation task.

Avoid vague actions such as:

> Improve authentication.

Instead:

> Deploy MFA to all remaining in-scope user accounts and implement an exception approval process for systems that cannot technically support MFA.

The GRC team should also identify the **gap owner**.

For example:

| Gap                    | Owner                     |
| ---------------------- | ------------------------- |
| Asset inventory        | IT Asset Manager          |
| MFA coverage           | IAM Manager               |
| Vulnerability scanning | Security Operations       |
| SIEM coverage          | SOC Manager               |
| IR exercise            | Incident Response Manager |
| Recovery testing       | BCM Manager               |

Ownership is critical because a gap without an accountable owner is unlikely to be resolved.

The assessment should also include a **target completion date**.

For example:

```text
Gap:
Incomplete MFA coverage

Owner:
IAM Manager

Target:
31 December 2026
```

The date should be aligned with risk and organizational priorities.

Critical gaps should generally receive more urgent attention than low-risk improvements.

The assessment should also identify **dependencies**.

For example:

```text
Gap:
Complete cloud asset inventory

Dependencies:
Cloud account discovery
CMDB integration
Asset ownership
Cloud tagging standards
```

A gap may therefore require several supporting activities before it can be closed.

The relationship might be:

```text
Cloud Discovery
       ↓
Asset Identification
       ↓
CMDB Integration
       ↓
Asset Ownership
       ↓
Complete Asset Inventory
```

The GRC professional should identify these dependencies before assigning unrealistic deadlines.

The gap assessment should also define **success criteria**.

For example:

```text
Gap:
Incomplete MFA coverage

Success Criteria:
100% of in-scope user accounts use MFA,
except formally approved and documented
exceptions.
```

This provides an objective definition of closure.

Another example:

```text
Gap:
Incomplete vulnerability scanning

Success Criteria:
100% of critical production systems are
included in authenticated vulnerability
scanning at the required frequency.
```

This is much stronger than:

> Vulnerability management improved.

The gap should only be considered closed when the success criteria have been met and appropriate evidence exists.

A useful closure model is:

```text
Gap Identified
      ↓
Remediation Planned
      ↓
Remediation Implemented
      ↓
Evidence Collected
      ↓
Validation Performed
      ↓
Gap Closed
```

The **validation step** is important.

For example:

> The IAM team reports that MFA has been deployed.

The GRC team should verify the claim using appropriate evidence.

For example:

```text
IAM Report
     +
MFA Configuration
     +
User Coverage Report
     +
Exception Register
     ↓
Validation
```

If the evidence shows that only 94% of users have MFA, the gap has not yet reached the target of 100%.

The assessment should therefore distinguish between:

```text
Remediation Reported
```

and:

```text
Remediation Validated
```

This is an important GRC control.

The gap assessment can also use a simple maturity comparison.

For example:

| Capability               | Current | Target | Gap |
| ------------------------ | ------: | -----: | --: |
| Asset Management         |       3 |      5 |   2 |
| Access Management        |       3 |      5 |   2 |
| Vulnerability Management |       4 |      5 |   1 |
| Monitoring               |       3 |      5 |   2 |
| Incident Response        |       3 |      4 |   1 |
| Recovery                 |       3 |      5 |   2 |

However, numerical maturity scores should not replace detailed analysis.

A score of 3 does not explain what is missing.

The GRC professional should always retain the underlying assessment information.

The gap assessment can also be visualized as a heat map.

```text
             Target State
                  ↑
                  │
Current State ────┼────→ Improvement
                  │
                  ↓
             Risk Exposure
```

A more practical representation is:

```text
MFA
Current: 70%
Target: 100%
Gap: 30%
Risk: High
Priority: Critical
```

```text
Asset Inventory
Current: 80%
Target: 100%
Gap: 20%
Risk: High
Priority: High
```

```text
Incident Response
Current: Plan exists
Target: Tested annually
Gap: Exercise capability
Risk: Medium
Priority: Medium
```

The gap assessment should also identify whether a gap can be addressed through:

* Existing processes.
* A new control.
* Technology implementation.
* Policy changes.
* Training.
* Staffing.
* Outsourcing.
* Process automation.
* Risk acceptance.

For example:

```text
Gap:
Insufficient security awareness coverage.

Treatment:
Training program expansion.
```

Another:

```text
Gap:
Legacy system cannot support MFA.

Treatment:
Compensating controls + planned replacement.
```

This demonstrates that not every gap requires the same type of solution.

The organization should also consider **quick wins**.

Some gaps can be addressed quickly with limited resources.

For example:

```text
Quick Win:
Enable MFA for remaining administrative accounts.
```

Other gaps may require major programs.

For example:

```text
Strategic Initiative:
Enterprise-wide asset discovery and CMDB modernization.
```

The GRC team can therefore classify remediation actions as:

```text
Quick Win
Short-Term
Medium-Term
Strategic
```

This helps prepare for the implementation roadmap in Part 4.

A practical gap register could look like:

| Gap ID | CSF Area          | Current     | Target                  | Risk   | Priority | Action           | Owner | Due |
| ------ | ----------------- | ----------- | ----------------------- | ------ | -------- | ---------------- | ----- | --- |
| G-001  | Access Control    | 70% MFA     | 100%                    | High   | Critical | Extend MFA       | IAM   | Q4  |
| G-002  | Asset Management  | 80%         | 100%                    | High   | High     | Cloud discovery  | IT    | Q1  |
| G-003  | Monitoring        | Partial     | Full critical coverage  | High   | High     | Expand SIEM      | SOC   | Q2  |
| G-004  | Incident Response | Untested    | Annual exercise         | Medium | Medium   | Conduct exercise | SOC   | Q1  |
| G-005  | Recovery          | Annual test | Objective-based testing | Medium | Medium   | Improve testing  | BCM   | Q2  |

The GRC team should periodically update the gap register.

A practical status model is:

```text
Identified
      ↓
Assessed
      ↓
Prioritized
      ↓
Action Planned
      ↓
In Progress
      ↓
Implemented
      ↓
Validated
      ↓
Closed
```

This provides management with visibility into progress.

The gap assessment should also support management reporting.

For example:

```text
Total Gaps: 25

Critical: 3
High: 8
Medium: 10
Low: 4

Closed: 7
In Progress: 12
Not Started: 6
```

Management can then understand the organization's improvement position without reviewing every individual gap.

However, summary metrics should always be supported by the underlying gap register.

For a practical exercise, use the following Current and Target Profiles.

**Current State**

```text
Asset Management:
80% coverage

MFA:
70% coverage

Vulnerability Management:
80% of critical systems scanned

Security Monitoring:
Critical servers monitored

Incident Response:
Plan exists but no annual exercise completed

Recovery:
Annual recovery test
```

**Target State**

```text
Asset Management:
100% coverage

MFA:
100% coverage

Vulnerability Management:
100% of critical systems scanned

Security Monitoring:
All critical systems monitored

Incident Response:
Annual enterprise-wide exercise

Recovery:
Critical systems tested against defined
recovery objectives
```

Create a **NIST CSF Gap Assessment** containing:

```text
Gap ID
CSF Function
Category
Current State
Target State
Gap Description
Gap Type
Risk
Priority
Recommended Action
Owner
Dependencies
Target Date
Success Criteria
Status
```

For example:

```text
Gap ID:
G-001

CSF Function:
Protect

Category:
Identity Management, Authentication,
and Access Control

Current State:
MFA covers 70% of users.

Target State:
MFA covers 100% of in-scope users.

Gap:
30% coverage gap.

Risk:
Unauthorized access.

Priority:
Critical.

Action:
Extend MFA deployment.

Owner:
IAM Manager.

Success Criteria:
100% coverage except formally
approved exceptions.
```

Then identify which gaps should be addressed first.

The prioritization should consider:

```text
Risk
Business Criticality
Regulatory Requirements
Threat Exposure
Customer Requirements
Implementation Complexity
Dependencies
```

The final result should not simply be a list of weaknesses.

It should become a **risk-based improvement backlog**.

The overall relationship is:

```text
Current Profile
      ↓
Target Profile
      ↓
Gap Assessment
      ↓
Risk-Based Prioritization
      ↓
Remediation Actions
      ↓
Implementation Roadmap
```

The key principle is:

> **A NIST CSF gap assessment transforms the difference between the organization's current and desired cybersecurity states into a prioritized, risk-based set of improvement actions.**

The results of the Current Profile, Target Profile, and Gap Assessment can now be transformed into a practical **NIST CSF Implementation Roadmap**.

The roadmap answers the question:

> **How will we move from the current cybersecurity state to the target state?**

The overall process is:

```text
Current Profile
      ↓
Target Profile
      ↓
Gap Assessment
      ↓
Prioritization
      ↓
Implementation Roadmap
      ↓
Execution
      ↓
Validation
      ↓
Continual Improvement
```

The implementation roadmap converts cybersecurity objectives into specific initiatives, activities, responsibilities, timelines, dependencies, and measurable outcomes.

A practical **NIST CSF Implementation Roadmap Template** can contain:

```text
NIST CSF IMPLEMENTATION ROADMAP

Initiative ID:

NIST CSF Function:

Category:

Related Gap:

Current State:

Target State:

Implementation Action:

Business Objective:

Risk Addressed:

Priority:

Initiative Owner:

Supporting Teams:

Dependencies:

Required Resources:

Estimated Cost:

Start Date:

Target Completion Date:

Milestones:

Success Criteria:

Required Evidence:

Status:

Risk / Issue:

Management Approval:

Comments:
```

The first step is to convert each significant gap into one or more **implementation initiatives**.

For example:

```text
Gap:
MFA coverage is 70%.

Target:
100% MFA coverage.

Implementation Initiative:
Enterprise MFA Expansion Program.
```

The initiative may then contain several activities:

```text
Enterprise MFA Expansion
        ↓
Identify Remaining Users
        ↓
Identify Exceptions
        ↓
Configure MFA
        ↓
Enroll Users
        ↓
Test
        ↓
Monitor Adoption
        ↓
Validate Coverage
```

This demonstrates an important distinction between a **gap** and a **project**.

A gap describes what is missing.

A project or initiative describes how the organization intends to address it.

For example:

```text
Gap:
Incomplete cloud asset visibility.

Initiative:
Enterprise Cloud Asset Discovery Program.
```

The roadmap should therefore avoid simply copying the gap register.

It should translate gaps into actionable work.

A practical roadmap might look like:

| Initiative            | CSF Area | Gap                       | Priority | Owner | Target  |
| --------------------- | -------- | ------------------------- | -------- | ----- | ------- |
| Cloud Asset Discovery | Identify | Incomplete inventory      | Critical | IT    | Q1 2027 |
| MFA Expansion         | Protect  | 30% coverage gap          | Critical | IAM   | Q4 2026 |
| SIEM Expansion        | Detect   | Cloud monitoring gaps     | High     | SOC   | Q2 2027 |
| IR Exercise           | Respond  | Insufficient testing      | Medium   | SOC   | Q1 2027 |
| Recovery Testing      | Recover  | Limited objective testing | High     | BCM   | Q2 2027 |

The roadmap should establish **priorities**.

Not every improvement should start simultaneously.

A practical prioritization sequence may be:

```text
Critical Risk Reduction
        ↓
Regulatory Requirements
        ↓
Business-Critical Capabilities
        ↓
High-Value Improvements
        ↓
Optimization
```

For example, if the organization has both:

```text
Gap A:
Privileged accounts without MFA

Gap B:
Security dashboard requires redesign
```

the MFA initiative should normally receive a higher priority because it addresses a more significant security risk.

The exact priority should, however, be based on the organization's approved risk methodology.

The roadmap should also identify **dependencies**.

Some initiatives cannot begin until another capability has been implemented.

For example:

```text
Cloud Asset Discovery
        ↓
Complete Cloud Inventory
        ↓
Vulnerability Scanning
        ↓
Security Monitoring
        ↓
Risk Reduction
```

If the organization attempts to implement vulnerability scanning before identifying the relevant cloud assets, coverage may remain incomplete.

Dependencies should therefore be documented in the roadmap.

For example:

```text
Initiative:
Cloud Vulnerability Management

Dependency:
Complete cloud asset inventory

Dependency Owner:
IT Asset Management

Required Before:
Vulnerability scanning expansion
```

The roadmap should also identify **milestones**.

For example:

```text
MFA Expansion Program

Milestone 1:
Identify all in-scope accounts

Milestone 2:
Identify technical exceptions

Milestone 3:
Configure MFA policies

Milestone 4:
Enroll users

Milestone 5:
Validate coverage

Milestone 6:
Close approved exceptions
```

Milestones make large initiatives easier to manage.

The roadmap should also establish **target dates**.

For example:

```text
August 2026:
Assessment completed

September 2026:
Implementation planning

October 2026:
Pilot deployment

November 2026:
Enterprise rollout

December 2026:
Validation and closure
```

Dates should be realistic and aligned with organizational capacity.

The roadmap should not assume that every initiative can be completed immediately.

The GRC team should consider:

* Budget.
* Staffing.
* Procurement.
* Technology dependencies.
* Business change windows.
* Regulatory deadlines.
* Existing projects.
* Organizational capacity.
* Vendor dependencies.

A roadmap should therefore represent a **feasible implementation sequence**, not simply a list of desired outcomes.

The roadmap can be organized into phases.

For example:

```text
Phase 1 – Immediate Risk Reduction
0–3 Months

Phase 2 – Capability Development
3–6 Months

Phase 3 – Enterprise Expansion
6–12 Months

Phase 4 – Optimization
12+ Months
```

A sample roadmap could be:

| Phase | Initiative                          | Objective                       |
| ----- | ----------------------------------- | ------------------------------- |
| 1     | Privileged MFA                      | Reduce unauthorized access risk |
| 1     | Critical Asset Inventory            | Improve asset visibility        |
| 2     | Cloud Asset Discovery               | Expand inventory coverage       |
| 2     | SIEM Expansion                      | Improve detection               |
| 3     | Enterprise Vulnerability Management | Improve vulnerability coverage  |
| 3     | IR Exercise Program                 | Improve response readiness      |
| 4     | Continuous Monitoring Optimization  | Improve detection capability    |

The roadmap should also distinguish between **quick wins** and **strategic initiatives**.

A quick win may be:

```text
Enable MFA for privileged accounts.
```

A strategic initiative may be:

```text
Implement enterprise-wide identity governance
and privileged access management.
```

Both contribute to the target state, but they require different levels of planning and resources.

The roadmap should also identify **initiative owners**.

For example:

| Initiative               | Primary Owner               |
| ------------------------ | --------------------------- |
| Asset Management         | IT Asset Manager            |
| MFA                      | IAM Manager                 |
| Vulnerability Management | Security Operations Manager |
| SIEM                     | SOC Manager                 |
| Incident Response        | Incident Response Manager   |
| Recovery Testing         | BCM Manager                 |

The GRC function normally coordinates and monitors the roadmap but does not necessarily own every technical implementation.

This distinction is important.

The GRC professional should be responsible for:

* Maintaining traceability.
* Coordinating stakeholders.
* Monitoring progress.
* Reporting status.
* Tracking risks and issues.
* Validating completion evidence.
* Escalating overdue actions.

Technical teams should normally own the implementation of their respective controls and capabilities.

The roadmap should also identify **supporting teams**.

For example:

```text
MFA Initiative

Primary Owner:
IAM

Supporting Teams:
IT
HR
Application Owners
Service Desk
GRC
```

This helps establish accountability.

The roadmap can also be connected to a **RACI matrix**.

For example:

| Activity           | GRC | IAM | IT | CISO |
| ------------------ | --- | --- | -- | ---- |
| Define Requirement | R   | C   | C  | A    |
| Design Solution    | C   | R   | C  | A    |
| Implement MFA      | C   | R   | C  | I    |
| Validate Coverage  | R   | C   | C  | A    |
| Report Results     | R   | C   | I  | A    |

This becomes particularly useful for large GRC programs.

The roadmap should also identify the **risk being addressed**.

For example:

```text
Initiative:
MFA Expansion

Risk:
Unauthorized account access

Risk Rating:
High

Expected Outcome:
Reduced likelihood of account compromise.
```

This helps management understand the business value of the initiative.

A cybersecurity roadmap should not become a technology shopping list.

For example:

Weak:

> Purchase a new security platform.

Stronger:

> Establish centralized monitoring coverage for all critical systems to improve detection of significant cybersecurity events.

The technology should be selected based on the required capability.

This maintains the risk and outcome focus of the NIST CSF.

The roadmap should also include **success criteria**.

For example:

```text
Initiative:
SIEM Expansion

Success Criteria:

100% of defined critical systems send
security-relevant logs to the SIEM.

Critical alerts are monitored by the SOC.

Monitoring coverage is reported monthly.
```

Another example:

```text
Initiative:
Cloud Asset Discovery

Success Criteria:

100% of in-scope cloud accounts are connected
to the discovery process.

All identified production assets have:
- Owner
- Classification
- Criticality
- Environment
- Lifecycle status
```

Success criteria make it possible to determine whether an initiative has actually achieved its objective.

The roadmap should also identify **required evidence**.

For example:

```text
Initiative:
MFA Expansion

Evidence:

MFA coverage report
IAM configuration
Exception register
User enrollment report
Validation results
```

The evidence provides the basis for closing the associated gap.

The relationship is:

```text
Initiative
      ↓
Implementation
      ↓
Evidence
      ↓
Validation
      ↓
Gap Closure
```

The GRC team should avoid marking initiatives as complete solely because the project team reports completion.

For example:

> IAM reports that MFA deployment is complete.

The GRC team should verify the achievement against the success criteria.

If the target is 100% coverage, the GRC team should confirm that the evidence actually demonstrates 100% coverage or appropriately documented exceptions.

This creates a strong governance mechanism.

The roadmap should also track **implementation status**.

A practical status model is:

```text
Not Started
Planning
In Progress
At Risk
Delayed
Implemented
Validation
Completed
```

The distinction between **Implemented** and **Completed** can be useful.

For example:

```text
Implemented:
Technical deployment completed.

Validation:
Evidence being reviewed.

Completed:
Implementation validated and
success criteria achieved.
```

This prevents premature closure.

The roadmap should also capture **risks and issues**.

For example:

```text
Initiative:
Cloud Asset Discovery

Issue:
Cloud account owners have not been identified.

Impact:
Implementation delayed.

Action:
Establish cloud ownership register.

Owner:
Cloud Governance Team.

Status:
In Progress.
```

A roadmap without issue tracking can create a false impression of progress.

The roadmap can also include **resource requirements**.

For example:

```text
Required Resources:

IAM Engineer
Cloud Security Engineer
GRC Analyst
Project Manager

Technology:
MFA Platform
Identity Provider
Reporting Capability

Budget:
To be determined through approved business case.
```

The exact resources depend on the organization's environment.

Large initiatives may require formal business cases.

For example:

```text
Business Case
      ↓
Budget Approval
      ↓
Project Initiation
      ↓
Implementation
      ↓
Validation
```

The roadmap should therefore connect cybersecurity initiatives to normal organizational project governance.

The implementation roadmap should also account for **regulatory deadlines**.

For example:

```text
Regulatory Requirement:
Security control implementation by defined deadline.

Roadmap Impact:
Initiative moved to higher priority.

Target Date:
Before regulatory deadline.
```

Regulatory requirements can therefore influence sequencing.

However, regulatory compliance should not be the only driver.

A serious security risk may deserve immediate treatment even when no specific regulation requires it.

The roadmap can also identify **business-critical systems**.

For example:

```text
Critical Systems
      ↓
Higher Risk
      ↓
Higher Priority
      ↓
Earlier Implementation
```

This creates a risk-based implementation sequence.

The roadmap should also be periodically reviewed.

A practical governance cycle may be:

```text
Monthly:
Initiative Status Review

Quarterly:
Roadmap Review

Semiannually:
Risk and Priority Review

Annually:
Target Profile Review
```

The frequency should be adjusted according to organizational risk and program complexity.

The roadmap should change when the environment changes.

For example:

```text
New Critical Vulnerability
        ↓
Risk Reassessment
        ↓
Priority Change
        ↓
Roadmap Re-sequencing
```

Similarly:

```text
New Regulation
        ↓
New Requirement
        ↓
Target Profile Update
        ↓
New Initiative
        ↓
Roadmap Update
```

This means the roadmap is not a static project plan.

It is a **living cybersecurity improvement plan**.

A practical roadmap can be maintained in a spreadsheet, GRC platform, project management system, or integrated combination of these tools.

For example:

```text
NIST CSF Target
      ↓
Gap Register
      ↓
GRC Initiative
      ↓
Project / Task
      ↓
Evidence
      ↓
Validation
      ↓
Closed Gap
```

This creates traceability across the GRC lifecycle.

A mature organization can also connect the roadmap to its executive dashboard.

For example:

```text
NIST CSF Implementation Status

Total Initiatives: 18

Completed: 6
In Progress: 8
At Risk: 2
Not Started: 2

Critical Gaps:
3

Critical Gaps Closed:
2

Overall Target Achievement:
67%
```

The exact metrics should be defined carefully so that they represent meaningful progress.

A simple percentage of completed initiatives can be misleading.

For example:

> 90% of initiatives completed.

If the remaining 10% contains the organization's most critical cybersecurity weaknesses, the overall posture may still be unacceptable.

Management reporting should therefore emphasize:

* Critical gaps.
* High-risk gaps.
* Risk reduction.
* Regulatory exposure.
* Business-critical capabilities.
* Overdue remediation.
* Target achievement.

The roadmap should ultimately allow executives to answer:

```text
What are we improving?

Why are we improving it?

Which risks are being reduced?

How much will it cost?

Who is responsible?

When will it be completed?

What dependencies exist?

How will we know the improvement worked?
```

For a practical exercise, use the following prioritized gaps:

```text
G-001:
MFA coverage is 70%.
Target: 100%.
Priority: Critical.

G-002:
Cloud asset inventory is incomplete.
Target: 100%.
Priority: High.

G-003:
Cloud workloads are not fully monitored.
Target: All critical systems monitored.
Priority: High.

G-004:
Incident response exercise is incomplete.
Target: Annual enterprise exercise.
Priority: Medium.

G-005:
Recovery testing does not consistently
validate defined recovery objectives.
Target: Objective-based recovery testing.
Priority: Medium.
```

Create a **NIST CSF Implementation Roadmap** containing:

```text
Initiative ID
Related Gap
NIST CSF Function
Target Capability
Implementation Action
Priority
Owner
Supporting Teams
Dependencies
Start Date
Target Date
Milestones
Resources
Success Criteria
Required Evidence
Status
Risks / Issues
```

For example:

```text
Initiative ID:
I-001

Related Gap:
G-001

NIST CSF Function:
Protect

Target Capability:
100% MFA coverage

Implementation Action:
Expand MFA to all remaining
in-scope users and establish
an exception management process.

Priority:
Critical

Owner:
IAM Manager

Supporting Teams:
IT, HR, Application Owners, GRC

Target:
Q4 2026

Success Criteria:
100% MFA coverage except
formally approved exceptions.

Evidence:
MFA coverage report
Exception register
Validation results.
```

Then organize the initiatives into a logical sequence.

For example:

```text
2026 Q3
- Detailed planning
- Critical privileged MFA expansion
- Cloud asset discovery preparation

2026 Q4
- Enterprise MFA expansion
- Critical asset inventory improvement
- Initial cloud monitoring expansion

2027 Q1
- Complete cloud asset inventory
- Enterprise incident response exercise
- Vulnerability management expansion

2027 Q2
- Full critical-system monitoring
- Recovery objective testing
- Control effectiveness validation
```

The exact dates should be adjusted according to organizational circumstances.

The final roadmap should connect every major initiative back to the original cybersecurity objective:

```text
Business Objective
       ↓
Cybersecurity Risk
       ↓
NIST CSF Target
       ↓
Current-State Gap
       ↓
Implementation Initiative
       ↓
Milestones
       ↓
Evidence
       ↓
Validation
       ↓
Risk Reduction
```

This creates an end-to-end governance structure.

The four tools developed in this section therefore work together:

```text
17.6 Part 1
Current Profile
"Where are we?"

        ↓

17.6 Part 2
Target Profile
"Where do we want to be?"

        ↓

17.6 Part 3
Gap Assessment
"What is missing?"

        ↓

17.6 Part 4
Implementation Roadmap
"How will we get there?"
```

This is the practical value of using the NIST CSF in a GRC program. The framework is not merely a catalog of cybersecurity concepts. When connected to organizational risk, ownership, evidence, projects, and measurable outcomes, it becomes a structured method for managing cybersecurity improvement.

A mature GRC professional should be able to take an executive objective, translate it into a cybersecurity target, assess the current state, identify the gaps, prioritize those gaps according to risk, and develop an implementation roadmap that can be tracked through completion.

The complete lifecycle can be summarized as:

```text
Govern
   ↓
Assess
   ↓
Profile
   ↓
Identify Gaps
   ↓
Prioritize
   ↓
Plan
   ↓
Implement
   ↓
Measure
   ↓
Validate
   ↓
Improve
```

The key principle is:

> **A NIST CSF implementation roadmap converts identified cybersecurity gaps into a prioritized, accountable, measurable, and time-bound improvement program that connects cybersecurity strategy with actual implementation.**





