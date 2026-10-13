# IC-14 Regulations of Insurance Business — Interactive Learning System & Simulator — Project Master Document

## 0. Origin Note
This project is built on the same architecture as the companion **General Insurance Accounting (India) Simulation Lab**, extended to cover the *Regulations of Insurance Business* syllabus. All concept explanations, scenarios and exam questions below are **original write-ups** describing the underlying Acts, Regulations and public legal provisions — they are not reproduced from any copyrighted study text. Only the topic sequence (chapter order) follows the standard syllabus structure of the subject.

## 1. Project Overview & Architecture
* **Format:** Self-contained single-page web application (`index.html`) using Tailwind CSS CDN — same shell as the Accounting Lab, re-themed as a **Regulatory Compliance Simulator**.
* **Core Philosophy:** Simulator-First Interactive Experience. Learners master every regulatory topic through interactive micro-bites, a decision-tree compliance sandbox, and diagnostic mistake-trapping questions — no raw textbook filler, no copied statutory commentary.

---

## 2. The Standard 3-Part Unit Architecture (unchanged from the Accounting Lab)
Every unit is built with three distinct, interactive components:

1. **Part 1: Learn Concepts (Micro-Bites)**
   Granular, interactive cards covering the syllabus points, statutory sections, and definitions of each chapter, written in original language.
2. **Part 2: Interactive Sandbox (Apex Shield Insurance Co. — Compliance Desk Simulator)**
   A state-driven event decision tree, run at the same fictional company (Apex Shield) used in the Accounting Lab for continuity, but tracking **regulatory KPIs** instead of ledger balances: `complianceScore`, `licenseHealth`, `grievancesResolved`, `disclosuresFiled`, `riskFlags`, `stage score`.
3. **Part 3: Diagnostic Exam & Misconception Bank**
   10 exam-standard scenario MCQs per unit with instant rationale and diagnostic misconception codes (`MIS_*`), all originally authored.

---

## 3. Chapter Map & Build Schedule
Chapter numbering below is the conventional numbering used across Licentiate-level "Regulations of Insurance Business" courses; titles are paraphrased/original, not copied.

| Day | Unit | Topic | Status |
| :--- | :--- | :--- | :--- |
| **Day 1** | **Unit 1** | Evolution of Insurance Law in India & the Insurance Act, 1938 | **COMPLETED & BUILT** |
| **Day 2** | **Unit 2** | IRDA(I): Formation, Functions, Powers & the Insurance Councils | **COMPLETED & BUILT** |
| **Day 3** | **Unit 3** | IRDAI's Licensing & Registration Functions (Insurers, Intermediaries, Agents) | **COMPLETED & BUILT** |
| **Day 4** | **Unit 4** | Regulations Governing Conduct of Insurance Business (Solicitation, Advertising, Claims, TPAs) | **COMPLETED & BUILT** |
| **Day 5** | **Unit 5** | Policyholders' Rights: Assignment, Nomination & Transfer of Policies | **COMPLETED & BUILT** |
| **Day 6** | **Unit 6** | Protection of Policyholders' Interests (IRDAI Regs & Ombudsman groundwork) | **COMPLETED & BUILT** |
| **Day 7** | **Unit 7** | Dispute Resolution Mechanism (Insurance Ombudsman, Consumer Fora, Grievance Cells) | **COMPLETED & BUILT** |
| **Day 8** | **Unit 8** | Financial Regulation: Solvency Margin & Investment Regulations | **COMPLETED & BUILT** |
| **Day 9** | **Unit 9** | International Trends & Comparative Insurance Regulation | **COMPLETED & BUILT** |
| **Day 10** | **Unit 10** | Annexure Track: Right to Information Act, 2005 (as applicable to insurers) | **COMPLETED & BUILT** |
| **Day 11** | **Unit 11** | Annexure Track: Grievance Redressal System — End-to-End Framework | **COMPLETED & BUILT** |
| **Day 12** | **Milestone 1** | Full Revision Engine, Cross-Chapter Mock Exam, Compliance Simulator Polish | Ready to Build |

---

## 4. Sandbox Redesign Notes (Accounting Ledger → Compliance Desk)
The Accounting Lab's ledger HUD (`cash / liabilities / equity / revenue / expenses`) is replaced with a **Compliance HUD**:

| Old (Accounting) | New (Regulations) | Meaning |
| :--- | :--- | :--- |
| Cash / Bank | **Compliance Score** | Cumulative score for correct regulatory decisions |
| Liabilities | **Risk Flags** | Count of unresolved compliance/regulatory risks |
| Equity | **License Health** | Simulated standing of Apex Shield's certificate of registration |
| Revenue | **Disclosures Filed** | Statutory filings correctly completed |
| Expenses | **Grievance Backlog** | Unresolved policyholder grievances |
| Audit Score | **Diagnostic Score** | Stage progress through the current unit's sandbox |

---

## 5. Milestone 1 — Status: COMPLETED & BUILT
* **Topic:** Full Revision Engine, Cross-Chapter Mock Exam, Compliance Simulator Polish
* **What was built:**
  * A **33-question Full Syllabus Mock Exam** (3 randomly shuffled questions drawn from each of the 11 units' 10-question banks, reshufflable via a "New Mock" button), scored live with a completion summary.
  * A **Revision Dashboard** showing per-unit practice accuracy (attempted/correct/% correct) tallied across the whole session — from both individual unit exams and the mock exam — plus a session-wide, frequency-ranked list of every misconception flag triggered.
  * A new "Milestone 1: Full Syllabus Mock & Revision" entry in the sidebar (gold-accented, visually distinct from the 11 unit tracks) that switches the main view into this cross-chapter mode without disturbing any individual unit's own state.
* **Design note:** All Milestone 1 tracking is in-memory for the current browser session only (no `localStorage`/file writes) — it resets on page reload, consistent with how the per-unit sandbox state already behaves in this build.

## 6. Completed Units Log
* **Unit 1** — Evolution of Insurance Law in India & the Insurance Act, 1938. Built with 6 concept cards, a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 2** — IRDA(I): Formation, Functions & Insurance Councils. Built with 6 concept cards (Authority composition under Section 4, tenure under Section 5, Section 14 duties, the Councils' shifting role, and Section 114A regulation-making power), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 3** — IRDAI's Licensing & Registration Functions. Built with 6 concept cards (Certificate of Registration requirement, current minimum capital norms for insurers/reinsurers, the staged registration process, intermediary categories, agent-vs-broker distinction, and suspension/cancellation grounds), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 4** — Regulations Governing Conduct of Insurance Business. Built with 6 concept cards (licensed solicitation, advertising/disclosure norms, policy-issuance timelines and the free-look period, life claim settlement timelines, cashless health claim timelines, and the role/limits of TPAs — all reflecting the current 2024 Master Circular framework), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 5** — Assignment, Nomination & Transfer of Policies. Built with 6 concept cards (Section 38 assignment, conditional vs absolute assignment, Section 39 nomination, the beneficial nominee concept, changeability of nomination vs assignment, and assignment overriding nomination), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 6** — Protection of Policyholders' Interests. Built with 6 concept cards (pre-sale disclosure, the current 30-day free-look period and its refund mechanics, anytime cancellation of retail policies, mandatory nomination and policy loans, mis-selling safeguards, and the internal grievance redressal groundwork), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 7** — Dispute Resolution Mechanism. Built with 6 concept cards (Insurance Ombudsman Rules 2017 legal basis, ₹50 lakh pecuniary and personal-lines subject-matter jurisdiction, the insurer-first escalation requirement, mediation/Recommendation/Award process, ₹5,000/day Award-enforcement penalty, and the three-tier Consumer Protection Act, 2019 alternative route), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 8** — Financial Regulation: Solvency Margin & Investment Regulations. Built with 6 concept cards (the 150% solvency ratio requirement, Section 64VA intervention powers, the government securities investment mandate, the infrastructure/social sector investment obligation, exposure/prudential norms, and the developing Risk-Based Capital framework), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 9** — International Trends & Comparative Insurance Regulation. Built with 6 concept cards (rule-based/principles-based/risk-based regulatory models, the IAIS and its Insurance Core Principles, Solvency II as the EU benchmark, the twin-peaks vs single-regulator structural comparison, ComFrame for global insurance groups, and why international alignment matters for India), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 10** — Right to Information Act, 2005 (Annexure Track). Built with 6 concept cards (RTI applicability to public-sector vs private insurers, the PIO/APIO request process, response timelines including the 48-hour life-or-liberty exception, fees and the BPL exemption, Section 8 exemptions, and the appeal/penalty structure), a 3-stage compliance sandbox, and 10 original exam MCQs.
* **Unit 11** — Grievance Redressal System (Annexure Track). Built with 6 concept cards (the full grievance redressal ladder, the Bima Bharosa portal as the 2022 upgrade of IGMS, how a complaint flows and stays visible to the complainant, alternative channels to reach IRDAI, who may file a grievance, and the escalation path to the Ombudsman/Consumer Fora), a 3-stage compliance sandbox, and 10 original exam MCQs.

**Project status: All 11 syllabus units plus the Milestone 1 revision layer are complete. The IC-14 Regulations of Insurance Business Compliance Lab is fully built end-to-end.**
