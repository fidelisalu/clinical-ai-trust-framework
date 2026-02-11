# Risk Gating Protocol

Risk gating prevents unsafe high-tier outputs.

## Step 1 — Assign tier
Assign Tier 0–3 using `framework/risk_tiering_model.md`

## Step 2 — Compare against thresholds
Example suggested thresholds:
- Tier 1: EGS≥0.85, CRS≥0.85, HR≤0.10, CCI≥0.80
- Tier 2: EGS≥0.92, CRS≥0.92, HR≤0.05, CCI≥0.88
- Tier 3: EGS≥0.97, CRS≥0.97, HR≤0.01, CCI≥0.95

## Step 3 — Decide system behavior
- PASS: show output normally
- CONDITIONAL: show safe fallback response with citations only
- FAIL: refuse Tier 2/3 guidance and recommend professional consultation
