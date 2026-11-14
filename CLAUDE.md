# Project: NASA Space Apps Challenge 2026, Ulaanbaatar

## Challenge (fill in once the team picks)
- Challenge title: [TBD]
- One-sentence goal: [what a user can do with our tool]
- Target user: [who uses it]
- Core feature (the ONE thing that must work): [TBD]
- Stretch features (only after core works): [TBD]
- NASA data we use: [TBD]

## Deadline
- Submission closes Sunday 15 Nov 2026, 23:59 Ulaanbaatar time (confirm with Local Lead).
- Internal deadline: Sunday 20:00. Demo ready by Sunday 17:00.
- If a task will take more than 2 hours, stop and propose a simpler version.

## Rules (breaking these disqualifies us)
- Must use NASA data. Log every dataset (name, URL, how we used it) in notes/DATA_SOURCES.md.
- Final project link must be public: no login, password, or API key needed.
- All visible text and the submission in English.
- AI-generated images or video need a visible "AI-generated" watermark.
- Never generate or edit NASA logos, flags, or mission insignia.
- Log AI use in notes/AI_USE.md as we go.
- No copyrighted images, music, or text without permission. No personal data.

## Tech stack (do not change without asking)
- Website: plain HTML + CSS + JavaScript in /docs. No framework, no build step.
- Charts: Chart.js or Plotly via CDN. Maps: Leaflet via CDN.
- Data processing: Python scripts in /scripts. Read /data/raw, write JSON/CSV to /docs/data.
- The site only reads precomputed files. No live API calls or API keys in browser code.
- Hosting: GitHub Pages from the /docs folder on the main branch.
- Local test: run `python3 -m http.server 8000` inside /docs, open http://localhost:8000

## Folders
- /data/raw   original downloads, never edited
- /scripts    data scripts, numbered in run order (01_download.py, 02_clean.py)
- /docs       the website and /docs/data
- /notes      DATA_SOURCES.md, AI_USE.md, METHOD.md, demo slides

## How to work with me
- Plan first: show a short numbered plan and wait for my OK before coding.
- Small steps. After each working step, tell me how to test it and give a commit message.
- Never leave the site broken at the end of a step.
- Never invent data, numbers, or citations. If data is missing, say so and stop.
- I am not a developer: give exact commands and say where to run them.
- Keep answers short.