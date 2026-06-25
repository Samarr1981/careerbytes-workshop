# 🤖 Build Your Own AI Interview Agent
### CareerBytes Workshop — June 27, 2025

Welcome! This guide has everything you need to build your own AI-powered interview coach today.

---

## ✅ Before You Start
1. Create a free account at [bolt.new](https://bolt.new)
2. Create a free account at [claude.ai](https://claude.ai)

That's it. No coding experience needed.

---

## 🧠 Step 1 — Ask Claude to Write Your Bolt Prompt

Open [claude.ai](https://claude.ai) and paste this:

> "I want to build a text-based AI interview coach web app using Bolt.new. The user enters a job role, optionally uploads their resume PDF and pastes a job description, then answers 5 tailored interview questions one at a time. At the end, show a score out of 10, overall feedback, and 3 areas for improvement. Write me a detailed Bolt.new prompt to build this with a clean modern UI."

Take the prompt Claude gives you and paste it into Bolt.new.

---

## 🚀 Step 2 — Add Your API Key in Bolt

When Bolt asks for your Anthropic API key:
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign in and go to API Keys
3. Create a new key
4. Paste it into Bolt's .env file as `ANTHROPIC_API_KEY`

> ⚠️ You will be given a shared key during the workshop — swap it for your own after the event.

---

## 💡 Step 3 — Iterate and Customize

Once your base app is working, ask Bolt to add features:

- "Add a difficulty selector — Junior, Mid, or Senior level"
- "Add an interview type selector — Behavioral, Technical, or Mixed"
- "Make the UI dark mode"
- "Show a motivational message based on the score"
- "Add a cheat sheet at the end with 3 things to study before the real interview"

---

## 📱 Example Starter Prompt

Here's the prompt used to build the example shown at the workshop:
Build a clean, modern AI interview coach web app.
UI: Very light grey background, gradient header deep navy to indigo,

feature pills showing "5 Tailored Questions", "AI Feedback", "Instant Score".

Card below header with role input, optional job description toggle,

PDF resume upload, and Start Interview button.
Interview screen: progress bar, one question at a time, textarea for answer.
Results: score out of 10, overall feedback, 3 areas for improvement, Practice Again button.
Backend: Anthropic API, claude-haiku-4-5, read key from .env as ANTHROPIC_API_KEY,

never hardcode it, call API server-side to avoid CORS, collect all 5 answers

then evaluate in one API call, never show feedback mid-interview.

Mobile responsive, no markdown asterisks in UI.

---

## 🔗 Useful Links

- [Bolt.new](https://bolt.new) — Build your app
- [Claude.ai](https://claude.ai) — Generate your prompt
- [Anthropic Console](https://console.anthropic.com) — Get your API key
- [Sage](https://sage-three-pi.vercel.app) — The voice AI interview coach built by your workshop facilitator

---

Built with ❤️ at CareerBytes x June 27 Workshop
Facilitated by [Samar Partap Passey](https://www.linkedin.com/in/samarpartap-passey)
