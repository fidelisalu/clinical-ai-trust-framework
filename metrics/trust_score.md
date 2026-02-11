# Overall Trust Score (OTS)

OTS is a composite indicator for quick comparison.

## Inputs (suggested)
- EGS (Evidence Grounding)
- CRS (Citation Reliability)
- 1 - HR (Hallucination complement)
- CCI (Calibration)
- Bias penalty (optional)

## Simple composite (example)
OTS = 0.30*EGS + 0.30*CRS + 0.20*(1-HR) + 0.20*CCI

## Bias penalty (optional)
If disparity metrics exceed thresholds, apply a penalty:
OTS = OTS - Penalty

This is intentionally configurable by auditors.
