---
name: Done Right Solutions LLC
description: Concrete work, done right. A calm, phone-first page in the logo's slate and brick red.
colors:
  brick-red: "#a92403"
  brick-red-deep: "#8e1d02"
  brick-red-on-dark: "#f2735a"
  slate: "#303945"
  slate-deep: "#1e252e"
  paper: "#f4f5f7"
  card: "#ffffff"
  field: "#e6e9ee"
  body-ink: "#2e3843"
  soft-ink: "#55606c"
  on-dark: "#f5f6f8"
  on-dark-soft: "#c8cfd8"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.2
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  field: "10px"
  row: "18px"
  tile: "20px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  list-gap: "10px"
  stack: "20px"
  head-to-content: "32px"
  band: "64px"
  band-wide: "96px"
components:
  button-primary:
    backgroundColor: "{colors.brick-red}"
    textColor: "{colors.card}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.brick-red-deep}"
    textColor: "{colors.card}"
  button-ghost:
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  service-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.slate-deep}"
    rounded: "{rounded.row}"
    padding: "12px 14px 12px 22px"
    height: "68px"
  feature-row:
    backgroundColor: "{colors.brick-red}"
    textColor: "{colors.card}"
    rounded: "{rounded.tile}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.slate-deep}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.slate-deep}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.slate-deep}"
    textColor: "{colors.card}"
  float-text:
    backgroundColor: "{colors.brick-red}"
    textColor: "{colors.card}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Done Right Solutions LLC

## Overview

**Creative North Star: "The Finished Slab"**

The page is built from the company's own logo: a white ground, the slate circle and the brick-red check. Everything is soft-cornered, borderless and flat, like a troweled floor; the only texture is a faint diagonal line on the deepest bands. Full-bleed bands alternate light and dark so each section reads as its own pour. Proof is the job itself, in real photographs, never illustration.

Density is low and phone-first: one column, large tap targets, one accent doing all the asking. The brick red appears only where the visitor is meant to act or where the eye should land, so its rarity carries the call to action.

**Key Characteristics:**
- Paper, slate and deep-slate bands; brick red as the single accent.
- One display face (Cal Sans) for headings, labels and buttons; system sans for reading.
- Soft radii (10 to 24px) and pills; no borders at rest, no decorative shadows.
- Real job photography under a slate overlay or in 4:5 tiles.
- Calm motion: one hero headline entrance, one 12px fade-up, nothing else.

## Colors

Cool slate neutrals from the logo's circle, warmed by one brick-red accent from its check.

### Primary
- **Brick Check Red** (brick-red): the one accent. Used as a fill with white text (about 7:1): primary buttons, the numbered step discs, the "more of our work" row, the floating text circle, hovered service-row arrows, text selection. Also legible as text or icon colour on light grounds (header phone icon, hover state on links, error text).
- **Fired Brick** (brick-red-deep): hover fill for primary buttons only.
- **Ember** (brick-red-on-dark): the accent lifted for dark grounds (about 5.5:1 on deep slate). Text and icons only: accent phrases in dark-band headings, stage numbers on photo tiles, the closing phone icon, footer link hover, focus rings on dark bands.

### Neutral
- **Paper** (paper): page ground and header. Never pure white, never black.
- **White Card** (card): service rows and the form card sitting on paper.
- **Field Grey** (field): input and chip fill on the white card; deliberately darker than paper so fields stay visible on white.
- **Slate Circle** (slate): mid dark band (closing band); also the focus/hover outline on light grounds.
- **Deep Slate** (slate-deep): hero ground, work band and footer; also heading ink and selected-chip fill on light.
- **Body Ink** (body-ink) and **Soft Ink** (soft-ink): running text and secondary text on light.
- **On Dark** (on-dark) and **On Dark Soft** (on-dark-soft): headings and running text on dark bands.
- Hairline `rgba(30,37,46,.12)` and tint `rgba(30,37,46,.06–.07)`: quiet arrow-circle and chip-like tints on light.

### Named Rules
**The One Check Rule.** Brick red is the only chromatic colour on the page. Nothing else gets hue; new emphasis comes from slate weight or white space.

**The Fill-Not-Ink Rule.** On light grounds brick red is a fill with white text. On dark grounds it never fills text; use Ember instead.

**The Two-Shade Rule.** Text in red on a dark band is always Ember (#f2735a); text in red on paper or white is Brick Check Red. Never swap them.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A friendly geometric display face at a single weight (400) does all the talking; the system body stays out of the way at a generous 1.7 line height.

### Hierarchy
- **Display** (400, clamp 42–84px, 1.02): the hero H1 only, white on the dark hero, last phrase in Ember.
- **Headline** (400, clamp 30–48px, 1.08, balanced wrap): section headings. On dark bands the last phrase may take Ember.
- **Title** (400, 18–22px, 1.1–1.2): service rows (21px), step titles (20px), photo-tile captions (18px phone, 22px desktop), the feature row (19–22px).
- **Label** (400, 17px, 1.2, Cal Sans): form labels, legends and buttons (buttons at 18px).
- **Lede** (400, clamp 17–19px, 1.7, max 40ch): the one line under a heading, in Soft Ink.
- **Body** (400, 16px, 1.7): running text; inputs are 16px so iOS never zooms. Small notes and errors at 15px.

### Named Rules
**The One Weight Rule.** Cal Sans is only ever used at 400. Hierarchy comes from size, not weight.

**The Display-Speaks Rule.** Anything the visitor taps or reads as a heading (buttons, rows, labels, phone numbers) is set in Cal Sans; paragraphs are system sans.

## Layout

A single centred column (max 1160px) with a 20px gutter on phones and 40px from 760px. Bands pad 64px vertically on phones and 96px from 760px. Section heads sit 32px above their content; lists and grids gap 10–16px; form fields stack at 20px.

Breakpoints: 760px (two-column service rows, buttons side by side at min 240px, wider gutters) and 1024px (hero splits 1.25fr / 1fr with the photo as a card, work tiles go to four across, the form section becomes text-left and a sticky head beside the form, the closing band puts the big phone number beside the name). A 374–380px floor tightens the header and chips for the smallest phones.

Bands run in order paper header, deep hero, paper, deep (textured), paper, slate, deep footer (textured), so no two adjacent sections share a ground.

**The Phone-First Rule.** Every layout is designed at 390px first; desktop only adds columns. Tap targets are 44px or larger everywhere.

## Elevation & Depth

Flat by default. Depth comes from tonal bands and white cards on paper, not shadows. Two shadows exist and both are functional: the floating text circle (`0 10px 28px rgba(20,24,30,.32)`) so it reads above content, and the desktop hero photo card (`0 24px 60px rgba(0,0,0,.28)`) lifting it off the textured band. Photos sit under slate gradients (an 84–88% overlay in the hero, a bottom fade to 90% on tiles) so white text holds contrast.

**The Flat Band Rule.** Rows, cards, fields and buttons carry no shadow at rest or on hover. A shadow means "this floats above the page", nothing else.

## Shapes

Soft and borderless: fields at 10px, service rows at 18px, photo tiles and the feature row at 20px (tiles 24px on desktop), cards at 24px, buttons, chips and the float at full pill or circle. Interactive circles (arrows, step discs) are 44px. Borders exist only as 2px transparent slots that turn slate on hover or focus, plus the ghost button's white outline. Photos are always `object-fit: cover`, 4:5 in tiles.

## Components

### Buttons
- **Shape:** full pill (999px), 56px tall, 26px side padding, Cal Sans 18px, optional 20px line icon.
- **Primary:** Brick Check Red fill, white text. One per view as the main ask.
- **Hover / Focus:** hover darkens to Fired Brick (pointer devices only); focus is a 3px slate outline at 3px offset (Ember on dark bands); press scales to .98.
- **Ghost:** on the dark hero only, a 25% slate wash with a 2px white outline at 75%; hover goes full white outline over a 10% white wash.
- **Copy (utility):** 48px pill in Field Grey with ink text, for fallbacks inside the form.

### Chips
- **Style:** Field Grey pill, 48px tall, body text, used as radio choices for the job type.
- **State:** selected fills Deep Slate with white text; hover and focus show a 3px slate outline at 2px offset (an outline, never a border, so it stays visible on the dark selected fill).

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** white on paper.
- **Shadow Strategy:** none (see Elevation).
- **Border:** none.
- **Internal Padding:** clamp(20px, 5vw, 32px).

### Inputs / Fields
- **Style:** Field Grey fill, no visible border, 10px radius, 52px min height (textarea 110px), brick-red caret, Cal Sans label above, optional hint in small Soft Ink.
- **Focus:** the 2px border turns slate; hover does the same on pointer devices.
- **Error:** border and a plain-sentence message in brick red, kept even while focused.

### Navigation
- **Header:** paper, logo mark plus "Done Right / Solutions LLC" lockup left, tap-to-call number right in Cal Sans with a red phone icon; hover turns the number red. No menu.
- **Footer:** deep slate with texture, name line and Facebook link; links go Ember on hover.

### Service Row (signature)
A white 68px row on paper with a Cal Sans title and a 44px arrow circle at the right. Only the arrow responds: on hover or focus it fills brick red with a white arrow; the row itself never changes. Tapping pre-selects the matching chip in the form. One column on phones, two from 760px.

### Work Tile (signature)
A 4:5 job photograph with a bottom slate fade and a white Cal Sans caption, its stage number above in Ember. Tiles form an ordered sequence (two across, four from 1024px) and are followed by one brick-red feature row linking to more work, whose arrow circle inverts to white on hover.

### Numbered Steps
44px brick-red discs with white Cal Sans numerals beside a Cal Sans title and a Soft Ink line.

### Floating Text Circle
A 60px brick-red circle, bottom right, opening a pre-filled text. It slides up (0.35s, `cubic-bezier(.2,.8,.2,1)`) once the hero scrolls away and hides while the form is on screen.

### Motion
The hero H1 enters letter by letter (each from 50px right, 1s `cubic-bezier(.34,1.56,.64,1)`, 20ms stagger), then restores plain text. Below-the-fold blocks fade up 12px over 0.4s. State transitions run 0.15–0.2s. Reduced motion disables all of it; nothing is ever hidden without JS.

### Eyebrow pill (house-style exception)

A quiet 14px label above the hero H1 and the work heading only: a small accent dot on a faint tint, with no hover state, arrow or shadow. Ellie chose it for the calm band style on 2026-10-19, even though Impeccable bans eyebrows. Don't use it on every heading.

## Do's and Don'ts

### Do:
- **Do** use Brick Check Red as a fill with white text on light grounds, and Ember (#f2735a) for red text or icons on dark bands.
- **Do** alternate full-bleed bands so no two neighbours share a ground, with the diagonal line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`) on deep slate only.
- **Do** set headings, buttons, rows and labels in Cal Sans 400 and body in the system stack at 16/1.7.
- **Do** fill form fields with Field Grey (#e6e9ee) on the white card, and show hover and focus as a slate outline or border.
- **Do** keep hover effects inside `@media (hover:hover)` and limit row hovers to the arrow circle.
- **Do** use the business's own job photos, cropped with `object-fit: cover` and darkened until white text passes 4.5:1.

### Don't:
- **Don't** introduce a second accent hue or any gradient beyond the slate photo overlays and the deep-band line texture.
- **Don't** put brick red text on deep slate or slate; it fails contrast. Use Ember.
- **Don't** add shadows to rows, cards, chips or buttons.
- **Don't** use bold or other weights of Cal Sans.
- **Don't** animate any heading other than the hero H1, or add parallax, carousels or counters.
- **Don't** replace the floating text circle with a bottom bar, or show it while the form is in view.
