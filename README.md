# Bumper Crop

A penny-arcade orchard machine in a single HTML file. Drop apples through
brass pegs, ring the toadstool bumpers, land the big baskets. Spend your
coins at the back counter. Nudge if you must — but mind the TILT.

**Play:** open `index.html` in any browser. No accounts, no ads, works
offline, saves your coins and upgrades in the browser.

## The loop

- Aim with the mouse (or ←/→); drop with click / tap / ↓ / Enter — fully keyboard-playable: ← → aim, ↓ drop, ↑/space hop, N nudge
- **The paddle follows your mouse** — chase the apple and bounce it toward
  the basket you want; off-center hits add english. Gentle balls roll
  through… unless you **HOP** (space / right-click): the rising plank
  volleys anything it touches, rescue included
- Pegs are worth a little, bumpers a lot; the basket multiplies the
  ball's whole haul (×1 to ×10)
- Coins buy upgrades: bigger hopper, faster apples, louder bumpers,
  golden pippins (×5 balls), twin windfall (splits), a wider plank, and — for the
  pinball faithful — **NUDGE**, which physically shoves every ball.
  Three nudges in quick succession and the machine **TILT**s: six
  seconds of dead bumpers and a locked hopper, exactly as tradition
  demands.

## The furniture (real pinball, miniaturized)

- **Pop bumpers** — the toadstools; the kick is the point
- **Rollovers** — roll through the lanes up top to spell **C·R·O·P**;
  complete the word and the **kickback** arms
- **Kickback** — while armed, a ball landing in a lousy ×1 basket gets
  fired back into play, score intact, one save per arming
- **Drop targets** — knock the bank of three down for a coin burst —
  and a **prism peg** appears: a rainbow pin that spawns a fresh ball
  every time it's struck (three charges, twenty seconds, total mayhem)
- The orchard is said to have wildlife. No further comment.

## The Tinker's Hatch

Below the shop: free tweaks, saved with your game. **Paddle feel** slider
(heavy → lightning), four **paint schemes** (Orchard, Midnight, Circus,
Copper), **square bumpers** — with true square physics, so flat sides
kick straight and corners are spicy — and **Sell the machine**, a full
fresh start (coins, upgrades, tweaks, and board bests all cleared;
the boards themselves are safe in their seeds).

## Boards are seeded

The URL hash is the peg layout: `#orchard-fair-42` is the same board for
everyone, forever. **Daily board** loads `#daily` — one shared layout per
UTC day, so friends can compete on the same pegs. **Share** copies a
board's permanent address. Finding the lane that feeds the ×10 basket is
per-board strategy, not luck.

## Deploy (same recipe as Smallfolk)

```bash
cd bumper-crop
gh repo create bumper-crop --public --source=. --push   # or create via web UI
# then: repo Settings → Pages → deploy from main / root
```

Canonical URL used by the Share button: `https://davidwbritt.github.io/bumper-crop/`
(edit `CANONICAL` in index.html if the repo name differs).

**itch.io:** new project → Kind: HTML → upload a zip of `index.html` →
"played in the browser" → viewport ~1080×920, fullscreen + mobile friendly
→ pricing "$0 or donate". Embed scrolling is already handled. Tags:
pinball, arcade, pachinko, plinko, idle, high-score, one-button.

**AI disclosure:** answer YES, same reasoning as Smallfolk — nothing
generates at runtime, but the code was built in a human–AI collaboration,
disclosed plainly.

## Roadmap candidates

- **Harvest words (v2, the stress layer):** mid-drop keyboard panics —
  "type CIDER before the golden apple lands to double it." Mouse aims,
  keyboard sweats. (Dave's mouse↔keyboard juggling idea; could also
  become its own game.)
- Sound polish, combo meter for multi-bumper ricochets, weekly board,
  local top-10 per board, flippers as a late unlockable if the feel holds.
