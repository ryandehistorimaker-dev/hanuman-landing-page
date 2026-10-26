---
name: Hanuman Construction
description: Exhibition and interior design-and-build, rendered in the same stock as the booths. Maroon HPL panels, exposed plywood edges, workshop-grey ground.
colors:
  hpl: "#821D1D"
  hpl-deep: "#5E1414"
  hpl-lift: "#9B2823"
  ply-a: "#E6C998"
  ply-b: "#C99D63"
  ply-c: "#EDD5AA"
  ply-d: "#B4874F"
  ply-face: "#D9B583"
  veneer-ink: "#3A2814"
  ground: "#DCDCD8"
  ground-2: "#CDCDC7"
  white-hpl: "#F5F3EF"
  light-edge: "#BDB3A6"
  on-hpl: "#FFFFFF"
  on-hpl-2: "#F2D9D4"
  ink: "#1C1A18"
  ink-2: "#4B4642"
  ink-3: "#5C5651"
  rule: "#B5B3AC"
  night: "#161413"
  night-2: "#24211F"
  night-text: "#CFC7BF"
  night-label: "#A79E95"
  night-rule: "#3A3532"
  field-stroke: "#8C867F"
  check-stroke: "#6E6863"
  placeholder: "#7C756F"
  sheet-edge: "#CFC9C0"
  selected-tint: "#F7ECEA"
  error: "#B3261E"
  whatsapp: "#1E8E4E"
  whatsapp-lift: "#22A05A"
typography:
  display:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(46px, 6.4vw, 94px)"
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: "-0.04em"
  display-mobile:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(40px, 12vw, 64px)"
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(30px, 4.4vw, 58px)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  headline-sm:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(28px, 3.4vw, 44px)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  headline-close:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(28px, 4vw, 52px)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  lead-in-mobile:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  subhead:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(20px, 2vw, 26px)"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(19px, 1.6vw, 22px)"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  lede:
    fontFamily: "Montserrat, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(17px, 1.5vw, 21px)"
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: "-0.01em"
  offer:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "clamp(16px, 1.3vw, 18px)"
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: "normal"
  closing-line:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "clamp(17px, 1.4vw, 19px)"
    fontWeight: 600
    lineHeight: 1.55
    letterSpacing: "normal"
  body:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 500
    lineHeight: 1.6
    letterSpacing: "normal"
  body-sm:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.55
    letterSpacing: "normal"
  field-label:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: "normal"
  code-sm:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0.1em"
  link:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "0.04em"
  label:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0.18em"
  button:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "0.01em"
rounded:
  none: "0px"
  tag: "2px"
  control: "4px"
  pill: "999px"
spacing:
  ply-rule: "5px"
  ply-edge-sm: "9px"
  ply-edge: "12px"
  chip-gap: "8px"
  gutter: "clamp(16px, 4.2vw, 64px)"
  section: "clamp(88px, 10vw, 150px)"
  max: "1320px"
components:
  button-primary:
    backgroundColor: "{colors.hpl}"
    textColor: "{colors.on-hpl}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 26px"
    height: "54px"
  button-primary-hover:
    backgroundColor: "{colors.hpl-lift}"
  button-light:
    backgroundColor: "{colors.white-hpl}"
    textColor: "{colors.hpl}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 26px"
    height: "54px"
  button-light-hover:
    backgroundColor: "{colors.on-hpl}"
  chip-cta:
    backgroundColor: "{colors.white-hpl}"
    textColor: "{colors.hpl}"
    rounded: "{rounded.control}"
    padding: "0 12px 0 14px"
    height: "48px"
  chip-cta-hover:
    backgroundColor: "{colors.on-hpl}"
  type-option:
    backgroundColor: "{colors.on-hpl}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "10px 14px"
    height: "50px"
  type-option-selected:
    backgroundColor: "{colors.selected-tint}"
    textColor: "{colors.hpl}"
  type-option-check:
    rounded: "{rounded.tag}"
    size: "12px"
  text-link:
    textColor: "{colors.ink}"
    typography: "{typography.link}"
    height: "44px"
  link-button:
    textColor: "{colors.hpl}"
    typography: "{typography.link}"
  field-input:
    backgroundColor: "{colors.on-hpl}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "12px 14px"
    height: "50px"
  field-label:
    textColor: "{colors.ink}"
    typography: "{typography.field-label}"
  nojs-notice:
    backgroundColor: "{colors.selected-tint}"
    textColor: "{colors.hpl}"
    rounded: "{rounded.control}"
    padding: "12px 14px"
  hpl-board:
    backgroundColor: "{colors.hpl}"
    textColor: "{colors.on-hpl}"
    rounded: "{rounded.none}"
    padding: "clamp(28px, 4vw, 56px)"
  sample-chip:
    backgroundColor: "{colors.white-hpl}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "16px 16px 22px"
  sheet:
    backgroundColor: "{colors.white-hpl}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "clamp(24px, 3vw, 40px)"
  photo-caption:
    backgroundColor: "{colors.white-hpl}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tag}"
    padding: "5px 9px"
  award-tag:
    backgroundColor: "{colors.hpl}"
    textColor: "{colors.on-hpl}"
    typography: "{typography.label}"
    rounded: "{rounded.tag}"
    padding: "2px 8px"
  whatsapp-pill:
    backgroundColor: "{colors.white-hpl}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "44px"
  dock-whatsapp:
    backgroundColor: "{colors.whatsapp}"
    textColor: "{colors.on-hpl}"
    rounded: "{rounded.control}"
    width: "54px"
    height: "50px"
  dock-whatsapp-hover:
    backgroundColor: "{colors.whatsapp-lift}"
---

# Design System: Hanuman Construction

## Overview

**Creative North Star: "The Workshop Sample Board"**

Hanuman builds booths and interiors from laminate-faced plywood, so the page is built from the same stock. Big fields are matte maroon HPL. Wherever a panel ends, its plywood core shows as a band of layered tan stripes. Panels are mounted over real build photographs and laid on a concrete-grey workshop ground, and charcoal "night" bands carry the built work. Nothing is rendered as glossy, glowing, or soft. Depth comes from boards stacked on boards and from edges you can see.

Density is generous and confident. Sections breathe on a 88–150px vertical rhythm, and display type is wide, rounded, and set tight like the logo. Small details come from a contractor's sample library: tracked Montserrat caps work as sample codes, round punch-holes mark swatches, and ruled schedules list projects. Motion only shows assembly: the hero board laminates down into place, process layers stack, and a chosen project type gets pasted onto the form.

The world rejects the dark-overlay hero with a centred white headline, rows of equal service cards, gradients used as decoration, and fake glow.

**Key Characteristics:**
- Maroon HPL fields with an exposed plywood edge on the top and one side.
- Square-cornered panels; soft radii only on small controls (2–4px).
- One family throughout: Montserrat 700–800 for display, medium-weight Montserrat for body (client asked for Montserrat/Helvetica only).
- Depth from layering and visible panel thickness, never from blur shadows.
- Real project photography as the substrate panels sit on.
- Motion shows how things get built: laminate, stack, paste.

## Colors

The palette is one material in three finishes: maroon laminate, plywood core, and the grey and charcoal of the workshop around it.

### Primary
- **Hanuman Maroon HPL** (hpl): The brand laminate, matched to the logo pill. It covers whole fields (hero board, closing board, the order section), the primary button, award tags, the selected swatch dot, step numbers, the section heading in "why space", and the focus ring on light grounds. Text on it is white or Blush Laminate.
- **Panel Core Maroon** (hpl-deep): The shadowed thickness of a maroon panel. Used for the inset line where ply meets laminate (boards, the order section's top band, the maroon sample chip), the button's bottom edge, and the shadowed base of the process stack's laminate face.
- **Lifted Maroon** (hpl-lift): Button hover only.

### Secondary
- **Plywood Plies** (ply-a, ply-b, ply-c, ply-d): Four alternating veneer tones. They are only ever used together as the ply stripe (`repeating-linear-gradient`, 5px repeat): a 12px panel edge, 9px on sample chips, 14px on the order section's top, 6px over the mobile dock, and a 5px rule under table headers and spec rows. Pale Ply (ply-a) on its own is the focus ring inside maroon and charcoal regions, where a maroon ring would vanish.
- **Veneer Face** (ply-face): The face of the plywood sample chip in the service deck.
- **Veneer Ink** (veneer-ink): Secondary text on the Veneer Face chip (sample code, sub-line, description). A dark tan from the same stock, so the chip never borrows the grey ink.

### Neutral
- **Workshop Concrete** (ground): The page ground and the mobile dock.
- **Concrete Shade** (ground-2): The services band, swatch punch-holes, the FAQ toggle at rest, and the scrollbar track.
- **White Laminate** (white-hpl): Light panel faces (form sheet, sample chips, photo captions, light button, hero project chips, WhatsApp pill).
- **Laminate Edge** (light-edge): The visible bottom thickness of a White Laminate control: the light button and the hero project chips. It is the white panel's deeper tone, the same role Panel Core Maroon plays under a maroon button.
- **Pure White** (on-hpl): Text on maroon and charcoal, and input and option fills inside the sheet.
- **Blush Laminate** (on-hpl-2): Secondary text on maroon (ledes, notes, the hero's chip prompt).
- **Workshop Ink** (ink), **Ink Grey** (ink-2), **Ink Muted** (ink-3): Primary, secondary, and tertiary text on light grounds.
- **Pencil Rule** (rule): 1px dividers on light grounds.
- **Night Charcoal** (night), **Night Panel** (night-2): The built-work band, closing photo base, footer, and the charcoal sample chip.
- **Night Text** (night-text), **Night Label** (night-label), **Night Rule** (night-rule): Secondary text, schedule header labels, and row dividers on charcoal.
- **Field Stroke** (field-stroke): The 1.5px border of every input and project-type tile. A mid warm grey, dark enough to read as a control boundary on white (3:1), not a hairline.
- **Check Stroke** (check-stroke): The empty square tick inside a project-type tile.
- **Placeholder Grey** (placeholder): Input and textarea placeholder text.
- **Sheet Edge** (sheet-edge), **Selected Tint** (selected-tint): The inset line under ply edges on white panels, and the fill of a selected project type (also the no-JavaScript notice inside the sheet).

### Functional
- **Error Red** (error): Invalid field border and message only, including the border of every project-type tile when no type is chosen.
- **WhatsApp Green** (whatsapp), **WhatsApp Lift** (whatsapp-lift): Only the WhatsApp glyph and the mobile-dock WhatsApp button, with Lift as that button's hover face. It is a third-party signal, not part of the palette.

### Named Rules
**The One Laminate Rule.** Maroon is the only chromatic accent. A new section gets a new finish of the same stock (maroon, white laminate, veneer, charcoal), never a new hue.

**The Plies Travel Together Rule.** The four ply tones are never used one at a time as fills. They show up as the striped edge or rule, because that is what plywood looks like when it is cut.

**The Two Rings Rule.** Focus is a 3px outline offset 3px (2px on the form's type tiles). It is Hanuman Maroon on light grounds (concrete, white laminate, the form sheet) and Pale Ply on maroon and charcoal (hero, boards, order section, built work, closing, footer). A white sheet inside a maroon section switches back to maroon.

## Typography

**Display Font:** Montserrat 700–800 (Helvetica Neue, Helvetica, Arial fallback)
**Body Font:** Montserrat (with system-ui fallback)
**Label Font:** Montserrat, tracked caps

**Character:** Montserrat matches the tracked tagline under the logo. Weight does the work a second face used to: heavy Montserrat is the sign, medium Montserrat carries everything you read.

### Hierarchy
- **Display** (700, clamp(46px, 6.4vw, 94px), 0.95, -0.04em): One oversized word per surface, inside the H1 on the hero board ("experience."). Under 760px it switches to Display Mobile (clamp(40px, 12vw, 64px)).
- **Headline** (600, clamp(30px, 4.4vw, 58px), 1.08, -0.02em): Section H2s, balanced wrapping.
- **Headline Small** (600, clamp(28px, 3.4vw, 44px)): Secondary H2s that sit beside denser content (FAQ) and the hero H1 lead-in (clamp(28px, 3.3vw, 46px)). The closing board's H2 is Headline Close (clamp(28px, 4vw, 52px)), wider at the top end because it is the only text on its board. Under 760px the hero lead-in drops to a flat 24px (Lead-in Mobile) so the big word carries the line.
- **Subhead** (600, clamp(20px, 2vw, 26px), 1.2): Schedule headings, including the second schedule table's heading; the form sheet title sits at its 20px floor.
- **Title** (600, clamp(19px, 1.6vw, 22px), 1.2, -0.01em): H3s, sample-chip names, spec terms, FAQ questions (16–19px), schedule brand names. Process step titles step up to clamp(22px, 2vw, 28px).
- **Lede** (Montserrat 600, clamp(17px, 1.5vw, 21px), 1.35): The one-line statement under a headline, never more than a single sentence. Spec terms sit in Montserrat 700 at clamp(18px, 1.6vw, 22px).
- **Offer** (Montserrat 600, clamp(16px, 1.3vw, 18px), 1.5, white): The concrete offer line on the hero board under the lede, capped at 46ch; 15px under 760px.
- **Closing Line** (Montserrat 600, clamp(17px, 1.4vw, 19px), 1.55): The closing paragraph in the why section, capped at 44ch, in Workshop Ink.
- **Body** (Montserrat 500, 17px / 16px under 760px, 1.6): Paragraphs capped at 62ch. The order section's lead question sets body at 600.
- **Body Small** (Montserrat 500, 15px, 1.55): Card and note copy, step copy, schedule detail columns, type tiles, footer, and the dock button. Hero chips set it at 700 in maroon; the hero chip prompt is 15px/700 in Blush Laminate (14px under 760px).
- **Link** (Montserrat 700, 15px, 0.04em, underlined): Text links and text-styled buttons.
- **Field Label** (Montserrat 700, 14px): Form labels and legends, nav links (uppercase, 0.06em), and small notes under sections.
- **Label** (Montserrat 700, 12px, 0.18em, uppercase): Sample codes ("HN · Booth"), photo captions, table headers (0.16em), and meta like "± 1 menit". Code Small (13px, 0.1em) carries the sub-line on sample chips; step numbers run at 13px / 0.16em in maroon, and form error and fine print sit at 13px in sentence case.
- **Form small print** (Montserrat 600, sentence case): the sheet's reassurance line under the title (15px, Ink Grey), the proof line above submit (14px, Ink Grey), the project-type status note (13px, Hanuman Maroon), and the note field's character counter (12px, Ink Muted, tabular numerals).

### Named Rules
**The Sample Code Rule.** Tracked caps label a physical thing: a swatch, a photo, a table column, a step. They never float above a headline as a section kicker.

**The Marked Language Rule.** Display copy is English inside an Indonesian page. Every English heading, lede, spec term, and service sub-label carries `lang="en"` so it is voiced and hyphenated as English; Indonesian reading copy inherits the page language.

**The One Big Word Rule.** The display size belongs to a single word inside the H1. Headlines elsewhere stay at headline scale.

**The Signboard Rule.** Heavy Montserrat (700–800) sets headings, one-sentence ledes, and short labels (spec terms, schedule brand names, the footer tagline). It never sets a paragraph of reading copy; closing lines, offers, and client lists are Montserrat at 600–700.

## Layout

Content sits in a 1320px max container with a fluid gutter (clamp(16px, 4.2vw, 64px)). Sections run on clamp(88px, 10vw, 150px) of vertical padding. Section heads cap at 880px.

Layout is asymmetric. Two-column splits are weighted (1.05/1, 1.1/0.9, 0.85/1.15, 0.7/1.3) with clamp(32px, 6vw, 96px) gaps. The hero board is left-anchored at min(760px, 62vw) and overhangs the next section by 40px. The client row then aligns to the column beside it.

The service deck is a four-column grid of unequal widths (1.12/0.94/1.04/0.9fr), with each chip slightly rotated (-1° to 1.2°) and vertically offset, like samples dropped on a table. Built work uses a 12-column photo mosaic with mixed spans.

Responsive breakpoints are 1080px and 760px. At 1080px, splits collapse to one column and the deck becomes 2×2 with rotation kept; between 761px and 1080px the hero board narrows to min(620px, 64vw) and the hero caption moves up to 96px from the top. At 760px:
- The hero photo becomes a 38svh band (220–420px) with the board overlapping it by 30px. The hero lede is hidden, so the board carries only the H1, the offer, and the chips, and the hero caption moves to the photo's top-left corner (66px down).
- Body copy drops to 16px.
- Hero chips become a 2×2 grid of equal full-width cells with short labels (the `long` second word drops: "Booth", "Interior", "Pop-up", "Event"); the same short-label device shortens the hero text link and the form's submit button.
- The form's project types stay a 2×2 grid at 14px.
- The deck becomes a snap-scrolling strip at 76% card width, upright, with cards aligned to the top and the CTA directly under the copy (no pushed-down foot).
- The gallery becomes two columns and shows its first five tiles until "Lihat semua proyek" expands the rest; captions keep the name and drop the muted second line.
- The schedule table reflows into stacked rows (see Ruled Lists and Schedules).
- A fixed dock with a ply top edge slides up.

## Elevation & Depth

Depth is physical, not atmospheric. Panels sit on other panels and show their thickness as a ply edge on the top and one side (right by default, left when the panel hugs the right side). The inside of that edge carries a 2px inset line in the panel's core tone. There are no ambient blur shadows at rest.

Two state-only exceptions exist. The project-type "paste" animation casts a short soft shadow that fades to none as the swatch lands. Inputs get a 3px translucent maroon focus halo.

### Shadow Vocabulary
- **Ply edge seam** (`box-shadow: inset 0 -2px 0 var(--hpl-deep)` on the edge strip): Separates the plywood band from the laminate face. Uses Sheet Edge on white panels and the panel's own deep tone on sample chips.
- **Panel thickness** (`box-shadow: 0 4px 0 var(--edge)`; hover `0 6px 0`; active `0 1px 0` with a 3px press): The visible bottom edge of a button or hero chip, always in the control's own deeper tone (Panel Core Maroon on primary, Laminate Edge on the light button and hero chips, #14643A on WhatsApp). It is straight down, never offset sideways, never black.
- **Field focus** (`box-shadow: 0 0 0 3px rgba(130,29,29,.18)`): Input focus only.
- **Paste drop** (`0 14px 18px -10px rgba(28,26,24,.45)` → none, 0.6s): Transient, inside the paste animation only.
- **Layer seam** (`box-shadow: inset 0 -1px 0 rgba(0,0,0,.18)`): The 1px glue line under each ply layer in the process stack.
- **Nav legibility** (`text-shadow: 0 1px 10px rgba(0,0,0,.55)`): A one-off. Only the white nav links over the hero photo, together with the 160px top scrim, so they read on any frame. Not a depth device and not to be reused.

### Named Rules
**The Visible Edge Rule.** If something is raised, show its edge: a ply band or a same-hue thickness line. If you can't say what material the edge is, don't add the depth.

## Shapes

Panels are square-cut: boards, sheets, sample chips, and gallery tiles use 0–2px corners. Rounding is reserved for small handled parts:
- 4px on buttons, hero chips, inputs, project-type tiles, and the no-JS notice.
- 2px on captions and tags.
- A full pill for the WhatsApp contact, echoing the logo pill, and for the browser scrollbar thumb.

Circles mark physical holes and toggles: punch-holes (16px) on swatches and the sheet, the hero caption's 8px dot, and the FAQ's 28px toggle. Multi-select ticks are 2px-rounded squares (the form's project types). The page currently has no single-choice control; if one is added, it takes a round dot so the shape still says how many you can pick. The client-row separators are square (0 radius).

## Components

### Buttons
Tactile and solid, like a laminated block with a visible bottom edge.
- **Shape:** Gently squared (4px), 54px tall, 26px side padding, Montserrat 700 at 16px, with an optional 18px stroked arrow icon.
- **Primary:** Hanuman Maroon face, white text, Panel Core edge.
- **Light:** White Laminate face, maroon text, Laminate Edge. Used on maroon boards.
- **Hover / Active:** Lifts 2px as the edge grows to 6px, moving the Ease Out curve over 0.25s. Press sinks 3px onto a 1px edge. Primary hover shifts to Lifted Maroon; light hover goes pure white.
- **Text link:** The Link face, underlined, 44px tap height, with a 15px arrow. On the hero board it is white (15px, 14px under 760px) and stands in for a secondary button: "Belum yakin jenisnya? Ceritakan saja idenya" sits under the chips and goes to the form with no type set.
- **Link button:** A real button dressed as a text link, for in-place actions ("Ubah isi formulir" on the sent form, "Lihat semua proyek" on mobile). No fill, no border; maroon on light grounds, white on charcoal.

### Chips
- **Hero project chips:** Call-to-action buttons, not a choice control. Small White Laminate blocks on the maroon board: maroon Montserrat 700 at 15px, 48px min height, 4px corners, 0 12px 0 14px padding, a 16px trailing arrow, and the Laminate Edge as a 4px bottom thickness. They lift and press like buttons (hover goes pure white, edge 6px, up 2px; active sinks 3px onto a 1px edge). Nothing is preselected: each chip writes its project type into the form, pastes that tile, and scrolls to the sheet. Under 760px they fill a 2×2 grid with short labels.
- **Form type options:** Multi-select checkboxes. 50px tiles in a two-column grid that stays 2×2 under 760px (8px 10px padding, 14px). They have a Field Stroke border, white fill, and a 12px square tick in Check Stroke. Selected: maroon border, Selected Tint fill, maroon text. When a choice is made elsewhere on the page, the tile plays the paste animation.

### Sample Chips (signature)
A service shown as a physical material sample. The square-cut face (White Laminate, Veneer Face, Night Panel, or Maroon) has a 9px ply edge on top and right. Inside are a punch-hole and a sample code row, a photo with a fixed aspect ratio per chip, a title, a tracked sub-line, a short description, and a text-link CTA. Chips sit rotated and offset, and on hover or focus they straighten and lift 12px over 0.45s. Choosing a chip's CTA adds that project type to the form, like the hero chips.

### HPL Board (signature)
A maroon field with a 12px ply edge on top and right (or left via a modifier). It carries the hero H1, the closing call, and the order section's top edge. On load the hero board itself stays put; only its content laminates top-down with a clip-path reveal over 0.7s with no delay, triggered after two animation frames with a 300ms fallback so the copy can never stay hidden.

### Form Sheet
A White Laminate sheet with a 12px ply edge, a maroon punch-hole top-right, and a ruled title row with a meta code.
- **Lead line:** One reassurance sentence directly under the title rule, 15px/600 in Ink Grey.
- **Fields:** 50px min height, 1.5px Field Stroke, 4px corners, white fill, 16px text, Placeholder Grey placeholder, Field Label above. Optional fields say so in the label in Ink Muted 600. Short optional fields pair two to a row (event date beside location or venue, then area size) and stack to one column under 760px.
- **Counter:** The note field's label carries a right-floated character counter (12px/600, Ink Muted, tabular numerals), hidden from assistive tech.
- **Focus:** Maroon border plus the 3px field-focus halo.
- **Error:** Error Red border and a 13px/600 message. When no project type is chosen, every type tile takes the Error Red border.
- **Type status note:** A 13px/600 maroon line under the type tiles, announced politely, collapsed entirely when empty.
- **Proof line:** Above the submit button, separated by a 1px Pencil Rule: a maroon award tag (no leading margin) and one line of proof at 14px/600 in Ink Grey.
- **Consent check:** A native 20px checkbox in maroon accent, its label row at 44px min height.
- **No-JS notice:** A Selected Tint block with maroon 15px/600 text and 4px corners, shown inside the sheet only when scripts are off.
- **Phone focus:** On phones the sheet title (a programmatically focusable heading, no visible ring) receives focus when a CTA sends the visitor to the form.
- **Success:** The form swaps for a done state. The done block is a programmatic focus target only: it takes focus when the form is sent, draws no outline, and is not a live region (announcements go through the form's separate visually hidden status line).

### Ruled Lists and Schedules
- **Bullet lists:** 1px Pencil Rule rows with a small ply-capped maroon swatch marker.
- **Spec rows:** Separated by the 5px ply rule, closed by a 1px Pencil Rule; the why section carries three rows.
- **Project schedules (on charcoal):** Both tables use the plain variant: three columns (brand, event or location, scope), no year column, the last column left-aligned in Night Text at weight 500. A 5px ply rule sits under tracked headers, Night Rule divides rows, and the brand name is set in the title face. Award tags are small maroon caps blocks after the brand; a repeat award is one row with a count ("Best Booth Design ×2"), not duplicated rows. The second table sits under its own Subhead heading. Under 760px the header row hides and each row becomes a two-column grid: the brand (with its tag) spans the full width, the event or location sits below it on the left at 14px, and the scope sits in an auto-width right column beside it, bottom-aligned, left-set, at 14px in Night Text.

### Client Row
Client names in Montserrat 700 (clamp(15px, 1.2vw, 17px)), separated by 5px square maroon marks (0 radius) that lead each name. The row is clipped at its left edge, so the mark that opens each wrapped line is hidden and no separator is ever left dangling at a line end.

### Photo Captions
White Laminate tags pinned to the photo's lower corner. The hero tag uses the label face and a concrete-grey dot; gallery tags use 12px/700 with a muted second line.

### Pre-launch Placeholder (temporary)
Client-supplied facts not yet confirmed (working hours, lead times) are set as `[ISI: …]` inside a pale-yellow mark (#FFE58F) with a dashed Plywood outline and 700 weight. It is a one-off editing flag, not a palette color or component: every instance must be replaced with the real fact and the mark removed before launch.

### Navigation
Absolute over the hero photo: logo pill on the left; uppercase 14px/700 text links (padded to a 44px tap height) and the White Laminate WhatsApp pill on the right. Under 760px, the text links hide and the pill collapses to a 44px icon button. On mobile, a fixed Workshop Concrete dock with a 6px ply top edge slides up once the hero chips and the form are both out of view. The hero-chip observer starts 900ms after load, after the lamination has finished, so the hidden board copy never reads as scrolled past. It holds a full-width primary button and a 54px WhatsApp Green button.

### Process Stack
Each step draws a stack of ply layers (18px), growing one layer per step and capped with a maroon laminate face. The stack sits on a 2px ink baseline and drops into place in staggered order when it scrolls into view.

### FAQ
Native disclosure rows between Pencil Rules, with questions in the title face. The section heading uses Headline Small. A 28px round toggle sits on Concrete Shade at rest. When open, it turns maroon and its plus rotates into a minus.

## Do's and Don'ts

### Do:
- **Do** end every maroon or white panel with a ply edge on the top and one side (12px on boards and sheets, 9px on chips), with the 2px seam line in the panel's core tone.
- **Do** use the four ply tones only together, as the 5px-repeat stripe, for edges and rules.
- **Do** keep panels square-cut and reserve 2–4px corners for controls, tags, and captions.
- **Do** mount boards over real project photography and let them overhang the section boundary.
- **Do** use tracked Montserrat caps (12px, 0.18em) to label physical things: swatches, photos, columns, steps.
- **Do** give raised controls a straight-down bottom edge in their own deeper tone (0 4px 0), lifting on hover and sinking on press.
- **Do** draw focus as the 3px ring: Hanuman Maroon on light grounds, Pale Ply on maroon and charcoal.
- **Do** use square ticks for multi-select, and keep round dots for single-choice controls only (none exist today).
- **Do** set reading copy in Montserrat; keep the 700–800 weights to headings, one-sentence ledes, and short labels.
- **Do** honour `prefers-reduced-motion`: lamination, stacking, paste, and lift transitions all switch off.

### Don't:
- **Don't** put a dark full-bleed overlay with a centred white headline over the hero photo, or lay services out as a row of equal cards.
- **Don't** use gradients as surface decoration or glow. The repeating-gradient ply stripe and the swatch marker are material, not ornament.
- **Don't** use ambient blur shadows on panels at rest. Depth comes from stacked layers and visible edges.
- **Don't** introduce a second chromatic accent. WhatsApp Green stays on the WhatsApp control only.
- **Don't** place tracked-caps labels above section headlines as kickers.
- **Don't** give a button's thickness edge a sideways offset or a black fill.
- **Don't** launch with any `[ISI: …]` placeholder mark on the page, and don't reuse its yellow anywhere else.
