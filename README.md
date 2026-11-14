# ASTRIX: Saudi Analogs

**NASA Space Apps Challenge 2026** · Challenge: *Identify Earth Locations that Analog the Permanent Moon Base Locations and Mars*

## Summary
ASTRIX finds Saudi landscapes (craters, sinkholes, lava tubes, volcanic fields and dune fields) that resemble lunar and Martian terrain. It links each site to engineering problems past missions faced, such as dust on solar panels, wheels stuck in soft soil and cold nights. A planner then suggests Saudi sites and seasons for testing space systems before launch.

## Features (prototype)
- 3D terrain tour of each site, viewable as Earth, Moon or Mars, with orbit and walk modes and a dust-storm toggle
- Map and data cards for candidate sites. Missing values are shown as *pending*, never guessed
- Weighted engineering readiness score with adjustable weights and data coverage
- Test scenario planner: system + environmental factors → sites + test window

## Run
Open `index.html` in a browser, or visit the GitHub Pages link.

## NASA data (planned / in use)
NASADEM, SRTM, MODIS LST, MERRA-2, NASA POWER, LRO Diviner, Moon Trek, Mars Trek, HiRISE.

## Readiness formula
`Score = Σ(criterion_i × weight_i) / Σ(weight_i)`, over criteria with available data. Each criterion is scaled 0–100.

## Status
Prototype. Site values and scores are placeholders until the team's measurements are finalised. 3D terrain is procedural, shaped from published dimensions, and will be replaced with NASADEM elevation data.

## Team
Team ASTRIX: six students.
