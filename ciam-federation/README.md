# CIAM Federation Demo (Auth0 → Grafana)

This folder shows my OIDC federation setup where Grafana uses Auth0 as the OpenID Provider.

## Screenshots
### 1. Auth0 Login Page
![Grafana Login](./grafana-login.png)

### 2. Logged Into Grafana Using Auth0
![Grafana Logged In](./grafana-logged-in.png)

## OIDC Flow
Grafana redirects the user to Auth0, which authenticates the user and returns an ID token.  
The login uses the OIDC Authorization Code Flow with PKCE for secure token exchange.

# OAuth Delegated Authorization (GitHub → SimplifyIAM OAuth Lab)

This section shows my OAuth 2.0 delegated authorization setup where the SimplifyIAM OAuth Lab app requests access to my GitHub profile.

## Screenshots
### 1. GitHub Consent Screen (Requested Scope)
![GitHub Consent](./github-consent.png)

### 2. Successful API Call to GitHub
![GitHub User Response](./github-user-response.png)

## Delegated Authorization & Scopes
OAuth is delegated authorization. Instead of giving the app my password, I authorize it to act on my behalf with limited permissions.

The `read:user` scope only allows reading my public GitHub profile.  
When I tried to access private repos, GitHub returned nothing because the token did not have permission.

This proves OAuth enforces least privilege:  
**Apps only get exactly what the user approves.**

## Key Difference: OAuth vs OIDC
- **OAuth = Authorization**  
  Controls what the app is allowed to do (e.g., read my profile).

- **OIDC = Authentication**  
  Proves who the user is (e.g., logging into Grafana using Auth0).

OAuth gives access.  
OIDC gives identity.

# SAML Federation (Auth0 → Salesforce)

This section demonstrates SAML 2.0 federation between Auth0 and Salesforce.

## Screenshots

### Salesforce Login Page with Auth0 SSO

./salesforce-auth0-login-page.png

### Decoded SAML Response with NameID

./saml-response-nameid.png

## SAML Flow

- Identity Provider (IdP): Auth0
- Service Provider (SP): Salesforce
- Protocol: SAML 2.0

Salesforce redirects users to Auth0 for authentication. Auth0 issues a signed SAML assertion that Salesforce validates before granting access.

## Identity Mapping

Salesforce uses the Federation ID stored on the user record to map the incoming SAML assertion.

The NameID in the assertion must match the user's Federation ID for successful authentication.

## Trust Mechanism

Salesforce trusts Auth0 by validating the digital signature on the SAML assertion using the configured X.509 certificate.

