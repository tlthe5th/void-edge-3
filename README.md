# Void Edge Chronicles 3.0

**The Abyss Championship — Realistic Tabletop Edition**  
*Created by Thomas Richards*

**Void Edge Chronicles 3.0** is a self-contained, browser-based physics tabletop strategy game built with vanilla HTML5 Canvas, CSS3, and the Web Audio API. Combining billiards-style bank angles with a central gravitational funnel, players draft escalating tiers of marbles to outmaneuver rivals and knock opposing pieces into the Void.

---

## 🎮 Play Now

* **Live Game:** [Play Void Edge Chronicles 3.0](https://tlthe5th.github.io/void-edge/) *(update URL if hosted in a dedicated 3.0 repository)*
* **Official Rulebook & Lore:** [SpirituallySmart.com](https://spirituallysmart.blogspot.com/2026/08/void-edge-minigame-by-thomas-richards.html)

---

## ✨ What's New in 3.0

* **Realistic 3D-Shaded Tabletop Arena:** Features mitered outer rails, procedural woven felt texture, a 4-sided beveled metallic gravity funnel, exterior reserve marble trays, and side resting gutters for the tapered red-and-gold Void Cues.
* **Tactile Void Cue & Bounce Raycasting:** Dragging back draws a tapered cue stick behind your active marble, fills a 4-tier power meter (`TOUCH`, `SOFT`, `MEDIUM`, `HARD`), and projects a real-time collision and cushion bounce trajectory.
* **The Chronicles Campaign Ladder:** Challenge four distinct AI opponents—**Kael the Drifter**, **Lyra of the Rim**, **Vespera**, and **The Void Architect**—each powered by multi-marble physics lookahead simulations tailored to their tactical tier.
* **Void Cam Slow-Motion Replays:** Sinking high-value **5pt Green Enforcers** or **10pt Cyan Heavy Diamonds** automatically triggers a 0.35x slow-motion instant replay.
* **Void Shards & Table Armory:** Earn Void Shards from victories and style knockouts to unlock custom cabinet woods, felt cloths, and funnel metals (*Royal Violet & Chrome*, *Obsidian & Brushed Gold*, *Tournament Emerald & Steel*, and *Crimson Velvet & Titanium*), saved automatically via `localStorage`.
* **Chronicle Referee & Shot Log:** Real-time play-by-play commentary paired with an expandable match event log and built-in interactive Field Manual.
* **3-Track Procedural Jukebox:** Switch between *Void Chase*, *Abyss Drift*, and *Neon Duel* alongside velocity-scaled collision acoustics.

---

## 📜 Rules & Gameplay

1. **Initiative Coin Toss:** At the start of each match, the coin toss winner chooses to **Attack First (Corner Gambit)** or **Defer (Counter Anchor)**.
2. **Five-Tier Escalating Roster:** Teams alternate launching 5 marbles drafted from their exterior reserve trays:
   * **White Scout:** `1 pt`
   * **Yellow Skirmisher:** `2 pts`
   * **Red Vanguard:** `3 pts`
   * **Green Enforcer:** `5 pts`
   * **Cyan Heavy Diamond:** `10 pts`
3. **The Beveled Gravity Funnel:** Any marble rolling onto the 4-sided sloped ramp experiences continuous gravitational pull toward the central Void pit.
4. **Touch-Rule Scoring:**
   * Knocking an opponent's marble into the Void awards its point value to your team.
   * If your own marble drops into the Void *after* contacting an opponent's marble, your opponent scores its points.
   * Dropping your own untouched marble into the Void awards **0 points** (unforced fall).
5. **Sudden Death:** If the score is tied after all 10 shots, both teams deploy `10 pt` Cyan Heavy Diamonds for sudden-death knockout rounds until a winner is decided.

---

## 🚀 Installation & Self-Hosting

Void Edge Chronicles 3.0 requires **zero build tools, external libraries, or asset folders**:

1. Download or clone `index.html`.
2. Open `index.html` directly in any modern desktop or mobile browser, or deploy via **GitHub Pages**.

### Blog / Website Embed Snippet

```html
<div style="width: 100%; max-width: 640px; margin: 0 auto; text-align: center;">
  <iframe src="[https://tlthe5th.github.io/void-edge/](https://tlthe5th.github.io/void-edge/)" width="100%" height="880px" style="border: 2px solid #a855f7; border-radius: 12px; background: #06030e;" allowfullscreen="" loading="lazy"></iframe>
</div>
