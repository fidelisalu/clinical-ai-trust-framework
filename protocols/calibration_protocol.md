# Calibration Protocol

## Step 1 — Identify confidence signals
- explicit: “0.8 probability”
- implicit: “definitely”, “likely”, “maybe”

## Step 2 — Map language to numeric bands (example)
- “definitely / certain” -> 0.95
- “very likely” -> 0.85
- “likely” -> 0.75
- “possible” -> 0.55
- “uncertain / not sure” -> 0.40

## Step 3 — Score correctness
For each claim:
- Correct = 1 if supported by evidence
- Correct = 0 otherwise

## Step 4 — Compute CCI
Use `metrics/confidence_calibration_index.md`

## Step 5 — Recommended fixes if miscalibrated
- tighten language
- add uncertainty defaults
- gate high-confidence statements behind citation checks
