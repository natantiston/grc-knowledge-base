# 18.3 Risk Management Diagrams

## Part 1 – Enterprise Risk Management Diagram

An Enterprise Risk Management diagram provides a visual representation of how an organization identifies, assesses, treats, monitors, reports, and governs risks across the enterprise.

The purpose of the diagram is to show how risk management connects business objectives with risk decisions.

A basic Enterprise Risk Management model can be represented as:

```text
Business Objectives
        ↓
Risk Identification
        ↓
Risk Assessment
        ↓
Risk Evaluation
        ↓
Risk Treatment
        ↓
Residual Risk
        ↓
Risk Monitoring
        ↓
Risk Reporting
        ↓
Management Decision
        ↓
Continuous Improvement
```

Risk management should begin with the organization's objectives.

Organizations take risks because they are trying to achieve something.

For example:

```text
Business Objective
       ↓
Launch New Digital Service
       ↓
Business Dependencies
       ↓
Potential Risks
       ↓
Risk Assessment
       ↓
Risk Treatment
```

This is important because GRC professionals should avoid treating risk management as a purely administrative exercise.

The fundamental relationship is:

```text
Business Objective
        ↓
Uncertainty
        ↓
Risk
        ↓
Potential Impact
        ↓
Management Decision
```

A risk can affect the organization's ability to achieve its objectives.

An enterprise may face many different categories of risk:

```text
                         Enterprise Risk
                                │
       ┌────────────────────────┼────────────────────────┐
       ↓                        ↓                        ↓
 Strategic Risk          Operational Risk          Financial Risk
       │                        │                        │
       ├── Market               ├── Process             ├── Credit
       ├── Business Model       ├── Technology          ├── Liquidity
       └── Competition          └── People              └── Market
       
       ┌────────────────────────┼────────────────────────┐
       ↓                        ↓                        ↓
 Cybersecurity Risk      Compliance Risk          Third-Party Risk
       │                        │                        │
       ├── Data Breach          ├── Regulatory           ├── Supplier
       ├── Ransomware            ├── Legal                ├── Outsourcing
       └── Unauthorized Access   └── Contractual          └── Concentration
```

The exact risk taxonomy should be customized to the organization.

A mature risk management diagram should clearly distinguish between **risk identification**, **risk assessment**, and **risk treatment**.

```text
Risk Identification
        ↓
What could happen?
        ↓
Risk Analysis
        ↓
How likely is it?
What would be the impact?
        ↓
Risk Evaluation
        ↓
Is the risk acceptable?
        ↓
Risk Treatment
        ↓
What should we do?
```

Risk identification may consider:

* Business processes
* Assets
* Threats
* Vulnerabilities
* Regulatory requirements
* Technology changes
* Third parties
* People
* External events
* Emerging risks

For cybersecurity risk, the model can be expanded:

```text
Asset
  ↓
Threat
  ↓
Vulnerability
  ↓
Threat Event
  ↓
Potential Impact
  ↓
Cybersecurity Risk
```

For example:

```text
Customer Database
        ↓
Cyber Threat
        ↓
Unpatched Application
        ↓
Unauthorized Access
        ↓
Customer Data Exposure
        ↓
Cybersecurity Risk
```

The next stage is risk analysis.

A common conceptual model is:

```text
Likelihood × Impact = Risk
```

For example:

```text
Likelihood: High
Impact: High
        ↓
High / Critical Risk
```

Organizations may use qualitative, semi-quantitative, or quantitative risk assessment methodologies.

A qualitative approach might use:

```text
Likelihood:
Low / Medium / High

Impact:
Low / Medium / High
```

A more detailed approach might use numerical scoring.

```text
Likelihood Score × Impact Score
              ↓
          Risk Score
```

The resulting risk rating can then be represented on a risk matrix:

```text
                 IMPACT
             Low   Med   High
          ┌─────┬─────┬─────┐
High      │ Med │ High│Crit │
          ├─────┼─────┼─────┤
LIKELIHOOD│ Low │ Med │ High│
Medium    ├─────┼─────┼─────┤
          │ Low │ Low │ Med │
Low       └─────┴─────┴─────┘
```

The organization should define its own scoring methodology and thresholds.

Once the risk is assessed, it should be compared against risk appetite.

```text
Inherent Risk
      ↓
Existing Controls
      ↓
Residual Risk
      ↓
Compare With Risk Appetite
      ↓
Within Appetite?
   ↙          ↘
 Yes           No
 ↓              ↓
Monitor       Treatment /
              Escalation
```

This distinction between inherent and residual risk is important.

**Inherent risk** represents the level of risk before considering relevant controls.

```text
Threat
  ↓
Risk
  ↓
Inherent Risk
```

**Residual risk** represents the remaining risk after considering controls.

```text
Inherent Risk
      ↓
Controls
      ↓
Residual Risk
```

For example:

```text
Inherent Risk:
High

Security Controls:
MFA
Encryption
Monitoring
Access Reviews

Residual Risk:
Medium
```

The organization may then decide whether the residual risk is acceptable.

Risk treatment can generally involve several approaches:

```text
Risk Treatment
      │
      ├── Avoid
      │
      ├── Reduce / Mitigate
      │
      ├── Transfer / Share
      │
      └── Accept
```

Risk avoidance means changing the activity so that the risk is no longer applicable.

```text
Risky Activity
      ↓
Stop / Change Activity
      ↓
Risk Avoided
```

Risk mitigation means implementing measures that reduce likelihood, impact, or both.

```text
Risk
 ↓
Security Controls
 ↓
Reduced Likelihood / Impact
 ↓
Lower Residual Risk
```

Risk transfer or sharing may involve:

```text
Risk
 ↓
Insurance
Contractual Arrangement
Outsourcing
Risk Sharing
```

Risk acceptance means management formally accepts the remaining exposure.

```text
Residual Risk
      ↓
Risk Owner
      ↓
Within Authority?
   ↙          ↘
 Yes           No
 ↓              ↓
Accept       Escalate
```

Risk acceptance should be documented and subject to the organization's approval requirements.

Risk ownership should also be visible in the Enterprise Risk Management diagram.

```text
Risk
 ↓
Risk Owner
 ↓
Risk Treatment Decision
 ↓
Monitoring
 ↓
Reporting
```

The risk owner should normally have sufficient authority and accountability to make decisions regarding the risk.

The GRC function may support the risk owner by providing:

* Risk methodology
* Risk assessment guidance
* Risk registers
* Risk reporting
* Risk monitoring
* Risk challenge
* Risk aggregation
* Escalation support

A typical relationship is:

```text
Risk Owner
     ↓
Owns Risk Decision

GRC
     ↓
Provides Methodology / Challenge / Monitoring

Management
     ↓
Approves Significant Decisions

Board
     ↓
Provides Oversight
```

The Enterprise Risk Management diagram should also show **risk aggregation**.

Individual risks can be grouped into larger risk categories.

```text
Individual Risks
       ↓
Risk Categories
       ↓
Enterprise Risk Profile
       ↓
Executive Reporting
       ↓
Board Oversight
```

For example:

```text
Cybersecurity Risks
       │
       ├── Ransomware
       ├── Data Breach
       ├── Insider Threat
       ├── Cloud Misconfiguration
       └── Third-Party Cyber Risk
               ↓
        Cyber Risk Profile
               ↓
        Enterprise Risk Profile
```

This helps management understand the organization's overall exposure rather than reviewing risks only as isolated items.

Risk aggregation can also identify concentration risk.

For example:

```text
Multiple Business Units
        ↓
Same Cloud Provider
        ↓
Common Dependency
        ↓
Concentration Risk
```

This is particularly important for third-party and technology risks.

The Enterprise Risk Management model should also include **risk monitoring**.

```text
Residual Risk
      ↓
Risk Monitoring
      ↓
Risk Indicators
      ↓
Risk Trend
      ↓
Threshold Breach?
   ↙          ↘
 No            Yes
 ↓              ↓
Continue      Escalate
Monitoring
```

Key Risk Indicators can help identify changes in risk exposure.

Examples include:

```text
Number of Critical Vulnerabilities

Number of Security Incidents

Third-Party Risk Rating

Control Failure Rate

Unresolved Audit Findings

Regulatory Breaches

System Availability

Privileged Access Exceptions
```

The diagram should connect these indicators to management action.

```text
KRI
 ↓
Threshold
 ↓
Breach
 ↓
Risk Assessment
 ↓
Escalation
 ↓
Management Action
```

Risk management should also include **risk review**.

```text
Risk Register
      ↓
Periodic Review
      ↓
Risk Still Relevant?
   ↙          ↘
 Yes           No
 ↓              ↓
Reassess      Retire
```

A risk should not remain permanently in the risk register without periodic reassessment.

Changes in the organization may require reassessment.

Examples include:

* New technology
* New regulation
* New supplier
* New business process
* Organizational restructuring
* Major security incident
* Mergers and acquisitions
* New geographic expansion
* Significant changes in threat landscape

This can be represented as:

```text
Business Change
      ↓
Risk Review
      ↓
Risk Reassessment
      ↓
Treatment Update
      ↓
Monitoring
```

The Enterprise Risk Management diagram should also show **risk reporting**.

```text
Operational Risk Data
        ↓
Risk Register
        ↓
Risk Analysis
        ↓
Risk Dashboard
        ↓
Management Reporting
        ↓
Risk Committee
        ↓
Board
```

Different audiences require different levels of risk information.

Operational teams may need:

```text
Individual Risk
Risk Owner
Controls
Actions
Due Dates
```

Executives may need:

```text
Top Risks
Risk Trends
Risk Appetite Breaches
Treatment Status
Emerging Risks
```

The Board may need:

```text
Enterprise Risk Profile
Strategic Risks
Material Cyber Risks
Risk Appetite
Major Risk Changes
Management Response
```

A complete Enterprise Risk Management diagram can therefore be represented as:

```text
                         BUSINESS OBJECTIVES
                                  │
                                  ↓
                         RISK IDENTIFICATION
                                  │
                                  ↓
                           RISK ANALYSIS
                                  │
                                  ↓
                         RISK EVALUATION
                                  │
                                  ↓
                         INHERENT RISK
                                  │
                                  ↓
                           RISK TREATMENT
                                  │
                                  ↓
                              CONTROLS
                                  │
                                  ↓
                           RESIDUAL RISK
                                  │
                    ┌─────────────┴─────────────┐
                    ↓                           ↓
             Within Appetite?             Outside Appetite?
                    ↓                           ↓
                Monitor                  Treat / Escalate
                    │                           │
                    └─────────────┬─────────────┘
                                  ↓
                          RISK MONITORING
                                  │
                                  ↓
                        RISK INDICATORS
                                  │
                                  ↓
                         RISK REPORTING
                                  │
                                  ↓
                       MANAGEMENT DECISION
                                  │
                                  ↓
                       CONTINUOUS REVIEW
                                  │
                                  └──────────────→
```

The complete risk governance relationship can also be summarized as:

```text
Business Objective
       ↓
Risk
       ↓
Risk Owner
       ↓
Risk Assessment
       ↓
Risk Appetite
       ↓
Treatment Decision
       ↓
Controls
       ↓
Residual Risk
       ↓
Monitoring
       ↓
Reporting
       ↓
Management Decision
       ↓
Continuous Improvement
```

The Enterprise Risk Management diagram should ultimately communicate one central principle:

**Risk management is not simply the identification of risks. It is a continuous management process that connects business objectives, uncertainty, risk ownership, controls, risk appetite, treatment decisions, monitoring, reporting, and management action.**

A risk lifecycle diagram provides a visual representation of how an organization manages a risk from the moment it is identified until it is treated, monitored, reviewed, and eventually closed or retired.

The risk lifecycle should be viewed as a **continuous process**, rather than a one-time assessment.

```text id="1m5f8u"
Identify
   ↓
Analyze
   ↓
Evaluate
   ↓
Treat
   ↓
Monitor
   ↓
Review
   ↓
Improve
   ↺
```

The lifecycle begins with **risk identification**.

```text id="a7q2ny"
Business Activity
      ↓
Potential Event
      ↓
Risk Identified
      ↓
Risk Registered
```

Risk identification can originate from many sources:

* Business processes
* Security assessments
* Internal audits
* Compliance assessments
* Vulnerability assessments
* Security incidents
* Third-party assessments
* Regulatory changes
* New projects
* Technology changes
* Business continuity exercises
* Emerging threats
* Management observations

For example:

```text id="0l0j4v"
Cloud Migration
      ↓
New Technology Dependency
      ↓
Potential Security Exposure
      ↓
Risk Identified
```

Once identified, the risk should be documented in the risk register.

Typical information includes:

```text id="4p5n0h"
Risk ID
Risk Description
Risk Category
Risk Owner
Affected Asset / Process
Threat
Vulnerability
Potential Impact
Existing Controls
Risk Rating
Treatment
Status
```

The next stage is **risk analysis**.

```text id="b6k9w2"
Risk
 ↓
Likelihood Assessment
 ↓
Impact Assessment
 ↓
Inherent Risk
```

Likelihood considers how probable the risk event may be.

Impact considers the consequences if the event occurs.

Impact may include:

```text id="b6qj6f"
Financial
Operational
Regulatory
Legal
Customer
Reputational
Safety
Strategic
```

For cybersecurity:

```text id="c8u5p0"
Threat
  ↓
Likelihood
  +
Potential Impact
  ↓
Inherent Cyber Risk
```

For example:

```text id="5x5y6w"
Risk:
Ransomware Attack

Likelihood:
High

Potential Impact:
High

Inherent Risk:
Critical
```

The organization then performs **risk evaluation**.

Risk evaluation determines whether the assessed risk is acceptable according to the organization's risk criteria and risk appetite.

```text id="5q5s5b"
Inherent Risk
      ↓
Risk Evaluation
      ↓
Compare Against Risk Appetite
      ↓
Acceptable?
   ↙          ↘
 Yes           No
 ↓              ↓
Monitor       Treat / Escalate
```

Risk evaluation is therefore different from risk analysis.

```text id="g6qk87"
Risk Analysis
"What is the level of risk?"

Risk Evaluation
"Is this level of risk acceptable?"
```

Once a decision is made to address the risk, the organization enters the **risk treatment** stage.

```text id="8sl6q4"
Risk Treatment
      │
      ├── Avoid
      ├── Mitigate
      ├── Transfer / Share
      └── Accept
```

For cybersecurity risks, mitigation is often achieved through security controls.

```text id="0e0p8c"
Cyber Risk
    ↓
Control Selection
    ↓
Control Implementation
    ↓
Control Operation
    ↓
Residual Risk
```

For example:

```text id="i4p1k5"
Risk:
Unauthorized Access

Controls:
MFA
Privileged Access Management
Access Reviews
Logging
Monitoring

        ↓

Residual Risk
```

The next stage is **residual risk assessment**.

```text id="wq5x7t"
Inherent Risk
      ↓
Existing / Planned Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
```

The organization then determines whether the residual risk remains within acceptable boundaries.

```text id="4j8f5n"
Residual Risk
      ↓
Within Risk Appetite?
    ↙          ↘
  Yes           No
   ↓             ↓
Accept /      Additional
Monitor       Treatment
                 ↓
              Reassess
```

This creates an iterative loop.

```text id="j7g1u6"
Risk
 ↓
Treatment
 ↓
Residual Risk
 ↓
Still Too High?
 ↙          ↘
Yes          No
 ↓            ↓
Retreat     Accept
 ↓
Reassess
```

The risk lifecycle then moves into **monitoring**.

Risk monitoring determines whether the risk profile is changing.

```text id="z2a7g9"
Residual Risk
      ↓
Monitoring
      ↓
Risk Indicators
      ↓
Risk Trend
      ↓
Thresholds
      ↓
Action if Required
```

Monitoring may include:

* Key Risk Indicators
* Control performance
* Security metrics
* Compliance status
* Incident trends
* Vulnerability trends
* Third-party performance
* Audit findings
* Business changes

For example:

```text id="l2qf5z"
Critical Vulnerabilities
        ↓
KRI Monitoring
        ↓
Threshold Exceeded
        ↓
Risk Increased
        ↓
Escalation
```

Monitoring should not be limited to checking whether controls exist.

It should determine whether the overall risk remains acceptable.

```text id="z8h8tm"
Control Status
     ↓
Risk Exposure
     ↓
Risk Trend
     ↓
Management Decision
```

The next stage is **risk review**.

Risk reviews should occur periodically and whenever significant changes occur.

```text id="j6d4ue"
Risk Review
     ↓
Has the Environment Changed?
    ↙              ↘
  No                Yes
   ↓                 ↓
Continue          Reassess
Monitoring          Risk
                      ↓
                 Update Treatment
```

Triggers for reassessment may include:

```text id="jbhq1c"
New Technology
New Threat
Security Incident
Regulatory Change
Business Change
New Supplier
Control Failure
Organizational Change
New Vulnerability
Major Project
```

For example:

```text id="w3b2qh"
Risk:
Cloud Security Risk

        ↓

New Cloud Architecture

        ↓

Risk Environment Changed

        ↓

Risk Reassessment

        ↓

New Treatment

        ↓

New Residual Risk
```

The lifecycle also includes **risk communication and reporting**.

```text id="x8z6o9"
Risk Data
   ↓
Risk Analysis
   ↓
Risk Reporting
   ↓
Risk Owner
   ↓
Management
   ↓
Risk Committee
   ↓
Board
```

Not every risk needs to be reported to every governance level.

Reporting should be based on:

* Risk severity
* Risk appetite
* Materiality
* Strategic importance
* Regulatory requirements
* Management thresholds

A useful reporting model is:

```text id="8c8j8n"
Operational Risk
      ↓
Risk Owner

Significant Risk
      ↓
Executive Management

Material Risk
      ↓
Risk Committee

Strategic / Critical Risk
      ↓
Board
```

Another important stage is **risk closure or retirement**.

Not every risk remains active indefinitely.

A risk may be closed when:

```text id="9q1f7a"
Risk Eliminated
      ↓
No Longer Relevant
      ↓
Activity Discontinued
      ↓
Risk Retired
```

For example:

```text id="m0u8r8"
Legacy Application
      ↓
Application Decommissioned
      ↓
Associated Risk Eliminated
      ↓
Risk Closed
```

However, closure should be supported by evidence.

```text id="k2q5v4"
Risk Closure Request
        ↓
Evidence Review
        ↓
Risk Owner Approval
        ↓
GRC Validation
        ↓
Risk Register Updated
        ↓
Risk Closed
```

This prevents risks from being removed simply because they are inconvenient or overdue.

A mature risk lifecycle therefore contains several interconnected loops.

```text id="n6r8w0"
                  IDENTIFY
                     ↓
                  ANALYZE
                     ↓
                  EVALUATE
                     ↓
                   TREAT
                     ↓
                 RESIDUAL
                   RISK
                     ↓
                  MONITOR
                     ↓
                   REVIEW
                     ↓
              CHANGE DETECTED?
                ↙         ↘
              No           Yes
               ↓            ↓
           Continue       Reassess
               │            │
               └─────┬──────┘
                     ↓
                  REPORT
                     ↓
                MANAGEMENT
                 DECISION
                     ↓
                IMPROVEMENT
                     │
                     └────────→ IDENTIFY
```

The relationship between **risk lifecycle and control lifecycle** is also important.

```text id="4l2w0j"
Risk Lifecycle
      │
      ↓
Risk Identified
      │
      ↓
Control Requirement
      │
      ↓
Control Lifecycle
      │
      ↓
Control Implemented
      │
      ↓
Control Tested
      │
      ↓
Control Monitored
      │
      ↓
Control Improved
      │
      ↓
Residual Risk Reassessed
```

This demonstrates that controls are not the end of risk management.

The ultimate objective is managing the residual risk.

For example:

```text id="b8e6z4"
Risk Identified
      ↓
MFA Implemented
      ↓
MFA Control Tested
      ↓
MFA Effective
      ↓
Residual Risk Reduced
      ↓
Risk Monitoring
```

A risk lifecycle should also connect with the **issue management lifecycle**.

```text id="q5x4j6"
Risk Identified
      ↓
Control Assessment
      ↓
Control Failure
      ↓
Finding
      ↓
Remediation
      ↓
Validation
      ↓
Risk Reassessment
```

This creates an important relationship:

```text id="1h3p5w"
Risk
 ↓
Control
 ↓
Control Failure
 ↓
Finding
 ↓
Remediation
 ↓
Residual Risk
```

Similarly, incidents can trigger the risk lifecycle.

```text id="u6k2p9"
Security Incident
      ↓
Incident Investigation
      ↓
Root Cause
      ↓
New / Increased Risk
      ↓
Risk Assessment
      ↓
Additional Controls
      ↓
Residual Risk
```

Therefore, risk management should receive information from multiple GRC processes.

```text id="1z4g6n"
                  Risk Management
                       ↑
       ┌───────────────┼────────────────┐
       ↑               ↑                ↑
   Incidents         Audits          Compliance
       ↑               ↑                ↑
       └───────────────┼────────────────┘
                       ↑
                 Control Testing
```

This creates an integrated GRC environment.

The lifecycle can also incorporate **emerging risks**:

```text id="1e7p4j"
Emerging Risk
      ↓
Initial Identification
      ↓
Monitoring
      ↓
Potential Materiality
      ↓
Formal Risk Assessment
      ↓
Risk Register
      ↓
Treatment
```

For example:

```text id="2r3j7n"
Generative AI Adoption
        ↓
New Data / Privacy / Security Risks
        ↓
Emerging Risk Monitoring
        ↓
Risk Assessment
        ↓
AI Governance Controls
        ↓
Residual Risk
```

The final lifecycle can be summarized as:

```text id="6f2p8k"
                    ┌───────────────┐
                    │   IDENTIFY    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    ANALYZE    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │   EVALUATE    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │     TREAT     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    MONITOR    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    REVIEW     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    REPORT     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    DECIDE     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │    IMPROVE    │
                    └───────┬───────┘
                            │
                            └──────────→ IDENTIFY
```

The key principle is:

> **Risk management is a continuous lifecycle, not a one-time risk assessment.**

A mature GRC professional should be able to trace a risk from its original identification through assessment, treatment, control implementation, residual risk, monitoring, reporting, reassessment, and eventual closure or continued acceptance.




