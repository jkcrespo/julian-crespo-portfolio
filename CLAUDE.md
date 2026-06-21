# Julian Crespo — Portfolio Site

---

## About me

I'm Julian Crespo, Design Systems Leader at FIS Global. My career spans product design, design systems, and design leadership across FIS Global, Lyra Health, Star Global, Adobe, and Collective Health.

Current focus: design systems leadership at FIS Global on the Unify Design System (UDS). System architecture, adoption, intake, and the people leadership that makes systems stick. Before this, I led design systems and major UI initiatives at Lyra Health as a one-person systems team.

The audience for this portfolio is **hiring managers and peer design leaders evaluating staff/lead candidates**. They care about organizational influence, defensible tradeoffs, and system scalability. Not just craft execution.

### My about-me copy

The simple about-me that should run on the site, verbatim from my August '24 deck:

> **Design super power: Genuine curiosity**
>
> I invest in opportunities that fulfill my need to continually learn new ways to make the art of design more equitable, extensible, and beautiful.

Use this copy verbatim. Don't paraphrase. Don't extend. It earns its place by being short.

---

## Experience timeline

For the homepage "Worked with" section.

| Dates | Role | Company |
|---|---|---|
| 10.24 – Present | Design Systems Leader | FIS Global |
| 08.21 – 10.24 | Sr Product Designer | Lyra Health |
| 03.20 – 07.21 | Interaction Designer | Star Global |
| 06.19 – 09.19 | Experience Designer | Adobe |
| 05.18 – 08.18 | Product Design Intern | Collective Health |
| Earlier | ...and a previous career | — |

The "previous career" line stays. It's a credibility marker.

---

## Site information architecture

```
/                         Home
                          — Hero (marquee with name + tagline)
                          — About strip ("genuine curiosity" quote)
                          — Featured work (3 projects)
                          — Experience timeline
                          — Footer

/design-work              Design Work index
                          — All 8 projects, grouped by employer (FIS, Lyra, Star Global)
                          — Each card links to project page

/design-work/[slug]       Project pages (8 total, summary format)

/not-design               Not Design
                          — Photography
                          — Art
                          — Interactive experiments

/about                    About (optional v2)
```

### Top nav

Visible on every page:

```
[J.C.]                    Design Work    Not Design    Menu
```

Menu opens a sheet with: Home, Design Work, Not Design, About, LinkedIn, Email.

"Not Design" is intentional. It's honest about what it is. Not a "play" or "studio" label.

---

## What we're working on

A Figma-based portfolio site. Dark mode, editorial register, structural homage to edwinle.com. Built first as wireframes in Figma, then coded as a static site or framework TBD.

**Hero subhead (locked):**
> Design systems leader. Craft, architecture, and the work that makes systems stick across products.

**Figma file:** `jGz1JZQSTw2Wi351WurDmL`
**URL:** https://www.figma.com/design/jGz1JZQSTw2Wi351WurDmL/Figma-Experiments

### Current canvas layout

```
x=4209   portfolio-jc (homepage, primary)              id 13:2
x=5849   Project — Beacon (detailed, archive)          id 24:2
x=7549   Project — Sprouts (detailed, archive)         id 24:82
x=9249   Project — Jam (detailed, archive)             id 24:162
x=11200  Substack Content Arc                          id 102:2
x=13000  Project — Craft & Design Systems (current)    id 181:2
x=14700  Project — Product Adoption (current)          id 181:76
x=16400  Project — Sprouts Overview (to be replaced)   id 181:150
```

**Still to build:**
- Three Lyra project pages (Look & Feel, Design System, Foundations & Tokens)
- Two Star Global project pages (Domino, vLab Digital Platform)
- Updated FIS pages with portfolio-facing names
- /not-design landing page

---

## Project naming conventions

FIS Global projects use portfolio-facing names. Internal names appear in copy and metadata only. Page titles and homepage cards use the descriptive name.

| Portfolio-facing name | Internal name | What it is |
|---|---|---|
| Craft & Design Systems | Unify Core + Greenhouse | Token architecture, foundations, components, documentation for a white-label product. |
| Product Adoption | Beacon Mobile | Design system adoption inside a white-label digital banking product, mobile first. |
| Design Intake | Unify Intake | Single intake surface for design needs across FIS design org, plus on-call triage role and guide. |

---

## Design Work — the projects

Eight projects total. Ordered FIS first (most senior, most recent), then Lyra, then Star Global. Each page uses the summary-style structure:

```
01-top-nav
02-hero               (eyebrow, title, subtitle)
03-meta               (role · client/scope · duration · year)
04-cover-visual       (labeled placeholder)
05-summary            (~80–100 words)
06-key-moves          (3 strategic moves)
07-outcomes           (~60 words)
08-case-study-link    ("View full case study >" + URL)
09-next-project
10-footer
```

### Featured trio for the homepage

1. **Craft & Design Systems** — collaborative architecture and ownership
2. **Product Adoption** — Design Ops and organizational change
3. **Design Intake** — system, tooling, and people leadership

The other five live on `/design-work`.

---

### 01 — Craft & Design Systems
*Internal: Unify Core + Greenhouse*

**Eyebrow:** PROJECT — DESIGN SYSTEM FOUNDATIONS
**Title:** Craft & Design Systems
**Subtitle:** Token architecture, foundations, components, and documentation for FIS's white-label products. Built collaboratively with a three-person founding team.
**Meta:** DESIGN SYSTEMS LEADER · FIS GLOBAL · 3-PERSON FOUNDING TEAM · 10.24 – PRESENT · [YEAR]

**Cover visual:** `[ DIAGRAM: Four-layer token architecture — primitives > UI defaults > intent > interaction ]`

**Summary (~90 words):**
> Before UDS could be adopted by any FIS product, it had to exist as a coherent system. I led the architecture work with two other systems leaders. A four-layer token system scoped to WCAG AA, a two-tier component library split between stable Core and experimental Greenhouse, distributed ownership across the team, and documentation built for contribution. My role spanned contributing to the system, leading slices of it, and reviewing what others contributed. The architecture held through every adoption and contribution that followed.

**Key moves:**
- Four-layer token system (primitives > UI defaults > intent > interaction) scoped to AA. AAA was a deliberate non-goal.
- Two-tier library. Core for stable production components, Greenhouse for experimental ones earning their way in.
- Collaborative ownership across the founding team with shared promotion authority.

**Outcomes:**
> The system was production-ready before its first adopter signed on. The two-tier model became the reference structure other FIS product groups asked about. Every downstream project, banking adoption, design intake, the formation of the official UDS team, assumed this architecture.

**Full case study:** `[PRESENTATION_URL_FOUNDATIONS]`

**Next:** Product Adoption >

---

### 02 — Product Adoption
*Internal: Beacon Mobile*

**Eyebrow:** PROJECT — DESIGN SYSTEM ADOPTION
**Title:** Product Adoption
**Subtitle:** Standing up a Design Ops function to land Unify inside FIS's white-label digital banking product. Consumer and business surfaces, mobile first.
**Meta:** DESIGN OPS · ADOPTION LEAD · FIS GLOBAL · 2 DESIGNERS REPORTING IN · [YEAR]

**Cover visual:** `[ SCREENSHOT: White-label banking mobile UI — UDS components in production ]`

**Summary (~90 words):**
> The white-label digital banking product was the first FIS product to commit to Unify, serving consumer and business banking on mobile. Adopting a design system at enterprise scale is an organizational change effort, not a "use the components" exercise. I created a Design Ops role for the engagement and assumed it, coordinating adoption across product, design, and engineering, and feeding learnings back into UDS so the next adopter would have a smoother path.

**Key moves:**
- Designed and assumed a Design Ops role that did not exist before this engagement.
- Audited the banking product's patterns against UDS Core. Coordinated migration across product, design, and engineering.
- Treated adoption as a coordination problem with craft consequences, not the reverse.

**Outcomes:**
> Mobile shipped on Unify as the first FIS product to do so. The adoption surfaced novel components that fed Greenhouse and pulled UDS forward. The engagement led to continued contracted work and the formation of a permanent UDS team I helped scope. The Design Ops role became the template other product adoptions followed.

**Full case study:** `[PRESENTATION_URL_BANKING]`

**Next:** Design Intake >

---

### 03 — Design Intake
*Internal: Unify Intake*

**Eyebrow:** PROJECT — INTAKE & GOVERNANCE
**Title:** Design Intake
**Subtitle:** A single touchpoint for design teams to submit needs, and a guide for DS designers to triage them as on-call owners.
**Meta:** DESIGN SYSTEMS LEADER · FIS GLOBAL · INTAKE SYSTEM · TOOLING · ON-CALL ROTATION · [YEAR]

**Cover visual:** `[ SCREENSHOT: Design Intake form — unify-intake.figma.site ]`

**Summary (~95 words):**
> As UDS adoption scaled, design needs surfaced through Slack DMs, hallway asks, and stray Jira tickets. A fragmented surface no one could triage. I designed and built a single intake system: a consumer-facing form for design teams to submit needs, an admin dashboard for triage, a five-step flow from submission to delivery, five request types, and a permanent Intake Owner role with an on-call rotation guide. The system runs on Figma Make, Supabase, and Resend. It is the touchpoint for design needs and the playbook for the DS designers who handle them.

**Key moves:**
- Replaced fragmented intake with a single submission form and admin dashboard built on Figma Make, Supabase, and Resend.
- Designed the five-step flow (Submit > Triage > Evaluate > Decide > Deliver) and five request types that route every design need.
- Created the Intake Owner role with four responsibilities and wrote the on-call guide that lets any DS designer step in.

**Outcomes:**
> Design teams now have one place to submit needs and a clear timeline for response. DS designers have a guide that makes triage a craft rather than tacit knowledge. The Intake Owner role became a permanent function, not a rotating burden. The system surfaces real demand data the design org never had before.

**Full case study:** `[PRESENTATION_URL_INTAKE]`

**Next:** Lyra Design System >

---

### 04 — Lyra Design System

**Eyebrow:** PROJECT — DESIGN SYSTEM
**Title:** Lyra Design System
**Subtitle:** Standing up Lyra's design language system as a team of one. Three months to stand up, never-ending to maintain.
**Meta:** SR PRODUCT DESIGNER · LYRA HEALTH · SYSTEM LEAD · 3 MONTHS STANDUP · [YEAR]

**Cover visual:** `[ DIAGRAM: Lyra design system structure — language, components, surfaces ]`

**Summary (~95 words):** [NEEDS DETAIL FROM ME]
> I stood up Lyra's design system alone. Three months to first usable release, then a long tail of maintenance, governance, and evangelism. The remit was broad: scale productivity across multiple design teams and product surfaces with a shared design language. Standing up a system without a collaborator meant making every tradeoff defensible on my own. Token strategy, component scope, contribution paths, and what to leave out. It taught me how systems scale: through clarity of decisions, not size of team.

**Key moves:** [NEEDS DETAIL FROM ME]

**Outcomes:** [NEEDS DETAIL FROM ME]

**Full case study:** `[PRESENTATION_URL_LYRA_DS]`

**Next:** Lyra: Foundations & Tokens >

---

### 05 — Lyra: Foundations & Tokens

**Eyebrow:** PROJECT — FOUNDATIONS
**Title:** Foundations & Tokens
**Subtitle:** Foundational tokens and design resources. The layer that makes innovation possible by making consistency cheap.
**Meta:** SR PRODUCT DESIGNER · LYRA HEALTH · DESIGN FOUNDATIONS · 6 MONTHS · [YEAR]

**Cover visual:** `[ DIAGRAM: Lyra token architecture and foundational resources ]`

**Summary (~95 words):** [NEEDS DETAIL FROM ME]
> Foundational tokens and design resources for the Lyra system. Over six months I established the token architecture, the foundational design resources, and the documentation that let other designers move fast without breaking shared surfaces. The framing was deliberate: foundations are not the dull part of a design system. They are where innovation gets unblocked, because every novel idea downstream depends on a stable surface to build against.

**Key moves:** [NEEDS DETAIL FROM ME]

**Outcomes:** [NEEDS DETAIL FROM ME]

**Full case study:** `[PRESENTATION_URL_LYRA_FT]`

**Next:** Lyra: Look & Feel >

---

### 06 — Lyra: Look & Feel

**Eyebrow:** PROJECT — UI REFRESH
**Title:** Look & Feel
**Subtitle:** A design-lead initiative to refresh Lyra's member-facing interfaces with warmth and platform parity.
**Meta:** SR PRODUCT DESIGNER · LYRA HEALTH · DESIGN LEAD INITIATIVE · 6 MONTHS · [YEAR]

**Cover visual:** `[ SCREENSHOT: Lyra member interface — before/after refresh ]`

**Summary (~90 words):** [NEEDS DETAIL FROM ME]
> A design-lead initiative to refresh Lyra's member-facing interfaces and bring platform parity across surfaces. The brief was to boost engagement by adding warmth to a clinical-feeling UI. The execution required holding a consistent visual language across product teams that had drifted. I led the design direction, the rollout sequencing, and the cross-team coordination that made the refresh land as a coherent shift, not a series of one-off updates.

**Key moves:** [NEEDS DETAIL FROM ME]

**Outcomes:** [NEEDS DETAIL FROM ME]

**Full case study:** `[PRESENTATION_URL_LYRA_LF]`

**Next:** Domino >

---

### 07 — Domino
*Client: One Concern*

**Eyebrow:** PROJECT — DISASTER RESILIENCE
**Title:** Domino
**Subtitle:** A resilience platform that brings disaster science and machine learning together for better decision-making during disaster operations.
**Meta:** LEAD DESIGNER · STAR GLOBAL · CLIENT: ONE CONCERN · 7 MONTHS · 2020

**Cover visual:** `[ SCREENSHOT: Domino dashboard — multi-hazard risk view ]`

**Summary (~95 words):** [NEEDS DETAIL FROM ME]
> Organizations need better tools to understand multi-hazard risks. Traditional risk assessments are expensive, slow to update, and fail to reflect conditions during live disaster operations. I led the design for Domino, a resilience platform that brings disaster science together with machine learning to support faster, more accurate decision-making. The work moved risk assessment from static snapshots toward something that reflects a moving, changing environment.

**Key moves:** [NEEDS DETAIL]
- Reframed risk assessment from a static snapshot into a dynamic, continuously updated picture.
- Designed for socio-economic and population trend data alongside the built environment.
- Built the UI around decision-making during live disaster operations, not retrospective analysis.

**Outcomes:** [NEEDS DETAIL FROM ME]

**Full case study:** `[PRESENTATION_URL_DOMINO]`

**Next:** vLab Digital Platform >

---

### 08 — vLab Digital Platform
*Client: Analog Devices*

**Eyebrow:** PROJECT — INTERACTIVE HARDWARE PLATFORM
**Title:** vLab Digital Platform
**Subtitle:** An interactive platform for learning, designing, testing, and prototyping hardware components. Without the hardware.
**Meta:** LEAD UX DESIGNER · STAR GLOBAL · CLIENT: ANALOG DEVICES · 6 MONTHS · 2020–2021

**Cover visual:** `[ SCREENSHOT: vLab platform — interactive component prototyping ]`

**Summary (~95 words):** [NEEDS DETAIL FROM ME]
> Analog Devices' digital experience didn't meet the demand of the modern hardware technology they offered. Development cycles ran longer than they should, increasing risk, expense, and complication of hardware/software integration. I led the UX for vLab, a platform that lets engineers and makers learn, design, test, and prototype hardware components in software. The brief was to facilitate interactive learning, design, and prototyping without physical hardware in hand.

**Key moves:** [NEEDS DETAIL]
- Designed around five hard constraints: content moderation, platform risk, trust in early models, fraud and quality control, and IP/privacy.
- Built for a community of makers, not a typical SaaS user.
- Treated hardware prototyping as a software interaction problem.

**Outcomes:** [NEEDS DETAIL FROM ME]

**Full case study:** `[PRESENTATION_URL_VLAB]`

**Next:** Back to Design Work >

---

## Not Design

A separate top-level surface for work outside the design practice.

```
/not-design
— Photography
— Art
— Interactive experiments
```

Visual treatment: same dark editorial bg, same type system. Content density is lighter. Not Design pages breathe more, lean toward imagery over text.

[NEEDS DETAIL FROM ME — counts, themes, format.]

---

## Design tokens

### Color

All values as 0–1 RGB for Figma Plugin API. Hex shown for reference.

| Token | Hex | RGB (0–1) | Use |
|---|---|---|---|
| bg | #0F0F0D | 0.06, 0.06, 0.05 | Page background |
| text | #F5F1EB | 0.96, 0.94, 0.92 | Primary text on dark bg |
| muted | #8C8C87 | 0.55, 0.55, 0.53 | Eyebrow, captions, secondary text |
| dim | #4D4D47 | 0.30, 0.30, 0.28 | Marquee row 2, ghosted display text |
| rule | #333330 | 0.20, 0.20, 0.18 | Horizontal dividers, 1px |
| placeholder | #1A1A1A | 0.10, 0.10, 0.10 | Visual placeholder frames |

All combinations validated to WCAG AA on the bg color. AA is the ceiling. AAA is not pursued.

### Typography

Two typefaces, both from Google Fonts:

- **Chonburi** — display titles, section headings, pull quotes. Single weight (Regular / 400). Hierarchy comes from size, not weight.
- **Gothic A1** — body, subtitles, captions, eyebrows, meta strips, and all running text. Weights in use: 400, 500, 600, 700.

### Type scale

| Style | Family | Weight | Size | Line height | Letter spacing |
|---|---|---|---|---|---|
| Eyebrow | Gothic A1 | 500 Medium | 12 | 130% | +0.08em (all caps) |
| Display title (hero) | Chonburi | 400 Regular | 128 | 100% | -0.01em |
| Subtitle | Gothic A1 | 400 Regular | 28 | 140% | normal |
| Section heading | Chonburi | 400 Regular | 40 | 110% | -0.005em |
| Body | Gothic A1 | 400 Regular | 17 | 160% | normal |
| Pull quote | Chonburi | 400 Regular | 32 | 140% | -0.005em |
| Caption | Gothic A1 | 400 Regular | 13 | 140% | normal |
| Meta strip | Gothic A1 | 500 Medium | 13 | 140% | +0.08em (all caps) |
| Card title | Chonburi | 400 Regular | 28 | 110% | normal |
| Tag | Gothic A1 | 500 Medium | 13 | 100% | +0.04em |
| Link / CTA | Gothic A1 | 500 Medium | 16 | 140% | normal |

**Font loading in Figma:**

```javascript
await figma.loadFontAsync({family: "Chonburi", style: "Regular"});
await figma.loadFontAsync({family: "Gothic A1", style: "Regular"});
await figma.loadFontAsync({family: "Gothic A1", style: "Medium"});
await figma.loadFontAsync({family: "Gothic A1", style: "SemiBold"});
await figma.loadFontAsync({family: "Gothic A1", style: "Bold"});
```

### Spacing scale

Use these values only. No in-between values.

| Token | Value |
|---|---|
| 2xs | 4 |
| xs | 8 |
| sm | 16 |
| md | 24 |
| lg | 40 |
| xl | 60 |
| 2xl | 80 |
| 3xl | 120 |
| 4xl | 160 |

**Section vertical padding presets:**
- Large section (hero, opening): 120 top / 120 bottom
- Medium section (body sections): 80 top / 80 bottom
- Tight section (meta, footer): 60 top / 60 bottom

### Shape primitives

| Element | Spec |
|---|---|
| Horizontal rule | 1px, color `rule` |
| Border radius | 0 default. Editorial sharp corners. |
| Tag / chip radius | 4px |
| Card image aspect ratio | 16:9 default, 3:2 for portrait crops |
| Pull quote left rail (optional) | 4px wide, color `muted`, 100% height |
| Visual placeholder fill | color `placeholder` |
| Cursor | Default. No custom cursor for v1. |

---

## Layout grid

| Property | Value |
|---|---|
| Desktop canvas | 1440 |
| Container width | 1360 (centered, 40px gutter each side) |
| Column count | 12 |
| Column gap | 24px |
| Section vertical rhythm | See section padding presets above |

Mobile and tablet are v2 scope. Do not generate tablet or mobile variants in Figma unless I ask.

---

## Interaction states

### Cards (homepage selected work, /design-work index)
- **Default:** as drawn
- **Hover:** image scales 1.02 over 300ms ease-out. Title gains underline (1px, offset 4px). Eyebrow color shifts `text` > `muted`.
- **Active:** scale 0.99 for 100ms then release
- **Focus (keyboard):** 2px outline in `text` color, 4px offset

### Links and inline CTAs
- **Default:** text only, no decoration
- **Hover:** underline appears (1px, offset 2px), 200ms ease-out
- **Focus (keyboard):** 2px outline in `text` color, 4px offset
- **Visited:** no special treatment

### Top nav
- **Default:** transparent background. Design Work and Not Design tabs visible.
- **Active tab:** underline (1px, offset 4px), `text` color
- **Sticky on scroll:** past the hero, gains 80% opacity `bg` color + 20px backdrop-blur
- **Menu trigger:** hover scales the indicator dot 1.2x

### "View full case study >" CTA
- **Default:** Gothic A1 Medium 16, arrow inline
- **Hover:** arrow translates 4px right over 200ms

---

## Motion

### Marquee (homepage hero row 2)
- Continuous horizontal scroll, right-to-left
- Speed: 60 seconds per full cycle
- Pauses on hover
- Reduced-motion: replaced with static centered text

### Parallax (project pages)
- Cover image translates Y at 0.5x scroll speed
- Inline image visuals translate Y at 0.8x scroll speed
- Section text content has no parallax
- Reduced-motion: parallax disabled

### Section reveal on scroll
- Body text fades in + translates 12px Y on entering viewport
- One-time only per session
- Stagger: 80ms between sibling elements
- Reduced-motion: instant appearance

### Easing curve
- Default ease: `cubic-bezier(0.22, 1, 0.36, 1)` (ease-out-quart)

---

## Style and voice

**Voice on portfolio pages:**
- First person, past tense.
- Confident but not boastful. Claim the impact, name the tradeoffs.
- Specific over vague.
- Editorial register: slower sentences, more breath.

**Voice on homepage cards:**
- Tight, scannable, no filler.

**Voice on the about strip:**
- The "genuine curiosity" quote is verbatim.

**Voice on Not Design:**
- Looser, more personal. Less staff-lead positioning, more genuine-curiosity-in-practice.

**Voice in Claude Code conversations:**
- Direct, no preamble.
- Push back if I'm under-claiming or being vague.
- Flag implicit tradeoffs.
- Suggest cuts before suggesting additions.

**Punctuation and style rules:**
- No em dashes. Use commas or cut the sentence short instead.
- Less verbose. Shorter sentences preferred.
- Bullets for actual enumerations only.
- No emojis unless I use them first.

**Avoid:**
- Generic UX language ("user-centered", "delight", "seamless").
- Vanity metrics.
- Passive voice when I'm claiming ownership.

---

## Visual asset placeholder convention

- `[ IMAGE: description ]` — static photo or illustration
- `[ ANIMATION: description ]` — gif, video, or interactive demo
- `[ CHART: description ]` — data visualization
- `[ DIAGRAM: description ]` — system architecture, flow, or schema
- `[ SCREENSHOT: description ]` — UI capture from product or tooling
- `[ STORYBOARD: description ]` — sequence of frames showing a journey

In Figma: flat dark rectangle (fill `placeholder`), label centered in Gothic A1 Medium 14 muted, one-line caption below in Gothic A1 Regular 13 muted.

---

## Figma generation conventions

- File key: `jGz1JZQSTw2Wi351WurDmL`
- Load both Chonburi and Gothic A1 (with all weights in use) before creating any text node.
- Set `textAutoResize = "HEIGHT"` and explicit width for text that wraps.
- Leave `textAutoResize = "WIDTH_AND_HEIGHT"` for display titles and headings.
- Set position (x, y) on each node after appending to its parent so positions are relative.
- Frame naming convention: `01-top-nav`, `02-hero`, etc.
- For tag and meta-strip text: set `letterSpacing = {value: 8, unit: "PERCENT"}` for +0.08em equivalents.
- For Chonburi display titles: set `letterSpacing = {value: -1, unit: "PERCENT"}` for -0.01em.

---

## Common tasks I'll ask for

- **Build a new project page** in Figma with the summary-style structure.
- **Build the three Lyra pages and two Star Global pages.** I'll feed real detail to replace `[NEEDS DETAIL]` placeholders.
- **Rename the existing FIS Figma pages** to portfolio-facing titles.
- **Build the /design-work index page** with all 8 projects grouped by employer.
- **Build the /not-design landing page** with the three categories.
- **Update existing page content.** Patch a section, swap a placeholder, change a subtitle.
- **Draft homepage card content.** Title + 2–3 tags matching each project page.
- **Tighten an existing draft.** I'll paste prose, you'll suggest 30%-shorter rewrites that preserve depth signals.
- **Audit a page against the design tokens.** Flag spacing, type, or color values off the scale.
- **Draft Notion or Jira tickets** related to UDS work (Notion-friendly, no bullets where they won't render).

---

## What NOT to do

- Don't use internal codenames as page titles. Use portfolio-facing names: Craft & Design Systems, Product Adoption, Design Intake.
- Don't paraphrase or extend the "Design super power: Genuine curiosity" copy. Verbatim.
- Don't fabricate detail for the Lyra or Star Global project pages. Drafts marked `[NEEDS DETAIL FROM ME]` stay as-is until I provide real content.
- Don't delete the archived parallax pages (ids 24:2, 24:82, 24:162).
- Don't replace `[PRESENTATION_URL_*]` placeholders with fabricated links.
- Don't introduce new design vocabulary I haven't used.
- Don't suggest AAA accessibility targets. AA is the ceiling.
- Don't write portfolio copy in passive voice when I'm claiming ownership.
- Don't introduce in-between spacing values. Pick from the scale.
- Don't substitute Chonburi or Gothic A1 with similar fonts. Raise it as a question instead.
- Don't generate mobile or tablet variants in Figma unless I explicitly ask.
- Don't relabel "Not Design" as something softer ("Play", "Studio", "Side Projects"). The name is deliberate.
- Don't use em dashes anywhere. Use commas or cut the sentence short.

---

## Tools and references

- **Figma:** primary canvas.
- **Figma Make:** intake form (`unify-intake.figma.site`) and admin dashboard (`uds-review.figma.site`).
- **Supabase:** backend for Unify Requests. Project ref `laoqicyotmmkukddxuzx`. Edge Function `make-server-ea616340`.
- **Resend:** email notifications for the intake system.
- **Jira:** active tickets include UDS-1425 and UDS-1419.
- **Notion:** preferred format for Jira ticket drafts.
- **Substack:** 24-month editorial arc in the Figma file at id 102:2.
- **Google Fonts:** Chonburi and Gothic A1 source.

---

## Open items to chase

- **Confirm `[YEAR]` placeholders** on each project page.
- **Lyra project detail** for Look & Feel, Design System, Foundations & Tokens.
- **Star Global project detail** for Domino and vLab.
- **Case study presentation URLs:** eight URLs to replace `[PRESENTATION_URL_*]` placeholders.
- **Cover assets:** real screenshots, diagrams, visuals to replace placeholders.
- **Not Design content:** photography, art, and interactive experiments. Counts, themes, format.
- **Preview Chonburi at scale:** confirm "Hi, I'm Julian Crespo" at 128pt reads the way I want before locking the choice in.
- **Rename the existing FIS Figma pages** to portfolio-facing titles on the next Figma update pass.

---

## How to use this file

1. Save as `CLAUDE.md` in the project root.
2. Run `claude` in the directory.
3. Claude Code will load this as persistent context.
4. Ask for the task: *"Rename the FIS Figma pages to portfolio-facing titles."* *"Build the Domino and vLab Star Global pages in Figma."* *"Draft homepage card copy for the featured trio."*
