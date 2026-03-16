# AI Capability Maturity Model — Milestone Log
Append-only record of completed work, key decisions, and current status. Newest entries at the top.

---

## Current Status (as of 2026-03-16)

**Active work:** YAML DSL v2.1 complete (table analysis pass); project docs updated; HTML artifact added as Phase 5 deliverable
**Immediate next action:** HTML artifact — product spec and UX planning session, then build
**Blocking items:** None

---

---

## Milestone Log

### 2026-03-16 | YAML DSL v2.1 — table analysis pass; project docs updated; HTML artifact added

- **What:** Final model refinement pass based on "Table Learning to See Business Protocols" (catalog entry 35). Project docs updated to reflect Phase 1–2 completion and add Phase 5 (HTML artifact).
- **Changes to ai-cmm-v2.yaml:**
  - Version bumped to 2.1
  - Model header: added `# Protocol trade pattern` note — protocols trade problems, not eliminate them; today's AI friction signals existing protocols pushed beyond design range
  - Level 1 description: added "pushed beyond design range" framing — shadow adoption is the signal, not the moral failure
  - L2→3 transition: added slop management / discovery protocol note — the unsolved protocol problem Level 3 organizations are building toward
  - Level 5 description: added containerization and printing press as historical precedents for planetary protocol embedding
  - Level 5 case_anchors: added ISO Containerization (1960s–present) as `historical_analogy` — physical interface protocol → planetary infrastructure → systemic fragility. Maersk attack as canonical early-L5 failure mode example
- **Source catalog:** Added entry 35 (Table: Learning to See Business Protocols) with full annotation
- **Project docs updated:**
  - _PROJECT.md: added HTML artifact as third deliverable; updated last updated date
  - README.md: updated status; added Model Development section with file map; added HTML artifact to outputs table
  - _WORKPLAN.md: Phase 1–2 marked complete; Phase 5 (HTML artifact) added; completion tracker updated
  - _MILESTONES.md: current status updated

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
