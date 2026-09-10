# Firstfire

[Play the main version](https://wiserax.github.io/firstfire/) · [Original edition, preserved](https://wiserax.github.io/alex-wiserax-firstfire/)

Twenty-round settlement defense with flexible building sites, selling, respawning lane infantry, gold mines, optional world chests and distinct maps. Mobile touch controls; separate V2 progress and settings.

The formations update introduces enemies progressively: weak raiders first, a 70/30 raider-runner mix next, then shields, healers, saboteurs, ranged attackers, charging lancers, siege crews and wardens. Scout the next formation and invest in the defenses that counter it. Named construction shortcuts make lane barracks and gold mines available after the first round. Mines produce session amber; permanent training and the shop remain separate.

`index.html` and `Firstfire.html` are the same self-contained game. Original models, audio and vector card art; third-party library and font notices are retained in `licenses/` and the HTML.

Source implementation: `99c6d182dbf31cc65c9046d99f43e8299a8d3b31` (gameplay-v2 branch). Original edition has not been modified.

River rendering hotfix: water, banks and highlights have separate depth layers; highlights follow the curved channel.

Balance and clarity update: compact boss HUD; independently firing siege crews with readable reload states; aiming and recoiling player weapons; six visual stages for each specialized tower (levels 3–8); paid outer plots with construction materials and persistent per-run land ownership. Early camp plots remain free. Mine returns and later upgrade costs now make expansion compete with immediate defense.

Records update: choose a nickname once, retain a player identity across tabs and reloads, and recover that identity on another device with a private recovery code. Shared rankings keep each player’s best finished run. Battle reports celebrate personal records and show earned permanent rewards, kills, tower contribution and collected relics. Analytics is creator-only. Recovery restores online identity and records, not device-local game saves.
