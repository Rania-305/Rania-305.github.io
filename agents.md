# Agent Guardrails for This Repository

This is Rania's personal portfolio site, targeting GTM Strategy & Operations and Corporate Strategy roles in tech. [PRD.md](PRD.md) is the source of truth for scope, content, and requirements — read it before making changes, and flag any conflict between a request and the PRD instead of silently picking one.

## Content Integrity

- Never invent dates, titles, employers, metrics, or outcomes. If a fact isn't confirmed in the PRD or provided by Rania, leave it out or mark it `TODO: confirm`.
- Do not publish confidential employer, customer, or employee information (e.g., Kaseya specifics beyond what PRD.md already sanitizes).
- Do not state or imply a causal business outcome (e.g., "prevented $X in revenue loss") unless the figure and attribution are explicitly approved.
- Keep project write-ups scoped to what is disclosable; when in doubt, generalize rather than guess.

## Security & Privacy

- Never commit secrets, API keys, tokens, or `.env` files.
- Any contact form or third-party integration (analytics, forms backend, embeds) must disclose what data it collects and must not add tracking without flagging it to Rania first.
- Do not add dependencies that phone home or fetch remote scripts unless necessary and reviewed.

## Quality Bar

- Every page must be responsive and usable on mobile, tablet, and desktop.
- Follow basic accessibility practices: semantic HTML, alt text on informative images, visible focus states, sufficient color contrast, keyboard-navigable UI.
- Keep the site fast and dependency-light — this is a static GitHub Pages site; avoid heavy frameworks or build steps unless the PRD's platform decision changes.
- Test that navigation, resume, and contact links actually work after changes.

## Process

- Prefer small, reviewable changes over large rewrites; don't restructure content or design decisions from the PRD without calling it out.
- Don't push to remote, force-push, or rewrite git history without explicit approval.
- If a request would violate one of the above, say so and propose a compliant alternative instead of proceeding.
