# ChatGPT Business + Gemini NotebookLM + GitHub Operating Contract

## Purpose

This contract defines how the three systems work together without duplicating authority or losing provenance.

## System of record

- GitHub is the canonical system of record for manifests, approved prompts, schemas, task definitions, provenance, public documentation, code, releases, and governance decisions.
- NotebookLM is the source-grounded research workspace for curated documents, summaries, questions, citations, audio/video overviews, and evidence synthesis.
- ChatGPT Business is the execution and collaboration layer for planning, drafting, coding, analysis, connected-app work, project coordination, and human-facing deliverables.

## Authority boundaries

1. NotebookLM may propose findings but does not directly change production repositories.
2. ChatGPT Business may prepare changes, issues, pull requests, documents, and implementation plans, but high-risk changes require human approval.
3. GitHub records every approved change through branches, commits, pull requests, issues, releases, and audit history.
4. Hermes routes tasks and status messages but does not override repository governance.
5. Fable 5 creates narrative and multimedia derivatives only from approved source packages.

## Canonical handoff package

Every cross-system handoff must include:

- task_id
- notebook_id
- primary_repository
- source_snapshot_date
- source_list or source_index reference
- objective
- requested_output
- factual_status: verified | supported | disputed | speculative | fictional
- risk_level: low | medium | high | restricted
- privacy_level: public | internal | confidential | restricted
- generated_by
- reviewed_by
- output_location
- provenance_record

## Standard workflow

1. Intake: ChatGPT Business or Hermes creates a task envelope.
2. Research: NotebookLM works only from the assigned source set.
3. Synthesis: NotebookLM produces cited notes and a source-grounded evidence packet.
4. Execution: ChatGPT Business transforms the packet into code, documents, plans, issues, or media briefs.
5. Validation: automated schema checks and human review verify completeness, privacy, and risk.
6. Versioning: GitHub stores approved manifests and outputs on a branch.
7. Review: a pull request records rationale, changes, tests, and provenance.
8. Release: approved material is merged, tagged, or published.
9. Feedback: Hermes updates notebook, repository, and dashboard status.

## Duplication control

Before creating a new NotebookLM, repository, prompt pack, or agent:

- search the fleet registry;
- search GitHub for overlapping names, objectives, and sources;
- designate one primary owner;
- link supporting notebooks and repositories as federated dependencies;
- merge or archive duplicate work instead of maintaining parallel undocumented copies.

## Privacy and security

Never commit API keys, passwords, personal records, private notebook source files, unreleased financial information, medical records, or restricted business data to public repositories. GitHub stores references, hashes, manifests, approved derivatives, and provenance unless a private repository is explicitly designated.

## Quality gates

A deliverable cannot be marked approved unless it has:

- a valid manifest;
- a source snapshot date;
- factual-status labels;
- privacy and risk classifications;
- an owner;
- a repository destination;
- review evidence;
- a provenance record;
- validation or test results where applicable.

## Operating principle

NotebookLM grounds the work. ChatGPT Business executes the work. GitHub governs and preserves the work. Hermes coordinates the work. Humans retain approval authority.
