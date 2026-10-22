# Lab folders

One folder per lab. Each lab page tells you which folder to work in; the AI saves its files there.

| Folder | Made in | What goes in it |
| --- | --- | --- |
| `lab01-research-areas` | Lab 1 (research areas) | `lab01-uist-papers.json`, `technology.md`, `technologies.png`, `research_area.png`, `notes.md` |
| `lab02-idea-patterns` | Homework 1 (install), Step 5 | `semantic-scholar-key.txt` (never in git); in Lab 2 (idea patterns): `codebook.md`, `technology.md`, `not-carried-over.xlsx`, `notes.md` |
| `lab02-idea-review` | Homework 2b (your idea as a mini abstract) | `idea.md` with your idea; Lab 3 (idea evaluation interview) adds `ai-rating.md` and `lab03-routes-by-pattern.md` next to it |
| `lab03-feasibility` | Lab 3 (idea evaluation interview) | `notes.md`; your ratings are on a paper sheet, not in any file, so the AI does not see them. The rest of Lab 3 works in `lab02-idea-review`, next to your idea |
| `lab04-reviews` | Lab 4 (simulated reviewers) | `reviews-v1.md` and the later reviews |
| `lab04-uist-paper` | Homework 2a (Overleaf) | Your paper, cloned from Overleaf; Labs 4 to 15 write into it. Not in the starter: the clone makes this folder |
| `lab05-citations` | Lab 5 (related work) | Nothing yet: Lab 5 writes `claude-memory.bib`, `claude-web.bib` and `sections/related-work.tex` into your paper |
| `lab06-crossref` | Lab 6 (verified source) | Nothing yet: Lab 6 works on the `.bib` files in your paper. The skills you build go in `../.claude/skills/` |
| `lab07-hello` | Homework 5 (first MCP server) | `pyproject.toml` and your first server |
| `lab07-closest-papers` | Lab 7 (claims) | `closest-papers.md`, and `papers/` with the PDFs (kept out of git) |
| `lab08-system-section` | Lab 8 (system section) | `idea.md`, `claims.md`, `skeleton.md`, `contributions.md`, `notes.md` |
| `lab09-build-route` | Lab 9 (build route) | `build-plan.md`, `route-options.md`, `routes-in-papers.csv`, `notes.md` |
| `lab10-evaluation` | Lab 10 (technical evaluation) | `eval-adapted.md`, `evaluations.csv` |
| `lab11-applications` | Lab 11 (applications) | `capabilities.md`, `applications-in-papers.csv`, `apps-from-edges.md`, `notes.md` |
| `lab12-decisions` | Lab 12 (design decisions) | `decisions.md`, `attacks.md`, `notes.md` |
| `lab13-introduction` | Lab 13 (introduction) | `intro-from-abstract.md`, `ledger.md`, `overlap.md`, `notes.md` |
| `lab14-writing` | Lab 14 (writing with AI) | To come |
| `lab15-project-pages` | Lab 15 (project page) | Your project page |

Each folder starts with an empty file `.gitkeep`, so git keeps the folder before it has anything else in it. You can ignore it.
