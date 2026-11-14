---
title: CSV upload now supports campaign tags and preferred agent
source: https://www.cloudtalk.io/blog/product-update-january-2026/
source_date: 2026-01-16
area: Contacts / CSV import
audience: Admins of teams without a CRM integration
status: summarized
---

## What changed
1. During CSV upload you can now assign campaign tags (multiple per contact)
   and a preferred agent per contact, instead of doing it afterwards.
2. Importing is faster, and there is an import history with statuses and a
   detailed log of succeeded and failed rows, with reasons.

## What it means for customers
Teams that import contacts by file no longer need to split their files or
fix tags and agent assignments afterwards, and they can troubleshoot failed
imports without guessing.

## Docs impact (to verify)
- The CSV import help article likely needs new column descriptions.
- A sample CSV template may need the new columns.
- A troubleshooting section may be needed for reading the import log.
- Check whether existing screenshots still match the upload screen.

## Open questions
- Which column names does the importer expect for tags and agent?
- What happens if a tag or agent in the file does not exist yet?
- Should the two changes be separate release note files?
