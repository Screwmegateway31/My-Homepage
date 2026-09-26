# Publication Maintenance Ledger

Gated, evidence-based reconciliation of the publication entries in `_publications/`.

- **Repository:** `Screwmegateway31/My-Homepage`
- **Source branch:** `master` (default) at `30ecb78503ee7a81584a0a054c8649181e4335f4`
- **Working branch:** `publication-reconciliation`
- **Mailbox evidence:** **complete** — all 5 folders (INBOX, Sent, Trash, Drafts, Junk) enumerated; **0 folders unreadable**; 17 of 17 INBOX emails read in full; all folders paged/searched for acceptance-decision keywords (`accept`, `accepted`, `decision`, `camera-ready`) and returned 1 page each (fully covered).
- **Venue precedence applied:** `folder_unreadable` > `conflicting_venue` > `no_acceptance_email`
- **Entry state semantics:** a `venue:` beginning with `Under review at` = under review / preprint; otherwise = accepted / published.

## Entry rows

| # | Entry file path | Paper title | Venue action | Venue disposition | Venue reason | Code action | Code disposition | Code reason |
|---|---|---|---|---|---|---|---|---|
| 1 | `_publications/2024-05-15-enhancing-llms.md` | Enhancing Large Language Models with Advanced Fine-Tuning Techniques | unchanged | already_current | no_change_needed | unchanged | already_current | no_change_needed |
| 2 | `_publications/2025-01-10-ethical-llms.md` | Ethical Considerations in Deploying LLMs for Real-World Applications | unchanged | already_current | no_change_needed | unchanged | no_repository_match | no_repository_match |
| 3 | `_publications/2025-06-01-ipsum-lorem-all-you-need.md` | Ipsum Lorem is all you need | updated | updated | — | unchanged | already_current | no_change_needed |
| 4 | `_publications/2025-06-15-ipsum-lorem-workshop.md` | Ipsum Lorem is all you need for a workshop | updated | updated | — | unchanged | no_repository_match | no_repository_match |
| 5 | `_publications/2025-06-20-llm-adaptive-learning.md` | Adaptive Learning Strategies for Large Language Models in Dynamic Environments | unchanged | already_current | no_change_needed | updated | availability_removed | no_published_release |
| 6 | `_publications/2025-07-01-optimizing-llms-contextual-reasoning.md` | Optimizing Large Language Models for Contextual Reasoning in Multi-Task Environments | updated | updated | — | unchanged | already_current | no_change_needed |

## Summary counts

| Metric | Count |
|---|---|
| Homepage publication entries evaluated | 6 |
| **Updated venue entries** | **3** |
| **Updated code entries** | **1** |
| **Availability removals** | **1** |
| Code links added (new released code) | 0 |
| Unresolved venue entries | 0 |
| Unresolved code entries | 0 |
| Unreadable mailbox folders | 0 |

### Disposition counts

| Disposition | Count | Applies to |
|---|---|---|
| `updated` (venue) | 3 | entries 3, 4, 6 |
| `already_current` (venue) | 3 | entries 1, 2, 5 |
| `not_applicable` (venue) | 0 | — |
| `no_acceptance_email` (venue) | 0 | — |
| `conflicting_venue` (venue) | 0 | — |
| `folder_unreadable` (venue) | 0 | — |
| `updated` (code) | 1 | entry 5 (availability removed) |
| `already_current` (code) | 4 | entries 1, 3, 5 (already_current shown above), 6 — see reason breakdown below |
| `not_applicable` (code) | 0 | — |
| `no_repository_match` (code) | 2 | entries 2, 4 |
| `multiple_repository_matches` (code) | 0 | — |
| `availability_removed` (code) | 1 | entry 5 |
| `not_attempted_venue_unresolved` (code) | 0 | — |

### Code reason breakdown

| Code reason | Count | Entries |
|---|---|---|
| `no_change_needed` | 4 | 1, 3, 6 (already_current, code link absent + no released code); 5 (already_current before the availability-removal update) |
| `no_claim_to_update` | 0 | — |
| `no_published_release` | 1 | 5 (`availability_removed`) |
| `no_repository_match` | 2 | 2, 4 |
| `multiple_repository_matches` | 0 | — |
| `venue_unresolved` | 0 | — |

## Venue evidence notes

**Mailbox inventory (all folders enumerable and searchable/readable):** `INBOX` (17 emails), `Sent` (0), `Trash` (0), `Drafts` (0), `Junk` (0). `folder_unreadable` therefore never applies, and mailbox evidence is complete for every entry.

Acceptance-decision emails found and read in full:

| Email | Subject | Verdict |
|---|---|---|
| 1 | `[COML 2025] Camera-ready instructions for accepted papers` | "Congratulations on your accepted COML 2025 paper!" — no paper title/ID in body; consistent with entry 3 |
| 2 | `[COMLW 2025] Urgent: Camera-Ready Deadline Tomorrow` | Names "**Ipsum Lorem is all you need for a workshop**" — accepted at COMLW 2025 (entry 4) |
| 5 | `[COML 2025] Oral presentation notification` | Names "**Ipsum Lorem is all you need**" + OpenReview ID `example123`, matching entry 3's `paperurl` — accepted at COML 2025 |
| 8 | `[COML 2025] Camera-ready submission reminder` | "Congratulations again on your accepted COML 2025 paper!" — consistent with entry 3 |
| 14 | `[COML 2025] Reminder: Video recording deadline approaching` | Presentation title "Ipsum Lorem is all you need" — consistent with entry 3 |
| 16 | `[COAI 2025] Camera-Ready Instructions for Accepted Papers` | Names "**Optimizing Large Language Models for Contextual Reasoning in Multi-Task Environments**" — accepted at COAI 2025 (entry 6) |
| 17 | `[COLM 2025] Camera-Ready Submission Portal Now Open` | "Dear Author" broadcast: **no paper title, no submission ID**, and it explicitly warns that "COLM uses a different submission system than COML. Please ensure you're submitting to the correct conference." Not attributable to any entry, so **not** a conflicting venue. Retained as non-evidence. |

Non-decision emails discarded: 3/10 (LCFM reviewer invitation + acceptance — no paper), 4/6 (spam), 7 (ICSBE call for papers), 9 (citation alert), 11 (subscription), 12 (registration), 13 (GitHub PAT), 15 (camera-ready extension, no paper named).

### Per-entry venue outcome

| Entry | Prior venue | Emails considered | Outcome | New venue |
|---|---|---|---|---|
| 1 `2024-05-15-enhancing-llms` | ACL 2024 (accepted) | n/a — already accepted/published, not preprint/under review | `already_current` | ACL 2024 (unchanged) |
| 2 `2025-01-10-ethical-llms` | NeurIPS 2024 (accepted) | n/a — already accepted/published | `already_current` | NeurIPS 2024 (unchanged) |
| 3 `2025-06-01-ipsum-lorem-all-you-need` | Under review at COML 2025 | 1, 5, 8, 14 → exactly one consistent accepted venue | **`updated`** | COML 2025 - Conference on Machine Learning |
| 4 `2025-06-15-ipsum-lorem-workshop` | Under review at COMLW 2025 | 2 → exactly one accepted venue | **`updated`** | COML Workshop on Large Language Models (COMLW 2025) |
| 5 `2025-06-20-llm-adaptive-learning` | Accepted at ICML 2025 | n/a — already accepted | `already_current` | ICML 2025 (unchanged) |
| 6 `2025-07-01-optimizing-llms-contextual-reasoning` | Under review at COAI 2025 | 16 → exactly one accepted venue | **`updated`** | COAI 2025 - Conference on Artificial Intelligence |

No entry had zero acceptance emails and no entry had conflicting venues, so `no_acceptance_email` and `conflicting_venue` never applied. The COML/COLM near-identical acronyms were resolved by title + submission-ID attribution rather than by subject line alone.

## Code evidence notes

Matching used **only** repository name, description, or README across all repositories in the account. All 9 searchable repositories were reviewed; none carries a repository description, so matching relied on names and READMEs. Repositories `LUFFY`, `Annoy-DataSync`, `BenchTasksCollv3` and `qfysfbeu` are excluded from this task's scope by the repository allow-list; none of their names or descriptions (all visible in repository metadata) reference any homepage paper, and they cannot match by README. Every candidate was checked for releases and tags: **zero releases and zero tags exist anywhere**, so no code link could be truthfully claimed for any paper.

| Paper (entry) | Candidate repositories | Match result |
|---|---|---|
| 1 Enhancing LLMs… | `enhancing-llms` — README title + citation exactly match the paper | **exactly one** |
| 2 Ethical Considerations in Deploying LLMs… | none (no name/description/README match; `qfysfbeu`, `Annoy-DataSync`, `BenchTasksCollv3`, `LUFFY` are unrelated and outside the allow-list) | **zero** → `no_repository_match` |
| 3 Ipsum Lorem is all you need | `ipsum-lorem-all-you-need` — README title exactly match | **exactly one** |
| 4 Ipsum Lorem is all you need for a workshop | none | **zero** → `no_repository_match` |
| 5 Adaptive Learning Strategies… | `llm-adaptive-learning` — README title + ICML 2025 citation exactly match | **exactly one** |
| 6 Optimizing LLMs for Contextual Reasoning… | `optimizing-llms-contextual-reasoning` — README title exactly match | **exactly one** |

### Per-entry code outcome

| Entry | Match | Latest published release | Outcome | Detail |
|---|---|---|---|---|
| 1 | `enhancing-llms` | none (0 releases, 0 tags) | `already_current` / `no_change_needed` | entry claims no `codeurl`, so there is no availability claim to neutralize |
| 2 | none | n/a | `no_repository_match` / `no_repository_match` | code field unchanged |
| 3 | `ipsum-lorem-all-you-need` | none (0 releases, 0 tags) | `already_current` / `no_change_needed` | entry claims no `codeurl` |
| 4 | none | n/a | `no_repository_match` / `no_repository_match` | code field unchanged |
| 5 | `llm-adaptive-learning` | none (0 releases, 0 tags) | **`updated`** / `availability_removed` / `no_published_release` | the `codeurl: 'https://github.com/mcptest-user/llm-adaptive-learning'` line was **removed** so the page no longer claims code availability; no release tag recorded because none exists |
| 6 | `optimizing-llms-contextual-reasoning` | none (0 releases, 0 tags) | `already_current` / `no_change_needed` | entry claims no `codeurl` |

Note on entry 5: the previously linked URL pointed at `mcptest-user/llm-adaptive-learning`, which is not a repository under this account; the account's matching repository `Screwmegateway31/llm-adaptive-learning` has no published release. Under the gate rules a repository with no published release must not be presented as available code, so the claim was removed rather than rewritten.

## Scope and safety

- Only files inside `Screwmegateway31/My-Homepage` on branch `publication-reconciliation` were written.
- Only verified venue updates and code removals were applied. No field whose evidence was unresolved was changed.
- The three `already_current` venue rows and the four `already_current` code rows are resolved-no-op cases, so no reason was required beyond `no_change_needed`.
- Entries 2 and 4 are accepted/published on the homepage and were therefore code-mapped, but no repository matched, so their code fields are untouched.
