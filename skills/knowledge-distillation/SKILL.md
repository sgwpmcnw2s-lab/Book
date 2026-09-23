---
name: knowledge-distillation
description: Transform books, notes, articles, meetings, or research into reusable decision rules and action systems. Use when the user asks to distill, extract transferable insights, build a knowledge base, or turn information into an AI-ready template; do not use for a simple summary or verbatim transcription.
---

# Knowledge Distillation

Treat distillation as a conversion from information into usable cognitive assets. The result must help someone make a decision, act in a new context, or hand the method to another person or AI.

## Core distinction

- A summary answers: “What did it say?”
- A distillation answers: “Why does it work, when does it apply, what should I do, and how will I know?”

Do not call excerpts, polished quotations, or compressed paraphrases a completed distillation.

## Working method

1. Preserve source fidelity. Separate directly supported facts from interpretation, inference, and unknowns. Retain source locations for consequential claims.
2. Identify the material’s central claim, then map the important phenomenon, causal logic, variables, and assumptions.
3. Convert the logic into conditional rules: use the form “when [conditions/signals], prefer [judgment/action], unless [boundary].”
4. Produce a small action set that is specific enough to try, with an observable verification method.
5. Test transferability: apply the rule to one new scenario not explicitly covered by the source. If it cannot guide a new decision, revise the model rather than expanding the summary.

## Evidence discipline

When current or externally checkable claims matter, search for primary, academic, government, publisher, or author sources before writing a verified conclusion.

- Label source identity, author opinion, independently supported fact, and your own inference separately.
- Use “source verified, method unverified” when a reliable source establishes what an author or book says but not that its method works generally.
- Do not convert a personal case, a famous speaker’s assertion, or a historical example into a universal causal rule.
- For finance, law, health, or other high-stakes decisions, provide educational experiments and risk boundaries rather than outcome promises or personalized advice.

## Required output

For substantial content, create these sections:

1. **One-sentence core proposition** — a falsifiable claim, not a slogan.
2. **Phenomenon and evidence** — what happened and what supports it.
3. **Logic and variables** — causal chain, key levers, and hidden assumptions.
4. **Judgment rules** — conditions, recommended response, and exceptions.
5. **Action plan** — next actions, owner if known, and timing if relevant.
6. **Boundaries and risks** — where the claim may fail or create harm.
7. **Validation and transfer** — what feedback would test it and one new use case.

Use the repository’s `99-模板/蒸馏模板.md` when authoring an Obsidian note.

For every new book or reading-list item, create its distillation with the template’s exact headings: phenomenon, logic, rules, actions, boundaries, validation, and transfer. Add external-source status in the phenomenon section; if verification is incomplete, explicitly mark it pending.

## Quality checks

Before delivery, check:

- Can a reader make at least one new decision without reopening the source?
- Is every rule tied to stated conditions rather than phrased as universal truth?
- Is there a concrete next action and a way to observe whether it worked?
- Are facts, interpretations, and unknowns visibly distinct?

If any answer is no, label the output as a draft or source summary rather than a finished distillation.
