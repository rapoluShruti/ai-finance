# Welth - AI-Powered Finance Platform

## 🚀 Overview

Welth is an AI-powered finance platform that helps users manage their finances efficiently. With advanced analytics, automatic transaction categorization, and AI-driven insights, users can track their expenses, set budgets, and receive personalized financial reports.
![Alt Text](./public/ss1.png)


## ✨ Features

- 🤖 AI-powered receipt scanning and transaction categorization
- 📊 Advanced analytics and spending insights
- 💰 Multi-account management
- 📅 Recurring transaction handling
- 📧 Monthly financial reports
- 🎯 Budget tracking and alerts
- 📱 Responsive design

## 🛠 Tech Stack

- **Framework:** Next.js 14 with App Router
- **Database:** Prisma with PostgreSQL
- **Authentication:** Clerk
- **Styling:** Tailwind CSS
- **AI Integration:** Google Gemini AI
- **Background Jobs:** Inngest
- **Email Service:** Resend

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ai-finance-platform.git
cd ai-finance-platform
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Set Up Environment Variables

Create a `.env` file and add the following variables:

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
RESEND_API_KEY=
ARCJET_KEY=
```

### 4️⃣ Set Up Database

```bash
npx prisma generate
npx prisma db push
```

### 5️⃣ Start the Development Server

```bash
npm run dev
```

## 📂 Project Structure

```
├── actions/         # Server actions
├── app/            # Next.js app router pages
├── components/     # React components
├── data/          # Static data & configs
├── emails/        # Email templates
├── hooks/         # Custom React hooks
├── lib/           # Utility functions
└── prisma/        # Database schema & migrations
```

## 💡 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License.
