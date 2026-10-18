# Website Copywriting: evidence reference

Companion to `SKILL.md`. This file holds the full recommendation audit, source verification record, unverified research leads, and candidate experiments. It is reference material for the skill author and reviewer. It is not published copy, and it is not required reading to write or edit a page.

Version: 1.1 (2026-10-18).

**How to use this reference**

- When someone asks whether a rule is proven, or asks for a conversion justification, consult this file instead of asserting an effect.
- Do not quote grades, lead numbers, or this file's contents to an end user as evidence that copy will convert. `[P]` items are review heuristics.
- Never present an unverified lead as an established result.
- A claim can only move to `[E]` when the conditions in "Grade definitions" are met and the source fields below can be filled in.

## Grade definitions

Grades apply to **effectiveness claims**: statements that something improves recognition, comprehension, trust, belief, or conversion.

- `[E]` verified direct evidence: a peer-reviewed study or a documented A/B test that measures the stated effect, with reported effect size, sample or denominator, and stated limits, from a primary source that was verified during an audit. A paper or tool that performs well at a different task does not make a conversion claim `[E]`.
- `[P]` plausible practice: useful, defensible guidance without direct measured evidence for the stated effect in the relevant context.
- `[S]` editorial style preference: a house or project style decision that makes no effectiveness claim (for example, the punctuation restriction).

Non-empirical items are not graded. They carry a type instead:

- `N` normative: truthfulness, ethics, or client obligations. These are not hypotheses to be tested. Do not label "do not fabricate proof" as unproven effectiveness.
- `W` workflow/process: how to run an audit, rewrite, or implementation, or how to keep facts and assumptions separate.

## Provenance metadata

Each item can carry provenance as metadata, not as a fourth grade:

- `provenance: external` (default for this file)
- `provenance: internal` for the user's own tests or product data

No internal test data was supplied for this skill. If the user later provides documented test results, record the variant, metric, sample, period, result, and limits, then grade `[E]` with `provenance: internal`. Internal evidence is more applicable to the tested context than transferred external results, but it remains evidence for that context only, and it still needs the documented fields above.

## Inventory convention and baseline

- **Unit:** one canonical recommendation = one directive a writer acts on, at the level the skill presents it (numbered rule, bullet, or checklist line), deduplicated when the same directive appears in more than one section.
- **Aliases:** a later near-verbatim restatement is recorded as an alias of the canonical ID and is not counted again.
- **Baseline:** the original attached skill (v1.0) carried no evidence grades. The "before" classification below is retrospective and disclosed as such; it was produced by this audit, not by the original author.
- **Denominator:** the count of canonical (non-alias) items. Sub-items that only illustrate or specialize a canonical item are listed in the notes, not counted.
- **Not a quota:** a rising `[E]` count is not a goal. A shorter, more honest skill with fewer claims is a valid outcome.

## Audit: canonical recommendations

Section names refer to the v1.0 original, preserved in v1.1.

| ID | Recommendation | Type | Grade | Notes / aliases |
|---|---|---|---|---|
| R01 | Write from the visitor's reality outward, not feature-first | EC | `[P]` | stance; implies recognition effect |
| R02 | Do not trade truth, accessibility, or precision for sounding human | N | n/a | |
| R03 | Lead with relevance | EC | `[P]` | non-negotiable 1 |
| R04 | Explain the causal connection; mechanism over promises | EC | `[P]` | non-negotiable 2 |
| R05 | Sound natural: everyday language, specific nouns, ordinary verbs; keep technical accuracy | EC | `[P]` | specialized by R28, R30, R35-R43 |
| R06 | No em or en dashes in proposed copy; preserve quotes; follow an explicit user style request | S | `[S]` | editorial preference; user override preserved |
| R07 | No manufactured emotions, pain, urgency, fear, statistics, proof, results, or features | N | n/a | aliases: R13, R54 |
| R08 | No compulsory template; choose sections from decision needs | EC | `[P]` | alias: R17 |
| R09 | Do not rewrite merely to rewrite; smallest change that improves comprehension | EC | `[P]` | non-negotiable 7 |
| R10 | Inspect the provided material before editing | W | n/a | |
| R11 | Establish audience, trigger, job, obstacle, cost, desired change, mechanism, evidence, action | W | n/a | one analysis step, not nine rules |
| R12 | Separate facts from assumptions; conservative wording; label assumptions to the user | N | n/a | |
| R13 | Do not invent specific customers or workflows | alias | n/a | alias of R07 |
| R14 | Keep the problem model as a private reasoning aid | W | n/a | |
| R15 | Distill to a concrete recognized moment over an abstract category | EC | `[P]` | |
| R16 | Choose problem-first or outcome-first by speed of recognition; not automatically problem-first | EC | `[P]` | |
| R17 | Think through the message beats internally; do not print them as fixed sections | alias | n/a | alias of R08 |
| R18 | First screen delivers recognition, solution, and credible mechanism | EC | `[P]` | |
| R19 | Do not dramatize a problem the visitor already understands | EC | `[P]` | |
| R20 | Headline: one clear thought; specific beats clever | EC | `[P]` | |
| R21 | Support names who it helps and how it works; cut words that do not change understanding | EC | `[P]` | |
| R22 | Every CTA must correspond to a real, available action | N | n/a | |
| R23 | Prefer a real workflow, interface state, or data example over abstract metaphor | EC | `[P]` | |
| R24 | Headline and support do different jobs; do not restate the same promise | EC | `[P]` | alias: R38 |
| R25 | Explain features as a cause chain (does, changes, matters, support) | EC | `[P]` | |
| R26 | Use the most relevant chain part in the hero; place the rest later | EC | `[P]` | |
| R27 | Prefer concrete situations over category labels | EC | `[P]` | |
| R28 | Prefer familiar wording over conceptual jargon | EC | `[P]` | specializes R05 |
| R29 | Include details specific to this audience and product | EC | `[P]` | |
| R30 | Prefer direct description over hollow excitement | EC | `[P]` | specializes R05 |
| R31 | Vary sentence rhythm when it helps the reader | EC | `[P]` | |
| R32 | Use a clarifying example | EC | `[P]` | |
| R33 | Include honest limits, tradeoffs, and precise terms when they build trust | EC | `[P]` | |
| R34 | Use natural transitions that follow the actual idea | EC | `[P]` | |
| R35 | Remove marketing filler that replaces meaning | EC | `[P]` | |
| R36 | Avoid fake contrasts unless they explain a real difference | EC | `[P]` | |
| R37 | Remove announced structure ("in this section...") | EC | `[P]` | |
| R38 | Remove repetitive restatement across page elements | alias | n/a | alias of R24 |
| R39 | Avoid perfectly symmetrical sections | EC | `[P]` | |
| R40 | Remove overexplained meaning | EC | `[P]` | |
| R41 | Remove empty emotional language without a concrete reason | EC | `[P]` | distinct from R07: vacuity, not fabrication |
| R42 | Remove forced conversational tricks | EC | `[P]` | |
| R43 | Fix dense or unnatural syntactic polish | EC | `[P]` | |
| R44 | Do not use a word blacklist as the strategy; fix thought, structure, and evidence | W | n/a | |
| R45 | Run the structural pass checklist | W | n/a | restates R08, R15, R16, R18, R24, R59 |
| R46 | Run the sentence pass checklist | W | n/a | restates R03, R05, R06, R30, R33 |
| R47 | Read as a visitor; simplify the thinking instead of adding humanizing tricks | EC | `[P]` | |
| R48 | Recognition: people engage when they can identify the situation | EC | `[P]` | psychology lens |
| R49 | Cognitive ease: concrete language and a coherent path reduce effort | EC | `[P]` | psychology lens |
| R50 | Information scent: headings and CTAs should predict what is next | EC | `[P]` | psychology lens |
| R51 | Control: people want to know what they can inspect, change, keep, or undo | EC | `[P]` | psychology lens |
| R52 | Trust: evidence, mechanisms, and acknowledged limits can beat grand claims | EC | `[P]` | psychology lens |
| R53 | Motivation: connect to what the visitor wants; do not invent insecurity or pressure | EC | `[P]` | psychology lens |
| R54 | Avoid fake scarcity, invented savings, unsupported comparisons, manipulative defaults, implied guarantees | alias | n/a | alias of R07 |
| R55 | Expert or developer audiences: lead with the practical task; show concrete artifacts early | EC | `[P]` | |
| R56 | Operational buyers: lead with a recognizable incident; show workflow and constraints | EC | `[P]` | |
| R57 | Unfamiliar categories: define early and anchor in a known situation | EC | `[P]` | |
| R58 | Single-feature or already-clear page: precise change; no long problem story | EC | `[P]` | |
| R59 | Every section earns its place by answering a real question or objection | EC | `[P]` | |
| R60 | Examples are starting points; favor verified real customer language over the examples | N | n/a | |
| R61 | Audit mode: 3 to 5 specific issues, quote, explain the misunderstanding, targeted fixes, note what works. Across all modes: no unmeasured conversion claims | W | n/a | v1.1 expanded the no-unmeasured-conversion-claims constraint from audit mode to all modes |
| R62 | Rewrite mode: production-ready copy, existing voice and detail level, preserve facts, explain important choices, favor one direction | W | n/a | |
| R63 | Implement mode: smallest relevant change, preserve routing, accessibility, function, responsiveness; verify and report gaps; no unrelated refactors | W | n/a | |
| R64 | Run the final checks before presenting copy; fall back to the structural pass when only sentence-level checks pass | W | n/a | checklist lines map to R03-R06, R18-R24, R33, R59 |
| R65 | Validate messaging with real users, comprehension tests, or product data when available | W | n/a | the only actionable line in the original research section |

The original "Research basis and limits" section contained no other recommendations. Its two paper citations were context, not rules; they are recorded under "Verified sources" below.

### Counts

- Canonical (counted) items: 61. Alias rows: 4 (R13, R17, R38, R54).
- By type: effectiveness claims (EC) 44; normative (N) 5; workflow (W) 11; style (S) 1.
- Grades inside the EC subset: `[E]` 0, `[P]` 44, `[S]` 0.
- The style item R06 is `[S]`. The 16 normative and workflow items are ungraded by design.
- Expected totals: 44 + 5 + 11 + 1 = 61 counted items, plus 4 alias rows = 65 table rows.

## Before / after reconciliation

- **Before (v1.0):** 61 counted canonical items; no grades present; retrospectively classified as 44 EC (`[E]` 0, `[P]` 44), 1 S, 16 ungraded N/W.
- **After (v1.1):** the same 61 counted canonical items. No new effectiveness rules were added. One workflow item (R61) was widened from audit mode only to all modes: do not claim conversion improvements without measurement. The Evidence labels and Evidence status sections are metadata, not recommendations.
- **Honest result:** the proportion of `[E]` effectiveness claims did not rise; it remains 0 for conversion claims. The revision is structural: it labels what is unproven, records the sources and gaps, and limits claims. It is not new evidence of effectiveness.

## Verified sources

Verification pass: 2026-10-18, against the arXiv records and full-text HTML. Treat the following as reported by that pass.

### StoryScope: Investigating idiosyncrasies in AI fiction

- Link: https://arxiv.org/abs/2604.03136 (full text: https://arxiv.org/html/2604.03136)
- Authors as listed: Jenna Russell, Rishanth Rajendhran, Chau Minh Pham, Mohit Iyyer, John Wieting.
- Dates: submitted 3 Apr 2026; v6 revised 10 Aug 2026.
- Population and design: 10,272 prompts, one human story and five LLM stories per prompt (61,608 stories, roughly 5,000 words each); a 257-feature narrative model.
- Reported result: 93.2% macro-F1 and .959 AUPRC for human-versus-AI story classification. A 95% prompt-bootstrap CI of 2.09-3.54 points is reported for the gap between narrative-only and narrative-plus-style models.
- Missing or inconsistent: no CI reported for the standalone 93.2 score; test-set counts differ between section 3 (1,377 prompts / 8,262 stories) and Appendix D (1,384 prompts / 8,301 stories); the arXiv record lists no journal reference or peer-review status.
- Applicability: story-level classification of AI fiction. It does not evaluate website copy or conversion. It can motivate reviewing structure instead of swapping words, nothing more.

### SlopShape: Identifying AI-Generated Commercial Web Content

- Links: https://arxiv.org/abs/2609.15369 (full text: https://arxiv.org/html/2609.15369; code: https://github.com/pulse-energy-eu/slopshape)
- Author: Jochen Madler, affiliated with Sitefire.
- Dates: submitted 14 Sep 2026; v3 revised 28 Sep 2026.
- Population and design: 2,250 pre-ChatGPT B2B company blog posts from 268 domains compared with 11,250 AI mirrors from five models; 176 structural features; held-out companies.
- Reported result: 97.0% macro-F1; test data 290 prompts across 38 domains (1,740 posts); 95% bootstrap CIs of 95.5-98.2 (domain-cluster) and 95.7-98.1 (prompt); 1.000 AUPRC in the table; 10,000 bootstrap resamples.
- Missing or inconsistent: no p-value alongside the headline score; the arXiv record lists no peer-review status.
- Limits as reported: software-heavy and US-heavy corpus, limited rewording attacks. The author reports operating a commercial GEO product.
- Applicability: structural classification of generated B2B blog posts. It does not measure landing-page effectiveness or conversion.

Neither paper demonstrates that the punctuation restriction, a problem-first framework, or any other rule here improves conversions. Macro-F1 is a classification score, not a lift, and it carries no visitor denominator.

## Unverified research leads (quarantine)

These were supplied as German-language feedback leads. Exact-phrase and broader searches plus Crossref and OpenAlex lookups produced nothing usable; search endpoints were partly blocked or returned unrelated results. Not locating a source is not proof that it does not exist, and secondary reporting was not accepted as verification. For every lead, the source, population, design, sample, metric definition, uncertainty, significance, and review status remain unverified. Do not cite these numbers as facts, or as the basis for a default rule.

| ID | Lead as supplied | What is missing / why it cannot support a rule |
|---|---|---|
| L1 | Sentence length and conversion correlate at r = -0.62 across 12,000 copy samples | Source, sample unit, and CVR definition unknown; correlation, not a tested intervention; even if verified, it would not establish a "keep complex sentences under 30%" rule |
| L2 | CTA commitment matching, +28%, All About Learning Press test | Test documentation, control, outcome denominator, uncertainty |
| L3 | Risk reversal in the button, +29% | Test details; whether button placement caused the result |
| L4 | Benefit versus urgency ANOVA on an e-learning landing page | Study, groups, outcome, sample, ANOVA results; transferability to other industries |
| L5 | Jewelry-site social proof, +11% among 12,000 users | Source; meaning of "users"; design; whether testimonial proximity to a CTA was tested |
| L6 | Emotion beta = .35 and action beta = .29 | Source, model, standardization, sample, uncertainty; independent coefficients do not establish a combined or interaction effect, so no "emotion plus action beats emotion alone" conclusion can be drawn even if the coefficients are verified later |

If a primary source is found later, fill in the source fields, apply the grade definitions, and update this table. Until then these leads may justify only candidate experiments, never defaults.

## Candidate experiments (not rules)

Hypotheses worth testing on the actual site. None of these may be presented as an established tactic, and none may be turned into a mandatory rule. Each requires the user's own measurement before it is treated as effective.

1. **Shorter, less complex sentences.** Hypothesis only; no verified effect size, and no threshold such as "under 30% complex sentences". Measure comprehension or conversion on the page before claiming anything.
2. **Match CTA wording to the visitor's commitment level.** Untested locally; run as a controlled variant.
3. **Put a guarantee in the button text, if a guarantee exists.** Optional, not mandatory. The guarantee must be true, supportable, and honored. No verified effect.
4. **Place authentic testimonials near the CTA.** Optional. Only real, verifiable testimonials, with permission, no fabrication. No verified effect, and proximity is not established as the cause of any result.
5. **Benefit framing versus urgency framing.** Only truthful framing; no invented deadlines or scarcity. Untested locally.
6. **Emotion plus action wording together.** Do not infer an interaction from separate regression coefficients; candidate experiment only.

For each: define one primary metric, a control, a sample the user can actually measure, and a stopping rule; record provenance as internal; report the result with its limits, including null results.

## Open evidence gaps

For the following rules there is no verified direct landing-page conversion evidence in this audit. This is a limitation to state, not a weakness to hide. These are exactly the 44 effectiveness claims graded `[P]`, set-equal to the effectiveness-claim rows in the audit table above:

- R01, R03, R04, R05, R08, R09
- R15, R16, R18, R19, R20, R21, R23, R24, R25, R26, R27, R28, R29, R30, R31, R32, R33, R34, R35, R36, R37, R39, R40, R41, R42, R43, R47
- R48, R49, R50, R51, R52, R53
- R55, R56, R57, R58, R59

Style decisions (R06) and normative or workflow items are not listed here: they make no landing-page conversion claim, so they are not evidence gaps. The unverified external leads above would only close these gaps if a primary source passes the E criteria and applies to the relevant audience; transferred results from another offer or industry would remain weaker than the user's own measured tests.

## Verification method and limitations

- Checked: the two cited papers against their arXiv records and full-text HTML on 2026-10-18, including sample, metric, reported uncertainty, and stated limits.
- Checked: exact-phrase and broader searches plus Crossref and OpenAlex for the six feedback leads. No primary source was located.
- Not accepted as verification: secondary reporting, blog summaries, and a tool or paper's success at a different task.
- Not claimed: that the six leads do not exist, or that no landing-page conversion research exists. This audit records what it could verify, not an exhaustive review of the literature.
- No internal test data was supplied by the user for this skill.

## Changelog

- **v1.0** (original attachment): writing-first guidance; non-negotiable rules; effectiveness claims unlabeled; a research section citing StoryScope (93.2% macro-F1) and SlopShape (97.0% macro-F1) as motivation; no grades, no companion audit.
- **v1.1** (2026-10-18): evidence labels added only for effectiveness claims; evidence boundary added; both papers attributed with explicit non-conversion limits and classification scores removed from the core; research details and limits moved to this reference; retrospective audit added (61 counted items; 44 effectiveness claims, all `[P]`, `[E]` 0); the no-unmeasured-conversion-claims workflow constraint widened from audit mode to all modes; six leads quarantined as unverified; candidate experiments documented. No new effectiveness rules were added; `[E]` count unchanged at 0.
