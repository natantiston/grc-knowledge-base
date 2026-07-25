# Lesson 13.3 – Shared Responsibility Model

> **Chapter:** 13 – Cloud Security
>
> **Lesson:** 13.3
>
> **Topic:** Shared Responsibility Model
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the concept of the Shared Responsibility Model in cloud computing.
- Explain why cloud security is a shared responsibility between providers and customers.
- Identify the different categories of responsibilities within cloud environments.
- Understand how responsibilities change across cloud service models.
- Recognize common misconceptions regarding cloud security responsibilities.
- Appreciate the role of the Shared Responsibility Model in Governance, Risk, and Compliance (GRC).

---

# Introduction

One of the most important concepts in cloud security is the **Shared Responsibility Model (SRM)**. Many organizations mistakenly believe that moving workloads to the cloud transfers all security responsibilities to the cloud provider. In reality, while cloud providers secure the underlying infrastructure, customers remain responsible for protecting their own data, identities, applications, and configurations.

This division of responsibilities is known as the **Shared Responsibility Model**.

Understanding the Shared Responsibility Model is essential because many cloud security incidents result not from failures by cloud providers but from customer errors, such as weak Identity and Access Management (IAM), exposed storage, excessive permissions, or poor configuration management.

For Governance, Risk, and Compliance (GRC) professionals, the Shared Responsibility Model clarifies accountability, supports risk assessments, strengthens governance, and helps organizations meet regulatory obligations.

---

# What is the Shared Responsibility Model?

The Shared Responsibility Model is a security framework that defines how security and compliance responsibilities are divided between the **Cloud Service Provider (CSP)** and the **customer**.

The model ensures that:

- Cloud providers secure the cloud infrastructure.
- Customers secure the workloads, data, and services they deploy within the cloud.
- Both parties work together to maintain a secure cloud environment.

The exact division of responsibilities depends on the cloud service model (IaaS, PaaS, or SaaS), but the concept of shared accountability remains constant.

---

# Why the Shared Responsibility Model Exists

Cloud providers operate large-scale infrastructure that serves thousands of customers. While providers manage and secure the underlying physical environment, they cannot control how each customer configures applications, manages identities, or protects data.

The Shared Responsibility Model exists because:

- Customers own their business data.
- Customers control access to their cloud resources.
- Providers cannot manage customer business processes.
- Regulatory compliance often remains the customer's responsibility.
- Security decisions made by customers directly affect their risk exposure.

This shared approach allows providers to deliver secure infrastructure while enabling customers to retain control over their own environments.

---

# Security of the Cloud vs. Security in the Cloud

The Shared Responsibility Model is often explained using two complementary concepts.

## Security **of** the Cloud

This refers to the responsibilities of the cloud provider.

The provider is responsible for protecting:

- Physical data centers.
- Physical servers.
- Networking infrastructure.
- Storage hardware.
- Virtualization platform.
- Hypervisors.
- Environmental controls.
- Physical security.
- Hardware maintenance.
- Infrastructure availability.

These controls ensure that the cloud platform itself remains secure and reliable.

---

## Security **in** the Cloud

This refers to the responsibilities of the customer.

Customers are responsible for protecting:

- User identities.
- Authentication.
- Access permissions.
- Applications.
- Virtual machines (where applicable).
- Operating systems (IaaS).
- Business data.
- Encryption settings.
- Security monitoring.
- Compliance obligations.

Although the infrastructure is managed by the provider, customers remain accountable for how they use cloud services.

---

# Shared Responsibility Principles

Several key principles underpin the Shared Responsibility Model.

### Accountability

Each party is accountable for the controls under its ownership.

---

### Collaboration

Cloud security requires cooperation between providers and customers.

---

### Risk Ownership

Organizations remain responsible for the risks associated with their business data and applications.

---

### Continuous Security

Security responsibilities continue throughout the lifecycle of cloud resources, from deployment to retirement.

---

### Governance

Organizations must establish governance processes to ensure customer responsibilities are consistently fulfilled.

---

# Responsibilities That Never Transfer

Regardless of the cloud service model, certain responsibilities always remain with the customer.

These typically include:

- Data ownership.
- Data classification.
- User access management.
- Identity governance.
- Regulatory compliance.
- Security awareness training.
- Business continuity planning.
- Risk management.
- Incident reporting.
- Governance oversight.

Using cloud services does not eliminate an organization's legal or regulatory obligations.

---

# Common Misconceptions

Many organizations misunderstand the Shared Responsibility Model.

### Misconception 1

**"The cloud provider secures everything."**

Reality:

The provider secures the infrastructure, but customers secure their own identities, applications, configurations, and data.

---

### Misconception 2

**"Compliance becomes the provider's responsibility."**

Reality:

Although providers support compliance through certifications and security controls, customers remain responsible for complying with applicable laws and regulations.

---

### Misconception 3

**"If data is stored in the cloud, it is automatically protected."**

Reality:

Customers must configure encryption, backups, access controls, monitoring, and data retention policies.

---

### Misconception 4

**"Cloud security eliminates cybersecurity risk."**

Reality:

Cloud computing changes the threat landscape but does not eliminate cyber risk.

---

# Shared Responsibility and GRC

The Shared Responsibility Model is closely linked to Governance, Risk, and Compliance.

Within a GRC program, organizations should:

- Define ownership of cloud security controls.
- Document customer responsibilities.
- Perform cloud risk assessments.
- Establish cloud governance policies.
- Monitor compliance continuously.
- Review third-party assurance reports.
- Conduct cloud security audits.
- Measure control effectiveness.
- Maintain evidence for regulatory compliance.

Clearly assigning responsibilities strengthens governance and reduces organizational risk.

---

# Benefits of Understanding the Shared Responsibility Model

Organizations that understand the Shared Responsibility Model are better equipped to:

- Reduce security gaps.
- Improve accountability.
- Strengthen governance.
- Improve regulatory compliance.
- Clarify operational responsibilities.
- Improve cloud risk management.
- Reduce configuration errors.
- Enhance security awareness.
- Improve audit readiness.
- Build resilient cloud environments.

Understanding responsibilities is the first step toward securing cloud workloads effectively.

---

📊 **Diagram Placeholder**

**Title:** Shared Responsibility Model Overview

**Diagram Description:**

```text
          Cloud Security

                 │

     ┌───────────┴───────────┐

     ▼                       ▼

Cloud Provider          Customer

Security of             Security in
the Cloud               the Cloud

• Physical Security     • Identity
• Hardware              • Data
• Networking            • Applications
• Hypervisor            • Access Control
• Infrastructure        • Configuration
• Availability          • Compliance
```

**Caption:**

*"The Shared Responsibility Model divides cloud security responsibilities between the cloud service provider, which secures the underlying infrastructure, and the customer, who secures data, identities, applications, configurations, and compliance within the cloud environment."*

---

# Practical Example

A software company migrates its customer relationship management (CRM) application to a public cloud provider. The cloud provider secures the physical data centers, networking infrastructure, storage hardware, and virtualization platform. However, the company is responsible for configuring user permissions, enabling Multi-Factor Authentication (MFA), encrypting customer data, securing application programming interfaces (APIs), and monitoring user activity.

During a routine security assessment, auditors discover that an administrator account does not have MFA enabled. Although the cloud provider's infrastructure remains fully secure, the organization identifies this as a customer responsibility under the Shared Responsibility Model. The issue is promptly corrected, reinforcing that cloud security depends on both the provider's infrastructure controls and the customer's governance and security practices.

---

# Key Takeaways

- The Shared Responsibility Model defines how cloud security responsibilities are divided between the cloud provider and the customer.
- Cloud providers are responsible for the **security of the cloud**, while customers are responsible for the **security in the cloud**.
- Customers always retain responsibility for protecting their data, identities, applications, configurations, governance, and regulatory compliance.
- Understanding the Shared Responsibility Model helps organizations reduce security gaps, improve accountability, and strengthen cloud governance.
- Cloud adoption does not transfer legal, regulatory, or risk management responsibilities to the cloud provider.
- A clear understanding of shared responsibilities is fundamental for implementing secure, compliant, and resilient cloud environments.

- # Customer Responsibilities

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the security responsibilities that remain with cloud customers.
- Identify the key areas customers must manage in cloud environments.
- Explain why customer responsibilities vary across cloud service models.
- Recognize how customer responsibilities support Governance, Risk, and Compliance (GRC).
- Apply best practices to fulfill customer security obligations.
- Understand the consequences of failing to meet customer responsibilities.

---

# Introduction

One of the most common misconceptions about cloud computing is that the cloud provider assumes responsibility for all aspects of security. In reality, customers retain significant responsibility regardless of the cloud service model they choose.

Whether an organization uses Infrastructure as a Service (IaaS), Platform as a Service (PaaS), or Software as a Service (SaaS), it remains accountable for protecting its business data, managing user access, complying with regulations, and implementing appropriate governance controls.

Many cloud security incidents—including exposed storage accounts, compromised administrator credentials, ransomware infections, and data breaches—occur because organizations fail to fulfill their own responsibilities rather than because of failures within the cloud provider's infrastructure.

Understanding customer responsibilities is therefore essential for maintaining a secure and compliant cloud environment.

---

# Why Customer Responsibilities Matter

Cloud providers deliver secure platforms, but they cannot make business decisions on behalf of their customers.

Customers determine:

- Who can access cloud resources.
- What data is stored.
- How applications are configured.
- Which security controls are enabled.
- What compliance requirements apply.
- How business risks are managed.

Since organizations retain ownership of their data and business processes, they must also retain ownership of their security and compliance obligations.

---

# Core Customer Responsibilities

Customers are responsible for multiple aspects of cloud security.

## 1. Identity and Access Management (IAM)

Identity security is one of the customer's most critical responsibilities.

Organizations should:

- Create and manage user accounts.
- Enforce Multi-Factor Authentication (MFA).
- Apply Role-Based Access Control (RBAC).
- Follow the Principle of Least Privilege.
- Remove inactive accounts.
- Protect privileged identities.
- Periodically review access permissions.

Compromised identities remain one of the leading causes of cloud security incidents.

---

## 2. Data Protection

Customers own their business data and must ensure it remains protected throughout its lifecycle.

Responsibilities include:

- Data classification.
- Data ownership.
- Encryption configuration.
- Backup management.
- Data retention.
- Secure deletion.
- Privacy protection.
- Data residency compliance.

Protecting data remains the customer's responsibility even when it is stored in a public cloud.

---

## 3. Application Security

Organizations are responsible for securing the applications they deploy.

This includes:

- Secure software development.
- Vulnerability management.
- Patch management.
- API security.
- Secure coding practices.
- Application testing.
- Dependency management.
- Configuration management.

Poorly secured applications can compromise otherwise secure cloud environments.

---

## 4. Operating System Security (IaaS)

In Infrastructure as a Service (IaaS), customers manage the operating systems running on virtual machines.

Responsibilities include:

- Operating system installation.
- Security updates.
- Patch management.
- Malware protection.
- Host firewalls.
- System hardening.
- User account management.
- Log management.

These responsibilities generally shift to the provider in PaaS and SaaS environments.

---

## 5. Network Configuration

Although cloud providers secure the physical network, customers configure their logical cloud networks.

Responsibilities include:

- Virtual network design.
- Firewall configuration.
- Security groups.
- Network segmentation.
- Private connectivity.
- VPN configuration.
- Load balancer security.
- DNS security.

Improper network configurations frequently lead to unauthorized access.

---

## 6. Security Monitoring

Customers are responsible for monitoring their cloud workloads and detecting suspicious activities.

Typical monitoring activities include:

- Reviewing audit logs.
- Monitoring privileged activities.
- Detecting unauthorized access.
- Monitoring configuration changes.
- Identifying anomalous behavior.
- Responding to alerts.
- Integrating logs with SIEM platforms.

Continuous monitoring helps identify threats before they escalate.

---

## 7. Regulatory Compliance

Cloud providers may support compliance through certifications and built-in controls, but customers remain responsible for meeting applicable regulatory obligations.

Responsibilities include:

- GDPR compliance.
- HIPAA compliance.
- PCI DSS compliance.
- Financial regulations.
- Internal governance requirements.
- Evidence collection.
- Audit preparation.
- Policy enforcement.

Compliance accountability cannot be outsourced to the cloud provider.

---

## 8. Business Continuity and Disaster Recovery

Organizations remain responsible for ensuring that critical business services can recover from disruptions.

Customer responsibilities include:

- Business Impact Analysis (BIA).
- Recovery planning.
- Backup validation.
- Disaster Recovery testing.
- Recovery procedures.
- Crisis management.
- Business continuity exercises.

Cloud availability does not automatically guarantee business continuity.

---

# Responsibilities Across Service Models

Customer responsibilities vary depending on the cloud service model.

| Responsibility | IaaS | PaaS | SaaS |
|---------------|:----:|:----:|:----:|
| Data Protection | ✔ | ✔ | ✔ |
| Identity Management | ✔ | ✔ | ✔ |
| User Access Control | ✔ | ✔ | ✔ |
| Application Security | ✔ | ✔ | Limited* |
| Operating System Security | ✔ | Provider | Provider |
| Middleware Security | ✔ | Provider | Provider |
| Network Configuration | ✔ | Partial | Limited |
| Compliance | ✔ | ✔ | ✔ |

*In SaaS, customers are primarily responsible for configuring security settings, managing users, and protecting business data within the application.

---

# Customer Responsibilities within GRC

From a Governance, Risk, and Compliance perspective, customers should establish processes to ensure responsibilities are consistently fulfilled.

These include:

- Cloud governance policies.
- Cloud risk assessments.
- Security awareness training.
- Asset inventories.
- Third-party risk management.
- Compliance monitoring.
- Internal audits.
- Continuous improvement.
- Executive reporting.
- Security metrics.

Strong governance ensures customer responsibilities are clearly assigned and regularly reviewed.

---

# Consequences of Neglecting Customer Responsibilities

Failing to fulfill customer responsibilities can lead to significant business impacts.

Potential consequences include:

- Data breaches.
- Regulatory penalties.
- Financial losses.
- Service disruptions.
- Ransomware attacks.
- Loss of customer trust.
- Legal liability.
- Audit findings.
- Reputational damage.
- Increased cyber risk.

Most cloud security incidents can be traced to customer-controlled areas such as identity management, access permissions, or configuration errors.

---

# Best Practices

Organizations should adopt the following practices to meet their cloud security responsibilities:

- Enforce Multi-Factor Authentication (MFA) for all users.
- Implement least-privilege access controls.
- Encrypt sensitive data at rest and in transit.
- Regularly review user permissions.
- Continuously monitor cloud activity.
- Conduct routine vulnerability assessments.
- Patch systems promptly.
- Test backup and recovery procedures.
- Maintain accurate asset inventories.
- Align governance with recognized security frameworks.
- Perform regular compliance reviews.
- Provide ongoing cloud security training.

These practices significantly reduce organizational risk.

---

📊 **Diagram Placeholder**

**Title:** Customer Responsibilities in the Shared Responsibility Model

**Diagram Description:**

```text
                Customer

                    │

 ┌──────────┬──────────┬──────────┐
 │          │          │          │
 ▼          ▼          ▼          ▼
Identity   Data     Applications  Compliance

 │          │          │          │
 ▼          ▼          ▼          ▼
Monitoring  Backup   Configuration Governance

                    │

          Business Continuity
```

**Caption:**

*"Regardless of the cloud service model, customers remain responsible for protecting their identities, data, applications, configurations, governance processes, and regulatory compliance. These responsibilities are fundamental to maintaining a secure cloud environment."*

---

# Practical Example

A global insurance company migrates several business applications to Microsoft Azure using an Infrastructure as a Service (IaaS) model. While Microsoft manages the physical data centers, networking infrastructure, and virtualization platform, the company remains responsible for configuring virtual machines, managing administrator accounts, securing customer databases, and monitoring security events.

During a routine security assessment, the cybersecurity team discovers that several virtual machines have not received critical operating system patches and that two administrator accounts lack Multi-Factor Authentication (MFA). Although the cloud infrastructure itself remains secure, these customer-controlled weaknesses significantly increase the organization's risk of compromise.

The company immediately deploys missing security updates, enables MFA for all privileged accounts, automates patch management, and introduces monthly access reviews. This reinforces that maintaining cloud security depends not only on the provider's infrastructure but also on the customer's ongoing governance, operational discipline, and security practices.

---

# Key Takeaways

- Cloud customers retain significant security responsibilities regardless of the cloud service model they use.
- Core customer responsibilities include identity management, data protection, application security, regulatory compliance, monitoring, and business continuity.
- In IaaS environments, customers also manage operating systems, network configurations, and virtual machine security.
- Customer responsibilities support Governance, Risk, and Compliance (GRC) by ensuring accountability, regulatory adherence, and effective risk management.
- Most cloud security incidents result from customer-controlled issues such as weak identities, excessive permissions, misconfigurations, or inadequate governance.
- Clearly understanding and fulfilling customer responsibilities is essential for building secure, resilient, and compliant cloud environments.

- # Cloud Provider Responsibilities

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the security responsibilities of Cloud Service Providers (CSPs).
- Identify the infrastructure and platform components managed by cloud providers.
- Explain how cloud providers ensure security, availability, and resilience.
- Recognize the provider's role in supporting compliance and regulatory requirements.
- Understand the limits of cloud provider responsibilities.
- Appreciate how cloud provider responsibilities fit within the Shared Responsibility Model.

---

# Introduction

Cloud Service Providers (CSPs) such as Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP) invest billions of dollars each year in securing their cloud infrastructure. They operate highly resilient data centers, implement advanced physical and logical security controls, and continuously monitor their environments to protect customers from infrastructure-level threats.

However, while providers deliver a secure cloud platform, they do not secure everything deployed within it. Their responsibilities focus on protecting the underlying infrastructure that enables cloud services, while customers remain responsible for securing the workloads, applications, identities, and data they place in the cloud.

Understanding where the provider's responsibilities begin and end enables organizations to deploy appropriate customer-managed controls and avoid dangerous assumptions.

---

# The Provider's Role in the Shared Responsibility Model

Cloud providers are responsible for the **security of the cloud**.

This means they protect the infrastructure that delivers cloud services, including:

- Physical facilities.
- Compute infrastructure.
- Storage infrastructure.
- Networking infrastructure.
- Virtualization platforms.
- Cloud service availability.
- Environmental controls.
- Infrastructure maintenance.

Customers rely on providers to operate secure, resilient, and highly available cloud platforms.

---

# Core Cloud Provider Responsibilities

Cloud providers manage numerous security and operational functions.

## 1. Physical Security

Cloud providers secure their data centers against physical threats.

Typical controls include:

- Security guards.
- Biometric access controls.
- CCTV surveillance.
- Visitor management.
- Physical access logging.
- Fencing and barriers.
- Intrusion detection systems.
- Environmental monitoring.

Physical security is entirely managed by the provider.

---

## 2. Data Center Infrastructure

Providers are responsible for maintaining the facilities that support cloud services.

This includes:

- Server hardware.
- Storage devices.
- Networking equipment.
- Power distribution.
- Cooling systems.
- Fire suppression.
- Environmental controls.
- Hardware replacement.

Customers never manage these components directly.

---

## 3. Network Infrastructure

Providers secure the backbone networks that connect cloud services.

Responsibilities include:

- Global backbone networks.
- Core routers.
- Internet connectivity.
- Network redundancy.
- DDoS mitigation infrastructure.
- Internal traffic management.
- Secure peering connections.
- Network availability.

Logical network configuration within customer environments remains the customer's responsibility.

---

## 4. Virtualization Layer

Virtualization enables multiple customers to share physical infrastructure securely.

Provider responsibilities include:

- Hypervisor security.
- Virtual machine isolation.
- Resource allocation.
- Hypervisor patching.
- Virtual infrastructure monitoring.
- Secure virtualization architecture.

Strong virtualization controls prevent customers from accessing one another's resources.

---

## 5. Cloud Platform Services

Providers maintain the cloud services they offer.

Examples include:

- Object storage services.
- Managed databases.
- Serverless platforms.
- Container platforms.
- Messaging services.
- Identity platforms.
- Artificial Intelligence (AI) services.
- Analytics platforms.

The provider ensures these managed services remain operational, patched, and available.

---

## 6. Infrastructure Maintenance

Cloud providers continuously maintain their infrastructure.

Activities include:

- Hardware replacement.
- Capacity expansion.
- Firmware updates.
- Infrastructure patching.
- Preventive maintenance.
- Performance optimization.
- Availability improvements.

These activities are performed with minimal disruption to customers.

---

## 7. Availability and Resilience

Providers design cloud platforms to achieve high availability.

Responsibilities include:

- Geographic redundancy.
- Fault-tolerant infrastructure.
- Data center resilience.
- Power redundancy.
- Network redundancy.
- Hardware failover.
- Infrastructure monitoring.
- Service recovery.

These capabilities enable customers to build highly available applications.

---

## 8. Infrastructure Security Monitoring

Cloud providers continuously monitor infrastructure for threats.

Typical monitoring includes:

- Infrastructure attacks.
- Hardware failures.
- Network anomalies.
- Distributed Denial-of-Service (DDoS) attacks.
- Hypervisor vulnerabilities.
- Platform integrity.
- Service health.
- Infrastructure incidents.

Provider monitoring protects the shared cloud platform but does not replace customer security monitoring.

---

# Compliance Responsibilities

Cloud providers support compliance by implementing recognized security frameworks and obtaining independent certifications.

Common certifications include:

- ISO/IEC 27001.
- ISO/IEC 27017.
- ISO/IEC 27018.
- SOC 1.
- SOC 2.
- SOC 3.
- PCI DSS.
- CSA STAR.
- ISO 22301.

These certifications demonstrate that the provider's infrastructure meets internationally recognized security standards.

However, provider certification does **not** automatically make customer workloads compliant.

---

# Provider Security Services

Most cloud providers offer optional security services to help customers strengthen their environments.

Examples include:

- Identity and Access Management (IAM).
- Key Management Services (KMS).
- Web Application Firewalls (WAF).
- Security Information and Event Management (SIEM).
- Cloud Security Posture Management (CSPM).
- Distributed Denial-of-Service (DDoS) protection.
- Security monitoring.
- Threat intelligence.
- Vulnerability assessment tools.

Although these services are provided by the cloud vendor, customers are responsible for configuring and using them correctly.

---

# What Cloud Providers Are NOT Responsible For

Despite their extensive responsibilities, providers generally do **not** manage:

- Customer data classification.
- User account management.
- Identity governance.
- Application security.
- Business logic.
- Customer operating systems (IaaS).
- Customer firewall rules.
- Customer encryption policies.
- Backup strategies (unless using managed backup services).
- Regulatory compliance for customer workloads.

These responsibilities remain with the customer.

---

# Cloud Provider Transparency

Leading providers publish documentation that helps customers understand security responsibilities.

This documentation typically includes:

- Shared Responsibility Models.
- Compliance reports.
- Audit reports.
- Service health dashboards.
- Security best practices.
- Reference architectures.
- Risk documentation.
- Incident notifications.

Organizations should regularly review provider documentation to understand available security capabilities and any changes to cloud services.

---

# Best Practices for Working with Cloud Providers

Organizations should:

- Review provider security documentation.
- Understand provider certifications.
- Evaluate provider compliance reports.
- Enable available security services.
- Monitor provider service advisories.
- Subscribe to security notifications.
- Review Service Level Agreements (SLAs).
- Assess third-party risks.
- Conduct regular cloud security reviews.
- Maintain communication with cloud vendors.

Effective collaboration improves both security and operational resilience.

---

📊 **Diagram Placeholder**

**Title:** Cloud Provider Responsibilities

**Diagram Description:**

```text
             Cloud Provider

                    │

 ┌──────────┬──────────┬──────────┐
 │          │          │          │
 ▼          ▼          ▼          ▼
Physical   Network   Virtualization
Security Infrastructure   Platform

 │          │          │
 ▼          ▼          ▼
Infrastructure   Availability   Monitoring

                    │

         Compliance & Certifications
```

**Caption:**

*"Cloud providers are responsible for securing the underlying infrastructure that supports cloud services, including physical facilities, networking, virtualization, platform operations, infrastructure monitoring, and globally recognized security certifications."*

---

# Practical Example

A manufacturing company hosts its enterprise resource planning (ERP) system on Amazon Web Services (AWS). AWS is responsible for securing the physical data centers, maintaining server hardware, protecting the global network infrastructure, patching the hypervisor, and ensuring the availability of managed cloud services.

When a hardware component in one data center fails, AWS automatically transfers workloads to redundant infrastructure without requiring customer intervention. The company's applications continue operating with minimal disruption because the provider's infrastructure resilience and availability controls function as designed.

However, during a later security review, the company discovers that an administrator accidentally granted excessive permissions to several users. Although AWS provides secure Identity and Access Management (IAM) services, configuring user permissions remains the customer's responsibility. This illustrates the distinction between provider-managed infrastructure security and customer-managed operational security.

---

# Key Takeaways

- Cloud Service Providers (CSPs) are responsible for the **security of the cloud**, including physical facilities, infrastructure, networking, virtualization, and platform operations.
- Providers invest heavily in physical security, infrastructure resilience, availability, monitoring, and globally recognized compliance certifications.
- Cloud providers offer numerous built-in security services, but customers are responsible for configuring and managing these services appropriately.
- Provider certifications support regulatory compliance but do not automatically make customer workloads compliant.
- Responsibilities such as identity management, application security, customer data protection, and governance remain with the customer.
- Understanding cloud provider responsibilities enables organizations to implement effective governance, reduce security gaps, and maximize the benefits of the Shared Responsibility Model.

- 
