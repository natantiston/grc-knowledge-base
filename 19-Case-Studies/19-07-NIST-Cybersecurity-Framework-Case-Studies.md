# 19.7 NIST Cybersecurity Framework Case Studies

## Part 1 – Implementing the NIST CSF in an Enterprise

## 1. Case Study Overview

**IberiaCloud Digital Services** is a large cloud and telecommunications services organization operating across Europe.

Although the organization already has:

* ISO 27001 certification;
* an established GRC function;
* security policies;
* risk management;
* security operations;
* internal audit;

management believes that cybersecurity activities are fragmented across business units.

The CISO therefore decides to implement the **NIST Cybersecurity Framework (CSF)** as an enterprise cybersecurity risk-management framework.

The objective is not to replace ISO 27001.

Instead, NIST CSF will provide a practical structure for communicating cybersecurity risk, current capabilities and target improvements across the organization.

---

# 2. Organization Profile

### Organization

**IberiaCloud Digital Services**

### Industry

Cloud, telecommunications and digital services

### Employees

Approximately 1,800

### Technology Environment

* Azure cloud;
* on-premises infrastructure;
* SaaS applications;
* customer-facing applications;
* mobile platforms;
* corporate endpoints;
* third-party services.

### Existing Frameworks

The organization already uses:

* ISO 27001;
* ISO 27005;
* COBIT;
* internal cybersecurity policies;
* enterprise risk management.

The new initiative introduces NIST CSF as an additional cybersecurity framework.

---

# 3. Business Problem

The CISO identifies several issues.

Different departments use different terminology.

For example:

### IT

> "We have 95% patch compliance."

### SOC

> "We reduced mean time to detect."

### GRC

> "There are 42 open cybersecurity risks."

### Executive Management

> "What does this mean for the business?"

The organization needs a common cybersecurity-risk language.

---

# 4. Why NIST CSF?

The organization selects NIST CSF because it provides a structured way to organize cybersecurity activities around:

* **Identify**
* **Protect**
* **Detect**
* **Respond**
* **Recover**

The framework helps management understand cybersecurity capabilities without requiring executives to understand every technical control.

---

# 5. Implementation Objective

The CISO defines five objectives:

1. establish an enterprise cybersecurity baseline;
2. identify cybersecurity gaps;
3. establish a target cybersecurity profile;
4. prioritize improvements based on risk;
5. communicate cybersecurity posture to executives.

The implementation is therefore focused on **risk and outcomes**, rather than framework adoption for its own sake.

---

# 6. NIST CSF Implementation Model

```text id="ncs6p2"
             BUSINESS CONTEXT
                    |
                    v
              CURRENT STATE
                    |
                    v
              RISK ASSESSMENT
                    |
                    v
          CURRENT CSF PROFILE
                    |
                    v
           GAP IDENTIFICATION
                    |
                    v
           TARGET CSF PROFILE
                    |
                    v
             PRIORITIZATION
                    |
                    v
           IMPLEMENTATION PLAN
                    |
                    v
               MONITORING
                    |
                    v
             PROFILE UPDATE
```

This becomes the enterprise implementation lifecycle.

---

# 7. Step 1 – Establish Executive Sponsorship

The CISO presents the initiative to the executive committee.

The presentation focuses on business outcomes:

* customer trust;
* service availability;
* regulatory compliance;
* financial exposure;
* operational resilience;
* cyber-risk reduction.

The CISO avoids presenting NIST CSF as simply another technical framework.

---

# 8. Executive Question

The CFO asks:

> "How will this help the business?"

The CISO responds:

> "It will give us a consistent way to identify where our cybersecurity capabilities are weak, prioritize investments based on risk, and demonstrate whether those investments reduce our exposure."

This secures executive sponsorship.

---

# 9. Step 2 – Define Organizational Scope

The organization decides that the first implementation will cover:

* corporate IT;
* cloud infrastructure;
* customer-facing platforms;
* SOC;
* identity services;
* critical third parties.

It excludes several low-risk legacy systems from the first phase.

The scope is documented.

---

# 10. Step 3 – Establish Governance

A cybersecurity transformation committee is established.

| Role                   | Responsibility           |
| ---------------------- | ------------------------ |
| CISO                   | Executive sponsor        |
| GRC Manager            | Framework implementation |
| CIO                    | Technology alignment     |
| SOC Manager            | Detection and response   |
| Infrastructure Manager | Infrastructure controls  |
| Cloud Security Manager | Cloud controls           |
| Risk Manager           | Risk integration         |
| Internal Audit         | Independent assurance    |

This ensures that NIST CSF implementation becomes an enterprise initiative.

---

# 11. Step 4 – Understand the Current Environment

The GRC team performs an inventory.

It identifies:

* systems;
* applications;
* data;
* business processes;
* cloud services;
* users;
* suppliers;
* security technologies;
* existing controls.

The team discovers that asset inventories differ between IT, security and procurement.

This becomes one of the first improvement opportunities.

---

# 12. Step 5 – Establish the Current Profile

The organization maps existing cybersecurity practices to the NIST CSF.

Example:

### Identify

Asset management is partially implemented.

### Protect

Access control is relatively mature.

### Detect

SOC monitoring is strong for critical systems but limited for some cloud services.

### Respond

Incident response is documented but exercises are inconsistent.

### Recover

Disaster recovery exists, but cyber-recovery capabilities require improvement.

---

# 13. Current Profile Example

| CSF Function | Current Maturity |
| ------------ | ---------------- |
| Identify     | Moderate         |
| Protect      | Strong           |
| Detect       | Strong           |
| Respond      | Moderate         |
| Recover      | Weak–Moderate    |

The profile immediately highlights areas requiring attention.

---

# 14. Step 6 – Avoid Treating NIST CSF as a Checklist

The GRC Manager makes an important decision:

> **The CSF will be used to understand cybersecurity outcomes, not simply to mark controls as "yes" or "no."**

For example:

Instead of asking:

> "Do we have vulnerability scanning?"

the organization asks:

> "Can we reliably identify vulnerabilities across our critical environment and reduce them within an acceptable risk timeframe?"

This produces a more meaningful assessment.

---

# 15. Step 7 – Identify Critical Business Services

The organization identifies its most important services.

Examples:

* customer billing;
* mobile services;
* cloud hosting;
* authentication;
* customer portal;
* network operations.

Each service is linked to:

* systems;
* data;
* dependencies;
* suppliers;
* cybersecurity risks.

---

# 16. Business-Service-to-Cybersecurity Model

```text id="bsc4m8"
Critical Business Service
          |
          v
Business Process
          |
          v
Applications + Systems
          |
          v
Data + Identity
          |
          v
Dependencies
          |
          v
Cybersecurity Risks
          |
          v
NIST CSF Outcomes
```

This ensures cybersecurity remains connected to business priorities.

---

# 17. Step 8 – Conduct Cybersecurity Risk Assessment

The GRC team evaluates risks affecting critical services.

Example:

### Risk

Compromise of privileged cloud credentials.

### Impact

High.

### Likelihood

Medium.

### Risk Rating

High.

### Existing Controls

* MFA;
* PAM;
* logging;
* monitoring;
* privileged-access reviews.

### Residual Risk

Medium.

The risk is mapped to relevant cybersecurity outcomes.

---

# 18. Step 9 – Map Existing Frameworks

The organization already has ISO 27001 controls.

Rather than creating a second independent control framework, the GRC team establishes relationships between:

**NIST CSF**

and

**ISO 27001**

For example:

```text id="xwalk7m2"
NIST CSF Outcome
       |
       v
ISO 27001 Control
       |
       v
Organizational Control
       |
       v
Evidence
       |
       v
Effectiveness
```

This reduces duplication.

---

# 19. Step 10 – Build the Framework Crosswalk

The GRC team maps:

* NIST CSF outcomes;
* ISO 27001 controls;
* internal policies;
* technical controls;
* risks;
* evidence.

Example:

| Cybersecurity Area | NIST CSF | ISO 27001              | Internal Control |
| ------------------ | -------- | ---------------------- | ---------------- |
| Asset Management   | Identify | Asset-related controls | CM-01            |
| Access Control     | Protect  | Access controls        | IAM-01           |
| Monitoring         | Detect   | Logging/monitoring     | SOC-02           |
| Incident Response  | Respond  | Incident controls      | IR-01            |
| Recovery           | Recover  | Continuity controls    | BC-03            |

The crosswalk creates a unified GRC structure.

---

# 20. Step 11 – Conduct Gap Assessment

The organization compares:

**Current Profile**

against

**Desired Profile**.

Major gaps include:

* incomplete cloud asset visibility;
* inconsistent vulnerability remediation;
* limited third-party monitoring;
* weak cyber-recovery testing;
* inconsistent incident exercises.

Each gap is assigned a risk rating.

---

# 21. Gap Assessment Example

| Gap                    | Risk   | Priority |
| ---------------------- | ------ | -------- |
| Cloud asset visibility | High   | Critical |
| Cyber-recovery testing | High   | Critical |
| Supplier monitoring    | High   | High     |
| Incident exercises     | Medium | Medium   |
| Awareness metrics      | Medium | Medium   |

This prevents the organization from trying to fix everything simultaneously.

---

# 22. Step 12 – Establish the Target Profile

The organization defines its desired future state.

Example:

### Identify

100% visibility of critical assets.

### Protect

Critical vulnerabilities remediated within defined risk-based SLAs.

### Detect

Continuous monitoring of critical systems.

### Respond

Annual enterprise cyber exercises.

### Recover

Cyber-recovery testing for all critical services.

The target profile becomes the destination for the transformation roadmap.

---

# 23. Step 13 – Prioritize Gaps

The organization evaluates each gap using:

* risk;
* business impact;
* regulatory importance;
* threat exposure;
* implementation effort;
* cost;
* dependencies.

A high-risk cyber-recovery weakness receives priority over a low-risk reporting enhancement.

---

# 24. Step 14 – Develop the Implementation Roadmap

The GRC team creates a two-year roadmap.

### Phase 1

Asset visibility and identity.

### Phase 2

Vulnerability and security monitoring.

### Phase 3

Incident response maturity.

### Phase 4

Cyber-recovery capabilities.

### Phase 5

Continuous optimization.

This creates a structured transformation program.

---

# 25. Step 15 – Implement Identify Improvements

The organization consolidates asset inventories.

The new architecture integrates:

* CMDB;
* cloud asset inventory;
* vulnerability platform;
* endpoint management;
* GRC platform.

The objective is to establish a reliable view of the organization's technology environment.

---

# 26. Step 16 – Implement Protect Improvements

The organization strengthens:

* identity governance;
* MFA;
* privileged access;
* vulnerability management;
* security awareness;
* data protection.

Controls are prioritized based on business risk.

---

# 27. Step 17 – Implement Detect Improvements

The SOC expands monitoring coverage.

Previously:

**78% of critical assets monitored**

Target:

**100%**

The organization also improves:

* SIEM coverage;
* cloud monitoring;
* alert correlation;
* threat detection;
* incident metrics.

---

# 28. Step 18 – Implement Respond Improvements

The organization updates incident-response procedures.

It introduces:

* escalation criteria;
* crisis-management roles;
* communication procedures;
* regulatory notification workflows;
* tabletop exercises.

A major cyber incident is simulated.

The exercise identifies several communication weaknesses.

These become new improvement actions.

---

# 29. Step 19 – Implement Recover Improvements

The organization reviews cyber-recovery capabilities.

Traditional disaster recovery is not considered sufficient.

The organization adds:

* immutable backups;
* privileged recovery accounts;
* recovery isolation;
* clean-room recovery procedures;
* cyber-recovery testing.

This improves resilience against destructive attacks.

---

# 30. Step 20 – Measure Results

After one year:

| Metric                                  | Baseline | Current |
| --------------------------------------- | -------: | ------: |
| Critical assets identified              |      78% |     99% |
| Critical assets monitored               |      78% |    100% |
| Critical vulnerability SLA              |      72% |     94% |
| Privileged accounts reviewed            |      95% |   99.5% |
| Cyber exercises                         |   1/year |  3/year |
| Critical services cyber-recovery tested |      40% |     90% |

These results demonstrate measurable improvement.

---

# 31. Step 21 – Report to Executives

The CISO translates the results into business language.

Instead of:

> "NIST CSF Protect improved from 3.1 to 3.7."

The CISO reports:

> "Critical-asset monitoring increased from 78% to 100%, reducing blind spots across the organization's most important services."

This makes cybersecurity relevant to executives.

---

# 32. Step 22 – Integrate With Enterprise Risk

The NIST CSF assessment is connected to the enterprise risk register.

Example:

### Cyber Risk

Loss of availability of customer authentication.

### Business Impact

High.

### Existing Controls

* redundant authentication infrastructure;
* monitoring;
* backup;
* incident response.

### CSF Gap

Cyber-recovery testing insufficient.

### Improvement

Expand recovery testing.

This integrates cybersecurity into enterprise risk management.

---

# 33. Step 23 – Integrate With Board Reporting

The Board receives a simplified cybersecurity view.

Example:

### Cybersecurity Posture

**Overall:** Improving

### Critical Exposure

2 high risks

### Major Improvement

100% critical asset monitoring

### Major Weakness

Cyber-recovery coverage at 90%

### Investment Required

Additional recovery infrastructure

This is much more useful than presenting a long technical control list.

---

# 34. Step 24 – Monitor the Profile

The organization reviews the current profile quarterly.

Changes may occur because of:

* new technology;
* new threats;
* incidents;
* acquisitions;
* regulatory changes;
* business expansion.

The current profile therefore remains dynamic.

---

# 35. Step 25 – Update the Target Profile

The target profile is also reviewed.

For example, AI becomes strategically important.

Management adds new cybersecurity objectives around:

* AI infrastructure;
* model security;
* AI supply chain;
* data protection;
* AI-related monitoring.

The target profile evolves with the business.

---

# 36. Step 26 – Governance and Accountability

The organization establishes ownership.

### CISO

Accountable for cybersecurity strategy.

### GRC

Owns framework governance and reporting.

### IT

Implements technology controls.

### SOC

Owns detection and response.

### Risk Management

Integrates cyber risk with enterprise risk.

### Internal Audit

Provides independent assurance.

This prevents NIST CSF implementation from becoming solely a GRC project.

---

# 37. Step 27 – Avoid Framework Duplication

A major risk is creating:

* ISO 27001 controls;
* NIST CSF controls;
* COBIT controls;
* internal controls;

as separate structures.

This creates:

* duplicate assessments;
* duplicate evidence;
* excessive workload;
* inconsistent reporting.

The organization instead uses one common control environment with multiple framework mappings.

---

# 38. Integrated Framework Model

```text id="ifm4x8"
                BUSINESS RISKS
                     |
                     v
             COMMON CONTROL SET
                     |
        +------------+------------+
        |            |            |
        v            v            v
    ISO 27001     NIST CSF      COBIT
        |            |            |
        +------------+------------+
                     |
                     v
                  EVIDENCE
                     |
                     v
               ASSURANCE
```

This is a mature GRC approach.

---

# 39. Step 28 – Internal Audit Assurance

Internal Audit evaluates whether the NIST CSF implementation is operating effectively.

It tests:

* current profile accuracy;
* risk mappings;
* control implementation;
* evidence;
* target-profile progress;
* management reporting.

Audit findings become improvement inputs.

---

# 40. Step 29 – Continual Improvement

The organization establishes an annual NIST CSF improvement cycle.

```text id="ncf7m3"
Current Profile
      |
      v
Risk Assessment
      |
      v
Gap Analysis
      |
      v
Target Profile
      |
      v
Prioritization
      |
      v
Implementation
      |
      v
Measurement
      |
      v
Management Review
      |
      v
Updated Profile
      |
      +------> Next Cycle
```

The framework becomes part of normal cybersecurity governance.

---

# 41. Common Implementation Mistakes

## Mistake 1 – Treating NIST CSF as a Checklist

The framework should support cybersecurity outcomes, not merely compliance scoring.

## Mistake 2 – Creating a Separate Control Universe

This creates unnecessary duplication.

## Mistake 3 – Ignoring Business Context

Cybersecurity priorities should reflect business-critical services.

## Mistake 4 – Focusing Only on Technology

Cybersecurity also involves:

* people;
* processes;
* governance;
* suppliers;
* risk;
* resilience.

---

# 42. Additional Mistakes

## Mistake 5 – Building a Target Profile Without Risk Analysis

The target state should reflect actual business and threat priorities.

## Mistake 6 – Measuring Activities Instead of Outcomes

"Number of training sessions" is less meaningful than whether security behavior improved.

## Mistake 7 – Failing to Update Profiles

The cybersecurity environment changes continuously.

## Mistake 8 – Not Connecting NIST CSF to Enterprise Risk

Cybersecurity risk should influence business decisions.

---

# 43. Practical NIST CSF Implementation Checklist

### Governance

* [ ] Executive sponsor established
* [ ] Scope defined
* [ ] Roles assigned
* [ ] Governance committee established

### Current State

* [ ] Assets identified
* [ ] Critical services identified
* [ ] Cybersecurity controls identified
* [ ] Current Profile established

### Risk

* [ ] Cybersecurity risks assessed
* [ ] Critical risks identified
* [ ] Business impact assessed
* [ ] Risk owners assigned

### Gap Analysis

* [ ] Current Profile assessed
* [ ] Target Profile defined
* [ ] Gaps documented
* [ ] Gaps prioritized

### Implementation

* [ ] Roadmap established
* [ ] Owners assigned
* [ ] Resources allocated
* [ ] Controls improved
* [ ] Technology implemented

### Measurement

* [ ] KPIs established
* [ ] KRIs established
* [ ] Profile reviewed
* [ ] Risk reduction measured
* [ ] Executive reporting established

### Continual Improvement

* [ ] Audit performed
* [ ] Lessons learned captured
* [ ] Profiles updated
* [ ] Improvement roadmap refreshed

---

# 44. Executive NIST CSF Dashboard

The CISO ultimately develops a simplified executive dashboard.

### Identify

**99% critical asset visibility**

### Protect

**94% critical vulnerability SLA compliance**

### Detect

**100% critical asset monitoring**

### Respond

**3 enterprise exercises completed**

### Recover

**90% critical services recovery-tested**

The dashboard provides a clear view of cybersecurity capability.

---

# 45. Case Study Results

After two years, IberiaCloud achieves:

* 99% critical-asset visibility;
* 100% monitoring coverage for critical assets;
* improved vulnerability remediation;
* stronger privileged-access governance;
* improved incident-response readiness;
* expanded cyber-recovery testing;
* integrated NIST CSF and ISO 27001 mappings;
* improved executive cybersecurity reporting.

More importantly, cybersecurity investment is now increasingly connected to **business risk and measurable outcomes**.

---

# 46. Final Case Study Model

```text id="ncf9p2"
              BUSINESS OBJECTIVES
                     |
                     v
              BUSINESS SERVICES
                     |
                     v
             CYBERSECURITY RISKS
                     |
                     v
              CURRENT PROFILE
                     |
                     v
                GAP ANALYSIS
                     |
                     v
              TARGET PROFILE
                     |
                     v
              RISK PRIORITIZATION
                     |
                     v
            IMPLEMENTATION ROADMAP
                     |
                     v
         +-----------+-----------+
         |           |           |
         v           v           v
      IDENTIFY    PROTECT      DETECT
         |           |           |
         +-----------+-----------+
                     |
             +-------+-------+
             |               |
             v               v
          RESPOND         RECOVER
             |               |
             +-------+-------+
                     |
                     v
               MEASUREMENT
                     |
                     v
             EXECUTIVE REVIEW
                     |
                     v
          CONTINUAL IMPROVEMENT
                     |
                     +------> CURRENT PROFILE
```

---

# 47. Lessons Learned

## Lesson 1 – Start With Business Risk

NIST CSF implementation should begin with business context rather than framework terminology.

## Lesson 2 – Establish a Current Profile

The organization must understand where it is before deciding where it wants to go.

## Lesson 3 – Build a Target Profile

The target state provides direction for cybersecurity investment.

## Lesson 4 – Prioritize the Gaps

Not every gap deserves immediate remediation.

---

# 48. Additional Lessons

## Lesson 5 – Integrate Frameworks

NIST CSF can complement ISO 27001, COBIT and other frameworks rather than replacing them.

## Lesson 6 – Measure Outcomes

The value of implementation should be demonstrated through measurable cybersecurity improvements.

## Lesson 7 – Communicate in Business Language

Executives need to understand risk exposure and business impact, not only technical maturity scores.

## Lesson 8 – Keep the Profile Current

A cybersecurity profile is not a one-time assessment.

It must evolve with:

* technology;
* threats;
* regulations;
* business strategy;
* organizational change.

---

# 49. Final Case Study Conclusion

The IberiaCloud case demonstrates how an enterprise can implement NIST CSF as a **cybersecurity governance and risk-management mechanism** rather than simply another compliance framework.

The mature implementation sequence is:

**Business Context → Cybersecurity Risk → Current Profile → Gap Analysis → Target Profile → Prioritization → Implementation → Measurement → Executive Review → Continual Improvement**

The most important GRC lesson is that NIST CSF becomes valuable when it connects technical cybersecurity capabilities to **business risk, investment decisions and measurable outcomes**.

The organization should ultimately be able to answer three executive questions:

> **Where are we today?**

> **Where do we need to be?**

> **What cybersecurity investments will close the most important gaps?**

That is the practical value of implementing NIST CSF at enterprise scale.

# 19.7 NIST Cybersecurity Framework Case Studies

## Part 2 – Building a Current and Target Organizational Profile

## 1. Case Study Overview

Following the initial NIST CSF implementation, **IberiaCloud Digital Services** needs to move from general framework adoption to a more structured assessment of its cybersecurity posture.

Management wants clear answers to two questions:

> **Where are we today?**

and

> **Where do we need to be?**

The GRC team therefore develops two organizational profiles:

* **Current Organizational Profile** — describes the organization's present cybersecurity outcomes and capabilities.
* **Target Organizational Profile** — describes the cybersecurity outcomes the organization wants to achieve.

The difference between the two becomes the foundation for the cybersecurity improvement roadmap.

---

# 2. Organization Profile

### Organization

**IberiaCloud Digital Services**

### Industry

Cloud and telecommunications services

### Employees

Approximately 1,800

### Environment

* Azure cloud;
* on-premises infrastructure;
* SaaS platforms;
* customer-facing applications;
* corporate endpoints;
* telecommunications infrastructure;
* critical third-party providers.

### Existing Frameworks

* ISO 27001;
* ISO 27005;
* NIST CSF;
* COBIT;
* enterprise risk management.

---

# 3. Business Situation

The organization has previously mapped its cybersecurity controls to NIST CSF.

However, management discovers that the organization has a large amount of security information but no consolidated view of its cybersecurity posture.

For example:

* IT has asset information;
* SOC has detection metrics;
* GRC has risk information;
* Internal Audit has control findings;
* Procurement has supplier information.

The information is fragmented.

The organization therefore establishes a formal **Current-to-Target Profile Program**.

---

# 4. What Is an Organizational Profile?

An organizational profile describes the cybersecurity outcomes that are relevant to an organization.

It provides a structured representation of:

* business priorities;
* cybersecurity requirements;
* current practices;
* desired outcomes;
* risk priorities.

The profile allows different stakeholders to discuss cybersecurity using a common framework.

---

# 5. Current vs Target Profile

```text id="ctp7m3"
          CURRENT PROFILE
                |
                | Gap
                v
        +----------------+
        | Cybersecurity  |
        | Improvement    |
        | Program        |
        +----------------+
                |
                v
          TARGET PROFILE
```

The **gap** between the profiles drives prioritization.

---

# 6. Step 1 – Define Business Context

Before creating either profile, the GRC team reviews the organization's business context.

It identifies:

* strategic objectives;
* critical services;
* regulatory obligations;
* customer expectations;
* threat environment;
* technology strategy;
* risk appetite.

The profile should reflect the organization's actual business environment.

---

# 7. Step 2 – Identify Critical Business Services

The organization identifies five critical services:

1. customer authentication;
2. cloud hosting;
3. customer billing;
4. network operations;
5. customer digital services.

Each service is mapped to its supporting:

* applications;
* infrastructure;
* data;
* identities;
* suppliers.

---

# 8. Step 3 – Identify Cybersecurity Priorities

Management identifies five major priorities.

### Priority 1

Protect customer information.

### Priority 2

Maintain service availability.

### Priority 3

Prevent unauthorized access.

### Priority 4

Detect cyber threats rapidly.

### Priority 5

Recover critical services after major cyber incidents.

These priorities influence the target profile.

---

# 9. Step 4 – Establish Risk Context

The GRC team reviews the enterprise risk register.

Major cybersecurity risks include:

| Risk                         | Rating      |
| ---------------------------- | ----------- |
| Cloud credential compromise  | High        |
| Ransomware                   | High        |
| Customer-data exposure       | High        |
| Critical supplier compromise | High        |
| Service disruption           | High        |
| Insider misuse               | Medium      |
| Phishing                     | Medium–High |

The profile must reflect these risks.

---

# 10. Step 5 – Build the Current Profile

The GRC team evaluates the organization's current cybersecurity outcomes.

The assessment covers the major NIST CSF areas.

### Identify

Current asset visibility is strong but cloud inventory has some gaps.

### Protect

Identity and access controls are mature.

### Detect

SOC monitoring is mature for core infrastructure.

### Respond

Incident-response processes exist but exercises are inconsistent.

### Recover

Traditional disaster recovery is mature, but cyber-recovery capabilities require improvement.

---

# 11. Current Profile Example

| CSF Function | Current State   |
| ------------ | --------------- |
| Identify     | Moderate–Strong |
| Protect      | Strong          |
| Detect       | Strong          |
| Respond      | Moderate        |
| Recover      | Moderate        |

The GRC team avoids presenting these ratings as the entire profile.

Each rating is supported by evidence and underlying outcomes.

---

# 12. Step 6 – Define Profile Assessment Criteria

The organization establishes assessment criteria.

For each cybersecurity outcome, it evaluates:

### 1. Implementation

Is the practice implemented?

### 2. Coverage

Does it cover critical systems?

### 3. Consistency

Is it implemented consistently?

### 4. Effectiveness

Does it actually reduce risk?

### 5. Assurance

Can the organization demonstrate effectiveness through evidence?

This produces a more meaningful profile.

---

# 13. Example: Vulnerability Management

The organization determines:

### Implementation

Yes.

### Coverage

94% of critical assets.

### Consistency

Mostly consistent.

### Effectiveness

Critical vulnerabilities are generally remediated within the defined SLA.

### Assurance

Strong reporting and evidence.

The current profile therefore indicates a relatively mature capability.

---

# 14. Step 7 – Identify Current-State Evidence

The GRC team collects evidence from:

* risk assessments;
* policies;
* procedures;
* control testing;
* vulnerability reports;
* SIEM dashboards;
* incident records;
* audit reports;
* supplier assessments;
* recovery tests.

The profile is evidence-based rather than based on opinion.

---

# 15. Step 8 – Establish the Target Profile

Management now defines the desired future state.

The target profile reflects:

* business strategy;
* risk appetite;
* regulatory requirements;
* threat environment;
* technology strategy;
* available resources.

The target profile should be ambitious but achievable.

---

# 16. Target Profile Example

### Identify

100% visibility of critical assets and dependencies.

### Protect

Risk-based preventive controls consistently applied to critical services.

### Detect

Continuous monitoring of all critical services.

### Respond

Validated enterprise-wide incident response and crisis-management capability.

### Recover

Cyber-recovery capabilities tested for all critical services.

---

# 17. Current-to-Target Comparison

| Function | Current        | Target    |
| -------- | -------------- | --------- |
| Identify | 94% visibility | 100%      |
| Protect  | Strong         | Optimized |
| Detect   | 92% coverage   | 100%      |
| Respond  | Moderate       | Strong    |
| Recover  | Moderate       | Strong    |

The differences become improvement opportunities.

---

# 18. Step 9 – Determine the Desired Maturity

The organization does not want every capability to reach the highest possible level.

For example:

A low-risk internal application may only require moderate cybersecurity capability.

A customer authentication service may require significantly stronger capability.

Therefore:

> **Target profiles should be risk-based rather than uniformly optimized.**

---

# 19. Risk-Based Targeting Model

```text id="rtm5k8"
             BUSINESS CRITICALITY
                    |
                    v
             CYBER RISK LEVEL
                    |
                    v
           REQUIRED CSF OUTCOMES
                    |
                    v
              TARGET PROFILE
```

This prevents unnecessary investment in low-risk areas.

---

# 20. Step 10 – Define Target Outcomes

For every major capability, the organization defines measurable outcomes.

Example:

### Current

92% of critical assets monitored.

### Target

100%.

### Improvement

Expand cloud and third-party monitoring.

### Measurement

Percentage of critical assets with active monitoring.

This creates an objective basis for measuring progress.

---

# 21. Step 11 – Establish Priority Categories

The organization categorizes profile gaps.

### Critical

Immediate action required.

### High

Address during the current transformation cycle.

### Medium

Address through planned improvement.

### Low

Monitor or accept based on risk.

This creates a manageable portfolio.

---

# 22. Step 12 – Identify Critical Gaps

The profile comparison identifies:

### Gap 1

Cloud asset inventory is incomplete.

### Gap 2

Third-party monitoring is inconsistent.

### Gap 3

Cyber-recovery testing is insufficient.

### Gap 4

Incident exercises are not enterprise-wide.

### Gap 5

Security metrics are focused heavily on activity rather than outcomes.

---

# 23. Step 13 – Build the Profile Gap Register

| Gap                    | Current    | Target     | Priority |
| ---------------------- | ---------- | ---------- | -------- |
| Asset visibility       | 94%        | 100%       | High     |
| Third-party monitoring | Partial    | Continuous | High     |
| Cyber recovery         | 60% tested | 100%       | Critical |
| Incident exercises     | 1/year     | 3/year     | Medium   |
| Outcome metrics        | Limited    | Mature     | Medium   |

The gap register becomes a key GRC management artifact.

---

# 24. Step 14 – Link Gaps to Risks

The organization does not prioritize gaps simply because they exist.

Each gap is linked to a risk.

Example:

**Cyber-recovery gap**

↓

**Ransomware risk**

↓

**Potential prolonged service outage**

↓

**High business impact**

↓

**Critical priority**

This provides a defensible basis for investment.

---

# 25. Step 15 – Link Gaps to Business Services

The GRC team also maps gaps to critical services.

Example:

| Gap                 | Business Service          |
| ------------------- | ------------------------- |
| Cyber recovery      | Cloud hosting             |
| Identity monitoring | Customer authentication   |
| Supplier monitoring | Customer digital services |
| Asset visibility    | Network operations        |

This makes the profile more meaningful to business leadership.

---

# 26. Step 16 – Develop Target-State Scenarios

Management defines several scenarios.

### Scenario A – Minimum Compliance

Meet regulatory and contractual requirements.

### Scenario B – Risk-Based Target

Address significant cybersecurity risks.

### Scenario C – Resilience-Focused Target

Strengthen critical services against major cyber disruption.

The organization chooses **Scenario B with selected resilience enhancements**.

---

# 27. Step 17 – Establish the Target Profile Governance

The target profile requires approval.

The governance process is:

```text id="tpg8r2"
GRC Analysis
     |
     v
CISO Review
     |
     v
Risk Committee
     |
     v
Executive Approval
     |
     v
Target Profile
```

This ensures that the target state represents a management decision.

---

# 28. Step 18 – Convert Profile Gaps Into Initiatives

The organization converts major gaps into projects.

### Gap

Incomplete cloud asset visibility.

### Initiative

Enterprise Cloud Asset Discovery Program.

---

### Gap

Weak cyber-recovery testing.

### Initiative

Cyber Recovery Enhancement Program.

---

### Gap

Supplier monitoring limitations.

### Initiative

Third-Party Continuous Monitoring Program.

---

# 29. Step 19 – Build the Roadmap

The initiatives are scheduled according to risk.

### Quarter 1

Asset visibility.

### Quarter 2

Identity and supplier monitoring.

### Quarter 3

Incident-response improvement.

### Quarter 4

Cyber-recovery expansion.

The sequence reflects dependencies and risk.

---

# 30. Step 20 – Define Success Metrics

Each target outcome requires a metric.

Examples:

### Identify

Percentage of critical assets identified.

### Protect

Percentage of critical vulnerabilities remediated within SLA.

### Detect

Percentage of critical assets monitored.

### Respond

Mean time to contain major incidents.

### Recover

Percentage of critical services successfully recovery-tested.

---

# 31. Example Target Metrics

| Outcome                    | Baseline | Target |
| -------------------------- | -------: | -----: |
| Critical asset visibility  |      94% |   100% |
| Critical vulnerability SLA |      94% |    98% |
| Critical asset monitoring  |      92% |   100% |
| Major incident exercises   |   1/year | 3/year |
| Critical recovery testing  |      60% |   100% |

These metrics allow management to determine whether the target profile is being achieved.

---

# 32. Step 21 – Establish Profile Reporting

The GRC platform creates a Current-to-Target dashboard.

```text id="ctd6m1"
IDENTIFY
Current  █████████░ 94%
Target   ██████████ 100%

PROTECT
Current  █████████░ Strong
Target   ██████████ Optimized

DETECT
Current  █████████░ 92%
Target   ██████████ 100%

RESPOND
Current  ██████░░░░ Moderate
Target   █████████░ Strong

RECOVER
Current  ██████░░░░ Moderate
Target   ██████████ Strong
```

The dashboard gives executives a high-level view of progress.

---

# 33. Step 22 – Integrate With ISO 27001

IberiaCloud already operates an ISO 27001 ISMS.

The organization therefore maps:

**Current Profile**

to:

* ISO 27001 controls;
* risk treatment;
* SoA;
* internal audit;
* management review.

The NIST profile becomes another management view of the same security environment.

---

# 34. Integrated Profile Model

```text id="ipm9v3"
              BUSINESS RISK
                   |
        +----------+----------+
        |                     |
        v                     v
    ISO 27001              NIST CSF
        |                     |
        +----------+----------+
                   |
                   v
             COMMON CONTROLS
                   |
                   v
                EVIDENCE
                   |
                   v
               ASSURANCE
```

This avoids duplicate security programs.

---

# 35. Step 23 – Handle Regulatory Requirements

The target profile incorporates relevant regulatory requirements.

For example:

* stronger incident reporting;
* critical-service resilience;
* supplier security;
* access controls;
* logging;
* business continuity.

Regulatory requirements therefore influence the target state.

---

# 36. Step 24 – Incorporate Threat Intelligence

The organization reviews current threats.

Threat intelligence indicates increasing:

* ransomware;
* identity attacks;
* cloud compromise;
* supply-chain attacks.

Management therefore increases target expectations for:

* identity security;
* monitoring;
* cyber recovery;
* supplier oversight.

This demonstrates that the target profile is threat-informed.

---

# 37. Step 25 – Review the Profile Quarterly

The GRC team reviews:

* changes in risk;
* new technologies;
* incidents;
* threat intelligence;
* regulatory changes;
* project progress;
* control effectiveness.

The profile is updated when significant changes occur.

---

# 38. Step 26 – Manage Exceptions

Some business units cannot immediately achieve the target.

For example:

A legacy platform cannot support modern MFA.

The organization documents:

* exception;
* business justification;
* risk;
* compensating controls;
* owner;
* expiration date.

The exception becomes part of the risk-management process.

---

# 39. Step 27 – Validate the Current Profile

Internal Audit performs independent testing.

It discovers that the GRC team's reported:

**94% asset visibility**

actually represents:

**89% verified coverage**

The difference is investigated.

The issue is caused by duplicate asset records.

The organization corrects the inventory methodology.

This demonstrates why independent assurance is important.

---

# 40. Step 28 – Update the Current Profile

After data-quality improvements:

**Verified coverage = 91%**

The organization does not artificially maintain the previous 94% figure.

The current profile is updated to reflect reality.

This improves management confidence in the profile.

---

# 41. Step 29 – Monitor Progress Toward the Target

Six months later:

| Area              | Baseline | Current | Target |
| ----------------- | -------: | ------: | -----: |
| Asset visibility  |      91% |     97% |   100% |
| Monitoring        |      92% |     98% |   100% |
| Vulnerability SLA |      94% |     96% |    98% |
| Recovery testing  |      60% |     82% |   100% |

The organization can now demonstrate measurable progress.

---

# 42. Step 30 – Management Decision

The CISO presents the profile to the executive committee.

The biggest remaining gap is cyber recovery.

Management decides to allocate additional funding to:

* immutable backup;
* recovery infrastructure;
* recovery exercises;
* specialist resources.

The Current-to-Target Profile has therefore directly influenced investment decisions.

---

# 43. Common Profile-Building Mistakes

## Mistake 1 – Building the Target Before Understanding the Current State

The organization must know where it is before defining where it wants to go.

## Mistake 2 – Making Every Target "Maximum"

Not every system requires the same security level.

## Mistake 3 – Using Unsupported Scores

Every maturity or capability assessment should have evidence.

## Mistake 4 – Ignoring Business Context

The profile should reflect business-critical services and risk.

---

# 44. Additional Mistakes

## Mistake 5 – Treating the Profile as a Static Document

Cybersecurity conditions change continuously.

## Mistake 6 – Failing to Link Gaps to Risk

A gap without risk context is difficult to prioritize.

## Mistake 7 – Ignoring Dependencies

Third parties, cloud services and shared infrastructure can affect profile outcomes.

## Mistake 8 – Creating a Separate NIST Program

NIST CSF should complement existing GRC processes where possible.

---

# 45. Practical Current Profile Checklist

### Business Context

* [ ] Business objectives identified
* [ ] Critical services identified
* [ ] Regulatory requirements identified
* [ ] Threat environment assessed

### Current State

* [ ] Assets assessed
* [ ] Controls assessed
* [ ] Risk assessed
* [ ] Evidence collected
* [ ] Current outcomes documented

### Assurance

* [ ] Assessment methodology defined
* [ ] Evidence validated
* [ ] Internal Audit involved where appropriate
* [ ] Data quality verified

---

# 46. Practical Target Profile Checklist

### Target State

* [ ] Business requirements considered
* [ ] Risk appetite considered
* [ ] Regulatory requirements considered
* [ ] Threat intelligence considered
* [ ] Critical services considered

### Target Outcomes

* [ ] Outcomes defined
* [ ] Metrics established
* [ ] Target levels approved
* [ ] Owners assigned

### Gap Management

* [ ] Current-to-target gaps identified
* [ ] Risks mapped
* [ ] Priorities established
* [ ] Improvement initiatives created
* [ ] Roadmap approved

---

# 47. Executive Current-to-Target Model

```text id="ect8n5"
                  EXECUTIVE OBJECTIVES
                          |
                          v
                    BUSINESS RISK
                          |
             +------------+------------+
             |                         |
             v                         v
       CURRENT PROFILE           TARGET PROFILE
             |                         |
             +------------+------------+
                          |
                          v
                    GAP ANALYSIS
                          |
                          v
                   RISK PRIORITY
                          |
                          v
                  INVESTMENT PLAN
                          |
                          v
                    IMPROVEMENT
                          |
                          v
                     MEASURE
                          |
                          v
                 UPDATED PROFILE
```

This is the core management model.

---

# 48. Case Study Results

After the profile program matures, IberiaCloud achieves:

* a documented enterprise Current Profile;
* an executive-approved Target Profile;
* risk-based gap prioritization;
* measurable cybersecurity objectives;
* integrated ISO 27001 and NIST CSF mapping;
* improved cybersecurity investment decisions;
* stronger executive reporting;
* continuous profile monitoring.

The organization can now clearly explain its cybersecurity position.

---

# 49. Final Case Study Model

```text id="fpm4r7"
                 BUSINESS CONTEXT
                        |
                        v
                 RISK ENVIRONMENT
                        |
             +----------+----------+
             |                     |
             v                     v
       CURRENT PROFILE        TARGET PROFILE
             |                     |
             |                     |
             +----------+----------+
                        |
                        v
                   GAP ANALYSIS
                        |
                        v
                RISK PRIORITIZATION
                        |
                        v
                 ROADMAP / ACTIONS
                        |
                        v
                   IMPLEMENTATION
                        |
                        v
                    MEASUREMENT
                        |
                        v
                 MANAGEMENT REVIEW
                        |
                        v
                 PROFILE UPDATE
                        |
                        +-------> NEXT CYCLE
```

---

# 50. Lessons Learned

## Lesson 1 – Current and Target Profiles Serve Different Purposes

The Current Profile describes reality.

The Target Profile describes the desired future state.

## Lesson 2 – The Gap Is the Management Opportunity

The difference between current and target capabilities provides the basis for cybersecurity improvement.

## Lesson 3 – Profiles Must Be Risk-Based

Not every capability requires the same target level.

## Lesson 4 – Evidence Matters

A profile should be supported by objective information.

---

# 51. Additional Lessons

## Lesson 5 – Business Context Comes First

Cybersecurity targets should support business objectives.

## Lesson 6 – Integrate With Existing GRC

NIST CSF profiles should connect with:

* ISO 27001;
* risk management;
* control management;
* audit;
* compliance;
* executive reporting.

## Lesson 7 – Profiles Should Drive Investment

The profile should help management determine where cybersecurity resources are most needed.

## Lesson 8 – Profiles Are Dynamic

The Current and Target Profiles should evolve as:

* threats change;
* technology changes;
* regulations change;
* business priorities change.

---

# 52. Final Case Study Conclusion

The IberiaCloud case demonstrates that the real value of a NIST CSF Organizational Profile is not the profile document itself.

Its value is the management cycle it creates:

**Business Context → Current Profile → Target Profile → Gap Analysis → Risk Prioritization → Investment → Implementation → Measurement → Profile Update**

A mature GRC professional should therefore be able to answer:

> **Where are we today?**

> **Where should we be?**

> **Why is there a gap?**

> **What risk does the gap create?**

> **What should we invest in first?**

> **How will we know that the investment worked?**

When the Current and Target Profiles are connected to enterprise risk, ISO 27001, control management, audit and executive decision-making, NIST CSF becomes a powerful mechanism for **cybersecurity strategy and continuous improvement**, rather than merely a framework-mapping exercise.

# 19.7 NIST Cybersecurity Framework Case Studies

## Part 3 – Performing a NIST CSF Gap Assessment

## 1. Case Study Overview

After establishing the **Current Organizational Profile** and **Target Organizational Profile**, IberiaCloud Digital Services must determine exactly where the organization falls short of its desired cybersecurity state.

The GRC team therefore performs a formal **NIST CSF Gap Assessment**.

The objective is not simply to identify missing controls. The assessment determines:

* what cybersecurity outcomes currently exist;
* what outcomes are required;
* where capability gaps exist;
* what risks those gaps create;
* which gaps should receive priority;
* what actions are required to close them.

The assessment becomes the bridge between **profile development** and the **implementation roadmap**.

---

# 2. Organization Profile

### Organization

**IberiaCloud Digital Services**

### Industry

Cloud and telecommunications services

### Employees

Approximately 1,800

### Existing Frameworks

* NIST CSF;
* ISO 27001;
* ISO 27005;
* COBIT;
* enterprise risk management.

### Previous Work

The organization has already established:

* a Current Profile;
* a Target Profile;
* a cybersecurity risk register;
* an ISO 27001 control environment;
* a GRC platform.

The next step is to identify and prioritize the gaps.

---

# 3. Business Problem

The organization initially identifies more than **80 potential cybersecurity gaps**.

However, management does not have the resources to address all of them immediately.

The CISO therefore asks the GRC team:

> "Which gaps create the greatest business risk, and which should we address first?"

The GRC team develops a structured gap-assessment methodology.

---

# 4. What Is a NIST CSF Gap Assessment?

A NIST CSF gap assessment compares the organization's:

**Current Profile**

against its:

**Target Profile**

to identify differences in cybersecurity outcomes and capabilities.

The basic model is:

```text id="gapm8x2"
CURRENT PROFILE
      |
      v
ASSESSMENT
      |
      v
TARGET PROFILE
      |
      v
GAP IDENTIFICATION
      |
      v
RISK ANALYSIS
      |
      v
PRIORITIZATION
      |
      v
REMEDIATION ROADMAP
```

---

# 5. Gap vs Risk

An important GRC distinction is:

> **A gap is not automatically a high risk.**

For example:

An internal low-value application may not have advanced monitoring.

That is technically a gap.

But if the application:

* contains no sensitive data;
* is not internet-facing;
* has limited business impact;

the associated risk may be low.

Conversely, a small gap in a customer authentication platform could create significant business risk.

Therefore, gaps must be evaluated in context.

---

# 6. Assessment Objectives

The GRC team establishes six objectives:

1. identify cybersecurity gaps;
2. validate the significance of each gap;
3. determine associated risks;
4. prioritize remediation;
5. estimate required resources;
6. create actionable improvement initiatives.

---

# 7. Step 1 – Confirm Assessment Scope

The assessment covers:

* corporate IT;
* cloud infrastructure;
* customer platforms;
* identity services;
* SOC;
* critical suppliers;
* cybersecurity governance.

Low-risk systems are excluded from the first assessment cycle.

This keeps the exercise manageable.

---

# 8. Step 2 – Confirm the Current Profile

Before performing the gap assessment, the GRC team validates the Current Profile.

The team reviews:

* asset inventories;
* risk assessments;
* control assessments;
* audit findings;
* incident records;
* vulnerability reports;
* SOC metrics;
* recovery tests.

This prevents inaccurate baseline information from entering the gap analysis.

---

# 9. Step 3 – Confirm the Target Profile

The GRC team also validates the Target Profile.

The target state reflects:

* business objectives;
* risk appetite;
* regulatory requirements;
* threat intelligence;
* customer requirements;
* cybersecurity strategy.

The Target Profile has executive approval.

---

# 10. Step 4 – Establish the Assessment Methodology

The GRC team establishes five assessment states:

### 1. Fully Achieved

The desired outcome is consistently achieved.

### 2. Substantially Achieved

The outcome is achieved with minor limitations.

### 3. Partially Achieved

Some capabilities exist, but significant weaknesses remain.

### 4. Minimally Achieved

Only limited capability exists.

### 5. Not Achieved

The required capability is absent.

This provides a consistent assessment language.

---

# 11. Step 5 – Define Assessment Evidence

The assessment must be evidence-based.

Potential evidence includes:

* policies;
* procedures;
* configuration records;
* system reports;
* vulnerability scans;
* SIEM records;
* access reviews;
* incident records;
* audit reports;
* penetration-testing results;
* supplier assessments;
* recovery-test results.

Evidence should demonstrate actual implementation, not merely documented intent.

---

# 12. Step 6 – Assess Identify

The first major assessment area concerns **Identify** capabilities.

The team reviews:

* asset management;
* business environment;
* governance;
* risk assessment;
* risk strategy;
* supply-chain risk.

---

# 13. Identify Assessment Example

### Current State

91% of critical assets are reliably identified.

### Target

100%.

### Gap

9% of critical assets lack verified ownership or inventory information.

### Risk

Security teams may fail to protect or monitor unknown assets.

### Priority

High.

---

# 14. Step 7 – Assess Protect

The GRC team reviews:

* identity management;
* access control;
* awareness;
* data security;
* platform security;
* technology infrastructure.

Example:

Privileged-access management covers 98% of critical administrative accounts.

Target:

100%.

Gap:

2%.

The gap is relatively small but involves highly privileged accounts.

Therefore, the risk may still be significant.

---

# 15. Step 8 – Assess Detect

The SOC provides evidence for detection capabilities.

The team assesses:

* continuous monitoring;
* event analysis;
* detection processes;
* anomaly detection;
* threat detection.

Example:

### Current

98% of critical infrastructure is monitored.

### Target

100%.

### Gap

2%.

However, the missing 2% includes several cloud workloads.

The GRC team therefore investigates whether the gap creates disproportionate risk.

---

# 16. Step 9 – Assess Respond

The assessment examines:

* incident management;
* incident analysis;
* communication;
* mitigation;
* response planning.

The organization has documented procedures.

However, the last enterprise-wide cyber exercise occurred 14 months ago.

The target requires:

**at least three major exercises annually.**

This creates a significant preparedness gap.

---

# 17. Step 10 – Assess Recover

The organization reviews:

* recovery planning;
* recovery execution;
* communication;
* restoration capabilities.

Current cyber-recovery testing covers:

**82% of critical services.**

Target:

**100%.**

The remaining services include two customer-facing platforms.

Because of their business criticality, the gap receives a **critical priority**.

---

# 18. Step 11 – Create the Gap Register

The GRC team consolidates the results.

| ID      | CSF Area | Gap                 | Current | Target | Priority |
| ------- | -------- | ------------------- | ------: | -----: | -------- |
| GAP-001 | Identify | Asset visibility    |     91% |   100% | High     |
| GAP-002 | Protect  | Privileged accounts |     98% |   100% | High     |
| GAP-003 | Detect   | Cloud monitoring    |     98% |   100% | High     |
| GAP-004 | Respond  | Cyber exercises     |  1/year | 3/year | Medium   |
| GAP-005 | Recover  | Cyber recovery      |     82% |   100% | Critical |

The register becomes the central gap-management artifact.

---

# 19. Step 12 – Determine Gap Severity

The team evaluates each gap using several dimensions.

### Business Impact

How significantly could the gap affect the organization?

### Threat Exposure

How likely is the capability to be exploited?

### Regulatory Impact

Could the gap create regulatory non-compliance?

### Customer Impact

Could customers be affected?

### Operational Impact

Could the gap disrupt critical services?

### Financial Impact

Could the gap cause significant financial loss?

---

# 20. Gap Scoring Model

The organization creates a simple scoring model.

```text id="gscore4m"
Gap Priority Score
       =
Business Impact
+
Threat Exposure
+
Regulatory Impact
+
Operational Impact
+
Customer Impact
```

Each dimension is scored from **1 to 5**.

The organization then defines priority thresholds.

---

# 21. Example Gap Score

### Gap

Insufficient cyber-recovery testing.

### Business Impact

5

### Threat Exposure

5

### Regulatory Impact

4

### Operational Impact

5

### Customer Impact

5

Total:

**24/25**

The gap receives **Critical** priority.

---

# 22. Step 13 – Link Gaps to Enterprise Risks

Each important gap is mapped to one or more risks.

Example:

```text id="gtr6k1"
Cyber-Recovery Gap
        |
        v
Ransomware Risk
        |
        v
Service Disruption
        |
        v
Customer Impact
        |
        v
Financial / Regulatory Impact
```

This demonstrates why the gap matters.

---

# 23. Step 14 – Link Gaps to Controls

The GRC team determines which controls address each gap.

Example:

### Gap

Incomplete privileged-account protection.

### Related Controls

* MFA;
* PAM;
* privileged-account review;
* session monitoring;
* access recertification.

This allows remediation to target actual control weaknesses.

---

# 24. Step 15 – Identify Root Causes

The GRC team does not immediately recommend new controls.

It first determines the root cause.

For example:

### Gap

Cloud asset visibility.

### Root Cause

No centralized cloud inventory process.

### Secondary Cause

Cloud teams use different provisioning methods.

### Governance Cause

No mandatory asset-registration requirement.

The remediation therefore needs to address the process and governance problem, not just deploy another tool.

---

# 25. Step 16 – Classify Gap Types

The organization classifies gaps into:

### Governance Gap

Missing policy, ownership or accountability.

### Process Gap

Required processes are incomplete.

### Technology Gap

Technology capability is insufficient.

### People Gap

Insufficient skills or staffing.

### Data Gap

Information is incomplete or unreliable.

### Third-Party Gap

Supplier capabilities are insufficient.

This classification helps determine remediation strategies.

---

# 26. Example Gap Classification

| Gap                 | Primary Type |
| ------------------- | ------------ |
| Asset ownership     | Governance   |
| Cloud discovery     | Technology   |
| Cyber exercises     | Process      |
| SOC cloud skills    | People       |
| Supplier monitoring | Third-party  |
| Recovery evidence   | Data/process |

This provides a more complete understanding of the problem.

---

# 27. Step 17 – Assess Dependencies

Some gaps depend on other initiatives.

For example:

**Continuous cloud monitoring**

may depend on:

* cloud asset discovery;
* centralized logging;
* cloud identity;
* SIEM integration.

Therefore, the GRC team establishes dependencies before prioritizing implementation.

---

# 28. Step 18 – Prioritize the Gaps

The organization categorizes gaps.

### Critical

Immediate executive attention.

### High

Remediation within the current planning cycle.

### Medium

Planned improvement.

### Low

Monitor, accept or address opportunistically.

The final prioritization is risk-based.

---

# 29. Prioritized Gap Portfolio

| Priority | Number of Gaps |
| -------- | -------------: |
| Critical |              5 |
| High     |             17 |
| Medium   |             38 |
| Low      |             24 |

The organization now has a manageable view of its 84 identified gaps.

---

# 30. Step 19 – Create Remediation Initiatives

Multiple related gaps are consolidated into programs.

For example:

### Cloud Security Improvement Program

Addresses:

* cloud asset visibility;
* cloud monitoring;
* cloud identity;
* cloud logging.

This is more efficient than managing each gap independently.

---

# 31. Step 20 – Develop Remediation Actions

For each gap, the GRC team defines:

* action;
* owner;
* deadline;
* resources;
* dependencies;
* expected outcome;
* success metric.

Example:

### Gap

Incomplete cyber-recovery coverage.

### Action

Extend recovery testing to all critical services.

### Owner

Head of IT Resilience.

### Target Date

Q4.

### Success Metric

100% of critical services tested.

---

# 32. Step 21 – Estimate Risk Reduction

The organization estimates expected risk reduction.

Example:

### Current Residual Risk

High.

### Remediation

Cyber-recovery testing and immutable backup expansion.

### Expected Residual Risk

Medium.

The risk owner approves the treatment plan.

---

# 33. Step 22 – Consider Risk Acceptance

Not every gap must be remediated.

For example:

A low-risk legacy application may have a security limitation that would cost €500,000 to eliminate while the associated risk is very low.

Management may decide to:

**accept the risk**

rather than implement an expensive remediation.

The decision must be documented.

---

# 34. Step 23 – Consider Compensating Controls

Sometimes the desired capability cannot be implemented immediately.

Example:

A legacy application cannot support modern MFA.

Compensating controls may include:

* privileged-access gateway;
* network segmentation;
* additional monitoring;
* restricted administrative access.

The risk is reassessed after implementation.

---

# 35. Step 24 – Create the Gap Treatment Model

```text id="gtm5p4"
                 GAP
                  |
        +---------+---------+
        |         |         |
        v         v         v
    REMEDIATE  MITIGATE  ACCEPT
        |         |         |
        v         v         v
     ACTION    CONTROL    RISK
        |         |         |
        +---------+---------+
                  |
                  v
             RISK REVIEW
```

This creates a consistent treatment approach.

---

# 36. Step 25 – Integrate With the GRC Platform

The organization configures the GRC platform to connect:

**NIST CSF Outcome**

↓

**Current State**

↓

**Target State**

↓

**Gap**

↓

**Risk**

↓

**Control**

↓

**Remediation**

↓

**Evidence**

This creates end-to-end traceability.

---

# 37. Step 26 – Automate Gap Tracking

The GRC platform generates automated notifications.

For example:

* remediation approaching deadline;
* overdue action;
* high-risk gap without owner;
* control failing validation;
* target date exceeded.

This improves accountability.

---

# 38. Step 27 – Validate Remediation

Closing an action does not automatically close the gap.

For example:

A team reports:

> "Cloud monitoring has been implemented."

GRC validates:

* configuration;
* coverage;
* alerts;
* evidence;
* operational effectiveness.

Only after validation can the gap be considered effectively addressed.

---

# 39. Step 28 – Reassess the Risk

After remediation:

### Before

Risk rating:

**High**

### After

Risk rating:

**Medium**

The risk register is updated.

The corresponding gap is marked:

**Remediated and validated.**

---

# 40. Step 29 – Update the Current Profile

Once significant remediation is complete, the Current Profile changes.

Example:

### Before

Cloud monitoring:

98%

### After

100%

The profile now moves closer to the Target Profile.

---

# 41. Step 30 – Measure Gap Closure

The GRC team tracks:

* total gaps;
* critical gaps;
* high-risk gaps;
* overdue gaps;
* remediated gaps;
* accepted risks;
* residual gaps.

Example:

| Metric        | Initial | Current |
| ------------- | ------: | ------: |
| Total gaps    |      84 |      51 |
| Critical gaps |       5 |       1 |
| High gaps     |      17 |       8 |
| Closed gaps   |       0 |      33 |
| Overdue gaps  |      12 |       4 |

This gives management a clear improvement picture.

---

# 42. Step 31 – Executive Reporting

The CISO reports:

### Current Position

84 gaps identified.

### Major Concern

5 critical gaps.

### Progress

33 gaps closed.

### Remaining Critical Risk

One critical cyber-recovery gap.

### Investment Required

Additional recovery infrastructure.

The report focuses on decisions rather than technical detail.

---

# 43. Step 32 – Internal Audit Assurance

Internal Audit independently reviews the gap assessment methodology.

It evaluates whether:

* gaps were correctly identified;
* evidence supports conclusions;
* risk ratings are reasonable;
* management actions are appropriate;
* closed gaps were actually remediated.

This provides independent assurance.

---

# 44. Step 33 – Management Review

The Risk and Compliance Committee reviews:

* critical gaps;
* overdue remediation;
* accepted risks;
* resource constraints;
* risk trends.

Management may decide to:

* accelerate remediation;
* accept certain risks;
* increase funding;
* modify targets;
* change priorities.

---

# 45. Step 34 – Update the Target Profile

Business requirements change.

For example, IberiaCloud launches a new AI-powered customer platform.

The target profile is updated to include stronger expectations for:

* AI security;
* data protection;
* model governance;
* third-party AI services;
* monitoring.

The gap assessment must therefore be refreshed.

---

# 46. Gap Assessment Lifecycle

```text id="gcycle8p"
        CURRENT PROFILE
               |
               v
        TARGET PROFILE
               |
               v
         GAP ASSESSMENT
               |
               v
          RISK ANALYSIS
               |
               v
        GAP PRIORITIZATION
               |
               v
       REMEDIATION / TREATMENT
               |
               v
            VALIDATION
               |
               v
         PROFILE UPDATE
               |
               v
       CONTINUAL MONITORING
               |
               +------> NEW GAP ASSESSMENT
```

---

# 47. Common Gap Assessment Mistakes

## Mistake 1 – Treating Every Gap Equally

Not every gap has the same business risk.

## Mistake 2 – Confusing Missing Controls With High Risk

A control gap must be evaluated in context.

## Mistake 3 – Ignoring Root Causes

Installing another security tool may not solve a governance or process problem.

## Mistake 4 – Closing Gaps Without Validation

Management should verify that remediation actually works.

---

# 48. Additional Mistakes

## Mistake 5 – Ignoring Accepted Risk

Some gaps may legitimately remain open if management accepts the associated risk.

## Mistake 6 – Creating Too Many Independent Actions

Related gaps should be consolidated into logical programs.

## Mistake 7 – Ignoring Dependencies

Remediation sequencing matters.

## Mistake 8 – Failing to Update the Profile

A completed remediation should result in an updated cybersecurity posture.

---

# 49. Practical NIST CSF Gap Assessment Checklist

### Preparation

* [ ] Scope defined
* [ ] Current Profile validated
* [ ] Target Profile approved
* [ ] Assessment methodology established

### Assessment

* [ ] Identify assessed
* [ ] Protect assessed
* [ ] Detect assessed
* [ ] Respond assessed
* [ ] Recover assessed

### Evidence

* [ ] Evidence collected
* [ ] Evidence validated
* [ ] Control implementation verified
* [ ] Effectiveness considered

### Gap Management

* [ ] Gaps documented
* [ ] Root causes identified
* [ ] Business impact assessed
* [ ] Risks mapped
* [ ] Priorities assigned

### Treatment

* [ ] Remediation actions defined
* [ ] Owners assigned
* [ ] Deadlines established
* [ ] Compensating controls considered
* [ ] Risk acceptance documented where applicable

### Validation

* [ ] Remediation validated
* [ ] Risk reassessed
* [ ] Current Profile updated
* [ ] Executive reporting updated

---

# 50. Executive Gap Dashboard

A mature GRC dashboard can show:

### Critical Gaps

**5 → 1**

### High Gaps

**17 → 8**

### Overall Gap Closure

**39%**

### Overdue Remediation

**4**

### Risk Accepted

**7**

### Target Achievement

**82%**

The CISO can immediately identify where executive intervention is required.

---

# 51. Final Integrated Model

```text id="finalgap9"
                BUSINESS OBJECTIVES
                       |
                       v
                  BUSINESS RISKS
                       |
                       v
               CURRENT PROFILE
                       |
                       v
                TARGET PROFILE
                       |
                       v
                 GAP REGISTER
                       |
          +------------+------------+
          |            |            |
          v            v            v
       RISK         ROOT CAUSE    IMPACT
     ANALYSIS       ANALYSIS     ANALYSIS
          |            |            |
          +------------+------------+
                       |
                       v
                GAP PRIORITIZATION
                       |
                       v
              TREATMENT DECISION
                       |
        +--------------+--------------+
        |              |              |
        v              v              v
    REMEDIATE       MITIGATE       ACCEPT
        |              |              |
        +--------------+--------------+
                       |
                       v
                  VALIDATION
                       |
                       v
                 RISK REASSESSMENT
                       |
                       v
                PROFILE UPDATE
                       |
                       v
              EXECUTIVE REPORTING
```

---

# 52. Case Study Results

After the gap-assessment program is implemented, IberiaCloud achieves:

* systematic identification of cybersecurity gaps;
* risk-based gap prioritization;
* improved remediation accountability;
* better linkage between gaps and business risks;
* integrated control and evidence traceability;
* measurable gap closure;
* improved executive reporting;
* stronger alignment between NIST CSF and ISO 27001.

The organization no longer views cybersecurity gaps as a simple checklist of missing controls.

Instead, every significant gap is evaluated according to:

**Business Impact → Risk → Root Cause → Treatment → Validation → Risk Reduction**

---

# 53. Lessons Learned

## Lesson 1 – A Gap Must Have Context

The significance of a gap depends on the business service, threat exposure and risk.

## Lesson 2 – Prioritization Is Essential

A large organization will always have more gaps than available resources.

## Lesson 3 – Root Cause Matters

Effective remediation addresses why the gap exists, not merely its visible symptom.

## Lesson 4 – Closure Requires Validation

A remediation action should not be considered complete until its effectiveness is demonstrated.

---

# 54. Additional Lessons

## Lesson 5 – Integrate Gap Management With Risk Management

The most important gaps should appear in the organization's risk-management process.

## Lesson 6 – Use a Common Control Environment

NIST CSF, ISO 27001 and other frameworks should be connected through common controls where practical.

## Lesson 7 – Accepted Risk Is a Valid Management Decision

Not every gap must be eliminated if the risk is understood and formally accepted.

## Lesson 8 – Gap Assessment Is Continuous

New technologies, threats, regulations and business changes continuously create new gaps.

---

# 55. Final Case Study Conclusion

The IberiaCloud case demonstrates that a NIST CSF Gap Assessment is much more than comparing two framework spreadsheets.

A mature assessment creates a complete chain:

**Current Profile → Target Profile → Gap → Risk → Root Cause → Treatment → Validation → Risk Reduction**

The GRC professional's role is to ensure that this chain remains traceable and defensible.

The ultimate objective is not:

> **"Close as many gaps as possible."**

It is:

> **"Reduce the organization's most important cybersecurity risks to an acceptable level."**

That distinction is fundamental to effective cybersecurity governance and risk management.



