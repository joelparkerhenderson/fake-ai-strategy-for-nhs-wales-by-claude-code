# Value Assessment: National Digital Cellular Pathology with AI Review — NHS Wales

⚠️ Disclaimer. This document is a fictitious illustrative example generated entirely by Claude Code as an experiment in applied strategy synthesis. It is not an official publication of NHS Wales, the Welsh Government, Digital Health and Care Wales (DHCW), Health Education and Improvement Wales (HEIW) or any UK public body. Quoted statistics from public sources are cited; projections, OKRs, KPIs and ROI figures are illustrative analytical estimates, not commitments. The document is intentionally bilingual in tone (Welsh / English) to reflect statutory requirements but is not a substitute for translation by qualified Welsh-language professionals. Use at your own risk.

**Date:** 2026-06-18 **Prepared by:** Bronwyn (Health Economics, DHCW) with a product & delivery section by Dan (NHS Wales App / DSPP Programme) **Status:** Draft for review **Decision supported:** What is the value to NHS Wales of a national digital cellular pathology capability that supports AI-assisted review of pathology slides — how should that value be framed for an investment decision, and what patient-facing product opportunity does it unlock?

---

## Reader's note on method

This is decision-support economics, not a health technology assessment. Two things shape how it is written:

1. **This is a platform and capacity investment, not a discrete clinical product.** Its benefits accrue through faster, more accurate, more resilient diagnosis across almost every cancer and many non-cancer pathways — but those benefits are indirect, shared, and hard to attribute to the technology alone. A single incremental cost-effectiveness ratio (ICER) would imply a precision the evidence does not support. I therefore use a **cost-consequence and option-value framing**, with scenarios and ranges, and flag what is monetisable versus what is not.

2. **The question bundles two distinct layers.** "Digital cellular pathology that allows AI review" is really *digitisation* (scanning glass slides to whole-slide images, WSI) **plus** an *AI/computational layer* on top. These have very different value profiles and evidence bases, so I separate them. Most robust near-term value is in digitisation as an enabling national backbone; AI is a higher-option-value but more uncertain incremental layer.

Since drafting, I have grounded this against the published **National Digital Cellular Pathology BJC (version 18.0, Phase 3 "National Scale Up")**, so the cost line and several benefit figures below are now the programme's **own validated/quoted numbers** rather than indicative estimates, and are attributed as such. Two caveats remain: the detailed year-by-year financial appendix tables were not machine-readable, so I quote the BJC's headline asks rather than the full schedule; and this remains decision-support framing to be read alongside the BJC, not a substitute for it.

---

## 1. Decision context, options and counterfactual

### 1.1 The decision and audience

Whether — and how — NHS Wales should invest in a **national** digital cellular pathology service (and a phased AI layer), as opposed to leaving digitisation to individual health boards. Audience: DHCW and NHS Wales Executive leadership, the National Pathology Programme, and Welsh Government, who need a credible, proportionate value narrative to support a multi-year, multi-million-pound managed-service commitment.

This is already a live programme. NHS Wales has a National Digital Cellular Pathology project under the National Pathology Programme, which has moved through verification and proof-of-concept and is at the procurement stage for an all-Wales managed service explicitly scoped to include artificial intelligence, machine learning and deep learning. So the realistic question is not "if" but "at what scope, pace and operating model, and is the national route justified over the alternatives."

### 1.2 Realistic options

| Option | Description |
| --- | --- |
| **A. Do nothing / continue as-is** | Boards continue with predominantly glass-slide workflows; ad-hoc, board-by-board digitisation; existing courier and outsourcing arrangements persist. |
| **B. Board-led digitisation (fragmented)** | Each University Health Board (UHB) procures its own digital pathology, on its own timetable, with limited interoperability. |
| **C. National digitisation backbone ("once for Wales")** | A single all-Wales digital cellular pathology service: any consultant reports any case from any location, integrated with the Welsh Laboratory Information Management System (WLIMS) and Welsh Clinical Portal. *(This is the current programme intent.)* |
| **D. National backbone + phased AI layer** | Option C, then computational-pathology tools added incrementally on validated, high-volume pathways. |

The honest comparison is **C/D versus A/B**, not technology versus nothing.

### 1.3 Counterfactual discipline ("do nothing")

The realistic counterfactual is not a steady state. It is:

- **Rising demand against a shrinking workforce.** NHS Wales cellular pathology processed **more than one million slides in 2022/23, forecast to ~1.5 million by 2025/26** (NDCP BJC), with the most urgent specimens a rising share, more specimens per case, and growing molecular/personalised-medicine complexity. Turnaround targets — **7 days for urgent suspected cancer, 14 days for urgent, 28 days for routine** — are increasingly breached. A specific safety risk the BJC names: prioritising urgent work pushes back "routine" specimens, **8–11% of which turn out to be cancer**, so delay concentrates precisely where it is least visible.
- **A workforce gap that is structural, not cyclical, and acute in Wales.** Nationally the RCPath census found only **3% of UK histopathology departments adequately staffed** and **78% with consultant vacancies**. The Welsh detail in the BJC is starker: NHS Wales Executive modelling put the **capacity gap at 25% in west Wales** (Hywel Dda had **3 substantive consultants against a requirement of 9**) and the equivalent of **~8.5 consultants short in south-east Wales**; about **36% of the Welsh consultant workforce is over 55** (with ~10% "retired and returned"), and an estimated **17% of Welsh consultant pathologists were locums**. Hywel Dda has described its service as at serious risk of collapse.
- **Rising cost of covering the gap.** Outsourcing reached **almost £4m in 2023/24, up from £1.2m** in the prior BJC version — the clearest signal that the do-nothing trajectory is actively getting more expensive.
- **Continued fragmentation and stranded investment.** Wales has no single pathology service — six UHBs plus trusts, with Powys served by neighbours, and two live regionalisation efforts (ARCH in the south-west; a south-east network) that *depend on* digital pathology to function. Betsi Cadwaladr has already invested and is the pilot site; further uncoordinated, board-by-board procurement risks duplication, non-interoperable islands and stranded spend. This is the core "once for Wales" rationale — an economic argument, not just an architectural one.

The opportunity cost of delay or partial adoption is therefore real: demand grows, the gap between capacity and need widens, locum/outsourcing spend rises, and the cost of later retrofitting interoperability onto fragmented systems compounds.

---

## 2. Scope

**In scope:** the national value case for (i) digitisation of cellular pathology and (ii) an AI-assisted review layer, at NHS-Wales-system level.

**Out of scope:** a NICE-submission-ready economic model; tool-by-tool HTA of specific AI products; clinical validation (a separate, essential governance process); the detailed procurement/financial model (the NDCP business justification case). This is strategic option-framing to support a decision, not a substitute for finance, procurement, regulatory or audit processes.

---

## 3. The value architecture

The single most important analytical point: **the two layers carry different value with different certainty.**

### 3.1 Layer 1 — Digitisation (the enabling backbone)

This is where the most robust, near-term, system-wide value sits, and it is a prerequisite for AI. Benefits are largely about logistics, flexibility, resilience and quality rather than direct cash release.

| Benefit | Mechanism | Evidence strength |
| --- | --- | --- |
| **Workforce flexibility / load-balancing** | Any consultant reports any case from any location; work can flow to where capacity exists across Wales, breaking the link between local staffing and local demand | High (operational logic; core programme design) |
| **Logistics elimination** | Removes physical transport of glass slides between sites and for MDT; international/regional consultation made trivial | High — academic-centre studies report 93–97% reductions in glass-slide retrieval and material courier/travel savings |
| **Turnaround time** | Faster routing to reporting and MDT; prior images instantly available | Moderate — e.g. ~1-day reduction in turnaround on resection cases where prior WSIs were available |
| **Subspecialisation & networked second opinions** | Real-time electronic expert review without posting slides; supports a national network of subspecialist reporting | High (programme rationale; reduces courier delay and cost for external opinion) |
| **Resilience & business continuity** | Fragile single-handed/rural services backed by the national network rather than dependent on one retiring consultant | High (directly addresses the "collapse risk") |
| **Ancillary test reduction** | On-demand access to prior material reduces repeat immunohistochemistry/ancillary ordering | Moderate — one centre reported IHC ordering falling from ~52% to ~21% of cases |
| **Training & archive** | Digital teaching sets; instant archive retrieval; reduced reliance on physical slide storage under Human Tissue Act retention rules | Moderate–High |

The Welsh proof-of-concept phases have already evidenced several of these in practice: digitally sharing lymphoma cases between Betsi Cadwaladr and Swansea Bay cut reporting from **two weeks to 24 hours**; voice-recognition reporting improved turnaround by **up to 5 days**; and digital images can take a case from glass-to-report in **hours rather than the usual two days**. One concrete example: a Swansea Bay urology MDT missing its slides had Hywel Dda scan and report them electronically mid-meeting, saving a week on the pathway.

A consistent caution from the literature: **digitisation is not reliably cash-releasing in the near term.** One widely cited view is that digital pathology revenue is "not likely to cover the costs, at least in the near term but possibly not ever." Reported savings range widely — from a single-centre 5-year saving around $1.3m to a projected $12.4m at a large integrated organisation — and depend heavily on scale, scope and whether productivity gains are actually banked. The defensible position is that **digitisation's value is dominated by capacity, quality, resilience and option value, with cost-avoidance as a secondary and uncertain benefit.**

### 3.2 Layer 2 — AI / computational pathology (the incremental layer)

AI sits on top of digitisation and is where the original question's interest lies. The evidence on *accuracy* is genuinely strong; the evidence on *whole-service deployment economics* in an NHS setting is much thinner, and there are real trade-offs.

| Benefit | Mechanism | Evidence strength / caveat |
| --- | --- | --- |
| **Workload reduction via triage** | High-sensitivity detection lets large volumes of benign slides be safely prioritised or pre-screened, focusing scarce consultant time on abnormal cases | Promising but pathway-specific — e.g. a prostate active-surveillance study reported AI sensitivity ~0.96 with specificity ~0.73, implying a large share of benign slides could be safely auto-screened. Real-world workload gains depend on prevalence and operating model. |
| **Safety net (missed-cancer reduction)** | AI flags small foci a fatigued or non-specialist reader might miss; improves sensitivity | Strong in prostate (Paige Prostate was the first FDA-authorised AI in pathology; standalone AUCs reported above 0.98 and improved pathologist sensitivity) |
| **Standardisation / reduced variability** | Automated or assisted grading reduces inter-observer variability (e.g. Gleason/ISUP grading; Ki-67 quantification in breast) | Strong for specific tasks; supports more consistent decisions and equity of diagnosis |
| **Quantification** | Objective measurement (tumour extent, biomarker scoring) supports precision medicine | Moderate–strong, task-specific |
| **Worklist prioritisation** | Triaging urgent-suspected-cancer (USC) cases to the front of the queue to protect the 7-day USC / 14-day urgent targets | Plausible operational benefit; limited formal economic evidence |
| **Option value** | Once the digital substrate and governance exist, new regulated algorithms can be added at marginal cost as they mature | High strategically; this is arguably AI's biggest economic argument |

**Trade-offs and risks specific to AI:** assistance can raise sensitivity but sometimes lowers specificity (more benign cases flagged for review); generalisability across different scanners and Welsh case-mix must be validated, not assumed; regulatory status (UKCA/MHRA), clinical governance, liability and information-governance for image data all add cost and time; and most robust evidence is concentrated in a few tumour types (prostate strongest), not across the whole service. AI is therefore best understood as a **targeted, phased, high-volume-pathway intervention**, not a uniform workforce substitute.

**Welsh evidence to date is encouraging and real.** Under an SBRI-funded project, the **IBEX** platform was used to pre-analyse and triage prostate biopsies; by mid-May 2024 **all six health boards** were using it to assist prostate reporting, with **over 1,900 prostatic cases** scanned across the first three boards. Reported benefits were an **~13% improvement in accuracy** and a **possible ~50% reduction in IHC** demand to support a cancer suspicion. A breast-AI project (Moondance) at Betsi Cadwaladr has completed validation and is processing breast biopsies, and a gastric-biopsy pilot is planned at Cardiff & Vale. This is exactly the pattern the economics favours — validated, high-volume, single-pathway deployments — and it strengthens the Option D case *for those pathways* without yet generalising to the whole service.

---

## 4. Costs — the actual BJC ask

The published NDCP BJC (version 18.0) resolves the cost side. The programme is **not** a capital purchase: the appraisal selected a **fully revenue-funded managed-service model** — the supplier owns and manages the digital solution (scanners, workstations, hardware, software, integration, training, image storage and ongoing service), procured by full tender, with a phased ("one health board at a time") rollout. The headline funding ask is:

| Cost line | Amount | Period | Notes |
| --- | --- | --- | --- |
| **Non-recurring revenue** (implementation) | **£423,000** total (**£71,000 per health board** × 6) | 2025/26 – 2027/28 | Project team and DHCW support |
| **Ongoing revenue** (managed service + HB staff) | **£34.4m** total | 2025/26 – 2034/35 (≈10 years) | Annual recurring managed-service contract cost, plus a Band 6 biomedical scientist, a Band 3 support worker and ~1 day/week of Band 7 IT in each health board |

So the validated commitment is roughly **£34.8m of revenue over a ten-year horizon, almost entirely recurring**. For reference, this sits squarely within the "low-to-mid tens of millions over 5–10 years" order of magnitude estimated in the earlier draft — the BJC firms it up and, importantly, confirms a **revenue/managed-service** rather than capital shape.

**Two financing points are material, and both appear in the BJC's own risk register:**

- **Welsh Government has confirmed no funding for the procurement phase**, and the recurring cost falls to **health boards**, which must build it into their integrated medium-term plans (IMTPs). At the time of writing, 2025/26 (and ongoing) HB revenue funding **was not yet secured** — recorded as a live financial risk to delivery. This is an affordability-and-commitment risk, not a value risk.
- **Capital funding was judged unlikely**, which is *why* the fully-revenue managed-service route was preferred — a reasonable response to capital constraint, but it makes the cost a permanent claim on revenue rather than a one-off.

**Storage is the structural recurring pressure.** Each board's initial ~**49TB** of local storage is already nearly full; **£150,000 per board** was allocated in 2023 as an interim fix pending a national solution. A standard slide is ~**1–1.5GB** (megaslides ~3GB), so at ~1.5m slides/year the national image store is a multi-petabyte, growing, retention-bound commitment. The BJC adopts a DHCW "cloud-first" approach and a tiered model (instant access to ~12 months of images; older images retrievable within 24–48 hours to contain cost). This is the line most likely to escalate and most worth scrutinising.

### 4.1 Per-board apportionment — cross-check against the Hywel Dda BJC

The Hywel Dda supporting paper (tabled at the board in 2024) lets us sense-check how the national £34.4m falls on individual boards, and it broadly reconciles — with three things worth flagging.

- **Recurring cost reconciles.** Hywel Dda commits to **~£500,000 per year**. The national £34.4m over ten years averages ~£3.44m/year, i.e. ~£573k per board on a flat split — so a smaller-volume board sitting slightly below the flat average is consistent. The apportionment is clearly **not a flat sixth**: ~£500k × 6 ≈ £30m, leaving headroom within the £34.4m for the national hub, storage and programme costs and for larger boards (Cardiff & Vale, Betsi Cadwaladr) carrying more. Orders of magnitude check out.
- **The "cost-neutral" framing deserves scrutiny.** Hywel Dda presents its ~£500k/year as **offset by ~£502k of productivity/efficiency savings, making it "cost neutral (£0)"**. But those savings are built from: replacing a **£335k high-cost agency locum with a ~£150k substantive (£185k saving)**; reducing **~£327k of in-lieu-of-locum (ILOL) insourcing (£177k saving)**; and **~£140k from AI-driven reductions in IHC and second opinions** (breast, gastric, general). The first two depend on **successfully recruiting** — the very thing the board has been unable to do since 2016, and which digital is *meant to enable*. So the £0-net claim is sound in logic but **circular and recruitment-contingent**: if recruitment still fails, the cost is not offset. A prudent reading treats the AI-driven ~£140k as the most secure strand and the recruitment-dependent ~£362k as conditional. This is a good example of advocacy framing ("cost neutral") that the economics should gently qualify.
- **Workforce reconciliation.** The national case quotes Hywel Dda variously at 2 and 3 substantive consultants; the board's own paper is unambiguous — **2 substantives** (both of retirement age, one already retired-and-returned) against a **budgeted 8.26 WTE** and a modelled requirement of 9, plus 2 CESR locum-consultants and 1 high-cost agency locum. The "25% west Wales gap" holds.

The Hywel Dda paper also quantifies the **asymmetric downside** of the do-nothing path more starkly than the national case: if its fragile service collapsed, outsourcing it entirely would cost **~£2.8m for microscopic reporting alone, or ~£4.44m including consultant-grade macroscopic dissection (2024/25 rates)** — for that one board. That is the tail risk the ~£500k/year is partly insuring against.

---

## 5. Where the monetisable value actually comes from

Framed as cost-consequence, the monetisable strands are:

1. **Avoided/contained outsourcing and locum spend — now a measured Welsh figure.** The BJC reports NHS Wales spent **almost £4m on outsourcing in 2023/24, up from £1.2m** in the previous version of the case (November 2023 per board: ~£2m Cwm Taf Morgannwg, ~£0.9m Swansea Bay, ~£0.66m Aneurin Bevan, ~£0.39m Cardiff & Vale, and ~£0.4m of in-lieu-of-locum cost at Hywel Dda; Betsi Cadwaladr relies on heavy insourcing instead). **The Hywel Dda cross-check shows this £4m is external-outsourcing only, and understates the true cost of covering the gap.** Hywel Dda contributes ~£0 to that £4m headline (it insources rather than using external companies) yet spends ~£327k a year on ILOL sessions *and* ~£335k on a high-cost agency locum — neither captured in the £4m. Once ILOL, agency locums and overtime are added across all six boards, the real Welsh spend on covering the workforce gap is materially higher than £4m. **Importantly, the BJC does not claim digitisation will cut this** — it argues, rightly, that multiple factors drive the spend and that digital's role is to **contain the risk of it escalating** with demand rather than to release it as cash. Alongside this, the national BJC's "prudent assessment" of workflow time saved is **~£750,000/year** of staff time redeployable to demand (and growing as volumes rise) — the most concrete monetisable benefit in the case, and framed as *capacity*, not cash.
2. **Logistics and ancillary savings.** Courier/transport and archive handling, plus **ancillary-test reduction**: the Welsh AI prostate project has already evidenced a **possible ~50% reduction in immunohistochemistry (IHC)**, and digitisation could save an estimated **2–3 WTE administrators** nationally on slide retrieval and MDT collation (a Leeds-based estimate cited in the BJC). Real, but modest at system scale relative to the workforce gap.
3. **Capacity creation** — the largest economic effect, but it is a *capacity* benefit, not automatically a cash benefit. It can be banked two ways, and the choice is a genuine decision for leadership:
   - **As capacity:** absorb the 1m→1.5m slide growth and cut diagnostic backlog/waits without proportionate headcount growth.
   - **As cash:** reduce locum/outsourcing spend.
   You generally cannot do both fully with the same gain.

### 5.1 The indirect health-outcome (QALY) logic — stated, not over-claimed

There is a credible chain from this investment to health gain: faster and more accurate cancer diagnosis → earlier and better-targeted treatment and reduced missed/under-graded cancers → improved outcomes and quality of life. In principle this generates QALYs. **I am not quantifying it here**, because the effect is diffuse, shared across many pathways, confounded by every other step in the cancer pathway, and contingent on whether freed capacity is reinvested to shorten waits. Presenting a QALY figure would be advocacy dressed as analysis. The honest statement is: the health-outcome upside is real and potentially large, concentrated in cancer pathways, but not robustly attributable to the technology in isolation.

---

## 6. Non-monetisable and system-level value

Per Green Book guidance, these are presented alongside — not hidden behind — the financial strands. For this investment they are arguably *more* important than the cash case:

| Value | Description |
| --- | --- |
| **National resilience** | Removes single-points-of-failure in fragile and single-handed services; the network, not one retiring consultant, underwrites continuity |
| **Equity of access** | Breaks the link between where a patient lives and the subspecialist expertise available to report their case; addresses North–South and rural–urban disparities |
| **Subspecialisation at national scale** | Enables a genuine all-Wales subspecialist reporting network, improving quality for rarer/complex cancers |
| **Precision-medicine enablement** | Digital substrate is a precondition for computational biomarkers, integration with genomics, and a cellular-pathology "centre of excellence" |
| **Workforce sustainability & recruitment** | Flexible/remote reporting and skill-mix development (e.g. consultant biomedical scientists) widen the recruitable workforce and support modern (digital) training |
| **Quality and safety** | Reduced diagnostic variability; AI safety-net against missed small cancers; auditability of the digital record |
| **Strategic option value** | Once the platform and governance exist, future regulated AI tools and new pathways are addable at marginal cost — this compounds over the long horizon and is the strongest long-term economic argument |

---

## 7. Scenarios (the real decision space)

| Scenario | Description | Likely value profile |
| --- | --- | --- |
| **A. Do nothing** | Glass workflows persist | Rising locum/outsourcing spend, growing backlog, continued collapse risk in fragile services. Negative trajectory. |
| **B. Fragmented board-led** | Boards digitise separately | Captures *local* logistics gains but loses the load-balancing, resilience and interoperability value; risks stranded, non-interoperable investment. Weakest value-for-money of the "do something" options. |
| **C. National digitisation** | "Once for Wales" backbone | Strong system, resilience, equity and option value; modest direct cash savings; the robust core of the case. |
| **D. National backbone + phased AI** | C plus targeted AI | Adds workload-triage, safety and standardisation value on high-volume pathways; higher recurring cost and governance burden; benefits concentrated where AI is validated and prevalence is favourable. |

The economically coherent recommendation set is **C as the priority, with D as a phased fast-follow** — not AI-first, and not fragmented.

---

## 8. Sensitivity — what the conclusion actually hinges on

Because this is a capacity/quality investment, the result is sensitive less to unit costs than to **operating-model and reinvestment choices**:

| Driver | Why it matters | If unfavourable |
| --- | --- | --- |
| **Networked operating model adopted** | Most value (load-balancing, resilience, subspecialisation) requires reporting reform across boards, not just hardware | If boards digitise in silos, a large share of the benefit evaporates — the case weakens to little more than local logistics |
| **Capacity vs cash decision** | Determines whether the gain shows up as shorter waits or lower locum spend | Ambiguity here makes benefits unrealised and the case look weaker than it is |
| **AI generalisability on Welsh data** | AI value depends on validated performance across Welsh scanners/case-mix | If generalisation is weak, defer/narrow AI; digitisation case stands alone |
| **Storage cost trajectory** | Dominant recurring cost; grows with volume | High storage cost erodes long-run affordability; mitigated by tiered storage/retention policy |
| **Clinical adoption & change capacity** | Benefits need engaged reporters and trained staff | Poor adoption is the most common reason digital pathology underdelivers |

**What would change the conclusion:** if the AI layer were assessed *in isolation* (stripped of the digitisation backbone), its standalone cash-releasing case is weak and I would be markedly more cautious — recommending it only on specific, high-volume, validated, regulated pathways with explicit benefits-realisation. Conversely, the *digitisation backbone* case (Option C) is robust across virtually all assumptions, because its value is structural (resilience, equity, option value) rather than dependent on a particular savings estimate.

---

## 9. Comparison and read-across

| Comparator | Position | Implication for Wales |
| --- | --- | --- |
| Ireland | Fully digital cellular pathology | National-scale digitisation is operationally proven |
| Scotland | Almost fully digital | A devolved-nation national model is feasible |
| England (e.g. NPIC/Leeds–Nottingham, PathLAKE/Midlands) | Mature digital networks, some with AI/research | Networked, hub-and-spoke models with AI and research value are the established direction of travel |

The strategic risk of *not* proceeding nationally is falling behind comparable systems while demand rises and the workforce shrinks — a point Welsh boards have themselves made in their business cases.

---

## 10. Equity and distributional analysis

- **Geographic:** national reporting equalises access to subspecialist expertise regardless of patient location; directly benefits smaller and rural boards currently exposed to single-handed-service risk.
- **Diagnostic equity:** AI-assisted standardisation reduces the chance that the quality of a patient's diagnosis depends on which reporter or site they happen to land with.
- **Workforce equity:** flexible/remote reporting supports a broader, more sustainable and more diverse workforce (including consultant biomedical scientists), and modern digital training.
- (Welsh-language considerations are limited here, as cellular pathology reporting is a back-office diagnostic function rather than a patient-facing one.)

Net equity effect: **clearly positive**, and concentrated on the parts of NHS Wales currently least able to sustain services alone.

---

## 11. Summary and recommendation

### 11.1 Assessment

- This is best understood as a **national infrastructure and capacity investment with strong option value**, not a discrete cost-per-QALY intervention. A cost-consequence and option-value framing is the honest one.
- The **digitisation backbone (Option C) is well justified** on resilience, equity, workforce-sustainability and option-value grounds, with logistics savings as a modest bonus. Its case holds across virtually all assumptions and aligns squarely with the "once for Wales" strategy.
- **AI (Option D) adds genuine, evidence-backed value** — workload triage, a missed-cancer safety net, and standardisation — but it is concentrated on specific high-volume pathways, carries recurring cost and governance burden, and should be **phased behind digitisation**, on validated and regulated tools, with explicit benefits-realisation gates.
- The dominant uncertainty is **not the technology but the operating model**: the value is unlocked by networked reporting and a clear decision on whether freed capacity is banked as shorter waits or as cash. Hardware without that reform underdelivers.
- The downside is bounded and the upside compounds: a fragmented or do-nothing path carries its own rising costs (outsourcing already up from £1.2m to ~£4m/year, growing backlog, collapse risk, stranded local investment).
- The validated cost is now known: a **fully revenue-funded managed-service** commitment of **~£34.4m over 2025/26–2034/35** (plus £0.42m non-recurring), falling to health boards. This confirms a permanent revenue claim rather than a one-off capital spend — with HB **affordability and funding commitment**, not value-for-money, the live risk (Welsh Government has declined to fund the procurement phase).

### 11.2 Recommendation (advice, not instruction — the decision and accountability remain with leadership)

**Proceed with the national digitisation backbone as the priority investment, and treat AI as a phased fast-follow.** Specifically:

1. Commit to **Option C/D nationally** rather than fragmented board-led digitisation, to avoid stranded, non-interoperable investment.
2. Make the **networked operating model and reporting reform an explicit, funded part of the programme** — not an afterthought — because that is where most value is realised.
3. **Decide, and state, whether the primary objective is capacity (cutting waits/backlog) or cash (reducing locum/outsourcing spend)**, and instrument the programme to measure that benefit.
4. **Phase AI** onto validated, regulated, high-volume pathways (prostate is the strongest evidenced starting point), behind clear clinical-governance, information-governance and validation gates on Welsh data.
5. Tie investment release to the **NDCP business justification case** for the validated cost and benefit profile, and to defined benefits-realisation checkpoints.

### 11.3 Suggested decision/review points

- **Pre-commitment:** secure health-board revenue commitment in IMTPs, and confirm the operating model (networked reporting), the national storage/retention strategy, and the capacity-vs-cash objective, before contract award.
- **Post-digitisation (12–18 months):** evaluate realised turnaround-time, load-balancing and resilience benefits before scaling the AI layer.
- **Per AI tool:** require Welsh-data validation, regulatory status and a defined target pathway before deployment; review specificity/workload trade-offs in live use.

---

# Part B — Product & delivery perspective

**Author:** Dan (Senior Responsible Owner, NHS Wales App / Digital Services for Patients and the Public Programme) · **Lens:** feasibility, effort, dependencies, delivery risk, resourcing

## B0. A scope boundary, stated plainly

Before anything else, a product leader's honesty check: **the national digital cellular pathology programme is not an NHS Wales App feature, and my team is not its delivery vehicle.** It is clinical and laboratory infrastructure — scanners, the laboratory information management system (LIMS), the national image store, pathologist reporting tools and AI for clinicians — procured as a managed service through the National Pathology Programme and NWSSP. Bronwyn's £34.4m case stands or falls on its own clinical and economic merits; the app has no bearing on it.

So my contribution is two things: (1) keep the scoping clean so we don't accidentally load lab infrastructure onto the app's roadmap or vice versa; and (2) identify the **genuine patient-facing product opportunity this capability unlocks**, and tell you honestly what it would take to deliver. The two worlds meet at exactly one place: the **results-and-pathway surface** the patient sees.

## B1. Why there is a real product opportunity here

The NHS Wales App was relaunched out of beta in May 2025 and is now positioned as the "digital front door" to NHS Wales. It already lets people view referrals and track waiting-list progression, order repeat prescriptions, see a health timeline, message securely and book GP appointments — with **requesting test results, hospital-appointment management and treatment-waiting-time tracking on the published near-term roadmap**. Identity is handled through NHS login plus the Welsh Identity Verification Service, and the app is bilingual by statute.

That matters because it means the obvious feature here is an **extension of where the product is already going, not a new invention**. As cellular pathology digitises and reporting gets faster and more standardised — and as results already flow LIMS → Welsh Clinical Portal — the app is the natural place to turn that back-office speed into something a patient can actually see and feel.

## B2. The proposed feature: "Track your test" (diagnostic-pathway visibility + results surface)

A patient-facing capability in the NHS Wales App for anyone whose tissue sample goes through cellular pathology:

- **Pathway visibility** — a simple, honest status view: *sample received → being analysed → reported → discussed at MDT → results available*, with realistic expected timescales framed against the 7-day USC / 14-day urgent / 28-day routine targets.
- **Results availability (not results push)** — where clinically appropriate and authorised, a prompt that *results are ready and the care team will be in touch*, rather than surfacing the diagnosis itself. This aligns with the roadmap's "request test results" but respects the reality that **you do not deliver a cancer diagnosis via an app notification**.
- **AI transparency** — a plain-language note where AI assisted the analysis. Cheap to build, and it gives the AI layer the patient-facing transparency/consent story it needs anyway.
- **Next step** — book or confirm the next appointment in the pathway, reusing the app's existing booking capability.

This directly amplifies the patient-facing benefits Bronwyn identifies — faster turnaround, equity, transparency — and it addresses the specific patient-anxiety risk the BJC names (people waiting, anxious, for results).

## B3. Feasibility and complexity

| Feature component | Build complexity | Primary dependency | Note |
| --- | --- | --- | --- |
| Pathway status tracking | Medium–High | Real-time status events from LIMS 2.0 + an agreed cancer-pathway data model | The hard part is not the UI; it is getting accurate, real-time status out of lab systems and mapping it to a patient-legible pathway |
| Results-availability surface | High (clinical-safety-dominated) | Welsh Clinical Portal integration + a clinical "results-release" policy | Aligned with the roadmap's "request test results"; the complexity is governance, not code |
| AI-involvement transparency statement | Low–Medium | IG/consent framework + plain-language content | Inexpensive; valuable because the AI layer needs a transparency story regardless |
| Next-step appointment action | Medium | Existing app booking + health-board systems (e.g. WPAS) | Reuses an existing capability rather than building new |

In short: the UI is the easy part. The genuine engineering and governance effort is in the integrations (LIMS 2.0, Welsh Clinical Portal) and the clinical-safety rules around releasing results.

## B4. Dependencies (the feature is downstream of other things)

This feature cannot meaningfully ship ahead of its dependencies, and most are outside the app team's control:

- **The pathology programme itself.** There is no point showing a patient a faster, smarter pathway if the back office is still on glass slides. The feature is contingent on Phase 3 digitisation actually landing.
- **LIMS 2.0 and the Welsh Clinical Portal** — the status events and authorised results both originate here. The BJC already flags LIMS 2.0 integration as a live risk for the pathology programme; that risk is inherited by this feature.
- **Identity assurance** (NHS login / Welsh Identity Verification Service) — already in place, a genuine asset.
- **Clinical safety** (DCB0129/DCB0160 assurance) and a clinician-owned **results-release policy**.
- **IG / DPIA** — covering both patient results and the handling/transparency of AI outputs.
- **Welsh language** — statutory, so bilingual content is in scope from day one, not retrofitted.

## B5. Delivery risks

- **Clinical safety is the dominant risk.** Surfacing a serious result inappropriately — or letting a patient infer a cancer diagnosis from a status change — is the failure mode that matters most. Mitigation: clinician-in-the-loop release rules; status language that never implies a diagnosis; no result content without an explicit, governed release.
- **Surfacing the backlog rather than the benefit.** A tracker that mostly says "delayed" simply advertises the very problem the £34.4m is meant to fix. Deploying the feature *before* digitisation has matured would erode trust. This is a sequencing risk, not a design flaw.
- **Digital exclusion.** The cancer-pathway demographic skews older and more digitally excluded — the same caveat that applies to any NHS Wales App feature. It must supplement, never replace, letters and phone contact.
- **Dependency/timeline risk.** Because the feature sits downstream of Phase 3 and LIMS 2.0, its timeline is hostage to theirs.
- **Expectation management.** Showing timescales creates an implicit promise; the service has to be able to meet them often enough that the feature builds confidence rather than complaints.

## B6. Effort, sequencing and resource

- **Do not build ahead of the infrastructure.** Sequence: Phase 3 digitisation and LIMS 2.0 / Portal integration stabilise *first*; the app feature follows.
- **A safe MVP** is pathway status plus a "results ready — your team will contact you" prompt, with **no diagnosis content**. Results detail and AI-transparency are fast-follows once the clinical-safety and IG frameworks are bedded in.
- **Effort.** A realistic discovery → alpha → beta → live cycle is a multi-quarter product effort with a dedicated DSPP squad (product manager, service designer, a clinical safety officer, integration engineers, IG and Welsh-language input), plus clinical governance sign-off. This is product investment *on top of*, and separate from, the pathology managed-service cost — and it is modest by comparison.

## B7. Joint economist + product view (Bronwyn + Dan)

- **The pathology investment justifies itself without the app.** The app feature is additive, not a prerequisite — we should not let an app ambition drive, delay or inflate the pathology business case.
- **But the app is where patients actually experience the value.** Faster, more transparent, more equitable pathways become visible to citizens through the app — and once the Portal integration and digitisation exist, that visibility is **low marginal cost for high experiential and option value**. That is squarely consistent with Bronwyn's option-value argument: the platform unlocks cheap, valuable downstream features.
- **Sequencing is the shared discipline.** Build the app layer *after* digitisation matures, or it surfaces the backlog instead of the benefit. Economics and product agree on the order of operations.
- **Combined recommendation:** treat "Track your test" as a **fast-follow, additive DSPP product**, explicitly dependent on Phase 3 and LIMS 2.0, scoped initially to pathway-status + results-ready prompt (no diagnosis push), with clinical-safety and digital-exclusion guardrails — and resourced separately from, but timed to follow, the pathology programme.

---

## Appendix A: Methodology notes

- **Framing:** cost-consequence and option-value analysis (HM Treasury Green Book), in preference to a single ICER, because the intervention is a shared platform/capacity investment with diffuse, hard-to-attribute health effects.
- **Discounting:** 3.5% real (Green Book) should be applied to any cost/benefit profile derived from the procurement business case.
- **Approach to numbers:** cost, activity, workforce and Welsh-deployment figures are taken from the **NDCP BJC (v18.0)** and NHS Wales / health-board sources and attributed accordingly; broader workforce and efficiency context from RCPath and the digital-pathology literature; AI performance from peer-reviewed validation studies and the Welsh IBEX/Moondance projects. Where the BJC quotes a figure I quote it directly; where I extrapolate or contextualise, I say so. Ranges and scenarios are used elsewhere to avoid false precision.
- **Explicit limitation:** this is proportionate decision-support, not an HTA, and not a substitute for clinical validation, procurement, or financial appraisal.

## Appendix B: Key sources

1. NHS Wales Executive — National Pathology Programme / Digital Cellular Pathology programme pages (programme status; >95% glass-vs-digital concordance; AI in scope).
2. **NHS Wales Executive, National Pathology Programme — Business Justification Case for National Digital Cellular Pathology, Phase 3 National Scale Up (version 18.0)** (as tabled at Cardiff & Vale UHB Board, 2024/25). Source of: the funding ask (£423k non-recurring / £71k per HB; £34.4m revenue 2025/26–2034/35); the fully-revenue managed-service preferred option; the ~£4m (from £1.2m) outsourcing figures and per-board breakdown; the ~£750k/year productivity estimate; the Welsh workforce establishment and gap data (25% west Wales; HDUHB 3 vs 9; ~8.5 SE Wales; 17% locums; 36% over 55); the AI prostate results (IBEX; ~13% accuracy; ~50% IHC reduction; all six HBs by May 2024); lymphoma two-week-to-24-hour and voice-recognition findings; storage parameters (49TB/board; £150k interim; 1–1.5GB/slide; cloud-first); the 8–11% cancer rate in "routine" specimens; and the activity figures (~1m slides 2022/23, ~1.5m by 2025/26).
2a. **Hywel Dda UHB — Digital Cellular Pathology Business Justification Case Supporting Paper** (Executive Team / Sustainable Resources Committee, 2024). Source of the per-board apportionment cross-check: HDUHB recurring commitment ~£500k/year; the "cost-neutral (£0)" framing and its ~£502k savings build-up (£185k locum-to-substantive; £177k ILOL; £140k AI-driven IHC/second-opinion); the workforce position (2 substantive vs 8.26 WTE budgeted / 9 required; 2 CESR + 1 agency locum); and the service-collapse outsourcing estimate (~£2.8m reporting / ~£4.44m including macroscopic dissection, 2024/25).
3. NWSSP Procurement Services — All Wales Digital Cellular Pathology Managed Service tender notices (national service scope; AI/ML/DL; WLIMS and Welsh Clinical Portal integration).
4. Royal College of Pathologists — *Meeting Pathology Demand: Histopathology Workforce Census* (3% of departments adequately staffed; 78% with vacancies; ~£27m/year UK cost of shortages) and the more recent RCPath workforce census (staffing inadequacy; overtime; rising demand and complexity).
5. Peer-reviewed AI-in-pathology validation literature (Paige Prostate / FDA authorisation; standalone AUCs; AI-assisted sensitivity gains; benign auto-screening sensitivity ~0.96 / specificity ~0.73; Gleason/ISUP standardisation; breast Ki-67).
6. Digital-pathology economic/operational studies (single-centre 5-year ~$1.3m savings; projected ~$12.4m at a large integrated organisation; reductions in glass-slide retrieval, IHC ordering and turnaround time; the caution that digital pathology may not be cash-cost-covering near-term).
7. Comparative national context: Ireland (fully digital), Scotland (near-fully digital), England networks (NPIC, PathLAKE).
8. **NHS Wales App / Digital Services for Patients and the Public (DSPP)** — Welsh Government written statement on the NHS Wales App launch (9 May 2025) and DHCW App resource-centre/roadmap material. Source for the product section: the May 2025 relaunch and "digital front door" ambition; current features (referrals, waiting-list progression, repeat prescriptions, health timeline, secure messaging, GP appointment booking); the near-term roadmap (request test results, hospital-appointment management, waiting-time tracking); NHS login plus the Welsh Identity Verification Service; and the statutory bilingual requirement.
