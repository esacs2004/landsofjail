# Rally Operations Playbook

Last updated: 2026-06-25
Scope: All rally-based gameplay in Lands of Jail (Trial Cage, alliance war rallies, event rallies, objective rallies)
Audience: Rally leaders, joiners, and alliance coordinators
Supplemental context source: Lands of Jail Unofficial Wiki: https://landsofjail.miraheze.org/wiki/Main_Page

## 1) Source and Accuracy Rules
- Use the community wiki as a fast reference for terminology, build ideas, and patch timeline context.
- Validate rally-critical decisions using current in-game evidence first:
- Hero panel screenshots.
- Battle reports.
- Alliance test runs.
- If wiki guidance and live results conflict, prioritize live tested results.

## 2) Universal Rally Build Rules
- One hero per slot is the default and recommended rule.
- Do not overload a single slot with multiple heroes.
- Observed rally UI currently shows 3 hero slots plus 1 separate Companion Power Armor slot.
- Type-balance lock for rally slots: use exactly one Shooter, one Bomber, and one Shieldbearer across S1-S3.
- Keep role balance across slots whenever possible:
- DPS pressure.
- Utility/control.
- Survivability/support.
- Avoid duplicate hero assignment across slots unless the mode explicitly benefits from it.

## 3) Rally Roles
- Rally Leader:
- Sets target, launch timing, and formation intent.
- Defines joiner type mix and troop range.
- Calls phase timing (burst windows, skill windows, join order).
- Rally Joiner:
- Sends correct hero type and troop count on call.
- Confirms readiness before launch.
- Holds or sends based on leader phase timing, not personal cadence.

## 4) Hero-Type Priority Framework
- Shooter (gun icon): burst pressure and fast target deletion.
- Bomber (grenade icon): AoE pressure and defense breaking.
- Shieldbearer (shield icon): frontline stability and attrition resistance.

Use mode context to weight priority:
- Damage-race objectives: Shooter/Bomber weighted higher.
- Sustain or counter-pressure windows: include Shieldbearer for stability.

## 5) Troop Count Framework
- Trial Cage baseline: 50k to 70k per joiner march.
- For other modes, use leader-declared bands based on objective type and enemy profile.
- Increase march size only when expected value exceeds added risk/cost.
- Reduce march size when preserving tempo, resources, or march availability is higher value.

## 6) Formation, Core, and Felon Timing
- Core reset discipline:
- Reset core before high-value join windows where burst conversion matters.
- Felon selection by target profile:
- Scorpion: melee burst orientation.
- Cobra: ranged AoE orientation.
- Positioning multipliers (for modes that provide seat/position bonuses):
- Prioritize uptime on damage multipliers over convenience positioning.

## 7) War Skill Synchronization Rules
- Stack war-skill windows with hero burst windows.
- Trigger skill windows on leader phase calls.
- Avoid unsynchronized early casts that burn cooldowns before damage windows.
- Matrix generation default: evaluate rally-matrix totals using highest documented War skill values unless a section explicitly states otherwise.

## 8) Mode Modules

### Trial Cage
- Follow one hero per slot strictly.
- 50k to 70k joiner baseline unless leader overrides.
- Time joins to seat multiplier and burst phases.

### Alliance War Rally
- Prioritize target-based hero-type mix (offense, sustain, anti-burst).
- Use join order discipline to avoid fragmented arrival waves.

### Event/Objectives Rally
- Start with baseline mix, then adjust by report feedback each cycle.
- Focus on repeatable timing and conversion, not one-off overcommit.

## 9) Slot Purpose by Rally Objective

Use these slot-purpose definitions when building a rally. Current observed rally UI shows 3 hero slots. Companion Power Armor should be treated as a separate support layer, not a fourth hero slot.

### Damage-Race Rally
Purpose note: maximize time-to-kill and burst conversion to end the fight before enemy sustain patterns matter.

Examples:
- Trial Cage.
- Boss/event damage races.

Slot order:
- Slot 1: Primary carry.
	- Highest burst or best boss-conversion hero.
- Slot 2: Damage amplifier.
	- Hero that adds ATK, Lethality, crit, or damage-taken increase.
- Slot 3: Secondary DPS.
	- Strong Shooter or Bomber follow-up damage.

Companion Power Armor:
- Use to reinforce burst timing or survivability depending on the target.

Default weighting:
- Shooter/Bomber priority first.
- Shieldbearer only if needed to keep uptime stable.

Example assignment (assuming highest documented War skill tier for each hero):
- Slot 1: Inata, Shooter, primary carry.
	- Why here: strongest clean shooter carry for burst-led damage race.
	- Combat-relevant War skills applied to march:
	- Siege Tactics: +25% Troops ATK.
	- Emergency Construction: +25% Troops HP.
	- Ignored for rally damage: Grand Wisdom (Research Speed).
- Slot 2: Lunarl, Bomber, damage amplifier.
	- Why here: adds deterministic offensive scaling for fast target deletion.
	- Combat-relevant War skills applied to march:
	- Insight: +25% Troops DMG dealt.
	- Assassination: +25% Troops Lethality.
- Slot 3: Phoenix, Shieldbearer, secondary DPS/support.
	- Why here: contributes both march-wide damage and control while preserving one-of-each type rule.
	- Combat-relevant War skills applied to march:
	- Crush Defense: +25% Troops DMG dealt.
	- Unyielding Spirit: +25% Troops HP.
	- Earth-Shaking Hammer: 20% chance to stun target for 1 round when attacking.

Combined march-wide boost from these 3 assigned heroes:
- +25% Troops ATK.
- +50% Troops DMG dealt.
- +25% Troops Lethality.
- +50% Troops HP.
- 20% attack-triggered stun chance.

Interpretation:
- Inata carries primary burst.
- Lunarl supplies deterministic offensive amplification.
- Phoenix adds durability and control so the damage-race line keeps uptime.

Assumption rule for this example:
- Each listed War skill is evaluated at its highest documented progression value.
- Only combat-relevant War skills that explicitly affect allied troops in march are counted in the total.
- Non-combat skills (research, construction, training) are excluded from rally math.
- Hero-type stat panels (for example Shooter ATK or Shieldbearer DEF totals) are treated as hero-specific build context, not added here as shared march-wide War skill buffs.

Small comparison table: highest offensive 3-slot trios from current documented roster

Method used for this table:
- Count only deterministic, march-wide offensive combat buffs.
- Assume each included War skill is at its highest documented progression value.
- Include: Troops ATK, Troops DMG dealt, Troops Lethality, and explicit enemy-damage-intake style offensive modifiers when clearly march-wide.
- Exclude: HP, DEF, stun, research, construction, training, gathering, and unclear proc-based math from the ranking column.
- Exclude Tyronn from ranking because current file is still pre-claim/provisional rather than a normal roster-state profile.

| Rank | Trio | Deterministic offensive buffs counted | Why it ranks here |
|---|---|---|---|
| 1 | Inata + Lunarl + Phoenix | +25% Troops ATK ; +50% Troops DMG dealt ; +25% Troops Lethality | Strongest clean one-of-each offensive trio in the current documented pool. |
| 2 | Vivian + Devilian + Phoenix | +25% Troops ATK ; +25% Troops DMG dealt ; +25% Troops Lethality | High pressure with better defensive stability through Devilian and Phoenix. |
| 3 | Lofili + Lunarl + Phoenix | +25% Troops DMG dealt ; +25% Troops Lethality ; +25% Troops HP | Lower deterministic ATK line but strong proc-upside burst from Lofili. |

Near-miss note:
- Lofili is a serious candidate because Tactical Move is offensively powerful, but its current wording is proc-based rather than a flat deterministic march buff, so it is excluded from the ranked table above.
- Samir and Flameborne also add offensive pressure through enemy-side debuffs, but their current documented values produce weaker clean deterministic totals than the top three trios above.

### Breakthrough Rally
Purpose note: crack high-defense targets by combining defense shred, pressure scaling, and conversion into frontline collapse.

Examples:
- High-defense target.
- Fortified enemy formation.
- Rally where front-line collapse is the win condition.

Slot order:
- Slot 1: Front-break carry.
	- Best single-target or AoE pressure hero.
- Slot 2: Defense shred / damage-taken amplifier.
	- Hero that lowers DEF or increases incoming damage.
- Slot 3: AoE breaker.
	- Bomber-type pressure to break clustered defense.

Companion Power Armor:
- Use as stability or finishing support based on whether the target breaks early or holds.

Default weighting:
- Keep one-of-each hero types while prioritizing Bomber pressure.
- Never duplicate a hero type across S1-S3.

Example assignment (assuming highest documented War skill tier for each hero):
- Slot 1: Lofili, Shooter, front-break carry.
	- Why here: combines direct march offense with enemy-HP suppression for faster collapse.
	- Combat-relevant War skills applied to march:
	- Strategic Insight: +25% Troops ATK.
	- Tactical Move: 50% chance to increase Troops DMG by 50% when attacking (proc-based).
- Slot 2: Flameborne, Bomber, defense shred.
	- Why here: provides clean enemy-defense reduction that improves whole-rally conversion.
	- Combat-relevant War skills applied to march:
	- Flameborne Protocol: -20% Enemy Troops DEF.
- Slot 3: Phoenix, Shieldbearer, AoE breaker/support.
	- Why here: closes breakthrough setup with deterministic damage plus control and durability.
	- Combat-relevant War skills applied to march:
	- Crush Defense: +25% Troops DMG dealt.
	- Unyielding Spirit: +25% Troops HP.
	- Earth-Shaking Hammer: 20% chance to stun target for 1 round when attacking.

Combined march-wide boost from these 3 assigned heroes:
- +25% Troops ATK.
- +25% Troops DMG dealt.
- +25% Troops HP.
- -20% Enemy Troops DEF.
- 20% attack-triggered stun chance.
- Proc-based spike: 50% chance to gain +50% Troops DMG when attacking.

Interpretation:
- Flameborne opens the target by reducing enemy DEF.
- Lofili and Phoenix convert the opening into burst plus safer uptime.

### Sustain / Hold Rally
Purpose note: outlast the opponent through durability and mitigation so your rally keeps uptime across repeated exchanges.

Examples:
- Extended contest windows.
- Counter-pressure scenarios.
- Objectives where surviving through repeated exchanges matters more than first-burst damage.

Slot order:
- Slot 1: Anchor tank.
	- Shieldbearer or most durable uptime hero.
- Slot 2: Team sustain.
	- Shield, healing, mitigation, or anti-burst utility.
- Slot 3: Reliable DPS.
	- Damage hero that still performs in longer windows.

Companion Power Armor:
- Use as mitigation or uptime support before adding extra aggression.

Default weighting:
- Shieldbearer first.
- Then balanced Bomber/Shooter support depending on enemy profile.

Example assignment (assuming highest documented War skill tier for each hero):
- Slot 1: Platos, Shooter, anchor tank.
	- Why here: reliable incoming-damage reduction for long windows.
	- Combat-relevant War skills applied to march:
	- Adaptability: +20% Troops DMG taken reduction.
- Slot 2: Gimes, Bomber, team sustain.
	- Why here: adds both raw HP and incoming-damage mitigation.
	- Combat-relevant War skills applied to march:
	- Robust Build: +25% Troops HP.
	- Agile Footwork: +20% Troops DMG taken reduction.
- Slot 3: Iwado, Shieldbearer, reliable DPS/support.
	- Why here: provides extra durability plus enemy-side pressure for attrition fights.
	- Combat-relevant War skills applied to march:
	- Iron Prison Encirclement: +14% Troops DEF and +12% Troops HP.
	- Shattering Strike: -20% Enemy Troops Lethality.

Combined march-wide boost from these 3 assigned heroes:
- +25% Troops DEF.
- +37% Troops HP.
- +40% Troops DMG taken reduction.
- -20% Enemy Troops Lethality.

Interpretation:
- Platos plus Gimes creates a durable sustain shell for long exchanges.
- Iwado adds extra frontline toughness and reduces enemy lethality to improve hold consistency.

### Utility / Efficiency Rally
Purpose note: deliver stable, repeatable clears with controlled losses when consistency is more valuable than peak burst.

Examples:
- Event clears.
- Resource or tempo-sensitive objective chains.
- Modes where repeatability and march efficiency are more important than max spike damage.

Slot order:
- Slot 1: Reliable clear hero.
	- Hero with consistent output and low setup dependency.
- Slot 2: March-efficiency support.
	- Speed, stamina, or event-utility specialist.
- Slot 3: Damage stabilizer.
	- Enough DPS to keep clears efficient.

Companion Power Armor:
- Use based on event mechanic rather than generic power ranking.

Default weighting:
- Use the minimum damage mix that clears reliably.
- Favor repeatability over flashy burst.

Example assignment (assuming highest documented War skill tier for each hero):
- Slot 1: Inata, Shooter, reliable clear hero.
	- Why here: simple, deterministic buffs that work in nearly every cycle.
	- Combat-relevant War skills applied to march:
	- Siege Tactics: +25% Troops ATK.
	- Emergency Construction: +25% Troops HP.

- Slot 2: Gimes, Bomber, march-efficiency support.
	- Why here: improves repeatability by reducing losses over chained objectives.
	- Combat-relevant War skills applied to march:
	- Robust Build: +25% Troops HP.
	- Agile Footwork: +20% Troops DMG taken reduction.
- Slot 3: Phoenix, Shieldbearer, damage stabilizer.
	- Why here: preserves clear speed while adding control and extra survivability.
	- Combat-relevant War skills applied to march:
	- Crush Defense: +25% Troops DMG dealt.
	- Unyielding Spirit: +25% Troops HP.
	- Earth-Shaking Hammer: 20% chance to stun target for 1 round when attacking.

Combined march-wide boost from these 3 assigned heroes:
- +25% Troops ATK.
- +25% Troops DMG dealt.
- +75% Troops HP.
- +20% Troops DMG taken reduction.
- 20% attack-triggered stun chance.

Interpretation:
- Inata keeps baseline damage consistent.
- Gimes lowers wipe risk across repeated objective chains.
- Phoenix keeps utility setup from losing conversion speed while adding control.

## 10) Common Mistakes to Avoid
- Overloading one slot instead of one hero per slot.
- Duplicating a hero type across S1-S3 (must be one Shooter, one Bomber, one Shieldbearer).
- Ignoring troop-count guidance for the objective.
- Missing reset/skill timing windows.
- Joining out of phase with leader calls.
- Using outdated builds without revalidation after patch/meta shifts.

## 11) Alliance Coordination SOP
- Pre-call:
- Leader posts target, launch time, required type mix, and troop band.
- Joiners confirm hero type and troop count.
- Live execution:
- Joiners hold for phase call and send in declared order.
- Post-rally:
- Record results and update next-wave settings.
- Track what changed (type mix, timing, skill window, troop size).

## 12) Rally Call Templates

Leader template:

```text
[RALLY CALL]
Mode:
Target:
Launch time (server):
Leader hero + type:
Rally objective: Damage race / Breakthrough / Sustain / Utility
Slot purposes:
S1:
S2:
S3:
Companion Power Armor:
Required joiner types:
Per-joiner troop band:
Rule: one hero per slot
Rule: exactly one Shooter + one Bomber + one Shieldbearer across S1-S3
Duplicate hero policy:
Core reset required: Yes/No
Felon focus: Scorpion/Cobra/Other
War skill timing: phase call only
```

Joiner template:

```text
[JOIN CONFIRM]
Hero:
Hero type:
Troops:
Core reset done: Yes/No
Ready by:
```

## 13) Quick Checklist
- Correct mode selected.
- Correct rally objective selected.
- Correct target selected.
- One hero per slot confirmed.
- One Shooter + one Bomber + one Shieldbearer across S1-S3 confirmed.
- Slot purpose assignments confirmed.
- Companion Power Armor purpose confirmed.
- Hero type mix validated.
- Troop band aligned.
- Core reset complete.
- Felon selection complete.
- War skills ready and synchronized.
- Join timing synced to leader phase call.
