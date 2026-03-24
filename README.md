# QC Weight Tools

A mobile-optimized web app for pharmaceutical manufacturing QC weight calculations. Designed for use on iPhone as a home screen app during batch record execution.

**Live app:** [seeholmes.github.io/scale](https://seeholmes.github.io/scale/)

---

## Features

### Bottle Weight Tab
- 10-bottle weight entry in a 2-column layout (bottles 1–5 left, 6–10 right)
- Mean, sample standard deviation (n−1), and CV%
- Precision toggle: ±0.1 or ±0.01
- Fill target calculator with specific gravity → net and gross targets
- Gross targets use display-precision rounding to match batch record math
- Keyboard navigation (Enter advances sequentially, arrow keys navigate directionally)

### Component Weight Tab
- 6 component rows (C1–C6), 3 sample weights each
- Auto-calculated row averages and column sums
- Rows with no data are ignored
- Minimum weight calculation: `Avg of Totals − (0.5 × lightest component avg)`

### General
- Light / dark theme toggle with persistence
- iOS home screen ready (standalone web app)

---

## Installation (iPhone)

1. Open [seeholmes.github.io/scale](https://seeholmes.github.io/scale/) in **Safari**
2. Tap the **Share** button
3. Tap **"Add to Home Screen"**
4. Tap **Add**

---

## Release Notes

### v1.10 — 2026-03-24
- Added Component Weight tab
- 6 component rows, 3 samples each with auto averages and column sums
- Minimum weight calculation with live formula display
- Two-tab interface (Bottle Wt / Component Wt / About)
- App renamed to QC Weight Tools

### v1.00 — 2026-03-23
- Initial release
- 10-bottle weight entry with 2-column layout
- Mean, sample SD (n−1), CV%
- Fill target calculator with specific gravity
- Net & gross targets with display-precision rounding
- Light / dark theme with localStorage persistence
- Keyboard navigation
- iOS home screen support

---

*Single-file HTML app — no build tools, no dependencies, no login.*
