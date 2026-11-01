# Escalation Ladder — Apple Support / Seller Dispute

Resolve over **72 hours**, with a contact window after each step:

## Level 0 — Self-service (Day 0)
- Run `ideviceactivation state` → check it stays **Unactivated**.
- Run `ideviceactivation activate -u <UDID>` → expect `Activation Lock` message (the lock lives on Apple's server; no device-side fix is possible).
- Take the evidence screenshots listed in `EvidenceCollectionChecklist.md`.

## Level 1 — Local technical review (Day 0)
- Confirm no pre-existing pairing conflict: `idevicepair validate -u <UDID>` → SUCCESS.
- If Activation Lock has already been set up under your account, note the email address in the lock prompt — that's who you should ask. If you can supply that account on the activation screen, set up the phone normally right away.
- Otherwise move to Level 2.

## Level 2 — Apple Support direct ticket (Day 1)
Submit `AppleSupportRequestTemplate.md` (review section by section).
Expect response within **48 hours**.
Expect resolution **±1 day** once Apple performs the standard Activation Lock removal review for a legitimate setup under the registered account.

If **still blocked** at Day ~3:

## Level 3 — Escalate (Day 3–5)
- Ask the support agent to escalate or call the priority line: `+1 800 692 7765` (US), or your local Premium tier line.
- Reference: *"my case #ASC-xxx did not resolve Activation Lock after 48h; please escalate as blocked."*

If **still blocked** at Day ~5–7:

## Level 4 — Vendor warranty / seller contract (Day 5–7)
- Seller dispute (`SellerDisputeTemplate.md`) if purchase evidence exists — keep package photos.
- Report to [platform/credit card] chargeback if applicable.

## Level 5 — Legal path (Day 7+)
- Document chain-of-custody, purchase, delivery attempts, Apple's denial reasons.
- If purchased new/refurb from a merchant, merchant handling agreement with Apple may apply to Activation Lock.

## Recovery timeline
| Step | Day | Outcome |
|------|-----|---------|
| 0 – evidence collection | 0 | device shows Unactivated |
| 1 – self-check | 0 | same result |
| 2 – Apple Support ticket | 1 | resolves in 1–3 days |
| 3 – escalation request | 3–5 | if unresolved, go 4 |
| 4 – seller dispute | 5–7 | if still blocked |
| 5 – legal review | 7+ | documented next steps |
