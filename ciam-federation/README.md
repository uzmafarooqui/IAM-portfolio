# CIAM Federation Demo (Auth0 → Grafana)

This folder shows my OIDC federation setup where Grafana uses Auth0 as the OpenID Provider.

## Screenshots
- grafana-login.png — Grafana login page showing the "Sign in with Auth0" button.
- grafana-logged-in.png — Logged into Grafana using my Auth0 user.

## OIDC Flow
Grafana redirects the user to Auth0, which authenticates the user and returns an ID token.  
The login uses the OIDC Authorization Code Flow with PKCE for secure token exchange.
