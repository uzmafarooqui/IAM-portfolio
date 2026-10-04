# CIAM Right to Erasure at Scale

In this lab, I simulated a GDPR Right to Erasure request using the Auth0 Management API.

I created a test user, deleted the account using the Management API, and verified that the user record was removed from Auth0.

## Before Deletion

user-before-delete.png

The test user existed in Auth0 with a unique user ID.

## Deletion Response

delete-response-204.png

The DELETE request returned:

```text
204 No Content
```

indicating that the user was successfully deleted.

## Verification

user-not-found-after-delete.png

After deletion, the user could no longer be found in Auth0.

## Downstream Erasure Checklist

### Auth0
- Delete user profile
- Delete credentials
- Delete metadata

### Analytics Platform
- Delete events associated with the user's JWT subject (`sub`)
- Remove tracking identifiers

### Marketing Platform
- Delete marketing profile
- Remove campaign memberships
- Remove email subscriptions

### Shopping Cart
- Delete saved carts
- Delete wishlists and preferences

### Support System
- Delete or anonymize personal data in support tickets
- Retain only where legally required

### Purchase Records
- Anonymize name, email, and other identifiers
- Retain transaction amount and date for tax and regulatory compliance

## What I Learned

- Deleting an Auth0 user is only the first step in an erasure workflow.
- Customer data often exists in multiple systems.
- Erasure processes must be automated to scale.
- Legal and regulatory retention requirements may require anonymization rather than deletion.
