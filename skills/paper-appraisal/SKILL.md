---
name: paper-appraisal
description: Use when a user asks for a journal-club review, critical appraisal or methodological assessment of a specific physical therapy or rehabilitation research paper identified by URL, title, PMID, DOI, attachment or a returned article record.
---

# Paper appraisal

Read [the evidence and tool contract](../../references/evidence-workflows.md) first.

1. Resolve and read the exact paper using the shared [exact-article full-text fallback](../../references/evidence-workflows.md#exact-article-full-text-fallback). Fetch a verified PMID or returned article UUID directly when available. Apply the shared [source-selection policy](../../references/evidence-workflows.md#source-selection-and-pubmed-approval) if a metered identifier lookup is authorized and needed. Clarify ambiguous matches instead of substituting a similar paper. Verify design from the available text.
2. State what was accessible and which source supplied it. Preserve the PhysioKeys access flags and separately label any host-read text, version and limitations. If no verified article text was accessible, stop short of an appraisal based on a snippet.
3. Produce these sections, sized to the paper and available evidence:
   - **Question and design:** population, research question, design and comparator.
   - **Methods and potential bias:** recruitment, allocation/confounding, blinding where relevant, missing data, outcome selection and analysis. For reviews, examine search/selection, included designs, heterogeneity and overlapping studies when reported. For diagnostic/measurement or prognosis studies, use their appropriate validity questions. Mark unavailable details as unknown; distinguish lack of reporting from demonstrated bias.
   - **Findings:** actual outcome measures, effect sizes, uncertainty and timepoints when supplied; separate statistical significance from practical importance. Do not invent MCIDs or assume a nonsignificant result proves equivalence.
   - **Applicability and limits:** how the study population, setting, intervention and follow-up relate to the research question; address harms only to the extent reported.
   - **Journal-club discussion:** two or three specific questions tied to the actual reporting gaps or findings.
   - **Citation and access note:** verified citation and identifier, the source URL and version actually read, and the limits on this appraisal.
4. Apply the shared [adaptive search and reading budgets](../../references/evidence-workflows.md#adaptive-search-and-reading-budgets). One identified paper needs no discovery search. Report any host fallback attempts separately. If the user supplies a larger paper set, work in batches and account for every requested ID, including duplicates, failed/unavailable records and any pending work. Keep each appraisal's facts and limitations tied to its own record.
5. Do not invent an official PEDro score, risk-of-bias result or GRADE certainty. If a fetched source reports a rating, attribute it and its scope explicitly. One paper and missing methods do not support an outcome-level body-of-evidence rating. Never assume unreported methods were performed correctly.

Example: if an RCT abstract omits allocation concealment, attrition counts, confidence intervals and harms, those fields remain unknown. Explain what full-text details would resolve them; do not fill them using typical trial practice.
