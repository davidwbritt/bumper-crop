# Bumper Crop — itch.io setup, paste-ready

Same drill as Smallfolk. One ordering note first: the in-game **Share**
button copies links to `https://davidwbritt.github.io/bumper-crop/` — so
either create the GitHub repo + Pages **before** publishing on itch, or
tell Claude to point `CANONICAL` at the itch URL instead.

## Creating the project (Dashboard → "Create new project")

| Field | Value |
|---|---|
| Title | Bumper Crop |
| Project URL | bumper-crop |
| Short description | A penny-arcade orchard machine: drop apples, work the paddle, spell CROP, mind the TILT. Free, offline, no accounts. |
| Classification | **Games** |
| Kind of project | **HTML** (played in the browser) |
| Release status | Released |
| Pricing | **$0 or donate** (pay-what-you-want, no minimum) |
| Uploads | `bumper-crop-web.zip` — check **"This file will be played in the browser"** |
| Embed options | Viewport **1080 × 920**; check **Fullscreen button** and **Mobile friendly** (embed scrolling is already handled in-code) |
| Cover image | `cover-630x500.png` |
| Screenshots | `shot1-cabinet.png` (re-shoot later with themes/features if you like) |
| Genre | Action (closest itch offers to Arcade) |
| Tags | pinball, pachinko, plinko, arcade, physics, high-score, casual, score-attack |
| **AI disclosure** | **YES** — "contains the output of generative AI." Nothing generates at runtime; the code was built in a disclosed human–AI collaboration. Same honest posture as Smallfolk. |
| Community | Comments enabled |

## Description (paste into the big text box)

---

**Drop apples. Ring bumpers. Don't TILT.**

Bumper Crop is a penny-arcade orchard machine: aim your drop, then steer
the paddle to bounce each apple toward the basket you want — the baskets
multiply an apple's whole haul, ×1 to ×10. **Space hops the paddle** for
a proper volley when a catch is worth fighting for.

**Real pinball furniture, miniaturized:**

- **Pop bumpers** that kick like they mean it (round — or square, with
  honest square physics, from the Tinker's Hatch)
- **Rollover lanes** that spell **C·R·O·P** — complete the word to arm
  the **kickback**, which fires balls back out of the lousy ×1 baskets
- A **drop-target bank**: flatten all three for a coin burst — and a
  **prism peg** appears, a rainbow pin that births a new ball each time
  it's struck. Multiball is earned, not given
- **NUDGE** — physically shove the machine. Three too fast and she
  **TILTs**: locked hopper, dead bumpers, blinking red letters, exactly
  as tradition demands

**Spend your coins at the Back Counter:** bigger hopper, faster apples,
louder bumpers, golden pippins (×5), twin windfalls, a wider plank.

**Every board is an address.** The URL hash is the peg layout —
`#orchard-fair-42` is the same board for everyone, forever. **Daily
board** gives the whole world one shared layout per day; find the lane
that feeds the ×10 and tell your friends they're wrong about theirs.

Free, offline, one HTML file, no accounts, no ads. Sound is a tiny
built-in synth. Your coins and upgrades save in your browser; the
Tinker's Hatch has paint schemes, a paddle-feel slider, and a
"sell the machine" fresh start.

*(No AI runs in the game — deterministic physics and honest tables. The
code was built in an open human–AI collaboration; the AI disclosure on
this page is checked on purpose.)*

---

## After publishing

1. Visibility → **Public**
2. Play a few boards in the itch player: drop, paddle, buy an upgrade,
   spell CROP, trigger a TILT, and confirm the page scrolls
3. Tell Claude the final URL — it goes in the arcade memory, and
   cross-promo links between Smallfolk and Bumper Crop can be added
   to both pages' footers
