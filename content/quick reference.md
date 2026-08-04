---
tags:
  - Version2
  - Handbook
  - Reference
---
# Quick Reference

## Roll & Difficulty *(Ch1 §1–2)*

- **Every check:** roll 3 dice from the relevant Pool, sum them.
- **Pool Level** (0–9) = sum of die tiers: d4=0, d6=1, d8=2, d10=3. **Expected Roll = 7.5 + Pool Level.**
- **Bands:** below Low Bar = **Miss** · between bars = **Blocked** · at/above High Bar = **Hit**. Default **Margin = 3**
- **SDC** (world vs. you) from party Expected Rolls. **PDC** (you vs. world): Low Bar = 4 + ⌈Level÷2⌉ + Practitioner Bonus (Ch2 §2 table); High Bar = Low + 3. Level-Up Baseline (Ch2 §1) + Practitioner table add further bonus on top (Ch1 §2).
- **Pool Roll Bonus:** flat bonus added directly to a roll made with your Practitioner-leaning Pool (Might for Wielder, Verve for Caster, either for Shaper). Sourced from both the Level-Up Baseline (Ch2 §1) and your Practitioner table (Ch2 §2), stacking. This is the lever that exists specifically to keep pace with PDC's growth.

## Resource Pools *(Ch2 §3)*

| Pool | Governs |
|---|---|
| Blood | Health, survival |
| Might | Strength, willpower |
| Verve | Attunement, arcane |

- Two layers: **3-die slot pool** (permanent) + **Pips** (spendable, refreshes).
- **Default Resource Protection:** Blood shielded — spend Might/Verve 1-for-1 to stop Blood damage. Some Legacies invert this.
- **Die-stepping:** step count/level set by the Level-Up Baseline (Ch2 §1), not flat anymore. Cost d4→d6 = 1 Pip, d6→d8 = 2, d8→d10 = 3.
- **Pool Pip Bonus:** Level-Up Baseline + Practitioner table (Ch2 §2) both add to your Pip Cap, stacking.

## Practitioner Type *(Ch2 §2)*

| Type | Lean | Default Speed | Speed-roll Pool |
|---|---|---|---|
| Caster | Verve | 2 | Verve |
| Wielder | Might | 3 | Might |
| Shaper | Both | 3 | Choose each encounter |

## Skills *(Ch3 §2)* — 9, assigned once to a Pool, no inherent bonus

Fortitude · Grit · Instinct · Force · Attunement · Insight · Focus · Charisma · Craft

**Favored Skills:** pick 2 (after Pool assignment + Practitioner Type). **Spend 1 Pip** to add your current Favored Skill Bonus (Ch2 §1) to a roll using one — active, not passive, specifically so it doesn't silently stack with Pool Roll Bonus for free.

## Approaches *(Ch3 §3)* — chosen per action, feeds Speed swing

| Flourish | Wit | Calculation | Passion | Charm | Resolve | Guile | Nerve |
|---|---|---|---|---|---|---|---|
| 2 | 4 | 1 | 6 | 2 | 5 | 2 | 4 |

## Ability Types *(Ch3 §1)* — also feeds Speed swing

| Harmony | Sense | Burst | Creation |
|---|---|---|---|
| 4 | 3 | 2 | 1 |

**Per action: Speed swing = Type value + Approach value.** 2 actions/turn → both swings stack into next round.

## Turn Order *(Ch3 §4)*

- **Baseline Speed** = Level + Practitioner default + element's speed read (not yet formalized). Level-Up Baseline (Ch2 §1) + Practitioner table (Ch2 §2) add further Speed bonus on top, stacking.
- **Once per encounter:** roll Speed (Pool per Practitioner Type) + Baseline + assigned-Skill tally. Sets round 1 only.
- Single queue, high → low, locks each round. **Ties:** roll highest Pool, high wins.
- **Speed-for-Action Trade:** 10+ above the round's highest → spend 10 Speed for an extra action (feeds next round's swing).

## Action Economy *(Ch3 §5)*

- **2 actions/turn**, flat, no scaling. Movement free but revocable.
- **Reaction:** flat Speed threshold; +1 more if above round average.
- **Tandem/Swap-in:** assist spends a reaction; their die replaces the actor's lowest die if higher.

## Crisis *(Ch3 §6)*

All 3 Pools at 0 Pips → **3d4/round**. Die only if all three show **different values** (37.5%/round, flat at every tier).

## Recovery Die *(Ch3 §7)*

1/player, shared, tied to Highlight/Flaw. Size by scene tension: **None → d4 → d6 → d8 → d10**. Half-pip top-up only at the two hardest tiers. Resets every scene.

## Power Scale & Flight *(Ch2 §6, Ch3 §8–9)*

| Tier | Levels | Flight |
|---|---|---|
| Nascent | 1–2 | Ground |
| Kindled | 3–4 | Ground |
| Skyborn | 5–6 | + Low Sky |
| Ascendant | 7–8 | + High Sky |
| Sovereign | 9–10 | All bands + Resistance + Metaphysical Weight |

Band mismatch = step-up/PDC penalty for the grounded side, not a wall. Flight gear works early but drains Pips below-tier (soft tax); Sprite Bond eases it.

## Resistance *(Ch2 §9)* — unlocks Level 5, not Sovereign

| Level | Penalty to incoming rolls | Elements covered |
|---|---|---|
| 5 | −1 | Your bonded element |
| 7 | −2 | + 1 encountered element |
| 9 | −3 | + 1 more encountered element |

Not immunity — a resisted Use still lands, just at a real disadvantage.

## Experience *(Ch2 §4)*

Up to 5 Experiences, 1 tagged per success. Growth cost 3/5/7 notches per tier → privilege + free step-up/scene + 1 milestone. 5 milestones = level (placeholder number).

## Identity *(Ch2 §7)* — unlocks Level 3

9 listed options, each names a resource/mechanic. **None are numerically defined** — a GM call is required before play.

---

**Still a placeholder:** the element-to-Speed read (Fast +2 / Average +0 / Slow −2) used for the test characters — everything else that was a placeholder as of earlier passes (PDC formula, Pip Cap growth, Pool Roll Bonus) is now real, official, and documented above. All 12 test-character sheets have been recomputed against the current formulas twice now — see `Characters/0. Build Conventions & Rules Gaps Found.md` for what's still outstanding, including the new stacking question Pool Roll Bonus raised with Favored Skill Bonus.
