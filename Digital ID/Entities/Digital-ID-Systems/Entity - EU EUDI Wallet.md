---
type: entity
entity-type: digital-id-system
aliases: ["European Digital Identity Wallet", "EUDI Wallet", "EU Digital Identity"]
status: development
affiliation: [[Entity - European Union]]
mandate: 2026
system-type: Decentralized Digital Identity Wallet
tags: [entity, entity/digital-id-system, EU, privacy-by-design, voluntary, user-control, rights-centric]
---

# EU EUDI Wallet

## Overview
The European Digital Identity Wallet (EUDI Wallet) represents the **rights-centric model** of digital identity implementation, in stark contrast to authoritarian systems like [[Entity - China Social Credit System]] and exclusion-prone systems like [[Entity - India Aadhaar System]]. Mandated by [[Entity - eIDAS 2.0 Regulation]], the EUDI Wallet is designed to be **voluntary, user-controlled, and privacy-preserving**, embodying [[Finding - EU EUDI Wallet Privacy by Design Model]].

## System Details
- **Jurisdiction**: [[Entity - European Union]] (27 member states)
- **Legal Basis**: [[Entity - eIDAS 2.0 Regulation]]
- **Mandate**: All member states must offer by 2026
- **Status**: Development phase, pilot programs
- **System Type**: Decentralized mobile wallet

## [[Finding - EU EUDI Wallet Privacy by Design Model]]

### Core Design Principles

**1. Voluntary Adoption**
- **Not Mandatory**: Citizens can choose whether to use
- **Accessible Alternatives**: Non-digital options must remain available
- **No Coercion**: Cannot be denied services for non-use

**2. User Control**
- **Local Data Storage**: Identity data stored on user's device, not central database
- **Selective Disclosure**: Users share only necessary attributes (e.g., "over 18" without revealing birthdate)
- **Data Minimization**: Collect and share least amount of data required
- **User Consent**: Explicit permission for each data sharing instance

**3. Privacy by Design**
- **No Central Database**: No government repository of citizen data
- **Pseudonymization**: Online transactions use pseudonymized data where possible
- **Offline Functionality**: Cash-like privacy for small peer-to-peer transactions
- **Zero-Knowledge Proofs**: Prove attribute without revealing underlying data

**4. Legal Safeguards**
- **[[Entity - GDPR]] Compliance**: Full alignment with EU data protection law
- **Right to Erasure**: Users can delete their data
- **Data Portability**: Users can transfer data between providers
- **Legal Recourse**: Strong enforcement mechanisms and penalties

### Technical Architecture

**Decentralized Model:**
- **Device-Based**: Wallet app on user's smartphone
- **No Central Registry**: Each member state issues credentials, no EU-wide database
- **Interoperability**: Recognized across all member states and private services
- **Cryptographic Security**: Public key infrastructure for verification

## Comparison to Other Models

### vs. China Social Credit System
**EUDI**: Voluntary, privacy-preserving, user-controlled
**China**: Mandatory, surveillance-oriented, government-controlled punishment system

### vs. India Aadhaar
**EUDI**: Decentralized, no central biometric database, voluntary
**Aadhaar**: Centralized database, de facto mandatory, [[Finding - Aadhaar Function Creep Voluntary to Mandatory]]

### vs. UK Brit Card
**EUDI**: Rights-based, privacy by design, voluntary
**[[Entity - UK Brit Card]]**: Security-state justification, proposed mandatory

### vs. US REAL ID
**EUDI**: EU-wide voluntary system with strong privacy protections
**[[Entity - US REAL ID Act]]**: Federal coercion, biometric standardization, security framing

## Implementation Challenges

### Technical Complexity
- **Interoperability**: 27 different national systems must work seamlessly
- **Standards**: Complex technical specifications (W3C Verifiable Credentials, etc.)
- **Vendor Ecosystem**: Multiple wallet providers, credential issuers, verifiers
- **User Experience**: Must be simple enough for mass adoption

### Slow Rollout
The rights-preserving architecture creates implementation challenges:
- **2026 Mandate**: Later than many centralized systems
- **Pilot Programs**: Extended testing before full deployment
- **Coordination**: 27 member states with different legacy systems

### Political Pressures
Tensions between privacy and other objectives:
- **Law Enforcement**: Pressure for backdoor access, reduced privacy
- **Corporate Lobbying**: Private sector prefers centralized, profitable models
- **Security Concerns**: Terror/crime prevention arguments for more surveillance

## eIDAS 2.0 Regulation

### [[Entity - eIDAS 2.0 Regulation]]
Updated regulation mandating EUDI Wallet:
- **Entry into Force**: 2024
- **Member State Compliance**: 2026
- **Scope**: Public and private sector acceptance
- **Standards**: Technical specifications for interoperability

### Governance
- **European Commission**: Overall coordination and standards
- **Member States**: Issue wallets to their citizens
- **Private Sector**: Can accept EUDI credentials for services
- **Data Protection Authorities**: Enforcement of privacy rules

## Use Cases

### Government Services
- Tax filing
- Healthcare records access
- Social benefits applications
- Voting (potential future use)
- Cross-border travel within EU

### Private Sector
- Age verification (e.g., alcohol purchase without revealing birthdate)
- Banking KYC (selective disclosure of required attributes)
- Rental agreements and contracts
- Employment verification

### Selective Disclosure Examples
- **Prove over 18**: Without revealing exact birthdate
- **Prove EU residency**: Without revealing specific address
- **Prove professional qualification**: Without revealing full education history

## Resistance Perspective

### Civil Society Support
**[[Entity - Electronic Frontier Foundation]]**, **[[Entity - Access Now]]**, **[[Entity - Privacy International]]** generally support EUDI approach as closest to their principles:
- Voluntary adoption
- User control and consent
- No centralized database
- Strong legal protections

### Remaining Concerns
Even rights-oriented systems raise issues:
- **Normalizing Digital ID**: Even voluntary systems create pressure to adopt
- **Exclusion Risk**: Those without smartphones or technical literacy
- **Function Creep**: Future governments may mandate what is currently voluntary
- **Corporate Access**: Private sector integration could lead to discrimination

## Connection to Key Investigations
- [[Investigation - Digital Identity-Industrial Complex Global Architecture]] - Rights-centric alternative model
- [[Investigation - Digital ID Global Implementation and Control Mechanisms]] - EU implementation

## Related Entities
- [[Entity - European Union]]
- [[Entity - eIDAS 2.0 Regulation]] - Legal mandate
- [[Entity - GDPR]] - Privacy legal framework
- [[Entity - European Central Bank]] - Digital euro integration potential
- [[Entity - Electronic Frontier Foundation]] - Digital rights advocacy
- [[Entity - Access Now]] - Human rights framework

## Related Findings
- [[Finding - EU EUDI Wallet Privacy by Design Model]] - Architectural principles
- [[Finding - Access Now WhyID Human Rights Framework]] - Alignment with rights-based approach
- [[Finding - EFF Mandatory ID Opposition Decentralized Advocacy]] - Voluntary, decentralized design

## Open Questions
- [ ] Implementation timeline and readiness by 2026
- [ ] Interoperability testing results across member states
- [ ] Corporate sector adoption and integration
- [ ] Law enforcement pressure for reduced privacy features
- [ ] Integration with potential digital euro CBDC
- [ ] Resistance to function creep and mandatory adoption pressures
- [ ] Accessibility for non-smartphone users and elderly

---
*Compiled by*: Research Agent
*Date*: 2025-10-01
