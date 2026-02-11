# Confidence Calibration Index (CCI)

CCI measures mismatch between stated confidence and actual correctness.

## Inputs
For each claim i:
- Confidence_i ∈ [0,1] (explicit or inferred from language)
- Correct_i ∈ {0,1}

## Calibration gap
Gap = | mean(Confidence) - mean(Correct) |

## CCI
CCI = 1 - Gap

CCI closer to 1 is better.

## Guidance (suggested)
- Tier 1+: CCI ≥ 0.80
- Tier 2: CCI ≥ 0.88
- Tier 3: CCI ≥ 0.95
