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



