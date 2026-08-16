# 19.4 Cybersecurity Risk Management Case Studies

## Part 1 – Enterprise Cybersecurity Risk Assessment

## 1. Case Study Overview

This case study demonstrates how an organization performs an **enterprise cybersecurity risk assessment** across business services, technology, information assets, third parties, and regulatory obligations.

The objective is to move beyond isolated technical vulnerability assessments and establish a business-oriented view of cybersecurity risk.

The case demonstrates the relationship between:

**Assets → Threats → Vulnerabilities → Business Impact → Inherent Risk → Controls → Residual Risk → Risk Treatment**

---

# 2. Organization Profile

### Company

**GlobalConnect Communications**

### Industry

Telecommunications and Digital Services

### Employees

Approximately 11,000

### Annual Revenue

Approximately €3.4 billion

### Geographic Presence

* Spain
* France
* Portugal
* Germany
* Qatar
* Saudi Arabia

### Critical Services

* Mobile telecommunications
* Broadband
* Enterprise connectivity
* Cloud services
* Customer applications
* Digital payment services
* Customer identity services

---

# 3. Business Context

GlobalConnect is undergoing a digital transformation.

The organization is:

* migrating workloads to cloud platforms;
* expanding digital customer services;
* deploying IoT services;
* integrating third-party platforms;
* modernizing customer applications.

These initiatives create new cybersecurity risks.

Management therefore decides to perform an enterprise cybersecurity risk assessment before finalizing the next three-year security strategy.

---

# 4. Risk Assessment Objectives

The assessment aims to determine:

1. What are the organization's most important cyber risks?
2. Which business services are most exposed?
3. Which threats could cause significant harm?
4. Which controls currently reduce those risks?
5. Which risks remain above appetite?
6. Which risks require immediate treatment?
7. Where should cybersecurity investment be prioritized?

---

# 5. Assessment Scope

The assessment covers:

### Business Services

* customer management;
* billing;
* mobile network;
* enterprise services;
* cloud services.

### Technology

* applications;
* networks;
* cloud;
* endpoints;
* identity platforms.

### Information

* customer data;
* financial information;
* authentication data;
* operational information.

### Third Parties

* cloud providers;
* managed service providers;
* payment providers;
* software suppliers.

---

# 6. Risk Assessment Methodology

GlobalConnect adopts a structured methodology.

```text
Business Context
      |
      v
Asset / Service Identification
      |
      v
Threat Identification
      |
      v
Vulnerability Analysis
      |
      v
Impact Assessment
      |
      v
Likelihood Assessment
      |
      v
Inherent Risk
      |
      v
Control Assessment
      |
      v
Residual Risk
      |
      v
Treatment Decision
```

---

# 7. Business-Centric Risk Assessment

The organization does not begin with:

> "What vulnerabilities do we have?"

Instead, it begins with:

> **"What business services must we protect, and what would happen if they were compromised?"**

This ensures that cybersecurity risk is connected to business objectives.

---

# 8. Critical Business Services

The organization identifies five critical services.

| Service             | Criticality |
| ------------------- | ----------- |
| Mobile Network      | Very High   |
| Customer Management | Very High   |
| Billing             | High        |
| Cloud Services      | High        |
| Digital Payment     | High        |

The mobile network and customer management platforms receive the highest protection priority.

---

# 9. Asset Identification

Each critical service is mapped to supporting assets.

For example:

### Customer Management Service

Includes:

* customer database;
* web application;
* API gateway;
* identity platform;
* cloud infrastructure;
* network components.

This creates a relationship between business services and technology assets.

---

# 10. Information Classification

The assessment identifies the information handled by each service.

Examples:

### Customer Management

* names;
* addresses;
* account information;
* authentication information;
* service information.

### Billing

* billing records;
* payment information;
* transaction history.

### Network Operations

* network configurations;
* infrastructure information;
* operational data.

---

# 11. Threat Identification

The assessment identifies relevant threat scenarios.

Examples include:

* ransomware;
* credential compromise;
* phishing;
* insider threat;
* supply-chain compromise;
* DDoS;
* cloud misconfiguration;
* application exploitation;
* data theft.

Threats are prioritized according to relevance to the organization.

---

# 12. Vulnerability Identification

The assessment identifies weaknesses that could allow threats to succeed.

Examples:

* outdated software;
* weak authentication;
* excessive privileges;
* insecure APIs;
* insufficient monitoring;
* cloud misconfiguration;
* unpatched systems;
* inadequate supplier controls.

---

# 13. Risk Scenario Construction

Instead of simply recording:

> "Unpatched server"

the organization creates a complete risk scenario.

Example:

> **A threat actor exploits an unpatched internet-facing application server, gaining unauthorized access to customer information and causing service disruption.**

This creates a clearer connection between vulnerability and business consequence.

---

# 14. Impact Assessment

GlobalConnect assesses impact across five dimensions.

### Confidentiality

Could sensitive information be disclosed?

### Integrity

Could information or systems be manipulated?

### Availability

Could services become unavailable?

### Financial

Could the organization suffer financial losses?

### Regulatory/Reputational

Could the incident cause regulatory or reputational consequences?

---

# 15. Impact Scale

The organization uses a five-level scale.

| Score | Impact        |
| ----: | ------------- |
|     1 | Insignificant |
|     2 | Minor         |
|     3 | Moderate      |
|     4 | Major         |
|     5 | Severe        |

The highest relevant impact dimension is considered during risk evaluation.

---

# 16. Likelihood Assessment

Likelihood is also scored from 1 to 5.

| Score | Likelihood     |
| ----: | -------------- |
|     1 | Rare           |
|     2 | Unlikely       |
|     3 | Possible       |
|     4 | Likely         |
|     5 | Almost Certain |

Factors considered include:

* threat capability;
* exposure;
* vulnerability;
* exploit availability;
* control strength;
* historical activity.

---

# 17. Inherent Risk

Inherent risk represents the level of risk **before considering existing controls**.

A simplified model is:

**Inherent Risk = Impact × Likelihood**

For example:

Impact = 5

Likelihood = 4

Therefore:

**Inherent Risk = 20**

The organization classifies this as **Critical**.

---

# 18. Risk Matrix

```text
                 LIKELIHOOD
              1   2   3   4   5

Impact 5      M   H   H   C   C
       4      M   M   H   H   C
       3      L   M   M   H   H
       2      L   L   M   M   H
       1      L   L   L   M   M
```

Where:

* **L = Low**
* **M = Medium**
* **H = High**
* **C = Critical**

The exact thresholds should be defined in the organization's risk methodology.

---

# 19. Example Risk Scenario

### Risk ID

CYB-001

### Business Service

Customer Management

### Threat

External attacker

### Vulnerability

Internet-facing application vulnerability

### Impact

5 – Severe

### Likelihood

4 – Likely

### Inherent Risk

20 – Critical

---

# 20. Existing Controls

GlobalConnect identifies the following controls:

* web application firewall;
* vulnerability management;
* endpoint protection;
* MFA;
* network segmentation;
* SIEM monitoring;
* secure development;
* penetration testing.

The assessment then evaluates whether these controls are actually effective.

---

# 21. Control Effectiveness

Controls are rated:

| Rating | Effectiveness         |
| ------ | --------------------- |
| 1      | Ineffective           |
| 2      | Partially Effective   |
| 3      | Effective             |
| 4      | Highly Effective      |
| 5      | Very Highly Effective |

The organization does not assume that an implemented control is automatically effective.

---

# 22. Control Testing

For the application vulnerability scenario, the assessment verifies:

* vulnerability scans;
* patching records;
* WAF configuration;
* penetration-testing results;
* monitoring;
* incident records.

The evidence indicates that controls are partially effective.

---

# 23. Residual Risk

After considering controls, the risk is reassessed.

### Inherent Risk

**20 – Critical**

### Control Effectiveness

**Moderate**

### Residual Risk

**12 – High**

The risk has decreased but remains above the organization's acceptable threshold.

---

# 24. Risk Appetite

GlobalConnect establishes a cybersecurity risk appetite.

For critical customer-facing services:

> **No Critical residual cybersecurity risk is acceptable without explicit executive approval and documented treatment.**

The residual risk of 12 therefore requires management action.

---

# 25. Risk Treatment Options

The organization considers four major treatment strategies.

### Avoid

Stop the risky activity.

### Reduce

Implement additional controls.

### Transfer

Transfer part of the financial or contractual exposure.

### Accept

Formally accept the remaining risk.

---

# 26. Treatment Decision

For CYB-001, management chooses:

**Risk Reduction**

Additional controls will include:

* accelerated patching;
* stronger application testing;
* improved API security;
* enhanced monitoring;
* additional penetration testing.

---

# 27. Risk Treatment Plan

| Action                          | Owner            | Due Date | Priority |
| ------------------------------- | ---------------- | -------- | -------- |
| Patch vulnerable platform       | IT               | 30 days  | Critical |
| Implement API security controls | AppSec           | 60 days  | High     |
| Conduct penetration test        | Security         | 45 days  | High     |
| Review WAF rules                | Network Security | 30 days  | High     |
| Validate monitoring             | SOC              | 30 days  | High     |

---

# 28. Risk Ownership

The risk is assigned to the:

**Director of Digital Services**

Cybersecurity GRC provides:

* methodology;
* analysis;
* challenge;
* monitoring;
* reporting.

The business owner remains accountable for the business risk.

---

# 29. Enterprise Risk Register

The assessment identifies multiple risks.

| ID      | Risk                     | Inherent | Residual |
| ------- | ------------------------ | -------: | -------: |
| CYB-001 | Application exploitation | Critical |     High |
| CYB-002 | Ransomware               | Critical |     High |
| CYB-003 | Cloud misconfiguration   |     High |   Medium |
| CYB-004 | Supplier compromise      |     High |     High |
| CYB-005 | Credential compromise    |     High |   Medium |
| CYB-006 | DDoS                     |     High |   Medium |

This gives management a consolidated view of cyber risk.

---

# 30. Risk Aggregation

Individual risks can create a larger enterprise exposure.

For example:

* identity compromise;
* cloud misconfiguration;
* privileged access weaknesses.

Individually, they may appear manageable.

Together, they could enable a major cloud compromise.

Therefore, GlobalConnect also performs **risk aggregation and dependency analysis**.

---

# 31. Risk Interdependencies

```text
Credential Compromise
          |
          v
Privileged Access
          |
          v
Cloud Environment
          |
          v
Customer Platform
          |
          v
Customer Data Exposure
```

This illustrates why cybersecurity risk should not always be evaluated as isolated risks.

---

# 32. Third-Party Risk

GlobalConnect identifies a major cloud provider as a critical dependency.

The provider supports:

* customer applications;
* data storage;
* APIs;
* analytics.

A supplier compromise could therefore affect multiple business services simultaneously.

The supplier risk is classified as:

**High Residual Risk**

---

# 33. Risk Concentration

Management identifies a concentration risk.

Several critical services depend on the same:

* cloud provider;
* identity provider;
* network provider.

This creates systemic exposure.

The organization therefore considers:

* redundancy;
* alternative providers;
* resilience;
* contractual controls;
* exit strategies.

---

# 34. Risk Treatment Prioritization

The organization ranks risks according to:

1. residual risk;
2. business criticality;
3. regulatory impact;
4. threat likelihood;
5. treatment urgency;
6. cost of remediation.

The highest risks receive priority.

---

# 35. Executive Risk Dashboard

The CISO presents the following summary:

```text
CYBERSECURITY RISK PROFILE

Critical Risks:        2
High Risks:            4
Medium Risks:          7
Low Risks:             12

RISKS ABOVE APPETITE:
• Customer application
• Third-party cloud dependency
• Ransomware exposure

TOP MANAGEMENT DECISIONS:
• Approve application modernization
• Increase supplier resilience investment
• Accelerate identity security program
```

This converts the risk assessment into executive decision support.

---

# 36. Risk Assessment and Budgeting

The assessment influences cybersecurity investment.

Instead of distributing the budget equally across all security capabilities, management prioritizes areas associated with the greatest risk.

Priority investments include:

* identity security;
* application security;
* cloud security;
* third-party resilience;
* ransomware protection.

---

# 37. Risk Treatment Monitoring

Risk treatment is monitored monthly.

The GRC team tracks:

* action status;
* overdue remediation;
* residual risk;
* control effectiveness;
* risk acceptance;
* evidence.

A risk is not automatically closed simply because a remediation task has been marked "complete."

---

# 38. Risk Closure

A risk can be closed only after:

1. treatment is implemented;
2. evidence is collected;
3. control effectiveness is validated;
4. residual risk is reassessed;
5. risk owner confirms the outcome.

This prevents premature closure.

---

# 39. Continuous Risk Monitoring

The organization moves toward continuous monitoring.

Relevant indicators include:

* threat intelligence;
* vulnerability data;
* security incidents;
* cloud configuration;
* identity events;
* supplier risk;
* control performance.

These indicators can trigger reassessment.

---

# 40. Risk Assessment Lifecycle

```text
Business Context
      |
      v
Risk Identification
      |
      v
Risk Analysis
      |
      v
Risk Evaluation
      |
      v
Risk Treatment
      |
      v
Risk Acceptance
      |
      v
Risk Monitoring
      |
      v
Risk Review
      |
      +-----------> Reassessment
```

Risk management is therefore continuous rather than a once-a-year exercise.

---

# 41. Governance Integration

The cybersecurity risk assessment is integrated with:

* enterprise risk management;
* ISO 27001 ISMS;
* NIST CSF;
* internal audit;
* compliance;
* third-party risk management.

This prevents cybersecurity risk from becoming an isolated security activity.

---

# 42. Assessment Evidence

The GRC team maintains evidence such as:

* risk assessments;
* risk register;
* vulnerability reports;
* control testing;
* penetration tests;
* business impact assessments;
* supplier assessments;
* treatment plans;
* risk acceptance records.

Evidence supports auditability and management confidence.

---

# 43. Common Assessment Errors

GlobalConnect identifies several common mistakes.

### Error 1

Treating vulnerabilities as risks without business context.

### Error 2

Assuming implemented controls are automatically effective.

### Error 3

Ignoring third-party dependencies.

### Error 4

Failing to distinguish inherent and residual risk.

### Error 5

Allowing risks to remain open indefinitely.

### Error 6

Using technical metrics instead of risk indicators.

---

# 44. Lessons Learned

## Lesson 1 – Start With Business Services

Cybersecurity risk should be connected to what the business is trying to protect.

## Lesson 2 – Use Risk Scenarios

A complete risk scenario provides more value than a list of vulnerabilities.

## Lesson 3 – Evaluate Controls

Control existence does not equal control effectiveness.

## Lesson 4 – Residual Risk Matters

Management decisions should focus on the risk remaining after controls.

## Lesson 5 – Risk Ownership Must Be Clear

Every significant risk requires an accountable owner.

---

# 45. Additional Lessons

## Lesson 6 – Risk Is Dynamic

Changes in:

* technology;
* threats;
* business processes;
* suppliers;
* regulations

can change risk levels.

## Lesson 7 – Aggregate Risk Matters

Several moderate risks can combine into a significant enterprise exposure.

## Lesson 8 – Risk Assessment Supports Investment

Risk analysis should influence cybersecurity funding and priorities.

## Lesson 9 – Risk Treatment Requires Verification

A completed action does not necessarily mean the risk has been reduced sufficiently.

---

# 46. Practical Enterprise Cybersecurity Risk Assessment Checklist

### Context

* [ ] Business objectives identified
* [ ] Critical services identified
* [ ] Risk appetite defined
* [ ] Assessment scope established

### Risk Identification

* [ ] Assets identified
* [ ] Threats identified
* [ ] Vulnerabilities identified
* [ ] Business impact identified
* [ ] Risk scenarios documented

### Analysis

* [ ] Impact assessed
* [ ] Likelihood assessed
* [ ] Inherent risk calculated
* [ ] Existing controls identified
* [ ] Control effectiveness assessed
* [ ] Residual risk calculated

### Treatment

* [ ] Treatment strategy selected
* [ ] Actions defined
* [ ] Risk owner assigned
* [ ] Due dates established
* [ ] Risk acceptance documented where applicable

### Monitoring

* [ ] Risk register maintained
* [ ] Treatment monitored
* [ ] KRIs established
* [ ] Risk reassessed
* [ ] Evidence retained

---

# 47. Final Enterprise Cybersecurity Risk Model

```text
                    BUSINESS OBJECTIVES
                           |
                           v
                    CRITICAL SERVICES
                           |
                           v
                   ASSETS & INFORMATION
                           |
                           v
                 THREATS & VULNERABILITIES
                           |
                           v
                    IMPACT + LIKELIHOOD
                           |
                           v
                     INHERENT RISK
                           |
                           v
                       CONTROLS
                           |
                           v
                  CONTROL EFFECTIVENESS
                           |
                           v
                     RESIDUAL RISK
                           |
             +-------------+-------------+
             |             |             |
             v             v             v
           Reduce        Transfer      Accept
             |             |             |
             +-------------+-------------+
                           |
                           v
                    RISK MONITORING
                           |
                           v
                  EXECUTIVE DECISIONS
                           |
                           +----------↺
```

# 48. Case Study Conclusion

The GlobalConnect case demonstrates how an enterprise cybersecurity risk assessment can provide management with a structured understanding of cyber exposure.

The complete process is:

**Business Context → Risk Identification → Risk Analysis → Inherent Risk → Control Assessment → Residual Risk → Treatment → Acceptance → Monitoring**

The most important principle is that cybersecurity risk should ultimately be expressed in terms of **business impact and decision-making**.

A GRC professional should therefore be able to answer not only:

> "What security vulnerabilities exist?"

but also:

> **"What business risk do these vulnerabilities create, how effective are the existing controls, what risk remains, who owns it, and what decision should management make?"**

That is the foundation of effective enterprise cybersecurity risk management.

# 19.4 Cybersecurity Risk Management Case Studies

## Part 2 – Cybersecurity Risk Treatment and Risk Acceptance Case Study

## 1. Case Study Overview

This case study demonstrates how an organization manages cybersecurity risks after they have been identified and assessed.

The focus is on the transition from:

**Risk Identification → Risk Evaluation → Risk Treatment → Risk Acceptance → Risk Monitoring**

The case illustrates how a GRC professional helps management determine:

* which risks should be reduced;
* which risks can be transferred;
* which risks should be avoided;
* which risks may be accepted;
* who has authority to accept risk;
* when residual risk is acceptable.

---

# 2. Organization Profile

### Company

**ApexTel Enterprise Services**

### Industry

Telecommunications and Managed Digital Services

### Employees

Approximately 7,500

### Annual Revenue

Approximately €2.1 billion

### Critical Services

* Enterprise connectivity
* Cloud services
* Managed security
* Customer portals
* Data centers
* Collaboration platforms

---

# 3. Current Risk Situation

ApexTel recently completed an enterprise cybersecurity risk assessment.

The assessment identified **18 significant cybersecurity risks**.

Management now needs to determine how those risks should be treated.

The organization cannot eliminate every cybersecurity risk.

Therefore, management must make deliberate, documented, risk-based decisions.

---

# 4. Risk Treatment Principles

ApexTel establishes four primary treatment strategies:

### Avoid

Stop the activity creating the risk.

### Reduce

Implement controls that reduce likelihood or impact.

### Transfer

Shift some financial or contractual consequences to another party.

### Accept

Retain the risk within approved risk appetite.

These strategies are not mutually exclusive.

A risk may use several treatment approaches simultaneously.

---

# 5. Risk Treatment Decision Model

```text id="c7r2m9"
                 IDENTIFIED RISK
                       |
                       v
                RISK EVALUATION
                       |
                       v
              ABOVE RISK APPETITE?
                 /             \
               YES              NO
                |                |
                v                v
          TREATMENT          MONITOR
                |
       +--------+--------+
       |        |        |
       v        v        v
     Avoid    Reduce   Transfer
       |        |        |
       +--------+--------+
                |
                v
          RESIDUAL RISK
                |
                v
          ACCEPT / RE-TREAT
```

---

# 6. Risk Appetite

ApexTel establishes the following principles:

### Critical Customer Services

No critical residual risk should remain without executive approval.

### Regulatory Compliance

Regulatory non-compliance risks generally require treatment.

### Low-Risk Operational Activities

Management may accept some low-level residual risk.

### Strategic Innovation

Higher temporary risks may be accepted where they support approved business objectives and appropriate safeguards exist.

---

# 7. Risk Acceptance Authority

A formal authority structure is created.

| Risk Level                             | Acceptance Authority                  |
| -------------------------------------- | ------------------------------------- |
| Low                                    | Operational Manager                   |
| Medium                                 | Business Director                     |
| High                                   | Executive Management                  |
| Critical                               | Executive Risk Committee              |
| Critical and materially above appetite | Board / delegated executive authority |

The actual thresholds are defined in the organization's risk management policy.

---

# 8. Risk Treatment Portfolio

The assessment identifies five major risks requiring management decisions.

| Risk                    | Residual Risk | Proposed Treatment |
| ----------------------- | ------------- | ------------------ |
| Legacy application      | Critical      | Reduce             |
| Cloud dependency        | High          | Transfer + Reduce  |
| Unsupported system      | High          | Avoid              |
| Phishing exposure       | Medium        | Reduce             |
| Low-risk legacy process | Low           | Accept             |

Each requires a different strategy.

---

# 9. Risk 1 – Legacy Application

ApexTel operates a customer application developed more than ten years ago.

The application:

* contains customer information;
* has limited security functionality;
* uses outdated components;
* is difficult to patch.

### Residual Risk

**Critical**

The risk is above appetite.

---

# 10. Treatment Options

The organization considers:

### Option A – Accept

Not recommended because the risk is critical.

### Option B – Transfer

Cyber insurance may help with some financial consequences but does not eliminate the security exposure.

### Option C – Reduce

Implement additional security controls.

### Option D – Avoid

Retire the application.

---

# 11. Treatment Decision

Management chooses a two-stage strategy:

**Short Term – Reduce**

* segmentation;
* additional monitoring;
* WAF;
* privileged access controls;
* enhanced logging.

**Long Term – Avoid**

Retire the legacy application and migrate customers to the modern platform.

---

# 12. Risk Treatment Plan

| Action                   | Owner                | Target    |
| ------------------------ | -------------------- | --------- |
| Network segmentation     | Network Security     | 30 days   |
| WAF enhancement          | Security Engineering | 45 days   |
| Privileged access review | IAM                  | 30 days   |
| Application replacement  | Digital Services     | 12 months |
| Final system retirement  | CIO                  | 15 months |

The risk is monitored throughout the transition.

---

# 13. Risk 2 – Cloud Dependency

ApexTel depends heavily on a major cloud provider.

The provider hosts:

* customer applications;
* data analytics;
* enterprise systems.

A major provider outage could affect multiple business services.

### Residual Risk

**High**

---

# 14. Treatment Decision

Management chooses:

**Reduce + Transfer**

### Reduce

* multi-region architecture;
* backup;
* disaster recovery;
* resilience testing;
* service monitoring.

### Transfer

* contractual service-level agreements;
* liability clauses;
* contractual security requirements;
* appropriate insurance.

---

# 15. Important GRC Principle

The organization recognizes:

> **Risk transfer does not eliminate the underlying cybersecurity risk.**

A contractual agreement may transfer financial consequences, but operational, reputational, regulatory, and customer impacts may remain.

Therefore, residual risk must still be monitored.

---

# 16. Risk 3 – Unsupported System

A small internal system runs on an operating system that is no longer supported by the vendor.

The system is not business-critical.

However, it cannot receive normal security patches.

### Residual Risk

**High**

---

# 17. Treatment Options

ApexTel evaluates:

* upgrade;
* replacement;
* isolation;
* additional monitoring;
* retirement.

The system has limited business value.

Therefore, management decides to:

**Avoid the risk by retiring the system.**

---

# 18. Risk Avoidance

The retirement plan includes:

1. identify system dependencies;
2. identify affected users;
3. migrate required information;
4. disable access;
5. securely dispose of the system;
6. verify retirement;
7. update the asset inventory;
8. close the risk.

This demonstrates that risk avoidance often requires business-process change.

---

# 19. Risk 4 – Phishing

ApexTel identifies phishing as a persistent threat.

The assessment finds:

* high attack volume;
* moderate employee susceptibility;
* strong email filtering;
* MFA;
* security awareness training.

### Residual Risk

**Medium**

The risk remains within the organization's defined tolerance but can still be improved.

---

# 20. Treatment Decision

Management chooses:

**Risk Reduction**

Measures include:

* phishing-resistant MFA;
* security awareness;
* simulated phishing;
* email security;
* browser protection;
* incident reporting.

The organization establishes measurable targets.

---

# 21. Example Metrics

### KPI

Percentage of employees completing security training.

### KRI

Percentage of users interacting with simulated phishing campaigns.

### Additional KRI

Number of successful credential compromise attempts.

These metrics help determine whether treatment is actually reducing risk.

---

# 22. Risk 5 – Low-Risk Legacy Process

A manual internal process creates a minor cybersecurity exposure.

The process:

* has low business impact;
* involves no sensitive information;
* has limited external exposure;
* would be expensive to automate.

### Residual Risk

**Low**

The risk falls within risk appetite.

Management decides to:

**Accept the risk.**

---

# 23. Formal Risk Acceptance

The acceptance record includes:

* risk ID;
* risk statement;
* risk rating;
* affected assets;
* business impact;
* existing controls;
* residual risk;
* justification;
* risk owner;
* approval authority;
* acceptance date;
* review date;
* expiration date where applicable.

Risk acceptance is therefore an explicit management decision.

---

# 24. Example Risk Acceptance Record

```text id="v6n3r1"
Risk ID: CYB-018

Risk:
Manual internal process may result in minor
unauthorized access exposure.

Residual Risk:
Low

Risk Owner:
Operations Director

Treatment:
Accept

Reason:
Cost of remediation exceeds expected risk reduction
and the activity remains within approved risk appetite.

Approval:
Operations Director

Review:
12 months
```

---

# 25. Risk Acceptance Is Not Risk Ignorance

A common misconception is:

> "Risk acceptance means management does nothing."

This is incorrect.

A valid risk acceptance means:

1. the risk is understood;
2. the impact is understood;
3. controls have been evaluated;
4. the risk is within appetite or explicitly authorized;
5. an accountable person accepts it;
6. the decision is periodically reviewed.

---

# 26. Risk Acceptance vs Risk Approval

These concepts should be distinguished.

### Risk Approval

Authorization to proceed with an activity or project.

### Risk Acceptance

Formal acknowledgment that a residual risk will remain.

A project approval does not automatically constitute risk acceptance.

---

# 27. Temporary Risk Acceptance

Some risks may be temporarily accepted.

For example:

A critical application requires six months for replacement.

Management may authorize temporary operation under additional controls.

The acceptance should include:

* expiration date;
* treatment plan;
* compensating controls;
* monitoring;
* escalation conditions.

---

# 28. Temporary Acceptance Model

```text id="p8m4x2"
Risk Identified
      |
      v
Temporary Treatment
      |
      v
Compensating Controls
      |
      v
Executive Acceptance
      |
      v
Defined Expiration
      |
      v
Continuous Monitoring
      |
      +----> Remediate
      |
      +----> Reassess
      |
      +----> Escalate
```

Temporary acceptance should never become an informal permanent condition.

---

# 29. Risk Treatment Cost Analysis

Management compares treatment cost with risk reduction.

Example:

### Option A

€1.5 million security modernization

Expected significant risk reduction.

### Option B

€300,000 compensating controls

Moderate risk reduction.

### Option C

Risk acceptance

No immediate investment but continued exposure.

Management does not select the cheapest option automatically.

It evaluates:

**Cost + Risk + Business Impact + Regulatory Requirements + Strategic Objectives**

---

# 30. Risk-Based Investment Decision

The organization chooses Option B as an interim measure and Option A as the strategic solution.

This illustrates:

> **Risk treatment should consider both immediate risk reduction and long-term risk transformation.**

---

# 31. Risk Treatment Tracking

The GRC team maintains a treatment register.

| Risk               | Action       | Owner | Due       | Status      |
| ------------------ | ------------ | ----- | --------- | ----------- |
| Legacy application | Segmentation | CISO  | 30 days   | Complete    |
| Legacy application | Replacement  | CIO   | 12 months | In progress |
| Cloud dependency   | DR testing   | CTO   | 90 days   | In progress |
| Unsupported system | Retirement   | IT    | 60 days   | Complete    |
| Phishing           | MFA upgrade  | IAM   | 90 days   | In progress |

---

# 32. Risk Treatment Validation

A treatment action is not considered complete merely because the owner says:

> "Completed."

GRC verifies:

* implementation evidence;
* control effectiveness;
* updated risk rating;
* residual risk.

For example:

**Action:** Implement MFA.

The GRC team verifies:

* MFA configuration;
* coverage;
* privileged accounts;
* exceptions;
* authentication logs.

---

# 33. Residual Risk Reassessment

After treatment, the legacy application risk is reassessed.

### Before Treatment

Likelihood = 5

Impact = 5

Inherent Risk = 25

### After Interim Controls

Likelihood = 3

Impact = 5

Residual Risk = 15

The risk decreases but remains **High**.

Therefore, the long-term application replacement remains necessary.

---

# 34. Risk Treatment Effectiveness

The organization asks:

> "Did the treatment actually reduce risk?"

This requires comparison of:

**Before Treatment → After Treatment**

Example:

```text id="j3v9k5"
Inherent Risk
     25
      |
      v
Security Controls
      |
      v
Residual Risk
     15
      |
      v
Additional Treatment
      |
      v
Target Risk
      8
```

The objective is not simply to complete actions but to reach an acceptable risk level.

---

# 35. Risk Appetite and Treatment Decisions

The organization establishes a decision model.

```text id="t4q6m8"
Residual Risk
      |
      v
Compare with Risk Appetite
      |
 +----+----+
 |         |
Within    Above
Appetite  Appetite
 |         |
 v         v
Accept   Treat /
Monitor  Escalate
```

This creates consistency across the organization.

---

# 36. Risk Escalation

A risk must be escalated when:

* it exceeds risk appetite;
* treatment is overdue;
* compensating controls fail;
* threat conditions change;
* business impact increases;
* regulatory requirements change.

Escalation is therefore triggered by defined conditions rather than personal judgment alone.

---

# 37. Risk Committee Review

The Executive Risk Committee reviews:

* risks above appetite;
* overdue treatment;
* temporary acceptance;
* critical third-party risks;
* major strategic risks.

The committee does not manage technical remediation directly.

Its role is to make appropriate risk decisions.

---

# 38. Board-Level Risk Acceptance

Some risks may require board involvement.

Examples:

* major customer data exposure;
* critical infrastructure risk;
* significant regulatory exposure;
* major strategic technology dependency.

The board should not routinely approve operational risks.

Board-level involvement should be reserved for material enterprise risks.

---

# 39. Risk Transfer Through Insurance

ApexTel evaluates cyber insurance.

Insurance may help address:

* incident response costs;
* business interruption;
* certain liability exposures;
* recovery expenses.

However, insurance does not replace:

* security controls;
* risk management;
* regulatory compliance;
* resilience.

---

# 40. Risk Transfer Through Contracts

For third parties, ApexTel uses contractual mechanisms including:

* security requirements;
* incident notification;
* audit rights;
* service-level agreements;
* data protection requirements;
* liability provisions;
* business continuity requirements.

Contracts reduce certain exposures but do not eliminate operational dependency.

---

# 41. Risk Avoidance Through Architecture

The organization also uses architectural decisions to avoid risk.

For example:

Instead of exposing an internal management interface directly to the internet, ApexTel redesigns the architecture so that access occurs through:

* VPN;
* zero-trust access;
* privileged access management;
* controlled administrative gateways.

The risky exposure is removed rather than simply monitored.

---

# 42. Risk Reduction Through Controls

Risk reduction can involve:

### Preventive Controls

* MFA;
* segmentation;
* secure configuration.

### Detective Controls

* SIEM;
* monitoring;
* threat detection.

### Corrective Controls

* incident response;
* recovery;
* remediation.

A mature treatment strategy often uses multiple control types.

---

# 43. Risk Treatment Decision Matrix

| Situation                                       | Preferred Approach               |
| ----------------------------------------------- | -------------------------------- |
| Activity creates unacceptable exposure          | Avoid                            |
| Risk can be reduced economically                | Reduce                           |
| Financial exposure can be contractually shifted | Transfer                         |
| Risk is low and within appetite                 | Accept                           |
| Risk is temporary during transformation         | Temporary acceptance + treatment |

The final decision remains management's responsibility.

---

# 44. Governance Responsibilities

### Business Owner

Owns the business risk.

### Cybersecurity GRC

Provides methodology and challenge.

### Security Teams

Implement technical controls.

### Risk Function

Coordinates enterprise risk integration.

### Compliance

Identifies regulatory obligations.

### Internal Audit

Provides independent assurance.

---

# 45. Common Risk Treatment Mistakes

## Mistake 1 – Treating Everything

Not every risk requires maximum investment.

## Mistake 2 – Accepting Everything

Risk acceptance should not become a way to avoid difficult remediation.

## Mistake 3 – Treating Insurance as Security

Insurance cannot prevent an attack.

## Mistake 4 – Ignoring Business Context

Security treatment must consider business objectives.

## Mistake 5 – Closing Risks Too Early

Treatment completion does not automatically mean risk reduction.

---

# 46. Practical Risk Treatment Checklist

### Risk Analysis

* [ ] Risk statement documented
* [ ] Inherent risk assessed
* [ ] Existing controls evaluated
* [ ] Residual risk calculated
* [ ] Risk appetite compared

### Treatment

* [ ] Avoidance considered
* [ ] Reduction considered
* [ ] Transfer considered
* [ ] Acceptance considered
* [ ] Treatment decision documented

### Accountability

* [ ] Risk owner assigned
* [ ] Treatment owner assigned
* [ ] Approval authority confirmed
* [ ] Escalation criteria defined

### Monitoring

* [ ] Treatment actions tracked
* [ ] Evidence collected
* [ ] Control effectiveness validated
* [ ] Residual risk reassessed
* [ ] Acceptance reviewed

---

# 47. Final Risk Treatment Model

```text id="g8c4m7"
                  RISK ASSESSMENT
                        |
                        v
                  RESIDUAL RISK
                        |
                        v
                  RISK APPETITE
                        |
             +----------+----------+
             |                     |
       Within Appetite        Above Appetite
             |                     |
             v                     v
          ACCEPT              TREAT / ESCALATE
                                   |
                    +--------------+--------------+
                    |              |              |
                    v              v              v
                  AVOID          REDUCE        TRANSFER
                    |              |              |
                    +--------------+--------------+
                                   |
                                   v
                           RESIDUAL RISK
                                   |
                                   v
                              VALIDATION
                                   |
                                   v
                              MONITORING
                                   |
                                   +--------↺
```

# 48. Case Study Conclusion

The ApexTel case demonstrates that cybersecurity risk treatment is fundamentally a **management decision process**, supported by cybersecurity expertise and GRC governance.

The key sequence is:

**Assess → Compare with Appetite → Select Treatment → Assign Ownership → Implement → Validate → Accept or Re-Treat → Monitor**

A mature GRC professional should be able to explain why a particular treatment strategy was selected and demonstrate that the resulting residual risk is understood and appropriately authorized.

Most importantly:

> **Risk acceptance should be a conscious, documented, accountable business decision—not the absence of action.**

Effective risk treatment therefore balances **security, business objectives, regulatory obligations, cost, resilience, and organizational risk appetite**.

# 19.4 Cybersecurity Risk Management Case Studies

## Part 3 – Cybersecurity Risk Monitoring, KRIs and Executive Risk Reporting

## 1. Case Study Overview

This case study demonstrates how an organization moves from a **periodic cybersecurity risk assessment** to a continuous risk monitoring and executive reporting model.

The organization already has:

* a cybersecurity risk register;
* defined risk appetite;
* risk owners;
* treatment plans;
* security controls.

However, management discovers that the risk register does not always reflect the organization's current exposure.

The objective is to establish a system that continuously identifies changes in risk and converts them into meaningful information for management and the board.

The core model is:

**Risk → Indicator → Threshold → Escalation → Decision → Action → Reassessment**

---

# 2. Organization Profile

### Company

**EuroSecure Digital Services**

### Industry

Telecommunications, Cloud and Digital Services

### Employees

Approximately 9,000

### Annual Revenue

Approximately €2.8 billion

### Geographic Presence

* Spain
* France
* Portugal
* Germany
* Italy

### Critical Services

* Customer digital platforms
* Mobile services
* Cloud infrastructure
* Enterprise connectivity
* Billing systems
* Identity services

---

# 3. Current Risk Management Environment

EuroSecure maintains approximately:

* 85 cybersecurity risks;
* 420 cybersecurity controls;
* 65 critical applications;
* 130 major suppliers;
* 12 major business services.

The GRC team performs a formal risk review every quarter.

However, the CISO identifies a major problem.

The quarterly risk assessment is often based on information that is several weeks or months old.

---

# 4. The Risk Visibility Problem

The CISO asks:

> "How do we know whether our risk profile has changed since the last assessment?"

The GRC team discovers that significant changes can occur between formal assessments.

For example:

* critical vulnerabilities increase;
* ransomware activity increases;
* supplier security deteriorates;
* privileged accounts increase;
* cloud configurations change;
* major incidents occur.

Yet the risk register may still show the original risk rating.

---

# 5. From Periodic Assessment to Continuous Monitoring

EuroSecure establishes a continuous cybersecurity risk monitoring model.

```text id="c5n8q2"
Security Data
     |
     +---- Vulnerabilities
     +---- Incidents
     +---- Threat Intelligence
     +---- Identity
     +---- Cloud
     +---- Suppliers
     +---- Controls
     |
     v
Risk Indicators
     |
     v
Thresholds
     |
     v
Risk Analysis
     |
     v
Risk Register Update
     |
     v
Management Decision
```

---

# 6. Key Risk Indicators

The organization introduces **Key Risk Indicators (KRIs)**.

A KRI is an indicator that provides information about changing risk exposure.

Examples include:

* critical vulnerabilities beyond SLA;
* privileged accounts;
* phishing susceptibility;
* third-party high-risk findings;
* security incidents;
* systems without MFA;
* overdue remediation;
* risks above appetite.

---

# 7. KRI vs KPI

The organization distinguishes between KPIs and KRIs.

### KPI

Measures performance.

Example:

> 98% of employees completed security training.

### KRI

Measures potential risk exposure.

Example:

> 7% of employees failed simulated phishing tests.

A KPI can demonstrate that an activity is being performed.

A KRI provides insight into whether risk exposure may be increasing.

---

# 8. Example KRI Framework

| KRI                                 | Green | Amber | Red |
| ----------------------------------- | ----: | ----: | --: |
| Critical vulnerabilities beyond SLA |   0–2 |   3–5 |  >5 |
| Systems without MFA                 |   <1% |  1–3% | >3% |
| High-risk suppliers overdue         |   0–2 |   3–5 |  >5 |
| Risks above appetite                |   0–2 |   3–4 |  >4 |
| Critical exceptions expired         |     0 |     1 |  >1 |

The organization defines thresholds based on its own risk appetite and risk methodology.

---

# 9. Critical Vulnerability KRI

EuroSecure monitors:

**Number of critical vulnerabilities beyond remediation SLA**

Current result:

**8**

Threshold:

**Red >5**

The KRI therefore becomes **Red**.

This indicates increased exposure.

---

# 10. KRI Escalation

The red indicator triggers:

1. GRC review;
2. risk owner notification;
3. CISO escalation;
4. remediation review;
5. executive reporting.

The indicator itself does not automatically mean a major incident exists.

It means management should investigate the increased risk.

---

# 11. KRI Investigation

The GRC team determines that the eight vulnerabilities affect:

* two customer applications;
* one cloud environment;
* one internal administrative platform.

Two vulnerabilities affect critical business services.

The risk exposure is therefore greater than the raw number "8" suggests.

---

# 12. Risk Correlation

The GRC team correlates several indicators.

### KRI 1

Critical vulnerabilities beyond SLA: **8 – Red**

### KRI 2

Privileged accounts without phishing-resistant MFA: **4% – Red**

### KRI 3

High-risk supplier findings: **4 – Amber**

### KRI 4

Security incidents: **+20% – Amber**

Individually, these indicators are concerning.

Together, they indicate a potentially significant increase in cyber risk.

---

# 13. Risk Correlation Model

```text id="a6f2m9"
Vulnerabilities
      |
      +------+
             |
MFA Weakness +----> Increased Cyber Risk
             |
Supplier Risk+
             |
Incident Trend+
```

This demonstrates why risk monitoring should not rely on a single metric.

---

# 14. Risk Register Reassessment

The original risk register contains:

**Ransomware Risk**

Residual Risk:

**Medium**

After analyzing the new indicators, the GRC team determines that likelihood has increased.

The risk is reassessed as:

**High**

The risk register is therefore updated.

---

# 15. Risk Appetite Comparison

EuroSecure's risk appetite states:

> "High residual risk affecting critical customer-facing services requires executive treatment or formal acceptance."

The reassessed ransomware risk therefore requires executive attention.

---

# 16. Executive Risk Report

The CISO prepares a concise executive report.

```text id="n4v8x2"
CYBER RISK STATUS

Overall Cyber Risk:        HIGH

Risks Above Appetite:      4
Critical Vulnerabilities:  8
Expired Exceptions:        1
High-Risk Suppliers:       4

TREND:
Cyber risk exposure ↑

PRIMARY CONCERNS:
• Ransomware
• Identity security
• Critical vulnerabilities
• Supplier exposure

REQUIRED DECISIONS:
• Accelerate MFA program
• Approve vulnerability remediation funding
• Review supplier resilience
```

The report focuses on decisions rather than technical detail.

---

# 17. Risk Trend Reporting

EuroSecure tracks risk indicators over time.

For example:

| Month    | Critical Vulnerabilities | Risks Above Appetite |
| -------- | -----------------------: | -------------------: |
| January  |                        2 |                    1 |
| February |                        3 |                    1 |
| March    |                        4 |                    2 |
| April    |                        5 |                    2 |
| May      |                        7 |                    3 |
| June     |                        8 |                    4 |

The trend indicates increasing exposure.

This is more informative than reporting only the current value.

---

# 18. Risk Trend Interpretation

A single red indicator may represent a temporary anomaly.

A persistent upward trend suggests a structural problem.

For example:

```text id="t7c3k5"
Risk Exposure

High |                 *
     |             *
     |          *
     |       *
     |    *
Low  | *
     +--------------------
       Jan Feb Mar Apr May Jun
```

The GRC team investigates the underlying causes rather than simply reporting the trend.

---

# 19. Root Cause Analysis

The increase in vulnerabilities is traced to:

* delayed application modernization;
* shortage of security engineering resources;
* increased cloud deployments;
* inconsistent patching processes.

The issue is therefore not simply:

> "Too many vulnerabilities."

The underlying issue is a **capacity and governance problem**.

---

# 20. Management Decision

Management approves:

* additional security engineering resources;
* accelerated application modernization;
* vulnerability remediation funding;
* stronger SLA enforcement.

The GRC team records the decision and links it to the relevant risks.

---

# 21. Risk-to-Decision Model

```text id="y2m6q9"
Risk Indicator
      |
      v
Risk Analysis
      |
      v
Risk Assessment
      |
      v
Management Decision
      |
      v
Investment / Action
      |
      v
Risk Reduction
      |
      v
Measurement
      |
      +--------↺
```

This creates a closed-loop governance process.

---

# 22. Dashboard Architecture

EuroSecure establishes three dashboard levels.

### Operational Dashboard

Used by security teams.

Contains:

* vulnerabilities;
* incidents;
* alerts;
* control failures.

### Management Dashboard

Used by executives.

Contains:

* risk exposure;
* KRIs;
* treatment status;
* exceptions;
* major control weaknesses.

### Board Dashboard

Contains:

* top enterprise cyber risks;
* risk trends;
* risks above appetite;
* resilience;
* regulatory exposure;
* major incidents;
* strategic decisions.

---

# 23. Operational Dashboard

Example:

```text id="u8r4p3"
SECURITY OPERATIONS

Critical Vulnerabilities:  8
Open Critical Incidents:   0
MFA Coverage:              96%
Patch Compliance:          91%
High Severity Alerts:      27
```

This is useful for security teams.

It is not sufficient for the board.

---

# 24. Management Dashboard

The management dashboard translates operational data into risk.

```text id="k5n2v7"
CYBER RISK MANAGEMENT

Ransomware Risk:            HIGH
Identity Risk:              HIGH
Supplier Risk:              MEDIUM
Cloud Risk:                 MEDIUM

Risks Above Appetite:       4
Overdue Treatment:          7
Critical Exceptions:        1
```

This allows executives to prioritize action.

---

# 25. Board Dashboard

The board receives a much more concise view.

```text id="m3q8x1"
BOARD CYBER RISK SUMMARY

Overall Risk: HIGH

TOP RISKS
1. Ransomware
2. Identity compromise
3. Critical application exposure

TREND
Risk exposure increasing

ABOVE APPETITE
4 risks

DECISIONS REQUIRED
• Security modernization
• Identity investment
• Supplier resilience
```

The board does not need hundreds of technical metrics.

---

# 26. Risk Heat Map

The GRC team uses a risk heat map to communicate the portfolio.

```text id="r6k2m4"
                    LIKELIHOOD
                Low   Med   High

IMPACT  High     H     H      C
        Med      M     M      H
        Low      L     L      M
```

Individual risks are plotted according to their assessed likelihood and impact.

The heat map provides a visual summary but does not replace detailed risk analysis.

---

# 27. Risk Appetite Dashboard

Another dashboard focuses specifically on appetite.

```text id="f9v3k6"
RISKS ABOVE APPETITE

Ransomware              🔴
Identity                🔴
Supplier Security       🟠
Cloud Resilience        🟠

Within Appetite
Application Risk        🟢
Endpoint Risk           🟢
Physical Security       🟢
```

The most important information is which risks require management intervention.

---

# 28. Risk Indicator Thresholds

Thresholds should be carefully designed.

For example:

### Green

Risk exposure remains within tolerance.

### Amber

Risk is approaching tolerance limits.

### Red

Risk is outside defined tolerance and requires investigation or action.

Thresholds should not be arbitrary.

They should be linked to:

* risk appetite;
* historical performance;
* business criticality;
* regulatory obligations;
* threat conditions.

---

# 29. Leading and Lagging Indicators

EuroSecure uses both.

### Leading Indicators

Provide early warning.

Examples:

* increase in phishing attempts;
* increase in critical vulnerabilities;
* declining patch compliance;
* increasing privileged accounts.

### Lagging Indicators

Show events that have already occurred.

Examples:

* security incidents;
* confirmed breaches;
* financial losses;
* regulatory penalties.

A mature dashboard uses both.

---

# 30. Risk Prediction

The GRC team begins analyzing trends.

For example:

If:

* critical vulnerabilities increase;
* patch compliance decreases;
* threat activity increases;

then ransomware exposure may increase.

This does not prove that a ransomware incident will occur.

It provides an early-warning signal requiring management attention.

---

# 31. Continuous Control Monitoring

EuroSecure introduces automated monitoring for selected controls.

Examples:

* MFA enabled;
* privileged accounts;
* encryption;
* security configurations;
* endpoint protection;
* cloud configuration.

Control failures feed into the GRC risk monitoring process.

---

# 32. Control-to-Risk Relationship

```text id="w7c5m2"
Control Failure
      |
      v
Control Effectiveness ↓
      |
      v
Residual Risk ↑
      |
      v
KRI Threshold Breach
      |
      v
Management Escalation
```

This connects operational control information to enterprise risk.

---

# 33. Third-Party Risk Monitoring

EuroSecure continuously monitors critical suppliers.

Indicators include:

* overdue assessments;
* unresolved high-risk findings;
* security incidents;
* expired certifications;
* SLA failures;
* financial deterioration.

A supplier's risk rating can therefore change between formal annual assessments.

---

# 34. Regulatory Risk Monitoring

The GRC team also monitors regulatory developments.

For example:

A new regulatory requirement could affect:

* incident reporting;
* security controls;
* supplier management;
* resilience.

The regulatory change can trigger:

**Requirement Review → Gap Assessment → Risk Reassessment → Treatment**

---

# 35. Incident-Triggered Risk Reassessment

A significant security incident automatically triggers a risk review.

For example:

```text id="b4n8q2"
Major Incident
      |
      v
Root Cause Analysis
      |
      v
Affected Risk Identification
      |
      v
Risk Reassessment
      |
      v
Control Review
      |
      v
Treatment Update
```

This ensures the risk register reflects lessons learned from real events.

---

# 36. Risk Reporting Frequency

Different information requires different reporting frequencies.

| Information         | Frequency         |
| ------------------- | ----------------- |
| Security operations | Daily             |
| Critical KRIs       | Weekly            |
| Risk treatment      | Monthly           |
| Enterprise risk     | Monthly/Quarterly |
| Board cyber risk    | Quarterly         |
| Major incident      | Immediate         |

Not every metric needs to be reported at the same frequency.

---

# 37. Risk Reporting Challenges

EuroSecure identifies several common problems.

### Too Much Data

Executives receive hundreds of metrics.

### Poor Context

Numbers are reported without business implications.

### No Trend

Current status is shown without historical comparison.

### No Threshold

Management cannot tell whether a value is acceptable.

### No Decision

Reports identify problems but do not explain what management needs to decide.

---

# 38. Improved Reporting Model

The organization adopts five questions for executive reporting:

1. **What is the risk?**
2. **Is it increasing or decreasing?**
3. **Is it within appetite?**
4. **Why is it changing?**
5. **What decision is required?**

This creates decision-oriented reporting.

---

# 39. Example Executive Risk Statement

Instead of:

> "Patch compliance is 91%."

The report states:

> **"Patch compliance has declined from 97% to 91% over three months, increasing exposure to critical vulnerabilities on customer-facing systems. Management action is required to accelerate remediation capacity."**

The second statement is more useful because it connects the metric to risk and action.

---

# 40. Board-Level Risk Statement

A board-level statement might be:

> **"Cybersecurity risk exposure has increased over the last quarter, primarily due to vulnerability remediation delays and increased identity-related exposure. Four risks currently exceed appetite. Management has initiated remediation and requests approval for accelerated security modernization."**

This is the level of communication expected from a mature GRC function.

---

# 41. Risk Reporting Governance

The GRC function establishes standards for:

* metric definitions;
* data sources;
* calculation methods;
* thresholds;
* reporting frequency;
* ownership;
* escalation;
* dashboard approval.

This prevents different departments from reporting inconsistent values.

---

# 42. Data Quality

Risk reporting is only as good as the underlying data.

EuroSecure establishes data-quality checks for:

* completeness;
* accuracy;
* timeliness;
* consistency;
* ownership.

For example:

A dashboard should not report:

> "100% MFA coverage"

if 15% of systems are excluded from the measurement.

---

# 43. KRI Ownership

Every KRI has an owner.

Example:

| KRI                      | Owner                        |
| ------------------------ | ---------------------------- |
| Critical vulnerabilities | CISO / Vulnerability Manager |
| MFA coverage             | IAM Manager                  |
| Supplier risk            | Third-Party Risk Manager     |
| Risks above appetite     | GRC                          |
| Incident trend           | SOC                          |
| Cloud configuration      | Cloud Security               |

The owner is responsible for data quality and interpretation.

---

# 44. Risk Dashboard Governance

The GRC team reviews the dashboard periodically.

Questions include:

* Is the KRI still relevant?
* Are thresholds still appropriate?
* Is the data reliable?
* Does the indicator predict meaningful risk?
* Does management use it?
* Should it be replaced?

Indicators should evolve with the organization.

---

# 45. Case Study Outcome

After twelve months of continuous monitoring, EuroSecure achieves:

* faster identification of increasing risks;
* earlier executive escalation;
* improved vulnerability remediation;
* better visibility of risks above appetite;
* stronger supplier monitoring;
* improved board reporting;
* better alignment between cybersecurity investment and risk.

---

# 46. Before-and-After Comparison

### Before

```text
Annual / Quarterly Assessment
            |
            v
       Risk Register
            |
            v
      Periodic Reporting
```

Risk information may become outdated between reviews.

### After

```text
Continuous Data
      |
      v
KRIs / KPIs
      |
      v
Risk Monitoring
      |
      v
Dynamic Risk Register
      |
      v
Executive Decisions
      |
      v
Continuous Treatment
```

The second model provides much stronger situational awareness.

---

# 47. Lessons Learned

## Lesson 1 – Risk Registers Are Not Static

Cybersecurity risk changes continuously.

## Lesson 2 – KRIs Provide Early Warning

Good indicators can identify increasing exposure before an incident occurs.

## Lesson 3 – Context Matters

A number alone is rarely sufficient for executive decision-making.

## Lesson 4 – Trends Are More Valuable Than Snapshots

Management should understand whether risk is increasing, decreasing, or stable.

---

# 48. Additional Lessons

## Lesson 5 – Indicators Must Be Actionable

A KRI should trigger investigation, escalation, or decision when thresholds are breached.

## Lesson 6 – Board Reporting Should Be Strategic

Boards need information about material risk and decisions, not operational noise.

## Lesson 7 – Automation Improves Timeliness

Automated data collection reduces manual reporting delays.

## Lesson 8 – Risk Monitoring Must Connect to Treatment

Identifying an increasing risk is useful only if the organization can respond.

---

# 49. Practical Cybersecurity Risk Monitoring Checklist

### Risk Monitoring

* [ ] Risk indicators identified
* [ ] KRI definitions established
* [ ] Thresholds defined
* [ ] Owners assigned
* [ ] Data sources identified
* [ ] Reporting frequency established

### Risk Governance

* [ ] Risk appetite defined
* [ ] Escalation criteria established
* [ ] Risks above appetite monitored
* [ ] Risk reassessment triggered by significant changes

### Executive Reporting

* [ ] Risk trends reported
* [ ] Business impact explained
* [ ] Top risks identified
* [ ] Management decisions highlighted
* [ ] Board reporting separated from operational reporting

### Data Quality

* [ ] Data completeness validated
* [ ] Data accuracy validated
* [ ] Metric definitions standardized
* [ ] Dashboard calculations reviewed

### Continuous Improvement

* [ ] KRI effectiveness reviewed
* [ ] Thresholds periodically reassessed
* [ ] New threat indicators considered
* [ ] Lessons from incidents incorporated

---

# 50. Final Cybersecurity Risk Monitoring Model

```text id="e6r3k8"
                 SECURITY & BUSINESS DATA
                          |
          +---------------+---------------+
          |               |               |
     Vulnerabilities    Incidents       Suppliers
          |               |               |
          +---------------+---------------+
                          |
                          v
                    RISK INDICATORS
                          |
                          v
                  THRESHOLDS / TRENDS
                          |
                          v
                    RISK ANALYSIS
                          |
                          v
                   RISK REGISTER
                          |
                          v
                    RISK APPETITE
                          |
             +------------+------------+
             |                         |
       Within Appetite           Above Appetite
             |                         |
             v                         v
          Monitor              Escalate / Treat
             |                         |
             +------------+------------+
                          |
                          v
                  EXECUTIVE DECISION
                          |
                          v
                     ACTION
                          |
                          v
                 RISK REASSESSMENT
                          |
                          +----------↺
```

# 51. Case Study Conclusion

The EuroSecure case demonstrates how organizations can move from **periodic risk assessment to continuous cybersecurity risk management**.

A mature GRC function does not simply maintain a risk register. It continuously asks whether the organization's risk profile has changed.

The complete model is:

**Collect Data → Monitor Indicators → Identify Trends → Reassess Risk → Compare With Appetite → Escalate → Decide → Treat → Reassess**

The most important principle is:

> **A cybersecurity risk dashboard should not merely tell management what is happening; it should help management understand what it means and what decision is required.**

For a GRC professional, the ability to translate technical and operational data into **risk indicators, executive insights, and actionable decisions** is one of the most important capabilities in modern cybersecurity governance.

# 19.4 Cybersecurity Risk Management Case Studies

## Part 4 – Cybersecurity Risk Management Program Review & Lessons Learned

## 1. Case Study Overview

This case study examines how an organization performs a **comprehensive review of its cybersecurity risk management program** after implementing risk assessment, treatment, monitoring, and reporting processes.

The objective is to determine whether the organization's cybersecurity risk management program is:

* effective;
* consistently implemented;
* aligned with business objectives;
* aligned with risk appetite;
* producing reliable management information;
* capable of adapting to changing threats;
* supported by effective governance and assurance.

The case moves beyond individual risks and examines the **risk management program as a whole**.

The central model is:

**Assess → Treat → Monitor → Report → Assure → Improve → Reassess**

---

# 2. Organization Profile

### Company

**IberiaCore Digital Infrastructure**

### Industry

Telecommunications and Digital Infrastructure

### Employees

Approximately 8,500

### Annual Revenue

Approximately €2.6 billion

### Geographic Presence

* Spain
* Portugal
* France
* Italy
* Germany

### Critical Services

* Telecommunications infrastructure
* Cloud services
* Enterprise connectivity
* Customer platforms
* Identity services
* Data centers

---

# 3. Background

IberiaCore implemented a formal cybersecurity risk management program three years ago.

The program includes:

* enterprise cybersecurity risk assessments;
* risk registers;
* risk appetite;
* risk treatment plans;
* risk acceptance;
* KRIs;
* executive reporting;
* control monitoring;
* internal audit.

Management initially considered the program successful.

However, after three years, the CISO asks an important question:

> **"Is our cybersecurity risk management program actually reducing organizational risk?"**

This triggers a formal program review.

---

# 4. Program Review Objectives

The review evaluates whether:

1. cybersecurity risks are consistently identified;
2. risk assessments are reliable;
3. risk ownership is clear;
4. controls effectively reduce risk;
5. risk treatment is completed;
6. accepted risks remain within appetite;
7. KRIs provide useful early warning;
8. executives receive meaningful information;
9. assurance activities are effective;
10. the program continuously improves.

---

# 5. Program Review Scope

The review covers the complete risk management lifecycle.

```text id="c2m7q9"
Risk Identification
       |
       v
Risk Assessment
       |
       v
Risk Treatment
       |
       v
Risk Acceptance
       |
       v
Risk Monitoring
       |
       v
Risk Reporting
       |
       v
Risk Assurance
       |
       v
Continuous Improvement
```

---

# 6. Review Methodology

The GRC team uses five assessment methods:

### 1. Documentation Review

Review policies, procedures, risk registers, and treatment plans.

### 2. Interviews

Interview risk owners, executives, cybersecurity teams, and control owners.

### 3. Data Analysis

Analyze risk and control metrics.

### 4. Control Testing

Test whether key processes operate effectively.

### 5. Benchmarking

Compare the program against recognized frameworks and organizational expectations.

---

# 7. Program Maturity Assessment

IberiaCore uses a five-level maturity model.

| Level | Description |
| ----: | ----------- |
|     1 | Initial     |
|     2 | Developing  |
|     3 | Defined     |
|     4 | Managed     |
|     5 | Optimized   |

The organization initially estimates its cybersecurity risk management maturity at:

**Level 4 – Managed**

The review will determine whether this assessment is justified.

---

# 8. Governance Assessment

The review confirms that:

* a CISO exists;
* risk owners are assigned;
* an executive risk committee exists;
* cybersecurity policies are documented.

However, interviews reveal that some business leaders still believe:

> "Cybersecurity owns cybersecurity risk."

This indicates a governance problem.

The organization needs to reinforce the principle that **business owners own business risk**.

---

# 9. Risk Ownership Assessment

The review examines 120 cybersecurity risks.

Results:

* 108 have named owners;
* 7 have shared ownership;
* 5 have unclear ownership.

Therefore:

**4.2% of risks lack clear accountability.**

The organization classifies this as a governance weakness.

---

# 10. Risk Assessment Quality

The GRC team samples 30 risk assessments.

The review identifies:

* 24 with complete business context;
* 4 with incomplete impact analysis;
* 2 using outdated threat assumptions.

This means approximately:

**20% of sampled assessments require improvement.**

The organization therefore cannot assume that all risk ratings are equally reliable.

---

# 11. Inherent vs Residual Risk

The review discovers another issue.

Several business units calculate residual risk without clearly documenting:

* which controls were considered;
* control effectiveness;
* evidence supporting the assessment.

This makes some residual-risk ratings difficult to validate.

The GRC team therefore introduces a standardized assessment template.

---

# 12. Control Effectiveness Review

The organization examines whether controls actually reduce risk.

The review finds:

### Control Implemented

**92%**

### Control Evidence Available

**86%**

### Controls Tested

**78%**

### Controls Demonstrated Effective

**71%**

This reveals an important distinction:

> **Control implementation is significantly higher than demonstrated control effectiveness.**

---

# 13. Risk Treatment Performance

The organization has 96 active treatment actions.

Current status:

| Status      | Number |
| ----------- | -----: |
| Completed   |     58 |
| In Progress |     24 |
| Overdue     |     14 |

The overdue rate is:

**14.6%**

The review determines that treatment delays are concentrated in:

* legacy applications;
* cloud modernization;
* third-party remediation.

---

# 14. Treatment Root Causes

The GRC team investigates overdue actions.

The main causes are:

* insufficient resources;
* unclear ownership;
* dependency on other projects;
* business prioritization;
* underestimated effort.

The conclusion is important:

> **A high number of overdue actions may indicate a governance or resource problem rather than simply a security-team performance problem.**

---

# 15. Risk Acceptance Review

The organization has 22 formally accepted cybersecurity risks.

The review discovers:

* 17 have current approvals;
* 3 require renewal;
* 2 have expired acceptance periods.

The expired risks are escalated immediately.

This confirms the importance of monitoring risk acceptance expiration.

---

# 16. Risk Appetite Review

The organization defines its cybersecurity risk appetite.

However, several business units use different interpretations.

For example:

One business unit considers "High" risk acceptable temporarily.

Another treats the same rating as requiring immediate escalation.

This creates inconsistency.

---

# 17. Risk Appetite Improvement

The GRC team creates explicit decision criteria.

```text id="k3v8m1"
Residual Risk
      |
      v
Risk Appetite Comparison
      |
 +----+----+
 |         |
Within    Above
Appetite  Appetite
 |         |
 v         v
Monitor   Treat /
          Escalate
```

The criteria are incorporated into the enterprise risk methodology.

---

# 18. KRI Effectiveness Review

The organization uses 35 cybersecurity KRIs.

The GRC team evaluates whether they actually provide useful warning.

Results:

* 18 highly useful;
* 9 moderately useful;
* 8 provide limited value.

Several indicators are removed.

Examples of weak indicators include metrics that:

* do not change decisions;
* are difficult to interpret;
* duplicate other metrics;
* lack reliable data;
* have no defined escalation threshold.

---

# 19. KRI Improvement

The organization applies five criteria to each KRI:

1. Is it relevant?
2. Is the data reliable?
3. Does it indicate risk?
4. Does it have meaningful thresholds?
5. Does management act on it?

If the answer is consistently "no," the indicator is removed or redesigned.

---

# 20. Executive Reporting Assessment

The review examines quarterly board reports.

The reports contain approximately 45 cybersecurity metrics.

The board feedback is:

> "There is too much information but not enough explanation."

The GRC team redesigns the report.

---

# 21. New Executive Reporting Model

The revised report focuses on:

### Top Risks

What are the most significant risks?

### Risk Trend

Are they increasing or decreasing?

### Risk Appetite

Are any above appetite?

### Business Impact

What could happen?

### Management Action

What is being done?

### Decision Required

What does management need to approve?

---

# 22. Example Executive Report

```text id="p7n4x2"
CYBERSECURITY RISK SUMMARY

Overall Risk: MEDIUM-HIGH

Risk Trend: ↑ Increasing

Risks Above Appetite: 3

TOP RISK
Legacy customer platform

WHY IT MATTERS
Critical customer service dependency.

CURRENT EXPOSURE
Residual risk remains High.

ACTION
Modernization program underway.

DECISION REQUIRED
Approve accelerated funding.
```

This is more useful than a dashboard containing dozens of technical metrics.

---

# 23. Third-Party Risk Review

The program review also examines supplier risk.

IberiaCore has:

**210 active suppliers**

Of these:

* 38 are critical suppliers;
* 24 require enhanced security monitoring;
* 6 have overdue remediation;
* 2 have expired security assessments.

The organization decides that annual supplier assessments are insufficient for critical suppliers.

---

# 24. Continuous Third-Party Monitoring

Critical suppliers will now be monitored using:

* security incidents;
* assessment findings;
* certifications;
* vulnerability information;
* SLA performance;
* business continuity;
* financial indicators.

Supplier risk ratings may therefore change dynamically.

---

# 25. Regulatory Alignment

The review assesses alignment with relevant requirements and frameworks, including:

* ISO/IEC 27001;
* ISO/IEC 27005;
* NIST Cybersecurity Framework;
* NIST Risk Management Framework;
* applicable EU cybersecurity requirements;
* privacy and data protection obligations.

The purpose is not to create separate risk programs.

Instead, the organization seeks to establish an integrated risk model.

---

# 26. Framework Integration

The organization maps:

```text id="m6q8v3"
Regulatory Requirements
          |
          v
Risk Requirements
          |
          v
Cybersecurity Controls
          |
          v
Control Evidence
          |
          v
Risk Assessment
          |
          v
Management Reporting
```

This reduces duplication between compliance and cybersecurity risk activities.

---

# 27. Internal Audit Assessment

Internal Audit performs an independent review.

The audit examines:

* risk governance;
* risk assessment;
* risk treatment;
* risk acceptance;
* KRI monitoring;
* reporting.

The audit identifies three significant improvement areas:

1. risk ownership;
2. treatment monitoring;
3. risk acceptance expiration.

---

# 28. Three Lines Perspective

The review confirms responsibilities across the three lines.

### First Line

Business and technology teams:

* own risk;
* operate controls;
* perform treatment.

### Second Line

GRC and cybersecurity risk:

* establish methodology;
* monitor;
* challenge;
* report.

### Third Line

Internal Audit:

* independently evaluates effectiveness;
* provides assurance;
* reports to the audit committee.

---

# 29. Program Effectiveness Assessment

The review scores the major capabilities.

| Capability          | Score |
| ------------------- | ----: |
| Risk Identification |     4 |
| Risk Assessment     |     3 |
| Risk Treatment      |     3 |
| Risk Acceptance     |     3 |
| Risk Monitoring     |     4 |
| Executive Reporting |     3 |
| Third-Party Risk    |     3 |
| Assurance           |     4 |

Overall maturity:

**Level 3 – Defined to Level 4 – Managed**

The organization realizes its previous Level 4 assessment was optimistic.

---

# 30. Maturity Gap

The target state is:

**Level 4 – Managed**

Current effective capability:

**Level 3 – Defined**

The gap is therefore:

**One maturity level**

The organization develops a two-year improvement roadmap.

---

# 31. Improvement Roadmap

## Phase 1 – 0–3 Months

* clarify risk ownership;
* renew expired risk acceptances;
* standardize risk assessment;
* review KRIs;
* improve executive reporting.

## Phase 2 – 3–9 Months

* automate risk monitoring;
* strengthen treatment tracking;
* improve supplier monitoring;
* integrate GRC data sources.

## Phase 3 – 9–18 Months

* continuous control monitoring;
* advanced analytics;
* automated risk reassessment;
* stronger risk forecasting.

## Phase 4 – 18–24 Months

* optimize risk decision-making;
* predictive analytics;
* integrated enterprise GRC;
* continuous maturity measurement.

---

# 32. Corrective Action Program

Every improvement receives:

* action ID;
* finding;
* root cause;
* action;
* owner;
* priority;
* target date;
* success criteria;
* evidence requirement.

This ensures the review itself becomes part of the GRC improvement lifecycle.

---

# 33. Example Corrective Action

### Finding

Risk acceptance monitoring is inconsistent.

### Root Cause

No centralized expiration monitoring.

### Action

Implement automated risk acceptance expiration alerts.

### Owner

GRC Director

### Target

90 days

### Success Criterion

100% of risk acceptances have:

* owner;
* approval;
* expiration/review date;
* automated monitoring.

---

# 34. Program Metrics

The organization introduces program-level metrics.

### Risk Management

* percentage of risks with owners;
* percentage of risks reviewed on schedule;
* risks above appetite.

### Treatment

* overdue treatment actions;
* average remediation age;
* treatment effectiveness.

### Acceptance

* active accepted risks;
* expired acceptances;
* acceptance renewal rate.

### Controls

* control effectiveness;
* failed controls;
* overdue control remediation.

---

# 35. Program-Level KRIs

Examples include:

### KRI 1

Percentage of cybersecurity risks without valid owners.

### KRI 2

Percentage of high-risk treatment actions overdue.

### KRI 3

Percentage of accepted risks beyond review date.

### KRI 4

Percentage of critical controls failing effectiveness tests.

These measure the health of the **risk management program itself**.

---

# 36. Continuous Improvement Cycle

The organization establishes:

```text id="w3p7m2"
Assess
  |
  v
Measure
  |
  v
Identify Gaps
  |
  v
Improve
  |
  v
Validate
  |
  v
Report
  |
  v
Reassess
  |
  +--------↺
```

This prevents the risk program from becoming static.

---

# 37. Lessons Learned

## Lesson 1 – A Risk Program Must Be Tested

Having policies and processes does not prove effectiveness.

## Lesson 2 – Maturity Should Be Evidence-Based

Organizations should not rate themselves highly without evidence.

## Lesson 3 – Risk Ownership Is Fundamental

Unclear ownership weakens the entire risk lifecycle.

## Lesson 4 – Treatment Must Be Measured

Completion percentages alone do not demonstrate risk reduction.

---

# 38. Additional Lessons

## Lesson 5 – Risk Acceptance Requires Governance

Expired or undocumented acceptance creates uncontrolled exposure.

## Lesson 6 – KRIs Must Drive Decisions

An indicator that never changes a decision may not be useful.

## Lesson 7 – Executive Reporting Should Be Decision-Oriented

Management needs risk context, trends, impact, and required actions.

## Lesson 8 – Assurance Completes the Lifecycle

Independent assurance provides confidence that the program actually operates as intended.

---

# 39. Common Program Review Findings

A cybersecurity risk management program may appear mature while suffering from:

* stale risk registers;
* inaccurate risk ratings;
* unclear ownership;
* overdue treatment;
* expired risk acceptance;
* ineffective controls;
* excessive metrics;
* poor executive reporting;
* weak third-party monitoring;
* insufficient assurance.

These are common indicators of a **process-oriented rather than risk-oriented GRC program**.

---

# 40. Practical Cybersecurity Risk Program Review Checklist

### Governance

* [ ] Risk ownership defined
* [ ] Risk appetite approved
* [ ] Escalation criteria established
* [ ] Governance committees operating

### Risk Assessment

* [ ] Risk methodology documented
* [ ] Business context included
* [ ] Inherent risk assessed
* [ ] Residual risk assessed
* [ ] Control effectiveness considered

### Risk Treatment

* [ ] Treatment plans documented
* [ ] Owners assigned
* [ ] Deadlines established
* [ ] Overdue actions escalated
* [ ] Treatment effectiveness validated

### Risk Acceptance

* [ ] Acceptance formally approved
* [ ] Authority defined
* [ ] Review dates established
* [ ] Expiration monitored

### Risk Monitoring

* [ ] KRIs established
* [ ] Thresholds defined
* [ ] Trends monitored
* [ ] Significant changes trigger reassessment

### Reporting

* [ ] Executive dashboard established
* [ ] Board reporting established
* [ ] Risks above appetite highlighted
* [ ] Decisions clearly identified

### Assurance

* [ ] Internal audit performed
* [ ] Control effectiveness tested
* [ ] Findings tracked
* [ ] Corrective actions validated

---

# 41. Final Cybersecurity Risk Management Program Model

```text
                    BUSINESS OBJECTIVES
                           |
                           v
                    RISK GOVERNANCE
                           |
                           v
                  RISK IDENTIFICATION
                           |
                           v
                    RISK ASSESSMENT
                           |
                           v
                    RISK TREATMENT
                           |
                           v
                    RISK ACCEPTANCE
                           |
                           v
                  CONTINUOUS MONITORING
                           |
                           v
                  EXECUTIVE REPORTING
                           |
                           v
                    INDEPENDENT ASSURANCE
                           |
                           v
                  PROGRAM EFFECTIVENESS
                           |
                           v
                  CONTINUOUS IMPROVEMENT
                           |
                           +-----------↺
```

# 42. Case Study Conclusion

The IberiaCore case demonstrates that implementing a cybersecurity risk management framework is only the beginning.

A mature organization must periodically ask:

> **Are our risk processes actually identifying the right risks, driving the right decisions, reducing exposure, and providing management with reliable assurance?**

The review demonstrates the difference between **having a risk management program** and **having an effective risk management program**.

The complete lifecycle is:

**Identify → Assess → Treat → Accept → Monitor → Report → Assure → Improve**

For a GRC professional, this case demonstrates an important career-level capability: the ability to evaluate not only individual cybersecurity risks, but also the **effectiveness, maturity, governance, and continuous improvement of the entire cybersecurity risk management program**.

The ultimate objective is not to achieve a perfect risk score.

It is to ensure that:

> **The organization understands its cybersecurity exposure, makes informed risk decisions, maintains accountability, and continuously improves its ability to manage cyber risk.**


