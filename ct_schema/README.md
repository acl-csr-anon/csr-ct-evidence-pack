# ct_schema

This directory documents the schema used for the `ct_state` field that appears
in the JSON response files under `responses/`.

- We **do not** re-store or re-process any model outputs here.
- We only specify the structure and meaning of metadata fields.

## Fields

- `ct_version`: Version identifier for this schema (e.g., `"1.0"`).
- `intent`: Short natural-language description of what the model is being asked.
- `constraint`: Description of style or process constraints (e.g., tone, independence).
- `semantic_anchor`: List of key concepts that should anchor the model’s response.

The formal machine-readable schema is provided in `ct_schema.json`.
