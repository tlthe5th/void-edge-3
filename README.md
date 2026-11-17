# Void Edge Chronicles 3.0 & Bumper Pool — Tabletop Edition

**Created by Thomas Richards**  
Licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**

A single-file, zero-dependency HTML5 Canvas physics tabletop game featuring two complete competitive modes on an interactive custom-rendered table: **Void Edge Chronicles 3.0** (a 5-tier gravity-funnel strategy duel) and **Classic Bumper Pool** (with simultaneous count-of-3 opening bank breaks, tight pockets, and bumper-carom AI).

---

## Live Links & Official Rulebooks

* **Play Online / Live Demo:** https://tlthe5th.github.io/void-edge-3/
* **Official Void Edge Rulebook:** https://spirituallysmart.blogspot.com/2026/08/void-edge-minigame-by-thomas-richards.html
* **Official Bumper Pool Rules Reference:** https://www.gametablesonline.com/bumper-pool-tables/rules.html
* **Creator Hub:** https://spirituallysmart.com

---

## Game Modes

### 1. Void Edge Chronicles 3.0 (Square 660×660 Gravity Arena)
* **Initiative Coin Toss:** Win the toss to choose between **Attack First (Corner Gambit)** or **Defer (Counter Anchor)**.
* **Escalating 5-Tier Marble Roster (10-Shot Match):** Each team drafts five marbles in ascending point order from their exterior tray:
  1. **White Scout** — `1 pt`
  2. **Yellow Skirmisher** — `2 pts`
  3. **Red Vanguard** — `3 pts`
  4. **Green Enforcer** — `5 pts`
  5. **Cyan Heavy Diamond** — `10 pts`
* **Gravity Funnel & Touch Rule:** Knock opponent marbles down the sloped metallic ramp into the central Void abyss to score their point value. Unforced self-drops award `0 pts`.
* **Sudden Death:** Tied matches enter Sudden Death with `10 pt` Cyan Heavy Diamonds until one player knocks the rival's Diamond into the Void.

### 2. Classic Bumper Pool (Rectangular 820×540 12-Bumper Table)
* **Simultaneous 3-2-1 Opening Bank Break:** Both players bank their marked cue ball off a side cushion toward their target pocket on the count of 3.
  * **One Player Sinks / Closest to Goal:** All balls stay exactly where they stop, and the winner takes the next shot with the next ball in line.
  * **Simultaneous Tie Shootout:** If both players sink their ball at the same time on 3, each spots their next ball in line (starting to the right of the opponent's goal) and shoots simultaneously on 3 again until one misses.
* **Tight Cup & Rim Lip-Out Physics:** Pocket cups (`14.8px` radius vs `14px` balls) require clean speed and angle control; overly hard or off-center shots swirl around the rim and lip out.
* **Marked Cue Ball Priority & Official Penalties:**
  * You must sink your marked cue ball before pocketing any of your remaining four balls.
  * Sinking another ball early, or dropping your own ball into your own cup, awards your opponent **2 free pocketed balls** dropped straight into their goal.
  * Sinking your final ball into the wrong cup results in an immediate forfeit.

---

## Key Features

* **Bumper-Carom & Multi-Ball Physics AI:** Four selectable rivals (**Kael the Drifter**, **Lyra of the Rim**, **Vespera**, and **The Void Architect**) capable of simulating multi-ball collisions, rail mirror-banks, and grazing caroms off all 12 rubber bumper posts.
* **Single Game & Best-of-3 Series:** Play quick single matches, Best-of-3 tournament series, or 2-Player Local Pass & Play.
* **Void Cam Slow-Motion Replay:** High-value eliminations (`5pt+` marbles or marked cue balls) trigger an automatic slow-motion replay.
* **Table & Funnel Armory:** Earn **Void Shards (`◆`)** from matches to unlock custom felt and cabinet finishes (*Royal Violet & Chrome*, *Obsidian & Brushed Gold*, *Tournament Emerald & Steel*, and *Crimson Velvet & Titanium*).
* **Web Audio Synthesizer & Jukebox:** Procedural collision clacks, pit drops, countdown tones, and a 4-track built-in chiptune/classical jukebox—zero external audio files required.

---

## Quick Start

No build step, server, or external packages are required:

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/tlthe5th/void-edge-3.git](https://github.com/tlthe5th/void-edge-3.git)
