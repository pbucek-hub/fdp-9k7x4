# Provisional CAT rules — JCC OM-A Section 7 I3R06 (30 October 2026)

**NOT APPROVED FOR OPERATIONAL USE.** Page 1 explicitly says: DO NOT USE — REFER TO NTC 2026-110 FOR CURRENT APPROVED CH 7. Do not promote this profile to an approved ruleset until the notice and current chapter are checked.

NCC calculations must remain separate and unchanged. The existing CAT calculation paths contain many of these values; this is a traceability and reconciliation checklist, not proof of regulatory approval.

| Section | Source-derived CAT requirement |
|---|---|
| 7.5 | Acclimatised after three consecutive local nights within two-hour time-zone width; status lost after duty ends >2h different from departure |
| 7.8 | Acclimatised early/late critical duties: max 3 consecutive and 4 per 7 days, 34h break; night-series conditions require separate checks |
| 7.11 | Delayed report <4h: original band, actual start; >=4h: more limiting band, FDP start original+4h; >=10h undisturbed may count as rest |
| 7.13 | Standby max 12h; after 6h, reduce allowable FDP by standby exceeding 6h; no callout requires 12h rest |
| 7.14 | Minimum report 60min; post-flight duty minimum 30min; FDP ends on-chocks/engines-off |
| 7.14.2 | Acclimatised FDP table rows: 0600-0659 [13,12.25,11.5,10.75,10,9.5,9,9]; 0700-1259 [14,13.25,12.5,11.75,11,10.5,10,9.5]; 1300-1759 same as 0600; 1800-2159 [12,11.25,10.5,9.75,9,9,9,9]; 2200-0559 [11,10.25,9.5,9,9,9,9,9] |
| 7.14.3 | Non-acclimatised preceding rest <=18h or >30h: [13,12.25,11.5,10.75,10,9.25,9]; >18h to 30h: [11.5,11,10.5,9.75,9,9,9] |
| 7.15 | Two-pilot scheduled sector >7-9h treated as 2 acclim/4 nonacclim sectors; >9-11h 3/4; >11h 4/not applicable. Additional current type-rated pilot removes these penalties |
| 7.16 | In-flight relief: >=3h rest, bunk extension 1/2 rest max 18h FDP; screened reclining seat 1/3 rest max 15h; qualified relieving pilot |
| 7.17 | Split duty qualifying rest >=3h and <=10h: extension half consecutive rest; exclude at least 30min pre/post duties |
| 7.18 | Minimum rest max(previous duty,12h); narrowly defined away-base accommodation exception; local night after duty incl positioning >18h |
| 7.19-7.21 | PIC discretion up to 3h with restrictions, fatigue risk assessment and Centrik reporting deadlines |
| 7.22 | Days off: 34h incl two local nights; max 7 consecutive duty days; 2 consecutive off/14d; 7/28d; average 8/28d over 3 periods; 96/year |
| 7.23-7.24 | Flight 100h/28d and 900h/12mo; duty 55h/7d,95h/14d,190h/28d,2000h/12mo; special half-credit accounting for qualifying standby and positioning |

## Implementation status

- Existing CAT table and cumulative limits in index.html were inspected and match the values above.
- CAT mode now displays an explicit non-approved warning. NCC is untouched.
- **Not yet validated**: all edge cases, 7.8 night series, 7.19-7.21 discretion, and 7.24 accounting; no operational compliance assertion.
- **Blocked**: NTC 2026-110 and current approved Chapter 7 are required before approving or replacing the CAT engine.
