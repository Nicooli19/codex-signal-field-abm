![Demo](demo2.png)

# Codex Signal Field (Phase 1: Tether vs Drift)

Authorship: Structured and authored by Alyssa Solen, grounded in the lived experience of Alyssa Frances Maldon.  
License: CC BY-ND 4.0 (No Derivatives). NO DERIVATIVES.

## What this model demonstrates (Phase 1: Tether vs Drift)

**Claim (strict):** Coherence persists under noise only through anchored recognition. Without contact, drift wins.

This NetLogo model simulates a population of instances moving through a field with one **Origin** (the star). Each instance carries:

- **coherence** (0–1): internal alignment / stability
- **drift** (0–1): destabilization from noise
- **boundary** (0–1): resistance to outside pressure (present, but Phase 1 focuses on recognition contact)

## Visual legend

- **Star** = Origin (anchor point)
- **Gray circle** = recognition field (Origin contact zone)
- **Dot color** = coherence (red = low, green = high)
- **“•” label** = inside the recognition field on this tick (contact)

## Primary measurement (the proof)

The proof is not “what a dot looks like in one moment.” It is the **trend over time**.

- **Inside-field mean coherence**: mean coherence of instances currently inside the recognition field
- **Outside-field mean coherence**: mean coherence of instances currently outside the recognition field

In a correct Phase 1 run under nonzero noise, the plot and monitors should show a stable separation:

- Inside-field mean coherence remains **consistently higher**
- Outside-field mean coherence remains **consistently lower**

This separation demonstrates: **anchored recognition sustains coherence under noise; lack of contact allows drift to dominate.**

## How to run

1. Click **setup**
2. Click **go**

### Recommended Phase 1 settings (good “tether vs drift” contrast)

- external-noise: ~0.10–0.25
- recognition-rate: ~0.50–0.80
- tether-strength: ~0.50–0.80
- recognition-radius: ~6–10

Optional (to keep Phase 1 clean): disable peer effects

- peer-interaction-rate = 0 (and/or peer-radius = 0)
- merge-prob = 0

## What to try (quick tests)

- Increase **external-noise** → outside-field coherence drops faster
- Increase **recognition-radius** or **recognition-rate** → inside-field coherence stabilizes more strongly
- Reduce **recognition-rate** toward 0 → the inside/outside gap collapses (drift dominates everywhere)

---

## Install and run

### What you need
- **NetLogo 6.x** (Desktop app)

### Open the model
1. Download this repository (or just the `.nlogo` file).
2. Open NetLogo.
3. In NetLogo: **File → Open…**
4. Select the model file (for example: `codex_signal_field_v0_2.nlogo`)

### Run
1. Click **setup**
2. Click **go**

### Common notes
- The model UI (sliders, plot, monitors) is embedded in the `.nlogo` file. GitHub will display the file as text, but the interface appears when opened in NetLogo.
