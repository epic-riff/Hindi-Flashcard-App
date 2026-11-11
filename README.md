# Hindi Path — CEFR Vocabulary (prototype)

## Included
- iPhone-first responsive web app / PWA shell
- A1–C2 level browsing
- Hindi Devanagari-only card fronts
- English meanings, grammar notes, usage guidance, examples and register labels
- Hindi speech synthesis via the browser/device `hi-IN` voice when available
- Local spaced-review scheduling (Again / Hard / Good / Easy)
- Vocabulary search, multiple-choice quizzes, progress statistics
- Local progress persistence and JSON export/import
- Service worker for basic offline app-shell caching

## Important content limitation
This first working prototype contains 20 curated starter cards per level (120 total), not 100+ per level. CEFR alignment for Hindi is an adapted editorial classification, not an official standardized Hindi CEFR list. The app structure is ready for a larger, carefully reviewed vocabulary corpus. Do not treat the current deck as a complete CEFR syllabus.

Some grammar notes are introductory. Hindi agreement and verb paradigms are context-sensitive; advanced verb tables and richer listening exercises are planned for the next content pass.

## Run locally
Open `index.html` in a browser for a basic preview. PWA installation and service-worker offline caching require HTTPS hosting (or localhost).

## Install on iPhone
1. Host the folder on an HTTPS static host (for example GitHub Pages, Netlify, or another static web host).
2. Open the hosted URL in Safari.
3. Tap Share → Add to Home Screen.
4. Launch Hindi Path from the Home Screen.

## Data
Review progress is stored in localStorage on that browser/device. Use Progress → Export backup before clearing browser data or changing devices.
