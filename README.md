# FinSuraksha

**Learn Money. Stay Safe. Build a Better Future.**

FinSuraksha is a responsive financial-literacy and digital-safety learning website concept for people across India. It aims to make everyday money skills easier to understand and help people recognise common online fraud patterns.

## Features in this prototype

- Responsive homepage for phones, tablets, laptops and desktops.
- Financial lessons covering savings, budgeting, banking, digital payments, fraud awareness and loans.
- Educational case studies for common scam patterns, with warning signs and suggested safe actions.
- Demonstration cyber-safety alert panel with a clear DEMO label.
- Searchable scam-awareness case library.
- Interactive reducing-balance EMI calculator.
- Short UPI safety quiz.
- Language selector framework for the 22 languages in the Eighth Schedule plus English.
- Font-size controls and accessible, high-contrast layout choices.
- Curated links to official Indian government, regulator and payment-system resources.
- Vercel-ready Vite + React project.

## Important scope and data notes

This is an educational prototype. The language selector lists all 22 scheduled languages plus English, but the lesson content in this version is primarily English. Reviewed translations, audio narration and subtitles need to be added before claiming full multilingual content support.

The scam examples and alert are educational demonstrations, not live incident reports or live government alerts. No live government database, NCRP, telecom or incoming-call integration is connected. Live alerts should only be published after checking an authoritative source, recording its URL and date, and completing human review. Never expose victims' personal information or label an unverified phone number as fraudulent.

FinSuraksha is not a bank, lender, regulator, government portal or emergency reporting service. If money has been lost to cyber financial fraud in India, contact the bank immediately and report through **1930** or https://cybercrime.gov.in/. For suspected fraudulent communications, see https://sancharsaathi.gov.in/.

## Tech stack

- React 18
- Vite 6
- Lucide React icons
- Plain CSS (responsive breakpoints)
- Vercel deployment configuration

## Run locally

Requirements: Node.js 18 or later and npm.

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Open https://vercel.com/ and sign in.
2. Choose **Add New → Project**.
3. Import the GitHub repository: `shiva4545sharma-ops/FinSuraksha`.
4. Vercel should detect Vite automatically.
5. Use build command `npm run build` and output directory `dist`.
6. Click **Deploy**.

No environment variables are required for this static prototype.

## Suggested next development steps

1. Add reviewed translations and native-speaker audio for each supported language.
2. Add an admin workflow for submitting, verifying, reviewing and expiring cyber-safety advisories.
3. Integrate only authorised/public data feeds and retain source, publication date and last-checked time.
4. Add a backend only when user accounts, saved progress or notification subscriptions are needed.
5. Add privacy, security, accessibility and content-review testing before public launch.

## Official learning and reporting resources

- RBI: https://www.rbi.org.in/
- SEBI Investor Education: https://investor.sebi.gov.in/
- NPCI: https://www.npci.org.in/
- National Cyber Crime Reporting Portal: https://cybercrime.gov.in/
- Sanchar Saathi: https://sancharsaathi.gov.in/
- CERT-In: https://www.cert-in.org.in/
- MyGov: https://www.mygov.in/

Always confirm current guidance on the original official website.
