# BuildFlow AI — Full Website MVP

This package is a complete responsive website rather than a landing-page mockup.

Included:
- Commercial SaaS-style homepage
- Feature/service sections
- Workflow section
- Working browser document generator
- Pricing page section
- FAQ
- Enquiry form with local lead storage
- Login modal/UI
- Mobile responsive design
- Production integration notes

## Run
Open `index.html` in a browser.

## To make it genuinely AI-powered and live
The browser demo currently uses deterministic JavaScript so it works immediately without an API key. For production:
- Add a secure server/backend.
- Have the backend call your chosen AI provider.
- Never expose an AI API key in `app.js`.
- Add authentication/database.
- Add Stripe/payment handling if subscriptions are offered.
- Add transactional email.
- Add privacy policy, terms, Australian business details and appropriate data/security controls.
- Add file upload/storage only after secure access controls are implemented.

## Suggested production architecture
Browser frontend -> secure backend -> AI API
                              -> database
                              -> email
                              -> payments
                              -> file storage
