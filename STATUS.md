# Project Status — Handoff Notes

> Read this first if you're a new Claude Code session picking up this repo.

## Where we are

- **Repo:** `shaquiranelson7-dev/figma-to-code-home-improvement-social-`
- **Working branch:** `claude/document-setup-status-ceSid` (develop + push here only)
- **Setup done:** The full **website-base** Figma-to-Code starter template
  (from `Produlis/website-base`) is committed — `.claude/` (agents,
  commands, rules, skills, settings), `CLAUDE.md`, `DESIGN-SYSTEM.md`,
  `global.css`, `best-practice/`, `README.md`, `LICENSE`, `.gitignore`.
- **No framework scaffolded yet** — `package.json` does not exist. The
  pipeline's "Phase init" (framework setup) has NOT run.

## The task

Build the **first page** from this Figma design:

`https://www.figma.com/design/sdLaVofRVJRIdYko2En4hi/upmind?node-id=1-178`

- Figma file key: `sdLaVofRVJRIdYko2En4hi`
- Target node: `1-178`

## Blocker (why we moved sessions)

The Figma MCP connector (`mcp__claude_ai_Figma__*`: `get_metadata`,
`get_design_context`, `get_screenshot`) was **NOT attached** to the
previous environment. The Figma-to-Code pipeline depends on it.
`WebFetch` cannot read Figma design URLs (auth + canvas-rendered).

**Before continuing, confirm the Figma connector is enabled on THIS
environment and OAuth is complete.** Verify with ToolSearch for
`mcp__claude_ai_Figma__get_metadata` — if it's not found, the connector
still isn't attached; tell the user before proceeding.

## Next steps (once Figma MCP is confirmed live)

1. **Phase init** — detect framework (none yet) → ask user Astro vs
   Next.js → scaffold into this dir (don't wipe `.claude/`, `CLAUDE.md`,
   `global.css`, etc.) → move `global.css` to framework location.
2. **Phase 0** — `get_metadata` + `get_design_context` +
   `get_screenshot` on the first Figma page → write `PROJECT_BRIEF.md`
   → update `global.css` design tokens.
3. **Phase 1** — analyze design, write `SITE_MAP.md` (with fileKey +
   per-section nodeIds), download all images to the static assets dir,
   write `IMAGE_MANIFEST.md`.
4. **Phase 2** — build the first page / node `1-178`.
5. **Phase 3+** — QA, responsive, SEO per `.claude/rules/`.

Follow the playbooks in `.claude/rules/phase-*.md`.

## Suggested kickoff message for the new session

> "This repo has the website-base template on branch
> `claude/document-setup-status-ceSid`. Read STATUS.md. The Figma
> connector is now enabled — build the first page from
> https://www.figma.com/design/sdLaVofRVJRIdYko2En4hi/upmind?node-id=1-178"
