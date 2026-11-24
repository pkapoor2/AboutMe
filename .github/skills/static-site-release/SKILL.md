---
name: static-site-release
description: 'Use when validating, committing, pushing, or checking deployment of the AboutMe static website; includes browser accessibility, privacy review, and Git submodule release boundaries.'
---

# Static website release SDLC

1. **Preflight:** inspect repository root, status, remotes and branch. If nested as a submodule, operate in the website repository, not the parent application. Completion: intended public remote and staged scope are explicit; unrelated work is preserved.
2. **Validate:** check editor diagnostics and diff whitespace. Preview the local HTML in the integrated browser. Verify title/headings, all internal anchors, mobile menu including keyboard/Escape and expanded state, details controls, and no horizontal overflow at narrow/mobile/desktop widths. Check reduced motion and external asset requests. Completion: checks pass or specific blockers are recorded.
3. **Privacy gate:** review full staged content and file list. Keep only explicit site/docs/skill paths; exclude credentials, local settings, private directories, documents, databases and logs. Scan findings require inspection; absence of a pattern match is not proof of no secrets. Completion: every staged file is intended for public disclosure.
4. **Commit:** stage an explicit allowlist after user-authorized release. Use existing Git identity without requesting secrets. Fetch remote state and inspect divergence. Completion: commit contains only reviewed website changes; conflicts or unexpected upstream changes halt release for reconciliation.
5. **Push:** use a normal non-force push to the intended branch. Humans handle any secret authentication or protected-branch approval. Completion: remote branch hash matches the local commit; report commit and push separately from deployment.
6. **Deployment:** inspect visible GitHub deployment status and published site when available. A successful push is not proof a new site is live. Completion: state either verified live content, pending deployment, or a specific failure—never invent success.
7. **Parent boundary:** a website commit changes its parent's submodule pointer. Update/commit/push the parent only if requested; avoid bundling unrelated application changes. Completion: clearly report whether the parent pointer remains local.

## Recovery

Preserve failed checks and narrow fixes to the regression. Avoid force pushes, destructive resets, invented tests or endless polling. For background deployment, report pending status rather than blocking or repeatedly querying.