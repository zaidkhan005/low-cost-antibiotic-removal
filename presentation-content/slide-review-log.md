# Slide-by-Slide Review Log

## Review method

Review the existing 15-slide draft sequentially. For each slide:
1. Check the slide's claims against the relevant extraction note and evidence matrix.
2. Verify cited author–date references and source locations where the claim depends on a specific result.
3. Check equations, symbols, units and numerical examples where present.
4. Assess whether the on-slide copy is appropriately concise and whether the visual specification communicates the point accurately.
5. Record a pass, a justified correction, or an unresolved evidence limitation before proceeding.

Do not reprocess completed papers, add references, or begin PowerPoint production during this review stage. Keep REF-01–REF-15 as internal tracking identifiers only; presentation-facing citations must use author–date format.

## Slide 1 — Title

**Status:** Pass; no content changes required.

**Checked**
- Working title matches the presentation's subject and scope.
- Subtitle accurately previews the fundamentals, models, evidence and feasibility progression.
- Visual brief asks for a generic antibiotic-molecule silhouette and explicitly avoids an unidentified or inaccurate molecular structure.
- No scientific claim requiring a citation appears on the title slide.
- Presenter, department/institution and date are correctly left as placeholders for the presenter to complete.

**Action:** None. The slide-by-slide draft was not modified for this review.

**Review basis:** `presentation-content/slide-by-slide-draft.md`, Slide 1, fetched from `main` at blob SHA `6cc9544773cd59608dbb38beedce38a09d9dcb0e`.

## Slide 2 — Antibiotics and the Aqueous Environment

**Status:** Pass; one presenter-note citation addition made.

**Checked**
- The antibiotic definition and stated human/veterinary contexts match the framing in the selected review literature.
- The source pathways are supported by Ajala et al. (2023) and Teo et al. (2022); the wording does not imply that all sources contribute equally in every setting.
- The displayed antibiotic classes are explicitly framed as examples, not an exhaustive or mutually exclusive taxonomy. The examples are supported across Ajala et al. (2023), Teo et al. (2022), and Rodríguez-López et al. (2024).
- The operational explanation of “aqueous medium” is clearly identified in the extraction as a plain-language teaching definition rather than a formal definition from one paper.
- The note distinguishing laboratory water, synthetic wastewater and real wastewater is retained; the matrix-effects explanation is supported by the reviewed discussion of competing ions and natural organic matter.

**Correction:** Added a source-citation bullet for the presenter-note statement on competing ions and natural organic matter: Ajala et al. (2023), PDF p. 9 (journal p. 4686), and Teo et al. (2022), PDF pp. 7–8. No scientific wording or on-slide content was changed.

**Verified change:** Commit `d168f48bcf4302adbea2897b042df18ef05e5e15`; the updated draft was fetched from `main`, and the content differs from the prior version only by the added Slide 2 citation.

## Slide 3 — Antibiotics as Emerging Water Contaminants

**Status:** Pass; one treatment-limitation statement narrowed and its evidence trail completed.

**Checked**
- Environmental occurrence across water-related and other matrices is supported by Gopal et al. (2020), Teo et al. (2022) and Ajala et al. (2023). The slide retains the explicit qualification that occurrence is compound- and matrix-specific.
- Ecological effects and antimicrobial-resistance concerns are supported by the Teo and Gopal reviews. The slide does not claim that adsorption removes ARB or ARGs.
- The original PDFs were checked for the conventional-treatment point: Teo et al. (2022), PDF p. 2, describe conventional biological treatment as inefficient for antibiotic residues; Gopal et al. (2020), PDF p. 4 / journal p. 27084, state that primary and secondary treatment were insufficient for complete TC removal.
- The visual pathway is appropriately framed as an environmental concern and does not present a universal concentration or removal percentage.

**Correction:** Replaced the broad wording “may not completely eliminate every antibiotic compound” with a more source-specific statement: conventional biological treatment may be inefficient, while the primary/secondary-treatment limitation is explicitly tied to tetracycline. Added the precise page locators to the slide citations and presenter notes.

**Evidence trail updated**
- Added FND-013 to `evidence-matrix/fundamentals-mechanisms.md`.
- Added the source-specific treatment statements and locators to `literature-extraction/fundamentals-and-adsorption-mechanisms.md`.
- Updated Slide 3 in the citation map to preserve the TC-specific qualification.

**Verified commits**
- Evidence matrix: `13b8eb69824a66b54b5c4c259ea8670544fa7372`
- Extraction note: `6af9ae91cf920654c2efacae46ba612b9a876160`
- Slide draft: `d66e0b196b25aba6716fafd904b51e7437d7891f`
- Citation map: `1d3aa43e69bd3152a808e5043652d46ba1cab9de`

All four files were fetched from `main` after their updates. The Slide 3 presentation-facing citations use author–date format; no REF identifiers appear in the slide copy.

## Slide 4 — Treatment Technologies for Antibiotic Removal

**Status:** Pass; comparison and source locators revised.

**Checked**
- Biological treatment is described as a wastewater-treatment process, with antibiotic-removal inefficiency qualified as a limitation reported by Teo et al. (2022). Gopal et al.'s statement about incomplete primary/secondary removal is retained as tetracycline-specific.
- AOPs are described as oxidative transformation/degradation processes. The slide retains the warning that oxidised by-products may be toxic and that parent-compound disappearance must not automatically be called mineralisation or detoxification.
- Membrane filtration/reverse osmosis is described as a separation approach. The cited limitations now include membrane fouling, energy requirement and operating cost; reverse-osmosis limitations are differentiated in the presenter notes.
- Adsorption is explicitly described as liquid-to-solid transfer rather than destruction. The slide retains recovery, regeneration and/or disposal of the loaded adsorbent and captured antibiotic.
- The slide is a role-and-limitation comparison, not a universal technology performance or cost ranking.

**Corrections**
- Replaced the broad membrane “production and operating costs” note with source-specific fouling, energy-demand and operating-cost limitations; added the reverse-osmosis caveat.
- Added the AOP by-product toxicity and mineralisation qualification.
- Replaced the vague adsorption waste note with the specific need to manage the loaded adsorbent and recovered antibiotic.
- Corrected the citation locations: Gopal et al. (2020), journal pp. 27084, 27086–27087 and 27091; Teo et al. (2022), PDF pp. 2, 6 and 14; Zhao et al. (2024), PDF p. 2.

**Evidence records added**
- `literature-extraction/treatment-technologies.md` — Stage 2 Extraction 08.
- `evidence-matrix/treatment-technologies.md` — eight traceable claims, TCH-001 to TCH-008.
- Both extraction and evidence README files now index the new records.

**Verified commits**
- Treatment extraction: `1dbce55ba752454a1fce90a046cbfa8cefad732f`
- Treatment evidence matrix: `6f35842551a39ac0d8b713bc805ac3c49150aea8`
- Slide draft: `8caa319367290dc5b726bd5f2fc15b4e30f87a19`
- Citation map: `16d7eb2a4175f8c44106510f8383603d2304f58b`
- Extraction index: `92457fe4f15b0ae37ad85ddec623a82fa1e23e25`
- Evidence index: `3c13c3deb1bdc2684dbb8d99078bcfcd68fcb3d3`

All six files were fetched again from `main`. The Slide 4 block contains all four technologies, preserves the process distinctions and qualifications, and contains no reader-facing REF identifiers.

## Slide 5 — Fundamentals of Adsorption

**Status:** Pass; sequence and visual specification clarified.

**Checked**
- The adsorbate, adsorbent and adsorption terms match the project's working definitions in the Stage 2 extraction.
- The adsorption/absorption distinction remains explicitly labelled as standard chemistry teaching terminology because the inspected fixed-source passages do not provide a dedicated formal comparison.
- Rodríguez-López et al. (2024), PDF p. 2, supports a separate distinction: biosorption refers to sorbents derived from biological materials, while the term adsorption does not specify sorbent origin. The slide does not conflate this with adsorption-versus-absorption.
- Ajala et al. (2023), PDF p. 9 / journal p. 4686, gives four principal steps: movement from the bulk matrix toward the adsorbent, liquid-film diffusion, movement toward accessible active sites, and final interaction with the adsorbent surface.
- Ajala et al. (2023), Figure 3, PDF p. 16 / journal p. 4693, illustrates pore filling and other possible adsorption modes. Pore filling is not described as a separate mandatory stage in the four-step passage.

**Correction:** Refined the process sequence to retain all four steps in the source order. Separated pore filling as a possible retention mode rather than showing pore entry as a universal fifth transport step. The source's phrase “adsorbent–adsorbent interactions” appears typographical in context; the slide uses “adsorbate–adsorbent interaction” as an explicitly identified editorial clarification.

**Evidence updates**
- Revised the adsorption-sequence passage in `literature-extraction/fundamentals-and-adsorption-mechanisms.md` to distinguish the four-step sequence from Figure 3's possible adsorption modes.
- Updated FND-005 and added FND-014 in `evidence-matrix/fundamentals-mechanisms.md`.
- Updated Slide 5 and its source/caveat row in the citation map.

**Verified commits**
- Extraction: `644f7234f25103d811a6a27fcb73a734706aea0c`
- Evidence matrix: `105eaec9f8c675e49fff85ab3a5650defa1e6d59`
- Slide draft: `ef4fd3ac5f9242ae75f8259c06110e3fd5c6827c`
- Citation map: `bbd4038503d900422c6bff67f90ef37154512611`

All four records were fetched from `main` after committing. Presentation-facing citations use author–date format; no REF identifiers appear in the Slide 5 block.

## Slide 6 — Classification of Adsorbent Materials

**Status:** Pass; material categories reorganised to avoid mixing classification dimensions.

**Main finding:** The original five-branch structure mixed base material form, feedstock origin and material modification. For example, brewing bagasse is a feedstock, activated biochar is the product, and a magnetic ferrite/biochar material is a composite made by modifying a carbonaceous base. These are related stages/descriptors, not mutually exclusive parallel material families.

**Revised framework**
- **Natural mineral sorbents:** kaolinite and smectite-group minerals such as montmorillonite (Perelomov et al., 2025, PDF pp. 4–7).
- **Non-biochar by-product sorbents:** raw date-palm fibre (Mirizadeh et al., 2023, PDF pp. 1–2), and hemp waste, oak ash and uncalcined mussel shell (Rodríguez-López et al., 2024, PDF p. 2). These are grouped as by-product solids used without conversion to biochar, not as one chemically uniform class.
- **Carbonaceous sorbents:** biochar, activated biochar and activated carbon. Ajala et al. (2023), PDF p. 9 / journal p. 4686, describe biochar as a carbon-rich product of biomass pyrolysis; Teo et al. (2022), PDF pp. 6–7, discuss the terminology and activation distinctions.
- **Processing/engineering overlay:** activation (K₂CO₃ for bagasse-derived biochar; KOH for fermentation-residue biochar) and composite formation (Fe₂O₃@BMBC from cotton-husk biochar; NFO/BC from sawdust-derived biochar).

**Specific terminology correction:** Avoided the label “uncarbonized by-product sorbents” because oak ash is itself produced by combustion. The final label is “non-biochar by-product sorbents,” which does not make an unsupported claim about the thermal history of all examples.

**Other qualifications retained**
- Do not list feedstock and its derived biochar as separate adsorbent families.
- Do not present “waste-derived” or “engineered composite” as a peer branch to a base material form.
- Use each paper's actual material designation; raw biochar, activated biochar and activated carbon are not interchangeable without checking the preparation route and source terminology.
- The slide is a corpus-based teaching grouping, not a universal taxonomy of all adsorbents.

**Evidence records**
- Added MAT-001 to MAT-005 to `evidence-matrix/fundamentals-mechanisms.md`, covering clay minerals, non-biochar by-product solids, carbonaceous feedstocks, activation and composite formation.
- Reorganised Section 5 in `literature-extraction/fundamentals-and-adsorption-mechanisms.md` to separate material form from feedstock and processing.
- Updated Slide 6 and its citation-map row with author–date references and precise PDF locators.

**Verified commits**
- Literature extraction restructure: `8d8cdc8433c89284fcd106a749ebf5093e1cb1b5`
- Extraction label clarification: `8685f4d84d2baa7cded1434c3b6695a812ce544f`
- Evidence matrix: `797b6a0c4397eb5d4a203ecfc29d625ccec7320a`
- Evidence label clarification: `93ed0d9c0a0f10a096e475c7787b67c798ff7964`
- Slide draft restructure: `8b16f57429ffb879936ddef2f79d329c09c26103`
- Slide label clarification: `af8ddabd2ece87a5fd459eee4ebeb4defec97c54`
- Citation map update: `06c37676e21a9d31ea511a74e56ad8454dc8f3e8`
- Citation-map label clarification: `c3d5a190c9531c0b0aac19ba8db081018d74ba45`

All four working files were fetched from `main` after their updates. The final Slide 6 block contains the three base material forms, separates processing/engineering, uses author–date citations and contains no reader-facing REF identifiers.

## Slide 7 — Mechanisms of Antibiotic Adsorption

**Status:** Pass; mechanism categories and visual plan made material-specific.

**Scientific review**
- Teo et al. (2022), PDF p. 7, discuss electrostatic interactions, hydrogen bonding, hydrophobic interactions and π–π / electron-donor–acceptor interactions for carbon-based adsorbents. These are review-level candidate interactions, not a universal set for every carbon–antibiotic pair.
- Perelomov et al. (2025), PDF pp. 5–7, describe clay basal/edge charge, pH-dependent edge chemistry, exchangeable cations, cation exchange and interlayer uptake in swelling minerals. These clay-specific processes are not interchangeable with metal complexation on iron-containing biochar.
- Chen et al. (2024), PDF pp. 1 and 5–6, report/propose electrostatic interactions, hydrogen bonding, π–π conjugation and Fe–O complexation for OTC/CIP on Fe₂O₃@BMBC. The revised slide attributes these to that material–antibiotic system.
- Liang et al. (2024), PDF p. 2, graphically depict electrostatic force, hydrogen bonding, π–π interaction and pore filling for TC on NiFe₂O₄/biochar. The revised slide explicitly labels this as the authors' conceptual graphical model.
- Meseguer et al. (2024), PDF p. 2, list pore filling, metal complexing, precipitation, hydrogen bonding, ion exchange, cation bridging and hydrophobic partition among mechanisms reported in the wider pharmaceutical-adsorption literature. This list is not experimental proof that all those mechanisms occur in that article's own CIP–activated-bagasse-biochar system.

**Corrections**
- Replaced the generic six-callout mechanism drawing with three material-specific panels: carbon-based adsorbents, natural clay minerals and iron-containing biochar composites.
- Separated clay cation exchange from Fe–O complexation and from the broad cation-bridging/metal-complexing list in the Meseguer introduction.
- Qualified Liang et al.'s graphical abstract as a conceptual model for its specific TC/NiFe₂O₄-biochar system.
- Preserved the safeguard that model fitting alone does not prove a molecular interaction or unique mechanism.
- Corrected the lower-case “the graphical abstract” wording in the presenter notes.

**Evidence records**
- Expanded Section 6.6 and added Section 6.7, “Matching mechanism claims to evidence scope,” in `literature-extraction/fundamentals-and-adsorption-mechanisms.md`.
- Revised MEC-001 and MEC-003 to MEC-006 in `evidence-matrix/fundamentals-mechanisms.md` to state their evidence scope and material–antibiotic boundaries.
- Updated Slide 7 and its citation-map row using author–date citations and PDF locators.

**Verified commits**
- Literature extraction: `3795fdae47cf11b382881d57a2509b23d8cc0402`
- Evidence matrix: `de78f3f9462e782395fe3345030258e63a6b9a20`
- Slide draft: `421f9a2943bf5262f6388c7316f12907d947e4a1`
- Citation map: `d7e91411e929c807ff40ebcb28a43aa1ba86e0fd`

All four working files were fetched from `main` after their updates. The Slide 7 block uses author–date citations, separates the material-specific examples and contains no reader-facing REF identifiers.

## Slide 8 — Factors Affecting Adsorption

**Status:** Pass; factor explanations and source-specific examples revised.

**Main scientific checks**
- **Antibiotic pKa vs adsorbent pHₚzc:** The slide now distinguishes acid–base dissociation of the antibiotic from the pH at which the adsorbent has zero net surface charge. They are not interchangeable.
- **TC speciation:** Gopal et al. (2020), PDF pp. 2–3, report pKa values of approximately 3.3, 7.7 and 9.7 and provide a species-distribution diagram. The simplified text describes cationic TC below 3.3, zwitterionic TC between 3.3 and 7.7, and anionic TC above 7.7; the third pKa is retained as further alkaline deprotonation.
- **OTC–kaolinite:** Perelomov et al. (2025), PDF p. 16, report OTC pKa values of 3.57, 7.49 and 9.88 and a system-specific maximum kaolinite adsorption capacity near pH 5.5. This is not presented as a universal optimum.
- **NFO/BC–TC pH and dose:** Liang et al. (2024), PDF p. 7, report pHₚzc ≈5.35 and maximum TC removal of 92.4% at pH 7.0 in their tested system. Dose increase from 0.2 to 1.0 g L⁻¹ raised removal from 37% to 93.9%; further increase gave little benefit relative to added adsorbent cost.
- **Competing matrix constituents:** Liang et al. (2024), PDF p. 8, report lower TC removal with increasing humic-acid dosage; NaCl had no significant effect in the reported tests, whereas MgCl₂ and CaCl₂ decreased capacity. Perelomov et al. (2025), PDF p. 16, separately report ionic-strength and dissolved-organic-matter effects for clay/tetracycline systems. The slide preserves the salt- and material-specific differences.
- **Precipitation control for CIP:** Meseguer et al. (2024), PDF p. 8, show that apparent CPX removal at pH 7–9 was mainly precipitation rather than adsorption, based on turbidity and blank tests. The slide now explicitly warns against interpreting this disappearance as adsorption. Subsequent tests were performed at pH 3.5 to minimise precipitation.
- **Temperature and contact time:** For CIP on K₂CO₃-activated bagasse biochar, Meseguer et al. (2024), PDF p. 8, report an increase in equilibrium uptake from 34.6 mg g⁻¹ at 10 °C to 109.9 mg g⁻¹ at 55 °C. About 82% of equilibrium uptake was reached after 24 h, with equilibrium at approximately 80 h under the stated conditions (PDF pp. 1 and 5). These results are explicitly tied to that system.
- **Particle size:** Rodríguez-López et al. (2024), PDF p. 2, report particle-size preparation details and identify size as an operating parameter, but the cited passage does not establish a universal directional effect on adsorption.

**Corrections**
- Split natural organic matter from ionic strength/competing ions in the on-slide factor table.
- Added material- and antibiotic-specific pH examples and separated pKa from pHₚzc.
- Added the CPX precipitation warning and blank-test distinction.
- Added specific dose, salt, temperature and contact-time examples to presenter notes, without making universal claims.
- Clarified that particle size is a reported operating/preparation variable, not a universally demonstrated directional factor.
- Replaced a non-Markdown inline tag with ordinary Markdown emphasis.

**Evidence records**
- Expanded Section 8 in `literature-extraction/fundamentals-and-adsorption-mechanisms.md` with source-specific examples and interpretation safeguards.
- Added FAC-001 to FAC-009 in `evidence-matrix/fundamentals-mechanisms.md`.
- Extended the extraction source map for REF-13 and REF-14 with the additional factor-evidence pages.
- Updated Slide 8 and its citation-map row using author–date references and PDF locators.

**Verified commits**
- Literature extraction factor section: `d2ff52ad88bcb92c08585f3323aa7d5c4d762c72`
- Literature extraction source map: `5075c89646a4f492f9c2f490490c832fef5d4085`
- Evidence matrix FAC-001–FAC-008: `e06f7da3fd376b3ddfbf31c02efc9f54be58b9a2`
- Evidence matrix FAC-009: `959a01e13f03f0e779ff2b56ccd6e8f3e9eb643c`
- Slide draft revision: `4b4b0fa66d662e098ec57b55ebaac1dd42bbcaa0`
- Slide draft formatting / pH clarification: `932be01ad22ad96390d548a4805309b7c1e25293`
- Citation map: `3d6c5d6233f4b385db518faed778c1393e59e49c`

The slide draft, citation map, extraction and evidence matrix were fetched from `main` after their updates. The final Slide 8 block contains no reader-facing REF identifiers and passes the checks for author–date citations, the pHₚzc/pKa distinction, the precipitation caveat, system-specific dose and salt effects, and the temperature/contact-time example.

## Slide 9 — Adsorption Capacity and Removal Efficiency

**Status:** Pass; equations and worked example verified, with notation/provenance clarifications.

**Original-source checks**
- Mirizadeh et al. (2023), PDF p. 2, define removal efficiency as (Y(\%)=((C_0-C_e)/C_0)\times100) and equilibrium capacity as (q_e=((C_0-C_e)V)/m). The paper defines (m) as dry biosorbent mass and (V) as solution volume.
- Mirizadeh et al. (2023), PDF pp. 2–3, report the batch volume (30 mL), the pH-series conditions (initial TC concentration 50 mg L⁻¹, dose 1 g L⁻¹, 298 K, 3 h), and a TC capacity of 16.15 mg g⁻¹ at pH 10. Figure 1 plots both adsorption capacity and removal efficiency for the pH series.
- Meseguer et al. (2024), PDF p. 4, use the volume-aware mass balance (q_t=(C_0V_0-C_tV_t)/m) when liquid volume at sampling differs from the initial volume. The presentation keeps this separate from the simplified constant-volume equilibrium expression.
- Zhao et al. (2024), PDF p. 3, print ((C_e-C_0)) in the capacity/removal expressions while defining (C_0) as initial and (C_e) as equilibrium concentration. The review preserves this as a source-level sign anomaly and does not reproduce it as a positive uptake equation.

**Independent arithmetic check**
- Adsorbent mass: (m=(1\;\mathrm{g\,L^{-1}})(0.030\;\mathrm{L})=0.030\;\mathrm{g}).
- Antibiotic mass adsorbed: (16.15\;\mathrm{mg\,g^{-1}}\times0.030\;\mathrm{g}=0.4845\;\mathrm{mg}).
- Initial antibiotic mass: (50\;\mathrm{mg\,L^{-1}}\times0.030\;\mathrm{L}=1.500\;\mathrm{mg}).
- Residual antibiotic mass: (1.500-0.4845=1.0155\;\mathrm{mg}).
- Back-calculated equilibrium concentration: (1.0155\;\mathrm{mg}/0.030\;\mathrm{L}=33.85\;\mathrm{mg\,L^{-1}}).
- Reconstructed removal: ((50-33.85)/50\times100=32.3\%).

The arithmetic is correct. The slide now labels (C_e=33.85\;\mathrm{mg\,L^{-1}}) and (Y=32.3\%) as reconstructed from the reported (q_e) and dose. The article also plots removal efficiency in Figure 1, but its text does not state an exact pH-10 numerical (Y); the reconstructed 32.3% is therefore not presented as an exact number quoted by the authors.

**Corrections and clarifications**
- Changed the removal-efficiency symbol from (R) to the source's (Y).
- Labelled the equilibrium-capacity equation as the constant-volume batch form.
- Added the distinction between (q_e) at equilibrium and (q_t) at a specified earlier time.
- Added the volume-aware (q_t) expression to the presenter notes for changing liquid volume.
- Added pH, temperature and contact time to the worked-example conditions.
- Corrected the footnote to acknowledge that Figure 1 plots removal efficiency while still distinguishing the reconstructed numerical result from a value stated in the text.
- Replaced the internal REF identifier in the slide footnote with author–date citation text.

**Evidence and repository updates**
- Refined Section 4 provenance wording in `literature-extraction/quantitative-adsorption-evaluation.md`.
- Revised QNT-006 in `evidence-matrix/quantitative-evaluation.md` to document the plotted-versus-reconstructed value distinction.
- Updated Slide 9 and its citation-map row to use (Y), distinguish constant-volume and volume-aware balances, and preserve the Zhao et al. source warning as a note only.

**Verified commits**
- Slide draft — author notation and back-calculation clarification: `4b6fdd1ba0a4f71487e613aa67ce60a9c419a3a4`
- Extraction provenance clarification: `fecab86f6ce49aec260363cc20ae0518581822bc`
- Evidence matrix QNT-006 clarification: `f0895c77a7cc7ddf127b45f6767e9b6ffce3b992`
- Slide draft — constant-volume and (q_t/q_e) distinction: `1a4fd90c803dc7e7e69cfbc3691b8b009f365ed3`
- Citation map: `302f19d34c5b1c27e1c06b17745bf4e7f8ca509d`
- Slide draft — full conditions, (Y) notation and reader-facing citation: `3ce790a9e90b05a1a62e5be124ed918ed8fe9052`, `a2bb00503d612a163b1c941785135104c25a5f2c`

The final draft, citation map, extraction and evidence matrix were fetched from `main` after their respective updates. The Slide 9 block uses author–date citations and contains no reader-facing REF identifiers.

## Slide 10 — Adsorption Isotherms

**Status:** Pass; model definitions and parameter explanations expanded at the user's request.

**Original-source verification**
- Ayawei et al. (2017), PDF pp. 2–3, describe Langmuir dynamic equilibrium between adsorption on open surface fractions and desorption from covered fractions; explain Freundlich as applicable to heterogeneous surfaces with a distribution of active-site energies; and state the Temkin assumption that heat of adsorption decreases linearly with increasing surface coverage.
- Ayawei et al. (2017), PDF p. 5, describe Sips as a Langmuir–Freundlich combination. The low-concentration behaviour is Freundlich-like and high-concentration behaviour is Langmuir-like.
- Ayawei et al. (2017), PDF pp. 7–8, explain that linearisation changes the error structure and discuss nonlinear regression and multiple error functions.
- Mirizadeh et al. (2023), PDF pp. 6–7, report Langmuir as the best tested model for TC and D–R as best for CIP. The authors interpret the TC Langmuir fit using the idealised homogeneous-site/monolayer model; this is retained as an interpretation, not microscopic proof.
- Egbedina et al. (2021), PDF pp. 5–7, show that the best-fitting two-parameter model varies by antibiotic and material treatment. The missing supplementary Table S1 remains a limitation; no missing three-parameter values were inferred.
- Meseguer et al. (2024), PDF p. 6 and pp. 11–12, provide the Sips parameterisation used in the slide and report Freundlich as best by the lowest ARE (2.44%). Their experimental curve approaches approximately 110 mg g⁻¹ but does not reach a clear plateau in the tested range.

**Definition improvements**
- Added a plain-language definition of an isotherm and explained what the two axes mean: (C_e) is the concentration remaining in solution at equilibrium; (q_e) is the amount retained per gram of adsorbent at equilibrium.
- Expanded Langmuir to explain finite, idealised equivalent sites, monolayer coverage and why the curve approaches a plateau; defined (q_{mL}) and (K_L).
- Expanded Freundlich to explain heterogeneous site energies, the role of the exponent (1/n), and why (K_F) is not a finite maximum capacity.
- Expanded Temkin to explain the coverage-dependent decrease in heat of adsorption and the roles of (b_T), (K_T), (R) and (T).
- Expanded Sips to explain the low-concentration Freundlich-like and high-concentration Langmuir-like limits; defined (q_{mS}), (K_S) and (n_S).
- Added an explicit reminder that an isotherm is an equilibrium relation, not a rate equation, and that model fit alone does not prove a molecular mechanism.
- Added more explanation to the presenter notes while keeping the on-slide definitions concise enough to support a visual four-model comparison.

**Scientific cautions retained**
- Freundlich exponent conventions differ across the selected papers; check the exact equation before interpreting or comparing (n).
- Fitted (q_m), (q_{mS}) and related capacities are model parameters, not automatically experimentally achieved uptake.
- Compare models within the same dataset and report the fit criterion; do not compare (R^2) from one paper directly with ARE from another.
- The slide uses the Sips equation specified by Meseguer et al. (2024); Ayawei et al. (2017), Eq. (21), prints a different denominator sign/parameterisation. The discrepancy remains documented.
- Temkin fitting alone is not used to infer endothermic or exothermic behaviour.

**Repository updates**
- Revised `presentation-content/slide-by-slide-draft.md` with expanded definitions and presenter explanations.
- Updated the Slide 10 row in `presentation-content/citation-map.md` to match the expanded teaching content.
- The existing literature extraction and evidence matrix were retained; they already contain the source-grounded definitions, model assumptions, parameter qualifications and source discrepancy. No reprocessing or new references were added.

**Verified commits**
- Slide 10 expanded definitions: `3b1c34c5bbb058d28f6a2e70b75050b554a36508`
- Citation map update: `dda00b5e38704119a9cbe654c7b9a29648ca97b2`

The slide draft and citation map were fetched from `main` after the updates. The Slide 10 block uses author–date citations only and retains the fixed 15-reference source boundary.

## Slide 11 — Adsorption Kinetics

**Status:** Pass; model definitions and parameter explanations expanded, with a source-notation clarification.

**Original-source verification**
- Vareda (2023), PDF p. 2, describes bulk transport, liquid-film diffusion, pore diffusion and surface interaction/reaction as relevant stages in liquid-phase adsorption. The review explains that kinetic tests estimate uptake rate and can provide insight into the rate-controlling step, but a kinetic model cannot identify the molecular interaction by itself.
- Vareda (2023), PDF pp. 2–6, explains why PFO and PSO are called “pseudo”: they adapt homogeneous reaction-kinetic forms to heterogeneous adsorption and express rate in terms of solid-phase uptake, while assuming the solution concentration is approximately constant. The review discusses both surface-reaction and diffusion-related interpretations of these models.
- Vareda (2023), PDF pp. 3–5, explicitly cautions that PSO can fit both surface-reaction-controlled and diffusion-controlled data; a PSO fit alone does not establish chemisorption.
- Vareda (2023), PDF p. 5, explains PFO as proportional to the remaining uptake gap and discusses why PFO fits can also be compatible with more than one rate-controlling situation.
- Vareda (2023), PDF p. 6, gives the Weber–Morris square-root-time relationship and relates the intercept to boundary-layer contribution; it also explains the Elovich model's declining rate with increasing surface coverage and its limitation far from equilibrium.
- Vareda (2023), PDF pp. 7–9, documents bias introduced by linearisation, warns about post-equilibrium data, and discusses nonlinear regression with AIC/BIC for model selection.
- Mirizadeh et al. (2023), PDF pp. 3 and 5–6, report approximately 120 min for TC and 90 min for CIP on raw date-palm fibre; their PFO/PSO and multi-region Weber–Morris results were checked in the original paper.
- Egbedina et al. (2021), PDF pp. 7–8, report that most uptake occurred within the first 15 min for the tested hybrid biochars and that model selection varied with antibiotic/material treatment. Their kinetic parameter table is in missing ESI Table S2 and remains unavailable.
- Meseguer et al. (2024), PDF pp. 9–11, report more than three days to equilibrium for CIP on activated bagasse biochar, Elovich as the lowest-ARE model (2.52%), Bangham next (3.17%), and a two-region Weber–Morris plot.

**Definition improvements**
- Explained (q_t) as uptake at a particular contact time and (q_e) as equilibrium uptake; contrasted kinetics with isotherms.
- Explained “pseudo” in PFO/PSO as an adapted rate-law form applied to solid-phase uptake under the assumptions described by Vareda, not a direct claim about the molecular reaction order.
- Expanded PFO: the rate is proportional to the remaining uptake gap ((q_e-q_t)); (k_1) controls how quickly the fitted curve approaches (q_e).
- Expanded PSO: the rate is proportional to the square of the remaining uptake gap; clarified the common units of (k_2) when uptake is in mg g⁻¹ and time is in minutes.
- Expanded Weber–Morris: uptake is related to square-root time; the slope is an apparent intraparticle-diffusion parameter and the intercept is an empirical boundary-layer contribution indicator. The notes clarify that a nonzero intercept or multiple linear regions means intraparticle diffusion alone does not explain the full curve.
- Expanded Elovich: (alpha) is the initial-rate parameter and (eta) is associated with the decline in rate as surface coverage develops; retained the far-from-equilibrium limitation.
- Added clear cautions against treating a best PFO/PSO/Elovich fit as proof of a unique mechanism and against ranking contact times across non-matched studies.

**Notation correction**
- Vareda (2023), PDF p. 6, denotes the Weber–Morris intercept as (E) in Eq. (21); REF-09, REF-10 and REF-14 use (C) or step-specific (C_i). The slide retains (C) for its general equation but now documents the source-specific notation rather than implying every paper uses the same symbol.
- Updated KIN-008 to preserve the Vareda equation's (E) and the experimental papers' (C/C_i) notation.

**Repository updates**
- Expanded Slide 11 and its presenter notes in `presentation-content/slide-by-slide-draft.md`.
- Updated the Slide 11 source and caveat row in `presentation-content/citation-map.md`.
- Added the Weber–Morris intercept notation note to `literature-extraction/adsorption-kinetics.md`.
- Revised KIN-008 in `evidence-matrix/adsorption-kinetics.md`.
- Existing extraction and matrix records were retained; no new references were added and no missing ESI parameters were inferred.

**Verified commits**
- Slide 11 expanded definitions: `d8bab6958d75fcd927c4a58ff8cda3e4ff745300`
- Slide 11 Weber–Morris notation note: `9b939fdc15dd89caa2818c7dcbd2cd460e1c2846`
- Extraction notation clarification: `59e5393d02512daa5cb381716a41a2ec82c4fe6e`
- Evidence matrix KIN-008 update: `8245dfa93953003678b72a12f65f1f3b3f944b48`
- Citation map update: `54d68516bc2d4ad8f5c830f3fbeab5bdf1c9f505`

All four working files were fetched from `main` after their updates. The Slide 11 block uses author–date citations, contains no reader-facing REF identifiers, explains all four models and preserves the source-specific notation differences.

## Slide 12 — Thermodynamics of Adsorption

**Status:** Pass; definitions expanded, all three reported equations retained, and source notation corrected.

**Original-source verification**
- Liang et al. (2024), PDF pp. 9–10, Section 3.5, print the three relationships:
  - `ΔG = −RT ln Kd` (Eq. 5, PDF p. 9);
  - `ΔG = ΔH − TΔS` (Eq. 6, PDF p. 10);
  - `ln Kd = −ΔH/(RT) + ΔS/R` (Eq. 7, PDF p. 10).
- The printed equations use `ΔG`, `ΔH` and `ΔS` **without** superscript degree symbols, although the surrounding text describes these as standard thermodynamic parameters. The slide, extraction and evidence matrix now preserve the printed symbols and explicitly record the difference.
- Liang et al. (2024), PDF p. 10, report negative ΔG values for TC adsorption on BC, NFO and NFO/BC; describe NFO adsorption as exothermic and BC/NFO-BC as endothermic; give ΔH = +31.384 kJ mol⁻¹ for NFO/BC; and describe its entropy change as positive. Table S4 is absent from the supplied PDF, so the missing numerical values are not reconstructed.
- Meseguer et al. (2024), PDF p. 5, use 0.025 g adsorbent, 50 mL of 300 mg L⁻¹ CPX solution, pH 3.5 and 72 h at 10, 25, 40 and 55 °C. PDF p. 9 reports equilibrium uptake of 34.6, 41.4, 89.3 and 109.9 mg g⁻¹, respectively; the authors interpret the trend as endothermic. No numerical ΔG, ΔH or ΔS table is supplied in the main paper.
- Mirizadeh et al. (2023), PDF p. 6, report endothermicity qualitatively but state that the Temkin model alone cannot establish the heat-effect direction; the supporting information was not supplied.
- Zhao et al. (2024), PDF p. 11, report increasing temperature-dependent uptake and describe it as endothermic. Its PDF p. 13 values at 298, 308 and 318 K are Langmuir-fitted (q_m) values, not numerical thermodynamic parameters.
- Chen et al. (2024), PDF p. 3, mention thermodynamics in the methods, but accessible numerical thermodynamic results are not present in the supplied main-paper PDF.

**Definition and teaching improvements**
- Expanded Gibbs free energy: explains thermodynamic favourability under the authors' convention and distinguishes it from speed and molecular mechanism.
- Expanded enthalpy: explains positive ΔH as heat absorbed/endothermic and negative ΔH as heat released/exothermic; clarifies that positive ΔH alone does not prove chemisorption.
- Expanded entropy: explains it as a net change in accessible microscopic arrangements/energy and matter dispersal, while avoiding unsupported claims about surface disorder alone.
- Explains how ΔG = ΔH − TΔS combines the enthalpy and entropy contributions and why temperature can affect favourability.
- Retained all three relationships from Liang et al. (2024), including ΔG = −RT ln Kd, the Gibbs–Helmholtz relation and the Van't Hoff equation.
- Explains the Van't Hoff plot as ln Kd against 1/T, with slope −ΔH/R and intercept ΔS/R, and provides unit guidance for R, T, ΔH and ΔS.
- Added (K_d)'s source-specific definition caveat and retained the requirement that a thermodynamic logarithm have a dimensionless argument. The missing Table S4 and unclear standard-state normalisation mean the numerical thermodynamic values cannot be independently reconstructed from the supplied main text.
- Preserved the Meseguer temperature-response example with its operating conditions and all four reported uptake values.
- Kept all cross-study temperature effects system-specific; the selected sources do not support a universal endothermic-adsorption claim.

**Source notation and evidence-quality correction**
- Removed the superscript degree symbols that had been added to Liang et al.'s printed ΔG, ΔH and ΔS equations. Added a notation note explaining that the authors' text describes the quantities as standard but the equations print the symbols without °.
- Added THM-026 to `evidence-matrix/adsorption-thermodynamics.md` to record the printed-symbol audit.
- Updated the Stage 2 extraction to preserve the same printed notation.

**Verified commits**
- Expanded Slide 12 definitions and presenter notes: `d7a4f761ef61407018f204cf2bf913bfa41ff596`
- Slide source-symbol correction: `d52343697c136fdb13878cd688607aa8ea598329`
- Literature extraction notation correction: `a0c0bd81ec6301856979b701344e72bf8d9cb45b`
- Evidence matrix notation audit / THM-026: `76a914a835114b744bceb16fd713811590def076`
- Citation map update: `ce2f20c6bcb9377b7a9d3e6f9595679ac11a802e`
- Restored Gibbs equilibrium relation and Kd definition in Slide 12: `7c0b2ae1d6912d0ca5f8ee1502de4e80d59c3c23`

The slide draft, citation map, thermodynamics extraction and evidence matrix were fetched from `main` after updating. The final Slide 12 block contains all three source equations, expanded definitions, author–date citations and no reader-facing REF identifiers.

## Review-wide citation rule correction

**Status:** Resolved.

The draft-wide instruction was corrected to require author–date citations with PDF page/table/figure locators where appropriate. It now explicitly confines REF-01–REF-15 to internal evidence and audit records.

**Verified change:** Commit `f0ef013f23085d3972de30dd058024c9b0a5bf97`. The updated draft was fetched from `main`; the old rule is absent, the new rule is present, and the file differs from its previous version only by this instruction.
