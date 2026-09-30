# AGENTS.md

## Architecture

A single static page with no build step or dependencies.

- `index.html` — the whole site: shows the word "duck" (lowercase) centered on the page, with the word "cheese" in smaller text directly below it, using inline CSS.
- `netlify.toml` — publishes the repository root.

## Conventions

- The word must stay exactly "duck" — lowercase, no punctuation. This was an explicit requirement.
- Keep the site dependency-free unless a future request calls for more.
