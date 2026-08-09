## 17.2 Risk Management Tools and Templates — Part 1

# 17.2 Risk Management Tools and Templates

## Part 1 – Enterprise Risk Register

The **Enterprise Risk Register** is one of the most important practical tools in GRC.

It provides a structured and centralized view of the organization's identified risks, their potential impact, ownership, treatment, and current status.

A risk register should not be treated simply as a spreadsheet.

It is a **management instrument** that helps the organization understand its risk exposure and make informed decisions about risk treatment and acceptance.

---

## 1.1 Purpose of an Enterprise Risk Register

The primary purpose of the risk register is to provide a consistent method for recording and monitoring organizational risks.

It should help answer questions such as:

* What risks does the organization face?
* Which risks are the most significant?
* Who owns each risk?
* What controls currently exist?
* What is the current risk level?
* What treatment is planned?
* Which risks have been accepted?
* Which remediation actions are overdue?
* How is the organization's risk exposure changing?

A well-maintained register allows management to move from informal discussions about risk to structured risk management.

---

## 1.2 Risk Register vs Risk Assessment

These two concepts should not be confused.

A **risk assessment** is the process of identifying, analyzing, and evaluating a particular risk.

A **risk register** is the structured repository used to record and monitor the results of risk assessments.

For example:

**Risk Assessment**

> Assess the risk of ransomware affecting critical business systems.

↓

**Risk Register**

> R-2026-001 – Ransomware affecting critical business systems – Critical – CIO – Treatment in progress.

The assessment produces information.

The risk register organizes and maintains that information.

---

## 1.3 Minimum Risk Register Structure

A basic risk register could contain:

| Field              | Description                      |
| ------------------ | -------------------------------- |
| Risk ID            | Unique identifier                |
| Risk Title         | Short description                |
| Risk Description   | Detailed explanation             |
| Risk Category      | Type of risk                     |
| Risk Owner         | Person accountable for the risk  |
| Likelihood         | Probability of occurrence        |
| Impact             | Potential consequence            |
| Inherent Risk      | Risk before considering controls |
| Existing Controls  | Current risk controls            |
| Residual Risk      | Risk remaining after controls    |
| Treatment Strategy | Response selected                |
| Treatment Action   | Planned action                   |
| Action Owner       | Person responsible for treatment |
| Target Date        | Expected completion              |
| Status             | Current state                    |
| Review Date        | Next risk review                 |

The exact structure should be adapted to the organization's risk methodology.

---

## 1.4 Risk Identification

The first step is identifying the risk.

A risk statement should describe a relationship between:

**Cause → Risk Event → Consequence**

For example:

> Because privileged accounts are not consistently reviewed, unauthorized access may remain undetected, resulting in compromise of sensitive systems and data.

This is stronger than simply writing:

> "Privileged access."

The second statement identifies a topic.

The first describes an actual risk.

---

## 1.5 Risk ID

Each risk should have a unique identifier.

Examples:

```text
R-2026-001
R-2026-002
R-2026-003
```

The identifier should remain stable throughout the life of the risk.

If the risk changes from High to Medium, the Risk ID should not change.

The identifier provides traceability across:

* Risk assessments.
* Control records.
* Findings.
* Remediation actions.
* Management reports.

---

## 1.6 Risk Title

The risk title should be short but meaningful.

Weak:

> Cybersecurity

Better:

> Unauthorized privileged access

Better still:

> Inadequate privileged access monitoring may allow unauthorized administrative activity.

However, the detailed description should contain the full context.

The title is primarily used for quick identification and reporting.

---

## 1.7 Risk Description

The risk description should provide enough information for another person to understand the risk without requiring a separate conversation.

A useful structure is:

### Cause

What creates the exposure?

### Event

What could happen?

### Consequence

What would happen if the event occurred?

For example:

> **Cause:** Legacy systems lack centralized security monitoring.
> **Event:** Malicious activity may remain undetected.
> **Consequence:** A successful compromise could result in data loss, service disruption, and regulatory exposure.

This structure improves consistency across the risk register.

---

## 1.8 Risk Categories

Risk categories allow risks to be grouped and analyzed.

Possible categories include:

* Cybersecurity.
* Information security.
* Privacy.
* Third-party.
* Operational.
* Financial.
* Legal.
* Regulatory.
* Technology.
* Business continuity.
* Strategic.
* Physical security.

An organization should establish a controlled taxonomy rather than allowing every user to invent categories.

For example, these should not become separate categories:

* Cyber.
* Cybersecurity.
* Cyber Security.
* IT Security.

Instead, the organization could establish:

> **Cybersecurity**

as the standardized category.

---

## 1.9 Risk Taxonomy

A mature organization may use multiple levels.

Example:

```text
Cybersecurity
│
├── Identity and Access Management
├── Network Security
├── Application Security
├── Data Security
├── Security Operations
└── Vulnerability Management
```

This allows management to identify concentrations of risk.

For example:

> 40% of high cybersecurity risks relate to Identity and Access Management.

This is more useful than simply knowing that the organization has 20 high cybersecurity risks.

---

## 1.10 Risk Owner

Every significant risk should have an accountable **risk owner**.

The risk owner is responsible for ensuring that the risk is properly managed.

The risk owner may:

* Review the risk.
* Evaluate treatment options.
* Allocate resources.
* Approve treatment.
* Accept residual risk where authorized.
* Monitor risk changes.

The risk owner is not necessarily the person performing every remediation task.

For example:

| Role         | Responsibility                   |
| ------------ | -------------------------------- |
| Risk Owner   | Accountable for managing risk    |
| Action Owner | Performs remediation             |
| GRC Analyst  | Facilitates and monitors process |
| CISO         | Provides security oversight      |

This distinction is important.

---

## 1.11 Risk Owner vs Control Owner

These roles are often confused.

### Risk Owner

Accountable for the risk.

### Control Owner

Accountable for operating a specific control.

For example:

**Risk**

> Unauthorized access to privileged systems.

**Risk Owner**

> CIO

**Control**

> Quarterly privileged access review.

**Control Owner**

> IAM Manager

The CIO owns the risk, while the IAM Manager owns the control.

---

## 1.12 Inherent Risk

**Inherent risk** represents the level of risk before considering the effectiveness of existing controls.

For example:

| Likelihood | Impact | Inherent Risk |
| ---------: | -----: | ------------- |
|          4 |      5 | 20 – Critical |

This answers:

> How significant would the exposure be without considering existing safeguards?

Inherent risk helps management understand the underlying exposure.

---

## 1.13 Existing Controls

The risk register should identify important controls that currently address the risk.

For example:

> Risk: Ransomware affecting critical systems

Existing controls might include:

* Endpoint protection.
* Network segmentation.
* Email filtering.
* Security awareness training.
* Backup.
* Vulnerability management.
* Security monitoring.

The register does not necessarily need to contain every technical configuration detail.

Those details may belong in the control repository.

---

## 1.14 Control Effectiveness

The existence of a control does not automatically mean that the risk has been adequately reduced.

For example:

> Backup exists.

This does not prove that the organization can recover successfully.

The organization should consider:

* Is the control implemented?
* Is it operating?
* Is it effective?
* Is it tested?
* Is there evidence?

Control effectiveness can therefore influence the assessment of residual risk.

---

## 1.15 Residual Risk

Residual risk is the risk remaining after considering existing controls.

For example:

**Inherent Risk**

20 – Critical

↓

Existing Controls

Strong endpoint protection, segmentation, backups, monitoring

↓

**Residual Risk**

10 – High

This does not necessarily mean that the risk is unacceptable.

The organization must compare the residual risk against its **risk appetite and risk tolerance**.

---

## 1.16 Risk Scoring

A simple risk model can use:

**Risk Score = Likelihood × Impact**

For example:

Likelihood = 4

Impact = 5

Therefore:

**Risk Score = 20**

An organization might define:

| Score | Rating   |
| ----: | -------- |
|   1–4 | Low      |
|   5–9 | Medium   |
| 10–16 | High     |
| 17–25 | Critical |

The scoring thresholds are organizational decisions and should be formally documented.

---

## 1.17 Likelihood

Likelihood represents the probability that the risk event will occur within the defined assessment period.

A five-point scale could be:

| Score | Likelihood     |
| ----: | -------------- |
|     1 | Rare           |
|     2 | Unlikely       |
|     3 | Possible       |
|     4 | Likely         |
|     5 | Almost Certain |

The organization should define what each level means.

For example, "Likely" should not simply mean that the assessor feels the risk is likely.

There should be defined criteria.

---

## 1.18 Impact

Impact represents the potential consequences if the risk occurs.

Impact can consider:

* Financial loss.
* Operational disruption.
* Customer impact.
* Regulatory consequences.
* Legal exposure.
* Reputational damage.
* Safety implications.
* Data loss.

A five-point scale might be:

| Score | Impact        |
| ----: | ------------- |
|     1 | Insignificant |
|     2 | Minor         |
|     3 | Moderate      |
|     4 | Major         |
|     5 | Severe        |

The organization should define impact criteria appropriate to its business.

---

## 1.19 Multi-Dimensional Impact

For mature risk programs, a single impact score may not provide enough information.

The organization may assess:

* Confidentiality.
* Integrity.
* Availability.
* Financial.
* Regulatory.
* Reputation.

For example:

| Dimension       | Score |
| --------------- | ----: |
| Confidentiality |     5 |
| Integrity       |     4 |
| Availability    |     3 |
| Regulatory      |     5 |
| Reputation      |     4 |

A defined methodology can then determine the overall impact.

This can provide greater analytical precision.

---

## 1.20 Risk Treatment

Once risk has been evaluated, the organization determines how it will respond.

Common treatment strategies include:

### Avoid

Stop the activity creating the risk.

### Mitigate

Implement controls to reduce likelihood or impact.

### Transfer

Transfer some financial or operational consequences to another party.

### Accept

Formally accept the risk within authorized limits.

These options should be based on the organization's risk management methodology.

---

## 1.21 Risk Treatment Action

The treatment strategy should be translated into specific actions.

Weak:

> Improve security.

Better:

> Implement MFA for all privileged accounts.

Even better:

> Implement phishing-resistant MFA for 100% of privileged accounts by 30 September 2026.

A strong action should be:

* Specific.
* Assigned.
* Measurable.
* Time-bound.

---

## 1.22 Action Owner

Every significant treatment action should have an owner.

For example:

| Action                   | Owner           | Due Date |
| ------------------------ | --------------- | -------- |
| Implement MFA            | IAM Manager     | 30 Sep   |
| Segment critical servers | Network Manager | 15 Oct   |
| Update backup process    | IT Operations   | 30 Aug   |

The action owner is responsible for executing the treatment.

This may be different from the risk owner.

---

## 1.23 Risk Status

The register should have standardized statuses.

For example:

* Open.
* Under Assessment.
* Treatment Planned.
* Treatment in Progress.
* Accepted.
* Monitoring.
* Closed.

Avoid allowing users to create arbitrary statuses.

---

## 1.24 Risk Acceptance

Risk acceptance should be formally documented.

A risk acceptance record may include:

* Risk ID.
* Risk description.
* Residual risk.
* Business justification.
* Compensating controls.
* Risk owner.
* Approver.
* Acceptance date.
* Expiration date.
* Review date.

Risk acceptance should not become a way to avoid remediation.

A mature organization treats acceptance as a conscious management decision.

---

## 1.25 Risk Acceptance Authority

Organizations should define who can accept different levels of risk.

For example:

| Risk Level | Acceptance Authority     |
| ---------- | ------------------------ |
| Low        | Risk Owner               |
| Medium     | Business Manager         |
| High       | CISO / Executive         |
| Critical   | Executive Risk Committee |

The exact authority structure depends on the organization's governance model.

---

## 1.26 Risk Review Date

Risks should not remain in the register indefinitely without review.

Each risk should have a defined review frequency.

For example:

| Risk Level | Review Frequency |
| ---------- | ---------------- |
| Critical   | Monthly          |
| High       | Quarterly        |
| Medium     | Semi-Annual      |
| Low        | Annual           |

The organization may define different frequencies.

A risk should also be reassessed when a significant change occurs.

Examples include:

* New technology.
* Major security incident.
* New regulation.
* Business acquisition.
* New supplier.
* Major architecture change.
* Significant control failure.

---

## 1.27 Risk Register Example

A practical enterprise risk register might look like:

| ID    | Risk                      | Category      | Inherent | Residual | Owner               | Treatment | Status      |
| ----- | ------------------------- | ------------- | -------- | -------- | ------------------- | --------- | ----------- |
| R-001 | Ransomware                | Cybersecurity | Critical | High     | CIO                 | Mitigate  | In Progress |
| R-002 | Vendor Data Breach        | Third Party   | High     | Medium   | CISO                | Mitigate  | Monitoring  |
| R-003 | Regulatory Non-Compliance | Compliance    | Critical | High     | Compliance Director | Mitigate  | Open        |
| R-004 | Legacy Infrastructure     | Technology    | High     | High     | CTO                 | Mitigate  | Open        |
| R-005 | Privileged Access         | IAM           | High     | Medium   | CIO                 | Mitigate  | Monitoring  |

This gives management a concise view of the organization's risk landscape.

---

## 1.28 Risk Register Quality Check

A GRC professional should periodically review the register.

Ask:

### Completeness

* Are important risks missing?

### Ownership

* Does every significant risk have an owner?

### Assessment

* Are likelihood and impact current?

### Controls

* Are important controls identified?

### Treatment

* Are treatment actions defined?

### Accountability

* Does every action have an owner?

### Timeliness

* Are due dates realistic?

### Acceptance

* Are accepted risks formally approved?

### Evidence

* Is the assessment supported by evidence?

### Review

* Are risks being reviewed on schedule?

---

## 1.29 Common Risk Register Problems

### Problem 1 – The Register Becomes a List

The organization records risks but does not actively manage them.

### Problem 2 – Risks Have No Owners

Nobody is accountable for managing the exposure.

### Problem 3 – Everything Is High

If every risk is high, the scoring methodology is probably not providing useful prioritization.

### Problem 4 – Old Risks Remain Forever

Risks are not reviewed or closed.

### Problem 5 – Treatment Is Vague

Actions such as "improve security" cannot be effectively tracked.

### Problem 6 – Residual Risk Is Ignored

The organization focuses only on inherent risk.

### Problem 7 – Risk Acceptance Is Informal

Management decisions are not documented.

### Problem 8 – Risk Scores Are Not Evidence-Based

Scores are based entirely on subjective opinion.

---

## 1.30 Evidence-Based Risk Assessment

Risk assessments should use available evidence whenever possible.

Examples include:

* Security incidents.
* Vulnerability reports.
* Audit findings.
* Penetration tests.
* Threat intelligence.
* Control testing.
* Historical incidents.
* Vendor assessments.
* Business impact analysis.

For example, instead of saying:

> "Likelihood is probably high."

the assessor might state:

> "Likelihood is rated 4 because the organization experienced three successful phishing incidents involving privileged users during the previous 12 months."

This provides a stronger basis for the rating.

---

## 1.31 Risk Register and GRC Platform

The risk register can begin as a structured spreadsheet, but mature organizations may manage it through a GRC platform.

The underlying information remains similar:

```text
Risk ID
Risk Description
Category
Owner
Likelihood
Impact
Inherent Risk
Controls
Residual Risk
Treatment
Action Owner
Due Date
Status
Review Date
```

The platform can then provide:

* Automated workflows.
* Notifications.
* Approvals.
* Dashboards.
* Escalations.
* Audit trails.
* Integration.

The technology changes the method of management, but the underlying risk methodology remains essential.

---

## 1.32 Practical Exercise – Create a Risk Register

Create a risk register for a fictional organization.

Assume the organization:

* Has 5,000 employees.
* Operates in multiple countries.
* Processes customer personal data.
* Uses cloud services.
* Has 500 third-party vendors.
* Has several critical business applications.

Identify at least **10 risks**.

For each risk, record:

1. Risk ID.
2. Risk title.
3. Risk description.
4. Category.
5. Risk owner.
6. Likelihood.
7. Impact.
8. Inherent risk.
9. Existing controls.
10. Residual risk.
11. Treatment strategy.
12. Treatment action.
13. Action owner.
14. Target date.
15. Status.
16. Review date.

---

## 1.33 Practical Exercise – Risk Statements

Create three risk statements using:

**Cause → Event → Consequence**

### Example

**Cause:** Critical systems are running unsupported operating systems.

**Event:** Attackers may exploit known vulnerabilities.

**Consequence:** A successful attack could disrupt critical business services and expose sensitive information.

Complete the same exercise for:

1. Phishing.
2. Third-party data breach.
3. Cloud misconfiguration.

---

## 1.34 Practical Exercise – Risk Prioritization

Assume the following risks:

| Risk           | Likelihood | Impact |
| -------------- | ---------: | -----: |
| Phishing       |          4 |      4 |
| Ransomware     |          4 |      5 |
| Vendor Breach  |          3 |      5 |
| Insider Threat |          3 |      4 |
| System Outage  |          2 |      5 |

Using:

**Risk Score = Likelihood × Impact**

calculate the score for each risk and rank them from highest to lowest.

Then determine which risks should receive management attention first.

---

## 1.35 Practical Exercise – Risk Treatment

Take the highest-rated risk from the previous exercise.

Develop:

* Treatment strategy.
* Three specific treatment actions.
* Action owner for each action.
* Target completion date.
* Expected residual risk.

The objective is to move from:

> "We have identified a risk."

to:

> "We have a controlled plan for managing the risk."

---

## 1.36 Practical Exercise – Risk Acceptance

Assume a critical legacy system cannot be replaced for another 18 months because of business constraints.

The system presents a high cybersecurity risk.

Develop a risk acceptance record containing:

* Risk description.
* Business justification.
* Residual risk.
* Compensating controls.
* Risk owner.
* Approval authority.
* Acceptance period.
* Review date.

The exercise demonstrates that risk acceptance is a formal governance decision rather than simply ignoring the risk.

---

## 1.37 Professional GRC Perspective

A risk register is valuable only when it supports decision-making.

A mature GRC professional should be able to look at the register and answer:

> Which risks require immediate attention?

> Which risks exceed risk appetite?

> Which risks are being actively treated?

> Which risks have been accepted?

> Which risk treatments are overdue?

> Where are risks concentrated?

> Are residual risks decreasing?

> Which business units have the greatest exposure?

The risk register should therefore evolve from a **record-keeping tool** into a **management decision-support tool**.

---

## Key Takeaways

1. The enterprise risk register is a core GRC management tool.
2. A risk assessment and risk register are related but different.
3. Every significant risk should have a unique identifier.
4. Risk statements should describe cause, event, and consequence.
5. Risk categories should use a controlled taxonomy.
6. Every significant risk should have an accountable owner.
7. Risk owner and control owner are not necessarily the same person.
8. Inherent risk represents exposure before considering controls.
9. Residual risk represents exposure after considering controls.
10. Risk scoring methodologies should be formally defined.
11. Risk treatment should result in specific, measurable actions.
12. Every treatment action should have an owner and target date.
13. Risk acceptance should be formally documented and approved.
14. Risks should be periodically reviewed and reassessed when significant changes occur.
15. Risk assessments should use evidence whenever possible.
16. A risk register should support management decisions rather than merely store information.
17. A mature risk register provides traceability between risks, controls, treatments, and decisions.

## Part 2 – Risk Assessment Template

The **Risk Assessment Template** is used to perform a structured assessment of an individual risk.

While the enterprise risk register provides an overview of many risks, the risk assessment template provides the detailed analysis behind a particular risk rating.

A good risk assessment should allow another qualified person to understand:

* What the risk is.
* Why the risk exists.
* What could happen.
* What controls are currently in place.
* How likely the event is.
* What the potential impact is.
* What the resulting risk level is.
* Whether additional treatment is required.
* Who is accountable for the decision.

The template therefore provides the analytical foundation for the risk register.

---

## 2.1 Purpose of the Risk Assessment Template

The template should create a consistent process for evaluating risks.

Without a standardized approach, different assessors may evaluate similar risks differently.

For example, one assessor may consider a risk with a likelihood of 4 and impact of 5 to be Critical, while another may classify the same risk as High.

A standardized template reduces this inconsistency by providing:

* Defined terminology.
* Defined scoring criteria.
* Standard questions.
* Required evidence.
* Consistent approval.
* Documented rationale.

---

## 2.2 Basic Risk Assessment Structure

A practical assessment can follow this structure:

```text id="y3r8kn"
Risk Identification
       ↓
Risk Context
       ↓
Risk Analysis
       ↓
Existing Controls
       ↓
Inherent Risk
       ↓
Control Effectiveness
       ↓
Residual Risk
       ↓
Risk Evaluation
       ↓
Treatment Decision
       ↓
Approval
       ↓
Monitoring
```

This provides a repeatable risk assessment lifecycle.

---

## 2.3 Section 1 – Risk Identification

The first section identifies the risk.

Example:

| Field           | Example                               |
| --------------- | ------------------------------------- |
| Risk ID         | R-2026-014                            |
| Risk Title      | Ransomware affecting critical systems |
| Assessment Date | 15 Aug 2026                           |
| Assessor        | GRC Analyst                           |
| Business Unit   | IT Operations                         |
| Risk Owner      | CIO                                   |

The Risk ID should correspond to the organization's central risk register.

---

## 2.4 Section 2 – Risk Description

The assessment should contain a detailed description.

A useful structure is:

### Cause

What creates the exposure?

### Risk Event

What could happen?

### Consequence

What would happen if the event occurred?

Example:

> **Cause:** Several critical servers operate with delayed security patching.
>
> **Risk Event:** An attacker may exploit a known vulnerability to gain unauthorized access.
>
> **Consequence:** The attacker could disrupt critical services, encrypt business data, and cause regulatory and financial impact.

This structure makes the risk easier to analyze.

---

## 2.5 Section 3 – Business Context

Risk should always be considered within its business context.

The assessment should identify:

* Business process.
* System or asset.
* Data involved.
* Business owner.
* Criticality.
* Geographic scope.
* Regulatory relevance.

Example:

| Attribute            | Value                       |
| -------------------- | --------------------------- |
| Business Process     | Customer Order Processing   |
| System               | ERP Platform                |
| Data                 | Customer and Financial Data |
| Criticality          | Critical                    |
| Countries            | Spain, Germany, France      |
| Regulatory Relevance | GDPR, NIS2                  |

The same technical vulnerability can represent very different levels of business risk depending on context.

---

## 2.6 Section 4 – Assets and Resources

Identify what could be affected.

Potential assets include:

* Applications.
* Servers.
* Networks.
* Databases.
* Cloud resources.
* Endpoints.
* Intellectual property.
* Customer information.
* Employees.
* Business processes.

Example:

> **Primary Asset:** Customer Database

> **Supporting Assets:** Database Server, Cloud Storage, Application Server

This provides context for the impact assessment.

---

## 2.7 Section 5 – Threat Identification

Identify the threat that could cause the risk event.

Examples include:

* Cybercriminals.
* Malicious insiders.
* Nation-state actors.
* Opportunistic attackers.
* Competitors.
* Fraudsters.
* Accidental human actions.
* Natural events.

For a ransomware scenario:

> **Threat:** Cybercriminal organization.

The threat should be relevant to the actual risk rather than included simply because it is technically possible.

---

## 2.8 Section 6 – Vulnerability or Weakness

Identify the condition that allows the threat to create the risk.

Examples:

* Unpatched systems.
* Weak authentication.
* Excessive privileges.
* Poor network segmentation.
* Inadequate monitoring.
* Missing backups.
* Weak vendor controls.
* Insufficient security awareness.

For example:

> **Vulnerability:** Critical servers are not consistently patched within the organization's defined remediation timeframe.

This provides a logical connection:

**Threat → Vulnerability → Risk Event**

---

## 2.9 Section 7 – Existing Controls

Identify the controls currently reducing the risk.

For ransomware, controls might include:

* Endpoint detection and response.
* Email security.
* Network segmentation.
* MFA.
* Vulnerability management.
* Backups.
* Security awareness.
* Incident response.
* Security monitoring.

The assessment should distinguish between controls that merely exist and controls that are demonstrated to be effective.

---

## 2.10 Section 8 – Control Effectiveness

Assess whether existing controls are actually working.

A simple model could be:

| Rating              | Description                                  |
| ------------------- | -------------------------------------------- |
| Effective           | Operating as intended                        |
| Partially Effective | Some weaknesses exist                        |
| Ineffective         | Control does not adequately address the risk |
| Not Implemented     | Control does not exist                       |

The organization may use a numerical scale instead.

For example:

**Control Effectiveness = 80%**

However, numerical scores should have clearly defined criteria.

---

## 2.11 Evidence Supporting Control Effectiveness

The assessment should identify evidence supporting the control rating.

Examples include:

* Control test results.
* Audit reports.
* Vulnerability scans.
* Configuration reviews.
* Access review reports.
* Security monitoring reports.
* Penetration tests.
* Incident records.

For example:

> Evidence: Q2 vulnerability management report showing 92% compliance with patching SLA.

This is stronger than simply stating:

> "Patching is effective."

---

## 2.12 Section 9 – Likelihood Assessment

The likelihood assessment determines how probable the risk event is.

A five-point model could be:

| Score | Rating         | Example                      |
| ----: | -------------- | ---------------------------- |
|     1 | Rare           | Exceptional circumstances    |
|     2 | Unlikely       | Could occur but not expected |
|     3 | Possible       | Could reasonably occur       |
|     4 | Likely         | Expected to occur            |
|     5 | Almost Certain | Expected frequently          |

The organization should define objective criteria for each level.

---

## 2.13 Evidence for Likelihood

Likelihood should consider relevant evidence.

Possible evidence includes:

* Threat intelligence.
* Historical incidents.
* Industry incidents.
* Vulnerability severity.
* Attack frequency.
* Exposure level.
* Existing controls.
* Threat actor capability.

For example:

> Likelihood = 4 because the system is internet-facing, contains a known exploitable vulnerability, and similar vulnerabilities have been actively exploited in the sector.

This provides a defensible rationale.

---

## 2.14 Section 10 – Impact Assessment

Impact should evaluate what could happen if the risk event occurs.

Possible dimensions include:

* Confidentiality.
* Integrity.
* Availability.
* Financial.
* Legal.
* Regulatory.
* Operational.
* Reputation.

Example:

| Impact Dimension | Score |
| ---------------- | ----: |
| Confidentiality  |     5 |
| Integrity        |     4 |
| Availability     |     5 |
| Financial        |     4 |
| Regulatory       |     5 |
| Reputation       |     4 |

The organization should define how the overall impact rating is calculated.

---

## 2.15 Business Impact Criteria

Impact criteria should be connected to business consequences.

For example:

### Low

Minor operational inconvenience.

### Medium

Noticeable disruption requiring management attention.

### High

Significant financial, operational, regulatory, or reputational consequences.

### Critical

Severe disruption to critical business operations or significant regulatory, financial, or customer consequences.

Organizations should ideally establish quantitative thresholds where practical.

For example:

> Financial impact greater than €5 million = Critical.

---

## 2.16 Section 11 – Inherent Risk Calculation

Once likelihood and impact have been determined:

**Inherent Risk = Likelihood × Impact**

Example:

Likelihood = 4

Impact = 5

Therefore:

**Inherent Risk = 20**

If the organization's matrix defines 17–25 as Critical:

> **Inherent Risk = Critical**

The assessment should record both the numerical score and the rating.

---

## 2.17 Risk Matrix

A standard risk matrix can be used.

| Likelihood \ Impact |  1 |  2 |  3 |  4 |  5 |
| ------------------- | -: | -: | -: | -: | -: |
| 5                   |  5 | 10 | 15 | 20 | 25 |
| 4                   |  4 |  8 | 12 | 16 | 20 |
| 3                   |  3 |  6 |  9 | 12 | 15 |
| 2                   |  2 |  4 |  6 |  8 | 10 |
| 1                   |  1 |  2 |  3 |  4 |  5 |

The organization then applies its approved thresholds.

The matrix itself should be governed and should not be changed by individual assessors without authorization.

---

## 2.18 Section 12 – Existing Risk Treatment

After calculating inherent risk, evaluate how existing controls reduce the exposure.

For example:

**Inherent Risk**

20 – Critical

↓

Existing Controls

* MFA.
* EDR.
* Network segmentation.
* Offline backups.
* Security monitoring.

↓

**Residual Risk**

12 – High

This demonstrates why residual risk must be assessed separately.

---

## 2.19 Section 13 – Residual Likelihood

Residual likelihood reflects the probability after existing controls are considered.

For example:

**Inherent Likelihood:** 4

Existing controls reduce the probability.

**Residual Likelihood:** 3

The assessor should document the rationale.

Example:

> EDR, network segmentation, and MFA reduce the likelihood of successful compromise; however, the system remains exposed to external threats.

---

## 2.20 Section 14 – Residual Impact

Controls do not always reduce impact.

For example, if sensitive information is successfully stolen, the confidentiality impact may remain very high even if strong preventive controls exist.

Therefore, the assessment should consider whether controls affect:

* Likelihood.
* Impact.
* Both.
* Neither.

Example:

**Inherent Impact:** 5

**Residual Impact:** 5

The impact remains Critical because the system contains highly sensitive customer information.

---

## 2.21 Section 15 – Residual Risk Calculation

Using the same methodology:

**Residual Risk = Residual Likelihood × Residual Impact**

Example:

Residual Likelihood = 3

Residual Impact = 5

Therefore:

**Residual Risk = 15**

If 10–16 represents High:

> **Residual Risk = High**

This is the risk level management must ultimately consider.

---

## 2.22 Section 16 – Risk Appetite Comparison

Residual risk should be compared against the organization's risk appetite.

For example:

**Risk Appetite**

Maximum acceptable score = 9

**Residual Risk**

Score = 15

Therefore:

> **Risk exceeds risk appetite.**

Additional treatment is required unless an authorized decision-maker formally accepts the risk.

This makes risk assessment directly relevant to governance.

---

## 2.23 Section 17 – Risk Treatment Decision

The assessment should record the selected treatment.

Possible options:

* Avoid.
* Mitigate.
* Transfer.
* Accept.

For example:

> **Treatment:** Mitigate

> **Reason:** Residual risk exceeds organizational risk appetite.

---

## 2.24 Section 18 – Treatment Plan

Treatment should be converted into specific actions.

Example:

| Action                               | Owner                  | Target Date |
| ------------------------------------ | ---------------------- | ----------- |
| Patch critical servers               | Infrastructure Manager | 30 Aug      |
| Implement automated patch compliance | IT Operations          | 15 Sep      |
| Segment legacy systems               | Network Manager        | 30 Sep      |
| Validate remediation                 | GRC                    | 10 Oct      |

Each action should be measurable and trackable.

---

## 2.25 Section 19 – Target Residual Risk

The assessment should define the expected risk level after treatment.

For example:

**Current Residual Risk**

15 – High

↓

Treatment Actions

↓

**Target Residual Risk**

6 – Medium

This allows management to determine whether the proposed treatment is sufficient.

---

## 2.26 Section 20 – Cost vs Risk Reduction

Risk treatment should consider proportionality.

Suppose:

**Current Residual Risk:** High

**Treatment Cost:** €2 million

**Expected Risk Reduction:** Small

The organization may determine that the proposed treatment is not economically justified.

Another treatment might achieve a similar reduction for €300,000.

This is why GRC professionals should understand both risk and business context.

---

## 2.27 Section 21 – Risk Acceptance Decision

If management decides not to implement additional treatment, the reason should be documented.

For example:

> "Management accepts the current residual risk because the system will be decommissioned within six months and replacement cost is disproportionate to the remaining exposure."

The decision should identify:

* Risk owner.
* Approval authority.
* Business justification.
* Compensating controls.
* Expiration date.
* Review date.

---

## 2.28 Section 22 – Risk Assessment Approval

The completed assessment should go through the appropriate approval process.

Example:

| Role        | Name    | Decision    | Date   |
| ----------- | ------- | ----------- | ------ |
| GRC Analyst | Analyst | Recommended | 15 Aug |
| Risk Owner  | CIO     | Approved    | 16 Aug |
| CISO        | CISO    | Approved    | 16 Aug |

The exact workflow depends on the organization's governance model.

---

## 2.29 Section 23 – Assessment Review

A risk assessment should be reviewed periodically.

Review triggers can include:

* Major incidents.
* Significant vulnerabilities.
* New technology.
* New regulations.
* Business changes.
* New suppliers.
* Major architecture changes.
* Control failures.
* Changes in threat landscape.

A risk assessment should not be considered permanently valid simply because it was approved.

---

## 2.30 Practical Risk Assessment Template

A reusable template can be structured as follows:

```text id="r0w5vp"
RISK ASSESSMENT

1. Risk Identification
   Risk ID:
   Risk Title:
   Assessment Date:
   Business Unit:
   Risk Owner:
   Assessor:

2. Risk Description
   Cause:
   Risk Event:
   Consequence:

3. Business Context
   Business Process:
   Asset/System:
   Data:
   Business Criticality:
   Regulatory Relevance:

4. Threat and Vulnerability
   Threat:
   Vulnerability:
   Exposure:

5. Existing Controls
   Control 1:
   Control 2:
   Control 3:

6. Control Effectiveness
   Effectiveness Rating:
   Supporting Evidence:

7. Likelihood
   Inherent Likelihood:
   Rationale:

8. Impact
   Inherent Impact:
   Rationale:

9. Inherent Risk
   Score:
   Rating:

10. Residual Risk
    Residual Likelihood:
    Residual Impact:
    Score:
    Rating:
    Rationale:

11. Risk Appetite
    Appetite Threshold:
    Within Appetite?:

12. Risk Treatment
    Strategy:
    Treatment Actions:
    Action Owners:
    Target Dates:

13. Target Risk
    Expected Residual Score:
    Expected Residual Rating:

14. Risk Acceptance
    Required?:
    Approver:
    Expiration Date:

15. Approval
    Risk Owner:
    CISO:
    Executive:

16. Review
    Next Review Date:
    Review Trigger:
```

This structure can be implemented in:

* Excel.
* SharePoint.
* Microsoft Forms.
* ServiceNow GRC.
* Archer.
* Other GRC platforms.

---

## 2.31 Practical Example – Ransomware Risk

### Risk

Ransomware may compromise critical business systems.

### Cause

Several critical systems have delayed security patching.

### Threat

Cybercriminal organizations.

### Vulnerability

Unsupported or unpatched systems.

### Consequence

Service disruption, data loss, financial impact, and regulatory exposure.

### Existing Controls

* EDR.
* Network segmentation.
* MFA.
* Offline backups.
* Security monitoring.
* Incident response.

### Inherent Assessment

Likelihood = 4

Impact = 5

Inherent Risk = 20 – Critical

### Residual Assessment

Likelihood = 3

Impact = 5

Residual Risk = 15 – High

### Risk Appetite

Maximum acceptable score = 9

### Decision

Residual risk exceeds appetite.

### Treatment

Implement:

* Automated patch management.
* Additional network segmentation.
* Legacy system replacement.
* Enhanced ransomware monitoring.

### Target Residual Risk

6 – Medium.

This is a complete risk assessment rather than simply a risk entry.

---

## 2.32 Assessment Quality Review

Before final approval, the GRC professional should ask:

### Risk Definition

* Is the risk clearly described?
* Does the statement identify cause, event, and consequence?

### Evidence

* Is the assessment supported by evidence?
* Are control effectiveness claims substantiated?

### Scoring

* Are likelihood and impact justified?
* Was the approved methodology used?

### Controls

* Are relevant controls identified?
* Are control weaknesses considered?

### Residual Risk

* Is residual risk clearly calculated?
* Does it reflect actual control effectiveness?

### Treatment

* Are actions specific?
* Are owners assigned?
* Are dates realistic?

### Governance

* Is the appropriate risk owner involved?
* Is approval documented?

### Monitoring

* Is a review date defined?
* Are reassessment triggers documented?

---

## 2.33 Common Risk Assessment Errors

### Error 1 – Confusing Vulnerability With Risk

> "Unpatched server"

is a vulnerability.

The risk might be:

> "An attacker may exploit the unpatched server, causing unauthorized access and service disruption."

### Error 2 – Treating Controls as Proof of Low Risk

The existence of a control does not automatically mean that the risk is low.

### Error 3 – Ignoring Control Effectiveness

A control that exists but does not operate effectively should not be treated as fully effective.

### Error 4 – Using Arbitrary Scores

Likelihood and impact should have documented criteria.

### Error 5 – Ignoring Residual Risk

Management decisions should normally focus on the remaining exposure after controls.

### Error 6 – No Treatment Owner

A treatment action without an owner is unlikely to progress.

### Error 7 – No Target Risk

The organization should understand what level of risk treatment is intended to achieve.

### Error 8 – No Review Trigger

Risk can change even when the scheduled review date has not arrived.

---

## 2.34 Risk Assessment Evidence Chain

A strong assessment creates a logical evidence chain:

```text id="x7q1ka"
Threat
   ↓
Vulnerability
   ↓
Risk Event
   ↓
Business Impact
   ↓
Existing Controls
   ↓
Control Effectiveness Evidence
   ↓
Likelihood / Impact
   ↓
Inherent Risk
   ↓
Residual Risk
   ↓
Treatment Decision
   ↓
Approval
```

An auditor or reviewer should be able to follow this chain and understand how the final risk decision was reached.

---

## 2.35 Risk Assessment as a Decision Tool

The purpose of the assessment is ultimately to support a decision.

The decision might be:

> Treat the risk.

> Accept the risk.

> Transfer the risk.

> Avoid the activity.

> Perform additional analysis.

Therefore, a risk assessment should not become an academic exercise in calculating numbers.

The numbers support the decision; they do not replace professional judgment.

---

## 2.36 Practical Exercise – Complete an Assessment

Select one of the following scenarios:

1. Ransomware affecting critical servers.
2. Customer data exposure through a cloud misconfiguration.
3. High-risk third-party supplier compromise.
4. Privileged account compromise.
5. Critical application vulnerability.

Complete the risk assessment template from Sections 1–23.

Your assessment should include:

* Risk statement.
* Threat.
* Vulnerability.
* Existing controls.
* Evidence.
* Likelihood.
* Impact.
* Inherent risk.
* Residual risk.
* Risk appetite comparison.
* Treatment plan.
* Target residual risk.
* Approval requirements.

The objective is to demonstrate that you can take a risk from **identification to a defensible management decision**.

---

## Key Takeaways

1. The risk assessment template provides detailed analysis behind a risk register entry.
2. Risk assessments should follow a standardized methodology.
3. Risk statements should identify cause, event, and consequence.
4. Business context is essential to understanding risk.
5. Threats and vulnerabilities should be clearly distinguished.
6. Existing controls should be documented.
7. Control effectiveness should be supported by evidence.
8. Likelihood and impact should use defined criteria.
9. Inherent risk represents the exposure before considering controls.
10. Residual risk represents the remaining exposure after considering controls.
11. Residual risk should be compared with risk appetite.
12. Treatment actions should be specific, measurable, assigned, and time-bound.
13. Target residual risk should be defined where appropriate.
14. Risk acceptance should be formally documented and approved.
15. Assessments should be reviewed periodically and when significant changes occur.
16. The assessment should create a defensible evidence chain from threat through management decision.
17. Risk scoring supports professional judgment; it does not replace it.
18. The ultimate purpose of the assessment is to support informed risk decisions.


## Part 3 – Risk Treatment Plan Template

The **Risk Treatment Plan** converts an identified risk into a structured set of actions designed to reduce, transfer, avoid, or otherwise manage the risk.

A risk assessment tells the organization **how much risk exists**.

A risk treatment plan explains **what the organization will do about it**.

This distinction is important.

A mature GRC process should not stop after calculating a risk score. A Critical or High risk must lead to an appropriate management decision, and when treatment is required, that decision must be translated into specific, trackable actions.

---

## 3.1 Purpose of a Risk Treatment Plan

The Risk Treatment Plan provides a structured mechanism for:

* Defining the selected treatment strategy.
* Identifying treatment actions.
* Assigning accountability.
* Establishing deadlines.
* Estimating resources.
* Tracking implementation.
* Measuring risk reduction.
* Validating completed actions.
* Monitoring residual risk.

The plan creates a bridge between **risk identification** and **risk reduction**.

```text
Risk Identified
      ↓
Risk Assessed
      ↓
Treatment Decision
      ↓
Treatment Plan
      ↓
Implementation
      ↓
Validation
      ↓
Residual Risk
      ↓
Risk Monitoring
```

---

## 3.2 Risk Treatment Options

A treatment plan should begin by documenting the selected risk response.

The commonly used treatment strategies are:

### Risk Avoidance

Stop the activity creating the risk.

Example:

> Decommission an insecure legacy application that is no longer required.

### Risk Reduction

Implement controls that reduce likelihood and/or impact.

Example:

> Implement phishing-resistant MFA for privileged accounts.

### Risk Sharing or Transfer

Share some of the consequences with another party.

Examples include:

* Cyber insurance.
* Contractual risk transfer.
* Outsourcing certain activities.

Risk transfer does not necessarily eliminate the underlying cybersecurity risk.

### Risk Retention or Acceptance

Retain the risk after determining that the exposure is within acceptable limits or that treatment is not currently proportionate.

Acceptance should be formally authorized.

---

## 3.3 Treatment Strategy Selection

The treatment strategy should be based on:

* Risk level.
* Risk appetite.
* Business requirements.
* Legal obligations.
* Regulatory requirements.
* Treatment cost.
* Technical feasibility.
* Time constraints.
* Business impact.
* Availability of alternatives.

For example:

> A critical vulnerability affecting a business-critical system may require immediate mitigation even when remediation is expensive.

The treatment decision should therefore consider both risk and business context.

---

## 3.4 Treatment Plan Structure

A practical treatment plan can contain:

| Field               | Description                   |
| ------------------- | ----------------------------- |
| Risk ID             | Link to the risk register     |
| Risk Description    | Risk being treated            |
| Current Risk        | Current residual risk         |
| Risk Appetite       | Acceptable threshold          |
| Treatment Strategy  | Selected response             |
| Treatment Objective | Desired outcome               |
| Action              | Specific remediation activity |
| Action Owner        | Person responsible            |
| Supporting Team     | Supporting stakeholders       |
| Priority            | Treatment priority            |
| Target Date         | Expected completion           |
| Resources           | Required resources            |
| Cost                | Estimated cost                |
| Dependencies        | Related activities            |
| Status              | Current progress              |
| Evidence            | Proof of completion           |
| Validation          | Independent verification      |
| Target Risk         | Expected residual risk        |

---

## 3.5 Treatment Objective

Before defining individual actions, establish the desired outcome.

Weak objective:

> Improve cybersecurity.

Better objective:

> Reduce the likelihood of unauthorized privileged access.

Specific objective:

> Reduce privileged account compromise risk by implementing phishing-resistant MFA for all privileged users and validating implementation through quarterly access reviews.

A clear objective helps determine whether the treatment was successful.

---

## 3.6 Treatment Actions

Treatment actions should be specific.

Weak:

> Improve access control.

Better:

> Implement MFA for privileged accounts.

Better still:

> Implement phishing-resistant MFA for 100% of privileged accounts by 30 September 2026 and validate implementation through an independent control test.

The final version is measurable and auditable.

---

## 3.7 SMART Treatment Actions

Treatment actions should ideally follow the SMART principle:

**Specific**

Clearly defines what must be done.

**Measurable**

Provides a way to determine completion.

**Achievable**

Can realistically be implemented.

**Relevant**

Addresses the identified risk.

**Time-bound**

Has a defined deadline.

For example:

> Implement MFA for all privileged accounts by 30 September 2026.

This is much stronger than:

> Improve authentication.

---

## 3.8 Action Ownership

Every treatment action should have an identified owner.

Example:

| Action               | Owner          |
| -------------------- | -------------- |
| Implement MFA        | IAM Manager    |
| Update access policy | GRC Manager    |
| Configure monitoring | SOC Manager    |
| Perform validation   | Internal Audit |

The **risk owner** remains accountable for the risk, while individual **action owners** are responsible for executing specific treatment activities.

---

## 3.9 Risk Owner vs Action Owner

Consider:

**Risk**

> Privileged account compromise.

**Risk Owner**

> CIO.

**Treatment Action**

> Implement phishing-resistant MFA.

**Action Owner**

> IAM Manager.

The IAM Manager performs the action.

The CIO remains accountable for the overall risk.

This distinction prevents accountability gaps.

---

## 3.10 Treatment Prioritization

Not every treatment action requires the same urgency.

Prioritization may consider:

* Risk severity.
* Regulatory deadlines.
* Exploitability.
* Business criticality.
* Customer impact.
* Threat activity.
* Dependency on other projects.

Example:

| Action                                 | Risk     | Priority  |
| -------------------------------------- | -------- | --------- |
| Patch actively exploited vulnerability | Critical | Immediate |
| Implement MFA                          | High     | High      |
| Update documentation                   | Medium   | Normal    |
| Improve reporting                      | Low      | Planned   |

Treatment priority should reflect actual risk rather than simply the age of the finding.

---

## 3.11 Treatment Timeline

A treatment plan should include realistic dates.

Example:

```text
15 Aug
Risk identified
   ↓
20 Aug
Treatment approved
   ↓
30 Aug
Design completed
   ↓
15 Sep
Implementation begins
   ↓
30 Sep
Implementation completed
   ↓
10 Oct
Control validation
   ↓
15 Oct
Residual risk reassessed
```

This creates visibility into the treatment lifecycle.

---

## 3.12 Milestones

Large treatment programs should be divided into milestones.

For example:

**Project: Privileged Access Improvement**

### Milestone 1

Inventory privileged accounts.

### Milestone 2

Identify accounts without MFA.

### Milestone 3

Implement MFA.

### Milestone 4

Remove unnecessary privileged accounts.

### Milestone 5

Perform validation.

### Milestone 6

Reassess residual risk.

Milestones make large remediation programs easier to manage.

---

## 3.13 Dependencies

Treatment actions may depend on other activities.

Examples:

* Procurement.
* Architecture approval.
* Software upgrades.
* Vendor support.
* Business acceptance.
* Legal review.
* Budget approval.

Example:

> MFA implementation depends on upgrading the legacy authentication platform.

The dependency should be documented because it may affect the treatment deadline.

---

## 3.14 Treatment Resources

The treatment plan should identify required resources.

These may include:

* Employees.
* Security specialists.
* Consultants.
* Technology.
* Software licenses.
* Infrastructure.
* Training.
* Legal support.
* Project management.

For example:

> Implementing a new GRC platform may require GRC analysts, IT engineers, procurement, legal, security architecture, and vendor support.

---

## 3.15 Treatment Cost

Cost may be considered when evaluating treatment options.

For example:

| Treatment             | Estimated Cost | Expected Risk Reduction |
| --------------------- | -------------: | ----------------------- |
| Additional monitoring |        €50,000 | Medium                  |
| Network segmentation  |       €250,000 | High                    |
| System replacement    |     €2,000,000 | Very High               |

The least expensive option is not necessarily the best option.

The organization should consider the relationship between:

**Cost → Risk Reduction → Business Value**

---

## 3.16 Cost of Doing Nothing

GRC professionals should also consider the potential cost of leaving the risk untreated.

Possible consequences include:

* Security incidents.
* Operational disruption.
* Regulatory penalties.
* Legal costs.
* Customer compensation.
* Recovery costs.
* Reputation damage.
* Lost revenue.

Therefore:

> Treatment cost should be compared against the potential consequences of unmanaged risk.

---

## 3.17 Treatment Dependencies and Constraints

Real-world treatment plans often encounter constraints.

Examples:

* Legacy technology.
* Limited budget.
* Lack of skilled personnel.
* Vendor limitations.
* Business disruption.
* Regulatory deadlines.
* Integration complexity.

These constraints should be documented rather than hidden.

For example:

> The legacy application cannot support modern MFA. Replacement is scheduled for Q2 2027. Compensating controls will therefore be implemented until replacement.

This provides management with a realistic view of the risk.

---

## 3.18 Compensating Controls

A compensating control may be used when the preferred control cannot yet be implemented.

Example:

**Preferred Control**

Phishing-resistant MFA.

**Constraint**

Legacy system does not support modern authentication.

**Compensating Controls**

* Network isolation.
* Restricted access.
* Additional monitoring.
* Dedicated jump server.
* Enhanced logging.

The compensating controls should be formally documented and assessed.

They should not automatically be considered equivalent to the preferred control.

---

## 3.19 Treatment Status

A standardized status model should be used.

For example:

* Not Started.
* Planned.
* Approved.
* In Progress.
* Blocked.
* Completed.
* Validation Pending.
* Validated.
* Closed.

Avoid using ambiguous statuses such as:

> Almost finished.

A standardized status supports reporting and metrics.

---

## 3.20 Blocked Treatment Actions

Some actions become blocked.

For example:

> MFA implementation is blocked because the identity platform upgrade has not been completed.

The treatment plan should record:

* Blocker.
* Impact.
* Responsible party.
* Escalation.
* Revised date.
* Temporary controls.

A blocked action should not simply remain "In Progress" indefinitely.

---

## 3.21 Overdue Actions

An overdue treatment action should trigger appropriate escalation.

Example:

```text
Due Date Passed
      ↓
Action Becomes Overdue
      ↓
Notify Action Owner
      ↓
Notify Risk Owner
      ↓
Assess Risk Impact
      ↓
Escalate if Required
```

The escalation level should depend on the risk severity.

A three-day delay on a Low risk is very different from a three-month delay on a Critical risk.

---

## 3.22 Treatment Evidence

Completion should be supported by evidence.

For example:

**Action**

Implement MFA for privileged accounts.

**Evidence**

* MFA configuration report.
* Identity platform export.
* List of privileged users.
* Implementation screenshots.
* Control test results.

The treatment should not be marked complete simply because someone states that the work is finished.

---

## 3.23 Validation

The GRC team should determine whether treatment actually reduced the risk.

For example:

> MFA was implemented.

does not automatically mean:

> The risk has been adequately reduced.

Validation may include:

* Configuration review.
* Sample testing.
* Control testing.
* Audit testing.
* Penetration testing.
* Vulnerability scanning.
* Evidence review.

Validation provides assurance that the treatment is operating as intended.

---

## 3.24 Treatment Completion vs Risk Closure

These are different concepts.

**Treatment Completed**

The planned action has been implemented.

**Risk Closed**

The risk no longer exists or is no longer relevant.

For example:

> A vulnerability is remediated.

The original risk may still exist because:

* Other vulnerabilities remain.
* The system remains exposed.
* The threat landscape changed.
* Additional weaknesses exist.

Therefore, the risk should be reassessed after treatment.

---

## 3.25 Target Residual Risk

A treatment plan should define the expected risk after implementation.

Example:

**Current Residual Risk**

20 – Critical

↓

Treatment

↓

**Target Residual Risk**

8 – Medium

This gives management a measurable treatment objective.

If the treatment is completed but the residual risk remains Critical, the organization must determine whether additional treatment is necessary.

---

## 3.26 Treatment Effectiveness

Treatment effectiveness can be evaluated by comparing:

**Before Treatment**

Risk Score = 20

**After Treatment**

Risk Score = 8

Risk reduction:

**20 → 8**

The reduction should not be interpreted mechanically.

A lower score is useful only if the underlying assessment methodology remains valid.

---

## 3.27 Treatment Plan Example

Consider a risk involving ransomware.

### Risk

Ransomware may compromise critical business systems.

### Current Residual Risk

15 – High.

### Risk Appetite

Maximum acceptable score = 9.

### Treatment Objective

Reduce residual risk to Medium or below.

### Treatment Actions

| Action                      | Owner          | Due Date | Status      |
| --------------------------- | -------------- | -------- | ----------- |
| Patch critical systems      | Infrastructure | 30 Aug   | In Progress |
| Deploy EDR                  | SOC            | 15 Sep   | Completed   |
| Improve segmentation        | Network        | 30 Sep   | In Progress |
| Validate backups            | IT Operations  | 10 Sep   | Planned     |
| Conduct ransomware exercise | Security       | 15 Oct   | Planned     |

### Target Risk

6 – Medium.

---

## 3.28 Treatment Plan Template

A reusable template can be structured as:

```text id="j9n4fs"
RISK TREATMENT PLAN

Risk ID:
Risk Title:
Risk Owner:
Current Risk Rating:
Risk Appetite:
Treatment Strategy:

Treatment Objective:

ACTION 1
Action:
Owner:
Priority:
Target Date:
Dependencies:
Resources:
Cost:
Status:
Evidence:
Validation:

ACTION 2
Action:
Owner:
Priority:
Target Date:
Dependencies:
Resources:
Cost:
Status:
Evidence:
Validation:

ACTION 3
Action:
Owner:
Priority:
Target Date:
Dependencies:
Resources:
Cost:
Status:
Evidence:
Validation:

Target Residual Risk:
Target Completion Date:

Risk Acceptance Required:
Approver:

Final Validation:
Validation Date:
Validated By:

Risk Status:
Next Review Date:
```

This template can be implemented in Excel, SharePoint, ServiceNow GRC, Archer, or another GRC platform.

---

## 3.29 Practical Exercise – Create a Treatment Plan

Use the ransomware risk from Part 2.

Assume:

**Current Residual Risk:** 15 – High.

**Risk Appetite:** 9.

Develop a treatment plan containing at least five actions.

For each action identify:

1. Action.
2. Owner.
3. Priority.
4. Target date.
5. Dependencies.
6. Required resources.
7. Expected evidence.
8. Validation method.

Then define the:

> **Target Residual Risk**

---

## 3.30 Practical Exercise – Treatment Prioritization

Consider these treatment actions:

| Action                        |     Cost | Risk Reduction | Urgency   |
| ----------------------------- | -------: | -------------- | --------- |
| Patch critical vulnerability  |  €20,000 | High           | Immediate |
| Replace legacy platform       |      €2M | Very High      | Medium    |
| Improve security awareness    | €100,000 | Medium         | High      |
| Deploy additional monitoring  | €200,000 | Medium         | High      |
| Update security documentation |  €10,000 | Low            | Low       |

Rank the actions according to:

* Risk reduction.
* Urgency.
* Cost.
* Business impact.

Then explain why the most expensive treatment is not necessarily the first action that should be implemented.

---

## 3.31 Practical Exercise – Treatment Delay

Assume a Critical risk has a treatment action due on 30 September.

The action is still incomplete on 30 November.

Determine:

* What should happen to the risk status?
* Who should be notified?
* Should the risk rating be reassessed?
* Should the issue be escalated?
* Should compensating controls be implemented?
* Should the risk acceptance decision be reconsidered?

This exercise demonstrates the difference between simply tracking remediation and actively managing risk.

---

## 3.32 Practical Exercise – Validate Treatment

Assume an organization states:

> "MFA has been implemented for all privileged accounts."

Develop a validation approach.

Identify:

### Evidence

What evidence would you request?

### Testing

What would you test?

### Sampling

Would you test every account or use a sample?

### Exceptions

How would you identify accounts that are excluded?

### Conclusion

What criteria would allow you to conclude that the treatment was effective?

This exercise develops practical GRC assurance skills.

---

## 3.33 Common Treatment Plan Problems

### Problem 1 – Vague Actions

> Improve security.

This cannot be effectively tracked.

### Problem 2 – No Owner

Nobody is accountable for implementation.

### Problem 3 – Unrealistic Deadline

The date does not reflect actual implementation complexity.

### Problem 4 – No Evidence

The action is marked complete without proof.

### Problem 5 – No Validation

Implementation is assumed to equal effectiveness.

### Problem 6 – No Target Risk

The organization does not know what improvement it expects.

### Problem 7 – Treatment Becomes a Project List

The organization tracks activities without checking whether the underlying risk is actually decreasing.

### Problem 8 – Risk Acceptance Becomes Permanent

Temporary acceptance becomes the default solution.

---

## 3.34 Risk Treatment and GRC Reporting

Treatment plan information can be transformed into management metrics.

Examples:

### Treatment Completion Rate

```text
Completed Treatment Actions
────────────────────────── × 100
Total Treatment Actions
```

### Overdue Treatment Rate

```text
Overdue Actions
─────────────── × 100
Total Open Actions
```

### High-Risk Remediation Rate

```text
Closed High-Risk Actions
──────────────────────── × 100
Total High-Risk Actions
```

These metrics should be interpreted carefully.

A high completion rate does not necessarily mean that risk has been reduced effectively.

---

## 3.35 Treatment Plan Dashboard

A management dashboard could show:

| Metric                     | Value |
| -------------------------- | ----: |
| Open High/Critical Risks   |    18 |
| Treatment Actions          |    47 |
| Actions Completed          |    31 |
| Actions Overdue            |     6 |
| Actions Blocked            |     3 |
| Risks Above Appetite       |     7 |
| Risks Reduced This Quarter |     9 |

This allows management to see whether risk treatment is progressing.

---

## 3.36 Treatment and Risk Appetite

Risk treatment should be closely connected to risk appetite.

For example:

```text
Residual Risk
      ↓
Compare with Risk Appetite
      ↓
Within Appetite?
   ↙        ↘
 YES         NO
  ↓           ↓
Monitor    Treat / Accept
```

This creates a clear governance decision point.

---

## 3.37 Treatment and Regulatory Requirements

Some risks cannot simply be accepted because a regulation or law requires a particular control or outcome.

For example, if an applicable regulation requires a specific security measure, management may have limited discretion to accept non-compliance.

The treatment plan should therefore consider:

* Legal requirements.
* Regulatory requirements.
* Contractual obligations.
* Industry standards.
* Internal policies.

A risk assessment should not be used to justify ignoring mandatory obligations.

---

## 3.38 Treatment and Third-Party Risks

Risk treatment may sometimes involve a supplier.

For example:

> A critical vendor does not meet the organization's security requirements.

Possible treatment actions include:

* Contractual remediation.
* Additional security requirements.
* Independent assessment.
* Compensating controls.
* Increased monitoring.
* Vendor replacement.

The organization should ensure that transferring an activity to a vendor does not automatically transfer accountability for the resulting risk.

---

## 3.39 Treatment Plan Lifecycle

A mature treatment process follows a lifecycle:

```text id="m4x9qk"
Identify Risk
      ↓
Assess Risk
      ↓
Select Treatment
      ↓
Develop Plan
      ↓
Approve Plan
      ↓
Implement
      ↓
Collect Evidence
      ↓
Validate
      ↓
Reassess Risk
      ↓
Accept / Further Treat
      ↓
Monitor
```

The important step is **reassessment**.

The organization should determine whether the treatment actually changed the risk.

---

## 3.40 Professional GRC Perspective

A GRC professional should avoid treating remediation as a simple checklist.

The key question is not:

> "Did the team complete the action?"

The more important question is:

> "Did the action reduce the organization's risk to an acceptable level?"

For example:

**Action completed:**

EDR deployed.

But:

**Risk question:**

Did EDR materially reduce the likelihood of ransomware successfully compromising critical systems?

The answer requires evidence and validation.

This is the difference between **activity tracking** and **risk management**.

---

## Key Takeaways

1. A Risk Treatment Plan converts risk decisions into specific actions.
2. Treatment should be based on risk, appetite, business context, and applicable obligations.
3. Common treatment strategies include avoidance, reduction, transfer/sharing, and acceptance.
4. Treatment objectives should describe the desired risk outcome.
5. Actions should be specific, measurable, achievable, relevant, and time-bound.
6. Every treatment action should have an accountable owner.
7. Large treatment programs should be divided into milestones.
8. Dependencies and constraints should be explicitly documented.
9. Compensating controls may be used when the preferred control cannot immediately be implemented.
10. Treatment completion should be supported by evidence.
11. Treatment implementation should be independently or appropriately validated.
12. Completing a treatment action does not automatically mean the risk is closed.
13. Target residual risk provides a measurable treatment objective.
14. Treatment should be monitored for overdue and blocked actions.
15. Risk treatment should remain connected to risk appetite.
16. Regulatory and contractual obligations may limit the organization's ability to simply accept certain risks.
17. The effectiveness of treatment should ultimately be determined by its impact on residual risk.
18. A mature GRC professional manages **risk reduction**, not merely remediation tasks.




