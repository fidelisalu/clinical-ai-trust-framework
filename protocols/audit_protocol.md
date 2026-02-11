# Audit Protocol (CATF)

This protocol defines a repeatable audit procedure.

## Step 1 — Define scope
- System name/version
- Intended users (clinicians, students, etc.)
- Intended use (Tier 0–3)
- Data sources (if applicable)

## Step 2 — Build audit set
- Create 20–50 prompts representative of expected usage
- Include edge cases and high-risk scenarios (if Tier 2/3)

## Step 3 — Generate outputs
- Record model/system output
- Record any citations provided
- Record confidence signals (explicit or implied)

## Step 4 — Extract claims
- Break output into claim units
- Count total claims (N)

## Step 5 — Verify citations
- Check existence, attribution, and support per claim
- Compute CRS

## Step 6 — Compute grounding + hallucinations
- Compute EGS
- Compute HR

## Step 7 — Calibration check
- Convert confidence language to numeric confidence where feasible
- Compute CCI

## Step 8 — Bias audit (if applicable)
- Compare outputs or error rates across groups
- Compute bias metrics

## Step 9 — Risk tier gating decision
- Based on tier thresholds, decide:
  - pass
  - conditional pass (safe fallback)
  - fail

## Step 10 — Report
Produce a short audit report:
- scores (EGS, CRS, HR, CCI, OTS)
- key failure modes
- recommended fixes
