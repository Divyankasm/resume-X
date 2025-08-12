\# resumeX – AI-Powered Resume Builder

\*\*Build and optimize your resume with AI.\*\*

A modern, open-source tool for creating professional, ATS-friendly resumes in minutes.

\---

\## 🚀 Features

\- \*\*AI Resume Writing\*\* – Generate and refine resume sections using multiple AI providers.

\- \*\*ATS Optimization\*\* – Analyze your resume for keyword matching and applicant tracking compatibility.

\- \*\*Multiple Versions\*\* – Maintain a base resume and tailor versions for different job applications.

\- \*\*Cover Letter Generation\*\* – Create job-specific cover letters instantly.

\- \*\*Performance Insights\*\* – Get real-time scoring and improvement suggestions.

\- \*\*Export to PDF\*\* – Download clean, professional PDFs.

\- \*\*Secure Data\*\* – Built with authentication and row-level security.

\---

\## 🛠 Tech Stack

\*\*Frontend:\*\*

\- Next.js 15

\- React 19

\- TypeScript

\- Tailwind CSS + Shadcn UI

\- Framer Motion

\*\*Backend & Database:\*\*

\- PostgreSQL

\- Supabase

\- Row Level Security

\*\*AI Integrations:\*\*

\- OpenAI GPT

\- Claude AI

\- Google Gemini

\- DeepSeek

\- Groq

\---

\## 📦 Installation

\### Prerequisites

\- Node.js 18+

\- pnpm (or npm)

\- PostgreSQL database

\- Supabase account

\### Steps

\`\`\`bash

\# 1. Clone your repo

git clone https://github.com//resumeX.git

cd resumeX

\# 2. Install dependencies

pnpm install

\# 3. Setup environment variables

cp .env.example .env.local

Edit .env.local with your database, Supabase, and AI API keys.

🗄 Database Setup

bash

Copy

Edit

\# Option 1: Run schema.sql in Supabase SQL editor

\# Option 2: Use Supabase CLI

supabase db push --db-url=your\_supabase\_db\_url schema.sql

▶️ Start Development Server

bash

Copy

Edit

pnpm dev

Visit: http://localhost:3000

📄 License

Licensed under the AGPL v3.

You may modify and distribute it, but must keep it open source under the same license.

🤝 Contributing

Clone this repository

Create a new branch (git checkout -b feature-name)

Commit your changes (git commit -m "Add feature")

Push and open a pull request

✨ Made with ❤️ by \[Your Name\]