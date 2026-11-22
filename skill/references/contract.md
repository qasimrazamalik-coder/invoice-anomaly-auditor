# Contract

## Capability
Flag duplicate, inconsistent and policy-breaking invoice records for human review without making payment decisions.

## Input root
`findings` with fields: id, severity, users_affected, confidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
