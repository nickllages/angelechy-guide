# Work in progress (update after every step; read this first after a context reset)

**Status Oct 23: everything below is DONE and published as artifact v77 + GitHub Pages. Nothing pending.**

## Session 2026-10-23 — restructure requests (user, in order)
Published so far: artifact v76 (Oct 23 list + chapter 6). Everything below is NOT published yet.
Backups before the restructure: build/.bak23b/ (sources + guide as of v76).

| # | Request (user's words, short) | Status |
|---|---|---|
| 1 | 1.2: remove the example side decks (covered on Siding) | DONE in sources (decktheory.html, cardpics.py dl-modes removed) |
| 2 | Remove from chapters things covered in another chapter; say where instead | Sources DONE; guide-direct DONE (build/restructure_oct23_guide.py) (build/restructure_oct23.py: 2.1 hand traps→2.2, side→2.3, out-of-list→pointers, 1.4 removed, 5.2 ranking removed, 5.3→5.2, 3.5 GY tech→6, tips deduped vs 1.3 mistakes, 4.3 replay notes→deep dives, deep-dive siding sentences removed, deep-dive hurts→6). Guide-direct PENDING (build/restructure_oct23_guide.py): 1.2 Switching builds→2.4, side flex table→2.2 pointer, Verdict flex row + decklist 41 note (1.2 theory bullet is the one home), 3.1 lessons + count callout + Endgame callout→pointers, 3.7 Dominus lock table→2.2 rule 1 (rename 3.7 "Odds & Boarder"), siding research callout trimmed + interruptions table→Plays, "What opponents side" callout→6 (moved to techs "usual package"), Plays "When they hit you"/"Under Fuwalos"→3.2–3.5/3.4, links #postban-rank/#muchart→#meta/#matchups |
| 3 | Remove the "Seen in" portion from all tables | DONE (ch 6, 1.2 flex tables, 2.4 builds) |
| 4 | Remove the last line in the Sources tab | DONE |
| 5 | Meta report: only the best decks by tier + disclaimer (position within a tier doesn't matter) | DONE (#meta rewritten). Tiers from old 5.2: T1 Angelechy, Artmage/Power Patron, Elfnote/Medius, Fairy Tail/Invoked; T2 Sky Striker, Radiant Typhoon, Sacred Beast, Maliss, D-HERO, Blitzclique, Mermail/Dark World, L&D Ritual, DTW; T3/rogue Branded/Dracotail, Kewl Tune/Ryzeal, Lunalight, Clown Crew/Ashtra |
| 6 | Remove the parts where each creator rates the decks | DONE |
| 7 | Results: only regionals+ and only Angelechy, "Event: representation in top cut" | DONE: Houston Top 4 + 2×Top 8 (9 in Top 32); Italian Open Top 8; Santiago Top 8; Belén 1st + Top 4; Burnaby 2nd + Top 4; Saint Peters Top 4 (Tenpai e4 splash) + Top 8; Louisville Top 4; Dubuque Top 8; none at Monterrey, Curitiba, Guatemala, Bogotá, Karlsruhe, Ramsgate, Chaguanas |
| 8 | Sidebar groups auto-close when you're not in them (unless they hold a favorite); star to favorite pages; Favorites tab/group only after favoriting | DONE + tested (build/v3/frames/favtest.js, all pass) |
| 9 | All matchups: smaller blocks; deep dives not listed in sidebar/subnav; Matchups page under Home (no own tab) | DONE + tested |
| 10 | Text on each All-matchups block goes into the deep dive | DONE in v2.py (blurb paragraph under h2; threat already in "Their key threat"); index card shows name + read only DONE |
| 11 | Home doesn't need an item in the sidebar (title links home) | DONE |
| 12 | Odds: keep only odds for what will happen; remove Burnaby Top 4 row and the too-many-hand-traps rows | DONE |
| 13 | Keep the brain updated so nothing is lost at the context limit | DOING: this file |

After all: update tests (build/v3test.sh inline reg test: tabbar 5→4, sidenav groups 5→4; add a favorites test), rebuild (side_oct23 not needed; run render_matchups.py then v3_apply.py), run reg/db/presets/gen tests, publish artifact (url https://claude.ai/artifact/9EaHDydVbJ9GjcgHrFi5F5) + bash tools/publish_site.sh, update brain/log.md, brain/decisions.md (structure rules), SKILL.md (meta report format, no creator ratings, results rule), memory; report.

Progress: rebuilt (render_matchups + v3_apply), link check clean, reg test updated (4 tabs/4 groups) and passing, favtest passing. NEXT: screenshots (meta, matchups, deep dive on phone), db/presets/gen tests, publish artifact + site, brain/log + decisions + SKILL + memory, report.
