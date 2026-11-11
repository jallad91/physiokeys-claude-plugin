---
name: evidence-brief
description: Use when a user asks for a focused evidence summary or research brief about physical therapy, physiotherapy or rehabilitation, including effectiveness, dosage studied, prognosis or assessment.
---

# Evidence brief

Read [the evidence and tool contract](../../references/evidence-workflows.md) first. For a comparison use [compare-interventions](../compare-interventions/SKILL.md); for appraisal of a particular paper use [paper-appraisal](../paper-appraisal/SKILL.md).

1. Identify the population, intervention/exposure, comparator if relevant, and outcome from the user's question. Ask one targeted clarification only if its absence would materially change the search. Preserve a clear question already supplied; never demand a formal PICO form.
2. If the brief is limited to supplied or selected papers, skip discovery and read that set. Otherwise choose depth using the shared [adaptive search and reading budgets](../../references/evidence-workflows.md#adaptive-search-and-reading-budgets), then start one focused `search` using the [source-selection policy](../../references/evidence-workflows.md#source-selection-and-pubmed-approval). For treatment questions, suitable reviews and RCTs are useful starting points; prognosis and measurement questions may need different designs. Use the live schema's supported result maximum and exact filter values. A clear deep-review request needs no redundant permission question within its announced budget.
3. Screen and deduplicate candidates, then read the chosen papers before claims. Follow the shared [exact-article full-text fallback](../../references/evidence-workflows.md#exact-article-full-text-fallback) for their access and provenance. Adapt the reading effort to the requested breadth; use the shared evidence ledger and coverage checkpoints for deeper reviews. Preserve distinct and conflicting findings, avoid double-counting trials included in reviews, and leave unreported facts unknown.
4. Deliver a concise answer in this order:
   - **Answer:** what the retrieved evidence supports, with appropriate uncertainty.
   - **Evidence:** for each source, population/design, intervention/comparator, relevant outcome and follow-up, reported effect/uncertainty when available, and citation/link. A compact table is useful for several papers.
   - **Limits and applicability:** differences between study populations and the question, missing methods/harms, and access depth. Do not infer a precise exercise prescription or certainty grade from study labels or duration alone.
   - **Scope:** source(s), design/year restrictions or relaxation when applicable, search calls, unique candidates screened and papers actually read/included, and remaining coverage gaps. Report any host fallback attempts separately. Use a concise scope note for a brief and fuller accounting for a deeper review; never imply that all returned candidates were read.

Example request: “Give me a brief on exercise for knee osteoarthritis.” The answer should distinguish review findings from a single trial, identify the outcome and follow-up, and state when full text or effect sizes were unavailable. A user asking for speed still needs those limits; keep them short rather than inventing precision.
