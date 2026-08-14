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


