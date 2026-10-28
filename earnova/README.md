# Earnova — Skills Meet Opportunity

**Powered by Jerk Solutions**

Earnova is a mobile-first prototype for a global freelancing marketplace connecting clients and freelancers.

## Included
- Responsive landing page and marketplace design
- Sample project cards with search, category and budget filters
- Local demo client/freelancer profile flow
- Local demo project posting
- KSh 100 registration-fee disclosure
- M-Pesa STK Push placeholder (does not initiate or collect payments)

## Important limitations
This is a **static front-end prototype**, not a production marketplace. GitHub Pages cannot safely store Daraja API secrets or verify payment callbacks. Demo profiles and user-created projects are stored only in the current browser using local storage. They are not secure accounts and do not sync across users or devices.

Before accepting real registration fees or launching publicly, add a secure backend and database, real authentication, authorized Safaricom Daraja integration, server-side callback verification, clear refund/terms/privacy pages, moderation, and support processes. Never ask users for an M-Pesa PIN. Never mark a payment successful without verified provider confirmation.
