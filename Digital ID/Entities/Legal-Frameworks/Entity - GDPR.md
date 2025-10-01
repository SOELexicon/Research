---
type: entity
entity-type: legal-framework
aliases: ["GDPR", "General Data Protection Regulation", "GDPR 2016/679"]
status: active
affiliation: [[Entity - European Union]]
enacted: 2016-04-27
enforcement: 2018-05-25
tags: [entity, entity/legal-framework, EU, data-protection, privacy]
---

# General Data Protection Regulation (GDPR)

## Overview
The General Data Protection Regulation (GDPR) is the [[Entity - European Union]]'s comprehensive data protection and privacy law, providing the strongest legal framework globally for individual rights over personal data. GDPR is the **foundational legal safeguard** for the [[Entity - EU EUDI Wallet]], ensuring that EU digital identity systems must be **privacy-preserving, user-controlled, and rights-respecting**—in stark contrast to surveillance-oriented systems like [[Entity - China Social Credit System]] or exclusion-prone systems like [[Entity - India Aadhaar System]].

## Legal Details
- **Jurisdiction**: [[Entity - European Union]] (27 member states) + EEA
- **Enacted**: April 27, 2016
- **Enforcement Date**: May 25, 2018
- **Legal Basis**: EU Regulation (directly applicable in all member states)
- **Extraterritorial Reach**: Applies to any organization processing EU residents' data

## Core Principles

### 1. Lawfulness, Fairness, and Transparency
Data processing must have legal basis and be transparent to data subjects.

### 2. Purpose Limitation
Data collected for specific purposes cannot be used for incompatible purposes.
- **Critical for Digital ID**: Prevents [[Finding - Function Creep Welfare to Surveillance Repurposing]]

### 3. Data Minimization
**Only necessary data** should be collected.
- **Selective Disclosure**: Foundation of [[Entity - EU EUDI Wallet]] architecture
- **Contrast to Aadhaar**: [[Entity - India Aadhaar System]] collects excessive biometric data

### 4. Accuracy
Personal data must be accurate and kept up to date.

### 5. Storage Limitation
Data should not be kept longer than necessary.

### 6. Integrity and Confidentiality
Data must be processed securely, protecting against:
- Unauthorized access
- Accidental loss
- Destruction or damage
- **Addresses**: [[Finding - Centralized Database Single Point of Failure]] risks

### 7. Accountability
Organizations must demonstrate compliance.

## Individual Rights

### Right to Access
Individuals can request:
- What personal data is held
- How it is being used
- Who it is shared with

### Right to Rectification
Correct inaccurate personal data.

### Right to Erasure ("Right to be Forgotten")
Request deletion of personal data.
- **Critical for Digital ID**: Can delete identity wallet data

### Right to Data Portability
Transfer personal data between service providers.
- **EUDI Wallet**: Can switch wallet providers

### Right to Object
Object to processing of personal data.

### Right to Restrict Processing
Limit how data is used.

### Rights Related to Automated Decision-Making
Not be subject solely to automated decisions (including profiling).

## Data Protection Impact Assessments (DPIAs)

### Mandatory for High-Risk Processing
GDPR requires DPIAs for processing that poses high risk to individuals' rights:
- **Large-scale biometric processing**
- **Systematic monitoring**
- **Special category data**

### [[Finding - Kenya Litigation DPIA Requirement Precedent]]
Kenya's High Court applied similar DPIA requirement:
- [[Entity - Kenya Huduma Namba System]] ruled illegal without DPIA
- Government "put cart before horse"
- Template for other jurisdictions

### DPIA Requirements
Before implementing digital ID:
1. **Description**: Systematic description of processing operations
2. **Necessity Assessment**: Demonstrate necessity and proportionality
3. **Risk Assessment**: Identify risks to individuals' rights
4. **Mitigation Measures**: Safeguards to address risks
5. **Consultation**: With Data Protection Authority if high residual risk

## Enforcement

### Data Protection Authorities
Each member state has independent DPA with powers to:
- Investigate complaints
- Conduct audits
- Issue warnings and reprimands
- Order data processing limitations
- **Impose administrative fines**

### Penalties
- **Up to €20 million** or **4% of annual global turnover** (whichever is greater)
- Significant deterrent for violations

### Notable Enforcement Actions
- Fines against tech giants (Meta, Google, Amazon) for privacy violations
- Scrutiny of facial recognition systems
- Challenges to biometric data processing

## Application to Digital Identity Systems

### EUDI Wallet Compliance
[[Entity - eIDAS 2.0 Regulation]] requires full GDPR compliance:
- Data minimization (selective disclosure)
- User control (consent for each sharing)
- No central database (decentralized architecture)
- Right to erasure (delete wallet data)

### Biometric Data - Special Category
GDPR classifies biometric data as **"special category"** requiring heightened protection:
- Explicit consent usually required
- Limited legal bases for processing
- Stricter security requirements
- **Higher risk of [[Finding - Biometric Security Vulnerability Systemic Failures]]**

### Function Creep Prevention
GDPR's **purpose limitation principle** is designed to prevent [[Finding - Function Creep Welfare to Surveillance Repurposing]]:
- Data collected for one purpose cannot be repurposed
- Welfare system data cannot be used for law enforcement without new legal basis
- **Contrast**: [[Entity - India Aadhaar System]] experienced massive function creep from welfare to mandatory for everything

## Comparison to Other Frameworks

### vs. No Data Protection Law (Pre-GDPR Kenya)
**GDPR**: Comprehensive framework before implementation
**Kenya (2019)**: Attempted [[Entity - Kenya Huduma Namba System]] rollout before data protection law in place → ruled unconstitutional

### vs. Weak Data Protection (India)
**GDPR**: Strong enforcement, individual rights, hefty penalties
**India**: Aadhaar implemented with minimal data protection → [[Event - India Aadhaar Tribune Investigation 2018]] (database access for $7)

### vs. No Data Protection (China)
**GDPR**: Individual rights, independent oversight, judicial review
**China**: [[Entity - China Social Credit System]] operates with no meaningful privacy protections

## Extraterritorial Impact

### Global Standard
GDPR has influenced data protection globally:
- **Brazil**: LGPD (Lei Geral de Proteção de Dados)
- **California**: CCPA (California Consumer Privacy Act)
- **Other jurisdictions**: Adopted similar principles

### Digital ID Systems Globally
GDPR principles provide benchmark for evaluating systems:
- [[Entity - EU EUDI Wallet]]: Full compliance
- [[Entity - Estonia e-ID System]]: Largely compliant
- [[Entity - India Aadhaar System]]: Would not comply with GDPR
- [[Entity - China Social Credit System]]: Completely incompatible with GDPR

## Connection to Key Investigations
- [[Investigation - Digital Identity-Industrial Complex Global Architecture]] - Legal framework for rights-respecting systems
- [[Investigation - Digital ID Systems as Tools of Authoritarian Control]] - Contrast to authoritarian frameworks

## Related Entities
- [[Entity - European Union]]
- [[Entity - EU EUDI Wallet]] - GDPR-compliant design
- [[Entity - eIDAS 2.0 Regulation]] - Requires GDPR compliance

## Related Findings
- [[Finding - EU EUDI Wallet Privacy by Design Model]] - GDPR principles embedded
- [[Finding - Kenya Litigation DPIA Requirement Precedent]] - DPIA requirement
- [[Finding - Function Creep Welfare to Surveillance Repurposing]] - Purpose limitation prevents
- [[Finding - Centralized Database Single Point of Failure]] - Security requirements address

---
*Compiled by*: Research Agent
*Date*: 2025-10-01
