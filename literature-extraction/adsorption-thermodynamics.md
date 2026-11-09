# Stage 2 Extraction 05 — Thermodynamics of Adsorption

**Status:** Source-grounded extraction completed for slide 12.  
**Source boundary:** Fixed 15-paper collection only. The strongest numerical thermodynamic evidence is REF-13. REF-09 refers to thermodynamic results in its Supporting Information, which was not supplied. REF-14 and REF-15 report temperature effects; REF-12 mentions thermodynamic experiments but the main PDF does not provide accessible thermodynamic results. No outside references or inferred values are added.  
**Use:** Scientific foundation and slide-content preparation, not final slide copy.

---

## 1. What thermodynamics contributes

Adsorption thermodynamics examines the energy and equilibrium favourability of the adsorbate–adsorbent process as temperature changes. In contrast to kinetic models, which describe uptake as a function of time, thermodynamic parameters are used to discuss:

- whether adsorption is thermodynamically favourable under the defined conditions;
- whether the process absorbs or releases heat;
- the associated entropy change of the system.

The central quantities used in the selected experimental source REF-13 are Gibbs free-energy change (\(\Delta G\)), enthalpy change (\(\Delta H\)) and entropy change (\(\Delta S\)) (REF-13, PDF pp. 9–10, Section 3.5).

**Important boundary:** Thermodynamic favourability is not equivalent to high adsorption capacity, fast kinetics, complete removal, or practical economic feasibility. These are different performance dimensions and must not be treated as interchangeable.

## 2. Equations reported in the selected source

REF-13 reports the following equations in its thermodynamics section (PDF pp. 9–10, Eqs. 5–7):

### 2.1 Gibbs free-energy relationship

\[
\Delta G^\circ=-RT\ln K_d
\]

where:
- \(\Delta G^\circ\) = standard Gibbs free-energy change;
- \(R\) = universal gas constant, reported as \(8.314\ \mathrm{J\,mol^{-1}\,K^{-1}}\);
- \(T\) = absolute temperature in kelvin;
- \(K_d\) = the adsorption distribution/equilibrium quantity used by the authors.

The source prints the equilibrium term as \(K_d\). Its main-text discussion does not clearly specify the operational definition and standard-state normalisation of \(K_d\), and the cited Table S4 with the calculated values was not included in the supplied PDF set. The formula can therefore be documented as the authors' reported relationship, but the reported numerical free energies should not be independently reconstructed from incomplete information.

### 2.2 Gibbs–Helmholtz relation used in the study

\[
\Delta G^\circ=\Delta H^\circ-T\Delta S^\circ
\]

This relates the Gibbs free-energy change to enthalpy and entropy at the specified temperature.

### 2.3 Van't Hoff relationship

\[
\ln K_d=-\frac{\Delta H^\circ}{RT}+\frac{\Delta S^\circ}{R}
\]

When \(\ln K_d\) is plotted against \(1/T\):
- slope \(=-\Delta H^\circ/R\);
- intercept \(=\Delta S^\circ/R\).

These slope/intercept relationships follow algebraically from the equation above. A thermodynamic calculation needs multiple temperature points and a consistently defined equilibrium quantity.

### 2.4 Sign interpretation

Under the thermodynamic convention used by the authors:

| Parameter | Sign | Interpretation |
|---|---|---|
| \(\Delta G^\circ\) | Negative | Adsorption is thermodynamically spontaneous/favourable under the stated conditions |
| \(\Delta G^\circ\) | Positive | Adsorption is non-spontaneous under the stated conditions |
| \(\Delta H^\circ\) | Positive | Endothermic; heat is absorbed |
| \(\Delta H^\circ\) | Negative | Exothermic; heat is released |
| \(\Delta S^\circ\) | Positive | Positive entropy change under the study's convention |
| \(\Delta S^\circ\) | Negative | Negative entropy change under the study's convention |

“Spontaneous” does not mean instantaneous; the rate is addressed by kinetic experiments. A process can be thermodynamically favourable and still require long contact time.

## 3. Unit and standard-state checks

Thermodynamic equations require consistent units:
- Use absolute temperature in kelvin, not degrees Celsius, in the equations.
- If \(R=8.314\ \mathrm{J\,mol^{-1}\,K^{-1}}\), express \(\Delta H^\circ\) in J mol\(^{-1}\) and \(\Delta S^\circ\) in J mol\(^{-1}\) K\(^{-1}\), or convert all terms consistently to kJ-based units.
- The argument of a natural logarithm in a thermodynamic equilibrium expression must be dimensionless. A distribution coefficient reported with units cannot be inserted into \(\ln K\) without a stated standard-state normalisation.

**Source-specific data-quality flag — REF-09:** The symbols list identifies \(K_D\) as a distribution coefficient with units of L g\(^{-1}\) (PDF p. 7), while the supporting equations for thermodynamic parameters are located in Supporting Information Section S1, which was not supplied. This means its standard-state normalisation cannot be checked from the available files. The main paper's reported qualitative endothermic conclusion may be cited as the authors' result, but its missing numerical thermodynamic parameters should not be recreated.

**Source-specific data-quality flag — REF-13:** The main text uses \(K_d\) in logarithmic thermodynamic expressions but does not clearly state its operational definition or standard-state normalisation in the inspected pages. The numerical thermodynamic values are referred to Table S4, which was not included in the supplied PDF. Only the numerical values explicitly stated in the main text are retained below.

Do not compare \(\Delta G^\circ\), \(\Delta H^\circ\) or \(\Delta S^\circ\) from different papers unless the equilibrium-constant definitions, units, standard states, concentration basis and experimental conditions are compatible.

## 4. Evidence from the selected antibiotic-adsorption studies

### 4.1 REF-13 — Tetracycline on sawdust biochar, NiFe\(_2\)O\(_4\), and NiFe\(_2\)O\(_4\)/biochar

REF-13 studied tetracycline adsorption on three materials: sawdust-derived biochar (BC), nickel ferrite (NFO) and the magnetic NFO/BC composite. Its thermodynamics section presents the three equations above and states that measurements/calculations were made at three temperatures (PDF pp. 9–10, Section 3.5).

The main text reports:

- All three TC adsorption processes had negative \(\Delta G\) values, which the authors interpret as spontaneous adsorption.
- The absolute \(\Delta G\) value for NFO/BC was greater than for BC and NFO at each investigated temperature, interpreted by the authors as a stronger adsorption driving force for the composite.
- For BC and NFO/BC, the absolute \(\Delta G\) value increased as reaction temperature increased. NFO showed the opposite trend.
- The authors identify TC adsorption on NFO as exothermic, whereas adsorption on BC and NFO/BC is endothermic.
- The main text explicitly gives \(\Delta H=+31.384\ \mathrm{kJ\,mol^{-1}}\) for NFO/BC. It also says this exceeds the authors' cited \(20.9\ \mathrm{kJ\,mol^{-1}}\) threshold and therefore classifies the process as chemically dominated.
- The authors describe \(\Delta S\) for NFO/BC as positive.

**Limitations:** Table S4, which contains the temperature-dependent numerical thermodynamic parameters, is not present in the supplied main-paper PDF. Exact \(\Delta G\) values at each temperature and the numerical \(\Delta S\) value must therefore remain unreported. The paper's enthalpy threshold is the authors' interpretation; it should not be presented as a universal diagnostic for physical versus chemical adsorption.

Locator: REF-13, PDF pp. 9–10, Section 3.5, Eqs. (5)–(7), and the paragraph immediately before Section 3.6.

### 4.2 REF-09 — Tetracycline and ciprofloxacin on raw date-palm fibre

REF-09 fitted the Temkin isotherm and notes that positive \(b_T\) values might suggest an exothermic interpretation under the Temkin assumption. However, the authors explicitly state that the Temkin model alone is insufficient to determine whether adsorption is endothermic or exothermic. They refer to a separate thermodynamic study in Supporting Information Section S3, which they say confirmed endothermic adsorption for the studied antibiotics on date-palm fibre (REF-09, PDF p. 6).

**Limitation:** The supporting information was not supplied. Therefore:
- retain only the qualitative author-reported endothermic conclusion;
- do not report numerical \(\Delta G\), \(\Delta H\) or \(\Delta S\) values;
- do not infer endothermicity from the Temkin \(b_T\) value alone.

The REF-09 symbols list gives \(K_D\) units of L g\(^{-1}\) (PDF p. 7). Because the thermodynamic equations are in the missing SI, the standard-state treatment cannot be verified from the supplied file.

**Do not confuse parameters:** REF-09 also reports Dubinin–Radushkevich mean adsorption-energy parameter \(E\) values of 0.247 kJ mol\(^{-1}\) for TC and 0.157 kJ mol\(^{-1}\) for CIP (PDF p. 7, Table 2). These are isotherm-derived energy parameters, not the thermodynamic enthalpy change \(\Delta H^\circ\).

### 4.3 REF-14 — Ciprofloxacin on K\(_2\)CO\(_3\)-activated barley-bagasse biochar

REF-14 examined the effect of temperature at pH 3.5 using 0.025 g of activated biochar with 50 mL of 300 mg L\(^{-1}\) CPX solution, with 72 h contact time. The study tested 10, 25, 40 and 55 °C (REF-14, PDF p. 5, Section 2.4).

The paper reports that equilibrium uptake increased with temperature:

| Temperature | Reported \(q_e\) |
|---:|---:|
| 10 °C | 34.6 mg g\(^{-1}\) |
| 25 °C | 41.4 mg g\(^{-1}\) |
| 40 °C | 89.3 mg g\(^{-1}\) |
| 55 °C | 109.9 mg g\(^{-1}\) |

Source: REF-14, PDF p. 9, Section 3.2, temperature-effect discussion.

The authors interpret the rise in uptake as evidence that adsorption is favoured by increasing temperature and is endothermic. This is a temperature-response result; the main paper does not provide a numerical \(\Delta G^\circ\), \(\Delta H^\circ\) or \(\Delta S^\circ\) table. Do not calculate these values from the four uptake values alone.

### 4.4 REF-15 — Tetracycline on fermentation-residue-derived porous biochar

REF-15 reports that the adsorption capacity of OSOB-3-700 increased as reaction temperature rose; the authors interpret this as an endothermic adsorption process (REF-15, PDF p. 11, Section 3.3.4).

Its temperature-dependent Langmuir table reports fitted \(q_m\) values:

| Temperature | Langmuir-fitted \(q_m\) |
|---:|---:|
| 298 K | 1096.871 mg g\(^{-1}\) |
| 308 K | 1270.712 mg g\(^{-1}\) |
| 318 K | 1830.624 mg g\(^{-1}\) |

Source: REF-15, PDF p. 13, Table 6.

These are model-fitted Langmuir maximum-capacity parameters, not direct measurements of \(\Delta H^\circ\), \(\Delta G^\circ\) or \(\Delta S^\circ\). The article's conclusion describes the process as endothermic, but the main PDF does not provide a numerical thermodynamic-parameter table. Do not infer a numerical enthalpy from the Langmuir \(q_m\) trend.

### 4.5 REF-12 — Oxytetracycline and ciprofloxacin on magnetic cotton-husk biochar

REF-12 states in its experimental description that adsorption experiments included thermodynamics, and that experiments were performed in triplicate (REF-12, PDF p. 3, Section 2.3). However, the supplied main-paper PDF pages inspected do not present a thermodynamic parameter table or accessible numerical \(\Delta G\), \(\Delta H\) or \(\Delta S\) results.

The paper's main text gives operating conditions for pH, kinetics, isotherms and regeneration (PDF pp. 3–4), but those should not be repurposed as thermodynamic evidence. Any detailed thermodynamic results not present in the supplied PDF remain unavailable for this extraction.

## 5. Cross-study comparison — what the evidence does and does not show

| Study | Antibiotic / adsorbent | Temperature evidence | Reported thermodynamic result | Evidence limitation |
|---|---|---|---|---|
| REF-09 | TC and CIP / raw date-palm fibre | Separate thermodynamic study cited | Authors report endothermicity | SI containing equations and numerical values not supplied |
| REF-12 | OTC and CIP / magnetic cotton-husk biochar | Thermodynamics mentioned in study methods | No accessible numerical result in supplied main PDF | Detailed result not located in supplied paper |
| REF-13 | TC / BC, NFO and NFO/BC | Three temperatures | All reported \(\Delta G\) negative; BC/NFO-BC endothermic; NFO exothermic; NFO/BC \(\Delta H=+31.384\) kJ mol\(^{-1}\); positive \(\Delta S\) for NFO/BC | Table S4 absent; \(K_d\) definition/standard state unclear in main text |
| REF-14 | CIP / K\(_2\)CO\(_3\)-activated bagasse biochar | \(q_e\) rises from 34.6 to 109.9 mg g\(^{-1}\) across 10–55 °C | Authors report endothermic adsorption | No numerical \(\Delta G\), \(\Delta H\), \(\Delta S\) table in main paper |
| REF-15 | TC / OSOB-3-700 porous biochar | Temperature-dependent uptake and fitted Langmuir \(q_m\) rise from 298–318 K | Authors report endothermic adsorption | \(q_m\) values are model fits, not thermodynamic parameters |

The collection demonstrates that temperature effects are material-specific: REF-13 reports opposite heat effects for NFO compared with BC and NFO/BC, while REF-09, REF-14 and REF-15 describe endothermic uptake for their tested adsorbent–antibiotic systems. Do not state that all antibiotic adsorption is universally endothermic.

## 6. Thermodynamics and mechanism: limits on inference

1. A negative \(\Delta G^\circ\) supports thermodynamic favourability under the stated conditions; it does not specify the rate or prove a particular molecular adsorption mechanism.
2. A positive \(\Delta H^\circ\) indicates an endothermic process; it is not, by itself, proof of chemisorption.
3. An increase in uptake with temperature is consistent with an endothermic trend in the studied system, but it does not provide a numerical \(\Delta H^\circ\) without a defined equilibrium constant and an appropriate thermodynamic analysis.
4. \(\Delta S^\circ\) is a system-level thermodynamic quantity; the sign should be interpreted only with the study's equilibrium definition and convention.
5. The magnitude thresholds used by individual authors to label “physical” or “chemical” adsorption should be reported as that paper's interpretation rather than universal rules.
6. Keep the isotherm parameter \(E\) from the D–R model distinct from thermodynamic enthalpy \(\Delta H^\circ\).
7. Do not compare thermodynamic values across papers when equilibrium-constant definitions, standard-state normalisations, units, temperatures or concentration bases are unavailable or inconsistent.

## 7. Slide 12 content recommendation

**Title:** Thermodynamics of Adsorption — Is the Process Favourable?

Recommended sequence:

1. Introduce \(\Delta G^\circ\), \(\Delta H^\circ\) and \(\Delta S^\circ\) with their signs and units.
2. Present the Gibbs equation and the Van't Hoff relationship.
3. Explain a Van't Hoff plot: \(\ln K\) against \(1/T\), with slope \(-\Delta H^\circ/R\) and intercept \(\Delta S^\circ/R\).
4. Use REF-13 as the numerical example: all three TC adsorption systems reported spontaneous; NFO/BC had \(\Delta H=+31.384\) kJ mol\(^{-1}\), while NFO was exothermic and BC/NFO-BC were endothermic.
5. Use REF-14 as the clearest observed temperature-response example: CIP \(q_e\) increases from 34.6 to 109.9 mg g\(^{-1}\) between 10 and 55 °C under the stated test conditions.
6. Add a small source note that REF-09 and REF-15 also report endothermic trends, but their full thermodynamic parameter tables are unavailable in the supplied PDFs.
7. Close with the caution: “Thermodynamic signs describe favourability and heat effects under stated conditions; they do not, by themselves, prove a molecular adsorption mechanism.”

**Slide-density note:** Keep the three parameters, sign interpretation and one Van't Hoff plot prominent. Present the study comparison in a compact callout/table. Put missing supplementary details and standard-state cautions in speaker notes.

---

## Source map

| REF-ID | PDF locator | Role in this extraction |
|---|---|---|
| REF-13 | PDF pp. 9–10, Section 3.5, Eqs. (5)–(7) | Gibbs, enthalpy, entropy and Van't Hoff equations; reported spontaneity and heat-effect comparisons |
| REF-13 | PDF p. 10, paragraph before Section 3.6 | NFO/BC \(\Delta H=+31.384\) kJ mol\(^{-1}\), qualitative entropy and adsorbent-dependent endo/exothermic findings; Table S4 is unavailable |
| REF-09 | PDF p. 6, Section 3.5 and Temkin discussion | Authors state Temkin alone cannot determine heat effect; separate SI thermodynamics reportedly confirmed endothermicity |
| REF-09 | PDF p. 7, symbols list and Table 2 | \(K_D\) listed with L g\(^{-1}\) units; D–R energy \(E\) distinguished from thermodynamic enthalpy |
| REF-14 | PDF p. 5, Section 2.4 | Temperature experiment conditions: pH 3.5, 0.025 g adsorbent, 50 mL, 300 mg L\(^{-1}\) CPX, 72 h, four temperatures |
| REF-14 | PDF p. 9, Section 3.2 | Temperature-dependent equilibrium uptake and authors' endothermic interpretation |
| REF-15 | PDF p. 11, Section 3.3.4 | Temperature-related increase in adsorption capacity; authors' endothermic interpretation |
| REF-15 | PDF p. 13, Table 6 | Temperature-dependent Langmuir-fitted \(q_m\) values |
| REF-12 | PDF p. 3, Section 2.3 | Thermodynamics named among experimental studies, but no accessible numerical thermodynamic result in the supplied main PDF |

**Next Stage 2 extraction:** regeneration and reusability (slide 13), followed by economics and practical feasibility (slide 14). Do not add references or begin PowerPoint production before the extraction and evidence review are complete.
