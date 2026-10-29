# NEON REQUIEM: 2099 — Phase 2 playable upgrade

## Running
Keep `index.html`, `style.css`, `script.js`, and `assets/` together. Open index.html in a modern browser, or deploy the complete folder to GitHub Pages. Audio is off by default; enable it from Settings after interacting with the page. File-based browser audio permissions vary, so localhost or HTTPS is recommended.

## What's playable in this build
- Original V2 save slots, encrypted export/import, missions, shops, crafting, factions, cyberware, NPC contacts, housing, businesses and tactical turn-based combat.
- Automatic world clock (20 real minutes per in-game day by default); auto weather and random city bulletins; pause when browser closed; retained in the save.
- Settings: Easy/Normal/Hard, clock speed, event frequency, audio levels, auto/compact/comfortable density, reduced motion, graphics quality.
- Compact fixed-height responsive gameplay shell with independent list scrolling.
- Real-time top-down street racing controlled by arrow/WASD/space or on-screen touch buttons; vehicle prerequisites, collisions, damage, nitro and money rewards.
- Combat adds AIM and COVER tactical moves to V2 weapon, stamina, reload, OS-gated hacking, damage, bosses and death checkpoint.
- Supplied Kenney sound effects and two music tracks bundled locally. Sounds are mapped to available game interactions, not yet all requested audio categories.

## Known limitations and candid scope
This is an incremental playable upgrade, not a finished simulation of every one of the 50 requested ideas. Full grid-based combat, independent pathfinding NPCs, advanced pursuit steering, detailed business operations, fully voiced NPCs, complete original-music soundtrack and complete audio coverage are not present. World events are abstracted as bulletins and faction changes, not fully animated NPC crowds. Racing is an arcade mini-game, not a continuous city-scale driving world. Some browsers prohibit local-file audio playback; GitHub Pages/localhost is recommended. Local browser saves can be modified by users; password-protected exports do not prevent cheating.

## Save compatibility
The V2 `nr2099-slot-0..2` localStorage save format is preserved. The same origin/browser profile is needed to see existing saves; exporting V2 saves before switching deployment origins is wise.

## Third-party audio
Kenney CC0 sound effect packs plus the two user-supplied music tracks; see assets files and license/manifest for identification. Verify individual music licensing before public distribution.
