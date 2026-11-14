# ASTRIX: Saudi Analogs

**NASA Space Apps Challenge 2026 (Tabuk)** · Challenge: *Identify Earth Locations that Analog the Permanent Moon Base Locations and Mars*

**Live site:** https://reema-albalawi.github.io/astrix-saudi-analogs/

## Summary
ASTRIX maps Saudi sites that serve as analogs for the Moon and Mars, using only published evidence. Each site shows its evidence grade, the values researchers measured, the instruments they used and what was not proven. Sites are linked to engineering problems past missions faced, such as dust on solar panels, wheels stuck in soft soil and sharp rocks, and a planner suggests where to test space systems before launch.

## Features (prototype)
- Find a test site: choose the mission destination, terrain and test, and get ranked Saudi sites with their evidence
- NASA GIBS map layers: VIIRS SNPP true colour, MODIS Terra daytime land surface temperature and ASTER GDEM shaded relief (no API key needed)
- Real 3D terrain for each site from SRTM elevation (AWS Terrain Tiles) with Esri satellite imagery draped on top
- Guided headset preview: stand on the rim of Al Wahbah, then see the same view lit like the lunar south pole; phone motion to look around; WebXR "Enter VR" on supported headsets
- 3D terrain for 10 land sites, viewable as Earth, Moon or Mars, with orbit, walk and rover-drive modes, rover routes and slope ratings
- Compare split view and a Sun slider with shadow coverage
- Mission replay (Opportunity, InSight, Spirit, Curiosity) ending in a recommended Saudi test site
- Satellite map with evidence grades, published measurements, limits and linked sources
- Weighted engineering readiness score (sample values) and a test scenario planner

## Evidence approach
- Every value comes from a cited study (see the References page of the live site).
- No similarity percentages are calculated.
- Lab temperatures, deep-water temperatures and air temperatures are labelled separately.
- Volcanic-field coordinates are field centres, not sample points. Sites without a published point get no map pin.
- Evidence grades: **A** direct analog study · **B** field or geological study · **C** supporting measurements.

## Sites
| Site | Grade | Lat, Lon | Published analog / relevance |
|------|-------|----------|------------------------------|
| Al Wahbah Crater | A | 22.90632, 41.13849 | Enceladus ocean chemistry [S01] |
| Eastern Province Sands | A | no published point | Martian regolith simulant [S04] |
| Wabar Craters, Rub' al Khali | B | 21.503427, 50.472181 | Impact craters [S05] |
| Umm Jirsan Cave | B | 25.5888, 39.757 | Lunar/Martian lava tubes [S08] |
| Harrat Khaybar | B | 25.5, 40.0 (field centre) | Basaltic volcanic terrain [S10] |
| Northern Harrat Rahat | B | 23.08, 39.78 (field centre) | Basalt lava fields [S12] |
| Saudi Sabkhas and Deserts | C | nine sites, no single point | Salinity and dryness for Mars [S20] |

**Candidates (need verification):** Hisma Plateau, Dahl Hith, As-Summan Dahls, Edge of the World (Tuwaiq), Wadi As-Sirhan Basin.

## Readiness formula
`Score = Σ(criterion_i × weight_i) / Σ(weight_i)`, over criteria with available data. Each criterion is scaled 0–100.

## Status
Prototype. Readiness scores are sample values. 3D terrain uses real SRTM elevation and satellite imagery on the live site; an illustrated model is shown where those cannot load. Test seasons are indicative until checked against NASA POWER records.

## Run
Open `index.html` in a browser, or visit the live site.

## References
See the References section of the live site for full citations and links . NASA data used on the site: GIBS (VIIRS, MODIS LST, ASTER GDEM) and SRTM elevation. NASA data for the next comparison step: Moon Trek, Mars Trek, Earthdata Search, NASA POWER, NASADEM / SRTM, LRO Diviner, HiRISE.

Satellite imagery: Esri, Maxar, Earthstar Geographics. 3D: three.js. Map: Leaflet.

## Team
Team ASTRIX: six students.
