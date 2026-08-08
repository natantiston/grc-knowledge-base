# 16.5 Social Engineering

> **Chapter:** 16 – Security Awareness
> **Topic:** Types of Social Engineering Attacks
> **Difficulty:** Beginner to Intermediate
> **Estimated Reading Time:** 10–15 minutes

## Introduction

Social engineering is the use of psychological manipulation, deception, or influence to persuade individuals to perform actions that compromise information security. Instead of directly exploiting a technical vulnerability, attackers exploit human behavior, trust, emotions, and decision-making.

Social engineering is particularly dangerous because it can bypass sophisticated technical security controls. An organization may have strong firewalls, endpoint protection, encryption, and access controls, but an employee who voluntarily provides credentials, approves an authentication request, transfers money, or discloses sensitive information can unintentionally bypass many of those defenses.

Attackers commonly exploit emotions and behavioral tendencies such as:

* Trust
* Fear
* Urgency
* Curiosity
* Authority
* Greed
* Sympathy
* Helpfulness
* Desire to avoid conflict
* Willingness to follow instructions

The objective may be to obtain credentials, gain unauthorized access, steal information, transfer funds, install malware, compromise systems, or gain physical access to restricted areas.

Social engineering can occur through email, telephone calls, SMS, messaging applications, social media, websites, physical interactions, and face-to-face conversations. Modern attacks may combine multiple techniques to make the deception more convincing.

Security Awareness Programs therefore need to teach employees not only how to recognize suspicious technical indicators but also how attackers manipulate human behavior.

---

## Learning Objectives

By the end of this lesson, you will be able to:

* Define social engineering.
* Explain why social engineering is a significant cybersecurity risk.
* Identify common types of social engineering attacks.
* Recognize psychological techniques used by attackers.
* Understand how attackers exploit human behavior.
* Identify employee responsibilities in preventing social engineering attacks.
* Explain social engineering risk from a Governance, Risk, and Compliance (GRC) perspective.

---

## What Is Social Engineering?

Social engineering is an attack technique in which an attacker manipulates a person into performing an action that benefits the attacker.

Unlike many technical attacks, the attacker may not need to exploit a software vulnerability. Instead, the attacker attempts to convince the victim that a fraudulent request is legitimate.

For example, an attacker may pretend to be:

* An IT administrator.
* A senior executive.
* A bank representative.
* A supplier.
* A customer.
* A government official.
* A colleague.
* A new employee.

The attacker creates a believable scenario and attempts to persuade the victim to take a specific action.

The action might include:

* Clicking a link.
* Opening an attachment.
* Providing a password.
* Approving an MFA request.
* Transferring money.
* Changing a supplier's bank account.
* Sharing confidential information.
* Allowing physical access.
* Installing software.
* Disabling a security control.

---

## How Social Engineering Works

Most social engineering attacks follow a general pattern.

### 1. Target Selection

The attacker identifies a person or organization that may provide useful access or information.

Targets may be selected based on:

* Job responsibilities.
* Privileged access.
* Financial authority.
* Access to sensitive information.
* Organizational position.
* Public visibility.

### 2. Information Gathering

The attacker gathers information about the target.

Sources may include:

* Company websites.
* Social media.
* Professional networking platforms.
* Public documents.
* Press releases.
* Organizational announcements.
* Previously compromised information.

The information is used to make the attack more credible.

### 3. Establishing Trust

The attacker creates a believable identity, relationship, or situation.

For example:

> "Hello, I'm from the IT support team. We are currently performing a security update on your account."

The attacker attempts to make the victim believe that the interaction is legitimate.

### 4. Psychological Manipulation

The attacker creates a reason for the victim to act.

Common techniques include:

* Creating urgency.
* Establishing authority.
* Creating fear.
* Offering a reward.
* Exploiting curiosity.
* Pretending to need assistance.

### 5. Victim Action

The victim performs the requested action.

This may result in:

* Credential disclosure.
* Unauthorized access.
* Malware execution.
* Financial loss.
* Data disclosure.
* Physical security compromise.

### 6. Exploitation

The attacker uses the information, access, or action obtained from the victim to achieve their objective.

---

## Common Types of Social Engineering

Social engineering includes a broad range of techniques.

### Phishing

Phishing uses fraudulent communications to trick users into performing an unsafe action.

Common objectives include:

* Stealing credentials.
* Installing malware.
* Obtaining financial information.
* Capturing authentication information.
* Redirecting users to malicious websites.

Phishing is commonly conducted through email but can also occur through other communication channels.

### Spear Phishing

Spear phishing is a targeted form of phishing directed at a specific person, department, or organization.

Attackers may use information about:

* The employee.
* Their position.
* Their organization.
* Their colleagues.
* Current projects.
* Customers.
* Suppliers.

The additional personalization makes the attack more convincing.

### Whaling

Whaling targets senior executives and other high-value individuals.

Potential targets include:

* Chief Executive Officers (CEOs).
* Chief Financial Officers (CFOs).
* Chief Information Security Officers (CISOs).
* Board members.
* Senior directors.

The attacker may attempt to exploit the authority, access, or financial decision-making capability of the target.

### Vishing

Vishing, or voice phishing, uses telephone or voice communications to manipulate victims.

An attacker may impersonate:

* IT support.
* Bank representatives.
* Customers.
* Vendors.
* Government officials.
* Senior executives.

### Smishing

Smishing is phishing conducted through SMS or messaging applications.

Common examples include fake:

* Delivery notifications.
* Banking alerts.
* Account verification requests.
* Password reset notifications.
* Security warnings.

### Business Email Compromise (BEC)

Business Email Compromise involves impersonating or compromising trusted business accounts to conduct fraudulent activities.

Common objectives include:

* Unauthorized payments.
* Bank account changes.
* Sensitive information theft.
* Payroll fraud.
* Procurement fraud.

### Pretexting

Pretexting involves creating a fabricated story or scenario to obtain information or persuade a person to perform an action.

For example, an attacker may pretend to be an IT administrator who needs an employee's credentials to resolve an alleged security problem.

### Baiting

Baiting uses an attractive offer or curiosity to encourage a victim to perform an unsafe action.

Examples include:

* Free software.
* USB devices.
* Fake documents.
* Promotional offers.
* Free downloads.

The objective may be to install malware or obtain unauthorized access.

### Quid Pro Quo

Quid pro quo attacks offer a perceived benefit in exchange for information or access.

For example:

> "I can fix your computer remotely if you provide your username and password."

The attacker creates the impression that cooperation will result in a useful service or benefit.

### Tailgating and Piggybacking

Tailgating and piggybacking involve gaining unauthorized physical access by following an authorized individual into a restricted area.

An attacker may claim:

* They forgot their access card.
* Their badge is not working.
* They are a new employee.
* They are delivering equipment.
* They are visiting another employee.

These attacks demonstrate that social engineering is not limited to digital environments.

---

## Psychological Techniques Used by Attackers

Attackers commonly exploit predictable human behaviors.

### Authority

The attacker pretends to be someone with authority.

Example:

> "The CEO needs this completed immediately."

Employees may be reluctant to question requests from senior personnel.

### Urgency

The attacker creates time pressure to prevent the victim from carefully evaluating the request.

Example:

> "You have five minutes before your account is locked."

Urgency reduces the likelihood that the victim will independently verify the request.

### Fear

The attacker creates a perception that something bad will happen if the victim does not cooperate.

Example:

> "Your account has been compromised. Confirm your credentials immediately."

### Curiosity

The attacker uses information or content that encourages the victim to investigate.

Example:

> "Here are the confidential photos from yesterday's meeting."

### Trust

The attacker impersonates someone familiar or trusted.

Example:

> "Hi, this is John from the IT team."

### Helpfulness

The attacker exploits the victim's willingness to assist another person.

Example:

> "I'm locked outside the office. Could you please hold the door open for me?"

### Reciprocity

The attacker provides something first and then asks the victim for something in return.

For example, an attacker may offer assistance with a technical problem before requesting sensitive information.

---

## Why Social Engineering Is Effective

Social engineering succeeds because it attacks one of the most difficult elements of cybersecurity to control: human decision-making.

Factors that increase organizational exposure include:

* High workloads.
* Time pressure.
* Lack of awareness.
* Remote and hybrid work.
* Organizational changes.
* Publicly available information.
* Complex business processes.
* Excessive trust.
* Poor verification procedures.
* Inadequate incident reporting.

Even experienced employees can become victims when an attack is carefully designed and supported by accurate information.

The objective of security awareness is therefore not to make employees suspicious of every communication. Instead, employees should learn to recognize situations that require additional verification.

---

## Social Engineering and Technology

Social engineering attacks increasingly combine human manipulation with technical capabilities.

For example, an attacker may:

1. Collect information from social media.
2. Create a convincing fraudulent email.
3. Direct the employee to a fake login page.
4. Capture the employee's credentials.
5. Trigger an MFA request.
6. Attempt to persuade the employee to approve the request.

Modern attacks may also use automation and artificial intelligence to generate convincing messages, impersonate individuals, and scale attacks.

This makes behavioral awareness increasingly important.

---

## Employee Responsibilities

Employees should:

* Verify unusual requests.
* Avoid making important decisions under unnecessary pressure.
* Protect sensitive information.
* Never share passwords or MFA codes.
* Independently verify financial requests.
* Follow established approval procedures.
* Challenge suspicious physical access attempts.
* Report suspicious activity.
* Follow organizational security policies.

Employees should be encouraged to pause and verify rather than automatically trust a request.

---

## Security Awareness Best Practices

Organizations should:

* Provide regular social engineering awareness training.
* Conduct controlled phishing simulations.
* Establish clear verification procedures.
* Train employees to recognize manipulation techniques.
* Protect publicly available employee information.
* Encourage prompt incident reporting.
* Reinforce physical security awareness.
* Review social engineering risks regularly.
* Provide role-specific awareness training for high-risk employees.

Security awareness should be reinforced continuously rather than delivered only as an annual compliance exercise.

---

## GRC Perspective

Social engineering is a significant Governance, Risk, and Compliance (GRC) concern because it represents a human-related risk that can undermine otherwise effective technical and administrative security controls.

### Governance

Governance responsibilities include:

* Establishing security awareness policies.
* Defining employee responsibilities.
* Establishing verification procedures.
* Defining incident reporting requirements.
* Assigning security awareness ownership.
* Establishing executive accountability.
* Defining security culture objectives.

### Risk Management

Social engineering risks should be assessed based on:

* Likelihood of successful manipulation.
* Potential business impact.
* Targeted employee groups.
* Access privileges.
* Sensitive information handled.
* Financial authority.
* Privileged access.
* Previous incidents.
* Phishing simulation results.

High-risk roles may require additional awareness training and targeted exercises.

### Compliance

Social engineering awareness supports compliance with:

* ISO/IEC 27001:2022 Information Security Management System (ISMS).
* ISO/IEC 27002:2022 Information Security Controls.
* NIST Cybersecurity Framework (CSF) 2.0.
* NIST SP 800-50, Building an Information Technology Security Awareness and Training Program.
* NIST SP 800-16, Information Technology Security Training Requirements.
* General Data Protection Regulation (GDPR).
* NIS2 Directive.
* Industry-specific cybersecurity regulations.

Evidence may include:

* Security awareness policies.
* Training records.
* Phishing simulation results.
* Social engineering exercise results.
* Incident reports.
* Risk assessments.
* Corrective action records.
* Management reviews.

These records help demonstrate that the organization actively manages human-related cybersecurity risks.

---

## Diagram Placeholder

**Title:** Social Engineering Attack Lifecycle

**Diagram Description:**

```text
       Target Selection
              │
              ▼
     Information Gathering
              │
              ▼
      Build Trust / Pretext
              │
              ▼
    Psychological Manipulation
              │
              ▼
        Victim Action
              │
              ▼
       Unauthorized Access
              │
              ▼
       Data / Financial Loss
```

**Caption:**

*"Social engineering attacks exploit human trust and decision-making to obtain information, access, or actions that benefit the attacker."*

---

## Practical Example

An attacker researches a company's employees through publicly available information and identifies the Finance Manager and Chief Financial Officer (CFO).

The attacker creates a convincing email impersonating the CFO and requests an urgent payment to a new supplier bank account. The message references a real business project and instructs the Finance Manager to complete the transfer before the end of the day.

The Finance Manager recognizes the urgency and authority tactics commonly used in social engineering attacks. Instead of processing the payment immediately, the employee follows the organization's financial verification procedure and contacts the CFO through a known telephone number.

The CFO confirms that no payment was requested.

The Finance Manager reports the incident to the Security team, which investigates the message, identifies the attempted fraud, and takes appropriate action to prevent similar attacks.

This example demonstrates how security awareness, verification procedures, and employee vigilance can prevent social engineering attacks even when the attacker has gathered legitimate organizational information.

---

## Key Takeaways

* Social engineering attacks exploit human psychology, trust, and decision-making.
* Attackers may use phishing, spear phishing, whaling, vishing, smishing, BEC, pretexting, baiting, quid pro quo, tailgating, and piggybacking.
* Common manipulation techniques include authority, urgency, fear, curiosity, trust, helpfulness, and reciprocity.
* Attackers increasingly combine social engineering with technical capabilities and automation.
* Employees should verify unusual requests, protect credentials, follow established procedures, and report suspicious activity promptly.
* Social engineering can bypass sophisticated technical security controls, making employee awareness an essential layer of organizational defense.
* Security awareness should focus on developing secure behaviors rather than simply teaching employees to identify obvious phishing messages.
* From a Governance, Risk, and Compliance (GRC) perspective, social engineering awareness strengthens governance through defined policies and responsibilities, reduces enterprise cyber risk through improved human behavior, and supports compliance through documented awareness, risk assessments, exercises, and continual improvement.

  # Part 2 – Phishing, Spear Phishing, and Whaling

Phishing is one of the most common forms of social engineering. It involves deceptive communications designed to persuade a person to reveal information, click a malicious link, open an attachment, approve an authentication request, transfer money, or perform another action that benefits an attacker.

Phishing, spear phishing, and whaling use similar psychological techniques but differ primarily in their level of targeting, personalization, and the type of victim being targeted.

Understanding these differences is important because organizations cannot rely on a single awareness message. Employees need to recognize both broad phishing campaigns and highly personalized attacks that may appear to originate from trusted individuals.

---

## Phishing

Traditional phishing is generally a broad attack in which an attacker sends fraudulent communications to a large number of potential victims.

Common objectives include:

* Stealing usernames and passwords.
* Obtaining payment information.
* Installing malware.
* Capturing authentication information.
* Redirecting users to malicious websites.
* Delivering ransomware.
* Collecting personal or confidential information.

Phishing messages may appear to come from:

* Banks.
* Cloud service providers.
* Microsoft 365 or other productivity platforms.
* Delivery companies.
* Government organizations.
* IT departments.
* Human Resources.
* Financial institutions.

The attacker attempts to make the message appear legitimate enough that the recipient performs the requested action without verification.

---

## Common Phishing Indicators

Employees should be trained to look for multiple indicators rather than relying on a single warning sign.

Potential indicators include:

* Unexpected requests.
* Unusual urgency.
* Requests for passwords.
* Requests for MFA codes or approval.
* Suspicious links.
* Unexpected attachments.
* Unusual sender addresses.
* Look-alike domains.
* Requests to bypass normal procedures.
* Threats of account suspension.
* Unexpected financial requests.
* Inconsistent branding or formatting.
* Requests for confidential information.

However, modern phishing messages may contain excellent grammar, professional branding, and realistic business language.

The absence of spelling mistakes does not mean that a message is safe.

---

## Spear Phishing

Spear phishing is a targeted form of phishing directed at a specific individual, team, department, or organization.

Unlike mass phishing, spear phishing typically uses information about the intended victim to make the communication more convincing.

Attackers may research:

* Job titles.
* Organizational structures.
* Business relationships.
* Current projects.
* Professional interests.
* Colleagues.
* Suppliers.
* Customers.
* Public announcements.
* Social media activity.

For example, an attacker may identify a Procurement Manager through a company's website and send a message pretending to be a known supplier. The message may reference a real purchase order and request that future payments be sent to a different bank account.

The more accurately the attacker understands the target's environment, the more convincing the attack may become.

---

## Why Spear Phishing Is Dangerous

Spear phishing presents a higher risk than generic phishing because personalization can reduce the victim's suspicion.

A typical attack may follow this sequence:

1. Research the target.
2. Identify trusted relationships.
3. Gather information about business activities.
4. Create a convincing identity or scenario.
5. Send a highly targeted communication.
6. Manipulate the victim into taking action.
7. Exploit the resulting access or information.

The attack may therefore appear to be part of normal business activity.

---

## Whaling

Whaling is a specialized form of spear phishing that targets senior executives or other high-value individuals.

Potential targets include:

* Chief Executive Officers (CEOs).
* Chief Financial Officers (CFOs).
* Chief Information Security Officers (CISOs).
* Board members.
* Senior directors.
* Legal executives.
* Finance managers.
* Other individuals with significant authority.

The objective may be to exploit the target's authority, access, or ability to approve important transactions.

---

## Why Executives Are Targeted

Executives and senior personnel may have:

* Broad access to sensitive information.
* Authority to approve transactions.
* Access to confidential business information.
* Significant influence over employees.
* Access to strategic systems.
* Relationships with external organizations.
* Authority over financial or operational decisions.

Attackers may therefore view executive accounts and identities as high-value targets.

Whaling does not always require compromising the executive's actual mailbox. Attackers may simply impersonate the executive using a look-alike email address, compromised account, spoofed communication, or another deceptive technique.

For example:

> "I am currently in a meeting and cannot take a call. Please process this payment immediately and send me the confirmation."

The attacker is exploiting authority and urgency simultaneously.

---

## Business Email Compromise Connection

Spear phishing and whaling are frequently used as part of Business Email Compromise (BEC) attacks.

A typical attack may involve:

```text
Research Target
      │
      ▼
Identify Executive or Supplier
      │
      ▼
Create Fake Identity or Compromise Account
      │
      ▼
Send Targeted Message
      │
      ▼
Create Urgency or Authority
      │
      ▼
Victim Takes Action
      │
      ▼
Financial or Information Loss
```

The attacker does not necessarily need to compromise the executive's actual mailbox. Impersonation, look-alike domains, compromised accounts, or fraudulent communications may be sufficient to deceive the victim.

---

## Comparing Phishing, Spear Phishing, and Whaling

| Characteristic        | Phishing                                     | Spear Phishing                    | Whaling                                                  |
| --------------------- | -------------------------------------------- | --------------------------------- | -------------------------------------------------------- |
| Targeting             | Broad                                        | Specific                          | Highly specific                                          |
| Personalization       | Usually low                                  | High                              | Very high                                                |
| Typical Targets       | General employees                            | Specific employees or departments | Executives and senior personnel                          |
| Information Gathering | Limited to moderate                          | Significant                       | Extensive                                                |
| Potential Impact      | Moderate to high                             | High                              | Very high                                                |
| Common Objective      | Credential theft, malware, information theft | Credential theft, access, fraud   | Financial fraud, sensitive information, strategic access |

These categories can overlap. Whaling is generally considered a highly targeted form of spear phishing.

---

## Verification Practices

Employees should apply additional verification when a communication involves:

* Money transfers.
* Bank account changes.
* Password resets.
* MFA requests.
* Confidential information.
* Privileged access.
* Sensitive customer information.
* Requests to bypass normal procedures.
* Changes to established business processes.

Verification should use a trusted communication channel rather than replying directly to the suspicious message.

For example, if an email requests a payment, the employee should independently contact the requester using an approved telephone number, internal directory, or established business communication method.

---

## What Employees Should Do

When an employee suspects phishing, spear phishing, or whaling, they should:

1. Stop and evaluate the request.
2. Avoid clicking suspicious links.
3. Do not open unexpected attachments.
4. Do not provide credentials or MFA codes.
5. Independently verify unusual requests.
6. Follow financial and approval procedures.
7. Report the communication through the approved security channel.
8. Follow instructions from the security or IT team.

Employees should not attempt to investigate the attacker themselves.

---

## Security Awareness Considerations

Awareness training should teach employees that sophisticated attacks may:

* Use correct company terminology.
* Reference real projects.
* Use legitimate-looking logos.
* Include accurate personal information.
* Appear to originate from a known person.
* Use realistic business language.
* Reference actual customers or suppliers.
* Create realistic business scenarios.

Employees should therefore focus on **behavioral verification** rather than simply looking for spelling mistakes or poor formatting.

A sophisticated phishing message can look professional and still be malicious.

---

## Best Practices

Organizations should:

* Conduct regular phishing awareness training.
* Run controlled phishing simulations.
* Train employees on spear phishing and whaling.
* Establish independent verification procedures.
* Require additional approval for high-risk transactions.
* Protect executive and employee information.
* Implement strong authentication.
* Monitor suspicious authentication activity.
* Provide simple reporting mechanisms.
* Review phishing trends regularly.
* Provide additional training to high-risk personnel.

Technical controls and human awareness should operate together as multiple layers of defense.

---

## GRC Perspective

Phishing, spear phishing, and whaling should be incorporated into the organization's Governance, Risk, and Compliance (GRC) framework because they represent significant human-centric risks.

### Governance

Governance should define:

* Security awareness requirements.
* Financial verification procedures.
* Executive security responsibilities.
* Incident reporting requirements.
* Authentication requirements.
* Security awareness ownership.
* Responsibilities for high-risk business processes.

### Risk Management

Organizations should assess:

* Which employees are frequently targeted.
* Which departments have financial authority.
* Which users have privileged access.
* Which systems contain sensitive information.
* Historical phishing incidents.
* Results of phishing simulations.
* Business impact of successful attacks.
* Exposure of employee and executive information.

High-risk employees should receive additional awareness and targeted exercises.

### Compliance

Phishing awareness contributes to compliance with:

* ISO/IEC 27001:2022 Information Security Management System (ISMS).
* ISO/IEC 27002:2022 Information Security Controls.
* NIST Cybersecurity Framework (CSF) 2.0.
* NIST SP 800-50, Building an Information Technology Security Awareness and Training Program.
* NIST SP 800-61 Rev. 2, Computer Security Incident Handling Guide.
* General Data Protection Regulation (GDPR).
* NIS2 Directive.
* Industry-specific cybersecurity requirements.

Evidence may include:

* Awareness training records.
* Phishing simulation results.
* Incident reports.
* Risk assessments.
* Executive training records.
* Security policies.
* Financial verification procedures.
* Corrective action records.

---

## Diagram Placeholder

**Title:** Phishing Attack Targeting Levels

**Diagram Description:**

```text
                    PHISHING
                       │
          ┌────────────┴────────────┐
          │                         │
     Broad Target              Targeted Attack
                                    │
                           ┌────────┴────────┐
                           │                 │
                    Spear Phishing       Whaling
                           │                 │
                    Specific Users      Executives
```

**Caption:**

*"Phishing ranges from broad campaigns to highly targeted spear phishing and whaling attacks directed at specific individuals or executives."*

---

## Practical Example

A company's Procurement Manager receives an email appearing to come from a long-term supplier. The email contains the correct supplier name, references an actual purchase order, and requests that future payments be sent to a new bank account.

The message appears legitimate because it contains information that would normally be known only by business partners. However, the Procurement Manager recognizes that changing supplier banking information is a high-risk request.

Instead of responding to the email, the employee contacts the supplier using the telephone number already stored in the organization's vendor management system. The supplier confirms that no bank account change was requested.

The employee reports the email to the Security team. The investigation determines that the attacker had gathered information about the supplier relationship and created a targeted spear-phishing campaign.

This example demonstrates why employees must verify unusual requests independently, even when a message contains accurate business information.

---

## Key Takeaways

* Phishing is generally broad, while spear phishing targets specific individuals or organizations.
* Whaling is a highly targeted form of spear phishing directed at executives and other high-value individuals.
* Personalized attacks can be significantly more convincing than generic phishing campaigns.
* Attackers may use publicly available information, compromised accounts, look-alike domains, and realistic business scenarios.
* Employees should independently verify unusual requests involving money, credentials, sensitive information, or changes to established procedures.
* Phishing awareness should focus on behavioral verification rather than simply identifying spelling mistakes or obvious technical indicators.
* Technical controls, authentication mechanisms, approval procedures, and employee awareness should work together as layers of defense.
* From a Governance, Risk, and Compliance (GRC) perspective, effective phishing awareness strengthens governance through defined verification and reporting procedures, reduces enterprise cyber risk through targeted employee education, and supports compliance through documented training, simulations, risk assessments, and incident management.

# Part 3 – Vishing, Smishing, and Business Email Compromise (BEC)

Vishing, smishing, and Business Email Compromise (BEC) are forms of social engineering that use trusted communication channels to manipulate individuals into revealing information, approving transactions, providing access, or performing other actions that benefit attackers.

Unlike traditional phishing, which is commonly associated with email, these attacks may use telephone calls, SMS messages, messaging applications, compromised business accounts, or impersonation of trusted individuals.

These attacks are particularly dangerous because employees may naturally trust familiar communication channels. A telephone call from someone claiming to be from IT, an SMS appearing to come from a bank, or an email appearing to come from a senior executive can create a strong sense of legitimacy.

---

## Vishing

Vishing, or voice phishing, is a social engineering attack conducted through telephone or voice communication.

The attacker attempts to convince the victim that they are speaking with a legitimate person or organization.

Attackers may impersonate:

* IT support personnel.
* Bank representatives.
* Government officials.
* Customers.
* Suppliers.
* Delivery companies.
* Human Resources personnel.
* Security teams.
* Senior executives.

The attacker may request:

* Passwords.
* MFA verification codes.
* Personal information.
* Account information.
* Remote access.
* Payment authorization.
* Confidential business information.

---

## Common Vishing Scenarios

A vishing attack may involve an attacker claiming:

> "This is the IT Help Desk. We detected suspicious activity on your account. I need your MFA code to verify your identity."

Another example may involve a financial department:

> "I'm calling from your bank's fraud department. We detected an unauthorized transaction. Please confirm your account details so we can secure your account."

The attacker creates a sense of urgency and authority to discourage the victim from independently verifying the call.

---

## Vishing Warning Signs

Employees should be cautious when a caller:

* Requests passwords.
* Requests MFA codes.
* Requests sensitive information unexpectedly.
* Creates extreme urgency.
* Threatens account suspension.
* Requests remote access.
* Demands immediate payment.
* Refuses independent verification.
* Becomes aggressive when questioned.
* Requests information that the legitimate organization should already possess.

A legitimate support organization should not normally require an employee to disclose their password or MFA verification code.

---

## Defensive Practices Against Vishing

Employees should:

1. Remain calm.
2. Avoid providing sensitive information immediately.
3. Ask for the caller's identity and department.
4. End the call if the request appears suspicious.
5. Independently contact the organization using a trusted number.
6. Never disclose passwords or MFA codes.
7. Follow established verification procedures.
8. Report suspicious calls to the appropriate security team.

Employees should remember that caller ID alone is not sufficient proof of identity because attackers may manipulate caller identification information.

---

## Smishing

Smishing is a form of phishing conducted through SMS or mobile messaging platforms.

The term combines **SMS** and **phishing**.

Smishing messages are commonly designed to encourage the victim to:

* Click a malicious link.
* Download an application.
* Provide credentials.
* Confirm personal information.
* Make a payment.
* Contact a fraudulent telephone number.
* Provide authentication information.

---

## Common Smishing Scenarios

Attackers may impersonate:

* Banks.
* Delivery companies.
* Government agencies.
* Mobile operators.
* Online retailers.
* Cloud service providers.
* Financial institutions.
* Employers.

Examples include:

> "Your package could not be delivered. Confirm your delivery address using the link below."

Or:

> "Your bank account has been temporarily restricted. Verify your identity immediately."

The message creates urgency and provides a simple action for the victim to take.

---

## Smishing Warning Signs

Employees should be cautious when an unexpected message:

* Contains a suspicious link.
* Requests personal information.
* Requests payment.
* Claims an account is suspended.
* Creates unusual urgency.
* Comes from an unknown number.
* Uses a shortened URL.
* Requests installation of an unfamiliar application.
* Instructs the recipient to bypass normal procedures.

Employees should avoid using links or telephone numbers provided in suspicious messages.

Instead, they should access the organization's official website or use a trusted contact method.

---

## Mobile Devices and Smishing Risk

Smishing can be particularly effective because mobile devices are frequently used for rapid communication.

Employees may also have less visibility into:

* Full URLs.
* Sender information.
* Security warnings.
* Domain names.
* Message headers.

Mobile users may therefore interact with malicious content before carefully evaluating it.

Security awareness programs should specifically address mobile-based threats rather than focusing exclusively on desktop email phishing.

---

## Business Email Compromise

Business Email Compromise (BEC) is a type of cyber-enabled fraud in which attackers impersonate or compromise trusted business identities to deceive employees and cause unauthorized financial or information-related actions.

BEC attacks often target:

* Finance departments.
* Procurement teams.
* Accounts payable personnel.
* Executives.
* Human Resources.
* Payroll departments.
* Vendor management teams.

The attacker may use:

* A compromised legitimate mailbox.
* A look-alike domain.
* A spoofed email address.
* A newly created fraudulent account.
* Stolen credentials.
* Information gathered through reconnaissance.

---

## Common BEC Scenarios

### Executive Impersonation

An attacker impersonates a senior executive and requests an urgent payment.

Example:

> "I'm currently traveling and need this supplier payment processed immediately."

The attacker exploits authority and urgency.

### Supplier Account Change

An attacker impersonates a supplier and requests a change to banking information.

Example:

> "Please update our bank details for all future invoices."

If the change is processed without verification, legitimate payments may be redirected to the attacker.

### Invoice Fraud

An attacker sends a fraudulent invoice or modifies a legitimate invoice.

The invoice may contain:

* Real supplier information.
* Correct purchase order numbers.
* Accurate employee names.
* Real project information.

This makes the fraudulent request more difficult to identify.

### Payroll Fraud

An attacker impersonates an employee and requests a change to their payroll account.

The objective is to redirect salary payments to an account controlled by the attacker.

### Sensitive Information Theft

BEC may also be used to obtain:

* Customer information.
* Employee information.
* Financial records.
* Contracts.
* Business plans.
* Credentials.
* Intellectual property.

---

## Why BEC Is Dangerous

BEC attacks can bypass many technical security controls because the attacker may not need to deliver malware.

Instead, the attacker manipulates an employee into performing a legitimate business action.

For example:

```text
Attacker
   │
   ▼
Research Organization
   │
   ▼
Identify Executive / Supplier
   │
   ▼
Impersonate Trusted Person
   │
   ▼
Send Fraudulent Request
   │
   ▼
Employee Trusts Request
   │
   ▼
Payment / Data Disclosure
   │
   ▼
Financial or Business Loss
```

This makes business processes and employee verification procedures critical security controls.

---

## BEC Red Flags

Employees should apply additional verification when an email requests:

* A change to bank account information.
* An urgent payment.
* A payment outside normal procedures.
* Confidential information.
* Payroll changes.
* Gift card purchases.
* Unusual wire transfers.
* Changes to supplier information.
* Bypassing established approval processes.

The greater the potential impact of the requested action, the stronger the verification should be.

---

## Independent Verification

Independent verification is one of the most important defenses against vishing, smishing, and BEC.

Verification should use a trusted communication channel that is independent from the suspicious request.

For example:

```text
Suspicious Email
      │
      ▼
Do Not Reply Immediately
      │
      ▼
Use Trusted Contact Information
      │
      ▼
Contact Requester Independently
      │
      ▼
Verify Request
      │
      ├───────────────┐
      │               │
   Legitimate       Fraudulent
      │               │
      ▼               ▼
Proceed Normally   Report Incident
```

Employees should not use the telephone number, email address, or link provided in a suspicious communication for verification.

---

## Comparison of Vishing, Smishing, and BEC

| Characteristic           | Vishing                       | Smishing                            | BEC                                 |
| ------------------------ | ----------------------------- | ----------------------------------- | ----------------------------------- |
| Primary Channel          | Telephone / Voice             | SMS / Messaging                     | Email / Business communication      |
| Typical Target           | Employees, customers          | Mobile users                        | Businesses and employees            |
| Common Objective         | Credentials, MFA, information | Credentials, malware, payment       | Financial fraud, data theft         |
| Common Technique         | Impersonation and urgency     | Malicious links and urgency         | Executive or supplier impersonation |
| Common High-Risk Targets | IT, finance, executives       | General users                       | Finance, procurement, executives    |
| Verification Method      | Independent call-back         | Official website or trusted contact | Independent business verification   |

These techniques can also be combined.

For example, an attacker may first send a smishing message and then call the victim to persuade them to provide the requested information.

---

## Combined Social Engineering Attacks

Modern attackers may combine multiple communication methods.

A possible attack sequence could be:

1. The attacker sends a fraudulent SMS.
2. The victim clicks the link.
3. The attacker obtains information from the victim.
4. The attacker calls the victim pretending to be IT support.
5. The attacker requests an MFA code.
6. The attacker attempts to access the employee's account.
7. The attacker uses the compromised account to conduct further attacks.

This combination is sometimes more effective than using a single communication channel because each interaction can reinforce the credibility of the previous one.

---

## Employee Responsibilities

Employees should:

* Treat unexpected calls and messages cautiously.
* Never provide passwords or MFA codes.
* Avoid clicking suspicious SMS links.
* Independently verify financial requests.
* Verify supplier bank account changes.
* Follow established approval procedures.
* Report suspicious communications.
* Preserve relevant information when instructed.
* Cooperate with security investigations.

Employees should remember that a legitimate-looking communication can still be fraudulent.

---

## Organizational Controls

Organizations should implement multiple layers of protection.

Important controls include:

* Security awareness training.
* Phishing and social engineering simulations.
* Strong authentication.
* MFA.
* Email security controls.
* Domain protection.
* Secure payment procedures.
* Dual approval for high-value transactions.
* Independent verification of bank changes.
* Vendor verification procedures.
* Incident reporting mechanisms.
* Monitoring for suspicious account activity.

Financial and high-impact business processes should receive particular attention because successful social engineering attacks can cause significant financial and operational damage.

---

## GRC Perspective

Vishing, smishing, and BEC represent significant Governance, Risk, and Compliance (GRC) risks because they can exploit weaknesses in human behavior and business processes.

### Governance

Governance should establish:

* Communication security policies.
* Employee responsibilities.
* Financial approval procedures.
* Supplier verification requirements.
* Incident reporting requirements.
* Executive protection measures.
* Authentication requirements.

### Risk Management

Organizations should assess:

* Which employees are most frequently targeted.
* Which departments can authorize payments.
* Which employees have privileged access.
* Which suppliers are high risk.
* Which business processes can be manipulated.
* Historical fraud and social engineering incidents.
* Results of awareness exercises.

Risk assessments should consider both technical and human factors.

### Compliance

Awareness and controls for vishing, smishing, and BEC support requirements associated with:

* ISO/IEC 27001:2022 Information Security Management System (ISMS).
* ISO/IEC 27002:2022 Information Security Controls.
* NIST Cybersecurity Framework (CSF) 2.0.
* NIST SP 800-50, Building an Information Technology Security Awareness and Training Program.
* General Data Protection Regulation (GDPR).
* NIS2 Directive.
* Financial-sector requirements.
* Industry-specific cybersecurity regulations.

Evidence may include:

* Security awareness records.
* Incident reports.
* Phishing and smishing simulation results.
* Vendor verification records.
* Financial approval records.
* Security policies.
* Risk assessments.
* Corrective action records.
* Management reviews.

---

## Diagram Placeholder

**Title:** Multi-Channel Social Engineering Attack

**Diagram Description:**

```text
             Attacker
                │
       ┌────────┼────────┐
       │        │        │
       ▼        ▼        ▼
    Vishing  Smishing   BEC
       │        │        │
       └────────┼────────┘
                │
                ▼
        Employee Manipulation
                │
                ▼
       Unauthorized Action
                │
       ┌────────┼────────┐
       │        │        │
       ▼        ▼        ▼
    Account   Financial   Data
   Compromise   Loss      Theft
```

**Caption:**

*"Attackers can use multiple communication channels to manipulate employees and bypass technical and procedural security controls."*

---

## Practical Example

A Finance Manager receives an SMS claiming that a supplier's payment account has been suspended and that an urgent verification is required. The message contains a link to a website that appears to belong to the organization's banking provider.

The Finance Manager does not click the link. Shortly afterward, the employee receives a telephone call from someone claiming to be from the company's bank. The caller explains that the SMS was legitimate and asks the Finance Manager to provide an MFA verification code.

The employee recognizes the combination of smishing and vishing techniques. Instead of providing the code, the employee ends the call and contacts the bank through an independently verified telephone number.

The bank confirms that neither the SMS nor the telephone call originated from them.

The Finance Manager reports the incident to the organization's Security team. The Security team identifies the attack as a coordinated social engineering campaign and alerts other employees who may be targeted.

This example demonstrates how attackers can combine multiple communication channels to increase credibility and pressure victims into taking unsafe actions.

---

## Key Takeaways

* Vishing uses telephone or voice communication to manipulate victims.
* Smishing uses SMS or messaging platforms to conduct phishing attacks.
* Business Email Compromise (BEC) uses impersonation or compromised business communications to facilitate fraud or information theft.
* Attackers commonly exploit authority, urgency, fear, trust, and familiarity.
* BEC frequently targets finance, procurement, payroll, executives, and vendor management processes.
* Employees should never provide passwords or MFA codes in response to unexpected requests.
* Financial requests and changes to supplier or employee banking information should be independently verified.
* Attackers may combine vishing, smishing, phishing, and BEC techniques within a single campaign.
* From a Governance, Risk, and Compliance (GRC) perspective, effective controls require defined policies, strong verification procedures, employee awareness, risk assessments, incident reporting, and documented evidence of continual improvement.


