# The Gold Hat Manifesto

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-aa8142?style=flat-square" alt="MIT License" /></a>
  <a href="https://github.com/HermeticOrmus"><img src="https://img.shields.io/badge/org-HermeticOrmus-aa8142?style=flat-square" alt="HermeticOrmus" /></a>
  <img src="https://img.shields.io/badge/stance-empower%20over%20extract-aa8142?style=flat-square" alt="Empower over extract" />
</p>

**TL;DR:** When a design decision is unclear, choose the option that *empowers* the person using the tool — never dark patterns, surveillance, or addiction mechanics. This repo is the canonical statement of that constraint.

The one question every tool should be built to answer: does this empower or extract?

Software can hand control to the person using it, or quietly take control away. Most tools drift toward extraction because extraction is profitable: more time on screen, more data captured, more dependence. This is the stance that chooses the other direction on purpose, and keeps choosing it.

This repository is the canonical home of the Gold Hat principle. It is the operating constraint behind every public repository under [HermeticOrmus](https://github.com/HermeticOrmus).

## The principle

| Always | Never |
|---|---|
| Empower the person using the tool | Dark patterns |
| Teach while helping | Surveillance capitalism |
| Respect autonomy | Addiction mechanics |
| Build for the long term | Quick fixes that rot |
| Solve the root cause | Patch the symptom |

## Empower over extract

A tool empowers when the person leaves more capable than they arrived. It extracts when it makes them more dependent, more watched, or more stuck. When a design decision is unclear, this is the tiebreaker: pick the option that leaves the user more in control of their own work and their own data. When the honest answer is "extract", it does not ship.

## Teach while doing

Automation does not have to make people helpless. The goal is to make the discipline legible. A tool should name the pattern it encodes, so the person could do it by hand if they wanted to. Automation that hides how it works builds dependence. Automation that shows its reasoning builds skill.

## Own your data

State belongs on hardware the user controls. Local files they can read, edit, and delete beat a remote service that holds their content hostage. If a feature would need to ship your data somewhere to work, that is a reason to question the feature, not to build the pipe.

## Build what lasts

Prefer the durable fix over the fast one, the simple design over the clever one. Code a person can still understand a year from now is worth more than code that was quick to write today. Root causes over symptoms.

## Why this exists

Most software is built to extract value: time, attention, data, money. Some is built to empower: it teaches, respects autonomy, builds long-term value for the user, solves root causes rather than patching symptoms.

This is a stance, not a claim of perfection. Not every commit will live up to it. It is the bar the work holds itself to, and the standard anyone is invited to hold it to. If you see something that violates the principle, say so.

## Lineage

The Gold Hat principle comes from Diego Bodart's (HermeticOrmus) operating identity. It is the spine of every public repository under that name.

The phrase reframes the old security idiom: where black hats break in and white hats merely avoid harm, gold hats build things that actively empower the people who use them. Not just "do no harm" but "leave them better off".

## Adopt it

The principle is free to take. To adopt it in your own project:

1. Drop a `GOLD_HAT.md` in your repository (many HermeticOrmus repos already include one — copy that shape if useful).
2. State the tiebreaker in your own words: when a decision is unclear, choose the option that empowers the user.
3. Link back here if you want a shared reference: `https://github.com/HermeticOrmus/gold-hat-manifesto`.
4. Optional: add GitHub topic `gold-hat` so others can find aligned work.

You do not need permission and you do not owe credit, though a link is welcome. The point is not attribution. The point is more software that empowers.

### Short copy-paste blurb

> This project follows the [Gold Hat](https://github.com/HermeticOrmus/gold-hat-manifesto) principle: empower over extract. No dark patterns, no surveillance capitalism, no addiction mechanics.

## Where it shows up

Public work under HermeticOrmus that carries this constraint includes (non-exhaustive):

- [LibreUIUX-Claude-Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) — UI/UX system for Claude Code
- [LibreEmbed-Claude-Code](https://github.com/HermeticOrmus/LibreEmbed-Claude-Code) — embedded / firmware plugins
- [LibreGameDev-Claude-Code](https://github.com/HermeticOrmus/LibreGameDev-Claude-Code) — game-dev plugins
- [grok-build-reality-os](https://github.com/HermeticOrmus/grok-build-reality-os) — Grok Build doctrine + guides
- [invoice-forge](https://github.com/HermeticOrmus/invoice-forge) — self-hosted invoicing (no SaaS lock-in)

## License

Released under [MIT](LICENSE) so the text is free to copy, adapt, and embed. The Gold Hat principle is the constraint on what gets built; the license is the constraint on how the words can be used. Both are open by design.

Build what elevates. Reject what degrades. Teach what empowers.
