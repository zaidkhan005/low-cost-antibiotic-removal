# Stage 2 Extraction 04 — Adsorption Kinetics

**Status:** Source-grounded extraction completed for slide 11.  
**Source boundary:** Fixed 15-paper collection only. REF-07 is the methodological review; antibiotic-specific experimental comparisons use REF-09, REF-10 and REF-14. REF-10's kinetic supplementary table was not supplied, so unavailable parameter values are not inferred.  
**Use:** Scientific foundation and slide-content preparation, not final slide copy.

---

## 1. What adsorption kinetics describes

Adsorption kinetics concerns how rapidly the uptake of an adsorbate changes with contact time and helps identify the slowest step that may control the overall process. REF-07 explains the liquid-phase adsorption sequence as:

1. Transport of adsorbate through the bulk liquid.
2. Diffusion through the liquid film at the solid–liquid interface.
3. Diffusion through pores within the adsorbent particle.
4. Surface reaction/interactions between adsorbate and adsorbent.

The slowest of the relevant steps can control the observed overall rate (REF-07, PDF p. 2). The kinetic experiment therefore provides rate and process-design information. It does not, on its own, identify the chemical nature of the surface interaction.

The principal measured/derived quantity is the uptake at time \(t\):

\[
q_t=\frac{(C_0-C_t)V}{m}
\]

for constant liquid volume, where \(C_0\) and \(C_t\) are the initial and time-\(t\) liquid concentrations, \(V\) is solution volume and \(m\) is adsorbent mass. For a volume that changes during sampling, use the volume-aware balance:

\[
q_t=\frac{C_0V_0-C_tV_t}{m}
\]

This extraction uses the time-dependent uptake already defined and cross-checked in Stage 2 Pass 2 (REF-14, PDF p. 4). Use consistent units and do not label an arbitrary time point as equilibrium uptake \(q_e\).

## 2. Four kinetic models approved for slide 11

The equations below are expressed in common nonlinear forms. The time unit used in the fitted rate constant must match the time unit used for \(t\). Parameter units also depend on the units used for \(q_t\) and \(q_e\).

### 2.1 Pseudo-first-order (PFO / PS1)

Differential form:

\[
\frac{dq_t}{dt}=k_1(q_e-q_t)
\]

Integrated nonlinear form:

\[
q_t=q_e\left(1-e^{-k_1t}\right)
\]

where:
- \(q_t\) = uptake at time \(t\) (mg g\(^{-1}\));
- \(q_e\) = fitted equilibrium uptake (mg g\(^{-1}\));
- \(k_1\) = pseudo-first-order rate constant (time\(^{-1}\)).

REF-07 identifies this as the Lagergren first-order equation and presents it as an adaptation of reaction-kinetic equations for heterogeneous adsorption systems (PDF p. 5).

**Interpretive caution:** Although it is often called a surface-reaction model, REF-07 explains that PFO can also approximate diffusion-related behaviour under some conditions, particularly close to equilibrium. A PFO fit is therefore not proof of a particular reaction or diffusion mechanism (REF-07, PDF pp. 5–6).

### 2.2 Pseudo-second-order (PSO / PS2)

Differential form:

\[
\frac{dq_t}{dt}=k_2(q_e-q_t)^2
\]

Integrated nonlinear form:

\[
q_t=\frac{k_2q_e^2t}{1+k_2q_et}
\]

where:
- \(q_e\) = fitted equilibrium uptake (mg g\(^{-1}\));
- \(k_2\) = pseudo-second-order rate constant (commonly g mg\(^{-1}\) time\(^{-1}\) with uptake in mg g\(^{-1}\));
- \(t\) = contact time.

REF-07 traces the model to an adaptation of second-order reaction kinetics for adsorption capacity on a solid and discusses conditions under which it can be derived from surface-reaction models (PDF pp. 3–4).

**Interpretive caution:** PSO can fit data originating from surface-reaction-controlled systems and from diffusion-controlled systems. REF-07 explicitly concludes that PSO is not associated with one unique adsorption mechanism and that a best PSO fit does not establish chemisorption (PDF pp. 4–5).

### 2.3 Weber–Morris intraparticle-diffusion model

\[
q_t=k_{\mathrm{WM}}t^{1/2}+C
\]

where:
- \(k_{\mathrm{WM}}\) = intraparticle-diffusion rate parameter (mg g\(^{-1}\) time\(^{-1/2}\));
- \(C\) = intercept (mg g\(^{-1}\)), associated in many experimental papers with the contribution of the boundary layer. Vareda (2023) writes the corresponding constant as \(E\) in Eq. (21), while REF-09, REF-10 and REF-14 use \(C\) or step-specific \(C_i\).

**Notation note:** The symbols \(C\) and \(E\) here denote the intercept term in the Weber–Morris linear relation; preserve the notation used by the paper when reproducing a particular study's fitted parameters.

A plot of \(q_t\) against \(t^{1/2}\) is interpreted by examining its shape, linear regions and intercept. Multiple linear regions can indicate multiple transport stages. A line that passes through the origin is consistent with intraparticle diffusion being the sole rate-limiting step under the model's assumptions; a nonzero intercept indicates that intraparticle diffusion alone does not account for the overall kinetics.

REF-07 gives the Weber–Morris form and relates its intercept to boundary-layer contribution (PDF p. 6). REF-09 and REF-10 also use the origin/intercept interpretation in their experimental discussion (REF-09, PDF p. 5; REF-10, PDF p. 8).

**Caution:** A Weber–Morris plot is an empirical diagnostic, not a complete transport model. Do not interpret one linear segment or a nonzero intercept as a unique microscopic mechanism.

### 2.4 Elovich model

A common integrated form is:

\[
q_t=\frac{1}{\beta}\ln(1+\alpha\beta t)
\]

where:
- \(\alpha\) = initial adsorption rate parameter;
- \(\beta\) = Elovich parameter associated with the rate's decrease as surface coverage develops.

REF-07 describes Elovich as a model used for chemisorption kinetics on heterogeneous surfaces; its assumed declining rate is associated with increasing surface coverage. However, the model neglects simultaneous desorption and can behave non-physically at long contact times. The author therefore states that it is applicable far from equilibrium (REF-07, PDF p. 6).

**Caution:** A good Elovich fit is not independent proof of chemisorption. Interpret it together with the model's assumptions, concentration–time curve and other evidence.

## 3. How the selected antibiotic studies use kinetic models

### 3.1 REF-09 — Tetracycline and ciprofloxacin on raw date-palm fibre

The study compared PFO, PSO and Weber–Morris plots (REF-09, PDF pp. 5–6; Figure 6 and Table 1). The kinetic plot conditions specify initial TC concentration of 80 mg L\(^{-1}\), initial CIP concentration of 150 mg L\(^{-1}\), and temperature of 298 K (REF-09, PDF p. 5, Figure 6).

**Reported PFO and PSO parameters (REF-09, PDF p. 6, Table 1)**

| Model/parameter | Tetracycline | Ciprofloxacin |
|---|---:|---:|
| PFO \(k_1\) (min\(^{-1}\)) | 0.029 | 0.052 |
| PFO \(R^2\) | 0.866 | 0.996 |
| PFO \(S_{y.x}\) | 0.502 | 0.154 |
| PSO \(k_2\) (g mg\(^{-1}\) min\(^{-1}\)) | 0.0021 | 0.0063 |
| PSO \(R^2\) | 0.989 | 0.999 |
| PSO \(S_{y.x}\) | 0.24 | 0.02 |

The authors report higher \(R^2\) and lower residual standard deviation for PSO than PFO for both antibiotics, and they interpret this as evidence of chemisorption/chemical interactions (REF-09, PDF p. 5). **This mechanistic inference must be presented as the authors' interpretation, not as a conclusion established by the PSO model alone.** REF-07's later methodological review shows why the model fit does not independently prove that interpretation.

The Weber–Morris plots show multiple linear regions (REF-09, PDF pp. 5–6, Figure 6 and Table 1). The authors interpret the initial steeper region as external/random adsorption, later regions as likely intraparticle-diffusion control, and the final region as a gradual approach to equilibrium. They state that a single intraparticle-diffusion step does not describe the complete process (REF-09, PDF p. 5).

The article's preceding concentration/time discussion reports equilibrium after approximately 120 min for TC and 90 min for CIP under the tested date-palm-fibre conditions (REF-09, PDF p. 3, Section 3.2). These times are study-specific and must not be generalised to other adsorbents or initial concentrations.

### 3.2 REF-10 — CIP and TET on hybrid kaolinite/coconut-husk biochar

The study compares PFO, PSO, intraparticle diffusion and Brouers–Sotolongo fractal kinetics across KCB, acid-activated KCB-A and alkali-activated KCB-B (REF-10, PDF pp. 7–8).

The authors report that most CIP and TET adsorption occurred within the first 15 minutes (REF-10, PDF p. 7, Section 3.2.3). Their reported best-fit assignments are:

- **PFO:** CIP on KCB and KCB-B; TET on KCB-A and KCB-B.
- **PSO:** CIP on KCB-A; TET on KCB.

The authors discuss PFO as fitting the initial 20–30 minutes and PSO as describing a broader time range for the relevant systems. They interpret some PSO fits as chemisorption (REF-10, PDF p. 7). This is an author interpretation and must be qualified using REF-07: PFO/PSO model selection alone does not distinguish surface reaction from diffusion.

The REF-10 authors also report that intraparticle-diffusion lines did not pass through the origin. They conclude that intraparticle diffusion alone was not the sole rate-limiting step and that surface diffusion could also contribute. They associate the intercept \(C\) with boundary-layer thickness (REF-10, PDF p. 8).

**Evidence limitation:** Detailed kinetic model parameters are in Table S2 of the Supporting Information, which was not supplied in the uploaded source set. The main text identifies model rankings and qualitative findings but does not provide the full parameter table. No missing rate constants, fitted capacities or error statistics are inferred.

### 3.3 REF-14 — Ciprofloxacin on K2CO3-activated barley-bagasse biochar

The study reports a multistep uptake curve and more than three days of contact time to reach equilibrium under the investigated conditions (REF-14, PDF p. 9, Section 3.3). Figure 4 conditions are 25 °C, pH 3.5, sorbent dose 0.5 g L\(^{-1}\), and initial CIP concentration 300 mg L\(^{-1}\) (REF-14, PDF p. 9).

Five models were fitted: PFO, PSO, Elovich, intraparticle diffusion and Bangham (REF-14, PDF pp. 9–10, Table 3).

**Reported kinetic parameters and average relative errors (REF-14, PDF p. 10, Table 3)**

| Model | Fitted \(q_e\) or parameter | ARE (%) |
|---|---:|---:|
| PFO | \(q_e=77.7\) mg g\(^{-1}\); \(k'_1=0.0057\) min\(^{-1}\) | 12.40 |
| PSO | \(q_e=82.92\) mg g\(^{-1}\); \(k'_2=0.0001\) g mg\(^{-1}\) min\(^{-1}\) | 7.62 |
| Elovich | \(\alpha=5.50\) mg g\(^{-1}\) min\(^{-1}\); \(\beta=0.087\) g mg\(^{-1}\) | 2.52 |
| Intraparticle diffusion | \(k_d=0.81\) mg g\(^{-1}\) min\(^{-1/2}\); \(C=38.81\) mg g\(^{-1}\) | 7.33 |
| Bangham | \(k_B=0.059\) L g\(^{-1}\); \(\sigma=0.21\) | 3.17 |

The lowest ARE is for Elovich (2.52%), followed by Bangham (3.17%). Thus, under the paper's stated ARE criterion, Elovich and Bangham describe the data better than PFO, PSO and the single intraparticle-diffusion fit (REF-14, PDF p. 10).

The intraparticle-diffusion plot has two linear zones. The first, steeper zone is attributed to transport through the boundary layer to the external surface; the second, less steep zone is associated with diffusion through micropores and mesopores. The nonzero intercept and two-zone pattern indicate that the complete process is not controlled by intraparticle diffusion alone (REF-14, PDF pp. 10–11, Figure 5 and discussion).

**Interpretive qualification:** REF-14 describes Elovich/Bangham fits in terms of complex adsorption and pore diffusion. REF-07 cautions that Elovich itself has limits near equilibrium and that its fit alone does not establish chemisorption. Present REF-14's result as a statistical model comparison and its mechanistic discussion as the authors' interpretation.

## 4. Equilibrium time: why it is not a universal material constant

The selected studies illustrate the wide variation in observed contact time:

| Study | Antibiotic/material | Reported time behaviour | Source |
|---|---|---|---|
| REF-09 | TC and CIP on raw date-palm fibre | About 120 min for TC and 90 min for CIP | PDF p. 3 |
| REF-10 | CIP/TET on hybrid biochar | Most adsorption in first 15 min | PDF p. 7 |
| REF-14 | CIP on activated bagasse biochar | More than 3 days to equilibrium | PDF p. 9 |

These results must not be treated as a direct ranking of materials because the studies differ in adsorbent, antibiotic, concentration, pH, dose, particle properties and experimental setup. REF-14 explicitly notes that equilibrium time varies with adsorbate/adsorbent nature, particle size and initial concentration (PDF p. 9).

For engineering design, the practical implication is that the contact time must be established experimentally for the particular adsorbent–antibiotic system and target treatment conditions.

## 5. Model fitting and interpretation safeguards from REF-07

### 5.1 Linear regression can bias model choice

REF-07 reports that linearised regression can favour PSO, even for simulated data generated from PFO. Linearisation can also distort estimated parameters, particularly the PFO equilibrium uptake (PDF pp. 7–9). A high linearised \(R^2\) therefore does not guarantee a good fit to the original nonlinear uptake-versus-time curve.

### 5.2 Nonlinear regression and model-selection criteria

REF-07 recommends nonlinear regression on the original equations and discusses:
- Akaike Information Criterion (AIC);
- Bayesian Information Criterion (BIC).

For these information criteria, lower values are preferred. They account for the number of data points and model parameters, allowing comparison of models with different parameter counts (REF-07, PDF pp. 7–8).

REF-07 states that \(R^2\) is not a valid general goodness-of-fit criterion for nonlinear regression (PDF p. 7). Thus, the preferred reporting practice is to show the fitted kinetic curve over the original experimental \(q_t\)-versus-\(t\) data and use appropriate residual/error and information criteria.

### 5.3 Data selection

REF-07 warns that including points after equilibrium can artificially enhance correlation, especially for linearised regression. Data points after equilibrium should not be used to fit the kinetic model (PDF pp. 3 and 7).

### 5.4 Do not equate a model with a mechanism

- A better PFO fit does not automatically mean diffusion control.
- A better PSO fit does not automatically mean chemisorption.
- A Weber–Morris line that does not pass through the origin indicates that intraparticle diffusion alone does not explain the full kinetic curve under that model.
- Elovich is intended for the far-from-equilibrium region in REF-07's analysis; its neglect of simultaneous desorption limits long-time interpretation.
- Kinetic fits should be considered alongside thermodynamic analysis and evidence from characterisation of the loaded adsorbent if the goal is to discuss mechanism (REF-07, PDF pp. 2, 4–6).

## 6. Slide 11 content recommendation

**Title:** Adsorption Kinetics: How Fast Does Adsorption Occur?

Recommended sequence:

1. **Show the uptake curve:** \(q_t\) against contact time, rising rapidly at first and then approaching a plateau.
2. **Explain the four models:** compact equation cards for PFO, PSO, Weber–Morris and Elovich, with the key fitted parameters.
3. **Show the transport stages:** bulk → boundary film → external surface → intraparticle pores → adsorption sites.
4. **Compare the selected antibiotic studies:** REF-09 (PSO preferred by authors; multiple Weber–Morris regions), REF-10 (model ranking varies by antibiotic/material; most uptake in 15 min), REF-14 (Elovich has the lowest ARE; >3 days to equilibrium).
5. **Close with a scientific caution:** “A kinetic model describes the shape/rate of uptake; its best fit alone does not prove the molecular adsorption mechanism.”

Keep the equation definitions concise on the slide and put model assumptions, detailed constants and fit criteria in speaker notes. State that the examples have different conditions and are not a controlled head-to-head comparison.

---

## Source map

| REF-ID | PDF locator | Role in this extraction |
|---|---|---|
| REF-07 | PDF p. 2 | Sequence of liquid-phase adsorption steps; scope and limitations of kinetic-model inference |
| REF-07 | PDF pp. 3–5 | PSO and PFO equations, derivations, conditions and ambiguity between surface-reaction and diffusion-controlled behaviour |
| REF-07 | PDF p. 6 | Boyd, Weber–Morris and Elovich models; boundary/intercept interpretation and Elovich limitations |
| REF-07 | PDF pp. 7–9 | Linearisation bias, post-equilibrium data warning, nonlinear fit, AIC/BIC and case comparisons |
| REF-09 | PDF p. 3, Section 3.2 | Contact time and approximate equilibrium times for TC and CIP |
| REF-09 | PDF p. 5, Figure 6 and kinetic discussion | PFO/PSO/Weber–Morris comparison and authors' interpretation |
| REF-09 | PDF p. 6, Table 1 | PFO, PSO and three-region Weber–Morris kinetic parameters |
| REF-10 | PDF pp. 7–8, Section 3.2.3 and Figure 8 | Relative speed, PFO/PSO model assignments, intraparticle diffusion interpretation |
| REF-10 | ESI Table S2 cited in PDF p. 7 | Full kinetic parameter table unavailable in uploaded source set; no missing values inferred |
| REF-14 | PDF p. 9, Section 3.3 and Figure 4 | Experimental uptake curve and equilibrium time |
| REF-14 | PDF pp. 9–10, Table 3 and Figure 5 | PFO, PSO, Elovich, intraparticle-diffusion and Bangham parameter/error comparison; multistep diffusion interpretation |

**Next Stage 2 extraction:** thermodynamics of adsorption (slide 12), followed by regeneration/reusability (slide 13) and economics/practical feasibility (slide 14). Do not add references or begin PowerPoint production before the extraction and evidence review are complete.
