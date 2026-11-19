# Claim Raven plugins for Claude Code and Codex

These plugins connect Claude Code and Codex to [Claim Raven](https://claimraven.com), a tool that helps veterans with VA disability claims. Each plugin does two things:

1. It adds the Claim Raven connection (Claim Raven Connect, `https://mcp.claimraven.com/mcp`), so you only have to sign in to Claim Raven once.
2. It adds short step-by-step guides ("skills") for common jobs, so the AI checks your Claim Raven account and official VA sources instead of guessing.

Every plugin only reads. None of them can change, upload, delete, submit or send anything.

## The plugins

| Plugin | For | What it helps with |
|---|---|---|
| `claim-raven` | Veterans with a Claim Raven account (Free included) | Check a VA decision letter, prepare for a C&P exam, draft a personal statement, plan a secondary condition claim, see what is due next, research a condition |
| `claim-raven-pro-research` | Accredited representatives and attorneys with a Claim Raven Pro account | Board of Veterans' Appeals case research, VA authority briefs, condition theory research. Research only: no client records pass through this connection. |
| `claim-raven-research` | Anyone, no account | Look up the exact text of a VA rule (38 CFR, 38 U.S.C., the M21 manuals) and find the VA law on a question |

## Install in Claude Code

```
claude plugin marketplace add claimraven/claim-raven-plugins
claude plugin install claim-raven@claim-raven
```

Use `claim-raven-pro-research@claim-raven` or `claim-raven-research@claim-raven` in the second line for the other plugins. Then type `/mcp` in Claude Code, choose the Claim Raven server and select Authenticate. A Claim Raven page opens where you sign in and choose what the AI can read. The no-account plugin needs no sign-in.

## Install in Codex

```
codex plugin marketplace add claimraven/claim-raven-plugins
codex plugin add claim-raven@claim-raven
```

Codex asks you to sign in to Claim Raven the first time it connects.

## Using Claude on the website, desktop or phone

Those apps add Claim Raven as a connector instead of a plugin. The steps are at [claimraven.com/mcp](https://claimraven.com/mcp).

## What to ask

- "Help me understand my VA decision letter from October."
- "I have a C&P exam for migraines next week. Help me prepare."
- "Can I claim sleep apnea secondary to my PTSD? What would I need?"
- "What is due next on my claim?"
- "What does 38 CFR 3.310 say?"

## Privacy and safety

- You choose what the AI can read on a Claim Raven page when you connect, and you can disconnect at any time in Claim Raven Settings, Connected AI, where every read is listed.
- What the AI reads goes to the company that runs your AI app, under that company's terms. Use a personal AI account, not a work one.
- Social Security numbers, VA file numbers and dates of birth are hidden before anything leaves Claim Raven. Hiding is automatic and can miss some.
- This repository holds only plugin settings and instructions. It contains no code that runs on your computer, no keys and no personal information.
- Claim Raven privacy policy: [claimraven.com/privacy-policy](https://claimraven.com/privacy-policy). Terms: [claimraven.com/terms-of-service](https://claimraven.com/terms-of-service).

Claim Raven is independent from VA. Answers are general information, not legal or medical advice. Check important points with a VA-accredited representative.

## Help

Email help@claimraven.com. Documentation: [claimraven.com/docs/mcp](https://claimraven.com/docs/mcp).

## License

MIT. See [LICENSE](LICENSE).
