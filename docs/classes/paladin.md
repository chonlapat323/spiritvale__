# Paladin

From Knight, Lv 76-80, class-change at Sanctum of Light. Max job level 50.
"Fuses shield and sanctity, protecting allies while smiting the wicked with blessed force."

Full skill list: High Guard, Holy Shield, Aegis of Light, Judgement Blade, Divine Punishment, Grand Cross, Life Bond, Sanctify, Defiance Aura, Vitality Aura, Conviction Aura, Shield Bash, Shield Throw, Faith, Sacrifice, Consecration, Gryphon Riding

Knight (base class) skills for reference: Taunt, Spear Mastery, Shield Mastery, Endure, Piercing Flurry, Fortify, Twohand Parry, Impale, Reflect Shield, Increased Regeneration, Air Cutter, Spear Quicken, Weapon Throw, Counter Stance.

## Post-Patch Changes
See [../patch-notes.md](../patch-notes.md) for the raw list. Summary: Sacrifice reworked into offense, Shield skills +30% dmg (buff); Consecration, Holy Shield, Judgement Blade, Grand Cross, Oathbreaker all lost offensive/utility value (nerf). Net effect: pushed toward pure shield-tank identity, but retains real damage via Sacrifice.

## Confirmed Skill Chain
Requirement links confirm: **Faith → Holy Shield → Shield Bash → Shield Throw**, with **Sacrifice** branching off Faith directly.

| Skill | Max Lv | Type | Cooldown | Mana Cost | Requirement | Notes |
|---|---|---|---|---|---|---|
| Holy Shield | 5 | Neutral | - | 20 | Faith Lv1+ | Grants Block + All Resistance (patch: All Resistance REMOVED, block only now) |
| Shield Bash | 5 | Neutral | 3s | 7 (+3/lv) | Holy Shield Lv1+ | "Charge, brace shield, lunge forth, crumble defenses" — one of the two "Shield skills" that got +30% dmg |
| Shield Throw | 10 | Neutral | n/a (not listed) | 5 (+2/lv) | Shield Bash Lv1+ | Multi-target throw; used by Cactus King (Lv40 boss), Goblin Warblade (Lv123) — the other +30% dmg target |
| Sacrifice | 5 | Neutral | - | 20 | Faith Lv1+ | See rework details below |

Note: wiki doesn't have real damage-scaling numbers yet for these (shows 0) — still early/incomplete data on the wiki itself, not just theorycraft on our end.

## Open Discrepancy: "Oathbreaker"
Patch notes mention an "Oathbreaker" skill (matk/str → block rework) that does NOT appear on the wiki's Paladin or Knight skill lists. Possibly a not-yet-documented skill, a hidden/quest-unlocked skill, or a wiki gap. Needs re-check once wiki updates.

## Wiki-vs-Patch Discrepancy: Sacrifice
**Wiki page (not yet updated to reflect patch):** Description: *"Offer your own HP to the divine, adding Holy damage to each of your blows"* — reads as a passive/on-hit self-buff (spend own HP for extra Holy dmg per attack).

**Patch notes (actual current behavior):** Reworked into a **single-target attack**, deals 5-10% of target's HP as damage, **ignores defense**, triggers hit effects.

This is a full mechanic change (sustain/on-hit passive → true-damage %HP-based nuke), not a tweak. The wiki is confirmed lagging behind the real patch state — treat wiki skill descriptions as potentially stale until cross-checked against patch notes.

### Damage basis: MAX HP, not current HP
User-reasoned correction: at best-case roll (10%/hit), 10 hits = exactly 100% = a clean kill. This only works if each hit is a fixed 10% of the target's **max** HP. If it scaled off *current* HP instead, each hit would only take 10% of whatever's left — asymptotically approaching but never mathematically reaching exactly 0 (Zeno's-paradox style), so "10 hits to kill" wouldn't resolve to a clean number.

→ **Practical implication: no need to front-load Sacrifice on high-HP targets** — it deals the same absolute damage regardless of when in the fight it's used, since it's a fixed % of the target's max HP each time.
→ Best case ~10 hits to kill (10%/hit), worst case ~20 hits (5%/hit), Sacrifice-only, ignoring cooldown/other damage sources/healing on the monster's side.

**Still unconfirmed, needs in-game test:** old wiki description said Sacrifice costs the caster's *own HP*. If that cost still applies post-rework, this isn't spammable without healing support (Life Bond etc.) — could make it risky against bosses.

## Reassessment
With Sacrifice now a defense-ignoring %HP nuke on top of the buffed Shield Bash/Throw combo, Paladin has more real offensive teeth post-patch than first assessed. Net tier: **A** — retains strong sustained tank utility plus a genuine execute/defense-ignore tool for high-DEF targets (bosses). See [../tier-list.md](../tier-list.md).

## Recommended Build: "Shield Breaker Tank"

**Skill priority order:**
1. Faith (root)
2. Holy Shield (unlocks Shield Bash; block only now, resist buff removed)
3. Shield Bash (max Lv5) — 3s CD, +30% dmg buff, spammable opener
4. Shield Throw (max Lv10) — AOE, +30% dmg buff, trash clear
5. Sacrifice (max Lv5) — main single-target DEF-ignore damage, usable any time (not current-HP dependent)
6. Life Bond — sustain, compensates for lost Consecration/Holy Shield sustain
7. One Aura (Vitality for survivability / Defiance for aggro / Conviction for damage — pick one, don't spread points)
8. High Guard / Aegis of Light — baseline defense filler

**Skip (nerfed past viability for point investment):** Judgement Blade, Grand Cross, Divine Punishment, Sanctify, Consecration, Gryphon Riding (utility mount, learn last if at all)

**Stats:** STR/VIT direct stats over %dmg-stacking gear — patch removed most global %dmg multiplier sources (Skill Damage cards, Weapon Element cards, reduced Potential), so flat stats now outvalue the old multiplier-stacking approach.

**Gear:** Prioritize STR/VIT/Block% rolls over Potential-value-heavy items.

**Rotation:**
- Solo/boss: Shield Bash (open) → Sacrifice (main dmg) → alternate on cooldown
- Trash/groups: Shield Throw primary, Shield Bash for stragglers
- Aura up at all times

**Unverified — test in-game:** Sacrifice's real HP cost (if any), exact SP cost per skill/level (no full cost table gathered yet, so this is a priority order, not a point-by-point budget).
