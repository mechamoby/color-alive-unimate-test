# Color Alive — UniMate T. rex + Stegosaurus walk + chomp (live test)

> **Note:** This is a **Color Alive! Sandbox** demo (UniMate spike), not the Color Alive! Dino Friends product.


Playable Three.js page for the UniMate walk/stand/feed spike, with a species toggle:

- T. rex (default): `/`.
- Stegosaurus: `/?species=stego`.

Both come from Sandbox branch `stego-unimate-spike`; the T. rex was first built on `trex-unimate-spike`. Quadruped planted-foot walk; small herbivore munch (lean in, 20° open, snap, 3 grinding chews, happy settle + tail wag).

Source: private repo `mechamoby/Color-Alive-Sandbox`.

Controls: Walk · Stand · Feed (or tap dino) · Slow-mo.

Walk v2: procedural planted-foot cycle (no foot slide, steady arms, seamless 2.4 s loop). Chomp unchanged.

Playtest polish (2026-09-30):
- T. rex: mouth corners open as a smooth cheek (no stretched strip at full gape; max gape 35°), and the arms stay outside the torso through the chews and the happy beat.
- Stego: the open mouth is hollow, with no centre pillar and no web between the jaws.
