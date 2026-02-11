# Terminology

This project uses the following definitions to keep audits consistent.

## Claim
A medically-relevant statement that can be checked against evidence.  
Example: "Drug X reduces HbA1c by ~1% in adults with type 2 diabetes."

## Claim Unit
A claim broken down into the smallest checkable part (one outcome + one population + one intervention + one direction).

## Citation
A reference to an external source (e.g., guideline, paper, clinical trial registry, regulatory update).

## Verified Citation
A citation that:
1) exists, and  
2) is correctly referenced, and  
3) supports the claim being made.

## Hallucination
A claim presented as factual that is not supported by the cited evidence or has no evidence.

## Confidence
A model/system estimate of correctness (explicit probability or implicit language such as “definitely”, “high confidence”).

## Risk Tier
A category describing potential harm if the output is wrong (see `framework/risk_tiering_model.md`).
