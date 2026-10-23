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
- Oct 23 (later): user — Brilliant Move stays in going 1st in the MIRROR ("helps build a better board"); mirror 1st plan swaps it for Endgame. DONE (sources, side_oct23, guide, brain, SKILL); published v78.
- Oct 23: user — remove the 2nd Endgame Problem from 1.2 flex options ("it is just bad"). DONE; published v78.
- Oct 23: user — Thrust flex row: "back in the main" → "in the main". DONE; published v78.
- Oct 23: user — Extra Deck now 2 Enlisted + 2 Castellan (3rd Enlisted out, answered via question); flex: Hyperion would replace the 2nd Castellan; remove the 2nd-Castellan flex row; Odin row → Maple Maiden (WIND Fairy Synchro). DONE (v79).
- Oct 23: user — remove the line about banned cards in 1.2 side-deck flex options. DONE (built, not published).
- Oct 23: user — move the Angelechy intro paragraph from 1.3 into 1.1 (incorporate better). DONE (built, not published).
- Oct 23: user — going 1st end board: one body only (normally Black-Winged Assault Dragon; Chaos Angel or Legatia only if bodies would help the opponent so you remove them, or you really need Legatia's draw), backrow always includes Castellan, never end on 2 bodies; main line ends on BWAD. Update all end-board text. DONE (v79).
- Oct 23: user — end-board example (1.3 fieldmap): show only your side, no Seneschal on theirs (Problem's Enlisted removes it). DONE (v79).
- Oct 23: user — fieldmap: remove 'count 6' label and the count explanation from the image. DONE (v79).
- Oct 23: user — watch more combo videos; find the main uninterrupted lines people play; update 3.1 lines and 1.3 'How a game goes'. DONE (v79).
- Oct 23: user — "most of the time you go for Destrier first, not Bastion" (Opposition places Destrier first; line A's Bastion-first is not the main line). Fold into the lines rewrite. DONE (v79).
- Oct 23 DONE (not yet rebuilt/published): Extra 2 Enlisted/2 Castellan edits (cards, learn, deckbuilder, postban, guide home/1.2/flex/2.4); 1.2 side-flex Forbidden sentence removed; 1.3 intro moved into 1.1 (guide2.html) and 1.3 now opens with the 41 paragraph; Seneschal "1 copy" fix; 1.1 "About 13%".
- NEXT: research combo videos (main uninterrupted going-1st lines) → rewrite 3.1 lines + 1.3 "How a game goes" + 1.3 fieldmap (your side only, no count, one body BWAD, Castellan in backrow).
- Oct 23: user — Verdict is often used just as a negate; remove points 3 and 4 from 1.3 'How a game goes' going first. DONE (built, not published).
- Oct 23: user — Fuwalos timing: if you know their deck and have e4 → Fuwalos in their Draw Phase (then e4 at Standby). Without e4 → only once they've committed to the Extra Deck (an effect, or a monster on board that will surely become an Extra Deck monster). Sky Striker exception: always Draw Phase. Update 1.3 going 2nd, 2.2 Fuwalos, mistakes, matchup notes where Fuwalos timing is stated. DONE (v79).
- Oct 23: user — 1.3 "How a game goes" going 2nd: keep only point 1 (as a paragraph, not a list item), using the new Fuwalos rule. DONE (built, not published).
- Research note: DB Grinder spreadsheet (docs.google.com/spreadsheets/d/190Z4IuiBvy-zm2_VXXTs2RDEU-Mnf5Sj-YD_QsLlP9E) Combosss tab = DuelingBook replay links (Oppo+1 blank, Problem+1 blank, E4 #1/#2, Oppo+Prob, Prob+Distur, Prob+Verdict). DuelingBook replay pages show a Cloudflare "Verify you are human" check → not bypassed; would need the user to click it.
- ygocombo.com/combo/163 (Problem+any, Oct 19) → Opp places Castellan, Seneschal gives Bastion, Verdict GY → Bastion→Shatranga→e4, Enlisted on Seneschal, Hyperion; e4 at their Draw Phase w/ Endgame. /combo/178 (Opposition+any, Oct 21) → Opp places Destrier → Strategy Score; Seneschal gives Shatranga body; Problem → Enlisted + Bastion → Shatranga → Verdict (ends 2 bodies).
- Oct 23: user — move the 'Your learning path' callout from 1.3 to 1.1. DONE (built, not published).
- Oct 23: user — remove outside references (creator/player names like "(DB Grinder)", quotes) from EVERYWHERE in the guide: "the things written on this guide are my own insights". Plan: strip names; turn verbatim quotes into plain statements in the guide's voice (no unattributed verbatim quotes). DONE (v79). Asked about the Sources page / replay links / event stats.
- Oct 23 answers: KEEP the Sources page (it's our research); remove references inside the guide itself (parenthetical or otherwise). REMOVE tournament stats from explanations too (keep only in the Meta report). Keep what creators said, as the guide's own advice.
- Oct 23: user — remove the "Not in this list, and why" section. DONE (built, not published).
- Oct 23: user — remove the '3 rules' section (#ht-rules) from 2.2. DONE (built, not published).
- Oct 23: user — 2.2 'Which hand trap, which matchup' (#ht-matrix): keep only the top 5 matchups per hand trap; make it smaller to fit mobile and desktop. DONE (built, not published).
- Oct 23: user — remove Forbidden hand traps and board breakers from the 2.2 lists. DONE (built, not published).
- Oct 23: user — retitle 2.2 'Which hand trap, which matchup' → 'Which non-engine, which matchup'. DONE (built, not published).
- Oct 23: user — make each 2.2 section that lists multiple hand traps collapsible (too long). DONE (built, not published).
- Oct 23: user — remove the intro explanation at the start of 2.2 Board breakers, and the 'After the list' (#ht-sacco tiers) portion of 2.2. DONE (built, not published).
- Oct 23: user — 2.2 Board breakers: make each card a collapsible entry like the hand-trap entries (cx details). DONE (built, not published).
- Oct 23: user — make 2.2 card blocks smaller so more fit on screen. DONE (built, not published).
- Oct 23: user — remove the FTK version from 2.4 (can't be played anymore). DONE (built, not published).
- 2.2 top-5 lists are hand-curated from scratchpad rank.py (matrix ratings + deep-dive chokes + side_oct23 plans + Boarder strength); data lives in build/v3/handtraps.html .netop.
- Oct 23: user — 2.4: ONE example list per build, explained briefly; no comments from other players; don't say where a list is from. No references to other people anywhere in the guide. DONE (v79).
- Oct 23: user — remove the "Not in guides I reviewed" tags from the guide (line cards). DONE (v79).
- Name-scrub scope: all build/v3/*.html, mu_v2_a/b/c.py, v2.py, side_oct23.py, guide-direct text; NOT the Sources page; Meta report keeps event results. Remove event stats elsewhere.
- Oct 23: user — REWRITE 3.1 lines: fix lines that show Extra Deck monsters as if in hand; NO card images; explain each line from the opening cards; show only the common ONE-card starters (Opposition, Problem, Strategy Score, Terraforming, Opening to e4) and how to play each going 1st AND going 2nd, plus the most common TWO-card starters, no repeats. Tags "Not in guides I reviewed" and all name tags go. Main going-1st line = Destrier first → BWAD, Castellan placed, one body. IN PROGRESS (needs video research: PhantomsYGO E5L8aAgMUpI, Kaiba Core mIKZX6iDORM, ruingear 1VrPmN0nRR8, DB sheet combos list: Oppo+1, Prob+1, E4 #1/#2, Oppo+Prob, Prob+Distur, Prob+Verdict).
- 2.4 DONE (built later): rewritten — summary table, Full Dominus / Bishop+Witness one example list each (derived from the user's list via swaps), e4 splash brief, watch table. Old named lists removed.
- Oct 23: user — Endgame lines: keep only the first e4 combo (EG1), remove EG2–EG4; call it an 'e4 play', not an Endgame Problem line. (Merge with line C: no repeats.) Also: remove where each line is from. DONE (v79).
- Oct 23: user — remove the 'Playing Endgame well' portion of 3.1. DONE (v79).
- Oct 23: user — 3.6 quiz: remove the parenthesis parts of hand titles; remove setup lines like "you expect one Ash" (just give the hand); answers = the correct play around ALL common hand traps; fix plays to the new lines (hand 1: bait Ghost Ogre by activating Problem first). DONE (v79).
- Research done: PhantomsYGO intro (E5L8aAgMUpI) transcript read: e4 going 2nd (Endgame → Enlisted EMZ + Castellan → Verdict; Verdict GY sends Enlisted → Bastion → Shatranga → e4 #2; Endgame draw; e4 #2 → Problem + Lv7 EMZ + Destrier → Strategy Score); Opposition going 1st (Destrier first; Seneschal → Shatranga body; Legatia option); Problem going 1st (Problem → Enlisted + Destrier → Opposition → Castellan → Verdict; Seneschal → Bastion for BWAD or Shatranga for Legatia). "True starters are Problem and Opposition."
- 3.1 REWRITTEN (guide-direct): ids line-opposition, line-problem, line-access, line-e4 (the e4 play), line-opp-problem, line-problem-gy, line-boarder; "What stops what" table at the end; no images, no tags, no sources. Old line A–G/EG refs repointed in learn/cards/guide2/techs/side + guide-direct. "Playing Endgame well" + EG2–EG4 removed.
- v3_apply.py: removed the old 'Set e4 (or your 2nd Verdict)' auto-correction (conflicted with the new line).
- 3.6 quiz rewritten (guide2.html): titles 'Hand N · Going first/second', answers on the new lines (Problem first to bait Ogre in hand 1). DONE (not published).
- Scrub progress: cards, handtraps, learn, guide2, postban, situational, decktheory, techs DONE. Deep dives: evidence/tags rewritten (no events/names), v2.py no Replays tab (rep_pane=""), empty evidence skipped. 4.3 Replays chapter REMOVED (guide2.html, v3.js AREAS, chapters.py conditional); its 17 replay links moved to the Sources footer under "Replays". Eyebrow "4 · Rulings and tips".
- NEXT: names in mu_v2 keys/chokes/plan/hurts/g1/g2, v2.py index text, side_oct23.py notes, guide-direct (home, meta?, 1.2, 3.7, siding, plays, 2.3?), v3_apply.py re-inserting names; then final grep of the built guide (excluding #sources and #meta results).
- Scrub DONE in all sources + guide-direct; scan.py (scratchpad) shows only tracker event dropdown + home meta-card line (allowed). Unattributed quotes reworded.
- Scrub DONE in all sources + guide-direct; scan.py (scratchpad) shows only tracker event dropdown + home meta-card line (allowed). Unattributed quotes reworded.

- Oct 23 v79 PUBLISHED (artifact v79). Site push next.
- Oct 23: user — remove section 3.7 (Odds & Boarder, #deck). DONE (v80): section, nav entry and the 2.3 'Full breakdown' link removed.
- Oct 23: user — remove section 4.1 (Rulings to know, #rulings). DONE (v81): section + nav removed, Tips renumbered 4.1, learning path and 5.2 links point to #tips.
- Oct 23: user — 'remove 4.2' = the Tips section (it was 4.2 before the renumber). DONE (v82): Tips removed; chapters 5→4 (4.1 What the list changed, 4.2 Your list now) and 6→5 (5 Playing around new tech, h2 5.1); all '6' tech links → '5'; learning path ends at Siding plans.
- Oct 23: user — 'remove 5.2' (post-banlist list section; was 4.2 'Your list now', #postban-list). DONE (v83): section + nav removed; 4.1 intro and home card no longer mention it.
- Oct 23: user — mirror: Brilliant Move stays even going first. DONE (v84): plans already kept it (MIR1); wording made explicit in 2.1, 2.2 More mirrors, situational, deck theory, 1.2 flex note, siding row/rules, mirror deep dive Going 1st.
- Oct 23: user — going 1st (not mirror): cut 1 Opening to e4 instead of a Veiler (Endgame is out, so e4 is weak going 1st); vs Elfnote going 1st Endgame STAYS (very strong into them), cut an e4 or a Veiler instead. DONE (v85): A = −3 Fuwalos −1 Endgame −1 BM −1 e4 (+3 Boarder +3 Thrust); Elfnote EL1 = −3 Fuwalos −1 BM −2 e4 (Endgame stays). ROLAD (DR1: −2 Veiler, +Droll), Mitsurugi/D-HERO/Invoked (NOOG), Sky Striker (SKY1) unchanged — asked user. Odds unchanged (86.6% play / 75.0% survives).
- Oct 23: user — Siding page: remove the 'Trif's rules' panel (titled 'Siding rules, applied to you'); simplify 'Your templates'. DONE (v86): rules panel removed; templates = 4 short bullets (going 1st, going 2nd, out first, order) + pointer to the table.
- Oct 23: user — simplify the Siding → Odds page (#plays). DONE (v87): page = 2 small tables (going 1st: play/survives; going 2nd: 3+ int/starter/both) + 1 note; the outdated 'best line by starters' table removed (lines live in 3.1); tables fit phones (.tbl.odds).
- Oct 23: user — coin flip animation: don't teleport at the end. DONE (v88): v3.js coinPlan keeps x (coinX persists, clamped ±44px); static transforms = last frame (toss + shadow); die resets the shared shadow. Test: build/v3/frames/cointest.js (PROF=ffprof2, hash lp) PASS.
- Oct 23: user — rename 'Odds calculator' to 'Hypergeometric calculator'. DONE (v89): nav label (v3.js) + home Tools card; page title already said it.
- Oct 23: user — Matchups (Home): archetype art behind each matchup card. DONE (v90): 18 art crops (YGOPRODeck cards_cropped of the KEY_CARD per matchup, 400x247 q72, ~27KB) in data/assets/art/<mu>.jpg → published as img/art/<mu>.jpg (artifact files + push_assets.py); JS sets --art on each .mu-card; CSS ::before art + ::after surface gradient (v3.css). New matchup = add data/assets/art/<id>.jpg.
- Oct 23: user — Meta report first paragraph → just 'Position within a tier doesn't matter'. DONE (v91).
- Oct 23: user — Meta report Angelechy results: each placing links to its YGOPRODeck decklist. DONE (v92): Houston T4 739270, T8 739277/739279 (+ '9 in the Top 32' → tournament/ycs-houston-5185), Bussolengo T8 739712, Santiago T8 739732, Belén 1st 738506, Burnaby T4 737973, Saint Peters T4 tenpai 737958 / T8 738293, Louisville T4 737740. No posted list: Belén T4, Burnaby 2nd, Dubuque T8 (left as text). All URLs return 200.
- Oct 23: user — add Lava Golem to more going-2nd plans. DONE (v93): user had no preference → Elfnote, Yummy, Maliss (−3 FBG −1 Terra) and Fairy Tail (−2 FBG −1 Terra) each +1 Golem; notes, deep-dive g2 tabs (Elfnote no longer 'don't plan to break the board'; Fuwalos Draw Phase), 2.3 Golem entry and 2.2 breaker card updated. Interruption counts unchanged.
- Oct 23: user — side Droll into more going-2nd plans too. DONE (v94): Elfnote (−1 Strategy Score makes room; OUT list + deckbuilder CHIP map now know Strategy Score) and Branded/Dracotail (−3rd FBG). Droll now in every going-2nd plan but the mirror. Elfnote keys/chokes/g2, 2.2 Droll entry ('weak only in the mirror'), More Elfnote panel, templates cut order updated.
- Oct 23: user — Siding: remove the explanation paragraph after the swaps. DONE (v95): planner shows only side out/in (+ going-2nd stats) and the deep-dive link; siding table has no 'Why' column (side_oct23.py drops cell 5; NOTE dict kept as reference only); deep dives no longer say 'Why these swaps: Siding' (v2.py).
