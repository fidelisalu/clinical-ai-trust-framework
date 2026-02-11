# Trust Dimensions Model

CATF defines five required dimensions for evaluating a clinical AI system.

## 1) Evidence Grounding
Measures the degree to which the system’s output claims are supported by verifiable sources.

Core checks:
- Claim extraction and enumeration
- Claim-to-citation mapping
- Source authority weighting

Primary metric:
- Evidence Grounding Score (EGS) — see `metrics/evidence_grounding_score.md`

---

## 2) Citation Reliability
Measures whether citations:
- exist,
- are not fabricated,
- are correctly attributed, and
- directly support the claim.

Primary metric:
- Citation Reliability Score (CRS) — see `metrics/citation_reliability_score.md`

---

## 3) Bias & Fairness Auditing
Measures whether the system’s behavior differs across demographic or clinical subgroups.

Primary metrics:
- Equal opportunity difference
- False negative disparity
- Demographic parity difference
See `metrics/bias_metrics.md`

---

## 4) Confidence Calibration
Measures alignment between system confidence and real correctness.

Primary metric:
- Confidence Calibration Index (CCI) — see `metrics/confidence_calibration_index.md`

---

## 5) Clinical Risk Stratification
Classifies outputs by potential harm if incorrect, then gates outputs accordingly.

See:
- `framework/risk_tiering_model.md`
- `protocols/risk_gating_protocol.md`
