# 18.20 Practical GRC Diagram Case Studies

## Part 1 – Building an ISO 27001 GRC Diagram Set

Building an **ISO 27001 GRC Diagram Set** involves translating the organization's Information Security Management System (ISMS), risk management process, controls, governance structure, and assurance activities into a coordinated collection of visual models.

The objective is not simply to create attractive diagrams. The objective is to create a **consistent visual representation of how ISO 27001 operates within the organization**.

A practical ISO 27001 diagram set should help different audiences understand:

* how the ISMS is governed;
* how information security risks are managed;
* how controls are selected and implemented;
* how evidence is generated;
* how controls are monitored and tested;
* how nonconformities are remediated;
* how management reviews the ISMS;
* how continual improvement operates.

The overall model is:

```text id="a1k8qz"
                    ISO 27001 ISMS
                          |
          +---------------+---------------+
          |               |               |
          v               v               v
      Governance        Risk           Controls
          |               |               |
          +---------------+---------------+
                          |
                          v
                       Evidence
                          |
                          v
                     Monitoring
                          |
                          v
                       Audit
                          |
                          v
                     Improvement
```

---

# 1. Why Build an ISO 27001 Diagram Set?

ISO 27001 contains many interconnected concepts.

A single diagram cannot adequately represent the entire ISMS.

Instead, organizations should develop a **diagram set**, where each diagram explains a particular aspect of the ISMS.

For example:

```text id="p4n7cx"
Diagram 1
ISMS Governance

Diagram 2
ISMS Context

Diagram 3
Risk Management

Diagram 4
Statement of Applicability

Diagram 5
Control Implementation

Diagram 6
Evidence Management

Diagram 7
Internal Audit

Diagram 8
Management Review

Diagram 9
Corrective Action

Diagram 10
Continual Improvement
```

Together, these diagrams provide a visual representation of the ISMS.

---

# 2. The ISO 27001 Diagram Architecture

A practical diagram set can be organized into several layers.

```text id="z6c2mw"
                 STRATEGIC LAYER
              Business Objectives
                       |
                       v
                ISMS Governance
                       |
                       v
                 ISMS Scope
                       |
                       ↓
                 RISK LAYER
              Risk Identification
                       |
                       v
                Risk Assessment
                       |
                       v
                Risk Treatment
                       |
                       ↓
                CONTROL LAYER
                 Control Selection
                       |
                       v
                 Control Design
                       |
                       v
               Control Operation
                       |
                       ↓
               ASSURANCE LAYER
                 Monitoring
                       |
                       v
                 Internal Audit
                       |
                       v
               Management Review
                       |
                       ↓
               IMPROVEMENT LAYER
              Corrective Action
                       |
                       v
                Continual Improvement
```

This layered approach makes the ISMS easier to explain to management, auditors, control owners, and employees.

---

# 3. Diagram 1 – ISO 27001 ISMS Governance

The first diagram should show who governs the ISMS.

```text id="q7v3bn"
                    BOARD / EXECUTIVE MANAGEMENT
                              |
                              v
                       ISMS GOVERNANCE
                              |
             +----------------+----------------+
             |                |                |
             v                v                v
        CISO / ISMS      Risk Management    Compliance
          Manager
             |
             v
       Control Owners
             |
             v
        Operational Teams
```

This diagram establishes accountability.

It should clearly distinguish:

* executive accountability;
* ISMS management;
* risk ownership;
* control ownership;
* operational responsibility;
* independent assurance.

---

# 4. Diagram 2 – ISMS Context

The organization should visualize the context in which its ISMS operates.

```text id="m8x4jp"
                 EXTERNAL CONTEXT
       Regulations | Threats | Technology
                       |
                       v
              +----------------+
              |  ORGANIZATION  |
              |                |
              |     ISMS       |
              +----------------+
                       |
       +---------------+---------------+
       |                               |
       v                               v
 INTERNAL CONTEXT                 INTERESTED PARTIES
 People | Processes              Customers
 Technology | Culture            Regulators
 Governance | Assets             Suppliers
```

The diagram should help explain the internal and external factors that influence information security.

---

# 5. Diagram 3 – ISMS Scope

The ISMS scope should be visually defined.

```text id="t6k2qr"
              ENTERPRISE
                  |
      +-----------+-----------+
      |                       |
      v                       v
   IN SCOPE                OUT OF SCOPE
      |
      +----------------------------+
      |                            |
      v                            v
Business Units                Technologies
Processes                    Locations
Applications                 Information Assets
```

The scope diagram is particularly useful during certification audits because it makes the boundaries of the ISMS easy to understand.

---

# 6. Diagram 4 – Interested Parties

A simple stakeholder model can show relevant interested parties.

```text id="r3m7vx"
                     REGULATORS
                         |
                         v
CUSTOMERS -----> ORGANIZATION <----- SUPPLIERS
                         |
                         v
                     EMPLOYEES
                         |
                         v
                     PARTNERS
                         |
                         v
                    SHAREHOLDERS
```

Each interested party may have information security requirements or expectations.

---

# 7. Diagram 5 – Information Security Risk Management

Risk management should be one of the central diagrams.

```text id="y9k4fw"
              IDENTIFY RISK
                    |
                    v
              ANALYZE RISK
                    |
                    v
              EVALUATE RISK
                    |
                    v
             TREAT THE RISK
                    |
          +---------+---------+
          |         |         |
          v         v         v
       Reduce     Avoid    Transfer
          |
          v
       Accept
          |
          v
        Monitor
          |
          +----------> REVIEW
```

This diagram connects risk identification to control selection and monitoring.

---

# 8. Diagram 6 – Inherent-to-Residual Risk

A second risk diagram can show the effect of controls.

```text id="c5q8mb"
                 INHERENT RISK
                      |
                      v
                Risk Treatment
                      |
                      v
                    Controls
                      |
                      v
              Control Effectiveness
                      |
                      v
                 RESIDUAL RISK
                      |
             +--------+--------+
             |                 |
             v                 v
       Within Appetite    Above Appetite
             |                 |
             v                 v
           Accept          Remediate
```

This is particularly useful for management reporting.

---

# 9. Diagram 7 – ISO 27001 Control Selection

The control selection process can be represented as:

```text id="n7w2kj"
Risk Assessment
      |
      v
Risk Treatment
      |
      v
Control Requirements
      |
      v
Applicable Controls
      |
      v
Statement of Applicability
      |
      v
Control Implementation
```

The diagram should show that control selection is driven by organizational risk and requirements rather than simply copying a checklist.

---

# 10. Diagram 8 – Statement of Applicability

The Statement of Applicability can be visualized as the bridge between risk treatment and controls.

```text id="v4c9zs"
             RISK TREATMENT
                   |
                   v
        CONTROL REQUIREMENTS
                   |
                   v
       +-----------------------+
       | STATEMENT OF          |
       | APPLICABILITY         |
       +-----------------------+
          |       |       |
          v       v       v
      Applicable Excluded Additional
       Controls  Controls  Controls
          |
          v
    Implementation
```

This helps explain why specific controls are included or excluded.

---

# 11. Diagram 9 – Control Implementation

Once controls are selected, the organization implements them.

```text id="h8r3mq"
Selected Control
      |
      v
Control Design
      |
      v
Control Owner
      |
      v
Implementation
      |
      v
Procedure
      |
      v
Operational Execution
      |
      v
Evidence
```

This connects the control framework to day-to-day operations.

---

# 12. Diagram 10 – Control Evidence

Evidence demonstrates that controls are operating.

```text id="x6p5cv"
                CONTROL
                   |
                   v
             CONTROL ACTIVITY
                   |
                   v
             SYSTEM / PROCESS
                   |
                   v
                 RECORD
                   |
                   v
                EVIDENCE
                   |
                   v
              VERIFICATION
```

Examples of evidence include:

* access review reports;
* vulnerability scan results;
* security incident records;
* training records;
* risk assessments;
* supplier assessments;
* backup test reports;
* policy approvals.

---

# 13. Diagram 11 – Control Monitoring

Controls should be monitored continuously or periodically.

```text id="w3m7nx"
                 CONTROL
                    |
                    v
                Monitoring
                    |
          +---------+---------+
          |                   |
          v                   v
       Effective          Exception
          |                   |
          v                   v
       Continue          Investigation
                              |
                              v
                          Remediation
```

This demonstrates that control operation is an ongoing process.

---

# 14. Diagram 12 – Internal Audit

The internal audit lifecycle can be included in the ISO 27001 diagram set.

```text id="q8f4zr"
             AUDIT PLANNING
                   |
                   v
              AUDIT SCOPE
                   |
                   v
              AUDIT TESTING
                   |
                   v
               FINDINGS
                   |
                   v
             AUDIT REPORT
                   |
                   v
             REMEDIATION
                   |
                   v
             FOLLOW-UP
```

The audit diagram should clearly distinguish independent assurance from operational control ownership.

---

# 15. Diagram 13 – Management Review

Management review is an important governance component.

```text id="m4v8qs"
              ISMS PERFORMANCE
                     |
                     v
                AUDIT RESULTS
                     |
                     v
               RISK STATUS
                     |
                     v
             SECURITY METRICS
                     |
                     v
             MANAGEMENT REVIEW
                     |
          +----------+----------+
          |          |          |
          v          v          v
       Decisions   Actions   Improvements
```

The diagram shows how management information leads to decisions.

---

# 16. Diagram 14 – Nonconformity and Corrective Action

A corrective action process can be represented as:

```text id="k6x2pj"
Nonconformity
      |
      v
Immediate Correction
      |
      v
Root Cause Analysis
      |
      v
Corrective Action
      |
      v
Implementation
      |
      v
Effectiveness Verification
      |
      v
Closure
```

This demonstrates that corrective action should address the underlying cause rather than simply the visible symptom.

---

# 17. Diagram 15 – Continual Improvement

The ISMS should operate as a continuous improvement cycle.

```text id="b8q5mz"
                    PLAN
                     |
                     v
                     DO
                     |
                     v
                   CHECK
                     |
                     v
                    ACT
                     |
                     v
               IMPROVEMENT
                     |
                     +------------+
                                  |
                                  v
                                  PLAN
```

The organization should continually improve the suitability, adequacy, and effectiveness of the ISMS.

---

# 18. Diagram 16 – ISO 27001 PDCA-Oriented View

A higher-level visualization can combine the ISMS lifecycle.

```text id="d7m4kc"
                  PLAN
                   |
       +-----------+-----------+
       |                       |
       v                       v
   Context                  Risk
       |                       |
       +-----------+-----------+
                   |
                   v
                 DO
                   |
                   v
             Controls
                   |
                   v
                CHECK
                   |
       +-----------+-----------+
       |                       |
       v                       v
   Monitoring                Audit
       |                       |
       +-----------+-----------+
                   |
                   v
                  ACT
                   |
                   v
              Improvement
```

This provides executives with a simplified understanding of the ISMS operating cycle.

---

# 19. Diagram 17 – ISO 27001 Evidence Architecture

A mature organization can visualize evidence management.

```text id="s9c3vx"
                 REQUIREMENT
                      |
                      v
                    CONTROL
                      |
                      v
                CONTROL ACTIVITY
                      |
                      v
                  EVIDENCE
                      |
          +-----------+-----------+
          |                       |
          v                       v
       Monitoring               Audit
          |                       |
          +-----------+-----------+
                      |
                      v
                 ASSURANCE
```

This demonstrates the relationship between controls and assurance.

---

# 20. Diagram 18 – ISO 27001 GRC Traceability

The complete traceability model can be represented as:

```text id="p5x8nr"
Business Objective
       |
       v
Information Security Risk
       |
       v
Requirement
       |
       v
Control Objective
       |
       v
ISO 27001 Control
       |
       v
Control Owner
       |
       v
Control Activity
       |
       v
Evidence
       |
       v
Testing
       |
       v
Finding
       |
       v
Corrective Action
       |
       v
Residual Risk
       |
       v
Management Review
       |
       v
Continual Improvement
```

This is one of the most valuable diagrams in the entire set because it connects governance, risk, compliance, controls, assurance, and improvement.

---

# 21. Diagram 19 – ISO 27001 GRC Operating Model

A broader operating model can combine the major functions.

```text id="j4n7cw"
                       EXECUTIVE MANAGEMENT
                              |
                              v
                       ISMS GOVERNANCE
                              |
        +---------------------+---------------------+
        |                     |                     |
        v                     v                     v
   Risk Management       Compliance             Security
        |                     |                     |
        +---------------------+---------------------+
                              |
                              v
                       CONTROL MANAGEMENT
                              |
                              v
                         OPERATIONS
                              |
                              v
                           EVIDENCE
                              |
                +-------------+-------------+
                |                           |
                v                           v
            MONITORING                     AUDIT
                |                           |
                +-------------+-------------+
                              |
                              v
                         FINDINGS
                              |
                              v
                        REMEDIATION
                              |
                              v
                       MANAGEMENT REVIEW
                              |
                              v
                     CONTINUAL IMPROVEMENT
```

This diagram can serve as an executive-level ISO 27001 GRC model.

---

# 22. Recommended ISO 27001 Diagram Set

For a practical project, the following diagram set provides strong coverage:

| #  | Diagram                    | Primary Purpose            |
| -- | -------------------------- | -------------------------- |
| 1  | ISMS Governance            | Accountability             |
| 2  | ISMS Context               | Organizational environment |
| 3  | ISMS Scope                 | Boundaries                 |
| 4  | Interested Parties         | Stakeholder requirements   |
| 5  | Risk Management            | Risk lifecycle             |
| 6  | Inherent-to-Residual Risk  | Risk treatment             |
| 7  | Control Selection          | Control determination      |
| 8  | Statement of Applicability | Applicability decisions    |
| 9  | Control Implementation     | Operationalization         |
| 10 | Control Evidence           | Evidence generation        |
| 11 | Control Monitoring         | Ongoing effectiveness      |
| 12 | Internal Audit             | Independent assurance      |
| 13 | Management Review          | Executive oversight        |
| 14 | Corrective Action          | Nonconformity management   |
| 15 | Continual Improvement      | ISMS improvement           |
| 16 | PDCA-Oriented ISMS         | Lifecycle overview         |
| 17 | Evidence Architecture      | Evidence traceability      |
| 18 | GRC Traceability           | End-to-end relationships   |
| 19 | GRC Operating Model        | Integrated executive view  |

---

# 23. Designing the Diagram Set as a System

The diagrams should not be created independently.

They should connect to one another.

For example:

```text id="c8m5rx"
ISMS Context
      |
      v
ISMS Scope
      |
      v
Risk Management
      |
      v
Risk Treatment
      |
      v
Control Selection
      |
      v
Statement of Applicability
      |
      v
Control Implementation
      |
      v
Evidence
      |
      v
Monitoring
      |
      v
Internal Audit
      |
      v
Findings
      |
      v
Corrective Action
      |
      v
Management Review
      |
      v
Continual Improvement
```

This creates a coherent visual story.

---

# 24. Diagram Consistency

All diagrams in the set should use consistent conventions.

For example:

```text id="r7v3kx"
Blue     = Governance
Green    = Risk
Orange   = Controls
Purple   = Assurance
Red      = Findings
Grey     = Supporting Information
```

The exact colors are less important than consistency.

Other conventions should also remain consistent:

* same terminology;
* same control IDs;
* same risk terminology;
* same directional flow;
* same symbols;
* same organizational roles.

---

# 25. Diagram Naming Convention

A professional diagram library can use standardized names.

For example:

```text id="f3q8mv"
ISO27001-01-ISMS-Governance
ISO27001-02-ISMS-Context
ISO27001-03-ISMS-Scope
ISO27001-04-Interested-Parties
ISO27001-05-Risk-Management
ISO27001-06-Risk-Treatment
ISO27001-07-Control-Selection
ISO27001-08-Statement-of-Applicability
ISO27001-09-Control-Implementation
ISO27001-10-Evidence-Architecture
ISO27001-11-Internal-Audit
ISO27001-12-Management-Review
ISO27001-13-Corrective-Action
ISO27001-14-Continual-Improvement
```

This makes the diagram repository easier to manage.

---

# 26. Diagram Version Control

The diagrams should be version-controlled.

For example:

```text id="n5c7bw"
Diagram ID: ISO27001-05
Version: 1.0
Owner: ISMS Manager
Approved By: CISO
Effective Date: 2026-01-01
Review Date: 2027-01-01
Status: Approved
```

Changes to the ISMS should trigger a review of affected diagrams.

---

# 27. Diagram-to-Document Traceability

Diagrams should connect to formal documentation.

```text id="k8x4pt"
Diagram
   |
   +----> Policy
   |
   +----> Procedure
   |
   +----> Risk Register
   |
   +----> Control Library
   |
   +----> Statement of Applicability
   |
   +----> Audit Program
```

This prevents diagrams from becoming disconnected presentation materials.

---

# 28. Diagram-to-Control Traceability

Each important diagram should identify the relevant controls where appropriate.

```text id="v2m6qr"
Risk Diagram
      |
      v
Risk Treatment
      |
      v
Control IDs
      |
      v
Control Library
```

This is particularly useful for auditors and GRC professionals.

---

# 29. Diagram-to-Evidence Traceability

For operational diagrams, evidence can also be connected.

```text id="h7k3mx"
Control
  |
  v
Control Activity
  |
  v
Evidence
  |
  v
Evidence Repository
```

This makes the diagram set useful during audit preparation.

---

# 30. Audience-Based Diagram Design

Different diagrams should target different audiences.

### Executive Management

Focus on:

* governance;
* major risks;
* control effectiveness;
* compliance status;
* residual risk.

### GRC Professionals

Focus on:

* requirements;
* controls;
* evidence;
* risk;
* testing;
* remediation.

### Control Owners

Focus on:

* responsibilities;
* procedures;
* evidence;
* monitoring;
* exceptions.

### Auditors

Focus on:

* scope;
* criteria;
* controls;
* evidence;
* testing;
* findings.

---

# 31. ISO 27001 Audit Preparation Diagram

A useful audit-readiness model is:

```text id="x6m4pv"
ISO 27001 Requirement
        |
        v
Control Mapping
        |
        v
Control Owner
        |
        v
Evidence Available?
        |
     +--+--+
     |     |
    Yes    No
     |     |
     v     v
   Ready  Gap
     |
     v
Internal Testing
     |
     v
Audit Readiness
```

This allows GRC teams to identify weaknesses before the certification or surveillance audit.

---

# 32. Certification Audit Visual Model

The certification audit can be represented as:

```text id="q8m5zr"
                 CERTIFICATION AUDIT
                         |
        +----------------+----------------+
        |                                 |
        v                                 v
     ISMS Review                    Control Review
        |                                 |
        v                                 v
    Documentation                     Evidence
        |                                 |
        +----------------+----------------+
                         |
                         v
                    Audit Findings
                         |
                         v
                    Certification
```

The exact audit structure depends on the certification body's audit methodology and applicable requirements.

---

# 33. ISO 27001 Continual Improvement Architecture

The final diagram should emphasize that certification is not the endpoint.

```text id="c4w8ny"
                  ISMS
                   |
                   v
               OPERATE
                   |
                   v
               MONITOR
                   |
                   v
                AUDIT
                   |
                   v
                REVIEW
                   |
                   v
              IMPROVEMENT
                   |
                   v
             UPDATED ISMS
                   |
                   +----------+
                              |
                              v
                            OPERATE
```

This reinforces the idea that an effective ISMS evolves with the organization's risks and environment.

---

# 34. Complete ISO 27001 Diagram Set Architecture

The complete visual architecture can be summarized as:

```text id="m7q2xc"
                    BUSINESS CONTEXT
                           |
                           v
                    ISMS GOVERNANCE
                           |
                           v
                      ISMS SCOPE
                           |
                           v
                 INTERESTED PARTIES
                           |
                           v
                    RISK MANAGEMENT
                           |
                           v
                    RISK TREATMENT
                           |
                           v
                  CONTROL SELECTION
                           |
                           v
               STATEMENT OF APPLICABILITY
                           |
                           v
                CONTROL IMPLEMENTATION
                           |
                           v
                       EVIDENCE
                           |
                           v
                      MONITORING
                           |
                           v
                    INTERNAL AUDIT
                           |
                           v
                       FINDINGS
                           |
                           v
                    CORRECTIVE ACTION
                           |
                           v
                  MANAGEMENT REVIEW
                           |
                           v
                 CONTINUAL IMPROVEMENT
                           |
                           +----------------+
                                            |
                                            v
                                      UPDATED ISMS
```

---

# 35. Practical Case Study – Enterprise Telecom Organization

Consider a large telecommunications organization implementing an ISO 27001 ISMS.

The organization may have:

* customer-facing digital services;
* mobile networks;
* cloud infrastructure;
* enterprise applications;
* data centers;
* identity systems;
* third-party suppliers;
* customer information;
* critical network infrastructure.

A simplified architecture might be:

```text id="y8n4ks"
                    TELECOM BUSINESS
                           |
                           v
                     ISMS SCOPE
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
   Network Systems     IT Systems       Customer Services
        |                  |                  |
        +------------------+------------------+
                           |
                           v
                    RISK ASSESSMENT
                           |
                           v
                  RISK TREATMENT PLAN
                           |
                           v
                   SECURITY CONTROLS
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
     Identity          Network            Data
     Security          Security          Protection
        |                  |                  |
        +------------------+------------------+
                           |
                           v
                       EVIDENCE
                           |
                           v
                    INTERNAL AUDIT
                           |
                           v
                  MANAGEMENT REVIEW
```

This demonstrates how the diagram set can be adapted to a real enterprise environment.

---

# 36. Practical Case Study – Cloud Migration

Suppose the organization is migrating applications to the cloud.

The diagram set can show:

```text id="k5r8zp"
Cloud Migration
      |
      v
New Information Assets
      |
      v
Risk Assessment
      |
      v
Security Requirements
      |
      v
Applicable Controls
      |
      v
Cloud Security Architecture
      |
      v
Implementation
      |
      v
Evidence
      |
      v
Control Testing
      |
      v
Residual Risk
```

This demonstrates how the ISMS integrates with business transformation projects.

---

# 37. Practical Case Study – Third-Party Service

Suppose a critical supplier provides a cloud service.

```text id="w4m7qc"
Critical Supplier
       |
       v
Third-Party Risk Assessment
       |
       v
Security Requirements
       |
       v
Contractual Controls
       |
       v
Supplier Evidence
       |
       v
Assessment
       |
       v
Monitoring
       |
       v
Risk Review
```

This connects third-party risk management to the ISO 27001 ISMS.

---

# 38. Practical Case Study – Security Incident

A security incident can flow through the ISMS diagram set.

```text id="j6q3mv"
Security Incident
       |
       v
Incident Response
       |
       v
Control Failure?
       |
       v
Risk Assessment
       |
       v
Corrective Action
       |
       v
Control Improvement
       |
       v
Management Review
```

This demonstrates how operational events can drive continual improvement.

---

# 39. Practical Case Study – Audit Finding

An audit finding can be traced through the complete system.

```text id="p8c4rx"
Audit Finding
     |
     v
Affected Control
     |
     v
Underlying Risk
     |
     v
Root Cause
     |
     v
Corrective Action
     |
     v
Evidence
     |
     v
Validation
     |
     v
Closure
     |
     v
Continual Improvement
```

This creates a clear audit trail.

---

# 40. Recommended Executive ISO 27001 Diagram

If management only wants one diagram, use the following high-level model:

```text id="v9m2sk"
                    BUSINESS OBJECTIVES
                            |
                            v
                     ISMS GOVERNANCE
                            |
                            v
                      RISK MANAGEMENT
                            |
                            v
                    CONTROL FRAMEWORK
                            |
                            v
                        OPERATIONS
                            |
                            v
                         EVIDENCE
                            |
                            v
                   MONITORING & AUDIT
                            |
                            v
                    MANAGEMENT REVIEW
                            |
                            v
                 CONTINUAL IMPROVEMENT
                            |
                            +------------+
                                         |
                                         v
                                   BUSINESS OBJECTIVES
```

This provides a concise executive representation of the entire ISMS.

---

# 41. Recommended GRC Professional Diagram

For a GRC professional, a more detailed model is preferable:

```text id="c7k5nw"
Business Objective
       |
       v
Risk
       |
       v
ISO Requirement
       |
       v
Control Objective
       |
       v
Control
       |
       v
Control Owner
       |
       v
Procedure
       |
       v
Evidence
       |
       v
Testing
       |
       v
Finding
       |
       v
Remediation
       |
       v
Residual Risk
       |
       v
Management Review
```

This provides operational traceability.

---

# 42. Diagram Governance

The diagram library itself should be governed.

A simple lifecycle is:

```text id="r5m8qx"
Create
  ↓
Review
  ↓
Approve
  ↓
Publish
  ↓
Use
  ↓
Monitor
  ↓
Update
  ↓
Approve Again
```

The diagram repository should therefore be treated as controlled GRC documentation.

---

# 43. Common Mistakes When Building ISO 27001 Diagrams

### Creating Diagrams Without a Purpose

Every diagram should answer a specific question.

### Overloading One Diagram

Trying to place the entire ISMS into one diagram usually reduces readability.

### Inconsistent Terminology

The terminology in diagrams should match the organization's policies and GRC system.

### Ignoring Risk

Control diagrams should connect back to information security risk.

### Ignoring Evidence

A control diagram should explain how control operation can be demonstrated.

### Ignoring Assurance

The diagram set should show monitoring, testing, and audit.

### No Continual Improvement

The ISMS should be represented as a continuous management system.

---

# 44. The ISO 27001 Diagram Set as a Visual Story

The complete diagram collection should tell a logical story:

```text id="n3x7kp"
1. WHY?
Business Context
      ↓
2. WHAT?
ISMS Scope
      ↓
3. WHAT CAN GO WRONG?
Risk
      ↓
4. WHAT DO WE DO?
Controls
      ↓
5. HOW DO WE PROVE IT?
Evidence
      ↓
6. DOES IT WORK?
Monitoring & Audit
      ↓
7. WHAT NEEDS FIXING?
Findings
      ↓
8. WHAT DID MANAGEMENT DECIDE?
Management Review
      ↓
9. HOW DO WE IMPROVE?
Continual Improvement
```

This is the most effective way to design a coherent ISO 27001 diagram library.

---

# 45. Final ISO 27001 GRC Diagram Set

The complete case-study architecture is:

```text id="q6v8mt"
                       ISO 27001 ISMS
                              |
                              v
                       ORGANIZATIONAL
                          CONTEXT
                              |
                              v
                         ISMS SCOPE
                              |
                              v
                      INTERESTED PARTIES
                              |
                              v
                       RISK MANAGEMENT
                              |
                              v
                        RISK TREATMENT
                              |
                              v
                     CONTROL SELECTION
                              |
                              v
               STATEMENT OF APPLICABILITY
                              |
                              v
                   CONTROL IMPLEMENTATION
                              |
                              v
                           EVIDENCE
                              |
                              v
                         MONITORING
                              |
                              v
                      INTERNAL AUDIT
                              |
                              v
                          FINDINGS
                              |
                              v
                      CORRECTIVE ACTION
                              |
                              v
                    MANAGEMENT REVIEW
                              |
                              v
                   CONTINUAL IMPROVEMENT
                              |
                              +----------------+
                                               |
                                               v
                                          UPDATED ISMS
```

The key lesson from this case study is that an ISO 27001 diagram set should not be viewed as a collection of isolated pictures. It should function as a **visual architecture of the ISMS**.

The strongest diagram set connects:

```text id="z5q9cw"
Context
   ↓
Scope
   ↓
Risk
   ↓
Requirements
   ↓
Controls
   ↓
Evidence
   ↓
Assurance
   ↓
Findings
   ↓
Remediation
   ↓
Residual Risk
   ↓
Management Review
   ↓
Continual Improvement
```

For a GRC professional, this approach demonstrates a deeper understanding of ISO 27001 than simply knowing individual clauses or controls. It demonstrates the ability to **translate the ISMS into a practical governance, risk, control, assurance, and decision-making architecture**.

# 18.20 Practical GRC Diagram Case Studies

## Part 2 – Building an Enterprise Risk Management Diagram Set

An **Enterprise Risk Management (ERM) Diagram Set** provides a visual representation of how an organization identifies, assesses, treats, monitors, reports, and governs risk across the enterprise.

The purpose is to show that risk management is not an isolated activity performed by a risk department. It is an integrated management process connecting:

* business objectives;
* enterprise risks;
* risk owners;
* risk appetite;
* risk assessment;
* risk treatment;
* controls;
* key risk indicators;
* monitoring;
* reporting;
* escalation;
* management decisions.

The overall ERM model is:

```text
Business Objectives
        |
        v
Risk Identification
        |
        v
Risk Assessment
        |
        v
Risk Treatment
        |
        v
Risk Monitoring
        |
        v
Risk Reporting
        |
        v
Management Decision
        |
        v
Continual Improvement
        |
        +--------------------> Business Objectives
```

---

# 1. Why Build an ERM Diagram Set?

Enterprise risk management can become difficult to understand when risks are maintained only in spreadsheets, registers, and reports.

A diagram set provides a visual representation of the entire risk architecture.

For example:

```text
                 ENTERPRISE
                     |
       +-------------+-------------+
       |             |             |
       v             v             v
   Strategic      Financial    Operational
     Risk           Risk          Risk
       |             |             |
       +-------------+-------------+
                     |
                     v
                Risk Register
                     |
                     v
              Risk Assessment
                     |
                     v
               Risk Treatment
                     |
                     v
                Risk Monitoring
                     |
                     v
               Executive Reporting
```

This allows executives and risk professionals to understand how individual risks fit into the enterprise risk environment.

---

# 2. The ERM Diagram Architecture

A practical ERM diagram set should cover several layers.

```text
STRATEGIC LAYER
Business Strategy
      |
      v
Risk Appetite
      |
      v
Risk Strategy

RISK LAYER
      |
      v
Risk Identification
      |
      v
Risk Assessment
      |
      v
Risk Treatment

CONTROL LAYER
      |
      v
Controls
      |
      v
Control Effectiveness

MONITORING LAYER
      |
      v
KRIs
      |
      v
Risk Monitoring

ASSURANCE LAYER
      |
      v
Risk Assurance
      |
      v
Internal Audit

REPORTING LAYER
      |
      v
Risk Dashboard
      |
      v
Management Decision
```

This layered architecture provides a foundation for the ERM diagram library.

---

# 3. Diagram 1 – Enterprise Risk Governance

The first diagram should explain who governs enterprise risk.

```text
                       BOARD
                         |
                         v
                RISK COMMITTEE
                         |
                         v
                EXECUTIVE MANAGEMENT
                         |
             +-----------+-----------+
             |           |           |
             v           v           v
        CRO / Risk    Business     Compliance
        Function       Units        Function
             |           |           |
             +-----------+-----------+
                         |
                         v
                    Risk Owners
                         |
                         v
                  Control Owners
```

The diagram should distinguish:

* board oversight;
* executive accountability;
* second-line risk management;
* business risk ownership;
* control ownership;
* independent assurance.

---

# 4. Diagram 2 – Enterprise Risk Management Lifecycle

The central ERM lifecycle can be represented as:

```text
                 IDENTIFY
                    |
                    v
                  ANALYZE
                    |
                    v
                 EVALUATE
                    |
                    v
                  TREAT
                    |
                    v
                 MONITOR
                    |
                    v
                 REPORT
                    |
                    v
                 REVIEW
                    |
                    +----------> IDENTIFY
```

The cycle should operate continuously rather than only during an annual risk assessment.

---

# 5. Diagram 3 – Business Objective-to-Risk Model

Risk should be connected to business objectives.

```text
Business Objective
       |
       v
Critical Success Factors
       |
       v
Potential Threats
       |
       v
Risk Events
       |
       v
Business Impact
```

For example:

```text
Business Objective:
Maintain reliable customer services
        |
        v
Threat:
Technology failure
        |
        v
Risk Event:
Critical platform outage
        |
        v
Impact:
Service disruption
Revenue loss
Customer dissatisfaction
Regulatory consequences
```

This ensures that enterprise risk remains connected to business strategy.

---

# 6. Diagram 4 – Risk Universe

A risk universe provides an enterprise-wide view.

```text
                       ENTERPRISE RISK
                             |
       +----------+----------+----------+----------+
       |          |          |          |          |
       v          v          v          v          v
   Strategic  Financial  Operational Compliance Technology
       |          |          |          |          |
       v          v          v          v          v
 Reputation    Credit     Process    Regulatory  Cybersecurity
 Market        Liquidity  People     Legal        Technology
 Competition   Treasury   Supplier   Privacy      Cloud
```

The categories should be adapted to the organization's own risk taxonomy.

---

# 7. Diagram 5 – Risk Identification Flow

A practical risk identification process can be represented as:

```text
Business Process
      |
      v
Assets / Objectives
      |
      v
Threats / Vulnerabilities
      |
      v
Potential Risk Event
      |
      v
Business Impact
      |
      v
Risk Statement
      |
      v
Risk Register
```

This creates a structured approach to identifying risks.

---

# 8. Diagram 6 – Risk Statement Model

A well-defined risk statement can be represented as:

```text
CAUSE
  |
  v
RISK EVENT
  |
  v
IMPACT
```

For example:

```text
Cause:
Insufficient privileged-access monitoring
        |
        v
Risk Event:
Unauthorized privileged activity
        |
        v
Impact:
Data compromise
Service disruption
Regulatory exposure
```

This structure prevents vague risk statements.

---

# 9. Diagram 7 – Risk Assessment Model

Risk assessment should consider likelihood and impact.

```text
                    RISK ASSESSMENT
                           |
              +------------+------------+
              |                         |
              v                         v
          Likelihood                  Impact
              |                         |
              +------------+------------+
                           |
                           v
                      Risk Rating
                           |
                           v
                    Risk Prioritization
```

A typical risk score can be based on:

```text
Risk Score = Likelihood × Impact
```

The actual methodology should be defined by the organization's risk framework.

---

# 10. Diagram 8 – Inherent Risk Model

Inherent risk represents exposure before considering controls.

```text
Threat
  |
  v
Vulnerability
  |
  v
Risk Event
  |
  v
Likelihood + Impact
  |
  v
INHERENT RISK
```

For example:

```text
Cloud Misconfiguration
        |
        v
Unauthorized Access
        |
        v
High Likelihood
+
High Impact
        |
        v
High Inherent Risk
```

---

# 11. Diagram 9 – Control Effectiveness

Controls reduce risk when they operate effectively.

```text
Inherent Risk
      |
      v
Existing Controls
      |
      v
Control Effectiveness
      |
      v
Residual Risk
```

A more detailed model is:

```text
                INHERENT RISK
                     |
                     v
              CONTROL DESIGN
                     |
                     v
             CONTROL OPERATION
                     |
                     v
            CONTROL EFFECTIVENESS
                     |
                     v
               RESIDUAL RISK
```

---

# 12. Diagram 10 – Risk Treatment

Risk treatment options can be represented as:

```text
                     RISK
                      |
                      v
                 RISK TREATMENT
                      |
       +--------------+--------------+
       |              |              |
       v              v              v
      Avoid         Reduce         Transfer
       |              |              |
       +--------------+--------------+
                      |
                      v
                   Accept
```

Treatment decisions should consider risk appetite, cost, business impact, and available controls.

---

# 13. Diagram 11 – Risk Treatment Decision Model

A more detailed decision model is:

```text
                   Identified Risk
                         |
                         v
                  Within Appetite?
                    /          \
                  Yes           No
                   |             |
                   v             v
                Accept       Treatment
                                 |
                +----------------+----------------+
                |                |                |
                v                v                v
              Reduce          Transfer          Avoid
                |
                v
          Residual Risk
                |
                v
        Within Risk Appetite?
                |
             +--+--+
             |     |
            Yes    No
             |     |
             v     v
           Accept Escalate
```

---

# 14. Diagram 12 – Risk Acceptance

Risk acceptance should be governed formally.

```text
Risk Identified
      |
      v
Risk Assessment
      |
      v
Residual Risk
      |
      v
Compare With Risk Appetite
      |
      v
Acceptance Required?
      |
      v
Risk Owner
      |
      v
Authorized Approver
      |
      v
Acceptance Decision
      |
      v
Review Date
```

Risk acceptance should have an explicit owner and approval authority.

---

# 15. Diagram 13 – Risk Escalation

Risks exceeding defined thresholds should be escalated.

```text
Risk Identified
      |
      v
Risk Rating
      |
      v
Threshold Check
      |
   +--+--+
   |     |
Within   Above
Threshold Threshold
   |        |
   v        v
Monitor   Escalate
             |
             v
        Senior Management
             |
             v
         Risk Committee
             |
             v
             Board
```

The exact escalation path depends on organizational governance.

---

# 16. Diagram 14 – Risk Ownership Model

Every material risk should have an accountable owner.

```text
                   RISK
                    |
                    v
               Risk Owner
                    |
        +-----------+-----------+
        |                       |
        v                       v
  Treatment Owner         Control Owners
        |                       |
        v                       v
 Treatment Plan             Controls
```

The risk owner remains accountable for the risk even when multiple control owners support its treatment.

---

# 17. Diagram 15 – Risk Register Architecture

A risk register can be represented visually.

```text
                      RISK REGISTER
                            |
       +--------------------+--------------------+
       |                    |                    |
       v                    v                    v
   Risk ID              Risk Owner           Category
       |                    |                    |
       v                    v                    v
 Risk Statement         Treatment            Rating
       |                    |                    |
       +--------------------+--------------------+
                            |
                            v
                      Residual Risk
```

A mature risk register should provide traceability to supporting assessments, controls, actions, and evidence.

---

# 18. Diagram 16 – Risk-to-Control Traceability

Risk and control management should be connected.

```text
Risk
 |
 v
Risk Treatment
 |
 v
Control Objective
 |
 v
Control
 |
 v
Control Owner
 |
 v
Evidence
 |
 v
Control Testing
 |
 v
Residual Risk
```

This ensures that controls are connected to actual risks rather than maintained as isolated compliance activities.

---

# 19. Diagram 17 – Risk-to-KRI Model

Key Risk Indicators help monitor changing exposure.

```text
                    RISK
                     |
                     v
              Risk Driver
                     |
                     v
                    KRI
                     |
                     v
                 Threshold
                     |
          +----------+----------+
          |                     |
          v                     v
       Normal                 Breach
          |                     |
          v                     v
       Monitor              Escalate
```

For example:

```text
Risk:
Third-party service disruption

KRI:
Number of critical supplier outages

Threshold:
> 2 incidents per quarter

Threshold Breach:
Escalation to management
```

---

# 20. Diagram 18 – KRI Monitoring

A continuous KRI process can be represented as:

```text
KRI Definition
      |
      v
Data Collection
      |
      v
KRI Calculation
      |
      v
Threshold Comparison
      |
      v
Trend Analysis
      |
      v
Risk Assessment
      |
      v
Escalation / Action
```

This connects risk measurement to management action.

---

# 21. Diagram 19 – Risk Dashboard

An executive risk dashboard may contain:

```text
+--------------------------------------+
|          ENTERPRISE RISK             |
+--------------------------------------+
| Critical Risks             6         |
| High Risks                18         |
| Risks Above Appetite       4         |
| Overdue Treatments         7         |
| KRI Breaches               9         |
| Emerging Risks             5         |
+--------------------------------------+
```

The dashboard should focus on information required for decision-making rather than simply displaying large quantities of risk data.

---

# 22. Diagram 20 – Risk Heat Map

A standard risk heat map can provide a visual comparison of risks.

```text
                 IMPACT
                   ↑
            High   |  ● R03
                   |        ● R07
                   |
          Medium   |     ● R05
                   | ● R09
                   |
             Low   | ● R11
                   +--------------------→
                     Low   Med.   High
                         LIKELIHOOD
```

The actual scoring methodology and thresholds should be defined by the organization's approved risk methodology.

---

# 23. Diagram 21 – Emerging Risk Model

ERM should also address emerging risks.

```text
Weak Signal
     |
     v
Emerging Risk
     |
     v
Monitoring
     |
     v
Scenario Analysis
     |
     v
Potential Impact
     |
     v
Risk Assessment
     |
     v
Treatment / Preparedness
```

Emerging risks may involve:

* new technologies;
* geopolitical changes;
* regulatory developments;
* climate-related events;
* supply-chain disruption;
* new cyber threats.

---

# 24. Diagram 22 – Scenario Analysis

Scenario analysis helps organizations understand potential future impacts.

```text
                    RISK SCENARIO
                          |
              +-----------+-----------+
              |           |           |
              v           v           v
           Best Case   Expected    Worst Case
              |           |           |
              +-----------+-----------+
                          |
                          v
                     Business Impact
                          |
                          v
                    Response Options
```

This can be used for strategic and operational risk planning.

---

# 25. Diagram 23 – Risk Interdependency Model

Enterprise risks rarely operate independently.

```text
               Cyber Risk
                  |
                  v
             Technology Risk
              /          \
             v            v
     Operational Risk   Data Risk
             |            |
             +-----+------+
                   |
                   v
             Financial Risk
                   |
                   v
            Reputational Risk
```

This illustrates why enterprise risk management should consider relationships between risks.

---

# 26. Diagram 24 – Risk Aggregation

Multiple risks may contribute to an enterprise-level exposure.

```text
Strategic Risk -----+
Financial Risk -----+
Cyber Risk ---------+----> Enterprise Risk Exposure
Operational Risk ---+
Third-Party Risk ---+
Compliance Risk ----+
```

This provides a bridge between individual risk assessments and executive risk reporting.

---

# 27. Diagram 25 – Risk Appetite Architecture

Risk appetite provides boundaries for decision-making.

```text
                   BOARD
                     |
                     v
                Risk Appetite
                     |
          +----------+----------+
          |                     |
          v                     v
    Risk Tolerance        Risk Capacity
          |                     |
          +----------+----------+
                     |
                     v
               Risk Thresholds
                     |
                     v
              Business Decisions
```

Risk appetite should be translated into measurable thresholds wherever practical.

---

# 28. Diagram 26 – Risk Appetite to Risk Limit

A more operational model is:

```text
Risk Appetite
      |
      v
Risk Tolerance
      |
      v
Risk Limits
      |
      v
KRI Thresholds
      |
      v
Monitoring
      |
      v
Escalation
```

This converts high-level governance into operational risk management.

---

# 29. Diagram 27 – Risk Reporting Flow

Risk information should move from operational levels toward management.

```text
Operational Risk Data
        |
        v
Risk Owners
        |
        v
Business Unit Risk
        |
        v
Enterprise Risk Function
        |
        v
Executive Management
        |
        v
Risk Committee
        |
        v
Board
```

Reporting should become more aggregated as it moves upward.

---

# 30. Diagram 28 – Risk Information Flow

A more complete information architecture is:

```text
Risk Events
    |
    v
Operational Data
    |
    v
Risk Indicators
    |
    v
Risk Assessments
    |
    v
Risk Register
    |
    v
Risk Dashboard
    |
    v
Management Decision
```

This connects operational data with executive decision-making.

---

# 31. Diagram 29 – Risk Assurance Model

Assurance can be integrated into ERM.

```text
                 RISK MANAGEMENT
                       |
          +------------+------------+
          |            |            |
          v            v            v
      First Line    Second Line   Third Line
      Controls      Oversight      Internal Audit
          |            |            |
          +------------+------------+
                       |
                       v
                 Risk Assurance
                       |
                       v
                     Board
```

This complements the Three Lines model discussed earlier in Chapter 18.

---

# 32. Diagram 30 – Risk-to-Audit Traceability

Audit planning should consider enterprise risk.

```text
Enterprise Risk
      |
      v
Risk Rating
      |
      v
Audit Universe
      |
      v
Audit Prioritization
      |
      v
Audit Plan
      |
      v
Audit Testing
      |
      v
Findings
```

This supports a risk-based internal audit program.

---

# 33. Diagram 31 – Risk-to-Compliance Traceability

Compliance risk can be connected to enterprise risk.

```text
Regulatory Requirement
        |
        v
Compliance Obligation
        |
        v
Compliance Risk
        |
        v
Control
        |
        v
Assessment
        |
        v
Compliance Status
        |
        v
Enterprise Risk
```

This prevents compliance risks from becoming isolated within a compliance department.

---

# 34. Diagram 32 – Risk-to-Project Traceability

Projects can introduce new risks.

```text
Business Project
      |
      v
Project Objectives
      |
      v
Project Risks
      |
      v
Risk Assessment
      |
      v
Treatment Actions
      |
      v
Project Controls
      |
      v
Residual Risk
      |
      v
Project Decision
```

This is particularly important for major transformation programs.

---

# 35. Diagram 33 – Third-Party Risk Integration

Third-party risks can be incorporated into ERM.

```text
Supplier
   |
   v
Supplier Risk
   |
   v
Risk Assessment
   |
   v
Contractual Controls
   |
   v
Supplier Monitoring
   |
   v
Residual Supplier Risk
   |
   v
Enterprise Risk Register
```

This provides visibility into risks originating outside the organization.

---

# 36. Diagram 34 – Cybersecurity Risk Integration

Cybersecurity risks should feed into enterprise risk management.

```text
Threat
  |
  v
Vulnerability
  |
  v
Cyber Risk
  |
  v
Risk Assessment
  |
  v
Security Controls
  |
  v
Residual Cyber Risk
  |
  v
Enterprise Risk Register
  |
  v
Executive Reporting
```

This demonstrates how cybersecurity risk becomes a business risk rather than remaining purely technical.

---

# 37. Diagram 35 – Risk Escalation and Decision Cycle

A mature ERM model includes escalation.

```text
Risk Monitoring
      |
      v
Threshold Breach?
    /       \
  No         Yes
  |           |
  v           v
Continue    Escalate
Monitoring     |
               v
         Risk Owner Review
               |
               v
        Executive Review
               |
               v
        Management Decision
               |
               v
          Risk Treatment
               |
               v
            Monitoring
```

This creates a closed-loop risk management process.

---

# 38. Diagram 36 – Risk Event to Lessons Learned

Risk events should improve the organization's risk management capability.

```text
Risk Event
    |
    v
Incident / Loss
    |
    v
Investigation
    |
    v
Root Cause
    |
    v
Risk Assessment Update
    |
    v
Control Improvement
    |
    v
Risk Register Update
    |
    v
Lessons Learned
```

This converts actual events into organizational learning.

---

# 39. Diagram 37 – ERM Continual Improvement

The complete ERM improvement cycle is:

```text
Identify
   |
   v
Assess
   |
   v
Treat
   |
   v
Monitor
   |
   v
Report
   |
   v
Review
   |
   v
Improve
   |
   +---------> Identify
```

The organization should continually refine its risk identification, assessment criteria, controls, monitoring, and reporting.

---

# 40. Diagram 38 – Integrated Enterprise Risk Model

A comprehensive model can connect the major components.

```text
                    BUSINESS STRATEGY
                           |
                           v
                    RISK APPETITE
                           |
                           v
                    RISK UNIVERSE
                           |
                           v
                  RISK IDENTIFICATION
                           |
                           v
                    RISK ASSESSMENT
                           |
                           v
                    RISK PRIORITIZATION
                           |
                           v
                     RISK TREATMENT
                           |
                 +---------+---------+
                 |                   |
                 v                   v
              Controls           Transfer
                 |                   |
                 v                   |
             Monitoring              |
                 |                   |
                 +---------+---------+
                           |
                           v
                     RESIDUAL RISK
                           |
                           v
                    RISK REPORTING
                           |
                           v
                 MANAGEMENT DECISION
                           |
                           v
                    RISK REVIEW
                           |
                           +---------> Risk Identification
```

---

# 41. Recommended ERM Diagram Set

A practical enterprise risk diagram library could contain:

| #  | Diagram                          | Primary Purpose          |
| -- | -------------------------------- | ------------------------ |
| 1  | Enterprise Risk Governance       | Governance               |
| 2  | ERM Lifecycle                    | Risk management process  |
| 3  | Business Objective-to-Risk       | Strategic alignment      |
| 4  | Risk Universe                    | Risk taxonomy            |
| 5  | Risk Identification              | Risk discovery           |
| 6  | Risk Statement                   | Risk definition          |
| 7  | Risk Assessment                  | Risk evaluation          |
| 8  | Inherent Risk                    | Initial exposure         |
| 9  | Control Effectiveness            | Risk reduction           |
| 10 | Risk Treatment                   | Treatment options        |
| 11 | Treatment Decision               | Treatment selection      |
| 12 | Risk Acceptance                  | Acceptance governance    |
| 13 | Risk Escalation                  | Escalation               |
| 14 | Risk Ownership                   | Accountability           |
| 15 | Risk Register                    | Risk data                |
| 16 | Risk-to-Control Traceability     | Control alignment        |
| 17 | Risk-to-KRI                      | Monitoring               |
| 18 | KRI Monitoring                   | Threshold management     |
| 19 | Risk Dashboard                   | Executive reporting      |
| 20 | Risk Heat Map                    | Risk prioritization      |
| 21 | Emerging Risk                    | Future exposure          |
| 22 | Scenario Analysis                | Forward-looking analysis |
| 23 | Risk Interdependency             | Connected risks          |
| 24 | Risk Aggregation                 | Enterprise exposure      |
| 25 | Risk Appetite                    | Governance               |
| 26 | Risk Limits                      | Operational thresholds   |
| 27 | Risk Reporting                   | Information flow         |
| 28 | Risk Information Architecture    | Data flow                |
| 29 | Risk Assurance                   | Three Lines              |
| 30 | Risk-to-Audit                    | Audit prioritization     |
| 31 | Risk-to-Compliance               | Regulatory integration   |
| 32 | Risk-to-Project                  | Project risk             |
| 33 | Third-Party Risk                 | Supplier exposure        |
| 34 | Cybersecurity Risk               | Cyber risk integration   |
| 35 | Risk Escalation Cycle            | Decision-making          |
| 36 | Risk Event-to-Lessons Learned    | Organizational learning  |
| 37 | ERM Continual Improvement        | Improvement              |
| 38 | Integrated Enterprise Risk Model | Executive overview       |

---

# 42. Building the Diagram Set in Phases

An organization does not need to build all diagrams simultaneously.

A practical implementation can use four phases.

### Phase 1 – Foundation

```text
Risk Governance
      ↓
Risk Universe
      ↓
Risk Appetite
      ↓
ERM Lifecycle
```

### Phase 2 – Risk Management

```text
Risk Identification
      ↓
Risk Assessment
      ↓
Risk Treatment
      ↓
Risk Acceptance
```

### Phase 3 – Monitoring and Assurance

```text
Risk Monitoring
      ↓
KRI
      ↓
Risk Dashboard
      ↓
Risk Assurance
      ↓
Audit
```

### Phase 4 – Integration

```text
Risk
 ↓
Compliance
 ↓
Controls
 ↓
Third Parties
 ↓
Cybersecurity
 ↓
Projects
 ↓
Enterprise Reporting
```

---

# 43. Practical Case Study – Telecommunications Company

Consider a large telecommunications organization.

Its enterprise risk universe could include:

```text
                     TELECOM ENTERPRISE
                             |
       +----------+----------+----------+----------+
       |          |          |          |          |
       v          v          v          v          v
    Network     Cyber      Financial  Regulatory  Supplier
     Risk       Risk         Risk       Risk       Risk
       |          |          |          |          |
       +----------+----------+----------+----------+
                             |
                             v
                       Risk Register
                             |
                             v
                       Risk Assessment
                             |
                             v
                       Risk Treatment
                             |
                             v
                     Executive Dashboard
```

This allows different risk categories to be managed under one enterprise framework.

---

# 44. Practical Case Study – Cybersecurity Risk

Consider a critical customer platform.

```text
Customer Platform
       |
       v
Critical Asset
       |
       v
Threats
       |
       v
Vulnerabilities
       |
       v
Cybersecurity Risk
       |
       v
Security Controls
       |
       v
Control Effectiveness
       |
       v
Residual Cyber Risk
       |
       v
Enterprise Risk Register
```

The cybersecurity team therefore contributes directly to enterprise risk management.

---

# 45. Practical Case Study – Cloud Transformation

A cloud transformation project may introduce several risks.

```text
Cloud Transformation
        |
        +--------> Security Risk
        |
        +--------> Privacy Risk
        |
        +--------> Availability Risk
        |
        +--------> Supplier Risk
        |
        +--------> Compliance Risk
        |
        +--------> Financial Risk
```

These risks should be assessed individually and then considered collectively at the enterprise level.

---

# 46. Practical Case Study – Regulatory Change

A regulatory change can enter the ERM process.

```text
New Regulation
      |
      v
Compliance Assessment
      |
      v
New / Changed Risk
      |
      v
Risk Assessment
      |
      v
Control Changes
      |
      v
Residual Risk
      |
      v
Management Decision
```

This demonstrates how compliance developments can affect enterprise risk.

---

# 47. Practical Case Study – Major Supplier Failure

Suppose a critical supplier experiences a major outage.

```text
Supplier Failure
      |
      v
Service Disruption
      |
      v
Business Impact
      |
      v
Risk Event
      |
      v
Risk Assessment
      |
      v
Incident Response
      |
      v
Supplier Remediation
      |
      v
Residual Risk
      |
      v
Management Review
```

The event should feed lessons learned back into the supplier risk process.

---

# 48. Executive ERM Diagram

If executives require one simple diagram, use:

```text
                    BUSINESS STRATEGY
                           |
                           v
                     RISK APPETITE
                           |
                           v
                    ENTERPRISE RISKS
                           |
                           v
                    RISK ASSESSMENT
                           |
                           v
                    RISK TREATMENT
                           |
                           v
                  RESIDUAL RISK
                           |
                           v
                    RISK MONITORING
                           |
                           v
                    EXECUTIVE REPORTING
                           |
                           v
                 MANAGEMENT DECISIONS
                           |
                           v
                   CONTINUAL REVIEW
```

This is the preferred high-level executive representation.

---

# 49. GRC Professional ERM Diagram

For a GRC professional, a more detailed model is preferable:

```text
Business Objective
       |
       v
Risk Appetite
       |
       v
Risk Universe
       |
       v
Risk Identification
       |
       v
Risk Assessment
       |
       v
Inherent Risk
       |
       v
Risk Treatment
       |
       v
Controls
       |
       v
Control Effectiveness
       |
       v
Residual Risk
       |
       v
KRI Monitoring
       |
       v
Risk Reporting
       |
       v
Management Decision
       |
       v
Risk Review
```

---

# 50. ERM Diagram Governance

The diagram library itself should be controlled.

A diagram should contain metadata such as:

```text
Diagram ID: ERM-001
Title: Enterprise Risk Management Lifecycle
Owner: Enterprise Risk Management
Approved By: Chief Risk Officer
Version: 1.0
Status: Approved
Effective Date: 2026-01-01
Review Date: 2027-01-01
```

This is particularly important when diagrams are used as formal governance documentation.

---

# 51. Common ERM Diagram Mistakes

### Treating Risk as an Annual Activity

Risk management should be continuous.

### Focusing Only on Risk Registers

The register is only one component of ERM.

### No Connection to Business Objectives

Risk should explain why it matters to the organization.

### No Risk Appetite

Management needs defined boundaries for decision-making.

### No Risk Ownership

Every material risk needs accountable ownership.

### No KRI Monitoring

Static risk assessments may become outdated.

### No Risk Interdependency

Risks can influence each other.

### No Escalation Path

Material risks must reach the appropriate decision-makers.

### No Connection to Controls

Risk treatment should be connected to actual control mechanisms.

---

# 52. The ERM Visual Story

The complete ERM diagram set should tell a logical story:

```text
WHY?
Business Strategy
      ↓
HOW MUCH RISK CAN WE TAKE?
Risk Appetite
      ↓
WHAT CAN GO WRONG?
Risk Identification
      ↓
HOW BAD IS IT?
Risk Assessment
      ↓
WHAT SHOULD WE DO?
Risk Treatment
      ↓
WHO IS RESPONSIBLE?
Risk Ownership
      ↓
IS THE RISK CHANGING?
KRI Monitoring
      ↓
IS IT WITHIN APPETITE?
Risk Reporting
      ↓
WHAT SHOULD MANAGEMENT DECIDE?
Risk Governance
      ↓
HOW DO WE IMPROVE?
Continual Improvement
```

---

# 53. Final Enterprise Risk Management Diagram Set

The complete ERM architecture can be summarized as:

```text
                       BUSINESS STRATEGY
                              |
                              v
                        RISK APPETITE
                              |
                              v
                         RISK UNIVERSE
                              |
                              v
                    RISK IDENTIFICATION
                              |
                              v
                      RISK ASSESSMENT
                              |
                              v
                       INHERENT RISK
                              |
                              v
                       RISK TREATMENT
                              |
                    +---------+---------+
                    |                   |
                    v                   v
                 CONTROLS           TRANSFER
                    |
                    v
             CONTROL EFFECTIVENESS
                    |
                    v
                 RESIDUAL RISK
                    |
                    v
                 KRI MONITORING
                    |
                    v
                 RISK REPORTING
                    |
                    v
              MANAGEMENT DECISION
                    |
                    v
                RISK REVIEW
                    |
                    v
             CONTINUAL IMPROVEMENT
                    |
                    +--------------------+
                                         |
                                         v
                                   BUSINESS STRATEGY
```

The central lesson is that an ERM diagram set should demonstrate that **risk management is a continuous decision-making system rather than simply a risk register**.

A mature ERM visual architecture connects:

```text
Strategy
   ↓
Risk Appetite
   ↓
Risk
   ↓
Assessment
   ↓
Treatment
   ↓
Controls
   ↓
Residual Risk
   ↓
KRI
   ↓
Reporting
   ↓
Management Decision
   ↓
Continuous Improvement
```

For a GRC professional, this diagram set demonstrates the ability to translate enterprise risk management into a **structured governance architecture that connects strategic objectives, risk ownership, controls, monitoring, assurance, and executive decision-making**.


# 18.20 Practical GRC Diagram Case Studies

## Part 3 – Building a Cybersecurity Compliance Architecture Diagram

A **Cybersecurity Compliance Architecture Diagram** provides a visual representation of how regulatory requirements, cybersecurity frameworks, policies, controls, technology, evidence, monitoring, and assurance connect across an organization.

The purpose is not simply to show a list of regulations or security controls. A mature compliance architecture should demonstrate **traceability from external obligations to business requirements, controls, implementation, evidence, testing, findings, remediation, and management reporting**.

The fundamental model is:

```text
Regulations / Standards
          |
          v
Compliance Obligations
          |
          v
Cybersecurity Requirements
          |
          v
Policies / Control Objectives
          |
          v
Security Controls
          |
          v
Technology / Processes
          |
          v
Evidence
          |
          v
Testing / Assessment
          |
          v
Findings
          |
          v
Remediation
          |
          v
Compliance Reporting
```

---

# 1. Why Build a Cybersecurity Compliance Architecture Diagram?

Cybersecurity compliance often involves multiple frameworks, regulations, contractual requirements, and internal policies.

For example, an organization may need to manage:

* ISO 27001;
* NIST Cybersecurity Framework;
* NIST SP 800-53;
* GDPR;
* NIS2;
* DORA;
* PCI DSS;
* SOC 2;
* customer security requirements;
* contractual obligations;
* internal cybersecurity policies.

Without an architecture model, these requirements can become fragmented.

A compliance architecture connects them:

```text
                    External Requirements
                           |
       +-------------------+-------------------+
       |                   |                   |
       v                   v                   v
   Regulations         Standards          Contracts
       |                   |                   |
       +-------------------+-------------------+
                           |
                           v
                  Compliance Obligations
                           |
                           v
                    Control Framework
                           |
                           v
                    Security Controls
                           |
                           v
                  Evidence & Monitoring
                           |
                           v
                    Assurance & Audit
```

---

# 2. The Seven Layers of Compliance Architecture

A practical architecture can be organized into seven layers.

```text
+------------------------------------------------+
| 1. REGULATORY / EXTERNAL REQUIREMENTS          |
+------------------------------------------------+
| 2. COMPLIANCE OBLIGATIONS                      |
+------------------------------------------------+
| 3. POLICIES / CONTROL OBJECTIVES              |
+------------------------------------------------+
| 4. SECURITY CONTROLS                           |
+------------------------------------------------+
| 5. TECHNOLOGY / PROCESSES                      |
+------------------------------------------------+
| 6. EVIDENCE / ASSURANCE                        |
+------------------------------------------------+
| 7. REPORTING / GOVERNANCE                      |
+------------------------------------------------+
```

Each layer should have traceability to the layer above and below it.

---

# 3. Diagram 1 – Regulatory-to-Control Architecture

The most important compliance diagram is:

```text
Regulation
    |
    v
Regulatory Requirement
    |
    v
Compliance Obligation
    |
    v
Control Objective
    |
    v
Security Control
    |
    v
Control Implementation
    |
    v
Evidence
    |
    v
Testing
    |
    v
Compliance Status
```

This creates a complete compliance chain.

---

# 4. Diagram 2 – Multi-Framework Compliance Model

Organizations often operate multiple frameworks.

```text
                  Enterprise Compliance
                         |
       +-----------------+-----------------+
       |                 |                 |
       v                 v                 v
   ISO 27001           NIST              GDPR
       |                 |                 |
       +-----------------+-----------------+
                         |
                         v
                  Common Control Set
                         |
       +-----------------+-----------------+
       |                 |                 |
       v                 v                 v
    Policies          Controls          Evidence
```

The objective is to avoid implementing completely separate controls for every framework.

---

# 5. Diagram 3 – Compliance Framework Crosswalk

A crosswalk connects requirements from different frameworks.

```text
ISO 27001
    |
    +------+
           |
NIST CSF --+----> Common Control
           |
GDPR ------+
           |
NIS2 ------+
           |
DORA ------+
```

For example, several frameworks may require effective access management.

Rather than creating five independent control processes, the organization can establish a common access-control capability and map it to multiple requirements.

---

# 6. Diagram 4 – Common Control Architecture

A common control can support multiple compliance requirements.

```text
ISO 27001 Requirement ----+
                          |
NIST Requirement ---------+
                          |
GDPR Requirement ---------+----> Access Control
                          |
NIS2 Requirement ---------+
                          |
Contract Requirement -----+
```

The control can then generate common evidence.

```text
Access Control
      |
      +----> IAM Configuration
      |
      +----> Access Reviews
      |
      +----> Privileged Access Reports
      |
      +----> Joiner/Mover/Leaver Records
```

This reduces duplication.

---

# 7. Diagram 5 – Compliance Obligation Lifecycle

Compliance obligations should be managed throughout their lifecycle.

```text
Identify Requirement
        |
        v
Interpret Requirement
        |
        v
Determine Applicability
        |
        v
Assign Owner
        |
        v
Map to Controls
        |
        v
Implement
        |
        v
Collect Evidence
        |
        v
Assess Compliance
        |
        v
Remediate Gaps
        |
        v
Monitor Changes
```

This creates a continuous compliance process.

---

# 8. Diagram 6 – Applicability Assessment

Not every requirement applies equally to every organization.

```text
New Requirement
       |
       v
Applicability Assessment
       |
       v
+------+------+
|             |
Applicable   Not Applicable
|             |
v             v
Control      Document
Implementation  Rationale
```

A documented rationale is important when an organization determines that a requirement is not applicable.

---

# 9. Diagram 7 – Regulatory Change Management

Compliance architecture should account for regulatory changes.

```text
Regulatory Change
       |
       v
Regulatory Monitoring
       |
       v
Impact Assessment
       |
       v
Affected Business Areas
       |
       v
Affected Controls
       |
       v
Gap Assessment
       |
       v
Remediation Plan
       |
       v
Implementation
       |
       v
Validation
```

This creates a connection between regulatory intelligence and cybersecurity controls.

---

# 10. Diagram 8 – Requirement-to-Control Traceability

A detailed traceability model can be represented as:

```text
Requirement ID
      |
      v
Requirement Statement
      |
      v
Control Objective
      |
      v
Control ID
      |
      v
Control Procedure
      |
      v
Control Owner
      |
      v
Evidence
      |
      v
Testing Result
```

This is one of the most important diagrams for a GRC professional.

---

# 11. Diagram 9 – Control Implementation Architecture

A control should not exist only as a statement in a policy.

```text
Control Objective
       |
       v
Control Requirement
       |
       v
Control Procedure
       |
       v
People + Process + Technology
       |
       v
Control Operation
       |
       v
Evidence
       |
       v
Control Testing
```

This demonstrates the difference between **documented control design** and **operational control implementation**.

---

# 12. Diagram 10 – Cybersecurity Policy Hierarchy

A compliance architecture should connect policies to controls.

```text
Enterprise Security Policy
          |
          v
Security Standards
          |
          v
Security Procedures
          |
          v
Technical Standards
          |
          v
Operational Procedures
          |
          v
Security Controls
```

For example:

```text
Access Control Policy
        |
        v
Password Standard
        |
        v
Privileged Access Procedure
        |
        v
IAM Configuration
        |
        v
Access Review Evidence
```

---

# 13. Diagram 11 – Compliance-to-Technology Architecture

Compliance requirements ultimately need to be implemented through business processes and technology.

```text
Compliance Requirement
          |
          v
Control Objective
          |
          v
Security Control
          |
          v
Security Technology
          |
     +----+----+----+
     |    |    |    |
     v    v    v    v
    IAM  SIEM  EDR  DLP
```

The architecture should show how technical capabilities support compliance objectives.

---

# 14. Diagram 12 – Compliance Evidence Architecture

Evidence should be connected to controls.

```text
Security Control
       |
       v
Evidence Requirement
       |
       v
Evidence Source
       |
       v
Evidence Collection
       |
       v
Evidence Validation
       |
       v
Evidence Repository
       |
       v
Audit / Assessment
```

Possible evidence sources include:

* IAM systems;
* SIEM platforms;
* vulnerability scanners;
* endpoint platforms;
* cloud platforms;
* ticketing systems;
* HR systems;
* configuration-management systems;
* vendor-management platforms.

---

# 15. Diagram 13 – Automated Evidence Collection

A mature GRC environment can automate evidence collection.

```text
Security Platform
       |
       v
API / Connector
       |
       v
GRC Platform
       |
       v
Evidence Repository
       |
       v
Control Assessment
       |
       v
Compliance Dashboard
```

For example:

```text
IAM
 |
 +----> Access Review Evidence
 |
 +----> Privileged Account Evidence
 |
 +----> Authentication Evidence
```

---

# 16. Diagram 14 – Compliance Assessment Flow

A standard compliance assessment can be represented as:

```text
Assessment Scope
      |
      v
Applicable Requirements
      |
      v
Control Mapping
      |
      v
Evidence Collection
      |
      v
Control Testing
      |
      v
Assessment Result
      |
      +----------+
      |          |
      v          v
Compliant    Deficiency
                 |
                 v
             Remediation
```

---

# 17. Diagram 15 – Control Testing Architecture

Control testing should evaluate whether controls are appropriately designed and operating effectively.

```text
Control
  |
  v
Control Objective
  |
  v
Test Procedure
  |
  v
Sample / Population
  |
  v
Evidence
  |
  v
Test Result
  |
  +----------+
  |          |
  v          v
Pass        Fail
              |
              v
           Finding
```

---

# 18. Diagram 16 – Compliance Finding Lifecycle

Compliance findings should follow a controlled lifecycle.

```text
Finding Identified
       |
       v
Finding Validation
       |
       v
Risk Assessment
       |
       v
Root Cause
       |
       v
Corrective Action
       |
       v
Remediation
       |
       v
Validation
       |
       v
Closure
```

This prevents findings from disappearing after an audit report is issued.

---

# 19. Diagram 17 – Compliance Remediation

A remediation architecture can be:

```text
Compliance Gap
      |
      v
Root Cause Analysis
      |
      v
Remediation Plan
      |
      v
Action Owner
      |
      v
Target Date
      |
      v
Implementation
      |
      v
Validation
      |
      v
Closure
```

Important attributes include:

* finding severity;
* risk rating;
* owner;
* due date;
* remediation action;
* evidence;
* validation result;
* closure approval.

---

# 20. Diagram 18 – Exception Management

Not every control deficiency can be immediately resolved.

```text
Control Exception
       |
       v
Business Justification
       |
       v
Risk Assessment
       |
       v
Compensating Control?
       |
   +---+---+
   |       |
  Yes      No
   |       |
   v       v
Document  Risk Treatment
   |       |
   +---+---+
       |
       v
Risk Acceptance
       |
       v
Expiration / Review
```

Exceptions should normally have an expiration or review date.

---

# 21. Diagram 19 – Compliance Risk Model

Compliance risk should be connected to enterprise risk.

```text
Regulatory Requirement
        |
        v
Compliance Obligation
        |
        v
Potential Non-Compliance
        |
        v
Business Impact
        |
        v
Compliance Risk
        |
        v
Risk Treatment
```

Possible impacts include:

* regulatory penalties;
* operational disruption;
* financial loss;
* contractual consequences;
* reputational damage;
* customer impact.

---

# 22. Diagram 20 – Compliance Risk-to-Control Model

```text
Compliance Risk
      |
      v
Risk Treatment
      |
      v
Control Objective
      |
      v
Security Control
      |
      v
Control Effectiveness
      |
      v
Residual Compliance Risk
```

This creates an important relationship between compliance and risk management.

---

# 23. Diagram 21 – Cybersecurity Compliance Operating Model

A complete operating model can be represented as:

```text
                    GOVERNANCE
                        |
                        v
               Compliance Strategy
                        |
                        v
              Regulatory Intelligence
                        |
                        v
               Compliance Management
                        |
          +-------------+-------------+
          |             |             |
          v             v             v
       Policies       Controls      Risk
          |             |             |
          +-------------+-------------+
                        |
                        v
                 Evidence & Testing
                        |
                        v
                 Assurance / Audit
                        |
                        v
                Reporting & Metrics
                        |
                        v
                 Management Action
```

---

# 24. Diagram 22 – Three Lines Compliance Architecture

Compliance responsibilities can be aligned with the Three Lines model.

```text
                    BOARD
                      |
                      v
              Oversight / Governance
                      |
        +-------------+-------------+
        |             |             |
        v             v             v
    First Line    Second Line    Third Line
    Operations    Compliance     Internal Audit
    Controls      Risk / GRC     Assurance
        |             |             |
        +-------------+-------------+
                      |
                      v
             Compliance Assurance
```

The first line operates controls, the second line provides oversight and challenge, and the third line provides independent assurance.

---

# 25. Diagram 23 – Compliance Governance Committee

A governance structure can be represented as:

```text
Board
  |
  v
Risk / Audit Committee
  |
  v
Executive Management
  |
  v
Cybersecurity & Compliance Committee
  |
  +-----------+-----------+-----------+
  |           |           |           |
  v           v           v           v
Security    Privacy     Risk       Legal
```

The exact structure should reflect the organization's governance model.

---

# 26. Diagram 24 – Compliance Metrics Architecture

Compliance metrics should support management decisions.

```text
Compliance Data
      |
      v
Compliance Metrics
      |
      +----------+----------+
      |                     |
      v                     v
KPI                       KRI
      |                     |
      +----------+----------+
                 |
                 v
          Compliance Dashboard
                 |
                 v
          Management Decision
```

Examples include:

* percentage of controls tested;
* overdue remediation actions;
* number of high-risk findings;
* percentage of evidence collected;
* number of regulatory changes;
* compliance exceptions;
* control failure rate.

---

# 27. Diagram 25 – Executive Compliance Dashboard

An executive view might look like:

```text
+-----------------------------------------+
|       CYBERSECURITY COMPLIANCE          |
+-----------------------------------------+
| Frameworks in Scope              6      |
| Controls in Scope              420      |
| Effective Controls             391      |
| Control Gaps                    29      |
| High-Risk Findings               5      |
| Overdue Actions                 11      |
| Open Exceptions                  8      |
+-----------------------------------------+
```

The dashboard should emphasize risk and decision-making rather than simply displaying compliance statistics.

---

# 28. Diagram 26 – Continuous Compliance Architecture

Continuous compliance moves away from periodic manual assessments.

```text
Security Systems
      |
      v
Continuous Data Collection
      |
      v
Automated Control Monitoring
      |
      v
Compliance Rules
      |
      v
Control Status
      |
      v
Alert / Exception
      |
      v
Remediation
      |
      v
Validation
      |
      +-----------> Continuous Monitoring
```

This approach is particularly valuable in cloud and highly automated environments.

---

# 29. Diagram 27 – Cloud Compliance Architecture

Cloud environments require continuous compliance monitoring.

```text
Cloud Environment
       |
       +--------> Identity
       |
       +--------> Network
       |
       +--------> Storage
       |
       +--------> Compute
       |
       +--------> Logging
       |
       +--------> Encryption
       |
       v
Cloud Security Controls
       |
       v
Continuous Compliance Monitoring
       |
       v
GRC Platform
       |
       v
Compliance Dashboard
```

---

# 30. Diagram 28 – DevSecOps Compliance Architecture

Compliance should also integrate with development processes.

```text
Requirements
     |
     v
Secure Design
     |
     v
Development
     |
     v
Security Testing
     |
     v
Compliance Checks
     |
     v
Deployment
     |
     v
Continuous Monitoring
     |
     v
Evidence
```

This embeds compliance into the software development lifecycle.

---

# 31. Diagram 29 – Vulnerability-to-Compliance Model

Security vulnerabilities can affect compliance.

```text
Vulnerability
      |
      v
Asset Exposure
      |
      v
Security Risk
      |
      v
Compliance Impact
      |
      v
Control Assessment
      |
      v
Remediation
      |
      v
Validation
```

For example, failure to remediate critical vulnerabilities may affect compliance with specific security requirements.

---

# 32. Diagram 30 – Incident-to-Compliance Architecture

Security incidents can create compliance obligations.

```text
Security Incident
       |
       v
Incident Classification
       |
       v
Compliance Impact Assessment
       |
       v
Notification Requirement?
       |
   +---+---+
   |       |
  Yes      No
   |       |
   v       v
Notification  Internal Handling
   |
   v
Regulator / Customer
   |
   v
Post-Incident Review
   |
   v
Control Improvement
```

This connects incident management with compliance obligations.

---

# 33. Diagram 31 – Privacy and Cybersecurity Compliance

Privacy and cybersecurity requirements frequently overlap.

```text
Personal Data
      |
      v
Privacy Requirements
      |
      +----------------+
      |                |
      v                v
Privacy Controls   Cyber Controls
      |                |
      +-------+--------+
              |
              v
       Data Protection
              |
              v
          Evidence
              |
              v
         Assessment
```

This is especially important when organizations process significant volumes of personal data.

---

# 34. Diagram 32 – Third-Party Compliance Architecture

Third-party compliance can be integrated into the architecture.

```text
Supplier
   |
   v
Contractual Requirements
   |
   v
Security Requirements
   |
   v
Supplier Controls
   |
   v
Supplier Evidence
   |
   v
Assessment
   |
   v
Risk Rating
   |
   v
Ongoing Monitoring
```

This creates a connection between third-party risk management and cybersecurity compliance.

---

# 35. Diagram 33 – Compliance Evidence Repository

A mature organization can maintain centralized evidence.

```text
                 EVIDENCE SOURCES
                       |
       +---------------+---------------+
       |               |               |
       v               v               v
    Security        Business         HR / IT
    Systems         Processes        Systems
       |               |               |
       +---------------+---------------+
                       |
                       v
                Evidence Repository
                       |
                       v
                Control Mapping
                       |
                       v
                Assessment / Audit
```

Evidence should be linked to controls and requirements rather than stored without context.

---

# 36. Diagram 34 – Compliance Data Architecture

A GRC platform can serve as the central compliance data layer.

```text
Regulations
    |
Frameworks
    |
Policies
    |
Controls
    |
Risks
    |
Evidence
    |
Findings
    |
Actions
    |
    v
+----------------------+
|     GRC PLATFORM     |
+----------------------+
    |
    +------> Dashboards
    |
    +------> Reports
    |
    +------> Alerts
    |
    +------> Management Decisions
```

This architecture is common in mature GRC environments.

---

# 37. Diagram 35 – End-to-End Cybersecurity Compliance Traceability

The complete traceability chain is:

```text
Regulation
    |
    v
Requirement
    |
    v
Obligation
    |
    v
Risk
    |
    v
Control Objective
    |
    v
Control
    |
    v
Technology / Process
    |
    v
Evidence
    |
    v
Testing
    |
    v
Finding
    |
    v
Remediation
    |
    v
Validation
    |
    v
Compliance Status
    |
    v
Executive Reporting
```

This is one of the strongest diagrams to include in a GRC knowledge base because it demonstrates the complete compliance lifecycle.

---

# 38. Diagram 36 – Integrated Compliance Architecture

A mature architecture integrates the major GRC domains.

```text
                    EXTERNAL REQUIREMENTS
                            |
             +--------------+--------------+
             |              |              |
             v              v              v
        Regulations      Standards      Contracts
             |              |              |
             +--------------+--------------+
                            |
                            v
                   Compliance Obligations
                            |
              +-------------+-------------+
              |             |             |
              v             v             v
            Risk        Controls       Policies
              |             |             |
              +-------------+-------------+
                            |
                            v
                   Security Operations
                            |
                            v
                      Evidence
                            |
                            v
                  Testing & Assurance
                            |
                            v
                      Findings
                            |
                            v
                     Remediation
                            |
                            v
                   Compliance Reporting
                            |
                            v
                    Management Decision
```

---

# 39. Practical Case Study – ISO 27001 + NIST + GDPR

Consider an organization using several frameworks.

```text
                 Compliance Environment
                         |
        +----------------+----------------+
        |                |                |
        v                v                v
    ISO 27001          NIST             GDPR
        |                |                |
        +----------------+----------------+
                         |
                         v
                 Common Control Set
                         |
        +----------------+----------------+
        |                |                |
        v                v                v
      IAM            Logging          Encryption
        |                |                |
        +----------------+----------------+
                         |
                         v
                      Evidence
                         |
                         v
                  Control Testing
                         |
                         v
                   GRC Dashboard
```

The organization can therefore operate a **unified control environment** rather than separate compliance silos.

---

# 40. Practical Case Study – NIS2 Cybersecurity Compliance

A NIS2-oriented architecture could be represented as:

```text
NIS2 Requirements
        |
        v
Applicable Obligations
        |
        v
Cybersecurity Risk Management
        |
        v
Security Controls
        |
        +----------+----------+
        |          |          |
        v          v          v
      Access    Incident    Supply Chain
      Control   Response      Security
        |          |          |
        +----------+----------+
                   |
                   v
              Evidence
                   |
                   v
              Assessment
                   |
                   v
             Gap Remediation
                   |
                   v
              Management
```

The exact control mapping should be based on the applicable legal requirements and the organization's implementation approach.

---

# 41. Practical Case Study – DORA-Oriented Architecture

For a financial organization subject to DORA:

```text
Digital Operational Resilience
             |
      +------+------+------+
      |      |      |      |
      v      v      v      v
 ICT Risk  Incident  Testing  Third Party
 Management Reporting          Risk
      |      |      |      |
      +------+------+------+
             |
             v
        ICT Controls
             |
             v
          Evidence
             |
             v
         Assurance
             |
             v
      Executive Reporting
```

This demonstrates how regulatory requirements can be translated into operational control domains.

---

# 42. Practical Case Study – PCI DSS

A payment-card environment may use:

```text
PCI DSS Requirements
        |
        v
Cardholder Data Environment
        |
        v
Security Controls
        |
        +--------+--------+--------+
        |        |        |        |
        v        v        v        v
      IAM      Network   Logging  Vulnerability
                Security           Management
        |        |        |        |
        +--------+--------+--------+
                 |
                 v
               Evidence
                 |
                 v
              Testing
                 |
                 v
              Attestation
```

This illustrates how a specific compliance framework can be integrated into the broader cybersecurity architecture.

---

# 43. Compliance Architecture Maturity

Organizations can mature their architecture through several stages.

### Level 1 – Fragmented

```text
Regulations → Individual Teams
```

Different teams manage different requirements with little coordination.

### Level 2 – Documented

```text
Requirements
      ↓
Policies
      ↓
Controls
```

Basic control mapping exists.

### Level 3 – Integrated

```text
Requirements
      ↓
Common Controls
      ↓
Evidence
      ↓
Testing
```

Multiple frameworks share common controls and evidence.

### Level 4 – Automated

```text
Requirements
      ↓
Controls
      ↓
Automated Evidence
      ↓
Continuous Monitoring
      ↓
Compliance Dashboard
```

### Level 5 – Risk-Driven

```text
Regulation
   ↓
Compliance Obligation
   ↓
Risk
   ↓
Control
   ↓
Evidence
   ↓
Continuous Monitoring
   ↓
Risk-Based Decision
```

The final stage integrates compliance into enterprise risk management.

---

# 44. Common Cybersecurity Compliance Architecture Mistakes

### 1. Treating Compliance as a Checklist

Compliance should be connected to risk and business objectives.

### 2. Creating Separate Controls for Every Framework

Where appropriate, common controls should support multiple requirements.

### 3. No Requirement-to-Control Traceability

Organizations should be able to demonstrate which controls address which requirements.

### 4. No Evidence Traceability

Evidence should be linked to specific controls and assessments.

### 5. No Control Ownership

Every important control should have an accountable owner.

### 6. No Regulatory Change Process

Compliance requirements can change over time.

### 7. No Remediation Tracking

Findings should have owners, deadlines, and validation.

### 8. Excessive Manual Evidence Collection

Automation can reduce repetitive evidence gathering.

### 9. No Integration With Risk

Compliance deficiencies can create business and cybersecurity risk.

### 10. No Executive View

Senior management needs visibility into material compliance exposure.

---

# 45. Recommended Cybersecurity Compliance Diagram Set

A practical diagram library can contain:

| #  | Diagram                             | Primary Purpose          |
| -- | ----------------------------------- | ------------------------ |
| 1  | Regulatory-to-Control Architecture  | Core traceability        |
| 2  | Multi-Framework Compliance          | Framework integration    |
| 3  | Framework Crosswalk                 | Requirement mapping      |
| 4  | Common Control Architecture         | Control reuse            |
| 5  | Compliance Obligation Lifecycle     | Obligation management    |
| 6  | Applicability Assessment            | Scope determination      |
| 7  | Regulatory Change Management        | Change management        |
| 8  | Requirement-to-Control Traceability | Traceability             |
| 9  | Control Implementation              | Operationalization       |
| 10 | Policy Hierarchy                    | Governance               |
| 11 | Compliance-to-Technology            | Technical implementation |
| 12 | Evidence Architecture               | Evidence management      |
| 13 | Automated Evidence Collection       | Automation               |
| 14 | Compliance Assessment               | Assessment               |
| 15 | Control Testing                     | Assurance                |
| 16 | Compliance Finding Lifecycle        | Findings                 |
| 17 | Compliance Remediation              | Corrective action        |
| 18 | Exception Management                | Risk acceptance          |
| 19 | Compliance Risk Model               | Risk integration         |
| 20 | Risk-to-Control Model               | Risk treatment           |
| 21 | Compliance Operating Model          | Governance               |
| 22 | Three Lines Compliance              | Accountability           |
| 23 | Compliance Governance               | Decision-making          |
| 24 | Compliance Metrics                  | Measurement              |
| 25 | Executive Dashboard                 | Reporting                |
| 26 | Continuous Compliance               | Monitoring               |
| 27 | Cloud Compliance                    | Cloud security           |
| 28 | DevSecOps Compliance                | SDLC integration         |
| 29 | Vulnerability-to-Compliance         | Security integration     |
| 30 | Incident-to-Compliance              | Incident integration     |
| 31 | Privacy + Cybersecurity             | Data protection          |
| 32 | Third-Party Compliance              | Supplier governance      |
| 33 | Evidence Repository                 | Evidence management      |
| 34 | Compliance Data Architecture        | GRC technology           |
| 35 | End-to-End Traceability             | Complete lifecycle       |
| 36 | Integrated Compliance Architecture  | Enterprise model         |

---

# 46. The Executive-Level Diagram

For executives, the entire architecture can be simplified to:

```text
                 REGULATIONS
                      |
                      v
             COMPLIANCE OBLIGATIONS
                      |
                      v
                  CYBER RISKS
                      |
                      v
              SECURITY CONTROLS
                      |
                      v
                   EVIDENCE
                      |
                      v
             TESTING & ASSURANCE
                      |
                      v
               GAPS / FINDINGS
                      |
                      v
                REMEDIATION
                      |
                      v
             COMPLIANCE STATUS
                      |
                      v
           MANAGEMENT DECISION
```

---

# 47. The GRC Professional Diagram

For a GRC practitioner, the preferred detailed model is:

```text
External Requirement
        |
        v
Compliance Obligation
        |
        v
Risk
        |
        v
Control Objective
        |
        v
Control
        |
        v
Control Owner
        |
        v
Implementation
        |
        v
Evidence
        |
        v
Control Testing
        |
        v
Finding
        |
        v
Remediation
        |
        v
Validation
        |
        v
Compliance Status
        |
        v
Risk Reporting
        |
        v
Executive Decision
```

This is the model that demonstrates **end-to-end GRC traceability**.

---

# 48. Final Cybersecurity Compliance Architecture

The complete architecture can ultimately be summarized as:

```text
                         BUSINESS OBJECTIVES
                                |
                                v
                      REGULATORY ENVIRONMENT
                                |
                                v
                     COMPLIANCE OBLIGATIONS
                                |
                                v
                           RISK UNIVERSE
                                |
                                v
                        CONTROL FRAMEWORK
                                |
                                v
                        SECURITY CONTROLS
                                |
                     +----------+----------+
                     |                     |
                     v                     v
                 TECHNOLOGY             PROCESS
                     |                     |
                     +----------+----------+
                                |
                                v
                         EVIDENCE SOURCES
                                |
                                v
                        GRC / EVIDENCE HUB
                                |
                                v
                       TESTING & ASSURANCE
                                |
                     +----------+----------+
                     |                     |
                     v                     v
                  COMPLIANT            FINDING
                                           |
                                           v
                                      REMEDIATION
                                           |
                                           v
                                       VALIDATION
                                           |
                                           v
                                  COMPLIANCE STATUS
                                           |
                                           v
                                  RISK REPORTING
                                           |
                                           v
                                  MANAGEMENT DECISION
```

The key principle is:

> **A cybersecurity compliance architecture should make it possible to trace every important external requirement through risk, controls, implementation, evidence, testing, remediation, and ultimately management decision-making.**

For a GRC professional, this architecture is particularly valuable because it demonstrates that **compliance is not merely documentation or audit preparation—it is an integrated operating capability connecting regulatory obligations, cybersecurity risk, control implementation, evidence, assurance, and enterprise governance.**


# 18.20 Practical GRC Diagram Case Studies

## Part 4 – Building an Executive GRC Visual Dashboard & Chapter Summary

An **Executive GRC Visual Dashboard** converts complex governance, risk, compliance, security, audit, and control information into a concise visual representation for senior management, executive committees, and the board.

The purpose is not to display every GRC metric. The purpose is to answer the executive questions:

```text
What is our current risk exposure?
        ↓
Are we within risk appetite?
        ↓
Where are our major compliance gaps?
        ↓
Are critical controls effective?
        ↓
What requires management attention?
        ↓
What decisions need to be made?
```

A well-designed executive GRC dashboard therefore functions as a **decision-support system**, not merely a reporting screen.

---

# 1. Why Executive GRC Dashboards Matter

GRC environments can generate enormous quantities of information:

* hundreds of risks;
* thousands of controls;
* multiple regulations;
* audit findings;
* compliance assessments;
* third-party assessments;
* security incidents;
* KRIs;
* KPIs;
* remediation actions;
* policy exceptions;
* evidence records.

Executives do not need all of this information simultaneously.

The dashboard should transform:

```text
Large GRC Data Volume
        |
        v
Data Aggregation
        |
        v
Risk / Compliance Analysis
        |
        v
Key Metrics
        |
        v
Executive Dashboard
        |
        v
Management Decision
```

The dashboard should therefore emphasize **materiality, trends, exceptions, and decisions**.

---

# 2. Executive GRC Dashboard Architecture

A practical dashboard can be organized into six layers.

```text
+------------------------------------------------+
| 1. ENTERPRISE RISK                             |
+------------------------------------------------+
| 2. COMPLIANCE                                  |
+------------------------------------------------+
| 3. CONTROL EFFECTIVENESS                       |
+------------------------------------------------+
| 4. AUDIT & ASSURANCE                           |
+------------------------------------------------+
| 5. SECURITY & RESILIENCE                       |
+------------------------------------------------+
| 6. MANAGEMENT ACTIONS                          |
+------------------------------------------------+
```

These areas provide a balanced view of the organization's GRC posture.

---

# 3. The Executive GRC Dashboard Model

The overall architecture can be represented as:

```text
                GRC DATA SOURCES
                       |
        +--------------+--------------+
        |              |              |
        v              v              v
      Risk         Compliance       Controls
        |              |              |
        +--------------+--------------+
                       |
        +--------------+--------------+
        |              |              |
        v              v              v
      Audit         Security       Third Party
                       |
                       v
                 GRC PLATFORM
                       |
                       v
               ANALYTICS ENGINE
                       |
                       v
              EXECUTIVE DASHBOARD
                       |
                       v
             MANAGEMENT DECISIONS
```

---

# 4. Dashboard Section 1 – Enterprise Risk

The first section should provide an enterprise risk overview.

```text
+--------------------------------------+
| ENTERPRISE RISK                      |
+--------------------------------------+
| Critical Risks              6        |
| High Risks                 18        |
| Risks Above Appetite        4        |
| Emerging Risks              7        |
| Overdue Treatment           9        |
+--------------------------------------+
```

The executive should immediately understand:

* how many material risks exist;
* which risks exceed appetite;
* whether exposure is increasing;
* whether treatment actions are progressing.

---

# 5. Risk Heat Map

A risk heat map provides a visual representation of exposure.

```text
                     IMPACT
                       ↑

             HIGH      |  ● R03   ● R07
                       |
             MEDIUM    |     ● R05
                       | ● R09
             LOW       | ● R11
                       +--------------------→
                         LOW   MED   HIGH
                            LIKELIHOOD
```

The heat map should identify the organization's most significant risks rather than attempt to display every minor risk.

---

# 6. Risk Trend Diagram

Executives should also understand whether exposure is increasing or decreasing.

```text
Risk Exposure

High |              ●
     |          ●       ●
Med  |      ●
     |  ●
Low  +--------------------------→
       Q1   Q2   Q3   Q4   Q5
```

Trend information can be more valuable than a single risk score.

For example:

```text
Current Risk: High
Trend: Increasing
Appetite: Exceeded
Management Action: Required
```

---

# 7. Dashboard Section 2 – Compliance

The compliance section should summarize the organization's regulatory position.

```text
+--------------------------------------+
| CYBERSECURITY COMPLIANCE             |
+--------------------------------------+
| Frameworks in Scope            7     |
| Requirements                 520     |
| Compliant                    471     |
| Partial Compliance            34     |
| Non-Compliant                 15     |
| High-Risk Gaps                 5     |
+--------------------------------------+
```

The most important information is usually the **material compliance exposure**, not the total number of requirements.

---

# 8. Compliance Status Model

Compliance status can be visualized as:

```text
                  Requirements
                       |
        +--------------+--------------+
        |              |              |
        v              v              v
    Compliant       Partial       Non-Compliant
        |              |              |
        +--------------+--------------+
                       |
                       v
                Compliance Risk
                       |
                       v
                Management Action
```

This connects compliance status to risk rather than treating compliance as an isolated score.

---

# 9. Dashboard Section 3 – Control Effectiveness

Executives should know whether important controls are actually operating effectively.

```text
+--------------------------------------+
| CONTROL EFFECTIVENESS                |
+--------------------------------------+
| Critical Controls             85     |
| Effective                     74     |
| Partially Effective             7    |
| Ineffective                     4    |
| Overdue Testing                 6    |
+--------------------------------------+
```

The dashboard should distinguish between:

* control design;
* control implementation;
* operating effectiveness;
* testing status.

---

# 10. Control Effectiveness Model

A useful visual model is:

```text
Control Population
       |
       v
Control Design
       |
       v
Implementation
       |
       v
Operation
       |
       v
Testing
       |
       v
Effectiveness
```

This prevents organizations from assuming that a documented control is automatically an effective control.

---

# 11. Dashboard Section 4 – Audit and Assurance

The audit section should provide assurance information.

```text
+--------------------------------------+
| AUDIT & ASSURANCE                    |
+--------------------------------------+
| Open Findings                 42     |
| High-Risk Findings             8    |
| Overdue Findings               11    |
| Audits in Progress              6    |
| Findings Closed This Quarter  19    |
+--------------------------------------+
```

Trend is important.

For example:

```text
Open Findings

Q1  ██████████████████  55
Q2  ███████████████     47
Q3  ████████████        39
Q4  ██████████          32
```

The executive question should be:

**Is assurance exposure improving?**

---

# 12. Finding Aging Diagram

Finding age can provide additional insight.

```text
Open Findings
     |
     +---- <30 days
     |
     +---- 31–60 days
     |
     +---- 61–90 days
     |
     +---- >90 days
```

Older findings should receive greater management attention when they represent material risks.

---

# 13. Dashboard Section 5 – Cybersecurity

The cybersecurity section can provide a business-oriented security view.

```text
+--------------------------------------+
| CYBERSECURITY                        |
+--------------------------------------+
| Critical Vulnerabilities       12    |
| Critical Incidents              2    |
| High-Risk Assets               34    |
| Security Exceptions             8    |
| Overdue Security Actions       15    |
+--------------------------------------+
```

The dashboard should avoid overwhelming executives with technical SOC metrics unless they directly affect business risk.

---

# 14. Cybersecurity Risk Translation

Technical information should be translated into business impact.

Instead of:

```text
Critical CVEs = 12
```

the executive dashboard might show:

```text
12 Critical Vulnerabilities
        |
        v
4 Affect Critical Assets
        |
        v
2 Create High Enterprise Risk
        |
        v
Executive Action Required
```

This is much more useful for senior management.

---

# 15. Dashboard Section 6 – Third-Party Risk

Third-party exposure should also be visible.

```text
+--------------------------------------+
| THIRD-PARTY RISK                     |
+--------------------------------------+
| Critical Suppliers            24     |
| High-Risk Suppliers             6    |
| Assessments Overdue             4    |
| Critical Findings               3    |
| Contracts Expiring <90 Days     7    |
+--------------------------------------+
```

The dashboard should prioritize suppliers whose failure could materially affect the organization.

---

# 16. Third-Party Risk Architecture

```text
Critical Suppliers
       |
       v
Supplier Risk Assessment
       |
       v
Control Assessment
       |
       v
Findings
       |
       v
Remediation
       |
       v
Residual Supplier Risk
       |
       v
Enterprise Risk Dashboard
```

---

# 17. Dashboard Section 7 – Business Continuity and Resilience

Resilience metrics can be included in the dashboard.

```text
+--------------------------------------+
| BUSINESS RESILIENCE                  |
+--------------------------------------+
| Critical Services              28    |
| BIA Coverage                   100%   |
| DR Tests Completed              91%   |
| RTO Exceptions                   3    |
| RPO Exceptions                   2    |
| Open Resilience Actions          7    |
+--------------------------------------+
```

This connects operational resilience to enterprise risk.

---

# 18. Dashboard Section 8 – Privacy

Where relevant, privacy indicators can be incorporated.

```text
+--------------------------------------+
| PRIVACY & DATA PROTECTION             |
+--------------------------------------+
| High-Risk Processing Activities  8    |
| DPIAs Completed                 94%    |
| Open Privacy Findings            6     |
| Data Incidents                   2     |
| Overdue Privacy Actions          3     |
+--------------------------------------+
```

The exact metrics should reflect the organization's regulatory environment.

---

# 19. Dashboard Section 9 – GRC Transformation

For organizations implementing GRC transformation programs:

```text
+--------------------------------------+
| GRC TRANSFORMATION                   |
+--------------------------------------+
| Processes Automated            68%   |
| Evidence Automation            74%   |
| Control Rationalization        81%   |
| Frameworks Integrated            6    |
| Manual Processes Remaining     22%   |
+--------------------------------------+
```

This allows executives to understand whether the GRC operating model is becoming more mature.

---

# 20. Executive Decision Layer

The dashboard should end with decisions.

```text
                     GRC INFORMATION
                            |
                            v
                     Executive Analysis
                            |
              +-------------+-------------+
              |             |             |
              v             v             v
          Accept Risk    Fund Action   Escalate
              |             |             |
              +-------------+-------------+
                            |
                            v
                     Management Action
```

This is the most important purpose of the executive dashboard.

---

# 21. GRC Metrics-to-Decision Model

A mature dashboard should connect each important metric to a potential management decision.

```text
Metric
  |
  v
Threshold
  |
  v
Risk Interpretation
  |
  v
Business Impact
  |
  v
Management Decision
  |
  v
Action
  |
  v
Outcome
```

For example:

```text
KRI Breach
   |
   v
Risk Appetite Exceeded
   |
   v
Business Exposure Increased
   |
   v
Executive Escalation
   |
   v
Additional Risk Treatment
```

---

# 22. KPI and KRI Relationship

KPIs and KRIs should not be confused.

```text
                    GRC PERFORMANCE
                           |
              +------------+------------+
              |                         |
              v                         v
             KPI                       KRI
              |                         |
       Performance                   Exposure
              |                         |
              +------------+------------+
                           |
                           v
                    Management Decision
```

A **KPI** primarily indicates performance.

A **KRI** primarily indicates risk exposure.

---

# 23. Leading and Lagging Indicators

A mature dashboard can include both.

```text
Leading Indicators
       |
       v
Potential Future Exposure
       |
       v
Preventive Action
       |
       v
Business Outcome
       |
       v
Lagging Indicators
```

Examples of leading indicators:

* overdue control remediation;
* privileged-account growth;
* supplier concentration;
* vulnerability aging;
* training completion gaps.

Examples of lagging indicators:

* incidents;
* regulatory penalties;
* audit findings;
* service outages;
* confirmed data breaches.

---

# 24. Executive Dashboard Traffic-Light Model

Traffic-light indicators can simplify status communication.

```text
GREEN
Within appetite / acceptable

AMBER
Requires management attention

RED
Outside appetite / immediate action
```

However, traffic lights should not replace numerical information where precision is necessary.

A good dashboard might show:

```text
Cyber Risk        RED
Compliance        AMBER
Controls          GREEN
Third Parties     AMBER
Resilience        GREEN
Audit             RED
```

---

# 25. Dashboard Drill-Down Architecture

Executives may start with a high-level dashboard and drill down into details.

```text
LEVEL 1
Executive Dashboard
       |
       v
LEVEL 2
Risk / Compliance Domain
       |
       v
LEVEL 3
Specific Risk / Control
       |
       v
LEVEL 4
Evidence / Finding
       |
       v
LEVEL 5
Detailed Record
```

This provides both executive simplicity and operational depth.

---

# 26. GRC Dashboard Data Flow

The technical architecture can be represented as:

```text
             DATA SOURCES
                  |
    +-------------+-------------+
    |             |             |
    v             v             v
GRC Platform   Security      Business
              Platforms       Systems
    |             |             |
    +-------------+-------------+
                  |
                  v
             Data Layer
                  |
                  v
             Analytics
                  |
                  v
             GRC Metrics
                  |
                  v
         Executive Dashboard
```

Potential source systems include:

* ServiceNow GRC;
* Archer;
* SIEM;
* IAM;
* vulnerability management;
* ticketing systems;
* cloud security platforms;
* audit systems;
* supplier-risk systems.

---

# 27. Data Quality Architecture

A dashboard is only as reliable as its underlying data.

```text
GRC Data
   |
   v
Data Validation
   |
   v
Data Quality Checks
   |
   +----------+----------+
   |                     |
   v                     v
Valid                  Invalid
   |                     |
   v                     v
Dashboard             Correction
```

Important data-quality dimensions include:

* completeness;
* accuracy;
* consistency;
* timeliness;
* uniqueness;
* ownership.

---

# 28. Dashboard Governance

The dashboard itself requires governance.

```text
Dashboard Owner
      |
      v
Metric Definitions
      |
      v
Data Owners
      |
      v
Calculation Rules
      |
      v
Data Validation
      |
      v
Approval
      |
      v
Publication
      |
      v
Periodic Review
```

Without metric governance, different departments may report inconsistent numbers.

---

# 29. Metric Definition Model

Every important metric should have a defined meaning.

```text
Metric Name
     |
     v
Definition
     |
     v
Calculation
     |
     v
Data Source
     |
     v
Owner
     |
     v
Frequency
     |
     v
Threshold
     |
     v
Escalation Rule
```

For example:

```text
Metric:
Critical Risk Above Appetite

Definition:
Number of material enterprise risks exceeding approved appetite.

Owner:
Enterprise Risk Management

Frequency:
Monthly

Escalation:
Risk Committee
```

---

# 30. Dashboard Design Principles

A strong executive dashboard should follow several principles.

### Principle 1 – Materiality

Show information that matters to business decisions.

### Principle 2 – Simplicity

Avoid unnecessary visual complexity.

### Principle 3 – Trend

Show whether the situation is improving or deteriorating.

### Principle 4 – Context

A number without context can be misleading.

### Principle 5 – Thresholds

Show when management action is required.

### Principle 6 – Ownership

Important metrics should have accountable owners.

### Principle 7 – Actionability

Every material exception should lead toward an action or decision.

---

# 31. What Not to Put on an Executive Dashboard

Avoid excessive technical detail such as:

```text
10,000+
Firewall Events
```

unless the number has direct business significance.

Instead:

```text
10,000+ Security Events
        |
        v
12 Confirmed High-Risk Events
        |
        v
2 Critical Business Assets Affected
        |
        v
Executive Attention Required
```

The objective is to translate technical data into business risk.

---

# 32. Executive Dashboard Example

A consolidated dashboard could look like:

```text
+------------------------------------------------------+
|              ENTERPRISE GRC DASHBOARD                |
+------------------------------------------------------+
| RISK             | COMPLIANCE       | CONTROLS       |
| Critical: 6      | Gaps: 15         | Failed: 4     |
| Above Appetite:4 | High Risk: 5     | Overdue: 6    |
+------------------------------------------------------+
| AUDIT            | CYBERSECURITY    | THIRD PARTY   |
| Findings: 42     | Critical: 12     | High Risk: 6  |
| High Risk: 8     | Incidents: 2     | Overdue: 4    |
+------------------------------------------------------+
| RESILIENCE       | PRIVACY          | ACTIONS       |
| RTO Issues: 3    | Findings: 6      | Overdue: 19   |
| DR Coverage:91%  | Incidents: 2     | Critical: 7   |
+------------------------------------------------------+
```

The exact metrics should be based on the organization's actual GRC data.

---

# 33. Executive GRC Dashboard – Decision View

A more mature dashboard can focus directly on management decisions:

```text
+------------------------------------------------+
|             MANAGEMENT ATTENTION               |
+------------------------------------------------+
|                                                |
| 🔴 4 Risks Above Approved Appetite             |
| 🔴 5 High-Risk Compliance Gaps                 |
| 🔴 8 High-Risk Audit Findings                  |
| 🟠 11 Overdue Remediation Actions              |
| 🟠 6 High-Risk Suppliers                       |
|                                                |
+------------------------------------------------+
| DECISIONS REQUIRED                             |
|                                                |
| 1. Approve additional risk treatment           |
| 2. Accept / reject risk exception               |
| 3. Allocate remediation resources               |
| 4. Escalate critical supplier exposure          |
+------------------------------------------------+
```

The strongest executive dashboards answer **"What do you need from me?"**

---

# 34. Board-Level GRC Dashboard

The board usually requires an even more condensed view.

```text
                    BOARD GRC VIEW
                          |
       +------------------+------------------+
       |                  |                  |
       v                  v                  v
  Enterprise Risk     Compliance        Resilience
       |                  |                  |
       +------------------+------------------+
                          |
                          v
                    Major Findings
                          |
                          v
                 Strategic Decisions
```

Board-level information should emphasize:

* material enterprise risks;
* risk appetite breaches;
* regulatory exposure;
* major incidents;
* systemic control weaknesses;
* resilience;
* significant third-party exposure;
* management actions.

---

# 35. CEO-Level GRC View

A CEO may need a very concise view:

```text
Enterprise Risk
      |
      v
Regulatory Exposure
      |
      v
Cybersecurity Exposure
      |
      v
Operational Resilience
      |
      v
Major Actions
      |
      v
Business Decisions
```

This is substantially different from an operational GRC dashboard.

---

# 36. CISO-Level GRC View

The CISO requires greater cybersecurity detail:

```text
Cyber Risk
   |
   +---- Vulnerability Risk
   |
   +---- Identity Risk
   |
   +---- Cloud Risk
   |
   +---- Third-Party Risk
   |
   +---- Data Protection Risk
   |
   +---- Incident Risk
   |
   +---- Resilience Risk
```

The CISO dashboard can then connect these areas to enterprise risk.

---

# 37. GRC Manager View

A GRC manager requires operational information:

```text
Controls
   |
   +---- Testing
   |
   +---- Evidence
   |
   +---- Findings
   |
   +---- Remediation
   |
   +---- Exceptions
   |
   +---- Risk Assessments
   |
   +---- Compliance Obligations
```

This illustrates an important concept:

> **The same GRC data can be presented differently depending on the decision-maker.**

---

# 38. Executive Dashboard Maturity

### Level 1 – Reporting

```text
Collect Data → Display Data
```

### Level 2 – Monitoring

```text
Collect → Analyze → Display
```

### Level 3 – Risk-Based

```text
Collect → Analyze → Identify Risk → Display
```

### Level 4 – Decision-Oriented

```text
Collect → Analyze → Risk → Threshold → Decision
```

### Level 5 – Predictive

```text
Collect
   ↓
Analyze
   ↓
Trend
   ↓
Predict
   ↓
Risk Scenario
   ↓
Decision
   ↓
Action
```

A mature organization should progressively move toward the final model.

---

# 39. Chapter 18 – GRC Diagram Architecture

Chapter 18 has progressively developed the major visual components of GRC.

The overall architecture can be represented as:

```text
                         GRC VISUAL COMMUNICATION
                                  |
       +--------------------------+--------------------------+
       |                          |                          |
       v                          v                          v
   GOVERNANCE                   RISK                    COMPLIANCE
       |                          |                          |
       v                          v                          v
 Governance Model          Risk Lifecycle           Regulatory Lifecycle
 Three Lines               Risk Assessment          Requirement Mapping
 Roles                      Risk Treatment           Compliance Assessment
 Committees                 Risk Monitoring          Regulatory Change
       |                          |                          |
       +--------------------------+--------------------------+
                                  |
                                  v
                              CONTROLS
                                  |
                     +------------+------------+
                     |                         |
                     v                         v
                  ISO 27001                  NIST CSF
                     |                         |
                     +------------+------------+
                                  |
                                  v
                              SECURITY
                                  |
              +-------------------+-------------------+
              |                   |                   |
              v                   v                   v
          Architecture        Incidents           Resilience
              |                   |                   |
              +-------------------+-------------------+
                                  |
                                  v
                           THIRD-PARTY RISK
                                  |
                                  v
                              AUDIT
                                  |
                                  v
                         DATA & EVIDENCE
                                  |
                                  v
                              METRICS
                                  |
                                  v
                             AUTOMATION
                                  |
                                  v
                              PROJECTS
                                  |
                                  v
                          THREAT & RISK
                                  |
                                  v
                         INTEGRATED GRC
                                  |
                                  v
                         EXECUTIVE DASHBOARD
```

---

# 40. Chapter 18 – Complete GRC Visual Model

The entire chapter can ultimately be summarized through one integrated model:

```text
                    BUSINESS OBJECTIVES
                           |
                           v
                      GOVERNANCE
                           |
                           v
                     RISK MANAGEMENT
                           |
                           v
                    COMPLIANCE
                           |
                           v
                       CONTROLS
                           |
                           v
                     CYBERSECURITY
                           |
                           v
                BUSINESS RESILIENCE
                           |
                           v
                 THIRD-PARTY RISK
                           |
                           v
                     AUDIT / ASSURANCE
                           |
                           v
                    DATA & EVIDENCE
                           |
                           v
                     METRICS / KRIs
                           |
                           v
                      AUTOMATION
                           |
                           v
                  MANAGEMENT DECISION
                           |
                           v
                  CONTINUAL IMPROVEMENT
                           |
                           +-------------> BUSINESS OBJECTIVES
```

This represents GRC as a **continuous management system** rather than a collection of disconnected activities.

---

# 41. The GRC Traceability Chain

One of the most important concepts developed throughout Chapter 18 is traceability:

```text
Business Objective
       |
       v
Risk
       |
       v
Requirement
       |
       v
Control Objective
       |
       v
Control
       |
       v
Implementation
       |
       v
Evidence
       |
       v
Testing
       |
       v
Finding
       |
       v
Remediation
       |
       v
Risk Status
       |
       v
Executive Decision
```

A mature GRC program should be able to move **forward and backward** through this chain.

For example:

**Requirement → Control → Evidence**

or:

**Risk → Control → Finding → Remediation**

or:

**Business Objective → Risk → KRI → Executive Decision**

---

# 42. The GRC Decision Chain

The ultimate purpose of GRC is decision support.

```text
DATA
 |
 v
INFORMATION
 |
 v
RISK / COMPLIANCE INSIGHT
 |
 v
MANAGEMENT INTERPRETATION
 |
 v
DECISION
 |
 v
ACTION
 |
 v
OUTCOME
 |
 v
NEW DATA
```

This creates a continuous feedback loop.

---

# 43. Chapter 18 – Practical GRC Diagram Portfolio

By the end of Chapter 18, a GRC professional should be able to create visual models covering:

### Governance

* Enterprise GRC governance;
* Three Lines;
* roles and responsibilities;
* governance committees.

### Risk

* ERM lifecycle;
* risk assessment;
* risk treatment;
* inherent and residual risk;
* risk appetite;
* risk monitoring.

### Compliance

* regulatory lifecycle;
* requirement-to-control mapping;
* compliance assessment;
* regulatory change.

### Controls

* control lifecycle;
* control objectives;
* control effectiveness;
* control-to-evidence relationships.

### Security

* defense in depth;
* Zero Trust;
* network security;
* identity security.

### Incidents

* incident response;
* escalation;
* investigation;
* lessons learned.

### Resilience

* business continuity;
* BIA;
* disaster recovery;
* RTO/RPO;
* recovery testing.

### Third Parties

* supplier lifecycle;
* due diligence;
* assessment;
* monitoring and offboarding.

### Audit

* audit lifecycle;
* evidence testing;
* findings;
* remediation;
* assurance.

### Data and Evidence

* evidence lifecycle;
* traceability;
* requirement-to-evidence;
* GRC data architecture.

### Metrics

* KPI/KRI;
* risk dashboards;
* executive dashboards;
* metrics-to-decision.

### Automation

* workflow automation;
* automated risk assessment;
* automated evidence collection;
* GRC platform integration.

### Projects

* implementation lifecycle;
* project roadmap;
* RACI;
* transformation roadmap.

### Threat and Risk

* threat-to-risk;
* vulnerability-to-risk;
* attack path;
* risk prioritization.

### Integrated GRC

* enterprise operating model;
* integrated risk/compliance/control;
* framework crosswalk;
* end-to-end traceability.

---

# 44. Practical GRC Diagram Development Method

When creating any GRC diagram, use the following approach:

```text
1. Define the Business Question
             ↓
2. Identify the GRC Domain
             ↓
3. Identify Inputs
             ↓
4. Identify Processes
             ↓
5. Identify Decisions
             ↓
6. Identify Outputs
             ↓
7. Add Ownership
             ↓
8. Add Risk / Control Relationships
             ↓
9. Add Evidence / Data
             ↓
10. Validate the Diagram
```

The diagram should communicate a meaningful relationship rather than merely decorate a document.

---

# 45. Choosing the Correct Diagram Type

A GRC professional should select the diagram according to the question being answered.

| Question                         | Appropriate Diagram         |
| -------------------------------- | --------------------------- |
| Who governs this?                | Governance model            |
| What is the process?             | Lifecycle / flowchart       |
| What depends on what?            | Relationship diagram        |
| How does risk change?            | Risk model                  |
| How do requirements map?         | Traceability / crosswalk    |
| Where are the controls?          | Control architecture        |
| How does data move?              | Data-flow diagram           |
| How do responsibilities divide?  | RACI / organizational model |
| How does risk compare?           | Heat map                    |
| How is performance changing?     | Trend chart                 |
| What needs management attention? | Executive dashboard         |
| How do systems integrate?        | Architecture diagram        |

---

# 46. The Golden Rule of GRC Visual Communication

A GRC diagram should answer **one primary question clearly**.

For example:

```text
What is the ERM lifecycle?
        ↓
Use a lifecycle diagram.
```

```text
How does a regulation map to evidence?
        ↓
Use a traceability diagram.
```

```text
Who is accountable for risk?
        ↓
Use a governance / responsibility diagram.
```

```text
Where is enterprise exposure increasing?
        ↓
Use a dashboard or trend visualization.
```

Avoid attempting to answer every question with one giant diagram.

---

# 47. Chapter 18 Final Model

The complete visual communication philosophy of Chapter 18 can be expressed as:

```text
                 COMPLEX GRC ENVIRONMENT
                           |
                           v
                    STRUCTURE THE DATA
                           |
                           v
                   IDENTIFY RELATIONSHIPS
                           |
                           v
                    SELECT VISUAL MODEL
                           |
                           v
                    CREATE DIAGRAM
                           |
                           v
                    VALIDATE ACCURACY
                           |
                           v
                  COMMUNICATE TO AUDIENCE
                           |
                           v
                  SUPPORT DECISION-MAKING
                           |
                           v
                   DRIVE GRC ACTION
```

The ultimate objective is not to produce attractive diagrams.

It is to transform complex GRC information into **understandable, traceable, decision-oriented visual communication**.

---

# Chapter 18 Summary

Chapter 18 established the importance of visual communication within Governance, Risk, and Compliance.

The chapter progressed from the fundamentals of diagram design through governance, risk, compliance, controls, cybersecurity, resilience, third-party risk, audit, evidence, metrics, automation, projects, threats, integrated GRC, and practical case studies.

The major concepts can be summarized as:

```text
GOVERNANCE
     ↓
RISK
     ↓
COMPLIANCE
     ↓
CONTROLS
     ↓
SECURITY
     ↓
RESILIENCE
     ↓
ASSURANCE
     ↓
EVIDENCE
     ↓
METRICS
     ↓
AUTOMATION
     ↓
INTEGRATION
     ↓
EXECUTIVE DECISION
```

A mature GRC professional should be capable of moving between three levels of visualization:

### Level 1 – Operational

```text
Process → Control → Evidence → Finding
```

### Level 2 – Management

```text
Risk → Compliance → Controls → Metrics → Actions
```

### Level 3 – Executive

```text
Business Objectives
        ↓
Enterprise Risk
        ↓
Compliance Exposure
        ↓
Control Effectiveness
        ↓
Business Resilience
        ↓
Management Decision
```

The final objective is **visual traceability**:

> **Every important business objective should be traceable to risks; risks to requirements and controls; controls to implementation and evidence; evidence to assurance; findings to remediation; and GRC information to informed management decisions.**

This completes **Chapter 18 – GRC Diagrams, Models & Visual Communication**.

