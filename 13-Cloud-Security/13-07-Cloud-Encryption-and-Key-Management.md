# Lesson 13.7 – Cloud Encryption and Key Management

> **Chapter:** 13 – Cloud Security
>
> **Lesson:** 13.7
>
> **Topic:** Cloud Encryption and Key Management

> **Difficulty:** Intermediate

> **Estimated Reading Time:** 15–20 minutes

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the role of encryption in cloud security.
- Differentiate between data at rest, data in transit, and data in use.
- Explain common encryption algorithms and techniques.
- Recognize the shared responsibility for encryption in cloud environments.
- Understand how encryption supports Governance, Risk, and Compliance (GRC).
- Identify best practices for implementing encryption in cloud services.

---

# Introduction

Cloud computing enables organizations to store and process vast amounts of sensitive information, including customer records, financial transactions, healthcare data, intellectual property, and confidential business information. Protecting this data is one of the most important responsibilities of every cloud security program.

Encryption is one of the most effective security controls available. It converts readable information into an unreadable format using cryptographic algorithms, ensuring that only authorized users with the correct cryptographic keys can access the original data. Even if attackers gain access to encrypted information, the data remains unusable without the corresponding decryption key.

Modern cloud providers offer encryption capabilities across nearly every cloud service. However, organizations remain responsible for determining when encryption is required, selecting appropriate encryption methods, managing encryption keys, and ensuring compliance with legal and regulatory requirements.

---

# What is Encryption?

Encryption is the process of transforming plaintext into ciphertext using a cryptographic algorithm and an encryption key.

The encrypted data cannot be interpreted without the appropriate decryption key.

A simplified process is shown below.

```text
Plaintext

      │

Encryption Algorithm

      │

Encryption Key

      │

      ▼

Ciphertext

      │

Decryption Key

      ▼

Original Plaintext
```

Encryption protects information against unauthorized disclosure, even if the storage media or communication channel is compromised.

---

# Why Encryption is Important

Organizations encrypt data to:

- Protect confidential information.
- Prevent unauthorized disclosure.
- Reduce the impact of data breaches.
- Secure cloud storage.
- Protect network communications.
- Meet contractual obligations.
- Support privacy regulations.
- Demonstrate regulatory compliance.

Encryption is considered a foundational security control across cloud, on-premises, and hybrid environments.

---

# Types of Data Requiring Encryption

Cloud environments contain several categories of data that require protection.

Examples include:

- Customer information.
- Personally Identifiable Information (PII).
- Financial records.
- Payment card data.
- Medical records.
- Intellectual property.
- Authentication credentials.
- Encryption keys.
- Business documents.
- Backup files.

Organizations should classify their information and apply encryption according to data sensitivity.

---

# Data States

Cloud security commonly classifies information into three data states.

## Data at Rest

Data at rest refers to information stored on persistent media.

Examples include:

- Cloud storage accounts.
- Virtual machine disks.
- Databases.
- Backup repositories.
- File systems.
- Object storage.

Encryption at rest protects information if storage devices are stolen, accessed without authorization, or compromised.

---

## Data in Transit

Data in transit refers to information moving between systems.

Examples include:

- Web browsing.
- API communication.
- Email transmission.
- VPN traffic.
- Database replication.
- Application communication.

Protocols such as TLS (Transport Layer Security) protect data while it travels across networks.

---

## Data in Use

Data in use refers to information currently being processed by applications or operating in system memory.

Traditionally, this has been the most difficult state to protect because applications require access to unencrypted data during processing.

Emerging technologies such as confidential computing and trusted execution environments help reduce risks associated with processing sensitive information.

---

# Common Encryption Techniques

Encryption generally falls into two categories.

## Symmetric Encryption

Symmetric encryption uses the same key for both encryption and decryption.

Characteristics include:

- Fast performance.
- Efficient for large volumes of data.
- Widely used for storage encryption.
- Lower computational overhead.

A commonly used algorithm is:

- Advanced Encryption Standard (AES).

AES-256 is widely recognized as the industry standard for protecting sensitive information.

---

## Asymmetric Encryption

Asymmetric encryption uses two related keys:

- Public key.
- Private key.

The public key encrypts data, while the private key decrypts it.

Characteristics include:

- Secure key exchange.
- Digital signatures.
- Authentication.
- Certificate management.

Common algorithms include:

- RSA.
- Elliptic Curve Cryptography (ECC).

Because asymmetric encryption requires more computational resources, it is often used to establish secure sessions rather than encrypt large amounts of data directly.

---

# Encryption in Cloud Services

Most cloud providers support encryption across multiple services.

Examples include:

- Virtual machine disks.
- Object storage.
- Managed databases.
- File storage.
- Backup services.
- Kubernetes secrets.
- Managed messaging services.

Organizations should verify that encryption is enabled and configured according to their security policies.

---

# Shared Responsibility for Encryption

Encryption responsibilities vary depending on the cloud service model.

| Service Model | Cloud Provider Responsibility | Customer Responsibility |
|---------------|-------------------------------|-------------------------|
| SaaS | Encrypts underlying platform | Protects user accounts, manages access, and configures available encryption options |
| PaaS | Encrypts platform services | Protects applications, manages sensitive data, and configures encryption features |
| IaaS | Provides encryption capabilities | Enables encryption, protects workloads, manages keys, and secures operating systems |

Understanding these responsibilities helps organizations avoid security gaps.

---

# Encryption within GRC

Encryption is an essential component of Governance, Risk, and Compliance.

### Governance

Organizations establish policies that define:

- Which data must be encrypted.
- Approved encryption standards.
- Key ownership.
- Cryptographic responsibilities.
- Data classification requirements.

---

### Risk Management

Encryption reduces risks associated with:

- Data breaches.
- Unauthorized disclosure.
- Insider threats.
- Lost storage devices.
- Network interception.
- Regulatory penalties.

Although encryption does not prevent every attack, it significantly limits the impact of unauthorized access.

---

### Compliance

Encryption supports compliance with numerous regulations and standards, including:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-53.
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Many regulatory frameworks require encryption for sensitive information both at rest and in transit.

---

# Best Practices

Organizations should:

- Encrypt sensitive data by default.
- Use strong, industry-approved algorithms.
- Enable encryption for storage and databases.
- Protect data in transit using TLS.
- Classify information before selecting encryption controls.
- Regularly review cryptographic configurations.
- Monitor encryption compliance.
- Document encryption standards.
- Rotate encryption keys according to policy.
- Test recovery procedures for encrypted data.

Implementing these practices strengthens cloud security and improves organizational resilience.

---

📊 **Diagram Placeholder**

**Title:** Data Encryption Across Different States

**Diagram Description:**

```text
                Sensitive Data

                      │

      ┌───────────────┼───────────────┐
      │               │               │
      ▼               ▼               ▼

 Data at Rest   Data in Transit   Data in Use

      │               │               │

 Storage        TLS / VPN / HTTPS   Memory

      │               │               │

      └───────────────┼───────────────┘

                      ▼

              Encryption Controls
```

**Caption:**

*"Cloud encryption protects sensitive information throughout its lifecycle by securing data at rest, safeguarding communications while data is in transit, and supporting emerging technologies that protect data during processing."*

---

# Practical Example

A global healthcare organization stores patient medical records in a cloud-hosted database. Database storage volumes are encrypted using AES-256, while all communication between hospitals and the cloud platform is protected with TLS 1.3. Backup files are automatically encrypted before being stored in object storage, and encryption policies are enforced across all production environments.

During an external compliance audit, the organization demonstrates that sensitive patient information is encrypted at rest and in transit, helping satisfy the security requirements of ISO/IEC 27001, HIPAA, and GDPR while significantly reducing the risk of unauthorized data disclosure.

---

# Key Takeaways

- Encryption converts readable data into ciphertext, protecting sensitive information from unauthorized access.
- Organizations should protect data in all three states: at rest, in transit, and in use.
- Symmetric encryption provides efficient protection for stored data, while asymmetric encryption supports secure key exchange, authentication, and digital signatures.
- Cloud providers offer encryption capabilities across most cloud services, but customers remain responsible for enabling and managing encryption according to the shared responsibility model.
- Strong encryption policies, combined with proper data classification and secure key management, reduce the impact of data breaches and strengthen organizational resilience.
- From a Governance, Risk, and Compliance (GRC) perspective, encryption is a foundational security control that supports regulatory compliance, protects confidential information, and enhances trust in cloud services.
- #

- # Key Management Services (KMS)

Encryption is only as secure as the protection of its encryption keys. Regardless of how strong an encryption algorithm is, if an attacker gains access to the encryption keys, the encrypted data can be decrypted. For this reason, effective key management is one of the most critical aspects of cloud security.

Cloud providers offer managed **Key Management Services (KMS)** that enable organizations to securely create, store, rotate, and control cryptographic keys used to protect cloud resources. These services reduce the complexity of managing encryption keys while providing centralized control, auditing, and integration with cloud services.

---

# What is Key Management?

Key management is the process of managing cryptographic keys throughout their entire lifecycle.

This includes:

- Key generation.
- Key storage.
- Key distribution.
- Key usage.
- Key rotation.
- Key backup.
- Key archival.
- Key destruction.

A secure key management process ensures that encryption keys remain confidential, available, and protected against unauthorized access.

---

# Why Key Management is Important

Proper key management helps organizations:

- Protect encrypted data.
- Prevent unauthorized decryption.
- Reduce insider threats.
- Support regulatory compliance.
- Enable secure data sharing.
- Simplify encryption administration.
- Improve audit readiness.
- Support business continuity.

Weak key management can undermine even the strongest encryption algorithms.

---

# Encryption Keys

An encryption key is a unique cryptographic value used by an encryption algorithm to encrypt or decrypt information.

Different keys may be used for:

- Disk encryption.
- Database encryption.
- File encryption.
- Backup encryption.
- Application encryption.
- API encryption.
- Digital certificates.
- Secure communications.

Protecting these keys is essential because anyone possessing the correct key may be able to access encrypted information.

---

# Key Lifecycle

Encryption keys pass through several lifecycle stages.

```text
Generate

      │

Store

      │

Distribute

      │

Use

      │

Rotate

      │

Archive

      │

Destroy
```

Organizations should establish documented procedures for each stage to reduce operational and security risks.

---

# Types of Encryption Keys

Cloud environments commonly use several categories of keys.

## Customer-Managed Keys (CMKs)

Customer-Managed Keys are created and controlled by the customer.

Organizations are responsible for:

- Key ownership.
- Access control.
- Rotation policies.
- Lifecycle management.
- Auditing.

CMKs provide the highest level of control and are often required for regulated industries.

---

## Provider-Managed Keys

Cloud providers can automatically manage encryption keys on behalf of customers.

The provider handles:

- Key generation.
- Secure storage.
- Rotation.
- Availability.
- Infrastructure protection.

Provider-managed keys simplify administration but offer less direct control.

---

## Bring Your Own Key (BYOK)

Some organizations choose to generate encryption keys outside the cloud and import them into a cloud Key Management Service.

Benefits include:

- Greater ownership.
- Regulatory compliance.
- Integration with existing enterprise key management.
- Consistent cryptographic governance.

BYOK is common among organizations with strict compliance or sovereignty requirements.

---

# Major Cloud Key Management Services

Each major cloud provider offers a managed key management solution.

## Microsoft Azure Key Vault

Azure Key Vault enables organizations to:

- Store encryption keys.
- Protect secrets.
- Manage digital certificates.
- Rotate keys.
- Control access through Azure Active Directory.
- Monitor key usage.

---

## AWS Key Management Service (AWS KMS)

AWS KMS provides:

- Centralized key management.
- Automatic key rotation.
- Integration with AWS services.
- Fine-grained access control.
- Audit logging with AWS CloudTrail.

---

## Google Cloud Key Management

Google Cloud KMS supports:

- Centralized encryption keys.
- Hardware-backed key protection.
- Automatic rotation.
- IAM-based access control.
- Cloud-native integrations.

These managed services simplify encryption management across cloud workloads.

---

# Hardware Security Modules (HSMs)

For highly sensitive environments, organizations may use **Hardware Security Modules (HSMs)**.

An HSM is a dedicated tamper-resistant device designed to securely generate, store, and process cryptographic keys.

Benefits include:

- Hardware-based protection.
- Strong physical security.
- FIPS-certified cryptographic operations.
- Secure key generation.
- Resistance to tampering.

Cloud providers also offer managed HSM services, allowing organizations to benefit from hardware-backed key protection without maintaining physical appliances.

---

# Key Rotation

Key rotation is the process of replacing an existing encryption key with a new one.

Organizations rotate keys to:

- Reduce the impact of key compromise.
- Meet regulatory requirements.
- Strengthen cryptographic security.
- Support security policies.

Rotation may occur:

- Automatically.
- On a defined schedule.
- Following a security incident.
- After personnel changes.

Regular key rotation reduces long-term exposure if a key is compromised.

---

# Access Control for Keys

Encryption keys should be accessible only to authorized users and systems.

Common security controls include:

- Role-Based Access Control (RBAC).
- Multi-Factor Authentication (MFA).
- Least Privilege.
- Separation of Duties.
- Just-In-Time (JIT) access.
- Privileged Identity Management (PIM).

Strict access control helps prevent accidental or malicious misuse of cryptographic keys.

---

# Auditing and Monitoring

Key management services maintain detailed audit logs.

Typical events include:

- Key creation.
- Key deletion.
- Key rotation.
- Access attempts.
- Permission changes.
- Failed authentication.
- Administrative actions.

Continuous monitoring enables organizations to detect suspicious activity and demonstrate compliance during security audits.

---

# Key Management within GRC

Effective key management supports Governance, Risk, and Compliance initiatives.

### Governance

Organizations establish policies covering:

- Key ownership.
- Cryptographic standards.
- Rotation schedules.
- Access approval processes.
- Key lifecycle management.

---

### Risk Management

Strong key management reduces risks associated with:

- Key theft.
- Unauthorized decryption.
- Insider misuse.
- Data breaches.
- Regulatory violations.
- Loss of sensitive information.

---

### Compliance

Key management supports compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-57 (Key Management).
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Auditors frequently review key management processes, access controls, and rotation policies.

---

# Best Practices

Organizations should:

- Use centralized Key Management Services.
- Protect highly sensitive keys with Hardware Security Modules (HSMs).
- Rotate keys regularly.
- Apply the Principle of Least Privilege.
- Enable Multi-Factor Authentication for administrators.
- Separate key management duties from application administration.
- Monitor key usage continuously.
- Audit all key-related activities.
- Remove unused or obsolete keys.
- Document key lifecycle procedures.

Implementing these practices strengthens encryption security and improves operational resilience.

---

📊 **Diagram Placeholder**

**Title:** Encryption Key Lifecycle

**Diagram Description:**

```text
          Generate Key

                │

                ▼

          Secure Storage

                │

                ▼

          Controlled Access

                │

                ▼

         Encrypt / Decrypt

                │

                ▼

          Rotate Periodically

                │

                ▼

       Archive or Destroy
```

**Caption:**

*"Encryption keys must be securely managed throughout their lifecycle. Effective key management includes secure generation, storage, controlled access, regular rotation, auditing, and secure destruction when keys are no longer required."*

---

# Practical Example

A financial institution stores customer transaction records in Amazon Web Services (AWS). Rather than relying solely on provider-managed encryption, the organization uses **AWS Key Management Service (AWS KMS)** with **Customer-Managed Keys (CMKs)** to control encryption for its databases, storage buckets, and backup repositories.

Access to encryption keys is restricted through Identity and Access Management (IAM) policies and Multi-Factor Authentication (MFA). Automatic key rotation is enabled annually, and all key usage events are logged through AWS CloudTrail. During an external PCI DSS audit, the organization demonstrates centralized key management, comprehensive audit logs, and strict access controls, confirming that sensitive financial data is protected throughout its lifecycle.

---

# Key Takeaways

- Encryption keys are the foundation of cryptographic security and must be protected throughout their lifecycle.
- Key Management Services (KMS) simplify the creation, storage, rotation, and auditing of encryption keys across cloud environments.
- Organizations can choose between provider-managed keys, customer-managed keys (CMKs), or Bring Your Own Key (BYOK) depending on business and regulatory requirements.
- Hardware Security Modules (HSMs) provide hardware-backed protection for highly sensitive cryptographic keys.
- Strong access controls, regular key rotation, and continuous monitoring reduce the risk of unauthorized key use and data compromise.
- From a Governance, Risk, and Compliance (GRC) perspective, effective key management supports regulatory compliance, strengthens encryption governance, and protects critical business information.

- # Encryption in Cloud Storage and Databases

Cloud environments store enormous amounts of sensitive information, including customer records, financial transactions, healthcare data, intellectual property, and business-critical applications. Protecting this information requires more than securing the network—it also requires encrypting the data wherever it is stored.

Most cloud providers offer built-in encryption capabilities for storage services, databases, virtual machine disks, and backup systems. Organizations should understand how these services implement encryption and ensure that appropriate encryption policies are consistently applied across all environments.

---

# Why Encrypt Stored Data?

Data stored in cloud environments may be exposed through:

- Unauthorized access.
- Stolen credentials.
- Insider threats.
- Misconfigured storage.
- Lost backup media.
- Infrastructure compromise.
- Data breaches.

Encryption protects stored information by ensuring that even if storage media or cloud resources are compromised, the data remains unreadable without the appropriate encryption keys.

---

# Storage Encryption

Cloud storage services support encryption for data stored in:

- Object storage.
- Block storage.
- File storage.
- Backup repositories.
- Archive storage.

Encryption is typically performed automatically before the data is written to physical storage and remains encrypted until it is accessed by an authorized user or application.

---

# Object Storage Encryption

Object storage is commonly used for:

- Documents.
- Images.
- Videos.
- Backup files.
- Application data.
- Log files.

Examples include:

- Azure Blob Storage.
- Amazon Simple Storage Service (Amazon S3).
- Google Cloud Storage.

Most providers automatically encrypt newly stored objects, while organizations can choose whether to use provider-managed or customer-managed encryption keys.

---

# Block Storage Encryption

Block storage provides virtual disks for cloud workloads.

Examples include:

- Azure Managed Disks.
- Amazon Elastic Block Store (Amazon EBS).
- Google Persistent Disk.

Encrypting block storage protects:

- Operating systems.
- Installed applications.
- Temporary files.
- Virtual machine data.
- System configurations.

Encryption occurs transparently without requiring application changes.

---

# File Storage Encryption

Cloud file services enable multiple users or applications to access shared files securely.

Examples include:

- Azure Files.
- Amazon Elastic File System (Amazon EFS).
- Google Filestore.

Encryption protects shared folders, business documents, application files, and collaborative data stored within these services.

---

# Database Encryption

Databases often contain an organization's most sensitive information.

Cloud database services support encryption for:

- Customer information.
- Financial transactions.
- Employee records.
- Healthcare information.
- Authentication credentials.
- Business analytics.

Encryption protects database files, transaction logs, backups, and snapshots.

---

# Transparent Data Encryption (TDE)

Many relational databases implement **Transparent Data Encryption (TDE)**.

TDE encrypts database files without requiring modifications to applications.

Benefits include:

- Automatic encryption.
- Minimal administrative effort.
- Protection of database files.
- Protection of backup files.
- Regulatory compliance support.

Common database platforms supporting TDE include:

- Microsoft SQL Server.
- Azure SQL Database.
- Oracle Database.
- PostgreSQL (cloud-managed implementations).
- MySQL (cloud-managed implementations).

---

# Database Backup Encryption

Database backups contain complete copies of business information and must receive the same level of protection as production databases.

Organizations should encrypt:

- Full backups.
- Incremental backups.
- Differential backups.
- Archived backups.
- Replicated backups.

Encrypted backups help prevent unauthorized disclosure if backup files are stolen or accessed improperly.

---

# Snapshot Encryption

Cloud providers allow administrators to create storage snapshots for backup and recovery.

Snapshots may include:

- Virtual machine disks.
- Databases.
- Storage volumes.
- File systems.

Encrypted snapshots ensure that recovery data remains protected throughout its lifecycle.

---

# Server-Side Encryption

Server-Side Encryption (SSE) encrypts data after it reaches the cloud provider.

The cloud provider performs:

- Encryption.
- Key management (unless customer-managed keys are used).
- Decryption during authorized access.

Advantages include:

- Simple deployment.
- Automatic encryption.
- Minimal application changes.
- Cloud-native integration.

SSE is the default encryption model for many cloud storage services.

---

# Client-Side Encryption

Client-Side Encryption (CSE) encrypts information before it leaves the customer's environment.

The organization controls:

- Encryption algorithms.
- Encryption keys.
- Decryption process.

Benefits include:

- Greater control over sensitive data.
- Enhanced privacy.
- Reduced reliance on cloud providers.
- Support for strict regulatory requirements.

Because data arrives at the cloud already encrypted, providers never see the plaintext.

---

# Comparing Server-Side and Client-Side Encryption

| Feature | Server-Side Encryption | Client-Side Encryption |
|---------|------------------------|------------------------|
| Encryption Location | Cloud provider | Customer environment |
| Key Ownership | Provider or customer | Customer |
| Ease of Deployment | High | Moderate |
| Administrative Overhead | Low | Higher |
| Provider Access to Plaintext | Possible during processing | No |
| Regulatory Control | Moderate | High |

Organizations often combine both approaches depending on business and compliance requirements.

---

# Storage Encryption in Major Cloud Platforms

### Microsoft Azure

Encryption capabilities include:

- Azure Storage Service Encryption.
- Azure Disk Encryption.
- Azure SQL Transparent Data Encryption.
- Azure Backup Encryption.

---

### Amazon Web Services (AWS)

Encryption services include:

- Amazon S3 Server-Side Encryption.
- Amazon EBS Encryption.
- Amazon RDS Encryption.
- AWS Backup Encryption.

---

### Google Cloud Platform (GCP)

Google Cloud provides:

- Cloud Storage Encryption.
- Persistent Disk Encryption.
- Cloud SQL Encryption.
- Automatic encryption of managed services.

These services integrate with each provider's Key Management Service (KMS).

---

# Encryption Performance Considerations

Modern cloud platforms are optimized for encryption, making performance impacts relatively small.

Organizations should still evaluate:

- CPU utilization.
- Storage throughput.
- Database performance.
- Application latency.
- Backup duration.
- Recovery performance.

Performance testing helps ensure encryption does not negatively affect business operations.

---

# Encryption within GRC

Encryption of cloud storage and databases supports Governance, Risk, and Compliance objectives.

### Governance

Organizations define policies covering:

- Data classification.
- Encryption requirements.
- Approved storage services.
- Key ownership.
- Backup protection.

---

### Risk Management

Storage encryption reduces risks such as:

- Data theft.
- Unauthorized disclosure.
- Lost storage media.
- Insider threats.
- Misconfigured storage.
- Regulatory penalties.

---

### Compliance

Encrypted storage supports compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-53.
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Many regulations explicitly require encryption for sensitive information stored in databases and cloud storage services.

---

# Best Practices

Organizations should:

- Enable encryption for all cloud storage services.
- Encrypt all production databases.
- Encrypt backups and snapshots.
- Use Customer-Managed Keys (CMKs) for highly sensitive workloads.
- Regularly review encryption configurations.
- Protect storage with strong access controls.
- Monitor storage access logs.
- Test encrypted backup restoration procedures.
- Document encryption standards.
- Periodically verify compliance with encryption policies.

Implementing these practices helps ensure that sensitive information remains protected throughout its lifecycle.

---

📊 **Diagram Placeholder**

**Title:** Encryption of Cloud Storage and Databases

**Diagram Description:**

```text
              Business Data

                    │

        ┌───────────┼────────────┐
        │           │            │
        ▼           ▼            ▼

   Object Storage  Database   VM Disk

        │           │            │

        └───────────┼────────────┘

                    ▼

          Encryption Service

                    │

        Key Management Service

                    │

                    ▼

           Encrypted Cloud Data
```

**Caption:**

*"Cloud storage, databases, and virtual machine disks should be encrypted using centralized key management services. Encrypting data at rest protects sensitive information against unauthorized access while supporting regulatory compliance."*

---

# Practical Example

A multinational insurance company stores customer policy documents in Amazon S3, transaction records in Amazon RDS, and virtual machine workloads on Amazon EBS volumes. To protect sensitive information, the organization enables **Server-Side Encryption (SSE)** for object storage, **Transparent Data Encryption (TDE)** for managed databases, and encryption for all EBS volumes using **Customer-Managed Keys (CMKs)** in AWS Key Management Service (AWS KMS).

Database backups and storage snapshots are also encrypted before being archived. Access to encryption keys is restricted through Identity and Access Management (IAM) policies, and all encryption-related events are logged through AWS CloudTrail. This approach protects sensitive customer information, reduces the impact of potential data breaches, and helps the organization comply with ISO/IEC 27001, PCI DSS, and GDPR requirements.

---

# Key Takeaways

- Encryption protects cloud storage, databases, backups, and snapshots from unauthorized access by rendering stored data unreadable without the appropriate cryptographic keys.
- Object storage, block storage, file storage, and managed database services offered by major cloud providers support built-in encryption capabilities.
- Transparent Data Encryption (TDE) protects relational databases without requiring application modifications, while encrypted backups and snapshots secure recovery data.
- Server-Side Encryption simplifies deployment, whereas Client-Side Encryption provides greater customer control over encryption keys and sensitive information.
- Integrating storage encryption with centralized Key Management Services (KMS) strengthens cryptographic governance and simplifies key administration.
- From a Governance, Risk, and Compliance (GRC) perspective, encrypting cloud storage and databases reduces cyber risk, supports regulatory compliance, and protects business-critical information throughout its lifecycle.

- 
- 
