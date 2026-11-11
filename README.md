# PhysioKeys for Claude

Find, read and cite published physical therapy, physiotherapy and rehabilitation research from a conversation with Claude, using your PhysioKeys account.

## What it adds

The PhysioKeys connector gives Claude the tools: research search, article reading, your saved papers and account status. This plugin adds guided skills that teach Claude how to use them well:

- **Evidence brief**: a focused summary of what the research supports, with the evidence, its limits and how much was actually read.
- **Compare interventions**: a comparison table that keeps direct and indirect evidence apart and never invents a winner.
- **Paper appraisal**: a journal-club review of one paper, marking unreported methods as unknown.
- **Setup**: connecting your account, what costs a search and what is free, and a first task.

The skills read each paper before making claims, say whether Claude read the abstract, partial text or full text, and cite every source. When PhysioKeys has only an abstract and Claude can browse, they allow a short, bounded attempt to read a public copy of that exact paper.

## Install

In Claude, add **PhysioKeys** from the directory under **Customize**. In Claude Code:

```
/plugin install physiokeys --marketplace jallad91/physiokeys-claude-plugin
```

## Use it

Connect PhysioKeys from the plugin's Connectors tab and sign in with your PhysioKeys account. Then ask a de-identified research question, such as "Give me an evidence brief on exercise for knee osteoarthritis" or "Compare eccentric loading and heavy slow resistance for Achilles tendinopathy". Ask "Open my PhysioKeys Research Library" to browse saved papers for free, tick papers and press **Ask Claude to compare these**.

## Costs

Each research search, and each further page of results, uses one search from your PhysioKeys plan. Opening and filtering saved papers, reading articles and checking your account do not use searches. Saving a paper counts toward your saved-paper capacity.

## Data

The plugin itself stores nothing and contains no code. Do not include patient names, dates of birth, record numbers or other identifiers; the skills refuse to send them. PhysioKeys is for general research and education, not individual diagnosis or treatment plans.

What is sent where:

- **PhysioKeys** (`https://app.physiokeys.com/api/mcp`, signed in with your PhysioKeys account): research queries, article IDs and save requests. PhysioKeys reads your saved-paper list and plan allowance, stores papers you choose to save and a usage record for each search, and keeps them until you remove them or delete your account. Its tool-usage records contain no query text or results.
- **Public article websites**, only when PhysioKeys has just an abstract and Claude's web access is turned on: the skills let Claude open a public copy of that exact paper (its publisher page, PubMed Central, or an author or institutional repository), looked up by the paper's DOI, PMID or title only, at most 3 attempts per paper and 6 per task. Nothing from your conversation, library or account is sent to these sites.

Privacy policy: https://www.physiokeys.com/privacy-policy/ · Terms of service: https://www.physiokeys.com/terms-of-service/
