---
name: website-copywriting
description: "Use when writing, rewriting, reviewing, or optimizing copy for a website, landing page, homepage, hero section, product page, feature page, onboarding flow, headline, or CTA. Clarify who the site is for, express the visitor's real problem or desired outcome, explain how the product solves it, and make the writing sound natural, specific, appealing, and credible rather than generic or AI-generated. Also use for website messaging, positioning, and copy audits."
---

# Website Copywriting

A website should make the right person recognize their situation, understand what the product does, and know what to do next.

**Principle:** Write from the visitor's reality outward, not from the product's feature list inward. The copy must sound like a person who understands the work, not like a marketer explaining how marketing works.

This is a writing and information-design skill, not an AI detector and not a rigid conversion formula. Do not optimize for sounding "human" at the expense of truth, accessibility, or precision.

## Evidence labels

**Version 1.1.** Labels appear only on effectiveness claims: statements that something improves recognition, comprehension, trust, or conversion. Obligations and workflow steps are not graded.

- `[E]` verified direct evidence: peer-reviewed study or documented test measuring the stated effect, with effect size and limits.
- `[P]` plausible practice: useful without direct measured evidence for this audience.
- `[S]` editorial style preference. Style items are graded in `references/evidence.md`; they are not tagged inline in this skill.

No rule in this skill is `[E]` for landing-page conversion. Treat conversion advice as a hypothesis to test on the actual site, and never promise a lift without measurement. Unlabeled effectiveness claims here are advisory practice at `[P]`; obligations and workflow steps are ungraded. The complete per-item classification, sources, and candidate experiments are in `references/evidence.md`.

## Non-negotiable rules

1. **Lead with relevance.** Name a specific problem, task, or outcome the intended visitor recognizes. Get to the product quickly enough that the visitor understands what is being offered. `[P]`
2. **Explain the causal connection.** Show what the product actually does to help. Do not replace mechanisms with promises. `[P]`
3. **Sound natural.** Prefer everyday language, specific nouns, and ordinary verbs. Maintain technical accuracy for technical audiences.
4. **Do not use em dashes or en dashes in proposed website copy.** Replace them with a period, comma, colon, or a natural rewrite. Preserve original punctuation when quoting source material. If the user explicitly requests a different style, follow it.
5. **No manufactured emotions.** Do not invent pain, urgency, fear, statistics, social proof, results, or features.
6. **No compulsory template.** Do not give every website the same Problem / Agitation / Solution / Features / Testimonials / CTA sequence. Choose sections based on what visitors need to decide.
7. **Do not rewrite merely to rewrite.** If the original is clearer, keep it. Make the smallest change that improves comprehension.

## Decide what the visitor needs to understand

Before editing, inspect the material the user provides: live page, screenshot, current copy, brief, or source code. Determine:

- **Audience:** Who needs this? Use a recognizable role or situation rather than "everyone."
- **Trigger:** What event makes them look for help right now?
- **Job:** What are they trying to accomplish?
- **Obstacle:** Why does the current approach fail or take too much effort?
- **Cost:** What does the obstacle actually mean for them? Lost time, unanswered questions, confusion, risk, or money. Only include consequences supported by context.
- **Desired change:** What would make their next hour, day, or workflow better?
- **Product mechanism:** How does the product cause that change, in concrete terms?
- **Evidence:** What is demonstrated, documented, or verified?
- **Action:** What can they actually click, try, request, or read next?

Keep a clean distinction between facts and assumptions. If details are missing, use conservative language and label material assumptions in your explanation to the user. Do not make up specific customers or workflows.

### Build an internal problem model

Use this as a reasoning aid, never as text to publish:

`Someone in [real situation] is trying to [job], but [obstacle]. They want [outcome]. The product helps by [specific mechanism].`

Then distill it to a recognizable moment. The moment is more important than an abstract category.

- Abstract: "Finance teams need streamlined reconciliation workflows."
- Concrete: "The payout total and your transaction records don't match."
- Abstract: "Improve observability across distributed deployments."
- Concrete: "A deploy failed. You're searching three services to find the error."

A good headline can begin with the problem **or** with the desired outcome. Choose what most quickly tells the intended visitor, "This is for me." A problem-first headline is not automatically best if the audience already knows exactly what they want.

## Compose the message

Think through these beats internally. Do not print them as six identical website sections.

1. **Recognition:** An actual situation the visitor has experienced or can imagine.
2. **Significance:** What remains unresolved, difficult, expensive, or uncertain. One specific consequence is usually enough.
3. **Relief:** What becomes possible or simpler.
4. **Mechanism:** How the product gets the visitor there.
5. **Believability:** A real example, demo, capability, limitation, or source that earns trust.
6. **Next action:** A CTA whose destination fulfills its promise.

The first screen should usually deliver recognition, the solution, and a credible mechanism without requiring the visitor to scroll. Do not spend half a page dramatizing a problem the visitor already understands.

### Write the hero

- **Headline:** One clear thought about the visitor's job, problem, or desired outcome. Specific beats clever.
- **Support:** Name who it helps and describe how it works in one or two natural sentences. Remove any words that don't change the reader's understanding.
- **CTA:** A real action such as "See an example," "Read the docs," "Try the demo," or "Talk to the maintainer," only if that action exists.
- **Visual:** If one is present or requested, prefer a real workflow, interface state, or before-and-after data example over abstract decorative metaphors.

The headline and support should do different jobs. Don't say the same promise three times in different words.

### Explain the solution as a cause, not a slogan

For each important feature, reason through:

`What it does -> what changes for the visitor -> why that matters -> what backs up the claim.`

Example:

- Capability: Run generated SQL against Parquet, JSON, and CSV on the customer's infrastructure.
- What changes: The customer can investigate those files without sending their contents to a hosted analytics provider.
- Meaning: Their data stays within the infrastructure they operate.
- Scope: This does not prove the entire system has no security risks.

Use the most relevant part of this chain in the hero. Put the rest in a demo, workflow section, FAQ, or documentation as needed.

## Make the copy feel written by a person

Human-sounding copy is often more specific, less symmetrical, and less eager to explain itself. It feels edited, not generated in one pass.

### Favor

- A concrete situation instead of a category label.
- Familiar wording instead of conceptual jargon.
- Details that only make sense for this audience and product.
- Direct descriptions instead of hollow excitement.
- Different sentence rhythms when they help the reader follow an idea.
- A useful example that clarifies the claim.
- Honest limits, practical tradeoffs, and precise technical terms when those build trust.
- Natural transitions that follow the actual idea, not prefabricated connecting phrases.

### Remove or rewrite

- **Marketing filler:** "Unlock," "supercharge," "seamless," "cutting-edge," "game-changing," "next-generation," "revolutionize," "empower," and similar terms when they replace meaning.
- **Fake contrasts:** "It's not just X. It's Y." "Stop doing X. Start doing Y." "The future of X is here." Only use contrast when it explains an actual difference, in normal language.
- **Announced structure:** "In this section, we'll explore..." "Let's dive in." "Here's why this matters." Don't tell visitors you're about to explain something; explain it.
- **Repetitive restatement:** A headline, subtitle, three feature cards, and closing paragraph that all make the same claim.
- **Perfectly symmetrical sections:** Three cards with identical grammatical patterns, identical word counts, and a tidy summary just to complete the layout.
- **Overexplained meaning:** "This empowers businesses to take control of their success." If the consequence is obvious, stop writing.
- **Empty emotional language:** "Say goodbye to headaches" or "Never worry again" without a concrete reason.
- **Forced conversational tricks:** Repeated rhetorical questions, fake anecdotes, forced humor, excessive contractions, and artificial vulnerability.
- **Syntactic polish that sounds unnatural:** Dense noun phrases, strings of adjectives, and punctuation doing the work of clear sentences.

**Do not make a word blacklist your editing strategy.** A word can be appropriate in the right context. The punctuation requirement above is a project style rule; the deeper task is to fix thought, structure, and evidence. A copywriter who merely removes dashes and replaces "leverage" with "use" has not solved the problem.

### Edit at two levels

**Structural pass:**

- Is the reader's actual problem visible, or is the page talking about itself?
- Does each section teach something new or remove a real objection?
- Does the product appear before the visitor loses interest?
- Is the argument linear only because the model defaulted to a template?
- Are there unnecessary summaries, repetitive stage labels, or exaggerated old-versus-new narratives?
- Does the content follow how this particular visitor decides, rather than a generic sales funnel?

**Sentence pass:**

- Would a knowledgeable person actually say this sentence to another person?
- Is there a more specific noun or verb?
- Can the sentence be cut without removing a fact?
- Is the sentence trying to sound impressive instead of explaining something?
- Are the facts accurate and the benefits supportable?
- Are there any em dashes or en dashes in the proposed copy? Remove them.

Read the result as a visitor, not as a writer. If it sounds like a rehearsed pitch, simplify the thinking rather than adding more "humanizing" tricks.

## Use psychology responsibly

Use psychologically useful principles as diagnostic lenses, not excuses to manipulate people. Each principle below is `[P]`.

- **Recognition:** People engage when they can identify the situation being described. `[P]`
- **Cognitive ease:** Concrete language and a coherent path reduce effort. `[P]`
- **Information scent:** Headings and CTAs should accurately predict what's next. `[P]`
- **Control:** People want to know what they can inspect, change, keep, or undo. `[P]`
- **Trust:** Evidence, actual mechanisms, and acknowledged limits can be more useful than grand claims. `[P]`
- **Motivation:** The copy should connect to something the visitor wants to achieve, not invent insecurity or pressure. `[P]`

Avoid fake scarcity, social proof, invented cost savings, unsupported performance comparisons, manipulative defaults, or implied guarantees.

## Page architecture is situational

Do not produce the same landing page for a developer CLI, a finance operations product, and a consumer utility.

**For expert or developer audiences:** Usually lead with the practical task or technical outcome. Show a command, interface, example, architecture detail, or documentation link early. Avoid over-explaining a familiar problem.

**For operational buyers:** Lead with a recognizable incident or responsibility. Explain what they can investigate, prevent, or complete, then show the workflow and constraints.

**For unfamiliar categories:** Define the product early, anchor it in a known situation, and show how someone would actually use it. Novelty alone is not a value proposition.

**For a single-feature or already-clear page:** Make a precise change. Don't bolt on a long problem story.

Every section must earn its place by answering a real question or objection. If it doesn't, remove it.

## Example: Queryance

### Weak, feature-first version

> Open-source analytics for finance operations. Convert natural language into SQL and execute it on Parquet, JSON, and CSV files on your infrastructure.

This describes the machinery first. It makes visitors work out the reason to care.

### Human Problem version

> **Find out why your payout numbers don't match.**
>
> Queryance helps SaaS finance teams investigate differences between their records. Ask a question, review the SQL, and run it against Parquet, JSON, or CSV files on your own infrastructure.
>
> **CTA:** Talk to the maintainer

The first sentence names an actual job. The second explains who the product is for and how it works. The CTA is appropriate only if a way to contact the maintainer actually exists.

### A version that tries too hard

> **Still drowning in financial chaos?**
>
> Stop wasting time on outdated spreadsheets. Unlock effortless reconciliation with the next generation of intelligent financial operations.

This invents emotion, leans on industry cliches, and never explains the mechanism. It is shorter than the good version but less informative.

These examples are starting points, not mandated patterns. If real customers use different language, favor their language after verifying what they mean.

## Execution modes

Follow the scope of the user's request.

### Audit

Provide the top 3 to 5 specific copy or hierarchy issues. Quote the relevant text, describe what a visitor would misunderstand or miss, and recommend targeted fixes. Identify what is already working. Don't claim conversion improvements without measurement.

### Rewrite

Provide production-ready copy for the requested sections, using the site's existing brand voice and level of technical detail. Preserve confirmed facts. Briefly explain important choices, especially when removing features from the hero or moving detail further down.

If showing alternatives, make them meaningfully different rather than merely swapping adjectives. Favor one primary direction.

### Implement

Only when asked to change the website itself: inspect the existing files and design system; change the smallest relevant content and layout surfaces; maintain routing, accessibility, functionality, and responsiveness; verify the modifications and report any verification gaps. Do not refactor unrelated components or introduce new infrastructure.

## Final checks before presenting copy

- Can the intended visitor recognize the task, problem, or outcome in a few seconds?
- Is it obvious what product is being offered and to whom?
- Does the text explain what actually happens, not just promise an outcome?
- Does each paragraph or section add new information?
- Is anything repetitive, formulaic, self-announcing, or strangely dramatic?
- Does the writing use believable everyday language for this audience?
- Are important technical details accurately preserved?
- Are all statistics, results, claims, and testimonials backed by evidence?
- Does every CTA correspond to a real next step?
- Does the copy avoid em dashes and en dashes?
- Is the final version simpler and more helpful than the original?
- Is any effectiveness claim presented as established fact rather than as `[P]` practice? Check `references/evidence.md` before repeating one.

If the draft passes only the sentence-level checks but still follows a generic pattern, return to the structural pass. The website should feel like it understands a real person doing real work.

## Evidence status and limits

**Version 1.1.** Every effectiveness claim in this skill is currently `[P]`; there are no `[E]` conversion rules. The punctuation restriction is a style decision, not an effectiveness claim. Two papers cited in earlier versions concern generated text, not conversion:

- **StoryScope: Investigating idiosyncrasies in AI fiction** (Russell et al., 2026), https://arxiv.org/abs/2604.03136, classifies human and AI fiction from narrative structure. It did not evaluate websites or conversion.
- **SlopShape: Identifying AI-Generated Commercial Web Content** (Madler, 2026 preprint), https://arxiv.org/abs/2609.15369, classifies structural features of B2B company blog posts. It did not evaluate landing pages or conversion.

They support reviewing structure instead of swapping words. They do not show that any rule here improves conversion. The punctuation restriction is an editorial preference. Validate messaging with real users, comprehension tests, or your own measured experiments. Source details, verification limits, and candidate experiments: `references/evidence.md`.
