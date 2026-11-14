# CloudTalk Docs Pipeline (unofficial learning project)

An independent portfolio project exploring how a product education team can keep
documentation, in-app guidance and AI answers in step with a fast release pace,
using AI-assisted drafting with mandatory human review.

> Not affiliated with CloudTalk. Based only on publicly available product updates.
> All summaries are written in my own words, with sources linked.

## The problem
Shipping 100+ releases a quarter makes manual documentation unsustainable.
Docs drift from the product, and customers (and AI tools) get outdated answers.

## The approach
1. **Release → docs draft:** a public release note becomes a docs update draft (AI-assisted).
2. **Human review + rules:** every change is reviewed; every mistake becomes a written rule.
3. **Drift checks:** docs are compared against a source-of-truth facts file.
4. **Most-asked topics:** support questions are grouped to decide what to fix first.
5. **How-to launch:** one bigger change taught end to end (docs, in-app tour, webinar, metrics).

## Repository structure
- `release-notes/`: my summaries of public CloudTalk product updates, with sources
- `docs/`: the documentation drafts
- `rules/`: style guide, prompts, review checklist, error log
- `reports/`: drift checks and topic analysis
- `launch/`: the how-to launch package

## Status
Work in progress. Updates are tracked in the commit history.

## What I'm learning
Docs-as-code (Markdown, Git, pull requests) and building repeatable AI workflows.
