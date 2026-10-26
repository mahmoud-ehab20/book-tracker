# 📚 Book Tracker

A full-stack web app for managing your personal reading list. Users can sign up, log in, and securely manage their own book collection.

🔗 **[Live Demo](https://book-tracker-sqln.vercel.app/)**


## 🚀 Features

- ✅ **User Authentication** — Email/password sign up and login with Supabase Auth
- ✅ **Personalized Dashboard** — Each user sees only their own books
- ✅ **Book Management** — Add, view, and delete books
- ✅ **REST API Routes** — Next.js API routes with JWT verification for authenticated requests
- ✅ **Responsive UI** — Clean layout that works on desktop and mobile
- ✅ **Deployed on Vercel** — Serverless hosting

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js (App Router), React, TypeScript |
| Backend | Next.js API routes |
| Auth & Database | Supabase Auth, PostgreSQL |
| Deployment | Vercel |

## ⚙️ Getting Started

### Prerequisites

- Node.js 18 or later
- A free [Supabase](https://supabase.com) project

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/mahmoud-ehab20/book-tracker.git
   cd book-tracker
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Create a `.env.local` file in the project root

   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Run the development server

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000)

## 👨‍💻 Author

**Mahmoud Ehab** — Software Engineering Graduate

- [LinkedIn](https://www.linkedin.com/in/mahmoud-ehab-hamada/)
- [Portfolio](https://mahmoud-ehab-portfolio.vercel.app/)
