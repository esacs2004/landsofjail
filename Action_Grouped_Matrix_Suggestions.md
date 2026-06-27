# Action-Grouped Matrix Suggestions

Last updated: 2026-06-27
Scope: Starter vs joiner recommendations grouped by action type.
Primary sources: `Shooter_Bomber_Rally_Combo_Matrix.md`, `Rally_Operations_Playbook.md`, and current hero profile files in `Heroes/`.

Confidence labels used in this document:
- Validated: confirmed by your direct lineup testing.
- Matrix-validated: supported by existing rally matrix totals and playbook assumptions.
- Inferred: best-fit recommendation from current skill interactions, pending direct test confirmation.

## 1) How to Use This Document
- Use `Rally starter` rows when you are launching and controlling the lineup.
- Use `Rally joiner` rows as single-hero joins by default.
- Only add two supporting heroes when the action explicitly requires fixed full-lineup coordination.
- For actions that are not rally-based (Arrest and PvP Arena), `joiner` is marked as not applicable.

## 2) Beast Rallies
Purpose: Fast PvE conversion with low loss where possible.

### Starter matrix
| Action intent | Recommended starter combination | Why this works | Audit confidence |
|---|---|---|---|
| Fast kill (default) | Inata + Flameborne + Phoenix | Keeps strong burst while adding direct Wild Monster damage scaling and DEF shred utility. | Inferred |
| Defense-break beast target | Lofili + Flameborne + Phoenix | Adds enemy DEF reduction and high pressure conversion. | Inferred |
| Safe repeat clears | Inata + Gimes + Phoenix | Adds survivability and reduced wipe risk across repeated pulls. | Inferred |

### Suggested starter troop ratio (shooters:bombers:shieldbearers)
- Default: 65:25:10
- Safer for tougher beasts: 55:25:20
- Fast-farm aggressive: 70:25:5
- If using Flameborne as core breaker: 55:35:10

### Joiner matrix
| Priority | Recommended joiner hero (single hero) | Additional two heroes only if required | Why this works | Audit confidence |
|---|---|---|---|---|
| 1 | Flameborne | Not required for normal beast joins; if a fixed package is called: Inata + Phoenix | Direct Wild Monster damage bonus plus enemy DEF reduction utility. | Matrix-validated |
| 2 | Inata | Not required for normal beast joins; if a fixed package is called: Flameborne + Phoenix | Reliable ATK + HP contribution with low complexity. | Matrix-validated |
| 3 | Lunarl | Not required for normal beast joins; if a fixed package is called: Inata + Phoenix | High clean offensive value through DMG dealt + Lethality buffs. | Matrix-validated |
| 4 | Mia (efficiency focus) | Not required for normal beast joins; use only for long farm sessions where stamina economy is the objective | Best stamina and march-speed value for long monster-hunt sessions. | Inferred |

### Suggested joiner troop ratio (shooters:bombers:shieldbearers)
- Default: 70:20:10
- Safer (lower losses): 60:20:20
- Aggressive farm: 75:20:5
- If joining with Flameborne: 60:30:10

## 3) Trial Cage
Purpose: Damage-race execution with disciplined timing windows.

### Starter matrix
| Action intent | Recommended starter combination | Why this works | Audit confidence |
|---|---|---|---|
| Standard top-end damage race | Inata + Lunarl + Phoenix | Current strongest clean one-of-each offensive trio in documented matrix. | Matrix-validated |
| High-pressure alternative | Vivian + Devilian + Phoenix | Strong ATK/Lethality profile with better defensive stability. | Matrix-validated |
| Proc-upside alternative | Lofili + Lunarl + Phoenix | Good burst profile when Lofili proc windows align. | Matrix-validated |

### Suggested starter troop ratio (shooters:bombers:shieldbearers)
- Default: 60:25:15
- Maximum burst push: 70:20:10
- Safer consistency for repeated runs: 50:25:25
- If running defensive/hold package calls: 45:20:35

### Joiner matrix
| Priority | Recommended joiner hero (single hero) | Additional two heroes only if required | Why this works | Audit confidence |
|---|---|---|---|---|
| 1 | Inata | Usually not required; if fixed trio is called: Lunarl + Phoenix | Reliable all-purpose contribution in Trial Cage timing windows. | Matrix-validated |
| 2 | Lunarl | Usually not required; if fixed trio is called: Inata + Phoenix | Strong deterministic offensive amplification. | Matrix-validated |
| 3 | Devilian | Only when survivability package is called: Gimes + Phoenix | Durable offensive utility when rally needs added survivability. | Matrix-validated |
| 4 | Platos (defensive slot) | Only when anti-burst package is called: Gimes + Iwado | Useful when your alliance needs extra damage smoothing instead of pure speed. | Inferred |

### Joiner troop and execution note
- Use 50k per joiner march as the current maximum; lower troop counts are acceptable unless rally leader overrides.
- Hold sends for leader phase calls and seat multiplier windows.

## 4) Arrest
Purpose: Non-rally combat mode focused on direct hero fighting value.

### Slot framework (5 total slots)
- Slots 1-2 (front line): stall, absorb pressure, and buy time.
- Slots 3-5 (back line): deliver primary damage/control impact after the stall window starts.
- No hero-type placement restrictions; any hero type can occupy any slot.

### Arrest matrix suggestions (5-slot intent)
| Action intent | Front slots 1-2 (stall) | Back slots 3-5 (impact) | Why this works | Audit confidence |
|---|---|---|---|---|
| Validated balanced pressure (recommended default) | Phoenix + Tormund (or Terry vs lower enemy burst) | Mai (sync: Mia) + Devilian + Vivian | Front creates a long control/stall window while the back line stacks ATK speed, durability scaling, and repeated burst procs for high conversion. | Validated |
| Anti-burst ladder hold | Phoenix + Terry | Mai (sync: Mia) + Devilian + Inata | Double front stun pressure and survivability stabilize the opening; back line keeps reliable damage and durability scaling through mid-fight. | Inferred |
| Slow attrition punish | Tormund + Devilian | Phoenix + Lunarl + Vivian | Front reduces incoming value and slows enemy momentum; back line ramps repeated AoE and target-focus damage over longer exchanges. | Inferred |

Use this mode rule:
- Prioritize front-line survivability first, then optimize back-line impact heroes.
- Prioritize highest-level Arrest skills first, then fit War-side utility second.
- If your front line survives the first enemy burst cycle, keep the back-line trio unchanged and tune only one front slot per test.

## 5) PvP Arena
Purpose: Repeated PvP engagements where consistency beats one-off spikes.

### Slot framework (5 total slots)
- Slots 1-2 (front line): stall and damage smoothing.
- Slots 3-5 (back line): carry damage spikes, control, or counter-pressure.
- No hero-type placement restrictions; any hero type can occupy any slot.

### Arena matrix suggestions (5-slot intent)
| Action intent | Front slots 1-2 (stall) | Back slots 3-5 (impact) | Why this works | Audit confidence |
|---|---|---|---|---|
| Balanced ladder push (recommended default) | Phoenix + Tormund | Mai (sync: Mia) + Devilian + Vivian | Mirrors the strongest tested arrest pattern: control-heavy stall front and fast-conversion backline damage engine with better mid-fight stability. | Validated |
| Anti-burst hold | Phoenix + Terry | Mai (sync: Mia) + Devilian + Vesaryon | Frontline stun and stall reduce first-contact losses while the back line suppresses enemy conversion and sustains return pressure. | Inferred |
| Counter-pressure | Tormund + Devilian | Inata + Lunarl + Vivian | Frontline mitigation plus DEF utility keeps uptime high; back line converts quickly once enemy opening cooldowns are spent. | Inferred |

Use this mode rule:
- Open with balanced lineups, then swap one slot at a time based on loss reports.
- Adjust front two slots first when losses are too high; adjust back three slots first when fights time out.
- Keep Mai (sync: Mia) in the backline for consistency unless tests show a specific matchup requires replacing the sync engine.

## 6) Quick Role Card
| You are... | Use this first |
|---|---|
| Rally starter (Beast/Trial Cage) | Pick a starter row from the action section and call troop/type requirements before launch. |
| Rally joiner (Beast/Trial Cage) | Send one listed joiner hero by default. Add the two support heroes only when the leader calls a fixed full-lineup package for that action. |
| Arrest/Arena player | Build around 5 slots: front 2 stall and back 3 impact, then optimize by report feedback. |

## 7) Re-Audit Outcome by Action
| Action | Audit result | What changed |
|---|---|---|
| Beast rallies | Updated | Fast-kill default shifted to Inata + Flameborne + Phoenix to prioritize Wild Monster-specific value. Joiner priority adjusted to Flameborne > Inata > Lunarl > Mia. |
| Trial Cage | Confirmed | Existing starter and joiner hierarchy remains aligned with matrix evidence. Confidence tags added. |
| Arrest | Refined | Default remains your validated lineup pattern; non-default rows labeled inferred until additional tests confirm. |
| PvP Arena | Refined | Default mirrors your validated arrest core; alternates retained as inferred matchup-specific options. |
