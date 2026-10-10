# IAM Implementation Portfolio

**Name:** Uzma Farooqui  
**Cohort:** SimplifyIAM Live Cohort 1  
**LinkedIn:** https://www.linkedin.com/in/uzmafarooqui  
**GitHub:** https://github.com/uzmafarooqui/IAM-portfolio  
**Completed:** May 2026

---

# About This Portfolio

This portfolio documents my hands-on Identity and Access Management (IAM) implementations completed throughout the SimplifyIAM Live Cohort.

Using midPoint, OpenLDAP, and Auth0, I built an end-to-end IAM environment that simulates real-world identity governance, provisioning, authentication, federation, customer identity (CIAM), and lifecycle management processes.

Throughout the program, I configured identity synchronization, automated provisioning workflows, implemented access management solutions, and explored modern CIAM concepts including MFA, account linking, consent management, progressive profiling, and GDPR right-to-erasure.

The goal of this portfolio is to demonstrate practical IAM implementation experience through real configurations, screenshots, workflows, and documented lessons learned.

---

# Environment

| Component | Purpose |
|------------|------------|
| midPoint | Identity Governance and Administration (IGA) |
| SimplifyHR (Flask) | HR Source of Truth |
| OpenLDAP | Target Directory |
| Auth0 | Access Management, Federation, MFA, and CIAM |

---

# Core IAM Projects
| Project | Description |
|----------|----------|
| architecture-environment | IAM architecture, identity flow, and platform deployment |
| joiner-workflow | Automated joiner provisioning using correlation and reconciliation |
| mover-leaver | Lifecycle-driven access changes and deprovisioning |
| auth0-federation | OIDC, OAuth 2.0, JWT, SAML, and federation |
| rbac-roles | Role-Based Access Control (RBAC) |
| access-certification | Access reviews and governance |
| ciam-ux | Progressive profiling |
| ciam-security | MFA and step-up authentication |
| federated-identity-chaining | Social login and federation |
| ciam-account-linking | Account linking and identity correlation |
| ciam-consent | Consent management and GDPR Article 7 |
| ciam-erasure | GDPR Right to Erasure |

---

## Why These Projects Matter

Identity and Access Management is about ensuring the right users have the right access at the right time.

These projects demonstrate practical implementation experience across identity governance, provisioning, authentication, federation, customer identity, lifecycle management, and privacy-focused workflows.

The goal is not only to describe IAM concepts, but to demonstrate working implementations and real-world IAM use cases.

---

## Evidence Included Throughout This Repository

Each project folder contains implementation evidence including:

- Screenshots
- Configuration examples
- OpenLDAP account records
- JWT analysis
- SAML assertions
- Access review evidence
- Federation configurations
- API results
- Validation testing

The objective is not only to describe IAM concepts but to demonstrate practical implementation experience through working implementations and documented outcomes.

---

## IAM Architecture and Environment

### What I Built

I deployed the core IAM lab environment and established connectivity between SimplifyHR, midPoint, and OpenLDAP. I validated identity data flow from the HR source into the identity platform and target directory.

### Skills Demonstrated

- IAM Architecture
- Directory Services
- OpenLDAP Administration
- midPoint Configuration
- Identity Data Flow
- Identity Lifecycle Foundations

---

## Joiner Provisioning

### What I Built

I implemented automated joiner provisioning using correlation rules, inbound mappings, and reconciliation processes within midPoint. New hires created in SimplifyHR were automatically provisioned into OpenLDAP.

### Skills Demonstrated

- Identity Provisioning
- Correlation Rules
- Reconciliation
- Joiner Processes
- OpenLDAP Account Creation

---

## Mover and Leaver Lifecycle Management

### What I Built

I configured role-based access changes and lifecycle workflows for employee transfers and departures. HR status changes automatically updated access assignments and disabled accounts in OpenLDAP.

### Skills Demonstrated

- Role-Based Access Control (RBAC)
- Identity Lifecycle Management
- Mover Automation
- Leaver Automation
- Access Revocation
- User Deprovisioning

---

## OIDC and SAML Federation

### What I Built

I configured OIDC and SAML federation using Auth0 and analyzed authentication artifacts including JWTs and SAML assertions. I also implemented MFA, account linking, consent management, progressive profiling, and GDPR privacy workflows.

### Skills Demonstrated

- OpenID Connect (OIDC)
- OAuth 2.0
- SAML 2.0
- JWT Analysis
- Multi-Factor Authentication (MFA)
- Federation
- CIAM Implementation
- Auth0 Administration

---

## Portfolio Development and Career Preparation

### What I Built

I consolidated all IAM implementations into a professional technical portfolio and translated the work into interview-ready projects and resume-ready accomplishments.

### Skills Demonstrated

- Technical Documentation
- Portfolio Development
- Career Branding
- Resume Optimization
- Interview Preparation

---

# CIAM Projects

## CIAM UX – Progressive Profiling

### Overview

Implemented progressive profiling using Auth0 Actions and custom token claims.

### Skills Demonstrated

- Progressive Profiling
- Custom JWT Claims
- User Experience Optimization
- Auth0 Actions

### Folder

```text
ciam-ux/
```

---

## CIAM Security – MFA and Step-Up Authentication

### Overview

Configured MFA using TOTP and analyzed AMR claims to understand authentication strength and step-up authentication patterns.

### Skills Demonstrated

- Multi-Factor Authentication
- TOTP
- Step-Up Authentication
- AMR Claims
- Token Analysis

### Folder

```text
ciam-security/
```

---

## Federated Identity Chaining

### Overview

Configured LinkedIn federation through Auth0 and analyzed trust relationships across identity providers.

### Skills Demonstrated

- Federation
- OIDC
- Identity Chaining
- Social Login
- JWT Analysis

### Folder

```text
federated-identity-chaining/
```

---

## CIAM Account Linking

### Overview

Created separate database and Google identities using the same email address and linked them using the Auth0 Management API and Postman.

### Skills Demonstrated

- Identity Correlation
- Account Linking
- REST APIs
- Auth0 Management API
- CIAM Security

### Folder

```text
ciam-account-linking/
```

---

## CIAM Right to Erasure

### Overview

Simulated GDPR right-to-erasure workflows using the Auth0 Management API and documented downstream data deletion requirements.

### Skills Demonstrated

- GDPR Compliance
- Data Privacy
- User Deletion Workflows
- REST APIs
- Data Retention Analysis

### Folder

```text
ciam-erasure/
```

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
- Joiner / Mover / Leaver Processes
- Account Linking
- Consent Management
- Progressive Profiling
- GDPR Right to Erasure

---

# Resume Highlights

- Implemented automated identity provisioning workflows using midPoint, including correlation, reconciliation, and OpenLDAP account creation.
- Built joiner, mover, and leaver processes that automated lifecycle-driven access changes and account deprovisioning.
- Configured Auth0-based access management solutions including OIDC, SAML federation, MFA, and JWT analysis.
- Implemented customer identity workflows including consent management, progressive profiling, account linking, and GDPR right-to-erasure.
- Developed and documented a complete IAM environment integrating identity governance, provisioning, authentication, and CIAM capabilities.

---

# My Transformation

## Where I Started

Before this cohort, I had experience supporting IAM operations including Active Directory, Microsoft Entra ID, access governance, identity lifecycle management, and authentication processes. However, I had limited hands-on experience building IAM platforms and configuring modern federation technologies.

## Where I Am Now

I have designed, configured, and tested a complete IAM environment using midPoint, OpenLDAP, and Auth0. I can demonstrate identity provisioning, reconciliation, lifecycle management, federation, MFA, account linking, consent management, progressive profiling, JWT analysis, and GDPR erasure workflows using working implementations.

---

# Roles I Am Targeting

- IAM Engineer
- Associate IAM Engineer
- Identity Engineer
- IAM Analyst
- CIAM Engineer
- Entra ID Engineer
- Access Management Engineer
- IAM Administrator
- Identity Governance Analyst

---

# Repository Structure

```text
IAM-portfolio/
│
├── architecture-environment/
├── joiner-workflow/
├── mover-leaver/
├── auth0-federation/
├── rbac-roles/
├── access-certification/
├── ciam-ux/
├── ciam-security/
├── federated-identity-chaining/
├── ciam-account-linking/
├── ciam-erasure/
└── README.md
```

---

# Contact

I am actively pursuing Identity and Access Management opportunities and continuing to expand my expertise in identity governance, access management, CIAM, and federation technologies.

**LinkedIn:** https://www.linkedin.com/in/uzmafarooqui
