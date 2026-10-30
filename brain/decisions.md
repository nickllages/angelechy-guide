# Decisions — the user's list, siding rules and preferences

The user plays Angelechy in the TCG, at locals and regionals. These are their decisions. Don't re-propose what they rejected unless new evidence is strong, and say so when you do. The user changes lists quickly, so confirm the full 40 + side before rebuilding siding.

## Current 70 (user, Oct 27: "check the new lucas sacco decklist, that is now my main deck and side except for the bridges and the wind guy that bounces things"; the 5 open side slots = 3 Cosmic Cyclone + 2 Thrust, the user's pick)

**Main 40** (= the list in Lucas Sacco's "Angelechy 101", Oct 27)
- Monsters (11): 3 Ash Blossom & Joyous Spring, 3 Ghost Ogre & Snow Rabbit, 2 Effect Veiler, 2 Ghost Mourner & Moonlit Chill, 1 Droll & Lock Bird
- Spells (15): 3 Angelechy Strategy Score, 3 Angelechy Opposition, 3 Angelechy Problem, 3 Foolish Burial Goods, 1 Terraforming, 1 Pot of Prosperity, 1 Angelechy Endgame Problem
- Traps (14): 3 Angelechy Opening to e4, 1 Angelechy Verdict, 1 Angelechy Disturbance, 3 Dominus Impulse, 3 Dominus Purge, 3 Dominus Spark

**Extra 15:** unchanged — 2 Angelechy Enlisted, 2 Angelechy Castellan, 2 Angelechy Bastion, 2 Angelechy Destrier, 2 Angelechy Shatranga, 1 Angelechy Seneschal, 1 Chaos Angel, 1 Black-Winged Assault Dragon, 1 Assault Blackwing – Kusanagi the Gathering Storm, 1 Centur-Ion Legatia

**Side 15:** 3 Inspector Boarder, 2 Triple Tactics Thrust, 3 Cosmic Cyclone, 3 Mulcharmy Fuwalos, 3 Skull Meister, 1 Angelechy Verdict (Sacco's side minus 2 Rainbow Bridge Bifrost and 3 Shiina)

Counts: 14 starters (Prosperity counted as a starter, as in the deckbuilder); 23 interruptions → 80% to open 3+; going-2nd plans 21–26 (most 24–26: 84–90%). Deckbuilder odds: 89.9% a play going 1st, 58.9% survives a hand trap; after siding 90% / 77%. Genesys 478 (308/58/112).
Lines with 1 Verdict: Shatranga adds Opening to e4 (Set e4 at the end; Verdict once the 2nd copy is sided in); Opposition's GY effect can shuffle Verdict back for a later Strategy Score. 1.2 field map shows "e4 (Set)".

## Siding rules (user)

- Side in **only** cards that matter in the matchup; side out main cards that are bad there (Oct 12).
- **Never side out Opposition** ("my best card", Oct 13).
- **Going second, never side out** Verdict, Disturbance, Endgame or Opening to e4.
- **Going first (default, user Oct 23; Oct 27 list):** −2 Opening to e4 −1 Endgame (user rules) −2 Ghost Mourner → +3 Boarder +2 Thrust (Claude's call: Boarder limits your monster effects too, so the small hand traps go first). Elfnote: Endgame stays + 1 e4, Droll goes instead of Endgame. Mitsurugi/Invoked: −3 Ogre (not Mourner) +1 Skull Meister; D-HERO: −3 Ogre +1 Set Cosmic Cyclone; Sky Striker: −2 Ogre; ROLAD piles + Blitzclique: −2 Veiler; Branded: −1 Droll −1 Mourner. Mirror: no Boarder; −2 Veiler −2 Mourner −1 Droll −1 Endgame −2 e4 → +1 Verdict +2 Skull Meister +3 Cosmic Cyclone +2 Thrust.
- **Going second:** engine out in order Terraforming, FBG, FBG, then Strategy Score. Nibiru vs decks that summon 5+ times; Droll vs search engines; Lava Golem vs Black Chaos, Mirrorjade, Liger Dancer and big boards; Typhoon vs face-up S/T; mirror −2 Veiler −3 Spark → +2 Typhoon +3 Thrust.
- **Card-specific cuts:** Ghost Ogre out vs Mitsurugi, Destiny HERO and Invoked (all 3). Veiler out vs the mirror and Blitzclique (and going 1st vs ROLAD). Fuwalos out vs (pure) Blitzclique. Spark out vs the mirror (going 2nd), Sky Striker and DTW. Droll stays out vs the mirror, Elfnote and pure Branded; Nibiru stays out vs the mirror and Sky Striker.
- **Brilliant Move:** not in the list (Oct 27).
- **Going 2nd (Oct 27 list):** all 3 Fuwalos in (not Blitzclique) for Terraforming + Pot of Prosperity + 1 FBG (max 3 engine cuts) or for bad main cards (Ogre vs Mitsurugi/D-HERO/Invoked, Spark vs Sky Striker/DTW/mirror, Veiler vs ROLAD piles/Blitz, Droll vs Elfnote/Branded/mirror). Skull Meister vs mirror (3), Elfnote, D-HERO, Mitsurugi, Blitzclique; Cosmic Cyclone vs mirror (2), Sky Striker, Blitzclique; Thrust 2 + 2nd Verdict in the mirror. Never Opposition/Verdict/Disturbance/Endgame/e4.

## Siding plans (generated from the newest `build/side_*.py`; do not edit by hand)

<!-- plans:start -->
*From `build/side_oct27.py` (2026-10-30).*

| Matchup | Going 1st | Going 2nd |
|---|---|---|
| Elfnote Ars Magna | −2 Ghost Mourner, −2 Effect Veiler, −1 Droll, −1 Ghost Ogre → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods, −1 Droll → +3 Fuwalos, +1 Skull Meister |
| ROLAD pile | −2 Effect Veiler, −1 Endgame Problem, −2 Ghost Mourner, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −2 Effect Veiler, −1 Terraforming → +3 Fuwalos |
| Angelechy mirror | −2 Effect Veiler, −2 Ghost Mourner, −1 Droll, −1 Endgame Problem, −3 Spark → +1 Verdict, +3 Skull Meister, +3 Typhoon, +2 Triple Tactics Thrust | −2 Effect Veiler, −2 Ghost Mourner, −1 Droll, −3 Spark, −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos, +1 Verdict, +3 Skull Meister, +3 Typhoon, +1 Triple Tactics Thrust |
| Branded ROLAD | −2 Effect Veiler, −1 Endgame Problem, −2 Ghost Mourner, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −2 Effect Veiler, −1 Terraforming → +3 Fuwalos |
| Power Patron / Artmage | −1 Endgame Problem, −2 Ghost Mourner, −1 Effect Veiler, −2 Ghost Ogre → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos |
| Yummy | −1 Endgame Problem, −2 Ghost Mourner, −2 Effect Veiler, −1 Droll → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos |
| Mitsurugi | −3 Ghost Ogre, −1 Endgame Problem, −2 Ghost Mourner, −1 Effect Veiler → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict, +1 Skull Meister | −3 Ghost Ogre, −1 Terraforming → +3 Fuwalos, +1 Skull Meister |
| Fairy Tail | −1 Endgame Problem, −2 Ghost Mourner, −2 Effect Veiler, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos |
| Blitzclique | −2 Effect Veiler, −1 Endgame Problem, −2 Ghost Mourner, −1 Ghost Ogre → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −2 Effect Veiler, −1 Terraforming → +2 Typhoon, +1 Skull Meister |
| Branded | −1 Endgame Problem, −1 Droll, −2 Ghost Mourner, −1 Effect Veiler, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Droll, −1 Terraforming, −1 Pot of Prosperity → +3 Fuwalos |
| Destiny HERO | −3 Ghost Ogre, −1 Endgame Problem, −2 Ghost Mourner, −1 Effect Veiler → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict, +1 Skull Meister | −3 Ghost Ogre, −1 Terraforming → +3 Fuwalos, +1 Skull Meister |
| Dark Time Wizard | −1 Endgame Problem, −2 Ghost Mourner, −3 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −3 Spark → +3 Fuwalos |
| Sky Striker | −2 Ghost Ogre, −1 Endgame Problem, −2 Ghost Mourner, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −3 Spark → +3 Fuwalos |
| Invoked | −3 Ghost Ogre, −1 Endgame Problem, −2 Ghost Mourner, −1 Effect Veiler → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict, +1 Skull Meister | −2 Ghost Ogre, −1 Terraforming → +3 Fuwalos |
| Maliss | −1 Endgame Problem, −1 Ghost Mourner, −1 Effect Veiler, −1 Droll, −1 Ghost Ogre, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos |
| Sacred Beast | −1 Endgame Problem, −2 Ghost Mourner, −2 Effect Veiler, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos |
| Lunalight | −1 Endgame Problem, −2 Ghost Mourner, −2 Effect Veiler, −1 Spark → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Fuwalos |
| radiant | −3 Ghost Ogre, −2 Effect Veiler, −1 Endgame Problem → +3 Inspector Boarder, +2 Triple Tactics Thrust, +1 Verdict | −1 Terraforming, −1 Pot of Prosperity, −1 Foolish Burial Goods → +3 Skull Meister |
<!-- plans:end -->

## Guide structure rules (user, Oct 23 — follow on every update)
- **One home per topic.** Don't repeat content across chapters; where another chapter needs it, write one line saying where it's covered (link). Homes: how the deck works (40 paragraph, field map, how a game goes) → 1.2; list + theory + flex options → 1.3 (user swapped 1.2/1.3, Oct 24); engine/Extra cards → 2.1; hand traps (incl. side hand traps Nibiru/Droll/Veiler) + out-of-list cards + board breakers + hand trap × matchup matrix → 2.2; side deck → 2.3; other builds + "Switching builds" → 2.4; Dominus locks → 2.2 rule 1; Boarder breakdown + opening odds → 3.7; Fuwalos → 3.4; removal → 3.5; anti-Angelechy tech + "the usual package" → 6; rulings → 4.1; tips → 4.2 (1.3 mistakes are not repeated there); replay notes → deep dives (4.3 is links only); siding reasons → Siding table (deep dives show chips + "Why these swaps" link, no siding sentences); tiers → Meta report; what the list took → 5.1.
- **Meta report = only** the tier list (Tier 1 / Tier 2 / Tier 3 and rogue, with "position within a tier doesn't matter") + "Angelechy at regionals and above" (event: Angelechy's top-cut placings; regionals and higher only, Angelechy only; one line listing events with none). No creator ratings anywhere in the guide (no creator tier tables, no "X ranks it tier 2" in deep dives).
- **No "Seen in"/evidence columns in tables.**
- **Odds only for what will happen** (the actual list and plans); no comparison lists, no "too many hand traps" rows.
- **Nav:** Home group = Meta report, Matchups, Sources (Home itself isn't listed in the sidebar; the title links home). Deep dives aren't listed in the sidebar/subnav (only via Matchups). Sidebar groups you're not in auto-close unless they hold a favorite; ☆ Favorite on every page; a Favorites tab/group (and #favs page) appears only once something is starred (localStorage ag-favs-v1). All-matchups blocks show name + read only; the description is in the deep dive.
- Chapter numbers now: 1.1–1.3 (1.4 removed), 2.1–2.4, 3.1–3.6 (3.7 "Odds & Boarder" removed by the user Oct 23; odds live on Siding → Odds, Boarder in 2.3 and 3.1), 4 Playing around new tech, 5 Replays (user, Oct 27); (user, Oct 23: 4.1 What the list changed removed too; 3.7 Odds & Boarder, 4.1 Rulings, Tips, 4.3 Replays and 'Your list now' (the post-list card-by-card changes) removed; old chapters 5 and 6 renumbered 4 and 5; replay links live on the Replays page (#replays, Guide chapter 5 — user, Oct 27: 'put the page in the guide as the last chapter'; build/replays_page.py), and the Sources footer only points there).
- **No outside references anywhere in the guide (user, Oct 23):** no creator/player names, no "(DB Grinder)"-style attributions, no "who played it" rows, no "where a line/list is from", no tags like "Not in guides I reviewed". Keep what they said, written as the guide's own advice (no verbatim unattributed quotes). Tournament/event stats ("6 of the 8 Houston lists…", "Louisville Top 4…") only in the Meta report. The Sources footer is the one place references live (user: "it was the research that we made"). Deep dives have no Replays tab.
- **1.1 holds the "what Angelechy is" intro and the learning path (user, Oct 23).** 1.2 (How it works) starts with the 40 paragraph.
- **3.1 = starters only (user, Oct 23):** text-only line cards (no card images, no Extra Deck cards shown as hand cards): one-card starters (Opposition, Problem, Strategy Score/FBG/Terraforming, Opening to e4 "the e4 play") each going 1st and 2nd; two-card starters (Opposition + Problem, Problem + Verdict/Disturbance, Boarder + Opposition after siding), no repeats; "What stops what" table last. ids: line-opposition, line-problem, line-access, line-e4, line-opp-problem, line-problem-gy, line-boarder.
- **Going-1st end board (user, Oct 23):** ONE monster, normally Black-Winged Assault Dragon (main line, Destrier placed first by Opposition); Castellan always in the backrow; never end on two bodies. Chaos Angel only when bodies left on the field would help the opponent (its summon banishes), Legatia only when you really need the draw. Verdict is often just a negate (1–4). 1.2 example board: your side only, no count.
- **Fuwalos timing (user, Oct 23):** know their deck + hold e4 → Fuwalos in their Draw Phase, then e4 at Standby. No e4 → only once they've committed to the Extra Deck (an effect, or a monster that will surely become Extra Deck material). Sky Striker → always Draw Phase.
- **2.2 (user, Oct 23):** no "Three rules" section, no "After the list" tiers, no Forbidden cards in the lists; "Which non-engine, which matchup" = each card's top 5 matchups as compact chips; every section is a collapsible fold; board breakers are collapsible cx cards like the hand traps; compact cards (several per row on desktop).
- **[Superseded Oct 24: Lava Golem cut from the side for Purulia]** **Lava Golem going 2nd = BOTH, for −1 Verdict −1 Spark (user, Oct 23, later):** every going-2nd plan with Golem brings 2; FBG/Terraforming only pay for the other side cards (max Terra + 2 FBG; Elfnote's side Veiler dropped to fit). Siding review (Oct 23): ROLAD + Branded ROLAD g2 also +1 Nibiru (−1 FBG); Power Patron keeps Spark (its best card) — 2nd Golem takes a FBG; Blitzclique g2 now brings both Golems (Colossus/Punisher) for Verdict + Terraforming (Spark stays); Invoked g2 keeps 1 Ghost Ogre instead of a Nibiru. Earlier note: **Lava Golem going 2nd (user, Oct 23):** also vs Elfnote (their post-list board is weaker), Yummy, Fairy Tail and Maliss — the next Foolish Burial Goods makes room, so every hand trap stays. Now in 14 of 17 going-2nd plans (not the mirror, Blitzclique or Sky Striker).
- **Droll going 2nd (user, Oct 23: most decks are weaker to it after the list):** now in every going-2nd plan except the mirror (added Elfnote, with a Strategy Score cut as the 4th engine card, and Branded/Dracotail with the 3rd FBG). Going-2nd engine cut order: Terraforming, FBG ×3, then a Strategy Score.
- **No 'What the siding research says' callout and no side/main summary paragraph (user, Oct 23).** Siding = planner, templates, two pointer notes (+ the hidden data table).
- **No Brilliant Move callout on Siding (user, Oct 23):** its rule lives in its 2.3 card (side deck) and the templates.
- **Siding table/planner (user, Oct 23):** chips only — no 'Why' column or explanation paragraph; each deep dive explains its swaps. Only the planner is shown; the per-matchup table is hidden data (#side-data) that the planner, deep dives and deckbuilder presets read — keep it in the page.
- **Siding → Odds (user, Oct 23):** only two small tables (going 1st: has a play / survives a hand trap; going 2nd: 3+ interruptions / a starter / both, game 1 vs after siding) and one note; no line table (lines live in 3.1).
- **Siding page (user, Oct 23):** no siding-rules panel; "Your templates" is 4 short bullets (going 1st, going 2nd, out first, order on their turn); details live in the per-matchup table.
- **2.1:** no "Not in this list, and why" section. **2.4:** one brief example list per build (made from the user's list via the swaps), no player comments, no sources; FTK removed (unplayable after the list). **3.6:** titles "Hand N · Going first/second" only; answers = the correct play around all common hand traps, on the 3.1 lines.

## Card decisions and the reasons (newest first)

- **Oct 30 — Radiant Typhoon read stays Even (user).** Going 1st vs Radiant Typhoon: user keeps the Opening to e4s; −Endgame and −Veiler accepted in principle; row not added yet (Thrust/Ogre question open).

- **Oct 27 — the user's list = Lucas Sacco's Angelechy 101 main + side minus Bifrost and Shiina (+3 Cosmic Cyclone +2 Thrust):** Nibiru, Purulia and Brilliant Move out of the 70; Ghost Mourner ×2, Pot of Prosperity, Skull Meister ×3 in; Fuwalos to the side; 1 Verdict main + 1 side; Thrust 3→2. Siding rebuilt in build/side_oct27.py (side_oct24.py retired). Sacco's reasons are in wip.md (Oct 27) / meta.md.
- **Oct 24 — the user's list:** 2 Effect Veiler ↔ 2 Nibiru (Nibiru main, Veiler side), Droll to the main (41), +1 Nibiru in the side, 2 Lava Golem → 2 Mulcharmy Purulia (the user had declined Purulia on Oct 19; now their own choice). Siding rebuilt in build/side_oct24.py (side_oct23.py retired).
- **Oct 23 (later) — Brilliant Move back to the side, side (3rd) Effect Veiler cut (user: "ill move the briliant move back to the side and cut the trid veiler"; the siding review had flagged the side Veiler as only coming in vs Mitsurugi and Invoked).** Main 40 = the Oct 22 main. Siding rebuilt (side_oct23.py): going 1st the BM slot becomes a 2nd e4; Mitsurugi/Invoked lose the side Veiler (NOOG 7-for-7, Mitsurugi g2 +2 Nibiru, Invoked g2 keeps 2 Ogre); BM comes in going 2nd vs ROLAD piles, Lunalight, DTW and the mirror. BM card moved from 2.1 to 2.3.
- **Oct 23 — Extra Deck (user):** 2 Enlisted + 2 Castellan (3rd Enlisted out). Flex: Masterflare Hyperion would replace the 2nd Castellan; no '2nd Castellan' flex row; Maple Maiden (WIND Fairy Synchro, for Shiina in the mirror) replaces the Odin row; the 2nd Endgame is never a flex option.
- **Oct 23 — the user's list (pasted from the deckbuilder):** main 41 = Oct 22 main + Brilliant Move (user: the 41st card is the 2nd Verdict, "there are lines that you can do with just one so that is just my choice its probably better to run just one" — the guide says so). Side: 3 Boarder, 3 Thrust, 3 Cosmic Cyclone, 2 Lava Golem, 2 Nibiru, 1 Droll, 1 Effect Veiler (Typhoon out, 3rd Golem out). Siding rebuilt in build/side_oct23.py (Claude's calls, reported to the user): going 1st Brilliant Move is cut instead of an e4 (win-more on turn 1); Cosmic Cyclone ×3 both turns in the mirror, ×2 going 2nd vs Sky Striker and Blitzclique, ×1 going 1st vs Destiny HERO (Set, chain to Dark City's activation: banished, no summon); the 3rd Veiler going 2nd vs Elfnote and Invoked, going 1st vs Mitsurugi and Invoked; Sacred Beast going 2nd Nibiru + Golem (Fallen Paradise's Sacred Beasts ignore your activated S/T effects). Corrected from card texts: Impulse negates the effect, so Magical Meltdown doesn't stop it (Typhoon/Cyclone on Meltdown isn't needed for Impulse).
- **Oct 22 — the user's list for the mirror-heavy field:** 3rd Ghost Ogre and 2 Effect Veiler moved to the main for both Nibiru and Droll, which moved to the side (after the YCS Houston Top 32: all 8 pure lists mained 3 Ogre, 4 mained 3 Veiler). Siding rebuilt in build/side_oct22.py: going 1st −1 Veiler instead of the Nibiru; Droll comes in vs search engines; Nibiru going 2nd vs 5+-summon decks.

- **Oct 19 — the October 19 list (user: research the list, rank decks, pick non-engine, modify the deck, side first).** Talent Forbidden → 3rd Thrust; Droll Limited (illegal 2nd copy). Main: 3rd Ghost Ogre (all 8 pure Houston Top 32 lists ran 3), 2 Veiler main (Elfnote, Patron, Sky Striker, Maliss, D-HERO), Spark 3 → 2 (weak in the mirror and vs Sky Striker), Nibiru to the side (does nothing in the mirror, now the most common matchup).
- **Oct 19 — refined after Drizzels' three post-BETB Angelechy videos (user asked to study them) and the Houston Top 32:** Brilliant Move to the main and Droll to the side (Colin H., #1 DB rated: no Droll, Brilliant Move main, 21 hand traps, "22-ish" max; 6 of 8 pure Houston lists main Brilliant Move). Extra: 2nd Castellan (Colin H.: needed for Opposition after e4's Castellan is hit; 3 of 8 Houston lists), Hyperion (7 of 8) and Legatia (5 of 8) for Black-Winged Assault Dragon, the 3rd Enlisted and the 2nd Seneschal (every Houston list ran 2 Enlisted, 1 Seneschal).
- **Oct 19 — final list from the user's deckbuilder screenshot:** main unchanged from before the list (1 Disturbance, 3 FBG); side 3 Lava Golem, 3 Boarder, 3 Thrust, 2 Veiler, 2 Typhoon, 1 Ogre, 1 Brilliant Move; Extra 3 Enlisted, 1 Castellan, 1 Seneschal, BWAD, Legatia. Earlier that day: proposed Brilliant Move main, 3 Ogre main, Droll to the side and Nibiru→Veiler; the user kept Droll main, 3 Spark, 2 Nibiru and Brilliant Move in the side, and runs 2 Disturbance (for the 3rd FBG). Accepted the 3rd Thrust, the 3rd Typhoon (previously rejected) and the new Extra.

- **Oct 14 — Elfnote going 2nd keeps Spark.** Elfnote activates monster effects in the hand and GY constantly (Regina, Medius) and Trif rates Spark high-impact; the engine makes room instead. The 2nd Droll comes in with both Veilers (Trif: Droll only with "baby" hand traps).
- **Oct 14 — Engine cut order Terraforming → FBG → FBG → Strategy Score.** Terraforming only finds Problem (which still needs a spare); FBG → Disturbance usually becomes Opposition, and Opposition recycles FBG's targets.
- **Oct 13 — Mirror going 2nd: Thrust and Talent replace Spark.** Spark from hand needs a monster effect in their hand or GY, which their first turn rarely has. Opposition gives them Seneschal, whose trigger turns Thrust and Talent on.
- **Oct 13 — 3 Ghost Ogre + 1 Droll main, not 2 + 2.** Ogre is LIGHT (only Impulse locks it), better vs Elfnote and the mirror; the 2nd Droll comes in going 2nd anyway.
- **Oct 13 — 2 Nibiru + 1 Droll, not a 3rd Nibiru.** Droll is best game 1 vs ROLAD/Patron/Mitsurugi; Nibiru is once per turn; the user's own testing found Nibiru underwhelming.
- **Oct 13 — keep both Veilers in the side.** Veiler is in 10 going-2nd plans and is the only side card that works vs Elfnote.
- **Oct 13 — the 3rd Thrust is the weakest side slot.** Candidates for it: Lava Golem (recommended), 3rd Veiler, 3rd Nibiru, Pot of Sloth. Not adopted yet.
- **Oct 13 — Opposition is never sided out.**
- **Oct 13 — consensus main adopted:** 1 Endgame (2nd is a brick), 1 Verdict main + 1 side (Opposition recycles; "god card in the mirror"), 1 Disturbance, no Brilliant Move (win more), Spark ×3 main, Thrust in the side.
- **Oct 12 —** the user ran 3 Veiler / 3 Nibiru / 1 Endgame / 2 Disturbance / Brilliant Move, then switched to the Burnaby Top 4 main after testing ("Nib has not seemed that impactful").
- **Oct 11 — Droll is bad vs the mirror and pure Branded** (user-confirmed).

## Rejected for this build

(Cosmic Cyclone was on this list until Oct 23; the user now sides 3.) Infinite Impermanence, Anti-Spell Fragrance (Forbidden since Oct 19), Songs of the Dominators, Solemn Judgment/Warning, Chaospawn Bishop + Witness lines. (A 3rd Typhoon was rejected before Oct 19; re-added Oct 19 with new evidence, see above.) Explained as "not in your list" on the guide's #cards and #handtraps pages; Songs and Bishop are still tracked as other builds in #builds.

Also: the 2nd Endgame (brick; user Oct 23: "just bad", not even a flex option), 2 Lancea (it turns off your own banishes), Pot of Sloth and a 3rd Typhoon for the open slot (Lava Golem ranked higher).

## Workflow preferences
- **Replays page = Guide chapter 5, the last chapter (user, Oct 27):** high-level games only — regional/YCS/major-event feature matches and high-rated DuelingBook; never locals, unrated DB uploads or commentary/analysis channels; pure Angelechy only. Grouped by matchup (deep-dive ids) as ONE accordion of collapsed rows attached to each other (user, Oct 27: 'too long'), newest first, games before the Oct 19 list marked; no player/creator names; notes paraphrased. Data: build/replays_page.py → build/v3/replays.html (v3_apply inserts it).
- **Text width (user, Oct 24):** paragraphs, lists and card texts fill the content column — no max-width:NNch reading-width limits.

- Deck, side, Extra and siding changes are **proposed in chat**; the guide changes only after the user says yes. Research that doesn't change the deck goes straight into the guide.
- Updates are reported in chat; the guide has no Updates section (Oct 12).
- Ignore Umbral Horror (no deep dive, no siding row).
- Mute videos when reading captions. Never bypass paywalls (Trif's Metafy masterclass). Never enter credentials; the user signs in themselves.
- The user prefers their own side deck over the Louisville Top 4's.
- The user reads the guide on their phone through GitHub Pages.
- **Tools:** the match tracker and life points stay on the device for now; logins come later with the user's **own backend** (a Supabase/Firebase project they create; Claude never creates accounts). The coin and die show over the screen (no playmat), with physics-based motion and fair randomness (Oct 13–14).

## Oct 30 — going-1st siding rule (user)
- "I always want verdict sided in when going first" + "base our siding somewhat on triffs siding ... removing any handtrap that is not super relevant when going first against the specific matchup and keeping in the e4s".
- Every going-1st plan: keep all 3 e4, +1 Verdict, +3 Boarder +2 Thrust (no Boarder in the mirror), −Endgame (stays vs Elfnote), and cut the 5 least relevant hand traps for that matchup. Source of truth: build/side_oct27.py (check() asserts it).
- After-siding going-1st odds: play 90%, survives a hand trap 78% (69% mirror). Home stat + Odds table updated.

## Oct 30 — side: 3 Typhoon replace 3 Cosmic Cyclone (user)
- Typhoon = face-up only, destroys; from hand only while you control no S/T. Never on Dark City or Area Zero. Plans: mirror +2 (both turns), Blitz 2nd +2; Sky Striker 2nd −3 Spark +3 Fuwalos only; D-HERO 1st +1 Skull Meister.
- Oct 30: mirror runs all 3 Typhoon both turns (user); all 3 Spark out both turns; going 2nd only 1 Thrust.
