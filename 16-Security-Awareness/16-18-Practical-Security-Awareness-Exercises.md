# Lesson 16.18 – Practical Security Awareness Exercises

> **Chapter:** 16 – Security Awareness
>
> **Topic:** Phishing Simulation Exercise
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes

## Introduction

Security awareness training is most effective when employees have an opportunity to **practice security behaviors**, not simply read policies or watch training videos.

A phishing simulation exercise is one of the most practical ways to test whether employees can recognize and appropriately respond to a suspicious message.

The purpose is not to trick or punish employees.

> **The purpose of a phishing simulation is to measure and improve an organization's ability to detect, report, and respond to phishing attempts.**

A mature program uses simulations as a controlled learning and measurement mechanism.

---

# What Is a Phishing Simulation?

A phishing simulation is a controlled exercise in which an organization sends simulated phishing messages to selected employees.

The simulated message may resemble a real attack, such as:

* Fake password-reset notifications.
* Fake Microsoft 365 alerts.
* Fake invoice requests.
* Fake HR communications.
* Fake delivery notifications.
* Fake executive requests.
* Fake account-verification messages.

The simulation is designed to test employee behavior without causing actual harm.

---

# Example

An employee receives:

> **Subject: Your account requires verification**

The message appears to come from an internal IT department.

It asks the employee to:

1. Click a link.
2. Sign in.
3. Verify their account.

The link leads to a controlled simulation page rather than a real credential-harvesting site.

The exercise records whether the employee:

* Opened the message.
* Clicked the link.
* Submitted information.
* Reported the message.
* Ignored it.

The organization can then analyze the results.

---

# Why Phishing Simulations Matter

Traditional training can measure:

> **What employees know.**

Phishing simulations can measure:

> **What employees actually do.**

There can be a significant difference.

An employee may correctly answer:

> "Never click suspicious links."

but still click a convincing simulated phishing email.

This is why practical exercises are valuable.

---

# Objectives of a Phishing Simulation

A simulation may have several objectives.

### 1. Measure Awareness

Determine whether employees recognize phishing indicators.

### 2. Measure Behavior

Observe how employees respond to suspicious messages.

### 3. Improve Reporting

Encourage employees to report suspected phishing.

### 4. Identify High-Risk Groups

Determine which populations may need additional support.

### 5. Test Processes

Evaluate whether employees know how to report suspicious activity.

### 6. Improve Training

Use results to improve future awareness content.

---

# Phishing Simulation vs. Real Phishing

A simulation should be clearly controlled.

| Phishing Attack                | Phishing Simulation                 |
| ------------------------------ | ----------------------------------- |
| Malicious                      | Controlled                          |
| Unauthorized                   | Authorized                          |
| Intended to compromise         | Intended to educate                 |
| Real credentials may be stolen | Credentials should not be collected |
| Attacker benefits              | Organization learns                 |
| Can cause damage               | Designed to minimize harm           |

The simulation must remain within the organization's approved scope.

---

# Authorization Is Essential

Phishing simulations should never be conducted without proper authorization.

Approval may involve:

* CISO.
* Security leadership.
* GRC.
* Legal.
* Privacy.
* HR.
* Communications.
* Business leadership.

This is especially important because simulations involve employee behavior and potentially personal data.

---

# Define the Scope

Before launching the exercise, define:

* Target population.
* Departments.
* Locations.
* Number of users.
* Simulation duration.
* Types of scenarios.
* Data collected.
* Reporting method.
* Success criteria.

For example:

> "The simulation will cover 2,000 employees in Finance, HR, and Operations over a two-week period."

This creates a clearly controlled exercise.

---

# Establish Rules of Engagement

The exercise should define what is allowed and prohibited.

For example:

### Allowed

* Simulated phishing emails.
* Controlled landing pages.
* Tracking clicks.
* Tracking reports.
* Measuring response time.

### Prohibited

* Collecting real passwords.
* Installing malware.
* Exploiting vulnerabilities.
* Disrupting business operations.
* Sending deceptive messages outside the approved scope.

The rules protect both the organization and its employees.

---

# Protect Employee Credentials

A fundamental rule is:

> **Never collect real employee passwords during a phishing simulation.**

If the simulation includes a fake login page, the page should be designed so that entering any value triggers the simulation without storing actual credentials.

For example:

Employee enters:

**Username:** [test@example.com](mailto:test@example.com)

**Password:** anything

The system records:

> "Credential submission attempted"

but does not store the password.

---

# Privacy Considerations

Phishing simulations may generate personal or employee-related data.

Possible information includes:

* Employee identity.
* Department.
* Location.
* Click behavior.
* Reporting behavior.
* Training history.

The organization should define:

* What data is collected.
* Why it is collected.
* Who can access it.
* How long it is retained.
* How it is reported.

Privacy should be considered before the simulation begins.

---

# Avoid Public Shaming

A mature awareness program should not publicly identify employees who fail simulations.

For example, avoid publishing:

> "John from Finance clicked the phishing email."

Instead, report aggregated results:

> "Finance had a 12% click rate during the simulation."

Individual results may be available to authorized personnel when necessary for targeted intervention.

---

# Selecting the Scenario

The simulation should reflect realistic threats.

Possible scenarios include:

### Credential Phishing

Fake account verification.

### Business Email Compromise

Fake executive request.

### Invoice Fraud

Fake supplier invoice.

### HR Phishing

Fake payroll or benefits notification.

### Cloud Phishing

Fake Microsoft 365 or Google Workspace notification.

### Delivery Phishing

Fake shipping notification.

The scenario should be appropriate for the target audience.

---

# Role-Based Simulations

Different employees face different threats.

For example:

### Finance

Fake payment request.

### HR

Fake employee information request.

### IT

Fake administrator notification.

### Executives

Executive impersonation.

### Developers

Fake repository or developer-platform notification.

This provides much more meaningful testing than sending everyone the same email.

---

# Establish a Baseline

Before measuring improvement, establish a baseline.

For example:

**Initial simulation**

* 15% clicked.
* 5% submitted information.
* 40% reported the email.

These results become the starting point.

Future simulations can then measure improvement.

---

# Key Metrics

Important metrics include:

### Click Rate

Percentage of recipients who clicked the simulated link.

**Click Rate =**

**Number of users who clicked ÷ Number of recipients × 100**

---

### Submission Rate

Percentage who attempted to submit information.

This can be particularly useful because clicking does not necessarily mean the employee would have provided credentials.

---

### Reporting Rate

Percentage of users who reported the simulation.

This is an important positive behavioral indicator.

---

### Report-to-Click Ratio

Measures whether users who interact with a suspicious email subsequently report it.

---

### Time to Report

Measures how quickly employees identify and report suspicious messages.

Fast reporting can help security teams respond to real attacks.

---

# Example Metrics

Suppose:

**5,000 employees** receive the simulation.

Results:

* 500 clicked.
* 100 attempted credential submission.
* 2,000 reported the message.

Therefore:

**Click rate = 10%**

**Submission rate = 2%**

**Reporting rate = 40%**

The organization now has measurable behavioral data.

---

# Measuring Improvement

Suppose the organization runs three simulations.

| Campaign   | Click Rate | Reporting Rate |
| ---------- | ---------: | -------------: |
| Baseline   |        15% |            40% |
| Campaign 2 |        10% |            55% |
| Campaign 3 |         6% |            72% |

This indicates improvement in both:

* Reduced risky behavior.
* Increased positive behavior.

This is more meaningful than simply measuring training completion.

---

# Difficulty Levels

Simulations can gradually increase in sophistication.

### Beginner

Obvious phishing indicators.

### Intermediate

More realistic branding and language.

### Advanced

Highly convincing business scenarios.

However, increasing difficulty should not become a contest to deceive employees.

The objective remains risk reduction.

---

# Simulation Frequency

There is no universal requirement that every organization run simulations at a particular frequency.

Frequency should depend on:

* Risk.
* Organization size.
* Threat environment.
* Employee population.
* Program maturity.
* Regulatory requirements.

Some organizations may conduct simulations quarterly, while high-risk populations may receive more frequent targeted exercises.

---

# Avoiding Excessive Simulations

Too many simulations can create:

* Awareness fatigue.
* Employee frustration.
* Reduced trust.
* Simulation recognition.
* Excessive administrative workload.

The goal is:

> **Enough testing to produce meaningful behavioral data without creating unnecessary disruption.**

---

# Communication Strategy

Organizations can choose different approaches.

### Blind Simulation

Employees are not told when a simulation will occur.

This provides more realistic behavioral measurement.

### Informed Exercise

Employees know that simulations occur periodically but do not know the exact timing or scenario.

This can reduce concerns about transparency while preserving realistic testing.

The appropriate approach depends on organizational policy, privacy requirements, and culture.

---

# Landing Page Design

A simulated phishing landing page can provide immediate learning.

For example:

> **This was a security awareness simulation.**

Then explain:

* What indicators were present.
* What the employee should have noticed.
* How to report suspicious messages.

This is known as **just-in-time training**.

It connects the lesson directly to the employee's behavior.

---

# Immediate Feedback

Immediate feedback can be more memorable than annual training.

For example:

Employee clicks simulation.

↓

Simulation page appears.

↓

"Look at the sender address."

↓

"Notice the unusual URL."

↓

"Be cautious of urgent requests."

↓

"Use the Report Phishing button."

This turns the mistake into a learning opportunity.

---

# Targeted Remediation

Employees who repeatedly demonstrate risky behavior may receive additional training.

For example:

**First failure**

→ Immediate microlearning.

**Second failure**

→ Targeted phishing training.

**Repeated failures**

→ Manager-supported intervention or additional awareness activity, depending on policy.

The objective should be improvement, not punishment.

---

# Positive Reinforcement

Employees who consistently report suspicious messages can also be recognized.

Examples include:

* Awareness recognition.
* Security champion recognition.
* Internal acknowledgment.
* Team-level recognition.

Positive reinforcement can help create a reporting culture.

---

# Security Reporting Process

The simulation should test whether employees know how to report suspicious messages.

Possible reporting methods include:

* Report Phishing button.
* Security mailbox.
* Help desk.
* Security Operations Center.
* Security awareness platform.

The reporting process should be simple.

---

# Why Reporting Matters

Consider two employees.

### Employee A

Receives phishing email → deletes it.

### Employee B

Receives phishing email → reports it.

Employee B provides greater organizational value because the security team can investigate whether other employees received the same attack.

Therefore:

> **Reporting behavior is an important security capability.**

---

# Connecting Simulations to the SOC

A mature program can connect phishing simulations with security operations.

For example:

**Employee reports simulated phishing**

↓

**Awareness platform records report**

↓

**Security team receives event**

↓

**Reporting behavior measured**

This can also reinforce the organization's real phishing-reporting process.

---

# Testing the Full Process

A sophisticated exercise can test more than employee recognition.

It can evaluate:

1. Can the employee recognize the phishing attempt?
2. Can they report it?
3. Does the report reach the correct team?
4. Can the security team identify the campaign?
5. Can the organization communicate with affected users?
6. Can lessons learned be incorporated?

This makes the exercise part of broader incident-response readiness.

---

# Phishing Simulation and GRC

From a GRC perspective, phishing simulations can support:

### Risk Management

Identify human-related risks.

### Control Testing

Test the effectiveness of awareness controls.

### Compliance

Provide evidence of awareness activities where applicable.

### Metrics

Measure behavioral performance.

### Continuous Improvement

Identify areas requiring additional controls.

### Audit Evidence

Demonstrate that the organization actively manages human risk.

---

# Evidence Collection

The program should maintain appropriate evidence such as:

* Campaign approval.
* Scope.
* Scenario.
* Date.
* Target population.
* Results.
* Training provided.
* Improvement actions.
* Management reporting.

This can support internal audits and external assessments.

---

# Practical GRC Scenario

Imagine an organization has experienced several credential-phishing incidents.

The GRC team identifies:

> **Human susceptibility to credential phishing as a significant risk.**

The organization establishes a simulation.

### Baseline

10,000 employees.

Results:

* 13% clicked.
* 4% attempted credential submission.
* 35% reported.

### Intervention

The organization provides:

* Targeted microlearning.
* Phishing-reporting guidance.
* Role-specific training.

### Follow-Up

Three months later:

* 7% clicked.
* 1% attempted credential submission.
* 68% reported.

The organization can now demonstrate measurable behavioral improvement.

---

# What the Results Do Not Prove

A phishing simulation does **not** prove that:

> "Employees are completely protected against phishing."

It only provides evidence about behavior under a particular simulated scenario.

Real attackers may use:

* Different techniques.
* Different timing.
* Different communication channels.
* AI-generated content.
* Phone calls.
* SMS.
* Social media.
* Deepfakes.

Therefore, phishing simulation results should be interpreted as **one component of human-risk measurement**.

---

# Common Mistakes

Organizations should avoid:

### Using Simulations to Punish Employees

This can discourage reporting.

### Collecting Real Credentials

This creates unnecessary security and privacy risk.

### Publicly Naming Failures

This damages trust.

### Making Every Simulation Extremely Difficult

The objective is learning, not defeating employees.

### Measuring Only Clicks

Reporting behavior is equally important.

### Ignoring Repeat Behavior

Repeated failures may indicate a deeper risk.

### Never Changing Scenarios

Employees eventually recognize the patterns.

### Running Too Many Campaigns

This can create fatigue.

### Failing to Follow Up

Simulation results are useless if no action is taken.

---

# Mature Phishing Simulation Lifecycle

A mature program follows:

**Risk Identification**

↓

**Scenario Design**

↓

**Authorization**

↓

**Campaign Preparation**

↓

**Simulation**

↓

**Behavior Measurement**

↓

**Immediate Feedback**

↓

**Targeted Training**

↓

**Follow-Up Simulation**

↓

**Trend Analysis**

↓

**Program Improvement**

This transforms phishing simulation from a simple test into a continuous security improvement mechanism.

---

# Key Takeaways

1. **Phishing simulations provide practical measurement of employee security behavior.**
2. **The primary objective is education and risk reduction, not punishment.**
3. **Every simulation should have clear authorization and scope.**
4. **Real employee credentials should never be collected.**
5. **Privacy considerations should be addressed before the exercise.**
6. **Scenarios should reflect realistic organizational threats.**
7. **Role-based simulations can provide more meaningful results.**
8. **Baseline measurements are essential for evaluating improvement.**
9. **Click rate is useful, but it should not be the only metric.**
10. **Reporting rate is an important positive security behavior.**
11. **Time to report can help measure responsiveness.**
12. **Immediate feedback can turn an unsuccessful simulation into a learning opportunity.**
13. **Repeated risky behavior may require targeted intervention.**
14. **Positive security behavior should also be recognized.**
15. **Simulations should support the organization's real phishing-reporting process.**
16. **Results should feed into security awareness and GRC risk management.**
17. **Excessive simulations can create awareness fatigue.**
18. **Simulation results should not be interpreted as proof of complete phishing protection.**
19. **Lessons learned should influence future training and simulations.**
20. **A mature program continuously measures, improves, and retests employee behavior.**

The fundamental model is:

**Simulate → Measure → Educate → Improve → Retest**

The ultimate goal is not to achieve a **zero-click rate** in simulations.

The real objective is to build employees who can:

> **Recognize suspicious activity → Stop → Report → Enable the organization to respond.**

That behavior is one of the most valuable human security capabilities an enterprise can develop.



