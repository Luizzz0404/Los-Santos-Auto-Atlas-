# Los Santos Auto Atlas — playable prototype

Open **index.html** in a modern browser. No installation, account or server is required. Internet access is recommended for the actual GTA V map tiles; if they do not load, the app displays a clearly illustrative built-in fallback map.

## Included features
- 25 vehicle profiles, English real-world histories and GTA-character descriptions.
- Search, vehicle-class filters, availability and Exotic Exports filters, sort.
- Interactive GTA map with draggable / zoomable base map, selectable regions, regional heat overlays.
- Vehicle detail sidebar on desktop and expandable bottom drawer on mobile.
- Explicit no-freeroam-spawn notice for purchase-only/special-event vehicles.
- Two-car comparison with stats and compare-on-map overlays.
- Personal garage: Owned, Wishlist, Favorites, saved locally in the browser.
- Export/import garage JSON for moving collection between devices.
- In-game-style performance bar UI, with conspicuous disclaimers that the current numerical values are illustrative estimates, **not** official verified game data.

## Important limitations / transparency
- This is a **working 25-car first release**, not a completed all-vehicle encyclopedia. The data model and interface are structured to expand to the complete GTA Online roster.
- Vehicle images are original *stylized SVG illustrations*, not screenshots of the actual GTA models. This avoids falsely presenting mismatched or unlicensed imagery as authentic screenshots.
- Spawn heatmap areas are **editorial, approximate estimates**, not measured probabilities or verified spawn coordinates. The region geometry is approximate. GTA Online spawn conditions vary.
- Exotic Exports eligibility is distinct from ordinary ambient traffic. A purchase-only vehicle may still occur in an Exotic Exports event.
- Price values are historical/reference base prices where available; `Price not verified` is shown instead of fabricating a price.
- Actual GTA stat bars, verified tested top speed and lap times are not provided yet; the interface marks current bars as illustrative. Do not rely on them for purchasing decisions.
- Map tiles are served by `https://viruxe.github.io/gtav-map-tiles/` and remain the property of their respective rights holders. This is a personal, unofficial fan prototype; please review asset rights before public redistribution.
- The fallback map is schematic and not an accurate geographic reference.
- Browser `localStorage` may be unavailable for `file://` pages in some iPhone contexts. Export/import is included; static hosting (e.g. GitHub Pages) gives more reliable persistence and iPhone behavior without a dedicated server.

## Sources / research starting points
- Exotic Exports roster: https://gta.fandom.com/wiki/Exotic_Exports_(GTA_Online)/Vehicles
- Exotic Exports mechanics: https://gta.fandom.com/wiki/Exotic_Exports_(GTA_Online)
- Map tiles: https://github.com/VIRUXE/gtav-map-tiles
- GTA vehicle reference: https://www.gtabase.com/grand-theft-auto-v/vehicles/

## Development priorities for next iterations
1. Replace estimated stat bars with individually verified GTA Online stats and independently tested metrics.
2. Replace stylized illustrations with correctly licensed, verified vehicle photographs.
3. Add verified spawn observations and better calibrated map regions; never fabricate exact probability values.
4. Expand the database incrementally to all GTA Online vehicles, including motorcycles and non-freeroam vehicles.
5. Optionally make a locally bundled map and add pinch-to-zoom for improved offline/mobile operation.
