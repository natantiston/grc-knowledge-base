# 19.12 Third-Party Risk Management Case Studies

## Part 1 – Assessing a Critical Technology Supplier

Third-party risk management is the process of identifying, assessing, treating, monitoring, and governing risks introduced by external organizations.

Modern enterprises depend heavily on third parties for:

* Cloud services
* SaaS platforms
* Network services
* Managed security services
* Data processing
* Payment processing
* Telecommunications
* Software development
* IT infrastructure
* Business process outsourcing
* Professional services

A critical supplier failure can therefore become an **enterprise risk**, not merely a procurement problem.

The fundamental GRC principle is:

> **An organization can outsource a service, but it cannot outsource accountability for the risk.**

---

# Case Study: GlobalConnect Telecom

GlobalConnect Telecom is preparing to deploy a new cloud-based **Customer Experience and Digital Contact Centre Platform**.

The platform will support:

* Customer authentication
* Voice communications
* Customer records
* Contact-center operations
* Customer service tickets
* Call recordings
* Analytics
* AI-assisted customer interactions

The proposed supplier is:

**CloudContact Solutions**

The supplier will process significant amounts of customer information and will become operationally important to GlobalConnect.

The procurement team has already completed the commercial evaluation.

GRC must now determine:

> **Is CloudContact Solutions an acceptable third-party risk?**

---

# 1. Why the Supplier Is Considered Critical

The supplier is not simply providing office software.

If CloudContact becomes unavailable:

* Customer service may stop.
* Contact-center agents may lose access.
* Customer communications may be disrupted.
* Customer records may become inaccessible.
* Regulatory obligations could potentially be affected.
* Revenue may be impacted.
* Brand reputation may suffer.

The supplier is therefore classified as:

> **Critical Technology Supplier**

---

# 2. Third-Party Risk Is an Enterprise Risk

A common mistake is treating supplier risk as:

> "Procurement has selected the vendor."

Procurement primarily evaluates:

* Price
* Commercial terms
* Contract
* Delivery

GRC evaluates:

* Security
* Privacy
* Resilience
* Compliance
* Operational risk
* Concentration risk
* Supply-chain risk

The final decision must consider all of these dimensions.

---

# 3. Third-Party Risk Lifecycle

GlobalConnect uses:

**Identify**

↓

**Classify**

↓

**Due Diligence**

↓

**Assess Risk**

↓

**Treat Risk**

↓

**Contract**

↓

**Onboard**

↓

**Monitor**

↓

**Reassess**

↓

**Offboard**

This lifecycle applies throughout the supplier relationship.

---

# 4. Step 1 – Identify the Supplier

The first step is to understand:

* Who is the supplier?
* What services will it provide?
* Which business units use it?
* What data will it access?
* What systems will it connect to?
* Where is it located?
* Which subcontractors does it use?

GRC should not begin with a generic questionnaire.

It should begin with:

> **Understanding the actual service relationship.**

---

# 5. Step 2 – Identify the Service

The proposed service is:

**Cloud-based customer contact-center platform**

The service includes:

* SaaS application
* Cloud infrastructure
* Customer data processing
* Voice communications
* AI functionality
* API integration

This already indicates several risk categories.

---

# 6. Step 3 – Identify Data

The supplier may process:

* Customer names
* Telephone numbers
* Account information
* Service information
* Call recordings
* Support tickets
* Authentication information
* Potentially sensitive customer information

The organization must determine:

> **What data is entering the supplier environment?**

---

# 7. Data Classification

GlobalConnect classifies the data.

Example:

| Data                       | Classification      |
| -------------------------- | ------------------- |
| Public marketing data      | Public              |
| Internal procedures        | Internal            |
| Customer account data      | Confidential        |
| Call recordings            | Highly Confidential |
| Authentication information | Restricted          |

The supplier's security requirements must reflect the highest relevant classification.

---

# 8. Step 4 – Determine System Access

GRC determines what access the supplier requires.

For example:

### Application Access

Yes

### Customer Database

Limited/API access

### Network Access

Controlled

### Administrative Access

Limited

### Production Access

Potentially required

### Personal Data

Yes

The greater the access, the greater the inherent risk.

---

# 9. Step 5 – Determine Business Criticality

GlobalConnect classifies services.

### Tier 1 – Critical

Failure causes major business or regulatory impact.

### Tier 2 – High

Significant business impact.

### Tier 3 – Moderate

Manageable operational impact.

### Tier 4 – Low

Limited impact.

CloudContact is classified:

**Tier 1 – Critical**

---

# 10. Criticality Assessment

The GRC team evaluates:

### Availability

What happens if the supplier is unavailable?

### Confidentiality

What happens if customer data is exposed?

### Integrity

What happens if customer information is altered?

### Regulatory

What happens if compliance requirements are violated?

### Financial

What financial losses could occur?

### Reputation

What happens to customer trust?

The combined impact is:

**Very High**

---

# 11. Inherent Risk

Before considering supplier controls, GlobalConnect calculates the inherent risk.

Example:

| Risk Dimension          | Rating |
| ----------------------- | -----: |
| Data Sensitivity        |      5 |
| Business Criticality    |      5 |
| System Access           |      4 |
| Regulatory Exposure     |      5 |
| Availability Dependency |      5 |
| Geographic Exposure     |      3 |

Overall inherent risk:

**High / Very High**

This means enhanced due diligence is required.

---

# 12. Step 6 – Determine Applicable Regulations

Depending on the organization's jurisdiction and activities, requirements may arise from:

* Data protection laws
* Cybersecurity regulations
* Telecommunications regulations
* Digital resilience requirements
* Contractual obligations
* Industry standards

For example, the GRC team may need to assess requirements relating to:

* GDPR
* NIS2
* DORA where applicable
* National telecommunications requirements
* Customer contractual requirements

The exact obligations must be determined based on the organization's activities and jurisdictions.

---

# 13. Step 7 – Security Due Diligence

GlobalConnect sends a detailed security assessment.

Topics include:

### Governance

* Security policy
* Security organization
* Security responsibilities

### Access Control

* MFA
* Privileged access
* Joiner/mover/leaver processes

### Infrastructure

* Network security
* Segmentation
* Hardening

### Application Security

* Secure development
* Code review
* Vulnerability management

### Monitoring

* SIEM
* Logging
* SOC

### Incident Response

* Incident detection
* Notification
* Investigation

### Resilience

* Backup
* DR
* Business continuity

---

# 14. Step 8 – Request Independent Evidence

GRC should avoid relying exclusively on supplier self-attestation.

Evidence may include:

* ISO 27001 certificate
* SOC 2 report
* Penetration-test summary
* Business continuity test results
* Disaster recovery test results
* Security policies
* Data-flow diagrams
* Vulnerability-management evidence
* Privacy documentation

The principle is:

> **Trust, but verify.**

---

# 15. ISO 27001 Evidence

Suppose CloudContact provides:

**ISO 27001 certification**

This is useful evidence.

However:

> **ISO 27001 certification does not automatically mean the supplier is risk-free.**

GRC should still determine:

* Scope
* Certification dates
* Applicable locations
* Covered services
* Exclusions
* Certification body
* Relevant controls

The certificate must actually cover the service being purchased.

---

# 16. SOC 2 Evidence

Suppose the supplier provides a:

**SOC 2 Type II report**

This can provide evidence regarding controls operating over a defined period.

GRC should review:

* Scope
* Trust Service Criteria
* Testing period
* Exceptions
* Auditor conclusions
* Complementary user entity controls

The report should be analyzed rather than simply marked:

> "SOC 2 = Pass."

---

# 17. Penetration Testing

The supplier provides a penetration-test executive summary.

GRC identifies:

* 3 Critical findings
* 7 High findings
* 14 Medium findings

The supplier states:

> "All critical findings have been remediated."

GRC requests evidence.

---

# 18. Validate Remediation

The supplier provides:

* Remediation report
* Retest evidence
* Updated security configuration

GRC confirms:

**3/3 critical findings remediated.**

However:

**2/7 high findings remain open.**

These become part of the residual risk assessment.

---

# 19. Step 9 – Assess Privacy Risk

Because the supplier processes customer information, Privacy must participate.

The organization determines:

* Data controller/processor roles
* Processing purposes
* Data categories
* Retention
* Subprocessors
* International transfers
* Data-subject rights
* Breach notification responsibilities

A Data Processing Agreement may be required.

---

# 20. Data Location

The supplier states that customer data is stored in:

* Germany
* Netherlands
* United States

GRC and Privacy must determine whether this geographic architecture is acceptable.

Questions include:

* Where is production data stored?
* Where are backups stored?
* Where is support personnel located?
* Where are logs stored?
* Are international transfers involved?

---

# 21. Subcontractor Risk

CloudContact uses:

* AWS
* Twilio
* A call-recording provider
* An AI model provider
* A managed SOC provider

This means GlobalConnect is not really assessing only one organization.

It is assessing a:

> **Fourth-party ecosystem.**

---

# 22. Fourth-Party Risk

The organization should determine:

* Which subcontractors are critical?
* What data do they access?
* What services do they provide?
* Can they be replaced?
* How are they monitored?
* What happens if they fail?

This becomes increasingly important for cloud and SaaS services.

---

# 23. Concentration Risk

Suppose GlobalConnect already uses:

* AWS for cloud
* Microsoft for productivity
* CloudContact for customer service

CloudContact also relies heavily on AWS.

This creates concentration.

A single cloud outage could affect multiple critical services.

Therefore:

> **Supplier risk must consider dependencies across the entire technology ecosystem.**

---

# 24. Business Continuity Assessment

GRC requests the supplier's:

* BCP
* DR plan
* RTO
* RPO
* DR test results
* Recovery architecture
* Crisis-management process

CloudContact reports:

**RTO = 4 hours**

**RPO = 1 hour**

GlobalConnect's requirement is:

**RTO = 2 hours**

**RPO = 30 minutes**

There is therefore a resilience gap.

---

# 25. Supplier Recovery Gap

The assessment identifies:

| Requirement | GlobalConnect | Supplier | Gap |
| ----------- | ------------: | -------: | --: |
| RTO         |            2h |       4h |  2h |
| RPO         |           30m |       1h | 30m |

This is significant because the supplier's recovery capability does not meet the organization's business requirement.

---

# 26. Service-Level Agreement

The contract must address:

* Availability
* RTO
* RPO
* Incident notification
* Security obligations
* Data protection
* Audit rights
* Subcontractors
* Business continuity
* Disaster recovery

For example:

**Availability SLA: 99.95%**

But availability alone is insufficient.

A supplier could meet 99.95% availability while still failing a critical recovery requirement.

---

# 27. Security Incident Notification

The contract should define:

> How quickly must the supplier notify GlobalConnect?

Example:

**Initial notification within 4 hours of confirmed security incident.**

For critical incidents, GlobalConnect may negotiate a shorter requirement.

The contract should also specify:

* Notification channel
* Required information
* Update frequency
* Escalation contacts

---

# 28. Right to Audit

For critical suppliers, the organization may require:

* Audit rights
* Evidence requests
* Independent assurance reports
* Regulatory access
* Security assessments

This provides ongoing assurance.

---

# 29. Risk Scoring

GlobalConnect calculates:

### Inherent Risk

**Very High**

### Control Effectiveness

**Good**

### Residual Risk

**High**

The supplier therefore requires:

> **Enhanced monitoring and executive risk acceptance.**

---

# 30. Residual Risk

Residual risk is the risk remaining after controls are considered.

For example:

**Inherent Risk: Very High**

↓

Security controls

↓

Contractual controls

↓

DR controls

↓

Monitoring

↓

**Residual Risk: High**

GRC must determine whether this residual risk is:

* Acceptable
* Requires treatment
* Requires executive acceptance
* Requires supplier remediation
* Requires rejection of the supplier

---

# 31. Risk Treatment Options

There are four fundamental options.

### Avoid

Do not use the supplier.

### Reduce

Implement additional controls.

### Transfer

Use contractual/insurance mechanisms.

### Accept

Management formally accepts the residual risk.

For a critical supplier, acceptance should normally be performed by an appropriately authorized risk owner.

---

# 32. Example Treatment Plan

| Risk                  | Treatment                        | Owner       |
| --------------------- | -------------------------------- | ----------- |
| RTO gap               | Negotiate enhanced DR capability | CIO         |
| High pentest findings | Require remediation              | CISO        |
| Data-transfer risk    | Strengthen DPA                   | Privacy     |
| Concentration risk    | Develop alternate provider       | Procurement |
| Privileged access     | Require PAM/MFA                  | CISO        |

---

# 33. Risk Acceptance

Suppose the supplier cannot meet the required:

**2-hour RTO**

Management may decide:

> "The risk is temporarily accepted for six months while the supplier implements a new recovery architecture."

This should include:

* Named risk owner
* Expiration date
* Compensating controls
* Risk rationale
* Executive approval

Risk acceptance should not become:

> "We cannot fix it, so leave it."

---

# 34. Compensating Controls

Because the supplier cannot meet the required RTO, GlobalConnect introduces:

* Manual customer-service procedures
* Alternate communication channel
* Secondary customer-support platform
* Offline customer information
* Additional monitoring

These reduce the impact of supplier failure.

---

# 35. Third-Party Risk Register

The supplier is added to the GRC system.

Example:

| Field          | Value                  |
| -------------- | ---------------------- |
| Supplier       | CloudContact Solutions |
| Service        | Digital Contact Centre |
| Criticality    | Tier 1                 |
| Data           | Customer Data          |
| Inherent Risk  | Very High              |
| Residual Risk  | High                   |
| Risk Owner     | CIO                    |
| Business Owner | Customer Operations    |
| Assessment     | Annual                 |
| Next Review    | 12 months              |

---

# 36. Supplier Tiering

GlobalConnect maintains supplier categories.

### Tier 1

Critical suppliers.

Assessment:

**Enhanced**

### Tier 2

High-risk suppliers.

Assessment:

**Standard/Enhanced**

### Tier 3

Moderate suppliers.

Assessment:

**Standard**

### Tier 4

Low-risk suppliers.

Assessment:

**Light-touch**

This prevents the organization from spending the same effort on every supplier.

---

# 37. Critical Supplier Assessment

A Tier 1 supplier may require:

* Annual assessment
* Annual independent assurance
* Penetration testing evidence
* DR testing evidence
* Business continuity review
* Privacy review
* Subprocessor review
* Security incident monitoring
* Contract review
* Executive escalation for major findings

---

# 38. Supplier Onboarding Decision

The final decision is:

### Commercial

**Approved**

### Security

**Conditionally approved**

### Privacy

**Approved with DPA**

### Business Continuity

**Conditional – RTO gap**

### GRC

**High residual risk**

### Executive Decision

**Approve with risk treatment plan**

The supplier can therefore proceed, but under defined conditions.

---

# 39. Executive Summary

The GRC Manager provides executives with:

> **CloudContact Solutions is classified as a Tier 1 critical technology supplier because it supports customer-service operations and processes confidential customer information. Inherent risk is assessed as Very High. Security and privacy controls are generally strong; however, the supplier currently has an RTO of four hours against GlobalConnect's two-hour requirement, and two high-risk penetration-test findings remain open. Residual risk is therefore High. The recommendation is conditional approval subject to remediation, contractual commitments, compensating controls, and executive risk acceptance.**

This is much more useful than:

> "Vendor assessment completed."

---

# 40. Common Third-Party Risk Mistakes

### Mistake 1

Treating procurement approval as security approval.

### Mistake 2

Using the same questionnaire for every supplier.

### Mistake 3

Accepting certificates without reviewing scope.

### Mistake 4

Ignoring subcontractors.

### Mistake 5

Ignoring data location.

### Mistake 6

Failing to assess business criticality.

### Mistake 7

Ignoring supplier concentration risk.

### Mistake 8

Not reviewing DR capability.

### Mistake 9

Accepting open critical vulnerabilities without formal risk treatment.

### Mistake 10

Assessing the supplier once and never monitoring it again.

---

# 41. GRC Professional Perspective

A mature GRC professional does not ask only:

> **"Is this supplier secure?"**

Instead, the questions are:

### Business

> How important is the service?

### Data

> What information does the supplier handle?

### Technology

> What systems can the supplier access?

### Security

> What controls protect the environment?

### Resilience

> Can the supplier recover within our requirements?

### Compliance

> What laws and regulations apply?

### Supply Chain

> Who does the supplier depend on?

### Risk

> What residual risk remains?

### Governance

> Who accepts that risk?

---

# 42. End-to-End Assessment Model

The complete assessment can be represented as:

**Supplier Identification**

↓

**Business Service Mapping**

↓

**Criticality Classification**

↓

**Data Classification**

↓

**Access Assessment**

↓

**Regulatory Assessment**

↓

**Security Due Diligence**

↓

**Privacy Assessment**

↓

**BC/DR Assessment**

↓

**Subcontractor Assessment**

↓

**Concentration Risk**

↓

**Control Evaluation**

↓

**Inherent Risk**

↓

**Residual Risk**

↓

**Risk Treatment**

↓

**Contractual Requirements**

↓

**Approval**

↓

**Continuous Monitoring**

---

# 43. Practical GRC Exercise

You are the GRC Manager.

A proposed cloud supplier provides a **critical customer platform**.

The assessment produces:

* Business criticality: **5/5**
* Data sensitivity: **5/5**
* Regulatory exposure: **4/5**
* System access: **4/5**
* Availability dependency: **5/5**
* ISO 27001: **Yes**
* SOC 2 Type II: **Yes**
* Critical penetration findings: **0**
* High penetration findings: **3**
* Supplier RTO: **8 hours**
* Required RTO: **4 hours**
* Supplier RPO: **4 hours**
* Required RPO: **1 hour**
* Critical subcontractors: **3**
* Tested subcontractors: **2**
* Residual risk: **High**

Your task is to determine:

1. Should the supplier be approved?
2. Should approval be unconditional or conditional?
3. What are the top five risks?
4. What contractual requirements should be included?
5. What compensating controls should be implemented?
6. Who should accept the residual risk?
7. How frequently should the supplier be reassessed?
8. What evidence should be monitored continuously?

---

# 44. Key GRC Lesson

The most important lesson from this case study is:

> **Third-party risk management is not a questionnaire exercise. It is an ongoing risk-management process tied to business criticality, data, security, resilience, compliance, contracts, and executive accountability.**

A supplier with an excellent security certification can still be unacceptable if:

* Its RTO is inadequate.
* Its subcontractors create unacceptable risk.
* Its data-processing model violates requirements.
* Its concentration risk is excessive.
* Its security findings remain unresolved.
* Its contractual protections are inadequate.

The ultimate GRC question is:

> **"If this supplier fails, is breached, becomes unavailable, or violates its obligations, can our organization continue operating within its risk appetite and regulatory requirements?"**

If the answer is **yes**, the supplier may be acceptable with appropriate controls.

If the answer is **no**, the organization must **reduce, transfer, avoid, or formally accept the risk** before proceeding.



