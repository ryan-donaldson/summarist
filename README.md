Summarist is a full-stack book-summary platform built with Next.js, React, TypeScript, Firebase, and Zustand. It helps busy readers gain key insights from popular books through concise written summaries and audio briefcasts, while offering personalized recommendations, book discovery and search, user authentication, subscription plan selection, and an in-browser audio player.

Live Demo: https://advanced-internship-dusky.vercel.app/

<img width="1919" height="918" alt="Summarist" src="https://github.com/user-attachments/assets/2e8181a8-27cf-479d-9e2a-bb0e3489a064" />

Tech stack: Next.js 16 (App Router), React 19, TypeScript, JavaScript, Firebase Authentication, Zustand for client-side state management, Tailwind CSS/CSS for styling, React Icons, Axios, and the Summarist Cloud Functions API for book data.

Main features:

• Book summaries with key ideas, descriptions, and author information
• Audio briefcasts with play/pause, 10-second skipping, progress seeking, and duration tracking
• Personalized “For You” content, including selected, recommended, and suggested books
• Debounced search by book title or author
• Firebase-powered registration, login, logout, and authenticated settings
• Subscription selection with monthly and yearly Premium plans, trial messaging, checkout flow, and gated premium audio
• Responsive sidebar navigation and adjustable text sizing in the reading/player experience




This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.
