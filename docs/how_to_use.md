# How to Use CATF

## If you are auditing a system
1) Determine intended risk tier (0–3)
2) Build a prompt set (20–50 prompts)
3) Run outputs and record citations/confidence
4) Extract claims and fill `sample_claim_annotations.csv`
5) Compute:
- EGS
- CRS
- HR
- CCI
6) Apply risk gating thresholds
7) Write an audit report

## If you are building a system
Use CATF as acceptance criteria:
- Add citation verification
- Add uncertainty defaults
- Add tier gating
- Add subgroup test coverage
