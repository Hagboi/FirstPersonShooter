# Dead Holdout

A wave-based zombie survival first-person shooter that runs in the browser. It's built with Three.js. All textures, models and sounds are generated in code, so there are no asset files.

## Play

Open `index.html` in a modern desktop browser (Chrome, Edge or Firefox). You need an internet connection the first time, because Three.js loads from a CDN.

If your browser blocks the file, serve the folder instead:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

You can also host it for free with GitHub Pages: go to Settings → Pages and deploy from your branch.

## Features

- **Rounds of zombies.** Each round brings more zombies with more health. From round 3, sprinters with red eyes start to show up.
- **Points.** You earn 10 per hit, 60 per kill, 100 per headshot kill and 130 per knife kill. Rebuilding a boarded window earns 10 per board.
- **Map.** The bunker has a start room, a storage room, a laboratory and a snowy courtyard. You open new areas by paying to clear debris.
- **Boarded windows.** Zombies tear the boards off to get in. Hold **F** at a window to nail them back up.
- **Wall weapons.** Kar98k, M1 Garand, Double-Barrel, Trench Gun, MP40, Thompson and STG-44, plus ammo refills.
- **Mystery Box (950 points).** Gives a random weapon: BAR, MG42, PTRS-41 anti-tank rifle, the wall weapons, or (rarely) the **Ray Gun**. Sometimes the box laughs at you, refunds your points and moves somewhere else.
- **Perk machines.** Tough Stuff gives more health, Quick Hands speeds up reloads, Rapid Rush raises fire rate, and Extra Holster lets you carry a third weapon.
- **Power-ups.** Zombies sometimes drop Max Ammo, Insta-Kill, Double Points, Kaboom or Carpenter.
- **Menus.** Main menu, pause menu, settings (sensitivity, FOV, volume, render quality, invert Y, FPS counter), how-to-play and game over.
- **Cheats menu.** Press **`** or **P** in-game. It has 22 toggles, including god mode, infinite ammo, bottomless mag, rapid fire, one-hit kills, explosive bullets, infinite points, a rigged box, freeze zombies, no clip, super speed/jump, low gravity, zombie X-ray, big heads, fullbright and no fog. There's also a zombie speed slider, plus actions: give points, give any weapon, jump to any round, spawn power-ups, open all doors, give all perks, kill all zombies and more.

## Controls

| Key | Action |
|---|---|
| WASD / Mouse | Move / look |
| Left / Right click | Fire / aim down sights |
| R | Reload |
| Shift | Sprint |
| Space | Jump |
| C / Ctrl | Crouch |
| F | Buy / use / take / rebuild (hold) |
| V or E | Knife |
| 1 2 3 / Q / Wheel | Switch weapon |
| Esc | Pause |
| ` or P | Cheats |
