# analysis

This project is an **evidence pack**, not a full benchmark.

The responses in `responses/` are organized by:

- **Prompt ID** (e.g., `P1` = dual-layer reproducibility, `P2` = semantic stability)
- **Model provider** (`GPT`, `Gemini`, `Claude`)
- **Trial index** (`P1_1.json` ... `P1_5.json`)

## Conceptual analysis axes

The experiments are intended to be read along the following qualitative axes:

### P1: Dual-Layer Reproducibility

For each model and trial, the reader can inspect:

1. **Structural aspects**  
   - Does the answer follow a comparable high-level structure  
     (e.g., introduction → core argument → implications)?
   - Are roles and argumentative steps allocated in similar ways across trials?

2. **Semantic aspects**  
   - Do core claims about “reproducibility in generative AI” remain stable?
   - Does the evaluative stance (e.g., how strict reproducibility should be defined)
     remain consistent across trials despite wording changes?

### P2: Semantic Stability (planned / conceptual)

For prompts like P2 (semantic stability), the intended reading is:

- Keep the **question** fixed.
- Generate multiple trials from the same model.
- Ask whether the **intent, stance, and conceptual core** of the answers
  remain invariant, even when lexical choices differ.

## What this directory does *not* contain

- No automatic metrics.
- No re-copying or re-aggregation of model outputs.
- No new experiments beyond what is already stored under `responses/`.

This directory provides **conceptual guidance** for interpreting the existing
JSON files as experimental evidence.
