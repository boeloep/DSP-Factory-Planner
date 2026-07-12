<div align="center">
  <img src="assets/logo.svg" width="72" height="72" alt="Dyson Sphere Program Factory Planner logo">

  # Dyson Sphere Program Factory Planner

  Pick a target item and rate. Get the full production chain — machines, belts, sorters, power — instantly.

  <img src="assets/banner.png" alt="Dyson Sphere Program Factory Planner banner" width="100%">

  <a href="https://dspfactoryplanner.com/" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Open%20the%20planner-22d3ee?style=for-the-badge&logo=googlechrome&logoColor=060c14" alt="Open the planner">
  </a>
</div>

<br>

<div align="center">
  <img src="assets/screenshot.png" alt="Planner screenshot showing a populated production plan" width="100%">
  <sub>A populated plan: target rate, full production tree, machine counts, and power draw, all in one screen.</sub>
</div>

## Features

<table>
<tr>
<td width="64"><img src="assets/icons/electromagnetic-matrix.png" width="40" height="40" alt=""></td>
<td><b>Target picker with per-minute rates</b><br>Search or browse items, set an exact rate, plan several targets at once.</td>
</tr>
<tr>
<td><img src="assets/icons/processor.png" width="40" height="40" alt=""></td>
<td><b>Full production tree</b><br>Every intermediate step down to raw resources, with exact and rounded-up (ceiling) machine counts, plus belts and sorters.</td>
</tr>
<tr>
<td><img src="assets/icons/circuit-board.png" width="40" height="40" alt=""></td>
<td><b>Recipe alternatives &amp; per-step overrides</b><br>Swap alternate recipes and machine tiers anywhere in the tree without recomputing everything by hand.</td>
</tr>
<tr>
<td><img src="assets/icons/proliferator-3.png" width="40" height="40" alt=""></td>
<td><b>Proliferator planning</b><br>Model speedup vs. extra-product spraying, including the proliferator spray cost itself.</td>
</tr>
<tr>
<td><img src="assets/icons/iron-ingot.png" width="40" height="40" alt=""></td>
<td><b>Power totals</b><br>Live power draw for the whole plan as you tune it.</td>
</tr>
<tr>
<td><img src="assets/icons/sorter-3.png" width="40" height="40" alt=""></td>
<td><b>Shareable plan links</b><br>Every plan is encoded into the URL — send a link, not a screenshot.</td>
</tr>
</table>

Works fully offline once loaded, no account, no install — it's a single HTML file.

## Known limitations

- Power totals are **work power only** — idle/standby drain isn't modeled.
- Fractionator deuterium is treated as a raw import, not derived from hydrogen fractionation.
- Built against game version **0.10.29.21950**; later game updates may shift recipes or numbers.

## Feedback

Found a bug or have a suggestion? [Open an issue](https://github.com/boeloep/DSP-Factory-Planner/issues).

---

<sub>Unofficial fan-made tool — not affiliated with or endorsed by Youthcat Studio or Gamera Games.</sub>
