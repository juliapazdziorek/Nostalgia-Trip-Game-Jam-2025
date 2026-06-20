# Banana's Era Shift

A nostalgia trip through the eras of gaming — three levels, three art styles, three cameras and two players styled after iconic gaming characters.

Built in **24 hours** at the PJATK Game Jam. For the record: 24 hours is *nowhere near* enough time, so the code quality isn't the best. For your own sanity, don't look too closely at the files.

https://github.com/user-attachments/assets/20113fd2-0ea8-44fb-b869-48d30ed3a78a

---
## The Idea

Two players, one goal, three levels you can't beat alone. Each player controls a
shape-shifter with its own tricks — you'll need both to get anywhere.

- **Player 1 — Sonic form** — small and fast, slips through tight gaps.
- **Player 2 — Kong form** — big and strong, shoves and smashes through obstacles.

### Three levels, three eras

Every level jumps to a new generation of gaming — the art, the resolution, and the
camera all shift together.

| Level | Era | Camera |
|:-:|-|-|
| **1** | Low-res arcade pixels — *Donkey Kong* cabinet vibes | Static single frame, no scrolling |
| **2** | Crisp 16-bit pixel art | One shared camera trailing the action |
| **3** | Modern hand-drawn 2D | Split-screen that merges up close, splits apart |

### Features

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
- **Language** — C#
- **Art** — hand-drawn 2D sprites

## My Role

- **Game design** — the core concept, the shape-shift hook, and how the co-op loop fits together
- **Level design** — laying out the three levels and the routes each form unlocks
- **Technical design of the mechanics** — speccing how the transformations, obstacles and camera systems behave

## The Team

- [@juliapazdziorek](https://github.com/juliapazdziorek)
- [@JackKaki](https://github.com/JackKaKi)
- [@VeeturN](https://github.com/VeeturN)
- [@User31181](https://github.com/User31181)

Big thanks to the PJATK Game Jam organizers and the jury.

## License

All rights reserved.
