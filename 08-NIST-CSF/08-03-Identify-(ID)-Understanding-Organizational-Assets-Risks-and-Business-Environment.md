# Lesson 8.3 – Identify (ID): Understanding Organizational Assets, Risks, and Business Environment

> **Chapter:** 08 – NIST Cybersecurity Framework (CSF) 2.0
> **Lesson:** 8.3
> **Part:** 1 of 4
> **Difficulty:** Intermediate
> **Estimated Reading Time:** 10–15 minutes
> **Prerequisites:** Lesson 8.2 – Govern (GV)

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of the **Identify (ID)** Function in the NIST Cybersecurity Framework (CSF) 2.0.
- Explain why asset identification is fundamental to cybersecurity.
- Understand how organizations identify business environments, assets, dependencies, and cybersecurity risks.
- Learn the categories within the Identify Function.
- Recognize how the Identify Function supports effective risk management and the remaining CSF Functions.

---

# Introduction

Before an organization can protect its systems, detect attacks, respond to incidents, or recover from disruptions, it must first understand **what it is trying to protect**.

The **Identify (ID)** Function provides this understanding.

It enables organizations to develop a comprehensive view of their business environment, critical assets, information, technologies, dependencies, and cybersecurity risks. Without accurate identification, organizations may invest in protecting the wrong assets, overlook critical systems, or fail to recognize significant risks.

The Identify Function answers fundamental questions such as:

- What assets do we own?
- Which business services are most critical?
- What data do we process?
- Which systems support our operations?
- What are our cybersecurity risks?
- Who depends on these services?
- Which external parties influence our cybersecurity posture?

---

# Purpose of the Identify Function

The Identify Function helps organizations:

- Understand business priorities.
- Inventory assets.
- Identify critical services.
- Understand dependencies.
- Assess cybersecurity risks.
- Support governance decisions.
- Prioritize cybersecurity investments.
- Enable risk-based decision-making.

Everything that follows in the Cybersecurity Framework depends upon accurate identification.

---

# Why Identification Matters

Organizations frequently face challenges such as:

- Unknown devices connected to networks.
- Shadow IT.
- Unmanaged cloud services.
- Forgotten applications.
- Legacy systems.
- Third-party dependencies.
- Artificial Intelligence platforms.
- Operational Technology (OT).

Assets that are not identified cannot be effectively protected or monitored.

One of the most common causes of cybersecurity incidents is the existence of unmanaged or poorly understood assets.

---

# Categories within the Identify Function

The Identify Function is divided into several categories.

| Category | Purpose |
|----------|---------|
| ID.AM | Asset Management |
| ID.RA | Risk Assessment |
| ID.IM | Improvement |
| *(Additional guidance within CSF 2.0 also links Identify activities with organizational understanding established in the Govern Function.)* |

These categories help organizations understand their cybersecurity environment before implementing protective measures.

---

# Asset Management (ID.AM)

Asset Management focuses on identifying and maintaining inventories of organizational assets.

Examples include:

### Hardware Assets

- Servers
- Workstations
- Laptops
- Mobile devices
- Firewalls
- Network switches
- Routers
- IoT devices
- Industrial Control Systems (ICS)

---

### Software Assets

Examples:

- Operating systems
- Enterprise applications
- SaaS platforms
- Databases
- Security tools
- AI applications
- Cloud services
- Development tools

---

### Information Assets

Organizations should identify:

- Customer information
- Financial records
- Employee data
- Intellectual property
- Source code
- Contracts
- Healthcare records
- AI training datasets

Information often represents the organization's most valuable asset.

---

### Services

Critical business services include:

- Online banking
- E-commerce
- Telecommunications
- Manufacturing operations
- Healthcare delivery
- Customer support
- Cloud hosting

Service inventories help organizations prioritize protection efforts.

---

# Asset Inventory

Organizations should maintain accurate inventories.

Example:

| Asset ID | Asset | Owner | Criticality | Location |
|-----------|-------|--------|-------------|----------|
| SVR-001 | Database Server | IT | Critical | Data Center |
| APP-014 | CRM System | Sales | High | Cloud |
| AI-003 | Fraud Detection Model | Data Science | High | Azure |

Asset inventories should be continuously updated as technology environments evolve.

---

# Asset Ownership

Every critical asset should have an assigned owner.

Owners are responsible for:

- Asset classification.
- Security requirements.
- Risk acceptance.
- Maintenance.
- Compliance.
- Lifecycle management.

Ownership establishes accountability.

---

# Business Environment

Organizations should understand:

- Business objectives.
- Critical operations.
- Products.
- Services.
- Customers.
- Revenue streams.
- Strategic priorities.

Cybersecurity investments should focus on protecting what is most important to business success.

---

# Critical Business Services

Organizations should identify services whose disruption would significantly impact operations.

Examples:

- Online payment systems.
- Emergency communications.
- Hospital patient care.
- Telecommunications networks.
- Manufacturing production lines.
- Utility services.

These services typically receive the highest cybersecurity priority.

---

# Business Dependencies

Organizations depend upon many internal and external resources.

Examples:

Internal:

- Employees
- Data centers
- Applications
- Networks

External:

- Cloud providers
- Internet providers
- Suppliers
- Payment processors
- AI service providers

Understanding dependencies improves resilience planning.

---

# The Foundation for Risk Management

Identification supports cybersecurity risk management by helping organizations understand:

- What exists.
- What is valuable.
- What requires protection.
- What could fail.
- What would happen if disruption occurs.

Without this understanding, effective cybersecurity planning is impossible.

---

📊 **Diagram Placeholder**

**Title:** The Identify Function in NIST CSF 2.0

**Diagram Description:**

Create a central box labeled **Identify (ID)**.

Branch into:

- Asset Management
- Business Environment
- Business Services
- Dependencies
- Information Assets
- Technology Assets
- Risk Assessment

Below these, connect to:

Risk Prioritization

↓

Protect

↓

Detect

↓

Respond

↓

Recover

Caption:

*"The Identify Function establishes a comprehensive understanding of organizational assets, business priorities, and cybersecurity risks that forms the foundation for effective cyber resilience."*

---

# Best Practices

Organizations should:

- Maintain accurate and continuously updated inventories of hardware, software, cloud services, data, AI systems, and other critical assets.
- Assign clear ownership for all critical assets to ensure accountability for classification, protection, maintenance, and lifecycle management.
- Identify business-critical services and prioritize cybersecurity activities according to their operational importance and business impact.
- Understand internal and external dependencies, including suppliers, cloud providers, AI services, and operational technology environments.
- Integrate asset inventories with configuration management, vulnerability management, and risk assessment processes to improve visibility and decision-making.
- Regularly review inventories to detect unauthorized devices, shadow IT, obsolete systems, and changes introduced through digital transformation initiatives.
- Align asset management with enterprise governance, business continuity, and regulatory compliance programs to support consistent cybersecurity management.
- Treat asset identification as a continuous governance activity rather than a one-time inventory exercise.

These practices provide organizations with the visibility required to make informed cybersecurity decisions, allocate resources effectively, and build a resilient security program.

---

# Practical Example

A multinational energy company operates power generation facilities, transmission networks, cloud-based operational systems, industrial control systems (ICS), and customer billing platforms. To strengthen cybersecurity governance, the organization begins implementing the Identify Function of the NIST Cybersecurity Framework 2.0 by creating a comprehensive inventory of hardware, software, cloud services, operational technology assets, AI-based predictive maintenance systems, and critical business data. Each asset is assigned an owner, classified according to business criticality, and linked to the business processes it supports. The assessment also identifies key dependencies on cloud providers, telecommunications networks, and third-party maintenance contractors.

Using this information, leadership develops a prioritized view of the organization's cybersecurity landscape. Critical assets supporting electricity generation and distribution receive enhanced protection, while previously undocumented legacy systems and unmanaged cloud resources are incorporated into governance processes. The resulting asset inventory becomes the foundation for vulnerability management, cybersecurity risk assessments, incident response planning, and business continuity activities. By establishing a complete understanding of its operational environment, the organization significantly improves its ability to manage cybersecurity risk and protect essential services.

# Risk Assessment (ID.RA): Identifying and Evaluating Cybersecurity Risks

Once an organization understands its assets, business environment, and dependencies, the next step is to determine **what could go wrong**. The **Risk Assessment (ID.RA)** category within the Identify Function enables organizations to recognize cybersecurity threats, evaluate vulnerabilities, estimate potential business impacts, and prioritize risks for treatment.

Risk assessment transforms asset information into actionable intelligence for leadership. Instead of treating every asset or threat equally, organizations evaluate which risks could have the greatest impact on business objectives and allocate resources accordingly.

---

# What is Cybersecurity Risk?

Cybersecurity risk is the possibility that a threat will exploit a vulnerability, resulting in harm to the organization.

Risk is commonly represented as:

```
Threat

+

Vulnerability

+

Asset

↓

Potential Business Impact

=

Cybersecurity Risk
```

The objective of risk assessment is not to eliminate every risk but to understand and manage risk to an acceptable level.

---

# Purpose of Risk Assessment

Risk assessments help organizations:

- Identify cybersecurity threats.
- Discover vulnerabilities.
- Evaluate potential business impacts.
- Prioritize cybersecurity investments.
- Support executive decision-making.
- Meet regulatory and contractual requirements.
- Improve operational resilience.

Risk assessment is one of the most important activities within an effective cybersecurity governance program.

---

# Components of Risk Assessment

A comprehensive assessment considers several key elements.

### Assets

Determine what requires protection.

Examples:

- Customer databases.
- Cloud infrastructure.
- AI systems.
- Industrial Control Systems (ICS).
- Financial applications.
- Business-critical services.

---

### Threats

Threats are events or actors capable of causing harm.

Examples include:

- Ransomware.
- Phishing attacks.
- Insider threats.
- Nation-state attacks.
- Supply chain compromises.
- Distributed Denial-of-Service (DDoS).
- Credential theft.
- AI-enabled attacks.

Threat intelligence should be reviewed regularly to understand the evolving cyber landscape.

---

### Vulnerabilities

Vulnerabilities are weaknesses that may be exploited.

Examples include:

- Unpatched software.
- Weak passwords.
- Misconfigured cloud services.
- Unsupported operating systems.
- Inadequate network segmentation.
- Poor identity management.
- Insecure APIs.

Reducing vulnerabilities decreases the likelihood of successful attacks.

---

### Existing Controls

Organizations should evaluate current safeguards such as:

- Multi-factor authentication (MFA).
- Firewalls.
- Endpoint protection.
- Security monitoring.
- Encryption.
- Security awareness training.
- Backup solutions.

Existing controls influence the overall level of risk.

---

### Business Impact

Risk assessment evaluates how cybersecurity incidents could affect:

- Financial performance.
- Business operations.
- Customer trust.
- Regulatory compliance.
- Reputation.
- Health and safety.
- Strategic objectives.

Business impact determines the importance of each identified risk.

---

# Risk Assessment Process

A structured process typically follows these steps:

```
Identify Assets

↓

Identify Threats

↓

Identify Vulnerabilities

↓

Evaluate Existing Controls

↓

Estimate Likelihood

↓

Estimate Business Impact

↓

Determine Risk Level

↓

Prioritize Risks
```

This process provides leadership with a consistent approach to evaluating cyber risk.

---

# Likelihood Assessment

Likelihood estimates how probable a cybersecurity event is.

Typical ratings include:

| Likelihood | Description |
|------------|-------------|
| Very Low | Rare occurrence |
| Low | Unlikely |
| Medium | Possible |
| High | Likely |
| Very High | Expected to occur frequently |

Likelihood may be influenced by threat activity, vulnerability exposure, and control effectiveness.

---

# Impact Assessment

Impact measures the consequences if a risk materializes.

Common impact areas include:

- Financial loss.
- Service disruption.
- Data breach.
- Regulatory penalties.
- Customer dissatisfaction.
- Operational downtime.
- Damage to reputation.

Organizations often use a five-level impact scale similar to likelihood.

---

# Risk Matrix

A risk matrix combines likelihood and impact to determine overall risk.

| Impact ↓ / Likelihood → | Low | Medium | High |
|-------------------------|-----|--------|------|
| High Impact | Medium | High | Critical |
| Medium Impact | Low | Medium | High |
| Low Impact | Low | Low | Medium |

The matrix helps organizations prioritize resources toward the highest risks.

---

# Qualitative vs Quantitative Risk Assessment

Organizations may use different assessment methods.

### Qualitative

Uses descriptive ratings such as:

- Low
- Medium
- High

Advantages:

- Easy to perform.
- Simple to communicate.
- Suitable for most organizations.

---

### Quantitative

Uses numerical values such as:

- Estimated financial loss.
- Annualized Loss Expectancy (ALE).
- Probability calculations.
- Cost-benefit analysis.

Advantages:

- Supports financial decision-making.
- Enables more detailed investment analysis.

Many organizations use a hybrid approach that combines both methods.

---

# Risk Register

Assessment results should be documented in a risk register.

Example:

| Risk ID | Asset | Threat | Likelihood | Impact | Risk Level | Owner |
|----------|-------|---------|------------|--------|------------|-------|
| R-001 | Customer Portal | Credential Theft | High | High | Critical | CISO |
| R-002 | ERP System | Ransomware | Medium | High | High | IT Director |
| R-003 | Cloud Storage | Misconfiguration | Medium | Medium | Medium | Cloud Manager |

The risk register becomes a central governance document for monitoring and managing cybersecurity risks.

---

# Continuous Risk Assessment

Cybersecurity risk changes continuously due to:

- Emerging threats.
- New vulnerabilities.
- Technology upgrades.
- Cloud adoption.
- Artificial Intelligence.
- Regulatory changes.
- Business expansion.
- Supplier changes.

Organizations should update risk assessments regularly rather than treating them as annual exercises.

---

📊 **Diagram Placeholder**

**Title:** Cybersecurity Risk Assessment Process

**Diagram Description:**

Create a sequential flow diagram.

Assets

↓

Threats

↓

Vulnerabilities

↓

Existing Controls

↓

Likelihood Assessment

↓

Impact Assessment

↓

Risk Rating

↓

Risk Register

↓

Risk Prioritization

↓

Risk Treatment

Caption:

*"Cybersecurity risk assessment enables organizations to evaluate threats, vulnerabilities, business impacts, and existing controls in order to prioritize risk management activities and support informed decision-making."*

---

# Best Practices

Organizations should:

- Conduct cybersecurity risk assessments using a documented and repeatable methodology that is aligned with enterprise risk management practices.
- Evaluate risks by considering assets, threats, vulnerabilities, existing controls, likelihood, and potential business impact rather than focusing on technical vulnerabilities alone.
- Use risk registers to document identified risks, assigned owners, treatment decisions, review dates, and ongoing monitoring activities.
- Incorporate threat intelligence, vulnerability assessments, penetration testing results, audit findings, and lessons learned into the risk assessment process.
- Review cybersecurity risks whenever significant business, technology, supplier, regulatory, or threat landscape changes occur, in addition to scheduled periodic assessments.
- Apply consistent likelihood and impact criteria to improve the accuracy, comparability, and transparency of risk evaluations across the organization.
- Prioritize cybersecurity initiatives according to business risk, regulatory obligations, and organizational objectives rather than attempting to address every risk simultaneously.
- Present risk assessment results in a business-focused format that enables executives to understand organizational exposure and make informed risk-based decisions.

These practices ensure that cybersecurity risk assessments provide meaningful information for governance, operational planning, investment prioritization, and continual improvement.

---

# Practical Example

A multinational healthcare organization operates hospitals, cloud-based electronic health record (EHR) systems, medical devices, AI-assisted diagnostic platforms, and patient portals. As part of its implementation of the NIST Cybersecurity Framework 2.0, the cybersecurity team performs a comprehensive risk assessment by identifying critical assets, evaluating ransomware threats targeting healthcare providers, assessing vulnerabilities in legacy medical devices, and reviewing existing security controls such as multi-factor authentication, endpoint protection, and network segmentation. Each identified risk is evaluated using standardized likelihood and impact criteria, with potential effects measured in terms of patient safety, regulatory compliance, operational disruption, financial loss, and reputational damage.

The results are documented in an enterprise risk register and presented to executive leadership. High-priority risks, including unsupported medical equipment and third-party cloud service dependencies, receive immediate attention through remediation projects and enhanced monitoring. Lower-priority risks are scheduled for future treatment based on available resources and organizational risk appetite. By maintaining a structured and continuously updated cybersecurity risk assessment process, the organization strengthens governance, improves resilience, and ensures that cybersecurity investments are focused on the areas of greatest business importance.

