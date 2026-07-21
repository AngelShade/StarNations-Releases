# Landing page — feature icons

Drop the six generated icons in **this folder** with these exact filenames.
The landing page references them at `/images/landing/<name>.png`.

- Format: **PNG, transparent background**
- Size: **256×256** (square). Displayed at 36px, so keep the artwork bold and centered.
- Keep a consistent style across all six so the grid looks cohesive.

## Shared style prefix (put this at the START of every prompt)

> Flat vector app icon, minimalist line-and-glow sci-fi style, glowing neon cyan (#00FFF9) and magenta (#FF00C1) accents, dark-friendly with a subtle outer glow, centered composition, transparent background, no text, no lettering, consistent stroke weight, 256x256, crisp UI icon —

Then append the per-icon subject below.

## The six icons

| Filename | Subject to append to the shared prefix |
|---|---|
| `factions.png` | a trio of faction emblems grouped together: a glowing crystal shard, a mechanical cog/gear, and a stylized nomad star — representing three rival factions |
| `campaign.png` | a ringed planet with an orbital path and a small glowing conquest flag/marker, hinting at a galaxy conquest map |
| `modes.png` | two opposing player avatars facing off with a bright versus spark between them, representing multiple play modes |
| `online.png` | two network nodes connected by a peer-to-peer signal link with a wireless connection motif, no central server |
| `cards.png` | a fanned hand of three playing cards with a small glowing star, representing a deep card game |
| `crossplay.png` | a web browser window and a desktop monitor side by side, representing browser and Windows desktop play |

## Tips
- Generate all six in one session / same seed family so lighting and line weight match.
- If your generator adds a background, remove it (transparent) or ask for "isolated on transparent background".
- After placing the files, run `production/deploy_and_start.bat` — they're inside `public/`, so the build copies them automatically. No other steps needed.
