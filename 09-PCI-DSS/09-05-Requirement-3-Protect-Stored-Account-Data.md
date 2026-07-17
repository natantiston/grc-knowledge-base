# Lesson 9.5 – Requirement 3: Protect Stored Account Data

> **Chapter:** 09 – Payment Card Industry Data Security Standard (PCI DSS) 4.0
> **Lesson:** 9.5
> **Difficulty:** Intermediate
> **Estimated Reading Time:** 10–15 minutes
> **Prerequisites:** Lesson 9.4 – Requirement 2: Apply Secure Configurations to All System Components

---

# Learning Objectives

By the end of this lesson, you will be able to:

- Understand the purpose of PCI DSS Requirement 3.
- Differentiate between Cardholder Data (CHD) and Sensitive Authentication Data (SAD).
- Explain why minimizing stored payment data reduces organizational risk.
- Identify the types of payment data that may and may not be stored.
- Understand the importance of data retention and secure disposal.

---

# Introduction

One of the most effective ways to protect payment card information is **not to store it unless absolutely necessary**. Every copy of stored payment data represents additional risk. If attackers compromise a system containing stored cardholder data, the consequences can include financial loss, regulatory penalties, reputational damage, and legal liability.

PCI DSS Requirement 3 focuses on protecting stored account data by minimizing storage, applying strong cryptographic protections, and ensuring that data is securely deleted when it is no longer required. It also strictly prohibits the storage of Sensitive Authentication Data (SAD) after authorization, even if encrypted. :contentReference[oaicite:0]{index=0}

---

# Purpose of Requirement 3

The primary objective of Requirement 3 is to protect stored payment account information from unauthorized disclosure.

Requirement 3 helps organizations:

- Minimize stored payment data.
- Protect stored Primary Account Numbers (PANs).
- Prevent storage of prohibited authentication data.
- Reduce the impact of data breaches.
- Support legal and regulatory compliance.
- Improve customer trust.

Reducing the amount of stored data significantly lowers the organization's overall cyber risk.

---

# Understanding Payment Account Data

PCI DSS distinguishes between two important categories of payment information.

## Cardholder Data (CHD)

Cardholder Data includes:

- Primary Account Number (PAN)
- Cardholder name
- Expiration date
- Service code

The PAN is the most critical element because it uniquely identifies the payment account.

If the PAN is stored, it must be protected using PCI DSS-approved methods such as encryption, truncation, masking, or strong hashing where appropriate. :contentReference[oaicite:1]{index=1}

---

## Sensitive Authentication Data (SAD)

Sensitive Authentication Data includes:

- Full magnetic stripe (track) data
- EMV chip equivalent data
- Card Verification Value (CVV/CVC/CVV2/CID)
- PINs
- Encrypted PIN blocks

Unlike Cardholder Data, **Sensitive Authentication Data must never be stored after authorization**, even if encrypted. :contentReference[oaicite:2]{index=2}

---

# Cardholder Data vs. Sensitive Authentication Data

| Data Element | May Be Stored? | Protection Required |
|--------------|----------------|---------------------|
| Primary Account Number (PAN) | Yes | Must be rendered unreadable using approved methods |
| Cardholder Name | Yes | Protect when stored with PAN |
| Expiration Date | Yes | Protect when stored with PAN |
| Service Code | Yes | Protect when stored with PAN |
| Full Track Data | **No** | Must never be stored after authorization |
| CVV/CVC/CVV2/CID | **No** | Must never be stored after authorization |
| PIN | **No** | Must never be stored |
| PIN Block | **No** | Must never be stored |

Understanding this distinction is fundamental to PCI DSS compliance. :contentReference[oaicite:3]{index=3}

---

# Data Minimization

PCI DSS strongly encourages organizations to store only the information required for legitimate business, legal, or regulatory purposes.

Examples of legitimate reasons include:

- Chargeback processing
- Transaction reconciliation
- Fraud investigations
- Financial reporting
- Legal retention requirements

If payment data is no longer required, it should be securely deleted or rendered unrecoverable. PCI DSS does not prescribe a maximum retention period, but organizations must define and enforce retention periods based on business, legal, and regulatory needs. :contentReference[oaicite:4]{index=4}

---

# Data Retention Policy

Organizations should establish a formal data retention policy that defines:

- What payment data is stored
- Why it is stored
- Where it is stored
- Who can access it
- How long it is retained
- How it is securely destroyed

The policy should be reviewed periodically and aligned with business and regulatory requirements.

---

# Why Storing Less Data Improves Security

Every additional database, backup, log file, or storage device containing payment data increases organizational risk.

Reducing stored data provides several benefits:

- Smaller attack surface
- Lower breach impact
- Simplified compliance
- Reduced storage costs
- Easier data management
- Faster incident response

Organizations should regularly review stored payment data and eliminate unnecessary copies.

---

# Examples of Stored Payment Data

Stored payment information may exist in:

- Databases
- Backup media
- Application logs
- File servers
- Cloud storage
- Payment applications
- Reports
- Printed receipts
- Archived records

All storage locations must be identified and protected.

---

📊 **Diagram Placeholder**

**Title:** PCI DSS Requirement 3 – Protect Stored Account Data

**Diagram Description:**

```text
Payment Transaction

↓

Authorization

↓

Store Only Required Cardholder Data

↓

Encrypt / Tokenize / Mask PAN

↓

Retention Policy

↓

Secure Deletion

↓

Continuous Review
```

Show a separate path indicating that Sensitive Authentication Data is deleted immediately after authorization and is never retained.

**Caption:**

*"Requirement 3 minimizes organizational risk by limiting stored payment data, protecting retained Cardholder Data, and prohibiting the storage of Sensitive Authentication Data after authorization."*

---

# Best Practices

Organizations should:

- Store payment card data only when there is a documented business, legal, or regulatory requirement.
- Identify every location where cardholder data is stored, including databases, backups, cloud storage, logs, and paper records.
- Develop and maintain a formal data retention and secure disposal policy.
- Eliminate unnecessary copies of payment information to reduce the Cardholder Data Environment (CDE) and overall risk.
- Ensure Sensitive Authentication Data is never retained after authorization, regardless of storage method or encryption. :contentReference[oaicite:5]{index=5}
- Periodically review stored account data to verify that retention periods remain appropriate.
- Integrate data lifecycle management with enterprise information governance and records management processes.
- Educate system administrators and application developers on PCI DSS data storage restrictions.

These practices reduce the organization's attack surface while strengthening payment security and supporting ongoing PCI DSS compliance.

---

# Practical Example

An international airline stores payment card information to support refunds and chargeback investigations. Before implementing PCI DSS Requirement 3, multiple databases, application logs, and backup files contained unnecessary copies of full cardholder data. During a data discovery exercise, the security team identifies every location where payment information is stored and removes duplicate records that are no longer required. The organization introduces a formal data retention policy that defines retention periods for legitimate business purposes and automates the secure deletion of expired records.

At the same time, developers modify the payment application to ensure that CVV values are never stored after transaction authorization, while stored Primary Account Numbers are protected using approved cryptographic methods. Regular audits verify compliance with the retention policy and confirm that Sensitive Authentication Data is not retained anywhere in the environment. As a result, the organization significantly reduces its storage footprint, lowers cyber risk, and strengthens compliance with PCI DSS Requirement 3.

