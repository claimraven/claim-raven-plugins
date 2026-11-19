---
name: check-presumptive
description: Use when someone asks whether a condition is presumptive for VA, or which presumptions fit where and when they served, for example the PACT Act and burn pits, Agent Orange, the Gulf War, radiation or Camp Lejeune. Uses Claim Raven's free research connection, no account needed.
---

# Check presumptive conditions

1. Ask for the condition and where and when the person served, if they have not said.
2. Call `check_presumptive_conditions` with the `condition`, the `place`, or both.
3. For each matching condition, say whether it is a presumption. Call it presumptive only when its rule type is presumption. A special review condition is something VA decides case by case, and "check exact diagnosis" means the exact diagnosis decides which rule applies.
4. Give the qualifying service dates and places, how VA handles the condition, what is still needed, and the citation with its link. Quote only what it returns.
5. If the answer asks to confirm the diagnosis, a match is not exactly what was asked (for example, type 1 diabetes is not type 2, and a throat cancer may or may not be a neck cancer). Ask the person to confirm the exact diagnosis before relying on it.
6. If nothing matches, read its coverage note: other presumptions exist (for example ALS), and `find_va_authority` can find the rule for those.

A presumption covers only the link to service. Evidence of the condition and service records are still needed. This is general information from public VA law, not a reading of anyone's file and not legal advice. A free Claim Raven account adds your own claim, your VA.gov copy and condition research: https://claimraven.com/mcp
