# 🏥 CareFusion AI

Offline, privacy-first, multi-agent health companion (MVP). No API key, no backend, no data upload.

## Run
Open `index.html` in any modern browser. Deploy anywhere static (GitHub Pages, Vercel).

## Features
- Dashboard with risk score, recovery score (0–100), adherence
- Daily Health Coach summary (e.g. "BP increased 8%", "Adherence dropped 90% → 70%")
- Six agents with status cards: Vitals, Medication, Lifestyle, Risk, Emergency, Coach
- Explainable AI factor breakdown and Digital Health Twin
- Personalised goals: weight, BP, activity
- Symptom checker and report analysis
- Medication tracking
- Emergency detection: stroke, heart attack, diabetic warnings, auto crisis banner
- What-If simulator and weekly report (print to PDF)
- **🎬 3-Min Demo Script** button with live countdown timer

## Architecture
Rule-based agents read one shared state (localStorage). Risk Agent scores 0–100; Coach and Emergency agents consume that state. All logic is client-side JavaScript.

## Demo Script (3:00)
Press the **3-Min Demo Script** button: Intro (20s) → Coach & Recovery (30s) → Agents & Explainability (30s) → Goals, Meds & Reports (30s) → Emergency (35s) → What-If & Weekly (25s) → Closing (10s).

## Disclaimer
Not a medical device. For information only; seek professional care in emergencies (India: 108/112).
