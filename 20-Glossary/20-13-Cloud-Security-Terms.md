# 20.13 Cloud Security Terms

This section defines the core terminology associated with **Cloud Security, Cloud Governance, Cloud Risk Management, Cloud Architecture, Cloud Compliance, Cloud Identity, Cloud Data Protection, Cloud Security Operations, and Cloud Resilience**.

> **Terminology note:** Cloud terminology varies slightly across providers and frameworks. This glossary is designed for the GRC knowledge base and aligns broadly with concepts used by **NIST, ISO/IEC 27001, ISO/IEC 27017, ISO/IEC 27018, CSA, CIS, major cloud service providers, and common enterprise cloud-security practices**.

---

# Cloud Security Glossary

| Term                                                     | Definition                                                                                                                                                     |
| -------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cloud Computing**                                      | A model for providing on-demand access to shared computing resources such as servers, storage, networks, applications, and services.                           |
| **Cloud Security**                                       | The policies, technologies, processes, controls, and practices used to protect cloud environments, data, applications, identities, and services.               |
| **Cloud Security Governance**                            | The governance structure used to establish accountability, policies, risk management, compliance, and security requirements for cloud environments.            |
| **Cloud Governance**                                     | The framework of decision rights, policies, standards, processes, and controls governing the use and management of cloud services.                             |
| **Cloud Risk Management**                                | The process of identifying, assessing, treating, monitoring, and reporting risks associated with cloud services and environments.                              |
| **Cloud Security Architecture**                          | The design of security controls and capabilities across cloud infrastructure, applications, identities, networks, data, and operations.                        |
| **Cloud Security Framework**                             | A structured set of principles, controls, processes, and practices used to manage cloud security.                                                              |
| **Cloud Security Policy**                                | An organizational policy defining requirements and expectations for secure use of cloud services.                                                              |
| **Cloud Service**                                        | A capability delivered through cloud computing infrastructure.                                                                                                 |
| **Cloud Service Provider (CSP)**                         | An organization that provides cloud computing services to customers.                                                                                           |
| **Cloud Customer**                                       | An organization or individual consuming cloud services from a provider.                                                                                        |
| **Cloud Consumer**                                       | Entity that uses or consumes a cloud service.                                                                                                                  |
| **Cloud Provider**                                       | Organization responsible for providing and operating cloud services.                                                                                           |
| **Cloud Broker**                                         | An entity that manages, integrates, aggregates, or facilitates cloud services between providers and consumers.                                                 |
| **Cloud Auditor**                                        | An independent party that evaluates cloud services, controls, compliance, or security.                                                                         |
| **Cloud Service Model**                                  | The classification of cloud services according to the responsibilities and capabilities provided by the cloud provider.                                        |
| **Infrastructure as a Service (IaaS)**                   | Cloud service model providing infrastructure resources such as virtual machines, storage, and networking.                                                      |
| **Platform as a Service (PaaS)**                         | Cloud service model providing managed platforms for application development and deployment.                                                                    |
| **Software as a Service (SaaS)**                         | Cloud service model in which applications are hosted and operated by a provider and delivered to customers over a network.                                     |
| **Function as a Service (FaaS)**                         | Cloud computing model in which customers execute application functions without managing underlying server infrastructure.                                      |
| **Serverless Computing**                                 | Cloud architecture in which the provider manages the underlying infrastructure and customers focus primarily on application logic or functions.                |
| **Anything as a Service (XaaS)**                         | General term describing technology capabilities delivered as cloud-based services.                                                                             |
| **Public Cloud**                                         | Cloud infrastructure made available to multiple customers and operated by a cloud provider.                                                                    |
| **Private Cloud**                                        | Cloud infrastructure dedicated to a single organization.                                                                                                       |
| **Hybrid Cloud**                                         | Environment combining private and public cloud capabilities with integration between them.                                                                     |
| **Community Cloud**                                      | Cloud environment shared by organizations with common requirements, such as regulatory or mission-specific requirements.                                       |
| **Multi-Cloud**                                          | Use of services from two or more cloud providers.                                                                                                              |
| **Single Cloud**                                         | Cloud architecture primarily dependent on one cloud provider.                                                                                                  |
| **Cloud-Native**                                         | Applications and architectures specifically designed to take advantage of cloud capabilities such as elasticity, automation, containers, and managed services. |
| **Cloud Migration**                                      | Process of moving applications, data, infrastructure, or workloads from one environment to another, including migration to cloud.                              |
| **Cloud Adoption**                                       | Organizational process of introducing and expanding the use of cloud technologies and services.                                                                |
| **Cloud Transformation**                                 | Broader organizational transformation involving architecture, operating models, processes, technology, and culture through cloud adoption.                     |
| **Cloud Workload**                                       | Application, service, process, or computing capability running within a cloud environment.                                                                     |
| **Cloud Resource**                                       | Computing, networking, storage, identity, application, or other resource provisioned in a cloud environment.                                                   |
| **Cloud Asset**                                          | A cloud resource or component that has value or requires protection.                                                                                           |
| **Cloud Account**                                        | Logical administrative boundary used to manage cloud resources, billing, access, and security.                                                                 |
| **Cloud Subscription**                                   | Customer-level organizational boundary used by some cloud providers to group and manage cloud resources and services.                                          |
| **Cloud Tenant**                                         | Logical environment assigned to a customer within a shared cloud platform.                                                                                     |
| **Multi-Tenancy**                                        | Architecture in which multiple customers share underlying cloud infrastructure while maintaining logical separation.                                           |
| **Tenant Isolation**                                     | Controls designed to prevent one cloud tenant from accessing another tenant's resources or data.                                                               |
| **Cloud Region**                                         | Geographic area containing one or more cloud provider infrastructure locations.                                                                                |
| **Availability Zone**                                    | Isolated cloud infrastructure location within a region designed to reduce the impact of localized failures.                                                    |
| **Cloud Data Center**                                    | Physical facility containing infrastructure used to deliver cloud services.                                                                                    |
| **Edge Computing**                                       | Processing data closer to where it is generated or consumed rather than relying entirely on centralized cloud infrastructure.                                  |
| **Cloud Availability**                                   | Degree to which cloud services are accessible and operational when required.                                                                                   |
| **Cloud Resilience**                                     | Ability of cloud services and workloads to withstand, adapt to, and recover from disruptions.                                                                  |
| **Cloud Disaster Recovery**                              | Use of cloud technologies and services to recover applications, systems, and data following disruptive events.                                                 |
| **Cloud Backup**                                         | Backup of data, systems, configurations, or workloads using cloud infrastructure or services.                                                                  |
| **Cloud Replication**                                    | Copying data, workloads, or services between cloud environments or locations.                                                                                  |
| **Cross-Region Replication**                             | Replication of data or workloads between geographically separated cloud regions.                                                                               |
| **Cross-Cloud Replication**                              | Replication between different cloud providers or cloud environments.                                                                                           |
| **Cloud Failover**                                       | Transfer of service operations from a failed cloud resource or environment to an alternate environment.                                                        |
| **Cloud Failback**                                       | Returning operations from a recovery cloud environment to the primary environment.                                                                             |
| **Cloud RTO**                                            | Target time within which a cloud-based workload or service must be restored following disruption.                                                              |
| **Cloud RPO**                                            | Maximum acceptable period of data loss for a cloud workload or service.                                                                                        |
| **Cloud Shared Responsibility Model**                    | Security model defining which security responsibilities are managed by the cloud provider and which remain with the customer.                                  |
| **Provider Responsibility**                              | Security and operational responsibilities managed by the cloud service provider.                                                                               |
| **Customer Responsibility**                              | Security and operational responsibilities that remain with the cloud customer.                                                                                 |
| **Shared Responsibility**                                | Security responsibilities jointly influenced or managed by both cloud provider and customer.                                                                   |
| **Responsibility Matrix**                                | Document mapping security, operational, compliance, and management responsibilities between cloud provider and customer.                                       |
| **Cloud Control Plane**                                  | Management layer through which cloud resources and services are provisioned, configured, and controlled.                                                       |
| **Cloud Data Plane**                                     | Layer responsible for processing or delivering actual workloads, data, and application traffic.                                                                |
| **Management Plane**                                     | Interfaces and services used to administer cloud resources and configurations.                                                                                 |
| **Control Plane Security**                               | Security measures protecting cloud management interfaces, administrative functions, APIs, and control mechanisms.                                              |
| **Cloud API**                                            | Application programming interface used to interact programmatically with cloud services and resources.                                                         |
| **API Security**                                         | Controls protecting APIs against unauthorized access, abuse, manipulation, and exploitation.                                                                   |
| **Cloud Console**                                        | Web-based interface used to administer cloud services and resources.                                                                                           |
| **Cloud CLI**                                            | Command-line interface used to manage cloud resources and services.                                                                                            |
| **Infrastructure as Code (IaC)**                         | Practice of defining and deploying infrastructure using machine-readable configuration files or code.                                                          |
| **Secure IaC**                                           | Application of security controls to infrastructure-as-code templates and deployment processes.                                                                 |
| **IaC Scanning**                                         | Automated analysis of infrastructure-as-code templates for security, compliance, configuration, and policy violations.                                         |
| **Configuration Management**                             | Process of defining, maintaining, monitoring, and controlling system and cloud configurations.                                                                 |
| **Cloud Configuration**                                  | Settings controlling the behavior, access, security, networking, and operation of cloud resources.                                                             |
| **Cloud Security Posture**                               | Overall security condition of a cloud environment based on its configurations, controls, vulnerabilities, identities, and risks.                               |
| **Cloud Security Posture Management (CSPM)**             | Technology and processes used to continuously identify and manage cloud security configuration risks and compliance issues.                                    |
| **Cloud Workload Protection Platform (CWPP)**            | Security capabilities designed to protect cloud workloads such as virtual machines, containers, and applications.                                              |
| **Cloud-Native Application Protection Platform (CNAPP)** | Integrated security approach combining capabilities such as CSPM, CWPP, CIEM, application security, and cloud workload protection.                             |
| **Cloud Infrastructure Entitlement Management (CIEM)**   | Security capability focused on managing and reducing excessive permissions and entitlements in cloud environments.                                             |
| **Cloud Detection and Response (CDR)**                   | Capabilities for detecting and responding to security threats within cloud environments.                                                                       |
| **Cloud Security Information and Event Management**      | Collection, correlation, monitoring, and analysis of cloud security events and logs.                                                                           |
| **Cloud Security Operations**                            | Processes for monitoring, detecting, investigating, responding to, and improving cloud security.                                                               |
| **Cloud Security Monitoring**                            | Continuous observation of cloud resources, configurations, identities, activities, and threats.                                                                |
| **Cloud Threat Detection**                               | Identification of malicious or suspicious activity in cloud environments.                                                                                      |
| **Cloud Incident Response**                              | Processes for detecting, containing, investigating, eradicating, and recovering from cloud security incidents.                                                 |
| **Cloud Forensics**                                      | Collection and analysis of evidence from cloud environments to investigate security incidents.                                                                 |
| **Cloud Logging**                                        | Recording cloud activities, events, configuration changes, authentication events, and other relevant activities.                                               |
| **Cloud Audit Logs**                                     | Logs recording administrative, security, API, and resource-management activities within cloud environments.                                                    |
| **Cloud Monitoring**                                     | Continuous observation of performance, availability, security, configurations, and operational activity.                                                       |
| **Cloud SIEM**                                           | Security information and event management capability designed to collect and analyze security telemetry from cloud and other environments.                     |
| **Cloud Security Analytics**                             | Analysis of cloud security data to identify anomalies, threats, vulnerabilities, and risks.                                                                    |
| **Cloud Threat Intelligence**                            | Intelligence concerning threats, vulnerabilities, attack techniques, and actors relevant to cloud environments.                                                |
| **Cloud Vulnerability Management**                       | Identification, prioritization, remediation, and monitoring of vulnerabilities affecting cloud workloads and services.                                         |
| **Cloud Vulnerability Scanning**                         | Automated or manual assessment of cloud resources for known vulnerabilities and security weaknesses.                                                           |
| **Cloud Penetration Testing**                            | Authorized security testing designed to identify vulnerabilities in cloud workloads, applications, APIs, networks, and configurations.                         |
| **Cloud Security Assessment**                            | Structured evaluation of cloud security controls, architecture, configuration, and risk.                                                                       |
| **Cloud Security Review**                                | Review of cloud architecture, configurations, controls, and security practices.                                                                                |
| **Cloud Compliance**                                     | Conformance of cloud services and environments with applicable laws, regulations, standards, policies, and contractual obligations.                            |
| **Cloud Compliance Monitoring**                          | Ongoing monitoring of cloud environments against defined regulatory, policy, and security requirements.                                                        |
| **Cloud Compliance Framework**                           | Set of requirements and controls used to evaluate and manage cloud compliance.                                                                                 |
| **Cloud Governance Framework**                           | Structured set of governance policies, processes, roles, and controls for cloud adoption and management.                                                       |
| **Cloud Policy**                                         | Rule defining acceptable configuration, usage, security, or operational requirements for cloud resources.                                                      |
| **Policy as Code (PaC)**                                 | Practice of expressing security, compliance, and governance policies in machine-readable form so they can be automatically enforced.                           |
| **Guardrail**                                            | Preventive or detective control designed to keep cloud usage within approved security, compliance, cost, or architectural boundaries.                          |
| **Preventive Guardrail**                                 | Control that prevents prohibited cloud configurations or actions.                                                                                              |
| **Detective Guardrail**                                  | Control that identifies violations after they occur or when they are detected.                                                                                 |
| **Cloud Landing Zone**                                   | Preconfigured cloud environment providing foundational governance, security, networking, identity, logging, and account structures for cloud workloads.        |
| **Secure Landing Zone**                                  | Cloud landing zone designed with security, compliance, identity, network, monitoring, and governance controls built into the foundation.                       |
| **Cloud Reference Architecture**                         | Standardized architectural model describing recommended cloud components, relationships, controls, and security patterns.                                      |
| **Cloud Architecture Review**                            | Formal assessment of a cloud architecture against security, compliance, resilience, performance, and governance requirements.                                  |
| **Zero Trust Cloud Security**                            | Application of zero-trust principles to cloud environments by continuously verifying identities, devices, workloads, applications, and access requests.        |
| **Identity and Access Management (IAM)**                 | Processes and technologies for managing identities, authentication, authorization, and access to cloud resources.                                              |
| **Cloud IAM**                                            | Identity and access management capabilities provided for cloud services and resources.                                                                         |
| **Identity Federation**                                  | Mechanism allowing identities managed by one organization or identity provider to authenticate to another environment.                                         |
| **Single Sign-On (SSO)**                                 | Authentication capability allowing users to access multiple applications or services using a common authentication process.                                    |
| **Multi-Factor Authentication (MFA)**                    | Authentication requiring two or more independent factors.                                                                                                      |
| **Adaptive Authentication**                              | Authentication that adjusts requirements based on contextual risk signals.                                                                                     |
| **Role-Based Access Control (RBAC)**                     | Access model assigning permissions based on defined roles.                                                                                                     |
| **Attribute-Based Access Control (ABAC)**                | Access model making authorization decisions based on attributes such as identity, resource, location, device, or context.                                      |
| **Policy-Based Access Control**                          | Authorization model in which access decisions are determined by centrally defined policies.                                                                    |
| **Least Privilege**                                      | Principle of providing users, services, applications, and identities only the minimum access necessary.                                                        |
| **Privileged Access**                                    | Access allowing administrative, security-sensitive, or high-impact actions.                                                                                    |
| **Privileged Identity Management (PIM)**                 | Controls for managing privileged identities and reducing unnecessary persistent privileged access.                                                             |
| **Just-in-Time Access (JIT)**                            | Temporary access granted only when required and for a limited duration.                                                                                        |
| **Just-Enough-Access (JEA)**                             | Principle of granting only the permissions necessary to perform a specific task.                                                                               |
| **Cloud Service Account**                                | Identity used by applications, workloads, automation, or services to interact with cloud resources.                                                            |
| **Machine Identity**                                     | Identity associated with a machine, workload, application, device, or automated process.                                                                       |
| **Workload Identity**                                    | Identity assigned to an application, workload, service, or compute resource for authentication and authorization.                                              |
| **Service Principal**                                    | Identity representing an application or automated workload that can authenticate and access cloud resources.                                                   |
| **Managed Identity**                                     | Cloud-provider-managed identity used by workloads or services without requiring users to manage long-lived credentials.                                        |
| **Secrets Management**                                   | Secure creation, storage, distribution, rotation, and management of passwords, keys, tokens, and other secrets.                                                |
| **Secrets Vault**                                        | Secure service used to store and manage sensitive credentials, keys, tokens, certificates, and secrets.                                                        |
| **Credential Rotation**                                  | Process of periodically replacing credentials, keys, secrets, or certificates.                                                                                 |
| **Cloud Key Management**                                 | Management of cryptographic keys used to protect cloud data and services.                                                                                      |
| **Key Management Service (KMS)**                         | Cloud service used to create, store, manage, rotate, and control cryptographic keys.                                                                           |
| **Hardware Security Module (HSM)**                       | Specialized hardware designed to securely generate, store, and use cryptographic keys.                                                                         |
| **Customer-Managed Key (CMK)**                           | Encryption key controlled or managed by the cloud customer rather than exclusively by the provider.                                                            |
| **Bring Your Own Key (BYOK)**                            | Model in which customers provide or control encryption keys used by cloud services.                                                                            |
| **Hold Your Own Key (HYOK)**                             | Encryption model in which the customer retains direct control of encryption keys outside the cloud provider environment.                                       |
| **Encryption at Rest**                                   | Protection of stored data using cryptographic mechanisms.                                                                                                      |
| **Encryption in Transit**                                | Protection of data while being transmitted across networks.                                                                                                    |
| **Encryption in Use**                                    | Protection of data while it is actively processed or used.                                                                                                     |
| **Confidential Computing**                               | Technology designed to protect data while in use through trusted execution environments or related mechanisms.                                                 |
| **Tokenization**                                         | Replacement of sensitive data with non-sensitive tokens that can be mapped back to the original data under controlled conditions.                              |
| **Data Loss Prevention (DLP)**                           | Controls designed to identify, monitor, and prevent unauthorized disclosure or movement of sensitive information.                                              |
| **Cloud Data Security**                                  | Protection of data stored, processed, transmitted, and shared within cloud environments.                                                                       |
| **Cloud Data Classification**                            | Categorization of cloud data according to sensitivity, confidentiality, criticality, regulatory requirements, or business value.                               |
| **Data Discovery**                                       | Identification and location of data stored or processed within cloud environments.                                                                             |
| **Data Lineage**                                         | Tracking where data originates, how it moves, how it is transformed, and where it is stored or consumed.                                                       |
| **Data Residency**                                       | Geographic location where data is physically or logically stored.                                                                                              |
| **Data Sovereignty**                                     | Concept that data is subject to the laws and jurisdiction applicable to the location where it is stored or processed.                                          |
| **Cross-Border Data Transfer**                           | Transfer of data between different countries or jurisdictions.                                                                                                 |
| **Cloud Data Lifecycle**                                 | Stages through which cloud data moves, including creation, storage, use, sharing, retention, archival, and destruction.                                        |
| **Data Retention**                                       | Defined period for maintaining data.                                                                                                                           |
| **Secure Data Deletion**                                 | Processes designed to ensure data is securely removed when no longer required.                                                                                 |
| **Cloud Storage Security**                               | Protection of cloud-based storage services and the data contained within them.                                                                                 |
| **Object Storage**                                       | Cloud storage model that stores data as objects with associated metadata and unique identifiers.                                                               |
| **Block Storage**                                        | Storage model providing block-level storage volumes for systems and applications.                                                                              |
| **File Storage**                                         | Storage model providing file-based access to shared or distributed storage.                                                                                    |
| **Cloud Network Security**                               | Controls protecting network communication, traffic flows, connectivity, and network resources in cloud environments.                                           |
| **Virtual Network**                                      | Logically isolated network environment created within cloud infrastructure.                                                                                    |
| **Virtual Private Cloud (VPC)**                          | Logically isolated cloud network used to host and connect cloud resources.                                                                                     |
| **Virtual Network (VNet)**                               | Cloud provider's logical networking environment used to isolate and connect resources.                                                                         |
| **Subnet**                                               | Logical subdivision of a cloud network used to organize and control network resources.                                                                         |
| **Network Security Group (NSG)**                         | Set of rules controlling network traffic to or from cloud resources.                                                                                           |
| **Security Group**                                       | Virtual firewall rules controlling network access to cloud resources.                                                                                          |
| **Cloud Firewall**                                       | Security control used to filter and control network traffic in cloud environments.                                                                             |
| **Web Application Firewall (WAF)**                       | Security control designed to protect web applications from malicious HTTP/HTTPS traffic and application-layer attacks.                                         |
| **Cloud Load Balancer**                                  | Service that distributes network or application traffic across multiple resources.                                                                             |
| **API Gateway**                                          | Service that manages, secures, routes, and monitors API traffic.                                                                                               |
| **Network Segmentation**                                 | Division of networks into security zones to reduce unauthorized access and limit attack propagation.                                                           |
| **Micro-Segmentation**                                   | Fine-grained segmentation that applies security controls to individual workloads, applications, or services.                                                   |
| **Private Endpoint**                                     | Network endpoint providing private connectivity to cloud services without exposing traffic to the public internet.                                             |
| **Public Endpoint**                                      | Endpoint accessible through public networks such as the internet.                                                                                              |
| **Internet Gateway**                                     | Component enabling communication between a cloud network and the public internet.                                                                              |
| **NAT Gateway**                                          | Network component enabling private resources to access external networks without exposing their private addresses directly.                                    |
| **DNS Security**                                         | Protection of domain-name resolution processes against manipulation, spoofing, and unauthorized changes.                                                       |
| **Cloud Security Group**                                 | Logical firewall mechanism controlling traffic to cloud resources.                                                                                             |
| **Container Security**                                   | Protection of container images, runtimes, hosts, orchestration platforms, and containerized workloads.                                                         |
| **Container Image**                                      | Packaged representation of software and its dependencies used to create containers.                                                                            |
| **Container Registry**                                   | Repository used to store, manage, scan, and distribute container images.                                                                                       |
| **Image Scanning**                                       | Analysis of container or machine images for vulnerabilities, malware, secrets, misconfigurations, and policy violations.                                       |
| **Container Runtime Security**                           | Controls protecting containers while they are executing.                                                                                                       |
| **Kubernetes Security**                                  | Security controls for Kubernetes clusters, workloads, identities, networking, configurations, and control planes.                                              |
| **Kubernetes Cluster**                                   | Group of machines or nodes managed by Kubernetes to run containerized workloads.                                                                               |
| **Pod Security**                                         | Security controls governing the execution and configuration of Kubernetes pods.                                                                                |
| **Cluster Security**                                     | Protection of the Kubernetes control plane, nodes, workloads, identities, and network.                                                                         |
| **DevSecOps**                                            | Integration of security practices into development and operations throughout the software delivery lifecycle.                                                  |
| **Cloud DevSecOps**                                      | Application of DevSecOps principles to cloud-native development and deployment environments.                                                                   |
| **Continuous Integration (CI)**                          | Practice of frequently integrating code changes into a shared development environment with automated testing and validation.                                   |
| **Continuous Delivery (CD)**                             | Practice of maintaining software in a deployable state through automated build, test, and delivery processes.                                                  |
| **Continuous Deployment**                                | Automated deployment of validated software changes into production.                                                                                            |
| **CI/CD Security**                                       | Security controls integrated into continuous integration and delivery pipelines.                                                                               |
| **DevSecOps Pipeline Security**                          | Protection of source code, build systems, repositories, artifacts, credentials, and deployment pipelines.                                                      |
| **Cloud Software Supply Chain Security**                 | Protection of cloud-based software development, dependencies, images, packages, pipelines, and deployment processes.                                           |
| **Artifact Security**                                    | Protection and validation of software packages, binaries, images, and other build outputs.                                                                     |
| **Cloud-Native Security**                                | Security practices specifically designed for cloud-native architectures, workloads, platforms, and development practices.                                      |
| **Immutable Infrastructure**                             | Infrastructure designed to be replaced rather than modified in place.                                                                                          |
| **Ephemeral Resource**                                   | Temporary cloud resource that exists only for a limited period or workload.                                                                                    |
| **Autoscaling**                                          | Automatic adjustment of computing resources according to demand or defined conditions.                                                                         |
| **Elasticity**                                           | Ability of cloud resources to dynamically scale up or down based on demand.                                                                                    |
| **Cloud Resource Tagging**                               | Assignment of metadata tags to cloud resources for management, governance, cost allocation, security, and compliance.                                          |
| **Cloud Asset Inventory**                                | Centralized record of cloud resources and assets.                                                                                                              |
| **Shadow IT**                                            | Use of technology or cloud services without formal organizational authorization or governance.                                                                 |
| **Shadow Cloud**                                         | Unauthorized or unmanaged use of cloud services by organizational users or teams.                                                                              |
| **Cloud Misconfiguration**                               | Incorrect or insecure configuration of cloud resources, services, identities, networks, or controls.                                                           |
| **Publicly Exposed Resource**                            | Cloud resource accessible from the public internet or an unauthorized external network.                                                                        |
| **Excessive Permission**                                 | Access privilege greater than required for a user's, service's, or application's legitimate responsibilities.                                                  |
| **Overprivileged Identity**                              | Identity possessing unnecessary or excessive permissions.                                                                                                      |
| **Orphaned Resource**                                    | Cloud resource that remains active or accessible without a valid owner, business purpose, or management responsibility.                                        |
| **Orphaned Account**                                     | Cloud account or identity that remains active without a legitimate owner or business requirement.                                                              |
| **Unused Resource**                                      | Cloud resource that is no longer required but remains provisioned.                                                                                             |
| **Cloud Hygiene**                                        | Practices for maintaining secure, controlled, documented, and appropriately configured cloud environments.                                                     |
| **Cloud Security Baseline**                              | Minimum set of security configurations and controls required for cloud resources or environments.                                                              |
| **Secure Configuration Baseline**                        | Approved configuration settings designed to establish an acceptable security posture.                                                                          |
| **Cloud Benchmark**                                      | Recommended security configuration standard for a cloud service or environment.                                                                                |
| **CIS Benchmark**                                        | Security configuration guidance published by the Center for Internet Security for various technologies and platforms.                                          |
| **Cloud Security Benchmarking**                          | Comparison of cloud configurations against recognized security standards or organizational baselines.                                                          |
| **Security Drift**                                       | Gradual deviation of cloud configurations from approved security baselines.                                                                                    |
| **Configuration Drift**                                  | Difference between an approved configuration and the actual deployed configuration.                                                                            |
| **Cloud Policy Violation**                               | Cloud resource configuration or activity that violates an organizational or regulatory policy.                                                                 |
| **Remediation**                                          | Corrective action taken to address cloud security weaknesses, vulnerabilities, or compliance violations.                                                       |
| **Automated Remediation**                                | Automated correction of identified cloud security or configuration issues.                                                                                     |
| **Cloud Security Orchestration**                         | Automated coordination of security tools, processes, and responses across cloud environments.                                                                  |
| **Security Automation**                                  | Use of automated technologies to perform security monitoring, detection, response, compliance, or remediation activities.                                      |
| **Cloud Security Posture Score**                         | Quantitative or qualitative measure representing the security posture of a cloud environment.                                                                  |
| **Cloud Risk Score**                                     | Measurement representing the assessed risk associated with cloud resources, services, or configurations.                                                       |
| **Cloud Compliance Score**                               | Measurement representing the degree of compliance with defined cloud security or regulatory requirements.                                                      |

---

# Cloud Security Responsibility Model

One of the **most important concepts in cloud security** is the **Shared Responsibility Model**.

A simplified representation is:

### Cloud Provider

Typically responsible for:

**Physical Facilities**
↓
**Physical Hardware**
↓
**Underlying Infrastructure**
↓
**Cloud Platform**

### Customer

Depending on the service model, typically responsible for:

**Data**
↓
**Identities**
↓
**Access Controls**
↓
**Configurations**
↓
**Applications**
↓
**Workloads**

The exact division varies by provider and service model.

---

# Shared Responsibility by Service Model

| Responsibility       | IaaS     | PaaS             | SaaS                                                |
| -------------------- | -------- | ---------------- | --------------------------------------------------- |
| Physical Data Center | Provider | Provider         | Provider                                            |
| Physical Hardware    | Provider | Provider         | Provider                                            |
| Core Infrastructure  | Provider | Provider         | Provider                                            |
| Operating System     | Customer | Usually Provider | Provider                                            |
| Runtime              | Customer | Provider         | Provider                                            |
| Application          | Customer | Customer         | Provider                                            |
| Data                 | Customer | Customer         | Shared/Customer responsibility depending on service |
| Identity & Access    | Customer | Customer         | Shared/Customer responsibility                      |
| Configuration        | Customer | Customer         | Customer/shared                                     |
| Security Governance  | Shared   | Shared           | Shared                                              |

**Important:** This table is conceptual. Actual responsibilities vary by cloud provider and specific service.

---

# Cloud Security Architecture Layers

A useful GRC architecture model is:

**1. Governance**

→ Policies
→ Standards
→ Risk Appetite
→ Compliance
→ Architecture Governance

**2. Identity**

→ IAM
→ MFA
→ RBAC
→ PAM
→ CIEM
→ Workload Identity

**3. Network**

→ Segmentation
→ Firewalls
→ WAF
→ Private Endpoints
→ Zero Trust

**4. Compute**

→ Virtual Machines
→ Containers
→ Serverless
→ Workloads

**5. Application**

→ Secure SDLC
→ DevSecOps
→ API Security
→ Application Security

**6. Data**

→ Classification
→ Encryption
→ DLP
→ Key Management
→ Retention

**7. Monitoring**

→ Logging
→ SIEM
→ Threat Detection
→ CSPM
→ CDR

**8. Resilience**

→ Backup
→ Replication
→ Multi-Region
→ Disaster Recovery
→ Failover

---

# CSPM vs CWPP vs CIEM vs CNAPP

These terms are especially important in modern cloud security.

| Capability | Primary Focus                                                   |
| ---------- | --------------------------------------------------------------- |
| **CSPM**   | Cloud configuration and security posture                        |
| **CWPP**   | Protection of cloud workloads                                   |
| **CIEM**   | Cloud identities and excessive permissions                      |
| **CNAPP**  | Integrated cloud-native application and infrastructure security |

Conceptually:

**CNAPP**

├── CSPM
├── CWPP
├── CIEM
├── Cloud Application Security
├── IaC Security
└── Container Security

---

# Cloud Security Risk Categories

A mature cloud risk assessment should consider:

### 1. Identity Risk

* excessive privileges;
* compromised credentials;
* weak authentication;
* orphaned accounts.

### 2. Configuration Risk

* public storage;
* exposed services;
* insecure security groups;
* configuration drift.

### 3. Data Risk

* unauthorized access;
* data leakage;
* weak encryption;
* incorrect data residency.

### 4. Application Risk

* vulnerable applications;
* insecure APIs;
* vulnerable dependencies;
* insecure deployment pipelines.

### 5. Infrastructure Risk

* vulnerable workloads;
* insecure containers;
* exposed management interfaces.

### 6. Third-Party Risk

* cloud provider dependency;
* subcontractors;
* fourth parties;
* provider concentration.

### 7. Compliance Risk

* regulatory requirements;
* contractual requirements;
* privacy requirements;
* audit requirements.

### 8. Resilience Risk

* provider outage;
* regional failure;
* inadequate backups;
* inadequate disaster recovery.

---

# Cloud Security Governance Model

For a GRC professional, cloud governance can be structured as:

**Cloud Strategy**

↓

**Cloud Governance**

↓

**Cloud Risk Management**

↓

**Cloud Security Architecture**

↓

**Cloud Security Controls**

↓

**Cloud Monitoring**

↓

**Cloud Compliance**

↓

**Cloud Assurance**

↓

**Continual Improvement**

---

# Cloud Security and GRC

Cloud security should not operate as an isolated technical function.

A mature GRC model connects:

### Governance

**Cloud Policy → Standards → Roles → Architecture Governance**

### Risk

**Cloud Risk Assessment → Risk Treatment → Risk Acceptance**

### Compliance

**Regulations → ISO → NIST → Contractual Requirements**

### Controls

**IAM → Encryption → Network Security → Logging → Monitoring**

### Assurance

**Assessments → Audits → Certifications → Evidence**

### Monitoring

**CSPM → SIEM → CIEM → Threat Intelligence → KRIs**

### Resilience

**Backup → Replication → DR → Multi-Region → Failover**

---

# Cloud Security Key Terms to Remember

For **GRC, CISO, cloud security, cybersecurity architecture, audit, and risk management**, prioritize:

**Cloud Security**
→ **Cloud Governance**
→ **Cloud Risk Management**
→ **Cloud Security Architecture**
→ **Cloud Service Provider (CSP)**
→ **IaaS**
→ **PaaS**
→ **SaaS**
→ **Public Cloud**
→ **Private Cloud**
→ **Hybrid Cloud**
→ **Multi-Cloud**
→ **Shared Responsibility Model**
→ **Cloud Control Plane**
→ **Cloud Data Plane**
→ **IAM**
→ **RBAC**
→ **ABAC**
→ **MFA**
→ **PAM**
→ **CIEM**
→ **Least Privilege**
→ **Zero Trust**
→ **Secrets Management**
→ **KMS**
→ **HSM**
→ **Encryption at Rest**
→ **Encryption in Transit**
→ **Data Residency**
→ **Data Sovereignty**
→ **DLP**
→ **VPC/VNet**
→ **Network Segmentation**
→ **Micro-Segmentation**
→ **WAF**
→ **API Gateway**
→ **Container Security**
→ **Kubernetes Security**
→ **DevSecOps**
→ **Infrastructure as Code**
→ **Policy as Code**
→ **CSPM**
→ **CWPP**
→ **CNAPP**
→ **Cloud Logging**
→ **Cloud SIEM**
→ **Cloud Incident Response**
→ **Cloud Forensics**
→ **Cloud Vulnerability Management**
→ **Cloud Compliance**
→ **Cloud Security Baseline**
→ **Configuration Drift**
→ **Security Drift**
→ **Cloud Misconfiguration**
→ **Cloud Resilience**
→ **Cloud Disaster Recovery**
→ **Cross-Region Replication**
→ **Cloud Failover**
→ **Cloud Backup**
→ **Cloud Risk Score**

### Key GRC takeaway

The central cloud-security principle is:

> **Moving workloads to the cloud does not eliminate security responsibility; it changes how security responsibilities are allocated, governed, monitored, and assured.**

A mature cloud GRC model therefore connects:

**Cloud Strategy → Governance → Shared Responsibility → Risk Assessment → Security Architecture → Controls → Continuous Monitoring → Compliance → Assurance → Resilience**

And for a GRC professional, the **Shared Responsibility Model, IAM, cloud configuration risk, data protection, third-party risk, compliance, and resilience** are among the most important areas to understand.


