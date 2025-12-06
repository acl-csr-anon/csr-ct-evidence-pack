# Cross-System Reproducibility (CSR) and Contractual Tag (CT) Evidence Pack

This repository provides all experimental materials, raw outputs, evaluation code,
and figures used in the paper:

"Redefining Reproducibility in Generative AI via Cross-System Reproducibility and Contractual Tags"

submitted to ACL (Main Track).

## Contents

- `prompts/`  
  Full definitions of P1 (Dual-Layer Reproducibility) and P2 (Semantic Stability).

- `responses/`  
  All 30 generated outputs from GPT, Gemini, and Claude, stored as structured JSON
  with decoding parameters and CT state.

- `metrics/`  
  Source code for:
  - Cross-System Reproducibility (R)
  - Cognitive Entropy Index (CEI)
  - Semantic Variance Factor (SVF)
  - Resonance Stability (RS)
  - Phase Coherence Score (PCS)

- `analysis/`  
  Intermediate similarity matrices, clustering results, and semantic drift analysis.

- `figures/`  
  All figures used in the paper (PDF and PNG).

- `scripts/`  
  End-to-end evaluation and figure generation scripts.

- `ct_schema/`  
  Minimal JSON schema for Contractual Tags (CT).

## Evaluation Metrics (Formally Adopted)

This repository formally adopts the following five quantitative metrics as the official evaluation framework
for Cross-System Reproducibility and Semantic Stability:

1. **Cross-System Reproducibility (CSR / R)**  
   Measures semantic consistency across different model families (GPT, Gemini, Claude)
   under identical prompts.

2. **Cognitive Entropy Index (CEI)**  
   Quantifies the dispersion of semantic representations across repeated generations.

3. **Semantic Variance Factor (SVF)**  
   Captures intra-model semantic fluctuation under fixed decoding conditions.

4. **Resonance Stability (RS)**  
   Evaluates structural and logical alignment stability across trials.

5. **Phase Coherence Score (PCS)**  
   Measures cross-output coherence in conceptual phase space.

These five metrics are treated as the **official quantitative foundation** of the CSR–CT framework
and are referenced consistently throughout the paper.

## Important Note on Figures and Language Consistency

The figures included in the ACL paper were generated using Japanese-language prompts,
whereas the responses publicly released in this GitHub repository are based on
English-language prompts.

This discrepancy is intentional and does not affect the validity of the experimental
claims. The purpose of this repository is to demonstrate the **structural and semantic
reproducibility framework itself**, not to provide bitwise-identical regeneration of
all figures.

All evaluation logic, experimental design, and reproducibility arguments remain fully
consistent across both language settings. No direct copy-paste alignment between
Japanese figures and English responses is assumed or required.

## Reproducibility

All experiments were conducted with temperature fixed at 0.0.
A single fixed sentence embedding model was used for evaluation.
All scripts required to reproduce the reported results are provided.

## License

For academic and verification purposes only.
Commercial use requires explicit permission.
