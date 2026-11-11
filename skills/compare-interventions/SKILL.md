---
name: compare-interventions
description: Use when a user asks to compare rehabilitation interventions, exercise approaches or treatment alternatives using published research, including which approach is better and where results differ.
---

# Compare interventions

Read [the evidence and tool contract](../../references/evidence-workflows.md) first.

1. Establish the condition/population, alternatives and outcomes. Use a supplied comparison directly; clarify only a difference that would change which evidence applies.
2. Choose depth from the shared [adaptive search and reading budgets](../../references/evidence-workflows.md#adaptive-search-and-reading-budgets). If the comparison is limited to supplied or selected papers, skip discovery and read that set. For discovery, start with one search naming both alternatives and the condition, using the [source-selection policy](../../references/evidence-workflows.md#source-selection-and-pubmed-approval) and the live schema's supported result maximum. Prefer relevant direct comparisons. Refine to fill an identified comparator, outcome or follow-up gap within the whole-task budget. Read chosen papers in batches using the shared [exact-article full-text fallback](../../references/evidence-workflows.md#exact-article-full-text-fallback) for their access and provenance. A thorough comparison can require more than five papers. Use the shared source-specific ledger for larger comparisons.
3. Build a readable comparison table, combining columns where helpful, that preserves source/citation, population and sample size if reported, intervention and comparator, outcome/measure, follow-up, reported result/uncertainty, and evidence access. Use “not reported in available text” for missing facts instead of invented values. If no relevant paper was returned, give a short explanation of the search limits rather than an empty table.
4. Separate **direct comparative findings** from **indirect evidence**. Two trials against different controls do not establish which intervention is superior. Compare like outcomes and timepoints; do not pool or rank incompatible populations, scales or follow-up periods. A statistically nonsignificant result does not establish equivalence.
5. Explain what the evidence supports for the user's general research question, what prevents a fair comparison, and what a useful head-to-head study would need to resolve. Do not manufacture a winner, numerical effect, formal certainty grade or patient-specific recommendation.
6. State source coverage, search-call count, unique candidates screened, papers actually read/included and access limitations, sized to the request. Report any host fallback attempts separately. Do not turn screened snippets into claims of completed reading. If asked to save cited papers, use only verified PMIDs and the existing save tool, report each actual outcome, and identify UUID-only sources that cannot be saved through that tool. Do not save merely because a paper was cited.

Example: eccentric loading versus heavy slow resistance for Achilles tendinopathy. A 12-week pain trial against waitlist and a 6-week function trial against usual care belong in separate rows; their results cannot determine a treatment winner.
