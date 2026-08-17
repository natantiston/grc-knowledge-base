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



