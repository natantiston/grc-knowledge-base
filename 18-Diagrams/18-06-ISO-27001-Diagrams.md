# 18.6 ISO 27001 Diagrams

### Part 1 – ISO 27001 ISMS Structure

ISO/IEC 27001 provides a systematic approach for establishing, implementing, maintaining, and continually improving an **Information Security Management System (ISMS)**.

For a GRC professional, the ISMS can be visualized as an interconnected system of:

```text
Context
   ↓
Leadership
   ↓
Planning
   ↓
Support
   ↓
Operation
   ↓
Performance Evaluation
   ↓
Improvement
   ↺
```

The ISMS is not simply a collection of security controls. It is a **management system** that connects organizational context, risk management, governance, controls, monitoring, and continual improvement.

---

# 1. What Is an ISMS?

An ISMS is a structured management system used to manage information security risks.

A simplified model is:

```text
                 INFORMATION SECURITY
                         ↓
                       ISMS
                         ↓
        ┌────────────────┼────────────────┐
        ↓                ↓                ↓
      PEOPLE           PROCESS         TECHNOLOGY
        ↓                ↓                ↓
        └────────────────┼────────────────┘
                         ↓
                  Risk Management
                         ↓
                 Security Controls
                         ↓
                  Security Outcomes
```

The ISMS provides the governance structure that coordinates these elements.

---

# 2. ISMS as a Management System

An important distinction is:

```text
Security Controls
        ≠
ISMS
```

Controls are mechanisms used to address security risks.

The ISMS provides the management framework around those controls.

```text
                 ISMS
                  ↓
        ┌─────────┼─────────┐
        ↓         ↓         ↓
      Risk      Controls   Assurance
   Management      ↓         ↓
        ↓       Evidence    Audit
        └─────────┼─────────┘
                  ↓
           Security Governance
```

This distinction is fundamental when implementing ISO 27001.

---

# 3. ISO 27001 ISMS Structure

At a high level, an ISMS can be visualized as:

```text
                         ORGANIZATION
                              ↓
                         ISMS CONTEXT
                              ↓
                    ┌─────────┴─────────┐
                    ↓                   ↓
                 INTERNAL            EXTERNAL
                 CONTEXT             CONTEXT
                    ↓                   ↓
                    └─────────┬─────────┘
                              ↓
                         LEADERSHIP
                              ↓
                            POLICY
                              ↓
                          PLANNING
                              ↓
                      RISK MANAGEMENT
                              ↓
                         OBJECTIVES
                              ↓
                           SUPPORT
                              ↓
                         OPERATION
                              ↓
                    PERFORMANCE EVALUATION
                              ↓
                         IMPROVEMENT
                              ↺
```

This illustrates that the ISMS begins with organizational context and continues through governance, risk management, operations, assurance, and improvement.

---

# 4. Organizational Context

The ISMS must be established within the context of the organization.

Relevant considerations include:

```text
Internal Issues
External Issues
Interested Parties
Legal Requirements
Regulatory Requirements
Business Objectives
Information Security Requirements
Organizational Structure
Technology Environment
```

A simplified model is:

```text
                EXTERNAL CONTEXT
                       ↓
              ┌─────────────────┐
              │                 │
              │   ORGANIZATION  │
              │                 │
              └─────────────────┘
                       ↑
                INTERNAL CONTEXT
                       ↓
                ISMS BOUNDARY
```

The organization must understand the environment in which its ISMS operates.

---

# 5. Interested Parties

An ISMS must also consider relevant interested parties.

Examples include:

```text
Customers
Employees
Suppliers
Regulators
Shareholders
Business Partners
Auditors
Government Authorities
```

The relationship can be visualized as:

```text
                    REGULATORS
                        ↓
CUSTOMERS ───────→ ORGANIZATION ←────── SUPPLIERS
                        ↓
                   EMPLOYEES
                        ↓
                      ISMS
```

Interested-party requirements can influence information security obligations and expectations.

---

# 6. ISMS Scope

The organization must define the scope of the ISMS.

The scope establishes what organizational areas, locations, processes, technologies, and services are included.

A simplified model is:

```text
                  ORGANIZATION
                       ↓
          ┌────────────────────────┐
          │      ISMS SCOPE        │
          │                        │
          │ Processes              │
          │ People                 │
          │ Technology             │
          │ Locations              │
          │ Information Assets     │
          │ Services               │
          └────────────────────────┘
```

The scope should be understandable and defensible.

For example:

```text
ISMS Scope

Cloud Services Division
        +
Corporate IT
        +
Customer Information Systems
        +
Supporting Infrastructure
```

The scope determines the organizational boundaries within which the ISMS is managed.

---

# 7. Leadership

Leadership provides direction and accountability for the ISMS.

A simplified governance structure is:

```text
                 TOP MANAGEMENT
                       ↓
                SECURITY DIRECTION
                       ↓
                ISMS GOVERNANCE
                       ↓
             Information Security
                 Management
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
      Risk          Controls       Compliance
    Management     Management       Management
```

Leadership should establish appropriate direction, responsibilities, and organizational support for information security.

---

# 8. Information Security Policy

The information security policy provides high-level direction.

```text
                 TOP MANAGEMENT
                       ↓
                SECURITY POLICY
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
     Security        Risk          Compliance
    Objectives    Management       Obligations
        ↓              ↓              ↓
        └──────────────┼──────────────┘
                       ↓
                     ISMS
```

The policy provides the foundation for more detailed security objectives, processes, standards, and controls.

---

# 9. Risk Management Within the ISMS

Risk management is a central component of the ISMS.

A simplified model is:

```text
                 INFORMATION ASSETS
                         ↓
                       THREATS
                         ↓
                   VULNERABILITIES
                         ↓
                        RISK
                         ↓
                  RISK ASSESSMENT
                         ↓
                  RISK TREATMENT
                         ↓
                       CONTROLS
                         ↓
                  RESIDUAL RISK
```

The ISMS uses risk management to determine how information security risks should be addressed.

---

# 10. Risk-Based Control Selection

Controls should be connected to identified risks and security objectives.

```text
Risk
 ↓
Risk Treatment
 ↓
Control Requirements
 ↓
Control Selection
 ↓
Implementation
 ↓
Evidence
 ↓
Effectiveness Assessment
```

This helps prevent organizations from implementing controls simply because they appear on a checklist.

The objective is to establish controls appropriate to the organization's risk environment.

---

# 11. Statement of Applicability

The **Statement of Applicability (SoA)** is an important component of an ISO 27001 ISMS.

A simplified relationship is:

```text
Risk Assessment
       ↓
Risk Treatment
       ↓
Control Selection
       ↓
Statement of Applicability
       ↓
Applicable Controls
       ↓
Implementation
```

The SoA provides a structured record of the organization's decisions regarding applicable controls.

A simplified diagram is:

```text
                RISK
                 ↓
          RISK TREATMENT
                 ↓
           CONTROL NEED
                 ↓
                 SoA
                 ↓
      ┌──────────┴──────────┐
      ↓                     ↓
   Applicable            Not Applicable
   Controls              Controls
      ↓
Implementation
```

The organization's justification and control decisions should be appropriately documented.

---

# 12. ISMS Objectives

Security objectives translate organizational direction into measurable goals.

For example:

```text
Security Objective
        ↓
Reduce Critical Vulnerabilities
        ↓
Target:
95% remediated within SLA
        ↓
Measurement
        ↓
Performance Result
```

Other objectives might include:

```text
Reduce Security Incidents
Improve Security Awareness
Increase Control Effectiveness
Improve Vulnerability Remediation
Improve Supplier Security
Increase Incident Response Performance
```

Objectives provide measurable direction for the ISMS.

---

# 13. Support Structure

An ISMS requires organizational support.

Important supporting elements include:

```text
Resources
Competence
Awareness
Communication
Documented Information
```

A simplified model is:

```text
                     ISMS
                      ↓
        ┌─────────────┼─────────────┐
        ↓             ↓             ↓
     PEOPLE        DOCUMENTATION   RESOURCES
        ↓             ↓             ↓
    Competence      Evidence      Technology
    Awareness       Records       Budget
    Training        Policies      Personnel
```

Without appropriate support, even a well-designed ISMS may fail to operate effectively.

---

# 14. Documented Information

ISO 27001 relies on appropriate documented information to demonstrate how the ISMS operates.

Examples include:

```text
Policies
Procedures
Risk Assessments
Risk Treatment Plans
Statement of Applicability
Security Objectives
Audit Results
Management Review Records
Corrective Action Records
Evidence
```

A simplified lifecycle is:

```text
Create
  ↓
Review
  ↓
Approve
  ↓
Use
  ↓
Maintain
  ↓
Review / Update
  ↓
Retain
  ↓
Dispose
```

Documented information should be appropriately controlled.

---

# 15. ISMS Operation

The operational component converts ISMS requirements into actual activities.

```text
ISMS Planning
      ↓
Operational Processes
      ↓
Security Activities
      ↓
Controls
      ↓
Evidence
      ↓
Security Outcomes
```

Examples include:

```text
Access Management
Vulnerability Management
Incident Management
Backup Management
Supplier Security
Change Management
Security Monitoring
Security Awareness
```

These activities support the practical operation of information security.

---

# 16. Performance Evaluation

The organization needs to determine whether the ISMS is working as intended.

A simplified model is:

```text
ISMS
 ↓
Monitoring
 ↓
Measurement
 ↓
Analysis
 ↓
Internal Audit
 ↓
Management Review
 ↓
Performance Evaluation
```

This creates an assurance mechanism around the ISMS.

---

# 17. Internal Audit

Internal audit provides an independent assessment within the organization's governance structure.

```text
                 ISMS
                  ↓
             Audit Planning
                  ↓
             Audit Execution
                  ↓
              Evidence
                  ↓
              Findings
                  ↓
          Audit Conclusions
```

The audit may assess whether the ISMS conforms to:

```text
ISO 27001 Requirements
Organizational Requirements
Established ISMS Processes
Applicable Policies
```

---

# 18. Management Review

Top management reviews the ISMS to determine whether it remains suitable, adequate, and effective.

A simplified model is:

```text
                 ISMS DATA
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
     Metrics      Audits       Risks
        ↓           ↓           ↓
        └───────────┼───────────┘
                    ↓
             MANAGEMENT REVIEW
                    ↓
              Decisions / Actions
                    ↓
               ISMS Improvement
```

Management review therefore connects operational performance with executive decision-making.

---

# 19. Nonconformity and Corrective Action

When the ISMS does not meet a requirement, the organization should address the issue.

```text
Nonconformity
      ↓
Immediate Correction
      ↓
Root Cause Analysis
      ↓
Corrective Action
      ↓
Implementation
      ↓
Effectiveness Review
      ↓
Closure
```

For example:

```text
Audit Finding
     ↓
Root Cause
     ↓
Corrective Action Plan
     ↓
Owner + Due Date
     ↓
Implementation
     ↓
Validation
     ↓
Closure
```

This prevents the ISMS from becoming a static compliance system.

---

# 20. Continual Improvement

Continual improvement is an important characteristic of an effective ISMS.

The organization should continually learn from:

```text
Audits
Incidents
Risk Assessments
Control Testing
Management Reviews
Nonconformities
Regulatory Changes
Technology Changes
Business Changes
```

The model becomes:

```text
             ISMS PERFORMANCE
                    ↓
                 Findings
                    ↓
                Analysis
                    ↓
               Improvement
                    ↓
              ISMS Changes
                    ↓
              New Performance
                    ↺
```

---

# 21. PDCA Perspective

The ISMS can also be understood through a continuous improvement cycle.

```text
              PLAN
                ↓
       Establish ISMS
       Assess Risks
       Set Objectives
                ↓
                ↓
               DO
                ↓
       Implement Processes
       Implement Controls
                ↓
                ↓
             CHECK
                ↓
       Monitor
       Measure
       Audit
       Review
                ↓
                ↓
               ACT
                ↓
       Correct
       Improve
       Update
                ↓
                └──────────────↺
```

Although ISO 27001:2022 is structured around the clauses and does not require organizations to label their ISMS explicitly as "PDCA," the PDCA concept remains a useful way to visualize continual improvement.

---

# 22. Integrated ISMS Diagram

A comprehensive ISMS model can be represented as:

```text
                         ORGANIZATIONAL CONTEXT
                                  ↓
                         ISMS SCOPE
                                  ↓
                              LEADERSHIP
                                  ↓
                         SECURITY POLICY
                                  ↓
                              PLANNING
                                  ↓
                       ┌──────────┴──────────┐
                       ↓                     ↓
                RISK ASSESSMENT        SECURITY OBJECTIVES
                       ↓                     ↓
                       └──────────┬──────────┘
                                  ↓
                           RISK TREATMENT
                                  ↓
                                  SoA
                                  ↓
                         CONTROL IMPLEMENTATION
                                  ↓
                              OPERATION
                                  ↓
                         DOCUMENTED EVIDENCE
                                  ↓
                       ┌──────────┴──────────┐
                       ↓                     ↓
                   MONITORING             AUDIT
                       ↓                     ↓
                       └──────────┬──────────┘
                                  ↓
                         MANAGEMENT REVIEW
                                  ↓
                    NONCONFORMITY / FINDINGS
                                  ↓
                         CORRECTIVE ACTION
                                  ↓
                         CONTINUAL IMPROVEMENT
                                  ↓
                                  ↺
```

---

# 23. ISMS as an Integrated GRC System

From a GRC perspective, the ISMS can be viewed as the integration of several disciplines:

```text
                       ISMS
                        ↓
       ┌────────────────┼────────────────┐
       ↓                ↓                ↓
    GOVERNANCE          RISK          ASSURANCE
       ↓                ↓                ↓
    Policy           Assessment       Audit
    Roles            Treatment        Testing
    Objectives       Residual Risk    Review
       ↓                ↓                ↓
       └────────────────┼────────────────┘
                        ↓
                     CONTROLS
                        ↓
                    EVIDENCE
                        ↓
                  PERFORMANCE
                        ↓
                  IMPROVEMENT
```

This is particularly important for a GRC professional because ISO 27001 is not merely an information-security technology framework. It provides a structured management system for governing information security.

---

# 24. Example – Enterprise ISO 27001 ISMS

Consider an organization operating cloud-based customer services.

```text
Business Context
      ↓
Customer Information
      ↓
Regulatory Requirements
      ↓
ISMS Scope
      ↓
Security Governance
      ↓
Risk Assessment
      ↓
Risk Treatment
      ↓
SoA
      ↓
Security Controls
      ↓
Operational Processes
      ↓
Evidence
      ↓
Internal Audit
      ↓
Management Review
      ↓
Corrective Actions
      ↓
Continual Improvement
```

The ISMS therefore creates a traceable relationship between the organization's business environment and its information-security activities.

---

# 25. ISMS Traceability Model

One of the strongest ways to visualize the ISMS is through traceability:

```text
Business Context
       ↓
Security Requirements
       ↓
Risks
       ↓
Risk Treatment
       ↓
Controls
       ↓
Control Activities
       ↓
Evidence
       ↓
Testing
       ↓
Performance
       ↓
Management Decisions
       ↓
Improvement
```

This demonstrates how ISO 27001 connects **business requirements, risk, controls, evidence, assurance, and management decisions**.

---

# 26. Executive View of the ISMS

At executive level, the entire ISMS can be simplified to:

```text
                  BUSINESS
                     ↓
                INFORMATION
                     ↓
                    RISK
                     ↓
                  CONTROLS
                     ↓
                PERFORMANCE
                     ↓
                  ASSURANCE
                     ↓
               MANAGEMENT
                 DECISIONS
                     ↓
                IMPROVEMENT
                     ↺
```

The ultimate purpose is not simply to achieve certification.

The ISMS should help the organization **systematically manage information-security risks and continually improve its security posture**.

---

# 27. Complete ISO 27001 ISMS Structure

The complete conceptual model is:

```text
                         ORGANIZATION
                              ↓
                   ┌─────────────────────┐
                   │    ISMS CONTEXT     │
                   └─────────────────────┘
                              ↓
                         LEADERSHIP
                              ↓
                           POLICY
                              ↓
                          PLANNING
                              ↓
                ┌─────────────┴─────────────┐
                ↓                           ↓
          RISK MANAGEMENT              OBJECTIVES
                ↓                           ↓
                └─────────────┬─────────────┘
                              ↓
                       RISK TREATMENT
                              ↓
                             SoA
                              ↓
                    CONTROL IMPLEMENTATION
                              ↓
                          OPERATION
                              ↓
                         EVIDENCE
                              ↓
                ┌─────────────┴─────────────┐
                ↓                           ↓
            MONITORING                    AUDIT
                ↓                           ↓
                └─────────────┬─────────────┘
                              ↓
                     MANAGEMENT REVIEW
                              ↓
                    FINDINGS / NONCONFORMITY
                              ↓
                     CORRECTIVE ACTION
                              ↓
                    CONTINUAL IMPROVEMENT
                              ↺
```

The central principle is:

> **An ISO 27001 ISMS is a management system that connects organizational context, leadership, risk management, controls, operational processes, evidence, performance evaluation, and continual improvement into a structured approach for managing information-security risk.**


# 18.6 ISO 27001 Diagrams

### Part 2 – ISO 27001 Risk Management Process

Risk management is one of the central mechanisms through which an ISO 27001 ISMS determines **what information-security risks the organization faces, how those risks should be evaluated, and how they should be treated**.

A simplified model is:

```text
Organizational Context
        ↓
Risk Assessment
        ↓
Risk Identification
        ↓
Risk Analysis
        ↓
Risk Evaluation
        ↓
Risk Treatment
        ↓
Residual Risk
        ↓
Risk Acceptance / Further Treatment
        ↺
Monitoring and Review
```

The important principle is that risk management should be **systematic, repeatable, and aligned with the organization's defined risk criteria**.

---

# 1. ISO 27001 Risk Management Concept

At a high level:

```text
                 BUSINESS CONTEXT
                        ↓
                 INFORMATION ASSETS
                        ↓
                      THREATS
                        ↓
                  VULNERABILITIES
                        ↓
                       RISK
                        ↓
                RISK ASSESSMENT
                        ↓
                 RISK TREATMENT
                        ↓
                     CONTROLS
                        ↓
                 RESIDUAL RISK
```

The purpose is not simply to identify threats.

The organization needs to understand how information-security risks could affect its objectives and determine appropriate treatment.

---

# 2. Establishing the Risk Context

Before assessing individual risks, the organization should establish the context in which risk management operates.

This includes defining:

```text
Risk Criteria
Risk Appetite / Acceptance Criteria
Assessment Methodology
Scoring Method
Assessment Scope
Relevant Assets / Processes
Risk Owners
```

A simplified model is:

```text
Organization
     ↓
Business Objectives
     ↓
Risk Context
     ↓
Risk Criteria
     ↓
Risk Assessment Methodology
     ↓
Risk Assessment
```

Without predefined criteria, different assessors may evaluate similar risks inconsistently.

---

# 3. Risk Assessment Methodology

An organization should establish a methodology for consistently assessing information-security risks.

For example:

```text
Likelihood
     +
Impact
     ↓
Risk Level
```

A common conceptual model is:

```text
Risk = Likelihood × Impact
```

The exact methodology, scoring scale, and calculation should be defined by the organization's risk assessment process.

---

# 4. Likelihood

Likelihood represents the possibility that a risk event could occur.

A simplified scale might be:

```text
1 – Rare
2 – Unlikely
3 – Possible
4 – Likely
5 – Almost Certain
```

For example:

```text
Threat:
Phishing Attack

Likelihood:
4 – Likely
```

The organization should define what each rating means rather than relying purely on subjective judgment.

---

# 5. Impact

Impact represents the potential consequences if the risk occurs.

Information-security impact can involve:

```text
Confidentiality
Integrity
Availability
Financial Loss
Regulatory Consequences
Reputation
Customer Impact
Operational Disruption
```

A simplified scale might be:

```text
1 – Insignificant
2 – Minor
3 – Moderate
4 – Major
5 – Severe
```

For example:

```text
Risk:
Compromise of Customer Database

Impact:
5 – Severe
```

---

# 6. Risk Matrix

Likelihood and impact can be visualized through a risk matrix.

```text
                    IMPACT
              Low    Medium    High
           ┌────────┬────────┬────────┐
Low        │   Low  │   Low  │ Medium │
           ├────────┼────────┼────────┤
Medium     │   Low  │ Medium │  High  │
LIKELIHOOD ├────────┼────────┼────────┤
High       │ Medium │  High  │Critical│
           └────────┴────────┴────────┘
```

The matrix helps organizations categorize risk according to their established criteria.

---

# 7. Risk Identification

Risk identification determines what could negatively affect the confidentiality, integrity, or availability of information and related business objectives.

A simplified flow is:

```text
Business Process
      ↓
Information Asset
      ↓
Threat
      ↓
Vulnerability
      ↓
Potential Event
      ↓
Consequence
      ↓
Risk
```

For example:

```text
Customer Database
      ↓
External Attacker
      ↓
Unpatched Vulnerability
      ↓
System Exploitation
      ↓
Unauthorized Access
      ↓
Data Breach Risk
```

---

# 8. Asset-Based Risk Identification

An organization can begin with its information assets.

```text
Information Asset
       ↓
Asset Owner
       ↓
Business Value
       ↓
Threats
       ↓
Vulnerabilities
       ↓
Risk Scenarios
```

Examples of assets include:

```text
Customer Database
Payment Platform
Cloud Environment
Employee Information
Source Code
Network Infrastructure
Security Credentials
Business Applications
```

This approach helps establish a relationship between assets and risks.

---

# 9. Process-Based Risk Identification

Risk can also be identified by business process.

```text
Business Process
       ↓
Process Activity
       ↓
Information Used
       ↓
Threats / Vulnerabilities
       ↓
Risk Scenario
```

For example:

```text
Online Payment
      ↓
Payment Processing
      ↓
Customer Financial Data
      ↓
Fraud / Data Theft
      ↓
Financial and Regulatory Risk
```

This approach is particularly useful when the organization wants to connect cybersecurity risk directly to business operations.

---

# 10. Threat-Based Risk Identification

Another approach begins with threats.

```text
Threat
  ↓
Potential Target
  ↓
Vulnerability
  ↓
Risk Event
  ↓
Business Impact
```

For example:

```text
Ransomware
    ↓
Critical Server
    ↓
Unpatched Software
    ↓
System Encryption
    ↓
Service Disruption
```

Different organizations may combine asset-based, process-based, and threat-based approaches.

---

# 11. Risk Scenario

A useful risk assessment should describe the scenario rather than simply assigning a label.

Weak description:

```text
"Cybersecurity Risk"
```

More useful:

```text
"An attacker could exploit an unpatched internet-facing
application and gain unauthorized access to customer data,
resulting in regulatory, financial, and reputational impact."
```

A risk scenario can therefore be represented as:

```text
Threat
  +
Vulnerability
  +
Asset / Process
  +
Potential Event
  +
Consequence
  =
Risk Scenario
```

---

# 12. Risk Analysis

After identifying a risk, the organization analyzes its characteristics.

```text
Risk Scenario
      ↓
Likelihood Analysis
      ↓
Impact Analysis
      ↓
Existing Controls
      ↓
Risk Level
```

For example:

```text
Risk:
Ransomware against critical server

Likelihood:
High

Impact:
High

Risk Level:
Critical
```

The organization's defined methodology should determine how these ratings are established.

---

# 13. Existing Controls

Risk assessment should consider existing controls.

```text
Risk Scenario
      ↓
Existing Controls
      ↓
Control Effectiveness
      ↓
Current Risk
```

For example:

```text
Risk:
Unauthorized privileged access

Existing Controls:
MFA
Privileged Access Management
Access Reviews
SIEM Monitoring
```

The organization should consider whether those controls actually reduce the likelihood or impact of the risk.

---

# 14. Inherent Risk

Inherent risk represents the level of risk before considering the effect of controls.

Conceptually:

```text
Threat
 +
Vulnerability
 +
Potential Impact
        ↓
INHERENT RISK
```

For example:

```text
Risk:
Ransomware affecting critical systems

Likelihood: High
Impact: High

        ↓

Inherent Risk:
Critical
```

This provides a baseline for evaluating the effect of risk treatment and controls.

---

# 15. Residual Risk

Residual risk is the risk remaining after controls and risk treatment have been considered.

```text
Inherent Risk
      ↓
Controls / Treatment
      ↓
Residual Risk
```

For example:

```text
Inherent Risk
     ↓
Critical
     ↓
MFA
EDR
Network Segmentation
Backups
Incident Response
     ↓
Residual Risk
     ↓
Medium
```

The residual risk should then be evaluated against the organization's acceptance criteria.

---

# 16. Inherent-to-Residual Risk Model

The complete model can be visualized as:

```text
                INHERENT RISK
                     ↓
              Risk Treatment
                     ↓
               Controls
                     ↓
           Control Effectiveness
                     ↓
               RESIDUAL RISK
                     ↓
            Risk Acceptance?
                ↙        ↘
              Yes         No
               ↓           ↓
            Monitor     Further
                        Treatment
```

This is one of the most important relationships in risk management.

---

# 17. Risk Evaluation

Risk evaluation determines whether the assessed risk is acceptable.

```text
Risk Level
    ↓
Compare Against
Risk Criteria
    ↓
┌──────────────┴──────────────┐
↓                             ↓
Acceptable                 Unacceptable
↓                             ↓
Accept                       Treat
```

For example:

```text
Residual Risk:
Low

Risk Acceptance Criteria:
Low

        ↓

Risk Accepted
```

Whereas:

```text
Residual Risk:
High

Risk Acceptance Criteria:
Medium

        ↓

Further Treatment Required
```

---

# 18. Risk Treatment

Once risks have been evaluated, the organization determines how they should be treated.

Common risk treatment strategies include:

```text
Avoid
Modify / Reduce
Share / Transfer
Retain / Accept
```

A simplified decision model is:

```text
                   RISK
                     ↓
             Treatment Decision
                     ↓
      ┌────────┬─────┼─────┬────────┐
      ↓        ↓     ↓     ↓        ↓
    Avoid    Reduce Transfer Accept  Other
```

The appropriate option depends on the organization's risk criteria and business circumstances.

---

# 19. Risk Avoidance

Risk avoidance involves changing the activity so that the risk no longer applies.

```text
Risky Activity
      ↓
Decision to Stop / Change Activity
      ↓
Risk Avoided
```

For example:

```text
High-Risk Unsupported Application
          ↓
Application Decommissioned
          ↓
Associated Risk Removed
```

Risk avoidance may not always be practical because the activity may provide important business value.

---

# 20. Risk Reduction

Risk reduction involves implementing controls to reduce likelihood, impact, or both.

```text
Risk
 ↓
Additional Controls
 ↓
Reduced Likelihood / Impact
 ↓
Lower Residual Risk
```

For example:

```text
Risk:
Unauthorized Access

Controls:
MFA
+
Least Privilege
+
Access Reviews

        ↓

Reduced Risk
```

This is one of the most common approaches in information-security risk management.

---

# 21. Risk Sharing or Transfer

Some risks may be shared or transferred to another party.

Examples include:

```text
Cyber Insurance
Third-Party Services
Contractual Risk Allocation
Outsourcing
```

A simplified model is:

```text
Risk
 ↓
Transfer / Share
 ↓
Third Party / Insurer
 ↓
Residual Organizational Exposure
```

Risk transfer does not necessarily eliminate the organization's accountability or all of its exposure.

---

# 22. Risk Acceptance

Risk acceptance means management formally decides that the remaining risk is acceptable.

```text
Residual Risk
      ↓
Compare with Risk Criteria
      ↓
Within Acceptance Level?
      ↓
YES
      ↓
Management Acceptance
      ↓
Monitor
```

Risk acceptance should be based on defined authority and organizational criteria.

---

# 23. Risk Treatment Plan

Risk treatment decisions should be translated into actionable activities.

```text
Risk
 ↓
Treatment Decision
 ↓
Treatment Action
 ↓
Control
 ↓
Owner
 ↓
Target Date
 ↓
Implementation
 ↓
Validation
```

For example:

```text
Risk:
Critical vulnerability

Treatment:
Reduce

Action:
Deploy security patch

Owner:
Infrastructure Team

Target:
Within defined remediation SLA
```

This creates accountability for risk treatment.

---

# 24. Risk Owner

Each significant risk should have an appropriate risk owner.

```text
Risk
 ↓
Risk Owner
 ↓
Risk Assessment
 ↓
Treatment Decision
 ↓
Acceptance / Escalation
```

The risk owner should have sufficient authority and knowledge to make or approve relevant decisions.

The risk owner is not necessarily the person who performs the technical control.

For example:

```text
Business Risk Owner
        ↓
Accepts / Manages Risk

Security Team
        ↓
Implements Security Controls
```

These responsibilities should be clearly defined.

---

# 25. Risk Treatment and Controls

The relationship between risk treatment and controls can be visualized as:

```text
Risk
 ↓
Treatment Decision
 ↓
Control Requirement
 ↓
Control Design
 ↓
Control Implementation
 ↓
Control Operation
 ↓
Control Testing
 ↓
Residual Risk
```

This creates a traceable relationship between a risk and the controls implemented to address it.

---

# 26. Statement of Applicability Relationship

The risk management process can connect to the Statement of Applicability.

```text
Risk Assessment
       ↓
Risk Treatment
       ↓
Control Requirements
       ↓
Statement of Applicability
       ↓
Applicable Controls
       ↓
Implementation
```

The SoA therefore forms an important bridge between risk treatment decisions and the organization's selected security controls.

---

# 27. Risk Acceptance and Escalation

Not all risks can be accepted at the same organizational level.

A simplified model is:

```text
Risk
 ↓
Residual Risk
 ↓
Compare with Authority Level
 ↓
┌───────────────┴───────────────┐
↓                               ↓
Within Authority            Exceeds Authority
↓                               ↓
Accept                        Escalate
                                ↓
                         Senior Management
```

This helps ensure that significant risks receive appropriate management attention.

---

# 28. Risk Monitoring

Risk management does not end when a risk is treated.

Risks should be monitored because their conditions can change.

```text
Risk
 ↓
Treatment
 ↓
Residual Risk
 ↓
Monitoring
 ↓
New Threats?
New Vulnerabilities?
Business Changes?
Technology Changes?
Regulatory Changes?
 ↓
Risk Reassessment
```

This creates a continuous risk management cycle.

---

# 29. Risk Review Triggers

A risk assessment may need to be revisited when significant changes occur.

Examples include:

```text
Major Technology Change
New Business Service
Cloud Migration
Acquisition / Merger
New Regulation
Major Cyber Incident
Significant Vulnerability
Supplier Change
Organizational Change
Change in Threat Landscape
```

The process can be visualized as:

```text
Risk Assessment
      ↓
Risk Treatment
      ↓
Monitoring
      ↓
Significant Change?
   ↙           ↘
 No            Yes
 ↓              ↓
Continue     Reassess
                ↓
          Updated Risk
```

---

# 30. Risk Register

A risk register provides a structured record of assessed risks.

A typical conceptual structure is:

```text
Risk ID
   ↓
Risk Description
   ↓
Risk Owner
   ↓
Asset / Process
   ↓
Threat
   ↓
Vulnerability
   ↓
Inherent Risk
   ↓
Existing Controls
   ↓
Treatment
   ↓
Residual Risk
   ↓
Acceptance
   ↓
Monitoring
```

The risk register becomes an important GRC management artifact.

---

# 31. Risk Register Example

A simplified example:

| Risk                           | Inherent Risk | Existing Controls                | Treatment    | Residual Risk | Owner             |
| ------------------------------ | ------------- | -------------------------------- | ------------ | ------------- | ----------------- |
| Unauthorized privileged access | High          | MFA, PAM, access reviews         | Reduce       | Medium        | IT Manager        |
| Ransomware                     | Critical      | EDR, segmentation, backups       | Reduce       | High          | CISO              |
| Supplier data exposure         | High          | Due diligence, contract controls | Reduce/Share | Medium        | Procurement       |
| Legacy application compromise  | High          | Network isolation, monitoring    | Reduce       | Medium        | Application Owner |

The actual risk ratings should be based on the organization's defined methodology.

---

# 32. Risk Communication

Risk management should communicate relevant information to decision-makers.

```text
Risk Assessment
      ↓
Risk Register
      ↓
Risk Reporting
      ↓
Management
      ↓
Decision
```

Executive reporting may focus on:

```text
Top Risks
Risk Trends
Residual Risk
Risk Appetite Breaches
Treatment Progress
Overdue Actions
Emerging Risks
```

Technical teams may require significantly more detailed information.

---

# 33. Risk-Based Decision Making

The purpose of risk management is ultimately to support decisions.

```text
                RISK INFORMATION
                       ↓
                MANAGEMENT ANALYSIS
                       ↓
                 DECISION OPTIONS
                       ↓
             ┌─────────┼─────────┐
             ↓         ↓         ↓
           Avoid     Reduce    Accept
             ↓         ↓         ↓
             └─────────┼─────────┘
                       ↓
                 BUSINESS DECISION
```

This demonstrates why risk management is a governance activity rather than simply a cybersecurity exercise.

---

# 34. Example – Cloud Migration

Consider an organization migrating a critical application to the cloud.

### Step 1 – Identify Risk

```text
Cloud Migration
      ↓
Potential Misconfiguration
      ↓
Unauthorized Data Exposure
      ↓
Security Risk
```

### Step 2 – Assess

```text
Likelihood: Medium
Impact: High
      ↓
Inherent Risk: High
```

### Step 3 – Treatment

```text
Cloud Security Controls
+
Encryption
+
IAM
+
Configuration Monitoring
+
Logging
```

### Step 4 – Residual Risk

```text
High Inherent Risk
      ↓
Security Controls
      ↓
Medium Residual Risk
```

### Step 5 – Decision

```text
Medium Residual Risk
      ↓
Within Acceptance Criteria?
      ↓
Yes
      ↓
Risk Accepted + Monitored
```

---

# 35. Example – Ransomware Risk

```text
                 RANSOMWARE
                     ↓
                Vulnerability
                     ↓
                 Risk Event
                     ↓
                INHERENT RISK
                     ↓
        ┌────────────┼────────────┐
        ↓            ↓            ↓
       EDR        Backups     Segmentation
        ↓            ↓            ↓
        └────────────┼────────────┘
                     ↓
               RESIDUAL RISK
                     ↓
             Management Review
                     ↓
            Accept / Further Treat
```

This illustrates the connection between risk identification, controls, and residual risk.

---

# 36. Risk Management Lifecycle

The complete ISO 27001 risk management concept can be visualized as:

```text
                 ESTABLISH CONTEXT
                        ↓
                DEFINE RISK CRITERIA
                        ↓
                  IDENTIFY RISKS
                        ↓
                   ANALYZE RISKS
                        ↓
                  EVALUATE RISKS
                        ↓
                 TREAT THE RISKS
                        ↓
                IMPLEMENT CONTROLS
                        ↓
                 RESIDUAL RISK
                        ↓
                ACCEPT / ESCALATE
                        ↓
                   MONITOR
                        ↓
                    REVIEW
                        ↓
                  REASSESS
                        ↺
```

This is a continuous process rather than a one-time exercise.

---

# 37. Integrated ISO 27001 Risk Model

A broader GRC visualization is:

```text
                    BUSINESS OBJECTIVES
                           ↓
                    ORGANIZATIONAL CONTEXT
                           ↓
                       RISK CRITERIA
                           ↓
                    RISK IDENTIFICATION
                           ↓
                      RISK ANALYSIS
                           ↓
                     RISK EVALUATION
                           ↓
                    ┌──────┴──────┐
                    ↓             ↓
                 ACCEPT         TREAT
                    ↓             ↓
                 Monitor      Risk Controls
                                  ↓
                            Implementation
                                  ↓
                            Effectiveness
                                  ↓
                            RESIDUAL RISK
                                  ↓
                       Acceptance / Escalation
                                  ↓
                              Monitoring
                                  ↺
```

---

# 38. Risk Management Traceability

For GRC professionals, traceability is particularly important.

The relationship can be represented as:

```text
Business Objective
        ↓
Security Requirement
        ↓
Risk
        ↓
Risk Treatment
        ↓
Control
        ↓
Control Activity
        ↓
Evidence
        ↓
Testing
        ↓
Control Effectiveness
        ↓
Residual Risk
        ↓
Management Decision
```

This allows an organization to answer questions such as:

* What business objective does this risk affect?
* What controls address the risk?
* Who owns the risk?
* What evidence demonstrates control operation?
* Is the control effective?
* What residual risk remains?
* Has management accepted that residual risk?

---

# 39. Executive Risk View

At the executive level, the detailed process can be simplified to:

```text
                 TOP RISKS
                     ↓
              INHERENT RISK
                     ↓
              RISK TREATMENT
                     ↓
             CONTROL EFFECTIVENESS
                     ↓
              RESIDUAL RISK
                     ↓
               RISK APPETITE
                     ↓
              MANAGEMENT ACTION
```

This allows executives to focus on the questions that matter most:

> **What are our most significant information-security risks?**

> **What are we doing about them?**

> **How effective are our controls?**

> **What risk remains?**

> **Is that residual risk acceptable?**

The central principle is that **ISO 27001 risk management connects organizational context and objectives to risk identification, analysis, evaluation, treatment, controls, residual risk, and management decisions through a structured and continually monitored process.**



