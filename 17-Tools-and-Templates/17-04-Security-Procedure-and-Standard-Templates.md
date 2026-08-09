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



