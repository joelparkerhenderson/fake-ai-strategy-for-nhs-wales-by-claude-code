# NHS Wales AI Strategy — Task Backlog 2026–2028

**Companion document to** [`ai-strategy-for-nhs-wales-by-claude-code.md`](./ai-strategy-for-nhs-wales-by-claude-code.md) **and** [`plan.md`](./plan.md).

> ⚠️ **Disclaimer.** Fictitious illustrative example produced by Claude Code. Not an official NHS Wales / Welsh Government publication. Owners, dates and effort estimates are illustrative.

This document is the **task-level decomposition** of the strategy and plan. Tasks are grouped by workstream (W1–W8) as defined in `plan.md` §3, then by phase. Each task carries an ID, owner, dependency, expected effort and acceptance criteria.

**Effort scale:** S ≤ 5 person-days · M = 1–4 person-weeks · L = 1–3 person-months · XL > 3 person-months.

**Status legend:** ☐ pending · ◐ in progress · ☑ done · ⊘ blocked · ✗ cancelled.

---

## Phase 0 — Mobilise (Jan–Mar 2026)

### W1 — Governance and Ethics

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W1.0.1 | Draft Terms of Reference for NHS Wales AI Council | NHS Wales CEO office | — | M | ☐ | ToR signed by Cabinet Secretary |
| W1.0.2 | Recruit AI Council members (incl. 2 patient reps) | NHS Wales CEO office | W1.0.1 | M | ☐ | All seats filled |
| W1.0.3 | Open competition for independent chair of AI Safety & Ethics Sub-Committee | AI Council | W1.0.2 | M | ☐ | Chair appointed |
| W1.0.4 | Adopt UK AI Playbook + FUTURE-AI principles formally | AI Council | W1.0.2 | S | ☐ | Resolution recorded; published |
| W1.0.5 | Design AI Register schema (data fields, MoSCoW) | DHCW | — | M | ☐ | Schema reviewed by AI Council |
| W1.0.6 | Procure or build AI Register platform | DHCW | W1.0.5 | L | ☐ | Platform UAT-ready by end of Phase 0 |
| W1.0.7 | Draft assurance-pipeline operating manual (six gates) | DHCW + AI Safety Sub | — | L | ☐ | v1.0 published |
| W1.0.8 | Establish standard DPIA, EqIA, WLIA templates for AI | DHCW + WLC + DPOs | — | M | ☐ | Templates published; in use by Q2 |
| W1.0.9 | Liaison protocol with MHRA, ICO Wales, NICE, HRA | AI Council Sec. | — | S | ☐ | Named contacts and SLAs |

### W2 — Infrastructure and Data

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W2.0.1 | Audit current NHS Wales AI estate (existing tools, vendors, contracts) | DHCW | — | L | ☐ | Audit report; basis for Register seeding |
| W2.0.2 | Architecture options paper: sovereign vs hyperscaler vs hybrid | DHCW Chief Architect | — | M | ☐ | Options assessed against cost, sovereignty, sustainability |
| W2.0.3 | National Data Resource (NDR) gap analysis to "AI-ready" maturity | DHCW | — | L | ☐ | Gap analysis with phased remediation plan |
| W2.0.4 | National AI Sandbox technical and governance design | DHCW + Swansea + SAIL | W2.0.3 | XL | ☐ | Design approved by AI Council |
| W2.0.5 | MLOps platform requirements specification | DHCW | — | M | ☐ | Specification ready for procurement |
| W2.0.6 | Carbon baseline of NHS Wales digital estate | DHCW Sustainability | — | M | ☐ | Baseline published; benchmark for K14 |

### W3–W5 — Clinical / Operational / Corporate AI (PoC scoping)

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W3.0.1 | Each LHB nominates 1 priority clinical AI use case for PoC | LHB AI Leads | W1.0.2 | S | ☐ | 7 use cases logged |
| W3.0.2 | Each LHB nominates 1 priority operational AI use case for PoC | LHB AI Leads | W1.0.2 | S | ☐ | 7 use cases logged |
| W3.0.3 | NWSSP nominates corporate AI PoC scope | NWSSP | — | S | ☐ | Scope agreed |
| W3.0.4 | NHS Wales Copilot (or sovereign equivalent) market engagement | NWSSP + DHCW | — | M | ☐ | Market response analysed |

### W6 — Workforce and Skills

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W6.0.1 | Confirm AI Literacy 101 curriculum (English) | HEIW | — | M | ☐ | Curriculum signed off by AI Council |
| W6.0.2 | Confirm AI Literacy 101 curriculum (Welsh translation + adaptation) | HEIW + WLC | W6.0.1 | M | ☐ | Bilingual version signed off |
| W6.0.3 | Y Tŷ Dysgu module build + accessibility testing | HEIW | W6.0.2 | L | ☐ | Module passes WCAG 2.2 AA + bilingual audit |
| W6.0.4 | CAISO programme curriculum design | HEIW + clinical leads | — | L | ☐ | Curriculum approved |
| W6.0.5 | National recruitment campaign for specialist AI roles | DHCW + HEIW | W2.0.4 | M | ☐ | Campaign live by Q2 2026 |

### W7 — Welsh Language

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W7.0.1 | Draft bilingual procurement standard for AI tools | DHCW + WLC | — | M | ☐ | Standard published; effective 1 April 2027 |
| W7.0.2 | Welsh Language Impact Assessment template for AI | WLC + DHCW | — | M | ☐ | Template in use by Q2 |
| W7.0.3 | Stakeholder workshop with Welsh-language professionals on AI | DHCW Welsh-Lang Lead | — | S | ☐ | Workshop held; report published |
| W7.0.4 | Bangor University partnership scoping for Welsh-language model | DHCW + Bangor | — | M | ☐ | MoU heads of terms agreed |

### W8 — Research and Innovation

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W8.0.1 | Health and Care Research Wales AI programme established | HCRW | — | M | ☐ | Programme team in post |
| W8.0.2 | Sandbox legal framework (data sharing, IP, indemnities) | HCRW + DHCW + Swansea | W2.0.4 | L | ☐ | Framework approved by Information Governance |
| W8.0.3 | Four Nations AI MoU heads of terms drafted | NHS Wales CEO + DHSC + NHSE + Scotland + NI | — | M | ☐ | Heads of terms agreed |
| W8.0.4 | Bevan Commission engagement on AI prioritisation | HCRW + Bevan | — | S | ☐ | Engagement report |

### Cross-cutting Phase 0 tasks

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| X0.1 | Trade union AI Partnership Forum subgroup convened | HEIW + unions | — | S | ☐ | Subgroup ToR agreed |
| X0.2 | First Llais "AI in your NHS Wales" engagement event | Llais | — | M | ☐ | Event held; report published |
| X0.3 | Baseline data collection for all 32 KPIs | DHCW + LHBs | — | L | ☐ | Baseline report published |
| X0.4 | Comms plan + bilingual AI portal on NHS Wales website | NHS Wales Comms | — | M | ☐ | Portal live with strategy + plan + tasks |
| X0.5 | First AI Council meeting | NHS Wales CEO office | W1.0.2 | S | ☐ | Minutes published |

---

## Phase 1 — Foundations (Apr–Dec 2026)

### W1 — Governance and Ethics

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W1.1.1 | AI Register v1 launched; first 5 entries published | DHCW | W1.0.6 | M | ☐ | Register live and indexed |
| W1.1.2 | Quarterly AI Council reports begin | AI Council Sec. | — | S × 3 | ☐ | Q2, Q3, Q4 reports published |
| W1.1.3 | Run all PoCs through six-gate assurance pipeline | AI Safety Sub | W1.0.7 | XL | ☐ | All PoCs gated |
| W1.1.4 | First AI Citizen Survey commissioned and run | PHW + Llais | — | L | ☐ | Survey delivered; baseline %trust published |
| W1.1.5 | First AI vendor framework (NWSSP) award | NWSSP | W2.0.2 | XL | ☐ | Framework live; first call-offs by Q4 |
| W1.1.6 | First end-of-year report to Senedd Health Committee | NHS Wales CEO office | — | M | ☐ | Report submitted Dec 2026 |

### W2 — Infrastructure and Data

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W2.1.1 | NDR uplift Phase 1 (Welsh Health Data Hub MVP) | DHCW | W2.0.3 | XL | ☐ | MVP live; 3 use cases consuming |
| W2.1.2 | National MLOps platform commissioned | DHCW | W2.0.5 | XL | ☐ | Platform live; first model deployed |
| W2.1.3 | National AI Sandbox operational (target Q3) | DHCW + Swansea | W2.0.4, W8.0.2 | XL | ☐ | Sandbox open to first projects |
| W2.1.4 | Sovereign / approved compute capacity contracted | DHCW + NWSSP | W2.0.2 | L | ☐ | Capacity reserved; contracts signed |
| W2.1.5 | NHS Wales-wide algorithmic transparency recording (ATRS) integration | DHCW | — | M | ☐ | All registered AI tools have ATRS records |
| W2.1.6 | Carbon-per-inference dashboard v1 | DHCW Sustainability | W2.0.6 | L | ☐ | Dashboard live; first quarterly reading |

### W3 — Clinical AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W3.1.1 | Stroke imaging procurement (RAPID-class) commenced | DHCW + LHBs | W1.1.5 | XL | ☐ | Tender issued; preferred supplier identified |
| W3.1.2 | Ambient AI scribe PoC in 5+ sites | LHBs + DHCW | W2.1.2, W6.1.x | XL | ☐ | Pilots running; first evaluation |
| W3.1.3 | Predictive deterioration PoC in 3+ HBs | LHBs | W2.1.1 | L | ☐ | Pilots live; safety case approved |
| W3.1.4 | Cancer pathway AI scoping (Velindre + LHBs) | Velindre + LHBs | — | L | ☐ | Roadmap published |
| W3.1.5 | All Wales Medical Genomics Service AI scoping | AWMGS + DHCW | — | M | ☐ | Scoping report |

### W4 — Operational AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W4.1.1 | DNA prediction PoC in 3 HBs (with bilingual nudges) | LHBs + DHCW | W2.1.1 | L | ☐ | Pilots live; first evaluation |
| W4.1.2 | Bed and ICU forecasting PoC in 2 HBs | LHBs | W2.1.1 | L | ☐ | Pilots live; first evaluation |
| W4.1.3 | RTT pathway closure RPA live in 1 HB | DHCW + LHB | — | L | ☐ | RPA in production; volumes measured |
| W4.1.4 | Theatre scheduling optimisation PoC in 1 HB | LHB | — | L | ☐ | Pilot live |
| W4.1.5 | WAST AI call-handling scoping | WAST | — | M | ☐ | Scoping report |

### W5 — Corporate / Generative AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W5.1.1 | NHS Wales Copilot tenant procured and configured | NWSSP + DHCW | W2.1.4 | L | ☐ | Tenant live; data boundaries set |
| W5.1.2 | NHS Wales Copilot restricted pilot to 2,000 staff | NWSSP + DHCW | W5.1.1 | L | ☐ | 2,000 active users; safe-use guidance issued |
| W5.1.3 | Clinic letter assistance PoC in 1 HB | LHB + DHCW | W5.1.1 | M | ☐ | Pilot live; sign-off rates measured |
| W5.1.4 | Procurement anomaly detection PoC | NWSSP | W2.1.1 | M | ☐ | Pilot live |
| W5.1.5 | Cybersecurity behavioural-anomaly detection PoC | DHCW Cyber | — | L | ☐ | Pilot live; alert tuning |

### W6 — Workforce and Skills

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W6.1.1 | AI Literacy 101 module live on Y Tŷ Dysgu (bilingual) | HEIW | W6.0.3 | M | ☐ | Module live by Q3 |
| W6.1.2 | All-staff campaign to drive completion | HEIW + Comms | W6.1.1 | L | ☐ | >50% completion by Q4 |
| W6.1.3 | AI in clinical decision-support training (workshops) | HEIW + colleges | — | XL | ☐ | First 1,000 clinicians trained |
| W6.1.4 | CAISO cohort 1 enrolled | HEIW | W6.0.4 | L | ☐ | Cohort 1 in training |
| W6.1.5 | Recruit 50 specialist AI roles across DHCW + LHBs | DHCW + HEIW | W6.0.5 | XL | ☐ | 50 in post by year end |
| W6.1.6 | Apprenticeship pathway agreed with NWSSP | NWSSP + HEIW | — | M | ☐ | Pathway live |

### W7 — Welsh Language

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W7.1.1 | Welsh-language clinical NLP benchmark v0.1 published | DHCW + Bangor | W7.0.4 | L | ☐ | Benchmark public; reproducible |
| W7.1.2 | Bilingual evaluation in every PoC at Pilot gate | DHCW Welsh-Lang Lead | W7.0.2 | M | ☐ | Evidence in every gate review |
| W7.1.3 | Cymraeg AI co-design workshops with Welsh speakers | DHCW + Llais + Mentrau Iaith | — | M | ☐ | Workshops held; outcomes inform standards |
| W7.1.4 | Welsh-language model partnership MoU signed | DHCW + Bangor + WG Language Tech | W7.0.4 | M | ☐ | MoU signed |

### W8 — Research and Innovation

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W8.1.1 | Sandbox open to first 3 academic-vendor pairs | HCRW + DHCW | W2.1.3 | L | ☐ | 3 projects in flight |
| W8.1.2 | First joint funding bids (NIHR / UKRI / Horizon Europe) | HCRW + universities | — | XL | ☐ | ≥3 bids submitted |
| W8.1.3 | Bevan Commission AI exemplar projects scoped | Bevan + HCRW | — | M | ☐ | 3 exemplars defined |
| W8.1.4 | Four Nations AI MoU signed | NHS Wales CEO + DHSC + NHSE + Scotland + NI | W8.0.3 | L | ☐ | MoU executed |

---

## Phase 2 — Acceleration (2027)

### W1 — Governance and Ethics

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W1.2.1 | First annual algorithmic bias audit cycle | AI Safety Sub | — | XL | ☐ | All high-risk AI tools audited; results published |
| W1.2.2 | AI Register v2 (public-facing UX, search, RSS) | DHCW | W1.1.1 | L | ☐ | v2 launched |
| W1.2.3 | Refresh Citizen Survey (year 2) | PHW + Llais | W1.1.4 | M | ☐ | Year 2 results published |
| W1.2.4 | NHS Wales AI Conference (annual) | AI Council + HCRW | — | L | ☐ | Conference held; international keynotes |

### W2 — Infrastructure and Data

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W2.2.1 | NDR Phase 2 (cross-HB linked records) | DHCW | W2.1.1 | XL | ☐ | Live across all 7 HBs |
| W2.2.2 | Welsh-language model training environment live | DHCW + Bangor | W7.1.4 | XL | ☐ | Training runs commencing |
| W2.2.3 | MLOps maturity uplift (continuous monitoring + drift) | DHCW | W2.1.2 | L | ☐ | All BAU AI tools monitored |
| W2.2.4 | Net-zero AI carbon dashboard public version | DHCW Sustainability | W2.1.6 | M | ☐ | Public dashboard live |

### W3 — Clinical AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W3.2.1 | Stroke imaging deployed in 100% of stroke units | DHCW + LHBs + WAST | W3.1.1 | XL | ☐ | All stroke units live |
| W3.2.2 | Ambient AI scribe at scale in ≥3 HBs | LHBs + DHCW | W3.1.2 | XL | ☐ | Scaled in ≥3 HBs |
| W3.2.3 | Predictive deterioration in 100% of acute admission wards | LHBs | W3.1.3 | XL | ☐ | All acute admission wards live |
| W3.2.4 | Cancer pathway AI MDT prep live in 2 HBs | Velindre + LHBs | W3.1.4 | L | ☐ | 2 HBs live |
| W3.2.5 | Genomics variant interpretation AI PoC live | AWMGS + DHCW | W3.1.5 | L | ☐ | PoC live |

### W4 — Operational AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W4.2.1 | DNA prediction live nationally (all 7 HBs) | LHBs + DHCW | W4.1.1 | XL | ☐ | National rollout complete |
| W4.2.2 | Bed forecasting in 5+ HBs | LHBs | W4.1.2 | XL | ☐ | 5+ HBs live |
| W4.2.3 | RTT pathway closure live in 5+ HBs | DHCW + LHBs | W4.1.3 | XL | ☐ | 5+ HBs live |
| W4.2.4 | Theatre scheduling optimisation in 3+ HBs | LHBs | W4.1.4 | L | ☐ | 3+ HBs live |
| W4.2.5 | WAST AI call-handling pilot | WAST | W4.1.5 | XL | ☐ | Pilot live |

### W5 — Corporate / Generative AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W5.2.1 | NHS Wales Copilot at scale (≥30,000 staff) | NWSSP + DHCW | W5.1.2 | XL | ☐ | ≥30,000 active users |
| W5.2.2 | Discharge summary assistance in ≥3 HBs | LHBs + DHCW | W5.1.3 | L | ☐ | 3+ HBs live |
| W5.2.3 | Procurement anomaly detection at scale | NWSSP | W5.1.4 | L | ☐ | National rollout |
| W5.2.4 | Cybersecurity behavioural-anomaly detection at scale | DHCW Cyber | W5.1.5 | L | ☐ | All NHS Wales networks |

### W6 — Workforce and Skills

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W6.2.1 | 5,000-clinician AI-augmented practice cohort complete | HEIW + colleges | W6.1.3 | XL | ☐ | 5,000 trained |
| W6.2.2 | 100 specialist AI roles cumulative | DHCW + HEIW | W6.1.5 | XL | ☐ | 100 in post |
| W6.2.3 | CAISO certification ≥1 per HB/Trust | HEIW | W6.1.4 | L | ☐ | ≥10 certified |
| W6.2.4 | UG curriculum integration scoping with universities | HEIW + universities | — | L | ☐ | Curriculum updates agreed for 2028 intake |

### W7 — Welsh Language

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W7.2.1 | Bilingual procurement mandate effective 1 April 2027 | NWSSP + DHCW | W7.0.1 | M | ☐ | Mandate enforced; first procurements compliant |
| W7.2.2 | Welsh-language clinical NLP benchmark v1.0 | DHCW + Bangor | W7.1.1 | L | ☐ | v1.0 published |
| W7.2.3 | Welsh-language Q&A library for ambient AI scribe | DHCW + clinicians | W3.2.2 | L | ☐ | Library in use |
| W7.2.4 | Mid-year Welsh-language AI compliance audit | WLC liaison | — | M | ☐ | Audit report |

### W8 — Research and Innovation

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W8.2.1 | Sandbox at 6+ active projects | HCRW + DHCW | W8.1.1 | XL | ☐ | 6+ projects in flight |
| W8.2.2 | £15m external research funding secured | HCRW + universities | W8.1.2 | XL | ☐ | £15m awarded |
| W8.2.3 | First Bevan Exemplar projects evaluated | Bevan + HCRW | W8.1.3 | L | ☐ | Evaluations published |
| W8.2.4 | Four Nations operationalisation: first joint procurement | NHS Wales + DHSC | W8.1.4 | XL | ☐ | Joint procurement live |

---

## Phase 3 — Embed (2028)

### W1 — Governance and Ethics

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W1.3.1 | Second annual algorithmic bias audit cycle | AI Safety Sub | W1.2.1 | XL | ☐ | All high-risk AI audited; ≥95% pass |
| W1.3.2 | Year 3 Citizen Survey | PHW + Llais | W1.2.3 | M | ☐ | Year 3 results; ≥70% trust target |
| W1.3.3 | Mid-cycle strategy refresh published | AI Council | — | XL | ☐ | Refresh approved by Cabinet Secretary |
| W1.3.4 | Independent benefits audit (Audit Wales) | NHS Wales CEO + Audit Wales | — | XL | ☐ | Audit report published |

### W2 — Infrastructure and Data

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W2.3.1 | Welsh-language clinical foundation model v1.0 release | DHCW + Bangor + WG Language Tech | W2.2.2 | XL | ☐ | Model v1.0 publicly released |
| W2.3.2 | NDR Phase 3 (real-time linkage; population-health view) | DHCW | W2.2.1 | XL | ☐ | Phase 3 live |
| W2.3.3 | Carbon intensity year-on-year reduction confirmed | DHCW Sustainability | W2.2.4 | M | ☐ | YoY reduction reported |

### W3 — Clinical AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W3.3.1 | AI-assisted reporting in ≥80% of CT/MR exams | LHBs + DHCW | W3.2.1 | XL | ☐ | 80% threshold met |
| W3.3.2 | 5+ NICE-evaluated AI medical devices in routine use | DHCW | W3.2.x | XL | ☐ | 5+ devices in BAU |
| W3.3.3 | Cancer pathway turnaround −25% achieved | Velindre + LHBs | W3.2.4 | XL | ☐ | Reduction validated |
| W3.3.4 | Personalised medicine (genomics + AI) at scale | AWMGS + DHCW | W3.2.5 | XL | ☐ | Live in 5+ HBs |

### W4 — Operational AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W4.3.1 | DNA rate −2pp achieved | LHBs + DHCW | W4.2.1 | M | ☐ | Reduction validated |
| W4.3.2 | LOS −0.4 days achieved (acute medical) | LHBs | W4.2.2 | M | ☐ | Reduction validated |
| W4.3.3 | Theatre utilisation +10pp | LHBs | W4.2.4 | M | ☐ | Increase validated |
| W4.3.4 | WAST AI call-handling at scale | WAST | W4.2.5 | XL | ☐ | National rollout |

### W5 — Corporate / Generative AI

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W5.3.1 | Procurement, finance, HR analytics fully operational | NWSSP | W5.2.x | XL | ☐ | All workstreams live |
| W5.3.2 | PHM cohorts live (Public Health Wales) | PHW + DHCW | W2.3.2 | XL | ☐ | Cohorts in use |
| W5.3.3 | Discharge summary assistance national rollout | LHBs + DHCW | W5.2.2 | XL | ☐ | All 7 HBs live |

### W6 — Workforce and Skills

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W6.3.1 | 200 specialist AI roles cumulative | DHCW + HEIW | W6.2.2 | XL | ☐ | 200 in post |
| W6.3.2 | UG curricula updated at all 4 medical/dental/pharmacy schools | HEIW + universities | W6.2.4 | XL | ☐ | Curricula refreshed |
| W6.3.3 | CAISO certification ≥2 per HB/Trust | HEIW | W6.2.3 | L | ☐ | ≥20 certified |
| W6.3.4 | Workforce confidence in AI ≥75% (annual survey) | HEIW | — | M | ☐ | Survey result published |

### W7 — Welsh Language

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W7.3.1 | 100% bilingual coverage of patient-facing AI tools | DHCW + WLC | W7.2.x | M | ☐ | Audit shows 100% |
| W7.3.2 | Welsh-language clinical FM v1.0 in 3+ live use cases | DHCW + LHBs | W2.3.1 | L | ☐ | 3+ deployments |

### W8 — Research and Innovation

| ID | Task | Owner | Dep. | Effort | Status | Acceptance criteria |
|---|---|---|---|---|---|---|
| W8.3.1 | £25m cumulative external funding secured | HCRW + universities | W8.2.2 | XL | ☐ | £25m+ in flight or completed |
| W8.3.2 | 10+ formal partnerships under National AI Sandbox | HCRW + DHCW | W8.2.1 | L | ☐ | 10+ partnerships live |
| W8.3.3 | Wales positioned as ICS partner of choice for UK health-AI research (evidenced by hosted trials) | HCRW | — | XL | ☐ | ≥3 UK-leading trials hosted |

---

## Cross-cutting / continuous tasks

These tasks run for the full life of the strategy:

| ID | Task | Owner | Cadence |
|---|---|---|---|
| C.1 | Monthly programme reporting against KPIs | DHCW | Monthly |
| C.2 | Quarterly stage-gate reviews of every in-flight programme | AI Council + AI Delivery Board | Quarterly |
| C.3 | Quarterly net-benefit review (with public summary) | NHS Wales Finance + AI Council | Quarterly |
| C.4 | Quarterly Llais public engagement | Llais + AI Council | Quarterly |
| C.5 | Quarterly trade union Partnership Forum AI subgroup | HEIW + unions | Quarterly |
| C.6 | Annual report to Senedd Health Committee | NHS Wales CEO office | Annual |
| C.7 | Annual independent algorithmic bias audit | AI Safety & Ethics Sub | Annual |
| C.8 | Annual Citizen Survey | PHW + Llais | Annual |
| C.9 | Annual workforce confidence survey | HEIW | Annual |
| C.10 | Continuous monitoring of every BAU AI tool (drift, safety, bias, energy) | DHCW + LHB AI Leads | Continuous |
| C.11 | Continuous incident response and lessons-learned | DHCW Safety + AI Safety Sub | Continuous |
| C.12 | Continuous horizon-scanning (regulatory, technology, vendor market) | DHCW + HEIW + HCRW | Continuous |
| C.13 | Continuous Welsh-language compliance audits | WLC liaison + DHCW | Continuous |

---

## Falsification triggers — pause-and-replan

Per §14.4 of the strategy. If any of the following is observed, the AI Council will convene a pause-and-replan session within 14 days:

1. AI-related serious incidents > 3 per year that would not have occurred without AI.
2. Patient trust in AI < 50% on the annual Citizen Survey.
3. Clinician confidence in AI falling year-on-year.
4. Realised benefit < 50% of central case at Year 1 review.
5. Material bilingual safety differential between Welsh and English users.
6. Bias audit failure > 10% of audited tools.
7. Cyber incident attributable to AI infrastructure causing >24-hour service disruption.

---

## How this backlog will evolve

- Tasks are owned at workstream level and tracked in the AI Delivery Board's tooling (Jira/Azure DevOps/equivalent).
- This document is the human-readable mirror; it is refreshed at every quarterly AI Council meeting.
- New tasks are added under the relevant workstream and phase. Cancelled tasks are kept with a ✗ status and a rationale.
- Tasks completed in a quarter are summarised in the public quarterly report.

*End of task backlog.*
