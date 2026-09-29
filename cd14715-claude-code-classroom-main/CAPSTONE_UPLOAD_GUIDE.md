# Capstone Upload Package

This ZIP contains the complete original classroom project plus `capstone-evidence/`.

The evidence folder contains the generated tests, system outputs, perturbation evidence,
calibration report, routing evidence, screenshots, and reflection documents.

Important: the policy project's true end-to-end Anthropic API run was not generated because
no API key/cassette set was available in the offline environment. It is explicitly marked
in the evidence instead of being fabricated.

Final live command when the course/API environment is configured:

```bash
policy-extractor pipeline data/policies/ --routing-out routing_decisions.json --spot-check-pct 0.2 --seed 42
```
