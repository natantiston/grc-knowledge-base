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

# Risk Prioritization, Asset Criticality, and Continuous Improvement (ID.IM)

Identifying cybersecurity risks is only valuable if organizations can determine **which risks require immediate attention and which can be managed over time**. Since resources such as budget, personnel, and technology are always limited, organizations must prioritize cybersecurity activities according to business impact and organizational risk appetite.

The **Improvement (ID.IM)** category within the Identify Function encourages organizations to continually refine asset identification, risk assessments, and cybersecurity decision-making based on changing business conditions, emerging threats, operational experience, and lessons learned.

Rather than treating identification as a one-time project, organizations should view it as an ongoing process that evolves alongside the business.

---

# Why Risk Prioritization Matters

Most organizations identify hundreds or even thousands of cybersecurity risks.

Examples include:

- Unpatched servers.
- Cloud misconfigurations.
- Weak passwords.
- Legacy systems.
- Third-party supplier risks.
- AI governance concerns.
- Insider threats.
- Vulnerability findings.

Attempting to resolve every issue simultaneously is unrealistic.

Risk prioritization enables leadership to focus resources where they will produce the greatest reduction in organizational risk.

---

# Factors Used in Risk Prioritization

Organizations typically evaluate multiple factors when determining priorities.

### Business Impact

Questions include:

- Would operations stop?
- Would customers be affected?
- Would revenue be lost?
- Would safety be impacted?
- Would legal obligations be violated?

Higher business impact generally results in higher priority.

---

### Asset Criticality

Critical assets require greater protection.

Examples:

| Asset | Criticality |
|---------|-------------|
| Customer Payment System | Critical |
| ERP System | High |
| Human Resources Portal | Medium |
| Internal Wiki | Low |

Asset criticality should be defined using consistent organizational criteria.

---

### Threat Exposure

Organizations should consider:

- Current threat intelligence.
- Industry attack trends.
- Known exploitation.
- Active ransomware campaigns.
- Nation-state activity.

Frequently targeted assets may require accelerated remediation.

---

### Vulnerability Severity

Organizations often use vulnerability scoring systems such as:

- Critical
- High
- Medium
- Low

Severity should be evaluated together with business context rather than as an isolated technical measure.

---

### Regulatory Requirements

Certain assets may require immediate protection because of legal obligations.

Examples include:

- Personal data.
- Payment card information.
- Healthcare records.
- Critical infrastructure systems.

Compliance considerations frequently influence prioritization.

---

# Asset Classification

Asset classification supports consistent decision-making.

Organizations commonly classify assets according to:

### Confidentiality

How sensitive is the information?

Examples:

- Public
- Internal
- Confidential
- Restricted

---

### Integrity

How important is data accuracy?

Financial records and healthcare information generally require high integrity.

---

### Availability

How important is continuous operation?

Examples:

- Emergency communication systems.
- Manufacturing production lines.
- Hospital systems.

Availability requirements influence protection priorities.

---

# The CIA Triad

Many organizations classify assets using the CIA model.

```
Confidentiality

↓

Integrity

↓

Availability

↓

Overall Asset Criticality
```

Assets with high confidentiality, integrity, and availability requirements receive the highest cybersecurity priority.

---

# Business Impact Analysis (BIA)

Business Impact Analysis helps identify:

- Critical business services.
- Recovery priorities.
- Operational dependencies.
- Maximum acceptable downtime.
- Financial consequences.
- Customer impacts.

BIA results should be incorporated into cybersecurity risk prioritization.

For example, if a payment platform has a Recovery Time Objective (RTO) of one hour, it will typically receive a higher cybersecurity priority than an internal collaboration tool with an RTO of twenty-four hours.

---

# Continuous Asset Identification

Technology environments change constantly.

Examples include:

- New cloud services.
- New applications.
- AI deployments.
- Remote employees.
- New suppliers.
- Mergers and acquisitions.
- Infrastructure upgrades.

Organizations should continuously update:

- Asset inventories.
- Ownership records.
- Classifications.
- Business dependencies.

Continuous visibility reduces the likelihood of unmanaged assets.

---

# Continuous Improvement (ID.IM)

The Improvement category emphasizes learning and adaptation.

Organizations should continuously improve:

- Asset inventories.
- Risk assessment methodologies.
- Governance processes.
- Identification procedures.
- Threat intelligence integration.
- Risk reporting.
- Decision-making processes.

Improvement ensures cybersecurity remains aligned with changing business and threat environments.

---

# Sources of Improvement

Organizations can improve identification processes using information from:

- Internal audits.
- External audits.
- Security incidents.
- Penetration tests.
- Vulnerability assessments.
- Threat intelligence.
- Red team exercises.
- Management reviews.
- Regulatory findings.
- Lessons learned.

Each activity provides valuable insights that strengthen cybersecurity governance.

---

# Cybersecurity Metrics

Organizations should measure identification effectiveness.

Examples include:

| KPI | Purpose |
|------|----------|
| Asset inventory accuracy | Measures inventory completeness |
| Asset ownership coverage | Measures accountability |
| Risk assessment completion | Measures assessment maturity |
| Critical asset classification rate | Measures governance effectiveness |
| Risk register review frequency | Measures continuous monitoring |

Metrics enable leadership to evaluate progress objectively.

---

# Integration with Other CSF Functions

The Identify Function supports every subsequent CSF Function.

```
Identify Assets

↓

Understand Risks

↓

Protect Critical Assets

↓

Detect Security Events

↓

Respond to Incidents

↓

Recover Business Operations

↓

Improve Governance
```

If the Identify Function is incomplete or inaccurate, every downstream cybersecurity activity becomes less effective.

---

# The Continuous Improvement Cycle

```
Asset Identification

↓

Risk Assessment

↓

Risk Prioritization

↓

Implementation

↓

Monitoring

↓

Lessons Learned

↓

Asset Inventory Updates

↓

Improved Risk Assessment

↓

Continual Improvement
```

This cycle enables organizations to adapt to changing technologies, threats, and business objectives.

---

📊 **Diagram Placeholder**

**Title:** Continuous Improvement within the Identify Function

**Diagram Description:**

Create a circular lifecycle.

Asset Inventory

↓

Asset Classification

↓

Risk Assessment

↓

Risk Prioritization

↓

Implementation

↓

Monitoring

↓

Audits & Lessons Learned

↓

Inventory Updates

↓

Return to Asset Inventory

Surround the lifecycle with:

- Business Objectives
- Threat Intelligence
- Regulatory Changes
- Technology Changes
- Governance

Caption:

*"The Identify Function is a continuous process that improves organizational visibility, prioritizes cybersecurity risks, and supports informed governance decisions throughout the cybersecurity lifecycle."*

---

# Best Practices

Organizations should:

- Prioritize cybersecurity risks according to business impact, asset criticality, threat exposure, regulatory obligations, and organizational risk appetite rather than technical severity alone.
- Establish consistent asset classification criteria based on confidentiality, integrity, availability, business value, and operational importance to support effective risk management.
- Integrate Business Impact Analysis (BIA) results into cybersecurity planning to ensure that the most critical business services receive appropriate protection and recovery capabilities.
- Continuously update asset inventories, ownership records, and dependency mappings to reflect changes in technology, cloud adoption, artificial intelligence, mergers, acquisitions, and supplier relationships.
- Measure the effectiveness of identification activities using meaningful KPIs such as asset inventory accuracy, ownership coverage, and risk assessment completion rates.
- Incorporate lessons learned from incidents, audits, vulnerability assessments, penetration tests, and threat intelligence into ongoing improvements of asset management and risk assessment processes.
- Encourage collaboration between business units, cybersecurity teams, IT operations, compliance, and executive leadership to maintain a complete understanding of organizational assets and risks.
- Treat the Identify Function as a continuous governance capability that evolves alongside business strategy, emerging technologies, and the changing cyber threat landscape.

These practices help organizations maintain accurate visibility of their operational environment, improve cybersecurity decision-making, and establish a strong foundation for protecting critical business services.

---

# Practical Example

A multinational pharmaceutical company manages research laboratories, manufacturing facilities, cloud collaboration platforms, AI-assisted drug discovery systems, and global distribution networks. Following a comprehensive asset inventory and cybersecurity risk assessment, the organization classifies its assets according to confidentiality, integrity, availability, and business criticality. Intellectual property repositories, manufacturing control systems, and clinical trial databases are identified as the highest-priority assets because their compromise could significantly affect patient safety, regulatory compliance, product availability, and competitive advantage. Lower-risk administrative systems are scheduled for remediation according to available resources and business priorities.

To maintain an accurate understanding of its cybersecurity environment, the organization continuously updates its asset inventory whenever new cloud services, laboratory equipment, AI models, or third-party suppliers are introduced. Quarterly governance reviews evaluate KPIs related to asset inventory accuracy, risk assessment completion, and asset ownership coverage, while lessons learned from penetration tests and security incidents are incorporated into updated risk assessment methodologies. By treating identification as a continuous improvement process, the organization strengthens cybersecurity governance, improves operational resilience, and ensures that cybersecurity investments remain aligned with evolving business objectives and enterprise risk.

# Applying the Identify Function in Real Organizations

Understanding the concepts behind the **Identify (ID)** Function is essential, but organizations achieve real value only when these concepts are applied consistently across business operations. The Identify Function is not simply about maintaining an asset inventory—it establishes the foundation for every cybersecurity decision by providing visibility into business processes, information assets, technology, dependencies, and organizational risk.

Organizations that successfully implement the Identify Function are better equipped to allocate cybersecurity resources, support executive decision-making, comply with regulatory requirements, and improve resilience against evolving cyber threats.

---

# The Identify Function Lifecycle

A practical implementation of the Identify Function typically follows a structured lifecycle.

```
Understand Business Objectives

↓

Identify Business Services

↓

Identify Assets

↓

Classify Assets

↓

Assign Asset Owners

↓

Identify Dependencies

↓

Perform Risk Assessment

↓

Prioritize Risks

↓

Maintain Asset Inventory

↓

Continual Improvement
```

Each step builds upon the previous one, creating an accurate and continuously updated understanding of the organization's cybersecurity environment.

---

# Step 1 – Understand Business Objectives

Cybersecurity should support organizational goals rather than operate independently.

Leadership should understand:

- Business strategy.
- Mission objectives.
- Revenue-generating services.
- Customer expectations.
- Regulatory obligations.
- Operational priorities.
- Digital transformation initiatives.

This understanding helps ensure that cybersecurity efforts protect what matters most to the organization.

---

# Step 2 – Identify Business Services

Organizations should determine which services are essential for business operations.

Examples include:

- Online banking.
- Payment processing.
- Healthcare delivery.
- Manufacturing operations.
- Telecommunications services.
- Cloud hosting.
- Customer support.
- AI-powered business applications.

Critical services should receive the highest cybersecurity attention.

---

# Step 3 – Identify Organizational Assets

Asset inventories should include all resources that support business services.

Examples include:

### Technology Assets

- Servers.
- Workstations.
- Firewalls.
- Cloud infrastructure.
- Virtual machines.
- Containers.
- Mobile devices.

### Information Assets

- Customer data.
- Financial records.
- Intellectual property.
- Source code.
- Healthcare records.
- Contracts.
- AI training datasets.

### Operational Assets

- Manufacturing equipment.
- Industrial Control Systems (ICS).
- Internet of Things (IoT) devices.
- Telecommunications infrastructure.

A complete inventory improves organizational visibility and supports effective cybersecurity management.

---

# Step 4 – Classify Assets

Organizations should classify assets according to:

- Business value.
- Confidentiality.
- Integrity.
- Availability.
- Regulatory requirements.
- Recovery priorities.

Example classification:

| Asset | Business Criticality | Classification |
|---------|----------------------|---------------|
| Customer Database | Critical | Restricted |
| ERP System | High | Confidential |
| HR Portal | Medium | Internal |
| Public Website | Medium | Public |

Classification ensures that security controls are proportional to business risk.

---

# Step 5 – Assign Ownership

Every critical asset should have a clearly defined owner.

Typical responsibilities include:

- Maintaining asset information.
- Supporting risk assessments.
- Approving changes.
- Reviewing access permissions.
- Coordinating vulnerability remediation.
- Supporting compliance activities.

Ownership establishes accountability across the organization.

---

# Step 6 – Identify Dependencies

Organizations should document dependencies such as:

Internal:

- Networks.
- Applications.
- Identity services.
- Databases.
- Data centers.

External:

- Cloud providers.
- Software vendors.
- Managed service providers.
- Internet connectivity.
- Payment processors.
- AI platform providers.

Understanding dependencies improves both cybersecurity and business continuity planning.

---

# Step 7 – Perform Risk Assessment

Using asset information, organizations evaluate:

- Threats.
- Vulnerabilities.
- Existing controls.
- Likelihood.
- Business impact.
- Overall risk.

Assessment results are documented within the organization's risk register and reviewed by leadership.

---

# Step 8 – Prioritize Risks

Leadership determines which risks require:

- Immediate remediation.
- Additional monitoring.
- Acceptance.
- Transfer.
- Long-term improvement.

Prioritization ensures that cybersecurity resources are allocated efficiently.

---

# Step 9 – Maintain Visibility

Technology environments evolve continuously.

Organizations should update inventories whenever:

- New systems are deployed.
- Applications are retired.
- Cloud services are added.
- Suppliers change.
- AI systems are introduced.
- Business acquisitions occur.

Maintaining visibility prevents unmanaged assets from introducing unnecessary cybersecurity risk.

---

# Integrating the Identify Function with Other Business Processes

The Identify Function should not operate in isolation.

It should integrate with:

- Enterprise Risk Management (ERM).
- Business Continuity Management (ISO 22301).
- Information Security Management (ISO/IEC 27001).
- AI Governance (ISO/IEC 42001).
- Privacy Management.
- Change Management.
- Configuration Management.
- Procurement and Supplier Management.

Integration reduces duplication and improves governance across the organization.

---

# Common Implementation Challenges

Organizations often encounter challenges such as:

- Incomplete asset inventories.
- Shadow IT.
- Rapid cloud adoption.
- Legacy technologies.
- Poor ownership assignments.
- Limited executive visibility.
- Inconsistent classification methods.
- Third-party complexity.

Addressing these challenges requires collaboration between business leaders, IT, cybersecurity teams, and executive management.

---

# Indicators of a Mature Identify Function

Organizations with mature identification capabilities typically demonstrate:

- Accurate enterprise asset inventories.
- Clearly assigned ownership.
- Standardized asset classification.
- Continuous asset discovery.
- Integrated risk assessments.
- Business-aligned prioritization.
- Executive reporting.
- Regular inventory reviews.
- Continuous improvement.

These characteristics improve organizational resilience and support informed governance.

---

# Relationship with the Remaining CSF Functions

The Identify Function provides the information required for all other CSF Functions.

```
Govern

↓

Identify

↓

Protect

↓

Detect

↓

Respond

↓

Recover

↓

Continual Improvement
```

Accurate identification ensures that protection, detection, response, and recovery efforts focus on the organization's most critical assets and services.

---

📊 **Diagram Placeholder**

**Title:** Practical Implementation of the Identify Function

**Diagram Description:**

Create a flowchart.

Business Objectives

↓

Business Services

↓

Asset Inventory

↓

Asset Classification

↓

Asset Ownership

↓

Dependencies

↓

Risk Assessment

↓

Risk Prioritization

↓

Asset Monitoring

↓

Continual Improvement

On the side, connect the process to:

- ISO/IEC 27001
- ISO 22301
- ISO/IEC 42001
- Enterprise Risk Management
- Change Management
- Supplier Management

Caption:

*"The Identify Function creates a continuously updated understanding of organizational assets, business priorities, and cybersecurity risks, enabling effective governance and supporting every subsequent cybersecurity activity."*

---

# Best Practices

Organizations should:

- Establish asset identification as a continuous organizational process rather than a one-time inventory exercise.
- Ensure that asset inventories include on-premises infrastructure, cloud services, operational technology, AI systems, software, data, and third-party dependencies.
- Assign accountable owners for all critical assets and clearly define responsibilities for maintaining asset information, supporting risk assessments, and approving changes.
- Use standardized asset classification criteria based on business value, confidentiality, integrity, availability, and regulatory obligations to ensure consistent protection priorities.
- Integrate the Identify Function with enterprise risk management, business continuity, information security, AI governance, procurement, and change management processes.
- Regularly review asset inventories and dependency mappings to identify shadow IT, obsolete technologies, new cloud services, mergers, acquisitions, and emerging business risks.
- Measure the effectiveness of identification activities through governance metrics such as inventory completeness, ownership coverage, asset classification accuracy, and assessment frequency.
- Promote collaboration among executive leadership, business units, IT operations, cybersecurity teams, and compliance functions to maintain accurate visibility across the organization.

These practices enable organizations to build a mature Identify Function that supports informed decision-making, effective risk management, regulatory compliance, and resilient cybersecurity operations.

---

# Practical Example

A multinational airline operates reservation platforms, airport operational systems, baggage handling systems, aircraft maintenance applications, customer mobile applications, cloud infrastructure, and AI-powered scheduling tools. To implement the Identify Function of the NIST Cybersecurity Framework 2.0, the organization establishes a centralized enterprise asset management program that inventories technology assets, operational technology, cloud services, business data, and critical third-party providers. Every critical asset is classified according to business importance, regulatory obligations, confidentiality, integrity, availability, and recovery requirements, with ownership assigned to accountable business and technical leaders.

The asset inventory is integrated with vulnerability management, change management, business continuity planning, supplier governance, and enterprise risk management. Automated discovery tools continuously identify new cloud resources, connected devices, and software deployments, while quarterly governance reviews evaluate asset inventory accuracy, ownership coverage, and cybersecurity risk trends. By maintaining a comprehensive and continuously updated understanding of its operational environment, the airline ensures that cybersecurity investments are directed toward protecting the systems and services that are most essential to safe, reliable, and resilient air transportation.
