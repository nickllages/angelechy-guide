# Open questions

Close an item by moving it to the bottom section with the answer and date. Don't delete it.

## Waiting on the user

1. **Ryzeal Blitzclique siding (proposed Oct 14).** The user's locals play Ryzeal Blitzclique, where Fuwalos draws (Ice Ryzeal's Deck summon, Rank 4 Xyz). Proposal: vs Ryzeal Blitzclique going 2nd keep Fuwalos and play −2 FBG −1 Terraforming → +2 Purulia +1 Droll (27). Pure Blitzclique keeps the current plan. Undecided: make it the default Blitz row, or add a second row?
2. ~~**The 3rd Thrust slot (Oct 13).**~~ Closed Oct 16: the user put Angelechy Brilliant Move there (situational, going 2nd vs battle-only boards).
3. **Logins (Oct 13).** The user chose their own backend (Supabase or Firebase) later. Needed from them: a project URL and its public (anon) key. Then: sign-in, private decklists per viewer, the user's public list and change feed, a tracker only they can read. Until then, the tracker and life points are device-only (localStorage).

## Research to do

0. **Emergency Forbidden & Limited list (announced Oct 14):** 34 Forbidden + 8 Limited, revealed Oct 16–18 at YCS Houston. When it's out: check every card in the 70 and the Builds section, the top-10 decks, and the hand-trap matrix; propose deck changes in the run summary. Then rebuild the Deckbuilder's card list (`python3 tools/build_carddb.py`) and republish.

4. **Trif's "number one hand trap against Angelechy"** (kept for his paid Metafy masterclass with Lucas Sacco, launched Oct 14). Never bypass the paywall; watch free sources. Card-text guesses: **D.D. Crow** (banishes Verdict in the GY before its effect; works at their own Standby against your e4 loop) and **Artifact Lancea** (on your turn nothing can be banished, which shuts off Verdict/Disturbance/Opposition/Strategy Score GY costs and Enlisted/Castellan/Endgame banishes). Ruled out: Dimension Shifter (Forbidden in the TCG), Retaliating "C" (only triggers on Spells that Special Summon). **Oct 21 lead:** Trif sided 3 Skull Meister vs Angelechy at YCS Houston (Top 4, went 4–1 vs Angelechy, "amazing against them") — strongest free-source candidate; still not named. Added as a lead in the guide's 'What opponents side against you' box.
5. **Unposted lists:** ~~the Belén winner~~ (posted Oct 15, see meta.md), Joshua Artavia (Belén Top 4), Prabhdeep Atwal (Burnaby 2nd). (Monterrey top cut posted Oct 14: no Angelechy.)
6. **Hand-trap matrix gaps ("—" in the guide's #handtraps):**
   - Ghost Ogre vs Branded ROLAD.
   - Fuwalos and Nibiru vs Mitsurugi.
   - Spark vs ROLAD, Branded ROLAD, Mitsurugi and Yummy.
   - Impulse vs Yummy.
   - Veiler vs ROLAD and Branded ROLAD.

   Fill them from replays.
7. **Is Ryzeal Blitzclique growing after BETB?** Only the Rochester/Manchester tops so far (September).
8. **A new deep dive for any deck that tops** (Ryzeal, Orcust, K9, Ashtra, Primite, Mermail — Mermail won Burnaby).

## Judge checks ⚖

9. Seneschal's mandatory trigger on their field counts as **their** monster-effect activation (turns on Thrust and Talent; uses their one effect under Boarder).
10. Enlisted targeting Seneschal: Seneschal goes to the Extra Deck instead of being banished, so Enlisted never changes control (line F).
11. Enlisted's mandatory return effect, when given to them by Disturbance, counts against Boarder's cap.
12. Endgame 3+: Set Verdict and activate it the same turn (line EG4).
13. Forbidden Droplet: does a placed Angelechy sent as cost count as a Monster Card (original type) for its "can't respond with the same type" clause?
14. Boarder: Pendulum Scales are Spell Cards, so only monsters in Monster Zones count as types (assumed).

## Closed

- **Oct 16 — Belén winner's list?** Posted Oct 15: 2 Droll/0 Nibiru main, Brilliant Move main, 3 Lava Golem + 3 Nibiru side (meta.md).

- **Oct 14 — Is the coin random?** Yes. Over 4,000 flips, 50.5–51.2% Heads; die χ² normal over 180,000 rolls. The motion looked scripted and was rebuilt with physics.
- **Oct 14 — Elfnote going 2nd: cut Spark?** No; cut engine (user agreed).
- **Oct 14 — Engine cut order going 2nd?** Terraforming → FBG → FBG → Strategy Score (user's point about Opposition recycling).
- **Oct 13 — Thrust/Talent going 2nd in the mirror?** Yes; Opposition's Seneschal turns them on (user's point).
