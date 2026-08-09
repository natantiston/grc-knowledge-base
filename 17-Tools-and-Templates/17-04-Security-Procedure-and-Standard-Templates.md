**Chapter:** 17 – Tools and Templates

**Topic:** Security Procedure and Standard Templates
**Difficulty:** Intermediate
**Estimated Reading Time:** 10–15 minutes

# **17.4 Security Procedure and Standard Templates**

## **Part 1 – Policy Template**

A **security policy template** is one of the most fundamental tools in a GRC program. It provides a consistent structure for documenting management requirements, security expectations, responsibilities, and governance decisions.

A policy answers the question:

> **"What does the organization require, and why?"**

A policy should not normally explain every technical step required to implement a security requirement. Those details belong in standards, procedures, and work instructions.

A practical GRC documentation hierarchy is:

```text
Policy
   ↓
Standard
   ↓
Procedure
   ↓
Work Instruction
```

For example:

```text
Access Control Policy
        ↓
Authentication Standard
        ↓
User Access Review Procedure
        ↓
Step-by-Step Access Review Work Instruction
```

This hierarchy prevents policies from becoming excessively technical while ensuring that organizational requirements can be translated into operational activities.

---

## **1.1 Purpose of a Security Policy**

A security policy establishes formal organizational direction.

It can define:

* What the organization requires.
* Why the requirement exists.
* Who is responsible.
* What activities are permitted or prohibited.
* What controls are expected.
* How exceptions are managed.
* How compliance is monitored.
* What happens when requirements are not followed.

For example:

> All employees and contractors must use approved authentication mechanisms when accessing organizational information systems.

This is a policy-level requirement.

The technical configuration required to enforce MFA would normally be documented in a security standard or technical procedure.

---

## **1.2 Policy vs Standard vs Procedure vs Guideline**

Understanding the distinction between these documents is essential for a GRC professional.

### Policy

Defines **what is required and why**.

Example:

> Privileged access must be strongly authenticated.

### Standard

Defines **specific mandatory requirements**.

Example:

> All privileged accounts must use phishing-resistant MFA.

### Procedure

Defines **how the requirement is performed**.

Example:

> The IAM team must enroll privileged users in the approved authentication platform and verify successful MFA registration.

### Guideline

Provides **recommended practices**.

Example:

> Users should avoid approving unexpected authentication requests.

The distinction can be summarized as:

| Document  | Primary Question                        |
| --------- | --------------------------------------- |
| Policy    | What must we do and why?                |
| Standard  | What specific requirements must be met? |
| Procedure | How do we perform the activity?         |
| Guideline | What is recommended?                    |

---

## **1.3 Why Policies Matter in GRC**

Policies provide the governance foundation for many GRC activities.

A policy can establish requirements for:

* Information security.
* Access control.
* Asset management.
* Data classification.
* Security awareness.
* Incident management.
* Vulnerability management.
* Third-party security.
* Cloud security.
* Business continuity.
* Acceptable use.
* Remote work.
* Cryptography.
* Change management.
* AI governance.

The policy requirement can then be mapped to controls, risks, evidence, and compliance requirements.

For example:

```text
Policy Requirement
        ↓
Security Control
        ↓
Evidence
        ↓
Control Testing
        ↓
Compliance Result
```

This creates traceability throughout the GRC environment.

---

## **1.4 Policy Lifecycle**

A mature policy should have a defined lifecycle.

A typical lifecycle is:

```text
Business Requirement
        ↓
Risk Assessment
        ↓
Policy Development
        ↓
Stakeholder Review
        ↓
Legal / Regulatory Review
        ↓
Management Approval
        ↓
Publication
        ↓
Communication
        ↓
Implementation
        ↓
Compliance Monitoring
        ↓
Periodic Review
        ↓
Revision
        ↓
Reapproval
```

Policy management should therefore be treated as an ongoing governance process rather than a one-time documentation activity.

---

## **1.5 Policy Template Structure**

A practical security policy template can contain:

```text
POLICY TITLE

Document ID:
Version:
Policy Owner:
Approved By:
Effective Date:
Review Date:
Classification:
Status:

1. Purpose
2. Scope
3. Policy Statement
4. Objectives
5. Roles and Responsibilities
6. Requirements
7. Exceptions
8. Compliance
9. Enforcement
10. Related Documents
11. References
12. Document Control
```

The organization can modify this structure depending on the type and complexity of the policy.

---

## **1.6 Document Metadata**

Controlled policies should contain basic document metadata.

Example:

| Field          | Example                     |
| -------------- | --------------------------- |
| Document ID    | SEC-POL-001                 |
| Title          | Information Security Policy |
| Version        | 3.0                         |
| Policy Owner   | CISO                        |
| Approved By    | CEO                         |
| Effective Date | 01 September 2026           |
| Review Date    | 01 September 2027           |
| Classification | Internal                    |
| Status         | Approved                    |

Document metadata provides version control and helps demonstrate that the organization is using the current approved version.

---

## **1.7 Policy Title**

The title should clearly communicate the subject of the policy.

Examples include:

* Information Security Policy.
* Access Control Policy.
* Acceptable Use Policy.
* Data Classification Policy.
* Incident Response Policy.
* Third-Party Security Policy.
* Cloud Security Policy.
* Security Awareness Policy.
* Business Continuity Policy.
* Artificial Intelligence Governance Policy.

A policy title should be specific enough that users can understand its purpose without reading the entire document.

---

## **1.8 Purpose Statement**

The purpose explains why the policy exists.

For example:

> The purpose of this policy is to establish requirements for protecting organizational information and information systems against unauthorized access, disclosure, modification, destruction, and disruption.

A purpose statement should be concise.

It should explain the security or business objective without turning into a detailed implementation procedure.

---

## **1.9 Scope**

The scope defines who and what the policy applies to.

For example:

> This policy applies to all employees, contractors, consultants, temporary personnel, third parties, information systems, applications, devices, and cloud services used to conduct organizational business.

Depending on the organization, scope may also define:

* Business units.
* Subsidiaries.
* Geographic locations.
* Information systems.
* Applications.
* Data.
* Cloud services.
* Third parties.

A poorly defined scope can create ambiguity about who is actually required to comply.

---

## **1.10 Policy Statement**

The policy statement establishes management's formal direction.

Example:

> The organization shall establish, maintain, and continuously improve an information security program appropriate to its business requirements, risk profile, legal obligations, regulatory requirements, and contractual commitments.

A policy statement should be sufficiently broad to establish direction without becoming an implementation procedure.

---

## **1.11 Mandatory Language**

Policy language should clearly distinguish mandatory requirements from recommendations.

### Must / Shall

Indicates a mandatory requirement.

> Employees must complete security awareness training annually.

### Should

Generally indicates a recommendation.

> Business units should perform periodic security reviews.

### May

Indicates permission or an available option.

> The CISO may approve temporary exceptions where appropriate.

If a requirement is mandatory, avoid weak language such as:

> Employees are encouraged to use MFA.

A stronger requirement would be:

> Employees must use MFA when accessing systems designated as requiring multi-factor authentication.

Clear language makes policies easier to implement, audit, and enforce.

---

## **1.12 Policy Objectives**

Policy objectives explain what the policy is intended to accomplish.

For an Access Control Policy, objectives could include:

* Prevent unauthorized access.
* Apply least privilege.
* Enforce appropriate authentication.
* Protect privileged accounts.
* Review access periodically.
* Remove access when it is no longer required.

Objectives help connect the policy to organizational risks and controls.

---

## **1.13 Roles and Responsibilities**

Policies should identify accountable roles.

Example:

### Board / Executive Management

Provides governance oversight and approves significant security direction.

### CISO

Owns the information security program and establishes security governance requirements.

### IT

Implements and operates applicable technical controls.

### HR

Supports employee lifecycle activities relevant to security.

### Procurement

Ensures security requirements are incorporated into applicable supplier relationships.

### Employees and Contractors

Follow security requirements and report suspected security incidents.

Clear ownership is essential because a policy without accountability is difficult to enforce.

---

## **1.14 Policy Requirements**

The requirements section contains the organization's mandatory security expectations.

For example:

### Access Management

The organization must:

1. Assign unique user identities.
2. Apply least privilege.
3. Protect privileged accounts.
4. Use appropriate authentication mechanisms.
5. Review access periodically.
6. Remove access when no longer required.
7. Document and approve exceptions.

The policy establishes **what must happen**.

The technical implementation should normally be documented separately.

---

## **1.15 Policy Exceptions**

Organizations will sometimes have legitimate situations where a requirement cannot immediately be met.

The policy should therefore establish an exception process.

Example:

> Exceptions to this policy must be formally documented, risk assessed, approved by the designated authority, and assigned an expiration or review date.

An exception request can include:

* Requirement being excepted.
* Business justification.
* Risk assessment.
* Compensating controls.
* Risk owner.
* Approval authority.
* Requested duration.
* Expiration date.

---

## **1.16 Example – Security Policy Exception**

Suppose an organization requires MFA for all privileged accounts.

A legacy application cannot technically support MFA.

The exception record might contain:

```text
Requirement:
Privileged accounts must use MFA.

Exception:
Legacy application does not support the approved MFA mechanism.

Business Justification:
Application replacement is scheduled for Q1 2027.

Compensating Controls:
- Network isolation
- Restricted administrative access
- Enhanced monitoring

Residual Risk:
High

Risk Owner:
Application Director

Approval:
CISO

Expiration:
31 December 2026
```

The exception should be reviewed periodically.

The fact that a system is old should not automatically justify an indefinite exception.

---

## **1.17 Compliance**

The policy should explain how compliance will be assessed.

Example:

> Compliance with this policy may be assessed through audits, control testing, security assessments, monitoring activities, management reviews, and other assurance activities.

This gives the organization a formal basis for monitoring whether policy requirements are being followed.

---

## **1.18 Enforcement**

The policy should explain potential consequences of non-compliance.

Example:

> Violations of this policy may result in corrective action, restriction of access, disciplinary measures, contractual remedies, or other actions consistent with applicable organizational requirements and law.

The exact enforcement mechanism depends on:

* Employment arrangements.
* Applicable law.
* Internal disciplinary processes.
* Supplier contracts.
* Regulatory requirements.

---

## **1.19 Related Documents**

Policies should identify related standards and procedures.

For example:

**Related Documents**

* Access Control Standard.
* Authentication Standard.
* Password Standard.
* Identity Management Procedure.
* Privileged Access Procedure.
* Security Incident Procedure.
* Risk Management Policy.
* Data Classification Policy.

This establishes the relationship between governance documents.

---

## **1.20 References**

A security policy may reference applicable frameworks, regulations, and standards.

Examples include:

* ISO/IEC 27001.
* ISO/IEC 27002.
* NIST Cybersecurity Framework.
* NIST SP 800-53.
* COBIT.
* GDPR.
* NIS2.
* Industry-specific regulations.
* Customer contractual requirements.

References should provide context and traceability.

The organization should avoid simply copying framework language into its policies.

The policy should reflect the organization's own:

* Business environment.
* Risks.
* Legal obligations.
* Technology.
* Governance structure.

---

## **1.21 Example – Acceptable Use Policy**

A simplified acceptable use requirement might state:

> Organizational information systems must be used responsibly, lawfully, and only for authorized purposes.

Supporting requirements could include:

* Users must protect authentication credentials.
* Users must not share passwords.
* Users must not install unauthorized software.
* Users must not access systems without authorization.
* Users must report suspected security incidents.
* Organizational information must not be transferred to unauthorized services.

Detailed technical requirements should normally be documented in applicable standards and procedures.

---

## **1.22 Example – Access Control Policy**

A practical Access Control Policy could establish:

```text
Policy Objective:
Ensure access to organizational systems is authorized,
appropriate, and regularly reviewed.

Requirements:

1. Unique identities must be assigned.
2. Access must be based on business need.
3. Least privilege must be applied.
4. Privileged access must receive additional protection.
5. MFA must be used where required.
6. Access must be reviewed periodically.
7. Access must be removed when no longer required.
8. Exceptions must be formally approved.
```

This provides governance direction without specifying every technical implementation detail.

---

## **1.23 Policy-to-Control Mapping**

A mature GRC program should map policy requirements to controls.

Example:

| Policy Requirement               | Control                     | Evidence       |
| -------------------------------- | --------------------------- | -------------- |
| MFA required                     | MFA enforcement             | IAM report     |
| Access reviewed quarterly        | Quarterly access review     | Review records |
| Access removed after termination | Joiner/mover/leaver control | HR/IAM records |
| Privileged access restricted     | PAM control                 | PAM report     |

This creates a traceability chain:

```text
Policy
   ↓
Requirement
   ↓
Control
   ↓
Evidence
   ↓
Testing
   ↓
Compliance Result
```

This is extremely valuable during audits and assessments.

---

## **1.24 Policy-to-Risk Mapping**

Policies should also be connected to organizational risks.

For example:

```text
Risk:
Unauthorized access to sensitive information
        ↓
Policy:
Access Control Policy
        ↓
Requirement:
Least privilege and strong authentication
        ↓
Controls:
IAM + PAM + MFA
        ↓
Testing:
Access Review + MFA Testing
```

This demonstrates that policy requirements are driven by business and security risks.

---

## **1.25 Policy Approval**

Every formal policy should have a defined approval authority.

Examples:

| Policy                      | Possible Approver             |
| --------------------------- | ----------------------------- |
| Information Security Policy | CEO / Board                   |
| Access Control Policy       | CIO / CISO                    |
| Data Protection Policy      | DPO / Executive Management    |
| Acceptable Use Policy       | CIO / CISO / HR               |
| Third-Party Security Policy | CISO / Procurement Leadership |

The appropriate approval authority depends on the organization's governance structure.

The important principle is:

> **The person approving the policy should have sufficient authority to establish the requirement.**

---

## **1.26 Policy Review**

Policies should have a defined review cycle.

Common approaches include:

* Annual review.
* Biennial review.
* Risk-based review.
* Event-driven review.

A policy should also be reviewed when:

* Regulations change.
* Major incidents occur.
* Business processes change.
* Technology changes significantly.
* Organizational responsibilities change.
* Risk appetite changes.
* Audit findings identify weaknesses.

An annual review date should not prevent an earlier review when a significant change occurs.

---

## **1.27 Version Control**

Example:

| Version | Date | Change                            | Approved By |
| ------- | ---- | --------------------------------- | ----------- |
| 1.0     | 2024 | Initial policy                    | CEO         |
| 2.0     | 2025 | Updated access requirements       | CISO        |
| 3.0     | 2026 | Added cloud security requirements | CIO         |

Version control provides historical traceability.

It allows auditors and management to determine:

* Which version was effective at a particular time.
* What changed.
* Who approved the change.
* When the change became effective.

---

## **1.28 Policy Communication**

Approval does not automatically create compliance.

Employees need to understand:

* What changed.
* Why it changed.
* What they must do.
* When the requirement becomes effective.
* Where the policy can be accessed.

Communication methods can include:

* Email.
* Intranet.
* Security awareness training.
* LMS.
* Town halls.
* Management briefings.
* Employee acknowledgement.

Significant policy changes may require formal acknowledgement.

---

## **1.29 Policy Acknowledgement**

Some policies should require employees or contractors to formally acknowledge that they have read and understood them.

For example:

> Employees must acknowledge the Acceptable Use Policy during onboarding and whenever material changes are made to the policy.

Evidence could include:

* LMS completion records.
* Electronic acknowledgement.
* HR records.

Not every policy necessarily requires individual acknowledgement. The requirement should be based on organizational risk, legal considerations, and the nature of the policy.

---

## **1.30 Policy Metrics**

A GRC team can use metrics to monitor policy governance.

Examples include:

* Percentage of policies reviewed on time.
* Number of overdue policy reviews.
* Percentage of policies approved.
* Number of policy exceptions.
* Number of policy violations.
* Percentage of employees acknowledging required policies.
* Number of audit findings related to policies.

Example:

> 96% of policies were reviewed within the required review period.

This gives management a measurable view of policy governance.

---

## **1.31 Policy Governance Dashboard**

A policy dashboard might contain:

| Metric                             | Result |
| ---------------------------------- | -----: |
| Total Policies                     |     84 |
| Approved                           |     81 |
| Under Review                       |      2 |
| Overdue                            |      1 |
| Active Exceptions                  |      7 |
| Policies Requiring Acknowledgement |     12 |
| Employee Acknowledgement           |    98% |

This allows the GRC team to identify policy governance issues quickly.

---

## **1.32 Common Policy Problems**

### Problem 1 – Policies Are Too Generic

> "The organization shall maintain adequate security."

This does not provide enough direction.

### Problem 2 – Policies Are Too Technical

A policy should not contain hundreds of configuration instructions.

### Problem 3 – No Owner

Nobody is accountable for maintaining the document.

### Problem 4 – No Approval

The document may not represent formal organizational direction.

### Problem 5 – No Exception Process

The organization has no formal method for handling legitimate deviations.

### Problem 6 – No Enforcement

The organization cannot explain what happens when requirements are ignored.

### Problem 7 – No Review

The policy becomes outdated.

### Problem 8 – Policy Exists but Controls Do Not

The organization has documented requirements but has not implemented them.

### Problem 9 – Controls Exist but Policy Does Not Support Them

Security teams may implement controls without sufficient governance direction.

### Problem 10 – Framework Copy-and-Paste

Copying ISO, NIST, or regulatory language does not automatically create an effective organizational policy.

---

## **1.33 Practical Exercise – Build an Access Control Policy**

Create a short Access Control Policy containing:

1. Purpose.
2. Scope.
3. Policy statement.
4. Objectives.
5. Roles and responsibilities.
6. Access requirements.
7. Privileged access requirements.
8. MFA requirements.
9. Access review requirements.
10. Joiner/mover/leaver requirements.
11. Exceptions.
12. Compliance.
13. Enforcement.
14. Review frequency.

Then map each major requirement to at least one security control.

---

## **1.34 Practical Exercise – Review a Policy Statement**

Consider this statement:

> "Employees should use strong passwords and protect company information."

Identify the weaknesses.

Consider:

* Is "should" sufficiently mandatory?
* What constitutes a strong password?
* Who is covered?
* What information must be protected?
* What controls support the requirement?
* How is compliance measured?
* What happens if the requirement is violated?

Then rewrite the requirement so that it becomes clear, measurable, and enforceable.

---

## **1.35 Practical Exercise – Policy Exception**

Scenario:

> A business unit requests an exception to the organization's encryption policy because an old application cannot support the approved encryption technology.

Create an exception record containing:

* Requirement.
* Business justification.
* Risk.
* Compensating controls.
* Risk owner.
* Approval authority.
* Expiration date.
* Review frequency.

Then determine whether the exception should be approved, rejected, or approved temporarily with additional controls.

---

## **1.36 Practical Exercise – Policy-to-Control Mapping**

Take the following policy requirement:

> "Privileged access must be reviewed at least quarterly."

Identify:

**Policy Requirement**

Quarterly privileged access review.

**Control**

IAM performs quarterly privileged access reviews.

**Evidence**

Approved access review report.

**Test**

Sample privileged accounts and verify review evidence.

**Potential Finding**

Missing or incomplete access reviews.

**Risk**

Unauthorized privileged access may remain active.

This demonstrates how a simple policy requirement becomes an auditable GRC control.

---

## **1.37 Practical Exercise – Policy Lifecycle**

Create a lifecycle for a new Cloud Security Policy:

```text
Business Need
      ↓
Risk Assessment
      ↓
Draft Policy
      ↓
Security Review
      ↓
Legal / Privacy Review
      ↓
Business Stakeholder Review
      ↓
Management Approval
      ↓
Publication
      ↓
Awareness
      ↓
Control Implementation
      ↓
Compliance Testing
      ↓
Annual / Event-Driven Review
```

Identify the person or function responsible for each stage.

---

## **1.38 GRC Professional Perspective**

A GRC professional should understand that a policy is not simply a document stored on an intranet.

An effective policy creates a governance chain:

```text
Business Objective
       ↓
Risk
       ↓
Policy
       ↓
Requirement
       ↓
Control
       ↓
Evidence
       ↓
Testing
       ↓
Compliance
       ↓
Management Reporting
```

This is why policy management is a core GRC activity.

The GRC professional should challenge policies that are:

* Too vague.
* Impossible to measure.
* Not aligned with actual business processes.
* Not supported by controls.
* Not approved.
* Not communicated.
* Not reviewed.
* Filled with unnecessary technical details.

The objective is not to create more documents.

The objective is to establish **clear organizational requirements that can be implemented, measured, tested, and enforced**.

---

## Key Takeaways

1. A policy establishes organizational direction and mandatory requirements.
2. Policies should clearly define purpose, scope, responsibilities, requirements, exceptions, compliance, and enforcement.
3. Policies should be distinguished from standards, procedures, and guidelines.
4. Mandatory language should be clear and consistent.
5. Every policy should have an owner and approval authority.
6. Policies should be reviewed periodically and whenever significant changes occur.
7. Policy exceptions should be documented, risk assessed, approved, and time-bound.
8. Policies should be mapped to controls and risks.
9. Evidence should demonstrate that policy requirements are actually implemented.
10. Policy communication is necessary for effective adoption.
11. Policy metrics can help management monitor governance effectiveness.
12. A good policy should be practical, measurable, and aligned with the organization's operating environment.
13. The purpose of a policy is not merely documentation. It is to establish **clear governance that can be translated into controls and verified through evidence**.

**17.4 Security Procedure and Standard Templates**

### Part 2 – Security Standard Template

A **security standard** translates high-level policy requirements into specific, mandatory security requirements that can be consistently implemented across the organization.

If a policy answers:

> **"What does the organization require?"**

a standard answers:

> **"What specific security requirements must be met?"**

For example, an Access Control Policy may state:

> Access to organizational systems must be appropriately protected.

The corresponding Authentication Standard could establish:

> All privileged accounts must use phishing-resistant multi-factor authentication.

The standard therefore provides greater specificity than the policy while avoiding the step-by-step instructions normally found in procedures.

---

## 2.1 Purpose of a Security Standard

Security standards establish a consistent minimum level of security.

They can define requirements for:

* Authentication.
* Passwords.
* Encryption.
* Network security.
* Endpoint security.
* Cloud security.
* Vulnerability management.
* Logging and monitoring.
* Privileged access.
* Application security.
* Data protection.
* Mobile devices.
* Remote access.
* Third-party connections.

Standards are particularly useful when an organization wants to prevent different teams from implementing security requirements in completely different ways.

For example, without an MFA standard:

> Team A may require MFA for administrators, Team B may use passwords only, and Team C may use different authentication methods.

A standard creates a common baseline.

---

## 2.2 Policy-to-Standard Relationship

A typical hierarchy is:

```text
Security Policy
       ↓
Security Standard
       ↓
Security Procedure
       ↓
Work Instruction
```

For example:

```text
Access Control Policy
       ↓
Authentication Standard
       ↓
MFA Enrollment Procedure
       ↓
MFA Enrollment Work Instruction
```

Each level becomes progressively more detailed.

---

## 2.3 Example

Consider the following documents.

### Policy

> The organization must protect access to information systems.

### Standard

> Privileged accounts must use phishing-resistant MFA.

### Procedure

> The IAM team must enroll privileged users in the approved authentication platform and verify successful registration.

### Work Instruction

> Step 1: Open the IAM administration console.
> Step 2: Select the user account.
> Step 3: Select Authentication Methods.
> Step 4: Register the approved security key.

The policy establishes governance.

The standard establishes the mandatory technical requirement.

The procedure explains the operational process.

The work instruction explains exactly how to perform the task.

---

## 2.4 Security Standard Template

A practical security standard template can contain:

```text
SECURITY STANDARD

Document ID:
Standard Name:
Version:
Standard Owner:
Approved By:
Effective Date:
Review Date:
Classification:
Status:

1. Purpose
2. Scope
3. Standard Requirements
4. Technical Requirements
5. Roles and Responsibilities
6. Exceptions
7. Compliance and Monitoring
8. Related Policies
9. Related Procedures
10. References
11. Document Control
```

The template can be adjusted depending on the type of standard.

---

## 2.5 Standard Metadata

Like policies, standards should have controlled metadata.

Example:

| Field          | Example                 |
| -------------- | ----------------------- |
| Document ID    | SEC-STD-004             |
| Standard Name  | Authentication Standard |
| Version        | 2.0                     |
| Owner          | CISO                    |
| Approved By    | CIO                     |
| Effective Date | 1 September 2026        |
| Review Date    | 1 September 2027        |
| Classification | Internal                |
| Status         | Approved                |

This allows the GRC team to manage standards as controlled documents.

---

## 2.6 Purpose Statement

The purpose should explain what security objective the standard supports.

Example:

> This standard establishes minimum authentication requirements for protecting access to organizational information systems and services.

It should be concise and focused.

---

## 2.7 Scope

The scope identifies the systems, users, technologies, and environments covered by the standard.

Example:

> This standard applies to all employees, contractors, administrators, service accounts, applications, cloud services, and information systems requiring authentication to organizational resources.

A standard may have a narrower scope than its parent policy.

For example:

```text
Access Control Policy
        ↓
Authentication Standard
        ↓
Privileged Authentication Standard
```

---

## 2.8 Standard Requirements

This is the most important part of the document.

For an Authentication Standard, requirements could include:

1. All users must have unique identities.
2. Shared accounts must be prohibited unless formally approved.
3. MFA must be required for privileged accounts.
4. MFA must be required for remote access.
5. Privileged accounts must use phishing-resistant authentication where technically supported.
6. Authentication credentials must be protected.
7. Authentication events must be logged.
8. Authentication failures must be monitored.

These requirements are specific enough to be tested.

---

## 2.9 Minimum Security Baseline

A standard often establishes a **minimum security baseline**.

For example:

### Password Standard

```text
Minimum Requirements

Password Length:
Minimum 14 characters

Password Reuse:
Prohibited for the defined password history

MFA:
Required for privileged access

Account Lockout:
Must follow approved authentication controls

Password Storage:
Passwords must not be stored in plaintext
```

The exact values should be based on the organization's risk assessment, technology, applicable standards, and current security practices.

The important GRC principle is that the organization establishes a **defined minimum requirement**.

---

## 2.10 Mandatory Requirements

Standards generally contain mandatory requirements.

Use clear language such as:

* Must.
* Shall.
* Required.
* Prohibited.

For example:

> All internet-facing administrative interfaces must use approved multi-factor authentication.

Avoid vague statements such as:

> Internet-facing administrative interfaces should preferably use MFA.

If MFA is mandatory, the standard should say so explicitly.

---

## 2.11 Technical Specificity

A standard should contain more technical detail than a policy, but it should still avoid becoming a step-by-step operational manual.

For example:

**Policy**

> Sensitive information must be protected.

**Standard**

> Sensitive information stored on organizational systems must use organization-approved encryption mechanisms.

**Procedure**

> The system administrator must configure the approved encryption mechanism according to the platform-specific implementation procedure.

This separation makes documents easier to maintain.

---

## 2.12 Roles and Responsibilities

The standard should identify who is responsible for implementation and compliance.

Example:

### CISO

Defines security requirements and approves the standard.

### Security Architecture

Defines approved technical security mechanisms.

### IT

Implements the required controls.

### Application Owners

Ensure applications comply with the standard.

### System Owners

Maintain compliance for systems under their responsibility.

### GRC

Monitors compliance and coordinates exceptions and assessments.

---

## 2.13 Exceptions

Standards should include an exception mechanism.

For example:

> Any deviation from this standard must be formally documented, risk assessed, approved by the designated authority, and assigned an expiration or review date.

An exception could be required when:

* A legacy system cannot meet the requirement.
* A vendor product has a technical limitation.
* A business-critical application requires temporary deviation.
* A migration is in progress.

The exception should document the reason and compensating controls.

---

## 2.14 Example – Encryption Standard Exception

Suppose the standard requires:

> Sensitive information must be encrypted using an approved encryption mechanism.

A legacy application cannot support the approved mechanism.

A temporary exception might include:

```text
Requirement:
Approved encryption required.

Exception:
Legacy application cannot support the approved encryption mechanism.

Reason:
Application replacement scheduled for March 2027.

Compensating Controls:
- Network segmentation
- Restricted access
- Enhanced monitoring
- Additional backup protection

Risk:
High

Owner:
Application Director

Expiration:
31 December 2026
```

The exception should be tracked in the organization's GRC system.

---

## 2.15 Compliance Monitoring

Standards should be measurable.

For example:

> 100% of privileged accounts must use approved MFA.

This creates a clear compliance test.

The GRC team can then measure:

```text
Total Privileged Accounts:
250

Accounts Using Required MFA:
245

Compliance:
98%

Non-Compliant:
5
```

The five accounts can then be investigated and remediated or formally excepted.

---

## 2.16 Standard-to-Control Mapping

A standard should be connected to the organization's control framework.

Example:

| Standard Requirement                 | Control                 | Evidence       |
| ------------------------------------ | ----------------------- | -------------- |
| MFA required for privileged accounts | Privileged MFA          | IAM report     |
| Authentication events logged         | Authentication logging  | SIEM records   |
| Shared accounts prohibited           | Unique identity control | IAM inventory  |
| Access reviewed periodically         | Access review control   | Review records |

This creates traceability:

```text
Policy
   ↓
Standard
   ↓
Control
   ↓
Evidence
   ↓
Testing
```

---

## 2.17 Standard-to-Risk Mapping

Standards should also support risk treatment.

Example:

```text
Risk:
Unauthorized privileged access
       ↓
Policy:
Access Control Policy
       ↓
Standard:
Privileged Authentication Standard
       ↓
Control:
Phishing-resistant MFA
       ↓
Evidence:
IAM configuration
       ↓
Test:
MFA compliance review
```

This demonstrates how a standard contributes directly to risk reduction.

---

## 2.18 Standard Ownership

Every standard should have an owner.

The owner is normally responsible for:

* Maintaining the standard.
* Monitoring changes.
* Coordinating reviews.
* Assessing proposed modifications.
* Coordinating stakeholder input.
* Managing exceptions.
* Ensuring continued alignment with policies and risks.

For example:

> Authentication Standard → IAM / Security Architecture

> Cloud Security Standard → Cloud Security / Security Architecture

> Vulnerability Management Standard → Vulnerability Management Team

---

## 2.19 Standard Approval

The approval authority should be appropriate to the significance of the standard.

Examples:

| Standard                          | Possible Approver         |
| --------------------------------- | ------------------------- |
| Authentication Standard           | CISO / CIO                |
| Encryption Standard               | CISO                      |
| Cloud Security Standard           | CISO / CIO                |
| Network Security Standard         | CISO / Network Leadership |
| Vulnerability Management Standard | CISO                      |
| Secure Development Standard       | CISO / CTO                |

Approval authority should be defined by the organization's governance framework.

---

## 2.20 Standard Review

Standards should be reviewed periodically and whenever significant changes occur.

Triggers can include:

* New technology.
* New vulnerabilities.
* Regulatory changes.
* Security incidents.
* Changes in threat landscape.
* Changes to organizational architecture.
* Changes to security frameworks.
* Audit findings.

For example, an authentication standard written several years ago may no longer reflect current passwordless or phishing-resistant authentication capabilities.

---

## 2.21 Version Control

Example:

| Version | Date | Change                                  | Approver |
| ------- | ---- | --------------------------------------- | -------- |
| 1.0     | 2024 | Initial standard                        | CISO     |
| 1.1     | 2025 | Added MFA requirement                   | CISO     |
| 2.0     | 2026 | Added phishing-resistant authentication | CIO      |

Version history allows the organization to demonstrate how security requirements evolved.

---

## 2.22 Standard Communication

A new standard should be communicated to affected stakeholders.

For example, a new Cloud Security Standard may need to be communicated to:

* Cloud engineers.
* DevOps teams.
* Developers.
* Security architects.
* Application owners.
* Infrastructure teams.
* GRC.
* Procurement.

Communication ensures that affected teams understand the new requirements.

---

## 2.23 Standard Implementation

Creating a standard does not mean the organization is compliant.

Consider:

> Standard requires MFA.

The organization must still:

1. Identify affected systems.
2. Determine current compliance.
3. Implement the requirement.
4. Test the implementation.
5. Record evidence.
6. Remediate exceptions.
7. Monitor ongoing compliance.

Therefore:

```text
Standard
   ↓
Implementation
   ↓
Verification
   ↓
Evidence
   ↓
Continuous Monitoring
```

---

## 2.24 Common Security Standard Types

An enterprise may maintain many security standards.

Examples include:

### Identity and Access

* Authentication Standard.
* Password Standard.
* Privileged Access Standard.
* Access Review Standard.

### Infrastructure

* Network Security Standard.
* Server Hardening Standard.
* Endpoint Security Standard.
* Logging Standard.

### Data Protection

* Encryption Standard.
* Data Classification Standard.
* Data Retention Standard.
* Secure Disposal Standard.

### Application Security

* Secure Coding Standard.
* Application Security Testing Standard.
* API Security Standard.
* Software Dependency Standard.

### Cloud

* Cloud Security Standard.
* Cloud Identity Standard.
* Cloud Logging Standard.
* Cloud Configuration Standard.

The exact set should reflect the organization's risk profile.

---

## 2.25 Practical Exercise – Create an Authentication Standard

Create an Authentication Standard containing:

1. Purpose.
2. Scope.
3. Authentication requirements.
4. MFA requirements.
5. Privileged account requirements.
6. Service account requirements.
7. Remote access requirements.
8. Authentication logging.
9. Exception process.
10. Compliance monitoring.
11. Roles and responsibilities.
12. Review requirements.

Then identify which requirements should be tested by GRC.

---

## 2.26 Practical Exercise – Convert Policy Into Standard

Start with this policy requirement:

> The organization must protect privileged access.

Convert it into at least five specific standard requirements.

For example:

```text
Policy:
Protect privileged access.

        ↓

Standard Requirements:

1. Privileged accounts must be uniquely assigned.
2. Privileged accounts must use MFA.
3. Privileged access must follow least privilege.
4. Administrative activity must be logged.
5. Privileged access must be reviewed periodically.
```

The objective is to practice converting broad governance language into measurable requirements.

---

## 2.27 Practical Exercise – Compliance Assessment

Assume an Authentication Standard requires:

> 100% of privileged accounts must use MFA.

The GRC team discovers:

```text
Privileged Accounts:
500

MFA Enabled:
485

MFA Not Enabled:
15
```

Calculate:

* Compliance percentage.
* Non-compliance percentage.
* Number of remediation actions required.

Then determine whether the 15 accounts should be:

* Remediated.
* Formally excepted.
* Disabled.
* Investigated further.

The correct answer may depend on the circumstances of each account.

---

## 2.28 Practical Exercise – Standard Exception

Scenario:

> A critical legacy system cannot support the organization's current authentication standard.

Create an exception containing:

* Standard requirement.
* Business justification.
* Risk.
* Compensating controls.
* Risk owner.
* Approval authority.
* Target remediation date.
* Expiration date.
* Review frequency.

The objective is to demonstrate that exceptions are **risk-managed deviations**, not informal agreements.

---

## 2.29 GRC Professional Perspective

A GRC professional should be able to determine whether a security standard is:

* Specific.
* Mandatory.
* Measurable.
* Risk-based.
* Technically achievable.
* Consistent with policy.
* Supported by controls.
* Testable.
* Properly approved.
* Properly maintained.

A weak standard might state:

> Systems must be secure.

A stronger standard might state:

> Internet-facing systems must implement organization-approved vulnerability scanning at least monthly, with critical vulnerabilities remediated according to the organization's defined remediation timeframe.

The second requirement is much more useful because it can be:

* Implemented.
* Measured.
* Tested.
* Audited.
* Reported.

The GRC professional should also avoid making standards unnecessarily restrictive.

A standard should establish an appropriate security baseline while allowing the organization to manage legitimate exceptions through a controlled risk process.

The objective is to create **consistent, measurable security requirements that translate policy into operational controls**.

---

## Key Takeaways

1. A security standard translates policy requirements into specific mandatory requirements.
2. Standards establish a consistent minimum security baseline.
3. Standards should be more specific than policies but less operational than procedures.
4. Requirements should use clear mandatory language.
5. Standards should be measurable and testable.
6. Standards should have an owner and appropriate approval authority.
7. Exceptions should be formally documented, risk assessed, approved, and time-bound.
8. Standards should be mapped to controls and organizational risks.
9. Compliance should be supported by objective evidence.
10. Standards should be reviewed when technology, threats, regulations, or business requirements change.
11. A standard should be practical enough to implement across the organization's environment.
12. The ultimate purpose of a security standard is to create **consistent and measurable security requirements that can be implemented, monitored, tested, and improved**.

Understood. From **Part 2 through Part 4 of each section**, I’ll keep the content continuous with **no chapter/topic header, no section title, and no separate introduction**. Only Part 1 carries the main section header.

Here is the corrected **17.4 Part 3**:

## **Part 3 – Security Procedure Template**

A **security procedure** translates a policy or standard into a defined sequence of activities that personnel can follow consistently.

If a policy answers:

> **"What does the organization require?"**

and a standard answers:

> **"What specific requirements must be met?"**

a procedure answers:

> **"How do we perform the activity?"**

For example:

```text
Access Control Policy
        ↓
Access Control Standard
        ↓
User Access Review Procedure
        ↓
Access Review Work Instruction
```

The procedure provides the operational process required to implement the organization's security requirements.

A well-designed procedure should be practical, repeatable, understandable, and capable of producing evidence.

---

## **3.1 Purpose of a Security Procedure**

The purpose of a security procedure is to ensure that an activity is performed consistently and according to approved requirements.

Procedures can be developed for activities such as:

* User provisioning.
* User deprovisioning.
* Access reviews.
* Vulnerability remediation.
* Incident escalation.
* Security event monitoring.
* Backup restoration.
* Security awareness training.
* Third-party assessments.
* Risk assessments.
* Security exception management.
* Data disposal.
* Security incident reporting.

Without procedures, different employees may perform the same activity differently.

For example, one administrator may remove terminated-user access immediately, while another may wait several days.

A procedure establishes a consistent process.

---

## **3.2 Procedure vs Policy vs Standard**

The difference can be summarized as:

| Document         | Main Question                      | Example                               |
| ---------------- | ---------------------------------- | ------------------------------------- |
| Policy           | What and why?                      | Access must be controlled             |
| Standard         | What specific requirement?         | Privileged access requires MFA        |
| Procedure        | How is it performed?               | Steps for provisioning access         |
| Work Instruction | Exactly how do I perform the task? | Screenshots and system-specific steps |

This distinction prevents governance documents from becoming unnecessarily complicated.

---

## **3.3 Security Procedure Template**

A practical procedure template can contain:

```text
SECURITY PROCEDURE

Procedure ID:
Procedure Name:
Version:
Procedure Owner:
Approved By:
Effective Date:
Review Date:
Classification:
Status:

1. Purpose
2. Scope
3. Roles and Responsibilities
4. Prerequisites
5. Procedure Steps
6. Escalation Requirements
7. Evidence and Records
8. Exceptions
9. Related Policies and Standards
10. References
11. Document Control
```

The structure can be modified depending on the activity.

---

## **3.4 Procedure Metadata**

Controlled procedures should contain document metadata.

Example:

| Field           | Example                      |
| --------------- | ---------------------------- |
| Procedure ID    | SEC-PRC-015                  |
| Procedure Name  | User Access Review Procedure |
| Version         | 2.0                          |
| Procedure Owner | IAM Manager                  |
| Approved By     | CISO                         |
| Effective Date  | 1 September 2026             |
| Review Date     | 1 September 2027             |
| Classification  | Internal                     |
| Status          | Approved                     |

Metadata supports document governance and auditability.

---

## **3.5 Purpose**

The purpose section explains why the procedure exists.

Example:

> This procedure defines the activities required to perform periodic user access reviews and ensure that access remains appropriate for business requirements.

The purpose should be concise.

It should not contain detailed instructions.

---

## **3.6 Scope**

The scope identifies where the procedure applies.

Example:

> This procedure applies to all corporate applications classified as requiring periodic access review and covers employees, contractors, privileged users, and service accounts where applicable.

The scope can specify:

* Systems.
* Business units.
* Users.
* Locations.
* Technologies.
* Processes.

---

## **3.7 Roles and Responsibilities**

A procedure should clearly identify who performs each activity.

Example:

### Application Owner

Reviews access and confirms whether users still require the assigned permissions.

### IAM Team

Generates access reports and coordinates the review.

### Business Manager

Confirms business justification for user access.

### GRC

Monitors completion and retains evidence.

### CISO

Provides escalation and governance oversight for significant issues.

Clear responsibilities prevent activities from being ignored because everyone assumes someone else is responsible.

---

## **3.8 Prerequisites**

Some procedures require prerequisites before execution.

For an access review, prerequisites might include:

* Current user access report.
* Application owner assignment.
* Review deadline.
* Previous review results.
* List of terminated users.
* List of privileged accounts.

For an incident response procedure, prerequisites might include:

* Incident ticket.
* Initial classification.
* Contact information.
* Relevant logs.
* Incident response team availability.

Prerequisites help ensure that the procedure begins with the necessary information.

---

## **3.9 Procedure Steps**

The procedure steps represent the operational core of the document.

For example:

### User Access Review

**Step 1 – Generate Access Report**

The IAM team generates the current access report for the application.

**Step 2 – Validate User Population**

The application owner confirms that the report contains the expected users.

**Step 3 – Review Access**

The application owner reviews each user's access against current business responsibilities.

**Step 4 – Identify Excessive Access**

Any unnecessary or inappropriate access is identified.

**Step 5 – Submit Remediation Request**

The application owner submits access removal or modification requests.

**Step 6 – Verify Remediation**

The IAM team confirms that the changes were successfully implemented.

**Step 7 – Record Completion**

The completed review and supporting evidence are retained.

This provides a repeatable operational process.

---

## **3.10 Procedure Flow**

A procedure can also be represented visually:

```text
Generate Access Report
        ↓
Validate User Population
        ↓
Review Access
        ↓
Identify Exceptions
        ↓
Approve Remediation
        ↓
Remove / Modify Access
        ↓
Verify Changes
        ↓
Store Evidence
        ↓
Close Review
```

Process flows can make procedures easier to understand.

---

## **3.11 Decision Points**

Good procedures should identify important decision points.

For example:

```text
Does the user still require access?
             |
       +-----+-----+
       |           |
      YES          NO
       |           |
Keep Access    Remove Access
       |           |
       +-----+-----+
             |
       Record Decision
```

Decision points help users understand what to do when different circumstances occur.

---

## **3.12 Escalation Requirements**

A procedure should explain when an issue must be escalated.

For example:

> Any privileged account identified as having inappropriate access must be escalated to the application owner and security team.

Escalation may be required for:

* Critical security violations.
* Privileged access issues.
* Suspected compromise.
* Regulatory violations.
* Repeated non-compliance.
* High-risk exceptions.
* Missed deadlines.

A procedure without escalation rules may result in important issues remaining unresolved.

---

## **3.13 Evidence and Records**

One of the most important GRC aspects of a procedure is evidence.

The procedure should identify what records are produced.

For example:

| Activity                | Evidence               |
| ----------------------- | ---------------------- |
| Access report generated | Access report          |
| Review completed        | Approved review record |
| Access removed          | IAM ticket             |
| Exception approved      | Exception record       |
| Remediation verified    | Verification report    |

This creates an audit trail.

The principle is:

> **If an important security activity is performed, there should normally be evidence demonstrating that it was performed.**

---

## **3.14 Procedure Evidence Flow**

The relationship can be represented as:

```text
Procedure
    ↓
Activity
    ↓
Output
    ↓
Evidence
    ↓
Control Testing
    ↓
Audit
```

For example:

```text
Access Review Procedure
        ↓
Quarterly Review
        ↓
Access Review Report
        ↓
Approved Evidence
        ↓
GRC Testing
        ↓
Audit Evidence
```

This is particularly important for regulated organizations.

---

## **3.15 Exceptions**

Procedures should define what happens when the normal process cannot be followed.

For example:

> If the application owner is unavailable during the review period, the review must be escalated to the designated backup owner.

Other exceptions may include:

* System unavailable.
* Required information missing.
* Technical failure.
* Emergency situation.
* Business continuity event.

The procedure should avoid allowing employees to simply bypass the process.

---

## **3.16 Emergency Procedures**

Some security activities require special emergency handling.

For example, an emergency privileged-access procedure may allow temporary access during a critical incident.

The procedure might require:

1. Emergency access request.
2. Incident reference.
3. Manager approval.
4. Security approval where required.
5. Temporary access.
6. Enhanced monitoring.
7. Removal after the emergency.
8. Post-event review.

Emergency procedures should still maintain accountability.

---

## **3.17 Procedure Timing**

Some procedures have defined time requirements.

Examples:

> Terminated employee access must be disabled within the organization's defined termination timeframe.

> Critical vulnerability remediation must follow the organization's approved remediation SLA.

> Security incidents classified as critical must be escalated immediately.

Time requirements make procedures measurable.

---

## **3.18 Procedure Inputs and Outputs**

A useful procedure should identify its inputs and outputs.

Example:

### Inputs

* User access report.
* HR employee list.
* Application ownership information.
* Previous review results.

### Process

* Validate.
* Review.
* Approve.
* Remediate.
* Verify.

### Outputs

* Approved access review.
* Remediation tickets.
* Exception records.
* Evidence package.

This model can be represented as:

```text
Inputs
   ↓
Process
   ↓
Outputs
   ↓
Evidence
```

---

## **3.19 Procedure Metrics**

Procedures can generate useful GRC metrics.

For an access review procedure:

* Percentage completed on time.
* Number of users reviewed.
* Number of excessive permissions identified.
* Number of access removals.
* Number of overdue reviews.
* Number of exceptions.
* Average remediation time.

Example:

> 98% of quarterly access reviews were completed within the required timeframe.

This turns operational activity into measurable governance information.

---

## **3.20 Procedure-to-Control Mapping**

Procedures should be connected to controls.

Example:

| Procedure Activity        | Control                | Evidence            |
| ------------------------- | ---------------------- | ------------------- |
| Generate access report    | Periodic access review | Access report       |
| Manager reviews access    | Access authorization   | Approved review     |
| Remove unnecessary access | Least privilege        | IAM ticket          |
| Verify changes            | Access remediation     | Verification report |

This allows GRC teams to assess whether the control is actually operating.

---

## **3.21 Procedure-to-Policy Mapping**

A mature documentation structure should maintain traceability.

Example:

```text
Access Control Policy
        ↓
Access Control Standard
        ↓
User Access Review Procedure
        ↓
IAM Access Review Control
        ↓
Access Review Evidence
```

This creates a clear governance chain from organizational requirements to operational execution.

---

## **3.22 Example – Vulnerability Management Procedure**

A vulnerability management procedure might contain:

```text
1. Identify Assets
2. Perform Vulnerability Scan
3. Validate Findings
4. Classify Vulnerabilities
5. Assign Risk
6. Assign Remediation Owner
7. Establish Remediation Deadline
8. Track Remediation
9. Perform Verification Scan
10. Close Finding
11. Record Evidence
12. Report Metrics
```

This is more operational than a vulnerability management policy.

The procedure explains how the organization actually performs vulnerability management.

---

## **3.23 Example – Security Incident Escalation Procedure**

A simplified incident procedure could be:

```text
Security Alert
      ↓
Initial Validation
      ↓
Incident Confirmed?
   YES ↓
Classify Severity
      ↓
Assign Incident Owner
      ↓
Contain / Investigate
      ↓
Escalate According to Severity
      ↓
Remediate
      ↓
Recover
      ↓
Document
      ↓
Lessons Learned
```

The procedure provides an operational sequence while the Incident Response Policy establishes the organization's overall governance requirements.

---

## **3.24 Procedure Review**

Procedures should be reviewed periodically.

However, procedures may require more frequent review than policies because operational processes can change rapidly.

Review triggers include:

* Technology changes.
* Process changes.
* Organizational restructuring.
* Security incidents.
* Audit findings.
* Regulatory changes.
* Control changes.
* Changes in system architecture.

A procedure that no longer reflects the actual process can create significant compliance problems.

---

## **3.25 Procedure Testing**

Procedures should be tested to determine whether they actually work.

Testing can include:

* Walkthroughs.
* Tabletop exercises.
* Sample execution.
* Simulated scenarios.
* Control testing.
* Internal audits.

For example, an access review procedure may be tested by selecting a sample of applications and verifying that the documented procedure matches the activities actually performed.

---

## **3.26 Common Procedure Problems**

### Problem 1 – Procedure Is Too Vague

> "Review the user access."

This does not explain how the review should occur.

### Problem 2 – Procedure Is Too Detailed

The document may become difficult to maintain if every software screen and button is included.

### Problem 3 – No Owner

Nobody is accountable for maintaining the procedure.

### Problem 4 – No Evidence Requirement

The activity is performed but there is no audit trail.

### Problem 5 – No Escalation

The procedure does not explain what happens when a serious issue is identified.

### Problem 6 – No Timing Requirement

Employees do not know when the activity must be completed.

### Problem 7 – Procedure Does Not Match Reality

The documented process differs from what employees actually do.

### Problem 8 – Procedure Is Not Tested

The organization assumes the procedure works without validating it.

---

## **3.27 Practical Exercise – Create an Access Review Procedure**

Create a procedure containing:

1. Purpose.
2. Scope.
3. Roles.
4. Inputs.
5. Prerequisites.
6. Review steps.
7. Decision points.
8. Remediation process.
9. Escalation requirements.
10. Evidence requirements.
11. Exception process.
12. Completion criteria.

Then create a simple process flow.

---

## **3.28 Practical Exercise – Create a Vulnerability Remediation Procedure**

Develop a procedure for a vulnerability classified as critical.

Include:

```text
Detection
   ↓
Validation
   ↓
Risk Assessment
   ↓
Owner Assignment
   ↓
Remediation
   ↓
Verification
   ↓
Evidence
   ↓
Closure
```

Define who performs each activity and what evidence should be produced.

---

## **3.29 Practical Exercise – Procedure Walkthrough**

Take an existing security procedure and ask:

1. Can a new employee follow it?
2. Are responsibilities clear?
3. Are inputs defined?
4. Are steps sequential?
5. Are decision points clear?
6. Are escalation requirements documented?
7. Is evidence identified?
8. Are exceptions addressed?
9. Are completion criteria defined?
10. Does the procedure match the actual business process?

If several answers are "no," the procedure probably requires improvement.

---

## **3.30 GRC Professional Perspective**

A GRC professional should not assume that a documented procedure is automatically an effective procedure.

The important question is:

> **Does the documented process actually produce the intended control outcome?**

A GRC professional should compare:

```text
Documented Procedure
        ↕
Actual Process
        ↕
Control Requirement
        ↕
Evidence
```

If these four elements do not align, there may be a control weakness.

For example:

**Standard:**

> Privileged access must be reviewed quarterly.

**Procedure:**

> Application owners review privileged access every quarter.

**Actual Practice:**

> Reviews are performed annually.

**Evidence:**

> Only annual review records exist.

The organization may have a documented standard and procedure, but the control is not operating as required.

This could result in:

* A control deficiency.
* An audit finding.
* A compliance issue.
* Increased security risk.

The GRC professional therefore needs to evaluate both **documentation and operational effectiveness**.

---

## **3.31 Practical GRC Documentation Chain**

A mature organization should be able to demonstrate:

```text
Policy
   ↓
Standard
   ↓
Procedure
   ↓
Control
   ↓
Activity
   ↓
Evidence
   ↓
Testing
   ↓
Finding / Compliance Result
   ↓
Management Reporting
```

This chain is one of the most important concepts in practical GRC.

It demonstrates that security requirements are not merely documented but are translated into operational activities and measurable controls.

---

## Key Takeaways

1. A security procedure explains **how** a security requirement is performed.
2. Procedures translate policies and standards into repeatable operational activities.
3. Procedures should define purpose, scope, responsibilities, prerequisites, steps, escalation, evidence, and exceptions.
4. Good procedures contain clear decision points and completion criteria.
5. Procedures should produce evidence that can support control testing and audits.
6. Procedure activities should be mapped to controls and policies.
7. Procedures should include appropriate timing and escalation requirements.
8. Emergency procedures should still maintain accountability and traceability.
9. Procedures should be periodically reviewed and updated when processes or technologies change.
10. Procedures should be tested to ensure they work in practice.
11. GRC professionals should compare documented procedures with actual operational practices.
12. The ultimate goal of a procedure is to ensure that security requirements are **consistently executed, measurable, auditable, and aligned with organizational risk**.

A complete security documentation framework should not stop at creating policies, standards, and procedures. The organization also needs practical templates that make those documents easier to create, maintain, approve, implement, and assess.

Templates provide consistency. Instead of every security team creating documents from scratch, the organization can establish approved structures that can be reused across different security and GRC activities.

A practical template library may include:

* Security policy template.
* Security standard template.
* Security procedure template.
* Work instruction template.
* Security exception template.
* Risk assessment template.
* Control assessment template.
* Security review checklist.
* Evidence collection template.
* Security awareness template.
* Third-party security assessment template.
* Audit finding template.
* Corrective action plan template.

The purpose of a template is not to force every document to look identical. The purpose is to establish a **minimum level of consistency and completeness**.

For example, every security procedure should normally identify an owner, scope, responsibilities, process steps, evidence requirements, and review information.

A practical **work instruction template** can contain:

```text
WORK INSTRUCTION

Document ID:
Work Instruction Name:
Related Procedure:
Version:
Owner:
Effective Date:
Review Date:

1. Purpose
2. Scope
3. Required Access / Tools
4. Prerequisites
5. Detailed Instructions
6. Validation
7. Troubleshooting
8. Evidence
9. Escalation
10. References
11. Document Control
```

A work instruction is normally more detailed than a procedure.

For example:

```text
Procedure:
User Access Review Procedure

Work Instruction:
How to Generate the User Access Report
from the IAM Platform
```

The procedure explains the process.

The work instruction explains how to perform a specific task within that process.

A **security exception template** should also be standardized because exceptions are common in real-world environments.

A practical template could contain:

```text
SECURITY EXCEPTION REQUEST

Exception ID:
Request Date:
Requestor:
Business Unit:
System / Process:

Requirement Being Excepted:

Reason for Exception:

Business Justification:

Security Risk:

Risk Rating:

Affected Assets:

Compensating Controls:

Remediation Plan:

Target Remediation Date:

Exception Owner:

Risk Owner:

Approver:

Expiration Date:

Review Frequency:

Status:
```

This prevents exceptions from becoming informal emails or undocumented agreements.

The relationship between the requirement and the exception should be clear:

```text
Security Requirement
        ↓
Requirement Cannot Be Met
        ↓
Exception Request
        ↓
Risk Assessment
        ↓
Compensating Controls
        ↓
Approval
        ↓
Time-Bound Exception
        ↓
Remediation
        ↓
Closure
```

A **risk assessment template** can provide another important reusable structure.

For example:

```text
RISK ASSESSMENT

Risk ID:
Assessment Date:
Risk Owner:
Business Unit:

Asset / Process:

Threat:

Vulnerability:

Existing Controls:

Likelihood:

Impact:

Inherent Risk:

Additional Controls:

Residual Likelihood:

Residual Impact:

Residual Risk:

Risk Treatment:

Treatment Owner:

Target Date:

Risk Acceptance:

Approval:

Review Date:
```

The template should support the organization's selected risk methodology rather than impose a particular scoring system.

For a **control assessment**, the organization can use a structured template such as:

```text
CONTROL ASSESSMENT

Control ID:
Control Name:
Control Owner:
Assessment Period:

Control Objective:

Control Requirement:

Control Description:

Frequency:

Responsible Party:

Evidence Required:

Evidence Provided:

Design Effectiveness:

Operating Effectiveness:

Testing Performed:

Test Result:

Finding:

Management Response:

Remediation Action:

Due Date:

Final Assessment:
```

This is particularly useful for GRC teams conducting control assessments against frameworks such as ISO/IEC 27001, NIST, COBIT, or internal control frameworks.

An **evidence collection template** can help standardize audit and compliance evidence.

Example:

```text
EVIDENCE COLLECTION RECORD

Evidence ID:
Control ID:
Evidence Name:
Evidence Description:

Evidence Owner:

Period Covered:

Source System:

Collection Date:

Evidence Type:

Confidentiality Classification:

Reviewer:

Review Date:

Evidence Status:

Comments:

Storage Location:
```

Evidence should be sufficiently clear that another reviewer can understand:

* What the evidence demonstrates.
* Which control it supports.
* What period it covers.
* Who provided it.
* Whether it is complete.
* Whether it has been reviewed.

A **security review checklist** can simplify recurring assessments.

Example:

```text
SECURITY REVIEW CHECKLIST

Review Area                  Status
--------------------------------------
Access Control               [ ]
Authentication               [ ]
Logging and Monitoring       [ ]
Vulnerability Management     [ ]
Endpoint Security            [ ]
Network Security             [ ]
Data Protection              [ ]
Backup and Recovery          [ ]
Third-Party Risk             [ ]
Security Awareness           [ ]
Incident Response            [ ]
Compliance                   [ ]
```

The checklist can then include:

```text
Requirement:
Status:
Evidence:
Finding:
Risk:
Action Required:
Owner:
Due Date:
```

Templates can also support **third-party security assessments**.

A vendor assessment template may include:

```text
THIRD-PARTY SECURITY ASSESSMENT

Vendor:
Service:
Business Owner:
Assessment Date:

Security Governance
[ ] Security policy
[ ] Security organization
[ ] Security certifications

Access Control
[ ] MFA
[ ] Privileged access
[ ] Access reviews

Data Protection
[ ] Encryption
[ ] Data classification
[ ] Data retention

Incident Management
[ ] Incident response process
[ ] Breach notification
[ ] Incident testing

Business Continuity
[ ] Business continuity plan
[ ] Disaster recovery
[ ] Recovery testing

Privacy
[ ] Privacy controls
[ ] Data processing requirements
[ ] Regulatory compliance

Findings:
Risk Rating:
Remediation:
Due Date:
```

A standardized vendor assessment makes it easier to compare suppliers consistently.

Templates should also include **document control**.

A document control section can contain:

| Field          | Purpose                          |
| -------------- | -------------------------------- |
| Document ID    | Unique identification            |
| Version        | Current document version         |
| Owner          | Person responsible               |
| Approver       | Authorized approval authority    |
| Effective Date | Date the document becomes active |
| Review Date    | Planned review date              |
| Classification | Information classification       |
| Status         | Draft, approved, retired         |
| Change History | Record of modifications          |

The document lifecycle can then follow:

```text
Draft
  ↓
Review
  ↓
Approval
  ↓
Publication
  ↓
Implementation
  ↓
Periodic Review
  ↓
Revision
  ↓
Reapproval
  ↓
Retirement
```

Document status should be clearly defined.

For example:

**Draft**

The document is being developed and has not been formally approved.

**Under Review**

The document is undergoing stakeholder or security review.

**Approved**

The document has received the required authorization.

**Effective**

The document is currently applicable to the organization.

**Superseded**

A newer version has replaced the document.

**Retired**

The document is no longer applicable.

Templates should also support **version control**.

For example:

| Version | Date       | Change                      | Author   | Approver |
| ------- | ---------- | --------------------------- | -------- | -------- |
| 0.1     | 2026-01-10 | Initial draft               | Security | —        |
| 0.2     | 2026-01-15 | Added access requirements   | Security | —        |
| 1.0     | 2026-02-01 | Approved version            | Security | CISO     |
| 1.1     | 2026-07-01 | Updated review requirements | GRC      | CISO     |

This creates a traceable history of changes.

A mature GRC function should also maintain a **template register**.

Example:

| Template           | Owner                 | Version | Review Cycle | Status |
| ------------------ | --------------------- | ------: | ------------ | ------ |
| Policy Template    | GRC                   |     2.0 | Annual       | Active |
| Standard Template  | Security Architecture |     1.2 | Annual       | Active |
| Procedure Template | GRC                   |     2.1 | Annual       | Active |
| Risk Assessment    | Risk Management       |     3.0 | Annual       | Active |
| Control Assessment | GRC                   |     2.0 | Annual       | Active |
| Exception Request  | Risk Management       |     2.2 | Annual       | Active |
| Evidence Record    | GRC                   |     1.5 | Annual       | Active |
| Vendor Assessment  | Third-Party Risk      |     3.0 | Annual       | Active |

The template register prevents uncontrolled versions of templates from circulating throughout the organization.

For larger organizations, templates should ideally be stored in a controlled repository such as a GRC platform, document management system, or approved collaboration platform.

The organization should avoid having multiple uncontrolled copies such as:

```text
Security Policy Template FINAL.docx
Security Policy Template FINAL2.docx
Security Policy Template FINAL-NEW.docx
Security Policy Template FINAL-APPROVED.docx
Security Policy Template FINAL-APPROVED-NEW.docx
```

This creates document governance problems.

Instead, there should be one controlled source of truth.

Templates should also be designed for **automation** where practical.

For example, a GRC platform could automatically populate:

* Document ID.
* Owner.
* Business unit.
* Review date.
* Approval status.
* Risk rating.
* Control ID.
* Assessment period.

This reduces manual errors and improves consistency.

Templates can also support **workflow automation**.

For example:

```text
Template Created
      ↓
Owner Completes
      ↓
Security Review
      ↓
GRC Review
      ↓
Management Approval
      ↓
Publication
      ↓
Notification
      ↓
Periodic Review
```

This turns a document template into part of an actual governance process.

A useful GRC practice is to distinguish between **mandatory fields** and **optional fields**.

For example:

### Mandatory

* Document owner.
* Scope.
* Requirements.
* Approval.
* Effective date.
* Review date.

### Optional

* Supporting diagrams.
* Additional references.
* Implementation examples.
* Appendices.

This prevents important governance information from being accidentally omitted.

Templates should also avoid unnecessary complexity.

A 50-page procedure template may discourage employees from documenting processes properly.

The goal should be:

> **Enough structure to ensure quality, but not so much structure that the template becomes a burden.**

The same principle applies to security questionnaires.

A third-party assessment containing hundreds of irrelevant questions may produce poor-quality answers and create unnecessary workload.

Questions should be relevant to:

* The service.
* The data involved.
* The organization's risk.
* Regulatory requirements.
* The vendor's access.
* The criticality of the relationship.

Templates should therefore be **risk-based** rather than simply comprehensive for the sake of being comprehensive.

A practical template library can be organized as follows:

```text
GRC Template Library
│
├── Governance
│   ├── Policy Template
│   ├── Standard Template
│   ├── Procedure Template
│   └── Work Instruction Template
│
├── Risk Management
│   ├── Risk Assessment
│   ├── Risk Register
│   ├── Risk Acceptance
│   └── Exception Request
│
├── Compliance
│   ├── Control Assessment
│   ├── Evidence Record
│   ├── Audit Checklist
│   └── Compliance Assessment
│
├── Third-Party Risk
│   ├── Vendor Assessment
│   ├── Security Questionnaire
│   └── Vendor Remediation Plan
│
└── Security Operations
    ├── Incident Report
    ├── Access Review
    ├── Vulnerability Assessment
    └── Security Review
```

This structure provides a practical starting point for an enterprise GRC repository.

The templates should also be mapped to the organization's frameworks where appropriate.

For example:

```text
ISO/IEC 27001
      ↓
Control Requirements
      ↓
GRC Assessment Template
      ↓
Evidence
      ↓
Assessment Result
```

Similarly:

```text
NIST CSF
      ↓
Cybersecurity Outcomes
      ↓
Control / Assessment Template
      ↓
Evidence
      ↓
Maturity / Gap Result
```

The template itself does not create compliance.

A completed template also does not automatically demonstrate that a control is effective.

For example, an organization may have a beautifully completed access review template, but if the actual access review was not performed, the document does not provide meaningful assurance.

This distinction is important:

> **Documentation is evidence of a process only when it accurately represents an activity that actually occurred.**

A GRC professional should therefore validate the relationship between:

```text
Template
   ↓
Completed Document
   ↓
Actual Activity
   ↓
Evidence
   ↓
Control Effectiveness
```

If the completed document does not correspond to actual activity, the organization may have a documentation problem or potentially a control deficiency.

Templates should also be reviewed periodically.

Review questions should include:

1. Is the template still relevant?
2. Are mandatory fields still appropriate?
3. Are regulatory requirements reflected?
4. Does it support current security processes?
5. Does it align with current policies and standards?
6. Are users actually completing it?
7. Does it produce useful evidence?
8. Can parts of the process be automated?
9. Is the template unnecessarily complicated?
10. Are outdated versions still being used?

A practical **template improvement cycle** is:

```text
Use Template
      ↓
Collect Feedback
      ↓
Identify Problems
      ↓
Update Template
      ↓
Test New Version
      ↓
Approve
      ↓
Publish
      ↓
Monitor Usage
      ↓
Repeat
```

This demonstrates that templates are living GRC tools rather than static documents.

For a practical GRC exercise, create a small enterprise template library containing:

```text
1. Security Policy Template
2. Security Standard Template
3. Security Procedure Template
4. Work Instruction Template
5. Risk Assessment Template
6. Security Exception Template
7. Control Assessment Template
8. Evidence Collection Template
9. Third-Party Security Assessment
10. Corrective Action Plan
```

For each template, define:

* Template owner.
* Purpose.
* Mandatory fields.
* Approval requirements.
* Review frequency.
* Storage location.
* Version number.
* Related framework or control.
* Expected evidence.

Then create a simple **Template Governance Register** and assign ownership for every template.

The final objective is to establish a reusable toolkit that allows the GRC team to create consistent, auditable, and risk-aligned documentation without reinventing the process every time.

A mature GRC function should eventually be able to answer:

> **"Do we have a standardized tool or template for this governance activity?"**

If the answer is yes, the next question should be:

> **"Is the template controlled, current, approved, and actually being used?"**

That distinction separates a collection of documents from a functioning GRC management system.

## Key Takeaways

1. Templates create consistency across security and GRC activities.
2. Templates should establish minimum quality requirements without creating unnecessary bureaucracy.
3. Work instructions provide more detailed operational guidance than procedures.
4. Risk, exception, control assessment, evidence, and third-party assessment templates are particularly useful for GRC.
5. Templates should have owners, versions, approval status, and review dates.
6. Organizations should maintain a controlled template repository.
7. Template workflows can be automated through GRC and document management platforms.
8. Templates should be risk-based and appropriate to the organization's environment.
9. A completed template does not automatically prove that a security control is effective.
10. GRC professionals should verify that documented activities actually occurred.
11. Templates should be periodically reviewed and improved based on operational experience.
12. A mature template library becomes a practical **GRC toolkit for consistent governance, risk management, compliance, assessment, and audit activities**.




