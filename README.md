# IC-14 Regulations of Insurance Business — Compliance Lab

An interactive, single-page learning system for the IC-14 "Regulations of Insurance Business" syllabus, built on the same architecture as the companion General Insurance Accounting simulation lab.

## What's inside

- **`index.html`** — the entire app. Self-contained (Tailwind CSS via CDN, no build step, no backend). Covers all 11 units of the syllabus:
  1. Evolution of Insurance Law & the Insurance Act, 1938
  2. IRDA(I): Formation, Functions & Insurance Councils
  3. IRDAI's Licensing & Registration Functions
  4. Regulations Governing Conduct of Insurance Business
  5. Assignment, Nomination & Transfer of Policies
  6. Protection of Policyholders' Interests
  7. Dispute Resolution Mechanism
  8. Financial Regulation: Solvency Margin & Investments
  9. International Trends & Comparative Insurance Regulation
  10. Right to Information Act, 2005 (Annexure)
  11. Grievance Redressal System (Annexure)

  Plus a **Milestone 1** cross-syllabus mock exam (33 questions) and a session revision dashboard.

  Each unit has three parts: concept micro-bites, a "Compliance Desk" decision-tree sandbox (fictional insurer *Apex Shield*), and a 10-question diagnostic exam with misconception tracking.

- **`PROJECT_MASTER.md`** — the build log and architecture notes for this project.

## Running it locally

No build step needed — it's a static HTML file.

```bash
# Option 1: just open it
open index.html        # macOS
start index.html        # Windows

# Option 2: serve it (recommended, avoids any file:// quirks)
npx serve .
# or, with the VS Code "Live Server" extension: right-click index.html → "Open with Live Server"
```

## Deploying

This is a static site — it deploys anywhere that serves static files (Cloudflare Pages, GitHub Pages, Netlify, Vercel, S3, etc.) with zero configuration. No build command, no output directory setting needed beyond the repo root.

## Content note

All explanations, scenarios, and exam questions are original write-ups based on publicly available insurance law and IRDAI regulations — not reproduced from any copyrighted study material. Only the general syllabus topic sequence follows the standard structure of the subject.
