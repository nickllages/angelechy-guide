# Angelechy brain

This folder is Claude's research memory for the Angelechy guide. The guide (`index.html` in this repo, built from `guide/angelechy-guide.html`) is the finished, user-facing page. These Markdown files hold everything behind it: what the user decided and why, every research note and source, conclusions that took work to reach, mistakes not to repeat, open questions, and how to gather data and publish.

**In a new session, read this file, then `decisions.md`, then the newest entries at the bottom of `log.md`.** Read the guide itself for the polished matchup pages, lines and siding tables.

## Files

| File | What's in it | Updated |
|---|---|---|
| `decisions.md` | The user's current 70, the siding plans (auto-generated from the newest `build/side_*.py`), siding rules, card decisions with reasons, rejected cards, workflow preferences | Every time the user decides something |
| `log.md` | Dated log of every research run and every change to the guide | Append after every session or daily run |
| `insights.md` | Rulings and interactions read from card texts, conclusions per matchup, side-card verdicts, odds, and corrections of past mistakes | When a conclusion is reached or overturned |
| `sources.md` | Creators, videos, replays and lists, with what each one said (quotes, dates, links) | When a source is read |
| `matchup-research.md` | Per-deck engine notes: how each opponent plays, its key cards, what it sides against Angelechy | When a deck is researched |
| `meta.md` | Results timeline, deck counts, tier lists, the catalogue of Angelechy lists | When new results come in |
| `open-questions.md` | Things not yet known or not yet decided, and judge checks | Add and close items as they resolve |
| `methods.md` | How to get data (APIs, scripts, captions), how the guide is built, tested and published, tooling gotchas | When a method changes |
| `raw/` | Opponent decklists with full card texts, side decks, the set list, card texts of every card discussed. **Generated** from `data/` by `tools/push_brain.py`; edit `data/`, not `raw/` | Every push |

## Update protocol

1. **Every research run or session:** append a dated entry to `log.md`: what was checked (with links), what was found, what changed in the guide, and what was proposed to the user.
2. **Put each finding where it lives:** a quote or video goes in `sources.md`, an opponent engine detail in `matchup-research.md`, a result or list in `meta.md`, and a durable conclusion or overturned belief in `insights.md`. Always add the date and the source.
3. **User decisions** go in `decisions.md`. Also mirror them into the scheduled task's SKILL.md and Claude's local memory when they change the list or the siding rules.
4. **Unknowns** go in `open-questions.md`. Close each one with the answer and date rather than deleting it.
5. **Push:** run `python3 tools/push_brain.py`. It regenerates `raw/` and the plan table in `decisions.md`, then commits the whole `brain/` folder to GitHub in one commit. `tools/publish_site.sh` runs it automatically after every guide publish.

## Rules for what goes in here

- This repository is public. No passwords, tokens, emails or private data. The user's decklist and siding are already public in the guide.
- Don't copy the guide into Markdown. Link to the guide's section (for example `#elfnote`, `#cards`, `#siding`) instead.
- Record uncertainty honestly: mark judge-check items ⚖ and guesses as guesses.
