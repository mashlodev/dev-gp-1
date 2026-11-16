# Golden Path

My 60-week path from designer to front-end design-engineer: HTML, CSS, JavaScript, motion, React, Next.js, WebGL — built by hand.

**Live builds:** `https://<your-username>.github.io/golden-path/`

## Progress

| Phase | Name                 | Weeks | Status         | Gate |
| ----- | -------------------- | ----- | -------------- | ---- |
| 00    | Set the Stage        | 1     | 🟡 in progress | —    |
| 01    | The Platform         | 2–7   | ⚪             | —    |
| 02    | JavaScript, for Real | 8–15  | ⚪             | —    |
| 03    | Motion Engineering   | 16–23 | ⚪             | —    |
| 04    | Engineering Toolkit  | 24–32 | ⚪             | —    |
| 05    | Production           | 33–40 | ⚪             | —    |
| 06    | Under the Hood       | 41–44 | ⚪             | —    |
| 07    | WebGL & Shaders      | 45–54 | ⚪             | —    |
| 08    | Signature            | 55–60 | ⚪             | —    |

## Repo map

```
golden-path/
├── .github/workflows/ci.yml   # format check, HTML validation, secret scan, deploy to Pages
├── index.html                 # hub page: links to every live build
├── baseline/                  # Week 1 drill. Never edited after it's committed.
├── phase-00-setup/            # Week 1 notes: motion diary
├── phase-01-platform/         # created in week 2, one subfolder per build
├── devlog/                    # one file per day, from _template.md
├── gates/                     # one scorecard per phase gate (G0.md, G1.md…)
├── design/                    # design-path notes: Figma links, baselines, skill radar
└── later.md                   # parked ideas, so they don't derail the plan
```

## Conventions

- **Folders:** `phase-NN-name/build-name/` with an `index.html` per build, e.g. `phase-01-platform/editorial-grid/`.
- **Commits:** Conventional Commits: `feat: …`, `fix: …`, `docs: …`, `chore: …`, `style: …`.
- **Branches:** commit to `main` in Phase 00. From Phase 01, one short-lived branch per build, merged when CI is green.
- **Devlog:** `devlog/YYYY-MM-DD.md`, written at the end of every session.
- **Before pushing:** `npm run format`, then `npm run check`.
- **Rules:** type, never paste. Docs before AI. Ship every Saturday. Gates are never skipped.
