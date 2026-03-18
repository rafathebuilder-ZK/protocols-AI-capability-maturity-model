# Litepaper — Bibliography, Quotes, and Resource Gaps

**Version:** 0.1 (pre-draft)
**Date:** 2026-03-18
**Purpose:** Curated resource list for litepaper drafting. Includes section mapping, citable claims, Chicago-style bibliography, and gap analysis.

**Note on quotes:** Verbatim quotes confirmed from source catalog annotations are marked ✓. Claims paraphrased from annotations are marked [PARAPHRASE — extract verbatim from source PDF before citing]. McKinsey (entry 18) requires re-verification from the full report.

---

## Part 1 — Curated Resources by Litepaper Section

### Section 1: The problem with existing AI maturity models

| # | Source | What it contributes |
|---|--------|-------------------|
| 14 | Microsoft RAI Maturity Model | What the best existing model measures — and the gap it leaves (responsible AI, not uncertainty governance) |
| 15 | Accenture Art of AI Maturity | 63% of organizations are AI Experimenters; the Foundation/Differentiation axis; CEO sponsorship finding |
| 13 | BCG AI Maturity Matrix | National-level frame — useful contrast to show why organizational model is needed |
| 17 | Menlo Ventures State of GenAI | 16% of enterprises have deployed true agents — empirical anchor for where most orgs actually are |
| 18 | McKinsey State of AI 2025 | Adoption vs. value capture gap; 33% → 65% adoption but results still lagging |
| 34 | Shadow AI prevalence roundup | 3.1% of enterprise ChatGPT users submitting confidential data; 86% of healthcare orgs have shadow AI |

### Section 2: A protocol-framed model

| # | Source | What it contributes |
|---|--------|-------------------|
| 20 | Rao — Introduction to the Protocol Reader | Definition of protocol as coordination mechanism; the foundational vocabulary |
| 21 | Rao/Nast — Theorizing Protocolization I | Protocols as "new nature" — formal grounding for why AI tools require protocol-level response |
| 23 | Rao — What is Formal Protocol Theory? | Methodology of protocol framing; why it differs from policy or compliance |
| 24 | Rao — Constructing the Evil Twin of AI | "Smooth to striated" behavioral space framing — the theoretical basis for why maturity = constrained optionality |
| 35 | Table: Learning to See Business Protocols | Protocol trade pattern — every protocol trades one class of problem for another; direct precedent for level-by-level failure mode logic |
| 3  | Benny — Why Does AI Development Look Like 1980s Software Planning? | Ontological drift — the mechanism by which low-maturity AI governance fails |

### Section 3: The five levels

**Level 1 — Shadow**

| # | Source | What it contributes |
|---|--------|-------------------|
| 28 | Samsung ChatGPT leak | Three engineers, proprietary data, April 2023 — canonical L1 case |
| 29 | Legal hallucination sanctions | 550+ cases, $86K fine, ABA Formal Opinion 512 — governance failure at scale |
| 30 | Healthcare shadow AI | 86% of healthcare orgs have shadow AI incidents; 3.1% of users submitting confidential data |
| 34 | Shadow AI prevalence roundup | IBM: shadow AI incidents cost $4.63M on average vs. baseline; 97% lacked proper AI access controls |

**Level 2 — Sanctioned**

| # | Source | What it contributes |
|---|--------|-------------------|
| 31 | Klarna | 90% daily adoption → "generic, repetitive, insufficiently nuanced" → rehiring; the L2 failure arc |
| 32 | Shopify | Lütke's "non-optional" memo — mandate without workflow design |
| 33 | Duolingo | Contractor replacement → user backlash → DAU growth at "lower end of projections" |
| 4  | Armstrong — The Hottest Job in Tech | L2→3 transition requires embedded workflow design; FDE as the transition enabler |

**Level 3 — Designed**

| # | Source | What it contributes |
|---|--------|-------------------|
| 1/2 | Uber (Pragmatic Summit + Orosz) | Level 3 in practice: designed workflows, new bottleneck (code review), purpose-built tooling |
| 8  | Scholl — Vertical Integration (Slacker Index) | Slacker Index as diagnostic for governance bottleneck; L3→4 transition is collapsing the ratio |
| 5  | Scianna — Building an FDE Team | Gravel road + demo-as-spec: practical tools for first governed workflow; Auftragstaktik for distributed AI authority |
| 27 | Rao — Have Your Factory Call My Factory | F2F pipeline: what Level 3 looks like at individual level when enterprise is still at Level 1 |
| 36 | Ranganathan/Ye — HBR | Intensification = symptom of missing protocol layer; empirical evidence for the L3/L1 mismatch |

**Level 4 — Infrastructural**

| # | Source | What it contributes |
|---|--------|-------------------|
| 1/2 | Uber | Four-layer platform architecture; 6x cost increase; code review as first-class bottleneck |
| 15 | Accenture | Achievers (12%): CEO sponsorship, industrialized tooling, cross-cutting talent — what L4 looks like |
| 16 | OpenAI State of Enterprise AI | Frontier orgs: 6x more messages than median; 2x per seat — empirical evidence for the L4/L1 gap |
| 4  | Armstrong — FDE | Platform feedback loop (FDE discovery → platform abstraction) — what moves an org from project-specific to integrated |

**Level 5 — Planetary**

| # | Source | What it contributes |
|---|--------|-------------------|
| 7/11 | Scholl — XB-1 and Jevons's Law | Jevons's Law: when iteration is cheap, new decision spaces open — the non-linear payoff of Level 5 |
| 24 | Rao — Evil Twin of AI | "Smooth to striated" framing; AI as optionality-to-structure converter; L5 as full striation |
| 25 | Stinson-Schroff — Mechanical Currents | Systemic fragility as the failure mode of planet-scale protocols |

### Section 4: How to use this model

| # | Source | What it contributes |
|---|--------|-------------------|
| 26 | Rafa — Finding Fault Lines | Bottleneck heterogeneity in practice — weakest function sets the org-level maturity |
| 15 | Accenture | Foundation/Differentiation axes as diagnostic dimensions |
| 14 | Microsoft | Warning against averaging scores — dimensions are interdependent, not additive |

### Section 5: Where organizations are now

| # | Source | What it contributes |
|---|--------|-------------------|
| 17 | Menlo Ventures | 16% true agents; 63% still using prompt design / RAG / fixed workflows |
| 15 | Accenture | 63% AI Experimenters; 12% AI Achievers |
| 18 | McKinsey | 65% have adopted GenAI; value capture still lagging |
| 16 | OpenAI | Widening capability gap: frontier orgs vs. median |
| 34 | Shadow AI roundup | Shadow AI prevalence — 86% healthcare, 3.1% enterprise ChatGPT users submitting confidential data |
| 36 | HBR | AI adoption intensifies work without organizational absorption — empirical evidence for stuck pattern |

---

## Part 2 — Key Citable Claims Per Source

### Entry 1 — Uber: Leading engineering through an agentic shift
- "AI is enabling people to become superhumans in terms of their productivity." — Dara Khosrowshahi, CEO ✓ [PARAPHRASE — confirm exact wording from transcript]
- 84% of Uber developers are active agentic coding users (March 2026) ✓
- 65–72% of code is AI-generated inside IDE tools ✓
- Claude Code adoption: 32% of developers in December 2025 → 63% in February 2026 ✓
- Code review became the primary operational bottleneck as agentic PR volume grew ✓

### Entry 2 — How Uber uses AI for development: inside look
- 11% of PRs opened by agents (March 2026) ✓
- AI-related costs up 6x since 2024 ✓
- Internal tools built for the agentic era: Minion, Shepherd, Autocover, Code Inbox, U Review ✓
- [PARAPHRASE — extract description of four-layer platform architecture]

### Entry 3 — Why Does AI Development Look Like 1980s Software Planning?
- [PARAPHRASE — extract definition of "ontological drift"]
- [PARAPHRASE — extract Conway's Law claim about LLMs imposing waterfall-like communication structure]
- Key thesis: "LLMs flip the cost structure [of agile vs. waterfall] because ontological drift becomes extremely expensive" ✓ [PARAPHRASE — verify exact claim]

### Entry 4 — The Hottest Job in Tech
- OpenAI deploys FDEs to customers spending $10M+/year ✓
- FDE cost: $200–300K salary; services rule of thumb ≤25% of Year-1 contract value → effective $1M+ floor ✓
- Workday 2012 IPO: 35% of revenue from on-site professional services ✓
- [PARAPHRASE — extract the "bigger platform shift than cloud" framing]

### Entry 5 — How to Build Your Forward Deployed Engineering Team
- [PARAPHRASE — extract definition of "gravel road" concept]
- [PARAPHRASE — extract Auftragstaktik description: "HQ sets objectives, field decides tactics"]
- Platform feedback test: "if revenue-per-FDE is growing and custom work is abstracting into platform features, FDE is working" ✓ [PARAPHRASE — verify]

### Entry 7 — Move fast and don't break things [Part 1]
- XB-1 built by ~50 engineers at ~$190M — order of magnitude better than comparable aerospace programs ✓
- Boomless Cruise discovered through iteration — not original design objective ✓
- [PARAPHRASE — extract Jevons's Law framing in Scholl's own words]

### Entry 8 — Vertical Integration (Slacker Index)
- Slacker Index = total lead time ÷ actual working time ✓
- Turbine blade case: $1M per engine, 6-month lead time → $2M 3D printer → 24-hour production, daily iteration ✓
- [PARAPHRASE — extract the statement that "problems unsolvable at year-long iteration cycles become tractable at 24-hour cycles"]

### Entry 13 — BCG AI Maturity Matrix
- Only 5 of 73 economies qualify as AI Pioneers ✓
- AI use boosted some companies' revenues by 2.5x vs. competitors ✓
- Global AI spending projection: $632B by 2028 (Goldman Sachs, May 2024) ✓ [secondary citation]
- [PARAPHRASE — extract the exposure/readiness mismatch framing]

### Entry 14 — Microsoft RAI Maturity Model
- Built on 80+ hours of interviews and focus groups with 90+ participants ✓
- 24 empirically derived dimensions organized across three categories ✓
- "Maturity is uneven and interdependent; a Level 5 tooling score does not compensate for Level 1 leadership" ✓ [PARAPHRASE — verify exact warning language]
- [PARAPHRASE — extract the claim that RAI maturity requires UX researchers, designers, anthropologists, sociologists, linguists — not just engineers]

### Entry 15 — Accenture Art of AI Maturity
- 12% of firms are AI Achievers; 63% are AI Experimenters ✓
- Achievers are 3.5x more likely to see AI-influenced revenue exceed 30% of total revenues ✓
- Achievers are 25% more likely to scale AI pilots to production ✓
- 83% of Achievers have CEO and senior leadership sponsorship ✓
- BBVA: 4,000+ internal custom GPTs deployed ✓
- AI transformation happening 16 months faster than digital transformation (projected) ✓

### Entry 16 — OpenAI State of Enterprise AI 2025
- ChatGPT message volume grew 8x from November 2024 ✓
- API reasoning token consumption grew 320x ✓
- 40–60 minutes/day saved per active ChatGPT Enterprise user ✓
- 75% of workers report improved speed or quality ✓
- Frontier organizations send 6x more messages than median enterprises ✓
- 75% of users can now complete tasks previously impossible for them ✓

### Entry 17 — Menlo Ventures State of GenAI Enterprise 2025
- Enterprise GenAI market: $37B (2025) — "fastest-scaling software category in history" ✓ [PARAPHRASE — verify exact quote]
- Only 16% of enterprise deployments qualify as "true agents" (27% for startups) ✓
- Build vs. buy shift: 47% build / 53% buy (2024) → 24% build / 76% buy (2025) ✓
- 50% of developers use AI coding tools daily; teams report 15%+ velocity gains ✓

### Entry 18 — McKinsey State of AI 2025
- GenAI adoption: ~33% (2023) → ~65% (2024) ✓ [VERIFY — full PDF not directly accessed; confirm via mckinsey.com]
- High performers share three characteristics: changed workflows, retrained workers, systematic error governance ✓ [VERIFY]

### Entry 20 — Rao — Introduction to the Protocol Reader
- [PARAPHRASE — extract foundational definition of protocol as coordination mechanism]

### Entry 23 — Rao — What is Formal Protocol Theory?
- [PARAPHRASE — extract key claim distinguishing protocol from policy or compliance]

### Entry 24 — Rao — Constructing the Evil Twin of AI
- "Smooth to striated behavioral space" — maturity is the progressive conversion of optionality into governed structure ✓ [PARAPHRASE — verify exact framing]

### Entry 26 — Rafa — Finding Fault Lines
- [PARAPHRASE — extract bottleneck heterogeneity argument: effective level = highest-value, highest-stakes function where governance is weakest]

### Entry 27 — Rao — Have Your Factory Call My Factory
- "Neither of them writes code. Neither has touched a line of content text. What they bring is domain knowledge." ✓ [PARAPHRASE — verify]
- F2F pipeline: "the handoff... is a shared Dropbox folder plus a manuscript transmittal server" — minimal protocol governing autonomous factories ✓

### Entry 28 — Samsung ChatGPT leak
- Three engineers submitted proprietary source code, equipment specifications, and an internal meeting transcript within one month (April 2023) ✓
- Cyberhaven estimate: 3.1% of enterprise ChatGPT users had submitted confidential company data ✓

### Entry 29 — Legal hallucination sanctions
- 550+ publicly reported hallucination cases tracked (as of early 2026); 712 judicial decisions worldwide ✓
- ByoPlanet v. Johansson: $86,000 fine — largest single sanction for AI hallucination ✓
- ABA Formal Opinion 512 (July 2024): lawyers must have "reasonable understanding" of AI capabilities and must verify all output ✓

### Entry 30 — Healthcare shadow AI
- 86% of healthcare organizations had shadow AI incidents (symplr 2025 survey) ✓
- Average healthcare breach cost: $7.42 million, 279 days to resolve (IBM 2025) ✓
- Shadow AI incidents cost $4.63M on average across all sectors — $670K above baseline ✓

### Entry 31 — Klarna
- 90% of Klarna employees using AI tools daily (May 2024) — highest publicly reported enterprise rate ✓
- CEO described AI customer service replies as "generic, repetitive, insufficiently nuanced" ✓ [PARAPHRASE — confirm exact CEO quote attribution]
- Klarna claimed $40M profit improvement for 2024 attributed to AI ✓
- Headcount reduction: ~5,527 (2022) → ~3,100 (IPO, September 2025) ✓

### Entry 32 — Shopify
- "Frankly, I don't think it's feasible to opt out of learning the skill of applying AI." — Tobias Lütke ✓
- Revenue growth: 30% YoY (Full Year 2025); operating expenses fell from 45% to 35% of revenue ✓

### Entry 33 — Duolingo
- CEO claimed 4–5x content production with same headcount (September 2025) ✓ [PARAPHRASE — no independent verification published]
- User backlash pushed DAU growth to "lower end of projections" (Q2 2025 earnings) ✓

### Entry 34 — Shadow AI prevalence roundup
- Gartner: 41% of employees acquire, modify, or create technology outside IT visibility ✓ [VERIFY source]
- IBM 2025: 97% of organizations experiencing AI-related security incidents lacked proper AI access controls ✓
- 44% of organizations experiencing shadow AI incident suffered confirmed data compromise ✓

### Entry 35 — Table: Learning to See Business Protocols
- Protocol trade pattern: protocols do not eliminate problems — they trade one class for another ✓
- [PARAPHRASE — extract canonical examples of protocol-as-trade from the table]

### Entry 36 — HBR — AI Doesn't Reduce Work, It Intensifies It
- [PARAPHRASE — extract central finding on intensification: expanding tasks, multitasking, working beyond normal hours]
- [PARAPHRASE — extract the intrinsic motivation finding — workers do this to themselves]

---

## Part 3 — Chicago Bibliography (17th Edition, Notes-Bibliography Style)

Armstrong, Evan. "The Hottest Job in Tech." *The Leverage*, August 5, 2025.

Benny, Sachin. "Why Does AI Development Look Like 1980s Software Planning?" *Summer Lightning*, November 16, 2025.

Benny, Sachin. "Vibe Coding and the Maker Movement." *Technically / Summer of Protocols*, February 26, 2026.

Chada, Anshu, and Ty Smith. "Uber: Leading Engineering through an Agentic Shift." Talk presented at The Pragmatic Summit, published by *The Pragmatic Engineer*, March 10, 2026. https://www.youtube.com/watch?v=i1tZN41VKcE.

Boston Consulting Group. "BCG AI Maturity Matrix." November 2024. https://web-assets.bcg.com/95/38/a3ada1a74c6a813f7fe10ac432e9/bcg-ai-maturity-matrix-2024.pdf.

McKinsey & Company. "The State of AI 2025." 2025. https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai.

Menlo Ventures. "2025 State of Generative AI in the Enterprise." November 2025. https://menlovc.com/2025-the-state-of-generative-ai-in-the-enterprise/.

Microsoft AETHER Committee (Vorvoreanu, Mihaela, Amy Heger, Samir Passi, et al.). "Microsoft Responsible AI Maturity Model." Microsoft Research, May 2023. https://www.microsoft.com/en-us/research/uploads/prod/2023/05/RAI_Maturity_Model_Aether_Microsoft_WhitePaper.pdf.

OpenAI. "State of Enterprise AI 2025." 2025.

Orosz, Gergely. "How Uber Uses AI for Development: Inside Look." *The Pragmatic Engineer*, March 10–11, 2026.

Ranganathan, Aruna, and Xingqi Maggie Ye. "AI Doesn't Reduce Work — It Intensifies It." *Harvard Business Review*, February 2026.

Rao, Venkatesh. "Introduction to the Protocol Reader." Summer of Protocols, 2023.

Rao, Venkatesh. "What Is Formal Protocol Theory?" *Protocolized*, 2025.

Rao, Venkatesh. "Constructing the Evil Twin of AI." *Protocolized*, 2025.

Rao, Venkatesh. "Have Your Factory Call My Factory." *Protocolized*, March 2026.

Rao, Venkatesh, and Patrick Nast. "Theorizing Protocolization I: New Nature." *Protocolized*, 2026.

Rao, Venkatesh, Patrick Nast, et al. "Theorizing Protocolization II: Atomic Protocol Questions." *Protocolized*, 2026.

Rafa [surname]. "Finding Fault Lines within the Firm." *Protocolized*, 2026. [full author name to confirm before publication]

Scianna, Mark. "How to Build Your Forward Deployed Engineering Team." *Per Aspera*, September 17, 2025.

Scholl, Blake. "Move Fast and Don't Break (Safety Critical) Things." *Boom Supersonic*, August 10, 2025.

Scholl, Blake. "Move Fast and Don't Break (Safety Critical) Things Part 2: Vertical Integration." *Boom Supersonic*, September 14, 2025.

Scholl, Blake. "Building a Safety Culture: Move and Don't Break Safety Critical Things, Part III." *Boom Supersonic*, March 15, 2026.

Scholl, Blake. "Hiring: Skills vs. Aptitude." *Boom Supersonic*, August 18, 2025.

Scholl, Blake. "The Airplane That Unlocked the Supersonic Age." *Boom Supersonic*, January 28, 2026.

Scholl, Blake. "Your Aftermarket Profits Are My Disruptor's Opportunity." *Boom Supersonic*, September 24, 2025.

Stinson-Schroff, Timber. "Mechanical Currents." *Protocolized*, 2025.

Accenture. "The Art of AI Maturity." Accenture Research, 2024. https://www.accenture.com/us-en/insights/technology/art-of-artificial-intelligence-maturity.

Otter, Thomas. "WTF Is a Forward-Deployed Engineer?" *Work in Progress*, April 21, 2025.

Protocolized. "Table: Learning to See Business Protocols." *Protocolized*, 2026.

**Case study sources (cited by incident, not as standalone works):**

Gizmodo / Bloomberg / Cybersecurity Dive. Samsung ChatGPT data leak reporting. April–May 2023.

VinciWorks; ABA Law Practice Magazine; Court records (*Mata v. Avianca*, 2023; *ByoPlanet v. Johansson*, 2025). Legal AI hallucination sanctions.

symplr. "2025 Enterprise Healthcare IT Survey." 2025. IBM Security. "Cost of a Data Breach Report 2025." 2025.

Fast Company; Fortune; Entrepreneur; TechCrunch. Klarna AI deployment and reversal reporting, 2023–2025.

CNBC; Digital Commerce 360. Shopify AI mandate reporting, April 2025.

TechCrunch; Fortune. Duolingo AI-first reporting, 2024–2025.

Gartner; Cyberhaven; Reco.ai; IBM. Shadow AI prevalence data roundup, 2024–2025.

---

## Part 4 — Resource Gaps

### Critical gaps (must fill before drafting)

**Gap 1: No CMM historical context**
The litepaper opens by situating the AI CMM against prior maturity models. No source in the catalog covers the original SEI CMM (1986) or CMMI (2002) — the intellectual lineage that "capability maturity model" invokes. Without this, the framing floats.
- **What's needed:** A brief primary or secondary source on SEI CMM / CMMI history and what it measured.

**Gap 2: McKinsey full report not directly accessed**
Entry 18 is based on web summaries only. Several figures (33% → 65% adoption) are widely cited secondhand but the original methodology and caveats are not verified.
- **What's needed:** Download the full McKinsey State of AI 2025 report from mckinsey.com (requires registration, publicly free).

**Gap 3: No peer-reviewed empirical source on AI governance failure rates in production**
The litepaper needs at least one peer-reviewed or independently validated source on what percentage of AI-assisted workflows fail at the output review stage, or what error rates look like in deployed enterprise AI. The current catalog has case studies (Samsung, legal, healthcare) but no systematic measurement.
- **What's needed:** Academic or auditor-quality study on AI output error rates in enterprise contexts. Candidates: NIST AI Risk Management Framework (2023), EU AI Act impact assessments, sector-specific regulatory reports.

**Gap 4: No source on the EU AI Act or US AI governance regulation**
The litepaper's audience includes executives who are asking about compliance. No source addresses the regulatory landscape. Relevant for Level 3+ framing (designed workflows need to satisfy regulatory requirements, not just internal governance).
- **What's needed:** Summary source on EU AI Act (August 2024), US Executive Order on AI (October 2023), or relevant sector guidance (OCC AI guidance for banks, HHS AI policy for healthcare).

**Gap 5: No source on AI workflow ROI measurement**
Level 3–4 transitions require measurement — but the catalog has no source that addresses how organizations actually measure AI workflow performance, what metrics matter, and what benchmarks exist.
- **What's needed:** A practitioner-quality source on AI ROI measurement or productivity measurement methodology.

**Gap 6: No source engaging the Air Canada chatbot liability case**
The Air Canada case is in the case studies overview but absent from the source catalog. It's a clean, legally-settled example of L2 governance failure (AI acting as agent without governed escalation path) and could strengthen Section 3, Level 2.
- **What's needed:** Add BC Civil Resolution Tribunal decision (February 2024) to source catalog as entry 37.

### Secondary gaps (useful if available, not blocking)

**Gap 7: Gartner shadow AI figure needs primary source**
Entry 34 references a Gartner figure (41% of employees acquire technology outside IT visibility) that was not directly cited in the catalog annotation. Gartner reports require subscription; the figure may be from a 2023 or 2024 Gartner Hype Cycle report.
- **What's needed:** Confirm original Gartner source and date before citing in the litepaper.

**Gap 8: No source on the history of the "shadow IT" concept**
The litepaper introduces Level 1 as "Shadow AI" — a term that borrows directly from "shadow IT." No source grounds this etymology or explains why the parallel is exact rather than metaphorical.
- **What's needed:** Brief secondary source on shadow IT history (optional — can be handled in footnote).

**Gap 9: No academic source on organizational change and technology adoption curves**
The litepaper would benefit from a peer-reviewed grounding for why enterprises plateau at Level 2 — the organizational inertia argument. Rogers' *Diffusion of Innovations* or Christensen's disruption work would serve, but neither is in the catalog.
- **What's needed:** One strong secondary source on technology adoption organizational dynamics (optional, strengthens credibility with academic readers).

---

## Part 5 — Gap-Filling Plan

### Immediate (do before first draft)

| Action | Source | Method | Priority |
|--------|--------|--------|---------|
| Download McKinsey State of AI 2025 | mckinsey.com | Free registration | Critical |
| Add Air Canada case to source catalog as entry 37 | BC Civil Resolution Tribunal decision, February 2024 | Web — publicly available | Critical |
| Find SEI CMM / CMMI history source | Wikipedia CMM article → primary SEI publication | Web | Critical |
| Download NIST AI RMF (2023) | nist.gov | Free PDF | Critical |

### Before final draft

| Action | Source | Method | Priority |
|--------|--------|--------|---------|
| Locate EU AI Act summary suitable for citation | EUR-Lex / OECD AI Policy Observatory | Web | High |
| Confirm Gartner 41% figure — primary source and date | Gartner Hype Cycle for IT (2023 or 2024) | Requires Gartner subscription or secondhand citation | High |
| Locate AI ROI / productivity measurement source | Forrester, Gartner, or peer-reviewed work | Web / library | Medium |
| Extract verbatim quotes from all [PARAPHRASE] entries | Local resource PDFs | Read source files directly | High |

### Quote extraction (local PDFs — do in one pass before drafting)

The following source files are in `../Resources/` and need verbatim quote extraction before first draft:

- `uber-agentic-shift-transcript.txt` — Entries 1, 2
- `Why Does AI Development Look Like 1980s Software Planning_.pdf` — Entry 3
- `The Hottest Job in Tech.pdf` — Entry 4
- `How to Build Your Forward Deployed Engineering Team.pdf` — Entry 5
- `Move fast and don't break (safety critical) things.pdf` — Entry 7
- `Move Fast and Don't Break (safety critical) Things Part 2_.pdf` — Entry 8
- `BCG-AI-Maturity-Matrix-2024.pdf` — Entry 13
- `Microsoft-Responsible-AI-Maturity-Model-2023.pdf` — Entry 14
- `Accenture-Art-of-AI-Maturity-Report.pdf` — Entry 15
- `OpenAI-State-of-Enterprise-AI-2025.pdf` — Entry 16
- `Constructing the Evil Twin of AI.pdf` — Entry 24
- `Have Your Factory Call My Factory.pdf` — Entry 27

---

*Last updated: 2026-03-18*
