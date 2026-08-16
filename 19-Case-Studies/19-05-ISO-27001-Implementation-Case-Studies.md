# 19.5 ISO 27001 Implementation Case Studies

## Part 1 – Building an ISO 27001 ISMS from Scratch

## 1. Case Study Overview

This case study demonstrates how an organization can design and implement an **ISO/IEC 27001 Information Security Management System (ISMS)** from the ground up.

The organization has cybersecurity technologies and security policies, but it does not yet have a formally structured ISMS.

Management wants to establish an ISMS that can:

* systematically manage information security risks;
* define security responsibilities;
* establish appropriate controls;
* demonstrate compliance;
* support continual improvement;
* prepare the organization for ISO 27001 certification.

The implementation follows the general lifecycle:

**Context → Leadership → Planning → Risk Assessment → Risk Treatment → Controls → Operation → Monitoring → Internal Audit → Management Review → Improvement**

---

# 2. Organization Profile

### Company

**IberiaCloud Digital Services**

### Industry

Cloud, Telecommunications and Digital Services

### Employees

Approximately 1,800

### Locations

* Spain
* Portugal
* France

### Critical Services

* Cloud hosting
* Managed connectivity
* Customer portals
* SaaS platforms
* Data analytics
* Managed security services

### Current Security Environment

The organization already has:

* firewalls;
* endpoint protection;
* identity management;
* vulnerability management;
* backup;
* security monitoring.

However, these capabilities operate independently.

There is no integrated ISMS.

---

# 3. The Business Problem

The CEO asks the CISO:

> **"We have many security controls, but how can we demonstrate that information security is systematically managed?"**

The organization identifies several weaknesses:

* security responsibilities are inconsistent;
* risk assessments differ between departments;
* policies are fragmented;
* supplier security is inconsistent;
* evidence is difficult to locate;
* security objectives are not formally measured;
* internal audits are limited;
* management review is informal.

Management therefore decides to establish an ISO 27001-based ISMS.

---

# 4. ISMS Implementation Objective

The organization establishes five primary objectives:

1. create a structured information security management system;
2. align information security with business objectives;
3. establish a formal risk management process;
4. implement appropriate information security controls;
5. prepare for independent certification.

The organization does not treat ISO 27001 as simply a technology project.

It is treated as a **management system implementation**.

---

# 5. Implementation Governance

The CEO appoints an executive sponsor.

The governance structure includes:

### Executive Sponsor

Provides authority and resources.

### CISO

Leads the ISMS program.

### GRC Team

Coordinates:

* risk management;
* policies;
* compliance;
* evidence;
* internal audit.

### IT and Security Teams

Implement technical controls.

### Business Owners

Own information security risks within their areas.

### HR

Supports:

* awareness;
* employment controls;
* training.

### Procurement

Supports supplier security requirements.

### Legal and Privacy

Supports:

* contracts;
* regulatory obligations;
* privacy requirements.

---

# 6. ISMS Implementation Roadmap

The organization establishes a 12-month implementation program.

```text
Phase 1
Context & Scope
      |
      v
Phase 2
Leadership & Governance
      |
      v
Phase 3
Risk Assessment
      |
      v
Phase 4
Risk Treatment
      |
      v
Phase 5
Control Implementation
      |
      v
Phase 6
Evidence & Operation
      |
      v
Phase 7
Monitoring & Measurement
      |
      v
Phase 8
Internal Audit
      |
      v
Phase 9
Management Review
      |
      v
Phase 10
Certification Readiness
```

---

# 7. Step 1 – Establish Organizational Context

The first task is understanding the organization.

The GRC team identifies:

### Internal Issues

* business strategy;
* organizational structure;
* technology environment;
* internal capabilities;
* existing security practices.

### External Issues

* regulatory requirements;
* customer expectations;
* threat environment;
* contractual obligations;
* industry requirements.

The organization documents these factors as part of its ISMS context.

---

# 8. Step 2 – Identify Interested Parties

The organization identifies relevant interested parties.

Examples include:

* customers;
* employees;
* suppliers;
* regulators;
* shareholders;
* business partners;
* certification bodies.

Their information-security requirements are documented.

---

# 9. Interested Party Requirements

For example:

### Customers

Require:

* confidentiality;
* availability;
* data protection;
* security assurance.

### Regulators

Require:

* compliance;
* incident management;
* appropriate security controls.

### Employees

Require:

* clear security responsibilities;
* appropriate access;
* security awareness.

### Suppliers

Must meet applicable security requirements.

---

# 10. Step 3 – Define ISMS Scope

One of the most important implementation decisions is the ISMS scope.

IberiaCloud defines:

> "The information security management system covering the design, operation, support, and management of cloud and managed digital services delivered from the organization's Spain and Portugal operations."

The scope identifies:

* organizational boundaries;
* locations;
* technologies;
* services;
* information assets;
* relevant interfaces.

---

# 11. Why Scope Matters

A poorly defined scope can create problems.

### Scope Too Broad

The organization may attempt to include every business function immediately.

This can make implementation unnecessarily complex.

### Scope Too Narrow

Critical dependencies may be excluded.

The organization therefore defines a scope that is:

**Business-relevant + defensible + manageable**

---

# 12. Step 4 – Establish the Information Security Policy

The organization develops an information security policy approved by executive management.

The policy establishes commitments to:

* protect information;
* manage information security risks;
* comply with applicable requirements;
* establish security objectives;
* provide appropriate resources;
* continually improve the ISMS.

The policy becomes the foundation for the ISMS.

---

# 13. Step 5 – Define Security Objectives

The organization establishes measurable objectives.

Examples:

### Objective 1

Achieve at least **95% compliance** with critical vulnerability remediation SLAs.

### Objective 2

Achieve **100% MFA coverage** for privileged accounts.

### Objective 3

Complete annual security awareness training for at least **98% of employees**.

### Objective 4

Assess **100% of critical suppliers** annually.

The objectives are linked to business and security risks.

---

# 14. Step 6 – Establish the Risk Assessment Methodology

The organization creates a standardized methodology.

Risk is assessed based on:

**Likelihood × Impact**

The methodology defines:

* scoring criteria;
* risk categories;
* assessment frequency;
* risk owners;
* acceptance criteria;
* escalation requirements.

The same methodology is applied consistently across the ISMS scope.

---

# 15. Example Risk Matrix

```text
                    LIKELIHOOD
                 Low  Medium  High

Impact  High      M      H      C
        Medium    L      M      H
        Low       L      L      M
```

Where:

* **L** = Low
* **M** = Medium
* **H** = High
* **C** = Critical

The organization documents the methodology rather than relying on individual judgment.

---

# 16. Step 7 – Create the Asset and Information Inventory

The GRC team identifies important information and supporting assets.

Examples:

* customer databases;
* cloud platforms;
* application servers;
* employee information;
* financial information;
* source code;
* identity systems;
* network infrastructure.

Each asset is assigned an owner.

---

# 17. Step 8 – Perform Information Security Risk Assessment

The organization performs its initial assessment.

Example:

### Asset

Customer cloud database

### Threat

Unauthorized access

### Vulnerability

Excessive privileged access

### Impact

High

### Likelihood

Medium

### Inherent Risk

High

The organization then evaluates existing controls.

---

# 18. Step 9 – Determine Risk Treatment

The organization evaluates treatment options:

* avoid;
* reduce;
* share/transfer;
* retain/accept.

For the privileged access risk, the organization chooses:

**Reduce**

by implementing:

* privileged access management;
* MFA;
* access reviews;
* session monitoring;
* least privilege.

---

# 19. Step 10 – Establish the Risk Treatment Plan

Each significant risk receives a treatment plan.

| Risk                   | Treatment           | Owner            | Target   |
| ---------------------- | ------------------- | ---------------- | -------- |
| Privileged access      | PAM + MFA           | IAM Manager      | 90 days  |
| Supplier risk          | Enhanced assessment | Procurement      | 120 days |
| Data leakage           | DLP                 | Security Manager | 180 days |
| Cloud misconfiguration | CSPM                | Cloud Security   | 90 days  |

The treatment plan becomes a key ISMS management artifact.

---

# 20. Step 11 – Determine Applicable Controls

The organization evaluates the controls required to treat identified risks.

The control selection process considers:

* risk results;
* legal requirements;
* contractual requirements;
* business requirements;
* technology environment;
* customer expectations.

The organization then determines which controls are applicable.

---

# 21. Statement of Applicability

The organization creates the **Statement of Applicability (SoA)**.

The SoA documents:

* applicable controls;
* justification for inclusion;
* implementation status;
* justification for exclusions.

The SoA creates a structured connection between:

**Risk → Control → Implementation**

---

# 22. Example Statement of Applicability

| Control Area       | Applicable | Status      | Reason                 |
| ------------------ | ---------- | ----------- | ---------------------- |
| Access Control     | Yes        | Implemented | Privileged access risk |
| Cryptography       | Yes        | Implemented | Data protection        |
| Supplier Security  | Yes        | In Progress | Third-party risk       |
| Physical Security  | Yes        | Implemented | Data center protection |
| Secure Development | Yes        | In Progress | Application risk       |

The SoA is not simply a checklist.

It should reflect the organization's actual risk and control environment.

---

# 23. Step 12 – Implement Controls

The organization implements or improves controls.

Examples:

### People

* security awareness;
* role definitions;
* background screening where appropriate.

### Process

* incident management;
* access reviews;
* supplier assessments;
* risk management.

### Technology

* MFA;
* SIEM;
* endpoint protection;
* vulnerability management;
* encryption.

---

# 24. Step 13 – Establish Documented Information

The ISMS requires controlled documentation and evidence.

Examples include:

* ISMS policy;
* risk methodology;
* risk register;
* SoA;
* security objectives;
* procedures;
* control records;
* training records;
* audit reports;
* management review records.

The organization establishes document control.

---

# 25. Document Control

The GRC team establishes:

* document owner;
* approval authority;
* version;
* effective date;
* review date;
* access restrictions;
* retention requirements.

This prevents employees from relying on obsolete policies.

---

# 26. Step 14 – Establish Operational Processes

The organization integrates the ISMS into daily operations.

Examples:

### Joiner

New employee receives appropriate access and security training.

### Mover

Access is adjusted when responsibilities change.

### Leaver

Access is revoked when employment ends.

### Supplier Onboarding

Security requirements are assessed before supplier approval.

### Change Management

Security implications are considered before major changes.

---

# 27. Step 15 – Establish Security Awareness

Employees receive security awareness training.

Topics include:

* phishing;
* password security;
* MFA;
* data protection;
* incident reporting;
* acceptable use;
* social engineering.

The organization measures completion and effectiveness.

---

# 28. Step 16 – Establish Incident Management

The ISMS integrates security incident management.

The process includes:

```text
Detection
   |
   v
Reporting
   |
   v
Classification
   |
   v
Investigation
   |
   v
Containment
   |
   v
Recovery
   |
   v
Lessons Learned
```

Incident information may also trigger a risk reassessment.

---

# 29. Step 17 – Establish Supplier Security

Critical suppliers are incorporated into the ISMS.

The organization establishes:

* supplier classification;
* security due diligence;
* contractual requirements;
* security assessments;
* monitoring;
* incident notification;
* offboarding.

This ensures third-party risk is incorporated into the ISMS rather than managed separately.

---

# 30. Step 18 – Establish Performance Monitoring

The organization defines ISMS metrics.

Examples:

* vulnerability remediation;
* security training;
* incidents;
* control effectiveness;
* supplier assessments;
* risk treatment;
* security objectives.

Metrics are reviewed periodically.

---

# 31. Example ISMS Dashboard

```text
ISMS PERFORMANCE

Security Objectives        92%
Risk Treatment             88%
Critical Patch SLA         96%
MFA Privileged Accounts    100%
Security Training          98%
Critical Supplier Review   100%

Overall ISMS Status        GREEN
```

Metrics must be supported by reliable evidence.

---

# 32. Step 19 – Internal Audit

Before certification, IberiaCloud conducts an internal audit.

The audit evaluates whether the ISMS:

* conforms to applicable requirements;
* is properly implemented;
* is operating effectively.

Auditors review:

* documentation;
* interviews;
* evidence;
* control operation;
* risk assessments;
* treatment plans.

---

# 33. Example Internal Audit Finding

### Finding

Two critical suppliers did not have current security assessments.

### Classification

Minor nonconformity / improvement opportunity, depending on the evidence and audit criteria.

### Root Cause

Supplier reassessment workflow was not consistently triggered.

### Corrective Action

Implement automated reassessment reminders and escalation.

---

# 34. Step 20 – Corrective Action

The organization applies a structured process:

```text
Finding
   |
   v
Root Cause
   |
   v
Corrective Action
   |
   v
Implementation
   |
   v
Evidence
   |
   v
Effectiveness Review
   |
   v
Closure
```

Simply fixing the immediate problem is not enough.

The organization must determine whether the underlying cause has been addressed.

---

# 35. Step 21 – Management Review

Senior management reviews the ISMS.

Inputs include:

* audit results;
* risk status;
* security objectives;
* incidents;
* interested-party requirements;
* performance metrics;
* changes affecting the ISMS;
* improvement opportunities.

Management determines whether the ISMS remains suitable and effective.

---

# 36. Example Management Decisions

Management decides to:

* increase security training investment;
* accelerate cloud security automation;
* expand supplier monitoring;
* revise security objectives;
* increase GRC staffing.

These decisions demonstrate management involvement in the ISMS.

---

# 37. Step 22 – Certification Readiness Assessment

Before engaging a certification body, the organization performs a readiness assessment.

The review checks:

* ISMS scope;
* policy;
* risk methodology;
* risk register;
* treatment plans;
* SoA;
* control evidence;
* internal audit;
* management review;
* corrective actions.

The organization then determines whether it is ready for certification.

---

# 38. Certification Preparation

The organization selects an accredited certification body.

The certification process generally includes two major stages.

### Stage 1

Review of ISMS documentation and readiness.

### Stage 2

Assessment of implementation and effectiveness.

The organization must demonstrate not merely that documentation exists, but that the ISMS operates.

---

# 39. Evidence Preparation

The GRC team establishes an evidence repository.

Evidence may include:

* access review records;
* vulnerability reports;
* training records;
* incident records;
* supplier assessments;
* audit results;
* management review records;
* risk treatment evidence.

Evidence must be:

**Relevant + Current + Traceable + Authentic**

---

# 40. End-to-End ISMS Traceability

A mature ISMS creates a relationship between:

```text
Business Requirement
        |
        v
Information Asset
        |
        v
Risk
        |
        v
Treatment
        |
        v
Control
        |
        v
Evidence
        |
        v
Monitoring
        |
        v
Audit
        |
        v
Management Review
```

This traceability is one of the most valuable characteristics of a mature ISMS.

---

# 41. Implementation Timeline

IberiaCloud completes the initial implementation in approximately 12 months.

| Month | Major Activity                  |
| ----: | ------------------------------- |
|     1 | Context and scope               |
|     2 | Governance and policy           |
|     3 | Asset and risk methodology      |
|     4 | Risk assessment                 |
|     5 | Risk treatment                  |
|     6 | SoA                             |
|     7 | Control implementation          |
|     8 | Documentation and evidence      |
|     9 | Operational integration         |
|    10 | Performance monitoring          |
|    11 | Internal audit                  |
|    12 | Management review and readiness |

Actual implementation duration varies significantly depending on organizational size, existing controls, scope, and maturity.

---

# 42. Implementation Challenges

The organization encounters several challenges.

### Challenge 1 – Business Engagement

Some departments initially view the ISMS as a GRC requirement rather than a business responsibility.

### Challenge 2 – Evidence

Security activities exist but are poorly documented.

### Challenge 3 – Risk Ownership

Business units initially expect the GRC team to own their risks.

### Challenge 4 – Control Duplication

Different teams operate overlapping controls.

### Challenge 5 – Legacy Technology

Some systems cannot easily meet modern security requirements.

---

# 43. How the GRC Team Responds

The GRC team focuses on integration rather than bureaucracy.

Instead of creating new processes unnecessarily, it maps existing activities into the ISMS.

For example:

Existing vulnerability management becomes evidence supporting applicable security controls.

Existing incident management becomes part of the ISMS operational framework.

Existing supplier assessments become evidence for supplier security controls.

---

# 44. Avoiding the "Paper ISMS"

A common failure is creating extensive documentation without changing actual behavior.

The organization therefore applies the principle:

> **Document what the organization actually does, improve what is inadequate, and collect evidence that demonstrates operation.**

The ISMS should reflect reality.

---

# 45. Before and After

### Before

```text
Security Tools
     |
     +---- Firewall
     +---- SIEM
     +---- IAM
     +---- EDR
     +---- Backup

Separate Security Activities
```

### After

```text
                    ISMS
                     |
       +-------------+-------------+
       |             |             |
      Risk         Controls      Governance
       |             |             |
       +-------------+-------------+
                     |
                  Evidence
                     |
                  Monitoring
                     |
                   Audit
                     |
              Management Review
                     |
               Improvement
```

The security technologies still exist, but they are now governed within an integrated management system.

---

# 46. Program Results

After implementation, IberiaCloud achieves:

* formal ISMS governance;
* standardized risk assessment;
* improved risk ownership;
* better control visibility;
* centralized evidence;
* measurable security objectives;
* improved supplier governance;
* stronger management oversight;
* improved audit readiness.

The organization is now prepared to pursue ISO 27001 certification.

---

# 47. Key Lessons Learned

## Lesson 1 – ISO 27001 Is a Management System

It is not simply a cybersecurity technology implementation.

## Lesson 2 – Start With Business Context

The ISMS should support organizational objectives.

## Lesson 3 – Risk Drives Control Selection

Controls should be connected to actual risks and requirements.

## Lesson 4 – Evidence Matters

An implemented control without reliable evidence can be difficult to demonstrate during assurance activities.

---

# 48. Additional Lessons

## Lesson 5 – Leadership Is Essential

Management must provide direction, resources, and accountability.

## Lesson 6 – Scope Must Be Defensible

A poorly designed scope can weaken the credibility of the ISMS.

## Lesson 7 – Business Owners Own Risk

The GRC team facilitates and challenges; it does not replace business accountability.

## Lesson 8 – Continual Improvement Is Fundamental

The ISMS should evolve as:

* threats change;
* technology changes;
* regulations change;
* business objectives change.

---

# 49. Practical ISO 27001 Implementation Checklist

### Context

* [ ] Organizational context documented
* [ ] Interested parties identified
* [ ] ISMS scope established
* [ ] ISMS boundaries documented

### Leadership

* [ ] Executive sponsor assigned
* [ ] Information security policy approved
* [ ] Roles and responsibilities defined
* [ ] Resources allocated

### Risk

* [ ] Risk methodology established
* [ ] Assets identified
* [ ] Risks assessed
* [ ] Risk owners assigned
* [ ] Risk treatment established

### Controls

* [ ] Applicable controls identified
* [ ] Statement of Applicability completed
* [ ] Controls implemented
* [ ] Control evidence collected

### Operation

* [ ] Security processes implemented
* [ ] Awareness program established
* [ ] Incident management operating
* [ ] Supplier security operating
* [ ] Access management operating

### Assurance

* [ ] ISMS metrics established
* [ ] Internal audit completed
* [ ] Findings addressed
* [ ] Management review completed

### Certification Readiness

* [ ] Documentation controlled
* [ ] Evidence available
* [ ] Corrective actions completed
* [ ] ISMS operating effectively
* [ ] Certification readiness assessed

---

# 50. Final ISO 27001 ISMS Implementation Model

```text
                    BUSINESS CONTEXT
                          |
                          v
                    ISMS SCOPE
                          |
                          v
                  LEADERSHIP & POLICY
                          |
                          v
                  RISK ASSESSMENT
                          |
                          v
                   RISK TREATMENT
                          |
                          v
              STATEMENT OF APPLICABILITY
                          |
                          v
                 CONTROL IMPLEMENTATION
                          |
                          v
                 OPERATION & EVIDENCE
                          |
                          v
              PERFORMANCE MONITORING
                          |
                          v
                   INTERNAL AUDIT
                          |
                          v
                 MANAGEMENT REVIEW
                          |
                          v
                  CORRECTIVE ACTION
                          |
                          v
                CONTINUAL IMPROVEMENT
                          |
                          +----------↺
```

# 51. Case Study Conclusion

The IberiaCloud case demonstrates how an organization can transform fragmented cybersecurity activities into a structured **ISO 27001 Information Security Management System**.

The critical lesson is that ISO 27001 implementation should not begin with:

> **"Which controls do we need?"**

It should begin with:

> **"What are our business objectives, information-security requirements, risks, and governance responsibilities?"**

From there, the organization builds a logical chain:

**Context → Scope → Leadership → Risk → Treatment → Controls → Evidence → Monitoring → Audit → Management Review → Improvement**

For a GRC professional, this case demonstrates the practical ability to translate ISO 27001 requirements into an operational management system rather than treating certification as a documentation exercise.

The ultimate objective is not simply to obtain a certificate.

It is to establish an ISMS that enables the organization to **systematically manage information security risk, demonstrate accountability, provide assurance, and continually improve its security posture**.

# 19.5 ISO 27001 Implementation Case Studies

## Part 2 – ISO 27001 Certification Readiness and Pre-Audit Assessment

## 1. Case Study Overview

After implementing its Information Security Management System, **IberiaCloud Digital Services** reaches the next critical stage: determining whether the organization is genuinely ready for an ISO/IEC 27001 certification audit.

The organization has:

* an approved ISMS scope;
* an information security policy;
* a risk assessment methodology;
* a risk register;
* risk treatment plans;
* a Statement of Applicability;
* implemented controls;
* security procedures;
* operational evidence.

However, management does not want to enter certification with the assumption that documentation automatically means readiness.

The CISO therefore commissions a formal **ISO 27001 certification readiness assessment**.

The objective is to identify gaps before the certification body does.

---

# 2. The Certification Readiness Problem

The organization initially believes it is approximately **95% ready**.

The GRC team challenges this assumption.

A document review shows that most required documents exist.

However, deeper testing reveals problems:

* some controls are implemented inconsistently;
* several records are incomplete;
* risk assessments are outdated;
* one internal audit finding remains unresolved;
* some employees cannot demonstrate awareness of applicable procedures;
* supplier reviews are not consistently performed;
* management review evidence is incomplete.

This leads to an important GRC lesson:

> **Certification readiness must be demonstrated through evidence of an operating ISMS, not estimated from the percentage of documents completed.**

---

# 3. Readiness Assessment Objectives

The assessment seeks to determine whether:

1. the ISMS scope is appropriate;
2. leadership involvement is demonstrable;
3. risks are properly assessed;
4. controls are appropriately selected;
5. controls are implemented;
6. processes operate consistently;
7. evidence is available;
8. internal audit has been completed;
9. management review has occurred;
10. corrective actions are effective.

---

# 4. Certification Readiness Model

The GRC team uses six readiness dimensions:

```text id="rdy6m1"
Governance
    |
    v
Risk Management
    |
    v
Control Implementation
    |
    v
Operational Evidence
    |
    v
Internal Audit
    |
    v
Management Review
```

All six dimensions must be sufficiently mature before certification.

---

# 5. Step 1 – Confirm the ISMS Scope

The first assessment verifies whether the documented scope accurately reflects reality.

The scope covers:

* cloud services;
* managed digital services;
* Spain and Portugal operations;
* supporting IT infrastructure.

The review discovers that a recently established cloud operations team in France provides support to systems within the scope.

The team was not explicitly addressed in the original scope analysis.

This creates a scope clarification requirement.

---

# 6. Scope Validation

The GRC team evaluates:

### Organizational Boundaries

Who operates the services?

### Physical Boundaries

Which locations are involved?

### Technological Boundaries

Which platforms and infrastructure support the services?

### Information Boundaries

Which information is processed?

### Interfaces

Which external providers support the ISMS?

The scope is updated to clearly explain relevant interfaces and dependencies.

---

# 7. Step 2 – Review Interested Parties

The assessment reviews whether interested-party requirements remain current.

The organization identifies:

* customers;
* regulators;
* employees;
* suppliers;
* shareholders;
* business partners.

A major customer has recently introduced additional contractual security requirements.

These requirements were not yet reflected in the ISMS requirements register.

The GRC team updates the register.

---

# 8. Step 3 – Review the Information Security Policy

The policy is assessed against:

* organizational context;
* security objectives;
* management commitment;
* applicable requirements;
* continual improvement.

The policy remains appropriate.

However, the review discovers that the current policy review date is overdue.

The policy is formally reviewed and reapproved.

---

# 9. Step 4 – Review Security Objectives

The organization established four security objectives.

| Objective                    | Target | Current |
| ---------------------------- | -----: | ------: |
| Critical patch SLA           |    95% |     96% |
| Privileged MFA               |   100% |    100% |
| Security training            |    98% |   98.5% |
| Critical supplier assessment |   100% |     94% |

The supplier-security objective is below target.

Management requires corrective action.

---

# 10. Step 5 – Review Risk Assessment

The GRC team samples 40 risks.

The assessment checks:

* asset;
* threat;
* vulnerability;
* impact;
* likelihood;
* inherent risk;
* existing controls;
* residual risk;
* risk owner;
* treatment.

The results identify:

* 35 fully supported assessments;
* 3 requiring updated business impact;
* 2 with outdated threat assumptions.

The organization updates the affected assessments.

---

# 11. Risk Assessment Traceability

The readiness team verifies that important risks connect to treatment and controls.

For example:

```text id="trc82x"
Customer Data
      |
      v
Unauthorized Access Risk
      |
      v
High Residual Risk
      |
      v
MFA + PAM + Access Review
      |
      v
Control Evidence
      |
      v
Effectiveness Testing
```

This demonstrates that the ISMS is operating as an integrated system.

---

# 12. Step 6 – Review Risk Treatment

The organization has 72 treatment actions.

Current status:

* 61 completed;
* 8 in progress;
* 3 overdue.

The three overdue actions concern legacy applications.

The GRC team evaluates whether the overdue actions create unacceptable residual risk.

One risk remains within approved tolerance.

Two require escalation.

---

# 13. Step 7 – Review the Statement of Applicability

The SoA is one of the most important readiness documents.

The GRC team verifies:

* applicability decisions;
* justification;
* implementation status;
* relationship to risk treatment;
* consistency with actual controls.

The review identifies one control marked "Implemented" even though its operating process is still being formalized.

The status is corrected.

This prevents the organization from presenting an inaccurate control implementation position.

---

# 14. Step 8 – Control Implementation Review

The team samples 25 applicable controls.

Each control is classified:

### Implemented

The control exists and operates.

### Partially Implemented

The control exists but has gaps.

### Not Implemented

The control is not operating.

### Not Applicable

The organization has documented justification.

Results:

| Status                | Controls |
| --------------------- | -------: |
| Implemented           |       21 |
| Partially implemented |        3 |
| Not implemented       |        1 |

The organization determines whether the gaps affect certification readiness.

---

# 15. Step 9 – Evidence Review

The GRC team evaluates evidence quality.

Evidence should demonstrate:

* what happened;
* when it happened;
* who performed it;
* what system/process was involved;
* whether the control operated as intended.

Weak evidence includes:

> "Access reviews are performed quarterly."

Strong evidence includes:

> A dated quarterly access review record showing the population reviewed, reviewer, exceptions identified, remediation actions, and approval.

---

# 16. Evidence Quality Model

The team evaluates evidence using:

**Complete + Current + Relevant + Traceable + Authentic**

For example:

### Weak

Screenshot without date or ownership.

### Strong

System-generated report containing:

* date;
* user population;
* reviewer;
* exceptions;
* approval;
* remediation evidence.

---

# 17. Step 10 – Employee Awareness Testing

The readiness team interviews employees.

Employees are asked questions such as:

* What are your information-security responsibilities?
* How do you report a suspected incident?
* What should you do with sensitive information?
* Where can you find security policies?
* What happens if you identify a security problem?

The results are mixed.

Approximately 91% of interviewed employees demonstrate adequate awareness.

The target was 98%.

The organization launches a targeted awareness campaign.

---

# 18. Step 11 – Supplier Security Assessment

The readiness assessment reviews 20 critical suppliers.

Results:

* 18 have current assessments;
* 1 has an expired assessment;
* 1 is undergoing reassessment.

The organization identifies the issue as a process weakness rather than merely a supplier problem.

The supplier reassessment workflow is improved.

---

# 19. Step 12 – Incident Management Evidence

The team reviews security incidents from the previous 12 months.

The assessment confirms:

* incidents are recorded;
* incidents are classified;
* investigations are documented;
* corrective actions exist.

However, lessons learned are inconsistently documented.

The organization introduces a standardized post-incident review template.

---

# 20. Step 13 – Access Management Evidence

The team reviews privileged access.

Evidence demonstrates:

* privileged accounts are identified;
* MFA is enabled;
* access is reviewed;
* inactive accounts are removed.

However, one legacy system does not yet support the organization's standard MFA mechanism.

The exception is formally documented and risk-assessed.

---

# 21. Step 14 – Vulnerability Management

The organization reviews vulnerability management.

Metrics show:

* 96% of critical vulnerabilities meet SLA;
* 4% exceed SLA.

The team analyzes the exceptions.

Most are associated with systems requiring planned maintenance windows.

The risks are documented and formally tracked.

This demonstrates that a missed SLA is not automatically an audit failure if the organization appropriately manages the associated risk and process.

---

# 22. Step 15 – Business Continuity Evidence

The readiness assessment reviews:

* backup;
* recovery testing;
* business continuity;
* disaster recovery;
* critical service dependencies.

The organization successfully demonstrates recovery testing for major systems.

However, one critical application has not participated in a full recovery exercise during the expected review period.

The issue is added to the corrective action plan.

---

# 23. Step 16 – Internal Audit Review

The organization has completed its internal audit.

The readiness team verifies whether the audit:

* covered the ISMS scope;
* used appropriate audit criteria;
* assessed implementation;
* identified findings;
* documented evidence;
* maintained auditor objectivity.

The internal audit is considered substantially effective.

However, one audit area lacked sufficient sampling evidence.

The audit record is supplemented.

---

# 24. Internal Audit Findings

The internal audit produced five findings:

| Finding               | Severity | Status            |
| --------------------- | -------- | ----------------- |
| Supplier reassessment | Medium   | Open              |
| Legacy MFA            | Medium   | Open              |
| Awareness gap         | Low      | Corrective action |
| Recovery testing      | Medium   | Open              |
| Document review       | Low      | Closed            |

Management prioritizes the three medium findings.

---

# 25. Step 17 – Corrective Action Review

Each finding is reviewed using:

```text id="ca91xk"
Finding
   |
   v
Containment
   |
   v
Root Cause
   |
   v
Corrective Action
   |
   v
Implementation
   |
   v
Effectiveness Verification
   |
   v
Closure
```

The readiness team refuses to close findings simply because an action was completed.

Effectiveness must be demonstrated.

---

# 26. Example Corrective Action

### Finding

Critical supplier reassessments were not consistently completed.

### Root Cause

Supplier reassessment dates were tracked manually.

### Corrective Action

Implement automated reassessment notifications.

### Evidence

GRC workflow records.

### Effectiveness Test

Review 20 critical suppliers after implementation.

### Success Criterion

100% have valid reassessment status.

---

# 27. Step 18 – Management Review

Management review is assessed carefully.

The GRC team confirms that management reviewed:

* ISMS performance;
* audit findings;
* risk status;
* security objectives;
* interested-party changes;
* improvement opportunities;
* resource requirements.

Management approves:

* additional GRC resources;
* improved supplier monitoring;
* recovery testing;
* MFA modernization.

---

# 28. Management Review Evidence

The organization maintains:

* agenda;
* participants;
* management inputs;
* decisions;
* actions;
* responsible owners;
* target dates.

This demonstrates that management review is an active governance process rather than a document created solely for audit purposes.

---

# 29. Step 19 – Readiness Scoring

The organization performs a final readiness assessment.

| Area                   | Score |
| ---------------------- | ----: |
| Context and Scope      |   95% |
| Leadership             |   96% |
| Risk Management        |   92% |
| Control Implementation |   89% |
| Evidence               |   87% |
| Awareness              |   91% |
| Internal Audit         |   94% |
| Management Review      |   96% |
| Continual Improvement  |   88% |

Overall readiness is assessed as:

**High, with targeted corrective actions required.**

The organization does not use the score as a substitute for professional judgment.

---

# 30. Critical vs Non-Critical Gaps

Not every gap should automatically delay certification.

The organization categorizes gaps.

### Critical

Potentially threatens the effectiveness of the ISMS.

Examples:

* major scope failure;
* systematic risk-management failure;
* absent internal audit;
* absent management review;
* significant control failure.

### Significant

Requires prompt corrective action.

Examples:

* repeated supplier assessment failures;
* major evidence gaps;
* ineffective risk treatment.

### Minor

Localized weakness.

Examples:

* outdated document;
* isolated evidence issue;
* minor process inconsistency.

---

# 31. Certification Go/No-Go Decision

The CISO presents the readiness assessment to the executive committee.

### Recommendation

**Proceed with certification preparation**, subject to closure or formal treatment of priority gaps.

The committee approves the recommendation.

---

# 32. Certification Audit Preparation

The GRC team establishes an audit coordination plan.

Responsibilities include:

### Audit Coordinator

Manages the certification audit.

### Process Owners

Provide operational evidence.

### Control Owners

Explain control operation.

### GRC

Coordinates:

* evidence;
* risk documentation;
* SoA;
* audit responses.

### Executives

Provide leadership and management evidence.

---

# 33. Audit Evidence Room

The organization creates a structured repository:

```text id="evr7a2"
01 Governance
02 ISMS Scope
03 Policies
04 Risk Management
05 Risk Treatment
06 Statement of Applicability
07 Control Evidence
08 Security Operations
09 Supplier Security
10 Internal Audit
11 Management Review
12 Corrective Actions
```

This makes evidence retrieval efficient during the audit.

---

# 34. Auditor Interview Preparation

The GRC team does not give employees scripted answers.

Instead, employees receive guidance to:

* answer truthfully;
* describe actual processes;
* provide evidence;
* avoid speculation;
* identify the appropriate process owner when necessary.

The goal is to demonstrate that the ISMS is genuinely embedded.

---

# 35. Mock Audit

Before certification, the organization performs a two-day mock audit.

The mock auditor asks:

> "Show me how this risk was assessed."

The risk owner demonstrates:

* risk record;
* methodology;
* assessment;
* treatment;
* control;
* evidence.

The mock auditor then asks:

> "How do you know the control is effective?"

The organization provides testing evidence.

This demonstrates traceability.

---

# 36. Mock Audit Finding

The mock audit discovers that one control has evidence but no documented effectiveness review.

The organization addresses the gap before certification.

This illustrates the value of a readiness assessment:

> **It identifies weaknesses while there is still time to correct them.**

---

# 37. Certification Audit Simulation

During the actual audit, the auditor selects:

**Risk: Unauthorized privileged access**

The auditor asks:

1. What is the risk?
2. Who owns it?
3. How was it assessed?
4. What controls treat it?
5. How are the controls implemented?
6. Show evidence.
7. How is effectiveness measured?
8. When was the risk last reviewed?

The GRC team traces the complete lifecycle.

---

# 38. End-to-End Audit Traceability

```text id="at82qp"
Risk
 |
 +--> Risk Assessment
 |
 +--> Risk Owner
 |
 +--> Treatment Plan
 |
 +--> Applicable Control
 |
 +--> Control Owner
 |
 +--> Control Evidence
 |
 +--> Effectiveness Testing
 |
 +--> Monitoring
 |
 +--> Internal Audit
 |
 +--> Management Review
```

This is one of the strongest demonstrations of ISMS maturity.

---

# 39. Lessons From the Readiness Assessment

## Lesson 1 – Documentation Is Not Enough

Auditors evaluate whether the management system operates.

## Lesson 2 – Evidence Should Be Prepared Continuously

Organizations should not create evidence immediately before certification.

## Lesson 3 – Risk and Controls Must Connect

A disconnected risk register and control framework weakens the ISMS.

## Lesson 4 – Internal Audit Is a Preparation Mechanism

Internal audit should identify problems before external certification.

---

# 40. Additional Lessons

## Lesson 5 – Management Review Must Be Genuine

Executives must actually review performance and make decisions.

## Lesson 6 – Employee Awareness Matters

Employees are part of the operating ISMS.

## Lesson 7 – Exceptions Must Be Managed

Legacy technology does not automatically invalidate an ISMS, but exceptions require appropriate risk treatment.

## Lesson 8 – Certification Is Not the End

After certification, surveillance and continual improvement remain necessary.

---

# 41. Practical Certification Readiness Checklist

### ISMS Foundation

* [ ] ISMS scope confirmed
* [ ] Organizational context reviewed
* [ ] Interested parties reviewed
* [ ] Policy approved
* [ ] Security objectives established

### Risk

* [ ] Risk methodology approved
* [ ] Risk register current
* [ ] Risk owners assigned
* [ ] Risk treatment current
* [ ] Risk acceptance documented

### Controls

* [ ] SoA reviewed
* [ ] Applicable controls implemented
* [ ] Control owners assigned
* [ ] Control evidence available
* [ ] Control effectiveness evaluated

### Operations

* [ ] Incident management operating
* [ ] Access management operating
* [ ] Vulnerability management operating
* [ ] Supplier security operating
* [ ] Business continuity evidence available
* [ ] Security awareness operating

### Assurance

* [ ] Internal audit completed
* [ ] Findings documented
* [ ] Corrective actions implemented
* [ ] Effectiveness verified
* [ ] Management review completed

### Certification

* [ ] Scope confirmed
* [ ] Evidence repository organized
* [ ] Mock audit completed
* [ ] Major gaps addressed
* [ ] Audit participants identified
* [ ] Certification audit scheduled

---

# 42. Final Certification Readiness Model

```text id="crf6p2"
             ISMS IMPLEMENTATION
                     |
                     v
              READINESS REVIEW
                     |
          +----------+----------+
          |                     |
      GAPS FOUND           NO MAJOR GAPS
          |                     |
          v                     |
    Corrective Action           |
          |                     |
          v                     |
    Effectiveness Test          |
          |                     |
          +----------+----------+
                     |
                     v
             MANAGEMENT REVIEW
                     |
                     v
              MOCK AUDIT
                     |
                     v
          CERTIFICATION AUDIT
                     |
                     v
             CERTIFICATION
                     |
                     v
          CONTINUAL IMPROVEMENT
                     |
                     +---------↺
```

# 43. Case Study Conclusion

The IberiaCloud case demonstrates that **ISO 27001 certification readiness is fundamentally an assurance exercise**.

The organization must be able to demonstrate a coherent chain from:

**Business Context → ISMS Scope → Risk → Treatment → Control → Evidence → Monitoring → Audit → Management Review → Improvement**

The most important question before certification is therefore not:

> **"Do we have all the documents?"**

It is:

> **"Can we demonstrate that our ISMS is implemented, operating, monitored, reviewed, and continually improved?"**

For a GRC professional, certification readiness requires more than knowledge of ISO 27001 requirements. It requires the ability to:

* challenge management assumptions;
* evaluate evidence;
* identify control weaknesses;
* assess risk;
* coordinate corrective actions;
* prepare business owners;
* support auditors;
* establish traceability;
* and determine whether the organization is genuinely ready for independent assurance.

A successful certification program should therefore be viewed not as a **one-time audit project**, but as the transition from **implementation to sustainable information-security governance**.

# 19.5 ISO 27001 Implementation Case Studies

## Part 3 – ISO 27001 Surveillance Audit and Continual Improvement

## 1. Case Study Overview

One year after achieving ISO/IEC 27001 certification, **IberiaCloud Digital Services** enters its first surveillance audit cycle.

The organization initially assumes that certification means the ISMS is now "complete."

The CISO corrects this assumption:

> **Certification is not the end of the ISMS. It is the beginning of a recurring assurance and continual-improvement cycle.**

The surveillance audit will determine whether the ISMS continues to:

* operate effectively;
* remain relevant to the organization;
* manage changing risks;
* maintain appropriate controls;
* generate reliable evidence;
* address audit findings;
* respond to organizational and technological changes.

---

# 2. Organization Profile

### Company

**IberiaCloud Digital Services**

### Industry

Cloud, Telecommunications and Digital Services

### Employees

Approximately 1,800

### Certified ISMS Scope

Cloud and managed digital services supporting operations in Spain and Portugal.

### Certification Status

ISO 27001 certified approximately 12 months earlier.

### Current Environment

Since certification, the organization has:

* migrated workloads to additional cloud platforms;
* acquired a smaller SaaS company;
* introduced AI-enabled customer-service tools;
* changed several critical suppliers;
* experienced increased phishing attempts;
* expanded remote working;
* introduced new regulatory requirements.

These changes create new information-security risks.

---

# 3. Why Surveillance Audits Matter

A certification audit provides assurance at a particular point in time.

A surveillance audit asks:

> **"Does the ISMS continue to operate effectively?"**

The auditor therefore looks beyond the original certification evidence.

The focus includes:

* changes;
* risk reassessment;
* control operation;
* internal audits;
* management reviews;
* corrective actions;
* continual improvement.

---

# 4. The Post-Certification Risk

The organization discovers that some teams have gradually returned to old habits.

Examples include:

* informal access requests;
* incomplete supplier reassessments;
* outdated procedures;
* inconsistent evidence;
* delayed risk reviews.

This is a common post-certification challenge.

The organization had successfully implemented the ISMS, but maintaining discipline requires continuous governance.

---

# 5. Surveillance Audit Lifecycle

```text id="svl7m2"
Certification
     |
     v
ISMS Operation
     |
     v
Risk Monitoring
     |
     v
Internal Audit
     |
     v
Management Review
     |
     v
Corrective Action
     |
     v
Surveillance Audit
     |
     v
Continual Improvement
     |
     +----------↺
```

---

# 6. Step 1 – Review Changes to the Organization

The GRC team begins by identifying changes since certification.

### Major Changes

* new cloud provider;
* acquisition;
* new AI service;
* new customer contracts;
* new employees;
* new regulatory obligations;
* changes in threat environment.

Each change is evaluated for its potential effect on the ISMS.

---

# 7. Change Impact Assessment

The GRC team uses a structured assessment.

```text id="cim5r8"
Organizational Change
        |
        v
Information Security Impact?
        |
     +--+--+
     |     |
    Yes    No
     |     |
     v     v
Risk     Document
Review   Decision
     |
     v
ISMS Update
```

This ensures significant changes do not bypass the ISMS.

---

# 8. Step 2 – ISMS Scope Review

The acquisition introduces a new SaaS business.

The acquired company processes customer information and uses cloud infrastructure.

The GRC team asks:

* Does the acquired business fall within the existing scope?
* Does it create new interfaces?
* Are new information assets involved?
* Are new suppliers involved?
* Are new risks introduced?

The scope is reassessed.

---

# 9. Scope Decision

Management decides to expand the ISMS scope to include relevant services from the acquired company.

The scope documentation is updated.

The organization also identifies integration dependencies between:

* existing systems;
* acquired systems;
* cloud platforms;
* identity services;
* security monitoring.

This prevents the acquisition from creating an unmanaged security boundary.

---

# 10. Step 3 – Risk Reassessment

The GRC team performs targeted risk reassessment.

New risks include:

### AI Service Risk

Potential exposure of customer information through AI-enabled services.

### Cloud Concentration Risk

Dependency on a limited number of cloud providers.

### Integration Risk

Security weaknesses during integration of the acquired company.

### Supplier Risk

New third-party dependencies.

### Identity Risk

Different identity architectures between organizations.

---

# 11. Example New Risk

### Risk

Sensitive customer information may be exposed through an AI-enabled customer-service platform.

### Threat

Unauthorized access or inappropriate disclosure.

### Vulnerability

Insufficient data-handling controls and unclear AI usage restrictions.

### Impact

High.

### Likelihood

Medium.

### Residual Risk

High before additional treatment.

The risk is escalated to the appropriate owner.

---

# 12. Step 4 – Update Risk Treatment

The organization establishes treatment actions:

* AI data classification;
* approved-use requirements;
* access restrictions;
* logging;
* monitoring;
* employee awareness;
* supplier contractual controls.

The risk treatment plan is updated.

This demonstrates that the ISMS adapts to technological change.

---

# 13. Step 5 – Review the Statement of Applicability

The GRC team reviews the Statement of Applicability.

The question is not simply:

> "Has the SoA changed?"

The more important question is:

> **"Does the SoA still accurately reflect the organization's risks, requirements, and controls?"**

New risks and organizational changes may require controls to be added, modified, or reassessed.

---

# 14. Step 6 – Control Effectiveness Review

The GRC team evaluates selected controls.

The review examines:

* design;
* implementation;
* operation;
* evidence;
* effectiveness.

Example:

### Access Review Control

The organization requires quarterly privileged-access reviews.

Testing reveals:

* 100% of reviews were scheduled;
* 94% were completed on time;
* 6% were delayed.

The delays are investigated.

---

# 15. Root Cause of Control Weakness

The delays were caused by:

* unclear reviewer responsibilities;
* organizational changes;
* incomplete automated notifications.

The GRC team improves the workflow.

This is more valuable than simply reporting:

**"94% compliant."**

The objective is to understand **why the control is underperforming**.

---

# 16. Step 7 – Review Security Objectives

The organization reviews its security objectives.

Previous objectives included:

* vulnerability remediation;
* MFA;
* training;
* supplier assessments.

The organization now adds an AI-related objective:

> **100% of approved AI services must undergo information-security and privacy risk assessment before production use.**

This aligns the ISMS with the organization's changing technology environment.

---

# 17. Step 8 – Review Security Incidents

The organization reviews incidents since certification.

During the year:

* 37 security incidents were recorded;
* 5 were classified as significant;
* 1 involved unauthorized access;
* 31 were resolved within defined targets.

The organization examines incident trends.

---

# 18. Incident Trend Analysis

The largest increase is phishing.

Phishing incidents increased by approximately:

**28%**

compared with the previous year.

The organization therefore reassesses:

* awareness;
* email security;
* MFA;
* phishing-resistant authentication;
* incident reporting.

This demonstrates the connection between incident management and risk management.

---

# 19. Step 9 – Lessons Learned From Incidents

A significant phishing incident reveals that several employees reported suspicious messages only after interacting with them.

The organization introduces:

* improved reporting mechanisms;
* targeted awareness;
* simulated phishing;
* enhanced email controls;
* additional authentication protections.

Incident lessons therefore become ISMS improvement actions.

---

# 20. Step 10 – Supplier Risk Review

The organization reviews its critical suppliers.

Current results:

| Supplier Status    | Number |
| ------------------ | -----: |
| Critical suppliers |     42 |
| Current assessment |     39 |
| Assessment overdue |      3 |

The GRC team investigates the three overdue assessments.

Two are caused by supplier delays.

One is caused by an internal workflow problem.

---

# 21. Supplier Improvement

The organization introduces automated supplier review reminders.

Critical suppliers are also assigned risk-based monitoring frequencies.

For example:

### Critical Supplier

Quarterly monitoring.

### High-Risk Supplier

Semiannual monitoring.

### Lower-Risk Supplier

Annual reassessment.

This moves supplier management from a calendar-driven process toward a risk-based process.

---

# 22. Step 11 – Internal Audit

Before surveillance, Internal Audit performs an ISMS audit.

The audit focuses on:

* risk management;
* access control;
* supplier security;
* incident management;
* AI governance;
* evidence management.

The audit identifies four findings.

---

# 23. Internal Audit Findings

| Finding                     | Risk   | Status |
| --------------------------- | ------ | ------ |
| Supplier reassessment delay | Medium | Open   |
| Access review delay         | Medium | Open   |
| AI assessment process       | Medium | Open   |
| Document review             | Low    | Closed |

The findings are entered into the corrective-action process.

---

# 24. Step 12 – Corrective Action Effectiveness

The organization does not simply mark actions complete.

For each action, it asks:

> **"Did the corrective action actually prevent recurrence?"**

For example:

### Original Problem

Supplier reassessments were delayed.

### Action

Automated reminders were introduced.

### Effectiveness Test

Review the next reassessment cycle.

### Result

100% of critical suppliers were reassessed within the required period.

The corrective action is therefore considered effective.

---

# 25. Step 13 – Management Review

Senior management reviews the ISMS.

Inputs include:

* internal audit results;
* surveillance readiness;
* risk trends;
* incidents;
* supplier performance;
* security objectives;
* changes;
* improvement actions.

Management identifies several priorities.

---

# 26. Management Decisions

Management approves:

* expansion of AI governance;
* improved phishing resistance;
* additional supplier monitoring;
* cloud security investment;
* automated evidence collection.

This demonstrates that management review drives real organizational decisions.

---

# 27. Step 14 – Surveillance Audit

The certification body conducts the surveillance audit.

The auditor reviews:

* ISMS operation;
* changes;
* risk assessments;
* controls;
* internal audit;
* management review;
* corrective actions.

The auditor selects samples from the current operating environment rather than relying only on evidence from the original certification audit.

---

# 28. Example Auditor Question

The auditor asks:

> "Your organization introduced an AI customer-service platform. How did this affect your ISMS?"

The GRC team demonstrates:

1. change assessment;
2. risk assessment;
3. control selection;
4. supplier assessment;
5. employee awareness;
6. monitoring;
7. management review.

This provides strong evidence of continual improvement.

---

# 29. Audit Traceability

The auditor traces the AI change through the ISMS.

```text id="ait9p4"
AI Platform Introduced
        |
        v
Change Assessment
        |
        v
Security Risk Identified
        |
        v
Risk Treatment
        |
        v
Controls Implemented
        |
        v
Evidence Generated
        |
        v
Monitoring
        |
        v
Internal Audit
        |
        v
Management Review
```

This demonstrates that the ISMS is functioning as a management system.

---

# 30. Surveillance Audit Result

The certification body identifies:

### Positive Observations

* strong risk management;
* effective management involvement;
* improved supplier monitoring;
* mature internal audit;
* good evidence traceability.

### Improvement Opportunity

AI governance processes should continue to mature.

### Minor Finding

One area of documentation requires improvement.

The organization remains certified subject to appropriate corrective action.

---

# 31. Response to the Finding

The organization performs:

### Root Cause Analysis

Why did the documentation gap occur?

### Correction

Update the affected documentation.

### Corrective Action

Improve the document-review workflow.

### Effectiveness Review

Test the process during the next review cycle.

This closes the loop.

---

# 32. Continual Improvement Model

The organization adopts a formal improvement cycle:

```text id="ci72kx"
PLAN
 |
 v
IMPLEMENT
 |
 v
MEASURE
 |
 v
AUDIT
 |
 v
IDENTIFY GAPS
 |
 v
CORRECT
 |
 v
IMPROVE
 |
 +-------> PLAN
```

The cycle continues throughout the certification period.

---

# 33. Moving Beyond Compliance

After certification, some organizations focus only on:

> "What will the auditor ask?"

IberiaCloud changes its approach.

The new question becomes:

> **"What information-security improvements does the business actually need?"**

This shifts the ISMS from an audit-driven program to a business-risk-driven program.

---

# 34. ISMS Continual Improvement Dashboard

The GRC team establishes a dashboard containing:

### Risk

* high risks;
* risks above appetite;
* risk trends.

### Controls

* control effectiveness;
* control failures;
* remediation.

### Compliance

* open findings;
* regulatory changes.

### Incidents

* incident volume;
* severity;
* response time;
* recurrence.

### Improvement

* corrective actions;
* overdue actions;
* effectiveness.

---

# 35. Example Improvement Metrics

| Metric                        | Previous | Current | Trend     |
| ----------------------------- | -------: | ------: | --------- |
| Critical supplier assessments |      93% |    100% | Improving |
| Privileged access reviews     |      94% |    100% | Improving |
| Critical patch SLA            |      96% |     98% | Improving |
| Security training             |    98.5% |   99.2% | Improving |
| Phishing incidents            |       29 |      37 | Worsening |

The dashboard reveals an important point:

Not every metric improves simultaneously.

---

# 36. Risk-Based Interpretation

The increase in phishing incidents does not automatically mean that the entire ISMS is failing.

The organization examines:

* attack volume;
* detection capability;
* employee reporting;
* successful compromise;
* response time;
* business impact.

For example, phishing reports may increase because employees are becoming better at detecting and reporting suspicious messages.

Therefore:

**Metric movement must be interpreted in context.**

---

# 37. Continual Improvement Example

The organization observes:

**Phishing reports ↑**

but:

**Successful phishing compromises ↓**

This may indicate that security awareness and technical controls are becoming more effective despite increased attack attempts.

This is why mature GRC analysis looks beyond single metrics.

---

# 38. Post-Surveillance Improvement Program

Following the audit, IberiaCloud establishes five priorities:

### Priority 1

Strengthen AI security governance.

### Priority 2

Increase phishing resistance.

### Priority 3

Automate supplier monitoring.

### Priority 4

Improve evidence automation.

### Priority 5

Expand continuous control monitoring.

---

# 39. GRC Automation Opportunity

The organization decides to integrate its GRC platform with:

* identity systems;
* vulnerability management;
* SIEM;
* cloud platforms;
* supplier management;
* ticketing systems.

The objective is to reduce manual evidence collection.

For example:

```text id="g5q2az"
Security System
      |
      v
GRC Platform
      |
      v
Control Status
      |
      v
Risk Status
      |
      v
Dashboard
      |
      v
Management Decision
```

---

# 40. Three Levels of ISMS Maturity

The organization identifies three stages.

### Stage 1 – Certification Driven

Focus:

> "Pass the audit."

### Stage 2 – Compliance Driven

Focus:

> "Maintain conformity."

### Stage 3 – Risk and Business Driven

Focus:

> "Use the ISMS to improve business resilience and manage information-security risk."

IberiaCloud's objective is to operate at Stage 3.

---

# 41. Lessons Learned

## Lesson 1 – Certification Does Not Mean Completion

An ISMS must continue operating and improving.

## Lesson 2 – Changes Must Trigger Risk Review

Technology, suppliers, acquisitions, and regulations can change the risk environment.

## Lesson 3 – Internal Audit Is a Continuous Assurance Mechanism

It should identify weaknesses before they become external audit problems.

## Lesson 4 – Corrective Actions Must Be Tested

Closing an action is not the same as proving effectiveness.

---

# 42. Additional Lessons

## Lesson 5 – Metrics Need Context

A metric increasing is not automatically bad.

## Lesson 6 – Management Review Must Drive Decisions

The review should result in meaningful actions.

## Lesson 7 – Evidence Should Be Continuous

Evidence should naturally emerge from operational processes.

## Lesson 8 – Continual Improvement Is a Strategic Capability

The ISMS should evolve with the organization's:

* business;
* technology;
* threats;
* suppliers;
* regulations.

---

# 43. Practical Surveillance Audit Checklist

### ISMS

* [ ] Scope remains appropriate
* [ ] Context reviewed
* [ ] Interested parties reviewed
* [ ] Policy remains current
* [ ] Objectives reviewed

### Risk

* [ ] Risk register updated
* [ ] New risks assessed
* [ ] Risk treatment current
* [ ] Risk acceptance reviewed

### Controls

* [ ] Controls operating
* [ ] Control effectiveness assessed
* [ ] Evidence available
* [ ] Exceptions documented

### Operations

* [ ] Incidents reviewed
* [ ] Supplier security reviewed
* [ ] Access management reviewed
* [ ] Vulnerability management reviewed
* [ ] Business continuity tested

### Assurance

* [ ] Internal audit completed
* [ ] Findings tracked
* [ ] Corrective actions verified
* [ ] Management review completed

### Surveillance

* [ ] Audit evidence organized
* [ ] Audit owners identified
* [ ] Recent changes documented
* [ ] Improvement actions documented
* [ ] Certification body requirements confirmed

---

# 44. Final ISO 27001 Continual Improvement Model

```text id="isoc7m"
              ISO 27001 CERTIFICATION
                       |
                       v
                 ISMS OPERATION
                       |
                       v
                 RISK MONITORING
                       |
                       v
                 CONTROL REVIEW
                       |
                       v
                 INTERNAL AUDIT
                       |
                       v
                MANAGEMENT REVIEW
                       |
                       v
                CORRECTIVE ACTION
                       |
                       v
              SURVEILLANCE AUDIT
                       |
                       v
              CONTINUAL IMPROVEMENT
                       |
                       v
                BUSINESS ALIGNMENT
                       |
                       +-----------↺
```

# 45. Case Study Conclusion

The IberiaCloud case demonstrates the transition from **ISO 27001 implementation to sustainable ISMS management**.

The organization learns that certification creates an ongoing obligation to maintain a functioning management system.

The mature lifecycle becomes:

**Implement → Operate → Monitor → Audit → Review → Improve → Reassess**

The most important lesson is:

> **An effective ISMS is not measured by whether the organization passed its last certification audit. It is measured by whether the organization continues to understand and manage information-security risk as its business environment changes.**

For a GRC professional, surveillance and continual improvement require the ability to connect:

**Business Change → Risk → Control → Evidence → Assurance → Management Decision → Improvement**

This is what transforms ISO 27001 from a certification project into a **living information-security governance system**.

# 19.5 ISO 27001 Implementation Case Studies

## Part 4 – ISO 27001 Nonconformity, Corrective Action and Improvement Case Study

## 1. Case Study Overview

This case study examines a more challenging ISO 27001 scenario.

**IberiaCloud Digital Services** has maintained its ISO 27001 certification for two years. During a surveillance audit, the certification auditor identifies several weaknesses in the organization's Information Security Management System (ISMS).

The organization must determine:

* what constitutes a nonconformity;
* how serious the issue is;
* what caused it;
* what immediate correction is required;
* what corrective action is necessary;
* how effectiveness will be verified;
* how the issue should be reported to management;
* how the ISMS should be improved to prevent recurrence.

The case demonstrates the difference between **fixing a problem** and **correcting the underlying cause**.

---

# 2. Organization Profile

### Company

**IberiaCloud Digital Services**

### Industry

Cloud, Telecommunications and Digital Services

### Employees

Approximately 1,800

### ISMS Scope

Cloud and managed digital services supporting operations in Spain, Portugal and selected shared-service functions.

### Certification Status

ISO 27001 certified for two years.

---

# 3. The Audit Finding

During surveillance, the certification auditor samples privileged-access reviews.

The organization requires privileged access to be reviewed periodically.

The auditor selects 30 privileged accounts.

The results show:

* 24 reviews completed on time;
* 4 reviews completed late;
* 2 reviews had no documented evidence.

The auditor raises a nonconformity because the organization cannot consistently demonstrate that the defined process is operating as intended.

---

# 4. Why the Finding Matters

At first, the IT manager responds:

> "The accounts were reviewed. We simply didn't keep all the evidence."

The GRC manager challenges this explanation.

There are actually two different issues:

### Operational Issue

Some reviews were completed late.

### Evidence Issue

Two reviews cannot be demonstrated through reliable records.

The organization therefore investigates whether the problem is isolated or systemic.

---

# 5. Initial Response

The CISO establishes a corrective-action team consisting of:

* GRC Manager;
* IAM Manager;
* IT Operations Manager;
* Internal Audit;
* Risk Manager.

The team is instructed not to immediately close the issue.

The first objective is to understand:

> **What actually happened?**

---

# 6. Nonconformity Lifecycle

```text id="ncf8q2"
Nonconformity Identified
          |
          v
Immediate Correction
          |
          v
Impact Assessment
          |
          v
Root Cause Analysis
          |
          v
Corrective Action
          |
          v
Implementation
          |
          v
Effectiveness Verification
          |
          v
Closure
          |
          v
Continual Improvement
```

---

# 7. Step 1 – Containment

The organization immediately performs an additional review of all privileged accounts.

The review identifies:

* 212 privileged accounts;
* 6 accounts requiring adjustment;
* 1 inactive account that should have been removed.

The inactive account is immediately disabled.

This is **correction**.

However, correction alone does not address why the account remained active.

---

# 8. Correction vs Corrective Action

This distinction is fundamental.

### Correction

Fix the immediate problem.

Example:

> Disable the inactive privileged account.

### Corrective Action

Address the underlying cause.

Example:

> Redesign the privileged-access review workflow so inactive accounts cannot remain unreviewed.

Therefore:

**Correction fixes the symptom.**

**Corrective action addresses the cause.**

---

# 9. Step 2 – Determine the Extent of the Problem

The team expands testing.

Instead of examining only the 30 sampled accounts, it reviews all privileged accounts.

The results show:

| Result                            | Accounts |
| --------------------------------- | -------: |
| Review completed on time          |      198 |
| Review completed late             |       10 |
| Evidence incomplete               |        3 |
| Unauthorized/inappropriate access |        1 |

The issue is therefore larger than the original audit sample.

---

# 10. Step 3 – Assess Security Impact

The GRC team evaluates whether the weakness created an actual security risk.

The inactive account had:

* privileged permissions;
* no recent activity;
* no active business requirement.

Although there is no evidence of misuse, the account represents a significant access-control exposure.

The risk is formally recorded.

---

# 11. Risk Assessment

### Risk

Unauthorized use of inactive privileged credentials.

### Threat

Compromise or misuse of an inactive privileged account.

### Vulnerability

Failure to consistently identify and remove inactive privileged accounts.

### Impact

High.

### Likelihood

Medium.

### Risk Rating

High.

The risk owner is the IAM Manager.

---

# 12. Step 4 – Root Cause Analysis

The organization conducts a root-cause analysis.

The team asks:

> Why was the inactive account not removed?

### Why 1

It was not identified during the review.

### Why 2

The review relied on a manually generated account list.

### Why 3

The account inventory was not automatically synchronized with the identity platform.

### Why 4

The IAM process had been designed before the current identity architecture.

### Why 5

The process had not been reassessed following the identity-system migration.

The root cause is therefore broader than:

> "The reviewer made a mistake."

---

# 13. Root Cause

The primary root cause is determined to be:

> **The privileged-access review process was not redesigned following a major identity-management architecture change, resulting in reliance on incomplete manually generated access data.**

This is a systemic process problem.

---

# 14. Root Cause Categories

The team classifies contributing causes:

### People

Reviewer responsibilities were not sufficiently clear.

### Process

The access-review process had not been updated.

### Technology

The GRC platform was not integrated with the identity platform.

### Governance

The process-change trigger was insufficient.

### Evidence

Review records were inconsistently retained.

---

# 15. Step 5 – Corrective Action Plan

The organization develops a multi-part corrective action.

### Action 1

Integrate the GRC platform with the identity-management system.

### Action 2

Automate privileged-account population reports.

### Action 3

Define mandatory reviewer responsibilities.

### Action 4

Implement escalation for overdue reviews.

### Action 5

Update the access-review procedure.

### Action 6

Train control owners.

### Action 7

Introduce effectiveness testing.

---

# 16. Corrective Action Ownership

| Action                | Owner                | Target   |
| --------------------- | -------------------- | -------- |
| GRC-IAM integration   | IAM Manager          | 90 days  |
| Automated reporting   | Security Engineering | 60 days  |
| Reviewer RACI         | GRC Manager          | 30 days  |
| Escalation workflow   | IAM Manager          | 45 days  |
| Procedure update      | GRC                  | 30 days  |
| Training              | Security Awareness   | 45 days  |
| Effectiveness testing | Internal Audit       | 120 days |

Each action has:

* owner;
* target date;
* expected result;
* evidence requirement.

---

# 17. Step 6 – Update the Risk Register

The risk register is updated.

The organization documents:

* original risk;
* existing controls;
* identified weakness;
* corrective actions;
* residual risk;
* risk owner;
* treatment status.

This ensures that the audit finding is not disconnected from enterprise risk management.

---

# 18. Step 7 – Update the Statement of Applicability

The organization determines whether the finding affects the Statement of Applicability.

The relevant access-control measures remain applicable.

However, the implementation status and supporting evidence are reviewed.

If the control remains applicable, the organization does not artificially change the applicability decision merely because the control had a weakness.

Instead, the organization improves implementation and effectiveness.

---

# 19. Step 8 – Update Procedures

The access-review procedure is revised.

The new process includes:

1. automated account population;
2. account-owner identification;
3. reviewer assignment;
4. risk-based prioritization;
5. review completion;
6. exception documentation;
7. remediation;
8. approval;
9. evidence retention;
10. escalation.

The process becomes more controlled and auditable.

---

# 20. Step 9 – Automate the Control

The organization implements a workflow:

```text id="aut4x8"
Identity Platform
       |
       v
Privileged Account Inventory
       |
       v
GRC Workflow
       |
       v
Assigned Reviewer
       |
       v
Access Decision
       |
   +---+---+
   |       |
Approve  Remove
   |       |
   +---+---+
       |
       v
Evidence Repository
       |
       v
Dashboard
```

Automation reduces dependence on manual spreadsheets.

---

# 21. Step 10 – Establish Escalation

The new workflow includes escalation.

### Day 0

Review assigned.

### Day 15

Reminder.

### Day 25

Manager escalation.

### Day 30

Security management escalation.

### Beyond deadline

Risk exception and formal management escalation.

This prevents overdue reviews from remaining invisible.

---

# 22. Step 11 – Evidence Requirements

The organization defines minimum evidence requirements.

Each review must demonstrate:

* account population;
* date;
* reviewer;
* access decision;
* exceptions;
* remediation;
* approval.

A simple screenshot is no longer sufficient.

---

# 23. Step 12 – Effectiveness Testing

After implementation, Internal Audit performs an effectiveness test.

The audit samples:

**50 privileged accounts**

Results:

* 50 correctly identified;
* 50 reviewed;
* 50 decisions documented;
* 3 inappropriate permissions identified;
* 3 remediation actions completed.

The automated workflow successfully identifies the population.

---

# 24. Effectiveness Result

The corrective action is considered effective because:

* the root cause was addressed;
* the process was redesigned;
* automation was introduced;
* evidence improved;
* the control operated consistently;
* exceptions were detected and remediated.

The corrective action can now move toward closure.

---

# 25. Step 13 – Certification Body Follow-Up

The organization submits evidence to the certification body.

The evidence includes:

* root-cause analysis;
* corrective-action plan;
* updated procedure;
* workflow configuration;
* training records;
* review records;
* effectiveness testing.

The certification body evaluates whether the response is adequate.

---

# 26. Auditor Perspective

The auditor is less interested in hearing:

> "We reminded employees to perform the review."

The auditor wants evidence that the organization has addressed the systemic cause.

A stronger response is:

> "We redesigned the process, automated the population, assigned ownership, introduced escalation, and verified effectiveness."

This demonstrates sustainable corrective action.

---

# 27. Step 14 – Management Review

The finding is presented to senior management.

Management reviews:

* root cause;
* risk impact;
* corrective actions;
* resource requirements;
* effectiveness results.

Management approves additional investment in GRC automation.

This turns an audit finding into an improvement opportunity.

---

# 28. From Finding to Improvement

The organization realizes that the same principle applies to other controls.

The CISO asks:

> "If privileged-access evidence is dependent on manual data extraction, what other controls have the same weakness?"

The GRC team launches a broader review.

---

# 29. Control Automation Review

The team identifies other manual processes:

* supplier assessments;
* vulnerability evidence;
* security training;
* policy attestations;
* risk reviews.

Several can be automated.

The organization therefore expands the corrective-action initiative into a broader **continuous-control-monitoring program**.

---

# 30. Improvement Opportunity

The original audit finding was:

**Privileged-access review weakness**

The resulting improvement becomes:

**Enterprise control automation and continuous monitoring**

This illustrates an important GRC principle:

> **A mature organization uses audit findings to identify broader opportunities for improving the control environment.**

---

# 31. Three Levels of Response

The organization now distinguishes three levels:

### Level 1 – Correction

Fix the immediate problem.

### Level 2 – Corrective Action

Prevent recurrence of the same problem.

### Level 3 – Improvement

Identify whether the same weakness exists elsewhere.

```text id="lv3xq7"
Problem
   |
   v
Correction
   |
   v
Corrective Action
   |
   v
Effectiveness
   |
   v
Broader Improvement
```

---

# 32. Lessons Learned

## Lesson 1 – Do Not Blame Individuals Too Quickly

A repeated failure may indicate a process or governance problem.

## Lesson 2 – Determine the Extent

A single audit sample may represent a larger systemic issue.

## Lesson 3 – Root Cause Matters

Corrective action should address why the problem occurred.

## Lesson 4 – Evidence Is Critical

The organization must demonstrate that corrective actions were implemented.

---

# 33. Additional Lessons

## Lesson 5 – Effectiveness Must Be Tested

A completed action is not automatically an effective action.

## Lesson 6 – Integrate Findings With Risk Management

Audit findings can represent information-security risks.

## Lesson 7 – Use Technology Where Appropriate

Automation can improve consistency, timeliness, and evidence quality.

## Lesson 8 – Escalation Creates Accountability

Overdue actions should not disappear into spreadsheets.

---

# 34. Practical Nonconformity Response Checklist

### Identification

* [ ] Finding documented
* [ ] Requirement identified
* [ ] Evidence preserved
* [ ] Immediate impact assessed

### Correction

* [ ] Immediate problem fixed
* [ ] Security exposure contained
* [ ] Affected systems reviewed

### Root Cause

* [ ] Root cause identified
* [ ] Contributing factors identified
* [ ] Extent of issue assessed

### Corrective Action

* [ ] Action plan established
* [ ] Owners assigned
* [ ] Target dates established
* [ ] Resources allocated

### Verification

* [ ] Corrective action implemented
* [ ] Evidence collected
* [ ] Effectiveness tested
* [ ] Recurrence evaluated

### Closure

* [ ] Finding formally closed
* [ ] Risk register updated
* [ ] Procedures updated
* [ ] Lessons learned documented

### Improvement

* [ ] Similar controls reviewed
* [ ] Automation opportunities considered
* [ ] Management informed

---

# 35. GRC Corrective Action Dashboard

The GRC team creates a dashboard:

| Finding               | Owner       | Due    | Status      | Effectiveness |
| --------------------- | ----------- | ------ | ----------- | ------------- |
| Privileged access     | IAM         | 30 Jun | Closed      | Effective     |
| Supplier reassessment | Procurement | 15 Jul | Open        | Pending       |
| AI risk assessment    | CISO        | 30 Jul | In Progress | Pending       |
| DR testing            | IT          | 15 Aug | Open        | Pending       |

This gives management visibility into the entire corrective-action portfolio.

---

# 36. Corrective Action Risk Prioritization

Not every finding requires the same urgency.

The organization prioritizes based on:

**Impact × Likelihood × Control Criticality**

A weakness affecting:

* privileged accounts;
* critical infrastructure;
* regulated information;
* customer data

receives higher priority than a minor documentation issue.

---

# 37. Executive Reporting

The CISO reports:

### Open Findings

7

### High-Risk Findings

1

### Medium-Risk Findings

4

### Low-Risk Findings

2

### Overdue Actions

1

### Corrective Actions Verified Effective

83%

The executive committee can therefore focus on the most important weaknesses.

---

# 38. Integration With Enterprise GRC

The organization integrates audit findings with its broader GRC environment.

```text id="egrc9m"
Audit Finding
      |
      v
GRC Platform
      |
 +----+----+----+
 |         |    |
Risk    Control Action
 |         |    |
 +----+----+----+
      |
      v
Management Dashboard
      |
      v
Executive Decision
```

This prevents audit findings from becoming isolated spreadsheets.

---

# 39. Long-Term Improvement

After the corrective-action program, IberiaCloud achieves:

* automated privileged-access reviews;
* stronger evidence;
* better accountability;
* faster remediation;
* improved risk visibility;
* reduced manual work;
* stronger audit readiness.

The organization also applies the same methodology to other control areas.

---

# 40. Final Case Study Model

```text id="fcm6t1"
             AUDIT FINDING
                   |
                   v
             IMMEDIATE FIX
                   |
                   v
             IMPACT REVIEW
                   |
                   v
            ROOT CAUSE ANALYSIS
                   |
                   v
            CORRECTIVE ACTION
                   |
                   v
              IMPLEMENT
                   |
                   v
             COLLECT EVIDENCE
                   |
                   v
          EFFECTIVENESS TEST
                   |
             +-----+-----+
             |           |
          Effective   Ineffective
             |           |
             |           v
             |      Reassess Cause
             |           |
             +-----------+
                   |
                   v
             CLOSE FINDING
                   |
                   v
          CONTINUAL IMPROVEMENT
```

# 41. Case Study Conclusion

The IberiaCloud case demonstrates how an ISO 27001 organization should respond when a certification or surveillance audit identifies a nonconformity.

The mature response is not:

**Finding → Fix → Close**

Instead, it is:

**Finding → Correction → Impact Assessment → Root Cause → Corrective Action → Implementation → Evidence → Effectiveness Testing → Closure → Improvement**

The distinction between **correction** and **corrective action** is particularly important for GRC professionals.

A correction addresses what happened.

A corrective action addresses **why it happened**.

An improvement asks:

> **"Where else could the same weakness exist?"**

That final question moves the organization beyond basic certification compliance toward a mature governance and assurance capability.

The ultimate objective is to create an ISMS in which audit findings become sources of organizational learning rather than recurring compliance problems.

