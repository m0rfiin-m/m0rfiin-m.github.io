# m0rfiin-blog

Marco Morfin's own Hugo portfolio and blog, live at https://m0rfiin-m.github.io (repo: github.com/m0rfiin-m/m0rfiin-blog). It's a portfolio first and a journal second: it supports his professional brand and his Full Sail coursework, covering entertainment tech and AI.

## Files and publishing

- Public pages: posts in `content/posts/`, portfolio pieces in `content/work/`, plus `content/about.md` and `content/resume.md`. Layouts in `layouts/`, theme in `themes/morfiin-minimal/`, images in `static/images/`. Never hand-edit the generated `public/` folder.
- Private material and the single review draft go in `docs/`: planning in `docs/Tracking/`, portfolio source notes in `docs/Portfolio/`, sources in `docs/Reference/`, review drafts in `docs/Review/`. No draft or conflict files in `content/`.
- Match existing posts for formatting and frontmatter. Topic-first, hyphenated filenames. Use existing content folders unless Marco asks for a new one.
- Publish, commit, and push only after Marco explicitly approves (he says "publish" or approves the draft). Published posts drop `draft: true` unless he says otherwise. Report the final file location, push status, and expected live status.
- Fine without asking: fixing typos and standardizing frontmatter. Check first: tags, titles, and moving files. Always ask before deleting content. If a rule is unclear, ask before making a publishing decision.

## Build and deploy

- Hugo isn't installed on Marco's PC. Pushing to `main` builds and deploys the site through GitHub Actions (`.github/workflows/deploy.yml`, Hugo 0.121.2). After a push, check that the deploy run passed (`gh run list --limit 3`).
- Marco writes posts directly in this folder with VS Code, Obsidian, or Octarine. The old Octarine-Docs auto-publish workflow was removed on 2026-11-08 after its token expired. Still `git pull` before editing, since he may push from another machine.
- `.octarine/` and `.obsidian/` are local editor settings and are gitignored. Leave them alone.

## Writing

Marco's voice: direct, practical, conversational, confident. Short paragraphs, active voice. No em dashes, filler, hype, clickbait, jargon, academic tone, AI-sounding transitions, inflated certainty, or bullet-heavy posts. Ask about angle, audience, or length when it changes the draft.

## Portfolio pieces

- Show work as evidence, not as a resume. Lead with outcomes, then the situation, goals, his responsibilities, actions, decisions, challenges, skills, results, lessons, and next improvements.
- Gather the relevant files and media first, then document the process and an honest look at strengths and weaknesses.
- Verify every metric and tie screenshots, reports, videos, links, or analytics to the outcome they support. Observed participation isn't proven engagement improvement. Never invent impact.
- Before publishing, check grammar, voice, evidence, results, lessons, and that media and links work. Keep one review draft and replace it with the approved public file.
