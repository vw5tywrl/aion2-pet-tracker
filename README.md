# Aion 2 Pet Tracker

Web-based pet catalog, spawn map, and collection tracker for Aion 2.

Live site: https://vw5tywrl.github.io/aion2-pet-tracker/

## Features

- **Persistent Collection** — Collected pets are saved locally in browser `localStorage`, keeping your progress after refreshing or closing the tab. Includes live completion counters and a **Hide Collected** toggle to focus on missing pets.
- **Search by Zone** — Interactive map explorer covering 68 sub-zones across Verteron, Altgard, and the Abyss. Selecting a zone on the map or from the dropdown lists every pet-dropping monster in that territory, plots their spawn points, and lets you mark pets collected directly from the side panel.
- **Monster Spawn Maps** — Clicking any open-world pet opens a pan-and-zoom map with exact monster spawn pins, per-monster level filters, pin tooltips, and direct QuestLog NPC links.
- **Region & Exclusive Views** — Separate tabs for **Black Cloud / Chest** (non-world-spawn pets), **Verteron (Elyos)**, **Altgard (Asmodian)**, **Abyss (Reshanta)**, and **All Regular Pets** (200 total), plus a contextual **Only Exclusives** toggle on region tabs to isolate region-locked drops.
- **Genus & Text Filtering** — Filter by Genus stat category (`Cogni · HP/Crit`, `Fera · Speed/Acc`, `Natura · Stamina`, `Varian · Sprint/Eva`) and search by pet name, monster name, or zone.
- **URL State & History** — Active tabs, filters, selected zones, and open pet maps sync to URL parameters so views can be bookmarked/shared and navigated with browser Back/Forward buttons.

## Run locally

```bash
git clone https://github.com/vw5tywrl/aion2-pet-tracker.git
cd aion2-pet-tracker
python -m http.server 8080
```

Open `http://localhost:8080` in a browser. No build steps or dependencies required.

## License

[MIT](LICENSE)
