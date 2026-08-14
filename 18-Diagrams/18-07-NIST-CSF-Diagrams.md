# 18.7 NIST Cybersecurity Framework Diagrams

### Part 1 – NIST CSF Core Functions

The **NIST Cybersecurity Framework (CSF)** provides a structured way for organizations to understand, assess, prioritize, and communicate cybersecurity risk.

The current **NIST CSF 2.0** organizes cybersecurity activities around six Core Functions:

```text
GOVERN
   ↓
IDENTIFY
   ↓
PROTECT
   ↓
DETECT
   ↓
RESPOND
   ↓
RECOVER
```

Unlike a strictly linear process, these functions are intended to operate **concurrently and continuously**, with **Govern** providing overarching cybersecurity risk management and direction.

---

# 1. What Is the NIST CSF?

The NIST CSF is a cybersecurity risk-management framework developed by the **National Institute of Standards and Technology (NIST)**.

It provides a common language for discussing cybersecurity capabilities and outcomes.

A simplified model is:

```text
                    CYBERSECURITY RISK
                           ↓
                    NIST CSF 2.0
                           ↓
        ┌──────────────────┼──────────────────┐
        ↓                  ↓                  ↓
     GOVERN             MANAGE             IMPROVE
        ↓
     CYBERSECURITY
     RISK MANAGEMENT
```

The six Core Functions provide the primary structure for organizing cybersecurity outcomes.

---

# 2. The Six NIST CSF 2.0 Core Functions

The six Functions are:

```text
┌──────────────┐
│    GOVERN    │
└──────┬───────┘
       ↓
┌──────────────┐
│   IDENTIFY   │
└──────┬───────┘
       ↓
┌──────────────┐
│   PROTECT    │
└──────┬───────┘
       ↓
┌──────────────┐
│    DETECT    │
└──────┬───────┘
       ↓
┌──────────────┐
│   RESPOND    │
└──────┬───────┘
       ↓
┌──────────────┐
│   RECOVER    │
└──────────────┘
```

However, this should not be interpreted as a simple one-directional sequence.

The Functions interact continuously:

```text
                  GOVERN
                ↙   ↓   ↘
          IDENTIFY PROTECT DETECT
                ↘   ↓   ↙
                 RESPOND
                    ↓
                  RECOVER
                    ↺
```

---

# 3. Govern

**Govern** establishes and monitors the organization's cybersecurity risk-management strategy, expectations, and policy.

It provides the governance foundation for the other Functions.

A simplified model is:

```text
                    GOVERN
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
      Strategy       Policy        Oversight
        ↓              ↓              ↓
        └──────────────┼──────────────┘
                       ↓
              Cybersecurity Direction
```

Govern addresses areas such as:

```text
Organizational Context
Risk Management Strategy
Roles and Responsibilities
Policy
Cybersecurity Supply Chain Risk Management
Oversight
```

For GRC professionals, **Govern is particularly important** because it connects cybersecurity activities to organizational governance and enterprise risk management.

---

# 4. Identify

**Identify** focuses on understanding the organization's cybersecurity risks.

A simplified model is:

```text
                 IDENTIFY
                     ↓
        ┌────────────┼────────────┐
        ↓            ↓            ↓
      Assets        Risks       Threats
        ↓            ↓            ↓
      Data        Vulnerabilities
        ↓            ↓            ↓
        └────────────┼────────────┘
                     ↓
             Risk Understanding
```

Examples include understanding:

```text
Assets
Data
Systems
Business Processes
Dependencies
Threats
Vulnerabilities
Cybersecurity Risks
```

The organization needs an accurate understanding of what it owns, operates, depends on, and needs to protect.

---

# 5. Protect

**Protect** focuses on implementing safeguards to manage identified cybersecurity risks.

A simplified model is:

```text
                   PROTECT
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
    Identity       Training        Data
    Management      & Awareness     Security
       ↓              ↓              ↓
    Access         Safeguards      Platform
    Control                         Security
```

Examples include:

```text
Identity Management
Access Control
Security Awareness
Data Security
Platform Security
Technology Infrastructure Resilience
```

The objective is to reduce the likelihood or impact of cybersecurity events.

---

# 6. Detect

**Detect** focuses on discovering and analyzing possible cybersecurity attacks, anomalies, or compromises.

A simplified model is:

```text
                 DETECT
                   ↓
          ┌────────┼────────┐
          ↓        ↓        ↓
      Monitoring  Events   Analysis
          ↓        ↓        ↓
          └────────┼────────┘
                   ↓
              Detection
                   ↓
              Investigation
```

Examples include:

```text
Security Monitoring
Log Analysis
Anomaly Detection
Threat Detection
Security Event Analysis
```

Detection provides the information needed to determine whether a cybersecurity event may have occurred.

---

# 7. Respond

**Respond** focuses on taking action when a cybersecurity incident or event is detected.

A simplified model is:

```text
                 RESPOND
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
    Incident      Analysis   Mitigation
    Management       ↓           ↓
        ↓           Communication
        └───────────┼───────────┘
                    ↓
                Containment
                    ↓
                 Recovery
```

Examples include:

```text
Incident Management
Incident Analysis
Incident Response Reporting
Incident Mitigation
Communication
```

The objective is to contain and manage the impact of cybersecurity incidents.

---

# 8. Recover

**Recover** focuses on restoring affected assets, systems, and operations after a cybersecurity incident.

A simplified model is:

```text
                  RECOVER
                     ↓
          Recovery Execution
                     ↓
              Restoration
                     ↓
             Verification
                     ↓
              Communication
                     ↓
             Improvements
```

Examples include:

```text
Incident Recovery
Recovery Communication
Recovery Verification
Business Restoration
Lessons Learned
```

Recovery is closely connected to business continuity and disaster recovery.

---

# 9. Govern as the Foundation

One of the most important changes in CSF 2.0 is the addition of **Govern** as a Core Function.

The conceptual model is:

```text
                    GOVERN
              ┌───────┼───────┐
              ↓       ↓       ↓
          IDENTIFY  PROTECT  DETECT
              ↓       ↓       ↓
              └───────┼───────┘
                      ↓
                   RESPOND
                      ↓
                   RECOVER
```

Govern establishes the direction within which the other cybersecurity activities operate.

For a GRC professional, this means cybersecurity should not be treated only as a technical function.

It is also a **governance and risk-management responsibility**.

---

# 10. Govern and Enterprise Risk

Govern connects cybersecurity risk with broader organizational risk.

```text
                ENTERPRISE
                    ↓
              BUSINESS OBJECTIVES
                    ↓
                ENTERPRISE RISK
                    ↓
          CYBERSECURITY RISK STRATEGY
                    ↓
                  GOVERN
                    ↓
       ┌────────────┼────────────┐
       ↓            ↓            ↓
    Identify      Protect      Detect
       ↓            ↓            ↓
       └────────────┼────────────┘
                    ↓
                 Respond
                    ↓
                  Recover
```

This helps ensure that cybersecurity decisions support business priorities.

---

# 11. Identify and Asset Management

A cybersecurity program cannot effectively protect what the organization does not understand.

A simplified relationship is:

```text
                 ORGANIZATION
                       ↓
                     ASSETS
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
       Data          Systems        Services
        ↓              ↓              ↓
        └──────────────┼──────────────┘
                       ↓
                  Risk Analysis
```

Asset understanding provides the foundation for risk-based protection.

---

# 12. Identify and Risk Assessment

The Identify Function is closely connected to risk management.

```text
Assets
  ↓
Threats
  ↓
Vulnerabilities
  ↓
Potential Events
  ↓
Business Impact
  ↓
Cybersecurity Risk
```

The resulting risk information can then influence protection priorities.

---

# 13. Protect and Security Controls

The Protect Function represents safeguards that reduce cybersecurity risk.

```text
Risk
 ↓
Protection Requirements
 ↓
Security Controls
 ↓
Implementation
 ↓
Protection Capability
```

Examples:

```text
MFA
Encryption
Access Controls
Secure Configuration
Security Training
Network Protection
Data Protection
```

The actual controls selected should be appropriate to the organization's risks and requirements.

---

# 14. Detect and Security Monitoring

Detection provides visibility into cybersecurity events.

```text
Technology
    ↓
Logs / Events
    ↓
Monitoring
    ↓
Analysis
    ↓
Potential Cybersecurity Event
```

A mature detection capability may combine:

```text
SIEM
EDR
Network Monitoring
Cloud Monitoring
Identity Monitoring
Threat Intelligence
Security Analytics
```

Detection should produce actionable information for response.

---

# 15. Respond and Incident Management

When an event is identified, response activities become important.

```text
Detection
   ↓
Triage
   ↓
Incident Analysis
   ↓
Containment
   ↓
Mitigation
   ↓
Communication
   ↓
Resolution
```

The response process should be aligned with the organization's incident-management capabilities.

---

# 16. Recover and Business Resilience

Recovery connects cybersecurity with organizational resilience.

```text
Cybersecurity Incident
        ↓
Business Disruption
        ↓
Recovery Strategy
        ↓
System Restoration
        ↓
Service Recovery
        ↓
Business Operations
```

Recovery planning may involve:

```text
Backups
Disaster Recovery
Business Continuity
Alternate Systems
Recovery Procedures
Crisis Communications
```

---

# 17. Relationship Between the Functions

The Functions can be connected as:

```text
                         GOVERN
                           ↓
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
       IDENTIFY         PROTECT           DETECT
          ↓                ↓                ↓
          └────────────────┼────────────────┘
                           ↓
                        RESPOND
                           ↓
                        RECOVER
                           ↓
                       IMPROVE
                           ↺
```

The improvement feedback loop means lessons from response and recovery can influence future identification, protection, and governance activities.

---

# 18. Cybersecurity Lifecycle

The six Functions can be viewed as a continuous cybersecurity lifecycle:

```text
        GOVERN
           ↓
       IDENTIFY
           ↓
        PROTECT
           ↓
         DETECT
           ↓
        RESPOND
           ↓
        RECOVER
           ↓
     LESSONS LEARNED
           ↓
        GOVERN
           ↺
```

This illustrates the continuous nature of cybersecurity risk management.

---

# 19. Example – Ransomware

Consider a ransomware scenario.

### Govern

```text
Cybersecurity Strategy
        ↓
Risk Appetite
        ↓
Incident Response Policy
```

### Identify

```text
Critical Systems
        ↓
Ransomware Risk
        ↓
Business Impact
```

### Protect

```text
EDR
MFA
Network Segmentation
Backups
Security Awareness
```

### Detect

```text
Endpoint Alerts
        ↓
Security Monitoring
        ↓
Ransomware Detection
```

### Respond

```text
Incident Declaration
        ↓
Containment
        ↓
System Isolation
        ↓
Investigation
```

### Recover

```text
Restore Systems
        ↓
Validate Systems
        ↓
Resume Operations
        ↓
Lessons Learned
```

The Functions therefore work together rather than operating as isolated activities.

---

# 20. Example – Cloud Environment

A cloud security program can also be mapped to the Functions.

```text
GOVERN
Cloud Security Strategy
        ↓
IDENTIFY
Cloud Assets + Risks
        ↓
PROTECT
IAM + Encryption + Configuration
        ↓
DETECT
Cloud Monitoring
        ↓
RESPOND
Incident Management
        ↓
RECOVER
Service Restoration
```

This demonstrates that the CSF is technology-neutral and can be applied across different environments.

---

# 21. NIST CSF and GRC

For GRC professionals, the six Functions can be connected to traditional GRC disciplines.

```text
                    NIST CSF
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
    GOVERN           IDENTIFY       PROTECT
        ↓              ↓              ↓
   Governance         Risk          Controls
   Policy             Assessment    Compliance
   Oversight
        ↓              ↓              ↓
        └──────────────┼──────────────┘
                       ↓
                 DETECT / RESPOND
                       ↓
                    Assurance
                       ↓
                    RECOVER
                       ↓
                 Resilience
```

This makes the CSF particularly useful as a common language between cybersecurity, risk, compliance, audit, and executive management.

---

# 22. NIST CSF and ISO 27001

The CSF can also be used alongside ISO 27001.

A conceptual relationship is:

```text
                 ISO 27001 ISMS
                       ↓
                Risk Management
                       ↓
              Security Controls
                       ↓
                NIST CSF Mapping
                       ↓
       ┌───────────────┼───────────────┐
       ↓               ↓               ↓
    GOVERN          IDENTIFY         PROTECT
       ↓               ↓               ↓
     DETECT          RESPOND         RECOVER
```

The two frameworks serve different purposes and can be mapped or used together rather than treated as competing frameworks.

---

# 23. NIST CSF and Control Frameworks

The CSF can also provide a high-level structure for organizing controls from other frameworks.

```text
              NIST CSF
                  ↓
       ┌──────────┼──────────┐
       ↓          ↓          ↓
      ISO       COBIT      CIS
    Controls   Practices   Controls
       ↓          ↓          ↓
       └──────────┼──────────┘
                  ↓
          Organizational
        Security Capabilities
```

This can help organizations communicate cybersecurity capabilities without requiring every executive stakeholder to understand individual technical controls.

---

# 24. CSF Core Functions and GRC Traceability

A GRC implementation can establish traceability such as:

```text
Business Objective
       ↓
Cybersecurity Risk
       ↓
NIST CSF Function
       ↓
Category / Outcome
       ↓
Control
       ↓
Control Activity
       ↓
Evidence
       ↓
Assessment
       ↓
Risk Status
```

This creates a bridge between the framework and operational GRC processes.

---

# 25. Executive View

Executives generally do not need to see every individual security control.

The CSF Functions can provide a high-level view:

```text
                    GOVERN
                       ↓
             Are we managing risk?
                       ↓
                   IDENTIFY
                       ↓
             Do we understand risk?
                       ↓
                    PROTECT
                       ↓
             Are we reducing risk?
                       ↓
                    DETECT
                       ↓
             Can we detect attacks?
                       ↓
                    RESPOND
                       ↓
             Can we contain incidents?
                       ↓
                    RECOVER
                       ↓
             Can we restore operations?
```

This makes the CSF useful as an executive communication model.

---

# 26. CSF Core Functions and Metrics

Organizations can associate metrics with each Function.

```text
GOVERN
↓
Risk Governance Metrics

IDENTIFY
↓
Asset / Risk Visibility Metrics

PROTECT
↓
Control Coverage Metrics

DETECT
↓
Detection Metrics

RESPOND
↓
Incident Response Metrics

RECOVER
↓
Recovery Metrics
```

Examples:

```text
Govern:
Risk acceptance exceptions

Identify:
Percentage of critical assets inventoried

Protect:
MFA coverage

Detect:
Mean time to detect

Respond:
Mean time to contain

Recover:
Mean time to recover
```

The exact metrics should reflect organizational objectives and risk priorities.

---

# 27. CSF as a Management System View

The six Functions can be viewed as an integrated system:

```text
                     GOVERN
                        ↓
                Risk Direction
                        ↓
                    IDENTIFY
                        ↓
                Risk Understanding
                        ↓
                    PROTECT
                        ↓
                Risk Reduction
                        ↓
                     DETECT
                        ↓
                Risk Visibility
                        ↓
                    RESPOND
                        ↓
                Risk Containment
                        ↓
                    RECOVER
                        ↓
                Business Resilience
                        ↓
                    Lessons Learned
                        ↓
                      GOVERN
                        ↺
```

This shows the relationship between governance, risk management, cybersecurity operations, and resilience.

---

# 28. Complete NIST CSF 2.0 Core Function Model

The complete conceptual diagram is:

```text
                         GOVERN
                            ↓
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
         Strategy         Policy        Oversight
             ↓              ↓              ↓
             └──────────────┼──────────────┘
                            ↓
                         IDENTIFY
                            ↓
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
           Assets          Risk         Threats
             ↓              ↓              ↓
             └──────────────┼──────────────┘
                            ↓
                         PROTECT
                            ↓
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
          Identity        Data          Platform
          Security       Security       Security
             ↓              ↓              ↓
             └──────────────┼──────────────┘
                            ↓
                          DETECT
                            ↓
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
         Monitoring      Analysis       Detection
                            ↓
                         RESPOND
                            ↓
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
         Management     Mitigation    Communication
                            ↓
                          RECOVER
                            ↓
             ┌──────────────┼──────────────┐
             ↓              ↓              ↓
         Restoration     Verification  Communication
                            ↓
                      Lessons Learned
                            ↓
                         GOVERN
                            ↺
```

---

# 29. The Core Concept

The NIST CSF 2.0 Core Functions can ultimately be summarized as:

```text
GOVERN
   ↓
Understand how cybersecurity risk should be managed

IDENTIFY
   ↓
Understand cybersecurity risks

PROTECT
   ↓
Implement safeguards

DETECT
   ↓
Find potential cybersecurity events

RESPOND
   ↓
Take action against cybersecurity incidents

RECOVER
   ↓
Restore capabilities and improve resilience
```

The central principle is:

> **NIST CSF 2.0 provides a common structure for governing cybersecurity risk, understanding the organization's risk environment, implementing safeguards, detecting cybersecurity events, responding to incidents, and recovering capabilities.**

For a GRC professional, the most important perspective is that the CSF is **not simply a list of cybersecurity controls**. It provides a high-level operating model that can connect **governance, risk, controls, cybersecurity operations, incident management, resilience, metrics, and executive decision-making** into one common language.

# 18.7 NIST Cybersecurity Framework Diagrams

### Part 2 – Identify-to-Recover Security Lifecycle

The NIST Cybersecurity Framework can be viewed as a continuous cybersecurity lifecycle in which the organization understands its risks, implements safeguards, detects cybersecurity events, responds to incidents, and restores capabilities.

In **NIST CSF 2.0**, the six Core Functions are:

```text
GOVERN
   ↓
IDENTIFY
   ↓
PROTECT
   ↓
DETECT
   ↓
RESPOND
   ↓
RECOVER
   ↺
```

The important point is that this is **not a simple linear process**. Activities can occur simultaneously, and lessons from one Function can influence activities in the others.

---

# 1. From Identify to Recover

The security lifecycle can be represented as:

```text
                 IDENTIFY
                    ↓
              Understand Risk
                    ↓
                 PROTECT
                    ↓
              Reduce Risk
                    ↓
                  DETECT
                    ↓
             Detect Events
                    ↓
                 RESPOND
                    ↓
            Manage Incidents
                    ↓
                  RECOVER
                    ↓
           Restore Capabilities
                    ↓
              Lessons Learned
                    ↓
                 IDENTIFY
                    ↺
```

This creates a continuous cycle of cybersecurity risk management.

---

# 2. Identify

The **Identify** Function establishes an understanding of the organization's cybersecurity risks.

```text
IDENTIFY
   ↓
Assets
   ↓
Business Processes
   ↓
Dependencies
   ↓
Threats
   ↓
Vulnerabilities
   ↓
Potential Impacts
   ↓
Cybersecurity Risk
```

The organization should understand what needs protection and why it matters.

Examples include:

```text
Critical Applications
Sensitive Data
Cloud Services
Network Infrastructure
Identity Systems
Business Processes
Third-Party Services
```

---

# 3. Identify and Business Context

Cybersecurity risk should be considered within the broader business environment.

```text
Business Objectives
       ↓
Business Processes
       ↓
Information Assets
       ↓
Dependencies
       ↓
Threats
       ↓
Vulnerabilities
       ↓
Cybersecurity Risk
```

For example:

```text
Business Objective:
Provide Digital Banking

        ↓

Critical Asset:
Online Banking Platform

        ↓

Risk:
Unauthorized access

        ↓

Potential Impact:
Financial Loss
Reputational Damage
Regulatory Consequences
```

This ensures that cybersecurity priorities are connected to business importance.

---

# 4. Identify and Asset Inventory

An accurate asset inventory supports risk identification.

```text
                 ASSET INVENTORY
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
     Hardware        Software          Data
        ↓               ↓               ↓
      Cloud          Applications      Services
        ↓               ↓               ↓
        └───────────────┼───────────────┘
                        ↓
                  Risk Assessment
```

Assets may include:

```text
Servers
Endpoints
Applications
Databases
Cloud Resources
Networks
Identity Systems
Information
Third Parties
```

The level of inventory detail should be appropriate to organizational needs and risk.

---

# 5. Identify and Risk Assessment

Risk assessment translates information about assets and threats into risk information.

```text
Asset
 ↓
Threat
 ↓
Vulnerability
 ↓
Potential Event
 ↓
Likelihood
 ↓
Impact
 ↓
Risk
```

A simplified example:

```text
Critical Database
      ↓
Ransomware Threat
      ↓
Insufficient Segmentation
      ↓
Database Encryption
      ↓
High Business Impact
      ↓
High Cybersecurity Risk
```

This information helps determine protection priorities.

---

# 6. Protect

Once risks are understood, the organization implements safeguards.

```text
IDENTIFY
   ↓
Risk
   ↓
Protection Requirement
   ↓
PROTECT
   ↓
Safeguards
```

Examples include:

```text
Identity Management
Access Control
MFA
Encryption
Security Awareness
Secure Configuration
Data Protection
Technology Resilience
```

The objective is to reduce the likelihood or impact of cybersecurity events.

---

# 7. Identify → Protect Relationship

The relationship can be visualized as:

```text
Risk Identification
       ↓
Risk Prioritization
       ↓
Protection Requirements
       ↓
Security Controls
       ↓
Implementation
       ↓
Risk Reduction
```

For example:

```text
Risk:
Unauthorized privileged access

        ↓

Protection Requirement:

Strong privileged authentication

        ↓

Controls:

MFA
Privileged Access Management
Access Reviews

        ↓

Risk Reduction
```

This demonstrates the risk-based nature of cybersecurity protection.

---

# 8. Protect and Defense Layers

Protection usually involves multiple layers.

```text
                    PROTECT
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
      People         Process       Technology
        ↓              ↓              ↓
    Awareness       Policies        MFA
    Training        Procedures      Encryption
    Roles           Standards       EDR
```

A mature security program combines people, processes, and technology.

---

# 9. Detect

Even strong preventive controls cannot guarantee that every attack will be prevented.

Therefore, detection is required.

```text
PROTECT
   ↓
Security Controls
   ↓
Security Events
   ↓
Monitoring
   ↓
Analysis
   ↓
DETECT
   ↓
Potential Cybersecurity Incident
```

Examples include:

```text
SIEM
EDR
Network Monitoring
Cloud Security Monitoring
Identity Monitoring
Threat Intelligence
Anomaly Detection
```

---

# 10. Detect and Security Monitoring

A simplified monitoring architecture is:

```text
                  DATA SOURCES
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
     Endpoints       Network        Cloud
        ↓              ↓              ↓
        └──────────────┼──────────────┘
                       ↓
                  Log Collection
                       ↓
                    Analysis
                       ↓
                     Alert
                       ↓
                    DETECT
```

Detection provides the information needed for incident analysis and response.

---

# 11. Detection Does Not Equal Incident

Not every security alert is necessarily a confirmed incident.

The process may be:

```text
Security Event
      ↓
Detection
      ↓
Triage
      ↓
Analysis
      ↓
Potential Incident
      ↓
Incident Confirmation
```

This distinction is important because organizations may generate thousands of security events while only a smaller number represent significant incidents.

---

# 12. Respond

When a cybersecurity incident is confirmed, response activities begin.

```text
DETECT
   ↓
Potential Incident
   ↓
Analysis
   ↓
Incident Confirmation
   ↓
RESPOND
   ↓
Containment
   ↓
Mitigation
   ↓
Communication
```

Response should be coordinated according to the organization's incident-management processes.

---

# 13. Incident Response Lifecycle

A simplified response model is:

```text
Detection
   ↓
Triage
   ↓
Analysis
   ↓
Containment
   ↓
Eradication / Mitigation
   ↓
Communication
   ↓
Resolution
```

Different organizations may structure these activities differently.

The important principle is that response should reduce the impact of the cybersecurity incident.

---

# 14. Respond and Communication

Communication is an important part of cybersecurity response.

```text
                  INCIDENT
                     ↓
              RESPONSE TEAM
                     ↓
       ┌─────────────┼─────────────┐
       ↓             ↓             ↓
   Technical      Management    External
   Teams          Leadership     Parties
       ↓             ↓             ↓
       └─────────────┼─────────────┘
                     ↓
               Coordinated Response
```

Depending on the incident, communication may involve:

```text
Executives
Legal
Compliance
Privacy
Customers
Suppliers
Regulators
Law Enforcement
```

Communication requirements depend on the organization's circumstances and applicable obligations.

---

# 15. Recover

Recovery focuses on restoring affected capabilities.

```text
RESPOND
   ↓
Incident Contained
   ↓
RECOVER
   ↓
Restore Systems
   ↓
Validate Systems
   ↓
Resume Operations
   ↓
Monitor
```

Recovery should aim to restore reliable business operations rather than simply turn systems back on.

---

# 16. Recovery and Business Continuity

Cybersecurity recovery often connects with business continuity and disaster recovery.

```text
Cybersecurity Incident
        ↓
Business Disruption
        ↓
Recovery Strategy
        ↓
Technical Recovery
        ↓
Business Recovery
        ↓
Normal Operations
```

Recovery may involve:

```text
Backups
System Restoration
Alternate Infrastructure
Disaster Recovery
Business Continuity
Application Recovery
Data Restoration
```

---

# 17. Recovery Verification

Restoring a system does not automatically mean recovery is complete.

A verification process can be represented as:

```text
System Restoration
       ↓
Security Validation
       ↓
Data Integrity Check
       ↓
Application Testing
       ↓
Business Validation
       ↓
Service Restoration
```

This helps ensure that recovered systems are secure and functional before returning fully to production.

---

# 18. Recover and Lessons Learned

Recovery should generate information that can improve future cybersecurity capabilities.

```text
Incident
   ↓
Response
   ↓
Recovery
   ↓
Lessons Learned
   ↓
Identify New Risks
   ↓
Improve Controls
   ↓
Improve Detection
   ↓
Improve Response
```

This creates the feedback loop that makes the lifecycle continuous.

---

# 19. The Complete Identify-to-Recover Flow

The complete operational flow can be visualized as:

```text
                    IDENTIFY
                       ↓
              Understand Assets
                       ↓
                Assess Cyber Risk
                       ↓
                    PROTECT
                       ↓
              Implement Safeguards
                       ↓
                     DETECT
                       ↓
              Monitor Security Events
                       ↓
                Analyze / Triage
                       ↓
                    RESPOND
                       ↓
              Contain / Mitigate
                       ↓
                    RECOVER
                       ↓
              Restore Capabilities
                       ↓
               Validate Recovery
                       ↓
                 Lessons Learned
                       ↓
              Update Risk Knowledge
                       ↓
                    IDENTIFY
                       ↺
```

---

# 20. Example – Phishing Attack

Consider a phishing attack against an employee.

### Identify

```text
Threat:
Phishing

Vulnerability:
Insufficient user awareness

Risk:
Credential compromise
```

### Protect

```text
Security Awareness
+
Email Security
+
MFA
```

### Detect

```text
Suspicious Email
       ↓
Email Security Alert
       ↓
Security Monitoring
```

### Respond

```text
Incident Investigation
       ↓
Account Investigation
       ↓
Credential Reset
       ↓
Session Revocation
```

### Recover

```text
Restore Account
       ↓
Verify Security
       ↓
Monitor User
       ↓
Lessons Learned
```

The organization can then improve:

```text
Training
Email Filtering
MFA
Detection Rules
Incident Procedures
```

---

# 21. Example – Ransomware

A ransomware scenario demonstrates the complete lifecycle.

```text
IDENTIFY
   ↓
Ransomware Risk Identified
   ↓
PROTECT
   ↓
EDR + Backups + Segmentation + MFA
   ↓
DETECT
   ↓
Ransomware Activity Detected
   ↓
RESPOND
   ↓
Isolate Systems
   ↓
Contain Incident
   ↓
RECOVER
   ↓
Restore From Clean Backups
   ↓
Validate Systems
   ↓
Resume Operations
   ↓
Lessons Learned
   ↓
Improve Controls
```

The lessons learned can then influence future risk assessment and protection strategies.

---

# 22. Example – Cloud Account Compromise

```text
IDENTIFY
   ↓
Cloud Identity Risk
   ↓
PROTECT
   ↓
MFA + Least Privilege
   ↓
DETECT
   ↓
Suspicious Login Detected
   ↓
RESPOND
   ↓
Disable Account
   ↓
Revoke Sessions
   ↓
Investigate Activity
   ↓
RECOVER
   ↓
Restore Secure Access
   ↓
Validate Permissions
   ↓
Improve Controls
```

This demonstrates how the lifecycle applies to modern cloud environments.

---

# 23. Identify-to-Recover and GRC

From a GRC perspective, each stage can connect to governance and assurance activities.

```text
IDENTIFY
Risk Management
Asset Management
Risk Assessment

        ↓

PROTECT
Control Management
Policy
Compliance

        ↓

DETECT
Monitoring
Metrics
Control Monitoring

        ↓

RESPOND
Incident Management
Risk Escalation
Regulatory Assessment

        ↓

RECOVER
Business Continuity
Disaster Recovery
Lessons Learned
```

This makes the NIST CSF useful as a bridge between cybersecurity operations and GRC.

---

# 24. Identify-to-Recover and ISO 27001

The lifecycle can also be mapped conceptually to ISO 27001 activities.

```text
NIST CSF                    ISO 27001
────────────────────────────────────────
GOVERN        →       ISMS Governance

IDENTIFY      →       Risk Assessment

PROTECT       →       Risk Treatment / Controls

DETECT        →       Monitoring / Evaluation

RESPOND       →       Incident Management

RECOVER       →       Continuity / Recovery

IMPROVE       →       Continual Improvement
```

This is a conceptual alignment rather than a statement that the frameworks are identical.

An organization can use both frameworks together.

---

# 25. Identify-to-Recover and Control Lifecycle

Security controls can also be mapped into the lifecycle.

```text
IDENTIFY
   ↓
Determine Control Requirements
   ↓
PROTECT
   ↓
Implement Controls
   ↓
DETECT
   ↓
Monitor Control Performance
   ↓
RESPOND
   ↓
Address Control Failures
   ↓
RECOVER
   ↓
Restore Control Capability
   ↓
Improve
```

This creates a direct relationship between cybersecurity operations and GRC control management.

---

# 26. Identify-to-Recover Metrics

Organizations can develop metrics across the lifecycle.

```text
IDENTIFY
Asset Coverage
Risk Assessment Coverage

        ↓

PROTECT
MFA Coverage
Patch Compliance
Control Coverage

        ↓

DETECT
Mean Time to Detect
Alert Accuracy

        ↓

RESPOND
Mean Time to Respond
Mean Time to Contain

        ↓

RECOVER
Mean Time to Recover
Recovery Success Rate
```

Metrics should be selected according to business objectives and risk priorities.

---

# 27. Identify-to-Recover Dashboard

An executive dashboard could present the lifecycle as:

```text
          NIST CYBERSECURITY LIFECYCLE

 IDENTIFY      PROTECT       DETECT
   92%           87%           94%
     ↓             ↓             ↓

             RESPOND
                89%
                 ↓

              RECOVER
                91%
```

Management can then drill down into areas where performance is below expectations.

For example:

```text
Protect = 87%

Primary gaps:
MFA Coverage
Patch Compliance
Security Awareness
```

This turns the framework into a management reporting mechanism.

---

# 28. Risk-Based Prioritization

Not every capability needs to have identical maturity.

For example:

```text
Critical Banking System
        ↓
High Risk
        ↓
Strong Protect + Detect + Respond
```

While:

```text
Low-Criticality System
        ↓
Lower Risk
        ↓
Proportionate Controls
```

The NIST CSF should therefore be implemented in a way that reflects organizational risk.

---

# 29. Continuous Feedback

The most important characteristic of the lifecycle is feedback.

```text
                     IDENTIFY
                        ↓
                     PROTECT
                        ↓
                      DETECT
                        ↓
                     RESPOND
                        ↓
                      RECOVER
                        ↓
                 LESSONS LEARNED
                        ↓
                  RISK REASSESSMENT
                        ↓
                     IDENTIFY
                        ↺
```

A cybersecurity incident may reveal:

```text
New Threat
New Vulnerability
Control Weakness
Detection Gap
Response Gap
Recovery Weakness
```

Those findings should influence future cybersecurity decisions.

---

# 30. Executive Security Lifecycle

For senior management, the lifecycle can be reduced to five questions:

```text
IDENTIFY
Do we understand our cybersecurity risks?

        ↓

PROTECT
Are we reducing those risks?

        ↓

DETECT
Can we detect significant events?

        ↓

RESPOND
Can we contain and manage incidents?

        ↓

RECOVER
Can we restore business operations?
```

With **Govern** providing the overarching direction:

```text
                     GOVERN
                        ↓
       ┌────────────────┼────────────────┐
       ↓                ↓                ↓
   IDENTIFY          PROTECT           DETECT
       ↓                ↓                ↓
       └────────────────┼────────────────┘
                        ↓
                     RESPOND
                        ↓
                     RECOVER
                        ↓
                  IMPROVEMENT
                        ↺
```

---

# 31. Complete Security Lifecycle Model

The complete GRC-oriented model can be represented as:

```text
                         GOVERN
                            ↓
                    BUSINESS CONTEXT
                            ↓
                         IDENTIFY
                            ↓
                    ASSETS / RISKS
                            ↓
                         PROTECT
                            ↓
                  CONTROLS / SAFEGUARDS
                            ↓
                          DETECT
                            ↓
                 EVENTS / THREAT ACTIVITY
                            ↓
                         RESPOND
                            ↓
                CONTAINMENT / MITIGATION
                            ↓
                         RECOVER
                            ↓
              RESTORATION / BUSINESS RESILIENCE
                            ↓
                      LESSONS LEARNED
                            ↓
                    RISK REASSESSMENT
                            ↓
                         GOVERN
                            ↺
```

---

# 32. The GRC Perspective

For a GRC professional, the Identify-to-Recover lifecycle can be interpreted as a chain of **risk understanding → risk treatment → assurance → incident management → resilience**.

```text
Risk
 ↓
Control
 ↓
Monitoring
 ↓
Incident
 ↓
Response
 ↓
Recovery
 ↓
Lessons Learned
 ↓
Risk Reassessment
```

This creates an important connection between **preventive governance** and **operational cybersecurity**.

The ultimate objective is not simply to prevent every cybersecurity event. It is to ensure that the organization can:

> **Understand its cybersecurity risks, implement proportionate safeguards, detect significant events, respond effectively, recover critical capabilities, and continuously improve its cybersecurity risk-management posture.**

# 18.7 NIST Cybersecurity Framework Diagrams

### Part 3 – NIST CSF Organizational Profile

A **NIST CSF Organizational Profile** describes an organization's current or target cybersecurity posture in the context of its business objectives, stakeholders, requirements, and risk environment.

The Profile is useful because organizations do not all have the same cybersecurity requirements. A healthcare organization, telecommunications company, financial institution, government agency, and small technology company may have very different priorities.

A simplified model is:

```text
                    ORGANIZATION
                         ↓
                Business Objectives
                         ↓
                  Risk Environment
                         ↓
              NIST CSF Organizational
                     Profile
                         ↓
          ┌──────────────┼──────────────┐
          ↓              ↓              ↓
       Current         Target        Priorities
       State           State
          ↓              ↓
          └──────────────┼──────────────┘
                         ↓
                   Risk Decisions
```

---

# 1. What Is an Organizational Profile?

An Organizational Profile provides a way to describe an organization's cybersecurity outcomes based on its:

```text
Business Objectives
Risk Appetite
Threat Environment
Legal Requirements
Regulatory Requirements
Customer Expectations
Technology Environment
Supply Chain
Available Resources
```

The Profile helps answer:

> **What cybersecurity outcomes are important to this organization?**

Rather than applying every cybersecurity practice equally, the organization can prioritize outcomes based on its specific circumstances.

---

# 2. Organizational Profile Concept

A simplified representation is:

```text
                 ORGANIZATION
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
     Business        Risk          External
     Objectives     Appetite       Requirements
        ↓              ↓              ↓
        └──────────────┼──────────────┘
                       ↓
                ORGANIZATIONAL
                   PROFILE
                       ↓
              CSF OUTCOMES
```

The Profile therefore provides organizational context for using the NIST CSF.

---

# 3. Organizational Profile and CSF Core

The Profile can organize cybersecurity outcomes across the six Core Functions:

```text
                 ORGANIZATIONAL PROFILE
                           ↓
        ┌──────────────────┼──────────────────┐
        ↓                  ↓                  ↓
      GOVERN            IDENTIFY           PROTECT
        ↓                  ↓                  ↓
      DETECT             RESPOND           RECOVER
        └──────────────────┼──────────────────┘
                           ↓
                 Cybersecurity Outcomes
```

This allows the organization to view its cybersecurity posture across the complete CSF.

---

# 4. Business Context

The Organizational Profile should reflect the organization's business environment.

For example:

```text
Business Model
      ↓
Critical Services
      ↓
Critical Assets
      ↓
Business Dependencies
      ↓
Cybersecurity Requirements
```

Consider a telecommunications company:

```text
Critical Services
     ↓
Mobile Network
Enterprise Connectivity
Cloud Services
Customer Platforms
     ↓
Critical Assets
     ↓
Cybersecurity Requirements
```

The cybersecurity profile should reflect the importance of these services.

---

# 5. Organizational Profile Inputs

Several sources can contribute to the Profile.

```text
                     PROFILE INPUTS
                           ↓
       ┌────────────┬──────┼──────┬────────────┐
       ↓            ↓      ↓      ↓            ↓
    Business       Risk   Laws   Threats    Technology
    Strategy       Data   & Regs             Environment
       ↓            ↓      ↓      ↓            ↓
       └────────────┴──────┼──────┴────────────┘
                           ↓
                    ORGANIZATIONAL
                       PROFILE
```

Other inputs may include:

```text
Customer Requirements
Contractual Obligations
Industry Standards
Internal Policies
Audit Findings
Security Incidents
Third-Party Dependencies
Executive Priorities
```

---

# 6. Organizational Profile and Risk

Risk is a major input into the Profile.

```text
Business Context
      ↓
Threat Environment
      ↓
Vulnerabilities
      ↓
Potential Impact
      ↓
Cybersecurity Risk
      ↓
Profile Priorities
```

For example:

```text
High Risk:
Customer Identity Systems

        ↓

Profile Priority:
Strong Identity Protection

        ↓

Potential Outcomes:
MFA
Privileged Access Management
Identity Monitoring
Access Reviews
```

The Profile therefore reflects the organization's risk priorities.

---

# 7. Organizational Profile and Requirements

External requirements can also influence the Profile.

```text
External Requirements
        ↓
Regulatory Requirements
        ↓
Contractual Requirements
        ↓
Industry Expectations
        ↓
Cybersecurity Outcomes
        ↓
Organizational Profile
```

For example, an organization operating in a regulated environment may prioritize:

```text
Data Protection
Access Control
Incident Management
Auditability
Third-Party Risk
Business Resilience
```

---

# 8. Current Profile

A **Current Profile** describes the cybersecurity outcomes that the organization is currently achieving.

A simplified model is:

```text
              CURRENT PROFILE
                     ↓
        ┌────────────┼────────────┐
        ↓            ↓            ↓
      Govern       Identify     Protect
        ↓            ↓            ↓
      Detect       Respond      Recover
        ↓            ↓            ↓
        └────────────┼────────────┘
                     ↓
             Current Outcomes
```

The Current Profile represents the organization's present cybersecurity posture.

---

# 9. Current Profile Example

Consider an organization with the following posture:

```text
GOVERN
Defined cybersecurity policy

IDENTIFY
85% critical assets identified

PROTECT
90% MFA coverage

DETECT
Centralized SIEM monitoring

RESPOND
Formal incident response process

RECOVER
Documented recovery procedures
```

These outcomes together form part of the organization's current cybersecurity profile.

---

# 10. Target Profile

A **Target Profile** describes the cybersecurity outcomes the organization wants to achieve.

```text
             TARGET PROFILE
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
      Govern      Identify    Protect
        ↓           ↓           ↓
      Detect      Respond     Recover
        ↓           ↓           ↓
        └───────────┼───────────┘
                    ↓
             Desired Outcomes
```

The Target Profile should reflect:

```text
Business Objectives
Risk Priorities
Regulatory Requirements
Threat Environment
Strategic Direction
```

---

# 11. Current vs Target

The fundamental relationship is:

```text
CURRENT PROFILE
      ↓
Where are we today?
      ↓
        GAP
      ↓
Where do we need to improve?
      ↓
TARGET PROFILE
      ↓
Where do we want to be?
```

This provides the foundation for cybersecurity improvement planning.

---

# 12. Organizational Profile and Prioritization

Not every CSF outcome will have the same priority.

A simplified model is:

```text
                 CSF OUTCOMES
                      ↓
             Risk-Based Assessment
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
      High          Medium           Low
    Priority       Priority        Priority
       ↓              ↓              ↓
   Immediate       Planned        Monitor
```

For example:

```text
Critical Identity System
        ↓
High Priority

Legacy Application
        ↓
Medium Priority

Low-Impact Internal Tool
        ↓
Lower Priority
```

This allows resources to be directed toward the areas of greatest importance.

---

# 13. Profile and Business Priorities

Cybersecurity priorities should support business priorities.

```text
Business Objective
       ↓
Business Risk
       ↓
Cybersecurity Risk
       ↓
CSF Outcome
       ↓
Security Capability
       ↓
Business Protection
```

For example:

```text
Business Objective:
24/7 Customer Service

        ↓

Risk:
Service disruption

        ↓

CSF Priority:
Resilience and Recovery

        ↓

Security Capability:
Redundant Infrastructure
+
Backup
+
Disaster Recovery
```

---

# 14. Profile and Stakeholders

Different stakeholders may have different concerns.

```text
                     ORGANIZATION
                           ↓
             ┌─────────────┼─────────────┐
             ↓             ↓             ↓
          Executive       Risk          Security
          Management     Management      Team
             ↓             ↓             ↓
             └─────────────┼─────────────┘
                           ↓
                    CSF PROFILE
```

Additional stakeholders may include:

```text
Compliance
Internal Audit
Legal
Privacy
IT
Operations
Business Units
Customers
Suppliers
Regulators
```

The Profile can provide a common language across these groups.

---

# 15. Profile and Governance

Governance determines the direction and expectations reflected in the Profile.

```text
Business Strategy
       ↓
Risk Appetite
       ↓
Cybersecurity Strategy
       ↓
Governance
       ↓
Organizational Profile
       ↓
Cybersecurity Outcomes
```

This reinforces the importance of **Govern** in NIST CSF 2.0.

---

# 16. Profile and Risk Appetite

The organization's risk appetite can influence target outcomes.

```text
Risk Appetite
      ↓
Risk Tolerance
      ↓
Security Requirements
      ↓
Target Outcomes
      ↓
Target Profile
```

For example:

```text
Low Risk Appetite
       ↓
Higher Security Requirements
       ↓
Stronger Controls
       ↓
More Monitoring
       ↓
Higher Target Profile
```

The opposite may apply to lower-risk environments.

---

# 17. Profile and Regulatory Environment

The regulatory environment can influence the organization's desired cybersecurity posture.

```text
Regulatory Requirements
        ↓
Compliance Obligations
        ↓
Cybersecurity Outcomes
        ↓
Target Profile
```

A GRC team may therefore use the Profile to connect:

```text
Regulation
   ↓
Requirement
   ↓
Cybersecurity Outcome
   ↓
Control
   ↓
Evidence
```

This creates traceability between regulatory requirements and cybersecurity capabilities.

---

# 18. Profile and Third-Party Risk

Third parties can significantly affect an organization's cybersecurity profile.

```text
Organization
     ↓
Third-Party Dependencies
     ↓
Supplier Risk
     ↓
Cybersecurity Requirements
     ↓
Profile Outcomes
```

For example:

```text
Critical Cloud Provider
        ↓
High Dependency
        ↓
Availability Risk
        ↓
Recovery Requirement
        ↓
Target Outcome
```

This makes supply-chain considerations part of the broader cybersecurity risk picture.

---

# 19. Profile and Technology

Technology architecture can influence the organization's cybersecurity outcomes.

```text
Technology Environment
        ↓
Cloud
On-Premises
SaaS
IoT
AI
Mobile
OT
        ↓
Risk Environment
        ↓
Cybersecurity Requirements
        ↓
Organizational Profile
```

A cloud-heavy organization may have stronger requirements around:

```text
Identity
Cloud Configuration
Data Protection
API Security
Cloud Monitoring
Third-Party Risk
```

---

# 20. Profile and Cybersecurity Maturity

The Profile can also provide a way to describe cybersecurity maturity at the outcome level.

```text
Current Profile
      ↓
Capability Assessment
      ↓
Maturity Gaps
      ↓
Target Profile
      ↓
Improvement Roadmap
```

For example:

```text
Current:
Basic security monitoring

Target:
24/7 centralized monitoring
+
Automated detection
+
Threat intelligence
```

The difference becomes an improvement opportunity.

---

# 21. Profile and CSF Categories

The CSF is structured hierarchically.

A simplified representation is:

```text
CSF
 ↓
Functions
 ↓
Categories
 ↓
Subcategories / Outcomes
```

The Profile can therefore be developed at an appropriate level of detail.

For example:

```text
PROTECT
   ↓
Identity Management
   ↓
Authentication
   ↓
Desired Authentication Outcome
```

This allows organizations to move from high-level executive discussions toward specific cybersecurity outcomes.

---

# 22. Organizational Profile and GRC Mapping

A GRC platform can represent the Profile through structured relationships.

```text
Business Objective
       ↓
Risk
       ↓
CSF Function
       ↓
CSF Category
       ↓
Outcome
       ↓
Control
       ↓
Evidence
       ↓
Assessment
```

This creates an integrated view of cybersecurity governance and control management.

---

# 23. Profile and Control Frameworks

The Profile can also be used to organize requirements from multiple frameworks.

```text
                    ORGANIZATIONAL PROFILE
                              ↓
        ┌─────────────────────┼─────────────────────┐
        ↓                     ↓                     ↓
    NIST CSF              ISO 27001              COBIT
        ↓                     ↓                     ↓
        └─────────────────────┼─────────────────────┘
                              ↓
                    Common Security Outcomes
                              ↓
                           Controls
```

This helps avoid treating each framework as a completely separate program.

---

# 24. Example – Financial Organization

Consider a financial organization.

Its Profile may prioritize:

```text
GOVERN
Strong regulatory governance

IDENTIFY
Critical financial assets

PROTECT
Strong identity and data protection

DETECT
Real-time transaction monitoring

RESPOND
Rapid fraud and cyber incident response

RECOVER
High availability and resilient recovery
```

The Profile reflects the organization's business and risk environment.

---

# 25. Example – Telecommunications Organization

A telecommunications organization may have a different Profile.

```text
GOVERN
Cybersecurity and regulatory governance

IDENTIFY
Network and customer service assets

PROTECT
Network security and identity controls

DETECT
Network and threat monitoring

RESPOND
Security incident containment

RECOVER
Network and service restoration
```

The same NIST CSF can therefore be adapted to a completely different business context.

---

# 26. Example – Healthcare Organization

A healthcare organization may emphasize:

```text
GOVERN
Healthcare security governance

IDENTIFY
Clinical systems and patient information

PROTECT
Privacy and access controls

DETECT
Unauthorized access and malware

RESPOND
Patient-impacting cyber incidents

RECOVER
Clinical system restoration
```

Again, the framework remains consistent while the organizational priorities differ.

---

# 27. Profile Development Process

A practical process for developing an Organizational Profile can be represented as:

```text
Understand Business Context
          ↓
Identify Stakeholders
          ↓
Understand Risk Environment
          ↓
Identify Requirements
          ↓
Select Relevant CSF Outcomes
          ↓
Assess Current State
          ↓
Define Desired State
          ↓
Prioritize
          ↓
Document Profile
```

This produces a structured representation of the organization's cybersecurity priorities.

---

# 28. Profile Development Inputs

The process can be expanded:

```text
                    INPUTS
                       ↓
       ┌───────────────┼───────────────┐
       ↓               ↓               ↓
 Business            Risk          Regulatory
 Strategy           Register       Requirements
       ↓               ↓               ↓
       └───────────────┼───────────────┘
                       ↓
                Threat Landscape
                       ↓
                Technology Context
                       ↓
              Stakeholder Expectations
                       ↓
              ORGANIZATIONAL PROFILE
```

---

# 29. Current Profile Assessment

A Current Profile assessment can be represented as:

```text
CSF Outcome
     ↓
Current Capability
     ↓
Evidence
     ↓
Assessment
     ↓
Current State
```

Evidence may include:

```text
Policies
Procedures
Configurations
Logs
Reports
Audit Results
Risk Assessments
Control Testing
Incident Records
```

This connects the Profile with GRC assurance processes.

---

# 30. Target Profile Development

The Target Profile should represent desired cybersecurity outcomes.

```text
Business Requirements
        ↓
Risk Requirements
        ↓
Regulatory Requirements
        ↓
Strategic Objectives
        ↓
Target CSF Outcomes
        ↓
TARGET PROFILE
```

The Target Profile should be realistic and achievable within the organization's risk, resource, and strategic constraints.

---

# 31. Profile Comparison

The Current and Target Profiles can be compared.

```text
             CURRENT PROFILE
                    ↓
              Assessment
                    ↓
                   GAP
                    ↓
              Prioritization
                    ↓
              TARGET PROFILE
```

Example:

```text
Current:
MFA = 70%

Target:
MFA = 100%

Gap:
30 percentage points
```

The gap becomes an actionable improvement area.

---

# 32. Profile and Roadmap

Profile gaps can be converted into a roadmap.

```text
Profile Gap
     ↓
Risk Assessment
     ↓
Priority
     ↓
Initiative
     ↓
Implementation
     ↓
Validation
     ↓
Updated Profile
```

This connects the NIST CSF directly to cybersecurity transformation planning.

---

# 33. Profile and Metrics

Metrics can measure progress toward the Target Profile.

```text
Target Outcome
      ↓
Metric
      ↓
Baseline
      ↓
Target
      ↓
Actual
      ↓
Gap
      ↓
Improvement Action
```

For example:

```text
Target:
100% critical systems monitored

Current:
82%

Gap:
18%

Action:
Expand monitoring coverage
```

---

# 34. Profile and Executive Reporting

An executive dashboard can summarize Profile performance.

```text
             ORGANIZATIONAL PROFILE
                       ↓
      ┌────────────────┼────────────────┐
      ↓                ↓                ↓
   Current           Target             Gap
   State             State            Analysis
      ↓                ↓                ↓
      └────────────────┼────────────────┘
                       ↓
                 Executive View
```

Executives can then focus on:

```text
Highest Risks
Largest Gaps
Critical Dependencies
Regulatory Requirements
Investment Priorities
Cybersecurity Trends
```

---

# 35. Profile and Investment Decisions

Profile gaps can help support investment decisions.

```text
Profile Gap
     ↓
Risk Impact
     ↓
Business Impact
     ↓
Investment Requirement
     ↓
Management Decision
     ↓
Security Improvement
```

For example:

```text
Detection Gap
     ↓
High Risk
     ↓
Potential Major Incident
     ↓
SIEM Enhancement
     ↓
Investment Approval
```

This helps translate technical cybersecurity needs into business decisions.

---

# 36. Organizational Profile as a Communication Tool

One of the greatest benefits of the Profile is communication.

Different stakeholders can use the same model:

```text
Executive
   ↓
Risk Manager
   ↓
GRC
   ↓
Cybersecurity
   ↓
IT Operations
   ↓
Internal Audit
```

The Profile creates a common reference point for discussing cybersecurity outcomes.

---

# 37. Profile and Assurance

Internal audit and assurance functions can also use the Profile.

```text
Target Profile
      ↓
Expected Outcomes
      ↓
Control Environment
      ↓
Testing
      ↓
Evidence
      ↓
Assurance Result
      ↓
Profile Status
```

This allows assurance activities to evaluate whether desired cybersecurity outcomes are being achieved.

---

# 38. Profile and Continuous Improvement

The Organizational Profile should evolve as the organization changes.

```text
Business Change
      ↓
Risk Change
      ↓
Technology Change
      ↓
Regulatory Change
      ↓
Profile Review
      ↓
Updated Outcomes
      ↓
Updated Target
      ↓
Improvement
```

Examples include:

```text
Cloud Migration
AI Adoption
Acquisition
New Regulation
New Product
New Threat
Major Incident
Organizational Restructuring
```

---

# 39. Profile Lifecycle

The complete Profile lifecycle can be represented as:

```text
Business Context
       ↓
Profile Development
       ↓
Current State
       ↓
Target State
       ↓
Gap Analysis
       ↓
Prioritization
       ↓
Implementation
       ↓
Measurement
       ↓
Review
       ↓
Profile Update
       ↺
```

This makes the Profile a living management artifact rather than a static document.

---

# 40. Complete NIST CSF Organizational Profile Model

The integrated model can be visualized as:

```text
                     BUSINESS
                     CONTEXT
                        ↓
              ┌─────────┼─────────┐
              ↓         ↓         ↓
           Strategy    Risk    Requirements
              ↓         ↓         ↓
              └─────────┼─────────┘
                        ↓
                ORGANIZATIONAL
                    PROFILE
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
      GOVERN         IDENTIFY         PROTECT
        ↓               ↓               ↓
      DETECT          RESPOND         RECOVER
        └───────────────┼───────────────┘
                        ↓
                CURRENT PROFILE
                        ↓
                  Gap Analysis
                        ↓
                 Target Profile
                        ↓
                Prioritized Actions
                        ↓
                 Implementation
                        ↓
                  Measurement
                        ↓
                    Review
                        ↓
               Profile Improvement
                        ↺
```

---

# 41. GRC-Oriented Profile Model

For GRC practitioners, the model can be extended into a complete governance chain:

```text
Business Objective
       ↓
Business Risk
       ↓
Cybersecurity Risk
       ↓
NIST CSF Outcome
       ↓
Organizational Profile
       ↓
Control Requirement
       ↓
Control
       ↓
Evidence
       ↓
Assessment
       ↓
Metric
       ↓
Risk Decision
       ↓
Improvement
```

This demonstrates how the NIST CSF can become part of an enterprise GRC operating model.

---

# 42. Key Principles

An effective Organizational Profile should be:

```text
Business-Aligned
Risk-Based
Outcome-Focused
Evidence-Supported
Prioritized
Measurable
Reviewable
Adaptable
```

It should not simply become a checklist of cybersecurity controls.

The focus should remain on **the cybersecurity outcomes the organization needs to achieve**.

---

# 43. Final Concept

The NIST CSF Organizational Profile can ultimately be summarized as:

```text
                  WHAT MATTERS
                       ↓
                Business Context
                       ↓
                  WHAT CAN HARM US
                       ↓
                    Risk
                       ↓
                WHAT DO WE NEED
                       ↓
                CSF Outcomes
                       ↓
                 WHERE ARE WE
                       ↓
                Current Profile
                       ↓
               WHERE DO WE WANT
                    TO BE
                       ↓
                Target Profile
                       ↓
                  WHAT IS THE GAP
                       ↓
                 Gap Analysis
                       ↓
                 WHAT SHOULD WE DO
                       ↓
                Prioritized Actions
                       ↓
                HOW ARE WE DOING
                       ↓
                   Metrics
                       ↓
                CONTINUAL REVIEW
                       ↺
```

The key GRC principle is:

> **The NIST CSF Organizational Profile translates an organization's unique business context, risk environment, requirements, and strategic priorities into a structured view of the cybersecurity outcomes it currently achieves and the outcomes it wants to achieve.**

This makes the Profile particularly valuable for **GRC, risk management, cybersecurity strategy, executive reporting, audit, compliance, and security transformation planning**.

# 18.7 NIST Cybersecurity Framework Diagrams

### Part 4 – Current Profile-to-Target Profile Gap Model

The **Current Profile-to-Target Profile Gap Model** provides a structured way to identify the difference between an organization's existing cybersecurity posture and its desired future state.

In practical GRC terms, it answers four fundamental questions:

```text
Where are we now?
        ↓
Where do we need to be?
        ↓
What is the gap?
        ↓
What should we do about it?
```

A simplified model is:

```text
CURRENT PROFILE
      ↓
Current Outcomes
      ↓
Gap Analysis
      ↓
Risk-Based Prioritization
      ↓
TARGET PROFILE
      ↓
Improvement Roadmap
      ↓
Implementation
      ↓
Measurement
      ↺
```

---

# 1. What Is a Profile Gap?

A **profile gap** exists when the cybersecurity outcomes currently achieved by an organization do not meet the desired outcomes defined in its Target Profile.

For example:

```text
Current:
80% of critical systems monitored

Target:
100% of critical systems monitored

Gap:
20%
```

The gap is not automatically a problem requiring immediate action.

It needs to be evaluated against:

```text
Risk
Business Impact
Regulatory Requirements
Threat Environment
Cost
Resource Availability
Strategic Priorities
```

---

# 2. Current Profile

The Current Profile describes the organization's present cybersecurity outcomes.

```text
                 CURRENT PROFILE
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
      GOVERN          IDENTIFY         PROTECT
        ↓               ↓               ↓
      DETECT          RESPOND         RECOVER
        ↓               ↓               ↓
        └───────────────┼───────────────┘
                        ↓
              Current Cybersecurity
                     Posture
```

The Current Profile should be supported by objective information.

Examples include:

```text
Risk Assessments
Control Assessments
Audit Findings
Security Metrics
Incident Records
Technical Assessments
Policies
Procedures
Evidence
```

---

# 3. Target Profile

The Target Profile describes the cybersecurity outcomes the organization wants to achieve.

```text
                  TARGET PROFILE
                         ↓
        ┌────────────────┼────────────────┐
        ↓                ↓                ↓
      GOVERN           IDENTIFY         PROTECT
        ↓                ↓                ↓
      DETECT           RESPOND          RECOVER
        ↓                ↓                ↓
        └────────────────┼────────────────┘
                         ↓
                Desired Cybersecurity
                       Posture
```

The Target Profile should reflect organizational priorities rather than simply attempting to maximize every possible security capability.

---

# 4. Current-to-Target Relationship

The fundamental relationship is:

```text
CURRENT PROFILE
      ↓
   Where we are
      ↓
   GAP ANALYSIS
      ↓
   Where we need improvement
      ↓
TARGET PROFILE
      ↓
   Where we want to be
```

A more complete model is:

```text
Current State
     ↓
Assessment
     ↓
Gap
     ↓
Risk Evaluation
     ↓
Priority
     ↓
Action
     ↓
Target State
```

---

# 5. Six Core Functions Gap Model

The comparison can be performed across all six CSF Functions.

```text
                    PROFILE GAP ANALYSIS
                            ↓
        ┌───────────────┬──┴──┬───────────────┐
        ↓               ↓     ↓               ↓
      GOVERN         IDENTIFY PROTECT       DETECT
        ↓               ↓     ↓               ↓
      RESPOND         RECOVER
        ↓               ↓
        └───────────────┼─────────────────────┘
                        ↓
                Prioritized Gaps
```

For each Function, the organization can compare:

```text
Current Outcome
Target Outcome
Gap
Risk
Priority
Action
```

---

# 6. Govern Gap

A governance gap might look like:

```text
CURRENT
Cybersecurity policies exist
        ↓
GAP
Limited executive oversight
        ↓
TARGET
Formal cybersecurity governance
and management oversight
```

Potential improvement activities may include:

```text
Governance Committee
Risk Reporting
Policy Governance
Risk Appetite
Management Oversight
Accountability
```

---

# 7. Identify Gap

An Identify gap might involve incomplete asset visibility.

```text
CURRENT
85% of critical assets identified
        ↓
GAP
15% unknown or insufficiently classified
        ↓
TARGET
100% of critical assets identified
```

Potential actions:

```text
Asset Discovery
Asset Inventory
Classification
Business Ownership
Dependency Mapping
Risk Assessment
```

---

# 8. Protect Gap

A Protect gap could involve identity security.

```text
CURRENT
MFA deployed to 80% of users
        ↓
GAP
20% remain outside the target scope
        ↓
TARGET
MFA coverage aligned with organizational requirements
```

Potential actions:

```text
MFA Expansion
Privileged Access Management
Access Reviews
Identity Governance
Authentication Improvements
```

The exact target should be based on risk and organizational requirements.

---

# 9. Detect Gap

A Detect gap could involve monitoring coverage.

```text
CURRENT
Critical systems partially monitored
        ↓
GAP
Monitoring coverage does not meet target
        ↓
TARGET
Required critical systems continuously monitored
```

Potential actions:

```text
SIEM Expansion
EDR Deployment
Cloud Monitoring
Log Integration
Detection Engineering
Threat Intelligence
```

---

# 10. Respond Gap

A Respond gap could involve incident-management capability.

```text
CURRENT
Incident response plan exists
        ↓
GAP
Limited testing and inconsistent escalation
        ↓
TARGET
Tested and operational incident response capability
```

Potential actions:

```text
Incident Playbooks
Escalation Procedures
Tabletop Exercises
Incident Communications
Response Automation
Incident Metrics
```

---

# 11. Recover Gap

A Recover gap could involve restoration capability.

```text
CURRENT
Backups exist
        ↓
GAP
Recovery testing is limited
        ↓
TARGET
Recovery capabilities regularly tested
```

Potential actions:

```text
Recovery Testing
Backup Validation
Disaster Recovery Exercises
Business Continuity Testing
System Restoration Procedures
Recovery Metrics
```

---

# 12. Gap Analysis Process

A practical gap analysis can follow:

```text
1. Define Business Context
          ↓
2. Establish Current Profile
          ↓
3. Define Target Profile
          ↓
4. Compare Current vs Target
          ↓
5. Identify Gaps
          ↓
6. Assess Risk
          ↓
7. Prioritize
          ↓
8. Define Actions
          ↓
9. Implement
          ↓
10. Measure Progress
```

This makes the Profile useful as a management process rather than simply a documentation exercise.

---

# 13. Evidence-Based Current Profile

The Current Profile should not be based solely on assumptions.

A strong assessment uses evidence.

```text
                 CURRENT PROFILE
                        ↓
                     Evidence
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
      Audit           Testing         Metrics
        ↓               ↓               ↓
        └───────────────┼───────────────┘
                        ↓
                Current Outcome
```

Examples of evidence:

```text
Configuration Reports
Audit Reports
Risk Assessments
Security Dashboards
Incident Records
Control Test Results
Penetration Tests
Vulnerability Assessments
Policy Reviews
```

---

# 14. Defining the Target Profile

The Target Profile should be based on organizational needs.

```text
Business Strategy
       ↓
Risk Appetite
       ↓
Threat Environment
       ↓
Regulatory Requirements
       ↓
Customer Requirements
       ↓
Technology Strategy
       ↓
TARGET PROFILE
```

This prevents the target from becoming an arbitrary list of security improvements.

---

# 15. Target Profile and Risk Appetite

Risk appetite can influence how ambitious the Target Profile should be.

```text
Higher Risk Sensitivity
        ↓
Stronger Security Requirements
        ↓
Higher Target Outcomes
```

For example:

```text
Critical Payment System
        ↓
Low Tolerance for Security Failure
        ↓
High Security Target
```

Whereas:

```text
Low-Criticality Internal Application
        ↓
Lower Business Impact
        ↓
Proportionate Security Target
```

The target should therefore remain risk-based.

---

# 16. Gap Does Not Always Mean Failure

An important GRC principle is:

> **A gap is not automatically a deficiency.**

For example:

```text
Current:
Monitoring = 90%

Target:
Monitoring = 100%

Gap:
10%
```

The organization might determine that the remaining 10% represents low-risk systems where additional investment would not be justified.

Therefore:

```text
Gap
 ↓
Risk Evaluation
 ↓
Business Impact
 ↓
Cost / Benefit
 ↓
Management Decision
```

A formally accepted risk may be an appropriate outcome.

---

# 17. Risk-Based Gap Prioritization

Not all gaps have equal importance.

A simple prioritization model is:

```text
                 IDENTIFIED GAPS
                        ↓
        ┌───────────────┼───────────────┐
        ↓               ↓               ↓
      High            Medium            Low
       ↓                ↓                ↓
   Immediate         Planned          Monitor
   Action            Action
```

Prioritization can consider:

```text
Risk Severity
Business Criticality
Regulatory Exposure
Threat Likelihood
Potential Impact
Control Effectiveness
Implementation Effort
Cost
Dependencies
```

---

# 18. Gap Scoring

Organizations may assign a score to each gap.

For example:

```text
Gap Score =
Risk Impact × Likelihood × Business Criticality
```

A simplified scoring table might be:

| Gap                             | Risk   | Business Impact | Priority  |
| ------------------------------- | ------ | --------------- | --------- |
| Critical asset visibility       | High   | High            | Immediate |
| MFA coverage                    | High   | High            | Immediate |
| Security awareness              | Medium | Medium          | Planned   |
| Low-risk application monitoring | Low    | Low             | Monitor   |

The exact scoring methodology should be defined by the organization's risk-management process.

---

# 19. Gap Register

A GRC platform can maintain a Profile Gap Register.

```text
Profile Gap
     ↓
Risk
     ↓
Owner
     ↓
Priority
     ↓
Action
     ↓
Due Date
     ↓
Status
     ↓
Evidence
```

Example:

```text
Gap:
Incomplete cloud asset inventory

Risk:
Unknown cloud exposure

Owner:
Cloud Security

Priority:
High

Action:
Implement automated discovery

Status:
In Progress
```

This turns Profile analysis into an actionable GRC process.

---

# 20. Gap-to-Action Traceability

Every significant gap should ideally have a traceable action.

```text
CURRENT OUTCOME
      ↓
IDENTIFIED GAP
      ↓
RISK
      ↓
REMEDIATION ACTION
      ↓
CONTROL / CAPABILITY
      ↓
EVIDENCE
      ↓
VALIDATION
      ↓
UPDATED PROFILE
```

This provides strong auditability.

---

# 21. Gap-to-Control Mapping

A GRC implementation may map gaps to controls.

```text
CSF Outcome
     ↓
Current Gap
     ↓
Control Requirement
     ↓
Control
     ↓
Implementation
     ↓
Evidence
     ↓
Assessment
```

For example:

```text
Target:
Strong privileged access protection

        ↓

Gap:
Privileged accounts lack MFA

        ↓

Control:
Privileged Access MFA

        ↓

Evidence:
Authentication Configuration

        ↓

Assessment:
Effective
```

---

# 22. Gap-to-Risk Mapping

The same gap should also be connected to risk.

```text
Gap
 ↓
Threat
 ↓
Vulnerability
 ↓
Potential Impact
 ↓
Risk
 ↓
Treatment Decision
```

Example:

```text
Gap:
No centralized monitoring

        ↓

Threat:
Undetected attacker activity

        ↓

Vulnerability:
Limited visibility

        ↓

Impact:
Delayed incident response

        ↓

Risk:
High
```

This prevents organizations from treating all gaps as equally important.

---

# 23. Gap-to-Regulation Mapping

Gaps may also be associated with regulatory obligations.

```text
Regulatory Requirement
        ↓
Expected Security Outcome
        ↓
Current Outcome
        ↓
Gap
        ↓
Compliance Risk
        ↓
Remediation
```

This is particularly valuable for GRC teams managing multiple regulatory requirements.

---

# 24. Gap-to-Evidence Mapping

Evidence provides support for the assessment.

```text
Target Outcome
       ↓
Expected Condition
       ↓
Evidence Requirement
       ↓
Evidence Collection
       ↓
Assessment
       ↓
Gap Determination
```

For example:

```text
Target:
Critical systems continuously monitored

Evidence:
SIEM Coverage Report

Assessment:
92% coverage

Gap:
8%
```

---

# 25. Gap-to-Metric Mapping

Metrics can track whether the gap is closing.

```text
Current
   ↓
Baseline Metric
   ↓
Target Metric
   ↓
Gap
   ↓
Improvement
   ↓
New Measurement
```

Example:

```text
MFA Coverage

Baseline:
72%

Target:
100%

Current:
88%

Remaining Gap:
12%
```

This provides a measurable view of progress.

---

# 26. Gap Closure Lifecycle

A gap can be managed through a lifecycle:

```text
Gap Identified
      ↓
Validated
      ↓
Risk Assessed
      ↓
Prioritized
      ↓
Action Assigned
      ↓
Remediation
      ↓
Evidence Collected
      ↓
Validation
      ↓
Gap Closed
```

If the gap cannot or should not be remediated:

```text
Gap
 ↓
Risk Assessment
 ↓
Risk Acceptance
 ↓
Management Approval
 ↓
Monitoring
```

This is an important GRC distinction.

---

# 27. Profile Gap and Risk Acceptance

Some gaps may be formally accepted.

```text
Gap Identified
      ↓
Risk Assessment
      ↓
Treatment Options
      ↓
┌─────┼─────────┬──────────┐
↓     ↓         ↓          ↓
Treat Transfer Avoid    Accept
```

If accepted:

```text
Risk Acceptance
      ↓
Appropriate Approval
      ↓
Document Rationale
      ↓
Define Review Date
      ↓
Monitor Risk
```

This ensures that unresolved gaps are not simply forgotten.

---

# 28. Gap Remediation Roadmap

The prioritized gaps can become a cybersecurity roadmap.

```text
PROFILE GAP
     ↓
PRIORITY
     ↓
INITIATIVE
     ↓
PROJECT
     ↓
IMPLEMENTATION
     ↓
VALIDATION
     ↓
PROFILE IMPROVEMENT
```

Example:

```text
Gap:
Limited cloud monitoring

        ↓

Priority:
High

        ↓

Initiative:
Cloud Security Monitoring

        ↓

Project:
SIEM Integration

        ↓

Implementation

        ↓

Validation

        ↓

Target Outcome Achieved
```

---

# 29. Short-Term and Long-Term Gaps

Not every gap can be closed immediately.

```text
              PROFILE GAPS
                    ↓
       ┌────────────┼────────────┐
       ↓            ↓            ↓
    0–3 Months   3–12 Months   12+ Months
       ↓            ↓            ↓
   Quick Wins     Projects     Strategic
```

This allows management to balance immediate risk reduction with long-term transformation.

---

# 30. Gap Dependencies

Some improvements depend on others.

```text
Asset Inventory
      ↓
Asset Classification
      ↓
Risk Assessment
      ↓
Control Prioritization
      ↓
Control Implementation
      ↓
Monitoring
```

For example, an organization may need accurate asset information before it can determine complete security-monitoring coverage.

Therefore, roadmap sequencing matters.

---

# 31. Current-to-Target Heat Map

A heat map can provide an executive representation.

```text
                    TARGET
              Low   Medium   High
CURRENT
Low           🟢      🟡       🟠

Medium        🟡      🟠       🔴

High          🟠      🔴       🔴
```

A more GRC-oriented version can compare current capability against desired capability:

```text
Function       Current       Target       Gap
------------------------------------------------
Govern          Medium        High        Medium
Identify        Medium        High        High
Protect         High          High        Low
Detect          Medium        High        High
Respond         Medium        High        Medium
Recover         Low           High        High
```

This provides a quick executive view of where attention is required.

---

# 32. CSF Function-Level Gap Dashboard

A dashboard could show:

```text
NIST CSF PROFILE GAP

GOVERN      ████████░░  80%
IDENTIFY    ███████░░░  70%
PROTECT     █████████░  90%
DETECT      ██████░░░░  60%
RESPOND     ███████░░░  70%
RECOVER     █████░░░░░  50%
```

The percentages are illustrative only.

A mature implementation should define exactly how capability or outcome achievement is measured.

---

# 33. Gap Analysis and Executive Decisions

The Profile Gap Model helps management answer:

```text
What are our biggest cybersecurity gaps?
             ↓
Which gaps create the greatest risk?
             ↓
Which gaps require investment?
             ↓
Which gaps can be accepted?
             ↓
What should we prioritize?
             ↓
Are we improving?
```

This turns cybersecurity assessment into a decision-support mechanism.

---

# 34. Profile Gap and Investment Prioritization

A practical decision model can be:

```text
Gap
 ↓
Risk
 ↓
Business Impact
 ↓
Regulatory Exposure
 ↓
Remediation Cost
 ↓
Implementation Complexity
 ↓
Priority
```

For example:

```text
High Risk
+
High Business Impact
+
Regulatory Exposure
+
Reasonable Remediation Cost
        ↓
HIGH PRIORITY
```

This supports rational allocation of cybersecurity resources.

---

# 35. Profile Gap and Program Management

A cybersecurity program can use the Profile Gap Model to track initiatives.

```text
Profile Gap
     ↓
Program Initiative
     ↓
Project
     ↓
Milestones
     ↓
Deliverables
     ↓
Evidence
     ↓
Outcome Validation
```

This creates traceability between strategic objectives and operational implementation.

---

# 36. Profile Gap and Internal Audit

Internal audit can use the model to evaluate whether identified gaps are being appropriately managed.

```text
Target Outcome
      ↓
Current Condition
      ↓
Gap
      ↓
Risk
      ↓
Management Action
      ↓
Evidence
      ↓
Audit Validation
```

This helps distinguish between:

```text
Known and Managed Gap
```

and:

```text
Unknown or Unmanaged Gap
```

The latter presents a significantly greater governance concern.

---

# 37. Profile Gap and Continuous Improvement

The gap model creates a continuous improvement cycle.

```text
       CURRENT PROFILE
              ↓
          GAP ANALYSIS
              ↓
        IMPROVEMENT PLAN
              ↓
         IMPLEMENTATION
              ↓
           MEASUREMENT
              ↓
        UPDATED PROFILE
              ↓
        NEW GAP ANALYSIS
              ↺
```

The organization's cybersecurity posture should therefore evolve as risks and business requirements change.

---

# 38. Major Events That Trigger Reassessment

The Profile should be reassessed when significant changes occur.

Examples include:

```text
Major Cybersecurity Incident
New Regulation
New Threat
Cloud Migration
AI Adoption
Merger or Acquisition
Major Technology Change
New Business Service
Critical Supplier Change
Significant Audit Finding
```

A simplified model is:

```text
Business / Risk Change
        ↓
Profile Review
        ↓
Current State Update
        ↓
Target State Review
        ↓
Gap Reassessment
        ↓
Updated Roadmap
```

---

# 39. Example – ISO 27001 Alignment

An organization implementing ISO 27001 may use the Profile Gap Model.

```text
Current Profile
       ↓
ISO 27001 ISMS Assessment
       ↓
Control / Risk Gaps
       ↓
Risk Treatment
       ↓
Target Profile
       ↓
Implementation
       ↓
Evidence
       ↓
Validation
```

The CSF Profile does not replace the ISO 27001 ISMS, but it can provide a useful cybersecurity posture and communication model alongside it.

---

# 40. Example – NIS2 Environment

In an environment subject to NIS2 requirements, the organization may consider areas such as:

```text
Risk Management
Incident Handling
Business Continuity
Supply Chain Security
Access Control
Cryptography
Vulnerability Management
Training
```

The conceptual process is:

```text
Regulatory Requirement
        ↓
Expected Cybersecurity Outcome
        ↓
Current Profile
        ↓
Gap
        ↓
Risk
        ↓
Remediation
        ↓
Evidence
        ↓
Target Profile
```

This demonstrates how regulatory obligations can influence the Target Profile.

---

# 41. Example – Third-Party Security

Suppose the organization has inadequate supplier security monitoring.

```text
CURRENT PROFILE
Limited supplier monitoring
        ↓
GAP
Insufficient visibility into critical suppliers
        ↓
RISK
Third-party compromise
        ↓
TARGET PROFILE
Risk-based supplier monitoring
        ↓
ACTION
Third-party monitoring program
```

The Profile therefore provides a strategic representation of the desired capability.

---

# 42. Example – AI Governance

For an organization adopting AI:

```text
Business Objective
       ↓
AI Adoption
       ↓
New Cybersecurity / AI Risks
       ↓
Current Profile
       ↓
Gap Analysis
       ↓
Target Outcomes
       ↓
AI Security and Governance Controls
```

Potential areas include:

```text
AI Asset Inventory
Data Protection
Access Control
Third-Party AI Risk
Model Security
Monitoring
Incident Response
```

The Profile can therefore evolve with emerging technologies.

---

# 43. Complete Current-to-Target Model

The integrated model can be represented as:

```text
                       BUSINESS CONTEXT
                              ↓
                       RISK ENVIRONMENT
                              ↓
                    ┌─────────┴─────────┐
                    ↓                   ↓
             CURRENT PROFILE       TARGET PROFILE
                    ↓                   ↑
                    └─────────┬─────────┘
                              ↓
                         GAP ANALYSIS
                              ↓
                        RISK ASSESSMENT
                              ↓
                       PRIORITIZATION
                              ↓
                     REMEDIATION PLAN
                              ↓
                         IMPLEMENTATION
                              ↓
                          VALIDATION
                              ↓
                          MEASUREMENT
                              ↓
                    UPDATED CURRENT PROFILE
                              ↓
                         REASSESSMENT
                              ↺
```

---

# 44. End-to-End GRC Traceability

For a mature GRC environment, the Profile Gap Model can connect strategy to evidence:

```text
Business Objective
        ↓
Risk
        ↓
NIST CSF Outcome
        ↓
Target Profile
        ↓
Current Profile
        ↓
Gap
        ↓
Control Requirement
        ↓
Control
        ↓
Evidence
        ↓
Assessment
        ↓
Remediation
        ↓
Validation
        ↓
Updated Profile
```

This is one of the most valuable applications of the Organizational Profile for GRC professionals.

---

# 45. Executive View

The entire concept can be reduced to:

```text
             WHERE ARE WE?
                   ↓
            CURRENT PROFILE
                   ↓
              GAP ANALYSIS
                   ↓
             WHAT MATTERS?
                   ↓
            RISK PRIORITY
                   ↓
            WHERE DO WE WANT
                 TO BE?
                   ↓
             TARGET PROFILE
                   ↓
             WHAT SHOULD WE
                  DO?
                   ↓
           ACTION ROADMAP
                   ↓
            ARE WE IMPROVING?
                   ↓
               METRICS
                   ↓
          UPDATED PROFILE
                   ↺
```

This makes the model easy to communicate to executives, risk committees, auditors, and cybersecurity leadership.

---

# 46. The GRC Perspective

From a GRC perspective, the Current Profile-to-Target Profile model provides a structured bridge between **assessment and action**.

It connects:

```text
Strategy
   ↓
Risk
   ↓
Cybersecurity Outcomes
   ↓
Current State
   ↓
Gap
   ↓
Treatment
   ↓
Controls
   ↓
Evidence
   ↓
Assurance
   ↓
Improvement
```

The most important principle is:

> **A cybersecurity profile should not merely describe where an organization is. It should help management understand where the organization needs to be, why the difference matters, and what actions are necessary to close the most important gaps.**

A mature GRC implementation therefore treats the Profile as a **living management instrument** that supports risk-based prioritization, investment decisions, control improvement, compliance, assurance, and continual cybersecurity improvement.



