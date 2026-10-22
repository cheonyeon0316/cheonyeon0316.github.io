# Jelly Dash UI assets

These files are independent transparent SVG assets for the game HUD. Use them directly from HTML/CSS; the HUD keeps changing numbers and labels as DOM text so localization and score updates remain easy.

| Asset | Use |
| --- | --- |
| `jelly-dash-wordmark.svg` | Game title wordmark above the playfield |
| `hud-panel.svg` | Reusable glassy backing for score, jelly, and charge panels |
| `pause-button.svg` | Pause control artwork |
| `jump-icon.svg` | Jump control hint |
| `slide-icon.svg` | Slide control hint |
| `blast-icon.svg` | Attack/charge indicator and attack hint |

The current game page uses these assets from `index.html`. HUD text and the seven charge pips remain live HTML, while the SVGs provide scalable artwork with no embedded gameplay values.
