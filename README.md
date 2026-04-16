# Atreides is Coming

A teaser landing page for Atreides Prime, the orchestration layer above Claude Code, OpenCode, Codex, and Pi.

## What this is

A demo of **Claude Opus 4.7 on high reasoning**, building a production-grade marketing page from context gathered by a spawned agent team.

The build process:

1. A lead agent (Shadow) received the brief.
2. A three-agent research team was spawned in parallel to gather context from an Obsidian knowledge vault: product vision and positioning, visual language and theme tokens, and the DNA story of how the product came to be.
3. The lead agent synthesized the returned briefs into a consolidated design direction.
4. The lead agent committed to a bold aesthetic direction and implemented the page as a single HTML file with embedded styling.
5. An SD2SU (Slow Down to Speed Up) review gate ran before delivery to catch anything flagged but deferred during the build.

Total wall-clock time from brief to delivery: minutes.

## Stack

- Single `index.html` file
- Vanilla HTML, CSS, and minimal JavaScript
- Google Fonts: DM Sans, Fraunces, JetBrains Mono
- No build step, no bundler, no framework

## Theme

Caladan Night, from the Atreides design system. Deep navy backgrounds layered in five lightness steps, storm blue as the single accent, tinted foregrounds (no pure white, no pure black), subtle fractal noise overlay for atmosphere, and an ambient breathing animation behind the glow.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Credits

- **Atreides design system:** Leto Prime (CDO, Ambitious Realism)
- **Design philosophy:** "Calm authority, not reactive scramble."
- **Build:** Shadow K, operating on Claude Opus 4.7 via Claude Code
