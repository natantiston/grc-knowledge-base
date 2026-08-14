# 18.12 Third-Party Risk Management Diagrams

## Part 1 – Third-Party Risk Lifecycle

Third parties have become an integral part of modern organizations. Cloud providers, managed service providers, software vendors, consultants, outsourcing partners, telecommunications providers, payment processors, and other suppliers may perform activities that directly affect an organization's **security, privacy, resilience, regulatory compliance, and business operations**.

As a result, third-party risk management (TPRM) should not be treated simply as a procurement activity. From a GRC perspective, it is a **continuous risk management lifecycle** that begins before a supplier is engaged and continues throughout the relationship until the supplier is properly offboarded.

A simplified third-party risk lifecycle is:

```text
Business Need
     ↓
Third-Party Identification
     ↓
Initial Risk Screening
     ↓
Due Diligence
     ↓
Risk Assessment
     ↓
Risk Treatment
     ↓
Contracting
     ↓
Onboarding
     ↓
Ongoing Monitoring
     ↓
Periodic Reassessment
     ↓
Offboarding
     ↓
Lessons Learned
     ↺
```

The lifecycle should be governed by the organization's risk appetite, regulatory obligations, security requirements, and business objectives.

---

# 1. What Is Third-Party Risk?

Third-party risk is the risk that an external organization or supplier may negatively affect the organization's:

```text
Confidentiality
Integrity
Availability
Privacy
Compliance
Resilience
Financial Position
Reputation
Operations
Strategic Objectives
```

For example:

```text
Cloud Provider
      ↓
Service Disruption
      ↓
Business Service Unavailable
      ↓
Customer Impact
      ↓
Financial / Regulatory Impact
```

The organization may not control the supplier directly, but it remains responsible for managing the risk created by the relationship.

---

# 2. Why Third-Party Risk Management Matters

Organizations increasingly depend on external parties for critical capabilities.

Examples include:

```text
Cloud Infrastructure
Software
Cybersecurity Services
Data Processing
Payment Services
Customer Support
Telecommunications
Logistics
Professional Services
Managed IT Services
```

This creates dependencies outside the organization's direct operational control.

A simplified dependency model is:

```text
Organization
      ↓
Third Party
      ↓
Technology / Service
      ↓
Business Process
      ↓
Customer / Stakeholder
```

A failure at the third party can therefore become a business risk for the organization.

---

# 3. Third-Party Risk vs. Vendor Management

Vendor management and third-party risk management are related but not identical.

**Vendor management** generally focuses on:

```text
Procurement
Contracts
Pricing
Service Delivery
Supplier Performance
```

**Third-party risk management** focuses on:

```text
Cybersecurity
Privacy
Compliance
Operational Risk
Business Continuity
Resilience
Financial Risk
Concentration Risk
Reputational Risk
```

A mature organization integrates both perspectives.

```text
Procurement
     +
Vendor Management
     +
Risk Management
     +
Cybersecurity
     +
Compliance
     ↓
Third-Party Governance
```

---

# 4. Third-Party Risk Lifecycle

The complete lifecycle can be represented as:

```text
1. Identify
      ↓
2. Classify
      ↓
3. Assess
      ↓
4. Due Diligence
      ↓
5. Treat
      ↓
6. Contract
      ↓
7. Onboard
      ↓
8. Monitor
      ↓
9. Reassess
      ↓
10. Offboard
```

Each stage should have defined ownership, controls, documentation, and evidence.

---

# 5. Stage 1 – Business Need

The lifecycle should begin when a business unit identifies a need for an external service.

For example:

```text
Business Requirement
       ↓
Capability Not Available Internally
       ↓
External Supplier Required
```

The business should document why the third party is needed.

Examples:

```text
Cloud Migration
Managed SOC
Software Platform
Payment Processing
Customer Support
Specialized Consulting
Data Analytics
```

This establishes the business context for subsequent risk assessment.

---

# 6. Stage 2 – Third-Party Identification

The organization identifies the proposed supplier and the services it will provide.

Information may include:

```text
Supplier Name
Service
Business Owner
Products
Locations
Data Processed
Systems Accessed
Countries Involved
Subcontractors
Contract Value
Expected Duration
```

This establishes the initial supplier profile.

---

# 7. Stage 3 – Initial Risk Screening

Before performing a detailed assessment, the organization can conduct an initial screening.

Questions may include:

```text
Will the supplier access sensitive information?

Will the supplier access internal systems?

Will the supplier process personal data?

Is the service business-critical?

Is the supplier supporting a regulated activity?

Does the supplier operate in another country?

Does the supplier use subcontractors?

Would supplier failure significantly affect operations?
```

The answers determine the appropriate level of due diligence.

---

# 8. Third-Party Risk Classification

Not every supplier requires the same level of assessment.

A classification model may be:

```text
Tier 1 – Critical
Tier 2 – High Risk
Tier 3 – Moderate Risk
Tier 4 – Low Risk
```

For example:

```text
Cloud Hosting Provider
        ↓
Critical

Office Supply Vendor
        ↓
Low
```

Risk classification should be based on the potential impact of supplier failure or compromise.

---

# 9. Critical Third Parties

A third party may be considered critical when disruption could significantly affect the organization's:

```text
Critical Business Services
Customers
Regulatory Obligations
Financial Stability
Security
Resilience
```

For example:

```text
Critical Business Service
        ↓
Cloud Provider
        ↓
Critical Third Party
```

Critical suppliers generally require enhanced governance and monitoring.

---

# 10. Risk Factors

Third-party risk classification can consider multiple factors.

```text
Data Sensitivity
System Access
Business Criticality
Service Availability
Regulatory Impact
Geographic Exposure
Subcontractor Dependence
Financial Exposure
Cybersecurity Exposure
Concentration Risk
```

A simplified model is:

```text
Risk Exposure
     ↓
Data
+
Access
+
Criticality
+
Dependency
+
Regulatory Impact
```

---

# 11. Data Exposure

The type of information processed by the supplier is an important risk factor.

Data may include:

```text
Public Information
Internal Information
Confidential Information
Personal Data
Financial Information
Customer Information
Authentication Data
Intellectual Property
Security Information
```

Generally, greater data sensitivity requires stronger controls and due diligence.

---

# 12. System Access

Supplier access to organizational systems can significantly affect risk.

Access levels may include:

```text
No System Access
       ↓
Limited User Access
       ↓
Application Access
       ↓
Privileged Access
       ↓
Administrative Access
```

A supplier with privileged access generally requires stronger security controls and oversight.

---

# 13. Business Criticality

The organization should determine how important the supplier's service is.

For example:

```text
Non-Critical Service
      ↓
Important Service
      ↓
Critical Service
```

A supplier supporting a critical customer-facing platform presents a substantially different risk profile from a supplier providing office stationery.

---

# 14. Regulatory Exposure

Third parties may operate within regulated environments.

Potential regulatory considerations include:

```text
Data Protection
Cybersecurity
Financial Regulation
Operational Resilience
Telecommunications
Healthcare
Critical Infrastructure
Contractual Requirements
```

The organization should determine which regulatory obligations may apply to the supplier relationship.

---

# 15. Geographic Risk

Supplier risk can also be affected by geographic factors.

Consider:

```text
Supplier Headquarters
Data Center Location
Data Processing Location
Support Location
Subcontractor Location
Data Transfer Countries
```

A simplified model is:

```text
Organization
      ↓
Supplier
      ↓
Country A
      ↓
Subcontractor
      ↓
Country B
```

This can create additional legal, privacy, geopolitical, or operational considerations.

---

# 16. Subcontractor Risk

A supplier may use other suppliers.

This creates a fourth-party or subcontractor dependency.

```text
Organization
      ↓
Primary Supplier
      ↓
Subcontractor
      ↓
Sub-subcontractor
```

The organization should understand important downstream dependencies, particularly where critical services or sensitive data are involved.

---

# 17. Stage 4 – Due Diligence

Due diligence evaluates whether the supplier has appropriate capabilities and controls.

It may include:

```text
Security Questionnaire
Certifications
Audit Reports
Penetration Testing
Policies
Business Continuity
Incident Response
Privacy Controls
Financial Information
References
Regulatory Compliance
```

The depth of due diligence should correspond to the supplier's risk classification.

---

# 18. Security Due Diligence

Cybersecurity due diligence may evaluate:

```text
Information Security Governance
Access Control
MFA
Encryption
Vulnerability Management
Security Monitoring
Incident Response
Secure Development
Backup
Business Continuity
Security Testing
```

The objective is to understand whether the supplier's security capabilities are appropriate for the services being provided.

---

# 19. Compliance Due Diligence

Compliance due diligence may examine:

```text
Applicable Regulations
Certifications
Audit Results
Control Frameworks
Regulatory Findings
Privacy Requirements
Contractual Obligations
```

Evidence may include:

```text
ISO 27001 Certificate
SOC 2 Report
Independent Audit Report
Penetration Test
Privacy Documentation
```

The evidence requested should be appropriate to the supplier's risk.

---

# 20. Privacy Due Diligence

Where personal data is processed, the organization should evaluate:

```text
Data Processing Activities
Data Locations
Purpose of Processing
Retention
Deletion
Subprocessors
International Transfers
Security Controls
Data Subject Rights
Incident Notification
```

The supplier's role should be clearly understood within the applicable privacy framework.

---

# 21. Business Continuity Due Diligence

Critical suppliers should also be assessed for resilience.

Questions may include:

```text
Does the supplier have a BCP?

Does the supplier have a DR plan?

What are its RTO and RPO?

How frequently does it test recovery?

Are critical sites geographically separated?

Does it have backup suppliers?

How does it handle major outages?
```

A supplier may have strong cybersecurity controls but still represent significant availability risk if its resilience capability is weak.

---

# 22. Financial Due Diligence

Supplier financial stability can also be relevant.

Potential indicators include:

```text
Financial Statements
Creditworthiness
Liquidity
Market Position
Business Stability
Ownership Changes
Litigation
Bankruptcy Risk
```

Financial failure can cause service interruption even when cybersecurity controls are strong.

---

# 23. Stage 5 – Third-Party Risk Assessment

Following due diligence, the organization evaluates the identified risks.

A simplified model is:

```text
Threat
   ↓
Third-Party Vulnerability
   ↓
Potential Impact
   ↓
Risk
```

For example:

```text
Supplier Cyberattack
        ↓
Weak Privileged Access
        ↓
Unauthorized Access
        ↓
Customer Data Exposure
        ↓
Third-Party Risk
```

---

# 24. Inherent Third-Party Risk

Inherent risk represents the level of risk associated with the supplier relationship **before considering the effectiveness of mitigating controls**.

For example:

```text
Critical Service
+
Sensitive Data
+
Privileged Access
+
External Supplier
        ↓
High Inherent Risk
```

This helps determine the level of control required.

---

# 25. Control Assessment

The organization then evaluates the supplier's controls.

```text
Inherent Risk
      ↓
Supplier Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
```

Controls may include:

```text
MFA
Encryption
Logging
Segmentation
Backup
DR
Security Monitoring
Incident Response
Access Reviews
```

---

# 26. Residual Third-Party Risk

Residual risk is the risk remaining after controls are considered.

A simplified model is:

```text
Inherent Risk
      ↓
Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
```

For example:

```text
Inherent Risk = High

Strong Security Controls
        ↓

Residual Risk = Moderate
```

The organization must determine whether the residual risk is acceptable.

---

# 27. Risk Treatment

If residual risk exceeds the organization's risk appetite, additional treatment may be required.

Options include:

```text
Reduce
Transfer
Avoid
Accept
```

For example:

```text
High Residual Risk
       ↓
Additional Controls
       ↓
Risk Reduced
```

Alternatively:

```text
High Residual Risk
       ↓
Business Cannot Accept
       ↓
Supplier Rejected
```

---

# 28. Risk Acceptance

Risk acceptance should be a formal management decision.

A typical process is:

```text
Risk Identified
      ↓
Risk Assessed
      ↓
Residual Risk
      ↓
Risk Exceeds Appetite
      ↓
Management Decision
      ↓
Accept / Treat / Avoid / Transfer
```

Risk acceptance should be performed by an appropriately authorized risk owner.

---

# 29. Stage 6 – Contracting

Security and risk requirements should be incorporated into contracts where appropriate.

Contractual requirements may include:

```text
Security Controls
Data Protection
Confidentiality
Incident Notification
Audit Rights
Security Testing
Business Continuity
RTO / RPO
Subcontractor Controls
Data Location
Data Deletion
Regulatory Compliance
Termination Rights
```

This converts risk requirements into enforceable obligations where contractually appropriate.

---

# 30. Security Clauses

For higher-risk suppliers, contracts may address:

```text
Access Control
Encryption
MFA
Vulnerability Management
Security Monitoring
Incident Response
Security Assessments
Audit Rights
```

The contract should reflect the actual risk profile rather than applying identical requirements to every supplier.

---

# 31. Incident Notification

Third-party contracts may establish requirements for notifying the organization of security incidents.

A simplified model is:

```text
Supplier Incident
      ↓
Supplier Detection
      ↓
Notification
      ↓
Organization Assessment
      ↓
Incident Response
      ↓
Regulatory / Customer Actions
```

Notification requirements should align with applicable legal, regulatory, and contractual obligations.

---

# 32. Audit Rights

Contracts may provide the organization with appropriate assurance mechanisms.

Examples include:

```text
Audit Rights
Independent Audit Reports
Certification Evidence
Control Assessments
Penetration Test Reports
Security Questionnaires
```

For critical suppliers, independent assurance may be particularly important.

---

# 33. Stage 7 – Third-Party Onboarding

Once the supplier is approved, onboarding begins.

A simplified process is:

```text
Risk Approval
      ↓
Contract Approval
      ↓
Security Requirements
      ↓
Access Provisioning
      ↓
Data / System Integration
      ↓
Security Validation
      ↓
Service Activation
```

Security and compliance requirements should be implemented before or as part of service activation.

---

# 34. Access Provisioning

Supplier access should follow least privilege.

```text
Business Need
      ↓
Required Access
      ↓
Approval
      ↓
Provisioning
      ↓
Monitoring
      ↓
Periodic Review
```

Supplier accounts should not receive broader access than necessary.

---

# 35. Stage 8 – Ongoing Monitoring

Third-party risk management does not end after onboarding.

Continuous monitoring may include:

```text
Security Performance
Compliance Status
Incidents
Service Availability
Risk Changes
Certification Status
Audit Findings
Contract Compliance
Threat Intelligence
Financial Stability
```

The lifecycle becomes:

```text
Onboarding
    ↓
Monitoring
    ↓
Assessment
    ↓
Remediation
    ↓
Monitoring
    ↺
```

---

# 36. Periodic Reassessment

Third parties should be reassessed according to their risk.

For example:

```text
Critical Supplier
      ↓
Annual / More Frequent Assessment

High-Risk Supplier
      ↓
Periodic Assessment

Low-Risk Supplier
      ↓
Longer Review Cycle
```

The actual frequency should be defined by the organization's TPRM methodology.

---

# 37. Event-Driven Reassessment

A reassessment may also be triggered by significant events.

Examples include:

```text
Security Incident
Major Service Outage
Acquisition
Ownership Change
New Subcontractor
New Data Processing
Major Technology Change
Regulatory Change
Certification Expiration
Major Control Failure
```

This is important because supplier risk can change between scheduled reviews.

---

# 38. Third-Party Risk Monitoring

A mature monitoring model may combine:

```text
Internal Assessments
Supplier Reporting
Audit Evidence
Security Ratings
Threat Intelligence
Incident Data
Performance Metrics
Regulatory Information
```

The objective is to identify changes in supplier risk before they become major business problems.

---

# 39. Third-Party Performance

Risk monitoring should not focus exclusively on cybersecurity.

Organizations may also monitor:

```text
Service Availability
SLA Performance
Incident Frequency
Response Time
Open Issues
Audit Findings
Regulatory Breaches
Recovery Test Results
```

This provides a broader view of supplier performance and risk.

---

# 40. Third-Party Risk Indicators

Useful indicators may include:

```text
Number of Critical Suppliers
High-Risk Suppliers
Overdue Assessments
Open High-Risk Findings
Expired Certifications
Supplier Incidents
SLA Breaches
Critical Supplier Concentration
Suppliers Without DR Testing
```

These can feed enterprise GRC dashboards.

---

# 41. Stage 9 – Remediation

If a supplier has control deficiencies, remediation should be tracked.

```text
Finding
   ↓
Risk Assessment
   ↓
Corrective Action
   ↓
Supplier Commitment
   ↓
Due Date
   ↓
Validation
   ↓
Closure
```

High-risk findings should receive appropriate escalation.

---

# 42. Supplier Risk Escalation

A supplier may require escalation when:

```text
Critical Finding
Repeated SLA Failure
Major Security Incident
Unresolved High Risk
Regulatory Breach
Failed DR Test
Expired Certification
```

A simplified escalation model is:

```text
Supplier
   ↓
Business Owner
   ↓
TPRM / GRC
   ↓
Risk Owner
   ↓
Executive Management
```

The exact escalation path depends on governance structure.

---

# 43. Stage 10 – Offboarding

Third-party risk management continues until the supplier relationship is properly terminated.

Offboarding may include:

```text
Service Termination
Access Removal
Credential Revocation
Data Return
Data Deletion
Asset Return
Contract Closure
Subcontractor Notification
Evidence Retention
Final Risk Review
```

A simplified process is:

```text
Termination Decision
       ↓
Access Removal
       ↓
Data Return / Deletion
       ↓
Asset Recovery
       ↓
Contract Closure
       ↓
Final Verification
       ↓
Supplier Offboarded
```

---

# 44. Access Revocation

Supplier access should be removed promptly when the relationship ends.

```text
Contract End
      ↓
Identify Supplier Accounts
      ↓
Disable Accounts
      ↓
Revoke Privileges
      ↓
Revoke Tokens / Certificates
      ↓
Validate Removal
```

Failure to remove supplier access can create unnecessary security exposure.

---

# 45. Data Return and Deletion

Where suppliers hold organizational data, offboarding should address:

```text
Data Return
Data Deletion
Backup Copies
Retention Requirements
Subcontractor Copies
Deletion Evidence
```

The organization should understand what happens to data after the contractual relationship ends.

---

# 46. Supplier Exit Strategy

For critical suppliers, organizations should consider how they would continue operations if the supplier became unavailable.

Potential strategies include:

```text
Alternative Supplier
Internal Capability
Data Portability
Multi-Cloud
Multi-Sourcing
Contractual Exit Assistance
Migration Plan
```

A simplified model is:

```text
Critical Supplier Failure
        ↓
Exit Strategy
        ↓
Alternative Capability
        ↓
Business Continuity
```

This reduces dependency and concentration risk.

---

# 47. Third-Party Concentration Risk

Organizations can become excessively dependent on a small number of suppliers.

For example:

```text
                    Organization
                         ↓
              ┌──────────┼──────────┐
              ↓          ↓          ↓
          Supplier A Supplier B Supplier C
              ↓
        80% of Critical Services
```

This creates concentration risk.

If Supplier A fails, a large portion of the organization may be affected simultaneously.

---

# 48. Fourth-Party Risk

The organization should also consider the supplier's own critical dependencies.

```text
Organization
      ↓
Supplier
      ↓
Fourth Party
      ↓
Technology / Service
```

For example:

```text
Organization
      ↓
Managed Cloud Provider
      ↓
Underlying Cloud Provider
      ↓
Data Center
```

This becomes increasingly important for highly interconnected technology ecosystems.

---

# 49. Third-Party Risk and Business Continuity

Critical suppliers should be incorporated into continuity planning.

```text
Critical Business Service
        ↓
Critical Supplier
        ↓
Supplier Failure
        ↓
Business Impact
        ↓
Continuity Strategy
        ↓
Alternative / Recovery Capability
```

This links TPRM with Business Continuity Management.

---

# 50. Third-Party Risk and Disaster Recovery

Supplier recovery capabilities should align with organizational requirements.

For example:

```text
Organization RTO = 4 Hours
        ↓
Critical Supplier
        ↓
Supplier RTO = 24 Hours
        ↓
Recovery Gap
```

The organization should identify and address this mismatch.

---

# 51. Third-Party Risk and Cybersecurity

Cybersecurity risk may enter through:

```text
Supplier Accounts
Supplier Systems
API Connections
Software
Cloud Services
Remote Access
Data Exchange
Subcontractors
```

A simplified attack path is:

```text
Attacker
   ↓
Supplier
   ↓
Compromise
   ↓
Trusted Connection
   ↓
Organization
   ↓
Business Impact
```

This is why supplier cybersecurity controls must be considered within enterprise risk management.

---

# 52. Third-Party Risk and Privacy

Where suppliers process personal data:

```text
Organization
      ↓
Personal Data
      ↓
Third Party
      ↓
Processing
      ↓
Storage / Transfer
```

The organization should understand:

```text
Purpose
Data Categories
Processing Location
Retention
Subprocessors
Security
Data Subject Rights
Deletion
International Transfers
```

Privacy requirements should be integrated into the TPRM process rather than managed independently.

---

# 53. Third-Party Risk and Compliance

TPRM can provide evidence for multiple compliance requirements.

```text
Regulation
    ↓
Third-Party Requirement
    ↓
Supplier Control
    ↓
Assessment
    ↓
Evidence
    ↓
Compliance Assurance
```

This creates traceability between regulatory obligations and supplier controls.

---

# 54. Third-Party Risk and GRC Platforms

A GRC platform can centralize:

```text
Supplier Inventory
Risk Classification
Assessments
Controls
Evidence
Findings
Remediation
Contracts
Reviews
Approvals
```

A simplified workflow is:

```text
Supplier
   ↓
Risk Tier
   ↓
Assessment
   ↓
Evidence
   ↓
Risk Score
   ↓
Approval
   ↓
Monitoring
   ↓
Reassessment
```

This improves consistency and auditability.

---

# 55. Third-Party Risk Evidence

Important evidence may include:

```text
Supplier Questionnaire
Risk Assessment
Security Certifications
Audit Reports
Penetration Test Results
Contracts
Security Clauses
Privacy Agreements
DR Test Results
Incident Records
Risk Acceptance
Remediation Plans
Monitoring Reports
Offboarding Evidence
```

Evidence should be retained according to the organization's records and compliance requirements.

---

# 56. Third-Party Risk Ownership

TPRM is a shared responsibility.

A simplified responsibility model is:

```text
Business Owner
      ↓
Owns Business Relationship

Procurement
      ↓
Manages Commercial Relationship

Information Security
      ↓
Assesses Security Risk

Privacy
      ↓
Assesses Data Protection Risk

Legal
      ↓
Reviews Contractual Requirements

GRC / Risk
      ↓
Coordinates Risk Governance

Executive Management
      ↓
Approves Significant Risk
```

Responsibilities should be formally defined.

---

# 57. Three Lines and Third-Party Risk

The Three Lines Model can also apply to TPRM.

```text
First Line
Business / Supplier Owners
        ↓
Manage Supplier Risk

Second Line
Risk / GRC / Security / Compliance
        ↓
Oversight and Challenge

Third Line
Internal Audit
        ↓
Independent Assurance
```

This creates appropriate separation between operational ownership and independent assurance.

---

# 58. Third-Party Risk Dashboard

An executive dashboard could show:

```text
        THIRD-PARTY RISK OVERVIEW

Total Suppliers                 428
Critical Suppliers               32
High-Risk Suppliers              61
Overdue Assessments               9
High-Risk Findings               14
Critical Findings                 3
Suppliers Without DR Evidence     7
Expired Certifications            5
Critical Supplier Incidents       2
```

The values are illustrative.

The dashboard should focus attention on material supplier risks rather than simply the number of suppliers.

---

# 59. Third-Party Risk Maturity

TPRM maturity can be represented as:

### Level 1 – Ad Hoc

```text
Limited Supplier Visibility
Reactive Assessments
Minimal Documentation
```

### Level 2 – Developing

```text
Supplier Inventory
Basic Questionnaires
Risk Classification
```

### Level 3 – Defined

```text
Formal TPRM Methodology
Risk-Based Assessments
Contractual Security Requirements
```

### Level 4 – Managed

```text
Continuous Monitoring
Metrics
Automated Workflows
Integrated Risk Management
```

### Level 5 – Optimized

```text
Continuous Risk Intelligence
Automated Risk Signals
Advanced Concentration Analysis
Fourth-Party Visibility
Predictive Risk Management
```

---

# 60. End-to-End Third-Party Risk Lifecycle

A mature TPRM lifecycle can be represented as:

```text
                    BUSINESS NEED
                          ↓
                 SUPPLIER IDENTIFIED
                          ↓
                  INITIAL SCREENING
                          ↓
                    RISK TIERING
                          ↓
                   DUE DILIGENCE
                          ↓
                  RISK ASSESSMENT
                          ↓
                   RISK TREATMENT
                          ↓
                    CONTRACTING
                          ↓
                     ONBOARDING
                          ↓
                 ACCESS / INTEGRATION
                          ↓
                 ONGOING MONITORING
                          ↓
                PERIODIC REASSESSMENT
                          ↓
                  EVENT-DRIVEN REVIEW
                          ↓
                     REMEDIATION
                          ↓
                     OFFBOARDING
                          ↓
                FINAL RISK VERIFICATION
                          ↓
                  LESSONS LEARNED
                          ↺
```

---

# 61. GRC Traceability Model

From a GRC perspective, third-party risk should provide traceability from the business requirement through to assurance.

```text
Business Requirement
        ↓
Third Party
        ↓
Service
        ↓
Risk Classification
        ↓
Inherent Risk
        ↓
Control Requirements
        ↓
Supplier Controls
        ↓
Evidence
        ↓
Residual Risk
        ↓
Risk Treatment
        ↓
Approval
        ↓
Monitoring
        ↓
Testing / Assurance
        ↓
Remediation
        ↓
Management Assurance
```

This traceability allows the organization to demonstrate not only that suppliers were assessed, but that identified risks are actively governed throughout the relationship.

---

# 62. Practical Example – Critical Cloud Provider

Consider a cloud provider supporting a critical business application.

```text
Business Requirement
       ↓
Critical Application
       ↓
Cloud Provider
       ↓
Critical Supplier
       ↓
High Inherent Risk
       ↓
Enhanced Due Diligence
       ↓
Security / Privacy / DR Assessment
       ↓
Contractual Controls
       ↓
Risk Approval
       ↓
Onboarding
       ↓
Continuous Monitoring
       ↓
Periodic Reassessment
       ↓
DR Testing
       ↓
Management Assurance
```

The supplier relationship becomes part of the organization's overall resilience architecture.

---

# 63. Practical Example – Managed Security Provider

Consider a managed security provider with privileged access.

```text
Security Operations Requirement
        ↓
Managed Security Provider
        ↓
Privileged System Access
        ↓
High Inherent Risk
        ↓
Enhanced Security Assessment
        ↓
MFA + PAM + Logging + Monitoring
        ↓
Contractual Security Requirements
        ↓
Ongoing Monitoring
        ↓
Periodic Access Review
        ↓
Risk Reassessment
```

The risk profile is driven not only by the supplier's service but also by the level of access granted.

---

# 64. Practical Example – Customer Data Processor

Consider a supplier processing customer personal data.

```text
Customer Data
      ↓
Third Party
      ↓
Personal Data Processing
      ↓
Privacy Risk
      ↓
Security Assessment
      ↓
Privacy Due Diligence
      ↓
Contractual Requirements
      ↓
Monitoring
      ↓
Periodic Review
      ↓
Secure Deletion at Offboarding
```

This demonstrates the integration between TPRM, cybersecurity, privacy, and compliance.

---

# 65. Key GRC Takeaways

A mature **Third-Party Risk Lifecycle** should establish:

```text
1. Supplier Identification
2. Business Ownership
3. Risk Classification
4. Critical Supplier Identification
5. Due Diligence
6. Cybersecurity Assessment
7. Privacy Assessment
8. Compliance Assessment
9. Business Continuity Assessment
10. Inherent Risk Assessment
11. Control Assessment
12. Residual Risk Assessment
13. Risk Treatment
14. Contractual Requirements
15. Secure Onboarding
16. Access Governance
17. Continuous Monitoring
18. Periodic Reassessment
19. Event-Driven Reassessment
20. Remediation
21. Concentration Risk Management
22. Fourth-Party Risk Management
23. Secure Offboarding
24. Evidence Management
25. Management Assurance
```

The central principle is:

> **Third-party risk management is a continuous lifecycle that ensures external dependencies remain within the organization's risk appetite throughout the entire supplier relationship.**

The complete GRC relationship can therefore be summarized as:

```text
Business Need
      ↓
Supplier
      ↓
Risk
      ↓
Controls
      ↓
Evidence
      ↓
Residual Risk
      ↓
Treatment
      ↓
Approval
      ↓
Monitoring
      ↓
Reassessment
      ↓
Assurance
      ↓
Offboarding
      ↓
Lessons Learned
      ↺
```

A mature organization should be able to answer a fundamental GRC question at any point in the supplier lifecycle:

> **“What third parties create material risk to our organization, what controls are in place, what evidence demonstrates their effectiveness, and who is accountable for the remaining risk?”**


