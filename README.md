> **Portfolio showcase** — the complete implementation is kept private to protect intellectual property. This public repository intentionally contains documentation only. A live demo or private code review can be provided for a serious project discussion.

# Sleeper Garage

Browser-based drag-racing game prototype focused on realistic tuning, reaction time and sleeper builds.

## Highlights
- deterministic race simulation separated from rendering
- Phaser 3 + TypeScript frontend
- live synthesized engine audio
- automated physics regression tests
- Vite build pipeline
- mobile-oriented game loop designed for later Capacitor packaging

src/sim contains pure race simulation logic. Rendering and interaction are kept separately so physics can be tested without a browser.

## Run
- npm install
- npm test
- npm run dev
- npm run build

Portfolio snapshot of an actively developed game project.

## Usage and licensing

This repository is source-available for portfolio evaluation. You may inspect the code and run an unmodified local copy for evaluation, but commercial use, redistribution, republishing and derivative distribution are not permitted without written permission. See [LICENSE.md](LICENSE.md).

