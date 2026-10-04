# IAM Implementation Portfolio

**Cohort:** SimplifyIAM Live Cohort 1  
**Name:** Uzma Farooqui  
**LinkedIn:** https://www.linkedin.com/in/uzmafarooqui  
**GitHub:** https://github.com/uzmafarooqui/IAM-portfolio  
**Completed:** May 2026  
**Status:** Completed

---

# What I Built

Over five live Saturday sessions, I built a complete Identity and Access Management (IAM) environment using midPoint, OpenLDAP, and Auth0.

The environment simulates how identity lifecycle management, provisioning, governance, access management, and customer identity (CIAM) workflows operate in a real enterprise environment. Throughout the cohort, I configured identity synchronization, automated joiner/mover/leaver workflows, implemented federation and MFA, and explored customer identity use cases including consent management, progressive profiling, account linking, and GDPR right-to-erasure.

This repository documents my configurations, screenshots, implementation decisions, and lessons learned throughout the program.

---

# Environment

| Component | Purpose |
|------------|------------|
| midPoint | Identity Governance and Administration (IGA) |
| SimplifyHR (Flask) | HR Source of Truth |
| OpenLDAP | Target Directory |
| Auth0 | Access Management, Federation, MFA, and CIAM |

---

# Session Deliverables

## Saturday 1 - Architecture and Environment

### What I Built

I deployed the IAM lab environment and established connectivity between SimplifyHR, midPoint, and OpenLDAP. I validated identity data flow from the HR source into the identity platform and target directory.

### Skills Demonstrated

- IAM Architecture
- Identity Data Flow
- OpenLDAP Administration
- midPoint Configuration
- Identity Lifecycle Foundations

---

## Saturday 2 - Joiner Workflow

### What I Built

I configured HR-to-directory provisioning using correlation rules, inbound mappings, and reconciliation processes in midPoint. New hires created in SimplifyHR were automatically provisioned into OpenLDAP.

### Skills Demonstrated

- Identity Provisioning
- Correlation Rules
- Reconciliation
- Joiner Processes
- OpenLDAP Account Creation

---

## Saturday 3 - Mover and Leaver Workflows

### What I Built

I configured lifecycle workflows for role changes and employee departures. HR-driven changes automatically updated user access and disabled accounts in OpenLDAP when users left the organization.

### Skills Demonstrated

- Role-Based Access Control (RBAC)
- Identity Lifecycle Management
- Mover Workflow Automation
- Leaver Workflow Automation
- Access Revocation

---

## Saturday 4 - Access Management

### What I Built

I configured OIDC and SAML federation using Auth0 and analyzed JWTs and SAML assertions. I also implemented MFA, account linking, consent management, progressive profiling, federated identity, and GDPR right-to-erasure workflows.

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

## Saturday 5 - Career Preparation

### What I Built

I consolidated technical deliverables into a professional IAM portfolio, documented implementation decisions, and translated hands-on IAM experience into resume-ready accomplishments.

### Skills Demonstrated

- IAM Documentation
- Technical Communication
- Portfolio Development
- Interview Preparation
- Resume Development

---

# CIAM Portfolio Projects

## CIAM UX - Progressive Profiling

### Overview

Implemented progressive profiling using Auth0 Actions.

### Key Concepts

- Progressive Profiling
- Custom JWT Claims
- User Experience Optimization

### Folder

```text
ciam-ux/
```

---

## CIAM Security - MFA and Step-Up Authentication

### Overview

Configured MFA using Auth0 and verified authentication methods through JWT claims.

### Key Concepts

- TOTP Authentication
- MFA
- Step-Up Authentication
- AMR Claims

### Folder

```text
ciam-security/
```

---

## Federated Identity Chaining

### Overview

Configured LinkedIn federation through Auth0 and analyzed trust relationships between an identity provider and relying application.

### Key Concepts

- Federation
- OIDC
- Identity Chaining
- JWT Claims

### Folder

```text
federated-identity-chaining/
```

---

## CIAM Account Linking

### Overview

Created separate Auth0 and Google identities using the same email address and linked the identities through the Auth0 Management API.

### Key Concepts

- Identity Correlation
- Account Linking
- Email Verification
- CIAM Security

### Folder

```text
ciam-account-linking/
```

---

## CIAM Right to Erasure

### Overview

Simulated GDPR right-to-erasure requests through the Auth0 Management API and documented downstream deletion obligations.

### Key Concepts

- GDPR
- Privacy
- Erasure Workflows
- Data Retention
- Identity Deletion

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
- Identity Governance
- Identity Provisioning
- Federation
- Identity Lifecycle Management
- Joiner/Mover/Leaver (JML)
- Consent Management
- Progressive Profiling
- Account Linking
- GDPR Right to Erasure
- Postman
- REST APIs

---

# Resume Highlights

- Deployed and validated an IAM lab environment integrating HR, identity governance, and directory services to support end-to-end identity lifecycle management.
- Implemented automated joiner provisioning workflows using midPoint, including correlation logic, reconciliation, and account creation in OpenLDAP.
- Built automated mover and leaver workflows with role updates, account deprovisioning, and reconciliation processes driven by HR lifecycle events.
- Configured Auth0-based access management solutions including OIDC, SAML federation, MFA, JWT analysis, account linking, consent management, and GDPR erasure workflows.
- Developed a comprehensive IAM implementation portfolio showcasing identity governance, provisioning, federation, CIAM, and access management capabilities.

---

# My Transformation

## Where I Started

Before this cohort, I had IAM analyst experience supporting Active Directory, Microsoft Entra ID, access governance, lifecycle management, access requests, and authentication processes. However, I had limited hands-on experience building IAM platforms from the ground up and implementing federation technologies.

## Where I Am Now

I have built and configured a complete IAM environment using midPoint, OpenLDAP, and Auth0. I can demonstrate identity provisioning, reconciliation, joiner/mover/leaver workflows, federation, MFA, OIDC, SAML, JWT analysis, account linking, consent management, progressive profiling, and GDPR right-to-erasure automation using real implementation examples.

## Roles I Am Targeting

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
├── ciam-ux/
├── ciam-security/
├── ciam-account-linking/
├── ciam-erasure/
├── federated-identity-chaining/
└── README.md
```

---

# Contact

I am actively pursuing opportunities in Identity and Access Management and continuing to expand my expertise in identity governance, federation, CIAM, and access management technologies.

**LinkedIn:** https://www.linkedin.com/in/uzmafarooqui
