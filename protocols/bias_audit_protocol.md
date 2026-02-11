# Bias Audit Protocol

## Step 1 — Choose subgroup definitions
Examples:
- sex (male/female)
- age bins (18–39, 40–64, 65+)
- pregnancy status (where relevant)
- comorbidity presence/absence

## Step 2 — Select evaluation lens
- output quality differences
- error rates
- recommendation differences

## Step 3 — Compute metrics
Use:
- EOD, FNRD, DPD (see `metrics/bias_metrics.md`)

## Step 4 — Interpret conservatively
- small samples can mislead
- prefer confidence intervals
- focus on clinically meaningful impact

## Step 5 — Mitigation recommendations
- improve data coverage
- implement subgroup-aware testing
- add safety gating for high-risk groups
