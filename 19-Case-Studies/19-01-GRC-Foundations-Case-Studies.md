# 19.1 GRC Foundations Case Studies

## Part 1 – Building a GRC Program from Scratch

## 1. Case Study Overview

This case study examines how an organization can establish a **Governance, Risk, and Compliance (GRC) program from the ground up** when its existing risk, compliance, cybersecurity, audit, and control activities are fragmented.

The objective is to demonstrate how a GRC professional moves from an unstructured environment toward an organized, risk-based, and measurable GRC operating model.

The case is fictional but designed to reflect a realistic enterprise environment.

---

# 2. Organization Profile

### Company

**AtlasConnect Telecommunications Group**

### Industry

Telecommunications and digital services

### Geographic Presence

* Headquarters: Europe
* Operations: Europe and Middle East
* Customers: approximately 8 million
* Employees: approximately 7,500

### Technology Environment

* Hybrid cloud infrastructure
* Microsoft Azure
* Enterprise data centers
* 5G/mobile network infrastructure
* Customer-facing digital applications
* CRM and billing platforms
* Enterprise ERP
* Identity and access management
* Security operations center
* Third-party technology providers

---

# 3. Initial Situation

AtlasConnect has grown rapidly through acquisitions.

Each business unit developed its own approach to:

* risk management;
* cybersecurity;
* compliance;
* vendor management;
* internal controls;
* audit preparation;
* security policies.

As a result, the organization has several disconnected processes.

```text
Business Unit A
      |
      +-- Risk Register
      +-- Security Controls
      +-- Compliance Process

Business Unit B
      |
      +-- Separate Risk Register
      +-- Different Controls
      +-- Different Reporting

Business Unit C
      |
      +-- Spreadsheet-Based Compliance
      +-- Local Policies
      +-- Manual Evidence
```

There is no consistent enterprise-wide GRC framework.

---

# 4. Management Problem

The Board asks the Chief Risk Officer and CISO:

> **"What are our most significant enterprise risks, and are our controls actually managing them?"**

Management discovers that answering this question is difficult.

Different departments provide different numbers.

For example:

| Area                | Reported Status        |
| ------------------- | ---------------------- |
| Enterprise Risk     | 34 high risks          |
| Cybersecurity       | 18 high risks          |
| Compliance          | 27 significant gaps    |
| Internal Audit      | 42 open findings       |
| Third Parties       | 16 high-risk suppliers |
| Security Operations | 11 critical exposures  |

The problem is not necessarily that the organization has too many risks.

The problem is that **there is no common GRC structure for understanding them**.

---

# 5. Initial GRC Maturity Assessment

A preliminary assessment produces the following result:

| GRC Capability      | Maturity |
| ------------------- | -------: |
| Governance          |      2/5 |
| Risk Management     |      2/5 |
| Compliance          |      2/5 |
| Controls            |      2/5 |
| Audit & Assurance   |      3/5 |
| Third-Party Risk    |      1/5 |
| GRC Technology      |      1/5 |
| Metrics & Reporting |      1/5 |
| Overall             |  **2/5** |

The organization is therefore classified as **developing / partially defined**.

---

# 6. Key GRC Problems

The assessment identifies ten major problems.

### 1. Fragmented risk registers

Different departments use different risk methodologies.

### 2. Inconsistent risk scoring

One department defines a "High" risk differently from another.

### 3. Duplicate controls

Several teams operate controls addressing the same risk.

### 4. Missing control ownership

Some controls have no clearly accountable owner.

### 5. Manual compliance tracking

Regulatory requirements are tracked primarily through spreadsheets.

### 6. Poor evidence management

Evidence is stored across email, SharePoint, local drives, and ticketing systems.

### 7. Weak third-party governance

Critical suppliers are not assessed consistently.

### 8. Audit findings are disconnected from risk

Audit findings are tracked separately from enterprise risk registers.

### 9. Limited executive reporting

Management receives large quantities of data but limited actionable information.

### 10. No integrated GRC platform

GRC activities are distributed across multiple tools.

---

# 7. GRC Program Objective

Management establishes the following objective:

> **Create an integrated enterprise GRC capability that provides consistent governance, risk visibility, regulatory compliance, control assurance, and executive decision support.**

The target state is:

```text
Governance
     |
     v
Enterprise Risk
     |
     +-------- Compliance
     |
     +-------- Controls
     |
     +-------- Audit
     |
     +-------- Third-Party Risk
     |
     +-------- Cybersecurity
     |
     +-------- Business Resilience
     |
     v
GRC Data & Evidence
     |
     v
Metrics & Reporting
     |
     v
Executive Decision-Making
```

---

# 8. Establishing the GRC Governance Structure

The first major decision is to establish governance.

The organization creates:

### Board Risk Committee

Provides board-level oversight.

### Executive GRC Committee

Responsible for enterprise GRC decisions.

### GRC Steering Committee

Coordinates implementation.

### GRC Office

Responsible for operating the GRC framework.

### Domain Owners

Responsible for individual GRC capabilities.

---

# 9. Governance Model

```text
                     Board
                       |
                       v
              Board Risk Committee
                       |
                       v
              Executive GRC Committee
                       |
                       v
              GRC Steering Committee
                       |
                       v
                    GRC Office
                       |
       +---------------+---------------+
       |               |               |
       v               v               v
     Risk         Compliance        Controls
       |               |               |
       +---------------+---------------+
                       |
       +---------------+---------------+
       |               |               |
       v               v               v
     Audit       Cybersecurity      Third Party
```

---

# 10. Defining GRC Roles

A basic responsibility structure is established.

| Activity              | GRC Office | Risk Owner | Compliance | Control Owner | Internal Audit |
| --------------------- | ---------- | ---------- | ---------- | ------------- | -------------- |
| Risk methodology      | A/R        | C          | C          | C             | C              |
| Risk assessment       | R          | A          | C          | C             | I              |
| Compliance assessment | C          | C          | A/R        | C             | I              |
| Control operation     | C          | C          | C          | A/R           | I              |
| Control testing       | R          | C          | C          | C             | A              |
| Audit                 | C          | I          | C          | C             | A/R            |
| Executive reporting   | A/R        | C          | C          | C             | C              |

The objective is to eliminate ambiguity.

---

# 11. Establishing a Common GRC Framework

The GRC team decides not to create an entirely new framework.

Instead, it establishes a common architecture using recognized frameworks and standards.

Potential reference frameworks include:

* ISO 31000;
* ISO/IEC 27001;
* ISO/IEC 27005;
* NIST Cybersecurity Framework;
* COBIT;
* applicable regulatory requirements;
* internal policies and standards.

The organization creates a **common GRC taxonomy**.

---

# 12. GRC Taxonomy

The taxonomy defines common terminology.

```text
Business Objective
        |
        v
Risk
        |
        v
Risk Scenario
        |
        v
Requirement
        |
        v
Control Objective
        |
        v
Control
        |
        v
Evidence
        |
        v
Test
        |
        v
Finding
        |
        v
Remediation
```

This becomes the foundation for integration.

---

# 13. Standardizing Risk Scoring

The organization adopts a common five-level model.

### Likelihood

| Score | Description    |
| ----: | -------------- |
|     1 | Rare           |
|     2 | Unlikely       |
|     3 | Possible       |
|     4 | Likely         |
|     5 | Almost Certain |

### Impact

| Score | Description   |
| ----: | ------------- |
|     1 | Insignificant |
|     2 | Minor         |
|     3 | Moderate      |
|     4 | Major         |
|     5 | Severe        |

A basic inherent risk score is:

**Risk Score = Likelihood × Impact**

For example:

```text
Likelihood = 4
Impact = 5

Risk Score = 4 × 5
           = 20
```

This would normally represent a high-priority risk under the organization's defined thresholds.

---

# 14. Risk Treatment Model

The organization defines four primary treatment options:

```text
                 Risk
                  |
       +----------+----------+
       |          |          |
       v          v          v
     Avoid      Reduce     Transfer
       |          |          |
       +----------+----------+
                  |
                  v
               Accept
```

Risk acceptance requires an authorized risk owner.

High risks may require escalation to the Executive GRC Committee.

---

# 15. Establishing the Control Framework

The organization creates a centralized control library.

Example:

| Control ID | Control                      | Owner           | Frequency |
| ---------- | ---------------------------- | --------------- | --------- |
| AC-001     | Privileged access review     | IAM Manager     | Monthly   |
| AC-002     | User access review           | System Owner    | Quarterly |
| VM-001     | Vulnerability scanning       | Security        | Weekly    |
| BC-001     | Disaster recovery testing    | IT Resilience   | Annual    |
| TP-001     | Critical supplier assessment | Procurement/GRC | Annual    |

Each control is connected to:

* risk;
* requirement;
* control objective;
* owner;
* evidence;
* test procedure;
* finding;
* remediation.

---

# 16. Requirement-to-Control Mapping

The GRC team establishes traceability.

```text
Regulation
    |
    v
Requirement
    |
    v
Control Objective
    |
    v
Control
    |
    v
Evidence
    |
    v
Testing
```

This prevents every regulation from being managed independently.

---

# 17. Compliance Management

The organization creates a central compliance obligation register.

Example:

| Requirement | Source                     | Owner              | Status    |
| ----------- | -------------------------- | ------------------ | --------- |
| R-001       | Data protection regulation | Privacy            | Compliant |
| R-002       | Cybersecurity regulation   | CISO               | Partial   |
| R-003       | Telecom regulation         | Regulatory Affairs | Compliant |
| R-004       | Contractual requirement    | Procurement        | Gap       |

Compliance gaps are connected to risk and remediation.

---

# 18. Audit Integration

Previously, Internal Audit maintained a separate finding register.

The new model connects findings to risks and controls.

```text
Audit Finding
      |
      v
Control Weakness
      |
      v
Risk
      |
      v
Risk Treatment
      |
      v
Remediation
      |
      v
Validation
      |
      v
Closure
```

This provides greater enterprise visibility.

---

# 19. Third-Party Risk Integration

Critical suppliers are brought into the GRC model.

The lifecycle becomes:

```text
Supplier Identification
        |
        v
Risk Classification
        |
        v
Due Diligence
        |
        v
Risk Assessment
        |
        v
Contractual Controls
        |
        v
Monitoring
        |
        v
Reassessment
        |
        v
Renewal / Offboarding
```

Supplier risks can now appear in the enterprise risk dashboard.

---

# 20. GRC Evidence Management

The organization establishes a centralized evidence model.

Each evidence item should contain:

* evidence ID;
* control ID;
* requirement;
* owner;
* collection date;
* validity period;
* source;
* reviewer;
* status.

Example:

```text
Evidence E-00482
      |
      +-- Control: AC-001
      +-- Requirement: R-023
      +-- Owner: IAM Manager
      +-- Period: Q2
      +-- Status: Validated
```

---

# 21. GRC Technology Strategy

The organization evaluates its existing tools.

Current environment:

```text
Excel
SharePoint
JIRA
Service Desk
SIEM
IAM
Audit Tool
Procurement System
```

The target architecture is:

```text
                    GRC PLATFORM
                         |
       +-----------------+-----------------+
       |                 |                 |
       v                 v                 v
      Risk          Compliance          Controls
       |                 |                 |
       +-----------------+-----------------+
                         |
       +-----------------+-----------------+
       |                 |                 |
       v                 v                 v
     Audit          Third Party        Evidence
                         |
                         v
                    Reporting
                         |
                         v
                Executive Dashboard
```

The organization does not automate everything immediately.

It first standardizes processes and data.

---

# 22. GRC Implementation Roadmap

A three-phase implementation is selected.

## Phase 1 – Foundation

**Months 1–3**

* establish governance;
* define GRC taxonomy;
* standardize risk methodology;
* define control framework;
* identify critical regulations;
* establish GRC policies.

## Phase 2 – Integration

**Months 4–8**

* consolidate risk registers;
* implement control library;
* integrate compliance;
* integrate audit findings;
* establish third-party risk;
* establish evidence management.

## Phase 3 – Optimization

**Months 9–12**

* implement automation;
* develop dashboards;
* integrate technology platforms;
* introduce advanced analytics;
* establish continuous monitoring.

---

# 23. Target GRC Maturity

The organization establishes a five-level maturity model.

| Level | Description |
| ----: | ----------- |
|     1 | Initial     |
|     2 | Developing  |
|     3 | Defined     |
|     4 | Managed     |
|     5 | Optimized   |

The target after 12 months is:

| Capability  | Initial | Target |
| ----------- | ------: | -----: |
| Governance  |       2 |      4 |
| Risk        |       2 |      4 |
| Compliance  |       2 |      4 |
| Controls    |       2 |      4 |
| Audit       |       3 |      4 |
| Third Party |       1 |      3 |
| Technology  |       1 |      3 |
| Metrics     |       1 |      4 |

The organization does not attempt to reach Level 5 immediately.

---

# 24. GRC Metrics

Management defines several initial KPIs and KRIs.

### Risk

* percentage of risks assessed;
* number of risks above appetite;
* overdue risk treatments.

### Compliance

* compliance coverage;
* high-risk compliance gaps;
* overdue regulatory actions.

### Controls

* control effectiveness;
* overdue control testing;
* failed critical controls.

### Audit

* open findings;
* overdue findings;
* high-risk findings.

### Third Party

* critical suppliers assessed;
* overdue assessments;
* high-risk supplier findings.

---

# 25. Executive Dashboard

After implementation, management receives a consolidated dashboard.

```text
+------------------------------------------------+
|             ENTERPRISE GRC DASHBOARD           |
+------------------------------------------------+
| RISK        | COMPLIANCE   | CONTROLS          |
| High: 18    | Gaps: 15     | Failed: 4         |
| Above App:4 | High: 5      | Overdue: 6        |
+------------------------------------------------+
| AUDIT       | THIRD PARTY  | CYBER              |
| Open: 42    | High: 6      | Critical: 12      |
| High: 8     | Overdue: 4   | Incidents: 2      |
+------------------------------------------------+
| MANAGEMENT ACTIONS                              |
| Critical: 7                                    |
| Overdue: 19                                    |
+------------------------------------------------+
```

Executives can now see the major areas requiring attention.

---

# 26. Business Benefits

After implementation, AtlasConnect expects several benefits.

### Better Risk Visibility

Management can see enterprise risk consistently.

### Improved Accountability

Risk and control ownership becomes explicit.

### Reduced Duplication

Common controls can support multiple requirements.

### Better Audit Readiness

Evidence is easier to locate and validate.

### Improved Regulatory Compliance

Regulatory obligations are centrally managed.

### Better Third-Party Oversight

Critical suppliers receive consistent assessments.

### Improved Decision-Making

Executives receive consolidated risk information.

---

# 27. Before-and-After Comparison

| Area                 | Before            | After                  |
| -------------------- | ----------------- | ---------------------- |
| Risk registers       | Fragmented        | Centralized            |
| Risk methodology     | Inconsistent      | Standardized           |
| Controls             | Duplicated        | Centralized library    |
| Compliance           | Spreadsheet-based | Structured             |
| Audit findings       | Isolated          | Linked to risk/control |
| Evidence             | Distributed       | Centralized            |
| Third parties        | Inconsistent      | Risk-based             |
| Reporting            | Manual            | Dashboard-based        |
| GRC technology       | Disconnected      | Integrated             |
| Executive visibility | Limited           | Enterprise-wide        |

---

# 28. Key Lessons from the Case

### Lesson 1 – Do Not Start with Technology

The organization first establishes:

```text
Governance
     ↓
Process
     ↓
Data
     ↓
Technology
```

Buying a GRC platform before defining the operating model can simply automate bad processes.

### Lesson 2 – Establish Common Definitions

Risk, control, finding, requirement, and evidence should have consistent meanings.

### Lesson 3 – Integrate GRC Activities

Risk, compliance, controls, audit, and third-party risk should not operate as isolated silos.

### Lesson 4 – Establish Ownership

Every significant risk and control should have an accountable owner.

### Lesson 5 – Build Traceability

Management should be able to trace:

```text
Business Objective
      ↓
Risk
      ↓
Requirement
      ↓
Control
      ↓
Evidence
      ↓
Finding
      ↓
Remediation
      ↓
Residual Risk
```

### Lesson 6 – Design for Decision-Making

GRC should ultimately answer:

> **What is the risk, who owns it, what is being done, and what decision is required?**

---

# 29. Case Study Decision Point

At the end of the first year, the Executive GRC Committee must decide whether to invest in further GRC maturity.

Three options are presented.

### Option A – Maintain Current State

Lowest investment but limited improvement.

### Option B – Expand Automation

Increase GRC platform integration and continuous monitoring.

### Option C – Enterprise GRC Transformation

Integrate GRC with enterprise risk, cybersecurity, compliance, audit, resilience, third-party risk, and executive decision-making.

The committee selects **Option C** because the organization considers GRC a strategic management capability rather than merely a compliance function.

---

# 30. Final Case Study Model

The completed GRC program can be represented as:

```text
                    BOARD / EXECUTIVES
                           |
                           v
                    GRC GOVERNANCE
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
       RISK           COMPLIANCE          CONTROLS
        |                  |                  |
        +------------------+------------------+
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
      AUDIT           THIRD PARTY       CYBERSECURITY
        |                  |                  |
        +------------------+------------------+
                           |
                           v
                    DATA & EVIDENCE
                           |
                           v
                    GRC TECHNOLOGY
                           |
                           v
                  METRICS & DASHBOARD
                           |
                           v
                  MANAGEMENT DECISIONS
                           |
                           v
                  CONTINUAL IMPROVEMENT
```

## Case Study Conclusion

The AtlasConnect case demonstrates that **building GRC from scratch is primarily an operating-model and governance challenge before it becomes a technology challenge**.

A successful GRC program establishes common governance, terminology, risk methodology, controls, compliance processes, evidence management, accountability, reporting, and technology integration.

The end state is not simply a larger collection of policies, registers, and dashboards. It is an **integrated management capability that connects business objectives, risk, compliance, controls, assurance, evidence, and executive decision-making**.

The core transformation is:

```text
Fragmented GRC
      ↓
Standardized GRC
      ↓
Integrated GRC
      ↓
Risk-Based GRC
      ↓
Data-Driven GRC
      ↓
Decision-Oriented GRC
```



# 19.1 GRC Foundations Case Studies

## Part 2 – Assessing an Organization's GRC Maturity

## 1. Case Study Overview

This case study examines how a GRC professional conducts an **enterprise GRC maturity assessment** to determine the current state of Governance, Risk, and Compliance capabilities.

The assessment is used to identify weaknesses, establish a baseline, prioritize improvement initiatives, and develop a realistic GRC transformation roadmap.

The organization in this case is fictional but reflects a realistic medium-to-large enterprise.

---

# 2. Organization Profile

### Company

**Nexora Digital Services**

### Industry

Digital technology and telecommunications services

### Employees

Approximately 4,200

### Annual Revenue

Approximately €1.2 billion

### Geographic Scope

* Spain
* Portugal
* France
* Germany
* Middle East

### Technology Environment

* Hybrid cloud
* Microsoft Azure
* SaaS applications
* Enterprise data center
* Customer-facing digital platforms
* CRM
* ERP
* IAM
* SOC
* Data analytics platforms
* Third-party technology services

---

# 3. Why the Assessment Was Initiated

The Board has become increasingly concerned about the organization's risk and compliance posture.

Several events occurred during the previous 12 months:

* two significant cybersecurity incidents;
* three high-risk audit findings;
* one regulatory compliance deficiency;
* several overdue risk treatment actions;
* inconsistent third-party security assessments;
* increasing cloud adoption;
* multiple new regulatory requirements.

The Chief Risk Officer therefore requests a formal GRC maturity assessment.

The assessment question is:

> **"How mature is our current GRC capability, where are the most significant weaknesses, and what should we improve first?"**

---

# 4. Assessment Objectives

The assessment has five objectives:

1. Determine the current maturity level.
2. Identify capability gaps.
3. Identify high-priority weaknesses.
4. Establish a target maturity state.
5. Develop an improvement roadmap.

The assessment is not intended to be an audit.

It is primarily a **management improvement exercise**.

---

# 5. Assessment Scope

The assessment covers eight GRC domains:

```text id="p6z3hl"
                GRC MATURITY ASSESSMENT
                         |
     +-------------------+-------------------+
     |                   |                   |
     v                   v                   v
 Governance            Risk              Compliance
     |                   |                   |
     +-------------------+-------------------+
                         |
     +-------------------+-------------------+
     |                   |                   |
     v                   v                   v
 Controls              Audit          Third-Party Risk
     |                   |                   |
     +-------------------+-------------------+
                         |
              +----------+----------+
              |                     |
              v                     v
          Technology             Metrics
```

---

# 6. Maturity Model

Nexora adopts a five-level maturity model.

| Level | Maturity   | General Description                                          |
| ----: | ---------- | ------------------------------------------------------------ |
|     1 | Initial    | Ad hoc and reactive                                          |
|     2 | Developing | Some processes exist but are inconsistent                    |
|     3 | Defined    | Standardized and documented                                  |
|     4 | Managed    | Measured, monitored, and consistently operated               |
|     5 | Optimized  | Integrated, automated, predictive, and continuously improved |

This model provides a common language for management.

---

# 7. Level 1 – Initial

At Level 1:

* processes are mostly ad hoc;
* responsibilities are unclear;
* documentation is limited;
* activities depend heavily on individuals;
* metrics are minimal;
* management reacts to events.

Example:

```text id="7ep8la"
Security Incident
      ↓
Management Reaction
      ↓
Temporary Fix
      ↓
Return to Normal
```

There may be little systematic learning.

---

# 8. Level 2 – Developing

At Level 2:

* some processes exist;
* policies may be documented;
* different departments use different approaches;
* risk registers exist;
* controls are identified;
* reporting is mostly manual.

Example:

```text id="d1g8o6"
Risk Registers
      |
      +---- Business Unit A
      |
      +---- Business Unit B
      |
      +---- Security
      |
      +---- Compliance
```

The organization has GRC activity but limited integration.

---

# 9. Level 3 – Defined

At Level 3:

* processes are standardized;
* responsibilities are defined;
* methodologies are documented;
* common terminology is used;
* controls are centrally managed;
* reporting is more consistent.

Example:

```text id="1dps6x"
Enterprise GRC Framework
          |
    +-----+-----+
    |     |     |
   Risk Compliance Controls
    |     |     |
    +-----+-----+
          |
        Audit
```

---

# 10. Level 4 – Managed

At Level 4:

* GRC performance is measured;
* KRIs and KPIs are established;
* control effectiveness is monitored;
* risk trends are analyzed;
* management receives regular reporting;
* processes are increasingly automated.

Example:

```text id="jz0y31"
GRC Data
    ↓
Analytics
    ↓
Metrics
    ↓
Thresholds
    ↓
Management Action
```

---

# 11. Level 5 – Optimized

At Level 5:

* GRC is integrated across the enterprise;
* automation is extensive;
* analytics support decisions;
* emerging risks are identified;
* continuous monitoring is established;
* GRC is closely aligned with business strategy.

Example:

```text id="b6s3nz"
Business Data
      ↓
Risk Analytics
      ↓
Emerging Risk Detection
      ↓
Predictive Insight
      ↓
Executive Decision
      ↓
Continuous Improvement
```

---

# 12. Assessment Methodology

The assessment team uses six activities:

```text id="b7b6hd"
1. Document Review
        ↓
2. Stakeholder Interviews
        ↓
3. Process Walkthroughs
        ↓
4. Evidence Review
        ↓
5. Maturity Scoring
        ↓
6. Gap Analysis
```

The results are then validated with management.

---

# 13. Evidence Sources

The assessment team reviews:

* GRC policies;
* risk registers;
* control libraries;
* audit reports;
* compliance assessments;
* security assessments;
* third-party assessments;
* incident reports;
* business continuity documentation;
* committee minutes;
* dashboards;
* risk acceptance records;
* remediation records.

The goal is to assess **actual operating capability**, not simply documented intent.

---

# 14. Stakeholder Interviews

The team interviews:

### Executive Management

To understand governance and decision-making.

### Risk Management

To understand risk methodology.

### CISO

To understand cybersecurity governance.

### Compliance

To understand regulatory management.

### Internal Audit

To understand assurance.

### Control Owners

To determine whether controls actually operate.

### Procurement

To assess third-party risk management.

### IT and Security Teams

To understand operational implementation.

---

# 15. Assessment Scoring

Each domain receives a score from 1 to 5.

For example:

| Domain              | Score |
| ------------------- | ----: |
| Governance          |     3 |
| Risk Management     |     2 |
| Compliance          |     3 |
| Controls            |     3 |
| Audit & Assurance   |     4 |
| Third-Party Risk    |     2 |
| GRC Technology      |     2 |
| Metrics & Reporting |     2 |

The average maturity is:

[
\frac{3+2+3+3+4+2+2+2}{8}=2.625
]

The organization therefore has an approximate maturity level of **2.6**, between Developing and Defined.

---

# 16. Maturity Assessment Results

The assessment produces the following summary:

```text id="l2thw7"
Governance          ███████████████  3.0
Risk Management     ██████████       2.0
Compliance          ███████████████  3.0
Controls            ███████████████  3.0
Audit               ████████████████████ 4.0
Third Party         ██████████       2.0
Technology          ██████████       2.0
Metrics             ██████████       2.0
```

The strongest area is **Audit & Assurance**.

The weakest areas are:

* risk management;
* third-party risk;
* GRC technology;
* metrics and reporting.

---

# 17. Detailed Governance Assessment

### Current State

Governance is relatively mature.

The organization has:

* Board Risk Committee;
* Executive Risk Committee;
* CISO;
* Compliance function;
* Internal Audit.

However, responsibilities overlap between Risk, Compliance, and Cybersecurity.

### Score

**3/5 – Defined**

### Main Gap

The organization needs a clearer integrated GRC operating model.

---

# 18. Detailed Risk Management Assessment

### Current State

The organization maintains several risk registers.

However:

* scoring methodologies differ;
* risk categories differ;
* risk appetite is not consistently applied;
* cyber risks are not consistently linked to enterprise risks;
* risk treatment tracking is inconsistent.

### Score

**2/5 – Developing**

### Major Gap

No common enterprise risk taxonomy.

---

# 19. Detailed Compliance Assessment

The organization has established compliance functions.

However:

* regulations are tracked differently by departments;
* requirements are not consistently mapped to controls;
* evidence collection remains manual;
* regulatory change management is inconsistent.

### Score

**3/5 – Defined**

### Main Gap

Weak requirement-to-control traceability.

---

# 20. Detailed Control Assessment

The organization has approximately **680 documented controls**.

The assessment finds:

* 90 duplicate or overlapping controls;
* 45 controls without clear ownership;
* 37 controls with inconsistent testing;
* 21 controls with insufficient evidence.

### Score

**3/5 – Defined**

The control framework exists but requires rationalization.

---

# 21. Detailed Audit Assessment

Internal Audit has a mature methodology.

Strengths include:

* risk-based audit planning;
* documented testing procedures;
* independent reporting;
* finding tracking;
* follow-up procedures.

### Score

**4/5 – Managed**

However, audit findings are not always integrated into enterprise risk reporting.

---

# 22. Detailed Third-Party Risk Assessment

Third-party risk is one of the weakest areas.

Approximately 1,100 suppliers exist.

Only 310 have undergone formal security or risk assessment.

Of those:

```text id="y6f89m"
310 Assessed Suppliers
       |
       +---- 246 Low/Medium Risk
       |
       +---- 52 High Risk
       |
       +---- 12 Critical Risk
```

### Score

**2/5 – Developing**

The organization needs risk-based supplier classification and monitoring.

---

# 23. GRC Technology Assessment

Current GRC activities rely on:

* Excel;
* SharePoint;
* email;
* Jira;
* ServiceNow;
* individual departmental systems.

There is no centralized GRC platform.

### Score

**2/5 – Developing**

The problem is not necessarily the absence of a GRC platform.

The larger issue is fragmented data and processes.

---

# 24. Metrics and Reporting Assessment

Management receives several reports every month.

However, the reports contain:

* inconsistent metrics;
* different reporting periods;
* duplicate information;
* limited trends;
* limited thresholds;
* insufficient linkage to decisions.

### Score

**2/5 – Developing**

The organization needs an enterprise GRC metrics framework.

---

# 25. Key Findings

The assessment identifies seven major findings.

### Finding 1

Risk methodology is inconsistent.

### Finding 2

Risk registers are fragmented.

### Finding 3

Third-party risk coverage is incomplete.

### Finding 4

Control duplication is significant.

### Finding 5

Requirement-to-control traceability is incomplete.

### Finding 6

GRC reporting is primarily descriptive rather than decision-oriented.

### Finding 7

GRC data is distributed across multiple systems.

---

# 26. Root Cause Analysis

The team performs a root cause analysis.

```text id="2b8fgt"
Fragmented GRC
       |
       v
No Common Operating Model
       |
       v
Different Methodologies
       |
       v
Different Data Structures
       |
       v
Different Reporting
       |
       v
Poor Enterprise Visibility
```

The underlying issue is therefore not simply "lack of technology."

It is a **lack of integrated GRC governance and architecture**.

---

# 27. Gap Analysis

The organization defines its target state as Level 4.

| Domain      | Current | Target | Gap |
| ----------- | ------: | -----: | --: |
| Governance  |       3 |      4 |   1 |
| Risk        |       2 |      4 |   2 |
| Compliance  |       3 |      4 |   1 |
| Controls    |       3 |      4 |   1 |
| Audit       |       4 |      4 |   0 |
| Third Party |       2 |      4 |   2 |
| Technology  |       2 |      4 |   2 |
| Metrics     |       2 |      4 |   2 |

The greatest improvement opportunities are:

* risk;
* third-party risk;
* technology;
* metrics.

---

# 28. Prioritization Model

Not every gap should be addressed simultaneously.

The GRC team evaluates each gap using:

```text
Business Impact
       +
Risk Exposure
       +
Regulatory Importance
       +
Implementation Effort
       =
Priority
```

High-impact and high-risk gaps receive priority.

---

# 29. Priority Matrix

| Initiative                         | Risk   | Effort | Priority |
| ---------------------------------- | ------ | ------ | -------- |
| Standardize risk methodology       | High   | Medium | Critical |
| Establish third-party risk program | High   | Medium | Critical |
| Rationalize control library        | High   | High   | High     |
| Improve GRC metrics                | Medium | Medium | High     |
| Implement GRC platform             | Medium | High   | Medium   |
| Integrate audit findings           | Medium | Medium | High     |

This prevents the organization from automatically making technology the first priority.

---

# 30. Target-State GRC Model

The target operating model is:

```text id="1e9u7f"
                      BOARD
                        |
                        v
                GRC GOVERNANCE
                        |
        +---------------+---------------+
        |               |               |
        v               v               v
       RISK        COMPLIANCE        CONTROLS
        |               |               |
        +---------------+---------------+
                        |
       +----------------+----------------+
       |                |                |
       v                v                v
     AUDIT         THIRD PARTY      CYBERSECURITY
       |                |                |
       +----------------+----------------+
                        |
                        v
                  GRC DATA LAYER
                        |
                        v
                 GRC TECHNOLOGY
                        |
                        v
                ANALYTICS & KRIs
                        |
                        v
               EXECUTIVE DASHBOARD
                        |
                        v
               MANAGEMENT DECISION
```

---

# 31. GRC Maturity Roadmap

The organization develops a two-year roadmap.

## Phase 1 – Stabilize

**Months 1–6**

* establish common taxonomy;
* standardize risk methodology;
* define ownership;
* rationalize critical controls;
* establish third-party classification.

## Phase 2 – Integrate

**Months 7–12**

* integrate risk and compliance;
* connect controls to requirements;
* integrate audit findings;
* establish evidence management;
* develop common metrics.

## Phase 3 – Automate

**Months 13–18**

* implement GRC platform capabilities;
* automate workflows;
* automate evidence collection;
* integrate enterprise systems.

## Phase 4 – Optimize

**Months 19–24**

* continuous monitoring;
* advanced analytics;
* predictive risk indicators;
* automated executive reporting.

---

# 32. Expected Future-State Maturity

After two years, the target is:

```text id="7hplzj"
Governance          4
Risk Management     4
Compliance          4
Controls            4
Audit               4
Third Party         4
Technology          4
Metrics             4
```

The organization does not need every capability to reach Level 5.

The target is **consistent, measurable, integrated, and risk-based GRC**.

---

# 33. Business Case for Improvement

Management estimates the following potential benefits:

* 20–30% reduction in duplicate control activities;
* 30–40% reduction in manual evidence collection;
* improved audit preparation;
* improved regulatory visibility;
* faster risk reporting;
* increased third-party assessment coverage;
* improved executive decision-making.

These figures should be treated as **planning estimates**, not guaranteed outcomes.

---

# 34. Important Assessment Principle

A maturity assessment should distinguish between:

### Documented Capability

What the organization says it does.

### Designed Capability

What the process was intended to achieve.

### Operating Capability

What actually happens.

### Measured Capability

Whether performance is measured.

### Optimized Capability

Whether the organization continuously improves it.

For example:

```text id="r2m3ep"
Policy Exists
     ↓
Process Designed
     ↓
Process Operates
     ↓
Performance Measured
     ↓
Process Improved
```

A policy alone does not demonstrate maturity.

---

# 35. Common Mistakes in GRC Maturity Assessments

### Mistake 1 – Scoring Based Only on Documentation

A large document library does not necessarily indicate maturity.

### Mistake 2 – Treating Technology as Maturity

Having a GRC platform does not automatically create mature GRC.

### Mistake 3 – Ignoring Business Alignment

GRC maturity must support business objectives.

### Mistake 4 – Giving Every Domain the Same Priority

High-risk weaknesses require greater attention.

### Mistake 5 – Creating an Unrealistic Target

Not every organization needs Level 5 maturity.

### Mistake 6 – Failing to Validate Results

Assessment results should be discussed with accountable stakeholders.

---

# 36. Executive Assessment Report

The final report to the Board contains five sections:

```text id="ez0gko"
1. Executive Summary
        ↓
2. Current Maturity
        ↓
3. Major Gaps
        ↓
4. Priority Improvements
        ↓
5. GRC Roadmap
```

The Board does not necessarily need hundreds of pages of assessment evidence.

It needs to understand:

* where the organization is;
* where the material weaknesses are;
* what risks they create;
* what management should do;
* how much effort is required;
* when improvement is expected.

---

# 37. Executive Summary Example

The assessment concludes:

> Nexora Digital Services has a developing GRC capability with an overall maturity of approximately 2.6/5. Governance, compliance, controls, and internal audit processes are reasonably established, while enterprise risk management, third-party risk, GRC technology, and metrics require significant improvement. The organization should prioritize standardization and integration before pursuing extensive automation.

---

# 38. Final Case Study Model

The maturity assessment process can be summarized as:

```text id="e1fqy8"
Define Scope
     |
     v
Define Maturity Model
     |
     v
Collect Evidence
     |
     v
Interview Stakeholders
     |
     v
Assess Capabilities
     |
     v
Score Maturity
     |
     v
Identify Gaps
     |
     v
Prioritize Improvements
     |
     v
Define Target State
     |
     v
Build Roadmap
     |
     v
Measure Progress
     |
     v
Reassess Maturity
```

The process is cyclical rather than one-time.

---

# 39. Case Study Conclusion

The Nexora case demonstrates that a **GRC maturity assessment is a management instrument rather than simply a scoring exercise**.

The most valuable output is not the maturity number of 2.6/5.

The real value comes from understanding:

```text
Current State
     ↓
Capability Gaps
     ↓
Business / Risk Impact
     ↓
Priority
     ↓
Target State
     ↓
Improvement Roadmap
     ↓
Measured Progress
```

A mature GRC professional should therefore be able to move beyond saying:

> "Our GRC maturity is Level 2."

and instead explain:

> **"We are at Level 2 in these specific capabilities, these weaknesses create these risks, these are the highest-priority improvements, and this roadmap will move us toward our target maturity."**

That is the difference between **measuring GRC maturity** and **using maturity assessment to drive GRC transformation**.

# 19.1 GRC Foundations Case Studies

## Part 3 – Designing a GRC Operating Model

## 1. Case Study Overview

This case study examines how an organization designs an **enterprise GRC operating model** after discovering that governance, risk, compliance, cybersecurity, audit, and control activities are fragmented across different departments.

The objective is to establish a practical model that defines:

* who makes GRC decisions;
* who owns risks;
* who owns controls;
* who performs compliance activities;
* who provides assurance;
* how GRC information flows;
* how issues are escalated;
* how management decisions are made.

The case demonstrates that a GRC operating model is more than an organizational chart. It defines **how GRC actually works across the enterprise**.

---

# 2. Organization Profile

### Company

**Orion Global Communications**

### Industry

Telecommunications and digital services

### Employees

Approximately 9,000

### Annual Revenue

Approximately €2.4 billion

### Geographic Presence

* Spain
* Portugal
* France
* Italy
* Middle East

### Major Business Areas

* Mobile telecommunications
* Broadband
* Enterprise connectivity
* Cloud services
* Digital payments
* Customer applications
* IoT services

---

# 3. The Business Problem

Orion has grown through acquisitions.

Each acquired organization brought its own:

* risk methodology;
* cybersecurity policies;
* compliance processes;
* control libraries;
* audit practices;
* third-party processes;
* reporting methods.

The result is a fragmented GRC environment.

```text
                 ORION GROUP
                     |
       +-------------+-------------+
       |             |             |
       v             v             v
   Business A    Business B    Business C
       |             |             |
      Risk          Risk          Risk
      Controls      Controls      Controls
      Compliance    Compliance    Compliance
```

There is no consistent enterprise-wide GRC operating model.

---

# 4. Management Challenge

The Board asks the Group Chief Risk Officer:

> **"Who is accountable when a major enterprise risk crosses multiple departments?"**

The answer is unclear.

For example, a cloud security risk may involve:

* Cloud Engineering;
* Cybersecurity;
* Procurement;
* Legal;
* Privacy;
* Business Operations;
* Enterprise Risk;
* Internal Audit.

Each function believes another function has primary responsibility.

This creates an **accountability gap**.

---

# 5. Current-State Assessment

The GRC team identifies five major weaknesses.

### 1. Overlapping responsibilities

Multiple functions perform similar activities.

### 2. Unclear accountability

Risk and control ownership are not consistently assigned.

### 3. Fragmented reporting

Each department produces separate reports.

### 4. Weak escalation

High-risk issues may take too long to reach executives.

### 5. Limited integration

Risk, compliance, cybersecurity, audit, and third-party risk operate independently.

---

# 6. Design Objective

Management defines the target objective:

> **Create an enterprise GRC operating model that establishes clear accountability, integrates GRC processes, enables risk-based decision-making, and provides independent assurance.**

The model must work across:

```text
Enterprise
   ↓
Business Units
   ↓
Functions
   ↓
Processes
   ↓
Systems
   ↓
Controls
```

---

# 7. GRC Operating Model Components

The organization decides that the operating model will contain seven components:

```text
                  GRC OPERATING MODEL
                          |
     +--------------------+--------------------+
     |                    |                    |
 Governance             People              Process
     |                    |                    |
 Technology             Data               Controls
     |                    |
     +--------- Reporting & Assurance --------+
```

Each component must be defined.

---

# 8. Component 1 – Governance

Governance establishes decision authority.

The proposed structure is:

```text
                         Board
                           |
                           v
                   Board Risk Committee
                           |
                           v
                  Executive GRC Committee
                           |
                           v
                  Enterprise GRC Council
                           |
                           v
                       GRC Office
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
      Risk            Compliance        Cybersecurity
```

---

# 9. Board Risk Committee

The Board Risk Committee provides oversight of material enterprise risks.

Responsibilities include:

* reviewing significant risks;
* reviewing risk appetite;
* monitoring major regulatory issues;
* reviewing significant cybersecurity risks;
* reviewing major business resilience risks;
* challenging management;
* overseeing risk reporting.

The committee does **not** manage individual operational controls.

Its role is oversight and challenge.

---

# 10. Executive GRC Committee

The Executive GRC Committee consists of senior executives.

Typical members include:

* CEO;
* CFO;
* CIO;
* CISO;
* Chief Risk Officer;
* Chief Compliance Officer;
* General Counsel;
* Chief Privacy Officer;
* COO.

Its responsibilities include:

* approving enterprise risk priorities;
* resolving cross-functional risk issues;
* approving significant risk treatments;
* reviewing compliance exposure;
* prioritizing remediation;
* escalating material issues to the Board.

---

# 11. Enterprise GRC Council

The Enterprise GRC Council provides operational coordination.

Members include:

* GRC Director;
* Risk Managers;
* Compliance Managers;
* Security Governance;
* Business Continuity;
* Third-Party Risk;
* Internal Control representatives.

The council ensures that GRC processes are coordinated across departments.

---

# 12. GRC Office

The GRC Office becomes the central coordination function.

It is responsible for:

* GRC methodology;
* GRC policies;
* risk taxonomy;
* control taxonomy;
* reporting standards;
* GRC processes;
* governance meetings;
* risk aggregation;
* GRC data quality;
* GRC platform administration.

The GRC Office **does not own every enterprise risk**.

Risk ownership remains with the business.

---

# 13. Risk Ownership Principle

A fundamental principle is established:

> **The person accountable for the business outcome should normally be accountable for the associated risk.**

For example:

```text
Customer Billing Process
        |
        v
Billing Director
        |
        v
Business Risk Owner
```

The GRC function facilitates and challenges the risk process but does not automatically become the risk owner.

---

# 14. Control Ownership

Controls are assigned separately from risk ownership where appropriate.

Example:

```text
Risk:
Unauthorized privileged access

Risk Owner:
CIO

Control:
Quarterly privileged access review

Control Owner:
IAM Manager
```

This distinction is critical.

The risk owner is accountable for the risk.

The control owner is accountable for operating the control.

---

# 15. Three Lines Integration

Orion adopts the Three Lines Model.

```text
                    BOARD
                      |
                      v
                Senior Management
                      |
        +-------------+-------------+
        |             |             |
        v             v             v
    First Line     Second Line   Third Line
    Management      Risk/GRC     Internal Audit
        |             |             |
        v             v             v
    Own & Manage   Challenge &    Independent
       Risk         Monitor        Assurance
```

The model prevents confusion between management responsibility and independent assurance.

---

# 16. First Line Responsibilities

The first line consists primarily of operational management.

Responsibilities include:

* identifying risks;
* operating controls;
* managing processes;
* implementing remediation;
* maintaining evidence;
* reporting issues.

Examples:

* IT Operations;
* Cloud Engineering;
* Network Operations;
* Finance;
* Procurement;
* HR;
* Business Units.

---

# 17. Second Line Responsibilities

The second line provides expertise, monitoring, challenge, and oversight.

Functions may include:

* Enterprise Risk;
* Compliance;
* Cybersecurity Governance;
* Privacy;
* Business Continuity;
* Third-Party Risk;
* Information Security Risk.

The second line does not replace operational management.

---

# 18. Third Line Responsibilities

Internal Audit provides independent assurance.

Responsibilities include:

* independent assessment;
* audit planning;
* control testing;
* governance assessment;
* reporting;
* follow-up;
* assurance over the effectiveness of governance and risk management.

Internal Audit should remain organizationally independent.

---

# 19. GRC Process Architecture

Orion defines a common GRC process architecture.

```text
Business Objectives
        |
        v
Risk Identification
        |
        v
Risk Assessment
        |
        v
Risk Treatment
        |
        v
Control Implementation
        |
        v
Control Testing
        |
        v
Monitoring
        |
        v
Reporting
        |
        v
Management Decision
        |
        v
Continual Improvement
```

This becomes the common process backbone.

---

# 20. Integrated Compliance Process

Compliance activities are integrated into the same model.

```text
Regulation
    |
    v
Requirement
    |
    v
Applicability
    |
    v
Control
    |
    v
Evidence
    |
    v
Assessment
    |
    v
Gap
    |
    v
Remediation
    |
    v
Validation
```

Compliance therefore becomes connected to risk and controls.

---

# 21. Third-Party Risk Integration

Third-party risk is integrated into the enterprise model.

```text
Supplier
   |
   v
Classification
   |
   v
Due Diligence
   |
   v
Risk Assessment
   |
   v
Contract Controls
   |
   v
Monitoring
   |
   v
Reassessment
   |
   v
Renewal / Exit
```

Critical suppliers are also represented in the enterprise risk register where appropriate.

---

# 22. Incident and Risk Integration

Cybersecurity incidents are connected to the risk process.

```text
Security Incident
       |
       v
Investigation
       |
       v
Root Cause
       |
       v
Control Weakness
       |
       v
Risk Assessment
       |
       v
Remediation
       |
       v
Residual Risk
```

This prevents incidents from being treated only as operational events.

---

# 23. Business Continuity Integration

Business resilience is integrated into GRC.

```text
Critical Business Process
          |
          v
Business Impact Analysis
          |
          v
Recovery Requirement
          |
          v
Recovery Strategy
          |
          v
Testing
          |
          v
Resilience Risk
```

This allows resilience weaknesses to appear in enterprise risk reporting.

---

# 24. GRC Data Model

Orion establishes a common GRC data model.

```text
Business Objective
        |
        v
Risk
        |
        v
Requirement
        |
        v
Control
        |
        v
Evidence
        |
        v
Test
        |
        v
Finding
        |
        v
Remediation
        |
        v
Residual Risk
```

Each object has:

* unique identifier;
* owner;
* status;
* relationship;
* review date;
* source;
* lifecycle state.

---

# 25. Example Traceability

Consider a regulatory requirement concerning privileged access.

```text
Requirement R-027
        |
        v
Control AC-014
        |
        v
Quarterly Access Review
        |
        v
Evidence E-884
        |
        v
Control Test T-221
        |
        v
Finding F-031
        |
        v
Remediation RA-118
```

Management can trace the entire lifecycle.

---

# 26. GRC Decision Rights

The operating model defines decision authority.

| Decision                  | Primary Authority       |
| ------------------------- | ----------------------- |
| Risk methodology          | GRC Committee           |
| Risk ownership            | Business                |
| Control ownership         | Process/System Owner    |
| Risk acceptance           | Authorized Risk Owner   |
| Major risk acceptance     | Executive GRC Committee |
| Audit opinion             | Internal Audit          |
| Compliance interpretation | Compliance/Legal        |
| Security risk treatment   | Business + Security     |
| GRC standards             | GRC Office              |

This prevents governance ambiguity.

---

# 27. Risk Escalation Model

The organization defines escalation thresholds.

```text
Low Risk
   |
   v
Business Management

Medium Risk
   |
   v
Business + GRC

High Risk
   |
   v
Executive GRC Committee

Critical Risk
   |
   v
Executive Committee
        |
        v
Board Risk Committee
```

Escalation criteria include:

* financial impact;
* regulatory impact;
* customer impact;
* security impact;
* operational impact;
* reputational impact;
* risk appetite breach.

---

# 28. GRC Reporting Architecture

Reporting occurs at three levels.

### Operational

Detailed information for control and process owners.

### Management

Aggregated information for executives.

### Board

Material risks, trends, exceptions, and decisions.

```text
Operational Data
       |
       v
GRC Analytics
       |
       +---- Operational Dashboard
       |
       +---- Management Dashboard
       |
       +---- Board Dashboard
```

The same underlying data supports different audiences.

---

# 29. GRC Metrics

The organization establishes metrics for:

### Risk

* number of risks above appetite;
* overdue treatments;
* risk trend.

### Compliance

* compliance coverage;
* regulatory gaps;
* overdue remediation.

### Controls

* control effectiveness;
* failed controls;
* overdue testing.

### Audit

* open findings;
* high-risk findings;
* overdue findings.

### Third Parties

* critical suppliers assessed;
* high-risk suppliers;
* overdue assessments.

---

# 30. Technology Architecture

The target GRC technology model is:

```text
                     GRC PLATFORM
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
       Risk          Compliance          Controls
        |                  |                  |
        +------------------+------------------+
                           |
       +-------------------+-------------------+
       |                   |                   |
       v                   v                   v
     Audit            Third Party          Evidence
                           |
                           v
                     GRC Analytics
                           |
                           v
                  Executive Reporting
```

The GRC platform integrates with:

* IAM;
* SIEM;
* vulnerability management;
* ServiceNow;
* procurement;
* HR;
* cloud platforms;
* audit systems.

---

# 31. Operating Model Principles

Orion establishes ten principles.

### Principle 1 – Business Ownership

Business management owns business risks.

### Principle 2 – Clear Accountability

Every major risk and control has an accountable owner.

### Principle 3 – Independent Assurance

Internal Audit remains independent.

### Principle 4 – Common Methodology

Enterprise GRC activities use common definitions.

### Principle 5 – Risk-Based Approach

Resources are prioritized according to risk.

### Principle 6 – Integrated Data

GRC information should be connected.

### Principle 7 – Proportionality

Controls should be appropriate to the level of risk.

### Principle 8 – Transparency

Significant risk decisions should be documented.

### Principle 9 – Continuous Improvement

The GRC operating model evolves with the organization.

### Principle 10 – Business Alignment

GRC should support strategic objectives rather than operate as a separate bureaucracy.

---

# 32. RACI Example

A simplified RACI is established for enterprise risk management.

| Activity      | Business | GRC | Compliance | CISO | Internal Audit |
| ------------- | -------- | --- | ---------- | ---- | -------------- |
| Identify risk | A/R      | C   | C          | C    | I              |
| Assess risk   | R        | A   | C          | C    | I              |
| Treat risk    | A/R      | C   | C          | C    | I              |
| Monitor risk  | R        | A   | C          | C    | I              |
| Audit process | I        | C   | C          | C    | A/R            |

**R = Responsible**
**A = Accountable**
**C = Consulted**
**I = Informed**

---

# 33. Implementation Roadmap

The operating model is implemented in four stages.

## Stage 1 – Design

**Months 1–3**

* define governance;
* define roles;
* define decision rights;
* establish taxonomy;
* define processes.

## Stage 2 – Standardize

**Months 4–6**

* standardize risk;
* standardize controls;
* standardize compliance;
* establish reporting.

## Stage 3 – Integrate

**Months 7–12**

* integrate GRC processes;
* integrate technology;
* integrate evidence;
* establish enterprise dashboards.

## Stage 4 – Optimize

**Months 13–18**

* automate workflows;
* introduce continuous monitoring;
* improve analytics;
* optimize decision-making.

---

# 34. Key Implementation Challenge

The biggest challenge is organizational resistance.

Some departments argue:

> "We already have our own process."

Others argue:

> "Central GRC will slow us down."

The GRC leadership therefore adopts a **federated operating model**.

---

# 35. Federated GRC Model

The federated approach combines central standards with local execution.

```text
                 CENTRAL GRC
                     |
        +------------+------------+
        |            |            |
        v            v            v
     Business A   Business B   Business C
        |            |            |
     Local GRC     Local GRC    Local GRC
        |            |            |
        +------------+------------+
                     |
                     v
              Enterprise GRC
```

### Central GRC provides:

* standards;
* methodology;
* taxonomy;
* governance;
* reporting;
* technology.

### Business units provide:

* risk ownership;
* control operation;
* local compliance;
* evidence;
* remediation.

---

# 36. Why the Federated Model Works

A fully centralized model could create:

* excessive bureaucracy;
* slow decision-making;
* weak business ownership.

A fully decentralized model could create:

* inconsistent methodologies;
* duplicate controls;
* fragmented reporting;
* inconsistent risk decisions.

The federated model attempts to balance both.

```text
Central Standards
        +
Local Execution
        =
Enterprise Consistency
+
Business Ownership
```

---

# 37. Target GRC Operating Model

The final model becomes:

```text
                         BOARD
                           |
                           v
                  BOARD RISK COMMITTEE
                           |
                           v
                 EXECUTIVE GRC COMMITTEE
                           |
                           v
                    CENTRAL GRC OFFICE
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
       Risk            Compliance       Cybersecurity
          |                |                |
          +----------------+----------------+
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
      Business A       Business B       Business C
          |                |                |
          +----------------+----------------+
                           |
                           v
                    GRC DATA PLATFORM
                           |
                           v
                  METRICS & ANALYTICS
                           |
                           v
                   MANAGEMENT DECISIONS
                           |
                           v
                  CONTINUAL IMPROVEMENT
```

Internal Audit operates independently across the model.

---

# 38. Case Study Outcomes

After 18 months, Orion reports several improvements.

| Capability         |       Before |        After |
| ------------------ | -----------: | -----------: |
| Risk methodology   |   Fragmented | Standardized |
| Risk ownership     |      Unclear |      Defined |
| Control ownership  | Inconsistent |      Defined |
| Compliance mapping |      Partial |   Integrated |
| Third-party risk   |   Fragmented |   Risk-based |
| Reporting          | Departmental |   Enterprise |
| GRC data           |  Distributed |   Integrated |
| Escalation         |     Informal |   Structured |
| Audit integration  |      Limited |     Improved |

The overall GRC maturity increases from approximately **2.4/5 to 3.7/5**.

---

# 39. Lessons Learned

### Lesson 1 – GRC Is an Operating Model

GRC is not simply a department.

It is a way of coordinating governance, risk, compliance, controls, assurance, and decision-making.

### Lesson 2 – Ownership Must Remain with the Business

The GRC function should not become the owner of every risk.

### Lesson 3 – Independence Matters

Internal Audit should not become part of operational risk management.

### Lesson 4 – Centralization Has Limits

Standards can be centralized while execution remains distributed.

### Lesson 5 – Data Integration Is Critical

Disconnected GRC information creates fragmented decision-making.

### Lesson 6 – Decision Rights Must Be Explicit

Everyone should understand who can:

* approve;
* accept;
* escalate;
* challenge;
* monitor;
* assure.

---

# 40. Final Case Study Model

The complete operating model can be summarized as:

```text
                    BUSINESS STRATEGY
                           |
                           v
                     GOVERNANCE
                           |
                           v
                     RISK OWNERS
                           |
              +------------+------------+
              |            |            |
              v            v            v
          Compliance    Controls    Cybersecurity
              |            |            |
              +------------+------------+
                           |
                           v
                     GRC DATA
                           |
                           v
                   MONITORING & METRICS
                           |
                           v
                    MANAGEMENT ACTION
                           |
                           v
                    EXECUTIVE OVERSIGHT
                           |
                           v
                 INDEPENDENT ASSURANCE
                           |
                           v
                   CONTINUAL IMPROVEMENT
```

## Case Study Conclusion

The Orion case demonstrates that designing a GRC operating model requires much more than defining reporting lines.

A successful operating model establishes **governance, accountability, decision rights, processes, data, technology, reporting, and assurance**.

The central principle is:

> **Centralize what must be consistent; federate what should remain close to the business.**

The ultimate objective is to create a GRC environment in which:

**Business owns risk → GRC coordinates and challenges → Controls manage risk → Data provides visibility → Executives make decisions → Internal Audit provides independent assurance.**

That structure creates a GRC capability that is **accountable, integrated, risk-based, and aligned with business objectives**.


# 19.1 GRC Foundations Case Studies

## Part 3 – Designing a GRC Operating Model

## 1. Case Study Overview

This case study examines how an organization designs an **enterprise Governance, Risk, and Compliance (GRC) operating model** after identifying fragmented responsibilities, inconsistent processes, duplicated controls, and weak executive visibility.

The purpose is to demonstrate how a GRC professional converts a collection of disconnected GRC activities into a **coordinated operating model with clear accountability, decision rights, processes, technology, and assurance**.

The organization in this case is fictional but reflects a realistic multinational enterprise.

---

## 2. Organization Profile

### Company

**Orion Global Communications**

### Industry

Telecommunications and Digital Services

### Employees

Approximately 9,000

### Annual Revenue

Approximately €2.4 billion

### Geographic Presence

* Spain
* Portugal
* France
* Italy
* Middle East

### Major Business Areas

* Mobile telecommunications
* Broadband
* Enterprise connectivity
* Cloud services
* Digital payments
* IoT services
* Customer-facing digital platforms

---

# 3. The Business Problem

Orion has expanded rapidly through acquisitions.

Each acquired organization brought its own:

* risk methodology;
* cybersecurity policies;
* compliance processes;
* control libraries;
* audit practices;
* third-party processes;
* reporting methods.

The result is a fragmented GRC environment.

```text
                 ORION GROUP
                     |
       +-------------+-------------+
       |             |             |
       v             v             v
   Business A    Business B    Business C
       |             |             |
      Risk          Risk          Risk
      Controls      Controls      Controls
      Compliance    Compliance    Compliance
```

There is no consistent enterprise-wide GRC operating model.

---

# 4. Management Challenge

The Board asks the Group Chief Risk Officer:

> **"Who is accountable when a major enterprise risk crosses multiple departments?"**

The answer is unclear.

For example, a cloud security risk may involve:

* Cloud Engineering;
* Cybersecurity;
* Procurement;
* Legal;
* Privacy;
* Business Operations;
* Enterprise Risk;
* Internal Audit.

Each function believes another function has primary responsibility.

This creates an **accountability gap**.

---

# 5. Current-State Assessment

The GRC team identifies five major weaknesses.

### 1. Overlapping Responsibilities

Multiple functions perform similar GRC activities.

### 2. Unclear Accountability

Risk and control ownership are not consistently assigned.

### 3. Fragmented Reporting

Each department produces separate reports.

### 4. Weak Escalation

High-risk issues may take too long to reach executives.

### 5. Limited Integration

Risk, compliance, cybersecurity, audit, and third-party risk operate independently.

---

# 6. Design Objective

Management defines the target objective:

> **Create an enterprise GRC operating model that establishes clear accountability, integrates GRC processes, enables risk-based decision-making, and provides independent assurance.**

The model must work across:

```text
Enterprise
   ↓
Business Units
   ↓
Functions
   ↓
Processes
   ↓
Systems
   ↓
Controls
```

---

# 7. GRC Operating Model Components

Orion determines that its operating model will contain seven major components:

```text
                  GRC OPERATING MODEL
                          |
     +--------------------+--------------------+
     |                    |                    |
     v                    v                    v
 Governance             People              Process
     |                    |                    |
 Technology             Data               Controls
     |                    |
     +--------- Reporting & Assurance --------+
```

Each component must have defined ownership and responsibilities.

---

# 8. Governance Structure

Governance establishes decision authority.

The proposed structure is:

```text
                         Board
                           |
                           v
                   Board Risk Committee
                           |
                           v
                  Executive GRC Committee
                           |
                           v
                  Enterprise GRC Council
                           |
                           v
                       GRC Office
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
      Risk            Compliance        Cybersecurity
```

---

# 9. Board Risk Committee

The Board Risk Committee provides oversight of material enterprise risks.

Responsibilities include:

* reviewing significant enterprise risks;
* reviewing risk appetite;
* monitoring major regulatory issues;
* reviewing significant cybersecurity risks;
* reviewing business resilience risks;
* challenging management;
* overseeing enterprise risk reporting.

The committee does **not** manage individual operational controls.

Its role is oversight and challenge.

---

# 10. Executive GRC Committee

The Executive GRC Committee consists of senior executives.

Typical members include:

* CEO;
* CFO;
* CIO;
* CISO;
* Chief Risk Officer;
* Chief Compliance Officer;
* General Counsel;
* Chief Privacy Officer;
* COO.

Responsibilities include:

* approving enterprise risk priorities;
* resolving cross-functional risk issues;
* approving significant risk treatments;
* reviewing compliance exposure;
* prioritizing remediation;
* escalating material issues to the Board.

---

# 11. Enterprise GRC Council

The Enterprise GRC Council provides operational coordination.

Members include:

* GRC Director;
* Risk Managers;
* Compliance Managers;
* Security Governance;
* Business Continuity;
* Third-Party Risk;
* Internal Control representatives.

The council ensures that GRC processes are coordinated across departments.

---

# 12. GRC Office

The GRC Office becomes the central coordination function.

Responsibilities include:

* GRC methodology;
* GRC policies;
* risk taxonomy;
* control taxonomy;
* reporting standards;
* GRC processes;
* governance meetings;
* risk aggregation;
* GRC data quality;
* GRC platform administration.

The GRC Office **does not own every enterprise risk**.

Risk ownership remains with the business.

---

# 13. Risk Ownership Principle

A fundamental principle is established:

> **The person accountable for the business outcome should normally be accountable for the associated risk.**

For example:

```text
Customer Billing Process
        |
        v
Billing Director
        |
        v
Business Risk Owner
```

The GRC function facilitates and challenges the risk process but does not automatically become the risk owner.

---

# 14. Control Ownership

Controls are assigned separately from risk ownership where appropriate.

Example:

```text
Risk:
Unauthorized privileged access

Risk Owner:
CIO

Control:
Quarterly privileged access review

Control Owner:
IAM Manager
```

This distinction is critical.

The risk owner is accountable for the risk.

The control owner is accountable for operating the control.

---

# 15. Three Lines Integration

Orion adopts the Three Lines Model.

```text
                    BOARD
                      |
                      v
                Senior Management
                      |
        +-------------+-------------+
        |             |             |
        v             v             v
    First Line     Second Line   Third Line
    Management      Risk/GRC     Internal Audit
        |             |             |
        v             v             v
    Own & Manage   Challenge &    Independent
       Risk         Monitor        Assurance
```

The model prevents confusion between management responsibility and independent assurance.

---

# 16. First Line Responsibilities

The first line consists primarily of operational management.

Responsibilities include:

* identifying risks;
* operating controls;
* managing processes;
* implementing remediation;
* maintaining evidence;
* reporting issues.

Examples include:

* IT Operations;
* Cloud Engineering;
* Network Operations;
* Finance;
* Procurement;
* HR;
* Business Units.

---

# 17. Second Line Responsibilities

The second line provides expertise, monitoring, challenge, and oversight.

Functions may include:

* Enterprise Risk;
* Compliance;
* Cybersecurity Governance;
* Privacy;
* Business Continuity;
* Third-Party Risk;
* Information Security Risk.

The second line does not replace operational management.

---

# 18. Third Line Responsibilities

Internal Audit provides independent assurance.

Responsibilities include:

* independent assessment;
* audit planning;
* control testing;
* governance assessment;
* reporting;
* follow-up;
* assurance over governance and risk management.

Internal Audit should remain organizationally independent.

---

# 19. GRC Process Architecture

Orion defines a common GRC process architecture.

```text
Business Objectives
        |
        v
Risk Identification
        |
        v
Risk Assessment
        |
        v
Risk Treatment
        |
        v
Control Implementation
        |
        v
Control Testing
        |
        v
Monitoring
        |
        v
Reporting
        |
        v
Management Decision
        |
        v
Continual Improvement
```

This becomes the common process backbone.

---

# 20. Integrated Compliance Process

Compliance activities are integrated into the same model.

```text
Regulation
    |
    v
Requirement
    |
    v
Applicability
    |
    v
Control
    |
    v
Evidence
    |
    v
Assessment
    |
    v
Gap
    |
    v
Remediation
    |
    v
Validation
```

Compliance therefore becomes connected to risk and controls.

---

# 21. Third-Party Risk Integration

Third-party risk is integrated into the enterprise model.

```text
Supplier
   |
   v
Classification
   |
   v
Due Diligence
   |
   v
Risk Assessment
   |
   v
Contract Controls
   |
   v
Monitoring
   |
   v
Reassessment
   |
   v
Renewal / Exit
```

Critical suppliers are also represented in the enterprise risk register where appropriate.

---

# 22. Incident and Risk Integration

Cybersecurity incidents are connected to the risk process.

```text
Security Incident
       |
       v
Investigation
       |
       v
Root Cause
       |
       v
Control Weakness
       |
       v
Risk Assessment
       |
       v
Remediation
       |
       v
Residual Risk
```

This prevents incidents from being treated only as operational events.

---

# 23. Business Continuity Integration

Business resilience is integrated into GRC.

```text
Critical Business Process
          |
          v
Business Impact Analysis
          |
          v
Recovery Requirement
          |
          v
Recovery Strategy
          |
          v
Testing
          |
          v
Resilience Risk
```

This allows resilience weaknesses to appear in enterprise risk reporting.

---

# 24. GRC Data Model

Orion establishes a common GRC data model.

```text
Business Objective
        |
        v
Risk
        |
        v
Requirement
        |
        v
Control
        |
        v
Evidence
        |
        v
Test
        |
        v
Finding
        |
        v
Remediation
        |
        v
Residual Risk
```

Each object has:

* unique identifier;
* owner;
* status;
* relationship;
* review date;
* source;
* lifecycle state.

---

# 25. Example Traceability

Consider a regulatory requirement concerning privileged access.

```text
Requirement R-027
        |
        v
Control AC-014
        |
        v
Quarterly Access Review
        |
        v
Evidence E-884
        |
        v
Control Test T-221
        |
        v
Finding F-031
        |
        v
Remediation RA-118
```

Management can trace the entire lifecycle.

---

# 26. GRC Decision Rights

The operating model defines decision authority.

| Decision                  | Primary Authority       |
| ------------------------- | ----------------------- |
| Risk methodology          | GRC Committee           |
| Risk ownership            | Business                |
| Control ownership         | Process/System Owner    |
| Risk acceptance           | Authorized Risk Owner   |
| Major risk acceptance     | Executive GRC Committee |
| Audit opinion             | Internal Audit          |
| Compliance interpretation | Compliance/Legal        |
| Security risk treatment   | Business + Security     |
| GRC standards             | GRC Office              |

This prevents governance ambiguity.

---

# 27. Risk Escalation Model

The organization defines escalation thresholds.

```text
Low Risk
   |
   v
Business Management

Medium Risk
   |
   v
Business + GRC

High Risk
   |
   v
Executive GRC Committee

Critical Risk
   |
   v
Executive Committee
        |
        v
Board Risk Committee
```

Escalation criteria include:

* financial impact;
* regulatory impact;
* customer impact;
* security impact;
* operational impact;
* reputational impact;
* risk appetite breach.

---

# 28. GRC Reporting Architecture

Reporting occurs at three levels.

### Operational

Detailed information for control and process owners.

### Management

Aggregated information for executives.

### Board

Material risks, trends, exceptions, and decisions.

```text
Operational Data
       |
       v
GRC Analytics
       |
       +---- Operational Dashboard
       |
       +---- Management Dashboard
       |
       +---- Board Dashboard
```

The same underlying data supports different audiences.

---

# 29. GRC Metrics

The organization establishes metrics for:

### Risk

* number of risks above appetite;
* overdue treatments;
* risk trend.

### Compliance

* compliance coverage;
* regulatory gaps;
* overdue remediation.

### Controls

* control effectiveness;
* failed controls;
* overdue testing.

### Audit

* open findings;
* high-risk findings;
* overdue findings.

### Third Parties

* critical suppliers assessed;
* high-risk suppliers;
* overdue assessments.

---

# 30. Technology Architecture

The target GRC technology model is:

```text
                     GRC PLATFORM
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
       Risk          Compliance          Controls
        |                  |                  |
        +------------------+------------------+
                           |
       +-------------------+-------------------+
       |                   |                   |
       v                   v                   v
     Audit            Third Party          Evidence
                           |
                           v
                     GRC Analytics
                           |
                           v
                  Executive Reporting
```

The GRC platform integrates with:

* IAM;
* SIEM;
* vulnerability management;
* ServiceNow;
* procurement;
* HR;
* cloud platforms;
* audit systems.

---

# 31. Operating Model Principles

Orion establishes ten principles.

### Principle 1 – Business Ownership

Business management owns business risks.

### Principle 2 – Clear Accountability

Every major risk and control has an accountable owner.

### Principle 3 – Independent Assurance

Internal Audit remains independent.

### Principle 4 – Common Methodology

Enterprise GRC activities use common definitions.

### Principle 5 – Risk-Based Approach

Resources are prioritized according to risk.

### Principle 6 – Integrated Data

GRC information should be connected.

### Principle 7 – Proportionality

Controls should be appropriate to the level of risk.

### Principle 8 – Transparency

Significant risk decisions should be documented.

### Principle 9 – Continuous Improvement

The GRC operating model evolves with the organization.

### Principle 10 – Business Alignment

GRC should support strategic objectives rather than operate as a separate bureaucracy.

---

# 32. RACI Example

A simplified RACI is established for enterprise risk management.

| Activity      | Business | GRC | Compliance | CISO | Internal Audit |
| ------------- | -------- | --- | ---------- | ---- | -------------- |
| Identify risk | A/R      | C   | C          | C    | I              |
| Assess risk   | R        | A   | C          | C    | I              |
| Treat risk    | A/R      | C   | C          | C    | I              |
| Monitor risk  | R        | A   | C          | C    | I              |
| Audit process | I        | C   | C          | C    | A/R            |

**R = Responsible**
**A = Accountable**
**C = Consulted**
**I = Informed**

---

# 33. Implementation Roadmap

The operating model is implemented in four stages.

## Stage 1 – Design

**Months 1–3**

* define governance;
* define roles;
* define decision rights;
* establish taxonomy;
* define processes.

## Stage 2 – Standardize

**Months 4–6**

* standardize risk;
* standardize controls;
* standardize compliance;
* establish reporting.

## Stage 3 – Integrate

**Months 7–12**

* integrate GRC processes;
* integrate technology;
* integrate evidence;
* establish enterprise dashboards.

## Stage 4 – Optimize

**Months 13–18**

* automate workflows;
* introduce continuous monitoring;
* improve analytics;
* optimize decision-making.

---

# 34. Key Implementation Challenge

The biggest challenge is organizational resistance.

Some departments argue:

> **"We already have our own process."**

Others argue:

> **"Central GRC will slow us down."**

The GRC leadership therefore adopts a **federated operating model**.

---

# 35. Federated GRC Model

The federated approach combines central standards with local execution.

```text
                 CENTRAL GRC
                     |
        +------------+------------+
        |            |            |
        v            v            v
     Business A   Business B   Business C
        |            |            |
     Local GRC     Local GRC    Local GRC
        |            |            |
        +------------+------------+
                     |
                     v
              Enterprise GRC
```

### Central GRC Provides

* standards;
* methodology;
* taxonomy;
* governance;
* reporting;
* technology.

### Business Units Provide

* risk ownership;
* control operation;
* local compliance;
* evidence;
* remediation.

---

# 36. Why the Federated Model Works

A fully centralized model could create:

* excessive bureaucracy;
* slow decision-making;
* weak business ownership.

A fully decentralized model could create:

* inconsistent methodologies;
* duplicate controls;
* fragmented reporting;
* inconsistent risk decisions.

The federated model attempts to balance both.

```text
Central Standards
        +
Local Execution
        =
Enterprise Consistency
        +
Business Ownership
```

---

# 37. Target GRC Operating Model

The final model becomes:

```text
                         BOARD
                           |
                           v
                  BOARD RISK COMMITTEE
                           |
                           v
                 EXECUTIVE GRC COMMITTEE
                           |
                           v
                    CENTRAL GRC OFFICE
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
       Risk            Compliance       Cybersecurity
          |                |                |
          +----------------+----------------+
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
      Business A       Business B       Business C
          |                |                |
          +----------------+----------------+
                           |
                           v
                    GRC DATA PLATFORM
                           |
                           v
                  METRICS & ANALYTICS
                           |
                           v
                   MANAGEMENT DECISIONS
                           |
                           v
                  CONTINUAL IMPROVEMENT
```

Internal Audit operates independently across the model.

---

# 38. Case Study Outcomes

After 18 months, Orion reports several improvements.

| Capability         | Before       | After        |
| ------------------ | ------------ | ------------ |
| Risk methodology   | Fragmented   | Standardized |
| Risk ownership     | Unclear      | Defined      |
| Control ownership  | Inconsistent | Defined      |
| Compliance mapping | Partial      | Integrated   |
| Third-party risk   | Fragmented   | Risk-based   |
| Reporting          | Departmental | Enterprise   |
| GRC data           | Distributed  | Integrated   |
| Escalation         | Informal     | Structured   |
| Audit integration  | Limited      | Improved     |

The overall GRC maturity increases from approximately **2.4/5 to 3.7/5**.

---

# 39. Lessons Learned

### Lesson 1 – GRC Is an Operating Model

GRC is not simply a department.

It is a way of coordinating governance, risk, compliance, controls, assurance, and decision-making.

### Lesson 2 – Ownership Must Remain with the Business

The GRC function should not become the owner of every risk.

### Lesson 3 – Independence Matters

Internal Audit should not become part of operational risk management.

### Lesson 4 – Centralization Has Limits

Standards can be centralized while execution remains distributed.

### Lesson 5 – Data Integration Is Critical

Disconnected GRC information creates fragmented decision-making.

### Lesson 6 – Decision Rights Must Be Explicit

Everyone should understand who can:

* approve;
* accept;
* escalate;
* challenge;
* monitor;
* assure.

---

# 40. Final Case Study Model

The complete operating model can be summarized as:

```text
                    BUSINESS STRATEGY
                           |
                           v
                     GOVERNANCE
                           |
                           v
                     RISK OWNERS
                           |
              +------------+------------+
              |            |            |
              v            v            v
          Compliance    Controls    Cybersecurity
              |            |            |
              +------------+------------+
                           |
                           v
                     GRC DATA
                           |
                           v
                   MONITORING & METRICS
                           |
                           v
                    MANAGEMENT ACTION
                           |
                           v
                    EXECUTIVE OVERSIGHT
                           |
                           v
                 INDEPENDENT ASSURANCE
                           |
                           v
                   CONTINUAL IMPROVEMENT
```

## Case Study Conclusion

The Orion case demonstrates that designing a GRC operating model requires much more than defining reporting lines.

A successful operating model establishes **governance, accountability, decision rights, processes, data, technology, reporting, and assurance**.

The central principle is:

> **Centralize what must be consistent; federate what should remain close to the business.**

The ultimate objective is to create a GRC environment in which:

**Business owns risk → GRC coordinates and challenges → Controls manage risk → Data provides visibility → Executives make decisions → Internal Audit provides independent assurance.**

That structure creates a GRC capability that is **accountable, integrated, risk-based, and aligned with business objectives**.


