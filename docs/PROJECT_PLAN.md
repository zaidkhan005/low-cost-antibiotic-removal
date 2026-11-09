# Project Plan

## Working title

**Low-Cost Adsorbents for the Removal of Antibiotics from Aqueous Medium**

## Purpose and presentation identity

This is an independent academic review presentation. It is not based on or restricted to the selected materials, antibiotics, comparisons, or conclusions of the user's separate semester manuscript. The presentation teaches the subject from foundational concepts and then reviews the scientific methods and evidence.

## Approved presentation structure (15 slides)

### Part I — Introduction and fundamentals

1. **Title** — topic, presenter, department, institution.
2. **Antibiotics and the aquatic environment** — definition, major antibiotic classes, contamination sources, pathways into water.
3. **Antibiotics as emerging water contaminants** — occurrence, persistence, environmental risks, antibiotic resistance, limitations of conventional treatment.
4. **Treatment technologies for antibiotic removal** — biological treatment, membrane filtration, advanced oxidation, coagulation, adsorption; comparative strengths and limitations.

### Part II — Adsorption science and low-cost materials

5. **Fundamentals of adsorption** — adsorption vs absorption; adsorbent vs adsorbate; physisorption vs chemisorption; surface adsorption and pore filling.
6. **Classification of adsorbents** — activated carbon, clays, biochar, agricultural/industrial waste-derived materials, engineered carbonaceous adsorbents, composites.
7. **Mechanisms of antibiotic adsorption** — electrostatic interactions, hydrogen bonding, π–π interactions, hydrophobic interactions, pore filling, complexation.
8. **Factors affecting adsorption** — pH, pKa/speciation, adsorbent dosage, initial concentration, contact time, temperature, ionic strength, competing substances/natural organic matter.

### Part III — Quantitative evaluation of adsorption

9. **Adsorption capacity and removal efficiency** — batch setup, mass balance, equations, worked numerical example.
10. **Adsorption isotherms** — Langmuir, Freundlich, Temkin, Sips; assumptions, equations, parameters, interpretation.
11. **Adsorption kinetics** — pseudo-first-order, pseudo-second-order, intraparticle diffusion, Elovich; rate constants, equilibrium time, interpretation.
12. **Thermodynamics of adsorption** — Gibbs free energy, enthalpy, entropy; spontaneity, endothermic/exothermic processes, temperature dependence.

### Part IV — Practical feasibility and research outlook

13. **Regeneration and reusability** — desorption, chemical/thermal/other regeneration methods, adsorption–desorption cycles, capacity retention, limitations.
14. **Low-cost potential and practical challenges** — feedstock, preparation/activation, separation/recovery, regeneration, real-water performance, scale-up, cost per treated volume.
15. **Conclusion and references** — key findings, research gaps, future directions, selected references.

## Fixed-source policy

The approved source collection is exactly 15 papers previously selected for this project. The project must not search for or add further papers. The PDFs supplied by the user are the working full-text source set. If a paper's bibliographic metadata differs from the preliminary citation, the PDF itself and verifiable publisher metadata must be used to correct the inventory; do not silently replace the paper.

## Stages and deliverables

### Stage 1 — PDF and reference audit
- Inventory all 15 files.
- Verify each title, author list, year, journal, volume/issue/pages or article number, and DOI.
- Check text and page completeness, including figures/tables.
- Record which presentation topics each paper actually supports.
- Flag metadata or access problems without substituting new references.

**Deliverable:** `references/reference_inventory.md` and `references/pdf_audit.md`.

### Stage 2 — Scientific extraction
Extract claims with precise page/table/figure locations where possible:
- definitions and foundational terminology;
- antibiotic classes, sources, occurrence, persistence, risk;
- treatment technology comparisons;
- adsorbent classes and material properties;
- adsorption mechanisms and controlling factors;
- equations and assumptions for uptake/removal;
- isotherm models and parameter interpretation;
- kinetic models and limitations;
- thermodynamic equations and sign conventions;
- regeneration methods, cycles, capacity retention and waste streams;
- feedstock/preparation/recovery costs, scale-up, real-water limitations.

**Deliverable:** topic notes under `literature-extraction/` and a source-to-claim evidence matrix.

### Stage 3 — Presentation content
- Draft each slide with title, teaching objective, concise main content, equations/diagram specifications, speaker explanation, and citations.
- Keep slide density appropriate for a 15-slide academic presentation.
- Ensure every citation is from the fixed 15-paper set.
- Review scientific accuracy before designing.

**Deliverable:** `presentation-content/slide-by-slide-draft.md`.

### Stage 4 — PowerPoint
- Build an editable 16:9 deck.
- Use diagrams and tables to explain, not decorate.
- Ensure equations and subscripts render correctly.
- Include in-slide citations and a complete references slide.
- Render, inspect all slides, and correct layout/overflow issues.

**Deliverable:** final PPTX plus a PDF export and preview.

## Scientific interpretation safeguards

1. Adsorption is a separation/transfer process; do not describe it as degradation unless a coupled transformation process is independently demonstrated.
2. Use \(q_e=(C_0-C_e)V/m\) only with consistent units and clearly identified equilibrium concentrations, solution volume, and adsorbent mass.
3. Use \(%R=((C_0-C_e)/C_0)\times100\) with explicit initial and final concentrations.
4. Keep measured \(q_e\), derived uptake, fitted \(q_m\), and percent removal distinct.
5. A good pseudo-second-order fit alone does not prove chemisorption.
6. An isotherm fit alone does not establish a unique molecular mechanism.
7. Thermodynamic conclusions require attention to the method and standard-state assumptions used to calculate parameters.
8. Report all relevant experimental conditions alongside capacity/removal figures.
9. Distinguish regeneration efficiency, desorption efficiency, capacity retention, and removal after reuse.
10. Do not call an adsorbent low-cost solely because its feedstock is waste-derived; include preparation, activation, recovery, regeneration, transport, and disposal where data permit.

## Current status

Stage 1 is complete: all 15 selected PDFs have first-pass bibliographic and file-integrity audit records. Existing REF-06–REF-10 branch-chat work has been transferred without reprocessing or renumbering. Stage 2 Pass 1 (fundamentals and adsorption mechanisms), Pass 2 (quantitative adsorption evaluation for slide 9), and Pass 3 (adsorption isotherms for slide 10) have been committed with corresponding source-to-claim evidence matrices. Pass 3 compares the four approved teaching models with antibiotic-specific results from REF-09, REF-10 and REF-14, records nonlinear-regression/error-function cautions from REF-06, and preserves the printed Sips-equation discrepancy between REF-06 and REF-14. Remaining Stage 2 topics are adsorption kinetics, thermodynamics, regeneration and economics. Exact source locators missing from the transferred REF-06–REF-10 handoff must still be recovered before using those particular claims in slide content. No additional references have been added.
