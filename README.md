# master-slide-skill

A reusable AI agent skill for creating distinctive, judge-focused hackathon presentations and editable PowerPoint decks.

## The problem it solves

Hackathon teams often have a working prototype but no time to turn it into a presentation judges can understand and remember. Decks slip into generic AI-template layouts, invented metrics, walls of bullet text, and slides that look like every other team's. Worse, agents frequently promise a `.pptx` but cannot actually produce, render, or verify one in the current environment.

`master-slide-skill` is a portable `SKILL.md` policy that instructs an AI coding agent to:

- Plan a hackathon story from the real problem statement and judging rubric.
- Build a distinctive 7–9 slide deck with evidence-based claims and readable design.
- Export an editable PowerPoint `.pptx` wherever the agent's environment supports it.
- Honestly report what it verified — and what it could not.

The skill is a framework for the agent, not a slide generator, not a fixed template, and not permission to invent missing product details.

## Feature overview

| Area | What the skill covers |
|------|----------------------|
| Narrative | Problem-to-demo story arc mapped to judging rubrics; 7–9 default slides, hard cap of 10 unless the event allows more |
| Authenticity | Claim ledger with provenance statuses (`verified`, `user-provided`, `estimate`, `hypothesis`, `planned`, `unknown`); no fabricated metrics or features |
| Design | Eight light/neutral theme directions, typography system, color contrast guidance, layout library, restrained motion |
| Visuals | Diagram and chart selection rules, genuine screenshot preference, source attribution |
| Output | `final-deck.pptx`, optional `deck-outline.md` and `assets/`; honest editability reporting per element type |
| Quality | Rendered-slide QA, PPTX reopen checks, preflight checklist, delivery contract |
| Caveats | Canva import and phone-remote limitations disclosed; HTML previews are authoring tools, not the final deliverable |

## Who should use it

- **Hackathon teams** that need a credible deck fast, without generic AI-template looks.
- **Solo builders and student innovators** presenting prototypes, demo days, or project showcases.
- **Founders** preparing early-stage product pitches and technical proposals.
- **AI-agent users** who want their coding agent to follow a repeatable presentation policy instead of improvising slide design.

## Workflow

1. **Problem statement and rubric** — the agent reads the challenge, judging criteria, time limit, and slide cap before designing anything.
2. **Story structure** — it selects a narrative arc (hook, problem, solution, demo, differentiation, evidence, feasibility, close) and gives every slide one job.
3. **Visual design** — it picks one theme from the library, sets the typography and color system, and avoids mixing presets.
4. **Diagrams and data** — it chooses the right visual for each claim, uses real data or marks data as illustrative, and cites sources.
5. **PowerPoint export** — it picks a production route after inspecting the environment: native PPTX objects, SVG-based slides, HTML stage to PPTX, or PowerPoint automation.
6. **Quality checks** — it re-renders and re-opens the `.pptx`, checks slide count/order/size, runs the preflight checklist, and reports only verified results.

## Installation

### OpenCode

Copy this folder into your configured OpenCode skills directory, preserving the `master-slide-skill/SKILL.md` structure. If your local setup uses a different skills directory, use that directory instead.

Example layout:

```text
<your-skills-directory>/
└── master-slide-skill/
    ├── SKILL.md
    ├── README.md
    └── LICENSE
```

Then invoke the skill in your agent prompt by mentioning `master-slide-skill` or asking the agent to follow `SKILL.md`. Exact invocation conventions depend on your OpenCode configuration and skill loader.

### Compatible agent-skill environments (portable)

The skill is Markdown-based and requires only that the agent can read `SKILL.md` and access local files. It also requires an available PowerPoint generation route in the active environment; adapt commands and tools to the agent you are using. Browser-based HTML preview is recommended for authoring and validation but is not the final deliverable unless explicitly requested.

Environment-specific paths (skills directory, output folder, PPTX authoring tools) must be adapted to your setup. This repository does not ship installers, dependencies, or a build system.

## Usage examples

### Request a new hackathon deck

> Use `master-slide-skill` to plan and build a hackathon deck for **[project name]**.
>
> Problem statement: *[exact challenge wording]*
> Audience: judges / demo-day panel
> Presentation time: 5 minutes; maximum slide count: 10
> Judging rubric: *[paste rubric or link]*
> What is built versus planned: *[briefly list]*
> Output: `final-deck.pptx`, 16:9, one coherent light theme
>
> Run the quality checks and report what you verified.

### Improve an existing outline

> Use `master-slide-skill` in **Refine** mode to audit `deck-outline.md`.
>
> Check each slide against the judging rubric, verify every statistic against its source, fix overflow or density issues, and output a revised `final-deck.pptx`. Report the verification results honestly — do not claim checks you did not run.

## Expected output

Where tooling supports it, the final deliverable is:

- `final-deck.pptx` — an editable PowerPoint file (text, shapes, charts, and diagrams editable wherever the export route preserves them).
- `deck-outline.md` — a compact source outline for later edits (optional but recommended).
- `assets/` — packaged screenshots, diagrams, or charts when needed for portability.
- Optional PDF or HTML preview only when requested; a preview never substitutes for the `.pptx`.

**Editability is not guaranteed.** Native text and shapes are generally editable; SVG graphics are vector but granular editability depends on the import/conversion path; rasterized slides preserve appearance but are not individually editable. The skill never labels a PPTX "fully editable" without validating its actual structure.

## Design principles

- **Original visual identity:** one coherent theme per deck, never a generic AI-template look.
- **Light and warm palettes:** light grounds by default; restrained accents; no neon or cyberpunk defaults.
- **Strong typography:** expressive headlines, legible body, consistent hierarchy; PowerPoint-friendly fallbacks.
- **Readable slides:** one major idea per slide, comfortable type sizes for projection, no shrinking text to fit.
- **Evidence-based claims:** every statistic traces to a source with a recorded provenance status.
- **Restrained animation:** builds only when they aid explanation; no spinning icons or animated backgrounds.
- **No fabricated UI:** real screenshots and real architecture only; planned components are labeled as planned.

## Repository structure

```text
master-slide-skill/
├── SKILL.md          # Agent skill policy — do not modify
├── README.md         # This file
├── LICENSE           # MIT License — complete [YEAR] and [COPYRIGHT HOLDER]
├── CONTRIBUTING.md   # Contribution guide for the community
├── SECURITY.md       # Security reporting notes
└── .gitignore        # Git ignore rules
```

`SKILL.md` is the skill itself. The other files support the public repository release.

## Contributing

Contributions are welcome — accuracy fixes, theme clarifications, documentation improvements, and issue reports. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for how to report bugs, propose improvements, and submit pull requests.

## License

This project is released under the [MIT License](LICENSE). The `LICENSE` file contains placeholders (`[YEAR]` and `[COPYRIGHT HOLDER]`) that the copyright holder should complete before publication. This repository does not confirm ownership of any third-party material referenced in `SKILL.md`, and it does not grant permission to relicense third-party assets, code, or templates.

## Acknowledgments and references

`master-slide-skill` synthesizes general presentation and design workflow ideas from the following sources, expressed as an independent, portable policy. It is not a copy of their code, assets, templates, or full text, and listing them does not claim affiliation or endorsement.

- [Visual Explainer](https://github.com/nicobailon/visual-explainer)
- [Frontend Slides](https://github.com/zarazhangrui/frontend-slides)
- [HTML PPT Skill](https://github.com/lewislulu/html-ppt-skill)
- [Guizang PPT Skill](https://github.com/op7418/guizang-ppt-skill)
- [Beautiful HTML Templates / AGENTS.md](https://github.com/zarazhangrui/beautiful-html-templates/blob/main/AGENTS.md)
- [PPT SVG Generator](https://github.com/vigorX777/ppt-svg-generator)
- [Tosea Slide Skill Directory](https://tosea.ai/slide-skills)
- [master-ui-skill](https://github.com/zarazhangrui/master-ui-skill) — complementary design governance reference, per the supplied personalized UI master skill

Inspect each repository's current license before copying code, assets, or bundled templates. URLs may change; do not assume a dependency is installed or that a preview matches the final exported `.pptx`.

## Limitations and troubleshooting

- A skill provides instructions to an agent; it does **not** itself guarantee that every agent has PowerPoint export, rendering, image, or browser tools. The agent must inspect its environment and report only checks it actually performed.
- `final-deck.pptx` is produced only when an available generation route exists in the active environment. Route support varies by agent and platform.
- Canva import may alter fonts, SVG details, charts, and effects. Do not assume Canva compatibility without testing.
- Phone-based remote control generally works only with a compatible HTML presentation or an application that exposes a supported remote-control route. A `.pptx` alone does not imply phone control.
- HTML previews are authoring and validation tools, not the final deliverable unless explicitly requested.
- Fonts: distinctive typefaces may not be installed on the judging laptop; verify fallback behavior.

If something does not work, open an issue describing your agent environment, the route you tried, and what happened.

## Call for contributors

This skill is maintained for the hackathon and AI-agent community. If you improve the guidance, fix an inaccuracy, or add a useful pattern, please open an issue or pull request. See [CONTRIBUTING.md](CONTRIBUTING.md).
