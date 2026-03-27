# 💘 LoveSync AI — AI-Powered Dating Platform

An intelligent dating platform that uses AI to analyze 150+ compatibility factors and connect users with meaningful relationships. Built with Next.js 15, TypeScript, and OpenAI.

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?logo=openai&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-Styling-06B6D4?logo=tailwindcss&logoColor=white)

---

## ✨ Features

- **AI-Powered Matching** — Analyzes 150+ compatibility factors using OpenAI to find meaningful connections
- **AI Insights Dashboard** — Personalized dating pattern analysis, compatibility insights, and improvement recommendations
- **Discovery Dashboard** — Browse and discover potential matches with intelligent suggestions
- **Messages Center** — Direct messaging between matched users
- **Profile Studio** — Create and customize your dating profile
- **Registration Flow** — Smooth user onboarding experience
- **Data Visualization** — Relationship analytics with Recharts
- **Responsive Design** — Mobile-first with Tailwind CSS

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 15 | React framework with App Router |
| TypeScript 5 | Type-safe development |
| React 19 | UI library |
| OpenAI API | AI-powered matching and insights |
| Tailwind CSS | Utility-first styling |
| Recharts | Data visualization for analytics |
| Heroicons | Icon library |
| Netlify | Deployment |

---

## 📁 Project Structure

```
love-sign/
├── src/
│   ├── app/
│   │   ├── homepage/           # Landing page with AI intro
│   │   ├── ai-insights/        # AI dating analytics dashboard
│   │   ├── discovery-dashboard/ # Browse matches
│   │   ├── messages-center/    # Direct messaging
│   │   ├── profile-studio/     # Profile management
│   │   ├── registration/       # User onboarding
│   │   ├── api/                # OpenAI API endpoints
│   │   ├── layout.tsx          # Root layout
│   │   └── not-found.tsx       # 404 page
│   ├── components/
│   │   ├── common/             # Header, shared components
│   │   └── ui/                 # Reusable UI components
│   ├── lib/
│   │   ├── types/openai.ts     # OpenAI type definitions
│   │   ├── openai-client.ts    # OpenAI client setup
│   │   └── openai-error-handler.ts
│   └── styles/                 # Global CSS
├── public/                     # Static assets
├── next.config.mjs
├── tailwind.config.js
├── tsconfig.json
└── package.json
```

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- OpenAI API key

### Installation

```bash
git clone https://github.com/dipk2003/love-sign.git
cd love-sign
npm install
```

### Environment Setup

Create a `.env.local` file:

```env
OPENAI_API_KEY=your_openai_api_key
```

### Development

```bash
npm run dev
```

App runs at `http://localhost:4028`

### Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm run lint` | Run ESLint |
| `npm run format` | Format code with Prettier |
| `npm run type-check` | TypeScript type checking |

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

Made with ❤️ by [Dipanshu Pandey](https://github.com/dipk2003)