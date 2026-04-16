# anaudr content intake

## Purpose

Before generating any carousel, the AI must collect the required input below.

It must not generate the carousel before these answers are clarified.

The goal is to:
- keep the content on-brand
- choose the correct structure
- choose the correct visual mode
- avoid random assumptions
- make the carousel faster to produce and easier to approve

## Mandatory rule

Before generating, the AI must ask the intake questions below.

If the user already answered some of them, the AI should not ask again.
It should only ask for the missing parts.

If something important is unclear, the AI must ask before generating.

## Intake questions

### 1. Topic
What is the carousel about?

The AI should identify:
- the main topic
- the specific angle
- the actual point being made

### 2. Carousel type
What kind of carousel is this?

Choose one primary type:
- legal explainer
- business / sales / marketing
- self-development
- psychology / relationships
- opinion / rant
- educational with examples
- framework / list / steps
- commentary on a trend / news / social topic

### 3. Goal
What is the purpose of this carousel?

Possible goals:
- educate
- provoke
- reframe
- sell an idea
- build authority
- create relatability
- generate comments
- generate shares
- generate saves
- lead into another content piece
- prepare people for an offer

### 4. Audience
Who is this for?

Clarify:
- who should read it
- what kind of person it is aimed at
- what they already know or don’t know
- what tone they can handle

### 5. Visual mode
Which visual mode fits best?

Choose one:
- dark mode
- pastel mode

The AI should suggest a mode based on topic, but confirm before generating if needed.

### 6. Typography direction
Which typography pairing should be used?

Choose one:
- Playfair Display + DM Sans
- Cormorant Garamond + Work Sans

If needed, the AI may recommend a pairing based on the topic.

### 7. Structure type
What structure should the carousel follow?

Examples:
- hook → explanation → examples → takeaway → CTA
- hook → myth vs reality → breakdown → takeaway → CTA
- hook → numbered list → examples → conclusion → CTA
- hook → problem → why it happens → solution → CTA
- hook → rant → proof → conclusion → CTA

### 8. Slide count
How many slides should it have?

Clarify:
- approximate number of slides
- whether it should be concise or more detailed

### 9. Text density
How text-heavy should it be?

Choose one:
- light
- medium
- dense

Clarify whether the priority is:
- speed of reading
- depth of explanation
- visual cleanliness
- heavy informational value

### 10. Tone intensity
How hard should the tone go?

Choose one:
- soft but sharp
- witty and clear
- sarcastic and strong
- brutal / provocative

### 11. Humor level
How much humor should it use?

Choose one:
- minimal
- moderate
- strong
- heavy satire

### 12. Proof / evidence needs
Does the carousel need:
- examples
- practical scenarios
- legal references
- statistics
- quotes
- studies
- real-life comparisons
- screenshots or source-based claims

### 13. Mandatory points
What must absolutely be included?

Examples:
- a phrase
- a legal nuance
- a number
- an example
- a CTA
- a specific argument
- a warning
- a disclaimer

### 14. Forbidden elements
What should be avoided in this carousel?

Examples:
- certain phrases
- too much sarcasm
- too much text
- dark mode
- overdesigned slides
- any sales tone
- any romantic tone
- too much jargon

### 15. Image / graphic direction
Should the carousel include:
- your portrait
- cutout photos
- screenshots
- diagrams
- objects
- meme references
- book covers
- symbolic visuals
- no images, mostly text-only design

### 16. Special components
Should the carousel use any of these?
- cards
- callout boxes
- arrows
- dashed dividers
- label chips
- numbered sections
- comparison layout
- timeline
- flow diagram
- big transparent emoji in the background
- highlighted text bars

### 17. Ending style
What kind of ending should it have?

Examples:
- mic-drop line
- question
- comment bait
- save/share prompt
- emotional close
- hard takeaway
- teaser for next content

### 18. CTA add-on
Should the final slide also include the branded engagement strip?

Add-on:
- `Nu uita să:`
- ❤️ love
- 📤 distribuie
- 🔁 reshare

Default answer:
- yes, unless the user says otherwise

## AI behavior after intake

After collecting the answers, the AI should do this in order:

1. summarize the chosen direction briefly
2. confirm any missing critical assumption
3. build the slide-by-slide structure
4. write the content
5. only then generate or format the HTML version

## Output rule

The AI should not jump directly into HTML before the content logic is clear.

It should first define:
- title / hook
- slide structure
- visual mode
- key highlighted phrases
- CTA direction

Then it can produce the final carousel output.

## Default assumptions if the user is brief

If the user gives very little information, the AI may make light default assumptions based on the anaudr system, but must still clarify anything that would strongly affect:
- tone
- visual mode
- structure
- legal accuracy
- CTA logic
