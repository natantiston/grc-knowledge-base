# 18.9 Security Architecture and Defense Diagrams

### Part 1 – Defense-in-Depth Model

**Defense in depth** is a cybersecurity strategy that uses multiple, overlapping layers of security controls so that the failure or bypass of one control does not automatically result in a successful compromise.

From a GRC perspective, the model is important because it demonstrates how security controls work together across **people, processes, technology, infrastructure, applications, identities, data, and governance**.

The fundamental concept is:

```text
Threat
  ↓
Layer 1
  ↓
Layer 2
  ↓
Layer 3
  ↓
Layer 4
  ↓
Layer 5
  ↓
Protected Asset
```

The objective is not to create one perfect security control. The objective is to create **multiple complementary controls that collectively reduce risk**.

---

# 1. What Is Defense in Depth?

Defense in depth means implementing multiple security layers across different points of the attack surface.

A simplified model is:

```text
                    THREAT
                       ↓
               ┌─────────────┐
               │ Perimeter   │
               │ Security    │
               └─────────────┘
                       ↓
               ┌─────────────┐
               │ Network     │
               │ Security    │
               └─────────────┘
                       ↓
               ┌─────────────┐
               │ Endpoint    │
               │ Security    │
               └─────────────┘
                       ↓
               ┌─────────────┐
               │ Application │
               │ Security    │
               └─────────────┘
                       ↓
               ┌─────────────┐
               │ Data        │
               │ Protection  │
               └─────────────┘
                       ↓
                  DATA / ASSET
```

If one layer fails, another layer can potentially prevent, detect, or limit the attack.

---

# 2. Why Defense in Depth Is Important

Cybersecurity controls are not perfect.

A firewall can be misconfigured.

An employee can click a phishing link.

A password can be compromised.

A vulnerability can remain unpatched.

A security monitoring system can miss an attack.

Defense in depth recognizes these realities.

```text
Control Failure
      ↓
Next Security Layer
      ↓
Detection / Prevention
      ↓
Attack Contained
```

Therefore, defense in depth reduces dependence on a single security mechanism.

---

# 3. Single-Layer Versus Defense-in-Depth

A single-control approach might look like:

```text
Threat
  ↓
Firewall
  ↓
Data
```

If the firewall is bypassed:

```text
Threat
  ↓
Firewall Bypassed
  ↓
Data
```

A defense-in-depth approach looks like:

```text
Threat
  ↓
Firewall
  ↓
Network Segmentation
  ↓
Identity Controls
  ↓
Endpoint Protection
  ↓
Application Security
  ↓
Data Protection
  ↓
Monitoring
  ↓
Data
```

Multiple controls create multiple opportunities to stop or detect the attack.

---

# 4. The Seven-Layer Security Model

A practical defense-in-depth model can include:

```text
1. Governance
2. Physical Security
3. Perimeter Security
4. Network Security
5. Endpoint Security
6. Application Security
7. Data Security
```

These layers should not be interpreted as a universal mandatory architecture. Organizations can adapt the model to their environment.

---

# 5. Governance Layer

Governance establishes the policies, standards, accountability, and risk decisions supporting cybersecurity.

```text
Governance
    ↓
Policies
    ↓
Standards
    ↓
Risk Management
    ↓
Security Requirements
    ↓
Technical Controls
```

Examples include:

```text
Security Policy
Risk Appetite
Security Standards
Asset Management
Security Roles
Exception Management
Third-Party Governance
Security Awareness
```

From a GRC perspective, governance provides the foundation for the technical security architecture.

---

# 6. Physical Security Layer

Physical security protects facilities, equipment, and physical infrastructure.

Examples include:

```text
Access Cards
Security Guards
CCTV
Biometric Access
Visitor Management
Secure Server Rooms
Environmental Controls
Fire Protection
```

The model becomes:

```text
Physical Threat
      ↓
Physical Controls
      ↓
Protected Infrastructure
```

A sophisticated cybersecurity architecture can still be compromised if an attacker gains unauthorized physical access.

---

# 7. Perimeter Security Layer

Perimeter controls protect the organization's external boundaries.

Examples include:

```text
Firewalls
Web Application Firewalls
DDoS Protection
Secure Gateways
Email Security
DNS Security
Network Access Controls
```

A simplified architecture:

```text
Internet
   ↓
DDoS Protection
   ↓
Firewall
   ↓
WAF / Secure Gateway
   ↓
Internal Environment
```

Perimeter controls remain useful even though modern security architectures increasingly emphasize identity and Zero Trust.

---

# 8. Network Security Layer

Network security controls protect communications and network segments.

Examples include:

```text
Network Segmentation
VLANs
IDS / IPS
Network Firewalls
Microsegmentation
Secure Routing
Network Monitoring
VPN
```

A segmented environment might look like:

```text
Internet
   ↓
DMZ
   ↓
Application Network
   ↓
Database Network
   ↓
Restricted Data
```

The purpose is to prevent unrestricted lateral movement.

---

# 9. Endpoint Security Layer

Endpoints can become an entry point for attackers.

Examples include:

```text
EDR
Antivirus
Host Firewall
Device Encryption
Patch Management
Application Control
Device Management
Endpoint Hardening
```

The model is:

```text
User
 ↓
Endpoint
 ↓
Security Controls
 ↓
Corporate Environment
```

If an endpoint is compromised, endpoint controls can detect or limit malicious activity.

---

# 10. Identity Security Layer

Identity is increasingly one of the most important security layers.

Examples include:

```text
Multi-Factor Authentication
Single Sign-On
Role-Based Access Control
Privileged Access Management
Identity Governance
Conditional Access
Password Policies
Access Reviews
```

A simplified model:

```text
USER
 ↓
IDENTITY
 ↓
AUTHENTICATION
 ↓
AUTHORIZATION
 ↓
RESOURCE
```

The principle is:

> **The user should receive only the access required for the authorized activity.**

---

# 11. Application Security Layer

Applications should have security controls throughout their lifecycle.

```text
Requirements
    ↓
Secure Design
    ↓
Secure Development
    ↓
Testing
    ↓
Deployment
    ↓
Monitoring
```

Controls may include:

```text
Secure Coding
SAST
DAST
Dependency Scanning
API Security
Application Authentication
Input Validation
Secrets Management
Vulnerability Management
```

Application security reduces the possibility that attackers can exploit weaknesses in business applications.

---

# 12. Data Security Layer

Data is ultimately one of the most important assets being protected.

Controls include:

```text
Encryption
Data Classification
Data Loss Prevention
Access Controls
Tokenization
Backup
Retention
Secure Disposal
Database Security
Data Monitoring
```

The model is:

```text
DATA
 ↓
CLASSIFICATION
 ↓
ACCESS CONTROL
 ↓
ENCRYPTION
 ↓
MONITORING
 ↓
BACKUP / RECOVERY
```

---

# 13. Monitoring and Detection Layer

Defense in depth is not limited to prevention.

Detection is equally important.

```text
Security Controls
      ↓
Logs
      ↓
Monitoring
      ↓
Detection
      ↓
Alert
      ↓
Investigation
```

Examples include:

```text
SIEM
SOC
EDR
NDR
Cloud Monitoring
Identity Monitoring
DLP Monitoring
Application Monitoring
```

A control that prevents an attack is valuable, but a control that detects a bypass can provide another layer of defense.

---

# 14. Response Layer

When prevention fails, incident response becomes another layer.

```text
Attack
 ↓
Detection
 ↓
Investigation
 ↓
Containment
 ↓
Eradication
 ↓
Recovery
```

This means defense in depth extends beyond preventive controls.

It includes the organization's ability to **respond and recover**.

---

# 15. Recovery Layer

Recovery protects the organization's ability to restore operations.

Examples include:

```text
Backups
Disaster Recovery
Business Continuity
Redundant Infrastructure
Recovery Testing
Crisis Management
```

The model is:

```text
Security Incident
      ↓
Service Disruption
      ↓
Recovery Strategy
      ↓
Restoration
      ↓
Business Continuity
```

Recovery controls reduce the potential business impact of successful attacks.

---

# 16. Human Layer

Employees are an important component of defense in depth.

Controls include:

```text
Security Awareness
Phishing Training
Role-Based Training
Acceptable Use Policies
Security Procedures
Incident Reporting
Background Screening
```

The model is:

```text
EMPLOYEE
   ↓
AWARENESS
   ↓
CORRECT DECISION
   ↓
THREAT AVOIDED
```

People should therefore be treated as part of the security architecture rather than simply as a security weakness.

---

# 17. Process Layer

Security processes provide another defensive layer.

Examples include:

```text
Vulnerability Management
Patch Management
Access Reviews
Change Management
Incident Management
Risk Management
Supplier Management
Security Testing
```

For example:

```text
Vulnerability
     ↓
Identification
     ↓
Assessment
     ↓
Prioritization
     ↓
Remediation
     ↓
Validation
```

This creates continuous operational defense.

---

# 18. Defense-in-Depth Architecture

A more complete model is:

```text
                         THREATS
                            ↓
                 ┌────────────────────┐
                 │     GOVERNANCE      │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │ PHYSICAL SECURITY  │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │ PERIMETER SECURITY │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │  NETWORK SECURITY  │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │ IDENTITY SECURITY  │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │ ENDPOINT SECURITY  │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │ APPLICATION        │
                 │ SECURITY           │
                 └────────────────────┘
                            ↓
                 ┌────────────────────┐
                 │   DATA SECURITY    │
                 └────────────────────┘
                            ↓
                          DATA
```

Monitoring, detection, response, and recovery operate across these layers.

---

# 19. Preventive, Detective, and Corrective Layers

Defense in depth can also be viewed through control types.

```text
                 SECURITY CONTROLS
                        ↓
        ┌───────────────┼────────────────┐
        ↓               ↓                ↓
    PREVENTIVE       DETECTIVE        CORRECTIVE
        ↓               ↓                ↓
     Stop Attack     Detect Attack    Recover
```

Examples:

| Control Type | Examples                      |
| ------------ | ----------------------------- |
| Preventive   | Firewall, MFA, encryption     |
| Detective    | SIEM, IDS, EDR                |
| Corrective   | Backup, recovery, remediation |

A mature architecture combines all three.

---

# 20. Example: Phishing Attack

Consider a phishing attack.

Defense in depth might provide:

```text
Phishing Email
      ↓
Email Security
      ↓
User Awareness
      ↓
MFA
      ↓
Endpoint Protection
      ↓
Identity Monitoring
      ↓
SIEM Detection
      ↓
Incident Response
```

Even if the employee clicks the malicious link, additional controls remain available.

---

# 21. Example: Ransomware Attack

A ransomware attack can encounter multiple layers:

```text
Initial Access
      ↓
Email Security
      ↓
Endpoint Protection
      ↓
Application Controls
      ↓
Network Segmentation
      ↓
EDR Detection
      ↓
Backup Protection
      ↓
Incident Response
      ↓
Recovery
```

The architecture attempts to prevent the attack, detect it, contain it, and recover from it.

---

# 22. Example: Compromised Account

If an attacker obtains valid credentials:

```text
Compromised Credentials
        ↓
MFA
        ↓
Conditional Access
        ↓
Least Privilege
        ↓
Privileged Access Controls
        ↓
Network Segmentation
        ↓
Behavior Monitoring
        ↓
SIEM Alert
        ↓
Account Disablement
```

This demonstrates why identity security should not depend exclusively on passwords.

---

# 23. Defense in Depth and Zero Trust

Defense in depth and Zero Trust are related but different concepts.

Defense in depth asks:

> **How many layers of protection exist?**

Zero Trust asks:

> **What should be trusted, and under what conditions should access be granted?**

They can operate together:

```text
              ZERO TRUST
                  +
          DEFENSE IN DEPTH
                  ↓
       MULTIPLE SECURITY LAYERS
                  ↓
       REDUCED ATTACK EXPOSURE
```

A Zero Trust architecture can therefore be one component of a broader defense-in-depth strategy.

---

# 24. Defense in Depth and Cloud

Cloud environments require layered controls even when infrastructure is managed by a cloud provider.

```text
Cloud Environment
       ↓
Identity
       ↓
Network
       ↓
Workload
       ↓
Application
       ↓
Data
       ↓
Monitoring
```

Examples include:

```text
IAM
MFA
Cloud Security Groups
Network Segmentation
Workload Protection
Secrets Management
Encryption
Cloud Logging
Security Monitoring
```

Cloud security responsibilities must also be aligned with the applicable shared-responsibility model.

---

# 25. Defense in Depth and Hybrid Environments

For hybrid environments:

```text
                    ENTERPRISE
                        ↓
        ┌───────────────┴───────────────┐
        ↓                               ↓
   ON-PREMISES                         CLOUD
        ↓                               ↓
 Network Security                  Cloud IAM
 Endpoint Security                 Cloud Network
 Identity                          Workload Security
 Data Security                     Data Security
        ↓                               ↓
        └───────────────┬───────────────┘
                        ↓
                    MONITORING
                        ↓
                       SOC
```

The objective is consistent security coverage across environments.

---

# 26. Defense in Depth and Third Parties

Third-party connections can introduce additional attack paths.

```text
THIRD PARTY
     ↓
CONTRACTUAL CONTROLS
     ↓
IDENTITY CONTROLS
     ↓
NETWORK CONTROLS
     ↓
APPLICATION CONTROLS
     ↓
DATA CONTROLS
     ↓
MONITORING
```

This demonstrates how third-party risk management can become part of technical defense in depth.

---

# 27. Defense in Depth and GRC

GRC provides the governance structure behind the technical architecture.

```text
BUSINESS OBJECTIVES
        ↓
RISK ASSESSMENT
        ↓
SECURITY REQUIREMENTS
        ↓
CONTROL DESIGN
        ↓
CONTROL IMPLEMENTATION
        ↓
CONTROL TESTING
        ↓
RISK MONITORING
```

The architecture should therefore be driven by risk rather than by simply accumulating security products.

---

# 28. Risk-Based Defense in Depth

Not every asset requires identical layers.

A critical system may require:

```text
High-Risk Asset
     ↓
Strong Authentication
     ↓
Network Segmentation
     ↓
Application Security
     ↓
Encryption
     ↓
Privileged Access
     ↓
Continuous Monitoring
     ↓
Enhanced Recovery
```

A lower-risk system may require fewer controls.

This creates:

> **Risk-based defense in depth.**

---

# 29. Defense Layers and Risk Reduction

Each layer should contribute to reducing risk.

```text
Inherent Risk
      ↓
Security Layer 1
      ↓
Reduced Exposure
      ↓
Security Layer 2
      ↓
Further Reduction
      ↓
Security Layer 3
      ↓
Residual Risk
```

The goal is not necessarily to eliminate risk.

The goal is to reduce risk to an acceptable level.

---

# 30. Control Overlap

Some controls intentionally overlap.

For example:

```text
MFA
 +
Conditional Access
 +
Privileged Access Management
 +
Identity Monitoring
```

All address identity-related risks from different perspectives.

If one control fails, others may still provide protection.

---

# 31. Control Independence

Defense in depth is stronger when controls do not depend entirely on the same mechanism.

For example:

```text
Firewall
      +
EDR
      +
MFA
      +
Network Segmentation
      +
SIEM
```

If a single firewall configuration is bypassed, the other controls can continue operating.

This creates **control diversity**.

---

# 32. Avoiding Common Dependencies

An organization should identify situations where multiple security controls depend on the same underlying component.

For example:

```text
Authentication
     ↓
Single Identity Provider
     ↓
All Applications
```

If that identity provider fails or is compromised, multiple controls may be affected simultaneously.

Therefore:

```text
Defense in Depth
        ↓
Identify Common Dependencies
        ↓
Reduce Single Points of Failure
```

---

# 33. Security Architecture Review

A GRC or security architecture review can ask:

```text
What are we protecting?
        ↓
What are the threats?
        ↓
What controls exist?
        ↓
Where are the gaps?
        ↓
Where are the dependencies?
        ↓
Where can an attacker move laterally?
        ↓
What happens if a control fails?
```

This turns defense in depth into a practical risk assessment exercise.

---

# 34. Attack Path Perspective

Defense in depth can be visualized against an attack path:

```text
Attacker
   ↓
Initial Access
   ↓
Execution
   ↓
Persistence
   ↓
Privilege Escalation
   ↓
Lateral Movement
   ↓
Data Access
   ↓
Exfiltration
```

Security controls should be mapped across the attack path.

```text
Initial Access → Email Security
Execution → EDR
Privilege → PAM
Lateral Movement → Segmentation
Data Access → IAM
Exfiltration → DLP
Detection → SIEM
```

This allows organizations to identify where defensive coverage is weak.

---

# 35. Defense Coverage Matrix

A GRC team can create a control coverage matrix.

| Attack Stage         | Security Control | Control Type         | Coverage |
| -------------------- | ---------------- | -------------------- | -------- |
| Initial Access       | Email Security   | Preventive           | Strong   |
| Execution            | EDR              | Detective/Preventive | Strong   |
| Privilege Escalation | PAM              | Preventive           | Medium   |
| Lateral Movement     | Segmentation     | Preventive           | Medium   |
| Data Access          | IAM              | Preventive           | Strong   |
| Exfiltration         | DLP              | Detective/Preventive | Medium   |

This can reveal security gaps and control concentration.

---

# 36. Defense-in-Depth Maturity

Organizations can assess maturity progressively.

```text
LEVEL 1
Basic Controls
     ↓
LEVEL 2
Multiple Security Controls
     ↓
LEVEL 3
Integrated Controls
     ↓
LEVEL 4
Risk-Based Layered Defense
     ↓
LEVEL 5
Adaptive and Continuously Optimized Defense
```

A mature organization continuously evaluates whether its defensive layers remain effective.

---

# 37. Metrics for Defense in Depth

Potential metrics include:

```text
Control Coverage
Control Effectiveness
Critical Asset Coverage
MFA Coverage
Endpoint Coverage
Logging Coverage
Vulnerability Remediation
Network Segmentation Coverage
Privileged Account Coverage
Detection Coverage
Backup Recovery Success
```

For example:

```text
Critical Assets Covered       98%
MFA Coverage                  97%
EDR Coverage                  99%
Central Logging Coverage      94%
Privileged Accounts Reviewed  100%
```

Values are illustrative.

---

# 38. Executive Defense-in-Depth Dashboard

Senior management could view:

```text
DEFENSE-IN-DEPTH STATUS

Critical Assets                 42
Security Controls               185
Critical Control Gaps             6
MFA Coverage                    97%
EDR Coverage                    99%
Logging Coverage                94%
High-Risk Vulnerabilities        12
Overdue Remediation               4
```

The dashboard should focus on **risk exposure and control effectiveness**, not simply the number of security tools deployed.

---

# 39. Common Defense-in-Depth Weaknesses

Organizations should watch for:

```text
Single Security Control
Single Identity Dependency
Poor Network Segmentation
Excessive Privileges
Unmonitored Assets
Unpatched Systems
Insufficient Logging
Weak Backup Protection
Poor Third-Party Controls
Untrained Users
```

A large number of security products does not automatically mean strong defense in depth.

---

# 40. Technology Sprawl Versus Effective Defense

A common mistake is:

```text
More Tools
   ↓
More Complexity
   ↓
More Configuration Errors
   ↓
Potentially More Risk
```

Effective defense in depth instead focuses on:

```text
Risk
 ↓
Required Protection
 ↓
Appropriate Controls
 ↓
Integration
 ↓
Testing
 ↓
Effectiveness
```

The objective is **effective layered protection**, not maximum technology consumption.

---

# 41. Defense-in-Depth and Control Testing

Every important layer should be tested.

```text
CONTROL
   ↓
IMPLEMENTED?
   ↓
OPERATING?
   ↓
EFFECTIVE?
   ↓
RISK REDUCED?
```

For example:

```text
MFA
 ↓
Enabled?
 ↓
Applied to Critical Systems?
 ↓
Bypass Tested?
 ↓
Evidence Available?
 ↓
Effective?
```

This connects security architecture directly with GRC assurance.

---

# 42. Defense-in-Depth and Risk Register

Security architecture gaps can become formal risks.

```text
ARCHITECTURE GAP
      ↓
RISK IDENTIFICATION
      ↓
RISK ASSESSMENT
      ↓
CONTROL REQUIREMENT
      ↓
REMEDIATION
      ↓
VALIDATION
```

Example:

```text
Risk:
Insufficient network segmentation

Treatment:
Implement segmentation

Control:
Network security zones

Evidence:
Architecture + firewall rules

Validation:
Security testing
```

---

# 43. Defense-in-Depth and Compliance

Many security and compliance frameworks require organizations to implement layered controls, although the exact requirements vary.

A GRC mapping may look like:

```text
Requirement
     ↓
Control Objective
     ↓
Security Control
     ↓
Defense Layer
     ↓
Evidence
     ↓
Testing
```

For example:

```text
Access Control Requirement
        ↓
Identity Security
        ↓
MFA
        ↓
Access Logs
        ↓
Control Testing
```

This makes the architecture auditable.

---

# 44. Defense-in-Depth Traceability

A mature GRC environment can establish:

```text
BUSINESS ASSET
      ↓
THREAT
      ↓
RISK
      ↓
CONTROL OBJECTIVE
      ↓
SECURITY CONTROL
      ↓
DEFENSE LAYER
      ↓
CONTROL EVIDENCE
      ↓
CONTROL TEST
      ↓
RESIDUAL RISK
```

This provides traceability between business risk and technical architecture.

---

# 45. Example: Critical Customer Database

Consider a customer database.

```text
                         THREAT
                            ↓
                    ┌──────────────┐
                    │  Firewall    │
                    └──────────────┘
                            ↓
                    ┌──────────────┐
                    │ Segmentation │
                    └──────────────┘
                            ↓
                    ┌──────────────┐
                    │ IAM / PAM    │
                    └──────────────┘
                            ↓
                    ┌──────────────┐
                    │ Database     │
                    │ Security     │
                    └──────────────┘
                            ↓
                    ┌──────────────┐
                    │ Encryption   │
                    └──────────────┘
                            ↓
                    ┌──────────────┐
                    │ Monitoring   │
                    └──────────────┘
                            ↓
                    CUSTOMER DATA
```

If an attacker bypasses one layer, additional controls remain.

---

# 46. Defense-in-Depth Operating Model

A complete organizational model can be viewed as:

```text
                    GOVERNANCE
                        ↓
                  RISK MANAGEMENT
                        ↓
                SECURITY ARCHITECTURE
                        ↓
        ┌───────────────┼────────────────┐
        ↓               ↓                ↓
      PEOPLE          PROCESS         TECHNOLOGY
        ↓               ↓                ↓
        └───────────────┼────────────────┘
                        ↓
                 SECURITY CONTROLS
                        ↓
                 MONITORING / SOC
                        ↓
                 INCIDENT RESPONSE
                        ↓
                    RECOVERY
                        ↓
                 RISK REASSESSMENT
```

This shows that defense in depth is an **operating model**, not simply a network diagram.

---

# 47. GRC Perspective

For a GRC professional, defense in depth should be evaluated through five questions:

```text
1. What risks are we trying to reduce?

2. Which security layers address those risks?

3. What happens if one control fails?

4. Are the controls operating effectively?

5. What residual risk remains?
```

These questions transform a technical architecture concept into a GRC assessment methodology.

---

# 48. Key Principles

A mature defense-in-depth strategy should:

```text
1. Use multiple complementary security layers.
2. Avoid dependence on a single security control.
3. Protect people, processes, technology, and data.
4. Combine preventive, detective, and corrective controls.
5. Incorporate identity and access security.
6. Segment critical systems and data.
7. Monitor security events across layers.
8. Maintain strong incident-response capabilities.
9. Maintain reliable recovery capabilities.
10. Regularly test control effectiveness.
11. Identify common dependencies and single points of failure.
12. Align defensive layers with business risk.
```

The central principle is:

> **No single security control should be expected to stop every attack. Effective cybersecurity uses multiple, coordinated layers that collectively prevent, detect, contain, respond to, and recover from threats.**

---

# 49. Final Integrated Defense-in-Depth Model

The complete model can be represented as:

```text
                              THREATS
                                 ↓
                       ┌─────────────────┐
                       │   GOVERNANCE    │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ PHYSICAL        │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ PERIMETER       │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ NETWORK         │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ IDENTITY        │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ ENDPOINT        │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ APPLICATION     │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ DATA            │
                       │ SECURITY        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ MONITORING &    │
                       │ DETECTION       │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ INCIDENT        │
                       │ RESPONSE        │
                       └─────────────────┘
                                 ↓
                       ┌─────────────────┐
                       │ RECOVERY        │
                       └─────────────────┘
                                 ↓
                              ASSETS
```

The ultimate GRC objective is to ensure that these layers are **risk-driven, properly implemented, independently tested, continuously monitored, and demonstrably effective**. This allows the organization to maintain protection even when individual controls fail, while providing management with visibility into security coverage and residual risk.


# 18.8 Privacy and Data Protection Diagrams

### Part 2 – Personal Data Processing Flow

A **Personal Data Processing Flow** illustrates how personal data moves through an organization from collection to use, storage, sharing, retention, and eventual deletion or disposal.

From a GRC perspective, this diagram is particularly important because it connects **business processes, personal data, processing activities, systems, third parties, privacy risks, controls, and regulatory obligations**.

A basic model is:

```text
Data Subject
     ↓
Data Collection
     ↓
Data Processing
     ↓
Data Storage
     ↓
Data Use
     ↓
Data Sharing
     ↓
Data Retention
     ↓
Data Deletion
```

The purpose is to make the organization's personal-data ecosystem visible and traceable.

---

# 1. What Is a Personal Data Processing Flow?

A personal data processing flow shows:

* **Where personal data originates**
* **What data is collected**
* **Why it is collected**
* **How it is processed**
* **Where it is stored**
* **Who can access it**
* **Who it is shared with**
* **How long it is retained**
* **How it is eventually deleted or disposed of**

A simplified representation is:

```text
COLLECT
   ↓
PROCESS
   ↓
STORE
   ↓
USE
   ↓
SHARE
   ↓
RETAIN
   ↓
DELETE
```

This provides a visual representation of the personal-data lifecycle within a business process.

---

# 2. Why Personal Data Processing Diagrams Matter

Organizations often have personal data distributed across many systems.

For example:

```text
Customer
   ↓
Website
   ↓
CRM
   ↓
Marketing Platform
   ↓
Cloud Storage
   ↓
Analytics Platform
   ↓
Third-Party Provider
```

Without a visual representation, it can become difficult to determine:

* where personal data exists;
* which systems process it;
* who has access;
* where it is transferred;
* whether third parties are involved;
* whether retention requirements are followed; and
* where privacy controls should be implemented.

Therefore, the diagram becomes a practical GRC tool.

---

# 3. Personal Data Processing Flow – Basic Model

A typical flow can be represented as:

```text
                 DATA SUBJECT
                      ↓
                DATA COLLECTION
                      ↓
              COLLECTION SYSTEM
                      ↓
               DATA PROCESSING
                      ↓
              BUSINESS APPLICATION
                      ↓
                 DATA STORAGE
                      ↓
          ┌───────────┴───────────┐
          ↓                       ↓
       INTERNAL                THIRD PARTY
       PROCESSING              PROCESSING
          ↓                       ↓
          └───────────┬───────────┘
                      ↓
                  DATA USE
                      ↓
                 RETENTION
                      ↓
                   DELETION
```

This is a high-level model. Actual organizations may have significantly more complex data flows.

---

# 4. Step 1 – Identify the Data Subject

The flow begins with the individual whose personal data is being processed.

Examples include:

```text
Customer
Employee
Applicant
Supplier Contact
Website Visitor
Patient
Student
Citizen
User
```

The diagram should identify the relevant population.

For example:

```text
Customer
   ↓
Customer Personal Data
```

This establishes the starting point of the processing activity.

---

# 5. Step 2 – Identify the Data Collected

The organization should identify the categories of personal data being collected.

For example:

```text
IDENTITY DATA
 ├── Name
 ├── Date of Birth
 └── Customer ID

CONTACT DATA
 ├── Email
 ├── Phone
 └── Address

TRANSACTION DATA
 ├── Purchase History
 └── Payment Information
```

The exact categories depend on the business process.

---

# 6. Data Classification

Personal data should be appropriately classified.

A simplified model could be:

```text
                    PERSONAL DATA
                          ↓
        ┌─────────────────┼─────────────────┐
        ↓                 ↓                 ↓
     General          Sensitive       Highly Sensitive
     Personal Data    Personal Data    Personal Data
```

Organizations should define classification categories according to their own policies and applicable laws.

Classification helps determine the appropriate security and privacy controls.

---

# 7. Step 3 – Collection

Personal data may be collected through multiple channels.

```text
                 DATA SUBJECT
                      ↓
        ┌─────────────┼─────────────┐
        ↓             ↓             ↓
      Website       Mobile        Call Center
        ↓             ↓             ↓
        └─────────────┼─────────────┘
                      ↓
                 DATA PLATFORM
```

Other collection points may include:

```text
Email
Physical Forms
Applications
Cookies
Sensors
APIs
Third-Party Platforms
```

A privacy diagram should make significant collection points visible.

---

# 8. Collection and Purpose

A key privacy principle is that the organization should understand **why the data is being collected**.

The flow should therefore connect:

```text
DATA COLLECTION
       ↓
PURPOSE
       ↓
PROCESSING ACTIVITY
```

For example:

```text
Customer Name
     ↓
Account Creation
     ↓
Customer Management
```

versus:

```text
Customer Email
     ↓
Marketing Purpose
     ↓
Marketing Platform
```

The same data element may potentially be used for different purposes, which should be appropriately governed.

---

# 9. Step 4 – Processing

Processing is broader than simply storing data.

It can include activities such as:

```text
Collecting
Recording
Organizing
Structuring
Retrieving
Using
Analyzing
Sharing
Transferring
Combining
Modifying
Deleting
```

Therefore:

```text
PERSONAL DATA
      ↓
PROCESSING
      ↓
BUSINESS ACTIVITY
```

The diagram should reflect the actual processing activity rather than treating processing as a single technical operation.

---

# 10. Processing System

The diagram should identify the system performing the processing.

For example:

```text
Customer
   ↓
Website
   ↓
CRM
   ↓
Analytics Platform
```

A more detailed model:

```text
Customer
   ↓
Web Application
   ↓
API Gateway
   ↓
CRM
   ↓
Data Warehouse
   ↓
Analytics Platform
```

This makes the technical path of personal data visible.

---

# 11. Step 5 – Storage

Personal data may be stored in multiple locations.

```text
                 PERSONAL DATA
                       ↓
              ┌────────┼────────┐
              ↓        ↓        ↓
             CRM     Database   Cloud
              ↓        ↓        ↓
              └────────┼────────┘
                       ↓
                 Data Repository
```

Storage locations may include:

```text
Databases
Cloud Storage
Data Warehouses
Backup Systems
Applications
Email Systems
Documents
Mobile Devices
Third-Party Platforms
```

A complete privacy data-flow diagram should not assume that the primary application is the only place where data exists.

---

# 12. Data Replication

Data may be copied between systems.

For example:

```text
CRM
 ↓
Production Database
 ↓
Data Warehouse
 ↓
Analytics Platform
 ↓
Backup
```

Each additional copy creates another location that must be considered for:

* access control;
* retention;
* security;
* privacy;
* monitoring; and
* deletion.

This is an important GRC consideration.

---

# 13. Backup and Personal Data

Backup systems can create additional data copies.

```text
PRIMARY DATABASE
       ↓
      BACKUP
       ↓
SECONDARY STORAGE
       ↓
DISASTER RECOVERY SITE
```

Therefore, data deletion requirements and retention policies should consider how backups are managed.

The organization should understand whether deleted personal data remains in backup systems and how those backups are eventually expired or overwritten.

---

# 14. Step 6 – Internal Data Sharing

Personal data may move between internal departments.

For example:

```text
CUSTOMER
   ↓
SALES
   ↓
CRM
   ↓
CUSTOMER SERVICE
   ↓
FINANCE
   ↓
REPORTING
```

The organization should understand:

```text
Who receives the data?
Why do they need it?
What data do they receive?
What access do they have?
How long do they retain it?
```

This supports least privilege and purpose-based access.

---

# 15. Internal Data Flow Example

Consider an employee onboarding process:

```text
EMPLOYEE
   ↓
HR
   ↓
HR SYSTEM
   ↓
PAYROLL
   ↓
IT
   ↓
ACCESS MANAGEMENT
   ↓
BENEFITS PROVIDER
```

Different functions may require different categories of employee data.

The diagram helps identify where unnecessary data sharing might occur.

---

# 16. Step 7 – Third-Party Data Sharing

Personal data may also be transferred to external organizations.

```text
ORGANIZATION
     ↓
THIRD PARTY
     ↓
PROCESSING SERVICE
     ↓
DATA STORAGE
```

Examples include:

```text
Cloud Provider
Payroll Provider
Email Provider
Marketing Provider
Payment Processor
Customer Support Provider
Analytics Provider
Identity Provider
```

Third-party data flows should be clearly identified.

---

# 17. Third-Party Processing Model

A simplified model is:

```text
DATA SUBJECT
     ↓
ORGANIZATION
     ↓
THIRD-PARTY PROCESSOR
     ↓
SUBPROCESSOR
     ↓
SERVICE
```

This can become particularly important when a supplier uses additional subprocessors.

A GRC review should therefore consider the complete processing chain where relevant.

---

# 18. Data Processor and Controller Relationships

Depending on the applicable legal framework and circumstances, organizations may have different roles in relation to personal data.

A simplified representation is:

```text
DATA SUBJECT
     ↓
ORGANIZATION
     ↓
PROCESSOR
     ↓
SUBPROCESSOR
```

The exact legal relationship must be determined based on the actual processing arrangement and applicable law.

From a GRC perspective, the important point is to document the relationship and associated responsibilities.

---

# 19. Step 8 – International Data Transfers

Personal data may cross geographic boundaries.

For example:

```text
EU CUSTOMER
     ↓
EU APPLICATION
     ↓
EU CLOUD REGION
     ↓
GLOBAL SERVICE PROVIDER
     ↓
NON-EU PROCESSING LOCATION
```

International transfers should therefore be represented in data-flow diagrams where applicable.

The organization should understand:

```text
Where is the data collected?
Where is it processed?
Where is it stored?
Where is it transferred?
Who receives it?
What transfer mechanism applies?
```

The applicable requirements depend on the jurisdictions involved.

---

# 20. Geographic Data Flow

A useful diagram can explicitly show geographic boundaries:

```text
                  EUROPE
                    ↓
              EU Application
                    ↓
              EU Database
                    ↓
              Global Provider
                    ↓
               OTHER REGION
```

This can help privacy and legal teams identify cross-border processing that requires additional assessment.

---

# 21. Step 9 – Access to Personal Data

A data-flow diagram should also consider who can access personal data.

For example:

```text
                 PERSONAL DATA
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
       HR             IT          Customer Service
        ↓              ↓              ↓
     Limited        Admin        Limited
     Access         Access       Access
```

Access should be aligned with business need and organizational security policies.

---

# 22. Role-Based Data Access

A more detailed model is:

```text
USER
 ↓
IDENTITY
 ↓
ROLE
 ↓
AUTHORIZATION
 ↓
DATA
```

For example:

```text
Customer Service Agent
       ↓
Customer Service Role
       ↓
Authorized Access
       ↓
Customer Profile
```

while:

```text
Marketing User
       ↓
Marketing Role
       ↓
Limited Authorization
       ↓
Marketing Dataset
```

This demonstrates how identity and privacy controls intersect.

---

# 23. Step 10 – Data Use

After collection and processing, personal data may be used for business activities.

Examples include:

```text
Customer Service
Billing
Fraud Detection
Marketing
Analytics
Reporting
Product Development
Account Management
```

The flow might be:

```text
PERSONAL DATA
      ↓
AUTHORIZED USE
      ↓
BUSINESS PURPOSE
      ↓
BUSINESS OUTPUT
```

The organization should understand whether the actual use aligns with the documented purpose.

---

# 24. Secondary Use

A particularly important privacy consideration is secondary use.

For example:

```text
Customer Data
      ↓
Original Purpose:
Account Management
      ↓
Potential Secondary Use:
Marketing Analytics
```

The organization should evaluate whether the secondary processing is permitted and appropriately governed.

This is where privacy governance becomes closely connected with data governance.

---

# 25. Data Analytics Flow

Analytics can create additional processing activities.

```text
CUSTOMER DATA
      ↓
DATA WAREHOUSE
      ↓
ANALYTICS
      ↓
REPORTING
      ↓
BUSINESS DECISION
```

Additional controls may be required depending on the nature of the data and the analytics activity.

---

# 26. Data Aggregation

Personal data may be combined from multiple sources.

```text
CRM
 ↓
Billing
 ↓
Website
 ↓
Mobile App
 ↓
      DATA PLATFORM
           ↓
      CUSTOMER PROFILE
```

Data aggregation can increase the privacy impact because multiple datasets may provide a more detailed picture of an individual.

---

# 27. Data Minimization

The processing flow should support the principle of collecting and using only the data necessary for the relevant purpose.

A useful model is:

```text
BUSINESS PURPOSE
      ↓
DATA REQUIREMENT
      ↓
MINIMUM NECESSARY DATA
      ↓
PROCESSING
```

For example:

```text
Purpose:
Send service notification

Required:
Email Address

Not Necessarily Required:
Date of Birth
Passport Number
Full Address
```

This illustrates why data-flow diagrams can support privacy-by-design analysis.

---

# 28. Data Flow and Privacy by Design

Privacy should be considered when designing the processing architecture.

```text
BUSINESS PROCESS
      ↓
PERSONAL DATA IDENTIFICATION
      ↓
PRIVACY RISK ASSESSMENT
      ↓
PRIVACY CONTROLS
      ↓
SYSTEM DESIGN
      ↓
IMPLEMENTATION
```

This helps prevent privacy requirements from being added only after a system has already been deployed.

---

# 29. Step 11 – Data Retention

Personal data should not simply remain indefinitely without a defined governance basis.

A simplified model is:

```text
COLLECTION
    ↓
PROCESSING
    ↓
USE
    ↓
RETENTION PERIOD
    ↓
REVIEW
    ↓
DELETION / DISPOSAL
```

Retention should be linked to applicable legal, regulatory, contractual, and business requirements.

---

# 30. Retention by Data Category

Different categories may have different retention requirements.

```text
Customer Records
      ↓
Retention Period A

Financial Records
      ↓
Retention Period B

Marketing Data
      ↓
Retention Period C

Employee Records
      ↓
Retention Period D
```

The actual retention periods must be established by the organization's approved retention schedule and applicable requirements.

---

# 31. Step 12 – Data Deletion

At the end of the retention period:

```text
RETENTION PERIOD ENDS
        ↓
DELETION DECISION
        ↓
DATA DELETION
        ↓
DELETION VALIDATION
        ↓
EVIDENCE
```

Deletion should consider all relevant copies and systems.

```text
PRIMARY SYSTEM
      ↓
BACKUP
      ↓
ARCHIVE
      ↓
THIRD PARTY
      ↓
DELETION / EXPIRATION
```

---

# 32. Data Disposal

Data may be disposed of through different mechanisms.

```text
Digital Data
    ↓
Secure Deletion

Physical Records
    ↓
Secure Destruction

Storage Media
    ↓
Secure Sanitization / Destruction
```

The appropriate method depends on the type of data and storage medium.

---

# 33. Complete Personal Data Processing Flow

A more comprehensive diagram is:

```text
                         DATA SUBJECT
                              ↓
                         COLLECTION
                              ↓
                       INITIAL SYSTEM
                              ↓
                         PROCESSING
                              ↓
                       DATA STORAGE
                              ↓
             ┌────────────────┼────────────────┐
             ↓                ↓                ↓
         INTERNAL          ANALYTICS        THIRD PARTY
         PROCESSING        PLATFORM         PROCESSING
             ↓                ↓                ↓
             └────────────────┼────────────────┘
                              ↓
                          DATA USE
                              ↓
                       DATA SHARING
                              ↓
                          RETENTION
                              ↓
                     RETENTION REVIEW
                              ↓
                    DELETION / DISPOSAL
```

This provides a useful high-level privacy architecture.

---

# 34. Personal Data Flow With Controls

The diagram can be enhanced by adding controls.

```text
DATA COLLECTION
      ↓
[Privacy Notice]
      ↓
DATA PROCESSING
      ↓
[Access Control]
      ↓
DATA STORAGE
      ↓
[Encryption]
      ↓
DATA SHARING
      ↓
[Third-Party Controls]
      ↓
DATA RETENTION
      ↓
[Retention Policy]
      ↓
DATA DELETION
      ↓
[Deletion Control]
```

This connects data movement directly with privacy and security controls.

---

# 35. Data Flow With GRC Traceability

A mature GRC model can connect each processing activity to governance elements:

```text
DATA
 ↓
PROCESSING ACTIVITY
 ↓
PURPOSE
 ↓
LEGAL / REGULATORY REQUIREMENT
 ↓
RISK
 ↓
CONTROL
 ↓
EVIDENCE
 ↓
ASSESSMENT
```

For example:

```text
Customer Email
      ↓
Marketing Communication
      ↓
Marketing Purpose
      ↓
Applicable Privacy Requirement
      ↓
Privacy Risk
      ↓
Consent / Preference Control
      ↓
Consent Record
      ↓
Control Review
```

This creates end-to-end traceability.

---

# 36. Data Flow and Records of Processing

Organizations may maintain formal records describing processing activities.

The data-flow diagram can provide a visual representation of those activities:

```text
PROCESSING ACTIVITY
       ↓
PURPOSE
       ↓
DATA CATEGORY
       ↓
DATA SUBJECT
       ↓
RECIPIENT
       ↓
STORAGE
       ↓
RETENTION
       ↓
TRANSFER
       ↓
SECURITY MEASURES
```

This is particularly valuable for privacy governance and compliance documentation.

---

# 37. Data Flow and Privacy Risk

The processing flow can be used to identify privacy risks.

```text
DATA FLOW
    ↓
IDENTIFY PROCESSING POINTS
    ↓
IDENTIFY RISKS
    ↓
ASSESS RISKS
    ↓
IMPLEMENT CONTROLS
    ↓
MONITOR
```

Potential risks include:

```text
Unauthorized Access
Excessive Collection
Unauthorized Sharing
Excessive Retention
Cross-Border Transfer
Data Leakage
Incorrect Data
Insufficient Deletion
Third-Party Exposure
```

---

# 38. Example – E-Commerce Customer

Consider an online customer:

```text
CUSTOMER
   ↓
E-COMMERCE WEBSITE
   ↓
CUSTOMER ACCOUNT
   ↓
CRM
   ↓
PAYMENT PROVIDER
   ↓
ORDER MANAGEMENT
   ↓
DELIVERY PROVIDER
   ↓
CUSTOMER SUPPORT
   ↓
RETENTION
   ↓
DELETION
```

This simple flow already contains multiple processing relationships.

---

# 39. E-Commerce Control Overlay

Controls can be added:

```text
CUSTOMER
   ↓
[Privacy Notice]
   ↓
WEBSITE
   ↓
[MFA / Authentication]
   ↓
CRM
   ↓
[Access Control]
   ↓
PAYMENT PROVIDER
   ↓
[Third-Party Risk Management]
   ↓
DELIVERY PROVIDER
   ↓
[Contractual Controls]
   ↓
RETENTION
   ↓
[Retention Policy]
   ↓
DELETION
```

This illustrates how GRC controls can be mapped directly onto business data flows.

---

# 40. Example – Employee Data

An employee processing flow might look like:

```text
EMPLOYEE
   ↓
RECRUITMENT
   ↓
HR SYSTEM
   ↓
PAYROLL
   ↓
BENEFITS
   ↓
IT ACCESS MANAGEMENT
   ↓
PERFORMANCE MANAGEMENT
   ↓
ARCHIVE
   ↓
RETENTION / DELETION
```

Each stage can involve different categories of personal data and different access requirements.

---

# 41. Example – Healthcare Data

A healthcare environment may have a more sensitive flow:

```text
PATIENT
   ↓
REGISTRATION
   ↓
CLINICAL SYSTEM
   ↓
HEALTHCARE PROFESSIONAL
   ↓
LABORATORY
   ↓
PHARMACY
   ↓
BILLING
   ↓
ARCHIVE
```

Because of the sensitivity of health information, the security and privacy controls may need to be significantly stronger.

---

# 42. Example – AI Processing

An AI-enabled business process can introduce another processing path:

```text
USER
 ↓
APPLICATION
 ↓
AI SERVICE
 ↓
MODEL PROCESSING
 ↓
OUTPUT
 ↓
APPLICATION
 ↓
USER
```

If personal data is involved:

```text
PERSONAL DATA
      ↓
AI INPUT
      ↓
AI PROCESSING
      ↓
AI OUTPUT
      ↓
STORAGE
```

The organization should understand whether the AI provider retains, uses, transfers, or otherwise processes the submitted data.

---

# 43. Data Flow and AI Governance

A GRC review can ask:

```text
What personal data enters the AI system?
             ↓
Why is it processed?
             ↓
Where is it processed?
             ↓
Who operates the AI service?
             ↓
Is the data retained?
             ↓
Is the data used for additional purposes?
             ↓
Who can access the output?
```

This demonstrates the relationship between privacy governance and AI governance.

---

# 44. Third-Party Data Flow Architecture

A complex organization might have:

```text
                         ORGANIZATION
                              ↓
                ┌─────────────┼─────────────┐
                ↓             ↓             ↓
               CRM          HR System      ERP
                ↓             ↓             ↓
                └─────────────┼─────────────┘
                              ↓
                       CLOUD PLATFORM
                              ↓
                 ┌────────────┼────────────┐
                 ↓            ↓            ↓
              Analytics     AI Service   Support
                 ↓            ↓            ↓
                 └────────────┼────────────┘
                              ↓
                       THIRD PARTIES
```

This illustrates why privacy data mapping can become complex in large enterprises.

---

# 45. Data Flow and Security Architecture

Privacy data flows should also align with security architecture.

```text
PERSONAL DATA
      ↓
IDENTITY CONTROL
      ↓
NETWORK CONTROL
      ↓
APPLICATION CONTROL
      ↓
DATABASE CONTROL
      ↓
ENCRYPTION
      ↓
MONITORING
```

This creates a connection between **privacy architecture and cybersecurity architecture**.

---

# 46. Data Flow and Zero Trust

A Zero Trust approach can be incorporated:

```text
DATA
 ↓
IDENTITY
 ↓
AUTHENTICATION
 ↓
DEVICE
 ↓
CONTEXT
 ↓
AUTHORIZATION
 ↓
APPLICATION
 ↓
DATA
```

Access to personal data should not automatically be granted merely because the user is inside the corporate network.

---

# 47. Data Flow and Data Loss Prevention

DLP controls can monitor movement of sensitive personal data.

```text
PERSONAL DATA
      ↓
EMAIL
      ↓
DLP
      ↓
AUTHORIZED?
   ↙       ↘
 YES        NO
  ↓          ↓
SEND       BLOCK / ALERT
```

Similar controls may operate across:

```text
Email
Cloud Storage
Endpoints
Web Applications
Messaging Platforms
```

---

# 48. Data Flow Monitoring

Monitoring can be placed across the processing path:

```text
COLLECTION
     ↓
PROCESSING
     ↓
STORAGE
     ↓
SHARING
     ↓
TRANSFER
     ↓
DELETION
```

At each stage, organizations may monitor for:

```text
Unauthorized Access
Unexpected Transfers
Unusual Volume
Unauthorized Downloads
Abnormal Data Movement
```

---

# 49. Data Flow and Evidence

A GRC platform can maintain evidence associated with the processing activity.

```text
PROCESSING ACTIVITY
       ↓
PRIVACY REQUIREMENT
       ↓
CONTROL
       ↓
EVIDENCE
       ↓
ASSESSMENT
       ↓
FINDING
       ↓
REMEDIATION
```

Examples of evidence include:

```text
Privacy Notices
Processing Records
Data Flow Diagrams
Access Reviews
Contracts
Transfer Assessments
Retention Records
Deletion Evidence
Control Test Results
```

---

# 50. Data Flow Governance Model

A mature organization can govern personal-data flows through:

```text
                    DATA GOVERNANCE
                           ↓
                  PRIVACY GOVERNANCE
                           ↓
                  DATA FLOW MAPPING
                           ↓
              PROCESSING ACTIVITIES
                           ↓
                   RISK ASSESSMENT
                           ↓
                    CONTROL DESIGN
                           ↓
                   CONTROL OPERATION
                           ↓
                     MONITORING
                           ↓
                      ASSURANCE
```

This demonstrates that a data-flow diagram is not merely a technical document. It can become an important **GRC governance artifact**.

---

# 51. Key Questions for a GRC Professional

When reviewing a personal-data processing flow, ask:

```text
1. What personal data is being collected?

2. Who is the data subject?

3. Why is the data being processed?

4. Where is the data collected?

5. Which systems process it?

6. Where is it stored?

7. Who has access?

8. Is it shared internally?

9. Is it shared with third parties?

10. Is it transferred internationally?

11. How long is it retained?

12. How is it deleted?

13. What privacy risks exist?

14. What controls address those risks?

15. What evidence demonstrates that the controls operate effectively?
```

These questions turn a simple data-flow diagram into a practical privacy and GRC assessment tool.

---

# 52. Final Integrated Personal Data Processing Model

The complete model can be represented as:

```text
                         DATA SUBJECT
                              ↓
                         COLLECTION
                              ↓
                         DATA ENTRY
                              ↓
                         PROCESSING
                              ↓
                        APPLICATION
                              ↓
                           STORAGE
                              ↓
             ┌────────────────┼────────────────┐
             ↓                ↓                ↓
         INTERNAL          ANALYTICS        THIRD PARTY
         PROCESSING        PROCESSING       PROCESSING
             ↓                ↓                ↓
             └────────────────┼────────────────┘
                              ↓
                           DATA USE
                              ↓
                       DATA TRANSFER
                              ↓
                         DATA RETENTION
                              ↓
                       RETENTION REVIEW
                              ↓
                      DELETION / DISPOSAL
```

The GRC overlay is:

```text
DATA FLOW
    ↓
PURPOSE
    ↓
REQUIREMENT
    ↓
PRIVACY RISK
    ↓
CONTROL
    ↓
EVIDENCE
    ↓
TESTING
    ↓
ASSURANCE
```

The key principle is:

> **An organization should be able to understand and demonstrate where personal data comes from, how it is processed, where it goes, who can access it, how it is protected, how long it is retained, and how it is ultimately disposed of.**

A well-designed personal data processing diagram therefore becomes a bridge between **privacy, cybersecurity, data governance, third-party risk, compliance, and GRC assurance**.


