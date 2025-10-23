# Racing HUD + Lap Replay (CSS-only v7)

**No JavaScript.** Flags behave as requested within CSS limits:
- **Green**: car runs at the speed bar setting.
- **Yellow**: mild slowdown (1.2× duration) with a **very small jump** (unavoidable in pure CSS).
- **Red**: car stops exactly where it is (paused).
- Default is **Red**, so nothing moves until Green.

Car follows the track via CSS **offset-path** (matches the SVG). Includes speedometer needle tied to speed bar, rain overlay, pit panels, splits panel, and a one-lap ghost replay.

Open `index.html` in a modern browser.
