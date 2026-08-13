# 18.2 GRC Governance Diagrams

## Part 1 – Enterprise GRC Governance Model

An Enterprise GRC Governance Model provides a visual representation of how governance, risk management, compliance, cybersecurity, internal controls, assurance, and executive decision-making are organized within an enterprise.

The purpose of the model is to answer several fundamental questions:

```text
Who provides oversight?

Who owns risk?

Who owns controls?

Who performs control activities?

Who provides independent assurance?

Who makes risk decisions?

Who receives GRC reporting?

How are issues escalated?
```

A simplified enterprise GRC governance model can be represented as:

```text
                    Board of Directors
                           │
                           ↓
                  Board Risk Committee
                           │
                           ↓
                  Executive Management
                           │
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
         CRO              CISO             CIO
          │                │                │
          └────────────────┼────────────────┘
                           ↓
                     Enterprise GRC
                           │
        ┌──────────────────┼──────────────────┐
        ↓                  ↓                  ↓
      Risk             Compliance           Control
   Management          Management          Management
        │                  │                  │
        └──────────────────┼──────────────────┘
                           ↓
                 Business & Technology
                       Functions
```

This model should not be interpreted as a mandatory organizational structure.

Different organizations may place GRC under different executives.

For example:

```text
Board
  ↓
CEO
  ↓
CRO
  ↓
Enterprise Risk
```

or:

```text
Board
  ↓
CEO
  ↓
CISO
  ↓
Cybersecurity GRC
```

or:

```text
Board
  ↓
Audit / Risk Committee
  ↓
Chief Risk Officer
  ↓
Enterprise GRC
```

The actual reporting structure depends on the organization's size, industry, regulatory requirements, risk profile, and operating model.

The important principle is that **governance responsibilities must be clearly defined regardless of the organizational structure**.

A mature GRC governance model normally contains several major layers.

### Board and Board Committees

The Board provides the highest level of governance oversight.

Its responsibilities may include:

* Approving organizational risk appetite.
* Reviewing significant enterprise risks.
* Monitoring management's risk response.
* Reviewing major cybersecurity risks.
* Providing oversight of regulatory compliance.
* Reviewing significant control weaknesses.
* Monitoring major incidents.
* Challenging management when risk exposure exceeds acceptable levels.

A simplified model is:

```text
Board
  │
  ├── Risk Oversight
  ├── Cybersecurity Oversight
  ├── Compliance Oversight
  ├── Financial Oversight
  └── Internal Control Oversight
```

The Board generally does not operate individual security controls.

Instead, it provides oversight and challenges management.

### Executive Management

Executive management is responsible for translating Board expectations into organizational actions.

A simplified relationship is:

```text
Board
  ↓
Risk Appetite
  ↓
Executive Management
  ↓
Risk Strategy
  ↓
Business Execution
```

Executive management may include:

* CEO
* CFO
* CIO
* CISO
* CRO
* COO
* General Counsel
* Other senior executives

The exact structure varies by organization.

### Chief Risk Officer

Where a CRO exists, the CRO may coordinate enterprise risk management across multiple risk domains.

For example:

```text
                     CRO
                      │
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
   Enterprise       Operational     Strategic
      Risk             Risk           Risk
       │
       ├── Cyber Risk
       ├── Financial Risk
       ├── Third-Party Risk
       └── Compliance Risk
```

The CRO does not necessarily own every individual risk.

Risk ownership normally remains with the business executive responsible for the affected activity.

For example:

```text
Business Risk
     ↓
Business Executive
     ↓
Risk Owner
```

The risk function provides governance, methodology, monitoring, challenge, and reporting.

### Chief Information Security Officer

The CISO is normally responsible for the organization's cybersecurity strategy and security program.

A simplified model is:

```text
CISO
 │
 ├── Security Strategy
 ├── Security Operations
 ├── Security Architecture
 ├── Identity & Access
 ├── Vulnerability Management
 ├── Security Engineering
 ├── Cybersecurity GRC
 └── Incident Response
```

The CISO may own cybersecurity risks at the program level, but individual business risks may remain with business risk owners.

This distinction is important.

For example:

```text
Customer Data Risk
       ↓
Business Owner
       ↓
Risk Owner

Cybersecurity Function
       ↓
Provides Security Controls
       ↓
Monitors / Advises / Assesses
```

The cybersecurity function may therefore be responsible for implementing or operating controls without necessarily being the owner of the underlying business risk.

### Enterprise GRC Function

The GRC function typically coordinates governance activities across risk, compliance, control, and assurance domains.

A possible structure is:

```text
Enterprise GRC
      │
      ├── Risk Management
      │
      ├── Compliance
      │
      ├── Policy Management
      │
      ├── Control Management
      │
      ├── Third-Party Risk
      │
      ├── Audit Coordination
      │
      ├── Regulatory Monitoring
      │
      └── GRC Reporting
```

The GRC function may perform activities such as:

```text
Risk Assessment
Control Assessment
Compliance Mapping
Policy Governance
Evidence Management
Issue Tracking
Exception Management
Risk Reporting
Regulatory Reporting
Audit Coordination
```

However, GRC should not automatically become the owner of every risk and control.

A strong governance model distinguishes:

```text
GRC
 ↓
Coordinates / Facilitates / Monitors / Challenges / Reports

Business
 ↓
Owns Business Risk

Control Owner
 ↓
Owns Control

Control Operator
 ↓
Performs Control

Internal Audit
 ↓
Provides Independent Assurance
```

This separation helps maintain accountability.

### Business Functions

Business functions are critical to enterprise GRC because risks ultimately affect business objectives.

For example:

```text
Sales
Finance
HR
Procurement
Operations
Customer Service
Product Development
Legal
Technology
```

Each business function may own specific risks and controls.

Example:

```text
Procurement
     ↓
Third-Party Risk
     ↓
Procurement Risk Owner
```

Another example:

```text
Finance
   ↓
Financial Reporting Risk
   ↓
Finance Risk Owner
```

Another:

```text
Customer Service
      ↓
Customer Data Risk
      ↓
Business Risk Owner
```

### Control Owners

A control owner is accountable for ensuring that a specific control is properly designed, implemented, maintained, and monitored.

For example:

```text
Control:
Privileged Access Review

Control Owner:
IAM Manager

Control Operator:
IAM Administrator

Evidence:
Access Review Report

GRC:
Control Assessment / Monitoring
```

This distinction is important because the person performing a control is not necessarily the person accountable for the control.

### Internal Audit

Internal Audit should maintain an appropriate level of independence from the activities it evaluates.

A simplified model is:

```text
Board / Audit Committee
          ↑
          │
   Internal Audit
          │
          ↓
Independent Assurance
```

Internal Audit may assess:

```text
Governance
Risk Management
Internal Controls
Cybersecurity
Compliance
Business Processes
```

Internal Audit should generally not become the operational owner of the controls it later audits.

This supports independence and objective assurance.

### The Three Lines Model

The Enterprise GRC Governance Model can also be aligned with the Three Lines Model.

A simplified representation is:

```text
Board / Governing Body
          │
          ↓
     Management
          │
   ┌──────┴──────┐
   ↓             ↓
First Line     Second Line
Operations     Risk / Compliance
   │             │
   └──────┬──────┘
          ↓
      Third Line
    Internal Audit
```

The first line generally owns and manages risks through business operations.

The second line provides expertise, support, monitoring, challenge, and oversight related to risk and compliance.

The third line provides independent and objective assurance.

A practical cybersecurity example is:

```text
First Line
IT / Security Operations
       ↓
Operate Security Controls

Second Line
Cybersecurity GRC
       ↓
Assess / Monitor / Challenge / Report

Third Line
Internal Audit
       ↓
Independent Assurance
```

This separation helps prevent conflicts of interest.

### Risk Ownership

A mature governance diagram should explicitly identify risk ownership.

For example:

```text
Enterprise Risk
      │
      ├── Strategic Risk
      │       ↓
      │    Executive
      │
      ├── Operational Risk
      │       ↓
      │    Business Owner
      │
      ├── Cyber Risk
      │       ↓
      │    Relevant Risk Owner
      │
      └── Third-Party Risk
              ↓
           Business Owner
```

The relevant risk owner should have sufficient authority to make decisions about the treatment of the risk.

A GRC professional should therefore avoid creating a governance model where risk ownership is assigned to a team that does not have authority over the affected business activity.

### Risk Escalation

Governance diagrams should also show escalation.

For example:

```text
Risk Identified
      ↓
Risk Owner
      ↓
Risk Assessment
      ↓
Within Risk Appetite?
   ↙           ↘
 Yes            No
  ↓              ↓
Monitor       Escalate
                 ↓
          Executive Management
                 ↓
           Risk Committee
                 ↓
                Board
```

Not every risk needs to reach the Board.

Escalation should normally depend on factors such as:

* Risk severity.
* Risk appetite.
* Financial impact.
* Regulatory impact.
* Customer impact.
* Operational impact.
* Reputational impact.
* Strategic importance.

### Compliance Governance

Compliance should also have a defined governance relationship.

For example:

```text
Regulator
    ↓
Regulatory Requirement
    ↓
Compliance Function
    ↓
Business / Control Owners
    ↓
Control Implementation
    ↓
Evidence
    ↓
Compliance Assessment
    ↓
Management Reporting
```

Compliance may coordinate requirements and assessments, while business and control owners remain accountable for implementation.

### GRC Reporting

The governance model should eventually connect to management reporting.

```text
Business Activities
       ↓
Risks
       ↓
Controls
       ↓
Assessments
       ↓
Issues
       ↓
GRC Dashboard
       ↓
Executive Management
       ↓
Risk Committee / Board
```

This creates a governance information flow.

Management can then understand:

```text
Current Risk Exposure

Control Effectiveness

Compliance Status

Open Findings

Overdue Remediation

Major Incidents

Third-Party Risk

Emerging Risks
```

### Enterprise GRC Governance Model

A more complete enterprise model can therefore be represented as:

```text
                         BOARD
                           │
                    Risk / Audit Committee
                           │
                           ↓
                 EXECUTIVE MANAGEMENT
                           │
       ┌───────────────────┼───────────────────┐
       ↓                   ↓                   ↓
      CRO                 CISO                CIO
       │                   │                   │
       └───────────────────┼───────────────────┘
                           ↓
                     ENTERPRISE GRC
                           │
       ┌───────────────────┼───────────────────┐
       ↓                   ↓                   ↓
      Risk             Compliance            Controls
       │                   │                   │
       └───────────────────┼───────────────────┘
                           ↓
                 BUSINESS FUNCTIONS
                           │
                           ↓
                   CONTROL OWNERS
                           │
                           ↓
                   CONTROL OPERATORS
                           │
                           ↓
                     GRC EVIDENCE
                           │
                           ↓
                    MONITORING &
                    ASSESSMENT
                           │
                           ↓
                   MANAGEMENT REPORTING
                           │
                           ↓
                  BOARD / COMMITTEE
```

Internal Audit operates across the governance structure as an independent assurance function:

```text
                 BOARD / AUDIT COMMITTEE
                           ↑
                           │
                    INTERNAL AUDIT
                           │
                    Independent
                      Assurance
                           │
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
       Governance         Risk            Controls
```

The complete model demonstrates an important GRC principle:

```text
Governance
    ↓
Risk Ownership
    ↓
Control Ownership
    ↓
Control Operation
    ↓
Monitoring
    ↓
Assessment
    ↓
Reporting
    ↓
Management Decision
    ↓
Independent Assurance
```

A well-designed Enterprise GRC Governance Model therefore provides a common visual language for understanding **authority, accountability, responsibility, risk ownership, control ownership, assurance, escalation, and decision-making** across the organization.

The Three Lines Model provides a practical way to visualize how an organization manages risk and provides assurance. It helps distinguish between operational management, risk and compliance oversight, and independent assurance.

The model begins with the governing body.

```text
Governing Body
      ↓
Oversight
      ↓
Management
      ↓
First Line + Second Line
      ↓
Third Line
      ↓
Independent Assurance
```

The governing body, normally the Board or an equivalent oversight body, is responsible for ensuring that appropriate governance and oversight arrangements exist.

Its responsibilities may include:

* Setting expectations for governance.
* Approving or overseeing risk appetite.
* Monitoring significant risks.
* Challenging management.
* Overseeing internal controls.
* Receiving independent assurance.

The Board does not normally operate individual controls.

Instead:

```text
Board
  ↓
Oversight
  ↓
Management
  ↓
Risk Management
  ↓
Operations
```

Management is responsible for achieving organizational objectives while managing risks within approved boundaries.

The Three Lines Model can be represented as:

```text
                 GOVERNING BODY
                       │
                       ↓
                  MANAGEMENT
                       │
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
    FIRST LINE     SECOND LINE    THIRD LINE
    Operations     Risk / GRC    Internal Audit
        │              │              │
        ↓              ↓              ↓
    Own Risk       Monitor /      Independent
    & Controls      Challenge       Assurance
```

The **First Line** represents functions that directly own and manage risks as part of their operations.

Examples include:

* Business operations
* IT operations
* Security operations
* Finance
* Human resources
* Procurement
* Engineering
* Customer operations

The First Line is closest to the actual business activity.

For example:

```text
Business Process
      ↓
Operational Risk
      ↓
First Line
      ↓
Controls
      ↓
Risk Management
```

The First Line is therefore responsible for managing risk rather than simply reporting risk.

A cybersecurity example is:

```text
Security Operations
      ↓
Operate Security Controls
      ↓
Monitor Security Events
      ↓
Respond to Incidents
      ↓
Manage Operational Risk
```

The First Line may operate:

* Access controls
* Endpoint security
* Network security
* Backup controls
* Vulnerability management
* Security monitoring
* Incident response

The First Line is generally accountable for ensuring that controls operate effectively within its area of responsibility.

The **Second Line** provides specialized expertise, support, monitoring, challenge, and oversight.

Examples include:

* Enterprise Risk Management
* Cybersecurity GRC
* Compliance
* Privacy
* Information Security Governance
* Regulatory Risk
* Third-Party Risk
* Business Continuity
* Quality and Control Functions

A simplified model is:

```text
FIRST LINE
Operations
    ↓
Own and Manage Risk
    ↓
SECOND LINE
Risk / Compliance / GRC
    ↓
Monitor / Challenge / Advise
```

The Second Line does not normally take over the First Line's responsibility for managing the risk.

For example:

```text
IT
 ↓
Operates Access Controls

Cybersecurity GRC
 ↓
Defines Requirements
 ↓
Monitors Compliance
 ↓
Assesses Control Effectiveness
 ↓
Reports Findings
```

The Second Line may therefore establish:

* Policies
* Standards
* Risk methodologies
* Control requirements
* Compliance requirements
* Assessment methodologies
* Monitoring procedures
* Reporting requirements

The Second Line may also challenge the First Line.

For example:

```text
First Line:
"Access reviews are operating effectively."

Second Line:
"Provide evidence demonstrating effectiveness."

First Line:
"Evidence provided."

Second Line:
"Testing identifies exceptions."

Second Line:
"Finding raised."
```

This challenge function is a fundamental part of effective GRC.

The **Third Line** is Internal Audit.

Internal Audit provides independent and objective assurance over governance, risk management, and controls.

A simplified representation is:

```text
Third Line
    ↓
Internal Audit
    ↓
Independent Assessment
    ↓
Governance
Risk Management
Internal Controls
```

Internal Audit may assess whether:

```text
Governance is effective

Risks are appropriately managed

Controls are properly designed

Controls operate effectively

Management processes are working
```

Internal Audit should maintain appropriate independence from the activities it audits.

For example, Internal Audit should generally not:

```text
Own the Security Control
       ↓
Operate the Security Control
       ↓
Then Audit the Same Control
```

Instead:

```text
First Line
     ↓
Owns / Operates Control

Second Line
     ↓
Monitors / Challenges

Third Line
     ↓
Independently Assesses
```

The Three Lines Model therefore establishes an important separation between **ownership, oversight, and assurance**.

A cybersecurity example can be represented as:

```text
                         BOARD
                           │
                           ↓
                     MANAGEMENT
                           │
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
     FIRST LINE       SECOND LINE      THIRD LINE
          │                │                │
   Security Ops       Cyber GRC       Internal Audit
          │                │                │
          ↓                ↓                ↓
 Operate Controls     Monitor /       Independent
 Manage Risks         Challenge       Assurance
```

Consider vulnerability management.

The First Line may be:

```text
Security Operations
        ↓
Scan Systems
        ↓
Identify Vulnerabilities
        ↓
Prioritize
        ↓
Remediate
        ↓
Verify
```

The Second Line may be:

```text
Cybersecurity GRC
        ↓
Define Vulnerability Requirements
        ↓
Monitor Compliance
        ↓
Review Metrics
        ↓
Challenge Exceptions
        ↓
Report Risk
```

The Third Line may be:

```text
Internal Audit
        ↓
Review Vulnerability Management
        ↓
Test Governance
        ↓
Test Controls
        ↓
Evaluate Effectiveness
        ↓
Issue Audit Findings
```

This creates clear separation.

The same principle applies to access management.

```text
FIRST LINE
IAM / IT
    ↓
Create / Modify / Remove Access
    ↓
Perform Access Reviews

SECOND LINE
Cybersecurity GRC
    ↓
Define Access Control Requirements
    ↓
Monitor Compliance
    ↓
Assess Exceptions

THIRD LINE
Internal Audit
    ↓
Independently Test Access Management
    ↓
Report Assurance Results
```

The Three Lines Model can also be applied to third-party risk.

```text
FIRST LINE
Business / Procurement
    ↓
Select Supplier
    ↓
Manage Supplier
    ↓
Monitor Performance

SECOND LINE
Third-Party Risk / GRC
    ↓
Define Requirements
    ↓
Assess Risk
    ↓
Monitor Compliance
    ↓
Challenge Exceptions

THIRD LINE
Internal Audit
    ↓
Audit Third-Party Risk Management
```

Another important concept is that the Three Lines Model is **not necessarily three separate departments**.

An organization may have different organizational structures.

For example, in a smaller organization:

```text
First Line
Business / IT

Second Line
Part-time GRC / Compliance

Third Line
Outsourced Internal Audit
```

A larger enterprise may have:

```text
First Line
Business + IT + Security Operations

Second Line
Enterprise Risk
Cybersecurity GRC
Compliance
Privacy
Third-Party Risk

Third Line
Internal Audit
```

The organizational structure can vary while the underlying responsibilities remain distinguishable.

A useful responsibility model is:

| Activity              | First Line          | Second Line         | Third Line             |
| --------------------- | ------------------- | ------------------- | ---------------------- |
| Own Risk              | Yes                 | Support / Challenge | Assess                 |
| Operate Controls      | Yes                 | Normally No         | No                     |
| Define Requirements   | Input               | Yes                 | Independent View       |
| Monitor Risk          | Yes                 | Yes                 | Independent Assessment |
| Compliance Monitoring | Operational Input   | Yes                 | Assess                 |
| Control Testing       | Operational Testing | Oversight Testing   | Independent Testing    |
| Risk Reporting        | Yes                 | Yes                 | Assurance Reporting    |
| Independent Assurance | No                  | No                  | Yes                    |

The exact division of responsibilities should be defined by the organization's governance model.

A critical distinction is:

```text
First Line
"What are we doing?"

Second Line
"Are we managing risk according to requirements?"

Third Line
"Is the overall system working effectively?"
```

The First Line is focused on **execution**.

The Second Line is focused on **oversight and challenge**.

The Third Line is focused on **independent assurance**.

This can be summarized as:

```text
FIRST LINE
DO

SECOND LINE
CHECK / CHALLENGE / ADVISE

THIRD LINE
INDEPENDENTLY ASSURE
```

However, "check" should not be interpreted as meaning that the Second Line replaces operational management.

The First Line remains responsible for managing its risks.

For example:

```text
Business
    ↓
Owns Risk

GRC
    ↓
Challenges Risk Management

Internal Audit
    ↓
Provides Independent Assurance
```

This separation becomes especially important when dealing with high-risk cybersecurity environments.

For example:

```text
Critical Vulnerability
        ↓
Security Operations
        ↓
Remediation
        ↓
Cybersecurity GRC
        ↓
Monitoring / Escalation
        ↓
Management
        ↓
Risk Decision
        ↓
Internal Audit
        ↓
Independent Assurance
```

The Three Lines Model can therefore be integrated into the broader Enterprise GRC Governance Model:

```text
                         BOARD
                           │
                           ↓
                    EXECUTIVE MANAGEMENT
                           │
              ┌────────────┴────────────┐
              ↓                         ↓
         FIRST LINE                 SECOND LINE
       Business / IT /           Risk / Compliance /
       Security Operations       Cybersecurity GRC
              │                         │
              └────────────┬────────────┘
                           ↓
                    Risk Management
                           │
                           ↓
                      Controls
                           │
                           ↓
                       Evidence
                           │
                           ↓
                     GRC Reporting
                           │
                           ↓
                    THIRD LINE
                  Internal Audit
                           │
                           ↓
               Independent Assurance
                           │
                           ↓
                         BOARD
```

The model creates a continuous governance loop:

```text
Governance
    ↓
Risk Ownership
    ↓
Control Operation
    ↓
Risk / Compliance Oversight
    ↓
Monitoring
    ↓
Independent Assurance
    ↓
Management Action
    ↓
Governance Improvement
```

For a GRC professional, understanding the Three Lines Model is essential because many governance failures occur when responsibilities become blurred.

Common weaknesses include:

```text
GRC Owns Business Risk
        ↓
Business Stops Taking Responsibility
```

or:

```text
Internal Audit Designs Controls
        ↓
Independence Is Reduced
```

or:

```text
Security Operations Assumes GRC
Responsibilities
        ↓
Independent Oversight Becomes Weak
```

A mature model instead establishes:

```text
Business
    ↓
Owns Risk

Operations
    ↓
Operates Controls

GRC / Risk / Compliance
    ↓
Monitors / Advises / Challenges

Internal Audit
    ↓
Independently Assures

Board
    ↓
Provides Oversight
```

The Three Lines Model should therefore be viewed as a **governance and accountability framework**, not merely an organizational chart.

Its primary value is creating clarity around who:

* Owns risk.
* Operates controls.
* Provides oversight.
* Challenges management.
* Performs monitoring.
* Provides independent assurance.
* Escalates significant issues.
* Makes risk decisions.
* Reports to governing bodies.

A strong GRC diagram makes these relationships visible so that responsibility does not disappear between organizational functions.

A mature GRC governance model should clearly distinguish **risk ownership, control ownership, operational responsibility, oversight, and independent assurance**. One of the most common weaknesses in GRC programs is assuming that the department responsible for managing a risk is automatically the owner of that risk.

Risk ownership should normally remain with the person or business function that has the authority to make decisions about the affected business activity.

A simplified model is:

```text
Business Objective
       ↓
Business Activity
       ↓
Business Risk
       ↓
Risk Owner
       ↓
Risk Treatment Decision
```

For example:

```text
Customer Service
       ↓
Customer Data Processing
       ↓
Data Protection Risk
       ↓
Business Risk Owner
       ↓
Risk Treatment
```

The cybersecurity function may provide controls and expertise, but it does not necessarily become the owner of the business risk.

A more complete relationship is:

```text
Business
    ↓
Owns Business Risk
    │
    ↓
Cybersecurity
    ↓
Provides Security Controls
    │
    ↓
GRC
    ↓
Monitors / Assesses / Challenges
    │
    ↓
Internal Audit
    ↓
Provides Independent Assurance
```

This distinction is particularly important when defining a risk register.

A risk register may contain:

| Risk                | Risk Owner       | Control Owner          | GRC              | Internal Audit        |
| ------------------- | ---------------- | ---------------------- | ---------------- | --------------------- |
| Unauthorized Access | Business Owner   | IAM Manager            | Monitor / Assess | Independent Assurance |
| Data Loss           | Data Owner       | Security Manager       | Monitor / Assess | Independent Assurance |
| Supplier Risk       | Business Owner   | Procurement Manager    | Oversight        | Independent Assurance |
| Cloud Security Risk | Technology Owner | Cloud Security Manager | Oversight        | Independent Assurance |

The **Risk Owner** is accountable for the risk.

The **Control Owner** is accountable for the control designed to reduce the risk.

The **Control Operator** performs the control activity.

The **GRC function** may coordinate, monitor, assess, challenge, and report.

**Internal Audit** provides independent assurance.

These roles can be represented as:

```text
Risk
 │
 ├── Risk Owner
 │      ↓
 │   Owns Risk
 │
 ├── Control Owner
 │      ↓
 │   Owns Control
 │
 ├── Control Operator
 │      ↓
 │   Performs Control
 │
 ├── GRC
 │      ↓
 │   Monitors / Challenges
 │
 └── Internal Audit
        ↓
     Independent Assurance
```

A common example is privileged access management.

```text
Business / Technology
        ↓
Owns Access Risk

IAM Manager
        ↓
Owns Access Control

IAM Administrator
        ↓
Operates Access Control

Cybersecurity GRC
        ↓
Assesses Control Effectiveness

Internal Audit
        ↓
Provides Independent Assurance
```

This model prevents GRC from becoming responsible for operating controls that it is expected to assess.

The same principle applies to compliance.

A regulation may create a requirement:

```text
Regulation
     ↓
Requirement
     ↓
Business Obligation
     ↓
Control
     ↓
Evidence
```

The compliance function may interpret and coordinate the requirement:

```text
Compliance
     ↓
Interpret Requirement
     ↓
Map Requirement
     ↓
Define Compliance Expectations
     ↓
Monitor Compliance
```

However, the relevant business or control owner normally remains responsible for implementing the required controls.

For example:

```text
Privacy Requirement
        ↓
Data Protection Control
        ↓
Data Owner
        ↓
Implementation
        ↓
Evidence
```

The GRC function may then assess:

```text
Is the requirement addressed?

Is the control properly designed?

Is the control implemented?

Is evidence available?

Is the control operating effectively?

Are exceptions documented?

Is remediation required?
```

This produces a clear accountability chain:

```text
Requirement
    ↓
Control
    ↓
Control Owner
    ↓
Evidence
    ↓
Assessment
    ↓
Finding
    ↓
Remediation
    ↓
Risk Owner
```

Another important governance concept is **risk acceptance**.

The person who accepts a risk should have sufficient authority to accept the potential consequences.

For example:

```text
Risk Identified
      ↓
Risk Assessment
      ↓
Residual Risk
      ↓
Within Risk Appetite?
    ↙       ↘
  Yes        No
   ↓          ↓
Monitor    Escalate
              ↓
        Risk Owner
              ↓
       Accept / Treat
```

A GRC professional should not automatically accept risk on behalf of management.

GRC can recommend:

```text
"Risk should be treated."
```

or:

```text
"Risk exceeds the approved appetite."
```

But the actual risk acceptance decision should normally remain with the authorized risk owner or management authority.

This distinction is important:

```text
GRC
 ↓
Recommends / Challenges

Risk Owner
 ↓
Decides

Management
 ↓
Approves When Required
```

Risk escalation should also follow defined governance thresholds.

For example:

```text
Low Risk
   ↓
Risk Owner
```

```text
Medium Risk
   ↓
Business Management
   ↓
Risk Function
```

```text
High Risk
   ↓
Executive Management
   ↓
Risk Committee
```

```text
Critical Risk
   ↓
Executive Management
   ↓
Board / Board Committee
```

The exact thresholds should be defined by the organization's risk appetite and governance framework.

The same concept applies to security incidents.

A security incident may initially be handled operationally:

```text
Security Event
      ↓
SOC
      ↓
Incident Classification
      ↓
Incident Response
```

If the incident becomes significant:

```text
Major Incident
      ↓
Incident Manager
      ↓
CISO
      ↓
Executive Management
      ↓
Legal / Privacy / Compliance
      ↓
Board When Required
```

GRC may coordinate reporting and regulatory requirements without becoming the operational incident response owner.

Another important governance relationship is between **policy, standards, procedures, and controls**.

A useful diagram is:

```text
Business Objectives
       ↓
Policies
       ↓
Standards
       ↓
Procedures
       ↓
Controls
       ↓
Evidence
```

For example:

```text
Information Security Policy
       ↓
Password Standard
       ↓
Password Management Procedure
       ↓
Technical Password Control
       ↓
Authentication Logs
```

This creates a traceable governance structure.

The GRC professional can then demonstrate:

```text
Policy
  ↓
Requirement
  ↓
Control
  ↓
Evidence
  ↓
Assessment
```

Another important relationship is between **risk and controls**.

Controls should exist because they address specific risks or requirements.

A simplified model is:

```text
Threat
  ↓
Risk
  ↓
Control Objective
  ↓
Security Control
  ↓
Control Effectiveness
  ↓
Residual Risk
```

For example:

```text
Threat:
Credential Theft

        ↓

Risk:
Unauthorized Account Access

        ↓

Control Objective:
Prevent Unauthorized Access

        ↓

Control:
Multi-Factor Authentication

        ↓

Assessment:
Effective

        ↓

Residual Risk:
Reduced
```

This prevents organizations from implementing controls simply because they are common industry practices without understanding what risk they address.

A mature GRC program therefore maintains relationships between:

```text
Business Objectives
        ↓
Risks
        ↓
Requirements
        ↓
Controls
        ↓
Evidence
        ↓
Assessments
        ↓
Findings
        ↓
Remediation
        ↓
Residual Risk
        ↓
Management Decisions
```

This is the **GRC traceability chain**.

The chain can be expanded further:

```text
Business Objective
        ↓
Business Process
        ↓
Business Asset
        ↓
Risk
        ↓
Regulatory Requirement
        ↓
Control Objective
        ↓
Control
        ↓
Control Owner
        ↓
Control Operator
        ↓
Evidence
        ↓
Control Test
        ↓
Finding
        ↓
Remediation
        ↓
Residual Risk
        ↓
Risk Acceptance
        ↓
Management Reporting
```

This type of diagram is extremely useful during audits because it demonstrates that the organization's controls are connected to actual business requirements and risks.

GRC governance should also establish **clear committee structures**.

A possible structure is:

```text
Board
  ↓
Board Risk / Audit Committee
  ↓
Executive Risk Committee
  ↓
Cybersecurity Steering Committee
  ↓
GRC Working Groups
  ↓
Operational Teams
```

Each committee should have a defined purpose.

For example:

```text
Board Risk Committee
    ↓
Strategic Risk Oversight

Executive Risk Committee
    ↓
Enterprise Risk Decisions

Cybersecurity Steering Committee
    ↓
Cybersecurity Strategy and Major Risks

GRC Working Group
    ↓
Operational Coordination
```

Committee governance should also define:

```text
Meeting Frequency
Membership
Chairperson
Decision Rights
Escalation Rules
Reporting Requirements
Minutes
Action Tracking
```

A governance diagram can therefore include decision rights:

```text
Issue Identified
      ↓
GRC Review
      ↓
Material?
   ↙       ↘
 No         Yes
 ↓           ↓
Operational  Executive
Management  Management
              ↓
        Risk Committee
              ↓
             Board
```

This prevents unnecessary escalation while ensuring significant matters receive appropriate attention.

Another important governance element is **management information**.

Operational information should move upward through the GRC structure.

```text
Operational Data
      ↓
Control Metrics
      ↓
Risk Metrics
      ↓
GRC Dashboard
      ↓
Executive Reporting
      ↓
Risk Committee
      ↓
Board
```

Examples of information include:

```text
Open Risks

Risk Appetite Breaches

Control Failures

Compliance Gaps

Audit Findings

Overdue Remediation

Security Incidents

Third-Party Risks

Emerging Risks

Key Risk Indicators
```

Management reporting should focus on information that supports decisions.

For example, instead of reporting:

```text
"We completed 5,842 control checks."
```

a more useful executive message may be:

```text
"3 critical controls remain ineffective,
resulting in exposure above the approved
risk appetite."
```

The second statement supports management action.

A strong governance diagram therefore connects **information with decision-making**.

```text
Data
 ↓
Information
 ↓
Risk Insight
 ↓
Management Decision
 ↓
Action
 ↓
Risk Reduction
```

GRC governance should also include **exception management**.

A control exception can follow:

```text
Control Exception
       ↓
Document Exception
       ↓
Risk Assessment
       ↓
Compensating Control?
    ↙          ↘
  Yes           No
   ↓             ↓
Monitor       Remediate
   ↓             ↓
Review        Escalate
```

The exception should have:

```text
Business Justification

Risk Assessment

Risk Owner

Expiration Date

Compensating Control

Approval

Remediation Plan
```

This prevents permanent exceptions from becoming hidden security weaknesses.

A mature GRC governance model should therefore provide clear relationships between:

```text
Board
 ↓
Executive Management
 ↓
Risk Owners
 ↓
Control Owners
 ↓
Control Operators
 ↓
GRC Oversight
 ↓
Internal Audit
```

The model should also make the direction of information and authority clear:

```text
AUTHORITY

Board
  ↓
Management
  ↓
Business / Technology
  ↓
Operational Teams
```

while assurance and reporting move in multiple directions:

```text
REPORTING

Operations
   ↓
GRC
   ↓
Management
   ↓
Board

ASSURANCE

Internal Audit
   ↓
Management
   ↓
Board / Audit Committee
```

This creates a governance system where responsibilities do not overlap unnecessarily and important information does not become trapped at the operational level.

The ultimate objective is to establish a governance environment in which:

```text
Every Significant Risk
        ↓
Has an Owner

Every Important Control
        ↓
Has an Owner

Every Control
        ↓
Has Evidence

Every Finding
        ↓
Has a Remediation Owner

Every Significant Exception
        ↓
Has Approval

Every Major Risk
        ↓
Has an Escalation Path

Every Governance Level
        ↓
Receives Appropriate Information

Every Major Governance Process
        ↓
Can Receive Independent Assurance
```

This is what transforms a collection of GRC activities into an integrated governance system.



