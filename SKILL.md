---
name: master-slide-skill
description: Design and produce authentic, problem-specific, hackathon-ready presentations with a strict narrative plan, a deliberate light/neobrutalist/editorial visual system, readable slide density, meaningful diagrams and data graphics, restrained motion, editable PowerPoint output, and evidence-based visual QA. Use when creating a new pitch, hackathon/demo-day deck, product presentation, technical proposal, project showcase, or when converting supplied notes, research, screenshots, or an existing deck into a polished .pptx.
compatibility: OpenCode and other coding agents that can read Agent Skills / SKILL.md. Requires local file access and an available PowerPoint generation route; adapt commands to the active agent. Browser-based HTML preview is recommended but is not the final deliverable unless explicitly requested.
metadata:
  author: Aakif / personalized workflow
  version: "1.0.0"
  output: editable-pptx
  primary_use: hackathons-and-product-demos
---

# MASTER SLIDE SKILL

## A practical design-and-production constitution for distinctive, accurate, editable presentations

**Mission:** Help an AI coding agent turn a real problem statement and the team's actual work into a crisp, persuasive, visually authored presentation, then deliver a verified `.pptx` file. The skill is a framework for the agent; it is not a finished deck, a fixed template, or permission to invent missing product details.

**Core principle:** The slide deck must look like a thoughtful human designer shaped the story, typography, diagrams, evidence, and rhythm. Avoid generic AI presentation patterns. Distinction comes from specificity, not from adding more decoration.

**Default context:** Hackathon, demo day, product pitch, engineering showcase, student innovation challenge, prototype review, and early-stage product presentations. The skill remains usable for other presentation types by adapting the narrative and density policy.

**Important output distinction:** HTML, CSS, SVG, and browser previews are authoring and validation tools. Unless explicitly requested otherwise, the final deliverable is a real PowerPoint `.pptx`, with text, shapes, charts, and diagrams editable wherever feasible. A visually polished HTML deck is not the same as an editable PowerPoint file.

---

# CONTENTS

1. Activation and operating contract
2. Priority and conflict resolution
3. Input discovery and focused questions
4. Research and source discipline
5. Hackathon narrative architecture
6. Slide-count and density policy
7. Copywriting and authenticity rules
8. Style discovery and theme library
9. Color-system rules
10. Typography system
11. Composition, grid, and spacing
12. Layout library and slide grammar
13. Infographics, diagrams, and charts
14. Product screenshots and visual assets
15. Motion, builds, and live-demo behavior
16. Editable PPTX architecture and export strategy
17. Mobile-friendly control and remote presentation
18. Quality assurance and validation
19. Iteration and change control
20. Delivery contract
21. Reusable intake schema
22. Hackathon deck outline example
23. Final preflight checklist
24. Reference map and attribution

---

# 1. ACTIVATION AND OPERATING CONTRACT

## 1.1 Trigger this skill when

- Creating a hackathon, demo-day, startup/product pitch, project showcase, or technical proposal deck.
- Turning a problem statement, README, research notes, diagrams, datasets, screenshots, or rough outline into slides.
- Reworking an AI-looking or generic presentation into a distinctive, purposeful deck.
- Designing a deck in HTML/SVG as an intermediate format, then exporting to PowerPoint.
- Producing a presentation that will be presented from a laptop but may need remote navigation from a phone.

## 1.2 Modes

Choose exactly one primary mode, plus optional supporting modes:

- **Plan:** research, define the audience, build the story, and create a slide-by-slide outline.
- **Build:** create the full deck from a sufficiently clear brief.
- **Convert:** use an existing deck or document as source material while preserving relevant facts.
- **Refine:** diagnose and fix an existing deck without casually changing approved content.
- **Audit:** inspect the deck, report evidence-backed defects, and propose prioritized fixes.

## 1.3 Skill behavior

- This file is policy, not a generator. Do not claim it has created, rendered, opened, or checked an artifact unless that action was performed.
- Inspect the available repository, files, installed packages, and tool capabilities before deciding the production route.
- Prefer working from real source material. If something is missing but non-blocking, declare a reasonable assumption and proceed. Ask a concise question only if the answer materially changes the deck.
- Do not force every available feature, animation, chart type, style, or library into every presentation.
- The objective is a coherent, persuasive, accurate deck, not maximum complexity.

---

# 2. PRIORITY AND CONFLICT RESOLUTION

Resolve conflicts in this order:

1. User's explicit brief, competition requirements, judging rubric, truthfulness, privacy, and safety.
2. Factual accuracy and traceable evidence.
3. Audience comprehension, persuasive story, and spoken-presentation needs.
4. Legibility, accessibility, and visual hierarchy.
5. Chosen theme's design system and the user's supplied brand assets.
6. PowerPoint compatibility and output reliability.
7. Optional decorative effects and personal taste.

A visual flourish never overrides correctness, clarity, or readable text. A theme preset never overrides the user's explicit color constraints. A beautiful but fabricated chart is a failure. A browser animation must not be presented as a capability of a static `.pptx` unless the export preserves it and that behavior has been verified.

---

# 3. INPUT DISCOVERY AND FOCUSED QUESTIONS

## 3.1 Read what is already available first

Before asking questions, inspect supplied files, conversation details, problem statements, repo README/source code, screenshots, branding, and any stated rules. Never ask the user for data they have already supplied.

## 3.2 Minimum brief

Determine the following. Use explicit known information first; ask only for high-impact gaps.

1. **Occasion and audience:** hackathon, demo day, judging panel, investor, technical reviewer, school showcase, or general audience.
2. **Problem statement:** exact challenge wording, who experiences the problem, and why it matters.
3. **Project truth:** name, current state, shipped features, prototype status, architecture, real demo, and what is only planned.
4. **Judging requirements:** rubric, mandatory sections, time limit, slide limit, required disclosures, and citation rules.
5. **Narrative mode:** pitch-first, demo-first, evidence-first, or technical-first.
6. **Content availability:** notes, source documents, links, project repository, screenshots, measured results, user research, or no content yet.
7. **Visual direction:** select from Section 8 or allow three visual previews. Respect any explicit request for light, non-neon, neo-brutalist or editorial aesthetics.
8. **Delivery constraints:** target `.pptx`, PowerPoint version if known, aspect ratio, offline expectations, phone-based remote navigation, and font restrictions.

## 3.3 Ask efficiently

- For a complete brief, proceed without another questionnaire.
- For an incomplete but actionable brief, ask at most three high-impact questions together.
- For a vague brief, ask one conversational question at a time only when the answer changes the direction substantially.
- Suggested short intake, only when required:
  - What is the exact problem statement and who are the judges/audience?
  - How long do you have to present, and is there a maximum slide count?
  - What is actually built and demonstrable today, versus planned?
- If a file or repo has these answers, extract them rather than re-asking.

## 3.4 Lock the brief before visual execution

Create a short `deck-brief.md` (or equivalent notes) recording:

- Objective and audience.
- One-sentence core claim.
- Presentation time and slide cap.
- Chosen narrative arc.
- Known facts and sources.
- Unverified assumptions.
- Required content.
- Selected theme and exclusions.
- Target output and verification method.

This is an internal working artifact unless the user asks to receive it.

---

# 4. RESEARCH AND SOURCE DISCIPLINE

## 4.1 Research only to answer a presentation need

When the pitch depends on current information, niche technical claims, market size, competitor behavior, relevant policies, standards, or external statistics, research those claims with authoritative and recent sources. Prefer primary sources: official datasets, papers, government or standards bodies, technical documentation, product docs, and first-party announcements.

## 4.2 Never invent evidence

Do not fabricate or embellish:

- User counts, interviews, pilots, customer logos, testimonials, adoption, revenue, savings, accuracy, latency, cost, benchmark scores, market size, TAM/SAM/SOM, traction, partnerships, grants, certifications, or deployment status.
- A citation, publication, dataset, quote, or benchmark.
- Product capabilities that do not exist in the code or cannot be demonstrated.

If a metric is not available, either omit it or label it clearly as a target, estimate, hypothesis, or illustrative example. Never make an illustrative number look measured.

## 4.3 Maintain a claim ledger

Track high-impact claims in a compact table:

| Claim | Value/wording | Source or evidence | Status | Slide |
|---|---|---|---|---|

Status must be one of `verified`, `user-provided`, `estimate`, `hypothesis`, `planned`, or `unknown`.

- `verified` means the agent directly checked the supporting source.
- `user-provided` means the user supplied it but it was not independently confirmed.
- `estimate` must show the method or assumptions.
- `hypothesis` is a proposition to validate, not a result.
- `planned` is not yet implemented.
- `unknown` is a stop sign for factual assertion.

Use short source footnotes on slides where claims require attribution. Place full references in a final references slide or speaker notes when appropriate. Do not add a reference slide just to display sources that were never used.

## 4.4 Cite without ruining the design

- Add short, readable source labels close to the claim, chart, or data graphic.
- Store full URL/title/date/accessed date in the working claim ledger or an appendix/reference slide.
- Do not use tiny illegible footnotes as a workaround for unsupported claims.
- Distinguish direct source facts from the team's interpretation.

---

# 5. HACKATHON NARRATIVE ARCHITECTURE

A hackathon deck must help judges understand the problem, believe the solution is relevant, see that the team can deliver it, and remember why it matters. Do not treat a slide deck as a product brochure.

## 5.1 Default story arc

Adapt the arc to the problem and rubric rather than blindly using a fixed template:

1. **Hook / thesis:** one memorable problem insight, user tension, or outcome. Avoid empty slogans.
2. **Problem:** specific person, task, context, and failure/pain. Keep it observable.
3. **Why now / stakes:** consequence, urgency, or gap with evidence if available.
4. **Solution:** clear product proposition and the one key change it makes.
5. **How it works:** a diagram of the real mechanism, not a pile of technology logos.
6. **Demo / workflow:** show the core user journey or the highest-value product moment.
7. **Differentiation:** compare alternatives on a fair, relevant basis.
8. **Evidence / validation:** tests, measured outcomes, user feedback, or explicit validation plan.
9. **Feasibility / architecture:** only the implementation details needed to establish credibility.
10. **Impact / roadmap / ask:** what changes, what remains, next milestone, or the concrete request.

Not every deck needs all ten. Combine or drop sections when the rubric, duration, and content warrant it. Never add filler slides to match the default arc.

## 5.2 Technical truth in solution slides

- Separate **built**, **working prototype**, **mocked**, **planned**, and **future research**.
- Show a genuine screenshot or code-derived architecture only when it communicates relevant proof.
- Use an architecture diagram that matches available code/configuration. Never infer a cloud service from a technology name alone.
- Keep implementation details aligned with judge needs: feasibility, reliability, privacy, latency, deployment, cost, or maintainability only when relevant.
- Show failure handling, data flow, and key dependencies if they materially affect the solution's credibility.

## 5.3 Demonstration story

Pick one journey that shows the core value. The recommended sequence:

- **Input:** what the user starts with.
- **Action:** what they do.
- **System behavior:** what the product computes, retrieves, or changes.
- **Outcome:** what the user gets and why it matters.
- **Proof:** real UI, output, or measured behavior.

If the demo may fail live, create an honest fallback screenshot or recorded walkthrough. Do not call the fallback a live product run. Keep a clear switch from slides to the actual product and back.

## 5.4 Differentiation and competitors

- Compare on criteria relevant to the user problem, not cherry-picked checkmarks.
- Separate confirmed competitor facts from estimates or inferences.
- Use a comparison matrix only when direct comparisons matter; otherwise show one meaningful difference with evidence.
- Do not write “no competitors” without research. Existing substitutes include spreadsheets, manual workflows, incumbent tools, and doing nothing.

---

# 6. SLIDE-COUNT AND DENSITY POLICY

## 6.1 Default slide cap

- **Default target:** 7–9 core slides.
- **Default maximum:** 10 slides, unless the user or competition explicitly permits more.
- **5–6 slides:** a short pitch with a strict time limit.
- **7–9 slides:** default hackathon/demo-day deck.
- **10 slides:** upper limit for the default compact deck; use only if each slide has a distinct job.
- **More than 10:** allowed only when explicitly requested or a rubric demands it. Explain the reason and use an appendix when useful.

Do not include a title slide, thank-you slide, or references slide in a way that accidentally exceeds the stated hard cap. Confirm whether the organizer counts appendices or backup slides.

## 6.2 Time-to-slide heuristic

Use this as a planning heuristic, not a universal law:

- 3 minutes: roughly 4–6 content-bearing slides.
- 5 minutes: roughly 6–8 slides.
- 7 minutes: roughly 7–9 slides.
- 10 minutes: roughly 8–10 slides.

Actual counts depend on speaking speed, live demo duration, judge interruptions, and mandatory rubric sections. Allocate a separate time block for a live demo. Target using no more than about 85–90% of the available time in the planned run-through to preserve breathing room.

## 6.3 Every slide needs one job

For every slide, write:

- **Audience question:** what the audience needs to understand at this point.
- **Takeaway:** one sentence that answers it.
- **Evidence/visual:** what makes the takeaway credible or clear.
- **Speaker support:** what is said aloud but need not be printed on the slide.
- **Transition:** how it leads to the next slide.

If two slides do the same job, combine them or distinguish the purpose. If a slide has no clear takeaway, remove it.

## 6.4 Density rules

**Speaking deck (default):**
- One major idea per slide.
- Usually one headline, one visual argument, and at most 1–3 supporting bullets.
- Do not put the speaker's entire script on the slide.
- As a typical target, keep slide-facing copy around 20–40 words, excluding source labels and unavoidable data labels. This is a guideline; complex technical diagrams may need more concise labels.

**Reading deck:**
- More explanatory copy is acceptable, but use hierarchy, structured grids, annotations, and carefully composed charts.
- Split any page that needs shrinking below comfortable room-readable type.

**Never:** shrink all text to fit, cover empty space with filler, use a paragraph where a diagram makes the mechanism clearer, or turn every bullet into a separate rounded card.

## 6.5 Slide-outline gate

Before final rendering, produce and internally check a slide map:

| # | Section | Audience question | One-sentence takeaway | Content | Primary visual | Time |
|---|---|---|---|---|---|---|

Ensure the story covers the judging rubric, the narrative escalates, slide count is within bounds, and each visual is appropriate for the claim. If the brief is clear, proceed directly; do not force a needless user approval step. For high-stakes design choices, offer three title-slide or style previews first.

---

# 7. COPYWRITING AND AUTHENTICITY RULES

## 7.1 Headlines are conclusions

Prefer headline statements that express the conclusion, not category labels.

- Weak: `Problem`, `Solution`, `Architecture`, `Market`.
- Stronger: `Small clinics lose time reconciling records by hand` (only if supported).
- Stronger: `One shared intake flow removes duplicate entry` (only if the product actually does this).

Do not write stronger wording than the evidence allows.

## 7.2 Natural, credible language

Avoid stereotypical AI marketing phrases unless the project's authentic voice genuinely uses them: “revolutionary,” “game-changing,” “seamless,” “unlock the power,” “redefine the future,” “cutting-edge,” “transformative,” “one-stop solution,” “in today's fast-paced world,” and unsupported superlatives such as “best” or “first.”

Prefer concrete verbs and observable outcomes. A technical judge should be able to ask “how do you know?” and receive a defensible answer.

## 7.3 Authenticity is not a filter

To avoid the “generated template” feeling:

- Use precise details from the actual problem, target user, product flow, and repo.
- Let real screenshots, domain-specific diagrams, and meaningful data drive composition.
- Avoid using the same title + subtitle + three-card grid on every slide.
- Use one distinctive visual motif derived from the project (e.g. the shape of a workflow, a dataset structure, a physical context, or a meaningful repeated line/marker).
- Avoid decorative fake UI, invented dashboards, random stock photography, arbitrary gradients, and icon collections without a reason.
- Use asymmetry, deliberate alignment, strong scale contrast, whitespace, and plain backgrounds rather than decoration everywhere.
- Include a grounded team or build detail if relevant; never fabricate a personal story or quote.
- Do not try to simulate handwritten human error, fake annotations, or fake data to make an AI-produced deck appear human-made. Make it genuinely specific and well-designed.

---

# 8. STYLE DISCOVERY AND THEME LIBRARY

## 8.1 Select one primary style system

Choose a single primary design language for a given deck. A second technique may support it only when the relationship is clear. Do not mix multiple presets slide-by-slide without a coherent art direction.

If the brief is underspecified and time permits, generate **three distinct cover previews** using the actual title/topic: one restrained option, one expressive option, and one thoughtful wildcard. Make them visually different, not just different accent colors. Pick one direction and keep it consistent throughout the deck.

## 8.2 Theme cards

Use the following theme library as starting points, not as mandatory templates. All palettes below are proposed design tokens and must be checked for contrast in the final context.

### Theme A — Warm Neo-Brutalist Studio (recommended default)

**Character:** direct, confident, tactile, graphic, contemporary, light.

- Background: warm paper `#F6F1E8`.
- Main ink: deep warm charcoal `#24211D`.
- Primary accent: tomato/coral `#E65B45`.
- Secondary accent: mustard `#D9A928` (use sparingly, not alongside multiple loud accents).
- Supporting surface: pale sage `#DDE5D7`.
- Rule/border: `#24211D`.
- Typography: expressive editorial serif headlines paired with a sturdy, highly legible sans-serif body; optional mono labels for metadata.
- Motifs: thick editorial rules, offset hard shadows, uneven but intentional modules, oversized numerals, cutout-style diagrams, underlined labels.
- Avoid: neon yellow overload, rounded app cards, decorative sticker clutter, exaggerated shadows on every object.
- Best for: hackathon projects that should feel designed, energetic, and grounded rather than corporate.

### Theme B — Editorial Paper & Ink

**Character:** precise, literary, calm, sophisticated, credible.

- Background: `#F7F4ED`.
- Main ink: `#211F1B`.
- Accent: muted oxblood `#8F3F3B`.
- Secondary neutral: warm stone `#D5CEC2`.
- Optional accent: olive `#737A55`.
- Typography: high-character serif display with a neutral sans-serif body; mono or small caps for labels only.
- Motifs: magazine columns, hairline rules, large title typography, quiet image captions, restrained asymmetry.
- Best for: research-led problem narratives, social impact, storytelling, reflective pitches.
- Avoid: making every slide look like a magazine cover or using too many tiny captions.

### Theme C — Swiss Grid Light

**Character:** objective, structured, technical, confident.

- Background: clean warm white `#FBFAF7`.
- Ink: `#25282B`.
- Primary accent: cobalt `#3159B8`.
- Secondary neutral: `#D8D9D5`.
- Optional support: brick red `#B84A3D` only when the story truly needs a second semantic accent.
- Typography: modern grotesk sans-serif, strong size contrast, highly aligned grid, limited decoration.
- Motifs: fixed column grid, rules, data labels, geometric charts, asymmetrical balance.
- Best for: architecture, technical feasibility, evidence, structured comparisons.
- Avoid: making every slide a sterile table, using tiny text, or overusing all-caps metadata.

### Theme D — Product Editorial / Warm Signal

**Character:** product-first, clear, friendly but not childish.

- Background: `#F5F3EE`.
- Ink: `#262822`.
- Accent: softened teal `#3E7772`.
- Secondary accent: apricot `#E5AA80`.
- Surface: `#E5E3DA`.
- Typography: distinctive sans headline with an editorial serif for selected pull quotes or single-word emphasis; body in a stable sans.
- Motifs: authentic UI screenshots, workflow steps, before/after pairs, clear action labels.
- Best for: product demos, workflow tools, apps and human-centered projects.
- Avoid: fake screenshots, huge claims, and a generic bento-grid on every slide.

### Theme E — Bauhaus Signal

**Character:** constructive, geometric, playful with discipline.

- Background: ivory `#F5F0E6`.
- Ink: `#232323`.
- Accent: vermilion `#D64535`.
- Supporting accent: ultramarine `#3157A3`.
- Secondary support: ochre `#D4A52B`.
- Typography: geometric sans-serif for most content; optional robust serif for a title only if the composition supports it.
- Motifs: circles, bars, squares, simple geometry, diagrammatic relationships, a strict grid.
- Best for: maker projects, physical computing, creative engineering, visual systems.
- Avoid: using all primary colors on every slide or turning decoration into an infographic with no information.

### Theme F — Soft Technical / Field Notes

**Character:** practical, thoughtful, field-tested, human.

- Background: `#F2F3ED`.
- Ink: `#2A302D`.
- Accent: forest `#416C59`.
- Support: clay `#C87C5A`.
- Neutral: `#D9DED4`.
- Typography: sturdy sans for body and a modest editorial serif for main statements.
- Motifs: annotated workflow, numbered evidence points, quiet grids, selective line illustration.
- Best for: sustainability, community projects, field research, healthcare or education tools when the context fits.
- Avoid: nature clichés and pretending an untested prototype is field-tested.

### Theme G — Light Monochrome with One Signal

**Character:** highly controlled, sharp, minimal, serious.

- Background: white `#FFFFFF` or warm white `#F8F7F3`.
- Ink: `#222222`.
- Border: `#2B2B2B`.
- One accent: choose a single saturated but non-neon color aligned to the subject (examples: brick `#B84A3D`, cobalt `#3159B8`, forest `#416C59`).
- Typography: one excellent sans family with clear weight hierarchy; optional display serif if it adds a real editorial idea.
- Motifs: large type, strong rules, simple labels, striking negative space.
- Best for: a very compact pitch where content must speak clearly.
- Avoid: pure-black heavy slabs on every slide, lifeless repetition, or thin low-contrast grey.

### Theme H — Paper Cut / Handmade Diagram

**Character:** explanatory, approachable, crafted.

- Background: `#F6F1E7`.
- Ink: `#292720`.
- Accent: muted terracotta `#BF6449`.
- Support: sage `#B8C7B0` and pale ochre `#E0C87A` in limited roles.
- Typography: highly legible sans body, hand-drawn-looking elements only as SVG line art (never for long text).
- Motifs: layered paper-like shapes, annotated cutouts, workflow arrows, carefully drawn figures.
- Best for: explaining complex mechanisms or multidisciplinary systems.
- Avoid: roughness that harms alignment, clip-art, noisy texture, or using illustrative metaphors that distort the actual system.

## 8.3 Style matching rules

Match **tone and audience first**, then topic. A technical hackathon deck can still be editorial or neo-brutalist if the chosen visual system clarifies the subject.

- If the user explicitly chooses a style, honor it unless it makes the deck unreadable or incompatible with a hard requirement.
- If there is an existing product brand kit, inspect it before choosing new tokens.
- If the user says no dark themes, do not generate dark-background options.
- If the user says no neon/cyberpunk, exclude neon, glow, purple-pink gradients, and terminal-green clichés.
- If no choice is supplied, prefer Theme A (Warm Neo-Brutalist Studio) for general hackathon work, but adapt it to the problem.

---

# 9. COLOR-SYSTEM RULES

1. Use one main background, one main ink, one primary accent, and at most one or two support colors. A palette is not a mandate to use every color on every page.
2. Use semantic roles: `background`, `surface`, `ink`, `muted-ink`, `border`, `accent`, `accent-foreground`, `secondary-accent`, `positive`, `warning`, `negative`, and `data-series-*` when required.
3. Keep most slides on a light ground by default. Avoid near-black/black full-bleed slides unless explicitly requested and justified by the narrative.
4. Never default to neon, cyberpunk, electric purple, or cyan-magenta gradients. Avoid generic AI-coded visual shortcuts.
5. Don't use gradients as a substitute for an idea. Flat colors, paper tones, solid geometry, and texture used with restraint are preferred.
6. Check actual foreground/background combinations. For normal-sized text, aim for at least 4.5:1 contrast; for large text, at least 3:1 as a useful accessibility baseline. Do not assume a visually strong color is readable.
7. Do not communicate category or status by color alone. Add labels, shapes, patterns, or direct annotations.
8. For data graphics, use colorblind-aware distinctions and direct labels whenever possible. If using multiple series, keep each series mapping stable across all slides.
9. Keep chart backgrounds simple; avoid 3D effects, gradients, ornamental borders, and excessive gridlines.
10. Record the chosen tokens before applying them. Avoid ad hoc new hex values slide-by-slide.

---

# 10. TYPOGRAPHY SYSTEM

Typography is the key source of visual identity. Select fonts by voice, readability, availability, language coverage, embedding/export behavior, and licensing—not hype.

## 10.1 Role system

Choose a restrained system, normally one or two families plus an optional mono family for labels:

- **Display/headline:** expressive serif or distinctive grotesk.
- **Subhead:** same family or compatible second family.
- **Body:** high-legibility sans-serif.
- **Numeric/data:** tabular numerals or a stable sans/mono if it helps comparisons.
- **Metadata/source labels:** optional mono or small caps, used sparingly.

Do not use a different font for every slide. Use the same hierarchy throughout the deck.

## 10.2 Font direction ideas

These are candidates to evaluate, not mandatory dependencies. Verify that the chosen font is available and licensed for the intended use; provide a sensible PowerPoint fallback if not embedded.

**Editorial serif headlines:** Newsreader, Source Serif 4, Literata, DM Serif Display, Fraunces, Libre Baskerville.

**Distinctive sans/grotesk:** Manrope, IBM Plex Sans, Source Sans 3, Plus Jakarta Sans, Public Sans, Geist, Space Grotesk (use selectively rather than as a universal default).

**Mono / technical labels:** IBM Plex Mono, JetBrains Mono, Source Code Pro.

**Practical pairings:**
- Newsreader + Manrope + IBM Plex Mono.
- Source Serif 4 + Source Sans 3.
- DM Serif Display + Manrope.
- Fraunces + IBM Plex Sans.
- Manrope + IBM Plex Mono for Swiss / technical work.
- Public Sans alone with deliberate weight/scale contrast for very clean decks.

Do not claim these fonts are installed. Inspect available fonts or choose a delivery-safe fallback. If delivering an editable `.pptx`, warn when the audience may not have the chosen typeface; consider embedding fonts only when the license and tooling permit.

## 10.3 Type hierarchy: widescreen 16:9

Use these ranges as starting points for a 13.333 × 7.5 inch slide, then validate at presentation size:

- Cover title: approximately 32–48 pt; larger only if it stays deliberate and fits cleanly.
- Main takeaway/headline: approximately 28–36 pt.
- Subheading: approximately 20–26 pt.
- Body/supporting text: approximately 18–24 pt for room presentation.
- Chart labels and diagram labels: preferably 14–18 pt; below 14 pt only for unavoidable source metadata, not for key content.
- Footnotes: normally 10–12 pt, with enough contrast and a clear reading purpose; do not hide key evidence here.

These are not mechanical constants. Content, font x-height, language, typeface weight, projection conditions, and room size affect legibility. Prefer splitting a slide to shrinking text. A slide title that wraps awkwardly should first be rewritten, not blindly reduced.

## 10.4 Typographic rules

- Use at most three type roles; more than three font families is rarely justified.
- Headlines state a claim and usually align left unless the chosen art direction gives a compelling reason otherwise.
- Use expressive weight contrast: large titles can be lighter or more emphatic, but body and small labels must remain readable.
- Keep paragraphs short. Use line length, line spacing, and blank space to create rhythm.
- All-caps and tracking are for brief labels, not long body copy.
- Use bold for selective emphasis rather than making entire paragraphs bold.
- Avoid fake small caps if they degrade readability.
- Use actual quotation marks, dashes, and punctuation consistently.
- Validate line breaks in the final exported deck, not only in a browser preview.

---

# 11. COMPOSITION, GRID, AND SPACING

## 11.1 Stage and grid

- Default to 16:9 widescreen unless the organizer specifies otherwise.
- Define a consistent outer margin, columns, gutters, and baseline before laying out slides.
- Use aligned edges and a purposeful grid, but allow controlled asymmetry when it supports the content.
- Avoid placing content in slide edges or under PowerPoint controls; keep important content within a safe area.
- Use negative space as a structural element, not as a blank that must be filled.

## 11.2 Neo-brutalist rules

When using a neo-brutalist theme:

- Use confident borders, solid blocks, large type, sharp edges, and occasional offset shadows.
- Keep the palette disciplined and light; avoid black-heavy backgrounds and neon accents by default.
- Choose purposeful asymmetry, not random misalignment.
- Give each outlined shape a structural or semantic role.
- Limit hard shadows to one or two focal moments; don't shadow every object.
- Use square/rectangular modules instead of rounding every content block.
- Preserve professional information hierarchy. Neo-brutalism is not permission to make dense or chaotic slides.

## 11.3 Cards are optional

Do not automatically place each bullet into a card. Use:

- Large claim + diagram.
- Side-by-side comparison.
- Full-width screenshot with one annotation.
- Timeline or staged sequence.
- Editorial text column + evidence image.
- Large metric + source and context.
- Dense architecture map when technical detail warrants it.
- A single chart with a direct takeaway.

Use cards only when they indicate meaningful grouping, comparison, status, or interaction.

## 11.4 Alignment and rhythm

- Align text blocks to common axes and keep consistent internal padding.
- Define consistent vertical spacing between title, content, and source.
- Alternate slide rhythms deliberately: title/statement, diagram, screenshot, comparison, metric, closing.
- Do not repeat the same three-column card layout on every slide.
- A slide may be very simple if its single idea deserves the space.

---

# 12. LAYOUT LIBRARY AND SLIDE GRAMMAR

Select layouts based on the communication job. The examples below are archetypes, not a prescribed slide sequence.

1. **Thesis / cover:** project title, precise one-line promise, team/context only if available.
2. **Tension / problem:** user/task/context + failure point or evidence.
3. **Before / after:** show the current workflow beside the proposed workflow.
4. **Solution diagram:** 3–5 numbered steps, with labeled actions and outcomes.
5. **User journey:** input → action → processing → result, with real product evidence.
6. **Product proof:** one high-quality screenshot with 1–3 clearly numbered annotations.
7. **System architecture:** layered or flow diagram based on real components and arrows labeled by what moves.
8. **Comparison:** compare meaningful alternatives on a small set of criteria; show evidence status.
9. **Impact metric:** one or two truthful numbers, units, baseline, timeframe, and source.
10. **Experiment / validation:** hypothesis, test method, sample/conditions, result, limitation.
11. **Roadmap:** no more than a few near-term milestones; distinguish current from future work.
12. **Closing / ask:** one memorable takeaway, requested action, next step, or demo prompt.
13. **Reference / appendix:** source detail, technical backup, risk register, extra charts, only if needed.

Avoid opening with an agenda slide unless the event format or audience benefits from it. The first slide after the cover should deliver substance quickly.

---

# 13. INFOGRAPHICS, DIAGRAMS, AND CHARTS

The visual must make the claim easier to understand. Do not use infographics only to decorate the page.

## 13.1 Diagram selection

| Information | Recommended visual |
|---|---|
| Step-by-step process | Numbered flow or timeline with action verbs |
| System architecture | Layered component diagram with labeled interfaces/data flows |
| User pain and product improvement | Before/after workflow or friction map |
| Trade-offs | Side-by-side comparison, matrix, or decision tree |
| Time-based milestones | Timeline with current/next/future explicitly marked |
| Relationships / actors | Entity map, swimlane, ecosystem diagram |
| Quantitative comparison | Sorted bars, dumbbell chart, slope chart, or small multiples |
| Trend over time | Line chart with time axis, metric and units |
| Part-to-whole | Stacked bar or a simple pie/donut only when categories form a true whole |
| Binary state or checklist | Table with text/icon states, not color alone |
| Complex mechanism | Custom SVG or editable PowerPoint shapes with labeled arrows |
| Physical product / interface | Real photo or screenshot with focused annotations |

## 13.2 Chart truth and readability

- Use the correct chart for the data and the claim.
- Preserve zero baselines for bar charts when appropriate; clearly flag intentional nonzero axes.
- Label units, time ranges, samples, and comparisons.
- Do not imply correlation is causation.
- Avoid 3D charts, decorative legends when direct labels work, and excessive gridlines.
- Use real data or explicitly marked illustrative data.
- When no meaningful data exists, use a qualitative workflow/diagram instead of fake metrics.
- Include data sources directly or in a readable source note.

## 13.3 Diagram semantics

- Every arrow represents a relationship or action. Label important arrows with verbs such as `sends`, `validates`, `stores`, `returns`, or `triggers`.
- Distinguish components from data, actors, states, and outcomes with both shape and label.
- Use consistent notation across the deck.
- Include a legend only when the notation cannot be understood directly.
- Draw the mechanism rather than just putting component names inside boxes.
- Diagram claims must match actual implementation; label planned components as planned.

## 13.4 Avoid infographic overload

One slide should normally have one primary visual argument. A diagram can have subcomponents, but should not compete with two unrelated charts, a screenshot, and multiple callout panels. Simplify, split, or move detail to speaker notes/appendix.

---

# 14. PRODUCT SCREENSHOTS AND VISUAL ASSETS

## 14.1 Use genuine evidence first

Preferred order:

1. Screenshots from the actual working product.
2. Real user-provided diagrams, photographs, logos, and datasets.
3. SVG diagrams built from verified architecture/process facts.
4. Subject-relevant imagery that adds context.
5. Generated illustration only when the user requests it and the visual does not masquerade as product evidence.

## 14.2 Screenshot handling

- Preserve legible content; do not crop away the UI state that proves the claim.
- Use consistent image slots and aspect ratios within related screenshot groups.
- Annotate only the specific features relevant to the slide's takeaway.
- Do not add fake labels or fabricate UI behavior in the screenshot.
- Do not use a fully generated app mockup and imply that it is the live implementation.
- Redact secrets, personal data, API keys, and sensitive user information.
- Prefer a clean crop; use a subtle backing surface only when it improves context and contrast.

## 14.3 Asset quality and rights

- Use only assets the user owns or is allowed to use, or assets with an appropriate license.
- Do not copy another slide deck pixel-for-pixel or reuse its protected branding without permission.
- Treat reference sites as design inspiration, not a source of unlicensed assets.
- Track the source and license of third-party images/icons when applicable.
- Use icons only when the label alone is insufficient or a repeated icon language materially helps.
- Avoid emoji as a default replacement for a coherent icon or illustration system.

---

# 15. MOTION, BUILDS, AND LIVE-DEMO BEHAVIOR

## 15.1 Motion must have a job

For a standard editable PowerPoint, prioritize animation only when it improves explanation or presentation pacing. Good uses include:

- Revealing the stages of a process in speaking order.
- Showing one architecture path at a time.
- Building a chart series gradually when the reveal supports a real argument.
- A restrained cover/title reveal when appropriate to the tool and event.
- Subtle transition continuity between related states.

Avoid constant motion, spinning icons, bouncing cards, animated backgrounds, particle effects, and repeated decorative entrance animations.

## 15.2 Keep motion restrained

- Prefer a small number of purposeful builds over animation on every object.
- Keep timing fast enough not to delay the speaker.
- Provide a static fallback and consider reduced-motion preferences in HTML previews.
- Ensure the core story remains clear without animation.
- Do not depend on web-only animation surviving a PPTX export. Verify the exported output.
- If reliable PowerPoint animation authoring is unavailable, use carefully separated reveal slides or static states rather than claiming to have animated the deck.

## 15.3 Live-demo rules

- The actual demo should be rehearsable and fit its time block.
- Keep a clean fallback state: a genuine screenshot, output capture, or short recording where the format allows.
- Tell the presenter how to return to the deck.
- Do not put a long URL, command, or API key on a presentation slide.
- The demo should validate the deck's central claim, not show every feature.

---

# 16. EDITABLE PPTX ARCHITECTURE AND EXPORT STRATEGY

## 16.1 Final output contract

By default, deliver:

- `final-deck.pptx` — the requested PowerPoint file.
- `deck-outline.md` or an equivalent compact source outline if it improves later edits.
- `assets/` folder only when needed to keep the deck portable.
- Optional PDF or HTML preview only when requested or helpful; do not substitute a preview for the `.pptx`.

## 16.2 Choose the production route after inspection

Do not assume the system has a specific package installed. Inspect the environment and choose one reliable route:

**Route A — Native editable PowerPoint objects:**
- Use an installed PPTX authoring library or PowerPoint automation route where available.
- Build slide text, shapes, lines, charts, tables, and basic diagrams as native PowerPoint elements whenever feasible.
- This is preferred for mobile editing and direct Canva/PowerPoint import workflows.

**Route B — SVG-based vector slides:**
- Build each slide as a clean 16:9 SVG with deliberate text and shape grouping.
- Convert/package SVGs into `.pptx` using a verified export path.
- SVG keeps vector quality, but internal editability can vary. Importing SVG and converting it to shapes may be required for individual shape editing. Verify support in the target PowerPoint/Canva workflow.
- Avoid unsupported filters, masks, exotic CSS effects, external fonts, scripts, or complex clipping that may not survive conversion.

**Route C — HTML/CSS slide stage to PPTX:**
- Use a fixed 16:9 HTML stage for accurate visual composition and preview.
- Export through a known converter or render slides to images and package them into a PPTX only when necessary.
- Image-only slides preserve appearance but are not individually editable. Do not call this a fully editable deck.
- If using image-based PPTX, provide source HTML/SVG alongside the deck when appropriate and state the editability trade-off.

**Route D — Native PowerPoint automation:**
- Use Office/PowerPoint automation only if the environment supports it reliably. Avoid assuming Windows COM or Microsoft Office exists in a container/Linux environment.

## 16.3 PowerPoint design fidelity

- Default slide size: 16:9 widescreen (13.333 × 7.5 inches, or equivalent), unless the event requires another ratio.
- Use fixed slide bounds and a consistent safety margin.
- Keep key text and charts within the canvas.
- Use native text for all headlines and body content where possible.
- Use editable shapes for rules, blocks, callouts, and simple diagrams.
- Prefer simple SVGs for custom vector illustrations, with the caveat about downstream editability.
- Keep speaker notes in a supported field or in a companion outline when feasible.
- Use reproducible file names and stable slide IDs during iteration.
- Do not depend on a remote image URL at presentation time; package assets locally when required.

## 16.4 Font behavior

- Check selected fonts and their availability.
- Use PowerPoint-friendly fallback fonts when embedding is unavailable.
- Do not assume the judging laptop has the same fonts installed.
- If the final layout relies on a distinctive font, verify PDF/rendered appearance after export and report any fallback risks.

## 16.5 Export truth

When delivering, specify which elements are editable:

- Native text and shapes: generally editable.
- Native charts/tables: editable if built as such and export preserves them.
- SVG graphics: vector, but granular editability depends on import/conversion path.
- Rasterized slides: appearance-preserving but not individually editable.

Never label a PPTX fully editable without validating its actual structure.

---

# 17. MOBILE-FRIENDLY CONTROL AND REMOTE PRESENTATION

The user may control a laptop presentation from a phone. Treat this as a separate interaction requirement, not a design flourish.

## 17.1 Preferred setup

- When the presentation app already supports a trusted remote/companion control feature, prefer that before building a custom remote system.
- If proposing a local-network remote controller, confirm the presenter is using a private, trusted network and keep the control surface simple.
- Avoid exposing a control server directly to the public internet.
- Do not include secrets, tokens, or private network details in slides or source control.

## 17.2 Browser deck control (only if relevant)

If an HTML companion is provided, it may offer a phone-sized controller with previous/next, current-slide status, and optional laser pointer. If implemented:

- Make pairing explicit and visible.
- Require a short-lived, unguessable pairing token or equivalent protection.
- Keep commands limited to navigation/pointer functions; never allow arbitrary code execution or shell commands.
- Restrict connections to the expected local scope and implement origin/permission checks.
- Provide a clear disconnect and fail-safe manual keyboard navigation.
- Test on the actual target devices; do not claim remote control works merely because the UI exists.

## 17.3 Canva and PowerPoint caveat

- A `.pptx` is a portable file format, but Canva import may alter unsupported fonts, SVG details, charts, and effects.
- A web-based phone controller generally controls a compatible HTML presentation, not an arbitrary Canva or PowerPoint presentation, unless those applications expose a supported remote-control route.
- Explain the actual control method. Do not promise phone control of Canva just because a `.pptx` was created.
- If the user wants to edit the deck in Canva, optimize for a clean PPTX import: text-based headings, simple shapes, common fonts or safe fallbacks, and minimal unsupported effects.

---

# 18. QUALITY ASSURANCE AND VALIDATION

Quality assurance is mandatory. The agent must test the actual generated artifact rather than trusting source code alone.

## 18.1 Content QA

- Every required rubric item is addressed.
- Every slide has one clear job, a conclusion-led headline, and the right evidence.
- No fabricated metrics, features, quotes, citations, customers, or results.
- Built/prototype/planned states are labeled accurately.
- The story is understandable to a judge who knows nothing about the project.
- Technical concepts have plain-language framing without losing correctness.
- The closing includes a clear takeaway, next step, or invitation to the real demo.

## 18.2 Design QA

- One coherent theme is used across the deck.
- Typography hierarchy is consistent and readable at full-screen 16:9.
- No essential content is below comfortable projection size.
- Color contrast is checked, not guessed.
- Alignment, gutters, safe areas, image crops, and chart labels are correct.
- Slides do not all have the same layout.
- There are no accidental overlaps, broken glyphs, clipped images, or awkward title wraps.
- Motion is restrained and does not block critical information.

## 18.3 PowerPoint structure QA

Where tooling permits:

1. Verify the file exists, is nonempty, and is a valid ZIP-based `.pptx` package.
2. Reopen/import it with an independent reader or render it using an independent route.
3. Confirm slide count, slide order, aspect ratio, and text presence.
4. Render every slide to an image/PDF for visual review.
5. Inspect a contact sheet, then inspect slides individually where issues are visible.
6. Check for overflows, clipping, off-canvas objects, missing fonts, misplaced source notes, and incorrect page references.
7. Inspect whether key text and shapes remain editable if editability is a requirement.
8. Open or parse presenter notes when they are part of the deliverable.
9. Verify any intended animations only with a target presentation engine that supports them.

## 18.4 Iteration policy

- Fix observed defects with targeted edits.
- Do not rewrite the full deck for one spacing issue.
- Re-render after meaningful changes and confirm the fix did not break another slide.
- Preserve approved facts and visual tokens when refining.
- If time is limited, prioritize in this order: factual errors, missing rubric content, unreadable/overflowing slide, narrative gap, broken evidence, then polish.

## 18.5 Honest verification report

Separate:

- **Verified:** checks actually executed.
- **Not verified:** what the available tooling could not test.
- **Known limitations:** font embedding, Canva import, animation support, remote control, or SVG editability limitations.

Do not claim that a deck was visually inspected, imported into Canva, or checked in Microsoft PowerPoint unless it was.

---

# 19. ITERATION AND CHANGE CONTROL

When revising a deck:

1. Identify the requested change and which slides it affects.
2. Preserve approved narrative, evidence, style tokens, and assets unless the change requires otherwise.
3. Count slide elements and assess density before adding content.
4. If the change causes overflow, split or reorganize the slide before reducing type sizes.
5. Keep the selected theme's fonts, palette, grid, and visual grammar consistent.
6. Update slide numbering, references, notes, and any navigation metadata.
7. Re-run the content and rendering checks on changed slides; run a full-deck check for structural changes.

Do not mix several unrelated slide template systems into one deck. If adding a missing layout, design it using the selected deck's design grammar.

---

# 20. DELIVERY CONTRACT

Before responding with the artifact, provide:

- The downloadable `.pptx` path.
- Slide count and aspect ratio.
- One-line explanation of the selected visual direction and why it suits the brief.
- Editability statement that distinguishes native elements, vectors, and images.
- Verification summary: checks performed, checks not performed, and known limitations.
- Any required companion source files.

Never say “perfect,” “fully editable,” “Canva-ready,” “PowerPoint-tested,” or “remote-control ready” without the relevant verification. Describe exactly what was confirmed.

---

# 21. REUSABLE INTAKE SCHEMA

Use this schema to organize the brief internally. Do not force the user to fill every field if their files already answer it.

```yaml
deck_brief:
  project_name: ""
  presentation_type: "hackathon_pitch"
  audience: "judges"
  problem_statement: ""
  core_thesis: ""
  presenter_time_minutes: null
  slide_limit: 10
  aspect_ratio: "16:9"
  narrative_mode: "problem-to-demo"
  density: "speaker-led"
  current_state:
    built: []
    prototype: []
    planned: []
    unsupported_claims_to_avoid: []
  evidence_sources: []
  judging_rubric: []
  required_sections: []
  design:
    theme: "warm-neo-brutalist-studio"
    background: "light"
    neon: false
    dark_theme: false
    display_font: "selected-after-availability-check"
    body_font: "selected-after-availability-check"
    mono_font: "optional"
    motif: "derived-from-project-domain"
  assets:
    screenshots: []
    logos: []
    diagrams: []
    charts_data: []
  output:
    pptx: true
    pdf_preview: false
    html_source: false
    canva_import_target: false
    phone_remote_control: false
  quality_gates:
    visual_render_check: true
    content_claim_audit: true
    pptx_reopen_check: true
    inspect_editability: true
```

---

# 22. HACKATHON DECK OUTLINE EXAMPLE

This is an example structure only. Replace all bracketed content with verified project-specific facts, and remove slides that don't earn their place. Do not keep the example wording in a real deck.

1. **The hook:** `[Specific user/problem insight]` — one sharp title, one visual cue.
2. **The cost of the current way:** `[Observable friction and evidence]` — process comparison or real data.
3. **The new approach:** `[Product proposition]` — one-sentence promise and product surface.
4. **The path through the product:** `[Core flow]` — input → system action → outcome.
5. **The proof moment:** `[Actual screenshot/demo output]` — genuine UI with one to three annotations.
6. **Why this approach:** `[Specific differentiation]` — fair comparison or architectural insight.
7. **Can we ship it?:** `[Real architecture, constraints, and feasibility]` — technical diagram grounded in repo/project facts.
8. **What we know so far:** `[Verified test/feedback/result or validation plan]` — measured data or honest unknowns.
9. **What happens next:** `[Next milestone / deployment / scale plan]` — realistic roadmap.
10. **The close:** `[Strong takeaway or ask]` — one memorable claim and direct transition to demo/Q&A.

A 7-slide version may combine slides 2+3, 4+5, and 8+9. A strict 5-minute pitch may need only 6–8 slides. The story and rubric decide the final count.

---

# 23. FINAL PREFLIGHT CHECKLIST

## Story and accuracy

- [ ] One sentence describes the deck's central claim.
- [ ] Each slide answers a real audience question.
- [ ] The deck respects the hard slide/time limit and rubric.
- [ ] Every statistic and technical claim has a known provenance/status.
- [ ] No fictional traction, fabricated outcomes, or unbuilt features are implied.
- [ ] The problem, solution, demo, differentiation, feasibility, and close form a coherent story.

## Design and legibility

- [ ] One primary visual system is applied consistently.
- [ ] Light/neutral ground and requested palette restrictions are followed.
- [ ] Typography is purposeful and has a real fallback plan.
- [ ] Body and chart text are readable on a projector.
- [ ] The deck is not a pile of cards or identical templates.
- [ ] Diagrams, charts, and screenshots each serve a clear claim.
- [ ] Colors and labels both carry meaning.
- [ ] No overflow, clipping, collisions, placeholder content, or accidental missing assets remain.

## Technical artifact

- [ ] The `.pptx` exists and reopens.
- [ ] Slide count/order/size are correct.
- [ ] Each slide was rendered and reviewed if tooling permits.
- [ ] Text, shapes, charts, and SVG editability are described honestly.
- [ ] External assets are packaged or linked appropriately for offline presentation.
- [ ] Canva/PowerPoint compatibility risks are disclosed where not tested.
- [ ] The presenter can navigate and return from the demo.

## Delivery

- [ ] Exact downloadable path is given.
- [ ] Verification results are factual.
- [ ] Known limitations and unverified items are clearly stated.

---

# 24. REFERENCE MAP AND ATTRIBUTION

This skill synthesizes general workflow ideas from the resources below while expressing them as an independent, portable policy. It is not a copy of their implementation code, assets, templates, or full text. Check each repository's current license before copying code, assets, or bundled templates into another project.

- **Visual Explainer** — figure-led explanations, mechanism diagrams, meaningful animation, source/render/visual QA discipline: https://github.com/nicobailon/visual-explainer
- **Frontend Slides** — style discovery, distinctive design, content-density modes, fixed 16:9 stage, animation restraint, and overflow checks: https://github.com/zarazhangrui/frontend-slides
- **HTML PPT Skill** — broad theme/layout/animation concepts and presentation workflow reference: https://github.com/lewislulu/html-ppt-skill
- **Guizang PPT Skill** — presenter-oriented narrative planning, slide timing, speaker notes, layout consistency, and structured visual QA: https://github.com/op7418/guizang-ppt-skill
- **Beautiful HTML Templates / AGENTS.md** — tone-first matching, preview-based selection, preserving one coherent design system, and extending layouts consistently: https://github.com/zarazhangrui/beautiful-html-templates/blob/main/AGENTS.md
- **PPT SVG Generator** — structured content analysis, SVG-to-PPT workflow concepts, and vector/editability caveats: https://github.com/vigorX777/ppt-svg-generator
- **Tosea Slide Skill Directory** — discovery/index of adjacent slide-generation skills and templates: https://tosea.ai/slide-skills
- **Personalized UI master skill supplied by the user** — product truth, typography/color systems, accessibility, motion purpose, evidence over assertion, and visual-QA discipline. Use the uploaded `master-ui-skill` as a complementary design governance reference, not as a replacement for this slide-specific workflow.

**Reference use policy:** Inspect the relevant upstream files when a task requires their exact workflow or when current behavior matters. Do not assume the URLs remain unchanged, a dependency is installed, a repository's license permits reuse, or a visual preview will match the final exported `.pptx`.
