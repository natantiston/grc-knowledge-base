# Lesson 8.5 – Detect (DE): Identifying Cybersecurity Events

> **Chapter:** 08 – NIST Cybersecurity Framework (CSF) 2.0
> **Lesson:** 8.5
> **Part:** 1 of 4
> **Difficulty:** Intermediate
> **Estimated Reading Time:** 10–15 minutes
> **Prerequisites:** Lesson 8.4 – Protect (PR)

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of the **Detect (DE)** Function in the NIST Cybersecurity Framework (CSF) 2.0.
- Explain why continuous monitoring is essential for modern cybersecurity.
- Identify the categories within the Detect Function.
- Understand how security monitoring enables rapid identification of cybersecurity events.
- Recognize how early detection reduces business impact and improves cyber resilience.

---

# Introduction

No organization can prevent every cyberattack.

Even organizations with mature governance, strong identity management, secure configurations, and multiple layers of protection may still experience cybersecurity incidents. Attackers continually develop new techniques, vulnerabilities emerge daily, and human error remains unavoidable.

For this reason, organizations must develop the ability to **identify cybersecurity events as quickly as possible**.

The **Detect (DE)** Function focuses on discovering cybersecurity events through continuous monitoring, analysis, and verification. Rapid detection allows organizations to contain threats before they escalate into significant business disruptions.

The Detect Function answers questions such as:

- Has a cyberattack occurred?
- Is suspicious activity taking place?
- Which systems are affected?
- How serious is the event?
- Does the activity require an incident response?

---

# Purpose of the Detect Function

The Detect Function helps organizations:

- Continuously monitor cybersecurity activities.
- Identify abnormal behavior.
- Detect malicious activity.
- Identify policy violations.
- Discover system failures.
- Support rapid incident response.
- Reduce attacker dwell time.
- Improve organizational resilience.

Effective detection minimizes the time between compromise and response.

---

# Why Detection Matters

Cyberattacks often remain undetected for extended periods.

Examples include:

- Credential theft.
- Insider threats.
- Ransomware.
- Supply chain attacks.
- Cloud compromises.
- Data exfiltration.
- Advanced Persistent Threats (APTs).
- AI-assisted attacks.

The longer an attacker remains undetected, the greater the potential damage.

Early detection significantly reduces operational, financial, and reputational impacts.

---

# Categories within the Detect Function

The Detect Function contains two primary categories.

| Category | Purpose |
|----------|---------|
| DE.CM | Continuous Monitoring |
| DE.AE | Adverse Event Analysis |

Together, these categories enable organizations to identify, analyze, and validate cybersecurity events before initiating response activities.

---

# Continuous Monitoring (DE.CM)

Continuous monitoring provides ongoing visibility into organizational systems and networks.

Rather than relying on periodic reviews, organizations continuously collect and analyze security information.

Monitoring may include:

- Network traffic.
- Endpoint activity.
- Authentication events.
- Cloud services.
- Applications.
- Databases.
- Industrial Control Systems (ICS).
- AI platforms.

Continuous monitoring forms the operational foundation of cybersecurity detection.

---

# What Should Be Monitored?

Organizations should monitor:

### User Activity

Examples:

- Login attempts.
- Privileged account usage.
- Failed authentication.
- Geographic anomalies.
- Unusual working hours.

---

### Network Activity

Examples:

- Unexpected traffic.
- Unauthorized connections.
- Data transfers.
- Command-and-control communications.
- Network scanning.

---

### Endpoint Activity

Examples:

- Malware detection.
- Unauthorized software.
- Suspicious processes.
- Registry modifications.
- File encryption behavior.

---

### Cloud Activity

Examples:

- Identity misuse.
- Public storage exposure.
- Configuration changes.
- API activity.
- Administrative actions.

---

### Application Activity

Examples:

- Failed logins.
- Privilege escalation.
- API abuse.
- Database queries.
- Unexpected application behavior.

---

# Security Monitoring Technologies

Organizations commonly implement:

- Security Information and Event Management (SIEM)
- Endpoint Detection and Response (EDR)
- Network Detection and Response (NDR)
- Intrusion Detection Systems (IDS)
- Extended Detection and Response (XDR)
- Security analytics platforms
- Cloud security monitoring
- User and Entity Behavior Analytics (UEBA)

These technologies collect, correlate, and analyze security data from multiple sources.

---

# Logging

Effective detection depends on high-quality logging.

Organizations should collect logs from:

- Operating systems.
- Applications.
- Firewalls.
- Cloud platforms.
- Databases.
- Active Directory.
- VPN gateways.
- Email systems.
- Identity providers.

Logs provide the evidence needed to identify and investigate cybersecurity events.

---

# Characteristics of Effective Logging

Logs should be:

- Accurate.
- Time synchronized.
- Tamper resistant.
- Securely stored.
- Retained appropriately.
- Easily searchable.
- Regularly reviewed.

Incomplete or inaccurate logs significantly reduce detection capabilities.

---

# Baseline Behavior

Organizations should understand what "normal" looks like.

Examples include:

- Typical user login locations.
- Normal network traffic volumes.
- Expected application behavior.
- Standard administrative activities.
- Routine cloud operations.

Once normal behavior is established, abnormal activities become easier to identify.

---

# Detecting Anomalies

An anomaly is activity that differs from expected behavior.

Examples:

- Multiple failed login attempts.
- Administrator logins at unusual hours.
- Unexpected outbound data transfers.
- Privilege escalation.
- Unauthorized software installation.
- Sudden encryption of large numbers of files.

Anomalies are not always attacks, but they warrant investigation.

---

# Relationship to the Protect Function

Protective controls attempt to prevent attacks.

Detection assumes that prevention may eventually fail.

```
Protect

↓

Prevent Attacks

↓

Detect

↓

Identify Suspicious Activity

↓

Respond

↓

Contain the Incident
```

Early detection limits attacker opportunities and supports faster response.

---

📊 **Diagram Placeholder**

**Title:** The Detect Function in NIST CSF 2.0

**Diagram Description:**

Create a monitoring architecture.

Multiple log sources:

- Endpoints
- Servers
- Firewalls
- Applications
- Cloud Platforms
- Identity Systems
- Network Devices
- AI Systems

↓

Central Monitoring Platform (SIEM/XDR)

↓

Correlation & Analytics

↓

Anomaly Detection

↓

Security Alerts

↓

Incident Response Team

Caption:

*"The Detect Function continuously monitors organizational activities, identifies abnormal behavior, and generates actionable alerts that enable rapid incident response."*

---

# Best Practices

Organizations should:

- Implement continuous security monitoring across endpoints, networks, cloud environments, applications, identity systems, operational technology, and critical business services.
- Collect, protect, and retain high-quality security logs from all significant technology platforms to support monitoring, investigations, compliance, and forensic analysis.
- Establish baseline behavior for users, systems, applications, and networks so that anomalous activity can be identified quickly and accurately.
- Deploy security monitoring technologies such as SIEM, EDR, NDR, XDR, IDS, and UEBA to improve visibility across complex technology environments.
- Synchronize system clocks and standardize logging configurations to improve event correlation and investigation accuracy.
- Prioritize monitoring of high-value assets, privileged accounts, critical business services, and externally exposed systems that present the greatest organizational risk.
- Continuously review monitoring coverage and update detection capabilities to address emerging threats, new technologies, cloud adoption, AI systems, and evolving business requirements.
- Integrate monitoring results with governance, risk management, and incident response processes so that security events are evaluated and addressed promptly.

These practices strengthen an organization's ability to identify cybersecurity events early, reduce attacker dwell time, support effective incident response, and improve overall cyber resilience.

---

# Practical Example

A multinational healthcare provider operates hospitals, cloud-hosted electronic health record (EHR) systems, medical devices, telemedicine platforms, and AI-assisted diagnostic services. To implement the Detect Function of the NIST Cybersecurity Framework 2.0, the organization deploys a centralized Security Information and Event Management (SIEM) platform that collects logs from servers, firewalls, endpoint devices, cloud services, Active Directory, VPN gateways, medical applications, and network infrastructure. Endpoint Detection and Response (EDR) agents continuously monitor employee workstations and critical medical systems, while User and Entity Behavior Analytics (UEBA) establishes normal patterns of user activity and automatically identifies unusual behavior.

One evening, the monitoring platform detects multiple failed administrative login attempts followed by a successful login from an unfamiliar geographic location and unusually large outbound data transfers from a patient records database. Automated correlation rules classify the activity as high risk and immediately generate alerts for the Security Operations Center (SOC). Early detection allows analysts to investigate and contain the incident before significant patient information is compromised, demonstrating how continuous monitoring supports rapid response, regulatory compliance, and organizational resilience.

