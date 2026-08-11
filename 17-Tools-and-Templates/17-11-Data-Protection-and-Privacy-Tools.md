**17.11 Data Protection and Privacy Tools**

**Part 1 – Data Inventory and Processing Register**

A Data Inventory and Processing Register is a practical GRC tool used to identify, document, classify, and monitor the information an organization collects, stores, processes, transfers, and shares.

From a GRC perspective, the purpose is not simply to create a list of databases or applications. The objective is to establish visibility over **what data exists, where it is located, why it is processed, who can access it, who it is shared with, how long it is retained, and what risks and compliance obligations apply to it**.

This information provides an important foundation for information security, privacy management, risk assessment, regulatory compliance, data classification, third-party risk management, incident response, and business continuity.

A practical Data Inventory and Processing Register can contain:

```text
DATA INVENTORY AND PROCESSING REGISTER

Record ID:

Business Process:

Data Asset:

Data Owner:

Data Steward:

System / Application:

Data Category:

Data Classification:

Data Subject:

Purpose of Processing:

Legal Basis:

Data Elements:

Sensitive Data:

Personal Data:

Volume of Data:

Data Location:

Storage Location:

Processing Location:

Data Flow:

Internal Users:

External Recipients:

Third Parties / Subprocessors:

Cross-Border Transfer:

Retention Period:

Disposal Method:

Security Controls:

Access Controls:

Encryption:

Backup:

Monitoring:

Privacy Requirements:

Regulatory Requirements:

Business Criticality:

Risk Rating:

Data Breach Impact:

Last Review Date:

Next Review Date:

Record Status:

Comments:
```

The first field should provide a unique **Record ID**.

For example:

```text
DPI-2026-001
DPI-2026-002
DPI-2026-003
```

The identifier allows the organization to track each processing activity or data asset throughout its lifecycle.

The register should identify the **business process** associated with the data.

Examples include:

```text
Human Resources
Recruitment
Payroll
Customer Management
Marketing
Sales
Customer Support
Finance
Procurement
Information Technology
Security Operations
```

This is important because data should be understood in its business context.

For example:

```text
Business Process:
Employee Recruitment

Data Asset:
Candidate Information

Purpose:
Evaluation and management of job applications
```

The organization should identify the **data asset** itself.

A data asset could be:

```text
Customer Database
Employee Records
Supplier Records
Marketing Database
Financial Records
Security Logs
Email Records
Application Data
Authentication Records
Backup Data
```

The register should identify the **data owner**.

The data owner is normally responsible for determining how the data should be used, protected, retained, and managed.

For example:

```text
Data Owner:
Human Resources Director
```

The organization may also identify a **data steward**.

The data steward may be responsible for operational management of the data.

For example:

```text
Data Owner:
HR Director

Data Steward:
HR Operations Manager
```

Separating ownership from operational stewardship can improve accountability.

The register should identify the **system or application** where the data is processed.

For example:

```text
System:
Workday

Database:
Employee HR Database

Supporting Systems:
Identity Management
Payroll System
Document Management Platform
```

This creates a connection between data governance and technology assets.

The register should identify the **data category**.

For example:

```text
Customer Data
Employee Data
Financial Data
Operational Data
Security Data
Supplier Data
Marketing Data
Technical Data
```

The organization should then apply its approved **data classification**.

A typical classification model may include:

```text
Public
Internal
Confidential
Restricted
```

For example:

```text
Data:
Employee Salary Information

Classification:
Restricted
```

Classification should be based on the potential impact of unauthorized disclosure, alteration, loss, or destruction.

The register should identify the **data subjects** where personal data is involved.

Examples include:

```text
Employees
Customers
Job Applicants
Suppliers
Contractors
Website Visitors
Business Contacts
```

For example:

```text
Data Subject:
Employees

Data:
Employee Name
Employee ID
Salary
Bank Account
Contact Information
```

The register should document the **purpose of processing**.

The purpose should be specific rather than vague.

A weak description would be:

```text
Business operations.
```

A stronger description would be:

```text
Processing employee information for payroll
calculation, salary payment, tax reporting,
and statutory employment administration.
```

Purpose documentation is important because data should not be collected or processed without a legitimate and defined business or legal purpose.

Where personal data is involved, the register should document the applicable **legal basis** where required.

For example:

```text
Contract
Legal Obligation
Legitimate Interests
Consent
Vital Interests
Public Task
```

The appropriate legal basis depends on the applicable privacy law and the specific processing activity.

The register should identify the **data elements** being processed.

For example:

```text
Employee Name
Date of Birth
Home Address
Email Address
Telephone Number
Employee Number
Salary
Bank Account
Tax Information
Employment History
```

This provides greater visibility than simply recording "employee data."

The organization should identify whether the processing involves **sensitive or special-category information**.

Examples may include:

```text
Health Information
Biometric Information
Genetic Information
Religious Information
Political Information
Trade Union Information
Criminal Record Information
```

The exact classification and legal treatment should follow applicable law.

The register should record the **volume of data** where this information is relevant to risk assessment.

For example:

```text
Number of Records:
250,000 Customer Records

Annual Growth:
Approximately 30,000 Records
```

Large volumes of personal or sensitive information may increase the potential impact of a security or privacy incident.

The register should identify the **data location**.

For example:

```text
Primary Location:
Madrid, Spain

Backup Location:
Frankfurt, Germany
```

For cloud services, the organization should distinguish between the logical service and the physical or geographic location of data processing where relevant.

The register should identify the **processing location**.

For example:

```text
Data Storage:
Germany

Customer Support Processing:
Ireland

Technical Support:
United States
```

This can help identify international data transfer and regulatory considerations.

The register should document the **data flow**.

A simple data flow can be represented as:

```text
Customer
   ↓
Website
   ↓
Customer Application
   ↓
CRM Platform
   ↓
Cloud Database
   ↓
Customer Support Provider
```

The data flow should identify where information moves between systems, business units, countries, and third parties.

A more detailed record may show:

```text
Collection:
Website

Processing:
CRM Platform

Storage:
Cloud Database

Sharing:
Customer Support Provider

Backup:
Cloud Backup Platform

Deletion:
Automated Retention Process
```

Data-flow visibility is particularly important when assessing privacy, cybersecurity, third-party, and cross-border risks.

The register should identify **internal users**.

For example:

```text
Customer Service
Sales
Finance
Marketing
Security Operations
System Administrators
```

Access should be based on business need and least privilege.

The register should also identify **external recipients**.

For example:

```text
Payment Processor
Cloud Service Provider
Marketing Provider
Customer Support Provider
Regulatory Authority
Government Agency
```

The organization should document why data is shared with each recipient.

The register should identify **third parties and subprocessors**.

For example:

```text
Primary Vendor:
ABC SaaS Provider

Subprocessor:
XYZ Cloud Hosting Provider

Additional Service:
Email Delivery Provider
```

This provides a connection between privacy management and third-party risk management.

The register should identify whether **cross-border transfers** occur.

For example:

```text
Cross-Border Transfer:
Yes

Origin:
Spain

Destination:
United States

Purpose:
Technical Support

Transfer Mechanism:
Applicable contractual and legal safeguards
```

The exact transfer mechanism should be determined by the organization's privacy and legal teams based on applicable law.

The register should document the **retention period**.

For example:

```text
Active Customer Records:
Duration of Customer Relationship

Inactive Records:
7 Years

Security Logs:
12 Months
```

Retention should be based on legal, regulatory, contractual, operational, and business requirements.

The principle should be:

```text
Keep Data:
Only as long as required.
```

The register should also identify the **disposal method**.

Examples include:

```text
Secure Deletion
Database Deletion
Cryptographic Erasure
Media Destruction
Document Shredding
Anonymization
```

For example:

```text
Retention Period:
7 Years

Disposal Method:
Secure Digital Deletion
```

The register should document the **security controls** protecting the data.

For example:

```text
Access Control
MFA
Encryption
Data Loss Prevention
Security Monitoring
Vulnerability Management
Backup
Network Segmentation
Logging
```

Controls should be linked to the organization's security framework where appropriate.

For example:

```text
ISO/IEC 27001 Control:
Access Control

Internal Control:
Role-Based Access Management

Evidence:
Quarterly Access Review
```

The register should identify **access controls**.

For example:

```text
Role-Based Access
Least Privilege
MFA
Privileged Access Management
Periodic Access Reviews
Access Revocation
```

The organization should identify who can access the data and why.

For example:

```text
Data:
Customer Financial Information

Authorized Users:
Finance
Customer Support

Privileged Access:
Database Administrators

External Access:
Approved Payment Processor
```

The register should document whether the data is **encrypted**.

For example:

```text
Encryption at Rest:
Yes

Encryption in Transit:
Yes

Key Management:
Centralized Key Management System
```

Encryption should be evaluated together with access control, key management, and other security measures.

The register should identify whether the data is included in **backup processes**.

For example:

```text
Backup:
Yes

Backup Frequency:
Daily

Backup Retention:
90 Days

Backup Encryption:
Yes

Recovery Testing:
Quarterly
```

This connects data protection with business continuity and disaster recovery.

The register should identify relevant **monitoring controls**.

For example:

```text
Security Logging
Access Monitoring
Database Activity Monitoring
Data Loss Prevention
Security Information and Event Management
```

Monitoring should be proportionate to the sensitivity and risk associated with the data.

The register should identify applicable **privacy requirements**.

For example:

```text
GDPR
National Data Protection Requirements
Contractual Privacy Requirements
Industry-Specific Privacy Requirements
```

The organization should identify which requirements apply to the specific processing activity rather than simply listing every regulation.

The register should also identify relevant **regulatory requirements**.

For example:

```text
GDPR
NIS2
DORA
PCI DSS
Employment Regulations
Financial Regulations
```

The exact requirements depend on the organization, industry, jurisdiction, and processing activity.

The register should document the **business criticality** of the data.

For example:

```text
Critical
High
Medium
Low
```

A loss of availability of critical data may have significant operational consequences even when confidentiality is not the primary concern.

The organization should also assess the **risk rating** associated with the processing activity.

For example:

```text
Likelihood:
Possible

Impact:
Major

Risk:
High
```

Risk assessment may consider:

```text
Data Sensitivity
Data Volume
Number of Data Subjects
External Sharing
Cross-Border Transfers
System Criticality
Access Privileges
Threat Exposure
Regulatory Impact
```

The register should also capture the potential **data breach impact**.

For example:

```text
Potential Impact:

Unauthorized disclosure of customer
personal information could result in
regulatory penalties, customer harm,
reputational damage, and financial loss.
```

This information can support privacy impact assessments and incident response planning.

A practical completed record may look like:

```text
DATA INVENTORY RECORD

Record ID:
DPI-2026-015

Business Process:
Customer Account Management

Data Asset:
Customer Profile Database

Data Owner:
Head of Customer Operations

Data Steward:
CRM Manager

System:
Customer Relationship Management Platform

Data Category:
Customer Data

Classification:
Confidential

Data Subjects:
Customers

Purpose:
Managing customer accounts, service requests,
communications, and customer support.

Data Elements:
Name
Email
Telephone Number
Customer ID
Service Information
Support History

Sensitive Data:
No Special-Category Data

Data Volume:
Approximately 500,000 Records

Storage Location:
European Union

Processing Location:
European Union

External Recipients:
Customer Support Provider

Subprocessor:
Cloud Infrastructure Provider

Cross-Border Transfer:
No

Retention:
Duration of Customer Relationship
plus applicable statutory retention period

Disposal:
Secure Digital Deletion

Security Controls:
MFA
Role-Based Access
Encryption
Logging
Monitoring
Backup

Business Criticality:
High

Risk Rating:
Medium

Last Review:
August 2026

Next Review:
August 2027

Status:
Active
```

The register should be reviewed periodically.

A review may be triggered by:

```text
New System
New Business Process
New Data Type
New Data Subject Category
New Vendor
New Subprocessor
New Country
New Regulation
Major System Change
Security Incident
Privacy Incident
Change in Retention Requirements
```

The GRC professional should avoid treating the register as a static document.

Data environments change continuously. New applications are introduced, vendors change, data is transferred to new locations, business processes evolve, and regulatory requirements change.

The register should therefore be integrated into the organization's change management and third-party risk management processes.

A mature data inventory can connect:

```text
Business Process
        ↓
Data Asset
        ↓
System / Application
        ↓
Data Owner
        ↓
Data Classification
        ↓
Processing Purpose
        ↓
Data Flow
        ↓
Third Parties
        ↓
Security Controls
        ↓
Privacy Requirements
        ↓
Risk Assessment
        ↓
Retention
        ↓
Secure Disposal
```

The register can also serve as a source for other GRC activities.

For example:

```text
Data Inventory
      ↓
Data Classification
      ↓
PIA / DPIA
      ↓
Privacy Risk Assessment
      ↓
Security Controls
      ↓
Third-Party Assessment
      ↓
Compliance Assessment
      ↓
Incident Response
      ↓
Audit Evidence
```

A well-maintained Data Inventory and Processing Register provides the organization with a practical answer to one of the most fundamental GRC questions:

**What information do we have, where is it processed, why do we process it, who has access to it, and how are we protecting it?**

The key principle is:

> **An effective Data Inventory and Processing Register provides a structured and continuously maintained view of organizational data, its processing activities, ownership, classification, locations, recipients, protection measures, retention requirements, and associated risks, creating a foundation for effective privacy, security, compliance, and data governance.**

**Part 2 – Data Classification Template**

Data classification is the process of assigning a defined security classification to information based on its sensitivity, business value, regulatory requirements, and the potential impact of unauthorized disclosure, modification, loss, or destruction.

A practical data classification framework allows an organization to determine how information should be handled throughout its lifecycle.

A typical classification model may contain four levels:

```text
PUBLIC
Information approved for public disclosure.

INTERNAL
Information intended for internal organizational
use and not normally approved for public disclosure.

CONFIDENTIAL
Information that could cause significant harm,
business disruption, financial loss, or reputational
damage if disclosed without authorization.

RESTRICTED
Highly sensitive information requiring the strongest
protection because unauthorized disclosure, alteration,
or loss could cause severe legal, financial, operational,
privacy, or security consequences.
```

The classification should be based on the potential impact of compromise rather than simply the type of document.

For example:

```text
Information:
Public Annual Report

Classification:
Public
```

The same organization may have:

```text
Information:
Internal Security Procedure

Classification:
Internal
```

And:

```text
Information:
Customer Contract

Classification:
Confidential
```

And:

```text
Information:
Customer Payment Information

Classification:
Restricted
```

A practical Data Classification Template can contain:

```text
DATA CLASSIFICATION TEMPLATE

Record ID:

Data Asset:

Business Process:

Data Owner:

Data Steward:

Data Description:

Data Type:

Data Subject:

Confidentiality:

Integrity:

Availability:

Regulatory Sensitivity:

Privacy Sensitivity:

Business Impact:

Classification:

Classification Justification:

Authorized Users:

Access Restrictions:

Storage Requirements:

Transmission Requirements:

Encryption Requirements:

Sharing Requirements:

Printing Requirements:

Backup Requirements:

Retention Period:

Disposal Requirements:

Third-Party Access:

Security Monitoring:

Classification Review Date:

Next Review Date:

Approved By:

Status:

Comments:
```

The first step is to identify the **data asset**.

For example:

```text
Data Asset:
Employee Personnel Records
```

The organization should describe what information is included.

For example:

```text
Data Description:

Employee identification information,
employment records, salary information,
benefits information, and related HR records.
```

The register should identify the **data owner**.

For example:

```text
Data Owner:
Human Resources Director
```

The data owner is normally responsible for determining the appropriate classification and approving changes to that classification.

The organization may also identify a **data steward**.

For example:

```text
Data Steward:
HR Operations Manager
```

The data steward may manage the data operationally while the data owner retains overall accountability.

Classification should consider the **confidentiality** of information.

Confidentiality asks:

> What would happen if unauthorized individuals gained access to this information?

For example:

```text
Confidentiality Impact:
Low

Potential Impact:
Limited inconvenience
```

Or:

```text
Confidentiality Impact:
High

Potential Impact:
Regulatory penalties,
customer harm,
reputational damage,
financial loss.
```

The classification process should also consider **integrity**.

Integrity asks:

> What would happen if the information were modified, corrupted, or manipulated without authorization?

For example:

```text
Data:
Financial Transaction Records

Integrity Impact:
Critical
```

Unauthorized modification could result in incorrect financial transactions, reporting errors, regulatory issues, or financial losses.

The organization should also consider **availability**.

Availability asks:

> What would happen if the information became unavailable when required?

For example:

```text
Data:
Customer Service Records

Availability Impact:
High
```

If the information is unavailable, customer service operations may be significantly disrupted.

A useful approach is therefore:

```text
Confidentiality
       +
Integrity
       +
Availability
       ↓
Overall Information Risk
       ↓
Data Classification
```

The organization should also consider **regulatory sensitivity**.

For example:

```text
Regulatory Sensitivity:

GDPR
Financial Regulation
Healthcare Regulation
Payment Card Requirements
Employment Requirements
Contractual Requirements
```

Information subject to specific regulatory requirements may require stronger protection.

The organization should consider **privacy sensitivity** where personal information is involved.

For example:

```text
Personal Data:
Yes

Special-Category / Highly Sensitive Data:
Yes

Privacy Sensitivity:
High
```

Examples of potentially highly sensitive information include:

```text
Health Information
Biometric Information
Financial Information
Authentication Information
Government Identification
Genetic Information
```

The exact classification should follow applicable legal and organizational requirements.

The organization should assess the **business impact** of unauthorized disclosure, modification, or loss.

For example:

```text
Business Impact:
Severe
```

Potential impacts may include:

```text
Financial Loss
Regulatory Penalties
Operational Disruption
Legal Exposure
Customer Harm
Reputational Damage
Loss of Competitive Advantage
```

The classification decision should be based on the overall risk.

For example:

```text
Data:
Customer Payment Information

Confidentiality:
Very High

Integrity:
High

Availability:
High

Regulatory Sensitivity:
High

Privacy Sensitivity:
High

Business Impact:
Severe

Classification:
Restricted
```

The organization should document the **classification justification**.

A weak justification would be:

```text
Sensitive information.
```

A stronger justification would be:

```text
The dataset contains customer financial and
personal information. Unauthorized disclosure
could result in customer harm, regulatory
exposure, financial loss, and reputational damage.
The information is therefore classified as Restricted.
```

This creates an auditable basis for the classification decision.

The organization should define **handling requirements** for each classification level.

For example:

```text
PUBLIC

Access:
No restriction

Sharing:
Publicly approved

Encryption:
Based on system requirements

Printing:
Permitted

Disposal:
Standard disposal
```

For Internal information:

```text
INTERNAL

Access:
Employees and authorized contractors

Sharing:
Internal business purposes

Encryption:
Based on risk and system requirements

Printing:
Controlled

Disposal:
Secure organizational disposal
```

For Confidential information:

```text
CONFIDENTIAL

Access:
Authorized personnel only

Sharing:
Business need and authorization

Encryption:
Required where appropriate

Printing:
Controlled

Disposal:
Secure disposal

External Sharing:
Requires authorization
```

For Restricted information:

```text
RESTRICTED

Access:
Strictly authorized personnel

Sharing:
Explicit authorization required

Encryption:
Required

MFA:
Required where applicable

Printing:
Strongly restricted

Disposal:
Secure destruction or approved deletion

External Sharing:
Formal authorization required
```

The organization should define **authorized users**.

For example:

```text
Data:
Employee Payroll Information

Authorized Users:

Payroll Team
HR Management
Finance
Approved Payroll Provider
```

Access should follow least privilege.

Not every employee in the HR department necessarily needs access to every payroll record.

The template should define **access restrictions**.

For example:

```text
Access Restrictions:

Role-Based Access
Least Privilege
MFA
Privileged Access Management
Quarterly Access Review
```

Higher classifications should normally require stronger access controls.

The organization should define **storage requirements**.

For example:

```text
Restricted Data:

Must be stored only in approved systems.
Must not be stored on unauthorized personal
devices or removable media.
```

The organization may also define approved storage locations.

For example:

```text
Approved:

Corporate File Platform
Approved Cloud Storage
Approved Business Applications

Not Approved:

Personal Cloud Storage
Personal Email
Unmanaged Devices
Unauthorized USB Media
```

The template should address **transmission requirements**.

For example:

```text
Public:
No special restriction.

Internal:
Approved organizational communication channels.

Confidential:
Approved secure communication channels.

Restricted:
Encrypted transmission using approved mechanisms.
```

The organization should define **encryption requirements**.

For example:

```text
Classification     At Rest      In Transit

Public             Optional     Standard
Internal           Risk-Based   Protected
Confidential       Required     Encrypted
Restricted         Required     Strong Encryption
```

The exact technical standards should be defined by the organization's security architecture.

The template should define **sharing requirements**.

For example:

```text
Public:
Approved for public distribution.

Internal:
Internal business use.

Confidential:
Authorization required before external sharing.

Restricted:
Formal authorization and approved secure
transfer mechanism required.
```

The organization should also consider **third-party sharing**.

For example:

```text
Data:
Customer Personal Data

Third Party:
Customer Support Provider

Requirements:

Approved Contract
Data Processing Agreement
Security Assessment
Access Restrictions
Secure Transfer
Retention Requirements
```

This connects data classification with third-party risk management.

The template should define **printing requirements**.

For example:

```text
Public:
No restriction.

Internal:
Controlled printing.

Confidential:
Secure printing and controlled distribution.

Restricted:
Printing should be minimized and strictly controlled.
```

The organization may also require secure disposal of printed materials.

For example:

```text
Confidential / Restricted:

Cross-cut shredding
Secure document destruction
Approved document disposal provider
```

The template should define **backup requirements**.

For example:

```text
Restricted Data:

Encrypted Backup
Access-Controlled Backup
Defined Retention
Regular Recovery Testing
Protection Against Unauthorized Deletion
```

Backup data should normally retain an appropriate level of protection consistent with the original information.

The organization should define **retention requirements**.

For example:

```text
Data:
Employee Records

Retention:
According to applicable legal,
regulatory, and organizational requirements.
```

Classification alone should not determine retention.

Retention should be based on:

```text
Legal Requirements
Regulatory Requirements
Contractual Requirements
Business Requirements
Privacy Requirements
Litigation Requirements
```

The template should define **disposal requirements**.

For example:

```text
Public:
Standard Disposal

Internal:
Approved Disposal

Confidential:
Secure Disposal

Restricted:
Secure Destruction or Approved Secure Deletion
```

Digital disposal may include:

```text
Secure Deletion
Cryptographic Erasure
Media Destruction
System Decommissioning
```

The organization should document **third-party access**.

For example:

```text
Data Classification:
Confidential

Third-Party Access:
Allowed

Conditions:

Contractual Authorization
Security Assessment
Least Privilege
MFA
Monitoring
Data Retention Controls
```

For Restricted data, additional approval may be required.

The template should also identify **security monitoring**.

For example:

```text
Restricted Data:

Access Logging
Privileged Activity Monitoring
Security Alerting
Data Loss Prevention
Database Monitoring
```

Monitoring should be proportional to the sensitivity of the information.

A practical classification decision may look like:

```text
DATA CLASSIFICATION RECORD

Record ID:
DC-2026-008

Data Asset:
Customer Payment Information

Data Owner:
Finance Director

Data Steward:
Payment Operations Manager

Data Type:
Financial / Personal Data

Confidentiality:
Very High

Integrity:
High

Availability:
High

Regulatory Sensitivity:
High

Privacy Sensitivity:
High

Business Impact:
Severe

Classification:
Restricted

Justification:

The data contains financial and personal
information. Unauthorized disclosure or
modification could result in customer harm,
financial loss, regulatory consequences,
and reputational damage.

Authorized Users:
Finance
Payment Operations
Approved Payment Provider

Access Controls:
RBAC
MFA
Privileged Access Management
Quarterly Access Review

Encryption:
Required

External Sharing:
Restricted and authorized

Retention:
According to approved retention schedule

Disposal:
Secure deletion

Review Frequency:
Annual

Status:
Approved
```

Organizations should establish **classification labels** that are easy for employees and systems to recognize.

For example:

```text
PUBLIC
INTERNAL
CONFIDENTIAL
RESTRICTED
```

Labels may be displayed in:

```text
Documents
Emails
File Names
Document Headers
Document Footers
Collaboration Platforms
Data Repositories
```

For example:

```text
CONFIDENTIAL

Customer Security Assessment
ABC Corporation
August 2026
```

The organization may also use automated labeling capabilities.

For example:

```text
Data Discovery
       ↓
Sensitive Data Detection
       ↓
Classification Recommendation
       ↓
User / Data Owner Validation
       ↓
Classification Label
       ↓
Security Controls
```

Automation can help identify information that may require additional protection, but classification decisions should be governed appropriately.

The organization should define **classification ownership**.

A typical model could be:

```text
Data Owner:
Determines and approves classification.

Data Steward:
Maintains classification operationally.

Information Security:
Defines security requirements.

Privacy:
Provides privacy requirements.

GRC:
Provides governance and oversight.

IT:
Implements technical controls.

Users:
Handle information according to classification.
```

The organization should provide clear instructions to employees.

For example:

```text
If you create new information:

1. Identify the data.
2. Determine its sensitivity.
3. Apply the appropriate classification.
4. Store it in an approved location.
5. Share it only with authorized recipients.
6. Protect it according to classification.
7. Retain it only as long as required.
8. Dispose of it securely.
```

Classification should also apply to information received from third parties.

For example:

```text
Supplier Information:
Confidential

Customer Contract:
Confidential

Security Assessment:
Restricted
```

The organization should not assume that only internally generated information requires classification.

Classification should also be considered during **system development and procurement**.

Before implementing a new application, the organization should determine:

```text
What data will the system process?

What classification will apply?

Who will access it?

Where will it be stored?

Will it be shared externally?

Will it cross borders?

What security controls are required?
```

This allows classification to influence security architecture and procurement decisions.

Classification should also connect to **access control**.

For example:

```text
Classification
      ↓
Access Requirements
      ↓
Authentication Requirements
      ↓
Encryption Requirements
      ↓
Monitoring Requirements
      ↓
Retention Requirements
      ↓
Disposal Requirements
```

This makes classification an operational security mechanism rather than simply a label.

The classification should be reviewed when significant changes occur.

Triggers may include:

```text
New Data Elements
New Business Purpose
New System
New Vendor
New Data Location
New Regulatory Requirement
Change in Business Criticality
Change in Data Sensitivity
Security Incident
Privacy Incident
```

For example:

```text
Original Classification:
Internal

Change:
Customer personal information added.

New Classification:
Confidential
```

Classification may therefore increase or decrease over time.

The organization should maintain a **classification review history**.

For example:

```text
01 January 2026:
Classification – Internal

15 June 2026:
Customer personal data added.

15 June 2026:
Classification changed to Confidential.

Reviewer:
Data Owner
```

This provides an auditable record.

A mature classification process should connect:

```text
Data Inventory
       ↓
Data Classification
       ↓
Security Requirements
       ↓
Privacy Requirements
       ↓
Access Controls
       ↓
Third-Party Controls
       ↓
Retention
       ↓
Secure Disposal
```

The classification template can also be integrated with GRC platforms, data governance platforms, document management systems, and information protection technologies.

For example:

```text
Data Asset
     ↓
Classification
     ↓
Risk Rating
     ↓
Control Requirements
     ↓
Evidence
     ↓
Compliance Assessment
```

The ultimate objective is not to classify every piece of information manually without purpose. The objective is to ensure that information receives **proportionate protection based on its sensitivity and business or regulatory impact**.

The key principle is:

> **Data classification provides the foundation for determining how information should be accessed, stored, transmitted, shared, monitored, retained, and securely disposed of based on its sensitivity, business value, regulatory requirements, and potential impact if compromised.**

**Part 3 – Privacy Impact Assessment (PIA/DPIA) Template**

A Privacy Impact Assessment (PIA), commonly referred to as a Data Protection Impact Assessment (DPIA) in GDPR contexts, is a structured GRC assessment used to identify and evaluate privacy risks associated with the collection, use, storage, sharing, or other processing of personal data.

A PIA/DPIA should be performed early in the design of a new system, process, product, service, or technology that may create significant privacy risks. It should not be treated as a document completed only after the technology has already been implemented.

The assessment helps the organization determine:

```text
What personal data is being processed?

Why is the data being processed?

Who are the data subjects?

What systems and third parties are involved?

Where is the data stored and processed?

What privacy risks could arise?

What controls reduce those risks?

Are residual risks acceptable?

What additional actions are required?
```

A practical PIA/DPIA process can be represented as:

```text
New Processing Activity
        ↓
Initial Privacy Screening
        ↓
Determine Whether PIA/DPIA Is Required
        ↓
Describe Processing
        ↓
Identify Data and Data Subjects
        ↓
Assess Necessity and Proportionality
        ↓
Identify Privacy Risks
        ↓
Assess Risk
        ↓
Identify Controls
        ↓
Determine Residual Risk
        ↓
Define Remediation
        ↓
Approval
        ↓
Implementation
        ↓
Ongoing Review
```

A practical PIA/DPIA Template can contain:

```text
PRIVACY IMPACT ASSESSMENT / DPIA

Assessment ID:

Project / Processing Activity:

Business Owner:

Privacy Owner:

Data Protection Officer:

System / Application:

Processing Description:

Purpose of Processing:

Data Subjects:

Personal Data Categories:

Special-Category / Sensitive Data:

Data Sources:

Data Recipients:

Third Parties / Subprocessors:

Data Locations:

Processing Locations:

International Transfers:

Retention Period:

Legal Basis:

Data Subject Rights:

Automated Decision-Making:

Profiling:

Technology Used:

Processing Necessity:

Processing Proportionality:

Privacy Risks:

Risk Likelihood:

Risk Impact:

Inherent Privacy Risk:

Existing Controls:

Additional Controls:

Residual Privacy Risk:

Risk Treatment:

Action Owner:

Target Date:

DPO / Privacy Review:

Management Approval:

Regulatory Consultation Required:

Assessment Status:

Review Date:

Next Review Date:

Comments:
```

The first step is to identify the **project or processing activity** being assessed.

For example:

```text
Project:
AI-Powered Customer Support Platform

Processing Activity:
Use of customer information to provide
automated customer support.
```

The assessment should describe the proposed processing clearly enough that someone outside the project team can understand what will happen to the personal data.

The assessment should identify the **business owner**.

For example:

```text
Business Owner:
Director of Customer Operations
```

The business owner is responsible for explaining why the processing is required and how it supports the business objective.

The assessment should identify the **privacy owner** or responsible privacy function.

For example:

```text
Privacy Owner:
Privacy Manager
```

Where applicable, the organization's **Data Protection Officer (DPO)** should be involved according to its privacy governance model and applicable legal requirements.

The assessment should identify the **system or technology** involved.

For example:

```text
System:
Customer Support Platform

Technology:
Cloud SaaS

Supporting Technology:
AI Service
CRM
Identity Platform
Analytics Platform
```

This is particularly important for new technologies such as artificial intelligence, biometrics, cloud services, monitoring technologies, and automated decision-making systems.

The assessment should provide a clear **processing description**.

For example:

```text
Customer information is collected through
the organization's website and customer
service channels. The information is stored
in the customer management platform and
used by authorized customer service personnel
and an AI-enabled support service to respond
to customer requests.
```

The description should explain the data lifecycle.

For example:

```text
Collection
   ↓
Transmission
   ↓
Storage
   ↓
Processing
   ↓
Sharing
   ↓
Retention
   ↓
Deletion
```

The assessment should identify the **purpose of processing**.

The purpose should be specific.

For example:

```text
Purpose:

To provide customer support, resolve service
requests, maintain customer account information,
and improve customer service operations.
```

A vague purpose such as "business operations" does not provide sufficient context for evaluating privacy risk.

The assessment should identify the **data subjects**.

Examples include:

```text
Customers
Employees
Job Applicants
Children
Suppliers
Contractors
Website Visitors
Patients
Students
```

The organization should pay particular attention to vulnerable or high-risk groups where applicable.

The assessment should identify the **categories of personal data**.

For example:

```text
Name
Address
Email Address
Telephone Number
Customer ID
Account Information
Transaction History
Support Communications
Technical Information
```

The organization should identify whether **special-category or highly sensitive information** is processed.

For example:

```text
Health Information
Biometric Data
Genetic Data
Religious Information
Political Information
Trade Union Information
```

The exact treatment depends on the applicable legal framework.

The assessment should identify the **source of the data**.

For example:

```text
Customer
Website
Mobile Application
Call Center
CRM System
Third-Party Provider
Public Source
```

Understanding the source helps establish whether the organization is collecting the data directly or receiving it from another party.

The assessment should identify **data recipients**.

For example:

```text
Internal:
Customer Service
Finance
Security

External:
Cloud Provider
Payment Processor
Customer Support Provider
AI Service Provider
```

Each recipient should have a defined business and legal purpose for receiving the information.

The assessment should identify **third parties and subprocessors**.

For example:

```text
Primary Vendor:
Customer Support SaaS Provider

Subprocessor:
Cloud Infrastructure Provider

Additional Provider:
AI Processing Service
```

This information should align with the organization's third-party risk management process.

The assessment should identify **data storage locations**.

For example:

```text
Primary Storage:
Germany

Backup:
Netherlands
```

The organization should also identify where the data is actually processed.

For example:

```text
Storage:
European Union

Technical Support:
United States

AI Processing:
European Union
```

Storage location and processing location may be different and should not automatically be treated as the same.

The assessment should identify **international transfers**.

For example:

```text
International Transfer:
Yes

Origin:
Spain

Destination:
United States

Purpose:
Technical Support

Transfer Mechanism:
Applicable approved legal safeguards
```

The appropriate legal mechanism should be determined by the organization's privacy and legal functions.

The assessment should document the **retention period**.

For example:

```text
Customer Account Data:
Duration of Customer Relationship

Support Records:
Defined Retention Period

Security Logs:
Defined Security Retention Period
```

Retention should be justified by legal, regulatory, contractual, and business requirements.

The assessment should identify the **legal basis** where applicable.

Examples may include:

```text
Contract
Legal Obligation
Legitimate Interests
Consent
Public Task
Vital Interests
```

The organization should document why the selected legal basis applies to the specific processing activity.

Where consent is used, the organization should also consider whether consent is freely given, specific, informed, and capable of being withdrawn where required by applicable law.

The assessment should identify relevant **data subject rights**.

For example:

```text
Right of Access
Right to Rectification
Right to Erasure
Right to Restriction
Right to Data Portability
Right to Object
Rights Related to Automated Decision-Making
```

The organization should determine how these rights will be supported operationally.

For example:

```text
Customer Request
       ↓
Privacy Request Management
       ↓
Identity Verification
       ↓
Data Discovery
       ↓
Request Evaluation
       ↓
Response
       ↓
Record Retention
```

The assessment should determine whether the processing involves **automated decision-making**.

For example:

```text
Automated Decision-Making:
Yes

Purpose:
Automated eligibility assessment

Impact:
Potentially significant effect on individuals
```

Where applicable, the organization should assess the legal and ethical implications of automated decisions.

The assessment should identify whether **profiling** occurs.

For example:

```text
Profiling:
Yes

Purpose:
Customer behavior analysis

Data Used:
Transaction History
Interaction History
Service Usage
```

Profiling may create additional privacy and fairness considerations depending on the purpose and impact.

The assessment should identify the **technology used**.

For example:

```text
Cloud Computing
Artificial Intelligence
Machine Learning
Biometrics
Facial Recognition
Location Tracking
Analytics
Monitoring Technologies
```

Technology should be considered as part of the privacy risk assessment rather than separately from the processing activity.

The organization should assess **necessity**.

The key question is:

> Is each category of personal data actually necessary to achieve the stated purpose?

For example:

```text
Purpose:
Customer Support

Data Required:

Customer ID       – Necessary
Name              – Necessary
Email             – Necessary
Support History   – Necessary
Date of Birth     – Not Required
```

If information is not necessary, the organization should consider removing it from the processing activity.

The organization should also assess **proportionality**.

The key question is:

> Is the amount and type of processing proportionate to the business objective and associated privacy risk?

For example:

```text
Business Purpose:
Customer Service Improvement

Proposed Processing:
Record and analyze every customer interaction.

Assessment:
Potentially proportionate if appropriate
controls, transparency, retention, and
purpose limitations are implemented.
```

Another example:

```text
Business Purpose:
Office Security

Proposed Processing:
Continuous biometric monitoring of all employees.

Assessment:
Requires significantly greater justification
and privacy risk analysis.
```

The organization should document the reasoning behind the conclusion.

The assessment should identify **privacy risks**.

Examples include:

```text
Unauthorized Disclosure
Unauthorized Access
Excessive Data Collection
Excessive Retention
Unlawful Processing
Lack of Transparency
Inaccurate Information
Unauthorized Secondary Use
Uncontrolled Third-Party Access
International Transfer Risk
Profiling Risk
Automated Decision Risk
Data Subject Rights Failure
```

A strong risk description should explain the cause, event, and consequence.

For example:

```text
Because customer information is shared with
a third-party AI service, there is a risk that
personal information could be processed beyond
the organization's intended purpose, resulting
in loss of privacy and potential regulatory exposure.
```

The organization should assess **privacy risk likelihood**.

For example:

```text
1 – Rare
2 – Unlikely
3 – Possible
4 – Likely
5 – Almost Certain
```

The organization should assess **privacy risk impact**.

For example:

```text
1 – Insignificant
2 – Minor
3 – Moderate
4 – Major
5 – Severe
```

A simple privacy risk calculation can be:

```text
Likelihood × Impact = Inherent Privacy Risk
```

For example:

```text
Likelihood:
4 – Likely

Impact:
5 – Severe

Inherent Risk:
20 – Critical
```

The exact scoring methodology should align with the organization's approved risk framework.

The assessment should identify **existing privacy and security controls**.

For example:

```text
Data Minimization
Purpose Limitation
Access Control
MFA
Encryption
Pseudonymization
Data Retention Controls
Privacy Notices
Consent Management
DLP
Security Monitoring
Third-Party Due Diligence
```

Controls should be evaluated for both design and operating effectiveness where appropriate.

The assessment should identify **additional controls** required to reduce the identified privacy risks.

For example:

```text
Risk:
Excessive access to customer personal data.

Additional Controls:

Implement role-based access.
Perform quarterly access reviews.
Restrict privileged access.
Enable enhanced monitoring.
```

Another example:

```text
Risk:
Third-party AI provider may retain
customer information beyond the intended purpose.

Additional Controls:

Contractual data-use restrictions.
Data retention restrictions.
Technical data minimization.
Provider security assessment.
Periodic compliance review.
```

The assessment should determine **residual privacy risk** after controls are considered.

For example:

```text
Inherent Risk:
Critical

Existing Controls:
Strong

Additional Controls:
Implemented

Residual Risk:
Medium
```

The organization should then determine whether the residual risk is acceptable.

The assessment should document the **risk treatment**.

Possible treatments include:

```text
Mitigate
Avoid
Transfer
Accept
```

For example:

```text
Treatment:
Mitigate

Action:
Reduce personal data sent to the
third-party processing service.
```

The assessment should assign an **action owner**.

For example:

```text
Action:
Implement data minimization.

Owner:
Product Manager
```

Each action should have a defined **target date**.

For example:

```text
Target Date:
30 September 2026
```

The assessment should also identify whether **DPO or privacy review** is required.

For example:

```text
DPO Review:
Required

DPO Assessment:
Privacy risks identified and additional
controls required before implementation.
```

Where applicable, the organization should determine whether **regulatory consultation** is required.

The assessment should not assume that consultation is automatically required for every DPIA.

The requirement depends on the applicable legal framework, residual risk, and circumstances of the processing activity.

The organization should define the **approval process**.

For example:

```text
Business Owner
      ↓
Information Security
      ↓
Privacy
      ↓
DPO
      ↓
Risk Owner
      ↓
Management Approval
```

The exact workflow should reflect the organization's governance structure.

A practical completed assessment may look like:

```text
PRIVACY IMPACT ASSESSMENT

Assessment ID:
PIA-2026-012

Project:
AI Customer Support Platform

Business Owner:
Director of Customer Operations

Privacy Owner:
Privacy Manager

Processing Purpose:
Provide automated customer support and
improve response times.

Data Subjects:
Customers

Personal Data:
Name
Customer ID
Email
Support History
Service Information

Sensitive Data:
No special-category data intentionally processed.

Recipients:
Customer Service
AI Service Provider
Cloud Provider

Processing Location:
European Union

International Transfer:
Potential technical support access outside
the European Union.

Retention:
Defined customer relationship retention period.

Legal Basis:
To be determined and documented by Privacy.

Automated Decision-Making:
No significant automated decisions.

Profiling:
Limited analytics profiling.

Privacy Risk:
High

Key Risks:

Excessive data sent to AI processing service.
Third-party access to customer information.
Potential retention beyond business requirements.

Existing Controls:

Access Control
Encryption
Vendor Due Diligence
Data Processing Agreement
Security Monitoring

Additional Controls:

Data minimization
Restricted AI data fields
Defined provider retention limits
Enhanced vendor monitoring

Residual Risk:
Medium

Treatment:
Mitigate

Action Owner:
Product Manager

Target Date:
30 September 2026

DPO Review:
Required

Status:
Open – Remediation Required
```

The assessment should include **privacy-by-design considerations**.

Privacy should be incorporated into the design of the system rather than added after implementation.

A practical approach is:

```text
Business Requirement
        ↓
Privacy Requirements
        ↓
Security Requirements
        ↓
System Design
        ↓
Privacy Risk Assessment
        ↓
Control Implementation
        ↓
Testing
        ↓
Approval
        ↓
Production
```

Privacy-by-design controls may include:

```text
Data Minimization
Purpose Limitation
Default Privacy Settings
Pseudonymization
Anonymization
Access Restrictions
Encryption
Retention Automation
Privacy Notices
Consent Management
```

The PIA/DPIA should also be connected to the organization's **security risk assessment**.

For example:

```text
Privacy Risk:
Unauthorized disclosure of customer data

Security Risk:
Unauthorized access to CRM database

Privacy Control:
Data minimization

Security Control:
MFA and RBAC
```

The two assessments may address different aspects of the same underlying risk.

The assessment should also connect to **third-party risk management** where external providers process personal data.

For example:

```text
PIA/DPIA
    ↓
Third-Party Identification
    ↓
Vendor Risk Assessment
    ↓
Security Due Diligence
    ↓
Data Processing Agreement
    ↓
Supplier Security Requirements
    ↓
Ongoing Monitoring
```

This creates a consistent GRC process rather than treating privacy and supplier security as separate activities.

The PIA/DPIA should also connect to **data classification**.

For example:

```text
Data:
Customer Financial Information

Classification:
Restricted

Privacy Risk:
High

Required Controls:
Encryption
MFA
Restricted Access
Monitoring
Retention Controls
```

Classification therefore becomes an input to the privacy risk assessment.

The assessment should be reviewed when significant changes occur.

Triggers may include:

```text
New Data Categories
New Purpose
New Technology
New AI Capability
New Vendor
New Subprocessor
New Country
New Data Transfer
Major System Change
New Regulation
Privacy Incident
Security Incident
Change in Risk Level
```

For example:

```text
Original Processing:
Customer support

New Processing:
AI-based customer behavior profiling

Action:
Review and update PIA/DPIA.
```

The PIA/DPIA should not be considered permanently valid simply because it was approved once.

The organization should maintain a **review history**.

For example:

```text
10 August 2026:
Initial PIA completed.

20 September 2026:
AI processing scope expanded.

20 September 2026:
PIA updated.

15 October 2026:
Additional privacy controls validated.
```

The assessment should maintain evidence supporting its conclusions.

Examples include:

```text
Data Flow Diagram
Privacy Notice
Data Processing Agreement
Vendor Assessment
Security Assessment
System Architecture
Data Retention Schedule
Access Control Design
Security Testing Results
Consent Records
Risk Assessment
```

The evidence should be retained according to the organization's records management requirements.

A mature PIA/DPIA process can be represented as:

```text
Data Inventory
       ↓
Data Classification
       ↓
Privacy Screening
       ↓
PIA / DPIA
       ↓
Privacy Risk Assessment
       ↓
Security Risk Assessment
       ↓
Control Requirements
       ↓
Third-Party Assessment
       ↓
Remediation
       ↓
Approval
       ↓
Implementation
       ↓
Ongoing Monitoring
       ↓
Periodic Review
```

The GRC professional should be able to use the PIA/DPIA to answer:

```text
What personal data is being processed?

Why is it being processed?

Is the processing necessary?

Is the processing proportionate?

Who can access the information?

Where is the information processed?

Who receives the information?

Are third parties involved?

Are international transfers involved?

What privacy risks exist?

What controls reduce those risks?

What residual risk remains?

Who accepted the risk?

What actions remain outstanding?
```

The key principle is:

> **A PIA/DPIA provides a structured method for identifying and managing privacy risks before and during personal-data processing, ensuring that data collection and use are necessary, proportionate, transparent, appropriately protected, and subject to accountable risk-based governance.**

**Part 4 – Data Breach Assessment Template**

A Data Breach Assessment Template is a practical GRC tool used to evaluate suspected or confirmed incidents involving the unauthorized disclosure, access, alteration, loss, destruction, or unavailability of personal or sensitive information.

The purpose of the assessment is to establish what happened, what information was affected, who may be affected, what the potential consequences are, what containment actions have been taken, and whether notification or escalation requirements apply.

A data breach assessment should begin as soon as a potentially reportable privacy or security incident is identified.

A practical assessment process can be represented as:

```text
Potential Data Breach
        ↓
Initial Triage
        ↓
Confirm Whether Personal Data Is Involved
        ↓
Containment
        ↓
Establish What Happened
        ↓
Identify Affected Data
        ↓
Identify Affected Individuals
        ↓
Assess Potential Consequences
        ↓
Assess Likelihood of Harm
        ↓
Determine Overall Risk
        ↓
Determine Notification Requirements
        ↓
Management / DPO Decision
        ↓
Remediation
        ↓
Documentation
        ↓
Lessons Learned
```

A practical Data Breach Assessment Template can contain:

```text
DATA BREACH ASSESSMENT

Assessment ID:

Incident ID:

Date and Time Detected:

Date and Time of Incident:

Incident Reporter:

Incident Owner:

Privacy Owner:

Data Protection Officer:

Business Owner:

Description of Incident:

Incident Type:

Systems / Applications Affected:

Data Assets Affected:

Personal Data Involved:

Sensitive / Special-Category Data:

Number of Records Affected:

Number of Data Subjects Affected:

Data Subjects:

Data Classification:

Data Location:

Data Recipients:

Third Parties Involved:

Cause:

Attack / Incident Method:

Data Accessed:

Data Disclosed:

Data Modified:

Data Lost:

Data Destroyed:

Data Exfiltrated:

Containment Actions:

Recovery Actions:

Security Controls in Place:

Likelihood of Harm:

Severity of Consequences:

Overall Breach Risk:

Potential Regulatory Impact:

Potential Financial Impact:

Potential Reputational Impact:

Potential Individual Harm:

Notification Required:

DPO Assessment:

Regulatory Notification:

Data Subject Notification:

Contractual Notification:

Management Notification:

Risk Treatment:

Corrective Actions:

Action Owner:

Target Date:

Evidence:

Assessment Decision:

Closure Date:

Lessons Learned:

Review Date:

Status:
```

The first step is to assign a unique **Assessment ID**.

For example:

```text
BRT-2026-001
BRT-2026-002
BRT-2026-003
```

The assessment should also reference the organization's **Incident ID**.

For example:

```text
Incident ID:
INC-2026-145

Breach Assessment:
BRT-2026-021
```

This creates traceability between the security incident management process and the privacy breach assessment.

The assessment should record **when the incident was detected**.

For example:

```text
Date Detected:
10 August 2026

Time Detected:
09:35
```

Where known, the organization should also record the **date and time the breach occurred**.

For example:

```text
Incident Occurred:
09 August 2026
22:15

Incident Detected:
10 August 2026
09:35
```

The difference between occurrence and detection can be important when determining the scope and duration of the incident.

The assessment should identify the **incident reporter**.

For example:

```text
Incident Reporter:
Security Operations Analyst
```

The assessment should identify the **incident owner**.

For example:

```text
Incident Owner:
Cybersecurity Incident Manager
```

The assessment should identify the **privacy owner** and, where applicable, the **Data Protection Officer**.

For example:

```text
Privacy Owner:
Privacy Manager

DPO:
Data Protection Officer
```

The assessment should identify the **business owner** responsible for the affected service or information.

For example:

```text
Business Owner:
Customer Operations Director
```

The assessment should provide a clear **description of the incident**.

A weak description would be:

```text
Customer data was leaked.
```

A stronger description would be:

```text
A customer support employee accidentally sent
a spreadsheet containing customer contact
information to an unauthorized external recipient.
The email was identified approximately 20 minutes
after transmission and the recipient was contacted
to request immediate deletion.
```

The description should explain:

```text
What happened?
How did it happen?
When did it happen?
What information was involved?
Who received or accessed the information?
What actions were taken?
```

The assessment should classify the **incident type**.

Examples include:

```text
Unauthorized Disclosure
Unauthorized Access
Lost Device
Stolen Device
Phishing
Malware
Ransomware
Misconfiguration
Accidental Disclosure
Insider Activity
Third-Party Breach
Hacking
Data Exfiltration
Improper Disposal
```

Multiple categories may apply.

The assessment should identify the **affected systems and applications**.

For example:

```text
CRM Platform
Email System
File Storage
HR System
Customer Portal
Database
Cloud Storage
```

The assessment should identify the **affected data assets**.

For example:

```text
Customer Database
Employee Records
Financial Records
Security Logs
Authentication Information
```

The assessment should determine whether **personal data was involved**.

For example:

```text
Personal Data:
Yes
```

The assessment should identify the specific categories.

For example:

```text
Names
Email Addresses
Telephone Numbers
Customer IDs
Account Information
Transaction Information
```

The assessment should determine whether **sensitive or special-category data** was involved.

For example:

```text
Special-Category Data:
No
```

Or:

```text
Special-Category Data:
Yes

Type:
Health Information
```

This distinction may significantly affect the assessment of potential harm and notification requirements.

The assessment should estimate the **number of records affected**.

For example:

```text
Estimated Records:
12,500
```

If the exact number is initially unknown, the assessment should document an estimate and update it as the investigation progresses.

For example:

```text
Initial Estimate:
Approximately 10,000–15,000 records

Confirmed:
12,438 records
```

The assessment should determine the **number of affected data subjects**.

This may be different from the number of records.

For example:

```text
Records:
25,000

Affected Individuals:
18,000
```

The assessment should identify the affected **data subject categories**.

Examples include:

```text
Customers
Employees
Job Applicants
Children
Patients
Suppliers
Contractors
```

The organization should consider whether certain groups may be particularly vulnerable.

The assessment should identify the **data classification**.

For example:

```text
Data Classification:
Restricted
```

Classification provides an important input into the breach risk assessment.

The assessment should identify the **data location**.

For example:

```text
System:
Customer CRM

Location:
European Union
```

The assessment should identify **data recipients** if the information was disclosed.

For example:

```text
Unauthorized Recipient:
External Email Address

Recipient Type:
Unknown Third Party
```

The assessment should identify **third parties involved**.

For example:

```text
Cloud Provider
Managed Service Provider
Payment Processor
Customer Support Provider
Software Provider
```

The assessment should determine the **cause of the breach**.

Examples include:

```text
Human Error
Weak Authentication
Compromised Credentials
Misconfiguration
Software Vulnerability
Insider Misuse
Lost Device
Third-Party Failure
Malware
Phishing
```

For example:

```text
Cause:
Misconfigured cloud storage permissions
```

The assessment should document the **attack or incident method**.

For example:

```text
Attack Method:
Compromised employee credentials

Initial Access:
Phishing email

Affected Account:
Customer Support Administrator
```

Where the incident is accidental rather than malicious, the assessment should document that clearly.

For example:

```text
Method:
Accidental email disclosure
```

The assessment should determine whether data was **accessed**.

For example:

```text
Data Accessed:
Yes

Evidence:
Authentication logs show successful
access from an unauthorized IP address.
```

The assessment should determine whether data was **disclosed**.

For example:

```text
Data Disclosed:
Yes

Recipient:
Unauthorized external party
```

The assessment should determine whether data was **modified**.

For example:

```text
Data Modified:
No
```

The assessment should determine whether information was **lost**.

For example:

```text
Data Lost:
No
```

The assessment should determine whether information was **destroyed**.

For example:

```text
Data Destroyed:
No
```

The assessment should determine whether data was **exfiltrated**.

For example:

```text
Data Exfiltration:
Confirmed

Estimated Volume:
Approximately 2 GB
```

If exfiltration cannot be confirmed:

```text
Data Exfiltration:
Not Confirmed

Evidence:
No confirmed outbound transfer identified.
Investigation continues.
```

The assessment should document **containment actions**.

Examples include:

```text
Disable Compromised Account
Revoke Credentials
Block IP Address
Remove Public Access
Isolate System
Disable Integration
Recall Email
Contact Unauthorized Recipient
Suspend Vendor Access
```

For example:

```text
Containment:

Compromised account disabled.
Active sessions terminated.
Password reset completed.
MFA re-enrollment required.
Unauthorized access blocked.
```

The assessment should document **recovery actions**.

Examples include:

```text
Restore Systems
Reset Credentials
Rebuild Compromised Hosts
Restore Secure Configuration
Validate Data Integrity
Monitor Affected Accounts
```

The assessment should identify the **security controls that were already in place**.

For example:

```text
MFA
Endpoint Protection
DLP
Email Security
Access Control
Logging
SIEM Monitoring
Encryption
Data Classification
```

The assessment should determine whether those controls operated effectively.

For example:

```text
Control:
MFA

Effectiveness:
Effective

Control:
DLP

Effectiveness:
Partially Effective
```

The organization should assess the **likelihood of harm** to affected individuals.

A practical scale may be:

```text
1 – Very Low
2 – Low
3 – Moderate
4 – High
5 – Very High
```

Factors may include:

```text
Nature of the Data
Sensitivity of the Data
Number of Individuals
Potential Recipient
Malicious Intent
Possibility of Identity Theft
Possibility of Financial Fraud
Potential Discrimination
Potential Physical Harm
Potential Reputational Harm
```

The assessment should evaluate the **severity of consequences**.

For example:

```text
1 – Insignificant
2 – Minor
3 – Moderate
4 – Major
5 – Severe
```

The organization can then calculate an overall breach risk.

For example:

```text
Likelihood of Harm × Severity of Consequences
= Overall Breach Risk
```

Example:

```text
Likelihood:
4 – High

Severity:
5 – Severe

Overall Risk:
20 – Critical
```

The exact scoring model should be aligned with the organization's approved privacy and risk methodology.

The assessment should consider **potential regulatory impact**.

For example:

```text
Regulatory Impact:

Potential Privacy Regulation Breach
Potential Notification Requirement
Potential Regulatory Investigation
Potential Enforcement Action
```

The assessment should not automatically conclude that a regulatory violation occurred. The purpose of the assessment is to determine whether applicable obligations may have been triggered.

The assessment should consider **potential financial impact**.

For example:

```text
Financial Impact:

Fraud Risk
Incident Response Costs
Customer Support Costs
Legal Costs
Regulatory Exposure
Business Interruption
Remediation Costs
```

The assessment should consider **potential reputational impact**.

For example:

```text
Reputational Impact:
High

Potential Consequences:

Loss of Customer Trust
Negative Publicity
Customer Complaints
Business Loss
Partner Concerns
```

The assessment should specifically consider **potential harm to individuals**.

For example:

```text
Potential Individual Harm:

Identity Theft
Financial Fraud
Loss of Confidentiality
Discrimination
Embarrassment
Reputational Damage
Physical Safety Risk
Psychological Harm
```

The organization should document the reasoning rather than simply selecting a risk score.

For example:

```text
The affected information includes names,
addresses, account identifiers, and financial
information. The information could potentially
be used for identity theft or targeted fraud.
The affected population is significant and
unauthorized access cannot currently be excluded.
```

The assessment should determine whether **notification is required**.

For example:

```text
Notification Required:
Under Assessment
```

The assessment should distinguish between different notification obligations.

For example:

```text
Regulatory Authority Notification
Data Subject Notification
Contractual Notification
Customer Notification
Insurance Notification
Management Notification
```

The organization should not treat all notification types as equivalent.

The assessment should document the **DPO or privacy decision**.

For example:

```text
DPO Assessment:

The incident involves personal data and
requires formal assessment of potential
risk to affected individuals.
```

The assessment should document whether **regulatory notification** is required.

For example:

```text
Regulatory Notification:
Required

Decision Basis:
Risk assessment indicates that notification
requirements are triggered under applicable
privacy requirements.
```

The organization should document the actual legal basis for the decision through its privacy or legal function.

The assessment should determine whether **data subject notification** is required.

For example:

```text
Data Subject Notification:
Required
```

The decision should be supported by the organization's legal and privacy assessment.

The assessment should also identify **contractual notification requirements**.

For example:

```text
Third-Party Contract:
Security incident notification required.

Supplier Notification:
Completed.
```

Third-party contracts may contain specific incident notification requirements.

The assessment should document **management notification**.

For example:

```text
Management Notification:

CISO
Chief Privacy Officer
Business Owner
Executive Management
```

The escalation level should depend on severity and organizational governance requirements.

The assessment should identify the **risk treatment**.

Possible treatments include:

```text
Mitigate
Accept
Transfer
Avoid
```

For a data breach, mitigation will generally include both immediate containment and longer-term corrective actions.

The assessment should document **corrective actions**.

For example:

```text
Corrective Actions:

Implement stronger email DLP controls.
Provide additional employee training.
Restrict external forwarding.
Perform access review.
Update data handling procedures.
```

Each action should have an **owner**.

For example:

```text
Action:
Implement DLP policy.

Owner:
Information Security Manager
```

Each action should have a **target date**.

For example:

```text
Target Date:
30 September 2026
```

The organization should retain appropriate **evidence**.

Examples include:

```text
Incident Report
System Logs
SIEM Alerts
Email Records
Access Logs
Forensic Evidence
Data Inventory
Data Classification Record
DPO Assessment
Notification Decision
Regulatory Correspondence
Affected Data Analysis
Remediation Evidence
Management Approval
```

Evidence should be protected because breach investigations may contain sensitive security and personal information.

The assessment should document the **final decision**.

For example:

```text
Assessment Decision:

Personal data breach confirmed.

Risk to affected individuals assessed as high.

Regulatory notification required.

Data subject notification required.

Corrective actions initiated.
```

The assessment should include a **closure date** once the investigation and required actions have been completed or formally transitioned to ongoing remediation.

The organization should also document **lessons learned**.

For example:

```text
Lessons Learned:

External email controls were insufficient.
Sensitive data was not adequately restricted.
Employees required additional awareness training.
Data minimization should be strengthened.
```

The assessment should identify whether the incident requires updates to:

```text
Security Controls
Privacy Procedures
Data Classification
Access Controls
Security Awareness
Vendor Requirements
Incident Response Procedures
Business Continuity
Risk Assessments
PIA / DPIA
```

A practical completed assessment may look like:

```text
DATA BREACH ASSESSMENT

Assessment ID:
BRT-2026-024

Incident ID:
INC-2026-145

Incident Type:
Unauthorized Disclosure

Date Detected:
10 August 2026

Business Owner:
Customer Operations Director

Privacy Owner:
Privacy Manager

Data Protection Officer:
DPO

Affected System:
Customer Support Platform

Affected Data:
Customer Name
Email Address
Telephone Number
Customer ID
Support History

Data Classification:
Confidential

Number of Records:
12,438

Affected Data Subjects:
Approximately 11,900 Customers

Cause:
Employee accidentally sent a customer
export file to an unauthorized external
recipient.

Data Accessed:
Yes

Data Disclosed:
Yes

Data Modified:
No

Data Lost:
No

Data Exfiltrated:
Not Applicable

Containment:

Recipient contacted.
Deletion requested.
Access to export functionality restricted.
Employee account reviewed.

Security Controls:

Access Control – Effective
DLP – Partially Effective
Email Security – Partially Effective

Likelihood of Harm:
3 – Moderate

Severity:
4 – Major

Overall Risk:
12 – High

Potential Individual Harm:

Targeted phishing
Fraud attempts
Loss of confidentiality

Regulatory Impact:
Under Assessment

Regulatory Notification:
Required / Pending Privacy Confirmation

Data Subject Notification:
Under Assessment

Corrective Actions:

Strengthen DLP controls.
Restrict customer data exports.
Provide targeted security awareness training.
Review customer support access permissions.

Action Owner:
Customer Security Manager

Target Date:
30 September 2026

Status:
Remediation in Progress
```

The assessment should be updated when additional facts become available.

For example:

```text
Initial Assessment:
12,438 records potentially affected.

Investigation:
8,742 records confirmed affected.

Final Assessment:
8,742 affected records.
```

This demonstrates why the assessment should be treated as a living record during an investigation.

A mature breach assessment process should distinguish between **facts, assumptions, and decisions**.

For example:

```text
FACT:
12,438 records were contained in the file.

CONFIRMED:
The file was sent to one external recipient.

UNKNOWN:
Whether the recipient opened the file.

DECISION:
Privacy team will assess notification
requirements based on available evidence.
```

This prevents assumptions from being presented as confirmed findings.

The organization should also maintain a clear **timeline**.

For example:

```text
09 Aug 2026 – 22:15
Unauthorized disclosure occurred.

10 Aug 2026 – 09:35
Incident detected.

10 Aug 2026 – 09:50
Account access restricted.

10 Aug 2026 – 10:20
Recipient contacted.

10 Aug 2026 – 12:00
Initial data assessment completed.

10 Aug 2026 – 15:00
Privacy assessment initiated.

11 Aug 2026 – 10:00
Notification decision completed.
```

A timeline provides valuable evidence for management, auditors, regulators, and post-incident reviews.

The GRC professional should also ensure that the breach assessment connects with the organization's other GRC processes.

```text
Security Incident
        ↓
Data Breach Assessment
        ↓
Data Inventory
        ↓
Data Classification
        ↓
Privacy Risk Assessment
        ↓
Regulatory Assessment
        ↓
Third-Party Risk
        ↓
Corrective Action
        ↓
Risk Register
        ↓
Audit Evidence
```

A data breach may also trigger an update to the organization's risk register.

For example:

```text
Existing Risk:
Medium

Breach Occurs

Risk Reassessment:
High

Treatment:
Additional Security Controls

Risk Owner:
CISO
```

The breach assessment should also be connected to the **PIA/DPIA**.

If a breach reveals that the original privacy assessment underestimated a particular risk, the organization should update the assessment.

For example:

```text
Original DPIA:
Third-party data access – Medium Risk

Breach:
Unauthorized third-party access identified

Updated DPIA:
Third-party access – High Risk

Additional Control:
Enhanced third-party monitoring
```

The organization should periodically analyze breach records for recurring patterns.

For example:

```text
2026 Breach Analysis

Human Error:
35%

Phishing:
25%

Misconfiguration:
20%

Third-Party Incident:
10%

Lost Devices:
5%

Other:
5%
```

These results can inform the organization's cybersecurity and privacy improvement programs.

The organization can also identify recurring control weaknesses.

For example:

```text
Repeated Issue:
Excessive Data Access

Recommended Action:
Strengthen RBAC and access reviews.
```

Or:

```text
Repeated Issue:
Employees sending sensitive data
to external recipients.

Recommended Action:
Improve DLP and security awareness.
```

This transforms individual incidents into organizational risk intelligence.

The breach assessment can also provide inputs to management reporting.

For example:

```text
Total Privacy Incidents:
24

Confirmed Personal Data Breaches:
8

High-Risk Breaches:
2

Average Time to Containment:
3.2 Hours

Overdue Corrective Actions:
4
```

The GRC team can use these metrics to identify trends and communicate privacy risk to management.

The organization should ensure that breach assessment records themselves are appropriately protected.

They may contain:

```text
Personal Information
Security Information
Forensic Findings
Legal Advice
Incident Details
Vulnerability Information
Employee Information
```

Access should therefore be restricted to authorized personnel.

A mature Data Breach Assessment process can be represented as:

```text
Detection
   ↓
Triage
   ↓
Containment
   ↓
Investigation
   ↓
Data Identification
   ↓
Impact Assessment
   ↓
Privacy Risk Assessment
   ↓
Notification Decision
   ↓
Remediation
   ↓
Documentation
   ↓
Lessons Learned
   ↓
Risk Improvement
```

The GRC professional should be able to use the Data Breach Assessment Template to answer:

```text
What happened?

When did it happen?

When was it detected?

What information was affected?

How sensitive was the information?

How many individuals were affected?

Was the information accessed or disclosed?

Was the information modified or destroyed?

Who received or accessed the information?

What controls were in place?

Did those controls operate effectively?

What harm could result?

What is the overall risk?

Is notification required?

Who made the notification decision?

What corrective actions are required?

Who owns those actions?

When will they be completed?

What lessons were learned?
```

The key principle is:

> **A Data Breach Assessment provides a structured and auditable method for determining the nature, scope, impact, and risk of a personal data breach, supporting timely containment, informed notification decisions, accountable remediation, regulatory compliance, and continuous improvement of the organization's privacy and security controls.**




