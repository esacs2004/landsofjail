# Shooter and Bomber Rally Combo Matrix

Last updated: 2026-06-25
Scope: Shooter-focused and Bomber-focused rally setup matrix for initiated rallies and joiner participation.
Source basis: Hero profiles in `Heroes/` and current 3-slot rally model from `Rally_Operations_Playbook.md`.

## Assumptions Used for "Overall Boost"
- Matrix build default: always evaluate listed combat War skills at their highest documented progression value.
- Initiated rally rows assume the rally leader controls 3 hero slots.
- Hard slot rule: use exactly one Shooter, one Bomber, and one Shieldbearer across the 3 rally hero slots.
- Joiner rows treat each entry as a one-hero contribution option when joining another player's rally.
- Deterministic combat effects are listed directly. Proc-based effects are called out separately.
- Non-combat development effects (research, construction, gathering, etc.) are excluded.

## Attack Matrix (Current Scope)
All existing Shooter and Bomber matrix sections below are attack-side rally guidance.

## Shooter Rally Matrix

### Purpose: Damage-Race
Purpose note: prioritize fastest reliable kill speed and burst conversion.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Inata + Lunarl + Phoenix | +25% Troops ATK; +50% Troops DMG dealt; +25% Troops Lethality; +50% Troops HP; +20% stun chance on attack. |
| Initiated rally | Lofili + Vivian + Phoenix | +50% Troops ATK; +25% Troops DMG dealt; +25% Troops HP; +16% rally-attack Lethality; plus Lofili proc DMG spike. |
| Initiated rally | Devilian + Lunarl + Phoenix | +25% Troops DMG dealt; +50% Troops Lethality; +50% Troops HP; +25% Troops DEF; +16% rally-attack DEF; +20% stun chance on attack. |
| Joiner rally | Inata | +25% Troops ATK; +25% Troops HP. |
| Joiner rally | Lofili | +25% Troops ATK; plus proc: 50% chance to gain +50% Troops DMG when attacking. |
| Joiner rally | Devilian | +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF (Devilian equipment War skill). |

### Purpose: Breakthrough (high-defense target)
Purpose note: break entrenched targets by stacking defense shred, penetration pressure, and conversion.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Lofili + Flameborne + Phoenix | +25% Troops ATK; +25% Troops DMG dealt; +25% Troops HP; -20% Enemy Troops DEF; +20% stun chance on attack; plus Lofili proc DMG spike. |
| Initiated rally | Devilian + Samir + Phoenix | +14% Troops ATK; +37% Troops Lethality; +25% Troops DMG dealt; +25% Troops HP; +25% Troops DEF; +16% rally-attack DEF; -20% Enemy Troops HP; +20% stun chance on attack. |
| Initiated rally | Inata + Flameborne + Iwado | +25% Troops ATK; +25% Troops HP; +14% Troops DEF; +12% Troops HP; -20% Enemy Troops DEF; -20% Enemy Troops Lethality. |
| Joiner rally | Inata | +25% Troops ATK; +25% Troops HP. |
| Joiner rally | Lofili | +25% Troops ATK; plus proc: 50% chance to gain +50% Troops DMG when attacking. |
| Joiner rally | Devilian | +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF (Devilian equipment War skill). |

### Purpose: Sustain/Hold
Purpose note: win long fights by maximizing durability, mitigation, and uptime.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Platos + Gimes + Iwado | +20% Troops DMG taken reduction; +25% Troops HP; +14% Troops DEF; +12% Troops HP; -20% Enemy Troops Lethality. |
| Initiated rally | Inata + Gimes + Phoenix | +25% Troops ATK; +25% Troops DMG dealt; +75% Troops HP; +20% Troops DMG taken reduction; +20% stun chance on attack. |
| Initiated rally | Devilian + Gimes + Gerd | +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF; +25% Troops HP; +20% Troops DMG taken reduction; +25% Troops DEF; -20% Enemy Troops ATK. |
| Joiner rally | Platos | +20% Troops DMG taken reduction. |
| Joiner rally | Inata | +25% Troops ATK; +25% Troops HP. |
| Joiner rally | Devilian | +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF. |

### Purpose: Utility/Efficiency
Purpose note: favor repeatable, low-risk clears over peak one-cycle burst.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Inata + Gimes + Phoenix | +25% Troops ATK; +25% Troops DMG dealt; +75% Troops HP; +20% Troops DMG taken reduction; +20% stun chance on attack. |
| Initiated rally | Platos + Ekko + Iwado | +20% Troops DMG taken reduction; +25% Troops Lethality; +14% Troops DEF; +12% Troops HP; -20% Enemy Troops Lethality. |
| Initiated rally | Devilian + Gimes + Vesaryon | +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF; +25% Troops HP; +20% Troops DMG taken reduction; -20% Enemy DMG. |
| Joiner rally | Inata | +25% Troops ATK; +25% Troops HP (reliable all-purpose contribution). |
| Joiner rally | Platos | +20% Troops DMG taken reduction (safe repeatability). |
| Joiner rally | Devilian | +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF (simple offensive add-on). |

## Bomber Rally Matrix

### Purpose: Damage-Race
Purpose note: prioritize fastest reliable kill speed and burst conversion.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Vivian + Inata + Phoenix | +50% Troops ATK; +25% Troops DMG dealt; +50% Troops HP; +16% rally-attack Lethality; +20% stun chance on attack. |
| Initiated rally | Lunarl + Inata + Phoenix | +25% Troops ATK; +50% Troops DMG dealt; +25% Troops Lethality; +50% Troops HP; +20% stun chance on attack. |
| Initiated rally | Samir + Devilian + Phoenix | +14% Troops ATK; +37% Troops Lethality; +25% Troops DMG dealt; +25% Troops HP; +25% Troops DEF; +16% rally-attack DEF; -20% Enemy Troops HP; +20% stun chance on attack. |
| Joiner rally | Vivian | +25% Troops ATK; +16% rally-attack Lethality (equipment War skill). |
| Joiner rally | Lunarl | +25% Troops DMG dealt; +25% Troops Lethality. |
| Joiner rally | Samir | +14% Troops ATK; +12% Troops Lethality; -20% Enemy Troops HP. |

### Purpose: Breakthrough (high-defense target)
Purpose note: break entrenched targets by stacking defense shred, penetration pressure, and conversion.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Samir + Lofili + Phoenix | +25% Troops ATK; +12% Troops Lethality; +25% Troops DMG dealt; +25% Troops HP; -20% Enemy Troops HP; +20% stun chance on attack; plus Lofili proc DMG spike. |
| Initiated rally | Flameborne + Devilian + Phoenix | +25% Troops Lethality; +25% Troops DMG dealt; +25% Troops HP; +25% Troops DEF; +16% rally-attack DEF; -20% Enemy Troops DEF; +20% stun chance on attack. |
| Initiated rally | Lunarl + Inata + Iwado | +25% Troops ATK; +25% Troops DMG dealt; +25% Troops Lethality; +25% Troops HP; +14% Troops DEF; +12% Troops HP; -20% Enemy Troops Lethality. |
| Joiner rally | Samir | +14% Troops ATK; +12% Troops Lethality; -20% Enemy Troops HP. |
| Joiner rally | Flameborne | -20% Enemy Troops DEF. |
| Joiner rally | Lunarl | +25% Troops DMG dealt; +25% Troops Lethality. |

### Purpose: Sustain/Hold
Purpose note: win long fights by maximizing durability, mitigation, and uptime.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Gimes + Platos + Iwado | +25% Troops HP; +20% Troops DMG taken reduction; +20% Troops DMG taken reduction; +14% Troops DEF; +12% Troops HP; -20% Enemy Troops Lethality. |
| Initiated rally | Tormund + Platos + Phoenix | +25% Troops DEF; +50% Troops HP; +20% Troops DMG taken reduction; +25% Troops DMG dealt; +20% stun chance on attack from Tormund; +20% stun chance on attack from Phoenix. |
| Initiated rally | Samir + Platos + Vesaryon | +14% Troops ATK; +12% Troops Lethality; +20% Troops DMG taken reduction; -20% Enemy Troops HP; -20% Enemy DMG. |
| Joiner rally | Gimes | +25% Troops HP; +20% Troops DMG taken reduction. |
| Joiner rally | Tormund | +25% Troops DEF; +25% Troops HP. |
| Joiner rally | Lunarl | +25% Troops DMG dealt; +25% Troops Lethality. |

### Purpose: Utility/Efficiency
Purpose note: favor repeatable, low-risk clears over peak one-cycle burst.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Vivian + Platos + Phoenix | +25% Troops ATK; +25% Troops DMG dealt; +25% Troops HP; +20% Troops DMG taken reduction; +16% rally-attack Lethality; +20% stun chance on attack. |
| Initiated rally | Ekko + Inata + Iwado | +25% Troops ATK; +25% Troops Lethality; +25% Troops HP; +14% Troops DEF; +12% Troops HP; -20% Enemy Troops Lethality. |
| Initiated rally | Gimes + Devilian + Vesaryon | +25% Troops HP; +20% Troops DMG taken reduction; +25% Troops Lethality; +25% Troops DEF; +16% rally-attack DEF; -20% Enemy DMG. |
| Joiner rally | Vivian | +25% Troops ATK; +16% rally-attack Lethality (high-value single joiner pick). |
| Joiner rally | Gimes | +25% Troops HP; +20% Troops DMG taken reduction (safe repeat value). |
| Joiner rally | Ekko | +25% Troops Lethality (low-complexity offensive contribution). |

## Defense Matrix
Defense scope: these combinations prioritize survivability, mitigation, and anti-pressure while preserving one Shooter + one Bomber + one Shieldbearer across S1-S3.

### Shooter Defense Matrix

#### Purpose: Defense/Hold
Purpose note: shooter-led defensive setups that hold long exchanges and reduce collapse risk.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Platos + Gimes + Iwado | +40% Troops DMG taken reduction; +37% Troops HP; +14% Troops DEF; -20% Enemy Troops Lethality. |
| Initiated rally | Devilian + Gimes + Gerd | +50% Troops DEF; +16% rally-attack DEF; +25% Troops HP; +20% Troops DMG taken reduction; +25% Troops Lethality; -20% Enemy Troops ATK. |
| Initiated rally | Inata + Tormund + Vesaryon | +25% Troops ATK; +50% Troops HP; +25% Troops DEF; -20% Enemy DMG; +20% attack-triggered stun chance. |
| Joiner rally | Platos | +20% Troops DMG taken reduction (best pure mitigation join). |
| Joiner rally | Devilian | +25% Troops DEF; +16% rally-attack DEF; +25% Troops Lethality (durable counter-pressure pick). |
| Joiner rally | Inata | +25% Troops HP; +25% Troops ATK (balanced hold + damage contribution). |

### Bomber Defense Matrix

#### Purpose: Defense/Hold
Purpose note: bomber-led defensive setups that absorb burst and maintain counter-pressure uptime.

| Rally role | Multiple combinations | Overall boost applied to rally |
|---|---|---|
| Initiated rally | Gimes + Platos + Iwado | +40% Troops DMG taken reduction; +37% Troops HP; +14% Troops DEF; -20% Enemy Troops Lethality. |
| Initiated rally | Tormund + Platos + Gerd | +50% Troops DEF; +25% Troops HP; +20% Troops DMG taken reduction; -20% Enemy Troops ATK; +20% attack-triggered stun chance. |
| Initiated rally | Gimes + Devilian + Vesaryon | +25% Troops HP; +20% Troops DMG taken reduction; +25% Troops DEF; +16% rally-attack DEF; +25% Troops Lethality; -20% Enemy DMG. |
| Joiner rally | Gimes | +25% Troops HP; +20% Troops DMG taken reduction (highest repeat-value defensive joiner). |
| Joiner rally | Tormund | +25% Troops DEF; +25% Troops HP; +20% attack-triggered stun chance (frontline stabilizer). |
| Joiner rally | Samir | +14% Troops ATK; +12% Troops Lethality; -20% Enemy Troops HP (defensive counter-pressure joiner). |

## Notes on Conditional Skills
- Lofili `Tactical Move` is proc-based (50% chance), so it is listed as a spike modifier and not folded into deterministic totals.
- Stun effects (Phoenix/Tormund/Terry line) are control value and not converted into equivalent percentage damage.
- "While defending" equipment War skills are not auto-counted unless the specific battle state is defensive.