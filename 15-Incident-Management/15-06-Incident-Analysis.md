# 15.6 Incident Analysis

## Part 1 – Root Cause Analysis

> **Chapter:** 15 – Incident Management
>
> **Topic:** Root Cause Analysis
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

## Introduction

Successfully containing a cybersecurity incident is only part of an effective incident response program. To prevent similar incidents from recurring, organizations must understand **why** the incident occurred, **how** the attacker exploited vulnerabilities, and **what** underlying weaknesses allowed the incident to succeed. This systematic investigation is known as **Root Cause Analysis (RCA)**. Rather than focusing solely on the immediate symptoms of an incident, RCA seeks to identify the fundamental causes that, if addressed, will reduce the likelihood of future occurrences.

Cybersecurity incidents rarely result from a single failure. Instead, they often arise from a combination of technical vulnerabilities, process deficiencies, human errors, inadequate security controls, misconfigurations, or governance weaknesses. For example, a ransomware attack may initially appear to result from a malicious email attachment, but deeper analysis could reveal multiple contributing factors, including ineffective email filtering, delayed security patching, insufficient employee awareness training, and inadequate network segmentation. Root Cause Analysis examines these interconnected factors to identify the true origin of the incident.

Conducting a thorough Root Cause Analysis enables organizations to move beyond reactive incident handling toward proactive risk reduction. The findings help security teams strengthen preventive controls, improve detection capabilities, update security policies, enhance employee training, and refine incident response procedures. RCA also provides valuable input into enterprise risk management by identifying systemic issues that may affect other business processes or technology environments.

International standards such as **ISO/IEC 27035**, **ISO/IEC 27001**, **NIST SP 800-61 Revision 2**, and the **NIST Cybersecurity Framework (CSF)** recommend performing Root Cause Analysis as part of the post-incident process. Within Governance, Risk, and Compliance (GRC), RCA supports continual improvement, strengthens governance, improves risk management, and demonstrates organizational commitment to learning from cybersecurity incidents.

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Define Root Cause Analysis (RCA).
- Explain the objectives of Root Cause Analysis.
- Identify common causes of cybersecurity incidents.
- Describe widely used Root Cause Analysis techniques.
- Understand how RCA supports continual improvement.
- Explain the relationship between RCA and Governance, Risk, and Compliance (GRC).

---

# What is Root Cause Analysis?

**Root Cause Analysis (RCA)** is a structured process used to identify the underlying causes of a cybersecurity incident rather than addressing only its immediate effects.

The objective is to answer questions such as:

- What happened?
- How did it happen?
- Why did it happen?
- Which controls failed?
- What allowed the incident to succeed?
- How can similar incidents be prevented?

The goal is to eliminate the underlying causes rather than repeatedly treating the symptoms.

---

# Why Root Cause Analysis Matters

Without Root Cause Analysis, organizations risk experiencing similar incidents repeatedly.

RCA helps organizations to:

- Prevent recurring incidents.
- Improve security controls.
- Strengthen policies and procedures.
- Reduce operational risk.
- Improve employee awareness.
- Enhance incident response.
- Support compliance.
- Increase organizational resilience.

Every significant cybersecurity incident should result in meaningful organizational learning.

---

# Common Root Causes

Cybersecurity incidents often involve multiple contributing factors.

Common root causes include:

- Unpatched software vulnerabilities.
- Weak passwords.
- Misconfigured systems.
- Human error.
- Phishing attacks.
- Inadequate access controls.
- Insufficient security monitoring.
- Third-party security weaknesses.
- Lack of employee awareness.
- Incomplete security policies.

Identifying all contributing factors provides a more complete understanding of the incident.

---

# Immediate Cause vs. Root Cause

Organizations should distinguish between immediate causes and underlying root causes.

| Immediate Cause | Root Cause |
|-----------------|------------|
| Employee clicked a phishing link | Insufficient security awareness training |
| Malware executed successfully | Endpoint protection was outdated |
| Database compromised | Weak access control and poor credential management |
| Unauthorized administrator access | Lack of Multi-Factor Authentication (MFA) |
| Data exfiltration detected | Network segmentation and monitoring deficiencies |

Addressing only the immediate cause may not prevent future incidents.

---

# Root Cause Analysis Techniques

Several structured techniques can be used to identify underlying causes.

Common methods include:

- Five Whys Analysis.
- Fishbone (Ishikawa) Diagram.
- Fault Tree Analysis.
- Event Timeline Analysis.
- Cause-and-Effect Analysis.
- Process Mapping.

Organizations may select different techniques depending on the complexity of the incident.

---

# The Five Whys Technique

The **Five Whys** method repeatedly asks "Why?" until the underlying cause is identified.

Example:

**Problem:** Ransomware encrypted a file server.

- Why? → A malicious attachment was opened.
- Why? → The employee believed the email was legitimate.
- Why? → Security awareness training was outdated.
- Why? → Annual training had not been conducted.
- Why? → No governance process existed to monitor training compliance.

The final answer identifies a governance weakness rather than only a user error.

---

# Fishbone (Ishikawa) Diagram

The Fishbone Diagram categorizes possible causes into logical groups.

Typical categories include:

- People.
- Process.
- Technology.
- Policies.
- Environment.
- Third Parties.

This approach helps investigators examine incidents from multiple perspectives rather than focusing solely on technical failures.

---

# Gathering Information

Root Cause Analysis relies on comprehensive evidence.

Sources of information include:

- Incident reports.
- Security logs.
- Forensic evidence.
- System configurations.
- Network traffic.
- Threat intelligence.
- User interviews.
- Audit findings.

Accurate information improves the quality of the analysis.

---

# Corrective and Preventive Actions

Root Cause Analysis should result in actionable improvements.

Examples include:

- Applying security patches.
- Strengthening authentication.
- Updating security policies.
- Improving monitoring.
- Enhancing employee awareness training.
- Deploying additional security controls.
- Improving vendor oversight.
- Updating incident response playbooks.

Actions should address both technical and organizational weaknesses.

---

# Best Practices

Organizations should:

- Conduct RCA after significant incidents.
- Involve technical and business stakeholders.
- Focus on facts rather than blame.
- Document findings thoroughly.
- Identify multiple contributing factors.
- Assign corrective actions.
- Track remediation progress.
- Review effectiveness after implementation.

Root Cause Analysis should support learning and continuous improvement rather than assigning fault.

---

# GRC Perspective

Root Cause Analysis supports Governance, Risk, and Compliance by identifying systemic weaknesses and enabling informed decisions that reduce organizational risk.

### Governance

Governance responsibilities include:

- Reviewing RCA findings.
- Approving corrective actions.
- Monitoring remediation progress.
- Updating governance processes.
- Providing executive oversight.
- Driving continual improvement.

### Risk Management

Risk management activities include:

- Identifying systemic weaknesses.
- Updating enterprise risk registers.
- Improving preventive controls.
- Reducing recurring incidents.
- Monitoring residual risk.
- Strengthening cyber resilience.

### Compliance

Root Cause Analysis supports compliance with:

- ISO/IEC 27001 Information Security Management System (ISMS)
- ISO/IEC 27035 Information Security Incident Management
- NIST SP 800-61 Computer Security Incident Handling Guide
- NIST Cybersecurity Framework (CSF)
- General Data Protection Regulation (GDPR)
- NIS2 Directive
- Industry-specific cybersecurity and privacy regulations

Documented Root Cause Analysis demonstrates due diligence, supports continual improvement, and provides evidence of effective incident management during audits and regulatory reviews.

---

## Diagram Placeholder

**Title:** Root Cause Analysis Process

**Diagram Description:**

```text
      Cybersecurity Incident
               │
               ▼
      Collect Information
               │
               ▼
      Analyze Contributing
            Factors
               │
               ▼
      Identify Root Cause
               │
               ▼
   Define Corrective Actions
               │
               ▼
 Implement Improvements
               │
               ▼
 Prevent Future Incidents
```

**Caption:**

*"Root Cause Analysis identifies the underlying causes of cybersecurity incidents and drives corrective actions that strengthen the organization's security posture and reduce the likelihood of recurrence."*

---

# Practical Example

A multinational manufacturing company experiences a ransomware attack that encrypts production servers and disrupts factory operations. Initial investigation reveals that an employee opened a phishing email containing a malicious attachment. During the Root Cause Analysis, investigators discover that the affected workstation had not received recent security patches, endpoint protection signatures were outdated, and employees had not completed mandatory security awareness training for more than eighteen months. In addition, privileged accounts lacked Multi-Factor Authentication (MFA), allowing attackers to move laterally after compromising user credentials. Based on these findings, the organization updates its patch management process, strengthens email filtering, implements MFA for privileged accounts, launches an organization-wide awareness campaign, and revises governance procedures to monitor security training compliance.

This example demonstrates that cybersecurity incidents often result from multiple technical, procedural, and governance weaknesses rather than a single isolated failure.

---

## Key Takeaways

- Root Cause Analysis (RCA) identifies the underlying causes of cybersecurity incidents to prevent recurrence rather than simply resolving immediate symptoms.
- Effective RCA examines technical vulnerabilities, process failures, human factors, governance weaknesses, and security control deficiencies.
- Structured techniques such as the Five Whys and Fishbone Diagram help organizations systematically identify contributing factors and root causes.
- Corrective and preventive actions should address both technical and organizational weaknesses to strengthen long-term security.
- From a Governance, Risk, and Compliance (GRC) perspective, Root Cause Analysis supports continual improvement, enhances governance, reduces enterprise risk, and demonstrates due diligence through documented lessons learned and remediation activities.

- 
