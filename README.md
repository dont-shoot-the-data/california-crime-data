# 🔴 California Race & Crime — By the Numbers

### An independent public records investigation into interracial violent crime across California's 10 largest cities.

**[→ View the Live Investigation](https://dont-shoot-the-data.github.io/california-crime-data/)**

---

## What This Is

A single-file interactive data visualization built from **public records requests** filed with 10 California police departments, requesting case-level suspect and victim data for four violent felony categories:

| Crime | Cities with Data |
|-------|-----------------|
| Homicide | Sacramento · San José · Oakland · San Francisco · San Diego · Los Angeles |
| Sexual Assault | Sacramento · San José |
| Robbery | Sacramento · San José |
| Kidnapping | Sacramento · San José |

Every number on the site traces back to either a **police department response** or a **California Attorney General report**. Source links are provided for every dataset. Nothing is modeled. Nothing is estimated. Nothing is hidden.

---

## Key Findings

### 🎯 #1 Target of Interracial Violence: **White Californians**

- **5,891** interracial attacks on White victims across all cities
- **76.4%** of all violence against White victims is interracial
- Ranked **#1 most interracially victimized** in all four crime categories
- Most murdered · Most raped · Most robbed · Most kidnapped — by other races

### ⚠️ #1 Source of Interracial Violence: **Black Californians**

- **9,474** interracial attacks by Black suspects across all cities
- Ranked **#1 interracial perpetrator** in all four crime categories
- 3.5× more interracial attacks than the #2 source (Hispanic: 2,743)

### 📊 The Pattern Holds Everywhere

White victims ranked #1 or #2 most interracially targeted in **every single city/crime combination** in the dataset — 11 of 11. Not one exception.

---

## Data Sources

| Source | Type | Period |
|--------|------|--------|
| Sacramento PD | Public Records Request | Jan 2016 – Mar 2024 |
| San José PD | Public Records Request | Jan 2020 – Jun 2025 |
| Oakland PD | Public Records Request | Jan 2020 – Mar 2024 |
| San Francisco PD | Public Records Request | Jan 2020 – early 2024 |
| San Diego Co. Sheriff | Transparency Reports | 2022 – 2025 |
| Los Angeles PD | Annual Homicide Reports | 2022 – 2024 |
| CA Attorney General | Crime in California Reports | 2000 – 2024 |

### Cities That Denied or Ignored Requests

| City | Status |
|------|--------|
| Fresno | ❌ PRR Denied |
| Long Beach | ❌ PRR Denied |
| Bakersfield | ⏳ Pending |
| Anaheim | ⏳ Pending |

---

## Methodology

- **One suspect = one count.** No cartesian pairing of suspects × victims.
- **Ethnicity over race.** Hispanic ethnicity takes precedence to avoid Hispanic/White conflation.
- **Unknown race disclosed separately.** Never bucketed into "Other."
- **Fractional victim split.** Mixed-victim incidents use 1/n per victim race. All cells floor-rounded.
- **Cross-tab pairing.** Suspect race → victim race matrices built from case-level incident data.

Full methodology is documented on the site.

---

## Tech

Single self-contained HTML file. No build step. No dependencies. No framework. No server.

- Vanilla JS + CSS
- ~5,300 lines
- All data embedded inline
- Responsive (mobile + desktop)
- Scroll-triggered animations
- Interactive tooltips and hover previews

---

## Who Made This

Independent investigative data journalism by [dont-shoot-the-data](https://github.com/dont-shoot-the-data).

This is not affiliated with any university, think tank, nonprofit, or political organization. The data speaks for itself.

---

<p align="center">
  <strong>If the data is wrong, show me where.</strong><br>
  <em>Every source is linked. Every number is verifiable.</em>
</p>
