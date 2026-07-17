# Lesson 9.3 – Requirement 1: Install and Maintain Network Security Controls

> **Chapter:** 09 – Payment Card Industry Data Security Standard (PCI DSS) 4.0
>
> **Lesson:** 9.3
>
> **Part:** 1 of 4
>
> **Difficulty:** Intermediate
>
> **Estimated Reading Time:** 10–15 minutes
>
> **Prerequisites:** Lesson 9.2 – PCI DSS Security Goals and the 12 Requirements

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of PCI DSS Requirement 1.
- Explain why network security controls are the first line of defense.
- Identify the components that make up network security controls.
- Understand the role of network segmentation in reducing PCI DSS scope.
- Explain how Requirement 1 supports the protection of the Cardholder Data Environment (CDE).

---

# Introduction

The first requirement of PCI DSS is to **install and maintain network security controls**. Before organizations can protect payment card data, they must first secure the networks through which that data flows.

Cybercriminals commonly attempt to gain unauthorized access through exposed network services, weak firewall configurations, open ports, insecure remote access solutions, and poorly segmented networks. Requirement 1 addresses these risks by ensuring that organizations establish secure network boundaries and control communications entering and leaving the Cardholder Data Environment (CDE).

Without effective network security controls, attackers may gain access to payment systems before other security mechanisms have an opportunity to detect or stop them.

---

# Purpose of Requirement 1

The primary objective of Requirement 1 is to prevent unauthorized network access to systems that store, process, or transmit payment card data.

Requirement 1 helps organizations:

- Protect the Cardholder Data Environment.
- Restrict unnecessary network communications.
- Reduce the attack surface.
- Prevent unauthorized access.
- Separate trusted and untrusted networks.
- Limit lateral movement during cyber attacks.

This requirement establishes the foundation upon which the remaining PCI DSS controls are built.

---

# What Are Network Security Controls?

Network Security Controls (NSCs) are technologies and processes that regulate traffic between different networks and systems.

Examples include:

- Firewalls
- Next-Generation Firewalls (NGFW)
- Router Access Control Lists (ACLs)
- Network Access Control (NAC)
- Secure Web Gateways
- Proxy Servers
- VPN Gateways
- Cloud Security Groups
- Web Application Firewalls (WAF)
- Micro-segmentation technologies

These controls inspect, allow, deny, or monitor network traffic based on defined security policies.

---

# Trusted vs. Untrusted Networks

Requirement 1 distinguishes between trusted and untrusted networks.

### Trusted Network

A trusted network is managed and controlled by the organization.

Examples include:

- Internal corporate network
- Data center network
- Private cloud network
- Internal management network

---

### Untrusted Network

An untrusted network is any network outside the organization's direct control.

Examples include:

- Internet
- Public Wi-Fi
- Third-party networks
- Customer networks
- Partner networks

Traffic between trusted and untrusted networks should always pass through appropriately configured network security controls.

---

# Cardholder Data Environment (CDE)

One of the most important concepts in Requirement 1 is the **Cardholder Data Environment (CDE).**

The CDE includes:

- Payment applications
- Payment databases
- POS systems
- Payment APIs
- Authentication servers
- Supporting network infrastructure

Protecting the CDE from unauthorized access is the primary objective of Requirement 1.

---

# Network Segmentation

PCI DSS strongly recommends network segmentation.

Network segmentation separates payment systems from the rest of the enterprise network.

For example:

```text
Corporate Network

──────── Firewall ────────

Cardholder Data Environment

• Payment Servers

• Payment Database

• POS Systems

• Payment Applications
```

Segmentation provides several benefits:

- Smaller PCI DSS scope
- Reduced attack surface
- Easier compliance
- Better traffic control
- Improved monitoring
- Reduced audit complexity

Although segmentation is not mandatory, it is considered a best practice for both security and compliance.

---

# Network Security Policies

Technology alone is insufficient.

Organizations should establish documented policies covering:

- Firewall management
- Network architecture
- Rule approval processes
- Rule review frequency
- Remote access
- Wireless security
- Change management
- Network monitoring

Policies ensure consistency and accountability across the organization.

---

# Modern Network Security

Today's payment environments often extend beyond traditional on-premises networks.

Requirement 1 also applies to:

- Cloud environments
- Hybrid infrastructure
- Containers
- Kubernetes clusters
- Virtual networks
- Software-defined networking (SDN)
- Remote workforce environments

Organizations should apply consistent security principles regardless of where payment systems are hosted.

---

📊 **Diagram Placeholder**

**Title:** Network Security Controls Protecting the Cardholder Data Environment

**Diagram Description:**

```text
Internet

↓

Perimeter Firewall

↓

DMZ

↓

Application Firewall

↓

Payment Application

↓

Database Firewall

↓

Cardholder Data Environment
```

Show monitoring and logging integrated with each security layer.

**Caption:**

*"Network Security Controls establish multiple defensive layers that protect the Cardholder Data Environment from unauthorized access and network-based attacks."*

---

# Best Practices

Organizations should:

- Identify all trusted and untrusted network connections supporting payment systems.
- Deploy network security controls at every boundary where traffic enters or leaves the Cardholder Data Environment.
- Use network segmentation to isolate payment systems from the corporate network and reduce PCI DSS scope.
- Apply a default-deny approach, allowing only explicitly authorized network traffic.
- Document network architecture, firewall rules, and communication paths to support operational management and compliance assessments.
- Review network security policies regularly to ensure they remain aligned with business and security requirements.
- Extend network security controls consistently across on-premises, cloud, and hybrid environments.
- Continuously monitor network activity for unauthorized connections, anomalous traffic, and policy violations.

These practices establish a strong network security foundation that supports all other PCI DSS requirements and significantly reduces the risk of unauthorized access to payment environments.

---

# Practical Example

A multinational retail organization operates physical stores, an e-commerce platform, and a centralized payment processing environment. To comply with PCI DSS Requirement 1, the company redesigns its network architecture by deploying next-generation firewalls between the internet, corporate network, and Cardholder Data Environment. Dedicated network segments isolate payment systems from office workstations and guest Wi-Fi networks, while access control lists restrict communications to only the services required for payment processing. Remote administrative access is secured through VPN connections protected by multi-factor authentication.

The organization also documents its network architecture, firewall rule sets, and payment data flows, ensuring they are reviewed during every significant infrastructure change. Security Operations continuously monitor firewall logs and network alerts using a Security Information and Event Management (SIEM) platform, allowing suspicious activity to be detected and investigated quickly. By implementing layered network security controls and strong segmentation, the organization reduces its PCI DSS scope while significantly improving the security of its Cardholder Data Environment.

