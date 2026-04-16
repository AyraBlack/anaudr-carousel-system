# anaudr content intake

## Purpose

This document defines the user-facing intake flow before generating an anaudr carousel.

Its job is to keep the process:
- fast
- clear
- low-friction
- strategic
- quality-first

The AI should ask only the minimum questions needed to generate a strong carousel.

This is **not** the place for deep strategy.  
That belongs in the internal decision framework.

---

## Core rule

Ask little.
Infer smartly.
Preview early.
Generate later.

The AI should behave like a strong creative partner, not like a government form.

---

## What belongs here

This file covers only:
- what the AI asks the user directly
- how short the intake should stay
- what the default quick intake looks like
- when extra questions are actually justified

Everything else should be handled silently by the AI.

---

## Default intake behavior

Before generating, the AI should usually ask **no more than 5 quick questions**.

If the user already gave enough direction, ask fewer.

Do not repeat obvious information.
Do not ask for things that can be inferred safely.

---

## Default quick intake

Use these as the main intake questions when needed:

1. What is this carousel about?
2. What is the goal?
3. Which theme should I use?
   - `DARK_THEME`
   - `COLOR_THEME`
   - `you choose`
4. What tone mix do you want?
5. Shorter and punchier or more detailed?

---

## Goal options

If helpful, goal can be framed as:
- educate
- provoke
- reframe
- build authority
- create relatability
- generate comments
- generate shares
- generate saves
- sell an idea
- prepare people for an offer

Do not force the user to choose from a list if their intent is already obvious.

---

## Tone options

If helpful, tone can be framed as:
- clear
- funny
- witty
- sarcastic
- sharp
- brutal
- authoritative
- playful
- or a mix

Do not treat tone like a bureaucratic checkbox if the user already made it obvious in how they speak.

---

## Optional follow-ups

Ask 1 to 3 extra follow-ups only if they materially affect the output.

Good optional follow-ups:
- any must-include phrase, argument, example, disclaimer, or source?
- any must-avoid element?
- do you want examples, proof, stats, screenshots, or legal references?
- should this be mostly text-driven or visually richer?
- is this part of a bigger content sequence or offer?

If the answer will not materially change the carousel, do not ask it.

---

## What the AI should infer silently

The AI should not ask the user to decide everything.

Silently infer when possible:
- the sharper angle
- carousel type
- likely audience
- structure
- slide count
- density
- proof needs
- typography direction
- best archetypes
- ending type
- visual rhythm

That thinking belongs in the internal decision framework, not here.

---

## Default assumptions

If the user gives a brief prompt, the AI should make smart defaults instead of asking unnecessary follow-ups.

Safe defaults:
- follow anaudr brand rules
- use the correct theme logic
- use `@anaudr`
- use slide numbers from slide 2 onward
- keep footer placement consistent across standard slides
- use serif + sans hierarchy where useful
- include branded CTA add-on on the final slide unless told otherwise
- propose the strongest structure based on topic and goal

---

## Preview-first rule

The AI must not jump straight into full generation.

After quick intake, it should provide a preview packet first.

The preview packet exists to validate direction early and avoid wasted effort.

---

## Preview packet

Before writing the full carousel, provide:
- the core angle in 1–2 lines
- the goal
- the selected theme
- the tone mix
- the estimated slide count
- a mini outline
- the first 2–3 slides in archetype-first preview format

Do not dump the full carousel before validating direction unless the user explicitly asks to skip preview.

---

## Approval rule

After the preview packet, wait for approval or corrections.

Only after preview approval should the AI:
1. write the full slide-by-slide content
2. wait for content approval if needed
3. generate the HTML

---

## Correct order

The correct order is:

1. intake
2. internal reasoning
3. preview packet
4. approval
5. full content draft
6. approval if needed
7. HTML generation

Do not skip to HTML unless the user explicitly chooses speed over preview.

---

## When to ask more questions

Ask more than the default intake only if one of these is unclear and important:

- the real angle
- the real goal
- the theme
- the tone balance
- the amount of detail
- the need for factual or legal precision
- a must-use source, screenshot, or example
- whether the carousel belongs to a bigger offer or sequence

If the issue is not important enough to change the carousel meaningfully, move forward.

---

## Quality rule

For anaudr, quality matters more than raw speed.

A fast wrong carousel is worse than a slightly slower strong one.

Optimize for:
- correct direction
- strong first slides
- less regeneration chaos
- stronger preview quality
- better visual logic
- better final output
