<div align="center">

# 🏛️ CivicAI

### AI-Powered Grievance Redressal System

**Bridging citizens and government — intelligently.**

</div>

---

## 🚩 The Problem

Filing a civic complaint today means navigating confusing portals, waiting in queues, and never knowing if anyone's actually doing something. Complaints get lost, priorities are misassigned, and accountability is near zero.

**CivicAI fixes this.**

---

## ✨ What It Does

CivicAI is a full-stack civic grievance platform where citizens can file complaints and AI handles the heavy lifting — routing, prioritization, SLA tracking, and escalation — automatically.

| Feature | Description |
|---|---|
| 🤖 **AI Priority Detection** | Gemini AI analyzes complaint text and auto-assigns Urgent / High / Medium / Low priority |
| 🏢 **Smart Department Routing** | Complaints are routed to Water, Electricity, Sanitation, Roads, Health, Education & more |
| ⏱️ **SLA Monitoring** | Each department has configurable SLA deadlines; breaches trigger automatic escalation (L1 → L2 → L3) |
| 📊 **Admin Analytics Dashboard** | Real-time charts for resolution rates, department performance, and complaint trends |
| 🌐 **Multi-language Support** | Interface translates dynamically for accessibility |
| 🌙 **Dark / Light Mode** | Clean, modern UI with full theme support |
| 👤 **Role-Based Access** | Separate flows for Citizens, Officers, and Admins |
| 📱 **Responsive Design** | Works seamlessly on desktop and mobile |

---

## 🎬 Demo

> 🚀 **Live App:** https://htm-blush.vercel.app/

**Demo Credentials:**
- **Citizen** — file & track complaints
- **Officer** — manage assigned complaint queue
- **Admin** — full analytics and oversight

---

## 🏗️ Tech Stack

```
Frontend    React 19 + TypeScript + Vite
Styling     Tailwind CSS v4
AI          Google Gemini API (@google/genai)
Charts      Recharts
Animation   Motion (Framer Motion)
Icons       Lucide React
```

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/civicai.git
cd civicai

# Install dependencies
npm install

# Set your Gemini API key
cp .env.example .env.local
# Edit .env.local → GEMINI_API_KEY=your_key_here

# Run locally
npm run dev
# → http://localhost:3000
```

---

## 🔄 How It Works

```
Citizen files complaint
        ↓
Gemini AI detects priority (Urgent / High / Medium / Low)
        ↓
System routes to correct department
        ↓
SLA timer starts → Officer notified
        ↓
Breach? → Auto-escalate L1 → L2 → L3
        ↓
Resolved → Citizen rates the experience
```

---

## 🗂️ Project Structure

```
src/
├── App.tsx              # Main app + all views
├── types.ts             # TypeScript interfaces & enums
├── constants.ts         # Departments, districts, SLA config
├── translations.ts      # Multi-language strings
├── components/
│   └── AILoader.tsx     # AI processing animation
├── services/
│   └── mockService.ts   # Mock backend / data layer
└── lib/
    └── utils.ts         # Utility helpers
```

---

## 🌍 Impact

CivicAI targets a real governance gap:

- **Faster resolution** through AI triage instead of manual sorting
- **Zero complaints lost** via automatic escalation on SLA breach
- **Transparency** through real-time status tracking for citizens
- **Data-driven governance** with analytics for administrators

---

## 📄 License

[Apache 2.0](LICENSE) — built with ❤️ for civic good.
