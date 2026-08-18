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




