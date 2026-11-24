# AboutMe

Prateek Kapoor's public professional website: hands-on cloud engineering leadership, a four-stage journey into engineering agents, system disciplines, career history, personal experimentation, education, and contact.

## Preview

Open [index.html](index.html) directly in a browser. No installation, build step, server, or internet connection is required to render the page. It uses embedded CSS, system fonts, and a small navigation script; there are no dependencies, analytics, external fonts, images, or other external assets. External professional and research links require internet access only when followed.

The mobile navigation supports keyboard interaction, expanded-state announcements, Escape to close, and focus restoration. Without JavaScript, navigation links remain visible. Past roles and architecture notes use native expandable details. Layouts adapt to narrow screens, and smooth scrolling respects reduced-motion preferences.

## Agent-readable profile

- Embedded Schema.org JSON-LD describes the `ProfilePage` and its `Person`, including role, organization, expertise, and public identity links. It is static data, not an external script or service.
- [profile.md](profile.md) provides the approved public narrative as plain Markdown. A visible footer link and an HTML alternate link make it discoverable.
- The canonical URL is https://pkapoor2.github.io/AboutMe/. The Markdown profile is published alongside it at https://pkapoor2.github.io/AboutMe/profile.md.
- Keep the page, JSON-LD, and Markdown aligned when changing public facts. Validate JSON syntax and compare role, identity links, metrics, dates, ownership, and benchmark scope before release. Update the Markdown revision date when its content changes.

The HTML remains readable without JavaScript. No WebMCP endpoint, agent tools, external requests, or private-data integration is introduced. Structured metadata improves machine readability; it does not guarantee discovery or indexing by any particular agent or search engine.

## Update and content decisions

- Updated current and previous roles and dates, and separated 15 direct reports from approximately 260 daily active engineers, measured through router OpenTelemetry instrumentation.
- Distinguished initial components built by Prateek from team extensions to retrieval/routing and the team's private inference stack. Live engineering workflows are described at a high level.
- Explained bounded review, accepted outputs, memory lifecycle, role permissions, and selective human escalation in direct engineering language.
- Presented the linked personal engineering benchmark with its paid token spend, elapsed time, and cost–latency tradeoff.
- Updated education using the exact program and degree names.
- Retained the existing GitHub and email destinations and added the reviewed LinkedIn profile and personal benchmark links.
- Removed Tailwind CDN and Google Fonts. The page makes no automatic external requests and does not import or fetch private data.

## Public boundaries

Publish only explicitly approved professional information. Use assertive, factual public copy; keep internal evidence-review and audit-status notes out of the public narrative. Preserve metric definitions, personal-project scope, and individual/team attribution. Keep architecture high-level. Do not publish sensitive personal records, raw source documents, credentials, confidential infrastructure details, or proprietary employer identifiers. This page has no automatic data synchronization.

## SDLC handoff

Reusable workspace skills are included: [public-profile-content](.github/skills/public-profile-content/SKILL.md) covers evidence and public disclosure boundaries; [static-site-release](.github/skills/static-site-release/SKILL.md) covers browser validation, staged privacy review, publication and submodule boundaries.

Before release, check desktop and narrow-screen layouts, keyboard navigation, expandable sections, internal anchors, external destinations, reduced-motion behavior, and the absence of external asset requests. Review content attribution separately from UI validation.

This website is an independent Git submodule in the Applywise workspace. Website commits and pushes are made in this repository; parent application changes and its submodule reference are handled separately. Push only after explicit publication authorization and successful release checks.
