---
type: entity
entity-type: system
aliases: ["PhilSys", "Philippine Identification System"]
status: active
parent-org: "[[Philippine Statistics Authority]]"
location: "[[Manila, Philippines]]"
founded: 2018-08-06
industry: "Digital Identity Infrastructure"
tags: [entity, entity/system, philippines, digital-id, biometric, id4d]
---

# Philippine Identification System (PhilSys)

## Overview
The Philippine Identification System (PhilSys) is a centralized biometric identification platform governed by Republic Act No. 11055, providing a single national ID for all citizens and resident aliens. Managed by the [[Philippine Statistics Authority]] (PSA), PhilSys issues a PhilSys Number (PSN) and physical PhilID card, supporting digital KYC, social protection, and e-government services with financing from the [[Entity - World Bank ID4D Program]].

## System Architecture
- **Data Captured**: Biographic information, fingerprints, iris scans (for registrants aged 5+), facial image.
- **Identifiers**: PSN (permanent), PhilSys Card Number (PCN) for card presentation, PhilSys Agency Site Code for enrollment tracking.
- **Technology Stack**: Combination of PSA-owned infrastructure and MOSIP-influenced modular components; biometric deduplication handled by NEC/Idemia consortium; card production by Allcard Inc.
- **Authentication Channels**: Offline QR code, mobile PhilSys Check app, and APIs for partner agencies.

## Implementation Timeline
### 2018-2019: Legal & Pilot Phase
- RA 11055 enacted August 2018; Implementing Rules and Regulations (IRR) approved October 2019.
- Pilot registration for select government employees and beneficiaries.

### 2020-2022: Mass Registration
- Step 1 demographic registration via online and field data collection (house-to-house enumerators) targeting low-income households.
- Step 2 biometric capture at registration centers; Step 3 card distribution through PhilPost.
- By end-2022, PSA reports 73.3 million individuals registered with PSN, 50 million PhilIDs printed.

### 2023-2025: Digital Expansion
- Launch of digital PhilID (ePhilID) for smartphone and printed PDF issuance.
- Integration with Land Bank, Development Bank of the Philippines, and private banks for e-KYC.
- Mandated acceptance of PhilID across financial institutions, SIM registration (Republic Act 11934), and public services.

## Strategic Objectives
- Improve targeting of social protection programs (4Ps, SAP emergency subsidies).
- Provide foundational ID for digital transformation (Philippine Digital Economy Strategy).
- Enable National ID linked to voter registration, tax, and health systems in future phases.

## Partners & Funding
- [[Entity - World Bank ID4D Program]]: $300M "PhilSys" project loan supporting infrastructure and operations.
- [[Asian Development Bank]]: Technical assistance for digital governance.
- [[Bangko Sentral ng Pilipinas]]: Regulatory support for banking integration.
- Private sector: Globe, Smart Communications for SIM verification; PayMaya (Maya) and GCash for e-wallet KYC.

## Risks & Issues
- **Data Security**: Multiple concerns following 2023 PSA disclosure of data breach attempts.
- **Inclusion**: Accessibility challenges for indigenous populations and remote islands; reliance on offline kits.
- **Legal Oversight**: Data privacy compliance under the National Privacy Commission (NPC) continuously monitored.
- **Operational**: Backlogs in physical card printing triggered adoption of digital PhilID as interim solution.

## Connections
- Key case study in [[Finding - Five-Phase Evolution]] (Rapid move from voluntary to mandatory functions).
- Tied to [[Finding - Systematic Biometric Exclusion of Vulnerable Populations]] due to registration hurdles in rural areas.
- Featured in [[Investigation - Digital ID Global Implementation and Control Mechanisms]].

## Sources
- [[World Bank ID4D Reports]]
- PSA PhilSys progress dashboards (2024)
- Republic Act 11055 and IRR documents
- Asian Development Bank Digital Transformation assessments
- Media: BusinessWorld, Rappler, Philippine Daily Inquirer coverage (2020-2025)

---
*Research Date*: 2025-09-28
*Analyst*: Craig
*Verification Status*: #status/partially-verified

