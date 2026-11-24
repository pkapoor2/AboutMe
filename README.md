# AboutMe

Prateek Kapoor's public professional website: hands-on cloud engineering leadership, a four-stage journey into engineering agents, system disciplines, career history, personal experimentation, education, and contact.

## Preview

Open [index.html](index.html) directly in a browser. No installation, build step, server, or internet connection is required to render the page. It uses embedded CSS, system fonts, and a small navigation script; there are no dependencies, analytics, external fonts, images, or other external assets. External professional and research links require internet access only when followed.

The mobile navigation supports keyboard interaction, expanded-state announcements, Escape to close, and focus restoration. Without JavaScript, navigation links remain visible. Past roles and architecture notes use native expandable details. Layouts adapt to narrow screens, and smooth scrolling respects reduced-motion preferences.

## Update and content decisions

- Corrected current and previous roles and dates, and separated 15 direct reports from approximately 260 daily active agent users. The usage figure is user-reported from router OpenTelemetry instrumentation, not independently audited.
- Distinguished initial components built by Prateek from team extensions to retrieval/routing and the team's private inference stack. Live engineering workflows are described at a high level.
- Explained bounded review, accepted outputs, memory lifecycle, role permissions, and selective human escalation without claiming guaranteed correctness or model-weight training.
- Clearly labeled the linked benchmark as a personal engineering project and an author-reported result. It compares paid token spend and elapsed time, not total cost of ownership or employer savings; the latency tradeoff remains visible.
- Updated education, identifying the Purdue AI/ML program as a professional program rather than a graduate degree. Omitted unsupported broad savings ratios, unresolved patent counts, and GPA.
- Retained the existing GitHub and email destinations and added the reviewed LinkedIn profile and personal benchmark links.
- Removed Tailwind CDN and Google Fonts. The page makes no automatic external requests and does not import or fetch private data.

## Public boundaries

Publish only explicitly approved professional information. Keep architecture high-level and distinguish personal experiments, reported usage, team contributions, and measured outcomes. Do not publish sensitive personal records, raw source documents, credentials, confidential infrastructure details, or proprietary employer identifiers. This page has no automatic data synchronization.

## SDLC handoff

Reusable workspace skills are included: [public-profile-content](.github/skills/public-profile-content/SKILL.md) covers evidence and public disclosure boundaries; [static-site-release](.github/skills/static-site-release/SKILL.md) covers browser validation, staged privacy review, publication and submodule boundaries.

Before release, check desktop and narrow-screen layouts, keyboard navigation, expandable sections, internal anchors, external destinations, reduced-motion behavior, and the absence of external asset requests. Review content attribution separately from UI validation.

This website is an independent Git submodule in the Applywise workspace. Website commits and pushes are made in this repository; parent application changes and its submodule reference are handled separately. Push only after explicit publication authorization and successful release checks.
