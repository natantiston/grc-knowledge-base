# Lesson 13.8 – Cloud Identity and Access Management (IAM)

> **Chapter:** 13 – Cloud Security
>
> **Lesson:** 13.8
>
> **Topic:** Cloud Identity and Access Management (IAM)

> **Difficulty:** Intermediate

> **Estimated Reading Time:** 15–20 minutes

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of Identity and Access Management (IAM) in cloud computing.
- Explain the core components of IAM.
- Differentiate between authentication and authorization.
- Understand identities, accounts, roles, and permissions.
- Recognize the importance of IAM within the Cloud Shared Responsibility Model.
- Understand how IAM supports Governance, Risk, and Compliance (GRC).

---

# Introduction

As organizations migrate workloads to the cloud, protecting infrastructure alone is no longer sufficient. Cyber attackers increasingly target user identities, credentials, and privileged accounts because compromising an identity often provides direct access to valuable cloud resources.

Identity and Access Management (IAM) is the framework of policies, technologies, and processes used to ensure that only authorized users, applications, and services can access cloud resources. IAM is considered one of the most critical security controls in cloud computing because every action performed within a cloud environment is associated with an authenticated identity.

A well-designed IAM strategy reduces the risk of unauthorized access, limits insider threats, supports regulatory compliance, and enables organizations to implement modern security models such as Zero Trust Architecture.

---

# What is Identity and Access Management (IAM)?

Identity and Access Management (IAM) is the process of managing digital identities and controlling access to systems, applications, and data based on defined security policies.

IAM answers four fundamental questions:

- **Who** is requesting access?
- **What** are they allowed to access?
- **When** is access permitted?
- **Under what conditions** should access be granted?

By answering these questions consistently, IAM ensures that cloud resources are accessed only by trusted identities with appropriate permissions.

---

# Why IAM is Important

Effective IAM enables organizations to:

- Protect sensitive information.
- Prevent unauthorized access.
- Reduce insider threats.
- Secure privileged accounts.
- Support remote and hybrid work.
- Simplify user administration.
- Improve audit readiness.
- Meet regulatory requirements.

Since identities are often the primary target of cyberattacks, IAM serves as the foundation of cloud security.

---

# Core Components of IAM

Identity and Access Management consists of several interconnected components.

## Identity

An identity represents a person, application, device, or service that interacts with cloud resources.

Examples include:

- Employees.
- Contractors.
- Customers.
- Administrators.
- Virtual machines.
- Applications.
- APIs.
- Service accounts.

Each identity should be unique and managed throughout its lifecycle.

---

## Authentication

Authentication verifies that an identity is who it claims to be.

Common authentication methods include:

- Username and password.
- Multi-Factor Authentication (MFA).
- Biometric authentication.
- Smart cards.
- Security keys.
- Digital certificates.
- Single Sign-On (SSO).

Authentication answers the question:

> **"Who are you?"**

---

## Authorization

Authorization determines what an authenticated identity is permitted to do.

Examples include:

- Viewing files.
- Creating virtual machines.
- Managing databases.
- Deleting storage accounts.
- Reading security logs.
- Approving configuration changes.

Authorization answers the question:

> **"What are you allowed to do?"**

---

# Authentication vs Authorization

Although closely related, authentication and authorization perform different functions.

| Authentication | Authorization |
|---------------|---------------|
| Verifies identity | Determines permissions |
| Occurs first | Occurs after authentication |
| Confirms who the user is | Determines what the user can access |
| Uses credentials | Uses policies and permissions |

Both processes are required before access to cloud resources is granted.

---

# Identities in Cloud Environments

Cloud platforms manage different types of identities.

### Human Identities

Examples include:

- Employees.
- System administrators.
- Business users.
- Contractors.
- Partners.

---

### Machine Identities

Cloud services also create identities for non-human entities such as:

- Virtual machines.
- Containers.
- Serverless functions.
- Applications.
- APIs.
- Automation scripts.

These identities authenticate with other cloud services without requiring user credentials.

---

# Accounts, Roles, and Permissions

IAM organizes access using accounts, roles, and permissions.

### Account

An account represents a user or service identity within the cloud platform.

---

### Role

A role is a predefined collection of permissions.

Examples include:

- Administrator.
- Security Administrator.
- Network Administrator.
- Database Administrator.
- Read-Only User.
- Billing Administrator.

Assigning roles simplifies access management.

---

### Permission

Permissions define specific actions an identity may perform.

Examples include:

- Read.
- Create.
- Modify.
- Delete.
- Approve.
- Manage.
- Execute.

Roles group related permissions together.

---

# Access Decision Flow

Cloud IAM evaluates access requests through a structured process.

```text
User or Service

        │

        ▼

Authentication

        │

        ▼

Identity Verified

        │

        ▼

Authorization Policy

        │

        ▼

Role & Permissions Evaluated

        │

        ▼

Access Granted or Denied
```

Every request is validated before access to cloud resources is permitted.

---

# IAM in Major Cloud Platforms

Every major cloud provider offers a comprehensive IAM service.

### Microsoft Azure

Azure provides:

- Microsoft Entra ID (formerly Azure Active Directory).
- Azure Role-Based Access Control (Azure RBAC).
- Managed Identities.
- Conditional Access.
- Privileged Identity Management (PIM).

---

### Amazon Web Services (AWS)

AWS Identity and Access Management (IAM) provides:

- Users.
- Groups.
- Roles.
- Policies.
- Temporary credentials.
- Identity federation.

---

### Google Cloud Platform (GCP)

Google Cloud IAM provides:

- Principals.
- Roles.
- Permissions.
- Service Accounts.
- IAM Conditions.
- Organization-level policies.

Although terminology differs, the underlying IAM concepts remain consistent across cloud providers.

---

# IAM and the Shared Responsibility Model

Identity management is primarily the customer's responsibility.

Cloud providers are responsible for securing the underlying IAM infrastructure, while customers are responsible for:

- Creating user accounts.
- Assigning permissions.
- Managing privileged access.
- Protecting credentials.
- Reviewing access regularly.
- Enabling Multi-Factor Authentication (MFA).

Poor IAM practices remain one of the leading causes of cloud security incidents.

---

# IAM within GRC

Identity and Access Management is a cornerstone of Governance, Risk, and Compliance.

### Governance

Organizations establish:

- Identity governance policies.
- Access approval workflows.
- Role definitions.
- Account lifecycle procedures.
- Segregation of Duties (SoD).

---

### Risk Management

Strong IAM reduces risks associated with:

- Unauthorized access.
- Credential theft.
- Insider threats.
- Privilege abuse.
- Account compromise.
- Regulatory violations.

---

### Compliance

IAM supports compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-53.
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Identity controls and access reviews are frequently evaluated during security audits.

---

# Best Practices

Organizations should:

- Establish a centralized IAM solution.
- Create unique identities for every user.
- Avoid shared accounts.
- Assign permissions using roles rather than individual permissions.
- Regularly review user access.
- Remove unused accounts promptly.
- Enable Multi-Factor Authentication for all privileged users.
- Monitor authentication activities.
- Document IAM policies and procedures.
- Conduct periodic access certification reviews.

Following these practices strengthens cloud security while simplifying identity administration.

---

📊 **Diagram Placeholder**

**Title:** Identity and Access Management Process

**Diagram Description:**

```text
          User or Application

                  │

                  ▼

          Authentication

                  │

        Identity Verified

                  │

                  ▼

        Authorization Policy

                  │

        Role & Permissions

                  │

          ┌───────┴────────┐
          │                │
          ▼                ▼

   Access Granted    Access Denied
```

**Caption:**

*"Identity and Access Management (IAM) verifies identities through authentication and determines authorized activities through authorization policies, ensuring that only approved users and services can access cloud resources."*

---

# Practical Example

A multinational manufacturing company uses Microsoft Azure to host its enterprise applications. Employees authenticate through **Microsoft Entra ID** using Multi-Factor Authentication (MFA). Engineers are assigned a "Virtual Machine Administrator" role that allows them to manage virtual machines but prevents access to financial databases. Finance personnel receive read and write permissions only for accounting applications, while security administrators use Privileged Identity Management (PIM) to obtain temporary administrative privileges when required.

Quarterly access reviews identify inactive accounts and excessive permissions, allowing the organization to remove unnecessary access and strengthen compliance with ISO/IEC 27001 and internal governance policies.

---

# Key Takeaways

- Identity and Access Management (IAM) ensures that only authorized users, applications, and services can access cloud resources.
- Authentication verifies an identity, while authorization determines the actions that an authenticated identity is permitted to perform.
- IAM manages identities, accounts, roles, and permissions to enforce secure and consistent access control across cloud environments.
- Major cloud providers offer comprehensive IAM services that support centralized identity management, role-based access control, and secure authentication.
- Organizations are responsible for managing identities, assigning permissions, protecting credentials, and reviewing access under the Shared Responsibility Model.
- From a Governance, Risk, and Compliance (GRC) perspective, IAM is a foundational security capability that reduces unauthorized access, strengthens governance, and supports regulatory compliance.

- 
