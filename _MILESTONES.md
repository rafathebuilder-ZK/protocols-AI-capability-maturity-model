# AI Capability Maturity Model — Milestone Log
Append-only record of completed work, key decisions, and current status. Newest entries at the top.

---

## Current Status (as of 2026-03-16)

**Active work:** Model Development phase complete; YAML DSL v2 written and committed to GitHub
**Immediate next action:** Begin Blog Post draft (Phase 3) — open with Klarna/Samsung hook, central argument, Level 1–2 definitions
**Blocking items:** None

---

---

## Milestone Log

### 2026-03-16 | Model Development Phase Complete — YAML DSL v2, GitHub push

- **What:** Full Model Development phase completed in one session. All deliverables committed to GitHub.
- **Deliverables created:**
  - `Research/source-catalog.md` — 34 annotated entries across 7 categories (case studies, governance theory, adoption data, org design, iteration methodology, protocol theory foundational + applied)
  - `Research/case-studies-overview.md` — confirmed-facts-only overview of 9 case studies (Samsung, legal profession, healthcare, Klarna, Shopify, Duolingo, Uber, Boom Supersonic, Air Canada, Rao/Dixon)
  - `Model-Development/recomposition-plan.md` — task plan and resource map for YAML recomposition
  - `Model-Development/thesis-extraction.md` — 5 load-bearing claims, structural assumptions, weaknesses
  - `Model-Development/model-critique.md` — 12-point critique of v4; preserve/discard/develop table
  - `Model-Development/evaluation-criteria.md` — Section A (7 required), Section B (10 quality), Section C (5 fitness) criteria
  - `Model-Development/ai-cmm-v1.yaml` — first YAML DSL version (baseline)
  - `Model-Development/resource-critique-v2.md` — 10-category critique of v1 against all 34 resources; consolidated change list
  - `Model-Development/ai-cmm-v2.yaml` — revised YAML DSL with all critique changes applied
- **Key design decisions:**
  - Level names: Shadow / Sanctioned / Designed / Infrastructural / Planetary
  - Heterogeneity stance: `bottleneck` (effective level = highest-value/highest-stakes function where governance is weakest)
  - Unit-of-analysis: individual → org → business model → industry/market → civilization
  - Boom Supersonic: late Level 3 (not L4–5 as in v4)
  - Level 4/5 case anchors marked `status: projected`; no confirmed fully realized examples
  - 6 protocol dimensions replacing v4's 12-dimension table
  - `ai_exposure` and `stuck_pattern_guidance` fields added
  - Style: _REPORT-STYLE.md rules applied (vocabulary constraints excluded)
- **GitHub:** Initial commit pushed to https://github.com/rafathebuilder-ZK/protocols-AI-capability-maturity-model (30 files, 6,716 lines)

### 2026-03-15 | Project Initialized

- **What:** Project skeleton created — README, _PROJECT.md, _WORKPLAN.md, _MILESTONES.md, folder structure, output briefs, research templates
- **Prior work inventoried:** `AI_Capability_Maturity_Model_v4.docx` (January 2026) — 5-level model, deployment manager audience, shadow AI + code quality focus. This project is net new, not a v5.
- **Key framing decisions:**
  - Central argument: AI adoption failure is a protocol failure — organizations applying enterprise-software governance logic to a probabilistic stack
  - Unit of maturity: organization's ability to govern uncertainty productively (not process compliance)
  - Two outputs: blog post (~1,500 words) + litepaper (8–12 pages)
  - Both grounded in desk research only; no fieldwork
