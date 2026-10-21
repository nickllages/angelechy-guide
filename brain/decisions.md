# Decisions — the user's list, siding rules and preferences

The user plays Angelechy in the TCG, at locals and regionals. These are their decisions. Don't re-propose what they rejected unless new evidence is strong, and say so when you do. The user changes lists quickly, so confirm the full 40 + side before rebuilding siding.

## Current 70 (user, Oct 19: deckbuilder screenshot after the October 19 Forbidden & Limited list)

**Main 40** (same 40 as before the list)
- Monsters (11): 3 Ash Blossom & Joyous Spring, 2 Ghost Ogre & Snow Rabbit, 3 Mulcharmy Fuwalos, 2 Nibiru, the Primal Being, 1 Droll & Lock Bird
- Spells (14): 3 Angelechy Strategy Score, 3 Angelechy Opposition, 3 Angelechy Problem, 3 Foolish Burial Goods, 1 Terraforming, 1 Angelechy Endgame Problem
- Traps (15): 3 Angelechy Opening to e4, 2 Angelechy Verdict, 1 Angelechy Disturbance, 3 Dominus Impulse, 3 Dominus Purge, 3 Dominus Spark

**Extra 15:** 3 Angelechy Enlisted, 2 Angelechy Bastion, 2 Angelechy Destrier, 2 Angelechy Shatranga, 1 Angelechy Seneschal, 1 Angelechy Castellan, 1 Chaos Angel, 1 Black-Winged Assault Dragon, 1 Assault Blackwing – Kusanagi the Gathering Storm, 1 Centur-Ion Legatia

**Side 15:** 3 Lava Golem, 3 Inspector Boarder, 3 Triple Tactics Thrust, 2 Effect Veiler, 2 Typhoon, 1 Ghost Ogre & Snow Rabbit, 1 Angelechy Brilliant Move

Counts: 13 starters (16 going second counting e4); 23 interruptions → 80% to open 3+; going-2nd plans 24–26 (Lava Golem is a breaker, not counted). Deckbuilder odds: 87.5% a play going 1st, 55.2% survives a hand trap; after siding 88% / 77%.

Earlier on Oct 19 the user said they ran 2 Disturbance; the screenshot (their final word) shows 1 Disturbance + 3 FBG. Proposals they declined: Nibiru→Veiler main, Brilliant Move main, 3 Ogre main, Droll to the side, 2 Spark, Hyperion, 2nd Castellan, 3rd Typhoon, Purulia (they chose 3 Lava Golem).

## Siding rules (user)

- Side in **only** cards that matter in the matchup; side out main cards that are bad there (Oct 12).
- **Never side out Opposition** ("my best card", Oct 13).
- **Going second, never side out** Verdict, Disturbance, Endgame or Opening to e4.
- **Going first (default):** −3 Fuwalos −1 Endgame −1 e4 −1 Nibiru → +3 Boarder +3 Thrust. Elfnote and pure Branded: −1 Droll instead of the Nibiru. Mitsurugi, Destiny HERO and Invoked: −2 Ogre instead of the e4 and Nibiru. Sky Striker: −2 Nibiru (keep the e4). Mirror: no Boarder (−3 Fuwalos −1 Droll −2 Nibiru → +1 Ogre +2 Typhoon +3 Thrust).
- **Going second:** engine out in order Terraforming, FBG, FBG, then Strategy Score. Veiler ×2 + the 3rd Ogre vs Elfnote, Yummy, Fairy Tail, Maliss; Lava Golem vs Black Chaos (2 vs ROLAD piles), Mirrorjade, Liger Dancer, Jinzo/Red-Eyes Exceed, and the Patron/Mitsurugi/D-HERO/Invoked boards; mirror −1 Droll −2 Nibiru −3 Spark → +1 Ogre +2 Typhoon +3 Thrust.
- **Card-specific cuts:** Droll out vs the mirror, pure Branded (and Elfnote going 1st). Ghost Ogre out vs Mitsurugi, Destiny HERO and Invoked. Nibiru out vs the mirror and Sky Striker. Fuwalos out vs (pure) Blitzclique. Spark out vs the mirror (going 2nd), Sky Striker and DTW.
- Brilliant Move: situational side card (no standard plan).

## Siding plans (generated from the newest `build/side_*.py`; do not edit by hand)

<!-- plans:start -->
*From `build/side_oct19.py` (2026-10-21).*

| Matchup | Going 1st | Going 2nd |
|---|---|---|
| Elfnote Ars Magna | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Droll → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Ghost Ogre |
| ROLAD pile | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Lava Golem, +1 Effect Veiler |
| Angelechy mirror | −3 Fuwalos, −1 Droll, −2 Nibiru → +1 Ghost Ogre, +2 Typhoon, +3 Triple Tactics Thrust | −1 Droll, −2 Nibiru, −3 Spark → +1 Ghost Ogre, +2 Typhoon, +3 Triple Tactics Thrust |
| Branded ROLAD | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Lava Golem, +1 Effect Veiler |
| Power Patron / Artmage | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Lava Golem |
| Yummy | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Ghost Ogre |
| Mitsurugi | −3 Fuwalos, −1 Endgame Problem, −2 Ghost Ogre → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Ghost Ogre, −1 Terraforming → +2 Effect Veiler, +1 Lava Golem |
| Fairy Tail | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Ghost Ogre |
| Blitzclique | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −3 Fuwalos → +2 Typhoon, +1 Ghost Ogre |
| Branded | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Droll → +3 Inspector Boarder, +3 Triple Tactics Thrust | −1 Droll, −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Ghost Ogre, +1 Lava Golem |
| Destiny HERO | −3 Fuwalos, −1 Endgame Problem, −2 Ghost Ogre → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Ghost Ogre, −1 Terraforming → +2 Effect Veiler, +1 Lava Golem |
| Dark Time Wizard | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −3 Spark → +2 Effect Veiler, +1 Lava Golem |
| Sky Striker | −3 Fuwalos, −1 Endgame Problem, −2 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −3 Spark, −2 Nibiru → +2 Effect Veiler, +2 Typhoon, +1 Ghost Ogre |
| Invoked | −3 Fuwalos, −1 Endgame Problem, −2 Ghost Ogre → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Ghost Ogre, −1 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Typhoon, +1 Lava Golem |
| Maliss | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Ghost Ogre |
| Sacred Beast | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Typhoon, +1 Ghost Ogre |
| Lunalight | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Nibiru → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Effect Veiler, +1 Lava Golem |
<!-- plans:end -->

## Card decisions and the reasons (newest first)

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

Infinite Impermanence, Cosmic Cyclone, Anti-Spell Fragrance (Forbidden since Oct 19), Songs of the Dominators, Solemn Judgment/Warning, Chaospawn Bishop + Witness lines. (A 3rd Typhoon was rejected before Oct 19; re-added Oct 19 with new evidence, see above.) Explained as "not in your list" on the guide's #cards and #handtraps pages; Songs and Bishop are still tracked as other builds in #builds.

Also: the 2nd Endgame (brick), 2 Lancea (it turns off your own banishes), Pot of Sloth and a 3rd Typhoon for the open slot (Lava Golem ranked higher).

## Workflow preferences

- Deck, side, Extra and siding changes are **proposed in chat**; the guide changes only after the user says yes. Research that doesn't change the deck goes straight into the guide.
- Updates are reported in chat; the guide has no Updates section (Oct 12).
- Ignore Umbral Horror (no deep dive, no siding row).
- Mute videos when reading captions. Never bypass paywalls (Trif's Metafy masterclass). Never enter credentials; the user signs in themselves.
- The user prefers their own side deck over the Louisville Top 4's.
- The user reads the guide on their phone through GitHub Pages.
- **Tools:** the match tracker and life points stay on the device for now; logins come later with the user's **own backend** (a Supabase/Firebase project they create; Claude never creates accounts). The coin and die show over the screen (no playmat), with physics-based motion and fair randomness (Oct 13–14).
