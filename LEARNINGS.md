# Learnings Log

Update this file after every working session.

---

## Session — 2026-06-16

### What worked
- Scaffolded Next.js 14 + TypeScript + Tailwind + Zustand via Claude Code
- Installed Bun, Vercel CLI, and GitHub CLI in one session

### What broke
- Homebrew permissions needed manual `sudo chown` fix (couldn't run from Claude Code)
- Next.js scaffold rejected the folder name "Doggie Subscription" — spaces and caps not allowed; used `doggie-subscription` subdirectory instead

### What I'd do differently
- Create the project folder with a URL-safe name (lowercase, hyphens only) from the start
