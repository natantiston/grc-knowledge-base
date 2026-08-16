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


