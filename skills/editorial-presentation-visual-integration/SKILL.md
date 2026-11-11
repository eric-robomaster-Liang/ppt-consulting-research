# Skill: Editorial Presentation Visual Integration

**Version:** 1.0.0  
**Purpose:** Create and revise student/business presentation decks so multiple contributors' slides feel like one coherent presentation without flattening them into screenshots or forcing every page into the same template.

## When to use

Use this skill when the user asks to:
- unify the visual style of slides created by different teammates;
- improve an existing PowerPoint while preserving its content and original visual assets;
- align charts, titles, illustrations, references, and speaker notes/scripts;
- redesign reference slides using Harvard author–date referencing.

## Core design principle

**Integrate, do not re-skin.** The result should look as if one design team made the whole deck, while each slide keeps a layout suited to its own content.

Never:
- place whole-slide screenshots into a new deck as a substitute for editing;
- force every page into identical rows of bars or identical card grids;
- delete, redraw, replace, or materially alter a teammate's icons/illustrations unless the user explicitly authorises it;
- change research claims, data, source attribution, or interview meaning just to improve the design;
- use decorative shapes that compete with the content.

## Visual language

### Overall mood
- Clean, approachable, lightly playful, and presentation-ready.
- Editorial/consulting style rather than a corporate template full of rigid bands.
- Generous whitespace; clear visual hierarchy; restrained colour.
- Use illustrations and organic visual cues where they add meaning. Do not replace them with arbitrary geometric collages.

### Canvas and typography
- Default canvas: widescreen 16:9.
- Use Aptos / Aptos Display or a similarly clear sans-serif family consistently.
- Use a consistent title position, size, weight, and colour across content slides.
- Suggested hierarchy:
  - Main slide title: 30–36 pt, bold.
  - Subtitle/question: 19–24 pt.
  - Main body or chart labels: 18–24 pt where feasible.
  - Source notes: 10–12 pt only when they are genuinely secondary; do not shrink substantive content to fit.
- Avoid long all-caps headings. Use concise section labels such as `Q4 / SETBACKS`.
- Check text at presentation size, not only while zoomed in on a laptop.

### Palette
Use a pale, calm background with a dark navy text system and a few soft accents. Suggested starting palette (adjust to sample the user's approved deck):
- Deep navy: `#244B68`
- Pale blue background: `#F2F7FB`
- Mid blue: `#4D9FD0`
- Coral: `#EF806F`
- Mint: `#69B99F`
- Warm yellow: `#E4B84F`
- Soft lavender: `#A894D5`
- Muted grey-blue: `#71899A`

Rules:
- Navy carries titles and primary text.
- Use one dominant accent and at most two supporting accents on a page.
- Use the multi-colour accents as small signals (dots, short rules, labels), not as five competing blocks.
- Keep contrast high enough for projection.

### Shapes and layout
- Prefer open layouts, whitespace, simple panels, and occasional soft rounded shapes.
- Use cards only when they genuinely group information. Avoid a wall of equal cards.
- Avoid thick full-width bars and repeated pill-shaped labels.
- Decorative dots may remain as empty colour accents; do not put arbitrary initials/numbers inside them.
- Keep independent sections visually separate. Do not make member cards hang halfway over a main profile card.
- Align columns and baselines precisely; use spacing rather than heavy borders to separate content.

## Slide integration workflow

1. **Inventory the source deck**
   - Identify slide order, dimensions, title text, body text, charts, pictures, icons, source notes, and page numbers.
   - Distinguish native PowerPoint charts/shapes from raster images.
   - Identify which assets the user explicitly says must remain unchanged.

2. **Establish the master visual language**
   - Sample the approved/strongest slides for title treatment, background, typography, palette, spacing, and footer conventions.
   - Define a small reusable set of title, section-label, source-note, and accent treatments.
   - Do not impose one identical content layout on all slides.

3. **Integrate slide by slide**
   - Preserve each contributor's information architecture if it already works.
   - Standardise title position, font, size, colour, section label, page number, source-note treatment, and spacing.
   - Adapt the content layout to the data: comparison, timeline, process, relationship, or single key statistic.
   - Preserve original icons and illustrations. Reposition or resize only when needed to fit the shared visual system; do not recolour or redraw without permission.
   - Keep charts editable where possible. If the source is a raster chart, preserve it as an image object unless the user asks for a redraw.

4. **Make charts communicate clearly**
   - Do not plot unrelated measures on one axis merely because they are percentages.
   - Separate adoption levels from task-performance changes when their meanings differ.
   - Label the metric, unit, time period, and source.
   - Use direct labels where possible; avoid legends that force the audience to decode the chart.
   - Keep positive and negative effects visually distinct and clearly signed.
   - Do not silently change source values or roundings.

5. **Align slides with the spoken script**
   - Match slide claims and numbers to the current script.
   - If a figure appears on the slide but is not spoken, decide whether it is useful supporting context or unnecessary clutter.
   - Do not add data to the script just to justify a chart.
   - Preserve the user's stated time limit and speaker's English ability; use short, speakable sentences when requested.

6. **References and Harvard style**
   - Follow the exact institutional Harvard guide supplied by the user; local university variants take precedence over generic Harvard conventions.
   - Use author–date in-text citations consistently, e.g. `(Smith, 2024)` or `Smith et al. (2024)` where the guide permits.
   - For four or more authors, use first author plus `et al.` in-text if the supplied guide specifies this; list all authors in the reference list if required.
   - Alphabetise the reference list by author/organisation.
   - Check author names, year, title, publication, volume/issue, page range, DOI/URL, and access date against the actual source.
   - Use DOI where available; do not invent missing bibliographic details.
   - Keep references readable. Split a dense reference list across two slides rather than shrinking the font excessively.
   - Ensure every in-text citation has a matching reference entry and every listed source is used.
   - Treat interviews as primary sources and format them according to the supplied guide; if interview date or details are missing, flag them instead of inventing them.

7. **Quality assurance**
   - Render every slide to images and inspect the whole-deck montage plus individual dense slides.
   - Check for text overlap, clipped labels, duplicate headings, stale chart categories, repeated source notes, and page-number inconsistencies.
   - Verify slide dimensions and slide count.
   - Confirm charts, text, and shapes remain editable. Do not claim editability without checking the objects.
   - Compare protected slides before and after; if the user asked to change only selected pages, ensure all other pages remain unchanged.
   - Deliver the editable `.pptx`; provide a PDF preview only as a supplement.

## Content integrity rules

- Preserve original facts, claims, interview wording, figures, and source attribution unless the user explicitly requests substantive editing.
- Distinguish verified source facts from assumptions or editorial suggestions.
- If a source is ambiguous or a citation cannot be verified, flag it clearly.
- Never silently “correct” data by substituting a different report or year. Explain the discrepancy and show the evidence.
- Do not fabricate company structure, interview details, data, or research results.

## File naming

Use semantic versioning only:
- `ProjectName_v1.0.0.pptx`
- `ProjectName_v1.0.1.pptx` for a small revision
- `ProjectName_v1.1.0.pptx` for a larger feature/content revision

Do not use names such as `final`, `final-final`, `latest`, `终稿`, or `最终版`.

## Delivery checklist

Before handing over, confirm:
- [ ] It is a real editable PowerPoint, not a deck of full-slide screenshots.
- [ ] Titles, typography, palette, page numbers, and source notes are consistent.
- [ ] Layouts are adapted to each slide's content; no repetitive bar/card template.
- [ ] Original teammate icons and illustrations are preserved as requested.
- [ ] Charts are correctly labelled and do not mix incompatible metrics.
- [ ] Slide content matches the current speaker script.
- [ ] Harvard citations and reference entries follow the user's institutional guide.
- [ ] All slides have been rendered and visually checked.
- [ ] Protected pages are unchanged.
- [ ] Filename uses `vX.Y.Z`.
