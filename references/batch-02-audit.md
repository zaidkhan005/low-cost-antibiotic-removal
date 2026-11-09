# Batch 2 PDF Audit — REF-06 to REF-10

**Audit status:** First-pass bibliographic and file-integrity audit complete. Detailed scientific extraction remains for Stage 2.

**Files received:** 5 additional PDFs (Batch 2 of 3).
**Date received:** 9 November 2026.
**Cumulative collection status:** 10 of the fixed 15 references are now present across the original chat and this branched chat. REF-01–REF-05 were retrieved from the connected Library and are recorded in [Batch 1 audit](batch-01-audit.md).
**Result:** All five Batch 2 PDFs open, are unencrypted, have readable first-page metadata and searchable text, and have non-empty final pages containing article end matter/references. No additional paper has been added.

## File-level audit

| REF-ID | Uploaded filename | Pages | Bibliographic verification | Initial topic coverage | Status |
|---|---|---:|---|---|---|
| REF-06 | `Journal of Chemistry - 2017 - Ayawei - Modelling and Interpretation of Adsorption Isotherms.pdf` | 11 | Nimibofa Ayawei, Augustus Newton Ebelegi and Donbebe Wankasi; *Journal of Chemistry*, 2017, Article ID 3039817; DOI 10.1155/2017/3039817. | Adsorption isotherm theory and interpretation, including Henry, Hill–Deboer, Fowler–Guggenheim, Langmuir, Freundlich, Dubinin–Radushkevich and other models; regression and error-function discussion. General modelling source, not antibiotic-specific. | First-pass audit complete |
| REF-07 | `Onvalidity,physicalmeaning,mechanisminsightsandregressionof  adsorptionkineticmodels.pdf` | 14 | João P. Vareda; *Journal of Molecular Liquids*, 2023, 376, 121416; DOI 10.1016/j.molliq.2023.121416. | Pseudo-first-order and pseudo-second-order models, diffusion models, Elovich model, linear versus nonlinear regression and model-selection criteria. Important methodological warning: PFO/PSO fits can arise in systems limited by either surface reaction or diffusion; model fit alone does not identify one mechanism. | First-pass audit complete |
| REF-08 | `Cost-effectiveness of regenerated green materials for removal of pharmaceuticals from wastewater.pdf` | 19 | Despina A. Gkika, Athanasia K. Tolkou, Stavros G. Poulopoulos, Ioannis K. Kalavrouziotis and George Z. Kyzas; *Waste Management*, 2025, 204, 114952; DOI 10.1016/j.wasman.2025.114952. | Review of waste-derived adsorbents, adsorption–desorption–regeneration systems, reuse, circular-economy framing and cost/environmental assessment. The scope is pharmaceuticals broadly, not antibiotics alone; use as regeneration/economic context, not as antibiotic-specific experimental evidence. | First-pass audit complete; scope caveat recorded |
| REF-09 | `Adsorption of Tetracycline and Ciprofloxacin from Aqueous Solution on Raw Date Palm Waste..pdf` | 8 | Shabnam Mirizadeh, Saleh Al Arni, Mahmoud Elwaheidi, Alsamani A. M. Salih, Attilio Converti and Alessandro Alberto Casazza; *Chemical Engineering & Technology*, 2023, 46(9), 1957–1964; DOI 10.1002/ceat.202300193. | Experimental study using raw date-palm waste for TC and CIP; examines pH, adsorbent dose, initial concentration, contact time, temperature and salts; includes isotherm, kinetic and thermodynamic analysis. Supporting Information is referenced as available online but is not included in the uploaded PDF. | First-pass audit complete; SI not included |
| REF-10 | `Green synthesis of ZnO coated hybrid biochar for the synchronous removal of ciprofloxacin and tetracycline in wastewater.pdf` | 10 | Abisola O. Egbedina, Kayode O. Adebowale, Bamidele I. Olu-Owolabi, Emmanuel I. Unuabonah and Morenike O. Adesina; *RSC Advances*, 2021, 11, 18483–18492; DOI 10.1039/D1RA01130H. | Experimental study of kaolinite/coconut-husk hybrid biochar, followed by HCl or KOH activation, for simultaneous CIP and TET adsorption; includes characterization, batch adsorption, isotherms, kinetics and thermodynamic analysis. Electronic Supplementary Information is referenced but is not included in the uploaded PDF. | First-pass audit complete; ESI not included |

## File-integrity checks

- Page counts confirmed from the uploaded PDFs: REF-06 11; REF-07 14; REF-08 19; REF-09 8; REF-10 10.
- All five PDFs are unencrypted and have extractable text on the first and final pages.
- All five contain article end matter/references at the end of the document.
- REF-10 triggered a minor Poppler shared-object warning during metadata inspection, but all 10 pages were readable and text extraction succeeded. No unreadable page was identified.
- REF-09 and REF-10 cite supplementary information available separately; those supplementary files were not part of this upload. Do not assume their contents.
- This is a first-pass bibliographic/file-integrity audit, not a page-by-page validation of every scientific result.

## Scientific-use notes for Stage 2

1. **REF-06:** Extract the exact equation forms, assumptions, parameter definitions and model scope from the PDF. Check dimensional consistency before reusing equations in slides.
2. **REF-07:** Preserve the paper's explicit warning that the common pseudo-order models are empirical and do not uniquely diagnose surface reaction versus diffusion control. Include its regression discussion when explaining model selection.
3. **REF-08:** Separate broad pharmaceutical-removal and circular-economy claims from antibiotic-specific evidence. Report cost estimates only with their original units, basis and stated system boundary.
4. **REF-09:** Experimental evidence is directly relevant to two antibiotic targets. Record its exact test conditions and distinguish observed/derived uptake from fitted model parameters. The SI is not present.
5. **REF-10:** Experimental evidence is directly relevant to simultaneous CIP/TET removal. The abstract contains a repeated material label in one kinetic-model sentence ("KCB-B" appears twice in the sequence); check the full results/tables during extraction rather than silently correcting the apparent discrepancy. The SI is not present.

## Next step

Await Batch 3 (REF-11–REF-15). Keep the fixed 15-paper limit unchanged. Stage 2 extraction can begin after the complete 15-paper corpus is assembled.
