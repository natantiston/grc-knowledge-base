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


