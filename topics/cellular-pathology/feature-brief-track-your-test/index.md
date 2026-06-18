# Feature Brief — "Track your test"

⚠️ Disclaimer. This document is a fictitious illustrative example generated entirely by Claude Code as an experiment in applied strategy synthesis. It is not an official publication of NHS Wales, the Welsh Government, Digital Health and Care Wales (DHCW), Health Education and Improvement Wales (HEIW) or any UK public body. Quoted statistics from public sources are cited; projections, OKRs, KPIs and ROI figures are illustrative analytical estimates, not commitments. The document is intentionally bilingual in tone (Welsh / English) to reflect statutory requirements but is not a substitute for translation by qualified Welsh-language professionals. Use at your own risk.

**Product:** NHS Wales App (Digital Services for Patients and the Public) · **Prepared by:** Dan (SRO, NHS Wales App), with economic case by Bronwyn (Health Economics, DHCW) · **Date:** 18 June 2026 · **Status:** Draft for delivery board · **Decision sought:** approval to proceed to *discovery*, sequenced behind the National Digital Cellular Pathology rollout

**In one line:** Give patients a clear, honest view of where their tissue-sample test sits in the diagnostic pathway — and a safe prompt when results are ready — turning the speed of digital pathology into something patients can actually see.

---

## 1. Problem & opportunity

Patients whose tissue samples go to cellular pathology often wait days to weeks with no visibility of progress. The National Digital Cellular Pathology business case names this patient anxiety as a direct harm of slow turnaround. Two things have now changed and create the opening:

- **Cellular pathology is being digitised nationally** — faster, more standardised reporting, with results already flowing LIMS → Welsh Clinical Portal.
- **The NHS Wales App has relaunched (May 2025) as the "digital front door"** — it already shows referrals and waiting-list progression, with *requesting test results* and *hospital-appointment management* on its published near-term roadmap.

The opportunity is to make the diagnostic pathway visible — reducing anxiety and "where are my results?" contacts — at **low marginal cost on top of an investment already being made**.

## 2. The feature

"Track your test" adds to the app:

- **Pathway status** — *sample received → being analysed → reported → discussed at MDT → results available*, with realistic expected timescales framed against the 7-day USC / 14-day urgent / 28-day routine targets.
- **Results-ready prompt (not a results push)** — when clinically authorised, *"your results are ready; your care team will contact you"* — never the diagnosis itself.
- **AI-transparency note** — plain-language statement where AI assisted the analysis.
- **Next step** — book or confirm the next pathway appointment, reusing the app's existing booking capability.

## 3. Who benefits

- **Patients** — less anxiety, more control, clearer expectations; most valuable on cancer pathways.
- **Care teams & labs** — fewer chase calls and less results-handling admin; supports cancer-pathway targets.
- **Allied health (prehabilitation & rehabilitation)** — physiotherapy, occupational therapy, dietetics and speech & language teams gain earlier sight of patients entering their pathways; faster, more accurate diagnosis lengthens the prehab runway before treatment and sharpens rehab planning, improving functional outcomes.
- **The system** — makes the pathology programme's turnaround and equity benefits *visible to citizens* (the experiential value the economic case points to).

## 4. Scope

**In:** patient-facing pathway status; results-ready prompt; AI-transparency note; next-step booking; bilingual (Welsh/English) from day one.

**Out (explicitly):** pushing diagnostic results or result content via the app; clinical reporting tools (these belong to the pathology programme, not the app); building or owning the pathology platform, LIMS or national image store. *This feature is the patient-facing surface only.*

## 5. Dependencies (the feature is downstream)

| Dependency | Why it gates the feature |
| --- | --- |
| National Digital Cellular Pathology — Phase 3 | No value in showing a faster pathway if the back office is still on glass slides |
| LIMS 2.0 + Welsh Clinical Portal integration | Source of both status events and authorised results (also a live risk in the BJC — inherited here) |
| NHS login / Welsh Identity Verification Service | Patient identity assurance — already in place |
| Clinical safety (DCB0129/0160) + a results-release policy | Governs what can be surfaced, to whom, and when |
| IG / DPIA, including AI outputs | Lawful handling and patient transparency |

## 6. Key risks & mitigations

| Risk | Mitigation |
| --- | --- |
| Patient infers a serious diagnosis from a status change or notification | Clinician-in-the-loop release; status language that never implies a diagnosis; no result content without a governed release |
| Tracker surfaces the *backlog* ("delayed") rather than the benefit | Sequence after digitisation matures; honest timescale ranges; phased rollout |
| Digital exclusion (older cancer demographic) | Supplement — never replace — letters and phone; accessibility-first design |
| Over-promising on timescales | Show ranges, not guarantees; monitor target-breach rates before scaling |

## 7. Delivery approach & sequencing

- **MVP:** pathway status + "results ready, contact your team" — **no diagnosis content.**
- **Fast-follows:** richer (governed) results context; AI-transparency; deeper booking integration.
- **Lifecycle:** discovery → alpha → beta → live, gated on Phase 3 and LIMS 2.0 milestones; realistically a multi-quarter effort.
- **Principle:** do not build ahead of the infrastructure.

## 8. Resource

A dedicated DSPP squad — product manager, service designer, clinical safety officer, integration engineers, IG and Welsh-language input — plus clinical governance sign-off. This is product investment **on top of, and modest relative to**, the pathology managed-service cost (~£34.4m over 2025/26–2034/35), and is **not** funded from the pathology programme.

## 9. Success measures

- Adoption among eligible patients, with **equity of uptake** (not skewed to younger / less-deprived groups).
- Reduction in "where are my results?" contacts to GP practices and hospital secretaries.
- Patient-reported experience and anxiety during the diagnostic wait.
- *Honest caveat:* this feature improves **experience and transparency**; it does not itself speed up diagnosis — that is the pathology programme. Turnaround gains must not be attributed to the app.

## 10. Decision sought

Approval to proceed to **discovery**, on the explicit understanding that build and release are **sequenced behind** the National Digital Cellular Pathology rollout and LIMS 2.0, delivered with clinical-safety and digital-exclusion guardrails, and resourced separately within DSPP. Recommendation is offered as advice; the delivery board remains accountable for the decision.
