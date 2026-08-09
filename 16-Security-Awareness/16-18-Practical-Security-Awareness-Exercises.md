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

## Social Engineering Role-Playing

Social engineering attacks exploit human behavior rather than relying exclusively on technical vulnerabilities. Attackers may manipulate employees through **trust, urgency, authority, fear, curiosity, or helpfulness** to obtain information, access, money, or other valuable resources.

Social engineering role-playing exercises allow employees to **practice responding to these situations in a controlled environment**.

> **The objective is to build the confidence and judgment employees need to recognize manipulation and respond securely under realistic pressure.**

---

# What Is Social Engineering Role-Playing?

Social engineering role-playing is a practical awareness exercise in which participants act out realistic scenarios involving attempts to manipulate or influence them.

Unlike a traditional training course, participants must make decisions during the scenario.

For example:

**Attacker:**
"I'm from IT. We're having an issue with your account. I need you to confirm your username and verification code."

**Employee:**
"What is your ticket number? I'll contact the IT service desk directly."

The employee has successfully resisted the manipulation.

---

# Why Role-Playing Matters

Employees may understand social engineering concepts theoretically but struggle when faced with a realistic situation.

For example, an employee might know:

> "Never share passwords."

But an attacker may not directly ask for a password.

Instead, the attacker could say:

> "I don't need your password. Just read me the six-digit MFA code you received."

The employee must recognize that the underlying objective is still credential compromise.

Role-playing helps employees practice this judgment.

---

# Common Social Engineering Techniques

Role-playing exercises can simulate:

* Pretexting.
* Impersonation.
* Baiting.
* Tailgating.
* Vishing.
* Smishing.
* Business email compromise.
* Help-desk manipulation.
* Executive impersonation.
* Authority-based manipulation.
* Urgency-based manipulation.

The scenarios should reflect the organization's actual risk profile.

---

# Pretexting

Pretexting occurs when an attacker creates a believable story to obtain information or influence behavior.

Example:

> "I'm from the finance department. I'm preparing the quarterly audit and need confirmation of your manager's contact details."

The request may sound legitimate.

The employee must verify the request before providing information.

---

# Impersonation

An attacker may pretend to be:

* IT staff.
* A manager.
* A senior executive.
* A supplier.
* A customer.
* A government official.
* A security officer.

Role-playing allows employees to practice challenging the identity of the requester.

---

# Authority

Attackers often exploit perceived authority.

For example:

> "The CEO needs this immediately. Don't delay me with unnecessary verification."

The employee may feel pressure because the requester appears senior.

The correct behavior is still:

> **Follow the organization's verification process.**

---

# Urgency

Another common manipulation technique is urgency.

Examples:

* "This must be completed in five minutes."
* "Your account will be disabled today."
* "The payment has to be made immediately."
* "We have an emergency."

Urgency reduces the time employees have to think critically.

Role-playing teaches employees to recognize:

> **Urgency should increase verification, not reduce it.**

---

# Fear

Attackers may also use fear.

For example:

> "Your account has been compromised. If you don't cooperate immediately, your access will be terminated."

Employees may react emotionally rather than logically.

Role-playing allows participants to practice slowing down and verifying the situation.

---

# Curiosity

Attackers can also exploit curiosity.

Examples include:

* "Confidential salary information."
* "New organizational structure."
* "Private executive announcement."
* "Unreleased product information."

The employee must recognize that curiosity can itself become an attack vector.

---

# Helpfulness

Employees often want to help colleagues.

Attackers can exploit this positive characteristic.

For example:

> "I'm locked out of the building. Could you hold the door open for me?"

The employee may be tempted to help without verifying identity.

Role-playing helps employees understand that:

> **Being helpful does not mean bypassing security controls.**

---

# Role-Playing Scenario Design

A good exercise should have:

### Objective

What behavior are you testing?

### Scenario

What situation is being simulated?

### Roles

Who plays the employee and who plays the social engineer?

### Trigger

What starts the interaction?

### Expected Behavior

What should the employee do?

### Success Criteria

How will performance be measured?

### Debrief

What should participants learn?

---

# Example Scenario

### Scenario

An employee receives a phone call.

The caller says:

> "Hello, I'm from the IT security team. We're investigating suspicious activity on your account."

The caller asks:

> "Can you confirm your employee ID and the MFA code you just received?"

### Employee Challenge

The employee must decide whether to:

* Provide the information.
* Refuse.
* Verify the caller.
* Contact IT independently.
* Report the incident.

### Expected Behavior

The employee should refuse to provide the MFA code and independently contact the organization's IT/security team.

---

# Choosing the Participants

Role-playing can involve:

* General employees.
* Executives.
* Finance.
* HR.
* IT.
* Help desk.
* Security personnel.
* Receptionists.
* Customer service.
* Procurement.

The target audience should reflect the threat being tested.

---

# Role-Playing for High-Risk Employees

Certain roles may require more advanced exercises.

For example:

### Finance

Payment fraud.

### Help Desk

Password-reset manipulation.

### Reception

Physical impersonation.

### Executives

Executive impersonation.

### HR

Employee-data requests.

### IT Administrators

Privileged-access manipulation.

---

# Help-Desk Social Engineering

Help desks are particularly important because they may control account recovery.

Example:

> "I'm the regional director. I'm traveling and can't access my account. I need you to reset my password immediately."

The employee must follow identity-verification procedures even when the requester claims to be a senior executive.

This tests whether procedures remain effective under pressure.

---

# Executive Impersonation

An attacker may pretend to be an executive.

Example:

> "I'm in a meeting and cannot take calls. Please purchase the gift cards and send me the codes."

Role-playing can teach employees to:

* Verify unusual requests.
* Use established communication channels.
* Avoid bypassing financial controls.
* Report suspicious behavior.

---

# Physical Social Engineering

Role-playing does not have to occur through email or telephone.

It can also simulate physical scenarios.

For example:

A person approaches an employee at an office entrance:

> "I forgot my badge. Can you let me in?"

The employee must determine whether to:

* Allow access.
* Challenge the individual.
* Contact security.
* Direct the person to reception.

This connects role-playing with physical security awareness.

---

# Tailgating Scenario

A realistic exercise could involve someone carrying several boxes.

They approach an employee entering a secure door.

The individual says:

> "Could you hold the door? My hands are full."

The employee must decide whether to allow access.

The expected response may be:

> "Please use reception or contact someone who can verify your access."

---

# Vishing Role-Playing

Vishing means **voice phishing**.

The exercise can simulate:

* Fake bank calls.
* Fake IT support.
* Fake executives.
* Fake suppliers.
* Fake government officials.

Employees should practice:

1. Staying calm.
2. Not providing sensitive information.
3. Verifying identity.
4. Ending suspicious calls.
5. Reporting the incident.

---

# Smishing Role-Playing

Smishing uses SMS or messaging platforms.

Example:

> "Your corporate account will be suspended. Verify immediately using this link."

The exercise can ask employees:

> "What would you do next?"

Possible responses:

* Click the link.
* Reply.
* Call the number provided.
* Verify independently.
* Report the message.

The objective is to reinforce safe decision-making.

---

# Social Media Role-Playing

Employees may also encounter social engineering through:

* LinkedIn.
* Facebook.
* X.
* WhatsApp.
* Professional communities.

Example:

> "Hi, I noticed you work at Company X. I'm recruiting for a confidential project. Could you tell me which cloud platform your company uses?"

The employee should understand that seemingly harmless information can contribute to attacker reconnaissance.

---

# Information Gathering

Role-playing can demonstrate how small pieces of information can be combined.

For example:

**Employee name**

*

**Job title**

*

**Manager**

*

**Technology platform**

*

**Office location**

=

**More convincing attack pretext**

This teaches employees to think beyond obviously sensitive information.

---

# Building the Scenario

The scenario should be realistic enough to create useful learning.

However, it should not be so realistic that it causes:

* Fear.
* Confusion.
* Business disruption.
* Reputational damage.

The exercise must remain within approved boundaries.

---

# Difficulty Levels

Role-playing can progress through several levels.

### Beginner

Obvious suspicious behavior.

### Intermediate

Plausible request with several warning signs.

### Advanced

Highly convincing pretext requiring multiple verification steps.

### Expert

Multi-stage social engineering involving several employees or channels.

Difficulty should increase according to program maturity.

---

# The Human Element

The exercise should focus on the psychological mechanisms behind social engineering.

Participants should learn to recognize:

### Authority

"Your manager asked me to do this."

### Urgency

"This needs to happen immediately."

### Fear

"Your account will be disabled."

### Reciprocity

"I helped you last week; now I need a favor."

### Trust

"I'm from your IT department."

### Curiosity

"Here's confidential information."

### Familiarity

"We worked together last year."

Understanding these principles helps employees recognize manipulation in unfamiliar situations.

---

# The STOP Model

A simple response model can help employees remember what to do.

### S – Stop

Do not act immediately.

### T – Think

Ask whether the request makes sense.

### O – Observe

Look for inconsistencies or warning signs.

### P – Proceed Safely

Verify independently before taking action.

The model can be adapted to the organization's awareness program.

---

# Verification Techniques

Employees should practice:

### Verify the Person

Confirm identity through an independent method.

### Verify the Request

Determine whether the request is expected.

### Verify the Channel

Use a trusted communication channel.

### Verify the Information

Confirm unusual requests with the appropriate business owner.

---

# Out-of-Band Verification

One of the strongest defenses against social engineering is **independent verification**.

For example:

An employee receives a message from the CEO requesting a payment.

Instead of replying to the message, the employee:

1. Finds the CEO's known phone number.
2. Calls independently.
3. Confirms the request.

This breaks the attacker's control of the communication channel.

---

# Role-Playing Instructions

Participants should be told:

* This is an exercise.
* Follow normal security procedures.
* Do not reveal real passwords or sensitive information.
* Ask questions.
* Stop the scenario if uncomfortable.
* Report suspicious behavior according to policy.

The facilitator should ensure that the exercise remains educational.

---

# Facilitator Responsibilities

The facilitator should:

* Explain the exercise.
* Establish boundaries.
* Monitor the scenario.
* Avoid unnecessary escalation.
* Record relevant observations.
* Conduct the debrief.
* Identify improvement opportunities.

The facilitator should not intentionally humiliate participants.

---

# Measuring Performance

Performance can be measured using:

* Verification behavior.
* Information disclosure.
* Policy adherence.
* Reporting.
* Response time.
* Confidence.
* Escalation behavior.

A simple scoring model might be:

| Behavior                         | Score |
| -------------------------------- | ----: |
| Immediately provides information |     0 |
| Questions the request            |     1 |
| Attempts verification            |     2 |
| Refuses and reports              |     3 |

The scoring system should reflect organizational security objectives.

---

# Measuring More Than Failure

A mature exercise should not simply ask:

> "Did the employee fail?"

Instead, examine:

* Did they recognize the risk?
* Did they challenge the requester?
* Did they verify identity?
* Did they follow policy?
* Did they report?
* Did they escalate appropriately?

This provides more useful behavioral information.

---

# Debriefing

The debrief is one of the most important parts of the exercise.

Immediately afterward, discuss:

* What happened?
* What warning signs existed?
* Why did the request appear credible?
* What could the employee have done differently?
* Which procedure should have been followed?

The goal is to convert the experience into learning.

---

# Psychological Safety

Employees should feel safe discussing mistakes.

For example:

> "What made this request seem legitimate?"

is better than:

> "Why did you fall for this?"

The first question encourages learning.

The second can create defensiveness.

---

# Lessons Learned

The facilitator should document:

* Successful behaviors.
* Common mistakes.
* Policy confusion.
* Process weaknesses.
* Training gaps.
* Technology issues.

These findings can feed into the broader security awareness program.

---

# Identifying Process Problems

Sometimes the employee is not the real problem.

Suppose an employee fails to verify a payment request because:

> The organization's verification procedure is unclear.

The exercise has identified a **process weakness**, not merely a training weakness.

The solution may require:

* Updated procedures.
* Better approval workflows.
* Stronger authentication.
* Technical controls.

This is an important GRC perspective.

---

# Identifying Policy Gaps

Role-playing may reveal questions such as:

> "Who should I contact if the CEO asks me to make an urgent payment?"

If the organization cannot answer clearly, the policy may need improvement.

Security exercises therefore help test the effectiveness of governance documents.

---

# Identifying Technical Gaps

Exercises may also reveal technical weaknesses.

For example:

Employees cannot easily report suspicious messages.

The organization may need:

* Report Phishing button.
* Improved help-desk workflow.
* Automated reporting.
* Better security tooling.

The exercise can therefore identify opportunities beyond awareness training.

---

# Linking Role-Playing to Risk Management

The findings can be incorporated into the risk-management process.

Example:

**Observation**

Employees struggle to verify executive requests.

↓

**Risk**

Business email compromise and payment fraud.

↓

**Risk Treatment**

Targeted training + verification process.

↓

**Control**

Dual authorization for payments.

↓

**Measurement**

Repeat role-playing exercise.

This demonstrates how practical exercises can support GRC.

---

# Role-Playing and Security Culture

Role-playing also reinforces an important cultural principle:

> **Employees are allowed to question unusual requests.**

In some organizations, employees may hesitate to challenge senior personnel.

A strong security culture communicates:

> "Following the security process is more important than blindly following an unusual request."

---

# Practical Enterprise Exercise

Imagine a company wants to test finance employees.

### Scenario

A participant receives a simulated phone call:

> "I'm the CFO. I'm traveling and need an urgent supplier payment processed today."

The caller requests:

* Payment details.
* Confirmation of the transaction.
* Immediate action.

### Expected Behavior

The employee should:

1. Remain calm.
2. Avoid providing sensitive information.
3. Verify the identity of the requester.
4. Follow financial approval procedures.
5. Report the suspicious request.

### Debrief

The facilitator explains:

* Authority was used.
* Urgency was used.
* The request bypassed normal procedures.
* Independent verification should have occurred.

---

# Advanced Multi-Stage Exercise

A mature organization can simulate a more complex attack.

### Stage 1

Attacker gathers employee information from public sources.

### Stage 2

Attacker contacts an employee pretending to be IT.

### Stage 3

Attacker contacts the help desk.

### Stage 4

Attacker attempts to obtain account information.

### Stage 5

Attacker attempts to manipulate another employee.

This demonstrates how social engineering can involve **multiple people and multiple communication channels**.

---

# Exercise After-Action Report

A formal exercise can produce an after-action report containing:

### Objective

What was being tested?

### Scope

Who participated?

### Scenario

What occurred?

### Results

What behaviors were observed?

### Findings

What weaknesses were identified?

### Risk

What could happen in a real attack?

### Recommendations

What improvements are required?

### Owner

Who is responsible?

### Target Date

When should remediation be completed?

This makes the exercise valuable for GRC and audit purposes.

---

# Common Mistakes

Organizations should avoid:

### Making the Exercise Punitive

The objective is learning.

### Using Real Sensitive Information

Exercises should use controlled information.

### Excessively Aggressive Scenarios

This can damage trust.

### Ignoring Process Weaknesses

Not every failure is caused by insufficient awareness.

### Failing to Debrief

Without debriefing, much of the learning opportunity is lost.

### Measuring Only Success/Failure

Behavioral details are more useful.

### Repeating Identical Scenarios

Participants eventually learn the script.

### Ignoring Privacy

Employee performance information should be handled appropriately.

---

# Key Takeaways

1. **Social engineering role-playing provides practical experience against human-manipulation techniques.**
2. **It helps employees practice security decisions under realistic conditions.**
3. **Scenarios should reflect actual organizational risks.**
4. **Common techniques include authority, urgency, fear, trust, curiosity, and helpfulness.**
5. **Role-playing can cover email, phone, SMS, social media, and physical interactions.**
6. **High-risk roles should receive scenarios relevant to their responsibilities.**
7. **Independent verification is one of the most important behaviors to reinforce.**
8. **Employees should never disclose real passwords, MFA codes, or sensitive information during exercises.**
9. **Privacy and authorization must be addressed before conducting the exercise.**
10. **Facilitators should create an environment where employees can safely discuss mistakes.**
11. **Performance should be measured through specific behaviors rather than simply pass/fail results.**
12. **Debriefing converts the exercise experience into practical learning.**
13. **Exercises can identify training, policy, process, and technical weaknesses.**
14. **Findings should feed into the organization's risk-management process.**
15. **Security role-playing can strengthen the organization's security culture.**
16. **Security awareness exercises should encourage employees to challenge unusual requests appropriately.**
17. **Advanced exercises can simulate multi-stage attacks involving multiple employees.**
18. **After-action reports provide useful evidence for GRC and continuous improvement.**
19. **Exercises should evolve as threats and organizational risks change.**
20. **The ultimate objective is to develop employees who can recognize manipulation, verify requests, refuse unsafe actions, and report suspicious activity.**

The fundamental model is:

**Scenario → Role-Play → Observe → Debrief → Identify Gaps → Improve → Retest**

The most important lesson is:

> **A security-aware employee is not simply someone who knows that social engineering exists; it is someone who can recognize manipulation and make the correct security decision when an attacker is actively trying to influence them.**



