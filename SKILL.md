---
name: obsidian-article-writeback
description: Use when turning project guidance, design notes, agent discussions, recent Codex work, or external article summaries into shareable Chinese Obsidian Knowledge articles, especially when the user asks to write into Knowledge, curate publishable topics, avoid duplicate topics, de-brand project material, or manage internal/draft/published article layers.
---

# Obsidian Article Writeback

## Overview

Turn reusable project or research insight into a practical Chinese Knowledge article. The default local target is `<your-vault>/Knowledge`.

## When To Use

Use this for:

- selecting which recent work is worth writing into Knowledge
- writing or rewriting a shareable Knowledge article
- converting project-specific experience into de-branded method writing
- separating internal originals, pending-publication drafts, published notes, and article ledger entries

Do not use this for repo devlogs, implementation docs, or spoiler-heavy lore with little reusable method value.

## Workflow

1. Confirm source and target.
   - Use the user-provided vault path when given; otherwise default to `<your-vault>/Knowledge`.
   - Read only the source material needed to extract the method.
   - If curating topics, list existing Knowledge titles first to avoid duplicates.

2. Extract the portable method.
   - Keep the repeatable decision, workflow, principle, checklist, or anti-pattern.
   - Remove project-only lore, transient implementation trivia, and assistant-process framing.
   - Preserve concrete operational nouns only when they teach the method.

3. Shape the article.
   - Default Chinese structure: `问题 -> 原因 -> 结论 -> 推荐流程 -> 常见错误 -> 最简原则`.
   - For publishing batches, maintain separate internal, pending-publication, and published layers.
   - Mark published articles with publish date and a no-duplicate-publication note when that convention exists.
   - For CTA, choose by article type: follow for series positioning, save for checklists/templates, comment for debate.

4. Write and verify.
   - Write Markdown into the target Knowledge vault only when the user asked for writeback.
   - Re-read the saved file.
   - Check language, headings, duplicate topic risk, banned project names, and any requested de-branding.
   - Report exact paths and what was verified.

## Output Contract

For curation, report candidate titles, duplication status, reuse value, and recommended order. For writeback, report created/updated paths, source material used, verification performed, and any content deliberately left internal.

## Common Mistakes

- Writing a project postmortem instead of a reusable article.
- Skipping the existing-title check and duplicating an old Knowledge note.
- Leaving project names in public copy after the user asked for de-branding.
- Treating a chat-only draft as done when the request was to write into the vault.
- Using the same CTA on every article instead of matching the article's job.
