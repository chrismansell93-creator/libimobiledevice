# Evidence Collection Checklist — Apple Support / Seller Dispute

Gather these **before submitting** any Activation Lock or seller-dispute request:

| # | Item | Verification command / source | Confirm? |
|---|------|--------------------------------|----------|
| 1 | ideviceactivation state output | `ideviceactivation state` (run via `/mingw64/bin`) | [ ] |
| 2 | activate failure log | `ideviceactivation activate -u <UDID>` — note the "Activation Lock" lines | [ ] |
| 3 | device info / system details | `ideviceinfo` | [ ] |
| 4 | paired Bluetooth / USB sessions | `idevicebtlogger` session logs | [ ] |
| 5 | Pair validation result | `idevicepair validate -u <UDID>` → SUCCESS | [ ] |
| 6 | full `irecovery -q` output (if in recovery) | `irecovery -q` | [ ] |
| 7 | iPhone model / carrier row | model **iPhone16,1**, carrier rows from ideviceinfo | [ ] |
| 8 | serial number / UDID | `idevice_id -d` or list via `ideviceinfo` | [ ] |
| 9 | Apple ID email matched to setup | screenshot of lock message (mask address) | [ ] |
| 10 | purchase evidence (seller dispute only) | seller name, date, platform, receipt | [ ] |
| 11 | IMEI / ECID match to serial | match against known value `GC6L60N2R0`, ECID `0x000208ca10e1401c` | [ ] |
| 12 | original packaging / box photo | if available for ownership verification | [ ] |

## Timestamps (approximate)
- Purchase date: ________
- Device UDID: `00008130-000208CA10E1401C`
- Serial: `GC6L60N2R0`
- ECID: `0x000208ca10e1401c`
