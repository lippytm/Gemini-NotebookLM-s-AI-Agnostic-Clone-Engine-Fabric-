# P-011-DSF-001 Integration — Gemini and NotebookLM

**Role:** Independent source-grounded research and product line  
**Canonical source:** `lippytm/Prompt-11-`  
**Canonical pull request:** https://github.com/lippytm/Prompt-11-/pull/3  
**Version:** 0.1

## Mission

The Gemini/NotebookLM line independently researches and develops the DARPA–Snowden Disclosure, Privacy & Human Resilience collection. It must not copy conclusions from the ChatGPT Business or Claude/Hermes lines before completing its own source review and QA.

The line produces separate Gemini editions of the NFT ebooks, NFT audiobooks, NFT video books, NFT interactive videos, workbooks, and Build Mode projects.

## Notebook architecture

Create separate source-grounded notebooks for:

1. DARPA mission, dual-use innovation, and technology-transition history
2. Total Information Awareness and congressional privacy controls
3. Snowden disclosure chronology and legal status
4. Section 215 bulk telephone-records history
5. Section 702, PRISM, upstream collection, FISC, and oversight
6. identity theft, synthetic identity, and digital recovery
7. medical identity, health-record integrity, medication safety, and healthcare cybersecurity
8. information operations, espionage, corruption, sabotage, and attribution
9. UAP records, official assessments, testimony, advocacy, and scientific standards
10. Ukraine and Iran conflict modules with publication-date and event-date controls
11. NFT, copyright, licensing, privacy, and on-chain/off-chain architecture
12. original story universe and human-advancement project concepts

Do not combine all subjects into one notebook until the individual notebooks have source manifests, contradiction reports, and QA status.

## Required source manifest

Every notebook must record:

```yaml
notebook_id: ""
module_id: P-011-DSF-001
canonical_version: 0.1
subject: ""
created_at: ""
last_source_refresh: ""
sources:
  - source_id: "S-000"
    title: ""
    institution_or_author: ""
    publication_date: ""
    url: ""
    source_tier: 1
    primary_or_secondary: PRIMARY|SECONDARY
    claims_supported: []
    limitations: ""
    archived_copy_reference: ""
current_status_check_required: true
review_state: DRAFT|VERIFIED|DISPUTED|REJECTED|PUBLISHED
```

## Claim-to-source matrix

Every material claim must identify:

- claim ID
- exact claim text
- truth label
- supporting source IDs
- precise page, section, paragraph, table, line, or timestamp
- counterevidence
- publication date
- event date
- current-status refresh requirement
- privacy class
- publication-safe status

Canonical truth labels:

- `VF` — Verified Fact
- `OA` — Official Assessment
- `CT` — Corroborated Testimony
- `AL` — Allegation
- `WH` — Working Hypothesis
- `FD` — Fictional Dramatization
- `CX` — Contradicted

## Independence rules

1. Gemini/NotebookLM must complete its first research draft without reading model conclusions from ChatGPT or Claude/Hermes.
2. Canonical source IDs and formatting rules may be shared; factual conclusions may not be imported without independent verification.
3. A model agreement count is not evidence. Three models repeating one weak source still represent one weak source.
4. Disagreements must be logged, not silently resolved.
5. The comparison phase begins only after each line passes its own SourceGate, TruthGate, DateGate, PrivacyGate, RightsGate, and HumanApprovalGate.

## Required independent outputs

Each notebook produces:

- source manifest
- fact chronology
- claim-to-source matrix
- contradiction report
- unresolved-questions register
- source gaps and research requests
- publication-safe summary
- independent Gemini draft
- proposed Reality, Story, Decision, and Build Mode content
- QA report

## NotebookLM audio and educational use

Notebook-generated audio or study materials are research aids, not automatically approved audiobook products. Before commercial or NFT release:

- rewrite into an original production script
- verify every factual claim and date
- confirm usage and commercial rights
- remove private or restricted data
- distinguish narration, testimony, official assessment, and fictional dramatization
- complete accessibility, medical, legal, privacy, and rights review
- obtain human approval

## Sensitive-data restrictions

Never upload the following to a general NotebookLM or Gemini research notebook:

- Social Security numbers or government identification images
- complete medical records or prescription numbers
- bank, tax, insurance, or benefits account data
- API keys, tokens, passwords, recovery codes, or private cryptographic keys
- confidential witness identities
- unredacted allegations concerning identifiable people
- unpublished classified information

Use redacted, synthetic, public-domain, or properly licensed data.

## Current-information rule

Current law, active surveillance authority, wars, sanctions, casualties, officeholders, government programs, platform terms, and prices must be refreshed immediately before publication. Notebook summaries are not permanent legal or news records.

## Product-line outputs

The Gemini line maintains separate identifiers:

- `DSF-GEM-EBOOK-*`
- `DSF-GEM-AUDIO-*`
- `DSF-GEM-VIDEO-*`
- `DSF-GEM-INTERACTIVE-*`
- `DSF-GEM-WORKBOOK-*`

Merged premium editions receive new identifiers only after cross-model comparison and human approval.

## Canonical dependency

After Prompt-11 PR #3 is merged, use:

- `docs/P011-DSF-001-darpa-snowden-disclosure-fabric.md`
- `docs/P011-DSF-001-source-register.md`
- `config/p011-dsf-001-handoff.yaml`
- `schemas/p011-evidence-claim.schema.json`

This mirror may add NotebookLM-specific procedures but may not weaken the canonical evidence, privacy, rights, or human-approval controls.
