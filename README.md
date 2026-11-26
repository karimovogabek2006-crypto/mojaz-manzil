# Mo'jaz Manzil website

This is a responsive, multilingual front-end starter website for Mo'jaz Manzil.

## Included
- Responsive landing page
- Eight language UI selector: Uzbek, English, German, Russian, French, Spanish, Chinese and Arabic
- RTL layout direction for Arabic
- Tour cards and difficulty filters
- Tour enquiry modal
- Enquiry form front-end validation
- Sustainability, guide, contact and company sections

## Important current limitation
The enquiry form is currently a front-end demo. It validates fields and displays a demo message, but it does **not** send email or save bookings. Do not publish it as a live booking service until a secure backend, database, spam protection and transactional email provider have been configured.

The sample tour names and imagery are placeholders. Confirm routes, prices, availability, guide details, legal texts, licenses and certificates before publishing.

## Run locally
1. Extract the ZIP.
2. Open the folder.
3. Double-click `index.html`, or use VS Code Live Server.
4. Test the language selector, filters, mobile layout and enquiry form.

## Before launch
1. Replace `hello@mojazmanzil.uz` with your real business email.
2. Replace sample tour information with verified information.
3. Replace image URLs with licensed company photos or properly licensed stock images.
4. Add real guide profiles and verified certificate scans.
5. Configure a backend (recommended: Next.js API routes or another server-side application).
6. Connect a PostgreSQL database and store booking requests.
7. Connect a transactional email provider or SMTP service server-side. Never place email passwords or API keys in browser JavaScript.
8. Add privacy, terms, cancellation and cookie documents reviewed for applicable law.
9. Connect a domain and HTTPS hosting.
10. Test real booking delivery, admin access, backups and spam protection.

## Suggested production stack
- Frontend/backend: Next.js + TypeScript
- Database: PostgreSQL + Prisma
- Authentication: secure server-side authentication
- Email: a transactional email provider or SMTP
- Hosting: a platform supporting Next.js and environment variables

## Brand note
Suggested tagline: “Every Step Has a Story.”
