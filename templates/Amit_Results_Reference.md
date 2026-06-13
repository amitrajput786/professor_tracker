# Amit's Results Reference — for Opening Angles

Use ONE of these per professor, matched to their stated open question.
Never invent numbers — these are the only verified results to cite.

## Track A — DM-FNet (Biomedical AI / WBC classification)
- Published: Elsevier BSPC 2026, DOI: 10.1016/j.bspc.2026.109666
- PBC dataset accuracy: 99.58%
- DKCAB ablation gain: +9.01pp
- Raabin dataset accuracy: 98.54%
- Basophil F1 = 0.15 (rare-class collapse, 0.5% of dataset — points to
  active learning / synthetic augmentation as remedy)
- Eosinophil F1 = 0.10 (cross-domain collapse, PBC→Raabin)
- Deployed model: 1.9M parameters (compressed from 3.41M)
- Active project: compressing further to ~30K parameters for edge deployment
  (incomplete — frame as live research-in-progress)
- HuggingFace: huggingface.co/spaces/adffedccasfe/WBC

## Track B/C — Drug Discovery GCN (Wall A)
- Repo: github.com/amitrajput786/Drug_discovery1
- Stack: AlphaFold + RDKit Morgan fingerprints + DeepChem/PyTorch Geometric, Tox21
- Wall: confident predictions on novel scaffolds are confidently WRONG, not
  uncertain — Morgan fingerprints lose pharmacophoric spatial relationships
  outside training vocabulary. No calibrated uncertainty head exists yet.
- Use for: cheminformatics/QSAR/docking/XAI professors (Track B "Wall A")

## Track B — Polymer GNN (Wall B)
- Dual-encoder GCN+Transformer (SMILES/BigSMILES → HOMO-LUMO gap, charge
  delocalization index, hydrolysis activation energy, water diffusion
  coefficient)
- Wall: fusion gate collapses on held-out hyperbranched polymers — near-zero
  weight to graph encoder, near-full weight to sequence branch. Predictions
  are sequence-plausible but topologically incorrect. Linear chains are ~10x
  overrepresented vs hyperbranched in training data.
- Use for: molecular/polymer GNN, equivariant ML, generative chemistry
  professors (Track B "Wall B")

## Track D — Spectrofluorometer (microplastics)
- Thesis: AI-Integrated Portable Spectrofluorometer, NIT Rourkela
- Hardware: Raspberry Pi 4B, Pi Camera Module 3 (IMX708), 365nm UV LEDs,
  IRLZ44N MOSFET, DS18B20, custom KiCad PCB, CD/PVP/PAM carbon-dot paper strips
- Results:
  - Tap water G/G0: R² = 0.844 (70-140 ppm range has mid-concentration
    instability — frame as "outliers from coating variability/LED thermal
    drift, same afternoon" if pressed)
  - Tap water G/B: R² = 0.693, p = 0.020
  - Milk G/B: R² = 0.911, p = 0.012
  - Blind prediction: 129.6 ppm vs 130 ppm actual (0.3% error)
- Analyte: polystyrene microplastics (NEVER heavy metals)
- GitHub: github.com/amitrajput786/UV_Visible-Portable-Device-
- Use for: fluorescence/optical sensing, carbon dot, microplastic detection
  professors (Track C/D)

## Hard rules — apply to every email/profile
- "5yr Integrated Masters in Chemistry (AI & Computational Chemistry)" —
  never "Integrated M.Sc." or "Masters in Chemistry"
- ISI Kolkata: UNCONFIRMED — never mention until confirmed
- Never use "funded PhD" (all European PhDs are funded) or "internship"
  (for Indian outreach only — not relevant to Europe track)
- Every citation must be manually verified against the professor's
  institutional page or Google Scholar before use — never trust AI-generated
  citations as final
