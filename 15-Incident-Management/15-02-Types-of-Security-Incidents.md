# 15.2 Types of Security Incidents

## Part 1 – Malware and Ransomware

> **Chapter:** 15 – Incident Management
>
> **Topic:** Malware and Ransomware
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

## Introduction

Not all cybersecurity incidents are the same. Security incidents vary significantly in their causes, techniques, objectives, severity, and business impact. Understanding the different types of security incidents enables organizations to develop appropriate detection capabilities, response procedures, recovery plans, and preventive controls. Effective incident management begins with correctly identifying the nature of an incident so that response teams can prioritize actions, allocate resources, and minimize organizational damage.

Among all categories of cybersecurity incidents, **malware** and **ransomware** remain two of the most common and destructive threats faced by organizations worldwide. Cybercriminals use malicious software to steal information, disrupt operations, gain unauthorized access, conduct espionage, or extort organizations for financial gain. Modern malware campaigns are increasingly sophisticated, often combining multiple attack techniques such as phishing, credential theft, privilege escalation, lateral movement, and data exfiltration before deploying ransomware or other malicious payloads.

Ransomware has evolved from a relatively simple malware variant into one of the most significant cybersecurity risks for governments, critical infrastructure operators, healthcare providers, financial institutions, and private enterprises. Many modern ransomware groups now employ **double extortion**, where they not only encrypt systems but also steal sensitive data and threaten to publish it unless a ransom is paid. Some groups have expanded to **triple extortion**, adding Distributed Denial-of-Service (DDoS) attacks or targeting customers and business partners to increase pressure on victims.

International standards such as **ISO/IEC 27035**, **ISO/IEC 27001**, **NIST SP 800-61 Revision 2**, and the **NIST Cybersecurity Framework (CSF)** emphasize preparedness, early detection, rapid containment, and structured recovery when responding to malware incidents. Within Governance, Risk, and Compliance (GRC), malware incidents provide valuable insights into control effectiveness, vulnerability management, employee awareness, and organizational resilience.

This lesson introduces the characteristics of malware and ransomware, explains how they infect systems, examines their business impact, and discusses best practices for prevention, detection, response, and recovery.

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Define malware and ransomware.
- Identify common types of malware.
- Explain how ransomware attacks are conducted.
- Understand the business impact of malware incidents.
- Recognize common infection vectors.
- Apply best practices for preventing and responding to malware incidents.

---

# What is Malware?

**Malware** (malicious software) is any software intentionally designed to disrupt operations, damage systems, steal information, gain unauthorized access, or perform malicious activities without the user's knowledge or consent.

Malware can affect:

- End-user devices.
- Servers.
- Mobile devices.
- Cloud workloads.
- Industrial control systems.
- Internet of Things (IoT) devices.

Attackers continuously modify malware to evade detection and bypass traditional security controls.

---

# Common Types of Malware

Malware exists in many forms, each designed to achieve different objectives.

### Virus

A virus attaches itself to legitimate files or programs and spreads when those files are executed.

Characteristics include:

- Requires user interaction.
- Infects executable files.
- Spreads between systems.
- May corrupt or destroy data.

---

### Worm

A worm spreads automatically across networks without requiring user interaction.

Characteristics include:

- Self-replicating.
- Exploits network vulnerabilities.
- Consumes network resources.
- Spreads rapidly.

---

### Trojan Horse

A Trojan disguises itself as legitimate software while secretly performing malicious activities.

Common objectives include:

- Installing backdoors.
- Stealing credentials.
- Downloading additional malware.
- Providing remote attacker access.

---

### Spyware

Spyware secretly monitors user activity.

It may collect:

- Login credentials.
- Browsing history.
- Financial information.
- Personal data.
- Keystrokes.

Spyware often supports identity theft and financial fraud.

---

### Adware

Adware displays unwanted advertisements and may collect user behavior information.

Although less destructive than other malware, it can:

- Reduce system performance.
- Track user activity.
- Introduce additional malware.

---

### Rootkits

Rootkits hide malicious activity by modifying operating system functions.

They enable attackers to:

- Maintain persistence.
- Hide malware.
- Conceal attacker activity.
- Evade detection.

Rootkits are particularly difficult to detect and remove.

---

# What is Ransomware?

**Ransomware** is a type of malware that encrypts files, systems, or entire networks and demands payment in exchange for restoring access.

Modern ransomware attacks often include:

- File encryption.
- Data theft.
- System disruption.
- Extortion.
- Public data leak threats.

Ransomware has become one of the most financially damaging forms of cybercrime.

---

# The Ransomware Attack Lifecycle

Although attacks vary, a typical ransomware campaign follows several stages:

1. Initial access.
2. Malware deployment.
3. Privilege escalation.
4. Lateral movement.
5. Data discovery.
6. Data exfiltration.
7. File encryption.
8. Ransom demand.

Understanding this lifecycle helps organizations detect attacks before encryption occurs.

---

# Common Infection Vectors

Malware commonly enters organizations through:

- Phishing emails.
- Malicious attachments.
- Compromised websites.
- Drive-by downloads.
- Exploited software vulnerabilities.
- Weak Remote Desktop Protocol (RDP) access.
- USB devices.
- Third-party software compromises.

Most successful attacks exploit a combination of technical vulnerabilities and human error.

---

# Business Impact

Malware and ransomware incidents may result in:

- Operational downtime.
- Financial losses.
- Data breaches.
- Loss of customer trust.
- Regulatory penalties.
- Business interruption.
- Intellectual property theft.
- Reputational damage.

Critical infrastructure organizations may also experience public safety consequences.

---

# Prevention Strategies

Organizations should implement multiple layers of defense.

Preventive measures include:

- Endpoint protection.
- Multi-factor authentication (MFA).
- Security awareness training.
- Vulnerability management.
- Regular software patching.
- Network segmentation.
- Email security controls.
- Secure backups.

A layered security approach significantly reduces infection risk.

---

# Responding to Malware Incidents

When malware is detected, organizations should:

1. Isolate affected systems.
2. Preserve forensic evidence.
3. Identify the malware type.
4. Determine the scope of infection.
5. Remove malicious software.
6. Restore systems from trusted backups.
7. Monitor for reinfection.
8. Conduct a lessons learned review.

Response actions should follow the organization's incident response plan.

---

# Best Practices

Organizations should:

- Deploy Endpoint Detection and Response (EDR) solutions.
- Maintain offline and immutable backups.
- Conduct regular phishing awareness training.
- Monitor network activity continuously.
- Perform vulnerability assessments.
- Restrict administrative privileges.
- Test ransomware recovery procedures.
- Conduct regular tabletop exercises.

Prepared organizations recover significantly faster from malware incidents.

---

# GRC Perspective

Malware and ransomware incidents directly impact Governance, Risk, and Compliance activities.

### Governance

Governance responsibilities include:

- Establishing malware response policies.
- Defining incident escalation procedures.
- Providing executive oversight.
- Approving recovery strategies.
- Allocating cybersecurity resources.
- Supporting continual improvement.

### Risk Management

Risk management activities include:

- Identifying malware threats.
- Assessing business impacts.
- Prioritizing critical assets.
- Monitoring residual risks.
- Updating enterprise risk registers.
- Improving cyber resilience.

### Compliance

Malware incident management supports compliance with:

- ISO/IEC 27001 Information Security Management System (ISMS)
- ISO/IEC 27035 Information Security Incident Management
- NIST SP 800-61 Computer Security Incident Handling Guide
- NIST Cybersecurity Framework (CSF)
- General Data Protection Regulation (GDPR), where personal data is affected
- NIS2 Directive
- Industry-specific cybersecurity regulations

An effective malware response program helps organizations reduce operational disruption, protect sensitive information, and demonstrate regulatory accountability.

---

## Diagram Placeholder

**Title:** Typical Ransomware Attack Lifecycle

**Diagram Description:**

```text
Initial Access
      │
      ▼
Malware Deployment
      │
      ▼
Privilege Escalation
      │
      ▼
Lateral Movement
      │
      ▼
Data Discovery
      │
      ▼
Data Exfiltration
      │
      ▼
File Encryption
      │
      ▼
Ransom Demand
```

**Caption:**

*"Modern ransomware attacks typically progress through multiple stages before encrypting systems and demanding payment, giving organizations opportunities to detect and stop the attack before significant damage occurs."*

---

# Practical Example

A manufacturing company receives multiple reports that employees are unable to access shared files. Shortly afterward, a ransom note appears on several workstations demanding payment in cryptocurrency. The Security Operations Center (SOC) discovers that attackers gained initial access through a phishing email containing a malicious attachment. After compromising one employee account, the attackers moved laterally across the network, escalated privileges, disabled certain security tools, and exfiltrated sensitive engineering documents before encrypting hundreds of servers.

The Computer Security Incident Response Team (CSIRT) immediately isolates affected systems, disconnects infected network segments, activates the organization's incident response plan, and begins restoring critical systems from offline backups. Legal, Compliance, and Executive Management coordinate regulatory notifications and stakeholder communications, while forensic investigators determine the root cause. Following recovery, the organization strengthens email security, implements phishing-resistant multi-factor authentication, expands endpoint detection capabilities, and enhances employee cybersecurity awareness training.

This case demonstrates how rapid detection, structured incident response, and resilient backup strategies can significantly reduce the impact of malware and ransomware incidents.

---

## Key Takeaways

- Malware is malicious software designed to disrupt operations, steal information, or gain unauthorized access to systems.
- Ransomware is a specialized form of malware that encrypts data or systems and often combines encryption with data theft and extortion.
- Common malware types include viruses, worms, Trojans, spyware, adware, and rootkits, each with different methods of operation and objectives.
- Effective prevention requires layered security controls, including endpoint protection, vulnerability management, security awareness, network segmentation, and secure backups.
- From a Governance, Risk, and Compliance (GRC) perspective, malware and ransomware incidents highlight the importance of governance, risk management, regulatory compliance, and continual improvement in strengthening organizational cyber resilience.

- # Phishing and Social Engineering

While malware exploits technical vulnerabilities, **phishing** and **social engineering** primarily exploit human behavior. Cybercriminals understand that employees, contractors, and business partners are often the easiest path into an organization's environment. Rather than attacking firewalls or encryption directly, attackers manipulate individuals into revealing confidential information, transferring funds, installing malicious software, or granting unauthorized access. As a result, phishing and social engineering remain among the leading causes of cybersecurity incidents worldwide.

Social engineering attacks are particularly dangerous because they rely on deception rather than technical sophistication. An attacker may impersonate a trusted colleague, senior executive, customer, supplier, government official, or IT support technician to convince a victim to perform an action that compromises security. Even organizations with mature technical defenses can become victims if employees are not adequately trained to recognize manipulation techniques.

**Phishing** is the most common form of social engineering. It typically involves fraudulent emails, messages, or websites designed to trick users into disclosing credentials, downloading malware, approving fraudulent transactions, or sharing sensitive information. Modern phishing campaigns frequently leverage artificial intelligence, publicly available information, and compromised accounts to create highly convincing attacks that are difficult to distinguish from legitimate communications.

International standards such as **ISO/IEC 27001**, **ISO/IEC 27035**, **NIST SP 800-61 Revision 2**, and the **NIST Cybersecurity Framework (CSF)** emphasize the importance of user awareness, secure communication practices, incident reporting, and layered security controls to reduce the likelihood and impact of phishing and social engineering attacks.

Within Governance, Risk, and Compliance (GRC), phishing incidents provide valuable insight into employee awareness, organizational culture, identity and access management, communication processes, and the effectiveness of preventive security controls.

---

# What is Social Engineering?

**Social engineering** is the psychological manipulation of individuals to persuade them to perform actions or reveal confidential information that benefits an attacker.

Instead of exploiting technology, attackers exploit:

- Trust.
- Curiosity.
- Fear.
- Urgency.
- Authority.
- Greed.
- Helpfulness.

Social engineering is often the first stage of a larger cyberattack.

---

# What is Phishing?

**Phishing** is a social engineering technique that uses fraudulent communications to trick individuals into revealing sensitive information or performing actions that compromise security.

Common phishing objectives include:

- Stealing usernames and passwords.
- Delivering malware.
- Collecting financial information.
- Bypassing multi-factor authentication.
- Gaining unauthorized system access.
- Conducting financial fraud.

Phishing attacks are typically delivered through email but increasingly use other communication channels.

---

# Types of Phishing

Organizations may encounter several forms of phishing.

### Email Phishing

Mass-distributed fraudulent emails sent to many recipients.

Common characteristics include:

- Fake login pages.
- Malicious attachments.
- Fraudulent hyperlinks.
- Requests for sensitive information.

---

### Spear Phishing

Highly targeted phishing attacks directed at specific individuals or departments.

Attackers often research:

- Job roles.
- Organizational structure.
- Business relationships.
- Publicly available information.

Because messages appear personalized, spear phishing is generally more effective than mass phishing.

---

### Whaling

Whaling targets senior executives and high-value individuals.

Typical targets include:

- Chief Executive Officer (CEO).
- Chief Financial Officer (CFO).
- Chief Information Officer (CIO).
- Board members.
- Senior managers.

Successful whaling attacks can result in significant financial or reputational damage.

---

### Smishing

**Smishing** uses SMS or text messages to deceive victims.

Examples include:

- Fake delivery notifications.
- Banking alerts.
- Account verification requests.
- Prize notifications.

---

### Vishing

**Vishing** (voice phishing) uses telephone calls or voice messages.

Attackers may impersonate:

- IT support.
- Banks.
- Government agencies.
- Business partners.
- Law enforcement.

Victims may be persuaded to reveal confidential information or authorize fraudulent transactions.

---

# Common Social Engineering Techniques

Attackers use numerous psychological tactics, including:

### Pretexting

Creating a believable fictional scenario to obtain information.

Example:

An attacker pretends to be an external auditor requesting employee records.

---

### Baiting

Offering something attractive to encourage unsafe behavior.

Examples include:

- Free software downloads.
- Infected USB devices.
- Fake promotional offers.

---

### Tailgating (Piggybacking)

An attacker gains physical access by following an authorized employee into a secure area without proper authentication.

---

### Quid Pro Quo

The attacker offers a service or benefit in exchange for sensitive information.

Example:

A fake IT technician offers technical support while requesting login credentials.

---

# Indicators of Phishing Attempts

Employees should watch for:

- Unexpected emails.
- Urgent requests.
- Poor grammar or spelling.
- Suspicious hyperlinks.
- Unknown attachments.
- Requests for passwords.
- Requests for financial transfers.
- Unusual sender addresses.

Recognizing these warning signs significantly reduces organizational risk.

---

# Business Impact

Successful phishing attacks may result in:

- Credential theft.
- Malware infections.
- Ransomware deployment.
- Financial fraud.
- Data breaches.
- Identity theft.
- Business Email Compromise (BEC).
- Regulatory violations.

Even a single compromised account can enable attackers to move laterally across an organization's network.

---

# Preventive Controls

Organizations should implement layered defenses, including:

- Security awareness training.
- Multi-factor authentication (MFA).
- Email filtering.
- Anti-phishing technologies.
- DNS filtering.
- Secure web gateways.
- Domain protection technologies (SPF, DKIM, and DMARC).
- Regular phishing simulations.

Technology alone cannot eliminate phishing risk; informed users remain a critical defense.

---

# Responding to Phishing Incidents

When a phishing attempt is identified, organizations should:

1. Report the suspicious message immediately.
2. Isolate affected systems if compromise is suspected.
3. Reset compromised credentials.
4. Block malicious domains and email addresses.
5. Scan systems for malware.
6. Investigate the scope of the attack.
7. Notify affected stakeholders if necessary.
8. Conduct a post-incident review.

Prompt reporting helps prevent additional users from becoming victims.

---

# Best Practices

Organizations should:

- Conduct regular phishing awareness campaigns.
- Perform simulated phishing exercises.
- Verify financial requests through secondary channels.
- Require MFA for critical systems.
- Limit administrative privileges.
- Encourage employees to report suspicious communications.
- Continuously monitor authentication activity.
- Review and update awareness training regularly.

Building a strong security culture significantly reduces phishing success rates.

---

# GRC Perspective

Phishing and social engineering incidents affect every component of Governance, Risk, and Compliance.

### Governance

Governance responsibilities include:

- Establishing security awareness policies.
- Defining acceptable use policies.
- Approving awareness programs.
- Supporting executive communication.
- Promoting security culture.
- Monitoring program effectiveness.

### Risk Management

Risk management activities include:

- Identifying human-related risks.
- Assessing phishing exposure.
- Monitoring employee susceptibility.
- Updating enterprise risk registers.
- Implementing mitigating controls.
- Improving organizational resilience.

### Compliance

Managing phishing risks supports compliance with:

- ISO/IEC 27001 Information Security Management System (ISMS)
- ISO/IEC 27035 Information Security Incident Management
- NIST SP 800-61 Computer Security Incident Handling Guide
- NIST Cybersecurity Framework (CSF)
- General Data Protection Regulation (GDPR), where personal data is involved
- NIS2 Directive
- Industry-specific cybersecurity regulations

An effective anti-phishing program combines governance, technology, training, and continuous monitoring to reduce organizational risk.

---

## Diagram Placeholder

**Title:** Typical Phishing Attack Flow

**Diagram Description:**

```text
Attacker Creates
Fraudulent Message
        │
        ▼
Victim Receives Email,
SMS, or Phone Call
        │
        ▼
Victim Clicks Link,
Downloads Attachment,
or Shares Information
        │
        ▼
Credential Theft,
Malware Installation,
or Unauthorized Access
        │
        ▼
Incident Detection
and Response
```

**Caption:**

*"Phishing attacks rely on deception rather than technical exploits, making user awareness and timely incident response essential components of organizational cybersecurity."*

---

# Practical Example

An employee in the finance department receives an email that appears to come from the Chief Financial Officer (CFO), requesting an urgent wire transfer to a new supplier account. The email uses the company's branding and contains language that creates a sense of urgency. Before processing the payment, the employee follows the organization's verification procedure by contacting the CFO through a separate communication channel. The CFO confirms that no such request was made, revealing the email to be a **Business Email Compromise (BEC)** attempt.

The employee reports the email to the Security Operations Center (SOC), which blocks the sender, identifies similar messages delivered to other employees, and updates email filtering rules. The incident response team investigates the attack, while the security awareness team uses the event as a training example to reinforce procedures for verifying financial requests.

This example demonstrates how effective security awareness, well-defined business processes, and prompt reporting can prevent phishing attempts from escalating into significant security incidents.

---

## Key Takeaways

- Social engineering exploits human psychology to gain unauthorized access or sensitive information rather than exploiting technical vulnerabilities.
- Phishing is the most common form of social engineering and includes email phishing, spear phishing, whaling, smishing, and vishing.
- Successful phishing attacks can lead to credential theft, malware infections, ransomware deployment, financial fraud, and data breaches.
- Organizations reduce phishing risk through layered security controls, employee awareness training, phishing simulations, multi-factor authentication, and robust email security.
- From a Governance, Risk, and Compliance (GRC) perspective, phishing prevention requires coordinated governance, risk management, compliance, technology, and organizational awareness to strengthen overall cyber resilience.

- 
