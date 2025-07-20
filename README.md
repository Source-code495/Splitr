<div align="center">
  <a href="https://github.com/piyush-eon/ai-splitwise-clone">
    <img src="./public/logos/logo.png" alt="SplitWise AI Logo" width="200">
  </a>

  # 💰 AI Splitwise Clone

  <p align="center">
    A modern expense sharing application with AI-powered insights
    <br />
    Built with Next.js 14, Convex, Tailwind CSS, Clerk Auth, and Inngest
    <br />
    <br />
    <a href="#demo">View Demo</a>
    ·
    <a href="#features">Features</a>
    ·
    <a href="#getting-started">Getting Started</a>
  </p>

  ![GitHub stars](https://img.shields.io/github/stars/piyush-eon/ai-splitwise-clone?style=social)
  ![Next.js](https://img.shields.io/badge/Next.js-14-black)
  ![Tailwind](https://img.shields.io/badge/Tailwind-4.1.3-blue)
  ![Convex](https://img.shields.io/badge/Convex-DB-orange)
  ![License](https://img.shields.io/badge/License-MIT-green)
</div>

## 🚀 About The Project

**AI Splitwise Clone** is a full-stack web application for tracking shared expenses among friends, roommates, and groups. It features smart settlement calculations, expense analytics, and AI-powered financial insights using Google's Gemini model.

![Dashboard Preview](./public/hero.png)

## ✨ Features

- 👥 **Group Expense Management** - Create groups for trips, events, or shared living
- 💸 **Smart Settlement Algorithm** - Minimizes the number of transactions needed
- 📊 **Expense Analytics** - Visualize spending patterns and category breakdowns
- 🔔 **Payment Reminders** - Automated notifications for pending debts
- 🧠 **AI-Powered Insights** - Monthly financial analysis using Google's Gemini AI
- 🔄 **Real-time Updates** - Instant sync across all users with Convex
- 🔒 **Secure Authentication** - User management with Clerk

## 🛠️ Built With

- [Next.js 14](https://nextjs.org/) - React framework
- [Convex](https://www.convex.dev/) - Backend database & real-time sync
- [Clerk](https://clerk.com/) - Authentication & user management
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [Shadcn UI](https://ui.shadcn.com/) - UI components
- [Inngest](https://www.inngest.com/) - Background jobs & scheduled tasks
- [Resend](https://resend.com/) - Email notifications
- [Google Gemini](https://ai.google.dev/) - AI-powered financial insights

## 🚦 Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn
- Convex account
- Clerk account
- Resend account
- Google AI (Gemini) API key

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/piyush-eon/ai-splitwise-clone.git
   cd ai-splitwise-clone
   ```

2. Install dependencies
   ```sh
   npm install
   ```

3. Create a `.env.local` file in the root directory with the following variables:
   ```
   # Deployment used by `npx convex dev`
   CONVEX_DEPLOYMENT=
   NEXT_PUBLIC_CONVEX_URL=

   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   CLERK_JWT_ISSUER_DOMAIN=

   RESEND_API_KEY=
   GEMINI_API_KEY=
   ```

4. Start the development server
   ```sh
   npm run dev
   ```
   In a separate terminal, run Convex dev server:
   ```sh
   npx convex dev
   ```

## 📝 Usage

1. **Sign up/Sign in** - Create an account or log in
2. **Create Groups** - Set up expense groups for your trips or shared housing
3. **Add Expenses** - Record expenses and specify how they should be split
4. **Settle Up** - View who owes whom and settle debts
5. **Explore Insights** - Check out spending patterns and AI-powered recommendations

## 🧠 Smart Features

### AI-Powered Monthly Insights

The application uses Google's Gemini AI to analyze spending patterns and provide personalized financial advice to users monthly, including:

- Spending trend analysis
- Category-wise breakdowns
- Personalized saving tips
- Unusual spending alerts

### Intelligent Settlement Algorithm

The system calculates the optimal way to settle debts within a group to minimize the number of transactions required.

## 🗺️ Roadmap

- [ ] Mobile application
- [ ] Currency conversion
- [ ] Custom expense categories
- [ ] Receipt scanning & OCR
- [ ] Advanced analytics dashboard

## � License

Distributed under the MIT License. See `LICENSE` for more information.

## 🔗 Environment Setup

```bash
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=

RESEND_API_KEY=

GEMINI_API_KEY=
```
