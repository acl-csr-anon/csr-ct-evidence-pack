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

## Reproducibility

All experiments were conducted with temperature fixed at 0.0.
A single fixed sentence embedding model was used for evaluation.
All scripts required to reproduce the reported results are provided.

## License

For academic and verification purposes only.
Commercial use requires explicit permission.
