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

## Review-wide citation rule correction

**Status:** Resolved.

The draft-wide instruction was corrected to require author–date citations with PDF page/table/figure locators where appropriate. It now explicitly confines REF-01–REF-15 to internal evidence and audit records.

**Verified change:** Commit `f0ef013f23085d3972de30dd058024c9b0a5bf97`. The updated draft was fetched from `main`; the old rule is absent, the new rule is present, and the file differs from its previous version only by this instruction.
