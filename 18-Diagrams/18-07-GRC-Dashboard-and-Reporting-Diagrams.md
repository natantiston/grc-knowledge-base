# 18.7 GRC Dashboard and Reporting Diagrams

## Part 1 – Introduction to GRC Dashboards and Reporting

A **GRC dashboard** provides a visual representation of governance, risk, compliance, control, audit, and remediation information.

The purpose is to transform large amounts of GRC data into information that different stakeholders can quickly understand and use for decision-making.

A simple reporting flow is:

```text
GRC Data
    ↓
Data Processing
    ↓
Metrics
    ↓
Analysis
    ↓
Dashboard
    ↓
Management Decision
    ↓
Action
```

A GRC dashboard should answer important questions such as:

```text
What are our most significant risks?
Are controls operating effectively?
Where are we not compliant?
Which findings are overdue?
Which risks are increasing?
Which vendors represent significant exposure?
Which actions require management attention?
```

A basic GRC reporting architecture can be represented as:

```text
                         GRC DATA
                            ↓
        ┌───────────────────┼───────────────────┐
        ↓                   ↓                   ↓
       Risk              Compliance           Audit
        ↓                   ↓                   ↓
     Controls             Issues            Findings
        ↓                   ↓                   ↓
        └───────────────────┼───────────────────┘
                            ↓
                       DATA ANALYSIS
                            ↓
                         METRICS
                            ↓
                       DASHBOARDS
                            ↓
                 MANAGEMENT REPORTING
                            ↓
                     DECISION / ACTION
```

### Why GRC Dashboards Matter

GRC environments can contain thousands of individual records.

For example:

```text
5,000+ Assets
1,500+ Controls
2,000+ Risks
10,000+ Evidence Records
500+ Audit Findings
300+ Vendors
```

A management team cannot efficiently review every individual record.

The dashboard therefore provides a summarized view.

```text
Thousands of Records
        ↓
Data Aggregation
        ↓
Key Metrics
        ↓
Visual Dashboard
        ↓
Management Understanding
```

The objective is not simply to make GRC information look attractive.

The objective is to make information **useful for decisions**.

### From Data to Decision

A mature reporting model follows this progression:

```text
Data
 ↓
Information
 ↓
Insight
 ↓
Decision
 ↓
Action
```

For example:

```text
Data:
14 overdue critical findings

        ↓

Information:
Critical findings increased by 40%

        ↓

Insight:
Remediation capacity is insufficient

        ↓

Decision:
Allocate additional remediation resources

        ↓

Action:
Assign additional technical teams
```

This demonstrates the real purpose of GRC reporting.

### Different Stakeholders Need Different Dashboards

There should not necessarily be one dashboard for everyone.

Different stakeholders require different information.

```text
Board
 ↓
Strategic Risk Dashboard

Executive Management
 ↓
Enterprise GRC Dashboard

CISO / Security Leadership
 ↓
Cyber Risk Dashboard

GRC Team
 ↓
Operational GRC Dashboard

Control Owner
 ↓
Control Performance Dashboard

Internal Audit
 ↓
Audit Dashboard
```

For example, a board member may need:

```text
Top Enterprise Risks
Risk Trend
Regulatory Exposure
Major Control Failures
Critical Findings
Strategic Risk Treatment
```

While a GRC analyst may need:

```text
Open Risks
Overdue Assessments
Control Testing
Evidence Collection
Exceptions
Issues
Remediation Tasks
```

The information is therefore presented at different levels.

### Strategic vs Operational Reporting

GRC reporting can generally be divided into two major categories.

```text
GRC Reporting
      ↓
 ┌────┴────┐
 ↓         ↓
Strategic Operational
```

**Strategic reporting** focuses on management decisions.

```text
Strategic
   ↓
Enterprise Risk
Regulatory Exposure
Major Findings
Risk Trends
Business Impact
```

**Operational reporting** focuses on execution.

```text
Operational
   ↓
Tasks
Assessments
Evidence
Control Testing
Issues
Remediation
```

A useful hierarchy is:

```text
                    BOARD
                      ↓
             Strategic Dashboard
                      ↓
                EXECUTIVES
                      ↓
             Management Dashboard
                      ↓
                GRC TEAM
                      ↓
             Operational Dashboard
                      ↓
              CONTROL OWNERS
                      ↓
                Task Views
```

### Risk Dashboard

A risk dashboard provides visibility into the organization's risk profile.

A basic risk dashboard might contain:

```text
Total Risks
High Risks
Critical Risks
Increasing Risks
Decreasing Risks
Overdue Risk Reviews
Risk Acceptance
Residual Risk
Risk Treatment Status
```

A simplified diagram is:

```text
                  RISK DASHBOARD
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
   Risk Exposure    Risk Trend     Risk Treatment
        ↓               ↓               ↓
   Critical Risks   Increasing     Open Actions
   High Risks       Stable         Completed
   Medium Risks     Decreasing     Overdue
```

### Risk Heat Map

One of the most common GRC visualizations is the risk heat map.

```text
Impact
  ↑
  │  🟨 🟧 🟥 🟥
  │  🟨 🟨 🟧 🟥
  │  🟩 🟨 🟧 🟥
  │  🟩 🟩 🟨 🟧
  └────────────────→ Likelihood
```

The heat map helps management quickly identify areas requiring attention.

The underlying relationship is:

```text
Likelihood
      +
Impact
      ↓
Risk Rating
```

The dashboard can then display:

```text
Critical
High
Medium
Low
```

### Risk Trend Reporting

A dashboard can also show whether risk is increasing or decreasing.

```text
Risk Level
   ↑
High │       ●
     │      / \
Med  │  ●──●   ●
     │ /
Low  │●
     └──────────────→ Time
```

The important question is not only:

> What is our current risk?

but also:

> **Is our risk getting better or worse?**

For example:

```text
Current Risk:
High

Trend:
Increasing

Management Meaning:
Immediate attention required
```

### Compliance Dashboard

A compliance dashboard provides visibility into the organization's compliance position.

Typical metrics include:

```text
Total Requirements
Compliant
Partially Compliant
Non-Compliant
Overdue Assessments
Open Compliance Issues
Upcoming Regulatory Deadlines
```

A simplified structure is:

```text
                 COMPLIANCE
                     ↓
       ┌─────────────┼─────────────┐
       ↓             ↓             ↓
   Compliant     Partial       Non-Compliant
       ↓             ↓             ↓
      80%           15%            5%
```

This gives management an immediate view of compliance posture.

### Control Dashboard

A control dashboard focuses on control performance.

```text
Controls
   ↓
 ┌─┴─────────────────────┐
 ↓                       ↓
Effective             Ineffective
 ↓                       ↓
Operating             Remediation
```

Typical metrics include:

```text
Total Controls
Controls Tested
Effective Controls
Ineffective Controls
Testing Overdue
Evidence Missing
Control Exceptions
```

For example:

```text
Control Population: 1,000

Tested:              920
Effective:           870
Ineffective:          50
Not Tested:            80
```

The dashboard should allow the user to understand why controls are ineffective.

```text
Ineffective Control
       ↓
Reason
       ↓
Finding
       ↓
Remediation
       ↓
Validation
```

### Audit Dashboard

An audit dashboard can provide information such as:

```text
Open Audits
Completed Audits
Open Findings
Critical Findings
Overdue Findings
Finding Aging
Remediation Status
```

A simple flow is:

```text
Audit
 ↓
Findings
 ↓
Severity
 ↓
Remediation
 ↓
Closure
```

Management can then see where audit issues remain unresolved.

### Issue and Remediation Dashboard

A remediation dashboard focuses on outstanding actions.

```text
Open Issues
     ↓
Severity
     ↓
Age
     ↓
Owner
     ↓
Due Date
     ↓
Status
```

A useful visualization is:

```text
Critical Issues
████████████

High Issues
████████

Medium Issues
████

Low Issues
██
```

The dashboard should emphasize **overdue and high-impact issues**, rather than simply showing the total number of issues.

### Third-Party Risk Dashboard

Third-party risk dashboards provide visibility into supplier and vendor exposure.

Metrics may include:

```text
Total Vendors
Critical Vendors
High-Risk Vendors
Assessments Completed
Assessments Overdue
Open Vendor Findings
Contract Exceptions
Vendor Risk Trend
```

A simple architecture is:

```text
Vendors
   ↓
Risk Classification
   ↓
Assessment
   ↓
Findings
   ↓
Remediation
   ↓
Monitoring
```

### Executive GRC Dashboard

An executive dashboard should be highly summarized.

For example:

```text
             ENTERPRISE GRC
                  DASHBOARD

Enterprise Risk       🟠
Compliance            🟢
Control Effectiveness 🟠
Audit Findings        🔴
Third-Party Risk      🟠
Policy Compliance     🟢
```

The executive should be able to identify the most important areas within seconds.

The dashboard should answer:

```text
What is the current situation?
What changed?
Why did it change?
What is the business impact?
What needs attention?
Who owns the action?
```

### Dashboard Drill-Down

A good dashboard should allow users to move from summary to detail.

```text
Executive Dashboard
        ↓
Risk Category
        ↓
Specific Risk
        ↓
Risk Assessment
        ↓
Related Controls
        ↓
Control Evidence
        ↓
Finding
        ↓
Remediation
```

For example:

```text
High Cyber Risk
      ↓
Cloud Security Risk
      ↓
Affected Business Service
      ↓
Affected Asset
      ↓
Control Failure
      ↓
Finding
      ↓
Remediation Ticket
```

This is called **drill-down capability**.

### GRC Reporting Hierarchy

A mature reporting architecture can therefore be represented as:

```text
                         RAW DATA
                            ↓
                       GRC RECORDS
                            ↓
                       DATA QUALITY
                            ↓
                         METRICS
                            ↓
                       ANALYTICS
                            ↓
                     VISUALIZATION
                            ↓
                     DASHBOARD
                            ↓
                       REPORTING
                            ↓
                      MANAGEMENT
                            ↓
                        DECISION
                            ↓
                         ACTION
```

The key principle is:

> **A GRC dashboard should not merely display information. It should help stakeholders understand risk, identify exceptions, prioritize action, and make informed decisions.**

The most effective dashboards therefore combine **current status, trends, severity, ownership, business impact, and actionable next steps** rather than simply presenting large quantities of GRC data.

## 18.7 GRC Dashboard and Reporting Diagrams

### Part 2 – GRC Dashboard Metrics, KPIs, KRIs, and Visualization

A GRC dashboard becomes useful when the underlying data is converted into meaningful **metrics, Key Performance Indicators (KPIs), and Key Risk Indicators (KRIs)**.

The basic relationship is:

```text
GRC Data
   ↓
Metrics
   ↓
KPIs / KRIs
   ↓
Visualization
   ↓
Dashboard
   ↓
Decision
```

### Metrics

A **metric** is a measurable value that describes a condition, activity, or result.

Examples include:

```text
Number of Open Risks
Number of Controls
Number of Audit Findings
Number of Vendors
Number of Exceptions
Number of Overdue Actions
```

For example:

```text
Open Risks = 245
```

This tells us the quantity, but not necessarily whether the situation is good or bad.

Therefore, metrics often need additional context.

```text
Open Risks
     +
Previous Period
     +
Target
     +
Risk Threshold
     ↓
Meaningful Insight
```

For example:

```text
Open Risks:
245

Previous Month:
180

Increase:
36%

Management Interpretation:
Risk exposure is increasing.
```

### KPI – Key Performance Indicator

A **KPI** measures performance against a defined objective or target.

For example:

```text
Control Testing Completion

Target: 95%
Actual: 92%

KPI Status:
Below Target
```

The basic structure is:

```text
Objective
   ↓
Target
   ↓
Actual Performance
   ↓
Variance
   ↓
KPI Status
```

Common GRC KPIs include:

```text
Control Testing Completion %
Policy Review Completion %
Risk Assessment Completion %
Audit Finding Closure %
Vendor Assessment Completion %
Security Training Completion %
Remediation SLA Compliance %
```

### KRI – Key Risk Indicator

A **KRI** is designed to provide an indication that risk exposure may be increasing or decreasing.

Examples include:

```text
Number of Critical Vulnerabilities
Number of Privileged Accounts
Number of High-Risk Vendors
Number of Overdue Critical Findings
Number of Security Exceptions
Number of Failed Controls
```

The relationship can be represented as:

```text
Risk Driver
    ↓
Indicator
    ↓
Threshold
    ↓
Risk Signal
    ↓
Management Action
```

For example:

```text
Privileged Accounts

Normal:       < 100
Warning:      100–150
Critical:     > 150
```

If the number increases above the defined threshold:

```text
KRI Threshold Breach
        ↓
Alert
        ↓
Risk Review
        ↓
Management Action
```

### KPI vs KRI

KPIs and KRIs serve different purposes.

```text
KPI
 ↓
Are we achieving our objectives?

KRI
 ↓
Is our risk exposure changing?
```

For example:

```text
KPI:
95% of controls tested on time

KRI:
Number of critical control failures
```

A GRC dashboard may contain both.

```text
              GRC DASHBOARD
                    ↓
          ┌─────────┴─────────┐
          ↓                   ↓
         KPI                 KRI
          ↓                   ↓
     Performance          Risk Exposure
```

### KPI Calculation

Many GRC KPIs are percentage-based.

For example:

```text
Completed Controls
────────────────── × 100
Total Controls
```

If:

```text
Completed = 920
Total = 1,000
```

Then:

```text
KPI = 92%
```

The important point is that the percentage should always have a defined **target**.

```text
Actual = 92%
Target = 95%

Variance = -3 percentage points
```

### KRI Thresholds

KRIs often use thresholds.

```text
             KRI THRESHOLD

Green       Normal
   ↓
Yellow      Warning
   ↓
Orange      Elevated
   ↓
Red         Critical
```

For example:

```text
Overdue Critical Findings

Green:      0–2
Yellow:     3–5
Orange:     6–10
Red:        >10
```

The thresholds should be defined based on the organization's risk appetite and business context.

### Risk Appetite and Dashboard Thresholds

Dashboard indicators should connect to risk appetite.

```text
Risk Appetite
      ↓
Risk Tolerance
      ↓
Threshold
      ↓
KRI
      ↓
Dashboard
      ↓
Alert
```

For example:

```text
Risk Appetite:
Low tolerance for critical regulatory findings

        ↓

KRI:
Open Critical Compliance Findings

        ↓

Threshold:
> 0

        ↓

Dashboard:
RED
```

This creates a direct connection between **risk strategy and operational monitoring**.

### Traffic-Light Indicators

One of the simplest GRC dashboard visualizations is the traffic-light indicator.

```text
🟢 Green
Within Target

🟡 Yellow
Warning / Attention Required

🔴 Red
Outside Tolerance / Critical
```

For example:

```text
Control Effectiveness     🟢
Risk Exposure             🟡
Audit Findings            🔴
Vendor Risk               🟡
Compliance                🟢
```

However, color should not be the only indicator.

A more accessible representation is:

```text
GREEN   – Within Target
AMBER   – Attention Required
RED     – Critical / Outside Tolerance
```

### Gauge Charts

A gauge can show progress against a target.

```text
        CONTROL TESTING

       ┌───────────────┐
       │      92%      │
       │       ↑       │
       └───────────────┘

Target: 95%
```

Gauge charts can be useful for a small number of high-level indicators.

They become less effective when a dashboard contains dozens of gauges.

### Bar Charts

Bar charts are useful for comparing categories.

```text
Open Findings by Severity

Critical  █████
High      ███████████
Medium    ███████████████
Low       ███████
```

This allows management to compare categories quickly.

### Trend Charts

Trend charts show how a metric changes over time.

```text
Open High-Risk Findings

Count
 ↑
50│       ●
40│     ●   ●
30│   ●       ●
20│ ●           ●
10│
 0└──────────────────→ Time
```

A trend can reveal:

```text
Increasing
Stable
Decreasing
Volatile
```

This is often more valuable than a single current number.

### Aging Analysis

GRC dashboards should often show how long issues have remained open.

```text
Finding Aging

0–30 days       █████████████
31–60 days      ████████
61–90 days      █████
91–180 days     ███
180+ days       ██
```

Aging analysis helps identify issues that may be becoming chronic.

```text
Finding
   ↓
Age
   ↓
SLA
   ↓
Overdue?
   ↓
Escalation
```

### Risk Distribution

A dashboard can show the distribution of risks.

```text
Critical     ███
High         █████████
Medium       ███████████████
Low          ███████████████████
```

But total counts alone can be misleading.

For example:

```text
100 Low Risks
```

may not be more concerning than:

```text
2 Critical Risks
```

Therefore dashboards should emphasize **risk severity and business impact**, not simply volume.

### Risk Concentration

A more advanced dashboard can identify where risks are concentrated.

```text
Risk by Business Unit

Finance       █████████
Technology    ███████████████
Operations    █████
HR            ██
Marketing     ███
```

This can help management identify concentration.

For example:

```text
Technology
   ↓
60% of High Risks
   ↓
Risk Concentration
   ↓
Management Attention
```

### Risk by Business Impact

Risk dashboards should also consider business impact.

```text
Risk
 ↓
Business Service
 ↓
Criticality
 ↓
Potential Impact
```

A dashboard may therefore display:

```text
Business Service       Risk Level

Customer Platform      🔴 High
Billing System         🔴 High
Internal HR System     🟢 Low
Marketing Portal       🟡 Medium
```

This gives risk information business context.

### Control Effectiveness Visualization

Control performance can be visualized as:

```text
Control Status

Effective       █████████████████
Partially       █████
Ineffective     ██
Not Tested      ███
```

A useful dashboard should allow drill-down:

```text
Ineffective Controls
       ↓
Control
       ↓
Risk
       ↓
Finding
       ↓
Owner
       ↓
Remediation
```

### Compliance Status Visualization

Compliance can be represented by requirement status.

```text
Compliance Status

Compliant        ███████████████████
Partial          █████
Non-Compliant    ██
Not Assessed     ███
```

The dashboard can then drill into:

```text
Framework
   ↓
Requirement
   ↓
Control
   ↓
Evidence
   ↓
Assessment
```

### Audit Finding Visualization

Audit findings can be presented by severity and status.

```text
                OPEN       CLOSED

Critical        ███          █
High            ███████      ████
Medium          █████████    ███████
Low             ███          ████████
```

Another useful metric is the closure rate.

```text
Closed Findings
──────────────── × 100
Total Findings
```

For example:

```text
Closed = 180
Total = 200

Closure Rate = 90%
```

### Exception Dashboard

Exceptions should not simply be counted.

They should be analyzed by:

```text
Severity
Age
Owner
Business Unit
Expiration Date
Risk
Control
Approval Status
```

A useful view is:

```text
Exception Status

Active       █████████
Expiring     ███
Expired      ██
Pending      ████
```

An expired exception should generate attention.

```text
Exception
    ↓
Expiration Date
    ↓
Expired?
  ↙     ↘
No       Yes
 ↓        ↓
Monitor  Escalate
```

### Vendor Risk Dashboard

Vendor dashboards can show risk concentration.

```text
Vendor Risk

Critical      ██
High          ███████
Medium        ███████████
Low           ███████████████
```

Additional indicators may include:

```text
Critical Vendors
Overdue Assessments
Open Vendor Findings
Contract Exceptions
High-Risk Vendors Without Current Assessment
```

A particularly useful KRI is:

```text
Critical Vendors Without Current Assessment
```

because it directly identifies potential exposure.

### Dashboard Filters

Users should be able to filter dashboard data.

Common filters include:

```text
Business Unit
Region
Risk Category
Risk Level
Framework
Control Owner
Risk Owner
Vendor
Date
Status
Severity
```

For example:

```text
Enterprise Dashboard
        ↓
Region = Europe
        ↓
Business Unit = Technology
        ↓
Risk Level = High
        ↓
Open Risks
```

This transforms a general dashboard into a focused analytical tool.

### Dashboard Drill-Through

A mature dashboard allows users to move from summary to source records.

```text
Dashboard
    ↓
Metric
    ↓
Category
    ↓
Record
    ↓
Evidence
```

For example:

```text
Critical Findings = 12
        ↓
Click
        ↓
12 Findings
        ↓
Select Finding
        ↓
Finding Details
        ↓
Related Control
        ↓
Evidence
```

This creates traceability.

### Dashboard Data Quality

Dashboard accuracy depends on data quality.

```text
Source Systems
      ↓
Data Validation
      ↓
GRC Database
      ↓
Data Quality Checks
      ↓
Dashboard
```

If source information is incomplete:

```text
Poor Data
   ↓
Incorrect Metric
   ↓
Incorrect Dashboard
   ↓
Incorrect Decision
```

Therefore:

> **A visually impressive dashboard with poor-quality data is still a poor GRC dashboard.**

### Leading and Lagging Indicators

GRC dashboards should distinguish between **leading** and **lagging indicators**.

A leading indicator provides an early signal.

```text
Leading Indicators

Unpatched Critical Assets
Increasing Exceptions
Overdue Risk Reviews
Privileged Access Growth
Vendor Assessment Delays
```

A lagging indicator reflects an event that has already occurred.

```text
Lagging Indicators

Security Incidents
Audit Findings
Regulatory Violations
Control Failures
Data Breaches
```

The relationship is:

```text
Leading Indicator
       ↓
Early Warning
       ↓
Preventive Action
       ↓
Reduced Risk

Lagging Indicator
       ↓
Event Occurred
       ↓
Investigation
       ↓
Corrective Action
```

A mature GRC dashboard should ideally contain both.

### Executive Dashboard Design Principles

An executive GRC dashboard should be:

```text
Simple
Relevant
Accurate
Actionable
Timely
Consistent
Traceable
```

It should avoid:

```text
Too Much Detail
Too Many Charts
Unnecessary Metrics
Unexplained Numbers
Ambiguous Colors
Outdated Data
```

The dashboard should prioritize:

```text
What Matters Most?
       ↓
What Changed?
       ↓
Why?
       ↓
What Is the Impact?
       ↓
What Action Is Required?
```

### GRC Dashboard Design Model

A complete dashboard architecture can be represented as:

```text
                     GRC DATA
                        ↓
                 DATA QUALITY
                        ↓
                    METRICS
                        ↓
              ┌─────────┴─────────┐
              ↓                   ↓
             KPI                 KRI
              ↓                   ↓
       Performance             Risk Signal
              └─────────┬─────────┘
                        ↓
                  VISUALIZATION
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
      Trend           Status          Risk Map
        ↓               ↓               ↓
        └───────────────┼───────────────┘
                        ↓
                    DASHBOARD
                        ↓
                    DRILL-DOWN
                        ↓
                 ROOT CAUSE / DATA
                        ↓
                    MANAGEMENT
                        ↓
                      ACTION
```

The key principle is:

> **GRC dashboards should convert data into actionable intelligence. KPIs show whether objectives are being achieved, KRIs provide early warning of changing risk exposure, and visualizations make patterns, trends, exceptions, and priorities easier to understand.**

A mature GRC dashboard therefore moves beyond **"What do we have?"** and answers the more important questions:

```text
What is happening?
        ↓
Why is it happening?
        ↓
How significant is it?
        ↓
Is it within our tolerance?
        ↓
What should we do?
        ↓
Who should do it?
        ↓
When should it be completed?
```



