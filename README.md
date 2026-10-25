# Finance Tracker with AI Features

A Next.js-based Finance Tracker application enhanced with AI functionalities. This app allows users to manage their budgets and expenses while leveraging AI for advanced insights.

---

## Features

- _User Authentication_: Secure login and signup using Clerk.
- _AI-Powered Analytics_: Gain insights into your financial habits.
- _Database Integration_: Powered by Supabase for efficient data management.
- _Email Notifications_: Integrated with Resend API for sending emails.

---

## Prerequisites

Before setting up the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/)

- A Supabase account for database connection.
- Clerk account for user authentication.
- API keys for Resend and Gemini.

---

## Setup Instructions

### Step 1: Clone the Repository

Clone the repository and navigate to the project directory:

```bash
git clone
cd finance-tracker
```

### Step 2: Install all the modules

```bash
npm i
```

### Step 3: Run the server

```bash
npm run dev
```

### Step 4: Create .env file and Add these variable with you own keys

**_Clerk configuration_**

- **NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY**=xxxxxxxxxxxxxxxxxxx
- **CLERK_SECRET_KEY**=xxxxxxxxxxxxxxxxxxxxxxxx
- **NEXT_PUBLIC_CLERK_SIGN_IN_URL**=sign-in
- **NEXT_PUBLIC_CLERK_SIGN_UP_URL**=sign-up

**_Supabase connection pooling via Supavisor_**

- **DATABASE_URL**=postgresql://user:password@db.example.supabase.co:5432/database_name

**_Direct database connection (used for migrations)_**

- **DIRECT_URL**=postgresql://user:password@db.example.supabase.co:5432/database_name

- **RESEND_API_KEY**=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
- **GEMINI_API_KEY**=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
