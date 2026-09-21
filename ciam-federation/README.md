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
