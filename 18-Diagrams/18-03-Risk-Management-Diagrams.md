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



