# Rock Climbing Simulator

An interactive rock climbing technique guide with a physics-based simulator.

Open `index.html` in a browser, or view it live via GitHub Pages.

## The simulator

A little climber on a bouldering wall, driven by a Verlet physics model:

- **Grip and stand** — drag his hands onto holds to grip and stand his feet on holds.
- **Set a stance** — drag his hips to a position; the hips hold that stance, so standing
  taller raises his shoulders and extends his reach.
- **Reach** — dragging a hand toward a far hold leans the whole body to extend as far as
  the feet and other hand allow. Limbs are a fixed length, so a hold out of reach stays
  out of reach.
- **Per-arm strain** — the panel shows how hard each arm is working. Lean off-balance or
  hang from one arm and its strain climbs past the limit.
- **Fatigue** — hold an arm over its limit for five seconds and it gives out; the climber
  falls off the wall. A flashing warning counts down 5 → 1 before he does.
- **Slipping feet** — reach too far off a foot and it slips off its hold.

Fully keyboard-accessible (focus the wall, use the arrow keys), theme-aware (light/dark),
and respects `prefers-reduced-motion`.

## Built with

A single self-contained HTML file — no build step, no dependencies.
