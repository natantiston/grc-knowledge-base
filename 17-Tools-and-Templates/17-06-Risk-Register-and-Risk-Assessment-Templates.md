**17.6 Risk Register and Risk Assessment Templates**

### Part 1 – Risk Register and Risk Assessment Template

Risk management is one of the most important practical activities within GRC. A GRC professional must be able to identify risks, analyze their potential impact and likelihood, determine appropriate treatment, assign ownership, and continuously monitor the remaining risk.

A **risk register** provides the organization with a structured record of identified risks and their current treatment status.

The basic risk management flow is:

```text
Risk Identification
        ↓
Risk Analysis
        ↓
Risk Evaluation
        ↓
Risk Treatment
        ↓
Risk Owner
        ↓
Monitoring
        ↓
Residual Risk
        ↓
Review
```

A practical risk register should not simply be a list of problems. It should show the relationship between the **risk, affected asset or process, existing controls, inherent risk, treatment decision, and residual risk**.

A basic **Risk Register Template** can contain:

```text
RISK REGISTER

Risk ID:
Risk Title:

Business Unit:
Process:
Asset / System:

Risk Description:

Risk Category:

Risk Owner:
Risk Assessor:

Threat:
Vulnerability:

Existing Controls:

Inherent Likelihood:
Inherent Impact:
Inherent Risk:

Risk Treatment:

Treatment Action:

Action Owner:
Target Date:

Additional Controls:

Residual Likelihood:
Residual Impact:
Residual Risk:

Risk Acceptance:

Risk Acceptance Owner:

Risk Status:

Review Date:

Evidence:

Comments:
```

The most important part of the template is the **risk statement**.

A weak risk statement might say:

> "Cybersecurity risk."

This provides almost no useful information.

A stronger risk statement identifies the cause, event, and consequence:

> If privileged accounts are not adequately protected, attackers may obtain unauthorized administrative access, resulting in compromise of critical systems and sensitive information.

A practical risk statement can therefore follow this structure:

```text
Because of [cause / vulnerability],
[threat event] could occur,
resulting in [business impact].
```

For example:

> Because privileged accounts are not consistently protected with MFA, an attacker who obtains administrator credentials could gain unauthorized access to critical systems, resulting in data compromise, service disruption, and regulatory exposure.

This provides much more useful information for risk analysis.

---

### Risk Identification

Risk identification begins by understanding the organization's:

* Assets.
* Business processes.
* Information.
* Technologies.
* Threats.
* Vulnerabilities.
* Dependencies.
* Regulatory obligations.
* Third parties.

Examples of risks include:

* Unauthorized access.
* Data breach.
* Ransomware.
* Service disruption.
* Insider threat.
* Third-party compromise.
* Cloud misconfiguration.
* Vulnerability exploitation.
* Regulatory non-compliance.
* Loss of critical information.
* Inadequate disaster recovery.
* Weak security governance.

The GRC professional should avoid identifying risks only from a cybersecurity perspective.

A cybersecurity event may create consequences across multiple business areas.

For example:

```text
Cybersecurity Event
        ↓
System Disruption
        ↓
Business Interruption
        ↓
Financial Loss
        ↓
Customer Impact
        ↓
Regulatory Consequences
        ↓
Reputational Damage
```

Therefore, risk assessment should consider the broader business impact.

---

### Risk Categories

Organizations commonly classify risks into categories.

For example:

| Category             | Example                          |
| -------------------- | -------------------------------- |
| Cybersecurity        | Ransomware attack                |
| Information Security | Unauthorized data disclosure     |
| Technology           | Critical system failure          |
| Third Party          | Supplier compromise              |
| Compliance           | Regulatory violation             |
| Operational          | Business process disruption      |
| Privacy              | Personal data exposure           |
| Strategic            | Security investment misalignment |
| Human                | Insider threat                   |
| Physical             | Data center disruption           |

Categories make it easier to identify patterns and report risk to management.

---

### Risk Description

The risk description should clearly explain what could happen and why it matters.

For example:

> A ransomware attack could encrypt critical production systems and prevent employees from accessing essential business applications, resulting in operational disruption and financial loss.

This is better than:

> Ransomware risk.

The description should provide enough context for someone outside the security team to understand the risk.

---

### Threat and Vulnerability

A risk assessment should distinguish between a **threat** and a **vulnerability**.

A threat is something that could cause harm.

Examples:

* Cybercriminal.
* Malicious insider.
* Nation-state actor.
* Malware.
* Natural disaster.
* Equipment failure.

A vulnerability is a weakness that could be exploited or lead to an undesirable event.

Examples:

* Missing MFA.
* Unpatched software.
* Excessive privileges.
* Weak backup controls.
* Poor configuration.
* Lack of monitoring.

The relationship can be represented as:

```text
Threat
   +
Vulnerability
   ↓
Risk Event
   ↓
Business Impact
```

For example:

```text
Threat:
Credential theft

Vulnerability:
Privileged accounts without MFA

Risk Event:
Unauthorized privileged access

Impact:
System compromise and data loss
```

This structure helps the GRC professional develop a meaningful risk statement.

---

### Existing Controls

The risk register should identify controls that already reduce the risk.

For example:

```text
Risk:
Unauthorized privileged access

Existing Controls:
- MFA
- Privileged Access Management
- Access reviews
- Security monitoring
- Password policy
- Account lockout
```

Existing controls are important because risk should not normally be evaluated as though the organization has no controls at all.

The assessor should determine whether the controls are:

* Designed appropriately.
* Implemented.
* Operating effectively.
* Monitored.
* Supported by evidence.

A control that exists only on paper should not necessarily be treated as fully effective.

---

### Inherent Risk

**Inherent risk** represents the level of risk before considering the effectiveness of existing controls.

For example:

```text
Threat:
Credential compromise

Vulnerability:
Privileged accounts without sufficient protection

Potential Impact:
Very High

Likelihood:
High

Inherent Risk:
Critical
```

Inherent risk helps management understand the underlying exposure.

---

### Likelihood

Likelihood estimates how probable it is that the risk event will occur.

A simple scale might be:

| Score | Likelihood     |
| ----: | -------------- |
|     1 | Rare           |
|     2 | Unlikely       |
|     3 | Possible       |
|     4 | Likely         |
|     5 | Almost Certain |

The organization should define the meaning of each level.

For example:

**1 – Rare**

The event is highly unlikely under normal circumstances.

**3 – Possible**

The event could occur under realistic circumstances.

**5 – Almost Certain**

The event is expected to occur or is already occurring frequently.

The assessment should use evidence wherever possible rather than relying entirely on subjective judgment.

---

### Impact

Impact represents the consequences if the risk event occurs.

Impact may consider:

* Financial loss.
* Operational disruption.
* Customer impact.
* Regulatory consequences.
* Privacy impact.
* Reputational damage.
* Safety implications.
* Data loss.
* Loss of availability.
* Loss of confidentiality.
* Loss of integrity.

A simple impact scale might be:

| Score | Impact        |
| ----: | ------------- |
|     1 | Insignificant |
|     2 | Minor         |
|     3 | Moderate      |
|     4 | Major         |
|     5 | Severe        |

The organization should define objective criteria for each level.

---

### Risk Score

A simple risk model can calculate risk using:

```text
Risk Score = Likelihood × Impact
```

For example:

```text
Likelihood = 4
Impact = 5

Risk Score = 4 × 5
           = 20
```

The organization could then classify the score:

| Score | Rating   |
| ----: | -------- |
|   1–4 | Low      |
|   5–9 | Medium   |
| 10–16 | High     |
| 17–25 | Critical |

The exact thresholds should be established by the organization's approved risk methodology.

The important principle is **consistency**.

The GRC professional should not change the scoring system from one risk assessment to another simply to make a particular risk appear more or less severe.

---

### Risk Matrix

A risk matrix can visualize the relationship between likelihood and impact.

```text
                IMPACT
             1    2    3    4    5

LIKELIHOOD
5            M    H    H    C    C
4            M    M    H    H    C
3            L    M    M    H    H
2            L    L    M    M    H
1            L    L    L    M    M

L = Low
M = Medium
H = High
C = Critical
```

The exact matrix should follow the organization's risk management framework.

The risk matrix provides a consistent way to prioritize risks.

---

### Risk Treatment

Once a risk has been evaluated, management must decide how it will be treated.

Common treatment options include:

1. **Mitigate** – implement additional controls to reduce the risk.
2. **Avoid** – stop the activity creating the risk.
3. **Transfer / Share** – transfer or share some financial or operational consequences through mechanisms such as insurance or contractual arrangements.
4. **Accept** – knowingly retain the risk within approved tolerance.

The treatment decision should be documented.

For example:

```text
Risk:
Ransomware affecting critical systems

Risk Rating:
High

Treatment:
Mitigate

Actions:
- Improve endpoint protection
- Implement immutable backups
- Conduct recovery testing
- Improve network segmentation
```

Risk treatment should be connected to measurable actions.

---

### Risk Owner

Every significant risk should have an accountable **risk owner**.

The risk owner is responsible for ensuring that the risk is appropriately managed.

For example:

| Risk                  | Risk Owner                  |
| --------------------- | --------------------------- |
| Privileged access     | IAM Manager                 |
| Customer data privacy | Data Protection Manager     |
| Third-party security  | Vendor Risk Manager         |
| Cloud security        | Cloud Security Manager      |
| Business continuity   | Business Continuity Manager |

The risk owner is not necessarily the person who performs every remediation activity.

For example:

```text
Risk Owner:
CISO

Action Owner:
IAM Manager
```

The CISO may own the risk while the IAM Manager implements the corrective action.

---

### Residual Risk

After existing and additional controls are considered, the remaining risk is called **residual risk**.

For example:

```text
Inherent Risk:
Critical

       ↓

Additional Controls:
MFA
PAM
Monitoring
Access Reviews

       ↓

Residual Risk:
Medium
```

The goal of security controls is generally not to eliminate every risk.

Some level of residual risk will usually remain.

The organization must determine whether the residual risk is acceptable.

---

### Risk Acceptance

Risk acceptance should be a formal decision.

For example:

```text
Risk:
Legacy application cannot support MFA

Inherent Risk:
High

Compensating Controls:
- Network isolation
- Restricted administrative access
- Enhanced monitoring

Residual Risk:
Medium

Decision:
Accept temporarily

Risk Owner:
Application Director

Review Date:
31 December 2026
```

Risk acceptance should be documented and approved by an appropriate authority.

The risk owner should understand what is being accepted.

---

### Risk Review

Risk registers should not become static spreadsheets that are updated only before an audit.

Risks should be reviewed periodically and when significant changes occur.

Review triggers may include:

* Major technology changes.
* New regulations.
* Significant security incidents.
* New threats.
* New vulnerabilities.
* Business acquisitions.
* New suppliers.
* Major system implementations.
* Changes in business processes.

A risk that was acceptable six months ago may no longer be acceptable after the threat environment changes.

The risk management lifecycle is therefore continuous:

```text
Identify
   ↓
Assess
   ↓
Treat
   ↓
Monitor
   ↓
Review
   ↓
Reassess
```

The practical objective of a risk register is to provide management with a **current and defensible view of the organization's most important security risks**.



