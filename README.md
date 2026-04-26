
# Banana's Era Shift

A nostalgia trip through the eras of gaming — three levels, three art styles, three cameras, two players who don't quite play the same game.

<!-- Drop your gameplay GIF or MP4 right here.
     Easiest way: open this README in GitHub's web editor and drag the file
     into the editor — GitHub will host it for you automatically. -->
![Gameplay Preview](docs/media/gameplay.gif)

---

## About

Banana's Era Shift is a local co-op 2D platformer built in **24 hours** during the 8th edition of the **PJATK Game Jam — *Nostalgia Trip*** (November 2025). It took home **2nd place**.

The hook: two players, two shape-shifters, three different eras of platforming. Each player drives a small generic mascot that **transforms on demand into its legendary form** — Player 1 shrinks down into a quick, expressive **Sonic the Hedgehog**, Player 2 bulks up into a heavy classic **Kong**. Transformation isn't cosmetic — it's how you solve the level. Hedgehog-Sonic's smaller hitbox squeezes through gaps that the default mascot can't fit through; Kong's bulkier form can shove rolling barrels around the stage instead of dying on contact. The two forms unlock different routes through the same room, and the players have to coordinate which form is doing what at any moment. Hedgehog collects apples, Kong collects bananas, and together they traverse three levels — each one shifting the visual style **and** the camera system to match a different era of the medium.

## Features

- **Movement that ages with the era.** Level 1 is deliberately stiff and arcade-y; later levels loosen up into dashes, wall-jumps and a grappling hook with auto-aim.
- **One-button shape-shift, asymmetric powers.** Hedgehog-Sonic shrinks to slip through tight gaps; Kong bulks up to shove rolling barrels around. Same input, opposite affordances.
- **Three levels, three eras, three cameras** — art style, pixel resolution, and camera all shift together to mirror a generation of the medium:
    - **Level 1 — early arcade.** Chunky low-res pixels, single static frame, no scrolling. *Donkey Kong* cabinet framing.
    - **Level 2 — 16-bit.** Sharper pixel art, one shared camera that trails the action across a level bigger than the screen.
    - **Level 3 — modern.** Hand-drawn high-res art, split-screen that merges when players are close and splits when they separate, with the divider rotating to stay perpendicular to the axis between them.
- **Per-character collectibles** — apples for Hedgehog-Sonic, bananas for Kong, re-skinned per era.
- **Classic obstacle kit** — rolling barrels, spawners, falling islands, moving platforms, moving walls, trampolines, seesaw boosters, spikes, doors, hooks, button triggers.
- **Polished menu and scene flow** — title → main menu → loading-with-controls → in-game → pause → credits → end, with a smoothly zooming menu camera and additive scene loading throughout.

## Built With

- **Engine** — [Unity 2022.3.46f1 LTS](https://unity.com/)
- **Language** — C# (~24 gameplay scripts, ~2,400 lines)
- **Art** — hand-drawn 2D sprites

## The Team

- [@juliapazdziorek](https://github.com/juliapazdziorek)
- [@JackKaki](https://github.com/JackKaKi)
- [@VeeturN](https://github.com/VeeturN)
- [@User31181](https://github.com/User31181)

Big thanks to the PJATK Game Jam organizers, the jury, and everyone who showed up to playtest at 4 AM.

## License

All rights reserved.
