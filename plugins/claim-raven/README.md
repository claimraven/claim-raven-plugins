# Claim Raven

Connect your own [Claim Raven](https://claimraven.com) workspace to Claude Code or Codex, read only. Ask about your tracked conditions, your VA.gov copy (ratings, claims, letters and payments), your deadlines and saved Claim Raven reports, look up exact 38 CFR, 38 U.S.C. and M21 text, research conditions, and study Board of Veterans' Appeals decisions.

## Included skills

- `check-decision-letter`: break down a VA decision letter, missing evidence, rules applied, and review options with dates.
- `prepare-for-cp-exam`: review exam criteria and build talking points in your own words.
- `prepare-personal-statement`: plan and check a first-person lay statement against selected evidence pages.
- `secondary-condition-claim`: check 38 CFR 3.310 rules, existing evidence, and questions for your doctor.
- `whats-due-next`: list upcoming deadlines, tasks, reminders, and open VA claims in soonest-first order.
- `research-condition`: look up service-connection pathways, rating criteria, and Board decision patterns.

## Setup

Install in Claude Code:

```
/plugin install claim-raven --marketplace claimraven/claim-raven-plugins
```

Then sign in once through Claim Raven Connect (`https://mcp.claimraven.com/mcp`) and choose which data classes the AI may read. The connection only reads; it cannot edit, upload, delete, or submit anything, and you can disconnect at any time in Claim Raven Settings, Connected AI.

Claim Raven is independent from VA. Answers are general information, not legal or medical advice.

- Documentation: [claimraven.com/docs/mcp](https://claimraven.com/docs/mcp)
- Privacy policy: [claimraven.com/privacy-policy](https://claimraven.com/privacy-policy)
- Terms of service: [claimraven.com/terms-of-service](https://claimraven.com/terms-of-service)
- Support: help@claimraven.com
