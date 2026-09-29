# Perturbation / Failure-Evidence Log

No runtime perturbation results are claimed in this package. The previously described perturbation results were not reproducible from the files available in this ZIP and have therefore not been presented as executed evidence.

## Required future perturbations

### 1. MCP/subagent failure
- Inject a deterministic MCP failure.
- Verify retry/backoff and graceful degradation.
- Preserve raw test output.

### 2. Invalid structured output
- Return a deliberately invalid agent result.
- Verify schema validation rejects it.
- Preserve the validation error.

### 3. Rate-limit condition
- Configure a low request limit in a test.
- Verify the limiter blocks/delays requests as designed.
- Preserve the observed output.
