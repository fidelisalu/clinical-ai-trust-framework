# Evidence Grounding Score (EGS)

EGS quantifies the proportion of claims supported by verifiable evidence.

## Process
1) Extract all claims from the output (N claims).
2) For each claim i, decide if it is verifiable and supported by at least one valid source.
3) Weight support by source authority.

## Base formula
EGS = (Σ SupportedClaim_i * AuthorityWeight_i) / N

Where:
- SupportedClaim_i ∈ {0,1}
- AuthorityWeight_i ∈ [0,1]

## Recommended authority weights (example)
- Clinical practice guideline / consensus statement: 1.00
- Systematic review / meta-analysis: 0.90
- Randomized controlled trial: 0.85
- Observational study: 0.75
- Secondary summary source: 0.40
- Unverifiable / non-authoritative: 0.00

## Threshold guidance (suggested)
- Tier 0: EGS ≥ 0.70
- Tier 1: EGS ≥ 0.85
- Tier 2: EGS ≥ 0.92
- Tier 3: EGS ≥ 0.97
