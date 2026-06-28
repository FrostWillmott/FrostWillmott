# Project Notes — FrostWillmott (GitHub Profile Repo)

## Project Structure
- Personal GitHub profile repository (README.md only)
- No source code; purely a profile/portfolio page
- `.junie/plans/` — Junie session plans folder

## Git Workflow
- Personal tool folders (.idea/, .cursor/) go in `.git/info/exclude`, NOT `.gitignore`
- `.gitignore` removed (was empty and useless for a profile repo)

## README Sections (as of 2026-06-28)
1. About Me
2. Tech Stack (Python, Django, DRF, FastAPI, Docker, PostgreSQL, Redis, Celery, etc.)
3. Education & Certificates
4. Current Focus
5. Contacts (GitHub, LinkedIn, Telegram badges)

Note: Projects section removed — listed repos (foodgram-project, api_yamdb, kittygram) were outdated; current projects are shown via GitHub pinned repos directly.

## Discovered Issues (fixed)
- .gitignore was empty → deleted; .idea/ and .cursor/ added to .git/info/exclude
- README.md was missing the Contacts section → restored

## Git Workflow Notes
- Remote can diverge (force-push or edits via GitHub UI); always `git pull --rebase` before pushing.
- Rebase conflicts on README.md: resolve by keeping the local (improved) version, then `GIT_EDITOR=true git rebase --continue`.
