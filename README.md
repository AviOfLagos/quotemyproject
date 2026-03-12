# QuoteMyProject

**QuoteMyProject** is a smart Project Estimation & Contract Generator designed specifically for software agencies. It allows clients to describe their web, mobile, or AI projects through a structured, multi-step configurator. Based on their selections, the system automatically calculates a realistic timeline, provides a cost estimate, and generates a dynamic proposal and contract draft (like an MSA and Statement of Work).

This repository is built on a production-ready Next.js 16 stack, heavily optimized for SEO (Static Site Generation enabled, Internationalization ready) so it can also function as a high-converting lead magnet.

## 🚀 Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS 4
- **Database / ORM:** PostgreSQL (via DrizzleORM) & PGlite for local dev
- **Authentication:** Clerk
- **i18n:** next-intl + Crowdin
- **Error Monitoring:** Sentry & Spotlight
- **Analytics:** PostHog
- **Linting/Testing:** ESLint, Prettier, Husky, Vitest, Playwright

## 📦 Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Configure Environment Variables
You MUST have a `.env` or `.env.local` file at the root.

**🚨 The Must-Have Environment Variables:**
According to `src/libs/Env.ts`, the application will **fail to build or start** if the following environment variables are missing.

```env
# 1. Clerk Authentication (Get these from your Clerk dashboard)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
CLERK_SECRET_KEY=sk_test_...

# 2. Database URL (A local PGLite fallback is provided in .env by default)
DATABASE_URL=postgresql://postgres:postgres@127.0.0.1:5432/postgres
```

*Note: All other variables (Arcjet, PostHog, Sentry telemetry) are strictly optional and the app will boot without them.*

### 3. Run the Development Server
```bash
npm run dev
```

The app will start on standard local ports (usually `localhost:3000` or `3001`).

## 🧠 Core Concept
1. **Top Configurators:** Clients select features (auth, payments, AI), platform targets, design levels, and integrations.
2. **Estimation Engine:** Calculates base hours + feature hours, multiplied by platform & timeline multipliers.
3. **Output:** A downloaded Proposal PDF, timeline estimate, and an automatic Lead captured for the agency!
