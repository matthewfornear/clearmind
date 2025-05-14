# Multi-Gated mRNA Therapeutic for Alzheimer's Disease

**Author:** Matthew Fornear  
**Contact:** [x.com/fixitorgotojail](https://x.com/fixitorgotojail) • [github.com/matthewfornear](https://github.com/matthewfornear)

---

## Overview

This project presents a prototype mRNA therapeutic capable of addressing all four major hallmarks of Alzheimer's disease using a single logic-controlled transcript. Rather than expressing a static payload, the mRNA is designed to activate selectively inside pathologically altered brain cells.

The first functional module targets amyloid-β clearance through the secretion of neprilysin, driven by intracellular detection of elevated Aβ levels.

---

## Mechanism of Action

The construct is built to evaluate intracellular states and express corrective proteins conditionally:

- **Amyloid-beta accumulation** → triggers expression of secretable neprilysin (tPA::neprilysin)
- **Tau hyperphosphorylation** → triggers PP2A or tau-stabilizing chaperones
- **Oxidative stress / metabolic dysfunction** → triggers neurotrophins (e.g., BDNF, NT-3)
- **Glial inflammation (CD68+, IL-1β+)** → triggers anti-inflammatory factors like IL-10

Gating logic is enforced at the RNA level through aptamer-controlled folding, ribozymes, untranslated region targeting, and miRNA suppression. The delivery vector is intended to be CNS-specific via RVG-tagged lipid nanoparticles.

---

## Files

- `rnafold_mfe_structure.pdf` – Secondary structure for minimum free energy configuration  
- `mountain_plot.pdf` – Visualization of structural openness, including 5' end accessibility  
- `sequence.txt` – Full codon-optimized mRNA (DNA form), including UTRs and poly(A) tail  
- `dot_bracket_output.txt` – Dot-bracket representation from RNAfold  
- `pitch_letter.pdf` – Cover letter and summary sent to potential collaborators

---

## Current Status

- Sequence is fully constructed, codon-optimized, and validated by RNAfold  
- MFE confirmed at **-631.3 kcal/mol** with ensemble consistency  
- 5′ UTR and start codon are translation-accessible  
- Provisional patent filed for oncology application of the same framework  
- Ready for lab testing, collaboration, or pitch packaging

---

## Next Steps

- Extend to include additional gated payloads for tau and inflammation  
- Simulate logic compatibility across modules  
- Prepare for in vitro synthesis and functional testing in cell lines  
- Partner with academic or biotech labs to validate therapeutic effect

---

## Attribution

This work was developed independently using publicly available protein data (Neprilysin: UniProt P08473) and validated in silico using [ViennaRNA RNAfold](http://rna.tbi.univie.ac.at/).

---

