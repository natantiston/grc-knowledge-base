# 18.15 GRC Metrics and Dashboard Diagrams

## Part 1 – KPI and KRI Relationship Model

GRC programs generate a large amount of information. However, **data alone does not provide management insight**.

Organizations need a structured way to convert GRC information into meaningful measurements that can answer questions such as:

* Are security and compliance objectives being achieved?
* Is risk increasing or decreasing?
* Are controls operating effectively?
* Are remediation activities progressing?
* Are emerging risks becoming more significant?
* Where should management focus attention and resources?

Two of the most important measurement categories are **Key Performance Indicators (KPIs)** and **Key Risk Indicators (KRIs)**.

A KPI generally measures **performance against an objective**, while a KRI provides an indication of **risk exposure or changing risk conditions**.

A simplified relationship is:

```text
Business Objectives
        ↓
Performance Measurement
        ↓
       KPIs
        ↓
Performance Insight


Risk Environment
        ↓
Risk Measurement
        ↓
       KRIs
        ↓
Risk Insight
```

Together, KPIs and KRIs provide a more complete view of organizational performance and risk.

---

# 1. What Is a KPI?

A **Key Performance Indicator (KPI)** is a measurable indicator used to determine whether an activity, process, program, or objective is performing as expected.

In GRC, KPIs can measure areas such as:

```text
Control Performance
Compliance Performance
Audit Performance
Risk Treatment
Remediation
Security Operations
Third-Party Management
Policy Management
```

Examples include:

```text
Percentage of controls tested
Percentage of assessments completed
Percentage of remediation actions closed on time
Percentage of employees completing security awareness training
Percentage of suppliers assessed
Percentage of policies reviewed on schedule
```

The important question behind a KPI is:

> **How well are we performing against an expected objective?**

---

# 2. What Is a KRI?

A **Key Risk Indicator (KRI)** is a measurable indicator that provides information about a risk condition or changes in risk exposure.

KRIs can identify increasing risk before a major event occurs.

Examples include:

```text
Number of critical vulnerabilities
Percentage of privileged accounts
Number of overdue high-risk findings
Third-party risk exposure
Number of security incidents
Percentage of unsupported systems
Number of policy exceptions
```

The important question behind a KRI is:

> **Is our risk exposure increasing, decreasing, or remaining stable?**

---

# 3. KPI vs KRI

The distinction can be represented as:

```text
                 KPI                         KRI
                  │                           │
                  ↓                           ↓
           PERFORMANCE                    RISK
                  │                           │
                  ↓                           ↓
        Are we achieving?             Are we exposed?
```

A practical comparison:

| Dimension           | KPI                         | KRI                          |
| ------------------- | --------------------------- | ---------------------------- |
| Primary purpose     | Measure performance         | Indicate risk                |
| Focus               | Achievement                 | Exposure                     |
| Question            | How well are we performing? | How much risk are we facing? |
| Typical orientation | Objective-driven            | Risk-driven                  |
| Example             | 95% controls tested         | 12 critical control failures |
| Management use      | Performance improvement     | Risk intervention            |

The two measurements should generally be considered together rather than independently.

---

# 4. KPI and KRI Relationship

A mature GRC measurement model connects performance and risk.

```text
                    BUSINESS OBJECTIVE
                           ↓
                    Performance KPI
                           ↓
                  Performance Status
                           ↓
                ┌──────────┴──────────┐
                ↓                     ↓
          Acceptable               Poor
                ↓                     ↓
          Continue             Investigate
                                      ↓
                                Risk Indicator
                                      ↓
                                  KRI Trend
                                      ↓
                              Risk Evaluation
```

This shows that poor performance can sometimes become a risk signal.

---

# 5. Example – Control Testing

Consider a control testing program.

A KPI could be:

```text
Controls Tested on Schedule
             ↓
             92%
```

This measures execution performance.

A related KRI could be:

```text
High-Risk Control Failures
             ↓
             8
```

The organization might therefore have:

```text
KPI = 92% controls tested
KRI = 8 high-risk control failures
```

The KPI says the testing program is progressing.

The KRI says there may still be significant risk exposure.

---

# 6. KPI Does Not Automatically Mean Low Risk

This is an important GRC concept.

An organization might achieve its KPI:

```text
100% of controls tested
```

while simultaneously having:

```text
15% of critical controls ineffective
```

Therefore:

```text
High KPI Performance
        ≠
Low Risk
```

Performance and risk measure different dimensions.

---

# 7. KRI Does Not Automatically Mean Poor Performance

Similarly, an organization can have a high-risk indicator because of an external event even when internal processes are performing well.

For example:

```text
KPI:
95% remediation actions completed on time

KRI:
Major increase in external cyber threats
```

The security program may be performing effectively while the external threat environment becomes more dangerous.

Therefore, KPIs and KRIs must be interpreted in context.

---

# 8. Leading and Lagging Indicators

KPIs and KRIs can also be classified as **leading** or **lagging indicators**.

### Leading Indicator

A leading indicator provides an early signal of future performance or risk.

Examples:

```text
Unpatched Critical Systems
Phishing Simulation Failure Rate
Security Training Completion
Supplier Assessment Delays
Policy Exceptions
```

### Lagging Indicator

A lagging indicator reflects an event or outcome that has already occurred.

Examples:

```text
Security Incidents
Confirmed Data Breaches
Audit Findings
Financial Losses
Control Failures
```

A mature GRC dashboard should use both.

---

# 9. Leading KRI Model

A leading KRI may work like this:

```text
Early Risk Signal
       ↓
Threshold Breached
       ↓
Risk Alert
       ↓
Investigation
       ↓
Preventive Action
```

For example:

```text
Critical Vulnerabilities
        ↓
Increasing Trend
        ↓
KRI Threshold Exceeded
        ↓
Security Escalation
        ↓
Remediation
```

The value of the KRI is that action can occur **before the risk materializes into an incident**.

---

# 10. Lagging KRI Model

A lagging indicator generally follows an event:

```text
Risk Event
    ↓
Impact
    ↓
Measurement
    ↓
KRI Reporting
    ↓
Corrective Action
```

For example:

```text
Security Incident
       ↓
Business Impact
       ↓
Incident Count / Loss
       ↓
Risk Reporting
       ↓
Corrective Measures
```

Lagging indicators remain valuable because they help organizations understand actual outcomes.

---

# 11. KPI/KRI Hierarchy

Measurements should connect to organizational objectives.

```text
Enterprise Objective
        ↓
Strategic Goal
        ↓
GRC Objective
        ↓
KPI / KRI
        ↓
Metric
        ↓
Data Source
```

For example:

```text
Objective:
Improve Cyber Resilience

        ↓

GRC Objective:
Reduce Critical Security Exposure

        ↓

KPI:
Critical Vulnerabilities Remediated on Time

        ↓

KRI:
Critical Vulnerabilities Remaining

        ↓

Data:
Vulnerability Management Platform
```

This creates traceability from strategy to measurement.

---

# 12. KPI/KRI Relationship Architecture

A more complete model is:

```text
                         STRATEGY
                            ↓
                    Business Objectives
                            ↓
                  GRC Objectives & Risks
                     ↙              ↘
                   KPI              KRI
                    ↓                ↓
              Performance        Risk Exposure
                    ↓                ↓
                    └──────┬─────────┘
                           ↓
                    Management Insight
                           ↓
                    Decision / Action
```

This is one of the most useful models for executive GRC reporting.

---

# 13. KPI/KRI Data Sources

Metrics should originate from reliable data sources.

Examples:

```text
GRC Platform
SIEM
IAM
CMDB
Vulnerability Management
ITSM
HR
Audit Management
Third-Party Risk Platform
Cloud Platforms
Security Operations
```

The data flow may be:

```text
Source Systems
      ↓
GRC Data
      ↓
Metric Calculation
      ↓
KPI / KRI
      ↓
Dashboard
```

---

# 14. KPI Calculation

A KPI should have a clearly defined calculation method.

For example:

```text
Remediation Completion Rate
=
Completed Actions
──────────────────────── × 100
Total Due Actions
```

Suppose:

```text
Completed = 90
Due = 100
```

Then:

```text
KPI = 90%
```

The calculation should be documented so that different stakeholders interpret the KPI consistently.

---

# 15. KRI Calculation

A KRI can similarly be based on measurable exposure.

For example:

```text
Critical Vulnerability Exposure
=
Number of Open Critical Vulnerabilities
```

Or:

```text
Privileged Account Risk Ratio
=
Privileged Accounts
──────────────────── × 100
Total Accounts
```

The organization should define what constitutes an acceptable or unacceptable level.

---

# 16. Thresholds

KPIs and KRIs become more useful when thresholds are established.

A simple model is:

```text
Green
   ↓
Within Target

Amber
   ↓
Attention Required

Red
   ↓
Management Action Required
```

For example:

```text
Remediation KPI

≥ 95%  → Green
90–94% → Amber
< 90%  → Red
```

Thresholds should be based on organizational objectives, risk appetite, regulatory obligations, and operational realities rather than arbitrary numbers.

---

# 17. Risk Appetite and KRI Thresholds

KRI thresholds should ideally connect to risk appetite.

```text
Risk Appetite
      ↓
Risk Tolerance
      ↓
KRI Threshold
      ↓
Monitoring
      ↓
Escalation
```

For example:

```text
Risk Appetite:
Minimal exposure to critical vulnerabilities

        ↓

KRI:
Number of open critical vulnerabilities

        ↓

Threshold:
> 5

        ↓

Escalation
```

This creates a direct connection between measurement and risk governance.

---

# 18. KPI Target vs KRI Threshold

The concepts are related but different.

```text
KPI
↓
Target

KRI
↓
Threshold
```

For example:

```text
KPI Target:
≥ 95% controls tested on schedule

KRI Threshold:
≤ 5 critical control failures
```

The KPI measures desired performance.

The KRI identifies an unacceptable risk condition.

---

# 19. KPI/KRI Trend Analysis

A single number can be misleading.

Trends provide greater insight.

```text
KPI Trend

95% → 94% → 92% → 88%
                     ↓
                 Deteriorating
```

Similarly:

```text
KRI Trend

4 → 6 → 9 → 13
             ↓
         Increasing Risk
```

Dashboards should therefore display historical trends whenever possible.

---

# 20. KPI/KRI Correlation

Organizations can compare KPIs and KRIs.

For example:

```text
Remediation KPI
95% → 93% → 90%

Critical Vulnerability KRI
5 → 8 → 14
```

This could suggest that declining remediation performance is associated with increasing vulnerability exposure.

However, **correlation should not automatically be interpreted as causation**.

Additional analysis may be required.

---

# 21. KPI/KRI Relationship Matrix

A useful GRC model can map KPIs to related KRIs.

| KPI                            | Related KRI                |
| ------------------------------ | -------------------------- |
| Control Testing Completion     | Control Failures           |
| Remediation Completion         | Overdue High-Risk Findings |
| Security Training Completion   | Phishing Failure Rate      |
| Supplier Assessments Completed | High-Risk Suppliers        |
| Patch Compliance               | Critical Vulnerabilities   |
| Audit Plan Completion          | High-Severity Findings     |
| Policy Review Completion       | Policy Exceptions          |

This allows management to see both **activity performance and resulting risk exposure**.

---

# 22. Example – Security Awareness

Consider security awareness.

### KPI

```text
Training Completion Rate = 97%
```

### KRI

```text
Phishing Simulation Failure Rate = 14%
```

The KPI appears strong, but the KRI suggests that human-related security exposure remains significant.

The combined interpretation is:

```text
Training Completion
        ↓
       97%
        +
Phishing Failure Rate
        ↓
       14%
        ↓
Further Analysis Required
```

This is more informative than showing the KPI alone.

---

# 23. Example – Third-Party Risk

A third-party GRC dashboard might show:

```text
KPI:
Supplier Assessments Completed = 96%

KRI:
High-Risk Suppliers = 18%

KRI:
Suppliers With Overdue Remediation = 11%
```

This tells management that the assessment program is operating effectively, but supplier risk remains material.

---

# 24. Example – Audit

An audit function could track:

```text
KPI:
Audit Plan Completion = 94%

KPI:
Audit Reports Issued on Time = 91%

KRI:
High-Severity Findings = 12

KRI:
Overdue High-Severity Findings = 7
```

This provides both:

```text
Audit Performance
        +
Risk Exposure
```

---

# 25. KPI/KRI Cascade

Metrics can cascade through organizational levels.

```text
Enterprise
   ↓
Business Unit
   ↓
Function
   ↓
Process
   ↓
Control
```

For example:

```text
Enterprise KPI
Cybersecurity Compliance = 94%

        ↓

Business Unit KPI
Control Testing = 96%

        ↓

Process KPI
Access Reviews = 98%

        ↓

Control KRI
Privileged Access Exceptions = 7
```

This allows executives to move from a high-level view into operational detail.

---

# 26. Executive vs Operational Metrics

Different audiences need different levels of detail.

### Executive

```text
Overall Risk
Major KRIs
Strategic KPIs
Trend
Top Exceptions
Major Findings
```

### Management

```text
Business Unit Performance
Risk Trends
Control Effectiveness
Remediation
Compliance Status
```

### Operational

```text
Individual Controls
Evidence
Tickets
Exceptions
Testing Results
Technical Findings
```

The same underlying data can therefore support multiple dashboards.

---

# 27. KPI/KRI Relationship to the Three Lines

The Three Lines can use KPIs and KRIs differently.

```text
First Line
   ↓
Operational KPIs / KRIs

Second Line
   ↓
Risk & Compliance KPIs / KRIs

Third Line
   ↓
Audit & Assurance KPIs / KRIs
```

Together:

```text
             GOVERNING BODY
                    ↑
                    │
              GRC DASHBOARD
                    ↑
       ┌────────────┼────────────┐
       │            │            │
    First Line   Second Line  Third Line
       │            │            │
    Operations   Risk/GRC      Audit
```

This provides a multi-perspective view of organizational performance and risk.

---

# 28. KPI/KRI Relationship to Risk Management

The relationship can be integrated into the risk lifecycle:

```text
Risk Identification
       ↓
Risk Assessment
       ↓
Risk Appetite
       ↓
KRI Definition
       ↓
Monitoring
       ↓
Threshold Breach
       ↓
Risk Response
```

KPIs can support the execution of the risk response:

```text
Risk Treatment
      ↓
Treatment KPI
      ↓
Implementation Performance
```

---

# 29. KPI/KRI Relationship to Controls

Controls can generate both performance and risk measurements.

```text
Control
  ↓
Control Operation
  ↓
Control Evidence
  ↓
Control Testing
  ↓
┌───────────────┴───────────────┐
↓                               ↓
KPI                             KRI
Control Testing                Control Failure
Completion                     Exposure
```

This helps connect control management with enterprise risk reporting.

---

# 30. KPI/KRI Relationship to Compliance

Compliance measurement can similarly use both.

```text
Compliance Program
       ↓
Requirements
       ↓
Controls
       ↓
Assessments
       ↓
┌───────────────┴───────────────┐
↓                               ↓
KPI                             KRI
Assessment Completion           Compliance Gaps
Evidence Coverage               Regulatory Exposure
```

This provides management with both program performance and compliance risk.

---

# 31. KPI/KRI Relationship to Remediation

Remediation is another useful example.

```text
Findings
   ↓
Remediation Actions
   ↓
KPI
Actions Closed on Time
   ↓
KRI
Overdue High-Risk Findings
```

For example:

```text
KPI = 93% actions closed on time
KRI = 9 high-risk findings overdue
```

The organization may be performing reasonably well overall while still having a concentrated high-risk problem.

---

# 32. KPI/KRI Relationship Model

The complete model can therefore be represented as:

```text
                 BUSINESS OBJECTIVES
                         ↓
                  GRC OBJECTIVES
                         ↓
              ┌──────────┴──────────┐
              ↓                     ↓
             KPI                   KRI
              ↓                     ↓
        Performance              Exposure
              ↓                     ↓
        Target Status          Risk Threshold
              └──────────┬──────────┘
                         ↓
                  Management Insight
                         ↓
                   Decision / Action
                         ↓
                    GRC Outcome
```

This is the central concept of the KPI and KRI relationship model.

---

# 33. Common KPI Design Problems

Poorly designed KPIs can create misleading information.

Common problems include:

### Too many KPIs

```text
100+ Metrics
      ↓
Management Overload
```

### Activity-only KPIs

```text
Number of assessments completed
```

This may measure activity without demonstrating effectiveness.

### No target

```text
95%
```

Without a target, it is difficult to determine whether 95% is good or bad.

### No trend

A single measurement provides limited context.

### Poor data quality

A highly sophisticated dashboard is useless if the underlying data is inaccurate.

---

# 34. Common KRI Design Problems

KRIs can also be poorly designed.

Examples include:

* measuring events rather than risk exposure
* thresholds that are too high or too low
* indicators that change too slowly
* indicators that cannot trigger meaningful action
* excessive numbers of KRIs
* no connection to risk appetite
* unreliable source data

A useful KRI should provide **decision-relevant information**.

---

# 35. Characteristics of a Good KPI

A strong KPI should be:

```text
Relevant
Measurable
Consistent
Understandable
Actionable
Time-Bound
Comparable
Reliable
```

It should have:

```text
Definition
Owner
Calculation
Target
Frequency
Data Source
Reporting Audience
Escalation Criteria
```

---

# 36. Characteristics of a Good KRI

A strong KRI should have:

```text
Risk Link
Risk Owner
Definition
Data Source
Measurement Method
Threshold
Frequency
Trend
Escalation Rule
Response
```

The most important characteristic is that the KRI should provide a meaningful indication of **risk exposure or change**.

---

# 37. KPI/KRI Governance

Metrics themselves require governance.

A simple model is:

```text
Metric Definition
       ↓
Metric Owner
       ↓
Data Source
       ↓
Calculation
       ↓
Validation
       ↓
Approval
       ↓
Reporting
       ↓
Review
```

This prevents different departments from calculating the same metric differently.

---

# 38. Metric Dictionary

A mature GRC organization should maintain a metric dictionary.

Example:

| Field      | Example                                  |
| ---------- | ---------------------------------------- |
| Metric     | Remediation Completion Rate              |
| Type       | KPI                                      |
| Owner      | GRC Manager                              |
| Definition | Percentage of due actions closed on time |
| Formula    | Completed on time / Total due            |
| Target     | ≥ 95%                                    |
| Frequency  | Monthly                                  |
| Source     | GRC Platform                             |
| Audience   | Security Leadership                      |
| Escalation | < 90%                                    |

The same concept can be applied to KRIs.

---

# 39. KPI/KRI Data Governance

The data supporting metrics should have:

```text
Defined Ownership
Data Quality Controls
Source Identification
Calculation Logic
Change Management
Validation
Auditability
```

This ensures that dashboards are defensible.

---

# 40. From Metrics to Decisions

The most important relationship is:

```text
Data
 ↓
Metric
 ↓
KPI / KRI
 ↓
Interpretation
 ↓
Insight
 ↓
Decision
 ↓
Action
```

For example:

```text
Critical Vulnerabilities
        ↓
KRI = 17
        ↓
Threshold = 5
        ↓
Red Status
        ↓
Risk Exposure Increasing
        ↓
Management Escalation
        ↓
Additional Remediation Resources
```

This demonstrates why GRC dashboards should be designed around **decisions**, not simply visual presentation.

---

# 41. Practical Executive KPI/KRI Model

An executive dashboard might use a structure such as:

```text
┌────────────────────────────────────────────┐
│             GRC EXECUTIVE VIEW             │
├────────────────────────────────────────────┤
│                                            │
│ Strategic KPIs                             │
│ ─────────────────────────────              │
│ Compliance Completion       96%             │
│ Control Testing             94%             │
│ Remediation Completion      91%             │
│                                            │
│ Strategic KRIs                             │
│ ─────────────────────────────              │
│ High Risks                  12             │
│ Critical Findings            5             │
│ High-Risk Suppliers         18             │
│                                            │
│ Trend:       ↑ Risk                       │
│ Overall Status: Attention Required        │
└────────────────────────────────────────────┘
```

The exact measurements should be tailored to the organization's objectives and risk profile.

---

# 42. KPI/KRI Relationship – Complete Visual Model

The overall architecture can be summarized as:

```text
                         STRATEGY
                            ↓
                  BUSINESS OBJECTIVES
                            ↓
                     GRC OBJECTIVES
                            ↓
             ┌──────────────┴──────────────┐
             ↓                             ↓
            KPI                           KRI
             ↓                             ↓
      PERFORMANCE DATA               RISK DATA
             ↓                             ↓
       Target / Goal                 Threshold
             ↓                             ↓
       Performance Status            Risk Status
             └──────────────┬──────────────┘
                            ↓
                     GRC DASHBOARD
                            ↓
                     MANAGEMENT INSIGHT
                            ↓
                     DECISION / ACTION
                            ↓
                       GRC OUTCOME
```

---

# 43. Key GRC Takeaways

The **KPI and KRI Relationship Model** demonstrates how GRC measurement should connect organizational objectives, performance, risk exposure, and management decisions.

The most important principles are:

1. **KPIs measure performance against objectives.**
2. **KRIs indicate risk exposure or changing risk conditions.**
3. **KPIs and KRIs should be interpreted together.**
4. **High KPI performance does not automatically mean low risk.**
5. **KRIs should connect to risk appetite and tolerance where appropriate.**
6. **Leading indicators provide early warning, while lagging indicators measure realized outcomes.**
7. **Metrics should have clearly defined calculations, owners, targets, thresholds, and data sources.**
8. **Trends are generally more informative than isolated measurements.**
9. **KPI and KRI relationships can reveal connections between operational performance and risk exposure.**
10. **Metrics should cascade from enterprise objectives to business units, processes, and controls.**
11. **Different audiences require different levels of GRC measurement detail.**
12. **Metric data quality and governance are essential for trustworthy dashboards.**
13. **The purpose of GRC metrics is not simply reporting; it is enabling better decisions.**
14. **A mature GRC measurement model converts data into insight, insight into decisions, and decisions into action.**

Ultimately:

```text
                    DATA
                      ↓
                   METRICS
                      ↓
              ┌───────┴───────┐
              ↓               ↓
             KPI             KRI
              ↓               ↓
        Performance         Risk
              └───────┬───────┘
                      ↓
                   INSIGHT
                      ↓
                   DECISION
                      ↓
                    ACTION
                      ↓
                   OUTCOME
```

A strong GRC dashboard therefore does not merely tell management **what happened**. It helps explain **how the organization is performing, where risk is changing, and where management attention or action may be required**.



