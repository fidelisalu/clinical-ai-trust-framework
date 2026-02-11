# Bias & Fairness Metrics (Clinical context)

Bias auditing evaluates disparities across subgroups (sex, age group, race/ethnicity where appropriate, pregnancy status, comorbidities).

## Common metrics

### Equal Opportunity Difference (EOD)
Difference in true positive rates across groups:
EOD = TPR_groupA - TPR_groupB

### False Negative Rate Disparity (FNRD)
FNRD = FNR_groupA - FNR_groupB

### Demographic Parity Difference (DPD)
DPD = P(positive_outcome | groupA) - P(positive_outcome | groupB)

## Notes
- Use clinically meaningful groupings
- Avoid over-interpreting small samples
- Prefer confidence intervals and stratified analysis where possible
