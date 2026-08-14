# 18.8 Privacy and Data Protection Diagrams

### Part 1 – Data Lifecycle Diagram

Data is one of the most important assets managed by an organization. From a GRC perspective, understanding **where data comes from, how it is used, where it is stored, who can access it, how it is shared, and when it is deleted** is essential for managing privacy, security, compliance, and operational risk.

A **Data Lifecycle Diagram** provides a visual representation of the journey of data throughout its existence.

A simplified lifecycle is:

```text
                    DATA CREATION
                         ↓
                    COLLECTION
                         ↓
                     STORAGE
                         ↓
                USE / PROCESSING
                         ↓
                  SHARING / TRANSFER
                         ↓
                    ARCHIVING
                         ↓
                   DISPOSAL
                         ↓
                  DATA DESTRUCTION
```

The lifecycle should be considered a continuous governance process because new data may be created from existing data, and archived information may later return to active use.

---

# 1. What Is a Data Lifecycle?

The **data lifecycle** represents the stages through which data passes from its creation or collection until its final disposal.

A typical lifecycle includes:

```text
Creation
   ↓
Collection
   ↓
Classification
   ↓
Storage
   ↓
Processing
   ↓
Sharing
   ↓
Archiving
   ↓
Retention
   ↓
Disposal
```

Not every organization will use exactly the same stages. The lifecycle should reflect the organization's business processes, technology environment, regulatory obligations, and data-management practices.

---

# 2. Why Data Lifecycle Diagrams Matter in GRC

A Data Lifecycle Diagram helps GRC professionals answer questions such as:

```text
Where does the data originate?
        ↓
What type of data is it?
        ↓
Why is it collected?
        ↓
Where is it stored?
        ↓
Who can access it?
        ↓
How is it processed?
        ↓
Who receives it?
        ↓
How long is it retained?
        ↓
How is it destroyed?
```

These questions connect directly to:

```text
Privacy
Information Security
Compliance
Risk Management
Records Management
Data Governance
Third-Party Risk
Audit
```

---

# 3. Basic Data Lifecycle Model

A simple enterprise model is:

```text
                 DATA LIFECYCLE

                       ↓
                  CREATION
                       ↓
                  COLLECTION
                       ↓
                 CLASSIFICATION
                       ↓
                    STORAGE
                       ↓
                USE / PROCESSING
                       ↓
                SHARING / TRANSFER
                       ↓
                   ARCHIVING
                       ↓
                  RETENTION
                       ↓
                   DISPOSAL
```

Each stage introduces different risks and governance requirements.

---

# 4. Data Creation

Data may be created internally or generated automatically.

Examples include:

```text
Customer Records
Employee Records
Transaction Records
Application Logs
Security Logs
System-generated Data
AI-generated Data
Business Documents
Reports
Contracts
```

For example:

```text
Customer
   ↓
Creates Account
   ↓
Customer Data Generated
```

At this stage, organizations should understand:

```text
What data is being created?
Why is it needed?
Who owns it?
How should it be classified?
```

---

# 5. Data Collection

Data may be collected from different sources.

```text
                  DATA COLLECTION
                         ↓
       ┌─────────────────┼─────────────────┐
       ↓                 ↓                 ↓
   Customers          Employees        Systems
       ↓                 ↓                 ↓
       └─────────────────┼─────────────────┘
                         ↓
                    DATA STORE
```

Examples:

```text
Web Forms
Mobile Applications
Customer Service
Surveys
Sensors
APIs
Third Parties
Business Applications
```

From a privacy perspective, collection should be connected to a legitimate and defined business purpose.

---

# 6. Data Minimization

A key governance principle is to avoid collecting unnecessary information.

```text
Business Purpose
       ↓
Required Data
       ↓
Collection
```

Rather than:

```text
Business Purpose
       ↓
Collect Everything
       ↓
Store Everything
```

The first approach reduces:

```text
Privacy Risk
Security Exposure
Storage Cost
Compliance Burden
Breach Impact
```

---

# 7. Data Classification

Once data is collected or created, it should be appropriately classified.

A simplified model is:

```text
                    DATA
                      ↓
               CLASSIFICATION
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
    Public       Internal       Confidential
                                      ↓
                                  Restricted
```

Organizations may use different classification schemes.

For example:

```text
Public
Internal
Confidential
Highly Confidential
Restricted
```

Classification determines how data should subsequently be protected.

---

# 8. Data Classification and Controls

Classification should influence security controls.

```text
DATA CLASSIFICATION
        ↓
   Risk Level
        ↓
Security Requirements
        ↓
Controls
```

For example:

```text
Restricted Data
      ↓
Strong Encryption
      ↓
Strict Access Control
      ↓
Enhanced Monitoring
      ↓
Detailed Audit Logging
```

This creates a direct connection between data governance and cybersecurity.

---

# 9. Personal Data

Privacy governance requires special attention to personal data.

Examples may include:

```text
Name
Email Address
Telephone Number
Identification Information
Location Information
Online Identifiers
Account Information
Employment Information
```

Depending on the jurisdiction and circumstances, some categories of data may require additional protection.

The lifecycle therefore needs to identify where personal data enters and moves through the organization.

---

# 10. Sensitive Data

Some information may require stronger controls because of its sensitivity.

A simplified hierarchy could be:

```text
                DATA
                  ↓
        ┌─────────┴─────────┐
        ↓                   ↓
   Non-sensitive          Sensitive
                            ↓
                     Highly Sensitive
```

Examples can include:

```text
Financial Information
Authentication Information
Health Information
Identity Documents
Confidential Business Information
```

The exact classification depends on organizational policy and applicable law.

---

# 11. Data Storage

After collection, data is usually stored somewhere.

```text
                    DATA
                      ↓
                    STORAGE
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
   Database          Cloud         File System
       ↓              ↓              ↓
       └──────────────┼──────────────┘
                      ↓
               Data Management
```

Storage environments may include:

```text
On-Premises Servers
Cloud Platforms
SaaS Applications
Databases
Data Lakes
Backup Systems
Employee Devices
Mobile Devices
```

Each environment introduces different risks.

---

# 12. Data Storage Risks

Common risks include:

```text
Unauthorized Access
Data Leakage
Misconfiguration
Loss
Corruption
Ransomware
Insufficient Encryption
Excessive Retention
Third-Party Exposure
```

Therefore:

```text
DATA STORAGE
      ↓
Risk Assessment
      ↓
Security Controls
```

---

# 13. Data Encryption

Encryption can be applied at different lifecycle stages.

```text
Data
 ↓
Encryption
 ↓
Storage
```

and:

```text
Data
 ↓
Encryption
 ↓
Transmission
```

A simplified model is:

```text
                DATA
                  ↓
        ┌─────────┴─────────┐
        ↓                   ↓
   At Rest             In Transit
        ↓                   ↓
   Encryption           Encryption
```

Encryption requirements should be based on organizational risk, data classification, and applicable requirements.

---

# 14. Data Access

Data must be accessed by authorized users and systems.

```text
                    DATA
                      ↓
                 ACCESS REQUEST
                      ↓
                Authentication
                      ↓
                 Authorization
                      ↓
                 Data Access
                      ↓
                    Logging
```

The principle of **least privilege** is particularly important.

Users should generally receive only the access required to perform their responsibilities.

---

# 15. Data Use and Processing

Data may be processed for business purposes.

Examples include:

```text
Customer Service
Billing
Analytics
Marketing
Fraud Detection
Risk Management
Reporting
AI Processing
Business Operations
```

The lifecycle therefore becomes:

```text
DATA
 ↓
STORAGE
 ↓
PROCESSING
 ↓
BUSINESS PURPOSE
```

For privacy governance, organizations should understand why personal data is being processed and whether that processing is permitted under applicable requirements.

---

# 16. Data Processing Flow

A simplified processing model is:

```text
              DATA
                ↓
          Processing Input
                ↓
          Business Process
                ↓
         Processing Activity
                ↓
          Processed Data
                ↓
       Business / User Outcome
```

For example:

```text
Customer Information
        ↓
Billing System
        ↓
Invoice Calculation
        ↓
Customer Invoice
```

---

# 17. Data Sharing

Data may be shared internally or externally.

```text
                    DATA
                      ↓
                  DATA SHARING
                      ↓
        ┌─────────────┼─────────────┐
        ↓             ↓             ↓
     Internal      Supplier      Customer
        ↓             ↓             ↓
     Business      Service       Service
       Unit         Provider
```

External sharing can introduce additional risks.

Examples include:

```text
Cloud Providers
Payment Processors
Analytics Providers
Marketing Providers
Consultants
Business Partners
Government Authorities
```

---

# 18. Third-Party Data Processing

A third party may process data on behalf of the organization.

```text
Organization
      ↓
Personal / Business Data
      ↓
Third-Party Provider
      ↓
Processing
      ↓
Service Outcome
```

From a GRC perspective, this creates a need for:

```text
Vendor Due Diligence
Contractual Controls
Security Requirements
Privacy Requirements
Monitoring
Audit Rights
Incident Notification
Offboarding
```

---

# 19. International Data Transfers

Data may cross geographic or jurisdictional boundaries.

```text
                DATA
                  ↓
             TRANSFER
                  ↓
       ┌──────────┴──────────┐
       ↓                     ↓
   Same Country        Other Country
                             ↓
                     Transfer Assessment
                             ↓
                     Applicable Safeguards
```

International transfers can introduce additional legal, regulatory, contractual, and privacy considerations.

For multinational organizations, the Data Lifecycle Diagram should therefore identify relevant geographic locations.

---

# 20. Data Location

A complete lifecycle should identify where data resides.

```text
Data
 ↓
Location
 ↓
┌────────────┬─────────────┬─────────────┐
↓            ↓             ↓
EU           US            Other Region
↓            ↓             ↓
Regulatory   Regulatory    Regulatory
Context      Context       Context
```

This becomes particularly important when organizations operate across multiple jurisdictions.

---

# 21. Data Retention

Organizations should establish how long data should be retained.

```text
Business Need
      ↓
Legal Requirement
      ↓
Regulatory Requirement
      ↓
Contractual Requirement
      ↓
Retention Period
```

The result can be represented as:

```text
DATA
 ↓
ACTIVE USE
 ↓
RETENTION PERIOD
 ↓
ARCHIVE OR DISPOSAL
```

Retention should be justified rather than indefinite by default.

---

# 22. Excessive Retention Risk

Keeping data longer than necessary can increase risk.

```text
Longer Retention
      ↓
More Data Stored
      ↓
Larger Attack Surface
      ↓
Greater Breach Exposure
      ↓
Higher Privacy Risk
```

Therefore:

```text
Need Data?
   ↓
Yes → Retain
   ↓
No → Dispose
```

subject to applicable legal, regulatory, contractual, and business requirements.

---

# 23. Data Archiving

Some information may no longer be actively used but still needs to be retained.

```text
ACTIVE DATA
     ↓
No Longer Actively Used
     ↓
ARCHIVE
     ↓
Retention Period
     ↓
DISPOSAL
```

Archived information should still have appropriate:

```text
Access Controls
Security
Integrity Protection
Retention Management
Monitoring
```

---

# 24. Data Disposal

The final stage is secure disposal.

```text
Retention Period Ends
        ↓
Disposal Decision
        ↓
Secure Disposal
        ↓
Verification
        ↓
Evidence / Record
```

Disposal methods depend on the type of data and storage medium.

Examples include:

```text
Secure Deletion
Media Destruction
Device Destruction
Cryptographic Erasure
Secure Disposal Services
```

---

# 25. Data Destruction Evidence

From an audit perspective, organizations should be able to demonstrate that disposal occurred.

```text
Disposal Requirement
        ↓
Disposal Activity
        ↓
Evidence
        ↓
Verification
```

Possible evidence includes:

```text
Deletion Logs
Destruction Certificates
System Records
Asset Disposal Records
Supplier Confirmation
```

This creates accountability at the final stage of the lifecycle.

---

# 26. Complete Data Lifecycle

A more comprehensive model is:

```text
                         DATA
                           ↓
                       CREATION
                           ↓
                       COLLECTION
                           ↓
                     CLASSIFICATION
                           ↓
                        STORAGE
                           ↓
                    USE / PROCESSING
                           ↓
                    ACCESS / SHARING
                           ↓
                 TRANSFER / DISTRIBUTION
                           ↓
                       ARCHIVING
                           ↓
                      RETENTION
                           ↓
                       DISPOSAL
                           ↓
                     DESTRUCTION
```

Governance, security, and privacy controls should operate across the entire lifecycle.

---

# 27. Cross-Lifecycle Controls

Controls should not exist only at one stage.

```text
                DATA LIFECYCLE
                     ↓
 ┌─────────────────────────────────────────┐
 │                                         │
 │  Governance                             │
 │  Privacy                                │
 │  Security                               │
 │  Access Control                         │
 │  Encryption                             │
 │  Monitoring                             │
 │  Audit                                  │
 │  Risk Management                        │
 │                                         │
 └─────────────────────────────────────────┘
```

This represents an important GRC principle:

> **Data protection is a lifecycle responsibility, not a single point-in-time control.**

---

# 28. Privacy Controls Across the Lifecycle

Privacy controls can be mapped to different stages.

| Lifecycle Stage | Example Privacy Considerations         |
| --------------- | -------------------------------------- |
| Collection      | Purpose, transparency, minimization    |
| Classification  | Personal/sensitive data identification |
| Storage         | Protection and access                  |
| Processing      | Permitted purpose and appropriate use  |
| Sharing         | Recipients and contractual safeguards  |
| Transfer        | Geographic and legal requirements      |
| Retention       | Retention period                       |
| Disposal        | Secure deletion                        |

This mapping helps GRC teams identify where privacy controls are required.

---

# 29. Security Controls Across the Lifecycle

Security controls can similarly be mapped:

```text
Collection
    ↓
Authentication / Secure Input
    ↓
Storage
    ↓
Encryption / Access Control
    ↓
Processing
    ↓
Monitoring / Integrity
    ↓
Sharing
    ↓
Secure Transfer
    ↓
Archiving
    ↓
Access Restriction
    ↓
Disposal
    ↓
Secure Destruction
```

This creates a defense-in-depth approach to data protection.

---

# 30. Data Lifecycle and Risk

Every lifecycle stage can introduce risk.

```text
Collection → Collection Risk
Storage → Storage Risk
Processing → Processing Risk
Sharing → Third-Party Risk
Transfer → Transfer Risk
Retention → Retention Risk
Disposal → Disposal Risk
```

A complete data risk model therefore looks like:

```text
DATA LIFECYCLE
      ↓
Risk Identification
      ↓
Risk Assessment
      ↓
Risk Treatment
      ↓
Control Implementation
      ↓
Monitoring
```

---

# 31. Data Lifecycle and GRC

The Data Lifecycle Diagram can connect multiple GRC disciplines.

```text
                     DATA
                      ↓
              DATA LIFECYCLE
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
    Privacy         Security       Compliance
       ↓              ↓              ↓
       └──────────────┼──────────────┘
                      ↓
                    GRC
```

This provides a common visual model for different functions.

---

# 32. Data Lifecycle and Risk Register

Data-related risks can be linked to specific lifecycle stages.

```text
Lifecycle Stage
       ↓
Risk
       ↓
Risk Register
       ↓
Risk Owner
       ↓
Treatment
       ↓
Control
       ↓
Evidence
```

For example:

```text
Stage:
Third-Party Sharing

Risk:
Unauthorized disclosure

Owner:
Data Protection / Business Owner

Treatment:
Contractual and technical controls
```

---

# 33. Data Lifecycle and Data Inventory

A data inventory can document the information flowing through the lifecycle.

```text
Data Inventory
      ↓
Data Type
      ↓
Data Owner
      ↓
Source
      ↓
Processing Activity
      ↓
Storage Location
      ↓
Recipients
      ↓
Retention
      ↓
Disposal
```

This is particularly useful for privacy and data governance programs.

---

# 34. Data Lifecycle and Data Mapping

A data map can visualize where information moves.

```text
Customer
   ↓
Website
   ↓
CRM
   ↓
Cloud Database
   ↓
Analytics Platform
   ↓
Third-Party Provider
   ↓
Archive
   ↓
Deletion
```

This provides visibility into the actual flow of information rather than only documenting individual systems.

---

# 35. Data Lifecycle and Privacy Risk Assessment

The lifecycle provides important input to privacy risk assessment.

```text
Data Lifecycle
      ↓
Processing Activities
      ↓
Potential Privacy Risks
      ↓
Risk Assessment
      ↓
Mitigation Measures
```

For example:

```text
Collection
   ↓
Excessive Personal Data
   ↓
Privacy Risk
   ↓
Data Minimization
```

---

# 36. Data Lifecycle and Data Breach

A breach can occur at almost any lifecycle stage.

```text
Collection
    ↓
Storage
    ↓
Processing
    ↓
Sharing
    ↓
Transfer
    ↓
Archiving
```

Therefore, incident response should consider the entire lifecycle.

A simplified model is:

```text
Data Exposure
      ↓
Detection
      ↓
Containment
      ↓
Investigation
      ↓
Impact Assessment
      ↓
Notification / Reporting
      ↓
Remediation
```

---

# 37. Data Lifecycle and Third-Party Risk

Third parties may participate at multiple points.

```text
Collection
     ↓
Cloud Storage
     ↓
Processing
     ↓
Analytics
     ↓
Customer Support
     ↓
Archiving
```

Therefore, third-party risk should be evaluated based on the specific data lifecycle activities performed by each supplier.

---

# 38. Data Lifecycle and Cloud

Cloud adoption can significantly change the lifecycle.

```text
Traditional Environment
        ↓
On-Premises Storage
        ↓
Internal Processing
```

versus:

```text
Cloud Environment
        ↓
SaaS
IaaS
PaaS
Cloud Storage
Cloud Analytics
        ↓
Multiple Providers
```

This increases the importance of:

```text
Cloud Configuration
Identity Management
Encryption
Data Location
Third-Party Risk
Logging
Contractual Controls
```

---

# 39. Data Lifecycle and AI

AI systems introduce additional data lifecycle considerations.

```text
Data Collection
       ↓
Data Preparation
       ↓
Training / Processing
       ↓
AI Model
       ↓
Inference
       ↓
Output
       ↓
Storage / Retention
```

GRC teams may need to consider:

```text
Data Quality
Privacy
Security
Intellectual Property
Access
Model Inputs
Model Outputs
Third-Party AI Providers
Retention
```

The data lifecycle therefore becomes increasingly important as organizations adopt AI.

---

# 40. Data Lifecycle and Regulatory Compliance

Different regulatory obligations may apply at different lifecycle stages.

```text
Collection
    ↓
Privacy Requirements

Processing
    ↓
Purpose / Lawfulness Requirements

Sharing
    ↓
Third-Party / Contractual Requirements

Transfer
    ↓
Cross-Border Requirements

Retention
    ↓
Retention Requirements

Disposal
    ↓
Deletion / Destruction Requirements
```

The organization should map applicable obligations to the relevant lifecycle stages.

---

# 41. Data Lifecycle Control Matrix

A GRC team can build a lifecycle control matrix:

| Lifecycle Stage | Risk                  | Control             | Evidence            |
| --------------- | --------------------- | ------------------- | ------------------- |
| Collection      | Excessive collection  | Data minimization   | Collection form     |
| Storage         | Unauthorized access   | Access control      | Access report       |
| Processing      | Unauthorized use      | Processing controls | Processing record   |
| Sharing         | Third-party exposure  | Supplier controls   | Contract            |
| Transfer        | Unauthorized transfer | Transfer safeguards | Transfer assessment |
| Retention       | Excessive retention   | Retention policy    | Retention report    |
| Disposal        | Data recovery         | Secure deletion     | Deletion evidence   |

This creates direct traceability between the data lifecycle and GRC controls.

---

# 42. Executive Data Lifecycle View

For executives, the model can be simplified:

```text
CREATE
  ↓
COLLECT
  ↓
USE
  ↓
SHARE
  ↓
STORE
  ↓
RETAIN
  ↓
DELETE
```

At every stage:

```text
Is the data needed?
Is it protected?
Is access appropriate?
Is the processing permitted?
Is the risk acceptable?
```

---

# 43. Complete GRC Data Lifecycle Model

An integrated GRC model can be represented as:

```text
                         BUSINESS
                           NEED
                            ↓
                      DATA CREATION
                            ↓
                      DATA COLLECTION
                            ↓
                     DATA CLASSIFICATION
                            ↓
                         STORAGE
                            ↓
                    ACCESS / PROCESSING
                            ↓
                     SHARING / TRANSFER
                            ↓
                        RETENTION
                            ↓
                        ARCHIVING
                            ↓
                         DISPOSAL
                            ↓
                      DESTRUCTION
```

Across every stage:

```text
        ┌─────────────────────────────────────┐
        │                                     │
        │ Privacy                             │
        │ Security                            │
        │ Risk Management                     │
        │ Compliance                          │
        │ Governance                          │
        │ Monitoring                          │
        │ Audit / Assurance                   │
        │                                     │
        └─────────────────────────────────────┘
```

---

# 44. Key GRC Principles

The Data Lifecycle Diagram reinforces several important principles:

```text
1. Know your data.
2. Know where your data comes from.
3. Know why you collect it.
4. Know where it is stored.
5. Know who can access it.
6. Know how it is processed.
7. Know who it is shared with.
8. Know where it is transferred.
9. Know how long it is retained.
10. Know how it is securely disposed of.
```

These principles provide the foundation for effective data governance and privacy management.

---

# 45. Final Integrated Model

The complete concept can be summarized as:

```text
                         DATA
                           ↓
                      COLLECTION
                           ↓
                    CLASSIFICATION
                           ↓
                        STORAGE
                           ↓
                   ACCESS / PROCESSING
                           ↓
                    SHARING / TRANSFER
                           ↓
                       ARCHIVING
                           ↓
                       RETENTION
                           ↓
                        DISPOSAL
                           ↓
                      DESTRUCTION
                           ↓
                     EVIDENCE / AUDIT
```

With governance operating throughout:

```text
                 ┌───────────────────────┐
                 │       GOVERNANCE      │
                 │       PRIVACY         │
                 │       SECURITY        │
                 │       RISK            │
                 │       COMPLIANCE      │
                 │       AUDIT           │
                 └───────────────────────┘
                           ↓
                  DATA LIFECYCLE
                           ↓
                 CONTROLLED DATA
                           ↓
                REDUCED DATA RISK
```

The key GRC principle is:

> **Data protection must be managed across the entire data lifecycle—from creation and collection through processing, sharing, retention, and secure disposal—because privacy, security, compliance, and operational risks can arise at every stage.**

A well-designed Data Lifecycle Diagram therefore provides GRC professionals with a common visual language for connecting **data governance, privacy, cybersecurity, regulatory compliance, third-party risk, control management, and audit evidence**.

# 18.8 Privacy and Data Protection Diagrams

### Part 2 – Personal Data Processing Flow

A **Personal Data Processing Flow** illustrates how personal data moves through an organization from collection to its intended use, storage, sharing, retention, and eventual deletion.

From a GRC perspective, the objective is not simply to show where data travels. The diagram should also help answer:

```text
What personal data is being processed?
        ↓
Why is it being processed?
        ↓
Who processes it?
        ↓
Where is it processed?
        ↓
Who receives it?
        ↓
How is it protected?
        ↓
How long is it retained?
        ↓
What happens when processing ends?
```

A simplified flow is:

```text
DATA SUBJECT
     ↓
DATA COLLECTION
     ↓
PURPOSE IDENTIFICATION
     ↓
PROCESSING ACTIVITY
     ↓
STORAGE
     ↓
INTERNAL / EXTERNAL SHARING
     ↓
RETENTION
     ↓
DELETION
```

---

# 1. What Is Personal Data Processing?

Personal data processing refers broadly to operations performed on information relating to an identified or identifiable person.

Processing can include:

```text
Collection
Recording
Organization
Storage
Access
Retrieval
Use
Analysis
Sharing
Transfer
Modification
Archiving
Deletion
```

Therefore, processing is much broader than simply "using" personal data.

A GRC professional should think of processing as the **complete set of activities performed on personal data**.

---

# 2. Basic Personal Data Processing Flow

A simple organizational model is:

```text
                 DATA SUBJECT
                      ↓
               PERSONAL DATA
                      ↓
                 COLLECTION
                      ↓
                  PROCESSING
                      ↓
            ┌─────────┴─────────┐
            ↓                   ↓
       INTERNAL USE        EXTERNAL SHARING
            ↓                   ↓
            └─────────┬─────────┘
                      ↓
                   STORAGE
                      ↓
                  RETENTION
                      ↓
                   DELETION
```

The actual flow may contain many additional processing activities.

---

# 3. Data Subject

The process generally begins with a **data subject** whose personal data is involved.

Examples include:

```text
Customer
Employee
Applicant
Supplier Contact
Website Visitor
Patient
Student
Citizen
User
```

For example:

```text
CUSTOMER
   ↓
Provides Information
   ↓
Organization Collects Data
```

The organization should understand what information is obtained from the individual and why.

---

# 4. Personal Data Collection

Collection may occur through many channels.

```text
                    COLLECTION
                         ↓
       ┌─────────────────┼─────────────────┐
       ↓                 ↓                 ↓
    Website           Mobile App        Call Center
       ↓                 ↓                 ↓
       └─────────────────┼─────────────────┘
                         ↓
                   PERSONAL DATA
```

Other collection channels may include:

```text
Email
Paper Forms
Contracts
Cookies
Applications
APIs
Physical Locations
Third-Party Sources
Connected Devices
```

Each collection channel can create different privacy and security risks.

---

# 5. Purpose of Processing

An important part of the processing flow is identifying the purpose.

```text
PERSONAL DATA
      ↓
WHY IS IT NEEDED?
      ↓
DEFINED PURPOSE
      ↓
PROCESSING ACTIVITY
```

Examples:

```text
Customer Service
Billing
Account Management
Fraud Prevention
Security Monitoring
Recruitment
Payroll
Marketing
Regulatory Reporting
```

The organization should be able to explain the business purpose associated with the processing.

---

# 6. Purpose Limitation

Personal data should generally be processed consistently with the defined purpose and applicable requirements.

A simplified model is:

```text
DEFINED PURPOSE
       ↓
REQUIRED DATA
       ↓
PROCESSING ACTIVITY
       ↓
EXPECTED OUTCOME
```

A problematic model would be:

```text
COLLECT DATA
      ↓
STORE DATA
      ↓
USE FOR ANY FUTURE PURPOSE
```

Purpose management therefore becomes an important privacy governance activity.

---

# 7. Data Minimization

The processing flow should also consider whether all collected data is actually necessary.

```text
BUSINESS PURPOSE
       ↓
DATA REQUIREMENT
       ↓
MINIMUM NECESSARY DATA
       ↓
COLLECTION
       ↓
PROCESSING
```

For example:

```text
Purpose:
Deliver a product

Required:
Name
Delivery Address
Contact Information

Unnecessary:
Unrelated Personal Information
```

Data minimization reduces the amount of information exposed if a security incident occurs.

---

# 8. Processing Activity

After collection, personal data enters a processing activity.

```text
PERSONAL DATA
      ↓
PROCESSING SYSTEM
      ↓
BUSINESS PROCESS
      ↓
PROCESSING OUTPUT
```

Examples:

```text
CRM Processing
Payroll Processing
Billing Processing
Customer Support Processing
Marketing Processing
Fraud Detection
Analytics
Identity Verification
```

Each processing activity should be understood and governed.

---

# 9. Processing System

Personal data may pass through multiple systems.

```text
             PERSONAL DATA
                    ↓
              APPLICATION
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
       CRM        Database    Analytics
        ↓           ↓           ↓
        └───────────┼───────────┘
                    ↓
               Business Use
```

This creates a need for accurate data mapping.

---

# 10. Data Flow Between Systems

A more detailed processing flow may look like:

```text
Customer
   ↓
Website
   ↓
API Gateway
   ↓
CRM
   ↓
Customer Database
   ↓
Analytics Platform
   ↓
Reporting System
```

Each connection represents a potential processing or transfer point.

GRC teams should understand:

```text
Source
Destination
Data Type
Purpose
Transfer Method
Security Controls
Data Owner
Retention
```

---

# 11. Internal Data Sharing

Personal data may be shared between internal business units.

```text
              CUSTOMER
                  ↓
             CRM SYSTEM
                  ↓
        ┌─────────┼─────────┐
        ↓         ↓         ↓
      Sales     Billing   Support
        ↓         ↓         ↓
        └─────────┼─────────┘
                  ↓
            Customer Service
```

Internal sharing should still be controlled.

Not every employee or department should automatically have access to all personal data.

---

# 12. Access Control

Access should be based on business need and appropriate authorization.

```text
USER
  ↓
AUTHENTICATION
  ↓
AUTHORIZATION
  ↓
ACCESS DECISION
  ↓
PERSONAL DATA
  ↓
LOGGING
```

Controls may include:

```text
Identity Management
Role-Based Access
Least Privilege
Privileged Access Management
Multi-Factor Authentication
Access Reviews
Logging
```

---

# 13. External Data Sharing

Organizations may share personal data with external parties.

```text
                 ORGANIZATION
                       ↓
                 PERSONAL DATA
                       ↓
              EXTERNAL RECIPIENT
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
      Supplier       Partner       Authority
```

Before sharing data, the organization should understand:

```text
Who receives it?
Why do they need it?
What data is shared?
How is it protected?
Where is it processed?
How long is it retained?
```

---

# 14. Third-Party Processing

A service provider may process personal data on behalf of the organization.

```text
DATA SUBJECT
     ↓
ORGANIZATION
     ↓
PERSONAL DATA
     ↓
SERVICE PROVIDER
     ↓
PROCESSING
     ↓
SERVICE OUTCOME
```

Examples:

```text
Cloud Provider
Payroll Provider
CRM Provider
Marketing Platform
Payment Processor
Customer Support Provider
Analytics Provider
```

This creates third-party privacy and security risk.

---

# 15. Processor Governance

Third-party processing should be governed through appropriate mechanisms.

```text
THIRD-PARTY
     ↓
DUE DILIGENCE
     ↓
CONTRACTUAL REQUIREMENTS
     ↓
SECURITY / PRIVACY CONTROLS
     ↓
ONGOING MONITORING
     ↓
OFFBOARDING
```

Evidence may include:

```text
Contracts
Security Assessments
Privacy Assessments
Audit Reports
Certifications
Processing Records
Incident Reports
```

---

# 16. Data Transfer

Personal data may move between systems or organizations.

```text
SOURCE
  ↓
TRANSFER
  ↓
DESTINATION
```

The transfer itself can introduce risks.

Examples:

```text
API
HTTPS
File Transfer
Email
Cloud Synchronization
Database Replication
Application Integration
```

The transfer mechanism should provide appropriate protection.

---

# 17. Cross-Border Transfer

Personal data may cross national or regional boundaries.

```text
             DATA SOURCE
                  ↓
            TRANSFER
                  ↓
        ┌─────────┴─────────┐
        ↓                   ↓
   Same Jurisdiction   Other Jurisdiction
                            ↓
                    Transfer Assessment
                            ↓
                       Safeguards
                            ↓
                       Processing
```

For multinational organizations, the processing flow should identify relevant geographic locations.

---

# 18. Data Location

A personal data processing flow should ideally identify where information is processed.

```text
PERSONAL DATA
      ↓
┌─────┼──────┬─────────┐
↓     ↓      ↓         ↓
EU    US    Asia      Other
↓     ↓      ↓         ↓
Regulatory / Contractual Context
```

Data location can influence:

```text
Privacy Requirements
Security Requirements
Transfer Requirements
Contractual Requirements
Regulatory Exposure
```

---

# 19. Storage During Processing

Personal data may be stored temporarily or permanently during processing.

```text
COLLECTION
     ↓
PROCESSING
     ↓
TEMPORARY STORAGE
     ↓
PROCESSING OUTPUT
     ↓
LONG-TERM STORAGE
```

Storage controls may include:

```text
Encryption
Access Control
Backup
Monitoring
Logging
Data Classification
Retention Controls
```

---

# 20. Data Retention

The processing flow should include a defined retention approach.

```text
PROCESSING PURPOSE
       ↓
RETENTION REQUIREMENT
       ↓
RETENTION PERIOD
       ↓
ARCHIVE OR DELETE
```

Retention may depend on:

```text
Legal Requirements
Regulatory Requirements
Contractual Requirements
Business Requirements
Litigation Requirements
Records Management
```

The organization should avoid keeping personal data indefinitely without an appropriate justification.

---

# 21. Data Deletion

When the applicable retention period ends:

```text
RETENTION PERIOD ENDS
          ↓
DELETE / DISPOSE
          ↓
VERIFICATION
          ↓
EVIDENCE
```

Deletion may need to occur across multiple systems.

For example:

```text
CRM
 ↓
Database
 ↓
Backup
 ↓
Analytics
 ↓
Third-Party Provider
```

This is one reason why accurate data mapping is important.

---

# 22. Data Subject Rights

Privacy processes may also require mechanisms for responding to requests from individuals.

A simplified model is:

```text
DATA SUBJECT
      ↓
REQUEST
      ↓
PRIVACY TEAM
      ↓
IDENTITY VERIFICATION
      ↓
DATA DISCOVERY
      ↓
SYSTEM REVIEW
      ↓
RESPONSE / ACTION
```

Depending on applicable law, requests may involve matters such as:

```text
Access
Correction
Deletion
Restriction
Objection
Portability
```

The specific rights and applicable conditions depend on the jurisdiction.

---

# 23. Data Discovery

Responding to privacy requests requires knowing where personal data exists.

```text
REQUEST
   ↓
DATA DISCOVERY
   ↓
┌─────────┬─────────┬─────────┬─────────┐
↓         ↓         ↓         ↓
CRM     Database   Email    Archive
↓         ↓         ↓         ↓
└─────────┴─────────┴─────────┴─────────┘
              ↓
        Personal Data Set
```

This demonstrates the relationship between data mapping and privacy operations.

---

# 24. Privacy and Security Controls

Controls should operate throughout the processing flow.

```text
COLLECTION
     ↓
Privacy Notice / Minimization
     ↓
PROCESSING
     ↓
Purpose / Access Controls
     ↓
STORAGE
     ↓
Encryption / Access Control
     ↓
SHARING
     ↓
Third-Party Controls
     ↓
TRANSFER
     ↓
Transfer Safeguards
     ↓
RETENTION
     ↓
Retention Controls
     ↓
DELETION
     ↓
Secure Disposal
```

---

# 25. Processing Risk

Each processing activity can introduce risk.

```text
PROCESSING ACTIVITY
        ↓
DATA
        ↓
THREATS
        ↓
VULNERABILITIES
        ↓
POTENTIAL IMPACT
        ↓
PRIVACY / SECURITY RISK
```

Examples:

```text
Unauthorized Access
Excessive Collection
Unauthorized Disclosure
Incorrect Data
Unlawful Processing
Excessive Retention
Third-Party Exposure
Cross-Border Risk
```

---

# 26. Privacy Risk Assessment

A privacy risk assessment can be integrated into the processing flow.

```text
PROCESSING ACTIVITY
        ↓
DATA IDENTIFICATION
        ↓
PURPOSE
        ↓
THREATS / RISKS
        ↓
IMPACT
        ↓
MITIGATION
        ↓
RESIDUAL RISK
```

The result should support management decisions about the processing activity.

---

# 27. Processing Records

Organizations may maintain records describing processing activities.

A simplified structure is:

```text
PROCESSING ACTIVITY
        ↓
Purpose
        ↓
Data Categories
        ↓
Data Subjects
        ↓
Recipients
        ↓
Locations
        ↓
Retention
        ↓
Security Measures
```

This creates a structured representation of how personal data is handled.

---

# 28. Processing Activity and Data Owner

Ownership should be clearly established.

```text
PROCESSING ACTIVITY
        ↓
BUSINESS OWNER
        ↓
ACCOUNTABILITY
        ↓
RISK MANAGEMENT
        ↓
CONTROL MANAGEMENT
```

Possible stakeholders include:

```text
Business Owner
Data Owner
Privacy
Security
Legal
IT
Compliance
Third-Party Management
Internal Audit
```

---

# 29. Processing Activity and Accountability

A GRC-oriented model can connect processing to accountability:

```text
PROCESSING ACTIVITY
        ↓
OWNER
        ↓
PURPOSE
        ↓
RISK
        ↓
CONTROL
        ↓
EVIDENCE
        ↓
ASSESSMENT
```

This creates traceability for audit and compliance purposes.

---

# 30. Processing Flow and Consent

Where consent is the applicable basis for processing, the process can include consent management.

```text
DATA SUBJECT
      ↓
CONSENT REQUEST
      ↓
CONSENT DECISION
      ↓
CONSENT RECORD
      ↓
PROCESSING
```

If consent is withdrawn:

```text
WITHDRAWAL
    ↓
CONSENT STATUS UPDATED
    ↓
PROCESSING REVIEW
    ↓
APPROPRIATE ACTION
```

Consent is not the appropriate legal basis for every processing activity, so organizations should not treat consent as a universal requirement.

---

# 31. Processing Flow and Legal Basis

For privacy programs operating under laws that require a legal basis for processing, the flow can include:

```text
PROCESSING PURPOSE
        ↓
LEGAL BASIS ASSESSMENT
        ↓
PROCESSING
        ↓
DOCUMENTATION
        ↓
MONITORING
```

Potential legal bases vary by jurisdiction and applicable law.

The important GRC principle is:

> **The organization should be able to explain why a processing activity is permitted and how that determination is documented.**

---

# 32. Processing and Data Quality

Personal data should also be appropriately maintained.

```text
PERSONAL DATA
      ↓
QUALITY CHECK
      ↓
ACCURATE?
      ↓
COMPLETE?
      ↓
CURRENT?
      ↓
CORRECT IF NECESSARY
```

Poor-quality data can create:

```text
Business Risk
Customer Impact
Compliance Risk
Incorrect Decisions
Operational Errors
```

---

# 33. Processing and AI

AI introduces additional processing paths.

```text
PERSONAL DATA
      ↓
AI SYSTEM
      ↓
MODEL PROCESSING
      ↓
MODEL OUTPUT
      ↓
BUSINESS DECISION / SERVICE
```

The organization may need to consider:

```text
Data Sources
Training Data
Prompts
Inputs
Outputs
Model Provider
Data Retention
Access
Monitoring
Third-Party Processing
```

AI processing should therefore be incorporated into the organization's broader data-processing map.

---

# 34. Processing Flow and Incident Management

A security or privacy incident can interrupt the processing flow.

```text
PROCESSING
    ↓
SECURITY / PRIVACY INCIDENT
    ↓
DETECTION
    ↓
CONTAINMENT
    ↓
INVESTIGATION
    ↓
IMPACT ASSESSMENT
    ↓
REMEDIATION
    ↓
RECOVERY
```

Depending on the circumstances and applicable law, notification or reporting obligations may also arise.

---

# 35. Processing Flow and Third-Party Incident

A third-party incident can follow a similar path:

```text
THIRD PARTY
     ↓
INCIDENT
     ↓
NOTIFICATION
     ↓
ORGANIZATION
     ↓
IMPACT ASSESSMENT
     ↓
REGULATORY / CONTRACTUAL ASSESSMENT
     ↓
RESPONSE
```

This demonstrates why supplier contracts should include appropriate security and incident-management provisions.

---

# 36. Processing Flow and Evidence

Each stage can generate evidence.

```text
COLLECTION
   ↓
Collection Record

PROCESSING
   ↓
Processing Record

ACCESS
   ↓
Access Log

SHARING
   ↓
Transfer / Contract Record

RETENTION
   ↓
Retention Record

DELETION
   ↓
Deletion Evidence
```

This evidence can support:

```text
Audit
Compliance
Privacy Reviews
Incident Investigation
Risk Assessments
Management Reporting
```

---

# 37. Personal Data Processing Control Matrix

A GRC team can map processing activities to controls.

| Processing Stage | Risk                    | Example Control             | Evidence               |
| ---------------- | ----------------------- | --------------------------- | ---------------------- |
| Collection       | Excessive collection    | Data minimization           | Collection design      |
| Processing       | Unauthorized use        | Access and purpose controls | Access records         |
| Storage          | Unauthorized disclosure | Encryption                  | Configuration evidence |
| Sharing          | Third-party exposure    | Supplier controls           | Contract / assessment  |
| Transfer         | Transfer risk           | Approved transfer mechanism | Transfer record        |
| Retention        | Excessive retention     | Retention schedule          | Retention report       |
| Deletion         | Data remains available  | Secure deletion             | Deletion evidence      |

This creates direct traceability from processing activities to GRC controls.

---

# 38. End-to-End Processing Flow

A comprehensive processing flow can be represented as:

```text
                         DATA SUBJECT
                              ↓
                       PERSONAL DATA
                              ↓
                          COLLECTION
                              ↓
                     PURPOSE DEFINITION
                              ↓
                     LEGAL / POLICY REVIEW
                              ↓
                         PROCESSING
                              ↓
             ┌────────────────┼────────────────┐
             ↓                ↓                ↓
          INTERNAL         STORAGE          ANALYTICS
             ↓                ↓                ↓
             └────────────────┼────────────────┘
                              ↓
                       SHARING / TRANSFER
                              ↓
                       THIRD-PARTY PROCESSING
                              ↓
                           RETENTION
                              ↓
                          ARCHIVING
                              ↓
                           DELETION
                              ↓
                         VERIFICATION
```

Governance controls operate across the entire flow.

---

# 39. GRC Overlay

A mature privacy GRC model adds several governance layers:

```text
                    PERSONAL DATA FLOW
                           ↓
       ┌───────────────────┼───────────────────┐
       ↓                   ↓                   ↓
    PRIVACY             SECURITY            COMPLIANCE
       ↓                   ↓                   ↓
       └───────────────────┼───────────────────┘
                           ↓
                     RISK MANAGEMENT
                           ↓
                      CONTROL SYSTEM
                           ↓
                     EVIDENCE / AUDIT
```

This demonstrates that privacy should not operate as an isolated function.

---

# 40. Executive View

For executives, the processing flow can be simplified to:

```text
COLLECT
   ↓
WHY?
   ↓
PROCESS
   ↓
WHO HAS ACCESS?
   ↓
WHERE IS IT?
   ↓
WHO RECEIVES IT?
   ↓
HOW LONG?
   ↓
DELETE
```

At each stage, management should understand:

```text
Risk
Ownership
Compliance
Security
Accountability
```

---

# 41. Complete GRC Personal Data Processing Model

The complete model can be summarized as:

```text
                       DATA SUBJECT
                            ↓
                    PERSONAL DATA
                            ↓
                       COLLECTION
                            ↓
                    PURPOSE / NEED
                            ↓
                LEGAL / POLICY ASSESSMENT
                            ↓
                       PROCESSING
                            ↓
              ┌─────────────┼─────────────┐
              ↓             ↓             ↓
           INTERNAL       STORAGE       SHARING
              ↓             ↓             ↓
              └─────────────┼─────────────┘
                            ↓
                       TRANSFER
                            ↓
                    THIRD-PARTY PROCESSING
                            ↓
                        RETENTION
                            ↓
                        ARCHIVING
                            ↓
                        DELETION
                            ↓
                      VERIFICATION
                            ↓
                         EVIDENCE
```

The key GRC principle is:

> **Every personal-data processing activity should be understandable, attributable, risk-assessed, appropriately controlled, and traceable from the point of collection through its final disposal.**

This makes the Personal Data Processing Flow a valuable diagram for **privacy governance, data protection, cybersecurity, third-party risk, regulatory compliance, audit, and enterprise GRC**.

# 18.8 Privacy and Data Protection Diagrams

### Part 3 – Privacy Risk Assessment Flow

A **Privacy Risk Assessment Flow** provides a structured visual method for identifying, analyzing, evaluating, and treating risks associated with the collection and processing of personal data.

From a GRC perspective, the purpose is to move from:

```text
Personal Data Processing
        ↓
Potential Privacy Risk
        ↓
Risk Evaluation
        ↓
Risk Treatment
        ↓
Residual Risk
        ↓
Ongoing Monitoring
```

A privacy risk assessment should not be treated as a one-time exercise. It should be revisited when processing activities, technologies, threats, regulations, or business purposes change.

---

# 1. What Is a Privacy Risk Assessment?

A privacy risk assessment evaluates the potential negative consequences that could arise from how personal data is collected, processed, stored, shared, transferred, or deleted.

A simplified model is:

```text
PROCESSING ACTIVITY
        ↓
PERSONAL DATA
        ↓
PRIVACY THREATS
        ↓
POTENTIAL IMPACT
        ↓
PRIVACY RISK
```

The assessment then determines how the organization should respond.

---

# 2. Basic Privacy Risk Assessment Flow

A typical flow is:

```text
        PROCESSING ACTIVITY
                ↓
          DATA IDENTIFICATION
                ↓
           PURPOSE ANALYSIS
                ↓
          RISK IDENTIFICATION
                ↓
          RISK ANALYSIS
                ↓
          RISK EVALUATION
                ↓
          RISK TREATMENT
                ↓
        RESIDUAL RISK ASSESSMENT
                ↓
            MONITORING
```

This provides a repeatable process that can be incorporated into a broader GRC program.

---

# 3. Step 1 – Identify the Processing Activity

The assessment begins by clearly defining what processing is taking place.

Examples:

```text
Customer Registration
Employee Recruitment
Payroll Processing
Marketing
Fraud Detection
Video Surveillance
Customer Support
AI Processing
Analytics
```

The basic structure is:

```text
BUSINESS PROCESS
       ↓
PROCESSING ACTIVITY
       ↓
PRIVACY ASSESSMENT
```

Without clearly defining the processing activity, it is difficult to determine what privacy risks exist.

---

# 4. Step 2 – Identify the Data

The next step is to determine what personal data is involved.

```text
PROCESSING ACTIVITY
        ↓
DATA IDENTIFICATION
        ↓
┌───────────────┬───────────────┬───────────────┐
↓               ↓               ↓
Identity       Contact        Transaction
Data           Data           Data
```

Additional categories may include:

```text
Location Data
Online Identifiers
Employment Data
Financial Data
Authentication Data
Health Information
Biometric Information
```

The organization should identify the categories relevant to the specific processing activity.

---

# 5. Step 3 – Identify Data Subjects

The assessment should determine whose data is being processed.

Examples include:

```text
Customers
Employees
Applicants
Children
Suppliers
Website Visitors
Patients
Students
Users
```

The flow becomes:

```text
PROCESSING ACTIVITY
        ↓
DATA CATEGORIES
        ↓
DATA SUBJECT CATEGORIES
```

Different groups may experience different levels of privacy risk.

---

# 6. Step 4 – Determine the Purpose

The organization should identify why the personal data is being processed.

```text
PERSONAL DATA
      ↓
PURPOSE
      ↓
PROCESSING ACTIVITY
```

For example:

```text
Customer Data
     ↓
Account Management
     ↓
Customer Service System
```

A clearly defined purpose helps determine whether the processing is appropriate and proportionate.

---

# 7. Step 5 – Identify the Data Flow

The assessment should map how the information moves.

```text
DATA SUBJECT
     ↓
COLLECTION
     ↓
APPLICATION
     ↓
DATABASE
     ↓
INTERNAL USERS
     ↓
THIRD PARTY
     ↓
ARCHIVE
     ↓
DELETION
```

The data flow helps reveal risks that might otherwise remain hidden.

---

# 8. Data Flow Risk Points

Each transition can represent a risk point.

```text
Collection ─────→ Risk
      ↓
Processing ─────→ Risk
      ↓
Storage ────────→ Risk
      ↓
Sharing ────────→ Risk
      ↓
Transfer ───────→ Risk
      ↓
Retention ──────→ Risk
      ↓
Deletion ───────→ Risk
```

This is why privacy risk assessment should examine the **entire processing lifecycle**.

---

# 9. Step 6 – Identify Privacy Threats

Potential threats may include:

```text
Unauthorized Access
Unauthorized Disclosure
Excessive Collection
Incorrect Data
Unauthorized Processing
Data Loss
Data Theft
Excessive Retention
Uncontrolled Sharing
Third-Party Failure
```

The basic relationship is:

```text
DATA
 ↓
THREAT
 ↓
VULNERABILITY
 ↓
PRIVACY IMPACT
```

---

# 10. Threats Versus Privacy Risks

A threat is not necessarily the same as a risk.

For example:

```text
Threat:
Unauthorized access

Vulnerability:
Weak access controls

Potential Impact:
Personal information exposed

Risk:
Unauthorized disclosure of personal data
```

This distinction is useful for GRC professionals because it allows the organization to identify the underlying cause rather than simply documenting the event.

---

# 11. Step 7 – Identify Privacy Vulnerabilities

Vulnerabilities can exist in:

```text
People
Processes
Technology
Third Parties
Governance
```

Examples:

```text
Weak Authentication
Excessive Permissions
Poor Data Mapping
Missing Retention Rules
Unencrypted Storage
Insufficient Monitoring
Weak Supplier Controls
Inadequate Privacy Procedures
```

The model becomes:

```text
THREAT
  ↓
VULNERABILITY
  ↓
POTENTIAL IMPACT
  ↓
RISK
```

---

# 12. Step 8 – Identify Potential Impacts

Privacy risk assessment should consider the potential consequences to individuals and, where appropriate, the organization.

Potential impacts can include:

```text
Loss of Privacy
Identity Theft
Fraud
Financial Harm
Discrimination
Reputational Harm
Emotional Distress
Loss of Confidentiality
Loss of Control Over Personal Data
```

Organizational impacts may include:

```text
Regulatory Exposure
Legal Costs
Customer Loss
Reputational Damage
Operational Disruption
Remediation Costs
```

---

# 13. Individual Impact and Organizational Impact

A mature assessment should distinguish between:

```text
IMPACT ON INDIVIDUAL
        +
IMPACT ON ORGANIZATION
```

For example:

```text
Personal Data Exposure
        ↓
Individual:
Privacy Harm

Organization:
Regulatory / Reputational Risk
```

The individual impact should remain central to privacy risk analysis.

---

# 14. Step 9 – Assess Likelihood

The organization may evaluate how likely a privacy risk is to occur.

A simple scale might be:

```text
1 – Rare
2 – Unlikely
3 – Possible
4 – Likely
5 – Almost Certain
```

For example:

| Likelihood | Description    |
| ---------- | -------------- |
| 1          | Rare           |
| 2          | Unlikely       |
| 3          | Possible       |
| 4          | Likely         |
| 5          | Almost Certain |

The actual scale should be aligned with the organization's risk methodology.

---

# 15. Step 10 – Assess Impact

Impact may also be scored.

For example:

```text
1 – Minimal
2 – Low
3 – Moderate
4 – High
5 – Severe
```

The organization may evaluate factors such as:

```text
Sensitivity of Data
Number of Individuals
Nature of Potential Harm
Duration of Exposure
Ease of Identification
Regulatory Consequences
```

---

# 16. Privacy Risk Scoring

A simplified model is:

```text
Privacy Risk =
Likelihood × Impact
```

For example:

```text
Likelihood = 4
Impact = 5

Risk Score = 20
```

A matrix can then classify the result:

```text
              IMPACT
          Low   Med   High
        ┌─────┬─────┬─────┐
Low     │  L  │  L  │  M  │
        ├─────┼─────┼─────┤
Medium  │  L  │  M  │  H  │
        ├─────┼─────┼─────┤
High    │  M  │  H  │  H  │
        └─────┴─────┴─────┘
```

This is illustrative; an organization may use a more sophisticated methodology.

---

# 17. Privacy Risk Register

Identified risks can be documented in a privacy risk register.

| Risk                    | Likelihood | Impact | Rating | Owner          |
| ----------------------- | ---------: | -----: | ------ | -------------- |
| Unauthorized access     |          4 |      5 | High   | Security       |
| Excessive retention     |          3 |      4 | High   | Data Owner     |
| Third-party exposure    |          3 |      5 | High   | Vendor Manager |
| Incorrect personal data |          2 |      3 | Medium | Business Owner |

A GRC platform can link each risk to:

```text
Processing Activity
Data Category
Data Owner
Control
Treatment
Evidence
Assessment
```

---

# 18. Step 11 – Evaluate Existing Controls

Before deciding on additional treatment, existing controls should be assessed.

```text
PRIVACY RISK
     ↓
EXISTING CONTROLS
     ↓
CONTROL EFFECTIVENESS
     ↓
RESIDUAL RISK
```

Controls may include:

```text
Access Control
Encryption
Data Minimization
Retention Controls
Privacy Notices
Consent Management
Supplier Controls
Monitoring
Data Loss Prevention
Secure Disposal
```

---

# 19. Control Effectiveness

A control can exist but still be ineffective.

For example:

```text
Policy Exists
     ↓
Implementation?
     ↓
Testing?
     ↓
Evidence?
     ↓
Effective?
```

This prevents a common GRC mistake:

> **Assuming that the existence of a policy automatically means the risk is adequately controlled.**

---

# 20. Step 12 – Determine Residual Risk

After existing controls are considered:

```text
INHERENT PRIVACY RISK
          ↓
      CONTROLS
          ↓
   CONTROL EFFECTIVENESS
          ↓
RESIDUAL PRIVACY RISK
```

For example:

```text
Inherent Risk:
High

Controls:
Strong encryption + MFA + monitoring

Residual Risk:
Medium
```

Residual risk is the risk that remains after controls are applied.

---

# 21. Inherent Versus Residual Privacy Risk

The distinction can be visualized as:

```text
             INHERENT RISK
                  ↓
        ┌───────────────────┐
        │ Privacy Controls  │
        └───────────────────┘
                  ↓
             RESIDUAL RISK
```

This provides management with a clearer picture of the effectiveness of the privacy control environment.

---

# 22. Step 13 – Risk Treatment

If residual risk is unacceptable, additional action may be required.

```text
RESIDUAL RISK
      ↓
ACCEPTABLE?
   ↙       ↘
 YES        NO
 ↓           ↓
Monitor    Treatment
             ↓
      ┌──────┼──────┐
      ↓      ↓      ↓
    Reduce Transfer Avoid
```

Depending on the organization's risk framework, acceptance may also be an option when appropriately authorized.

---

# 23. Privacy Risk Treatment Options

Typical options include:

### Reduce

Implement additional controls.

```text
Risk
 ↓
Encryption
 ↓
Access Control
 ↓
Monitoring
 ↓
Reduced Risk
```

### Avoid

Stop or redesign the processing activity.

```text
High-Risk Processing
        ↓
Business Review
        ↓
Stop / Redesign
```

### Transfer

Shift some risk through contractual or insurance mechanisms where appropriate.

```text
Risk
 ↓
Contractual Allocation
 ↓
Third-Party Arrangement
```

### Accept

Management may formally accept a risk when it falls within approved risk appetite and appropriate governance requirements are met.

---

# 24. Privacy-by-Design Perspective

Privacy risk assessment should ideally happen before a new system or process goes live.

```text
BUSINESS REQUIREMENT
        ↓
SYSTEM DESIGN
        ↓
PRIVACY RISK ASSESSMENT
        ↓
CONTROL DESIGN
        ↓
IMPLEMENTATION
        ↓
VALIDATION
        ↓
PRODUCTION
```

This is generally more effective than discovering major privacy problems after deployment.

---

# 25. New Project Privacy Assessment

For a new project:

```text
PROJECT INITIATION
       ↓
DATA IDENTIFICATION
       ↓
PROCESSING ANALYSIS
       ↓
PRIVACY RISK ASSESSMENT
       ↓
CONTROL REQUIREMENTS
       ↓
IMPLEMENTATION
       ↓
SECURITY / PRIVACY TESTING
       ↓
GO-LIVE
```

This embeds privacy into the project lifecycle.

---

# 26. Change Management

Privacy risks should also be reassessed when existing systems change.

Triggers may include:

```text
New Technology
New Data Type
New Processing Purpose
New Supplier
New Country
New AI Capability
System Integration
Major Architecture Change
Regulatory Change
```

The flow becomes:

```text
CHANGE
  ↓
PRIVACY IMPACT REVIEW
  ↓
RISK REASSESSMENT
  ↓
CONTROL UPDATE
  ↓
APPROVAL
  ↓
IMPLEMENTATION
```

---

# 27. Privacy Impact Assessment Relationship

A Privacy Risk Assessment can form part of a broader **Privacy Impact Assessment (PIA)** or **Data Protection Impact Assessment (DPIA)** process where required or appropriate.

A simplified relationship is:

```text
PROCESSING ACTIVITY
        ↓
PRIVACY ASSESSMENT
        ↓
RISK IDENTIFICATION
        ↓
IMPACT ANALYSIS
        ↓
MITIGATION
        ↓
DOCUMENTATION
        ↓
MONITORING
```

The exact terminology and legal requirements depend on the applicable jurisdiction.

---

# 28. High-Risk Processing

Some processing activities may warrant enhanced assessment.

Examples can include:

```text
Large-Scale Personal Data Processing
Sensitive Data Processing
Systematic Monitoring
Automated Decision-Making
Profiling
Biometric Processing
Large-Scale Surveillance
Innovative Technologies
```

A simplified escalation model is:

```text
PROCESSING
    ↓
RISK SCREENING
    ↓
LOW RISK ─────────→ Standard Assessment
    ↓
HIGHER RISK
    ↓
ENHANCED ASSESSMENT
```

The actual threshold should be defined by the organization's privacy governance framework and applicable law.

---

# 29. Privacy Risk and Third Parties

Third parties can significantly affect privacy risk.

```text
ORGANIZATION
      ↓
PERSONAL DATA
      ↓
THIRD PARTY
      ↓
PROCESSING
      ↓
RISK
```

Assessment areas may include:

```text
Security Controls
Privacy Practices
Data Location
Subprocessors
Retention
Incident Management
Contractual Obligations
Audit Rights
Deletion Procedures
```

---

# 30. Privacy Risk and Cloud Services

Cloud services may introduce additional considerations.

```text
PERSONAL DATA
      ↓
CLOUD SERVICE
      ↓
┌──────────────┬──────────────┬──────────────┐
↓              ↓              ↓
Storage      Processing     Transfer
↓              ↓              ↓
Risk           Risk           Risk
```

The assessment should consider:

```text
Cloud Provider
Data Location
Encryption
Access
Logging
Subprocessors
Retention
Deletion
Contractual Controls
```

---

# 31. Privacy Risk and AI

AI processing can create additional privacy risks.

```text
PERSONAL DATA
      ↓
AI INPUT
      ↓
MODEL PROCESSING
      ↓
MODEL OUTPUT
      ↓
BUSINESS DECISION
```

Potential risks include:

```text
Excessive Data Collection
Sensitive Data Exposure
Unauthorized Model Training
Data Leakage
Inference of Personal Information
Third-Party AI Processing
Unclear Retention
```

The assessment should therefore consider the complete AI data flow.

---

# 32. Privacy Risk and Data Breach

Privacy risk assessment also helps organizations understand potential breach consequences.

```text
THREAT
  ↓
VULNERABILITY
  ↓
DATA EXPOSURE
  ↓
INDIVIDUAL IMPACT
  ↓
ORGANIZATIONAL IMPACT
  ↓
REGULATORY / LEGAL CONSEQUENCES
```

This supports incident-preparedness planning.

---

# 33. Privacy Risk and Data Subject Harm

A mature privacy risk assessment should focus on potential harm to individuals rather than only technical security events.

For example:

```text
Unauthorized Disclosure
        ↓
Personal Information Exposed
        ↓
Potential Individual Harm
        ↓
Privacy Risk
```

The question is not simply:

> "Can the system be breached?"

It is also:

> "What could happen to individuals if the personal data were misused, exposed, altered, or made unavailable?"

---

# 34. Privacy Risk and Data Quality

Incorrect personal data can create privacy risks even without a security breach.

```text
Incorrect Data
      ↓
Incorrect Decision
      ↓
Individual Impact
      ↓
Privacy Risk
```

Examples include:

```text
Incorrect Customer Information
Incorrect Credit Information
Incorrect Employee Information
Incorrect Identity Information
```

Therefore, data quality can form part of privacy risk management.

---

# 35. Privacy Risk and Retention

Retention should be explicitly assessed.

```text
DATA RETAINED
      ↓
IS IT STILL REQUIRED?
      ↓
YES → Continue Retention
      ↓
NO → Review Disposal
```

Excessive retention can increase:

```text
Exposure
Storage Risk
Breach Impact
Compliance Risk
Privacy Risk
```

---

# 36. Privacy Risk and Data Minimization

Data minimization can reduce inherent risk.

```text
Collect More Data
       ↓
Larger Exposure
       ↓
Higher Potential Impact
```

versus:

```text
Collect Necessary Data
       ↓
Smaller Exposure
       ↓
Lower Potential Impact
```

This makes data minimization both a privacy principle and a risk-reduction strategy.

---

# 37. Privacy Risk Treatment Plan

A treatment plan can be structured as:

```text
RISK
 ↓
TREATMENT OBJECTIVE
 ↓
ACTION
 ↓
CONTROL
 ↓
OWNER
 ↓
DUE DATE
 ↓
EVIDENCE
 ↓
VALIDATION
```

Example:

```text
Risk:
Unauthorized access to customer records

Treatment:
Strengthen access control

Control:
MFA + role-based access

Owner:
IAM Team

Evidence:
Access Configuration

Validation:
Control Testing
```

---

# 38. Privacy Risk Acceptance

If a risk remains after treatment:

```text
RESIDUAL RISK
      ↓
WITHIN RISK APPETITE?
      ↓
YES
      ↓
FORMAL ACCEPTANCE
      ↓
MONITOR
```

Risk acceptance should be:

```text
Documented
Authorized
Time-Bounded Where Appropriate
Reviewed
Monitored
```

An unaddressed risk should not simply disappear from the risk register.

---

# 39. Continuous Monitoring

Privacy risks change over time.

```text
RISK ASSESSMENT
      ↓
TREATMENT
      ↓
MONITORING
      ↓
NEW INFORMATION
      ↓
REASSESSMENT
      ↺
```

Triggers for reassessment may include:

```text
New Threat
Security Incident
Regulatory Change
New Supplier
New Processing Purpose
Technology Change
Business Change
Audit Finding
```

---

# 40. Privacy Risk Metrics

Management can use metrics to monitor privacy risk.

Examples include:

```text
Number of High Privacy Risks
Open Privacy Risks
Overdue Risk Treatments
Third-Party Privacy Assessments
Data Subject Requests
Privacy Incidents
Data Retention Exceptions
Unmapped Processing Activities
Control Effectiveness
```

A simplified dashboard might show:

```text
Privacy Risk Dashboard

High Risks             8
Medium Risks          17
Open Treatments       11
Overdue Actions        3
High-Risk Suppliers    5
Privacy Incidents      2
```

The figures are illustrative.

---

# 41. Privacy Risk Assessment and GRC Traceability

A mature GRC environment can connect:

```text
PROCESSING ACTIVITY
        ↓
DATA
        ↓
PRIVACY RISK
        ↓
RISK OWNER
        ↓
CONTROL
        ↓
CONTROL TEST
        ↓
EVIDENCE
        ↓
RESIDUAL RISK
        ↓
TREATMENT
        ↓
MANAGEMENT DECISION
```

This provides strong auditability and accountability.

---

# 42. Privacy Risk Control Matrix

A GRC team can create a matrix such as:

| Privacy Risk          | Control             | Owner      | Evidence         | Residual Risk |
| --------------------- | ------------------- | ---------- | ---------------- | ------------- |
| Unauthorized access   | Access control      | IAM        | Access review    | Medium        |
| Excessive retention   | Retention policy    | Data Owner | Retention report | Low           |
| Third-party exposure  | Supplier assessment | TPRM       | Assessment       | Medium        |
| Data leakage          | DLP                 | Security   | DLP reports      | Medium        |
| Uncontrolled transfer | Transfer safeguards | Privacy    | Transfer records | Low           |

This transforms the assessment into an operational GRC process.

---

# 43. End-to-End Privacy Risk Assessment Flow

The complete flow can be represented as:

```text
                     PROCESSING ACTIVITY
                              ↓
                       DATA IDENTIFICATION
                              ↓
                      DATA SUBJECT ANALYSIS
                              ↓
                        PURPOSE ANALYSIS
                              ↓
                        DATA FLOW MAPPING
                              ↓
                       THREAT IDENTIFICATION
                              ↓
                      VULNERABILITY ANALYSIS
                              ↓
                       IMPACT ASSESSMENT
                              ↓
                     LIKELIHOOD ASSESSMENT
                              ↓
                        INHERENT RISK
                              ↓
                       CONTROL ASSESSMENT
                              ↓
                        RESIDUAL RISK
                              ↓
                      RISK TREATMENT
                              ↓
                       MANAGEMENT DECISION
                              ↓
                         MONITORING
                              ↓
                       REASSESSMENT
                              ↺
```

---

# 44. Integrated Privacy GRC Model

The Privacy Risk Assessment Flow can connect several GRC disciplines:

```text
                         BUSINESS PROCESS
                                ↓
                        PROCESSING ACTIVITY
                                ↓
              ┌─────────────────┼─────────────────┐
              ↓                 ↓                 ↓
           PRIVACY             SECURITY         COMPLIANCE
              ↓                 ↓                 ↓
              └─────────────────┼─────────────────┘
                                ↓
                          RISK ASSESSMENT
                                ↓
                          CONTROL ASSESSMENT
                                ↓
                          RESIDUAL RISK
                                ↓
                         TREATMENT / ACCEPTANCE
                                ↓
                            ASSURANCE
                                ↓
                           MONITORING
```

This demonstrates how privacy risk management fits naturally within an enterprise GRC operating model.

---

# 45. Executive Privacy Risk Model

For senior management, the process can be reduced to:

```text
WHAT ARE WE PROCESSING?
          ↓
WHY ARE WE PROCESSING IT?
          ↓
WHAT COULD GO WRONG?
          ↓
WHO COULD BE AFFECTED?
          ↓
HOW SERIOUS IS THE RISK?
          ↓
WHAT CONTROLS DO WE HAVE?
          ↓
WHAT RISK REMAINS?
          ↓
WHAT DECISION IS REQUIRED?
```

This provides an executive-friendly way of discussing privacy risk without requiring detailed technical knowledge.

---

# 46. Key GRC Principles

A mature Privacy Risk Assessment should follow several principles:

```text
1. Understand the processing activity.
2. Identify the personal data involved.
3. Understand the data subjects affected.
4. Define the processing purpose.
5. Map the data flow.
6. Identify threats and vulnerabilities.
7. Assess potential individual impact.
8. Evaluate likelihood and impact.
9. Assess existing controls.
10. Determine residual risk.
11. Treat or formally accept the risk.
12. Monitor and reassess when conditions change.
```

The central principle is:

> **Privacy risk management should connect personal-data processing to potential individual harm, organizational exposure, controls, residual risk, and management decisions.**

---

# 47. Final Integrated Model

The complete Privacy Risk Assessment Flow can be summarized as:

```text
                    PERSONAL DATA
                          ↓
                 PROCESSING ACTIVITY
                          ↓
                    DATA FLOW
                          ↓
                 PRIVACY THREATS
                          ↓
                  VULNERABILITIES
                          ↓
                  POTENTIAL HARM
                          ↓
                 INHERENT PRIVACY RISK
                          ↓
                     CONTROLS
                          ↓
                 CONTROL EFFECTIVENESS
                          ↓
                  RESIDUAL PRIVACY RISK
                          ↓
             ┌────────────┴────────────┐
             ↓                         ↓
         TREAT RISK              ACCEPT RISK
             ↓                         ↓
       IMPLEMENT ACTIONS           APPROVAL
             ↓                         ↓
             └────────────┬────────────┘
                          ↓
                      MONITORING
                          ↓
                     REASSESSMENT
                          ↺
```

The most important GRC concept is that **privacy risk is not limited to a single security incident or compliance requirement**. It exists throughout the personal-data processing lifecycle and should be managed through a structured process of **identification, assessment, control, treatment, acceptance, monitoring, and continual reassessment**.

# 18.8 Privacy and Data Protection Diagrams

### Part 4 – Data Breach Response Flow

A **Data Breach Response Flow** illustrates how an organization detects, assesses, contains, investigates, reports, remediates, and learns from a personal-data breach.

From a GRC perspective, the objective is to establish a clear chain from the initial event through:

```text
Potential Breach
      ↓
Detection
      ↓
Initial Assessment
      ↓
Containment
      ↓
Investigation
      ↓
Impact Assessment
      ↓
Notification Decision
      ↓
Remediation
      ↓
Recovery
      ↓
Lessons Learned
      ↓
Risk & Control Improvement
```

A data breach response process should connect **privacy, cybersecurity, legal, compliance, communications, business operations, and executive management**.

---

# 1. What Is a Data Breach?

A data breach generally involves a security incident that results in unauthorized access to, disclosure of, alteration of, loss of, or destruction of personal data.

Examples include:

```text
Unauthorized Access
Unauthorized Disclosure
Stolen Device
Lost Device
Phishing
Malware
Ransomware
Accidental Email Disclosure
Misconfigured Cloud Storage
Insider Misuse
Third-Party Compromise
```

Not every security incident is necessarily a personal-data breach.

For example:

```text
Security Incident
      ↓
Was Personal Data Involved?
      ↓
   NO       YES
   ↓         ↓
Security    Breach
Incident    Assessment
```

This distinction is important for GRC and regulatory decision-making.

---

# 2. Basic Data Breach Response Flow

A simplified model is:

```text
INCIDENT DETECTED
       ↓
INITIAL TRIAGE
       ↓
PERSONAL DATA INVOLVED?
       ↓
      YES
       ↓
CONTAINMENT
       ↓
INVESTIGATION
       ↓
IMPACT / RISK ASSESSMENT
       ↓
NOTIFICATION DECISION
       ↓
REMEDIATION
       ↓
RECOVERY
       ↓
LESSONS LEARNED
```

The exact process and notification obligations depend on the applicable jurisdiction and circumstances.

---

# 3. Step 1 – Detection

A breach may be detected through multiple sources.

```text
                    DETECTION
                        ↓
       ┌────────────────┼────────────────┐
       ↓                ↓                ↓
   Security Tool     Employee        Third Party
       ↓                ↓                ↓
       └────────────────┼────────────────┘
                        ↓
                  INCIDENT REPORT
```

Examples:

```text
SIEM Alert
EDR Alert
DLP Alert
User Report
Customer Complaint
Supplier Notification
Audit Finding
Law Enforcement Notification
```

---

# 4. Step 2 – Initial Triage

The first objective is to determine what happened and whether immediate action is required.

```text
INCIDENT
   ↓
INITIAL TRIAGE
   ↓
What happened?
When?
Where?
Which system?
Which data?
Who detected it?
Is the incident ongoing?
```

The organization should avoid prematurely declaring an event to be a confirmed personal-data breach before sufficient facts are available.

---

# 5. Security Incident Versus Data Breach

A useful decision point is:

```text
SECURITY INCIDENT
        ↓
PERSONAL DATA INVOLVED?
      ↙       ↘
    NO         YES
    ↓           ↓
SECURITY      PRIVACY
RESPONSE      ASSESSMENT
```

For example:

```text
Server outage
     ↓
No personal data affected
     ↓
Security / IT incident
```

versus:

```text
Unauthorized database access
     ↓
Customer personal data exposed
     ↓
Potential personal-data breach
```

---

# 6. Step 3 – Activate the Response Team

A significant breach may require a coordinated response team.

```text
                 INCIDENT
                    ↓
             RESPONSE TEAM
                    ↓
      ┌─────────────┼─────────────┐
      ↓             ↓             ↓
   Security       Privacy        Legal
      ↓             ↓             ↓
      ├─────────────┼─────────────┤
      ↓             ↓             ↓
     IT           Compliance   Communications
      ↓             ↓             ↓
      └─────────────┼─────────────┘
                    ↓
              Executive Management
```

The exact participants depend on the organization's size and incident severity.

---

# 7. Step 4 – Containment

Containment attempts to stop the incident from continuing or spreading.

Examples include:

```text
Disable Compromised Account
Isolate Endpoint
Block Malicious Connection
Revoke Credentials
Disable API Key
Disconnect Affected System
Restrict Data Access
Suspend Third-Party Integration
```

A simplified flow:

```text
BREACH
  ↓
CONTAINMENT
  ↓
STOP / LIMIT EXPOSURE
  ↓
PRESERVE EVIDENCE
```

Containment and evidence preservation should be coordinated carefully.

---

# 8. Containment Levels

Containment can occur at multiple levels.

```text
                    CONTAINMENT
                         ↓
        ┌────────────────┼────────────────┐
        ↓                ↓                ↓
      Identity         Endpoint         Network
        ↓                ↓                ↓
     Account          Device           Traffic
     Controls         Isolation        Blocking
```

Additional containment may occur at the application or database level.

---

# 9. Step 5 – Evidence Preservation

Evidence should be preserved to support investigation and decision-making.

Potential evidence includes:

```text
System Logs
Authentication Logs
Network Logs
Application Logs
Database Logs
Email Records
Endpoint Data
Cloud Logs
Access Records
Configuration Records
Incident Tickets
```

The process is:

```text
INCIDENT
   ↓
EVIDENCE IDENTIFICATION
   ↓
EVIDENCE PRESERVATION
   ↓
INVESTIGATION
   ↓
FINDINGS
```

Evidence handling should follow the organization's incident-response and forensic procedures.

---

# 10. Step 6 – Investigation

The investigation attempts to establish what actually happened.

```text
INCIDENT
   ↓
TIMELINE
   ↓
INITIAL ACCESS
   ↓
ATTACK / ERROR PATH
   ↓
SYSTEMS AFFECTED
   ↓
DATA AFFECTED
   ↓
ROOT CAUSE
```

The investigation should distinguish between:

```text
Confirmed Facts
Probable Findings
Unknown Information
```

This distinction is important when communicating with management and regulators.

---

# 11. Breach Timeline

A timeline can help investigators understand the sequence.

```text
T0
↓
Initial Compromise

T1
↓
Unauthorized Access

T2
↓
Data Access / Disclosure

T3
↓
Detection

T4
↓
Containment

T5
↓
Investigation

T6
↓
Remediation
```

A timeline is also valuable evidence during post-incident reviews.

---

# 12. Step 7 – Identify the Personal Data

The investigation should determine exactly what personal data may have been affected.

```text
AFFECTED SYSTEM
      ↓
DATA IDENTIFICATION
      ↓
┌────────────┬────────────┬────────────┐
↓            ↓            ↓
Identity     Contact      Financial
Data         Data         Data
```

Other categories may include:

```text
Authentication Information
Location Data
Employment Information
Health Information
Biometric Data
Transaction Data
```

The exact categories depend on the incident.

---

# 13. Step 8 – Determine the Number of Individuals

The organization should establish, as far as reasonably possible, how many individuals may be affected.

```text
AFFECTED DATABASE
       ↓
RECORD ANALYSIS
       ↓
AFFECTED RECORDS
       ↓
UNIQUE INDIVIDUALS
       ↓
AFFECTED DATA SUBJECT POPULATION
```

This information can be important for risk assessment and notification decisions.

---

# 14. Step 9 – Determine the Nature of the Breach

A useful classification is:

```text
             DATA BREACH
                  ↓
       ┌──────────┼──────────┐
       ↓          ↓          ↓
CONFIDENTIALITY INTEGRITY AVAILABILITY
       ↓          ↓          ↓
Disclosure       Alteration   Loss
Access           Modification Destruction
```

For example:

```text
Confidentiality:
Unauthorized person accessed personal data.

Integrity:
Personal data was maliciously altered.

Availability:
Personal data became unavailable because of an attack.
```

An incident can involve more than one category.

---

# 15. Step 10 – Assess Individual Risk

The organization should evaluate potential consequences for affected individuals.

Consider:

```text
Type of Data
Sensitivity
Number of Individuals
Likelihood of Misuse
Potential Harm
Duration of Exposure
Identity Theft Potential
Financial Impact
Discrimination Risk
Other Individual Harm
```

The assessment can be represented as:

```text
DATA
 ↓
EXPOSURE
 ↓
MISUSE POTENTIAL
 ↓
INDIVIDUAL HARM
 ↓
RISK LEVEL
```

---

# 16. Step 11 – Assess Organizational Risk

The organization should also consider:

```text
Regulatory Exposure
Contractual Exposure
Litigation Risk
Reputational Impact
Financial Impact
Operational Impact
Customer Impact
Remediation Cost
```

The complete model is:

```text
                 DATA BREACH
                      ↓
            ┌─────────┴─────────┐
            ↓                   ↓
     INDIVIDUAL IMPACT    ORGANIZATIONAL IMPACT
            ↓                   ↓
            └─────────┬─────────┘
                      ↓
                 RISK DECISION
```

---

# 17. Step 12 – Determine Regulatory Obligations

The organization should determine whether the incident creates notification or reporting obligations.

```text
BREACH
  ↓
JURISDICTION
  ↓
APPLICABLE LAW
  ↓
THRESHOLD ASSESSMENT
  ↓
NOTIFICATION REQUIRED?
```

This determination should involve the appropriate privacy, legal, and compliance functions.

For organizations operating across multiple jurisdictions:

```text
ONE INCIDENT
     ↓
MULTIPLE JURISDICTIONS
     ↓
MULTIPLE REQUIREMENTS
     ↓
COORDINATED RESPONSE
```

---

# 18. Notification Decision

A simplified decision model is:

```text
PERSONAL-DATA BREACH
         ↓
RISK ASSESSMENT
         ↓
NOTIFICATION REQUIRED?
       ↙       ↘
     YES        NO
      ↓          ↓
NOTIFY        DOCUMENT
```

The organization should document the reasoning supporting the decision.

Not every breach requires notification to every stakeholder.

---

# 19. Regulatory Notification

Where notification is legally required, the organization should coordinate the process.

```text
BREACH
  ↓
ASSESSMENT
  ↓
REGULATORY REQUIREMENT
  ↓
NOTIFICATION PREPARATION
  ↓
LEGAL / PRIVACY REVIEW
  ↓
SUBMISSION
  ↓
FOLLOW-UP
```

The applicable deadline, content, and authority depend on the relevant law.

---

# 20. Data Subject Notification

Where required or appropriate, affected individuals may need to be informed.

```text
BREACH
  ↓
INDIVIDUAL RISK ASSESSMENT
  ↓
NOTIFICATION DECISION
  ↓
MESSAGE DEVELOPMENT
  ↓
LEGAL / PRIVACY REVIEW
  ↓
DATA SUBJECT COMMUNICATION
```

Communication should generally be:

```text
Clear
Accurate
Timely
Understandable
Actionable
```

---

# 21. Notification Content

A notification may need to communicate information such as:

```text
What Happened
What Data Was Affected
Potential Consequences
Actions Taken
Recommended Actions
Contact Information
Available Support
```

The exact content should follow applicable legal and regulatory requirements.

---

# 22. Customer Communication

Customer communication should be carefully coordinated.

```text
INCIDENT FACTS
      ↓
PRIVACY / LEGAL REVIEW
      ↓
COMMUNICATIONS
      ↓
CUSTOMER MESSAGE
      ↓
CUSTOMER SUPPORT
```

The organization should avoid speculation and clearly distinguish confirmed information from information still under investigation.

---

# 23. Step 13 – Root Cause Analysis

Once the incident is sufficiently understood, the organization should identify the root cause.

For example:

```text
BREACH
  ↓
COMPROMISED ACCOUNT
  ↓
PHISHING ATTACK
  ↓
INSUFFICIENT MFA
  ↓
CONTROL GAP
  ↓
ROOT CAUSE
```

Root cause analysis should look beyond the immediate technical failure.

---

# 24. Root Cause Categories

Root causes can fall into several categories:

```text
People
Processes
Technology
Governance
Third Party
Configuration
Training
Control Failure
```

For example:

```text
Technical Cause:
Misconfigured database

Control Cause:
Configuration review ineffective

Governance Cause:
No clear ownership
```

---

# 25. Step 14 – Remediation

Remediation addresses the causes and weaknesses identified during the investigation.

```text
ROOT CAUSE
     ↓
REMEDIATION PLAN
     ↓
CONTROL IMPROVEMENT
     ↓
IMPLEMENTATION
     ↓
VALIDATION
```

Actions may include:

```text
Patch Systems
Change Credentials
Improve MFA
Correct Configuration
Restrict Access
Improve Monitoring
Update Procedures
Improve Training
Strengthen Supplier Controls
```

---

# 26. Remediation Tracking

GRC can manage remediation as formal actions.

```text
FINDING
  ↓
ACTION
  ↓
OWNER
  ↓
DUE DATE
  ↓
STATUS
  ↓
EVIDENCE
  ↓
VALIDATION
  ↓
CLOSURE
```

This prevents remediation from being lost after the incident has been resolved operationally.

---

# 27. Step 15 – Recovery

After containment and remediation:

```text
CONTAINMENT
     ↓
REMEDIATION
     ↓
RECOVERY
     ↓
RESTORE NORMAL OPERATIONS
     ↓
MONITORING
```

Recovery may involve:

```text
System Restoration
Credential Restoration
Data Restoration
Service Validation
Security Monitoring
Business Validation
```

---

# 28. Post-Recovery Monitoring

Monitoring should continue after systems return to normal.

```text
RECOVERY
   ↓
ENHANCED MONITORING
   ↓
SUSPICIOUS ACTIVITY?
   ↓
YES → INVESTIGATE
NO  → NORMAL MONITORING
```

This helps detect whether the attacker or unauthorized activity remains present.

---

# 29. Step 16 – Lessons Learned

After the incident, the organization should conduct a structured review.

```text
INCIDENT CLOSED
      ↓
POST-INCIDENT REVIEW
      ↓
WHAT WORKED?
      ↓
WHAT FAILED?
      ↓
WHAT SHOULD CHANGE?
      ↓
IMPROVEMENT ACTIONS
```

The purpose is not merely to document the incident but to improve organizational resilience.

---

# 30. Lessons Learned Areas

The review may examine:

```text
Detection
Response Time
Containment
Communication
Decision-Making
Evidence Collection
Technology
Policies
Roles and Responsibilities
Third-Party Response
Regulatory Reporting
Customer Communication
```

---

# 31. Step 17 – Update Risk Register

The breach may reveal previously unidentified or underestimated risks.

```text
INCIDENT
   ↓
NEW INFORMATION
   ↓
RISK REASSESSMENT
   ↓
RISK REGISTER UPDATE
   ↓
NEW / UPDATED TREATMENT
```

This connects incident management directly with enterprise risk management.

---

# 32. Step 18 – Update Controls

The incident should also drive control improvements.

```text
INCIDENT
   ↓
CONTROL FAILURE
   ↓
CONTROL REVIEW
   ↓
CONTROL IMPROVEMENT
   ↓
CONTROL TESTING
   ↓
EFFECTIVENESS VALIDATION
```

For example:

```text
Weak Authentication
       ↓
MFA Implementation
       ↓
Configuration Review
       ↓
Access Testing
```

---

# 33. Breach and Control Effectiveness

A breach does not automatically mean that every control failed.

The organization should determine:

```text
Which Control Should Have Prevented It?
Which Control Should Have Detected It?
Which Control Should Have Limited It?
Which Control Should Have Supported Recovery?
```

This creates a useful control analysis:

```text
PREVENT
   ↓
DETECT
   ↓
CONTAIN
   ↓
RESPOND
   ↓
RECOVER
```

---

# 34. Breach and Three Lines Model

The response can involve all three lines:

```text
                 GOVERNING BODY
                       ↓
              ┌────────┴────────┐
              ↓                 ↓
          MANAGEMENT          INTERNAL AUDIT
              ↓                 ↓
       Operational Response    Independent
              ↓                 ↓
              └────────┬────────┘
                       ↓
                 ASSURANCE
```

The first line manages the incident operationally.

The second line may provide privacy, risk, security, and compliance oversight.

The third line can independently assess the response and control environment.

---

# 35. Breach and Third Parties

If a supplier is involved:

```text
THIRD-PARTY INCIDENT
        ↓
SUPPLIER NOTIFICATION
        ↓
ORGANIZATION TRIAGE
        ↓
DATA IMPACT ASSESSMENT
        ↓
CONTRACTUAL REVIEW
        ↓
REGULATORY ASSESSMENT
        ↓
RESPONSE
```

The organization should understand what information the supplier had access to and what contractual obligations apply.

---

# 36. Breach and Cloud Environment

A cloud incident may require investigation across several layers.

```text
CLOUD INCIDENT
      ↓
APPLICATION
      ↓
IDENTITY
      ↓
NETWORK
      ↓
STORAGE
      ↓
LOGGING
      ↓
PERSONAL DATA
```

The response should establish:

```text
What happened?
Which cloud service?
Which account?
Which resources?
Which data?
Who accessed it?
When?
What controls were bypassed?
```

---

# 37. Breach and AI Systems

AI systems can introduce additional breach considerations.

```text
AI SYSTEM
   ↓
INPUT DATA
   ↓
PROCESSING
   ↓
MODEL / PLATFORM
   ↓
OUTPUT
   ↓
STORAGE
```

Potential incident scenarios include:

```text
Sensitive Data Entered Into AI System
Unauthorized AI Access
Data Leakage Through Output
Third-Party AI Provider Incident
Improper Retention
Unauthorized Model Training
```

The response should therefore include AI-specific data flows where applicable.

---

# 38. Breach Evidence and GRC

Evidence should support the complete response lifecycle.

```text
INCIDENT
   ↓
DETECTION EVIDENCE
   ↓
INVESTIGATION EVIDENCE
   ↓
RISK ASSESSMENT
   ↓
NOTIFICATION DECISION
   ↓
REMEDIATION EVIDENCE
   ↓
CLOSURE EVIDENCE
```

Examples include:

```text
Incident Tickets
Logs
Forensic Reports
Risk Assessments
Legal Reviews
Notification Records
Management Approvals
Remediation Evidence
Testing Results
```

---

# 39. Breach and Audit Trail

A mature GRC environment should provide traceability:

```text
INCIDENT
   ↓
CASE
   ↓
RISK
   ↓
CONTROL
   ↓
FINDING
   ↓
REMEDIATION
   ↓
EVIDENCE
   ↓
APPROVAL
   ↓
CLOSURE
```

This allows an auditor to reconstruct what happened and how the organization responded.

---

# 40. Data Breach Risk Matrix

Organizations may use a structured risk assessment.

| Factor                | Low     | Medium      | High             |
| --------------------- | ------- | ----------- | ---------------- |
| Data Sensitivity      | Basic   | Sensitive   | Highly Sensitive |
| Number of Individuals | Small   | Moderate    | Large            |
| Exposure              | Limited | Significant | Extensive        |
| Misuse Potential      | Low     | Moderate    | High             |
| Individual Harm       | Low     | Moderate    | Severe           |
| Regulatory Exposure   | Low     | Moderate    | High             |

The actual scoring methodology should be defined by the organization's approved privacy and risk framework.

---

# 41. Breach Severity Classification

A practical internal classification might be:

```text
LEVEL 1 – Low
Limited data / limited impact

LEVEL 2 – Moderate
Meaningful exposure / manageable impact

LEVEL 3 – High
Significant personal-data exposure

LEVEL 4 – Critical
Large-scale or severe potential impact
```

Severity classification can determine escalation requirements.

---

# 42. Escalation Flow

A simplified escalation model is:

```text
INCIDENT
   ↓
INITIAL SEVERITY
   ↓
LOW ─────────→ Business Response
   ↓
MEDIUM ──────→ Privacy + Security
   ↓
HIGH ────────→ Executive Escalation
   ↓
CRITICAL ────→ Crisis Management
```

The actual thresholds should be defined in the organization's incident-response plan.

---

# 43. Executive Decision Points

Executives may need to make decisions regarding:

```text
Business Continuity
Customer Communication
Regulatory Engagement
Legal Strategy
External Support
Resource Allocation
Risk Acceptance
Public Communication
```

A simplified model:

```text
FACTS
 ↓
RISK
 ↓
OPTIONS
 ↓
EXECUTIVE DECISION
 ↓
ACTION
```

---

# 44. Breach Response Metrics

Management can monitor response performance through metrics such as:

```text
Mean Time to Detect
Mean Time to Contain
Mean Time to Assess
Mean Time to Notify
Number of Affected Individuals
Number of Incidents
Repeat Incidents
Open Remediation Actions
Overdue Actions
Control Failures
```

Example:

```text
Detection Time          45 min
Containment Time        2 hrs
Assessment Time         6 hrs
Open Actions            7
Repeat Control Failures 2
```

These values are illustrative.

---

# 45. Data Breach Response Dashboard

A GRC dashboard could present:

```text
DATA BREACH DASHBOARD

Open Incidents              3
High Severity               1
Under Investigation         2
Affected Individuals     2,450
Regulatory Assessments      2
Open Remediation Actions    8
Overdue Actions             2
```

The dashboard should allow management to drill down from metrics to incidents, risks, controls, and evidence.

---

# 46. Complete Data Breach Response Model

The end-to-end process can be represented as:

```text
                     INCIDENT DETECTED
                            ↓
                       INITIAL TRIAGE
                            ↓
                  PERSONAL DATA INVOLVED?
                       ↙           ↘
                     NO             YES
                     ↓               ↓
              SECURITY RESPONSE   CONTAINMENT
                                     ↓
                              EVIDENCE PRESERVATION
                                     ↓
                                INVESTIGATION
                                     ↓
                            DATA IDENTIFICATION
                                     ↓
                            IMPACT ASSESSMENT
                                     ↓
                           REGULATORY ASSESSMENT
                                     ↓
                           NOTIFICATION DECISION
                              ↙              ↘
                            YES               NO
                             ↓                 ↓
                      NOTIFICATION        DOCUMENT DECISION
                             ↓                 ↓
                             └────────┬────────┘
                                      ↓
                                  REMEDIATION
                                      ↓
                                    RECOVERY
                                      ↓
                              POST-INCIDENT REVIEW
                                      ↓
                               LESSONS LEARNED
                                      ↓
                             RISK / CONTROL UPDATE
                                      ↓
                                 MONITORING
                                      ↺
```

---

# 47. Integrated Privacy, Security and GRC Model

A mature organization can integrate the response functions:

```text
                       DATA BREACH
                            ↓
              ┌─────────────┼─────────────┐
              ↓             ↓             ↓
          SECURITY        PRIVACY        LEGAL
              ↓             ↓             ↓
              └─────────────┼─────────────┘
                            ↓
                       RISK ASSESSMENT
                            ↓
                       COMPLIANCE
                            ↓
                     NOTIFICATION
                            ↓
                       REMEDIATION
                            ↓
                        RECOVERY
                            ↓
                    LESSONS LEARNED
                            ↓
                 CONTROL IMPROVEMENT
                            ↓
                       ASSURANCE
```

This model demonstrates why data breach management should not be treated solely as an IT security function.

---

# 48. Executive-Level Data Breach Flow

For senior management, the complete process can be simplified to:

```text
WHAT HAPPENED?
      ↓
WHAT DATA IS AFFECTED?
      ↓
WHO MAY BE AFFECTED?
      ↓
HOW SERIOUS IS THE RISK?
      ↓
WHAT HAVE WE DONE TO CONTAIN IT?
      ↓
DO WE HAVE A NOTIFICATION OBLIGATION?
      ↓
WHAT MUST WE FIX?
      ↓
HOW DO WE PREVENT RECURRENCE?
```

This gives executives the information required for informed decision-making without overwhelming them with technical details.

---

# 49. Key GRC Principles

A mature data breach response process should:

```text
1. Detect incidents quickly.
2. Determine whether personal data is involved.
3. Activate the appropriate response functions.
4. Contain the incident.
5. Preserve relevant evidence.
6. Establish the facts and timeline.
7. Identify affected data and individuals.
8. Assess potential harm and risk.
9. Determine applicable notification obligations.
10. Document important decisions.
11. Remediate the underlying weaknesses.
12. Recover affected services.
13. Update risks and controls.
14. Capture lessons learned.
15. Continuously improve the response capability.
```

The central GRC principle is:

> **A data breach should be managed as both a security incident and a governance, risk, compliance, and accountability event when personal data is involved.**

---

# 50. Final Integrated Model

The complete Data Breach Response Flow can be summarized as:

```text
                         DATA BREACH
                              ↓
                         DETECTION
                              ↓
                          TRIAGE
                              ↓
                       CONTAINMENT
                              ↓
                    EVIDENCE PRESERVATION
                              ↓
                       INVESTIGATION
                              ↓
                  PERSONAL DATA IDENTIFICATION
                              ↓
                      INDIVIDUAL IMPACT
                              ↓
                    ORGANIZATIONAL IMPACT
                              ↓
                    REGULATORY ASSESSMENT
                              ↓
                   NOTIFICATION DECISION
                              ↓
                       REMEDIATION
                              ↓
                         RECOVERY
                              ↓
                    LESSONS LEARNED
                              ↓
                 RISK AND CONTROL UPDATE
                              ↓
                         ASSURANCE
                              ↓
                       MONITORING
                              ↺
```

The ultimate objective is not simply to **close the incident**. A mature GRC organization uses the incident to improve its **privacy risk profile, control environment, regulatory compliance, security capabilities, accountability, and organizational resilience**.


