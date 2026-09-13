# Advanced Physics Laboratory
# Advanced Physics Laboratory

Selected experimental reports from **Advanced Physics Laboratory I–II (PHYS 442–443)** at the **Department of Physics, Boğaziçi University**.

This repository presents a selection of laboratory work covering statistical analysis of radioactive processes, atomic physics, X-ray spectroscopy, and semiconductor physics. The experiments involved experimental data acquisition, quantitative modeling, statistical fitting, uncertainty propagation, and comparison of measured results with theoretical predictions.

Data analysis and visualization were performed primarily using **CERN ROOT**. The ROOT analysis code used to produce the figures, fits, histograms, and numerical results is included in the appendices of the corresponding reports.

---

## Selected Experiments

### 1. Poisson Statistics and Radioactive Decay

An experimental investigation of the **Poisson distribution in radioactive decay**, using gamma-ray count data collected with a Geiger–Müller tube.

The analysis examines how well Poisson and Gaussian distributions describe radioactive counting statistics under different counting conditions. Histograms of experimental count data were fitted with both distributions and evaluated quantitatively using goodness-of-fit statistics. Time-dependent forms of the Poisson distribution were also used to estimate the decay-rate parameter from experimental event intervals.

**Analysis methods**
- Histogram construction and normalization
- Poisson distribution fitting
- Gaussian distribution fitting
- Comparison of competing statistical models
- Mean and standard-deviation analysis
- χ²/ndf goodness-of-fit evaluation
- Parameter estimation with uncertainties
- Analysis of time intervals between radioactive events

A particular focus of the experiment was the transition between the Poisson and Gaussian regimes and the behavior of the two models for low-count rare events.

---

### 2. Franck–Hertz Experiment — Neon

A modern implementation of the **Franck–Hertz experiment**, investigating discrete atomic excitation energies through inelastic electron–neon collisions.

Current–voltage characteristics were recorded under multiple experimental conditions. The recurring structures in these curves were analyzed using Gaussian peak fitting, allowing excitation energies to be extracted from the separation between successive features.

Measurements from multiple datasets were then combined statistically to obtain an experimental estimate of the first excitation energy of neon.

**Analysis methods**
- Current–voltage data analysis
- Gaussian peak fitting
- Peak-position and peak-separation extraction
- Propagation of fit uncertainties
- Inverse-variance weighted averages
- Weighted histogram construction
- Gaussian fitting of aggregated measurements
- Comparison of alternative data-aggregation methods

The analysis produced an experimental excitation energy close to the expected excitation scale of neon while also examining the effects of limited statistics, calibration, and experimental instability.

---

### 3. X-Ray Spectroscopy

An investigation of **X-ray production and spectroscopy** using an X-ray tube with a molybdenum target and Bragg diffraction from a NaCl crystal.

The experiment examined both the continuous **Bremsstrahlung spectrum** and characteristic **Kα and Kβ emission lines**. Angular measurements were converted into wavelength information through Bragg's law, while the short-wavelength cutoff of the Bremsstrahlung spectrum was analyzed using the Duane–Hunt relation.

Measurements at different accelerating voltages were ultimately used to obtain an experimental estimate of **Planck's constant**.

**Analysis methods**
- X-ray spectral visualization and analysis
- Identification of characteristic spectral peaks
- Gaussian peak fitting
- Experimental calibration and offset correction
- Bragg-diffraction analysis
- Bremsstrahlung cutoff determination
- Linear regression
- Multi-stage uncertainty propagation
- χ²/ndf evaluation
- Extraction of physical constants from fitted parameters

Particular attention was given to the propagation of experimental uncertainties and to the interpretation of fit quality when measurement uncertainties are large.

---

### 4. Hall Effect in n-Doped Germanium

An experimental study of the **Hall effect in an n-doped germanium semiconductor**, used to determine fundamental electronic transport properties of the material.

Hall voltage measurements were performed as functions of magnetic field and applied current. Combined with longitudinal voltage measurements, the experimental data were used to determine several semiconductor transport parameters.

**Quantities determined**
- Hall coefficient
- Electrical resistance
- Resistivity
- Conductivity
- Charge-carrier density
- Electron mobility

**Analysis methods**
- Linear fitting of experimental data
- Magnetic-field calibration and offset analysis
- Propagation of experimental uncertainties
- Extraction of material parameters from fitted quantities
- Comparison of experimental behavior with the classical Hall/Drude description

This experiment extends the portfolio beyond atomic and radiation physics into **solid-state and semiconductor physics**, demonstrating the use of quantitative data analysis for material characterization.

---

## Computational and Data-Analysis Methods

Across these experiments, the analysis involved a combination of experimental physics and computational data processing, including:

- **CERN ROOT**
- Experimental data visualization
- `TGraph` / error-bar graphs
- Histograms
- Linear and nonlinear fitting
- Gaussian fitting
- Poisson fitting
- χ²-based goodness-of-fit analysis
- Statistical parameter estimation
- Weighted averages
- Uncertainty propagation
- Extraction of physical parameters from fitted models

The complete analysis code is included in the **appendix of each laboratory report**, alongside the corresponding figures and numerical results.

---

## Reports

| Experiment | Main Topics | Key Analysis |
|---|---|---|
| **Poisson Statistics** | Radioactive decay, counting statistics | Histograms, Poisson/Gaussian fits, χ²/ndf |
| **Franck–Hertz (Neon)** | Atomic excitation, quantum physics | Gaussian peak fits, weighted averages, weighted histograms |
| **X-Ray Spectroscopy** | Bremsstrahlung, characteristic radiation, Bragg diffraction | Spectral analysis, calibration, linear fits, uncertainty propagation |
| **Hall Effect** | Semiconductor physics, electronic transport | Linear fits, Hall coefficient, carrier density, mobility |

The individual PDF reports in this repository contain the full theoretical background, experimental setup, methodology, data analysis, discussion of uncertainties, results, and ROOT source code.

---

## About

These reports were prepared as part of the mandatory upper-level **Advanced Physics Laboratory** sequence in the undergraduate Physics program at **Boğaziçi University**.

**Berkay Köktürk**  
B.Sc. Physics, Boğaziçi University  
M.Sc. Physics, Heidelberg University
