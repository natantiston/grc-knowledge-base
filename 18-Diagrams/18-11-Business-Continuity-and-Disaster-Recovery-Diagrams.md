# 18.11 Business Continuity and Disaster Recovery Diagrams

## Part 1 – Business Continuity Management Lifecycle

The **Business Continuity Management (BCM) Lifecycle** is the structured process an organization uses to prepare for, respond to, and recover from disruptive events while maintaining or restoring critical business activities.

From a GRC perspective, BCM connects **business risk, operational resilience, cybersecurity, crisis management, disaster recovery, regulatory requirements, and executive governance**.

A simplified BCM lifecycle is:

```text
Governance & Planning
        ↓
Business Impact Analysis
        ↓
Risk Assessment
        ↓
Business Continuity Strategy
        ↓
Plan Development
        ↓
Implementation
        ↓
Training & Awareness
        ↓
Testing & Exercises
        ↓
Incident / Disruption
        ↓
Response & Continuity
        ↓
Recovery
        ↓
Review & Improvement
        ↺
```

---

# 1. What Is Business Continuity Management?

**Business Continuity Management** is the management discipline used to ensure that an organization can continue delivering important products and services at an acceptable level following a disruptive event.

Disruptions may result from:

```text
Cyberattack
Natural Disaster
Power Outage
Pandemic
Fire
Flood
Equipment Failure
Cloud Outage
Telecommunications Failure
Supplier Failure
Human Error
Civil Disruption
```

BCM therefore considers disruption broadly rather than focusing only on cybersecurity.

---

# 2. Why BCM Matters to GRC

BCM is an important GRC discipline because disruption creates organizational risk.

A simplified relationship is:

```text
Threat
  ↓
Disruption
  ↓
Business Impact
  ↓
Risk
  ↓
Continuity Strategy
  ↓
Recovery
```

GRC provides governance over:

```text
Risk
Compliance
Policies
Responsibilities
Controls
Testing
Evidence
Management Decisions
```

A mature BCM program ensures that continuity decisions are based on business priorities and organizational risk rather than being driven solely by technical considerations.

---

# 3. BCM Lifecycle

A mature BCM lifecycle can be represented as:

```text
1. Governance
      ↓
2. Business Impact Analysis
      ↓
3. Risk Assessment
      ↓
4. Continuity Strategy
      ↓
5. Plan Development
      ↓
6. Implementation
      ↓
7. Training & Awareness
      ↓
8. Testing & Exercises
      ↓
9. Response
      ↓
10. Recovery
      ↓
11. Review
      ↓
12. Improvement
      ↺
```

The lifecycle is continuous rather than a one-time project.

Changes in business operations, technology, threats, suppliers, regulations, and organizational structure can require the BCM program to be reassessed.

---

# 4. Business Continuity vs. Disaster Recovery

Business continuity and disaster recovery are closely related but have different primary focuses.

### Business Continuity

Business continuity focuses on maintaining or restoring **critical business activities and services**.

```text
Business Service
      ↓
Disruption
      ↓
Continuity Strategy
      ↓
Minimum Acceptable Service
      ↓
Business Recovery
```

### Disaster Recovery

Disaster recovery focuses primarily on restoring **technology, systems, applications, and infrastructure**.

```text
IT System
   ↓
Failure
   ↓
Recovery Environment
   ↓
System Restoration
```

The relationship can be represented as:

```text
Business Requirements
        ↓
Business Continuity
        ↓
Technology Requirements
        ↓
Disaster Recovery
```

Disaster recovery should therefore support business continuity requirements.

---

# 5. BCM Governance

The lifecycle begins with governance.

Governance establishes:

```text
Policy
Scope
Objectives
Roles
Responsibilities
Authority
Risk Appetite
Reporting
Accountability
```

A typical governance structure may look like:

```text
Board / Executive Management
            ↓
      BCM Governance
            ↓
   Business Continuity Manager
            ↓
 ┌──────────┼──────────┐
 ↓          ↓          ↓
Business   IT/DR      GRC/Risk
Units      Teams      Teams
```

Supporting functions may include cybersecurity, facilities, HR, communications, legal, procurement, and third-party risk management.

---

# 6. BCM Policy

The organization should establish a formal BCM policy.

It may define:

```text
Purpose
Scope
Objectives
Roles
Responsibilities
Business Continuity Requirements
Testing Requirements
Reporting
Exceptions
Review Frequency
```

The policy establishes management's expectations for business continuity and provides the foundation for the broader BCM program.

---

# 7. BCM Scope

The organization must determine what is included within the BCM program.

Scope may include:

```text
Business Units
Critical Services
Applications
Facilities
Employees
Suppliers
Cloud Services
Data
Technology Infrastructure
Geographic Locations
```

A simplified model is:

```text
Enterprise
   ↓
Business Services
   ↓
Critical Services
   ↓
Supporting Processes
   ↓
People / Technology / Data / Suppliers
```

Clearly defining scope helps ensure that important dependencies are not overlooked.

---

# 8. Critical Business Services

BCM should be organized around **business services and activities**, not only IT systems.

For example:

```text
Customer Service
      ↓
CRM Platform
      ↓
Database
      ↓
Cloud Infrastructure
      ↓
Network
      ↓
Identity Services
```

If the CRM platform becomes unavailable, the actual business concern is not simply that a technical system has failed.

The key question is:

> **Can the organization continue providing customer service?**

This business-oriented perspective is fundamental to effective BCM.

---

# 9. Critical Business Activities

The organization should identify activities that are essential to delivering important products and services.

Examples include:

```text
Customer Authentication
Payment Processing
Emergency Communications
Order Processing
Customer Support
Network Operations
Financial Processing
Regulatory Reporting
```

The criticality of each activity depends on its business impact and the organization's objectives.

---

# 10. Business Impact Analysis

The **Business Impact Analysis (BIA)** identifies the consequences of disruption to business activities.

A simplified flow is:

```text
Business Activity
       ↓
Potential Disruption
       ↓
Impact Over Time
       ↓
Criticality
       ↓
Recovery Requirements
```

The BIA provides the information required to establish recovery priorities and continuity strategies.

It should consider how the impact of an outage changes over time.

---

# 11. Types of Business Impact

Business impacts may include:

```text
Financial
Operational
Customer
Regulatory
Legal
Reputational
Strategic
Safety
```

A simplified model is:

```text
Service Unavailable
      ↓
Customer Impact
      ↓
Operational Impact
      ↓
Financial Impact
      ↓
Regulatory / Legal Impact
      ↓
Reputational Impact
```

The actual impact profile will depend on the business service and disruption scenario.

---

# 12. Maximum Tolerable Period of Disruption

The organization should determine how long a business activity can tolerate disruption before the consequences become unacceptable.

Conceptually:

```text
Disruption Begins
      ↓
Business Impact Increases
      ↓
Acceptable Threshold
      ↓
Maximum Tolerable Period
```

This provides an important input into recovery and continuity planning.

The terminology and methodology should be aligned with the organization's chosen BCM framework.

---

# 13. Recovery Time Objective

The **Recovery Time Objective (RTO)** defines the targeted time within which a service or activity should be restored following a disruption.

Conceptually:

```text
Disruption
    ↓
    ├───────────────┐
    ↓               ↓
  RTO Target     Recovery
                  Point
```

For example:

```text
Critical Service
RTO = 2 hours
```

This represents a target for restoring the service within two hours.

The RTO should be derived from business requirements rather than simply from the capabilities of the IT department.

---

# 14. Recovery Point Objective

The **Recovery Point Objective (RPO)** defines the acceptable amount of data loss measured in time.

For example:

```text
Last Valid Recovery Point
       ↓
       │← RPO →│
       ↓        ↓
    Recovery   Failure
```

If:

```text
RPO = 30 minutes
```

the recovery strategy should aim to limit data loss to approximately that period, subject to the actual technology and recovery conditions.

---

# 15. RTO and RPO Relationship

RTO and RPO answer different questions.

| Metric  | Question                                                  |
| ------- | --------------------------------------------------------- |
| **RTO** | How quickly must the service recover?                     |
| **RPO** | How much recent data can the organization afford to lose? |

For example:

```text
Critical Business Service

RTO = 1 hour
RPO = 15 minutes
```

This means the organization targets service restoration within one hour while limiting data loss to approximately fifteen minutes.

These values are illustrative and should be established through business requirements and risk analysis.

---

# 16. Risk Assessment

BCM requires an understanding of threats, vulnerabilities, and potential disruption scenarios.

A simplified model is:

```text
Threat
   +
Vulnerability
   ↓
Disruption Scenario
   ↓
Business Impact
   ↓
Risk
```

Potential scenarios include:

```text
Ransomware
Data Center Failure
Cloud Provider Outage
Power Failure
Network Failure
Supplier Failure
Natural Disaster
Workforce Unavailability
```

Risk assessment helps determine which continuity measures are necessary.

---

# 17. Scenario Analysis

The organization should consider realistic disruption scenarios.

For example:

```text
Scenario:
Primary Data Center Unavailable

        ↓

Business Services Affected

        ↓

Customer / Operational Impact

        ↓

Recovery Requirements

        ↓

Continuity Strategy
```

Other scenarios may include:

```text
Cyberattack
Pandemic
Major Supplier Failure
Telecommunications Outage
Loss of Building
Loss of Workforce
Cloud Service Outage
```

Scenario analysis helps test whether continuity strategies are realistic.

---

# 18. Business Continuity Strategy

Once critical activities, impacts, and risks are understood, the organization develops continuity strategies.

Possible strategies include:

```text
Alternate Site
Remote Working
Redundant Systems
Cloud Failover
Backup Infrastructure
Manual Processing
Alternative Supplier
Cross-Trained Employees
Geographic Redundancy
```

The strategy should align with:

```text
Business Criticality
RTO
RPO
Risk
Cost
Regulatory Requirements
Operational Feasibility
```

---

# 19. Strategy Selection

A simplified decision model is:

```text
Business Requirement
        ↓
RTO / RPO
        ↓
Risk
        ↓
Available Options
        ↓
Cost / Feasibility
        ↓
Recovery Strategy
```

For example:

```text
RTO = 1 hour
      ↓
Manual Recovery Not Sufficient
      ↓
Redundant Technology Required
```

The organization should balance resilience requirements against cost, complexity, and risk.

---

# 20. Continuity Strategy Hierarchy

Different services may require different levels of resilience.

```text
Low Criticality
      ↓
Manual Workaround

Moderate Criticality
      ↓
Backup / Restore

High Criticality
      ↓
Alternate Environment

Critical Service
      ↓
Highly Available / Redundant Architecture
```

The appropriate strategy should be proportional to the business requirement.

---

# 21. Business Continuity Plans

The selected strategy must be translated into actionable plans.

A continuity plan may contain:

```text
Activation Criteria
Roles
Responsibilities
Contact Information
Recovery Priorities
Communication Procedures
Manual Workarounds
Alternate Locations
Technology Recovery
Supplier Contacts
Escalation Procedures
Return-to-Normal Procedures
```

A plan should be practical enough to support decision-making during an actual disruption.

---

# 22. Plan Structure

A simplified continuity plan flow is:

```text
Disruption
   ↓
Plan Activation
   ↓
Incident / Crisis Management
   ↓
Business Continuity Procedures
   ↓
Service Prioritization
   ↓
Recovery
   ↓
Return to Normal
```

The plan should clearly identify who makes decisions and who performs each recovery activity.

---

# 23. Roles and Responsibilities

BCM requires clear accountability.

A typical structure may include:

```text
Executive Management
        ↓
Crisis Management Team
        ↓
Business Continuity Manager
        ↓
Business Unit Owners
        ↓
IT / Disaster Recovery
        ↓
Supporting Functions
```

Supporting functions may include:

```text
Cybersecurity
GRC
Risk
Facilities
HR
Communications
Legal
Procurement
Third-Party Management
```

Clearly defined responsibilities reduce confusion during a crisis.

---

# 24. Crisis Management vs. Business Continuity

These functions are related but have different primary purposes.

### Crisis Management

Focuses on:

```text
Strategic Decisions
Leadership
External Stakeholders
Reputation
Major Business Impact
```

### Business Continuity

Focuses on:

```text
Maintaining Critical Activities
Alternative Operations
Service Continuity
Operational Recovery
```

A simplified relationship is:

```text
Crisis Management
       ↓
Strategic Direction
       ↓
Business Continuity
       ↓
Operational Continuity
```

---

# 25. Business Continuity Activation

Not every incident requires full BCM activation.

Activation decisions may consider:

```text
Duration
Business Impact
Service Criticality
Geographic Scope
Customer Impact
Regulatory Impact
Resource Availability
```

A simplified decision model is:

```text
Disruption
    ↓
Impact Assessment
    ↓
BCM Activation Threshold?
    ↙              ↘
  NO                YES
   ↓                  ↓
Normal Response   Activate BCM
```

Defined activation criteria help prevent both underreaction and unnecessary escalation.

---

# 26. Crisis Escalation

A serious disruption may escalate through several levels:

```text
Operational Incident
        ↓
Major Incident
        ↓
Business Continuity Activation
        ↓
Crisis Management
        ↓
Executive Management
```

The thresholds for each level should be clearly established before an actual crisis occurs.

---

# 27. Communication During Disruption

Communication is a critical continuity capability.

The organization should establish processes for:

```text
Internal Communication
Customer Communication
Supplier Communication
Regulator Communication
Executive Communication
Employee Communication
Media Communication
```

A simplified model is:

```text
Crisis
  ↓
Situation Assessment
  ↓
Approved Communication
  ↓
Stakeholder Notification
  ↓
Continuous Updates
```

Communication procedures should identify both the responsible parties and the approved communication channels.

---

# 28. Employee Continuity

People are critical dependencies for most business services.

A continuity strategy should consider:

```text
Workforce Availability
Remote Working
Cross-Training
Succession
Alternate Personnel
Critical Skills
Access to Systems
Communication
```

For example:

```text
Critical Employee Unavailable
        ↓
Backup Employee
        ↓
Cross-Training
        ↓
Service Continues
```

People-related continuity risks should be incorporated into the BIA and risk assessment.

---

# 29. Facility Continuity

Organizations should consider the potential loss of physical facilities.

Possible strategies include:

```text
Alternate Office
Remote Work
Secondary Site
Hot Site
Warm Site
Cold Site
```

The appropriate strategy depends on:

```text
RTO
Cost
Criticality
Operational Requirements
```

---

# 30. Technology Continuity

Technology continuity may involve:

```text
Redundancy
High Availability
Backup
Replication
Failover
Alternate Data Center
Cloud Recovery
Disaster Recovery
```

A simplified model is:

```text
Primary System
      ↓
Failure
      ↓
Failover
      ↓
Secondary System
      ↓
Service Continues
```

Technology continuity should be designed around business recovery requirements.

---

# 31. Data Continuity

Data protection is a core component of business resilience.

Strategies may include:

```text
Backup
Replication
Immutable Backup
Offline Backup
Geographic Redundancy
Point-in-Time Recovery
```

For cyber threats, recovery copies should be protected against unauthorized alteration or deletion.

The ability to create a backup does not automatically demonstrate that the organization can successfully recover from it.

---

# 32. Supplier Continuity

Critical suppliers can become significant points of failure.

The organization should evaluate:

```text
Supplier Criticality
Dependency
RTO
Supplier Recovery Capability
Alternative Suppliers
Contractual Requirements
Communication
```

A simple model is:

```text
Critical Supplier
      ↓
Supplier Failure
      ↓
Alternative?
   ↙        ↘
 YES         NO
 ↓            ↓
Failover    Continuity Risk
```

Supplier continuity should form part of third-party risk management.

---

# 33. Dependency Mapping

BCM should identify dependencies between:

```text
Business Service
      ↓
People
      ↓
Process
      ↓
Technology
      ↓
Data
      ↓
Facility
      ↓
Supplier
```

For example:

```text
Customer Service
      ↓
CRM
      ↓
Cloud Platform
      ↓
Identity Provider
      ↓
Network
      ↓
Cloud Supplier
```

A disruption in one dependency can affect the entire business service.

---

# 34. Business Continuity Dependency Model

A mature organization should understand the complete dependency chain:

```text
Service
  ↓
Process
  ↓
Application
  ↓
Infrastructure
  ↓
Data
  ↓
People
  ↓
Supplier
```

This allows recovery priorities to be established based on actual business dependencies rather than isolated technology components.

---

# 35. Training and Awareness

Employees need to understand their BCM responsibilities.

Training may cover:

```text
Emergency Procedures
Plan Activation
Communication
Remote Working
Manual Procedures
Escalation
Crisis Roles
Recovery Responsibilities
```

Training ensures that continuity plans are understood before a disruption occurs.

---

# 36. Testing and Exercises

Continuity plans must be tested.

Testing can include:

```text
Document Review
Walkthrough
Tabletop Exercise
Simulation
Technical Recovery Test
Failover Test
Full-Scale Exercise
```

A possible progression is:

```text
Document Review
      ↓
Tabletop
      ↓
Simulation
      ↓
Technical Test
      ↓
Full Exercise
```

Testing provides evidence that plans are not merely documented but can actually work under realistic conditions.

---

# 37. Tabletop Exercise

A tabletop exercise allows participants to discuss a disruption scenario without necessarily affecting production systems.

Example:

```text
Scenario:
Primary Data Center Unavailable

      ↓

What happens first?

      ↓

Who activates BCM?

      ↓

Which services are prioritized?

      ↓

How are customers informed?

      ↓

How is recovery performed?
```

Tabletop exercises are particularly useful for identifying gaps in roles, procedures, escalation, communication, and decision-making.

---

# 38. Technical Recovery Testing

Technical recovery tests verify whether systems can actually be recovered.

For example:

```text
Production Failure
      ↓
Backup / Replica
      ↓
Recovery
      ↓
Application Validation
      ↓
Business Validation
```

A backup existing does not necessarily prove that recovery will succeed.

Recovery testing should therefore validate both technical recovery and the business's ability to use the recovered service.

---

# 39. Exercise Findings

Testing should produce documented findings.

```text
Exercise
   ↓
Observation
   ↓
Finding
   ↓
Improvement Action
   ↓
Owner
   ↓
Remediation
   ↓
Retest
```

This creates a feedback loop between BCM testing and continuous improvement.

---

# 40. BCM Metrics

Useful BCM metrics include:

```text
Percentage of Critical Services With Plans
Percentage of Plans Tested
Successful Recovery Tests
RTO Achievement
RPO Achievement
Open BCM Findings
Overdue Actions
Critical Supplier Coverage
Employee Training Coverage
Exercise Frequency
```

These metrics provide management with visibility into the organization's continuity posture.

---

# 41. RTO Achievement

Organizations should compare actual recovery performance with the established target.

```text
Target RTO
      ↓
Actual Recovery Time
      ↓
Compare
      ↓
Met / Not Met
```

For example:

```text
RTO = 2 hours
Actual Recovery = 1 hour 40 minutes
Result = Target achieved
```

These values are illustrative.

Repeated failure to achieve RTO targets may indicate that the continuity strategy or recovery architecture needs reassessment.

---

# 42. RPO Achievement

Similarly:

```text
Target RPO
      ↓
Actual Data Loss
      ↓
Compare
      ↓
Met / Not Met
```

For example:

```text
RPO = 30 minutes
Actual Data Loss = 12 minutes
Result = Target achieved
```

These values are illustrative.

RPO performance should be validated during appropriate recovery tests.

---

# 43. BCM Documentation

Important BCM documentation may include:

```text
BCM Policy
Business Impact Analysis
Risk Assessment
Continuity Strategies
Business Continuity Plans
Crisis Management Plan
Disaster Recovery Plans
Contact Lists
Dependency Maps
Exercise Results
Recovery Test Results
Improvement Actions
```

Documentation should be reviewed and updated as the organization changes.

---

# 44. BCM and Cybersecurity

Cybersecurity incidents are important BCM scenarios.

A ransomware scenario might be:

```text
Ransomware
   ↓
Systems Unavailable
   ↓
Business Disruption
   ↓
BCM Activation
   ↓
Manual / Alternate Operations
   ↓
Secure Recovery
   ↓
Return to Normal
```

This demonstrates that cybersecurity and BCM are closely connected while remaining distinct disciplines.

---

# 45. BCM and Disaster Recovery

A useful integrated model is:

```text
Business Impact Analysis
          ↓
Business Requirements
          ↓
Continuity Strategy
          ↓
Technology Requirements
          ↓
Disaster Recovery Strategy
          ↓
Technical Recovery
          ↓
Business Validation
```

Disaster recovery should therefore be driven by business requirements.

---

# 46. BCM and Risk Management

The relationship with enterprise risk management can be represented as:

```text
Risk Identification
       ↓
Disruption Scenarios
       ↓
Business Impact
       ↓
Risk Assessment
       ↓
Continuity Strategy
       ↓
Risk Treatment
```

BCM is therefore one mechanism through which the organization can treat operational resilience risks.

---

# 47. BCM and Third-Party Risk

Critical supplier dependencies should be incorporated into continuity planning.

```text
Business Service
       ↓
Critical Supplier
       ↓
Supplier Disruption
       ↓
Business Impact
       ↓
Continuity Strategy
```

Supplier assessments may include:

```text
BCM Capability
DR Capability
Recovery Objectives
Testing
Redundancy
Incident Notification
Subcontractor Dependencies
```

This helps ensure that organizational resilience does not depend on unassessed third parties.

---

# 48. BCM and Compliance

Organizations may have legal, regulatory, contractual, or industry requirements related to continuity and resilience.

The GRC process should connect:

```text
Requirement
   ↓
BCM Control
   ↓
Implementation
   ↓
Evidence
   ↓
Testing
   ↓
Assurance
```

This creates traceability between external requirements and actual continuity capabilities.

---

# 49. BCM Evidence

Examples of BCM evidence include:

```text
Approved BCM Policy
BIA Results
Risk Assessments
Continuity Plans
Training Records
Exercise Records
Recovery Test Results
Meeting Minutes
Improvement Actions
Management Approvals
```

Evidence demonstrates that BCM is an operating management process rather than simply a collection of documents.

---

# 50. BCM Governance Dashboard

An executive dashboard could show:

```text
        BUSINESS CONTINUITY STATUS

Critical Services With Plans       96%
Plans Tested                       88%
RTO Achievement                    91%
RPO Achievement                    94%
Critical Suppliers Assessed        89%
Open High Findings                  4
Overdue Actions                     3
Last Enterprise Exercise          Q2
```

The values are illustrative.

The dashboard should focus on resilience, risk, and recovery capability rather than simply the number of BCM documents completed.

---

# 51. BCM Maturity

Organizations can assess BCM maturity using stages such as:

```text
Level 1 – Ad Hoc
Level 2 – Developing
Level 3 – Defined
Level 4 – Managed
Level 5 – Optimized
```

### Level 1 – Ad Hoc

```text
Limited Planning
Reactive Response
Little Testing
```

### Level 2 – Developing

```text
Basic Plans
Some Ownership
Limited Exercises
```

### Level 3 – Defined

```text
Formal BCM Framework
BIA
Risk Assessment
Documented Plans
Regular Testing
```

### Level 4 – Managed

```text
Metrics
Integrated Risk Management
Supplier Resilience
Management Reporting
```

### Level 5 – Optimized

```text
Continuous Improvement
Advanced Analytics
Integrated Resilience
Scenario Modeling
Adaptive Recovery
```

---

# 52. Continuous Improvement

The BCM lifecycle must continuously evolve.

```text
Test
 ↓
Findings
 ↓
Improvements
 ↓
Updated Plans
 ↓
Retest
 ↓
Measure
 ↓
Improve
 ↺
```

This is particularly important because:

```text
Business Changes
Technology Changes
Threats Change
Suppliers Change
Regulations Change
```

A continuity plan that was effective in the past may no longer be sufficient after major organizational or technological changes.

---

# 53. BCM Review Triggers

Plans should be reviewed when significant changes occur.

Examples include:

```text
New Critical System
Major Cloud Migration
New Supplier
Business Acquisition
New Regulation
Major Organizational Change
New Threat
Major Incident
Failed Recovery Test
Change in Business Strategy
```

These events can change business dependencies, risk levels, recovery requirements, or continuity strategies.

---

# 54. Post-Incident BCM Review

Following a major disruption:

```text
Incident
   ↓
Recovery
   ↓
BCM Review
   ↓
What Worked?
   ↓
What Failed?
   ↓
What Must Change?
   ↓
Plan Update
   ↓
Retesting
```

This ensures that real-world disruption experience is incorporated into the BCM program.

---

# 55. Enterprise Resilience Model

BCM contributes to broader organizational resilience.

```text
Risk Management
       +
Cybersecurity
       +
Business Continuity
       +
Disaster Recovery
       +
Crisis Management
       +
Third-Party Resilience
       ↓
Enterprise Resilience
```

The objective is not merely to recover technology.

It is to maintain the organization's ability to deliver critical outcomes despite disruption.

---

# 56. Integrated BCM Lifecycle

A complete GRC-oriented model can be represented as:

```text
                         GOVERNANCE
                             ↓
                    BCM POLICY & SCOPE
                             ↓
                  BUSINESS IMPACT ANALYSIS
                             ↓
                      RISK ASSESSMENT
                             ↓
                  CONTINUITY STRATEGY
                             ↓
                    PLAN DEVELOPMENT
                             ↓
                 IMPLEMENTATION & TRAINING
                             ↓
                     TESTING & EXERCISES
                             ↓
                       DISRUPTION
                             ↓
                    RESPONSE / ACTIVATION
                             ↓
                    BUSINESS CONTINUITY
                             ↓
                        RECOVERY
                             ↓
                    RETURN TO NORMAL
                             ↓
                    POST-INCIDENT REVIEW
                             ↓
                  IMPROVEMENT ACTIONS
                             ↓
                    PLAN / CONTROL UPDATE
                             ↓
                         RETEST
                             ↺
```

---

# 57. GRC Traceability Model

From a GRC perspective, BCM should create a traceable relationship:

```text
Business Requirement
        ↓
Critical Business Activity
        ↓
Business Impact
        ↓
Risk
        ↓
Recovery Requirement
        ↓
Continuity Strategy
        ↓
Control
        ↓
Test
        ↓
Evidence
        ↓
Management Assurance
```

This allows management to understand **why a continuity control exists, what risk it addresses, and whether it actually works**.

---

# 58. Practical Example – Telecommunications Service

Consider a critical telecommunications customer service.

```text
Business Service
Customer Connectivity
        ↓
Critical Activity
Network Service Delivery
        ↓
Dependencies
Network + Data Center + Cloud + Identity + Suppliers
        ↓
Potential Disruption
Cyberattack / Power Failure / Network Failure
        ↓
Business Impact
Customer Service Disruption
        ↓
Recovery Requirement
High Availability
        ↓
Continuity Strategy
Redundancy + Geographic Failover
        ↓
Testing
Failover Exercise
        ↓
Evidence
Test Results
        ↓
Improvement
Architecture / Process Changes
```

This illustrates how BCM connects business requirements to technical resilience.

---

# 59. Practical Example – Ransomware

A ransomware scenario may follow:

```text
Ransomware Attack
       ↓
Critical Systems Encrypted
       ↓
Incident Response
       ↓
BCM Activation
       ↓
Prioritize Critical Services
       ↓
Manual / Alternate Operations
       ↓
Secure Backup Recovery
       ↓
Business Validation
       ↓
Service Restoration
       ↓
Lessons Learned
       ↓
Improve Resilience
```

The recovery strategy should ensure that compromised systems are not simply restored without addressing the underlying security and resilience issues.

---

# 60. Key GRC Takeaways

An effective **Business Continuity Management Lifecycle** should provide:

```text
1. Executive Governance
2. Clear BCM Scope
3. Business Impact Analysis
4. Risk Assessment
5. Critical Activity Identification
6. RTO and RPO Requirements
7. Continuity Strategies
8. Documented Plans
9. Defined Roles and Responsibilities
10. Employee Training
11. Regular Testing
12. Supplier Resilience
13. Disaster Recovery Integration
14. Crisis Management Integration
15. Evidence and Assurance
16. Performance Measurement
17. Post-Incident Review
18. Continuous Improvement
```

The central principle is:

> **Business continuity is not simply about recovering systems; it is about maintaining the organization's ability to deliver critical business outcomes when normal operations are disrupted.**

A mature GRC-driven BCM program therefore creates a continuous cycle:

```text
Govern
   ↓
Understand Business Impact
   ↓
Assess Risk
   ↓
Design Continuity
   ↓
Implement
   ↓
Test
   ↓
Respond
   ↓
Recover
   ↓
Review
   ↓
Improve
   ↺
```

This transforms business continuity from a collection of recovery documents into an **enterprise resilience capability governed by risk, business priorities, measurable recovery requirements, testing, evidence, and continuous improvement**.

## Part 2 – Business Impact Analysis Model

The **Business Impact Analysis (BIA)** is one of the most important components of Business Continuity Management because it establishes what the organization must protect, how quickly critical activities need to recover, and what consequences may result from disruption.

From a GRC perspective, the BIA connects **business activities, dependencies, impacts, criticality, recovery requirements, and risk-based decision-making**.

A simplified BIA model is:

```text
Business Service
       ↓
Business Activity
       ↓
Dependencies
       ↓
Disruption Scenario
       ↓
Business Impact
       ↓
Criticality
       ↓
Recovery Requirements
       ↓
RTO / RPO
       ↓
Continuity Strategy
```

---

# 1. Purpose of a Business Impact Analysis

The primary purpose of a BIA is to understand the consequences of disruption to business activities and establish appropriate recovery requirements.

The BIA helps answer questions such as:

```text
What business activities are critical?
What happens if they stop?
How quickly must they recover?
How much data can be lost?
Which dependencies are required?
What level of service is acceptable?
What are the financial consequences?
What are the regulatory consequences?
What resources are required for recovery?
```

The BIA therefore provides the business foundation for continuity planning.

---

# 2. Business-Centric Perspective

A BIA should begin with the **business service or activity**, rather than starting with individual technologies.

For example:

```text
Customer Payment Processing
          ↓
Payment Processing Activity
          ↓
Applications
          ↓
Database
          ↓
Network
          ↓
Cloud Infrastructure
          ↓
External Payment Provider
```

The BIA asks what happens to the **business service** if any of these dependencies become unavailable.

This prevents the organization from treating technology availability as the objective itself.

---

# 3. BIA Scope

The organization should define the scope of the BIA.

The scope may include:

```text
Business Units
Business Services
Business Processes
Critical Activities
Applications
Technology
Facilities
Employees
Data
Suppliers
Geographic Locations
```

A simplified hierarchy is:

```text
Enterprise
    ↓
Business Unit
    ↓
Business Service
    ↓
Business Process
    ↓
Business Activity
    ↓
Dependencies
```

The scope should be broad enough to identify important business dependencies.

---

# 4. Identifying Business Services

The first step is to identify the services the organization provides.

Examples include:

```text
Customer Support
Payment Processing
Network Connectivity
Online Banking
Order Fulfillment
Healthcare Services
Emergency Communications
Regulatory Reporting
Financial Processing
```

Each service can then be decomposed into the activities and dependencies required to deliver it.

---

# 5. Identifying Critical Activities

Not every business activity has the same level of importance.

A BIA should distinguish between:

```text
Critical Activities
Important Activities
Supporting Activities
Non-Critical Activities
```

For example:

```text
Customer Service
      ↓
Customer Authentication     → Critical
Case Management             → Important
Reporting                   → Supporting
Historical Analysis         → Lower Criticality
```

The classification should be based on business impact rather than personal judgment.

---

# 6. Business Impact Over Time

The consequences of an outage may increase as the disruption continues.

A simplified model is:

```text
Disruption Begins
       ↓
Minimal Impact
       ↓
Increasing Impact
       ↓
Significant Impact
       ↓
Severe Impact
       ↓
Unacceptable Impact
```

For example:

```text
0–30 Minutes
Limited Operational Impact

30–120 Minutes
Increasing Customer Impact

2–8 Hours
Significant Financial / Operational Impact

8–24 Hours
Major Business Impact

>24 Hours
Potential Regulatory / Strategic Impact
```

The actual time periods depend on the organization and business activity.

---

# 7. Types of Business Impact

A BIA should consider multiple impact categories.

```text
Financial
Operational
Customer
Regulatory
Legal
Reputational
Strategic
Safety
```

A single disruption may produce several impacts simultaneously.

For example:

```text
System Outage
     ↓
Operational Disruption
     ↓
Customer Impact
     ↓
Revenue Loss
     ↓
Regulatory Consequences
     ↓
Reputational Damage
```

---

# 8. Financial Impact

Financial impact may include:

```text
Lost Revenue
Transaction Losses
Recovery Costs
Penalty Costs
Compensation
Overtime
Emergency Procurement
Contractual Penalties
```

For example:

```text
Service Outage
      ↓
Transactions Cannot Be Completed
      ↓
Revenue Loss
      ↓
Financial Impact
```

Financial impact may increase significantly as downtime continues.

---

# 9. Operational Impact

Operational impact considers how disruption affects normal business operations.

Examples include:

```text
Work Cannot Be Performed
Customer Requests Delayed
Orders Cannot Be Processed
Employees Cannot Access Systems
Production Stops
Manual Processing Required
Service Levels Degrade
```

A BIA should determine which operational consequences are acceptable and for how long.

---

# 10. Customer Impact

Customer impact can include:

```text
Service Unavailability
Transaction Delays
Loss of Access
Poor Service Quality
Communication Failure
Customer Complaints
Customer Attrition
```

For customer-facing services, customer impact may become a major driver of recovery priorities.

---

# 11. Regulatory and Legal Impact

Some business activities are subject to regulatory or contractual requirements.

A disruption may result in:

```text
Regulatory Breach
Reporting Failure
Contractual Breach
Legal Exposure
Financial Penalties
Loss of License
Supervisory Action
```

Therefore, regulatory impact should be considered alongside financial and operational impact.

---

# 12. Reputational Impact

Some disruptions can damage stakeholder confidence.

Potential impacts include:

```text
Loss of Customer Trust
Negative Publicity
Investor Concern
Partner Concern
Brand Damage
Loss of Market Confidence
```

Reputational impact can be difficult to quantify but should still be considered in the BIA.

---

# 13. Strategic Impact

A prolonged disruption may affect the organization's strategic objectives.

Examples include:

```text
Delayed Product Launch
Loss of Market Opportunity
Competitive Disadvantage
Failure to Meet Strategic Objectives
Loss of Major Customers
```

Strategic impact becomes particularly important for critical enterprise services.

---

# 14. Impact Rating

Organizations may assign an impact rating to each business activity.

For example:

```text
1 – Very Low
2 – Low
3 – Moderate
4 – High
5 – Critical
```

A simplified model:

```text
Business Activity
       ↓
Impact Assessment
       ↓
Financial
Operational
Customer
Regulatory
Reputational
Strategic
       ↓
Overall Impact Rating
```

The organization should define clear criteria for each rating.

---

# 15. Impact Rating Criteria

A mature BIA should establish objective criteria.

For example:

| Impact Level | Example Description                         |
| ------------ | ------------------------------------------- |
| Very Low     | Minimal disruption                          |
| Low          | Limited operational effect                  |
| Moderate     | Noticeable business disruption              |
| High         | Significant financial or operational impact |
| Critical     | Severe or potentially unacceptable impact   |

The exact thresholds should be tailored to the organization.

---

# 16. Criticality Classification

Once impacts are assessed, activities can be classified according to criticality.

```text
Critical
   ↓
High
   ↓
Moderate
   ↓
Low
```

For example:

```text
Emergency Communication      → Critical
Payment Processing           → Critical
Customer Support             → High
Internal Reporting           → Moderate
Historical Analysis          → Low
```

Criticality should be supported by documented impact criteria.

---

# 17. Recovery Requirements

The BIA translates business impact into recovery requirements.

```text
Business Impact
      ↓
Criticality
      ↓
Recovery Requirement
      ↓
RTO
      ↓
RPO
      ↓
Minimum Service Level
```

This is one of the most important outputs of the BIA.

---

# 18. Recovery Time Objective

The **RTO** represents the targeted time within which a business activity or service should be restored.

For example:

```text
Business Service
      ↓
Maximum Acceptable Downtime
      ↓
RTO
```

Example:

```text
Payment Processing
RTO = 1 hour
```

The organization therefore establishes a recovery target based on business requirements.

---

# 19. Recovery Point Objective

The **RPO** represents the acceptable amount of data loss measured in time.

```text
Last Recoverable Data
        ↓
        │← RPO →│
        ↓        ↓
      Recovery  Failure
```

Example:

```text
Payment Database
RPO = 15 minutes
```

This means the recovery strategy should aim to limit data loss to approximately fifteen minutes.

---

# 20. Minimum Business Continuity Objective

The organization may also define the minimum acceptable level of service during disruption.

For example:

```text
Normal Service
100%
   ↓
Disruption
   ↓
Continuity Mode
60%
   ↓
Recovery
   ↓
Normal Service
100%
```

The organization may determine that operating at reduced capacity is acceptable temporarily.

For example:

```text
Normal Customer Support = 100 agents
Continuity Mode = 40 agents
```

The exact requirement depends on business needs.

---

# 21. Dependencies

A BIA should identify the resources and dependencies required for each business activity.

These may include:

```text
People
Processes
Applications
Infrastructure
Data
Facilities
Networks
Suppliers
Utilities
Third Parties
```

A dependency model may look like:

```text
Business Activity
       ↓
People
       ↓
Process
       ↓
Application
       ↓
Infrastructure
       ↓
Data
       ↓
Supplier
```

This helps identify potential single points of failure.

---

# 22. People Dependencies

People are often critical dependencies.

The BIA may identify:

```text
Required Roles
Required Skills
Minimum Staffing
Key Personnel
Backup Personnel
Shift Requirements
Location Requirements
```

For example:

```text
Critical Service
      ↓
5 Specialized Engineers Required
      ↓
2 Backup Engineers
      ↓
Cross-Training Required
```

This ensures that recovery plans do not assume unlimited personnel availability.

---

# 23. Technology Dependencies

Technology dependencies may include:

```text
Applications
Servers
Databases
Networks
Cloud Services
Identity Services
Security Systems
Storage
Communication Systems
```

For example:

```text
Customer Service
      ↓
CRM
      ↓
Identity Provider
      ↓
Network
      ↓
Cloud Platform
```

Failure of one dependency may affect the entire service.

---

# 24. Facility Dependencies

Some activities depend on physical locations.

Examples include:

```text
Data Centers
Offices
Call Centers
Warehouses
Manufacturing Facilities
Operations Centers
```

The BIA should determine whether the activity can operate from:

```text
Primary Site
Alternate Site
Remote Location
Home Working
```

---

# 25. Supplier Dependencies

Third parties may be critical to service delivery.

Examples include:

```text
Cloud Providers
Telecommunications Providers
Payment Providers
Managed Security Providers
Software Vendors
Logistics Providers
Outsourced Operations
```

A BIA should identify these dependencies and assess their effect on recovery.

---

# 26. Dependency Chain

A complete dependency chain may look like:

```text
Business Service
        ↓
Business Process
        ↓
Critical Activity
        ↓
People
        ↓
Application
        ↓
Infrastructure
        ↓
Data
        ↓
Facility
        ↓
Supplier
```

This provides a comprehensive view of what must be available to maintain the business service.

---

# 27. BIA Data Collection

Organizations may collect BIA information through:

```text
Interviews
Workshops
Questionnaires
Surveys
Document Review
Process Analysis
System Mapping
Business Owner Validation
```

Business owners should participate because they understand the operational consequences of disruption.

---

# 28. Business Owner Role

Business owners are important participants in the BIA.

They typically help identify:

```text
Critical Activities
Business Impact
Dependencies
Critical Resources
Recovery Priorities
RTO
RPO
Minimum Service Levels
```

GRC or BCM teams may facilitate the assessment, but business owners should validate the results.

---

# 29. BIA Questionnaire

A BIA questionnaire may include questions such as:

```text
What business activity do you perform?

What happens if the activity becomes unavailable?

What is the impact after 1 hour?

What is the impact after 4 hours?

What is the impact after 24 hours?

What systems are required?

What data is required?

What personnel are required?

Which suppliers are required?

What is the required RTO?

What is the required RPO?

What is the minimum acceptable service level?
```

The questionnaire should produce information that can be analyzed consistently.

---

# 30. BIA Assessment Workflow

A typical BIA workflow is:

```text
Identify Business Activity
          ↓
Identify Dependencies
          ↓
Assess Impact
          ↓
Assess Impact Over Time
          ↓
Determine Criticality
          ↓
Define RTO / RPO
          ↓
Define Minimum Service
          ↓
Business Owner Validation
          ↓
Management Approval
```

This creates a structured and auditable process.

---

# 31. BIA and Risk Management

The BIA and risk assessment serve different but complementary purposes.

```text
Risk Assessment
      ↓
What could go wrong?
      ↓
Likelihood + Impact
```

While:

```text
BIA
      ↓
What happens if the business activity is disrupted?
      ↓
Business Consequences + Recovery Requirements
```

Together:

```text
Risk Assessment
        +
Business Impact Analysis
        ↓
Continuity Strategy
```

---

# 32. BIA and Risk Scenarios

A BIA can evaluate multiple disruption scenarios.

For example:

```text
Scenario 1
Cyberattack
      ↓
Service Unavailable

Scenario 2
Cloud Outage
      ↓
Service Unavailable

Scenario 3
Facility Loss
      ↓
Service Unavailable

Scenario 4
Supplier Failure
      ↓
Service Unavailable
```

The business impact may be similar even though the causes are different.

---

# 33. BIA Prioritization

Once business activities are assessed, recovery priorities can be established.

For example:

```text
Priority 1
Critical Services
       ↓
Priority 2
High-Impact Services
       ↓
Priority 3
Moderate Services
       ↓
Priority 4
Low-Impact Services
```

Recovery resources should generally be allocated according to business priorities and approved risk decisions.

---

# 34. Recovery Sequence

The BIA can influence the order in which services are recovered.

For example:

```text
Critical Infrastructure
        ↓
Identity Services
        ↓
Core Applications
        ↓
Customer Services
        ↓
Supporting Applications
        ↓
Non-Critical Services
```

The exact sequence depends on technical and business dependencies.

---

# 35. BIA Dependency Conflict

Sometimes two services may both be considered critical but depend on the same limited resource.

For example:

```text
Service A ──┐
            ├── Shared Database
Service B ──┘
```

If the database cannot be recovered immediately, the organization may need to determine which service receives priority.

This demonstrates why BIA results should be analyzed across the enterprise rather than only within individual departments.

---

# 36. BIA Consolidation

Individual business assessments should eventually be consolidated.

```text
Business Unit A
      ↓
BIA Results
      ↓
Business Unit B
      ↓
BIA Results
      ↓
Business Unit C
      ↓
BIA Results
      ↓
Enterprise BIA
```

Enterprise consolidation can reveal:

```text
Shared Dependencies
Common Applications
Single Points of Failure
Conflicting Priorities
Critical Suppliers
Concentration Risk
```

---

# 37. BIA and Technology Architecture

BIA results should influence technology architecture.

For example:

```text
BIA
 ↓
Critical Service
 ↓
RTO = 1 hour
 ↓
Single Data Center Insufficient
 ↓
Redundant Architecture Required
```

This demonstrates how business requirements can drive technical resilience investments.

---

# 38. BIA and Disaster Recovery

The BIA provides important requirements for disaster recovery.

```text
BIA
 ↓
Critical Service
 ↓
RTO / RPO
 ↓
Technology Recovery Requirements
 ↓
DR Strategy
 ↓
DR Architecture
 ↓
DR Testing
```

Without a reliable BIA, disaster recovery investments may not align with actual business priorities.

---

# 39. BIA and Cybersecurity

Cybersecurity resilience can also be influenced by BIA results.

For example:

```text
Critical Service
      ↓
High Business Impact
      ↓
Short RTO
      ↓
High Resilience Requirement
      ↓
Strong Security + Recovery Controls
```

Critical business services may therefore require stronger preventive, detective, and recovery controls.

---

# 40. BIA and Third-Party Risk

If a critical business activity depends on a supplier, the supplier becomes part of the continuity analysis.

```text
Critical Business Service
       ↓
Critical Supplier
       ↓
Supplier Failure
       ↓
Business Impact
       ↓
Recovery Requirement
```

This can lead to additional requirements such as:

```text
Supplier BCM Assessment
Contractual RTO
Supplier DR Testing
Alternative Supplier
Redundancy
Incident Notification
```

---

# 41. BIA and Compliance

Regulatory and contractual requirements may influence BIA results.

For example:

```text
Regulatory Requirement
        ↓
Critical Business Activity
        ↓
Maximum Acceptable Disruption
        ↓
Recovery Requirement
        ↓
Control
        ↓
Evidence
```

This provides traceability between compliance obligations and continuity requirements.

---

# 42. BIA Evidence

Important BIA evidence may include:

```text
BIA Methodology
BIA Questionnaires
Business Owner Assessments
Impact Ratings
Dependency Maps
RTO / RPO Records
Approval Records
BIA Reports
Review Records
Management Decisions
```

These records provide evidence that recovery requirements were established through a structured process.

---

# 43. BIA Review and Validation

BIA results should be periodically reviewed.

Review may confirm:

```text
Business Activity
Criticality
Dependencies
Impact Ratings
RTO
RPO
Minimum Service Level
Business Owner
```

A simplified cycle is:

```text
BIA
 ↓
Business Validation
 ↓
Management Approval
 ↓
Implementation
 ↓
Review
 ↓
Update
 ↺
```

---

# 44. BIA Change Triggers

A BIA should be reassessed when significant changes occur.

Examples include:

```text
New Business Service
New Application
Major Cloud Migration
New Supplier
Business Acquisition
Organizational Restructuring
New Regulation
Major Technology Change
Major Incident
Failed Recovery Test
Change in Business Strategy
```

These changes can alter both business impact and recovery requirements.

---

# 45. BIA Maturity

BIA maturity can be considered across several levels.

### Level 1 – Basic

```text
Limited Identification
Informal Assessments
Minimal Documentation
```

### Level 2 – Developing

```text
Structured Questionnaires
Business Owner Participation
Basic RTO / RPO
```

### Level 3 – Defined

```text
Formal BIA Methodology
Standard Impact Criteria
Dependency Mapping
Documented Approvals
```

### Level 4 – Managed

```text
Enterprise Consolidation
Metrics
Scenario Analysis
Integrated Risk Management
```

### Level 5 – Optimized

```text
Dynamic Dependency Mapping
Advanced Analytics
Continuous Monitoring
Scenario Modeling
Integrated Resilience Planning
```

---

# 46. Executive BIA View

Executives generally do not need every individual BIA record.

They need a consolidated view of:

```text
Critical Business Services
Highest Business Impacts
Critical Dependencies
Recovery Requirements
Major Gaps
Resilience Investments
Unresolved Risks
```

A simplified executive view might look like:

```text
             ENTERPRISE BIA

Critical Services              42
High-Risk Services             11
Services With RTO < 4 hrs      18
Critical Suppliers             9
Major Recovery Gaps             5
Unresolved High Risks           3
```

The values are illustrative.

---

# 47. BIA Traceability Model

From a GRC perspective, the BIA should create a clear chain:

```text
Business Service
       ↓
Business Activity
       ↓
Business Impact
       ↓
Criticality
       ↓
Dependencies
       ↓
Recovery Requirement
       ↓
RTO / RPO
       ↓
Continuity Strategy
       ↓
Control
       ↓
Test
       ↓
Evidence
```

This makes the BIA a valuable source of governance and assurance information.

---

# 48. Practical Example – Telecommunications

Consider a telecommunications operator.

```text
Business Service
Mobile Network Connectivity
        ↓
Critical Activity
Network Service Delivery
        ↓
Dependencies
Network + Data Center + Power + Cloud + Suppliers
        ↓
Disruption
Major Network Failure
        ↓
Business Impact
Customers Cannot Access Services
        ↓
Criticality
Critical
        ↓
Recovery Requirement
Very Short RTO
        ↓
Continuity Strategy
Redundancy + Geographic Failover
```

The BIA therefore provides the business justification for significant resilience investments.

---

# 49. Practical Example – Banking

Consider a payment processing service.

```text
Payment Processing
       ↓
Critical Activity
Transaction Authorization
       ↓
Impact
Transactions Cannot Be Completed
       ↓
Financial Impact
Revenue / Transaction Loss
       ↓
Customer Impact
Payment Failure
       ↓
Regulatory Impact
Potential Compliance Consequences
       ↓
Criticality
Critical
       ↓
Recovery Requirement
Very Short RTO + Low RPO
```

The BIA provides the foundation for designing appropriate continuity and recovery capabilities.

---

# 50. Key GRC Takeaways

A mature **Business Impact Analysis Model** should establish:

```text
1. Critical Business Services
2. Critical Business Activities
3. Business Impact Categories
4. Impact Over Time
5. Criticality
6. Business Dependencies
7. Recovery Priorities
8. RTO Requirements
9. RPO Requirements
10. Minimum Service Levels
11. People Requirements
12. Technology Requirements
13. Facility Requirements
14. Supplier Dependencies
15. Regulatory Requirements
16. Business Owner Accountability
17. Management Approval
18. Periodic Review
```

The central principle is:

> **The BIA translates business importance and disruption consequences into measurable recovery requirements.**

A strong GRC-oriented BIA therefore creates a traceable relationship:

```text
Business Need
     ↓
Business Impact
     ↓
Criticality
     ↓
Recovery Requirement
     ↓
Continuity Strategy
     ↓
Control
     ↓
Testing
     ↓
Evidence
     ↓
Management Assurance
```

The BIA is therefore more than a questionnaire or spreadsheet. It is a **business-driven decision-making model that establishes which services matter most, what could happen if they fail, how quickly they must recover, and what level of resilience the organization should provide**.


