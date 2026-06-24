# ☀️ Ballistics & Zeroing

A self-contained, offline-capable ballistics and rifle-zeroing web app for the shooting range.

## Features

- **Zero / Sight-In calculator** — enter your group's offset at a known distance, get exact turret corrections (clicks UP/DOWN/LEFT/RIGHT).
- **Trajectory solver** — full G1 drag-model drop chart with elevation, retained velocity, and wind drift at every range.
- **Rifle profiles** — save up to 10 rifle/load profiles storing ballistics, scope adjustment (MIL/MOA), click value, and sight height. Selecting a profile auto-loads everything into the calculators.
- **Cartridge library** — 33 built-in cartridges (.22 LR through .50 BMG) with verified factory-load ballistics, plus searchable lookup and custom cartridge input.
- **Fully user-controlled units** — meters/yards and cm/inches toggles.
- **Works 100% offline** — a single HTML file, no internet or backend required. Runs entirely in the browser.

## Usage

Open the live site, or open `index.html` in any browser.

1. Go to the **Rifles** tab and create a profile (or use the Cartridges tab to look one up).
2. Select your rifle in the **Zero** or **Trajectory** tab.
3. Enter your data and calculate.

## Accuracy note

This tool uses a standard G1 drag model — accurate to field-usable tolerances and validated against published manufacturer data. **Always confirm true zero on paper.** No calculator replaces a confirmed dope card.

## Versions

- `index.html` — current release (V3)
- `index-v1.html`, `index-v2.html`, `index-v3.html` — version history

---

Built as a learning project. Forged with the help of Omnissiah. ☀️
