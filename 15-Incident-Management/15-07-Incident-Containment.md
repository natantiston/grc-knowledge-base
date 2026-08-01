# 15.7 Incident Containment

## Part 1 – Short-Term Containment

> **Chapter:** 15 – Incident Management
>
> **Topic:** Short-Term Containment
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

## Introduction

Once a cybersecurity incident has been detected, analyzed, classified, and confirmed, the organization's immediate priority is to prevent the incident from causing additional harm. This phase is known as **incident containment**. The objective of containment is not to eliminate the threat completely, but rather to limit its spread, reduce business impact, preserve critical evidence, and create a stable environment for further investigation and eradication. The first stage of this process is referred to as **short-term containment**, where rapid actions are taken to stop the immediate progression of the attack.

Cyberattacks often evolve rapidly. Malware can spread across networks within minutes, attackers can move laterally between systems, and sensitive data may be exfiltrated before organizations fully understand the scope of the compromise. Delays in containment increase the likelihood of financial loss, operational disruption, regulatory penalties, and reputational damage. Consequently, incident response teams must make timely decisions based on available evidence while balancing the need to protect business operations and preserve forensic evidence.

Short-term containment focuses on immediate defensive actions that reduce the attacker's ability to continue exploiting systems. These actions may include isolating compromised devices, disabling compromised user accounts, blocking malicious network traffic, restricting privileged access, or temporarily shutting down vulnerable services. Since investigations are often ongoing during this stage, responders should avoid unnecessary system changes that could destroy valuable forensic evidence or hinder subsequent analysis.

International standards such as **ISO/IEC 27035**, **ISO/IEC 27001**, **NIST SP 800-61 Revision 2**, and the **NIST Cybersecurity Framework (CSF)** identify containment as a critical phase of incident response. Within Governance, Risk, and Compliance (GRC), effective short-term containment reduces enterprise risk, supports regulatory compliance, minimizes business disruption, and enables organizations to transition safely into eradication and recovery activities.

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Define short-term containment.
- Explain the objectives of immediate containment activities.
- Identify common short-term containment actions.
- Understand how containment protects business operations.
- Describe factors influencing containment decisions.
- Explain the relationship between containment and Governance, Risk, and Compliance (GRC).

---

# What is Short-Term Containment?

**Short-term containment** refers to the immediate actions taken to stop or limit the spread of a cybersecurity incident while preserving evidence and maintaining essential business operations.

Its primary goals are to:

- Prevent further compromise.
- Protect critical assets.
- Minimize operational disruption.
- Preserve digital evidence.
- Reduce business impact.
- Create time for investigation.

Containment is intended to stabilize the environment rather than permanently eliminate the threat.

---

# Objectives of Short-Term Containment

The objectives of short-term containment include:

- Limiting attacker movement.
- Preventing malware propagation.
- Protecting sensitive information.
- Maintaining critical business services.
- Preserving forensic evidence.
- Reducing operational risk.
- Supporting incident investigation.
- Preparing for eradication.

Rapid containment helps reduce the overall impact of cybersecurity incidents.

---

# Common Short-Term Containment Actions

Incident responders may perform several immediate containment activities.

Examples include:

- Isolating infected endpoints.
- Blocking malicious IP addresses.
- Disabling compromised user accounts.
- Resetting privileged credentials.
- Disconnecting affected servers from the network.
- Blocking malicious email campaigns.
- Restricting remote access.
- Applying temporary firewall rules.
- Disabling compromised applications.
- Suspending vulnerable services.

The specific actions depend on the nature and severity of the incident.

---

# Factors Influencing Containment Decisions

Containment decisions should consider both technical and business factors.

Examples include:

- Incident severity.
- Business criticality.
- Availability requirements.
- Regulatory obligations.
- Safety considerations.
- Potential financial impact.
- Evidence preservation.
- Recovery complexity.

Organizations should avoid containment actions that unnecessarily increase operational disruption.

---

# Preserving Evidence During Containment

Containment should not compromise future investigations.

Responders should:

- Capture volatile evidence before shutdown.
- Preserve system logs.
- Document all actions taken.
- Avoid unnecessary system modifications.
- Maintain Chain of Custody.
- Coordinate with forensic investigators.

Evidence preservation supports Root Cause Analysis, legal review, and regulatory investigations.

---

# Balancing Security and Business Continuity

Immediate containment often requires balancing security objectives with business needs.

Examples include:

- Isolating one workstation rather than shutting down an entire network.
- Blocking a compromised account without affecting other users.
- Redirecting services to backup infrastructure.
- Restricting only affected applications.
- Using temporary controls until permanent remediation is available.

Risk-based decision-making minimizes unnecessary business disruption.

---

# Coordination During Containment

Successful containment requires collaboration across multiple teams.

Participants may include:

- Security Operations Center (SOC).
- Computer Security Incident Response Team (CSIRT).
- IT Operations.
- Network administrators.
- Cloud administrators.
- Business owners.
- Legal counsel.
- Privacy Office.
- Executive Management.

Clear communication ensures containment activities are coordinated and effective.

---

# Risks of Poor Containment

Delayed or ineffective containment may result in:

- Lateral movement.
- Data exfiltration.
- Malware propagation.
- Extended business disruption.
- Increased financial loss.
- Regulatory violations.
- Loss of forensic evidence.
- Reputational damage.

Well-defined containment procedures reduce these risks.

---

# Best Practices

Organizations should:

- Maintain documented containment playbooks.
- Prioritize critical business assets.
- Preserve forensic evidence.
- Coordinate across response teams.
- Use risk-based decision-making.
- Test containment procedures regularly.
- Document all containment actions.
- Review containment effectiveness after each incident.

Prepared organizations respond faster and reduce incident impact.

---

# GRC Perspective

Short-term containment supports Governance, Risk, and Compliance by reducing organizational risk while ensuring that incident response activities remain controlled, documented, and aligned with business objectives.

### Governance

Governance responsibilities include:

- Approving containment procedures.
- Defining decision-making authority.
- Monitoring response effectiveness.
- Allocating incident response resources.
- Providing executive oversight.
- Supporting continual improvement.

### Risk Management

Risk management activities include:

- Limiting business disruption.
- Protecting critical assets.
- Reducing operational risk.
- Preserving organizational resilience.
- Supporting enterprise risk management.
- Preparing for recovery activities.

### Compliance

Short-term containment supports compliance with:

- ISO/IEC 27001 Information Security Management System (ISMS)
- ISO/IEC 27035 Information Security Incident Management
- NIST SP 800-61 Computer Security Incident Handling Guide
- NIST Cybersecurity Framework (CSF)
- General Data Protection Regulation (GDPR)
- NIS2 Directive
- Industry-specific cybersecurity and privacy regulations

Documented containment procedures demonstrate due diligence, support regulatory compliance, and reduce the potential impact of cybersecurity incidents.

---

## Diagram Placeholder

**Title:** Short-Term Containment Process

**Diagram Description:**

```text
      Confirmed Incident
              │
              ▼
    Assess Business Impact
              │
              ▼
 Determine Immediate Actions
              │
              ▼
  Isolate Affected Systems
              │
              ▼
 Block Attacker Activities
              │
              ▼
 Preserve Digital Evidence
              │
              ▼
 Stabilize Environment
              │
              ▼
 Proceed to Investigation
   and Eradication Phase
```

**Caption:**

*"Short-term containment focuses on immediately limiting the spread and impact of a cybersecurity incident while preserving evidence and maintaining essential business operations."*

---

# Practical Example

A multinational logistics company detects ransomware activity spreading across its internal network after several file servers begin encrypting shared documents. The Security Operations Center (SOC) immediately activates the incident response plan. The Computer Security Incident Response Team (CSIRT) isolates the affected servers from the corporate network, disables compromised administrator accounts, blocks communication with known malicious command-and-control (C2) servers, and temporarily suspends remote access services. Before shutting down any systems, investigators capture volatile memory and preserve system logs for forensic analysis. Critical logistics applications continue operating through unaffected backup infrastructure, allowing business operations to continue while the security team investigates the incident and prepares for eradication.

This example demonstrates how rapid, risk-based containment actions can significantly reduce the impact of a cybersecurity incident while preserving evidence and supporting business continuity.

---

## Key Takeaways

- Short-term containment consists of the immediate actions taken to limit the spread and impact of a cybersecurity incident before eradication begins.
- Effective containment focuses on protecting critical assets, preserving evidence, reducing operational disruption, and preventing additional compromise.
- Common containment actions include isolating affected systems, disabling compromised accounts, blocking malicious communications, and implementing temporary security controls.
- Containment decisions should balance cybersecurity objectives with business continuity requirements and regulatory obligations.
- From a Governance, Risk, and Compliance (GRC) perspective, short-term containment strengthens governance, reduces enterprise risk, supports regulatory compliance, and provides a stable foundation for successful eradication and recovery.

- # Long-Term Containment

While short-term containment focuses on immediately stopping the spread of a cybersecurity incident, **long-term containment** aims to maintain a secure and stable operating environment while the organization performs a thorough investigation, eradicates the threat, and prepares for full system recovery. This phase ensures that attackers cannot regain access, malware cannot re-establish persistence, and business operations can continue safely until permanent remediation measures are implemented.

Cybersecurity incidents often require days or even weeks of investigation. During this period, organizations may not yet know the complete scope of the compromise or whether all malicious components have been identified. Returning affected systems to normal operation too quickly may allow attackers to exploit remaining vulnerabilities or reactivate dormant malware. Long-term containment therefore introduces temporary but controlled security measures that reduce risk while enabling investigators to complete forensic analysis and implement permanent corrective actions.

Long-term containment frequently involves rebuilding compromised systems, deploying temporary infrastructure, strengthening access controls, increasing security monitoring, implementing network segmentation, restricting privileged access, and applying temporary compensating controls. These measures provide a secure operating environment until the organization can confidently proceed with eradication and recovery activities. Throughout this process, business continuity requirements remain an important consideration, requiring close coordination between technical teams and business stakeholders.

International standards such as **ISO/IEC 27035**, **ISO/IEC 27001**, **NIST SP 800-61 Revision 2**, and the **NIST Cybersecurity Framework (CSF)** emphasize the importance of maintaining effective containment throughout the incident response lifecycle. Within Governance, Risk, and Compliance (GRC), long-term containment supports enterprise risk management, regulatory compliance, operational resilience, and continual improvement by reducing the likelihood of recurring compromise.

---

# Purpose of Long-Term Containment

Long-term containment provides a secure operating environment while incident response activities continue.

Its objectives include:

- Preventing reinfection.
- Restricting attacker access.
- Supporting forensic investigations.
- Maintaining business operations.
- Protecting sensitive information.
- Reducing operational risk.
- Supporting eradication activities.
- Preparing for system recovery.

Long-term containment bridges the gap between immediate response and permanent remediation.

---

# Long-Term Containment Activities

Organizations may implement several temporary security measures during this phase.

Examples include:

- Rebuilding compromised servers.
- Moving critical services to clean environments.
- Restricting privileged accounts.
- Applying temporary firewall rules.
- Increasing endpoint monitoring.
- Enhancing network segmentation.
- Disabling unnecessary services.
- Deploying additional intrusion detection rules.
- Blocking known Indicators of Compromise (IOCs).
- Increasing log retention.

These controls remain in place until the threat has been completely eliminated.

---

# Temporary Security Controls

Long-term containment often relies on compensating controls rather than permanent solutions.

Examples include:

- Temporary network segmentation.
- Restricted remote access.
- Additional Multi-Factor Authentication (MFA) requirements.
- Enhanced endpoint protection policies.
- Increased Security Operations Center (SOC) monitoring.
- Temporary access restrictions.
- Additional approval requirements for privileged activities.

Compensating controls reduce risk while permanent corrective actions are being implemented.

---

# Supporting Ongoing Investigations

Containment should enable investigators to continue collecting evidence without increasing organizational risk.

Activities may include:

- Preserving forensic images.
- Monitoring attacker behavior.
- Collecting additional logs.
- Conducting threat hunting.
- Validating Indicators of Compromise (IOCs).
- Identifying additional compromised systems.

Organizations should coordinate containment activities with forensic investigators to avoid disrupting evidence collection.

---

# Monitoring During Containment

Continuous monitoring is essential throughout long-term containment.

Security teams should monitor:

- Authentication activity.
- Endpoint alerts.
- Network traffic.
- Privileged account usage.
- Firewall events.
- Cloud activity.
- Security Information and Event Management (SIEM) alerts.
- Endpoint Detection and Response (EDR) telemetry.

Continuous monitoring helps identify attempted reinfection or attacker persistence.

---

# Business Continuity Considerations

Long-term containment should minimize disruption to critical business services.

Organizations may:

- Operate from backup systems.
- Use redundant infrastructure.
- Enable alternate communication channels.
- Prioritize critical applications.
- Implement manual business processes where necessary.
- Coordinate recovery with business units.

Containment decisions should balance security with operational requirements.

---

# Risks of Inadequate Long-Term Containment

Weak containment may result in:

- Attacker persistence.
- Repeat compromise.
- Continued data exfiltration.
- Malware reactivation.
- Extended business disruption.
- Increased recovery costs.
- Regulatory violations.
- Loss of stakeholder confidence.

Maintaining containment until eradication is complete significantly reduces these risks.

---

# Transition to Eradication

Long-term containment concludes when the organization has sufficient confidence to begin eradication activities.

Indicators may include:

- Scope of compromise identified.
- Root Cause Analysis completed.
- Evidence preserved.
- Recovery plans approved.
- Required resources available.
- Business stakeholders informed.

A structured transition reduces the risk of prematurely restoring compromised systems.

---

# Best Practices

Organizations should:

- Maintain containment until threats are fully understood.
- Use compensating security controls.
- Increase monitoring throughout the containment period.
- Coordinate with forensic investigators.
- Document all containment decisions.
- Review containment effectiveness regularly.
- Communicate with business stakeholders.
- Prepare detailed eradication plans before recovery.

Successful long-term containment minimizes risk while supporting business continuity and investigation activities.

---

# GRC Perspective

Long-term containment strengthens Governance, Risk, and Compliance by ensuring that organizations manage cybersecurity incidents using structured, risk-based, and well-documented processes.

### Governance

Governance responsibilities include:

- Approving containment strategies.
- Monitoring incident response progress.
- Supporting executive decision-making.
- Allocating response resources.
- Reviewing containment effectiveness.
- Driving continual improvement.

### Risk Management

Risk management activities include:

- Limiting ongoing exposure.
- Protecting critical business assets.
- Reducing residual risk.
- Supporting enterprise risk management.
- Maintaining operational resilience.
- Preparing for secure recovery.

### Compliance

Long-term containment supports compliance with:

- ISO/IEC 27001 Information Security Management System (ISMS)
- ISO/IEC 27035 Information Security Incident Management
- NIST SP 800-61 Computer Security Incident Handling Guide
- NIST Cybersecurity Framework (CSF)
- General Data Protection Regulation (GDPR)
- NIS2 Directive
- Industry-specific cybersecurity and privacy regulations

Documented long-term containment activities demonstrate due diligence, support regulatory expectations, and provide evidence that cybersecurity risks are being managed throughout the incident lifecycle.

---

## Diagram Placeholder

**Title:** Long-Term Containment Lifecycle

**Diagram Description:**

```text
     Short-Term Containment
               │
               ▼
   Deploy Temporary Controls
               │
               ▼
 Continuous Monitoring
               │
               ▼
 Ongoing Investigation &
   Threat Hunting
               │
               ▼
 Validate Scope of Incident
               │
               ▼
 Maintain Business Operations
               │
               ▼
 Prepare for Eradication
```

**Caption:**

*"Long-term containment maintains a secure operating environment through temporary security controls, continuous monitoring, and coordinated investigation until permanent remediation can be safely performed."*

---

# Practical Example

A multinational retail organization experiences a compromise of its e-commerce platform through a vulnerable third-party application. Following immediate containment, the incident response team migrates customer transactions to a clean backup environment while leaving the compromised servers isolated for forensic investigation. Temporary firewall rules block known malicious IP addresses, privileged access is restricted through additional Multi-Factor Authentication (MFA), and Security Information and Event Management (SIEM) monitoring is enhanced to detect any further suspicious activity. Threat hunters search the environment for additional Indicators of Compromise (IOCs), while system administrators rebuild affected servers using hardened baseline configurations. These temporary containment measures remain in place until investigators confirm that the attacker has been completely removed and recovery activities can begin safely.

This example demonstrates how long-term containment enables organizations to continue business operations securely while supporting thorough investigation, threat eradication, and preparation for system recovery.

---

## Key Takeaways

- Long-term containment maintains a secure operating environment after immediate threats have been stabilized and before full eradication and recovery are completed.
- Organizations use temporary security controls, increased monitoring, network segmentation, and restricted access to prevent attacker persistence and reduce organizational risk.
- Continuous monitoring, threat hunting, and forensic investigations help verify the scope of compromise and ensure that no hidden threats remain.
- Business continuity should remain a key consideration throughout long-term containment to minimize operational disruption while protecting critical assets.
- From a Governance, Risk, and Compliance (GRC) perspective, long-term containment strengthens governance, supports enterprise risk management, demonstrates regulatory compliance, and prepares the organization for secure eradication and recovery.

- 
