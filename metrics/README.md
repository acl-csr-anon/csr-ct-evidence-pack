# metrics

No automatic quantitative metrics are reported in this evidence pack.

- The purpose of this repository is to **document concrete model responses**
  and the **prompting / annotation setup** (see `prompts/`, `responses/`,
  and `ct_schema/`), so that others can inspect and, if desired, re-analyze
  the data themselves.
- We deliberately **do not**:
  - recompute scores,
  - aggregate responses into new datasets, or
  - perform large-scale statistical evaluation.

Researchers who wish to derive quantitative metrics (e.g., distributional
similarity, structural stability scores) are expected to do this **downstream**
using the existing JSON files in `responses/`.
