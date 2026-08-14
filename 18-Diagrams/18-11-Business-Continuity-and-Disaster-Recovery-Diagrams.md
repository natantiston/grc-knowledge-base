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


