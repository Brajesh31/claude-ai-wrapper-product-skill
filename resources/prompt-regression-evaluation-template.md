# Prompt Regression Evaluation Template

## Evaluation context
- Product feature:
- Prompt version:
- Model and version:
- Evaluator:
- Dataset version:
- Date:

## Representative cases
| Case ID | User intent | Input fixture | Expected output constraints | Expected refusal/approval behavior |
|---|---|---|---|---|
| | | | | |

## Results
| Case ID | Correctness | Format validity | Groundedness | Safety | Latency | Tokens/cost | Pass? |
|---|---:|---:|---:|---:|---:|---:|---|
| | | | | | | | |

## Regression review
- New failures:
- Existing failures:
- Output drift:
- Cost or latency regression:
- Prompt injection and adversarial cases:
- Human-review cases:

## Release decision
- Pass threshold:
- Blocking failures:
- Mitigations:
- Rollback version:
- Approved by:
- Date:

Keep the evaluation set versioned. Do not rely only on a few hand-picked happy-path prompts.
