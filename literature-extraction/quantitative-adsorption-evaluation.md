# Stage 2 Extraction 02 — Quantitative Adsorption Evaluation

**Status:** First-pass, source-grounded extraction for slide 9.  
**Source boundary:** The fixed 15-paper collection only. The quantitative definitions and worked example below are taken from REF-09; the volume-aware mass balance and additional method controls are cross-checked against REF-14. A formula inconsistency in REF-15 is recorded as a source warning, not silently corrected.  
**Use:** Scientific content foundation for slide 9; not final slide copy.

---

## 1. What is measured in a batch adsorption experiment?

A batch experiment places a known mass of adsorbent in contact with a known volume and initial concentration of antibiotic solution under controlled conditions. Researchers vary or hold constant parameters such as pH, adsorbent dose, initial antibiotic concentration, contact time and temperature. After contact, the solid is separated from the liquid and the remaining antibiotic concentration is measured.

The concentration decrease in solution is used to calculate the antibiotic mass removed from the liquid phase. This is then expressed in two different ways:

- **Adsorption capacity, q:** mass of antibiotic adsorbed per unit mass of adsorbent (commonly mg g⁻¹).
- **Removal efficiency, Y or R:** percentage of the initial antibiotic concentration removed from solution (%).

These are related by the mass balance but answer different questions. Capacity normalises uptake to adsorbent mass; removal efficiency expresses the fraction removed from the treated solution.

**Selected-source support**
- REF-09, PDF p. 2: batch tests used 30 mL of TC or CIP solution in 50 mL flasks; solution pH, adsorbent dose, contact time and initial concentration were varied. Starting concentrations were measured by UV–vis calibration curves, using 360 nm for TC and 278 nm for CIP. Duplicate experiments were reported as means with standard deviations.
- REF-14, PDF p. 4: experiments were conducted in magnetically stirred glass flasks at controlled pH and temperature. Samples were taken at specified times, centrifuged, and the supernatant was analysed for ciprofloxacin. Tests were performed in triplicate; blank tests were also performed.

## 2. Mass-balance equations

### 2.1 Equilibrium adsorption capacity

For a batch system in which the liquid volume is treated as constant:

\[
q_e = \frac{(C_0-C_e)V}{m}
\]

where:

- \(q_e\) = equilibrium adsorption capacity (mg g⁻¹);
- \(C_0\) = initial antibiotic concentration in solution (mg L⁻¹);
- \(C_e\) = equilibrium antibiotic concentration in solution (mg L⁻¹);
- \(V\) = solution volume (L);
- \(m\) = dry adsorbent mass (g).

This is the definition used by REF-09 (PDF p. 2, Eq. 2).

### 2.2 Removal efficiency

\[
Y(\%) = \frac{C_0-C_e}{C_0}\times100
\]

This is the removal-efficiency definition used by REF-09 (PDF p. 2, Eq. 1).

### 2.3 Time-dependent uptake and changing liquid volume

When concentration is measured at time \(t\), use \(C_t\) rather than \(C_e\). REF-14 expresses uptake as:

\[
q_t = \frac{C_0V_0-C_tV_t}{m}
\]

Here, \(V_0\) and \(V_t\) are the initial and time-\(t\) solution volumes. This form retains the mass balance when the liquid volume at sampling differs from the initial volume (REF-14, PDF p. 4, Eq. 1). For a constant-volume experiment, it reduces to:

\[
q_t = \frac{(C_0-C_t)V}{m}
\]

Use the equilibrium expression only when the system has reached the stated equilibrium condition. Do not label an arbitrary time-point uptake as \(q_e\).

### 2.4 Unit check

With concentration in mg L⁻¹, volume in L, and adsorbent mass in g:

\[
\frac{(\mathrm{mg\,L^{-1}})(\mathrm{L})}{\mathrm{g}} = \mathrm{mg\,g^{-1}}
\]

Convert mL to L before applying the equation, unless all units are converted consistently.

## 3. Typical experimental workflow and what must be reported

1. Prepare an antibiotic solution with a known initial concentration, \(C_0\), and volume, \(V_0\).
2. Add a measured dry mass of adsorbent, \(m\), and report the corresponding dose (g L⁻¹).
3. Set and report pH and temperature; agitate for a defined contact time and mixing condition.
4. Separate the adsorbent from the liquid by the method used in the study (e.g., filtration or centrifugation).
5. Measure the remaining antibiotic concentration using an appropriate calibration curve/analytical method.
6. Calculate uptake and removal using a clearly stated mass-balance equation.
7. Report replicates, variation, blanks and any sampling-volume correction.

REF-09 reports UV–vis calibration curves and duplicate measurements (PDF p. 2). REF-14 reports centrifugation and supernatant analysis, triplicate measurements and blank tests (PDF p. 4). The analytical wavelength should not be copied indiscriminately between compounds or pH conditions: REF-09 used different wavelengths for TC and CIP, while REF-14 reports pH-dependent CPX wavelengths and separate calibration curves (REF-14, PDF p. 4).

For comparisons, report at least the antibiotic, adsorbent, initial concentration, pH, adsorbent dose or mass, solution volume, contact time, temperature, separation/measurement method, and whether the result is measured, calculated from a mass balance or fitted by a model.

## 4. Worked numerical example — derived from REF-09

REF-09 reports a TC adsorption capacity of **16.15 mg g⁻¹** at pH 10. The corresponding Figure 1 conditions are: initial TC concentration 50 mg L⁻¹, date-palm-fibre dose 1 g L⁻¹, temperature 298 K and contact time 3 h (REF-09, PDF p. 3).

The experiment used 30 mL of solution (REF-09, PDF p. 2). At a dose of 1 g L⁻¹:

\[
m = (1\;\mathrm{g\,L^{-1}})(0.030\;\mathrm{L})=0.030\;\mathrm{g}
\]

The antibiotic mass adsorbed, calculated from the reported capacity, is:

\[
m_{\mathrm{adsorbed}}=(16.15\;\mathrm{mg\,g^{-1}})(0.030\;\mathrm{g})
=0.4845\;\mathrm{mg}
\]

Initial antibiotic mass:

\[
m_0=(50\;\mathrm{mg\,L^{-1}})(0.030\;\mathrm{L})=1.500\;\mathrm{mg}
\]

Residual mass and the corresponding equilibrium concentration, back-calculated on the same mass-balance basis:

\[
m_e=1.500-0.4845=1.0155\;\mathrm{mg}
\]

\[
C_e=\frac{1.0155\;\mathrm{mg}}{0.030\;\mathrm{L}}
=33.85\;\mathrm{mg\,L^{-1}}
\]

Removal efficiency derived from the reported capacity and dose:

\[
Y=\frac{50-33.85}{50}\times100=32.3\%
\]

**Interpretation and provenance:** The reported value is \(q=16.15\;\mathrm{mg\,g^{-1}}\). The residual concentration (33.85 mg L⁻¹) and removal percentage (32.3%) above are **derived calculations**, not separately quoted measured values from the article. This is a worked mass-balance illustration anchored to one reported REF-09 condition; it must not be presented as an independently reported removal result.

## 5. What the experimental results teach about the two metrics

REF-09 provides direct examples showing that capacity and removal efficiency do not necessarily peak at the same initial concentration:

- For TC, reported \(q\) reached 24.5 mg g⁻¹ as \(C_0\) increased to 80 mg L⁻¹, then was nearly constant at higher concentrations; the maximum reported removal efficiency (54.8%) occurred at the lowest initial concentration.
- For CIP, reported \(q\) increased to 32 mg g⁻¹ at 100 mg L⁻¹ and then changed little; the maximum reported removal efficiency (58.75%) occurred at 30 mg L⁻¹.
- In the adsorbent-dose experiment, removal efficiency reached 84.77% for TC and 66.7% for CIP at 5 g L⁻¹. However, capacity per gram decreased above 1 g L⁻¹ for TC and 0.5 g L⁻¹ for CIP (REF-09, PDF pp. 3–4).

These are study-specific results, not universal optimum values. They demonstrate why a presentation must state whether it is comparing percentage removal or uptake per gram, and must keep the experimental conditions attached to each result.

## 6. Source-quality and interpretation cautions

### 6.1 Do not confuse measured, calculated and fitted quantities

- A residual concentration is an analytical measurement (e.g., from a calibration curve).
- \(q_e\) calculated from the measured concentration, volume and adsorbent mass is a mass-balance-derived uptake.
- \(q_m\) from a Langmuir isotherm is a fitted model parameter, not automatically the measured uptake in a particular batch.
- Removal efficiency is a percentage and is not an adsorption capacity.

### 6.2 REF-15 equation-sign anomaly

In the uploaded REF-15 PDF, page 3, the printed expressions for adsorption capacity and removal rate use \((C_e-C_0)\) rather than \((C_0-C_e)\), while the accompanying definitions identify \(C_0\) as the initial concentration and \(C_e\) as the equilibrium concentration. For net removal, the printed sign would produce a negative value. This appears inconsistent with the positive-capacity convention explicitly used in REF-09 (PDF p. 2) and REF-14 (PDF p. 4). **Do not reproduce REF-15's printed equations as the positive uptake/removal formulas.** Retain the discrepancy as a source-level warning; the conventional positive mass-balance form used in this presentation is supported independently by REF-09 and REF-14. Do not silently alter REF-15's own text or claim that the publisher has confirmed a correction.

### 6.3 Scope boundary

A decrease in dissolved concentration is used by these studies to quantify removal from the liquid phase. Do not describe this as antibiotic degradation or mineralisation unless a transformation process is independently demonstrated. Adsorption capacity alone does not establish practical low cost or process viability.

## 7. Slide 9 content recommendation

**Title:** Adsorption Capacity and Removal Efficiency

Recommended visual sequence:

- **Experimental setup:** known antibiotic concentration and volume + known dry adsorbent mass → controlled pH/temperature/contact time → solid–liquid separation → residual concentration measurement.
- **Two equations:** show \(q_e\) and \(Y\) side by side, with units and symbol definitions.
- **Worked example:** use the REF-09 TC/date-palm-fibre example above, explicitly labelling the back-calculated \(C_e\) and removal percentage as derived.
- **Interpretation callout:** “High percentage removal does not necessarily mean high adsorption capacity per gram.”

Keep the main slide uncluttered; place the complete calculation and experimental conditions in speaker notes or a compact worked-example panel. Cite REF-09 and REF-14 beside the corresponding equations/protocol, and REF-15 only in a source-quality note if there is room.

---

## Source map

| REF-ID | PDF locator | Material/system | Use in this extraction |
|---|---|---|---|
| REF-09 | PDF p. 2, Eqs. (1)–(2), Section 2.3 | Raw date-palm fibre; TC and CIP | Core positive mass-balance equations, batch setup, concentration measurement, duplicate runs |
| REF-09 | PDF p. 3, Figure 1 and Section 3.2 | Raw date-palm fibre; TC and CIP | Worked example condition and reported capacity; capacity/removal response to initial concentration |
| REF-09 | PDF p. 4, Figure 4 and Section 3.3 | Raw date-palm fibre; TC and CIP | Dose dependence: removal versus uptake per gram |
| REF-14 | PDF p. 4, Section 2.4, Eq. (1) | K2CO3-activated barley-bagasse biochar; CIP | Time-dependent, volume-aware mass balance; centrifugation, supernatant analysis, triplicates and blanks |
| REF-14 | PDF p. 4, Section 2.3 | K2CO3-activated barley-bagasse biochar; CIP | pH-dependent analytical wavelengths and calibration curves |
| REF-15 | PDF p. 3, Eqs. (1)–(2) | Fermentation-residue-derived porous biochar; TC | Recorded equation-sign anomaly; not used as the source of the positive equations |

**Next Stage 2 extraction:** adsorption isotherms (slide 10), followed by kinetics, thermodynamics, regeneration and economics. Do not add references or begin PowerPoint production before the extraction/evidence review is complete.
