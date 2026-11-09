# Stage 2 Extraction 03 — Adsorption Isotherms

**Status:** Source-grounded extraction completed for slide 10.  
**Source boundary:** Only the fixed 15-paper collection is used. The modelling framework is drawn primarily from REF-06; antibiotic-specific comparisons are drawn from REF-09, REF-10 and REF-14. No new references have been added.  
**Use:** Scientific foundation and slide-content preparation, not final slide copy.

---

## 1. What an adsorption isotherm describes

An adsorption isotherm relates the amount of adsorbate retained by an adsorbent at equilibrium to the residual concentration of adsorbate in the liquid phase, at a specified temperature and under specified solution conditions.

The central relationship is:

- \(C_e\): equilibrium concentration remaining in the liquid phase (commonly mg L\(^{-1}\));
- \(q_e\): equilibrium amount adsorbed per unit mass of adsorbent (commonly mg g\(^{-1}\)).

An isotherm is therefore an equilibrium relationship, not a rate equation. It does not describe how quickly equilibrium is reached; that is the subject of adsorption kinetics.

REF-06 identifies equilibrium information as essential to understanding and designing an adsorption system (PDF p. 1). REF-14 describes its experimental isotherm as the relationship between \(C_e\) and \(q_e\) at equilibrium (PDF p. 11).

**Important condition:** An isotherm curve is specific to the conditions under which it was measured. Temperature, pH, antibiotic speciation, adsorbent dose and the experimental concentration range must be reported. Do not compare fitted constants from studies with different conditions as though they were directly interchangeable.

## 2. The four models approved for slide 10

The project plan specifies Langmuir, Freundlich, Temkin and Sips. The equations below retain the parameterisations and notation used by the selected sources. \(q_e\) is in mg g\(^{-1}\) and \(C_e\) is in mg L\(^{-1}\), unless a study uses another concentration basis.

### 2.1 Langmuir isotherm

**Equation used in REF-14:**

\[
q_e=\frac{q_{mL}K_L C_e}{1+K_L C_e}
\]

where:

- \(q_{mL}\) = Langmuir-fitted maximum adsorption capacity (mg g\(^{-1}\));
- \(K_L\) = Langmuir equilibrium constant (L mg\(^{-1}\)).

**Model interpretation and assumptions**

- The model represents a finite surface coverage and approaches a limiting uptake as concentration increases.
- REF-06 describes adsorption and desorption as balancing at dynamic equilibrium; adsorption is proportional to the fraction of surface that remains open, and desorption to the fraction already covered (PDF p. 2).
- REF-09 interprets its Langmuir fit for tetracycline as consistent with a homogeneous adsorbent surface containing a limited number of identical, independent adsorption sites and monolayer coverage at equilibrium (PDF p. 6).

Use the homogeneous-site/monolayer description as the idealised Langmuir interpretation. A good fit is not direct microscopic proof that every site is identical or that the real surface is perfectly uniform.

**Separation factor**

REF-06 gives the dimensionless Langmuir separation factor:

\[
R_L=\frac{1}{1+K_L C_0}
\]

The source interprets \(R_L>1\) as unfavourable, \(R_L=1\) as linear, \(0<R_L<1\) as favourable, and \(R_L=0\) as irreversible adsorption (REF-06, PDF p. 2). Use the same concentration units for \(K_L\) and \(C_0\). \(R_L\) is a model-derived indicator, not an independent measurement of mechanism.

### 2.2 Freundlich isotherm

**Equation used in REF-14:**

\[
q_e=K_F C_e^{1/n}
\]

where:

- \(K_F\) = Freundlich coefficient, with units depending on the exponent and the units chosen for \(C_e\);
- \(n\) = dimensionless Freundlich exponent parameter in this equation.

REF-06 describes Freundlich as applicable to heterogeneous surfaces and as representing surface heterogeneity and an exponential distribution of active-site energies (PDF p. 2).

**Interpretation**

- It is an empirical relationship used to describe non-uniform adsorption surfaces.
- Unlike the Langmuir form, the equation has no explicit finite saturation-capacity parameter \(q_m\). Therefore, \(K_F\) must not be relabelled as a measured maximum capacity.
- The precise meaning and favourability interpretation of \(n\) must follow the exact form of the equation and the convention used by the individual paper.

**Parameter caution:** The selected studies do not report or interpret the Freundlich exponent in a fully uniform way. REF-09 reports \(n=0.307\) for TC and \(n=0.384\) for CIP (PDF p. 7), whereas REF-14 reports \(n=6.44\) and interprets \(n>1\) as favourable under its stated convention (PDF p. 12). REF-10 also uses \(n>1\) as a favourability indicator (PDF p. 7). Do not compare raw \(n\) values or apply a universal threshold without checking the exact equation and exponent convention used in each paper.

### 2.3 Temkin isotherm

**Equation presented in REF-06:**

\[
q_e=\frac{RT}{b_T}\ln K_T+\frac{RT}{b_T}\ln C_e
\]

Equivalently, using the same model form:

\[
q_e=\frac{RT}{b_T}\ln(K_T C_e)
\]

where:

- \(R\) = universal gas constant;
- \(T\) = absolute temperature;
- \(b_T\) = Temkin parameter related to heat of sorption (REF-06 reports J mol\(^{-1}\));
- \(K_T\) = Temkin equilibrium constant (the reported unit depends on the concentration basis and model convention).

**Model interpretation**

- REF-06 states that Temkin accounts for indirect adsorbate–adsorbate interactions.
- It assumes that the heat of adsorption of the molecules in the layer decreases linearly as surface coverage increases.
- REF-06 identifies the model as applicable over an intermediate range of ion concentrations (PDF p. 3).

**Thermodynamic caution:** Do not determine whether adsorption is endothermic or exothermic solely from a Temkin fit. REF-09 explicitly notes that the Temkin model alone does not provide sufficient information to establish the endothermic or exothermic nature of adsorption; its separate thermodynamic analysis indicated endothermic behaviour (REF-09, PDF p. 6). The paper's positive \(b_T\) values and its thermodynamic conclusion should both be preserved with this qualification.

### 2.4 Sips isotherm (Langmuir–Freundlich form)

**Equation used in REF-14:**

\[
q_e=
\frac{q_{mS}K_S C_e^{1/n_S}}
{1+K_S C_e^{1/n_S}}
\]

where:

- \(q_{mS}\) = Sips-fitted maximum adsorption capacity (mg g\(^{-1}\));
- \(K_S\) = Sips constant, with units depending on \(n_S\) and the concentration basis;
- \(n_S\) = dimensionless Sips exponent.

REF-06 describes Sips as a combination of the Langmuir and Freundlich isotherms and as suitable for heterogeneous surfaces. Its stated limiting behaviour is Freundlich-like at low adsorbate concentration and Langmuir-like at high concentration (PDF p. 5). REF-14 supplies the explicit equation, parameter definitions and units used in its ciprofloxacin study (PDF p. 6).

**Interpretation**

Sips provides a way to represent heterogeneous adsorption while also allowing the fitted curve to approach a finite limiting capacity at high concentration. The fitted \(q_{mS}\) is a model parameter; it should not automatically be called an experimentally achieved uptake.

**Source-equation qualification:** The printed Sips equation in REF-06 (Eq. 21, PDF p. 4) uses a denominator containing a minus sign and a different parameterisation from REF-14's Table 2 (PDF p. 6), which uses a plus sign. This difference is recorded rather than silently reconciled. For the slide equation, use the directly specified REF-14 form above, and do not present it as a verbatim transcription of REF-06 Eq. 21.

## 3. Additional isotherm models present in the selected literature

The four models above are the approved teaching focus, but the fixed papers also apply other equilibrium models. These are important context because the best-fitting model differs between antibiotic–adsorbent systems.

- **Dubinin–Radushkevich (D–R):** used in REF-09 for TC/CIP and REF-10 for CIP/TET. REF-06 describes it as a semi-empirical model associated with a Gaussian energy distribution and pore filling (PDF pp. 2–3); the studies use its fitted parameters to discuss adsorption characteristics.
- **Langmuir–Freundlich (L–F):** used in REF-10 as a three-parameter model and described as combining Langmuir and Freundlich behaviour.
- **Brouers–Sotolongo (B–S):** used in REF-10 for several TET/adsorbent combinations.
- **Redlich–Peterson and Toth:** used in REF-14 alongside Langmuir, Freundlich and Sips.

Do not expand slide 10 into a catalogue of every model. A short note that experimental papers may test additional models is sufficient; the central teaching comparison remains the four approved models.

## 4. What the selected antibiotic studies actually report

### 4.1 REF-09 — Raw date-palm fibre with tetracycline and ciprofloxacin

The authors fitted Langmuir, Freundlich, Temkin and D–R models to TC and CIP equilibrium data (REF-09, PDF pp. 6–7).

**Model selection reported by the authors**

- **TC:** Langmuir was the best of the tested models, with \(R^2=0.977\); the D–R fit had \(R^2=0.923\), Freundlich \(R^2=0.845\), and Temkin \(R^2=0.939\).
- **CIP:** D–R was the best of the tested models, with \(R^2=0.975\); Langmuir had \(R^2=0.953\), Freundlich \(R^2=0.837\), and Temkin \(R^2=0.944\).

**Selected fitted parameters from Table 2 (REF-09, PDF p. 7)**

| Model parameter | Tetracycline | Ciprofloxacin |
|---|---:|---:|
| Langmuir \(q_m\) (mg g\(^{-1}\)) | 29.16 | 41.47 |
| Langmuir \(K_L\) (L mg\(^{-1}\)) | 0.075 | 0.049 |
| Langmuir \(R^2\) | 0.977 | 0.953 |
| Freundlich \(n\) | 0.307 | 0.384 |
| Freundlich \(K_F\) | 6.405 | 6.058 |
| Freundlich \(R^2\) | 0.845 | 0.837 |
| D–R \(q_s\) (mg g\(^{-1}\)) | 23.68 | 32.54 |
| D–R \(E\) (kJ mol\(^{-1}\)) | 0.247 | 0.157 |
| D–R \(R^2\) | 0.923 | 0.975 |
| Temkin \(b_T\) (J mol\(^{-1}\)) | 405.56 | 253.72 |
| Temkin \(A_T\) (L mol\(^{-1}\), as tabulated) | 0.751 | 0.382 |
| Temkin \(R^2\) | 0.939 | 0.944 |

The article's interpretation is that TC behaviour is represented better by Langmuir, while CIP is represented better by D–R. The authors associate the Langmuir fit for TC with homogeneous, identical, independent sites and monolayer adsorption; they discuss the D–R fit for CIP in terms of energy distribution and date-palm surface characteristics (REF-09, PDF p. 6).

**Use qualification:** These are fitted model parameters and model-fit statistics, not direct proof of a unique molecular mechanism. Do not rank TC and CIP solely by their fitted \(q_m\) or \(q_s\) values without considering the different model selected for each antibiotic.

### 4.2 REF-10 — Kaolinite/coconut-husk hybrid biochar for simultaneous CIP and TET adsorption

The study compares three material states: KCB (unactivated hybrid biochar), KCB-A (acid-activated) and KCB-B (alkali-activated). The authors test Langmuir, Freundlich, D–R and Temkin as two-parameter models, then L–F and B–S as three-parameter models (REF-10, PDF pp. 5–7).

**Two-parameter model selection reported**

| Antibiotic/material | Best reported two-parameter fit | Reported \(R^2\) |
|---|---|---:|
| CIP on KCB | Temkin | 0.989 |
| CIP on KCB-A | Langmuir | 0.999 |
| CIP on KCB-B | Langmuir | 0.985 |
| TET on KCB | D–R | 0.974 |
| TET on KCB-A | Langmuir | 0.965 |
| TET on KCB-B | D–R | 0.971 |

The authors report Langmuir monolayer capacity values of 71.1, 139.9 and 228.7 mg g\(^{-1}\) for CIP on KCB, KCB-A and KCB-B, respectively; for TET the corresponding values are 118, 116.6 and 231.9 mg g\(^{-1}\) (REF-10, PDF p. 6).

**Three-parameter model selection reported**

- L–F gave the best fit for CIP on the three materials (\(R^2>0.98\), as reported).
- B–S gave the best fit for TET on KCB (\(R^2>0.997\)) and KCB-A (\(R^2>0.969\)); L–F was reported as best for TET on KCB-B (REF-10, PDF p. 7).

**Use qualification:** This study is a particularly clear example that the selected model depends on both the antibiotic and the specific adsorbent preparation. The complete Table S1 containing detailed isotherm parameters is in the supplementary information, which was not included in the uploaded PDF set. Do not invent missing three-parameter values or treat the reported \(R^2\) values as a complete error-analysis record.

### 4.3 REF-14 — Ciprofloxacin on K2CO3-activated barley-bagasse biochar

The isotherm experiment was conducted at 25 °C and pH 3.5, using 0.025 g of adsorbent with 50 mL of ciprofloxacin solution over an initial concentration range of 25–1000 mg L\(^{-1}\). Equilibrium was reached at approximately 80 h. The models were fitted by nonlinear regression using Excel Solver, minimising the average relative error (ARE) (REF-14, PDF p. 6).

The study tested Langmuir, Freundlich, Sips, Redlich–Peterson and Toth models.

**Table 4 results (REF-14, PDF pp. 11–12)**

| Model | Fitted capacity (mg g\(^{-1}\)) | ARE (%) |
|---|---:|---:|
| Langmuir | \(q_{mL}=104.9\) | 11.94 |
| Freundlich | No finite \(q_m\) parameter | 2.44 |
| Sips | \(q_{mS}=133.4\) | 4.92 |
| Redlich–Peterson | No \(q_m\) reported in this table | 3.31 |
| Toth | \(q_{mT}=131.4\) | 5.40 |

The article identifies Freundlich as the best fit because it has the lowest ARE (2.44%). Redlich–Peterson, Sips and Toth are also described as suitable; Langmuir is considered unsuitable for this dataset because of its higher ARE (11.94%) (REF-14, PDF p. 12).

The experimental curve approaches approximately 110 mg g\(^{-1}\), but the authors state that a clear plateau is not reached even at the higher concentrations (REF-14, PDF pp. 11–12). The different fitted capacities from Langmuir, Sips and Toth therefore illustrate why a fitted maximum capacity must be identified with its model and should not automatically be reported as measured uptake.

## 5. Model fitting and how to decide which isotherm is suitable

### 5.1 Avoid relying on linearised \(R^2\) alone

REF-06 explains that transforming an isotherm to a linear form changes the error structure of the experimental data. The authors describe nonlinear regression on the original isotherm equation as a mathematically rigorous way to estimate parameters and minimise the difference between experimental and model-predicted uptake (REF-06, PDF p. 7).

REF-06 discusses multiple error functions, including:
- sum of squared errors (SSE/ERRSQ);
- hybrid fractional error;
- average relative error (ARE);
- Marquardt percentage standard deviation (MPSD);
- sum of absolute errors;
- nonlinear chi-square.

The article notes that different error functions can produce different parameter sets. It also explains that the ordinary sum of squared errors can weight larger high-concentration errors more heavily, while the hybrid fractional error was developed to improve fit at low concentrations (REF-06, PDF pp. 7–8).

REF-14 provides a practical example: it fits the original nonlinear equations and selects the best model by minimising ARE (REF-14, PDF p. 6).

### 5.2 Recommended model-selection procedure for this presentation

1. Plot the experimental equilibrium data as \(q_e\) against \(C_e\), retaining the tested concentration range and conditions.
2. Fit the nonlinear equation for each candidate model to the same experimental dataset.
3. Report the model parameter estimates with their units and the fitting method.
4. Compare more than one appropriate goodness-of-fit/error measure where available; inspect residual patterns rather than relying only on \(R^2\).
5. Check that the fitted parameters are physically meaningful and consistent with the concentration range measured.
6. State the selected model as the best statistical description under those conditions, not as proof of the molecular adsorption mechanism.

This procedure follows the methodological cautions in REF-06 and the nonlinear ARE workflow in REF-14.

## 6. Scientific safeguards and source discrepancies

1. **A fitted isotherm is not a mechanism measurement.** Langmuir, Freundlich, Temkin or Sips fit alone does not prove a unique molecular mechanism.
2. **A fitted \(q_m\) is not automatically an observed uptake.** State whether the value comes from Langmuir, Sips or Toth, and report it as a model-fitted parameter.
3. **Do not call \(K_F\) a maximum capacity.** The Freundlich equation has no explicit finite \(q_m\) term.
4. **Do not compare fit statistics across different studies as if they were generated from identical experiments.** Compare candidate models within the same study and dataset first.
5. **Check units and parameter definitions.** The reported units for Temkin constants vary with the concentration basis; Freundlich and Sips coefficients also depend on their exponent conventions.
6. **Sips equation discrepancy:** REF-06 Eq. (21) (PDF p. 4) and REF-14 Table 2 (PDF p. 6) print different denominator signs/parameterisations. The slide equation in this extraction follows REF-14's experimental-paper form. Preserve this source discrepancy; do not silently rewrite REF-06.
7. **Supplementary information limitation:** REF-10's Table S1 was not included in the upload. Use only the main-text model-fit information recorded above.
8. **Temkin thermodynamics caution:** REF-09 states that Temkin fitting alone is insufficient to establish endothermic or exothermic behaviour; use the separate thermodynamic analysis for that conclusion.

## 7. Slide 10 content recommendation

**Title:** Adsorption Isotherms: Relating Equilibrium Concentration to Uptake

Recommended slide composition:

- A small equilibrium schematic defining \(C_e\) and \(q_e\).
- Four equation/model panels: Langmuir, Freundlich, Temkin and Sips.
- One compact comparison table:
  - REF-09: Langmuir best for TC; D–R best for CIP.
  - REF-10: best fit varies with CIP/TET and KCB/KCB-A/KCB-B.
  - REF-14: Freundlich best for CIP on activated bagasse biochar (ARE = 2.44%).
- A bottom-line teaching point: **“The best-fitting isotherm is specific to the antibiotic–adsorbent system and the experimental conditions.”**

Keep model assumptions concise on the slide; put the parameter definitions, fit statistics and source qualifications in speaker notes. Include the caution that model fit is not direct mechanistic proof.

---

## Source map

| REF-ID | PDF locator | Role in this extraction |
|---|---|---|
| REF-06 | PDF p. 2 | Langmuir, Freundlich and D–R descriptions; Langmuir separation factor |
| REF-06 | PDF p. 3 | Temkin assumptions, equation and intermediate-concentration qualification |
| REF-06 | PDF pp. 4–5 | Redlich–Peterson and Sips model descriptions and limiting behaviour |
| REF-06 | PDF pp. 7–8 | Linearisation bias, nonlinear regression and error-function comparison |
| REF-09 | PDF p. 6 | Author interpretation of TC Langmuir and CIP D–R model fits; Temkin thermodynamic caution |
| REF-09 | PDF p. 7, Table 2 | Fitted parameters and \(R^2\)/standard-deviation statistics for TC and CIP |
| REF-10 | PDF pp. 5–7 | Model rankings for CIP/TET on KCB, KCB-A and KCB-B; reported Langmuir monolayer capacities; three-parameter model findings |
| REF-10 | PDF p. 7, ESI Table S1 cited by article | Full three-parameter model table is not present in the uploaded source set; no missing parameters inferred |
| REF-14 | PDF p. 6, Table 2 | Langmuir, Freundlich, Sips, Redlich–Peterson and Toth equations; parameter definitions; nonlinear regression and ARE |
| REF-14 | PDF pp. 11–12, Figure 7 and Table 4 | Experimental CPX isotherm, fitted parameters and ARE model comparison |

**Next Stage 2 extraction:** adsorption kinetics (slide 11), followed by thermodynamics, regeneration and economics. Do not add references or begin PowerPoint production before the full extraction/evidence review is complete.
