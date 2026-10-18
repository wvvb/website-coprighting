# website-copyrighting

A Pi skill for auditing, rewriting, and implementing website copy. It starts from the visitor's problem and the product's mechanism, not from a feature list or a fixed page template.

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
    ├── SKILL.md                  # core instructions, loaded by Pi when relevant
    └── references/
        └── evidence.md           # companion: grades, sources, limits
```

**Core:** `SKILL.md` holds the rules and the audit, rewrite, and implement workflows. This is what Pi loads, and what `/skill:website-copywriting` forces.

**Companion:** `references/evidence.md` documents the review behind the skill: how each recommendation is classified, which sources were verified, and what remains unproven. You do not need it to use the skill. It answers the question "is this rule proven?", and it must stay next to `SKILL.md` because the skill refers to it for that.

Current reviewed version: 1.1.

## Install

Requirements: Git and a working Pi installation. There are no other dependencies to install, no package manager step, and no build.

1. Clone the repository to `~/Code/website-copyrighting`:

```bash
git clone https://github.com/wvvb/website-coprighting ~/Code/website-copyrighting
```

2. Check whether Pi already has a skill at the destination:

```bash
ls -la ~/.pi/agent/skills/website-copywriting
```

If that path does not exist, create the parent directory and symlink the nested skill directory:

```bash
mkdir -p ~/.pi/agent/skills
ln -s ~/Code/website-copyrighting/website-copywriting ~/.pi/agent/skills/website-copywriting
```

If the destination already exists, do not overwrite it. Inspect it first, and move or remove it yourself only if you intend to replace it.

3. Reload Pi so it discovers the skill and registers the command:

```text
/reload
```

Starting a new Pi session has the same effect.

4. Invoke the skill with a real request:

```text
/skill:website-copywriting Audit the hero and pricing copy at https://example.com, then rewrite the headline and subhead in the current voice. Keep the product claims as they are.
```

Pi can also load the skill automatically when a request matches its description. The `/skill:` command forces it when you want to be sure.

## Updating

The symlink points into the clone, so updating is a pull plus a reload:

```bash
git -C ~/Code/website-copyrighting pull
```

Run `/reload` inside an active Pi session after the pull, or restart Pi.

## Notes

- The local clone folder is `website-copyrighting`, the skill and its command are `website-copywriting`, and the GitHub repository is `wvvb/website-coprighting`. The three spellings are not identical; use each name exactly as written for its context.
- Keep `references/` with `SKILL.md`. Moving or deleting `references/evidence.md` breaks the evidence lookups the skill relies on.
