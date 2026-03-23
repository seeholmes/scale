BOTTLE WEIGHT STATISTICS — RELEASE NOTES
=========================================

v1.00  (2026-03-23)
-------------------
Initial release.

Features:
  - 10-bottle weight entry with 2-column layout (bottles 1-5 left, 6-10 right)
  - Mean, sample standard deviation (n-1), and CV% statistics
  - SD reported at 0.001 precision; CV% at 0.01 precision
  - Mean reported at selected precision
  - Precision toggle: ±0.1 or ±0.01 input steps
  - Fill target calculator:
      - Inputs: Specific gravity, Low / Target / High nominal net weights
      - Calculates actual net targets (nominal × SG)
      - Calculates gross targets (rounded net + rounded mean bottle weight)
      - Gross uses display-precision rounding to match batch record math
  - Light / dark theme toggle with localStorage persistence
  - Keyboard navigation:
      - Enter key: sequential advance (1→2→3...10)
      - Arrow Up/Down: move within column
      - Arrow Left/Right: jump to same row in opposite column
  - iOS home screen ready (apple-touch-icon, standalone web app meta tags)
  - Hosted at: https://seeholmes.github.io/scale/

=========================================
