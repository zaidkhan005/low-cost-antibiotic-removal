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

## Review-wide citation rule correction

**Status:** Resolved.

The draft-wide instruction was corrected to require author–date citations with PDF page/table/figure locators where appropriate. It now explicitly confines REF-01–REF-15 to internal evidence and audit records.

**Verified change:** Commit `f0ef013f23085d3972de30dd058024c9b0a5bf97`. The updated draft was fetched from `main`; the old rule is absent, the new rule is present, and the file differs from its previous version only by this instruction.
