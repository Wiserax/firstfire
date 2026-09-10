# Firstfire

[Play the main version](https://wiserax.github.io/firstfire/) · [Original edition, preserved](https://wiserax.github.io/alex-wiserax-firstfire/)

Twenty-round settlement defense with flexible building sites, selling, respawning lane infantry, gold mines, optional world chests and distinct maps. Mobile touch controls; separate V2 progress and settings.

The formations update introduces enemies progressively: weak raiders first, a 70/30 raider-runner mix next, then shields, healers, saboteurs, ranged attackers, charging lancers, siege crews and wardens. Scout the next formation and invest in the defenses that counter it. Named construction shortcuts make lane barracks and gold mines available after the first round. Mines produce session amber; permanent training and the shop remain separate.

`index.html` and `Firstfire.html` are the same self-contained game. Original models, audio and vector card art; third-party library and font notices are retained in `licenses/` and the HTML.

Source implementation: `a026c890bf935e54524736b7024d7f85e2382c4f` (gameplay-v2 branch). Original edition has not been modified.

River rendering hotfix: water, banks and highlights have separate depth layers; highlights follow the curved channel.

Balance and clarity update: compact boss HUD; independently firing siege crews with readable reload states; aiming and recoiling player weapons; six visual stages for each specialized tower (levels 3–8); paid outer plots with construction materials and persistent per-run land ownership. Early camp plots remain free. Mine returns and later upgrade costs now make expansion compete with immediate defense.

Records update: choose a nickname once, retain a player identity across tabs and reloads, and recover that identity on another device with a private recovery code. Shared rankings keep each player’s best finished run. Battle reports celebrate personal records and show earned permanent rewards, kills, tower contribution and collected relics. Analytics is creator-only. Recovery restores online identity and records, not device-local game saves.

Sound update 24: original adaptive music with three chapter arrangements, tactile coin/deposit sounds, distinct weapons and boss entrances, escalating treasure reveals, and rewarding result cues. Independent master/music/effects/ambience sliders retain your preferences. Sound pauses when the game is hidden. All sound is generated locally; no external audio downloads.

Build 25 — Experiments: forge towers from ten elements and ten attack patterns, then mix a second element. Three seeded discoveries per upgrade, three rarity tiers and previews using the actual game models. Evolve barracks through three bloodlines, three roles and three mutations into 27 troop forms. Seven sky weapons offer temporary powers with visible combat charge. New attack and evolution sounds, bounded effects, and revised enemy/economy tuning accompany the update. Existing identity and progress are retained; old tower saves migrate to the forge system.
