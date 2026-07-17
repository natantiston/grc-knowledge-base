# Lesson 9.8 – Requirement 6: Develop and Maintain Secure Systems and Software

> **Chapter:** 09 – Payment Card Industry Data Security Standard (PCI DSS) 4.0
>
> **Lesson:** 9.8
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Explain the purpose of PCI DSS Requirement 6.
- Understand the importance of secure software development and system maintenance.
- Describe the Secure Software Development Life Cycle (SSDLC).
- Understand vulnerability management and security patch management.
- Recognize the role of secure coding practices in protecting payment systems.

---

# Introduction

Modern organizations rely heavily on software applications, operating systems, cloud platforms, databases, and third-party components to process payment transactions. Every software vulnerability presents an opportunity for attackers to gain unauthorized access to systems, steal payment card data, deploy malware, or disrupt business operations. Many of the largest payment card breaches have been traced to unpatched vulnerabilities, insecure application development practices, or poorly managed software changes.

PCI DSS Requirement 6 focuses on developing and maintaining secure systems and software throughout their entire lifecycle. Rather than treating security as a final testing activity before deployment, organizations are expected to integrate security into software development, vulnerability management, change management, and ongoing system maintenance. This reduces the likelihood that vulnerabilities will be introduced into production environments and helps protect the Cardholder Data Environment (CDE). :contentReference[oaicite:0]{index=0}

---

# Purpose of Requirement 6

The objective of Requirement 6 is to ensure that systems and software remain secure throughout their lifecycle by identifying vulnerabilities early, applying security patches promptly, following secure development practices, and validating changes before deployment.

Requirement 6 helps organizations:

- Reduce software vulnerabilities.
- Prevent exploitation of known security weaknesses.
- Secure internally developed applications.
- Protect commercial off-the-shelf software.
- Improve software quality and resilience.
- Reduce business and operational risk.
- Support continuous PCI DSS compliance.

Security should be embedded into every stage of the software lifecycle rather than added after development is complete.

---

# Why Secure Software Matters

Every application that processes, stores, or transmits payment card information represents a potential attack surface.

Attackers commonly exploit:

- Unpatched operating systems
- Vulnerable web applications
- Weak authentication mechanisms
- Insecure APIs
- Misconfigured servers
- Third-party software vulnerabilities
- Coding flaws
- Poor change management

Even a single overlooked vulnerability can provide attackers with access to sensitive payment information.

---

# Common Software Vulnerabilities

Organizations should understand the most common vulnerabilities affecting enterprise applications.

Examples include:

- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Broken Authentication
- Security Misconfiguration
- Buffer Overflow
- Command Injection
- Sensitive Data Exposure
- Insecure Direct Object References (IDOR)
- Remote Code Execution (RCE)

Many of these weaknesses can be prevented through secure coding practices and security testing.

---

# Secure Software Development Life Cycle (SSDLC)

PCI DSS encourages organizations to integrate security throughout the Software Development Life Cycle.

A typical Secure SDLC consists of:

```text
Requirements

↓

Secure Design

↓

Secure Development

↓

Security Testing

↓

Code Review

↓

Deployment

↓

Continuous Monitoring

↓

Maintenance
```

Security activities should occur throughout every phase rather than only before deployment.

---

# Vulnerability Management

Vulnerability management is a continuous process that identifies, evaluates, prioritizes, and remediates security weaknesses.

A mature vulnerability management program includes:

- Vulnerability identification
- Risk assessment
- Risk prioritization
- Patch management
- Security verification
- Continuous monitoring

Organizations should obtain vulnerability information from reputable sources and assign risk rankings to newly identified vulnerabilities to support timely remediation. :contentReference[oaicite:1]{index=1}

---

# Security Patch Management

Software vendors regularly release security patches to correct newly discovered vulnerabilities.

An effective patch management process includes:

- Monitoring vendor security advisories
- Evaluating patch relevance
- Risk assessment
- Testing patches before deployment
- Production deployment
- Verification of successful installation
- Documentation

Critical security patches should be prioritized according to organizational risk management processes and PCI DSS requirements. :contentReference[oaicite:2]{index=2}

---

# Secure Coding Principles

Secure coding reduces the likelihood that vulnerabilities are introduced during software development.

Examples include:

- Validate all user input.
- Encode output correctly.
- Use parameterized queries.
- Implement strong authentication.
- Apply least privilege.
- Protect sensitive data.
- Handle errors securely.
- Avoid hardcoded credentials.
- Perform secure session management.
- Validate all API requests.

Following secure coding standards significantly reduces application security risks.

---

# PCI DSS Requirement 6 Overview

Requirement 6 requires organizations to establish processes that support secure systems and software throughout their lifecycle.

Key areas include:

- Secure software development practices
- Vulnerability identification
- Timely security patch management
- Protection of public-facing web applications
- Secure change management
- Security testing before production deployment

These requirements help ensure that software remains secure as technology and threats evolve. :contentReference[oaicite:3]{index=3}

---

📊 **Diagram Placeholder**

**Title:** Secure Software Development Lifecycle (SSDLC)

**Diagram Description:**

```text
Requirements

↓

Secure Design

↓

Development

↓

Security Testing

↓

Deployment

↓

Monitoring

↓

Maintenance

↓

Continuous Improvement
```

Show security activities integrated into every phase of the software development lifecycle.

**Caption:**

*"PCI DSS Requirement 6 promotes integrating security throughout the entire software lifecycle, from design and development to deployment, maintenance, and continuous improvement."*

---

# Best Practices

Organizations should:

- Integrate security into every phase of the Software Development Life Cycle (SDLC).
- Establish a formal vulnerability management program with risk-based prioritization.
- Monitor trusted sources for newly disclosed vulnerabilities affecting systems and software.
- Apply security patches after appropriate testing and within organizationally defined timeframes based on risk.
- Follow secure coding standards to reduce common software vulnerabilities.
- Perform security testing before software is deployed into production.
- Maintain documented change management procedures for all system and software modifications.
- Continuously monitor systems for newly discovered vulnerabilities and emerging threats. :contentReference[oaicite:4]{index=4}

---

# Practical Example

A multinational payment processor develops several customer-facing payment applications while also maintaining commercial software for payment gateways, databases, and cloud infrastructure. To comply with PCI DSS Requirement 6, the organization implements a Secure Software Development Life Cycle (SSDLC) that incorporates security requirements during design, automated code analysis during development, vulnerability scanning before deployment, and formal security testing prior to releasing software into production. Development teams follow secure coding standards based on industry best practices, while all software changes are reviewed through a structured change management process.

In parallel, the cybersecurity team operates a centralized vulnerability management program that continuously monitors vendor security advisories, evaluates newly disclosed vulnerabilities, and prioritizes remediation based on business risk. Critical security patches are tested in staging environments before deployment to production, while dashboards provide executive visibility into patch compliance and vulnerability remediation. By integrating secure development, vulnerability management, patch management, and continuous monitoring, the organization significantly reduces software-related risks and strengthens the security of its Cardholder Data Environment.

