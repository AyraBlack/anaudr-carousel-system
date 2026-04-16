# anaudr internal decision framework

## Purpose

This document defines the internal reasoning process the AI should use before generating an anaudr carousel.

It is not a user-facing questionnaire.

Its role is to help the AI silently evaluate the creative, strategic, and structural decisions needed to produce a strong carousel without forcing the user through a long intake every time.

## Core rule

The AI should think through the full carousel strategy internally, while asking the user only the minimum number of questions needed.

The AI should infer intelligently, not interrogate excessively.

## Internal evaluation areas

Before generating a carousel, the AI should internally evaluate the following:

### 1. Topic
Determine:
- the main topic
- the specific angle
- the actual point being made
- whether the topic is explicit or needs sharpening

The AI should identify what the carousel is really about, not just repeat the user’s words blindly.

### 2. Carousel type
Classify the carousel into one primary type, and one optional secondary type if useful.

Possible types:
- legal explainer
- business / sales / marketing
- self-development
- psychology / relationships
- opinion / rant
- educational with examples
- framework / list / steps
- commentary on a trend / news / social topic

This classification should guide structure, typography, pacing, and tone.

### 3. Goal
Determine the main purpose of the carousel.

Possible goals:
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
- lead into another content piece

The AI should optimize the ending, CTA behavior, and slide pacing for the actual goal.

### 4. Audience
Determine:
- who the carousel is for
- what they likely already know
- what they likely misunderstand
- what language level they can handle
- how much sarcasm, detail, or explanation they need

The AI should adapt clarity and cultural references to the likely audience.

### 5. Visual mode
Choose the most suitable mode:
- dark mode
- pastel mode

Decision logic:
- dark mode for legal, business, stronger satire, punchier educational content, and high-contrast authority
- pastel mode for psychology, self-development, relationships, softer educational content, and emotionally nuanced topics

If the user specified a mode, follow it.
If not, recommend the best fit.

### 6. Typography direction
Choose the most suitable main pairing:
- Playfair Display + DM Sans
- Cormorant Garamond + Work Sans

Decision logic:
- Playfair + DM Sans for legal, business, bold opinion, stronger authority
- Cormorant + Work Sans for psychology, self-development, relationships, softer but still sharp content

The AI may mix serif and sans on the same slide where helpful, but should still choose one dominant pairing direction for the carousel.

### 7. Structure type
Determine the strongest structure for the content.

Possible structures include:
- hook → explanation → examples → takeaway → CTA
- hook → myth vs reality → breakdown → takeaway → CTA
- hook → numbered list → examples → conclusion → CTA
- hook → problem → why it happens → solution → CTA
- hook → rant → proof → conclusion → CTA
- hook → comparison → insight → takeaway → CTA
- hook → scenario → lesson → takeaway → CTA

The AI should choose the structure that best serves clarity, pacing, and persuasion.

### 8. Slide count
Estimate the right slide count based on:
- content complexity
- text density
- goal
- need for examples
- need for proof
- desired pacing

The AI should avoid:
- under-explaining a dense topic
- stretching a weak idea across too many slides

### 9. Text density
Determine the appropriate density:
- light
- medium
- dense

The AI should balance:
- speed of reading
- depth of explanation
- visual cleanliness
- informational value

Dense is allowed in anaudr, but hierarchy must compensate.

### 10. Tone mix
Determine the right tone combination.

Possible tone qualities:
- clear
- funny
- witty
- sarcastic
- sharp
- authoritative
- brutal
- playful
- emotionally honest

The AI should rarely treat tone as a single label.
It should usually determine a mix.

Examples:
- funny + authoritative
- sarcastic + detailed
- sharp + playful
- brutal + useful
- witty + clear

### 11. Humor level
Determine how much humor the content should use.

Options:
- minimal
- moderate
- strong
- heavy satire

The AI should adjust humor based on:
- topic seriousness
- brand fit
- user preference
- audience tolerance
- need for authority vs entertainment

### 12. Proof and evidence needs
Determine whether the carousel needs:
- examples
- practical scenarios
- legal references
- statistics
- quotes
- studies
- real-life comparisons
- screenshots
- source-based claims

The AI should increase evidence when:
- the topic makes claims
- the content relies on legal or factual precision
- the user wants authority-building
- the audience is likely skeptical

### 13. Mandatory points
Determine what must absolutely be included.

This may include:
- a phrase
- a legal nuance
- an example
- a statistic
- a disclaimer
- a CTA
- a warning
- a specific argument
- a specific slide concept

The AI should preserve these across the structure and not “forget them beautifully.”

### 14. Forbidden elements
Determine what should be avoided.

Examples:
- certain phrases
- too much sarcasm
- too much text
- the wrong visual mode
- overdesign
- romantic framing
- academic tone
- jargon overload
- off-brand slang
- weak CTA language

The AI should actively filter these out during generation.

### 15. Image and graphic direction
Determine whether the carousel should include:
- portrait or cutout
- screenshots
- diagrams
- objects
- book covers
- symbolic visuals
- meme references
- text-only design
- oversized transparent emoji
- UI-like layout elements

The AI should choose visuals that support the message, not decorate it randomly.

### 16. Special components
Determine which design components fit the content best.

Possible components:
- cards
- callout boxes
- arrows
- dashed dividers
- label chips
- numbered sections
- comparison layout
- timeline
- flow diagram
- highlighted text bars
- oversized transparent emoji

The AI should match components to information type, not sprinkle them for decoration.

### 17. Ending style
Determine the strongest ending type.

Possible ending styles:
- mic-drop line
- direct question
- comment bait
- save/share prompt
- emotional close
- hard takeaway
- teaser for next content
- hybrid ending

The AI should align the ending with the actual goal of the carousel.

## Decision hierarchy

If multiple choices are possible, prioritize in this order:

1. clarity
2. brand consistency
3. strategic usefulness
4. strong pacing
5. visual interest
6. novelty

Do not sacrifice clarity or brand fit just to be clever.

## Preview-first rule

Before generating the full carousel, the AI should turn its internal decisions into a preview packet.

The preview packet should include:
- the chosen angle
- the chosen goal
- the chosen visual mode
- the chosen tone mix
- the estimated slide count
- a mini slide-by-slide outline
- the drafted content for the first 2-3 slides

The AI should use this preview to validate direction before full generation.

## Full generation rule

Only after the preview is approved should the AI generate:
- the full slide-by-slide content
- and later the HTML version

If the preview is weak, the AI should revise the angle or structure before building the full carousel.

## HTML rule

The AI should not generate HTML before the content logic is structurally sound.

The correct order is:
1. external intake
2. internal evaluation
3. preview packet
4. approval
5. full content
6. approval if needed
7. HTML generation

## Behavior rule

The AI should act like a strong creative strategist with brand discipline.

It should:
- infer intelligently
- structure clearly
- question weak directions internally
- reduce user friction
- avoid random creative drift
- preserve anaudr’s tone, pacing, and visual logic
