<div align="center">
    <img src="./public/logos/logo.png" alt="SplitSage Logo" width="200" />
  <h1>💸 Splitr</h1>

  <p align="center">
    <strong>Your intelligent expense-sharing companion</strong><br/>
    Powered by AI, designed for friends, roommates, and teams
  </p>

  <p align="center">
    Built with Next.js 14, Convex, Tailwind, Clerk, and Gemini AI
    <br/><br/>
    <a href="splitr-orpin.vercel.app">🖥️ View Demo</a> • 
    <a href="#features">🚀 Features</a> • 
    <a href="#getting-started">⚙️ Getting Started</a>
  </p>

  <p align="center">
<!--     <img src="https://img.shields.io/github/stars/piyush-eon/ai-splitwise-clone?style=social" /> -->
    <img src="https://img.shields.io/badge/Next.js-14-black" />
    <img src="https://img.shields.io/badge/Tailwind-4.1.3-blue" />
    <img src="https://img.shields.io/badge/Convex-DB-orange" />
<!--     <img src="https://img.shields.io/badge/License-MIT-green" /> -->
  </p>
</div>

---

## ✨ What is Splitr?

**Splitr** is a full-stack AI-enhanced expense sharing application for groups. Whether you're planning a trip, managing a shared apartment, or tracking group budgets — Splitr helps you split costs fairly, analyze spending, and get personalized financial tips.

> 💡 **AI-Powered by Gemini** — Get smart insights, saving advice, unusual spending alerts, and monthly breakdowns.

![Dashboard Preview](./public/hero.png)

---

## 🔥 Key Features

- 👥 **Group Expense Management** — Create shared groups for trips, households, events, etc.
- 🔄 **Real-Time Sync** — All members see updates instantly (powered by Convex).
- 💰 **Smart Settlement Algorithm** — Minimizes the number of transactions between users.
- 📈 **Visual Analytics** — Charts, spending patterns, and category breakdowns.
- 🧠 **Gemini AI Insights** — Monthly financial summaries with smart tips.
- 🔔 **Payment Reminders** — Never miss a due amount.
- 🔐 **Secure Auth** — Powered by Clerk for robust user management.

---

## 🧱 Tech Stack

| Frontend       | Backend/Infra       | AI & Utilities        |
|----------------|---------------------|------------------------|
| Next.js 14     | Convex (DB + Sync)  | Google Gemini AI      |
| Tailwind CSS   | Inngest (Jobs)      | Resend (Email API)    |
| Shadcn UI      | Clerk Auth          |                        |

---

## ⚙️ Getting Started

### ✅ Prerequisites

Make sure you have the following installed or created:

- Node.js `v18+`
- Accounts and API keys from:
  - [Convex](https://www.convex.dev/)
  - [Clerk](https://clerk.com)
  - [Resend](https://resend.com)
  - [Gemini AI](https://ai.google.dev/)

---

### 🧰 Setup Instructions

#### 1. Clone the Repository

```bash
git clone https://github.com/Source-code495/SplitWise.git
cd ai-splitwise-clone
```

#### 2. Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

#### 3. Configure Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```env
# Convex configuration
CONVEX_DEPLOYMENT=your_convex_deployment_id
NEXT_PUBLIC_CONVEX_URL=https://your-deployment-id.convex.cloud

# Clerk authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_************
CLERK_SECRET_KEY=sk_test_************
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
CLERK_JWT_ISSUER_DOMAIN=https://your-domain.clerk.accounts.dev

# Email service (Resend)
RESEND_API_KEY=re_************

# AI service (Google's Gemini)
GEMINI_API_KEY=AIza************
```

> 💡 **Note**: You'll need to replace the placeholders with your actual API keys and credentials from each service.

#### 4. Initialize Convex

```bash
npx convex dev
```

#### 5. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Your app should now be running at [http://localhost:3000](http://localhost:3000)!

---



