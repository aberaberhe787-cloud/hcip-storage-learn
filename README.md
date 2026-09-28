# HCIP Storage V5.5 — Exam Learning System

A focused learning application built around the official **HCIP-Storage V5.5** training material (~598 pages).

## Design principle

**The PDF is the source of truth.**

Every concept, explanation and quiz answer is anchored to the exact page of the official training document. When a learner answers incorrectly the system diagnoses the misconception and points back to the precise source page.

## Features (v0.1)

- **Learn** – Concept cards with definition, exam focus, comparison notes, PDF page reference
- **Practice** – MCQ / True-False / Fill / Scenario with “Why was my answer wrong?” diagnosis
- **Mock Exam** – Full 60-question, 90-minute exam weighted to official H13-624 V5.5 domains (Tech 50%, Deploy 15%, Perf 15%, O&M 20%)
- Dark mode toggle

## Stack

- Next.js 16 (App Router) + TypeScript + Tailwind CSS v4
- Ready for Firebase and Vercel deployment

## Getting started

```bash
npm install
npm run dev
```

Open http://localhost:3000

## Source material

Official Huawei HCIP-Storage V5.5 Training Material and H13-624 V5.5 exam outline.
