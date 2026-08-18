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

# 19.12 Third-Party Risk Management Case Studies

## Part 2 – Conducting Third-Party Security Due Diligence

Third-party security due diligence is the process of determining whether a supplier has sufficient security capabilities, controls, governance, and resilience to protect the organization's information and services.

The objective is **not** to prove that a supplier has zero risk.

The objective is to determine:

> **Whether the supplier's security risk is understood, controlled, contractually governed, monitored, and acceptable to the organization.**

The process is:

**Supplier → Service → Data → Access → Threats → Controls → Evidence → Risk → Treatment → Approval → Monitoring**

---

# Case Study: GlobalConnect Telecom

GlobalConnect is preparing to onboard **SecureCloud Managed Services**, a managed security and cloud operations provider.

SecureCloud will provide:

* Cloud infrastructure management
* Security monitoring
* Vulnerability management
* Endpoint management
* Privileged administration
* Incident-response support

The supplier will have **privileged access to GlobalConnect's production environment**.

This creates a significantly higher security risk than a normal SaaS supplier.

---

# 1. Why Due Diligence Is Necessary

GlobalConnect's internal security controls may be strong, but SecureCloud introduces additional attack paths.

A compromise of SecureCloud could potentially provide attackers with:

* Administrative access
* Network access
* Cloud access
* Security-tool access
* Customer information
* Production systems

Therefore:

> **The supplier becomes part of GlobalConnect's attack surface.**

---

# 2. Security Due Diligence vs Vendor Questionnaire

A questionnaire is only one component of due diligence.

Weak approach:

> Send questionnaire → Receive answers → Mark supplier "compliant."

Mature approach:

> Understand service → Identify risks → Request evidence → Validate controls → Assess gaps → Determine residual risk → Define treatment → Approve → Monitor.

The difference is **evidence and risk judgment**.

---

# 3. Step 1 – Understand the Service

Before asking security questions, GRC documents:

### Service

Managed cloud and security operations.

### Business Owner

Chief Information Officer.

### Technical Owner

Cloud Infrastructure Director.

### Security Owner

Chief Information Security Officer.

### Supplier

SecureCloud Managed Services.

### Criticality

Tier 1.

---

# 4. Step 2 – Understand the Data

The supplier may access:

* Infrastructure logs
* Security alerts
* User identities
* IP addresses
* Configuration information
* Security events
* Customer systems
* Potentially personal data

Some information may be highly sensitive.

Therefore:

**Data Classification = Confidential / Restricted**

---

# 5. Step 3 – Understand Supplier Access

The most important question is:

> **What can the supplier actually access?**

SecureCloud requires:

* VPN access
* Privileged accounts
* Cloud administration
* Security-platform administration
* Remote support
* Emergency access

This significantly increases inherent risk.

---

# 6. Privileged Access Risk

A compromised supplier administrator could potentially:

* Disable security controls
* Modify firewall rules
* Access production systems
* Delete logs
* Create accounts
* Exfiltrate data
* Disable backups

Therefore, privileged supplier access must be treated as a high-risk control area.

---

# 7. Step 4 – Map the Supplier Attack Surface

GRC works with Security Architecture to create a simplified access map:

**SecureCloud**

↓

VPN

↓

Privileged Access Management

↓

Cloud Management Platform

↓

Production Systems

↓

Security Tools

↓

Critical Business Services

This shows where supplier compromise could affect the enterprise.

---

# 8. Step 5 – Establish Due Diligence Requirements

Because this is a Tier 1 supplier, GlobalConnect requires enhanced due diligence.

Evidence requirements include:

* ISO 27001 certificate
* SOC 2 Type II report
* Penetration-test summary
* Vulnerability-management process
* Access-control policy
* PAM architecture
* MFA evidence
* Security monitoring
* Incident-response plan
* Business continuity plan
* DR test results
* Data-protection documentation
* Subprocessor list

---

# 9. Step 6 – Review Security Certifications

SecureCloud provides:

**ISO 27001 certification**

GRC does not immediately mark the supplier:

**"Secure."**

Instead, it asks:

* What is the certification scope?
* Does it include managed services?
* Does it cover the relevant data center?
* Is the certificate current?
* Who issued it?
* When does it expire?
* Were exclusions identified?

---

# 10. Scope Matters

Suppose the certificate states:

> "Information security management for corporate administrative functions."

But SecureCloud's managed cloud service is outside the scope.

Then the certificate provides limited assurance for GlobalConnect's actual service.

Therefore:

> **Certification scope must match the service being assessed.**

---

# 11. SOC 2 Review

SecureCloud provides a SOC 2 Type II report.

GRC reviews:

* Reporting period
* Scope
* Systems covered
* Controls tested
* Exceptions
* Auditor opinion
* Complementary customer controls

The review identifies:

**2 control exceptions**

These must be assessed for relevance.

---

# 12. Control Exception Assessment

The supplier's SOC 2 report identifies:

> Quarterly privileged-access reviews were not completed on time for two quarters.

GlobalConnect determines:

* The issue is relevant.
* Privileged access is critical.
* The supplier has remediated the process.
* Evidence of the new process is available.

Risk:

**Medium/High**

depending on the environment and access level.

---

# 13. Step 7 – Security Questionnaire

GlobalConnect uses a structured questionnaire.

Typical sections include:

### Governance

* Security policies
* Security organization
* Security responsibilities

### Identity

* MFA
* PAM
* Access reviews

### Infrastructure

* Network segmentation
* Hardening
* Encryption

### Application Security

* Secure SDLC
* Code review
* Vulnerability management

### Monitoring

* SIEM
* SOC
* Logging

### Incident Response

* Detection
* Escalation
* Forensics

### Resilience

* BCP
* DR
* Backup

---

# 14. Avoid Checkbox Compliance

Suppose the questionnaire asks:

> "Do you use MFA?"

Supplier answer:

**Yes.**

That is not enough.

GRC should determine:

* Which systems?
* Which users?
* Which privileged accounts?
* Which authentication mechanism?
* Are emergency accounts included?
* Are service accounts excluded?
* Are exceptions monitored?

The quality of due diligence depends on the quality of follow-up questions.

---

# 15. Step 8 – Identity and Access Management

GlobalConnect evaluates:

### Joiner

How are new supplier employees granted access?

### Mover

How is access changed when responsibilities change?

### Leaver

How quickly is access removed?

For privileged access:

* MFA
* PAM
* Session recording
* Approval workflow
* Time-limited access

should be evaluated.

---

# 16. Privileged Access Management

A mature model is:

**Request**

↓

**Approval**

↓

**Temporary Privilege**

↓

**Perform Activity**

↓

**Session Recording**

↓

**Automatic Expiration**

This is preferable to:

> Permanent supplier administrator account.

---

# 17. Emergency Access

The supplier may need emergency access during a major incident.

GlobalConnect should define:

* Who can approve emergency access?
* How long does it remain active?
* Is it monitored?
* Is it recorded?
* Is it reviewed afterward?

Emergency access should not become a permanent backdoor.

---

# 18. Step 9 – Network Security

Due diligence evaluates:

* Network segmentation
* VPN security
* Firewall controls
* Zero Trust principles
* Administrative networks
* Remote access
* IP restrictions

A supplier should not receive unrestricted access to the enterprise.

---

# 19. Zero Trust Principle

A useful principle is:

> **Never assume supplier access is trusted simply because the supplier is approved.**

Access should be:

* Explicitly authorized
* Limited
* Authenticated
* Monitored
* Continuously evaluated

---

# 20. Step 10 – Encryption

GRC verifies:

### Data in Transit

TLS or equivalent protection.

### Data at Rest

Strong encryption.

### Key Management

Who controls encryption keys?

### Backup Encryption

Are backups also protected?

### Key Rotation

How frequently are keys rotated?

The question is not merely:

> "Is data encrypted?"

It is:

> **"How is encryption implemented and governed?"**

---

# 21. Step 11 – Logging and Monitoring

GlobalConnect requires:

* Authentication logs
* Privileged activity logs
* Administrative changes
* Security events
* API activity

Logs should be:

* Protected
* Retained
* Monitored
* Available for investigation

Supplier activity should ideally be integrated into GlobalConnect's monitoring capability.

---

# 22. Step 12 – Incident Response

GRC evaluates the supplier's ability to respond to incidents.

Questions include:

* How are incidents detected?
* Who investigates?
* How quickly are customers notified?
* Who makes notification decisions?
* Is forensic support available?
* Are incident exercises performed?

---

# 23. Incident Notification Requirement

GlobalConnect contractually requires:

**Critical security incident notification ≤ 4 hours**

The supplier's existing policy states:

**Notification within 24 hours**

This is a contractual and operational gap.

The supplier must either:

* Improve the process
* Provide a contractual commitment
* Provide compensating controls
* Or be rejected/conditionally approved

---

# 24. Step 13 – Vulnerability Management

GRC evaluates:

* Vulnerability scanning
* Patch management
* Critical patch timelines
* Risk acceptance
* Exception management

Example requirements:

| Severity | Required Remediation |
| -------- | -------------------: |
| Critical |            ≤ 15 days |
| High     |            ≤ 30 days |
| Medium   |            ≤ 60 days |
| Low      |           Risk-based |

Actual requirements should reflect the organization's risk appetite and contract.

---

# 25. Step 14 – Penetration Testing

SecureCloud provides an annual penetration-test report.

Findings:

* Critical: 0
* High: 2
* Medium: 9
* Low: 17

GRC does not automatically reject the supplier.

It evaluates:

* What systems were tested?
* Were production systems included?
* How old is the test?
* Are findings relevant?
* Are high findings remediated?
* Has retesting occurred?

---

# 26. Step 15 – Software Security

If SecureCloud develops software or automation, GRC assesses:

* Secure SDLC
* Code review
* SAST
* DAST
* Dependency scanning
* Secrets management
* CI/CD security
* Open-source component management

This is especially important when supplier-developed software enters production.

---

# 27. Step 16 – Endpoint Security

Supplier administrators may use their own devices to access GlobalConnect.

GRC therefore assesses:

* Endpoint detection
* Antivirus/EDR
* Encryption
* Patch management
* Device management
* USB restrictions
* Security configuration

A compromised supplier laptop could become a path into the enterprise.

---

# 28. Step 17 – Personnel Security

Due diligence should consider:

* Background screening
* Security awareness
* Privileged-user training
* Confidentiality agreements
* Insider-threat controls
* Employee termination procedures

This is particularly important for personnel with privileged access.

---

# 29. Step 18 – Physical Security

For critical suppliers, GRC may assess:

* Data-center security
* Physical access
* CCTV
* Visitor controls
* Environmental controls
* Fire protection
* Power redundancy

Physical resilience supports cyber and operational resilience.

---

# 30. Step 19 – Backup and Recovery

GRC evaluates:

* Backup frequency
* Backup retention
* Backup encryption
* Backup isolation
* Immutable backups
* Recovery testing
* RTO
* RPO

Example:

SecureCloud:

**RTO = 4 hours**

GlobalConnect:

**Required RTO = 2 hours**

This becomes a supplier risk.

---

# 31. Step 20 – Cyber Recovery

Traditional DR asks:

> "Can you restore the service?"

Cyber recovery asks:

> **"Can you restore the service into a trusted environment after compromise?"**

Due diligence should therefore assess:

* Clean recovery
* Malware scanning
* Credential reset
* Backup isolation
* Recovery testing
* Forensic preservation

---

# 32. Step 21 – Business Continuity

Supplier BCP should address:

* Workforce disruption
* Facility loss
* Technology failure
* Cyberattack
* Supplier dependency
* Regional disaster

GlobalConnect asks:

> **"Can SecureCloud continue supporting us during a major disaster?"**

---

# 33. Step 22 – Geographic Resilience

The supplier operates:

* Primary operations: United Kingdom
* DR: Netherlands
* Support: India
* SOC: Philippines

GRC evaluates:

* Geographic concentration
* Data location
* Legal jurisdiction
* Regional outage risk
* Cross-border support

Geographic diversity can improve resilience but may create regulatory complexity.

---

# 34. Step 23 – Subprocessor Assessment

SecureCloud uses:

* Cloud provider
* Telecom provider
* Security monitoring provider
* Software provider

GRC evaluates:

* Who they are
* What they do
* What data they access
* Whether they are critical
* Whether they can be replaced

This is particularly important for cloud services.

---

# 35. Step 24 – Change Management

Supplier changes can introduce risk.

Examples:

* New software version
* New cloud region
* New subcontractor
* New AI model
* Architecture change

The contract should require notification of material changes.

---

# 36. Step 25 – AI-Specific Supplier Due Diligence

Suppose SecureCloud uses AI for:

* Security analytics
* Automated incident classification
* Customer-service assistance

GRC should additionally assess:

* AI model governance
* Data used for training
* Prompt/data handling
* Model security
* Third-party AI dependencies
* Human oversight
* AI incident management

This is increasingly relevant for modern technology suppliers.

---

# 37. Step 26 – Regulatory Compliance

GlobalConnect assesses whether the supplier supports applicable obligations.

Potential areas include:

* Privacy
* Cybersecurity
* Telecommunications
* Digital resilience
* Data residency
* Incident reporting
* Record retention

The supplier should contractually support GlobalConnect's regulatory obligations where appropriate.

---

# 38. Step 27 – Contractual Security Requirements

Security requirements should be incorporated into the contract.

Typical clauses include:

### Security

Minimum security controls.

### Privacy

Data-processing obligations.

### Incident Response

Notification requirements.

### Audit

Right to obtain assurance.

### Resilience

BCP/DR requirements.

### Subcontractors

Approval/notification requirements.

### Data Return

Requirements upon termination.

### Data Destruction

Secure deletion.

### Access

Restrictions on supplier access.

---

# 39. Step 28 – Security Schedule

For a critical supplier, GlobalConnect attaches a:

> **Third-Party Security Schedule**

It defines measurable requirements.

Example:

| Requirement              | Contractual Standard           |
| ------------------------ | ------------------------------ |
| MFA                      | Required                       |
| PAM                      | Required for privileged access |
| Critical vulnerabilities | ≤15 days                       |
| Incident notification    | ≤4 hours                       |
| Security testing         | Annual                         |
| DR testing               | Annual                         |
| Backup testing           | Quarterly                      |
| Access review            | Quarterly                      |

This converts security expectations into contractual obligations.

---

# 40. Step 29 – Risk Scoring

GlobalConnect scores the supplier.

Example:

| Category            | Score |
| ------------------- | ----: |
| Data Risk           |     5 |
| Access Risk         |     5 |
| Availability Risk   |     5 |
| Regulatory Risk     |     4 |
| Cybersecurity Risk  |     4 |
| Supplier Dependency |     4 |

Overall:

**Very High Inherent Risk**

After controls:

**High Residual Risk**

---

# 41. Step 30 – Risk Treatment

The GRC team identifies:

### Risk 1

Supplier RTO exceeds requirement.

**Treatment:** Contractual improvement + alternate service.

### Risk 2

Two high vulnerabilities remain open.

**Treatment:** Remediation deadline + compensating controls.

### Risk 3

Supplier has privileged access.

**Treatment:** PAM + MFA + session recording.

### Risk 4

Critical subcontractor dependency.

**Treatment:** Subprocessor monitoring + contingency plan.

---

# 42. Conditional Approval

GRC recommends:

> **Conditional Approval**

Conditions:

1. High vulnerabilities remediated within 30 days.
2. Supplier RTO reduced to ≤2 hours within six months.
3. PAM implemented before production access.
4. Security incident notification reduced to ≤4 hours.
5. Annual penetration testing required.
6. Annual DR testing required.

---

# 43. Risk Acceptance

Suppose management decides to accept the current RTO gap temporarily.

The acceptance must identify:

* Risk
* Business justification
* Risk owner
* Expiration date
* Compensating controls
* Review date

Example:

**Risk Owner:** CIO

**Risk:** Supplier RTO exceeds business requirement.

**Expiration:** 6 months

**Compensating Control:** Alternate customer-support platform.

This makes risk acceptance accountable.

---

# 44. Continuous Monitoring

Due diligence does not end after onboarding.

The organization monitors:

* Security incidents
* SLA performance
* Vulnerabilities
* Certifications
* Audit reports
* DR tests
* Changes
* Subprocessors
* Financial health
* Regulatory events

This transforms:

**Vendor Due Diligence**

into:

**Third-Party Risk Management**

---

# 45. Continuous Monitoring Dashboard

Example:

| Metric                        |     Target |   Current |
| ----------------------------- | ---------: | --------: |
| Security incidents            | 0 critical |         1 |
| SLA compliance                |     ≥99.9% |    99.95% |
| Critical vulnerabilities      |          0 |         0 |
| High vulnerabilities >30 days |          0 |         2 |
| DR test                       |     Annual | Completed |
| ISO certification             |      Valid |       Yes |
| Access review                 |  Quarterly |   Current |
| Open high findings            |         ≤1 |         2 |

The supplier is therefore flagged for enhanced monitoring.

---

# 46. Supplier Risk Rating Changes

Supplier risk should be dynamic.

For example:

### Initial

**High**

### Major security incident

**Very High**

### Remediation completed

**High**

### Strong assurance + successful DR test

**Medium/High**

Risk ratings should change based on evidence.

---

# 47. Evidence Repository

GlobalConnect stores supplier evidence in its GRC platform.

Examples:

* Supplier assessment
* ISO certificate
* SOC report
* Penetration test
* DR test
* Security questionnaire
* Risk assessment
* Contract
* DPA
* Remediation evidence
* Risk acceptance

This supports:

* Audit
* Regulatory review
* Management reporting
* Reassessment

---

# 48. Audit Trail

A mature GRC process should answer:

> Who approved this supplier?

> What evidence was reviewed?

> What risks were identified?

> Who accepted the residual risk?

> When must the supplier be reassessed?

> Which findings remain open?

This creates accountability.

---

# 49. Common Due Diligence Failures

### Failure 1

Supplier completes questionnaire without evidence.

### Failure 2

Security reviews only before contract signing.

### Failure 3

No validation of certificate scope.

### Failure 4

No assessment of privileged access.

### Failure 5

No review of subcontractors.

### Failure 6

No DR testing evidence.

### Failure 7

No contractual security requirements.

### Failure 8

No ongoing monitoring.

### Failure 9

Risk acceptance is undocumented.

### Failure 10

Supplier is treated as trusted indefinitely.

---

# 50. GRC Decision Model

The final decision should be:

**Approve**

if risk is acceptable.

**Approve with Conditions**

if remediation is required.

**Accept Risk**

if management explicitly accepts residual risk.

**Reject**

if risk exceeds organizational tolerance.

The decision should never simply be:

> "The questionnaire is complete."

---

# 51. Practical GRC Exercise

You are conducting security due diligence for a critical cloud supplier.

The supplier reports:

* ISO 27001: **Yes**
* SOC 2 Type II: **Yes**
* MFA: **Yes**
* PAM: **Partial**
* Critical vulnerabilities: **0**
* High vulnerabilities: **4**
* Penetration test: **18 months old**
* DR test: **24 months old**
* RTO: **8 hours**
* Required RTO: **4 hours**
* RPO: **2 hours**
* Required RPO: **1 hour**
* Subprocessors: **7**
* Subprocessors independently assessed: **3**
* Incident notification: **24 hours**
* Organization requirement: **4 hours**

### Your task:

Determine:

1. The top five security risks.
2. Which evidence is insufficient.
3. Which findings require immediate remediation.
4. Which requirements should be contractual.
5. Whether the supplier should be approved.
6. What compensating controls should be implemented.
7. Who should accept residual risk.
8. How often the supplier should be reassessed.

---

# 52. Final Third-Party Security Due Diligence Model

The complete process is:

**Understand Supplier**

↓

**Understand Service**

↓

**Identify Data**

↓

**Map Access**

↓

**Determine Criticality**

↓

**Identify Threats**

↓

**Request Evidence**

↓

**Validate Controls**

↓

**Assess Security**

↓

**Assess Privacy**

↓

**Assess Resilience**

↓

**Assess Subcontractors**

↓

**Assess Compliance**

↓

**Calculate Inherent Risk**

↓

**Evaluate Control Effectiveness**

↓

**Calculate Residual Risk**

↓

**Treat Risk**

↓

**Contractualize Requirements**

↓

**Approve**

↓

**Monitor**

↓

**Reassess**

---

# 53. Key GRC Lesson

The central lesson is:

> **Third-party security due diligence is an evidence-based risk decision, not a compliance checklist.**

A supplier can have:

* ISO 27001
* SOC 2
* Penetration testing
* Strong policies
* Mature security tools

and still represent unacceptable risk if:

* Its privileged access is excessive.
* Its recovery capability is inadequate.
* Its subcontractors are poorly governed.
* Its incident notification is too slow.
* Its critical findings remain unresolved.
* Its security controls do not cover the actual service.

The GRC professional's ultimate question is:

> **"Based on the evidence available, can we reasonably trust this supplier with this service, this data, and this level of access—and if not, what must change before we do?"**

That is the essence of **third-party security due diligence**.

# 19.12 Third-Party Risk Management Case Studies

## Part 3 – Managing a High-Risk Supplier Finding

A high-risk supplier finding occurs when a third-party assessment identifies a weakness that could materially affect the organization's:

* Confidentiality
* Integrity
* Availability
* Regulatory compliance
* Business operations
* Financial position
* Reputation

The objective of GRC is not simply to record the finding.

The objective is to:

> **Understand the risk, establish accountability, determine treatment, track remediation, and verify that the risk has actually been reduced.**

A mature process is:

**Finding → Validation → Risk Assessment → Ownership → Treatment → Remediation → Evidence → Verification → Closure → Monitoring**

---

# Case Study: GlobalConnect Telecom

GlobalConnect relies on **DataCore Technologies**, a critical managed-service provider supporting its customer analytics platform.

DataCore has:

* Production access
* Access to customer information
* Administrative privileges
* Cloud infrastructure responsibilities
* Several subcontractors

During GlobalConnect's annual third-party assessment, several significant findings are identified.

---

# 1. Supplier Assessment Results

The assessment identifies:

| Finding                        | Severity |
| ------------------------------ | -------- |
| Excessive privileged accounts  | Critical |
| Unsupported operating systems  | High     |
| Incomplete MFA coverage        | High     |
| DR testing not completed       | High     |
| Missing subcontractor evidence | Medium   |

The most serious finding is:

> **Excessive privileged access to production systems.**

---

# 2. The Finding

GlobalConnect discovers that:

* 18 supplier administrators have production access.
* 7 no longer require that level of access.
* 4 accounts have not been used for more than 90 days.
* 3 accounts do not use MFA.
* 2 shared administrator accounts exist.

This represents a significant access-control weakness.

---

# 3. Why This Is a GRC Issue

At first glance, this looks like an IT security problem.

But it is actually a **third-party enterprise risk**.

If a supplier account is compromised, an attacker could potentially:

* Access production systems
* Modify configurations
* Extract data
* Disable security controls
* Deploy malicious software
* Disrupt services

Therefore, the issue must be escalated beyond the technical team.

---

# 4. Step 1 – Validate the Finding

Before escalating, GRC confirms:

* The assessment evidence
* Account list
* Access permissions
* Last-login dates
* MFA configuration
* Business justification
* Supplier explanation

GRC should distinguish:

> **A confirmed control failure**

from:

> **An assessment assumption.**

---

# 5. Step 2 – Determine the Business Impact

The GRC team asks:

### Confidentiality

Could unauthorized access expose customer data?

**Yes.**

### Integrity

Could unauthorized users modify systems?

**Yes.**

### Availability

Could privileged accounts disrupt production?

**Yes.**

### Regulatory

Could compromise create a reportable incident?

**Potentially.**

### Financial

Could an incident cause significant losses?

**Yes.**

Overall potential impact:

**Very High**

---

# 6. Step 3 – Determine Likelihood

GRC evaluates:

* Number of excessive accounts
* Privilege level
* MFA gaps
* External access
* Monitoring
* Existing compensating controls
* Threat environment

Because several weaknesses exist simultaneously, likelihood is assessed as:

**High**

---

# 7. Risk Calculation

A simple model can be:

**Risk = Likelihood × Impact**

Example:

Likelihood:

**4 / 5**

Impact:

**5 / 5**

Risk:

**20 / 25**

Classification:

**Critical**

This means the finding cannot be treated as a routine administrative issue.

---

# 8. Finding vs Risk

This distinction is extremely important.

### Finding

> 18 supplier administrators have production access.

### Risk

> Excessive supplier privileged access could allow unauthorized modification or compromise of critical production systems.

### Business impact

> A compromise could disrupt customer services, expose information, and create regulatory and financial consequences.

GRC converts:

**Technical observation**

into:

**Business risk.**

---

# 9. Step 4 – Assign Risk Ownership

A common mistake is assigning the risk to:

> "IT Security."

The actual risk owner should normally be the business executive accountable for the affected service.

For example:

**Risk Owner:** CIO

**Security Advisor:** CISO

**Business Owner:** Customer Operations Director

**Supplier Owner:** Vendor Management

**Remediation Owner:** DataCore Security Director

This separates:

* Risk ownership
* Control ownership
* Remediation responsibility

---

# 10. Risk Owner vs Remediation Owner

This distinction is critical.

### Risk Owner

Accepts responsibility for the risk.

### Control Owner

Owns the relevant security control.

### Remediation Owner

Must fix the identified weakness.

For example:

**CIO**

→ Risk Owner

**CISO**

→ Control Owner

**DataCore Security Director**

→ Remediation Owner

The supplier should not automatically become the risk owner simply because the weakness is on the supplier side.

---

# 11. Step 5 – Establish a Remediation Plan

The GRC team requires DataCore to submit a formal remediation plan.

Example:

| Action                      | Owner             | Deadline |
| --------------------------- | ----------------- | -------- |
| Remove unnecessary accounts | DataCore IAM      | 7 days   |
| Disable dormant accounts    | DataCore IAM      | 3 days   |
| Implement MFA               | DataCore IAM      | 14 days  |
| Eliminate shared accounts   | DataCore Security | 30 days  |
| Implement PAM               | DataCore Security | 60 days  |

---

# 12. Immediate Containment

Because the finding is critical, GRC does not wait 60 days for the complete remediation.

Immediate controls include:

* Disable dormant accounts.
* Remove unnecessary privileges.
* Enforce MFA.
* Restrict source IP addresses.
* Increase monitoring.
* Require approval for emergency access.

This reduces exposure while permanent remediation is underway.

---

# 13. Step 6 – Determine Whether Risk Acceptance Is Appropriate

Suppose DataCore says:

> "PAM implementation will take three months."

GRC asks:

> Can the organization safely operate for three months?

If yes, temporary risk treatment may be possible.

If no, the organization may need to:

* Suspend supplier access
* Reduce privileges
* Move the service
* Introduce compensating controls
* Require accelerated remediation

---

# 14. Compensating Controls

If the primary control cannot be implemented immediately, compensating controls may include:

* MFA
* Jump server
* IP restrictions
* Session recording
* Real-time monitoring
* Approval workflow
* Temporary access
* SOC monitoring

The compensating control should reduce the actual risk—not simply create additional paperwork.

---

# 15. Step 7 – Establish a Risk Acceptance Threshold

GlobalConnect's policy states:

| Risk     | Treatment                    |
| -------- | ---------------------------- |
| Low      | Business owner may accept    |
| Medium   | Director approval            |
| High     | Executive approval           |
| Critical | Executive Committee approval |

Because the finding is classified as:

**Critical**

the risk cannot be accepted by the supplier manager.

It requires the appropriate executive authority.

---

# 16. Risk Acceptance Example

Management temporarily accepts the risk because the supplier provides a critical service.

The risk acceptance record states:

**Risk:** Excessive supplier privileged access

**Residual Risk:** High

**Business Justification:** Supplier provides critical production support.

**Compensating Controls:** MFA, PAM gateway, IP restrictions, SOC monitoring.

**Risk Owner:** CIO

**Acceptance Date:** August 18, 2026

**Expiration:** October 31, 2026

**Required Remediation:** Full PAM implementation.

This is accountable risk acceptance.

---

# 17. Risk Acceptance Is Not Risk Closure

This distinction is fundamental.

### Risk Acceptance

Management agrees to live with the risk temporarily or permanently.

### Risk Closure

The underlying risk has been sufficiently reduced or eliminated.

A risk acceptance should therefore not be marked:

> **Closed**

simply because management signed the form.

---

# 18. Step 8 – Track the Finding in GRC

The finding is recorded in the GRC platform.

Example:

| Field             | Value                 |
| ----------------- | --------------------- |
| Finding ID        | TPRM-2026-041         |
| Supplier          | DataCore Technologies |
| Severity          | Critical              |
| Category          | Access Control        |
| Risk Owner        | CIO                   |
| Remediation Owner | DataCore Security     |
| Due Date          | 60 days               |
| Status            | In Progress           |
| Residual Risk     | High                  |
| Acceptance        | Temporary             |
| Evidence Required | PAM implementation    |

---

# 19. Finding Lifecycle

The finding moves through:

**Open**

↓

**Validated**

↓

**Assigned**

↓

**Remediation Planned**

↓

**Remediation In Progress**

↓

**Evidence Submitted**

↓

**Under Verification**

↓

**Closed**

or:

**Risk Accepted**

---

# 20. Step 9 – Monitor Remediation

GRC conducts regular reviews.

Example:

### Week 1

18 accounts → 9 accounts

### Week 2

9 accounts → 4 accounts

### Week 4

4 accounts → 1 account

### Week 6

1 account → 0 unnecessary accounts

Progress is measurable.

---

# 21. Do Not Close Based on Supplier Statements

Supplier says:

> "All privileged-access issues have been resolved."

GRC should not immediately close the finding.

Instead, request evidence.

Possible evidence:

* Updated access list
* PAM screenshots
* Configuration reports
* MFA reports
* Access review results
* System logs
* Independent validation

---

# 22. Evidence-Based Closure

Suppose DataCore provides:

* PAM deployment report
* MFA compliance report
* Access review
* Privileged-session logs

GRC validates:

**18 → 6 → 0 unnecessary privileged accounts**

and confirms:

**100% privileged accounts use MFA.**

The remediation is now supported by evidence.

---

# 23. Step 10 – Independent Verification

For critical findings, the person who implemented the remediation should ideally not be the only person verifying it.

For example:

**DataCore**

implements remediation.

**GlobalConnect Security**

validates technical effectiveness.

**GRC**

validates governance and evidence.

This creates separation of duties.

---

# 24. Control Effectiveness Testing

GRC asks:

> Is the control merely implemented, or is it actually effective?

Example:

PAM exists.

But testing discovers:

* Emergency accounts bypass PAM.
* Two service accounts remain unmanaged.

Therefore:

**Control exists = Yes**

**Control effective = No**

The finding should remain open.

---

# 25. Step 11 – Recalculate Residual Risk

Before remediation:

**Inherent Risk = Critical**

After immediate controls:

**Residual Risk = High**

After complete remediation:

**Residual Risk = Medium**

The risk reduction should be documented.

Example:

**Critical → High → Medium**

---

# 26. The Importance of Risk Reduction

A mature GRC function should demonstrate:

> **How much risk was actually reduced?**

Not merely:

> "The supplier completed the action."

For example:

| Stage               | Risk     |
| ------------------- | -------- |
| Initial             | Critical |
| Containment         | High     |
| Partial remediation | High     |
| Full remediation    | Medium   |

This provides evidence of GRC value.

---

# 27. Second High-Risk Finding

The assessment also identifies:

> **Unsupported operating systems in the supplier environment.**

DataCore has:

**37 servers**

of which:

**6 servers**

run unsupported operating systems.

---

# 28. Why Unsupported Systems Matter

Unsupported systems may no longer receive:

* Security patches
* Vendor fixes
* Vulnerability updates
* Security support

This increases the likelihood of exploitation.

But GRC must determine:

> **Are those six systems actually exposed to critical services?**

---

# 29. Risk Context

Suppose:

* 4 systems are isolated.
* 2 systems support production.
* 1 production system contains sensitive information.
* Internet exposure is limited.

Risk may differ significantly across the six systems.

Therefore:

> **Asset context matters.**

---

# 30. Risk Treatment

Possible options:

### Replace

Upgrade operating system.

### Isolate

Network segmentation.

### Compensate

Additional EDR and monitoring.

### Remove

Decommission unnecessary servers.

### Accept

Only if formally justified.

The preferred solution is normally:

> **Remove the unsupported technology.**

---

# 31. Third Finding – Incomplete MFA

DataCore has:

**120 supplier accounts**

but only:

**114 accounts**

have MFA.

Six accounts are exceptions.

GRC determines:

* 2 are service accounts.
* 2 are emergency accounts.
* 2 are human administrator accounts.

The human administrator exceptions are unacceptable.

---

# 32. Risk-Based Exception Management

Not every exception has identical risk.

### Service account

May require compensating technical controls.

### Emergency account

May require vaulting and controlled access.

### Human administrator

Should normally use strong MFA.

Therefore, GRC evaluates exceptions individually.

---

# 33. Fourth Finding – DR Testing

DataCore has not tested its DR environment for:

**24 months**

GlobalConnect requires:

**Annual testing**

This is a significant resilience finding.

GRC asks:

* Why was the test missed?
* Has the architecture changed?
* Are recovery procedures current?
* Has the supplier experienced major changes?
* Can the service meet the required RTO/RPO?

---

# 34. Corrective Action

DataCore commits to:

**DR test within 30 days**

The test must demonstrate:

* Recovery time
* Recovery point
* Application availability
* Data integrity
* Communication
* Escalation
* Lessons learned

A successful test becomes evidence for closure.

---

# 35. Fifth Finding – Missing Subcontractor Evidence

DataCore uses three critical subcontractors.

Only one has provided adequate security evidence.

This creates:

> **Fourth-party risk.**

GRC requires:

* Subcontractor inventory
* Security assurance
* Contractual flow-down requirements
* Risk classification
* Monitoring

---

# 36. Supplier Escalation

If the supplier fails to remediate critical findings, GRC may escalate through:

**Supplier Manager**

↓

**Procurement**

↓

**CISO**

↓

**CIO**

↓

**Risk Committee**

↓

**Executive Management**

The escalation level should correspond to the risk.

---

# 37. Supplier Performance Review

A quarterly supplier review may include:

### Security

* Open findings
* Incidents
* Vulnerabilities

### Compliance

* Regulatory issues
* Audit findings

### Resilience

* DR tests
* SLA performance

### Governance

* Risk acceptance
* Control exceptions

### Commercial

* Contract performance

This creates integrated supplier governance.

---

# 38. Supplier Risk Dashboard

Example:

| Metric             | Status    |
| ------------------ | --------- |
| Critical findings  | 0         |
| High findings      | 2         |
| Overdue findings   | 1         |
| Security incidents | 1         |
| SLA                | 99.95%    |
| MFA                | 100%      |
| PAM                | 100%      |
| DR test            | Completed |
| ISO 27001          | Valid     |

The supplier is classified:

**High Risk – Enhanced Monitoring**

---

# 39. When Should a Finding Be Escalated?

Escalate when:

* Critical vulnerability exists.
* Remediation deadline is missed.
* Supplier refuses remediation.
* Risk exceeds appetite.
* Security incident occurs.
* Contractual requirements are violated.
* Regulatory exposure exists.
* Supplier becomes financially unstable.
* Risk increases materially.

---

# 40. When Should a Supplier Be Suspended?

In extreme cases, GlobalConnect may suspend supplier access.

Examples:

* Active compromise
* Malicious insider
* Uncontrolled privileged access
* Repeated critical failures
* Material contract breach
* Regulatory prohibition
* Failure to remediate unacceptable risk

Suspension itself can create operational risk, so the decision must consider business continuity.

---

# 41. Supplier Risk vs Business Continuity

Suppose DataCore's privileged access is considered too risky.

Immediately terminating access could cause:

* Loss of technical support
* Service disruption
* Customer impact

Therefore, GRC must consider:

> **How do we reduce supplier risk without creating an even larger operational risk?**

Possible solution:

* Reduce access
* Add monitoring
* Transition support
* Establish alternate provider
* Gradually remove supplier access

---

# 42. Exit Strategy

Critical supplier relationships should have an exit strategy.

It should address:

* Data extraction
* Data migration
* Credential revocation
* Access removal
* Asset return
* Data destruction
* Knowledge transfer
* Replacement supplier

This ensures:

> **Risk management does not depend on permanent supplier dependency.**

---

# 43. Finding Closure Criteria

A high-risk finding should be closed only when:

1. Root cause is understood.
2. Corrective action is completed.
3. Evidence is provided.
4. Evidence is independently validated.
5. Control operates effectively.
6. Residual risk is recalculated.
7. Risk owner agrees.
8. GRC formally closes the finding.

---

# 44. Root Cause Matters

Suppose the supplier repeatedly fails privileged-access reviews.

The immediate problem:

> Access review not completed.

But the root cause may be:

> No automated identity lifecycle integration between HR and IAM.

If GRC only fixes the immediate review, the problem may return.

Therefore:

> **Corrective action should address the root cause, not just the symptom.**

---

# 45. Corrective vs Preventive Action

### Corrective Action

Fix the current problem.

Example:

Remove unauthorized accounts.

### Preventive Action

Prevent recurrence.

Example:

Automate supplier account provisioning and deprovisioning.

A mature remediation plan should contain both.

---

# 46. Lessons Learned

After the finding is closed, GRC should ask:

* Why was the issue not detected earlier?
* Was the original due diligence sufficient?
* Did monitoring fail?
* Was the contract weak?
* Was ownership unclear?
* Should the supplier tier change?
* Should assessment frequency increase?

This converts an individual finding into organizational improvement.

---

# 47. Supplier Risk Rating Update

Before the findings:

**Medium**

After critical findings:

**Critical**

After containment:

**High**

After remediation:

**Medium**

If repeated failures occur:

**High/Critical**

Supplier ratings should therefore be dynamic.

---

# 48. Practical GRC Exercise

A critical supplier has the following findings:

| Finding               | Severity | Status      |
| --------------------- | -------- | ----------- |
| Privileged accounts   | Critical | Open        |
| Unsupported servers   | High     | In progress |
| MFA gaps              | High     | Remediated  |
| DR testing            | High     | Overdue     |
| Subprocessor evidence | Medium   | Open        |

The supplier asks for another **90 days** to remediate the critical finding.

You are the GRC Manager.

Determine:

1. Should the extension be approved?
2. Who should approve it?
3. What compensating controls should be required?
4. What evidence should the supplier provide?
5. Should the supplier's risk rating change?
6. Should supplier access be restricted?
7. When should escalation occur?
8. What would constitute successful closure?

---

# 49. High-Risk Supplier Finding Management Model

The complete process is:

**Identify Finding**

↓

**Validate Finding**

↓

**Assess Business Impact**

↓

**Calculate Risk**

↓

**Assign Risk Owner**

↓

**Assign Remediation Owner**

↓

**Contain Immediate Exposure**

↓

**Develop Corrective Action**

↓

**Establish Deadline**

↓

**Apply Compensating Controls**

↓

**Monitor Progress**

↓

**Collect Evidence**

↓

**Independently Verify**

↓

**Recalculate Residual Risk**

↓

**Close or Accept Risk**

↓

**Monitor for Recurrence**

↓

**Capture Lessons Learned**

---

# 50. Key GRC Lesson

The central lesson is:

> **A supplier finding is not successfully managed when the supplier says "fixed." It is successfully managed when the organization can demonstrate that the risk has been reduced to an acceptable level through verified, effective controls.**

The strongest GRC approach therefore connects:

**Finding**

→ **Risk**

→ **Business Impact**

→ **Accountability**

→ **Remediation**

→ **Evidence**

→ **Verification**

→ **Residual Risk**

→ **Executive Decision**

This is what transforms third-party risk management from a **vendor compliance exercise** into a genuine **enterprise risk management capability**.

# 19.12 Third-Party Risk Management Case Studies

## Part 4 – Offboarding a Critical Third Party Securely

Third-party offboarding is the controlled process of terminating a supplier relationship while protecting:

* Information
* Systems
* Credentials
* Intellectual property
* Customer data
* Business operations
* Regulatory compliance
* Evidence and records

Offboarding is frequently underestimated.

Organizations often focus heavily on **supplier onboarding** but fail to consider how the relationship will end.

For a critical supplier, this can create significant security and operational exposure.

The fundamental principle is:

> **A supplier relationship is not securely terminated until the supplier's access, data, dependencies, assets, and residual risks have been addressed and verified.**

The lifecycle is:

**Exit Decision → Planning → Dependency Assessment → Access Revocation → Data Return → Data Destruction → Asset Recovery → Knowledge Transfer → Subcontractor Closure → Verification → Contract Closure → Lessons Learned**

---

# Case Study: GlobalConnect Telecom

GlobalConnect has used **DataCore Technologies** for seven years to operate part of its customer analytics and reporting environment.

DataCore provides:

* Cloud infrastructure management
* Database administration
* Security monitoring
* Application support
* Production support
* Backup management

DataCore has:

* Privileged accounts
* VPN access
* Cloud administration
* API credentials
* Service accounts
* Administrative certificates
* Access to customer information

GlobalConnect has now selected another provider.

The contract with DataCore will terminate in **90 days**.

This creates a major GRC challenge:

> **How can GlobalConnect terminate the supplier without creating a security incident or business disruption?**

---

# 1. Why Offboarding Is a Security Risk

Supplier termination can create risks such as:

* Former employees retaining access
* Forgotten service accounts
* API keys remaining active
* VPN credentials remaining valid
* Data remaining with the supplier
* Backup copies not being deleted
* Subcontractors retaining information
* Certificates remaining valid
* Supplier personnel retaining knowledge of systems
* Incomplete documentation

The most dangerous assumption is:

> "The contract ended, so the supplier no longer has access."

Contract termination and technical access termination are **not the same thing**.

---

# 2. Offboarding Is a GRC Process

A mature offboarding process involves:

### Business

Why is the supplier being terminated?

### Security

How will access be removed?

### Privacy

How will personal data be returned or deleted?

### IT

How will systems and credentials be transitioned?

### Procurement

How will the contract be terminated?

### Legal

What contractual obligations remain?

### Risk

What residual risks exist after termination?

### Audit

What evidence proves the relationship was properly closed?

---

# 3. Step 1 – Establish the Exit Decision

GlobalConnect's Executive Committee approves the supplier transition.

Reason:

> GlobalConnect is moving from DataCore to an internally managed platform and a new managed-service provider.

The decision includes:

* Contract termination
* Transition period
* Replacement supplier
* Migration plan
* Security requirements
* Business continuity requirements

---

# 4. Step 2 – Establish an Offboarding Team

A cross-functional team is established.

| Role             | Responsibility        |
| ---------------- | --------------------- |
| CIO              | Executive sponsor     |
| CISO             | Security              |
| GRC Manager      | Risk and governance   |
| Procurement      | Contract              |
| Legal            | Legal obligations     |
| Privacy Officer  | Data protection       |
| IT               | Technical migration   |
| Business Owner   | Service continuity    |
| Supplier Manager | Supplier coordination |
| DataCore         | Exit execution        |

This avoids having one department manage the entire exit.

---

# 5. Step 3 – Define the Exit Date

The organization establishes:

**Contract termination date:** November 16, 2026

The transition period is:

**90 days**

During this period:

* DataCore continues limited operations.
* New provider begins onboarding.
* Systems are migrated.
* Access is progressively reduced.

---

# 6. Step 4 – Build an Exit Plan

The GRC team creates an exit checklist.

Major workstreams include:

1. Access revocation
2. Data migration
3. Data return
4. Data destruction
5. Credential rotation
6. Asset recovery
7. Documentation
8. Knowledge transfer
9. Subcontractor termination
10. Contract closure
11. Evidence collection
12. Final risk assessment

---

# 7. Step 5 – Identify Everything the Supplier Can Access

This is one of the most important steps.

The organization identifies:

* User accounts
* Privileged accounts
* Service accounts
* VPN accounts
* API keys
* SSH keys
* Certificates
* Tokens
* Cloud roles
* Database accounts
* Monitoring accounts
* Backup accounts

The goal is:

> **No forgotten access.**

---

# 8. Access Inventory

Example:

| Access Type         | Quantity |
| ------------------- | -------: |
| Human accounts      |       26 |
| Privileged accounts |       14 |
| Service accounts    |       18 |
| API keys            |       12 |
| VPN accounts        |       21 |
| SSH keys            |        9 |
| Certificates        |        7 |

Total access artifacts:

**107**

These must be accounted for.

---

# 9. Step 6 – Identify Supplier Personnel

DataCore has:

**26 personnel**

who support GlobalConnect.

The organization identifies:

* Names
* Roles
* Access levels
* Business justification
* Last login
* Systems accessed

This creates a supplier personnel register.

---

# 10. Step 7 – Reduce Access During Transition

Offboarding does not mean immediately disabling every account.

If DataCore still needs to support migration, access may be temporarily retained.

However:

> **Access should progressively decrease as the supplier's responsibilities decrease.**

Example:

### Day 1

Full operational support.

### Day 30

Reduced administrative access.

### Day 60

Migration-only access.

### Day 80

Emergency access only.

### Day 90

All access revoked.

This is a **risk-based deprovisioning strategy**.

---

# 11. Step 8 – Apply Least Privilege

During transition:

* Remove unnecessary access.
* Remove inactive accounts.
* Restrict privileged roles.
* Require MFA.
* Use PAM.
* Require approval.
* Monitor sessions.

The supplier should not retain normal operational privileges merely because the contract has not yet expired.

---

# 12. Step 9 – Credential Rotation

This is critical.

GlobalConnect identifies credentials that DataCore knew or controlled.

These include:

* Passwords
* API keys
* Tokens
* SSH keys
* Certificates
* Cloud secrets
* Database credentials

All relevant credentials should be:

> **Rotated or revoked.**

---

# 13. Why Credential Rotation Matters

Suppose a DataCore administrator knows a production database password.

Even after the account is disabled, the password may still be known.

If the password is reused elsewhere, the organization remains exposed.

Therefore:

**Disable account**

is not necessarily sufficient.

The organization may also need:

**Rotate credential**

---

# 14. Step 10 – Review Shared Credentials

Shared accounts are particularly dangerous.

Example:

**svc-admin**

was used by:

* 8 DataCore administrators
* 2 GlobalConnect administrators

The organization must:

* Replace shared credentials.
* Create individual accounts.
* Rotate passwords.
* Review historical activity.

Shared credentials can make accountability difficult.

---

# 15. Step 11 – Cloud Access Revocation

DataCore has administrative access to:

* Azure
* AWS
* SaaS management platforms

GlobalConnect must revoke:

* IAM roles
* Service principals
* Access keys
* Federation relationships
* Administrative accounts
* API tokens

Cloud access should be validated independently.

---

# 16. Step 12 – VPN and Remote Access

DataCore uses VPN access.

At termination:

* Disable VPN accounts.
* Remove certificates.
* Remove device trust.
* Remove IP allowlists.
* Disable remote-access gateways.
* Review remote sessions.

The organization should verify that no alternate remote-access method remains.

---

# 17. Step 13 – Data Inventory

GlobalConnect identifies all information held by DataCore.

Potential locations include:

* Production databases
* Backup systems
* File shares
* Cloud storage
* Tickets
* Logs
* Email
* Workstations
* Development environments
* Disaster-recovery environments

The organization must know:

> **Where is our data?**

---

# 18. Step 14 – Data Return

The contract requires DataCore to return GlobalConnect data.

The migration includes:

* Customer records
* Configuration data
* Logs
* Reports
* Documentation
* System configurations
* Backup information

Data integrity must be validated.

---

# 19. Data Migration Validation

Suppose DataCore exports:

**2.4 TB**

of data.

GlobalConnect validates:

* File counts
* Hash values
* Database record counts
* Application functionality
* Data integrity

The goal is not merely:

> "The supplier sent us the data."

It is:

> **"We verified that the data is complete, accurate, and usable."**

---

# 20. Step 15 – Data Retention

Not all supplier data should necessarily be deleted immediately.

Some records may need to be retained for:

* Legal requirements
* Regulatory obligations
* Audit
* Contractual disputes
* Financial records

Therefore, Legal, Privacy, and GRC must determine:

> **What must be retained and for how long?**

---

# 21. Step 16 – Data Destruction

For information that should not be retained, the supplier must securely destroy it.

This may include:

* Production copies
* Temporary files
* Local copies
* Backup copies
* Test data
* Cached information

The organization should obtain:

> **Evidence of secure destruction.**

---

# 22. Backup Challenge

Suppose DataCore says:

> "All production data has been deleted."

GRC asks:

> What about backups?

The supplier has:

* Daily backups
* Monthly backups
* Disaster-recovery copies
* Offline archives

The contract should define how data is handled in backups.

---

# 23. Data Destruction Certificate

DataCore provides a:

**Certificate of Data Destruction**

It confirms:

* Systems covered
* Data categories
* Destruction method
* Date
* Responsible officer

However, GRC should verify that the certificate covers the relevant environments.

---

# 24. Step 17 – Subcontractor Offboarding

DataCore uses:

* Cloud provider
* Backup provider
* SOC provider
* Database support provider

Termination must flow through the supply chain.

The organization must determine:

> **Did every relevant subcontractor also stop processing GlobalConnect data?**

This is often overlooked.

---

# 25. Step 18 – Recover Physical Assets

DataCore has:

* 12 laptops
* 4 network appliances
* 3 security tokens
* 7 hardware authentication devices

GlobalConnect verifies:

* Asset inventory
* Serial numbers
* Condition
* Return date

Assets are reconciled against the original records.

---

# 26. Step 19 – Revoke Physical Access

The organization removes:

* Building badges
* Data-center access
* Visitor permissions
* Physical tokens
* Site access lists

Security should confirm that former supplier personnel cannot enter restricted facilities.

---

# 27. Step 20 – Knowledge Transfer

A critical supplier may possess significant institutional knowledge.

DataCore knows:

* Network architecture
* Application dependencies
* Recovery procedures
* Operational processes
* Troubleshooting procedures
* System configurations

This knowledge must be transferred.

---

# 28. Knowledge Transfer Package

The outgoing supplier provides:

* Architecture diagrams
* Configuration documentation
* Runbooks
* Incident procedures
* DR procedures
* Asset inventories
* Contact lists
* Dependency maps
* Known issues
* Open risks

This reduces operational dependency.

---

# 29. Step 21 – Transition to Replacement Supplier

The new supplier begins taking over.

The transition should be controlled.

Example:

**DataCore**

→ Existing environment

**NewSupplier**

→ Target environment

The organization should avoid a situation where:

> Both suppliers have unrestricted privileged access simultaneously.

---

# 30. Dual-Supplier Risk

During transition:

* Two suppliers may have access.
* Credentials may overlap.
* Responsibilities may be unclear.
* Incident accountability may become ambiguous.

Therefore:

> **Dual access should be temporary, documented, restricted, and monitored.**

---

# 31. Step 22 – Security Monitoring During Transition

Because transition creates elevated risk, monitoring may be increased.

Examples:

* Privileged-session monitoring
* SIEM alerts
* Unusual data-transfer detection
* Authentication monitoring
* API activity monitoring
* DLP monitoring

The organization should pay particular attention to:

> **Large data downloads before termination.**

---

# 32. Step 23 – Insider Threat Consideration

Supplier termination may increase insider risk.

A disgruntled supplier employee may attempt:

* Data theft
* Sabotage
* Unauthorized access
* Credential misuse
* Intellectual-property theft

Therefore, GRC should coordinate with Security Operations.

---

# 33. Step 24 – Review Outstanding Supplier Findings

Before final termination, GlobalConnect reviews:

* Open vulnerabilities
* Open audit findings
* Open incidents
* Risk acceptances
* Contract disputes
* Regulatory issues

Not all findings disappear when the contract ends.

Some may require continued monitoring.

---

# 34. Step 25 – Contractual Exit Obligations

The contract should address:

* Notice period
* Data return
* Data destruction
* Assistance during transition
* Knowledge transfer
* Audit rights
* Confidentiality
* Intellectual property
* Security obligations
* Post-termination obligations

This is why exit requirements should be established:

> **Before the supplier is onboarded.**

---

# 35. Step 26 – Final Access Verification

On termination day, GlobalConnect executes a formal access-revocation checklist.

Example:

| Access              | Status              |
| ------------------- | ------------------- |
| Human accounts      | Revoked             |
| Privileged accounts | Revoked             |
| VPN                 | Disabled            |
| API keys            | Rotated             |
| SSH keys            | Revoked             |
| Cloud roles         | Removed             |
| Certificates        | Revoked             |
| Physical access     | Removed             |
| Service accounts    | Reassigned/disabled |

---

# 36. Four-Eyes Verification

Access revocation should ideally be verified by two independent parties.

For example:

**IT Security**

performs revocation.

**GRC/Internal Control**

verifies completion.

This reduces the risk of missed access.

---

# 37. Step 27 – Final Security Validation

GRC requests evidence such as:

* IAM reports
* PAM reports
* VPN logs
* Cloud IAM reports
* Certificate revocation records
* Asset-return records
* Data destruction certificate

The objective is to prove:

> **The supplier no longer has unauthorized access.**

---

# 38. Step 28 – Final Privacy Validation

Privacy confirms:

* Data returned
* Data deleted where required
* Retention obligations documented
* Subprocessors addressed
* International transfers terminated
* DPA obligations completed

This provides privacy closure.

---

# 39. Step 29 – Final Business Validation

The business owner confirms:

* Replacement service operational
* Business processes functioning
* Customer impact acceptable
* No critical dependencies remain
* Support processes transferred

Security closure without business continuity validation is incomplete.

---

# 40. Step 30 – Final Risk Assessment

GRC performs a final risk review.

Example:

### Before Exit

Supplier dependency:

**Very High**

### During Transition

Risk:

**High**

### After Transition

Dependency:

**Low**

### After Access Revocation

Supplier security exposure:

**Low**

This demonstrates successful risk reduction.

---

# 41. Supplier Offboarding Register

The GRC platform should maintain:

| Item                  | Status   |
| --------------------- | -------- |
| Contract termination  | Complete |
| Access revocation     | Complete |
| Data migration        | Complete |
| Data destruction      | Complete |
| Asset recovery        | Complete |
| Subcontractor closure | Complete |
| Knowledge transfer    | Complete |
| Final risk review     | Complete |
| Evidence archive      | Complete |

---

# 42. Final Supplier Closure

DataCore's status changes from:

**Active**

to:

**Terminated**

But GRC retains the historical record.

This may include:

* Assessments
* Contracts
* Risk records
* Incidents
* Audit findings
* Evidence
* Approvals
* Termination records

Historical records are important for:

* Audits
* Regulatory reviews
* Litigation
* Lessons learned

---

# 43. Post-Termination Monitoring

Termination does not necessarily mean all monitoring immediately stops.

For a defined period, GlobalConnect may monitor:

* Residual credentials
* Data leakage
* Unexpected authentication
* Supplier communications
* Regulatory obligations

For example:

**30–90 days of enhanced monitoring**

may be appropriate for a critical supplier.

---

# 44. Post-Termination Incident Scenario

Suppose two weeks after termination, GlobalConnect detects:

> A former DataCore API key attempting authentication.

This becomes a security incident.

The organization investigates:

* Was the key supposed to be revoked?
* Where was it stored?
* Who used it?
* Was data accessed?
* Was the key reused elsewhere?

This illustrates why:

> **Credential inventory and rotation are essential.**

---

# 45. Offboarding Failure Scenario

Imagine GlobalConnect terminates DataCore but forgets:

* One VPN account
* Two API keys
* One service account
* One cloud IAM role

Three months later, attackers compromise one of these credentials.

The supplier relationship was legally terminated.

But technically:

> **The organization was never fully offboarded.**

This is a classic third-party risk failure.

---

# 46. Common Offboarding Mistakes

### Mistake 1

Assuming contract termination automatically removes access.

### Mistake 2

Forgetting service accounts.

### Mistake 3

Forgetting API keys.

### Mistake 4

Not rotating shared credentials.

### Mistake 5

Ignoring backups.

### Mistake 6

Not checking subcontractors.

### Mistake 7

Failing to recover physical assets.

### Mistake 8

Skipping knowledge transfer.

### Mistake 9

Not validating data destruction.

### Mistake 10

Failing to maintain evidence.

---

# 47. Secure Offboarding Checklist

A critical supplier should generally have:

### Governance

* [ ] Executive approval
* [ ] Exit plan
* [ ] Risk assessment
* [ ] Defined termination date

### Identity

* [ ] User accounts revoked
* [ ] Privileged accounts revoked
* [ ] Service accounts reviewed
* [ ] MFA relationships removed
* [ ] VPN access removed

### Credentials

* [ ] Passwords rotated
* [ ] API keys revoked
* [ ] SSH keys revoked
* [ ] Certificates revoked
* [ ] Tokens invalidated

### Data

* [ ] Data inventory completed
* [ ] Data returned
* [ ] Data migrated
* [ ] Data destroyed
* [ ] Backups addressed
* [ ] Destruction evidence obtained

### Infrastructure

* [ ] Cloud access removed
* [ ] Network access removed
* [ ] Monitoring access removed
* [ ] Administrative access removed

### Physical

* [ ] Assets recovered
* [ ] Badges revoked
* [ ] Tokens returned

### Supply Chain

* [ ] Subcontractors identified
* [ ] Subcontractor access removed
* [ ] Data processing terminated

### Business

* [ ] Knowledge transfer completed
* [ ] Replacement supplier operational
* [ ] Business continuity confirmed

### Governance Closure

* [ ] Final risk review
* [ ] Evidence archived
* [ ] Contract closed
* [ ] Lessons learned completed

---

# 48. Offboarding RACI

A simplified RACI could look like:

| Activity          | GRC | Security | IT  | Procurement | Privacy | Supplier |
| ----------------- | --- | -------- | --- | ----------- | ------- | -------- |
| Exit planning     | A/R | C        | C   | R           | C       | C        |
| Access revocation | C   | A/R      | R   | I           | I       | R        |
| Data migration    | C   | C        | A/R | I           | C       | R        |
| Data destruction  | A   | C        | C   | I           | R       | R        |
| Contract closure  | C   | I        | I   | A/R         | C       | C        |
| Final risk review | A/R | C        | C   | C           | C       | I        |

The exact RACI should be adapted to organizational structure.

---

# 49. GRC Metrics for Supplier Offboarding

Useful metrics include:

### Access Revocation Rate

**100%**

### Credential Rotation Rate

**100%**

### Data Destruction Completion

**100%**

### Asset Recovery

**100%**

### Open Exit Findings

**0 Critical / 0 High**

### Knowledge Transfer

**100%**

### Subcontractor Closure

**100%**

These provide measurable evidence of successful offboarding.

---

# 50. Practical GRC Exercise

A critical supplier is being terminated.

The organization discovers:

* 24 human accounts
* 8 privileged accounts
* 11 service accounts
* 15 API keys
* 6 VPN accounts
* 3 cloud IAM roles
* 2 subcontractors
* 4 TB of production data
* 7 TB of backup data
* 14 supplier laptops
* 3 undocumented integrations

The supplier's contract ends in **30 days**.

You are the GRC Manager.

Determine:

1. What should be completed before termination?
2. Which risks require immediate action?
3. Which credentials must be rotated?
4. How should backup data be handled?
5. How should subcontractors be addressed?
6. How should the undocumented integrations be identified?
7. What evidence should be retained?
8. What should happen on the final termination day?
9. How should post-termination monitoring be performed?
10. What would constitute successful closure?

---

# 51. End-to-End Critical Supplier Offboarding Model

The complete lifecycle is:

**Executive Exit Decision**

↓

**Establish Exit Team**

↓

**Define Termination Date**

↓

**Map Supplier Dependencies**

↓

**Inventory Accounts and Access**

↓

**Inventory Data**

↓

**Inventory Assets**

↓

**Identify Subcontractors**

↓

**Plan Migration**

↓

**Reduce Supplier Privileges**

↓

**Transfer Knowledge**

↓

**Migrate Data**

↓

**Validate Data Integrity**

↓

**Recover Assets**

↓

**Rotate Credentials**

↓

**Revoke Access**

↓

**Address Data Retention**

↓

**Securely Destroy Data**

↓

**Terminate Subcontractor Access**

↓

**Validate Business Continuity**

↓

**Perform Final Security Verification**

↓

**Perform Final Privacy Verification**

↓

**Recalculate Residual Risk**

↓

**Close Contract**

↓

**Archive Evidence**

↓

**Post-Termination Monitoring**

↓

**Lessons Learned**

---

# 52. The Most Important GRC Principle

The most important lesson from third-party offboarding is:

> **"No supplier should retain access, data, credentials, assets, or operational dependency simply because the organization has ended the contract."**

A secure termination requires both:

**Administrative termination**

and

**Technical termination.**

The organization should be able to demonstrate:

> **Who had access, what they accessed, what data they possessed, what was returned, what was destroyed, what credentials were revoked, and who verified the closure.**

---

# 53. Chapter 19.12 Summary

The four case studies in **Third-Party Risk Management** demonstrate the complete supplier-risk lifecycle:

### Part 1 – Assessing a Critical Technology Supplier

Focus:

**Identify → Classify → Assess → Treat → Approve**

### Part 2 – Conducting Third-Party Security Due Diligence

Focus:

**Questionnaire → Evidence → Control Validation → Residual Risk**

### Part 3 – Managing a High-Risk Supplier Finding

Focus:

**Finding → Risk → Remediation → Verification → Closure**

### Part 4 – Offboarding a Critical Third Party Securely

Focus:

**Exit → Access Revocation → Data Protection → Transition → Verification → Closure**

Together, these demonstrate that mature third-party risk management is not simply:

> **"Assess the vendor once."**

It is:

> **Identify → Assess → Contract → Monitor → Remediate → Reassess → Exit → Verify**

That lifecycle is the foundation of a mature **Third-Party Risk Management (TPRM) program** and directly connects supplier governance with enterprise risk management, cybersecurity, privacy, business continuity, compliance, audit, and executive decision-making.





