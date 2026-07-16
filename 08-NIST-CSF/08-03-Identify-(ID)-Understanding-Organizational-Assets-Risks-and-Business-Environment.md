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

