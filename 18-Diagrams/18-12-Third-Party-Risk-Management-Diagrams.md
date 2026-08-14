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

# 18.12 Third-Party Risk Management Diagrams

## Part 2 – Supplier Due Diligence Process

Supplier due diligence is the process of gathering, validating, and evaluating information about a third party before the organization enters into, or materially expands, a business relationship.

From a GRC perspective, due diligence should answer four fundamental questions:

```text
Who is the supplier?
        ↓
What will the supplier do?
        ↓
What risks does the relationship create?
        ↓
Can those risks be adequately managed?
```

A mature supplier due diligence process is **risk-based**. A low-risk supplier should not be subjected to the same level of scrutiny as a cloud provider processing sensitive customer information or a managed service provider with privileged access to critical systems.

A simplified process is:

```text
Supplier Identified
       ↓
Business Context
       ↓
Risk Classification
       ↓
Due Diligence Scope
       ↓
Information Request
       ↓
Evidence Collection
       ↓
Evidence Validation
       ↓
Risk Analysis
       ↓
Control Gap Assessment
       ↓
Residual Risk
       ↓
Risk Treatment / Acceptance
       ↓
Approval Decision
       ↓
Onboarding
```

---

# 1. Purpose of Supplier Due Diligence

The primary objective is to understand the risks associated with a supplier **before the organization becomes dependent on that supplier**.

Due diligence helps identify risks involving:

```text
Cybersecurity
Privacy
Compliance
Business Continuity
Financial Stability
Operational Resilience
Reputation
Legal Exposure
Geographic Exposure
Subcontractors
Concentration Risk
```

The process therefore supports informed business and risk decisions.

---

# 2. Supplier Due Diligence in the GRC Lifecycle

Supplier due diligence sits between supplier identification and formal risk treatment.

```text
Business Need
      ↓
Supplier Selection
      ↓
Initial Screening
      ↓
Supplier Due Diligence
      ↓
Risk Assessment
      ↓
Risk Treatment
      ↓
Contract
      ↓
Onboarding
```

Due diligence provides the evidence required to perform a meaningful risk assessment.

---

# 3. Risk-Based Due Diligence

The level of due diligence should correspond to supplier risk.

A simplified model is:

```text
Low Risk
   ↓
Basic Screening

Moderate Risk
   ↓
Standard Due Diligence

High Risk
   ↓
Enhanced Due Diligence

Critical Supplier
   ↓
Enhanced + Independent Assurance
```

This prevents the TPRM function from applying unnecessary effort to low-risk suppliers while ensuring material suppliers receive sufficient scrutiny.

---

# 4. Supplier Risk Tiering

Before issuing a detailed questionnaire, the organization should determine the supplier's risk tier.

Possible tiers include:

```text
Tier 1 – Critical
Tier 2 – High
Tier 3 – Moderate
Tier 4 – Low
```

The tier can determine:

```text
Assessment Depth
Evidence Requirements
Approval Level
Review Frequency
Monitoring Intensity
Contractual Requirements
```

---

# 5. Initial Supplier Screening

Initial screening can be performed using a relatively small set of questions.

For example:

```text
Does the supplier process sensitive data?
Does the supplier access internal systems?
Does the supplier have privileged access?
Does the supplier support a critical service?
Is the supplier subject to regulatory requirements?
Does the supplier use subcontractors?
Does the supplier operate internationally?
Would supplier failure materially affect the organization?
```

The answers determine whether enhanced due diligence is required.

---

# 6. Business Context

Due diligence should begin with understanding the business relationship.

The organization should document:

```text
Business Service
Supplier Service
Business Owner
Expected Contract Duration
Criticality
Users
Systems
Data
Locations
Dependencies
```

This provides context for interpreting the supplier's controls.

---

# 7. Service Description

The supplier should clearly describe the services being provided.

For example:

```text
Supplier
   ↓
Cloud Hosting
   ↓
Application Hosting
   ↓
Database Services
   ↓
Customer Data Processing
```

The more complex the service, the more important it becomes to understand its architecture and dependencies.

---

# 8. Data Due Diligence

The organization should identify what information the supplier will access, process, transmit, or store.

Potential categories include:

```text
Public Data
Internal Data
Confidential Data
Personal Data
Financial Data
Authentication Data
Customer Data
Intellectual Property
Security Data
```

The sensitivity of the data should influence the depth of due diligence.

---

# 9. System Access Assessment

Supplier access should be explicitly documented.

A simple model is:

```text
No Access
   ↓
Limited Application Access
   ↓
System Access
   ↓
Administrative Access
   ↓
Privileged Access
```

A supplier with privileged access should generally receive enhanced security scrutiny.

---

# 10. Geographic Assessment

The organization should understand where the supplier operates and where data is processed.

```text
Supplier Headquarters
        ↓
Service Location
        ↓
Data Processing Location
        ↓
Support Location
        ↓
Subcontractor Location
```

Geographic considerations may affect:

```text
Privacy
Data Transfers
Regulatory Compliance
Legal Jurisdiction
Geopolitical Risk
Operational Resilience
```

---

# 11. Supplier Ownership and Corporate Structure

Due diligence should establish who owns and controls the supplier.

Information may include:

```text
Legal Entity
Ownership
Parent Company
Subsidiaries
Major Acquisitions
Corporate Structure
Ultimate Ownership
```

This becomes particularly important when dealing with large multinational suppliers or complex corporate structures.

---

# 12. Financial Due Diligence

Financial instability can create operational risk.

Possible information includes:

```text
Financial Statements
Revenue
Profitability
Liquidity
Credit Rating
Debt
Market Position
Bankruptcy Indicators
```

The objective is not necessarily to perform a complete financial audit but to determine whether the supplier presents material financial continuity risk.

---

# 13. Legal and Regulatory Due Diligence

The organization may review:

```text
Legal Disputes
Regulatory Actions
Licensing
Applicable Regulations
Sanctions Screening
Contractual Restrictions
Compliance History
```

This can help identify legal or regulatory exposure associated with the supplier.

---

# 14. Reputation Due Diligence

Reputational issues can become organizational risks.

Potential sources of concern include:

```text
Major Security Incidents
Regulatory Enforcement
Fraud Allegations
Repeated Service Failures
Public Controversies
Unethical Business Practices
Significant Customer Complaints
```

The organization should assess whether such issues could affect its own reputation or stakeholder confidence.

---

# 15. Cybersecurity Questionnaire

A cybersecurity questionnaire is one of the most common due diligence mechanisms.

It may cover:

```text
Security Governance
Access Management
MFA
Encryption
Vulnerability Management
Patch Management
Security Monitoring
Logging
Incident Response
Secure Development
Backup
Business Continuity
Security Testing
```

The questionnaire should be proportionate to the supplier's risk.

---

# 16. Security Governance Assessment

Questions may examine whether the supplier has:

```text
Information Security Policy
Security Governance Structure
Security Leadership
Risk Management Process
Security Awareness Program
Internal Audit
Security Metrics
Security Incident Management
```

Relevant evidence might include:

```text
Security Policies
Organization Chart
Risk Reports
Security Program Documentation
Audit Reports
```

---

# 17. Identity and Access Management

Supplier access controls should be examined carefully.

The assessment may cover:

```text
MFA
Least Privilege
Privileged Access Management
Joiner-Mover-Leaver Process
Access Reviews
Service Accounts
Password Management
Remote Access
```

A simplified control model is:

```text
User
 ↓
Authentication
 ↓
Authorization
 ↓
Least Privilege
 ↓
Monitoring
 ↓
Periodic Review
```

---

# 18. Data Protection and Encryption

Due diligence should determine how the supplier protects data.

Questions may include:

```text
Is data encrypted in transit?
Is data encrypted at rest?
How are encryption keys managed?
Who can access the keys?
How are backups protected?
How is sensitive data segregated?
```

Evidence may include security architecture documentation and relevant certifications or independent assurance reports.

---

# 19. Vulnerability Management

The supplier should demonstrate how it identifies and addresses vulnerabilities.

A simplified process is:

```text
Identify Vulnerability
       ↓
Assess Severity
       ↓
Prioritize
       ↓
Remediate
       ↓
Validate
       ↓
Monitor
```

For higher-risk suppliers, the organization may request evidence of vulnerability scanning, penetration testing, or remediation practices.

---

# 20. Security Monitoring

The supplier's ability to detect suspicious activity should be assessed.

Controls may include:

```text
Security Monitoring
SIEM
SOC
Threat Detection
Log Management
Alerting
Endpoint Detection
Network Monitoring
```

The objective is to determine whether the supplier can detect and respond to security events affecting the organization's services or information.

---

# 21. Incident Response Due Diligence

The organization should understand how the supplier handles incidents.

A simplified model is:

```text
Detection
   ↓
Analysis
   ↓
Containment
   ↓
Eradication
   ↓
Recovery
   ↓
Notification
   ↓
Lessons Learned
```

Important questions include:

```text
How quickly must the supplier notify us?
Who receives the notification?
How are incidents escalated?
How is evidence preserved?
How are customers informed?
```

---

# 22. Business Continuity Due Diligence

For important suppliers, the organization should evaluate business continuity capabilities.

Questions may include:

```text
Does the supplier have a BCP?
Does it have a DR plan?
What are its RTO and RPO?
How frequently are plans tested?
Are critical facilities redundant?
Are alternative suppliers available?
```

The supplier's resilience should align with the organization's own recovery requirements.

---

# 23. Disaster Recovery Evidence

Possible evidence includes:

```text
DR Plan
Recovery Procedures
DR Test Report
RTO / RPO Documentation
Recovery Architecture
Backup Strategy
Failover Test Results
```

The organization should distinguish between:

**Claim:**

> "We have a disaster recovery plan."

and:

**Evidence:**

> A recent recovery exercise demonstrating that critical services were successfully recovered within defined objectives.

Evidence provides stronger assurance than statements alone.

---

# 24. Privacy Due Diligence

Where personal data is involved, privacy assessment should address:

```text
Data Categories
Processing Purpose
Data Subjects
Processing Locations
Retention
Deletion
Subprocessors
International Transfers
Data Subject Rights
Security Measures
Incident Management
```

The supplier's privacy responsibilities should be clearly established.

---

# 25. Subprocessor Assessment

Suppliers may rely on subcontractors or subprocessors.

The organization should determine:

```text
Who Are the Subprocessors?
What Services Do They Provide?
What Data Do They Access?
Where Are They Located?
What Controls Do They Have?
How Are They Monitored?
```

A simplified chain is:

```text
Organization
      ↓
Supplier
      ↓
Subprocessor
      ↓
Service / Data
```

For critical services, visibility into important downstream dependencies can be essential.

---

# 26. Certifications and Independent Assurance

Supplier certifications can provide useful evidence.

Examples include:

```text
ISO/IEC 27001
ISO 22301
ISO/IEC 27701
SOC 1
SOC 2
PCI DSS
```

However, certification should not automatically be treated as proof that every relevant risk is adequately controlled.

The organization should evaluate:

```text
Scope
Validity
Expiration
Control Coverage
Applicability
Exceptions
Audit Findings
```

---

# 27. Scope Verification

A common GRC mistake is accepting a certificate without checking its scope.

For example:

```text
Supplier
   ↓
ISO 27001 Certificate
   ↓
Check Scope
   ↓
Does Scope Cover Our Service?
   ↓
Yes / No
```

A supplier may have an ISO 27001 certificate covering only a specific business unit, location, or service.

Therefore, **scope matters**.

---

# 28. SOC Report Review

Where a supplier provides a SOC report, reviewers should consider:

```text
Report Type
Reporting Period
Systems Covered
Control Objectives
Testing Performed
Exceptions
Complementary User Entity Controls
```

A SOC report should be evaluated in the context of the organization's specific requirements.

---

# 29. Penetration Testing Evidence

For higher-risk technology suppliers, penetration testing evidence may provide additional assurance.

The review may consider:

```text
Testing Scope
Testing Date
Methodology
Critical Findings
High Findings
Remediation Status
Retesting
```

The organization should avoid requesting sensitive technical details unnecessarily and should define secure evidence-handling procedures.

---

# 30. Supplier Questionnaire Response

A typical questionnaire lifecycle is:

```text
Questionnaire Issued
       ↓
Supplier Completes
       ↓
Evidence Attached
       ↓
GRC Review
       ↓
Clarification Questions
       ↓
Validation
       ↓
Risk Assessment
```

The questionnaire should not become a purely administrative exercise.

The objective is to obtain meaningful risk information.

---

# 31. Evidence Validation

Evidence should be evaluated for:

```text
Authenticity
Relevance
Currency
Scope
Completeness
Applicability
```

For example:

```text
Supplier Provides Certificate
        ↓
Check Issuing Organization
        ↓
Check Expiration
        ↓
Check Scope
        ↓
Check Service Coverage
        ↓
Accept as Evidence
```

---

# 32. Evidence Age

Evidence should be sufficiently current for the risk being assessed.

For example:

```text
Old Evidence
     ↓
May Not Represent
Current Controls
```

Therefore, assessment methodology should define acceptable evidence age where appropriate.

---

# 33. Control Gap Assessment

The organization compares required controls with available supplier controls.

```text
Required Control
       ↓
Supplier Control
       ↓
Evidence
       ↓
Effective?
       ↓
Yes / No / Partial
```

This identifies gaps requiring treatment.

---

# 34. Supplier Risk Scoring

A risk scoring model may combine:

```text
Business Criticality
Data Sensitivity
System Access
Regulatory Exposure
Security Posture
Resilience
Financial Risk
Geographic Risk
```

For example:

```text
Risk Score
    =
Impact × Likelihood
```

The exact methodology should be defined by the organization's enterprise risk framework.

---

# 35. Inherent Risk vs. Residual Risk

Due diligence should distinguish between the two.

```text
                 INHERENT RISK
                      ↓
               Supplier Exposure
                      ↓
              Supplier Controls
                      ↓
             Control Effectiveness
                      ↓
                RESIDUAL RISK
```

This distinction prevents organizations from assuming that a supplier with strong controls has no risk.

---

# 36. Risk Treatment Decision

Following assessment:

```text
Residual Risk
      ↓
Compare With Risk Appetite
      ↓
Within Appetite?
   ↙           ↘
 Yes            No
 ↓               ↓
Approve      Treat / Transfer /
             Avoid / Accept
```

The decision should be documented.

---

# 37. Risk Acceptance

If the organization accepts residual risk, the acceptance should normally identify:

```text
Risk
Risk Owner
Business Justification
Risk Level
Expiration / Review Date
Compensating Controls
Approval Authority
```

This creates accountability for the decision.

---

# 38. Contractual Risk Treatment

Some identified risks can be addressed through contractual requirements.

For example:

```text
Risk
 ↓
Contractual Requirement
 ↓
Supplier Obligation
 ↓
Monitoring
 ↓
Evidence
```

Examples include:

```text
Incident Notification
Audit Rights
Security Requirements
Data Deletion
Business Continuity
Subprocessor Notification
```

---

# 39. Supplier Due Diligence Approval

A formal approval model may look like:

```text
Due Diligence Complete
        ↓
Risk Assessment
        ↓
Findings Identified
        ↓
Treatment / Acceptance
        ↓
Business Owner Approval
        ↓
Risk / GRC Approval
        ↓
Security / Privacy / Legal Approval
        ↓
Supplier Approved
```

The exact approval chain depends on organizational governance.

---

# 40. Conditional Approval

Not every supplier needs to be fully risk-free before onboarding.

An organization may provide conditional approval when:

```text
Residual Risk Is Known
        +
Remediation Plan Exists
        +
Risk Owner Accepts
        +
Due Dates Are Defined
```

For example:

```text
Supplier Approved
      ↓
Condition:
Implement MFA Within 60 Days
      ↓
Monitoring
      ↓
Validation
```

This should not become a mechanism for indefinitely postponing critical remediation.

---

# 41. Supplier Due Diligence Exceptions

Exceptions may occur when:

```text
Supplier Cannot Provide Evidence
Legacy Supplier
Emergency Procurement
Unique Technology
Limited Market Alternatives
```

Exceptions should be documented and risk-assessed rather than ignored.

---

# 42. Emergency Supplier Onboarding

Sometimes a business cannot wait for the full due diligence process.

A controlled emergency process may be:

```text
Urgent Business Need
       ↓
Initial Risk Screening
       ↓
Temporary Approval
       ↓
Minimum Security Controls
       ↓
Service Activation
       ↓
Full Due Diligence
       ↓
Final Approval
```

Emergency processes should have defined time limits and governance.

---

# 43. Due Diligence and Procurement

TPRM should integrate with procurement.

```text
Business Requirement
        ↓
Procurement
        ↓
Supplier Shortlist
        ↓
TPRM Screening
        ↓
Due Diligence
        ↓
Risk Assessment
        ↓
Commercial Evaluation
        ↓
Supplier Selection
```

This prevents cybersecurity and compliance reviews from becoming an afterthought after a supplier has already been selected.

---

# 44. Due Diligence and Legal Review

Legal and GRC activities should also be coordinated.

```text
Due Diligence
      ↓
Risk Requirements
      ↓
Contract Clauses
      ↓
Legal Review
      ↓
Negotiation
      ↓
Contract Execution
```

This helps translate identified risks into enforceable contractual obligations where appropriate.

---

# 45. Due Diligence and GRC Platforms

A GRC platform can automate much of the process.

```text
Supplier Record
      ↓
Risk Tier
      ↓
Questionnaire
      ↓
Evidence Collection
      ↓
Assessment
      ↓
Risk Score
      ↓
Approval
      ↓
Monitoring
```

Automation can improve:

```text
Consistency
Traceability
Workflow Management
Evidence Management
Reporting
Auditability
```

---

# 46. Automated Evidence Collection

Where technically and contractually appropriate, evidence can be collected or monitored automatically.

Examples include:

```text
Certificate Expiration
Security Ratings
Public Breach Information
Questionnaire Status
Assessment Due Dates
Contract Expiration
Risk Findings
```

Automation should support—not replace—professional risk judgment.

---

# 47. Due Diligence Dashboard

A GRC dashboard could display:

```text
        SUPPLIER DUE DILIGENCE

Suppliers Under Assessment          24
High-Risk Assessments               11
Critical Suppliers                   7
Assessments Overdue                  5
Evidence Gaps                       13
High-Risk Findings                   4
Conditional Approvals                3
Expired Certifications               2
```

The figures are illustrative.

Management should be able to quickly identify where supplier risk requires attention.

---

# 48. Due Diligence Evidence Repository

A centralized repository may contain:

```text
Supplier Profile
Questionnaires
Certificates
Audit Reports
Penetration Tests
BCP / DR Evidence
Privacy Documentation
Contracts
Risk Assessments
Risk Acceptances
Remediation Plans
Approval Records
```

This creates a single source of truth for supplier assurance.

---

# 49. Three Lines in Supplier Due Diligence

The Three Lines Model can be applied to the process.

```text
FIRST LINE
Business / Procurement
        ↓
Own Supplier Relationship

SECOND LINE
GRC / Risk / Security / Privacy
        ↓
Assess and Challenge Risk

THIRD LINE
Internal Audit
        ↓
Independent Assurance
```

This helps prevent the supplier owner from being the only party determining whether supplier risk is acceptable.

---

# 50. Due Diligence Quality

A high-quality assessment should be:

```text
Risk-Based
Evidence-Based
Documented
Consistent
Proportionate
Current
Traceable
Repeatable
```

A poor assessment often looks like:

```text
Questionnaire Sent
       ↓
Supplier Answers "Yes"
       ↓
Assessment Approved
```

A stronger process is:

```text
Requirement
      ↓
Supplier Response
      ↓
Evidence
      ↓
Validation
      ↓
Control Assessment
      ↓
Risk Analysis
      ↓
Decision
```

---

# 51. Common Due Diligence Weaknesses

Organizations frequently encounter problems such as:

```text
Incomplete Supplier Inventory
Generic Questionnaires
No Risk Tiering
Insufficient Evidence
Expired Certifications
No Scope Validation
No Subprocessor Visibility
No Business Continuity Review
No Contractual Enforcement
No Follow-Up on Findings
No Periodic Reassessment
```

These weaknesses can create a false sense of assurance.

---

# 52. Avoiding Questionnaire Fatigue

Suppliers may be required to complete questionnaires for many customers.

Organizations can reduce unnecessary burden by using:

```text
Risk-Based Questionnaires
Standardized Frameworks
Existing Certifications
Independent Assurance Reports
Reusable Evidence
Targeted Follow-Up Questions
```

However, standardized evidence should still be evaluated against the organization's specific risks.

---

# 53. Critical Supplier Enhanced Due Diligence

For critical suppliers, the process may include:

```text
Detailed Questionnaire
       ↓
Security Architecture Review
       ↓
Independent Assurance
       ↓
Business Continuity Review
       ↓
DR Test Evidence
       ↓
Subprocessor Assessment
       ↓
Concentration Risk
       ↓
Executive Risk Review
```

The exact requirements depend on the organization's risk appetite and regulatory environment.

---

# 54. Example – Cloud Provider Due Diligence

A practical assessment could look like:

```text
Cloud Provider
      ↓
Critical Service?
      ↓
Yes
      ↓
Processes Sensitive Data?
      ↓
Yes
      ↓
Privileged Access?
      ↓
Yes
      ↓
Enhanced Due Diligence
      ↓
ISO / SOC Evidence
      ↓
Architecture Review
      ↓
Security Assessment
      ↓
Privacy Assessment
      ↓
DR Assessment
      ↓
Subprocessor Review
      ↓
Risk Decision
```

This is substantially more appropriate than using a simple generic vendor questionnaire.

---

# 55. Example – Low-Risk Office Supplier

A low-risk supplier might follow a much simpler path:

```text
Office Supply Supplier
      ↓
No Sensitive Data
      ↓
No System Access
      ↓
Non-Critical Service
      ↓
Low Risk
      ↓
Basic Screening
      ↓
Standard Procurement Controls
      ↓
Approval
```

This demonstrates the principle of proportionality.

---

# 56. Example – Managed Security Provider

A managed security provider with privileged access may require:

```text
Managed Security Provider
        ↓
Privileged Access
        ↓
Critical Security Service
        ↓
High / Critical Risk
        ↓
Enhanced Due Diligence
        ↓
PAM / MFA Assessment
        ↓
SOC Capability Review
        ↓
Incident Response Review
        ↓
Security Monitoring
        ↓
BCP / DR
        ↓
Contractual Controls
        ↓
Executive Risk Approval
```

---

# 57. End-to-End Supplier Due Diligence Model

The complete process can be visualized as:

```text
                  SUPPLIER IDENTIFIED
                          ↓
                   BUSINESS CONTEXT
                          ↓
                  INITIAL SCREENING
                          ↓
                    RISK TIERING
                          ↓
              ┌───────────┴───────────┐
              ↓                       ↓
          LOW / MODERATE          HIGH / CRITICAL
              ↓                       ↓
       STANDARD REVIEW          ENHANCED REVIEW
              └───────────┬───────────┘
                          ↓
                  INFORMATION REQUEST
                          ↓
                  EVIDENCE COLLECTION
                          ↓
                  EVIDENCE VALIDATION
                          ↓
                  CONTROL ASSESSMENT
                          ↓
                    RISK ANALYSIS
                          ↓
                  RESIDUAL RISK
                          ↓
                RISK APPETITE TEST
                          ↓
             ┌────────────┴────────────┐
             ↓                         ↓
        ACCEPTABLE                 NOT ACCEPTABLE
             ↓                         ↓
          APPROVE              TREAT / ACCEPT / AVOID
             └────────────┬────────────┘
                          ↓
                     CONTRACTING
                          ↓
                      ONBOARDING
```

---

# 58. GRC Traceability

Supplier due diligence should create a traceable chain:

```text
Business Requirement
        ↓
Supplier
        ↓
Service
        ↓
Risk Tier
        ↓
Due Diligence Requirement
        ↓
Supplier Response
        ↓
Evidence
        ↓
Control Assessment
        ↓
Risk Finding
        ↓
Risk Treatment
        ↓
Risk Acceptance / Approval
```

This allows an auditor, risk manager, or executive to trace **why a supplier was approved and what evidence supported the decision**.

---

# 59. Key GRC Takeaways

A mature **Supplier Due Diligence Process** should establish:

```text
1. Clear Supplier Identification
2. Business Context
3. Risk-Based Classification
4. Proportionate Due Diligence
5. Cybersecurity Assessment
6. Privacy Assessment
7. Compliance Assessment
8. Business Continuity Assessment
9. Financial Assessment
10. Geographic Assessment
11. Subprocessor Assessment
12. Security Evidence Collection
13. Evidence Validation
14. Control Gap Identification
15. Inherent Risk Assessment
16. Residual Risk Assessment
17. Risk Treatment
18. Formal Approval
19. Contractual Risk Requirements
20. Documented Exceptions
21. Auditability
22. Ongoing Monitoring
```

The central principle is:

> **Supplier due diligence should provide sufficient, evidence-based information for the organization to make an informed decision about whether the supplier's risks are understood and can be managed within the organization's risk appetite.**

The strongest GRC model is therefore not:

```text
Questionnaire
      ↓
Approval
```

but:

```text
Supplier
   ↓
Business Context
   ↓
Risk Classification
   ↓
Due Diligence
   ↓
Evidence
   ↓
Validation
   ↓
Risk Assessment
   ↓
Control Gaps
   ↓
Risk Treatment
   ↓
Management Decision
   ↓
Documented Assurance
```

# 18.12 Third-Party Risk Management Diagrams

## Part 3 – Third-Party Risk Assessment Model

Third-party risk assessment is the process of determining the level of risk created by an external supplier, service provider, partner, or other third party.

While due diligence focuses primarily on **collecting and validating information**, the risk assessment process uses that information to determine:

```text
What can go wrong?
        ↓
How likely is it?
        ↓
What would be the impact?
        ↓
What controls exist?
        ↓
How effective are those controls?
        ↓
What risk remains?
        ↓
Is the remaining risk acceptable?
```

A mature third-party risk assessment therefore connects **business criticality, data exposure, access, threats, vulnerabilities, controls, and residual risk** into a structured decision-making model.

---

# 1. Purpose of Third-Party Risk Assessment

The primary purpose is to determine whether a supplier relationship creates a level of risk that the organization can accept and manage.

The assessment should help answer:

```text
Who is the third party?
        ↓
What does the third party provide?
        ↓
What does the third party have access to?
        ↓
What could go wrong?
        ↓
What controls are available?
        ↓
How effective are those controls?
        ↓
What risk remains?
```

The output should be a **documented risk decision**, not simply a questionnaire score.

---

# 2. Third-Party Risk Assessment in the TPRM Lifecycle

The assessment typically occurs after supplier due diligence.

```text
Supplier Identification
        ↓
Risk Screening
        ↓
Due Diligence
        ↓
Third-Party Risk Assessment
        ↓
Risk Treatment
        ↓
Approval
        ↓
Contracting
        ↓
Onboarding
        ↓
Monitoring
```

The assessment converts information gathered during due diligence into a structured risk view.

---

# 3. Core Third-Party Risk Assessment Model

A simplified model is:

```text
              BUSINESS CONTEXT
                     ↓
              SUPPLIER EXPOSURE
                     ↓
              THREAT / VULNERABILITY
                     ↓
                INHERENT RISK
                     ↓
               SUPPLIER CONTROLS
                     ↓
             CONTROL EFFECTIVENESS
                     ↓
                RESIDUAL RISK
                     ↓
              RISK APPETITE TEST
                     ↓
              MANAGEMENT DECISION
```

This model should be applied consistently across suppliers while allowing the depth of assessment to vary according to risk.

---

# 4. Business Context

The first step is understanding why the supplier exists and what business service it supports.

Key information includes:

```text
Business Service
Supplier Service
Business Owner
Criticality
Contract Value
Contract Duration
Users
Systems
Data
Locations
Dependencies
```

Without business context, it is difficult to determine whether a particular supplier control weakness is actually material.

---

# 5. Supplier Exposure

Supplier exposure describes how closely the third party is connected to the organization.

Potential exposure includes:

```text
Data Access
System Access
Privileged Access
Network Connectivity
API Connectivity
Physical Access
Remote Access
Operational Dependency
Regulatory Dependency
```

A supplier with no access to organizational systems presents a very different exposure profile from a supplier operating a critical cloud environment.

---

# 6. Data Exposure

Data sensitivity is a major factor in third-party risk.

A simplified hierarchy is:

```text
Public
   ↓
Internal
   ↓
Confidential
   ↓
Sensitive
   ↓
Highly Sensitive / Regulated
```

The assessment should consider:

```text
Type of Data
Volume of Data
Data Subjects
Processing Activities
Storage
Transmission
Retention
Deletion
```

---

# 7. System Access

The level of access granted to a supplier should be explicitly considered.

```text
No Access
    ↓
Application Access
    ↓
System Access
    ↓
Remote Access
    ↓
Administrative Access
    ↓
Privileged Access
```

Greater access generally increases potential impact if the supplier is compromised.

---

# 8. Business Criticality

The organization should determine how important the supplier is to business operations.

For example:

```text
Low Criticality
      ↓
Important Service
      ↓
Business-Critical Service
      ↓
Mission-Critical Service
```

A supplier supporting a critical customer platform may therefore require substantially stronger assurance than a supplier providing a non-critical administrative service.

---

# 9. Operational Dependency

Risk is also affected by how dependent the organization is on the supplier.

Consider:

```text
Can the supplier be replaced quickly?

Are alternative suppliers available?

How long would migration take?

Is the organization technically dependent on the supplier?

Does the supplier provide a unique capability?
```

A supplier that cannot easily be replaced may create significant dependency risk.

---

# 10. Regulatory Exposure

The assessment should identify whether the supplier relationship affects regulatory obligations.

Potential areas include:

```text
Data Protection
Cybersecurity
Financial Regulation
Operational Resilience
Telecommunications
Healthcare
Critical Infrastructure
Contractual Compliance
```

The assessment should identify which obligations are relevant to the specific relationship.

---

# 11. Geographic Exposure

Geography can influence third-party risk.

Consider:

```text
Supplier Headquarters
Data Center Location
Processing Location
Support Location
Subcontractor Location
Data Transfer Locations
```

Potential risks include:

```text
Regulatory Conflict
Data Transfer Restrictions
Geopolitical Risk
Operational Disruption
Legal Jurisdiction
```

---

# 12. Subcontractor Exposure

Third-party risk may extend beyond the primary supplier.

```text
Organization
      ↓
Supplier
      ↓
Subcontractor
      ↓
Fourth Party
```

The assessment should consider whether important services or sensitive data depend on downstream providers.

---

# 13. Threat Assessment

The organization should identify relevant threats.

Examples include:

```text
Cyberattack
Ransomware
Insider Threat
Credential Theft
Supply Chain Attack
Data Breach
Service Outage
Fraud
Natural Disaster
Geopolitical Event
Financial Failure
```

Threats should be relevant to the supplier's actual service and exposure.

---

# 14. Vulnerability Assessment

Threats alone do not determine risk.

The organization should also consider vulnerabilities.

Examples include:

```text
Weak Authentication
Excessive Privileges
Poor Patch Management
Insufficient Monitoring
Weak Encryption
Inadequate Backup
Poor Incident Response
Insufficient Segmentation
Weak Supplier Governance
```

A simplified relationship is:

```text
Threat
   +
Vulnerability
   ↓
Potential Risk Event
```

---

# 15. Threat–Vulnerability–Impact Model

A useful third-party risk model is:

```text
Threat
  ↓
Vulnerability
  ↓
Risk Event
  ↓
Impact
```

For example:

```text
Cyberattacker
      ↓
Weak Supplier MFA
      ↓
Supplier Account Compromise
      ↓
Unauthorized Access
      ↓
Customer Data Exposure
      ↓
Financial / Regulatory / Reputational Impact
```

This provides a more meaningful assessment than simply assigning a generic supplier score.

---

# 16. Impact Assessment

Impact describes the consequences if the risk materializes.

Potential impact categories include:

```text
Confidentiality
Integrity
Availability
Privacy
Financial
Regulatory
Legal
Operational
Reputational
Strategic
```

A single supplier event can affect several categories simultaneously.

---

# 17. Impact Scale

An organization may use a scale such as:

```text
1 – Insignificant
2 – Minor
3 – Moderate
4 – Major
5 – Severe
```

For example:

```text
Customer Data Breach
        ↓
Privacy Impact = 5
Regulatory Impact = 5
Reputational Impact = 4
Financial Impact = 4
Operational Impact = 3
```

The actual scoring criteria should be defined within the organization's risk methodology.

---

# 18. Likelihood Assessment

Likelihood estimates how probable it is that the risk event will occur.

A simple scale may be:

```text
1 – Rare
2 – Unlikely
3 – Possible
4 – Likely
5 – Almost Certain
```

Factors may include:

```text
Threat Activity
Supplier Exposure
Control Weaknesses
Historical Incidents
Attack Surface
Industry Threats
Supplier Security Maturity
```

---

# 19. Inherent Risk

Inherent risk represents the risk **before considering mitigating controls**.

A simplified representation is:

```text
Threat
   +
Exposure
   +
Vulnerability
   +
Impact
   ↓
INHERENT RISK
```

For example:

```text
Critical Supplier
+
Sensitive Customer Data
+
Privileged Access
+
External Connectivity
        ↓
High Inherent Risk
```

This provides a baseline against which control effectiveness can be evaluated.

---

# 20. Inherent Risk Scoring

A common conceptual model is:

```text
Inherent Risk = Likelihood × Impact
```

For example:

```text
Likelihood = 4
Impact = 5

Inherent Risk = 4 × 5 = 20
```

The resulting score would then be mapped to the organization's defined risk categories.

---

# 21. Supplier Control Assessment

Once inherent risk is established, the organization evaluates the controls implemented by the supplier.

Examples include:

```text
MFA
Privileged Access Management
Encryption
Network Segmentation
Vulnerability Management
Security Monitoring
Incident Response
Backup
Disaster Recovery
Security Awareness
Access Reviews
```

The key question is:

> **Are the supplier's controls sufficient to reduce the identified risks?**

---

# 22. Control Effectiveness

Controls should not simply be recorded as present or absent.

A more useful assessment considers:

```text
Control Design
      ↓
Control Implementation
      ↓
Control Operation
      ↓
Control Effectiveness
```

For example:

```text
MFA Policy Exists
        ↓
MFA Implemented
        ↓
MFA Applied to Critical Accounts
        ↓
MFA Effectiveness Validated
```

This provides stronger assurance.

---

# 23. Control Maturity

A supplier control can also be assessed by maturity.

For example:

```text
Level 1 – Ad Hoc
Level 2 – Developing
Level 3 – Defined
Level 4 – Managed
Level 5 – Optimized
```

A supplier may technically have a control while still having low maturity.

---

# 24. Control Gaps

The assessment should identify differences between required and actual controls.

```text
Required Control
       ↓
Supplier Control
       ↓
Comparison
       ↓
Gap Identified
```

For example:

```text
Requirement:
MFA for Privileged Access

Supplier:
MFA Available Only for Standard Users

       ↓

Control Gap
```

The gap then becomes part of the risk treatment process.

---

# 25. Compensating Controls

A supplier may not implement the exact expected control but may have another mechanism that reduces the risk.

For example:

```text
Expected Control
       ↓
MFA

Not Available
       ↓
Strong Network Isolation
+
Privileged Access Gateway
+
Additional Monitoring
```

These may provide compensating protection, depending on the specific risk.

Compensating controls should be formally evaluated rather than automatically accepted.

---

# 26. Residual Risk

After considering controls, the organization determines the remaining risk.

```text
Inherent Risk
      ↓
Mitigating Controls
      ↓
Control Effectiveness
      ↓
RESIDUAL RISK
```

For example:

```text
Inherent Risk = High

Strong Controls
      ↓

Residual Risk = Moderate
```

Residual risk is the key risk level used for management decision-making.

---

# 27. Residual Risk and Risk Appetite

The organization should compare residual risk against its defined risk appetite.

```text
Residual Risk
      ↓
Risk Appetite
      ↓
Within Appetite?
```

If yes:

```text
Approve / Continue
```

If no:

```text
Treat
Transfer
Avoid
or
Formally Accept
```

---

# 28. Third-Party Risk Heat Map

A typical risk matrix can be represented as:

```text
                    IMPACT
              Low   Medium   High   Critical
           ┌───────┬────────┬───────┬─────────┐
Rare       │ Low   │ Low    │ Low   │ Medium  │
           ├───────┼────────┼───────┼─────────┤
Unlikely   │ Low   │ Low    │Medium │ High    │
           ├───────┼────────┼───────┼─────────┤
Possible   │ Low   │Medium  │ High  │ High    │
           ├───────┼────────┼───────┼─────────┤
Likely     │Medium │ High   │ High  │ Critical│
           ├───────┼────────┼───────┼─────────┤
Almost     │ High  │ High   │Critical│Critical│
Certain    │       │        │        │        │
           └───────┴────────┴────────┴─────────┘
```

The matrix is illustrative. Organizations should use their approved risk methodology.

---

# 29. Multi-Dimensional Third-Party Risk

Third-party risk should not always be reduced to one number.

A supplier may have:

```text
Cybersecurity Risk       High
Privacy Risk             High
Operational Risk         Medium
Financial Risk           Low
Regulatory Risk          High
Reputational Risk        Medium
```

This provides a more useful view than a single aggregate score.

---

# 30. Third-Party Risk Profile

A supplier risk profile could therefore look like:

```text
        THIRD-PARTY RISK PROFILE

Cybersecurity       █████████ High
Privacy             █████████ High
Operational         ██████    Medium
Regulatory          ████████  High
Financial           ███       Low
Reputation          █████     Medium
Concentration       ███████   High
```

The values are illustrative.

This allows management to understand **what type of risk** the supplier creates.

---

# 31. Critical Supplier Assessment

Critical suppliers should normally receive enhanced assessment.

A simplified model is:

```text
Critical Supplier
       ↓
Business Impact Analysis
       ↓
Enhanced Due Diligence
       ↓
Cybersecurity Assessment
       ↓
Privacy Assessment
       ↓
Resilience Assessment
       ↓
Subcontractor Assessment
       ↓
Concentration Analysis
       ↓
Residual Risk
       ↓
Executive Review
```

---

# 32. Third-Party Risk and Business Impact

A supplier assessment should connect supplier failure to business consequences.

```text
Supplier Failure
       ↓
Service Disruption
       ↓
Business Process Impact
       ↓
Customer Impact
       ↓
Financial / Regulatory Impact
```

This helps convert technical supplier issues into business risk.

---

# 33. Third-Party Risk and Business Continuity

For critical suppliers:

```text
Supplier
   ↓
Service
   ↓
Business Process
   ↓
Criticality
   ↓
RTO / RPO
   ↓
Supplier Recovery Capability
```

The organization should determine whether supplier recovery capabilities are compatible with its own continuity objectives.

---

# 34. Third-Party Risk and Cybersecurity

Cybersecurity risk can be assessed across several domains:

```text
Governance
Identity
Data Protection
Infrastructure
Application Security
Monitoring
Incident Response
Vulnerability Management
Resilience
```

This provides a structured cybersecurity risk profile for the supplier.

---

# 35. Third-Party Risk and Privacy

Privacy risk assessment can follow:

```text
Personal Data
      ↓
Processing Activity
      ↓
Supplier
      ↓
Processing Risk
      ↓
Privacy Controls
      ↓
Residual Privacy Risk
```

Relevant considerations include:

```text
Data Minimization
Purpose Limitation
Retention
Access
Encryption
Subprocessors
International Transfers
Data Subject Rights
Deletion
```

---

# 36. Third-Party Risk and Compliance

Compliance risk can be represented as:

```text
Regulatory Requirement
       ↓
Supplier Obligation
       ↓
Supplier Control
       ↓
Evidence
       ↓
Assessment
       ↓
Compliance Risk
```

This creates traceability between external suppliers and organizational compliance obligations.

---

# 37. Third-Party Risk and Concentration

Risk can increase when multiple critical services depend on the same provider.

```text
Business Service A ──┐
Business Service B ──┤
Business Service C ──┼── Supplier X
Business Service D ──┤
Business Service E ──┘
```

If Supplier X fails, multiple business services may be affected simultaneously.

Therefore, concentration should be incorporated into the risk assessment.

---

# 38. Fourth-Party Risk

The assessment should consider significant downstream dependencies.

```text
Organization
      ↓
Supplier A
      ↓
Supplier B
      ↓
Supplier C
```

The organization does not necessarily need complete visibility into every downstream provider, but critical dependencies should be understood where they materially affect risk.

---

# 39. Risk Treatment Options

Once residual risk has been determined, treatment options include:

```text
Reduce
Transfer
Avoid
Accept
```

### Reduce

Implement additional controls.

### Transfer

Use insurance, contractual mechanisms, or other risk-transfer mechanisms where appropriate.

### Avoid

Do not proceed with the supplier relationship or discontinue the service.

### Accept

Formally accept the remaining risk at the appropriate authority level.

---

# 40. Risk Treatment Plan

A treatment plan should identify:

```text
Risk
Control Gap
Action
Responsible Owner
Supplier Owner
Due Date
Target Risk
Status
Evidence
```

A simplified workflow is:

```text
Risk
 ↓
Treatment Action
 ↓
Implementation
 ↓
Validation
 ↓
Residual Risk
 ↓
Closure / Acceptance
```

---

# 41. Third-Party Risk Acceptance

Risk acceptance should be performed by the appropriate risk owner.

A typical structure is:

```text
Risk Identified
      ↓
Risk Assessed
      ↓
Residual Risk
      ↓
Risk Owner Review
      ↓
Accept / Reject / Treat
      ↓
Formal Documentation
```

The acceptance decision should include sufficient justification.

---

# 42. Risk Escalation

Escalation may be required when:

```text
Residual Risk > Risk Appetite
Critical Control Gap
Major Security Exposure
Regulatory Concern
Critical Supplier Dependency
Unresolved High-Risk Finding
```

A possible escalation path is:

```text
Supplier Owner
      ↓
GRC / Risk
      ↓
Security / Privacy / Compliance
      ↓
Business Leadership
      ↓
Executive Risk Committee
```

---

# 43. Risk Assessment Frequency

Assessment frequency should reflect supplier risk.

```text
Critical Supplier
      ↓
Continuous / Frequent Monitoring
+
Periodic Full Assessment

High Risk
      ↓
Periodic Assessment

Moderate Risk
      ↓
Scheduled Reassessment

Low Risk
      ↓
Simplified Review
```

The exact frequency should be established in the organization's TPRM methodology.

---

# 44. Event-Driven Reassessment

A new assessment may be triggered by significant changes.

Examples:

```text
Cybersecurity Incident
Major Service Change
New Data Processing
New Subprocessor
Acquisition
Ownership Change
Regulatory Change
Major Vulnerability
Security Certification Expiration
Business Model Change
```

Therefore:

```text
Scheduled Assessment
        +
Event-Driven Assessment
        ↓
Continuous Risk Management
```

---

# 45. Third-Party Risk Monitoring

Monitoring should track changes in the supplier's risk profile.

Possible indicators include:

```text
Security Incidents
Open Findings
Certification Status
Service Availability
Security Rating
Compliance Issues
DR Test Results
SLA Performance
Financial Condition
Threat Intelligence
```

These indicators can trigger reassessment when risk changes materially.

---

# 46. Third-Party Risk Dashboard

An executive dashboard could provide:

```text
       THIRD-PARTY RISK PROFILE

Critical Suppliers                32
High-Risk Suppliers               61
Critical Risks                     4
High Risks                        17
Open High Findings                23
Overdue Assessments                9
Suppliers With Major Incidents     3
Concentration Risks                5
```

The figures are illustrative.

The dashboard should emphasize **material risk and trends**, not simply supplier counts.

---

# 47. Supplier Risk Scorecard

A supplier scorecard could combine multiple dimensions:

```text
Supplier
     ↓
Cybersecurity
Privacy
Compliance
Resilience
Financial
Operational
Reputation
Concentration
     ↓
Overall Risk Profile
```

This gives decision-makers a consolidated view while preserving the underlying risk dimensions.

---

# 48. Risk Assessment Evidence

Important assessment evidence may include:

```text
Completed Questionnaire
Security Certifications
Audit Reports
Penetration Tests
Architecture Documents
DR Test Results
Privacy Documentation
Incident Records
Risk Assessment
Control Assessment
Risk Acceptance
Remediation Plan
```

Evidence should support the actual risk conclusions.

---

# 49. Evidence-to-Risk Traceability

A mature assessment should be able to trace:

```text
Risk
 ↓
Control
 ↓
Evidence
 ↓
Assessment Result
 ↓
Residual Risk
 ↓
Decision
```

For example:

```text
Risk:
Unauthorized Privileged Access

Control:
MFA + PAM

Evidence:
Access Review + PAM Report

Assessment:
Effective

Residual Risk:
Moderate

Decision:
Accept
```

This makes the assessment auditable.

---

# 50. Three Lines and Third-Party Risk Assessment

The Three Lines Model provides governance around assessment activities.

```text
FIRST LINE
Business / Supplier Owner
        ↓
Owns Risk

SECOND LINE
GRC / Risk / Security / Privacy
        ↓
Assesses and Challenges

THIRD LINE
Internal Audit
        ↓
Provides Independent Assurance
```

This separation helps prevent conflicts of interest.

---

# 51. GRC Platform Risk Assessment Workflow

A GRC platform may automate the workflow:

```text
Supplier Record
       ↓
Risk Tier
       ↓
Assessment Questionnaire
       ↓
Evidence
       ↓
Risk Calculation
       ↓
Control Assessment
       ↓
Findings
       ↓
Treatment
       ↓
Approval
       ↓
Monitoring
```

This improves consistency and creates an auditable record.

---

# 52. Automated Risk Scoring

Automation can calculate preliminary risk scores based on defined criteria.

For example:

```text
Criticality
    +
Data Sensitivity
    +
System Access
    +
Regulatory Exposure
    +
Supplier Control Maturity
    ↓
Calculated Risk Profile
```

However, automated scoring should not eliminate professional judgment.

A high score should trigger analysis—not automatically determine the final decision.

---

# 53. Human Judgment in Risk Assessment

Certain situations require professional judgment.

For example:

```text
Supplier Has Strong Controls
        +
Critical Dependency
        ↓
Risk May Still Be Significant
```

Or:

```text
Supplier Has a Control Gap
        +
Effective Compensating Controls
        ↓
Risk May Remain Acceptable
```

GRC professionals must therefore interpret assessment results within the business context.

---

# 54. Common Third-Party Risk Assessment Mistakes

Common weaknesses include:

```text
Using One Score for Everything
Ignoring Business Criticality
Ignoring Data Sensitivity
Ignoring Privileged Access
Accepting Certifications Without Scope Review
Ignoring Subcontractors
Ignoring Concentration Risk
Treating Questionnaires as Evidence
Failing to Validate Supplier Claims
Ignoring Residual Risk
No Risk Owner
No Reassessment
```

These weaknesses can produce inaccurate risk decisions.

---

# 55. Better Assessment Approach

A stronger model is:

```text
Business Context
       ↓
Supplier Exposure
       ↓
Threats
       ↓
Vulnerabilities
       ↓
Impact
       ↓
Inherent Risk
       ↓
Controls
       ↓
Control Effectiveness
       ↓
Residual Risk
       ↓
Risk Appetite
       ↓
Treatment
       ↓
Management Decision
```

This creates a logical connection between the supplier's characteristics and the final risk decision.

---

# 56. Practical Example – Cloud Provider

Suppose a cloud provider hosts a critical customer platform.

### Business Context

```text
Critical Customer Service
```

### Exposure

```text
Sensitive Data
+
Privileged Access
+
Internet Connectivity
```

### Threat

```text
Cyberattack
```

### Vulnerability

```text
Weak Privileged Access Controls
```

### Impact

```text
Customer Data Exposure
+
Service Disruption
+
Regulatory Impact
```

### Inherent Risk

```text
High
```

### Controls

```text
MFA
PAM
Encryption
Monitoring
Segmentation
DR
```

### Residual Risk

```text
Moderate
```

### Decision

```text
Accept With Monitoring
```

This illustrates how the assessment converts technical information into a management decision.

---

# 57. Practical Example – SaaS HR Provider

Consider a SaaS provider processing employee information.

```text
Employee Data
      ↓
SaaS Provider
      ↓
Personal Data Processing
      ↓
Privacy + Security Risk
      ↓
Due Diligence
      ↓
Privacy Assessment
      ↓
Security Controls
      ↓
Residual Risk
      ↓
Risk Decision
```

The assessment should consider both cybersecurity and privacy exposure.

---

# 58. Practical Example – Managed Service Provider

A managed service provider has remote administrative access.

```text
Managed Service Provider
          ↓
Remote Access
          ↓
Privileged Access
          ↓
Critical Systems
          ↓
High Inherent Risk
          ↓
PAM + MFA + Monitoring
          ↓
Control Assessment
          ↓
Residual Risk
          ↓
Management Decision
```

The level of access materially influences the risk assessment.

---

# 59. Practical Example – Low-Risk Supplier

A supplier provides office equipment and has:

```text
No Sensitive Data
No System Access
No Critical Service
No Regulatory Dependency
```

The assessment may result in:

```text
Low Inherent Risk
      ↓
Basic Controls
      ↓
Low Residual Risk
      ↓
Standard Approval
```

This demonstrates why TPRM must remain proportionate.

---

# 60. End-to-End Third-Party Risk Assessment Model

The complete model can be represented as:

```text
                         BUSINESS CONTEXT
                                ↓
                     ┌────────────────────┐
                     │ Supplier Exposure  │
                     └─────────┬──────────┘
                               ↓
                  ┌─────────────────────────┐
                  │ Threats + Vulnerability │
                  └────────────┬────────────┘
                               ↓
                     ┌───────────────────┐
                     │ Impact Assessment │
                     └─────────┬─────────┘
                               ↓
                     ┌───────────────────┐
                     │  INHERENT RISK    │
                     └─────────┬─────────┘
                               ↓
                     ┌───────────────────┐
                     │ Supplier Controls │
                     └─────────┬─────────┘
                               ↓
                  ┌─────────────────────────┐
                  │ Control Effectiveness   │
                  └────────────┬────────────┘
                               ↓
                     ┌───────────────────┐
                     │  RESIDUAL RISK    │
                     └─────────┬─────────┘
                               ↓
                     ┌───────────────────┐
                     │  Risk Appetite    │
                     └─────────┬─────────┘
                               ↓
                    ┌──────────┴──────────┐
                    ↓                     ↓
                ACCEPTABLE           NOT ACCEPTABLE
                    ↓                     ↓
                APPROVE              TREAT / AVOID /
                                     TRANSFER / ACCEPT
```

---

# 61. Integrated Third-Party Risk Model

A mature assessment can integrate multiple risk dimensions:

```text
                     THIRD PARTY
                          ↓
        ┌─────────────────┼─────────────────┐
        ↓                 ↓                 ↓
   Cybersecurity       Privacy          Compliance
        ↓                 ↓                 ↓
        └─────────────────┼─────────────────┘
                          ↓
                  Operational Risk
                          ↓
                   Resilience Risk
                          ↓
                   Financial Risk
                          ↓
                Concentration Risk
                          ↓
                    RISK PROFILE
                          ↓
                  MANAGEMENT DECISION
```

This creates a more comprehensive view of supplier risk.

---

# 62. GRC Traceability Model

From a GRC perspective, the assessment should provide traceability from the original business requirement to the final risk decision.

```text
Business Requirement
        ↓
Supplier
        ↓
Service
        ↓
Exposure
        ↓
Threat
        ↓
Vulnerability
        ↓
Impact
        ↓
Inherent Risk
        ↓
Control
        ↓
Evidence
        ↓
Control Effectiveness
        ↓
Residual Risk
        ↓
Risk Treatment
        ↓
Risk Owner
        ↓
Management Decision
        ↓
Monitoring
```

This is one of the most important characteristics of a mature GRC risk assessment.

---

# 63. Key GRC Takeaways

A mature **Third-Party Risk Assessment Model** should establish:

```text
1. Business Context
2. Supplier Criticality
3. Data Exposure
4. System Access
5. Operational Dependency
6. Regulatory Exposure
7. Geographic Exposure
8. Subcontractor Exposure
9. Threat Assessment
10. Vulnerability Assessment
11. Impact Assessment
12. Likelihood Assessment
13. Inherent Risk
14. Control Assessment
15. Control Effectiveness
16. Control Gaps
17. Compensating Controls
18. Residual Risk
19. Risk Appetite Comparison
20. Risk Treatment
21. Risk Acceptance
22. Risk Escalation
23. Risk Monitoring
24. Periodic Reassessment
25. Evidence and Traceability
```

The central principle is:

> **Third-party risk assessment should translate supplier exposure, threats, vulnerabilities, business impact, and control effectiveness into a clear understanding of residual risk and an accountable management decision.**

The strongest assessment is therefore not simply:

```text
Supplier
   ↓
Questionnaire
   ↓
Score
```

but:

```text
Supplier
   ↓
Business Context
   ↓
Exposure
   ↓
Threat + Vulnerability
   ↓
Impact
   ↓
Inherent Risk
   ↓
Controls
   ↓
Evidence
   ↓
Control Effectiveness
   ↓
Residual Risk
   ↓
Risk Appetite
   ↓
Treatment / Acceptance
   ↓
Management Decision
   ↓
Continuous Monitoring
```

# 18.12 Third-Party Risk Management Diagrams

## Part 4 – Supplier Monitoring and Offboarding

Supplier risk does not end when a supplier is approved and onboarded.

A supplier that was considered acceptable at the beginning of a relationship may become higher risk because of:

```text id="n8l0zq"
Security Incidents
Regulatory Changes
Ownership Changes
New Subcontractors
Service Changes
Technology Changes
Financial Problems
Control Failures
Contract Changes
Geopolitical Events
```

For this reason, mature Third-Party Risk Management (TPRM) treats supplier management as a **continuous lifecycle**.

A simplified lifecycle is:

```text id="4z5q8u"
Supplier Onboarding
        ↓
Risk Monitoring
        ↓
Periodic Assessment
        ↓
Event-Driven Assessment
        ↓
Risk Treatment
        ↓
Performance Review
        ↓
Renewal / Reassessment
        ↓
Offboarding
        ↓
Data / Access / Asset Closure
        ↓
Final Assurance
```

The objective is to ensure that supplier risk remains within the organization's acceptable boundaries **throughout the entire relationship and through its termination**.

---

# 1. Purpose of Supplier Monitoring

Supplier monitoring provides ongoing visibility into whether the supplier continues to meet:

```text id="n2k0ah"
Security Requirements
Compliance Requirements
Contractual Obligations
Service Levels
Risk Expectations
Resilience Requirements
Privacy Obligations
```

The organization should not rely exclusively on the assessment performed before onboarding.

A supplier's risk profile can change significantly over time.

---

# 2. Continuous Supplier Risk Lifecycle

The complete model can be represented as:

```text id="s3k5x9"
                  SUPPLIER
                     ↓
                 ONBOARDING
                     ↓
                 MONITORING
                     ↓
             PERIODIC ASSESSMENT
                     ↓
             EVENT-DRIVEN REVIEW
                     ↓
              RISK REASSESSMENT
                     ↓
          ┌──────────┴──────────┐
          ↓                     ↓
    Risk Acceptable        Risk Increased
          ↓                     ↓
      Continue          Treat / Escalate
          ↓                     ↓
       Monitor            Reassess
          └──────────┬──────────┘
                     ↓
              CONTRACT END
                     ↓
                OFFBOARDING
```

This illustrates that monitoring and reassessment continue until the relationship formally ends.

---

# 3. Supplier Monitoring Model

A practical monitoring model consists of several dimensions:

```text id="9i0s7d"
                 SUPPLIER
                     ↓
      ┌──────────────┼──────────────┐
      ↓              ↓              ↓
   Security      Compliance       Service
      ↓              ↓              ↓
   Privacy       Resilience      Financial
      ↓              ↓              ↓
      └──────────────┼──────────────┘
                     ↓
              SUPPLIER RISK
                     ↓
              MANAGEMENT ACTION
```

This prevents monitoring from becoming limited to cybersecurity alone.

---

# 4. Security Monitoring

Security monitoring may include:

```text id="8b5d3q"
Security Incidents
Vulnerability Findings
Penetration Test Results
Security Certification Status
Access Control Issues
MFA Compliance
Privileged Access Issues
Security Assessment Findings
Threat Intelligence
```

For critical suppliers, some of these indicators may need to be monitored continuously or at defined intervals.

---

# 5. Compliance Monitoring

The organization should determine whether the supplier continues to satisfy applicable compliance requirements.

Examples include:

```text id="k8t0fh"
Regulatory Obligations
Contractual Requirements
Privacy Requirements
Security Standards
Industry Requirements
Licensing
Audit Requirements
```

A supplier may have been compliant when onboarded but become non-compliant following a regulatory or business change.

---

# 6. Certification Monitoring

Supplier certifications should be monitored for:

```text id="5d3v0k"
Expiration
Renewal
Scope Changes
Suspension
Certification Withdrawal
New Audit Findings
```

A simple workflow is:

```text id="7o7t1f"
Certification
      ↓
Expiration Date
      ↓
Approaching?
   ↙       ↘
 Yes        No
 ↓           ↓
Request     Continue
Renewal     Monitoring
 ↓
Validate
 ↓
Update Supplier Record
```

A certification should not simply remain permanently marked as "valid" in a GRC system.

---

# 7. Security Rating Monitoring

External security ratings can provide additional signals.

Potential indicators include:

```text id="1y7p1k"
Security Rating
Exposed Services
Known Vulnerabilities
Credential Exposure
Domain Reputation
Public Security Events
```

These indicators can be useful for identifying changes that warrant further investigation.

However, external ratings should generally be treated as **risk indicators**, not definitive proof of security effectiveness.

---

# 8. Supplier Incident Monitoring

A significant supplier security incident may trigger immediate reassessment.

```text id="5d3xkj"
Supplier Incident
       ↓
Notification
       ↓
Initial Impact Assessment
       ↓
Business Impact?
       ↓
Security / Privacy Impact?
       ↓
Risk Reassessment
       ↓
Corrective Action
       ↓
Management Decision
```

The severity and scope of the incident should determine the level of response.

---

# 9. Event-Driven Monitoring

Not every risk change follows the annual assessment schedule.

Monitoring should identify events such as:

```text id="5q8d4v"
Major Security Incident
Acquisition
Merger
Ownership Change
New Subprocessor
New Data Processing
New Geographic Location
Major Service Change
Technology Migration
Regulatory Enforcement
Financial Distress
Repeated SLA Failures
```

These events can trigger an **event-driven reassessment**.

---

# 10. Periodic Supplier Assessment

Suppliers should be reassessed according to risk.

A simplified model is:

```text id="h2w2gl"
Critical
   ↓
Frequent / Continuous Monitoring
+
Periodic Full Assessment

High
   ↓
Regular Reassessment

Moderate
   ↓
Scheduled Review

Low
   ↓
Simplified Periodic Review
```

The exact frequency should be defined by the organization's TPRM policy.

---

# 11. Supplier Risk Score Changes

Supplier risk should be capable of changing over time.

```text id="49d8w6"
Initial Risk
     ↓
Moderate
     ↓
Security Incident
     ↓
High
     ↓
Remediation
     ↓
Moderate
```

This demonstrates why supplier risk should not be treated as a static value.

---

# 12. Risk Trend Monitoring

A GRC platform can track supplier risk over time.

For example:

```text id="r7v5dg"
Risk Level

High ────────────┐
                 │
Medium ─────┐    └───────
            │
Low ────────┘
     Time →
```

The organization can identify whether supplier risk is:

```text id="f6z7w2"
Increasing
Stable
Decreasing
```

A deteriorating trend may warrant management attention even before a formal risk threshold is exceeded.

---

# 13. Supplier Performance Monitoring

TPRM should also consider operational performance.

Possible metrics include:

```text id="f7m0nj"
SLA Compliance
Availability
Incident Frequency
Response Time
Resolution Time
Service Quality
Contract Compliance
```

A supplier with repeated operational failures may create significant business risk even if its cybersecurity controls remain strong.

---

# 14. Supplier Resilience Monitoring

For critical suppliers, resilience indicators may include:

```text id="a0p2ks"
DR Test Results
Backup Performance
Recovery Time
Recovery Point
Service Availability
Redundancy
Geographic Resilience
Business Continuity Testing
```

The organization should determine whether the supplier continues to meet the resilience requirements established during onboarding.

---

# 15. Supplier Financial Monitoring

Financial deterioration can create operational and continuity risks.

Potential indicators include:

```text id="xw3k4f"
Credit Risk
Financial Results
Debt
Liquidity
Major Losses
Bankruptcy Indicators
Credit Rating Changes
Major Customer Loss
```

A financially distressed supplier may be unable to maintain security, staffing, infrastructure, or service levels.

---

# 16. Supplier Ownership Monitoring

Changes in ownership can materially change risk.

```text id="v4m2cg"
Supplier
   ↓
Acquisition
   ↓
New Ownership
   ↓
New Governance
   ↓
Potential Risk Change
   ↓
Reassessment
```

Important changes may include:

```text id="9cx2rv"
Acquisition
Merger
Private Equity Investment
Change in Parent Company
Divestiture
Major Restructuring
```

---

# 17. Subprocessor Monitoring

Subprocessors should be monitored throughout the supplier relationship.

```text id="3t3z0q"
Supplier
   ↓
Subprocessor Change
   ↓
Notification
   ↓
Risk Assessment
   ↓
Approve / Reject
   ↓
Update Supplier Risk Record
```

For sensitive services, the organization may require contractual notification or approval before certain subprocessors are introduced.

---

# 18. Geographic Change Monitoring

A supplier may change where services or data are delivered.

For example:

```text id="qv4m1f"
Original Processing Location
          ↓
New Data Center
          ↓
New Country
          ↓
New Legal Jurisdiction
          ↓
Privacy / Regulatory Review
```

Geographic changes may therefore require reassessment.

---

# 19. Contractual Compliance Monitoring

Supplier monitoring should verify compliance with important contract provisions.

Examples:

```text id="y6x1o4"
Security Clauses
Privacy Clauses
Audit Rights
Incident Notification
SLA
BCP / DR
Data Retention
Data Deletion
Subprocessor Requirements
```

Contractual obligations should be mapped to monitoring activities where appropriate.

---

# 20. Supplier SLA Monitoring

Service-level monitoring may include:

```text id="c5j7jp"
Availability
Response Time
Resolution Time
Capacity
Service Quality
Incident Handling
```

A simplified model is:

```text id="0v9k2n"
Contract SLA
     ↓
Measured Performance
     ↓
Compare
     ↓
SLA Met?
   ↙      ↘
 Yes       No
 ↓          ↓
Continue   Corrective Action
```

Repeated SLA failures may increase supplier risk.

---

# 21. Supplier Finding Monitoring

Open supplier findings should be tracked until closure.

```text id="7i6h5f"
Finding
  ↓
Risk Rating
  ↓
Remediation Plan
  ↓
Due Date
  ↓
Supplier Action
  ↓
Evidence
  ↓
Validation
  ↓
Closure
```

High-risk findings should receive stronger escalation and oversight.

---

# 22. Supplier Remediation

When weaknesses are identified:

```text id="w0z2z9"
Finding
   ↓
Root Cause
   ↓
Corrective Action
   ↓
Responsible Owner
   ↓
Target Date
   ↓
Evidence
   ↓
Validation
```

The organization should distinguish between:

**Supplier says the issue is fixed**

and:

**The organization has sufficient evidence that the issue has been remediated.**

---

# 23. Risk Escalation

Risk should be escalated when predefined thresholds are exceeded.

Examples:

```text id="x4n6kq"
Critical Security Incident
High-Risk Control Failure
Regulatory Violation
Repeated SLA Failure
Major Data Breach
Expired Critical Certification
Financial Distress
Unacceptable Residual Risk
```

A possible escalation path is:

```text id="72u1n6"
Supplier Owner
      ↓
TPRM / GRC
      ↓
Security / Privacy / Compliance
      ↓
Business Leadership
      ↓
Executive Risk Committee
```

---

# 24. Supplier Monitoring Dashboard

An enterprise TPRM dashboard may show:

```text id="4h0b5v"
        SUPPLIER MONITORING

Critical Suppliers                 32
High-Risk Suppliers                61
Overdue Assessments                 9
Open High Findings                 17
Critical Incidents                  2
Expired Certifications              3
SLA Breaches                       11
Suppliers Under Remediation         8
```

The figures are illustrative.

The dashboard should focus on **material risk exposure and trends** rather than simply the number of suppliers.

---

# 25. Supplier Risk Indicators

Useful Key Risk Indicators (KRIs) may include:

```text id="8j5f9q"
% Critical Suppliers With Current Assessments
% High-Risk Findings Overdue
% Suppliers With Expired Certifications
Number of Critical Supplier Incidents
Number of Suppliers With DR Test Failures
Number of Suppliers With Major SLA Breaches
Number of Suppliers With Unresolved High Risks
```

These indicators help management understand the overall supplier risk posture.

---

# 26. Supplier Risk Alerts

Automated alerts can be configured for:

```text id="j7l4cc"
Assessment Expiration
Certification Expiration
Contract Expiration
High-Risk Finding
Security Incident
Subprocessor Change
SLA Breach
Risk Threshold Breach
```

A simplified automation model is:

```text id="v4w5bx"
Monitoring Event
      ↓
Risk Rule
      ↓
Threshold Exceeded?
      ↓
Alert
      ↓
Risk Owner
      ↓
Action
```

---

# 27. Continuous Monitoring vs Periodic Assessment

These are complementary, not interchangeable.

### Continuous Monitoring

Looks for **changes and events**.

```text
Incidents
Alerts
Certifications
SLA
Threat Signals
```

### Periodic Assessment

Performs a **structured review**.

```text
Questionnaire
Evidence
Controls
Risk
Resilience
Compliance
```

Together:

```text id="1hj7vl"
Continuous Monitoring
        +
Periodic Assessment
        ↓
Continuous Third-Party Risk Management
```

---

# 28. Supplier Renewal Assessment

Before renewing a significant supplier contract, the organization should consider:

```text id="qv4h4p"
Current Risk
Open Findings
Security Performance
SLA Performance
Compliance
Incidents
Financial Condition
Business Criticality
Contract Changes
```

The renewal decision can therefore be informed by the supplier's actual performance during the relationship.

---

# 29. Supplier Renewal Decision

A simplified model is:

```text id="cxz1yq"
Contract Expiring
       ↓
Risk Review
       ↓
Performance Review
       ↓
Open Issues?
   ↙         ↘
 No           Yes
 ↓             ↓
Renew       Remediate /
            Escalate
 ↓
Updated Contract
```

Renewal should not be an automatic procurement event.

---

# 30. Supplier Offboarding

Offboarding is the controlled termination of the supplier relationship.

It should address:

```text id="r1o2pj"
Access Removal
Data Return
Data Deletion
Asset Return
Credential Revocation
Account Closure
Contract Termination
Subprocessor Closure
Knowledge Transfer
Service Transition
Evidence Retention
```

Offboarding is therefore a **security and risk-management process**, not merely an administrative activity.

---

# 31. Supplier Offboarding Lifecycle

A simplified process is:

```text id="8xj7j2"
Termination Decision
        ↓
Offboarding Plan
        ↓
Service Transition
        ↓
Access Revocation
        ↓
Asset Recovery
        ↓
Data Return
        ↓
Data Deletion
        ↓
Account Closure
        ↓
Contract Closure
        ↓
Evidence Collection
        ↓
Final Risk Review
```

---

# 32. Access Revocation

One of the most important offboarding activities is removing supplier access.

This may include:

```text id="j1n8g4"
User Accounts
Privileged Accounts
VPN
Remote Access
API Keys
Service Accounts
Certificates
Tokens
Cloud Access
Physical Access
```

A simplified control is:

```text id="8n0gph"
Supplier Termination
       ↓
Access Inventory
       ↓
Revoke Access
       ↓
Validate Revocation
       ↓
Evidence
```

The validation step is important because simply requesting access removal does not prove that access has actually been removed.

---

# 33. Privileged Access Revocation

For suppliers with privileged access:

```text id="x0z6ts"
Termination
    ↓
PAM Account Closure
    ↓
Privileged Credential Rotation
    ↓
Token / Key Revocation
    ↓
Session Termination
    ↓
Validation
```

Credential rotation may be particularly important where shared credentials or service accounts were used.

---

# 34. Data Return

The organization should determine what information must be returned.

Examples include:

```text id="0px6ut"
Customer Data
Employee Data
Business Records
Documents
Backups
Configuration Data
Security Logs
Intellectual Property
```

Data return should follow contractual and regulatory requirements.

---

# 35. Data Deletion

Where required, the supplier should securely delete organizational data.

A simplified model is:

```text id="6s7t9h"
Termination
     ↓
Data Inventory
     ↓
Data Return
     ↓
Deletion
     ↓
Backup Consideration
     ↓
Deletion Evidence
```

The organization should consider whether copies remain in:

```text id="l0i5e4"
Production
Backups
Archives
Logs
Test Environments
Subprocessors
```

---

# 36. Data Deletion Evidence

Evidence may include:

```text id="h1v8yd"
Deletion Certificate
System Records
Deletion Logs
Supplier Attestation
Contractual Confirmation
```

The appropriate evidence depends on the sensitivity of the data and contractual requirements.

---

# 37. Asset Recovery

Supplier-owned or organization-owned assets should be accounted for.

Examples include:

```text id="xq2j8z"
Laptops
Mobile Devices
Network Equipment
Security Tokens
Access Cards
Physical Media
Documentation
```

A simplified model is:

```text id="h8p5yq"
Asset Inventory
     ↓
Supplier
     ↓
Return
     ↓
Inspection
     ↓
Inventory Update
```

---

# 38. Contract Closure

Contract termination should confirm that outstanding obligations are addressed.

```text id="3l0y3m"
Contract
   ↓
Termination Notice
   ↓
Outstanding Obligations
   ↓
Data / Security Requirements
   ↓
Financial Settlement
   ↓
Contract Closure
```

Legal, procurement, GRC, security, privacy, and business owners may all have responsibilities depending on the relationship.

---

# 39. Service Transition

If the supplier supports a critical business service, offboarding should include transition planning.

```text id="a8h7vr"
Existing Supplier
       ↓
Transition Plan
       ↓
New Supplier / Internal Service
       ↓
Data Migration
       ↓
Testing
       ↓
Service Validation
       ↓
Old Supplier Termination
```

The organization should avoid terminating the old supplier before the replacement service is sufficiently operational.

---

# 40. Knowledge Transfer

Some suppliers possess important operational knowledge.

Offboarding may therefore require:

```text id="2x6d4m"
Architecture Documentation
Operational Procedures
Configuration
Runbooks
Support Information
Contact Information
Known Issues
Recovery Procedures
```

This reduces the risk of losing operational knowledge when the supplier relationship ends.

---

# 41. Subprocessor Offboarding

Where the primary supplier uses subprocessors:

```text id="2l6r9p"
Primary Supplier
      ↓
Subprocessor
      ↓
Data / Service
      ↓
Termination
      ↓
Data Deletion
      ↓
Access Revocation
      ↓
Confirmation
```

The organization should ensure that termination requirements flow through the supplier chain where applicable.

---

# 42. Final Supplier Risk Assessment

At the end of the relationship, a final review can verify that:

```text id="9t6gq3"
Access Removed
Data Returned
Data Deleted
Assets Returned
Contracts Closed
Findings Resolved
Subprocessors Addressed
Evidence Collected
```

This provides formal closure.

---

# 43. Offboarding Checklist

A practical checklist could include:

```text id="1y9r7p"
☐ Termination Approved
☐ Business Owner Notified
☐ Procurement Notified
☐ Legal Notified
☐ Security Notified
☐ Privacy Notified
☐ Access Inventory Completed
☐ User Accounts Disabled
☐ Privileged Access Removed
☐ API Keys Revoked
☐ Certificates Revoked
☐ Assets Returned
☐ Data Returned
☐ Data Deleted
☐ Subprocessors Addressed
☐ Contract Closed
☐ Final Evidence Collected
☐ Supplier Record Updated
☐ Offboarding Approved
```

---

# 44. Offboarding Failure Scenario

Consider a supplier whose contract has ended but whose VPN account remains active.

```text id="l4b0z2"
Contract Terminated
        ↓
Supplier No Longer Authorized
        ↓
VPN Account Remains Active
        ↓
Compromised Supplier Credential
        ↓
Unauthorized Access
        ↓
Security Incident
```

This demonstrates why contractual termination and technical termination must be synchronized.

---

# 45. Supplier Exit Risk

Offboarding itself can create risk.

Potential risks include:

```text id="7n2f8x"
Data Loss
Service Disruption
Access Persistence
Knowledge Loss
Incomplete Migration
Unresolved Vulnerabilities
Contractual Disputes
Regulatory Exposure
```

Therefore:

> **Supplier termination should be risk-managed in the same way as supplier onboarding.**

---

# 46. Supplier Exit Strategy

For critical suppliers, an exit strategy should ideally be understood before the relationship becomes dependent on the supplier.

```text id="6k9b4n"
Critical Supplier
       ↓
Exit Strategy
       ↓
Alternative Provider
       ↓
Migration Requirements
       ↓
Data Portability
       ↓
Transition Timeline
       ↓
Testing
```

This reduces vendor lock-in and concentration risk.

---

# 47. Exit Strategy and Concentration Risk

If the supplier is difficult to replace:

```text id="9v4q1k"
Critical Service
       ↓
Single Supplier
       ↓
High Dependency
       ↓
Limited Alternatives
       ↓
High Concentration Risk
```

The organization may therefore need:

```text id="u7d0w3"
Alternative Supplier
Multi-Sourcing
Data Portability
Contractual Exit Rights
Transition Assistance
```

---

# 48. Supplier Monitoring and Offboarding in a GRC Platform

A GRC platform can manage the lifecycle:

```text id="e6x8yd"
Supplier Record
      ↓
Risk Tier
      ↓
Assessment
      ↓
Controls
      ↓
Findings
      ↓
Monitoring
      ↓
Alerts
      ↓
Reassessment
      ↓
Renewal / Termination
      ↓
Offboarding
      ↓
Closure
```

This provides a centralized record of the supplier relationship.

---

# 49. Automated Offboarding Workflow

Where systems are integrated, offboarding can trigger automated actions.

For example:

```text id="n0p7u1"
Supplier Termination Approved
            ↓
GRC Workflow
            ↓
IAM
            ↓
Disable Accounts
            ↓
PAM
            ↓
Remove Privileged Access
            ↓
IT Asset Management
            ↓
Recover Assets
            ↓
Data Management
            ↓
Data Deletion
            ↓
Evidence Repository
            ↓
Closure
```

Automation reduces the likelihood that a critical offboarding step is forgotten.

---

# 50. Supplier Lifecycle Governance

The complete lifecycle can be represented as:

```text id="h6w2p8"
                 THIRD-PARTY LIFECYCLE

Identification
      ↓
Screening
      ↓
Due Diligence
      ↓
Risk Assessment
      ↓
Approval
      ↓
Contract
      ↓
Onboarding
      ↓
Monitoring
      ↓
Reassessment
      ↓
Risk Treatment
      ↓
Renewal
      ↓
Termination
      ↓
Offboarding
      ↓
Closure
```

Governance should exist across every stage.

---

# 51. Three Lines and Supplier Monitoring

The Three Lines Model can also be applied during ongoing monitoring.

```text id="5x8j2a"
FIRST LINE
Business / Supplier Owner
        ↓
Monitors Performance

SECOND LINE
GRC / Risk / Security / Privacy
        ↓
Challenges and Oversees

THIRD LINE
Internal Audit
        ↓
Provides Independent Assurance
```

This provides separation between operational ownership and independent assurance.

---

# 52. Supplier Monitoring Metrics

Useful KPIs and KRIs include:

```text id="d0g5h9"
Assessment Completion Rate
Assessment Overdue Rate
High-Risk Finding Rate
Finding Closure Rate
Certification Expiration Rate
Security Incident Rate
SLA Breach Rate
Supplier Risk Trend
Critical Supplier Coverage
Offboarding Completion Rate
```

Metrics should be connected to management decisions rather than collected solely for reporting purposes.

---

# 53. Supplier Offboarding Metrics

Useful offboarding indicators include:

```text id="2p3x4m"
% Suppliers Fully Offboarded
% Supplier Accounts Disabled on Time
% Data Deletion Confirmed
% Assets Returned
% Open Findings at Termination
Average Offboarding Duration
Number of Access Exceptions
```

These metrics help identify weaknesses in the supplier exit process.

---

# 54. GRC Traceability

A mature supplier lifecycle should provide traceability from onboarding through termination.

```text id="b7f0m2"
Supplier
   ↓
Business Service
   ↓
Risk Assessment
   ↓
Controls
   ↓
Evidence
   ↓
Monitoring
   ↓
Findings
   ↓
Remediation
   ↓
Renewal / Termination
   ↓
Offboarding Evidence
   ↓
Closure
```

This creates an auditable lifecycle record.

---

# 55. Practical Example – Critical Cloud Supplier

Consider a cloud provider supporting a critical customer platform.

### During the relationship:

```text id="5f1m4q"
Continuous Monitoring
        ↓
Security Incidents
        ↓
Certificate Status
        ↓
SLA Performance
        ↓
DR Testing
        ↓
Risk Assessment
```

Suppose the supplier announces a major change to its hosting architecture.

```text id="y3g5d8"
Architecture Change
        ↓
Event-Driven Review
        ↓
Security Assessment
        ↓
Privacy Assessment
        ↓
Risk Reassessment
        ↓
Approval / Treatment
```

If the organization later terminates the supplier:

```text id="m4k9j2"
Termination
    ↓
Migration
    ↓
Access Revocation
    ↓
Data Return
    ↓
Data Deletion
    ↓
Asset Recovery
    ↓
Final Assurance
    ↓
Closure
```

This demonstrates the full TPRM lifecycle.

---

# 56. Practical Example – Supplier Security Incident

Suppose a SaaS provider experiences a significant security incident.

```text id="8w5v1k"
Supplier Incident
      ↓
Notification
      ↓
Initial Assessment
      ↓
Affected Data?
      ↓
Affected Service?
      ↓
Regulatory Impact?
      ↓
Risk Reassessment
      ↓
Corrective Actions
      ↓
Validation
      ↓
Risk Decision
```

The organization should determine whether the incident changes the supplier's residual risk.

---

# 57. Practical Example – Supplier Termination

Suppose a supplier contract expires.

A controlled offboarding process would be:

```text id="6g2k9w"
Contract Expiry
      ↓
Business Confirmation
      ↓
Transition Completed
      ↓
Access Revoked
      ↓
Assets Returned
      ↓
Data Returned
      ↓
Data Deleted
      ↓
Deletion Evidence
      ↓
Contract Closed
      ↓
Supplier Record Archived
```

This provides formal evidence that the relationship has been terminated securely.

---

# 58. Common Monitoring Weaknesses

Organizations frequently encounter:

```text id="w4n9k1"
No Supplier Inventory
No Risk-Based Monitoring
Annual Review Only
No Event-Driven Reassessment
Expired Certifications
Untracked Findings
Poor SLA Monitoring
No Subprocessor Visibility
No Concentration Monitoring
No Exit Strategy
```

These weaknesses can leave organizations exposed between formal assessments.

---

# 59. Common Offboarding Weaknesses

Typical failures include:

```text id="x6c3p0"
Accounts Not Disabled
Privileged Access Not Removed
API Keys Not Revoked
Data Not Deleted
Backups Ignored
Assets Not Returned
Subprocessors Not Addressed
No Deletion Evidence
Contract Terminated Before Migration
No Final Risk Review
```

The most serious issue is often **persistent access after supplier termination**.

---

# 60. Mature Supplier Monitoring and Offboarding Model

A mature model can be summarized as:

```text id="z3g8p2"
                    SUPPLIER
                       ↓
                   ONBOARDING
                       ↓
                 RISK BASELINE
                       ↓
              CONTINUOUS MONITORING
                       ↓
             ┌─────────┴─────────┐
             ↓                   ↓
       NORMAL STATUS        RISK EVENT
             ↓                   ↓
          Monitor          Reassess Risk
             ↓                   ↓
             └─────────┬─────────┘
                       ↓
                 PERIODIC REVIEW
                       ↓
                CONTRACT RENEWAL
                       ↓
                  OR TERMINATION
                       ↓
                  OFFBOARDING
                       ↓
              ACCESS REVOCATION
                       ↓
                 DATA RETURN
                       ↓
                DATA DELETION
                       ↓
               ASSET RECOVERY
                       ↓
               FINAL ASSURANCE
                       ↓
                    CLOSURE
```

---

# 61. Integrated Supplier Risk Management Model

The broader GRC model can be represented as:

```text id="c8w6r1"
                 SUPPLIER
                    ↓
             BUSINESS CONTEXT
                    ↓
              RISK ASSESSMENT
                    ↓
             CONTROL BASELINE
                    ↓
               ONBOARDING
                    ↓
        ┌───────────┴───────────┐
        ↓                       ↓
   MONITORING              INCIDENT / CHANGE
        ↓                       ↓
        └───────────┬───────────┘
                    ↓
             RISK REASSESSMENT
                    ↓
             TREAT / ACCEPT
                    ↓
             CONTINUE / RENEW
                    ↓
               TERMINATION
                    ↓
               OFFBOARDING
                    ↓
                 CLOSURE
```

This represents the principle that third-party risk management is **continuous rather than a one-time assessment**.

---

# 62. End-to-End Supplier Governance Model

A comprehensive lifecycle can be visualized as:

```text id="v6p3z8"
IDENTIFY
   ↓
SCREEN
   ↓
DUE DILIGENCE
   ↓
ASSESS
   ↓
APPROVE
   ↓
CONTRACT
   ↓
ONBOARD
   ↓
MONITOR
   ↓
REASSESS
   ↓
TREAT
   ↓
RENEW OR TERMINATE
   ↓
OFFBOARD
   ↓
VERIFY
   ↓
CLOSE
```

At every stage, the organization should maintain:

```text
Ownership
Evidence
Risk Visibility
Accountability
Traceability
```

---

# 63. Key GRC Takeaways

A mature **Supplier Monitoring and Offboarding Model** should establish:

```text
1. Continuous Supplier Monitoring
2. Risk-Based Monitoring Frequency
3. Security Monitoring
4. Compliance Monitoring
5. Certification Monitoring
6. SLA Monitoring
7. Resilience Monitoring
8. Financial Monitoring
9. Subprocessor Monitoring
10. Ownership Change Monitoring
11. Event-Driven Reassessment
12. Periodic Risk Assessment
13. Risk Trend Analysis
14. Finding and Remediation Tracking
15. Risk Escalation
16. Contract Renewal Review
17. Formal Termination Process
18. Access Revocation
19. Privileged Access Removal
20. Data Return
21. Data Deletion
22. Asset Recovery
23. Service Transition
24. Subprocessor Closure
25. Final Assurance
26. Evidence Retention
27. Formal Supplier Closure
```

The central principle is:

> **Third-party risk management does not end when a supplier is approved, and it does not end when the contract is terminated. Risk must be monitored throughout the relationship, and the supplier must be securely and verifiably offboarded when the relationship ends.**

The complete lifecycle can therefore be summarized as:

```text id="b2m7v4"
              SUPPLIER LIFECYCLE

        IDENTIFY
           ↓
        ASSESS
           ↓
        APPROVE
           ↓
       ONBOARD
           ↓
       MONITOR
           ↓
      REASSESS
           ↓
   TREAT / ACCEPT
           ↓
    RENEW / EXIT
           ↓
      OFFBOARD
           ↓
       VERIFY
           ↓
        CLOSE
```

A strong GRC program ensures that **supplier risk, control effectiveness, contractual obligations, monitoring evidence, remediation activities, and final offboarding actions remain traceable throughout the entire third-party relationship**.



