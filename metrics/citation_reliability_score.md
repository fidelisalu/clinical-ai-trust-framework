# Citation Reliability Score (CRS)

CRS measures whether citations are valid and correctly support the claim.

## Components
For each citation:
1) Existence: does the source exist?
2) Attribution: is it correctly referenced?
3) Support: does it support the specific claim?

## Per-claim CRS
For each claim i:
CRS_i = (Existence_i + Attribution_i + Support_i) / 3

Each component is 0 or 1.

## Overall CRS
CRS = (Σ CRS_i) / N

## Threshold guidance (suggested)
- Tier 1+: CRS ≥ 0.85
- Tier 2: CRS ≥ 0.92
- Tier 3: CRS ≥ 0.97
