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


