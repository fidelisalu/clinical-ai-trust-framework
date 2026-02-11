# Clinical Risk Tiering Model

CATF uses risk tiers to ensure higher-risk outputs face stricter trust thresholds.

## Tier 0 — Informational
General medical information (definitions, basic concepts) with minimal patient specificity.

Examples:
- “What is hypertension?”
- “Common symptoms of anemia”

## Tier 1 — Advisory (Low risk)
General guidance with clear uncertainty and recommendation to consult a professional.

Examples:
- “Possible next steps to discuss with a clinician”
- “What guidelines generally recommend”

## Tier 2 — Decision Support (Moderate risk)
Suggests diagnostic or treatment options and may influence clinician action.

Examples:
- “Based on symptoms, consider differential diagnoses…”
- “Guideline-directed therapy options include…”

## Tier 3 — High-Risk Intervention Guidance
Outputs that could directly lead to harm if wrong.

Examples:
- Dosage instructions
- Contraindication-sensitive recommendations
- Emergency triage instructions
- Pregnancy/pediatric dosing guidance

---

## Tier gating principle
The system must not generate Tier 2 or Tier 3 guidance unless trust thresholds are met (grounding, citation reliability, calibration).
