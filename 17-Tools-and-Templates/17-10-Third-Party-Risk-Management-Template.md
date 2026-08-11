**17.10 Third-Party Risk Management Templates**

**Part 1 – Vendor Risk Assessment Questionnaire**

A Vendor Risk Assessment Questionnaire is a structured tool used to collect information from third-party vendors and suppliers to determine their cybersecurity, privacy, operational, compliance, and resilience risks before and during a business relationship.

Organizations increasingly depend on third parties for cloud services, software, managed services, telecommunications, payment processing, data processing, consulting, infrastructure, and other critical activities. A vendor may therefore introduce risks that the organization cannot directly control.

The vendor risk assessment process can be represented as:

```text
Vendor Identification
        ↓
Business Service Assessment
        ↓
Inherent Risk Assessment
        ↓
Vendor Questionnaire
        ↓
Evidence Collection
        ↓
Security Assessment
        ↓
Risk Analysis
        ↓
Risk Decision
        ↓
Contractual Requirements
        ↓
Ongoing Monitoring
```

The questionnaire should not be treated as a simple administrative form. It should be designed to collect information that allows the GRC professional to determine whether the vendor's security and risk management practices are appropriate for the services being provided.

A practical Vendor Risk Assessment Questionnaire can contain:

```text
VENDOR RISK ASSESSMENT QUESTIONNAIRE

Vendor Name:

Vendor ID:

Assessment ID:

Service / Product:

Business Owner:

Procurement Owner:

Vendor Contact:

Assessment Date:

Assessment Type:

Initial Assessment:
Annual Review:
Renewal Assessment:
Triggered Assessment:

Service Description:

Business Criticality:

Data Classification:

Data Processed:

Personal Data:

Sensitive Data:

Customer Data:

Vendor Access:

Internal Network Access:

Privileged Access:

Cloud Service:

Subcontractors:

Service Location:

Data Processing Locations:

Business Continuity Requirements:

Regulatory Requirements:

Security Certifications:

Security Policies:

Security Governance:

Risk Management:

Identity and Access Management:

Data Protection:

Encryption:

Vulnerability Management:

Security Monitoring:

Incident Management:

Business Continuity:

Disaster Recovery:

Privacy:

Third-Party Management:

Compliance:

Security Testing:

Audit Rights:

Cyber Insurance:

Security Exceptions:

Overall Risk:

Risk Rating:

Required Remediation:

Risk Owner:

Assessment Decision:

Assessment Expiration Date:

Reviewer:

Approval:
```

The first step is to identify the **vendor and service** being assessed.

For example:

```text
Vendor:
Cloud Service Provider

Service:
Enterprise Cloud Hosting Platform

Business Owner:
Head of Infrastructure

Procurement Owner:
Strategic Procurement Manager
```

The assessment should focus on the actual service being provided rather than evaluating the vendor in an abstract way.

A large technology company may provide many different services, and the risk associated with each service may be different.

For example:

```text
Vendor:
Technology Provider

Service A:
Public Marketing Website Hosting

Risk:
Low

Service B:
Customer Data Processing Platform

Risk:
High

Service C:
Critical Production Infrastructure

Risk:
Critical
```

The questionnaire should therefore assess the vendor in the context of the specific service.

The next step is to determine the **business criticality** of the service.

For example:

```text
Critical:
Failure could significantly disrupt
critical business operations.

High:
Failure could materially affect
important business processes.

Medium:
Failure would create manageable
operational disruption.

Low:
Failure would have limited impact.
```

Business criticality helps determine the depth of the vendor assessment.

A critical cloud provider should normally receive substantially more scrutiny than a vendor providing office supplies.

The assessment should also determine the **type of information accessed or processed by the vendor**.

For example:

```text
Public Information
Internal Information
Confidential Information
Personal Data
Sensitive Personal Data
Financial Information
Customer Information
Security Information
Intellectual Property
```

The more sensitive the information, the greater the need for appropriate security controls.

The questionnaire should identify whether the vendor has **direct access to organizational systems**.

For example:

```text
Does the vendor have access to organizational systems?

Yes / No
```

If yes:

```text
Type of Access:

User Access
Administrative Access
Privileged Access
API Access
Remote Access
Service Account
```

The questionnaire should also identify whether the vendor can access systems remotely.

For example:

```text
Does the vendor have remote access?

Yes / No

If yes:

Is MFA required?

Yes / No

Is access time-limited?

Yes / No

Is access monitored?

Yes / No
```

This helps identify access-related risks.

The questionnaire should then assess the vendor's **security governance**.

Example questions include:

```text
Does the organization maintain a formal
information security program?

Yes / No

Is information security governed by
defined policies and standards?

Yes / No

Is there an executive responsible for
information security?

Yes / No

Are security responsibilities formally
assigned?

Yes / No
```

The vendor may be asked to provide supporting evidence such as:

```text
Information Security Policy
Security Organization Chart
Security Governance Documentation
Security Certification
Independent Assurance Report
```

The questionnaire should assess the vendor's **security certifications and independent assurance**.

For example:

```text
Does the vendor maintain ISO/IEC 27001
certification?

Yes / No / Not Applicable

Does the vendor have a SOC 2 Type II report?

Yes / No / Not Applicable

Does the vendor undergo independent
security assessments?

Yes / No
```

Where a certification or assurance report exists, the assessment should verify:

```text
Scope
Validity
Expiration Date
Covered Services
Covered Locations
Exceptions
```

A certification should not automatically be treated as proof that every security requirement has been satisfied.

The questionnaire should then assess **risk management**.

For example:

```text
Does the vendor maintain a formal information
security risk management process?

Yes / No

Are security risks formally identified,
assessed, treated, and monitored?

Yes / No

Are high-risk security issues reported
to senior management?

Yes / No
```

The vendor should be able to demonstrate that risk management is an established process rather than an informal activity.

The questionnaire should assess **security policies and standards**.

For example:

```text
Does the vendor maintain documented policies
covering:

Information Security
Access Control
Data Protection
Incident Management
Business Continuity
Vulnerability Management
Acceptable Use
Security Awareness
Third-Party Security
```

The auditor or GRC professional may request selected policies as evidence.

The questionnaire should also assess **identity and access management**.

Example questions include:

```text
Are user accounts uniquely assigned?

Yes / No

Is MFA required for privileged access?

Yes / No

Are privileged accounts separately controlled?

Yes / No

Are access rights reviewed periodically?

Yes / No

Are terminated users removed promptly?

Yes / No

Are service accounts controlled and monitored?

Yes / No
```

Additional evidence may include:

```text
Access Control Policy
IAM Procedure
MFA Configuration
Access Review Evidence
Privileged Access Procedure
```

The assessment should determine whether access controls are appropriate for the service being provided.

For a vendor operating critical infrastructure, privileged access controls may be particularly important.

The questionnaire should assess **data protection**.

For example:

```text
Does the vendor process organizational data?

Yes / No

What types of data are processed?

Where is the data stored?

Where is the data processed?

Is data encrypted at rest?

Yes / No

Is data encrypted in transit?

Yes / No

Are encryption keys appropriately protected?

Yes / No
```

The questionnaire should also ask whether data is transferred to other locations.

For example:

```text
Is organizational data transferred across
international borders?

Yes / No

If yes:

Identify the countries involved.

Identify the applicable transfer mechanisms.
```

Where personal data is involved, privacy and legal teams may need to assess the relevant requirements.

The questionnaire should also assess **data retention and deletion**.

For example:

```text
Does the vendor have a documented data
retention policy?

Yes / No

Is data deleted when the contractual
retention period expires?

Yes / No

Can the vendor provide evidence of secure
data deletion when required?

Yes / No
```

This is particularly important when the vendor processes sensitive or personal information.

The questionnaire should assess **vulnerability management**.

For example:

```text
Does the vendor perform vulnerability
scanning?

Yes / No

Does the vendor perform penetration testing?

Yes / No

Are critical vulnerabilities prioritized?

Yes / No

Are vulnerabilities remediated within
defined timeframes?

Yes / No
```

The vendor may be asked to provide:

```text
Penetration Test Summary
Vulnerability Management Policy
Remediation Metrics
Independent Security Assessment
```

The questionnaire should not necessarily require the vendor to provide sensitive technical details that could create additional security risks.

For example, the organization may request a penetration test executive summary rather than the complete technical report.

The assessment should also evaluate **security monitoring and logging**.

For example:

```text
Are security events monitored?

Yes / No

Are security logs retained?

Yes / No

Are privileged activities logged?

Yes / No

Are security alerts investigated?

Yes / No

Is monitoring performed continuously?

Yes / No
```

The level of monitoring should be appropriate to the risk of the service.

The questionnaire should assess **security incident management**.

For example:

```text
Does the vendor maintain a formal incident
response process?

Yes / No

Are security incidents classified according
to severity?

Yes / No

Are customers notified of relevant incidents?

Yes / No

Are incident notification timeframes defined
contractually?

Yes / No

Are post-incident reviews performed?

Yes / No
```

The organization should pay particular attention to how quickly the vendor is required to notify it of security incidents.

Contractual requirements may establish specific notification timeframes depending on the service and applicable regulatory obligations.

The questionnaire should also assess whether the vendor performs **incident response testing**.

For example:

```text
Does the vendor conduct incident response
exercises?

Yes / No

Frequency:

Annual
Semi-Annual
Other

Date of Most Recent Exercise:

Evidence Available:

Yes / No
```

This provides greater assurance than simply confirming that an incident response plan exists.

The questionnaire should assess **business continuity and disaster recovery**.

For example:

```text
Does the vendor maintain a Business
Continuity Plan?

Yes / No

Does the vendor maintain a Disaster
Recovery Plan?

Yes / No

Are recovery plans tested periodically?

Yes / No

When was the most recent test?

What were the results?

Were identified issues remediated?
```

The organization should also assess recovery capabilities.

For example:

```text
RTO:

RPO:

Recovery Testing Frequency:

Last Test Date:

Critical Dependencies:
```

For critical services, these requirements should be aligned with the organization's own business continuity and disaster recovery requirements.

The questionnaire should assess **subcontractors and fourth parties**.

For example:

```text
Does the vendor use subcontractors to
deliver the service?

Yes / No

If yes:

Identify critical subcontractors.

What services do they provide?

Do they process organizational data?

Do they have access to organizational systems?

Are subcontractors subject to security
requirements?

Does the vendor monitor subcontractor risk?
```

This is important because risk may extend beyond the organization's direct contractual relationship.

The vendor may have multiple dependencies:

```text
Organization
      ↓
Primary Vendor
      ↓
Subcontractor
      ↓
Fourth Party
```

The organization should understand material dependencies where they could affect service security, availability, confidentiality, or compliance.

The questionnaire should also assess **security awareness and personnel security**.

For example:

```text
Do employees receive security awareness
training?

Yes / No

Is training provided at onboarding?

Yes / No

Is training refreshed periodically?

Yes / No

Are privileged personnel subject to
additional security requirements?

Yes / No
```

Where appropriate, the assessment may also address background screening requirements.

The questionnaire should assess **physical security** where the vendor operates physical facilities relevant to the service.

For example:

```text
Are critical facilities protected by
physical access controls?

Yes / No

Are visitor controls implemented?

Yes / No

Are physical security events monitored?

Yes / No

Are environmental controls implemented?

Yes / No
```

This may be particularly relevant to:

```text
Data Centers
Managed Service Facilities
Network Operations Centers
Warehouses
Production Facilities
```

The questionnaire should assess **secure development practices** when the vendor develops or maintains software.

For example:

```text
Does the vendor maintain a Secure Software
Development Lifecycle?

Yes / No

Are security requirements defined during
software development?

Yes / No

Are code reviews performed?

Yes / No

Are applications security tested before release?

Yes / No

Are vulnerabilities tracked through remediation?

Yes / No
```

Additional evidence may include:

```text
Secure Development Policy
Application Security Standard
Secure Coding Standard
Penetration Test Summary
Software Security Assessment
```

The questionnaire should assess **change management**.

For example:

```text
Does the vendor maintain a formal change
management process?

Yes / No

Are security impacts assessed before
significant changes?

Yes / No

Are changes approved before implementation?

Yes / No

Are emergency changes subject to review?

Yes / No
```

This is important because changes to a vendor's service can affect the organization's security posture.

The questionnaire should also assess **security testing**.

For example:

```text
Does the vendor perform regular security
assessments?

Yes / No

Does the vendor perform penetration testing?

Yes / No

Are critical findings tracked to closure?

Yes / No

Are independent assessments performed?

Yes / No
```

The assessment should consider both the frequency and scope of testing.

The questionnaire should also address **audit rights**.

For example:

```text
Does the contract provide the organization
with appropriate audit or assurance rights?

Yes / No

Can the organization request relevant
security evidence?

Yes / No

Can the organization perform or commission
security assessments where contractually
appropriate?

Yes / No
```

Audit rights are particularly important for high-risk and regulated services.

The questionnaire should assess **cyber insurance** where relevant.

For example:

```text
Does the vendor maintain cybersecurity
insurance?

Yes / No

Coverage Amount:

Policy Expiration:

Relevant Coverage:
```

Cyber insurance should not be treated as a replacement for effective security controls.

It is one component of the broader risk management approach.

The questionnaire should also assess **regulatory and compliance obligations**.

For example:

```text
Which regulations or requirements apply
to the service?

GDPR
NIS2
DORA
HIPAA
PCI DSS
Other
```

The actual requirements depend on the organization's industry, location, services, customers, and regulatory environment.

The questionnaire should determine whether the vendor has processes for maintaining compliance with applicable obligations.

The questionnaire should also assess **security exceptions**.

For example:

```text
Does the vendor have any known security
exceptions relevant to the service?

Yes / No

If yes:

Describe the exception.

Identify the affected control.

Identify the associated risk.

Identify compensating controls.

Provide remediation date.
```

An exception should not automatically result in vendor rejection.

The GRC professional should evaluate the risk and determine whether it can be accepted, mitigated, transferred, or requires remediation.

The questionnaire should also capture **evidence requirements**.

For example:

```text
Evidence Requested:

ISO/IEC 27001 Certificate
SOC 2 Type II Report
Penetration Test Summary
Business Continuity Test Summary
Security Policies
Incident Response Procedure
Data Processing Agreement
Cyber Insurance Certificate
```

Evidence should be proportional to the vendor's risk level.

A low-risk vendor should not necessarily be required to complete the same extensive assessment as a critical cloud provider.

A tiered approach can be used:

```text
Tier 1 – Low Risk

Basic Questionnaire
Contractual Requirements
Limited Evidence

Tier 2 – Medium Risk

Detailed Questionnaire
Security Evidence
Risk Assessment

Tier 3 – High Risk

Detailed Questionnaire
Independent Assurance
Technical Evidence
Contractual Security Requirements
Management Review

Tier 4 – Critical

Enhanced Due Diligence
Independent Assessment
Technical Validation
Executive Approval
Continuous Monitoring
```

This makes third-party risk management more efficient and risk-based.

The questionnaire should also calculate or support an **inherent vendor risk assessment** before considering the effectiveness of the vendor's controls.

For example:

```text
Inherent Risk Factors:

Business Criticality
Data Sensitivity
System Access
Regulatory Exposure
Service Dependency
Geographic Exposure
Subcontractor Dependency
Operational Impact
```

A vendor may therefore receive:

```text
Inherent Risk:
High
```

The completed questionnaire and supporting evidence may then be used to assess the effectiveness of the vendor's controls.

For example:

```text
Inherent Risk:
High

Control Assessment:
Strong

Residual Risk:
Medium
```

Another vendor may have:

```text
Inherent Risk:
High

Control Assessment:
Weak

Residual Risk:
High
```

This distinction is important.

The risk assessment should not simply assign a risk score based on questionnaire responses without considering the underlying business context.

The questionnaire should also contain **scoring criteria** where the organization uses a quantitative or semi-quantitative methodology.

For example:

```text
Response:

Yes = 0 Risk Points
Partially = 2 Risk Points
No = 5 Risk Points
Unknown = 5 Risk Points
Not Applicable = 0 Risk Points
```

The exact scoring model should be defined by the organization's third-party risk methodology.

Scoring should also consider the importance of each question.

For example:

```text
MFA for Privileged Access:
Weight = 5

Security Awareness:
Weight = 2

Policy Review:
Weight = 1
```

A missing critical control should therefore have greater influence than a minor administrative deficiency.

The questionnaire should also include a mechanism for **reviewer comments**.

For example:

```text
Vendor Response:
MFA implemented.

Reviewer Comment:
Evidence provided confirms MFA for
administrative accounts.

Assessment:
Effective.
```

This prevents the questionnaire from becoming a simple collection of yes/no responses.

The GRC professional should challenge responses where necessary.

For example:

```text
Vendor Response:
"We are ISO 27001 certified."

Follow-Up:
Provide certificate and applicable scope.

Result:
Certificate covers the corporate office but
does not cover the service being assessed.

Conclusion:
Additional assurance required.
```

This demonstrates why vendor risk assessment requires professional judgment.

The completed questionnaire should result in a **vendor risk decision**.

Possible decisions include:

```text
Approved
Approved with Conditions
Remediation Required
Risk Acceptance Required
Restricted Use
Additional Due Diligence Required
Not Approved
```

For example:

```text
Decision:
Approved with Conditions

Conditions:

Implement MFA for all privileged access
within 60 days.

Provide updated penetration testing
evidence within 90 days.
```

The conditions should be formally tracked.

The questionnaire should also establish a **review frequency**.

For example:

```text
Low Risk:
Every 24 months

Medium Risk:
Annually

High Risk:
Annually

Critical:
Continuous Monitoring + Annual Assessment
```

The exact frequency should be determined by the organization's risk methodology and applicable requirements.

A vendor should also be reassessed when a **trigger event** occurs.

Examples include:

```text
Major Security Incident
Significant Service Change
New Data Processing
New Regulatory Requirement
Acquisition or Merger
Change of Subcontractor
Change of Hosting Location
Major Technology Change
Contract Renewal
Significant Control Failure
```

The questionnaire should therefore support both scheduled and event-driven assessments.

A practical completed assessment may look like:

```text
Vendor:
Enterprise Cloud Provider

Service:
Production Cloud Infrastructure

Business Criticality:
Critical

Data:
Confidential Customer Data

System Access:
Privileged Administrative Access

Inherent Risk:
Critical

Security Certification:
ISO/IEC 27001

Independent Assurance:
SOC 2 Type II

MFA:
Yes

Privileged Access Management:
Yes

Encryption:
Yes

Vulnerability Management:
Yes

Incident Notification:
Contractually Defined

Business Continuity:
Tested Annually

Subcontractors:
Yes

Subcontractor Risk Management:
Implemented

Security Exception:
Legacy administrative interface

Compensating Control:
Network Restriction and Enhanced Monitoring

Residual Risk:
Medium

Decision:
Approved with Conditions

Conditions:
Remove legacy interface within 90 days.

Risk Owner:
CISO

Next Review:
12 Months
```

The completed questionnaire should be stored in the organization's third-party risk management repository and linked to the vendor record.

The overall relationship can be represented as:

```text
Vendor
   ↓
Service
   ↓
Inherent Risk
   ↓
Questionnaire
   ↓
Evidence
   ↓
Control Assessment
   ↓
Residual Risk
   ↓
Risk Decision
   ↓
Contractual Requirements
   ↓
Remediation
   ↓
Ongoing Monitoring
```

A well-designed Vendor Risk Assessment Questionnaire provides the GRC professional with a repeatable method for understanding third-party exposure, evaluating vendor security controls, collecting supporting evidence, identifying deficiencies, determining residual risk, and supporting informed decisions about whether and under what conditions the organization should engage with a vendor.

The key principle is:

> **A Vendor Risk Assessment Questionnaire should be risk-based and evidence-driven, using the vendor's business criticality, data access, system access, regulatory exposure, security controls, and dependencies to determine the level of due diligence and ongoing oversight required.**

**Part 2 – Third-Party Due Diligence Checklist**

Third-party due diligence is the process of validating the information provided by a vendor and determining whether the vendor can be trusted to meet the organization's security, privacy, compliance, operational, and resilience requirements.

The Vendor Risk Assessment Questionnaire primarily collects information from the vendor. Due diligence goes a step further by independently reviewing available evidence, validating important claims, identifying gaps, and determining whether the vendor presents an acceptable level of risk.

The due diligence process can be represented as:

```text
Vendor Identification
        ↓
Initial Risk Screening
        ↓
Questionnaire
        ↓
Evidence Collection
        ↓
Evidence Validation
        ↓
Security Due Diligence
        ↓
Privacy Due Diligence
        ↓
Compliance Due Diligence
        ↓
Operational Resilience Review
        ↓
Risk Analysis
        ↓
Approval / Conditions / Rejection
        ↓
Ongoing Monitoring
```

A practical Third-Party Due Diligence Checklist can contain:

```text
THIRD-PARTY DUE DILIGENCE CHECKLIST

Vendor Name:

Vendor ID:

Assessment ID:

Service:

Business Owner:

Procurement Owner:

Vendor Contact:

Assessment Date:

Assessment Type:

Vendor Classification:

Business Criticality:

Inherent Risk:

Security Governance:

Security Policies:

Security Certification:

Independent Assurance:

Access Control:

Privileged Access:

Authentication:

Data Protection:

Encryption:

Vulnerability Management:

Security Monitoring:

Incident Management:

Business Continuity:

Disaster Recovery:

Privacy:

Regulatory Compliance:

Subcontractor Management:

Security Testing:

Physical Security:

Secure Development:

Change Management:

Contractual Security Requirements:

Audit Rights:

Insurance:

Financial Stability:

Reputation:

Security Incidents:

Legal / Regulatory Issues:

Known Exceptions:

Evidence Reviewed:

Evidence Gaps:

Risk Findings:

Required Remediation:

Risk Decision:

Risk Owner:

Approval:

Next Review Date:

Reviewer:

Review Status:
```

The first step is to confirm the **identity of the vendor**.

The organization should verify that the legal entity being assessed is the same entity that will provide the service.

For example:

```text
Vendor Legal Name:
ABC Cloud Services Ltd.

Trading Name:
ABC Cloud

Registered Entity:
ABC Cloud Services Ltd.

Contracting Entity:
ABC Cloud Services Ltd.
```

This distinction is important because a brand name may represent multiple legal entities or subsidiaries.

The organization should verify:

```text
Legal Name
Registered Address
Registration Information
Ownership
Parent Company
Subsidiaries
Contracting Entity
Service Provider Entity
```

This helps prevent situations where the organization performs due diligence on one entity but signs a contract with another.

The next step is to confirm the **service being provided**.

For example:

```text
Service:
Customer Relationship Management Platform

Purpose:
Customer Data Management

Business Owner:
Chief Customer Officer

Criticality:
High
```

The due diligence review should remain focused on the actual service.

A vendor may have strong corporate security controls while a particular service has different risks or dependencies.

The organization should determine the **business criticality** of the service.

For example:

```text
Critical:
Failure could significantly disrupt
critical business operations.

High:
Failure could materially affect
important business functions.

Medium:
Failure could cause manageable disruption.

Low:
Failure would have limited impact.
```

This classification determines how extensive the due diligence should be.

The organization should also confirm the **inherent risk** before evaluating mitigating controls.

For example:

```text
Data Sensitivity:
High

System Access:
Privileged

Business Criticality:
Critical

Regulatory Exposure:
High

Third-Party Dependency:
High

Inherent Risk:
Critical
```

A high inherent risk does not automatically mean that the vendor is unacceptable. It means that stronger due diligence and stronger controls may be required.

The checklist should verify the vendor's **security governance structure**.

Questions may include:

```text
[ ] Formal information security program exists
[ ] Security responsibilities are defined
[ ] Security leadership is established
[ ] Security policies are approved
[ ] Security risks are reported to management
[ ] Security performance is monitored
```

The organization should request appropriate evidence.

For example:

```text
Evidence:

Information Security Policy
Security Governance Documentation
Security Organization Structure
Security Certification
Independent Assurance Report
```

The evidence should be reviewed rather than simply marked as received.

The organization should verify the vendor's **security certifications**.

For example:

```text
[ ] ISO/IEC 27001 certificate reviewed
[ ] Certificate is valid
[ ] Certificate scope reviewed
[ ] Relevant services included
[ ] Relevant locations included
[ ] Expiration date confirmed
[ ] Certification body identified
```

A valid certification should not automatically result in a low-risk assessment.

The organization should determine whether the certification scope actually covers the service being purchased.

For example:

```text
Vendor:
ABC Cloud

ISO/IEC 27001 Scope:
Corporate IT Services

Contracted Service:
Customer Cloud Platform

Conclusion:
Certification scope does not clearly cover
the contracted service.

Additional Assurance:
Required.
```

The same principle applies to SOC reports and other independent assurance reports.

The checklist should verify the **scope and coverage** of independent assurance.

For example:

```text
[ ] Report obtained
[ ] Reporting period confirmed
[ ] Services covered
[ ] Locations covered
[ ] Controls covered
[ ] Exceptions reviewed
[ ] Complementary customer controls identified
[ ] Report expiration / period confirmed
```

The organization should identify whether there are **control exceptions**.

For example:

```text
SOC Report Exception:

Access review control was not consistently
performed during part of the assessment period.
```

The GRC professional should evaluate whether the exception affects the service being purchased.

The due diligence checklist should assess **identity and access management**.

For example:

```text
[ ] Unique user accounts
[ ] Strong authentication
[ ] MFA for privileged access
[ ] Privileged access management
[ ] Periodic access reviews
[ ] Joiner / mover / leaver controls
[ ] Service account controls
[ ] Remote access controls
[ ] Emergency access controls
```

The organization should request evidence proportional to the risk.

For a critical vendor, evidence may include:

```text
Access Control Policy
Privileged Access Procedure
MFA Standard
Access Review Evidence
Privileged Access Management Evidence
```

The checklist should assess **data protection**.

For example:

```text
[ ] Data classification implemented
[ ] Data handling requirements defined
[ ] Encryption at rest
[ ] Encryption in transit
[ ] Key management controls
[ ] Data retention requirements
[ ] Secure data deletion
[ ] Backup protection
```

The organization should determine where the data will be stored and processed.

For example:

```text
Primary Data Location:
Germany

Backup Data Location:
Netherlands

Support Access:
United States

Subprocessor:
Ireland
```

Geographic information can be important for privacy, regulatory, contractual, and data transfer considerations.

The checklist should assess **privacy requirements** where personal data is processed.

For example:

```text
[ ] Data Processing Agreement required
[ ] Data processing roles identified
[ ] Processing purposes documented
[ ] Data retention defined
[ ] Subprocessors identified
[ ] International transfers assessed
[ ] Data subject support defined
[ ] Data breach notification requirements defined
[ ] Data deletion requirements defined
```

The organization should determine whether the vendor acts as:

```text
Controller
Processor
Joint Controller
Independent Service Provider
```

The correct classification should be determined based on the actual processing relationship and applicable law.

The checklist should assess **vulnerability management**.

For example:

```text
[ ] Vulnerability management program exists
[ ] Regular vulnerability scanning performed
[ ] Critical vulnerabilities prioritized
[ ] Remediation timelines defined
[ ] Penetration testing performed
[ ] Findings tracked to closure
[ ] Exceptions formally managed
```

Evidence may include:

```text
Vulnerability Management Policy
Penetration Test Summary
Security Assessment
Remediation Metrics
Independent Assurance Report
```

The organization should avoid requesting unnecessarily sensitive technical information.

For example, a penetration test executive summary may be sufficient where the complete technical report contains sensitive system information.

The checklist should assess **security monitoring and logging**.

For example:

```text
[ ] Security events monitored
[ ] Privileged activity logged
[ ] Authentication events logged
[ ] Security alerts investigated
[ ] Logs protected from unauthorized modification
[ ] Log retention defined
[ ] Monitoring responsibilities defined
```

For critical services, the organization may also verify whether monitoring is performed continuously.

The checklist should assess the vendor's **incident management capability**.

For example:

```text
[ ] Incident response plan exists
[ ] Incident classification exists
[ ] Security escalation process exists
[ ] Customer notification process exists
[ ] Regulatory notification responsibilities defined
[ ] Incident exercises performed
[ ] Lessons learned process exists
```

The organization should pay particular attention to contractual incident notification requirements.

For example:

```text
Vendor Requirement:

Notify the organization of a confirmed
security incident affecting customer data
within the contractual notification period.
```

The exact notification requirement should be established through the organization's legal, privacy, regulatory, and contractual requirements.

The checklist should assess **business continuity**.

For example:

```text
[ ] Business Continuity Plan exists
[ ] Disaster Recovery Plan exists
[ ] Critical services identified
[ ] Recovery objectives defined
[ ] Recovery testing performed
[ ] Test results reviewed
[ ] Corrective actions tracked
```

The organization should compare the vendor's recovery capabilities with its own requirements.

For example:

```text
Organization Requirement:

RTO:
4 hours

RPO:
1 hour

Vendor Capability:

RTO:
2 hours

RPO:
30 minutes

Assessment:
Meets requirement.
```

Another vendor may not meet the requirement:

```text
Organization Requirement:

RTO:
4 hours

Vendor Capability:

RTO:
12 hours

Assessment:
Gap identified.

Action:
Remediation or risk acceptance required.
```

The checklist should also assess **subcontractor and fourth-party risk**.

For example:

```text
[ ] Subcontractors identified
[ ] Critical subcontractors identified
[ ] Security requirements flow down
[ ] Subcontractors assessed
[ ] Subcontractor changes notified
[ ] Material fourth parties identified
[ ] Subcontractor incidents monitored
```

The organization should determine whether critical subcontractors are involved in:

```text
Data Processing
Cloud Hosting
Security Operations
Customer Support
Infrastructure
Software Development
Payment Processing
```

The checklist should also assess **secure software development** when the vendor develops software.

For example:

```text
[ ] Secure SDLC exists
[ ] Security requirements defined
[ ] Code review performed
[ ] Dependency management implemented
[ ] Application security testing performed
[ ] Vulnerability remediation process exists
[ ] Security testing performed before release
```

The organization may request evidence such as:

```text
Secure Development Policy
Application Security Standard
Penetration Test Summary
Software Security Assessment
Vulnerability Management Evidence
```

The checklist should assess **change management**.

For example:

```text
[ ] Formal change management process
[ ] Security impact assessment
[ ] Change approval
[ ] Testing before production
[ ] Emergency change process
[ ] Post-implementation review
```

This is important for vendors that operate critical infrastructure or provide continuously changing technology services.

The checklist should assess **physical security** where relevant.

For example:

```text
[ ] Physical access controls
[ ] Visitor management
[ ] Security monitoring
[ ] Environmental controls
[ ] Fire protection
[ ] Power protection
[ ] Physical security incident management
```

For a cloud provider, the organization may rely on independent assurance reports rather than conducting its own physical inspection.

The checklist should also assess **personnel security**.

For example:

```text
[ ] Background screening
[ ] Security awareness training
[ ] Confidentiality agreements
[ ] Security responsibilities
[ ] Employee termination process
[ ] Privileged personnel controls
```

Requirements should be proportional to the vendor's role and access.

The checklist should assess **security awareness**.

For example:

```text
[ ] Security awareness program
[ ] Initial security training
[ ] Periodic refresher training
[ ] Phishing awareness
[ ] Role-based security training
[ ] Training completion monitoring
```

The organization may request training statistics or policy documentation as supporting evidence.

The checklist should also evaluate **financial stability** where service continuity could be affected by the vendor's financial condition.

For critical vendors, the organization may consider:

```text
[ ] Financial statements reviewed
[ ] Credit assessment performed
[ ] Financial risk identified
[ ] Business dependency assessed
[ ] Exit strategy available
```

Financial due diligence may be especially important when replacing the vendor would be difficult or expensive.

The checklist should assess **reputation and external risk indicators**.

Depending on the organization's methodology and applicable law, this may include:

```text
[ ] Material security incidents identified
[ ] Regulatory enforcement identified
[ ] Significant litigation identified
[ ] Public security concerns reviewed
[ ] Relevant adverse information reviewed
```

The objective is not to conduct unrestricted background investigations. The review should remain proportionate, lawful, relevant, and focused on third-party risk.

The organization should also assess the vendor's **history of security incidents**.

For example:

```text
[ ] Material incidents identified
[ ] Incident history reviewed
[ ] Root causes reviewed
[ ] Corrective actions reviewed
[ ] Recurring issues identified
```

A previous security incident does not automatically mean that the vendor is unacceptable.

The key questions are:

```text
What happened?

What was the root cause?

How significant was the impact?

How did the vendor respond?

What corrective actions were implemented?

Has the issue recurred?
```

The checklist should assess **contractual security requirements**.

For example:

```text
[ ] Confidentiality requirements
[ ] Security requirements
[ ] Data protection requirements
[ ] Incident notification
[ ] Audit rights
[ ] Security assessment rights
[ ] Subcontractor requirements
[ ] Data deletion
[ ] Business continuity
[ ] Exit requirements
```

The security requirements should reflect the vendor's risk.

A critical vendor may require significantly more detailed contractual requirements than a low-risk supplier.

The checklist should also assess **audit and assurance rights**.

For example:

```text
[ ] Right to request security evidence
[ ] Right to review assurance reports
[ ] Right to conduct assessments
[ ] Right to request remediation
[ ] Right to audit where appropriate
```

The organization should ensure that contractual rights are practical and enforceable.

The checklist should also assess **cybersecurity insurance** where relevant.

For example:

```text
[ ] Cyber insurance exists
[ ] Coverage verified
[ ] Policy period verified
[ ] Coverage appropriate to service risk
```

Insurance should be treated as a risk-transfer mechanism rather than a substitute for security controls.

The checklist should record **evidence reviewed**.

For example:

```text
Evidence Reviewed:

ISO/IEC 27001 Certificate
SOC 2 Type II Report
Penetration Test Summary
Business Continuity Test Report
Information Security Policy
Incident Response Plan
Data Processing Agreement
Cyber Insurance Certificate
```

The reviewer should record whether the evidence actually supports the vendor's claims.

For example:

```text
Vendor Response:
"We perform annual penetration testing."

Evidence:
Penetration Test Summary dated June 2026.

Conclusion:
Verified.
```

Another example:

```text
Vendor Response:
"All privileged accounts use MFA."

Evidence:
MFA policy provided.

Additional Validation:
No technical evidence provided.

Conclusion:
Unable to independently verify.
```

This distinction is important.

A policy describing a control does not necessarily demonstrate that the control is operating.

The checklist should identify **evidence gaps**.

For example:

```text
Evidence Gap:

Vendor has not provided evidence demonstrating
quarterly privileged access reviews.

Risk Impact:
Medium

Required Action:
Provide evidence or implement the required
review process.
```

Evidence gaps should be tracked to resolution.

The due diligence review should identify **security findings**.

For example:

```text
Finding:

Vendor does not currently require MFA for
all privileged administrative access.

Risk:
High

Required Remediation:
Implement MFA for all privileged accounts.
```

The finding should be linked to the vendor risk record.

The organization should then determine the **residual risk**.

For example:

```text
Inherent Risk:
High

Controls:
Strong

Open Finding:
Medium

Residual Risk:
Medium
```

The risk decision should be based on the organization's third-party risk methodology.

Possible outcomes include:

```text
Approved
Approved with Conditions
Remediation Required
Risk Acceptance Required
Restricted Use
Additional Due Diligence
Not Approved
```

For example:

```text
Decision:
Approved with Conditions

Conditions:

1. Implement privileged MFA within 60 days.

2. Provide updated penetration test evidence
within 90 days.

3. Complete annual security assessment.
```

The conditions should be assigned to responsible owners and tracked.

The checklist should identify the **risk owner**.

For example:

```text
Risk Owner:
Chief Information Security Officer
```

The risk owner should be someone with sufficient authority to accept the identified risk.

The business owner may be responsible for the relationship, while the security or risk function may provide the independent risk assessment.

The checklist should also establish the **next review date**.

For example:

```text
Risk Tier:
High

Review Frequency:
Annual

Next Review:
15 August 2027
```

Critical vendors may require more frequent monitoring.

The review should also be triggered when significant changes occur.

For example:

```text
[ ] Major Security Incident
[ ] Change in Ownership
[ ] New Service
[ ] New Data Processing
[ ] New Subcontractor
[ ] Major Technology Change
[ ] Regulatory Change
[ ] Contract Renewal
[ ] Significant Control Failure
```

A practical completed checklist may look like:

```text
Vendor:
Enterprise Cloud Provider

Service:
Production Cloud Infrastructure

Business Criticality:
Critical

Inherent Risk:
Critical

ISO/IEC 27001:
Verified

SOC 2 Type II:
Verified

MFA:
Verified

Privileged Access:
Verified

Encryption:
Verified

Vulnerability Management:
Verified

Incident Management:
Verified

Business Continuity:
Verified

Subcontractor Management:
Verified

Security Testing:
Verified

Open Finding:
Legacy administrative interface does not
support MFA.

Compensating Controls:
Network restrictions
Enhanced monitoring

Residual Risk:
Medium

Decision:
Approved with Conditions

Condition:
Legacy interface must be removed within
90 days.

Risk Owner:
CISO

Next Review:
12 Months
```

The final due diligence decision should be documented and approved according to the organization's governance process.

A complete third-party due diligence record should create traceability between:

```text
Vendor
   ↓
Service
   ↓
Business Criticality
   ↓
Inherent Risk
   ↓
Questionnaire
   ↓
Evidence
   ↓
Due Diligence
   ↓
Findings
   ↓
Residual Risk
   ↓
Risk Decision
   ↓
Contract
   ↓
Remediation
   ↓
Ongoing Monitoring
```

A mature GRC function should not perform vendor due diligence only once at the beginning of a relationship. The assessment should form part of the vendor lifecycle and be refreshed when the vendor, service, technology, data, regulatory environment, or risk profile changes.

The key principle is:

> **Third-party due diligence validates vendor claims through evidence, independent review, and risk-based analysis so that the organization can make informed decisions about whether a vendor is suitable, what conditions should apply, and how the relationship should be monitored over time.**

**Part 3 – Supplier Security Requirements**

Supplier Security Requirements define the minimum cybersecurity, information security, privacy, resilience, and compliance controls that a supplier must meet when providing products or services to an organization.

These requirements are normally established before a supplier is onboarded and incorporated into appropriate procurement documents, contracts, statements of work, service agreements, or supplier security schedules.

The purpose is to ensure that security expectations are clearly communicated before the supplier receives access to organizational information, systems, facilities, or customers.

A practical supplier security requirements structure can include:

```text
SUPPLIER SECURITY REQUIREMENTS

Supplier Name:

Supplier Service:

Business Owner:

Supplier Risk Tier:

Security Classification:

Information Access:

System Access:

Security Requirements:

Access Control:

Authentication:

Data Protection:

Encryption:

Vulnerability Management:

Security Testing:

Security Monitoring:

Incident Management:

Business Continuity:

Disaster Recovery:

Privacy:

Subcontractor Management:

Security Awareness:

Personnel Security:

Physical Security:

Secure Development:

Change Management:

Audit and Assurance:

Regulatory Compliance:

Security Incident Notification:

Data Retention and Deletion:

Contract Termination:

Security Exceptions:

Compliance Evidence:

Supplier Responsibilities:

Organization Responsibilities:

Review Frequency:

Approval:
```

Supplier security requirements should be **risk-based**.

Not every supplier requires the same level of security controls.

For example:

```text
Low-Risk Supplier

Office Supplies
No System Access
No Sensitive Data

Security Requirements:
Basic contractual security obligations
```

A higher-risk supplier may require:

```text
High-Risk Supplier

Cloud Service Provider
Customer Data
Production System Access

Security Requirements:
ISO/IEC 27001
MFA
Encryption
Security Monitoring
Incident Notification
Business Continuity
Penetration Testing
Audit Rights
Subcontractor Controls
```

A critical supplier may require an even more comprehensive set of requirements.

The organization should therefore classify suppliers before applying security requirements.

A practical model may be:

```text
Tier 1 – Low Risk

Limited business impact
No sensitive data
No privileged access

Tier 2 – Moderate Risk

Internal information
Limited system access
Moderate business dependency

Tier 3 – High Risk

Confidential or personal data
Significant system access
Important business service

Tier 4 – Critical

Critical business service
Privileged access
Sensitive information
High regulatory or operational impact
```

The supplier's risk tier should determine the depth of the security requirements.

One of the first requirements should address **information security governance**.

For example:

```text
Supplier shall maintain an information
security management program appropriate to
the nature, scale, and risk of the services
provided to the organization.
```

The supplier should maintain appropriate security policies, procedures, responsibilities, and governance processes.

For higher-risk suppliers, the organization may require evidence of formal security governance.

For example:

```text
Required Evidence:

Information Security Policy
Security Organization
Security Certification
Independent Assurance Report
Risk Management Process
```

The supplier should also be required to comply with applicable organizational security requirements.

For example:

```text
Supplier shall comply with the organization's
applicable information security requirements
identified in the contract, security schedule,
statement of work, or other governing agreement.
```

This creates a contractual connection between supplier obligations and the organization's security framework.

Supplier requirements should address **access control**.

For example:

```text
Supplier shall restrict access to organizational
systems and information to authorized personnel
based on business need and least privilege.
```

Specific requirements may include:

```text
Unique User Accounts
Least Privilege
Role-Based Access
Privileged Access Management
Periodic Access Reviews
Access Revocation
Service Account Management
Remote Access Controls
```

For example:

```text
Supplier personnel shall not receive privileged
access unless explicitly authorized by the
organization and shall use approved authentication
mechanisms.
```

The supplier should also be required to protect privileged accounts.

For example:

```text
Privileged access shall be:

Authorized
Individually Assigned
Authenticated Using MFA
Logged
Monitored
Periodically Reviewed
```

Supplier access should be removed promptly when personnel no longer require it.

This is particularly important for:

```text
Managed Service Providers
Cloud Providers
IT Support Providers
Security Operations Providers
Application Support Providers
```

The requirements should address **authentication and MFA**.

For example:

```text
Supplier personnel accessing organizational
systems shall use multi-factor authentication
where technically supported and required by
the organization's security standards.
```

For privileged access:

```text
MFA shall be mandatory for privileged
administrative access to organizational systems.
```

The organization should define exceptions through a formal risk acceptance process rather than allowing suppliers to determine their own exceptions.

Supplier requirements should address **data protection**.

For example:

```text
Supplier shall protect organizational information
against unauthorized access, disclosure,
modification, loss, destruction, or misuse.
```

The supplier should follow agreed data classification and handling requirements.

For example:

```text
Supplier shall handle information according
to the classification and security requirements
specified by the organization.
```

Requirements should identify the types of information involved.

For example:

```text
Public
Internal
Confidential
Restricted
Personal Data
Sensitive Personal Data
Customer Data
```

The requirements should address **encryption**.

For example:

```text
Supplier shall protect sensitive information
using appropriate encryption mechanisms during
transmission and storage.
```

The organization may specify additional requirements for high-risk services.

For example:

```text
Data in Transit:
Approved Transport Encryption

Data at Rest:
Approved Encryption

Encryption Keys:
Protected and Access-Controlled
```

The exact technical standards should be defined by the organization's security architecture and applicable requirements.

Supplier requirements should address **vulnerability management**.

For example:

```text
Supplier shall maintain a vulnerability
management process appropriate to the services
provided.
```

Specific requirements may include:

```text
Regular Vulnerability Scanning
Risk-Based Prioritization
Critical Vulnerability Remediation
Security Patch Management
Exception Management
Remediation Tracking
```

The organization may establish contractual remediation targets.

For example:

```text
Critical Vulnerabilities:
Remediate within agreed critical timeframe.

High Vulnerabilities:
Remediate within agreed high-risk timeframe.
```

The exact timelines should reflect the organization's risk appetite and service requirements.

Supplier requirements should address **penetration testing and security testing** where appropriate.

For example:

```text
Suppliers providing high-risk applications
or infrastructure shall conduct security
testing at defined intervals and after
significant changes.
```

The organization may require:

```text
Penetration Testing
Application Security Testing
Vulnerability Assessment
Configuration Assessment
Cloud Security Assessment
```

The organization should not automatically require every supplier to provide detailed technical security reports.

Evidence should be proportional to risk and appropriately protected.

Supplier requirements should address **security monitoring and logging**.

For example:

```text
Supplier shall maintain appropriate security
logging and monitoring capabilities for systems
supporting the contracted service.
```

Requirements may include:

```text
Authentication Logging
Privileged Activity Logging
Security Event Monitoring
Log Protection
Log Retention
Security Alert Investigation
```

For critical services, the organization may require continuous monitoring or defined security monitoring coverage.

Supplier requirements should address **security incident management**.

For example:

```text
Supplier shall maintain documented processes
for detecting, responding to, investigating,
and recovering from information security incidents.
```

The supplier should notify the organization when an incident affects:

```text
Organizational Data
Organizational Systems
Customer Information
Service Availability
Confidentiality
Integrity
```

The contract should define the notification requirements.

For example:

```text
The supplier shall notify the organization
without undue delay and within the contractual
incident notification period after becoming
aware of a security incident that materially
affects the organization's information or services.
```

The exact notification period should be established based on applicable laws, regulations, contracts, and organizational requirements.

The supplier should also cooperate with investigations.

For example:

```text
Supplier shall provide reasonable cooperation
during security incident investigations,
including relevant information, timelines,
impact assessments, and remediation actions.
```

Supplier requirements should address **business continuity and disaster recovery**.

For example:

```text
Supplier shall maintain business continuity
and disaster recovery capabilities appropriate
to the criticality of the contracted service.
```

The organization may specify:

```text
RTO
RPO
Recovery Testing
Backup Requirements
Geographic Redundancy
Crisis Management
Recovery Communications
```

For example:

```text
Required RTO:
4 hours

Required RPO:
1 hour
```

The supplier should demonstrate that its capabilities meet the agreed requirements.

Supplier requirements should address **backup protection**.

For example:

```text
Supplier shall maintain appropriate backup
procedures for organizational data and systems
where backup services form part of the contracted
service.
```

Requirements may include:

```text
Backup Frequency
Backup Integrity
Encryption
Access Control
Retention
Recovery Testing
Protection Against Unauthorized Deletion
```

Supplier requirements should address **privacy and personal data protection** when applicable.

For example:

```text
Supplier shall process personal data only for
authorized purposes and in accordance with
applicable data protection requirements and
contractual instructions.
```

Additional requirements may include:

```text
Data Processing Agreement
Subprocessor Controls
International Data Transfers
Data Subject Assistance
Data Retention
Data Deletion
Privacy Incident Notification
```

The supplier should not introduce new subprocessors without following the agreed approval or notification process.

Supplier requirements should address **subcontractors and fourth parties**.

For example:

```text
Supplier shall maintain appropriate security
requirements for subcontractors involved in
the delivery of the contracted services.
```

For critical suppliers, the organization may require:

```text
Identification of Critical Subcontractors
Security Due Diligence
Security Requirements Flow-Down
Incident Notification
Material Change Notification
Subcontractor Monitoring
```

The supplier should remain accountable for the security performance of its subcontractors where contractually appropriate.

Supplier requirements should address **personnel security**.

For example:

```text
Supplier shall implement personnel security
controls appropriate to the roles and access
levels of personnel supporting the contracted
services.
```

Requirements may include:

```text
Background Screening
Confidentiality Agreements
Security Awareness
Role-Based Training
Access Authorization
Termination Procedures
```

The specific requirements should comply with applicable employment and privacy laws.

Supplier requirements should address **security awareness**.

For example:

```text
Supplier personnel with access to organizational
information or systems shall receive appropriate
security awareness training.
```

For specialized roles, additional training may be required.

Examples include:

```text
Privileged Administrators
Security Operations Personnel
Developers
Privacy Personnel
Incident Responders
```

Supplier requirements should address **physical security** where physical facilities support the service.

For example:

```text
Supplier shall implement appropriate physical
security controls for facilities used to store,
process, or access organizational information.
```

Controls may include:

```text
Physical Access Control
Visitor Management
CCTV
Environmental Protection
Fire Protection
Power Protection
Physical Security Monitoring
```

The level of detail should depend on the service.

Supplier requirements should address **secure software development** when the supplier develops or maintains software.

For example:

```text
Supplier shall maintain a secure software
development lifecycle appropriate to the
services provided.
```

Requirements may include:

```text
Security Requirements
Secure Coding
Code Review
Dependency Management
Application Security Testing
Vulnerability Management
Security Testing Before Release
```

For high-risk applications, the organization may require evidence of security testing before major releases.

Supplier requirements should address **change management**.

For example:

```text
Supplier shall maintain a formal change
management process for changes that could
materially affect the security, availability,
confidentiality, or integrity of the service.
```

Significant changes may include:

```text
Architecture Changes
Hosting Location Changes
Major Software Changes
Security Control Changes
Data Processing Changes
Subcontractor Changes
```

The organization should establish notification requirements for material changes.

Supplier requirements should address **security event and incident cooperation**.

For example:

```text
Supplier shall cooperate with the organization
in investigating security events affecting
the contracted service.
```

This may include:

```text
Incident Timeline
Affected Systems
Affected Data
Root Cause
Containment Actions
Remediation
Lessons Learned
```

Supplier requirements should also address **audit and assurance**.

For example:

```text
The organization may require reasonable
evidence demonstrating the supplier's
compliance with applicable security requirements.
```

Evidence may include:

```text
ISO/IEC 27001 Certificate
SOC 2 Report
Security Assessment
Penetration Test Summary
Business Continuity Test Results
Security Policies
Independent Audit Report
```

For critical suppliers, the organization may require contractual rights to perform or commission additional assessments.

The requirements should define how audits are conducted without creating unnecessary operational disruption.

Supplier requirements should address **regulatory compliance**.

For example:

```text
Supplier shall comply with applicable legal,
regulatory, and contractual requirements
relevant to the services provided.
```

Depending on the service, this may include requirements related to:

```text
Data Protection
Cybersecurity
Operational Resilience
Financial Services
Payment Security
Critical Infrastructure
Industry-Specific Requirements
```

The exact requirements should be determined through the organization's legal and compliance assessment.

Supplier requirements should address **security documentation**.

For example:

```text
Supplier shall maintain documented security
policies, procedures, and records necessary
to demonstrate compliance with applicable
security requirements.
```

The organization may request updated evidence periodically.

Supplier requirements should also address **security metrics and reporting** where appropriate.

For example:

```text
Supplier shall provide agreed security and
service performance information upon request.
```

Metrics may include:

```text
Security Incidents
Critical Vulnerabilities
Patch Compliance
Availability
Recovery Testing
Security Assessment Results
Open Security Findings
```

Critical suppliers may be required to provide regular security reports.

Supplier requirements should address **data retention and secure deletion**.

For example:

```text
Upon expiration or termination of the service,
the supplier shall return or securely delete
organizational information in accordance with
contractual and legal requirements.
```

The organization may require evidence of deletion.

For example:

```text
Secure Deletion Confirmation
Data Destruction Certificate
System Decommissioning Record
```

The requirement should also address backup copies where technically and legally applicable.

Supplier requirements should address **contract termination and exit**.

For example:

```text
Supplier shall support an orderly transition
of services upon contract termination and
shall protect organizational information
during the transition.
```

Exit requirements may include:

```text
Data Return
Data Deletion
Credential Revocation
Access Removal
Asset Return
Knowledge Transfer
Configuration Transfer
Subcontractor Termination
```

Exit planning is particularly important for critical suppliers because supplier dependency can create significant operational risk.

Supplier requirements should also address **security exceptions**.

For example:

```text
Supplier shall not deviate materially from
agreed security requirements without documented
approval through the organization's security
exception or risk acceptance process.
```

A supplier should not be permitted to unilaterally decide that a security requirement is unnecessary.

An exception record may include:

```text
Requirement:
MFA for Privileged Access

Exception:
Legacy administrative interface does not
support MFA.

Risk:
High

Compensating Control:
Network Restriction

Remediation Date:
30 November 2026

Risk Owner:
CISO
```

Supplier requirements should also define **responsibilities between the organization and the supplier**.

For example:

```text
Organization Responsibilities:

Provide security requirements
Authorize access
Review supplier evidence
Monitor supplier risk
Manage risk decisions

Supplier Responsibilities:

Implement security controls
Protect organizational information
Report incidents
Provide required evidence
Manage subcontractor security
Support audits
Remediate identified deficiencies
```

This prevents ambiguity regarding who is responsible for a particular control.

A useful tool is a **shared responsibility matrix**.

For example:

```text
Control                    Organization   Supplier

Identity Management        A              R

Application Security       C              R

Data Protection            A              R

Incident Response          R              R

Physical Security          C              R

Business Continuity        A              R

Subcontractor Management   C              R
```

The exact RACI or responsibility model should be adapted to the service.

Supplier requirements should also define **security review frequency**.

For example:

```text
Low Risk:
Every 24 Months

Medium Risk:
Every 12–24 Months

High Risk:
Annual

Critical:
Annual + Continuous Monitoring
```

The organization should also reserve the right to reassess the supplier following significant changes.

Supplier security requirements should be reviewed before contract execution.

The review process can be:

```text
Business Requirement
        ↓
Supplier Risk Classification
        ↓
Security Requirements
        ↓
Supplier Negotiation
        ↓
Legal Review
        ↓
Security Review
        ↓
Risk Approval
        ↓
Contract Execution
        ↓
Supplier Onboarding
        ↓
Ongoing Monitoring
```

The security requirements should be incorporated into the appropriate contractual documents.

They may appear in:

```text
Master Services Agreement
Statement of Work
Data Processing Agreement
Security Schedule
Supplier Security Addendum
Service Level Agreement
```

The specific contractual structure depends on the organization's procurement and legal framework.

A practical high-risk supplier security schedule may look like:

```text
SUPPLIER SECURITY SCHEDULE

Supplier:
ABC Cloud Services

Service:
Production Cloud Hosting

Risk Tier:
Critical

1. Information Security Governance
   Formal security program required.

2. Access Control
   Least privilege and privileged access
   controls required.

3. Authentication
   MFA required for privileged access.

4. Data Protection
   Organizational data must be protected
   according to agreed classification.

5. Encryption
   Sensitive data encrypted in transit
   and at rest.

6. Vulnerability Management
   Critical vulnerabilities must be
   remediated within agreed timeframes.

7. Security Testing
   Periodic security testing required.

8. Incident Notification
   Security incidents must be reported
   within the agreed contractual period.

9. Business Continuity
   Agreed RTO and RPO requirements must
   be maintained.

10. Subcontractors
    Material subcontractors must be
    appropriately assessed and managed.

11. Audit and Assurance
    Appropriate security assurance evidence
    must be provided.

12. Data Deletion
    Organizational data must be securely
    deleted at contract termination.

13. Security Exceptions
    Exceptions require documented approval.

14. Ongoing Monitoring
    Supplier risk will be reviewed periodically.
```

The supplier should acknowledge these requirements before service commencement.

The organization should then monitor compliance throughout the relationship.

For example:

```text
Supplier Onboarding
        ↓
Contractual Security Requirements
        ↓
Initial Due Diligence
        ↓
Security Evidence
        ↓
Risk Approval
        ↓
Periodic Assessment
        ↓
Continuous Monitoring
        ↓
Issue Management
        ↓
Reassessment
        ↓
Renewal / Exit
```

Supplier security requirements should also be updated when the organization's risk environment changes.

Examples include:

```text
New Regulation
New Security Threat
New Data Classification
New Technology
New Business Service
Major Security Incident
Supplier Acquisition
New Subcontractor
Change in Service Architecture
```

The organization should avoid using static supplier requirements that remain unchanged for many years despite major changes in the threat and regulatory environment.

The final objective is to create a clear contractual and operational security baseline.

A mature supplier security requirement framework should ensure that:

```text
Security Expectations Are Defined
        ↓
Responsibilities Are Clear
        ↓
Controls Are Contractually Established
        ↓
Evidence Is Required
        ↓
Compliance Is Monitored
        ↓
Exceptions Are Controlled
        ↓
Deficiencies Are Remediated
        ↓
Supplier Risk Is Reassessed
```

The key principle is:

> **Supplier security requirements establish clear, risk-based, and enforceable security expectations that suppliers must meet throughout the relationship, from onboarding and service delivery through monitoring, remediation, renewal, and contract termination.**

**Part 4 – Third-Party Risk Register**

A Third-Party Risk Register is a structured record used to identify, assess, monitor, and manage cybersecurity, privacy, compliance, operational, and resilience risks associated with suppliers, vendors, contractors, service providers, and other external parties.

The register provides the organization with a centralized view of third-party risks and helps ensure that identified risks have accountable owners, defined treatment actions, target dates, and appropriate management oversight.

The third-party risk management lifecycle can be represented as:

```text
Vendor Identification
        ↓
Vendor Classification
        ↓
Inherent Risk Assessment
        ↓
Due Diligence
        ↓
Control Assessment
        ↓
Risk Identification
        ↓
Risk Recording
        ↓
Risk Treatment
        ↓
Risk Monitoring
        ↓
Risk Reassessment
        ↓
Risk Closure / Acceptance
```

A practical Third-Party Risk Register can contain:

```text
THIRD-PARTY RISK REGISTER

Risk ID:

Vendor ID:

Vendor Name:

Service:

Business Owner:

Vendor Owner:

Risk Description:

Risk Category:

Risk Source:

Affected Asset / Service:

Data Involved:

Business Criticality:

Regulatory Impact:

Inherent Likelihood:

Inherent Impact:

Inherent Risk Rating:

Existing Controls:

Control Effectiveness:

Residual Likelihood:

Residual Impact:

Residual Risk Rating:

Risk Treatment:

Corrective Action:

Action Owner:

Target Date:

Risk Owner:

Risk Acceptance Required:

Risk Acceptance Authority:

Risk Status:

Risk Due Date:

Evidence:

Last Review Date:

Next Review Date:

Escalation Status:

Comments:
```

The first step is to assign a unique **Risk ID**.

For example:

```text
TPR-2026-001
TPR-2026-002
TPR-2026-003
```

The identifier should remain unique throughout the lifecycle of the risk.

The register should also contain a **Vendor ID** that links the risk to the organization's vendor master record.

For example:

```text
Vendor ID:
VEN-00457

Vendor:
ABC Cloud Services

Service:
Production Cloud Infrastructure
```

This creates traceability between procurement, vendor management, third-party risk management, and cybersecurity GRC.

The register should identify the **business owner**.

For example:

```text
Business Owner:
Head of Infrastructure
```

The business owner understands why the organization uses the vendor and the importance of the service to business operations.

The **vendor owner** may be a separate role responsible for managing the commercial and operational relationship.

For example:

```text
Business Owner:
Chief Technology Officer

Vendor Owner:
Vendor Management Manager
```

The **risk owner** is responsible for managing the identified risk and ensuring that an appropriate risk decision is made.

These roles should not automatically be assumed to be the same person.

The register should contain a clear **risk description**.

A weak risk description would be:

```text
Cloud security risk.
```

A stronger description would be:

```text
The supplier's privileged administrative
accounts are not consistently protected
with MFA, which may increase the risk of
unauthorized administrative access to the
production environment.
```

A strong risk description should explain:

```text
Cause
Risk Event
Potential Consequence
```

A useful structure is:

```text
Because of [cause],
there is a risk that [event],
which could result in [impact].
```

For example:

```text
Because the supplier does not enforce MFA
for all privileged accounts, there is a risk
that an unauthorized individual could gain
administrative access, resulting in compromise
of production systems or sensitive information.
```

The register should classify the **risk category**.

Possible categories include:

```text
Cybersecurity
Information Security
Privacy
Compliance
Operational
Availability
Confidentiality
Integrity
Business Continuity
Third-Party Dependency
Concentration Risk
Data Protection
Technology
Financial
Reputational
```

Multiple categories may apply to the same risk.

For example:

```text
Primary Category:
Cybersecurity

Secondary Category:
Operational
Privacy
```

The register should identify the **risk source**.

For example:

```text
Risk Source:

Vendor Assessment
Security Questionnaire
Audit Finding
Security Incident
Penetration Test
Contract Review
Compliance Assessment
Threat Intelligence
Business Continuity Review
Management Review
```

This provides traceability back to the activity that identified the risk.

The register should identify the **affected asset or service**.

For example:

```text
Affected Service:
Customer Payment Platform

Affected Assets:
Cloud Infrastructure
Customer Database
Application Platform
```

This helps determine the potential business impact.

The register should identify the **data involved**.

For example:

```text
Data:

Customer Personal Data
Payment Information
Authentication Information
Confidential Business Information
```

Data classification should be aligned with the organization's data classification framework.

The register should also capture **business criticality**.

For example:

```text
Critical
High
Medium
Low
```

A supplier supporting a critical business process should normally receive greater risk attention than a supplier supporting a non-critical activity.

The organization should also identify **regulatory impact**.

For example:

```text
Regulatory Impact:

GDPR
NIS2
DORA
PCI DSS
Industry Requirements
Contractual Requirements
```

The actual regulatory requirements should be determined based on the organization's circumstances and the services provided.

The register should assess **inherent risk** before considering mitigating controls.

A simple methodology can use:

```text
Likelihood × Impact = Inherent Risk
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

A five-level likelihood scale might be:

```text
1 – Rare
2 – Unlikely
3 – Possible
4 – Likely
5 – Almost Certain
```

A five-level impact scale might be:

```text
1 – Insignificant
2 – Minor
3 – Moderate
4 – Major
5 – Severe
```

The resulting risk matrix could be:

```text
              IMPACT
          1    2    3    4    5

L  5       5   10   15   20   25
I  4       4    8   12   16   20
K  3       3    6    9   12   15
E  2       2    4    6    8   10
L  1       1    2    3    4    5
```

The organization should define the thresholds for:

```text
Low
Medium
High
Critical
```

For example:

```text
1–4:
Low

5–9:
Medium

10–15:
High

16–25:
Critical
```

The exact thresholds should be defined by the organization's approved risk methodology.

The register should document the **existing controls**.

For example:

```text
Existing Controls:

MFA for most privileged accounts
Privileged Access Management
Network Segmentation
Security Monitoring
Quarterly Access Reviews
Incident Response Process
```

Controls should be described clearly enough to understand how they reduce the identified risk.

The organization should then evaluate **control effectiveness**.

For example:

```text
Effective
Partially Effective
Ineffective
Not Tested
Unknown
```

A vendor may have a documented control that appears appropriate but is not operating effectively.

For example:

```text
Control:
Quarterly Access Review

Documentation:
Available

Evidence:
Incomplete

Assessment:
Partially Effective
```

The register should then assess **residual risk**.

Residual risk is the risk remaining after considering the effectiveness of existing controls.

For example:

```text
Inherent Risk:
Critical

Existing Controls:
Strong

Residual Risk:
Medium
```

Another example:

```text
Inherent Risk:
High

Existing Controls:
Weak

Residual Risk:
High
```

This distinction is fundamental to third-party risk management.

The organization should then determine the appropriate **risk treatment**.

Common treatment options include:

```text
Mitigate
Accept
Transfer
Avoid
```

For example:

```text
Risk:
Vendor does not support MFA for a legacy
administrative interface.

Treatment:
Mitigate

Action:
Replace legacy interface with MFA-enabled
administrative access.
```

Risk treatment should be selected based on the organization's risk appetite and business requirements.

The register should contain the **corrective action**.

A weak action would be:

```text
Improve vendor security.
```

A stronger action would be:

```text
Require the supplier to implement MFA for
all privileged administrative access and
provide evidence of implementation.
```

The corrective action should address the specific risk.

The register should identify the **action owner**.

For example:

```text
Action Owner:
Vendor Security Manager
```

The organization may also identify an internal owner responsible for monitoring the remediation.

For example:

```text
Internal Owner:
Third-Party Risk Manager
```

The corrective action should have a **target completion date**.

For example:

```text
Target Date:
30 November 2026
```

The date should be realistic but should also reflect the severity of the risk.

Critical risks generally require faster remediation than low-risk issues.

The register should identify the **risk owner**.

For example:

```text
Risk Owner:
Chief Information Security Officer
```

The risk owner should have appropriate authority to make or approve the risk decision.

The register should identify whether **formal risk acceptance** is required.

For example:

```text
Risk Acceptance Required:
Yes
```

If risk acceptance is required, the register should identify the **risk acceptance authority**.

For example:

```text
Risk Acceptance Authority:
CISO

Executive Approval:
Required
```

The approval level should correspond to the organization's risk governance framework.

A high or critical third-party risk may require senior management approval.

The register should maintain a **risk status**.

Common statuses include:

```text
Open
Under Assessment
Treatment in Progress
Monitoring
Accepted
Overdue
Escalated
Closed
```

For example:

```text
Status:
Treatment in Progress
```

The status should accurately reflect the current condition of the risk.

A risk should not be marked "Closed" merely because a remediation task was created.

The risk should be closed only when the defined closure criteria have been satisfied.

The register should also include a **risk due date**.

This is particularly important for risks requiring remediation.

For example:

```text
Risk Due Date:
31 December 2026
```

The GRC team should monitor approaching and overdue due dates.

The register should also identify **supporting evidence**.

For example:

```text
Evidence:

Vendor Security Assessment
ISO/IEC 27001 Certificate
SOC 2 Report
Penetration Test Summary
Contract Security Schedule
Remediation Evidence
Management Approval
```

Evidence should be linked to the risk record where the GRC platform supports document or evidence management.

The register should capture the **last review date**.

For example:

```text
Last Review:
15 August 2026
```

It should also contain the **next review date**.

For example:

```text
Next Review:
15 November 2026
```

Review frequency should be based on risk.

For example:

```text
Low:
Annual or Biennial

Medium:
Annual

High:
Quarterly

Critical:
Continuous Monitoring / Monthly Review
```

The exact frequency should be determined by the organization's methodology.

The register should support **risk escalation**.

For example:

```text
Escalation Status:

Normal
Management Attention
Executive Escalation
Critical Escalation
```

An escalation may be triggered when:

```text
Remediation Is Overdue
Risk Increases
Control Fails
Vendor Has Major Incident
Regulatory Exposure Increases
Critical Dependency Emerges
Risk Exceeds Appetite
```

The GRC professional should monitor third-party risks against the organization's **risk appetite**.

For example:

```text
Risk Appetite:
Medium

Vendor Residual Risk:
High

Result:
Outside Risk Appetite
```

This should trigger management action.

The organization may then:

```text
Mitigate
Accept
Transfer
Avoid
Escalate
```

A third-party risk register should also support **risk aggregation**.

For example:

```text
Vendor A:
High Risk

Vendor B:
High Risk

Vendor C:
Medium Risk

Vendor D:
Critical Risk
```

Management can use this information to understand the overall third-party risk landscape.

The organization can calculate metrics such as:

```text
Total Third Parties:
250

High-Risk Third Parties:
32

Critical Third Parties:
8

Open Third-Party Risks:
47

Overdue Risks:
9

Risks Outside Appetite:
6
```

These metrics can be displayed in a GRC dashboard.

The organization should also monitor **risk trends**.

For example:

```text
Q1:
55 Open Third-Party Risks

Q2:
49 Open Third-Party Risks

Q3:
43 Open Third-Party Risks

Q4:
35 Open Third-Party Risks
```

A declining number of risks may indicate improved risk management, but the organization should also consider changes in vendor population, assessment coverage, and business activity.

The register should also identify **concentration risk**.

Concentration risk occurs when an organization becomes heavily dependent on a small number of suppliers or a single supplier for critical services.

For example:

```text
Cloud Infrastructure:

70% Provider A
20% Provider B
10% Provider C
```

If Provider A experiences a major outage, the organization's exposure may be significant.

The register can therefore capture:

```text
Critical Dependency:
Yes

Alternative Supplier:
Limited

Exit Difficulty:
High

Concentration Risk:
High
```

This information can be important for business continuity and resilience planning.

The register should also identify **fourth-party dependency risk**.

For example:

```text
Organization
     ↓
Cloud Provider
     ↓
Data Center Provider
     ↓
Infrastructure Provider
```

The organization may not have a direct contractual relationship with the fourth party, but its failure could still affect the service.

The GRC professional should therefore consider material dependencies where appropriate.

The register should also capture **vendor security incidents**.

For example:

```text
Incident ID:
INC-2026-078

Vendor:
ABC Cloud

Incident:
Unauthorized access attempt

Impact:
No customer data confirmed compromised

Response:
Contained

Corrective Action:
Additional authentication controls
```

The incident may result in a new third-party risk.

For example:

```text
Existing Risk:
Medium

Post-Incident Risk:
High
```

This demonstrates why third-party risk registers should be connected to incident management.

The register can also connect third-party risks to:

```text
Vendor Records
Contracts
Controls
Compliance Requirements
Audit Findings
Security Incidents
Business Continuity Plans
Risk Acceptance Records
Corrective Actions
```

This creates an integrated GRC information structure.

A practical example of a completed third-party risk record is:

```text
Risk ID:
TPR-2026-014

Vendor:
ABC Cloud Services

Service:
Production Cloud Hosting

Business Owner:
Head of Infrastructure

Risk Owner:
CISO

Risk Category:
Cybersecurity

Risk Source:
Vendor Due Diligence

Affected Service:
Production Infrastructure

Data:
Confidential Customer Data

Business Criticality:
Critical

Risk Description:

The supplier does not enforce MFA for all
privileged administrative accounts, increasing
the risk of unauthorized access to production
systems and sensitive information.

Inherent Likelihood:
4 – Likely

Inherent Impact:
5 – Severe

Inherent Risk:
20 – Critical

Existing Controls:

Privileged Access Management
Network Segmentation
Security Monitoring
Access Reviews

Control Effectiveness:
Partially Effective

Residual Likelihood:
3 – Possible

Residual Impact:
5 – Severe

Residual Risk:
15 – High

Risk Treatment:
Mitigate

Corrective Action:

Implement MFA for all privileged administrative
accounts and provide implementation evidence.

Action Owner:
Vendor Security Manager

Target Date:
30 November 2026

Risk Acceptance Required:
No

Status:
Treatment in Progress

Last Review:
15 August 2026

Next Review:
15 September 2026
```

After remediation, the record may be updated:

```text
Corrective Action:
Completed

Evidence:
MFA Configuration Report
Access Control Test Results

Control Effectiveness:
Effective

Residual Likelihood:
1 – Rare

Residual Impact:
5 – Severe

Residual Risk:
5 – Medium

Risk Decision:
Accepted Within Risk Appetite

Status:
Monitoring
```

The risk may eventually be closed if the risk condition is eliminated or the applicable risk management process allows closure.

For example:

```text
Status:
Closed

Closure Basis:

MFA implemented for all privileged accounts.
Validation completed.
No outstanding remediation.
Residual risk within approved tolerance.
```

However, some third-party risks should remain under continuous monitoring rather than being permanently closed.

For example:

```text
Critical Cloud Provider Dependency

Risk Status:
Monitoring
```

This is because the underlying dependency continues to exist even though controls may be effective.

The Third-Party Risk Register should therefore distinguish between:

```text
Risk Resolved
Risk Mitigated
Risk Accepted
Risk Transferred
Risk Avoided
Risk Under Continuous Monitoring
```

The register should be periodically reviewed for outdated information.

The GRC professional should verify:

```text
Vendor Information
Service Information
Risk Rating
Control Effectiveness
Open Findings
Risk Owner
Treatment Status
Target Dates
Evidence
Regulatory Requirements
Subcontractor Dependencies
Next Review Date
```

Changes should be documented rather than silently overwritten where historical traceability is important.

Version history may include:

```text
15 Aug 2026:
Initial Risk Assessment

15 Sep 2026:
Vendor Provided Remediation Evidence

30 Sep 2026:
Control Validation Completed

01 Oct 2026:
Residual Risk Reduced

01 Oct 2026:
Risk Status Changed to Monitoring
```

This creates an auditable record of the risk lifecycle.

A mature Third-Party Risk Register should ultimately provide management with answers to questions such as:

```text
Which vendors present the greatest risk?

Which vendors support critical business services?

Which vendors process sensitive information?

Which risks are outside risk appetite?

Which vendor risks are overdue?

Which vendors have unresolved security findings?

Which vendors have experienced security incidents?

Where do we have concentration risk?

Which vendor risks require executive attention?
```

The register should not become merely a spreadsheet containing hundreds of disconnected risk entries. It should function as a management tool that connects third-party risk information with business decisions, remediation activities, contracts, controls, compliance requirements, and ongoing monitoring.

A mature third-party risk management structure can be represented as:

```text
Vendor Inventory
        ↓
Vendor Classification
        ↓
Risk Assessment
        ↓
Due Diligence
        ↓
Security Requirements
        ↓
Third-Party Risk Register
        ↓
Risk Treatment
        ↓
Corrective Actions
        ↓
Continuous Monitoring
        ↓
Management Reporting
```

The key principle is:

> **A Third-Party Risk Register provides a centralized and auditable view of supplier risks, linking each risk to its business context, responsible owner, existing controls, treatment actions, residual risk, evidence, and management decision so that third-party risk remains actively governed throughout the supplier lifecycle.**




