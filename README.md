# ASTRIX: Saudi Analogs

**NASA Space Apps Challenge 2026 (Tabuk)** · Challenge: *Identify Earth Locations that Analog the Permanent Moon Base Locations and Mars*

**Live site:** https://reema-albalawi.github.io/astrix-saudi-analogs/

## Summary
ASTRIX maps ten Saudi landscapes that resemble lunar and Martian terrain. Five are known analogs documented in NASA sources, and five are new candidates our team identified. Each site is linked to the engineering problems past missions faced, such as dust on solar panels, wheels stuck in soft soil, sharp rocks and freezing nights. A planner then suggests Saudi sites and seasons for testing space systems before launch.

## Features (prototype)
- 3D terrain tour of all 10 sites, viewable as Earth, Moon or Mars, with orbit, walk and rover-drive modes
- Compare split view: the same ground on Earth beside the Moon or Mars
- Sun slider with shadow coverage, including lunar south-pole lighting (Sun 1.5° above the horizon)
- Rover routes with length and slope ratings; WebXR "Enter VR" on supported headsets
- Mission replay (Opportunity, InSight, Spirit, Curiosity) ending in a recommended Saudi test site
- Satellite map, site cards with NASA climate data, similarity estimates and analog limits
- Weighted engineering readiness score and a test scenario planner

## Sites
| # | Site | Type | Lat, Lon | Counterpart | Similarity* |
|---|------|------|----------|-------------|-----------|
| 1 | Al Wahbah Crater | Known | 22.9090, 41.1440 | Shackleton / Copernicus (Moon) | 92% |
| 2 | Harrat Khaybar | Known | 25.5000, 39.9000 | Tharsis volcanics (Mars), lunar basalt | 89% |
| 3 | Rub' al Khali | Known | 20.0000, 50.0000 | Meridiani Planum (Mars) | 94% |
| 4 | Harrat Rahat | Known | 23.0800, 39.7800 | Tharsis / Elysium (Mars) | 91% |
| 5 | Hisma Plateau | Known | 28.7500, 35.8000 | Valles Marineris, Gale crater (Mars) | 95% |
| 6 | Dahl Hith | New | 24.4847, 46.9994 | Arsia Mons collapse pits (Mars) | 88% |
| 7 | As-Summan Dahls | New | 26.5000, 47.5000 | Marius Hills skylights (Moon) | 93% |
| 8 | Umm Jirsan Cave | New | 25.5881, 39.7575 | Lunar / Martian lava tubes | 96% |
| 9 | Edge of the World (Tuwaiq) | New | 24.9450, 45.9910 | Shackleton rim (Moon), Martian canyons | 87% |
| 10 | Wadi As-Sirhan Basin | New | 30.5000, 38.0000 | Jezero crater (Mars) | 90% |

\*Team estimate from published comparisons. Rounded coordinates mark an approximate centre of a large area.

## Readiness formula
`Score = Σ(criterion_i × weight_i) / Σ(weight_i)`, over criteria with available data. Each criterion is scaled 0–100.

## Status
Prototype. Readiness scores are sample values until the team's measurements are final. 3D terrain is procedural, shaped from published descriptions, and will be replaced with NASADEM elevation data.

## Run
Open `index.html` in a browser, or visit the live site.

## References (NASA)
1. NASA Science Planetary Analogs Portal
2. Planetary Analog Explorer (side-by-side Earth and Moon/Mars comparisons)
3. NASADEM & SRTM Digital Elevation Data
4. NASA Earth Observatory: White and Black Volcanoes of Saudi Arabia
5. NASA Earth Observatory: Harrat Khaybar Volcanic Field
6. NTRS: Rub' al Khali Interdune Sabkha Analog for Present Mars
7. NASA Technical Reports Server (NTRS): Planetary Caves & Exploration Analogs

Satellite imagery: Esri, Maxar, Earthstar Geographics. 3D: three.js. Map: Leaflet.

## Team
Team ASTRIX: six students.
