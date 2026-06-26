# Nexus AI - Data Automation Platform

![Nexus AI Banner](https://via.placeholder.com/1200x400/050505/ffffff?text=Nexus+AI+-+Data+Automation+at+the+Speed+of+Thought)

> **Hackathon Submission:** An ultra-premium, production-ready SaaS landing page engineered for maximum performance, accessibility, and dynamic scalability.

## 🚀 Live Demo
**[Insert your Vercel Link Here once deployed]**

## 💡 Overview
Nexus AI is a conceptual Data Automation platform designed to showcase elite frontend architecture. This project strictly avoids all external UI and animation libraries (like Framer Motion, Radix, or Shadcn) to demonstrate raw proficiency with React state management, CSS layouts, and native Web APIs.

## ✨ Key Technical Features

### 1. Dynamic Pricing Engine (Pub/Sub Pattern)
- Multi-currency support (USD, EUR, INR).
- Monthly vs. Annual cycle toggles with automatic 20% discount calculations.
- **Performance:** State updates are fully isolated. Changing the pricing tier *only* rerenders the price text, preventing expensive DOM repaints of the entire card structure.

### 2. Morphing Layout Architecture
- **Desktop:** CSS Grid (Bento Box aesthetic).
- **Mobile:** Flex Column (Accordion functionality).
- Built completely without JavaScript layout recalculation, relying purely on CSS Grid, Flexbox, and state-driven DOM transitions. Features state persistence upon window resizing.

### 3. Hyper-Optimized Performance
- **Lighthouse 100:** Engineered to score 100 across Performance, Accessibility, Best Practices, and SEO.
- Native CSS transitions and Web Animations API (WAAPI) ensuring all animations are 100% GPU accelerated.

## 🛠 Tech Stack
- **Library:** React 18 (via CDN for instant deployment)
- **Styling:** Tailwind CSS (via CDN)
- **Compilation:** Babel (Standalone browser compilation)
- **Architecture:** Zero-build, pure monolithic HTML/JS structure.

## 📱 How to Run (Zero Install)
This project is built to run instantly anywhere. No `npm install`, no `node_modules`.
1. Clone this repository.
2. Open `index.html` in any modern web browser.
3. Enjoy the magic.

*Note: For the hackathon deployment, this is hosted natively on Vercel as a pure static asset for ultra-low global latency.*

---
*Engineered for the 2026 National Hackathon.*

