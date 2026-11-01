# Apple Support Request Template — Activation Lock Removal

**Subject line:**
*Activation Lock Removal Request — Device `00008130-XXXX-XXXX-XXXX-XXXXXXXXXXXX` (iPhone **16,1**)*

> Use the exact UDID (`00008130-000208CA10E1401C`) in both placeholders above and below. Replace `[YOUR NAME]` / `[YOUR EMAIL]` / `[YOUR PHONE]` with your Apple ID contact details.

---

## Email body (use the Support ticket below, one per section)

### Section 1 — Account / ownership verification

> I am the lawful owner of the Apple account used to set up this iPhone:
>
> - **Apple ID:** `a•••••@•••••.com` (example mask — replace with your real ID only at submit time)
> - **Password:** you will not send your password; Apple will verify identity independently.
>
> I purchased this iPhone from [seller name] on [date] through [platform]. The box serial **GC6L60N2R0** and any original packaging are available on request for verification.
>
> Asking you to **remove Activation Lock** so I can legally use this device under my account.

### Section 2 — Problem description

> ideviceactivation (`state`) reports **Activation State: Unactivated**. Running `activate -u <UDID>` returns server-side **Activation Lock**: *"This iPhone is linked to an Apple account. Enter the Apple account and password…"*. This means the lock is enforced on **Apple's servers**, not locally. No code fix on the device side can override it — I am asking Apple Support to perform the standard Activation Lock removal review that applies when the device was legitimately set up under a known account.

### Section 3 — Evidence already collected (attach)

- [ ] ideviceactivation output screenshot showing `ActivationState: Unactivated`
- [ ] Screenshot of the full `activate` failure log (Apple prompts requiring input)
- [ ] Screenshot of `ideviceinfo` — system information for this phone
- [ ] Purchase receipt / order confirmation from the seller
- [ ] IMEI / ECID matchable to device serial `GC6L60N2R0`

### Section 4 — What happens after Apple resolves it

After Activation Lock removal, sign into **Settings → General → Transfer or Reset Phone → Erase All Content and Settings**, or use my existing Apple ID in **Settings → Sign In & Security**, then complete setup. Activation requires **just my Apple account** — I do not ask you for additional credentials.

---

## Ticket checklist

Before submitting, confirm:
1. UDID in subject matches `00008130-000208CA10E1401C`.
2. Account owner name listed matches the person submitting.
3. Screenshots included for ideviceactivation failure output.
4. Purchase evidence attached or reference sent separately.
