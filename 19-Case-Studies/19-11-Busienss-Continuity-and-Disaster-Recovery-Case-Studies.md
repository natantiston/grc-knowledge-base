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


