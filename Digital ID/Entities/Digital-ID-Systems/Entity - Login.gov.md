---
type: entity
entity-type: digital-id-system
aliases: ["Login.gov", "USAGov Login"]
status: active
affiliation: [[Entity - United States]]
launched: 2017
system-type: Federal Digital Identity Platform
tags: [entity, entity/digital-id-system, US, federal-platform, Idemia-contract]
---

# Login.gov

## Overview
Login.gov is the [[Entity - United States]] federal government's centralized digital identity platform for accessing government services online. In 2025, [[Entity - Idemia]] was awarded a **$194.5 million, 10-year contract** ([[Event - Login.gov Idemia 194.5 Million Contract]]) to provide identity proofing services, demonstrating how government digital ID systems create massive, long-term revenue streams for the biometric [[Investigation - Digital Identity-Industrial Complex Global Architecture]].

## System Details
- **Country**: [[Entity - United States]]
- **Launch**: 2017
- **Administrator**: U.S. General Services Administration (GSA)
- **Purpose**: Single sign-on for federal government services
- **Enrollment**: 100+ million accounts (as of 2025)

## [[Event - Login.gov Idemia 194.5 Million Contract]]

### Contract Details
**Award**: $194.5 million over 10 years to [[Entity - Idemia]]

**Services:**
- **Identity Proofing**: Verification that user is who they claim to be
- **Facial Recognition**: Biometric matching against government ID documents
- **Document Verification**: Automated analysis of driver's licenses, passports
- **Liveness Detection**: Prevention of spoofing attacks with photos/videos

### Corporate Revenue Model
The Idemia contract exemplifies [[Finding - Thales Idemia Government Contract Dependency Model]]:
- **Long-Term**: 10-year agreement guarantees sustained revenue
- **Scale**: 100+ million users, continuous new enrollments
- **Vendor Lock-In**: Proprietary technology creates switching costs
- **Maintenance**: Ongoing support and technology upgrades

## Architecture

### Two-Factor Authentication
Login.gov provides:
1. **Password**: Traditional authentication factor
2. **Second Factor**: SMS, authentication app, security key, or biometric

### Identity Proofing Levels
- **IAL1**: Self-asserted identity (email only)
- **IAL2**: Verified identity (Idemia facial recognition + document verification)

Higher-security services require IAL2 (Idemia verification).

## Federal Services Integration

### Connected Agencies (Partial List)
- **Social Security Administration**: Benefits applications
- **Internal Revenue Service**: Tax filing
- **Small Business Administration**: Loan applications
- **Department of Veterans Affairs**: Benefits access
- **U.S. Citizenship and Immigration Services**: Immigration applications

## Privacy and Security Concerns

### Centralized Identity Repository
Login.gov creates [[Finding - Centralized Database Single Point of Failure]]:
- **Single Target**: Biometric data for 100+ million Americans
- **High-Value**: Attractive to state-sponsored hackers, criminals
- **Permanent Risk**: Biometric data cannot be changed if compromised

### Third-Party Vendor Access
Idemia contract raises sovereignty concerns:
- **French Corporation**: Critical U.S. identity infrastructure operated by foreign company
- **Data Access**: Idemia processes sensitive biometric and identity data
- **[[Finding - Sovereignty Paradox in Oracle Cloud Dependencies]]**: Similar foreign dependency pattern

### Biometric Technology Limitations
Login.gov facial recognition subject to:
- [[Finding - Facial Recognition Accuracy Disparity by Race Gender Age]]
- [[Finding - Biometric Technology Demographic Bias Pattern]]
- [[Finding - Biometric Spoofing Presentation Attack Vulnerability]]

## Comparison to Other Systems

### vs. India Aadhaar
**Login.gov**: Federal services only, voluntary for most services
**[[Entity - India Aadhaar System]]**: All government services, de facto mandatory

### vs. Estonia e-ID
**Login.gov**: Online-only, no physical card
**[[Entity - Estonia e-ID System]]**: Smart card for in-person and online use

### vs. UK Brit Card (Proposed)
**Login.gov**: Federal services, not mandatory for employment
**[[Entity - UK Brit Card]]**: Proposed mandatory for "right to work"

## Expansion and Function Creep

### [[Finding - Function Creep Welfare to Surveillance Repurposing]]
Risk of expansion beyond initial scope:
- **Current**: Voluntary for most services
- **Potential**: Mandatory for all federal benefits
- **Future**: Integration with state/local services
- **Law Enforcement**: Database queries for investigations

### Private Sector Integration
Potential for Login.gov acceptance by:
- Banks (KYC verification)
- Employers (right to work verification)
- Age-restricted purchases
- Healthcare providers

## Connection to DIIC

### Corporate Beneficiaries
- **[[Entity - Idemia]]**: $194.5M identity proofing contract
- **Cloud Providers**: Likely AWS or other major providers for hosting
- **Biometric Vendors**: Ongoing technology refresh cycles

### Market Model
Login.gov demonstrates:
- **[[Finding - Digital ID Market Growth 16-21 Percent CAGR to 2030]]**: Government mandates drive corporate revenue
- **[[Finding - Corporate Vendor Lock-in Architecture 2024-2025]]**: Long-term dependencies
- **Transaction Fees**: Per-verification revenue model for contractors

## Connection to Key Investigations
- [[Investigation - Digital Identity-Industrial Complex Global Architecture]] - U.S. federal implementation
- [[Investigation - Digital ID Global Implementation and Control Mechanisms]] - Corporate contract model

## Related Entities
- [[Entity - United States]]
- [[Entity - Idemia]] - $194.5M identity proofing contractor
- [[Entity - National Institute of Standards and Technology]] - Technical standards

## Related Events
- [[Event - Login.gov Idemia 194.5 Million Contract]]

## Related Findings
- [[Finding - Thales Idemia Government Contract Dependency Model]]
- [[Finding - Centralized Database Single Point of Failure]]
- [[Finding - Facial Recognition Accuracy Disparity by Race Gender Age]]
- [[Finding - Function Creep Welfare to Surveillance Repurposing]]
- [[Finding - Corporate Vendor Lock-in Architecture 2024-2025]]

---
*Compiled by*: Research Agent
*Date*: 2025-10-01
