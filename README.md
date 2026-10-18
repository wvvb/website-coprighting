# website-copyrighting

[![skills.sh](https://skills.sh/b/wvvb/website-coprighting)](https://skills.sh/wvvb/website-coprighting)

A reusable agent skill for auditing, rewriting, and implementing website copy. It starts from the visitor's problem and the product's mechanism, not from a feature list or a fixed page template.

The skill is a plain Markdown `SKILL.md` plus a relative `references/` directory: no build step, no package manager, no runtime dependency. Harnesses that support Agent Skills can install it through their documented skill mechanism. Any other agent harness can read `SKILL.md` and open the companion files next to it. Discovery paths differ between harnesses, so this repository does not claim automatic loading everywhere.

Naming note: there are three names, and they are not all spelled the same. The public GitHub repository is `wvvb/website-coprighting`. The local clone folder used in these instructions is `website-copyrighting`. The skill inside is named `website-copywriting`, which is also the invocation command. The public URL keeps the repository spelling: https://github.com/wvvb/website-coprighting

## Who this is for

People writing or reviewing copy for a homepage, landing page, product page, feature page, onboarding flow, headline, or CTA, and who want output that sounds specific and credible rather than generic.

A typical failure it fixes: "Open-source analytics for finance operations" describes the machinery and leaves the visitor to work out why it matters. The skill makes the copy answer the visitor's question first.

## What it does

The skill follows the scope of the request and works in three modes:

- **Audit**: reports 3 to 5 specific copy or hierarchy problems. Each one quotes the text, says what a visitor would miss, and recommends a targeted fix. It also names what already works.
- **Rewrite**: produces production-ready copy for the sections you ask for, in the site's existing voice and level of technical detail, and preserves confirmed facts.
- **Implement**: runs only when you ask to change the site itself. It edits the smallest relevant content and layout surfaces, and keeps routing, accessibility, functionality, and responsiveness intact.

It does not invent pain, urgency, statistics, testimonials, or features, and it does not claim a conversion improvement without measurement.

## What it is not

- Not an AI detector. It reviews structure, evidence, and clarity, and it never scores text for "AI-ness".
- Not a conversion formula. No page shape is required, and no rule carries a promise of a lift.
- Not a rewrite-everything pass. If the original is clearer, it stays.

## Files

```text
website-copyrighting/            # local clone folder
└── website-copywriting/          # the skill
    ├── SKILL.md                  # core instructions; the entry point for any harness
    └── references/
        └── evidence.md           # companion: grades, sources, limits
```

**Core:** `SKILL.md` holds the rules and the audit, rewrite, and implement workflows. A harness with Agent Skills support can load it when a request matches its description; in Pi, `/skill:website-copywriting` forces it.

**Companion:** `references/evidence.md` documents the review behind the skill: how each recommendation is classified, which sources were verified, and what remains unproven. You do not need it to use the skill. It answers the question "is this rule proven?", and it must stay next to `SKILL.md` because the skill refers to it for that.

Current reviewed version: 1.1.

## Install

Requirements: a compatible agent harness. The CLI route runs through `npx` and needs Node.js and npm; the manual clone route needs Git only. The skill itself has no build step and no runtime dependency.

### Primary: skills CLI

The `skills` CLI resolves this repository from GitHub by name. List what the repository contains without installing anything:

```bash
npx skills add wvvb/website-coprighting --list
```

Then install the skill:

```bash
npx skills add wvvb/website-coprighting --skill website-copywriting
```

`--skill website-copywriting` selects the repository's single skill; without it, the CLI asks you to pick one. If the CLI cannot infer your harness or install scope, it prompts for both: which supported agent (harness) to install into, and project-level versus global scope. Answer the prompts, or pass `-a <agent>` and `-g` up front. By default the CLI links the skill into the harness's skill directory; `--copy` copies files instead. `npx skills --help` lists the remaining options.

Loading follows the harness: select `website-copywriting` through the harness's documented skill mechanism, or let the harness match the skill's description to a request. The CLI installs only into the harnesses it supports, not every agent harness. For Pi, see the example below.

The skills CLI collects anonymous install telemetry, which feeds the skills.sh directory rankings. A public repository installed through the CLI can appear in the directory over time; inclusion and timing are not guaranteed, and this repository does not claim a directory listing.

### Alternative: clone and wire manually

1. Clone the repository to `~/Code/website-copyrighting`:

```bash
git clone https://github.com/wvvb/website-coprighting ~/Code/website-copyrighting
```

2. Make the skill available to your agent:

- Harnesses with Agent Skills support: install `website-copywriting/` through that harness's documented skill mechanism.
- Other agent harnesses: point the agent at `website-copywriting/SKILL.md`. It can read the file directly, and `references/evidence.md` sits beside it for evidence lookups.

Install locations and discovery rules differ by harness. This repository does not claim that every harness finds the skill automatically.

### Pi example

This is one concrete install path for the Pi harness; it is not a universal procedure.

Check whether Pi already has a skill at the destination:

```bash
ls -la ~/.pi/agent/skills/website-copywriting
```

If that path does not exist, create the parent directory and symlink the nested skill directory:

```bash
mkdir -p ~/.pi/agent/skills
ln -s ~/Code/website-copyrighting/website-copywriting ~/.pi/agent/skills/website-copywriting
```

If the destination already exists, do not overwrite it. Inspect it first, and move or remove it yourself only if you intend to replace it.

Reload Pi so it discovers the skill and registers the command:

```text
/reload
```

Starting a new Pi session has the same effect. Pi can also load the skill automatically when a request matches its description; `/skill:website-copywriting` forces it when you want to be sure.

## Use

Give the agent a real request. Two examples:

```text
Audit the hero and pricing copy at https://example.com. Report the 3 to 5 biggest problems, quote the text, and name what already works.
```

```text
Rewrite the headline and subhead in the current voice. Keep the product claims as they are.
```

In a harness with skill invocation, select `website-copywriting` first; in Pi, `/skill:website-copywriting` forces it for that request.

## Updating

Updating is a pull:

```bash
git -C ~/Code/website-copyrighting pull
```

If you installed through the Pi symlink example above, run `/reload` in an active Pi session after the pull, or restart Pi. If you copied the skill directory into another harness, replace that copy after pulling.

## Notes

- The local clone folder is `website-copyrighting`, the skill and its command are `website-copywriting`, and the GitHub repository is `wvvb/website-coprighting`. The three spellings are not identical; use each name exactly as written for its context.
- Keep `references/` with `SKILL.md`. Moving or deleting `references/evidence.md` breaks the evidence lookups the skill relies on.
