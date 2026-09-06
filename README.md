# CompanionDay Complete Starter

One project containing:
- Public website
- Registration with name, phone, email and password
- ₹499 Razorpay registration payment
- Login blocked until payment is confirmed
- Companion listing and booking requests
- Owner-only admin panel at `/admin.html`
- Admin can add companion profiles, upload photos, verify/unverify and delete
- SQLite database

## Setup
1. Install Node.js 20+.
2. Copy `.env.example` to `.env`.
3. Set a strong ADMIN_PASS and SESSION_SECRET.
4. Add live/test Razorpay API keys.
5. Run `npm install`
6. Run `npm start`
7. Public site: `http://localhost:3000`
8. Admin: `http://localhost:3000/admin.html`

## Production checklist
Use HTTPS, a strong session secret, a managed database/backups, object storage for images, rate limiting, CSRF protection, secure cookies, Razorpay server-side signature verification/webhooks, audit logs, privacy/terms/consent flows, age/identity verification, reporting/blocking, and appropriate local legal/compliance review before taking real users or payments.
