# BillBridge

**A listening ear. A helping hand. One less bill to worry about.**

BillBridge is being built for a charity that wants to help people navigate everyday difficulties and unexpected expenses. Its mission combines listening and solidarity: giving people somewhere to turn and enabling others to help with essential bills while preserving dignity.

## Live prototype

https://billbridge-community.netlify.app/

## Current experience

- Browse fictional bill requests by category.
- Choose a **payer** or **requester** role at registration.
- Preview a role-specific personal space, profile and activity.
- Prepare a fictional bill request or simulate a contribution.
- View sign-in and password-recovery interface previews.

## Prototype limitations

This is a static HTML/CSS/JavaScript demonstration, not a live financial or support service. There is no backend authentication, database, document storage, email recovery, bill verification, payment processing or listening/messaging service. Profile and activity data exist only in tab memory and clear on refresh. Use fictional details only.

Public aliases demonstrate the intended privacy approach; they do not provide production anonymity. Role separation is a client-side demonstration, not server-side authorization. No claim of registered charity status is made by this repository.

## Intended verification workflow

Before accepting real requests: private document submission, duplicate and consistency checks, authorized confirmation with the bill issuer of the current unpaid balance, documented reviewer approval, redacted publication, direct payment to the issuer and reconciliation. Document appearance or an AI-image detector alone must not be treated as proof of authenticity.

## Run locally

Open `index.html` in a modern browser, or serve this directory:

```sh
python3 -m http.server 8000
```

## Deployment

Upload this directory to the existing Netlify project. No build step or dependencies are required. `netlify.toml` declares the static publish directory.

## Next development priorities

Secure accounts and password recovery; persistent profiles with server-enforced roles; restricted document storage and review; listening/support workflow; verified payment integration; privacy and retention controls.
