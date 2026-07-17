# Lesson 9.7 – Requirement 5: Protect All Systems and Networks from Malicious Software

> **Chapter:** 09 – Payment Card Industry Data Security Standard (PCI DSS) 4.0
>
> **Lesson:** 9.7
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of PCI DSS Requirement 5.
- Explain how malware threatens payment card environments.
- Identify the different types of malicious software.
- Understand PCI DSS anti-malware requirements.
- Recognize enterprise best practices for malware prevention and detection.

---

# Introduction

Malicious software, commonly known as **malware**, remains one of the most common attack methods used by cybercriminals to compromise payment systems. Malware can steal payment card information, encrypt business data for ransom, capture user credentials, disrupt business operations, or provide attackers with unauthorized access to critical systems.

PCI DSS Requirement 5 requires organizations to protect all systems and networks from malicious software by implementing preventive, detective, and responsive security controls. These controls include deploying anti-malware solutions where appropriate, keeping them up to date, monitoring their effectiveness, and implementing mechanisms to protect personnel from phishing attacks. :contentReference[oaicite:0]{index=0}

---

# Purpose of Requirement 5

The objective of Requirement 5 is to reduce the likelihood that malware can compromise systems within the Cardholder Data Environment (CDE).

Requirement 5 helps organizations:

- Prevent malware infections.
- Detect malicious software quickly.
- Contain malware before it spreads.
- Protect payment card information.
- Reduce business disruption.
- Improve overall cybersecurity resilience.

Modern malware evolves rapidly, making continuous protection essential.

---

# What Is Malware?

Malware is software intentionally designed to disrupt, damage, or gain unauthorized access to computer systems.

Examples include:

- Viruses
- Worms
- Trojan horses
- Ransomware
- Spyware
- Adware
- Rootkits
- Keyloggers
- Botnets
- Fileless malware
- Malicious scripts

Each type uses different techniques to compromise systems and steal sensitive information.

---

# Common Malware Types

## Virus

A virus attaches itself to legitimate files or programs and spreads when infected files are executed.

Typical impact:

- File corruption
- System instability
- Data loss

---

## Worm

A worm spreads automatically across networks without requiring user interaction.

Typical impact:

- Rapid network infection
- Service disruption
- Bandwidth exhaustion

---

## Trojan Horse

A Trojan disguises itself as legitimate software.

Typical impact:

- Remote access
- Credential theft
- Installation of additional malware

---

## Ransomware

Ransomware encrypts files or systems and demands payment for decryption.

Typical impact:

- Business interruption
- Financial loss
- Data unavailability

Many ransomware attacks also steal sensitive data before encryption.

---

## Spyware

Spyware secretly collects information about users and systems.

Examples include:

- Browser monitoring
- Credential collection
- Screen capture
- Activity monitoring

---

## Keylogger

A keylogger records keyboard input.

Attackers use keyloggers to steal:

- Usernames
- Passwords
- Payment card information
- Multi-factor authentication codes

---

## Fileless Malware

Unlike traditional malware, fileless malware operates primarily in memory using legitimate operating system tools.

Characteristics include:

- Difficult to detect
- Minimal filesystem artifacts
- Often abuses PowerShell or Windows Management Instrumentation (WMI)
- Frequently used in advanced attacks

Behavior-based detection is often more effective than signature-based detection against fileless malware.

---

# How Malware Enters an Organization

Malware commonly enters organizations through:

- Phishing emails
- Malicious websites
- Software vulnerabilities
- Unpatched operating systems
- Infected USB devices
- Remote Desktop attacks
- Supply chain compromises
- Malicious downloads
- Compromised third-party software
- Cloud application abuse

Many successful attacks begin with a single compromised endpoint.

---

# Malware in the Cardholder Data Environment (CDE)

Within the Cardholder Data Environment, malware can target:

- Point-of-Sale (POS) terminals
- Payment applications
- Web servers
- Database servers
- Employee workstations
- Administrator laptops
- Payment APIs
- Virtual machines
- Cloud workloads

Once installed, malware may attempt to capture cardholder data before encryption or transmit stolen information to external attackers.

---

# PCI DSS Malware Protection Requirements

Requirement 5 requires organizations to implement controls that:

- Deploy anti-malware solutions on systems commonly affected by malware, unless a documented periodic evaluation concludes a system is not at risk.
- Ensure anti-malware solutions detect, block, remove, or contain known malware.
- Keep anti-malware mechanisms current through automatic updates.
- Perform real-time protection, scheduled scanning, or continuous behavioral analysis.
- Implement anti-phishing mechanisms to protect personnel from phishing attacks. :contentReference[oaicite:1]{index=1}

---

📊 **Diagram Placeholder**

**Title:** Common Malware Infection Path

**Diagram Description:**

```text
Phishing Email

↓

Employee Clicks Link

↓

Malware Downloaded

↓

Endpoint Compromised

↓

Credential Theft

↓

Lateral Movement

↓

Payment System Access

↓

Cardholder Data Theft
```

Show warning icons at each attack stage and security controls such as anti-malware and endpoint detection interrupting the attack chain.

**Caption:**

*"PCI DSS Requirement 5 helps prevent malware from compromising systems within the Cardholder Data Environment by implementing layered anti-malware and anti-phishing controls."*

---

# Best Practices

Organizations should:

- Deploy anti-malware solutions on all applicable systems and networks that are susceptible to malware.
- Keep anti-malware software, engines, and signatures automatically updated.
- Combine signature-based detection with behavioral analysis and Endpoint Detection and Response (EDR) capabilities.
- Protect users through anti-phishing technologies, secure email gateways, and regular security awareness training.
- Regularly evaluate systems that are excluded from anti-malware deployment and document the rationale for those decisions.
- Continuously monitor endpoints for malware infections, suspicious behavior, and unauthorized software installations.
- Integrate malware protection with vulnerability management, patch management, and incident response processes.
- Regularly review malware detection logs and investigate alerts to reduce the risk of compromise. :contentReference[oaicite:2]{index=2}

---

# Practical Example

A multinational retailer operates thousands of Point-of-Sale terminals, corporate workstations, payment servers, and cloud-hosted applications. To comply with PCI DSS Requirement 5, the organization deploys centrally managed Endpoint Detection and Response (EDR) software across all Windows endpoints and payment systems. Real-time malware protection, behavioral analysis, automatic signature updates, and scheduled scans are enabled by default. Linux servers that are determined through documented risk evaluations to have a low malware risk are periodically reassessed to confirm the evaluation remains valid, while web-facing Linux systems are additionally monitored for suspicious activity.

The organization also implements advanced email security with phishing detection, attachment sandboxing, and URL filtering to reduce malware delivered through email. Security alerts from the EDR platform are integrated into the Security Information and Event Management (SIEM) solution, allowing the Security Operations Center (SOC) to rapidly investigate and isolate infected devices. By combining preventive controls, continuous monitoring, user awareness, and incident response, the organization significantly reduces the risk of malware compromising its Cardholder Data Environment.

