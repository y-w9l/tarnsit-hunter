# 🪐 Exoplanet Transit Hunter — Hack4Dev Iraq 2026

![Hack4Dev Banner](https://img.shields.io/badge/Hackathon-Hack4Dev--Iraq--2026-blue?style=for-the-badge)
![Challenge](https://img.shields.io/badge/Challenge-A%3A%20Transit%20Hunter-orange?style=for-the-badge)
![Team](https://img.shields.io/badge/Team-Physics%20Club%20Team-purple?style=for-the-badge)

---

## 📌 1. Team & Project Overview

* Team Name: Physics Club Team
* Hackathon: Hack4Dev Iraq Data Science Hackathon (Exoplanet Data Challenge 2026)[span_1](start_span)[span_1](end_span)
* Selected Track: Challenge A — Transit Hunter[span_2](start_span)[span_2](end_span)

---

## 🎯 2. Problem Statement

Observational photometric data collected from stars often contains significant noise, non-transit variability (such as stellar activity, starspots, or instrumental artifacts), and gaps[span_3](start_span)[span_3](end_span). 

The primary challenge is to accurately identify true periodic flux dips caused by transiting exoplanets while filtering out false positives and instrumental noise, as well as extracting valid physical characteristics from the detected signals[span_4](start_span)[span_4](end_span).

---

## 💡 3. Proposed Solution

The Physics Club Team developed an end-to-end analytical pipeline to process light curves and detect candidate exoplanetary transits[span_5](start_span)[span_5](end_span):

1. Data Preprocessing & Cleaning: Handling missing values and removing outliers without distorting genuine scientific signals[span_6](start_span)[span_6](end_span).
2. Detrending: Eliminating long-term stellar variability and instrumental trends to isolate short-term transit events.
3. Signal Detection: Identifying periodic brightness dips corresponding to potential planetary transits[span_7](start_span)[span_7](end_span).
4. Scientific Validation & Interpretation: Distinguishing candidate exoplanet signals from false positives (e.g., eclipsing binaries or stellar noise) and estimating key physical properties alongside uncertainty bounds[span_8](start_span)[span_8](end_span).

---

## 🔬 4. Scientific Background

This project relies on the Transit Method (Transit Photometry), one of the most successful techniques for discovering exoplanets:

* Photometry: When an exoplanet passes directly between its host star and the observer (or space telescope), it blocks a small fraction of the star's light.
* Light Curve: A graph showing the star's brightness (flux) over time[span_9](start_span)[span_9](end_span).
* Transit Signature: A transiting planet creates a distinct, periodic U-shaped or box-like dip in the light curve[span_10](start_span)[span_10](end_span).
* Key Astrophysical Parameters:
  * Transit Depth ($\Delta F / F$): Directly related to the ratio of the planet's radius to the star's radius $\left(\frac{R_p}{R_*}\right)^2$. Larger planets cause deeper dips.
  * Orbital Period ($P$): The time interval between consecutive transit events.
  * Transit Duration ($T_{dur}$): Depends on the planet's orbital speed and inclination relative to the observer's line of sight.

> ⚠️ Scientific Note: A dip in a light curve alone does not guarantee a confirmed exoplanet[span_11](start_span)[span_11](end_span). Eclipsing binary systems, background signals, and starspots can mimic transit signals and must be systematically evaluated[span_12](start_span)[span_12](end_span).

---

## 🛠️ 5. Tech Stack & Tools

<!-- ✏️ [Leave empty for your tools and libraries] -->




---

## ⚙️ 6. Code Execution & Pipeline Mechanics

<!-- ✏️ [Leave empty for your code explanation and run instructions] -->




---

## 📊 7. Results & Limitations

* Deliverables:
  * Cleaned and detrended light curve visualisations[span_13](start_span)[span_13](end_span).
  * * Identified candidate signals along with estimated physical parameters[span_14](start_span)[span_14](end_span).
  * Fully reproducible Jupyter Notebooks / Scripts[span_15](start_span)[span_15](end_span).
* Limitations:
  * Low Signal-to-Noise Ratio ($SNR$) signals require further validation.
  * Detected signals remain "exoplanet candidates" until confirmed via follow-up methods (e.g., Radial Velocity measurements)[span_16](start_span)[span_16](end_span).

---

## 📜 8. Acknowledgments & References

* Organizers: Hack4Dev Iraq 2026 - Iraqi Andromeda Team[span_17](start_span)[span_17](end_span)
* Authors: Physics Club Team (College of Artificial Intelligence, University of Baghdad)

