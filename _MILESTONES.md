# AI Capability Maturity Model — Milestone Log
Append-only record of completed work, key decisions, and current status. Newest entries at the top.

---

## Current Status (as of 2026-03-18)

**Active work:** Artifact v1.12 live at https://protocolized.dev/ai-maturity-model/. Blog post v1.1 live at https://protocolized.dev/blog-the-missing-layer/. protocolized.dev domain fully configured.
**Immediate next action:** Begin litepaper (Phase 4).
**Blocking items:** None
**Versioning:** v1.0 is the deployed baseline. Future artifact changes tracked as v1.1, v1.2, etc. (incremental) or v2.0 (major model update). New versions saved as separate files before promoting to deployment.

---

---

## Milestone Log

### 2026-03-18 | Blog post v1.1 — published to protocolized.dev/blog-the-missing-layer

- **What:** Blog post "The Missing Protocol Layer" (v1.1) published as standalone HTML page at https://protocolized.dev/blog-the-missing-layer/.
- **Changes from v1.0:** Samsung (L1), Klarna (L2), Uber (L3) case study references added; ISO containerization parallel added to The Missing Layer section; eight voice/style changes reverted per author review.
- **Design:** Matches CMM artifact aesthetic — same fonts, colours, nav, hero with blurred background, footer. Level descriptions rendered as cards. Containerization paragraph as callout block. CTA links to maturity model and subscribe.
- **protocolized.dev/blog/** redirects to protocolized.summerofprotocols.com (same as root).
- **CMM artifact updated:** "Read more ↗" button (btn-secondary, centered) added to "Why this model exists" section, linking to blog post.
- **here.now slugs:** blog post = `witty-garnet-6k4f`; blog redirect = `whimsy-turret-j9jc`.

### 2026-03-17 | Artifact v1.12 — published to protocolized.dev

- **What:** Artifact published as permanent static site at https://protocolized.dev/ai-maturity-model/ via here.now hosting.
- **Domain setup:** protocolized.dev registered with here.now; ALIAS + TXT records added in Porkbun; SSL active. Root domain redirects to protocolized.summerofprotocols.com.
- **Subscribe link fix:** Top nav Subscribe updated from summerofprotocols.com homepage to /subscribe.
- **Deploy workflow:** `Artifact/publish/index.html` is the canonical deploy source (copy of current draft). Update draft → copy to publish/ → republish with `--slug thorny-basin-5xkf`.
- **here.now slug:** `thorny-basin-5xkf` (authenticated, permanent).

### 2026-03-17 | Artifact v1.0 — deployed as public Claude artifact

- **What:** v1.0 promoted from draft to public deployment. Phase 5 complete.
- **Final polish applied before deployment:** mono font consistency across `.context-intro` elements; exit card buttons equalized and centered; hero title block centered; competing column widths resolved (single 920px column); mobile hamburger nav; case study source links; footer icons (Substack + GitHub) and disclaimer; historical parallel callouts on all five level cards; expandable dimension panels; layout test suite (21/21 passing).
- **Versioning established:** v1.0 is the deployed baseline. Incremental changes → v1.1, v1.2. Major model updates → v2.0.
- **Remaining:** Add public artifact URL to README and planning docs once confirmed.

### 2026-03-16 | HTML Artifact v1 — built, polished, pushed to GitHub

- **What:** Interactive diagnostic artifact built from scratch and iteratively polished in one session. Pushed to GitHub (commit 4824dcb).
- **File:** `Artifact/drafts/v1.html` (~1,900 lines, single-file, no external CDN)
- **Structure:** Five sections — Entry, Context (five level cards), Case Studies (Samsung/Klarna/Boom), Self-Assessment (two-step funnel), Output card (level-specific diagnosis)
- **Assessment logic:** Step 1 recognition (options A/B/C → provisional level) → Step 2 scenario (3 options each → 9 paths) → 5 possible placements (L1, L2, L2-3, L3, L3-4)
- **Level cards:** Each has number + name, 1-sentence tagline, description paragraph, historical parallel callout, expandable dimension panel (6 dimensions with value badges and descriptions)
- **Output cards:** Level placement, tagline, 2-sentence description (second person), failure mode (3 sentences), single next action (done-when condition), five-level arc visual with current level highlighted
- **Style guide compliance:** Style review pass complete — negative parallelism reduced, em-dash pairs eliminated, assertion adverbs removed, managerial filler replaced. Source citations added to all statistics.
- **QC:** `_ARTIFACT-QC.md` created — 22 criteria across 5 categories (Audience Fit, Content Accuracy, Style Guide, Assessment UX, Technical); 22/22 passing
- **Key design decisions:** Document-title hero (not fear-based); context section leads with five level cards (not intro text); historical parallels as accent callouts; no score — diagnosis only; print stylesheet for output card
- **Historical parallels per level:** L1: Lotus 1-2-3 spreadsheets (mid-1980s) · L2: Corporate email/Exchange (early 1990s) · L3: Git + CI/CD (2008–2015) · L4: EDI in retail (late 1980s–90s) · L5: Internet protocols/BGP (2000s–present)

### 2026-03-16 | YAML DSL v2.2 — historical analogues per level; containerization throughline

- **What:** Added `historical_parallels` block to all five level definitions. Each level now has a `period_technology` (a historical technology that was at that maturity stage during its own adoption arc) and a `containerization_throughline` (what ISO containerization looked like at that stage, as a single coherent throughline across the model).
- **Period technologies:**
  - L1: Spreadsheets in accounting (Lotus 1-2-3, mid-1980s) — shadow use, individual gains, organizational risk invisible
  - L2: Corporate email (Microsoft Exchange / Lotus Notes, early 1990s) — mandate without workflow design, attention overload as new persistent problem
  - L3: Git + CI/CD in software (2008–2015) — designed workflow, competitive position depends on it, domain expertise is the constraint
  - L4: EDI in retail/manufacturing (late 1980s–90s) — license-to-operate requirement, individual advantage commoditized, sector floor raised
  - L5: Internet protocols (TCP/IP, BGP) — invisible global infrastructure, failure propagates before any actor can respond
- **Containerization throughline:**
  - L1: Pre-standard experimentation (1950s–60s) — McLean's first containers, proprietary box sizes, no inter-operability
  - L2: ISO standardization mandated, infrastructure not yet built (1965–75) — 20ft/40ft standards adopted, ports being rebuilt but rail/trucking lagging
  - L3: Intermodal system designed end-to-end (1975–90) — Maersk builds competitive moat on logistics precision, vertical integration collapses Slacker Index
  - L4: Universal adoption as license-to-operate (1990s–2000s) — supply chain becomes mainstream discipline, governance shifts to managing interdependencies
  - L5: Invisible planetary infrastructure (2000s–present) — Maersk ransomware, Ever Given, COVID port congestion as cross-sector cascading failures

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
