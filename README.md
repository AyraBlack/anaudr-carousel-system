# anaudr carousel system

## What this repository is

This repository is the source of truth for the anaudr Instagram carousel system.

It stores the brand rules, carousel rules, examples, and intake process used to create consistent HTML carousels for Instagram.

The goal is simple:
- keep the anaudr brand visually and verbally consistent
- generate carousels faster
- avoid reinventing the style every time
- make it easier to work with AI tools like Qwen inside a defined system

## Main files

- `brand-book.md`  
  Defines the anaudr brand identity, including colors, fonts, tone of voice, typography, style, and visual behavior.

- `carousel-rules.md`  
  Defines how a carousel should be built, slide by slide, including structure, pacing, layout logic, and formatting constraints.

- `content-intake.md`  
  Defines the questions that must be asked before generating a carousel.

- `examples.md`  
  Stores examples of good carousel writing, hooks, structures, and brand-consistent references.

## How this system works

1. The brand rules are defined in `brand-book.md`.
2. The carousel rules are defined in `carousel-rules.md`.
3. Before generating anything, the AI must ask the questions from `content-intake.md`.
4. The AI then generates a carousel that follows the anaudr brand system.
5. Examples from `examples.md` are used as style references, not as templates to copy blindly.

## Core principle

Consistency first. Speed second. Chaos never.

If a choice has to be made, the system should prefer:
- clarity over decoration
- consistency over novelty
- brand fit over random creativity
- structure over AI improvisation

## Current goal

Build a repeatable system for creating Instagram carousels in HTML for the anaudr brand.

## Status

Work in progress. The system is being built step by step.

## Notes

This repository is for system files and brand logic.
It is not the final content archive.
It is the operating manual behind the content.
