> **Archived (September 2026).** Two scaffold commits for a computational-physics hobby track (July 2026): a plan and zero shipped sprints. The roadmap was gitignored, so the repo never even contained it. If the idea revives, it starts somewhere the plan is committed.

# Computational Physics — Workspace

An intellectual-hobby track: rebuild math and physics by **building things that move on screen**. Not a career switch — a boredom-killer that keeps the brain sharp for the paycheck work. Full plan lives in `init/Computational-Physics-Roadmap.md` (private, gitignored).

## Where am I right now
- **Current sprint:** Y1S0 — Projectile → `sprints/y1s0-projectile/`
- **Status:** not started

## The four rules
1. **Project-first.** Every sprint ships one visual artifact. Math is learned just-in-time, never in a vacuum. (This is the anti-C++ vaccine.)
2. **Ship in public.** One short blog post per artifact.
3. **Two languages, two jobs.** Python (explore + plot) inside the sprint; Go (tested engine) in `engine-go/`.
4. **Guilt-free pause.** Each sprint folder is self-contained — vanish during a release crunch, resume without reconstructing anything.

## Map
| Folder | What lives here |
|---|---|
| `init/` | Private strategy brain (roadmap + questionnaire). **Gitignored.** |
| `sprints/` | The work. One self-contained folder per sprint. |
| `engine-go/` | Cumulative, tested Go engine. Portfolio centerpiece. |
| `math/` | Just-in-time math notes, cross-cutting. |
| `blog/` | Shipped posts (promoted from sprint drafts). |
| `resources/` | Curated free resources. |

## The loop, per sprint
Open the sprint README → learn just enough math (`notes.md`) → build in `explore.py` → produce the artifact in `output/` → re-build a tested version in `engine-go/` → draft `blog-draft.md` → ship it to `blog/` → log it in `PROGRESS.md`.
