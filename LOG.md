# Log

## 2026-10-07

- Created project logs (CLAUDE.md, AGENTS.md, STATE.md, LOG.md), following the ACT FS26 folder's pattern. Folder held only the CCIS undergraduate catalog PDF. Project purpose not yet recorded.
- Jon: no git for now. Project goal: build a database of possible OER textbooks for the courses "we" teach.
- Pulled the PSYC course list from the catalog (46 listings incl. topics, directed study, internships, research). Scope ("we" = which courses) and database format not yet decided.

## 2026-10-08

- Explained CC licenses to Jon (remixable vs. ND; SA/NC carry-through; combining rules).
- Jon: make the folder a git repo and build a website for faculty. His vision: faculty adopt good open texts outright or remix a couple with AI into a better one. Needs a licenses page.
- `git init` (local only). Catalog PDF gitignored. Site is plain HTML with Psych-AI-Pilot's `shared.css` plus a few added classes.
- Drafted `index.html` and `licenses.html`. Checked rendering at desktop and phone width; used non-breaking hyphens so license names don't split on phones.
- License content and the repository list (OpenStax, Open Textbook Library, LibreTexts, Noba, OER Commons, OASIS) come from field knowledge, not Jon's materials, so they are flagged for his review.
