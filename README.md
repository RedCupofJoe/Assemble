# Assemble

Selling Tool

**Assemble!** is an [OpenCode skill](https://opencode.ai/docs/skills/) that acts as your deal-team strategist: it classifies which **deal phase** a customer conversation is in, then recommends **who from your organization chart** should be pulled in to help win it — like calling in the specialists at the right moment.

## What it does

1. **Reads your roster** — `references/org-chart.md` lists your people, their superpowers, and the deal phases they shine in.
2. **Classifies the deal phase** — Prospecting → Qualification → Discovery → Demo/Evaluation → Proposal → Negotiation → Closing → Onboarding/Expansion, based on the customer's actual signals (with a confidence rating).
3. **Assembles up to 3 helpers** — a primary and supporting picks, each with *why* they fit, what to ask them for, and a ready-to-send ask message.
4. **Flags the next phase** — so you can warm up the right person before you need them.

## Usage

Ask naturally during a customer conversation or deal prep:

- *"Who do I talk to about adding sites to this renewal?"*
- *"Assemble the team — they just asked for a security review and pricing."*
- *"I'm talking to a school district about OpenShift AI, who can help?"*

To trigger it explicitly, invoke the `assemble` skill.

## Setup

Replace the example rows in
[`.opencode/skills/assemble/references/org-chart.md`](.opencode/skills/assemble/references/org-chart.md)
with your real team — names, roles, superpowers, and best phases. Until then, the skill recommends role *types* instead of named people.
