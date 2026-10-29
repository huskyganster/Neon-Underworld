# NEON REQUIEM: 2099 — V4 Foundation Playable Build

## Start
Keep `index.html`, `style.css`, `script.js`, and the entire `assets/` folder together. Run a local static server (`python -m http.server 8000`) and visit http://localhost:8000 or upload the contents to GitHub Pages.

## V4 implemented in this build
- Fully movable top-down district map with generated street grids, buildings, civilian walkers, gang enemies, patrols, and marked shops, garage, contacts lounge, clinic.
- PC movement WASD/arrow keys, aim with mouse, hold click to shoot, E interact, R reload, Q use med item.
- Mobile twin-stick movement/aim and action buttons; enemies shoot independently in real time and the character takes damage.
- NPC gunfight consequences increase wanted level, contextual credit drops; wanted level 5 can deploy unusually powerful tactical officers.
- Map canvas recreated after rendering / switching screens, with fallback navigation list of all 8 districts.
- Cyberpsychosis values constrained to 0–100; effects cleaned on reload and starting a game.
- All V3 functionality (menu, saves, markets, cyberware, mission list, combat arena, racing, settings and included licensed audio) is retained.
- Audio is attempted after entering the game; a browser may still block or mute it until an interaction.

## Scope / limitations
This is a playable V4 **foundation milestone**, not complete delivery of the entire 10-task V4 design. The old Arena remains turn-based; the new world map has real-time action. Many planned systems (full corporate careers, stock market, property simulation, custom illustrated cyberware screen, full heist missions, smarter simulated traffic and faction territory warfare) are still pending. Environmental characters are simple geometric representations, not completed art. Save state remains editable in browser storage, although file exports can be encrypted. Full end-to-end browser testing may uncover additional bugs.

## Preserve old saves
Uses the existing V3 slot keys (`nr2099-slot-0` through `nr2099-slot-2`). Back up/export your saves before replacing your published files. Reloaded saves retain V3 schema.
