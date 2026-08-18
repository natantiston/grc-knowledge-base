# 20.9 PCI DSS Terms

This section defines the core terminology associated with the **Payment Card Industry Data Security Standard (PCI DSS)**, payment card security, cardholder data, sensitive authentication data, merchants, service providers, scope, requirements, validation, assessments, and compliance.

> **Terminology note:** PCI DSS is a global payment-card security standard maintained by the **PCI Security Standards Council (PCI SSC)**. **PCI DSS v4.0.1** is the current revision of the standard and should be used as the primary reference point for modern PCI DSS terminology.

---

# PCI DSS Glossary

| Term                                                         | Definition                                                                                                                                                                                                |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **PCI DSS**                                                  | Payment Card Industry Data Security Standard, a global security standard containing technical and operational requirements designed to protect payment account data.                                      |
| **PCI SSC**                                                  | Payment Card Industry Security Standards Council, the organization responsible for developing and maintaining PCI Standards, including PCI DSS.                                                           |
| **PCI DSS v4.0.1**                                           | The current revision of PCI DSS v4.0, incorporating clarifications and corrections to the standard.                                                                                                       |
| **Payment Brand**                                            | A payment card organization participating in the PCI SSC, such as Visa, Mastercard, American Express, Discover, or JCB.                                                                                   |
| **Merchant**                                                 | An entity that accepts payment cards or payment account information for payment of goods or services.                                                                                                     |
| **Service Provider**                                         | An entity that is not a payment brand and is directly involved in processing, storing, or transmitting cardholder data on behalf of another entity, or that could affect the security of cardholder data. |
| **Acquirer**                                                 | A financial institution or payment processor that establishes and maintains relationships with merchants for accepting payment card transactions.                                                         |
| **Issuer**                                                   | A financial institution or other entity that issues payment cards to cardholders.                                                                                                                         |
| **Cardholder**                                               | A person to whom a payment card is issued or an additional authorized user of the card.                                                                                                                   |
| **Payment Account Data**                                     | Data associated with a payment account, including cardholder data and/or sensitive authentication data.                                                                                                   |
| **Cardholder Data (CHD)**                                    | At a minimum, the full PAN and may also include cardholder name, expiration date, and service code when associated with the PAN.                                                                          |
| **Primary Account Number (PAN)**                             | The unique payment card number that identifies the cardholder account.                                                                                                                                    |
| **Sensitive Authentication Data (SAD)**                      | Security-related authentication information used to authenticate cardholders or authorize payment transactions, such as full track data, card verification codes, and PIN-related data.                   |
| **Full Track Data**                                          | Data encoded on the magnetic stripe or equivalent data on a chip that can be used to perform payment transactions.                                                                                        |
| **Card Verification Code**                                   | A value used to verify that a payment card is physically present or that the transaction is authorized, such as CVV, CVC, CID, or CAV2.                                                                   |
| **PIN**                                                      | Personal Identification Number used to authenticate a cardholder during certain payment transactions.                                                                                                     |
| **PIN Block**                                                | Encrypted representation of a PIN used for secure transmission or processing.                                                                                                                             |
| **Stored Cardholder Data**                                   | Cardholder data retained in any electronic or physical form after a payment transaction.                                                                                                                  |
| **Truncated PAN**                                            | A PAN that has been shortened by removing or masking portions of the number.                                                                                                                              |
| **Masked PAN**                                               | A PAN displayed with portions hidden to prevent unauthorized viewing.                                                                                                                                     |
| **Unencrypted PAN**                                          | A PAN stored or transmitted without appropriate cryptographic protection.                                                                                                                                 |
| **Strong Cryptography**                                      | Cryptographic algorithms and key strengths considered sufficiently resistant to practical cryptanalytic attacks for the intended purpose.                                                                 |
| **Encryption**                                               | The process of transforming information into an unreadable form using cryptographic techniques.                                                                                                           |
| **Tokenization**                                             | A process that replaces sensitive payment data with a non-sensitive substitute value called a token.                                                                                                      |
| **Token**                                                    | A value that substitutes for a PAN or other sensitive data and has limited or no value outside the intended tokenization system.                                                                          |
| **Payment Tokenization**                                     | Tokenization specifically applied to payment account data, typically replacing PANs with tokens.                                                                                                          |
| **Cryptographic Key**                                        | A value used by a cryptographic algorithm to encrypt, decrypt, authenticate, or otherwise protect information.                                                                                            |
| **Key Management**                                           | Processes for generating, distributing, storing, rotating, retiring, revoking, and destroying cryptographic keys.                                                                                         |
| **Key Encryption Key (KEK)**                                 | A cryptographic key used to encrypt or protect another cryptographic key.                                                                                                                                 |
| **Data Encryption Key (DEK)**                                | A cryptographic key used to encrypt data.                                                                                                                                                                 |
| **Key Rotation**                                             | The controlled replacement of cryptographic keys according to defined requirements or lifecycle events.                                                                                                   |
| **Key Custodian**                                            | An individual responsible for performing key-management responsibilities.                                                                                                                                 |
| **Cardholder Data Environment (CDE)**                        | The people, processes, and technologies that store, process, or transmit cardholder data or sensitive authentication data, or that could affect the security of the CDE.                                  |
| **CDE Scope**                                                | The systems, networks, applications, people, processes, and components subject to PCI DSS requirements because of their relationship to the CDE.                                                          |
| **In-Scope System**                                          | A system, application, network, process, or component subject to PCI DSS requirements.                                                                                                                    |
| **Out-of-Scope System**                                      | A system or component determined not to be subject to PCI DSS requirements based on documented scope analysis and appropriate isolation.                                                                  |
| **Scope**                                                    | The boundaries defining which people, processes, technologies, networks, systems, applications, and locations are subject to PCI DSS.                                                                     |
| **Scope Reduction**                                          | Architectural or procedural measures that legitimately reduce the number of systems or components subject to PCI DSS requirements.                                                                        |
| **Segmentation**                                             | Logical or physical separation of systems, networks, or environments to control communication and potentially reduce PCI DSS scope.                                                                       |
| **Network Segmentation**                                     | Isolation of networks or network components using controls such as firewalls, access controls, VLANs, or other mechanisms.                                                                                |
| **Segmentation Control**                                     | A technical or procedural control used to isolate the CDE from systems that do not require access to cardholder data.                                                                                     |
| **Connected-to System**                                      | A system or component capable of communicating with or affecting the security of the CDE.                                                                                                                 |
| **Security Impacting System**                                | A system that may affect the security of the CDE even if it does not directly store, process, or transmit cardholder data.                                                                                |
| **Trusted Network**                                          | A network that is within the organization's security boundary and has defined security controls.                                                                                                          |
| **Untrusted Network**                                        | A network outside the organization's security control or one that cannot be considered trusted.                                                                                                           |
| **Wireless Network**                                         | A network using wireless communications technologies to connect devices and systems.                                                                                                                      |
| **Public-Facing System**                                     | A system, application, or service accessible from an untrusted public network such as the Internet.                                                                                                       |
| **Firewall**                                                 | A security mechanism that controls network traffic between networks or security zones based on defined rules.                                                                                             |
| **Network Security Control (NSC)**                           | A network security technology or process used to control and protect network traffic and boundaries.                                                                                                      |
| **Router**                                                   | A network device that forwards traffic between networks.                                                                                                                                                  |
| **Security Group**                                           | A logical set of rules controlling network traffic to or from resources, commonly used in cloud environments.                                                                                             |
| **Wireless Access Point**                                    | A device that enables wireless network connectivity.                                                                                                                                                      |
| **Virtualization**                                           | Technology that creates virtual versions of computing resources such as servers, networks, storage, or operating systems.                                                                                 |
| **Cloud Computing**                                          | A model for providing scalable computing resources and services over a network, typically through shared or virtualized infrastructure.                                                                   |
| **Cloud Service Provider (CSP)**                             | An organization providing cloud computing services that may host, process, store, or transmit payment account data or support PCI DSS requirements.                                                       |
| **Shared Responsibility**                                    | A model in which the cloud service provider and customer each have defined security responsibilities.                                                                                                     |
| **Hosted Payment Page**                                      | A payment page hosted or operated by a third party or payment service provider rather than directly by the merchant.                                                                                      |
| **Payment Application**                                      | Software involved in processing, storing, transmitting, or supporting payment transactions.                                                                                                               |
| **Custom Software**                                          | Software developed specifically for an organization or environment rather than acquired as a standard commercial product.                                                                                 |
| **Bespoke Software**                                         | Software developed specifically for a particular organization or purpose.                                                                                                                                 |
| **Off-the-Shelf Software**                                   | Commercial software designed for general use rather than specifically developed for one organization.                                                                                                     |
| **Web Application**                                          | An application accessed through a web browser or web-based interface.                                                                                                                                     |
| **Application Security**                                     | Practices and controls used to protect applications from vulnerabilities, unauthorized access, misuse, and attacks.                                                                                       |
| **Secure Software Development Lifecycle (Secure SDLC)**      | Processes for integrating security practices throughout software planning, development, testing, deployment, maintenance, and retirement.                                                                 |
| **Change Management**                                        | Formal processes for requesting, assessing, approving, implementing, documenting, and reviewing changes to systems and environments.                                                                      |
| **Significant Change**                                       | A change that could affect the security or PCI DSS compliance status of the CDE and therefore requires appropriate assessment and validation.                                                             |
| **Configuration Standard**                                   | A documented baseline specifying secure configuration requirements for systems and technologies.                                                                                                          |
| **Vendor-Supplied Default**                                  | Default credentials, configurations, settings, accounts, or security parameters provided by a technology vendor.                                                                                          |
| **Default Password**                                         | A password provided by a vendor or manufacturer that has not been appropriately changed before use.                                                                                                       |
| **Hardening**                                                | The process of reducing vulnerabilities and unnecessary functionality through secure configuration and system controls.                                                                                   |
| **System Component**                                         | Any network component, server, computing device, application, or other component included in the PCI DSS scope.                                                                                           |
| **Network Component**                                        | Devices or technologies that facilitate communication, such as firewalls, routers, switches, wireless access points, and network appliances.                                                              |
| **Server**                                                   | A system that provides services or resources to other systems or users.                                                                                                                                   |
| **Endpoint**                                                 | A device or system that connects to a network or processes organizational information.                                                                                                                    |
| **Workstation**                                              | A user-operated computing device that may access organizational systems or data.                                                                                                                          |
| **Malware**                                                  | Malicious software designed to perform unauthorized or harmful actions.                                                                                                                                   |
| **Anti-Malware**                                             | Security technologies designed to detect, prevent, contain, or remove malicious software.                                                                                                                 |
| **Vulnerability**                                            | A weakness that could be exploited by a threat to compromise the confidentiality, integrity, or availability of systems or data.                                                                          |
| **Vulnerability Scanning**                                   | Automated or semi-automated examination of systems and applications for known vulnerabilities.                                                                                                            |
| **Internal Vulnerability Scan**                              | Vulnerability scanning performed against systems within an organization's internal environment.                                                                                                           |
| **External Vulnerability Scan**                              | Vulnerability scanning performed against Internet-accessible or externally exposed systems.                                                                                                               |
| **Penetration Testing**                                      | Security testing designed to identify and exploit vulnerabilities to determine the potential impact of attacks.                                                                                           |
| **Penetration Testing Methodology**                          | A documented approach defining how penetration tests are planned, performed, analyzed, and reported.                                                                                                      |
| **Penetration Testing Segmentation Validation**              | Testing designed to verify that segmentation controls effectively isolate the CDE from other environments.                                                                                                |
| **Wireless Penetration Testing**                             | Security testing designed to identify weaknesses in wireless infrastructure and configurations.                                                                                                           |
| **Application Penetration Testing**                          | Testing designed to identify vulnerabilities in applications, including web applications and APIs.                                                                                                        |
| **External Penetration Test**                                | Penetration testing performed from outside the organization's network environment.                                                                                                                        |
| **Internal Penetration Test**                                | Penetration testing performed from within the organization's internal network environment.                                                                                                                |
| **Authenticated Scanning**                                   | Vulnerability scanning performed with authorized credentials to obtain deeper visibility into system vulnerabilities.                                                                                     |
| **Uncredentialed Scanning**                                  | Vulnerability scanning performed without authenticated access to the target system.                                                                                                                       |
| **Logging**                                                  | Recording system, security, application, and user activities for monitoring, investigation, and accountability.                                                                                           |
| **Audit Log**                                                | A record of activities that can be used to establish what occurred, when it occurred, and potentially who performed the activity.                                                                         |
| **Audit Trail**                                              | A chronological record that supports reconstruction and investigation of system or user activity.                                                                                                         |
| **Security Event**                                           | An observable occurrence that may have security relevance.                                                                                                                                                |
| **Time Synchronization**                                     | Coordinating system clocks to a consistent and trusted time source.                                                                                                                                       |
| **Log Review**                                               | Examination of logs to identify suspicious, unauthorized, or anomalous activity.                                                                                                                          |
| **Centralized Logging**                                      | Collection of logs from multiple systems into a centralized repository or platform.                                                                                                                       |
| **Security Information and Event Management (SIEM)**         | A platform that collects, correlates, analyzes, and monitors security events and logs.                                                                                                                    |
| **File Integrity Monitoring (FIM)**                          | Technology or processes that detect unauthorized modification of critical files, configurations, or system components.                                                                                    |
| **Intrusion Detection System (IDS)**                         | Technology designed to detect suspicious or malicious network or system activity.                                                                                                                         |
| **Intrusion Prevention System (IPS)**                        | Technology designed to detect and actively prevent or block malicious network or system activity.                                                                                                         |
| **Anti-Phishing**                                            | Security measures designed to prevent or detect fraudulent attempts to obtain credentials, payment information, or other sensitive data.                                                                  |
| **Multi-Factor Authentication (MFA)**                        | Authentication requiring two or more independent authentication factors.                                                                                                                                  |
| **Authentication Factor**                                    | Something a user knows, has, or is, used to authenticate identity.                                                                                                                                        |
| **Password**                                                 | A secret authentication value used to verify identity.                                                                                                                                                    |
| **Passphrase**                                               | A longer sequence of words or characters used as an authentication secret.                                                                                                                                |
| **Service Account**                                          | An account used by an application, service, process, or system rather than an individual user.                                                                                                            |
| **Privileged User**                                          | A user with elevated permissions that allow administrative or security-sensitive actions.                                                                                                                 |
| **Remote Access**                                            | Access to organizational systems or networks from an external location.                                                                                                                                   |
| **Remote Administration**                                    | Administrative access to systems from a remote location.                                                                                                                                                  |
| **Vendor Remote Access**                                     | Remote access provided to third-party vendors or service providers for support, maintenance, or administration.                                                                                           |
| **Need-to-Know**                                             | Principle that access to information is granted only when required for legitimate business purposes.                                                                                                      |
| **Least Privilege**                                          | Principle that users and systems receive only the permissions necessary to perform authorized tasks.                                                                                                      |
| **Physical Security**                                        | Controls designed to prevent unauthorized physical access to facilities, systems, equipment, and data.                                                                                                    |
| **Media**                                                    | Physical or electronic devices used to store information.                                                                                                                                                 |
| **Electronic Media**                                         | Digitally encoded storage media such as hard drives, SSDs, USB devices, and backup media.                                                                                                                 |
| **Hard-Copy Media**                                          | Physical documents or printed materials containing information.                                                                                                                                           |
| **Media Destruction**                                        | Secure destruction of media to prevent recovery of sensitive information.                                                                                                                                 |
| **Media Inventory**                                          | A maintained record of relevant media containing cardholder data.                                                                                                                                         |
| **Retention Period**                                         | The defined period for which information is retained before secure disposal.                                                                                                                              |
| **Secure Disposal**                                          | Destruction or deletion of information so that it cannot be reconstructed or recovered using reasonable methods.                                                                                          |
| **Information Security Policy**                              | A formally approved policy establishing an organization's information-security requirements and expectations.                                                                                             |
| **Acceptable Use Policy**                                    | A policy defining permitted and prohibited use of organizational systems, devices, networks, applications, and information.                                                                               |
| **Incident Response Plan**                                   | A documented plan defining responsibilities, procedures, communication, containment, investigation, recovery, and escalation for security incidents.                                                      |
| **Incident Response Team (IRT)**                             | A designated group responsible for responding to cybersecurity incidents.                                                                                                                                 |
| **Incident Response Testing**                                | Testing of incident-response procedures to verify readiness and effectiveness.                                                                                                                            |
| **Security Awareness Program**                               | A structured program designed to educate personnel about security risks, policies, responsibilities, and expected behaviors.                                                                              |
| **Security Training**                                        | Training designed to provide personnel with security knowledge and skills appropriate to their responsibilities.                                                                                          |
| **Security Responsibility**                                  | A formally assigned obligation to perform or oversee a security-related activity.                                                                                                                         |
| **Third Party**                                              | An external organization or entity that provides services, technology, products, or other capabilities to the organization.                                                                               |
| **Third-Party Service Provider (TPSP)**                      | An external entity providing services that could affect the security of cardholder data or the CDE.                                                                                                       |
| **Service Provider Compliance**                              | The provider's demonstrated compliance with applicable PCI DSS requirements.                                                                                                                              |
| **Responsibility Matrix**                                    | Documentation defining which PCI DSS responsibilities belong to the merchant, service provider, or other parties.                                                                                         |
| **Compensating Control**                                     | An alternative control used when an organization cannot meet a specified PCI DSS requirement as written, provided the alternative control meets the defined PCI DSS criteria.                             |
| **Customized Approach**                                      | A PCI DSS v4.x approach that allows an entity to meet a requirement's stated security objective through a customized implementation rather than following the defined approach.                           |
| **Defined Approach**                                         | The standard implementation approach for meeting a PCI DSS requirement using the specified requirements and testing procedures.                                                                           |
| **Customized Approach Objective**                            | The security objective associated with a PCI DSS requirement that must be achieved when using the customized approach.                                                                                    |
| **Targeted Risk Analysis (TRA)**                             | A documented risk analysis used to determine appropriate frequency or flexibility for certain PCI DSS activities where the standard permits an entity to define its own frequency or approach.            |
| **Risk Assessment**                                          | A process for identifying, analyzing, and evaluating risks.                                                                                                                                               |
| **Risk Analysis**                                            | Examination of risk characteristics, including likelihood, impact, threats, vulnerabilities, and other relevant factors.                                                                                  |
| **PCI DSS Requirement**                                      | A specific security requirement established by PCI DSS that an applicable entity must satisfy.                                                                                                            |
| **PCI DSS Testing Procedure**                                | The procedure used by an assessor or entity to determine whether a PCI DSS requirement is met.                                                                                                            |
| **Customized Testing Procedure**                             | Testing performed to determine whether the security objective of a customized PCI DSS implementation is achieved.                                                                                         |
| **Security Objective**                                       | The security outcome that a PCI DSS requirement or customized control is intended to achieve.                                                                                                             |
| **Evidence**                                                 | Documentation, records, configurations, logs, interviews, observations, or other information demonstrating that PCI DSS requirements have been implemented.                                               |
| **Compliance Validation**                                    | The process of demonstrating conformity with applicable PCI DSS requirements.                                                                                                                             |
| **Self-Assessment Questionnaire (SAQ)**                      | A PCI SSC questionnaire used by eligible entities to assess and report their compliance with applicable PCI DSS requirements.                                                                             |
| **Attestation of Compliance (AOC)**                          | A formal document used to attest to an entity's or service provider's PCI DSS compliance status.                                                                                                          |
| **Attestation of Validation**                                | Formal confirmation by an entity or assessor that applicable PCI DSS validation activities have been completed.                                                                                           |
| **Report on Compliance (ROC)**                               | A formal report documenting the results of a PCI DSS assessment, typically completed by a Qualified Security Assessor (QSA).                                                                              |
| **Qualified Security Assessor (QSA)**                        | A professional qualified by the PCI SSC to assess PCI DSS compliance.                                                                                                                                     |
| **Internal Security Assessor (ISA)**                         | An individual qualified through the PCI SSC ISA program to support an organization's PCI DSS compliance efforts and internal assessment activities.                                                       |
| **Qualified Internal Security Assessor (QISA)**              | A PCI SSC qualification framework for individuals performing internal PCI DSS assessments within eligible organizations.                                                                                  |
| **Approved Scanning Vendor (ASV)**                           | A PCI SSC-approved organization authorized to conduct external vulnerability scanning for PCI DSS purposes.                                                                                               |
| **PCI Forensic Investigator (PFI)**                          | A PCI SSC-qualified organization or professional authorized to conduct forensic investigations under applicable PCI SSC programs.                                                                         |
| **PCI Professional (PCIP)**                                  | An individual who has completed the PCI SSC Professional (PCIP) qualification program.                                                                                                                    |
| **Payment Application Qualified Security Assessor (PA-QSA)** | A PCI SSC-qualified assessor authorized to assess payment applications against applicable PCI standards.                                                                                                  |
| **Point-to-Point Encryption (P2PE)**                         | A solution designed to encrypt payment account data securely from the point of interaction to a secure decryption environment.                                                                            |
| **PCI-Listed P2PE Solution**                                 | A payment encryption solution validated and listed by the PCI SSC under its P2PE program.                                                                                                                 |
| **Point of Interaction (POI)**                               | The physical or logical location where payment account data is entered or captured.                                                                                                                       |
| **Payment Terminal**                                         | A device used to accept payment card transactions.                                                                                                                                                        |
| **Point-of-Sale (POS)**                                      | Hardware and software used to conduct and process payment transactions.                                                                                                                                   |
| **PIN Entry Device (PED)**                                   | A device designed to securely accept PINs during payment transactions.                                                                                                                                    |
| **Cardholder Data Flow**                                     | The movement of cardholder data through systems, applications, networks, people, and external services.                                                                                                   |
| **Data Flow Diagram (DFD)**                                  | A visual representation showing how data moves between systems, processes, users, networks, and other components.                                                                                         |
| **CDE Data Flow Diagram**                                    | A diagram specifically documenting the flow of cardholder data through the Cardholder Data Environment.                                                                                                   |
| **Network Diagram**                                          | A documented representation of network architecture, connectivity, segmentation, and relevant security boundaries.                                                                                        |
| **System Inventory**                                         | A maintained list of systems and components relevant to the organization's environment and PCI DSS scope.                                                                                                 |
| **Software Inventory**                                       | A maintained record of software applications and components deployed within relevant environments.                                                                                                        |
| **Scope Validation**                                         | Activities performed to confirm that the PCI DSS scope accurately identifies all relevant systems, processes, people, networks, and dependencies.                                                         |
| **Scope Reduction**                                          | Reduction of PCI DSS scope through appropriate technologies, processes, segmentation, tokenization, or other measures.                                                                                    |
| **Cardholder Data Storage**                                  | Retention of cardholder data in any electronic or physical form.                                                                                                                                          |
| **Cardholder Data Transmission**                             | Movement of cardholder data between systems, networks, applications, devices, or organizations.                                                                                                           |
| **Cardholder Data Processing**                               | Activities performed on cardholder data, including collection, transformation, authorization, analysis, or transaction processing.                                                                        |
| **Data-at-Rest**                                             | Data stored on systems, databases, files, devices, or other storage media.                                                                                                                                |
| **Data-in-Transit**                                          | Data transmitted across networks or communication channels.                                                                                                                                               |
| **Data-in-Use**                                              | Data actively being processed or accessed by a system or application.                                                                                                                                     |
| **Secure Transmission**                                      | Transmission of data using appropriate cryptographic or security mechanisms to protect against unauthorized disclosure or modification.                                                                   |
| **Wireless Security**                                        | Security controls protecting wireless networks and communications from unauthorized access, interception, and attack.                                                                                     |
| **Mobile Computing Device**                                  | A portable computing device such as a laptop, tablet, or smartphone.                                                                                                                                      |
| **Bring Your Own Device (BYOD)**                             | Use of personally owned devices to access organizational systems or information.                                                                                                                          |
| **Remote Work**                                              | Performance of organizational activities outside controlled organizational facilities.                                                                                                                    |
| **Physical Access Control**                                  | Mechanisms restricting physical access to facilities, systems, equipment, or sensitive areas.                                                                                                             |
| **Visitor**                                                  | A person who is not an authorized employee or contractor with approved access to a controlled facility or area.                                                                                           |
| **Visitor Log**                                              | A record documenting visitor access to controlled facilities or areas.                                                                                                                                    |
| **Video Monitoring**                                         | Use of video surveillance systems to monitor physical areas and support security investigations.                                                                                                          |
| **Security Testing**                                         | Activities designed to identify vulnerabilities, weaknesses, control failures, or other security issues.                                                                                                  |
| **Internal Testing**                                         | Security testing performed from within an organization's controlled environment.                                                                                                                          |
| **External Testing**                                         | Security testing performed from outside the organization's controlled environment.                                                                                                                        |
| **Penetration Testing**                                      | Simulated attacks designed to identify and exploit vulnerabilities and evaluate the effectiveness of security controls.                                                                                   |
| **Wireless Testing**                                         | Security testing of wireless networks, configurations, authentication, encryption, and associated devices.                                                                                                |
| **Segmentation Testing**                                     | Testing to verify that segmentation mechanisms effectively isolate the CDE from other environments.                                                                                                       |
| **Security Control Validation**                              | Evaluation of whether security controls are correctly implemented and operating effectively.                                                                                                              |
| **Control Failure**                                          | A condition where a required security control is absent, improperly implemented, or ineffective.                                                                                                          |
| **Noncompliance**                                            | Failure to satisfy one or more applicable PCI DSS requirements.                                                                                                                                           |
| **Remediation**                                              | Corrective activities performed to address identified PCI DSS deficiencies, vulnerabilities, or control failures.                                                                                         |
| **Corrective Action**                                        | Action taken to eliminate the cause of a nonconformity or control deficiency and prevent recurrence.                                                                                                      |
| **Compensating Control Worksheet**                           | Documentation demonstrating how a compensating control satisfies the applicable PCI DSS criteria.                                                                                                         |
| **PCI DSS Scope Document**                                   | Documentation defining the systems, networks, applications, people, processes, and locations included in PCI DSS scope.                                                                                   |
| **PCI DSS Responsibility Matrix**                            | Documentation identifying which PCI DSS responsibilities are performed by the merchant, service provider, cloud provider, or other parties.                                                               |
| **Compliance Monitoring**                                    | Ongoing activities used to verify continued adherence to PCI DSS requirements.                                                                                                                            |
| **Annual Assessment**                                        | Periodic formal assessment of PCI DSS compliance, generally performed according to the applicable payment-brand and acquiring requirements.                                                               |
| **Quarterly External Vulnerability Scan**                    | Periodic external vulnerability scanning required in applicable PCI DSS circumstances.                                                                                                                    |
| **Evidence Retention**                                       | Preservation of records demonstrating PCI DSS compliance and control operation for the required period.                                                                                                   |
| **PCI DSS Scope Confirmation**                               | Formal confirmation that the organization's defined PCI DSS scope accurately reflects the actual cardholder data environment and relevant dependencies.                                                   |

---

# PCI DSS 12 Requirement Areas

For GRC purposes, PCI DSS terminology is easier to understand when the requirements are grouped by their security objectives.

| PCI DSS Area       | Primary Security Objective                                                                      |
| ------------------ | ----------------------------------------------------------------------------------------------- |
| **Requirement 1**  | Install and maintain network security controls                                                  |
| **Requirement 2**  | Apply secure configurations to all system components                                            |
| **Requirement 3**  | Protect stored account data                                                                     |
| **Requirement 4**  | Protect cardholder data with strong cryptography during transmission over open, public networks |
| **Requirement 5**  | Protect all systems and networks from malicious software                                        |
| **Requirement 6**  | Develop and maintain secure systems and software                                                |
| **Requirement 7**  | Restrict access to system components and cardholder data by business need to know               |
| **Requirement 8**  | Identify users and authenticate access to system components                                     |
| **Requirement 9**  | Restrict physical access to cardholder data                                                     |
| **Requirement 10** | Log and monitor all access to system components and cardholder data                             |
| **Requirement 11** | Regularly test security systems and processes                                                   |
| **Requirement 12** | Support information security with organizational policies and programs                          |

---

# PCI DSS v4.0.1 Key Concepts

## 1. Defined Approach

The **Defined Approach** is the traditional method for meeting a PCI DSS requirement.

The entity follows:

**PCI DSS Requirement → Defined Requirement → Defined Testing Procedure**

This provides a relatively standardized assessment method.

---

## 2. Customized Approach

PCI DSS v4.x introduced greater flexibility through the **Customized Approach**.

The organization can design an alternative control implementation provided that it demonstrates achievement of the relevant **security objective**.

The basic concept is:

> **Requirement → Security Objective → Customized Control → Evidence → Validation**

This is highly relevant to GRC because it allows organizations to design controls that better fit:

* cloud architectures;
* DevSecOps environments;
* modern payment architectures;
* zero-trust environments;
* automation;
* containerized platforms; and
* other complex technology environments.

---

# 3. Targeted Risk Analysis

A **Targeted Risk Analysis (TRA)** is used where PCI DSS permits an entity to determine an appropriate frequency or approach based on its own risk considerations.

A typical TRA should consider:

1. asset or activity;
2. threat;
3. vulnerability;
4. likelihood;
5. impact;
6. risk;
7. mitigating controls;
8. defined frequency;
9. responsible owner; and
10. periodic reassessment.

This is an important distinction from a general enterprise risk assessment.

---

# 4. Cardholder Data vs. Sensitive Authentication Data

This distinction is fundamental.

### Cardholder Data

May include:

* PAN;
* cardholder name;
* expiration date; and
* service code.

### Sensitive Authentication Data

May include:

* full track data;
* card verification codes;
* PINs;
* PIN blocks.

A critical PCI DSS principle is:

> **Sensitive authentication data must not be stored after authorization, even if encrypted, except where specifically permitted by PCI payment requirements.**

---

# 5. CDE Scope

A common GRC mistake is assuming:

> "If a server doesn't store cardholder data, it is automatically out of scope."

That is **not necessarily true**.

A system may remain in PCI DSS scope if it:

* processes cardholder data;
* transmits cardholder data;
* connects to the CDE;
* provides security services to the CDE;
* provides administrative services to the CDE; or
* can otherwise affect the security of the CDE.

Therefore, PCI DSS scope analysis must consider **connectivity and security impact**, not merely data storage.

---

# 6. PCI DSS Scope Reduction

Organizations frequently attempt to reduce PCI DSS scope through:

* network segmentation;
* tokenization;
* point-to-point encryption;
* hosted payment pages;
* outsourcing;
* cloud architecture;
* dedicated payment environments; and
* minimizing cardholder-data storage.

However:

> **Outsourcing a PCI DSS activity does not automatically eliminate the organization's PCI DSS responsibilities.**

The organization must understand:

* which activities are outsourced;
* which responsibilities remain internal;
* what the provider's PCI DSS responsibilities are;
* how the provider is validated; and
* how the services affect the CDE.

---

# 7. PCI DSS GRC Model

For a GRC professional, PCI DSS can be organized into the following governance lifecycle:

**PCI DSS Scope Definition**
↓
**Cardholder Data Flow Mapping**
↓
**Asset & System Inventory**
↓
**PCI DSS Risk Assessment**
↓
**Control Mapping**
↓
**Gap Assessment**
↓
**Remediation Plan**
↓
**Control Implementation**
↓
**Evidence Collection**
↓
**Testing & Validation**
↓
**ROC / SAQ / AOC**
↓
**Continuous Compliance Monitoring**

---

# 8. PCI DSS and Other GRC Frameworks

PCI DSS can be integrated into an enterprise GRC framework alongside:

| Framework          | Primary Focus                           |
| ------------------ | --------------------------------------- |
| **PCI DSS**        | Payment card security                   |
| **ISO/IEC 27001**  | Information security management         |
| **NIST CSF**       | Cybersecurity risk management           |
| **ISO 31000**      | Enterprise risk management              |
| **ISO 22301**      | Business continuity                     |
| **ISO/IEC 42001**  | AI management                           |
| **COBIT**          | Enterprise IT governance and management |
| **NIST SP 800-53** | Security and privacy controls           |
| **CIS Controls**   | Prioritized cybersecurity safeguards    |

The important GRC principle is:

> **PCI DSS defines payment-card security requirements, while the broader GRC framework provides the governance, risk, control, compliance, evidence, and assurance mechanisms used to manage those requirements.**

---

# Key PCI DSS Terms to Remember

For certification, interviews, audits, and practical GRC work, prioritize these terms:

**PCI DSS**
→ **PCI SSC**
→ **Cardholder Data (CHD)**
→ **Sensitive Authentication Data (SAD)**
→ **PAN**
→ **CDE**
→ **Merchant**
→ **Service Provider**
→ **Acquirer**
→ **Issuer**
→ **Scope**
→ **Network Segmentation**
→ **Tokenization**
→ **P2PE**
→ **Defined Approach**
→ **Customized Approach**
→ **Targeted Risk Analysis**
→ **Compensating Control**
→ **QSA**
→ **ASV**
→ **ROC**
→ **SAQ**
→ **AOC**
→ **Penetration Testing**
→ **Vulnerability Scanning**
→ **Evidence**
→ **Continuous Compliance**

These are among the most important terms for understanding **PCI DSS assessment, PCI compliance programs, payment security, third-party risk, audit evidence, and cybersecurity GRC**.


