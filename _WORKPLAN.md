# AI Capability Maturity Model — Workplan
Living task list. Update status as work progresses.

**Status key:** `[ ]` not started · `[~]` in progress · `[x]` complete · `[!]` blocked

---

## Phase 1 — Research

### Status: COMPLETE (2026-03-16)

### Tasks
- [x] Survey existing AI maturity models (BCG, Microsoft RAI, Accenture, OpenAI, Menlo Ventures, McKinsey)
- [x] Identify what each model measures and where it falls short for generative AI specifically
- [x] Gather empirical data: adoption surveys, breach reports, productivity studies (2024–2026)
- [x] Identify case studies — 9 documented (Samsung, legal profession, healthcare, Klarna, Shopify, Duolingo, Uber, Boom Supersonic, Rao/Dixon pipeline)
- [x] Synthesize: what does protocol thinking add that existing models miss?
- [x] Source catalog complete — 35 annotated entries across 7 categories
- [x] Case studies overview document written — confirmed facts only

### Definition of Done
Source catalog complete with 35 annotated entries; case studies overview confirmed; research questions answered with evidence.

---

## Phase 2 — Model Development

### Status: COMPLETE (2026-03-16)

### Tasks
- [x] Thesis and logic flow extracted (thesis-extraction.md)
- [x] Full critique of v4 and working hypothesis (model-critique.md)
- [x] Test and evaluation criteria written (evaluation-criteria.md)
- [x] YAML DSL v1 written (ai-cmm-v1.yaml)
- [x] Resource critique — all 34 sources evaluated against v1 (resource-critique-v2.md)
- [x] YAML DSL v2 written with consolidated changes (ai-cmm-v2.yaml)
- [x] Table analysis pass — protocol trade pattern, containerization analogue, Level 1/2→3 framing (v2.1)

### Deliverables
- `ai-cmm-v2.yaml` (v2.1) — current authoritative model definition
- 5 levels: Shadow / Sanctioned / Designed / Infrastructural / Planetary
- 6 protocol dimensions; bottleneck heterogeneity stance
- Case anchors with catalog citations; Level 4–5 marked `projected` or `historical_analogy`

### Definition of Done
YAML DSL v2.1 passing evaluation-criteria.md requirements; all case anchors cited; protocol trade framing integrated; containerization historical analogue added to Level 5.

---

## Phase 3 — Blog Post

### Status: NOT STARTED

### Tasks
- [ ] Write blog post brief (Blog-Post/README.md)
- [ ] Draft v1 (~1,500 words)
- [ ] Self-review against style guide
- [ ] Practice Advisor review
- [ ] Final draft ready for publication

### Evaluation Criteria
- [ ] Accessible to non-specialist practitioners
- [ ] Distinctive Protocolized angle is clear (protocol framing, not just another AI CMM)
- [ ] Hook is strong — reader wants to keep reading after paragraph 1
- [ ] Ends with clear pointer to litepaper
- [ ] Style guide compliant (no AI writing tropes, no managerial filler)

### Definition of Done
Published on Protocolized.

---

## Phase 4 — Litepaper

### Status: NOT STARTED

### Tasks
- [ ] Write litepaper brief (Litepaper/README.md)
- [ ] Draft v1 (8–12 pages)
- [ ] Self-review against style guide
- [ ] Practice Advisor review
- [ ] Format for distribution (PDF-ready)
- [ ] Final draft ready for release

### Evaluation Criteria
- [ ] Each level is specific enough that a reader can place their organization on the model
- [ ] Tensions and failure modes are recognizable from practice (not just theoretical)
- [ ] References are sourced and credible
- [ ] Readable by a non-specialist executive in 20 minutes
- [ ] Style guide compliant

### Definition of Done
Litepaper released as downloadable PDF alongside or after blog post.

---

## Phase 5 — Interactive HTML Artifact

### Status: COMPLETE (v1.0 deployed 2026-03-17)

### Purpose
A publicly accessible Claude artifact providing a diagnostic tool: users explore the five levels, place their organization, and receive a level-specific summary of failure modes and progression requirements.

### Tasks
- [x] Product spec and UX planning session (_ARTIFACT-BRIEF.md written)
- [x] Define interaction model (funnel: step 1 recognition → step 2 scenario → level placement)
- [x] Build HTML artifact (Artifact/drafts/v1.html — single-file, pushed to GitHub)
- [x] Layout test suite (Artifact/drafts/layout-test.py — 21 criteria, 21/21 passing)
- [x] Content/style QC (_ARTIFACT-QC.md — 22 criteria, 22/22 passing)
- [x] Publish as public Claude artifact (v1.0 deployed 2026-03-17)
- [ ] Add public artifact URL to README, blog post, and litepaper once URL confirmed

### Versioning convention
- Deployed version: **v1.0** (Artifact/drafts/v1.html)
- Incremental changes (copy, layout, polish): v1.1, v1.2, etc. — saved as new files
- Major redesigns or model updates: v2.0
- The deployed artifact URL should be updated when a new version is promoted

### Definition of Done
✓ Public Claude artifact URL exists; artifact renders the five levels accurately from YAML content; artifact is linked from published blog post.

---

## Completion Tracker

| Phase | Planning | Execution | Review | Done |
|-------|----------|-----------|--------|------|
| 1 — Research | [x] | [x] | [x] | [x] |
| 2 — Model Development | [x] | [x] | [x] | [x] |
| 3 — Blog Post | [x] | [ ] | [ ] | [ ] |
| 4 — Litepaper | [x] | [ ] | [ ] | [ ] |
| 5 — HTML Artifact | [x] | [x] | [x] | [x] |

---

*Last updated: 2026-03-17*
