# Lesson 7.8 – Improvement: Nonconformity and Corrective Action

> **Chapter:** 07 – ISO/IEC 42001 Artificial Intelligence Management System (AIMS)
> **Lesson:** 7.8
> **Part:** 1 of 4
> **Difficulty:** Intermediate
> **Estimated Reading Time:** 10–15 minutes
> **Prerequisites:** Lesson 7.7 – Performance Evaluation

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of Clause 10 – Improvement.
- Explain the concepts of nonconformity and corrective action.
- Learn how organizations investigate AI governance issues.
- Understand root cause analysis within an Artificial Intelligence Management System (AIMS).
- Recognize how corrective actions support continual improvement.

---

# Introduction

No Artificial Intelligence Management System is perfect. Even mature organizations experience governance failures, operational incidents, audit findings, regulatory observations, security events, or process weaknesses. What distinguishes a mature organization is not the absence of problems, but how effectively those problems are identified, investigated, corrected, and prevented from recurring.

Clause 10 of ISO/IEC 42001 focuses on improvement. It requires organizations to respond to nonconformities, determine their root causes, implement corrective actions, verify effectiveness, and continually improve the Artificial Intelligence Management System.

Rather than assigning blame, Clause 10 promotes organizational learning by ensuring that weaknesses become opportunities for strengthening governance.

---

# Purpose of Clause 10

Clause 10 ensures that organizations:

- Identify governance weaknesses.
- Respond appropriately to nonconformities.
- Correct identified problems.
- Prevent recurrence.
- Improve governance effectiveness.
- Strengthen operational resilience.
- Support continual improvement.

Improvement is a continuous activity throughout the lifecycle of the Artificial Intelligence Management System.

---

# What is a Nonconformity?

A **nonconformity** is the failure to meet a requirement.

Requirements may originate from:

- ISO/IEC 42001.
- Organizational AI policies.
- Internal procedures.
- Regulatory obligations.
- Contractual commitments.
- Approved governance processes.

A nonconformity indicates that expected governance controls have not been fully implemented or maintained.

---

# Examples of AI Nonconformities

Common examples include:

### Governance

- Missing AI policy approval.
- Undefined governance responsibilities.
- Incomplete AI inventory.

---

### Risk Management

- AI risk assessment not completed.
- Risk treatment plans not implemented.
- High-risk AI systems operating without approval.

---

### AI Lifecycle

- Missing validation before deployment.
- Inadequate testing.
- Undocumented model updates.

---

### Operational Controls

- Human oversight not performed.
- Monitoring activities incomplete.
- Incident response procedures not followed.

---

### Documentation

- Missing records.
- Outdated procedures.
- Uncontrolled document versions.

Nonconformities may range from minor administrative issues to significant governance failures.

---

# Sources of Nonconformities

Organizations identify nonconformities through various activities.

Examples include:

- Internal audits.
- External certification audits.
- Operational monitoring.
- AI incidents.
- Customer complaints.
- Employee observations.
- Regulatory inspections.
- Security investigations.
- Management reviews.

Every source contributes valuable information for improving governance.

---

# Responding to a Nonconformity

When a nonconformity is identified, organizations should respond promptly.

A structured response generally includes:

```
Identify Nonconformity

↓

Contain the Problem

↓

Assess Impact

↓

Investigate Root Cause

↓

Develop Corrective Action

↓

Implement Improvements

↓

Verify Effectiveness

↓

Close the Action
```

Prompt action reduces operational, legal, financial, and reputational risks.

---

# Immediate Correction vs Corrective Action

These terms are often confused but have different meanings.

### Immediate Correction

Addresses the current issue.

Example:

A missing AI risk assessment is completed immediately.

---

### Corrective Action

Addresses the underlying cause to prevent recurrence.

Example:

The project approval process is revised so that deployment cannot proceed until a documented AI risk assessment has been completed and approved.

Correction fixes today's problem.

Corrective action prevents tomorrow's problem.

---

# Root Cause Analysis

Corrective actions should address the underlying cause rather than symptoms.

Organizations commonly use techniques such as:

### Five Whys

Repeatedly ask **"Why?"** until the underlying cause is identified.

Example:

AI validation was missed.

↓

Why?

The approval process was bypassed.

↓

Why?

Approval responsibilities were unclear.

↓

Why?

Governance procedures were outdated.

↓

Root Cause:

Governance documentation had not been updated after organizational restructuring.

---

### Fishbone (Cause-and-Effect) Analysis

Potential causes may be grouped into categories such as:

- People.
- Process.
- Technology.
- Data.
- Governance.
- Environment.

Structured analysis helps organizations identify systemic issues rather than isolated failures.

---

# Evaluating Impact

Before implementing corrective actions, organizations should determine:

- Business impact.
- Customer impact.
- Regulatory impact.
- Financial impact.
- Security implications.
- Privacy implications.
- Reputational consequences.

Understanding impact helps prioritize response efforts and allocate appropriate resources.

---

📊 **Diagram Placeholder**

**Title:** Nonconformity and Corrective Action Process

**Diagram Description:**

Create a flow diagram.

Nonconformity Detected

↓

Immediate Correction

↓

Root Cause Analysis

↓

Corrective Action Plan

↓

Implementation

↓

Effectiveness Verification

↓

Closure

↓

Continual Improvement

Caption:

*"Effective corrective action eliminates the root cause of nonconformities, strengthens governance processes, and supports continual improvement of the Artificial Intelligence Management System."*

---

# Best Practices

Organizations should:

- Establish formal procedures for identifying, documenting, investigating, and resolving nonconformities across the Artificial Intelligence Management System.
- Respond promptly to governance issues while prioritizing actions according to business impact, AI risk, regulatory obligations, and stakeholder concerns.
- Distinguish clearly between immediate corrections that resolve the current issue and corrective actions that eliminate the underlying root cause.
- Perform structured root cause analyses using recognized techniques such as the Five Whys, Fishbone Diagram, or equivalent methodologies appropriate to organizational complexity.
- Evaluate the operational, legal, security, privacy, financial, and reputational impact of each nonconformity before determining corrective actions.
- Assign clear ownership, implementation timelines, and success criteria for every corrective action to ensure accountability and effective execution.
- Maintain complete records of nonconformities, investigations, root cause analyses, corrective actions, verification activities, and closure decisions.
- Use lessons learned from nonconformities to strengthen governance processes, improve operational controls, and reduce the likelihood of recurrence.

These practices enable organizations to transform operational issues into opportunities for learning, governance maturity, and continual improvement within the Artificial Intelligence Management System.

---

# Practical Example

A multinational healthcare provider deploys an Artificial Intelligence system that assists clinicians in prioritizing diagnostic imaging cases. During an internal audit, auditors discover that a recently updated AI model was placed into production before the required independent validation and fairness assessment had been completed. The organization immediately pauses further model updates, performs the missing validation activities, documents the issue as a nonconformity, and assesses the potential clinical, regulatory, and operational impacts. Fortunately, no patient harm is identified, but the incident exposes weaknesses in the deployment approval process.

A root cause analysis using the Five Whys reveals that recent organizational restructuring resulted in unclear approval responsibilities between the AI engineering team and the clinical governance committee. Management updates governance procedures, revises approval workflows, implements automated deployment gates within the DevSecOps pipeline, and provides additional training to project managers and AI developers. Follow-up reviews confirm that all future AI deployments include mandatory validation and governance approvals before production release. The corrective action not only resolves the immediate issue but also strengthens the organization's overall Artificial Intelligence Management System and reduces the likelihood of similar governance failures occurring again.

