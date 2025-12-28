# HIN-FAIR — Notarization Log

This file records any external timestamping or notarization events attached to the canonical document hashes in `meta/HASHES.md`.

## Fields (template)

For each event, record at least:

- Date (UTC)
- Method (for example OpenTimestamps, blockchain, institutional archive)
- Hashes covered (list or reference)
- Proof location or transaction reference
- Notes (optional)

## Example entry (illustrative only)

- Date: 2025-12-27 (UTC)  
- Method: OpenTimestamps  
- Hashes covered:  
  - SHA-256: ...HIN_FAIR_GOVERNANCE_v1_1  
  - SHA-256: ...HIN_FAIR_BACKGROUND_NOTES_v1_1  
- Proof: `ots_receipts/hin_fair_v1_1.ots`  
- Notes: Initial public release notarization.

Update this file whenever you add new notarization events.
