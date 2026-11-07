# CareFusion AI – Requirements

## Goal
An offline, privacy-first, multi-agent health companion that turns daily vitals into explainable risk, coaching and emergency guidance.

## Functional Requirements
| ID | Feature | Description |
|----|---------|-------------|
| FR1 | Health Dashboard | Risk score, recovery score, adherence, trend charts |
| FR2 | Multi-Agent Architecture | Vitals, Medication, Lifestyle, Risk, Emergency, Coach agents with live status cards |
| FR3 | Explainable AI | Per-factor point breakdown of the risk score |
| FR4 | Digital Health Twin | Snapshot of BMI, BP, glucose, weight, sleep, biological load |
| FR5 | Risk Scoring Engine | Rule-based 0–100 score (BP, glucose, BMI, activity, sleep, adherence, age) |
| FR6 | Daily Health Coach Summary | Week-over-week BP %, adherence change, activity and sleep tips |
| FR7 | Personalised Goals | Weight, BP and activity targets with progress bars |
| FR8 | Recovery Score | 0–100 improvement score from risk and adherence |
| FR9 | Symptom Checker | Rule-based possible causes with urgent flag |
| FR10 | Report Analysis | Hemoglobin, cholesterol, HbA1c, creatinine classification |
| FR11 | Medication Tracking | Add medicines, one-tap taken, adherence % |
| FR12 | Emergency Detection | Stroke, heart attack, diabetic warnings plus automatic crisis banner |
| FR13 | What-If Simulator | Projected risk for weight, steps, sleep, adherence changes |
| FR14 | Weekly Report | Averages and trends, printable to PDF |
| FR15 | 3-Minute Demo Script | Button opens timed script with countdown highlighting |

## Non-Functional Requirements
- 100% offline: no API key, no network calls, data in localStorage only
- Privacy-first: nothing leaves the device
- Responsive/mobile friendly, light and dark theme
- Single-file deployment (index.html)
- Accessible controls with clear labels

## Safety
Informational only; not a medical diagnosis. Emergency guidance directs users to 108/112.

## Out of Scope
Cloud sync, wearable integration, clinical validation, multi-user accounts.
