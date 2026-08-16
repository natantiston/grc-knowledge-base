# 18.18 Cybersecurity Risk and Threat Diagrams

## Part 1 – Threat-to-Risk Model

A **Threat-to-Risk Model** provides a visual representation of how cybersecurity threats can create risk to organizational assets, processes, services, and business objectives.

The model is particularly important in GRC because it connects the **technical security environment** with **enterprise risk management**.

A simplified relationship is:

```text
Threat
   ↓
Threat Event
   ↓
Vulnerability / Exposure
   ↓
Potential Impact
   ↓
Risk
   ↓
Risk Treatment
   ↓
Residual Risk
```

The central concept is that a **threat does not automatically equal risk**. Risk emerges when a threat can exploit a vulnerability or exposure and potentially produce an impact to something the organization values.

---

# 1. What Is a Threat-to-Risk Model?

A threat-to-risk model explains how external or internal threat conditions become organizational risk.

For example:

```text
Cyber Threat
     ↓
Threat Actor
     ↓
Attack Opportunity
     ↓
Vulnerability / Weakness
     ↓
Threat Event
     ↓
Business Impact
     ↓
Cybersecurity Risk
```

This creates a bridge between:

* threat intelligence;
* vulnerability management;
* cybersecurity;
* risk management;
* business impact;
* GRC decision-making.

---

# 2. Threat, Risk, and Vulnerability Are Different

These concepts should not be treated as interchangeable.

### Threat

A **threat** represents something capable of causing harm.

Examples include:

* cybercriminal activity;
* ransomware;
* phishing;
* insider activity;
* supply-chain attacks;
* nation-state activity;
* malicious software.

### Vulnerability

A **vulnerability** is a weakness that could potentially be exploited.

Examples include:

* unpatched software;
* weak authentication;
* excessive privileges;
* insecure configuration;
* exposed services.

### Risk

**Risk** represents the potential for an adverse outcome resulting from the interaction of threats, vulnerabilities or exposures, and consequences.

A simplified model is:

```text id="v1h0pf"
Threat
   +
Vulnerability / Exposure
   +
Potential Impact
   ↓
Cybersecurity Risk
```

---

# 3. Basic Threat-to-Risk Relationship

The fundamental relationship can be visualized as:

```text id="4b4o4e"
                 THREAT
                   │
                   ↓
          Threat Exploits Weakness
                   │
                   ↓
             THREAT EVENT
                   │
                   ↓
                IMPACT
                   │
                   ↓
                 RISK
```

The model emphasizes that the existence of a threat alone does not establish that a particular asset is at significant risk.

---

# 4. Threat Sources

Threats can originate from different sources.

```text id="5e8p6r"
                    THREAT SOURCES
                          │
       ┌──────────────────┼──────────────────┐
       ↓                  ↓                  ↓
    External           Internal          Environmental
       │                  │                  │
 Cybercriminals        Insiders          Natural Events
 Hacktivists           Employees         Power Failure
 Nation States         Contractors       Fire / Flood
 Suppliers             Privileged Users   Physical Damage
```

The classification should reflect the organization's threat model.

---

# 5. Threat Actors

A threat actor may intentionally or unintentionally create a threat.

Examples include:

* organized cybercriminal groups;
* nation-state actors;
* malicious insiders;
* negligent employees;
* contractors;
* compromised suppliers;
* opportunistic attackers.

A simple model is:

```text id="gq5e3h"
Threat Actor
      ↓
Capability
      ↓
Intent
      ↓
Opportunity
      ↓
Threat Event
```

Not every threat actor has the same capability, motivation, resources, or opportunity.

---

# 6. Threat Event

A **threat event** represents an occurrence that could cause harm.

Examples:

```text id="cn6tqf"
Phishing Email
      ↓
Credential Theft

Malware Deployment
      ↓
System Compromise

Exposed API
      ↓
Unauthorized Access

Supplier Compromise
      ↓
Third-Party Breach
```

The threat event becomes important from a risk perspective when it can affect an organizational asset, process, service, or objective.

---

# 7. Assets and Business Resources

Threats ultimately matter because they can affect something valuable.

These may include:

```text id="2ovh4w"
Information
Applications
Infrastructure
Devices
Cloud Services
Identities
Business Processes
Customers
Employees
Critical Services
Reputation
```

The relationship is:

```text id="2b0pr3"
Threat
   ↓
Target
   ↓
Asset / Service
   ↓
Potential Impact
```

---

# 8. Threat-to-Asset Relationship

A threat model should identify what the threat could affect.

For example:

```text id="zq7u9r"
Ransomware
    ↓
File Servers
    ↓
Business Data
    ↓
Critical Business Processes
    ↓
Service Disruption
```

This helps translate technical threats into business consequences.

---

# 9. Vulnerability and Exposure

A threat may become more significant when vulnerabilities or exposures are present.

```text id="v7s3du"
Threat
  +
Exposure
  +
Vulnerability
  ↓
Potential Attack Path
  ↓
Threat Event
```

Examples:

```text id="o8d5lc"
Phishing
   +
Weak MFA
   ↓
Account Compromise

Ransomware
   +
Unpatched Server
   ↓
System Compromise

External Attacker
   +
Exposed Application
   ↓
Unauthorized Access
```

---

# 10. Threat Likelihood

Risk analysis commonly considers the likelihood that a threat event could occur.

A simplified conceptual relationship is:

```text id="apb4py"
Threat Capability
       +
Opportunity
       +
Vulnerability
       +
Exposure
       ↓
Likelihood
```

Likelihood should be assessed using the organization's defined risk methodology rather than automatically assuming that every vulnerability creates high likelihood.

---

# 11. Threat Impact

The impact of a successful threat event can involve multiple dimensions.

```text id="4g67se"
                    IMPACT
                      │
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
Confidentiality   Integrity     Availability
       │              │              │
       └──────────────┼──────────────┘
                      ↓
               Business Impact
```

Other impact categories may include:

* financial loss;
* regulatory consequences;
* legal consequences;
* customer harm;
* operational disruption;
* reputational damage;
* strategic impact.

---

# 12. Cybersecurity Risk Model

A simplified risk relationship is:

```text id="8a3z7q"
                THREAT
                  │
                  ↓
          Likelihood of Event
                  │
                  +
          Potential Impact
                  │
                  ↓
                 RISK
```

Organizations may use quantitative or qualitative approaches to calculate or categorize risk.

For example:

```text
Risk = Likelihood × Impact
```

This is a simplified representation and should be interpreted according to the organization's approved risk methodology.

---

# 13. Threat-to-Risk Chain

The complete chain can be represented as:

```text id="2k9q8e"
Threat Source
      ↓
Threat Actor
      ↓
Threat Capability
      ↓
Threat Event
      ↓
Vulnerability / Exposure
      ↓
Attack Opportunity
      ↓
Asset / Service
      ↓
Potential Impact
      ↓
Cybersecurity Risk
```

This provides a useful structure for cybersecurity risk analysis.

---

# 14. Threat Modeling and GRC

Threat modeling is often associated with cybersecurity engineering, but it has important GRC value.

Threat information can feed into:

```text id="g0p6mg"
Threat Intelligence
       ↓
Threat Identification
       ↓
Risk Assessment
       ↓
Risk Prioritization
       ↓
Security Controls
       ↓
Monitoring
       ↓
Risk Reporting
```

This creates a connection between technical security analysis and governance decisions.

---

# 15. Threat Intelligence to Risk

Threat intelligence can provide information about:

* emerging threat actors;
* attack techniques;
* campaigns;
* vulnerabilities being exploited;
* targeted industries;
* attack trends.

A simplified flow is:

```text id="w6j2z1"
Threat Intelligence
        ↓
Threat Analysis
        ↓
Organizational Relevance
        ↓
Risk Assessment
        ↓
Risk Prioritization
        ↓
Security Action
```

Not every threat intelligence observation should automatically become a risk.

The organization should evaluate relevance and potential business impact.

---

# 16. Vulnerability Management Connection

Threat-to-risk analysis can connect vulnerability management with business risk.

```text id="m8i0fo"
Vulnerability Identified
        ↓
Asset Criticality
        ↓
Threat Relevance
        ↓
Exploitability
        ↓
Potential Impact
        ↓
Risk Rating
        ↓
Remediation Priority
```

This provides a stronger basis for prioritization than vulnerability severity alone.

---

# 17. Asset Criticality

The importance of an asset can affect the significance of a threat.

For example:

```text id="v9n0p7"
Same Vulnerability
       │
       ├────────→ Low-Criticality Asset
       │                 ↓
       │             Lower Risk
       │
       └────────→ Critical Business System
                         ↓
                    Higher Risk
```

Therefore, vulnerability severity and business risk should not automatically be treated as the same thing.

---

# 18. Threat Scenario

A **threat scenario** combines multiple elements into a meaningful risk scenario.

For example:

```text id="h3m8a0"
Threat Actor:
Cybercriminal Group
        ↓
Technique:
Credential Phishing
        ↓
Weakness:
Insufficient Authentication
        ↓
Target:
Privileged Account
        ↓
Event:
Unauthorized Access
        ↓
Impact:
Critical System Compromise
        ↓
Risk:
Business Disruption / Data Exposure
```

Scenario-based analysis makes technical threats easier for business stakeholders to understand.

---

# 19. Threat Scenario Structure

A structured scenario can contain:

| Element              | Example                |
| -------------------- | ---------------------- |
| Threat Actor         | Cybercriminal          |
| Threat               | Credential theft       |
| Attack Technique     | Phishing               |
| Vulnerability        | Weak authentication    |
| Asset                | Administrative account |
| Threat Event         | Account compromise     |
| Impact               | Unauthorized access    |
| Business Consequence | Service disruption     |
| Risk                 | High                   |

This format can be incorporated into an enterprise risk register.

---

# 20. Threat-to-Risk Register

A cybersecurity risk register can connect threats to business risks.

| Risk ID | Threat     | Vulnerability / Exposure | Asset          | Impact                 | Risk   |
| ------- | ---------- | ------------------------ | -------------- | ---------------------- | ------ |
| CR-001  | Ransomware | Unpatched endpoint       | Endpoint Fleet | Operational disruption | High   |
| CR-002  | Phishing   | Weak authentication      | User Accounts  | Credential compromise  | High   |
| CR-003  | DDoS       | Limited resilience       | Public Service | Availability loss      | Medium |
| CR-004  | Insider    | Excessive privileges     | Sensitive Data | Data exposure          | High   |

The actual ratings should be determined using the organization's approved risk methodology.

---

# 21. Threat-to-Control Relationship

Once risk is identified, controls can be mapped to the threat scenario.

```text id="u2q6v4"
Threat
  ↓
Risk
  ↓
Control Objective
  ↓
Security Control
  ↓
Control Operation
  ↓
Evidence
  ↓
Control Effectiveness
```

For example:

```text id="x1l9k3"
Phishing Threat
      ↓
Credential Compromise Risk
      ↓
Strong Authentication
      ↓
MFA Control
      ↓
MFA Enforcement
      ↓
Authentication Logs
      ↓
Effectiveness Assessment
```

This creates traceability between threats, risks, and controls.

---

# 22. Preventive Controls

Preventive controls attempt to reduce the likelihood of a threat event occurring.

Examples include:

* multi-factor authentication;
* secure configuration;
* network segmentation;
* access restrictions;
* secure coding;
* email filtering.

Conceptually:

```text id="7tx4u5"
Threat
  ↓
Preventive Control
  ↓
Reduced Likelihood
  ↓
Reduced Risk
```

---

# 23. Detective Controls

Detective controls seek to identify suspicious or unauthorized activity.

Examples include:

* security monitoring;
* SIEM;
* intrusion detection;
* anomaly detection;
* log analysis.

The model is:

```text id="8z1o4b"
Threat Event
      ↓
Detection
      ↓
Alert
      ↓
Investigation
      ↓
Response
```

Detection can reduce the potential duration and impact of an incident.

---

# 24. Corrective Controls

Corrective controls help contain or recover from a threat event.

Examples include:

* incident response;
* system restoration;
* backup recovery;
* account disabling;
* malware removal.

The relationship is:

```text id="8k1v7q"
Threat Event
      ↓
Incident
      ↓
Containment
      ↓
Recovery
      ↓
Restoration
```

Together, preventive, detective, and corrective controls form a broader defense strategy.

---

# 25. Threat-to-Risk-to-Control Model

The complete relationship is:

```text id="p0c5ez"
Threat
  ↓
Threat Event
  ↓
Vulnerability / Exposure
  ↓
Risk
  ↓
Control
  ↓
Control Effectiveness
  ↓
Residual Risk
```

This is particularly valuable for GRC because it connects cybersecurity analysis with control management and risk treatment.

---

# 26. Risk Treatment

Once risk is assessed, management may choose different treatment strategies.

```text id="j5v4py"
                  RISK
                    │
       ┌────────────┼────────────┐
       ↓            ↓            ↓
     Avoid        Reduce       Transfer
       │            │            │
       └────────────┼────────────┘
                    ↓
                 Accept
```

Treatment selection should be based on organizational risk appetite, business requirements, cost, and available options.

---

# 27. Residual Risk

Security controls rarely eliminate risk completely.

The relationship is:

```text id="x2r5yq"
Inherent Risk
      ↓
Security Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
```

Residual risk is the risk remaining after controls and other risk treatments have been applied.

---

# 28. Threat-to-Residual-Risk Model

The full model can therefore be represented as:

```text id="q1f7cd"
Threat
  ↓
Vulnerability / Exposure
  ↓
Threat Event
  ↓
Inherent Risk
  ↓
Risk Treatment
  ↓
Security Controls
  ↓
Control Effectiveness
  ↓
Residual Risk
  ↓
Risk Acceptance / Further Treatment
```

This provides an important connection between technical threat analysis and enterprise risk decisions.

---

# 29. Threat-to-Risk Escalation

Threat information may trigger escalation when it creates a significant change in risk.

```text id="xq3w6m"
New Threat Identified
        ↓
Relevance Assessment
        ↓
Risk Impact Analysis
        ↓
Risk Rating Change?
        │
    ┌───┴───┐
    ↓       ↓
   No      Yes
    │       │
 Continue   Escalate
 Monitoring   ↓
          Management
```

This allows organizations to respond to changing threat conditions.

---

# 30. Threat Landscape and Enterprise Risk

Threats should be considered in the broader business context.

```text id="z6x5pj"
External Threat Landscape
          ↓
Industry Threats
          ↓
Organization Exposure
          ↓
Business Critical Assets
          ↓
Threat Scenarios
          ↓
Enterprise Cyber Risk
```

This prevents threat analysis from becoming isolated from organizational priorities.

---

# 31. Cyber Risk Prioritization

Risk teams can prioritize scenarios using multiple factors:

```text id="p6t2hs"
Threat Severity
      +
Asset Criticality
      +
Exploitability
      +
Exposure
      +
Business Impact
      +
Control Weakness
      ↓
Cyber Risk Priority
```

This supports risk-based allocation of cybersecurity resources.

---

# 32. Threat-to-Risk Model in a GRC Platform

A GRC platform may maintain relationships such as:

```text id="c7s8k2"
Threat
 │
 ├── Threat Actor
 ├── Technique
 └── Threat Scenario
        │
        ↓
       Risk
        │
        ├── Asset
        ├── Business Process
        ├── Owner
        └── Risk Rating
                │
                ↓
              Control
                │
                ↓
              Evidence
                │
                ↓
             Assessment
                │
                ↓
          Residual Risk
```

This creates a connected GRC data model.

---

# 33. Threat-to-Risk Traceability

A mature GRC environment should be able to trace:

```text id="m5l3qe"
Threat
  ↓
Scenario
  ↓
Risk
  ↓
Asset
  ↓
Control
  ↓
Evidence
  ↓
Assessment
  ↓
Residual Risk
  ↓
Management Decision
```

This traceability improves:

* accountability;
* auditability;
* risk reporting;
* control effectiveness analysis;
* management decision-making.

---

# 34. Threat Modeling and Business Objectives

Cybersecurity threats should ultimately be evaluated against business objectives.

```text id="1n6x2r"
Business Objective
       ↓
Critical Service
       ↓
Critical Asset
       ↓
Threat
       ↓
Threat Scenario
       ↓
Cyber Risk
       ↓
Business Impact
```

This allows cybersecurity professionals to explain technical risks in business terms.

---

# 35. Example – Customer Portal

Consider an online customer portal.

```text id="2m7r4k"
Threat Actor
    ↓
Credential Attack
    ↓
Weak Authentication
    ↓
Customer Account Compromise
    ↓
Unauthorized Access
    ↓
Customer Data Exposure
    ↓
Regulatory / Financial / Reputational Impact
    ↓
Cybersecurity Risk
```

Possible controls include:

* MFA;
* bot protection;
* rate limiting;
* anomaly detection;
* access monitoring;
* incident response.

The controls reduce either likelihood, impact, or both.

---

# 36. Example – Ransomware

A ransomware scenario could be modeled as:

```text id="4t8q1m"
Cybercriminal
      ↓
Phishing
      ↓
Endpoint Compromise
      ↓
Privilege Escalation
      ↓
Lateral Movement
      ↓
Ransomware Deployment
      ↓
Critical Systems Encrypted
      ↓
Business Disruption
      ↓
Cybersecurity Risk
```

The risk model can then identify where controls should interrupt the attack chain.

---

# 37. Example – Cloud Service Exposure

A cloud risk scenario might be:

```text id="7k2v9n"
External Threat Actor
        ↓
Internet Exposure
        ↓
Misconfigured Cloud Resource
        ↓
Unauthorized Access
        ↓
Sensitive Data Exposure
        ↓
Business / Regulatory Impact
        ↓
Cybersecurity Risk
```

Relevant controls may include:

* cloud configuration management;
* identity controls;
* encryption;
* logging;
* continuous monitoring;
* security assessments.

---

# 38. Threat-to-Risk Model and Risk Appetite

Not every identified threat requires the same level of treatment.

The organization should compare assessed risk against risk appetite.

```text id="2h8c4m"
Threat Scenario
      ↓
Risk Assessment
      ↓
Risk Rating
      ↓
Risk Appetite
      │
 ┌────┴────┐
 ↓         ↓
Within     Outside
Appetite   Appetite
 ↓         ↓
Monitor    Treat / Escalate
```

This connects cybersecurity analysis directly to executive risk governance.

---

# 39. Threat-to-Risk Model and Incident Management

Threat analysis can also feed incident management.

```text id="j9q5e3"
Threat Intelligence
       ↓
Threat Scenario
       ↓
Potential Risk
       ↓
Security Monitoring
       ↓
Alert
       ↓
Incident
       ↓
Investigation
       ↓
Lessons Learned
       ↓
Risk Reassessment
```

An incident can therefore provide feedback into the risk model.

---

# 40. Continuous Threat-to-Risk Cycle

Cybersecurity risk is dynamic.

A mature model therefore operates continuously:

```text id="2y4m7q"
       THREAT LANDSCAPE
              ↓
        THREAT ANALYSIS
              ↓
         RISK ASSESSMENT
              ↓
        CONTROL RESPONSE
              ↓
          MONITORING
              ↓
        THREAT CHANGES
              │
              └──────────────↺
```

This ensures that risk assessments reflect changing threat conditions.

---

# 41. Common Threat-to-Risk Modeling Mistakes

### Treating Every Threat as High Risk

A threat becomes significant only when its relevance, likelihood, exposure, and potential impact justify that assessment.

### Treating Vulnerability Severity as Risk

A critical vulnerability on a non-critical isolated asset may present a different business risk than the same vulnerability on a mission-critical system.

### Ignoring Business Context

Technical severity alone does not communicate the full organizational consequence.

### Ignoring Threat Relevance

A vulnerability may exist but have limited practical risk if the relevant threat scenario is unlikely or the asset is adequately protected.

### Assuming Controls Eliminate Risk

Controls generally reduce risk rather than guarantee zero risk.

### Failing to Reassess

Threat landscapes change, so cybersecurity risk assessments must be periodically reviewed.

---

# 42. Threat-to-Risk Governance Model

The governance relationship can be summarized as:

```text id="f4x7d9"
                    BOARD
                      │
                      ↓
             ENTERPRISE RISK APPETITE
                      │
                      ↓
                CYBER RISK
                      │
          ┌───────────┼───────────┐
          ↓           ↓           ↓
       THREATS     EXPOSURES    IMPACTS
          │           │           │
          └───────────┼───────────┘
                      ↓
                RISK ASSESSMENT
                      ↓
                RISK TREATMENT
                      ↓
                   CONTROLS
                      ↓
                RESIDUAL RISK
                      ↓
              MANAGEMENT DECISION
```

This demonstrates how technical threat information ultimately supports governance decisions.

---

# 43. Executive Threat-to-Risk View

For executives, the technical details can be simplified:

```text id="u3w8p1"
THREAT
  ↓
"Could this affect us?"
  ↓
EXPOSURE
  ↓
"What could be affected?"
  ↓
IMPACT
  ↓
"How serious would it be?"
  ↓
RISK
  ↓
"What should we do?"
  ↓
TREATMENT
  ↓
"Is the remaining risk acceptable?"
```

This makes cybersecurity risk understandable without requiring the executive audience to understand every technical detail.

---

# 44. End-to-End Threat-to-Risk Model

The complete model can be represented as:

```text id="x8p4q2"
                    THREAT LANDSCAPE
                           │
                           ↓
                     THREAT SOURCE
                           │
                           ↓
                      THREAT ACTOR
                           │
                           ↓
                     THREAT CAPABILITY
                           │
                           ↓
                     THREAT SCENARIO
                           │
                           ↓
                 VULNERABILITY / EXPOSURE
                           │
                           ↓
                      THREAT EVENT
                           │
                           ↓
                   ASSET / BUSINESS SERVICE
                           │
                           ↓
                     POTENTIAL IMPACT
                           │
                           ↓
                    INHERENT CYBER RISK
                           │
                           ↓
                    RISK TREATMENT
                           │
                           ↓
                       CONTROLS
                           │
                           ↓
                  CONTROL EFFECTIVENESS
                           │
                           ↓
                     RESIDUAL RISK
                           │
                           ↓
                  MANAGEMENT DECISION
                           │
                           ↓
                    MONITORING & REVIEW
                           │
                           └──────────────↺
```

The **Threat-to-Risk Model** provides a critical bridge between cybersecurity operations and enterprise GRC. It shows how threat intelligence, threat actors, vulnerabilities, exposures, assets, business impacts, controls, and risk decisions are connected.

The key principle is that **threats become meaningful from a GRC perspective when they are evaluated in relation to organizational exposure, affected assets or services, potential consequences, and the effectiveness of existing controls**. This allows cybersecurity teams and GRC professionals to move from simply identifying threats toward making **risk-based decisions about where security resources, controls, and management attention should be applied**.

# 18.18 Cybersecurity Risk and Threat Diagrams

## Part 2 – Threat, Vulnerability, and Risk Relationship

The **Threat, Vulnerability, and Risk Relationship** diagram explains how threats, vulnerabilities, exposures, assets, and business consequences interact to create cybersecurity risk.

The model is important because these concepts are frequently used interchangeably even though they represent different elements of the risk equation.

A simplified relationship is:

```text
Threat
   +
Vulnerability / Exposure
   +
Affected Asset
   +
Potential Impact
   ↓
Cybersecurity Risk
```

A more complete model is:

```text
Threat
  ↓
Threat Event
  ↓
Vulnerability / Exposure
  ↓
Affected Asset
  ↓
Potential Consequence
  ↓
Risk
```

The purpose of this model is to help GRC and cybersecurity professionals understand **why a particular weakness matters, what could exploit it, what could be affected, and what the resulting business risk may be**.

---

# 1. Threat, Vulnerability, and Risk Are Different

The first principle is to distinguish the three concepts.

### Threat

A **threat** is something capable of causing harm.

Examples:

* cybercriminal;
* ransomware;
* phishing;
* malicious insider;
* nation-state activity;
* supply-chain compromise.

### Vulnerability

A **vulnerability** is a weakness that could be exploited.

Examples:

* unpatched software;
* weak authentication;
* insecure configuration;
* excessive privileges;
* vulnerable application code.

### Risk

**Risk** represents the potential for an adverse outcome resulting from the interaction of threats, vulnerabilities or exposures, and consequences.

A simple conceptual model is:

```text id="7h5j1p"
Threat
   +
Vulnerability / Exposure
   +
Potential Impact
   ↓
Risk
```

---

# 2. The Fundamental Relationship

The core relationship can be represented as:

```text id="y3p8q0"
             THREAT
                │
                ↓
       Can exploit weakness
                │
                ↓
        VULNERABILITY
                │
                ↓
          Threat Event
                │
                ↓
          Affected Asset
                │
                ↓
        Business Impact
                │
                ↓
              RISK
```

The model shows that a vulnerability by itself does not automatically represent a specific level of business risk.

---

# 3. Threat

Threats represent potential sources of harm.

A threat may be:

### Intentional

```text id="x4d9r2"
Cybercriminal
Nation-State
Malicious Insider
Hacktivist
```

### Unintentional

```text id="v7q2m6"
Human Error
Misconfiguration
Accidental Disclosure
Operational Mistake
```

### Environmental

```text id="a6n3k8"
Fire
Flood
Power Failure
Natural Disaster
```

The threat category should reflect the organization's threat model.

---

# 4. Vulnerability

A vulnerability is a weakness that can potentially be exploited or otherwise contribute to an adverse event.

Examples include:

```text id="d2k7m1"
Weak Password
     ↓
Authentication Weakness

Unpatched Server
     ↓
Software Vulnerability

Open Storage Bucket
     ↓
Configuration Weakness

Excessive Privilege
     ↓
Access Control Weakness
```

Vulnerabilities may exist in:

* applications;
* infrastructure;
* networks;
* cloud environments;
* identities;
* processes;
* configurations;
* organizational procedures.

---

# 5. Exposure

Not every cybersecurity risk is caused by a conventional technical vulnerability.

An **exposure** may also create risk.

Examples include:

* internet-accessible services;
* publicly exposed information;
* excessive permissions;
* unmanaged devices;
* unsupported systems;
* third-party connectivity.

Therefore, a more comprehensive model is:

```text id="q8n5t3"
Threat
   +
Vulnerability
   OR
Exposure
   ↓
Potential Threat Event
```

This is why modern cybersecurity risk analysis often considers both vulnerabilities and broader exposures.

---

# 6. Asset

The threat and vulnerability relationship becomes meaningful when something valuable can be affected.

Examples:

```text id="v0m6c2"
Customer Database
Financial System
Cloud Platform
Identity System
Production Network
Business Application
Critical Service
```

The asset's criticality can influence the resulting risk.

---

# 7. Asset Criticality Changes Risk

Consider the same vulnerability on two systems:

```text id="m3p7x9"
Unpatched Vulnerability
        │
        ├───────────────┐
        ↓               ↓
Low-Criticality     Critical System
Asset                   │
        ↓               ↓
Lower Potential      Higher Potential
Impact                  Impact
        ↓               ↓
Different Risk Levels
```

Therefore:

**Vulnerability severity ≠ automatically equivalent business risk.**

---

# 8. Threat + Vulnerability

A threat becomes more relevant when it can exploit a specific weakness.

For example:

```text id="q2v6n8"
Threat:
Ransomware Group
        +
Vulnerability:
Unpatched Endpoint
        ↓
Potential Exploitation
```

Another example:

```text id="p4k8r1"
Threat:
Credential Attacker
        +
Weak Authentication
        ↓
Account Compromise
```

This creates a threat scenario that can be assessed for risk.

---

# 9. Threat + Exposure

A threat can also exploit an exposure even when there is no conventional software vulnerability.

For example:

```text id="j8q4v2"
Internet Exposure
       +
Threat Actor
       ↓
Unauthorized Access Opportunity
```

Another example:

```text id="s6w2m9"
Excessive Privileges
       +
Compromised Account
       ↓
Unauthorized Data Access
```

This illustrates why exposure management is increasingly important in cybersecurity risk management.

---

# 10. Vulnerability + Asset

The significance of a vulnerability depends partly on the asset affected.

For example:

```text id="u5r8k2"
Critical Database
      │
      ↓
Critical Vulnerability
      │
      ↓
High Potential Impact
```

Whereas:

```text id="n7c3p5"
Isolated Test System
      │
      ↓
Same Vulnerability
      │
      ↓
Lower Potential Impact
```

The technical weakness may be identical, but the business risk may differ.

---

# 11. Threat + Vulnerability + Asset

The basic cybersecurity risk relationship therefore becomes:

```text id="m4x8z7"
        THREAT
           │
           +
     VULNERABILITY
           │
           +
          ASSET
           │
           ↓
     THREAT EVENT
           │
           ↓
      POTENTIAL IMPACT
           │
           ↓
          RISK
```

This is a foundational model for cybersecurity risk analysis.

---

# 12. Likelihood

Risk assessment commonly considers the likelihood of a threat event occurring.

Conceptually:

```text id="w8k2q5"
Threat Capability
       +
Opportunity
       +
Exposure
       +
Vulnerability
       ↓
Likelihood
```

Factors influencing likelihood may include:

* attacker capability;
* attacker motivation;
* exposure;
* exploit availability;
* vulnerability severity;
* existing controls;
* environmental conditions;
* historical activity.

The exact methodology should follow the organization's approved risk framework.

---

# 13. Impact

Impact describes the potential consequence if the threat event occurs.

A cybersecurity impact model may consider:

```text id="r6m1t4"
                 IMPACT
                   │
       ┌───────────┼───────────┐
       ↓           ↓           ↓
Confidentiality Integrity Availability
       │           │           │
       └───────────┼───────────┘
                   ↓
             Business Impact
```

Additional consequences may include:

* financial loss;
* regulatory penalties;
* legal exposure;
* customer harm;
* reputational damage;
* operational disruption;
* strategic consequences.

---

# 14. Likelihood and Impact

A simplified risk model is:

```text id="f5x2m8"
Likelihood
     ×
Impact
     ↓
Risk
```

For example:

| Likelihood | Impact | General Risk Direction |
| ---------- | ------ | ---------------------- |
| Low        | Low    | Low                    |
| Low        | High   | Moderate               |
| High       | Low    | Moderate               |
| High       | High   | High                   |

Actual risk ratings should be based on the organization's approved methodology.

---

# 15. The Complete Relationship

The relationship can be visualized as:

```text id="g3v7p2"
THREAT
  │
  ↓
Threat Capability / Intent
  │
  ↓
Vulnerability / Exposure
  │
  ↓
Attack Opportunity
  │
  ↓
Threat Event
  │
  ↓
Affected Asset
  │
  ↓
Potential Impact
  │
  ↓
Likelihood + Impact
  │
  ↓
CYBERSECURITY RISK
```

This is the core relationship between threat, vulnerability, and risk.

---

# 16. Controls Modify the Relationship

Controls can reduce the likelihood or impact of a threat event.

```text id="x9k5c1"
Threat
  ↓
Vulnerability / Exposure
  ↓
Potential Attack
  ↓
Security Controls
  ↓
Reduced Likelihood / Impact
  ↓
Residual Risk
```

Examples:

```text id="h6v2q8"
Weak Authentication
       ↓
MFA
       ↓
Reduced Account-Compromise Risk
```

```text id="n3x7p4"
Unpatched System
       ↓
Patch Management
       ↓
Reduced Exploitation Risk
```

---

# 17. Preventive Controls

Preventive controls attempt to prevent or reduce the likelihood of exploitation.

Examples include:

* MFA;
* network segmentation;
* secure configuration;
* application security controls;
* access restrictions;
* endpoint protection.

The relationship is:

```text id="u4q9m1"
Threat
  +
Vulnerability
  ↓
Preventive Control
  ↓
Reduced Likelihood
  ↓
Reduced Risk
```

---

# 18. Detective Controls

Detective controls identify suspicious activity.

Examples include:

* SIEM;
* intrusion detection;
* security monitoring;
* endpoint detection;
* anomaly detection.

The model is:

```text id="r2m8v6"
Threat Event
     ↓
Detection
     ↓
Alert
     ↓
Investigation
```

Effective detection can reduce the duration and potential impact of an attack.

---

# 19. Corrective Controls

Corrective controls respond to successful or partially successful threat events.

Examples include:

* incident response;
* account disabling;
* malware removal;
* system restoration;
* backup recovery.

The relationship is:

```text id="k7x4p2"
Threat Event
      ↓
Incident
      ↓
Containment
      ↓
Recovery
      ↓
Reduced Impact
```

---

# 20. Inherent and Residual Risk

Controls create an important distinction between inherent and residual risk.

```text id="t5n8q3"
Threat + Vulnerability + Impact
             ↓
        Inherent Risk
             ↓
       Security Controls
             ↓
      Control Effectiveness
             ↓
        Residual Risk
```

**Inherent risk** represents the level of risk before considering applicable controls or treatments.

**Residual risk** represents the remaining risk after controls and treatments are considered.

---

# 21. Control Effectiveness

Controls are not automatically effective merely because they exist.

The model should consider:

```text id="p9v2m5"
Control Exists
     ↓
Control Designed
     ↓
Control Implemented
     ↓
Control Operating
     ↓
Control Effective?
```

Control effectiveness influences the remaining risk.

```text id="z8c4q1"
Strong Control
     ↓
Lower Residual Risk

Weak / Ineffective Control
     ↓
Higher Residual Risk
```

---

# 22. Threat, Vulnerability, and Control Relationship

The complete relationship can be represented as:

```text id="q4n7x2"
             THREAT
                │
                ↓
      VULNERABILITY / EXPOSURE
                │
                ↓
          ATTACK OPPORTUNITY
                │
                ↓
             CONTROLS
                │
        ┌───────┴────────┐
        ↓                ↓
   Prevent Attack    Detect Attack
        │                │
        └───────┬────────┘
                ↓
          Threat Event
                │
                ↓
             IMPACT
                │
                ↓
              RISK
```

Controls can intervene at multiple points in the chain.

---

# 23. Threat and Vulnerability Are Not Always Required Together

A useful conceptual distinction is that cybersecurity risk does not always require a traditional vulnerability.

For example:

```text
Threat
  +
Operational Exposure
  +
Critical Asset
  ↓
Risk
```

A misconfigured process, excessive privilege, exposed service, or weak governance mechanism can create risk even without a known software vulnerability.

Therefore:

**Threat + exposure + consequence can be sufficient to create a meaningful risk scenario.**

---

# 24. Threat Exposure Model

A modern exposure-oriented model may look like:

```text id="y7m3q8"
External Threat
      ↓
Internet Exposure
      ↓
Attack Surface
      ↓
Potential Attack Path
      ↓
Critical Asset
      ↓
Business Impact
      ↓
Cyber Risk
```

This is particularly relevant to:

* cloud environments;
* internet-facing systems;
* remote access;
* APIs;
* third-party connections;
* digital services.

---

# 25. Attack Surface

The **attack surface** represents the collection of points through which an attacker could potentially interact with an organization's environment.

Examples include:

```text id="c8p2w6"
Internet-Facing Applications
Cloud Services
Endpoints
APIs
Remote Access
Identity Systems
Third Parties
```

The relationship is:

```text id="v5m9q3"
Threats
   ↓
Attack Surface
   ↓
Exposures / Vulnerabilities
   ↓
Potential Attack Paths
   ↓
Risk
```

---

# 26. Business Context

Technical analysis becomes more valuable when connected to business context.

For example:

```text id="m2x7k5"
Vulnerability
      ↓
Affected System
      ↓
Business Process
      ↓
Critical Service
      ↓
Business Objective
      ↓
Potential Impact
      ↓
Risk
```

This allows executives to understand why a particular technical weakness deserves attention.

---

# 27. Threat-to-Business-Risk Translation

A technical statement might be:

> "The server has a critical vulnerability."

A GRC-oriented interpretation asks:

```text id="h8p4r2"
Which server?
     ↓
What business service?
     ↓
What asset?
     ↓
What threat could exploit it?
     ↓
What could happen?
     ↓
What is the potential impact?
     ↓
What controls exist?
     ↓
What is the residual risk?
```

This transforms technical vulnerability information into a business risk assessment.

---

# 28. Example – Vulnerable Web Application

Consider an internet-facing application.

```text id="p6x3m9"
Threat Actor
     ↓
Internet-Facing Application
     ↓
Application Vulnerability
     ↓
Exploitation
     ↓
Unauthorized Access
     ↓
Customer Data
     ↓
Data Exposure
     ↓
Regulatory / Financial / Reputation Impact
     ↓
Cybersecurity Risk
```

Possible controls include:

* secure development;
* vulnerability management;
* web application firewall;
* access control;
* logging;
* monitoring;
* incident response.

---

# 29. Example – Phishing

A phishing scenario can be represented as:

```text id="n5q7v3"
Threat Actor
      ↓
Phishing Campaign
      ↓
User Receives Malicious Email
      ↓
Credential Theft
      ↓
Weak / Compromised Authentication
      ↓
Account Takeover
      ↓
Unauthorized Access
      ↓
Business Impact
      ↓
Cyber Risk
```

Controls may interrupt the chain at several points:

```text id="r8m2c4"
Email Filtering
     ↓
User Awareness
     ↓
MFA
     ↓
Identity Monitoring
     ↓
Incident Response
```

---

# 30. Example – Ransomware

A ransomware risk relationship may look like:

```text id="b4x8q2"
Threat Actor
      ↓
Phishing / Exploit
      ↓
Endpoint Vulnerability
      ↓
Initial Compromise
      ↓
Privilege Escalation
      ↓
Lateral Movement
      ↓
Ransomware Deployment
      ↓
Critical Systems
      ↓
Business Disruption
      ↓
Cybersecurity Risk
```

The organization may use multiple controls to break this chain.

---

# 31. Example – Excessive Privileges

A risk scenario does not always require an external attacker.

```text id="x3m7p8"
Compromised Account
       ↓
Excessive Privileges
       ↓
Unauthorized Access
       ↓
Sensitive Information
       ↓
Data Exposure
       ↓
Business / Regulatory Impact
       ↓
Risk
```

Controls may include:

* least privilege;
* privileged access management;
* access reviews;
* segregation of duties;
* monitoring.

---

# 32. Threat-Vulnerability-Risk Matrix

A matrix can be used to visualize relationships.

| Threat         | Vulnerability / Exposure | Asset             | Potential Impact       | Risk   |
| -------------- | ------------------------ | ----------------- | ---------------------- | ------ |
| Ransomware     | Unpatched endpoint       | Endpoint fleet    | Operational disruption | High   |
| Phishing       | Weak authentication      | User accounts     | Account compromise     | High   |
| Data theft     | Excessive privileges     | Customer database | Confidentiality loss   | High   |
| DDoS           | Limited resilience       | Public service    | Availability loss      | Medium |
| Insider misuse | Weak access monitoring   | Sensitive systems | Data exposure          | High   |

This type of matrix can support risk registers and management reporting.

---

# 33. Threat-Vulnerability-Risk Heatmap

Organizations may also visualize risks using likelihood and impact.

```text id="s4n8q2"
                    IMPACT
              Low    Medium    High
           ┌───────┬─────────┬────────┐
High       │ Medium│  High   │Critical│
LIKELIHOOD ├───────┼─────────┼────────┤
Medium     │  Low  │ Medium  │  High  │
           ├───────┼─────────┼────────┤
Low        │  Low  │   Low   │ Medium │
           └───────┴─────────┴────────┘
```

The actual scoring thresholds should follow the organization's approved risk methodology.

---

# 34. Threat Relevance

Not every threat applies equally to every organization.

Threat relevance can be evaluated using:

```text id="g7x2m9"
Threat
  ↓
Industry Relevance
  ↓
Organizational Exposure
  ↓
Asset Relevance
  ↓
Business Context
  ↓
Risk Relevance
```

For example, a threat targeting a technology platform that the organization does not use may have little direct relevance.

---

# 35. Threat Intelligence and Vulnerability Management

Threat intelligence can improve vulnerability prioritization.

Instead of:

```text id="x8p4v1"
Critical Vulnerability
        ↓
Patch Everything Equally
```

a risk-based approach can be:

```text id="q6m2z8"
Vulnerability
      ↓
Is It Exploited?
      ↓
Is Asset Exposed?
      ↓
Is Threat Relevant?
      ↓
Is Asset Critical?
      ↓
Potential Business Impact
      ↓
Risk-Based Priority
```

This helps direct limited resources toward the most meaningful exposures.

---

# 36. Risk Treatment Relationship

Once risk has been identified, management can determine how it should be treated.

```text id="n4x7c2"
Cybersecurity Risk
        ↓
Evaluate Against Risk Appetite
        ↓
┌───────┼────────┬────────┐
↓       ↓        ↓        ↓
Avoid  Reduce  Transfer  Accept
```

Risk reduction may involve:

* patching;
* configuration changes;
* stronger authentication;
* segmentation;
* monitoring;
* resilience improvements.

---

# 37. Residual Risk and Acceptance

After treatment:

```text id="j5q8m3"
Inherent Risk
      ↓
Treatment
      ↓
Controls
      ↓
Residual Risk
      ↓
Risk Appetite
      │
 ┌────┴────┐
 ↓         ↓
Acceptable Not Acceptable
 ↓         ↓
Monitor    Further Treatment
```

This creates an explicit connection between cybersecurity controls and management decisions.

---

# 38. Relationship to the Risk Register

The threat-vulnerability-risk model can feed directly into a GRC risk register.

A risk record may contain:

```text id="c7v2m9"
Risk ID
   ↓
Threat
   ↓
Vulnerability / Exposure
   ↓
Asset
   ↓
Business Process
   ↓
Risk Scenario
   ↓
Likelihood
   ↓
Impact
   ↓
Inherent Risk
   ↓
Controls
   ↓
Residual Risk
   ↓
Risk Owner
   ↓
Treatment
   ↓
Review Date
```

This creates structured risk information suitable for governance and reporting.

---

# 39. Relationship to Control Frameworks

The model can also connect with control frameworks.

```text id="m3x8q1"
Threat
  ↓
Risk
  ↓
Control Objective
  ↓
Control
  ↓
Framework Mapping
  ↓
Evidence
  ↓
Assessment
```

For example, one control may address requirements across:

* ISO 27001;
* NIST CSF;
* COBIT;
* regulatory requirements;
* internal policies.

This supports control harmonization.

---

# 40. Relationship to GRC Traceability

A mature organization should be able to trace:

```text id="v6p2k8"
Threat
 ↓
Vulnerability / Exposure
 ↓
Risk
 ↓
Business Asset
 ↓
Control
 ↓
Requirement
 ↓
Evidence
 ↓
Assessment
 ↓
Residual Risk
```

This provides a strong foundation for integrated GRC reporting.

---

# 41. Relationship to Incident Management

A realized risk can become an incident.

```text id="q8m3v5"
Threat
  ↓
Vulnerability
  ↓
Threat Event
  ↓
Security Incident
  ↓
Investigation
  ↓
Business Impact
  ↓
Risk Reassessment
```

Incident lessons can therefore improve future risk assessments.

---

# 42. Relationship to Business Continuity

Cybersecurity risks may also affect resilience.

```text id="z5x7p3"
Cyber Threat
      ↓
System Compromise
      ↓
Service Disruption
      ↓
Business Impact
      ↓
Continuity / Recovery
      ↓
Residual Risk
```

This creates a connection between cybersecurity risk management and business continuity planning.

---

# 43. Relationship to Third-Party Risk

The same model applies to suppliers.

```text id="w4n8q2"
Third-Party Threat
       ↓
Supplier Vulnerability
       ↓
Supplier Exposure
       ↓
Connected Enterprise Asset
       ↓
Potential Business Impact
       ↓
Third-Party Cyber Risk
```

This is important because an organization's risk exposure can extend beyond its directly managed infrastructure.

---

# 44. Dynamic Threat-Vulnerability-Risk Model

The relationship is not static.

```text id="m7q2x4"
Threat Landscape
       ↓
New Threats
       ↓
New Vulnerabilities
       ↓
Changing Exposure
       ↓
Changing Risk
       ↓
New Controls
       ↓
New Residual Risk
       ↓
Continuous Monitoring
       │
       └──────────────↺
```

Organizations should therefore periodically reassess significant cyber risks.

---

# 45. Executive View

For executive audiences, the relationship can be simplified:

```text id="h2x7m5"
THREAT
"What could harm us?"
       ↓
VULNERABILITY / EXPOSURE
"Where are we weak or exposed?"
       ↓
ASSET
"What could be affected?"
       ↓
IMPACT
"What would happen?"
       ↓
RISK
"How significant is it?"
       ↓
CONTROL
"What are we doing about it?"
       ↓
RESIDUAL RISK
"What risk remains?"
```

This provides a concise bridge between cybersecurity analysis and executive decision-making.

---

# 46. Common Modeling Mistakes

### Treating Vulnerability as Risk

A vulnerability is an input to risk analysis, not automatically the final risk.

### Treating Threat as Risk

The presence of a threat does not automatically mean that the organization has high risk.

### Ignoring Asset Criticality

The same vulnerability can create very different levels of risk depending on what it affects.

### Ignoring Exposure

An apparently low-severity weakness can become significant when the asset is highly exposed.

### Ignoring Existing Controls

Risk assessment should consider relevant controls according to the organization's methodology.

### Ignoring Business Impact

Technical consequences should ultimately be translated into organizational consequences.

### Treating Risk as Static

Threats, vulnerabilities, assets, controls, and business conditions change continuously.

---

# 47. Integrated Threat-Vulnerability-Risk Diagram

A comprehensive model is:

```text id="p8x4m2"
                    THREAT LANDSCAPE
                           │
                           ↓
                     THREAT ACTOR
                           │
                           ↓
                     THREAT EVENT
                           │
                           ↓
                ┌─────────────────────┐
                │ VULNERABILITY /     │
                │ EXPOSURE            │
                └──────────┬──────────┘
                           ↓
                    ATTACK OPPORTUNITY
                           │
                           ↓
                    AFFECTED ASSET
                           │
                           ↓
                     BUSINESS PROCESS
                           │
                           ↓
                     POTENTIAL IMPACT
                           │
                           ↓
                      INHERENT RISK
                           │
                           ↓
                       CONTROLS
                           │
                           ↓
                  CONTROL EFFECTIVENESS
                           │
                           ↓
                      RESIDUAL RISK
                           │
                           ↓
                  MANAGEMENT DECISION
                           │
                           ↓
                    MONITORING & REVIEW
                           │
                           └──────────────↺
```

---

# 48. Final Threat-Vulnerability-Risk Model

The relationship can ultimately be summarized as:

```text id="r4m8q1"
             THREAT
                │
                ↓
       VULNERABILITY / EXPOSURE
                │
                ↓
          THREAT SCENARIO
                │
                ↓
          AFFECTED ASSET
                │
                ↓
        LIKELIHOOD + IMPACT
                │
                ↓
        INHERENT CYBER RISK
                │
                ↓
             CONTROLS
                │
                ↓
       CONTROL EFFECTIVENESS
                │
                ↓
          RESIDUAL RISK
                │
                ↓
       MANAGEMENT DECISION
                │
                ↓
        MONITORING & REVIEW
                │
                └──────────────↺
```

The **Threat, Vulnerability, and Risk Relationship** model provides a structured way to connect technical weaknesses with meaningful business risk. It demonstrates that **a threat is not the same as a vulnerability, and neither is automatically equivalent to risk**. Risk emerges from the interaction of relevant threats, vulnerabilities or exposures, affected assets, likelihood, and potential consequences.

For GRC professionals, this relationship is particularly valuable because it allows technical security information to flow into **risk registers, control frameworks, treatment decisions, executive reporting, and governance processes**. The resulting model helps organizations prioritize cybersecurity resources based not simply on the existence or severity of vulnerabilities, but on the **actual risk those conditions create for the business**.



