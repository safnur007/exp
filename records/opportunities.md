# Opportunity assessment — 2026-09-12

All amounts below are advertised or conditional, not agreed fees or received revenue. Estimates are planning judgments. This initial assessment predates the authorized outreach recorded at the end of this file. No purchases were made.

| Priority | Opportunity | Payout and timing | Effort / difficulty | Completion / payment confidence | Competition and intervention | Decision |
|---|---|---|---|---|---|---|
| 1 | [tscircuit contributor program](https://github.com/tscircuit/contribution-tracker/blob/main/docs/sponsorship-calculation-explanation.md), potentially [review-time table #284](https://github.com/tscircuit/contribution-tracker/issues/284) | Monthly score-based sponsorship; published base tiers $10–$700, no fixed fee for this issue | Preliminary 3–6 hours; medium; scope needs confirmation | Medium technical confidence; payment unknown until enrollment confirmed | #284 has no comments at inspection; related PR search still required. Sponsor onboarding requires owner involvement | EVALUATING; prepare scoped inquiry, do not count a receivable |
| 2 | [Omi double recording #3244](https://github.com/BasedHardware/omi/issues/3244) | Advertised $100; discretionary bounty after merge | Estimated 1–3 days; medium/high | Low with current device access; payment route unconfirmed | 22 comments; requires device/macOS reproduction; official guide requests PayPal | Defer: cannot adequately verify hardware behavior here |
| 3 | [JuliaHealth Adapt support #3](https://github.com/JuliaHealth/JuliaHealth2026BountyProgram/issues/3) | Selected projects receive $750 after acceptance | Multiple weeks; high | Low for rapid completion; funded program but selection required | Application window ended Sep 8; contributor selection Sep 16–22; owner signs NumFOCUS agreement | Defer: scheduled work starts Oct 14, unsuitable for speed |
| 4 | [AsyncAPI September website microgrant #5704](https://github.com/asyncapi/website/issues/5704) | Amount not verified | Not estimated: already assigned | Not available to us without reassignment | Assigned to anshgoyalevil | Skip |
| 5 | [Tenstorrent #56277](https://github.com/tenstorrent/tt-metal/issues/56277) | Advertised $7,500 | High; specialized accelerator testing | Low with available environment | Assigned to jasondavies, 11 comments | Skip |
| 6 | [Jarvis native installers #13](https://github.com/PG-AGI/toingg-jarvis/issues/13) | Algora bot specifies $5 | Estimated 1–3 days; cross-platform packaging | Medium technical, low payment probability due competing completed implementations | Multiple submitted native installer PRs, demo requirement, payout onboarding | Skip: poor expected return |
| 7 | [Claude changelog #1](https://github.com/claude-builders-bounty/claude-builders-bounty/issues/1) | Advertised $50 through Opire | Estimated 2–4 hours; low/medium | High technical; very low acceptance expectation | Repository displays roughly 3,100 open PRs; funding not independently verified | Skip: heavily contested |

## Evidence and constraints

- Checked source issues through the public GitHub REST API, plus linked project contribution documents. Search indexes are discovery aids only.
- [tscircuit eligibility inquiry #358](https://github.com/tscircuit/contribution-tracker/issues/358) has multiple contributor questions but no maintainer answer in the comments read. Do not infer eligibility from the scoring table.
- [Omi contribution guide](https://github.com/BasedHardware/omi/blob/main/docs/doc/developer/Contribution.mdx) distinguishes paid bounties from device/transcription-credit rewards. Credits and merchandise are not cash revenue.
- [JuliaHealth program timeline](https://github.com/JuliaHealth/JuliaHealth2026BountyProgram) requires an executed contractor agreement before paid work begins, and acceptance by December 8.
- The provided Payoneer destination is a placeholder. The actual link has been requested privately in the task, and must not be committed.
- No probability percentages are asserted: there is insufficient acceptance and payment evidence to estimate them reliably.

## Next action

The initial ranking above is superseded for tscircuit #284: a follow-up primary-source search found [open PR #335](https://github.com/tscircuit/contribution-tracker/pull/335), explicitly fixing #284. JOB-001 is now ABANDONED and its unsent inquiry is withdrawn. Do not submit another implementation of this issue.

An alternative is [Expensify's paid contribution program](https://github.com/Expensify/App/blob/main/contributingGuides/CONTRIBUTING.md). Its current guide requires a fully verified Upwork profile before applying, an accepted proposal before opening a PR, and testing across the affected supported platforms. Payments follow deployment and a minimum seven-day regression period. This is a conditional lead, not a selected job: no Upwork profile, verification, zero-cost application route, or testing access has been established. No registration, application, contract, or platform charge was initiated.

The prior turn made progress by creating records. This continuation made progress by discovering a competing implementation and withdrawing an unsuitable lead. No job, process, or payment is currently in a verified wait state. Outreach permission and the real payment link are still pending; elapsed time does not grant either.

Continue looking for explicit cash-funded, unassigned work that can be tested with available resources. Do not duplicate completed submissions merely to increase activity.

## Payment and participation gates — follow-up

Read the remaining Expensify contribution guide and its [AI Etiquette policy](https://github.com/Expensify/App/blob/main/contributingGuides/AI_ETIQUETTE.md). The policy calls for human ownership, understanding, and review of AI-assisted submissions. Fully autonomous submission cannot be represented as meeting that expectation. A verified Upwork profile alone would not resolve this requirement. The guide also requires a CLA, signed commits, accepted proposals, and platform testing; owner participation is necessary for legal acceptance.

The small banner-removal issue [#99593](https://github.com/Expensify/App/issues/99593) already has multiple detailed proposals. Do not invest in a duplicate implementation. Other least-commented Help Wanted results include bank-reconciliation work, iOS camera failures and macOS UI behavior; no suitable accepted, reproducible paid scope has been established for this experiment.

The user has been asked whether a verified Upwork profile exists. No answer or payment link has been received in the conversation as of this audit. No client communication authorization beyond the original drafting/payment-link instructions has arrived. The original tscircuit draft remains withdrawn.

The same missing outreach authorization and unestablished payment route have persisted across the initial goal turn and two continuations. No live submitted job, running implementation, accepted contract, or expected payment exists to poll. Resume revenue-seeking contact after user authorization and a usable payment route are supplied; do not simulate progress by repeatedly searching the same exhausted leads or manufacturing unpaid deliverables.

## Resumed with explicit authorization — 2026-09-12

The user supplied the payment destination privately and explicitly authorized targeted legitimate paid-work proposals and payment-eligibility inquiries. This supersedes the earlier missing-authorization/payment-link blocker. Keep the destination out of this repository; do not access Payoneer. Platform eligibility remains a separate question. Count only user-confirmed receipts.

Sent two targeted messages:

1. [tscircuit eligibility inquiry](https://github.com/tscircuit/contribution-tracker/issues/358#issuecomment-5638988458): asks whether AI-performed work without separate human code review qualifies and whether Payoneer is supported. No task assignment requested.
2. [Omi PowerShell examples proposal](https://github.com/BasedHardware/omi/issues/13513): proposes $25 after acceptance and merge for a selectable read-only PowerShell example script, native JSON processing, exit-status handling, offline regression tests and an index link. AI workflow and Payoneer eligibility explicitly need confirmation. The posted issue was returned successfully with its full body and source URL.

Omi scope estimate: 2–4 hours, low/medium difficulty, high technical feasibility for the offline scope on the current Windows host. Acceptance and payment probability remain unknown. Upfront cost $0. The current examples index lists a Bash script and no PowerShell script; exact-filename issue/PR search returned no `shell_examples.ps1` match. Broader related work may exist; recheck before implementation. The proposed Bengali guide was skipped because #13480 already covers it.

Next: inspect replies on these specific threads on a later work pass, without repeated bumps. Start substantial implementation only after the relevant paid scope and payment route are approved. Neither inquiry is an invoice or confirmed receivable; both are pending external responses, not a running process.

## Current policy: two opportunities and two-hour checks

This supersedes previous search/blocked instructions. JOB-002 (tscircuit) and JOB-003 (Omi) are WAITING_FOR_REPLY. Keep at most two active/pending opportunities. Check incoming replies every two hours and process actionable responses autonomously. Do not resend either inquiry or send periodic bumps. If unanswered, wait another two hours; the revenue goal is neither blocked nor completed by silence. Search for one replacement only if one opportunity becomes invalid or a reasonable period without response makes it no longer viable, considering project activity rather than a single two-hour interval.

Before this policy change, one eligibility-only email was sent to the official Tarsnap contact, asking about AI contributions and cash payout options. It is INACTIVE under the two-opportunity limit, with no agreed work or fee; do not send duplicate outreach or pursue it while both active slots remain occupied. No implementation or payment claim was made.

Confirmed revenue remains $0/$200 and spending $0. Only manual user confirmation can change confirmed revenue. The private Payoneer link remains outside the public repository.
