# Pentest Findings Dashboard

A clean, modern **web application penetration testing findings tracker** built as a portfolio project.

Track vulnerabilities, assign severity & status, filter results, export data, and generate professional printable reports — all running 100% client-side with localStorage.

![Next.js](https://img.shields.io/badge/Next.js-16-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38bdf8)
![License](https://img.shields.io/badge/license-MIT-green)

## Features

- **Add / Edit / Delete** findings with rich details
- **Severity levels**: Critical, High, Medium, Low, Info (color-coded)
- **Categories**: XSS, SQL Injection, IDOR, CSRF, SSRF, Authentication, and more
- **Status tracking**: Open → In Progress → Fixed / Accepted Risk
- **Dashboard stats** (total, open, critical, high, fixed)
- **Search + multi-filter** (severity, status, category)
- **Professional Report** view → Print / Save as PDF
- **Export & Import** findings as JSON
- **Demo data** button for instant preview
- **Dark / Light** mode (system preference)
- Fully **client-side** — no backend, no database, no account needed

## Tech Stack

- **Next.js 16** (App Router)
- **TypeScript**
- **Tailwind CSS v4**
- **localStorage** for persistence

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy

Deploy instantly to Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

Or any static host that supports Next.js.

## Project Structure

```
src/
├── app/
│   ├── layout.tsx
│   ├── page.tsx          # Main dashboard
│   └── globals.css
├── components/
│   ├── StatsCards.tsx
│   ├── FindingCard.tsx
│   ├── FindingForm.tsx
│   └── ReportView.tsx
├── lib/
│   └── storage.ts        # localStorage helpers
└── types/
    └── finding.ts        # TypeScript types
```

## Resume / Portfolio Talk Track

> “I built a client-side penetration testing findings management tool that lets security professionals track vulnerabilities by severity and status, generate professional PDF-ready reports, and export data. Implemented with Next.js, TypeScript and Tailwind, fully offline-capable via localStorage.”

## License

MIT — feel free to use and modify for your own portfolio.

---

Built as a polished portfolio demo for web application security / penetration testing roles.
