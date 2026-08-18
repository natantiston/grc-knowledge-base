# 19.11 Business Continuity and Disaster Recovery Case Studies

## Part 1 – Conducting a Business Impact Analysis

A **Business Impact Analysis (BIA)** is one of the foundational activities of Business Continuity Management (BCM).

The purpose of a BIA is not simply to create a list of applications or identify which systems are important.

A mature BIA determines:

> **Which business activities are critical, what happens when they are disrupted, how quickly they must be restored, what resources they depend on, and what level of disruption the organization can tolerate.**

From a GRC perspective, the BIA connects:

**Business Objectives → Critical Activities → Dependencies → Impact → Recovery Requirements → Risk → Continuity Strategy**

A well-designed BIA provides the foundation for:

* Business continuity planning
* Disaster recovery
* Crisis management
* Cyber resilience
* Technology recovery
* Third-party resilience
* Recovery prioritization
* Risk treatment
* Executive decision-making

---

# Case Study: GlobalConnect Telecom

GlobalConnect Telecom is a large telecommunications and digital-services organization operating across several countries.

The organization provides:

* Mobile services
* Broadband
* Enterprise connectivity
* Cloud services
* Digital customer platforms
* Managed services
* Billing
* Customer support
* Network operations

The organization has:

* 20 million customers
* 18,000 employees
* Multiple data centers
* Hybrid cloud infrastructure
* 24/7 Network Operations Center
* 24/7 Security Operations Center
* Multiple critical suppliers

The Board has recently requested that management strengthen enterprise resilience after several disruptions involving:

* Cybersecurity incidents
* Cloud outages
* Supplier failures
* Power disruptions
* Network failures

The CEO asks the GRC function to conduct an enterprise-wide **Business Impact Analysis**.

---

# 1. Define the Purpose of the BIA

The first step is to establish why the BIA is being conducted.

GlobalConnect defines the objectives as:

1. Identify critical business activities.
2. Determine the consequences of disruption.
3. Establish recovery priorities.
4. Determine acceptable downtime.
5. Identify recovery requirements.
6. Identify dependencies.
7. Identify resource requirements.
8. Identify single points of failure.
9. Support business continuity planning.
10. Support disaster recovery planning.
11. Inform enterprise risk management.

The BIA will therefore become a major input into the organization's resilience program.

---

# 2. Establish BIA Governance

The BIA cannot be performed solely by IT.

The organization establishes a BIA governance team.

### Executive Sponsor

Chief Risk Officer

### BCM Manager

Coordinates the BIA.

### GRC

Provides:

* Risk methodology
* Governance
* Control mapping
* Documentation
* Reporting

### Business Owners

Identify:

* Critical activities
* Business impacts
* Recovery requirements

### IT

Identifies:

* Applications
* Infrastructure
* Technology dependencies

### Cybersecurity

Identifies:

* Security dependencies
* Cyber resilience requirements

### Procurement

Identifies:

* Critical suppliers

### Facilities

Identifies:

* Buildings
* Power
* Physical infrastructure

### Finance

Identifies:

* Financial impact

### Legal and Compliance

Identify:

* Regulatory obligations
* Contractual obligations

---

# 3. Define the BIA Scope

The organization defines the initial scope.

It covers:

* Corporate functions
* Customer services
* Network operations
* Enterprise services
* Cloud services
* Billing
* Customer support
* Digital platforms
* Critical suppliers
* Data centers

The BIA covers the full business service chain rather than only IT.

---

# 4. Identify Business Processes

The organization begins by identifying major business activities.

Example:

### Customer Management

* Customer onboarding
* Customer authentication
* Customer support
* Service changes

### Billing

* Usage collection
* Rating
* Invoice generation
* Payment processing

### Network Operations

* Network monitoring
* Fault management
* Service restoration

### Enterprise Services

* Service provisioning
* Customer support
* SLA management

### Cloud Services

* Cloud provisioning
* Platform monitoring
* Customer support

---

# 5. Identify Business Activities Rather Than Applications

This distinction is important.

Weak approach:

> "SAP is critical."

Better approach:

> "Customer billing is critical."

The application is important because it supports a business activity.

The BIA therefore starts with:

**Business Activity**

and then identifies:

**Applications → Technology → People → Facilities → Suppliers → Data**

---

# 6. Identify Critical Business Services

The organization groups activities into business services.

Example:

**Customer Billing Service**

includes:

* Usage collection
* Rating
* Invoice generation
* Payment processing
* Billing support

This is more useful for executive decision-making than a list of hundreds of applications.

---

# 7. Identify Business Owners

Each critical service receives an accountable business owner.

Example:

| Service                 | Business Owner               |
| ----------------------- | ---------------------------- |
| Customer Billing        | CFO                          |
| Customer Portal         | Chief Digital Officer        |
| Network Operations      | CTO                          |
| Enterprise Connectivity | Enterprise Business Director |
| Cloud Services          | Cloud Director               |
| Customer Support        | Customer Operations Director |

The owner is responsible for defining business impact and recovery requirements.

---

# 8. Define Impact Categories

GlobalConnect uses several impact categories.

### Financial

* Lost revenue
* Penalties
* Additional costs
* Compensation

### Operational

* Service disruption
* Productivity loss
* Backlogs

### Customer

* Customer dissatisfaction
* Service loss
* Churn

### Regulatory

* Regulatory breach
* Reporting obligations
* Enforcement

### Legal

* Contractual exposure
* Litigation

### Reputation

* Brand damage
* Loss of trust

### Safety

Where relevant, disruption could create safety consequences.

---

# 9. Define Impact Timeframes

Impact changes over time.

For example:

| Duration | Billing Impact |
| -------- | -------------- |
| 1 hour   | Low            |
| 4 hours  | Medium         |
| 8 hours  | High           |
| 24 hours | Severe         |
| 48 hours | Critical       |

This is important because the same disruption may be tolerable for one hour but unacceptable after 24 hours.

---

# 10. Determine Maximum Tolerable Period of Disruption

The organization identifies the:

**Maximum Tolerable Period of Disruption (MTPD)**

This represents the maximum period the organization can tolerate before the consequences become unacceptable.

Example:

**Customer Authentication**

MTPD:

**4 hours**

**Customer Billing**

MTPD:

**24 hours**

**Internal HR System**

MTPD:

**5 business days**

The values must be based on business impact rather than IT preference.

---

# 11. Determine Recovery Time Objective

The organization then establishes:

**Recovery Time Objective (RTO)**

RTO represents the target time within which a service should be restored after disruption.

Example:

| Service                    |     MTPD |        RTO |
| -------------------------- | -------: | ---------: |
| Emergency network services |  2 hours | 30 minutes |
| Customer authentication    |  4 hours |     1 hour |
| Network operations         |  4 hours |     1 hour |
| Billing                    | 24 hours |    8 hours |
| Customer portal            | 12 hours |    4 hours |
| HR                         |   5 days |     3 days |

RTO should generally be **shorter than MTPD**, providing recovery margin.

---

# 12. Determine Recovery Point Objective

The BIA also identifies:

**Recovery Point Objective (RPO)**

RPO determines how much data loss the business can tolerate.

Example:

### Customer Authentication

RPO:

**15 minutes**

### Billing

RPO:

**1 hour**

### HR

RPO:

**24 hours**

The RPO becomes a major input into technology architecture and backup strategy.

---

# 13. Distinguish RTO, RPO, and MTPD

These concepts should not be confused.

### MTPD

> How long can the business tolerate disruption?

### RTO

> How quickly should the service be restored?

### RPO

> How much data loss can the business tolerate?

Example:

**Billing**

MTPD = 24 hours

RTO = 8 hours

RPO = 1 hour

This means:

* Business can tolerate up to 24 hours.
* Management wants recovery within 8 hours.
* Data loss should not exceed approximately 1 hour.

---

# 14. Identify Dependencies

Every critical business activity has dependencies.

For Customer Billing:

**Billing Process**

↓

Billing Application

↓

Database

↓

Cloud/Server Infrastructure

↓

Network

↓

Identity

↓

Electricity

↓

Data Center

↓

Third-Party Payment Provider

The BIA identifies all these dependencies.

---

# 15. Identify People Dependencies

Technology is not the only dependency.

For billing, the organization may require:

* Billing analysts
* Finance personnel
* Application administrators
* Database administrators
* Vendor specialists
* Customer-service personnel

The BIA identifies:

* Minimum staffing
* Required skills
* Location requirements
* Alternate personnel

---

# 16. Identify Facility Dependencies

The organization assesses:

* Primary office
* Data center
* Disaster recovery site
* Network operations center
* Customer-service center

For each location:

* Can employees work remotely?
* Is alternate space available?
* Is power redundant?
* Is connectivity redundant?
* Are physical security controls available?

---

# 17. Identify Technology Dependencies

Technology dependencies include:

* Applications
* Databases
* Servers
* Cloud platforms
* Networks
* Identity services
* Storage
* Backup
* Monitoring

The organization documents which dependencies are critical to each business service.

---

# 18. Identify Data Dependencies

The BIA determines which data is required.

For customer billing:

* Customer master data
* Usage data
* Tariff information
* Payment data
* Invoice history

The organization identifies:

* Data owner
* Location
* Criticality
* Recovery requirement
* Retention requirement

---

# 19. Identify Third-Party Dependencies

Modern organizations are heavily dependent on suppliers.

GlobalConnect identifies:

* Cloud providers
* Payment providers
* Network vendors
* Managed-service providers
* Data-center providers
* Telecommunications carriers

For each supplier, the BIA asks:

> What happens if this supplier becomes unavailable?

---

# 20. Identify Single Points of Failure

The BIA reveals:

### Single Point of Failure

A dependency whose failure could significantly disrupt a critical business service.

Example:

Customer billing depends on a single payment gateway.

If that provider fails:

**Payment processing stops.**

This becomes a resilience risk.

---

# 21. Analyze Supplier Concentration

The organization also identifies concentration risk.

For example:

**70% of critical cloud workloads**

are hosted by one provider.

This may create:

**Third-Party Concentration Risk**

The BIA therefore becomes an input into third-party risk management.

---

# 22. Determine Minimum Business Continuity Requirements

For each critical service, the business defines the minimum acceptable operating capability.

Example:

Customer Support normally requires:

**1,200 agents**

During disruption:

**300 agents**

may be sufficient to maintain minimum service.

Therefore:

**Minimum Business Continuity Staffing = 300**

This becomes a continuity-planning requirement.

---

# 23. Determine Manual Workarounds

The organization asks:

> Can the process continue without the primary system?

For billing, perhaps:

* Manual usage reconciliation
* Temporary spreadsheets
* Deferred invoicing
* Manual customer adjustments

Manual workarounds may be used temporarily.

However, they introduce:

* Human error
* Capacity limitations
* Security risks
* Data-integrity risks

Therefore, they must be documented and tested.

---

# 24. Determine Minimum Service Level

Business continuity does not always mean returning to 100% operation.

Example:

Normal customer support:

**100% capacity**

Continuity mode:

**30% capacity**

This may be acceptable temporarily.

The BIA therefore identifies:

**Minimum Business Continuity Objective (MBCO)**

or equivalent minimum service requirement.

---

# 25. Financial Impact Analysis

Finance works with business owners to estimate financial consequences.

Example for customer billing:

| Duration | Estimated Financial Impact |
| -------- | -------------------------: |
| 4 hours  |                €200K–€400K |
| 8 hours  |                €500K–€800K |
| 24 hours |                €1.5M–€2.5M |
| 48 hours |                    €4M–€6M |

These figures are estimates and should be refined using actual business data.

---

# 26. Regulatory Impact

Some services have regulatory consequences.

For example:

A prolonged telecommunications outage could trigger:

* Regulatory reporting
* Service-level obligations
* Customer compensation
* Contractual requirements

The BIA therefore considers regulatory impact alongside financial impact.

---

# 27. Customer Impact

The organization evaluates:

* Number of customers affected
* Customer segment
* Criticality of service
* Vulnerable customers
* Enterprise customers
* Government customers

For example:

A four-hour outage affecting a consumer entertainment service may be tolerable.

A four-hour outage affecting emergency communications may be unacceptable.

Impact must therefore be evaluated in context.

---

# 28. Reputation Impact

The organization evaluates how disruption could affect:

* Customer trust
* Brand perception
* Media coverage
* Investor confidence
* Strategic relationships

Reputation is difficult to quantify, but it should not be ignored.

---

# 29. Legal and Contractual Impact

Some enterprise customers have contractual SLAs.

For example:

**Availability commitment: 99.95%**

A major outage may trigger:

* Service credits
* Penalties
* Contract disputes
* Escalation

These requirements must be included in the BIA.

---

# 30. Determine Business Service Criticality

GlobalConnect categorizes services.

### Tier 1 – Mission Critical

Disruption creates severe business, regulatory, or customer consequences.

Examples:

* Core telecommunications
* Emergency services
* Customer authentication

### Tier 2 – Business Critical

Disruption significantly affects operations.

Examples:

* Billing
* Customer portal
* Enterprise service management

### Tier 3 – Important

Disruption affects productivity but is temporarily manageable.

Examples:

* Internal collaboration
* Reporting

### Tier 4 – Non-Critical

Can remain unavailable for several days.

Examples:

* Non-essential applications

---

# 31. Example BIA Results

| Business Service        | Criticality |    MTPD |    RTO | RPO |
| ----------------------- | ----------- | ------: | -----: | --: |
| Core Network            | Tier 1      |      2h |    30m | 15m |
| Authentication          | Tier 1      |      4h |     1h | 15m |
| Customer Billing        | Tier 2      |     24h |     8h |  1h |
| Customer Portal         | Tier 2      |     12h |     4h |  1h |
| Enterprise Provisioning | Tier 2      |     12h |     4h | 30m |
| HR                      | Tier 3      |  5 days | 3 days | 24h |
| Corporate Reporting     | Tier 4      | 10 days | 7 days | 48h |

This table becomes a critical input into the continuity program.

---

# 32. Identify Recovery Dependencies

Recovery priorities must consider dependencies.

For example:

You cannot restore:

**Customer Portal**

until:

**Identity Service**

is operational.

You cannot restore:

**Billing**

until:

**Database + Network + Identity**

are available.

Therefore, the recovery sequence is:

**Identity**

↓

**Network**

↓

**Database**

↓

**Billing**

↓

**Customer Portal**

This is why dependency mapping is essential.

---

# 33. Business Impact vs Technical Criticality

A technically complex system is not necessarily the most business-critical system.

For example:

**Legacy reporting platform**

may be technically difficult to recover.

But:

**Customer authentication**

may be much more important to the business.

The BIA prevents IT complexity from being confused with business criticality.

---

# 34. BIA Interview Process

GlobalConnect conducts structured interviews with business owners.

Questions include:

### Business Activity

What does the process do?

### Impact

What happens if it stops?

### Time

How long can it remain unavailable?

### Data

What information is required?

### People

Who is needed?

### Technology

Which systems support the process?

### Suppliers

Which external parties are required?

### Manual Workaround

Can the process continue manually?

### Recovery

What is the minimum acceptable service?

### Dependencies

What must be available first?

---

# 35. BIA Workshop Example

The Billing Director says:

> "Billing can be unavailable for 48 hours."

Finance disagrees:

> "Revenue recognition and cash collection become significantly affected after 24 hours."

Customer Operations says:

> "Customers begin experiencing serious service problems after 12 hours."

The BIA team facilitates the discussion.

The final agreed position becomes:

**MTPD = 24 hours**

**RTO = 8 hours**

This demonstrates why BIA is a **business governance exercise**, not simply an IT exercise.

---

# 36. Validate BIA Results

After interviews, GRC reviews the results for inconsistencies.

For example:

### Service A

RTO = 2 hours

### Dependency B

RTO = 8 hours

This is impossible.

The dependency must recover at least as quickly as the service that depends on it.

The GRC team therefore performs a consistency check.

---

# 37. BIA Dependency Graph

A simplified dependency structure might look like:

**Customer Services**

↓

**Customer Portal**

↓

**Identity**

↓

**Network**

↓

**Data Center / Cloud**

↓

**Power + Connectivity**

Each layer must meet the recovery requirements of the business service.

---

# 38. Identify Resilience Gaps

The BIA reveals several weaknesses.

### Gap 1

Customer authentication has only one regional recovery environment.

### Gap 2

Billing depends on a single external payment provider.

### Gap 3

Several critical applications do not meet their RTO.

### Gap 4

Manual workarounds are undocumented.

### Gap 5

Some suppliers have no validated recovery evidence.

These become risk-treatment candidates.

---

# 39. Convert BIA Findings into Risks

Example:

### BIA Finding

Billing depends on a single payment provider.

↓

### Risk

Failure of the payment provider could interrupt customer payment processing.

↓

### Likelihood

Medium

↓

### Impact

High

↓

### Risk Rating

High

↓

### Treatment

Establish secondary payment capability.

The BIA therefore feeds directly into ERM.

---

# 40. BIA and Cybersecurity

Cybersecurity is increasingly integrated with business continuity.

Potential cyber disruptions include:

* Ransomware
* DDoS
* Cloud compromise
* Identity compromise
* Data corruption
* Supply-chain attacks

The BIA determines:

> Which services must be restored first after a cyberattack?

This makes BIA an important part of cyber resilience.

---

# 41. BIA and Disaster Recovery

The BIA determines **what the business needs**.

Disaster Recovery determines **how technology will recover to meet those requirements**.

The relationship is:

**BIA**

→ Critical Services

→ RTO/RPO

→ Technology Requirements

→ Disaster Recovery Strategy

For example:

**BIA:** Billing RTO = 8 hours.

↓

**DR Requirement:** Recovery environment must restore billing within 8 hours.

↓

**Testing:** Recovery test demonstrates 6.5 hours.

↓

**Result:** DR capability meets requirement.

---

# 42. BIA and Business Continuity

The BIA also informs non-technical continuity measures.

For example:

If a customer-service center becomes unavailable:

* Employees may work remotely.
* Calls may be redirected.
* Alternate offices may be activated.
* Temporary staffing may be used.

Thus:

**BIA → Business Continuity Strategy**

and:

**BIA → Disaster Recovery Strategy**

---

# 43. BIA and Third-Party Risk

For each critical supplier, the organization evaluates:

* Supplier BIA
* Business continuity plan
* Disaster recovery plan
* RTO
* RPO
* Recovery testing
* Geographic redundancy
* Incident response
* Financial resilience

A supplier's recovery capability must align with the organization's own requirements.

---

# 44. Supplier BIA Example

GlobalConnect requires its cloud provider to support:

**RTO:** 4 hours

**RPO:** 1 hour

The supplier reports:

**RTO:** 8 hours

This creates a resilience gap.

The organization must either:

1. Negotiate improved supplier capability.
2. Implement compensating controls.
3. Establish an alternate provider.
4. Accept the risk formally.

---

# 45. BIA Documentation

The final BIA package contains:

* Scope
* Methodology
* Business services
* Business owners
* Impact assessments
* MTPD
* RTO
* RPO
* Dependencies
* Minimum staffing
* Manual workarounds
* Critical suppliers
* Recovery priorities
* Resilience gaps
* Risk findings
* Management approvals

The BIA becomes controlled GRC documentation.

---

# 46. BIA Evidence

Evidence may include:

* Workshop records
* Interview notes
* Approved BIA forms
* Dependency maps
* Financial estimates
* Business-owner approvals
* RTO/RPO approvals
* Supplier evidence
* Recovery-test results

This provides auditability.

---

# 47. BIA Approval

The business owner approves the BIA.

For critical services, executive approval may be required.

Example:

**Customer Billing**

Business Owner: CFO

Reviewed by:

* CIO
* CISO
* BCM Manager
* Risk

Approved by:

**Executive Risk Committee**

This creates accountability.

---

# 48. BIA Review Frequency

The BIA should not be treated as a one-time document.

GlobalConnect reviews critical BIAs:

**At least annually**

and after significant changes such as:

* Major technology changes
* New suppliers
* Mergers and acquisitions
* New regulations
* Major incidents
* New products
* Cloud migrations
* Organizational restructuring

---

# 49. Trigger-Based BIA Review

Certain events automatically trigger reassessment.

Examples:

### Major Cyber Incident

Reassess critical dependencies.

### Cloud Migration

Reassess technology recovery.

### New Supplier

Reassess third-party dependency.

### Major Product Launch

Reassess business criticality.

### Regulatory Change

Reassess impact requirements.

This makes the BIA dynamic.

---

# 50. Common BIA Failures

Organizations frequently perform poor BIAs because they:

### Focus only on IT

Business impact is ignored.

### Use application lists

Business services are not identified.

### Let IT determine RTO

Business owners should establish business requirements.

### Ignore suppliers

Third-party dependencies are overlooked.

### Ignore manual processes

Workarounds are not planned.

### Use unrealistic RTOs

Every application is declared "critical."

### Never validate assumptions

The BIA becomes outdated.

### Do not connect BIA to risk

Identified gaps are not treated.

### Do not test recovery

The organization assumes the BIA requirements can be achieved.

---

# 51. Executive BIA Dashboard

A useful executive dashboard might show:

### Critical Business Services

**24**

### Services with Validated RTO

**21 / 24**

### Services Without Adequate DR

**5**

### Critical Suppliers

**37**

### Suppliers with Validated Recovery

**31 / 37**

### High Resilience Risks

**12**

### Overdue BIA Reviews

**3**

This allows executives to see the organization's resilience posture.

---

# 52. BIA Maturity Model

GlobalConnect assesses BIA maturity.

### Level 1 – Ad Hoc

Business continuity is reactive.

### Level 2 – Developing

Critical services are identified.

### Level 3 – Defined

Formal BIA methodology exists.

### Level 4 – Managed

BIAs are linked to risk, DR, suppliers, and metrics.

### Level 5 – Optimized

BIA is dynamic, automated, continuously monitored, and integrated with enterprise resilience management.

A mature enterprise should target:

**Level 4–5**

for critical services.

---

# 53. Practical GRC Exercise

You are the **GRC/Business Continuity Manager** for a telecommunications organization.

The organization asks you to perform a BIA for these services:

1. Mobile network
2. Customer authentication
3. Customer billing
4. Customer portal
5. Enterprise provisioning
6. Customer support
7. Cloud services
8. HR
9. Finance
10. Corporate reporting

For each service, determine:

### Business Impact

* Financial
* Operational
* Customer
* Regulatory
* Legal
* Reputation

### Recovery Requirements

* Criticality
* MTPD
* RTO
* RPO
* Minimum service level

### Dependencies

* People
* Applications
* Infrastructure
* Data
* Facilities
* Suppliers

### Continuity

* Manual workaround
* Alternate location
* Alternate technology
* Alternate supplier

### Governance

* Business owner
* Risk owner
* Executive approval

Then create a consolidated table.

| Service                 | Criticality | MTPD | RTO | RPO | Main Dependency | Recovery Priority |
| ----------------------- | ----------- | ---: | --: | --: | --------------- | ----------------- |
| Mobile Network          |             |      |     |     |                 |                   |
| Authentication          |             |      |     |     |                 |                   |
| Billing                 |             |      |     |     |                 |                   |
| Customer Portal         |             |      |     |     |                 |                   |
| Enterprise Provisioning |             |      |     |     |                 |                   |
| Customer Support        |             |      |     |     |                 |                   |
| Cloud Services          |             |      |     |     |                 |                   |
| HR                      |             |      |     |     |                 |                   |
| Finance                 |             |      |     |     |                 |                   |
| Reporting               |             |      |     |     |                 |                   |

Finally, identify:

1. Five critical business services
2. Five critical dependencies
3. Three single points of failure
4. Three high resilience risks
5. Three continuity improvements
6. Three disaster-recovery requirements

---

# 54. Final BIA Governance Model

A mature BIA process follows:

**Identify Business Services**

↓

**Identify Business Owners**

↓

**Assess Impact**

↓

**Determine MTPD**

↓

**Determine RTO/RPO**

↓

**Identify Dependencies**

↓

**Identify Minimum Service Levels**

↓

**Identify Workarounds**

↓

**Identify Resilience Gaps**

↓

**Convert Gaps into Risks**

↓

**Develop Continuity/DR Requirements**

↓

**Approve**

↓

**Test**

↓

**Review and Update**

The most important distinction is:

> **The BIA does not design the recovery solution.**

It defines **what the business requires from the recovery solution**.

The overall relationship is:

**Business Requirements**

→ **BIA**

→ **Criticality**

→ **MTPD**

→ **RTO/RPO**

→ **Continuity Strategy**

→ **Disaster Recovery Strategy**

→ **Testing**

→ **Resilience Assurance**

A mature GRC professional therefore uses the BIA as a bridge between **business strategy, risk management, cybersecurity, business continuity, disaster recovery, third-party risk, and executive governance**.

The ultimate objective is not simply to document what happens when a system goes down.

It is to determine:

> **Which business services the organization cannot afford to lose, how long it can tolerate their disruption, what dependencies must be protected, and what recovery capability management must fund and maintain.**

# 19.11 Business Continuity and Disaster Recovery Case Studies

## Part 2 – Developing a Business Continuity Strategy

A **Business Continuity Strategy (BCS)** defines how an organization will continue delivering its critical products and services when a disruptive event occurs.

The BIA from Part 1 established:

* What is critical
* What the business impact is
* Maximum tolerable disruption
* RTO
* RPO
* Minimum service requirements
* Critical dependencies

The next question is:

> **How will the organization maintain or restore those critical services within the required recovery objectives?**

The strategy therefore connects:

**BIA → Recovery Requirements → Continuity Options → Strategy Selection → Resources → Implementation → Testing**

---

# Case Study: GlobalConnect Telecom

GlobalConnect Telecom has completed its enterprise BIA.

The BIA identified:

* 24 critical business services
* 37 critical suppliers
* 12 high resilience risks
* 5 services with inadequate disaster-recovery capability
* 3 significant single points of failure

The most critical services include:

1. Mobile network
2. Customer authentication
3. Customer billing
4. Enterprise provisioning
5. Customer support

The executive committee now asks:

> **"What continuity strategy should we fund, and how much resilience do we actually need?"**

The GRC and BCM teams must develop the strategy.

---

# 1. What Is a Business Continuity Strategy?

A Business Continuity Strategy defines the organization's approach for:

* Continuing critical operations
* Protecting people
* Protecting information
* Maintaining customer services
* Recovering technology
* Managing suppliers
* Maintaining communications
* Responding to disruption
* Restoring normal operations

It answers:

> **What capabilities do we need before, during, and after a disruption?**

---

# 2. Business Continuity vs Disaster Recovery

These terms are closely related but different.

### Business Continuity

Focuses on:

> **Keeping the business operating.**

### Disaster Recovery

Focuses primarily on:

> **Recovering technology and IT services.**

For example:

A customer-support center becomes unavailable.

### Business Continuity

Employees work from another location or remotely.

Calls are redirected.

Temporary staffing is activated.

### Disaster Recovery

The supporting CRM and communication systems are restored.

Therefore:

**BCM is broader than DR.**

---

# 3. The Strategy Development Process

GlobalConnect follows:

**BIA**

↓

**Recovery Requirements**

↓

**Continuity Options**

↓

**Risk Assessment**

↓

**Cost-Benefit Analysis**

↓

**Strategy Selection**

↓

**Executive Approval**

↓

**Implementation**

↓

**Testing**

↓

**Continual Improvement**

---

# 4. Start With Recovery Requirements

The strategy cannot be designed before understanding the requirements.

Example:

### Customer Authentication

MTPD:

**4 hours**

RTO:

**1 hour**

RPO:

**15 minutes**

Minimum service:

**80% of normal authentication capacity**

Therefore, the continuity strategy must support those requirements.

---

# 5. Identify Continuity Options

Organizations normally have several options.

### Option 1 – Preventive Controls

Prevent disruption.

Examples:

* Redundant power
* Network redundancy
* High availability
* Backup systems
* Security controls

### Option 2 – Alternate Processing

Move processing to another environment.

Examples:

* Secondary data center
* Cloud recovery
* Alternate region

### Option 3 – Alternate Workplace

Move employees.

Examples:

* Remote work
* Alternate office
* Recovery facility

### Option 4 – Manual Workaround

Continue the process manually.

### Option 5 – Alternate Supplier

Use another provider.

### Option 6 – Service Degradation

Provide reduced functionality temporarily.

### Option 7 – Reciprocal Arrangements

Another organization provides temporary support.

---

# 6. Choose Strategy Based on Criticality

Not every business process needs the same level of resilience.

For example:

### Core Network

May require:

**Near-zero interruption**

### Billing

May tolerate:

**Several hours**

### HR

May tolerate:

**Several days**

### Historical Reporting

May tolerate:

**Several weeks**

A major BCM mistake is attempting to make everything equally resilient.

That creates unnecessary cost.

---

# 7. Tiered Continuity Strategy

GlobalConnect establishes four resilience tiers.

### Tier 1 – Mission Critical

RTO:

**≤ 1 hour**

Characteristics:

* High availability
* Geographic redundancy
* Real-time replication
* 24/7 support

### Tier 2 – Business Critical

RTO:

**1–8 hours**

Characteristics:

* Secondary environment
* Regular backups
* Recovery procedures
* Alternate staffing

### Tier 3 – Important

RTO:

**8–72 hours**

Characteristics:

* Standard backup
* Documented recovery
* Alternate work arrangements

### Tier 4 – Non-Critical

RTO:

**>72 hours**

Characteristics:

* Basic backup
* Manual recovery
* Lower-cost resilience

---

# 8. Strategy for the Mobile Network

The mobile network is Tier 1.

The BIA established:

**MTPD:** 2 hours

**RTO:** 30 minutes

**RPO:** 15 minutes

The organization chooses:

### Primary Strategy

Geographically redundant network infrastructure.

### Supporting Measures

* Multiple network paths
* Redundant core systems
* Backup power
* Geographic separation
* Automated failover
* 24/7 monitoring
* Spare equipment

The strategy is designed to minimize service interruption.

---

# 9. Strategy for Customer Authentication

Authentication is also Tier 1.

The organization implements:

* Primary authentication platform
* Secondary regional platform
* Real-time replication
* Multiple network paths
* Emergency authentication procedures

If the primary environment fails:

**Traffic → Secondary Environment**

automatically.

This supports the one-hour RTO.

---

# 10. Strategy for Customer Billing

Billing is Tier 2.

The BIA requires:

**RTO = 8 hours**

**RPO = 1 hour**

The organization determines that real-time geographic redundancy would be unnecessarily expensive.

Instead, it chooses:

* Secondary recovery environment
* Hourly replication
* Immutable backups
* Documented recovery procedures
* Recovery testing

This is an example of:

> **Risk-based resilience investment.**

---

# 11. Strategy for Customer Support

Customer support has:

**RTO = 4 hours**

The organization determines that physical office redundancy is not sufficient.

Instead, it develops:

### Remote Workforce Strategy

Employees can work remotely using:

* Secure VPN/ZTNA
* Cloud contact center
* Multi-factor authentication
* Cloud-based CRM
* Redundant internet connectivity

This creates operational resilience without requiring a second physical call center.

---

# 12. Strategy for Workforce Continuity

People are a critical business dependency.

GlobalConnect establishes:

### Primary Workforce

Normal employees.

### Alternate Workforce

Cross-trained employees.

### Remote Workforce

Employees capable of working remotely.

### External Workforce

Approved contractors or managed-service providers.

The organization documents:

* Required skills
* Minimum staffing
* Contact information
* Backup personnel
* Training requirements

---

# 13. Cross-Training

A major continuity risk is:

> **Key-person dependency**

Example:

Only one employee knows how to operate a critical legacy billing system.

If that employee becomes unavailable:

**Billing recovery may fail.**

The strategy therefore includes:

* Cross-training
* Job rotation
* Documentation
* Backup personnel

This reduces people-related resilience risk.

---

# 14. Alternate Work Locations

GlobalConnect identifies:

### Primary Site

Madrid Operations Center

### Alternate Site

Barcelona Recovery Office

### Remote Workforce

Available across multiple regions.

The organization evaluates:

* Capacity
* Connectivity
* Security
* Power
* Access
* Equipment
* Staffing

The alternate location must support the required minimum service.

---

# 15. Remote Work as a Continuity Strategy

Remote work can provide resilience against:

* Building failure
* Local disasters
* Transportation disruption
* Severe weather
* Public health emergencies
* Civil disruptions

However, it introduces risks:

* Home internet dependency
* Endpoint security
* Identity security
* VPN capacity
* Data protection
* Physical security

Therefore:

**Remote work ≠ automatic resilience.**

It must be designed and tested.

---

# 16. Technology Continuity Strategy

Technology continuity may use:

### High Availability

Systems remain operational through redundancy.

### Fault Tolerance

Failure of one component does not interrupt service.

### Backup

Data can be restored.

### Replication

Data is copied to another environment.

### Disaster Recovery

Systems are rebuilt or restored after major failure.

### Cloud Recovery

Workloads are recovered in another cloud region.

The appropriate approach depends on RTO and RPO.

---

# 17. Backup Strategy

GlobalConnect implements:

### Operational Backups

Frequent backups for routine recovery.

### Immutable Backups

Protected from modification or deletion.

### Offline/Isolated Backups

Protected against ransomware.

### Geographic Redundancy

Copies stored in separate locations.

The strategy must consider:

**Availability + Integrity + Confidentiality**

not simply whether backups exist.

---

# 18. Ransomware-Resilient Continuity

Modern BCM must account for ransomware.

A conventional backup may not be sufficient.

Attackers may compromise:

* Backup credentials
* Backup servers
* Backup management systems

Therefore, GlobalConnect uses:

**Production**

↓

**Replication**

↓

**Immutable Backup**

↓

**Isolated Recovery Copy**

↓

**Validated Recovery**

This creates stronger cyber resilience.

---

# 19. Data Recovery Strategy

The strategy must define:

* What data is backed up
* Backup frequency
* Retention
* Encryption
* Location
* Integrity verification
* Restoration priority
* Recovery testing

A backup that cannot be successfully restored is not a reliable continuity capability.

---

# 20. Cloud Continuity Strategy

GlobalConnect uses multiple cloud regions.

For critical workloads:

**Primary Region**

↓

**Secondary Region**

↓

**Backup Storage**

This can reduce dependence on a single location.

However, multi-region architecture can create:

* Higher cost
* More complexity
* Configuration risk
* Data synchronization issues

Therefore, the strategy should be risk-based.

---

# 21. Third-Party Continuity Strategy

GlobalConnect requires critical suppliers to demonstrate resilience.

Supplier requirements include:

* Business continuity plan
* Disaster recovery plan
* RTO/RPO
* Recovery testing
* Incident notification
* Alternate processing capability
* Geographic redundancy
* Cybersecurity controls

For critical suppliers, the organization may require:

**Annual recovery-test evidence.**

---

# 22. Supplier Substitution

Where possible, GlobalConnect establishes alternate suppliers.

Example:

### Payment Processing

Primary:

Supplier A

Secondary:

Supplier B

If Supplier A fails:

**Payment Processing → Supplier B**

This is an example of:

**Supplier redundancy.**

---

# 23. Supplier Concentration Risk

Not every service can easily have a second supplier.

For example:

A specialized telecommunications provider may have no practical alternative.

In that case, the organization may use:

* Increased contractual requirements
* Supplier monitoring
* Additional inventory
* Longer-term contingency arrangements
* Financial monitoring
* Enhanced incident response

The strategy should recognize when true redundancy is impossible.

---

# 24. Facilities Continuity

The organization evaluates:

* Power
* Cooling
* Physical access
* Fire protection
* Water
* Connectivity
* Building access
* Environmental risks

Critical facilities use:

* UPS
* Generators
* Multiple power feeds
* Redundant cooling
* Geographic separation

This protects against infrastructure disruption.

---

# 25. Communications Continuity

During a crisis, communication is critical.

GlobalConnect establishes:

### Primary

Corporate communication platform

### Secondary

Emergency collaboration platform

### Tertiary

Telephone/SMS

### Emergency

Crisis-management communication channel

The organization must not depend on a single communication platform during a crisis.

---

# 26. Crisis Management Strategy

Business continuity focuses on maintaining services.

Crisis management focuses on managing the overall event.

The crisis-management strategy includes:

* Crisis Management Team
* Incident Commander
* Executive escalation
* Legal
* Communications
* Public relations
* Regulatory liaison
* Security
* Business operations

The strategy defines:

**Who makes decisions when normal governance is disrupted?**

---

# 27. Crisis Escalation Thresholds

The organization defines escalation criteria.

For example, escalation to the executive crisis team occurs when:

* Critical service unavailable >1 hour
* Customer impact >500,000
* Suspected major data breach
* Financial impact >€5M
* Regulatory notification required
* Major supplier failure
* Safety implications

This prevents delayed escalation.

---

# 28. Continuity Strategy for Cyber Incidents

The strategy specifically addresses:

### Ransomware

Recovery from clean backups.

### DDoS

Traffic filtering and alternate connectivity.

### Identity Compromise

Emergency identity controls.

### Cloud Outage

Alternate region.

### Data Corruption

Point-in-time recovery.

### Supplier Cyber Incident

Isolation and alternate supplier.

Cybersecurity and BCM must therefore work together.

---

# 29. Continuity Strategy for Physical Disasters

Potential events include:

* Fire
* Flood
* Earthquake
* Severe weather
* Building failure
* Power failure

Strategies include:

* Alternate site
* Remote work
* Geographic redundancy
* Backup power
* Alternate suppliers

The strategy must not be designed around only one type of disaster.

---

# 30. Continuity Strategy for Pandemic or Workforce Disruption

The organization considers:

* Employee unavailability
* Travel restrictions
* Office closures
* Increased remote work
* Reduced staffing

Continuity options include:

* Cross-training
* Remote work
* Shift rotation
* Alternate staffing
* Automation
* Outsourcing

The objective is to maintain minimum service with reduced workforce capacity.

---

# 31. Minimum Business Continuity Objective

The BIA identified minimum service levels.

Example:

### Customer Support

Normal:

**1,200 agents**

Continuity:

**300 agents**

The strategy therefore ensures:

* Remote access for 300 agents
* CRM availability
* Call routing
* Secure authentication
* Management oversight

This creates a practical continuity capability.

---

# 32. Cost-Benefit Analysis

Resilience has a cost.

Suppose GlobalConnect evaluates three options for billing.

### Option A – Basic Backup

Cost:

**€500K**

RTO:

24 hours

### Option B – Secondary Recovery Site

Cost:

**€1.5M**

RTO:

8 hours

### Option C – Active-Active Architecture

Cost:

**€5M**

RTO:

15 minutes

The BIA requires:

**RTO = 8 hours**

Therefore, Option B may provide the best balance.

The organization should not automatically purchase the most expensive solution.

---

# 33. Risk-Based Strategy Selection

The decision should consider:

**Risk Reduction**

*

**Business Requirement**

*

**Cost**

*

**Operational Complexity**

*

**Regulatory Requirement**

*

**Residual Risk**

This is a classic GRC decision.

---

# 34. Executive Resilience Investment Decision

The GRC team presents:

| Option   |  Cost | RTO | Residual Risk |
| -------- | ----: | --: | ------------- |
| Basic    | €500K | 24h | High          |
| Balanced | €1.5M |  8h | Medium        |
| Premium  |   €5M | 15m | Low           |

Recommendation:

**Balanced**

because it meets the approved business requirement without excessive cost.

---

# 35. Business Continuity Strategy Document

The strategy document should contain:

## 1. Purpose

Why the strategy exists.

## 2. Scope

What is covered.

## 3. Business Priorities

Critical services.

## 4. Recovery Requirements

MTPD, RTO, RPO.

## 5. Continuity Options

Available approaches.

## 6. Selected Strategies

Approved solutions.

## 7. People

Staffing and skills.

## 8. Technology

IT and cyber resilience.

## 9. Facilities

Alternate locations.

## 10. Suppliers

Third-party resilience.

## 11. Communications

Crisis communications.

## 12. Crisis Management

Governance and escalation.

## 13. Recovery

Return to normal operations.

## 14. Testing

Validation requirements.

## 15. Governance

Ownership and approval.

---

# 36. Continuity Strategy Matrix

GlobalConnect creates a consolidated matrix.

| Service          | RTO | Strategy              | Alternate Capability | Owner |
| ---------------- | --: | --------------------- | -------------------- | ----- |
| Mobile Network   | 30m | Geographic redundancy | Secondary core       | CTO   |
| Authentication   |  1h | Active/standby        | Secondary region     | CISO  |
| Billing          |  8h | DR site               | Secondary platform   | CFO   |
| Customer Portal  |  4h | Cloud recovery        | Secondary region     | CDO   |
| Customer Support |  4h | Remote workforce      | Cloud contact center | COO   |
| HR               |  3d | Backup/manual         | Remote access        | CHRO  |

This becomes the organization's continuity blueprint.

---

# 37. Recovery Sequence

The strategy also defines recovery order.

For GlobalConnect:

### Priority 1

Network

### Priority 2

Identity and Authentication

### Priority 3

Core Data Platforms

### Priority 4

Billing

### Priority 5

Customer Portal

### Priority 6

Enterprise Services

### Priority 7

Internal Corporate Systems

The recovery sequence should reflect business dependencies.

---

# 38. Avoiding Recovery Conflicts

Suppose the business wants:

**Customer Portal**

restored immediately.

But cybersecurity requires:

**Identity platform**

to be validated first.

The continuity strategy must establish governance for resolving such conflicts.

The principle is:

> **Recovery must not create a second incident.**

Fast recovery with compromised systems can increase organizational risk.

---

# 39. Continuity and Security

Continuity does not mean:

> "Restore everything as quickly as possible."

It means:

> **Restore critical services safely within approved risk limits.**

For example, a compromised server should not simply be restored from an unvalidated backup because management wants the application online.

Recovery must include:

* Security validation
* Malware scanning
* Identity controls
* Configuration validation
* Data integrity checks

---

# 40. Recovery From a Cyberattack

A mature cyber-recovery sequence is:

**Contain Attack**

↓

**Eradicate Threat**

↓

**Validate Environment**

↓

**Validate Backups**

↓

**Restore Critical Infrastructure**

↓

**Restore Applications**

↓

**Validate Security**

↓

**Restore Business Service**

↓

**Monitor**

This should be incorporated into the continuity strategy.

---

# 41. Continuity Strategy and Risk Appetite

The Board may define:

> "The organization has very low tolerance for disruption to core telecommunications services."

This directly influences strategy.

For core network:

**High resilience investment**

For internal reporting:

**Lower investment**

Therefore:

**Risk Appetite → Resilience Investment**

---

# 42. Continuity Strategy and Regulatory Requirements

Some sectors have mandatory resilience requirements.

The strategy should consider applicable:

* Telecommunications regulations
* Financial regulations
* Privacy obligations
* Cybersecurity requirements
* Critical infrastructure requirements
* Contractual requirements

Regulatory requirements may establish minimum resilience levels.

---

# 43. Strategy Approval

The strategy is reviewed by:

* BCM
* GRC
* IT
* Cybersecurity
* Business owners
* Procurement
* Legal
* Finance

Then submitted to:

**Enterprise Risk Committee**

and ultimately:

**Executive Management / Board**

depending on governance structure.

---

# 44. Implementation Roadmap

GlobalConnect creates a 12-month implementation plan.

### Months 1–3

* Establish alternate work capability
* Improve critical backups
* Validate supplier recovery

### Months 4–6

* Implement secondary billing environment
* Improve authentication redundancy
* Conduct recovery exercises

### Months 7–9

* Implement additional network redundancy
* Improve cloud resilience
* Conduct cyber-recovery testing

### Months 10–12

* Full enterprise exercise
* Board resilience review
* Remediation validation

---

# 45. Metrics

The organization measures:

### Coverage

Percentage of critical services with approved continuity strategies.

### Recovery

Percentage meeting RTO.

### Data

Percentage meeting RPO.

### Testing

Percentage of strategies tested.

### Suppliers

Percentage of critical suppliers with validated recovery capability.

### People

Percentage of critical roles with trained alternates.

### Risks

Number of high resilience risks.

Example dashboard:

**Critical services with approved strategy:** 100%

**Services meeting RTO:** 92%

**Services meeting RPO:** 95%

**Critical suppliers tested:** 89%

**Critical roles with alternates:** 94%

---

# 46. Testing the Strategy

A strategy is only credible if it is tested.

Testing methods include:

### Walkthrough

Discuss the scenario.

### Tabletop Exercise

Management simulates a crisis.

### Technical Recovery Test

Systems are restored.

### Failover Test

Traffic is switched to alternate infrastructure.

### Full Simulation

Business and technology operate under simulated disaster conditions.

The level of testing should correspond to criticality.

---

# 47. Lessons From Testing

Suppose the billing recovery test shows:

Required RTO:

**8 hours**

Actual:

**13 hours**

This means:

**Continuity strategy does not currently meet the BIA requirement.**

The organization must:

1. Identify the cause.
2. Assess risk.
3. Develop corrective action.
4. Assign an owner.
5. Set a deadline.
6. Retest.

This creates the improvement cycle.

---

# 48. Continuity Strategy and GRC

From a GRC perspective, the strategy creates several governance artifacts:

* Business requirements
* Risk assessments
* Recovery requirements
* Control requirements
* Supplier requirements
* Management approvals
* Risk acceptance
* Test evidence
* Corrective actions
* Executive reporting

Therefore, BCM becomes part of enterprise governance rather than an isolated IT activity.

---

# 49. Common Strategy Mistakes

### Mistake 1

Buying DR technology before conducting the BIA.

### Mistake 2

Giving every system the same RTO.

### Mistake 3

Ignoring people.

### Mistake 4

Ignoring suppliers.

### Mistake 5

Ignoring cyberattacks.

### Mistake 6

Assuming cloud automatically provides resilience.

### Mistake 7

Never testing the strategy.

### Mistake 8

Failing to consider security during recovery.

### Mistake 9

Ignoring manual workarounds.

### Mistake 10

Failing to obtain executive approval.

---

# 50. Practical GRC Exercise

You are the **Business Continuity and GRC Manager** for GlobalConnect.

The BIA has produced these requirements:

| Service          | MTPD | RTO | RPO |
| ---------------- | ---: | --: | --: |
| Mobile Network   |   2h | 30m | 15m |
| Authentication   |   4h |  1h | 15m |
| Billing          |  24h |  8h |  1h |
| Customer Portal  |  12h |  4h |  1h |
| Customer Support |  12h |  4h |  1h |
| HR               |   5d |  3d | 24h |

Develop a continuity strategy for each service.

For every service determine:

### 1. Continuity Strategy

Examples:

* High availability
* Geographic redundancy
* Cloud recovery
* Alternate site
* Remote workforce
* Manual workaround
* Alternate supplier

### 2. Required Resources

Identify:

* People
* Technology
* Facilities
* Suppliers
* Data

### 3. Recovery Approach

Define:

* Primary recovery location
* Alternate recovery location
* Backup strategy
* Failover strategy

### 4. Security Requirements

Include:

* Identity
* MFA
* Backup protection
* Network segmentation
* Monitoring
* Recovery validation

### 5. Testing

Define:

* Test frequency
* Test type
* Success criteria

### 6. Governance

Identify:

* Business owner
* Risk owner
* Strategy owner
* Executive approval

---

# 51. Final Business Continuity Strategy Model

A mature strategy follows:

**BIA**

↓

**Criticality**

↓

**MTPD / RTO / RPO**

↓

**Continuity Options**

↓

**Risk & Cost Analysis**

↓

**Strategy Selection**

↓

**People + Process + Technology + Facilities + Suppliers**

↓

**Implementation**

↓

**Testing**

↓

**Corrective Action**

↓

**Continual Improvement**

The key principle is:

> **Business continuity strategy should be driven by business requirements, not by the technology that happens to be available.**

A strong GRC professional asks:

> **What does the business need to survive?**

Then:

> **What level of resilience is justified by the risk?**

And finally:

> **Can we demonstrate through testing that the organization can actually achieve the required recovery objectives?**

That is the difference between having a **business continuity document** and having a **real organizational resilience capability**.

# 19.11 Business Continuity and Disaster Recovery Case Studies

## Part 3 – Responding to a Major IT Disaster

A major IT disaster is an event that causes significant disruption to technology services and threatens the organization's ability to continue critical business operations.

Examples include:

* Data center failure
* Major cloud outage
* Ransomware
* Destructive malware
* Core network failure
* Database corruption
* Major power failure
* Storage failure
* Critical software failure
* Cyberattack
* Regional infrastructure outage
* Major third-party technology failure

From a GRC perspective, the objective is not simply:

> **"Get the servers back online."**

The objective is:

> **Protect people and the business, stabilize the situation, recover critical services according to approved priorities, manage risk, meet regulatory obligations, and provide executive assurance.**

The overall process is:

**Disaster → Detection → Assessment → Declaration → Crisis Governance → Containment → Continuity → Recovery → Validation → Restoration → Lessons Learned**

---

# Case Study: GlobalConnect Telecom

GlobalConnect Telecom operates:

* Mobile telecommunications
* Broadband
* Enterprise connectivity
* Cloud services
* Digital customer platforms
* Billing
* Customer support

The organization has:

* Multiple data centers
* Hybrid cloud infrastructure
* 24/7 Network Operations Center
* 24/7 Security Operations Center
* Disaster recovery environments
* Critical third-party suppliers

The organization has previously completed its BIA and continuity strategy.

Its most important recovery requirements include:

| Service          | MTPD | RTO | RPO |
| ---------------- | ---: | --: | --: |
| Mobile Network   |   2h | 30m | 15m |
| Authentication   |   4h |  1h | 15m |
| Customer Portal  |  12h |  4h |  1h |
| Customer Billing |  24h |  8h |  1h |
| Customer Support |  12h |  4h |  1h |

---

# 1. The Disaster

At 02:17 on Monday morning, the Network Operations Center detects abnormal behavior in the primary data center.

Multiple systems begin reporting:

* Storage failures
* Database errors
* Authentication failures
* Application outages
* Network instability

Within 10 minutes:

**Customer authentication begins failing.**

At 02:31:

**Customer-facing applications become unavailable.**

At 02:40:

**Billing services begin experiencing database corruption.**

At 02:45:

The SOC discovers indicators suggesting that the event may involve malicious activity.

The situation is now classified as a potential:

> **Major IT and cybersecurity disaster.**

---

# 2. Initial Response

The first objective is **stabilization**, not immediate recovery.

The organization activates:

* IT Incident Management
* Cybersecurity Incident Response
* Business Continuity Management
* Disaster Recovery
* Crisis Management

The incident commander establishes command and control.

---

# 3. Incident Classification

The organization uses severity levels.

### Severity 1

Critical enterprise impact.

Examples:

* Major customer outage
* Core network failure
* Ransomware
* Major data loss

### Severity 2

Significant business impact.

### Severity 3

Limited business impact.

### Severity 4

Minor operational issue.

The current incident is classified:

**Severity 1 – Critical**

because multiple critical services are affected.

---

# 4. Incident Commander

One person must coordinate the response.

The Incident Commander is responsible for:

* Situation awareness
* Response coordination
* Decision-making
* Escalation
* Resource allocation
* Recovery coordination

Without centralized command, multiple teams may make conflicting decisions.

---

# 5. Establish the Incident Management Structure

GlobalConnect establishes:

### Incident Commander

Overall operational command.

### Cybersecurity Lead

Investigates the suspected cyberattack.

### IT Recovery Lead

Coordinates technical recovery.

### Business Continuity Lead

Coordinates business continuity.

### Communications Lead

Manages internal and external communications.

### Legal/Privacy Lead

Assesses legal and regulatory requirements.

### Executive Liaison

Provides executive updates.

---

# 6. Separate Incident Response From Crisis Governance

This distinction is important.

### Technical Incident Team

Answers:

> What happened technically?

### Crisis Management Team

Answers:

> What does the organization need to do strategically?

For example:

Technical team:

> "The database cluster is corrupted."

Executives need to know:

> "Customer billing is unavailable, approximately 6 million customers may be affected, and recovery is expected within six hours."

GRC helps translate technical information into business information.

---

# 7. Establish a Common Operating Picture

The crisis team establishes a centralized situation report.

Example:

**Incident:** Major IT outage

**Start:** 02:17

**Affected services:**

* Authentication
* Customer portal
* Billing

**Potential cause:**

Cybersecurity event under investigation.

**Customers affected:**

Approximately 6 million.

**Current status:**

Containment underway.

**Estimated RTO exposure:**

Authentication approaching one-hour RTO.

This becomes the basis for executive decisions.

---

# 8. Protect Life and Safety First

Although this is primarily an IT disaster, the organization first confirms:

* Employee safety
* Facility safety
* Physical security
* Emergency services requirements

For telecommunications organizations, technology failure can potentially affect:

* Emergency communications
* Critical infrastructure
* Hospitals
* Government services

Therefore, business continuity decisions may have safety implications.

---

# 9. Stabilize the Environment

The technical team determines whether systems should remain online.

If compromise is suspected, the organization may:

* Isolate affected systems
* Disable compromised accounts
* Block malicious traffic
* Disconnect affected networks
* Freeze changes
* Protect backup systems

The goal is:

> **Prevent further damage.**

---

# 10. Do Not Destroy Evidence

A common mistake during major incidents is immediately rebuilding everything.

If malicious activity is suspected, evidence may be required for:

* Root cause analysis
* Legal proceedings
* Regulatory investigations
* Insurance
* Internal investigations

Therefore, evidence preservation must be coordinated with:

* Cybersecurity
* Legal
* Forensics
* Privacy
* Compliance

---

# 11. Protect Backups

Because the incident may involve ransomware or destructive malware, the organization immediately protects:

* Backup infrastructure
* Backup credentials
* Recovery servers
* Immutable backups
* Offline backups

The recovery environment must not be contaminated by the incident.

---

# 12. Activate the Business Continuity Plan

Technical recovery alone is insufficient.

The organization activates business continuity measures.

### Customer Support

Move staff to remote operations.

### Billing

Implement temporary manual processing.

### Enterprise Customers

Establish priority support channels.

### Communications

Activate crisis communications.

This allows the business to continue while IT recovery occurs.

---

# 13. Prioritize Recovery

The recovery order is based on the BIA.

GlobalConnect's recovery sequence is:

**1. Network**

↓

**2. Authentication**

↓

**3. Core Data Platforms**

↓

**4. Customer Portal**

↓

**5. Billing**

↓

**6. Enterprise Services**

↓

**7. Internal Corporate Systems**

The organization does not simply restore systems based on technical convenience.

---

# 14. Dependency-Aware Recovery

Suppose the customer portal depends on:

* Identity
* Network
* Database

The portal cannot be safely recovered before these dependencies.

Therefore:

**Network**

→

**Identity**

→

**Database**

→

**Customer Portal**

This is why dependency mapping performed during the BIA is so important.

---

# 15. Recovery Decision Point

At 03:15, the technical team determines that the primary environment cannot be trusted.

The Incident Commander asks:

> "Do we repair the primary environment or fail over to the recovery environment?"

The decision considers:

* RTO
* RPO
* Data integrity
* Cybersecurity risk
* Recovery readiness
* Business impact

The team decides:

**Fail over critical services to the secondary environment.**

---

# 16. Disaster Recovery Activation

The DR plan is formally activated.

The recovery team begins:

1. Validate recovery environment.
2. Confirm clean infrastructure.
3. Validate backup integrity.
4. Restore identity.
5. Restore network dependencies.
6. Restore critical databases.
7. Restore applications.
8. Conduct security validation.
9. Begin controlled customer recovery.

---

# 17. Recovery Environment Validation

The organization does not immediately route customers to the recovery environment.

First it validates:

* Operating system integrity
* Application integrity
* Database consistency
* Network configuration
* Identity controls
* Security monitoring
* Malware status

This prevents the organization from recovering into another compromised environment.

---

# 18. Backup Validation

The team identifies several recovery points.

| Backup   |    Age | Integrity | Status    |
| -------- | -----: | --------- | --------- |
| Backup A | 15 min | Failed    | Reject    |
| Backup B |     1h | Valid     | Candidate |
| Backup C |     6h | Valid     | Candidate |
| Backup D |    24h | Valid     | Candidate |

The team selects:

**Backup B**

because it is the most recent validated clean recovery point.

This produces an estimated data loss of approximately:

**1 hour**

which meets the approved billing RPO.

---

# 19. Recovery Point Decision

Suppose the most recent backup is corrupted.

The team must choose between:

### Option A

Use the latest corrupted backup.

### Option B

Use an older clean backup.

The organization chooses:

**Option B**

because:

> **Data integrity is more important than recovering from a corrupted backup.**

This demonstrates the relationship between cybersecurity and disaster recovery.

---

# 20. Authentication Recovery

Authentication has:

**RTO = 1 hour**

At 03:25:

Secondary authentication environment is activated.

At 03:42:

Internal validation completed.

At 03:50:

Controlled customer traffic begins.

At 04:05:

Authentication reaches approximately 80% capacity.

The organization has successfully recovered the service within the required RTO.

---

# 21. Customer Portal Recovery

The portal depends on:

* Network
* Identity
* Database

After dependencies are validated:

At 04:30:

Application recovery begins.

At 05:15:

Technical validation completes.

At 05:30:

Limited customer access is restored.

At 06:00:

Full service restored.

RTO requirement:

**4 hours**

Actual recovery:

Approximately **3 hours 43 minutes**

Result:

**RTO achieved.**

---

# 22. Billing Recovery

Billing is more complicated because the database was corrupted.

The organization restores:

* Customer data
* Usage data
* Billing configuration
* Payment information
* Invoice history

Data reconciliation is performed before billing is reopened.

The recovery team identifies:

* 1.2 million records requiring reconciliation
* 47,000 duplicate transactions
* 3,200 incomplete records

These are corrected before full billing restoration.

---

# 23. Manual Business Workaround

Because billing recovery is still underway, Finance activates a manual workaround.

Customer-service teams can:

* Verify account status
* Record payments
* Issue temporary adjustments
* Defer non-critical billing actions

This allows the business to operate while the underlying system is restored.

---

# 24. Customer Prioritization

Not all customers are treated equally during a major outage.

Priority may be given to:

1. Emergency services
2. Critical infrastructure
3. Hospitals
4. Government services
5. Enterprise critical customers
6. General consumers

This prioritization should be defined in advance rather than invented during the crisis.

---

# 25. Third-Party Coordination

The incident also affects a cloud provider.

GlobalConnect immediately activates its supplier escalation process.

The supplier provides:

* Technical support
* Incident information
* Recovery status
* Security information
* Estimated restoration time

The supplier's contractual SLA becomes relevant.

---

# 26. Executive Communication

The CEO does not need thousands of technical details.

The executive update states:

> **"A major IT incident has affected authentication, customer portal, and billing. Approximately 6 million customers may be affected. The primary environment has been isolated. Critical services are being recovered through the secondary environment. Authentication is restored and customer portal recovery is progressing. Billing recovery remains in progress. No regulatory notification decision has been finalized at this time."**

This is useful executive communication.

---

# 27. Executive Situation Report

A standard executive report may contain:

| Item                        | Status                  |
| --------------------------- | ----------------------- |
| Incident Severity           | Critical                |
| Customer Impact             | 6M potentially affected |
| Network                     | Operational             |
| Authentication              | Restored                |
| Customer Portal             | Restored                |
| Billing                     | Recovery                |
| Cybersecurity Investigation | Ongoing                 |
| Data Integrity              | Under validation        |
| Regulatory Assessment       | In progress             |
| Estimated Full Recovery     | 09:00                   |
| Executive Decision Required | None currently          |

This gives leadership a clear picture.

---

# 28. Regulatory Assessment

The legal/privacy team evaluates:

* Whether personal data was affected
* Whether confidentiality was compromised
* Whether integrity was compromised
* Whether availability obligations were breached
* Whether contractual reporting is required
* Whether regulators must be notified

The organization does not wait until the end of the incident to begin this assessment.

---

# 29. Customer Communications

Customer communication should be:

* Accurate
* Timely
* Consistent
* Transparent
* Approved

The organization avoids making unsupported statements such as:

> "No data was compromised."

if the investigation is still ongoing.

Instead:

> "We are investigating the incident and assessing whether customer data was affected."

This reduces legal and reputational risk.

---

# 30. Cybersecurity and Disaster Recovery Integration

A cyber-induced disaster is different from a traditional infrastructure failure.

Traditional disaster:

**Server fails**

↓

**Restore backup**

Cyber disaster:

**Attack**

↓

**Compromise**

↓

**Contain**

↓

**Eradicate**

↓

**Validate**

↓

**Restore clean environment**

Therefore:

> **Cyber recovery requires security validation before business restoration.**

---

# 31. Recovery Validation

After systems are restored, the organization validates:

### Availability

Is the service working?

### Integrity

Is the data accurate?

### Confidentiality

Are access controls functioning?

### Security

Has the threat been removed?

### Performance

Can the system handle expected demand?

### Monitoring

Are alerts functioning?

Only after validation does the organization declare the service operational.

---

# 32. Controlled Service Restoration

GlobalConnect avoids immediately returning 100% of traffic.

Instead:

**10% traffic**

↓

**25%**

↓

**50%**

↓

**75%**

↓

**100%**

At each stage:

* Monitor
* Validate
* Check performance
* Check security
* Check errors

This reduces the risk of a second failure.

---

# 33. Avoiding a Secondary Disaster

Suppose the recovery environment can handle:

**70% capacity**

but normal customer demand is:

**100%**

If the organization restores all traffic immediately:

**Recovery environment → overload → second outage**

Therefore, controlled restoration is essential.

---

# 34. Return to Normal Operations

Disaster recovery is not complete when the system comes online.

The organization must determine:

> Is the primary environment safe to return to?

Possible approaches include:

### Option 1

Fail back to the original environment.

### Option 2

Continue operating from the secondary environment.

### Option 3

Rebuild the primary environment from clean infrastructure.

For a cyberattack, rebuilding may be safer than simply failing back.

---

# 35. Failback Decision

GlobalConnect decides:

**Do not immediately fail back.**

Instead:

1. Investigate the primary environment.
2. Rebuild compromised infrastructure.
3. Patch vulnerabilities.
4. Validate configurations.
5. Conduct security testing.
6. Restore clean data.
7. Test internally.
8. Perform controlled failback.

This reduces the risk of reinfection.

---

# 36. Incident Closure Criteria

The incident should not be closed merely because:

> "The website is back."

Closure requires:

* Critical services restored
* Security investigation sufficiently advanced
* Data integrity confirmed
* Regulatory assessment completed
* Customer impact assessed
* Temporary workarounds removed
* Residual risks documented
* Executive owner identified
* Corrective actions created

---

# 37. Business Impact Assessment After the Incident

The organization calculates actual impact.

Example:

### Customers affected

6 million

### Service interruption

3–8 hours depending on service

### Estimated revenue impact

€3M–€5M

### SLA credits

€1.2M

### Recovery cost

€2M

### Regulatory exposure

Under assessment

### Reputational impact

Significant

This information feeds into enterprise risk management.

---

# 38. Root Cause Analysis

After stabilization, the organization performs root cause analysis.

Potential findings:

### Technical Cause

Storage corruption.

### Contributing Cause

Insufficient redundancy.

### Cybersecurity Cause

Compromised administrative credentials.

### Governance Cause

Privileged-access review was overdue.

### Process Cause

Recovery procedures were not updated after a cloud migration.

This demonstrates that major incidents often have multiple causes.

---

# 39. Control Failure Analysis

GRC asks:

> Which controls should have prevented or reduced the incident?

Examples:

* Privileged access management
* MFA
* Network segmentation
* Backup protection
* Vulnerability management
* Monitoring
* Change management
* Supplier management
* DR testing

The purpose is not simply to identify who made a mistake.

The purpose is:

> **Identify systemic control weaknesses.**

---

# 40. Risk Register Update

The incident generates new or revised risks.

Example:

### Risk

Critical authentication infrastructure lacks sufficient geographic resilience.

### Likelihood

Medium

### Impact

Very High

### Risk Rating

High

### Treatment

Implement active-active architecture.

### Owner

CISO

### Target Date

6 months

The incident therefore becomes an enterprise risk-management input.

---

# 41. Corrective Action Plan

Example:

| Finding                    | Action                       | Owner       | Due      |
| -------------------------- | ---------------------------- | ----------- | -------- |
| Insufficient redundancy    | Add secondary region         | CTO         | 6 months |
| Backup corruption          | Implement immutable backups  | CIO         | 3 months |
| Privileged access weakness | Strengthen PAM               | CISO        | 2 months |
| Outdated DR plan           | Update DR documentation      | BCM         | 1 month  |
| Supplier dependency        | Establish alternate supplier | Procurement | 9 months |

---

# 42. Lessons-Learned Workshop

The organization asks:

### What worked?

* Crisis management structure
* Secondary authentication
* Remote workforce
* Executive escalation

### What failed?

* Backup validation
* Documentation
* Supplier escalation
* Recovery communications

### What needs improvement?

* Cyber recovery
* Dependency mapping
* Privileged access
* DR testing

This creates a structured improvement program.

---

# 43. Disaster Recovery Test Gap

One important discovery is that the organization had tested:

**Technical application recovery**

but had not tested:

**End-to-end business recovery.**

This is a common weakness.

A system may recover successfully while the business process remains unavailable because:

* People are unavailable
* Interfaces are broken
* Suppliers are unavailable
* Data reconciliation fails
* Manual procedures are missing

Therefore:

> **Technical recovery does not automatically equal business recovery.**

---

# 44. Update the BIA

The incident may reveal that previous assumptions were wrong.

For example:

Before the incident:

Billing MTPD:

**24 hours**

After the incident:

Finance determines that:

**12 hours**

is actually the maximum tolerable period.

The BIA should therefore be updated.

This demonstrates that:

**Incident → Lessons Learned → BIA Improvement**

---

# 45. Update the Business Continuity Strategy

The continuity strategy is also updated.

New requirements may include:

* Stronger backup isolation
* More remote-working capacity
* Alternate payment provider
* Improved communications
* Enhanced supplier resilience

Thus:

**Incident → Strategy Improvement**

---

# 46. Update the Disaster Recovery Strategy

The DR program may be changed to include:

* More frequent recovery testing
* Clean-room recovery
* Cyber recovery vault
* Automated failover
* Improved dependency mapping
* Security validation before recovery

The objective is not merely to repeat the old recovery process.

---

# 47. Update the Crisis Management Plan

The organization may discover that:

* Escalation was too slow
* Executive roles were unclear
* Communication approvals took too long
* Regulatory decision-making was unclear

The crisis plan is therefore revised.

---

# 48. Evidence and Audit Trail

GRC maintains evidence such as:

* Incident timeline
* Decision logs
* Recovery records
* Communications
* Approval records
* Backup validation
* Recovery test results
* Root cause analysis
* Risk register updates
* Corrective actions

This evidence supports:

* Internal audit
* External audit
* Regulatory review
* Insurance claims
* Management assurance

---

# 49. Executive Lessons

The CEO ultimately wants to know:

### 1. What happened?

Major IT/cybersecurity disaster.

### 2. What was affected?

Authentication, portal, billing.

### 3. How many customers?

Approximately 6 million.

### 4. How long?

3–8 hours depending on service.

### 5. Did we meet RTO?

Most critical services did.

### 6. What failed?

Primary infrastructure and several supporting controls.

### 7. What is the risk now?

Residual resilience and cybersecurity risks remain.

### 8. What are we doing?

Implementing corrective actions.

### 9. How much will it cost?

Approximately €X million.

### 10. How do we prevent recurrence?

Technology, cybersecurity, supplier, and governance improvements.

---

# 50. Executive Disaster Dashboard

A mature organization may maintain:

| Metric                                 |  Result |
| -------------------------------------- | ------: |
| Critical services affected             |       3 |
| Customers affected                     |      6M |
| Critical services recovered within RTO |     2/3 |
| Data loss within RPO                   |     Yes |
| Critical suppliers affected            |       1 |
| Regulatory assessment                  | Ongoing |
| High-risk findings                     |       7 |
| Corrective actions                     |      12 |
| Estimated recovery cost                |     €2M |
| Residual risk                          |    High |

This turns a technical disaster into a governance decision.

---

# 51. GRC Role During an IT Disaster

The GRC professional does **not** replace the technical incident-response team.

Instead, GRC provides:

### Governance

Who has authority to decide?

### Risk

What risks are being accepted?

### Compliance

What obligations apply?

### Business Impact

Which services have priority?

### Evidence

Can decisions and actions be demonstrated?

### Executive Reporting

What does leadership need to know?

### Assurance

Did recovery meet approved requirements?

---

# 52. Three Lines Perspective

The incident can also be viewed through the Three Lines Model.

### First Line

IT and business operations:

* Respond
* Recover
* Correct

### Second Line

GRC/Risk/Compliance:

* Challenge
* Monitor
* Coordinate
* Assess risk

### Third Line

Internal Audit:

* Independently evaluate response and controls

This prevents operational response and independent assurance from being confused.

---

# 53. Common IT Disaster Response Failures

### Failure 1

No clear Incident Commander.

### Failure 2

Teams start recovering systems independently.

### Failure 3

Backups are not protected from ransomware.

### Failure 4

Recovery begins before containment.

### Failure 5

Evidence is destroyed.

### Failure 6

Executives receive excessive technical detail.

### Failure 7

Customer communication is delayed.

### Failure 8

Regulatory obligations are assessed too late.

### Failure 9

Recovery priorities are not based on the BIA.

### Failure 10

Systems are restored but business processes remain unavailable.

### Failure 11

Organizations fail to validate restored data.

### Failure 12

They close the incident without addressing root causes.

---

# 54. Practical GRC Exercise

Assume you are the **GRC Manager** supporting GlobalConnect during a major IT disaster.

At 08:00:

* Mobile network is operational.
* Authentication is operational.
* Customer portal is operational.
* Billing is still unavailable.
* Approximately 6 million customers were affected.
* One critical supplier is also experiencing an outage.
* Cybersecurity investigation is ongoing.
* Regulators may require notification.

Prepare an executive situation report containing:

### Incident Status

* Severity
* Current impact
* Affected services

### Risk

* Current risks
* Emerging risks
* Residual risks

### Recovery

* Services recovered
* Services outstanding
* RTO performance
* RPO performance

### Compliance

* Potential reporting obligations
* Privacy considerations
* Contractual obligations

### Business Continuity

* Manual workarounds
* Alternate suppliers
* Staffing

### Executive Decisions

Identify three decisions management may need to make.

---

# 55. Incident Timeline Exercise

Construct a timeline:

| Time  | Event                         | Decision                   | Owner   |
| ----- | ----------------------------- | -------------------------- | ------- |
| 02:17 | Initial detection             | Investigate                | NOC     |
| 02:45 | Cyber indicators discovered   | Escalate                   | SOC     |
| 03:00 | Major incident declared       | Activate crisis management | IC      |
| 03:15 | Primary environment untrusted | Activate DR                | CIO     |
| 03:25 | Backup selected               | Restore                    | DR Lead |
| 03:50 | Authentication restored       | Controlled traffic         | CTO     |
| 05:30 | Portal restored               | Validate                   | CDO     |
| 08:00 | Billing recovery ongoing      | Executive review           | CFO     |

The timeline becomes important evidence for post-incident analysis.

---

# 56. Final IT Disaster Response Model

A mature response follows:

**Detect**

↓

**Classify**

↓

**Escalate**

↓

**Establish Command**

↓

**Assess Business Impact**

↓

**Contain**

↓

**Protect People and Data**

↓

**Activate Continuity**

↓

**Prioritize Recovery**

↓

**Validate Recovery Environment**

↓

**Restore Critical Services**

↓

**Validate Security and Data**

↓

**Controlled Service Restoration**

↓

**Return to Normal**

↓

**Root Cause Analysis**

↓

**Corrective Action**

↓

**Risk Register Update**

↓

**Test Improvements**

↓

**Continual Improvement**

---

# 57. Key GRC Lesson

The most important lesson from a major IT disaster is:

> **Disaster recovery is not simply an IT restoration exercise. It is an enterprise risk and resilience decision.**

The technical team answers:

> **"How do we restore the system?"**

Business continuity answers:

> **"How do we keep operating while the system is unavailable?"**

Cybersecurity answers:

> **"Is the environment safe to recover?"**

GRC answers:

> **"Are we recovering according to approved risk, business, regulatory, and governance requirements?"**

Executives answer:

> **"What level of risk, cost, customer impact, and operational disruption are we willing to accept?"**

A mature organization brings all five together:

**IT Recovery + Cybersecurity + Business Continuity + GRC + Executive Governance**

That is what turns a disaster-response process into a genuine **organizational resilience capability**.



