# Stage 2 Extraction 06 — Regeneration and Reusability

**Status:** Source-grounded extraction completed for slide 13.  
**Source boundary:** Fixed 15-paper collection only. Primary experimental evidence is drawn from REF-11, REF-12, REF-13 and REF-15. REF-14 records an explicit regeneration/reuse research gap. Methodological and practical context is drawn from the antibiotic review REF-02 and the broader wastewater/pharmaceutical reviews REF-03 and REF-08. REF-03 and REF-08 are not antibiotic-specific; their general observations are labelled accordingly.  
**Use:** Scientific foundation and slide-content preparation, not final slide copy.

---

## 1. Why regeneration matters

Adsorption transfers a dissolved contaminant from water onto a solid adsorbent. Once adsorption is complete, the loaded solid must be separated from the treated water. It then has to be managed by one of three routes: regeneration and reuse, recovery of the adsorbed material, or controlled treatment/disposal of the spent adsorbent.

Regeneration and reusability matter because a material that has a high initial adsorption capacity may still be impractical if it loses capacity rapidly, cannot be recovered from water, or needs expensive and environmentally burdensome treatment before each reuse cycle. REF-02 describes regeneration as involving adsorbate decomposition or adsorbate desorption and emphasises recycling/reuse for industrial applications (PDF p. 29). REF-08 states that regeneration, reusability, economic cost and environmental impact should be considered together (PDF pp. 7–8). REF-03 similarly cautions that an adsorbent may cease to be economically attractive if it is low-cost but difficult to regenerate (PDF p. 20; general wastewater adsorption context).

## 2. Distinguish the three reuse metrics

These terms are related but are not interchangeable.

### 2.1 Desorption

Desorption is the release of the adsorbed antibiotic from the solid into a regenerant or eluent. It can be quantified as the fraction of the loaded mass released:

\[
\text{Desorption efficiency (\%)}=
\frac{\text{mass of antibiotic desorbed}}
{\text{mass of antibiotic loaded before desorption}}\times100
\]

This describes contaminant release, not necessarily restored adsorbent capacity.

### 2.2 Regeneration performance

Regeneration concerns whether the material can perform adsorption again after the desorption or treatment step. The most useful check is to perform another adsorption test under comparable conditions and measure the resulting adsorption capacity or removal performance.

REF-08 makes this distinction explicitly: desorption tests alone do not measure performance in a subsequent adsorption cycle, whereas regeneration efficiency reflects the adsorbent's subsequent adsorption effectiveness (PDF p. 7).

### 2.3 Capacity retention and cycle removal

When initial and reused adsorption capacities are measured under comparable conditions, capacity retention can be expressed as:

\[
\text{Capacity retention (\%)}=
\frac{q_{\text{after cycle }n}}
{q_{\text{fresh}}}\times100
\]

This is a derived comparison metric; it should only be calculated when both capacities use the same basis and comparable experimental conditions.

Removal percentage in a later cycle is a separate measure. A reported removal rate after the fourth or fifth cycle is not automatically the same as the percentage of initial adsorption capacity retained. Keep the exact quantity reported by each paper.

## 3. Regeneration approaches described in the selected sources

### 3.1 Chemical regeneration

Chemical eluents can change pH or compete with the adsorbate for binding sites, facilitating release. REF-02 discusses acid–base regeneration using acids such as HCl and soluble bases such as NaOH, as well as extraction with organic solvents (PDF p. 30). REF-08 summarises acidic, alkaline, salt, chelating-agent and solvent approaches (PDF p. 7).

The selected experimental studies demonstrate that the preferred eluent is material- and contaminant-dependent:
- REF-12 uses ethanol with ultrasound for the magnetic cotton-husk biochar composite.
- REF-13 describes deionized-water desorption for the NiFe\(_2\)O\(_4\)/biochar composite.
- REF-15 uses 0.1 M NaOH for tetracycline-loaded porous biochar.

Do not assume one regenerant is suitable for all adsorbents or antibiotic classes.

### 3.2 Solvent-assisted regeneration

REF-02 describes solvent regeneration as shifting the equilibrium between biomass, adsorbate and solvent, and lists organic solvents such as methanol, benzene and acetone as examples in its general discussion (PDF p. 30). These are examples reported in the review, not universal recommendations.

REF-12 demonstrates a combined ethanol–ultrasound procedure. REF-08 notes that organic solvents can raise toxicity, safety and environmental-management concerns, and that released contaminants and spent regenerant require appropriate handling (PDF p. 7).

### 3.3 Thermal regeneration

REF-02 describes thermal regeneration as one way to decompose carbonised adsorbate at elevated temperature and notes that high-temperature treatment may support desorption (PDF p. 29). REF-08 describes thermal regeneration of carbon adsorbents commonly at 500–800 °C under inert conditions, while noting the energy and cost challenges (PDF p. 8).

Thermal treatment should not be presented as automatically harmless to the adsorbent. Changes to material structure or functional groups may affect the next adsorption cycle. REF-08 states that no single regeneration method consistently maintains or improves adsorption efficiency for every adsorbent (PDF p. 8).

### 3.4 Other methods in the review literature

REF-08 also lists biological regeneration, advanced oxidation, ultrasound, microwave-assisted and electrochemical methods (PDF p. 8). These are review-level method categories; they are not all experimentally demonstrated for the antibiotic adsorbents in the selected primary papers.

## 4. Repeated-cycle evidence from the fixed experimental studies

### 4.1 REF-12 — Magnetic cotton-husk biochar for oxytetracycline and ciprofloxacin

REF-12 evaluates reusability of the magnetic Fe\(_2\)O\(_3\)-supported, ball-milled cotton-husk biochar composite (Fe\(_2\)O\(_3\)@BMBC). Its magnetic sensitivity facilitates separation, while the regeneration step uses ethanol with ultrasound (PDF pp. 2–3, 10–11).

**Reported regeneration procedure (REF-12, PDF pp. 3–4):**
- The used adsorbent is separated after adsorption.
- The loaded composite is placed in ethanol (0.5 L) and treated ultrasonically at 500 W for 60 min.
- The material is then washed with ultrapure water (0.5 L), separated and dried at 70 °C.
- Reuse tests are conducted for five cycles.
- The regeneration-test conditions in the method section specify 50 mg adsorbent, 20 mL antibiotic solution, initial concentration 500 mg L\(^{-1}\), 25 °C and 24 h adsorption (PDF p. 4).

**Important derived solvent-volume observation:** the stated 0.5 L ethanol volume for 50 mg adsorbent corresponds to 10 L ethanol per gram of adsorbent. The 0.5 L rinse-water volume corresponds to 10 L water per gram. These ratios are calculated directly from the reported volumes and mass; they are not a reported process-cost estimate. They illustrate why regenerant and wash-water demand should be assessed before scale-up.

**Reported results after five reuse cycles (REF-12, PDF p. 10; Fig. 7, PDF p. 11):**

| Regeneration procedure | OTC adsorption capacity remaining | CIP adsorption capacity remaining |
|---|---:|---:|
| Water washing control | 21.2% of fresh capacity | 19.7% of fresh capacity |
| Ultrasound + ethanol co-processing | 86.8% of fresh capacity | 91.1% of fresh capacity |

These values are capacity retention relative to the fresh material, as reported by the authors. They should not be relabelled as desorption efficiencies or removal percentages.

REF-12 also reports Fe leaching below 0.4 mg L\(^{-1}\) for Fe-containing biochars across the tested pH range of 3–11 (PDF p. 10, Fig. 7c and discussion). This provides evidence about material leaching under the tested pH conditions; it does not replace a full mass balance on adsorbent losses or the spent regenerant.

### 4.2 REF-13 — Tetracycline on NiFe\(_2\)O\(_4\)/biochar

REF-13 tests TC adsorption–desorption and reusability for four cycles. In the reusability subsection, the authors state that NFO/BC was separated by centrifugation and desorbed with deionized water before being returned to TC solution until adsorption saturation was reached again (PDF p. 8, Fig. 4f and Section 3.2).

The reported TC removal rate for NFO/BC remained 72% after the fourth cycle (REF-13, PDF p. 8; conclusion on PDF p. 11). This is the paper's reported removal rate after the fourth cycle; it is not explicitly reported as 72% of the initial adsorption capacity.

**Procedure-detail qualification:** the experimental-methods text also says that used adsorbent was washed to neutral with deionized water and ethanol and dried at 60 °C for the cycle test (REF-13, PDF p. 4). The reusability subsection specifically describes desorption with deionized water. The available main text does not fully clarify whether ethanol is part of the cycle regeneration protocol or an additional washing step. Preserve both statements rather than silently choosing one.

REF-13 also identifies the composite's magnetic properties as an advantage for separation in larger-scale treatment (PDF p. 8). Magnetic collection improves handling but is distinct from desorption and from proof of restored adsorption capacity.

### 4.3 REF-15 — Porous biochar derived from antibiotic fermentation residue

REF-15 investigates five consecutive adsorption–desorption cycles for tetracycline using OSOB-3-700 (PDF p. 5, Section 2.7; Figure 10 on PDF p. 14).

**Reported procedure:**
- Adsorbent dose: 0.25 g L\(^{-1}\).
- Initial TC concentration: 250 mg L\(^{-1}\).
- Shaking: 180 rpm for 24 h.
- Regeneration: 0.1 M NaOH.
- Following desorption, rinse with deionized water until pH = 7 and dry at 80 °C.

The authors report that adsorption capacity decreased only slightly over the five cycles and describe the material as having good regeneration performance (REF-15, PDF pp. 13–14, Section 3.6 and Figure 10). The text does not provide a numerical percentage of capacity retained after cycle five; do not invent one by reading an approximate value from the plotted bars.

The same discussion cites an HCl-elution example from another study in which adsorption capacity was about 50% of its initial value after treatment (REF-15, PDF p. 13). This is a literature comparison referenced by the authors, not an HCl control experiment on OSOB-3-700 in the current study.

### 4.4 REF-11 — Desorption and release from hemp waste, oak ash and mussel shell

REF-11 measures sorption and desorption of CIP, clarithromycin and trimethoprim onto hemp waste (HW), oak ash (OA) and mussel shell (MS), using batch and stirred-flow chamber experiments (PDF pp. 3–6). Its experiments show that antibiotic release depends on the adsorbent and the antibiotic.

For CIP at the highest initial concentration, desorption percentages were 22.4% for HW, 16.4% for OA and 15.5% for MS (REF-11, PDF p. 5, Section 3.2 and Table 1). The authors report that HW showed the lowest CIP desorption among the three by-products under those conditions.

This is a desorption/release study, not a repeated adsorption–desorption regeneration test. It demonstrates that antibiotic held by a by-product can be released again; it does not demonstrate how well the same material performs over several subsequent adsorption cycles.

The paper's flow-chamber release experiments are also relevant to practical risk: release from a retained solid under changing solution conditions can reintroduce an antibiotic to the flowing water (REF-11, PDF pp. 3–4 and 6, Section 3.5 and Fig. 3).

### 4.5 REF-14 — Ciprofloxacin on activated barley-bagasse biochar

REF-14 concludes that further experiments should be performed with real effluents and to investigate regeneration and reuse of the activated biochar (PDF p. 13, concluding discussion). The paper does not report a completed multi-cycle regeneration study in the supplied main PDF.

This is an evidence gap, not proof that the material cannot be regenerated.

### 4.6 REF-09 and REF-10 — What can be claimed

The supplied main PDFs for REF-09 (raw date-palm fibre) and REF-10 (kaolinite/coconut-husk hybrid biochar) do not report a completed repeated adsorption–desorption regeneration series. REF-10's ESI was not supplied, but its main text does not provide regeneration-cycle results. Do not claim reuse performance for these materials based only on their adsorption results.

## 5. What review sources add — methods, limitations and practical costs

### 5.1 REF-02 — Antibiotic-specific biomass/biochar review

REF-02 explains that biomass-based adsorbent regeneration may involve adsorbate decomposition or desorption and describes thermal and solvent regeneration routes (PDF pp. 29–30). It notes an example of magnetic biochar used for tetracycline adsorption where FTIR showed no significant band shifts and the functional groups were broadly similar after regeneration, although ash content increased slightly (PDF p. 29).

Its thermal and solvent sections provide method context, but the quantitative examples shown in those paragraphs are not all antibiotic adsorption studies. Do not present unrelated pyrene/benzopyrene thermal-retention percentages as antibiotic regeneration results.

### 5.2 REF-08 — Pharmaceutical-wide regeneration and economic review

REF-08 is broader than antibiotics alone. Its method overview covers acidic and alkaline eluents, salt solutions, chelating agents, solvents and other regeneration strategies (PDF p. 7). It states that the selection of a desorption agent affects the eluent's environmental and economic outcomes, and that released pollutants and desorbing agents require appropriate handling.

REF-08 explicitly distinguishes desorption efficiency from regeneration efficiency: a desorption test does not measure adsorption performance in the next cycle, while regeneration efficiency tests the adsorbent's subsequent removal performance (PDF p. 7).

The review identifies energy, eluent and wastewater treatment as parts of regeneration cost (PDF p. 7). It also notes that acids/alkalis may damage adsorbent structure and increase leaching risks, and that organic solvents such as methanol and benzene can raise toxicity and safety concerns (PDF pp. 7–8). No single regeneration method consistently maintains or improves capacity for every adsorbent (PDF p. 8).

### 5.3 REF-03 — General wastewater adsorbent economics

REF-03 is not antibiotic-specific, but it provides a relevant general feasibility safeguard. It states that equipment, adsorbent consumption, energy, regeneration/reactivation and spent-adsorbent disposal all enter the overall cost; a low-cost adsorbent that is difficult to regenerate may not be economically attractive (PDF p. 20).

## 6. Practical issues to show alongside cycle results

1. **Solid separation:** Magnetic collection can simplify recovery for REF-12 and REF-13, but the reported studies still use washing/centrifugation steps. Separation efficiency and adsorbent mass loss should be measured rather than assumed.
2. **Capacity decline:** Capacity can decrease because contaminant remains bound, pores or active sites remain occupied, or the regenerant alters the material. These are plausible reasons reported/discussed in the selected studies, not a universal cause for every decline.
3. **Regenerant demand:** Ethanol, acid, alkali, water, ultrasound, heating and drying all require resources. Report reagent concentration, liquid-to-solid ratio, time, energy and washing needs.
4. **Secondary liquid waste:** The antibiotic is transferred into the regenerant during desorption. That liquid must be treated, recycled or managed; it should not simply be assumed harmless.
5. **Material stability and leaching:** Monitor structural/functional-group changes and any metal or organic release, particularly for nanoparticle-bearing composites.
6. **Cycle mass balance:** Track fresh adsorbent mass, recovered mass, mass lost, adsorbed antibiotic mass, desorbed antibiotic mass, capacity after each cycle and residual antibiotic in regeneration/wash streams.
7. **Economic comparison:** Compare regenerant, energy, labour, washing, solvent recovery, corrosion control and wastewater treatment against the cost of replacing the adsorbent.

## 7. Slide 13 content recommendation

**Title:** Regeneration and Reusability — Can the Adsorbent Be Used Again?

Recommended layout:

1. **Process sequence:** adsorption → solid–liquid separation → desorption/regeneration → rinse/dry → next adsorption cycle.
2. **Three metric definitions:** desorption efficiency, regeneration performance and capacity retention.
3. **Three primary cycle examples:**
   - REF-12: five cycles; ethanol + ultrasound; 86.8% OTC and 91.1% CIP capacity retention; water-wash control only 21.2% and 19.7%.
   - REF-13: four cycles; DI-water desorption; reported 72% TC removal after cycle four.
   - REF-15: five cycles; 0.1 M NaOH; authors report only a slight capacity decrease, but the text supplies no exact final retention percentage.
4. **Practical caution:** a desorption/release result such as REF-11 does not itself demonstrate repeated-cycle regeneration.
5. **Close:** “A good adsorbent must be recoverable and must retain useful adsorption capacity after regeneration; the regenerant and spent liquid must also be managed.”

Include a small side note on solvent/energy/wastewater treatment costs. Do not rank REF-12, REF-13 and REF-15 directly because the adsorbates, adsorbents, regenerants, initial conditions and reported performance metrics differ.

---

## Source map

| REF-ID | PDF locator | Role in this extraction |
|---|---|---|
| REF-02 | PDF p. 29, Section 8 | Definition/principles of biomass adsorbent regeneration; thermal regeneration discussion; tetracycline-related example |
| REF-02 | PDF p. 30, Section 8.2 | Solvent and acid–base regeneration approaches |
| REF-03 | PDF p. 20 | General regeneration/reactivation and disposal cost safeguard; non-antibiotic-specific review |
| REF-08 | PDF p. 7, Table 1 and Section 3.4 | Eluent types, desorption vs regeneration efficiency, secondary-liquid concerns, regeneration costs |
| REF-08 | PDF p. 8, Section 3.4.1–3.4.2 | Chemical, thermal, microwave, electrochemical and other regeneration routes; challenges |
| REF-11 | PDF pp. 3–4 | Batch desorption and stirred-flow release methods |
| REF-11 | PDF pp. 5–6, Section 3.2–3.4 and Table 1 | CIP/CLA/TRI desorption results; single-desorption vs repeated regeneration distinction |
| REF-12 | PDF pp. 3–4, Sections 2.3 and conditions list | Ethanol + ultrasound regeneration method, volumes, drying and five-cycle design |
| REF-12 | PDF pp. 10–11, Section 3.6 and Fig. 7 | Capacity retention for OTC/CIP, water-wash control and Fe-leaching results |
| REF-13 | PDF p. 4, experimental methods | General washing/drying statement preceding cycle testing |
| REF-13 | PDF p. 8, Fig. 4f and reusability discussion | Four DI-water desorption cycles, 72% TC removal after cycle four, magnetic separation |
| REF-13 | PDF p. 11, conclusion | Reuse result reiterated |
| REF-14 | PDF p. 13, conclusion | Explicit call for further regeneration and reuse experiments |
| REF-15 | PDF p. 5, Section 2.7 | Five-cycle design and 0.1 M NaOH procedure |
| REF-15 | PDF pp. 13–14, Section 3.6 and Fig. 10 | Reported slight capacity decline; cycle graph; comparison of regeneration comments |
| REF-15 | PDF p. 13 | Cited HCl-elution comparison (~50% initial capacity), not a current-study HCl control |

**Next Stage 2 extraction:** economics and practical feasibility (slide 14). Do not add references or begin PowerPoint production before the extraction and evidence review are complete.
