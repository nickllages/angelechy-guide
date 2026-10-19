# Decisions — the user's list, siding rules and preferences

The user plays Angelechy in the TCG, at locals and regionals. These are their decisions. Don't re-propose what they rejected unless new evidence is strong, and say so when you do. The user changes lists quickly, so confirm the full 40 + side before rebuilding siding.

## Current 70 (since Oct 19, 2026: after the October 19 Forbidden & Limited list; the guide's recommended list, applied at the user's request)

**Main 40**
- Monsters (11): 3 Ash Blossom & Joyous Spring, 3 Ghost Ogre & Snow Rabbit, 3 Mulcharmy Fuwalos, 2 Effect Veiler
- Spells (15): 3 Angelechy Strategy Score, 3 Angelechy Opposition, 3 Angelechy Problem, 3 Foolish Burial Goods, 1 Terraforming, 1 Angelechy Endgame Problem, 1 Angelechy Brilliant Move
- Traps (14): 3 Angelechy Opening to e4, 2 Angelechy Verdict, 1 Angelechy Disturbance, 3 Dominus Impulse, 3 Dominus Purge, 2 Dominus Spark

**Extra 15:** 2 Angelechy Enlisted, 2 Angelechy Bastion, 2 Angelechy Destrier, 2 Angelechy Shatranga, 2 Angelechy Castellan, 1 Angelechy Seneschal, 1 Chaos Angel, 1 Assault Blackwing – Kusanagi the Gathering Storm, 1 Centur-Ion Legatia, 1 Masterflare Hyperion

**Side 15:** 3 Inspector Boarder, 3 Triple Tactics Thrust, 2 Nibiru, the Primal Being, 2 Mulcharmy Purulia, 3 Typhoon, 1 Effect Veiler, 1 Droll & Lock Bird

Counts: 13 starters (16 going second counting e4); 22 interruptions (11 monster hand traps + 8 Dominus + 3 e4) → 76% to open 3+ in 6; most going-2nd plans reach 25 (87%). Odds (deckbuilder): 87.5% a play going 1st, 55.4% a play that survives a hand trap; going 1st after siding 88% / 77%.

Pre-list (Oct 16) list for reference: main 3 Ash, 2 Ogre, 3 Fuwalos, 2 Nibiru, 1 Droll, 3 Spark; side 3 Boarder, 2 Thrust, 1 Talent, 1 Brilliant Move, 1 Ogre, 2 Purulia, 2 Typhoon, 2 Veiler, 1 Droll; Extra 3 Enlisted, 2 Seneschal, 1 Castellan, Black-Winged Assault Dragon.

## Siding rules (user)

- Side in **only** cards that matter in the matchup; side out main cards that are bad there (Oct 12).
- **Never side out Opposition** ("my best card", Oct 13).
- **Going second, never side out** Verdict, Disturbance or Endgame (single copies), Opening to e4, or (since Oct 19) Brilliant Move.
- **Going first (default, Oct 19):** −3 Fuwalos −1 Endgame −1 e4 −1 Brilliant Move → +3 Boarder +3 Thrust. Exceptions:
  - Mitsurugi, Destiny HERO and Invoked: −3 Ghost Ogre instead of the e4, +1 Veiler +1 Droll from the side.
  - Sky Striker: also −1 Ghost Ogre +1 Droll (Engage!).
  - Mirror: no Boarder (−3 Fuwalos −2 Veiler −1 Brilliant Move → +3 Typhoon +3 Thrust).
- **Going second: engine comes out in this order:** Terraforming, then Foolish Burial Goods, then the 2nd FBG, then Strategy Score (Oct 14, the user's correction: Opposition's GY effect shuffles FBG's targets back). Cut engine only to make room for a card that matters.
- **Matchup-specific going-2nd decisions (Oct 19):** Elfnote keeps Spark (−2 FBG −1 Terra → +2 Nibiru +1 Veiler). Mirror: −2 Veiler −2 Spark −1 Terra → +3 Typhoon +2 Thrust. Search engines (ROLAD, Branded ROLAD, Patron, Mitsurugi, D-HERO, Invoked, Sky Striker, Sacred Beast, DTW) get the side Droll.
- **Card-specific cuts:** Droll stays out vs the mirror, Elfnote and pure Branded. Ghost Ogre out vs Mitsurugi, Destiny HERO and Invoked. Veiler out vs the mirror and Blitzclique. Nibiru never vs the mirror or Sky Striker. Fuwalos out vs (pure) Blitzclique.

## Siding plans (generated from the newest `build/side_*.py`; do not edit by hand)

<!-- plans:start -->
*From `build/side_oct19.py` (2026-10-19).*

| Matchup | Going 1st | Going 2nd |
|---|---|---|
| Elfnote Ars Magna | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Nibiru, +1 Effect Veiler |
| ROLAD pile | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Droll |
| Angelechy mirror | −3 Fuwalos, −2 Effect Veiler, −1 Brilliant Move → +3 Typhoon, +3 Triple Tactics Thrust | −2 Effect Veiler, −2 Spark, −1 Terraforming → +3 Typhoon, +2 Triple Tactics Thrust |
| Branded ROLAD | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Droll |
| Power Patron / Artmage | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +1 Droll, +1 Nibiru, +1 Effect Veiler |
| Yummy | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Nibiru |
| Mitsurugi | −3 Fuwalos, −1 Endgame Problem, −3 Ghost Ogre, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust, +1 Effect Veiler, +1 Droll | −3 Ghost Ogre, −1 Terraforming → +2 Purulia, +1 Effect Veiler, +1 Droll |
| Fairy Tail | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Nibiru |
| Blitzclique | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −3 Fuwalos, −2 Effect Veiler, −1 Terraforming → +2 Purulia, +3 Typhoon, +1 Nibiru |
| Branded | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Effect Veiler |
| Destiny HERO | −3 Fuwalos, −1 Endgame Problem, −3 Ghost Ogre, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust, +1 Effect Veiler, +1 Droll | −3 Ghost Ogre, −1 Terraforming → +2 Purulia, +1 Droll, +1 Effect Veiler |
| Dark Time Wizard | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Spark → +1 Effect Veiler, +1 Droll |
| Sky Striker | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move, −1 Ghost Ogre → +3 Inspector Boarder, +3 Triple Tactics Thrust, +1 Droll | −2 Spark, −1 Terraforming → +1 Effect Veiler, +1 Droll, +1 Typhoon |
| Invoked | −3 Fuwalos, −1 Endgame Problem, −3 Ghost Ogre, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust, +1 Effect Veiler, +1 Droll | −3 Ghost Ogre, −1 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Typhoon, +1 Droll, +1 Effect Veiler |
| Maliss | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Nibiru |
| Sacred Beast | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +1 Typhoon, +1 Nibiru, +1 Droll |
| Lunalight | −3 Fuwalos, −1 Endgame Problem, −1 Opening to e4, −1 Brilliant Move → +3 Inspector Boarder, +3 Triple Tactics Thrust | −2 Foolish Burial Goods, −1 Terraforming → +2 Purulia, +1 Nibiru |
<!-- plans:end -->

## Card decisions and the reasons (newest first)

- **Oct 19 — the October 19 list (user: research the list, rank decks, pick non-engine, modify the deck, side first).** Talent Forbidden → 3rd Thrust; Droll Limited (illegal 2nd copy). Main: 3rd Ghost Ogre (all 8 pure Houston Top 32 lists ran 3), 2 Veiler main (Elfnote, Patron, Sky Striker, Maliss, D-HERO), Spark 3 → 2 (weak in the mirror and vs Sky Striker), Nibiru to the side (does nothing in the mirror, now the most common matchup).
- **Oct 19 — refined after Drizzels' three post-BETB Angelechy videos (user asked to study them) and the Houston Top 32:** Brilliant Move to the main and Droll to the side (Colin H., #1 DB rated: no Droll, Brilliant Move main, 21 hand traps, "22-ish" max; 6 of 8 pure Houston lists main Brilliant Move). Extra: 2nd Castellan (Colin H.: needed for Opposition after e4's Castellan is hit; 3 of 8 Houston lists), Hyperion (7 of 8) and Legatia (5 of 8) for Black-Winged Assault Dragon, the 3rd Enlisted and the 2nd Seneschal (every Houston list ran 2 Enlisted, 1 Seneschal).
- **Oct 19 — re-added despite earlier rejections, with the evidence:** Brilliant Move main (rejected Oct 13 as "win more"; now 6/8 Houston lists + Colin H.; it's the first card out going 1st) and a 3rd Typhoon (rejected Oct 13–16; the mirror is now the most common matchup and Bastion is the card to hit; 3 of 8 Houston lists side 3). Told the user both can be reverted.

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
