# 20.21 Risk and Control Relationships

This section defines the terminology used to understand how **risks, risk scenarios, controls, control objectives, processes, assets, requirements, evidence, findings, and remediation activities relate to one another**.

Understanding these relationships is fundamental to GRC because a mature GRC program does not simply maintain separate lists of risks and controls. It establishes **traceable relationships between business objectives, risks, controls, requirements, evidence, assurance, and management decisions**.

---

# 20.21.1 Core Risk-Control Concepts

| Term                             | Definition                                                                                        |
| -------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Risk-Control Relationship**    | Logical relationship showing how one or more controls address a specific risk.                    |
| **Risk-Control Mapping**         | Process of linking identified risks to controls designed to manage them.                          |
| **Risk-Control Matrix (RCM)**    | Matrix showing relationships between risks and controls.                                          |
| **Risk-Control Register**        | Structured repository containing risks, controls, owners, relationships, and related information. |
| **Risk-to-Control Traceability** | Ability to trace a risk to the controls intended to mitigate it.                                  |
| **Control-to-Risk Traceability** | Ability to identify which risks are addressed by a particular control.                            |
| **Risk Coverage**                | Degree to which identified risks are addressed by controls.                                       |
| **Control Coverage**             | Degree to which controls address identified risks or requirements.                                |
| **Risk Coverage Gap**            | Portion of a risk that is inadequately addressed by existing controls.                            |
| **Control Gap**                  | Missing or inadequate control addressing a risk or requirement.                                   |
| **Control Overlap**              | Multiple controls addressing substantially the same risk or objective.                            |
| **Control Dependency**           | Situation where the effectiveness of one control depends on another control.                      |
| **Control Chain**                | Sequence of related controls working together to manage a risk.                                   |
| **Risk Treatment Control**       | Control implemented as part of a risk treatment strategy.                                         |
| **Risk Mitigation Control**      | Control specifically designed to reduce risk likelihood or impact.                                |

---

# 20.21.2 Risk Hierarchy and Control Hierarchy

Risks and controls often exist at different levels.

### Risk hierarchy

**Enterprise Risk**

↓

**Risk Category**

↓

**Risk Domain**

↓

**Risk**

↓

**Risk Scenario**

↓

**Risk Event**

↓

**Cause**

↓

**Consequence**

### Control hierarchy

**Control Framework**

↓

**Control Domain**

↓

**Control Objective**

↓

**Control**

↓

**Control Procedure**

↓

**Control Activity**

↓

**Control Evidence**

This allows GRC professionals to establish detailed relationships between high-level enterprise risks and specific operational controls.

---

# 20.21.3 Risk-to-Control Relationship

A typical relationship can be represented as:

**Risk**

→ **Risk Scenario**

→ **Control Objective**

→ **Control**

→ **Control Activity**

→ **Evidence**

For example:

**Risk: Unauthorized Access**

→ Employee or attacker obtains privileged credentials

→ Ensure privileged access is appropriately authorized

→ Privileged Access Management Control

→ Quarterly privileged-access review

→ Access review report

This relationship demonstrates how an abstract risk becomes an actionable control.

---

# 20.21.4 Control Objective

| Term                     | Definition                                                                    |
| ------------------------ | ----------------------------------------------------------------------------- |
| **Control Objective**    | Desired outcome that a control is intended to achieve.                        |
| **Risk Objective**       | Desired outcome related to managing a specific risk.                          |
| **Security Objective**   | Desired security outcome such as confidentiality, integrity, or availability. |
| **Compliance Objective** | Desired outcome related to meeting applicable requirements.                   |
| **Control Outcome**      | Actual result produced by a control.                                          |
| **Control Purpose**      | Reason the control exists.                                                    |
| **Control Intent**       | Intended risk, compliance, security, or governance outcome of a control.      |

A useful distinction is:

> **Risk asks what could go wrong.**

> **Control objective asks what must be achieved to reduce that risk.**

> **Control asks what the organization will do to achieve the objective.**

---

# 20.21.5 Preventive and Detective Relationships

Controls may address different points in the risk scenario.

### Preventive

**Threat / Cause**

↓

**Preventive Control**

↓

**Risk Event Prevented**

Examples:

* MFA
* access authorization
* secure configuration
* segregation of duties

### Detective

**Risk Event**

↓

**Detective Control**

↓

**Detection**

Examples:

* SIEM monitoring
* access review
* vulnerability scanning
* anomaly detection

### Corrective

**Risk Event**

↓

**Corrective Control**

↓

**Recovery / Correction**

Examples:

* account disabling
* system restoration
* malware removal
* data recovery

A mature risk treatment strategy often uses **multiple control types together**.

---

# 20.21.6 Risk-Control Coverage

| Term                      | Definition                                                                               |
| ------------------------- | ---------------------------------------------------------------------------------------- |
| **Full Coverage**         | Controls adequately address the relevant risk scenario and its significant consequences. |
| **Partial Coverage**      | Controls address some but not all aspects of the risk.                                   |
| **Insufficient Coverage** | Controls exist but do not reduce the risk adequately.                                    |
| **No Coverage**           | No meaningful control addresses the identified risk.                                     |
| **Direct Coverage**       | Control directly addresses the risk.                                                     |
| **Indirect Coverage**     | Control contributes to risk reduction but does not directly address the risk.            |
| **Residual Exposure**     | Risk remaining despite implemented controls.                                             |
| **Coverage Gap**          | Portion of the risk not adequately addressed by controls.                                |
| **Control Strength**      | Relative ability of a control to reduce the relevant risk.                               |
| **Control Adequacy**      | Degree to which a control is sufficient for its intended purpose.                        |

---

# 20.21.7 Inherent Risk → Control → Residual Risk

One of the most important GRC relationships is:

**Inherent Risk**

↓

**Risk Treatment**

↓

**Controls**

↓

**Residual Risk**

For example:

**Inherent Risk:**
Unauthorized privileged access

↓

**Controls:**

* MFA
* PAM
* least privilege
* privileged access review
* logging
* monitoring

↓

**Residual Risk:**
Remaining possibility of unauthorized privileged access despite controls.

The residual risk is then compared against:

**Risk Appetite**

and

**Risk Tolerance**

to determine whether additional treatment is necessary.

---

# 20.21.8 Risk Treatment and Control Relationships

| Risk Treatment | Control Relationship                                                               |
| -------------- | ---------------------------------------------------------------------------------- |
| **Avoid**      | Eliminate the activity or condition creating the risk.                             |
| **Reduce**     | Implement controls to reduce likelihood or impact.                                 |
| **Transfer**   | Use insurance, contracts, outsourcing, or other mechanisms to transfer/share risk. |
| **Accept**     | Retain the risk without additional treatment when justified.                       |
| **Share**      | Share risk with another party through contractual or operational arrangements.     |

Controls are most directly associated with **risk reduction**, but controls may also support risk transfer and acceptance decisions.

---

# 20.21.9 One Risk → Multiple Controls

A single risk may require multiple controls.

Example:

### Risk

**Ransomware causes prolonged business disruption.**

Controls:

1. Endpoint protection
2. Email security
3. Security awareness
4. Network segmentation
5. Vulnerability management
6. Backup
7. Immutable backup
8. Incident response
9. Business continuity
10. Disaster recovery

Therefore:

**One Risk → Many Controls**

This is normal and often necessary.

---

# 20.21.10 One Control → Multiple Risks

The reverse is also possible.

For example:

### Multi-Factor Authentication

may reduce:

* account compromise;
* credential theft;
* unauthorized access;
* privilege abuse;
* phishing impact;
* remote-access risk.

Therefore:

**One Control → Multiple Risks**

This is why control rationalization is important.

---

# 20.21.11 Many-to-Many Risk-Control Relationship

The most realistic GRC model is:

**Many Risks**

↕

**Many Controls**

For example:

| Risk                      | Controls                                          |
| ------------------------- | ------------------------------------------------- |
| Account compromise        | MFA, PAM, access review, monitoring               |
| Data breach               | DLP, encryption, access control, monitoring       |
| Insider threat            | segregation of duties, monitoring, access reviews |
| Ransomware                | EDR, backup, segmentation, awareness              |
| Regulatory non-compliance | policies, training, monitoring, audits            |

And one control may appear against several risks.

This is known as a **many-to-many relationship**.

---

# 20.21.12 Risk-Control Matrix

A Risk-Control Matrix can be structured as:

| Risk ID | Risk                | Control ID | Control       | Coverage | Owner    |
| ------- | ------------------- | ---------- | ------------- | -------- | -------- |
| R-001   | Unauthorized access | C-001      | MFA           | Full     | IAM      |
| R-001   | Unauthorized access | C-002      | Access Review | Partial  | IAM      |
| R-002   | Data breach         | C-003      | Encryption    | Full     | Security |
| R-002   | Data breach         | C-004      | DLP           | Partial  | Security |
| R-003   | Ransomware          | C-005      | EDR           | Full     | SOC      |
| R-003   | Ransomware          | C-006      | Backup        | Full     | IT       |

This provides a direct view of **risk coverage**.

---

# 20.21.13 Risk-Control Traceability

A mature traceability chain is:

**Business Objective**

↓

**Risk**

↓

**Risk Scenario**

↓

**Risk Treatment**

↓

**Control Objective**

↓

**Control**

↓

**Control Activity**

↓

**Evidence**

↓

**Control Test**

↓

**Finding**

↓

**Remediation**

↓

**Residual Risk**

↓

**Risk Acceptance / Further Treatment**

This is one of the most important models in enterprise GRC.

---

# 20.21.14 Control-to-Requirement Relationship

Controls are not only connected to risks.

They can also be connected to:

* laws;
* regulations;
* standards;
* frameworks;
* policies;
* contracts;
* customer requirements.

Example:

**MFA Control**

→ ISO/IEC 27001

→ NIST CSF

→ PCI DSS

→ Internal Security Policy

→ Customer Security Requirement

Therefore:

**One Control → Multiple Requirements**

This is the foundation of **cross-framework control reuse**.

---

# 20.21.15 Risk-Control-Requirement Model

A comprehensive relationship is:

**Business Objective**

↓

**Risk**

↓

**Requirement**

↓

**Control Objective**

↓

**Control**

↓

**Evidence**

↓

**Assessment**

↓

**Finding**

↓

**Remediation**

This model connects **risk management and compliance management** rather than treating them as separate disciplines.

---

# 20.21.16 Risk-Control-Asset Relationship

Controls operate against assets, processes, systems, people, or information.

A useful relationship is:

**Risk**

→ **Asset**

→ **Control**

For example:

**Data Breach Risk**

→ Customer Database

→ Encryption

→ Access Control

→ DLP

→ Monitoring

The asset may therefore serve as the bridge between the risk and the controls.

---

# 20.21.17 Risk-Control-Process Relationship

Another important relationship is:

**Risk**

→ **Business Process**

→ **Control**

Example:

**Payment Fraud Risk**

→ Payment Processing

→ Segregation of Duties

→ Transaction Monitoring

→ Approval Control

This allows organizations to determine which business processes are exposed to which risks and how those risks are controlled.

---

# 20.21.18 Risk-Control-Technology Relationship

A technical GRC model may be:

**Risk**

→ **Control**

→ **Technology**

For example:

**Unauthorized Access Risk**

→ MFA Control

→ Microsoft Entra ID

→ Conditional Access

→ Authentication Logs

This enables GRC teams to connect abstract controls with actual technology implementations.

---

# 20.21.19 Control Dependency

Some controls cannot operate effectively without other controls.

Example:

**Access Review**

depends on:

→ Accurate identity inventory

→ Accurate access records

→ Defined ownership

→ User lifecycle management

Therefore:

**Control A → depends on → Control B**

Control dependencies are important because a control may appear effective independently but fail because its supporting controls are weak.

---

# 20.21.20 Control Chain

A control chain may operate as:

**Prevent**

→ **Detect**

→ **Respond**

→ **Recover**

Example:

**Phishing**

↓

Email Security

↓

User Awareness

↓

MFA

↓

SIEM Detection

↓

SOC Investigation

↓

Account Containment

↓

Password Reset

↓

Recovery

This represents **defense in depth**.

---

# 20.21.21 Compensating Control Relationship

Sometimes the primary control cannot be implemented.

Example:

**Primary Control**

Automated privileged-access approval

↓

Not technically supported by legacy system

↓

**Compensating Controls**

* manual approval;
* enhanced monitoring;
* restricted administrator access;
* periodic independent review.

The compensating control must provide **sufficient risk reduction**, not merely exist as a substitute.

---

# 20.21.22 Control Effectiveness Relationship

Control effectiveness can be analyzed through:

**Design Effectiveness**

*

**Implementation**

*

**Operating Effectiveness**

=

**Overall Control Effectiveness**

A control can fail in several ways:

### Design Failure

The control is fundamentally inadequate.

### Implementation Failure

The control was designed correctly but not properly implemented.

### Operating Failure

The control exists but is not consistently performed.

### Evidence Failure

The control may operate, but sufficient evidence is unavailable.

---

# 20.21.23 Risk-Control-Finding Relationship

An important audit relationship is:

**Risk**

↓

**Control**

↓

**Control Failure**

↓

**Finding**

↓

**Root Cause**

↓

**Corrective Action**

↓

**Remediation**

↓

**Validation**

↓

**Closure**

This connects risk management with audit and compliance remediation.

---

# 20.21.24 Risk-Control-Evidence Relationship

A control should generally produce or depend upon evidence.

Example:

**Control: Quarterly Access Review**

↓

**Activity: Review privileged accounts**

↓

**Evidence: Signed access review report**

↓

**Test: Verify review completed**

↓

**Conclusion: Operating effectiveness**

This creates an **evidence chain**.

---

# 20.21.25 Risk-Control-Exception Relationship

Sometimes an organization cannot meet a control requirement.

The relationship may become:

**Requirement**

↓

**Control**

↓

**Exception**

↓

**Risk Assessment**

↓

**Compensating Control**

↓

**Risk Acceptance**

↓

**Expiration / Review**

An exception should therefore not simply mean:

> "Control not implemented."

It should trigger a structured **risk-based decision process**.

---

# 20.21.26 Risk Acceptance Relationship

A risk acceptance decision can be represented as:

**Risk**

↓

**Inherent Risk**

↓

**Controls**

↓

**Residual Risk**

↓

**Risk Appetite / Tolerance**

↓

**Decision**

→ Treat further

or

→ Accept

or

→ Transfer

or

→ Avoid

The **risk owner**, not merely the control owner, should normally be accountable for the risk decision.

---

# 20.21.27 Risk Aggregation

Individual risks may combine into broader risks.

Example:

**Phishing Risk**

**Credential Theft Risk**

**MFA Failure Risk**

**Privileged Access Risk**

↓

### Identity and Access Risk

↓

### Cybersecurity Risk

↓

### Enterprise Risk

This is known as **risk aggregation** or **risk hierarchy**.

---

# 20.21.28 Risk-Control Relationship Quality

A strong relationship should answer:

1. **What risk does the control address?**
2. **What risk scenario does it address?**
3. **What control objective does it achieve?**
4. **How does it reduce likelihood or impact?**
5. **Who owns the control?**
6. **What evidence demonstrates operation?**
7. **How is it tested?**
8. **What requirements does it satisfy?**
9. **What assets or processes does it protect?**
10. **What residual risk remains?**

If these questions cannot be answered, the risk-control relationship may be incomplete.

---

# 20.21.29 Risk-Control Relationship Types

The principal relationship types are:

### Direct Mitigation

Control directly reduces the risk.

### Indirect Mitigation

Control contributes to risk reduction indirectly.

### Preventive

Control attempts to prevent the risk event.

### Detective

Control identifies the risk event.

### Corrective

Control reduces consequences or restores operations.

### Compensating

Alternative control provides equivalent risk treatment.

### Supporting

Control enables another control to operate effectively.

### Monitoring

Control provides visibility into risk conditions.

### Governance

Control establishes accountability, policy, oversight, or decision-making.

---

# 20.21.30 Risk-Control Modeling Example

Consider:

### Business Objective

Maintain availability of critical customer services.

↓

### Risk

Critical service outage.

↓

### Risk Causes

* hardware failure;
* cyberattack;
* cloud outage;
* human error;
* supplier failure.

↓

### Controls

* redundancy;
* backup;
* disaster recovery;
* monitoring;
* incident response;
* business continuity;
* supplier resilience.

↓

### Evidence

* backup reports;
* DR test results;
* monitoring logs;
* incident records;
* supplier assessments.

↓

### Assurance

* control testing;
* DR exercise;
* audit;
* management review.

↓

### Residual Risk

Remaining probability and impact of prolonged service outage.

↓

### Decision

Accept / Treat / Transfer / Avoid.

This is the **complete risk-control lifecycle**.

---

# 20.21.31 Key Risk-Control Relationships to Remember

For the GRC Knowledge Base, the most important relationships are:

**Risk → Control**

**Risk → Multiple Controls**

**Control → Multiple Risks**

**Risk → Requirement**

**Requirement → Control**

**Risk → Asset**

**Risk → Process**

**Risk → Technology**

**Control → Evidence**

**Control → Test**

**Control → Finding**

**Finding → Remediation**

**Control → Multiple Frameworks**

**Control → Control Dependency**

**Inherent Risk → Controls → Residual Risk**

**Residual Risk → Risk Appetite → Risk Decision**

**Risk → Control → Evidence → Assurance**

---

# 20.21.32 Final Risk-Control Knowledge Model

The complete enterprise GRC relationship can be expressed as:

> **Business Objective**
> ↓
> **Risk**
> ↓
> **Risk Scenario**
> ↓
> **Cause / Threat**
> ↓
> **Potential Consequence**
> ↓
> **Risk Treatment**
> ↓
> **Control Objective**
> ↓
> **Control**
> ↓
> **Control Activity**
> ↓
> **Process / System / Asset**
> ↓
> **Evidence**
> ↓
> **Control Testing**
> ↓
> **Finding / Exception**
> ↓
> **Corrective Action**
> ↓
> **Remediation**
> ↓
> **Residual Risk**
> ↓
> **Risk Acceptance / Further Treatment**
> ↓
> **Monitoring**
> ↓
> **Continuous Improvement**

This relationship model is at the heart of a mature GRC program because it connects **strategy, risk, compliance, controls, operations, technology, assurance, and executive decision-making into one traceable system**.



