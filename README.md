# IAM Implementation Portfolio

## Uzma Farooqui

**SimplifyIAM Live Cohort 1**

**LinkedIn:** [Uzma Farooqui](https://www.linkedin.com/in/uzmafarooqui)
**GitHub:** [IAM Portfolio](https://github.com/uzmafarooqui/IAM-portfolio)

---

# Portfolio Overview

This repository showcases hands-on Identity and Access Management (IAM) implementations completed during the SimplifyIAM Live Cohort.

Using SimplifyHR, midPoint, OpenLDAP, and Auth0, I designed, configured, tested, and documented a complete IAM environment covering identity governance, provisioning, lifecycle management, federation, authentication, customer identity (CIAM), and privacy-focused workflows.

The purpose of this portfolio is to demonstrate practical IAM implementation experience through working configurations, screenshots, technical artifacts, validation testing, and documented outcomes.

---

# IAM Lab Environment

| Component | Purpose |
|------------|------------|
| SimplifyHR | HR Source of Truth |
| midPoint | Identity Governance & Administration (IGA) |
| OpenLDAP | Target Directory |
| Auth0 | Authentication, Federation, MFA, and CIAM |

---

# Capabilities Built

## Foundations

- IAM Architecture and Environment

## Identity Governance (IGA)

- HR-Driven Identity Onboarding (Joiner)
- Provisioning to a Target Directory
- Mover Lifecycle Management
- Leaver Lifecycle Management
- Role-Based Access Control (RBAC)
- Access Certification and Governance

## Access Management and Federation

- OIDC Single Sign-On
- OAuth 2.0 and JWT Validation
- SAML Federation
- Multi-Factor Authentication (MFA)

## Customer Identity and Access Management (CIAM)

- Progressive Profiling
- Federated Identity Chaining
- Account Linking
- Consent Management
- GDPR Right to Erasure

## Outcome

- Technical Portfolio Development
- IAM Interview Readiness
- Career Preparation

---

# Portfolio Index

## Foundations
- ./architecture-environment

## Identity Governance (IGA)
- ./joiner-leaver
- ./rbac-roles
- ./access-certification

## Access Management and Federation
- ./ciam-federation
- ./ciam-security

## Customer Identity and Access Management (CIAM)
- ./ciam-ux
- ./ciam-federated-identity-chaining
- ./ciam-account-linking
- ./ciam-consent
- ./ciam-erasure
---

# What You'll Find in This Repository

Each project folder contains technical evidence, including:

- Screenshots
- Configuration files
- midPoint mappings
- Auth0 Actions
- OpenLDAP records
- JWT analysis
- SAML assertions
- API requests and responses
- Validation testing
- Lessons learned
- Enterprise technology mappings

The goal is not only to explain IAM concepts but also to demonstrate working implementations and practical IAM skills.

---

# IAM Architecture and Environment

## Capability

Design and deploy a complete IAM environment.

## What I Built

I deployed and integrated SimplifyHR, midPoint, OpenLDAP, and Auth0 into a working IAM lab environment.

The solution established trusted identity flows from the HR source through governance and provisioning systems into the target directory.

## Why It Matters

IAM platforms rely on authoritative identity data flowing securely across systems while maintaining governance and accountability.

## Evidence

- Architecture diagrams
- Connectivity validation
- Identity flow screenshots
- Environment deployment documentation

## Skills Demonstrated

- IAM Architecture
- Identity Governance
- Directory Services
- OpenLDAP Administration
- midPoint Administration

---

# HR-Driven Identity Onboarding (Joiner)

## Capability

Provision new user accounts automatically from HR onboarding events.

## What I Built

I configured correlation, reconciliation, inbound mappings, and provisioning workflows in midPoint.

When a new employee was created in SimplifyHR, the account was automatically provisioned into OpenLDAP.

## Why It Matters

Automated onboarding improves consistency, reduces manual administration, and ensures users receive appropriate access quickly.

## Evidence

- User creation screenshots
- Correlation rules
- Reconciliation results
- OpenLDAP account creation

## Skills Demonstrated

- Identity Provisioning
- Correlation
- Reconciliation
- Joiner Automation
- Lifecycle Management

---

# Mover and Leaver Lifecycle Management

## Capability

Modify or revoke access as employee roles and employment status change.

## What I Built

I configured lifecycle-driven workflows that automatically updated user access during transfers and disabled accounts for departing employees.

## Why It Matters

Users should only retain access appropriate for their current role.

Disabling accounts instead of deleting them preserves audit history and supports compliance requirements.

## Evidence

- Before-and-after screenshots
- Role changes
- Access updates
- Account disablement validation

## Skills Demonstrated

- Identity Lifecycle Management
- RBAC
- Access Revocation
- Mover Automation
- Leaver Automation

---

# Access Management and Federation

## Capability

Provide secure authentication and federation using industry-standard protocols.

## What I Built

I configured Auth0-based federation solutions and validated authentication using:

- OIDC
- OAuth 2.0
- JWTs
- SAML Assertions
- MFA

I also implemented CIAM-focused use cases including consent management, account linking, progressive profiling, and privacy workflows.

## Why It Matters

Federation centralizes authentication, improves security, and simplifies the user experience across applications.

## Evidence

- JWT screenshots
- SAML assertions
- MFA screenshots
- Federation configuration
- Authentication testing

## Skills Demonstrated

- OIDC
- OAuth 2.0
- JWT Analysis
- SAML
- Federation
- MFA
- Auth0 Administration

---

# Customer Identity and Access Management (CIAM)

## Progressive Profiling

Implemented progressive profiling using Auth0 Actions and custom claims to collect user information over time.

## MFA and Step-Up Authentication

Configured MFA using TOTP and analyzed authentication assurance through AMR claims.

## Federated Identity Chaining

Integrated Google and LinkedIn federation through Auth0 and analyzed trust relationships between identity providers.

## Account Linking

Linked multiple user identities into a unified customer profile using the Auth0 Management API and Postman.

## Consent Management

Implemented granular consent collection, withdrawal workflows, and GDPR Article 7 compliance requirements.

## GDPR Right to Erasure

Simulated privacy-focused account deletion processes and documented downstream data removal requirements.

---

# Enterprise Technology Mapping

| Lab Technology | Enterprise Equivalent |
|----------------|----------------------|
| midPoint | SailPoint IdentityNow / IdentityIQ |
| OpenLDAP | Active Directory |
| Auth0 | Microsoft Entra ID / Okta |
| Access Certification | Access Reviews |
| OIDC | Workforce & CIAM Authentication |
| SAML | Enterprise Single Sign-On |
| Consent Management | Privacy & Compliance Programs |
| Account Linking | Customer Identity Correlation |

---

# Technologies Demonstrated

- Auth0
- midPoint
- OpenLDAP
- Microsoft Entra ID
- Active Directory
- OAuth 2.0
- OpenID Connect (OIDC)
- SAML 2.0
- JWT
- MFA
- RBAC
- REST APIs
- Postman
- Identity Provisioning
- Identity Governance
- Federation
- CIAM
- Identity Lifecycle Management
- Access Certification
- Consent Management
- Account Linking
- Progressive Profiling
- GDPR Right to Erasure

---

# Resume Highlights

- Implemented automated identity provisioning workflows using midPoint, including correlation, reconciliation, and OpenLDAP account creation.
- Built joiner, mover, and leaver processes that automated lifecycle-driven access changes and account deprovisioning.
- Configured Auth0-based federation using OIDC, OAuth 2.0, SAML, MFA, and JWT analysis.
- Implemented CIAM solutions including consent management, account linking, progressive profiling, and GDPR privacy workflows.
- Developed and documented a complete IAM environment integrating identity governance, provisioning, authentication, federation, and customer identity services.

---

# Career Outcome

Before joining the SimplifyIAM cohort, my experience focused primarily on supporting IAM operations including Active Directory, Microsoft Entra ID, access governance, authentication, and identity lifecycle management.

Through this portfolio, I designed, configured, tested, and documented a complete IAM environment covering governance, provisioning, federation, authentication, privacy, and CIAM capabilities.

---

# Roles I Am Targeting

- IAM Engineer
- Associate IAM Engineer
- IAM Analyst
- IAM Administrator
- Identity Engineer
- Identity Governance Analyst
- Access Management Engineer
- Entra ID Engineer
- CIAM Engineer

---

# Contact

I am actively pursuing Identity and Access Management opportunities and continuing to expand my expertise in identity governance, federation, access management, CIAM, and Microsoft Entra ID.

**LinkedIn:** https://www.linkedin.com/in/uzmafarooqui

**GitHub:** https://github.com/uzmafarooqui/IAM-portfolio
