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

- # Authentication and Multi-Factor Authentication (MFA)

Authentication is the process of verifying the identity of a user, application, or service before access to cloud resources is granted. It serves as the first line of defense in Identity and Access Management (IAM), ensuring that only legitimate identities can access organizational systems and data.

As cyberattacks increasingly target user credentials through phishing, password spraying, credential stuffing, and brute-force attacks, relying solely on usernames and passwords is no longer sufficient. Organizations now implement stronger authentication methods, particularly **Multi-Factor Authentication (MFA)**, to significantly reduce the risk of unauthorized access.

---

# Understanding Authentication

Authentication answers a simple but critical question:

> **"Are you really who you claim to be?"**

Before any access request is approved, the cloud platform verifies the identity using one or more authentication factors.

A typical authentication process is illustrated below.

```text
User Requests Access

          │

          ▼

Enter Credentials

          │

          ▼

Identity Verification

          │

          ▼

Authentication Successful

          │

          ▼

Authorization Process
```

Only after successful authentication does the system evaluate the user's permissions.

---

# Authentication Factors

Authentication methods are generally categorized into three factors.

## Something You Know

Knowledge factors rely on information known only to the user.

Examples include:

- Passwords.
- PINs.
- Passphrases.
- Security questions.

Although widely used, these methods are vulnerable to phishing and password reuse attacks.

---

## Something You Have

Possession factors require the user to possess a trusted device or object.

Examples include:

- Mobile authentication applications.
- Hardware security keys.
- Smart cards.
- One-Time Password (OTP) tokens.
- SMS verification codes.

This factor significantly increases account security because attackers must possess the physical device.

---

## Something You Are

Biometric factors verify unique physical characteristics.

Examples include:

- Fingerprint recognition.
- Facial recognition.
- Iris scanning.
- Voice recognition.

Biometric authentication improves convenience while providing strong identity verification.

---

# Single-Factor Authentication (SFA)

Single-Factor Authentication requires only one authentication factor, typically a username and password.

Example:

```text
Username

+

Password

↓

Access Granted
```

Although simple, SFA provides limited protection because compromised passwords often result in unauthorized access.

---

# Multi-Factor Authentication (MFA)

Multi-Factor Authentication requires two or more independent authentication factors before granting access.

Example:

```text
Username

+

Password

+

Mobile Authenticator Approval

↓

Access Granted
```

Even if an attacker steals a password, access is denied without the additional authentication factor.

---

# Benefits of Multi-Factor Authentication

Implementing MFA helps organizations:

- Reduce credential theft.
- Prevent unauthorized access.
- Minimize phishing risks.
- Protect privileged accounts.
- Secure remote access.
- Improve regulatory compliance.
- Strengthen Zero Trust implementations.
- Reduce successful account compromise.

MFA is considered one of the most effective and cost-efficient security controls available.

---

# Common MFA Methods

Organizations may deploy various MFA technologies.

### Authenticator Applications

Applications generate time-based one-time passwords (TOTPs) or require approval notifications.

Examples include:

- Microsoft Authenticator.
- Google Authenticator.
- Duo Mobile.

These applications are more secure than SMS-based authentication.

---

### Hardware Security Keys

Hardware security keys use cryptographic authentication.

Examples include:

- FIDO2 security keys.
- USB security keys.
- NFC authentication devices.

Hardware keys provide strong protection against phishing attacks.

---

### SMS Verification

Users receive a one-time verification code through text messaging.

Although widely supported, SMS authentication is vulnerable to SIM swapping and interception attacks.

Many organizations are gradually replacing SMS-based authentication with stronger methods.

---

### Push Notifications

Users receive a notification on a trusted mobile device asking them to approve or deny the authentication request.

Benefits include:

- User convenience.
- Fast authentication.
- Reduced password fatigue.

Organizations should educate users to reject unexpected approval requests to prevent MFA fatigue attacks.

---

# Passwordless Authentication

Modern cloud environments increasingly support passwordless authentication.

Instead of passwords, users authenticate using:

- Biometrics.
- Hardware security keys.
- Trusted devices.
- Cryptographic certificates.

Benefits include:

- Reduced phishing risk.
- Elimination of password reuse.
- Improved user experience.
- Lower help desk costs related to password resets.

Passwordless authentication is becoming a key component of modern identity security.

---

# Adaptive Authentication

Adaptive authentication evaluates additional context before granting access.

Factors considered may include:

- User location.
- Device health.
- Time of access.
- Network type.
- User behavior.
- Risk score.

If unusual activity is detected, additional verification may be required before access is granted.

---

# Conditional Access

Many cloud platforms implement Conditional Access policies that combine authentication with contextual security controls.

Examples include:

- Require MFA when accessing sensitive applications.
- Block authentication from high-risk countries.
- Deny access from unmanaged devices.
- Require compliant devices before granting access.
- Restrict administrator access outside business hours.

Conditional Access strengthens authentication without unnecessarily impacting user productivity.

---

# Authentication Services in Major Cloud Platforms

### Microsoft Azure

Authentication capabilities include:

- Microsoft Entra ID.
- Microsoft Authenticator.
- Conditional Access.
- Passwordless Authentication.
- Windows Hello for Business.

---

### Amazon Web Services (AWS)

AWS provides:

- IAM authentication.
- Multi-Factor Authentication (MFA).
- IAM Identity Center.
- Temporary security credentials.
- Federation with external identity providers.

---

### Google Cloud Platform (GCP)

Google Cloud supports:

- Cloud Identity.
- Google Workspace authentication.
- Multi-Factor Authentication.
- Security keys.
- Identity federation.

These services enable centralized and secure authentication across cloud resources.

---

# Authentication within GRC

Authentication controls support Governance, Risk, and Compliance objectives.

### Governance

Organizations establish:

- Authentication standards.
- Password policies.
- MFA requirements.
- Identity verification procedures.
- Access approval processes.

---

### Risk Management

Strong authentication reduces risks including:

- Credential theft.
- Phishing attacks.
- Account compromise.
- Insider threats.
- Unauthorized remote access.
- Privilege escalation.

---

### Compliance

Authentication controls support compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-63 (Digital Identity Guidelines).
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Many regulations require Multi-Factor Authentication for privileged or remote access.

---

# Best Practices

Organizations should:

- Enable Multi-Factor Authentication for all users, especially privileged accounts.
- Use phishing-resistant authentication methods whenever possible.
- Replace SMS-based MFA with authenticator apps or hardware security keys.
- Implement passwordless authentication where appropriate.
- Enforce strong password policies.
- Deploy Conditional Access policies based on risk.
- Monitor authentication logs continuously.
- Educate users about phishing and MFA fatigue attacks.
- Regularly review authentication policies.
- Test authentication controls during security assessments.

Implementing these practices significantly strengthens cloud identity security.

---

📊 **Diagram Placeholder**

**Title:** Multi-Factor Authentication Process

**Diagram Description:**

```text
            User Login

                │

                ▼

      Username & Password

                │

                ▼

      Second Authentication

      (Authenticator App,
     Security Key, Biometric)

                │

        ┌───────┴────────┐
        │                │
        ▼                ▼

   Verification      Authentication
    Successful           Failed

        │                │
        ▼                ▼

 Access Granted    Access Denied
```

**Caption:**

*"Multi-Factor Authentication (MFA) strengthens identity verification by requiring users to present two or more independent authentication factors before access to cloud resources is granted."*

---

# Practical Example

A global financial services company protects access to its cloud environment using **Microsoft Entra ID** with **Conditional Access** policies. Employees authenticate using their username and password, followed by approval through the Microsoft Authenticator application. Administrators are additionally required to use FIDO2 hardware security keys when accessing privileged management portals.

If a login attempt originates from an unfamiliar country or an unmanaged device, Conditional Access automatically blocks the request or requires additional verification before granting access. Security teams monitor authentication logs through Microsoft Sentinel to identify suspicious sign-in attempts and respond to potential credential attacks. This approach significantly reduces the likelihood of account compromise while helping the organization meet ISO/IEC 27001, PCI DSS, and NIST security requirements.

---

# Key Takeaways

- Authentication verifies the identity of users, applications, and services before access to cloud resources is granted.
- Multi-Factor Authentication (MFA) significantly improves security by requiring two or more independent authentication factors.
- Modern authentication methods include authenticator applications, hardware security keys, biometrics, passwordless authentication, and adaptive authentication.
- Conditional Access enhances authentication by evaluating contextual information such as user location, device health, and risk level before granting access.
- Major cloud providers offer integrated authentication services that support centralized identity management and strong access protection.
- From a Governance, Risk, and Compliance (GRC) perspective, robust authentication controls reduce identity-related risks, strengthen organizational security, and support compliance with international standards and regulatory requirements.

- # Authentication and Multi-Factor Authentication (MFA)

Authentication is the process of verifying the identity of a user, application, or service before access to cloud resources is granted. It serves as the first line of defense in Identity and Access Management (IAM), ensuring that only legitimate identities can access organizational systems and data.

As cyberattacks increasingly target user credentials through phishing, password spraying, credential stuffing, and brute-force attacks, relying solely on usernames and passwords is no longer sufficient. Organizations now implement stronger authentication methods, particularly **Multi-Factor Authentication (MFA)**, to significantly reduce the risk of unauthorized access.

---

# Understanding Authentication

Authentication answers a simple but critical question:

> **"Are you really who you claim to be?"**

Before any access request is approved, the cloud platform verifies the identity using one or more authentication factors.

A typical authentication process is illustrated below.

```text
User Requests Access

          │

          ▼

Enter Credentials

          │

          ▼

Identity Verification

          │

          ▼

Authentication Successful

          │

          ▼

Authorization Process
```

Only after successful authentication does the system evaluate the user's permissions.

---

# Authentication Factors

Authentication methods are generally categorized into three factors.

## Something You Know

Knowledge factors rely on information known only to the user.

Examples include:

- Passwords.
- PINs.
- Passphrases.
- Security questions.

Although widely used, these methods are vulnerable to phishing and password reuse attacks.

---

## Something You Have

Possession factors require the user to possess a trusted device or object.

Examples include:

- Mobile authentication applications.
- Hardware security keys.
- Smart cards.
- One-Time Password (OTP) tokens.
- SMS verification codes.

This factor significantly increases account security because attackers must possess the physical device.

---

## Something You Are

Biometric factors verify unique physical characteristics.

Examples include:

- Fingerprint recognition.
- Facial recognition.
- Iris scanning.
- Voice recognition.

Biometric authentication improves convenience while providing strong identity verification.

---

# Single-Factor Authentication (SFA)

Single-Factor Authentication requires only one authentication factor, typically a username and password.

Example:

```text
Username

+

Password

↓

Access Granted
```

Although simple, SFA provides limited protection because compromised passwords often result in unauthorized access.

---

# Multi-Factor Authentication (MFA)

Multi-Factor Authentication requires two or more independent authentication factors before granting access.

Example:

```text
Username

+

Password

+

Mobile Authenticator Approval

↓

Access Granted
```

Even if an attacker steals a password, access is denied without the additional authentication factor.

---

# Benefits of Multi-Factor Authentication

Implementing MFA helps organizations:

- Reduce credential theft.
- Prevent unauthorized access.
- Minimize phishing risks.
- Protect privileged accounts.
- Secure remote access.
- Improve regulatory compliance.
- Strengthen Zero Trust implementations.
- Reduce successful account compromise.

MFA is considered one of the most effective and cost-efficient security controls available.

---

# Common MFA Methods

Organizations may deploy various MFA technologies.

### Authenticator Applications

Applications generate time-based one-time passwords (TOTPs) or require approval notifications.

Examples include:

- Microsoft Authenticator.
- Google Authenticator.
- Duo Mobile.

These applications are more secure than SMS-based authentication.

---

### Hardware Security Keys

Hardware security keys use cryptographic authentication.

Examples include:

- FIDO2 security keys.
- USB security keys.
- NFC authentication devices.

Hardware keys provide strong protection against phishing attacks.

---

### SMS Verification

Users receive a one-time verification code through text messaging.

Although widely supported, SMS authentication is vulnerable to SIM swapping and interception attacks.

Many organizations are gradually replacing SMS-based authentication with stronger methods.

---

### Push Notifications

Users receive a notification on a trusted mobile device asking them to approve or deny the authentication request.

Benefits include:

- User convenience.
- Fast authentication.
- Reduced password fatigue.

Organizations should educate users to reject unexpected approval requests to prevent MFA fatigue attacks.

---

# Passwordless Authentication

Modern cloud environments increasingly support passwordless authentication.

Instead of passwords, users authenticate using:

- Biometrics.
- Hardware security keys.
- Trusted devices.
- Cryptographic certificates.

Benefits include:

- Reduced phishing risk.
- Elimination of password reuse.
- Improved user experience.
- Lower help desk costs related to password resets.

Passwordless authentication is becoming a key component of modern identity security.

---

# Adaptive Authentication

Adaptive authentication evaluates additional context before granting access.

Factors considered may include:

- User location.
- Device health.
- Time of access.
- Network type.
- User behavior.
- Risk score.

If unusual activity is detected, additional verification may be required before access is granted.

---

# Conditional Access

Many cloud platforms implement Conditional Access policies that combine authentication with contextual security controls.

Examples include:

- Require MFA when accessing sensitive applications.
- Block authentication from high-risk countries.
- Deny access from unmanaged devices.
- Require compliant devices before granting access.
- Restrict administrator access outside business hours.

Conditional Access strengthens authentication without unnecessarily impacting user productivity.

---

# Authentication Services in Major Cloud Platforms

### Microsoft Azure

Authentication capabilities include:

- Microsoft Entra ID.
- Microsoft Authenticator.
- Conditional Access.
- Passwordless Authentication.
- Windows Hello for Business.

---

### Amazon Web Services (AWS)

AWS provides:

- IAM authentication.
- Multi-Factor Authentication (MFA).
- IAM Identity Center.
- Temporary security credentials.
- Federation with external identity providers.

---

### Google Cloud Platform (GCP)

Google Cloud supports:

- Cloud Identity.
- Google Workspace authentication.
- Multi-Factor Authentication.
- Security keys.
- Identity federation.

These services enable centralized and secure authentication across cloud resources.

---

# Authentication within GRC

Authentication controls support Governance, Risk, and Compliance objectives.

### Governance

Organizations establish:

- Authentication standards.
- Password policies.
- MFA requirements.
- Identity verification procedures.
- Access approval processes.

---

### Risk Management

Strong authentication reduces risks including:

- Credential theft.
- Phishing attacks.
- Account compromise.
- Insider threats.
- Unauthorized remote access.
- Privilege escalation.

---

### Compliance

Authentication controls support compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-63 (Digital Identity Guidelines).
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Many regulations require Multi-Factor Authentication for privileged or remote access.

---

# Best Practices

Organizations should:

- Enable Multi-Factor Authentication for all users, especially privileged accounts.
- Use phishing-resistant authentication methods whenever possible.
- Replace SMS-based MFA with authenticator apps or hardware security keys.
- Implement passwordless authentication where appropriate.
- Enforce strong password policies.
- Deploy Conditional Access policies based on risk.
- Monitor authentication logs continuously.
- Educate users about phishing and MFA fatigue attacks.
- Regularly review authentication policies.
- Test authentication controls during security assessments.

Implementing these practices significantly strengthens cloud identity security.

---

📊 **Diagram Placeholder**

**Title:** Multi-Factor Authentication Process

**Diagram Description:**

```text
            User Login

                │

                ▼

      Username & Password

                │

                ▼

      Second Authentication

      (Authenticator App,
     Security Key, Biometric)

                │

        ┌───────┴────────┐
        │                │
        ▼                ▼

   Verification      Authentication
    Successful           Failed

        │                │
        ▼                ▼

 Access Granted    Access Denied
```

**Caption:**

*"Multi-Factor Authentication (MFA) strengthens identity verification by requiring users to present two or more independent authentication factors before access to cloud resources is granted."*

---

# Practical Example

A global financial services company protects access to its cloud environment using **Microsoft Entra ID** with **Conditional Access** policies. Employees authenticate using their username and password, followed by approval through the Microsoft Authenticator application. Administrators are additionally required to use FIDO2 hardware security keys when accessing privileged management portals.

If a login attempt originates from an unfamiliar country or an unmanaged device, Conditional Access automatically blocks the request or requires additional verification before granting access. Security teams monitor authentication logs through Microsoft Sentinel to identify suspicious sign-in attempts and respond to potential credential attacks. This approach significantly reduces the likelihood of account compromise while helping the organization meet ISO/IEC 27001, PCI DSS, and NIST security requirements.

---

# Key Takeaways

- Authentication verifies the identity of users, applications, and services before access to cloud resources is granted.
- Multi-Factor Authentication (MFA) significantly improves security by requiring two or more independent authentication factors.
- Modern authentication methods include authenticator applications, hardware security keys, biometrics, passwordless authentication, and adaptive authentication.
- Conditional Access enhances authentication by evaluating contextual information such as user location, device health, and risk level before granting access.
- Major cloud providers offer integrated authentication services that support centralized identity management and strong access protection.
- From a Governance, Risk, and Compliance (GRC) perspective, robust authentication controls reduce identity-related risks, strengthen organizational security, and support compliance with international standards and regulatory requirements.

- # Authorization and Role-Based Access Control (RBAC)

After an identity has been successfully authenticated, the next step is determining what that identity is allowed to do. This process is known as **authorization**. While authentication verifies identity, authorization enforces security policies by granting only the permissions necessary to perform approved tasks.

Modern cloud platforms rely heavily on **Role-Based Access Control (RBAC)** to simplify permission management, reduce administrative complexity, and minimize the risk of excessive privileges. Proper authorization is a critical component of cloud security because many cloud breaches result from users or applications having more permissions than required.

---

# Understanding Authorization

Authorization is the process of determining whether an authenticated identity has permission to perform a requested action.

Authorization answers the question:

> **"What are you allowed to do?"**

Every request to access a cloud resource is evaluated against predefined access policies before permission is granted.

A simplified authorization process is shown below.

```text
Authenticated User

        │

        ▼

Access Request

        │

        ▼

Evaluate Roles & Policies

        │

        ▼

Permission Granted or Denied
```

Only identities with the appropriate permissions can perform the requested operation.

---

# Permissions

Permissions define the specific actions that an identity is allowed to perform.

Examples include:

- Read files.
- Create virtual machines.
- Delete storage accounts.
- Start or stop servers.
- Modify firewall rules.
- Access databases.
- View audit logs.
- Manage user accounts.

Each permission represents a specific capability within the cloud environment.

---

# What is a Role?

A role is a predefined collection of permissions assigned to a user, group, application, or service.

Instead of assigning permissions individually, administrators assign roles that contain the necessary permissions for a particular job function.

Examples of common roles include:

- Security Administrator.
- Network Administrator.
- Database Administrator.
- Backup Operator.
- Read-Only Auditor.
- Billing Administrator.
- Application Developer.

Using roles simplifies administration and reduces configuration errors.

---

# Role-Based Access Control (RBAC)

Role-Based Access Control (RBAC) is an authorization model in which permissions are assigned to roles, and roles are assigned to identities.

The relationship can be illustrated as follows.

```text
User

   │

Assigned Role

   │

Permissions

   │

Cloud Resources
```

This approach allows administrators to manage access consistently across large cloud environments.

---

# Benefits of RBAC

Implementing RBAC provides several advantages:

- Simplifies permission management.
- Reduces administrative overhead.
- Supports least privilege.
- Improves consistency.
- Reduces configuration errors.
- Enhances scalability.
- Simplifies audits.
- Improves regulatory compliance.

RBAC is considered the standard authorization model for enterprise cloud environments.

---

# Principle of Least Privilege

The **Principle of Least Privilege (PoLP)** states that users, applications, and services should receive only the permissions required to perform their assigned responsibilities.

For example:

| Role | Required Permissions |
|------|----------------------|
| Help Desk | Reset passwords |
| Database Administrator | Manage databases only |
| Network Administrator | Configure networking services |
| Auditor | Read-only access to logs |
| Developer | Deploy applications without managing IAM |

Applying least privilege reduces the organization's attack surface and limits the potential impact of compromised accounts.

---

# Privileged Accounts

Some identities require elevated permissions to manage cloud infrastructure.

Examples include:

- Global Administrators.
- Subscription Owners.
- Security Administrators.
- IAM Administrators.
- Cloud Architects.
- Platform Engineers.

Because privileged accounts have extensive access, they represent high-value targets for attackers.

Organizations should apply additional protections such as:

- Multi-Factor Authentication (MFA).
- Privileged Identity Management (PIM).
- Just-In-Time (JIT) access.
- Continuous monitoring.
- Session logging.

---

# Segregation of Duties (SoD)

Segregation of Duties prevents a single individual from controlling every stage of a sensitive business process.

Examples include separating responsibilities for:

- System administration and auditing.
- Software development and production deployment.
- Financial approval and payment processing.
- User creation and permission approval.
- Security monitoring and incident response.

Segregating responsibilities reduces fraud, errors, and insider threats.

---

# Role Assignment Scope

Cloud platforms allow roles to be assigned at different levels.

Examples include:

- Organization.
- Management Group.
- Subscription.
- Resource Group.
- Individual Resource.

Permissions assigned at higher levels are often inherited by lower-level resources unless restricted.

Properly selecting the assignment scope helps ensure users receive only the access they require.

---

# Built-in and Custom Roles

Cloud providers typically offer two types of roles.

## Built-in Roles

Built-in roles are predefined by the cloud provider.

Examples include:

- Owner.
- Contributor.
- Reader.
- Security Administrator.
- Network Contributor.

These roles cover common administrative responsibilities.

---

## Custom Roles

Organizations may create custom roles when built-in roles provide too many or too few permissions.

Custom roles allow administrators to:

- Limit excessive permissions.
- Support unique business functions.
- Meet regulatory requirements.
- Enforce organizational security policies.

Custom roles should be carefully reviewed and documented.

---

# Authorization in Major Cloud Platforms

### Microsoft Azure

Azure uses **Azure Role-Based Access Control (Azure RBAC)** to assign permissions to users, groups, managed identities, and service principals.

Examples of built-in roles include:

- Owner.
- Contributor.
- Reader.
- User Access Administrator.
- Security Administrator.

---

### Amazon Web Services (AWS)

AWS IAM uses policies attached to:

- Users.
- Groups.
- Roles.

Policies specify which actions are allowed or denied for AWS resources.

---

### Google Cloud Platform (GCP)

Google Cloud IAM assigns permissions through:

- Primitive Roles.
- Predefined Roles.
- Custom Roles.

Access can be granted at the organization, folder, project, or resource level.

Although terminology differs, the underlying authorization concepts are similar across providers.

---

# Authorization within GRC

Authorization plays a central role in Governance, Risk, and Compliance programs.

### Governance

Organizations establish:

- Access control policies.
- Role definitions.
- Approval workflows.
- Segregation of Duties requirements.
- Access review procedures.

---

### Risk Management

Proper authorization reduces risks associated with:

- Excessive privileges.
- Insider threats.
- Privilege escalation.
- Unauthorized access.
- Misconfigured permissions.
- Regulatory violations.

Regular access reviews help identify and remove unnecessary permissions before they become security risks.

---

### Compliance

Authorization controls support compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-53.
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Auditors commonly review role assignments, privileged accounts, approval records, and periodic access certifications.

---

# Best Practices

Organizations should:

- Implement Role-Based Access Control (RBAC) across all cloud environments.
- Apply the Principle of Least Privilege.
- Protect privileged accounts with Multi-Factor Authentication (MFA).
- Use Privileged Identity Management (PIM) where available.
- Implement Just-In-Time (JIT) administrative access.
- Perform regular access reviews.
- Remove unused roles and permissions.
- Separate administrative responsibilities through Segregation of Duties.
- Monitor privileged activities continuously.
- Document all authorization policies and role definitions.

Following these practices helps reduce identity-related risks while improving operational efficiency and compliance.

---

📊 **Diagram Placeholder**

**Title:** Role-Based Access Control (RBAC) Model

**Diagram Description:**

```text
             User

              │

      Assigned Role

              │

        Permissions

              │

      Cloud Resources

              │

      Access Granted
      or Access Denied
```

**Caption:**

*"Role-Based Access Control (RBAC) simplifies authorization by assigning permissions to roles rather than directly to users. This approach supports consistent access management, least privilege, and scalable cloud security."*

---

# Practical Example

A multinational engineering company hosts its cloud infrastructure in Microsoft Azure. Network engineers are assigned the **Network Contributor** role, allowing them to manage virtual networks and security groups without granting access to databases or billing information. Database administrators receive permissions limited to Azure SQL resources, while auditors are assigned a read-only role that allows them to review security logs and compliance reports without making configuration changes.

Highly privileged roles such as **Owner** and **User Access Administrator** are protected through Privileged Identity Management (PIM), requiring approval and Multi-Factor Authentication (MFA) before administrative privileges are activated. Quarterly access reviews ensure that employees retain only the permissions necessary for their current responsibilities, reducing security risks and supporting ISO/IEC 27001 compliance.

---

# Key Takeaways

- Authorization determines what authenticated users, applications, and services are permitted to do within a cloud environment.
- Role-Based Access Control (RBAC) simplifies permission management by assigning permissions to roles rather than directly to individual users.
- Applying the Principle of Least Privilege minimizes the attack surface by granting only the permissions required to perform authorized tasks.
- Privileged accounts require additional safeguards such as Multi-Factor Authentication (MFA), Privileged Identity Management (PIM), and continuous monitoring.
- Segregation of Duties (SoD) reduces fraud, insider threats, and operational errors by separating critical administrative responsibilities.
- From a Governance, Risk, and Compliance (GRC) perspective, strong authorization controls improve governance, reduce identity-related risks, and demonstrate compliance with internationally recognized security standards.

- # Identity Governance and Privileged Access Management

Managing identities extends beyond creating user accounts and assigning permissions. As organizations grow, they must establish governance processes that ensure identities are created, maintained, reviewed, and removed in a secure and consistent manner throughout their lifecycle.

Identity Governance and Administration (IGA) and Privileged Access Management (PAM) are two essential components of modern cloud security. Together, they help organizations control who has access to cloud resources, how privileged access is managed, and how access decisions support business, security, and compliance objectives.

---

# What is Identity Governance?

Identity Governance is the framework of policies, processes, and technologies used to manage identities and their access rights throughout their lifecycle.

Identity governance helps organizations answer questions such as:

- Who currently has access?
- Why was access granted?
- Who approved the access?
- Is the access still required?
- When should access be removed?

By answering these questions, organizations improve visibility, accountability, and security.

---

# Identity Lifecycle Management

Every identity follows a lifecycle from creation to removal.

A typical identity lifecycle includes:

```text
Create Identity

        │

        ▼

Assign Roles

        │

        ▼

Modify Access

        │

        ▼

Periodic Review

        │

        ▼

Suspend Access

        │

        ▼

Delete Identity
```

Managing identities throughout their lifecycle reduces the risk of orphaned accounts and unauthorized access.

---

# Joiner, Mover, and Leaver (JML) Process

One of the most important identity governance processes is the **Joiner, Mover, and Leaver (JML)** model.

### Joiner

When a new employee joins the organization:

- Create a user account.
- Assign appropriate roles.
- Enable Multi-Factor Authentication (MFA).
- Grant access based on job responsibilities.

---

### Mover

When an employee changes roles:

- Review current permissions.
- Remove unnecessary access.
- Assign new roles.
- Update approval records.

---

### Leaver

When an employee leaves the organization:

- Disable accounts immediately.
- Revoke privileged access.
- Remove authentication tokens.
- Archive audit records.
- Delete accounts according to organizational policy.

Prompt deprovisioning helps prevent unauthorized access by former employees.

---

# Access Reviews and Certification

User access should not remain permanent without validation.

Organizations perform periodic access reviews to verify that users still require their assigned permissions.

Access reviews typically evaluate:

- User accounts.
- Assigned roles.
- Privileged accounts.
- Service accounts.
- Shared resources.
- Third-party access.

Managers and resource owners should regularly certify that access remains appropriate.

---

# Privileged Access Management (PAM)

Privileged Access Management (PAM) focuses on protecting accounts with elevated permissions.

Examples of privileged accounts include:

- Global Administrators.
- Cloud Subscription Owners.
- Security Administrators.
- Database Administrators.
- Domain Administrators.
- Root accounts.

Because these accounts can make significant changes to cloud environments, they require stronger security controls than standard user accounts.

---

# Risks Associated with Privileged Accounts

Compromised privileged accounts can lead to serious consequences, including:

- Unauthorized system changes.
- Data breaches.
- Service disruption.
- Malware deployment.
- Privilege escalation.
- Complete cloud environment compromise.

For this reason, privileged identities should receive the highest level of protection.

---

# Just-In-Time (JIT) Access

Rather than granting permanent administrative privileges, organizations increasingly adopt **Just-In-Time (JIT)** access.

With JIT:

- Administrative access is requested only when needed.
- Access requires approval.
- Privileges are granted for a limited time.
- Permissions are automatically revoked after the approved period expires.

JIT significantly reduces the attack surface by minimizing standing privileges.

---

# Privileged Identity Management (PIM)

Many cloud providers offer Privileged Identity Management (PIM) services.

PIM enables organizations to:

- Grant temporary administrative access.
- Require approval before activating privileges.
- Enforce Multi-Factor Authentication (MFA).
- Record privileged activities.
- Review privileged assignments regularly.
- Automatically expire elevated permissions.

PIM supports the Principle of Least Privilege while maintaining operational flexibility.

---

# Monitoring Privileged Activities

Organizations should continuously monitor privileged operations.

Examples include:

- Role assignments.
- Permission changes.
- Administrative logins.
- Policy modifications.
- User creation.
- Account deletion.
- Security configuration changes.

Security Information and Event Management (SIEM) platforms can correlate these events to identify suspicious administrative activity.

---

# Identity Governance in Major Cloud Platforms

### Microsoft Azure

Microsoft provides identity governance capabilities through:

- Microsoft Entra ID Governance.
- Privileged Identity Management (PIM).
- Access Reviews.
- Entitlement Management.
- Lifecycle Workflows.

---

### Amazon Web Services (AWS)

AWS supports identity governance through:

- AWS IAM.
- IAM Identity Center.
- AWS Organizations.
- AWS CloudTrail.
- AWS Identity Federation.

---

### Google Cloud Platform (GCP)

Google Cloud offers:

- Cloud Identity.
- IAM Recommender.
- IAM Conditions.
- Organization Policies.
- Cloud Audit Logs.

These services help organizations manage identities, review access, and monitor privileged activities across cloud environments.

---

# Identity Governance within GRC

Identity governance directly supports Governance, Risk, and Compliance objectives.

### Governance

Organizations establish:

- Identity lifecycle policies.
- Access approval workflows.
- Role ownership.
- Access review schedules.
- Privileged access procedures.

---

### Risk Management

Identity governance reduces risks associated with:

- Excessive permissions.
- Orphaned accounts.
- Privilege misuse.
- Insider threats.
- Unauthorized administrative access.
- Regulatory non-compliance.

Regular governance activities improve visibility and reduce identity-related risks.

---

### Compliance

Identity governance supports compliance with:

- ISO/IEC 27001.
- ISO/IEC 27002.
- NIST Cybersecurity Framework (CSF).
- NIST SP 800-53.
- PCI DSS.
- HIPAA.
- GDPR.
- SOC 2.

Auditors commonly review access certifications, privileged account management, user lifecycle records, and administrative activity logs.

---

# Best Practices

Organizations should:

- Establish a formal identity governance program.
- Implement Joiner, Mover, and Leaver (JML) procedures.
- Perform regular user access reviews.
- Protect privileged accounts using Privileged Identity Management (PIM).
- Implement Just-In-Time (JIT) administrative access.
- Enable Multi-Factor Authentication (MFA) for privileged identities.
- Monitor privileged activities continuously.
- Remove inactive and orphaned accounts promptly.
- Automate identity lifecycle management where possible.
- Document governance policies and review them regularly.

Implementing these practices strengthens cloud security, improves operational efficiency, and supports long-term compliance.

---

📊 **Diagram Placeholder**

**Title:** Identity Governance and Privileged Access Lifecycle

**Diagram Description:**

```text
        Employee Lifecycle

               │

               ▼

     Create Identity (Joiner)

               │

               ▼

      Assign Roles & Access

               │

               ▼

     Periodic Access Review

               │

               ▼

    Temporary Privileged Access
      (JIT / PIM Activation)

               │

               ▼

      Remove Access (Leaver)

               │

               ▼

        Audit & Compliance
```

**Caption:**

*"Identity governance manages user access throughout the entire identity lifecycle, while Privileged Access Management ensures that elevated permissions are granted only when necessary, monitored continuously, and removed promptly to reduce security risk."*

---

# Practical Example

A multinational energy company uses **Microsoft Entra ID Governance** to automate identity lifecycle management. When new employees join the organization, user accounts are automatically created, assigned to department-specific groups, and protected with Multi-Factor Authentication (MFA). If an employee transfers to another department, previous permissions are automatically removed before new role assignments are applied.

Administrative roles such as **Global Administrator** are managed through **Privileged Identity Management (PIM)**. Administrators must request temporary access, obtain managerial approval, complete MFA verification, and activate privileges only for the duration of the approved maintenance task. Quarterly access reviews identify inactive accounts and excessive permissions, ensuring compliance with ISO/IEC 27001 and reducing the organization's exposure to identity-related threats.

---

# Key Takeaways

- Identity Governance ensures that identities and access rights are managed securely throughout the entire user lifecycle.
- The Joiner, Mover, and Leaver (JML) process helps organizations provision, modify, and remove access consistently and securely.
- Privileged Access Management (PAM) protects high-risk administrative accounts through stronger controls such as Just-In-Time (JIT) access and Privileged Identity Management (PIM).
- Regular access reviews, automated lifecycle management, and continuous monitoring reduce excessive permissions and improve accountability.
- Major cloud providers offer identity governance services that automate access management and strengthen privileged access security.
- From a Governance, Risk, and Compliance (GRC) perspective, identity governance and privileged access management improve operational control, reduce cyber risk, and provide strong evidence of compliance during internal and external audits.

- 
