# Shipment Document Completeness Checker

Review shipments for required documents, consignee details, and carrier handoff.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-shipment-document-completeness-checker.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
