version: alpha
name: HuggingFace-design-analysis
description: A developer-first, repository-dense interface for Hugging Face. The system anchors on a neutral white/light-gray canvas with thin gray borders, compact system-sans typography, metadata-rich cards, and the Hugging Face yellow/orange brand pair as a selective identity accent. Product credibility comes from showing real models, datasets, Spaces, organizations, download/like counts, update recency, repository names, tags, and code-oriented controls rather than abstract marketing decoration. The hugging-face emoji/logo is the signature friendly counterweight to an otherwise technical, information-dense platform.

colors:
primary: "#FFD21E"
primary-active: "#FFB800"
primary-soft: "#FFF4BF"
secondary: "#FF9D00"
secondary-soft: "#FFF0D6"
ink: "#111827"
body: "#374151"
body-strong: "#1F2937"
muted: "#6B7280"
muted-soft: "#9CA3AF"
hairline: "#E5E7EB"
hairline-soft: "#F3F4F6"
canvas: "#FFFFFF"
surface-soft: "#F9FAFB"
surface-card: "#FFFFFF"
surface-raised: "#FFFFFF"
surface-muted: "#F3F4F6"
surface-dark: "#111827"
surface-dark-elevated: "#1F2937"
on-primary: "#111827"
on-secondary: "#111827"
on-dark: "#F9FAFB"
on-dark-soft: "#D1D5DB"
link: "#2563EB"
link-visited: "#7C3AED"
success: "#16A34A"
warning: "#D97706"
error: "#DC2626"
info: "#2563EB"

Official Hugging Face brand colors verified from the public brand-assets page:

yellow #FFD21E · orange #FF9D00 · gray #6B7280.

Remaining UI neutrals/semantic colors are implementation guidance reconstructed

from the live Hub visual language; treat them as design tokens, not trademark specs.

typography:
display-xl:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 48px
fontWeight: 700
lineHeight: 1.08
letterSpacing: -1.1px
display-lg:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 36px
fontWeight: 700
lineHeight: 1.15
letterSpacing: -0.7px
display-md:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 30px
fontWeight: 700
lineHeight: 1.2
letterSpacing: -0.4px
display-sm:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 24px
fontWeight: 600
lineHeight: 1.25
letterSpacing: -0.2px
title-lg:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 20px
fontWeight: 600
lineHeight: 1.35
letterSpacing: -0.1px
title-md:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 16px
fontWeight: 600
lineHeight: 1.4
letterSpacing: 0
title-sm:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 14px
fontWeight: 600
lineHeight: 1.4
letterSpacing: 0
body-lg:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 18px
fontWeight: 400
lineHeight: 1.6
letterSpacing: 0
body-md:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 16px
fontWeight: 400
lineHeight: 1.55
letterSpacing: 0
body-sm:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 14px
fontWeight: 400
lineHeight: 1.5
letterSpacing: 0
caption:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 12px
fontWeight: 500
lineHeight: 1.4
letterSpacing: 0
code:
fontFamily: "ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', monospace"
fontSize: 13px
fontWeight: 400
lineHeight: 1.55
letterSpacing: 0
button:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 14px
fontWeight: 500
lineHeight: 1
letterSpacing: 0
nav-link:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 14px
fontWeight: 500
lineHeight: 1.4
letterSpacing: 0
metadata:
fontFamily: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
fontSize: 12px
fontWeight: 400
lineHeight: 1.4
letterSpacing: 0

rounded:
xs: 4px
sm: 6px
md: 8px
lg: 12px
xl: 16px
pill: 9999px
full: 9999px

spacing:
xxs: 4px
xs: 8px
sm: 12px
md: 16px
lg: 24px
xl: 32px
xxl: 48px
section: 80px

Overview

Hugging Face is a developer-first collaboration and discovery interface, not a conventional SaaS marketing page. The homepage immediately places the user inside the working ecosystem: search, Models, Datasets, Spaces, Buckets, Docs, Enterprise, and Pricing are exposed in the global navigation; the hero describes Hugging Face as the platform where the ML community collaborates; and the next major surface is live/trending repository content rather than a testimonial carousel or decorative brand story.

The visual system is deliberately neutral, compact, and repository-dense. White and very-light-gray surfaces carry most of the UI. Thin gray borders establish grouping. Typography stays in a practical system-sans voice. Yellow is the signature brand flash, but it is not a full-canvas color. The interface lets model thumbnails, Space previews, organization logos, repository names, tags, metrics, and timestamps provide most of the visual variation.

Brand voltage comes from the official Hugging Face palette — yellow ({colors.primary} — #FFD21E), orange ({colors.secondary} — #FF9D00), and neutral gray ({colors.muted} — #6B7280) — plus the hugging-face emoji/logo. The face mark makes an otherwise infrastructure-heavy experience feel friendly and community-led.

The design system has four primary surface modes:

White canvas ({colors.canvas}) — default page floor and most cards

Soft neutral ({colors.surface-soft} / {colors.surface-muted}) — search fields, tags, subtle grouping

Hairline-bordered white cards — repositories, organizations, libraries, pricing, feature modules

Dark code/product surfaces ({colors.surface-dark}) — code examples, terminals, developer snippets; used selectively rather than as a page-wide motif

The page pacing is not created by alternating huge color bands. It is created by density changes: spacious hero → dense trending repositories → larger explanatory feature modules → commercial cards → organization/library proof → compact footer.

Key Characteristics:

White/light-gray foundation with subtle cool-gray borders.

Official yellow (#FFD21E) used as a selective identity accent; orange (#FF9D00) is the companion brand accent.

System-sans typography with compact body, metadata, and navigation sizing.

Repository names, owner names, metrics, recency, tags, likes, and downloads are first-class visual content.

Product objects are the marketing: models, datasets, Spaces, organizations, libraries, and code are shown directly.

High information density is intentional. Do not “clean up” the interface until it looks like a generic sparse SaaS homepage.

Cards are mostly white with 1px borders; shadows are rare and subtle.

Border radius is modest: 6–12px for most product surfaces, full pills only for tags/badges/avatars.

Community identity is visible through real handles, organizations, update timestamps, counts, and the hugging-face mark.

Search is a primary navigation primitive, not an auxiliary utility.

Colors

Brand & Accent

HF Yellow / Primary ({colors.primary} — #FFD21E): Official Hugging Face yellow. Use for the logo/mark, small highlights, selected promotional emphasis, and signature community moments. Avoid using it as the default button fill everywhere.

HF Yellow Active ({colors.primary-active} — #FFB800): Darker interaction/pressed variant for yellow controls when needed.

HF Yellow Soft ({colors.primary-soft} — #FFF4BF): Pale yellow background for low-intensity callouts, badges, or highlighted educational content.

HF Orange / Secondary ({colors.secondary} — #FF9D00): Official companion orange. Use sparingly in the logo universe, gradient/illustration accents, or secondary branded moments.

HF Gray ({colors.muted} — #6B7280): Official brand gray and the baseline for secondary text/metadata.

Surface

Canvas ({colors.canvas} — #FFFFFF): Main page floor. Hugging Face is materially whiter and more utility-oriented than warm editorial AI brands.

Surface Soft ({colors.surface-soft} — #F9FAFB): Search boxes, large low-contrast areas, soft product backdrops.

Surface Card ({colors.surface-card} — #FFFFFF): Repository, organization, feature, and library cards. Separation comes from borders, not fill.

Surface Raised ({colors.surface-raised} — #FFFFFF): Menus/popovers; pair with a small shadow and stronger border.

Surface Muted ({colors.surface-muted} — #F3F4F6): Tags, compact chips, inactive controls, skeleton/loading surfaces.

Surface Dark ({colors.surface-dark} — #111827): Code windows or terminal-like demonstrations.

Surface Dark Elevated ({colors.surface-dark-elevated} — #1F2937): Nested code/terminal controls or darker popovers.

Hairline ({colors.hairline} — #E5E7EB): Standard 1px card/input/divider border.

Hairline Soft ({colors.hairline-soft} — #F3F4F6): Extremely subtle row separators and grouped list boundaries.

Text

Ink ({colors.ink} — #111827): Major headings, repository names, selected tabs, primary controls.

Body Strong ({colors.body-strong} — #1F2937): Strong paragraphs and compact titles.

Body ({colors.body} — #374151): Default running text.

Muted ({colors.muted} — #6B7280): Metadata, labels, timestamps, helper text.

Muted Soft ({colors.muted-soft} — #9CA3AF): Least-important metadata, disabled labels, icon placeholders.

Link ({colors.link} — #2563EB): Functional links where standard web affordance is beneficial. Do not force all links to yellow; yellow has poor text contrast on white.

On Primary ({colors.on-primary} — #111827): Dark text/icons on yellow.

On Dark ({colors.on-dark} — #F9FAFB): Code-panel primary text.

On Dark Soft ({colors.on-dark-soft} — #D1D5DB): Secondary code/terminal labels.

Semantic

Success ({colors.success} — #16A34A): Running/healthy/available indicators.

Warning ({colors.warning} — #D97706): Warnings, gated state, caution banners.

Error ({colors.error} — #DC2626): Validation failures, destructive actions, outages.

Info ({colors.info} — #2563EB): Documentation/info callouts and neutral technical links.

Color Principles for AI Agents

Keep at least 75–85% of large page surface area neutral white/light gray.

Do not use yellow for long body text.

Use yellow as recognition, not as continuous decoration.

Let thumbnails, avatars, logos, tags, and generated community content add color naturally.

Prefer border/spacing hierarchy before adding additional background colors.

Never introduce arbitrary purple/cyan gradients just because the product is “AI.”

Typography

Font Family

The system should use a neutral, modern system sans for almost everything. Prefer Inter when available, with ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, and Segoe UI fallbacks. Code uses a native monospace stack.

Unlike editorial AI brands, Hugging Face should not use a serif display face. The visual voice needs to remain continuous with developer tooling, repositories, documentation, tables, and account surfaces.

Inter/system sans 700 → major hero and top-level section headings

Inter/system sans 600 → card titles, repository names, tabs, compact feature headings

Inter/system sans 400–500 → body, metadata, navigation, buttons, labels

Native monospace → code, commands, API snippets, hashes, filenames when appropriate

Hierarchy

Token

Size

Weight

Line Height

Letter Spacing

Use

{typography.display-xl}

48px

700

1.08

-1.1px

Homepage hero statement

{typography.display-lg}

36px

700

1.15

-0.7px

Major section headings

{typography.display-md}

30px

700

1.2

-0.4px

Commercial/platform section headings

{typography.display-sm}

24px

600

1.25

-0.2px

Sub-section headings

{typography.title-lg}

20px

600

1.35

-0.1px

Large card/feature titles

{typography.title-md}

16px

600

1.4

0

Repository/card titles

{typography.title-sm}

14px

600

1.4

0

Compact labels and card section heads

{typography.body-lg}

18px

400

1.6

0

Hero supporting copy / lead text

{typography.body-md}

16px

400

1.55

0

Standard explanatory copy

{typography.body-sm}

14px

400

1.5

0

UI copy, cards, navigation-adjacent text

{typography.caption}

12px

500

1.4

0

Tags and compact badge labels

{typography.metadata}

12px

400

1.4

0

Likes, downloads, update times, owner details

{typography.code}

13px

400

1.55

0

Code and terminal snippets

{typography.button}

14px

500

1.0

0

Buttons

{typography.nav-link}

14px

500

1.4

0

Top navigation

Principles

Information hierarchy is created primarily by size + weight, not decorative typeface changes.

Do not over-enlarge headings. The site needs to transition smoothly from marketing into product/repository UI.

Repository names should be easy to scan and usually stronger than their metadata.

Metadata may be small, but it must remain legible; it is part of the product's trust signal.

Use monospace only where the content is actually code-like. Do not turn the whole interface into a terminal aesthetic.

Avoid all-caps marketing labels. Compact title case or sentence case fits the ecosystem better.

Layout

Spacing System

Base unit: 4px.

Tokens: {spacing.xxs} 4px · {spacing.xs} 8px · {spacing.sm} 12px · {spacing.md} 16px · {spacing.lg} 24px · {spacing.xl} 32px · {spacing.xxl} 48px · {spacing.section} 80px.

Hero vertical rhythm: 64–80px desktop, 40–56px mobile.

Repository/card padding: typically 12–20px; information-dense cards should not use oversized 32–48px padding.

Feature/commercial card padding: 24–32px.

List row spacing: 10–14px vertical.

Major sections: 64–96px depending on density; use less spacing around discovery grids than around brand/enterprise storytelling.

Grid & Container

Max content width: target 1280px centered for the marketing homepage.

Product/discovery surfaces: may extend wider when data density benefits from extra columns.

Hero: centered or gently constrained single-column message; avoid a forced 50/50 marketing split unless the second half contains a real product artifact.

Trending: 3-column desktop structure for Models / Spaces / Datasets; collapse progressively to one column.

Feature explanation: 2-column modules or 2×2 grid with large product-native illustrations.

Organizations: repeatable multi-column cards; 4-up desktop is a strong default.

Open-source libraries: dense 3–4 column grid of repository-like tiles.

Footer: 4-column link structure at desktop; stack cleanly on small screens.

Whitespace Philosophy

Hugging Face whitespace should feel practical, not luxurious. The interface needs enough room to scan but must retain the sense that a large, active ecosystem exists beneath every navigation path.

Good Hugging Face spacing says:

“There is a lot here, and it is organized.”

Bad Hugging Face spacing says:

“We removed half the information to make a prettier screenshot.”

Information Density Rules

Preserve repository name + owner/source context.

Preserve at least one activity signal when available (downloads, likes, update time, runs, followers).

Use compact gaps between metadata items (8–12px).

Prefer wrapping metadata to removing it on narrower widths.

Do not reduce cards to image + marketing title when the underlying object has useful technical information.

Elevation & Depth

Level

Treatment

Use

Flat

White canvas, no shadow

Main page bands, lists, hero

Hairline

1px {colors.hairline}

Repository cards, inputs, organization cards, library cards

Muted fill

{colors.surface-soft} / {colors.surface-muted}

Search, tags, grouped technical controls

Raised

White + border + very small shadow

Menus, popovers, floating selectors

Dark utility

{colors.surface-dark}

Code/terminal examples

The elevation philosophy is border first, shadow last. Hugging Face should not look like a floating-card dashboard with heavy drop shadows. Structural clarity comes from:

1px neutral borders,

white/soft-gray surface shifts,

compact spacing,

clear headings,

content imagery.

Shadow Guidance

When a shadow is necessary, keep it subtle, e.g. a low-alpha 0 1px 2px or 0 4px 12px for floating overlays only. Do not add shadows to every repository card.

Decorative Depth

Space thumbnails/previews provide natural visual depth.

Organization logos and avatars provide recognizable focal points.

Code blocks add dark contrast only where technically relevant.

The hugging-face mascot/logo may be rendered larger in the hero, but it should remain a brand mark rather than become a 3D character illustration system.

Shapes

Border Radius Scale

Token

Value

Use

{rounded.xs}

4px

Tiny controls, code/file chips

{rounded.sm}

6px

Compact buttons, menu items, repository sub-controls

{rounded.md}

8px

Inputs, standard buttons, search field, tabs with fill

{rounded.lg}

12px

Repository cards, organization cards, Space cards, feature modules

{rounded.xl}

16px

Large visual/product illustration frames only

{rounded.pill}

9999px

Tags, badges, compact status chips

{rounded.full}

9999px / 50%

Avatars, circular brand/icon marks

Image & Preview Behavior

Hugging Face should favor real product/community artifacts over generic illustration:

Space screenshots and app previews

Organization logos

User avatars

Model/dataset imagery when available

UI/activity-feed excerpts

Code/library examples

Task/modality diagrams grounded in actual platform taxonomies

Avoid photorealistic stock imagery and generic “AI brain/network” illustrations.

Components

Top Navigation

top-nav — A compact 64px white navigation bar with a subtle bottom hairline. The left cluster carries the Hugging Face mark/wordmark. A prominent {component.global-search} lets users search models, datasets, and users. Primary navigation exposes product nouns rather than abstract marketing categories: Models, Datasets, Spaces, Buckets, Docs, Enterprise, Pricing. Authentication actions remain at the right.

Agent rule: navigation is part of the product. Never remove global search from a desktop Hugging Face-style shell unless the page is a dedicated focused flow.

Global Search

global-search — Soft-gray or white-with-border field, approximately 40px tall, rounded {rounded.md}. Placeholder should explicitly name searchable object types. Search icon at left; keyboard shortcut hint may appear at right when appropriate.

Search results should group by object type and preserve owner/repository context.

Buttons

button-primary — Yellow brand button with dark text. Use selectively for high-value actions such as creating an account, creating a repository, or starting a key flow. Yellow's role is recognizability, not blanket conversion coloring.

button-secondary — White button with 1px gray border, dark text. This is the everyday workhorse action style.

button-ghost — Transparent control for low-priority actions inside dense product UI.

button-icon — 36px icon control with light border or ghost treatment. Use for star/like, share, overflow, filter, copy, and utility actions.

text-link — Standard functional text link. Blue or dark-underlined links are more legible for inline actions than yellow text.

Hero

hero-band — White, centered or slightly constrained hero. It should contain:

Hugging Face mark/mascot or small brand cue

Direct ecosystem statement

Short explanatory sentence

One primary exploration action

One catalog/browse action

The live homepage's content model is a strong pattern: identity statement → platform explanation → Explore Apps / Browse Models.

Do not clutter the hero with six pricing claims, customer logos, or animated gradients.

Trending / Discovery

trending-column — One category lane for Models, Spaces, or Datasets. Each lane has a compact heading, 4–6 current items, and a browse-all link.

repository-row — A compact list item for a model/dataset/library. Carry:

owner/repository name

update time or status

relevant counts (downloads/likes/stars)

optional task/modality/tag markers

Metrics should remain visually secondary but always easy to scan.

repository-card — Use when more description or tags are necessary. White background, 1px border, 12px radius, 16px padding. Do not center-align repository information.

Space Cards

space-card — Visual card for an interactive application. Place {component.space-preview} above or beside metadata. Carry:

Space title

creator/organization

preview thumbnail

short capability description

relevant engagement/running state

Unlike model/dataset rows, Spaces benefit from visual previews because the output/UI is part of the object.

Feature Modules

feature-card — 24px padding, white background, thin border or borderless within a 2-column section. Pair a concise value statement with a real product-native illustration. Typical concepts:

collaboration/activity feed

open-source stack / code

tasks/modalities

user portfolio/profile

Do not convert these into generic icon + 3-line SaaS cards if a real Hugging Face artifact can carry the point.

Organization Cards

organization-card — Show the organization as an active ecosystem participant, not just a logo. Carry:

logo/avatar

organization name

organization type/plan label where appropriate

model count or other repository activity

follower count

The social proof should feel inspectable.

Open-Source Library Cards

library-card — Repository-like tile for Transformers, Diffusers, Datasets, Tokenizers, TRL, PEFT, Accelerate, smolagents, etc. Carry:

library/repository name

short technical description

star/engagement count when available

optional language or ecosystem badge

This is technical authority proof. Keep it concrete.

Metadata

metadata-inline — 12px muted row used for update time, downloads, likes, followers, status, and plan labels. Iconography should be minimal and recognizable.

Metadata order recommendation:

recency/status

usage count

appreciation/social count

optional task/license/language

Use separators (•) or 8–12px gaps rather than boxed chips for every metric.

Tags / Badges

tag-pill — Neutral gray pill for task, framework, license, modality, or category tags. Keep compact.

tag-yellow — Soft yellow tag for a truly branded/featured/important state. Do not make every tag yellow.

Avoid a rainbow of badge colors unless the color encodes meaningful categories.

Code Window

code-window-card — Dark technical surface for actual commands or code. Use native monospace, preserve line breaks, enable copy action, and never use fake decorative code. On mobile, allow horizontal scroll before wrapping commands in ways that make them invalid.

Pricing / Enterprise

pricing-card — White with border, 24px padding, 12px radius. Pricing should remain explicit and technical where possible. Avoid visually isolating enterprise from the open ecosystem: frame paid tiers as additional compute, governance, security, support, or private collaboration layered onto the same platform.

Tabs / Filters

tabs — Compact text tabs with bottom border or minimal active state. The default aesthetic should resemble repository/product navigation more than marketing pill navigation.

tab-active — Darker text + stronger bottom border. Use filled pills only when the control behaves like a filter chip rather than page-level navigation.

Inputs & Forms

text-input — 40px height, white background, gray hairline, 8px radius. Keep forms utilitarian and compact.

text-input-focused — Strengthen border/outline enough for accessibility. Do not turn focus states into large glowing gradients.

Footer

footer — White/light footer with a top border. Use compact 4-column navigation covering Website, Company, Resources, Social or equivalent. Preserve system-theme controls where relevant. The footer should feel like the final utility directory, not a dramatic dark brand finale.

Do's and Don'ts

Do

Anchor pages on a white/light-neutral canvas.

Use official Hugging Face yellow (#FFD21E) and orange (#FF9D00) for recognizable branded moments.

Make global search prominent on discovery-oriented surfaces.

Preserve repository names, owners, tags, metrics, and timestamps.

Show real models, datasets, Spaces, organizations, libraries, profile/activity UI, and code.

Use 1px neutral borders as the primary grouping device.

Keep cards compact enough that multiple ecosystem objects are visible above the fold.

Treat community activity as social proof.

Use system-sans typography throughout the product/marketing bridge.

Prefer sentence case and technical clarity over advertising language.

Let real content create visual variation.

Keep the interface friendly through the Hugging Face mark, approachable copy, and visible community handles.

Reference components via {component.*} keys and colors/spacing via {token.refs}.

Don't

Don't redesign Hugging Face into a sparse luxury-AI landing page.

Don't use dark mode as the default marketing canvas unless the project specifically targets a dark product surface.

Don't replace repository lists with generic feature cards.

Don't hide downloads, likes, update times, followers, or ownership when they matter to trust.

Don't use yellow body text on white.

Don't flood the interface with yellow backgrounds.

Don't introduce neon purple/blue “AI gradients” as a brand device.

Don't use huge 80–120px hero typography that breaks continuity with the Hub.

Don't use serif display fonts.

Don't use heavy shadows around every card.

Don't make every badge a different color.

Don't invent fake metrics or fake repository names in high-fidelity mockups when real/placeholder-safe data is available.

Don't illustrate code; show real code snippets when code is the point.

Don't remove density merely to create whitespace.

Responsive Behavior

Breakpoints

Name

Width

Key Changes

Mobile

< 640px

Nav collapses; search becomes full-width or dedicated control; hero 48→34px; trending columns stack; feature modules stack; organization/library grids 1-up; footer stacks

Small tablet

640–768px

2-up cards where space permits; repository metadata may wrap; search remains prominent

Tablet

768–1024px

Top nav may collapse secondary links; trending may become 2+1 or stacked; organization/library grids 2–3 up

Desktop

1024–1440px

Full navigation/search; 3-column trending; 2-column features; 4-up organizations; 3–4-up libraries

Wide

> 1440px

Maintain readable max width; increase outer margins rather than endlessly widening cards

Touch Targets

Standard buttons/inputs: minimum 40px visual height; target 44px interactive area where possible.

Icon buttons: minimum 36px visual with padded hit area to ~44px.

Entire repository/organization/Space row may be clickable, but nested actions must remain independently accessible.

Tags that are interactive filters need at least ~32px height or expanded invisible hit area.

Collapsing Strategy

Preserve content order, not desktop geometry.

Hero copy comes before hero/supporting artifact.

Trending categories stack Models → Spaces → Datasets unless product priorities specify otherwise.

Metadata wraps to a second line rather than disappearing.

Repository owner/name should never be truncated so aggressively that identity is lost; prefer responsive width, title/tooltip, or controlled middle truncation for long technical names.

Large image previews scale proportionally; avoid fixed desktop heights that crop key UI.

Code remains monospace and horizontally scrollable when necessary.

Navigation search can become a dedicated search button/overlay, but search must remain one tap away.

Mobile Density

Do not overcorrect density on mobile. The goal is vertical clarity, not information deletion. A strong mobile repository item can still show:

name

owner

one-line description or task

2–3 metadata signals

Accessibility

Contrast

Never place white text on {colors.primary} yellow.

Use {colors.on-primary} dark text on yellow.

Muted metadata must still meet readable contrast on white; do not use extremely faint gray for essential counts/status.

Focus indicators must be visible on both white and soft-gray backgrounds.

Keyboard & Focus

Global search is reachable near the start of tab order.

Cards with nested controls should not create confusing double-focus behavior.

Repository rows need a clear primary link target.

Tabs must expose selected state programmatically.

Modal/search overlays must trap focus correctly and restore focus on close.

Motion

Keep transitions short and functional (menus, hover feedback, preview loading).

Avoid ambient motion behind dense repository information.

Honor prefers-reduced-motion.

Content & Voice

Tone

Hugging Face copy should feel:

collaborative

technically literate

optimistic

direct

community-oriented

playful in small doses

Use nouns developers recognize: models, datasets, Spaces, repositories, inference, endpoints, libraries, organizations, tasks, modalities.

Avoid replacing precise technical nouns with abstract enterprise language.

CTA Language

Prefer action labels such as:

Explore AI Apps

Browse models

View dataset

Open Space

View pricing

Getting started

Sign Up

Create repository

Avoid vague CTAs like “Unlock innovation” or “Transform your journey.”

Social Proof

Prefer verifiable activity signals:

model count

download count

likes/stars

followers

updated time

organization activity

library popularity

These are stronger than generic testimonial quotes for a developer ecosystem.

AI-Agent Implementation Rules

Inspect before inventing. If reproducing an existing Hugging Face surface, identify whether the object is a model, dataset, Space, organization, library, pricing card, or documentation surface before selecting a component.

Preserve object identity. Never strip owner/repository naming into a generic title if the content is repository-based.

Prefer real structure over visual imitation. A card that looks right but omits metadata hierarchy is not Hugging Face-like.

Use tokens. Reference {colors.*}, {typography.*}, {rounded.*}, {spacing.*}, and {component.*} rather than adding one-off styles.

Default to border-first depth. Do not add shadows unless the element floats above the page.

Default to compact UI. Start with 12–24px card padding, not 32–48px.

Keep yellow scarce. Before adding yellow, ask whether the element is brand-significant, primary, featured, or status-relevant. If not, use neutral styling.

Show activity. When designing discovery cards, include real or placeholder-safe recency/engagement metadata.

Make search obvious. Any Hub-like browsing shell should provide prominent search/filter access.

Use product artifacts. For illustrations, prefer screenshots/previews/code/activity feeds over abstract shapes.

Do not hallucinate unsupported metrics. When real data is unavailable, use clearly labeled placeholders or omit the count.

Respect content variability. Repository names, descriptions, tags, and counts can be long. Test overflow and wrapping.

Build light and dark states separately. Do not assume inverting every neutral token creates a valid dark theme.

Test keyboard navigation. Dense interfaces need strong focus order and focus visibility.

Test at data extremes. Validate cards with zero tags, many tags, huge counts, no thumbnail, long organization names, and very recent/very old timestamps.

Iteration Guide

Focus on one component family at a time: navigation/search, repository rows/cards, Space cards, organization cards, feature modules, enterprise cards, or library cards.

Reference the relevant YAML key ({component.repository-card}, {component.global-search}, etc.) in implementation notes.

Use {token.refs} everywhere; avoid inline hex/radius/spacing unless creating a new documented token.

Verify whether a style is brand-official or reconstructed implementation guidance before treating it as immutable.

Preserve the core trinity: neutral canvas + gray structure + yellow/orange identity.

Validate density at 1440px, 1024px, 768px, and 390px widths.

For repository-like components, iterate hierarchy in this order:

owner/name

object description/task

metadata

tags

secondary actions

For Space cards, iterate preview quality before adding decorative styling.

For enterprise/commercial modules, maintain continuity with the open Hub. Add governance/compute information without changing to an unrelated corporate visual system.

When emphasis is weak, first increase type weight/contrast or grouping; do not immediately add a new color.

When a page feels too empty, add meaningful platform content before decorative illustration.

When a page feels too busy, simplify duplicated metadata or strengthen grouping before removing core technical information.

Known Gaps

Only the yellow (#FFD21E), orange (#FF9D00), and gray (#6B7280) colors in this document are asserted as official Hugging Face brand colors from the public brand-assets page. The broader neutral/semantic palette is a practical reconstruction for agent implementation and should be revalidated against the current production CSS when pixel accuracy is required.

Exact production font files/family declarations are not formalized here. Inter + system-sans is the recommended implementation approximation for the observed developer/UI voice.

Exact hover/transition timings are not extracted. Use restrained 100–200ms functional transitions unless the production surface is being replicated from source.

Dark-theme tokens are intentionally incomplete. Hugging Face supports theme switching, but a production-quality dark theme should be extracted from live styles rather than generated by naive inversion.

The homepage is only one part of the design language. Model pages, dataset pages, Spaces, organization pages, docs, settings, billing, and HuggingChat introduce additional specialized components not fully covered here.

Repository task badges, framework badges, license markers, gated/private states, discussions, file browsers, and commit/history UI require additional component-level extraction for full Hub parity.

Live counts, trending items, model names, dataset names, and organization statistics are dynamic content and must never be hard-coded as design tokens.

The hugging-face logo/emoji is a brand asset; use the official asset instead of redrawing or approximating it.

This document is a design/implementation guide for AI agents, not an official Hugging Face design-system specification.
