---
name: ASAP.ai TECHLABS
description: An engagement drawn as a system diagram, from your problem to AI running in production.
colors:
  field: "#0a1c45"
  field-raised: "#0e2457"
  line: "rgba(160, 190, 255, 0.2)"
  line-strong: "rgba(160, 190, 255, 0.45)"
  text: "#f3f6ff"
  text-2: "#b8c5e6"
  text-3: "#93a3cb"
  sheet: "#f4f6fb"
  sheet-raised: "#ffffff"
  ink: "#0a1c45"
  ink-2: "#3b4a70"
  ink-3: "#56658c"
  sheet-line: "#cdd5e7"
  input-stroke: "#8a97b8"
  brand: "#1747d6"
  brand-wash: "#eef3ff"
  ink-solid-hover: "#142d6b"
  live: "#00d4ff"
  alert: "#ff5d7a"
  alert-sheet-stroke: "#c4153a"
  alert-sheet-text: "#b0122f"
  lockup-ai: "#00d4ff"
  lockup-sub: "#c0c0d0"
typography:
  display:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2.4rem, 5.6vw, 5.25rem)"
    fontWeight: 800
    lineHeight: 0.98
    letterSpacing: "-0.03em"
    fontVariation: "'wdth' 118"
  figure:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(3rem, 6vw, 4.75rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.035em"
    fontFeature: "lnum"
    fontVariation: "'wdth' 125"
  headline:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2rem, 3.8vw, 3.35rem)"
    fontWeight: 800
    lineHeight: 1.04
    letterSpacing: "-0.025em"
    fontVariation: "'wdth' 114"
  case-title:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.45rem, 2.2vw, 1.85rem)"
    fontWeight: 800
    lineHeight: 1.12
    letterSpacing: "-0.02em"
    fontVariation: "'wdth' 110"
  title:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "1.3rem"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 106"
  lead:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.1rem, 1.6vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 100"
  body:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
    fontVariation: "'wdth' 100"
  label:
    fontFamily: "Archivo, Segoe UI, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 600
    letterSpacing: "0.12em"
    fontVariation: "'wdth' 125"
  mono:
    fontFamily: "JetBrains Mono, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "0.82rem"
    fontWeight: 400
    letterSpacing: "0"
  lockup-main:
    fontFamily: "Sora, Segoe UI, sans-serif"
    fontSize: "1.35rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.3px"
  lockup-sub:
    fontFamily: "Sora, Segoe UI, sans-serif"
    fontSize: "0.62rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "4px"
rounded:
  chip: "4px"
  control: "6px"
  panel: "8px"
  figure: "10px"
  drawer: "16px"
spacing:
  gutter: "clamp(16px, 4vw, 48px)"
  spine: "clamp(28px, 4vw, 56px)"
  section-y: "clamp(4.5rem, 9vw, 8.5rem)"
  head-gap: "clamp(2.5rem, 5vw, 4rem)"
  case-gap: "clamp(4rem, 8vw, 7rem)"
  container-max: "1240px"
components:
  button-solid:
    backgroundColor: "{colors.text}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0.75rem 1.4rem"
    height: "48px"
  button-solid-hover:
    backgroundColor: "{colors.sheet-raised}"
  button-solid-sheet:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.text}"
    rounded: "{rounded.control}"
    padding: "0.75rem 1.4rem"
    height: "48px"
  button-solid-sheet-hover:
    backgroundColor: "{colors.ink-solid-hover}"
  button-line:
    textColor: "{colors.text}"
    rounded: "{rounded.control}"
    padding: "0.75rem 1.4rem"
    height: "48px"
  button-nav:
    backgroundColor: "{colors.text}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0.55rem 1.05rem"
    height: "42px"
  button-quiet:
    backgroundColor: "{colors.sheet-raised}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0.5rem 0.9rem"
    height: "44px"
  copy-button:
    backgroundColor: "{colors.sheet-raised}"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.control}"
    size: "44px"
  chip-stack:
    backgroundColor: "{colors.sheet-raised}"
    textColor: "{colors.ink-2}"
    typography: "{typography.mono}"
    rounded: "{rounded.chip}"
    padding: "0.25rem 0.55rem"
  input-field:
    backgroundColor: "{colors.sheet-raised}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0.75rem 0.9rem"
    height: "48px"
  choice:
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0.8rem 0.9rem"
  choice-selected:
    backgroundColor: "{colors.brand-wash}"
    textColor: "{colors.ink}"
  port:
    backgroundColor: "{colors.field-raised}"
    textColor: "{colors.text}"
    rounded: "{rounded.panel}"
    padding: "1.1rem 1.15rem 1.2rem"
  figure:
    backgroundColor: "{colors.field}"
    textColor: "{colors.text}"
    rounded: "{rounded.figure}"
    padding: "clamp(1rem, 3vw, 2.25rem)"
  form-panel:
    backgroundColor: "{colors.sheet-raised}"
    textColor: "{colors.ink}"
    rounded: "{rounded.figure}"
    padding: "clamp(1.25rem, 3vw, 2.25rem)"
  sent-panel:
    backgroundColor: "{colors.brand-wash}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "1.1rem 1.2rem"
  nav-bar:
    backgroundColor: "{colors.field}"
    textColor: "{colors.text-2}"
    height: "68px"
  nav-link:
    textColor: "{colors.text-2}"
    rounded: "{rounded.control}"
    padding: "0.55rem 0.9rem"
  nav-link-current:
    textColor: "{colors.text}"
  sheet-menu:
    backgroundColor: "{colors.field-raised}"
    textColor: "{colors.text}"
    rounded: "{rounded.drawer}"
---

# Design System: ASAP.ai TECHLABS

## Overview

**Creative North Star: "The Engagement Schematic"**

The page is drawn the way the company draws its own systems: an engagement is a pipeline from "your problem" to "running in production", and every section hangs off one vertical line like stations on a drawing. Two materials carry the whole world. A deep cobalt drawing field, faintly gridded with a hexagonal lattice and ruled in hairline pale-blue line work, holds the diagrams, the navigation and the brand. Cool white spec sheets hold dense reading: case studies, process, the contact form. Sections alternate between the two, so the page reads as drawing, sheet, drawing, sheet.

The hexagon from the logo mark is the only motif. It appears as section nodes on the spine, as pipeline stations, as numbered process steps, as list bullets on sheets and as diagram nodes inside figures. Nothing else is ornamental. Colour is reserved for state: cyan means live, in production or current; red means something went wrong; brand blue is how a sheet says "this one". Type is Archivo, stretched wide for display and figures, normal width for reading, with JetBrains Mono only where a stack or a technical figure is named.

The system rejects the AI-consultancy default: no glowing dark hero, no gradient headings, no glass cards, no centred stack of identical sections, no icon tiles, no eyebrow labels over headings, no decorative motion.

**Key Characteristics:**
- One left spine with a hexagon node and registration tick at every section head.
- Two materials only: cobalt field and white sheet, alternating by section.
- Hexagon is the single motif, always drawn with a hairline outline and a hollow or filled centre.
- Colour encodes state; at rest the page is cobalt, white and ink.
- Scale jumps: billboard figures and display headlines against small, wide, uppercase labels.
- One authored motion moment (work packets travelling the hero pipeline to a pinging Run node); everything else is press feedback, a drawer and quiet state transitions.

## Colors

A two-material palette of cobalt and cool paper, with exactly three state hues and nothing decorative.

### Primary
- **Drawing Cobalt** (field): the ground of the hero, About, Services, nav and footer, and the inside of every figure. Also used as ink on sheets, so the two materials share one blue.
- **Signal Blue** (brand): emphasis on sheets only. Billboard case figures, hexagon bullets in case points, the selected contact choice, the current section node on a sheet, the "Run" step in the process, focus outlines on sheets.

### Secondary
- **Live Cyan** (live): state, never decoration. The Run node and its status dot, travelling work packets, the current nav item's dot, the current section node on the field, the Run stage in the services map, the "Check" node in Fig. 2, text selection, focus outlines on the field.

### Tertiary
- **Fault Coral** (alert): the failure path inside figures (mismatch arrow, node and "Team alerted" label in Fig. 1). On sheets the alert role darkens for contrast: **Fault Crimson Stroke** (alert-sheet-stroke) for an invalid field's border and **Fault Crimson** (alert-sheet-text) for error messages.
- A caution amber (`--caution: #ffb547`) and a deeper node cobalt (`--field-node: #12306f`) are declared on `:root` but no element uses them; they are reserved, not part of the recorded palette, until a surface needs them.

### Neutral
- **Raised Cobalt** (field-raised): ports in the pipeline, the large hexagon nodes inside figures, the mobile bottom-sheet menu.
- **Hairline** (line) and **Strong Hairline** (line-strong): pale-blue line work on the field. Hairline divides (nav bottom, figcaption top, spec rows, title-block cells); Strong Hairline draws (spine, pipeline track, hexagon outlines, line buttons, port borders).
- **Field White** (text), **Field Mist** (text-2), **Field Slate** (text-3): primary, secondary and label text on the field.
- **Cool Paper** (sheet) and **Paper White** (sheet-raised): the sheet ground and raised paper (form panel, stack chips, copy button, inputs).
- **Ink** (ink), **Ink Mid** (ink-2), **Ink Soft** (ink-3): primary, secondary and label text on sheets; Ink Soft also outlines hexagons and draws the registration tick on sheets.
- **Rule Grey-Blue** (sheet-line): dividers, chip borders and the spine on sheets.
- **Input Steel** (input-stroke): text-field borders, darker than sheet-line so fields read as controls.
- **Selection Wash** (brand-wash): fill of a selected choice and the sent confirmation panel.
- **Deep Ink** (ink-solid-hover): hover fill for the solid button on sheets.

### Named Rules
**The State-Only Rule.** Cyan, coral and brand blue appear only when they mean something: live, failed, current or selected. If an element is coloured and you cannot say which state it reports, remove the colour.

**The Material Pairing Rule.** Cyan lives on the field; brand blue is its counterpart on sheets. Never put cyan on a sheet or brand blue on the field.

**The Lockup Ground Rule.** The logo lockup ("ASAP" white, ".ai" lockup-ai, "TECHLABS" lockup-sub) always sits on Drawing Cobalt. Its colours are brand assets, not palette roles, and never move to other elements by association.

## Typography

**Display Font:** Archivo variable (with Segoe UI, system-ui, sans-serif)
**Body Font:** Archivo at normal width (same family)
**Label/Mono Font:** JetBrains Mono (with ui-monospace, SFMono-Regular, Menlo, monospace)
**Lockup Font:** Sora, used only inside the logo lockup

**Character:** One grotesque doing every job by changing its width axis: wide and heavy for headlines and figures, wide and small for labels, normal width for reading. Mono is a technical annotation, not a voice.

### Hierarchy
- **Figure** (800, clamp(3rem, 6vw, 4.75rem), 0.95, width 125, lining numerals): the one billboard number per case study, in Signal Blue on a sheet.
- **Display** (800, clamp(2.4rem, 5.6vw, 5.25rem), 0.98, width 118): the hero headline only, left-aligned, max 15ch.
- **Headline** (800, clamp(2rem, 3.8vw, 3.35rem), 1.04, width 114): section headings, always on the spine with a node.
- **Case Title** (800, clamp(1.45rem, 2.2vw, 1.85rem), 1.12, width 110): case-study headings beside their figure.
- **Title** (700, 1.3rem, 1.2, width 106): process steps, services and other in-section headings; pipeline station names use the same cut at 1.05 to 1.15rem.
- **Lead** (400, clamp(1.1rem, 1.6vw, 1.3rem), 1.5): the sentence under a headline, max 38 to 44ch.
- **Body** (400, 1.0625rem, 1.6, width 100): reading copy, held to 44 to 46ch.
- **Label** (600, 0.75rem, 0.12em, uppercase, width 125): spec-list terms, contact terms, figcaptions, pipeline port types, footer title-block fields. Inside figures the same voice is drawn at 9px, 600, letter-spacing 1.2.
- **Mono** (400, 0.82rem): technology stack chips only.

### Named Rules
**The Width-Axis Rule.** Hierarchy comes from Archivo's width axis plus weight, not from adding families. Wider means louder; reading text stays at width 100.

**The Label-Is-Data Rule.** The uppercase label names a field, a figure or a port. It never floats above a section heading as an eyebrow.

**The Sora Quarantine Rule.** Sora appears only inside the logo lockup. Never set any other text in it.

## Layout

The page is a single column of full-bleed sections inside a 1240px container with a fluid gutter. Every section's content is pushed right by the spine width, and a 1px vertical line runs at the gutter's left edge through every section from nav to footer: Strong Hairline on the field, Rule Grey-Blue on sheets. Each section head carries a hexagon node on that line and a short horizontal registration tick reaching from the spine to the heading, so every section visibly hangs off one axis.

Sections are spaced by the section-y rhythm; headings sit head-gap above their content; case studies are separated by case-gap. Within a section, content is asymmetric: case studies run figure-left 7fr to text 5fr, About splits copy and spec list evenly, Contact runs details 5fr to form 7fr. Horizontal diagrams (the hero pipeline, the process, the services map) draw their own track line and hang hexagon stations from it; services hang under the pipeline stage they serve.

Responsive behaviour:
- **1100px:** pipeline station descriptions hide, the input and Run ports keep their width.
- **900px:** nav links and the nav button give way to a menu toggle and bottom-sheet menu. Every horizontal diagram (pipeline, process, services) rotates onto the page spine, so the stations stack down the same vertical axis the sections use. Two-column sections become one column. The footer title block becomes two columns.
- **560px:** figures keep legible label sizes by scrolling sideways inside their panel (SVG min-width 460px) rather than shrinking. Choices, paired fields, spec rows, contact rows and the title block stack to one column.

### Named Rules
**The One Axis Rule.** Every section, at every width, hangs off the left spine. On small screens diagrams join the spine instead of shrinking.

**The Alternating Materials Rule.** Sections alternate field and sheet. Do not put two sheets or two field sections back to back without reason.

## Elevation & Depth

Flat. Depth comes from material change (field to sheet), from Raised Cobalt on the field, from Paper White on Cool Paper, and from hairline borders. The only shadows are functional: an input's focus ring, the inset stroke that marks a selected choice, and the logo mark's own glow, which is part of the brand artwork.

### Shadow Vocabulary
- **Field focus ring** (`box-shadow: 0 0 0 3px rgba(23, 71, 214, 0.18)`): text fields on focus, with a brand-blue border.
- **Selected stroke** (`box-shadow: inset 0 0 0 1px #1747d6`): doubles the border of a selected choice.
- **Logo mark glow** (`filter: drop-shadow(0 0 10px rgba(43, 127, 255, 0.55))`): the 40px mark in the lockup only; a fixed brand asset.

### Named Rules
**The Flat Drawing Rule.** Surfaces never float. If something needs to stand forward, raise its material one step or give it a hairline; do not add a shadow or a glow.

## Shapes

Rectilinear panels with small, consistent corners, and one non-rectangular form: the pointy-top hexagon (clip-path polygon 50% 0, 100% 25%, 100% 75%, 50% 100%, 0 75%, 0 25%). Hexagons are drawn as an outline by layering a 1.5 to 2px inset of the ground colour inside a line-coloured hexagon; a filled hexagon means state (current, Run, selected). Corners step by role: chips 4px, controls 6px, ports and confirmation panels 8px, figures and the form panel 10px, the mobile drawer 16px on its top edge. Status dots and the nav current marker are circles. Lines are always 1px.

## Components

### Buttons
Firm, quiet, wide-cut labels that press physically.
- **Shape:** gently squared (6px), min height 48px, label Archivo 650 at width 108, optional 16px arrow icon.
- **Solid on field:** Field White fill with Ink text; hover goes to pure white.
- **Solid on sheet:** Ink fill with Field White text; hover to Deep Ink.
- **Line:** transparent with a Strong Hairline border on the field; hover border goes to Field White.
- **Quiet:** Paper White with a Rule Grey-Blue border on sheets, 44px; hover border Ink Soft. Used for secondary actions after sending.
- **Nav:** the solid button at 42px for the bar.
- **Press / hover:** every button scales to 0.97 on press (160ms, ease-out); the arrow icon nudges 3px right on hover. Hover styles apply only to fine pointers.
- **Text link:** underlined in Strong Hairline, underline brightens to Field White on hover, 44px hit area.

### Chips
- **Stack chip:** JetBrains Mono 0.82rem, Ink Mid on Paper White, 1px Rule Grey-Blue border, 4px corners. Static labels for a case's technology; never interactive.

### Cards / Containers
- **Figure:** a piece of drawing field set into a sheet, 10px corners, padded art area holding a schematic SVG (hexagon nodes, hairline arrows, Live Cyan or Fault Coral only on the node that carries state), then a figcaption in the Label voice ("Fig. n · Schematic" left, provenance right) above a Hairline rule.
- **Port:** a pipeline station that holds content, Raised Cobalt with a Strong Hairline border, 8px corners. The input port holds the primary action; the Run port's border is Live Cyan.
- **Form panel:** Paper White on Cool Paper with a Rule Grey-Blue border, 10px corners.
- **Sent panel:** Selection Wash with a brand-blue border, 8px corners, settles in (400ms, 6px rise) and takes focus as a status region.

### Inputs / Fields
- **Style:** Paper White, 1px Input Steel border, 6px corners, 48px min height (textarea 140px, vertical resize), visible label above, "(optional)" in Ink Soft.
- **Focus:** border to brand blue plus the field focus ring; caret is brand blue.
- **Error:** border to Fault Crimson Stroke, message below in Fault Crimson at 0.88rem, wired with aria-invalid and aria-describedby; validates on blur and re-checks on input once invalid.
- **Choice:** a radio drawn as a bordered tile (bold title plus small description); selected is brand border, Selection Wash fill and inset stroke; focus shows a brand outline.

### Navigation
- **Bar:** sticky, Drawing Cobalt, 68px, Hairline bottom border; lockup left, four links, solid nav button.
- **Links:** Field Mist at 0.95rem 500; hover to Field White; the current section (set by scroll position) turns Field White with a 6px Live Cyan dot and aria-current.
- **Mobile (900px and below):** a 48px outlined toggle whose bars morph to a cross opens a bottom-sheet menu: Raised Cobalt, 16px top corners, grab handle, links at 56px rows that stagger in (30ms steps), solid call button full width. It slides on the drawer curve over 500ms, can be dragged down to close (velocity-aware), and sits over a dimmed backdrop.

### Spine Node and Registration Tick (signature)
Every section head carries a 13 by 15px outlined hexagon on the spine and a 29px tick reaching to the heading. When a section is current, its node fills: Live Cyan on the field, brand blue on a sheet (400ms ease-out).

### Engagement Pipeline (signature)
A horizontal track at full width: the input port (the primary call action), four outlined hexagon stations, then the Run port with a Live Cyan status dot. On the field only.

### Process Steps and Services Map
Numbered 30 by 34px outlined hexagons on a sheet track; the final Run step fills brand blue. The services map reuses the pipeline's stages as hexagon headers on the field and hangs each service below its stage with a Strong Hairline left rule; the Run stage is Live Cyan.

### Spec List and Footer Title Block
- **Spec list:** a definition list ruled in Hairline, Label-voice terms in a 9.5rem column, values in Field White.
- **Title block:** the footer drawn as a drawing's title block: a Strong Hairline box of cells divided by Hairline (lockup, Practice, Studio, social), with 44px outlined social buttons.

### Motion
One authored moment: three Live Cyan packets travel the hero pipeline track (6s linear, staggered 2s) toward the Run node, whose status dot pings (2.4s). Both pause off-screen and disappear under reduced motion. Everything else is feedback: press scale (160ms), state transitions (200ms) on ease-out `cubic-bezier(0.23, 1, 0.32, 1)`, and the drawer on `cubic-bezier(0.32, 0.72, 0, 1)`. Under reduced motion, drawer transitions are effectively instant and press scaling is removed.

### Brand Lockup (fixed)
The mark (`assets/logo-mark.webp`) at 40px with its blue drop-shadow, beside "ASAP" in white and ".ai" in lockup-ai (Sora 800, 1.35rem) over "TECHLABS" in lockup-sub (Sora 600, 0.62rem, 4px tracking). Identical in nav and footer, always on Drawing Cobalt. This artwork and styling never change.

## Do's and Don'ts

### Do:
- **Do** hang every new section off the left spine with a hexagon node and registration tick.
- **Do** alternate field and sheet sections, and choose the material by content: diagrams and brand on the field, dense reading and forms on sheets.
- **Do** colour only state: Live Cyan for live, current or in production on the field; brand blue for current or selected on sheets; Fault Coral for failure.
- **Do** lead proof with a figure: a schematic on drawing field or one billboard number at Figure scale, with text confirming it.
- **Do** use Archivo's width axis for hierarchy and keep reading text at width 100 within 44 to 46ch.
- **Do** keep touch targets at 44px or more and every interactive element with a visible focus outline (Live Cyan on the field, brand blue on sheets, 2px, offset 3px).
- **Do** rotate horizontal diagrams onto the spine below 900px rather than shrinking them.
- **Do** keep the logo mark, its glow and the Sora lockup styling exactly as specified, on Drawing Cobalt.

### Don't:
- **Don't** place uppercase labels or kickers above section headings; labels name fields, figures and ports.
- **Don't** use gradient text, glow halos, glass or blurred panels, or decorative gradients.
- **Don't** use icon tiles; the hexagon is the only motif, and icons appear only as small inline line glyphs inside controls (arrows, copy, check, social).
- **Don't** add infinite or ambient animation beyond the hero pipeline's packets and Run ping.
- **Don't** add drop shadows to raise surfaces; change material or add a hairline.
- **Don't** set any text other than the lockup in Sora, or use JetBrains Mono for anything but stacks and technical figures.
- **Don't** put Live Cyan on a sheet or brand blue on the field.
- **Don't** recolour, restyle or place the lockup on a light ground.
