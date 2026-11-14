
# 30DayMapChallenge 2026

### Exploring Cities Through Cartography & Spatial Analytics

A collection of maps exploring urban environments through spatial data, geographic analysis, and creative cartographic design.

Each project explores a different theme, city, or mapping technique as part of the **30DayMapChallenge 2026**.

**Cartography & Design:** Alhaylam Fahad Alajmi  
**University of Pennsylvania | Master of Urban Spatial Analytics (MUSA)**

---

# PROJECT 01 | RIYADH, SAUDI ARABIA

## WHERE THE DESERT MEETS THE CITY

**THE RIYADH SPATIAL ATLAS**

*Day 09 — Urban–Rural*

### 01 | Project Overview

Riyadh's built environment exhibits substantial spatial variation, from compact urban districts to sparsely developed areas near the desert fringe.

**Research Question**

How does building footprint coverage differ across selected urban conditions in Riyadh?

### 02 | The Final Atlas

![Where the Desert Meets the City](maps/day09_urban_rural/WHERE_THE_DESERT_MEETS_THE_CITY_FINAL.png)

[View the high-resolution atlas (PDF)](maps/day09_urban_rural/WHERE_THE_DESERT_MEETS_THE_CITY_FINAL.pdf)

### 03 | Key Findings

| Urban Condition | Building Coverage | Building Features |
|:----------------|------------------:|------------------:|
| Compact | 25.1% | 2,374 |
| Intermediate | 8.4% | 1,553 |
| Sparse | 1.0% | 666 |

### 04 | Spatial Methodology

**Study area:** 60 × 60 km analytical window in Riyadh.

**Coordinate system:** EPSG:32638.

**Comparison windows:** Three equally sized 2.5 × 2.5 km samples.

**Building coverage calculation:**

Building Coverage (%) = Building Footprint Area / Window Area × 100

### 05 | Data Sources

- Microsoft Global ML Building Footprints
- © OpenStreetMap contributors

---

# PROJECT 02 | PARIS, FRANCE

## LA CARTE INFINIE — PARIS

**THE INFINITE MAP**

*Day 14 — Borgesian Map*

*One city, infinite scales. / Une ville, mille échelles.*

### 01 | Project Overview

La Carte Infinie explores Paris through multiple levels of geographic detail.

Inspired by the Borgesian Map theme, the project moves from a city-wide perspective to individual buildings, streets, trees, and landmarks.

The project combines an interactive 3D map with a 2D editorial poster to demonstrate how changing the viewing scale reveals different layers of the city.

### 02 | Interactive 3D Map

**[EXPLORE THE INTERACTIVE PARIS MAP](https://alalajmi15.github.io/30DayMapChallenge-2026/maps/day14_borgesian_map/exports/Paris_La_Carte_Infinie_PUBLISH.html)**

The interactive map includes:

- 3D building footprints
- Streets and the Seine River
- Parks and individual trees
- Selected Paris landmarks
- Zoom-dependent urban details
- Interactive camera controls
- Bilingual French and English information panels

**Note:** Building heights are illustrative (15 meters), not measured heights.

### 03 | The Final Poster

![La Carte Infinie — Paris](maps/day14_borgesian_map/exports/Day14_La_Carte_Infinie_Paris_Poster.png)

[View the high-resolution Paris poster (PDF)](maps/day14_borgesian_map/exports/Day14_La_Carte_Infinie_Paris_Poster.pdf)

### 04 | Cartographic Concept

The poster presents three connected geographic scales:

1. **The City** — Paris study area
2. **The District** — Louvre neighborhood
3. **The Details** — Individual urban features

The connected maps illustrate how the same geographic environment can be understood differently at multiple scales.

### 05 | Study Area & Methodology

**Location:** Paris, France

**Study area:** Approximately 48 km² (8 × 6 km).

**Coordinate reference system:** EPSG:2154.

**Tools and libraries:**

- Python
- GeoPandas
- Shapely
- Matplotlib
- MapLibre GL JS
- Jupyter Notebook

### 06 | Data Sources & Limitations

- OpenStreetMap geographic features
- OpenStreetMap data completeness varies by location
- Building heights are illustrative rather than measured
- The highlighted study boundary does not restrict interactive navigation

**[View Full Paris Project Documentation](maps/day14_borgesian_map/README.md)**

---

## ABOUT THE AUTHOR

**Alhaylam Fahad Alajmi**

Master of Urban Spatial Analytics (MUSA)  
University of Pennsylvania

*Civil Engineering | Geospatial Analytics | Urban Systems*

---

**30DayMapChallenge 2026**
